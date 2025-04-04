# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [7.0.0](https://github.com/nanorepublica/gatsby-source-prismic/compare/v3.1.4...v7.0.0) (2025-04-04)


### Bug Fixes

* add verbose log when downloading files ([e3d4adf](https://github.com/nanorepublica/gatsby-source-prismic/commit/e3d4adf3b0ac0db1571cc03208ae2af87c87c4fd))
* add video_id to oembed for issue [#286](https://github.com/nanorepublica/gatsby-source-prismic/issues/286) ([#324](https://github.com/nanorepublica/gatsby-source-prismic/issues/324)) ([4c19d9d](https://github.com/nanorepublica/gatsby-source-prismic/commit/4c19d9d8e17bda9ce7ca2e3fa7900de399acffcf))
* allow complete opt-in file downloading ([#470](https://github.com/nanorepublica/gatsby-source-prismic/issues/470)) ([c1b27b3](https://github.com/nanorepublica/gatsby-source-prismic/commit/c1b27b3003372dc258d5d9911e748a448b0e408d))
* apply same fix to typepath generation ([8ad9af3](https://github.com/nanorepublica/gatsby-source-prismic/commit/8ad9af3a06aad32423453305417b37cf00815c9e))
* correctly resolve fields with transformed names ([#415](https://github.com/nanorepublica/gatsby-source-prismic/issues/415)) ([1c7907f](https://github.com/nanorepublica/gatsby-source-prismic/commit/1c7907f420e22b99d3c6009d85c443e2a00fa414))
* correctly resolve root document fields when using transformFieldName ([9175c7d](https://github.com/nanorepublica/gatsby-source-prismic/commit/9175c7d6681b2385abd5a7a5e2701183dd7e5515)), closes [#447](https://github.com/nanorepublica/gatsby-source-prismic/issues/447)
* ensure cached localFile fields are not null ([#472](https://github.com/nanorepublica/gatsby-source-prismic/issues/472)) ([b2d9d01](https://github.com/nanorepublica/gatsby-source-prismic/commit/b2d9d018fa61fddc8c901c98b3040f0b1ac6214e))
* ensure legacy preview toolbar has correct repo endpoint URL ([c64aab3](https://github.com/nanorepublica/gatsby-source-prismic/commit/c64aab3c72026a9308f557796c4ea9e87782ec1b))
* ensure legacy prismicId nested preview data merging still works ([575414e](https://github.com/nanorepublica/gatsby-source-prismic/commit/575414ea6502fd97f30c4ce4221863a97ae873f7))
* error when link fields are null ([b742a57](https://github.com/nanorepublica/gatsby-source-prismic/commit/b742a57dfb68ab9e635d88059785caf2c7872fe2)), closes [#312](https://github.com/nanorepublica/gatsby-source-prismic/issues/312)
* image field proxy types ([91e07eb](https://github.com/nanorepublica/gatsby-source-prismic/commit/91e07eb91275db18312193c1b39cfbbbf1f3fb7a))
* lock `@prismicio/client` version ([43e7795](https://github.com/nanorepublica/gatsby-source-prismic/commit/43e77957ed579ae1519699278c56522da5b8c75a))
* omit `target` attribute on links without a target ([#520](https://github.com/nanorepublica/gatsby-source-prismic/issues/520)) ([abfb55e](https://github.com/nanorepublica/gatsby-source-prismic/commit/abfb55e37bdd431cebe78caaebe0f939dd8d7fd7))
* Preview docs, unpublished code example ([494eee7](https://github.com/nanorepublica/gatsby-source-prismic/commit/494eee7812bf237ad89214e2852788a698895af0))
* **previews:** catch error when a field type cannot be found ([352c923](https://github.com/nanorepublica/gatsby-source-prismic/commit/352c9238c51166863134aed823ae609807be6b01))
* **previews:** correctly resolve the `url` property in link fields ([#542](https://github.com/nanorepublica/gatsby-source-prismic/issues/542)) ([0a426c5](https://github.com/nanorepublica/gatsby-source-prismic/commit/0a426c5f64b74af36f8b1c656355d44502c2ecfd))
* **previews:** resolve CORS error with `@prismicio/client` ([1d66749](https://github.com/nanorepublica/gatsby-source-prismic/commit/1d6674912d5780de37d8cad78c56b59b0d83b92a))
* **previews:** restore `dataRaw` document field ([3ab85ea](https://github.com/nanorepublica/gatsby-source-prismic/commit/3ab85ea0132f71df4ba54e9a1df4f1ee5c876353))
* **previews:** retain correct scroll position during preview bootstrapping ([#504](https://github.com/nanorepublica/gatsby-source-prismic/issues/504)) ([46803df](https://github.com/nanorepublica/gatsby-source-prismic/commit/46803df0147f6c909369b82c976e14aac2053543))
* **previews:** support React 18 ([#508](https://github.com/nanorepublica/gatsby-source-prismic/issues/508)) ([6f55e01](https://github.com/nanorepublica/gatsby-source-prismic/commit/6f55e01efb55825699a99f6c47a6c1e780ad73e7))
* **previews:** treat null link fields as valid ([#433](https://github.com/nanorepublica/gatsby-source-prismic/issues/433)) ([4e6cc1d](https://github.com/nanorepublica/gatsby-source-prismic/commit/4e6cc1db493baa13d7b74b7f95c52c30f55a149d))
* **previews:** wait for bootstrap to complete before merging data ([4b9bfe4](https://github.com/nanorepublica/gatsby-source-prismic/commit/4b9bfe4594810bf3b4de919ed0b3c967c20b4382))
* remove default q=50 Imgix parameter for Gatsby images ([1067bd0](https://github.com/nanorepublica/gatsby-source-prismic/commit/1067bd0c63ffbd7ebd6ee3dca76c0631c1fc1a66))
* remove mention of _previewable docs (not yet written) ([0dc6014](https://github.com/nanorepublica/gatsby-source-prismic/commit/0dc6014edd53b6c131096944ffee0066289fbbad))
* remove vimeo from `video_id` field description ([d00c2e0](https://github.com/nanorepublica/gatsby-source-prismic/commit/d00c2e0505cbc4b1a78127dd33d8a91455b7071e))
* replace `@prismicio/client`'s `getAll` with `dangerouslyGetAll` ([50c0ef2](https://github.com/nanorepublica/gatsby-source-prismic/commit/50c0ef2e1628394c29755380f26926428436dd2a))
* resolve npm 7 install failure with Gatsby v3 ([#347](https://github.com/nanorepublica/gatsby-source-prismic/issues/347)) ([c28ecfd](https://github.com/nanorepublica/gatsby-source-prismic/commit/c28ecfd3ef7a959abfc665b91c5d5bdbe5fd17cd))
* restore document link ([#298](https://github.com/nanorepublica/gatsby-source-prismic/issues/298)) ([4d94c3b](https://github.com/nanorepublica/gatsby-source-prismic/commit/4d94c3b02a9cbe5365ad9ee4292231d6578bc574))
* **source:** correctly support Cloud Builds on Gatsby Cloud ([#450](https://github.com/nanorepublica/gatsby-source-prismic/issues/450)) ([555a37d](https://github.com/nanorepublica/gatsby-source-prismic/commit/555a37d592fee72ccf9cdc5958c5d81b45f48306))
* **source:** exclude empty Slice Zones in GraphQL type ([23cb131](https://github.com/nanorepublica/gatsby-source-prismic/commit/23cb1316dd081249ec1788c6963eeba0a3e2c077))
* **source:** resolve "Unable to serialize object as a key" error on empty Embed fields ([5afb496](https://github.com/nanorepublica/gatsby-source-prismic/commit/5afb496b4376b069be5f863a87de5bb2265e5425)), closes [#484](https://github.com/nanorepublica/gatsby-source-prismic/issues/484)
* **source:** restore fetching documents of all languages by defualt ([def010a](https://github.com/nanorepublica/gatsby-source-prismic/commit/def010a2ce0db5180cd3140b5368cc94c35ca4b6))
* **source:** support Slice Zones with missing `choices` property ([#511](https://github.com/nanorepublica/gatsby-source-prismic/issues/511)) ([bab9ca8](https://github.com/nanorepublica/gatsby-source-prismic/commit/bab9ca8678631645b682498781d494a6ef86eb46))
* **source:** support Slices without non-repeat/repeat models ([5821cf0](https://github.com/nanorepublica/gatsby-source-prismic/commit/5821cf0970002a63df096090aed1f3a4fdfc92fb))
* **sourec:** only normalize data field if it contains fields ([1eb81a2](https://github.com/nanorepublica/gatsby-source-prismic/commit/1eb81a223d1c3f45884bfc22c04645e2047df293))
* support repositories without image fields ([#250](https://github.com/nanorepublica/gatsby-source-prismic/issues/250)) ([1f68757](https://github.com/nanorepublica/gatsby-source-prismic/commit/1f68757d7759861cdf6bdcbfdd4259eb42471a7b)), closes [#238](https://github.com/nanorepublica/gatsby-source-prismic/issues/238)
* support Shared Slices without primary/items models ([db83f3d](https://github.com/nanorepublica/gatsby-source-prismic/commit/db83f3ddc0e70a4d00044149a1fd1cf78615412e))
* support Slice Zones with missing `choices` property ([eb0386f](https://github.com/nanorepublica/gatsby-source-prismic/commit/eb0386fbb4b8e3e682b09957f4cef8942e96e0e8))
* update @prismicio/imgix (fixes [#488](https://github.com/nanorepublica/gatsby-source-prismic/issues/488)) ([7eb0269](https://github.com/nanorepublica/gatsby-source-prismic/commit/7eb02693d750f01c06a34bf4c5c781a872ee7a01))
* update `@imgix/gatsby` to support Gatsby v5.10.0 ([#532](https://github.com/nanorepublica/gatsby-source-prismic/issues/532)) ([c729e0a](https://github.com/nanorepublica/gatsby-source-prismic/commit/c729e0aa64823db3a2c3f64b6cee1a56f42078b8))
* update all dependencies ([4e16769](https://github.com/nanorepublica/gatsby-source-prismic/commit/4e16769220e3e38a0ea8393b5fdb22e84d5190d3))
* update dependencies ([57ceb56](https://github.com/nanorepublica/gatsby-source-prismic/commit/57ceb5625bbfb989745845c50d770bca659ae4c1))
* update missing _previewable warning message ([fbcd4b9](https://github.com/nanorepublica/gatsby-source-prismic/commit/fbcd4b98ee5d42a4eef4d608d8799debe7859e93))
* use consistent node IDs to better support Gatsby Preview ([4bfef99](https://github.com/nanorepublica/gatsby-source-prismic/commit/4bfef99aa186f27ff1877f32ffae7f9ab812e34e)), closes [issue#297](https://github.com/issue/issues/297)


### Features

* add _previewable field for preview API ([7adb446](https://github.com/nanorepublica/gatsby-source-prismic/commit/7adb4462845e70467d10b7fdd5b53eb5783e4094))
* add `pageSize` option ([#456](https://github.com/nanorepublica/gatsby-source-prismic/issues/456)) ([72d6a68](https://github.com/nanorepublica/gatsby-source-prismic/commit/72d6a6860262293d3ade374387ac9ffa07b629da))
* add `routes` option to support Route Resolver ([#479](https://github.com/nanorepublica/gatsby-source-prismic/issues/479)) ([731f1a1](https://github.com/nanorepublica/gatsby-source-prismic/commit/731f1a119dabf1d19c9a1bd661fd158854e22fc1))
* ensure unpublished previews contain preview data ([1cc54c4](https://github.com/nanorepublica/gatsby-source-prismic/commit/1cc54c4d04e55be3c3534eb718e8da049954dcb5))
* support for custom fetch function ([#432](https://github.com/nanorepublica/gatsby-source-prismic/issues/432)) ([8f4a96f](https://github.com/nanorepublica/gatsby-source-prismic/commit/8f4a96ffd0653f4b6fe9271af52d2fdd35cd7876))
* support for Gatsby Cloud ([#255](https://github.com/nanorepublica/gatsby-source-prismic/issues/255)) ([2badd85](https://github.com/nanorepublica/gatsby-source-prismic/commit/2badd85936511c21d61761da2d9b1daece40af94))
* support Gatsby 4 ([#466](https://github.com/nanorepublica/gatsby-source-prismic/issues/466)) ([d391580](https://github.com/nanorepublica/gatsby-source-prismic/commit/d391580a1ef5828b8bde018126eefdd859b54ae8))
* support Gatsby 5 ([#529](https://github.com/nanorepublica/gatsby-source-prismic/issues/529)) ([1971ce2](https://github.com/nanorepublica/gatsby-source-prismic/commit/1971ce24ee8f663df2e30ab71ff49508100bdeff))
* type Rich Text and Title fields with custom PrismicStructuredText scalar ([#473](https://github.com/nanorepublica/gatsby-source-prismic/issues/473)) ([5737479](https://github.com/nanorepublica/gatsby-source-prismic/commit/5737479f8c113341214da7b432bf70e590e294f7))
* v4.0.0 ([#408](https://github.com/nanorepublica/gatsby-source-prismic/issues/408)) ([407887f](https://github.com/nanorepublica/gatsby-source-prismic/commit/407887f2a039346420d4238beb8866dd33d230f8)), closes [#334](https://github.com/nanorepublica/gatsby-source-prismic/issues/334) [#335](https://github.com/nanorepublica/gatsby-source-prismic/issues/335) [#349](https://github.com/nanorepublica/gatsby-source-prismic/issues/349) [#350](https://github.com/nanorepublica/gatsby-source-prismic/issues/350) [#352](https://github.com/nanorepublica/gatsby-source-prismic/issues/352) [#353](https://github.com/nanorepublica/gatsby-source-prismic/issues/353) [#359](https://github.com/nanorepublica/gatsby-source-prismic/issues/359) [#360](https://github.com/nanorepublica/gatsby-source-prismic/issues/360) [#351](https://github.com/nanorepublica/gatsby-source-prismic/issues/351) [#364](https://github.com/nanorepublica/gatsby-source-prismic/issues/364) [#371](https://github.com/nanorepublica/gatsby-source-prismic/issues/371) [#375](https://github.com/nanorepublica/gatsby-source-prismic/issues/375) [#383](https://github.com/nanorepublica/gatsby-source-prismic/issues/383) [#405](https://github.com/nanorepublica/gatsby-source-prismic/issues/405) [#406](https://github.com/nanorepublica/gatsby-source-prismic/issues/406)


### BREAKING CHANGES

* Changes to Gatsby's query runner requires the plugin to
download local files at bootstrap. Add a `shouldDownloadFiles` plugin
option if you use the `localFile` field for Image and Link fields.

* v5.0.0-alpha.0

* chore: link test-site to local packages

* chore: add publish:next script

* fix: provide better missing schema message

* style: run prettier

* chore: update dependencies

* v5.0.0-next.0

* chore: update gatsby-plugin-image

* v5.0.0-next.1

* chore: fix duplicated changelog

* fix: include gatsby-node.js on npm

* v5.0.0-next.2

* fix(previews): remove missing styles message

* v5.0.0-next.3

* chore: update gatsby, gatsby-plugin-image peer dep

* v5.0.0-next.4

* fix(previews): optional repositoryConfigs option for withPrismicPreviewResolver

* v5.0.0-next.5

* fix: move default function plugin options to Node APIs

* v5.0.0-next.6

* fix: use non-.mjs exports

This is primarily to support Storybook without special configuration.

* v5.0.0-next.7

* feat(source): move plugin option defaults to Gatsby Node APIs

* v5.0.0-next.8

* chore: update yarn.lock

* refactor: plugin options validation

* feat: improved plugin options validation messages

* chore: merge CHANGELOG

* feat: support pageSize plugin option

* chore: update dependencies

* fix: use updated @prismicio/helpers `asLink`

* v5.0.0-next.9

* fix(source): skip data field normalization for documents without data fields

* fix(previews): upgrade gatsby-source-prismic dependency

* v5.0.0-next.10

* fix(source): skip schema validation if Custom Types API is used

* v5.0.0-next.11

* fix: update peerDependencies for Gatsby 4

* chore: update test site dependencies

* chore: do not format CHANGELOG with prettier

* test: temporarily skip snapshot tests in CI

* test: explicitly pass CI-skipped tests





## [6.0.2](https://github.com/prismicio/prismic-gatsby/compare/v6.0.1...v6.0.2) (2024-08-12)

**Note:** Version bump only for package @prismicio/gatsby





## [6.0.1](https://github.com/prismicio/prismic-gatsby/compare/v6.0.0...v6.0.1) (2023-09-05)


### Bug Fixes

* **previews:** correctly resolve the `url` property in link fields ([#542](https://github.com/prismicio/prismic-gatsby/issues/542)) ([0a426c5](https://github.com/prismicio/prismic-gatsby/commit/0a426c5f64b74af36f8b1c656355d44502c2ecfd))





# [6.0.0](https://github.com/prismicio/prismic-gatsby/compare/v5.3.1...v6.0.0) (2023-06-29)

**Note:** Version bump only for package @prismicio/gatsby





# [6.0.0-alpha.19](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v6.0.0-alpha.18...v6.0.0-alpha.19) (2022-11-17)

**Note:** Version bump only for package @prismicio/gatsby





# [6.0.0-alpha.18](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v6.0.0-alpha.17...v6.0.0-alpha.18) (2022-11-17)

### Bug Fixes

- handle nonexistent fields ([#49](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/49)) ([28e9ee5](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/28e9ee551fa1a50b364d17dc19a7123c13b6971d))

# [6.0.0-alpha.17](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v6.0.0-alpha.16...v6.0.0-alpha.17) (2022-11-04)

### Bug Fixes

- allow `uid` and `lang` Route Resolver options ([#48](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/48)) ([fbe8586](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/fbe858663b17098c2305793b962ce45255c0cc18))

# [6.0.0-alpha.16](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v6.0.0-alpha.0...v6.0.0-alpha.16) (2022-11-02)

### Bug Fixes

- always treat Select fields as nullable ([8e98ec4](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/8e98ec4df57a8cfb98a9365ecea0ba5c66a78128))
- builds and tests ([d664e4a](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/d664e4acd50adc61a7671181d3daddbb623686df))
- change UID field type from `ID!` to `String!` ([#12](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/12)) ([8a27248](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/8a27248e4f82ab6d90b7980617e315ef3b3f0cb9))
- import fetch ([ce33026](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/ce33026d379cee7145d5a482bebda185f74e4ef6))
- **previews:** replace nanostores with Zustand ([#44](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/44)) ([5e5aa05](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/5e5aa0567388dcdadb7b07c5862ff439922ddb8f))
- remove `node:` prefix from Node.js imports ([6851757](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/6851757f4669bf6b385b84d99302b2d358d9461b))
- resolve correct image thumbnail URLs ([#41](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/41)) ([ef02eb0](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/ef02eb06294d2b5bd4a6ff20c54737600876edcc))
- resolve error when using `gatsbyImageData` with SVGs ([#13](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/13)) ([a1ae60d](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/a1ae60dec307f7017982adec228e2e4b539623cf))
- support `gatsbyImageData` fixed layout with given dimensions ([#17](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/17)) ([450864d](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/450864d085d14cf00f8f1985bebe43caf51175b0))
- support all `gatsbyImageData` parameters ([#19](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/19)) ([172389a](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/172389a752123738eb06cc33d8a8dd63467ce790))
- support empty Slice Zones ([#42](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/42)) ([30c1318](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/30c131860d7d72ddca467b11aa84f49f038c6e1e))
- support image thumbnails with dashes in their name ([#16](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/16)) ([6ba042f](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/6ba042fe33ec0678c04f69f70d5f20c1970fc7d3))
- support Integration Field catalogs with no usage ([#14](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/14)) ([2aaf89d](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/2aaf89d2816c244c1e44b261a94e5c420a0c8cbc))
- use `link_type` rather than `linkType` in `LinkField` ([1fa1b32](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/1fa1b3284114f854b8e60fa1b29dcb6d5e1a8a56))
- use `PrismicEmbedField` over `PrismicEmbed` everywhere ([fd32368](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/fd323682918343dc67242bd547d2692c724f019b))
- use correct required type name for AlternateLanguage ([7d1a658](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/7d1a65851571e95efde26cd75b7e5eaf8b3dbc70))

### Features

- 🍬 ([b7b5fdc](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/b7b5fdc441672f08f4f3ec2d8654fd2610374132))
- add `shouldDownloadFile` path to Link and Link to Media field descriptions ([#21](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/21)) ([2629eb0](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/2629eb02e3b6ac6293b6c34bc2ea13f7a0b2a501))
- add debug `usePrismicPreviewState()` hook ([#43](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/43)) ([a3321a4](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/a3321a45e074ebf0b49dc95c6fe48b65734305d0))
- add temporary timers to measure `sourecNodes` and preview times ([#25](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/25)) ([d932796](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/d9327969bfd51ea975b9e611d4329cf2a39386dc))
- **previews:** validate plugin options ([#10](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/10)) ([20e1beb](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/20e1bebf34093e1add544ab090f1ed13475f5658))
- restore Gatsby Cloud incremental builds support ([4a4a087](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/4a4a087b3b94b80a46b013dfc6d9a24f64611d7c))
