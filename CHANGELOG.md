# Changelog

## [4.0.0](https://github.com/AyushSehrawat/zilean/compare/v3.5.0...v4.0.0) (2025-12-15)


### ⚠ BREAKING CHANGES

* Upgrade rtn for adult check handling

### 🚀 New Features

* add cache check endpoint, require auth for /torrents endpoints ([7352abd](https://github.com/AyushSehrawat/zilean/commit/7352abd7a6940e27ac5170fcc2ca99a8f9abf456))
* Add the ability to opt into lucene ([c610f14](https://github.com/AyushSehrawat/zilean/commit/c610f14a82c1946009226d65fd4ff6c72455c6ee))
* huge changes to facilitate the bad adult classification we have ([5149cd1](https://github.com/AyushSehrawat/zilean/commit/5149cd10ee5598997850d721f1a5478c281195ae))
* include imdb resync command ([cb1765d](https://github.com/AyushSehrawat/zilean/commit/cb1765dcb676c16a4841532742b6c2384165ee2a))
* support generic ingestion endpoint ([8b78d90](https://github.com/AyushSehrawat/zilean/commit/8b78d909cd9846e90103e8719c56b22c92b5931e))
* trying git instead of downloading repo ([cb0e2a4](https://github.com/AyushSehrawat/zilean/commit/cb0e2a4bd73923c4b3ff30d3af11df140ed96a62))
* Upgrade rtn for adult check handling ([5422baa](https://github.com/AyushSehrawat/zilean/commit/5422baa3ad68a8fc0dafe235ccdebf293fd10492))


### 🔥 Bug Fixes

* allow service registration when scrape is disabled ([cdd4fdc](https://github.com/AyushSehrawat/zilean/commit/cdd4fdcd78b8ac706a63596364cfc52bcb009378))
* allow service registration when scrape is disabled ([cd45854](https://github.com/AyushSehrawat/zilean/commit/cd4585461b485f08c33da9adf7848f67259786b2))
* better distinction handling ([633433b](https://github.com/AyushSehrawat/zilean/commit/633433b4d3a5b601e9946100bcd2e44867511cf6))
* broken imdbid ([135d389](https://github.com/AyushSehrawat/zilean/commit/135d389b9fc50c4d7082f66643a1f8ac3be59052))
* db indexes for new columns ([bab4059](https://github.com/AyushSehrawat/zilean/commit/bab405917d3d27cf8eab53bee3040b3b63fd58fb))
* dedupe infohashes ([caa116d](https://github.com/AyushSehrawat/zilean/commit/caa116d2d619ea1dbfe04561bfc1e4c1ba5e56bb))
* ensure cleanup of resources after syncs ([4785d0c](https://github.com/AyushSehrawat/zilean/commit/4785d0cf3cb3d49abd36f2b24fb62833d2234c60))
* ensure imdbId from torznab has tt prefixed ([354ae43](https://github.com/AyushSehrawat/zilean/commit/354ae43a56e45285183031eb3ec7477c86888ffe))
* Ensure scrape endpoint isn't anonymous ([067054f](https://github.com/AyushSehrawat/zilean/commit/067054feb9eaff3ab6ada273166d824dc03a19cd))
* Fix imdbSearch matching - thanks MatYRiCs ([ca8b01b](https://github.com/AyushSehrawat/zilean/commit/ca8b01b17edd1abb1eb77eb4817ee63e625187da))
* Fix imdbSearch matching - thanks MatYRiCs ([a31d543](https://github.com/AyushSehrawat/zilean/commit/a31d543eecebb96cc12ea527e5ab3c89e85f7b1b))
* include ingestion request timeout ([92426da](https://github.com/AyushSehrawat/zilean/commit/92426da0af85f6595e1886576615664ee525b75c))
* increase command timeout in dockerfile example ([007f514](https://github.com/AyushSehrawat/zilean/commit/007f514097afb386ca2d5da7ccbfda3c8f121e68))
* log batch import error ([b325076](https://github.com/AyushSehrawat/zilean/commit/b325076593e877343efbf360a8cb982d79e5bb75))
* regex ([ebd58e1](https://github.com/AyushSehrawat/zilean/commit/ebd58e1ce4fba27df12392eed04421077812ff5e))
* remove pinned curl version from dockerfile ([b0c1531](https://github.com/AyushSehrawat/zilean/commit/b0c15311044724c7c9b074a8849a00d57dd14b44))
* remove pinned curl version from dockerfile ([94bebe6](https://github.com/AyushSehrawat/zilean/commit/94bebe62407953c86d5d1801a48d68a252572e51))
* remove warnings from dataprotection stack ([1a11e54](https://github.com/AyushSehrawat/zilean/commit/1a11e5414e5002a181b8377ea95d4f56b83a06ce))
* stop word removal ([026b1bc](https://github.com/AyushSehrawat/zilean/commit/026b1bc67bc95df3784b56943b357842c9582b34))
* Store it in ingestion too :/ ([1cac03c](https://github.com/AyushSehrawat/zilean/commit/1cac03c726e8f28a1e5ca1fb0f4b1127cdfd0485))
* uhoh - repo issue ([398e85d](https://github.com/AyushSehrawat/zilean/commit/398e85d67d88d456f48001fd8f62f9545842f793))


### ⚙️ Chores

* change workfllow data ([547360a](https://github.com/AyushSehrawat/zilean/commit/547360aa21847fd40a44695a81a3e3d368b8c2f7))
* documentation ([b474b99](https://github.com/AyushSehrawat/zilean/commit/b474b9940fcd46ee129e5ddc1a4eeb27ae90698b))
* **main:** release 2.3.1 ([5d9eafc](https://github.com/AyushSehrawat/zilean/commit/5d9eafc736bd8454abb0643ea430c593f3b28327))
* **main:** release 2.3.1 ([999713a](https://github.com/AyushSehrawat/zilean/commit/999713a8df2efdf313db42c8a1944484c0baaf89))
* **main:** release 2.3.10 ([eab31ce](https://github.com/AyushSehrawat/zilean/commit/eab31ceaff6bd2ed970e8428ca3814f3dffc7961))
* **main:** release 2.3.10 ([65f7fb4](https://github.com/AyushSehrawat/zilean/commit/65f7fb49d8b2208483327b8b00f554b35d9f15af))
* **main:** release 2.3.2 ([15ec48b](https://github.com/AyushSehrawat/zilean/commit/15ec48bd6c2b7fd7e71feae701e27dbd0cdda651))
* **main:** release 2.3.2 ([1b69bf1](https://github.com/AyushSehrawat/zilean/commit/1b69bf1f341383726fecc8211b8fef87198e475d))
* **main:** release 2.3.3 ([7af7e22](https://github.com/AyushSehrawat/zilean/commit/7af7e224cdd891cd436245a2dbd379bef28d69fa))
* **main:** release 2.3.3 ([16a9018](https://github.com/AyushSehrawat/zilean/commit/16a9018727cd51ba37c08b9bd75c6ee0dd26b0a9))
* **main:** release 2.3.4 ([e4a4bbd](https://github.com/AyushSehrawat/zilean/commit/e4a4bbd38f9429a91e1e5baabceadff07d7bcab1))
* **main:** release 2.3.4 ([2ee2bc2](https://github.com/AyushSehrawat/zilean/commit/2ee2bc22907f1579ef0750aa30562f76d6fd546d))
* **main:** release 2.3.5 ([4a3c05b](https://github.com/AyushSehrawat/zilean/commit/4a3c05b1cdb72bb27e820a50ca3bb914453a2cd6))
* **main:** release 2.3.5 ([d508acf](https://github.com/AyushSehrawat/zilean/commit/d508acfa20dfdfa933361feca6c446a4d0bbc7c0))
* **main:** release 2.3.6 ([945fdba](https://github.com/AyushSehrawat/zilean/commit/945fdba5019983b9a773a58277f3018f5068fb79))
* **main:** release 2.3.6 ([e87c2e9](https://github.com/AyushSehrawat/zilean/commit/e87c2e9ba432357b3ca26698b8009aca00aaa986))
* **main:** release 2.3.7 ([d6cf877](https://github.com/AyushSehrawat/zilean/commit/d6cf8771623fbe63b9e754bcf354ec7b9efb6507))
* **main:** release 2.3.7 ([c8e0752](https://github.com/AyushSehrawat/zilean/commit/c8e07526ee0680474d1880e68329622cc3fa46a4))
* **main:** release 2.3.8 ([4db3ff3](https://github.com/AyushSehrawat/zilean/commit/4db3ff3b48d82f3fec4e4aa06beaf7bc8367ed46))
* **main:** release 2.3.8 ([87d8ae2](https://github.com/AyushSehrawat/zilean/commit/87d8ae204e95e5898aa9f1c2564faf679a834616))
* **main:** release 2.3.9 ([b977f1f](https://github.com/AyushSehrawat/zilean/commit/b977f1f990e36f214ba5e305edd630fbb1ac5de4))
* **main:** release 2.3.9 ([ceb3d28](https://github.com/AyushSehrawat/zilean/commit/ceb3d28473c78607f2824408a88672698a978c1d))
* **main:** release 3.0.0 ([f94d824](https://github.com/AyushSehrawat/zilean/commit/f94d8245c2b029bfdc8d1ec240ed98340502a067))
* **main:** release 3.0.0 ([3bf2c0c](https://github.com/AyushSehrawat/zilean/commit/3bf2c0cf6a573c01cc57c3d8bb0f9497e560aafa))
* **main:** release 3.1.0 ([cd0e937](https://github.com/AyushSehrawat/zilean/commit/cd0e9376c85eab3a8c8b2905022dc9cb9247e37c))
* **main:** release 3.1.0 ([5d871b4](https://github.com/AyushSehrawat/zilean/commit/5d871b4b4c5fa8f8a7f01d13a482f62802c91d6e))
* **main:** release 3.2.0 ([594d9c7](https://github.com/AyushSehrawat/zilean/commit/594d9c72fac76154a7850b369c58580896c5f98b))
* **main:** release 3.2.0 ([92d9284](https://github.com/AyushSehrawat/zilean/commit/92d9284fcc336f0864e5604ff368ee3cb3d8d75a))
* **main:** release 3.2.1 ([d8ea553](https://github.com/AyushSehrawat/zilean/commit/d8ea553e39114625d4447ce5550ba2407db2f182))
* **main:** release 3.2.1 ([89dff16](https://github.com/AyushSehrawat/zilean/commit/89dff16c1068c29753ea9dd791af409e48f0d9dd))
* **main:** release 3.3.0 ([3d76f41](https://github.com/AyushSehrawat/zilean/commit/3d76f4117756efdc1414c45aa58f60f21bbb8265))
* **main:** release 3.3.0 ([a39d498](https://github.com/AyushSehrawat/zilean/commit/a39d498c3385f44c0b9e590adf3b5958a6271843))
* **main:** release 3.3.1 ([f7b1c2c](https://github.com/AyushSehrawat/zilean/commit/f7b1c2ca6371ae925bff9c01bac24105a66f20ae))
* **main:** release 3.3.1 ([c8170b2](https://github.com/AyushSehrawat/zilean/commit/c8170b2013a81b0fd770657f2e4866902819ba32))
* **main:** release 3.3.2 ([f7d56ae](https://github.com/AyushSehrawat/zilean/commit/f7d56aee7928349a6b170dfdef8d5425060b7da5))
* **main:** release 3.3.2 ([776db71](https://github.com/AyushSehrawat/zilean/commit/776db71b4b8748ca5021b163b20ffbb0d354e992))
* **main:** release 3.3.3 ([da4c99b](https://github.com/AyushSehrawat/zilean/commit/da4c99ba67f12c55b4327b8b97f69d6cd6961609))
* **main:** release 3.3.3 ([2a3e9ae](https://github.com/AyushSehrawat/zilean/commit/2a3e9ae625e1495fb7ff9ec5737ea1f42443030b))
* **main:** release 3.3.4 ([80d5e77](https://github.com/AyushSehrawat/zilean/commit/80d5e7796ffa65ec7230bcbaf299174e3d16ed72))
* **main:** release 3.3.4 ([af1e085](https://github.com/AyushSehrawat/zilean/commit/af1e0856a131797b051534cd6a9e46f8ad1d0118))
* **main:** release 3.3.5 ([565ac77](https://github.com/AyushSehrawat/zilean/commit/565ac77860274f80c1d09d02ef2331be7fc04321))
* **main:** release 3.3.5 ([7fdc52b](https://github.com/AyushSehrawat/zilean/commit/7fdc52b1997239e62da1c254da6f554d1a5fef9c))
* **main:** release 3.3.6 ([3f74888](https://github.com/AyushSehrawat/zilean/commit/3f748883a4e61d474ba517f680363903a85e100d))
* **main:** release 3.3.6 ([50398fc](https://github.com/AyushSehrawat/zilean/commit/50398fcbb197d2a6915ddd88a5a63bfd36d12f50))
* **main:** release 3.4.0 ([23a631b](https://github.com/AyushSehrawat/zilean/commit/23a631bbb5aa19c4687089ab75d1635dcc73910c))
* **main:** release 3.4.0 ([b19a8c4](https://github.com/AyushSehrawat/zilean/commit/b19a8c4581caffadbe6cf37004c3f4c8b662f377))
* **main:** release 3.5.0 ([3e0d7af](https://github.com/AyushSehrawat/zilean/commit/3e0d7af87088f050a4ae3455ed3d4cb1cac33e2a))
* update docs ([10828ac](https://github.com/AyushSehrawat/zilean/commit/10828ac74183904b8ae1bcd6e079464829bd8d10))
* update docs ([970f14d](https://github.com/AyushSehrawat/zilean/commit/970f14d66489c82a6841f5b4051fb4254d900154))
* update readme ([cb7af70](https://github.com/AyushSehrawat/zilean/commit/cb7af7007eec7d74be6f78ee682599704e29138b))


### ⌨️ Code Refactoring

* include imdbfiles which dont have a year (0) ([b943ba0](https://github.com/AyushSehrawat/zilean/commit/b943ba0e51bfadfa7b34ceadad9d1f88b4560320))
* rework matching ([f42c2fa](https://github.com/AyushSehrawat/zilean/commit/f42c2faf4cdc85da4b37ca10a15b998a311359c9))
* rework matching slightly ([2b34f05](https://github.com/AyushSehrawat/zilean/commit/2b34f051f8e55401870c67117cfe6c478b950ca1))
* rework matching, and update docs ([cfbd53d](https://github.com/AyushSehrawat/zilean/commit/cfbd53dbed78f60bc193de90ce6e3c3dd2ccf4fb))


### 📦 CI Improvements

* automate doc publishing now its working when release publishes ([022ef57](https://github.com/AyushSehrawat/zilean/commit/022ef576007eb27853aed6e48a7c4992f0c06e07))
* upgrade docs workflow [skip-release] ([11091d9](https://github.com/AyushSehrawat/zilean/commit/11091d99a94a850e94d426090134b70f8bc258ed))

## [3.5.0](https://github.com/iPromKnight/zilean/compare/v3.4.0...v3.5.0) (2025-04-21)


### 🚀 New Features

* support generic ingestion endpoint ([8b78d90](https://github.com/iPromKnight/zilean/commit/8b78d909cd9846e90103e8719c56b22c92b5931e))

## [3.4.0](https://github.com/iPromKnight/zilean/compare/v3.3.6...v3.4.0) (2025-01-26)


### 🚀 New Features

* Add the ability to opt into lucene ([c610f14](https://github.com/iPromKnight/zilean/commit/c610f14a82c1946009226d65fd4ff6c72455c6ee))


### 🔥 Bug Fixes

* ensure cleanup of resources after syncs ([4785d0c](https://github.com/iPromKnight/zilean/commit/4785d0cf3cb3d49abd36f2b24fb62833d2234c60))

## [3.3.6](https://github.com/iPromKnight/zilean/compare/v3.3.5...v3.3.6) (2025-01-24)


### ⌨️ Code Refactoring

* include imdbfiles which dont have a year (0) ([b943ba0](https://github.com/iPromKnight/zilean/commit/b943ba0e51bfadfa7b34ceadad9d1f88b4560320))

## [3.3.5](https://github.com/iPromKnight/zilean/compare/v3.3.4...v3.3.5) (2025-01-24)


### ⌨️ Code Refactoring

* rework matching slightly ([2b34f05](https://github.com/iPromKnight/zilean/commit/2b34f051f8e55401870c67117cfe6c478b950ca1))

## [3.3.4](https://github.com/iPromKnight/zilean/compare/v3.3.3...v3.3.4) (2025-01-24)


### ⚙️ Chores

* update docs ([10828ac](https://github.com/iPromKnight/zilean/commit/10828ac74183904b8ae1bcd6e079464829bd8d10))
* update readme ([cb7af70](https://github.com/iPromKnight/zilean/commit/cb7af7007eec7d74be6f78ee682599704e29138b))


### ⌨️ Code Refactoring

* rework matching ([f42c2fa](https://github.com/iPromKnight/zilean/commit/f42c2faf4cdc85da4b37ca10a15b998a311359c9))

## [3.3.3](https://github.com/iPromKnight/zilean/compare/v3.3.2...v3.3.3) (2025-01-18)


### 🔥 Bug Fixes

* remove pinned curl version from dockerfile ([94bebe6](https://github.com/iPromKnight/zilean/commit/94bebe62407953c86d5d1801a48d68a252572e51))

## [3.3.2](https://github.com/iPromKnight/zilean/compare/v3.3.1...v3.3.2) (2025-01-18)


### 🔥 Bug Fixes

* Fix imdbSearch matching - thanks MatYRiCs ([a31d543](https://github.com/iPromKnight/zilean/commit/a31d543eecebb96cc12ea527e5ab3c89e85f7b1b))

## [3.3.1](https://github.com/iPromKnight/zilean/compare/v3.3.0...v3.3.1) (2025-01-01)


### 🔥 Bug Fixes

* allow service registration when scrape is disabled ([cd45854](https://github.com/iPromKnight/zilean/commit/cd4585461b485f08c33da9adf7848f67259786b2))

## [3.3.0](https://github.com/iPromKnight/zilean/compare/v3.2.1...v3.3.0) (2024-11-22)


### 🚀 New Features

* include imdb resync command ([cb1765d](https://github.com/iPromKnight/zilean/commit/cb1765dcb676c16a4841532742b6c2384165ee2a))


### 📦 CI Improvements

* automate doc publishing now its working when release publishes ([022ef57](https://github.com/iPromKnight/zilean/commit/022ef576007eb27853aed6e48a7c4992f0c06e07))

## [3.2.1](https://github.com/iPromKnight/zilean/compare/v3.2.0...v3.2.1) (2024-11-22)


### 🔥 Bug Fixes

* Ensure scrape endpoint isn't anonymous ([067054f](https://github.com/iPromKnight/zilean/commit/067054feb9eaff3ab6ada273166d824dc03a19cd))

## [3.2.0](https://github.com/iPromKnight/zilean/compare/v3.1.0...v3.2.0) (2024-11-22)


### 🚀 New Features

* add cache check endpoint, require auth for /torrents endpoints ([7352abd](https://github.com/iPromKnight/zilean/commit/7352abd7a6940e27ac5170fcc2ca99a8f9abf456))

## [3.1.0](https://github.com/iPromKnight/zilean/compare/v3.0.0...v3.1.0) (2024-11-21)


### 🚀 New Features

* huge changes to facilitate the bad adult classification we have ([5149cd1](https://github.com/iPromKnight/zilean/commit/5149cd10ee5598997850d721f1a5478c281195ae))


### ⚙️ Chores

* update docs ([970f14d](https://github.com/iPromKnight/zilean/commit/970f14d66489c82a6841f5b4051fb4254d900154))


### 📦 CI Improvements

* upgrade docs workflow [skip-release] ([11091d9](https://github.com/iPromKnight/zilean/commit/11091d99a94a850e94d426090134b70f8bc258ed))

## [3.0.0](https://github.com/iPromKnight/zilean/compare/v2.3.10...v3.0.0) (2024-11-20)


### ⚠ BREAKING CHANGES

* Upgrade rtn for adult check handling

### 🚀 New Features

* Upgrade rtn for adult check handling ([5422baa](https://github.com/iPromKnight/zilean/commit/5422baa3ad68a8fc0dafe235ccdebf293fd10492))


### ⚙️ Chores

* documentation ([b474b99](https://github.com/iPromKnight/zilean/commit/b474b9940fcd46ee129e5ddc1a4eeb27ae90698b))

## [2.3.10](https://github.com/iPromKnight/zilean/compare/v2.3.9...v2.3.10) (2024-11-17)


### 🔥 Bug Fixes

* better distinction handling ([633433b](https://github.com/iPromKnight/zilean/commit/633433b4d3a5b601e9946100bcd2e44867511cf6))

## [2.3.9](https://github.com/iPromKnight/zilean/compare/v2.3.8...v2.3.9) (2024-11-17)


### 🔥 Bug Fixes

* dedupe infohashes ([caa116d](https://github.com/iPromKnight/zilean/commit/caa116d2d619ea1dbfe04561bfc1e4c1ba5e56bb))

## [2.3.8](https://github.com/iPromKnight/zilean/compare/v2.3.7...v2.3.8) (2024-11-17)


### 🔥 Bug Fixes

* regex ([ebd58e1](https://github.com/iPromKnight/zilean/commit/ebd58e1ce4fba27df12392eed04421077812ff5e))

## [2.3.7](https://github.com/iPromKnight/zilean/compare/v2.3.6...v2.3.7) (2024-11-17)


### 🔥 Bug Fixes

* log batch import error ([b325076](https://github.com/iPromKnight/zilean/commit/b325076593e877343efbf360a8cb982d79e5bb75))

## [2.3.6](https://github.com/iPromKnight/zilean/compare/v2.3.5...v2.3.6) (2024-11-17)


### 🔥 Bug Fixes

* db indexes for new columns ([bab4059](https://github.com/iPromKnight/zilean/commit/bab405917d3d27cf8eab53bee3040b3b63fd58fb))

## [2.3.5](https://github.com/iPromKnight/zilean/compare/v2.3.4...v2.3.5) (2024-11-17)


### 🔥 Bug Fixes

* broken imdbid ([135d389](https://github.com/iPromKnight/zilean/commit/135d389b9fc50c4d7082f66643a1f8ac3be59052))
* remove warnings from dataprotection stack ([1a11e54](https://github.com/iPromKnight/zilean/commit/1a11e5414e5002a181b8377ea95d4f56b83a06ce))

## [2.3.4](https://github.com/iPromKnight/zilean/compare/v2.3.3...v2.3.4) (2024-11-17)


### 🔥 Bug Fixes

* ensure imdbId from torznab has tt prefixed ([354ae43](https://github.com/iPromKnight/zilean/commit/354ae43a56e45285183031eb3ec7477c86888ffe))

## [2.3.3](https://github.com/iPromKnight/zilean/compare/v2.3.2...v2.3.3) (2024-11-17)


### 🔥 Bug Fixes

* include ingestion request timeout ([92426da](https://github.com/iPromKnight/zilean/commit/92426da0af85f6595e1886576615664ee525b75c))
* increase command timeout in dockerfile example ([007f514](https://github.com/iPromKnight/zilean/commit/007f514097afb386ca2d5da7ccbfda3c8f121e68))

## [2.3.2](https://github.com/iPromKnight/zilean/compare/v2.3.1...v2.3.2) (2024-11-17)


### 🔥 Bug Fixes

* Store it in ingestion too :/ ([1cac03c](https://github.com/iPromKnight/zilean/commit/1cac03c726e8f28a1e5ca1fb0f4b1127cdfd0485))

## [2.3.1](https://github.com/iPromKnight/zilean/compare/v2.3.0...v2.3.1) (2024-11-17)


### 🔥 Bug Fixes

* stop word removal ([026b1bc](https://github.com/iPromKnight/zilean/commit/026b1bc67bc95df3784b56943b357842c9582b34))

## [2.3.0](https://github.com/iPromKnight/zilean/compare/v2.2.1...v2.3.0) (2024-11-17)


### 🚀 New Features

* add blacklist feature and API key authentication ([562bd14](https://github.com/iPromKnight/zilean/commit/562bd1433aa741c13e417a1608a628ee7093a0e6))

## [2.2.1](https://github.com/iPromKnight/zilean/compare/v2.2.0...v2.2.1) (2024-11-16)


### 🔥 Bug Fixes

* add configuration tests and update ingestion scraping logic ([ae73304](https://github.com/iPromKnight/zilean/commit/ae73304a6713fec098bcc5a39b5d5b088ca68e6b))


### ⚙️ Chores

* uddate readme ([a3461a6](https://github.com/iPromKnight/zilean/commit/a3461a606e5ff6cbad90bf6b33acaefe9c7cb831))
* update readme ([d9fed86](https://github.com/iPromKnight/zilean/commit/d9fed86a5382e7a5030811f157adbf8d908dabe0))

## [2.2.0](https://github.com/iPromKnight/zilean/compare/v2.1.3...v2.2.0) (2024-11-16)


### 🚀 New Features

* completed generic ingestion with service discovery ([0db28ba](https://github.com/iPromKnight/zilean/commit/0db28bad3c60308beb1942f18884b1c816518b55))
* Implement cli to allow choice of sync process to run ([6402511](https://github.com/iPromKnight/zilean/commit/6402511c44d9fe00f53785e597956c182a77221b))
* service discovery and manual config ([b39b6a3](https://github.com/iPromKnight/zilean/commit/b39b6a36b57df5be350cdf3905492f64a93a3626))
* Streaming endpoint ([79e12e1](https://github.com/iPromKnight/zilean/commit/79e12e155eec9fb2f541dbe841689eb02e477b0c))


### ⌨️ Code Refactoring

* collection of selectors in case they dont all match ([3bce11e](https://github.com/iPromKnight/zilean/commit/3bce11ec8bedd34eae66dc6c8f381485a0fcffc5))
* rename scraper ([88af4fd](https://github.com/iPromKnight/zilean/commit/88af4fd2ab652f34b129e13b2748327892679af5))
* started before scraper expansion ([1673841](https://github.com/iPromKnight/zilean/commit/16738410743b6e689aaf03c136d60c578cbabfc3))
* wire up secondary service, with separate schedule ([dceb6cb](https://github.com/iPromKnight/zilean/commit/dceb6cba9d205eb82ed8a680e1eac3d5e73159a5))

## [2.1.3](https://github.com/iPromKnight/zilean/compare/v2.1.2...v2.1.3) (2024-11-16)


### 🔥 Bug Fixes

* also handle xx ([09c70fb](https://github.com/iPromKnight/zilean/commit/09c70fbf0ed34e4f314c9928bbce8d13a89a9176))

## [2.1.2](https://github.com/iPromKnight/zilean/compare/v2.1.1...v2.1.2) (2024-11-16)


### 🔥 Bug Fixes

* Add filtering logic to exclude certain torrents during DMM scraping ([50612a7](https://github.com/iPromKnight/zilean/commit/50612a7d1467e9b47289882b762f658f4c09c5c6))
* reverse predicate ([c083aac](https://github.com/iPromKnight/zilean/commit/c083aacb999121b9d341cce0a0ab65e0a0d2fe9a))
* this will allow maxxxine, and xxx ([1f3c5c0](https://github.com/iPromKnight/zilean/commit/1f3c5c05f9979128a5cc49c9de72990550c87aa8))

## [2.1.1](https://github.com/iPromKnight/zilean/compare/v2.1.0...v2.1.1) (2024-11-15)


### 🔥 Bug Fixes

* Ensure culture libs are included in the container for .net to use. ([4a7a3ba](https://github.com/iPromKnight/zilean/commit/4a7a3ba46ba97f181d3fb8353d8db412e7bd2f06))

## [2.1.0](https://github.com/iPromKnight/zilean/compare/v2.0.2...v2.1.0) (2024-11-15)


### 🚀 New Features

* Add Torznab API support and enhance search capabilities ([d41abaf](https://github.com/iPromKnight/zilean/commit/d41abaf105fd3efe4e6e93e3e0fd0211cce66d33))
* torznab support started ([709be25](https://github.com/iPromKnight/zilean/commit/709be255de892677fa3155decb61eb81018e3991))


### ⌨️ Code Refactoring

* Updated to .net 9 ([709be25](https://github.com/iPromKnight/zilean/commit/709be255de892677fa3155decb61eb81018e3991))

## [2.0.2](https://github.com/iPromKnight/zilean/compare/v2.0.1...v2.0.2) (2024-11-12)


### 🔥 Bug Fixes

* Ensure infohashes only 40 chars in results ([cb4ae26](https://github.com/iPromKnight/zilean/commit/cb4ae26b60a08a083175810fdbe4e2c630fed674))
