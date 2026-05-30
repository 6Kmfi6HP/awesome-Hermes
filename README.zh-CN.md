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
- [Web Dashboard](https://hermes-agent.nousresearch.com/docs/user-guide/features/web-dashboard) —— 官方浏览器仪表盘，可直接管理配置、密钥、会话、日志、分析、技能与定时任务。
- [Dashboard Plugins](https://hermes-agent.nousresearch.com/docs/user-guide/features/dashboard-plugins) —— 官方扩展说明，教你给内置 Hermes 仪表盘增加自定义标签页和后端接口。
- [Extending the Dashboard](https://hermes-agent.nousresearch.com/docs/user-guide/features/extending-the-dashboard) —— 官方运行时扩展指南，讲清如何不用 fork Hermes、也不用重建前端，就能通过主题、插件标签页、shell slot 和插件后端 API 重塑内置 Dashboard。
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
- [Hermes Desktop（Windows 版）](https://github.com/acegraphx/hermes-desktop-win) —— 面向 Windows 的原生 WPF 工作台，通过 SSH 连接 Hermes 主机，可管理会话、文件、Wiki、技能、Cron 和终端。
- [Scarf](https://github.com/awizemann/scarf) —— 原生 macOS 图形客户端，支持多窗口管理本地或远端 Hermes 服务器，走 SSH 打通聊天、仪表盘、会话、记忆、Cron、MCP 与配置操作。
- [Hermes Desktop（原生 macOS / SSH 工作台）](https://github.com/dodo-reach/hermes-desktop) —— 通过 SSH 直接连接 Hermes 主机的原生 Mac 工作台，把远端主机作为唯一真相源，提供会话、技能、Usage 视图和真正的终端，而不是浏览器壳。
- [Hermes Desktop（OS1 版）](https://github.com/nickvasilescu/hermes-desktop-os1) —— 面向 Orgo 云计算机与 SSH 主机的原生 macOS 工作台，集成 VM 自动开通、会话、看板、文件、技能、Cron、终端与 WebRTC 语音。
- [Hermes WebUI](https://github.com/nesquena/hermes-webui) —— 更成熟的浏览器界面，目标是接近 CLI 等级的聊天、会话、文件浏览与远程访问体验。
- [Hermes AI Agent — VS Code Extension](https://github.com/joaompfp/hermes-vscode) —— Hermes CLI 的 VS Code 侧边栏，通过 ACP 提供流式聊天、工具轨迹、会话持久化和技能选择器。
- [Hermes WebUI（运维面板）](https://github.com/sanchomuzax/hermes-webui) —— 偏只读的监控与配置面板，可查看会话、定时任务、技能与配置数据。
- [Hermes Agent WebUI](https://github.com/laolaoshiren/hermes-agent-webui) —— 聊天优先的自托管前端，重点是多会话对话流和更安全的公网部署默认值，而不是做成偏后台控制台的重面板界面。
- [Hermes Control Interface](https://github.com/xaspx/hermes-control-interface) —— 自托管控制台，整合浏览器终端、文件浏览器、Profile / Gateway 控制、Cron 与 Session 监控、Token 统计和系统指标，并用简单密码门禁保护。
- [Hermes UI](https://github.com/pyrate-llama/hermes-ui) —— 带有玻璃拟态风格的单文件命令中心，集成聊天、文件浏览、记忆、技能、Kanban 和实时运维监控。
- [Hermes for Web](https://github.com/reallygood83/hermes-for-web) —— 带有 setup packs、产物管理和记忆感知启动页的浏览器工作台。
- [Portable Hermes Agent](https://github.com/rookiemann/portable-hermes-agent) —— 偏向 Windows 友好的打包分发方案。
- [hermes-agent-desktop](https://github.com/comedy1024/hermes-agent-desktop) —— 一体化 Docker 桌面环境，把 Hermes Agent、Hermes WebUI 和浏览器可访问的 Debian KDE 打包在一起，适合想要 GUI 入口和现成自托管运行时的用户。
- [Hermes Dashboard](https://github.com/Bichev/hermes-dashboard) —— 会话、工具和 API 成本监控面板。
- [Hermes Dashboard（网关控制台）](https://github.com/chrisryugj/hermes-dashboard) —— 面向 Hermes gateway 的完整 Web 控制面，覆盖配置编辑、MCP 管理、Cron 控制、技能浏览、日志查看和模型切换，尽量不必回到 CLI。
- [Hermes Dashboard（实时 Wiki）](https://github.com/Kori-x/hermes-dashboard) —— 实时可观测性面板，并可自动生成本地技能、插件、工具、记忆与 SOUL 文件的检索式 Wiki。
- [Hermes Web UI](https://github.com/EKKOLearnAI/hermes-web-ui) —— 可通过 npm 安装的 Vue 运维面板，把多平台聊天、Profile 切换、模型管理、分析、日志、Web 终端和渠道配置整合到一个控制台里。
- [Hermes Studio](https://github.com/JPeetz/Hermes-Studio) —— 面向重度用户的浏览器工作室，主打 crews、多级执行审批、可视化记忆图谱、工作流 DAG，以及生态里最完整的一批 Cron / Job 管理能力。
- [Hermes War Room](https://github.com/Naroh091/hermes-war-room) —— 浏览器版运维控制面，把 Hermes 的原生编排能力可视化成 mission control、团队名册、实时 agent 状态和按 agent 划分的任务队列。
- [Minions](https://github.com/Agent-3-7/minions) —— 面向 Hermes 自主任务的 mission control 面板，使用持久化 root 会话做任务监督、回顾与状态跟踪。
- [Hermes Telegram Mini App](https://github.com/clawvader-tech/hermes-telegram-miniapp) —— Telegram 内嵌的移动优先 Mini App，把聊天、Cron 控制、系统健康和后台 agent spawning 直接带进 Telegram，并附带更硬化的认证与隧道部署说明。
- [Hermes Voice Agent](https://github.com/onlockj/hermes-voice-agent) —— 低延迟的 Telegram 语音通道，带 PWA 前端、OpenAI Realtime 流水线、barge-in 支持和一键部署说明。
- [Atomic Bot](https://github.com/AtomicBot-ai/atomicbot) —— 原生桌面启动器，近期新增了 macOS / Windows 上的一键 Hermes 安装路径，适合想跳过终端、直接获得仪表盘、终端、日志和文件浏览能力的用户。
- [Web3Hermes](https://github.com/Web3CZ/Web3Hermes) —— 面向中国大陆用户的轻量中文 WebUI，主打桌面浏览器里的聊天、会话、工作区与任务视图。
- [Hermes HUD UI](https://github.com/joeynyc/hermes-hudui) —— 面向 Hermes 的浏览器版“意识监控面板”，可直接从 ~/.hermes/ 读取并可视化记忆、Token 成本、技能、Cron 任务与成长快照。
- [Hermes HUD](https://github.com/joeynyc/hermes-hud) —— HUD UI 对应的终端版监控面板，适合在 TUI 中实时查看记忆、技能、纠错痕迹、工具使用与 agent 成长状态。

## 技能、插件与扩展

### 技能与技能生态

- [Bundled Skills Catalog](https://hermes-agent.nousresearch.com/docs/reference/skills-catalog)
- [Optional Skills Catalog](https://hermes-agent.nousresearch.com/docs/reference/optional-skills-catalog)
- [Creating Skills](https://hermes-agent.nousresearch.com/docs/developer-guide/creating-skills)
- [Work with Skills](https://hermes-agent.nousresearch.com/docs/guides/work-with-skills)
- [Shopify Skill](https://hermes-agent.nousresearch.com/docs/user-guide/skills/optional/productivity/productivity-shopify) —— 官方可选电商技能，让 Hermes 直接通过 GraphQL 管理 Shopify 商品、订单、库存、客户与履约流程。
- [OpenHands](https://hermes-agent.nousresearch.com/docs/user-guide/skills/optional/autonomous-ai-agents/autonomous-ai-agents-openhands) —— 官方可选技能，可把代码任务委派给 OpenHands CLI，并以 headless、模型无关的方式运行。
- [agentskills.io](https://agentskills.io) —— 多种 Agent 生态共用的开放技能标准。
- [wondelai/skills](https://github.com/wondelai/skills) —— 较完整的社区技能集合。
- [Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) —— 安全方向的大型技能库。
- [chainlink-agent-skills](https://github.com/smartcontractkit/chainlink-agent-skills) —— Chainlink 相关工作流技能。
- [black-forest-labs/skills](https://github.com/black-forest-labs/skills) —— 图像与 FLUX 生态相关技能。
- [pydantic-ai-skills](https://github.com/DougTrajano/pydantic-ai-skills) —— 强类型结构化技能工作流。
- [litprog-skill](https://github.com/tlehman/litprog-skill) —— 偏 literate programming 的技能项目。
- [awesome-hermes-skills](https://github.com/ChuckSRQ/awesome-hermes-skills) —— 可直接安装的 Hermes 技能合集，覆盖研究、产物预览、自我改进基准和 GitHub 工作流。
- [hermes-merchant](https://github.com/arimanyus/hermes-merchant) —— 面向 ML/AI 求职自动化的 Hermes 技能包，可抓取职位、按画像打分，并自动填写 Greenhouse 申请。
- [hermes-skill-factory](https://github.com/Romanescu11/hermes-skill-factory) —— 将重复工作提炼成技能。
- [Hermes Memory Skills](https://github.com/nexus9888/hermes-memory-skills) —— 面向记忆维护的技能包，可在不同后端上执行 dreaming 与 surgical trimming。
- [Super Hermes](https://github.com/Cranot/super-hermes) —— 一组分析型技能，教 Hermes 写出更锋利的推理 lens、暴露盲点，并在深度分析中汇报结构性约束。
- [hermeshub](https://github.com/amanning3390/hermeshub) —— 社区技能发现入口。
- [skilldock.io](https://github.com/chigwell/skilldock.io) —— 跨 Agent 的技能注册表。
- [HyperDirector](https://github.com/gloweaseco-leo/hyperdirector) —— 面向 Hermes 的结构化 HyperFrames 视频生产技能包，串起 brief → storyboard → HTML → render 的完整工作流，并提供一键安装脚本。
- [agency-agents-zh](https://github.com/jnMetaCode/agency-agents-zh) —— 215 个即插即用的中文 AI 专家角色，覆盖工程、设计、营销、金融等 18 个部门，支持通过 `--category` 参数分批安装到 Hermes Agent。

### 插件与附加扩展

- [Plugins](https://hermes-agent.nousresearch.com/docs/user-guide/features/plugins)
- [Built-in Plugins](https://hermes-agent.nousresearch.com/docs/user-guide/features/built-in-plugins) —— 官方内置插件目录，整理了 Hermes 仓库自带但默认需手动启用的插件，例如磁盘清理、Langfuse 追踪、Spotify 控制、Google Meet 入会、图像后端和 dashboard 示例插件。
- [Memory Provider Plugin Guide](https://hermes-agent.nousresearch.com/docs/developer-guide/memory-provider-plugin)
- [Model Provider Plugins](https://hermes-agent.nousresearch.com/docs/developer-guide/model-provider-plugin) —— 官方文档，说明如何把推理后端做成可插拔的 provider 插件，覆盖 provider profile、自动发现、CLI 接线，以及自定义 / 覆盖现有模型路由的方式。
- [Context Engine Plugins](https://hermes-agent.nousresearch.com/docs/developer-guide/context-engine-plugin) —— 官方参考文档，解释如何用自定义上下文引擎替换 Hermes 内置压缩器，比如做 DAG 式或尽量无损的上下文管理策略。
- [Build a Hermes Plugin](https://hermes-agent.nousresearch.com/docs/guides/build-a-hermes-plugin) —— 官方端到端插件开发指南，覆盖工具、hooks、skills、slash commands 与打包资源。
- [Hermes Example Plugins](https://github.com/NousResearch/hermes-example-plugins) —— 官方参考实现，用最小化、易读的代码演示核心插件表面。
- [Hermes Memory UI](https://github.com/xraysight/hermes-memory-ui) —— 只读型 dashboard 插件，用来查看 `MEMORY.md`、`USER.md` 和可选的 holographic SQLite 记忆内容，同时避免绕过 Hermes 正常的记忆写入保护机制。
- [memory-files-dashboard-plugin](https://github.com/wobbywells/memory-files-dashboard-plugin) —— dashboard 插件，可通过专用文件 API 安全编辑 `USER.md` 和 `MEMORY.md`，而不是手工直接改文件。
- [MemPalace](https://github.com/neilharding/hermes_memorypalace) —— 按 workspace 分层的记忆提供器，用本地 ChromaDB + SQLite 做显式/隐式记忆与语义召回。
- [Mnemosyne](https://github.com/AxDSan/mnemosyne) —— 面向 Hermes 的本地优先 SQLite 记忆提供器，主打亚毫秒级检索、可选向量 / FTS 召回、配套 MCP 工具，以及从云记忆后端迁回本地的导入路径。
- [Hermes Memory Provider（Basic Memory）](https://github.com/basicmachines-co/hermes-basic-memory) —— 基于 Basic Memory 知识图谱的记忆插件，提供 search-before-answer 回忆、逐轮捕获、会话摘要和 `/bm-*` 直接控制命令。
- [MemOS](https://github.com/MemTensor/MemOS) —— 更通用的 AI Memory OS，但已提供 Hermes 本地插件，带混合检索、智能去重、可视化记忆管理，以及适合多 Agent 共享的知识层。
- [agentmemory](https://github.com/rohitg00/agentmemory) —— 外部长时记忆引擎，已提供专门的 Hermes memory-provider 插件，同时带 REST / MCP 接口、会话回放和实时可视化界面，适合跨会话持续召回。
- [Supermemory](https://github.com/supermemoryai/supermemory) —— 官方记忆引擎与应用，支持 Hermes 接入，提供混合检索、连接器和长期上下文层。
- [mem9 Hermes Plugin](https://github.com/mem9-ai/mem9-hermes-plugin) —— 托管式持久记忆插件，提供语义召回、逐轮信息抽取与简洁的 CLI 接入流程。
- [yantrikdb-hermes-plugin](https://github.com/yantrikos/yantrikdb-hermes-plugin) —— 自维护记忆提供器，支持去重归一、矛盾追踪与可解释召回。
- [hermes-observational-memory](https://github.com/intertwine/hermes-observational-memory) —— 独立 memory-provider 插件，让 Hermes 与 Claude Code、Codex 共用本地 Markdown 记忆库，并支持可搜索观察记录与可选写回。
- [hermes-plugins](https://github.com/42-evey/hermes-plugins) —— 一组社区插件合集。
- [hermes-tools](https://github.com/axisdynamics/hermes-tools) —— 面向实战的原生插件包，包含 agent 间 pub/sub、provider 失败切换和持久化记忆等能力。
- [Hermes Plugin: Carabiner](https://github.com/donovan-yohan/hermes-plugin-carabiner) —— 依托 Honcho 的关系记忆插件，专门记录 specialist agent 之间的交接、反馈循环和协作上下文。
- [hermes-notification](https://github.com/itgoyo/hermes-notification) —— 很轻量的跨平台插件，在 Hermes 完成回复后触发原生桌面通知和提示音。
- [hermes-web-search-plus](https://github.com/robbyczgw-cla/hermes-web-search-plus) —— 更强的 Web 搜索路由能力。
- [hermes-opencode-plugin](https://github.com/zaycruz/hermes-opencode-plugin) —— 让 Hermes 把软件工程任务分发给 OpenCode 的多代理编排层。
- [hermes-provider-switcher](https://github.com/tmdgusya/hermes-provider-switcher) —— 不用手动切 shell 环境变量，就能让 Hermes 通过 GLM、Kimi、MiniMax 等 provider 驱动 Claude Code。
- [hermes-lcm](https://github.com/stephenschoettler/hermes-lcm) —— 基于 DAG 摘要与回钻工具的无损上下文管理层。
- [hermes-mindgraph-plugin](https://github.com/shuruheel/hermes-mindgraph-plugin) —— 语义图记忆插件，把混合检索出的目标、决策与结构化知识自动注入 Hermes 会话。
- [Icarus Plugin](https://github.com/esaradev/icarus-plugin) —— 面向 Hermes 的共享记忆与自训练插件，包含训练数据导出、微调、评测、切换与回滚流程。
- [hermes-weather-plugin](https://github.com/FahrenheitResearch/hermes-weather-plugin) —— 天气方向插件。
- [hermes-wxtrain-plugin](https://github.com/FahrenheitResearch/hermes-wxtrain-plugin) —— 面向天气数据训练流程的扩展。
- [hermes-plugin-chrome-profiles](https://github.com/anpicasso/hermes-plugin-chrome-profiles) —— 浏览器 profile 切换。
- [hermes-claude-code-rc](https://github.com/kevinmarmstrong/hermes-claude-code-rc) —— 通过 Hermes 暴露 `/cc` 指令，让你能从 Telegram 启动或管理 Claude Code 远程控制会话、无头执行和 shell 命令，同时把实际执行环境留在你自己的机器上。
- [hermes-a2a](https://github.com/iamagenius00/hermes-a2a) —— 零补丁 A2A 插件，可把消息注入 Hermes 当前运行中的会话，单独持久化 A2A 对话记录，并通过 HMAC 签名 webhook 立即唤醒 Agent，而不是依赖轮询。
- [hermes-local-rig-accounting](https://github.com/GumbyEnder/hermes-local-rig-accounting) —— 面向本地 LLM 推理设备成本核算的插件，可基准测试吞吐，并把电费与硬件折旧换算成透明的每 token 成本，供 Hermes 中查看与比较。
- [hermes-cloudflare](https://github.com/raulvidis/hermes-cloudflare) —— 另一类浏览器渲染/访问路径。
- [hermes-payguard](https://github.com/nativ3ai/hermes-payguard) —— 支付控制相关插件。
- [Hermes Dojo](https://github.com/Yonkoo11/hermes-dojo) —— 针对 Hermes 的自我改进闭环，会从会话失败里挖掘薄弱技能、自动修补，并支持夜间 analyze→improve→report 流程。
- [Ladybug Memory Plugin](https://github.com/Ladybug-Memory/hermes-memory-plugin) —— 本地优先的记忆提供器，把 Hermes 的长期记忆保存在单个 `.lbdb` 图数据库文件里，支持类型化记忆、权重召回与可选实体抽取。
- [Membase for Hermes](https://github.com/aristoapp/hermes-membase) —— 持久记忆插件，把混合向量检索与知识图谱召回、Wiki 检索以及 Hermes 内置 `MEMORY.md` 镜像结合起来，适合想把长期记忆从本地文件扩展到共享记忆层的用户。
- [Hermes Dashboard Plugin](https://github.com/tmdgusya/hermes-dashboard-plugin) —— 基于官方 dashboard plugin SDK 的轻量扩展，用一个带 neubrutalism 风格的新标签页整合会话、技能、Profile、Token 使用和可编辑的记忆文件视图。
- [Hermes Theme Editor](https://github.com/sanchomuzax/hermes-theme-editor) —— 可视化 dashboard 主题编辑插件，可直接创建、预览并启用自定义 YAML 主题，无需手工改文件。
- [Hermes Prompt Vault](https://github.com/LeventeNagy/hermes-prompt-vault) —— 提示词库插件，支持 `/vault` 命令和 Dashboard 界面，可保存、检索并复用来自各个平台的提示词。
- [Hermes Workspace Dashboard Plugin](https://github.com/outsourc-e/hermes-workspace-plugin) —— 将 Hermes Workspace 聊天界面嵌入 Hermes Dashboard 的标签页，支持本地端口自动发现与一键安装。
- [Hermes Canvas](https://github.com/tonbistudio/hermes-canvas) —— 把 Hermes Dashboard 变成实时前端创作工作室的插件，带项目脚手架、开发服务器控制和 Agent 驱动编辑。
- [Hermes Achievements](https://github.com/PCinkusz/hermes-achievements) —— 把真实的 Hermes 会话历史转成可收集的 Dashboard 成就与徽章系统。
- [Agent Analytics Hermes Plugin](https://github.com/Agent-Analytics/agent-analytics-hermes-plugin) —— 面向 Hermes 仪表盘的只读分析插件，可把账号连接、项目选择和 Web 分析视图直接嵌进 Hermes 控制台，方便把业务信号和 Agent 活动放在一起看。
- [Hermes Labyrinth](https://github.com/stainlu/hermes-labyrinth) —— 只读型 dashboard 插件，把 Hermes 当成“飞行记录仪”来观测：可把提示词、工具调用、失败、审批、记忆命中、Cron 运行和子代理轨迹整理成可导出的观测路径，而不是再做一个聊天界面。
- [Honcho Memory Plugin](https://github.com/GumbyEnder/hermes-plugins) —— 以 Honcho 记忆面板为核心的 dashboard 插件集合，提供实时统计、队列健康度、语义搜索，以及文档 / 消息历史的下钻视图。

## 部署与运维

- [Contributing Guide](https://hermes-agent.nousresearch.com/docs/developer-guide/contributing)
- [Gateway Internals](https://hermes-agent.nousresearch.com/docs/developer-guide/gateway-internals)
- [Cron Internals](https://hermes-agent.nousresearch.com/docs/developer-guide/cron-internals)
- [Tools Runtime](https://hermes-agent.nousresearch.com/docs/developer-guide/tools-runtime)
- [Provider Runtime](https://hermes-agent.nousresearch.com/docs/developer-guide/provider-runtime)
- [Adding Providers](https://hermes-agent.nousresearch.com/docs/developer-guide/adding-providers) —— 官方贡献指南，讲如何添加或覆盖一等公民级推理 Provider；既覆盖 OpenAI 兼容后端的插件化快路径，也覆盖原生适配器的深度接入路径。
- [Trajectory Format](https://hermes-agent.nousresearch.com/docs/developer-guide/trajectory-format)
- [nix-hermes-agent](https://github.com/0xrsydn/nix-hermes-agent) —— Nix / NixOS 打包方案。
- [hermes-agent-docker](https://github.com/xmbshwll/hermes-agent-docker) —— 简单 Docker 镜像方案。
- [hermes-agent-template](https://github.com/Crustocean/hermes-agent-template) —— 云端部署模板。
- [hermes-suite](https://github.com/sunnysktsang/hermes-suite) —— 将 hermes-agent、hermes-webui 和 hermes-dashboard 打包到同一个 Docker/Podman 容器里的单容器方案。
- [HermesHQ](https://github.com/jpalmae/hermeshq) —— 面向多实例 Hermes Agent 的 Docker 优先控制平面，可从一个 Web 应用统一管理多个实例。
- [portainer-stack-hermes](https://github.com/ellickjohnson/portainer-stack-hermes) —— Portainer + Docker Compose 风格部署。
- [hermes-autonomous-server](https://github.com/JackTheGit/hermes-autonomous-server) —— 无人值守服务器部署。
- [hermes-ha-addon](https://github.com/WolframRavenwolf/hermes-ha-addon) —— 将 Hermes 打包成 Home Assistant Add-on，并带持久终端与网关接入。
- [Unofficial Hermes Agent Helm Chart](https://github.com/ultraworkers/hermes-agent-helm-chart) —— 面向 Kubernetes 的社区 Helm Chart，强调单写者持久化保护、完整 values schema，以及比裸 Docker Compose 更适合平台团队复用的云原生组合方式。
- [hermesclaw](https://github.com/TheAiSingularity/hermesclaw) —— 将 Hermes 放进 NVIDIA OpenShell 风格沙箱边界内运行。
- [openclaw-to-hermes](https://github.com/0xNyk/openclaw-to-hermes) —— OpenClaw 迁移辅助工具。
- [Honcho Self-Hosted for Hermes](https://github.com/elkimek/honcho-self-hosted) —— 自托管记忆后端方案。
- [Hermes Memory Installer](https://github.com/mage0535/hermes-memory-installer) —— 一键式持久记忆栈，带 SQLite FTS5、生命周期保护与 gbrain 知识图谱同步。
- [Hindsight](https://github.com/vectorize-io/hindsight) —— 可与 Hermes 工作流结合的长期记忆层。

## 集成与桥接

- [Integrations Overview](https://hermes-agent.nousresearch.com/docs/integrations)
- [Providers](https://hermes-agent.nousresearch.com/docs/integrations/providers)
- [Adding a Platform Adapter](https://hermes-agent.nousresearch.com/docs/developer-guide/adding-platform-adapters) —— 官方开发指南，说明如何通过插件系统接入新的消息平台适配器，覆盖 gateway 注册、鉴权、配置、Cron 投递和 prompt 提示注入。
- [QQ Bot](https://hermes-agent.nousresearch.com/docs/user-guide/messaging/qqbot) —— 官方 QQ 接入文档，说明如何通过 QQ Bot 官方 API v2 把 Hermes 连接到 QQ，覆盖私聊、群聊 @、频道消息和语音转写。
- [Hermes Home Assistant Integration](https://github.com/WolframRavenwolf/hermes-ha-integration)
- [gridmint/hermes-telegram](https://github.com/gridmint/hermes-telegram) —— 基于 MTProto / Telethon 的 Telegram 适配器，让 Hermes 不只依赖 Bot API，还能直接以真实 Telegram 用户账号身份接入。
- [hermes-android](https://github.com/raulvidis/hermes-android) —— Android 桥接。
- [hermes-miniverse](https://github.com/teknium1/hermes-miniverse) —— Miniverse 场景集成。
- [hermes-agent-acp-skill](https://github.com/Rainhoole/hermes-agent-acp-skill) —— Hermes 与其他代码 Agent 的桥接思路。
- [hermes-computer-use](https://github.com/Noah3521/hermes-computer-use) —— 面向 Hermes 的像素级浏览器自动化 MCP Server，利用 Xvfb 和系统级输入驱动原生 Chrome，适合更难被识别的网页工作流。
- [Hermes 技能 MCP 服务](https://github.com/poogas/hermes-skill-installer) —— 一个 MCP 桥接层，允许 Hermes 即使运行在隔离容器里，也能在宿主机上搜索、查看、安装、列出和移除技能。
- [evey-bridge-plugin](https://github.com/42-evey/evey-bridge-plugin) —— Hermes 与 Claude Code 的桥。
- [hermes-claude-code](https://github.com/DevvGwardo/hermes-claude-code) —— MCP server + 插件桥接层，把偏编码的任务从 Hermes 委派给 Claude Code CLI 子代理来完成实现、测试与 git 工作。
- [reina](https://github.com/Crustocean/reina) —— Crustocean 平台内的 Hermes 集成案例。
- [hermes-blockchain-oracle](https://github.com/gizdusum/hermes-blockchain-oracle) —— 区块链分析型 MCP/桥接项目。
- [hermes-council](https://github.com/Ridwannurudeen/hermes-council) —— 多视角对抗式决策支持。
- [hermes-CCC](https://github.com/AlexAI-MCP/hermes-CCC) —— 将 Hermes 的核心思路与技能工作流迁移到 Claude Code Channel。
- [Composio MCP 集成](https://composio.dev/toolkits/composio/framework/hermes-agent) —— 通过 Composio 的 SOC 2 合规 MCP 桥接层，把 Hermes 连接到 1,000+ SaaS 应用，自带托管 OAuth、工具路由与并行执行能力。
- [CodeGraph](https://github.com/colbymchenry/codegraph) —— 本地预索引代码知识图谱，用直接 SQLite 查询替代昂贵的 grep/read 循环，可为 Hermes 和其他编码 Agent 节省 50–90% 的 Token 用量和工具调用次数。

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
- [Hermes Agent（CaMeL 分支）](https://github.com/nativ3ai/hermes-agent-camel) —— 带 CaMeL trust boundaries 的 Hermes 分支，为间接提示注入提供运行时防护。
- [Hermes Skill Distillation](https://github.com/beardthelion/hermes-skill-distillation) —— 将真实任务轨迹转成 Hermes 4 微调数据的 hackathon 研究项目。

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
- [Hermes Agent Setup and Tutorial Guide（DataCamp）](https://www.datacamp.com/tutorial/hermes-agent) —— DataCamp 出品的综合性教程，从安装到本地模型、研究工作流和常见问题排查，适合入门到中级用户。
- [Hermes Agent + Honcho](https://docs.honcho.dev/v3/guides/integrations/hermes) —— Honcho 官方写的 Hermes 集成说明，讲清了 peer 建模、持久化写回，以及 Hermes 如何在本地记忆文件之外使用语义记忆工具。
- [Hermes Agent v0.13 Reference](https://blakecrosley.com/guides/hermes) —— 独立的深度参考文档，把架构、安装、Provider 鉴权、安全性和日常 CLI 操作整理到一处。
- [Hermes Agent Book](https://github.com/ZhangHanDong/hermes-book) —— 从源码层面系统解读 Hermes 的中文书，按章节拆开架构、提示词装配、工具系统、记忆提供器、CLI / Gateway 内核与运行时设计取舍。
- [Hermes Atlas](https://github.com/ksimback/hermes-ecosystem) —— 社区维护的 Hermes 生态地图与配套站点，汇总经过筛选的项目、主题资源列表、实时仓库指标、入门指南，以及更偏研究/观察性质的生态报告。
- [Hermes Atlas MCP](https://github.com/ksimback/hermes-atlas-mcp) —— 把 Hermes Atlas 的实时生态目录封装成 MCP Server，让 Claude Desktop、Cursor、Continue 等 MCP 客户端能直接在对话里检索 Hermes 工具、指南与生态项目。
- [Hermes-Agent-Action-Plan](https://github.com/vectrocomputers/Hermes-Agent-Action-Plan) —— 偏隐私优先的配置哲学与操作手册。
- [hermes-fleet-setup](https://github.com/Pu11en/hermes-fleet-setup) —— 10 个 Telegram bot 的实战搭建指南，包含隔离 profile、每个 agent 的 GitHub 认证，以及启动/停止脚本。
- [LLM-WIKI-TO-AGENT-Template](https://github.com/AlexChanshuo/LLM-WIKI-TO-AGENT-Template) —— 可复用蓝图，把 Obsidian 知识库、Hermes Telegram 图书管理员和 GitHub 备份串成一套个人知识工作流。
- [Hermes Memory Stack](https://github.com/yelixir-dev/hermes-memory-stack) —— 面向分层记忆、llmwiki 路由和可选 NotebookLM / source-pack 工作流的模块化启动栈。
- [hermes-wsl-ubuntu](https://github.com/metantonio/hermes-wsl-ubuntu) —— Windows WSL2 安装路径。

### 书籍与相关精选

- [Hermes Agent Orange Book](https://github.com/alchaincyf/hermes-agent-orange-book) —— 提供中英双语 PDF 下载的社区书籍，不只讲安装，还系统覆盖记忆、技能、自我改进闭环与多代理使用模式。
- [Hermes Agent Guide（白皮书）](https://github.com/jwangkun/hermes-agent-guide) —— 大体量中文 Markdown 白皮书，把分散文档整理成一条更系统的学习路径，覆盖架构、部署、迁移、变现思路与多 Agent 运营。
- [awesome-hermes-usecases](https://github.com/aliaihub/awesome-hermes-usecases) —— 基于一手来源整理的真实 Hermes 使用案例目录，并附带可运行 demo。
- [awesome-hermes-agent](https://github.com/0xNyk/awesome-hermes-agent) —— 另一份可交叉参考的 Hermes 精选列表。

### 视频

- [Hermes Agent Skills Tutorial](https://www.youtube.com/watch?v=cyn2JPlvTG4) —— 聚焦自定义 Skills 的使用方式与编写思路。
- [Hermes Agent Dashboard (Setup Guide and Overview)](https://www.youtube.com/watch?v=GfQEdMZ9LlA) —— 面向运维与重度用户的本地 Web Dashboard 上手视频。
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
