## [1.4.0] - 2015-08-14

### Fixed

- [] more fixes (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/3f2c94d969ab675df9492270bc5eb540880033e0
- [] Add tests and fix indentation (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/78d59eb81264653a63eaa84c94433a3deee88c08
- [] Move to use _.isPlainObject() cause otherwise asumes functions and other structures are objects when we don't want them to (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/adea305f91df7a6bd06573f4635b5e7cd1187873
- [] Add metrics.page uuid property sent on each call (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/7f8b673002038d30a27c262abe4e713ae7ab41ee
- [] Release: 1.3.1 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/b6d08cb6ad47e9f84cc30e9df5aae2d3bb759def
- [] Fix tests indentation (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/b54c5b71b255f890b9e2e1127922159c4b5f0e6d
- [] Fix demo example (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/76e60b9dfd4fcf8b5c130d56312d625895319b3c
- [] Add event uuid to allow x-reference with segment (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/5c104a17cdcd039014d5ab8d08b0674c315353d2
- [] Update segment error message (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/b30363dd65b185e147fac1c126e8cd2ed81a5fd8
- [] Fix tests with patch of zuul-ngrok (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/c36b3bb689917781808880e4c669a80fce3850e6
- [] Fix tests (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/263a313354b175634d0ff6c459dcc52458e79864
- [] No more hacks we don't like it (`Martin Gontovnikas`)
  https://github.com/auth0/metrics/commit/b90b2d3674947ac434dc3ad7d11801600b155fba
- [] Gonto hacking at work (`Martin Gontovnikas`)
  https://github.com/auth0/metrics/commit/5c2e9e44cb6fcf9bf7677753306fdfc0fa557e57
- [] Release: 1.3.0 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/01a4ad3d77dd8791dfe18907b731fa8a7da9adba
- [] Update zuul (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/5c86decc76854559a9aa439f778c3316c652f277
- [] Fixed problem with Cookies :D finally (`Martin Gontovnikas`)
  https://github.com/auth0/metrics/commit/973f74d8ccc01f936300b623debab2f00c15be57
- [] Release: 1.2.1 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/900944faa89fa068c9d589f828b7ea313e14030b
- [] Merge pull request #8 from auth0/loader-improvements (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/658d995754e4c02a899d4e68cd0f86e17fb76c0e
- [] Include a minified loader script in the build (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/a64713cf2297e762a5f30d5a7f861986b0ca638b
- [] Ensure there are stub methods for the loader (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/d52003889b819c0cb0776191e5907240de48a2db
- [] Release: 1.2.0 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/7e6c722ec23acafb4f3cb03c6ce7bf73bd7532de
- [] Attempt to properly purge loader scripts (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4d9f8efc23d73f84d151727a8bf57f092e8d7e52
- [] Release: 1.1.2 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/2bdf213a9349af94696086985d561282de30e839
- [] Fix jsdoc task src (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/2ea23aba3350732f1ef35a1860cf0616e2c2d866
- [] Release: 1.1.1 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/a8c9ab4d154db393af20faba2223c03a3f71a134
- [] Merge pull request #7 from auth0/track-segment-error (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e4379db04f477afc8a0845916573b179a5e4ea32
- [] Track segment error also for alias and identify (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/3aedacaeb285e92762f7267dbad2919bf66a10af
- [] Wrap in try/catch the call to track segment-error (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/654bf0270ef9e40a0692e8168eb0f97dd5e3bf49
- [] Track segment errors when calling track and page (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4fc2f867f89381266f4c19dd10097c6c9e5b7042
- [] Merge pull request #5 from auth0/loader-script (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/2ad136b89758469978bb372af8562623b2445501
- [] Document using the loader for the sync case (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/91ce153d35bf15fc9536f0c290d156afe38c7d5a
- [] Move jsdoc loader template from ./lib to ./support (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/eaf55711840bea61363598f7b8deb435d7b02863
- [] Doc loader script in README (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/fc8812d6936c7d11faa3d1adbc99d2a6b17cabb6
- [] Update error message when the loader fails (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/7929793a98e738280a1d51ce4943de576149dddb
- [] Update loader to take just a config object (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/1f6e8917fec70142ec47d1f0efed0848b8849229
- [] Little improvents of style to loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6e4621b4997ca479eecd43175c498feae993da1a
- [] Update cdn tasks to include the loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/c2fbf31e19afc2c4b246884df5f47fada6281f55
- [] Include loader script in the build process (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/ade66bd9c6d449b0db9dba143e844c215e3b0954
- [] Remove unused fastly grunt task (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6bd613ff15d33f4ab3459138802a0b60bd916dba
- [] Use ejs.renderFile when rendering loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4e7e81a0bb0a34adba4e4439b12f6c055ec2d859
- [] Some work to auto-generate the loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/a98a9d30deb5664cbb66fcde7d29b00bf9fc5bdc
- [] Release: 1.1.0 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e5ca29d1e5d7d1cfd4d5e7dfa7515cf39aa3bd2b
- [] Fixing bump command (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/5f0ebb3c37c09078a68c960ed2f257792db10af9
- [] Replace call to console.log with debug (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6911fe409a30b05577794252ceab788d79b12e4d
- [] Forgot to add lodash to test_harness.html (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/95bc9cc4215729e87562ca669e831d798f1ac24f
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/8202f5531fe6a6b4ee820deb31ca7620aebfa4b3
- [] Merge pull request #4 from auth0/anonymous-traits (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e388e183919efdf242bad481a611108811f576c0
- [] Doc associating traits without id in README (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/9d5965bedfb3325b5233008c0d5c28ace85957ab
- [] Call analytics identify even without an user id (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4e40bcc54a3d119c96d9c77a47a038e041e4e4df
- [] Depend exactly on sinon version 1.16.0 (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/d048e6f5f6a076221e6bd9997cdfc7a70c94a216
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/85281ab88fb9b09bc31730d089c0137536257e70

## [1.3.1] - 2015-08-14

### Fixed

- [] Fix tests indentation (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/b54c5b71b255f890b9e2e1127922159c4b5f0e6d
- [] Fix demo example (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/76e60b9dfd4fcf8b5c130d56312d625895319b3c
- [] Add event uuid to allow x-reference with segment (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/5c104a17cdcd039014d5ab8d08b0674c315353d2
- [] Update segment error message (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/b30363dd65b185e147fac1c126e8cd2ed81a5fd8
- [] Fix tests with patch of zuul-ngrok (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/c36b3bb689917781808880e4c669a80fce3850e6
- [] Fix tests (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/263a313354b175634d0ff6c459dcc52458e79864
- [] No more hacks we don't like it (`Martin Gontovnikas`)
  https://github.com/auth0/metrics/commit/b90b2d3674947ac434dc3ad7d11801600b155fba
- [] Gonto hacking at work (`Martin Gontovnikas`)
  https://github.com/auth0/metrics/commit/5c2e9e44cb6fcf9bf7677753306fdfc0fa557e57
- [] Release: 1.3.0 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/01a4ad3d77dd8791dfe18907b731fa8a7da9adba
- [] Update zuul (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/5c86decc76854559a9aa439f778c3316c652f277
- [] Fixed problem with Cookies :D finally (`Martin Gontovnikas`)
  https://github.com/auth0/metrics/commit/973f74d8ccc01f936300b623debab2f00c15be57
- [] Release: 1.2.1 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/900944faa89fa068c9d589f828b7ea313e14030b
- [] Merge pull request #8 from auth0/loader-improvements (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/658d995754e4c02a899d4e68cd0f86e17fb76c0e
- [] Include a minified loader script in the build (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/a64713cf2297e762a5f30d5a7f861986b0ca638b
- [] Ensure there are stub methods for the loader (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/d52003889b819c0cb0776191e5907240de48a2db
- [] Release: 1.2.0 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/7e6c722ec23acafb4f3cb03c6ce7bf73bd7532de
- [] Attempt to properly purge loader scripts (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4d9f8efc23d73f84d151727a8bf57f092e8d7e52
- [] Release: 1.1.2 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/2bdf213a9349af94696086985d561282de30e839
- [] Fix jsdoc task src (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/2ea23aba3350732f1ef35a1860cf0616e2c2d866
- [] Release: 1.1.1 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/a8c9ab4d154db393af20faba2223c03a3f71a134
- [] Merge pull request #7 from auth0/track-segment-error (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e4379db04f477afc8a0845916573b179a5e4ea32
- [] Track segment error also for alias and identify (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/3aedacaeb285e92762f7267dbad2919bf66a10af
- [] Wrap in try/catch the call to track segment-error (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/654bf0270ef9e40a0692e8168eb0f97dd5e3bf49
- [] Track segment errors when calling track and page (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4fc2f867f89381266f4c19dd10097c6c9e5b7042
- [] Merge pull request #5 from auth0/loader-script (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/2ad136b89758469978bb372af8562623b2445501
- [] Document using the loader for the sync case (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/91ce153d35bf15fc9536f0c290d156afe38c7d5a
- [] Move jsdoc loader template from ./lib to ./support (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/eaf55711840bea61363598f7b8deb435d7b02863
- [] Doc loader script in README (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/fc8812d6936c7d11faa3d1adbc99d2a6b17cabb6
- [] Update error message when the loader fails (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/7929793a98e738280a1d51ce4943de576149dddb
- [] Update loader to take just a config object (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/1f6e8917fec70142ec47d1f0efed0848b8849229
- [] Little improvents of style to loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6e4621b4997ca479eecd43175c498feae993da1a
- [] Update cdn tasks to include the loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/c2fbf31e19afc2c4b246884df5f47fada6281f55
- [] Include loader script in the build process (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/ade66bd9c6d449b0db9dba143e844c215e3b0954
- [] Remove unused fastly grunt task (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6bd613ff15d33f4ab3459138802a0b60bd916dba
- [] Use ejs.renderFile when rendering loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4e7e81a0bb0a34adba4e4439b12f6c055ec2d859
- [] Some work to auto-generate the loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/a98a9d30deb5664cbb66fcde7d29b00bf9fc5bdc
- [] Release: 1.1.0 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e5ca29d1e5d7d1cfd4d5e7dfa7515cf39aa3bd2b
- [] Fixing bump command (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/5f0ebb3c37c09078a68c960ed2f257792db10af9
- [] Replace call to console.log with debug (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6911fe409a30b05577794252ceab788d79b12e4d
- [] Forgot to add lodash to test_harness.html (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/95bc9cc4215729e87562ca669e831d798f1ac24f
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/8202f5531fe6a6b4ee820deb31ca7620aebfa4b3
- [] Merge pull request #4 from auth0/anonymous-traits (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e388e183919efdf242bad481a611108811f576c0
- [] Doc associating traits without id in README (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/9d5965bedfb3325b5233008c0d5c28ace85957ab
- [] Call analytics identify even without an user id (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4e40bcc54a3d119c96d9c77a47a038e041e4e4df
- [] Depend exactly on sinon version 1.16.0 (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/d048e6f5f6a076221e6bd9997cdfc7a70c94a216
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/85281ab88fb9b09bc31730d089c0137536257e70

## [1.3.0] - 2015-08-14

### Fixed

- [] Update zuul (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/5c86decc76854559a9aa439f778c3316c652f277
- [] Fixed problem with Cookies :D finally (`Martin Gontovnikas`)
  https://github.com/auth0/metrics/commit/973f74d8ccc01f936300b623debab2f00c15be57
- [] Release: 1.2.1 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/900944faa89fa068c9d589f828b7ea313e14030b
- [] Merge pull request #8 from auth0/loader-improvements (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/658d995754e4c02a899d4e68cd0f86e17fb76c0e
- [] Include a minified loader script in the build (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/a64713cf2297e762a5f30d5a7f861986b0ca638b
- [] Ensure there are stub methods for the loader (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/d52003889b819c0cb0776191e5907240de48a2db
- [] Release: 1.2.0 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/7e6c722ec23acafb4f3cb03c6ce7bf73bd7532de
- [] Attempt to properly purge loader scripts (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4d9f8efc23d73f84d151727a8bf57f092e8d7e52
- [] Release: 1.1.2 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/2bdf213a9349af94696086985d561282de30e839
- [] Fix jsdoc task src (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/2ea23aba3350732f1ef35a1860cf0616e2c2d866
- [] Release: 1.1.1 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/a8c9ab4d154db393af20faba2223c03a3f71a134
- [] Merge pull request #7 from auth0/track-segment-error (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e4379db04f477afc8a0845916573b179a5e4ea32
- [] Track segment error also for alias and identify (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/3aedacaeb285e92762f7267dbad2919bf66a10af
- [] Wrap in try/catch the call to track segment-error (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/654bf0270ef9e40a0692e8168eb0f97dd5e3bf49
- [] Track segment errors when calling track and page (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4fc2f867f89381266f4c19dd10097c6c9e5b7042
- [] Merge pull request #5 from auth0/loader-script (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/2ad136b89758469978bb372af8562623b2445501
- [] Document using the loader for the sync case (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/91ce153d35bf15fc9536f0c290d156afe38c7d5a
- [] Move jsdoc loader template from ./lib to ./support (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/eaf55711840bea61363598f7b8deb435d7b02863
- [] Doc loader script in README (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/fc8812d6936c7d11faa3d1adbc99d2a6b17cabb6
- [] Update error message when the loader fails (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/7929793a98e738280a1d51ce4943de576149dddb
- [] Update loader to take just a config object (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/1f6e8917fec70142ec47d1f0efed0848b8849229
- [] Little improvents of style to loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6e4621b4997ca479eecd43175c498feae993da1a
- [] Update cdn tasks to include the loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/c2fbf31e19afc2c4b246884df5f47fada6281f55
- [] Include loader script in the build process (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/ade66bd9c6d449b0db9dba143e844c215e3b0954
- [] Remove unused fastly grunt task (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6bd613ff15d33f4ab3459138802a0b60bd916dba
- [] Use ejs.renderFile when rendering loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4e7e81a0bb0a34adba4e4439b12f6c055ec2d859
- [] Some work to auto-generate the loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/a98a9d30deb5664cbb66fcde7d29b00bf9fc5bdc
- [] Release: 1.1.0 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e5ca29d1e5d7d1cfd4d5e7dfa7515cf39aa3bd2b
- [] Fixing bump command (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/5f0ebb3c37c09078a68c960ed2f257792db10af9
- [] Replace call to console.log with debug (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6911fe409a30b05577794252ceab788d79b12e4d
- [] Forgot to add lodash to test_harness.html (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/95bc9cc4215729e87562ca669e831d798f1ac24f
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/8202f5531fe6a6b4ee820deb31ca7620aebfa4b3
- [] Merge pull request #4 from auth0/anonymous-traits (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e388e183919efdf242bad481a611108811f576c0
- [] Doc associating traits without id in README (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/9d5965bedfb3325b5233008c0d5c28ace85957ab
- [] Call analytics identify even without an user id (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4e40bcc54a3d119c96d9c77a47a038e041e4e4df
- [] Depend exactly on sinon version 1.16.0 (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/d048e6f5f6a076221e6bd9997cdfc7a70c94a216
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/85281ab88fb9b09bc31730d089c0137536257e70

## [1.2.1] - 2015-08-14

### Fixed

- [] Merge pull request #8 from auth0/loader-improvements (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/658d995754e4c02a899d4e68cd0f86e17fb76c0e
- [] Include a minified loader script in the build (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/a64713cf2297e762a5f30d5a7f861986b0ca638b
- [] Ensure there are stub methods for the loader (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/d52003889b819c0cb0776191e5907240de48a2db
- [] Release: 1.2.0 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/7e6c722ec23acafb4f3cb03c6ce7bf73bd7532de
- [] Attempt to properly purge loader scripts (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4d9f8efc23d73f84d151727a8bf57f092e8d7e52
- [] Release: 1.1.2 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/2bdf213a9349af94696086985d561282de30e839
- [] Fix jsdoc task src (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/2ea23aba3350732f1ef35a1860cf0616e2c2d866
- [] Release: 1.1.1 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/a8c9ab4d154db393af20faba2223c03a3f71a134
- [] Merge pull request #7 from auth0/track-segment-error (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e4379db04f477afc8a0845916573b179a5e4ea32
- [] Track segment error also for alias and identify (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/3aedacaeb285e92762f7267dbad2919bf66a10af
- [] Wrap in try/catch the call to track segment-error (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/654bf0270ef9e40a0692e8168eb0f97dd5e3bf49
- [] Track segment errors when calling track and page (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4fc2f867f89381266f4c19dd10097c6c9e5b7042
- [] Merge pull request #5 from auth0/loader-script (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/2ad136b89758469978bb372af8562623b2445501
- [] Document using the loader for the sync case (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/91ce153d35bf15fc9536f0c290d156afe38c7d5a
- [] Move jsdoc loader template from ./lib to ./support (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/eaf55711840bea61363598f7b8deb435d7b02863
- [] Doc loader script in README (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/fc8812d6936c7d11faa3d1adbc99d2a6b17cabb6
- [] Update error message when the loader fails (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/7929793a98e738280a1d51ce4943de576149dddb
- [] Update loader to take just a config object (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/1f6e8917fec70142ec47d1f0efed0848b8849229
- [] Little improvents of style to loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6e4621b4997ca479eecd43175c498feae993da1a
- [] Update cdn tasks to include the loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/c2fbf31e19afc2c4b246884df5f47fada6281f55
- [] Include loader script in the build process (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/ade66bd9c6d449b0db9dba143e844c215e3b0954
- [] Remove unused fastly grunt task (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6bd613ff15d33f4ab3459138802a0b60bd916dba
- [] Use ejs.renderFile when rendering loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4e7e81a0bb0a34adba4e4439b12f6c055ec2d859
- [] Some work to auto-generate the loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/a98a9d30deb5664cbb66fcde7d29b00bf9fc5bdc
- [] Release: 1.1.0 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e5ca29d1e5d7d1cfd4d5e7dfa7515cf39aa3bd2b
- [] Fixing bump command (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/5f0ebb3c37c09078a68c960ed2f257792db10af9
- [] Replace call to console.log with debug (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6911fe409a30b05577794252ceab788d79b12e4d
- [] Forgot to add lodash to test_harness.html (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/95bc9cc4215729e87562ca669e831d798f1ac24f
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/8202f5531fe6a6b4ee820deb31ca7620aebfa4b3
- [] Merge pull request #4 from auth0/anonymous-traits (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e388e183919efdf242bad481a611108811f576c0
- [] Doc associating traits without id in README (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/9d5965bedfb3325b5233008c0d5c28ace85957ab
- [] Call analytics identify even without an user id (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4e40bcc54a3d119c96d9c77a47a038e041e4e4df
- [] Depend exactly on sinon version 1.16.0 (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/d048e6f5f6a076221e6bd9997cdfc7a70c94a216
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/85281ab88fb9b09bc31730d089c0137536257e70

## [1.2.0] - 2015-08-14

### Fixed

- [] Attempt to properly purge loader scripts (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4d9f8efc23d73f84d151727a8bf57f092e8d7e52
- [] Release: 1.1.2 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/2bdf213a9349af94696086985d561282de30e839
- [] Fix jsdoc task src (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/2ea23aba3350732f1ef35a1860cf0616e2c2d866
- [] Release: 1.1.1 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/a8c9ab4d154db393af20faba2223c03a3f71a134
- [] Merge pull request #7 from auth0/track-segment-error (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e4379db04f477afc8a0845916573b179a5e4ea32
- [] Track segment error also for alias and identify (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/3aedacaeb285e92762f7267dbad2919bf66a10af
- [] Wrap in try/catch the call to track segment-error (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/654bf0270ef9e40a0692e8168eb0f97dd5e3bf49
- [] Track segment errors when calling track and page (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4fc2f867f89381266f4c19dd10097c6c9e5b7042
- [] Merge pull request #5 from auth0/loader-script (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/2ad136b89758469978bb372af8562623b2445501
- [] Document using the loader for the sync case (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/91ce153d35bf15fc9536f0c290d156afe38c7d5a
- [] Move jsdoc loader template from ./lib to ./support (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/eaf55711840bea61363598f7b8deb435d7b02863
- [] Doc loader script in README (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/fc8812d6936c7d11faa3d1adbc99d2a6b17cabb6
- [] Update error message when the loader fails (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/7929793a98e738280a1d51ce4943de576149dddb
- [] Update loader to take just a config object (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/1f6e8917fec70142ec47d1f0efed0848b8849229
- [] Little improvents of style to loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6e4621b4997ca479eecd43175c498feae993da1a
- [] Update cdn tasks to include the loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/c2fbf31e19afc2c4b246884df5f47fada6281f55
- [] Include loader script in the build process (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/ade66bd9c6d449b0db9dba143e844c215e3b0954
- [] Remove unused fastly grunt task (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6bd613ff15d33f4ab3459138802a0b60bd916dba
- [] Use ejs.renderFile when rendering loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4e7e81a0bb0a34adba4e4439b12f6c055ec2d859
- [] Some work to auto-generate the loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/a98a9d30deb5664cbb66fcde7d29b00bf9fc5bdc
- [] Release: 1.1.0 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e5ca29d1e5d7d1cfd4d5e7dfa7515cf39aa3bd2b
- [] Fixing bump command (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/5f0ebb3c37c09078a68c960ed2f257792db10af9
- [] Replace call to console.log with debug (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6911fe409a30b05577794252ceab788d79b12e4d
- [] Forgot to add lodash to test_harness.html (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/95bc9cc4215729e87562ca669e831d798f1ac24f
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/8202f5531fe6a6b4ee820deb31ca7620aebfa4b3
- [] Merge pull request #4 from auth0/anonymous-traits (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e388e183919efdf242bad481a611108811f576c0
- [] Doc associating traits without id in README (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/9d5965bedfb3325b5233008c0d5c28ace85957ab
- [] Call analytics identify even without an user id (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4e40bcc54a3d119c96d9c77a47a038e041e4e4df
- [] Depend exactly on sinon version 1.16.0 (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/d048e6f5f6a076221e6bd9997cdfc7a70c94a216
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/85281ab88fb9b09bc31730d089c0137536257e70

## [1.1.2] - 2015-08-14

### Fixed

- [] Fix jsdoc task src (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/2ea23aba3350732f1ef35a1860cf0616e2c2d866
- [] Release: 1.1.1 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/a8c9ab4d154db393af20faba2223c03a3f71a134
- [] Merge pull request #7 from auth0/track-segment-error (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e4379db04f477afc8a0845916573b179a5e4ea32
- [] Track segment error also for alias and identify (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/3aedacaeb285e92762f7267dbad2919bf66a10af
- [] Wrap in try/catch the call to track segment-error (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/654bf0270ef9e40a0692e8168eb0f97dd5e3bf49
- [] Track segment errors when calling track and page (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4fc2f867f89381266f4c19dd10097c6c9e5b7042
- [] Merge pull request #5 from auth0/loader-script (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/2ad136b89758469978bb372af8562623b2445501
- [] Document using the loader for the sync case (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/91ce153d35bf15fc9536f0c290d156afe38c7d5a
- [] Move jsdoc loader template from ./lib to ./support (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/eaf55711840bea61363598f7b8deb435d7b02863
- [] Doc loader script in README (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/fc8812d6936c7d11faa3d1adbc99d2a6b17cabb6
- [] Update error message when the loader fails (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/7929793a98e738280a1d51ce4943de576149dddb
- [] Update loader to take just a config object (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/1f6e8917fec70142ec47d1f0efed0848b8849229
- [] Little improvents of style to loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6e4621b4997ca479eecd43175c498feae993da1a
- [] Update cdn tasks to include the loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/c2fbf31e19afc2c4b246884df5f47fada6281f55
- [] Include loader script in the build process (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/ade66bd9c6d449b0db9dba143e844c215e3b0954
- [] Remove unused fastly grunt task (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6bd613ff15d33f4ab3459138802a0b60bd916dba
- [] Use ejs.renderFile when rendering loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4e7e81a0bb0a34adba4e4439b12f6c055ec2d859
- [] Some work to auto-generate the loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/a98a9d30deb5664cbb66fcde7d29b00bf9fc5bdc
- [] Release: 1.1.0 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e5ca29d1e5d7d1cfd4d5e7dfa7515cf39aa3bd2b
- [] Fixing bump command (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/5f0ebb3c37c09078a68c960ed2f257792db10af9
- [] Replace call to console.log with debug (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6911fe409a30b05577794252ceab788d79b12e4d
- [] Forgot to add lodash to test_harness.html (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/95bc9cc4215729e87562ca669e831d798f1ac24f
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/8202f5531fe6a6b4ee820deb31ca7620aebfa4b3
- [] Merge pull request #4 from auth0/anonymous-traits (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e388e183919efdf242bad481a611108811f576c0
- [] Doc associating traits without id in README (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/9d5965bedfb3325b5233008c0d5c28ace85957ab
- [] Call analytics identify even without an user id (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4e40bcc54a3d119c96d9c77a47a038e041e4e4df
- [] Depend exactly on sinon version 1.16.0 (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/d048e6f5f6a076221e6bd9997cdfc7a70c94a216
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/85281ab88fb9b09bc31730d089c0137536257e70

## [1.1.1] - 2015-08-14

### Fixed

- [] Merge pull request #7 from auth0/track-segment-error (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e4379db04f477afc8a0845916573b179a5e4ea32
- [] Track segment error also for alias and identify (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/3aedacaeb285e92762f7267dbad2919bf66a10af
- [] Wrap in try/catch the call to track segment-error (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/654bf0270ef9e40a0692e8168eb0f97dd5e3bf49
- [] Track segment errors when calling track and page (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4fc2f867f89381266f4c19dd10097c6c9e5b7042
- [] Merge pull request #5 from auth0/loader-script (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/2ad136b89758469978bb372af8562623b2445501
- [] Document using the loader for the sync case (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/91ce153d35bf15fc9536f0c290d156afe38c7d5a
- [] Move jsdoc loader template from ./lib to ./support (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/eaf55711840bea61363598f7b8deb435d7b02863
- [] Doc loader script in README (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/fc8812d6936c7d11faa3d1adbc99d2a6b17cabb6
- [] Update error message when the loader fails (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/7929793a98e738280a1d51ce4943de576149dddb
- [] Update loader to take just a config object (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/1f6e8917fec70142ec47d1f0efed0848b8849229
- [] Little improvents of style to loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6e4621b4997ca479eecd43175c498feae993da1a
- [] Update cdn tasks to include the loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/c2fbf31e19afc2c4b246884df5f47fada6281f55
- [] Include loader script in the build process (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/ade66bd9c6d449b0db9dba143e844c215e3b0954
- [] Remove unused fastly grunt task (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6bd613ff15d33f4ab3459138802a0b60bd916dba
- [] Use ejs.renderFile when rendering loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4e7e81a0bb0a34adba4e4439b12f6c055ec2d859
- [] Some work to auto-generate the loader script (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/a98a9d30deb5664cbb66fcde7d29b00bf9fc5bdc
- [] Release: 1.1.0 (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e5ca29d1e5d7d1cfd4d5e7dfa7515cf39aa3bd2b
- [] Fixing bump command (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/5f0ebb3c37c09078a68c960ed2f257792db10af9
- [] Replace call to console.log with debug (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6911fe409a30b05577794252ceab788d79b12e4d
- [] Forgot to add lodash to test_harness.html (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/95bc9cc4215729e87562ca669e831d798f1ac24f
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/8202f5531fe6a6b4ee820deb31ca7620aebfa4b3
- [] Merge pull request #4 from auth0/anonymous-traits (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e388e183919efdf242bad481a611108811f576c0
- [] Doc associating traits without id in README (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/9d5965bedfb3325b5233008c0d5c28ace85957ab
- [] Call analytics identify even without an user id (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4e40bcc54a3d119c96d9c77a47a038e041e4e4df
- [] Depend exactly on sinon version 1.16.0 (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/d048e6f5f6a076221e6bd9997cdfc7a70c94a216
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/85281ab88fb9b09bc31730d089c0137536257e70

## [1.1.0] - 2015-08-14

### Fixed

- [] Fixing bump command (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/5f0ebb3c37c09078a68c960ed2f257792db10af9
- [] Replace call to console.log with debug (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/6911fe409a30b05577794252ceab788d79b12e4d
- [] Forgot to add lodash to test_harness.html (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/95bc9cc4215729e87562ca669e831d798f1ac24f
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/8202f5531fe6a6b4ee820deb31ca7620aebfa4b3
- [] Merge pull request #4 from auth0/anonymous-traits (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/e388e183919efdf242bad481a611108811f576c0
- [] Doc associating traits without id in README (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/9d5965bedfb3325b5233008c0d5c28ace85957ab
- [] Call analytics identify even without an user id (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/4e40bcc54a3d119c96d9c77a47a038e041e4e4df
- [] Depend exactly on sinon version 1.16.0 (`Gabriel Andretta`)
  https://github.com/auth0/metrics/commit/d048e6f5f6a076221e6bd9997cdfc7a70c94a216
- [] Update README.md (`Cristian Douce`)
  https://github.com/auth0/metrics/commit/85281ab88fb9b09bc31730d089c0137536257e70

## [1.0.1] - 2015-08-14

### Fixed



## [1.0.0] - 2015-08-11

### Fixed



## [1.0.0] - 2015-08-11

### Fixed



