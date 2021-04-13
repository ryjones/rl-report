# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 4 | 3 | 9 | 3 | 19 |

- [Fail](#user-content-fail)
  - [❌ `apache-license-file`](#user-content--apache-license-file)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `readme-file-exists`](#user-content--readme-file-exists)
  - [❌ `contributing-file-exists`](#user-content--contributing-file-exists)
- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `apache-license-file` <a href="#user-content--apache-license-file" id="-apache-license-file">#</a>

Doesn't contain Apache License.*Version 2.0 (`LICENSE.md`).

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Did not find file matching the specified patterns. (`CODE_OF_CONDUCT*`).

### ❌ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `README.md`
- `README`

### ❌ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Did not find a file matching the specified patterns. (`CONTRIBUTING.md`).


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `js/proto/acm_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/balance_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/bcm_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/crypto_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/dump_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/encoding_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/errors_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/exec_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/keys_grpc_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/keys_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/names_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/payload_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/permission_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/registry_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/rpc_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/rpcdump_grpc_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/rpcdump_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/rpcevents_grpc_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/rpcevents_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/rpcquery_grpc_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/rpcquery_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/rpctransact_grpc_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/rpctransact_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/spec_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/storage_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/txs_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/validator_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/example/basic-app/app.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `docs/example/basic-app-website/app.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/gogoproto/gogo_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/test/eth/truffle-config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/google/protobuf/descriptor_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/google/protobuf/timestamp_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/abci/types_grpc_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/abci/types_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/blockchain/types_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/consensus/types_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/consensus/wal_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/crypto/keys_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/crypto/proof_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/mempool/types_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/p2p/conn_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/p2p/pex_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/p2p/types_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/privval/types_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/state/types_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/statesync/types_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/store/types_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/types/block_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/types/canonical_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/types/events_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/types/evidence_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/types/params_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/types/types_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/types/validator_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/version/types_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/test/eth/migrations/1614708961_deploy_event_emitter.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/test/eth/migrations/1_initial_migration.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/test/eth/test/event-emitter.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/libs/bits/types_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/rpc/grpc/types_grpc_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `js/proto/tendermint/rpc/grpc/types_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `burrow.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/acm.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/bytecode.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/bytecode_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `bcm/block.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `bcm/block_store.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `bcm/blockchain_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `binary/bytes.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `binary/bytes_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `binary/integer_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `binary/word160.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `binary/word160_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `binary/word256_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `config/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `config/config_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/consensus.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `core/processes.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/run_deploy.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `dump/dump.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `dump/dump_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `dump/load.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `dump/load_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `dump/mock.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `dump/mock_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `dump/pipe.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `dump/sink.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `dump/source.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `dump/source_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `crypto/address.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `crypto/address_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `crypto/crypto.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `crypto/crypto_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `crypto/doc.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `crypto/hash.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `crypto/private_key.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `crypto/public_key.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `crypto/public_key_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `crypto/signature.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `crypto/tendermint.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `encoding/ethereum.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `encoding/ethereum_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `encoding/grpc.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `encoding/protobuf.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `encoding/protobuf_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/convention.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/emitter_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/accounts.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/simulated_call.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/simulated_call_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/version.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/capture.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/capture_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/replay.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/replay_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/revert_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/spin_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `genesis/deterministic_genesis.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `genesis/genesis_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `keys/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `keys/core.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `keys/filesystem_key_store.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `keys/key.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `keys/key_store.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `keys/memory_key_store.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `keys/server.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `permission/account_permissions.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `permission/base_permissions.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `permission/base_permissions_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `permission/perm_flag.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `permission/perm_flag_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `permission/util_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `process/process.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `project/history.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `project/history_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/grpc.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/test.sol.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `storage/forest.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `storage/forest_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `storage/key_format.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `storage/key_format_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `storage/key_value_store.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `storage/key_value_store_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `storage/prefix.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `storage/prefix_db.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `storage/prefix_db_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `storage/prefix_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `storage/rwtree.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `storage/rwtree_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `storage/sort_order.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `storage/tree.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `storage/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `sync/ring_mutex.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `sync/ring_mutex_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `testutil/dir.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/envelope.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/ethereum_tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/json_codec.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/json_codec_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/protobuf_codec.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/protobuf_codec_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `util/debug.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `util/debug_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/acmstate/dump_state.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/acmstate/memory_state.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/acmstate/metadata_cache.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/acmstate/state.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/acmstate/state_cache_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/balance/balance.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/balance/balance_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/balance/type.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/validator/bucket.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/validator/bucket_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/validator/cache.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/validator/ring.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/validator/ring_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/validator/set.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/validator/set_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/validator/validator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/validator/validators.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `acm/validator/validators_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/main_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `config/deployment/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `config/source/source.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `config/source/source_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/abci/app.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/abci/execute_tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/abci/execute_tx_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/abci/peers_filter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/abci/peers_filter_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/abci/process.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/tendermint/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/tendermint/config_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/tendermint/logger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/tendermint/node_view.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/tendermint/priv_validator_memory.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/tendermint/sign_info.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/tendermint/tendermint.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/tendermint/tendermint_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/compile/compilers.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/compile/compilers_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/def/client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/def/client_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/def/deploy.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/def/deploy_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/def/job.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/def/job_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/def/jobs.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/def/jobs_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/def/playbook.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/jobs/job_manager.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/jobs/jobs_contracts.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/jobs/jobs_contracts_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/jobs/jobs_governance.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/jobs/jobs_proposal.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/jobs/jobs_state.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/jobs/jobs_test_jobs.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/jobs/jobs_transact.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/jobs/jobs_util.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/jobs/writers.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/keys/keys.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/keys/keys_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/loader/load_package.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/loader/load_package_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/proposals/proposals.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/util/chains_info.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/util/variables.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `encoding/rlp/rlp.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `encoding/rlp/rlp_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `encoding/web3hex/decoder.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `encoding/web3hex/decoder_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `encoding/web3hex/encoder.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `encoding/web3hex/encoder_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/pubsub/example_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/pubsub/pubsub.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/pubsub/pubsub_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/query/builder.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/query/builder_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/query/empty.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/query/empty_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/query/expression.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/query/expression_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/query/parser_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/query/query.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/query/query.peg.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/query/query_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/query/tags.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `event/query/tags_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/contexts/bond_context.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/contexts/bond_context_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/contexts/call_context.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/contexts/governance_context.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/contexts/identify_context.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/contexts/name_context.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/contexts/name_context_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/contexts/permissions_context.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/contexts/permissions_context_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/contexts/proposal_context.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/contexts/send_context.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/contexts/send_context_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/contexts/shared.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/contexts/unbond_context.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/defaults/options.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/engine/account.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/engine/account_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/engine/accounts.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/engine/blockchain.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/engine/call.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/engine/call_frame.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/engine/callable.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/engine/dispatcher.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/engine/dispatcher_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/engine/memory.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/engine/memory_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/engine/natives.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/engine/options.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/engine/state.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/errors/code.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/errors/code_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/errors/codes.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/errors/errors.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/errors/errors_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/errors/exception.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/errors/maybe.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/errors/native.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/errors/vm.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/evm/code.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/evm/code_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/evm/contract.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/evm/stack_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/exec/block_execution.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/exec/block_execution_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/exec/call_event.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/exec/codec.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/exec/event.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/exec/event_sink.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/exec/event_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/exec/events.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/exec/govern_account_event.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/exec/header.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/exec/stream_event.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/exec/stream_event_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/exec/tx_execution.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/names/names_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/native/function.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/native/native.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/native/native_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/native/permissions.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/native/precompiles.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/native/state.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/proposal/proposal.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/registry/registry_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/solidity/abi_tester.sol.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/solidity/big_mod.sol.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/solidity/delgate_proxy.sol.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/solidity/ecrecover.sol.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/solidity/event_emitter.sol.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/solidity/evm.sol.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/solidity/ewasm.solang.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/solidity/revert.sol.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/solidity/strange_loop.sol.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/solidity/zero_reset.sol.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/state/abi.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/state/accounts.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/state/dump.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/state/events.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/state/events_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/state/names.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/state/proposals.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/state/registry.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/state/validators.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/state/validators_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/state/version.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/vms/vms.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/wasm/contract.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/wasm/storage_test.solang.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/wasm/wasm.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/wasm/wasm_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/storage/cache_db.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/storage/cache_db_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/storage/channel_iterator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/storage/channel_iterator_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/storage/kvcache.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/storage/kvcache_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/storage/multi_iterator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/storage/multi_iterator_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/storage/unique_iterator.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/storage/unique_iterator_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `forensics/storage/util_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `genesis/spec/genesis_spec.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `genesis/spec/genesis_spec_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `genesis/spec/presets.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `genesis/spec/presets_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `genesis/spec/template_account.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/core/kernel_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/governance/bonding_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/governance/governance_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/governance/helpers.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/governance/identify_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/keys/keys_server_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/rpcquery/query_server_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/rpctest/helpers.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/rpctest/tx_expecter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/rpctransact/call_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/rpctransact/name_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `integration/rpctransact/send_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `keys/common/paths.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/errors/multiple_errors.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/logconfig/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/logconfig/config_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/logconfig/filter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/logconfig/filter_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/logconfig/format.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/logconfig/sinks.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/logconfig/sinks_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/logconfig/sort.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/loggers/capture_logger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/loggers/capture_logger_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/loggers/file_logger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/loggers/file_logger_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/loggers/filter_logger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/loggers/filter_logger_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/loggers/format.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/loggers/shared_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/loggers/sort_logger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/loggers/sort_logger_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/loggers/stream_logger.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/loggers/stream_logger_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/lib/lib.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/lib/rpc_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/metrics/const_info.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/metrics/exporter_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/metrics/metrics.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/rpcdump/dump_server.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/rpcevents/blocks.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/rpcevents/blocks_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/rpcevents/execution_events_server.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/rpcinfo/methods.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/rpcquery/query_server.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/rpctransact/transact_server.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/web3/eth_service.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/web3/eth_service_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/web3/server.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/web3/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/payload/batch_tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/payload/bond_tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/payload/call_tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/payload/gov_tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/payload/identify_tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/payload/name_tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/payload/payload.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/payload/payload_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/payload/perms_tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/payload/proposal_tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/payload/send_tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/payload/tx_input.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/payload/tx_output.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `txs/payload/unbond_tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/chain/chain.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/config/config.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/service/abi_provider.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/service/block_consumer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/service/block_consumer_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/service/constants.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/service/consumer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/service/consumer_ethereum_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/service/consumer_integration_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/service/consumer_postgres_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/service/consumer_sqlite_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/service/decoder.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/service/rowbuilder.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/service/rowbuilder_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/service/server.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/service/server_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqldb/queries.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqldb/sqldb.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqldb/sqldb_integration_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqldb/sqldb_postgres_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqldb/sqldb_sqlite_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqldb/sqldb_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqldb/system_tables.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqlsol/block_data.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqlsol/block_data_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqlsol/constants.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqlsol/generate.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqlsol/generate_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqlsol/projection.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqlsol/projection_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqlsol/spec_loader.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqlsol/spec_loader_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqlsol/sqlsol.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/test/EventsTest.sol.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/test/db.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/test/events.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/test/sqlsol.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/types/event_class.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/types/event_class_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/types/event_data.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/types/event_input_type.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/types/event_tables.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/types/sql_column_type.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/types/sql_error_type.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/types/sql_supported_databases.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/types/sql_table.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/types/sql_utils.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/abi.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/accounts.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/compile.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/config_options.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/configure.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/deploy.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/dump.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/errors.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/explore.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/helpers.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/helpers_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/keys.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/restore.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/spec.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/start.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/tx.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/vent.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `cmd/burrow/commands/vent_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `consensus/tendermint/codes/codes.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/def/rule/rules.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `deploy/def/rule/rules_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/evm/abi/abi.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/evm/abi/abi_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/evm/abi/event_spec.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/evm/abi/event_spec_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/evm/abi/function_spec.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/evm/abi/packing.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/evm/abi/packing_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/evm/abi/primitives.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/evm/abi/primitives_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/evm/abi/spec.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/logconfig/presets/instructions.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `logging/logconfig/presets/instructions_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `project/cmd/changelog/main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `project/cmd/notes/main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `project/cmd/version/main.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/lib/jsonrpc/client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/lib/server/handlers.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/lib/server/handlers_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/lib/server/http_params.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/lib/server/http_server.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/lib/server/parse_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/lib/types/error_codes.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/lib/types/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/lib/types/types_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/rpcinfo/infoclient/client_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/web3/ethclient/client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/web3/ethclient/client_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/web3/ethclient/transact_client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/web3/ethclient/transact_client_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `rpc/web3/ethclient/types.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/web3/web3test/web3test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/chain/burrow/burrow.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/chain/ethereum/consumer.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/chain/ethereum/consumer_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/chain/ethereum/ethereum.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/chain/ethereum/throttle_client.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/chain/ethereum/throttler.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/chain/ethereum/throttler_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqldb/adapters/db_adapter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqldb/adapters/postgres_adapter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqldb/adapters/postgres_adapter_test.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqldb/adapters/sqlite_adapter.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `vent/sqldb/adapters/sqlite_adapter_nosqlite.go`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `execution/evm/asm/bc/helpers.go`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`package.json`).

</details>

## Passed <a href="#user-content-passed" id="passed">#</a>

<details>
<summary>Click to see rules</summary>

### ✅ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Contains https://wiki.hyperledger.org/display/.*(SEC|HYP)/Defect[.+]Response (`SECURITY.md`).

### ✅ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Did not find file matching the specified patterns. Below is a list of files or patterns that failed:

- `README.md`
- `README`

### ✅ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Found file (`MAINTAINERS.md`).

### ✅ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Found file (`CHANGELOG.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/repolinter.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`testnet`).

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

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=java"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

