---
tags:
  - github-trending
  - daily
date: 2026-02-18
created: 2026-02-18T01:55:46.252Z
---

# 2026-02-18 GitHub Trending Top 10

## 1. [p-e-w/heretic](https://github.com/p-e-w/heretic)
- **语言**: Python
- **Stars**: 7,254
- **简介**: Fully automatic censorship removal for language models

### AI 总结
**简介**: Heretic 是一个用于自动移除语言模型“安全对齐”（即审查）的工具，无需昂贵的后训练。

**核心功能**:
- 结合先进的“方向性消融”（abliteration）技术与基于Optuna的TPE参数优化器，实现完全自动化的模型去审查。
- 通过共同最小化模型的拒绝率和与原模型的KL散度，在有效移除审查的同时，尽可能保留原模型的智能和能力。
- 提供内置的模型评估功能，用户无需深入了解Transformer内部原理即可通过命令行使用。

**技术亮点**: 基于Optuna的TPE参数优化器，结合了方向性消融（abliteration）技术，支持大多数密集模型（包括多模态模型和多种MoE架构）。

---
## 2. [seerr-team/seerr](https://github.com/seerr-team/seerr)
- **语言**: TypeScript
- **Stars**: 9,336
- **简介**: Open-source media request and discovery manager for Jellyfin, Plex, and Emby.

### AI 总结
**简介**: Seerr 是一款开源的媒体请求与管理工具，专为 Jellyfin、Plex 和 Emby 媒体服务器设计。

**核心功能**:
- 与 Jellyfin、Emby、Plex 深度集成，支持用户导入、认证和管理。
- 支持电影、剧集及混合媒体库的请求与管理。
- 与现有服务（如 Sonarr、Radarr）无缝集成，自动化媒体获取。
- 提供可定制的请求系统，用户可轻松请求单个季度或电影。
- 包含精细的权限管理系统与多种通知代理支持。
- 支持媒体库扫描，自动追踪已可用的内容。
- 拥有移动端友好的设计，便于随时随地处理请求。

**技术亮点**: 基于 TypeScript 开发，支持 PostgreSQL 和 SQLite 数据库，提供完整的 API 文档，并可通过 Docker 快速部署。

---
## 3. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 53,636
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为 AI 编码智能体构建的、基于可组合“技能”的软件开发工作流框架。

**核心功能**:
- **智能设计引导**：通过对话提炼需求，分块呈现设计方案供用户确认。
- **结构化实施**：在确认设计后，生成详细到可由初级工程师遵循的、强调 TDD、YAGNI 和 DRY 原则的实施计划。
- **子智能体驱动开发**：启动子智能体按计划执行工程任务，并自动进行审查，支持长时间自主工作。
- **自动化技能触发**：内置涵盖设计、测试、调试、协作等环节的多种技能库，在任务前自动检查并触发相关技能。

**技术亮点**: 基于 Shell 脚本实现，通过插件市场（Claude Code, Cursor）或指令方式（Codex, OpenCode）与主流 AI 编码工具集成，强制实施一套规范化的开发流程。

---
## 4. [steipete/gogcli](https://github.com/steipete/gogcli)
- **语言**: Go
- **Stars**: 3,876
- **简介**: Google Suite CLI: Gmail, GCal, GDrive, GContacts.

### AI 总结
**简介**: gogcli 是一个用 Go 语言编写的、面向脚本和自动化的命令行工具，用于在终端中高效管理 Google Workspace 套件（如 Gmail、日历、云端硬盘、联系人等）的各项服务。

**核心功能**:
- **多服务集成**: 支持 Gmail、Calendar、Drive、Contacts、Tasks、Sheets、Docs、Slides、Forms、Apps Script、Chat、Classroom、Keep、Groups 等十多项 Google 服务的查询与管理。
- **脚本友好**: 提供 JSON 优先的输出格式，便于与其他工具集成和自动化处理。
- **多账户与安全认证**: 支持同时管理多个 Google 账户，使用操作系统密钥环或加密文件安全存储凭证，并内置最小权限认证和自动令牌刷新机制。

**技术亮点**:
- **Go 语言开发**: 保证了工具的跨平台性和执行效率。
- **灵活的安装方式**: 支持通过 Homebrew、Arch User Repository 或从源码构建。
- **完善的权限控制**: 提供 `--readonly` 等选项进行只读操作，并支持 Google Workspace 服务账户的域范围授权。

---
## 5. [alibaba/zvec](https://github.com/alibaba/zvec)
- **语言**: C++
- **Stars**: 4,504
- **简介**: A lightweight, lightning-fast, in-process vector database

### AI 总结
**简介**: Zvec 是阿里巴巴开源的一个轻量级、极速的进程内向量数据库，旨在直接嵌入到应用程序中。

**核心功能**:
- **极速向量检索**: 可在毫秒级时间内搜索数十亿向量。
- **简单易用**: 无需服务器，安装即可使用，支持 Python 和 Node.js。
- **支持混合向量**: 同时支持稠密向量和稀疏向量，并原生支持单次调用中的多向量查询。
- **混合搜索**: 可将语义相似性与结构化过滤器结合，以获得精确结果。
- **跨平台运行**: 作为进程内库，可在笔记本、服务器、CLI工具甚至边缘设备上运行。

**技术亮点**:
- 基于阿里巴巴内部久经考验的向量搜索引擎 **Proxima** 构建。
- 提供生产级、低延迟、可扩展的相似性搜索能力。

---
## 6. [openclaw/openclaw](https://github.com/openclaw/openclaw)
- **语言**: TypeScript
- **Stars**: 205,512
- **简介**: Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞

### AI 总结
**简介**: OpenClaw 是一个可部署在个人设备上的私有化 AI 助手，支持跨多种主流通讯平台和操作系统。

**核心功能**:
- 支持通过 WhatsApp、Telegram、Slack、Discord、Google Chat、Signal、iMessage、Microsoft Teams、WebChat 等众多渠道与助手交互。
- 支持语音交互（macOS/iOS/Android）和实时 Canvas 渲染控制。
- 提供命令行向导（`openclaw onboard`）引导完成网关、工作区、通道和技能的设置。

**技术亮点**:
- 基于 TypeScript 开发，支持 npm、pnpm 或 bun 包管理器。
- 运行时要求 Node.js ≥22，推荐通过系统服务（launchd/systemd）常驻运行。
- 支持 Anthropic (Claude) 和 OpenAI 等模型，并具备模型故障转移和认证配置轮换功能。

---
## 7. [SynkraAI/aios-core](https://github.com/SynkraAI/aios-core)
- **语言**: JavaScript
- **Stars**: 1,207
- **简介**: Synkra AIOS: AI-Orchestrated System for Full Stack Development - Core Framework v4.0

### AI 总结
**简介**: Synkra AIOS 是一个由人工智能驱动的、可自我修改的通用 AI 代理框架，旨在通过“代理驱动开发”革新全栈开发及其他领域。

**核心功能**:
- **代理驱动开发**: 提供基于 AI 代理的开发范式，支持软件、娱乐、创意写作、商业策略等多个领域。
- **快速启动**: 提供 10 分钟快速入门指南，通过简单的安装和激活步骤，帮助用户快速验证框架价值。
- **多 IDE/CLI 兼容**: 支持 Claude Code、Gemini CLI、Codex CLI、Cursor、GitHub Copilot 等多种开发环境，并详细说明了各平台对生命周期钩子（hooks）的支持差异。
- **CLI 优先架构**: 明确采用“CLI 优先 -> 可观测性其次 -> UI 最后”的架构优先级，核心智能和执行均发生在 CLI 层。

**技术亮点**:
- **基于 Node.js**: 要求 Node.js 版本 >= 18.0.0。
- **工程化完善**: 项目配备完整的 CI/CD 流程、代码覆盖率报告（codecov）和详细的集成文档。
- **演进与传承**: 项目最初衍生自 BMad Method，但现已发展出独立的 v4.x+ 架构、术语和功能体系。

---
## 8. [ashishps1/awesome-system-design-resources](https://github.com/ashishps1/awesome-system-design-resources)
- **语言**: Java
- **Stars**: 32,832
- **简介**: Learn System Design concepts and prepare for interviews using free resources.

### AI 总结
**简介**: 一个专注于系统设计学习和面试准备的免费资源集合库，涵盖了从核心概念到分布式系统的全面知识。

**核心功能**:
- 提供系统设计核心概念的学习资源，如可扩展性、可用性、CAP定理等。
- 整理了网络、API、数据库、缓存、异步通信及分布式系统等关键领域的基础知识。
- 包含大量指向外部博客、文章和教程的链接，用于深入学习。

**技术亮点**: 内容结构清晰，按技术领域分门别类，是面向开发者和面试者的结构化学习路径指南。

---
## 9. [steipete/summarize](https://github.com/steipete/summarize)
- **语言**: TypeScript
- **Stars**: 3,453
- **简介**: Point at any URL/YouTube/Podcast or file. Get the gist. CLI and Chrome Extension.

### AI 总结
**简介**: 一个支持通过命令行和浏览器扩展，快速对网页、文件、YouTube视频、播客等多种内容进行智能摘要的工具。

**核心功能**:
- 支持多种输入源：网页URL、本地文件、PDF、图片、音频/视频、YouTube、播客和RSS。
- 提供浏览器侧边栏扩展（Chrome/Firefox）和命令行界面（CLI）两种使用方式。
- 针对视频内容（如YouTube）可提取带时间戳的幻灯片截图，并支持OCR识别和字幕切换。
- 支持多种AI模型：本地OpenAI兼容端点、付费提供商以及免费的OpenRouter预设。
- 提供多种输出模式：Markdown/纯文本、JSON诊断信息、仅提取内容、性能指标和成本估算。

**技术亮点**:
- 采用客户端-服务端架构：浏览器扩展与本地后台守护进程通信，以处理繁重的媒体提取任务（使用yt-dlp, ffmpeg, OCR, 语音转录）。
- 支持流式Markdown输出，响应迅速。
- 具备智能默认行为：若内容短于请求长度则直接返回原文。
- 跨平台支持，可通过npm、Homebrew（macOS）或npx快速安装。

---
## 10. [hummingbot/hummingbot](https://github.com/hummingbot/hummingbot)
- **语言**: Python
- **Stars**: 17,056
- **简介**: Open source software that helps you create and deploy high-frequency crypto trading bots

### AI 总结
**简介**: Hummingbot 是一个开源的 Python 框架，用于设计和部署可在众多中心化或去中心化交易所运行的高频加密货币交易机器人。

**核心功能**:
- 提供标准化连接器，支持与超过 140 个交易场所进行交互。
- 支持部署自动化交易策略，用户累计交易量已超过 340 亿美元。
- 提供 Gateway DEX 中间件，便于与不同区块链网络的去中心化交易所（DEX）进行交互。

**技术亮点**: 项目采用 Apache 2.0 开源协议，核心使用 Docker 进行容器化部署，并支持通过 Docker Compose 快速启动。其架构设计允许开发者轻松构建和扩展新的交易所连接器与交易策略。

---
