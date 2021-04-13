# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 3 | 5 | 9 | 2 | 19 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [❌ `changelog-file-exists`](#user-content--changelog-file-exists)
- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Did not find file matching the specified patterns. (`CODE_OF_CONDUCT*`).

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

- `tools/PTE/ccArgumentsGenerators/ccFunctionsBase.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `regression/barebones_caliper/benchmarks/callbacks/barebonesCreateAsset.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/PTE/CITest/scripts/test_driver.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/PTE/CITest/scripts/test/test.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `regression/barebones/barebones_suite_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `regression/barebones/barebones_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `regression/barebones_caliper/barebones_suite_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `regression/barebones_caliper/barebones_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `regression/basicnetwork/basicnetwork_suite_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `regression/basicnetwork/basicnetwork_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `regression/publish/publish_suite_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `regression/publish/publish_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `regression/smoke/smoke_suite_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `regression/smoke/smoke_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/gotools/tools.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `chaincodes/marbles02/go/marbles_chaincode.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `tools/operator/connectionprofile/updateconncectionprofile.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/fabricconfiguration/configtx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/logger/logger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/networkclient/channelTx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/networkclient/checkNetworkInSync.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/networkclient/command.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/networkclient/createconfigtx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/networkclient/cryptogen.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/networkclient/migrateToRaft.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/networkclient/upgradeNetwork.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/paths/paths.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/testclient/testclient.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/utilities/git.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/utilities/git_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/launcher/dockercompose/health.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/launcher/dockercompose/network.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/launcher/k8s/connprofile.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/launcher/k8s/extendNetwork.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/launcher/k8s/health.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/launcher/k8s/network.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/testclient/inputStructs/structs.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/testclient/operations/channelConfig.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/testclient/operations/executeCommand.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/testclient/operations/installchaincode.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/testclient/operations/instantiatechaincode.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/testclient/operations/invokequery.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/testclient/operations/joinBySnapshot.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tools/operator/testclient/operations/snapshot.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `regression/hsm/chaincode/fabcar/go/fabcar.go`: The first 7 lines do not contain the pattern(s): Copyright.

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

### ✅ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Contains license (`README.md`).

### ✅ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Found file (`MAINTAINERS.rst`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`ci/azure-pipelines.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`regression/testdata`).

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

