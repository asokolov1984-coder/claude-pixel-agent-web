# Graph Report - claude-pixel-agent-web  (2026-11-02)

## Corpus Check
- 137 files · ~62,630 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 427 file(s) not represented in the graph (top: .aseprite 415, (none) 7, .code-workspace 2)

## Summary
- 1250 nodes · 2769 edges · 88 communities (63 shown, 25 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS · INFERRED: 10 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `f174fe15`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- ComponentShowcase.tsx
- field.tsx
- react
- cn
- dependencies
- websocket.ts
- devDependencies
- agents.ts
- package.json
- DungeonMap.tsx
- bridge/claude-dungeon-bridge.mjs
- PixelEngine
- public/bridge/claude-dungeon-bridge.mjs
- llm.ts
- dialog.tsx
- sidebar.tsx
- Claude Dungeon - TODO
- sdk.ts
- dungeonConfig.ts
- vite.config.ts
- _core/index.ts
- compilerOptions
- DashboardLayout.tsx
- routers.ts
- debug-collector.js
- DungeonScene
- class-variance-authority
- 🏰 Claude Dungeon
- map.ts
- App.tsx
- components.json
- compilerOptions
- Home.tsx
- bridge.test.ts
- carousel.tsx
- main.tsx
- Claude Dungeon Bridge Script
- alert-dialog.tsx
- sheet.tsx
- db.ts
- lucide-react
- chart.tsx
- select.tsx
- SDKServer
- storage.ts
- useAuth.ts
- DungeonMapPhaser.tsx
- card.tsx
- dropdown-menu.tsx
- oauth.ts
- pagination.tsx
- bridge.ts
- env.ts
- voiceTranscription.ts
- Map.tsx
- empty.tsx
- transcriptParser.ts
- Contributing to Claude Dungeon
- auth.logout.test.ts
- scripts
- errors.ts
- notification.ts
- pnpm
- @aws-sdk/s3-request-presigner@^3.693.0
- clsx
- dotenv
- @hookform/resolvers@^5.2.2
- input-otp
- jose
- phaser
- @radix-ui/react-avatar
- @radix-ui/react-context-menu
- @radix-ui/react-menubar
- @radix-ui/react-radio-group
- @radix-ui/react-separator
- @radix-ui/react-slider
- @radix-ui/react-switch
- @radix-ui/react-toggle-group
- react-day-picker
- react-hook-form
- react-resizable-panels
- sonner
- tailwindcss-animate@^1.0.7
- vaul
- zod
- cookie.d.ts

## God Nodes (most connected - your core abstractions)
1. `cn()` - 276 edges
2. `ComponentsShowcase()` - 130 edges
3. `react` - 69 edges
4. `lucide-react` - 29 edges
5. `Button()` - 25 edges
6. `Claude Dungeon - TODO` - 23 edges
7. `DashboardLayoutContent()` - 20 edges
8. `PixelEngine` - 18 edges
9. `DungeonScene` - 16 edges
10. `compilerOptions` - 16 edges

## Surprising Connections (you probably didn't know these)
- `Props` --references--> `Hero`  [EXTRACTED]
  client/src/components/DungeonMap.tsx → client/src/hooks/useHeroSocket.ts
- `Props` --references--> `Hero`  [EXTRACTED]
  client/src/components/DungeonMapPhaser.tsx → client/src/hooks/useHeroSocket.ts
- `AlertDialogHeader()` --calls--> `cn()`  [EXTRACTED]
  client/src/components/ui/alert-dialog.tsx → client/src/lib/utils.ts
- `AlertDialogFooter()` --calls--> `cn()`  [EXTRACTED]
  client/src/components/ui/alert-dialog.tsx → client/src/lib/utils.ts
- `AlertDialogTitle()` --calls--> `cn()`  [EXTRACTED]
  client/src/components/ui/alert-dialog.tsx → client/src/lib/utils.ts

## Import Cycles
- None detected.

## Communities (88 total, 25 thin omitted)

### Community 0 - "ComponentShowcase.tsx"
Cohesion: 0.07
Nodes (55): Accordion(), AccordionContent(), AccordionItem(), AccordionTrigger(), AspectRatio(), AvatarImage(), Breadcrumb(), BreadcrumbEllipsis() (+47 more)

### Community 1 - "field.tsx"
Cohesion: 0.06
Nodes (42): ButtonGroup(), ButtonGroupSeparator(), ButtonGroupText(), buttonGroupVariants, Field(), FieldContent(), FieldDescription(), FieldError() (+34 more)

### Community 2 - "react"
Cohesion: 0.09
Nodes (31): AIChatBox(), AIChatBoxProps, Message, StatsPanelProps, TranscriptInput(), TranscriptInputProps, Button(), buttonVariants (+23 more)

### Community 3 - "cn"
Cohesion: 0.08
Nodes (35): ContextMenu(), ContextMenuCheckboxItem(), ContextMenuContent(), ContextMenuItem(), ContextMenuLabel(), ContextMenuRadioItem(), ContextMenuSeparator(), ContextMenuShortcut() (+27 more)

### Community 4 - "dependencies"
Cohesion: 0.05
Nodes (44): dependencies, @aws-sdk/client-s3@^3.693.0, class-variance-authority@^0.7.1, cookie@^1.0.2, embla-carousel-react@^8.6.0, express@^4.21.2, framer-motion@^12.23.22, lucide-react@^0.453.0 (+36 more)

### Community 5 - "websocket.ts"
Cohesion: 0.09
Nodes (38): broadcast(), CLAUDE_DIR, CLAUDE_PROJECTS_DIR, clearIdleTimer(), createDemoHeroes(), createHero(), DATA_DIR, decodeProjectPath() (+30 more)

### Community 6 - "devDependencies"
Cohesion: 0.05
Nodes (37): devDependencies, add@^2.0.6, autoprefixer@^10.4.20, drizzle-kit@^0.31.4, esbuild@^0.25.0, pnpm@^10.15.1, postcss@^8.4.47, prettier@^3.6.2 (+29 more)

### Community 7 - "agents.ts"
Cohesion: 0.09
Nodes (33): ActiveTool, agentsRouter, AppConfig, CLAUDE_DIR, CLAUDE_PROJECTS_DIR, ClaudeAgent, ClaudeSkill, CONFIG_PATH (+25 more)

### Community 8 - "package.json"
Cohesion: 0.06
Nodes (31): axios@^1.12.0, cmdk@^1.1.1, date-fns@^4.1.0, mysql2@^3.15.0, next-themes@^0.4.6, @radix-ui/react-accordion@^1.2.12, @radix-ui/react-alert-dialog@^1.1.15, @radix-ui/react-dialog@^1.1.15 (+23 more)

### Community 9 - "DungeonMap.tsx"
Cohesion: 0.11
Nodes (25): bfsPath(), drawBoss(), drawCastle(), drawGuardian(), drawHero(), drawRoomLabel(), drawSprite(), drawStaticImg() (+17 more)

### Community 10 - "bridge/claude-dungeon-bridge.mjs"
Cohesion: 0.14
Nodes (25): args, CONFIG, createHero(), debug(), decodeProjectPath(), detectHeroClass(), fileOffsets, fileToHeroId (+17 more)

### Community 11 - "PixelEngine"
Cohesion: 0.10
Nodes (9): AgentPanelProps, stateColors, stateLabels, PixelOffice(), PixelOfficeProps, AgentState, OfficeLayout, PixelEngine (+1 more)

### Community 12 - "public/bridge/claude-dungeon-bridge.mjs"
Cohesion: 0.15
Nodes (25): args, CONFIG, createHero(), debug(), decodeProjectPath(), detectHeroClass(), fileOffsets, fileToHeroId (+17 more)

### Community 13 - "llm.ts"
Cohesion: 0.10
Nodes (25): assertApiKey(), ensureArray(), FileContent, ImageContent, invokeLLM(), InvokeParams, InvokeResult, JsonSchema (+17 more)

### Community 14 - "dialog.tsx"
Cohesion: 0.16
Nodes (21): ManusDialog(), ManusDialogProps, Command(), CommandDialog(), CommandEmpty(), CommandGroup(), CommandInput(), CommandItem() (+13 more)

### Community 15 - "sidebar.tsx"
Cohesion: 0.13
Nodes (21): SidebarContext, SidebarContextProps, SidebarGroup(), SidebarGroupAction(), SidebarGroupContent(), SidebarGroupLabel(), SidebarInput(), SidebarMenuAction() (+13 more)

### Community 16 - "Claude Dungeon - TODO"
Cohesion: 0.08
Nodes (23): Claude Dungeon - TODO, Phase 10: 最终完善, Phase 11: 核心逻辑修复, Phase 12: 前端视觉全面升级, Phase 13: Another Metroidvania 素材包全面整合, Phase 14: 英雄行为系统全面重构, Phase 15: 全面视觉优化, Phase 16: 大城堡 Tilemap 重做 (+15 more)

### Community 17 - "sdk.ts"
Cohesion: 0.14
Nodes (12): OAuthService, SessionPayload, AuthorizeRequest, AuthorizeResponse, CanAccessRequest, CanAccessResponse, ExchangeTokenRequest, ExchangeTokenResponse (+4 more)

### Community 18 - "dungeonConfig.ts"
Cohesion: 0.16
Nodes (18): Props, ActiveTool, AppMode, Hero, WsMessage, ASSETS, DungeonRoom, HERO_CLASSES (+10 more)

### Community 19 - "vite.config.ts"
Cohesion: 0.10
Nodes (17): @builder.io/vite-plugin-jsx-loc@^0.1.1, @tailwindcss/vite@^4.1.3, vite@^7.1.7, vite-plugin-manus-runtime@^0.0.57, @vitejs/plugin-react@^5.0.4, @builder.io/vite-plugin-jsx-loc, @tailwindcss/vite, vite (+9 more)

### Community 20 - "_core/index.ts"
Cohesion: 0.16
Nodes (12): express, createContext(), findAvailablePort(), isPortAvailable(), startServer(), serveStatic(), setupVite(), __dirname (+4 more)

### Community 21 - "compilerOptions"
Cohesion: 0.10
Nodes (19): compilerOptions, allowImportingTsExtensions, baseUrl, esModuleInterop, incremental, jsx, lib, module (+11 more)

### Community 22 - "DashboardLayout.tsx"
Cohesion: 0.20
Nodes (17): DashboardLayoutContent(), DashboardLayoutContentProps, menuItems, Avatar(), AvatarFallback(), DropdownMenu(), DropdownMenuContent(), DropdownMenuItem() (+9 more)

### Community 23 - "routers.ts"
Cohesion: 0.20
Nodes (12): systemRouter, adminProcedure, protectedProcedure, publicProcedure, requireUser, router, t, AXIOS_TIMEOUT_MS (+4 more)

### Community 24 - "debug-collector.js"
Cohesion: 0.24
Nodes (15): compactText(), describeElement(), elText(), formatArg(), formatArgs(), getInputValueSafe(), installUiEventListeners(), nav() (+7 more)

### Community 25 - "DungeonScene"
Cohesion: 0.20
Nodes (3): bfsPath(), DungeonScene, heroRoomToRoomId()

### Community 26 - "class-variance-authority"
Cohesion: 0.16
Nodes (13): Alert(), AlertDescription(), AlertTitle(), alertVariants, Badge(), badgeVariants, ToggleGroup(), ToggleGroupContext (+5 more)

### Community 27 - "🏰 Claude Dungeon"
Cohesion: 0.12
Nodes (16): 🏰 Claude Dungeon, Connect to Claude Code, Contributing, Credits, Features, How It Works, Installation, License (+8 more)

### Community 28 - "map.ts"
Cohesion: 0.12
Nodes (16): DirectionsResult, DistanceMatrixResult, ElevationResult, GeocodingResult, getMapsConfig(), LatLng, makeRequest(), MapsConfig (+8 more)

### Community 29 - "App.tsx"
Cohesion: 0.17
Nodes (9): App(), Router(), ErrorBoundary, Toaster(), Theme, ThemeContext, ThemeContextType, ThemeProvider() (+1 more)

### Community 30 - "components.json"
Cohesion: 0.12
Nodes (15): aliases, components, hooks, lib, ui, utils, rsc, $schema (+7 more)

### Community 31 - "compilerOptions"
Cohesion: 0.12
Nodes (15): compilerOptions, allowImportingTsExtensions, isolatedModules, lib, module, moduleDetection, moduleResolution, noEmit (+7 more)

### Community 32 - "Home.tsx"
Cohesion: 0.25
Nodes (11): ConfigPanel(), ConfigPanelProps, HeroPanel(), AgentEditorProps, ItemEditor(), SkillsManager(), SkillsManagerProps, useHeroSocket() (+3 more)

### Community 33 - "bridge.test.ts"
Cohesion: 0.17
Nodes (9): vitest@^2.1.4, vitest, ensureTestDir(), getOrCreateTestApiKey(), loadTestConfig(), saveTestConfig(), TEST_CONFIG_PATH, TEST_DIR (+1 more)

### Community 34 - "carousel.tsx"
Cohesion: 0.19
Nodes (13): Carousel(), CarouselApi, CarouselContent(), CarouselContext, CarouselContextProps, CarouselItem(), CarouselNext(), CarouselOptions (+5 more)

### Community 35 - "main.tsx"
Cohesion: 0.15
Nodes (11): queryClient, redirectToLoginIfUnauthorized(), trpcClient, react-dom@^19.2.1, superjson@^1.13.3, @tanstack/react-query@^5.90.2, @trpc/client@^11.6.0, react-dom (+3 more)

### Community 36 - "Claude Dungeon Bridge Script"
Cohesion: 0.17
Nodes (11): 1. Get your API key, 2. Run the bridge, 3. Start Claude Code, Claude Dungeon Bridge Script, Hero Behavior, How It Works, Options, Quick Start (+3 more)

### Community 37 - "alert-dialog.tsx"
Cohesion: 0.20
Nodes (9): AlertDialogAction(), AlertDialogCancel(), AlertDialogContent(), AlertDialogDescription(), AlertDialogFooter(), AlertDialogHeader(), AlertDialogOverlay(), AlertDialogPortal() (+1 more)

### Community 38 - "sheet.tsx"
Cohesion: 0.26
Nodes (10): Sheet(), SheetContent(), SheetDescription(), SheetFooter(), SheetHeader(), SheetOverlay(), SheetPortal(), SheetTitle() (+2 more)

### Community 39 - "db.ts"
Cohesion: 0.24
Nodes (7): InsertUser, users, drizzle-orm@^0.44.5, drizzle-orm, getDb(), getUserByOpenId(), upsertUser()

### Community 40 - "lucide-react"
Cohesion: 0.18
Nodes (7): Props, State, Checkbox(), RadioGroup(), RadioGroupItem(), Spinner(), lucide-react

### Community 41 - "chart.tsx"
Cohesion: 0.27
Nodes (10): ChartConfig, ChartContainer(), ChartContext, ChartContextProps, ChartLegendContent(), ChartStyle(), ChartTooltipContent(), getPayloadConfigFromPayload() (+2 more)

### Community 42 - "select.tsx"
Cohesion: 0.22
Nodes (9): Select(), SelectContent(), SelectItem(), SelectLabel(), SelectScrollDownButton(), SelectScrollUpButton(), SelectSeparator(), SelectTrigger() (+1 more)

### Community 43 - "SDKServer"
Cohesion: 0.31
Nodes (3): User, isNonEmptyString(), SDKServer

### Community 44 - "storage.ts"
Cohesion: 0.42
Nodes (10): buildAuthHeaders(), buildDownloadUrl(), buildUploadUrl(), ensureTrailingSlash(), getStorageConfig(), normalizeKey(), StorageConfig, storageGet() (+2 more)

### Community 45 - "useAuth.ts"
Cohesion: 0.29
Nodes (7): DashboardLayout(), DashboardLayoutSkeleton(), SidebarMenuSkeleton(), Skeleton(), getLoginUrl(), useAuth(), UseAuthOptions

### Community 46 - "DungeonMapPhaser.tsx"
Cohesion: 0.20
Nodes (8): DungeonMapPhaser(), HeroSprite, Props, ROOM_CENTERS, ROOM_WALKABLE, RoomId, ROOMS, WALKABLE

### Community 47 - "card.tsx"
Cohesion: 0.29
Nodes (8): Card(), CardAction(), CardContent(), CardDescription(), CardFooter(), CardHeader(), CardTitle(), NotFound()

### Community 48 - "dropdown-menu.tsx"
Cohesion: 0.20
Nodes (5): DropdownMenuCheckboxItem(), DropdownMenuRadioItem(), DropdownMenuShortcut(), DropdownMenuSubContent(), DropdownMenuSubTrigger()

### Community 49 - "oauth.ts"
Cohesion: 0.29
Nodes (7): getSessionCookieOptions(), isSecureRequest(), LOCAL_HOSTS, getQueryParam(), registerOAuthRoutes(), sdk, appRouter

### Community 50 - "pagination.tsx"
Cohesion: 0.28
Nodes (8): Pagination(), PaginationContent(), PaginationEllipsis(), PaginationItem(), PaginationLink(), PaginationLinkProps, PaginationNext(), PaginationPrevious()

### Community 51 - "bridge.ts"
Cohesion: 0.39
Nodes (8): Config, CONFIG_PATH, createBridgeRouter(), DATA_DIR, getOrCreateApiKey(), loadConfig(), requireBridgeKey(), saveConfig()

### Community 52 - "env.ts"
Cohesion: 0.28
Nodes (5): DataApiCallOptions, ENV, generateImage(), GenerateImageOptions, GenerateImageResponse

### Community 53 - "voiceTranscription.ts"
Cohesion: 0.28
Nodes (8): getFileExtension(), getLanguageName(), transcribeAudio(), TranscribeOptions, TranscriptionError, TranscriptionResponse, WhisperResponse, WhisperSegment

### Community 54 - "Map.tsx"
Cohesion: 0.36
Nodes (6): loadMapScript(), MapView(), MapViewProps, Window, noop, usePersistFn()

### Community 55 - "empty.tsx"
Cohesion: 0.29
Nodes (7): Empty(), EmptyContent(), EmptyDescription(), EmptyHeader(), EmptyMedia(), emptyMediaVariants, EmptyTitle()

### Community 56 - "transcriptParser.ts"
Cohesion: 0.25
Nodes (3): AgentActivity, ParsedTranscript, TranscriptEntry

### Community 57 - "Contributing to Claude Dungeon"
Cohesion: 0.25
Nodes (7): Code Style, Contributing to Claude Dungeon, Development Setup, Good First Issues, Project Conventions, Pull Request Guidelines, Questions?

### Community 58 - "auth.logout.test.ts"
Cohesion: 0.29
Nodes (5): @trpc/server@^11.6.0, @trpc/server, AuthenticatedUser, CookieCall, TrpcContext

### Community 59 - "scripts"
Cohesion: 0.25
Nodes (8): scripts, build, check, db:push, dev, format, start, test

### Community 60 - "errors.ts"
Cohesion: 0.39
Nodes (5): BadRequestError(), ForbiddenError(), HttpError, NotFoundError(), UnauthorizedError()

### Community 61 - "notification.ts"
Cohesion: 0.48
Nodes (6): buildEndpointUrl(), isNonEmptyString(), NotificationPayload, notifyOwner(), trimValue(), validatePayload()

### Community 62 - "pnpm"
Cohesion: 0.40
Nodes (5): tailwindcss>nanoid, wouter@3.7.1, pnpm, overrides, patchedDependencies

## Knowledge Gaps
- **25 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `react` connect `react` to `ComponentShowcase.tsx`, `field.tsx`, `cn`, `dependencies`, `package.json`, `DungeonMap.tsx`, `PixelEngine`, `dialog.tsx`, `sidebar.tsx`, `dungeonConfig.ts`, `DashboardLayout.tsx`, `class-variance-authority`, `App.tsx`, `Home.tsx`, `carousel.tsx`, `alert-dialog.tsx`, `sheet.tsx`, `lucide-react`, `chart.tsx`, `select.tsx`, `useAuth.ts`, `DungeonMapPhaser.tsx`, `card.tsx`, `dropdown-menu.tsx`, `pagination.tsx`, `Map.tsx`?**
  _High betweenness centrality (0.228) - this node is a cross-community bridge._
- **Should `ComponentShowcase.tsx` be split into smaller, more focused modules?**
  _Cohesion score 0.07033248081841433 - nodes in this community are weakly interconnected._
- **Why does `cn()` connect `cn` to `ComponentShowcase.tsx`, `field.tsx`, `react`, `dialog.tsx`, `sidebar.tsx`, `DashboardLayout.tsx`, `class-variance-authority`, `App.tsx`, `carousel.tsx`, `alert-dialog.tsx`, `sheet.tsx`, `lucide-react`, `chart.tsx`, `select.tsx`, `useAuth.ts`, `card.tsx`, `dropdown-menu.tsx`, `pagination.tsx`, `Map.tsx`, `empty.tsx`?**
  _High betweenness centrality (0.110) - this node is a cross-community bridge._
- **Should `field.tsx` be split into smaller, more focused modules?**
  _Cohesion score 0.05585106382978723 - nodes in this community are weakly interconnected._
- **Why does `express` connect `_core/index.ts` to `dependencies`, `package.json`, `oauth.ts`, `sdk.ts`, `bridge.ts`?**
  _High betweenness centrality (0.065) - this node is a cross-community bridge._
- **Should `react` be split into smaller, more focused modules?**
  _Cohesion score 0.08880666049953746 - nodes in this community are weakly interconnected._
- **Should `cn` be split into smaller, more focused modules?**
  _Cohesion score 0.07536231884057971 - nodes in this community are weakly interconnected._