# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 5 | 4 | 6 | 4 | 19 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `readme-references-license`](#user-content--readme-references-license)
  - [❌ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [❌ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [❌ `integrates-with-ci`](#user-content--integrates-with-ci)
- [Warning](#user-content-warning)
  - [⚠️ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `test-directory-exists`](#user-content--test-directory-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Did not find file matching the specified patterns. (`CODE_OF_CONDUCT*`).

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

- `src/proto/block_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/commands_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/endpoint_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/endpoint_pb_service.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/primitive_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/proposal_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/qry_responses_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/queries_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/transaction_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `example/chain.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `example/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `example/tls.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/chain.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/cryptoHelper.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/queryHelper.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/txHelper.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/util.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `example/smart-contract/getAccountTransactions.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `example/smart-contract/integrationHelpers.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/commands/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/block_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/commands_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/endpoint_grpc_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/endpoint_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/endpoint_pb_service.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/primitive_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/proposal_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/qry_responses_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/queries_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/proto/transaction_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/queries/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/validation/checks.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/validation/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `**/test*`
- `**/specs`
- `**/**_test.go`

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

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!**/node_modules/**`).

### ✅ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Found file (`package.json`).

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

