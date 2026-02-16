---
tags:
  - github-trending
  - daily
date: 2026-02-16
created: 2026-02-16T01:55:44.952Z
---

# 2026-02-16 GitHub Trending Top 10

## 1. [nautechsystems/nautilus_trader](https://github.com/nautechsystems/nautilus_trader)
- **语言**: Rust
- **Stars**: 19,323
- **简介**: A high-performance algorithmic trading platform and event-driven backtester

### AI 总结
**简介**: NautilusTrader 是一个开源、高性能、生产级的算法交易平台和事件驱动回测引擎，支持用户使用同一套代码进行历史回测和实盘交易。

**核心功能**:
- 提供事件驱动引擎，用于自动化交易策略的投资组合回测和实盘部署。
- 支持多种资产类别，包括外汇、股票、期货、期权、加密货币、DeFi和博彩。
- 通过模块化适配器，可集成任何 REST API 或 WebSocket 数据源，实现多交易场所同时操作。

**技术亮点**:
- 核心采用 Rust 编写，结合 Tokio 进行异步网络处理，确保高性能与可靠性。
- 提供“AI优先”的 Python 原生环境，保持研究/回测环境与生产环境的一致性。
- 强调软件正确性与安全性，支持任务关键型交易系统的回测和实盘部署。

---
## 2. [steipete/gogcli](https://github.com/steipete/gogcli)
- **语言**: Go
- **Stars**: 2,998
- **简介**: Google Suite CLI: Gmail, GCal, GDrive, GContacts.

### AI 总结
**简介**: 一个用 Go 语言编写的、面向脚本和自动化的 Google Workspace 命令行工具，支持 Gmail、日历、云端硬盘、联系人、任务等多项服务。

**核心功能**:
- 支持管理 Gmail、日历、Chat、Classroom、云端硬盘、联系人、任务、表格、表单、Apps Script、文档、幻灯片、Keep 笔记、群组等 Google 服务。
- 提供 JSON 优先的输出格式，便于脚本解析和自动化。
- 支持管理多个 Google 账户，并内置最小权限认证和自动刷新令牌机制。

**技术亮点**:
- 使用操作系统密钥环或加密的磁盘密钥环安全存储凭据。
- 支持 Google Workspace 服务账户和域范围委派认证。
- 提供命令允许列表功能，可用于沙盒或代理运行环境。

---
## 3. [rowboatlabs/rowboat](https://github.com/rowboatlabs/rowboat)
- **语言**: TypeScript
- **Stars**: 6,828
- **简介**: Open-source AI coworker, with memory

### AI 总结
**简介**: Rowboat 是一个开源的、具备长期记忆功能的本地优先 AI 协作者，能将您的工作信息转化为知识图谱并据此行动。

**核心功能**:
- **构建并维护知识图谱**：连接您的电子邮件和会议笔记，构建并持续更新一个可长期保存、可编辑的 Obsidian 兼容知识图谱（基于 Markdown）。
- **基于上下文的智能辅助**：利用知识图谱中的历史信息，自动生成会议简报、起草邮件、创建文档和演示文稿（如 PDF 幻灯片）。
- **支持语音备忘录**：录制语音笔记，自动提取关键信息并更新到知识图谱中。
- **后台智能体**：可运行后台智能体自动处理重复性任务，如草拟邮件回复、生成每日语音摘要等。

**技术亮点**:
- **本地优先与隐私**：所有数据和处理均在本地机器上进行，确保隐私。
- **透明可编辑的记忆系统**：知识图谱以纯文本 Markdown 文件存储，用户可直接查看和编辑，而非隐藏于黑盒模型中。
- **TypeScript 开发**：项目使用 TypeScript 编写。
- **集成扩展**：支持与 Gmail、Granola、Fireflies 等服务集成以获取数据。

---
## 4. [github/gh-aw](https://github.com/github/gh-aw)
- **语言**: Go
- **Stars**: 2,723
- **简介**: GitHub Agentic Workflows

### AI 总结
**简介**: GitHub Agentic Workflows 是一个允许开发者使用自然语言 Markdown 编写，并在 GitHub Actions 中运行的智能代理工作流工具。

**核心功能**:
- 使用自然语言 Markdown 编写工作流，降低自动化门槛。
- 在 GitHub Actions 环境中安全地运行 AI 代理，实现仓库任务的自动化。

**技术亮点**:
- **安全性优先架构**: 默认以只读权限运行，通过 `safe-outputs` 机制控制写入操作，并集成了沙箱执行、输入净化、网络隔离、供应链安全（SHA 固定依赖）、工具白名单和编译时验证等多层防护。
- **访问控制**: 支持将访问权限限制为团队成员，并为关键操作设置人工审批关卡。
- **配套安全项目**: 包含用于网络出口控制的 Agent Workflow Firewall (AWF) 和用于集中访问管理的 MCP Gateway。

---
## 5. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)
- **语言**: TypeScript
- **Stars**: 25,437
- **简介**: Chrome DevTools for coding agents

### AI 总结
**简介**: Chrome DevTools MCP 是一个基于 Model-Context-Protocol (MCP) 的服务器，能让 AI 编程助手（如 Claude、Cursor）连接并控制真实的 Chrome 浏览器，实现自动化、调试和性能分析。

**核心功能**:
- **性能洞察**: 利用 Chrome DevTools 记录性能追踪数据，并提供可操作的性能分析建议。
- **高级浏览器调试**: 分析网络请求、截取屏幕截图、检查浏览器控制台消息（支持源映射堆栈跟踪）。
- **可靠自动化**: 基于 Puppeteer 自动化 Chrome 操作，并自动等待操作结果。

**技术亮点**:
- 作为 MCP 服务器，为 AI 助手提供标准化的浏览器控制接口。
- 底层整合了 Chrome DevTools Protocol 和 Puppeteer，实现深度浏览器交互。
- 支持通过 Google CrUX API 获取真实用户性能数据进行综合分析。

---
## 6. [alibaba/zvec](https://github.com/alibaba/zvec)
- **语言**: C++
- **Stars**: 2,361
- **简介**: A lightweight, lightning-fast, in-process vector database

### AI 总结
**简介**: Zvec 是阿里巴巴开源的一个轻量级、极速的进程内向量数据库，旨在直接嵌入应用程序中。

**核心功能**:
- **极速向量检索**：支持毫秒级搜索数十亿向量。
- **简单易用**：无需服务器，安装即可使用，支持 Python 和 Node.js。
- **混合向量支持**：同时支持稠密向量和稀疏向量，并原生支持单次调用中的多向量查询。
- **混合搜索**：可结合语义相似性和结构化过滤器进行精确检索。
- **随处运行**：作为进程内库，可在笔记本、服务器、CLI工具甚至边缘设备上运行。

**技术亮点**: 基于阿里巴巴经过实战检验的向量搜索引擎 **Proxima** 构建，提供生产级、低延迟、可扩展的相似性搜索能力。

---
## 7. [openclaw/openclaw](https://github.com/openclaw/openclaw)
- **语言**: TypeScript
- **Stars**: 197,441
- **简介**: Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞

### AI 总结
**简介**: OpenClaw 是一个可在自有设备上部署的个人AI助手，支持跨操作系统和平台，通过多种即时通讯渠道与用户交互。

**核心功能**:
- 支持通过 WhatsApp、Telegram、Slack、Discord、Google Chat、Signal、iMessage、Microsoft Teams、WebChat 等主流渠道，以及 BlueBubbles、Matrix、Zalo 等扩展渠道进行交互。
- 具备语音交互（支持 macOS/iOS/Android）和实时画布渲染能力。
- 提供引导式命令行安装向导，支持在 macOS、Linux 和 Windows（通过 WSL2）上快速部署。
- 支持 Anthropic（Claude Pro/Max）和 OpenAI（ChatGPT/Codex）等模型的 OAuth 订阅与认证。

**技术亮点**:
- 使用 TypeScript 开发，运行时要求 Node.js ≥22。
- 提供稳定版、测试版和开发版多个发布渠道，支持通过 CLI 命令切换。
- 支持通过 npm、pnpm 或 bun 进行安装和管理，并推荐使用 pnpm 进行源码构建。

---
## 8. [moonshine-ai/moonshine](https://github.com/moonshine-ai/moonshine)
- **语言**: C
- **Stars**: 3,833
- **简介**: Fast and accurate automatic speech recognition (ASR) for edge devices

### AI 总结
**简介**: Moonshine Voice 是一个专为边缘设备设计的开源、实时、高精度自动语音识别（ASR）工具包。

**核心功能**:
- **全设备端运行**: 无需网络、账户、API密钥或信用卡，保障处理速度与隐私安全。
- **低延迟流式处理**: 针对实时语音应用优化，在用户说话时即可进行转录，响应迅速。
- **开箱即用的高级API**: 提供转录、说话人识别（声纹分离）和指令识别等完整解决方案，降低开发门槛。
- **多平台与多语言支持**: 可在 Python、iOS、Android、macOS、Linux、Windows、树莓派及物联网设备上运行，支持英语、西班牙语、中文、日语、韩语等多种语言。

**技术亮点**:
- **基于前沿研究的自研模型**: 从零开始训练，在高端模型上精度超越 Whisper Large V3，同时提供小至26MB的轻量模型。
- **统一的跨平台C库**: 核心库使用C语言编写，确保了在不同硬件和操作系统上的一致性和高性能。

---
## 9. [brave/brave-browser](https://github.com/brave/brave-browser)
- **语言**: Unknown
- **Stars**: 21,550
- **简介**: Brave browser for Android, iOS, Linux, macOS, Windows.

### AI 总结
**简介**: Brave 浏览器是一个注重隐私和安全的跨平台（Android、iOS、Linux、macOS、Windows）网页浏览器。

**核心功能**:
- **隐私保护与广告拦截**: 内置基于 Rust 开发的广告拦截引擎（adblock-rust），默认阻止跟踪器和侵入性广告。
- **开源与可构建**: 提供完整的构建工具链，允许开发者从源码编译桌面版浏览器。其核心基于 Chromium，并通过 `brave-core` 仓库维护对第三方 Chromium 代码的定制和补丁。
- **多平台支持**: 项目仓库包含了为各大主流操作系统构建和开发的环境配置与指南。

**技术亮点**:
- **架构基于 Chromium**: 浏览器核心源自 Chromium 项目，确保了与 Chrome 扩展和网页标准的兼容性。
- **模块化构建系统**: 使用 npm 脚本管理复杂的构建流程（如 `init`、`sync`、`build`），可灵活配置组件构建、静态链接构建、发布构建或调试构建。
- **跨平台 Rust 组件**: 关键功能（如广告拦截）采用高性能、内存安全的 Rust 语言实现，并通过 FFI 与核心 C++ 代码集成。

---
## 10. [SynkraAI/aios-core](https://github.com/SynkraAI/aios-core)
- **语言**: JavaScript
- **Stars**: 797
- **简介**: Synkra AIOS: AI-Orchestrated System for Full Stack Development - Core Framework v4.0

### AI 总结
**简介**: Synkra AIOS 是一个由 AI 驱动的、可自我修改的 JavaScript 框架，旨在通过智能体编排实现全栈开发。

**核心功能**:
- **智能体驱动的规划与开发**: 通过专门的智能体（如分析师、产品经理、架构师）协作，生成详细且一致的 PRD 和架构文档，并由 Scrum Master 智能体将其转化为包含完整上下文的开发任务。
- **CLI 优先架构**: 强调命令行界面为系统的核心，所有执行、决策和自动化均在此发生，UI 仅为辅助管理工具。
- **IDE/平台钩子兼容性**: 提供生命周期钩子以实现高级自动化，支持与 Claude Code、Gemini CLI 等多种 IDE/CLI 工具集成，自动化程度各异。

**技术亮点**: 采用 CLI First → Observability Second → UI Third 的架构层次，确保功能完全通过 CLI 驱动；框架基于 Node.js (>=18.0.0)，并已脱离对 BMAD 的历史依赖，演进为独立的 AIOS 4.x 架构。

---
