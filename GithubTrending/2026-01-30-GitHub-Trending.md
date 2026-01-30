---
tags:
  - github-trending
  - daily
date: 2026-01-30
created: 2026-01-30T05:50:13.175Z
---

# 2026-01-30 GitHub Trending Top 10

> [!INFO]
> 本日报由 AI 自动生成，精选 GitHub Trending 前 10 项目。

## 1. [openclaw/openclaw](https://github.com/openclaw/openclaw)
- **语言**: TypeScript
- **Stars**: 107,001
- **简介**: Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞

### AI 总结
**简介**: OpenClaw 是一个可在个人设备上部署的、跨平台和跨通信渠道的个人AI助手。

**核心功能**:
- 支持通过多种主流即时通讯渠道（如 WhatsApp、Telegram、Slack、Discord、Signal、iMessage、Microsoft Teams 等）与助手交互。
- 支持语音交互（macOS/iOS/Android）和实时画布渲染。
- 通过向导式 CLI 工具 (`openclaw onboard`) 简化网关、工作区、渠道和技能的配置与部署。
- 支持 Anthropic (Claude) 和 OpenAI 等主流 AI 模型，并推荐使用 Anthropic Pro/Max 以获得更好的长上下文处理和抗提示注入能力。

**技术亮点**:
- 使用 TypeScript 开发。
- 支持通过 npm、pnpm 或 bun 安装，要求 Node.js ≥ 22 运行时。
- 提供稳定版 (stable)、测试版 (beta) 和开发版 (dev) 多个发布渠道。
- 支持以系统服务（launchd/systemd）形式安装守护进程，实现常驻运行。

---
## 2. [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)
- **语言**: JavaScript
- **Stars**: 27,909
- **简介**: Collection of extracted System Prompts from popular chatbots like ChatGPT, Claude & Gemini

### AI 总结
**简介**: 一个收集并公开主流聊天机器人（如 ChatGPT、Claude、Gemini）系统提示词（System Prompts）的仓库。

**核心功能**:
- 集中收集和整理来自多个流行AI聊天机器人的系统提示词/系统消息。
- 鼓励社区通过提交 Pull Request 来共同维护和更新这个提示词集合。

**技术亮点**: 项目本身主要是一个信息集合，使用 JavaScript 语言，并通过徽章和 star 历史图表来展示项目流行度。

---
## 3. [MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli)
- **语言**: Python
- **Stars**: 5,058
- **简介**: Kimi Code CLI is your next CLI agent.

### AI 总结
**简介**: Kimi Code CLI 是一个运行在终端中的 AI 代理，旨在辅助完成软件开发任务和终端操作。

**核心功能**:
- **Shell 命令模式**：可在 CLI 内直接切换并执行 Shell 命令。
- **IDE 集成**：通过 Agent Client Protocol 协议，可与 Zed、JetBrains 等兼容 ACP 的编辑器或 IDE 无缝集成。
- **Zsh 集成**：提供官方插件，可在 Zsh 中启用 AI 代理能力。
- **MCP 支持**：支持 Model Context Protocol 工具，可管理多种 MCP 服务器（如 HTTP、Stdio 传输方式），并支持通过配置文件或命令行选项进行配置。

**技术亮点**: 基于 Python 开发，支持 ACP 和 MCP 协议，具备良好的扩展性和与开发生态的集成能力。

---
## 4. [modelcontextprotocol/ext-apps](https://github.com/modelcontextprotocol/ext-apps)
- **语言**: TypeScript
- **Stars**: 896
- **简介**: Official repo for spec & SDK of MCP Apps protocol - standard for UIs embedded AI chatbots, served by MCP servers

### AI 总结
**简介**: 这是一个为 MCP Apps 协议提供官方规范与 SDK 的 TypeScript 项目，旨在为嵌入 AI 聊天机器人的 UI 界面建立标准化交互方式。

**核心功能**:
- 提供 **MCP Apps 规范**，允许 MCP 服务器在对话式客户端中声明和提供交互式 UI 资源（如图表、表单）。
- 提供 **SDK for App 开发者**，用于构建在 MCP 客户端内运行的交互式 UI。
- 提供 **SDK for Host 开发者**，用于在聊天应用中嵌入并与 MCP Apps 通信。

**技术亮点**: 基于 Model Context Protocol 扩展，通过 `ui://` 资源声明、沙盒化 iframe 渲染以及双向通知机制实现服务器与 UI 的安全交互。

---
## 5. [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU)
- **语言**: Python
- **Stars**: 6,158
- **简介**: Memory for 24/7 proactive agents like openclaw (moltbot, clawdbot).

### AI 总结
**简介**: memU 是一个专为 24/7 全天候主动式 AI 智能体设计的内存框架，旨在通过持续捕获和理解用户意图，降低长期运行成本，使智能体能够自主、主动地行动。

**核心功能**:
- **24/7 主动式智能体**: 提供永不睡眠、永不遗忘的持续后台运行内存。
- **用户意图捕获**: 自动理解和记忆用户的目标、偏好及跨会话的上下文。
- **成本高效**: 通过缓存洞察和避免冗余的 LLM 调用，显著降低长期运行的令牌成本。

**技术亮点**: 采用 Python 3.13+ 开发，通过独立的“记忆机器人”模块监控主智能体的交互，实现记忆的提取、存储和主动注入，从而构建长期记忆并减少上下文长度。

---
## 6. [hashicorp/vault](https://github.com/hashicorp/vault)
- **语言**: Go
- **Stars**: 34,664
- **简介**: A tool for secrets management, encryption as a service, and privileged access management

### AI 总结
**简介**: Vault 是一个用于安全访问和管理机密信息（如 API 密钥、密码、证书等）的工具，提供统一的访问接口、严格的访问控制和详细的审计日志。

**核心功能**:
- **安全机密存储**：加密存储任意键值对数据，支持写入磁盘、Consul 等多种后端。
- **动态机密生成**：按需为 AWS、SQL 数据库等系统生成临时凭证，并在租约到期后自动撤销。
- **数据加密服务**：无需存储数据即可提供加密和解密功能，便于开发和安全团队协作。
- **租约与续期**：为每个机密关联租约，支持自动撤销和通过 API 续期。
- **机密撤销**：支持撤销单个机密或按用户、类型等批量撤销，便于密钥轮换和入侵响应。

**技术亮点**: 使用 Go 语言开发，提供企业版（Vault Enterprise），支持与 Consul 等系统集成，具备完善的自动化测试和持续集成流程。

---
## 7. [badlogic/pi-mono](https://github.com/badlogic/pi-mono)
- **语言**: TypeScript
- **Stars**: 3,522
- **简介**: AI agent toolkit: coding agent CLI, unified LLM API, TUI & web UI libraries, Slack bot, vLLM pods

### AI 总结
**简介**: Pi Monorepo 是一个用于构建 AI 智能体和管理大语言模型部署的 TypeScript 工具集。

**核心功能**:
- **统一 LLM API**: 提供支持 OpenAI、Anthropic、Google 等多供应商的统一接口。
- **智能体运行时**: 包含工具调用和状态管理的智能体运行核心。
- **交互式编码助手**: 提供命令行界面的交互式编码智能体。
- **多样化部署与集成**: 包含 Slack 机器人、终端 UI 库、Web UI 组件以及用于管理 GPU Pod 上 vLLM 部署的 CLI。

**技术亮点**: 采用 Monorepo 架构，包含多个独立且功能聚焦的 NPM 包，便于按需集成和使用。

---
## 8. [anomalyco/opencode-anthropic-auth](https://github.com/anomalyco/opencode-anthropic-auth)
- **语言**: JavaScript
- **Stars**: 280
- **简介**: 

### AI 总结
**简介**: 一个用于在浏览器环境中安全调用 Anthropic Claude API 的轻量级身份验证库。

**核心功能**:
- 提供 `AnthropicAuth` 类，用于在浏览器中安全地管理 Anthropic API 密钥。
- 通过 `getAuthHeader` 方法生成符合 Anthropic API 要求的 HTTP 认证头。

**技术亮点**: 专为浏览器环境设计，代码简洁，直接处理 API 密钥的存储和请求头的格式化。

---
## 9. [protocolbuffers/protobuf](https://github.com/protocolbuffers/protobuf)
- **语言**: C++
- **Stars**: 70,531
- **简介**: Protocol Buffers - Google's data interchange format

### AI 总结
**简介**: Protocol Buffers (protobuf) 是 Google 开发的一种语言中立、平台中立、可扩展的结构化数据序列化机制。

**核心功能**:
- 提供协议编译器，用于将 `.proto` 文件编译成各种编程语言的代码。
- 提供多种编程语言（如 C++、Java、Python、Go 等）的运行时库，用于数据的序列化与反序列化。

**技术亮点**: 支持通过 Bazel（含 Bzlmod 和 WORKSPACE 两种方式）进行依赖管理和构建；提供预编译的编译器二进制文件以简化安装；其源代码管理强调稳定性，建议用户使用官方发布版本而非直接使用主分支。

---
## 10. [pedroslopez/whatsapp-web.js](https://github.com/pedroslopez/whatsapp-web.js)
- **语言**: JavaScript
- **Stars**: 20,743
- **简介**: A WhatsApp client library for NodeJS that connects through the WhatsApp Web browser app

### AI 总结
**简介**: 一个基于 Node.js 的 WhatsApp 客户端库，通过 WhatsApp Web 浏览器应用进行连接，允许开发者构建自动化聊天机器人或集成工具。

**核心功能**:
- 通过 Puppeteer 启动并管理 WhatsApp Web 实例，模拟用户操作。
- 支持发送和接收消息、媒体（图片、音频、视频、文档）、联系人卡片、位置等。
- 支持群组管理（邀请成员、修改信息、踢人、晋升/降级成员等）。
- 支持多设备登录、消息回复、用户提及、设置状态、消息反应、创建投票等功能。
- 提供会话认证策略，支持保存和恢复登录状态。

**技术亮点**:
- 使用 Puppeteer 控制无头浏览器，直接调用 WhatsApp Web 内部 API，功能覆盖广泛。
- 基于 Node.js，要求 Node v18 或更高版本，易于集成到现有 JavaScript/Node.js 项目中。
- 社区活跃，提供详细的指南、文档和 Discord 支持。

---
