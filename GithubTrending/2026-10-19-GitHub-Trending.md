---
tags:
  - github-trending
  - daily
date: 2026-10-19
created: 2026-10-19T01:55:42.894Z
---

# 2026-10-19 GitHub Trending Top 10

## 1. [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)
- **语言**: Python
- **Stars**: 53,390
- **简介**: The job search that runs on your machine. AI job application framework built on Claude Code: evaluate postings, tailor CVs, write cover letters, prep interviews. Fork it and own it.

### AI 总结
**简介**: 一个基于 Claude Code 的本地化 AI 求职申请框架，通过结构化工作流自动完成职位评估、简历定制、求职信撰写和面试准备。

**核心功能**:
- `/setup`：填写个人档案，生成结构化的个人资料文件
- `/scrape`：搜索招聘门户（当前适配丹麦市场：Jobindex、Jobnet、Akademikernes Jobbank 等），展示带匹配评分的职位列表
- `/apply <url>`：评估职位匹配度并打分推荐，随后用 LaTeX 生成定制化的 CV 与求职信，经 Reviewer agent 评审、修改后输出最终版本
- `/interview`：面试准备辅助
- 内置职业指导最佳实践：结构化评估标准、前瞻性求职信框架、可选薪资基准参考

**技术亮点**:
- 基于 Claude Code 构建的 drafter-reviewer 双代理流水线，核心工作流语言与国家无关，招聘门户技能可按本地市场替换
- 使用 LaTeX 排版输出：CV 用 `lualatex` 编译，求职信由 `cover.cls`（依赖 `fontspec`）用 `xelatex` 编译
- 技术栈：Python 3.10+、Bun（求职搜索 CLI 工具）、LaTeX 发行版
- 支持 ATS 可解析性检查（可选 `pypdf`，Poppler `pdftotext` 作为回退）
- 项目作者本人用该框架完成 69 份定制申请、20 次初面并成功入职 AI 工程师岗位

---
## 2. [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- **语言**: Python
- **Stars**: 42,735
- **简介**: Official, Anthropic-managed directory of high quality Claude Code Plugins.

### AI 总结
**简介**: Anthropic 官方维护的 Claude Code 高质量插件目录，收录内部与第三方插件，支持通过插件市场直接安装。

**核心功能**:
- 提供插件目录，分为 `/plugins`（Anthropic 内部开发）与 `/external_plugins`（第三方及社区）两类
- 支持通过 `/plugin install {plugin-name}@claude-plugins-official` 命令或 `/plugin > Discover` 浏览安装
- 支持第三方插件提交，需满足质量与安全标准审核
- 定义标准化插件结构（plugin.json、.mcp.json、commands、agents、skills 等）
- 插件名称不可变，支持通过 `renames` 映射实现旧名自动迁移
- 支持 skill-bundle 插件：无 manifest 时可通过 `strict: false` + `skills` 数组直接声明技能

**技术亮点**: 基于 Claude Code 插件市场机制，采用标准目录结构组织插件；通过 `marketplace.json` 中的 `strict` 模式与 `renames` 映射实现灵活的技能打包与向后兼容的插件重命名；技能以 `<plugin-name>:<skill-name>` 形式注册。

---
## 3. [anomalyco/opencode](https://github.com/anomalyco/opencode)
- **语言**: TypeScript
- **Stars**: 216,652
- **简介**: The open source coding agent.

### AI 总结
**简介**: OpenCode 是一个用 TypeScript 开发的开源 AI 编程代理（coding agent），提供终端 UI 和桌面应用两种形态。

**核心功能**:
- 内置 **build** 与 **plan** 两种代理，可通过 `Tab` 键切换：build 为默认的全权限开发代理，plan 为只读的分析与代码探索代理（默认禁止文件编辑、执行 bash 前需授权）
- 提供 **general** 子代理，用于复杂搜索和多步骤任务，可通过 `@general` 调用
- 支持多种安装方式：一键脚本、npm/bun/pnpm/yarn、Homebrew、Pacman/AUR、mise、Nix
- 提供桌面应用（Beta），覆盖 macOS（Apple Silicon/Intel）、Windows、Linux（.deb/.rpm/.AppImage）
- 安装脚本支持自定义安装目录，按 `OPENCODE_INSTALL_DIR` → `XDG_BIN_DIR` → `$HOME/bin` → `$HOME/.opencode/bin` 优先级选择路径

**技术亮点**: 基于 TypeScript 开发，采用 monorepo 结构（含 `packages/console`、`packages/web` 等），通过 npm 包 `@opencode/cli` 分发 CLI；提供多语言 README（20+ 种语言）和 Discord 社区支持。

---
## 4. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 12,765
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，汇集面向主流开发工具、框架和 SaaS 产品的插件，每个插件均为独立目录并带有自己的 `.cursor-plugin/plugin.json` 清单。

**核心功能**:
- **开发工具类插件**：提供教学辅助（Teaching）、持续学习（Continual Learning）、团队协作（Cursor Team Kit）、深度代码审查（Thermos）、插件脚手架（Create Plugin）、迭代式 AI 循环（Ralph Loop）、仓库兼容性扫描（Agent Compatibility）、CLI 设计规范（CLI for Agents）、PR 审查画布（PR Review Canvas）、文档画布（Docs Canvas）、TypeScript SDK（Cursor SDK）、Origin API 开发技能（Origin Apps）、并行云代理编排（Orchestrate）、高质量编码工作流（pstack、dyl-stack）、强模型咨询（Advisor）以及 Grok 语音集成（Grok Voice）等能力。
- **生产力类插件**：覆盖 Gmail、Google Drive、Google Calendar、Google Docs、Google Sheets、Google Slides，支持邮件管理、文件读写共享、日程安排和文档表格幻灯片编辑。
- **集成类插件**：包括 Google Ads、Gong、Salesforce（含 Headless 360 Beta）以及 Playwright 等，用于广告投放分析、销售数据洞察、CRM 记录管理和浏览器自动化测试。

**技术亮点**: 项目以 TypeScript 为主要语言；采用“根目录独立插件 + 统一清单文件”的模块化架构，便于插件的独立开发、分发与市场接入。

---
## 5. [ruvnet/ruflo](https://github.com/ruvnet/ruflo)
- **语言**: TypeScript
- **Stars**: 76,553
- **简介**: 🌊 The original agent harness. Deploy intelligent multi-player swarms, coordinate autonomous workflows, and build conversational AI systems. Features adaptive memory, self-learning intelligence, federation, vector RAG integration, and native Claude Code / Codex / Hermes and many more Integrated

### AI 总结
**简介**: Ruflo 是一个面向 Claude Code 与 Codex 的智能体元框架（agent meta-harness），用于部署多智能体集群、编排自主工作流并构建对话式 AI 系统。

**核心功能**:
- 多智能体集群部署与自主工作流协调，支持自适应记忆与自学习智能
- 联邦机制与向量 RAG 集成，支持持久化上下文与反馈学习
- 原生集成 Claude Code / Codex / Hermes 等多种工具，通过插件市场一键安装
- 提供可视化控制台（Console）与可选独立终端 UI（TUI），含成本、Swarm、事件等监控面板
- 通过 MCP 服务器向各类客户端暴露工具，支持 `npx ruflo@latest init wizard` 快速初始化
- 可选 ruOS 桌面环境，支持通过 MCP 连接 ChatGPT 或 Claude

**技术亮点**: 基于 TypeScript 开发；采用插件化架构（Core / Console / Mods 分层）；通过 MCP 协议实现跨客户端工具集成；配套 RuVector 提供本地向量搜索、图关系与持久记忆能力。

---
## 6. [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory)
- **语言**: Rust
- **Stars**: 10,531
- **简介**: Solution for long term memory for agent coding CLIs and to facilitate handoff between different agent vendors

### AI 总结
**简介**: ai-memory 是一个用 Rust 编写的长期记忆解决方案，让 AI 编程代理在不同厂商工具（如 Claude Code、Codex、Cursor 等）之间无缝交接任务，无需重复解释背景。

**核心功能**:
- **跨代理记忆共享**：支持 20 多个编程代理（Claude Code、Codex、Cursor、Gemini CLI 等）共享同一份记忆，交接内容为类型化协议，每个交接有明确归属且仅被认领一次
- **跨项目与跨机器延续**：用户的工作习惯画像会带入每个新仓库；记忆存储于自建服务器，可在不同设备间恢复同一项目的知识
- **团队协作**：多人共用一个服务器时，项目知识可共享，个人交接保持私密，内置多用户认证、归属追踪和审计日志
- **静默捕获与零 LLM 依赖**：通过生命周期钩子自动记录提示、工具调用和会话边界，在类型化隐私边界处脱敏；默认路径捕获、搜索和交接均无需 API Key
- **纯 Markdown 存储**：记忆以 git 托管的普通 `.md` 文件为唯一真相来源，可用 grep、Obsidian 或手动编辑，数据库仅为可重建的派生索引
- **无 LLM 的记忆老化机制**：按可调周期衰减记忆，被使用的记忆衰减更慢；冷记忆可压缩为持久事实，近重复合并、矛盾标记均零 API 调用，原始内容保留在 git 中可恢复
- **可选的“做梦”功能**：配置 LLM 后，空闲时后台将冷笔记重写为连贯页面，默认关闭且需通过召回评估

**技术亮点**: Rust 实现（需 1.95+），采用 git -backed wiki 作为真相源、数据库作为派生索引的架构；类型化隐私边界与交接协议；零 LLM 调用的默认路径；基于访问权重的记忆保留策略；MIT 许可证。

---
## 7. [stablyai/orca](https://github.com/stablyai/orca)
- **语言**: TypeScript
- **Stars**: 96,734
- **简介**: Orca is the place for working with a fleet of agents (e.g. Grok Bot, Claude Code). Run any coding agent with your own subscription. Available on desktop, mobile and remote runtime.

### AI 总结
**简介**: Orca 是一个面向开发者的 AI 智能体编排工具，可同时运行 Codex、Claude Code、OpenCode、Pi 等多种编码智能体，并支持桌面、移动端与远程运行时。

**核心功能**:
- **移动伴侣端**：在手机上监控和操控智能体，智能体完成任务时收到通知，并可随时发送后续指令
- **并行工作树**：将一条提示分发给多个智能体，各自在独立的 git worktree 中运行，对比结果后合并最优方案
- **终端分屏**：Ghostty 级终端，支持 WebGL 渲染、无限分屏，且滚动历史在重启后仍保留
- **设计模式**：在真实 Chromium 窗口中点击任意 UI 元素，即可将其 HTML、CSS 和截图直接发送到智能体提示中
- **GitHub 与 Linear 原生集成**：在应用内浏览 PR、issue 和项目看板，从任务直接打开工作树，无需切换上下文
- **SSH 工作树**：在远程高性能机器上运行智能体，支持完整的文件编辑、git 和终端，并自动重连与端口转发

**技术亮点**: 基于 TypeScript 构建；支持 macOS、Windows、Linux 多平台；采用 git worktree 实现智能体间的工作隔离；终端基于 WebGL 渲染；采用 MIT 开源协议。

---
## 8. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 54,622
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: HKUDS 推出的 CLI-Anything 项目，旨在为任意软件生成可被 AI Agent 直接调用的命令行接口（CLI），让软件“Agent-Native”，打通 AI 智能体与世界软件之间的鸿沟。

**核心功能**:
- 一键为各类软件生成 Agent 可用的 CLI harness，适配 Pi、OpenClaw、nanobot、Cursor、Claude Code 等智能体
- 提供 CLI-Hub 社区中心，可通过 `pip install cli-anything-hub` 后使用 `cli-hub install <name>` 浏览、安装和管理社区构建的 CLI
- 支持预览、实时预览与轨迹循环（trajectory loops），可产出 CAD 构建、3D 场景、图表、游戏、字幕等真实制品
- 开放贡献机制，支持提交新 CLI harness 或通过 wishlist 请求特定软件支持

**技术亮点**: 基于 Python（≥3.10）与 Click 构建 CLI，采用 pytest 单元与端到端测试（宣称 2461 项测试通过），输出支持 JSON 与人类可读双格式；配套 arXiv 技术报告，采用 Apache 2.0 开源许可。

---
## 9. [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio)
- **语言**: Python
- **Stars**: 75,503
- **简介**: VoiceStudio is the open-source, fully-local ElevenLabs alternative — voice cloning, voice design, video dubbing, dictation, transcription & audiobook creation in 646 languages.

### AI 总结
**简介**: VoiceStudio 是一个开源、完全本地运行的 ElevenLabs 替代方案，基于 Python 构建，支持 646 种语言的语音克隆、语音设计、视频配音、听写、转录和有声书制作。

**核心功能**:
- **语音克隆与设计**：克隆已有声音，或通过描述设计自定义语音
- **视频配音**：为视频生成带时间轴的语音配音
- **听写与转录**：通过浮动小组件进行语音听写，支持音频转录
- **有声书与批量任务**：制作故事、有声书，支持批处理和监视文件夹
- **本地 API 与 MCP**：为智能体提供本地 API 和 MCP 连接能力，支持可复用配方

**技术亮点**:
- 默认引擎基于 k2-fsa/OmniVoice，支持切换其他引擎
- 完全本地运行，远程服务可选，使用分析需用户同意
- 支持 CUDA（NVIDIA GPU）、Metal/MPS（Apple Silicon）加速，无独显时可用 CPU 运行
- 提供 Electron 桌面应用，支持 macOS、Windows、Linux 及 Docker 部署
- 采用 AGPL-3.0 许可证

---
## 10. [android/skills](https://github.com/android/skills)
- **语言**: Kotlin
- **Stars**: 8,796
- **简介**: 

### AI 总结
**简介**: Android 官方推出的 AI 优化模块化技能库，帮助 AI 代理更好地理解和执行符合 Android 开发最佳实践的特定任务模式。

**核心功能**:
- 提供基于开放标准（SKILL.md）的模块化技能说明文件，聚焦 LLM 表现较弱的用例和工作流
- 支持通过 Android CLI 安装单个或全部技能（`android skills add`），并可更新已安装技能
- 支持作为代理插件安装（Claude Code、Codex），代理会根据任务自动激活相关技能

**技术亮点**: 采用开放标准 Agent Skills 格式（Markdown 规范文件）为 LLM 提供领域知识；基于 Kotlin 开发；遵循 developer.android.com 官方指南；以 Apache License 2.0 开源。

---
