# Changelog

## [2.0.0-alpha.29](https://github.com/swastikCommits/openfoodfacts-nodejs/compare/v2.0.0-alpha.29...v2.0.0-alpha.29) (2026-02-21)


### ⚠ BREAKING CHANGES

* split v2 and v3, reorganize exports, use multiple returns ([#690](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/690))
* initial work for version 2.0.0

### Features

* Add endpoint for /insights robotoff ([#553](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/553)) ([475363b](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/475363b44f493a1829756e2dc87fa85ba958995a))
* add folksonomy and prices API ([00bfa2f](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/00bfa2f90d99f2828aa467188ae18168271a9a1f))
* add getAttributeGroups method ([9c0f72b](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/9c0f72b6647d3673ef0aa85a5523bd1e01ee3b51))
* Add getAttributeGroups method to v3 ([d81ebcf](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/d81ebcf9071e24c1ab8e4dabbe50f00d329b0fbc))
* add getLoginStatus method ([e14b8fe](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/e14b8fe57f1eb9c0abd85d1dc219d81c35b4a6fb))
* add getNutrients method and update type definitions for nutrient-related entities ([842689a](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/842689acad469f94cbe6e8de0c7249bb83b9ba8d))
* add getProductImageFolder method to return product image base URL ([#646](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/646)) ([7aa9da4](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/7aa9da4ae0bc1e513ccfd991b407f6cb1e151c0f))
* add getValues method to Folksonomy class ([68a4567](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/68a4567599f65d72d5b051d486e48c32b9e1f7e1))
* add nutripatrol API interfaces and support all flag endpoints ([d29ffac](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/d29ffac5bc00c780cdfcd62e3ea51ae2d1b73c52))
* add performOCR ([eeb37d4](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/eeb37d44aaadd17df7ac7fbc3e5d6ee4b765be54))
* add robotoff openapi generation to package.json ([3d0a113](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/3d0a113a630ba8795a5cd8b9b8e74f0f3f0b5318))
* add support for custom host in OpenFoodFacts constructor ([#611](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/611)) ([19efc0c](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/19efc0c5b6bdeaa4b44b06370931d441b59225ae))
* add support for the Search-A-Licious API ([#607](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/607)) ([a98db57](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/a98db57c573db7a95573506b5d92af8b95a97d11))
* add support for ticket in nutripatrol API ([d09ae9a](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/d09ae9ac44abac4e1a0c8a40c8e1540cfc20b2da))
* add USER_AGENT constant and include it in API request headers ([#559](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/559)) ([6052c45](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/6052c459f706e82f303cad31f052e307dcd98237))
* add v3 API support and deprecate getProduct in favor of ([fb439f4](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/fb439f43464fed00c3366445738e6163031435a0))
* Added API for fetching currencies list ([#653](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/653)) ([32e014c](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/32e014c14dda90a6f3f753fd4f9fa26342910ba1))
* added error handling for Folksonomy Write APIs ([#623](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/623)) ([1cd83d9](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/1cd83d94d3f6f2fda24fe409b0ef1cd965f9ab7a))
* api to get attribute-groups ([#669](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/669)) ([934030f](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/934030fb6031ec920958eeba57a5a37e67ecf616))
* **api:** add Facets Knowledge Panel API and Facets types ([db99d62](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/db99d620391361884008d1e3548326c64a0471c4))
* **api:** add KnowledgePanel types and elements structure ([04b9199](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/04b9199f649c73e8b8df6c911e8e6e95b4fbf447))
* **api:** add methods to fetch facet and facet values ([f35ed4d](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/f35ed4da422f064f742fa489dfaec26c9301aad4))
* auto build & deploy documentation ([a66d3a8](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/a66d3a8b9f2dd7bfac060dbf5ba1d5461e4b14aa))
* change `Content-Type` in `robotoff.ts` annotate method ([#599](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/599)) ([6be74ef](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/6be74eff7f8a084fc6de0a8c413a4606c04dcaed))
* export PriceFull type ([c401940](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/c40194065234d9cfad92d9c0bc5e760a028a9b53))
* export ProductDataType and recorder imports ([d15d14d](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/d15d14d42a1093a55b7ddf020a75db75f3ffa885))
* **images:** add selectAndCropImagesV3 method ([e23ef4f](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/e23ef4fca3814183031be14fe693ab1a3e3b1eec))
* implement facet api ([402cf24](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/402cf24fa3af848ea325411bf40f106fcfbcb366))
* implement image edit api ([#675](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/675)) ([f86e0c8](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/f86e0c88f1aa22dd32ce623c09db4ac04bb19f23))
* initial work for version 2.0.0 ([2b488a3](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/2b488a36dc7bfb7326dfbb59b83e0393fd31f84b))
* integration of OBF, OPF and OPFF ([#616](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/616)) ([897598f](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/897598ff9f137fbdcb78f290bd7141da94b3d49c))
* Make authToken optional for folksonomy client ([#571](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/571)) ([5679099](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/56790997304bbde5c5862b985eea015c6e6cc630))
* make base url configurable for all APIs ([#624](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/624)) ([aea2b8f](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/aea2b8f8a8ab2ae7888735e32d262f37b8971c99))
* moved products api to off.ts and added functions used in explorer ([#660](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/660)) ([1f654c6](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/1f654c60d1d0e4259979216cd88d04de75fde092))
* **nutripatrol:** Export type `FlagCreate` ([08da5ea](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/08da5eafd707dce8f9e63552fd69290e51c7e022))
* refactor error handling in nutripatrol wrapper ([eb94452](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/eb94452503d58f602f20fd947547476851fea36d))
* refresh schemas to latest version & adapt (test) code ([7a52aa4](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/7a52aa44a71459381b58e22eba78444d900e935d))
* **robotoff:** Implement logos & labels crops fetch and annotate routes [#528](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/528) ([#762](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/762)) ([810e057](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/810e0575c8018d1e934b2cc4c578049c462d07d4))
* streamline api typing generation ([ffafc0a](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/ffafc0a270910788359d3e9aad4b97bb8f5bd5fd))
* Typescript declaration files ([8ec0240](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/8ec02404d0d4d866631344c586a139f6623e0a7d))
* unify TS target for CJS and ESM to ES2017 ([1352669](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/13526695537530f834a2d5e57a192312b42bdf17))
* update API generation process and remove obsolete script ([0588baa](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/0588baa6b278b55390cada13a9c0f507a06aa8d4))
* update OpenPrices schema ([bbc90ec](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/bbc90ec7cddb648c0c7a66ac6f1f83e61774227d))


### Bug Fixes

* add build step to Node.js workflow, fix tests setup ([1cd9d71](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/1cd9d710d4755c96f7f5f3494ba3cf3ced89578b))
* add language option to OpenFoodFactsOptions and constructor defaults ([a8d9c15](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/a8d9c15a0114e16d5e3c8abf3d8c511b7e0b6f97))
* add missing types and main entry points in package.json ([de6cc4c](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/de6cc4cbc1a1de91234b9ce20b9eaee9e5ec22cd))
* add temporary type to loadLogo method to prevent TypeScript errors ([efb9fe5](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/efb9fe569980b2a325a9b42f07f6e74cee30023b))
* **auth:** enhance getLoginStatus to return error details on failure ([0a84b34](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/0a84b34b97c5268501a0dd22885d0d9d7b825565))
* auto-generate version.ts and update build process ([66ae03a](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/66ae03abfa12b1c984569f3774b4afb4e0a1e13a))
* body stream already read error, add types ([#622](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/622)) ([56e14ec](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/56e14eca2e2d92e3035b028ca616c88a13cbfefb))
* Change trigger condition for NPM publish workflow, add permissions ([814233a](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/814233a63690d5eaac4ac363378bde6c5829bfa5))
* checkout submodules during nodejs workflow ([21e342e](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/21e342e472f071616db797662eead7801216f3dc))
* export Search APIs in main.ts ([2663866](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/2663866002b1fca014db34c1f27062f7da52810a))
* export types in search.ts ([922c152](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/922c15233c9bf98af428f1e6acdb416488a084b0))
* Fix package workflow triggers and publishing ([2ecdcb7](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/2ecdcb748ecef9f3e6fe4da435fcd9f4ed953978))
* login and isAuthenticated methods in OpenPrices client ([#620](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/620)) ([e3903ab](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/e3903abb334d19e3a16535564e923fdbca44cef9))
* make 'code' and 'schema_version' required field, add imgid ([7ebfe26](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/7ebfe26e125b42c727127f82447dec5a260a5071))
* make docs job depend on build job ([b8dce91](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/b8dce914a664a93c115297efc66edf8b8eb7af0f))
* point export fields to the right paths ([056349c](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/056349c6ad403c06b3db9d7e80d93dcc04c752dc))
* Potential fix for code scanning alert no. 10: Workflow does not contain permissions ([fd6e1c2](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/fd6e1c240ba4aae197de1d7082a9c0aaa8ea0a19))
* Potential fix for code scanning alert no. 11: Workflow does not contain permissions ([416c7ef](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/416c7ef32305510334193a8a0b48f0fa77231d63))
* Potential fix for code scanning alert no. 20: Workflow does not contain permissions ([35c5e43](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/35c5e43b44023ea13f64f2996dc442dba8561eda))
* Potential fix for code scanning alert no. 9: Workflow does not contain permissions ([c9ba350](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/c9ba3509c106e95a4f6f0975f10bcfb0fd408735))
* refactor ProductState type inference in ProductOpenerApiV3 ([4379908](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/43799086a307272b9b26038d5caf8e920e405c01))
* remove $schemas path alias and update imports accordingly ([c7c7f9c](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/c7c7f9cad8e521dbb807ca361489af7f4c0c264d))
* remove externalv2 import from v2 schema ([5fce7e9](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/5fce7e9011812305aa13f5491e788218d466560e))
* Remove git+ prefix from repository URL ([9e47031](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/9e470319b1e3fe4cfccce8d2a0f6a6d35908c2f2))
* remove tests for now, as they are really difficult to implement with the new openapi codegen ([d5efade](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/d5efade6a74fe56307c8d278183cb3d3201bbab3))
* replace export with export type to make bundlers work ([4b57979](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/4b57979e80a361f939bf12c8e17beeda6a51baa7))
* replace window.fetch with globalThis.fetch ([92ef159](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/92ef159edba119cee9ee7e6db69ae50f21209665))
* Require product metadata fields in PO schemas ([837f031](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/837f031c0461bc893dac43d40a726ec78e62f52f))
* robotoff logo_id path parameter ([745d30e](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/745d30e8b8fee3423fb229345159236258328124))
* run doc generation only for latest node version ([e28547e](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/e28547ecec0f96370aa998e48d97d4e545f47a5e))
* **search:** improve typing for charts parameter in POST /search ([a21b9f1](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/a21b9f1843a079aed481f77cf74ead5c1d00316f))
* send nested objects as json serialized in robotoff.annotate ([a6a9194](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/a6a91945d0dc32e2b5fb2b18d1e20f33fdfd8393))
* Simplify condition for release-publish job execution ([f7ac365](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/f7ac36505cb15b8df728e74243767f3e0a5becc0))
* switch import paths to ES modules ([3bed3ac](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/3bed3ac1d21c41a60c623f7cff0e7405ff1e0304))
* **test:** do not specify return type if not needed ([d28c691](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/d28c691d27c134b6688072ba72df642eadab34b1))
* try to fix getProductV3 return type pt.2 ([946c825](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/946c825c3b050c862ce4abe0d64acb07fd189451))
* try to fix getProductV3 return type pt.3 ([5a8c1b1](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/5a8c1b19750c747fdf2b70f6f780eeed0f9121e6))
* **ts:** wrong [@ts-ignore](https://github.com/ts-ignore) usage ([53ebeef](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/53ebeefb4498ed2850e1592920ba227c71a9c089))
* Update GitHub workflow to publish via Yarn ([36bf328](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/36bf328a04723283578a6c989e3dc7ef0c7379ee))
* Update package URLs to openfoodfacts-js ([32892c5](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/32892c526f999f037200f70e2d981baf42cc5a49))
* Update release workflow to include outputs and streamline npm publish process ([6369bc6](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/6369bc68a45c460caf4eb80a92db5cc7f6401184))
* Update return type of getProductAttributes to ProductAttributeGroup[] ([6f1ba74](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/6f1ba744899898f6ffe725e3ccab5e2baa6b7413))
* use branch for server submodule. fixes type error ([19c730a](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/19c730ab353e4128caaa9fe48906eea3e163ebd3))
* Use VERSION constant for User-Agent string ([11341c9](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/11341c9406a628e24d261131b308f0b970f8cb70))


### Miscellaneous Chores

* bump version to 2.0.0-alpha.10 ([fef12ca](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/fef12cab2922e18d320de6cb4bb81ff518fa590b))
* bump version to 2.0.0-alpha.11 ([0fe67be](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/0fe67beab1527842e00a5537da088088fee9d973))
* bump version to 2.0.0-alpha.12 ([3d64d4e](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/3d64d4e65bb66727dafa5fd8fede73edc3292d9f))
* bump version to 2.0.0-alpha.8 ([c342334](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/c34233447f8eac0faab0685b05b6dfb3c0deb847))
* release 2.0.0-alpha.9 ([a7826c8](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/a7826c8ed3f84b77637313c4309c43c48732c309))
* trigger 2.0.0-alpha.14 release ([ac1f117](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/ac1f11765f9169ea5cde6c1824a572bacc08cece))
* trigger 2.0.0-alpha.16 release ([dacdfe9](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/dacdfe9aad9f8b1ba89cc6d30d6da2296b300e39))
* trigger 2.0.0-alpha.17 release ([bc04b46](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/bc04b465c76a055043957ac50153f43575f92b1d))
* trigger 2.0.0-alpha.18 release ([983d454](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/983d45457aab48bf431553b4da3499fea05bf611))
* trigger 2.0.0-alpha.19 release ([d659b53](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/d659b53285fc05dc06f7d2db5b456b7e3a447a25))
* trigger 2.0.0-alpha.20 release ([04950ad](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/04950ad6b60b7125740c8d6808330ae34acd308b))
* trigger 2.0.0-alpha.21 release ([94f9e63](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/94f9e63298e8e491c92356454c4652799f258585))
* trigger 2.0.0-alpha.22 release ([f931df2](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/f931df2cab420c4e7a8055697b7e8ce3214d8605))
* trigger 2.0.0-alpha.23 release ([fa44d36](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/fa44d361965309a31e6247e16e7513a3ac1d7da7))
* Trigger 2.0.0-alpha.28 release ([58ff532](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/58ff532a30b985c288c1c46ad56428762f45672a))
* Trigger 2.0.0-alpha.29 release ([4bb3db4](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/4bb3db42eefeb23c61d14c40864ca61168eb74ce))


### Code Refactoring

* split v2 and v3, reorganize exports, use multiple returns ([#690](https://github.com/swastikCommits/openfoodfacts-nodejs/issues/690)) ([9c3b1d4](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/9c3b1d4d5639256f1b2f1fc051349e06dc0b54b1))


### Continuous Integration

* Include prebuild in prepack script ([616007c](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/616007cc0cea4f46d3bad90f3379a6561e1963ad))
* Remove build step in package.yml ([32892c5](https://github.com/swastikCommits/openfoodfacts-nodejs/commit/32892c526f999f037200f70e2d981baf42cc5a49))

## [2.0.0-alpha.29](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.28...v2.0.0-alpha.29) (2026-02-09)


### Features

* **nutripatrol:** Export type `FlagCreate` ([08da5ea](https://github.com/openfoodfacts/openfoodfacts-js/commit/08da5eafd707dce8f9e63552fd69290e51c7e022))
* **robotoff:** Implement logos & labels crops fetch and annotate routes [#528](https://github.com/openfoodfacts/openfoodfacts-js/issues/528) ([#762](https://github.com/openfoodfacts/openfoodfacts-js/issues/762)) ([810e057](https://github.com/openfoodfacts/openfoodfacts-js/commit/810e0575c8018d1e934b2cc4c578049c462d07d4))


### Bug Fixes

* robotoff logo_id path parameter ([745d30e](https://github.com/openfoodfacts/openfoodfacts-js/commit/745d30e8b8fee3423fb229345159236258328124))


### Miscellaneous Chores

* Trigger 2.0.0-alpha.29 release ([4bb3db4](https://github.com/openfoodfacts/openfoodfacts-js/commit/4bb3db42eefeb23c61d14c40864ca61168eb74ce))

## [2.0.0-alpha.28](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.27...v2.0.0-alpha.28) (2026-02-04)


### Features

* update OpenPrices schema ([bbc90ec](https://github.com/openfoodfacts/openfoodfacts-js/commit/bbc90ec7cddb648c0c7a66ac6f1f83e61774227d))


### Miscellaneous Chores

* Trigger 2.0.0-alpha.28 release ([58ff532](https://github.com/openfoodfacts/openfoodfacts-js/commit/58ff532a30b985c288c1c46ad56428762f45672a))

## [2.0.0-alpha.27](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.26...v2.0.0-alpha.27) (2026-02-04)


### Bug Fixes

* Simplify condition for release-publish job execution ([f7ac365](https://github.com/openfoodfacts/openfoodfacts-js/commit/f7ac36505cb15b8df728e74243767f3e0a5becc0))

## [2.0.0-alpha.26](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.25...v2.0.0-alpha.26) (2026-02-04)


### Bug Fixes

* Update release workflow to include outputs and streamline npm publish process ([6369bc6](https://github.com/openfoodfacts/openfoodfacts-js/commit/6369bc68a45c460caf4eb80a92db5cc7f6401184))

## [2.0.0-alpha.25](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.24...v2.0.0-alpha.25) (2026-02-04)


### Continuous Integration

* Include prebuild in prepack script ([616007c](https://github.com/openfoodfacts/openfoodfacts-js/commit/616007cc0cea4f46d3bad90f3379a6561e1963ad))

## [2.0.0-alpha.24](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.23...v2.0.0-alpha.24) (2026-02-04)


### Bug Fixes

* Update package URLs to openfoodfacts-js ([32892c5](https://github.com/openfoodfacts/openfoodfacts-js/commit/32892c526f999f037200f70e2d981baf42cc5a49))


### Continuous Integration

* Remove build step in package.yml ([32892c5](https://github.com/openfoodfacts/openfoodfacts-js/commit/32892c526f999f037200f70e2d981baf42cc5a49))

## [2.0.0-alpha.23](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.22...v2.0.0-alpha.23) (2026-02-04)


### Bug Fixes

* Fix package workflow triggers and publishing ([2ecdcb7](https://github.com/openfoodfacts/openfoodfacts-js/commit/2ecdcb748ecef9f3e6fe4da435fcd9f4ed953978))
* Remove git+ prefix from repository URL ([9e47031](https://github.com/openfoodfacts/openfoodfacts-js/commit/9e470319b1e3fe4cfccce8d2a0f6a6d35908c2f2))


### Miscellaneous Chores

* trigger 2.0.0-alpha.23 release ([fa44d36](https://github.com/openfoodfacts/openfoodfacts-js/commit/fa44d361965309a31e6247e16e7513a3ac1d7da7))

## [2.0.0-alpha.22](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.21...v2.0.0-alpha.22) (2026-02-04)


### Bug Fixes

* Change trigger condition for NPM publish workflow, add permissions ([814233a](https://github.com/openfoodfacts/openfoodfacts-js/commit/814233a63690d5eaac4ac363378bde6c5829bfa5))


### Miscellaneous Chores

* trigger 2.0.0-alpha.22 release ([f931df2](https://github.com/openfoodfacts/openfoodfacts-js/commit/f931df2cab420c4e7a8055697b7e8ce3214d8605))

## [2.0.0-alpha.21](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.20...v2.0.0-alpha.21) (2026-02-04)


### Features

* **images:** add selectAndCropImagesV3 method ([e23ef4f](https://github.com/openfoodfacts/openfoodfacts-js/commit/e23ef4fca3814183031be14fe693ab1a3e3b1eec))


### Bug Fixes

* Require product metadata fields in PO schemas ([837f031](https://github.com/openfoodfacts/openfoodfacts-js/commit/837f031c0461bc893dac43d40a726ec78e62f52f))
* Update GitHub workflow to publish via Yarn ([36bf328](https://github.com/openfoodfacts/openfoodfacts-js/commit/36bf328a04723283578a6c989e3dc7ef0c7379ee))


### Miscellaneous Chores

* trigger 2.0.0-alpha.21 release ([94f9e63](https://github.com/openfoodfacts/openfoodfacts-js/commit/94f9e63298e8e491c92356454c4652799f258585))

## [2.0.0-alpha.20](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.19...v2.0.0-alpha.20) (2026-01-12)


### Bug Fixes

* **auth:** enhance getLoginStatus to return error details on failure ([0a84b34](https://github.com/openfoodfacts/openfoodfacts-js/commit/0a84b34b97c5268501a0dd22885d0d9d7b825565))
* Potential fix for code scanning alert no. 10: Workflow does not contain permissions ([fd6e1c2](https://github.com/openfoodfacts/openfoodfacts-js/commit/fd6e1c240ba4aae197de1d7082a9c0aaa8ea0a19))
* Potential fix for code scanning alert no. 11: Workflow does not contain permissions ([416c7ef](https://github.com/openfoodfacts/openfoodfacts-js/commit/416c7ef32305510334193a8a0b48f0fa77231d63))
* Potential fix for code scanning alert no. 20: Workflow does not contain permissions ([35c5e43](https://github.com/openfoodfacts/openfoodfacts-js/commit/35c5e43b44023ea13f64f2996dc442dba8561eda))
* Potential fix for code scanning alert no. 9: Workflow does not contain permissions ([c9ba350](https://github.com/openfoodfacts/openfoodfacts-js/commit/c9ba3509c106e95a4f6f0975f10bcfb0fd408735))
* **search:** improve typing for charts parameter in POST /search ([a21b9f1](https://github.com/openfoodfacts/openfoodfacts-js/commit/a21b9f1843a079aed481f77cf74ead5c1d00316f))


### Miscellaneous Chores

* trigger 2.0.0-alpha.20 release ([04950ad](https://github.com/openfoodfacts/openfoodfacts-js/commit/04950ad6b60b7125740c8d6808330ae34acd308b))

## [2.0.0-alpha.19](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.18...v2.0.0-alpha.19) (2025-09-20)


### Features

* add getLoginStatus method ([e14b8fe](https://github.com/openfoodfacts/openfoodfacts-js/commit/e14b8fe57f1eb9c0abd85d1dc219d81c35b4a6fb))


### Miscellaneous Chores

* trigger 2.0.0-alpha.19 release ([d659b53](https://github.com/openfoodfacts/openfoodfacts-js/commit/d659b53285fc05dc06f7d2db5b456b7e3a447a25))

## [2.0.0-alpha.18](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.17...v2.0.0-alpha.18) (2025-09-17)


### Features

* unify TS target for CJS and ESM to ES2017 ([1352669](https://github.com/openfoodfacts/openfoodfacts-js/commit/13526695537530f834a2d5e57a192312b42bdf17))


### Bug Fixes

* make 'code' and 'schema_version' required field, add imgid ([7ebfe26](https://github.com/openfoodfacts/openfoodfacts-js/commit/7ebfe26e125b42c727127f82447dec5a260a5071))
* replace window.fetch with globalThis.fetch ([92ef159](https://github.com/openfoodfacts/openfoodfacts-js/commit/92ef159edba119cee9ee7e6db69ae50f21209665))
* send nested objects as json serialized in robotoff.annotate ([a6a9194](https://github.com/openfoodfacts/openfoodfacts-js/commit/a6a91945d0dc32e2b5fb2b18d1e20f33fdfd8393))


### Miscellaneous Chores

* trigger 2.0.0-alpha.18 release ([983d454](https://github.com/openfoodfacts/openfoodfacts-js/commit/983d45457aab48bf431553b4da3499fea05bf611))

## [2.0.0-alpha.17](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.16...v2.0.0-alpha.17) (2025-09-07)


### Features

* export ProductDataType and recorder imports ([d15d14d](https://github.com/openfoodfacts/openfoodfacts-js/commit/d15d14d42a1093a55b7ddf020a75db75f3ffa885))
* update API generation process and remove obsolete script ([0588baa](https://github.com/openfoodfacts/openfoodfacts-js/commit/0588baa6b278b55390cada13a9c0f507a06aa8d4))


### Miscellaneous Chores

* trigger 2.0.0-alpha.17 release ([bc04b46](https://github.com/openfoodfacts/openfoodfacts-js/commit/bc04b465c76a055043957ac50153f43575f92b1d))

## [2.0.0-alpha.16](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.15...v2.0.0-alpha.16) (2025-09-01)


### Features

* add getNutrients method and update type definitions for nutrient-related entities ([842689a](https://github.com/openfoodfacts/openfoodfacts-js/commit/842689acad469f94cbe6e8de0c7249bb83b9ba8d))
* export PriceFull type ([c401940](https://github.com/openfoodfacts/openfoodfacts-js/commit/c40194065234d9cfad92d9c0bc5e760a028a9b53))


### Bug Fixes

* add missing types and main entry points in package.json ([de6cc4c](https://github.com/openfoodfacts/openfoodfacts-js/commit/de6cc4cbc1a1de91234b9ce20b9eaee9e5ec22cd))


### Miscellaneous Chores

* trigger 2.0.0-alpha.16 release ([dacdfe9](https://github.com/openfoodfacts/openfoodfacts-js/commit/dacdfe9aad9f8b1ba89cc6d30d6da2296b300e39))

## [2.0.0-alpha.15](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.14...v2.0.0-alpha.15) (2025-08-24)


### Features

* add getValues method to Folksonomy class ([68a4567](https://github.com/openfoodfacts/openfoodfacts-js/commit/68a4567599f65d72d5b051d486e48c32b9e1f7e1))


### Bug Fixes

* add build step to Node.js workflow, fix tests setup ([1cd9d71](https://github.com/openfoodfacts/openfoodfacts-js/commit/1cd9d710d4755c96f7f5f3494ba3cf3ced89578b))
* refactor ProductState type inference in ProductOpenerApiV3 ([4379908](https://github.com/openfoodfacts/openfoodfacts-js/commit/43799086a307272b9b26038d5caf8e920e405c01))
* try to fix getProductV3 return type pt.2 ([946c825](https://github.com/openfoodfacts/openfoodfacts-js/commit/946c825c3b050c862ce4abe0d64acb07fd189451))
* try to fix getProductV3 return type pt.3 ([5a8c1b1](https://github.com/openfoodfacts/openfoodfacts-js/commit/5a8c1b19750c747fdf2b70f6f780eeed0f9121e6))
* Use VERSION constant for User-Agent string ([11341c9](https://github.com/openfoodfacts/openfoodfacts-js/commit/11341c9406a628e24d261131b308f0b970f8cb70))

## [2.0.0-alpha.14](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.13...v2.0.0-alpha.14) (2025-08-24)


### Bug Fixes

* auto-generate version.ts and update build process ([66ae03a](https://github.com/openfoodfacts/openfoodfacts-js/commit/66ae03abfa12b1c984569f3774b4afb4e0a1e13a))
* point export fields to the right paths ([056349c](https://github.com/openfoodfacts/openfoodfacts-js/commit/056349c6ad403c06b3db9d7e80d93dcc04c752dc))
* replace export with export type to make bundlers work ([4b57979](https://github.com/openfoodfacts/openfoodfacts-js/commit/4b57979e80a361f939bf12c8e17beeda6a51baa7))
* switch import paths to ES modules ([3bed3ac](https://github.com/openfoodfacts/openfoodfacts-js/commit/3bed3ac1d21c41a60c623f7cff0e7405ff1e0304))


### Miscellaneous Chores

* trigger 2.0.0-alpha.14 release ([ac1f117](https://github.com/openfoodfacts/openfoodfacts-js/commit/ac1f11765f9169ea5cde6c1824a572bacc08cece))

## [2.0.0-alpha.13](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.12...v2.0.0-alpha.13) (2025-08-24)


### ⚠ BREAKING CHANGES

* split v2 and v3, reorganize exports, use multiple returns ([#690](https://github.com/openfoodfacts/openfoodfacts-js/issues/690))

### Code Refactoring

* split v2 and v3, reorganize exports, use multiple returns ([#690](https://github.com/openfoodfacts/openfoodfacts-js/issues/690)) ([9c3b1d4](https://github.com/openfoodfacts/openfoodfacts-js/commit/9c3b1d4d5639256f1b2f1fc051349e06dc0b54b1))

## [2.0.0-alpha.12](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.11...v2.0.0-alpha.12) (2025-08-20)


### Features

* **api:** add Facets Knowledge Panel API and Facets types ([db99d62](https://github.com/openfoodfacts/openfoodfacts-js/commit/db99d620391361884008d1e3548326c64a0471c4))
* **api:** add KnowledgePanel types and elements structure ([04b9199](https://github.com/openfoodfacts/openfoodfacts-js/commit/04b9199f649c73e8b8df6c911e8e6e95b4fbf447))
* **api:** add methods to fetch facet and facet values ([f35ed4d](https://github.com/openfoodfacts/openfoodfacts-js/commit/f35ed4da422f064f742fa489dfaec26c9301aad4))
* implement facet api ([402cf24](https://github.com/openfoodfacts/openfoodfacts-js/commit/402cf24fa3af848ea325411bf40f106fcfbcb366))


### Bug Fixes

* add language option to OpenFoodFactsOptions and constructor defaults ([a8d9c15](https://github.com/openfoodfacts/openfoodfacts-js/commit/a8d9c15a0114e16d5e3c8abf3d8c511b7e0b6f97))
* **test:** do not specify return type if not needed ([d28c691](https://github.com/openfoodfacts/openfoodfacts-js/commit/d28c691d27c134b6688072ba72df642eadab34b1))


### Miscellaneous Chores

* bump version to 2.0.0-alpha.12 ([3d64d4e](https://github.com/openfoodfacts/openfoodfacts-js/commit/3d64d4e65bb66727dafa5fd8fede73edc3292d9f))

## [2.0.0-alpha.11](https://github.com/openfoodfacts/openfoodfacts-js/compare/v2.0.0-alpha.10...v2.0.0-alpha.11) (2025-08-12)


### Features

* implement image edit api ([#675](https://github.com/openfoodfacts/openfoodfacts-js/issues/675)) ([f86e0c8](https://github.com/openfoodfacts/openfoodfacts-js/commit/f86e0c88f1aa22dd32ce623c09db4ac04bb19f23))


### Miscellaneous Chores

* bump version to 2.0.0-alpha.11 ([0fe67be](https://github.com/openfoodfacts/openfoodfacts-js/commit/0fe67beab1527842e00a5537da088088fee9d973))

## [2.0.0-alpha.10](https://github.com/openfoodfacts/openfoodfacts-nodejs/compare/v2.0.0-alpha.9...v2.0.0-alpha.10) (2025-08-02)


### Features

* add getAttributeGroups method ([9c0f72b](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/9c0f72b6647d3673ef0aa85a5523bd1e01ee3b51))
* api to get attribute-groups ([#669](https://github.com/openfoodfacts/openfoodfacts-nodejs/issues/669)) ([934030f](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/934030fb6031ec920958eeba57a5a37e67ecf616))
* moved products api to off.ts and added functions used in explorer ([#660](https://github.com/openfoodfacts/openfoodfacts-nodejs/issues/660)) ([1f654c6](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/1f654c60d1d0e4259979216cd88d04de75fde092))
* streamline api typing generation ([ffafc0a](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/ffafc0a270910788359d3e9aad4b97bb8f5bd5fd))


### Miscellaneous Chores

* bump version to 2.0.0-alpha.10 ([fef12ca](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/fef12cab2922e18d320de6cb4bb81ff518fa590b))

## [2.0.0-alpha.9](https://github.com/openfoodfacts/openfoodfacts-nodejs/compare/v2.0.0-alpha.8...v2.0.0-alpha.9) (2025-07-18)


### Features

* add v3 API support and deprecate getProduct in favor of ([fb439f4](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/fb439f43464fed00c3366445738e6163031435a0))
* Added API for fetching currencies list ([#653](https://github.com/openfoodfacts/openfoodfacts-nodejs/issues/653)) ([32e014c](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/32e014c14dda90a6f3f753fd4f9fa26342910ba1))


### Miscellaneous Chores

* release 2.0.0-alpha.9 ([a7826c8](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/a7826c8ed3f84b77637313c4309c43c48732c309))

## [2.0.0-alpha.8](https://github.com/openfoodfacts/openfoodfacts-nodejs/compare/v2.0.0-alpha.7...v2.0.0-alpha.8) (2025-07-12)


### Features

* add getProductImageFolder method to return product image base URL ([#646](https://github.com/openfoodfacts/openfoodfacts-nodejs/issues/646)) ([7aa9da4](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/7aa9da4ae0bc1e513ccfd991b407f6cb1e151c0f))
* refresh schemas to latest version & adapt (test) code ([7a52aa4](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/7a52aa44a71459381b58e22eba78444d900e935d))


### Bug Fixes

* remove $schemas path alias and update imports accordingly ([c7c7f9c](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/c7c7f9cad8e521dbb807ca361489af7f4c0c264d))
* remove externalv2 import from v2 schema ([5fce7e9](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/5fce7e9011812305aa13f5491e788218d466560e))


### Miscellaneous Chores

* bump version to 2.0.0-alpha.8 ([c342334](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/c34233447f8eac0faab0685b05b6dfb3c0deb847))

## 1.0.0 (2022-04-27)

### Features

- **additives:** add getAdditives function ([f8abf40](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/f8abf40e0f083a81624fcd4f875bb77c157071fe))
- **country:** OFF is now set to be immutable ([604edc3](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/604edc34a26ced68032687e21f8f0d05be6d6ade))
- **facets:** add functions for the rest of the OFF facets ([64c17f4](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/64c17f43e942bbc3eaa70c5aac15003ac67354e3))
- **feature added:** more functions added in the package ([fd44462](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/fd44462d6d58d8e497eb3b031a63f5be6355b39d))

### Bug Fixes

- **additives:** remove useless line ([7944550](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/7944550e45ab50603c5e6db9e08ec88642f0fb6f))
- dependabot.yml syntax ([56c015d](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/56c015d61b6067f082072bbe9f021414b26d1b37))
- skip CodeQL for Dependabot on push events ([56fae76](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/56fae76222ef1d0f11b6013f147819910aae367d))
- tests for ci (npm ci) ([cf08b37](https://github.com/openfoodfacts/openfoodfacts-nodejs/commit/cf08b37beea9d7823c02e8b468b9c0308b17ebf9))
