# Repolinter Report

*This report was generated automatically by the Repolinter.*

This Repolinter run generated the following results:
| ❗  Error | ❌  Fail | ⚠️  Warn | ✅  Pass | Ignored | Total |
|---|---|---|---|---|---|
| 0 | 1 | 3 | 12 | 3 | 19 |

- [Fail](#user-content-fail)
  - [❌ `code-of-conduct-file`](#user-content--code-of-conduct-file)
- [Warning](#user-content-warning)
  - [⚠️ `notice-file-exists`](#user-content--notice-file-exists)
  - [⚠️ `source-license-headers-exist`](#user-content--source-license-headers-exist)
  - [⚠️ `package-metadata-exists`](#user-content--package-metadata-exists)
- [Passed](#user-content-passed)
  - [✅ `apache-license-file`](#user-content--apache-license-file)
  - [✅ `security-file-matches`](#user-content--security-file-matches)
  - [✅ `readme-file-exists`](#user-content--readme-file-exists)
  - [✅ `readme-references-license`](#user-content--readme-references-license)
  - [✅ `maintainers-file-exists`](#user-content--maintainers-file-exists)
  - [✅ `contributing-file-exists`](#user-content--contributing-file-exists)
  - [✅ `integrates-with-ci`](#user-content--integrates-with-ci)
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

### ❌ `code-of-conduct-file` <a href="#user-content--code-of-conduct-file" id="-code-of-conduct-file">#</a>

Did not find file matching the specified patterns. (`CODE_OF_CONDUCT*`).


## Warning <a href="#user-content-warning" id="warning">#</a>

<details>
<summary>Click to see rules</summary>

### ⚠️ `notice-file-exists` <a href="#user-content--notice-file-exists" id="-notice-file-exists">#</a>

Did not find a file matching the specified patterns. (`NOTICE*`).

### ⚠️ `source-license-headers-exist` <a href="#user-content--source-license-headers-exist" id="-source-license-headers-exist">#</a>

Below is a list of files or patterns that failed:

- `packages/node/bin/is-indy-installed.js`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `jest.config.base.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `jest.config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/mediator.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `scripts/get-next-bump.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/InMemoryStorageService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/e2e-http.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/e2e-subject.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/e2e-test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/e2e-ws-pickup-v2.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/e2e-ws.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/jest.config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `demo/src/Alice.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `demo/src/AliceInquirer.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `demo/src/BaseAgent.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `demo/src/BaseInquirer.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `demo/src/Faber.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `demo/src/FaberInquirer.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `demo/src/Listener.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `demo/src/OutputClass.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/jest.config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/node/jest.config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/react-native/jest.config.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/requester.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/responder.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/transport/SubjectInboundTransport.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `tests/transport/SubjectOutboundTransport.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/constants.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/types.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/TestMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/agents.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/connectionless-proofs.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/connections.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/dids.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/generic-records.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/helpers.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/ledger.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/logger.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/migration.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/multi-protocol-version.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/oob-mediation-provision.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/oob-mediation.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/oob.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/postgres.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/proofs-auto-accept.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/proofs-sub-protocol.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/proofs.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/setup.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/tests/wallet.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/types/jest.d.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/node/src/NodeFileSystem.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/node/src/PostgresPlugin.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/node/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/node/tests/NodeFileSystem.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/react-native/src/ReactNativeFileSystem.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/react-native/src/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/react-native/tests/index.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/DummyApi.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/module.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/Agent.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/AgentConfig.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/AgentDependencies.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/AgentMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/BaseMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/Dispatcher.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/EnvelopeService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/EventEmitter.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/Events.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/Handler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/MessageReceiver.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/MessageSender.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/TransportService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/helpers.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/cache/CacheRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/cache/CacheRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/cache/PersistedLruCache.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/cache/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/crypto/JwsService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/crypto/JwsTypes.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/crypto/KeyType.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/crypto/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/error/AriesFrameworkError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/error/ClassValidationError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/error/IndySdkError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/error/RecordDuplicateError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/error/RecordNotFoundError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/error/ValidationErrorUtils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/error/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/logger/BaseLogger.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/logger/ConsoleLogger.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/logger/Logger.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/logger/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/logger/replaceError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/plugins/DependencyManager.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/plugins/Module.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/plugins/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/BaseRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/FileSystem.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/InMemoryMessageRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/IndyStorageService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/MessageRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/Metadata.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/Repository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/RepositoryEvents.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/StorageService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/transport/HttpOutboundTransport.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/transport/InboundTransport.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/transport/OutboundTransport.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/transport/TransportEventTypes.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/transport/WsOutboundTransport.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/transport/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/Hasher.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/HashlinkEncoder.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/JWE.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/JsonEncoder.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/JsonTransformer.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/LinkedAttachment.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/MessageValidator.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/MultiBaseEncoder.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/MultiHashEncoder.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/TypedArrayEncoder.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/VarintEncoder.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/attachment.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/base58.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/base64.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/buffer.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/did.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/indyError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/indyProofRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/messageType.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/mixins.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/parseInvitation.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/path.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/promises.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/regex.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/sleep.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/string.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/timestamp.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/transformers.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/type.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/uri.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/uuid.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/validators.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/version.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/wallet/IndyWallet.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/wallet/Wallet.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/wallet/Wallet.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/wallet/WalletModule.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/wallet/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/node/src/transport/HttpInboundTransport.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/node/src/transport/WsInboundTransport.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/handlers/DummyRequestHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/handlers/DummyResponseHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/handlers/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/messages/DummyRequestMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/messages/DummyResponseMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/repository/DummyRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/repository/DummyRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/repository/DummyState.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/repository/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/services/DummyEvents.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/services/DummyService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `samples/extension-module/dummy/services/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/__tests__/Agent.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/__tests__/AgentConfig.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/__tests__/AgentMessage.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/__tests__/Dispatcher.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/__tests__/MessageSender.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/__tests__/TransportService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/__tests__/stubs.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/agent/models/InboundMessageContext.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/cache/__tests__/PersistedLruCache.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/crypto/__tests__/JwsService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/ack/AckDecorator.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/ack/AckDecorator.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/ack/AckDecoratorExtension.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/attachment/Attachment.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/attachment/AttachmentExtension.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/l10n/L10nDecorator.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/l10n/L10nDecorator.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/l10n/L10nDecoratorExtension.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/service/ServiceDecorator.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/service/ServiceDecorator.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/service/ServiceDecoratorExtension.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/signature/SignatureDecorator.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/signature/SignatureDecoratorUtils.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/signature/SignatureDecoratorUtils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/thread/ThreadDecorator.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/thread/ThreadDecorator.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/thread/ThreadDecoratorExtension.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/timing/TimingDecorator.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/timing/TimingDecorator.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/timing/TimingDecoratorExtension.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/transport/TransportDecorator.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/transport/TransportDecorator.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/transport/TransportDecoratorExtension.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/error/__tests__/BaseError.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/error/__tests__/ValidationErrorUtils.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/basic-messages/BasicMessageEvents.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/basic-messages/BasicMessageRole.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/basic-messages/BasicMessagesModule.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/basic-messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/common/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/ConnectionEvents.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/ConnectionsModule.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/DidExchangeProtocol.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/DidExchangeStateMachine.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/CredentialEvents.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/CredentialServiceOptions.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/CredentialsModule.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/CredentialsModuleOptions.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/DidsModule.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/helpers.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/types.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/discover-features/DiscoverFeaturesModule.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/discover-features/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/generic-records/GenericRecordsModule.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/indy/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/indy/module.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/ledger/IndyPool.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/ledger/LedgerModule.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/ledger/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/ledger/ledgerUtil.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/OutOfBandModule.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/OutOfBandService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/helpers.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/problem-reports/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/ProofAutoAcceptType.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/ProofEvents.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/ProofResponseCoordinator.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/ProofState.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/ProofsModule.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/QuestionAnswerEvents.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/QuestionAnswerModule.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/QuestionAnswerRole.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/MediatorModule.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/MediatorPickupStrategy.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/RecipientModule.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/RoutingEvents.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/plugins/__tests__/DependencyManager.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/__tests__/DidCommMessageRecord.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/__tests__/DidCommMessageRepository.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/__tests__/IndyStorageService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/__tests__/Metadata.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/__tests__/Repository.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/__tests__/TestRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/didcomm/DidCommMessageRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/didcomm/DidCommMessageRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/didcomm/DidCommMessageRole.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/didcomm/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/StorageUpdateService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/UpdateAssistant.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/updates.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/HashlinkEncoder.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/JWE.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/JsonEncoder.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/JsonTransformer.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/MessageValidator.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/MultiBaseEncoder.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/MultiHashEncoder.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/TypedArrayEncoder.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/did.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/indyError.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/indyProofRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/messageType.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/regex.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/shortenedUrl.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/string.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/transformers.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/utils/__tests__/version.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/wallet/error/WalletDuplicateError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/wallet/error/WalletError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/wallet/error/WalletInvalidKeyError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/wallet/error/WalletNotFoundError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/wallet/error/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/crypto/__tests__/__fixtures__/didJwsz6Mkf.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/crypto/__tests__/__fixtures__/didJwsz6Mkv.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/decorators/attachment/__tests__/Attachment.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/basic-messages/__tests__/BasicMessageService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/basic-messages/handlers/BasicMessageHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/basic-messages/handlers/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/basic-messages/messages/BasicMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/basic-messages/messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/basic-messages/repository/BasicMessageRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/basic-messages/repository/BasicMessageRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/basic-messages/repository/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/basic-messages/services/BasicMessageService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/basic-messages/services/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/common/messages/AckMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/__tests__/ConnectionInvitationMessage.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/__tests__/ConnectionRequestMessage.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/__tests__/ConnectionService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/__tests__/helpers.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/errors/ConnectionProblemReportError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/errors/ConnectionProblemReportReason.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/errors/DidExchangeProblemReportError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/errors/DidExchangeProblemReportReason.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/errors/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/handlers/AckMessageHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/handlers/ConnectionProblemReportHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/handlers/ConnectionRequestHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/handlers/ConnectionResponseHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/handlers/DidExchangeCompleteHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/handlers/DidExchangeRequestHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/handlers/DidExchangeResponseHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/handlers/TrustPingMessageHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/handlers/TrustPingResponseMessageHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/handlers/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/messages/ConnectionInvitationMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/messages/ConnectionProblemReportMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/messages/ConnectionRequestMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/messages/ConnectionResponseMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/messages/DidExchangeCompleteMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/messages/DidExchangeProblemReportMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/messages/DidExchangeRequestMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/messages/DidExchangeResponseMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/messages/TrustPingMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/messages/TrustPingResponseMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/Connection.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/ConnectionRole.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/ConnectionState.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/DidExchangeRole.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/DidExchangeState.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/HandshakeProtocol.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/InvitationDetails.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/repository/ConnectionRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/repository/ConnectionRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/repository/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/services/ConnectionService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/services/TrustPingService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/services/helpers.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/services/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/__tests__/fixtures.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/errors/CredentialProblemReportError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/errors/CredentialProblemReportReason.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/errors/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/CredentialFormat.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/CredentialFormatService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/CredentialFormatServiceOptions.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/models/CredentialAutoAcceptType.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/models/CredentialFormatSpec.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/models/CredentialPreviewAttribute.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/models/CredentialState.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/models/RevocationNotification.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/models/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/repository/CredentialExchangeRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/repository/CredentialMetadataTypes.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/repository/CredentialRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/repository/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/services/CredentialService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/services/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/util/composeAutoAccept.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/util/previewAttributes.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/__tests__/DidResolverService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/__tests__/keyDidDocument.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/__tests__/peer-did.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/DidDocument.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/DidDocumentBuilder.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/DidDocumentRole.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/DidResolver.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/Key.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/createPeerDidFromServices.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/keyDidDocument.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/parse.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/repository/DidRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/repository/DidRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/repository/didRecordMetadataTypes.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/repository/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/services/DidResolverService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/services/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/discover-features/__tests__/DiscoverFeaturesService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/discover-features/handlers/DiscloseMessageHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/discover-features/handlers/QueryMessageHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/discover-features/handlers/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/discover-features/messages/DiscloseMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/discover-features/messages/QueryMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/discover-features/messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/discover-features/services/DiscoverFeaturesService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/discover-features/services/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/generic-records/repository/GenericRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/generic-records/repository/GenericRecordsRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/generic-records/service/GenericRecordService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/indy/services/IndyHolderService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/indy/services/IndyIssuerService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/indy/services/IndyRevocationService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/indy/services/IndyUtilitiesService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/indy/services/IndyVerifierService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/indy/services/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/ledger/__tests__/IndyLedgerService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/ledger/__tests__/IndyPoolService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/ledger/__tests__/didResponses.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/ledger/error/LedgerError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/ledger/error/LedgerNotConfiguredError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/ledger/error/LedgerNotFoundError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/ledger/services/IndyLedgerService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/ledger/services/IndyPoolService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/ledger/services/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/__tests__/OutOfBandInvitation.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/__tests__/OutOfBandService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/__tests__/helpers.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/domain/OutOfBandDidCommService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/domain/OutOfBandEvents.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/domain/OutOfBandRole.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/domain/OutOfBandState.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/handlers/HandshakeReuseAcceptedHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/handlers/HandshakeReuseHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/handlers/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/messages/HandshakeReuseAcceptedMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/messages/HandshakeReuseMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/messages/OutOfBandInvitation.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/repository/OutOfBandRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/repository/OutOfBandRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/repository/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/problem-reports/errors/ProblemReportError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/problem-reports/errors/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/problem-reports/messages/ProblemReportMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/problem-reports/messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/problem-reports/models/ProblemReportReason.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/problem-reports/models/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/__tests__/ProofRequest.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/__tests__/ProofService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/__tests__/ProofState.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/__tests__/fixtures.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/errors/PresentationProblemReportError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/errors/PresentationProblemReportReason.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/errors/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/handlers/PresentationAckHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/handlers/PresentationHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/handlers/PresentationProblemReportHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/handlers/ProposePresentationHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/handlers/RequestPresentationHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/handlers/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/messages/PresentationAckMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/messages/PresentationMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/messages/PresentationPreview.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/messages/PresentationProblemReportMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/messages/ProposePresentationMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/messages/RequestPresentationMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/models/AttributeFilter.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/models/PartialProof.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/models/PredicateType.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/models/ProofAttribute.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/models/ProofAttributeInfo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/models/ProofIdentifier.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/models/ProofPredicateInfo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/models/ProofRequest.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/models/RequestedAttribute.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/models/RequestedCredentials.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/models/RequestedPredicate.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/models/RequestedProof.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/models/RetrievedCredentials.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/models/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/repository/ProofRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/repository/ProofRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/repository/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/services/ProofService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/proofs/services/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/__tests__/QuestionAnswerService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/handlers/AnswerMessageHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/handlers/QuestionMessageHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/handlers/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/messages/AnswerMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/messages/QuestionMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/models/QuestionAnswerState.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/models/ValidResponse.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/models/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/repository/QuestionAnswerRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/repository/QuestionAnswerRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/repository/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/services/QuestionAnswerService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/question-answer/services/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/__tests__/mediation.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/__tests__/pickup.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/error/RoutingProblemReportReason.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/error/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/handlers/ForwardHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/handlers/KeylistUpdateHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/handlers/KeylistUpdateResponseHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/handlers/MediationDenyHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/handlers/MediationGrantHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/handlers/MediationRequestHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/handlers/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/messages/ForwardMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/messages/KeylistMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/messages/KeylistUpdateMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/messages/KeylistUpdateResponseMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/messages/MediationDenyMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/messages/MediationGrantMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/messages/MediationRequestMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/models/MediationRole.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/models/MediationState.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/models/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/repository/MediationRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/repository/MediationRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/repository/MediatorRoutingRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/repository/MediatorRoutingRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/repository/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/services/MediationRecipientService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/services/MediatorService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/services/RoutingService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/services/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/__tests__/0.1.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/__tests__/UpdateAssistant.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/__tests__/backup.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/__tests__/updates.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/error/StorageUpdateError.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/repository/StorageVersionRecord.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/repository/StorageVersionRepository.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/__tests__/ConnectionState.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/did/DidDoc.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/did/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/repository/__tests__/ConnectionRecord.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/indy/IndyCredentialFormat.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/indy/IndyCredentialFormatService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/indy/IndyCredentialUtils.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/indy/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/models/__tests__/CredentialState.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/revocation-notification/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/V1CredentialService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/CredentialFormatCoordinator.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/V2CredentialService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/repository/__tests__/CredentialExchangeRecord.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/util/__tests__/previewAttributes.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/__tests__/DidDocument.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/key-type/bls12381g1.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/key-type/bls12381g1g2.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/key-type/bls12381g2.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/key-type/ed25519.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/key-type/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/key-type/keyDidMapping.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/key-type/multiCodecKey.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/key-type/x25519.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/service/DidCommV1Service.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/service/DidCommV2Service.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/service/DidDocumentService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/service/IndyAgentService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/service/ServiceTransformer.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/service/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/verificationMethod/VerificationMethod.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/verificationMethod/VerificationMethodTransformer.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/verificationMethod/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/key/DidKey.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/key/KeyDidResolver.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/key/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/peer/PeerDidResolver.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/peer/didPeer.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/peer/peerDidNumAlgo0.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/peer/peerDidNumAlgo1.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/peer/peerDidNumAlgo2.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/sov/SovDidResolver.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/web/WebDidResolver.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/repository/__tests__/DidRecord.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/indy/services/__mocks__/IndyHolderService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/indy/services/__mocks__/IndyIssuerService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/indy/services/__mocks__/IndyVerifierService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/oob/repository/__tests__/OutOfBandRecord.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/services/__tests__/MediationRecipientService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/services/__tests__/MediatorService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/services/__tests__/RoutingService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/services/__tests__/V2MessagePickupService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/updates/0.1-0.2/connection.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/updates/0.1-0.2/credential.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/updates/0.1-0.2/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/updates/0.1-0.2/mediation.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/did/__tests__/Authentication.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/did/__tests__/DidDoc.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/did/__tests__/PublicKey.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/did/authentication/Authentication.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/did/authentication/EmbeddedAuthentication.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/did/authentication/ReferencedAuthentication.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/did/authentication/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/did/publicKey/Ed25119Sig2018.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/did/publicKey/EddsaSaSigSecp256k1.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/did/publicKey/PublicKey.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/did/publicKey/RsaSig2018.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/connections/models/did/publicKey/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/indy/__tests__/IndyCredentialUtils.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/indy/models/IndyCredPropose.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/indy/models/IndyCredential.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/indy/models/IndyCredentialInfo.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/indy/models/IndyCredentialView.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/indy/models/IndyRevocationInterval.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/indy/models/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/revocation-notification/handlers/V1RevocationNotificationHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/revocation-notification/handlers/V2RevocationNotificationHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/revocation-notification/handlers/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/revocation-notification/messages/V1RevocationNotificationMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/revocation-notification/messages/V2RevocationNotificationMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/revocation-notification/messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/revocation-notification/services/RevocationNotificationService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/revocation-notification/services/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/revocation-notification/util/revocationIdentifier.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/__tests__/V1CredentialServiceCred.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/__tests__/V1CredentialServiceProposeOffer.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/__tests__/v1-connectionless-credentials.e2e.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/__tests__/v1-credentials-auto-accept.e2e.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/__tests__/v1-credentials.e2e.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/handlers/V1CredentialAckHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/handlers/V1CredentialProblemReportHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/handlers/V1IssueCredentialHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/handlers/V1OfferCredentialHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/handlers/V1ProposeCredentialHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/handlers/V1RequestCredentialHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/handlers/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/messages/V1CredentialAckMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/messages/V1CredentialPreview.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/messages/V1CredentialProblemReportMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/messages/V1IssueCredentialMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/messages/V1OfferCredentialMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/messages/V1ProposeCredentialMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/messages/V1RequestCredentialMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v1/messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/__tests__/V2CredentialServiceCred.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/__tests__/V2CredentialServiceOffer.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/__tests__/v2-connectionless-credentials.e2e.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/__tests__/v2-credentials-auto-accept.e2e.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/__tests__/v2-credentials.e2e.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/handlers/V2CredentialAckHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/handlers/V2CredentialProblemReportHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/handlers/V2IssueCredentialHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/handlers/V2OfferCredentialHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/handlers/V2ProposeCredentialHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/handlers/V2RequestCredentialHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/handlers/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/messages/V2CredentialAckMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/messages/V2CredentialPreview.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/messages/V2CredentialProblemReportMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/messages/V2IssueCredentialMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/messages/V2OfferCredentialMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/messages/V2ProposeCredentialMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/messages/V2RequestCredentialMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/v2/messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/key-type/__tests__/bls12381g1.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/key-type/__tests__/bls12381g1g2.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/key-type/__tests__/bls12381g2.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/key-type/__tests__/ed25519.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/domain/key-type/__tests__/x25519.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/key/__tests__/DidKey.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/key/__tests__/KeyDidResolver.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/peer/__tests__/didPeer.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/peer/__tests__/peerDidNumAlgo0.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/peer/__tests__/peerDidNumAlgo1.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/peer/__tests__/peerDidNumAlgo2.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/dids/methods/sov/__tests__/SovDidResolver.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v1/MessagePickupService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v1/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v2/V2MessagePickupService.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v2/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/updates/0.1-0.2/__tests__/connection.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/updates/0.1-0.2/__tests__/credential.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/storage/migration/updates/0.1-0.2/__tests__/mediation.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/formats/indy/models/__tests__/IndyCredentialView.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/revocation-notification/services/__tests__/RevocationNotificationService.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/credentials/protocol/revocation-notification/util/__tests__/revocationIdentifier.test.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v1/handlers/BatchHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v1/handlers/BatchPickupHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v1/handlers/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v1/messages/BatchMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v1/messages/BatchPickupMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v1/messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v2/handlers/DeliveryRequestHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v2/handlers/MessageDeliveryHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v2/handlers/MessagesReceivedHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v2/handlers/StatusHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v2/handlers/StatusRequestHandler.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v2/handlers/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v2/messages/DeliveryRequestMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v2/messages/MessageDeliveryMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v2/messages/MessagesReceivedMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v2/messages/StatusMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v2/messages/StatusRequestMessage.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.
- `packages/core/src/modules/routing/protocol/pickup/v2/messages/index.ts`: The first 7 lines do not contain the pattern(s): Copyright, License.

### ⚠️ `package-metadata-exists` <a href="#user-content--package-metadata-exists" id="-package-metadata-exists">#</a>

Did not find a file matching the specified patterns. Below is a list of files or patterns that failed:

- `setup.py`
- `requirements.txt`

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

### ✅ `maintainers-file-exists` <a href="#user-content--maintainers-file-exists" id="-maintainers-file-exists">#</a>

Found file (`MAINTAINERS.md`).

### ✅ `contributing-file-exists` <a href="#user-content--contributing-file-exists" id="-contributing-file-exists">#</a>

Found file (`CONTRIBUTING.md`).

### ✅ `integrates-with-ci` <a href="#user-content--integrates-with-ci" id="-integrates-with-ci">#</a>

Found file (`.github/workflows/codeql-analysis.yml`).

### ✅ `changelog-file-exists` <a href="#user-content--changelog-file-exists" id="-changelog-file-exists">#</a>

Found file (`CHANGELOG.md`).

### ✅ `test-directory-exists` <a href="#user-content--test-directory-exists" id="-test-directory-exists">#</a>

Found file (`tests`).

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

</details>

