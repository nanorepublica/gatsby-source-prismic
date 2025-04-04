# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [7.0.0](https://github.com/prismicio/prismic-gatsby/compare/v3.1.4...v7.0.0) (2025-04-04)


### Bug Fixes

* add verbose log when downloading files ([e3d4adf](https://github.com/prismicio/prismic-gatsby/commit/e3d4adf3b0ac0db1571cc03208ae2af87c87c4fd))
* allow complete opt-in file downloading ([#470](https://github.com/prismicio/prismic-gatsby/issues/470)) ([c1b27b3](https://github.com/prismicio/prismic-gatsby/commit/c1b27b3003372dc258d5d9911e748a448b0e408d))
* apply same fix to typepath generation ([8ad9af3](https://github.com/prismicio/prismic-gatsby/commit/8ad9af3a06aad32423453305417b37cf00815c9e))
* correctly resolve fields with transformed names ([#415](https://github.com/prismicio/prismic-gatsby/issues/415)) ([1c7907f](https://github.com/prismicio/prismic-gatsby/commit/1c7907f420e22b99d3c6009d85c443e2a00fa414))
* correctly resolve root document fields when using transformFieldName ([9175c7d](https://github.com/prismicio/prismic-gatsby/commit/9175c7d6681b2385abd5a7a5e2701183dd7e5515)), closes [#447](https://github.com/prismicio/prismic-gatsby/issues/447)
* ensure cached localFile fields are not null ([#472](https://github.com/prismicio/prismic-gatsby/issues/472)) ([b2d9d01](https://github.com/prismicio/prismic-gatsby/commit/b2d9d018fa61fddc8c901c98b3040f0b1ac6214e))
* lock `@prismicio/client` version ([43e7795](https://github.com/prismicio/prismic-gatsby/commit/43e77957ed579ae1519699278c56522da5b8c75a))
* omit `target` attribute on links without a target ([#520](https://github.com/prismicio/prismic-gatsby/issues/520)) ([abfb55e](https://github.com/prismicio/prismic-gatsby/commit/abfb55e37bdd431cebe78caaebe0f939dd8d7fd7))
* **previews:** resolve CORS error with `@prismicio/client` ([1d66749](https://github.com/prismicio/prismic-gatsby/commit/1d6674912d5780de37d8cad78c56b59b0d83b92a))
* **previews:** restore `dataRaw` document field ([3ab85ea](https://github.com/prismicio/prismic-gatsby/commit/3ab85ea0132f71df4ba54e9a1df4f1ee5c876353))
* remove default q=50 Imgix parameter for Gatsby images ([1067bd0](https://github.com/prismicio/prismic-gatsby/commit/1067bd0c63ffbd7ebd6ee3dca76c0631c1fc1a66))
* replace `@prismicio/client`'s `getAll` with `dangerouslyGetAll` ([50c0ef2](https://github.com/prismicio/prismic-gatsby/commit/50c0ef2e1628394c29755380f26926428436dd2a))
* **source:** correctly support Cloud Builds on Gatsby Cloud ([#450](https://github.com/prismicio/prismic-gatsby/issues/450)) ([555a37d](https://github.com/prismicio/prismic-gatsby/commit/555a37d592fee72ccf9cdc5958c5d81b45f48306))
* **source:** exclude empty Slice Zones in GraphQL type ([23cb131](https://github.com/prismicio/prismic-gatsby/commit/23cb1316dd081249ec1788c6963eeba0a3e2c077))
* **source:** resolve "Unable to serialize object as a key" error on empty Embed fields ([5afb496](https://github.com/prismicio/prismic-gatsby/commit/5afb496b4376b069be5f863a87de5bb2265e5425)), closes [#484](https://github.com/prismicio/prismic-gatsby/issues/484)
* **source:** restore fetching documents of all languages by defualt ([def010a](https://github.com/prismicio/prismic-gatsby/commit/def010a2ce0db5180cd3140b5368cc94c35ca4b6))
* **source:** support Slices without non-repeat/repeat models ([5821cf0](https://github.com/prismicio/prismic-gatsby/commit/5821cf0970002a63df096090aed1f3a4fdfc92fb))
* **sourec:** only normalize data field if it contains fields ([1eb81a2](https://github.com/prismicio/prismic-gatsby/commit/1eb81a223d1c3f45884bfc22c04645e2047df293))
* support Shared Slices without primary/items models ([db83f3d](https://github.com/prismicio/prismic-gatsby/commit/db83f3ddc0e70a4d00044149a1fd1cf78615412e))
* support Slice Zones with missing `choices` property ([eb0386f](https://github.com/prismicio/prismic-gatsby/commit/eb0386fbb4b8e3e682b09957f4cef8942e96e0e8))
* update @prismicio/imgix (fixes [#488](https://github.com/prismicio/prismic-gatsby/issues/488)) ([7eb0269](https://github.com/prismicio/prismic-gatsby/commit/7eb02693d750f01c06a34bf4c5c781a872ee7a01))
* update `@imgix/gatsby` to support Gatsby v5.10.0 ([#532](https://github.com/prismicio/prismic-gatsby/issues/532)) ([c729e0a](https://github.com/prismicio/prismic-gatsby/commit/c729e0aa64823db3a2c3f64b6cee1a56f42078b8))
* update dependencies ([57ceb56](https://github.com/prismicio/prismic-gatsby/commit/57ceb5625bbfb989745845c50d770bca659ae4c1))


### Features

* add `pageSize` option ([#456](https://github.com/prismicio/prismic-gatsby/issues/456)) ([72d6a68](https://github.com/prismicio/prismic-gatsby/commit/72d6a6860262293d3ade374387ac9ffa07b629da))
* add `routes` option to support Route Resolver ([#479](https://github.com/prismicio/prismic-gatsby/issues/479)) ([731f1a1](https://github.com/prismicio/prismic-gatsby/commit/731f1a119dabf1d19c9a1bd661fd158854e22fc1))
* support for custom fetch function ([#432](https://github.com/prismicio/prismic-gatsby/issues/432)) ([8f4a96f](https://github.com/prismicio/prismic-gatsby/commit/8f4a96ffd0653f4b6fe9271af52d2fdd35cd7876))
* support Gatsby 4 ([#466](https://github.com/prismicio/prismic-gatsby/issues/466)) ([d391580](https://github.com/prismicio/prismic-gatsby/commit/d391580a1ef5828b8bde018126eefdd859b54ae8))
* support Gatsby 5 ([#529](https://github.com/prismicio/prismic-gatsby/issues/529)) ([1971ce2](https://github.com/prismicio/prismic-gatsby/commit/1971ce24ee8f663df2e30ab71ff49508100bdeff))
* type Rich Text and Title fields with custom PrismicStructuredText scalar ([#473](https://github.com/prismicio/prismic-gatsby/issues/473)) ([5737479](https://github.com/prismicio/prismic-gatsby/commit/5737479f8c113341214da7b432bf70e590e294f7))
* v4.0.0 ([#408](https://github.com/prismicio/prismic-gatsby/issues/408)) ([407887f](https://github.com/prismicio/prismic-gatsby/commit/407887f2a039346420d4238beb8866dd33d230f8)), closes [#334](https://github.com/prismicio/prismic-gatsby/issues/334) [#335](https://github.com/prismicio/prismic-gatsby/issues/335) [#349](https://github.com/prismicio/prismic-gatsby/issues/349) [#350](https://github.com/prismicio/prismic-gatsby/issues/350) [#352](https://github.com/prismicio/prismic-gatsby/issues/352) [#353](https://github.com/prismicio/prismic-gatsby/issues/353) [#359](https://github.com/prismicio/prismic-gatsby/issues/359) [#360](https://github.com/prismicio/prismic-gatsby/issues/360) [#351](https://github.com/prismicio/prismic-gatsby/issues/351) [#364](https://github.com/prismicio/prismic-gatsby/issues/364) [#371](https://github.com/prismicio/prismic-gatsby/issues/371) [#375](https://github.com/prismicio/prismic-gatsby/issues/375) [#383](https://github.com/prismicio/prismic-gatsby/issues/383) [#405](https://github.com/prismicio/prismic-gatsby/issues/405) [#406](https://github.com/prismicio/prismic-gatsby/issues/406)


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

**Note:** Version bump only for package gatsby-source-prismic





## [6.0.1](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v6.0.0...v6.0.1) (2023-09-05)

**Note:** Version bump only for package gatsby-source-prismic





# [6.0.0](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v5.3.1...v6.0.0) (2023-06-29)

**Note:** Version bump only for package gatsby-source-prismic





# [6.0.0-alpha.19](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v6.0.0-alpha.18...v6.0.0-alpha.19) (2022-11-17)

**Note:** Version bump only for package gatsby-source-prismic





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
- remove `node:` prefix from Node.js imports ([6851757](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/6851757f4669bf6b385b84d99302b2d358d9461b))
- resolve correct image thumbnail URLs ([#41](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/41)) ([ef02eb0](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/ef02eb06294d2b5bd4a6ff20c54737600876edcc))
- resolve error when using `gatsbyImageData` with SVGs ([#13](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/13)) ([a1ae60d](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/a1ae60dec307f7017982adec228e2e4b539623cf))
- support `gatsbyImageData` fixed layout with given dimensions ([#17](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/17)) ([450864d](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/450864d085d14cf00f8f1985bebe43caf51175b0))
- support all `gatsbyImageData` parameters ([#19](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/19)) ([172389a](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/172389a752123738eb06cc33d8a8dd63467ce790))
- support empty Slice Zones ([#42](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/42)) ([30c1318](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/30c131860d7d72ddca467b11aa84f49f038c6e1e))
- support image thumbnails with dashes in their name ([#16](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/16)) ([6ba042f](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/6ba042fe33ec0678c04f69f70d5f20c1970fc7d3))
- support Integration Field catalogs with no usage ([#14](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/14)) ([2aaf89d](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/2aaf89d2816c244c1e44b261a94e5c420a0c8cbc))
- use `link_type` rather than `linkType` in `LinkField` ([1fa1b32](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/1fa1b3284114f854b8e60fa1b29dcb6d5e1a8a56))
- use correct required type name for AlternateLanguage ([7d1a658](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/7d1a65851571e95efde26cd75b7e5eaf8b3dbc70))

### Features

- 🍬 ([b7b5fdc](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/b7b5fdc441672f08f4f3ec2d8654fd2610374132))
- add `shouldDownloadFile` path to Link and Link to Media field descriptions ([#21](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/21)) ([2629eb0](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/2629eb02e3b6ac6293b6c34bc2ea13f7a0b2a501))
- add temporary timers to measure `sourecNodes` and preview times ([#25](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/25)) ([d932796](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/d9327969bfd51ea975b9e611d4329cf2a39386dc))
- **previews:** validate plugin options ([#10](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/10)) ([20e1beb](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/20e1bebf34093e1add544ab090f1ed13475f5658))
- restore Gatsby Cloud incremental builds support ([4a4a087](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/4a4a087b3b94b80a46b013dfc6d9a24f64611d7c))

# gatsby-source-prismic

## 6.0.0-alpha.15

## 6.0.0-alpha.14

### Patch Changes

- [#42](https://github.com/prismicio-community/prismic-gatsby-early-access/pull/42) [`30c1318`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/30c131860d7d72ddca467b11aa84f49f038c6e1e) Thanks [@angeloashmore](https://github.com/angeloashmore)! - Support Slice Zones without choices

## 6.0.0-alpha.13

### Patch Changes

- [#41](https://github.com/prismicio-community/prismic-gatsby-early-access/pull/41) [`ef02eb0`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/ef02eb06294d2b5bd4a6ff20c54737600876edcc) Thanks [@angeloashmore](https://github.com/angeloashmore)! - Resolve correct image thumbnail URLs

## 6.0.0-alpha.12

### Patch Changes

- [`89e23b9`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/89e23b95d6f729a5076ac7bcb78ba6f8018fec50) Thanks [@angeloashmore](https://github.com/angeloashmore)! - Support Boolean fields with a `null` value

* [`bd16c2e`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/bd16c2ef4a148afff8cec7935a43db24e9999d5e) Thanks [@angeloashmore](https://github.com/angeloashmore)! - Support environments and Gatsby versions that don't support `node:` imports

- [`00f34f2`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/00f34f2c851296d949bc511c42db631d78dbc302) Thanks [@angeloashmore](https://github.com/angeloashmore)! - Prevent Imgix rate-limiting when building site with many images

## 6.0.0-alpha.11

### Patch Changes

- [#25](https://github.com/prismicio-community/prismic-gatsby-early-access/pull/25) [`d932796`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/d9327969bfd51ea975b9e611d4329cf2a39386dc) Thanks [@angeloashmore](https://github.com/angeloashmore)! - Add temporary timers to measure `sourceNodes` and preview times

* [#21](https://github.com/prismicio-community/prismic-gatsby-early-access/pull/21) [`2629eb0`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/2629eb02e3b6ac6293b6c34bc2ea13f7a0b2a501) Thanks [@angeloashmore](https://github.com/angeloashmore)! - feat: add `shouldDownloadFile` path to Link and Link to Media field descriptions

## 6.0.0-alpha.10

### Patch Changes

- [#19](https://github.com/prismicio-community/prismic-gatsby-early-access/pull/19) [`172389a`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/172389a752123738eb06cc33d8a8dd63467ce790) Thanks [@angeloashmore](https://github.com/angeloashmore)! - Support all `gatsbyImageData` parameters

## 6.0.0-alpha.9

### Patch Changes

- [#17](https://github.com/prismicio-community/prismic-gatsby-early-access/pull/17) [`450864d`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/450864d085d14cf00f8f1985bebe43caf51175b0) Thanks [@angeloashmore](https://github.com/angeloashmore)! - Support `gatsbyImageData` fixed layout with given dimensions

## 6.0.0-alpha.8

### Patch Changes

- [#16](https://github.com/prismicio-community/prismic-gatsby-early-access/pull/16) [`6ba042f`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/6ba042fe33ec0678c04f69f70d5f20c1970fc7d3) Thanks [@angeloashmore](https://github.com/angeloashmore)! - Support image thumbnails with dashes in their name

## 6.0.0-alpha.7

### Patch Changes

- [#14](https://github.com/prismicio-community/prismic-gatsby-early-access/pull/14) [`2aaf89d`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/2aaf89d2816c244c1e44b261a94e5c420a0c8cbc) Thanks [@angeloashmore](https://github.com/angeloashmore)! - Support Integration Field catalogs with no usage

## 6.0.0-alpha.6

### Patch Changes

- [#13](https://github.com/prismicio-community/prismic-gatsby-early-access/pull/13) [`a1ae60d`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/a1ae60dec307f7017982adec228e2e4b539623cf) Thanks [@angeloashmore](https://github.com/angeloashmore)! - Resolve error when using `gatsbyImageData` with SVGs

* [#13](https://github.com/prismicio-community/prismic-gatsby-early-access/pull/13) [`a1954ea`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/a1954ea20bee0e8a596a822938740a71445dede6) Thanks [@angeloashmore](https://github.com/angeloashmore)! - Use `PrismicEmbedField` over `PrismicEmbed` everywhere

## 6.0.0-alpha.5

### Patch Changes

- [#12](https://github.com/prismicio-community/prismic-gatsby-early-access/pull/12) [`8a27248`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/8a27248e4f82ab6d90b7980617e315ef3b3f0cb9) Thanks [@angeloashmore](https://github.com/angeloashmore)! - Change UID field type from `ID!` to `String!`

## 6.0.0-alpha.4

### Patch Changes

- cba6c9b: Adds plugin options validation for `gatsby-plugin-prismic-previews`.
