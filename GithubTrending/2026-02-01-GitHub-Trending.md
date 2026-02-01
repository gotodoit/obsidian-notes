---
tags:
  - github-trending
  - daily
date: 2026-02-01
created: 2026-02-01T22:31:45.905Z
---

# 2026-02-01 GitHub Trending Top 10

> [!INFO]
> 本日报由 AI 自动生成，精选 GitHub Trending 前 10 项目。

## 1. [openclaw/openclaw](https://github.com/openclaw/openclaw)
- **语言**: TypeScript
- **Stars**: 141,113
- **简介**: Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞

### AI 总结
**简介**: OpenClaw 是一个可在自有设备上部署的个人AI助手，支持跨多种主流通讯平台和操作系统。

**核心功能**:
- 支持通过 WhatsApp、Telegram、Slack、Discord、Google Chat、Signal、iMessage、Microsoft Teams、WebChat 等多种渠道与用户交互。
- 支持语音交互（macOS/iOS/Android）和实时画布渲染。
- 通过向导式 CLI 工具 (`openclaw onboard`) 简化网关、工作区、通道和技能的配置与部署。
- 支持 Anthropic (Claude Pro/Max) 和 OpenAI (ChatGPT/Codex) 等模型的 OAuth 订阅与认证。

**技术亮点**:
- 使用 TypeScript 开发。
- 推荐运行环境为 Node.js ≥22，支持 npm、pnpm 或 bun 包管理器。
- 提供稳定版 (stable)、测试版 (beta) 和开发版 (dev) 多个发布通道。
- 支持通过 systemd/launchd 安装守护进程，实现服务常驻。

---
## 2. [ThePrimeagen/99](https://github.com/ThePrimeagen/99)
- **语言**: Lua
- **Stars**: 2,712
- **简介**: Neovim AI agent done right

### AI 总结
**简介**: 一个为 Neovim 设计的、旨在优化 AI 工作流的智能代理插件。

**核心功能**:
- **AI 辅助编码**: 提供 `fill_in_function` 和 `visual` 等命令，利用 AI 自动补全函数或处理选中的代码块。
- **规则与技能系统**: 支持通过 `@` 触发自动补全来引用预定义的技能规则（如 `SKILL.md` 文件），并可配置自定义规则目录和项目级的 `AGENT.md` 文件来引导 AI 行为。
- **请求管理**: 可以停止所有正在进行的 AI 请求。

**技术亮点**:
- 使用 **Lua** 编写，深度集成 Neovim。
- 支持与 **cmp** 自动补全引擎集成，实现技能规则的智能提示。
- 提供可配置的日志系统，便于调试和追踪 AI 请求。

---
## 3. [pedramamini/Maestro](https://github.com/pedramamini/Maestro)
- **语言**: TypeScript
- **Stars**: 930
- **简介**: Agent Orchestration Command Center

### AI 总结
**简介**: Maestro 是一款跨平台的桌面应用，旨在通过键盘优先的设计，高效编排和管理多个AI代理与项目，实现并行开发和自动化任务执行。

**核心功能**:
- **Git Worktrees**: 在隔离分支上并行运行AI代理，实现无冲突的并行开发。
- **Auto Run & Playbooks**: 基于文件系统的任务运行器，可批量处理Markdown清单，支持可重复的工作流和长时间无人值守运行。
- **Group Chat**: 在单个对话中协调多个AI代理，由主持代理进行问题路由和响应合成。
- **Mobile Remote Control**: 内置Web服务器，支持通过二维码在手机上远程监控和控制代理。
- **Command Line Interface**: 提供完整的CLI，支持无头操作和脚本集成。
- **Multi-Agent Management**: 并行运行无限数量的代理和终端会话，每个代理拥有独立的工作空间和上下文。
- **Dual-Mode Sessions**: 每个代理同时具备AI终端和命令终端，可无缝切换。

**技术亮点**: 基于TypeScript开发，支持Claude Code、OpenAI Codex和OpenCode等AI编码工具，采用Git集成、消息队列、可扩展的斜杠命令系统，并具备强大的输出过滤和会话发现能力。

---
## 4. [kovidgoyal/calibre](https://github.com/kovidgoyal/calibre)
- **语言**: Python
- **Stars**: 23,606
- **简介**: The official source code repository for the calibre ebook manager

### AI 总结
**简介**: Calibre 是一个功能全面、跨平台的开源电子书管理工具。

**核心功能**:
- 支持查看、转换、编辑和编目主流电子书格式。
- 可与电子书阅读器设备通信。
- 能够从互联网获取书籍元数据。
- 支持下载报纸并转换为电子书以便阅读。

**技术亮点**: 项目采用 Python 语言开发，支持 Linux、Windows 和 macOS 三大操作系统，并拥有完整的持续集成（CI）流程。

---
## 5. [badlogic/pi-mono](https://github.com/badlogic/pi-mono)
- **语言**: TypeScript
- **Stars**: 4,849
- **简介**: AI agent toolkit: coding agent CLI, unified LLM API, TUI & web UI libraries, Slack bot, vLLM pods

### AI 总结
**简介**: Pi Monorepo 是一个用于构建 AI 智能体和管理大语言模型部署的 TypeScript 工具包。

**核心功能**:
- **统一 LLM API**: 提供支持 OpenAI、Anthropic、Google 等多供应商的统一接口。
- **智能体运行时**: 包含工具调用和状态管理的智能体核心运行时。
- **交互式编程助手**: 提供命令行界面的交互式编程智能体。
- **部署与管理**: 提供用于管理 GPU Pod 上 vLLM 部署的 CLI。
- **用户界面库**: 包含支持差异渲染的终端 UI 库和用于 AI 聊天界面的 Web 组件。
- **Slack 集成**: 可将 Slack 消息委托给编程智能体处理的 Slack 机器人。

**技术亮点**: 采用 TypeScript 开发，项目结构为 Monorepo，包含多个功能独立的包，并提供了完整的开发、构建、检查和测试脚本。

---
## 6. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 16,187
- **简介**: A Claude Code plugin that automatically captures everything Claude does during your coding sessions, compresses it with AI (using Claude's agent-sdk), and injects relevant context back into future sessions.

### AI 总结
**简介**: 一个为 Claude Code 设计的持久化记忆压缩系统插件，能自动捕获编码会话中的操作，通过AI压缩并注入相关上下文到未来的会话中。

**核心功能**:
- 自动捕获 Claude 在编码会话中的所有操作和观察结果
- 使用 AI（基于 Claude 的 agent-sdk）对捕获的内容进行语义压缩和总结
- 将压缩后的上下文信息智能地注入到未来的会话中，保持项目知识的连续性

**技术亮点**:
- 基于 TypeScript 开发
- 采用 Claude 的 agent-sdk 进行 AI 压缩处理
- 支持多语言文档（超过 20 种语言）
- 兼容 Node.js 18.0.0 及以上版本
- 采用 AGPL 3.0 开源协议

---
## 7. [microsoft/agent-lightning](https://github.com/microsoft/agent-lightning)
- **语言**: Python
- **Stars**: 12,930
- **简介**: The absolute trainer to light up AI agents.

### AI 总结
**简介**: 微软开源的 Agent Lightning 是一个用于优化和训练 AI 智能体的工具，旨在无需修改代码即可提升智能体性能。

**核心功能**:
- **零代码（几乎）优化**：无需修改现有智能体代码即可进行训练优化。
- **框架无关性**：支持 LangChain、OpenAI Agent SDK、AutoGen、CrewAI 等多种主流或自定义智能体框架。
- **选择性优化**：可在多智能体系统中针对特定一个或多个智能体进行优化。
- **多算法支持**：集成了强化学习、自动提示优化、监督微调等多种训练算法。

**技术亮点**: 采用简洁架构，最小化对现有智能体流程的侵入，支持通过 PyPI 快速安装，并提供了详细的文档和活跃的社区支持。

---
## 8. [amantus-ai/vibetunnel](https://github.com/amantus-ai/vibetunnel)
- **语言**: TypeScript
- **Stars**: 3,492
- **简介**: Turn any browser into your terminal & command your agents on the go.

### AI 总结
**简介**: VibeTunnel 是一个 TypeScript 项目，可将任何浏览器变为你的终端，让你能随时随地通过网页访问和控制本地终端会话。

**核心功能**:
- 将本地终端会话代理到浏览器中，实现远程访问和操作。
- 提供原生 macOS 应用（推荐）和 npm 包（支持 Linux 和 headless 系统）两种安装方式。
- 通过 `vt` 命令行工具便捷地转发和管理终端会话。

**技术亮点**: 项目采用 TypeScript 开发，提供原生 macOS 应用和基于 Node.js 的跨平台服务，支持在 Apple Silicon Mac 和 Linux 系统上运行。

---
## 9. [steipete/CodexBar](https://github.com/steipete/CodexBar)
- **语言**: Swift
- **Stars**: 3,859
- **简介**: Show usage stats for OpenAI Codex and Claude Code, without having to login.

### AI 总结
**简介**: 一款轻量级的 macOS 菜单栏应用，用于无需登录即可实时监控多个主流 AI 服务（如 OpenAI Codex、Claude、Cursor 等）的用量配额和重置时间。

**核心功能**:
- 在菜单栏集中展示多个 AI 服务提供商的会话和周期（如每周）使用量及重置倒计时。
- 支持丰富的提供商，包括 Codex、Claude、Cursor、Gemini、Copilot 等，并可通过设置灵活启用。
- 提供合并图标模式、刷新频率预设、WidgetKit 小组件以及用于脚本和 CI 的独立命令行工具。

**技术亮点**:
- 采用 Swift 开发，专为 macOS 14+ 设计，无 Dock 图标，界面极简。
- 隐私优先：默认在设备端解析数据，仅读取有限的已知位置（如浏览器 Cookie、本地日志），不存储密码。
- 架构灵活，支持通过浏览器 Cookie、OAuth、本地 CLI、API 密钥等多种方式获取不同提供商的数据。

---
## 10. [j178/prek](https://github.com/j178/prek)
- **语言**: Rust
- **Stars**: 4,216
- **简介**: ⚡ Better `pre-commit`, re-engineered in Rust

### AI 总结
**简介**: prek 是一个用 Rust 重写的、更快的 `pre-commit` 替代工具，旨在提供无依赖、高性能的 Git 钩子管理体验。

**核心功能**:
- 完全兼容原版 `pre-commit` 的配置文件和钩子。
- 提供单一二进制文件，无需 Python 或其他运行时环境。
- 内置对 monorepo（工作区模式）的支持。
- 与 `uv` 集成，用于管理 Python 虚拟环境和依赖。
- 改进了 Python、Node.js、Bun、Go、Rust 和 Ruby 等工具链的安装，支持钩子间共享。
- 内置了一些常用钩子的 Rust 原生实现。

**技术亮点**: 采用 Rust 编写，性能优于原版 `pre-commit`，磁盘空间使用更高效。

---
