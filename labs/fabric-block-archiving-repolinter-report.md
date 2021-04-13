# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 0 | 3 | 12 | 4 | 19 |

- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [✅ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `core/archiver/archiver.go`: The first 7 lines do not contain the pattern(s): License.
- `core/archiver/archiver_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
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
- `common/flogging/mock/observer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/flogging/mock/write_syncer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/grpclogging/fakes/echo_service.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/grpclogging/fakes/leveler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/grpcmetrics/fakes/echo_service.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/ledger/blockarchive/blockarchive.go`: The first 7 lines do not contain the pattern(s): License.
- `common/metrics/metricsfakes/counter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/metrics/metricsfakes/gauge.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/metrics/metricsfakes/histogram.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/metrics/metricsfakes/provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/policies/mocks/identity.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/policies/mocks/identity_deserializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/aclmgmt/mocks/defaultaclprovider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/aclmgmt/mocks/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/cclifecycle/mocks/enumerator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/cclifecycle/mocks/metadata_change_listener.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/cclifecycle/mocks/query.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/cclifecycle/mocks/query_creator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
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
- `core/endorser/mocks/channel_state_retriever.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/endorser/mocks/plugin_mapper.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/endorser/mocks/query_creator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/endorser/mocks/transient_store_retriever.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/library/race_test.go`: The first 7 lines do not contain the pattern(s): License.
- `core/ledger/kvledger/kv_ledger_archive.go`: The first 7 lines do not contain the pattern(s): License.
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
- `core/policy/mocks/channel_policy_manager_getter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/policy/mocks/channel_policy_reference_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/policy/mocks/identity.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/policy/mocks/identity_deserializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/policy/mocks/policy.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/policy/mocks/policy_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/policy/mocks/signature_policy_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/mock/chaincode.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/mock/chaincode_stream_handler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/mock/selfdescribingsyscc.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/cmd/mocks/channel_response.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/cmd/mocks/command_registrar.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/cmd/mocks/local_response.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/cmd/mocks/response_parser.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/cmd/mocks/service_response.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/cmd/mocks/stub.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/support/mocks/channel_config_getter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/support/mocks/channel_policy_manager_getter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/support/mocks/config_block_getter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/support/mocks/configtx_validator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/support/mocks/evaluator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/support/mocks/gossip_support.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/support/mocks/identity.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/support/mocks/msp_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/support/mocks/policy_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/support/mocks/resources.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/support/mocks/verifier.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `gossip/api/mocks/security_advisor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `gossip/privdata/mocks/app_capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `gossip/privdata/mocks/capability_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `gossip/privdata/mocks/collection_store.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `gossip/privdata/mocks/committer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `gossip/privdata/mocks/config_history_retriever.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `gossip/privdata/mocks/missing_pvt_data_tracker.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `gossip/privdata/mocks/reconciliation_fetcher.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `gossip/privdata/mocks/rw_set_scanner.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `gossip/privdata/mocks/sleeper.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `gossip/service/mocks/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/mocks/mock_consenter_support.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `bccsp/idemix/handlers/mock/big.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `bccsp/idemix/handlers/mock/credential.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `bccsp/idemix/handlers/mock/credrequest.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `bccsp/idemix/handlers/mock/ecp.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `bccsp/idemix/handlers/mock/issuer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `bccsp/idemix/handlers/mock/issuer_public_key.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `bccsp/idemix/handlers/mock/issuer_secret_key.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `bccsp/idemix/handlers/mock/nymsignature_scheme.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `bccsp/idemix/handlers/mock/revocation.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `bccsp/idemix/handlers/mock/signature_scheme.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `bccsp/idemix/handlers/mock/user.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/flogging/httpadmin/fakes/logging.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/ledger/blkstorage/fsblkstorage/blockfile_archiver.go`: The first 7 lines do not contain the pattern(s): License.
- `common/ledger/blkstorage/fsblkstorage/blockfile_archiver_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/ledger/blkstorage/fsblkstorage/blocks_archived_itr.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `common/ledger/blkstorage/fsblkstorage/fs_blockstore_archive.go`: The first 7 lines do not contain the pattern(s): License.
- `common/ledger/blkstorage/fsblkstorage/fs_blockstore_archive_test.go`: The first 7 lines do not contain the pattern(s): License.
- `common/ledger/blockledger/mocks/read_writer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
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
- `core/committer/txvalidator/mocks/application_capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/mocks/capability_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/mocks/query_executor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/mocks/validator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/common/privdata/mock/chaincode_info_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/common/privdata/mock/identity_deserializer_factory.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/common/privdata/mock/query_executor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/common/privdata/mock/query_executor_factory.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/container/dockercontroller/mock/dockerclient.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/container/dockercontroller/mock/platform_builder.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/pvtdatapolicy/mock/coll_info_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/cscc/mocks/acl_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/cscc/mocks/chaincode_stub.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/cscc/mocks/channel_policy_manager_getter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/cscc/mocks/policy_checker.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/cscc/mocks/store_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/application.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/application_capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/cc_package.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/chaincode_builder.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/chaincode_stub.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/fs_support.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/query_executor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/state_query_iterator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/scc/lscc/mock/system_chaincode_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `discovery/support/gossip/mocks/gossip.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/configtxgen/encoder/fakes/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/chaincode/mock/deliver.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/chaincode/mock/deliver_client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/chaincode/mock/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/channel/mock/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/common/mock/deliverservice.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/common/mock/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/gossip/mocks/policy_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/gossip/mocks/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/node/mock/get_ledger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/node/mock/peer_ledger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `internal/peer/packaging/mock/platform.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
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
- `orderer/common/cluster/mocks/block_verifier.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/chain_puller.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/channel_lister.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/block_retriever.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/cluster_client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/communicator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/dispatcher.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/handler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/ledger_factory.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/ledger_writer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/metrics_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/policy.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/policy_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/secure_dialer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/step_client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/step_stream.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/verifier_factory.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/cluster/mocks/verifier_retriever.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/msgprocessor/mocks/channel_capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/msgprocessor/mocks/channel_config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/msgprocessor/mocks/config_resources.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/msgprocessor/mocks/configtx_validator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/msgprocessor/mocks/metadata_validator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/msgprocessor/mocks/orderer_capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/msgprocessor/mocks/orderer_config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/msgprocessor/mocks/policy.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/msgprocessor/mocks/policy_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/msgprocessor/mocks/sig_filter_support.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/msgprocessor/mocks/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/multichannel/mocks/channel_capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/multichannel/mocks/channel_config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/multichannel/mocks/configtx_validator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/multichannel/mocks/orderer_capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/multichannel/mocks/orderer_config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/multichannel/mocks/policy.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/multichannel/mocks/policy_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/multichannel/mocks/resources.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/multichannel/mocks/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/server/mocks/chain_replicator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/server/mocks/factory.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/server/mocks/health_checker.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/common/server/mocks/signer_serializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/etcdraft/mocks/chain_getter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/etcdraft/mocks/configurator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/etcdraft/mocks/inactive_chain_registry.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/etcdraft/mocks/message_receiver.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/etcdraft/mocks/mock_blockpuller.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/etcdraft/mocks/mock_rpc.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/etcdraft/mocks/orderer_capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/etcdraft/mocks/orderer_config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/etcdraft/mocks/receiver_getter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/kafka/mock/channel_capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/kafka/mock/channel_config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/kafka/mock/health_checker.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/kafka/mock/metrics_gauge.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/kafka/mock/metrics_histogram.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/kafka/mock/metrics_meter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/kafka/mock/metrics_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/kafka/mock/metrics_registry.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/kafka/mock/orderer_capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/kafka/mock/orderer_config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/kafka/mock/sync_producer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `orderer/consensus/solo/mocks/orderer_config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v14/mocks/capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v14/mocks/identity_deserializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v14/mocks/mapper.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v14/mocks/plugin.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v14/mocks/plugin_factory.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v14/mocks/query_executor_creator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/mocks/channel_policy_manager_getter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/mocks/channel_resources.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/mocks/collection_resources.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/mocks/dispatcher.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/mocks/ledger_resources.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/mocks/policy_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/mocks/query_executor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/common/validation/statebased/mocks/collection_resources.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/common/validation/statebased/mocks/key_level_validation_parameter_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/mocks/transaction_validator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
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
- `core/committer/txvalidator/v20/plugindispatcher/mocks/capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/plugindispatcher/mocks/channel_policy_manager_getter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/plugindispatcher/mocks/identity_deserializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/plugindispatcher/mocks/lifecycle_resources.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/plugindispatcher/mocks/mapper.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/plugindispatcher/mocks/plugin.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/plugindispatcher/mocks/plugin_factory.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/plugindispatcher/mocks/policy_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/plugindispatcher/mocks/query_executor_creator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/committer/txvalidator/v20/valinforetriever/mocks/lifecycle_resources.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v12/mocks/capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v12/mocks/identity_deserializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v12/mocks/policy_evaluator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v12/mocks/state.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v12/mocks/state_fetcher.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v13/mocks/capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v13/mocks/identity_deserializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v13/mocks/policy_evaluator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v13/mocks/state.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v13/mocks/state_based_validator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v13/mocks/state_fetcher.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v20/mocks/capabilities.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v20/mocks/collection_resources.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v20/mocks/identity_deserializer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v20/mocks/state.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v20/mocks/state_based_validator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/handlers/validation/builtin/v20/mocks/state_fetcher.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/queryutil/mock/query_executer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/statedb/mock/results_iterator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/statedb/mock/versioned_db.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/txmgr/mock/tx_mgr.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/validator/valimpl/mock/processor.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/validator/valimpl/mock/txmgr.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/ledger/kvledger/txmgmt/validator/valimpl/mock/txsim.go`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`go.mod`).

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

### ✅ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Found file (`CHANGELOG.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`ci/azure-pipelines.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`test-pyramid.png`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!**/node_modules/**`).

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

