# awesome-Hermes

> A curated list of awesome resources for Hermes Agent — the self-improving AI agent built by Nous Research.

Hermes Agent is an autonomous AI agent with a built-in learning loop: it creates skills from experience, improves them during use, remembers across sessions, searches its own conversation history, and runs across CLI, Telegram, Discord, Slack, WhatsApp, Signal, and more.

This repository collects the best official docs, guides, references, architecture notes, skills material, automation patterns, and ecosystem links for learning, using, extending, and deploying Hermes Agent.

If you're new to Hermes, start with the official repository and documentation. If you're already using it, this list is meant to be the fastest way to jump to the right guide or reference page.

Official repo: https://github.com/NousResearch/hermes-agent
Official docs: https://hermes-agent.nousresearch.com/docs/

## Why Hermes?

- Built-in learning loop with memory, session search, and self-improving skills
- Works across terminal and messaging surfaces, not just inside an IDE
- Strong automation story: cron jobs, delegation, MCP, browser control, code execution
- Useful for both end users and developers extending the system

## Contents

- [Official](#official)
- [Getting Started](#getting-started)
- [Core Concepts](#core-concepts)
- [Features](#features)
- [Messaging & Voice](#messaging--voice)
- [Automation & Orchestration](#automation--orchestration)
- [Skills & Extensions](#skills--extensions)
- [Developer Docs](#developer-docs)
- [Reference](#reference)
- [Community](#community)

## Official

- [Hermes Agent GitHub repository](https://github.com/NousResearch/hermes-agent) - Main source code.
- [Hermes Agent documentation](https://hermes-agent.nousresearch.com/docs/) - Full docs site.
- [Documentation index](https://hermes-agent.nousresearch.com/docs/) - Top-level map of the docs and key entry points.
- [Nous Research](https://nousresearch.com) - The lab behind Hermes Agent.

## Getting Started

- [Installation](https://hermes-agent.nousresearch.com/docs/getting-started/installation) - Install Hermes on Linux, macOS, or WSL2.
- [Quickstart](https://hermes-agent.nousresearch.com/docs/getting-started/quickstart) - First conversation, key commands, and first features to try.
- [Learning Path](https://hermes-agent.nousresearch.com/docs/getting-started/learning-path) - Best docs to read based on your experience level.
- [Configuration](https://hermes-agent.nousresearch.com/docs/user-guide/configuration) - Providers, config values, and runtime setup.
- [CLI Guide](https://hermes-agent.nousresearch.com/docs/user-guide/cli) - Terminal interface, slash commands, and daily usage.
- [Profiles](https://hermes-agent.nousresearch.com/docs/user-guide/profiles) - Profile-aware Hermes homes and separated environments.
- [Updating](https://hermes-agent.nousresearch.com/docs/getting-started/updating) - Upgrade Hermes safely.

## Core Concepts

- [Architecture](https://hermes-agent.nousresearch.com/docs/developer-guide/architecture) - High-level map of the system, major subsystems, and data flow.
- [Prompt Assembly](https://hermes-agent.nousresearch.com/docs/developer-guide/prompt-assembly) - How Hermes builds its system prompt from SOUL, memory, skills, and context files.
- [Context Compression & Prompt Caching](https://hermes-agent.nousresearch.com/docs/developer-guide/context-compression-and-caching) - How long sessions stay usable and efficient.
- [Persistent Memory](https://hermes-agent.nousresearch.com/docs/user-guide/features/memory) - MEMORY.md, USER.md, and what Hermes should remember.
- [Skills System](https://hermes-agent.nousresearch.com/docs/user-guide/features/skills) - Progressive-disclosure procedural memory and slash-command skills.
- [Context Files](https://hermes-agent.nousresearch.com/docs/user-guide/features/context-files) - Project-specific instructions via AGENTS.md and related files.
- [Use SOUL.md with Hermes](https://hermes-agent.nousresearch.com/docs/guides/use-soul-with-hermes) - Shape Hermes' default personality and communication style.
- [Session Storage](https://hermes-agent.nousresearch.com/docs/developer-guide/session-storage) - How conversations are persisted and searched.

## Features

- [Tools & Toolsets](https://hermes-agent.nousresearch.com/docs/user-guide/features/tools) - Built-in tools, toolsets, and terminal backends.
- [Built-in Tools Reference](https://hermes-agent.nousresearch.com/docs/reference/tools-reference) - Authoritative code-derived tool catalog.
- [Toolsets Reference](https://hermes-agent.nousresearch.com/docs/reference/toolsets-reference) - Tool grouping and platform presets.
- [Browser Automation](https://hermes-agent.nousresearch.com/docs/user-guide/features/browser) - Interactive browser workflows with text and vision.
- [Vision](https://hermes-agent.nousresearch.com/docs/user-guide/features/vision) - Image analysis and multimodal understanding.
- [Code Execution](https://hermes-agent.nousresearch.com/docs/user-guide/features/code-execution) - Sandboxed Python execution for multi-step logic.
- [Batch Processing](https://hermes-agent.nousresearch.com/docs/user-guide/features/batch-processing) - Trajectory generation and bulk processing.
- [RL Training](https://hermes-agent.nousresearch.com/docs/user-guide/features/rl-training) - Atropos environments and research workflows.
- [Fallback Providers](https://hermes-agent.nousresearch.com/docs/user-guide/features/fallback-providers) - Provider failover and routing resilience.
- [Provider Routing](https://hermes-agent.nousresearch.com/docs/user-guide/features/provider-routing) - Route requests across providers and models.
- [Credential Pools](https://hermes-agent.nousresearch.com/docs/user-guide/features/credential-pools) - Shared credential management for providers.
- [Checkpoints & Rollback](https://hermes-agent.nousresearch.com/docs/user-guide/checkpoints-and-rollback) - Restoreable agent state for risky work.
- [Docker Usage](https://hermes-agent.nousresearch.com/docs/user-guide/docker) - Safer containerized execution.
- [Security](https://hermes-agent.nousresearch.com/docs/user-guide/security) - Command approval, isolation, and messaging authorization.

## Messaging & Voice

- [Messaging Overview](https://hermes-agent.nousresearch.com/docs/user-guide/messaging) - Supported platforms and gateway model.
- [Telegram Guide](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/telegram) - Run Hermes through Telegram.
- [Discord Guide](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/discord) - Discord deployment and usage.
- [WhatsApp Guide](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/whatsapp) - WhatsApp integration.
- [Slack Guide](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/slack) - Slack integration.
- [Signal Guide](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/signal) - Signal integration.
- [Email Guide](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/email) - Email as a Hermes surface.
- [Home Assistant Guide](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/homeassistant) - Home automation integration.
- [Voice Mode](https://hermes-agent.nousresearch.com/docs/user-guide/features/voice-mode) - Speech input/output across CLI and messaging.
- [Use Voice Mode with Hermes](https://hermes-agent.nousresearch.com/docs/guides/use-voice-mode-with-hermes) - Practical voice setup and workflows.
- [Tutorial: Team Telegram Assistant](https://hermes-agent.nousresearch.com/docs/guides/team-telegram-assistant) - Shared team bot on Telegram.
- [Tutorial: Daily Briefing Bot](https://hermes-agent.nousresearch.com/docs/guides/daily-briefing-bot) - Scheduled summaries delivered through the gateway.

## Automation & Orchestration

- [Scheduled Tasks (Cron)](https://hermes-agent.nousresearch.com/docs/user-guide/features/cron) - Unified cronjob tool and lifecycle actions.
- [Automate Anything with Cron](https://hermes-agent.nousresearch.com/docs/guides/automate-with-cron) - Real-world automation patterns.
- [Subagent Delegation](https://hermes-agent.nousresearch.com/docs/user-guide/features/delegation) - Spawn isolated child agents for parallel work.
- [MCP (Model Context Protocol)](https://hermes-agent.nousresearch.com/docs/user-guide/features/mcp) - Connect Hermes to external tool servers.
- [Use MCP with Hermes](https://hermes-agent.nousresearch.com/docs/guides/use-mcp-with-hermes) - Practical MCP setup and usage patterns.
- [API Server](https://hermes-agent.nousresearch.com/docs/user-guide/features/api-server) - Use Hermes as a service.
- [Hooks](https://hermes-agent.nousresearch.com/docs/user-guide/features/hooks) - Event-driven extensions and automation.
- [Webhooks](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/webhooks) - Trigger Hermes from external systems.

## Skills & Extensions

- [Bundled Skills Catalog](https://hermes-agent.nousresearch.com/docs/reference/skills-catalog) - Skills that ship with Hermes.
- [Official Optional Skills Catalog](https://hermes-agent.nousresearch.com/docs/reference/optional-skills-catalog) - Extra official skills you can install explicitly.
- [Creating Skills](https://hermes-agent.nousresearch.com/docs/developer-guide/creating-skills) - How to author and publish skills.
- [Work with Skills](https://hermes-agent.nousresearch.com/docs/guides/work-with-skills) - Practical skill usage and installation patterns.
- [Plugins](https://hermes-agent.nousresearch.com/docs/user-guide/features/plugins) - Extend Hermes with plugin systems.
- [Memory Providers](https://hermes-agent.nousresearch.com/docs/user-guide/features/memory-providers) - Swap or extend memory backends.
- [Memory Provider Plugin Guide](https://hermes-agent.nousresearch.com/docs/developer-guide/memory-provider-plugin) - Build your own memory provider plugin.
- [Integrations Overview](https://hermes-agent.nousresearch.com/docs/integrations) - Supported providers and broader integrations.
- [Providers](https://hermes-agent.nousresearch.com/docs/integrations/providers) - Provider ecosystem and configuration details.

## Developer Docs

- [Contributing](https://hermes-agent.nousresearch.com/docs/developer-guide/contributing) - Dev setup, testing, and PR workflow.
- [Agent Loop](https://hermes-agent.nousresearch.com/docs/developer-guide/agent-loop) - Core synchronous conversation loop.
- [Tools Runtime](https://hermes-agent.nousresearch.com/docs/developer-guide/tools-runtime) - Tool registration, dispatch, and availability checking.
- [Adding Tools](https://hermes-agent.nousresearch.com/docs/developer-guide/adding-tools) - Extend Hermes with native tools.
- [Adding Providers](https://hermes-agent.nousresearch.com/docs/developer-guide/adding-providers) - Add model providers and runtime wiring.
- [Gateway Internals](https://hermes-agent.nousresearch.com/docs/developer-guide/gateway-internals) - Message flow, adapters, and delivery model.
- [Cron Internals](https://hermes-agent.nousresearch.com/docs/developer-guide/cron-internals) - Scheduler model and job execution.
- [Provider Runtime](https://hermes-agent.nousresearch.com/docs/developer-guide/provider-runtime) - Resolution precedence and API mode selection.
- [Environments](https://hermes-agent.nousresearch.com/docs/developer-guide/environments) - RL and execution environments.
- [ACP Internals](https://hermes-agent.nousresearch.com/docs/developer-guide/acp-internals) - IDE/editor integration details.
- [Extending the CLI](https://hermes-agent.nousresearch.com/docs/developer-guide/extending-the-cli) - Command registry and CLI architecture.
- [Trajectory Format](https://hermes-agent.nousresearch.com/docs/developer-guide/trajectory-format) - Training-data export format.

## Reference

- [CLI Commands Reference](https://hermes-agent.nousresearch.com/docs/reference/cli-commands) - Standalone CLI commands.
- [Slash Commands Reference](https://hermes-agent.nousresearch.com/docs/reference/slash-commands) - In-chat slash commands.
- [Environment Variables Reference](https://hermes-agent.nousresearch.com/docs/reference/environment-variables) - Configurable env vars.
- [MCP Config Reference](https://hermes-agent.nousresearch.com/docs/reference/mcp-config-reference) - MCP configuration keys.
- [Profile Commands Reference](https://hermes-agent.nousresearch.com/docs/reference/profile-commands) - Profile management commands.
- [FAQ](https://hermes-agent.nousresearch.com/docs/reference/faq) - Common questions and troubleshooting.

## Community

- [Discord](https://discord.gg/NousResearch) - Community chat.
- [GitHub Issues](https://github.com/NousResearch/hermes-agent/issues) - Bug reports and feature requests.
- [GitHub Discussions](https://github.com/NousResearch/hermes-agent/discussions) - Longer-form discussion.
- [agentskills.io](https://agentskills.io) - Open skill ecosystem referenced by Hermes.

## Contributing

Contributions are welcome. If you know a great Hermes resource, open a pull request or issue.

Suggested additions:

- tutorials
- blog posts
- videos and talks
- community examples
- notable skills and MCP servers
- deployment guides
- integrations built on top of Hermes

## License

MIT for this list unless noted otherwise by individual linked resources.
