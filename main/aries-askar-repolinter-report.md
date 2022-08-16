# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 4 | 7 | 7 | 1 | 19 |

- [Fail](#user-content-fail)
  - [❌ `apache-license-file`](#user-content--apache-license-file)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `security-file-matches`](#user-content--security-file-matches)
  - [❌ `maintainers-file-exists`](#user-content--maintainers-file-exists)
- [Warning](#user-content-warning)
  - [⚠️ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `apache-license-file` <a href="#user-content--apache-license-file" id="-apache-license-file">#</a>

Below is a list of files or patterns that failed:

- `LICENSE-MIT`: Doesn't contain Apache License.*Version 2.0.

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Did not find file matching the specified patterns. (`CODE_OF_CONDUCT*`).

### ❌ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Did not find file matching the specified patterns. (`SECURITY.md`).

### ❌ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `MAINTAINERS.md`
- `MAINTAINERS.rst`


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Did not find a file matching the specified patterns. (`CHANGELOG.md`).

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `wrappers/javascript/nodejs/babel.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/babel.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/jest.config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/NodeJSAriesAskar.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/error.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/cryptoBox.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/joseEcdh.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/keys.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/store.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/src/ReactNativeAriesAskar.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/error.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/types.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/ffi/alloc.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/ffi/callback.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/ffi/conversion.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/ffi/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/ffi/primitives.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/ffi/serialize.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/ffi/structures.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/library/NativeBindingInterface.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/library/bindings.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/library/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/src/library/register.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/utils/fixtures.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/utils/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/nodejs/tests/utils/initialize.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/src/library/NativeBindings.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/src/library/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/src/library/register.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/src/utils/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/src/utils/serialize.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/ariesAskar/AriesAskar.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/ariesAskar/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/ariesAskar/register.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/crypto/CryptoBox.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/crypto/Ecdh1PU.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/crypto/EcdhEs.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/crypto/Jwk.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/crypto/Key.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/crypto/handles.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/crypto/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/enums/EntryOperation.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/enums/KeyAlgs.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/enums/KeyMethod.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/enums/LogLevel.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/enums/SigAlgs.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/enums/StoreKeyMethod.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/enums/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/store/Entry.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/store/EntryList.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/store/KeyEntry.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/store/KeyEntryList.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/store/OpenSession.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/store/Scan.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/store/Session.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/store/Store.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/shared/src/store/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/android/src/main/java/org/hyperledger/ariesaskar/AriesAskarModule.java`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `wrappers/javascript/react-native/android/src/main/java/org/hyperledger/ariesaskar/AriesAskarPackage.java`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`package.json`).

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`Gemfile`).

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

### ✅ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Contains license (`README.md`).

### ✅ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Found file (`CONTRIBUTING.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/build-android.yml`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`tests`).

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

</details>

