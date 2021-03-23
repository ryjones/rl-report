# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 8 | 2 | 5 | 3 | 18 |

- [Fail](#user-content-fail)
  - [❌ `apache-license-file`](#user-content--apache-license-file)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `security-file-matches`](#user-content--security-file-matches)
  - [❌ `readme-references-license`](#user-content--readme-references-license)
  - [❌ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [❌ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [❌ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [❌ `integrates-with-ci`](#user-content--integrates-with-ci)
- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
- [Passed](#user-content-passed)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
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

### ❌ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Did not find a file matching the specified patterns. (`CHANGELOG.md`).

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

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `test/apitests.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/executechaincode.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/querychaincode.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/debug/karma.conf.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/debug/node.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/follow-redirects/http.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/follow-redirects/https.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/follow-redirects/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/ms/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/axios.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/defaults.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/utils.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/dist/axios.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/dist/axios.min.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/debug/src/browser.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/debug/src/debug.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/debug/src/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/debug/src/node.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/adapters/http.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/adapters/xhr.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/core/Axios.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/core/InterceptorManager.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/core/buildFullPath.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/core/createError.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/core/dispatchRequest.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/core/enhanceError.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/core/mergeConfig.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/core/settle.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/core/transformData.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/cancel/Cancel.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/cancel/CancelToken.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/cancel/isCancel.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/helpers/bind.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/helpers/buildURL.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/helpers/combineURLs.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/helpers/cookies.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/helpers/deprecatedMethod.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/helpers/isAbsoluteURL.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/helpers/isURLSameOrigin.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/helpers/normalizeHeaderName.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/helpers/parseHeaders.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `test/node_modules/axios/lib/helpers/spread.js`: The first 5 lines do not contain the pattern(s): Copyright, License.

</details>

## Passed <a href="#user-content-passed" id="passed">#</a>

<details>
<summary>Click to see rules</summary>

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`test`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!node_modules/**`).

### ✅ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Found file (`package.json`).

### ✅ `license-detectable-by-licensee` <a href="#user-content--license-detectable-by-licensee" id="-license-detectable-by-licensee">#</a>

Licensee identified the license for project: ISC.

</details>

## Ignored <a href="#user-content-ignored" id="ignored">#</a>

<details>
<summary>Click to see rules</summary>

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=ruby"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=java"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

