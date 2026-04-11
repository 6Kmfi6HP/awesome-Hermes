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
- [Team Telegram Assistant Guide](https://hermes-agent.nousresearch.com/docs/guides/team-telegram-assistant)
- [Daily Briefing Bot Guide](https://hermes-agent.nousresearch.com/docs/guides/daily-briefing-bot)
- [Automate with Cron](https://hermes-agent.nousresearch.com/docs/guides/automate-with-cron)
- [Use MCP with Hermes](https://hermes-agent.nousresearch.com/docs/guides/use-mcp-with-hermes)
- [Use SOUL.md with Hermes](https://hermes-agent.nousresearch.com/docs/guides/use-soul-with-hermes)
- [Use Voice Mode with Hermes](https://hermes-agent.nousresearch.com/docs/guides/use-voice-mode-with-hermes)

## Workspaces and User Interfaces

- [Hermes Workspace](https://github.com/outsourc-e/hermes-workspace) — the best-known browser workspace for Hermes with chat, terminal, memory, skills, and inspector.
- [Pan UI](https://github.com/Euraika-Labs/pan-ui) — another self-hosted workspace focused on operating Hermes with a fuller control panel.
- [Hermes Desktop](https://github.com/fathah/hermes-desktop) — native desktop companion that handles install, setup, chat, sessions, memory, skills, and settings.
- [Hermes WebUI](https://github.com/nesquena/hermes-webui) — mature browser UI that aims for near CLI parity, including chat, sessions, file browsing, and remote access workflows.
- [Hermes WebUI (ops dashboard)](https://github.com/sanchomuzax/hermes-webui) — read-only monitoring and configuration dashboard for sessions, cron, skills, and config data.
- [Hermes for Web](https://github.com/reallygood83/hermes-for-web) — personalized browser workbench with onboarding packs, artifacts, and memory-aware startup flows.
- [Portable Hermes Agent](https://github.com/rookiemann/portable-hermes-agent) — packaged desktop-style distribution for users who want an easier Windows path.
- [Hermes Dashboard](https://github.com/Bichev/hermes-dashboard) — analytics and cost-monitoring dashboard for sessions, tools, and API usage.
- [Hermes Dashboard (live wiki)](https://github.com/Kori-x/hermes-dashboard) — real-time observability dashboard plus an auto-generated local wiki for skills, plugins, tools, memory, and soul files.
- [Hermes HUD UI](https://github.com/joeynyc/hermes-hudui) — browser-based consciousness monitor for Hermes that visualizes memory, token costs, skills, cron jobs, and growth snapshots directly from ~/.hermes/.
- [Hermes HUD](https://github.com/joeynyc/hermes-hud) — terminal-first companion to the HUD UI for live inspection of memory, skills, mistakes, tool usage, and ongoing agent growth.

## Skills, Plugins, and Extensions

### Skills and skill ecosystems

- [Bundled Skills Catalog](https://hermes-agent.nousresearch.com/docs/reference/skills-catalog)
- [Optional Skills Catalog](https://hermes-agent.nousresearch.com/docs/reference/optional-skills-catalog)
- [Creating Skills](https://hermes-agent.nousresearch.com/docs/developer-guide/creating-skills)
- [Work with Skills](https://hermes-agent.nousresearch.com/docs/guides/work-with-skills)
- [agentskills.io](https://agentskills.io) — open skill ecosystem used across multiple agent stacks.
- [wondelai/skills](https://github.com/wondelai/skills) — broad community skill collection.
- [Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) — large security-oriented skill library.
- [chainlink-agent-skills](https://github.com/smartcontractkit/chainlink-agent-skills) — agent skills around Chainlink workflows.
- [black-forest-labs/skills](https://github.com/black-forest-labs/skills) — skills around FLUX and image workflows.
- [pydantic-ai-skills](https://github.com/DougTrajano/pydantic-ai-skills) — typed, structured skill workflows.
- [litprog-skill](https://github.com/tlehman/litprog-skill) — literate-programming-oriented skill workflow.
- [hermes-skill-factory](https://github.com/Romanescu11/hermes-skill-factory) — generates reusable skills from repeated work.
- [hermeshub](https://github.com/amanning3390/hermeshub) — community discovery hub for Hermes skills.
- [skilldock.io](https://github.com/chigwell/skilldock.io) — cross-agent skill registry.

### Plugins and add-ons

- [Plugins](https://hermes-agent.nousresearch.com/docs/user-guide/features/plugins)
- [Memory Provider Plugin Guide](https://hermes-agent.nousresearch.com/docs/developer-guide/memory-provider-plugin)
- [hermes-plugins](https://github.com/42-evey/hermes-plugins) — community plugin bundle with operational add-ons.
- [hermes-web-search-plus](https://github.com/robbyczgw-cla/hermes-web-search-plus) — richer web-search routing.
- [hermes-opencode-plugin](https://github.com/zaycruz/hermes-opencode-plugin) — lets Hermes hand software-engineering tasks to OpenCode’s multi-agent harness.
- [hermes-lcm](https://github.com/stephenschoettler/hermes-lcm) — lossless context-management layer built around DAG summaries and drill-back tools.
- [hermes-weather-plugin](https://github.com/FahrenheitResearch/hermes-weather-plugin) — weather-oriented plugin stack.
- [hermes-wxtrain-plugin](https://github.com/FahrenheitResearch/hermes-wxtrain-plugin) — training-data workflows for weather use cases.
- [hermes-plugin-chrome-profiles](https://github.com/anpicasso/hermes-plugin-chrome-profiles) — browser profile switching.
- [hermes-cloudflare](https://github.com/raulvidis/hermes-cloudflare) — alternative browser/rendering path.
- [hermes-payguard](https://github.com/nativ3ai/hermes-payguard) — payment-control oriented plugin.

## Deployment and Operations

- [Contributing Guide](https://hermes-agent.nousresearch.com/docs/developer-guide/contributing)
- [Gateway Internals](https://hermes-agent.nousresearch.com/docs/developer-guide/gateway-internals)
- [Cron Internals](https://hermes-agent.nousresearch.com/docs/developer-guide/cron-internals)
- [Tools Runtime](https://hermes-agent.nousresearch.com/docs/developer-guide/tools-runtime)
- [Provider Runtime](https://hermes-agent.nousresearch.com/docs/developer-guide/provider-runtime)
- [Trajectory Format](https://hermes-agent.nousresearch.com/docs/developer-guide/trajectory-format)
- [nix-hermes-agent](https://github.com/0xrsydn/nix-hermes-agent) — Nix/NixOS packaging.
- [hermes-agent-docker](https://github.com/xmbshwll/hermes-agent-docker) — simple Docker image approach.
- [hermes-agent-template](https://github.com/Crustocean/hermes-agent-template) — deployment template for cloud setups.
- [portainer-stack-hermes](https://github.com/ellickjohnson/portainer-stack-hermes) — Portainer and Docker Compose style deployment.
- [hermes-autonomous-server](https://github.com/JackTheGit/hermes-autonomous-server) — unattended server-style deployment.
- [hermes-ha-addon](https://github.com/WolframRavenwolf/hermes-ha-addon) — packages Hermes as a Home Assistant add-on with persistent terminal and gateway access.
- [hermesclaw](https://github.com/TheAiSingularity/hermesclaw) — runs Hermes inside NVIDIA OpenShell-style sandbox boundaries for stronger containment.
- [openclaw-to-hermes](https://github.com/0xNyk/openclaw-to-hermes) — migration helper for older OpenClaw users.
- [Honcho Self-Hosted for Hermes](https://github.com/elkimek/honcho-self-hosted) — self-hosted memory backend setup.
- [Hindsight](https://github.com/vectorize-io/hindsight) — another long-term memory layer that can complement Hermes workflows.

## Integrations and Bridges

- [Integrations Overview](https://hermes-agent.nousresearch.com/docs/integrations)
- [Providers](https://hermes-agent.nousresearch.com/docs/integrations/providers)
- [Hermes Home Assistant Integration](https://github.com/WolframRavenwolf/hermes-ha-integration)
- [hermes-android](https://github.com/raulvidis/hermes-android) — Android bridge.
- [hermes-miniverse](https://github.com/teknium1/hermes-miniverse) — bridge into Miniverse environments.
- [hermes-agent-acp-skill](https://github.com/Rainhoole/hermes-agent-acp-skill) — bridge patterns for Hermes with other coding agents.
- [evey-bridge-plugin](https://github.com/42-evey/evey-bridge-plugin) — Hermes and Claude Code bridge idea.
- [reina](https://github.com/Crustocean/reina) — Hermes-oriented integration inside the Crustocean platform.
- [hermes-blockchain-oracle](https://github.com/gizdusum/hermes-blockchain-oracle) — blockchain analytics via MCP-style integration.
- [hermes-council](https://github.com/Ridwannurudeen/hermes-council) — adversarial multi-view decision support.
- [hermes-CCC](https://github.com/AlexAI-MCP/hermes-CCC) — ports core Hermes ideas and skill workflows into Claude Code Channel.

## Research, Multi-Agent, and Domain Projects

### Research and multi-agent work

- [Ankh.md](https://github.com/Abruptive/Ankh.md) — swarm-style multi-agent coordination.
- [bigiron](https://github.com/supermodeltools/bigiron) — AI-native software delivery with multiple agent roles.
- [gladiator](https://github.com/runtimenoteslabs/gladiator) — experiment in autonomous competitive agent companies.
- [opencode-hermes-multiagent](https://github.com/1ilkhamov/opencode-hermes-multiagent) — multi-agent orchestration around OpenCode and Hermes.
- [NemoHermes](https://github.com/Hmbown/NemoHermes) — GPU/capability routing layer idea.
- [hermes-nightshift-glm](https://github.com/Microck/hermes-nightshift-glm) — overnight code-quality bot that plans, implements, reviews, and opens PRs or issues.
- [Hermes-Agent-Online-RL](https://github.com/ar0cket1/Hermes-Agent-Online-RL) — online RL loop for adapting Hermes-backed local or hosted models from live feedback.

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

## Guides, Books, Videos, and Related Lists

### Community docs and guides

- [hermes-agent-docs](https://github.com/mudrii/hermes-agent-docs) — community docs supplement.
- [HermesWiki](https://github.com/martymcenroe/HermesWiki) — community-maintained wiki.
- [Hermes-Wiki](https://github.com/cclank/Hermes-Wiki) — source-verified architecture wiki with deep codebase pages.
- [hermes-agent-anatomy](https://github.com/anneheartrecord/hermes-agent-anatomy) — Chinese codebase anatomy series with diagrams and module-by-module analysis.
- [hermes-optimization-guide](https://github.com/OnlyTerp/hermes-optimization-guide) — practical setup, migration, LightRAG, Telegram, and skill-building guide.
- [Hermes-Agent-Action-Plan](https://github.com/vectrocomputers/Hermes-Agent-Action-Plan) — privacy-first operating philosophy and configuration playbook.
- [hermes-wsl-ubuntu](https://github.com/metantonio/hermes-wsl-ubuntu) — Windows WSL2 setup path.
- [Hermes Ecosystem](https://github.com/ksimback/hermes-ecosystem) — ecosystem map project.
- [Hermes Agent Ecosystem Map](https://hermes-ecosystem.vercel.app/) — web view of the broader ecosystem.

### Books and curated lists

- [Hermes Agent Orange Book](https://github.com/alchaincyf/hermes-agent-orange-book) — practical community guide/book.
- [awesome-hermes-agent](https://github.com/0xNyk/awesome-hermes-agent) — another curated resource list worth checking alongside this repo.

### Videos

- [Hermes Agent Setup: Install, Configure, and Run It 100% Free](https://www.youtube.com/watch?v=9v1DyzP7-58)
- [I am Switching to Hermes Agent](https://www.youtube.com/watch?v=J-kSdzHr9Ek)
- [Hermes AI Agent Explained: Persistent AI That Runs 24/7](https://www.youtube.com/watch?v=ZhCIZ-ZTcyE)

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
