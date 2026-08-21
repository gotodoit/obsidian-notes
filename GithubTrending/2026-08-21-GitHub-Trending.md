---
tags:
  - github-trending
  - daily
date: 2026-08-21
created: 2026-08-21T01:55:44.715Z
---

# 2026-08-21 GitHub Trending Top 10

## 1. [modular/modular](https://github.com/modular/modular)
- **语言**: Mojo
- **Stars**: 27,983
- **简介**: The Modular Platform (includes MAX & Mojo)

### AI 总结
**简介**: Modular Platform 是一个统一的 AI 开发与部署平台，包含 MAX Framework 和 Mojo 语言两大核心组件。

**核心功能**:
- **Mojo 编译器与标准库**: 提供高性能的 Mojo 编程语言编译器及标准库，支持 AI 相关开发
- **MAX 加速库**: 提供高性能的 AI 内核加速库，优化模型推理性能
- **MAX 推理服务器**: 提供 OpenAI 兼容的推理端点，支持模型部署与服务
- **MAX 模型流水线**: 基于 Python 的模型图构建，支持多种模型架构
- **代码示例**: 提供 MAX 和 Mojo 的示例代码，帮助开发者快速上手

**技术亮点**:
- 基于 Mojo 语言构建，结合 Python 易用性与 C 级性能
- 支持 Apache License v2.0 开源协议（含 LLVM Exceptions）
- 提供完整的社区支持体系（Discord、论坛、Meetup 等）
- 持续开源更多平台组件，接受社区贡献（标准库、加速库、模型架构等）

---
## 2. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 226,653
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: 这是 Matt Pocock 开源的一套面向真实工程场景的 AI 编码 Agent Skills，源自其日常使用的 `.agents` 目录，强调小型、可组合、可定制，而非“vibe coding”式的全流程接管。

**核心功能**:
- **安装即用**：支持通过 Claude Code 插件（`claude plugins install mattpocock-skills`）或 `npx skills@latest add mattpocock/skills` 快速安装，后者可自由选择技能并适配多种 Agent（如 Codex）。
- **一键初始化**：运行 `/setup-matt-pocock-skills` 可配置项目偏好（问题追踪器类型、标签体系、文档存储位置）。
- **需求对齐技能**：提供 `/grill-me`（非代码场景）和 `/grill-with-docs`（代码场景）技能，通过“盘问式”提问让 Agent 在动手前充分理解需求，解决“Agent 没做对”的常见痛点。
- **约束输出风格**：内置技能帮助约束 Agent 的回复简洁度，避免过度冗长（基于领域驱动设计中的“通用语言”理念）。
- **可编辑与可更新**：技能文件以普通文件形式写入仓库，支持自由修改；通过 `npx skills update` 手动拉取更新，不强制后台自动更新。

**技术亮点**:
- 基于 Shell 脚本实现，轻量且与模型无关，可运行于 Claude Code、Codex 等主流编码 Agent。
- 采用“插件（只读订阅） + 文件复制（可编辑）”双模式分发，兼顾托管更新与自定义需求。
- 内置 ADR（架构决策记录）机制（如 `.agents/adr/`），展示工程化演进思路，未来计划支持 Codex 原生插件。

---
## 3. [AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi)
- **语言**: Rust
- **Stars**: 11,937
- **简介**: ⚡️A native, local-first alternative to Logitech Options+, written in Rust 🦀 — remap buttons, DPI, and SmartShift over HID++. No account, no telemetry.

### AI 总结
**简介**: OpenLogi 是一个用 Rust 编写的本地优先 Logitech Options+ 替代品，通过 HID++ 和 UVC 协议解锁罗技鼠标、键盘和摄像头的全部功能，无需账号和遥测。

**核心功能**:
- **设备管理**: 支持 Logi Bolt/Unifying 接收器、蓝牙或有线连接，显示电量和充电状态
- **鼠标增强**: 按键重映射（含中键、模式切换键、拇指滚轮）、手势绑定、8 格操作环（Actions Ring）、DPI 预设与循环、SmartShift 滚轮模式切换、原生滚轮方向反转
- **键盘功能**: 全局 F 键重映射（支持文本输入、组合键、多步骤工作流）、静态 RGB 灯光控制
- **摄像头控制**: 支持任意罗技 UVC 摄像头（Brio、StreamCam、C920 系列），实时预览（仅在查看时占用摄像头）、硬件级图像参数调节（变焦、对焦、曝光、白平衡等）、一键配置文件（默认/直播/视频通话）
- **跨平台**: 支持 macOS、Linux 和 Windows，Linux 为一等平台
- **配置与脚本**: 纯文本 TOML 配置，可跨机器同步；提供 GUI 和 CLI 双界面

**技术亮点**: 原生 Rust + GPUI 框架，保持轻量；通过 OS 输入钩子实现按键捕获，支持按应用自动切换配置（macOS/Windows，Linux 仅 X11/XWayland）；摄像头控制直接写入 UVC 硬件，适用于 Meet/Zoom/OBS 等所有应用；媒体键在 Linux 上使用 D-Bus MPRIS。

---
## 4. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 274,978
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码代理（Coding Agent）的完整软件开发方法论，基于一组可组合的技能（Skills）构建，让 AI 代理在开发过程中自动遵循规范化的流程，从需求梳理到测试驱动开发，实现长时间自主工作。

**核心功能**:
- **自动触发的工作流**: 代理启动后不会直接写代码，而是先引导用户明确真实目标，逐步提炼出规格说明（Spec），并以小段可读形式展示给用户确认。
- **实现计划生成**: 设计确认后，代理会生成一份清晰、可执行的实现计划，强调真正的红/绿 TDD（测试驱动开发）、YAGNI（你不需要它）和 DRY（不要重复自己）原则。
- **子代理驱动开发（Subagent-Driven Development）**: 用户批准后，代理会启动子代理逐个完成工程任务，并持续检查和审查工作，可自主连续工作数小时而不偏离既定计划。
- **多平台插件支持**: 提供针对多种主流编码工具（Claude Code、Cursor、Gemini CLI、GitHub Copilot CLI、Codex、Devin CLI 等）的安装方式，可分别独立安装。

**技术亮点**:
- 基于 Shell 语言实现，采用可组合技能（Composable Skills）架构，技能可触发自动激活，无需用户额外操作。
- 支持通过官方插件市场（如 Claude 和 Codex）或直接仓库安装，兼容 CLI 和 GUI 多种开发环境。

---
## 5. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 4,099
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，为开发者工具、框架和 SaaS 产品提供标准化的 Agent 插件，每个插件独立成目录并包含 `plugin.json` 清单文件。

**核心功能**:
- **开发工具类插件**: 提供持续学习、团队协作、代码审查（Thermos 深度安全审查）、PR 渲染画布、文档可视化画布、CLI 设计模式、并行 Agent 编排（Orchestrate）等插件
- **生产力集成插件**: 集成 Gmail、Google Drive、Google Calendar 等日常办公工具，支持邮件管理、文件搜索与共享、会议调度
- **第三方服务集成插件**: 覆盖 Salesforce、HubSpot、Intercom、Zoom、Docusign、Navan、Outreach 等主流 SaaS 平台，支持数据查询、记录更新、流程管理
- **招聘与销售场景插件**: 提供 Ashby 候选人管理、Gong 交易洞察、Clay 人脉丰富、Juicebox 招聘分析等垂直场景工具
- **浏览器自动化插件**: 通过 Playwright 实现真实浏览器中的导航、点击、截图和测试操作

**技术亮点**: 基于 TypeScript 开发，采用统一的 `plugin.json` 清单规范；插件分为官方自研（Cursor）和第三方贡献（如 Lauren Tan 的 pstack）；支持 CLI 兼容性扫描、SDK 开发、并行云 Agent 编排等高级特性；内置 `create-plugin` 脚手架工具用于快速创建和验证新插件。

---
## 6. [santifer/career-ops](https://github.com/santifer/career-ops)
- **语言**: JavaScript
- **Stars**: 66,722
- **简介**: Open-source AI job search: scan job portals, evaluate listings with a structured A-F rubric into a 1.0-5.0 score, tailor your CV, track applications — runs locally in your AI coding CLI (Claude Code, Codex, OpenCode, Antigravity…)

### AI 总结
**简介**: career-ops 是一个开源 AI 求职系统，在本地 AI 编程 CLI 中运行，自动扫描职位门户、按 A-F 评分标准评估职位、定制简历并跟踪申请进度。

**核心功能**:
- **职位扫描与评估**: 自动抓取职位列表，使用结构化 A-F 评分标准（对应 1.0-5.0 分）评估职位匹配度
- **简历定制**: 根据职位要求自动生成个性化简历（已生成 100+ 份定制 CV）
- **申请跟踪**: 系统化管理求职申请流程，全程在本地 CLI 环境中运行
- **多平台兼容**: 支持 Claude Code、Codex、OpenCode、Antigravity、Qwen、Kimi、GitHub Copilot 等多种 AI 编码 CLI

**技术亮点**:
- 基于 Node.js 构建，支持 Go 扩展，使用 Playwright 进行网页自动化
- 采用多智能体（Multi-Agent）架构设计，将求职流程工程化
- 纯本地运行，保护用户隐私数据
- 已被 WIRED、Business Insider 等媒体专题报道，在 Product Hunt 和 Trendshift 上获得推荐

---
## 7. [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory)
- **语言**: Rust
- **Stars**: 3,641
- **简介**: Solution for long term memory for agent coding CLIs and to facilitate handoff between different agent vendors

### AI 总结
**简介**: ai-memory 是一个为 AI 编码代理提供长期记忆的 Rust 工具，让用户可以在不同代理工具（如 Claude Code、OpenAI Codex）之间无缝切换，无需重新解释架构、失败方案或待解决问题。

**核心功能**:
- **跨代理记忆持久化**: 在 Claude Code 中途退出任务，切换到 Codex 后能继续工作，无需重复说明上下文
- **多代理支持**: 支持 Claude Code、Codex、Command Code、Devin CLI、OpenCode、Cursor、Gemini CLI、Pi、OpenClaw、Antigravity CLI 等主流 AI 编码工具
- **生命周期钩子集成**: 通过 MCP 配置和生命周期钩子自动捕获对话上下文，实现会话间无缝衔接
- **会话最终化**: 提供 `finalize-session` 命令生成最终摘要和交接文档，便于代理间切换
- **托管工作流**: `ai-memory run` 提供跨工具链的透明连续性，支持多种代理引擎
- **跨平台支持**: 支持 Linux（含 Docker）、macOS（原生二进制）、Windows（WSL2 及实验性原生支持）

**技术亮点**: 基于 Rust 开发，采用 MCP（Model Context Protocol）架构实现代理集成，通过生命周期钩子机制自动捕获会话上下文；支持会话感知的自动作用域隔离（`--session-aware`）；提供原生二进制分发和 Docker 镜像，支持多架构（amd64/arm64）发布。

---
## 8. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)
- **语言**: Python
- **Stars**: 113,013
- **简介**: 利用 AI 大模型和自动化工作流，根据主题或关键词一键生成高清短视频。Generate HD short videos from a topic or keyword with an automated AI workflow.

### AI 总结
**简介**: MoneyPrinterTurbo 是一款基于 AI 大模型和自动化工作流的一站式短视频生成工具，只需提供主题或关键词，即可自动完成脚本撰写、素材匹配、字幕生成、背景音乐合成并输出高清短视频。

**核心功能**:
- **一键生成视频**：输入主题或关键词，自动完成从文案到成片的完整流程
- **智能脚本撰写**：利用 AI 大模型（如 Kimi K3、GPT、Claude 等）生成视频文案，并提炼素材搜索关键词
- **自动化素材匹配**：根据文案内容自动搜索并匹配高清视频素材
- **字幕与配音**：自动生成字幕并合成背景音乐，支持多语言输出
- **双界面支持**：提供 WebUI 图形界面和 API 接口，方便不同使用场景

**技术亮点**:
- 基于 Python 3.11+ 开发，支持 Windows、macOS、Linux 跨平台运行
- 兼容多种主流 LLM（OpenAI、Claude、Gemini、DeepSeek、Qwen 等），通过标准接口灵活切换
- 集成火山引擎、Kimi 等多家 AI 服务商，支持多模态模型（文本、视觉、图像生成）
- 开源项目，拥有活跃的社区和持续的版本迭代，支持通过 API 进行二次开发集成

---
## 9. [agent-substrate/substrate](https://github.com/agent-substrate/substrate)
- **语言**: Go
- **Stars**: 1,407
- **简介**: Agent Substrate: the core system

### AI 总结
**简介**: Agent Substrate 是一个面向大规模智能体（Agent）部署的高性能、高密度运行时环境，通过将大量有状态“演员”（Actors）映射到少量就绪“工人”（Workers）上，实现资源的高效复用。

**核心功能**:
- **全生命周期管理**: 提供智能体沙箱的完整生命周期管理，包括创建、销毁、挂起和恢复操作。
- **亚秒级挂起/恢复**: 支持亚秒级的智能体恢复/挂起操作，实现“即时演员传送”。
- **高密度多路复用**: 支持将大量有状态智能体复用映射到少量物理 Pod 上，演示中实现了 30 倍以上的超额订阅。
- **状态持久化**: 通过全状态快照，在休眠周期内完美保留易失性 RAM 和文件系统状态。
- **多沙箱技术支持**: 支持 microVM 和 gVisor 等多种沙箱技术，提供一致的生命周期操作。
- **实时调度与路由**: 实时将智能体分配到可用工人，并路由传入流量。

**技术亮点**: 基于 Kubernetes 构建，利用 Pod 和 Pod 自动扩缩容能力；框架无关，支持 ADK、LangChain、Claude Code、CodeX 及 MCP 等生态；采用 gVisor 内核级隔离，可托管任何技术栈构建的智能体；当前处于早期开发阶段，支持最新的 Kubernetes 稳定版及上一个次要版本。

---
## 10. [chaitanyagiri/munder-difflin](https://github.com/chaitanyagiri/munder-difflin)
- **语言**: TypeScript
- **Stars**: 3,141
- **简介**: local multi-agent harness

### AI 总结
**简介**: Munder Difflin 是一个免费开源的本地多智能体（multi-agent）桌面应用，它将你已有的终端编码 CLI（如 Claude Code、Codex、Grok 等）包装成可自我协作的“智能体办公室”，由你的数字克隆“Michael”统一调度，在你离开时持续工作。

**核心功能**:
- **终端即智能体**：每个 `claude`、`codex`、`grok`、`qwen` 等会话作为真实进程运行在伪终端中，通过 xterm.js 渲染，字节级还原真实体验。
- **智能体可视化**：每个智能体以 Pixi.js 绘制的头像呈现在 2D 办公室地板上，工作时走动到工位，互发消息时信封在桌间飞舞。
- **蜂群式协调**：智能体读取长期记忆并处理邮箱消息；路由器在收件箱间传递消息；GOD 智能体（Michael）负责分配任务、裁决冲突，仅在必要时升级给你。
- **瞬时记忆层**：基于 Markdown 的记忆系统配合语义检索索引，让智能体跨会话记忆，毫秒级召回。
- **自带密钥与本地 LLM 支持**：支持 BYOK（自带密钥）及本地大模型接入。

**技术亮点**: 基于 Electron、React、TypeScript、Pixi.js、xterm.js 和 node-pty 构建；采用“Markdown 优先 + 语义索引”的记忆架构；跨平台支持 macOS、Windows、Linux；目前为可工作的原型版本（v0.4.4），采用 MIT 许可证，欢迎贡献 PR。

---
