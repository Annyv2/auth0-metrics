# auth0-metrics

This library provides a module to track all frontend usage on auth0.com, it wraps Segment and sends the same data both to segment and our own endpoint.

## Installation

To install the dependencies, execute:

`npm install`



## Usage (local)
To build and run the library locally, you can run
`npm run dev`, that will let you include the library from http://localhost:9999/auth0-metrics.js, you can also test the methods included in http://localhost:9999/

## Usage (deploy)
To use it, you have to include the script which has been built, it is built with major, minor and fix versions to be able to granularly specify versioning. You can include either the complete or minified version.

For example, for version 1.3.7, the following files will be built:

```
metrics-1.js
metrics-1.3.js
metrics-1.3.7.js
metrics-1.min.js
metrics-1.3.min.js
metrics-1.3.7.min.js
```

Then you have to call the constructor with the correct dev/prod variables

`var metrics = new Auth0Metrics('segmentKey', 'dwhEndpoint', 'website');`

### Loader

A script that will asynchronously load `auth0-metrics.js` is also provided.

```html
<script src="auth0-metrics-loader.js"></script>
<script>
  metricsLib.load({
    segmentKey: 'segmentKey',
    dwhEndpoint: 'dwhEndpoint',
    label: 'website'
  });
</script>
```

Once loaded, an instance of `Auth0Metrics` will be available on `metricsLib`. Calls to public instance methods of `Auth0Metrics` on `metricsLib` will be silently ignored until then.

```js
// tracks the page if auth0-metrics.js has been loaded, otherwise the call is
// ignored and doesn't produce an error.
metricsLib.page();
```

If `auth0-metrics.js` has already been loaded, the script will not attempt load it again, and will simply create an instance of `Auth0Metrics` with the given configuration.

Using the loader may also be desired when loading `auth0-metrics.js` synchronously. If there's an exception during the instantiation of `Auth0Metrics`, the stubs methods will still be in place and calls like the one above to `page` won't throw.

```html
<script src="auth0-metrics.js"></script>
<script src="auth0-metrics-loader.js"></script>
<script>
  metricsLib.load({
    segmentKey: 'segmentKey',
    dwhEndpoint: 'dwhEndpoint',
    label: 'website'
  });
</script>
```

Contrast the previous snippet with the following that instantiates `Auth0Metrics` directly.

```html
<script src="auth0-metrics.js"></script>
<script>
  var metricsLib = new Auth0Metrics('segmentKey', 'dwhEndpoint', 'website');
</script>
```

If the instantiation doesn't succeed, trying to call a method on `metricsLib` will throw because it is `undefined` and may break the behavior of your site.

## API


### .setUserId(uid)
Sets the userId of the currently connected client
#### Parameters
* `uid` user id to set

### .page(callback)
Sends information of the current page to track it
#### Parameters
* `callback` a function to call after sending this event

### .track(event, data, callback)
Sends information of a custom event to track.
#### Parameters
* `event` a string with the name of the event to track
* `data` an object with any data we need to pass
* `callback` a function to call after sending this event

### .identify(id, traits, callback)
Sends information of an identification (login/signup) to track.
> NOTE: This method's signature does not fully pair with Segment's [analytics.js](https://segment.com/docs/libraries/analytics.js/#identify). You can proxy directly to Segment by doing `metricsLib.segment().identify()` instead.

#### Parameters
* `id` user id to identify the current user to
* `traits` additional properties to set to the user
* `callback` a function to call after sending this event

You can omit the user `id` if you want to associate `traits` with the currently identified user, anonymous or not. You can also omit `traits` if all you want to do is associate an `id`. Finally, `callback` is optional and can always be omitted.

### .alias(id, callback)
Sends an alias (renaming a previous id to a new one).
#### Parameters
* `id` new user id to map to, the previous id will be taken from the cookie.
* `callback` a function to call after sending this event

### .traits()
Traits (additional properties) of the current user

### .ready(cb)
Executes a callback when segment finishes loading.
#### Parameters
* `cb` function to run when segment finishes loading.
