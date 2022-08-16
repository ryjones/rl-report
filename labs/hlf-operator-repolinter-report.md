# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 4 | 4 | 9 | 2 | 19 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `security-file-matches`](#user-content--security-file-matches)
  - [❌ `readme-references-license`](#user-content--readme-references-license)
  - [❌ `contributing-file-exists`](#user-content--contributing-file-exists)
- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Did not find file matching the specified patterns. (`CODE_OF_CONDUCT*`).

### ❌ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Did not find file matching the specified patterns. (`SECURITY.md`).

### ❌ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Doesn't contain license (`README.md`).

### ❌ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Did not find a file matching the specified patterns. (`CONTRIBUTING.md`).


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `website-docs/babel.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `website-docs/docusaurus.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `website-docs/sidebars.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/client/nodejs/enrollAdmin.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/client/nodejs/invoke.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/client/nodejs/register.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `website-docs/src/pages/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fixtures/chaincodes/fabcar/typescript/src/car.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `fixtures/chaincodes/fabcar/typescript/src/fabcar.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `fixtures/chaincodes/fabcar/typescript/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright.
- `main.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `controllers/hlf_controller.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `controllers/suite_test.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `kubectl-hlf/main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `api/hlf.kungfusoftware.es/register.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/ca/ca_controller.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/ca/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/certs/provision_certs.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/chaincode/chaincode_controller.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/console/console_controller.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/console/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/explorer/explorer_controller.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/explorer/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/hlfmetrics/metrics.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/networkconfig/networkconfig_controller.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/operatorapi/operatorapi.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/operatorapi/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/operatorui/operatorui.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/operatorui/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/ordnode/ordnode_controller.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/ordnode/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/ordservice/ordservice_controller.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/ordservice/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/peer/peer_controller.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/peer/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/tests/ca_controller_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/tests/ord_controller_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/tests/peer_controller_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/tests/suite_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/tests/utils.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/testutils/channel.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/testutils/genesis.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `controllers/utils/utils.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/kubectl-hlf.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `api/hlf.kungfusoftware.es/v1alpha1/doc.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `api/hlf.kungfusoftware.es/v1alpha1/groupversion_info.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `api/hlf.kungfusoftware.es/v1alpha1/hlf_types.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `api/hlf.kungfusoftware.es/v1alpha1/zz_generated.deepcopy.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `examples/client/go/main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fixtures/external-chaincode/asset-external/assetTransfer.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `kubectl-hlf/cmd/ca/ca.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/ca/create.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/ca/delete.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/ca/enroll.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/ca/register.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/chaincode/approve.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/chaincode/calculatepackageid.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/chaincode/chaincode.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/chaincode/checkcommitreadiness.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/chaincode/commit.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/chaincode/getlatest.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/chaincode/install.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/chaincode/invoke.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/chaincode/query.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/chaincode/queryapproved.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/chaincode/querycommitted.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/chaincode/queryinstalled.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/addanchorpeer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/addorg.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/channel.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/create.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/delanchorpeer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/generate.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/inspect.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/join.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/signupdate.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/top.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/update.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/console/console.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/console/create.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/console/delete.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/console/update.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/externalchaincode/create.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/externalchaincode/delete.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/externalchaincode/externalchaincode.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/externalchaincode/sync.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/externalchaincode/update.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/fop/fop.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/helpers/channel.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/helpers/constants.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/helpers/helpers.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/helpers/hlf.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/helpers/mappers.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/helpers/marshall.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/inspect/inspect.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/networkconfig/create.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/networkconfig/delete.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/networkconfig/export.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/networkconfig/networkconfig.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/networkconfig/refresh.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/networkconfig/update.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/operatorapi/create.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/operatorapi/delete.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/operatorapi/operatorapi.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/operatorapi/update.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/operatorui/create.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/operatorui/delete.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/operatorui/operatorui.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/operatorui/update.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/ordnode/create.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/ordnode/delete.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/ordnode/join.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/ordnode/ordnode.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/ordnode/removechannel.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/ordnode/renew.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/ordnode/upgrade.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/org/inspect.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/org/org.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/peer/create.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/peer/delete.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/peer/peer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/peer/renew.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/peer/upgrade.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/utils/addUser.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/utils/utils.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fixtures/chaincodes/fabcar/external/fabcar.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `fixtures/chaincodes/fabcar/go/fabcar.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `kubectl-hlf/cmd/channel/consenter/add.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/consenter/consenter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/consenter/remove.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/consenter/replace.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/ordorg/add.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/ordorg/ordorg.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/channel/ordorg/remove.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/fop/export/ca.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/fop/export/export.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/fop/export/orderer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/fop/export/org.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/fop/export/peer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/fop/export/utils.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `kubectl-hlf/cmd/helpers/osnadmin/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `fixtures/chaincodes/fabcar/java/src/main/java/org/hyperledger/fabric/samples/fabcar/Car.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `fixtures/chaincodes/fabcar/java/src/main/java/org/hyperledger/fabric/samples/fabcar/CarQueryResult.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `fixtures/chaincodes/fabcar/java/src/main/java/org/hyperledger/fabric/samples/fabcar/FabCar.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `fixtures/chaincodes/fabcar/java/src/test/java/org/hyperledger/fabric/samples/fabcar/CarQueryResultTest.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `fixtures/chaincodes/fabcar/java/src/test/java/org/hyperledger/fabric/samples/fabcar/CarTest.java`: The first 7 lines do not contain the pattern(s): Copyright.
- `fixtures/chaincodes/fabcar/java/src/test/java/org/hyperledger/fabric/samples/fabcar/FabCarTest.java`: The first 7 lines do not contain the pattern(s): Copyright.

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

### ✅ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Found file (`MAINTAINERS.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/goreleaser-beta.yml`).

### ✅ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Found file (`CHANGELOG.md`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`controllers/tests`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!**/node_modules/**`).

### ✅ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Found file (`go.mod`).

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

