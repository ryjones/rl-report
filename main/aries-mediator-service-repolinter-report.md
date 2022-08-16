# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 7 | 5 | 3 | 4 | 19 |

- [Fail](#user-content-fail)
  - [❌ `apache-license-file`](#user-content--apache-license-file)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `security-file-matches`](#user-content--security-file-matches)
  - [❌ `readme-references-license`](#user-content--readme-references-license)
  - [❌ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [❌ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [❌ `integrates-with-ci`](#user-content--integrates-with-ci)
- [Warning](#user-content-warning)
  - [⚠️ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Passed](#user-content-passed)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `apache-license-file` <a href="#user-content--apache-license-file" id="-apache-license-file">#</a>

Did not find file matching the specified patterns. (`LICENSE*`).

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Did not find file matching the specified patterns. (`CODE_OF_CONDUCT*`).

### ❌ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Did not find file matching the specified patterns. (`SECURITY.md`).

### ❌ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Doesn't contain license (`README.md`).

### ❌ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `MAINTAINERS.md`
- `MAINTAINERS.rst`

### ❌ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Did not find a file matching the specified patterns. (`CONTRIBUTING.md`).

### ❌ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `circle.yml`
- `.circleci/config.yml`
- `ci/azure-pipelines.yml`
- `.ci/azure-pipelines.yml`
- `Jenkinsfile`
- `Jenkinsfile.ci`
- `Jenkinsfile.cd`
- `.github/workflows/*.yml`


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Did not find a file matching the specified patterns. (`CHANGELOG.md`).

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `acapy/controller/jest.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/app.hooks.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/app.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/channels.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/declarations.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/logger.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/test/app.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/middleware/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/models/endorser.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/models/enums.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/models/errors.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/services/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/utils/aca-py.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/utils/sleep.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/test/services/webhooks.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/services/aries-agent/aries-agent.class.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/services/aries-agent/aries-agent.hooks.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/services/aries-agent/aries-agent.service.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/services/webhooks/webhooks.class.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/services/webhooks/webhooks.hooks.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acapy/controller/src/services/webhooks/webhooks.service.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`package.json`).

### ⚠️ `license-detectable-by-licensee` <a href="#user-content--license-detectable-by-licensee" id="-license-detectable-by-licensee">#</a>

Licensee did not identify a license for project.

</details>

## Passed <a href="#user-content-passed" id="passed">#</a>

<details>
<summary>Click to see rules</summary>

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`acapy/controller/test`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!**/node_modules/**`).

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
