# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 0 | 1 | 14 | 4 | 19 |

- [Warning](#user-content-warning)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [✅ `notice-file-exists`](#user-content--notice-file-exists)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `protoutil/fakes/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/configtx/mock/policy.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/configtx/mock/policy_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/deliver/mock/block_iterator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/deliver/mock/block_reader.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/deliver/mock/chain.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/deliver/mock/chain_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/deliver/mock/filtered_response_sender.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/deliver/mock/inspector.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/deliver/mock/policy_checker.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/deliver/mock/private_data_response_sender.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/deliver/mock/receiver.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/deliver/mock/response_sender.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/fabhttp/fakes/logger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/flogging/mock/observer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/flogging/mock/write_syncer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/grpclogging/fakes/echo_service.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/grpclogging/fakes/leveler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/grpcmetrics/fakes/echo_service.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/metrics/metricsfakes/counter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/metrics/metricsfakes/gauge.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/metrics/metricsfakes/histogram.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/metrics/metricsfakes/provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/fake/application_config_retriever.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/fake/context_registry.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/fake/launch_registry.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/fake/message_handler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/fake/query_response_builder.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/fake/registry.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/acl_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/application_capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/application_config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/ccstreamhandler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/cert_generator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/chaincode_stream.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/collection_store.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/connectionhandler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/container_router.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/history_query_executor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/invoker.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/ledger_getter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/lifecycle.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/peer_ledger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/policy.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/policy_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/resources.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/results_iterator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/runtime.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/transaction_registry.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/mock/tx_simulator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/container/mock/docker_builder.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/container/mock/external_builder.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/container/mock/instance.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/container/mock/package_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/deliverservice/fake/ledger_info.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/dispatcher/mock/protobuf.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/endorser/fake/channel_fetcher.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/endorser/fake/history_query_executor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/endorser/fake/id_deserializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/endorser/fake/identity.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/endorser/fake/prvt_data_distributor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/endorser/fake/query_executor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/endorser/fake/support.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/endorser/fake/tx_simulator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/mock/cc_event_listener.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/mock/cc_event_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/mock/custom_tx_processor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/mock/deployed_ccinfo_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/mock/health_check_registry.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/mock/membership_info_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/mock/query_executor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/mock/state_listener.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/mock/tx_simulator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/middleware/fakes/http_handler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/operations/fakes/healthchecker.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/operations/fakes/logger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/peer/mock/collection_policy_checker.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/peer/mock/identity_deserializer_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/peer/mock/peer_ledger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/mock/chaincode.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/mock/chaincode_stream_handler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/mock/selfdescribingsyscc.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/common/export_test.go`: The first 7 lines do not contain the pattern(s): Copyright.
- `common/flogging/httpadmin/fakes/logging.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/ledger/testutil/fakes/signing_identity.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/extcc/mock/ccstreamhandler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/aclprovider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/application_capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/application_config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/application_org_config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/chaincode_builder.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/chaincode_info_cache.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/chaincode_info_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/chaincode_launcher.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/chaincode_store.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/chaincode_stub.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/channel_config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/channel_config_source.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/channel_policy_reference_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/convertible_policy.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/inconvertible_policy.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/install_listener.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/installed_chaincodes_lister.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/legacy_ccinfo.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/legacy_lifecycle.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/legacy_metadata_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/metadata_handler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/metadata_update_listener.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/msp.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/msp_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/package_parser.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/policy_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/query_executor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/queryexecutor_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/results_iterator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/rw_state.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/scc_functions.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/state_iterator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/lifecycle/mock/validation_state.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/persistence/mock/ioreadwriter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/persistence/mock/legacy_cc_package_locator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/persistence/mock/metadata_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/persistence/mock/osfileinfo.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/platforms/mock/package_writer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/platforms/mock/platform.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/common/privdata/mock/chaincode_info_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/common/privdata/mock/identity_deserializer_factory.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/common/privdata/mock/query_executor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/common/privdata/mock/query_executor_factory.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/container/dockercontroller/mock/dockerclient.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/container/dockercontroller/mock/platform_builder.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/mock/chaincode_info_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/pvtdatapolicy/mock/coll_info_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/snapshotgrpc/mock/acl_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/snapshotgrpc/mock/ledger_getter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/application.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/application_capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/cc_package.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/chaincode_builder.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/chaincode_stub.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/fs_support.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/query_executor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/results_iterator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/state_query_iterator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/system_chaincode_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/configtxgen/encoder/fakes/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/chaincode/mock/deliver.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/chaincode/mock/deliver_client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/chaincode/mock/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/channel/mock/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/common/mock/deliverservice.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/common/mock/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/node/mock/get_ledger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/node/mock/peer_ledger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/packaging/mock/platform.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/snapshot/mock/signer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/snapshot/mock/snapshot_client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/blockcutter/mock/config_fetcher.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/blockcutter/mock/metrics_histogram.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/blockcutter/mock/metrics_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/blockcutter/mock/orderer_config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/broadcast/mock/ab_server.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/broadcast/mock/channel_support.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/broadcast/mock/channel_support_registrar.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/broadcast/mock/metrics_counter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/broadcast/mock/metrics_histogram.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/broadcast/mock/metrics_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/ledger/blockledger/fileledger/mock/block_store_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/ledger/blockledger/fileledger/mock/file_ledger_block_store.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/tests/fakes/signer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/lifecycle/chaincode/mock/broadcast_client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/lifecycle/chaincode/mock/deliver.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/lifecycle/chaincode/mock/endorser_client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/lifecycle/chaincode/mock/peer_deliver_client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/lifecycle/chaincode/mock/platform_registry.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/lifecycle/chaincode/mock/reader.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/lifecycle/chaincode/mock/signer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/lifecycle/chaincode/mock/writer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/pkg/peer/blocksprovider/fake/ab_deliver_client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/pkg/peer/blocksprovider/fake/block_verifier.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/pkg/peer/blocksprovider/fake/deliver_streamer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/pkg/peer/blocksprovider/fake/dialer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/pkg/peer/blocksprovider/fake/gossip_service_adapter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/pkg/peer/blocksprovider/fake/ledger_info.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/pkg/peer/blocksprovider/fake/orderer_connection_source.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/pkg/peer/blocksprovider/fake/signer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/pkg/peer/blocksprovider/fake/sleeper.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/privacyenabledstate/mock/channelinfo_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/privacyenabledstate/mock/snapshot_pvtdatahashes_consumer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/queryutil/mock/query_executer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/statedb/mock/namespace_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/statedb/mock/results_iterator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/statedb/mock/versioned_db.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/validation/mock/postOrderSimulatorProvider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/validation/mock/processor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/validation/mock/txsim.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/chaincode/platforms/java/testdata/gradle/src/main/java/example/ExampleCC.java`: The first 7 lines do not contain the pattern(s): Copyright, License.

</details>

## Passed <a href="#user-content-passed" id="passed">#</a>

<details>
<summary>Click to see rules</summary>

### ✅ `apache-license-file` <a href="#user-content--apache-license-file" id="-apache-license-file">#</a>

Contains Apache License.*Version 2.0 (`LICENSE`).

### ✅ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Contains https://wiki.hyperledger.org/community/hyperledger-project-code-of-conduct (`CODE_OF_CONDUCT.md`).

### ✅ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Contains https://wiki.hyperledger.org/display/.*(SEC|HYP)/Defect[.+]Response (`SECURITY.md`).

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Contains license (`README.md`).

### ✅ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Found file (`MAINTAINERS.md`).

### ✅ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Found file (`CONTRIBUTING.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`ci/azure-pipelines.yml`).

### ✅ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Found file (`CHANGELOG.md`).

### ✅ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Found file (`NOTICE`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`discovery/test`).

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

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=javascript"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=ruby"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=java"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

