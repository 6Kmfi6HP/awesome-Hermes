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
- [Open WebUI](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/open-webui/) —— 把 Hermes 作为 OpenAI 兼容后端接入 Open WebUI。
- [Open WebUI Hermes Agent Guide](https://docs.openwebui.com/getting-started/quick-start/connect-an-agent/hermes-agent/) —— Open WebUI 官方侧的接入说明，补充了 Docker 网络、`/v1` 路径与常见排错细节。
- [Team Telegram Assistant Guide](https://hermes-agent.nousresearch.com/docs/guides/team-telegram-assistant)
- [Daily Briefing Bot Guide](https://hermes-agent.nousresearch.com/docs/guides/daily-briefing-bot)
- [Automate with Cron](https://hermes-agent.nousresearch.com/docs/guides/automate-with-cron)
- [Use MCP with Hermes](https://hermes-agent.nousresearch.com/docs/guides/use-mcp-with-hermes)
- [Use SOUL.md with Hermes](https://hermes-agent.nousresearch.com/docs/guides/use-soul-with-hermes)
- [Use Voice Mode with Hermes](https://hermes-agent.nousresearch.com/docs/guides/use-voice-mode-with-hermes)

## 工作台与界面项目

- [Hermes Workspace](https://github.com/outsourc-e/hermes-workspace) —— 目前最知名的 Hermes 浏览器工作台，整合聊天、终端、记忆、技能与 inspector。
- [Pan UI](https://github.com/Euraika-Labs/pan-ui) —— 另一个偏控制台风格的自托管工作台。
- [Hermes Desktop（跨平台桌面伴侣）](https://github.com/fathah/hermes-desktop) —— 面向 macOS 和 Linux 的桌面包装层，负责安装、Provider 配置、聊天、会话、记忆、技能与设置入口。
- [Hermes Desktop（原生 macOS / SSH 工作台）](https://github.com/dodo-reach/hermes-desktop) —— 通过 SSH 直接连接 Hermes 主机的原生 Mac 工作台，把远端主机作为唯一真相源，提供会话、技能、Usage 视图和真正的终端，而不是浏览器壳。
- [Hermes WebUI](https://github.com/nesquena/hermes-webui) —— 更成熟的浏览器界面，目标是接近 CLI 等级的聊天、会话、文件浏览与远程访问体验。
- [Hermes WebUI（运维面板）](https://github.com/sanchomuzax/hermes-webui) —— 偏只读的监控与配置面板，可查看会话、定时任务、技能与配置数据。
- [Hermes Control Interface](https://github.com/xaspx/hermes-control-interface) —— 自托管控制台，整合浏览器终端、文件浏览器、Profile / Gateway 控制、Cron 与 Session 监控、Token 统计和系统指标，并用简单密码门禁保护。
- [Hermes for Web](https://github.com/reallygood83/hermes-for-web) —— 带有 setup packs、产物管理和记忆感知启动页的浏览器工作台。
- [Portable Hermes Agent](https://github.com/rookiemann/portable-hermes-agent) —— 偏向 Windows 友好的打包分发方案。
- [Hermes Dashboard](https://github.com/Bichev/hermes-dashboard) —— 会话、工具和 API 成本监控面板。
- [Hermes Dashboard（实时 Wiki）](https://github.com/Kori-x/hermes-dashboard) —— 实时可观测性面板，并可自动生成本地技能、插件、工具、记忆与 SOUL 文件的检索式 Wiki。
- [Hermes HUD UI](https://github.com/joeynyc/hermes-hudui) —— 面向 Hermes 的浏览器版“意识监控面板”，可直接从 ~/.hermes/ 读取并可视化记忆、Token 成本、技能、Cron 任务与成长快照。
- [Hermes HUD](https://github.com/joeynyc/hermes-hud) —— HUD UI 对应的终端版监控面板，适合在 TUI 中实时查看记忆、技能、纠错痕迹、工具使用与 agent 成长状态。

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
- [MemPalace](https://github.com/neilharding/hermes_memorypalace) —— 按 workspace 分层的记忆提供器，用本地 ChromaDB + SQLite 做显式/隐式记忆与语义召回。
- [hermes-plugins](https://github.com/42-evey/hermes-plugins) —— 一组社区插件合集。
- [hermes-web-search-plus](https://github.com/robbyczgw-cla/hermes-web-search-plus) —— 更强的 Web 搜索路由能力。
- [hermes-opencode-plugin](https://github.com/zaycruz/hermes-opencode-plugin) —— 让 Hermes 把软件工程任务分发给 OpenCode 的多代理编排层。
- [hermes-provider-switcher](https://github.com/tmdgusya/hermes-provider-switcher) —— 不用手动切 shell 环境变量，就能让 Hermes 通过 GLM、Kimi、MiniMax 等 provider 驱动 Claude Code。
- [hermes-lcm](https://github.com/stephenschoettler/hermes-lcm) —— 基于 DAG 摘要与回钻工具的无损上下文管理层。
- [hermes-mindgraph-plugin](https://github.com/shuruheel/hermes-mindgraph-plugin) —— 语义图记忆插件，把混合检索出的目标、决策与结构化知识自动注入 Hermes 会话。
- [Icarus Plugin](https://github.com/esaradev/icarus-plugin) —— 面向 Hermes 的共享记忆与自训练插件，包含训练数据导出、微调、评测、切换与回滚流程。
- [hermes-weather-plugin](https://github.com/FahrenheitResearch/hermes-weather-plugin) —— 天气方向插件。
- [hermes-wxtrain-plugin](https://github.com/FahrenheitResearch/hermes-wxtrain-plugin) —— 面向天气数据训练流程的扩展。
- [hermes-plugin-chrome-profiles](https://github.com/anpicasso/hermes-plugin-chrome-profiles) —— 浏览器 profile 切换。
- [hermes-cloudflare](https://github.com/raulvidis/hermes-cloudflare) —— 另一类浏览器渲染/访问路径。
- [hermes-payguard](https://github.com/nativ3ai/hermes-payguard) —— 支付控制相关插件。
- [Hermes Dojo](https://github.com/Yonkoo11/hermes-dojo) —— 针对 Hermes 的自我改进闭环，会从会话失败里挖掘薄弱技能、自动修补，并支持夜间 analyze→improve→report 流程。

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
- [hermes-ha-addon](https://github.com/WolframRavenwolf/hermes-ha-addon) —— 将 Hermes 打包成 Home Assistant Add-on，并带持久终端与网关接入。
- [hermesclaw](https://github.com/TheAiSingularity/hermesclaw) —— 将 Hermes 放进 NVIDIA OpenShell 风格沙箱边界内运行。
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
- [hermes-CCC](https://github.com/AlexAI-MCP/hermes-CCC) —— 将 Hermes 的核心思路与技能工作流迁移到 Claude Code Channel。

## 研究、多代理与垂直应用

### 研究与多代理方向

- [Ankh.md](https://github.com/Abruptive/Ankh.md) —— swarm 风格多代理协作。
- [bigiron](https://github.com/supermodeltools/bigiron) —— 面向软件交付流程的多代理系统。
- [gladiator](https://github.com/runtimenoteslabs/gladiator) —— 自主竞争型 Agent 公司实验。
- [opencode-hermes-multiagent](https://github.com/1ilkhamov/opencode-hermes-multiagent) —— OpenCode 与 Hermes 的多代理编排。
- [NemoHermes](https://github.com/Hmbown/NemoHermes) —— 偏 GPU / capability routing 的探索。
- [hermes-nightshift-glm](https://github.com/Microck/hermes-nightshift-glm) —— 夜间自动跑代码质量任务、提 PR 或开 issue 的 bot。
- [Hermes-Agent-Online-RL](https://github.com/ar0cket1/Hermes-Agent-Online-RL) —— 基于实时反馈持续适配 Hermes 所接本地或托管模型的在线 RL 项目。
- [Hermes Incident Commander](https://github.com/Lethe044/hermes-incident-commander) —— 面向生产事故的自治 SRE Agent，可用子代理并行诊断、自动修复，并把新事故沉淀为预防性技能。
- [Hermes Skill Forge](https://github.com/Lethe044/hermes-skill-marketplace) —— 实验性的自进化项目，重点不是只做完一次任务，而是把重复工作抽象成经过测试、可发布的技能。

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
- [Hermes-Wiki](https://github.com/cclank/Hermes-Wiki) —— 基于源码核对的架构 Wiki，拆解较深。
- [llm-wiki-compiler](https://github.com/atomicmemory/llm-wiki-compiler) —— 通用型 Wiki 编译工具，可把原始资料整理成可互链的 Markdown Wiki，方便 Hermes 用户持续查询与扩展外部知识。
- [hermes-agent-anatomy](https://github.com/anneheartrecord/hermes-agent-anatomy) —— 中文源码解剖系列，带图示和模块分析。
- [hermes-optimization-guide](https://github.com/OnlyTerp/hermes-optimization-guide) —— 包含安装、迁移、LightRAG、Telegram 与技能构建的实战指南。
- [Hermes-Agent-Action-Plan](https://github.com/vectrocomputers/Hermes-Agent-Action-Plan) —— 偏隐私优先的配置哲学与操作手册。
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
