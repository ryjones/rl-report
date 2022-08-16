# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 3 | 3 | 9 | 4 | 19 |

- [Fail](#user-content-fail)
  - [❌ `security-file-matches`](#user-content--security-file-matches)
  - [❌ `readme-references-license`](#user-content--readme-references-license)
  - [❌ `contributing-file-exists`](#user-content--contributing-file-exists)
- [Warning](#user-content-warning)
  - [⚠️ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Did not find file matching the specified patterns. (`SECURITY.md`).

### ❌ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Doesn't contain license (`README.md`).

### ❌ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Did not find a file matching the specified patterns. (`CONTRIBUTING.md`).


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Did not find a file matching the specified patterns. (`CHANGELOG.md`).

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `src/main/java/hlf/java/rest/client/FabricClientBootstrap.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/config/AppIntegrationConfig.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/config/FabricProperties.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/config/GatewayConfig.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/config/KafkaConsumerConfig.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/config/KafkaProducerConfig.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/config/KafkaProperties.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/config/SecurityConfig.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/config/ServerProperties.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/config/SwaggerConfig.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/controller/ChaincodeOperationsController.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/controller/ChannelOperationController.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/controller/ConfigHandlerController.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/controller/FabricClientController.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/controller/FabricOperationsController.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/exception/AuthenticationFailureException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/exception/BaseException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/exception/ChannelOperationException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/exception/ErrorCode.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/exception/ErrorConstants.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/exception/FabricTransactionException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/exception/GlobalExceptionHandler.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/exception/NotFoundException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/exception/ServiceException.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/listener/BlockEventListener.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/listener/ChaincodeEventListener.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/listener/DynamicKafkaListener.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/listener/FabricEventListener.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/listener/TransactionConsumer.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/AnchorPeerDTO.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/BlockEventPrivateDataWriteSet.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/BlockEventWriteSet.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/ChaincodeEventCapture.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/ChaincodeOperations.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/ChaincodeOperationsType.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/ChannelOperationRequest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/ChannelOperationType.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/ClientResponseModel.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/CommitChannelParamsDTO.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/EventAPIResponseModel.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/EventStructure.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/EventType.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/MSPDTO.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/NewOrgParamsDTO.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/Orderer.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/model/Peer.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/security/HeaderAuthenticationFilter.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/AddOrgToChannelWriteSetBuilder.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/ChaincodeOperationsService.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/ChannelConfigDeserialization.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/ChannelService.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/ConfigHandlerService.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/EventPublishService.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/HFClientWrapper.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/NetworkStatus.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/TransactionFulfillment.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/util/FabricClientConstants.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/util/FabricEventParseUtil.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/util/SerializationUtil.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/IT/ChannelIT.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/IT/SmartContractIT.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/controller/FabricClientControllerTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/controller/FabricOperationsControllerTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/exception/GlobalExceptionHandlerTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/integration/ConfigHandlerControllerIntegrationTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/util/EnrollAdmin.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/util/RegisterUser.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/util/TestingUtlitlies.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/impl/AddOrgToChannelWriteSetBuilderImpl.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/impl/ChaincodeOperationsServiceImpl.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/impl/ChannelConfigDeserializationImpl.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/impl/ChannelServiceImpl.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/impl/ConfigHandlerServiceImpl.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/impl/EventPublishServiceImpl.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/impl/HFClientWrapperImpl.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/impl/NetworkStatusImpl.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/main/java/hlf/java/rest/client/service/impl/TransactionFulfillmentImpl.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/controller/e2e/ConsumeEventFromMultipleKafkaHosts.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/controller/e2e/ConsumeFromEventKafka.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/controller/e2e/SendToIntgKafka.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/service/impl/NetworkStatusImplTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/service/impl/TransactionFulfillmentImplTest.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/chaincode/src/main/java/org/example/MyAsset.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `src/test/java/hlf/java/rest/client/chaincode/src/main/java/org/example/MyAssetContract.java`: The first 7 lines do not contain the pattern(s): Copyright, License.

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

### ✅ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Found file (`MAINTAINERS.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/pull_request.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`src/test`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!**/node_modules/**`).

### ✅ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Found file (`pom.xml`).

### ✅ `license-detectable-by-licensee` <a href="#user-content--license-detectable-by-licensee" id="-license-detectable-by-licensee">#</a>

Licensee identified the license for project: Apache-2.0.

</details>

## Ignored <a href="#user-content-ignored" id="ignored">#</a>

<details>
<summary>Click to see rules</summary>

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=javascript"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=go"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=ruby"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

