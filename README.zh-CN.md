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
- [J.A.R.V.I.S](https://github.com/eadmin2/jarvis_ai) —— 钢铁侠风格语音助手 + 全息 HUD，本地 Whisper STT、ElevenLabs TTS、实时工具调用可视化、审批卡片和打断支持，完全自托管。

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
- [Hermes Studio (Web UI)](https://github.com/EKKOLearnAI/hermes-studio) —— 功能完整的桌面应用和 Web 控制台，支持多平台聊天、会话管理、定时任务、使用分析、平台频道、文件浏览、Web 终端和语音 I/O，提供桌面应用、npm 包和 Docker 镜像三种分发方式。
- [Hermes War Room](https://github.com/Naroh091/hermes-war-room) —— 浏览器版运维控制面，把 Hermes 的原生编排能力可视化成 mission control、团队名册、实时 agent 状态和按 agent 划分的任务队列。
- [Minions](https://github.com/Agent-3-7/minions) —— 面向 Hermes 自主任务的 mission control 面板，使用持久化 root 会话做任务监督、回顾与状态跟踪。
- [Minions (Agent37)](https://github.com/agent37-platform/minions) —— 面向 Hermes 自主任务的 mission control 面板，提供看板任务板、任务创建界面和回顾流程，通过 `npx minionsai` 一键安装。
- [Hermes Telegram Mini App](https://github.com/clawvader-tech/hermes-telegram-miniapp) —— Telegram 内嵌的移动优先 Mini App，把聊天、Cron 控制、系统健康和后台 agent spawning 直接带进 Telegram，并附带更硬化的认证与隧道部署说明。
- [Hermes Voice Agent](https://github.com/onlockj/hermes-voice-agent) —— 低延迟的 Telegram 语音通道，带 PWA 前端、OpenAI Realtime 流水线、barge-in 支持和一键部署说明。
- [Atomic Bot](https://github.com/AtomicBot-ai/atomicbot) —— 原生桌面启动器，近期新增了 macOS / Windows 上的一键 Hermes 安装路径，适合想跳过终端、直接获得仪表盘、终端、日志和文件浏览能力的用户。
- [Web3Hermes](https://github.com/Web3CZ/Web3Hermes) —— 面向中国大陆用户的轻量中文 WebUI，主打桌面浏览器里的聊天、会话、工作区与任务视图。
- [Hermes HUD UI](https://github.com/joeynyc/hermes-hudui) —— 面向 Hermes 的浏览器版“意识监控面板”，可直接从 ~/.hermes/ 读取并可视化记忆、Token 成本、技能、Cron 任务与成长快照。
- [Hermes HUD](https://github.com/joeynyc/hermes-hud) —— HUD UI 对应的终端版监控面板，适合在 TUI 中实时查看记忆、技能、纠错痕迹、工具使用与 agent 成长状态。
- [Hermes Client](https://github.com/lotsoftick/hermes_client) —— 面向 Hermes 的 Web 聊天界面，支持多 Profile 管理、实时流式对话、Cron / Skill / Plugin 配置，以及 PWA 独立窗口。
- [Hermes Agent CN Desktop](https://github.com/Eynzof/hermes-agent-cn-desktop) —— 面向中文社区的 Windows 优先原生桌面客户端，基于 Tauri v2 + Rust + React，提供运行时管理、诊断、记忆工具和安全代理。
- [Hermes Chat Bubble](https://github.com/clearmud/hermes-chat-bubble) — 轻量级 dashboard 插件，为 Hermes Dashboard 添加浮动式 TUI 聊天气泡，复用已有持久化聊天宿主而非开启第二个会话。
- [ClawPanel](https://github.com/qingchencloud/clawpanel) —— 同时支持 OpenClaw 和 Hermes Agent 的多引擎 AI 管理面板，内置 AI 助手可自动完成环境检查、日志分析、配置修复和故障排查，底层采用 Rust + Tauri v2。

- [Agent Sessions](https://github.com/jazzyalex/agent-sessions) —— 原生 macOS 会话浏览器与驾驶舱，支持 Hermes（以及 Claude Code、Codex、OpenCode、Gemini CLI），可搜索/过滤所有历史会话、归档与恢复、实时查看速率限制与使用统计。
- [ReevesAgents](https://github.com/mertkayacs/reevesagents) —— 免费开源的 AI CLI 代理工作区管理器，集成 TUI、WebUI、MCP 服务器和 CLI，无需 API 密钥。
- [CC Switch](https://github.com/farion1231/cc-switch) —— 跨平台桌面一体化助手，一键安装 Hermes Agent，同时支持 Claude Code、Codex、OpenCode、OpenClaw 和 Gemini CLI，统一模型路由。
- [AionUi](https://github.com/iOfficeAI/AionUi) —— 免费、本地、开源的 24/7 协作应用，可管理 Hermes Agent 及 20+ 其他 CLI Agent，提供统一工作区和自定义模型路由。
- [Wesight](https://github.com/freestylefly/wesight) —— 开源桌面 AI Agent 工作台，支持一键安装 Hermes Agent、自定义 LLM 模型路由，以及 Claude Code、Codex 和 OpenClaw。
- [OpenClaw-Admin](https://github.com/itq5/OpenClaw-Admin) —— 基于 Vue 3 的 AI Agent 管理平台，同时支持 OpenClaw Gateway 和 Hermes Agent，提供 Web UI 管理 Agent、会话、模型、频道和技能。
- [iHermes](https://github.com/2winter-dev/iHermes) —— 移动优先的 Hermes 客户端，基于 Expo 构建，可从 Android、iOS 或 Web (PWA) 直接连接自建 Hermes Agent，无需强制后端服务。
- [Cadux](https://github.com/raymondclowe/cadux) —— 快速轻量的 Android 和桌面客户端，通过 SSE 流式传输、Bearer token 认证和局域网设备配对守护进程连接 Hermes Agent Gateway。
- [Hermes Swift iOS](https://github.com/hermes-webui/hermes-swift-ios) —— 原生 iPhone 客户端，通过 Tailscale 连接 Hermes WebUI，支持二维码扫描、语音输入和文件选择器集成。
- [My Hermes Desktop](https://github.com/wuguirongsg/My-Hermes-Desktop) —— 基于 Tauri 2 + React 的原生 macOS 伴侣应用，零终端操作，Apple 风格交互。
- [Hermes Theme Reflect](https://github.com/daletkc/hermes-theme-reflect) —— Hermes Agent Dashboard 高级暗色主题，深海军蓝底色搭配靛蓝-紫罗兰色调。
- [Republic (Daedalus)](https://github.com/JustinPerea/Republic) —— Hermes 黑客松获奖主题，采用 The Designers Republic 与 Marathon 视觉语言，骨白色配近纯黑底色、放射性黄色结构色、Geist Mono / IBM Plex 字体排印，并附带完整设计系统文档。
- [Agent of Empires](https://github.com/agent-of-empires/agent-of-empires) —— 跨平台 TUI 和 Web 管理界面，支持 Hermes、Claude Code、Codex、OpenCode、Gemini CLI 等多个编码 Agent，带移动端访问和会话共享。
- [Hermes Link Curator](https://github.com/dodo-reach/hermes-link-curator) —— 链接策展配置包，把 Hermes 变成图书管理员：发送 URL 即可归档、打标签、生成摘要，配有 Obsidian 风格的 Web 仪表盘。
- [Hermes Mini App Template](https://github.com/waguriagentic/hermes-miniapp-template) —— Telegram Mini App 模板，可直接 fork 扩展自定义工具和仪表盘，面向 Hermes Agent 开发者。
- [Vessel Browser](https://github.com/unmodeled-tyler/vessel-browser) —— 面向 Agent 工具链的开源 Chromium 浏览器，提供持久化状态、MCP 控制和人类可视监督界面，适合长时间运行的 Agent 工作流。
- [Hermes Island](https://github.com/esaradev/hermes-island) —— macOS Dynamic Island 菜单栏应用，实时监控 Hermes Agent 会话、记忆和多代理工作流。
- [Hermes Console](https://github.com/dannyshmueli/obsidian-hermes-console) —— Obsidian 社区插件，可直接在知识库中运行 Hermes Agent，提供终端标签页、选中笔记上下文桥接和完整设置界面；可通过 Obsidian 社区插件目录安装。

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
- [awesome-hermes-skills (ZeroPointRepo)](https://github.com/ZeroPointRepo/awesome-hermes-skills) —— 85 个内置 + 78 个社区技能、插件和工具，兼容 Claude Code、OpenClaw、Cursor 和 Windsurf。
- [hermes-skills (itgoyo)](https://github.com/itgoyo/hermes-skills) —— 310+ 个 Hermes Agent 技能，覆盖编程、营销、设计、金融、MLOps 和游戏开发，可通过克隆到 ~/.hermes/skills/ 安装。
- [hermes-merchant](https://github.com/arimanyus/hermes-merchant) —— 面向 ML/AI 求职自动化的 Hermes 技能包，可抓取职位、按画像打分，并自动填写 Greenhouse 申请。
- [hermes-skill-factory](https://github.com/Romanescu11/hermes-skill-factory) —— 将重复工作提炼成技能。
- [Hermes Memory Skills](https://github.com/nexus9888/hermes-memory-skills) —— 面向记忆维护的技能包，可在不同后端上执行 dreaming 与 surgical trimming。
- [Super Hermes](https://github.com/Cranot/super-hermes) —— 一组分析型技能，教 Hermes 写出更锋利的推理 lens、暴露盲点，并在深度分析中汇报结构性约束。
- [hermeshub](https://github.com/amanning3390/hermeshub) —— 社区技能发现入口。
- [skilldock.io](https://github.com/chigwell/skilldock.io) —— 跨 Agent 的技能注册表。
- [HyperDirector](https://github.com/gloweaseco-leo/hyperdirector) —— 面向 Hermes 的结构化 HyperFrames 视频生产技能包，串起 brief → storyboard → HTML → render 的完整工作流，并提供一键安装脚本。
- [agency-agents-zh](https://github.com/jnMetaCode/agency-agents-zh) —— 215 个即插即用的中文 AI 专家角色，覆盖工程、设计、营销、金融等 18 个部门，支持通过 `--category` 参数分批安装到 Hermes Agent。
- [hermes-agent-idea-workflow](https://github.com/AkoliteZA/hermes-agent-idea-workflow) —— 从模糊想法到设计文档、实现规格和 agent 可用构建交接的预构建 idea-to-spec 工作流技能。
- [LLMQuant 技能包](https://github.com/LLMQuant/skills) —— 18 个量化金融技能，覆盖股票、期权、宏观、加密、信贷、组合与风险，基于 LLMQuant Data，可一键安装到 Hermes、Claude Code、Codex、Cursor 和 OpenClaw。
- [hermes-agent-rtk-caveman](https://github.com/adityahimaone/hermes-agent-rtk-caveman) —— 开箱即用的 RTK + Caveman 配置，通过 Rust Token Killer 和 Caveman 模板化实现 CLI 操作 90–99% 的 token 节省，附带 40+ 预配置技能。
- [AI Agent Skills](https://github.com/kevinnft/ai-agent-skills) —— 191 个面向归属权的 Agent 技能，覆盖 Hermes Agent、Claude Code 和 Cursor，横跨 28 个类别，支持单一安装器和可搜索目录。

- [hermes-skill-atlas](https://github.com/codesstar/hermes-skill-atlas) —— 交互式技能地图，收录 70+ 经过验证的开源 Hermes 技能，支持搜索与分类筛选。
- [Felo 技能包](https://felo.ai/skills/hermes-agent) —— 12 个生产级 Hermes 技能，覆盖研究、幻灯片、内容创作、社交聆听和持久化 LiveDoc 工作流。
- [hermes-edu-skills](https://github.com/zhongweiv/hermes-edu-skills) —— 188 个结构化中文教育技能，覆盖教材同步、备考复习、教师工具和亲子学习，可通过 CLI 安装并导出到其他 Agent 工具。
- [Mercury Agent Skills](https://github.com/cosmicstack-labs/mercury-agent-skills) —— 跨 Agent 技能注册表，提供 Web 端发现中心，支持 Hermes、Claude Code、Codex、OpenClaw 和 Cursor，可一键 CLI 安装并支持版本锁定。
- [hermes-arxiv-agent](https://github.com/genggng/hermes-arxiv-agent) — arXiv 论文自动抓取技能，可生成中文摘要、每日推送飞书，并提供本地或 GitHub Pages 静态阅读站点。
- [YouTube Skills](https://github.com/ZeroPointRepo/youtube-skills) —— 面向 Hermes 等 Agent 的 YouTube 字幕提取、视频搜索与频道浏览技能，基于 TranscriptAPI，无需 Google 配额。
- [21-Day Self-Interview](https://github.com/Forlives/21-day-self-interview) —— 中英双语 Hermes 技能，连续 21 天每晚由 AI 提出三个人生自省问题，记住所有回答并在第 7、14、21 天将你的原话汇集成像回放，无需外部依赖。
- [Hermes Kanban Bridge](https://github.com/GumbyEnder/hermes-kanban) —— Obsidian 插件 + Hermes 技能，把 Hermes 变成住在你 Obsidian 知识库里的项目搭档，可以一句话把目标拆成看板、挪卡片、跑站会和周回顾——全程本地，无云依赖。
- [Cinema Manager](https://github.com/DavidBB-L/cinema-manager) —— 电影与剧集资源搜索技能，可自动保存到夸克网盘，面向媒体自动化工作流。
- [Hermes Proficiencies](https://github.com/sene1337/hermes-proficiencies) —— 可共享的操作属性技能，将人类 SOP 和手册编码为 agent 可读格式，支持安全发布和工作区维护。
- [Hermes SkillOpt](https://github.com/magnus919/hermes-SkillOpt) —— 源自微软研究院 SkillOpt 的受控技能优化，通过文本空间优化和验证门控，在 52/52 项测试设置上实现改善。
- [Hermes Council](https://github.com/magnus919/hermes-council) —— 多代理辩论系统，可组建自定义专家代理团队对任何问题进行结构化轮次辩论，生成可见对话记录和综合建议。纯 SKILL.md，零新基础设施。
- [Hermes Best Models](https://github.com/fox-in-the-box-ai/hermes-best-models) —— 专为 Hermes Agent 设计的 LLM 评估基准，帮助运维人员找到最适合自己场景的模型。
- [planning-with-files](https://github.com/OthmanAdi/planning-with-files) —— 针对长期运行 Agent 任务的持久化文件规划方案，提供崩溃安全的 Markdown 计划、确定性完成门控和多 Agent 共享状态，通过 SKILL.md 标准兼容 60+ Agent。
- [avoid-ai-writing](https://github.com/conorbronsdon/avoid-ai-writing) —— 审计并重写内容以去除 AI 写作模式的技能，兼容 Hermes、Claude Code 和 OpenClaw。
- [Hermes Skins](https://github.com/joeynyc/hermes-skins) —— Hermes CLI 的自定义皮肤和可视化主题，带社区贡献的风格。
- [Education Agent Skills](https://github.com/GarethManning/education-agent-skills) —— 165 个基于证据的教育技能，适用于 Claude、Codex、Hermes 及任何兼容 Agent Skills 的工具，覆盖教学法、评估和课堂自动化。
- [Deep Research Agent](https://github.com/CYC2002tommy/Deep-Research-Agent) —— 工业级科研流水线技能，从摘要检索到全文验证、Q1-Q2 期刊过滤、反幻觉检查到文档编译的全流程自动化。
- [Master Skill](https://github.com/swaylq/master-skill) —— 跨代理行业操作系统技能，自动从六个维度（行业大佬、工具地图、工作流、知识正典、信息源、术语标准）调研并蒸馏出可部署的行业技能，30-60 分钟完成。
- [SkillReaper](https://github.com/thousandflowers/skillreaper) —— 基于证据的剪枝工具，扫描真实对话记录识别并安全移除未使用的技能、MCP 服务和代理。
- [novel2hermes_jp](https://github.com/kgmkm/novel2hermes_jp) —— 日语小说写作技能包，结合 Hermes 记忆与 vecmemori 外部检索，支持长篇小说的企划与执笔。
- [dream-auto](https://github.com/StefanIsMe/dream-auto) —— 基于 MCTS 的自主梦境系统，在后台运行思考循环，探索替代推理路径并在会话之间巩固洞察。
- [hermes-persona](https://github.com/kenyonxu/hermes-persona) —— 动态人格上下文注入引擎，通过代码驱动配置调整人格、语调和行为规则。
- [Hermes Self-Iteration Skill](https://github.com/TangGV/hermes-self-iteration-skill) —— 上层执行协议，驱动 Hermes 自动完成分析 → 改进 → 验证 → ROI 门控循环，将任何项目、系统或工作流变成自成熟管线。

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
- [LanceDB Hermes Agent Memory](https://github.com/lancedb/hermes-agent-memory) — 基于 LanceDB 的记忆提供器，内嵌 workspace 级 LanceDB 表，支持向量 ANN 召回、可选混合模式（向量 + BM25，RRF 融合）以及带类型记忆通道的持久化事实。
- [Hermes Memory pgvector](https://github.com/andreab67/hermes-memory-pgvector) — 基于 Postgres + pgvector 的记忆提供器，面向多 Agent 编队，支持按 minion 主题分隔、异步写入，且记忆热路径上无需 LLM。
- [MemOS](https://github.com/MemTensor/MemOS) —— 更通用的 AI Memory OS，但已提供 Hermes 本地插件，带混合检索、智能去重、可视化记忆管理，以及适合多 Agent 共享的知识层。
- [agentmemory](https://github.com/rohitg00/agentmemory) —— 外部长时记忆引擎，已提供专门的 Hermes memory-provider 插件，同时带 REST / MCP 接口、会话回放和实时可视化界面，适合跨会话持续召回。
- [Supermemory](https://github.com/supermemoryai/supermemory) —— 官方记忆引擎与应用，支持 Hermes 接入，提供混合检索、连接器和长期上下文层。
- [Open Second Brain](https://github.com/itechmeat/open-second-brain) —— 基于 Obsidian 的持久化记忆层，可将 Obsidian 笔记库作为 Hermes 的记忆后端，通过逐夜“梦境”将重复纠正转化为可确认的偏好规则，支持确定性置信度评分及跨 Agent MCP 访问。
- [EverOS](https://github.com/EverMind-AI/EverOS) —— 可移植、自进化记忆层，支持 Claude Code、Codex、OpenClaw 和 Hermes，具备混合检索和跨 Agent 记忆同步。
- [LycheeMem](https://github.com/LycheeMem/LycheeMem) —— 轻量级长期记忆，MCP 原生混合检索，工作区级召回，对 Hermes 提供一等支持。
- [Sibyl Memory](https://github.com/Sibyl-Labs/Sibyl-Memory) —— 持久化记忆插件，结构化分层存储、本地 SQLite、无需向量数据库，提供 SDK/CLI/MCP/插件多种接口。
- [mem9 Hermes Plugin](https://github.com/mem9-ai/mem9-hermes-plugin) —— 托管式持久记忆插件，提供语义召回、逐轮信息抽取与简洁的 CLI 接入流程。
- [yantrikdb-hermes-plugin](https://github.com/yantrikos/yantrikdb-hermes-plugin) —— 自维护记忆提供器，支持去重归一、矛盾追踪与可解释召回。
- [hermes-observational-memory](https://github.com/intertwine/hermes-observational-memory) —— 独立 memory-provider 插件，让 Hermes 与 Claude Code、Codex 共用本地 Markdown 记忆库，并支持可搜索观察记录与可选写回。
- [hermes-plugins](https://github.com/42-evey/hermes-plugins) —— 一组社区插件合集。
- [DashClaw](https://github.com/ucsandman/DashClaw) —— AI Agent 治理运行时，拦截操作、强制策略、要求审批，并产生审计就绪的决策轨迹。
- [hermes-otel](https://github.com/briancaffey/hermes-otel) —— Hermes Agent 的 OpenTelemetry 插件，导出链路、指标和日志，可对接 Grafana、Datadog 等 OTel 兼容后端。
- [ShellWard](https://github.com/jnMetaCode/shellward) —— AI Agent 安全中间件，提供 8 层纵深防御、DLP 数据流管控和提示注入检测；零依赖，可作为独立 SDK 或 OpenClaw 插件，支持 Claude Code、Cursor、LangChain 和 Hermes。
- [TokenTelemetry](https://github.com/VasiHemanth/tokentelemetry) —— 100% 本地可观测性仪表盘，追踪 Hermes Agent、Claude Code、Codex、Gemini CLI 等 30+ 平台的 token 用量、成本、工具调用、会话轨迹和推理步骤。
- [Pi Hermes Memory](https://github.com/chandra447/pi-hermes-memory) —— 为 Pi 编码 agent 移植的持久化记忆与学习循环，带来 Hermes 风格的会话检索、分类记忆、密钥扫描和后台记忆整合。
- [hermes-tools](https://github.com/axisdynamics/hermes-tools) —— 面向实战的原生插件包，包含 agent 间 pub/sub、provider 失败切换和持久化记忆等能力。
- [Hermes Plugin: Carabiner](https://github.com/donovan-yohan/hermes-plugin-carabiner) —— 依托 Honcho 的关系记忆插件，专门记录 specialist agent 之间的交接、反馈循环和协作上下文。
- [hermes-notification](https://github.com/itgoyo/hermes-notification) —— 很轻量的跨平台插件，在 Hermes 完成回复后触发原生桌面通知和提示音。
- [hermes-web-search-plus](https://github.com/robbyczgw-cla/hermes-web-search-plus) —— 更强的 Web 搜索路由能力。
- [cronalytics](https://github.com/8bit64k/cronalytics) —— Cron 分析与可观测插件，可视化定时任务的历史记录、运行时长、失败率和消耗。
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
- [Hermes Long-Run Orchestrator](https://github.com/yuzai-code/hermes-plugin-long-run-orchestrator) —— 将 30 分钟以上的编码任务派发到 tmux 里的 Claude Code/Codex，带 watchdog 进度检查和飞书/Telegram 完成通知，Hermes 只做调度器。
- [Hermes DeepL Plugin](https://github.com/drmzperx/hermes-deepl-plugin) —— 基于 DeepL 的翻译和用量查询工具，零第三方依赖，自动根据 API Key 格式选择 Free 或 Pro 端点。
- [hermes-payguard](https://github.com/nativ3ai/hermes-payguard) —— 支付控制相关插件。
- [Hermes Dojo](https://github.com/Yonkoo11/hermes-dojo) —— 针对 Hermes 的自我改进闭环，会从会话失败里挖掘薄弱技能、自动修补，并支持夜间 analyze→improve→report 流程。
- [Ladybug Memory Plugin](https://github.com/Ladybug-Memory/hermes-memory-plugin) —— 本地优先的记忆提供器，把 Hermes 的长期记忆保存在单个 `.lbdb` 图数据库文件里，支持类型化记忆、权重召回与可选实体抽取。
- [Membase for Hermes](https://github.com/aristoapp/hermes-membase) —— 持久记忆插件，把混合向量检索与知识图谱召回、Wiki 检索以及 Hermes 内置 `MEMORY.md` 镜像结合起来，适合想把长期记忆从本地文件扩展到共享记忆层的用户。
- [Memory OS](https://github.com/ClaudioDrews/memory-os) —— 面向 Hermes Agent 的 7 层记忆操作系统，集成 Qdrant 向量库、带实体解析的结构化事实、LLM 驱动的会话抽取、自动策展 Wiki 知识库和多源精确召回。
- [Hermes Dashboard Plugin](https://github.com/tmdgusya/hermes-dashboard-plugin) —— 基于官方 dashboard plugin SDK 的轻量扩展，用一个带 neubrutalism 风格的新标签页整合会话、技能、Profile、Token 使用和可编辑的记忆文件视图。
- [Hermes Plugin: Credits](https://github.com/Atemndobs/hermes-plugin-credits) —— Dashboard 插件，为 Analytics 标签页添加 Provider 余额/配额小部件，可实时查看 OpenRouter 余额、Anthropic 限速利用率和 OpenAI/Codex 每分钟 token 数，无需切换到各平台面板。
- [Hermes Trace](https://github.com/hlothaire/hermes-trace) —— 执行轨迹插件，捕获每个 turn、LLM 调用、工具调用、子代理启动和审批请求为结构化有向图，提供 18 个生命周期钩子、`/trace` 斜杠命令、ASCII Gantt 时间线、Mermaid 导出和 CLI 查询工具。
- [Hermes TPS Counter](https://github.com/ryan-brosas/hermes-tps-counter) —— 轻量插件，追踪每次 LLM 调用后的 token 生成速率，并在 Hermes 状态栏注入实时 TPS、滚动均值、峰值和 token 统计。
- [Hermes Theme Editor](https://github.com/sanchomuzax/hermes-theme-editor) —— 可视化 dashboard 主题编辑插件，可直接创建、预览并启用自定义 YAML 主题，无需手工改文件。
- [Hermes Prompt Vault](https://github.com/LeventeNagy/hermes-prompt-vault) —— 提示词库插件，支持 `/vault` 命令和 Dashboard 界面，可保存、检索并复用来自各个平台的提示词。
- [Hermes Workspace Dashboard Plugin](https://github.com/outsourc-e/hermes-workspace-plugin) —— 将 Hermes Workspace 聊天界面嵌入 Hermes Dashboard 的标签页，支持本地端口自动发现与一键安装。
- [Hermes Canvas](https://github.com/tonbistudio/hermes-canvas) —— 把 Hermes Dashboard 变成实时前端创作工作室的插件，带项目脚手架、开发服务器控制和 Agent 驱动编辑。
- [Hermes Achievements](https://github.com/PCinkusz/hermes-achievements) —— 把真实的 Hermes 会话历史转成可收集的 Dashboard 成就与徽章系统。
- [Agent Analytics Hermes Plugin](https://github.com/Agent-Analytics/agent-analytics-hermes-plugin) —— 面向 Hermes 仪表盘的只读分析插件，可把账号连接、项目选择和 Web 分析视图直接嵌进 Hermes 控制台，方便把业务信号和 Agent 活动放在一起看。
- [Hermes Labyrinth](https://github.com/stainlu/hermes-labyrinth) —— 只读型 dashboard 插件，把 Hermes 当成“飞行记录仪”来观测：可把提示词、工具调用、失败、审批、记忆命中、Cron 运行和子代理轨迹整理成可导出的观测路径，而不是再做一个聊天界面。
- [Honcho Memory Plugin](https://github.com/GumbyEnder/hermes-plugins) —— 以 Honcho 记忆面板为核心的 dashboard 插件集合，提供实时统计、队列健康度、语义搜索，以及文档 / 消息历史的下钻视图。
- [GBrain](https://github.com/garrytan/gbrain) —— Garry Tan 出品的生产级知识图谱大脑层，可对个人和机构知识做综合、图遍历和缺口分析，支持向量 / BM25 混合检索、自装配实体图谱和崩溃安全的子代理任务队列。
- [Memory OS](https://github.com/ClaudioDrews/memory-os) —— 面向 Hermes Agent 的 7 层记忆操作系统，集成 Qdrant 向量召回、结构化事实、fabric 召回、自动生成 Wiki 和手术式上下文注入，本地运行，支持任意 LLM 后端。

- [ClawSec](https://github.com/prompt-security/clawsec) —— Prompt Security 维护的安全技能套件，提供 NVD 安全公告 feed、SOUL.md 与配置文件漂移检测、技能供应链完整性校验，以及 Hermes 专属的 `hermes-attestation-guardian` 技能。
- [ClawShell](https://github.com/clawshell/clawshell) —— 面向 Hermes 和 OpenClaw 的运行时安全层，通过虚拟到真实密钥映射代理拦截 LLM API 调用，用可配置 DLP 模式扫描 PII，隔离邮件访问，并暴露使用审计接口。
- [ComfyUI Skills for OpenClaw](https://github.com/HuangYuChuh/ComfyUI_Skills_OpenClaw) —— 把任意 ComfyUI 图像生成工作流转化为可通过 CLI 调用的 Hermes/Agent 技能，支持基于 schema 的参数映射、多服务器路由和依赖检查。
- [Hermes 多代理工作流模板](https://github.com/tonbistudio/hermes-multi-agent-workflow) —— 基于 Hermes Kanban 构建的可复用分诊流水线模板：`sources → intake → dedup → score → research → route → Human Gate → fulfill → deliver`，引擎逻辑与领域配置分离，通过 triage.yaml 定制。
- [superpowers-zh](https://github.com/jnMetaCode/superpowers-zh) —— superpowers 技能包（116K+ 星）的中文增强版，新增 6 个原创技能，完整汉化支持 Hermes Agent 及其他 15 款 AI 编程工具。
- [Draw.io Skill](https://github.com/Agents365-ai/drawio-skill) —— 从自然语言生成 draw.io 图表，提供 6 种预设、视觉自检、最多 5 轮精修、10,000+ 官方图形和 PNG/SVG/PDF 导出。
- [Hermes Tool Router](https://github.com/AtlasOmnia/hermes-tool-router) —— 条件化工具 Schema 加载，按提示词实际需要加载工具以减少首轮 token 膨胀，对长或模糊请求提供安全的全量回退。
- [Hermes D1 Memory](https://github.com/benben17/hermes-d1-memory) —— 基于 Cloudflare D1 的外部记忆提供器，使用无服务器边缘部署的 SQLite + FTS5，提供零维护的长期记忆持久化。
- [Hermes Voice HA Integration](https://github.com/rusty4444/hermes-voice-ha-integration) —— Home Assistant 语音栈，串联唤醒词检测、STT、Hermes LLM 和 TTS 回传到 HA media_player，全程本地无需云服务。
- [Hardmail](https://github.com/orlyjamie/hardmail) —— 面向 Hermes 的加固型无 shell 原生邮件工具，覆盖 Gmail、IMAP、SMTP 和 Resend，发送需操作员审批且采用默认失败关闭策略。
- [Inkbox Plugin](https://github.com/inkbox-ai/hermes-agent-plugin) —— 面向 Inkbox 平台的 Hermes Agent 插件。
- [多通道提示词优化器](https://github.com/Sahil-SS9/hermes-multichannel-prompt-optimizer) —— 在用户提示词到达 LLM 之前进行重写的插件，支持模型感知定制、质量评分和跨 CLI、TUI、Discord、Telegram 的分析。
- [LLM-Wiki Obsidian Hermes](https://github.com/r0b0tlab/llm-wiki_obsidian_hermes_r0b0tlabbra1n) —— 文件系统优先的记忆系统，桥接 LLM-Wiki、Obsidian 和 Hermes，以 Markdown 为真相源，提供 SQLite FTS5 搜索、密钥扫描和分层上下文包。
- [Hermes Roaming](https://github.com/rtsitola/hermes-roaming) —— 通过 Syncthing 实现跨机器记忆漫游，支持主从架构和自动导入/导出，适用于多设备 Hermes 部署。
- [Hermes WeChat Relay](https://github.com/c1422113471-cpu/hermes-wechat-relay) —— Profile 本地微信中继插件，通过外部桥接转发微信消息，无需修改 Hermes 核心或替换内置 weixin 适配器。
- [Hermes Health Apollo](https://github.com/Infinite-Labs-AI/hermes-health-apollo) —— 本地优先健康智能插件，连接可穿戴设备数据、日历上下文和 Gmail 元数据，让 Hermes 能回答从健康状态到下一步行动的问题。
- [Hermes Tavern](https://github.com/gchigoo/hermes-tavern) —— 独立的 SillyTavern 兼容角色扮演与小说运行时，作为插件运行在 Hermes Agent 网关上，支持角色卡导入、会话管理和 RP 特定斜杠命令。
- [Meshtastic Hermes Plugin](https://github.com/thpham/meshtastic-hermes-plugin) —— 面向 LoRa 网状网络（Meshtastic）的 Hermes 插件，提供消息工具、节点交互知识库和双向网关，采用隐私设计处理数据包。
- [Hermes Tesla Fleet Plugin](https://github.com/Oceanswave/hermes-tescmd-plugin) —— 原生 Tesla Fleet API 插件，提供 175 个类型化工具，覆盖车辆状态、充电、空调、安全、导航和能源站点操作，带确认门控。
- [Hermes Delegate Guard](https://github.com/mosqlee/hermes-delegate-guard) —— 两个安全插件，一个阻止 delegate_task 代码修改滥用（强制"Claude 规划，Codex 实现"），另一个检测并抑制工具连接失败的级联错误。
- [Hermes Mattermost Enhancer](https://github.com/colin-chang/hermes-plugin-mattermost-enhancer) —— 让 Hermes 在 Mattermost 中更好用的增强插件，提供危险命令审批卡片、/model 模型切换、WebSocket 稳定性改进等。

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
- [hermes-agent-control-room](https://github.com/CryptoDmitry/hermes-agent-control-room) —— 以控制室为核心的第一优先级模板，从一台 VPS 管理多团队 Hermes Agent 编排工作流。
- [Unofficial Hermes Agent Helm Chart](https://github.com/ultraworkers/hermes-agent-helm-chart) —— 面向 Kubernetes 的社区 Helm Chart，强调单写者持久化保护、完整 values schema，以及比裸 Docker Compose 更适合平台团队复用的云原生组合方式。
- [hermesclaw](https://github.com/TheAiSingularity/hermesclaw) —— 将 Hermes 放进 NVIDIA OpenShell 风格沙箱边界内运行。
- [openclaw-to-hermes](https://github.com/0xNyk/openclaw-to-hermes) —— OpenClaw 迁移辅助工具。
- [Honcho Self-Hosted for Hermes](https://github.com/elkimek/honcho-self-hosted) —— 自托管记忆后端方案。
- [Hermes Memory Installer](https://github.com/mage0535/hermes-memory-installer) —— 一键式持久记忆栈，带 SQLite FTS5、生命周期保护与 gbrain 知识图谱同步。
- [Hindsight](https://github.com/vectorize-io/hindsight) —— 可与 Hermes 工作流结合的长期记忆层。
- [MNEMOS](https://github.com/ncz-os/mnemos) —— 面向 Agentic AI 的生产级记忆操作系统，支持四种持久化后端（PostgreSQL、Oracle 26ai、IBM Db2、SQLite）、梦境管线、GDPR 合规与统一 MCP 接口，兼容 Hermes、Claude Code、OpenClaw、LangChain 等主流框架。
- [Scope Recall Hermes](https://github.com/410979729/scope-recall-hermes) —— Hermes Agent 的作用域记忆提供者，采用 SQLite 真值源、LanceDB 语义召回和每夜工作流摘要。

- [NVIDIA NemoClaw](https://github.com/NVIDIA/NemoClaw) —— NVIDIA 开源的沙箱化 Agent 运行时，提供专门的 Hermes 快速启动入口，可在 OpenShell 沙箱中实现硬化执行环境、网络策略管控和托管推理。Apache 2.0。
- [NemoClaw Community](https://github.com/NVIDIA/nemoclaw-community) — NVIDIA 社区驱动的示例与集成仓库，展示如何用 NemoClaw 蓝图组合出可约束、可审查的 Agent 工作流。
- [tenbox](https://github.com/78/tenbox) —— 面向 Hermes 的轻量级 x86-64/arm64 虚拟机监控器（VMM），用硬件加速虚拟化为 Agent 提供 VM 级隔离边界，作为容器沙箱的替代方案。跨平台支持 Windows WHVP、macOS Hypervisor Framework 和 Linux KVM。
- [Mem0 集成](https://docs.mem0.ai/integrations/hermes) —— 官方 Mem0 记忆提供者插件，支持自动后台同步、零延迟预取与语义重排。
- [hermes-patches](https://github.com/Cyrene963/hermes-patches) —— 社区补丁集合，覆盖记忆元认知、结构化记忆图谱工具、混合技能选择器、多用户隔离与 Telegram 上下文增强，采用 overlay-first 安装策略。
- [ClawPhone](https://github.com/marshallrichards/ClawPhone) —— 在 Android 智能手机上运行 Hermes Agent（以及 OpenClaw、Claude Code、Codex）的脚本与配置，基于 Termux 部署。
- [Hermes Agent Android 版](https://github.com/AbuZar-Ansarii/Hermes-Agent-On-Android) —— 通过 Termux 一键安装，在任意 Android 设备上运行 Hermes Agent。
- [hermes-concurrent-agents](https://github.com/r0b0tlab/hermes-concurrent-agents) —— 在统一内存 GPU 上部署多个并发 Hermes worker，支持 profile 隔离、看板协调和崩溃恢复，最大化吞吐量。
- [Hermes Operator](https://github.com/UndermountainCC/hermes-operator) —— 面向 Kubernetes 的 Hermes Agent 算子，通过声明式 CRD 管理部署。
- [ClawFleet](https://github.com/clawfleet/ClawFleet) —— 开源舰队管理器，将多个 Hermes（和 OpenClaw）代理部署在隔离的 Docker 容器中，提供浏览器仪表板、一键安装和版本锁定。
- [Hermes Claude Code Local](https://github.com/KaiFelixBennett/hermes-claude-code-local) —— 在 llama.cpp 上本地运行 Hermes Agent 和 Claude Code，零 API 费用；基准测试显示 4 小时 / 700 万 token 会话在 Claude Opus 上需花费 $94。
- [Hermes Swarm Map](https://github.com/NimbleCoAI/hermes-swarm-map) —— 多人管理编排平台，从单一仪表盘管理多个 Hermes Agent 实例，提供设置向导、模型级联、多租户安全、预算控制和 Telegram/Signal/Mattermost 连接。
- [Hermes Cockpit](https://github.com/goktugozdem2/hermes-cockpit) —— 跨项目任务控制面板，适合运行多个自主 Worker、Cron 任务和编码 Agent 的操作者，提供项目健康卡、任务队列和跨项目告警。
- [Hermes Advanced Profile Manager](https://github.com/MaverickKB/hermes-advanced-profile-manager) —— 轻量本地 WebUI 用于全面管理 Hermes 配置，提供就绪评估、技能与技能组、工具集、MCP 服务器、Provider、委派权限、备份审计和交互式系统图。
- [Hermes Memory-OS](https://github.com/btnalit/Hermes-Memory-OS) —— 面向 Hermes 的工程化 Agent OS 运行时，支持双引擎记忆（SQLite + 平面文件）、确定性状态机锁、时间衰减加权检索和所有者审查反馈循环。
- [Nexus Memory](https://github.com/Neboy72/nexus-memory) —— 自托管通用记忆层，支持混合检索（向量 + BM25），三种部署模式（Hermes 插件、OpenClaw 插件、MCP 服务），本地优先存储。

- [hermes-alpha](https://github.com/kaminocorp/hermes-alpha) —— Hermes Agent 的云部署版，提供精简的云端一键部署，适合希望使用托管云运行时而非自托管的用户。
- [Hermes Agent One-Click Kit](https://github.com/sodam-ai/Hermes-Agent_One-Click_Kit) —— 新手友好的 Windows .bat 安装器，双击即可完成 Hermes Agent 安装、Messenger 连接和登录，配有韩语/英语文档。
- [claude-tap](https://github.com/liaohch3/claude-tap) —— 本地代理和追踪查看器，拦截并检查 Hermes、Claude Code、Codex、Gemini CLI 等编码 Agent 的 API 流量，暴露系统提示词、工具调用、流式响应和 Token 用量到自包含 HTML 查看器中。

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
- [hermes-mcp](https://github.com/mlennie/hermes-mcp) —— MCP 反向桥接层，让 Claude Desktop、Claude.ai 等 MCP 客户端通过 OAuth 2.1 将定时任务、浏览器操作、邮件、搜索等任务委托给本地 Hermes Agent 执行，支持 cloudflared 隧道远程访问。
- [evey-bridge-plugin](https://github.com/42-evey/evey-bridge-plugin) —— Hermes 与 Claude Code 的桥。
- [hermes-claude-code](https://github.com/DevvGwardo/hermes-claude-code) —— MCP server + 插件桥接层，把偏编码的任务从 Hermes 委派给 Claude Code CLI 子代理来完成实现、测试与 git 工作。
- [reina](https://github.com/Crustocean/reina) —— Crustocean 平台内的 Hermes 集成案例。
- [hermes-blockchain-oracle](https://github.com/gizdusum/hermes-blockchain-oracle) —— 区块链分析型 MCP/桥接项目。
- [hermes-council](https://github.com/Ridwannurudeen/hermes-council) —— 多视角对抗式决策支持。
- [hermes-CCC](https://github.com/AlexAI-MCP/hermes-CCC) —— 将 Hermes 的核心思路与技能工作流迁移到 Claude Code Channel。
- [Composio MCP 集成](https://composio.dev/toolkits/composio/framework/hermes-agent) —— 通过 Composio 的 SOC 2 合规 MCP 桥接层，把 Hermes 连接到 1,000+ SaaS 应用，自带托管 OAuth、工具路由与并行执行能力。
- [LangBot](https://github.com/langbot-app/LangBot) —— 生产级多平台智能机器人开发平台（16K+ 星标），支持 Hermes Agent 作为后端，覆盖 Discord、Slack、LINE、Telegram、微信、飞书、钉钉和 QQ，自带知识库编排与插件系统。
- [hermesclaw 微信](https://github.com/AaronWong1999/hermesclaw) —— 在同一微信账号上同时运行 Hermes Agent 和 OpenClaw，实现统一消息管理。
- [clawmes](https://github.com/clawnchdev/clawmes) — Hermes Agent 加密货币插件，覆盖钱包管理、DEX 交易、借贷质押、治理投票和链上自动化，测试覆盖 100%。
- [hermes-nextcloud](https://github.com/adnw-vinc/hermes-nextcloud) —— 通过 WebDAV/CalDAV 管理 Nextcloud 文件、笔记、日历、任务和联系人的 Hermes 技能。
- [CodeGraph](https://github.com/colbymchenry/codegraph) —— 本地预索引代码知识图谱，用直接 SQLite 查询替代昂贵的 grep/read 循环，可为 Hermes 和其他编码 Agent 节省 50–90% 的 Token 用量和工具调用次数。
- [Infisical agent-vault](https://github.com/Infisical/agent-vault) —— 面向 AI Agent 的 HTTP 凭证代理与保管库，支持 Hermes、Claude Code 和 OpenClaw 等 Agent，提供集中式密钥管理和细粒度访问控制。
- [hermes-claude-auth](https://github.com/kristianvast/hermes-claude-auth) —— Hermes Agent 的 Claude Code OAuth 绕过工具，无需标准认证流程即可访问 Claude 模型。
- [PrediHermes](https://github.com/nativ3ai/hermes-geopolitical-market-sim) —— 地缘政治市场预测 Hermes 技能，整合 WorldOSINT 情报源、Polymarket 市场发现和 MiroFish 多 agent 模拟工作流。

- [wechat-acp](https://github.com/formulahendry/wechat-acp) —— 桥接微信聊天消息到任意 ACP 兼容 AI Agent，包括 Hermes、Claude、Codex 和 Gemini，覆盖个人聊天、群聊和 Bot 场景。
- [agentcookie](https://github.com/mvanhorn/agentcookie) —— 通过 Tailscale 在多台 Mac 之间同步 Agent 会话，让远程主机上的 Hermes 或 OpenClaw 启动时已自动鉴权，端到端对等网络，无需云中间人。
- [Hermes Agent QQ Plugin](https://github.com/shynloc/Hermes-Agent-QQ-Plugin) —— QQ 聊天插件，基于 OpenClaw QQ Bot 适配 Hermes Agent，将 QQ 作为原生频道。
- [hermes-multitenancy](https://github.com/eggyrooch-blip/hermes-multitenancy) —— Feishu Bot 多租户路由插件，一个 Bot 实例服务多个用户，各自隔离配置。
- [hermes-tweet](https://github.com/Xquik-dev/hermes-tweet) —— 原生 Hermes Agent X/Twitter 自动化插件，通过 Xquik 实现发布、调度和交互工作流。
- [Hermes Lansenger Adapter](https://github.com/lansenger-pm/hermes-lansenger-adapter) —— 面向蓝信（Lansenger）企业通讯平台的消息适配器，提供 WebSocket 实时消息、审批卡片、媒体工具和 Markdown 投递，纯插件模式，零核心修改。

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
- [Oh My Hermes](https://github.com/Salomondiei08/oh-my-hermes) —— 自治式工作流层，包含 23 个技能和 5 条工作流，把 Hermes 升级为全栈 CTO，可独立管理看板、分诊 GitHub issue、执行安全扫描和人机协作部署。
- [hermes-agent-rs](https://github.com/Lumio-Research/hermes-agent-rs) — Hermes 的完整 Rust 重新实现，编译为单个约 16MB 静态二进制文件，零依赖，支持 10 种 LLM 提供商、30+ 工具、17 种平台适配器、8 种记忆后端，基于 Tokio 异步运行时；可在树莓派和离线服务器上运行。
- [go-magic](https://github.com/magicwubiao/go-magic) — 高性能、超轻量的 Go 语言 Hermes Agent 重新实现，配套 React/TypeScript Web 仪表盘，面向资源受限环境的单二进制部署。
- [Hermes Turbo Agent](https://github.com/wesleysimplicio/hermes-turbo-agent) — 性能基准测试、优化热路径与 turbo 评分系统，面向生产环境 Hermes 部署，目标 100 倍执行速度提升。
- [Perseus](https://github.com/tcconnally/perseus) —— 面向 AI 助手的实时上下文引擎，提供解析先于上下文、会话航点和工具选择智能，专为 Hermes Agent 设计。
- [Hermes Code Bridge](https://github.com/xuyang-liu16/hermes-code-bridge) —— 将 Hermes Agent 用作本地编码代理（Codex、Kimi Code、Claude Code、OpenCode、Gemini CLI）的控制平面。
- [Hermes System Doctor](https://github.com/AlekseiUL/hermes-system-doctor) —— 面向 Hermes Agent 的诊断与审批门控修复规划工具，在问题演变为故障前识别并处理。
- [Hermes Bumblebee Bridge](https://github.com/Deconstruct2021/hermes-bumblebee-bridge) —— 基于 Perplexity Bumblebee 的只读供应链扫描，提供每日扫描、Telegram 告警和 JARVIS 风格叙述。
- [Hermes Compression Eval](https://github.com/NousResearch/hermes-compression-eval) —— 官方离线评估工具，用于测试 Hermes ContextCompressor 的压缩质量，涵盖准确性、上下文感知和工件追踪等维度的探针评分。
- [Olympian](https://github.com/jahilldev/olympian) —— AI 无人工厂，驱动 Hermes Agent 完成从 issue 到 PR 的全生命周期：规划、多轮迭代实现、置信度自评审和草稿 PR，人类只需批准方案和最终 PR。
- [Home AI Mesh](https://github.com/punchtaylor/home-ai-mesh) —— MIT 开源的多节点家庭 AI 网络构建指南，通过 Raspberry Pi、Jetson 和 GPU 协调 MQTT 和 Hermes Agent，支持故障转移、金融、语音和监控节点。
- [Autocontext](https://github.com/greyhaven-ai/autocontext) —— 递归式自改进框架，帮助 AI Agent 在复杂目标上通过迭代式优化不断改进，支持原生 Hermes Agent 技能导出，可无缝整合到任意 profile 中。

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
- [Learn Hermes Agent](https://github.com/longyunfeigu/learn-hermes-agent) —— 27 章代码优先教程，从零开始用 Python 构建自主 AI Agent，覆盖 agent 循环、工具系统、记忆、技能、MCP、多平台网关和自我进化——灵感来自 Hermes Agent。
- [hermes-agent-team](https://github.com/linke-ai/hermes-agent-team) —— 基于 Hermes Agent 构建的本地多 Agent 团队协作 Web 系统，提供中文 UI 和基于角色的 agent 编排。
- [Hermes Forge](https://github.com/Mahiruxia/hermes-forge) —— 本地优先的 Hermes Agent 桌面工作台，集成自动部署、模型同步、Windows 桥接、微信 Gateway、文件附件、权限审批和 GitHub 自动更新。
- [RunbookHermes](https://github.com/Tommy-yw/RunbookHermes) —— 面向 Hermes 的 AIOps Agent，基于证据驱动的事件响应、审批门控恢复，并从历史事件中学习 Runbook。
- [hermes-life-os](https://github.com/Lethe044/hermes-life-os) —— 个人操作系统 Agent，自学习用户偏好、检测生活模式，结合记忆、Cron 和 Atropos RL 持续自我提升。
- [Hermes Dynamic Workflows](https://github.com/lingjiuu/hermes-dynamic-workflows) —— 为 Hermes 带来 Claude Code 风格的动态工作流引擎，模型可按需编写并执行沙盒化 Python 脚本，适合大规模编排任务。

## 指南、书籍、视频与相关列表

### 社区文档与指南

- [hermes-agent-docs](https://github.com/mudrii/hermes-agent-docs) —— 社区补充文档。
- [HermesWiki](https://github.com/martymcenroe/HermesWiki) —— 社区 Wiki。
- [Hermes-Wiki](https://github.com/cclank/Hermes-Wiki) —— 基于源码核对的架构 Wiki，拆解较深。
- [llm-wiki-compiler](https://github.com/atomicmemory/llm-wiki-compiler) —— 通用型 Wiki 编译工具，可把原始资料整理成可互链的 Markdown Wiki，方便 Hermes 用户持续查询与扩展外部知识。
- [hermes-agent-anatomy](https://github.com/anneheartrecord/hermes-agent-anatomy) —— 中文源码解剖系列，带图示和模块分析。
- [hermes-optimization-guide](https://github.com/OnlyTerp/hermes-optimization-guide) —— 包含安装、迁移、LightRAG、Telegram 与技能构建的实战指南。
- [Hermes Agent 源码学习指南](https://github.com/xiehongyu777/hermes-agent-guide) —— 中文源码学习指南，逐模块讲解 Hermes Agent 内部实现。
- [Hermes Agent Setup and Tutorial Guide（DataCamp）](https://www.datacamp.com/tutorial/hermes-agent) —— DataCamp 出品的综合性教程，从安装到本地模型、研究工作流和常见问题排查，适合入门到中级用户。
- [Hermes Agent + Honcho](https://docs.honcho.dev/v3/guides/integrations/hermes) —— Honcho 官方写的 Hermes 集成说明，讲清了 peer 建模、持久化写回，以及 Hermes 如何在本地记忆文件之外使用语义记忆工具。
- [Hermes Agent v0.13 Reference](https://blakecrosley.com/guides/hermes) —— 独立的深度参考文档，把架构、安装、Provider 鉴权、安全性和日常 CLI 操作整理到一处。
- [Goal Video Resources](https://github.com/nemanjadotcom/goal-video-resources) —— 来自"I Was Wrong About Hermes Agent /goal"视频的 prompts、AGENTS.md 和 SOUL.md 文件。
- [Hermes Telegram Artifacts](https://github.com/camel-vibe/hermes-telegram-artifacts) —— 独立的产物服务器 + 技能，通过 Telegram Mini Apps 在 Hermes Agent 中交付交互式 HTML 小组件。
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
- [awesome-hermes-agent (SamurAIGPT)](https://github.com/SamurAIGPT/awesome-hermes-agent) —— 另一份精选列表，按成熟度标签（production/beta/experimental）整理了 Hermes Agent 的技能、插件、工具与集成资源。
- [awesome-hermes-agent-zh](https://github.com/jefferyjob/awesome-hermes-agent-zh) —— 中文精选列表，整理了 Hermes Agent 的技能、工具、集成与社区资源。
- [Hermes Agent 中文站](https://github.com/zcweah1981/awesome-hermes-agent-zh) —— 实战型中文入口，覆盖上手路径、国内部署、OpenClaw 共存迁移、排障参考与可下载方案包。

### 视频

- [Hermes Agent Skills Tutorial](https://www.youtube.com/watch?v=cyn2JPlvTG4) —— 聚焦自定义 Skills 的使用方式与编写思路。
- [Hermes Agent Dashboard (Setup Guide and Overview)](https://www.youtube.com/watch?v=GfQEdMZ9LlA) —— 面向运维与重度用户的本地 Web Dashboard 上手视频。
- [Hermes Agent Setup: Install, Configure, and Run It 100% Free](https://www.youtube.com/watch?v=9v1DyzP7-58)
- [I am Switching to Hermes Agent](https://www.youtube.com/watch?v=J-kSdzHr9Ek)
- [Hermes AI Agent Explained: Persistent AI That Runs 24/7](https://www.youtube.com/watch?v=ZhCIZ-ZTcyE)
- [Hermes Agent: Zero to Personal AI Assistant（1 小时教程）](https://www.youtube.com/watch?v=gb5TlGw6Uks) —— 从零开始在 VPS 上部署 Hermes，覆盖安装、配置、技能设置和网关连接。
- [FULL Hermes Agent Tutorial For Beginners in 2026](https://www.youtube.com/watch?v=4ftONmdO9yo) —— 面向初学者的 Hermes 教程，涵盖设置、Telegram 集成和实用模式。

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
