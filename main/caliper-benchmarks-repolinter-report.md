# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 7 | 4 | 5 | 2 | 18 |

- [Fail](#user-content-fail)
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
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Did not find file matching the specified patterns. (`CODE_OF_CONDUCT*`).

### ❌ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Doesn't contain https://wiki.hyperledger.org/display/SEC/Defect+Response (`SECURITY.md`).

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

- `benchmarks/scenario/simple/open.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/simple/query.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/simple/transfer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/smallbank/create.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/smallbank/modify.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/smallbank/query.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/lib/batch-create-asset.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/lib/batch-delete-asset.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/lib/batch-get-asset.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/lib/create-asset.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/lib/create-private-asset.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/lib/delete-asset.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/lib/empty-contract.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/lib/get-asset.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/lib/get-private-asset.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/lib/helper.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/lib/mixed-range-query-asset.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/lib/mixed-rich-query-asset.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/lib/range-query-asset.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/lib/rich-query-asset.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fabric/fabcar/changeCarOwner.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fabric/fabcar/createCar.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fabric/fabcar/helper.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fabric/fabcar/queryAllCars.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fabric/fabcar/queryCar.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fabric/marbles/init.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fabric/marbles/query.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fisco-bcos/helloworld/get.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fisco-bcos/helloworld/set.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fisco-bcos/transfer/addUser.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fisco-bcos/transfer/transfer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/simple/utils/operation-base.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/simple/utils/simple-state.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/smallbank/utils/operation-base.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/smallbank/utils/smallbank.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/fabric/api/fixed-asset/node/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/fabric/api/fixed-asset-base/node/fixed-asset-base.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/fabric/samples/fabcar/javascript/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/fabric/samples/marbles/node/marbles.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/fabric/samples/marbles-norichquery/node/marbles.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/fabric/scenario/simple/node/simpletest.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/fabric/api/fixed-asset/node/lib/fixed-asset.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `src/fabric/samples/fabcar/javascript/lib/fabcar.js`: The first 5 lines do not contain the pattern(s): Copyright.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`package.json`).

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

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`benchmarks/api/fabric/test.yaml`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!node_modules/**`).

### ✅ `license-detectable-by-licensee` <a href="#user-content--license-detectable-by-licensee" id="-license-detectable-by-licensee">#</a>

Licensee identified the license for project: Apache-2.0.

</details>

## Ignored <a href="#user-content-ignored" id="ignored">#</a>

<details>
<summary>Click to see rules</summary>

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=ruby"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

