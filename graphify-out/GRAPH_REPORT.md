# Graph Report - oracle  (2026-10-23)

## Corpus Check
- 46 semantic source files; AST status: extracted. Exclusions and reuse evidence: build-audit.json.

## Summary
- 2808 nodes · 7821 edges · 169 communities (118 shown, 51 thin omitted)
- Extraction: 98% EXTRACTED · 2% INFERRED · 0% AMBIGUOUS · INFERRED: 124 edges (avg confidence: 0.85)
- Token usage: per-project usage unavailable (native Codex semantic extraction).

## Graph Freshness
- Built from commit: `bc66fad8`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- browser/index.ts
- executor.ts
- oracle.ts
- chatgptFiles.ts
- modelSelection.ts
- liveTabs.ts
- deepResearch.ts
- build-docs-site.mjs
- run.ts
- vitest
- sessionManager.ts
- oracle/types.ts
- cli/sessionRunner.ts
- assistantResponse.ts
- delay
- thinkingStatus.ts
- oracle-cli.ts
- sessionStore.ts
- files.ts
- projectSourcesRunner.ts
- browser/types.ts
- consult.ts
- modelResolver.ts
- reattach.ts
- package.json
- sessionDisplay.ts
- notifier.ts
- actions/projectSources.ts
- browser-manual-login-live.test.ts
- navigation.ts
- helpers.ts
- options.ts
- ModelName
- runRootCommand
- rules
- scripts
- integrationCli.test.ts
- perfTrace.ts
- bridge/client.ts
- chromeLifecycle.ts
- dryRun.ts
- runOptions.ts
- dependencies
- detect.ts
- runner.ts
- prompt.ts
- tui/index.ts
- compilerOptions
- ref_node_child_process
- src/config.ts
- browserDefaults.ts
- remote/server.ts
- markdownRenderer.ts
- getCliVersion
- movePathsToTrash
- promptComposerExpressions.test.ts
- cli/projectSources.ts
- browserSessionManager.ts
- docsCheck.ts
- providerFailures.ts
- zipBundle.ts
- chalk
- sessionTable.ts
- git-policy.ts
- BrowserLogger
- doctor.ts
- tabLeaseRegistry.ts
- devDependencies
- browser-tools.ts
- followup.ts
- chatgptImages.test.ts
- mcp/server.ts
- stripWrappersAndAssignments
- cookies.ts
- showStatus
- tagline.ts
- compilerOptions
- BrowserAttachment
- browserConfig.ts
- markdown.ts
- FileSessionStore
- runCommand
- browser/config.ts
- chatgptImage.ts
- rootAlias.ts
- tui/index.test.ts
- ref_node_process
- release.sh
- StoredRunOptions
- mcporter-sessions-live.test.ts
- Oracle CLI
- docs-list.ts
- host.ts
- clipboard.ts
- agent-send.ts
- test-browser.ts
- MockStream
- multi-live.test.ts
- help.ts
- MockStream
- Mythical Pro Agents
- Oracle quickstart
- Session lifecycle
- mcp/utils.ts
- browserGuard.pty.test.ts
- Oracle browser mode and recovery lifecycle
- Oracle MCP server tools and session resources
- OpenAI-compatible endpoints
- extract-chatgpt-response.ts
- errorUtils.ts
- hiddenAliases.ts
- win-dpapi.d.ts
- OpenRouter setup
- toasted-notifier.d.ts
- Oracle integration with coding agents
- Session completion notifications
- Proposed Oracle provider preflight, route plan and unified timeout semantics
- Oracle deterministic one-shot prompt/file bundles with local sessions
- OracleNotifier.swift
- bin
- repository
- chrome-remote-interface
- smoke-claude.sh
- pty.d.ts
- build-notifier.sh
- Host cookie loading fails fast; GUI session or Node20 retest suggested
- probe-cookies.tsx
- browser-smoke.sh
- browser-smoke-upload-only.sh
- oracle-local-browser.sh
- API costs require consent and secrets excluded from attachments
- oracle.d.ts
- Oracle operating notes
- Oracle icon: gold interwoven three-loop emblem in a teal circular medallion with circuit traces
- Oracle release history
- Anthropic adapter integration and limitations
- Windows-hosted browser bridge for Linux clients
- Chromium fork executable and cookie configuration
- Oracle CLI command and flag reference
- Layered JSON5 Oracle configuration
- sweet-cookie Windows DPAPI and Gemini required cookies; manual-login workaround
- Follow-up conversations and provider response lineage
- Gemini API and cookie-based web integration
- Experimental Grok Responses API integration
- Oracle overview and consult paths
- Oracle installation and optional provider credentials
- Linux browser environment notes
- Manual browser and live API verification checklist
- Parallel multi-model execution with isolated logs
- npm and Homebrew release checklist
- Oracle social card: ask.oracle.dev, purple orbital eye motif, prompt agent marketing, GPT-5.5 Pro/Gemini 3 Pro/Claude Opus/Deep Research and Homebrew installation command
- Oracle social card
- Unit type browser API Gemini and MCP testing lanes
- Four validation lanes: CLI API/browser, mcporter MCP and Claude MCP
- Selectable first row and disabled headers mitigate TUI selector crash
- Windows app-bound cookie decryption favors persistent manual-login profile
- Windows browser flakiness, live DevTools URL and shell helper incompatibility
- Weekly grouped Dependabot updates
- Cross-platform Node 24 CI checks
- GitHub Pages documentation deployment
- Release-triggered Homebrew tap update workflow
- Workspace overrides for devtools-protocol and Vite
- Oracle wordmark
- Oracle banner: teal orb, gold Celtic knot and circuit motif
- Signed arm64 macOS notification helper with optional notarization and fallback

## God Nodes (most connected - your core abstractions)
1. `vitest` - 159 edges
2. `runBrowserMode()` - 99 edges
3. `delay()` - 76 edges
4. `runRemoteBrowserMode()` - 63 edges
5. `runRootCommand()` - 60 edges
6. `runOracle()` - 52 edges
7. `BrowserLogger` - 44 edges
8. `SessionMetadata` - 43 edges
9. `performSessionRun()` - 43 edges
10. `SessionStore` - 37 edges

## Surprising Connections (you probably didn't know these)
- `addProjectSourcesCommonOptions()` --indirect_call--> `parseIntOption()`  [INFERRED]
  bin/oracle-cli.ts → src/cli/options.ts
- `MockStream` --implements--> `ResponseStreamLike`  [EXTRACTED]
  tests/cli/runOracle/helpers.ts → src/oracle/types.ts
- `MockClient` --references--> `OracleRequestBody`  [EXTRACTED]
  tests/cli/runOracle/helpers.ts → src/oracle/types.ts
- `CliOptions` --references--> `EngineMode`  [EXTRACTED]
  bin/oracle-cli.ts → src/cli/engine.ts
- `CliOptions` --references--> `ApiProviderMode`  [EXTRACTED]
  bin/oracle-cli.ts → src/oracle/types.ts

## Import Cycles
- None detected.

## Communities (169 total, 51 thin omitted)

### Community 0 - "browser/index.ts"
Cohesion: 0.05
Nodes (88): clearComposerAttachments(), waitForResearchPlanAutoConfirm(), installJavaScriptDialogAutoDismissal(), appendArtifacts(), saveBrowserTranscriptArtifact(), collectGeneratedImageArtifacts(), closeRemoteChromeTarget(), connectToRemoteChrome() (+80 more)

### Community 1 - "executor.ts"
Cohesion: 0.05
Nodes (67): joinSelectors(), runProviderDomFlow(), chatgptDomProvider, asSelectorLiteral(), extractThoughts(), GEMINI_DEEP_THINK_SELECTORS, geminiDeepThinkDomProvider, GeminiDomProviderState (+59 more)

### Community 2 - "oracle.ts"
Cohesion: 0.08
Nodes (41): openai, runApiDryRun(), buildMarkdownBundle(), MarkdownBundle, sanitizeMultiModelFailureForThrow(), HeartbeatConfig, startHeartbeat(), asRetryableTransportError() (+33 more)

### Community 3 - "chatgptFiles.ts"
Cohesion: 0.07
Nodes (61): isToolOnlyPlaceholder(), normalizeSessionId(), pathExists(), readSizeBytes(), resolveSessionArtifactsDir(), resolveUniquePath(), sanitizePathSegment(), saveDeepResearchReportArtifact() (+53 more)

### Community 4 - "modelSelection.ts"
Cohesion: 0.05
Nodes (39): assertResolvedModelSelection(), assertResolvedModelSelectionForTest(), buildComposerSignalMatchers(), buildComposerSignalMatchersForTest(), buildModelMatchersLiteral(), buildModelMatchersLiteralForTest(), buildModelSelectionExpression(), buildModelSelectionExpressionForTest() (+31 more)

### Community 5 - "liveTabs.ts"
Cohesion: 0.09
Nodes (53): buildTabInspectionExpression(), buildTargetFingerprint(), ChatGptTabSummary, ChromeTarget, classifyTabState(), collectChatGptTabs(), connectToExistingChatGptTab(), connectToTarget() (+45 more)

### Community 6 - "deepResearch.ts"
Cohesion: 0.07
Nodes (52): activateDeepResearch(), ActivateOutcome, buildActivateDeepResearchExpression(), buildActivateDeepResearchExpressionForTest(), buildDeepResearchCompletionPollExpression(), buildDeepResearchCompletionPollExpressionForTest(), buildDeepResearchFrameStatusExpression(), buildDeepResearchFrameStatusExpressionForTest() (+44 more)

### Community 7 - "build-docs-site.mjs"
Cohesion: 0.07
Nodes (52): allHtml(), allMarkdown(), allPages, buildExcludes, cname, docsDir, docsInstallHint(), docsLlmsPages() (+44 more)

### Community 8 - "run.ts"
Cohesion: 0.09
Nodes (44): firstNonEmpty(), printProviderPlans(), ProviderDoctorCliOptions, resolveAzureOptions(), resolveModels(), resolveProviderMode(), runProviderDoctor(), isCustomBaseUrl() (+36 more)

### Community 9 - "vitest"
Cohesion: 0.12
Nodes (17): vitest, zod, PROJECT_CONFIG_RELATIVE_PATH, setOracleHomeDirOverrideForTest(), ansiRegex, tempDirs, model, isOpenRouterBase (+9 more)

### Community 10 - "sessionManager.ts"
Cohesion: 0.10
Nodes (48): safeModelSlug(), TransportFailureReason, attachModelRuns(), countSlugWords(), createSessionId(), createSessionLogWriter(), ensureModelLogReference(), fileExists() (+40 more)

### Community 11 - "oracle/types.ts"
Cohesion: 0.08
Nodes (30): @google/genai, callClaude(), createClaudeClient(), extractPrompt(), parseClaudeResponse(), resolveClaudeModelId(), buildAzureResponsesBaseUrl(), buildOpenRouterCompletionClient() (+22 more)

### Community 12 - "cli/sessionRunner.ts"
Cohesion: 0.09
Nodes (38): kleur, ensureSessionArtifacts(), runBrowserSessionExecution(), formatBrowserReattachGuidance(), autoReattachUntilComplete(), buildFallbackPath(), buildMultiModelOutputManifest(), calculateModelElapsedMs() (+30 more)

### Community 13 - "assistantResponse.ts"
Cohesion: 0.11
Nodes (39): AssistantSnapshot, buildActiveThinkingStatusPredicateJs(), buildActiveThinkingStatusPredicateJsForTest(), buildAssistantExtractor(), buildAssistantExtractorForTest(), buildAssistantSnapshotExpression(), buildAssistantSnapshotExpressionForTest(), buildConversationDebugExpressionForTest() (+31 more)

### Community 14 - "delay"
Cohesion: 0.12
Nodes (30): guessMimeType(), transferAttachmentViaDataTransfer(), buildUserTurnAttachmentExpression(), uploadAttachmentFile(), waitForAttachmentAnchored(), waitForAttachmentCompletion(), waitForAttachmentVisible(), waitForUserTurnAttachments() (+22 more)

### Community 15 - "thinkingStatus.ts"
Cohesion: 0.09
Nodes (24): buildThinkingStatusExpression(), buildThinkingStatusExpressionForTest, buildThinkingStatusFingerprint(), formatThinkingLog(), formatThinkingWaitingLog(), readThinkingStatus(), readThinkingStatusForTest, resolveThinkingStatusInterval() (+16 more)

### Community 16 - "oracle-cli.ts"
Cohesion: 0.07
Nodes (33): bridgeCommand, buildRunOptions(), CLI_ENTRYPOINT, CliOptions, docsArgIndex, docsCommand, doctorArgIndex, extractResponseIdFromSession() (+25 more)

### Community 17 - "sessionStore.ts"
Cohesion: 0.08
Nodes (16): DuplicatePromptGuardOptions, normalizeRunSignature(), shouldBlockDuplicatePrompt(), StatusTreeRow, SessionRunParams, BrowserHarvestMetadata, BrowserModelSelectionEvidenceStatus, filterSessionsByRange() (+8 more)

### Community 18 - "files.ts"
Cohesion: 0.10
Nodes (31): fast-glob, buildIgnoredWhitelist(), DEFAULT_FS, DEFAULT_IGNORED_DIRS, DEFAULT_MAX_FILE_SIZE_BYTES, expandDirectoryRecursive(), expandWithCustomFs(), expandWithNativeGlob() (+23 more)

### Community 19 - "projectSourcesRunner.ts"
Cohesion: 0.12
Nodes (35): openProjectSourcesTab(), waitForProjectSourcesListSettled(), waitForProjectSourcesReady(), registerTerminationHooks(), maybeReuseRunningChrome(), maybeReuseRunningChromeForTest(), acquireProfileRunLock(), cleanupStaleProfileState() (+27 more)

### Community 20 - "browser/types.ts"
Cohesion: 0.11
Nodes (32): BrowserExecutionResult, BrowserSessionRunnerDeps, buildBrowserRunWarnings(), buildBrowserRunWarningsForTest(), buildUnavailableModelSelectionEvidence(), formatModelSelectionEvidence(), isRequestedProBrowserRun(), RunBrowserSessionArgs (+24 more)

### Community 21 - "consult.ts"
Cohesion: 0.09
Nodes (32): applyConsultPreset(), buildConsultDryRunResolved(), ConsultArtifactSummary, consultArtifactSummaryShape, ConsultDryRunResolved, consultDryRunResolvedShape, ConsultImageSummary, consultImageSummaryShape (+24 more)

### Community 22 - "modelResolver.ts"
Cohesion: 0.10
Nodes (27): countTokensAnthropic(), countTokensGpt5(), countTokensGpt5Pro(), DEFAULT_MODEL, PRO_MODELS, require, TOKENIZER_OPTIONS, catalogCache (+19 more)

### Community 23 - "reattach.ts"
Cohesion: 0.13
Nodes (31): connectToChrome(), listRemoteChromeTargets(), inferPortFromBrowserWSEndpoint(), readPromptPreviewTurnIndex(), ReattachDeps, ReattachResult, refreshAttachRuntime(), resumeBrowserSession() (+23 more)

### Community 24 - "package.json"
Cohesion: 0.06
Nodes (33): author, bugs, url, description, devEngines, runtime, engines, node (+25 more)

### Community 25 - "sessionDisplay.ts"
Cohesion: 0.13
Nodes (31): attachSession(), buildReattachLine(), buildSessionLogForDisplay(), dim(), extractRenderableChunks(), formatBrowserEvidence(), formatBytes(), formatCompletionSummary() (+23 more)

### Community 26 - "notifier.ts"
Cohesion: 0.11
Nodes (27): toasted-notifier, buildMessage(), describeNotifierError(), escapeAppleScript(), fsExistsSync(), hasRosetta(), inferCost(), isMacBadCpuError() (+19 more)

### Community 27 - "actions/projectSources.ts"
Cohesion: 0.14
Nodes (28): buildMarkProjectSourcesUploadInputExpression(), buildOpenProjectSourcesAddDialogExpression(), buildOpenProjectSourcesTabExpression(), buildProjectSourcesConfirmationButtonExpression(), buildProjectSourcesDialogReadyExpression(), buildProjectSourcesListExpression(), buildProjectSourcesReadyExpression(), clickPoint() (+20 more)

### Community 28 - "browser-manual-login-live.test.ts"
Cohesion: 0.11
Nodes (13): @steipete/sweet-cookie, delay(), waitForDevToolsPort(), waitForPageTarget(), CASES, DEFAULT_PROJECT_URLS, acquireLiveTestLock(), isProcessRunning() (+5 more)

### Community 29 - "navigation.ts"
Cohesion: 0.12
Nodes (29): attemptWelcomeBackLogin(), buildLoginProbeExpression(), buildLoginProbeExpressionForTest(), buildWelcomeBackAccountPickerExpression(), buildWelcomeBackAccountPickerExpressionForTest(), conversationIdFromUrl(), currentUrl(), dismissBlockingUi() (+21 more)

### Community 30 - "helpers.ts"
Cohesion: 0.12
Nodes (15): BackgroundExecutionParams, BackgroundPollParams, RetrieveRetryParams, ClientLike, OracleResponse, ResponseStreamEvent, buildResponse(), createMockFs() (+7 more)

### Community 31 - "options.ts"
Cohesion: 0.14
Nodes (23): addProjectSourcesCommonOptions(), commander, collectModelList(), collectPaths(), collectTextValues(), dedupePathInputs(), inferModelFromLabel(), isGeminiDeepThinkAlias() (+15 more)

### Community 32 - "ModelName"
Cohesion: 0.11
Nodes (20): BrowserFollowupResolution, MultiModelOutputManifest, WizardAnswers, defaultDeps, describeLog(), forwardOscProgress(), fsStat(), ModelExecutionResult (+12 more)

### Community 33 - "runRootCommand"
Cohesion: 0.13
Nodes (23): assertFollowupSupported(), buildRunOptionsFromMetadata(), enforceBrowserSearchFlag(), executeSession(), firstNonEmpty(), formatRouteTargetForLog(), getBrowserConfigFromMetadata(), getSessionMode() (+15 more)

### Community 34 - "rules"
Cohesion: 0.07
Nodes (26): categories, correctness, perf, suspicious, ignorePatterns, plugins, rules, eslint/no-await-in-loop (+18 more)

### Community 35 - "scripts"
Cohesion: 0.07
Nodes (27): scripts, build, build:vendor, check, docs:check, docs:list, docs:site, format (+19 more)

### Community 36 - "integrationCli.test.ts"
Cohesion: 0.08
Nodes (14): child, cliEntry, here, rawArgs, readStdin(), resolveDashPrompt(), AZURE_ENV_KEYS, CLI_ENTRY (+6 more)

### Community 37 - "perfTrace.ts"
Cohesion: 0.11
Nodes (14): launchDetachedSession(), buildDetachedPerfTraceEnv(), createPerfTrace(), deriveDetachedPerfTraceEnv(), DisabledPerfTrace, FilePerfTrace, PerfTrace, PerfTraceEvent (+6 more)

### Community 38 - "bridge/client.ts"
Cohesion: 0.16
Nodes (19): json5, BridgeTunnelInfo, formatBridgeConnectionString(), looksLikePath(), normalizeHostPort(), parseBridgeConnectionString(), parseHostPort(), readBridgeConnectionArtifact() (+11 more)

### Community 39 - "chromeLifecycle.ts"
Cohesion: 0.12
Nodes (24): buildChromeFlags(), closeBlankChromeTabs(), connectToBrowserWebSocket(), connectToNewTarget(), connectToRemoteChromeTarget(), createSessionBoundChromeClient(), execFileAsync, formatApprovalWait() (+16 more)

### Community 40 - "dryRun.ts"
Cohesion: 0.16
Nodes (20): BrowserControlConfig, BrowserControlPlan, describeBrowserControlPlan(), formatBrowserControlPlan(), buildCookiePlan(), BrowserPromptArtifacts, buildTokenEstimateSuffix(), formatAttachmentLabel() (+12 more)

### Community 41 - "runOptions.ts"
Cohesion: 0.14
Nodes (20): resolveRestartWaitPreference(), resolveWaitFlag(), normalizeChatGptModelForBrowser(), shouldDetachSession(), defaultWaitPreference(), EngineMode, hasApiEnvironment(), normalizeEngineMode() (+12 more)

### Community 42 - "dependencies"
Cohesion: 0.08
Nodes (25): dependencies, @anthropic-ai/tokenizer, chalk, chrome-launcher, chrome-remote-interface, clipboardy, commander, dotenv (+17 more)

### Community 43 - "detect.ts"
Cohesion: 0.15
Nodes (21): AttachRunningConnectionInfo, compareDevToolsCandidates(), resolveAttachRunningConnection(), AttachRunningBrowserFamily, AttachRunningProfileRoot, deriveDevToolsProfileRoot(), detectChromeBinary(), DevToolsActivePortCandidate (+13 more)

### Community 44 - "runner.ts"
Cohesion: 0.11
Nodes (21): CommandInterceptionResult, EXTENDED_SCRIPT_KEYWORDS, formatSleepArgument(), formatSleepDuration(), GitRmPlan, isSleepBinary(), LINT_BINARIES, LONG_SCRIPT_KEYWORDS (+13 more)

### Community 45 - "prompt.ts"
Cohesion: 0.13
Nodes (19): ARCHIVE_EXTENSIONS, assembleBrowserPrompt(), AssemblePromptDeps, assertAttachmentCount(), BrowserBundleMetadata, BrowserBundleSource, formatSectionsForBundle(), isRawUploadFile() (+11 more)

### Community 46 - "tui/index.ts"
Cohesion: 0.16
Nodes (21): MAX_RENDER_BYTES, askOracleFlow(), Choice, dim(), fetchSessionBuckets(), getSessionLogPath(), isTty(), launchTui() (+13 more)

### Community 47 - "compilerOptions"
Cohesion: 0.09
Nodes (22): compilerOptions, allowImportingTsExtensions, allowJs, checkJs, esModuleInterop, forceConsistentCasingInFileNames, isolatedModules, jsx (+14 more)

### Community 48 - "ref_node_child_process"
Cohesion: 0.11
Nodes (6): chrome-launcher, repoRoot, tmpRoot, reusePaths, entry, TOKENIZER_STUB

### Community 49 - "src/config.ts"
Cohesion: 0.14
Nodes (20): BridgeClaudeConfigCliOptions, formatClaudeMcpConfig(), runBridgeClaudeConfig(), AzureConfig, configPath(), deepMerge(), discoverProjectConfigPaths(), EnginePreference (+12 more)

### Community 50 - "browserDefaults.ts"
Cohesion: 0.20
Nodes (16): archiveChatGptConversation(), BrowserArchiveDecision, buildArchiveConversationExpression(), buildArchiveConversationExpressionForTest(), isProjectChatgptUrl(), isTemporaryChatgptUrl(), resolveBrowserArchiveDecision(), BrowserArchiveMode (+8 more)

### Community 51 - "remote/server.ts"
Cohesion: 0.18
Nodes (17): normalizeChatgptUrl(), canSpawn(), createRemoteServer(), findAvailablePort(), formatReachableAddresses(), formatSocket(), isWsl(), loadLocalChatgptCookies() (+9 more)

### Community 52 - "markdownRenderer.ts"
Cohesion: 0.17
Nodes (16): markdansi, shiki, ensureShikiReady(), HIGHLIGHT_LANGS, HighlightLang, normalizeLanguage(), renderMarkdownAnsi(), ShikiHighlighter (+8 more)

### Community 53 - "getCliVersion"
Cohesion: 0.11
Nodes (13): getCliVersion(), readVersionFromPackage(), CLI_ENTRY, execFileAsync, CLI_ENTRY, execFileAsync, execFileAsync, execFileAsync (+5 more)

### Community 54 - "movePathsToTrash"
Cohesion: 0.13
Nodes (20): buildFindDeletePlan(), buildTrashTarget(), extractFindInvocation(), extractRmInvocation(), findTrashCliCommand(), formatTrashError(), getTrashDirectory(), isCrossDeviceError() (+12 more)

### Community 55 - "promptComposerExpressions.test.ts"
Cohesion: 0.16
Nodes (8): buildAttachmentReadyExpressionForTest(), evaluateAttachmentReadyExpression(), FakeDocument, FakeElement, FakeInputElement, flattenElements(), matchesSelector(), matchesSingleSelector()

### Community 56 - "cli/projectSources.ts"
Cohesion: 0.21
Nodes (15): resolveConfiguredMaxFileSizeBytes(), buildProjectSourcesBrowserConfig(), printProjectSourcesResult(), ProjectSourcesCliOptions, removeUndefined(), resolveProjectSourceFiles(), runProjectSourcesCliCommand(), projectSourceEntryShape (+7 more)

### Community 57 - "browserSessionManager.ts"
Cohesion: 0.20
Nodes (15): closeTab(), connectWithNewTab(), acquireManualLoginChromeForRun(), acquireManualLoginChromeForRunForTest(), verifyDevToolsReachable(), writeChromePid(), writeDevToolsActivePort(), GeminiBrowserSession (+7 more)

### Community 58 - "docsCheck.ts"
Cohesion: 0.18
Nodes (17): checkDocsFlags(), collectCommanderFlags(), collectCommandFlags(), DEFAULT_DOC_PATHS, DocsCheckIssue, DocsCheckResult, expandSlashFlagReferences(), extractMarkdownFlagReferences() (+9 more)

### Community 59 - "providerFailures.ts"
Cohesion: 0.20
Nodes (17): formatMultiModelFailureDetails(), classifyMessage(), classifyProviderFailure(), doctorCommand(), extractProviderMessage(), fixForCategory(), hasStatusCode(), inferFailureRoute() (+9 more)

### Community 60 - "zipBundle.ts"
Cohesion: 0.18
Nodes (16): assertZip16(), assertZip32(), centralDirectoryHeader(), crc32(), CRC32_TABLE, createStoredZip(), endOfCentralDirectory(), localFileHeader() (+8 more)

### Community 61 - "chalk"
Cohesion: 0.17
Nodes (12): chalk, BrowserHarvestOptions, BrowserLiveTailOptions, usesDefaultStatusFilters(), defaultDependencies, formatSessionCleanupMessage(), handleSessionCommand(), listIgnoredFlags() (+4 more)

### Community 62 - "sessionTable.ts"
Cohesion: 0.17
Nodes (16): tokentally, CHARS_PAD, colorStatus(), COST_PAD, dim(), formatCostTable(), formatSessionTableHeader(), formatSessionTableRow() (+8 more)

### Community 63 - "git-policy.ts"
Cohesion: 0.16
Nodes (16): analyzeGitExecution(), COMMIT_HELPER_SUBCOMMANDS, DESTRUCTIVE_SUBCOMMANDS, determineGitWorkdir(), evaluateGitPolicies(), extractGitInvocation(), findGitSubcommand(), GitCommandInfo (+8 more)

### Community 64 - "BrowserLogger"
Cohesion: 0.19
Nodes (14): PromptReadyNavigationOptions, AttachmentReadyExpectation, DomEvaluate, ProviderDomAdapter, ProviderDomFlowContext, ProviderDomFlowResult, ProviderDomResponse, ChatgptDomProviderState (+6 more)

### Community 65 - "doctor.ts"
Cohesion: 0.21
Nodes (13): detectChromeCookieDb(), resolveAttachRunningProfileRoots(), BridgeCodexConfigCliOptions, escapeTomlString(), formatCodexMcpSnippet(), runBridgeCodexConfig(), BridgeDoctorCliOptions, runBridgeDoctor() (+5 more)

### Community 66 - "tabLeaseRegistry.ts"
Cohesion: 0.29
Nodes (15): acquireBrowserTabLease(), BrowserTabLease, BrowserTabLeaseDeps, BrowserTabLeaseRecord, BrowserTabLeaseRegistryFile, hasOtherActiveBrowserTabLeases(), isLeaseRecord(), normalizeMaxConcurrentTabs() (+7 more)

### Community 67 - "devDependencies"
Cohesion: 0.12
Nodes (16): devDependencies, @anthropic-ai/tokenizer, devtools-protocol, es-toolkit, esbuild, oxfmt, oxlint, puppeteer-core (+8 more)

### Community 68 - "browser-tools.ts"
Cohesion: 0.17
Nodes (14): AsyncFunctionCtor, browserURL(), ChromeProcessInfo, ChromeSessionDescription, ChromeTabInfo, connectBrowser(), DEFAULT_PROFILE_DIR, describeChromeSessions() (+6 more)

### Community 69 - "followup.ts"
Cohesion: 0.24
Nodes (8): hasRecoverableChatGptConversation(), isRecoverableChatGptConversationUrl(), RecoveredConversation, resolveRecoveryUrl(), FollowupSessionReader, resolveBrowserFollowupReference(), resolveBrowserResumeConversationUrl(), baseMetadata

### Community 70 - "chatgptImages.test.ts"
Cohesion: 0.17
Nodes (4): evaluateImageExpression(), FakeElement, flattenElements(), matchesSelector()

### Community 71 - "mcp/server.ts"
Cohesion: 0.22
Nodes (10): dotenv, @modelcontextprotocol/sdk, shouldStartMcpServerFromModule(), startMcpServer(), registerConsultTool(), registerSessionResources(), registerSessionsTool(), sessionsInputShape (+2 more)

### Community 72 - "stripWrappersAndAssignments"
Cohesion: 0.20
Nodes (15): determineEffectiveTimeoutMs(), isSingleTestInvocation(), isSingleTestViaBun(), isSingleTestViaPnpm(), isTestRunnerSuiteInvocation(), matchesScriptKeyword(), shouldExtendForScript(), shouldExtendTimeout() (+7 more)

### Community 73 - "cookies.ts"
Cohesion: 0.24
Nodes (13): COOKIE_URLS, attachUrl(), ChromeCookieSyncError, normalizeExpiration(), normalizeInlineCookies(), readChromeCookies(), readChromeCookiesWithWait(), readDuration() (+5 more)

### Community 74 - "showStatus"
Cohesion: 0.20
Nodes (13): buildSessionChainLine(), buildStatusTreeRows(), formatLineageParentLabel(), matchesModel(), showStatus(), abbreviateResponseId(), buildResponseOwnerIndex(), collectSessionResponseIds() (+5 more)

### Community 75 - "tagline.ts"
Cohesion: 0.25
Nodes (13): activeTaglines(), formatIntroLine(), HOLIDAY_RULES, HolidayRule, inYearWindow(), isFourthThursdayOfNovember(), isTaglineActive(), onMonthDay() (+5 more)

### Community 76 - "compilerOptions"
Cohesion: 0.14
Nodes (13): ./tsconfig.json, compilerOptions, allowImportingTsExtensions, allowJs, declaration, emitDeclarationOnly, noEmit, outDir (+5 more)

### Community 77 - "BrowserAttachment"
Cohesion: 0.19
Nodes (11): AttachmentPlan, AttachmentSection, buildAttachmentPlan(), CookiePlan, WrittenBrowserBundle, BrowserAttachment, BrowserAutomationConfig, ProjectSourcesOperation (+3 more)

### Community 78 - "browserConfig.ts"
Cohesion: 0.27
Nodes (12): BROWSER_MODEL_LABELS, buildBrowserConfig(), mapModelToBrowserLabel(), parseCookieNames(), parseInlineCookiesPayload(), parseMaxConcurrentTabs(), parseRemoteChromeTarget(), resolveBrowserModelLabel() (+4 more)

### Community 79 - "markdown.ts"
Cohesion: 0.23
Nodes (12): addLineNumbers(), detectFenceLanguage(), EXT_TO_LANG, FenceLanguage, FileSectionInput, formatFileSection(), FormatFileSectionOptions, FormatFileSectionsOptions (+4 more)

### Community 80 - "FileSessionStore"
Cohesion: 0.18
Nodes (5): deleteSessionsOlderThan(), ensureDir(), ensureSessionStorage(), getSessionsDir(), FileSessionStore

### Community 81 - "runCommand"
Cohesion: 0.23
Nodes (13): buildExecutionParams(), exitCodeFromSignal(), formatCompletionSummary(), formatDisplayCommand(), formatDuration(), injectWorkspaceBinDirs(), isEnvAssignment(), isRunnerTmuxSession() (+5 more)

### Community 82 - "browser/config.ts"
Cohesion: 0.27
Nodes (10): DEFAULT_BROWSER_CONFIG, DEFAULT_CHATGPT_COOKIE_NAMES, normalizeArchiveMode(), normalizeResearchMode(), parseDebugPort(), resolveBrowserConfig(), resolveManualLoginProfileDir(), DEEP_RESEARCH_DEFAULT_TIMEOUT_MS (+2 more)

### Community 83 - "chatgptImage.ts"
Cohesion: 0.21
Nodes (10): appendAspectRatio(), buildChatGptImageConsultInput(), ChatGptImageInput, chatGptImageInputSchema, chatGptImageInputShape, chatGptImageOutputShape, registerChatGptImageTool(), resolveDefaultImageOutputPath() (+2 more)

### Community 84 - "rootAlias.ts"
Cohesion: 0.21
Nodes (9): defaultDeps, defaultSessionDeps, handleSessionAlias(), handleStatusFlag(), SessionAliasDependencies, SessionAliasOptions, StatusAliasDependencies, StatusAliasOptions (+1 more)

### Community 85 - "tui/index.test.ts"
Cohesion: 0.17
Nodes (11): createSessionLogWriterMock, ensureSessionStorageMock, getPathsMock, initializeSessionMock, listSessionsMock, performSessionRunMock, promptMock, pruneOldSessionsMock (+3 more)

### Community 86 - "ref_node_process"
Cohesion: 0.22
Nodes (6): osc-progress, buildConfig, BunBuildConfig, OscProgressOptions, startOscProgress(), supportsOscProgress()

### Community 87 - "release.sh"
Cohesion: 0.45
Nodes (10): banner(), main(), phase_artifacts(), phase_gates(), phase_publish(), phase_smoke(), phase_tag(), run() (+2 more)

### Community 88 - "StoredRunOptions"
Cohesion: 0.18
Nodes (8): PartialMode, InitializeSessionOptions, StoredRunOptions, filterSessions, listSessions, readLog, readRequest, readSession

### Community 89 - "mcporter-sessions-live.test.ts"
Cohesion: 0.20
Nodes (8): execFileAsync, hasOpenAI, isOpenRouterBase, MCP_CONFIG, McporterOutput, OPENAI_ENV, ORACLE_MCP_BIN, runMcporter()

### Community 90 - "Oracle CLI"
Cohesion: 0.20
Nodes (10): API and browser engines, Browser auto reattach, ChatGPT project sources, Manual login profile sharing and tab slots, MCP consult and image tools, Multimodel advisory panels and partial results, Oracle CLI, Prompt and file bundling (+2 more)

### Community 91 - "docs-list.ts"
Cohesion: 0.20
Nodes (8): es-toolkit, DOCS_DIR, docsListDir, docsListFile, EXCLUDED_DIRS, markdownFiles, walkMarkdownFiles(), relativePath()

### Community 92 - "host.ts"
Cohesion: 0.33
Nodes (9): BridgeConnectionArtifact, BridgeHostCliOptions, ReverseTunnelHandle, runBridgeHost(), spawnBridgeHostInBackground(), splitArgs(), startReverseTunnel(), upsertConnectionArtifact() (+1 more)

### Community 93 - "clipboard.ts"
Cohesion: 0.28
Nodes (5): clipboardy, CopyResult, copyToClipboard(), loadClipboard(), clipboardWrite

### Community 94 - "agent-send.ts"
Cohesion: 0.36
Nodes (7): CliOptions, ensureSession(), EntryMode, parseArgs(), runTmux(), sendMessage(), usage()

### Community 95 - "test-browser.ts"
Cohesion: 0.33
Nodes (6): fetchVersion(), firewallHint(), hostHint, isWsl(), main(), resolveWslHost()

### Community 96 - "MockStream"
Cohesion: 0.32
Nodes (3): makeResponse(), mockClientFactory(), MockStream

### Community 97 - "multi-live.test.ts"
Cohesion: 0.25
Nodes (5): CLI_ENTRY, execFileAsync, isOpenRouterBase, OPENAI_ENV, TSX_BIN

### Community 98 - "help.ts"
Cohesion: 0.43
Nodes (6): applyHelpStyling(), createColorWrapper(), HelpColors, renderHelpBanner(), renderHelpFooter(), Stylizer

### Community 100 - "Mythical Pro Agents"
Cohesion: 0.33
Nodes (6): Claude Opus 4.1, Deep Research, Mythical Pro Agents, Gemini 3.1 Pro, GPT-5.5 Pro, Multi-model triangulation

### Community 101 - "Oracle quickstart"
Cohesion: 0.33
Nodes (6): API mode, Browser mode, Oracle quickstart, Dry-run preview, Render mode, Session reattachment

### Community 102 - "Session lifecycle"
Cohesion: 0.33
Nodes (6): Background mode, Session lifecycle, Followup lineage, Pruning, Session storage, Zombie detection

### Community 103 - "mcp/utils.ts"
Cohesion: 0.60
Nodes (4): isExternalMcpOutputAllowed(), mapConsultToRunOptions(), resolveMcpOutputPath(), resolveThroughSymlinks()

### Community 104 - "browserGuard.pty.test.ts"
Cohesion: 0.33
Nodes (3): ansiRegex, CLI_ENTRY, TSX_BIN

### Community 105 - "Oracle browser mode and recovery lifecycle"
Cohesion: 0.40
Nodes (5): ChatGPT CDP, Deep Research, Oracle browser mode and recovery lifecycle, Gemini web, Session artifacts

### Community 106 - "Oracle MCP server tools and session resources"
Cohesion: 0.40
Nodes (5): chatgpt_image, consult, Oracle MCP server tools and session resources, project_sources, sessions

### Community 107 - "OpenAI-compatible endpoints"
Cohesion: 0.40
Nodes (5): Azure v1 Responses, OpenAI-compatible endpoints, Model aliases, OpenRouter, Provider diagnostics

### Community 108 - "extract-chatgpt-response.ts"
Cohesion: 0.40
Nodes (3): puppeteer-core, ExtractedMessage, port

### Community 110 - "errorUtils.ts"
Cohesion: 0.60
Nodes (3): isErrorLogged(), LOGGED_SYMBOL, markErrorLogged()

### Community 111 - "hiddenAliases.ts"
Cohesion: 0.60
Nodes (3): applyHiddenAliases(), HiddenAliasOptions, OptionSetter

### Community 112 - "win-dpapi.d.ts"
Cohesion: 0.40
Nodes (3): DpapiModule, Scope, win-dpapi

### Community 113 - "OpenRouter setup"
Cohesion: 0.50
Nodes (4): Attribution headers, OpenRouter setup, Model catalog, Provider key precedence

### Community 116 - "Oracle integration with coding agents"
Cohesion: 0.67
Nodes (3): Browser consult, Oracle integration with coding agents, Oracle MCP

### Community 117 - "Session completion notifications"
Cohesion: 0.67
Nodes (3): CI and SSH suppression, Session completion notifications, OracleNotifier.app

### Community 118 - "Proposed Oracle provider preflight, route plan and unified timeout semantics"
Cohesion: 0.67
Nodes (3): Packed CLI help tests prevent documented flag drift, Proposed partial-success output manifests and classified errors, Proposed Oracle provider preflight, route plan and unified timeout semantics

### Community 119 - "Oracle deterministic one-shot prompt/file bundles with local sessions"
Cohesion: 0.67
Nodes (3): Oracle deterministic one-shot prompt/file bundles with local sessions, Explicit engine then layered config then keys select API or browser, Stable session states and semver CLI contracts

### Community 121 - "bin"
Cohesion: 0.67
Nodes (3): bin, oracle, oracle-mcp

### Community 122 - "repository"
Cohesion: 0.67
Nodes (3): repository, type, url

## Knowledge Gaps
- **102 isolated node(s):** `./src/browser/chromeCookies.ts`, `Foundation`, `OPENAI_API_KEY`, `UserNotifications`, `@anthropic-ai/tokenizer` (+97 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 820 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **51 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `vitest` connect `vitest` to `browser/index.ts`, `executor.ts`, `oracle.ts`, `modelSelection.ts`, `liveTabs.ts`, `deepResearch.ts`, `run.ts`, `oracle/types.ts`, `cli/sessionRunner.ts`, `assistantResponse.ts`, `delay`, `thinkingStatus.ts`, `oracle-cli.ts`, `sessionStore.ts`, `browser/types.ts`, `modelResolver.ts`, `reattach.ts`, `package.json`, `sessionDisplay.ts`, `notifier.ts`, `actions/projectSources.ts`, `browser-manual-login-live.test.ts`, `navigation.ts`, `helpers.ts`, `options.ts`, `ModelName`, `runRootCommand`, `integrationCli.test.ts`, `bridge/client.ts`, `chromeLifecycle.ts`, `dryRun.ts`, `runOptions.ts`, `detect.ts`, `prompt.ts`, `tui/index.ts`, `ref_node_child_process`, `browserDefaults.ts`, `markdownRenderer.ts`, `getCliVersion`, `promptComposerExpressions.test.ts`, `cli/projectSources.ts`, `browserSessionManager.ts`, `docsCheck.ts`, `providerFailures.ts`, `zipBundle.ts`, `chalk`, `doctor.ts`, `tabLeaseRegistry.ts`, `followup.ts`, `chatgptImages.test.ts`, `mcp/server.ts`, `cookies.ts`, `showStatus`, `tagline.ts`, `BrowserAttachment`, `browserConfig.ts`, `markdown.ts`, `browser/config.ts`, `rootAlias.ts`, `tui/index.test.ts`, `ref_node_process`, `StoredRunOptions`, `mcporter-sessions-live.test.ts`, `clipboard.ts`, `multi-live.test.ts`, `mcp/utils.ts`, `browserGuard.pty.test.ts`, `errorUtils.ts`, `hiddenAliases.ts`?**
  _High betweenness centrality (0.103) - this node is a cross-community bridge._
- **What connects `./src/browser/chromeCookies.ts`, `Foundation`, `OPENAI_API_KEY` to the rest of the system?**
  _102 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `browser/index.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.04978070175438597 - nodes in this community are weakly interconnected._
- **Why does `dependencies` connect `dependencies` to `package.json`?**
  _High betweenness centrality (0.017) - this node is a cross-community bridge._
- **Should `executor.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.050617283950617285 - nodes in this community are weakly interconnected._
- **Why does `devDependencies` connect `devDependencies` to `package.json`?**
  _High betweenness centrality (0.014) - this node is a cross-community bridge._
- **Should `oracle.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.08269230769230769 - nodes in this community are weakly interconnected._