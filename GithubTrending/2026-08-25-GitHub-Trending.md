---
tags:
  - github-trending
  - daily
date: 2026-08-25
created: 2026-08-25T01:55:44.261Z
---

# 2026-08-25 GitHub Trending Top 10

## 1. [Alishahryar1/free-claude-code](https://github.com/Alishahryar1/free-claude-code)
- **语言**: Python
- **Stars**: 49,029
- **简介**: Use Claude Code, Codex, Pi, and OpenCode for free (1.3B+ free tokens) from your terminal, app, IDE, or phone like OpenClaw (voice supported + ToS friendly)

### AI 总结
**简介**: 一个开源工具，让用户通过统一界面免费使用 Claude Code、Codex 等 9 种编码代理和 50 多个模型提供商（每月 13 亿+免费 token），支持终端、桌面、IDE 和手机等多种使用场景。

**核心功能**:
- **多提供商聚合**: 整合 50 多个 ToS 友好的模型提供商，支持免费、付费、订阅和本地模型，每月可获取 13 亿+免费 token
- **多代理支持**: 兼容 Claude Code、Codex、Pi、OpenCode、Cline 等 9 种主流编码代理，共享统一模型目录
- **智能故障转移**: 提供商中断时自动切换至下一个配置的模型，无需重启当前对话
- **Token 优化**: 可选 RTK 过滤终端输出，配合 5 项 FCC 优化可减少最多 90% 的终端输出 token 消耗
- **多端访问**: 支持原生启动器、VS Code、JetBrains、Discord、Telegram 等多种客户端
- **语音输入**: 支持本地 Whisper 或 NVIDIA NIM 语音转文字，可直接语音与代理交互
- **完整代理能力**: 保留流式响应、工具调用、图片输入、交错思考等原生功能，可独立路由不同 Claude 模型

**技术亮点**: 基于 Python 3.14 开发，使用 uv 包管理、Pytest 测试、Ruff 代码格式化、Loguru 日志和 Ty 类型检查；提供跨平台安装脚本（macOS/Linux/Windows），内置 Admin UI 管理界面，支持系统托盘/菜单栏操作。

---
## 2. [openai/codex](https://github.com/openai/codex)
- **语言**: Rust
- **Stars**: 117,131
- **简介**: Lightweight coding agent that runs in your terminal

### AI 总结
**简介**: Codex CLI 是 OpenAI 推出的轻量级编程代理，可直接在终端中运行，帮助开发者高效完成编码任务。

**核心功能**:
- 终端内运行：作为本地命令行工具，无需离开终端即可使用 AI 编程助手
- 多平台安装：支持 Mac、Linux 和 Windows，提供脚本安装、包管理器（npm、Homebrew）及 GitHub Releases 二进制下载
- 灵活认证：支持使用 ChatGPT 账户（Plus/Pro/Business/Edu/Enterprise 计划）或 API 密钥登录
- 多场景适配：提供 IDE 插件（VS Code、Cursor、Windsurf）和桌面应用（`codex app`）版本

**技术亮点**: 使用 Rust 编写，性能高效；支持通过环境变量配置安装源（默认 OpenAI 官方源，可回退至 GitHub Releases）；采用 Apache-2.0 开源协议，便于社区贡献和二次开发。

---
## 3. [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)
- **语言**: Python
- **Stars**: 34,119
- **简介**: The job search that runs on your machine. AI job application framework built on Claude Code: evaluate postings, tailor CVs, write cover letters, prep interviews. Fork it and own it.

### AI 总结
**简介**: 一个基于 Claude Code 的 AI 求职应用框架，可本地运行，帮助求职者评估职位、定制简历、撰写求职信并准备面试。

**核心功能**:
- **职位搜索与筛选** (`/scrape`)：通过 CLI 工具搜索丹麦主流求职门户（Jobindex、Jobnet 等），展示匹配度评分
- **职位适配评估** (`/apply <url>`)：AI 评估职位与个人档案的匹配度，给出评分与推荐
- **简历定制生成**：自动生成定制化 LaTeX 简历（使用 `lualatex` 编译），并含 ATS 可解析性检查
- **求职信自动撰写**：通过 drafter-reviewer 双智能体流水线生成并优化求职信（`xelatex` 编译）
- **面试准备**：基于职位描述和个人档案生成针对性面试问题与准备材料
- **个人档案管理** (`/setup`)：填写个人资料生成结构化档案文件，驱动整个工作流

**技术亮点**:
- 基于 Claude Code CLI，可替换为 Codex、Gemini CLI 等其他智能体工具
- 核心工作流（自我画像、匹配评估、草稿-评审流水线）语言/国家无关，可适配本地求职门户
- Python 3.10+ / Bun / LaTeX（TeX Live 等）技术栈
- 内置职业指导最佳实践：结构化评估标准、前瞻性求职信框架、可选薪资基准对比

---
## 4. [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills)
- **语言**: Unknown
- **Stars**: 206,560
- **简介**: A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.

### AI 总结
**简介**: 一个基于 Andrej Karpathy 对 LLM 编码缺陷观察的单一 CLAUDE.md 文件，用于改善 Claude Code 的编码行为。

**核心功能**:
- **Think Before Coding**: 要求模型明确陈述假设、呈现多种解释、在困惑时停止并提问，避免盲目假设和隐藏困惑
- **Simplicity First**: 强制最小化代码实现，禁止过度设计、不必要的抽象和投机性功能
- **Surgical Changes**: 限制修改范围，只改动与任务直接相关的代码，不触碰无关代码或注释
- **Goal-Driven Execution**: 将命令式任务转化为可验证的成功标准，通过测试驱动循环执行直到验证通过

**技术亮点**:
- 以单一配置文件（CLAUDE.md）形式集成，支持通过 Claude Code 插件市场安装或直接 curl 下载
- 附带 Cursor 项目规则（.cursor/rules），实现跨工具的一致性编码规范
- 提供清晰的"替代/转换"表格，指导如何将模糊任务转化为可验证目标

---
## 5. [makeplane/plane](https://github.com/makeplane/plane)
- **语言**: TypeScript
- **Stars**: 57,959
- **简介**: 🔥🔥🔥 Open-source Jira, Linear, Monday, and ClickUp alternative. Plane is a modern project management platform to manage tasks, sprints, docs, and triage.

### AI 总结
**简介**: Plane 是一个开源的现代化项目管理平台，可替代 Jira、Linear、Monday 和 ClickUp，帮助团队高效管理任务、迭代周期、文档和问题分类。

**核心功能**:
- **工作项管理**: 使用富文本编辑器创建和管理任务，支持文件上传、子属性设置及关联问题引用
- **周期追踪**: 通过燃尽图等可视化工具跟踪迭代进度，保持团队动力
- **模块拆分**: 将复杂项目分解为更小、更易管理的模块
- **自定义视图**: 通过过滤器定制工作流，仅展示相关任务，并支持保存和分享视图
- **页面功能**: 内置 AI 能力的富文本页面，可格式化文本、插入图片/链接，或将笔记转换为可执行任务
- **数据分析**: 提供跨项目实时洞察，可视化趋势并识别阻碍因素

**技术亮点**: 基于 TypeScript 构建，前端采用 React Router，后端使用 Django 框架，并支持 Node.js；提供 Docker、Kubernetes 等多种自托管部署方式，同时支持云端快速启动。

---
## 6. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 235,841
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是由 Nous Research 打造的自进化 AI 代理，内置学习闭环，能跨会话积累经验、自主创建技能并持续优化，支持在低成本 VPS 或云端运行。

**核心功能**:
- **终身学习闭环**: 自动从经验中创建技能、使用中自我改进，定期记忆沉淀，支持跨会话搜索历史对话并构建用户画像
- **多平台接入**: 通过单一网关同时支持 Telegram、Discord、Slack、WhatsApp、Signal 和 CLI，支持语音备忘录转写和跨平台对话连续性
- **真实终端界面**: 完整 TUI，支持多行编辑、斜杠命令自动补全、对话历史、中断重定向和流式工具输出
- **定时自动化**: 内置 cron 调度器，可用自然语言设置每日报告、夜间备份、每周审计等无人值守任务
- **子代理并行**: 可生成隔离子代理处理并行工作流，支持通过 RPC 编写 Python 脚本调用工具，将多步流水线压缩为零上下文消耗
- **灵活部署**: 支持本地、Docker、SSH、Singularity、Modal、Daytona、Vercel Sandbox 七种终端后端，其中 Daytona 和 Modal 提供无服务器持久化，空闲时休眠、按需唤醒
- **研究就绪**: 支持批量轨迹生成和轨迹压缩，用于训练下一代工具调用模型

**技术亮点**: 模型无关设计（支持 Nous Portal、OpenRouter、OpenAI 及自定义端点，切换无需改代码）；采用 FTS5 会话搜索 + LLM 摘要实现跨会话记忆；兼容 agentskills.io 开放技能标准；集成 Honcho 辩证用户建模。

---
## 7. [anthropics/claude-plugins-community](https://github.com/anthropics/claude-plugins-community)
- **语言**: Python
- **Stars**: 1,374
- **简介**: Community plugin marketplace for Claude Cowork and Claude Code. Read-only mirror — submit plugins at clau.de/plugin-directory-submission.

### AI 总结
**简介**: 这是 Anthropic 官方维护的 Claude Cowork 与 Claude Code 社区插件市场镜像仓库，收录了通过安全审核的社区插件列表。

**核心功能**:
- 提供社区插件的统一市场清单（`.claude-plugin/marketplace.json`），每晚自动同步自 Anthropic 内部审核管道
- 支持 Claude Cowork 用户通过 [claude.com/plugins](https://claude.com/plugins/) 直接安装插件
- 支持 Claude Code 用户通过命令行添加市场并安装插件（`claude plugin marketplace add` / `claude plugin install`）
- 插件提交入口统一指向 [clau.de/plugin-directory-submission](https://clau.de/plugin-directory-submission)，不接收直接 Pull Request

**技术亮点**: 采用只读镜像架构，所有插件变更均从内部审核管道流入，确保安全性与可控性；插件需通过自动化安全扫描后方可上架。

---
## 8. [AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi)
- **语言**: Rust
- **Stars**: 15,909
- **简介**: ⚡️A native, local-first alternative to Logitech Options+, written in Rust 🦀 — remap buttons, DPI, and SmartShift over HID++. No account, no telemetry.

### AI 总结
**简介**: OpenLogi 是一个用 Rust 编写的本地优先、原生 Logitech Options+ 替代品，通过 HID++ 和 UVC 协议解锁罗技鼠标、键盘和摄像头的全部功能，无需账户和遥测。

**核心功能**:
- **鼠标**: 按钮重映射（含中键、模式切换键和拇指滚轮）、任意按钮手势绑定、光标中心八槽操作环、DPI 预设与控制、SmartShift 滚轮模式切换、原生滚动方向反转
- **键盘**: 全局 F 键重映射（支持键入文本、组合键、多步骤工作流）、静态 RGB 灯光控制
- **摄像头**: 罗技 UVC 摄像头即插即用支持，实时预览（仅在观看时占用摄像头），直接写入硬件的图像控制（变焦、对焦、曝光、亮度、白平衡等）
- **跨平台**: 支持 macOS、Linux（一等公民）和 Windows，设备连接方式涵盖 Bolt 接收器、Unifying 接收器、蓝牙和有线
- **配置与自动化**: 纯文本 TOML 配置（可跨机器同步）、每应用配置覆盖层（自动切换）、CLI 命令行工具

**技术亮点**: 原生 Rust + GPUI 框架，保持轻量；通过 OS 输入钩子实现按钮重映射；直接与 HID++ 硬件协议通信，支持 UVC 硬件级图像控制；提供 GUI 与 CLI 双界面。

---
## 9. [apache/maka](https://github.com/apache/maka)
- **语言**: TypeScript
- **Stars**: 2,933
- **简介**: Apache Maka (Incubating) is a local-first AI agent workspace. Model messages, tool calls, tool results, permission decisions, and termination events are recorded as an append-only log.

### AI 总结
**简介**: Apache Maka (Incubating) 是一个本地优先的 AI Agent 工作空间，将模型消息、工具调用、权限决策等执行过程记录为可恢复的追加日志。

**核心功能**:
- **本地优先架构**: 会话、设置和运行记录默认保存在本地，用户自带模型（云 API、本地模型或兼容网关）
- **完整执行记录**: 模型消息、工具调用、工具结果及回合终止方式均被持久化记录，UI 和后续模型调用只是该记录的不同视图
- **上下文压缩不丢历史**: 可从提示中省略旧工具输出，但保留已保存的证据
- **统一 Runtime Host**: 桌面端、终端 CLI 和评估系统共用同一运行核心
- **内置工具集**: 包含 Read、Write、Edit、Bash、Glob、Grep 等工具，沙箱外操作需审批，运行可中止
- **多端入口**: 提供桌面应用（Electron + React）、TUI/CLI 和可复现的 Eval 评估系统

**技术亮点**: 基于 TypeScript 开发，采用 Electron + React 桌面架构，支持流式会话、工具时间线、分支、搜索和崩溃恢复；遵循 Apache 2.0 许可，当前处于 Apache 孵化器阶段，macOS Apple Silicon 已发布早期公开版本，Windows 提供预览版，Linux 支持即将推出。

---
## 10. [PostHog/posthog](https://github.com/PostHog/posthog)
- **语言**: Python
- **Stars**: 39,010
- **简介**: 🦔 PostHog is the leading platform for building self-driving products. Our developer tools – AI observability, analytics, session replay, flags, experiments, error tracking, logs, and more – capture all the context agents need to diagnose problems, uncover opportunities, and ship fixes. Steer it all from Slack, web, desktop, or the MCP.

### AI 总结
**简介**: PostHog 是一个开源的产品分析平台，旨在帮助开发者构建“自动驾驶”产品，通过捕获和分析用户数据、错误、日志等上下文信息，实现问题诊断、机会发现和修复推送。

**核心功能**:
- **产品分析**: 自动捕获或手动埋点事件，通过可视化或 SQL 分析用户行为
- **会话重放**: 观看真实用户与网站或移动应用的交互，诊断问题并理解用户行为
- **功能开关**: 安全地向特定用户或群体逐步发布新功能
- **实验**: 测试变更并通过统计方法衡量其对目标指标的影响，支持无代码设置
- **错误追踪**: 追踪错误、接收警报并解决问题以改进产品
- **日志管理**: 收集、搜索和分析日志数据，并与产品数据关联
- **AI 可观测性**: 捕获 LLM 应用的追踪、生成、延迟和成本信息
- **数据仓库与管道**: 同步外部工具数据，自定义过滤和转换，实时或批量导出至 25+ 工具
- **问卷调查**: 使用无代码模板或自定义构建器收集用户反馈
- **自助驾驶模式**: 将产品数据中的信号（错误、愤怒点击等）自动转化为研究报告和可审查的拉取请求

**技术亮点**:
- 基于 Python 开发，支持 Docker 部署
- 提供 Slack、Web、桌面端和 MCP（Model Context Protocol）多种交互方式
- 支持自托管（开源版）和云服务（PostHog Cloud US/EU）两种部署模式
- 提供慷慨的免费月度额度，各工具均可免费使用

---
