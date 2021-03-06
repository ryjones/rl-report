# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 5 | 4 | 7 | 3 | 19 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `security-file-matches`](#user-content--security-file-matches)
  - [❌ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [❌ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [❌ `integrates-with-ci`](#user-content--integrates-with-ci)
- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Did not find file matching the specified patterns. (`CODE_OF_CONDUCT*`).

### ❌ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Did not find file matching the specified patterns. (`SECURITY.md`).

### ❌ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `MAINTAINERS.md`
- `MAINTAINERS.rst`

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

- `support/Lab02/key.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `support/Lab02/rsa.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `support/Lab05/chaincode/index.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/index.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/ledger-api/state.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/ledger-api/statelist.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/lib/logistics-contract.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/lib/quc-contract.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/lib/user-contract.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/test/contract.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/ledger-api/state.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/ledger-api/statelist.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/lib/logistics-contract.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/lib/quc-contract.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/lib/user-contract.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/test/contract.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/lib/logistics/course-list.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/lib/logistics/course.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/lib/logistics/university-list.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/lib/logistics/university.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/lib/quc/feedback-list.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/lib/quc/feedback.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/lib/quc/quc-list.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/lib/quc/quc.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/lib/users/professor-list.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/lib/users/professor.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/lib/users/student-list.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab05/chaincode/lib/users/student.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/lib/logistics/course-list.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/lib/logistics/course.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/lib/logistics/university-list.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/lib/logistics/university.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/lib/quc/feedback-list.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/lib/quc/feedback.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/lib/quc/quc-list.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/lib/quc/quc.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/lib/users/professor-list.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/lib/users/professor.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/lib/users/student-list.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/chaincode/lib/users/student.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/b4s/organization/students-union/b4s_client/app.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `support/Lab06/b4s/organization/students-union/b4s_client/gateway.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `support/Lab06/b4s/organization/students-union/utils/addToWallet.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/b4s/organization/students-union/utils/renamePK.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `support/Lab06/b4s/organization/students-union/utils/showIdentity.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/b4s/organization/university/b4s_client/app.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `support/Lab06/b4s/organization/university/b4s_client/gateway.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `support/Lab06/b4s/organization/university/user-interface/babel.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `support/Lab06/b4s/organization/university/utils/addToWallet.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/b4s/organization/university/utils/createUniversity.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/b4s/organization/university/utils/renamePK.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `support/Lab06/b4s/organization/university/utils/showIdentity.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `support/Lab06/b4s/organization/students-union/b4s_client/routes/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `support/Lab06/b4s/organization/students-union/b4s_client/routes/logistics.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `support/Lab06/b4s/organization/university/b4s_client/routes/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `support/Lab06/b4s/organization/university/b4s_client/routes/logistics.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `support/Lab06/b4s/organization/university/b4s_client/routes/users.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `support/Lab06/b4s/organization/university/user-interface/src/main.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `support/Lab06/b4s/organization/university/user-interface/src/router.js`: The first 7 lines do not contain the pattern(s): Copyright, License.

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

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`support/Lab02/test`).

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

