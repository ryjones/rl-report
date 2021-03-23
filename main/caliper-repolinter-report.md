# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 2 | 2 | 11 | 3 | 18 |

- [Fail](#user-content-fail)
  - [❌ `security-file-matches`](#user-content--security-file-matches)
  - [❌ `integrates-with-ci`](#user-content--integrates-with-ci)
- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [✅ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Doesn't contain https://wiki.hyperledger.org/display/SEC/Defect+Response (`SECURITY.md`).

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

- `packages/caliper-cli/caliper.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-cli/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-ethereum/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fisco-bcos/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-gui-server/app.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/publish.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-cli/lib/bindCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-cli/lib/launchCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-cli/lib/unbindCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-ethereum/lib/connectorFactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-ethereum/lib/ethereum-connector.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/FabricConnectorContext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/FabricConnectorFactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/configValidator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/fabricNetwork.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/FabricConnectorFactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/configValidator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/fabricNetwork.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fisco-bcos/lib/channelPromise.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fisco-bcos/lib/common.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fisco-bcos/lib/connectorFactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fisco-bcos/lib/fiscoBcos-connector.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fisco-bcos/lib/fiscoBcosApi.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fisco-bcos/lib/generateRawTransactions.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fisco-bcos/lib/installSmartContract.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fisco-bcos/lib/invokeSmartContract.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fisco-bcos/lib/sendRawTransactions.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-gui-dashboard/src/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-gui-dashboard/src/routes.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-gui-server/src/gui-caliper-flow.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-gui-server/test/random-gen-test.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/lib/dockerCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/lib/npmCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/lib/verdaccio.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/lib/version.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/besu_tests/open.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/besu_tests/query.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/besu_tests/store.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/besu_tests/transfer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/ethereum_tests/open.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/ethereum_tests/query.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/ethereum_tests/transfer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/fabric_docker_distributed_tests/init.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/fabric_docker_distributed_tests/query.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/fabric_docker_local_tests/init.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/fabric_docker_local_tests/query.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/fabric_tests/init.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/fabric_tests/initByChannel.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/fabric_tests/query.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/fabric_tests/queryByChannel.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/fisco-bcos_tests/get.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/fisco-bcos_tests/set.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-cli/lib/launch/launchManagerCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-cli/lib/launch/launchWorkerCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-cli/lib/lib/bindCommon.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/caliper-engine.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/caliper-worker.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/worker-message-handler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-configuration/ConnectionProfileDefinition.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-configuration/ConnectorConfiguration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-configuration/ConnectorConfigurationFactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/identity-management/ExportedIdentity.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/identity-management/IWalletFacade.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/identity-management/IWalletFacadeFactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/identity-management/IdentityManager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/identity-management/IdentityManagerFactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/connector-configuration/ConnectionProfileDefinition.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/connector-configuration/ConnectorConfiguration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/connector-configuration/ConnectorConfigurationFactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/identity-management/IdentityManager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/utils/GenerateConfiguration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/utils/GenerateWallet.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fisco-bcos/lib/web3lib/config.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fisco-bcos/lib/web3lib/transactionObject.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fisco-bcos/lib/web3lib/utils.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fisco-bcos/lib/web3lib/web3sync.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-gui-dashboard/src/utilities/GuiUtils.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-gui-server/src/api/api1.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-gui-server/src/api/api2.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-gui-server/test/temp/app-test.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-gui-server/test/temp/httpVerbs.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/lib/impl/docker.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/lib/impl/npm.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/lib/utils/cmdutils.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/lib/verdaccio/startCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/lib/verdaccio/stopCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/lib/version/checkCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/lib/version/fixCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-caliper/generators/app/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-caliper/generators/benchmark/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-caliper/test/benchmark/config.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-caliper/test/benchmark/workload.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-cli/lib/launch/lib/launchManager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-cli/lib/launch/lib/launchWorker.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/config/Config.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/config/config-util.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/core/connector-base.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/core/connector-interface.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/core/transaction-statistics-collector.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/core/transaction-status.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messages/assignIdMessage.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messages/assignedMessage.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messages/connectedMessage.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messages/exitMessage.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messages/initializeMessage.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messages/message.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messages/parse.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messages/prepareMessage.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messages/preparedMessage.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messages/readyMessage.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messages/registerMessage.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messages/testMessage.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messages/testResultMessage.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messages/txResetMessage.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messages/txUpdateMessage.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messengers/messenger-interface.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/prometheus/prometheus-query-client.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/prometheus/prometheus-query-helper.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/utils/benchmark-validator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/utils/caliper-utils.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/utils/constants.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/utils/log-formats.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/utils/logging-util.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/utils/version.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/charts/chart-builder.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/monitors/monitor-docker.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/monitors/monitor-interface.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/monitors/monitor-process.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/monitors/monitor-prometheus.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/monitors/monitor-utilities.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/orchestrators/monitor-orchestrator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/orchestrators/round-orchestrator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/orchestrators/worker-orchestrator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/report/report-builder.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/report/report.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/test-observers/default-observer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/test-observers/null-observer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/test-observers/observer-interface.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/manager/test-observers/test-observer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/rate-control/compositeRate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/rate-control/fixedFeedbackRate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/rate-control/fixedLoad.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/rate-control/fixedRate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/rate-control/linearRate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/rate-control/maxRate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/rate-control/noRate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/rate-control/rateControl.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/rate-control/rateInterface.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/rate-control/recordRate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/rate-control/replayRate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/tx-observers/internal-tx-observer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/tx-observers/logging-tx-observer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/tx-observers/prometheus-push-tx-observer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/tx-observers/prometheus-tx-observer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/tx-observers/tx-observer-dispatch.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/tx-observers/tx-observer-interface.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/workload/workloadModuleBase.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/worker/workload/workloadModuleInterface.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/common/core/transaction-statisitcs-collector.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/common/prometheus/prometheus-query-helper.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/common/utils/caliper-utils.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/manager/charts/chart-builder.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/manager/monitor/monitor-utilities.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/manager/monitors/monitor-prometheus.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/manager/orchestrators/worker-orchestrator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/manager/report/report.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/worker/rate-control/fixedFeedbackRate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/worker/rate-control/fixedLoad.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/worker/rate-control/fixedRate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/worker/rate-control/linearRate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/worker/rate-control/maxRate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/worker/rate-control/noRate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/worker/tx-observers/prometheus-push-tx-observer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/test/worker/tx-observers/prometheus-tx-observer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-versions/v1/ClientCreator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-versions/v1/FabricChaincodeOperations.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-versions/v1/FabricChannelOperations.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-versions/v1/FabricGateway.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-versions/v1/FabricNonGateway.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-versions/v1/WalletFacade.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-versions/v1/WalletFacadeFactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-versions/v1/fabric-gateway.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-versions/v1/fabric.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-versions/v2/FabricGateway.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-versions/v2/WalletFacade.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-versions/v2/WalletFacadeFactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-versions/v2/fabric-gateway.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/lib/connector-versions/v2/registrarHelper.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/connector-versions/v1/ClientCreator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/connector-versions/v1/ClientStubs.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/connector-versions/v1/FabricGateway-1.4.4.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/connector-versions/v1/FabricGateway.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/connector-versions/v1/FabricNonGateway.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/connector-versions/v1/V1GatewayStubs.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/connector-versions/v1/WalletFacade.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/connector-versions/v2/FabricGateway.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/connector-versions/v2/V2GatewayStubs.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-fabric/test/connector-versions/v2/WalletFacade.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/lib/verdaccio/impl/start.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/lib/verdaccio/impl/stop.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/lib/version/impl/check.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-publish/lib/version/impl/fix.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-caliper/generators/benchmark/templates/workload.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messengers/mqtt/factory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messengers/mqtt/mqtt-messenger.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messengers/process/factory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-core/lib/common/messengers/process/process-messenger.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/fabric_docker_distributed_tests/src/marbles/node/marbles.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/fabric_docker_local_tests/src/marbles/node/marbles.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/fabric_tests/phase3/src/marbles/node/marbles.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/caliper-tests-integration/generator_tests/fabric/src/marbles/node/marbles.js`: The first 5 lines do not contain the pattern(s): Copyright.

</details>

## Passed <a href="#user-content-passed" id="passed">#</a>

<details>
<summary>Click to see rules</summary>

### ✅ `apache-license-file` <a href="#user-content--apache-license-file" id="-apache-license-file">#</a>

All files passed this test.

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

### ✅ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Found file (`CHANGELOG.md`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`packages/caliper-core/test`).

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

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=ruby"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=java"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

