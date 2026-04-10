# awesome-Hermes

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English](./README.md) | 中文

一个面向 Hermes Agent 的原创精选资源清单，覆盖学习、使用、扩展、部署与生态项目。

Hermes Agent 是 Nous Research 打造的自我改进型 AI Agent。它把持久记忆、会话检索、技能系统、工具调用、多平台消息网关、子代理委派、浏览器自动化、定时任务、MCP 和多种执行后端整合在同一个系统里。

官方仓库：https://github.com/NousResearch/hermes-agent
官方文档：https://hermes-agent.nousresearch.com/docs/

## 这份清单包含什么

- 官方文档与版本更新入口
- 上手与运维相关的高价值指南
- 社区工作台、插件、工具与部署项目
- skills / agentskills.io 生态资源
- 集成、桥接层与垂直领域应用
- 视频、书籍、社区文档与相关精选列表

## 建议阅读顺序

如果你刚接触 Hermes，推荐按下面顺序看：

1. 先看官方 Quickstart
2. 再理解核心概念：Memory、Skills、Tools、Profiles
3. 选一个主要使用入口：CLI、Telegram、Discord 或 API
4. 等基础稳定后，再去接工作台、插件和更复杂的集成

## 目录

- [官方基础资源](#官方基础资源)
- [快速开始](#快速开始)
- [核心概念与功能](#核心概念与功能)
- [消息、语音与自动化](#消息语音与自动化)
- [工作台与界面项目](#工作台与界面项目)
- [技能、插件与扩展](#技能插件与扩展)
- [部署与运维](#部署与运维)
- [集成与桥接](#集成与桥接)
- [研究、多代理与垂直应用](#研究多代理与垂直应用)
- [指南、书籍、视频与相关列表](#指南书籍视频与相关列表)
- [社区](#社区)
- [贡献](#贡献)

## 官方基础资源

- [Hermes Agent](https://github.com/NousResearch/hermes-agent) —— 主仓库。
- [官方文档](https://hermes-agent.nousresearch.com/docs/) —— 文档总入口。
- [Releases](https://github.com/NousResearch/hermes-agent/releases) —— 版本更新说明与功能变化。
- [Nous Research](https://nousresearch.com) —— Hermes 背后的团队。
- [Hermes Agent Self-Evolution](https://github.com/NousResearch/hermes-agent-self-evolution) —— 用进化式方法优化 Hermes 行为的研究项目。
- [Hermes Paperclip Adapter](https://github.com/NousResearch/hermes-paperclip-adapter) —— 把 Hermes 接入 Paperclip 这类公司工作流。
- [Autonovel](https://github.com/NousResearch/autonovel) —— 基于 Hermes 的长篇自动写作流程。

## 快速开始

- [Installation](https://hermes-agent.nousresearch.com/docs/getting-started/installation)
- [Quickstart](https://hermes-agent.nousresearch.com/docs/getting-started/quickstart)
- [Learning Path](https://hermes-agent.nousresearch.com/docs/getting-started/learning-path)
- [Updating](https://hermes-agent.nousresearch.com/docs/getting-started/updating)
- [Configuration](https://hermes-agent.nousresearch.com/docs/user-guide/configuration)
- [CLI Guide](https://hermes-agent.nousresearch.com/docs/user-guide/cli)
- [Profiles](https://hermes-agent.nousresearch.com/docs/user-guide/profiles)
- [FAQ](https://hermes-agent.nousresearch.com/docs/reference/faq)

## 核心概念与功能

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

## 消息、语音与自动化

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
- [Team Telegram Assistant Guide](https://hermes-agent.nousresearch.com/docs/guides/team-telegram-assistant)
- [Daily Briefing Bot Guide](https://hermes-agent.nousresearch.com/docs/guides/daily-briefing-bot)
- [Automate with Cron](https://hermes-agent.nousresearch.com/docs/guides/automate-with-cron)
- [Use MCP with Hermes](https://hermes-agent.nousresearch.com/docs/guides/use-mcp-with-hermes)
- [Use SOUL.md with Hermes](https://hermes-agent.nousresearch.com/docs/guides/use-soul-with-hermes)
- [Use Voice Mode with Hermes](https://hermes-agent.nousresearch.com/docs/guides/use-voice-mode-with-hermes)

## 工作台与界面项目

- [Hermes Workspace](https://github.com/outsourc-e/hermes-workspace) —— 目前最知名的 Hermes 浏览器工作台，整合聊天、终端、记忆、技能与 inspector。
- [Pan UI](https://github.com/Euraika-Labs/pan-ui) —— 另一个偏控制台风格的自托管工作台。
- [Hermes Desktop](https://github.com/dodo-reach/hermes-desktop) —— 面向 macOS 的原生桌面工作台方案。
- [Hermes WebUI](https://github.com/sanchomuzax/hermes-webui) —— 更轻量的 Web 控制面板。
- [Portable Hermes Agent](https://github.com/rookiemann/portable-hermes-agent) —— 偏向 Windows 友好的打包分发方案。

## 技能、插件与扩展

### 技能与技能生态

- [Bundled Skills Catalog](https://hermes-agent.nousresearch.com/docs/reference/skills-catalog)
- [Optional Skills Catalog](https://hermes-agent.nousresearch.com/docs/reference/optional-skills-catalog)
- [Creating Skills](https://hermes-agent.nousresearch.com/docs/developer-guide/creating-skills)
- [Work with Skills](https://hermes-agent.nousresearch.com/docs/guides/work-with-skills)
- [agentskills.io](https://agentskills.io) —— 多种 Agent 生态共用的开放技能标准。
- [wondelai/skills](https://github.com/wondelai/skills) —— 较完整的社区技能集合。
- [Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) —— 安全方向的大型技能库。
- [chainlink-agent-skills](https://github.com/smartcontractkit/chainlink-agent-skills) —— Chainlink 相关工作流技能。
- [black-forest-labs/skills](https://github.com/black-forest-labs/skills) —— 图像与 FLUX 生态相关技能。
- [pydantic-ai-skills](https://github.com/DougTrajano/pydantic-ai-skills) —— 强类型结构化技能工作流。
- [litprog-skill](https://github.com/tlehman/litprog-skill) —— 偏 literate programming 的技能项目。
- [hermes-skill-factory](https://github.com/Romanescu11/hermes-skill-factory) —— 将重复工作提炼成技能。
- [hermeshub](https://github.com/amanning3390/hermeshub) —— 社区技能发现入口。
- [skilldock.io](https://github.com/chigwell/skilldock.io) —— 跨 Agent 的技能注册表。

### 插件与附加扩展

- [Plugins](https://hermes-agent.nousresearch.com/docs/user-guide/features/plugins)
- [Memory Provider Plugin Guide](https://hermes-agent.nousresearch.com/docs/developer-guide/memory-provider-plugin)
- [hermes-plugins](https://github.com/42-evey/hermes-plugins) —— 一组社区插件合集。
- [hermes-web-search-plus](https://github.com/robbyczgw-cla/hermes-web-search-plus) —— 更强的 Web 搜索路由能力。
- [hermes-weather-plugin](https://github.com/FahrenheitResearch/hermes-weather-plugin) —— 天气方向插件。
- [hermes-wxtrain-plugin](https://github.com/FahrenheitResearch/hermes-wxtrain-plugin) —— 面向天气数据训练流程的扩展。
- [hermes-plugin-chrome-profiles](https://github.com/anpicasso/hermes-plugin-chrome-profiles) —— 浏览器 profile 切换。
- [hermes-cloudflare](https://github.com/raulvidis/hermes-cloudflare) —— 另一类浏览器渲染/访问路径。
- [hermes-payguard](https://github.com/nativ3ai/hermes-payguard) —— 支付控制相关插件。

## 部署与运维

- [Contributing Guide](https://hermes-agent.nousresearch.com/docs/developer-guide/contributing)
- [Gateway Internals](https://hermes-agent.nousresearch.com/docs/developer-guide/gateway-internals)
- [Cron Internals](https://hermes-agent.nousresearch.com/docs/developer-guide/cron-internals)
- [Tools Runtime](https://hermes-agent.nousresearch.com/docs/developer-guide/tools-runtime)
- [Provider Runtime](https://hermes-agent.nousresearch.com/docs/developer-guide/provider-runtime)
- [Trajectory Format](https://hermes-agent.nousresearch.com/docs/developer-guide/trajectory-format)
- [nix-hermes-agent](https://github.com/0xrsydn/nix-hermes-agent) —— Nix / NixOS 打包方案。
- [hermes-agent-docker](https://github.com/xmbshwll/hermes-agent-docker) —— 简单 Docker 镜像方案。
- [hermes-agent-template](https://github.com/Crustocean/hermes-agent-template) —— 云端部署模板。
- [portainer-stack-hermes](https://github.com/ellickjohnson/portainer-stack-hermes) —— Portainer + Docker Compose 风格部署。
- [hermes-autonomous-server](https://github.com/JackTheGit/hermes-autonomous-server) —— 无人值守服务器部署。
- [openclaw-to-hermes](https://github.com/0xNyk/openclaw-to-hermes) —— OpenClaw 迁移辅助工具。
- [Honcho Self-Hosted for Hermes](https://github.com/elkimek/honcho-self-hosted) —— 自托管记忆后端方案。
- [Hindsight](https://github.com/vectorize-io/hindsight) —— 可与 Hermes 工作流结合的长期记忆层。

## 集成与桥接

- [Integrations Overview](https://hermes-agent.nousresearch.com/docs/integrations)
- [Providers](https://hermes-agent.nousresearch.com/docs/integrations/providers)
- [Hermes Home Assistant Integration](https://github.com/WolframRavenwolf/hermes-ha-integration)
- [hermes-android](https://github.com/raulvidis/hermes-android) —— Android 桥接。
- [hermes-miniverse](https://github.com/teknium1/hermes-miniverse) —— Miniverse 场景集成。
- [hermes-agent-acp-skill](https://github.com/Rainhoole/hermes-agent-acp-skill) —— Hermes 与其他代码 Agent 的桥接思路。
- [evey-bridge-plugin](https://github.com/42-evey/evey-bridge-plugin) —— Hermes 与 Claude Code 的桥。
- [reina](https://github.com/Crustocean/reina) —— Crustocean 平台内的 Hermes 集成案例。
- [hermes-blockchain-oracle](https://github.com/gizdusum/hermes-blockchain-oracle) —— 区块链分析型 MCP/桥接项目。
- [hermes-council](https://github.com/Ridwannurudeen/hermes-council) —— 多视角对抗式决策支持。

## 研究、多代理与垂直应用

### 研究与多代理方向

- [Ankh.md](https://github.com/Abruptive/Ankh.md) —— swarm 风格多代理协作。
- [bigiron](https://github.com/supermodeltools/bigiron) —— 面向软件交付流程的多代理系统。
- [gladiator](https://github.com/runtimenoteslabs/gladiator) —— 自主竞争型 Agent 公司实验。
- [opencode-hermes-multiagent](https://github.com/1ilkhamov/opencode-hermes-multiagent) —— OpenCode 与 Hermes 的多代理编排。
- [NemoHermes](https://github.com/Hmbown/NemoHermes) —— 偏 GPU / capability routing 的探索。

### 垂直应用项目

- [hermescraft](https://github.com/bigph00t/hermescraft) —— Minecraft 持久陪伴 Agent。
- [hermes-embodied](https://github.com/bryercowan/hermes-embodied) —— 机器人/具身智能方向。
- [Hermes-mars-rover](https://github.com/Snehal707/Hermes-mars-rover) —— 火星车模拟场景。
- [anihermes](https://github.com/rodmarkun/anihermes) —— 动漫/媒体服务器交互项目。
- [job-scout-agent](https://github.com/Christabel337/job-scout-agent) —— 求职自动化。
- [hermes-ai-infrastructure-monitoring-toolkit](https://github.com/JackTheGit/hermes-ai-infrastructure-monitoring-toolkit) —— 基础设施监控与告警。
- [hermes-legal](https://github.com/Lethe044/hermes-legal) —— 法律审阅场景。
- [hermes-startup-architect](https://github.com/dlkakbs/hermes-startup-architect) —— 创业规划与材料生成。
- [mercury](https://github.com/hxsteric/mercury) —— 区块链现金流与分析。
- [hermes-research-agent](https://github.com/Aum08Desai/hermes-research-agent) —— 自动化研究工作流。

## 指南、书籍、视频与相关列表

### 社区文档与指南

- [hermes-agent-docs](https://github.com/mudrii/hermes-agent-docs) —— 社区补充文档。
- [HermesWiki](https://github.com/martymcenroe/HermesWiki) —— 社区 Wiki。
- [hermes-wsl-ubuntu](https://github.com/metantonio/hermes-wsl-ubuntu) —— Windows WSL2 安装路径。
- [Hermes Ecosystem](https://github.com/ksimback/hermes-ecosystem) —— 生态地图项目。
- [Hermes Agent Ecosystem Map](https://hermes-ecosystem.vercel.app/) —— 生态地图网页版本。

### 书籍与相关精选

- [Hermes Agent Orange Book](https://github.com/alchaincyf/hermes-agent-orange-book) —— 实用型社区书籍/指南。
- [awesome-hermes-agent](https://github.com/0xNyk/awesome-hermes-agent) —— 另一份可交叉参考的 Hermes 精选列表。

### 视频

- [Hermes Agent Setup: Install, Configure, and Run It 100% Free](https://www.youtube.com/watch?v=9v1DyzP7-58)
- [I am Switching to Hermes Agent](https://www.youtube.com/watch?v=J-kSdzHr9Ek)
- [Hermes AI Agent Explained: Persistent AI That Runs 24/7](https://www.youtube.com/watch?v=ZhCIZ-ZTcyE)

## 社区

- [Discord](https://discord.gg/NousResearch)
- [GitHub Issues](https://github.com/NousResearch/hermes-agent/issues)
- [GitHub Discussions](https://github.com/NousResearch/hermes-agent/discussions)

## 贡献

欢迎补充资源。

更适合加入这份列表的内容包括：

- 真正在生产或稳定环境中可用的部署方案
- 高质量插件与技能项目
- 信息密度高的教程与案例复盘
- 有维护痕迹的垂直应用
- 生态地图、控制台、运维与观察性工具

不建议加入：

- 低质量重复 fork
- 没有 README 的半成品仓库
- 对生态没有新增价值的重复链接

## License

本仓库采用 MIT，外部链接资源以其各自许可证为准。
