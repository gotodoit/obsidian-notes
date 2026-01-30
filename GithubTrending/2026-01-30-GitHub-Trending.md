---
tags:
  - github-trending
  - daily
date: 2026-01-30
created: 2026-01-30T03:10:59.872Z
---

# 2026-01-30 GitHub Trending Top 10

> [!INFO]
> 本日报由 AI 自动生成，精选 GitHub Trending 前 10 项目。

## 1. [moltbot/moltbot](https://github.com/moltbot/moltbot)
- **语言**: TypeScript
- **Stars**: 105,371
- **简介**: Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞

### AI 总结
**简介**: Moltbot 是一个可在个人设备上部署的、跨平台和跨通信渠道的个人AI助手。

**核心功能**:
- 支持在 WhatsApp、Telegram、Slack、Discord、Google Chat、Signal、iMessage、Microsoft Teams 等主流即时通讯平台以及 WebChat 上交互。
- 支持语音交互（macOS/iOS/Android）和实时画布渲染。
- 通过向导式 CLI (`moltbot onboard`) 简化网关、工作区、渠道和技能的配置与部署。
- 支持 Anthropic (Claude) 和 OpenAI 等主流 AI 模型，并推荐使用 Anthropic Pro/Max 以获得更好的长上下文处理和抗提示注入能力。

**技术亮点**:
- 使用 TypeScript 开发，支持 npm、pnpm 或 bun 包管理器。
- 采用网关（Gateway）作为控制平面，实现助手的核心逻辑与通信渠道的解耦。
- 提供稳定的发布渠道管理（stable/beta/dev），便于用户选择或开发者参与贡献。
- 支持通过 systemd/launchd 安装守护进程，实现服务的持久化运行。

---
## 2. [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)
- **语言**: JavaScript
- **Stars**: 27,758
- **简介**: Collection of extracted System Prompts from popular chatbots like ChatGPT, Claude & Gemini

### AI 总结
**简介**: 一个收集并公开主流聊天机器人（如 ChatGPT、Claude、Gemini）系统提示词（System Prompts）的仓库。

**核心功能**:
- 汇集从热门聊天机器人中提取出的系统提示词、系统消息或开发者消息。
- 鼓励社区通过提交 Pull Request 来共同维护和更新这个集合。

**技术亮点**: 项目本身是一个信息集合，主要使用 JavaScript 语言进行相关工具或脚本的开发。

---
## 3. [MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli)
- **语言**: Python
- **Stars**: 5,004
- **简介**: Kimi Code CLI is your next CLI agent.

### AI 总结
**简介**: Kimi Code CLI 是一个在终端中运行的 AI 代理，旨在辅助完成软件开发任务和终端操作。

**核心功能**:
- **终端集成**：可在 CLI 内直接切换至 Shell 命令模式执行命令，无需退出。
- **IDE 集成**：通过支持 Agent Client Protocol (ACP)，可与 Zed、JetBrains 等兼容 ACP 的编辑器或 IDE 无缝协作。
- **Shell 增强**：提供 Zsh 插件，为 Shell 体验增加 AI 代理能力。
- **MCP 工具支持**：支持 Model Context Protocol，可便捷地管理和连接各类 MCP 服务器以扩展工具能力。

**技术亮点**: 基于 Python 开发，支持 ACP 和 MCP 协议，具备良好的可扩展性和与开发生态的集成能力。

---
## 4. [modelcontextprotocol/ext-apps](https://github.com/modelcontextprotocol/ext-apps)
- **语言**: TypeScript
- **Stars**: 859
- **简介**: Official repo for spec & SDK of MCP Apps protocol - standard for UIs embedded AI chatbots, served by MCP servers

### AI 总结
**简介**: 这是一个为 MCP Apps 协议提供官方规范与 SDK 的 TypeScript 项目，旨在为嵌入 AI 聊天机器人的 UI 提供标准化交互界面。

**核心功能**:
- 提供 **MCP Apps 协议规范**，允许 MCP 服务器在对话式客户端中声明和交付交互式 UI（如图表、表单、播放器）。
- 提供 **SDK 与开发库**，包含面向应用开发者的核心 SDK 与 React Hooks，以及面向主机开发者的应用桥接 SDK。
- 支持 **双向通信机制**，UI 可通过沙盒 iframe 渲染，并与主机进行数据交换和工具调用。

**技术亮点**:
- 基于 **Model Context Protocol (MCP)** 扩展，通过 `ui://` 资源声明实现 UI 嵌入。
- 提供 **TypeScript SDK** 与 **React 集成**，支持现代前端开发。
- 包含丰富的 **示例应用**（如地图、Three.js、ShaderToy），展示实时 3D 渲染、交互式可视化等实际用例。

---
## 5. [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU)
- **语言**: Python
- **Stars**: 6,100
- **简介**: Memory for 24/7 proactive agents like moltbot (clawdbot).

### AI 总结
**简介**: memU 是一个专为24/7持续运行的主动式AI智能体设计的内存框架，旨在通过降低LLM令牌成本并持续理解用户意图，使长期在线、自主进化的智能体变得实用。

**核心功能**:
- **24/7主动智能体**: 提供永不睡眠、永不遗忘的持续后台运行内存。
- **用户意图捕捉**: 自动理解并记忆用户的目标、偏好和跨会话的上下文。
- **成本高效**: 通过缓存洞察和避免冗余的LLM调用，显著降低长期运行的令牌成本。

**技术亮点**: 基于Python 3.13+开发，采用主动内存生命周期管理架构，能够预测用户意图并自主准备相关上下文，实现智能体驱动的主动工作流。

---
## 6. [hashicorp/vault](https://github.com/hashicorp/vault)
- **语言**: Go
- **Stars**: 34,640
- **简介**: A tool for secrets management, encryption as a service, and privileged access management

### AI 总结
**简介**: Vault 是一个用 Go 语言编写的、用于安全访问和管理密钥（如 API 密钥、密码、证书等）的工具，提供统一的密钥管理界面、严格的访问控制和详细的审计日志。

**核心功能**:
- **安全密钥存储**：可存储任意键值对，数据在写入持久存储前会进行加密。
- **动态密钥生成**：能为 AWS 或 SQL 数据库等系统按需生成密钥，并在租约到期后自动撤销。
- **数据加密**：提供加密和解密服务，无需存储原始数据，便于开发和安全团队协作。
- **租约与续期**：每个密钥都关联一个租约，到期自动撤销，客户端可通过 API 续期。
- **密钥撤销**：支持撤销单个密钥或按特定条件（如用户、类型）批量撤销，便于密钥轮换和入侵响应。

**技术亮点**: 采用 Go 语言开发，支持与 Consul 等后端集成，提供企业版，并拥有完善的文档、教程和认证体系。

---
## 7. [badlogic/pi-mono](https://github.com/badlogic/pi-mono)
- **语言**: TypeScript
- **Stars**: 3,492
- **简介**: AI agent toolkit: coding agent CLI, unified LLM API, TUI & web UI libraries, Slack bot, vLLM pods

### AI 总结
**简介**: Pi Monorepo 是一个用于构建 AI 代理和管理大语言模型（LLM）部署的 TypeScript 工具集。

**核心功能**:
- **统一 LLM API**: 提供支持多提供商（OpenAI、Anthropic、Google 等）的统一 API。
- **AI 代理工具**: 包含代理运行时（支持工具调用和状态管理）、交互式编码代理 CLI 以及 Slack 机器人。
- **用户界面库**: 提供支持差异渲染的终端 UI 库和用于 AI 聊天界面的 Web 组件。
- **部署管理**: 提供用于在 GPU Pod 上管理 vLLM 部署的 CLI 工具。

**技术亮点**: 采用 Monorepo 架构，使用 TypeScript 开发，并包含完整的开发工作流（构建、检查、测试）。

---
## 8. [anomalyco/opencode-anthropic-auth](https://github.com/anomalyco/opencode-anthropic-auth)
- **语言**: JavaScript
- **Stars**: 264
- **简介**: 

### AI 总结
**简介**: 一个用于在 Node.js 环境中安全获取 Anthropic API 访问令牌的库。

**核心功能**:
- 通过 OAuth 2.0 流程，安全地从 Anthropic 获取访问令牌。
- 提供简单的 API，便于在 Node.js 应用程序中集成 Anthropic 的身份验证。

**技术亮点**: 基于 Node.js 环境，实现了标准的 OAuth 2.0 授权码流程，用于与 Anthropic API 进行安全交互。

---
## 9. [protocolbuffers/protobuf](https://github.com/protocolbuffers/protobuf)
- **语言**: C++
- **Stars**: 70,520
- **简介**: Protocol Buffers - Google's data interchange format

### AI 总结
**简介**: Protocol Buffers (protobuf) 是 Google 开发的一种语言中立、平台中立、可扩展的结构化数据序列化机制。

**核心功能**:
- 提供协议编译器，用于将 `.proto` 文件编译成各种编程语言的代码。
- 为多种编程语言（如 C++、Java、Python、Go、C# 等）提供运行时库，用于序列化和反序列化结构化数据。

**技术亮点**:
- 支持使用 Bazel（支持 Bzlmod 和传统 WORKSPACE）进行构建和依赖管理。
- 提供预编译的二进制编译器供非 C++ 用户快速使用，也支持从源码构建。
- 项目遵循严格的发布流程，建议用户使用已发布的稳定版本而非主分支，以保证兼容性和稳定性。

---
## 10. [pedroslopez/whatsapp-web.js](https://github.com/pedroslopez/whatsapp-web.js)
- **语言**: JavaScript
- **Stars**: 20,722
- **简介**: A WhatsApp client library for NodeJS that connects through the WhatsApp Web browser app

### AI 总结
**简介**: 一个基于 Node.js 的 WhatsApp Web 客户端库，通过 Puppeteer 控制浏览器来模拟用户操作，实现与 WhatsApp 的交互。

**核心功能**:
- 支持多设备登录，可发送和接收消息、媒体文件（图片、音频、视频、文档）、贴纸、联系人卡片和位置信息。
- 支持群组管理，包括创建邀请、修改群组信息和设置、添加/移除成员、提升/降级成员权限等。
- 支持用户状态设置、消息回复、消息反应、创建投票、频道功能，以及静音/取消静音聊天、屏蔽/取消屏蔽联系人等操作。

**技术亮点**: 使用 Puppeteer 无头浏览器技术，通过 WhatsApp Web 的内部接口进行操作，支持会话保存与恢复，并提供了多种身份验证策略。

---
