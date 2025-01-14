## [5.1.3](https://github.com/webtorrent/webtorrent-cli/compare/v5.1.2...v5.1.3) (2024-12-12)

## [5.1.2](https://github.com/webtorrent/webtorrent-cli/compare/v5.1.1...v5.1.2) (2024-06-14)


### Bug Fixes

* include version.cjs in the .npmignore, which is preventing the published package from functioning correctly. ([#311](https://github.com/webtorrent/webtorrent-cli/issues/311)) ([c3138e0](https://github.com/webtorrent/webtorrent-cli/commit/c3138e02ed9f508b4878b86ab29332a2d4543a92))

## [5.1.1](https://github.com/webtorrent/webtorrent-cli/compare/v5.1.0...v5.1.1) (2024-06-13)


### Bug Fixes

* update version import to be consistent with WebTorrent ([#310](https://github.com/webtorrent/webtorrent-cli/issues/310)) ([4bf287b](https://github.com/webtorrent/webtorrent-cli/commit/4bf287b2242e6ea2cf98c9e65659599f62fdef4b))

# [5.1.0](https://github.com/webtorrent/webtorrent-cli/compare/v5.0.1...v5.1.0) (2024-06-02)


### Features

* add magnetURI on seeding and infoHash on downloading ([#308](https://github.com/webtorrent/webtorrent-cli/issues/308)) ([b36a82e](https://github.com/webtorrent/webtorrent-cli/commit/b36a82e4d3cfb9f7f3b59577535b97075069121c))

## [5.0.1](https://github.com/webtorrent/webtorrent-cli/compare/v5.0.0...v5.0.1) (2024-06-02)


### Bug Fixes

* -s / --select not working ([#304](https://github.com/webtorrent/webtorrent-cli/issues/304)) ([825b0ee](https://github.com/webtorrent/webtorrent-cli/commit/825b0eed54123f81ce4fe67ba638095aa7eda80b))

# [5.0.0](https://github.com/webtorrent/webtorrent-cli/compare/v4.1.0...v5.0.0) (2024-06-02)


* BREAKING CHANGE: Update WebTorrent to v2 and drop NodeJS < 16 (#303) ([3e34c7f](https://github.com/webtorrent/webtorrent-cli/commit/3e34c7f69ff2041be5c8d12b130959a1b58111cc)), closes [#303](https://github.com/webtorrent/webtorrent-cli/issues/303)


### BREAKING CHANGES

* Update WebTorrent to v2 and drop support for NodeJS < 16

* feat: update create-torrent to 6.0.17

* feat: improve logging by including peer type (TCP,UTP,WEBRTC,WEBSEED)

* fix: update ci to drop NodeJS 14

* fix: update docs to reflect changes, adds webrtc connectivity but requires native deps.

# [4.1.0](https://github.com/webtorrent/webtorrent-cli/compare/v4.0.4...v4.1.0) (2022-06-02)


### Features

* add peerflix-style interactive select mode ([#234](https://github.com/webtorrent/webtorrent-cli/issues/234)) ([4540a0a](https://github.com/webtorrent/webtorrent-cli/commit/4540a0af33a09779f5847a255d986add28688483))

## [4.0.4](https://github.com/webtorrent/webtorrent-cli/compare/v4.0.3...v4.0.4) (2022-03-09)


### Bug Fixes

* webtorrent version resolve ([a6d3ee7](https://github.com/webtorrent/webtorrent-cli/commit/a6d3ee75b74a645022971a06797d59a2e4da2707))

## [4.0.3](https://github.com/webtorrent/webtorrent-cli/compare/v4.0.2...v4.0.3) (2022-02-03)


### Bug Fixes

* **deps:** update dependency mime to v3 ([#201](https://github.com/webtorrent/webtorrent-cli/issues/201)) ([0427557](https://github.com/webtorrent/webtorrent-cli/commit/04275570cde6fa2aedf78ffd0321891b7a0999b5))

## [4.0.2](https://github.com/webtorrent/webtorrent-cli/compare/v4.0.1...v4.0.2) (2022-01-04)


### Bug Fixes

* dynamic imports ([ad2f997](https://github.com/webtorrent/webtorrent-cli/commit/ad2f997c28859f9f7f9715244f25e95eb827b5f4))

## [4.0.1](https://github.com/webtorrent/webtorrent-cli/compare/v4.0.0...v4.0.1) (2022-01-04)


### Bug Fixes

* npm global install permissions issue ([#210](https://github.com/webtorrent/webtorrent-cli/issues/210)) ([8e4c77f](https://github.com/webtorrent/webtorrent-cli/commit/8e4c77f791e5811f56284adc74ff6fc0666b2149))

# [4.0.0](https://github.com/webtorrent/webtorrent-cli/compare/v3.5.4...v4.0.0) (2021-09-17)


### chore

* switch to ESM (BREAKING) ([#197](https://github.com/webtorrent/webtorrent-cli/issues/197)) ([0bc380d](https://github.com/webtorrent/webtorrent-cli/commit/0bc380dc83de8caf84cf7969542afadf3dbc6329))


### BREAKING CHANGES

* switch to ESM

## [3.5.4](https://github.com/webtorrent/webtorrent-cli/compare/v3.5.3...v3.5.4) (2021-08-06)


### Bug Fixes

* **deps:** update dependency create-torrent to v5 ([74877da](https://github.com/webtorrent/webtorrent-cli/commit/74877da76166fb595d2df431ff2bf368713e27c6))

## [3.5.3](https://github.com/webtorrent/webtorrent-cli/compare/v3.5.2...v3.5.3) (2021-07-18)


### Bug Fixes

* removal of ascii-logo.txt ([#181](https://github.com/webtorrent/webtorrent-cli/issues/181)) ([d528345](https://github.com/webtorrent/webtorrent-cli/commit/d528345812470375b8cb033de0940e54485ef5f5))

## [3.5.2](https://github.com/webtorrent/webtorrent-cli/compare/v3.5.1...v3.5.2) (2021-07-16)


### Bug Fixes

* specify option types explicitly ([#179](https://github.com/webtorrent/webtorrent-cli/issues/179)) ([878c2f7](https://github.com/webtorrent/webtorrent-cli/commit/878c2f7568c34e40a4b3467c480e9026cc9377c2))

## [3.5.1](https://github.com/webtorrent/webtorrent-cli/compare/v3.5.0...v3.5.1) (2021-07-15)


### Bug Fixes

* standard fix, remove executable ([d028284](https://github.com/webtorrent/webtorrent-cli/commit/d028284f68b4d4ce7ac235a4741aeadcbf7685b1))

# [3.5.0](https://github.com/webtorrent/webtorrent-cli/compare/v3.4.1...v3.5.0) (2021-07-15)


### Features

* add playlist option ([#168](https://github.com/webtorrent/webtorrent-cli/issues/168)) ([a003e7e](https://github.com/webtorrent/webtorrent-cli/commit/a003e7e6badeb62d52f7945c4526163a81015d19))

## [3.4.1](https://github.com/webtorrent/webtorrent-cli/compare/v3.4.0...v3.4.1) (2021-07-15)


### Bug Fixes

* multiple torrent downloads ([#177](https://github.com/webtorrent/webtorrent-cli/issues/177)) ([1a75830](https://github.com/webtorrent/webtorrent-cli/commit/1a7583044f14c34d1d4c76ec526ae446ecd461ac))

# [3.4.0](https://github.com/webtorrent/webtorrent-cli/compare/v3.3.2...v3.4.0) (2021-07-14)


### Features

* allow script arguments ([#176](https://github.com/webtorrent/webtorrent-cli/issues/176)) ([e6228ab](https://github.com/webtorrent/webtorrent-cli/commit/e6228ab6141445b1f9dc2b3a0256522a9a47bfb6))

## [3.3.2](https://github.com/webtorrent/webtorrent-cli/compare/v3.3.1...v3.3.2) (2021-07-14)


### Bug Fixes

* Chromecast logic & typo ([#175](https://github.com/webtorrent/webtorrent-cli/issues/175)) ([8234278](https://github.com/webtorrent/webtorrent-cli/commit/8234278a4bab58f47a13aed5484eff8482e57e17))

## [3.3.1](https://github.com/webtorrent/webtorrent-cli/compare/v3.3.0...v3.3.1) (2021-07-09)


### Code Refactoring

* move to yargs, use chalk ([#144](https://github.com/webtorrent/webtorrent-cli/issues/144)) ([177bc48](https://github.com/webtorrent/webtorrent-cli/commit/177bc480ce184a312e1c164c30acb890a8357ffe))


### BREAKING CHANGES

* * Create new branch: revamp

* Complete revamp

* Added quote function

* Bugfixes

* Bugfixes

* Replace console.log with process.stdout.write

* Bugfixes

* Cleanup dependencies

* Added feature

* Standard --fix

* Update docs

* Standard --fix

* Fix small bug

* Standard --fix

* Multiple torrent downloads fix

* Less hard coding

* Small adjustments

* Fix optiongroup order

* Replace yargs with minimist wrapper

* Revert commit: 94c561c

* Pull changes 3.2.1

* Pull changes 3.2.1

* Fix busy port issue

* Small fixes

* Small changes

* Small fixes

* Small fixes

* Small changes

* Remove unnecessary complexity

* Webtorrent 0.112.0

* Small fixes

* Small fix

* Remove clivas.flush

* Revert removal

* Replace Clivas with Chalk and console.log

* Yargs 16.2.0

* Small fix

* Small improvements

* dependency fix

* Yargs 17.0.1

* Update .gitignore

* Update .gitignore

* Add [default] to download description

* Remove regions

* Update .gitignore

Co-authored-by: Osman Altun <oaltun@quintor.local>
Co-authored-by: Diego Rodríguez Baquero <github@diegorbaquero.com>

# [3.3.0](https://github.com/webtorrent/webtorrent-cli/compare/v3.2.4...v3.3.0) (2021-06-08)


### Features

* add support for SMPlayer ([#154](https://github.com/webtorrent/webtorrent-cli/issues/154)) ([875d035](https://github.com/webtorrent/webtorrent-cli/commit/875d035538c1f6cc22353c8e00e685e622af2f54))

## [3.2.4](https://github.com/webtorrent/webtorrent-cli/compare/v3.2.3...v3.2.4) (2021-05-31)


### Bug Fixes

* **deps:** update dependency open to v8 ([#156](https://github.com/webtorrent/webtorrent-cli/issues/156)) ([aeb104d](https://github.com/webtorrent/webtorrent-cli/commit/aeb104d5e14e9e6bbf76cb56fa0373308761646c))

## [3.2.3](https://github.com/webtorrent/webtorrent-cli/compare/v3.2.2...v3.2.3) (2021-05-31)


### Bug Fixes

* update engines to node >=12 ([a282fa6](https://github.com/webtorrent/webtorrent-cli/commit/a282fa6908e2ccf371e49a41422bb16d5adffa19))

## [3.2.2](https://github.com/webtorrent/webtorrent-cli/compare/v3.2.1...v3.2.2) (2021-05-31)


### Bug Fixes

* **deps:** update dependency parse-torrent to v9 ([a2cb7f9](https://github.com/webtorrent/webtorrent-cli/commit/a2cb7f9e86198472c564a16d57a8aa96d9dc465c))
