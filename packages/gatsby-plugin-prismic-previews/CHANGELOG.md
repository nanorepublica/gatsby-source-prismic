# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [7.0.0](https://github.com/prismicio/prismic-gatsby/compare/v3.1.4...v7.0.0) (2025-04-04)


### Bug Fixes

* allow complete opt-in file downloading ([#470](https://github.com/prismicio/prismic-gatsby/issues/470)) ([c1b27b3](https://github.com/prismicio/prismic-gatsby/commit/c1b27b3003372dc258d5d9911e748a448b0e408d))
* correctly resolve fields with transformed names ([#415](https://github.com/prismicio/prismic-gatsby/issues/415)) ([1c7907f](https://github.com/prismicio/prismic-gatsby/commit/1c7907f420e22b99d3c6009d85c443e2a00fa414))
* image field proxy types ([91e07eb](https://github.com/prismicio/prismic-gatsby/commit/91e07eb91275db18312193c1b39cfbbbf1f3fb7a))
* lock `@prismicio/client` version ([43e7795](https://github.com/prismicio/prismic-gatsby/commit/43e77957ed579ae1519699278c56522da5b8c75a))
* omit `target` attribute on links without a target ([#520](https://github.com/prismicio/prismic-gatsby/issues/520)) ([abfb55e](https://github.com/prismicio/prismic-gatsby/commit/abfb55e37bdd431cebe78caaebe0f939dd8d7fd7))
* **previews:** catch error when a field type cannot be found ([352c923](https://github.com/prismicio/prismic-gatsby/commit/352c9238c51166863134aed823ae609807be6b01))
* **previews:** correctly resolve the `url` property in link fields ([#542](https://github.com/prismicio/prismic-gatsby/issues/542)) ([0a426c5](https://github.com/prismicio/prismic-gatsby/commit/0a426c5f64b74af36f8b1c656355d44502c2ecfd))
* **previews:** resolve CORS error with `@prismicio/client` ([1d66749](https://github.com/prismicio/prismic-gatsby/commit/1d6674912d5780de37d8cad78c56b59b0d83b92a))
* **previews:** retain correct scroll position during preview bootstrapping ([#504](https://github.com/prismicio/prismic-gatsby/issues/504)) ([46803df](https://github.com/prismicio/prismic-gatsby/commit/46803df0147f6c909369b82c976e14aac2053543))
* **previews:** support React 18 ([#508](https://github.com/prismicio/prismic-gatsby/issues/508)) ([6f55e01](https://github.com/prismicio/prismic-gatsby/commit/6f55e01efb55825699a99f6c47a6c1e780ad73e7))
* **previews:** treat null link fields as valid ([#433](https://github.com/prismicio/prismic-gatsby/issues/433)) ([4e6cc1d](https://github.com/prismicio/prismic-gatsby/commit/4e6cc1db493baa13d7b74b7f95c52c30f55a149d))
* **previews:** wait for bootstrap to complete before merging data ([4b9bfe4](https://github.com/prismicio/prismic-gatsby/commit/4b9bfe4594810bf3b4de919ed0b3c967c20b4382))
* replace `@prismicio/client`'s `getAll` with `dangerouslyGetAll` ([50c0ef2](https://github.com/prismicio/prismic-gatsby/commit/50c0ef2e1628394c29755380f26926428436dd2a))
* update @prismicio/imgix (fixes [#488](https://github.com/prismicio/prismic-gatsby/issues/488)) ([7eb0269](https://github.com/prismicio/prismic-gatsby/commit/7eb02693d750f01c06a34bf4c5c781a872ee7a01))
* update `@imgix/gatsby` to support Gatsby v5.10.0 ([#532](https://github.com/prismicio/prismic-gatsby/issues/532)) ([c729e0a](https://github.com/prismicio/prismic-gatsby/commit/c729e0aa64823db3a2c3f64b6cee1a56f42078b8))
* update dependencies ([57ceb56](https://github.com/prismicio/prismic-gatsby/commit/57ceb5625bbfb989745845c50d770bca659ae4c1))


### Features

* add `pageSize` option ([#456](https://github.com/prismicio/prismic-gatsby/issues/456)) ([72d6a68](https://github.com/prismicio/prismic-gatsby/commit/72d6a6860262293d3ade374387ac9ffa07b629da))
* add `routes` option to support Route Resolver ([#479](https://github.com/prismicio/prismic-gatsby/issues/479)) ([731f1a1](https://github.com/prismicio/prismic-gatsby/commit/731f1a119dabf1d19c9a1bd661fd158854e22fc1))
* support Gatsby 4 ([#466](https://github.com/prismicio/prismic-gatsby/issues/466)) ([d391580](https://github.com/prismicio/prismic-gatsby/commit/d391580a1ef5828b8bde018126eefdd859b54ae8))
* support Gatsby 5 ([#529](https://github.com/prismicio/prismic-gatsby/issues/529)) ([1971ce2](https://github.com/prismicio/prismic-gatsby/commit/1971ce24ee8f663df2e30ab71ff49508100bdeff))
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

**Note:** Version bump only for package gatsby-plugin-prismic-previews





## [6.0.1](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v6.0.0...v6.0.1) (2023-09-05)


### Bug Fixes

* **previews:** correctly resolve the `url` property in link fields ([#542](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/542)) ([0a426c5](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/0a426c5f64b74af36f8b1c656355d44502c2ecfd))





# [6.0.0](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v5.3.1...v6.0.0) (2023-06-29)

**Note:** Version bump only for package gatsby-plugin-prismic-previews





# [6.0.0-alpha.19](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v6.0.0-alpha.18...v6.0.0-alpha.19) (2022-11-17)

**Note:** Version bump only for package gatsby-plugin-prismic-previews





# [6.0.0-alpha.18](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v6.0.0-alpha.17...v6.0.0-alpha.18) (2022-11-17)

### Bug Fixes

- handle nonexistent fields ([#49](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/49)) ([28e9ee5](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/28e9ee551fa1a50b364d17dc19a7123c13b6971d))

# [6.0.0-alpha.17](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v6.0.0-alpha.16...v6.0.0-alpha.17) (2022-11-04)

### Bug Fixes

- allow `uid` and `lang` Route Resolver options ([#48](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/48)) ([fbe8586](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/fbe858663b17098c2305793b962ce45255c0cc18))

# [6.0.0-alpha.16](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v6.0.0-alpha.0...v6.0.0-alpha.16) (2022-11-02)

### Bug Fixes

- builds and tests ([d664e4a](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/d664e4acd50adc61a7671181d3daddbb623686df))
- **previews:** replace nanostores with Zustand ([#44](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/44)) ([5e5aa05](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/5e5aa0567388dcdadb7b07c5862ff439922ddb8f))
- remove `node:` prefix from Node.js imports ([6851757](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/6851757f4669bf6b385b84d99302b2d358d9461b))
- support image thumbnails with dashes in their name ([#16](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/16)) ([6ba042f](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/6ba042fe33ec0678c04f69f70d5f20c1970fc7d3))

### Features

- 🍬 ([b7b5fdc](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/b7b5fdc441672f08f4f3ec2d8654fd2610374132))
- add debug `usePrismicPreviewState()` hook ([#43](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/43)) ([a3321a4](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/a3321a45e074ebf0b49dc95c6fe48b65734305d0))
- add temporary timers to measure `sourecNodes` and preview times ([#25](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/25)) ([d932796](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/d9327969bfd51ea975b9e611d4329cf2a39386dc))
- **previews:** validate plugin options ([#10](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/10)) ([20e1beb](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/20e1bebf34093e1add544ab090f1ed13475f5658))
- restore Gatsby Cloud incremental builds support ([4a4a087](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/4a4a087b3b94b80a46b013dfc6d9a24f64611d7c))

# gatsby-plugin-prismic-previews

## 6.0.0-alpha.15

### Patch Changes

- [#44](https://github.com/prismicio-community/prismic-gatsby-early-access/pull/44) [`5e5aa05`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/5e5aa0567388dcdadb7b07c5862ff439922ddb8f) Thanks [@angeloashmore](https://github.com/angeloashmore)! - Replace Nano Stores with Zustand

- Updated dependencies []:
  - gatsby-source-prismic@6.0.0-alpha.15

## 6.0.0-alpha.14

### Patch Changes

- Updated dependencies [[`30c1318`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/30c131860d7d72ddca467b11aa84f49f038c6e1e)]:
  - gatsby-source-prismic@6.0.0-alpha.14

## 6.0.0-alpha.13

### Patch Changes

- Updated dependencies [[`ef02eb0`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/ef02eb06294d2b5bd4a6ff20c54737600876edcc)]:
  - gatsby-source-prismic@6.0.0-alpha.13

## 6.0.0-alpha.12

### Patch Changes

- Updated dependencies [[`89e23b9`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/89e23b95d6f729a5076ac7bcb78ba6f8018fec50), [`bd16c2e`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/bd16c2ef4a148afff8cec7935a43db24e9999d5e), [`00f34f2`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/00f34f2c851296d949bc511c42db631d78dbc302)]:
  - gatsby-source-prismic@6.0.0-alpha.12

## 6.0.0-alpha.11

### Patch Changes

- [#25](https://github.com/prismicio-community/prismic-gatsby-early-access/pull/25) [`d932796`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/d9327969bfd51ea975b9e611d4329cf2a39386dc) Thanks [@angeloashmore](https://github.com/angeloashmore)! - Add temporary timers to measure `sourceNodes` and preview times

- Updated dependencies [[`d932796`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/d9327969bfd51ea975b9e611d4329cf2a39386dc), [`2629eb0`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/2629eb02e3b6ac6293b6c34bc2ea13f7a0b2a501)]:
  - gatsby-source-prismic@6.0.0-alpha.11

## 6.0.0-alpha.10

### Patch Changes

- Updated dependencies [[`172389a`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/172389a752123738eb06cc33d8a8dd63467ce790)]:
  - gatsby-source-prismic@6.0.0-alpha.10

## 6.0.0-alpha.9

### Patch Changes

- Updated dependencies [[`450864d`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/450864d085d14cf00f8f1985bebe43caf51175b0)]:
  - gatsby-source-prismic@6.0.0-alpha.9

## 6.0.0-alpha.8

### Patch Changes

- Updated dependencies [[`6ba042f`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/6ba042fe33ec0678c04f69f70d5f20c1970fc7d3)]:
  - gatsby-source-prismic@6.0.0-alpha.8

## 6.0.0-alpha.7

### Patch Changes

- Updated dependencies [[`2aaf89d`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/2aaf89d2816c244c1e44b261a94e5c420a0c8cbc)]:
  - gatsby-source-prismic@6.0.0-alpha.7

## 6.0.0-alpha.6

### Patch Changes

- Updated dependencies [[`a1ae60d`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/a1ae60dec307f7017982adec228e2e4b539623cf), [`a1954ea`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/a1954ea20bee0e8a596a822938740a71445dede6)]:
  - gatsby-source-prismic@6.0.0-alpha.6

## 6.0.0-alpha.5

### Patch Changes

- Updated dependencies [[`8a27248`](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/8a27248e4f82ab6d90b7980617e315ef3b3f0cb9)]:
  - gatsby-source-prismic@6.0.0-alpha.5

## 6.0.0-alpha.4

### Patch Changes

- cba6c9b: Adds plugin options validation for `gatsby-plugin-prismic-previews`.
- Updated dependencies [cba6c9b]
  - gatsby-source-prismic@6.0.0-alpha.4
