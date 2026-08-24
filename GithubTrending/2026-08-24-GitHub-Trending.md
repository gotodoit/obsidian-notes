---
tags:
  - github-trending
  - daily
date: 2026-08-24
created: 2026-08-24T01:55:44.620Z
---

# 2026-08-24 GitHub Trending Top 10

## 1. [openai/codex](https://github.com/openai/codex)
- **语言**: Rust
- **Stars**: 115,348
- **简介**: Lightweight coding agent that runs in your terminal

### AI 总结
**简介**: Codex CLI 是 OpenAI 推出的轻量级编码代理，直接运行在终端中，帮助开发者通过自然语言完成编程任务。

**核心功能**:
- 终端原生交互：在本地命令行中直接运行，无需离开终端环境
- 多平台支持：提供 macOS、Linux 和 Windows 的安装方式，并支持 npm、Homebrew 等包管理器
- ChatGPT 账号集成：可使用 Plus、Pro、Business 等订阅计划直接登录使用
- 多种安装选项：支持官方脚本安装、GitHub Releases 二进制下载及包管理器安装
- 桌面应用扩展：可通过 `codex app` 命令或 IDE 插件（VS Code、Cursor 等）获得更丰富的使用体验

**技术亮点**:
- 使用 Rust 语言开发，性能高效且启动快速
- 支持多种安装渠道，包括官方 CDN 和 GitHub Releases 自动回退机制
- 提供跨平台静态编译的二进制文件（如 musl 版本），便于分发和部署
- 采用 Apache-2.0 开源许可，支持社区贡献

---
## 2. [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2)
- **语言**: JavaScript
- **Stars**: 12,849
- **简介**: Prompt as Code | GPT-Image2 工业级提示词引擎与模板库，470+ 个案例逆向工程，20+ 套工业级模板，并提炼出Skills，持续更新中

### AI 总结
**简介**: 一个面向 GPT-Image2 的工业级提示词引擎与模板库，通过逆向工程 500+ 真实案例提炼出可复用的 Prompt 模板和 Skills，倡导 "Prompt as Code" 理念。

**核心功能**:
- **532 个逆向工程案例库**：基于真实 GPT-Image2 生成案例进行反向拆解，提炼高质量提示词写法
- **20+ 工业级模板**：覆盖多种风格与场景的即用型 Prompt 模板，持续更新中
- **可视化画廊网站**：提供在线浏览、大图预览、一键复制完整提示词、按风格/场景筛选，支持 Google 登录后在线测试生成
- **付费社区**：提供专属讨论群（一次性 ¥9.90 支付宝付费），用于交流 Prompt 技巧和获取更新
- **多语言支持**：提供英文、简体中文、日文文档

**技术亮点**: 项目采用 JavaScript 构建，配套可视化站点（gpt-image2.canghe.ai）提供产品级浏览体验；模板设计遵循 "Prompt as Code" 工程化思想，将提示词视为可复用、可版本管理的代码资产；支持通过异步 API 批量生成图像（配合赞助商平台），并兼容 Remote MCP 和 Agent Skills 接入 Claude Code 与 Cursor 等 AI 编程工具。

---
## 3. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 233,931
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: 这是 Matt Pocock 开源的日常工程实践 Agent Skills 集合，旨在帮助开发者用 AI 编码代理完成真实软件工程，而非“vibe coding”。

**核心功能**:
- 提供可组合、易修改的小型 Skills，适用于 Claude Code、Codex 等任意编码代理
- 核心命令 `/grill-me` 和 `/grill-with-docs`：通过“拷问式”提问对齐需求，解决代理误解指令的问题
- `/setup-matt-pocock-skills` 一键初始化：配置 issue 追踪器（GitHub/Linear/本地）、标签系统和文档存储位置
- 支持两种安装方式：Claude Code 插件（自动更新）或 `npx skills` 命令（可编辑、可 hack）
- 内置 `/triage` 等基于标签的工单管理流程

**技术亮点**: 基于数十年工程经验提炼，采用“小而精、可组合”的设计哲学，区别于 GSD/BMAD 等重流程方案，保持开发者控制权；支持跨模型通用，并附带 ADR 文档记录架构决策。

---
## 4. [basecamp/omarchy](https://github.com/basecamp/omarchy)
- **语言**: Shell
- **Stars**: 29,174
- **简介**: Beautiful, Modern & Opinionated Linux

### AI 总结
**简介**: Omarchy 是由 DHH 开发的一款美观、现代且高度定制化的 Linux 发行版，主打开箱即用的优雅体验。

**核心功能**:
- 提供精心设计的默认桌面环境与视觉风格，强调美观与现代化
- 内置“有主见”的默认配置，减少用户手动调优成本
- 面向开发者的优化，适合快速搭建高效工作流
- 官方文档与网站（omarchy.org）提供完整使用指南

**技术亮点**: 基于 Shell 脚本构建，采用 MIT 开源协议；以“Opinionated”为核心理念，通过预置配置实现开箱即用，适合追求效率与一致性的开发者。

---
## 5. [AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi)
- **语言**: Rust
- **Stars**: 14,996
- **简介**: ⚡️A native, local-first alternative to Logitech Options+, written in Rust 🦀 — remap buttons, DPI, and SmartShift over HID++. No account, no telemetry.

### AI 总结
**简介**: OpenLogi 是一个用 Rust 编写的本地优先 Logitech Options+ 替代品，通过 HID++ 和 UVC 协议解锁罗技鼠标、键盘和网络摄像头的全部功能，无需账号和遥测。

**核心功能**:
- **设备管理**: 支持 Logi Bolt、Unifying 接收器、蓝牙或有线连接，显示电池电量和充电状态
- **鼠标功能**: 中键/拇指滚轮捕获与重映射、手势绑定、Actions Ring 八槽操作环、DPI 预设与循环、SmartShift 滚轮模式切换、滚动方向反转
- **键盘功能**: 全局 F 键重映射（支持文本输入、组合键、多步工作流）、静态 RGB 灯光控制
- **摄像头功能**: 任意罗技 UVC 摄像头即插即用、实时预览（离开即释放摄像头）、UVC 硬件级图像控制（变焦/对焦/曝光/白平衡等）、一键配置预设
- **跨平台**: 支持 macOS、Linux 和 Windows，Linux 为一等公民
- **轻量原生**: 使用 Rust + GPUI，比 Options+ 更轻量
- **纯文本配置**: 所有配置存储在一个 TOML 文件中，方便跨机器同步
- **应用级配置覆盖**: 按应用自动切换配置（macOS + Windows；Linux 仅 X11/XWayland）
- **CLI 支持**: 提供图形界面之外的命令行工具

**技术亮点**: 基于 Rust 编写，使用 GPUI 原生界面框架，通过 HID++ 协议与罗技设备通信，通过 UVC 协议直接控制摄像头硬件，采用 OS 输入钩子实现按键重映射。

---
## 6. [block/buzz](https://github.com/block/buzz)
- **语言**: Rust
- **Stars**: 30,134
- **简介**: A hive mind communication platform

### AI 总结
**简介**: Buzz 是一个自托管的协作工作区，让人类和 AI 代理在同一个“房间”里共同工作，底层基于 Nostr 中继协议，所有消息和操作均为签名事件。

**核心功能**:
- **人机协作空间**: 人类和 AI 代理共享频道，代理可像团队成员一样被添加、互动和响应
- **代理自治权限**: 代理拥有独立密钥、频道成员身份和审计轨迹，可安全地分诊 bug、运行工作流、审查代码，无需授予人类权限
- **功能分支即频道**: 将补丁、CI、审查和合并决策汇聚在一个房间，频道即代码变更的完整记录
- **统一事件搜索**: 跨对话、补丁、工作流运行和审批进行一站式搜索，因为它们本质上是同类型事件
- **媒体帧级评论**: 支持在视频等媒体的特定帧上锚定评论，便于精确讨论
- **代理全功能操作**: 代理可创建频道、编辑画布、运行工作流、发起语音会议、协调其他代理，与人类拥有相同操作面

**技术亮点**: 基于 Rust 实现，采用 Nostr 中继协议作为统一事件日志——所有消息、反应、工作流步骤、审查批准和 git 事件均为签名事件，同一身份模型、同一审计轨迹，适用于人和流程。默认单中继部署支持单社区，多租户托管模式下各社区保持语义隔离。

---
## 7. [apache/maka](https://github.com/apache/maka)
- **语言**: TypeScript
- **Stars**: 2,369
- **简介**: Apache Maka (Incubating) is a local-first AI agent workspace. Model messages, tool calls, tool results, permission decisions, and termination events are recorded as an append-only log.

### AI 总结
**简介**: Apache Maka (Incubating) 是一个本地优先的 AI Agent 工作空间，将模型消息、工具调用、工具结果、权限决策和终止事件记录为追加式日志，旨在为真实工作构建可靠、可恢复的 Agent 执行环境。

**核心功能**:
- **本地优先数据管理**: 会话、设置和运行记录默认保存在本地，用户自带模型（云 API、本地模型或兼容网关）
- **持久化执行记录**: 模型消息、工具调用、工具结果及回合结束方式均被完整记录，UI 和后续模型调用只是该记录的视图
- **上下文压缩不丢历史**: 可从下一轮提示中省略旧工具输出，但保留已保存的证据，不删除历史
- **统一运行时宿主 (Runtime Host)**: 桌面端、终端和评估系统共用同一运行时，确保执行一致性
- **多交互界面**: 提供桌面应用（Electron + React，支持流式会话、工具时间线、分支、搜索和恢复）、TUI/CLI 和 Eval 基准测试工具
- **内置工具集**: 包含 Read、Write、Edit、Bash、Glob、Grep 等工具，Computer Use 和目录技能为可选功能
- **沙箱安全边界**: 离开沙箱的工具操作需审批，运行可中止，失败会被分类处理

**技术亮点**: 基于 TypeScript 构建，采用追加式日志（append-only log）作为核心执行记录机制；桌面端使用 Electron + React 架构；支持多模型连接和流式输出；遵循 Apache 2.0 许可证，当前处于 Apache 孵化器阶段，支持 macOS Apple Silicon（早期公开版）、Windows 预览版，Linux 即将支持。

---
## 8. [Alishahryar1/free-claude-code](https://github.com/Alishahryar1/free-claude-code)
- **语言**: Python
- **Stars**: 48,007
- **简介**: Use Claude Code, Codex, Pi, and OpenCode for free (1.3B+ free tokens) from your terminal, app, IDE, or phone like OpenClaw (voice supported + ToS friendly)

### AI 总结
**简介**: 一个开源工具，让你免费使用 Claude Code、Codex、Pi 等 9 种编码代理，通过 49 个合规提供商每月获取 13 亿+免费 token，支持在终端、桌面、IDE 或手机端使用。

**核心功能**:
- **多提供商聚合**: 集成 49 个 ToS 友好的免费/付费/订阅/本地模型提供商，统一搜索界面管理，自动移除被禁止的集成
- **多代理支持**: 支持 Claude Code、Codex、Pi、OpenCode、Cline、Hermes、DeepSeek Harness、Grok Build、Muse Code 等 9 种编码代理
- **故障自动切换**: 提供商中断时自动尝试下一个配置的模型，无需重启对话
- **Token 优化**: 可选 RTK 过滤终端输出，5 项 FCC 优化（配额探测、命令前缀检测等）无需调用提供商即可减少最多 90% 输出 token
- **多端接入**: 支持 VS Code、JetBrains、Discord、Telegram、Codex App 等客户端
- **语音输入**: 支持本地 Whisper 或 NVIDIA NIM 语音转文字，语音笔记直接编码
- **完整代理能力**: 保留流式响应、工具调用、思维链展示、图像输入，可独立路由 Fable/Opus/Sonnet/Haiku 模型

**技术亮点**: Python 3.14 开发，使用 uv 包管理、Pytest 测试、Ty 类型检查、Ruff 代码格式化、Loguru 日志；提供跨平台安装脚本（macOS/Linux shell + Windows PowerShell），包含桌面托盘/菜单栏 UI 和 Admin 管理界面。

---
## 9. [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman)
- **语言**: Rust
- **Stars**: 36,784
- **简介**: Your Personal AI super intelligence. A brain that builds a local-first memory of your life, a fantastic orchestrator of agent fleets and workflows, and a deep researcher.

### AI 总结
**简介**: OpenHuman 是一个开源的个人 AI 超级智能体，以本地优先的方式构建你的生活记忆，并作为智能体集群与工作流的编排器及深度研究员。

**核心功能**:
- **脑（记忆）**: 构建持久化的本地记忆系统，记录你的世界与生活数据。
- **编排器（Orchestrator）**: 在持久化图上运行多智能体（agent fleets）与复杂工作流。
- **深度研究员**: 在你完成提问前，自动扫描你的本地数据与网络信息进行深度研究。

**技术亮点**:
- 使用 Rust 编写，强调性能与安全性。
- 本地优先（Local-first）架构，数据存储于本地。
- 处于早期 Beta 阶段，但发布后连续 9 天登顶 GitHub 趋势榜。

---
## 10. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 242,579
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个面向 AI 编程代理（如 Claude Code、Codex 等）的性能优化系统，提供技能、本能、记忆、安全与研究优先的开发能力。

**核心功能**:
- **技能与本能系统**: 为 AI 代理提供可扩展的技能库和自适应行为模式
- **记忆管理**: 支持代理跨会话持久化记忆，提升上下文理解能力
- **安全防护**: 内置 AgentShield 安全模块，防止恶意操作和数据泄露
- **多平台支持**: 兼容 Claude Code、Codex、Opencode、Cursor 等主流 AI 编程工具
- **插件化架构**: 通过插件市场快速安装技能、代理和命令
- **研究优先开发**: 强调可观测性和性能调优，支持深入分析代理行为

**技术亮点**: 采用 TypeScript/JavaScript 构建，提供 npm 包（ecc-universal、ecc-agentshield）和 GitHub App 集成；支持 Shell、Python、Go、Java 等多语言环境；拥有活跃的社区生态（Discord、多语言文档），遵循 MIT 开源协议。

---
