## [3.2.2](https://github.com/FarmData2/FD2-SampleDBs/compare/v3.2.1...v3.2.2) (2024-01-25)


### Fixes

* drops the creation of log categories ([#39](https://github.com/FarmData2/FD2-SampleDBs/issues/39)) ([b29e049](https://github.com/FarmData2/FD2-SampleDBs/commit/b29e049bfae0913d6a8de0bce4a65938fe989329))

## [3.2.1](https://github.com/FarmData2/FD2-SampleDBs/compare/v3.2.0...v3.2.1) (2024-01-24)


### Fixes

* clarifies and adjusts the FarmData2 log categories ([#38](https://github.com/FarmData2/FD2-SampleDBs/issues/38)) ([f71814c](https://github.com/FarmData2/FD2-SampleDBs/commit/f71814c24d6d52d4bbbbae050a97e572869a7b31))

## [3.2.0](https://github.com/FarmData2/FD2-SampleDBs/compare/v3.1.0...v3.2.0) (2024-01-23)


### Features

* adds log categories for PASA SHBS ([#37](https://github.com/FarmData2/FD2-SampleDBs/issues/37)) ([ecb87c4](https://github.com/FarmData2/FD2-SampleDBs/commit/ecb87c40db2bb8b340c96179c3d2c37cfebff2ab)), closes [#36](https://github.com/FarmData2/FD2-SampleDBs/issues/36)

## [3.1.0](https://github.com/FarmData2/FD2-SampleDBs/compare/v3.0.0...v3.1.0) (2024-01-18)


### Features

* add log category for soil disturbances ([#35](https://github.com/FarmData2/FD2-SampleDBs/issues/35)) ([3a2e4b7](https://github.com/FarmData2/FD2-SampleDBs/commit/3a2e4b7d91a843b6892ace81eff88faeee55fc38))
* adds generic equipment for seedings to sample database ([#31](https://github.com/FarmData2/FD2-SampleDBs/issues/31)) ([1ca8802](https://github.com/FarmData2/FD2-SampleDBs/commit/1ca880217688c04f466e17a3002de8aa8e648293))


### Fixes

* "revert: "fix: updates sample db image in dist"" ([#34](https://github.com/FarmData2/FD2-SampleDBs/issues/34)) ([df91e03](https://github.com/FarmData2/FD2-SampleDBs/commit/df91e039e659b07bdb730ba9f13992797ab03eb9)), closes [FarmData2/FD2-SampleDBs#33](https://github.com/FarmData2/FD2-SampleDBs/issues/33)
* updates sample db image in dist ([#32](https://github.com/FarmData2/FD2-SampleDBs/issues/32)) ([893d65b](https://github.com/FarmData2/FD2-SampleDBs/commit/893d65b84542d3b5d68e934e7028706b718c3d3b))

## [3.0.0](https://github.com/FarmData2/FD2-SampleDBs/compare/v2.0.1...v3.0.0) (2023-12-30)


### ⚠ BREAKING CHANGES

* Changes the areas and crops that appear in the sample
database which will break FarmData2 tests.

### Features

* reduces size of sample database ([#30](https://github.com/FarmData2/FD2-SampleDBs/issues/30)) ([f78cee4](https://github.com/FarmData2/FD2-SampleDBs/commit/f78cee4ec054dd66a324ac4fa241f60790c17442)), closes [#27](https://github.com/FarmData2/FD2-SampleDBs/issues/27) [#28](https://github.com/FarmData2/FD2-SampleDBs/issues/28) [#29](https://github.com/FarmData2/FD2-SampleDBs/issues/29)

## [2.0.1](https://github.com/FarmData2/FD2-SampleDBs/compare/v2.0.0...v2.0.1) (2023-12-12)


### Fixes

* removes ssl key creation from sample DB build ([#26](https://github.com/FarmData2/FD2-SampleDBs/issues/26)) ([a73f630](https://github.com/FarmData2/FD2-SampleDBs/commit/a73f6306b781f435c3f35fb120f7391a256debe8))

## [2.0.0](https://github.com/FarmData2/FD2-SampleDBs/compare/v1.5.3...v2.0.0) (2023-12-12)


### ⚠ BREAKING CHANGES

* database images are built using farmOS v3.x and
postgres v13.
* migrates to farmos3 and postgres 13 (#21)

### Features

* migrates to farmOS and postgres 13 ([#23](https://github.com/FarmData2/FD2-SampleDBs/issues/23)) ([729f80c](https://github.com/FarmData2/FD2-SampleDBs/commit/729f80c023ea74e45406bebd785cc713064c8569))
* migrates to farmos3 and postgres 13 ([#21](https://github.com/FarmData2/FD2-SampleDBs/issues/21)) ([dc606e8](https://github.com/FarmData2/FD2-SampleDBs/commit/dc606e82953e5357e7a32880774504534f9f42aa))

## [1.5.3](https://github.com/FarmData2/FD2-SampleDBs/compare/v1.5.2...v1.5.3) (2023-12-05)


### Fixes

* includes the zipped db ([d367ab4](https://github.com/FarmData2/FD2-SampleDBs/commit/d367ab4332a41d359fb183cd79b74f74fd81ab9e))

## [1.5.2](https://github.com/FarmData2/FD2-SampleDBs/compare/v1.5.1...v1.5.2) (2023-12-05)


### Fixes

* makes units for tray seedings consistent ([#19](https://github.com/FarmData2/FD2-SampleDBs/issues/19)) ([0a5ea3c](https://github.com/FarmData2/FD2-SampleDBs/commit/0a5ea3c06014fbee32e886b9c15c069c5033c6d4))

## [1.5.1](https://github.com/FarmData2/FD2-SampleDBs/compare/v1.5.0...v1.5.1) (2023-11-29)


### Fixes

* adds zipped sample db ([#17](https://github.com/FarmData2/FD2-SampleDBs/issues/17)) ([362884e](https://github.com/FarmData2/FD2-SampleDBs/commit/362884ec76698d127f6ad49137bee0766690a9d1))

## [1.5.0](https://github.com/FarmData2/FD2-SampleDBs/compare/v1.4.0...v1.5.0) (2023-11-29)


### Features

* enables the farmOS inventory module ([#16](https://github.com/FarmData2/FD2-SampleDBs/issues/16)) ([80a9c8b](https://github.com/FarmData2/FD2-SampleDBs/commit/80a9c8bfaeafb8cfd3fd207d87f9615ea143c978))

## [1.4.0](https://github.com/FarmData2/FD2-SampleDBs/compare/v1.3.0...v1.4.0) (2023-11-21)


### Features

* adds log categories to the sample database ([#15](https://github.com/FarmData2/FD2-SampleDBs/issues/15)) ([824e65d](https://github.com/FarmData2/FD2-SampleDBs/commit/824e65d0e6cd1f4d24d74f394655a0d95dd165fe))
* adds units to the sample database ([#14](https://github.com/FarmData2/FD2-SampleDBs/issues/14)) ([798cf8f](https://github.com/FarmData2/FD2-SampleDBs/commit/798cf8f6ac921779a717e344b55057f6abb25887))

## [1.3.0](https://github.com/FarmData2/FD2-SampleDBs/compare/v1.2.2...v1.3.0) (2023-11-17)


### Features

* adds CORS origins to farm client and added tray size vocabulary ([#13](https://github.com/FarmData2/FD2-SampleDBs/issues/13)) ([3e26c61](https://github.com/FarmData2/FD2-SampleDBs/commit/3e26c61500807584f9a6dffac7705bf7d3078a19)), closes [#11](https://github.com/FarmData2/FD2-SampleDBs/issues/11)

## [1.2.2](https://github.com/FarmData2/FD2-SampleDBs/compare/v1.2.1...v1.2.2) (2023-11-02)


### Fixes

* includes updated sample db in dist ([#12](https://github.com/FarmData2/FD2-SampleDBs/issues/12)) ([8a3e970](https://github.com/FarmData2/FD2-SampleDBs/commit/8a3e97040507058e70a87ac272955e6004852711)), closes [#10](https://github.com/FarmData2/FD2-SampleDBs/issues/10)

## [1.2.1](https://github.com/FarmData2/FD2-SampleDBs/compare/v1.2.0...v1.2.1) (2023-10-31)


### Fixes

* prepends parent crop name to subcrops. ([#10](https://github.com/FarmData2/FD2-SampleDBs/issues/10)) ([7f3d7d1](https://github.com/FarmData2/FD2-SampleDBs/commit/7f3d7d1b152ed24a7d7362148d5b84089e7a7c69))

## [1.2.0](https://github.com/FarmData2/FD2-SampleDBs/compare/v1.1.1...v1.2.0) (2023-10-30)


### Features

* add crops to the sample database ([febd843](https://github.com/FarmData2/FD2-SampleDBs/commit/febd8435e087b2223044ef9c41cf8d241221795b))

## [1.1.1](https://github.com/FarmData2/FD2-SampleDBs/compare/v1.1.0...v1.1.1) (2023-10-30)


### Chores

* small updates ([d7dc1ff](https://github.com/FarmData2/FD2-SampleDBs/commit/d7dc1ffae8ce0d9c6d58a6b1d642608794c05141))
* updates spell check dictionary ([9f4a02f](https://github.com/FarmData2/FD2-SampleDBs/commit/9f4a02f685c737d3d447c4cbbd5d7f6ff3acb4c4))


### Documentation

* update instructions for release ([01c7fcf](https://github.com/FarmData2/FD2-SampleDBs/commit/01c7fcf8951651e9c55f74ebdf945efe30e586b0))
* update steps for creating release ([e7472c9](https://github.com/FarmData2/FD2-SampleDBs/commit/e7472c9e896d6134a84768e093cea6100fdac6fb))
* updates readme with npm run commands ([f06b09f](https://github.com/FarmData2/FD2-SampleDBs/commit/f06b09f1450bcb7a03de8271fc7ad77b5c430763))


### Fixes

* adds arguments to error_check calls for custom messages ([9de9b97](https://github.com/FarmData2/FD2-SampleDBs/commit/9de9b9797673c25067721b37177b4723da076412))
* adds parameter to error_check function ([b17e266](https://github.com/FarmData2/FD2-SampleDBs/commit/b17e26615c879fa5fd34deb9eb1b80fcea94f8dd))

## [1.1.0](https://github.com/FarmData2/FD2-SampleDBs/compare/v1.0.0...v1.1.0) (2023-09-29)


### Chores

* make .releases script cjs ([#6](https://github.com/FarmData2/FD2-SampleDBs/issues/6)) ([bafb256](https://github.com/FarmData2/FD2-SampleDBs/commit/bafb2562b692dd17e383974244e6045785e0fd44))


### Features

* add scripts for creating a sample database ([#3](https://github.com/FarmData2/FD2-SampleDBs/issues/3)) ([6ac84eb](https://github.com/FarmData2/FD2-SampleDBs/commit/6ac84eb52039f8d7a7ae97283de51320c50a414b))
* add the planting areas to sampleDB ([#5](https://github.com/FarmData2/FD2-SampleDBs/issues/5)) ([8eeacf7](https://github.com/FarmData2/FD2-SampleDBs/commit/8eeacf78fcbbe8140babdb8256fc8c89b756d598))
* add utility functions for fields and beds, and greenhouses ([#7](https://github.com/FarmData2/FD2-SampleDBs/issues/7)) ([af0738d](https://github.com/FarmData2/FD2-SampleDBs/commit/af0738d44c8a79bed42e355aa7754777ed633c7a))

## 1.0.0 (2023-09-13)


### Chores

* initial setup ([#1](https://github.com/FarmData2/FD2-SampleDBs/issues/1)) ([7e9c049](https://github.com/FarmData2/FD2-SampleDBs/commit/7e9c049384490010a0f9a800073978465aef2bf4))


### Continuous Integration

* add action that builds releases ([8891bc6](https://github.com/FarmData2/FD2-SampleDBs/commit/8891bc6ab4509fb35609861dd4d4655ccc54245a))


### Documentation

* update and clarify README.md ([4c1770c](https://github.com/FarmData2/FD2-SampleDBs/commit/4c1770cf90cafe171b76171826f7a27dbdde10e7))
* update README for base database creation ([8b4a7e4](https://github.com/FarmData2/FD2-SampleDBs/commit/8b4a7e49706e7feb4dbcaff0be460fbab008f78c))


### Features

* add scripts to create base (empty) database ([#2](https://github.com/FarmData2/FD2-SampleDBs/issues/2)) ([184f0d4](https://github.com/FarmData2/FD2-SampleDBs/commit/184f0d4372edd50c24b4d44f51136c91f151be03))


### Fixes

* correct tar command to use gzip not bzip ([5914486](https://github.com/FarmData2/FD2-SampleDBs/commit/591448630ddd64f8f4589b14fb1ae572db90b0e9))
* include db file in the repo for distribution ([66f45ca](https://github.com/FarmData2/FD2-SampleDBs/commit/66f45ca1caefca653c1295541ad0b39056cf1913))
* remove build step in release action ([e62c056](https://github.com/FarmData2/FD2-SampleDBs/commit/e62c056abb1df33d8f2529a74b866c39bee43dc8))
