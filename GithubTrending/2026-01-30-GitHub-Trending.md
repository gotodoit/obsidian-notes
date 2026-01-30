---
tags:
  - github-trending
  - daily
date: 2026-01-30
created: 2026-01-30T22:31:48.998Z
---

# 2026-01-30 GitHub Trending Top 10

> [!INFO]
> 本日报由 AI 自动生成，精选 GitHub Trending 前 10 项目。

## 1. [openclaw/openclaw](https://github.com/openclaw/openclaw)
- **语言**: TypeScript
- **Stars**: 118,469
- **简介**: Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞

### AI 总结
**简介**: OpenClaw 是一个可部署在个人设备上的私有化 AI 助手，支持跨多种即时通讯平台和操作系统。

**核心功能**:
- 支持在 WhatsApp、Telegram、Slack、Discord、Google Chat、Signal、iMessage、Microsoft Teams、WebChat 等主流通讯渠道以及 BlueBubbles、Matrix、Zalo 等扩展渠道上进行对话。
- 支持语音交互（macOS/iOS/Android）和实时 Canvas 渲染控制。
- 提供交互式命令行向导（`openclaw onboard`），简化网关、工作区、渠道和技能的配置流程。
- 支持 Anthropic (Claude Pro/Max) 和 OpenAI (ChatGPT/Codex) 等模型的 OAuth 订阅与认证。

**技术亮点**:
- 使用 TypeScript 开发，支持 npm、pnpm 或 bun 包管理器。
- 采用网关（Gateway）作为控制平面的架构，实现助手的本地化、快速和常驻运行。
- 支持通过系统服务（launchd/systemd）安装守护进程，确保服务持续运行。
- 提供稳定版（stable）、测试版（beta）和开发版（dev）多个发布渠道，便于用户选择和升级。

---
## 2. [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)
- **语言**: JavaScript
- **Stars**: 28,496
- **简介**: Collection of extracted System Prompts from popular chatbots like ChatGPT, Claude & Gemini

### AI 总结
**简介**: 一个收集并公开主流聊天机器人（如 ChatGPT、Claude、Gemini）系统提示词（System Prompts）的仓库。

**核心功能**:
- 收集并整理来自 ChatGPT、Claude、Gemini 等流行聊天机器人的系统提示词、系统消息或开发者消息。
- 鼓励社区通过提交 Pull Request 来共同维护和更新这个提示词集合。

**技术亮点**: 项目本身是一个信息集合，主要使用 JavaScript 语言进行相关工具或脚本的开发。

---
## 3. [MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli)
- **语言**: Python
- **Stars**: 5,268
- **简介**: Kimi Code CLI is your next CLI agent.

### AI 总结
**简介**: Kimi Code CLI 是一个运行在终端中的 AI 代理，旨在辅助完成软件开发任务和终端操作。

**核心功能**:
- **终端 Shell 模式**：可直接在 CLI 中运行 shell 命令，无需切换环境。
- **IDE 与编辑器集成**：通过 VS Code 扩展和 ACP 协议，支持与 Zed、JetBrains 等 IDE 无缝协作。
- **Zsh 集成**：提供 zsh 插件，可在 Zsh 中启用 AI 代理模式。
- **MCP 支持**：支持 Model Context Protocol 工具，可管理并连接多种 MCP 服务器以扩展能力。

**技术亮点**:
- 基于 Python 开发，支持 ACP 协议，实现与多种开发工具的互操作性。
- 提供灵活的 MCP 服务器管理，支持 HTTP、Stdio 传输及 OAuth 授权。

---
## 4. [modelcontextprotocol/ext-apps](https://github.com/modelcontextprotocol/ext-apps)
- **语言**: TypeScript
- **Stars**: 998
- **简介**: Official repo for spec & SDK of MCP Apps protocol - standard for UIs embedded AI chatbots, served by MCP servers

### AI 总结
**简介**: 这是一个为 MCP Apps 协议提供官方规范与 SDK 的 TypeScript 项目，旨在为嵌入 AI 聊天机器人的 UI 界面制定标准。

**核心功能**:
- 提供 **MCP Apps 协议规范**，允许 MCP 服务器在对话式客户端中声明和提供交互式 UI（如图表、表单、播放器）。
- 提供 **SDK 与开发库**，包含面向应用开发者的核心 SDK 和 React Hooks，以及面向主机开发者的 App Bridge SDK。
- 包含 **丰富的示例**，展示了地图、3D 场景、着色器等真实场景的交互式应用。

**技术亮点**:
- 基于 **Model Context Protocol (MCP)** 扩展，通过 `ui://` 资源声明和沙盒化 iframe 渲染实现安全、内联的 UI 嵌入。
- 支持 **双向通信**，UI 可通过主机接收工具数据并调用其他工具。
- 提供 **Agent Skills** 插件，便于在 AI 编码助手（如 Claude Code）中快速构建 MCP 应用。

---
## 5. [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU)
- **语言**: Python
- **Stars**: 6,431
- **简介**: Memory for 24/7 proactive agents like openclaw (moltbot, clawdbot).

### AI 总结
**简介**: memU 是一个专为 24/7 全天候主动式 AI 智能体设计的内存框架，旨在通过持续捕获和理解用户意图，大幅降低长期运行智能体的 LLM 令牌成本。

**核心功能**:
- **24/7 主动智能体**: 提供永不睡眠、永不遗忘的持续后台运行能力。
- **用户意图捕获**: 自动理解和记忆用户的目标、偏好及跨会话上下文。
- **成本高效**: 通过缓存洞察和避免冗余的 LLM 调用，显著降低长期运行成本。

**技术亮点**: 采用 Python 3.13+ 开发，通过独立的“记忆机器人”模块监控主智能体的交互，实现记忆的提取、存储和主动注入，从而构建长期记忆并减少上下文大小。

---
## 6. [hashicorp/vault](https://github.com/hashicorp/vault)
- **语言**: Go
- **Stars**: 34,804
- **简介**: A tool for secrets management, encryption as a service, and privileged access management

### AI 总结
**简介**: HashiCorp Vault 是一个用 Go 语言编写的工具，用于安全地管理密钥、提供加密服务以及进行特权访问管理。

**核心功能**:
- **安全的密钥存储**：可存储任意键值对，数据在写入持久化存储前会进行加密。
- **动态密钥生成**：能够为 AWS、SQL 数据库等系统按需生成密钥，并在租约到期后自动撤销。
- **数据加密**：提供加密和解密服务，无需存储原始数据，便于开发和安全团队协作。
- **租约与续期**：每个密钥都关联一个租约，到期自动撤销，客户端可通过 API 续期。
- **密钥吊销**：支持吊销单个密钥或整组密钥（如特定用户读取的所有密钥），有助于密钥轮换和入侵响应。

**技术亮点**: 采用 Go 语言开发，支持与 Consul 等后端集成，提供统一的密钥管理接口和详细的审计日志。

---
## 7. [badlogic/pi-mono](https://github.com/badlogic/pi-mono)
- **语言**: TypeScript
- **Stars**: 3,730
- **简介**: AI agent toolkit: coding agent CLI, unified LLM API, TUI & web UI libraries, Slack bot, vLLM pods

### AI 总结
**简介**: Pi 是一个用于构建 AI 智能体和管理大语言模型部署的 TypeScript 工具集。

**核心功能**:
- **统一 LLM API**: 提供支持 OpenAI、Anthropic、Google 等多供应商的统一 API。
- **智能体运行时**: 包含工具调用和状态管理的智能体运行时核心。
- **交互式编码助手**: 提供命令行界面的交互式编码智能体。
- **多样化部署与界面**: 包含 Slack 机器人、终端 UI 库、Web UI 组件库以及用于管理 GPU Pod 上 vLLM 部署的 CLI。

**技术亮点**: 采用 Monorepo 架构，包含多个独立的 npm 包，分别处理 AI 模型交互、智能体逻辑、用户界面和基础设施管理。

---
## 8. [anomalyco/opencode-anthropic-auth](https://github.com/anomalyco/opencode-anthropic-auth)
- **语言**: JavaScript
- **Stars**: 340
- **简介**: 

### AI 总结
**简介**: 一个用于在 Node.js 环境中安全调用 Anthropic API 的认证助手库。

**核心功能**:
- 提供 `AnthropicAuth` 类，用于管理 Anthropic API 密钥的认证流程。
- 自动从环境变量 `ANTHROPIC_API_KEY` 或 `.env` 文件中安全加载 API 密钥。
- 简化 API 请求的构建，自动为请求头添加正确的认证信息。

**技术亮点**: 基于 Node.js，专注于环境变量管理和安全的密钥处理，简化了与 Anthropic API 的集成。

---
## 9. [protocolbuffers/protobuf](https://github.com/protocolbuffers/protobuf)
- **语言**: C++
- **Stars**: 70,572
- **简介**: Protocol Buffers - Google's data interchange format

### AI 总结
**简介**: Protocol Buffers (protobuf) 是 Google 开发的一种语言中立、平台中立、可扩展的结构化数据序列化机制。

**核心功能**:
- 提供协议编译器，用于将 `.proto` 文件编译成目标语言代码。
- 提供多种编程语言（如 C++、Java、Python、Go 等）的运行时库，用于数据的序列化与反序列化。

**技术亮点**: 支持使用 Bazel（含 Bzlmod 和 WORKSPACE 两种模式）进行构建，并提供预编译的编译器二进制文件以简化非 C++ 用户的安装流程。

---
## 10. [pedroslopez/whatsapp-web.js](https://github.com/pedroslopez/whatsapp-web.js)
- **语言**: JavaScript
- **Stars**: 20,836
- **简介**: A WhatsApp client library for NodeJS that connects through the WhatsApp Web browser app

### AI 总结
**简介**: 一个基于 Node.js 的 WhatsApp Web 客户端库，通过 Puppeteer 控制浏览器来模拟用户操作，实现自动化消息收发与管理。

**核心功能**:
- 支持多设备登录与会话管理
- 发送和接收消息、媒体文件（图片、音频、视频、文档）、联系人卡片、位置等
- 全面的群组管理功能（创建、邀请、踢人、修改信息与设置等）
- 支持消息回复、提及用户、消息反应、创建投票等交互操作
- 支持频道（Channels）功能

**技术亮点**: 使用 Puppeteer 无头浏览器操控 WhatsApp Web，模拟真实用户行为以降低封禁风险；提供多种会话认证策略以保持登录状态。

---
