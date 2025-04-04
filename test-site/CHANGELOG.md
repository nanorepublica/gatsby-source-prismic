# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [7.0.0](https://github.com/nanorepublica/gatsby-source-prismic/compare/v3.1.4...v7.0.0) (2025-04-04)


### Bug Fixes

* allow complete opt-in file downloading ([#470](https://github.com/nanorepublica/gatsby-source-prismic/issues/470)) ([c1b27b3](https://github.com/nanorepublica/gatsby-source-prismic/commit/c1b27b3003372dc258d5d9911e748a448b0e408d))
* correctly resolve fields with transformed names ([#415](https://github.com/nanorepublica/gatsby-source-prismic/issues/415)) ([1c7907f](https://github.com/nanorepublica/gatsby-source-prismic/commit/1c7907f420e22b99d3c6009d85c443e2a00fa414))


### Features

* support Gatsby 4 ([#466](https://github.com/nanorepublica/gatsby-source-prismic/issues/466)) ([d391580](https://github.com/nanorepublica/gatsby-source-prismic/commit/d391580a1ef5828b8bde018126eefdd859b54ae8))
* support Gatsby 5 ([#529](https://github.com/nanorepublica/gatsby-source-prismic/issues/529)) ([1971ce2](https://github.com/nanorepublica/gatsby-source-prismic/commit/1971ce24ee8f663df2e30ab71ff49508100bdeff))
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

**Note:** Version bump only for package test-site





## [6.0.1](https://github.com/prismicio/prismic-gatsby/compare/v6.0.0...v6.0.1) (2023-09-05)

**Note:** Version bump only for package test-site





# [6.0.0](https://github.com/prismicio/prismic-gatsby/compare/v5.3.1...v6.0.0) (2023-06-29)

**Note:** Version bump only for package test-site





# [6.0.0-alpha.19](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v6.0.0-alpha.18...v6.0.0-alpha.19) (2022-11-17)

**Note:** Version bump only for package test-site





# [6.0.0-alpha.18](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v6.0.0-alpha.17...v6.0.0-alpha.18) (2022-11-17)

**Note:** Version bump only for package test-site

# [6.0.0-alpha.17](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v6.0.0-alpha.16...v6.0.0-alpha.17) (2022-11-04)

**Note:** Version bump only for package test-site

# [6.0.0-alpha.16](https://github.com/prismicio-community/prismic-gatsby-early-access/compare/v6.0.0-alpha.0...v6.0.0-alpha.16) (2022-11-02)

### Features

- 🍬 ([b7b5fdc](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/b7b5fdc441672f08f4f3ec2d8654fd2610374132))
- add debug `usePrismicPreviewState()` hook ([#43](https://github.com/prismicio-community/prismic-gatsby-early-access/issues/43)) ([a3321a4](https://github.com/prismicio-community/prismic-gatsby-early-access/commit/a3321a45e074ebf0b49dc95c6fe48b65734305d0))
