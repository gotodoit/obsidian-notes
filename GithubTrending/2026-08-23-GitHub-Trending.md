---
tags:
  - github-trending
  - daily
date: 2026-08-23
created: 2026-08-23T01:55:44.226Z
---

# 2026-08-23 GitHub Trending Top 10

## 1. [openai/codex](https://github.com/openai/codex)
- **语言**: Rust
- **Stars**: 113,491
- **简介**: Lightweight coding agent that runs in your terminal

### AI 总结
**简介**: Codex CLI 是 OpenAI 推出的轻量级编码代理，运行在终端中，帮助开发者直接在命令行完成编程任务。

**核心功能**:
- 终端内运行的本地编码代理，支持自然语言驱动的代码生成与修改
- 支持 ChatGPT 账号登录（Plus/Pro/Business/Edu/Enterprise 套餐），也可通过 API Key 使用
- 提供 IDE 插件（VS Code、Cursor、Windsurf）和桌面应用（`codex app`）扩展
- 跨平台安装支持：macOS、Linux、Windows，可通过 curl/powershell 脚本、npm、Homebrew 或 GitHub Releases 安装

**技术亮点**:
- 使用 Rust 编写，性能高效
- 提供多种安装方式（脚本、包管理器、预编译二进制），并支持自定义下载源（默认 OpenAI 官方，可回退到 GitHub Releases）
- 采用 Apache-2.0 开源协议，附带贡献指南和开源基金支持

---
## 2. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 232,134
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: mattpocock/skills 是作者日常使用的 AI 编程代理（如 Claude Code、Codex）技能集合，旨在帮助开发者进行真实工程开发，而非“vibe coding”，强调小、易适配、可组合，且兼容任何模型。

**核心功能**:
- **快速安装**: 支持通过 Claude Code 插件（自动更新）或 `npx skills` 命令（可编辑文件）两种方式安装，并可选择安装到不同代理。
- **一键初始化**: 运行 `/setup-matt-pocock-skills` 可配置问题追踪器（GitHub/Linear/本地文件）、标签规则和文档存储位置。
- **对齐需求（Grilling）**: 提供 `/grill-me` 和 `/grill-with-docs` 技能，通过让代理在开发前向你提出详细问题，解决“代理没按预期工作”的沟通偏差问题。
- **降低冗长**: 基于领域驱动设计理念，帮助减少代理输出过于冗长的问题。

**技术亮点**: 基于 Shell 实现，采用“小而美”的技能设计哲学，支持即插即用与自由定制，并可通过 skills.sh 或插件市场分发与更新。

---
## 3. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 242,186
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个面向 AI 编程代理（如 Claude Code、Codex、Opencode、Cursor 等）的性能优化系统，提供技能、直觉、记忆、安全与研究优先的开发能力。

**核心功能**:
- **技能与代理增强**: 为 Claude Code 等代理提供可安装的技能、代理、命令和插件管理的钩子（hooks），提升代理的自动化能力
- **多语言支持**: 内置 Shell、TypeScript、Python、Go、Java、Perl、Markdown 等多种语言环境支持，适配不同开发场景
- **安全防护（AgentShield）**: 提供 `ecc-agentshield` npm 包，用于代理运行时的安全防护
- **多渠道安装**: 支持通过 Claude Code 插件市场、npm 包（`ecc-universal`）、GitHub App 等多种方式安装部署
- **社区与生态**: 拥有活跃的 Discord 社区、官方网站（ecc.tools）及多语言文档（含简体中文、繁体中文、日、韩、德、法、葡等 12 种语言）

**技术亮点**: 基于 JavaScript/TypeScript 构建，采用插件化架构设计，通过 marketplace 机制实现模块化安装；提供统一的 npm 包（`ecc-universal`）和代理安全包（`ecc-agentshield`）双通道分发；项目强调官方源安全验证，仅支持从 GitHub 仓库、npm 官方包及官网等可信渠道获取，以防范第三方恶意篡改。

---
## 4. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 276,202
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码代理的软件开发方法论框架，通过可组合的技能和初始指令，让 AI 代理自动遵循规范的开发流程。

**核心功能**:
- **需求澄清**: 代理启动时不会直接写代码，而是先询问用户真实目标，从对话中提炼出规格说明
- **设计评审**: 将规格以短段落形式展示给用户，便于阅读和确认
- **实施规划**: 生成清晰的实施计划，强调 TDD（测试驱动开发）、YAGNI（不需要则不实现）和 DRY（不重复自己）原则
- **自主子代理开发**: 用户批准后，代理启动子代理驱动的开发流程，逐个完成工程任务并进行审查，可自主工作数小时
- **多平台支持**: 支持 Claude Code、Cursor、Gemini CLI、Codex、GitHub Copilot CLI 等十余种主流编码代理工具

**技术亮点**:
- 基于 Shell 实现，采用插件化架构，可通过官方市场或 GitHub 仓库安装
- 技能自动触发机制，无需用户手动干预，代理自动应用方法论
- 提供企业级商业支持服务，包括技术支持、附加工具和托管支出管理

---
## 5. [Wei-Shaw/sub2api](https://github.com/Wei-Shaw/sub2api)
- **语言**: Go
- **Stars**: 38,802
- **简介**: Sub2API 一站式开源中转服务，让 Claude、Openai 、Gemini、Grok订阅统一接入，支持拼车共享，更高效分摊成本，原生工具无缝使用。

### AI 总结
**简介**: Sub2API 是一个开源的 AI API 网关平台，用于将 Claude、OpenAI、Gemini 等订阅配额统一转换为 API 接口，支持拼车共享以降低成本。
**核心功能**:
- 统一接入多个 AI 提供商的订阅服务（Claude、OpenAI、Gemini、Grok），转换为标准 API 格式
- 支持拼车共享，让多个用户分摊订阅成本
- 原生工具无缝使用，兼容 Claude Code、Codex 等主流编程工具
- 提供 Web 管理界面（基于 Vue 3），便于配额管理和用户管理
**技术亮点**: 基于 Go 1.26.5 构建，使用 Vue 3.4+ 前端，PostgreSQL 15+ 存储，Redis 7+ 缓存，支持 Docker 一键部署；采用网关架构设计，实现多提供商适配和配额分发。

---
## 6. [makeplane/plane](https://github.com/makeplane/plane)
- **语言**: TypeScript
- **Stars**: 57,238
- **简介**: 🔥🔥🔥 Open-source Jira, Linear, Monday, and ClickUp alternative. Plane is a modern project management platform to manage tasks, sprints, docs, and triage.

### AI 总结
**简介**: Plane 是一个开源的现代项目管理平台，旨在替代 Jira、Linear、Monday 和 ClickUp，帮助团队轻松管理任务、冲刺（Cycles）、文档和问题分类。

**核心功能**:
- **工作项（Work Items）**: 使用富文本编辑器高效创建和管理任务，支持文件上传、子属性设置和关联问题引用。
- **周期（Cycles）**: 通过燃尽图等工具跟踪团队进度，维持工作节奏。
- **模块（Modules）**: 将复杂项目拆分为更小、更易管理的子模块。
- **视图（Views）**: 通过自定义过滤器展示关键问题，并支持保存和共享视图。
- **页面（Pages）**: 利用 AI 和富文本编辑器记录和整理想法，可将笔记转化为可执行任务。
- **分析（Analytics）**: 提供实时数据洞察，可视化趋势并帮助移除项目阻塞。

**技术亮点**: 基于 TypeScript 开发，前端使用 React Router，后端采用 Django 框架，并依赖 Node.js 环境。支持多种部署方式，包括 Docker、Kubernetes 和托管服务，并提供云版本（Plane Cloud）和自托管选项，满足不同用户对数据控制的需求。

---
## 7. [n8n-io/n8n](https://github.com/n8n-io/n8n)
- **语言**: TypeScript
- **Stars**: 201,836
- **简介**: Fair-code workflow automation platform with native AI capabilities. Combine visual building with custom code, self-host or cloud, 400+ integrations.

### AI 总结
**简介**: n8n 是一个公平代码（fair-code）许可的工作流自动化平台，原生支持 AI 能力，允许用户通过可视化画布结合自定义代码构建和部署 AI 代理与自动化工作流，支持自托管或云服务，并集成 1500+ 应用。

**核心功能**:
- **AI 原生自动化平台**: 构建和运营 AI 工作流及多步骤代理，可使用自有数据、模型和工具
- **模型灵活性，无锁定**: 支持 OpenAI、Anthropic、Google 及开源模型，切换供应商无需更改架构
- **从原型到生产**: 设计包含逻辑、工具调用、人工审批和完整可观测性的多步骤 AI 工作流
- **按需编写代码**: 将可视化构建与 JavaScript、Python 和 npm 包结合，用于高级 AI 工作流
- **企业级 AI 就绪**: 支持自托管或安全部署，具备基于角色的访问控制、审计追踪和敏感数据处理能力
- **充分利用现有资源**: 1500+ 集成和 9000+ 工作流模板，将 AI 与现有系统连接

**技术亮点**: 基于 TypeScript 构建，采用公平代码（fair-code）许可模式（Sustainable Use License 和 Enterprise License），源码可见、可自托管、可扩展自定义节点；支持 Docker 一键部署，提供可视化节点编辑器和 CLI 操作界面。

---
## 8. [anthropics/claude-code](https://github.com/anthropics/claude-code)
- **语言**: Python
- **Stars**: 142,551
- **简介**: Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands.

### AI 总结
**简介**: Claude Code 是 Anthropic 推出的终端智能编码代理，通过自然语言交互帮助开发者理解代码库、执行日常任务并处理 Git 工作流。

**核心功能**:
- 自然语言驱动：通过对话式指令完成编码任务，无需手动查找文档或编写复杂命令
- 代码理解与解释：快速解析代码库结构，解释复杂代码逻辑
- Git 工作流自动化：处理分支管理、提交、合并等日常 Git 操作
- 跨平台支持：支持 MacOS、Linux、Windows 系统，并集成于终端、IDE 及 GitHub（@claude 标签）
- 插件扩展：提供自定义命令和代理的插件机制，增强功能灵活性
- 问题反馈：内置 `/bug` 命令直接报告问题，并支持社区 Discord 交流

**技术亮点**: 基于 Node.js 18+ 构建，采用 npm 分发（现已弃用，推荐官方脚本安装）；强调数据隐私保护，具备敏感信息留存限制、会话数据访问控制等安全机制；支持多环境无缝切换（终端/IDE/GitHub）。

---
## 9. [AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi)
- **语言**: Rust
- **Stars**: 13,980
- **简介**: ⚡️A native, local-first alternative to Logitech Options+, written in Rust 🦀 — remap buttons, DPI, and SmartShift over HID++. No account, no telemetry.

### AI 总结
**简介**: OpenLogi 是一个用 Rust 编写的本地优先、原生 Logitech Options+ 替代品，通过 HID++ 和 UVC 协议解锁罗技鼠标、键盘和摄像头的全部功能，无需账户和遥测。

**核心功能**:
- **鼠标**: 按键重映射（含中键、模式切换键、拇指滚轮）、手势绑定、DPI 控制与预设、SmartShift 滚轮模式切换、原生滚动方向反转
- **键盘**: 全局 F 键重映射（支持文本输入、组合键、多步骤工作流）、静态 RGB 灯光控制
- **摄像头**: 支持任意罗技 UVC 摄像头（Brio、StreamCam、C920 等），实时预览（仅在观看时占用摄像头）、硬件级图像参数调节（变焦、对焦、曝光等）、一键配置文件（默认/直播/视频通话）
- **通用**: 电池电量显示、按应用自动切换配置（macOS + Windows，Linux 仅 X11/XWayland）、Litra 灯光控制（亮度、色温、随摄像头自动开关）、操作环（光标中心八槽动作面板）

**技术亮点**:
- 原生 Rust + GPUI，轻量高效
- 首个将 Linux 作为一等公民的罗技外设管理工具
- 纯文本 TOML 配置，便于跨机器同步
- 提供 CLI 和 GUI 双界面
- 支持 Logi Bolt、Unifying 接收器、蓝牙和有线连接
- 跨平台（macOS 13+、Linux、Windows）

---
## 10. [modular/modular](https://github.com/modular/modular)
- **语言**: Mojo
- **Stars**: 28,851
- **简介**: The Modular Platform (includes MAX & Mojo)

### AI 总结
**简介**: Modular Platform 是一个统一的 AI 开发与部署平台，包含 MAX 框架和 Mojo 语言，旨在简化 AI 模型的构建、优化与部署。

**核心功能**:
- **Mojo 编译器**: 提供高性能的 Mojo 语言编译器，支持 Python 生态兼容的 AI 开发。
- **Mojo 标准库**: 包含丰富的标准库，涵盖数据处理、算法及系统编程接口。
- **MAX 加速器库**: 提供高性能的 AI 内核实现，针对不同硬件架构优化计算性能。
- **MAX 推理服务器**: 提供 OpenAI 兼容的推理端点，支持模型的快速部署与调用。
- **MAX 模型流水线**: 基于 Python 的图结构，支持模型加载、预处理、推理及后处理流程。
- **代码示例**: 提供丰富的 MAX 与 Mojo 示例代码，帮助开发者快速上手。

**技术亮点**:
- 基于 **Mojo 语言**（支持 Python 语法与系统级性能）构建，融合 Python 易用性与 C++ 性能。
- 采用 **Apache License v2.0（含 LLVM 例外）** 开源许可，支持社区贡献。
- 支持 **MAX 框架** 与 **Mojo 编译器** 的协同工作，提供端到端的 AI 开发体验。

---
