# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 4 | 3 | 9 | 2 | 18 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
  - [❌ `security-file-matches`](#user-content--security-file-matches)
  - [❌ `changelog-file-exists`](#user-content--changelog-file-exists)
  - [❌ `integrates-with-ci`](#user-content--integrates-with-ci)
- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [✅ `test-directory-exists`](#user-content--test-directory-exists)
  - [✅ `binaries-not-present`](#user-content--binaries-not-present)
  - [✅ `package-metadata-exists`](#user-content--package-metadata-exists)
  - [✅ `license-detectable-by-licensee`](#user-content--license-detectable-by-licensee)
- [Ignored](#user-content-ignored)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)
  - [`package-metadata-exists`](#user-content-package-metadata-exists)

## Fail <a href="#user-content-fail" id="fail">#</a>

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Did not find file matching the specified patterns. (`CODE_OF_CONDUCT*`).

### ❌ `security-file-matches` <a href="#user-content--security-file-matches" id="-security-file-matches">#</a>

Did not find file matching the specified patterns. (`SECURITY.md`).

### ❌ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Did not find a file matching the specified patterns. (`CHANGELOG.md`).

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

- `scripts/depcheck.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `scripts/pkgbump.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `scripts/pkgcheck.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `scripts/pkgstamp.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-admin/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/cli.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-embedded/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-hlfv1/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-proxy/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-server/cli.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-server/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-web/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-web/karma.conf.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cucumber-steps/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-documentation/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/cli.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/karma.conf.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/protractor.fabric.conf.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/protractor.web.conf.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/webpack.config.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground-api/cli.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground-api/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/cli.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/start.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-pouchdb/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/karma.conf.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/karma.conf.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-wallet-filesystem/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-wallet-inmemory/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/loopback-connector-composer/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-admin/lib/adminconnection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-admin/scripts/api-changelog.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-admin/scripts/tsgen.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-admin/test/adminconnection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/cli.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/lib/assetregistry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/lib/businessnetworkconnection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/lib/historian.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/lib/identityregistry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/lib/participantregistry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/lib/query.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/lib/registry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/lib/transactionregistry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/scripts/api-changelog.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/scripts/tsgen.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/test/assetregistry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/test/businessnetworkconnection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/test/historian.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/test/identityregistry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/test/participantregistry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/test/query.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/test/registry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-client/test/transactionregistry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/aclmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/baseexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/basefileexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/businessnetworkdefinition.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/businessnetworkmetadata.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/certificate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/certificateutil.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/commitdecorator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/commitdecoratorfactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/connection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/connectionmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/connectionprofilemanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/factory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/filewallet.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/globalize.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/idcard.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/indexcompiler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/modelmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/modelutil.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/querymanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/readonlydecorator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/readonlydecoratorfactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/returnsdecorator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/returnsdecoratorfactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/scriptmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/securitycontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/securityexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/serializer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/typenotfoundexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/util.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/wallet.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/scripts/api-changelog.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/scripts/systemmodelgen.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/scripts/tsgen.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/aclmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/baseexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/businessnetworkdefinition.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/basefileexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/businessnetworkmetadata.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/certificate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/certificateutil.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/commitdecorator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/commitdecoratorfactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/connection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/connectionmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/connectionprofilemanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/factory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/filewallet.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/idcard.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/indexcompiler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/modelmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/modelutil.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/module.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/querymanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/readonlydecorator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/readonlydecoratorfactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/returnsdecorator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/returnsdecoratorfactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/scriptmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/securitycontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/securityexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/serializer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/typenotfoundexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/util.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/wallet.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-embedded/lib/embeddedconnection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-embedded/lib/embeddedconnectionmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-embedded/lib/embeddedsecuritycontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-embedded/test/embeddedconnection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-embedded/test/embeddedconnectionmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-embedded/test/embeddedsecuritycontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-embedded/test/setup.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-hlfv1/lib/hlfconnection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-hlfv1/lib/hlfconnectionmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-hlfv1/lib/hlfqueryhandler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-hlfv1/lib/hlfsecuritycontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-hlfv1/lib/hlftxeventhandler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-hlfv1/lib/hlfutil.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-hlfv1/lib/hlfwalletproxy.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-hlfv1/test/hlfconnection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-hlfv1/test/hlfconnectionmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-hlfv1/test/hlfqueryhandler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-hlfv1/test/hlfsecuritycontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-hlfv1/test/hlftxeventhandler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-hlfv1/test/hlfutil.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-hlfv1/test/hlfwalletproxy.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-proxy/lib/proxybusinessnetworkcardstore.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-proxy/lib/proxyconnection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-proxy/lib/proxyconnectionmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-proxy/lib/proxysecuritycontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-proxy/lib/proxyutil.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-proxy/test/proxybusinessnetworkcardstore.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-proxy/test/proxyconnection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-proxy/test/proxyconnectionmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-proxy/test/proxysecuritycontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-proxy/test/proxyutil.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-server/lib/connectorserver.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-server/test/cli.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-server/test/connectorserver.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-web/lib/chaincodestore.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-web/lib/webconnection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-web/lib/webconnectionmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-web/lib/websecuritycontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-web/scripts/tsgen.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-web/test/chaincodestore.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-web/test/setup.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-web/test/webconnection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-web/test/webconnectionmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-connector-web/test/websecuritycontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cucumber-steps/lib/assetsteps.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cucumber-steps/lib/businessnetworksteps.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cucumber-steps/lib/composer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cucumber-steps/lib/errorsteps.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cucumber-steps/lib/eventsteps.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cucumber-steps/lib/hooks.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cucumber-steps/lib/identitysteps.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cucumber-steps/lib/participantsteps.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cucumber-steps/lib/transactionsteps.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cucumber-steps/test/composer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-documentation/lib/opus.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-documentation/test/opus.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-documentation/testdata/logic.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-documentation/testdata/objects.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `packages/composer-playground/config/empty.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/config/head-config.common.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/config/helpers.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/config/karma.conf.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/config/spec-bundle.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/config/webpack.common.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/config/webpack.dev.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/config/webpack.github-deploy.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/config/webpack.prod.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/config/webpack.test.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground-api/lib/util.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground-api/routes/npm.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground-api/test/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground-api/test/npm.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-report/bin/cmd.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-report/lib/report.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-report/test/cmd.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-report/test/report.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/lib/loopbackcardstore.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/lib/loopbackwallet.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/lib/util.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/server/server.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/server/servercmd.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/apikey.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/assets.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/authentication.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/cli.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/events.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/filter.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/ldapserver.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/multiuser.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/participants.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/queries.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/returningTransations.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/root.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/system.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/transactions.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/accesscontroller.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/accessexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/aclcompiler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/api.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/callbackrelationship.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/compiledaclbundle.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/compiledquerybundle.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/compiledscriptbundle.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/container.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/context.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/datacollection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/dataservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/engine.businessnetworks.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/engine.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/engine.logging.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/engine.queries.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/engine.registries.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/engine.resources.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/engine.transactions.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/eventservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/httpservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/identitymanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/identityservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/installedbusinessnetwork.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/invalidrelationship.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/loggingservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/networkmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/querycompiler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/registry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/registrymanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/resolver.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/resourcemanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/scriptcompiler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/service.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/transactionhandler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/transactionlogger.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/scripts/tsgen.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/accesscontroller.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/accessexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/aclcompiler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/api.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/callbackrelationship.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/compiledaclbundle.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/compiledquerybundle.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/compiledscriptbundle.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/container.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/context.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/datacollection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/dataservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/engine.businessnetworks.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/engine.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/engine.logging.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/engine.queries.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/engine.registries.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/engine.resources.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/engine.transactions.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/eventservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/httpservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/identitymanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/identityservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/installedbusinessnetwork.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/invalidrelationship.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/loggingservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/networkmanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/querycompiler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/registry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/registrymanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/resolver.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/resourcemanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/scriptcompiler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/service.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/transactionhandler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/transactionlogger.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/lib/embeddedcontainer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/lib/embeddedcontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/lib/embeddeddataservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/lib/embeddedeventservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/lib/embeddedhttpservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/lib/embeddedidentityservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/lib/embeddedloggingservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/lib/embeddedscriptcompiler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/test/embeddedcontainer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/test/embeddedcontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/test/embeddeddataservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/test/embeddedeventservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/test/embeddedhttpservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/test/embeddedidentityservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/test/embeddedloggingservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/test/embeddedscriptcompiler.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-embedded/test/setup.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/lib/composer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/lib/nodecontainer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/lib/nodecontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/lib/nodedatacollection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/lib/nodedataservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/lib/nodeeventservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/lib/nodehttpservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/lib/nodeidentityservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/lib/nodeloggingservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/lib/nodeutils.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/test/composer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/test/nodecontainer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/test/nodecontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/test/nodedatacollection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/test/nodedataservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/test/nodeeventservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/test/nodehttpservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/test/nodeidentityservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/test/nodeloggingservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/test/nodeutils.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-hlfv1/test/start.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-pouchdb/lib/pouchdbdatacollection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-pouchdb/lib/pouchdbdataservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-pouchdb/lib/pouchdbutils.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-pouchdb/test/pouchdbdatacollection.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-pouchdb/test/pouchdbdataservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-pouchdb/test/pouchdbutils.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-pouchdb/test/setup.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/lib/webcontainer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/lib/webcontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/lib/webdataservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/lib/webeventservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/lib/webhttpservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/lib/webidentityservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/lib/webloggingservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/test/setup.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/test/webcontainer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/test/webcontext.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/test/webdataservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/test/webeventservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/test/webhttpservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/test/webidentityservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime-web/test/webloggingservice.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/scripts/http.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/accesscontrols.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/assets.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/events.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/historian.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/identities.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/native.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/nohistorian.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/participants.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/post.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/queries.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/testutil.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/transactions.assets.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/transactions.http.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/transactions.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/transactions.native.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/transactions.participants.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/transactions.queries.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/lib/clisteps.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/lib/composer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/lib/errorsteps.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/lib/generatorsteps.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/lib/hooks.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/lib/md-code-extractor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/lib/reststeps.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/lib/tutorialsteps.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/scripts/ldap.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/scripts/npm_serve.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-wallet-filesystem/lib/filesystemwallet.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-wallet-filesystem/test/config.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-wallet-filesystem/test/wallet.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-wallet-inmemory/lib/memorywallet.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-wallet-inmemory/test/config.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-wallet-inmemory/test/wallet.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-website/scripts/merge.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/util.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/test/angular-archive.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/test/angular-network.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/test/app.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/test/business-network.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/test/loopback.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/test/model.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/loopback-connector-composer/lib/businessnetworkconnectionwrapper.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/loopback-connector-composer/lib/businessnetworkconnector.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/loopback-connector-composer/lib/filterparser.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/loopback-connector-composer/test/assets.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/loopback-connector-composer/test/businessnetworkconnectionwrapper.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/loopback-connector-composer/test/businessnetworkconnector.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/loopback-connector-composer/test/events.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/loopback-connector-composer/test/filterparser.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/loopback-connector-composer/test/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/loopback-connector-composer/test/participants.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/loopback-connector-composer/test/transactions.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/archive.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/card.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/generator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/identity.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/participant.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/report.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/transaction.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/archive/archive.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/archive/create.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/archive/list.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/card/card.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/card/create.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/card/delete.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/card/export.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/card/import.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/card/list.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/card/validate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/generator/createCode.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/generator/generator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/identity/bind.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/identity/identity.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/identity/issue.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/identity/list.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/identity/request.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/identity/revoke.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/network/download.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/network/install.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/network/list.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/network/loglevel.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/network/network.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/network/ping.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/network/reset.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/network/start.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/network/upgrade.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/participant/add.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/participant/participant.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/report/report.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/transaction/submit.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/transaction/transaction.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/test/utils/cmdutils.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/acl/aclfile.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/acl/aclrule.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/acl/illegalaclexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/acl/modelbinding.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/acl/operation.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/acl/predicate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/cardstore/businessnetworkcardstore.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/cardstore/networkcardstoremanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/cardstore/walletbackedcardstore.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/codegen/codegen.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/codegen/filewriter.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/codegen/javascriptparser.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/codegen/parsejs.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/codegen/writer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/config/configmediator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/assetdeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/classdeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/conceptdeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/decorated.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/decorator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/decoratorfactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/enumdeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/enumvaluedeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/eventdeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/field.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/functiondeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/illegalmodelexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/introspector.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/modelfile.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/numbervalidator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/parseexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/participantdeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/property.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/relationshipdeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/script.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/stringvalidator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/transactiondeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/validator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/log/consolelogger.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/log/logger.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/log/node.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/log/tree.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/log/winstonInjector.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/model/concept.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/model/identifiable.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/model/relationship.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/model/resource.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/model/resourceid.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/model/typed.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/model/validatedconcept.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/model/validatedresource.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/module/loadModule.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/query/invalidqueryexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/query/limit.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/query/orderby.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/query/query.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/query/queryanalyzer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/query/queryfile.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/query/select.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/query/skip.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/query/sort.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/query/where.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/query/whereastvalidator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/serializer/instancegenerator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/serializer/jsongenerator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/serializer/jsonpopulator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/serializer/resourcevalidator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/serializer/typedstack.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/serializer/validationexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/serializer/valuegenerator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/tools/changelog.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/tools/plantumltoimage.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/tools/versionchecker.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/acl/aclfile.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/acl/aclrule.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/acl/illegalaclexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/acl/modelbinding.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/acl/operation.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/acl/predicate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/cardstore/businessnetworkcardstore.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/cardstore/composer-wallet-fault.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/cardstore/networkcardstoremanager.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/cardstore/walletbackedcardstore.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/_template.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/filewriter.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/golangvisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/javascriptparser.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/javavisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/jsonschemavisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/loopbackvisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/loopbackvisitorcircular.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/parsejs.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/plantumlvisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/typescriptvisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/writer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/composer/i18n.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/config/configmediator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/assetdeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/classdeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/decorated.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/decorator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/decoratorfactory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/decorators.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/enumdeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/eventdeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/field.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/functiondeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/illegalmodelexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/introspector.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/introspectutils.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/modelfile.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/numbervalidator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/parseexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/participantdeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/property.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/property_ex.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/relationshipdeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/script.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/semantic_validation.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/stringvalidator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/transactiondeclaration.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/types.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/validator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/log/consolelogger.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/log/logger.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/log/tree.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/model/concept.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/model/identifiable.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/model/relationship.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/model/resource.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/model/typed.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/model/validatedconcept.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/models/animaltracking.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/models/dependencies2.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/models/farm2fork.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/models/model.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/models/relationship.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/models/test.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/models/vehicle-lifecycle.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/models/wildcards.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/module/testmodule.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/module/module.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/query/invalidqueryexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/query/limit.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/query/orderby.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/query/query.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/query/queryanalyzer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/query/queryfile.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/query/select.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/query/skip.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/query/sort.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/query/where.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/query/whereastvalidator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/serializer/instancegenerator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/serializer/jsongenerator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/serializer/jsonpopulator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/serializer/resourcevalidator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/serializer/typedstack.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/serializer/valuegenerator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/tools/changelog.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/tools/plantumltoimage.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/tools/versionchecker.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cucumber-steps/features/support/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-documentation/lib/processors/file.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-documentation/lib/processors/hc_network.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-documentation/lib/processors/markdownit.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-documentation/lib/processors/nunjucks.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-documentation/lib/processors/root.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-documentation/lib/processors/stream.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/config/github-deploy/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/config/html-elements-plugin/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/e2e/verdaccio/npm_serve.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/src/assets/service-worker.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground-api/config/environment/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/common/models/card.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/server/boot/authentication.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/server/boot/composer-discovery.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/server/boot/composer-runtime.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/server/boot/root.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/lib/loopbackcardstore.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/lib/loopbackwallet.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/lib/util.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/server/server.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/server/servercmd.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/api/assetregistry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/api/factory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/api/participantregistry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/api/query.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/lib/api/serializer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/api/assetregistry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/api/factory.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/api/participantregistry.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/api/query.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/api/serializer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-runtime/test/data/animaltracking.cto.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/data/accesscontrols.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/data/events.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/data/identities.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/data/post.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/data/queries.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/data/transactions.assets.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/data/transactions.http.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/data/transactions.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/data/transactions.participants.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/data/transactions.queries.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/data/transactions.utility.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/features/support/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-website/apigen-opus/bin/cli1.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-website/apigen-opus/lib/classopus.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/angular/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/app/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/businessnetwork/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/loopback/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/model/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/archive/createCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/archive/listCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/card/createCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/card/deleteCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/card/exportCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/card/importCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/card/listCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/generator/createCodeCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/generator/createDocsCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/identity/bindCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/identity/issueCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/identity/listCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/identity/requestCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/identity/revokeCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/downloadCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/installCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/listCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/loglevelCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/pingCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/resetCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/startCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/upgradeCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/participant/addCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/report/reportCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/transaction/submitCommand.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/utils/cmdutils.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/codegen/fromjs/apisignaturegenerator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/codegen/fromjs/jsongenerator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/codegen/fromjs/plantumlgenerator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/loaders/compositemodelfileloader.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/loaders/defaultmodelfileloader.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/loaders/githubmodelfileloader.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/loaders/httpmodelfileloader.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/loaders/jobqueue.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/introspect/loaders/modelfiledownloader.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/fromjs/apisignaturegenerator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/fromjs/jsonsignaturegenerator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/fromjs/platumlgenerator.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/model/animaltracking.cto.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/parser/functiondeclaration.bracesmissing.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/parser/functiondeclaration.good.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/parser/functiondeclaration.missingfirstbrace.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/parser/functiondeclaration.missingname.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/parser/functiondeclaration.missingsecondbrace.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/parser/functiondeclaration.missingtx.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/parser/functiondeclaration.missingtype.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/parser/functiondeclaration.notatx.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/parser/functiondeclaration.queryandtransaction.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/parser/functiondeclaration.spaces.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/parser/functiondeclaration.throwsexception.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/parser/functiondeclaration.typenametogether.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/loaders/compositemodelfileloader.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/loaders/defaultmodelfileloader.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/loaders/githubmodelfileloader.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/loaders/httpmodelfileloader.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/loaders/jobqueue.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/introspect/loaders/modelfiledownloader.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/serializer/complex/complex.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cucumber-steps/features/basic-sample-network/lib/sample.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-documentation/_bnaTemplate/assets.default/js/autotrack.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `packages/composer-documentation/_bnaTemplate/assets.default/js/nav.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `packages/composer-documentation/_bnaTemplate/assets.default/js/search.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `packages/composer-documentation/_bnaTemplate/assets.default/js/search_bar.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `packages/composer-documentation/lib/processors/generators/basics.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-documentation/lib/processors/generators/classdeclarations.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-documentation/lib/processors/parsers/modelfile-cmts.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `packages/composer-documentation/lib/processors/visitors/info.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/e2e/data/files/importScript.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/common/models/card.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/server/boot/authentication.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/server/boot/composer-discovery.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-rest-server/test/server/boot/composer-runtime.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-functional/systest/data/common-network/transactions.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-website/jekylldocs/assets/js/autotrack.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `packages/composer-website/jekylldocs/assets/js/nav.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-website/jekylldocs/assets/js/search.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-website/jekylldocs/assets/js/search_bar.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/angular/templates/app.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/angular/templates/karma.conf.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/angular/templates/protractor.conf.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/angular/templates/proxy.conf.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-admin/test/data/businessnetwork/lib/animaltracking.cto.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-admin/test/data/businessnetwork/lib/animaltracking.cto.queries.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/archive/lib/create.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/archive/lib/list.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/card/lib/create.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/card/lib/delete.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/card/lib/export.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/card/lib/import.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/card/lib/list.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/card/lib/validate.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/generator/lib/createCode.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/identity/lib/bind.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/identity/lib/issue.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/identity/lib/list.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/identity/lib/request.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/identity/lib/revoke.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/lib/download.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/lib/install.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/lib/list.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/lib/loglevel.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/lib/ping.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/lib/reset.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/lib/start.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/network/lib/upgrade.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/participant/lib/add.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/report/lib/report.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-cli/lib/cmds/transaction/lib/submit.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/codegen/fromcto/golang/golangvisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/codegen/fromcto/java/javavisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/codegen/fromcto/jsonschema/jsonschemavisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/codegen/fromcto/loopback/loopbackvisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/codegen/fromcto/plantuml/plantumlvisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/codegen/fromcto/typescript/typescriptvisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/lib/codegen/fromcto/xmlschema/xmlschemavisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/fromcto/golang/golangvisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/fromcto/java/javavisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/fromcto/jsonschema/jsonschemavisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/fromcto/loopback/loopbackvisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/fromcto/plantuml/plantumlvisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/fromcto/typescript/typescriptvisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/codegen/fromcto/xmlschema/xmlschemavisitor.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-documentation/_bnaTemplate/assets.default/js/libs/prettify.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `packages/composer-rest-server/test/data/bond-network/lib/logic.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/resources/sample-networks/basic-sample-network/lib/sample.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/resources/sample-networks/carauction-network/lib/logic.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/resources/sample-networks/marbles-network/lib/logic.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/resources/sample-networks/marbles-network-update/lib/logic.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/resources/sample-networks/queries-network/lib/logic.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/resources/sample-networks/test-network/lib/logic.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/resources/sample-networks/trade-network/lib/logic.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-tests-integration/resources/sample-networks/vehicle-manufacture-network/lib/script.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-website/jekylldocs/assets/js/libs/prettify.js`: The first 5 lines do not contain the pattern(s): Copyright, License.
- `packages/generator-hyperledger-composer/generators/businessnetwork/templates/lib/logic.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/businessnetwork/templates/test/logic.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/loopback-connector-composer/test/data/bond-network/lib/logic.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/zip/test-archive/lib/mozart.cto.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/zip/test-archive/lib/mozart.cto.queries.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/zip/test-archive-dotfolders/lib/mozart.cto.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/zip/test-npm-archive/lib/mozart.cto.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-common/test/data/zip/test-npm-archive/lib/mozart.cto.queries.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/e2e/data/sample-networks/basic-sample-network/lib/sample.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/composer-playground/e2e/data/sample-networks/import-network/lib/sample.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/businessnetwork/templates/features/support/index.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/loopback/templates/skeleton/server/server.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/loopback/templates/skeleton/common/lib/composer.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/loopback/templates/skeleton/common/models/ping-response.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/loopback/templates/skeleton/common/models/system.js`: The first 5 lines do not contain the pattern(s): Copyright.
- `packages/generator-hyperledger-composer/generators/loopback/templates/skeleton/server/boot/root.js`: The first 5 lines do not contain the pattern(s): Copyright.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. (`Gemfile`).

</details>

## Passed <a href="#user-content-passed" id="passed">#</a>

<details>
<summary>Click to see rules</summary>

### ✅ `apache-license-file` <a href="#user-content--apache-license-file" id="-apache-license-file">#</a>

Contains Apache License.*Version 2.0 (`LICENSE.txt`).

### ✅ `readme-file-exists` <a href="#user-content--readme-file-exists" id="-readme-file-exists">#</a>

Found file (`README.md`).

### ✅ `readme-references-license` <a href="#user-content--readme-references-license" id="-readme-references-license">#</a>

Contains license (`README.md`).

### ✅ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Found file (`MAINTAINERS.md`).

### ✅ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Found file (`CONTRIBUTING.md`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`packages/composer-admin/test`).

### ✅ `binaries-not-present` <a href="#user-content--binaries-not-present" id="-binaries-not-present">#</a>

Excluded file type doesn't exist. (`**/*.exe,**/*.dll,!node_modules/**`).

### ✅ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Found file (`package.json`).

### ✅ `license-detectable-by-licensee` <a href="#user-content--license-detectable-by-licensee" id="-license-detectable-by-licensee">#</a>

Licensee identified the license for project: NOASSERTION.

</details>

## Ignored <a href="#user-content-ignored" id="ignored">#</a>

<details>
<summary>Click to see rules</summary>

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=java"

### `package-metadata-exists` <a href="#user-content-package-metadata-exists" id="package-metadata-exists">#</a>

This rule was ignored for the following reason: ignored due to unsatisfied condition(s): "language=python"

</details>

