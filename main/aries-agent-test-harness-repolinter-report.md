# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 3 | 5 | 8 | 3 | 19 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `security-file-matches`](#user-content--security-file-matches)
  - [❌ `maintainers-file-exists`](#user-content--maintainers-file-exists)
- [Warning](#user-content-warning)
  - [⚠️ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Doesn't contain https://wiki.hyperledger.org/community/hyperledger-project-code-of-conduct (`CODE_OF_CONDUCT.md`).

### ❌ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Did not find file matching the specified patterns. (`SECURITY.md`).

### ❌ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `MAINTAINERS.md`
- `MAINTAINERS.rst`


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Did not find a file matching the specified patterns. (`CHANGELOG.md`).

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `aries-backchannels/verity/verity_backchannel.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/BaseController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/Server.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/TestAgent.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/TestHarnessConfig.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/TsedLogger.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/controllers/AgentStatusController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/controllers/ConnectionController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/controllers/CredentialController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/controllers/CredentialDefinitionController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/controllers/DidController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/controllers/IssueCredentialController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/controllers/IssueCredentialV2Controller.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/controllers/MediationController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/controllers/PresentProofController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/controllers/SchemaController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/utils/ConnectionUtils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/utils/CredentialUtils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/utils/ProofUtils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/utils/httpUtils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `aries-backchannels/javascript/server/src/utils/ledgerUtils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`package.json`).

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `setup.py`
- `requirements.txt`

</details>

## Passed <a href="#user-content-passed" id="passed">#</a>

<details>
<summary>Click to see rules</summary>

### ✅ `apache-license-file` <a href="#user-content--apache-license-file" id="-apache-license-file">#</a>

Contains Apache License.*Version 2.0 (`LICENSE`).

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Contains license (`README.md`).

### ✅ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Found file (`CONTRIBUTING.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/generate-summary-results.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`TEST-COVERAGE.md`).

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

</details>

