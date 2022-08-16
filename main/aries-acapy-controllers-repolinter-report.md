# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 3 | 4 | 8 | 4 | 19 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [❌ `integrates-with-ci`](#user-content--integrates-with-ci)
- [Warning](#user-content-warning)
  - [⚠️ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Doesn't contain https://wiki.hyperledger.org/community/hyperledger-project-code-of-conduct (`CODE_OF_CONDUCT.md`).

### ❌ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `MAINTAINERS.md`
- `MAINTAINERS.rst`

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

### ⚠️ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Did not find a file matching the specified patterns. (`CHANGELOG.md`).

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `AliceFaberAcmeDemo/controllers/acme-controller/app.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/extra-webpack.config.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/karma.conf.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/acme-controller/routes/connection.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/acme-controller/routes/index.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/acme-controller/routes/proof.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/acme-controller/services/AgentService.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/acme-controller/services/NavLinkService.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/e2e/protractor.conf.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/main.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/polyfills.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/typings.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/e2e/src/app.e2e-spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/e2e/src/app.po.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/app-routing.module.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/app.module.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/environments/environment.prod.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/environments/environment.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/connection/connection-resolver.service.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/connection/connection-resolver.service.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/connection/connection-routing.module.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/connection/connection.module.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/credential/credential-routing.module.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/credential/credential.module.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/enums/agent-status.enum.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/models/nav-link.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/models/nav-link.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/proof/proof-routing.module.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/proof/proof.module.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/services/agent.service.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/services/agent.service.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/services/interceptor.service.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/services/interceptor.service.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/services/nav-link.service.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/services/nav-link.service.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/shared/shared.module.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/components/app/app.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/components/app/app.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/components/nav/nav.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/components/nav/nav.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/components/nav-card/nav-card.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/components/nav-card/nav-card.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/components/nav-card-list/nav-card-list.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/components/nav-card-list/nav-card-list.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/shared/pipes/to-date.pipe.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/shared/pipes/to-date.pipe.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/connection/components/accept-connection/accept-connection.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/connection/components/accept-connection/accept-connection.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/connection/components/connection/connection.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/connection/components/connection/connection.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/connection/components/connection-card/connection-card.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/connection/components/connection-card/connection-card.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/connection/components/connection-list/connection-list.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/connection/components/connection-list/connection-list.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/connection/components/new-connection/new-connection.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/connection/components/new-connection/new-connection.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/credential/components/credential/credential.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/credential/components/credential/credential.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/credential/components/credential-card/credential-card.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/credential/components/credential-card/credential-card.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/credential/components/credential-list/credential-list.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/credential/components/credential-list/credential-list.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/proof/components/proof/proof.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/proof/components/proof/proof.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/proof/components/proof-card/proof-card.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/proof/components/proof-card/proof-card.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/proof/components/proof-list/proof-list.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/proof/components/proof-list/proof-list.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/shared/components/component-nav/component-nav.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/shared/components/component-nav/component-nav.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/shared/components/empty-list/empty-list.component.spec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `AliceFaberAcmeDemo/controllers/alice-controller/src/app/shared/components/empty-list/empty-list.component.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`package.json`).

</details>

## Passed <a href="#user-content-passed" id="passed">#</a>

<details>
<summary>Click to see rules</summary>

### ✅ `apache-license-file` <a href="#user-content--apache-license-file" id="-apache-license-file">#</a>

Contains Apache License.*Version 2.0 (`LICENSE`).

### ✅ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Contains https://wiki.hyperledger.org/display/.*(SEC|HYP)/Defect[.+]Response (`SECURITY.md`).

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Contains license (`README.md`).

### ✅ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Found file (`CONTRIBUTING.md`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`AliceFaberAcmeDemo/controllers/alice-controller/src/test.ts`).

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

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

