# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 5 | 6 | 6 | 2 | 19 |

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
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
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

- `benchmarks/scenario/simple/open.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/simple/query.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/simple/transfer.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/smallbank/create.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/smallbank/modify.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/smallbank/query.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/batch-create-asset.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/batch-delete-asset.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/batch-get-asset.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/create-asset.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/create-private-asset.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/delete-asset.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/empty-contract.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/get-asset.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/get-private-asset.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/helper.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/mixed-range-query-asset.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/mixed-rich-query-asset.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/range-query-asset.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/rich-query-asset.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fabric/fabcar/changeCarOwner.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fabric/fabcar/createCar.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fabric/fabcar/queryAllCars.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fabric/fabcar/queryCar.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fabric/marbles/init.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fabric/marbles/query.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fisco-bcos/helloworld/get.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fisco-bcos/helloworld/set.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fisco-bcos/transfer/addUser.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/samples/fisco-bcos/transfer/transfer.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/simple/utils/operation-base.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/simple/utils/simple-state.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/smallbank/utils/operation-base.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/scenario/smallbank/utils/smallbank.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/read-write-assets/delete-preloaded-assets.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/read-write-assets/preload-assets.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `benchmarks/api/fabric/workloads/read-write-assets/read-write-assets.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/api/fixed-asset/node/index.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/api/fixed-asset-base/node/fixed-asset-base.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/samples/fabcar/node/index.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/samples/marbles/node/marbles.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/samples/marbles-norichquery/node/marbles.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/scenario/simple/node/simpletest.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/api/fixed-asset/node/lib/fixed-asset.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/samples/fabcar/node/lib/fabcar.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/api/fixed-asset/go/FixedAssetContract.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/fabric/api/fixed-asset-base/go/main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/fabric/samples/fabcar/go/fabcar.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/samples/marbles/go/marbles.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/samples/marbles-norichquery/go/marbles.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/scenario/simple/go/simpletest.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/scenario/smallbank/go/smallbank.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/api/fixed-asset/go/assets/FixedAsset.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/fabric/api/fixed-asset/go/utils/QueryResponse.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/fabric/api/fixed-asset/go/utils/ResponseMetadata.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/fabric/api/fixed-asset-base/go/assets/FixedAsset.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/fabric/api/fixed-asset-base/go/contracts/FixedAssetContract.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/fabric/api/fixed-asset-base/go/utils/Context.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/fabric/api/fixed-asset-base/go/utils/QueryResponse.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/fabric/api/fixed-asset-base/go/utils/ResponseMetadata.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/fabric/api/fixed-asset/java/src/main/java/org/example/FixedAsset.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/api/fixed-asset/java/src/main/java/org/example/FixedAssetContract.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/api/fixed-asset/java/src/main/java/org/example/QueryResponse.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/fabric/api/fixed-asset/java/src/main/java/org/example/ResponseMetadata.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/fabric/samples/fabcar/java/src/main/java/org/hyperledger/fabric/samples/fabcar/Car.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/samples/fabcar/java/src/main/java/org/hyperledger/fabric/samples/fabcar/FabCar.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/samples/fabcar/java/src/test/java/org/hyperledger/fabric/samples/fabcar/CarTest.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `src/fabric/samples/fabcar/java/src/test/java/org/hyperledger/fabric/samples/fabcar/FabCarTest.java`: The first 7 lines do not contain the pattern(s): Copyright.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`package.json`).

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`go.mod`).

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

### ✅ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Contains https://wiki.hyperledger.org/display/.*(SEC|HYP)/Defect[.+]Response (`SECURITY.md`).

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`networks/fabric/test-network.yaml`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!**/node_modules/**`).

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

