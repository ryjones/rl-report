# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 4 | 3 | 8 | 4 | 19 |

- [Fail](#user-content-fail)
  - [❌ `security-file-matches`](#user-content--security-file-matches)
  - [❌ `readme-references-license`](#user-content--readme-references-license)
  - [❌ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [❌ `contributing-file-exists`](#user-content--contributing-file-exists)
- [Warning](#user-content-warning)
  - [⚠️ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
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

### ❌ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `MAINTAINERS.md`
- `MAINTAINERS.rst`

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

- `packages/stitch/ext_libs/_concat.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `packages/stitch/ext_libs/loglevel-1.6.1.min.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `packages/stitch/ext_libs/loglevel-plugin-remote-0.6.0.min.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/apollo/src/components/JoinOSNChannelModal/JoinOSNChannelModal.js`: The first 7 lines do not contain the pattern(s): Copyright.
- `packages/stitch/src/protoc/output/common/common_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/common/configtx_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/common/configuration_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/common/ledger_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/common/policies_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/msp/identities_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/msp/msp_config_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/msp/msp_principal_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/orderer/ab_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/orderer/ab_pb_service.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/orderer/configuration_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/chaincode_event_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/chaincode_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/configuration_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/events_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/events_pb_service.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/peer_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/peer_pb_service.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/proposal_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/proposal_response_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/query_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/transaction_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/google/protobuf/timestamp_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/ledger/rwset/rwset_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/ledger/rwset/kvrwset/kv_rwset_pb.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/common/common_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/common/configtx_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/common/configuration_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/common/ledger_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/common/policies_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/msp/identities_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/msp/msp_config_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/msp/msp_principal_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/orderer/ab_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/orderer/ab_pb_service.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/orderer/configuration_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/chaincode_event_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/chaincode_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/configuration_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/events_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/events_pb_service.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/peer_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/peer_pb_service.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/proposal_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/proposal_response_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/query_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/peer/transaction_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/google/protobuf/timestamp_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/ledger/rwset/rwset_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/stitch/src/protoc/output/ledger/rwset/kvrwset/kv_rwset_pb.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.

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

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/apollo.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`common/deploy_scripts/test_run_athena.sh`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!**/node_modules/**`).

### ✅ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Found file (`package.json`).

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

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>
