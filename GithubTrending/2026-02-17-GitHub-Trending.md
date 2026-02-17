---
tags:
  - github-trending
  - daily
date: 2026-02-17
created: 2026-02-17T01:55:45.396Z
---

# 2026-02-17 GitHub Trending Top 10

## 1. [alibaba/zvec](https://github.com/alibaba/zvec)
- **语言**: C++
- **Stars**: 3,645
- **简介**: A lightweight, lightning-fast, in-process vector database

### AI 总结
**简介**: Zvec 是阿里巴巴开源的一个轻量级、超高速的进程内向量数据库，旨在直接嵌入到应用程序中，提供低延迟、可扩展的相似性搜索。

**核心功能**:
- **超高速搜索**: 可在毫秒级时间内搜索数十亿向量。
- **简单易用**: 无需服务器，安装即可使用，支持 Python 和 Node.js。
- **支持多种向量**: 同时支持稠密向量和稀疏向量，并原生支持单次调用中的多向量查询。
- **混合搜索**: 可将语义相似性与结构化过滤器结合，以获得精确结果。
- **随处运行**: 作为进程内库，可在笔记本、服务器、CLI工具甚至边缘设备上运行。

**技术亮点**: 基于阿里巴巴经过实战检验的向量搜索引擎 **Proxima** 构建，提供生产级性能。支持 Linux (x86_64, ARM64) 和 macOS (ARM64) 平台。

---
## 2. [nautechsystems/nautilus_trader](https://github.com/nautechsystems/nautilus_trader)
- **语言**: Rust
- **Stars**: 19,791
- **简介**: A high-performance algorithmic trading platform and event-driven backtester

### AI 总结
**简介**: NautilusTrader 是一个开源、高性能、生产级的算法交易平台，支持事件驱动的回测和实盘交易部署，无需代码更改。

**核心功能**:
- 提供高性能的事件驱动引擎，用于投资组合级别的自动化交易策略回测。
- 支持将同一策略无缝部署到实盘交易环境，实现研究/回测与生产环境的一致性。
- 支持多资产类别（如外汇、股票、期货、期权、加密货币、DeFi 和博彩）和高频交易。
- 通过模块化适配器，可集成任何 REST API 或 WebSocket 数据源。

**技术亮点**:
- 核心采用 Rust 编写，利用 Tokio 进行异步网络处理，确保高性能与可靠性。
- 提供 Python 原生环境，便于量化交易者进行策略开发和部署。
- 强调软件正确性和安全性，支持任务关键型的回测和实盘交易工作负载。

---
## 3. [rowboatlabs/rowboat](https://github.com/rowboatlabs/rowboat)
- **语言**: TypeScript
- **Stars**: 7,335
- **简介**: Open-source AI coworker, with memory

### AI 总结
**简介**: Rowboat 是一个开源的、具备记忆功能的本地优先 AI 协作者，它能将您的工作转化为知识图谱并据此行动。

**核心功能**:
- **构建长期知识图谱**：连接您的电子邮件和会议笔记，在本地构建并维护一个可持久化、可编辑的 Markdown 知识图谱。
- **基于上下文的智能辅助**：利用知识图谱中的上下文，帮助您完成会议准备、邮件草拟、文档生成（如 PDF 幻灯片）等工作。
- **支持语音备忘录**：录制语音备忘录，自动提取关键信息并更新到知识图谱中。
- **运行后台智能体**：可启动后台智能体，自动处理重复性任务（如草拟邮件回复）。

**技术亮点**:
- **本地优先与隐私**：所有数据默认存储在本地，确保隐私。
- **透明可编辑的记忆**：使用与 Obsidian 兼容的纯 Markdown 笔记和反向链接作为“工作记忆”，用户可随时查看和编辑。
- **TypeScript 开发**：项目使用 TypeScript 编写。
- **灵活的集成与扩展**：支持集成 Gmail、Granola、Fireflies 等服务，并可配置 Deepgram、Brave Search、Exa 等第三方 API 以增强功能。

---
## 4. [steipete/gogcli](https://github.com/steipete/gogcli)
- **语言**: Go
- **Stars**: 3,517
- **简介**: Google Suite CLI: Gmail, GCal, GDrive, GContacts.

### AI 总结
**简介**: gogcli 是一个用 Go 语言编写的、面向脚本和自动化的命令行工具，用于在终端中快速、便捷地管理 Google Workspace 套件中的多项服务（如 Gmail、日历、云端硬盘等）。

**核心功能**:
- **多服务集成**: 支持通过命令行操作 Gmail、日历、Chat、Classroom、云端硬盘、文档、幻灯片、表格、表单、Apps Script、联系人、任务、People、群组和 Keep 笔记。
- **脚本友好**: 提供 JSON 优先的输出模式，便于与其他工具集成和自动化处理。
- **多账户与安全**: 支持同时管理多个 Google 账户，并使用操作系统密钥环或加密的磁盘密钥环安全存储凭证，支持自动刷新令牌和最小权限认证。

**技术亮点**:
- **Go 语言开发**: 保证了高性能和跨平台兼容性。
- **灵活的认证体系**: 内置最小权限认证（`--readonly`）、支持 Google Workspace 服务账户和域范围授权。
- **模块化设计**: 提供命令允许列表功能，便于在沙箱或代理环境中限制可用命令。

---
## 5. [openclaw/openclaw](https://github.com/openclaw/openclaw)
- **语言**: TypeScript
- **Stars**: 201,786
- **简介**: Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞

### AI 总结
**简介**: OpenClaw 是一个可部署在个人设备上的私有化 AI 助手，支持跨多种主流通讯平台和操作系统。

**核心功能**:
- 支持通过 WhatsApp、Telegram、Slack、Discord、Google Chat、Signal、iMessage、Microsoft Teams、WebChat 等多种渠道与助手交互。
- 支持语音交互（macOS/iOS/Android）和实时画布渲染。
- 提供命令行向导 (`openclaw onboard`) 引导完成网关、工作区、通道和技能的设置。

**技术亮点**:
- 使用 TypeScript 开发，运行时要求 Node.js ≥22。
- 支持通过 npm、pnpm 或 bun 安装。
- 主要推荐集成 Anthropic (Claude) 和 OpenAI 的模型，并支持模型故障转移和 OAuth 认证。

---
## 6. [SynkraAI/aios-core](https://github.com/SynkraAI/aios-core)
- **语言**: JavaScript
- **Stars**: 997
- **简介**: Synkra AIOS: AI-Orchestrated System for Full Stack Development - Core Framework v4.0

### AI 总结
**简介**: Synkra AIOS 是一个由 AI 驱动的、可自我修改的通用 AI 代理框架，旨在通过“代理驱动开发”革新全栈开发及其他领域。

**核心功能**:
- **快速启动**: 提供 10 分钟快速入门指南，通过简单的安装和激活步骤，帮助用户快速验证框架价值。
- **多 IDE/CLI 兼容**: 支持 Claude Code、Gemini CLI、Codex CLI、Cursor、GitHub Copilot 等多种开发环境，并详细说明了不同环境下的生命周期钩子支持度。
- **代理驱动开发**: 内置多种 AI 代理（如 `@dev`, `@qa`），可自动化执行任务、决策和开发流程。

**技术亮点**:
- **CLI 优先架构**: 明确采用“CLI 优先 → 可观测性其次 → UI 最后”的设计哲学，核心智能和执行均基于命令行。
- **生命周期钩子**: 提供高级自动化能力，其支持程度因 IDE 而异，是实现上下文自动化、护栏和审计的关键。
- **演进与独立**: 项目最初源自 BMad Method，但现已发展为具有独立架构和特性的 v4.x+ 版本。

---
## 7. [letta-ai/letta-code](https://github.com/letta-ai/letta-code)
- **语言**: TypeScript
- **Stars**: 1,460
- **简介**: The memory-first coding agent

### AI 总结
**简介**: Letta Code 是一个基于 Letta API 构建的、以“记忆优先”为核心理念的持久化编程助手。

**核心功能**:
- **持久化智能体**：与传统的独立会话模式不同，它使用一个跨会话持久存在的智能体，能够随着使用不断学习和积累记忆。
- **多模型支持**：可灵活切换并连接多种大语言模型，如 Claude、GPT、Gemini、GLM 等，支持使用自有 API 密钥。
- **记忆与技能系统**：通过 `/init`、`/remember` 等命令管理智能体的长期记忆，并支持通过 `.skills` 目录和 `/skill` 命令让智能体学习和复用技能模块。

**技术亮点**: 基于 TypeScript 开发，采用智能体优先的架构设计，支持通过 Docker 自托管，并提供了 npm 和 AUR 等多种安装方式。

---
## 8. [ruvnet/wifi-densepose](https://github.com/ruvnet/wifi-densepose)
- **语言**: Python
- **Stars**: 6,809
- **简介**: Production-ready implementation of InvisPose - a revolutionary WiFi-based dense human pose estimation system that enables real-time full-body tracking through walls using commodity mesh routers

### AI 总结
**简介**: 一个基于WiFi信号（CSI）实现实时、无摄像头、隐私保护的人体姿态估计系统，支持穿墙追踪和多目标检测。

**核心功能**:
- **隐私优先**：利用WiFi信号而非摄像头进行姿态检测。
- **实时处理**：延迟低于50毫秒，姿态估计可达30 FPS。
- **多目标追踪**：可同时追踪多达10人。
- **应用场景广泛**：适用于医疗保健、健身、智能家居、安防及灾难救援（WiFi-Mat模块）。
- **企业级API**：提供生产就绪的API，包含认证、限流和监控功能。
- **硬件无关**：兼容标准WiFi路由器和接入点。
- **高性能Rust实现**：提供Rust版本，性能相比Python版本提升数百至数千倍。

**技术亮点**:
- **技术栈**：主要基于Python（FastAPI），并提供高性能的Rust实现。
- **架构特点**：包含完整的信号处理管道（CSI预处理、相位净化、特征提取），支持WebSocket实时流传输，并拥有100%的测试覆盖率。
- **灾难响应模块**：专门的WiFi-Mat模块，用于搜救场景，可检测生命体征、进行3D定位和伤员分类。

---
## 9. [seerr-team/seerr](https://github.com/seerr-team/seerr)
- **语言**: TypeScript
- **Stars**: 9,081
- **简介**: Open-source media request and discovery manager for Jellyfin, Plex, and Emby.

### AI 总结
**简介**: Seerr 是一款为 Jellyfin、Plex 和 Emby 设计的开源媒体请求与发现管理工具。

**核心功能**:
- 与 Jellyfin、Emby、Plex 深度集成，支持用户导入、认证和管理。
- 支持电影、剧集及混合媒体库的请求与管理。
- 与现有服务（如 Sonarr、Radarr）轻松集成，实现自动化。
- 提供可定制的请求系统，用户可通过友好界面请求特定季或电影。
- 简洁直观的请求管理界面和精细的权限系统。
- 支持多种通知代理和移动端友好设计。
- 支持媒体关注列表和屏蔽列表功能。

**技术亮点**: 基于 TypeScript 开发，支持 PostgreSQL 和 SQLite 数据库，提供完整的 API 文档，并可通过 Docker 部署。

---
## 10. [hummingbot/hummingbot](https://github.com/hummingbot/hummingbot)
- **语言**: Python
- **Stars**: 16,579
- **简介**: Open source software that helps you create and deploy high-frequency crypto trading bots

### AI 总结
**简介**: Hummingbot 是一个开源的 Python 框架，用于帮助用户设计和部署可在众多中心化或去中心化交易所运行的高频加密货币交易机器人。

**核心功能**:
- 提供标准化的交易所连接器，支持在超过 140 个交易场所构建和部署自动化交易策略。
- 支持与去中心化交易所交互的 Gateway DEX 中间件。
- 提供多种安装方式，最便捷的是通过 Docker 和 Docker Compose 进行部署。

**技术亮点**: 基于 Apache 2.0 开源协议，采用模块化架构，将策略逻辑与交易所 API 连接分离，便于策略跨平台复用和扩展。

---
