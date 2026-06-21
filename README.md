# awesome-Hermes

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

English | [中文](./README.zh-CN.md)

A curated, original collection of resources for learning, using, extending, and deploying Hermes Agent.

Hermes Agent is a self-improving AI agent from Nous Research. It combines persistent memory, session search, skills, tool use, messaging gateways, delegation, browser automation, cron jobs, MCP, and multiple execution backends in one system.

Official repo: https://github.com/NousResearch/hermes-agent
Official docs: https://hermes-agent.nousresearch.com/docs/

## What’s in this list

- official docs and release references
- practical setup and operator guides
- community workspaces, plugins, and utilities
- skills and agentskills.io ecosystem projects
- integrations, bridges, and domain-specific projects
- videos, books, and other learning material

## Start here

If you are new to Hermes, this order works well:

1. Read the official docs quickstart
2. Learn the core concepts: memory, skills, tools, and profiles
3. Pick a runtime surface: CLI, Telegram, Discord, or API
4. Add a workspace or plugin only after the basics are stable

## Contents

- [Official Foundations](#official-foundations)
- [Getting Started](#getting-started)
- [Core Concepts and Features](#core-concepts-and-features)
- [Messaging, Voice, and Automation](#messaging-voice-and-automation)
- [Workspaces and User Interfaces](#workspaces-and-user-interfaces)
- [Skills, Plugins, and Extensions](#skills-plugins-and-extensions)
- [Deployment and Operations](#deployment-and-operations)
- [Integrations and Bridges](#integrations-and-bridges)
- [Research, Multi-Agent, and Domain Projects](#research-multi-agent-and-domain-projects)
- [Guides, Books, Videos, and Related Lists](#guides-books-videos-and-related-lists)
- [Community](#community)
- [Contributing](#contributing)

## Official Foundations

- [Hermes Agent](https://github.com/NousResearch/hermes-agent) — main repository.
- [Official Documentation](https://hermes-agent.nousresearch.com/docs/) — central documentation hub.
- [Releases](https://github.com/NousResearch/hermes-agent/releases) — changelogs and notable features by version.
- [Nous Research](https://nousresearch.com) — the team behind Hermes.
- [Hermes Agent Self-Evolution](https://github.com/NousResearch/hermes-agent-self-evolution) — research project for improving Hermes behavior with evolutionary methods.
- [Hermes Paperclip Adapter](https://github.com/NousResearch/hermes-paperclip-adapter) — run Hermes inside Paperclip-style company workflows.
- [Autonovel](https://github.com/NousResearch/autonovel) — long-form autonomous writing workflow built around Hermes.

## Getting Started

- [Installation](https://hermes-agent.nousresearch.com/docs/getting-started/installation)
- [Quickstart](https://hermes-agent.nousresearch.com/docs/getting-started/quickstart)
- [Learning Path](https://hermes-agent.nousresearch.com/docs/getting-started/learning-path)
- [Updating](https://hermes-agent.nousresearch.com/docs/getting-started/updating)
- [Configuration](https://hermes-agent.nousresearch.com/docs/user-guide/configuration)
- [CLI Guide](https://hermes-agent.nousresearch.com/docs/user-guide/cli)
- [Profiles](https://hermes-agent.nousresearch.com/docs/user-guide/profiles)
- [FAQ](https://hermes-agent.nousresearch.com/docs/reference/faq)

## Core Concepts and Features

- [Architecture](https://hermes-agent.nousresearch.com/docs/developer-guide/architecture)
- [Prompt Assembly](https://hermes-agent.nousresearch.com/docs/developer-guide/prompt-assembly)
- [Session Storage](https://hermes-agent.nousresearch.com/docs/developer-guide/session-storage)
- [Persistent Memory](https://hermes-agent.nousresearch.com/docs/user-guide/features/memory)
- [Memory Providers](https://hermes-agent.nousresearch.com/docs/user-guide/features/memory-providers)
- [Skills](https://hermes-agent.nousresearch.com/docs/user-guide/features/skills)
- [Context Files](https://hermes-agent.nousresearch.com/docs/user-guide/features/context-files)
- [Tools](https://hermes-agent.nousresearch.com/docs/user-guide/features/tools)
- [Tool Reference](https://hermes-agent.nousresearch.com/docs/reference/tools-reference)
- [Toolsets Reference](https://hermes-agent.nousresearch.com/docs/reference/toolsets-reference)
- [Browser Automation](https://hermes-agent.nousresearch.com/docs/user-guide/features/browser)
- [Vision](https://hermes-agent.nousresearch.com/docs/user-guide/features/vision)
- [Code Execution](https://hermes-agent.nousresearch.com/docs/user-guide/features/code-execution)
- [Provider Routing](https://hermes-agent.nousresearch.com/docs/user-guide/features/provider-routing)
- [Fallback Providers](https://hermes-agent.nousresearch.com/docs/user-guide/features/fallback-providers)
- [Security](https://hermes-agent.nousresearch.com/docs/user-guide/security)
- [Checkpoints and Rollback](https://hermes-agent.nousresearch.com/docs/user-guide/checkpoints-and-rollback)
- [Docker Usage](https://hermes-agent.nousresearch.com/docs/user-guide/docker)

## Messaging, Voice, and Automation

- [Messaging Overview](https://hermes-agent.nousresearch.com/docs/user-guide/messaging)
- [Telegram](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/telegram)
- [Discord](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/discord)
- [WhatsApp](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/whatsapp)
- [Slack](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/slack)
- [Signal](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/signal)
- [Email](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/email)
- [Home Assistant](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/homeassistant)
- [Voice Mode](https://hermes-agent.nousresearch.com/docs/user-guide/features/voice-mode)
- [Scheduled Tasks / Cron](https://hermes-agent.nousresearch.com/docs/user-guide/features/cron)
- [Subagent Delegation](https://hermes-agent.nousresearch.com/docs/user-guide/features/delegation)
- [MCP](https://hermes-agent.nousresearch.com/docs/user-guide/features/mcp)
- [API Server](https://hermes-agent.nousresearch.com/docs/user-guide/features/api-server)
- [Hooks](https://hermes-agent.nousresearch.com/docs/user-guide/features/hooks)
- [Webhooks](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/webhooks)
- [Open WebUI](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/open-webui/) — use Hermes as an OpenAI-compatible backend behind Open WebUI.
- [Open WebUI Hermes Agent Guide](https://docs.openwebui.com/getting-started/quick-start/connect-an-agent/hermes-agent/) — Open WebUI’s own connector guide, including Docker networking and `/v1` troubleshooting details.
- [Web Dashboard](https://hermes-agent.nousresearch.com/docs/user-guide/features/web-dashboard) — official browser dashboard for config, keys, sessions, logs, analytics, skills, and cron management.
- [Dashboard Plugins](https://hermes-agent.nousresearch.com/docs/user-guide/features/dashboard-plugins) — official guide for adding custom tabs and backend endpoints to the built-in Hermes dashboard.
- [Extending the Dashboard](https://hermes-agent.nousresearch.com/docs/user-guide/features/extending-the-dashboard) — canonical runtime extension guide for reskinning the official dashboard with themes, custom tabs, shell slots, and plugin backend APIs without forking Hermes.
- [Team Telegram Assistant Guide](https://hermes-agent.nousresearch.com/docs/guides/team-telegram-assistant)
- [Daily Briefing Bot Guide](https://hermes-agent.nousresearch.com/docs/guides/daily-briefing-bot)
- [Automate with Cron](https://hermes-agent.nousresearch.com/docs/guides/automate-with-cron)
- [Use MCP with Hermes](https://hermes-agent.nousresearch.com/docs/guides/use-mcp-with-hermes)
- [Use SOUL.md with Hermes](https://hermes-agent.nousresearch.com/docs/guides/use-soul-with-hermes)
- [Use Voice Mode with Hermes](https://hermes-agent.nousresearch.com/docs/guides/use-voice-mode-with-hermes)
- [J.A.R.V.I.S](https://github.com/eadmin2/jarvis_ai) — Iron-Man-style voice assistant and holographic HUD for Hermes Agent with local Whisper STT, ElevenLabs TTS, live tool-call visualization, approval cards, and barge-in support, all self-hosted.

## Workspaces and User Interfaces

- [Hermes Workspace](https://github.com/outsourc-e/hermes-workspace) — the best-known browser workspace for Hermes with chat, terminal, memory, skills, and inspector.
- [Pan UI](https://github.com/Euraika-Labs/pan-ui) — another self-hosted workspace focused on operating Hermes with a fuller control panel.
- [Hermes Desktop (cross-platform companion)](https://github.com/fathah/hermes-desktop) — desktop wrapper that helps with install, provider setup, chat, sessions, memory, skills, and settings across macOS and Linux.
- [Hermes Desktop for Windows](https://github.com/acegraphx/hermes-desktop-win) — native WPF workspace for Windows users who want SSH access to Hermes hosts plus sessions, files, wiki, skills, cron, and terminal management.
- [Scarf](https://github.com/awizemann/scarf) — native macOS GUI with multi-window local/remote server support over SSH, covering chat, dashboard, sessions, memory, cron, MCP, and config workflows from one desktop app.
- [Hermes Desktop (native macOS over SSH)](https://github.com/dodo-reach/hermes-desktop) — native Mac workspace that connects straight to a Hermes host over SSH, keeps the remote machine as the source of truth, and exposes sessions, skills, usage views, and a real terminal without a browser layer.
- [Hermes Desktop - OS1 Edition](https://github.com/nickvasilescu/hermes-desktop-os1) — native macOS workspace for Hermes on Orgo cloud computers and SSH hosts, with VM provisioning, sessions, kanban, files, skills, cron, terminal, and WebRTC voice mode.
- [Hermes WebUI](https://github.com/nesquena/hermes-webui) — mature browser UI that aims for near CLI parity, including chat, sessions, file browsing, and remote access workflows.
- [Hermes AI Agent — VS Code Extension](https://github.com/joaompfp/hermes-vscode) — VS Code sidebar for Hermes CLI over ACP, with streaming chat, tool traces, session persistence, and a skills picker.
- [Hermes WebUI (ops dashboard)](https://github.com/sanchomuzax/hermes-webui) — read-only monitoring and configuration dashboard for sessions, cron, skills, and config data.
- [Hermes Agent WebUI](https://github.com/laolaoshiren/hermes-agent-webui) — chat-first self-hosted frontend that focuses on multi-session conversation workflows and safer public deployment defaults instead of a control-panel-heavy layout.
- [Hermes Control Interface](https://github.com/xaspx/hermes-control-interface) — self-hosted control surface with a browser terminal, file explorer, profile and gateway controls, cron/session monitoring, token analytics, and system metrics behind a simple password gate.
- [Hermes UI](https://github.com/pyrate-llama/hermes-ui) — glassmorphic single-file command center with chat, file browsing, memory, skills, Kanban, and live operational monitoring.
- [Hermes for Web](https://github.com/reallygood83/hermes-for-web) — personalized browser workbench with onboarding packs, artifacts, and memory-aware startup flows.
- [Portable Hermes Agent](https://github.com/rookiemann/portable-hermes-agent) — packaged desktop-style distribution for users who want an easier Windows path.
- [hermes-agent-desktop](https://github.com/comedy1024/hermes-agent-desktop) — all-in-one Docker desktop that bundles Hermes Agent, Hermes WebUI, and a browser-accessible Debian KDE environment for users who want GUI access plus a ready-made self-hosted runtime.
- [Hermes Dashboard](https://github.com/Bichev/hermes-dashboard) — analytics and cost-monitoring dashboard for sessions, tools, and API usage.
- [Hermes Dashboard (gateway control panel)](https://github.com/chrisryugj/hermes-dashboard) — full web control surface for the Hermes gateway with config editing, MCP management, cron controls, skill browsing, logs, and model switching without using the CLI.
- [Hermes Dashboard (live wiki)](https://github.com/Kori-x/hermes-dashboard) — real-time observability dashboard plus an auto-generated local wiki for skills, plugins, tools, memory, and soul files.
- [Hermes Web UI](https://github.com/EKKOLearnAI/hermes-web-ui) — npm-installable Vue dashboard that brings multi-platform chat, profile switching, model management, analytics, logs, web terminal, and channel configuration into one operational console.
- [Hermes Studio](https://github.com/JPeetz/Hermes-Studio) — power-user browser studio built around crews, execution approvals, visual memory graphs, workflow DAGs, and one of the deepest cron/job-management interfaces in the ecosystem.
- [Hermes Studio (Web UI)](https://github.com/EKKOLearnAI/hermes-studio) — full-featured desktop app and web console for Hermes Agent with multi-platform chat, session management, scheduled jobs, usage analytics, platform channels, file browsing, web terminal, and voice I/O — ships as desktop app, npm package, and Docker image.
- [Hermes War Room](https://github.com/Naroh091/hermes-war-room) — browser-based operations floor that makes Hermes’ native orchestration visible with mission control, team rosters, live agent status, and per-agent task queues.
- [Minions](https://github.com/Agent-3-7/minions) — mission-control board for autonomous Hermes work, with persistent root sessions, task supervision, and review flow.
- [Minions (Agent37)](https://github.com/agent37-platform/minions) — mission-control board for autonomous Hermes work with Kanban task boards, task creation screens, and review flows, installable via `npx minionsai`.
- [Hermes Telegram Mini App](https://github.com/clawvader-tech/hermes-telegram-miniapp) — mobile-first Telegram Mini App that adds chat, cron control, system health, and background agent spawning directly inside Telegram with hardened auth and tunnel-based deployment docs.
- [Hermes Voice Agent](https://github.com/onlockj/hermes-voice-agent) — low-latency Telegram voice channel with a PWA frontend, OpenAI Realtime pipeline, barge-in support, and one-shot deploy docs.
- [Atomic Bot](https://github.com/AtomicBot-ai/atomicbot) — native desktop launcher that recently added one-click Hermes setup on macOS and Windows, bundling dashboard, terminal, logs, and file browsing for users who want a faster no-terminal path.
- [Web3Hermes](https://github.com/Web3CZ/Web3Hermes) — lightweight Chinese-localized WebUI focused on desktop browser chat, sessions, workspace, and task views for mainland users.
- [Hermes HUD UI](https://github.com/joeynyc/hermes-hudui) — browser-based consciousness monitor for Hermes that visualizes memory, token costs, skills, cron jobs, and growth snapshots directly from ~/.hermes/.
- [Hermes HUD](https://github.com/joeynyc/hermes-hud) — terminal-first companion to the HUD UI for live inspection of memory, skills, mistakes, tool usage, and ongoing agent growth.
- [Hermes Client](https://github.com/lotsoftick/hermes_client) — web-based chat interface for Hermes with multi-profile management, real-time streaming, cron/skill/plugin configuration, and PWA support for standalone desktop windows.
- [Hermes Agent CN Desktop](https://github.com/Eynzof/hermes-agent-cn-desktop) — native Windows-first desktop client for the Chinese Hermes community, built with Tauri v2 + Rust + React, featuring runtime management, diagnostics, memory tools, and secure proxying.
- [Hermes Chat Bubble](https://github.com/clearmud/hermes-chat-bubble) — lightweight dashboard plugin that adds a floating TUI chat bubble to the Hermes Dashboard, repositioning the existing persistent chat host without opening a second session.
- [ClawPanel](https://github.com/qingchencloud/clawpanel) — multi-engine AI management panel supporting both OpenClaw and Hermes Agent, with a built-in AI assistant that handles environment checks, log analysis, config repair, and automated troubleshooting via Rust + Tauri v2.

- [Agent Sessions](https://github.com/jazzyalex/agent-sessions) — native macOS session browser and cockpit for Hermes (and Claude Code, Codex, OpenCode, Gemini CLI), with search/filter across all past sessions, archive and resume, real-time rate-limit tracking, and analytics.
- [ReevesAgents](https://github.com/mertkayacs/reevesagents) — free, open-source workspace manager for AI CLI agents that bundles TUI, WebUI, MCP server, and CLI in one package with no API key required.
- [CC Switch](https://github.com/farion1231/cc-switch) — cross-platform desktop all-in-one assistant that adds one-click Hermes Agent setup alongside Claude Code, Codex, OpenCode, OpenClaw, and Gemini CLI with unified model routing.
- [AionUi](https://github.com/iOfficeAI/AionUi) — free, local, open-source 24/7 cowork app that manages Hermes Agent alongside 20+ other CLI agents with a unified workspace and custom model routing.
- [Wesight](https://github.com/freestylefly/wesight) — open-source desktop AI agent workspace with one-click Hermes Agent setup, custom LLM model routing, and support for Claude Code, Codex, and OpenClaw.
- [OpenClaw-Admin](https://github.com/itq5/OpenClaw-Admin) — Vue 3 AI agent management platform that supports both OpenClaw Gateway and Hermes Agent, providing a web UI for managing agents, sessions, models, channels, and skills.
- [iHermes](https://github.com/2winter-dev/iHermes) — mobile-first Hermes client built with Expo that connects to your own Hermes agent from Android, iOS, or Web (PWA) with no mandatory backend service.
- [Cadux](https://github.com/raymondclowe/cadux) — fast, lightweight Android and desktop client for the Hermes Agent Gateway with SSE streaming, Bearer token auth, and LAN device pairing via a companion daemon.
- [Hermes Swift iOS](https://github.com/hermes-webui/hermes-swift-ios) — native iPhone client for connecting to a Hermes WebUI instance over Tailscale, with QR code scanning, voice input, Share Sheet, and document picker integration.
- [My Hermes Desktop](https://github.com/wuguirongsg/My-Hermes-Desktop) — Tauri 2 + React native companion app for macOS with zero-terminal operation and Apple-style interaction patterns.
- [Hermes Theme Reflect](https://github.com/daletkc/hermes-theme-reflect) — premium dark theme for the Hermes Agent dashboard featuring deep navy with indigo-violet accents.
- [Republic (Daedalus)](https://github.com/JustinPerea/Republic) — hackathon-winning dashboard theme in the visual language of The Designers Republic and Marathon, with bone-on-near-black aesthetic, radioactive yellow structural color, Geist Mono/IBM Plex typography, and full design-system documentation.
- [Agent of Empires](https://github.com/agent-of-empires/agent-of-empires) — cross-platform TUI and Web management surface for multiple coding agents including Hermes, Claude Code, Codex, OpenCode, Gemini CLI, and more, with mobile-friendly access and session sharing.
- [Hermes Link Curator](https://github.com/dodo-reach/hermes-link-curator) — link curator profile pack that turns Hermes into a librarian: send a URL, get it archived, tagged, summarized, and browsable in an Obsidian-style dashboard with a web UI.
- [Hermes Mini App Template](https://github.com/waguriagentic/hermes-miniapp-template) — ready-to-use Telegram Mini App template for Hermes Agent that developers can fork and extend with custom tools and dashboards.
- [Vessel Browser](https://github.com/unmodeled-tyler/vessel-browser) — open source chromium-based AI browser built for agent harnesses with durable state, MCP control, and a human-visible supervisory UI for long-running workflows.
- [Hermes Island](https://github.com/esaradev/hermes-island) — macOS Dynamic Island notch app that monitors Hermes agent sessions, memory, and multi-agent workflows from the menu bar.
- [Hermes Console](https://github.com/dannyshmueli/obsidian-hermes-console) — Obsidian community plugin that runs Hermes Agent directly inside your vault with terminal tabs, selected-note context bridging, and a full settings UI; installable from the Obsidian Community Plugin directory.

## Skills, Plugins, and Extensions

### Skills and skill ecosystems

- [Bundled Skills Catalog](https://hermes-agent.nousresearch.com/docs/reference/skills-catalog)
- [Optional Skills Catalog](https://hermes-agent.nousresearch.com/docs/reference/optional-skills-catalog)
- [Creating Skills](https://hermes-agent.nousresearch.com/docs/developer-guide/creating-skills)
- [Work with Skills](https://hermes-agent.nousresearch.com/docs/guides/work-with-skills)
- [Shopify Skill](https://hermes-agent.nousresearch.com/docs/user-guide/skills/optional/productivity/productivity-shopify) — official optional commerce skill for managing Shopify products, orders, inventory, customers, and fulfillments directly from Hermes via GraphQL.
- [OpenHands](https://hermes-agent.nousresearch.com/docs/user-guide/skills/optional/autonomous-ai-agents/autonomous-ai-agents-openhands) — official optional skill for delegating coding work to the OpenHands CLI in headless, model-agnostic mode.
- [agentskills.io](https://agentskills.io) — open skill ecosystem used across multiple agent stacks.
- [wondelai/skills](https://github.com/wondelai/skills) — broad community skill collection.
- [Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) — large security-oriented skill library.
- [chainlink-agent-skills](https://github.com/smartcontractkit/chainlink-agent-skills) — agent skills around Chainlink workflows.
- [black-forest-labs/skills](https://github.com/black-forest-labs/skills) — skills around FLUX and image workflows.
- [pydantic-ai-skills](https://github.com/DougTrajano/pydantic-ai-skills) — typed, structured skill workflows.
- [litprog-skill](https://github.com/tlehman/litprog-skill) — literate-programming-oriented skill workflow.
- [awesome-hermes-skills](https://github.com/ChuckSRQ/awesome-hermes-skills) — curated, install-ready Hermes skill pack covering research, artifact previews, self-improvement benchmarks, and GitHub workflows.
- [awesome-hermes-skills (ZeroPointRepo)](https://github.com/ZeroPointRepo/awesome-hermes-skills) — 85 built-in + 78 community skills, plugins, and tools for Hermes Agent, cross-compatible with Claude Code, OpenClaw, Cursor, and Windsurf.
- [hermes-skills (itgoyo)](https://github.com/itgoyo/hermes-skills) — 310+ Hermes Agent skills covering coding, marketing, design, finance, MLOps, and game development, installable by cloning into ~/.hermes/skills/.
- [hermes-merchant](https://github.com/arimanyus/hermes-merchant) — portable Hermes skill pack for ML/AI job scraping, profile scoring, and Greenhouse application automation.
- [hermes-skill-factory](https://github.com/Romanescu11/hermes-skill-factory) — generates reusable skills from repeated work.
- [Hermes Memory Skills](https://github.com/nexus9888/hermes-memory-skills) — memory-hygiene skill pack that runs dreaming and surgical trimming across different memory backends.
- [Super Hermes](https://github.com/Cranot/super-hermes) — analytical skill set that teaches Hermes to write sharper reasoning lenses, expose blind spots, and report structural constraints during deep analysis.
- [hermeshub](https://github.com/amanning3390/hermeshub) — community discovery hub for Hermes skills.
- [skilldock.io](https://github.com/chigwell/skilldock.io) — cross-agent skill registry.
- [HyperDirector](https://github.com/gloweaseco-leo/hyperdirector) — Hermes skill pack for structured HyperFrames video production, with brief→storyboard→HTML→render workflow and install scripts.
- [agency-agents-zh](https://github.com/jnMetaCode/agency-agents-zh) — 215 ready-to-use Chinese AI expert roles covering engineering, design, marketing, finance, and more, with explicit Hermes Agent install support via `--category` batching.
- [hermes-agent-idea-workflow](https://github.com/AkoliteZA/hermes-agent-idea-workflow) — pre-build idea-to-spec workflow skills that turn rough product ideas into design docs, implementation specs, and agent-ready build handoffs.
- [LLMQuant Skills](https://github.com/LLMQuant/skills) — 18 category finance skills covering equities, options, macro, crypto, credit, portfolio, and risk, grounded in LLMQuant Data and installable across Hermes, Claude Code, Codex, Cursor, and OpenClaw.
- [hermes-agent-rtk-caveman](https://github.com/adityahimaone/hermes-agent-rtk-caveman) — ready-to-use RTK + Caveman configuration for 90–99% token savings on CLI operations, with 40+ pre-configured skills and one-command setup.
- [AI Agent Skills](https://github.com/kevinnft/ai-agent-skills) — 191 attribution-first agent skills for Hermes Agent, Claude Code, and Cursor across 28 categories with a single installer and searchable catalog.

- [hermes-skill-atlas](https://github.com/codesstar/hermes-skill-atlas) — interactive map of 70+ curated, verified open-source Hermes skills with search and category filtering.
- [Felo Skills Pack](https://felo.ai/skills/hermes-agent) — 12 production-ready Hermes skills for research, slides, content creation, social listening, and persistent LiveDoc workflows.
- [hermes-edu-skills](https://github.com/zhongweiv/hermes-edu-skills) — 188 structured Chinese education skills covering textbook sync, exam prep, teacher tools, and family learning, installable via CLI with cross-agent export support.
- [Mercury Agent Skills](https://github.com/cosmicstack-labs/mercury-agent-skills) — curated cross-agent skill registry with a web-based discovery hub, supporting Hermes, Claude Code, Codex, OpenClaw, and Cursor with one-click CLI install and version pinning.
- [hermes-arxiv-agent](https://github.com/genggng/hermes-arxiv-agent) — arXiv paper auto-fetching skill that generates Chinese summaries, pushes daily digests to Feishu, and provides a local or GitHub Pages reading site for browsing curated papers.
- [YouTube Skills](https://github.com/ZeroPointRepo/youtube-skills) — YouTube transcript extraction, search, and channel browsing skills for Hermes and other agents, powered by TranscriptAPI with no Google quota required.
- [21-Day Self-Interview](https://github.com/Forlives/21-day-self-interview) — Hermes Agent skill that asks three meaningful existential-psychology questions each night for 21 days, remembers every answer, and reflects your own words back on days 7, 14, and 21. Bilingual zh/en with no external dependencies.
- [Hermes Kanban Bridge](https://github.com/GumbyEnder/hermes-kanban) — Obsidian plugin plus Hermes skill that turns Hermes into a project co-pilot living inside your Obsidian vault, breaking goals into Kanban boards, moving cards, running standups, and doing weekly reviews — fully local, no cloud.
- [Cinema Manager](https://github.com/DavidBB-L/cinema-manager) — movie and TV resource search skill with automatic Quark cloud drive saving for media automation workflows.
- [Hermes Proficiencies](https://github.com/sene1337/hermes-proficiencies) — shareable operating-attribute skills for encoding human SOPs and playbooks into agent-readable format with safe publishing and workspace hygiene.
- [Hermes SkillOpt](https://github.com/magnus919/hermes-SkillOpt) — controlled skill optimization derived from Microsoft Research's SkillOpt, with text-space optimization and validation gates that improved 52 out of 52 test settings.
- [Hermes Council](https://github.com/magnus919/hermes-council) — multi-agent debate system that spawns custom-composed expert agents to debate questions in structured rounds, producing visible transcripts and synthesized recommendations. Pure SKILL.md, zero new infrastructure.
- [Hermes Best Models](https://github.com/fox-in-the-box-ai/hermes-best-models) — LLM evaluation benchmarks specifically designed for Hermes agents, helping operators find the best models for their use case.
- [planning-with-files](https://github.com/OthmanAdi/planning-with-files) — persistent file-based planning for long-running agentic tasks with crash-proof markdown plans, deterministic completion gates, and multi-agent shared state on disk. Works with 60+ agents including Hermes via the SKILL.md standard.
- [avoid-ai-writing](https://github.com/conorbronsdon/avoid-ai-writing) — skill that audits and rewrites content to strip AI writing patterns, compatible with Hermes, Claude Code, and OpenClaw.
- [Hermes Skins](https://github.com/joeynyc/hermes-skins) — custom skins and visual themes for the Hermes CLI agent, with community-contributed styles.
- [Education Agent Skills](https://github.com/GarethManning/education-agent-skills) — 165 evidence-based education skills for Claude, Codex, Hermes, and any Agent Skills-compatible tool, covering pedagogy, assessment, and classroom automation.
- [Deep Research Agent](https://github.com/CYC2002tommy/Deep-Research-Agent) — industrial-grade scientific research pipeline skill that automates literature review from abstract querying through full-text verification, Q1-Q2 journal filtering, anti-hallucination checks, and document compilation.
- [Master Skill](https://github.com/swaylq/master-skill) — cross-agent industry OS skill that auto-researches a domain across six dimensions (leaders, tool maps, workflows, knowledge canons, information sources, terminology) and distills a deployable skill in 30–60 minutes.
- [SkillReaper](https://github.com/thousandflowers/skillreaper) — evidence-based pruning tool that scans real transcript data to identify and safely remove unused skills, MCP servers, and agents from your stack.
- [novel2hermes_jp](https://github.com/kgmkm/novel2hermes_jp) — Japanese novel-writing skill pack that combines Hermes memory with vecmemori external search for long-form fiction planning and drafting.
- [dream-auto](https://github.com/StefanIsMe/dream-auto) — MCTS-powered autonomous dream system that runs background thinking cycles for Hermes, exploring alternative reasoning paths and consolidating insights between sessions.
- [hermes-persona](https://github.com/kenyonxu/hermes-persona) — dynamic persona context injection engine for Hermes Agent, with code-driven configuration for adapting personality, tone, and behavioral rules across sessions.
- [Hermes Self-Iteration Skill](https://github.com/TangGV/hermes-self-iteration-skill) — upper-layer execution protocol that drives Hermes through autonomous analysis → improvement → verification → ROI-gated continuations, turning any project, system, or workflow into a self-maturing pipeline.

### Plugins and add-ons

- [Plugins](https://hermes-agent.nousresearch.com/docs/user-guide/features/plugins)
- [Built-in Plugins](https://hermes-agent.nousresearch.com/docs/user-guide/features/built-in-plugins) — official catalog of opt-in bundled plugins such as disk cleanup, Langfuse tracing, Spotify control, Google Meet joining, image backends, and dashboard examples that ship inside Hermes itself.
- [Memory Provider Plugin Guide](https://hermes-agent.nousresearch.com/docs/developer-guide/memory-provider-plugin)
- [Model Provider Plugins](https://hermes-agent.nousresearch.com/docs/developer-guide/model-provider-plugin) — official guide to shipping first-class inference backends as drop-in plugins, including provider profiles, auto-discovery, CLI wiring, and override behavior for custom or patched model routes.
- [Context Engine Plugins](https://hermes-agent.nousresearch.com/docs/developer-guide/context-engine-plugin) — official reference for replacing Hermes’s built-in context compressor with custom engines such as DAG-based or lossless context-management strategies.
- [Build a Hermes Plugin](https://hermes-agent.nousresearch.com/docs/guides/build-a-hermes-plugin) — end-to-end official guide for authoring Hermes plugins with tools, hooks, skills, slash commands, and packaged assets.
- [Hermes Example Plugins](https://github.com/NousResearch/hermes-example-plugins) — official reference implementations that demonstrate the main plugin surfaces with minimal, readable code.
- [Hermes Memory UI](https://github.com/xraysight/hermes-memory-ui) — read-only dashboard plugin for inspecting `MEMORY.md`, `USER.md`, and optional holographic SQLite memory without bypassing Hermes’s normal memory-write safeguards.
- [memory-files-dashboard-plugin](https://github.com/wobbywells/memory-files-dashboard-plugin) — dashboard plugin that safely exposes `USER.md` and `MEMORY.md` editing through dedicated file APIs instead of forcing operators to patch them by hand.
- [MemPalace](https://github.com/neilharding/hermes_memorypalace) — workspace-scoped hierarchical memory provider with local ChromaDB + SQLite recall and explicit/implicit memory lanes.
- [Mnemosyne](https://github.com/AxDSan/mnemosyne) — local-first SQLite memory provider for Hermes with sub-millisecond retrieval, optional vector/FTS recall, MCP tools, and migration paths from cloud memory backends.
- [Hermes Memory Provider (Basic Memory)](https://github.com/basicmachines-co/hermes-basic-memory) — memory-provider plugin that swaps in a Basic Memory knowledge graph, adds search-before-answer recall, per-turn capture, session summaries, and direct `/bm-*` control commands.
- [LanceDB Hermes Agent Memory](https://github.com/lancedb/hermes-agent-memory) — LanceDB-backed memory provider that embeds a workspace-scoped LanceDB table with vector ANN recall, optional hybrid mode (vector + BM25 via RRF), and durable facts with typed memory lanes.
- [Hermes Memory pgvector](https://github.com/andreab67/hermes-memory-pgvector) — Postgres + pgvector memory provider for multi-agent fleets, with per-minion themes, async writing, and a single embedding endpoint — no LLM in the memory hot path.
- [MemOS](https://github.com/MemTensor/MemOS) — broader memory OS that now ships a Hermes local plugin with hybrid retrieval, smart deduplication, visual memory management, and a shared multi-agent knowledge layer.
- [agentmemory](https://github.com/rohitg00/agentmemory) — external long-term memory engine with a dedicated Hermes memory-provider plugin, REST/MCP access, session replay, and a real-time viewer for cross-session recall.
- [Supermemory](https://github.com/supermemoryai/supermemory) — official memory engine and app with Hermes support, hybrid search, connectors, and a native long-term context layer.
- [Open Second Brain](https://github.com/itechmeat/open-second-brain) — persistent memory layer that turns an Obsidian vault into Hermes Agent's memory store, with nighty dream passes to convert repeat corrections into confirmed preferences, deterministic confidence scoring, and an MCP server for cross-agent access.
- [EverOS](https://github.com/EverMind-AI/EverOS) — portable, self-evolving memory layer that works across Claude Code, Codex, OpenClaw, and Hermes, with hybrid retrieval and cross-agent memory sync.
- [LycheeMem](https://github.com/LycheeMem/LycheeMem) — lightweight long-term memory for LLM agents with MCP-native hybrid search, workspace-scoped recall, and first-class Hermes support.
- [Sibyl Memory](https://github.com/Sibyl-Labs/Sibyl-Memory) — persistent memory plugin with structured tiers, local SQLite, no vector DB, and SDK/CLI/MCP/plugin interfaces for Hermes.
- [mem9 Hermes Plugin](https://github.com/mem9-ai/mem9-hermes-plugin) — hosted persistent memory plugin for Hermes with semantic recall, turn-by-turn extraction, and quick CLI setup.
- [yantrikdb-hermes-plugin](https://github.com/yantrikos/yantrikdb-hermes-plugin) — self-maintaining memory provider with canonicalization, contradiction tracking, and explainable recall.
- [hermes-observational-memory](https://github.com/intertwine/hermes-observational-memory) — standalone memory-provider plugin that lets Hermes share a local markdown memory store with Claude Code and Codex, with searchable observations and optional writeback.
- [hermes-plugins](https://github.com/42-evey/hermes-plugins) — community plugin bundle with operational add-ons.
- [DashClaw](https://github.com/ucsandman/DashClaw) — governance runtime for AI agents that intercepts actions, enforces guard policies, requires approvals, and produces audit-ready decision trails.
- [hermes-otel](https://github.com/briancaffey/hermes-otel) — OpenTelemetry plugin for Hermes Agent that exports traces, metrics, and logs for integration with Grafana, Datadog, and other OTel-compatible backends.
- [ShellWard](https://github.com/jnMetaCode/shellward) — AI Agent security middleware with 8-layer defense, DLP data flow control, and prompt injection detection; zero dependencies, works as standalone SDK or OpenClaw plugin for Claude Code, Cursor, LangChain, and Hermes.
- [TokenTelemetry](https://github.com/VasiHemanth/tokentelemetry) — 100% local observability dashboard tracking token usage, costs, tool calls, session traces, and reasoning steps across Hermes Agent, Claude Code, Codex, Gemini CLI, and 30+ other platforms.
- [Pi Hermes Memory](https://github.com/chandra447/pi-hermes-memory) — persistent memory and learning loop for the Pi coding agent, porting Hermes-style session search, categorized memory, secret scanning, and background consolidation to Pi.
- [hermes-tools](https://github.com/axisdynamics/hermes-tools) — production-grade native plugin pack with inter-agent pub/sub, provider failover, and persistent memory primitives.
- [Hermes Plugin: Carabiner](https://github.com/donovan-yohan/hermes-plugin-carabiner) — Honcho-backed relationship memory plugin for specialist-agent handoffs, feedback loops, and peer context before delegations.
- [hermes-notification](https://github.com/itgoyo/hermes-notification) — tiny cross-platform plugin that fires native desktop notifications and sound when Hermes finishes a response.
- [hermes-web-search-plus](https://github.com/robbyczgw-cla/hermes-web-search-plus) — richer web-search routing.
- [cronalytics](https://github.com/8bit64k/cronalytics) — cron analytics and observability plugin that visualizes scheduled task history, runtimes, failures, and cost across Hermes cron jobs.
- [hermes-opencode-plugin](https://github.com/zaycruz/hermes-opencode-plugin) — lets Hermes hand software-engineering tasks to OpenCode’s multi-agent harness.
- [hermes-provider-switcher](https://github.com/tmdgusya/hermes-provider-switcher) — runs Claude Code through GLM, Kimi, MiniMax, and similar providers without manual shell env switching.
- [hermes-lcm](https://github.com/stephenschoettler/hermes-lcm) — lossless context-management layer built around DAG summaries and drill-back tools.
- [hermes-mindgraph-plugin](https://github.com/shuruheel/hermes-mindgraph-plugin) — semantic graph memory plugin that injects hybrid-retrieved goals, decisions, and structured knowledge into Hermes sessions.
- [Icarus Plugin](https://github.com/esaradev/icarus-plugin) — shared memory and self-training plugin for Hermes with training-data extraction plus fine-tune, evaluation, switch, and rollback workflows.
- [hermes-weather-plugin](https://github.com/FahrenheitResearch/hermes-weather-plugin) — weather-oriented plugin stack.
- [hermes-wxtrain-plugin](https://github.com/FahrenheitResearch/hermes-wxtrain-plugin) — training-data workflows for weather use cases.
- [hermes-plugin-chrome-profiles](https://github.com/anpicasso/hermes-plugin-chrome-profiles) — browser profile switching.
- [hermes-claude-code-rc](https://github.com/kevinmarmstrong/hermes-claude-code-rc) — plugin that exposes `/cc` commands through Hermes so you can start or monitor Claude Code remote-control sessions, headless runs, and shell commands from Telegram while keeping execution on your own machine.
- [hermes-a2a](https://github.com/iamagenius00/hermes-a2a) — zero-patch A2A plugin that injects messages into Hermes’s currently running session, stores separate conversation logs, and wakes the agent instantly via HMAC-signed webhooks instead of polling.
- [hermes-local-rig-accounting](https://github.com/GumbyEnder/hermes-local-rig-accounting) — plugin for local-LLM rig cost accounting that benchmarks throughput and converts electricity plus hardware depreciation into transparent per-token pricing for Hermes.
- [hermes-cloudflare](https://github.com/raulvidis/hermes-cloudflare) — alternative browser/rendering path.
- [Hermes Long-Run Orchestrator](https://github.com/yuzai-code/hermes-plugin-long-run-orchestrator) — plugin that dispatches 30+ minute coding tasks to Claude Code/Codex inside tmux sessions, with watchdog progress checks and Feishu/Telegram completion notifications, keeping Hermes as pure scheduler.
- [Hermes DeepL Plugin](https://github.com/drmzperx/hermes-deepl-plugin) — DeepL-backed translation and usage-quota tool with zero third-party dependencies, auto-selecting Free or Pro endpoint based on key format.
- [hermes-payguard](https://github.com/nativ3ai/hermes-payguard) — payment-control oriented plugin.
- [Hermes Dojo](https://github.com/Yonkoo11/hermes-dojo) — self-improvement loop that mines session failures, patches weak skills, and automates overnight analyze→improve→report cycles.
- [Ladybug Memory Plugin](https://github.com/Ladybug-Memory/hermes-memory-plugin) — local-first memory provider that keeps Hermes recall in a single on-disk `.lbdb` graph database with typed memories, weighted recall, and optional entity extraction.
- [Membase for Hermes](https://github.com/aristoapp/hermes-membase) — persistent memory plugin that pairs hybrid vector plus knowledge-graph recall with wiki retrieval and mirroring of Hermes’s built-in `MEMORY.md`, giving teams a shared long-term memory layer beyond local files.
- [Hermes Dashboard Plugin](https://github.com/tmdgusya/hermes-dashboard-plugin) — lightweight neubrutalist dashboard add-on built on the official plugin SDK, giving Hermes web users a unified tab for sessions, skills, profiles, token usage, and editable memory files.
- [Hermes Plugin: Credits](https://github.com/Atemndobs/hermes-plugin-credits) — dashboard plugin that adds a provider credit/quota widget to the Analytics tab, showing real-time remaining balance for OpenRouter, rate-limit utilization for Anthropic, and per-minute tokens for OpenAI/Codex without leaving the dashboard.
- [Hermes Trace](https://github.com/hlothaire/hermes-trace) — execution trace plugin that captures every turn, LLM call, tool call, subagent spawn, and approval request as a structured directed graph, with 18 lifecycle hooks, `/trace` slash command, ASCII Gantt timeline, Mermaid export, and CLI query tool.
- [Hermes TPS Counter](https://github.com/ryan-brosas/hermes-tps-counter) — lightweight plugin that tracks tokens-per-second throughput after each LLM call and injects live TPS, rolling average, peak, and token counts into the Hermes status bar.
- [Hermes Theme Editor](https://github.com/sanchomuzax/hermes-theme-editor) — dashboard plugin for visually creating, previewing, and activating custom YAML themes without hand-editing theme files.
- [Hermes Prompt Vault](https://github.com/LeventeNagy/hermes-prompt-vault) — prompt library plugin with /vault commands and a dashboard UI for saving, searching, and reusing prompts from any platform.
- [Hermes Workspace Dashboard Plugin](https://github.com/outsourc-e/hermes-workspace-plugin) — dashboard tab that embeds Hermes Workspace chat, with local port auto-detection and one-command install.
- [Hermes Canvas](https://github.com/tonbistudio/hermes-canvas) — dashboard plugin that turns the Hermes web dashboard into a live frontend creation studio with project scaffolding, dev-server control, and agent-driven editing.
- [Hermes Achievements](https://github.com/PCinkusz/hermes-achievements) — badge system for turning real Hermes session history into collectible dashboard achievements.
- [Agent Analytics Hermes Plugin](https://github.com/Agent-Analytics/agent-analytics-hermes-plugin) — dashboard-only analytics add-on that embeds account connection, project selection, and read-only web analytics inside the Hermes dashboard for operators who want campaign or site signals next to agent activity.
- [Hermes Labyrinth](https://github.com/stainlu/hermes-labyrinth) — read-only dashboard plugin that treats Hermes like a flight recorder, turning prompts, tool calls, failures, approvals, memory hits, cron runs, and subagents into exportable observability trails instead of another chat UI.
- [Honcho Memory Plugin](https://github.com/GumbyEnder/hermes-plugins) — dashboard plugin bundle centered on a Honcho memory panel with live stats, queue health, semantic search, and drill-down views for documents and message history.
- [GBrain](https://github.com/garrytan/gbrain) — production-grade knowledge graph brain layer by Garry Tan that performs synthesis, graph traversal, and gap analysis over personal and institutional knowledge, with hybrid vector/BM25 search, self-wiring entity graph, and crash-safe sub-agent job queue.
- [Memory OS](https://github.com/ClaudioDrews/memory-os) — 7-layer memory operating system for Hermes Agent with Qdrant vector recall, structured facts, fabric recall, auto-curated wiki, and surgical context injection, running locally with any LLM provider.

- [ClawSec](https://github.com/prompt-security/clawsec) — security skill suite maintained by Prompt Security with NVD-backed advisory feed, drift detection for SOUL.md and config files, supply-chain skill integrity verification, and a Hermes-specific `hermes-attestation-guardian` skill.
- [ClawShell](https://github.com/clawshell/clawshell) — runtime security layer for Hermes and OpenClaw that intercepts LLM API calls through a virtual-to-real key mapping proxy, scans for PII with configurable DLP patterns, isolates email access, and exposes usage auditing.
- [ComfyUI Skills for OpenClaw](https://github.com/HuangYuChuh/ComfyUI_Skills_OpenClaw) — turns any ComfyUI image-generation workflow into a callable Hermes/agent skill via CLI, with schema-based parameter mapping, multi-server routing, and dependency checking.
- [Hermes Multi-Agent Workflow](https://github.com/tonbistudio/hermes-multi-agent-workflow) — reusable triage pipeline template built on Hermes Kanban: `sources → intake → dedup → score → research → route → Human Gate → fulfill → deliver`, with domain-agnostic engine and triage.yaml config.
- [superpowers-zh](https://github.com/jnMetaCode/superpowers-zh) — Chinese enhanced edition of the superpowers skill pack (116K+ stars), adding 6 original skills and full localization for Hermes Agent alongside 15 other AI coding tools.
- [Draw.io Skill](https://github.com/Agents365-ai/drawio-skill) — generates draw.io diagrams from natural language with 6 presets, vision self-check, up to 5-round refinement, 10,000+ official shapes, and PNG/SVG/PDF export.
- [Hermes Tool Router](https://github.com/AtlasOmnia/hermes-tool-router) — conditional tool-schema loading that reduces first-turn token bloat by loading only the tools a prompt actually needs, with safe full-surface fallback for long or ambiguous requests.
- [Hermes D1 Memory](https://github.com/benben17/hermes-d1-memory) — Cloudflare D1-backed external memory provider using serverless edge-deployed SQLite with FTS5, offering zero-maintenance long-term memory persistence.
- [Hermes Voice HA Integration](https://github.com/rusty4444/hermes-voice-ha-integration) — Home Assistant voice stack that chains wake word detection, STT, Hermes LLM, and TTS back to HA media_player entirely on-device with no cloud dependency.
- [Hardmail](https://github.com/orlyjamie/hardmail) — hardened, shell-free native email tools for Hermes covering Gmail, IMAP, SMTP, and Resend with operator-approved sends and fail-closed security defaults.
- [Inkbox Plugin](https://github.com/inkbox-ai/hermes-agent-plugin) — Hermes Agent plugin for the Inkbox platform.
- [Multichannel Prompt Optimizer](https://github.com/Sahil-SS9/hermes-multichannel-prompt-optimizer) — plugin that rewrites user prompts before they reach the LLM with model-aware tailoring, quality scoring, and analytics across CLI, TUI, Discord, and Telegram.
- [LLM-Wiki Obsidian Hermes](https://github.com/r0b0tlab/llm-wiki_obsidian_hermes_r0b0tlabbra1n) — filesystem-first memory system bridging LLM-Wiki, Obsidian, and Hermes with Markdown source of truth, SQLite FTS5 search, secret scanning, and tier-based context packets.
- [Hermes Roaming](https://github.com/rtsitola/hermes-roaming) — memory roaming across machines via Syncthing with master-slave architecture and automatic import/export for multi-device Hermes setups.
- [Hermes WeChat Relay](https://github.com/c1422113471-cpu/hermes-wechat-relay) — profile-local platform plugin for relaying WeChat messages through an external bridge without modifying Hermes core or replacing the built-in weixin adapter.
- [Hermes Health Apollo](https://github.com/Infinite-Labs-AI/hermes-health-apollo) — local-first health intelligence plugin that connects wearable data, calendar context, and Gmail metadata so Hermes can answer questions between health status and next actions.
- [Hermes Tavern](https://github.com/gchigoo/hermes-tavern) — standalone SillyTavern-compatible roleplay and novel runtime that runs as a plugin against Hermes Agent gateways, supporting character card import, session management, and RP-specific slash commands.
- [Meshtastic Hermes Plugin](https://github.com/thpham/meshtastic-hermes-plugin) — Hermes plugin for LoRa mesh communication via Meshtastic: messaging tools, a node-interaction knowledge base, and a bidirectional gateway so the agent can chat over the mesh, with privacy-by-design packet handling.
- [Hermes Tesla Fleet Plugin](https://github.com/Oceanswave/hermes-tescmd-plugin) — native plugin for Tesla Fleet API operations with 175 typed tools, OAuth handling, signed vehicle commands, charging, climate, security, navigation controls, and safety confirmation gates.
- [Hermes Delegate Guard](https://github.com/mosqlee/hermes-delegate-guard) — two safety plugins that guard delegate_task calls: one blocks code-modification abuse (enforcing "Claude plans, Codex implements"), another detects and suppresses cascading tool-connectivity failures after guarded-tool errors.
- [Hermes Mattermost Enhancer](https://github.com/colin-chang/hermes-plugin-mattermost-enhancer) — plugin that makes Hermes smarter inside Mattermost with dangerous-command approval cards via DM, /model switching, WebSocket stability improvements, and configurable approval persistence.

## Deployment and Operations

- [Contributing Guide](https://hermes-agent.nousresearch.com/docs/developer-guide/contributing)
- [Gateway Internals](https://hermes-agent.nousresearch.com/docs/developer-guide/gateway-internals)
- [Cron Internals](https://hermes-agent.nousresearch.com/docs/developer-guide/cron-internals)
- [Tools Runtime](https://hermes-agent.nousresearch.com/docs/developer-guide/tools-runtime)
- [Provider Runtime](https://hermes-agent.nousresearch.com/docs/developer-guide/provider-runtime)
- [Adding Providers](https://hermes-agent.nousresearch.com/docs/developer-guide/adding-providers) — official contributor guide for adding or overriding first-class inference providers, including the plugin fast path for OpenAI-compatible backends and the deeper path for native adapters.
- [Trajectory Format](https://hermes-agent.nousresearch.com/docs/developer-guide/trajectory-format)
- [nix-hermes-agent](https://github.com/0xrsydn/nix-hermes-agent) — Nix/NixOS packaging.
- [hermes-agent-docker](https://github.com/xmbshwll/hermes-agent-docker) — simple Docker image approach.
- [hermes-agent-template](https://github.com/Crustocean/hermes-agent-template) — deployment template for cloud setups.
- [hermes-suite](https://github.com/sunnysktsang/hermes-suite) — single-container Docker/Podman image that packages hermes-agent, hermes-webui, and hermes-dashboard for rootless and multi-service deployments.
- [HermesHQ](https://github.com/jpalmae/hermeshq) — Docker-first control plane for managing multiple Hermes Agent instances from one web app.
- [portainer-stack-hermes](https://github.com/ellickjohnson/portainer-stack-hermes) — Portainer and Docker Compose style deployment.
- [hermes-autonomous-server](https://github.com/JackTheGit/hermes-autonomous-server) — unattended server-style deployment.
- [hermes-ha-addon](https://github.com/WolframRavenwolf/hermes-ha-addon) — packages Hermes as a Home Assistant add-on with persistent terminal and gateway access.
- [hermes-agent-control-room](https://github.com/CryptoDmitry/hermes-agent-control-room) — control-room-first template for managing Hermes agents from one VPS to specialist teams with orchestrated workflows.
- [Unofficial Hermes Agent Helm Chart](https://github.com/ultraworkers/hermes-agent-helm-chart) — Kubernetes packaging with explicit single-writer storage guardrails, values schema, and cloud-native composition points for teams that want a more operator-friendly deployment path than raw Docker Compose.
- [hermesclaw](https://github.com/TheAiSingularity/hermesclaw) — runs Hermes inside NVIDIA OpenShell-style sandbox boundaries for stronger containment.
- [openclaw-to-hermes](https://github.com/0xNyk/openclaw-to-hermes) — migration helper for older OpenClaw users.
- [Honcho Self-Hosted for Hermes](https://github.com/elkimek/honcho-self-hosted) — self-hosted memory backend setup.
- [Hermes Memory Installer](https://github.com/mage0535/hermes-memory-installer) — one-click persistent memory stack with SQLite FTS5, lifecycle guards, and gbrain knowledge-graph sync.
- [Hindsight](https://github.com/vectorize-io/hindsight) — another long-term memory layer that can complement Hermes workflows.
- [MNEMOS](https://github.com/ncz-os/mnemos) — production-grade memory operating system for agentic AI with four-backend persistence (PostgreSQL, Oracle 26ai, IBM Db2, SQLite), dream-state pipeline, GDPR compliance, and a unified MCP interface — supports Hermes alongside Claude Code, OpenClaw, LangChain, and others.
- [Scope Recall Hermes](https://github.com/410979729/scope-recall-hermes) — scoped memory provider with SQLite truth, LanceDB semantic recall, and nightly workflow digest for Hermes Agent.

- [NVIDIA NemoClaw](https://github.com/NVIDIA/NemoClaw) — NVIDIA's open-source sandboxed agent runtime with a dedicated Hermes quickstart, providing hardened execution environments, network policy enforcement, and managed inference inside OpenShell. Apache 2.0.
- [NemoClaw Community](https://github.com/NVIDIA/nemoclaw-community) — NVIDIA's community-driven repository of examples, showcases, and integrations for composing constrained, inspectable agent workflows with NemoClaw blueprints.
- [tenbox](https://github.com/78/tenbox) — lightweight x86-64/arm64 Virtual Machine Monitor for running Hermes inside hardware-accelerated VMs, offering a VM-level isolation boundary as an alternative to container-based sandboxing. Cross-platform (Windows WHVP, macOS Hypervisor Framework, Linux KVM).
- [Mem0 Integration](https://docs.mem0.ai/integrations/hermes) — official Mem0 memory provider plugin for Hermes with automatic background sync, zero-latency prefetch, and semantic reranking.
- [hermes-patches](https://github.com/Cyrene963/hermes-patches) — community patch collection for Hermes Agent covering memory metacognition, structured memory graph tools, hybrid skill selectors, multi-user isolation, and Telegram context enhancements with an overlay-first install strategy.
- [ClawPhone](https://github.com/marshallrichards/ClawPhone) — scripts and tweaks for running Hermes Agent (and OpenClaw, Claude Code, Codex) on Android smartphones with Termux-based deployment.
- [Hermes Agent on Android](https://github.com/AbuZar-Ansarii/Hermes-Agent-On-Android) — one-line Termux installation to run Hermes Agent on any Android device.
- [hermes-concurrent-agents](https://github.com/r0b0tlab/hermes-concurrent-agents) — deploy multiple concurrent Hermes workers on unified-memory GPUs with profile isolation, Kanban coordination, and crash recovery for maximum throughput.
- [Hermes Operator](https://github.com/UndermountainCC/hermes-operator) — Kubernetes operator for managing Hermes Agent deployments with declarative CRDs.
- [ClawFleet](https://github.com/clawfleet/ClawFleet) — open-source fleet manager that deploys multiple Hermes (and OpenClaw) agents in isolated Docker containers with a browser dashboard, one-line install, and version pinning.
- [Hermes Claude Code Local](https://github.com/KaiFelixBennett/hermes-claude-code-local) — run Hermes Agent plus Claude Code locally on llama.cpp for zero API costs, with benchmarks showing a 4-hour / 7M-token session that would have cost $94 on Claude Opus.
- [Hermes Swarm Map](https://github.com/NimbleCoAI/hermes-swarm-map) — multiplayer admin and orchestration platform for managing multiple Hermes agent instances from one dashboard, with setup wizard, model cascades, multi-tenant security, budget enforcement, and platform connections for Telegram, Signal, and Mattermost.
- [Hermes Cockpit](https://github.com/goktugozdem2/hermes-cockpit) — multi-project mission control dashboard for operators running autonomous workers, cron jobs, coding agents, and deploys across many products, with project health cards, task queues, and cross-project alerts.
- [Hermes Advanced Profile Manager](https://github.com/MaverickKB/hermes-advanced-profile-manager) — dependency-light local WebUI for full Hermes profile management: readiness verdicts, skills & skill groups, toolsets, MCP servers, providers, delegation authority, backups, audit, and an interactive system graph.
- [Hermes Memory-OS](https://github.com/btnalit/Hermes-Memory-OS) — engineering-focused agent OS runtime for Hermes with dual-engine memory (SQLite + flat files), deterministic state machine locks, temporal-decay weighted retrieval, and an owner-review feedback loop.
- [Nexus Memory](https://github.com/Neboy72/nexus-memory) — universal self-hosted memory layer for AI agents: hybrid search (vector + BM25), three deployment modes (Hermes plugin, OpenClaw plugin, MCP server), and local-first storage.
- [hermes-tescmd-plugin](https://github.com/Oceanswave/hermes-tescmd-plugin) — native Tesla Fleet API operations for Hermes, covering vehicle state, charging, climate, navigation, security, and energy sites through structured tools with confirmation gates. (Also listed under Plugins.)

- [hermes-alpha](https://github.com/kaminocorp/hermes-alpha) — cloud-deployed version of Hermes Agent with streamlined provisioning for users who want a managed cloud runtime instead of self-hosting.
- [Hermes Agent One-Click Kit](https://github.com/sodam-ai/Hermes-Agent_One-Click_Kit) — beginner-friendly Windows .bat installer that sets up Hermes Agent, connects messengers, and handles login with double-click execution and Korean/English docs.
- [claude-tap](https://github.com/liaohch3/claude-tap) — local proxy and trace viewer for AI coding agents that intercepts and inspects API traffic from Hermes, Claude Code, Codex, Gemini CLI, and others, exposing system prompts, tool calls, streaming responses, and token usage in a self-contained HTML viewer.

## Integrations and Bridges

- [Integrations Overview](https://hermes-agent.nousresearch.com/docs/integrations)
- [Providers](https://hermes-agent.nousresearch.com/docs/integrations/providers)
- [Adding a Platform Adapter](https://hermes-agent.nousresearch.com/docs/developer-guide/adding-platform-adapters) — official guide for shipping new messaging-platform adapters through the plugin system, covering gateway registration, auth, config, cron delivery, and prompt hints.
- [QQ Bot](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/qqbot) — official guide for connecting Hermes to QQ via the official QQ Bot API v2, including private chat, group @ mentions, guild messages, and voice transcription.
- [Hermes Home Assistant Integration](https://github.com/WolframRavenwolf/hermes-ha-integration)
- [gridmint/hermes-telegram](https://github.com/gridmint/hermes-telegram) — MTProto / Telethon adapter that lets Hermes operate as a real Telegram user account instead of only through the Bot API gateway.
- [hermes-android](https://github.com/raulvidis/hermes-android) — Android bridge.
- [hermes-miniverse](https://github.com/teknium1/hermes-miniverse) — bridge into Miniverse environments.
- [hermes-agent-acp-skill](https://github.com/Rainhoole/hermes-agent-acp-skill) — bridge patterns for Hermes with other coding agents.
- [hermes-computer-use](https://github.com/Noah3521/hermes-computer-use) — pixel-level browser automation MCP server for Hermes, driving stock Chrome through Xvfb and OS-level input for harder-to-detect web workflows.
- [Hermes Skills MCP Server](https://github.com/poogas/hermes-skill-installer) — MCP bridge that lets Hermes search, inspect, install, list, and remove skills on the host even when the agent runs inside an isolated container.
- [hermes-mcp](https://github.com/mlennie/hermes-mcp) — MCP server that lets Claude Desktop, Claude.ai, and any MCP client delegate tasks to a local Hermes Agent (cron jobs, web search, email, browser, messaging) via OAuth 2.1 and cloudflared tunnel for remote access.
- [evey-bridge-plugin](https://github.com/42-evey/evey-bridge-plugin) — Hermes and Claude Code bridge idea.
- [hermes-claude-code](https://github.com/DevvGwardo/hermes-claude-code) — MCP server and plugin bridge that delegates coding-heavy tasks from Hermes to Claude Code CLI sub-agents for implementation, testing, and git work.
- [reina](https://github.com/Crustocean/reina) — Hermes-oriented integration inside the Crustocean platform.
- [hermes-claude-auth](https://github.com/kristianvast/hermes-claude-auth) — Claude Code OAuth bypass tool for Hermes Agent that lets you access Claude models without the standard authentication flow.
- [hermes-blockchain-oracle](https://github.com/gizdusum/hermes-blockchain-oracle) — blockchain analytics via MCP-style integration.
- [hermes-council](https://github.com/Ridwannurudeen/hermes-council) — adversarial multi-view decision support.
- [hermes-CCC](https://github.com/AlexAI-MCP/hermes-CCC) — ports core Hermes ideas and skill workflows into Claude Code Channel.
- [Composio MCP Integration](https://composio.dev/toolkits/composio/framework/hermes-agent) — connect Hermes to 1,000+ SaaS apps through Composio's SOC 2 compliant MCP bridge, with managed OAuth, tool routing, and parallel execution.
- [LangBot](https://github.com/langbot-app/LangBot) — production-grade multi-platform AI bot platform (16K+ stars) that supports Hermes Agent as a backend, covering Discord, Slack, LINE, Telegram, WeChat, Feishu, DingTalk, and QQ with built-in knowledge base orchestration and plugin system.
- [hermesclaw WeChat](https://github.com/AaronWong1999/hermesclaw) — run Hermes Agent and OpenClaw on the same WeChat account for unified messaging.
- [clawmes](https://github.com/clawnchdev/clawmes) — Hermes Agent plugin for crypto workflows: wallet management, DEX trading, lending and staking, governance voting, and on-chain automation with 100% test coverage.
- [hermes-nextcloud](https://github.com/adnw-vinc/hermes-nextcloud) — Hermes skill for managing Nextcloud files, notes, calendar, tasks, and contacts via WebDAV and CalDAV.
- [CodeGraph](https://github.com/colbymchenry/codegraph) — local pre-indexed code knowledge graph that replaces expensive grep/read cycles with direct SQLite queries, cutting token usage and tool calls by 50–90% for Hermes and other coding agents.
- [Infisical agent-vault](https://github.com/Infisical/agent-vault) — HTTP credential proxy and vault for AI agents including Hermes, Claude Code, and OpenClaw, providing centralized secret management with fine-grained access control for agent harnesses.

- [wechat-acp](https://github.com/formulahendry/wechat-acp) — bridge WeChat chat messages to any ACP-compatible AI agent including Hermes, Claude, Codex, and Gemini, covering personal chat, group chat, and bot flows.
- [agentcookie](https://github.com/mvanhorn/agentcookie) — keeps agent sessions synced across Macs over Tailscale, so Hermes or OpenClaw on a remote machine wakes up authenticated and ready — peer-to-peer, no cloud middleman.
- [Hermes Agent QQ Plugin](https://github.com/shynloc/Hermes-Agent-QQ-Plugin) — QQ chat plugin adapted from the OpenClaw QQ bot for Hermes Agent, enabling QQ messaging as a native channel.
- [hermes-multitenancy](https://github.com/eggyrooch-blip/hermes-multitenancy) — Feishu bot multi-tenant routing plugin for Hermes Agent, enabling one bot instance to serve multiple users with isolated profiles.
- [hermes-tweet](https://github.com/Xquik-dev/hermes-tweet) — native Hermes Agent plugin for X/Twitter automation through Xquik, with posting, scheduling, and engagement workflows.
- [Hermes Lansenger Adapter](https://github.com/lansenger-pm/hermes-lansenger-adapter) — enterprise messaging platform adapter for Hermes Agent, providing WebSocket real-time messaging, approval cards, media tools, and markdown delivery for the Lansenger (蓝信) ecosystem — pure plugin, zero core modifications.

## Research, Multi-Agent, and Domain Projects

### Research and multi-agent work

- [Ankh.md](https://github.com/Abruptive/Ankh.md) — swarm-style multi-agent coordination.
- [bigiron](https://github.com/supermodeltools/bigiron) — AI-native software delivery with multiple agent roles.
- [gladiator](https://github.com/runtimenoteslabs/gladiator) — experiment in autonomous competitive agent companies.
- [opencode-hermes-multiagent](https://github.com/1ilkhamov/opencode-hermes-multiagent) — multi-agent orchestration around OpenCode and Hermes.
- [NemoHermes](https://github.com/Hmbown/NemoHermes) — GPU/capability routing layer idea.
- [hermes-nightshift-glm](https://github.com/Microck/hermes-nightshift-glm) — overnight code-quality bot that plans, implements, reviews, and opens PRs or issues.
- [Hermes-Agent-Online-RL](https://github.com/ar0cket1/Hermes-Agent-Online-RL) — online RL loop for adapting Hermes-backed local or hosted models from live feedback.
- [Hermes Incident Commander](https://github.com/Lethe044/hermes-incident-commander) — autonomous SRE operator that detects incidents, fans out diagnosis with subagents, heals services, and turns novel incidents into reusable prevention skills.
- [Hermes Skill Forge](https://github.com/Lethe044/hermes-skill-marketplace) — experimental self-evolving agent that turns repeated work into tested, publishable skills instead of stopping at one-off task completion.
- [Hermes Agent (CaMeL fork)](https://github.com/nativ3ai/hermes-agent-camel) — Hermes fork with opt-in CaMeL trust boundaries and runtime guardrails against indirect prompt injection.
- [Hermes Skill Distillation](https://github.com/beardthelion/hermes-skill-distillation) — hackathon pipeline that turns real task trajectories into fine-tuning data for Hermes 4.
- [Oh My Hermes](https://github.com/Salomondiei08/oh-my-hermes) — opinionated autonomous workflow layer with 23 skills and 5 workflows that turns Hermes into a full-stack CTO with Kanban management, GitHub issue triage, security scanning, and human-in-the-loop deployment.
- [hermes-agent-rs](https://github.com/Lumio-Research/hermes-agent-rs) — complete Rust reimplementation of Hermes as a single ~16MB static binary with zero dependencies, 10 LLM providers, 30+ tools, 17 platform adapters, 8 memory backends, and Tokio async runtime; runs on Raspberry Pi and air-gapped servers.
- [go-magic](https://github.com/magicwubiao/go-magic) — high-performance, ultra-lightweight Go reimplementation of Hermes Agent with a React/TypeScript web dashboard, targeting single-binary deployment for resource-constrained environments.
- [Hermes Turbo Agent](https://github.com/wesleysimplicio/hermes-turbo-agent) — performance benchmarks, optimized hot-paths, and a turbo scoring system for production Hermes deployments targeting 100x faster execution.
- [Perseus](https://github.com/tcconnally/perseus) — live context engine for AI assistants with resolve-before-context, session waypoints, and tool-selection intelligence designed for Hermes Agent.
- [Hermes Code Bridge](https://github.com/xuyang-liu16/hermes-code-bridge) — use Hermes Agent as the control plane for local coding agents like Codex, Kimi Code, Claude Code, OpenCode, and Gemini CLI.
- [Hermes System Doctor](https://github.com/AlekseiUL/hermes-system-doctor) — diagnostic and approval-gated repair planning tool for Hermes Agent that identifies issues before they become failures.
- [Hermes Bumblebee Bridge](https://github.com/Deconstruct2021/hermes-bumblebee-bridge) — read-only supply-chain scanning for Hermes powered by Perplexity's Bumblebee with daily scans, Telegram alerts, and JARVIS-style narration.
- [Hermes Compression Eval](https://github.com/NousResearch/hermes-compression-eval) — official offline evaluation harness for Hermes's ContextCompressor that runs probe-based quality scoring across accuracy, context awareness, and artifact trail dimensions.
- [Olympian](https://github.com/jahilldev/olympian) — AI dark factory that drives Hermes Agent through the full issue-to-PR lifecycle: plan, implement with multi-revision gates, self-review with confidence scoring, and draft PR, with a human only ever approving the plan and the final PR.
- [Home AI Mesh](https://github.com/punchtaylor/home-ai-mesh) — MIT-licensed practical guide for building a multi-node home AI mesh with Raspberry Pis, Jetsons, and GPUs coordinated over MQTT and Hermes Agent, with failover, finance, voice, and watchdog nodes.
- [Autocontext](https://github.com/greyhaven-ai/autocontext) — recursive self-improving harness for AI agents that iteratively refines approaches on complex goals, with native Hermes Agent skill export for seamless integration into any profile.

### Domain-specific applications

- [hermescraft](https://github.com/bigph00t/hermescraft) — persistent Minecraft companion.
- [hermes-embodied](https://github.com/bryercowan/hermes-embodied) — robotics-oriented project.
- [Hermes-mars-rover](https://github.com/Snehal707/Hermes-mars-rover) — rover simulation use case.
- [anihermes](https://github.com/rodmarkun/anihermes) — anime/media server style interface.
- [job-scout-agent](https://github.com/Christabel337/job-scout-agent) — job search automation.
- [hermes-ai-infrastructure-monitoring-toolkit](https://github.com/JackTheGit/hermes-ai-infrastructure-monitoring-toolkit) — infra monitoring and alerting.
- [hermes-legal](https://github.com/Lethe044/hermes-legal) — legal review use case.
- [hermes-startup-architect](https://github.com/dlkakbs/hermes-startup-architect) — startup planning and materials generation.
- [mercury](https://github.com/hxsteric/mercury) — blockchain and cash-flow analysis.
- [hermes-research-agent](https://github.com/Aum08Desai/hermes-research-agent) — autonomous research workflow.
- [Learn Hermes Agent](https://github.com/longyunfeigu/learn-hermes-agent) — 27-chapter hands-on tutorial for building an autonomous AI agent from scratch in Python, covering the agent loop, tools, memory, skills, MCP, multi-platform gateway, and self-evolution — inspired by Hermes Agent.
- [hermes-agent-team](https://github.com/linke-ai/hermes-agent-team) — local multi-agent team collaboration web system built on Hermes Agent with a Chinese-language UI and role-based agent orchestration.
- [Hermes Forge](https://github.com/Mahiruxia/hermes-forge) — local-first desktop workbench integrating auto-deploy, model sync, Windows bridge, WeChat gateway, file attachments, permission approval, and GitHub auto-update.
- [RunbookHermes](https://github.com/Tommy-yw/RunbookHermes) — Hermes-native AIOps agent for evidence-driven incident response, approval-gated remediation, and runbook learning from past incidents.
- [hermes-life-os](https://github.com/Lethe044/hermes-life-os) — personal OS agent that learns who you are, detects life patterns, and grows smarter about you every day, combining memory, cron, and Atropos RL for continuous self-improvement.
- [Hermes Dynamic Workflows](https://github.com/lingjiuu/hermes-dynamic-workflows) — Claude Code-style dynamic workflow engine for Hermes that lets the model write and execute sandboxed Python scripts on the fly for large-scale orchestration tasks.

## Guides, Books, Videos, and Related Lists

### Community docs and guides

- [hermes-agent-docs](https://github.com/mudrii/hermes-agent-docs) — community docs supplement.
- [HermesWiki](https://github.com/martymcenroe/HermesWiki) — community-maintained wiki.
- [Hermes-Wiki](https://github.com/cclank/Hermes-Wiki) — source-verified architecture wiki with deep codebase pages.
- [llm-wiki-compiler](https://github.com/atomicmemory/llm-wiki-compiler) — general tool for compiling raw sources into an interlinked markdown wiki that Hermes users can query and extend over time.
- [hermes-agent-anatomy](https://github.com/anneheartrecord/hermes-agent-anatomy) — Chinese codebase anatomy series with diagrams and module-by-module analysis.
- [hermes-optimization-guide](https://github.com/OnlyTerp/hermes-optimization-guide) — practical setup, migration, LightRAG, Telegram, and skill-building guide.
- [Hermes Agent Source Code Guide](https://github.com/xiehongyu777/hermes-agent-guide) — Chinese-language source code learning guide that walks through Hermes Agent internals module by module.
- [Hermes Agent Setup and Tutorial Guide (DataCamp)](https://www.datacamp.com/tutorial/hermes-agent) — comprehensive beginner-to-intermediate tutorial covering installation, local models, research workflows, and troubleshooting from a well-known educational platform.
- [Hermes Agent + Honcho](https://docs.honcho.dev/v3/guides/integrations/hermes) — Honcho’s own integration guide explaining how Hermes uses peer modeling, durable writeback, and semantic memory tools beyond the built-in local files.
- [Hermes Agent v0.13 Reference](https://blakecrosley.com/guides/hermes) — detailed independent reference that pulls together architecture, installation, provider auth, security, and everyday CLI operations.
- [Goal Video Resources](https://github.com/nemanjadotcom/goal-video-resources) — prompts, AGENTS.md, and SOUL.md files from the "I Was Wrong About Hermes Agent /goal" video.
- [Hermes Telegram Artifacts](https://github.com/camel-vibe/hermes-telegram-artifacts) — standalone artifact server plus skill for delivering interactive HTML widgets via Telegram Mini Apps in Hermes Agent.
- [Hermes Agent Book](https://github.com/ZhangHanDong/hermes-book) — source-level Chinese book that walks through Hermes architecture, prompt assembly, tools, memory providers, CLI/gateway internals, and runtime design tradeoffs chapter by chapter.
- [Hermes Atlas](https://github.com/ksimback/hermes-ecosystem) — community-maintained ecosystem map and companion site covering vetted Hermes projects, themed resource lists, live repo metadata, beginner guides, and narrative reports on the broader ecosystem.
- [Hermes Atlas MCP](https://github.com/ksimback/hermes-atlas-mcp) — MCP server that exposes the live Hermes Atlas catalog to Claude Desktop, Cursor, Continue, and other MCP-aware clients so they can search Hermes tools, guides, and ecosystem projects from inside the agent.
- [Hermes-Agent-Action-Plan](https://github.com/vectrocomputers/Hermes-Agent-Action-Plan) — privacy-first operating philosophy and configuration playbook.
- [hermes-fleet-setup](https://github.com/Pu11en/hermes-fleet-setup) — practical 10-bot Telegram fleet guide with isolated profiles, per-agent GitHub auth, and start/stop scripts.
- [LLM-WIKI-TO-AGENT-Template](https://github.com/AlexChanshuo/LLM-WIKI-TO-AGENT-Template) — reproducible blueprint for combining an Obsidian vault, a Hermes Telegram librarian, and GitHub backups into a single personal knowledge workflow.
- [Hermes Memory Stack](https://github.com/yelixir-dev/hermes-memory-stack) — modular bootstrap stack for layered memory, llmwiki routing, and optional NotebookLM/source-pack workflows.
- [hermes-wsl-ubuntu](https://github.com/metantonio/hermes-wsl-ubuntu) — Windows WSL2 setup path.

### Books and curated lists

- [Hermes Agent Orange Book](https://github.com/alchaincyf/hermes-agent-orange-book) — bilingual community book with downloadable PDFs that goes beyond setup into memory, skills, self-improvement loops, and multi-agent usage patterns.
- [Hermes Agent Guide (白皮书 / Whitepaper)](https://github.com/jwangkun/hermes-agent-guide) — large Chinese markdown book that turns scattered docs into a structured path covering architecture, deployment, migration, monetization, and multi-agent operation.
- [awesome-hermes-usecases](https://github.com/aliaihub/awesome-hermes-usecases) — evidence-backed catalog of real-world Hermes use cases, with primary sources and runnable demos.
- [awesome-hermes-agent](https://github.com/0xNyk/awesome-hermes-agent) — another curated resource list worth checking alongside this repo.
- [awesome-hermes-agent (SamurAIGPT)](https://github.com/SamurAIGPT/awesome-hermes-agent) — alternative curated list with maturity labels (production/beta/experimental) covering skills, plugins, tools, and integrations for Hermes Agent.
- [awesome-hermes-agent-zh](https://github.com/jefferyjob/awesome-hermes-agent-zh) — Chinese-language curated list of Hermes Agent skills, tools, integrations, and community resources.
- [Hermes Agent 中文站](https://github.com/zcweah1981/awesome-hermes-agent-zh) — practical Chinese entry point covering onboarding paths, domestic deployment, OpenClaw migration, troubleshooting, and downloadable setup packs.

### Videos

- [Hermes Agent Skills Tutorial](https://www.youtube.com/watch?v=cyn2JPlvTG4) — focused walkthrough on using and creating custom skills.
- [Hermes Agent Dashboard (Setup Guide and Overview)](https://www.youtube.com/watch?v=GfQEdMZ9LlA) — practical tour of the local web dashboard for operators who prefer a browser control surface.
- [Hermes Agent Setup: Install, Configure, and Run It 100% Free](https://www.youtube.com/watch?v=9v1DyzP7-58)
- [I am Switching to Hermes Agent](https://www.youtube.com/watch?v=J-kSdzHr9Ek)
- [Hermes AI Agent Explained: Persistent AI That Runs 24/7](https://www.youtube.com/watch?v=ZhCIZ-ZTcyE)
- [Hermes Agent: Zero to Personal AI Assistant (1-Hour Course)](https://www.youtube.com/watch?v=gb5TlGw6Uks) — complete walkthrough from scratch on a VPS, covering installation, configuration, skill setup, and gateway connections.
- [FULL Hermes Agent Tutorial For Beginners in 2026](https://www.youtube.com/watch?v=4ftONmdO9yo) — beginner-focused tutorial covering setup, Telegram integration, and practical usage patterns.

## Community

- [Discord](https://discord.gg/NousResearch)
- [GitHub Issues](https://github.com/NousResearch/hermes-agent/issues)
- [GitHub Discussions](https://github.com/NousResearch/hermes-agent/discussions)

## Contributing

Contributions are welcome.

Good additions include:

- production deployments
- serious plugins and skills
- high-signal tutorials
- case studies and write-ups
- domain applications that are still maintained
- ecosystem maps, dashboards, and operational tooling

Please avoid low-effort forks, abandoned experiments with no README, or duplicate links that do not add new value.

## License

MIT for this repository unless a linked resource states otherwise.
