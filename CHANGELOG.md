# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [2.1.0](https://github.com/serverless/utils/compare/v2.0.0...v2.1.0) (2020-12-22)

### Features

- Add general logging utility ([#63](https://github.com/serverless/utils/issues/63)) ([58ccc3c](https://github.com/serverless/utils/commit/58ccc3c0ec741ce173982eb4b897cca2af6135b6)) ([Piotr Grzesik](https://github.com/pgrzesik))

### Bug Fixes

- Ensure that getConfig falls back to getGlobalConfig on error ([#62](https://github.com/serverless/utils/pull/62)) ([4f1251d](https://github.com/serverless/utils/commit/4f1251dc0500bb6f8c357832f243ca0524476fd9)) ([Piotr Grzesik](https://github.com/pgrzesik))
- Ensure that invalid user config is handled gracefully ([#62](https://github.com/serverless/utils/pull/62)) ([9537df2](https://github.com/serverless/utils/commit/9537df2b06bb7560ff0f0ad8f5dc4779cfcf9332)) ([Piotr Grzesik](https://github.com/pgrzesik))

## [2.0.0](https://github.com/serverless/utils/compare/v1.2.0...v2.0.0) (2020-09-21)

### ⚠ BREAKING CHANGES

- Node.js version 10 or later is required (dropped support for v6 and v8)

### Features

- Integrate @serverless/inquirer project ([#59](https://github.com/serverless/utils/pull/59)) ([3fc274a](https://github.com/serverless/utils/commit/3fc274a413ac04f34daee2abeff1b969686182c6)) ([Mariusz Nowak](https://github.com/medikoo))
- Drop support for Node.js v8 ([6cba266](https://github.com/serverless/utils/commit/6cba266861c9c55e4e897f896bb76cd265b0f80a)) ([Mariusz Nowak](https://github.com/medikoo))

## [1.2.0](https://github.com/serverless/utils/compare/v1.1.0...v1.2.0) (2020-06-26)

### Features

- Smarter notification resolution logic, also with support for unconditional notifications ([#56](https://github.com/serverless/utils/pull/56)) ([6329b1a](https://github.com/serverless/utils/commit/6329b1a03ce1ed57c8c922ea021a26f911d6e5c3)) ([Mariusz Nowak](https://github.com/medikoo))
- Configure AWS metrics URL ([#56](https://github.com/serverless/utils/pull/56)) ([c271b3f](https://github.com/serverless/utils/commit/c271b3f0a0e0901a3c45d5726c3e32b54a5a36ba)) ([Mariusz Nowak](https://github.com/medikoo))
- Provide eventual fallback to extended response format ([#56](https://github.com/serverless/utils/pull/56)) ([86ddb95](https://github.com/serverless/utils/commit/86ddb9575d635cdcf326436fe571cc1b2c5818b7)) ([Mariusz Nowak](https://github.com/medikoo))

## [1.1.0](https://github.com/serverless/utils/compare/v1.0.0...v1.1.0) (2020-06-15)

### Features

- **Analytics & Notifications URL**
  - By default do not expose analytics url in CI environment ([05ea565](https://github.com/serverless/utils/commit/05ea565a1642a9da10cb4770ef75ae70c4443a22)) ([Mariusz Nowak](https://github.com/medikoo))
  - Support override of analytics url via `SLS_ANALYTICS_URL` env var ([66ff290](https://github.com/serverless/utils/commit/66ff290a5c06b1b082e377eb3d8ead46b42c4f95)) ([Mariusz Nowak](https://github.com/medikoo))

### [1.0.0](https://github.com/serverless/utils/compare/v0.0.20...v1.0.0) (2020-06-12)

A new beginning. All old utilities were removed. Project now serves high level utilities for Serverless Framework and Component CLI's

### Features

- `analyticsAndNotificationsUrl` util ([b581cef](https://github.com/serverless/utils/commit/b581cef03961a0ee29e2fc9da577a7c0e600e915))
- `config` util ([aeb48d5](https://github.com/serverless/utils/commit/aeb48d58dab279e8c84db2f84b3515ba71815575))
- `isInChina` util ([c457d8c](https://github.com/serverless/utils/commit/c457d8c4e9829d9ab6d38a84e0f7c41809379f43))
- `processBackendNotificationRequest` util ([5249e2b](https://github.com/serverless/utils/commit/5249e2b9a09e72126382e902abeea38d9a089398))
