# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 5 | 5 | 7 | 1 | 18 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `security-file-matches`](#user-content--security-file-matches)
  - [❌ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [❌ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [❌ `changelog-file-exists`](#user-content--changelog-file-exists)
- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `test-directory-exists`](#user-content--test-directory-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
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

### ❌ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Did not find a file matching the specified patterns. (`CONTRIBUTING.md`).

### ❌ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Did not find a file matching the specified patterns. (`CHANGELOG.md`).


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `App.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `babel.config.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `commitlint.config.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `jest.config.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `metro.config.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `__tests__/App-test.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `assets/images.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `assets/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/AppHeader/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/AppHeaderLarge/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/CurrentContact/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/CurrentCredential/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/Errors/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/ListContacts/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/ListCredentials/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/LoadingOverlay/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/Message/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/Navbar/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/Notifications/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/Settings/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/SetupWizard/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/Terms/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/Workflow/Credential/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `components/Workflow/QRCodeScanner/styles.js`: The first 5 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `**/test*`
- `**/specs`
- `**/**_test.go`

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`Gemfile`).

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `pom.xml`
- `build.xml`
- `build.gradle`

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

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/repolinter.yml`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!node_modules/**`).

### ✅ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Found file (`package.json`).

### ✅ `license-detectable-by-licensee` <a href="#user-content--license-detectable-by-licensee" id="-license-detectable-by-licensee">#</a>

Licensee identified the license for project: Apache-2.0.

</details>

## Ignored <a href="#user-content-ignored" id="ignored">#</a>

<details>
<summary>Click to see rules</summary>

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

