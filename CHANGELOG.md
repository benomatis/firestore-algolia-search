# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [0.5.17](https://github.com/benomatis/firestore-algolia-search/compare/v0.5.16...v0.5.17) (2022-10-28)


### Features

* offer choice to choose between multi-line params vs interactive cli inputs for import process ([88d727c](https://github.com/benomatis/firestore-algolia-search/commit/88d727ce2825f9a1672e881c9bfd603e20dd11d9))

### 0.5.16 (2022-10-28)


### Features

* add commandline inputs for import process ([703827f](https://github.com/benomatis/firestore-algolia-search/commit/703827f01321b472efa591e4c0d99e200c146805))
* add data sync ([482b43f](https://github.com/benomatis/firestore-algolia-search/commit/482b43f405e044d6c0b166d95a52ab1c119b8fe3))
* add document path to record ([db43169](https://github.com/benomatis/firestore-algolia-search/commit/db43169be8fd846e335b5cf5737bf6d20e6c766e))
* add import func ([e9acd2d](https://github.com/benomatis/firestore-algolia-search/commit/e9acd2dd5faa6f4671146d327e11fc08549440e1))
* add Timestamp, Reference, and GeoPoint process ([#30](https://github.com/benomatis/firestore-algolia-search/issues/30)) ([d4b7afd](https://github.com/benomatis/firestore-algolia-search/commit/d4b7afdb1168b85594f29aea2db8be60b6d7c2db))
* add transform func processing ([196726f](https://github.com/benomatis/firestore-algolia-search/commit/196726f3068b93b8b0baf171acb281073c68ea80))
* add transform function processing ([2d7362b](https://github.com/benomatis/firestore-algolia-search/commit/2d7362b8981ac5b54c67585bbb282913e02fa4fc))
* add update & delete trigger ([8520960](https://github.com/benomatis/firestore-algolia-search/commit/8520960dc3bb3d00d3434a00a94dc8a3630cdc92))
* Changed API key to type 'secret' ([#81](https://github.com/benomatis/firestore-algolia-search/issues/81)) ([9bbad73](https://github.com/benomatis/firestore-algolia-search/commit/9bbad73805efc0938193af291e3b3ebe8aa36047))
* **config:** support comma-space separated fields ([#53](https://github.com/benomatis/firestore-algolia-search/issues/53)) ([23fdf24](https://github.com/benomatis/firestore-algolia-search/commit/23fdf249084851777d18e08f4ef256631d9e971a)), closes [#52](https://github.com/benomatis/firestore-algolia-search/issues/52)
* create algolia firebase extension ([f5972a0](https://github.com/benomatis/firestore-algolia-search/commit/f5972a0049194f4aa50e61a38b65b89446be5968))
* handle removed attributes ([321cb84](https://github.com/benomatis/firestore-algolia-search/commit/321cb842246df903658c9ea209fb29927cf17e85))
* make module executable for import process. ([7f19030](https://github.com/benomatis/firestore-algolia-search/commit/7f19030de696ae6627111834de6d5b90a21af756))
* offer choice to choose between multi-line params vs interactive cli inputs for import process ([9f5fc28](https://github.com/benomatis/firestore-algolia-search/commit/9f5fc286b369f738064b39e0a5bd1e575d52c8ed))
* **release:** add semver, commitlint, and changelog ([728eb2f](https://github.com/benomatis/firestore-algolia-search/commit/728eb2fd44db5aabafb19886b12b7e622e75fe92))
* update records on changes ([7090405](https://github.com/benomatis/firestore-algolia-search/commit/709040512fd06e44e25bfd178b7451e8c72bd1ae))


### Bug Fixes

* add an 'a' to instructions ([9e020b4](https://github.com/benomatis/firestore-algolia-search/commit/9e020b442e4f9bef573f9b23d95634f4dfbccfa7))
* add compliled import ([481bb7a](https://github.com/benomatis/firestore-algolia-search/commit/481bb7adbd314723c386f38daef1878e58a08cc0))
* add missing param in post install doc ([76c9924](https://github.com/benomatis/firestore-algolia-search/commit/76c99241e754a8a70e055114c83ea4b3f981c8f3))
* add space to import cmd ([dcd591c](https://github.com/benomatis/firestore-algolia-search/commit/dcd591ccdad68082245c4309c6937d3ba936d66b))
* add versioning to solve race condition ([7f34270](https://github.com/benomatis/firestore-algolia-search/commit/7f34270165b538871ff84254562d0e5d23f77a8b))
* add warning and size check ([275da65](https://github.com/benomatis/firestore-algolia-search/commit/275da65cc85cfe2b4a6423c5f32b81765603cecf))
* add Warsaw cloud function location (europe-central2) ([#26](https://github.com/benomatis/firestore-algolia-search/issues/26)) ([4552ba8](https://github.com/benomatis/firestore-algolia-search/commit/4552ba8eab3ff15264329c6badc69693e1e621b9))
* adjust source url in extension.xml ([4d72ab3](https://github.com/benomatis/firestore-algolia-search/commit/4d72ab37b80817ae4600b34e61c742cd29d72b01))
* **agent:** use correct method to augment user agent ([5c7bd42](https://github.com/benomatis/firestore-algolia-search/commit/5c7bd427a5e08de2c20ef2a0451e1a580e92fed9)), closes [/github.com/algolia/algoliasearch-client-javascript/blob/5207d68ff61ef5eeaf4cc4192e375d1ed8c5c413/packages/client-search/src/createSearchClient.ts#L52](https://github.com/benomatis//github.com/algolia/algoliasearch-client-javascript/blob/5207d68ff61ef5eeaf4cc4192e375d1ed8c5c413/packages/client-search/src/createSearchClient.ts/issues/L52)
* change timestamp to a long instead of a string ([#37](https://github.com/benomatis/firestore-algolia-search/issues/37)) ([56e5c29](https://github.com/benomatis/firestore-algolia-search/commit/56e5c294b0b44e0e6c3840dc405f4d1489753093))
* check path for subcollection ([19b9022](https://github.com/benomatis/firestore-algolia-search/commit/19b902282624f2a4e3db747943d6ee5400687748))
* compile index after ua change ([7911f16](https://github.com/benomatis/firestore-algolia-search/commit/7911f16b39de104fbc3b4054896fac85adf17d8d))
* handle boolean field properly ([b8b4993](https://github.com/benomatis/firestore-algolia-search/commit/b8b4993f6f28598f1cff743577d41fed84005ac8))
* import process ([#28](https://github.com/benomatis/firestore-algolia-search/issues/28)) ([47ef9f3](https://github.com/benomatis/firestore-algolia-search/commit/47ef9f3ec542cc29932fa5ee699fa82b11fed79a)), closes [#27](https://github.com/benomatis/firestore-algolia-search/issues/27)
* misspelling on field length check ([7b65a1d](https://github.com/benomatis/firestore-algolia-search/commit/7b65a1d4bb44bd8cca90a0fbf598dd02c652a754))
* move payload check in extract ([f2b1399](https://github.com/benomatis/firestore-algolia-search/commit/f2b1399516f442273b21ee466f292bfb922af22b))
* move rimraf from dev to dependencies ([44a747a](https://github.com/benomatis/firestore-algolia-search/commit/44a747a796709dc84ecab5805bb406611a17a678))
* moving all dev to dependencies ([01d8f66](https://github.com/benomatis/firestore-algolia-search/commit/01d8f665797a19acc821aac3522951837ac5ebeb))
* reimpl proper user agent config ([b850a50](https://github.com/benomatis/firestore-algolia-search/commit/b850a50e187caca0e9d37e71e8dcd66f63b62501))
* remove exit function to allow async to complete ([c7f207c](https://github.com/benomatis/firestore-algolia-search/commit/c7f207c936f71cfe65b2ce21bbea720416aeab61))
* remove null attributes from index record ([e297e27](https://github.com/benomatis/firestore-algolia-search/commit/e297e27e28c8cda6cc6dd274f2bafbbc775781c7))
* remove the data fetch ([23a5da7](https://github.com/benomatis/firestore-algolia-search/commit/23a5da7489766ecdeba9f2c354cc4221aa2cc2fe))
* resolve issues from merge ([9f073be](https://github.com/benomatis/firestore-algolia-search/commit/9f073bed077a5a507b2cbf87c2d80d078bb0fa00))
* security and versioning ([218e547](https://github.com/benomatis/firestore-algolia-search/commit/218e547c2fc93657103e07d8a2d661c7826845a8))
* update package lock ([41bbebc](https://github.com/benomatis/firestore-algolia-search/commit/41bbebc3efc8222f509fa2b51cc1d8a0a17d81bf))
* update the payload size check to 100kb ([cd25055](https://github.com/benomatis/firestore-algolia-search/commit/cd2505515e229ccac985f3f0f9b33fd11fde8faa))

### [0.5.15](https://github.com/algolia/firestore-algolia-search/compare/v0.5.14...v0.5.15) (2022-10-28)


### Bug Fixes

* add compliled import ([481bb7a](https://github.com/algolia/firestore-algolia-search/commit/481bb7adbd314723c386f38daef1878e58a08cc0))
* remove exit function to allow async to complete ([c7f207c](https://github.com/algolia/firestore-algolia-search/commit/c7f207c936f71cfe65b2ce21bbea720416aeab61))

### [0.5.14](https://github.com/algolia/firestore-algolia-search/compare/v0.5.13...v0.5.14) (2022-09-08)


### Bug Fixes

* remove null attributes from index record ([e297e27](https://github.com/algolia/firestore-algolia-search/commit/e297e27e28c8cda6cc6dd274f2bafbbc775781c7))

### [0.5.13](https://github.com/algolia/firestore-algolia-search/compare/v0.5.12...v0.5.13) (2022-06-20)


### Features

* add commandline inputs for import process ([703827f](https://github.com/algolia/firestore-algolia-search/commit/703827f01321b472efa591e4c0d99e200c146805))

### [0.5.12](https://github.com/algolia/firestore-algolia-search/compare/v0.5.11...v0.5.12) (2022-06-06)


### Bug Fixes

* moving all dev to dependencies ([01d8f66](https://github.com/algolia/firestore-algolia-search/commit/01d8f665797a19acc821aac3522951837ac5ebeb))

### [0.5.11](https://github.com/algolia/firestore-algolia-search/compare/v0.5.10...v0.5.11) (2022-06-06)


### Bug Fixes

* move rimraf from dev to dependencies ([44a747a](https://github.com/algolia/firestore-algolia-search/commit/44a747a796709dc84ecab5805bb406611a17a678))

### [0.5.10](https://github.com/algolia/firestore-algolia-search/compare/v0.5.9...v0.5.10) (2022-05-13)


### Features

* add data sync ([482b43f](https://github.com/algolia/firestore-algolia-search/commit/482b43f405e044d6c0b166d95a52ab1c119b8fe3))

### [0.5.9](https://github.com/algolia/firestore-algolia-search/compare/v0.5.8...v0.5.9) (2021-11-15)


### Features

* Changed API key to type 'secret' ([#81](https://github.com/algolia/firestore-algolia-search/issues/81)) ([9bbad73](https://github.com/algolia/firestore-algolia-search/commit/9bbad73805efc0938193af291e3b3ebe8aa36047))

### [0.5.8](https://github.com/algolia/firestore-algolia-search/compare/v0.5.2...v0.5.8) (2021-10-27)


### Features

* add document path to record ([db43169](https://github.com/algolia/firestore-algolia-search/commit/db43169be8fd846e335b5cf5737bf6d20e6c766e))
* handle removed attributes ([321cb84](https://github.com/algolia/firestore-algolia-search/commit/321cb842246df903658c9ea209fb29927cf17e85))
* **release:** add semver, commitlint, and changelog ([728eb2f](https://github.com/algolia/firestore-algolia-search/commit/728eb2fd44db5aabafb19886b12b7e622e75fe92))


### Bug Fixes

* check path for subcollection ([19b9022](https://github.com/algolia/firestore-algolia-search/commit/19b902282624f2a4e3db747943d6ee5400687748))
* remove the data fetch ([23a5da7](https://github.com/algolia/firestore-algolia-search/commit/23a5da7489766ecdeba9f2c354cc4221aa2cc2fe))
* security and versioning ([218e547](https://github.com/algolia/firestore-algolia-search/commit/218e547c2fc93657103e07d8a2d661c7826845a8))

### [0.5.7](https://github.com/algolia/firestore-algolia-search/compare/v0.5.2...v0.5.7) (2021-10-13)


### Features

* add document path to record ([db43169](https://github.com/algolia/firestore-algolia-search/commit/db43169be8fd846e335b5cf5737bf6d20e6c766e))
* handle removed attributes ([321cb84](https://github.com/algolia/firestore-algolia-search/commit/321cb842246df903658c9ea209fb29927cf17e85))
* **release:** add semver, commitlint, and changelog ([728eb2f](https://github.com/algolia/firestore-algolia-search/commit/728eb2fd44db5aabafb19886b12b7e622e75fe92))


### Bug Fixes

* remove the data fetch ([23a5da7](https://github.com/algolia/firestore-algolia-search/commit/23a5da7489766ecdeba9f2c354cc4221aa2cc2fe))

### [0.5.6](https://github.com/algolia/firestore-algolia-search/compare/v0.5.2...v0.5.6) (2021-10-13)


### Features

* add document path to record ([db43169](https://github.com/algolia/firestore-algolia-search/commit/db43169be8fd846e335b5cf5737bf6d20e6c766e))
* handle removed attributes ([321cb84](https://github.com/algolia/firestore-algolia-search/commit/321cb842246df903658c9ea209fb29927cf17e85))
* **release:** add semver, commitlint, and changelog ([728eb2f](https://github.com/algolia/firestore-algolia-search/commit/728eb2fd44db5aabafb19886b12b7e622e75fe92))


### Bug Fixes

* remove the data fetch ([23a5da7](https://github.com/algolia/firestore-algolia-search/commit/23a5da7489766ecdeba9f2c354cc4221aa2cc2fe))

### [0.5.5](https://github.com/algolia/firestore-algolia-search/compare/v0.5.2...v0.5.5) (2021-10-06)


### Features

* handle removed attributes ([321cb84](https://github.com/algolia/firestore-algolia-search/commit/321cb842246df903658c9ea209fb29927cf17e85))
* **release:** add semver, commitlint, and changelog ([728eb2f](https://github.com/algolia/firestore-algolia-search/commit/728eb2fd44db5aabafb19886b12b7e622e75fe92))


### Bug Fixes

* remove the data fetch ([23a5da7](https://github.com/algolia/firestore-algolia-search/commit/23a5da7489766ecdeba9f2c354cc4221aa2cc2fe))

### [0.5.4](https://github.com/algolia/firestore-algolia-search/compare/v0.5.2...v0.5.4) (2021-09-29)


### Features

* handle removed attributes ([321cb84](https://github.com/algolia/firestore-algolia-search/commit/321cb842246df903658c9ea209fb29927cf17e85))
* **release:** add semver, commitlint, and changelog ([728eb2f](https://github.com/algolia/firestore-algolia-search/commit/728eb2fd44db5aabafb19886b12b7e622e75fe92))


### Bug Fixes

* remove the data fetch ([23a5da7](https://github.com/algolia/firestore-algolia-search/commit/23a5da7489766ecdeba9f2c354cc4221aa2cc2fe))

### [0.5.3](https://github.com/algolia/firestore-algolia-search/compare/v0.5.2...v0.5.3) (2021-09-28)


### Features

* handle removed attributes ([321cb84](https://github.com/algolia/firestore-algolia-search/commit/321cb842246df903658c9ea209fb29927cf17e85))
* **release:** add semver, commitlint, and changelog ([728eb2f](https://github.com/algolia/firestore-algolia-search/commit/728eb2fd44db5aabafb19886b12b7e622e75fe92))
