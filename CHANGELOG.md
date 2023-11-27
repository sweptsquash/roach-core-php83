# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 1.0.0 (2023-11-27)


### ⚠ BREAKING CHANGES

* add namespace to run and scheduler ([#105](https://github.com/sweptsquash/roach-core-php83/issues/105))

### Features

* add namespace to run and scheduler ([#105](https://github.com/sweptsquash/roach-core-php83/issues/105)) ([167e824](https://github.com/sweptsquash/roach-core-php83/commit/167e824362a9507caa3cc03200eb546d51e35437))
* Add PHP 8.3 to composer.json ([31c305e](https://github.com/sweptsquash/roach-core-php83/commit/31c305ec759ea3fe0064d2d48bd6721966f50a72))
* add ResponseReceiving and ResponseReceived events ([96c9332](https://github.com/sweptsquash/roach-core-php83/commit/96c9332c796cf8c64ca8bd15885580b49354a78c))
* allow request middleware to set a response to bypass downloader ([#106](https://github.com/sweptsquash/roach-core-php83/issues/106)) ([d8ae43e](https://github.com/sweptsquash/roach-core-php83/commit/d8ae43ea5efb7f1cd729fc6dab19756beddb4702))


### Bug Fixes

* disable PhpCsFixerCustomFixers/phpdoc_array_style breaking psalm check ([a5c9874](https://github.com/sweptsquash/roach-core-php83/commit/a5c9874cea45f11bbff8649f22451ef62abfbf2f))
* IntegrationTestCase unlink tmp file on setUp ([6cf4481](https://github.com/sweptsquash/roach-core-php83/commit/6cf4481bf6ae35eef906f1e9f487ed1eca8c2bef))
* PHP-CS-Fixer and Psalm ([da81bae](https://github.com/sweptsquash/roach-core-php83/commit/da81bae331ae555ae906d3f20147872c2f82ab12))
* PHP-CS-Fixer ruleset creation ([31c305e](https://github.com/sweptsquash/roach-core-php83/commit/31c305ec759ea3fe0064d2d48bd6721966f50a72))
* Psalm errors ([ddfc652](https://github.com/sweptsquash/roach-core-php83/commit/ddfc652877485125095e486a2593d5c8698e1228))
* rename integration tests so they actually get run ([33eb25e](https://github.com/sweptsquash/roach-core-php83/commit/33eb25e31769d1d3080174341efeac06cd89ee45))
* Workflow actions to use latest versions ([6cf4481](https://github.com/sweptsquash/roach-core-php83/commit/6cf4481bf6ae35eef906f1e9f487ed1eca8c2bef))


### Miscellaneous Chores

* (deps): bump symfony/console from 6.2.5 to 6.2.7 ([#93](https://github.com/sweptsquash/roach-core-php83/issues/93)) ([4f535da](https://github.com/sweptsquash/roach-core-php83/commit/4f535da0d95f6e5a88bea4c1e5d9c7f3219388c6))
* (deps): bump symfony/css-selector from 6.2.5 to 6.2.7 ([20fc15b](https://github.com/sweptsquash/roach-core-php83/commit/20fc15b708c6c486b49a2c766630b42512df25c6))
* (deps): bump symfony/dom-crawler from 6.2.5 to 6.2.7 ([#92](https://github.com/sweptsquash/roach-core-php83/issues/92)) ([25e4831](https://github.com/sweptsquash/roach-core-php83/commit/25e48316e49408ad2ce120e76d56fa70be8864dc))
* add code of conduct ([ed80fbe](https://github.com/sweptsquash/roach-core-php83/commit/ed80fbe7919d0a518d54a4ba48b8cefb0565f6cc))
* add CODEOWNERS file ([9efec92](https://github.com/sweptsquash/roach-core-php83/commit/9efec92ce1ba244cbd205037e8c3463d6986f054))
* add commitlint step to pipeline ([64e785a](https://github.com/sweptsquash/roach-core-php83/commit/64e785a0a04c5697ec91f17905190cbc062512ce))
* add contribution guide ([bdb57e0](https://github.com/sweptsquash/roach-core-php83/commit/bdb57e0824cb4c883be3d9109696c74d88586644))
* add issue templates ([5c4fd81](https://github.com/sweptsquash/roach-core-php83/commit/5c4fd81a3a3caa7ee6b3ab42d69f85d0e02dbfbe))
* apply cs fixes ([1c628d0](https://github.com/sweptsquash/roach-core-php83/commit/1c628d0e898070d1b37b1741e730b756a32e377e))
* bump ergebnis/php-cs-fixer-config to 6.11.0 ([31c305e](https://github.com/sweptsquash/roach-core-php83/commit/31c305ec759ea3fe0064d2d48bd6721966f50a72))
* bump other packages ([31c305e](https://github.com/sweptsquash/roach-core-php83/commit/31c305ec759ea3fe0064d2d48bd6721966f50a72))
* coding-standards ([31c305e](https://github.com/sweptsquash/roach-core-php83/commit/31c305ec759ea3fe0064d2d48bd6721966f50a72))
* **deps-dev:** bump ergebnis/composer-normalize from 2.29.0 to 2.30.2 ([980b920](https://github.com/sweptsquash/roach-core-php83/commit/980b92040b6f6ea38907a49d296f69f9a91ab606))
* **deps-dev:** bump ergebnis/php-cs-fixer-config from 5.3.1 to 5.3.2 ([44d81c9](https://github.com/sweptsquash/roach-core-php83/commit/44d81c9855542fec1f8f1c342d666e1ca6680350))
* **deps-dev:** bump ergebnis/php-cs-fixer-config from 5.3.2 to 5.3.3 ([7b6f59f](https://github.com/sweptsquash/roach-core-php83/commit/7b6f59fab7bb75efcbacc848122ed23b840b560f))
* **deps-dev:** bump ergebnis/php-cs-fixer-config from 5.3.3 to 5.4.0 ([#113](https://github.com/sweptsquash/roach-core-php83/issues/113)) ([cfaae68](https://github.com/sweptsquash/roach-core-php83/commit/cfaae68eea8107d6fd755fb7f2e1e3d661a5ff80))
* **deps-dev:** bump ergebnis/php-cs-fixer-config from 5.4.0 to 5.7.0 ([#127](https://github.com/sweptsquash/roach-core-php83/issues/127)) ([61b2d2a](https://github.com/sweptsquash/roach-core-php83/commit/61b2d2a8fa5d1aad0907ce9c7b58c64fa94dfca6))
* **deps-dev:** bump phpunit/phpunit from 10.0.15 to 10.0.16 ([57b4d03](https://github.com/sweptsquash/roach-core-php83/commit/57b4d03bd6ca00c5b17af81ac8ebbc8382c91677))
* **deps-dev:** bump phpunit/phpunit from 10.0.16 to 10.0.18 ([a5fe27a](https://github.com/sweptsquash/roach-core-php83/commit/a5fe27ad0cadb3f74da4916f7b1a97d27abe144c))
* **deps-dev:** bump phpunit/phpunit from 10.0.18 to 10.2.0 ([#130](https://github.com/sweptsquash/roach-core-php83/issues/130)) ([355a1e6](https://github.com/sweptsquash/roach-core-php83/commit/355a1e60687d77033202cd024ef3a9177af3ffa0))
* **deps-dev:** bump phpunit/phpunit from 10.2.0 to 10.3.2 ([9aded43](https://github.com/sweptsquash/roach-core-php83/commit/9aded43194f8784fbc57de1ee8e5e98323824e30))
* **deps-dev:** bump vimeo/psalm from 5.6.0 to 5.8.0 ([b60588a](https://github.com/sweptsquash/roach-core-php83/commit/b60588ad6e60bd6eb8146466202bd8baf12ad8f0))
* **deps-dev:** bump vimeo/psalm from 5.8.0 to 5.9.0 ([#110](https://github.com/sweptsquash/roach-core-php83/issues/110)) ([0ef0d78](https://github.com/sweptsquash/roach-core-php83/commit/0ef0d781c207a2634116c422702917db062743ba))
* **deps-dev:** bump vimeo/psalm from 5.9.0 to 5.15.0 ([4835458](https://github.com/sweptsquash/roach-core-php83/commit/483545871a321b522a29629d7293e58288e8a032))
* **deps:** bump guzzlehttp/guzzle from 7.5.0 to 7.8.0 ([0c4e817](https://github.com/sweptsquash/roach-core-php83/commit/0c4e817acd3a4f253fe87db7958402277ff4ce34))
* **deps:** bump guzzlehttp/psr7 from 2.4.3 to 2.5.0 ([#120](https://github.com/sweptsquash/roach-core-php83/issues/120)) ([7572aae](https://github.com/sweptsquash/roach-core-php83/commit/7572aaefa6f1f310f2faab6d7bc7ffd4ebccbf2a))
* **deps:** bump psy/psysh from 0.11.12 to 0.11.13 ([4542cbf](https://github.com/sweptsquash/roach-core-php83/commit/4542cbf00fe2b02a86d5b2048a97556706adf44f))
* **deps:** bump psy/psysh from 0.11.13 to 0.11.18 ([#128](https://github.com/sweptsquash/roach-core-php83/issues/128)) ([8e940ef](https://github.com/sweptsquash/roach-core-php83/commit/8e940efce2d4452d03a4fb3e7dc8418968628e7d))
* **deps:** bump symfony/console from 6.2.7 to 6.2.8 ([#111](https://github.com/sweptsquash/roach-core-php83/issues/111)) ([c24018c](https://github.com/sweptsquash/roach-core-php83/commit/c24018c83fd7d517f4ab9c96f2db533198df7b6a))
* **deps:** bump symfony/css-selector from 6.2.7 to 6.3.2 ([34e38b9](https://github.com/sweptsquash/roach-core-php83/commit/34e38b9e42e0c10e44b7d8b9b0b1bc30b3f66c6d))
* **deps:** bump symfony/dom-crawler from 6.2.7 to 6.2.8 ([#109](https://github.com/sweptsquash/roach-core-php83/issues/109)) ([8302a9a](https://github.com/sweptsquash/roach-core-php83/commit/8302a9a4b071c5726f78e728f3e3b4f524313025))
* **deps:** bump symfony/dom-crawler from 6.2.8 to 6.2.9 ([#118](https://github.com/sweptsquash/roach-core-php83/issues/118)) ([1099794](https://github.com/sweptsquash/roach-core-php83/commit/1099794ea5e6016f01bc0f956fa644a1a5aca4b3))
* **deps:** bump symfony/event-dispatcher from 6.2.5 to 6.2.7 ([3a19510](https://github.com/sweptsquash/roach-core-php83/commit/3a19510e0457867f0a307c8511e2cb0ef85a8e6b))
* **deps:** bump symfony/event-dispatcher from 6.2.8 to 6.3.2 ([fdfa495](https://github.com/sweptsquash/roach-core-php83/commit/fdfa4956097b041acfcb67cfb8415a65a2425ace))
* **deps:** bump symfony/options-resolver from 6.2.5 to 6.2.7 ([#89](https://github.com/sweptsquash/roach-core-php83/issues/89)) ([fe24ee3](https://github.com/sweptsquash/roach-core-php83/commit/fe24ee3241546c3dc968537b344040dd9bb3c483))
* include nyholm/psr7 and nyholm/psr7-server to resolve RuntimeException for PSR-17 ResponseFactory implementations ([edac6f7](https://github.com/sweptsquash/roach-core-php83/commit/edac6f749e04c5dc79a3601fea1d32fa0776770a))
* remove unused reference ([7f55429](https://github.com/sweptsquash/roach-core-php83/commit/7f55429c1abb9a336b7e7a471afa7289d193f88e))
* set up dependabot ([29fb85e](https://github.com/sweptsquash/roach-core-php83/commit/29fb85ee3e7db67b855a2999b1af592253043e1a))
* set up release please action ([5a7df32](https://github.com/sweptsquash/roach-core-php83/commit/5a7df32ca5fc8816fd4e7b6273eb5071f1203e00))
* upgrade to phpunit 10 ([fd83095](https://github.com/sweptsquash/roach-core-php83/commit/fd830953f85f3ad7a06c04988ca39a24718c5e46))

## [2.0.1] – 2023-02-17

### Fixed

- Fixed version incompatibility with `sebastian/version` depenency

## [2.0.0] – 2023-02-06

### Added

- Added `userAgent` option to `ExecuteJavascriptMiddleware` (#82)
- Added `delay` option to `ExecuteJavascriptMiddleware` (#72)

### Changed

- Dropped PHP 8.0 support
- Updated various dependencies

## [1.1.1] — 2022-09-09

### Changed

- `ExecuteJavascriptMiddleware` now uses `waitUntilNetworkIdle` before returning the response body (#56)

## [1.1.0] — 2022-06-22

### Added

- Added a way to define custom item classes as well as item processors which only process certain
  types of items (#47)

### Changed

- Fixed deprecation warning in console commands for `symfony/console:^6.1` (#44)

## [1.0.0] — 2022-04-19

### Added

- Added `Roach::collectSpider` method to start a spider run and return all scraped items.
- Added `array $context` parameter to `Roach::startSpider` and `Roach::collectSpider` to pass arbitrary
  context data to a spider when starting a run.
- Added `roach:run <spider>` command to start a spider through the CLI.
- Added `Roach::fake()` method to test that a run for a given spider was started

### Changed

- Requests dropped by downloader middleware are no longer affected by `requestDelay` (fixes #27)
- Move `spatie/browsershot` from a `require` to `suggest` as it's only necessary if the `ExecuteJavascriptMiddleware` is used.
  Remove `ext-exif` as a dependency for the same reason.

### Removed

- Removed default command from CLI. To start the REPL, you now need to explicitly invoke the `roach:shell <url>` command, instead.

## [0.2.0] - 2021-12-28

### Added

- Added `ExecuteJavascriptMiddleware` to retrieve a page’s body after executing Javascript (#7)

## [0.1.0] - 2021-12-27

### Added

- Initial release

[2.0.0]: https://github.com/roach-php/core/compare/1.1.1...2.0.0
[1.1.1]: https://github.com/roach-php/core/compare/1.1.0...1.1.1
[1.1.0]: https://github.com/roach-php/core/compare/1.0.0...1.1.0
[1.0.0]: https://github.com/roach-php/core/compare/0.2.0...1.0.0
[0.2.0]: https://github.com/roach-php/core/compare/0.1.0...0.2.0
