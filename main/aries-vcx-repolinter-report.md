# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 7 | 5 | 5 | 1 | 18 |

- [Fail](#user-content-fail)
  - [❌ `apache-license-file`](#user-content--apache-license-file)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `security-file-matches`](#user-content--security-file-matches)
  - [❌ `readme-references-license`](#user-content--readme-references-license)
  - [❌ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [❌ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [❌ `changelog-file-exists`](#user-content--changelog-file-exists)
- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `apache-license-file` <a href="#user-content--apache-license-file" id="-apache-license-file">#</a>

Did not find file matching the specified patterns. (`LICENSE*`).

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Did not find file matching the specified patterns. (`CODE_OF_CONDUCT*`).

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

### ❌ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Did not find a file matching the specified patterns. (`CHANGELOG.md`).


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `wrappers/node/notification-server.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-cli/logger.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-cli/script-common.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-cli/vcxclient-cli.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-cli/vcxclient-interactive.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/demo/alice.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/demo/faber.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/demo/integration-test.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/demo/logger.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/demo/notification-server.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/demo/script-common.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/agent.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/common.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/index.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/distribute-tails.spec.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/feature-discovery.spec.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/sign-messaging.spec.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/sign-verify.spec.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/trustping.spec.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/update-state-v2.spec.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-connections.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-cred-holder.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-cred-issuer.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-ledger-creddef.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-ledger-schema.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-prover.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/services/service-verifier.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/storage/storage-file.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/storage/storage-service.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/utils/credentials.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/utils/messages.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/utils/proofs.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/src/utils/vcx-workflows.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/utils/alice.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/utils/data.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/utils/faber.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `agents/node/vcxagent-core/test/utils/utils.js`: The first 5 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`package.json`).

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `pom.xml`
- `build.xml`
- `build.gradle`

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `setup.py`
- `requirements.txt`

</details>

## Passed <a href="#user-content-passed" id="passed">#</a>

<details>
<summary>Click to see rules</summary>

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/main.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`ci/test.dockerfile`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!node_modules/**`).

### ✅ `license-detectable-by-licensee` <a href="#user-content--license-detectable-by-licensee" id="-license-detectable-by-licensee">#</a>

Licensee identified the license for project: Apache-2.0.

</details>

## Ignored <a href="#user-content-ignored" id="ignored">#</a>

<details>
<summary>Click to see rules</summary>

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=ruby"

</details>

