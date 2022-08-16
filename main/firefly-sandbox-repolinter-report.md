# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 1 | 3 | 11 | 4 | 19 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Doesn't contain https://wiki.hyperledger.org/community/hyperledger-project-code-of-conduct (`CODE_OF_CONDUCT.md`).


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `server/jest.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/src/enums.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/src/interfaces.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/src/logger.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/src/server.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/src/utils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/test/common.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/test/contracts.template.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/test/contracts.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/test/datatypes.template.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/test/datatypes.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/test/messages.template.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/test/messages.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/test/misc.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/test/tokens.template.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/test/tokens.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `ui/src/react-app-env.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `ui/src/setupTests.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/src/clients/firefly.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/src/controllers/common.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/src/controllers/contracts.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/src/controllers/datatypes.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/src/controllers/messages.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/src/controllers/tokens.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `server/src/controllers/websocket.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `ui/src/constants/ResourceUrls.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `ui/src/constants/SDK_PATHS.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `ui/src/ff_models/messageTypes.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `ui/src/interfaces/api.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `ui/src/interfaces/ff.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `ui/src/interfaces/tutorialSection.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `ui/src/utils/decimals.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `ui/src/utils/decimals.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `ui/src/utils/fetches.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `ui/src/utils/files.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `ui/src/utils/strings.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `ui/src/utils/time.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`package.json`).

</details>

## Passed <a href="#user-content-passed" id="passed">#</a>

<details>
<summary>Click to see rules</summary>

### ✅ `apache-license-file` <a href="#user-content--apache-license-file" id="-apache-license-file">#</a>

Contains Apache License.*Version 2.0 (`LICENSE`).

### ✅ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Contains https://wiki.hyperledger.org/display/.*(SEC|HYP)/Defect[.+]Response (`SECURITY.md`).

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Contains license (`README.md`).

### ✅ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Found file (`MAINTAINERS.md`).

### ✅ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Found file (`CONTRIBUTING.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/docker_main.yml`).

### ✅ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Found file (`CHANGELOG.md`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`server/test`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!**/node_modules/**`).

### ✅ `license-detectable-by-licensee` <a href="#user-content--license-detectable-by-licensee" id="-license-detectable-by-licensee">#</a>

Licensee identified the license for project: Apache-2.0.

</details>

## Ignored <a href="#user-content-ignored" id="ignored">#</a>

<details>
<summary>Click to see rules</summary>

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=go"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=ruby"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=java"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

