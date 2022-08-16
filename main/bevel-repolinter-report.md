# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 1 | 5 | 10 | 3 | 19 |

- [Fail](#user-content-fail)
  - [❌ `security-file-matches`](#user-content--security-file-matches)
- [Warning](#user-content-warning)
  - [⚠️ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
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

### ❌ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Did not find file matching the specified patterns. (`SECURITY.md`).


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Did not find a file matching the specified patterns. (`CHANGELOG.md`).

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `examples/supplychain-app/corda/express_nodeJS/api.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/corda/express_nodeJS/app.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/corda/express_nodeJS/config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/express_nodeJs/api.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/express_nodeJs/app.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/express_nodeJs/config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/quorum/express_nodeJS/app.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/quorum/express_nodeJS/config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/quorum/express_nodeJS/web3services.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/quorum/smartContracts/compile.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/quorum/smartContracts/deploy.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/quorum/smartContracts/truffle-config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/App.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/App.test.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/desktopStyles.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/mobileStyles.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/serviceWorker.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/setupProxy.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/besu/express_nodeJS/ABI/productABI.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/corda/express_nodeJS/controllers/container.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/corda/express_nodeJS/controllers/general.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/corda/express_nodeJS/controllers/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/corda/express_nodeJS/controllers/product.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/bootstrap-server.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/express_nodeJs/controllers/container.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/express_nodeJs/controllers/general.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/express_nodeJs/controllers/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/express_nodeJs/controllers/product.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/quorum/express_nodeJS/ABI/productABI.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/quorum/express_nodeJS/controllers/container.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/quorum/express_nodeJS/controllers/general.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/quorum/express_nodeJS/controllers/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/quorum/express_nodeJS/controllers/product.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/quorum/smartContracts/migrations/1_initial_migration.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/quorum/smartContracts/migrations/2_general_contract.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/quorum/smartContracts/test/GeneralContract.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/util/getTimezone.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/util/numberPadding.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/util/parseName.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/brunch-config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/brunch-config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/containers/desktop/ContainerDetails.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/containers/desktop/Dashboard.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/containers/desktop/ProductMap.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/containers/desktop/QrGen.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/containers/mobile/ContainerDetails.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/containers/mobile/CreateContainer.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/containers/mobile/DashboardQrScan.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/containers/mobile/LocationDetails.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/containers/mobile/PackageGood.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/containers/mobile/ProductDetails.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/containers/mobile/QrReader.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/supplychain-frontend/src/util/api/supplyChainRequests.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/initialize.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/initialize.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/scripts/geoCode.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/scripts/headersList.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/scripts/jwtProcess.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/scripts/processData.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/scripts/restCalls.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/scripts/geoCode.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/scripts/headersList.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/scripts/jwtProcess.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/scripts/processData.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/scripts/restCalls.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/components/DisplayBraid/DisplayBraid.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/components/Map/MyMap.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/components/Metrics/Metrics.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/components/Modal/Modal.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/components/Nav/Nav.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/components/Sidebar/Sidebar.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/components/Spinner/Spinner.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/components/Table/Table.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/containers/App/App.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/containers/Default/Default.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/containers/Login/Login.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/containers/Page/Page.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/components/DisplayBraid/DisplayBraid.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/components/Map/MyMap.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/components/Metrics/Metrics.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/components/Modal/Modal.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/components/Nav/Nav.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/components/Sidebar/Sidebar.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/components/Spinner/Spinner.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/components/Table/Table.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/containers/App/App.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/containers/Default/Default.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/containers/Login/Login.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/containers/Page/Page.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/containers/Pages/Braid/Braid.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/containers/Pages/Home/Home.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/doorman/website/app/containers/Pages/Swagger/Swagger.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/containers/Pages/Braid/Braid.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/containers/Pages/Home/Home.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `platforms/r3-corda/images/networkmap/website/app/containers/Pages/Swagger/Swagger.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/SupplyChainClient.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/User.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/logging.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/routes.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/server.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/controller/ContainerController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/controller/GeneralController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/controller/ProductController.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/controller/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/mixins/Validateable.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/models/Container.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/models/ContainerRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/models/Contents.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/models/ContentsRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/models/Product.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/models/ProductRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/models/ScanResponse.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/rest-server/src/models/UpdateRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/chaincode/common/Container.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/chaincode/common/ContainerRequest.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/chaincode/common/History.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/chaincode/common/Identity.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/chaincode/common/Product.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/chaincode/common/ProductRequest.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/chaincode/common/UpdateRequest.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/chaincode/supplychain/Common.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/chaincode/supplychain/Common_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/chaincode/supplychain/Container.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/chaincode/supplychain/Container_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/chaincode/supplychain/Product.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/chaincode/supplychain/Product_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/chaincode/supplychain/SupplyChain.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `examples/supplychain-app/fabric/chaincode_rest_server/chaincode/supplychain/cmd/main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.

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

### ✅ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Contains https://wiki.hyperledger.org/community/hyperledger-project-code-of-conduct (`CODE_OF_CONDUCT.md`).

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Contains license (`README.md`).

### ✅ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Found file (`MAINTAINERS.md`).

### ✅ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Found file (`CONTRIBUTING.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.circleci/config.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`examples/identity-app/tests`).

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

