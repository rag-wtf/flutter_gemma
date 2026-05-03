# Graph Report - .  (2026-05-03)

## Corpus Check
- Large corpus: 395 files · ~912,654 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder, or use --no-semantic to run AST-only.

## Summary
- 3797 nodes · 8542 edges · 78 communities detected
- Extraction: 97% EXTRACTED · 3% INFERRED · 0% AMBIGUOUS · INFERRED: 242 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_TensorFlow.js Core|TensorFlow.js Core]]
- [[_COMMUNITY_Ffi Inference Model|Ffi Inference Model]]
- [[_COMMUNITY_LiteRT Web Runtime|LiteRT Web Runtime]]
- [[_COMMUNITY_Web Embedding Model|Web Embedding Model]]
- [[_COMMUNITY_SQLite Web Storage|SQLite Web Storage]]
- [[_COMMUNITY_Example App UI|Example App UI]]
- [[_COMMUNITY_JS Bridge Utils|JS Bridge Utils]]
- [[_COMMUNITY_TFJS Gradient Ops|TFJS Gradient Ops]]
- [[_COMMUNITY_Base Model Interface|Base Model Interface]]
- [[_COMMUNITY_Native FFI Integration|Native FFI Integration]]
- [[_COMMUNITY_Inference Model Implementation|Inference Model Implementation]]
- [[_COMMUNITY_LiteRT Web Core|LiteRT Web Core]]
- [[_COMMUNITY_JS Internal Utils|JS Internal Utils]]
- [[_COMMUNITY_Web Vector Store|Web Vector Store]]
- [[_COMMUNITY_Chat UI Components|Chat UI Components]]
- [[_COMMUNITY_Windows Plugin Registration|Windows Plugin Registration]]
- [[_COMMUNITY_Model Specification API|Model Specification API]]
- [[_COMMUNITY_Spec Creation Utils|Spec Creation Utils]]
- [[_COMMUNITY_Web Download Service|Web Download Service]]
- [[_COMMUNITY_JS Handler Registry|JS Handler Registry]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]
- [[_COMMUNITY_Community 22|Community 22]]
- [[_COMMUNITY_Community 23|Community 23]]
- [[_COMMUNITY_Community 24|Community 24]]
- [[_COMMUNITY_Community 25|Community 25]]
- [[_COMMUNITY_Community 26|Community 26]]
- [[_COMMUNITY_Community 27|Community 27]]
- [[_COMMUNITY_Community 28|Community 28]]
- [[_COMMUNITY_Community 29|Community 29]]
- [[_COMMUNITY_Community 30|Community 30]]
- [[_COMMUNITY_Community 31|Community 31]]
- [[_COMMUNITY_Community 32|Community 32]]
- [[_COMMUNITY_Community 33|Community 33]]
- [[_COMMUNITY_Community 34|Community 34]]
- [[_COMMUNITY_Community 35|Community 35]]
- [[_COMMUNITY_Community 36|Community 36]]
- [[_COMMUNITY_Community 37|Community 37]]
- [[_COMMUNITY_Community 38|Community 38]]
- [[_COMMUNITY_Community 39|Community 39]]
- [[_COMMUNITY_Community 40|Community 40]]
- [[_COMMUNITY_Community 41|Community 41]]
- [[_COMMUNITY_Community 42|Community 42]]
- [[_COMMUNITY_Community 43|Community 43]]
- [[_COMMUNITY_Community 44|Community 44]]
- [[_COMMUNITY_Community 45|Community 45]]
- [[_COMMUNITY_Community 46|Community 46]]
- [[_COMMUNITY_Community 47|Community 47]]
- [[_COMMUNITY_Community 48|Community 48]]
- [[_COMMUNITY_Community 49|Community 49]]
- [[_COMMUNITY_Community 50|Community 50]]
- [[_COMMUNITY_Community 51|Community 51]]
- [[_COMMUNITY_Community 52|Community 52]]
- [[_COMMUNITY_Community 53|Community 53]]
- [[_COMMUNITY_Community 54|Community 54]]
- [[_COMMUNITY_Community 55|Community 55]]
- [[_COMMUNITY_Community 56|Community 56]]
- [[_COMMUNITY_Community 57|Community 57]]
- [[_COMMUNITY_Community 58|Community 58]]
- [[_COMMUNITY_Community 59|Community 59]]
- [[_COMMUNITY_Community 60|Community 60]]
- [[_COMMUNITY_Community 61|Community 61]]
- [[_COMMUNITY_Community 62|Community 62]]
- [[_COMMUNITY_Community 63|Community 63]]
- [[_COMMUNITY_Community 64|Community 64]]
- [[_COMMUNITY_Community 65|Community 65]]
- [[_COMMUNITY_Community 66|Community 66]]
- [[_COMMUNITY_Community 67|Community 67]]
- [[_COMMUNITY_Community 89|Community 89]]
- [[_COMMUNITY_Community 90|Community 90]]
- [[_COMMUNITY_Community 91|Community 91]]
- [[_COMMUNITY_Community 92|Community 92]]
- [[_COMMUNITY_Community 93|Community 93]]
- [[_COMMUNITY_Community 94|Community 94]]
- [[_COMMUNITY_Community 95|Community 95]]
- [[_COMMUNITY_Community 96|Community 96]]
- [[_COMMUNITY_Community 97|Community 97]]
- [[_COMMUNITY_Community 98|Community 98]]

## God Nodes (most connected - your core abstractions)
1. `js()` - 498 edges
2. `E()` - 108 edges
3. `package:flutter_test/flutter_test.dart` - 80 edges
4. `package:flutter/foundation.dart` - 68 edges
5. `v()` - 65 edges
6. `package:flutter_gemma/flutter_gemma.dart` - 64 edges
7. `vr` - 62 edges
8. `wn` - 57 edges
9. `_()` - 56 edges
10. `Ss()` - 55 edges

## Surprising Connections (you probably didn't know these)
- `loadLiteRTModel()` --calls--> `loadAndCompile()`  [INFERRED]
  web/rag/litert_embeddings_api.js → example/web/litert.js
- `TC()` --calls--> `ua()`  [INFERRED]
  example/web/assets/sqlite_vector_store_worker-CfG9aZgP.js → example/web/tensorflow.js
- `TC()` --calls--> `ua()`  [INFERRED]
  example/web/assets/sqlite_vector_store_worker-gXbe1onm.js → example/web/tensorflow.js
- `maybeStopUnwind()` --calls--> `xa()`  [INFERRED]
  example/web/assets/sqlite_vector_store_worker-CfG9aZgP.js → example/web/tensorflow.js
- `maybeStopUnwind()` --calls--> `xa()`  [INFERRED]
  example/web/assets/sqlite_vector_store_worker-gXbe1onm.js → example/web/tensorflow.js

## Communities

### Community 0 - "TensorFlow.js Core"
Cohesion: 0.01
Nodes (448): _(), $0(), a0(), a1, Ab(), af(), ag(), ai (+440 more)

### Community 1 - "Ffi Inference Model"
Cohesion: 0.01
Nodes (439): base_model.dart, ../core/di/service_registry.dart, ../core/domain/model_source.dart, ../core/ffi/ffi_inference_model.dart, ../core/ffi/litert_lm_client.dart, ../core/model.dart, ../core/model_management/constants/preferences_keys.dart, ../core/services/model_repository.dart (+431 more)

### Community 2 - "LiteRT Web Runtime"
Cohesion: 0.01
Nodes (229): _(), $A(), aC, ag(), allocate(), allocateData(), analyzePath(), AQ() (+221 more)

### Community 3 - "Web Embedding Model"
Cohesion: 0.01
Nodes (296): dart:async, flutter_gemma_web_embedding_model.dart, TestPreferences, EmbeddingInstallation, EmbeddingInstallationBuilder, _extractFilename, Function, modelFromAsset (+288 more)

### Community 4 - "SQLite Web Storage"
Cohesion: 0.01
Nodes (176): fsync(), put_char(), _(), aC, ag(), allocate(), allocateData(), analyzePath() (+168 more)

### Community 5 - "Example App UI"
Cohesion: 0.01
Nodes (229): AlertDialog, build, _buildAudioSupportInfo, _buildErrorBanner, _buildImageSupportInfo, ChatScreen, ChatScreenState, Container (+221 more)

### Community 6 - "JS Bridge Utils"
Cohesion: 0.04
Nodes (171): $A(), dI(), iA(), mA(), OA(), AB(), Ag(), allocate() (+163 more)

### Community 7 - "TFJS Gradient Ops"
Cohesion: 0.02
Nodes (16): Aa, Ae(), Do, em, $i, Io(), ix, nm (+8 more)

### Community 8 - "Base Model Interface"
Cohesion: 0.02
Nodes (91): dart:js_interop, dart:js_interop_unsafe, BaseModel, EmbeddingModelInterface, InferenceModelInterface, ArgumentError, _cosineSimilarity, _createTable (+83 more)

### Community 9 - "Native FFI Integration"
Cohesion: 0.02
Nodes (91): dart:ffi, dart:isolate, Function, main, testEngine, Function, main, runTest (+83 more)

### Community 10 - "Inference Model Implementation"
Cohesion: 0.02
Nodes (82): ../chat.dart, ../extensions.dart, ../flutter_gemma_interface.dart, _assertNotClosed, FfiInferenceModel, FfiInferenceModelSession, _logGenerationStats, StateError (+74 more)

### Community 11 - "LiteRT Web Core"
Cohesion: 0.08
Nodes (66): generateDocumentEmbeddingInternal(), generateEmbeddingInternal(), loadLiteRTModel(), loadSentencePieceTokenizer(), preprocessDocumentForEmbedding(), preprocessTextForEmbedding(), _(), A() (+58 more)

### Community 12 - "JS Internal Utils"
Cohesion: 0.07
Nodes (12): B(), bx(), cx, og(), Ss(), Sw, sx, ts() (+4 more)

### Community 13 - "Web Vector Store"
Cohesion: 0.05
Nodes (15): SQLiteVectorStore, _(), F(), W(), y(), clearAll(), deleteModel(), downloadToOPFS() (+7 more)

### Community 14 - "Chat UI Components"
Cohesion: 0.05
Nodes (40): build, _buildAudioPreview, _buildImagePreview, _buildRecordingIndicator, ChatInputField, ChatInputFieldState, _clearAudio, _clearImage (+32 more)

### Community 15 - "Windows Plugin Registration"
Cohesion: 0.11
Nodes (19): RegisterPlugins(), FlutterWindow(), OnCreate(), Create(), Destroy(), EnableFullDpiSupportIfAvailable(), GetClientArea(), GetThisFromHandle() (+11 more)

### Community 16 - "Model Specification API"
Cohesion: 0.07
Nodes (26): ArgumentError, _cleanupAllTasksOfType, createBundledEmbeddingSpec, createBundledInferenceSpec, createEmbeddingSpec, createInferenceSpec, deleteModel, _detectModelType (+18 more)

### Community 17 - "Spec Creation Utils"
Cohesion: 0.1
Nodes (19): ArgumentError, createBundledEmbeddingSpec, createBundledInferenceSpec, createEmbeddingSpec, createInferenceSpec, deleteModel, DownloadProgress, EmbeddingModelSpec (+11 more)

### Community 18 - "Web Download Service"
Cohesion: 0.13
Nodes (15): ../../domain/web_storage_mode.dart, BackgroundDownloaderService, createDownloadService, createDownloadService, WebDownloadService, ../../infrastructure/background_downloader_service.dart, ../../infrastructure/blob_url_manager.dart, ../../infrastructure/web_cache_interop_stub.dart (+7 more)

### Community 19 - "JS Handler Registry"
Cohesion: 0.2
Nodes (2): fe, it

### Community 20 - "Community 20"
Cohesion: 0.28
Nodes (1): tr()

### Community 21 - "Community 21"
Cohesion: 0.14
Nodes (4): fl_register_plugins(), main(), my_application_activate(), my_application_new()

### Community 22 - "Community 22"
Cohesion: 0.15
Nodes (12): add, ArgumentError, clear, _cosineSimilarity, DocumentEmbedding, HnswSearchResult, HnswVectorIndex, rebuild (+4 more)

### Community 23 - "Community 23"
Cohesion: 0.19
Nodes (1): Ng

### Community 24 - "Community 24"
Cohesion: 0.33
Nodes (11): addDocument(), blobToEmbedding(), clear(), close(), cosineSimilarity(), embeddingToBlob(), getAllDocumentsWithEmbeddings(), getDocumentsByIds() (+3 more)

### Community 25 - "Community 25"
Cohesion: 0.21
Nodes (6): addDocument(), blobToEmbedding(), cosineSimilarity(), embeddingToBlob(), getAllDocumentsWithEmbeddings(), searchSimilar()

### Community 26 - "Community 26"
Cohesion: 0.18
Nodes (10): clearAll, deleteModel, downloadToOPFS, Function, getCachedModelSize, getStorageStats, getStreamReader, isModelCached (+2 more)

### Community 27 - "Community 27"
Cohesion: 0.18
Nodes (10): File, FileSystemException, getBaseName, getCorrectedPath, getMinimumSize, isSmallFile, ModelFileSystemManager, ModelStorageException (+2 more)

### Community 28 - "Community 28"
Cohesion: 0.2
Nodes (9): CanceledError, DownloadError, ForbiddenError, NetworkError, NotFoundError, RateLimitedError, ServerError, UnauthorizedError (+1 more)

### Community 29 - "Community 29"
Cohesion: 0.25
Nodes (7): FileNameUtils, getBaseName, getExtension, getMinimumSize, hasValidExtension, isFileValid, isSmallFile

### Community 30 - "Community 30"
Cohesion: 0.25
Nodes (7): BlobUrlManager, cleanup, cleanupAll, cleanupByUrl, isTracking, track, UnsupportedError

### Community 31 - "Community 31"
Cohesion: 0.29
Nodes (6): FunctionCallResponse, ModelResponse, ParallelFunctionCallResponse, TextResponse, ThinkingResponse, toString

### Community 32 - "Community 32"
Cohesion: 0.29
Nodes (6): createBlobUrl, revokeBlobUrl, StorageQuota, toString, UnsupportedError, WebCacheInterop

### Community 33 - "Community 33"
Cohesion: 0.29
Nodes (6): _extractFilenameFromSource, InferenceModelFile, InferenceModelSpec, LoraModelFile, _sourceToUrl, _urlToSource

### Community 34 - "Community 34"
Cohesion: 0.52
Nodes (1): kb

### Community 35 - "Community 35"
Cohesion: 0.29
Nodes (2): FlutterAppDelegate, AppDelegate

### Community 36 - "Community 36"
Cohesion: 0.29
Nodes (4): RunnerTests, RunnerUITests, -testFlutterIntegrationTest, XCTestCase

### Community 37 - "Community 37"
Cohesion: 0.48
Nodes (7): EmbeddingInstallationBuilder, FlutterGemma, ServiceRegistry, DartVectorStoreRepository, HnswVectorIndex, WebVectorStoreRepository, VectorStoreRepository

### Community 38 - "Community 38"
Cohesion: 0.33
Nodes (5): download_error.dart, DownloadException, toString, toTitle, toUserMessage

### Community 39 - "Community 39"
Cohesion: 0.33
Nodes (5): ModelDownloadException, ModelException, ModelStorageException, ModelValidationException, toString

### Community 40 - "Community 40"
Cohesion: 0.53
Nodes (1): y0

### Community 41 - "Community 41"
Cohesion: 0.6
Nodes (1): vw

### Community 42 - "Community 42"
Cohesion: 0.47
Nodes (4): wWinMain(), CreateAndAttachConsole(), GetCommandLineArguments(), Utf8FromUtf16()

### Community 43 - "Community 43"
Cohesion: 0.33
Nodes (3): RegisterGeneratedPlugins(), NSWindow, MainFlutterWindow

### Community 44 - "Community 44"
Cohesion: 0.4
Nodes (4): DownloadProgress, ModelFile, ModelSpec, toString

### Community 45 - "Community 45"
Cohesion: 0.4
Nodes (4): ResumeChecker, ResumeRecommendation, _summarizeResumeResults, toString

### Community 46 - "Community 46"
Cohesion: 0.6
Nodes (1): Wt

### Community 47 - "Community 47"
Cohesion: 0.4
Nodes (5): config.json, config.json.example, Gemma Models, HuggingFace Token, Meta Models

### Community 48 - "Community 48"
Cohesion: 0.5
Nodes (3): OrphanedFileInfo, StorageStats, toString

### Community 49 - "Community 49"
Cohesion: 0.5
Nodes (3): EmbeddingModelFile, EmbeddingModelSpec, EmbeddingTokenizerFile

### Community 50 - "Community 50"
Cohesion: 0.5
Nodes (3): bundledPath, externalPath, PreferencesKeys

### Community 51 - "Community 51"
Cohesion: 0.5
Nodes (3): _assertNotClosed, MobileEmbeddingModel, StateError

### Community 52 - "Community 52"
Cohesion: 0.5
Nodes (3): _assertNotClosed, DesktopEmbeddingModel, StateError

### Community 53 - "Community 53"
Cohesion: 0.67
Nodes (4): LiteRT Core, LiteRT Embeddings, SentencePiece, TensorFlow.js

### Community 54 - "Community 54"
Cohesion: 0.67
Nodes (2): LiteRtLmFfiClient, UnsupportedError

### Community 55 - "Community 55"
Cohesion: 0.67
Nodes (2): CacheMetadata, toString

### Community 56 - "Community 56"
Cohesion: 0.67
Nodes (2): MobileInferenceModel, StateError

### Community 57 - "Community 57"
Cohesion: 0.67
Nodes (2): createFile, UnsupportedError

### Community 58 - "Community 58"
Cohesion: 0.67
Nodes (2): DesktopEmbeddingModel, MobileEmbeddingModel

### Community 59 - "Community 59"
Cohesion: 0.67
Nodes (3): OPFS Helper, SQLite VectorStore Web Worker, SQLiteVectorStore

### Community 60 - "Community 60"
Cohesion: 1.0
Nodes (1): Tool

### Community 61 - "Community 61"
Cohesion: 1.0
Nodes (1): EmbeddingModel

### Community 62 - "Community 62"
Cohesion: 1.0
Nodes (1): AppKeys

### Community 63 - "Community 63"
Cohesion: 1.0
Nodes (1): MainActivity

### Community 64 - "Community 64"
Cohesion: 1.0
Nodes (1): MainActivity

### Community 65 - "Community 65"
Cohesion: 1.0
Nodes (1): MainActivityTest

### Community 66 - "Community 66"
Cohesion: 1.0
Nodes (1): package:integration_test/integration_test_driver.dart

### Community 67 - "Community 67"
Cohesion: 1.0
Nodes (2): LiteRTWebEmbeddings, WebEmbeddingModel

### Community 89 - "Community 89"
Cohesion: 1.0
Nodes (1): Public Models

### Community 90 - "Community 90"
Cohesion: 1.0
Nodes (1): Local Models

### Community 91 - "Community 91"
Cohesion: 1.0
Nodes (1): flutter_lints

### Community 92 - "Community 92"
Cohesion: 1.0
Nodes (1): Gemma 3 Logo

### Community 93 - "Community 93"
Cohesion: 1.0
Nodes (1): Gemma Logo

### Community 94 - "Community 94"
Cohesion: 1.0
Nodes (1): DeepSeek Logo

### Community 95 - "Community 95"
Cohesion: 1.0
Nodes (1): DeepSeek Logo with Background

### Community 96 - "Community 96"
Cohesion: 1.0
Nodes (1): Flutter + Gemma Logo (Light)

### Community 97 - "Community 97"
Cohesion: 1.0
Nodes (1): Flutter + Gemma Logo (Dark)

### Community 98 - "Community 98"
Cohesion: 1.0
Nodes (1): Cache API Wrapper

## Knowledge Gaps
- **1373 isolated node(s):** `RetrievalResult`, `VectorStoreStats`, `DocumentWithEmbedding`, `_PigeonCodec`, `PlatformService` (+1368 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `JS Handler Registry`** (15 nodes): `fe`, `.constructor()`, `.getHandlers()`, `.getInstance()`, `.getLoadHandlers()`, `.getSaveHandlers()`, `.registerLoadRouter()`, `.registerSaveRouter()`, `.constructor()`, `it`, `.constructor()`, `.getInstance()`, `.getManager()`, `.getSchemes()`, `.registerManager()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 20`** (15 nodes): `tr()`, `.calculateFirstParentOutputIndex()`, `.calculateOutputIndex()`, `.calculateOutputIndexRowSplit()`, `.calculateOutputIndexValueRowID()`, `.calculateOutputSize()`, `.compute()`, `.getFirstDimensionSize()`, `.getMaxWidth()`, `.getMaxWidthRowSplit()`, `.getMaxWidthValueRowID()`, `.getRowPartitionTensor()`, `.getRowPartitionTypeByDimension()`, `.setOutput()`, `.tensorShapeFromTensor()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 23`** (13 nodes): `Ng`, `.constructor()`, `.get_adjusted_ptr()`, `.get_caught()`, `.get_destructor()`, `.get_rethrown()`, `.get_type()`, `.init()`, `.set_adjusted_ptr()`, `.set_caught()`, `.set_destructor()`, `.set_rethrown()`, `.set_type()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 34`** (7 nodes): `kb`, `.constructor()`, `.getDepthCoordString()`, `.getHeightCoordString()`, `.getInputSamplingString()`, `.getOutputDepthSize()`, `.getWidthCoordString()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 35`** (7 nodes): `AppDelegate.swift`, `AppDelegate.swift`, `FlutterAppDelegate`, `AppDelegate`, `.application()`, `.applicationShouldTerminateAfterLastWindowClosed()`, `.applicationSupportsSecureRestorableState()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 40`** (6 nodes): `y0`, `.compute()`, `.constructor()`, `.createNGrams()`, `.getNumNGrams()`, `.getPadWidth()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 41`** (6 nodes): `vw`, `.constructor()`, `.getOutOfBoundsCondition()`, `.getOutput()`, `.getSetup()`, `.getSourceCoordsArr()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 46`** (5 nodes): `Wt`, `.constructor()`, `.databaseAction()`, `.load()`, `.save()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 54`** (3 nodes): `LiteRtLmFfiClient`, `UnsupportedError`, `litert_lm_client_stub.dart`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 55`** (3 nodes): `CacheMetadata`, `toString`, `cache_metadata.dart`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 56`** (3 nodes): `MobileInferenceModel`, `StateError`, `flutter_gemma_mobile_inference_model.dart`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 57`** (3 nodes): `platform_io_web.dart`, `createFile`, `UnsupportedError`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 58`** (3 nodes): `DesktopEmbeddingModel`, `MobileEmbeddingModel`, `embedding_models.dart`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 60`** (2 nodes): `Tool`, `tool.dart`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 61`** (2 nodes): `EmbeddingModel`, `embedding_models.dart`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 62`** (2 nodes): `app_keys.dart`, `AppKeys`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 63`** (2 nodes): `MainActivity.kt`, `MainActivity`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 64`** (2 nodes): `MainActivity.kt`, `MainActivity`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 65`** (2 nodes): `MainActivityTest.java`, `MainActivityTest`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 66`** (2 nodes): `integration_test.dart`, `package:integration_test/integration_test_driver.dart`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 67`** (2 nodes): `LiteRTWebEmbeddings`, `WebEmbeddingModel`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 89`** (1 nodes): `Public Models`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 90`** (1 nodes): `Local Models`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 91`** (1 nodes): `flutter_lints`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 92`** (1 nodes): `Gemma 3 Logo`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 93`** (1 nodes): `Gemma Logo`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 94`** (1 nodes): `DeepSeek Logo`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 95`** (1 nodes): `DeepSeek Logo with Background`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 96`** (1 nodes): `Flutter + Gemma Logo (Light)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 97`** (1 nodes): `Flutter + Gemma Logo (Dark)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 98`** (1 nodes): `Cache API Wrapper`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `package:flutter/foundation.dart` connect `Ffi Inference Model` to `Web Embedding Model`, `Example App UI`, `Base Model Interface`, `Native FFI Integration`, `Inference Model Implementation`, `Chat UI Components`?**
  _High betweenness centrality (0.087) - this node is a cross-community bridge._
- **Why does `js()` connect `TensorFlow.js Core` to `LiteRT Web Runtime`, `Community 34`, `SQLite Web Storage`, `JS Bridge Utils`, `TFJS Gradient Ops`, `Community 40`, `Community 41`, `JS Internal Utils`, `Web Vector Store`, `Community 46`, `JS Handler Registry`, `Community 20`?**
  _High betweenness centrality (0.065) - this node is a cross-community bridge._
- **Why does `package:flutter_gemma/flutter_gemma.dart` connect `Ffi Inference Model` to `Web Embedding Model`, `Example App UI`, `Chat UI Components`?**
  _High betweenness centrality (0.037) - this node is a cross-community bridge._
- **Are the 57 inferred relationships involving `v()` (e.g. with `L()` and `g()`) actually correct?**
  _`v()` has 57 INFERRED edges - model-reasoned connections that need verification._
- **What connects `RetrievalResult`, `VectorStoreStats`, `DocumentWithEmbedding` to the rest of the system?**
  _1373 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `TensorFlow.js Core` be split into smaller, more focused modules?**
  _Cohesion score 0.01 - nodes in this community are weakly interconnected._
- **Should `Ffi Inference Model` be split into smaller, more focused modules?**
  _Cohesion score 0.01 - nodes in this community are weakly interconnected._