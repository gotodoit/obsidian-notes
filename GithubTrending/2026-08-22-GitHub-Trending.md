---
tags:
  - github-trending
  - daily
date: 2026-08-22
created: 2026-08-22T01:55:44.233Z
---

# 2026-08-22 GitHub Trending Top 10

## 1. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 229,587
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: 这是 Matt Pocock 开源的一套用于真实工程开发的 AI Agent 技能集合，源自其个人 `.agents` 目录，旨在解决编码 Agent 在实际开发中的常见失败模式。

**核心功能**:
- **`/grill-me` 与 `/grill-with-docs`**: 通过“拷问式”提问对齐需求，解决 Agent 误解开发意图的问题，是作者最受欢迎的技能。
- **`/setup-matt-pocock-skills`**: 一次性初始化脚本，配置问题跟踪器（GitHub/Linear/本地文件）、标签规则及文档存储位置。
- **`/triage`**: 基于标签对工单进行分流管理。
- **可组合与可定制**: 技能设计为小型、易适配、可自由修改，且不绑定特定模型。

**技术亮点**:
- 支持两种安装哲学：通过 **Claude Code 插件** 以只读托管包形式订阅自动更新，或通过 **skills.sh** 将可编辑文件复制到本地项目进行定制。
- 基于数十年工程经验（引用《程序员修炼之道》与《领域驱动设计》），强调开发者控制权而非流程接管（区别于 GSD、BMAD 等方案）。
- 使用 Shell 脚本实现，可跨 Claude Code、Codex 等不同 Agent 使用，并规划了原生 Codex 插件支持。

---
## 2. [mahlernim/google-timeline-visualizer](https://github.com/mahlernim/google-timeline-visualizer)
- **语言**: Kotlin
- **Stars**: 2,240
- **简介**: Visualize your year in travel using your Google Location History (Timeline) data

### AI 总结
**简介**: 一个将 Google 位置历史（Timeline）数据转换为动画旅行视频的工具，支持 Android 应用和 iPhone 网页应用两种使用方式。

**核心功能**:
- 导入 Google Timeline JSON 文件，选择日期范围（按月或精确日期）生成旅行路线
- 提供交互式地图预览，支持多种摄像机运动模式和自定义视频时长（10-300 秒）
- 生成 1080×1080 分辨率的 MP4 视频，可直接播放、分享或保存
- 支持视频标题模板（包含 `{year}` 和 `{name}` 变量），可保存用户偏好设置
- 内置 Google Maps Timeline 数据恢复指南，帮助用户找回丢失的历史数据
- 视频渲染支持后台运行，可切换应用或关闭屏幕继续处理

**技术亮点**: 基于 Kotlin 开发的 Android 原生应用（支持 Android 8.0+），同时提供基于 Web 的 iPhone 版本（需 Safari 16.4+ 支持 H.264 编码）。视频渲染采用预先准备地图瓦片的策略，渲染过程分阶段显示进度并估算剩余时间。

---
## 3. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)
- **语言**: Python
- **Stars**: 113,959
- **简介**: 利用 AI 大模型和自动化工作流，根据主题或关键词一键生成高清短视频。Generate HD short videos from a topic or keyword with an automated AI workflow.

### AI 总结
**简介**: MoneyPrinterTurbo 是一款基于 AI 大模型与自动化工作流的一站式短视频生成工具，输入主题或关键词即可自动产出高清短视频。

**核心功能**:
- 自动生成视频脚本：基于 AI 大模型撰写文案
- 智能匹配素材：提取关键词并自动搜索/选择视频素材
- 自动生成字幕与背景音乐
- 一键合成并输出高清短视频
- 提供 WebUI 和 API 两种交互界面

**技术亮点**:
- 基于 Python 3.11+ 开发，支持 Windows / macOS / Linux 跨平台
- 集成大模型（如 Kimi K3）驱动视频创作全流程，包括文案撰写、素材关键词提炼与画面决策
- 支持火山引擎、CCSub、Infistar.ai 等第三方 API 服务，扩展模型与素材来源

---
## 4. [AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi)
- **语言**: Rust
- **Stars**: 12,982
- **简介**: ⚡️A native, local-first alternative to Logitech Options+, written in Rust 🦀 — remap buttons, DPI, and SmartShift over HID++. No account, no telemetry.

### AI 总结
**简介**: OpenLogi 是一个用 Rust 编写的本地优先、原生替代 Logitech Options+ 的开源工具，通过 HID++ 和 UVC 协议解锁罗技鼠标、键盘和摄像头的完整功能，无需账号、无遥测。

**核心功能**:
- **设备管理**: 支持 Logi Bolt、Unifying 接收器、蓝牙或有线连接，显示电池电量和充电状态
- **鼠标增强**: 按键重映射（含中键、模式切换键、拇指滚轮）、手势绑定、Actions Ring 八槽快捷操作环、DPI 预设与循环切换、SmartShift 滚轮模式切换及灵敏度调节、原生滚动反转
- **键盘功能**: 全局 F 键重映射（支持文本输入、组合键、多步工作流）、静态 RGB 灯光控制
- **摄像头控制**: 支持任意罗技 UVC 摄像头（Brio、StreamCam、C920 等），实时预览（仅在查看时占用摄像头）、硬件级图像参数调节（变焦、对焦、曝光、白平衡等）、一键配置文件（默认/直播/视频通话）
- **跨平台**: 支持 macOS、Linux 和 Windows，Linux 为一等公民
- **配置与脚本**: 纯文本 TOML 配置文件，可跨机器同步；提供 CLI 命令行工具
- **应用联动**: 支持按应用自动切换配置（macOS + Windows；Linux 仅 X11/XWayland）、Litra 灯随摄像头活动自动开关

**技术亮点**: 原生 Rust + GPUI 框架，轻量高效；通过 OS 输入钩子实现按键捕获与重映射；采用 HID++ 和 UVC 硬件协议直连；支持 D-Bus MPRIS（Linux 媒体键）；配置完全本地化，无云端依赖。

---
## 5. [PostHog/posthog](https://github.com/PostHog/posthog)
- **语言**: Python
- **Stars**: 38,302
- **简介**: 🦔 PostHog is the leading platform for building self-driving products. Our developer tools – AI observability, analytics, session replay, flags, experiments, error tracking, logs, and more – capture all the context agents need to diagnose problems, uncover opportunities, and ship fixes. Steer it all from Slack, web, desktop, or the MCP.

### AI 总结
**简介**: PostHog 是一个开源的“自驱型产品”构建平台，提供产品分析、会话回放、功能开关、实验、错误追踪、日志、AI 可观测性等全套开发者工具，并支持通过 Slack、Web、桌面端或 MCP 进行操控。

**核心功能**:
- **自驱模式**: 将产品数据中的信号（错误、愤怒点击、失败查询等）自动转化为研究报告和可审查的 Pull Request。
- **产品分析**: 支持自动捕获或手动埋点的事件分析，通过可视化或 SQL 洞察用户行为。
- **Web 分析**: 提供类似 GA 的仪表盘，监控流量、转化率、Web 指标和收入。
- **会话重放**: 回放真实用户与网站或移动应用的交互，辅助诊断问题。
- **功能开关**: 安全地向特定用户或群体灰度发布功能。
- **实验**: 对更改进行 A/B 测试并衡量其统计显著性，支持无代码实验。
- **错误追踪**: 捕获错误、发送告警并跟踪解决进度。
- **日志管理**: 将日志数据与产品数据一同采集、搜索和分析。
- **调查问卷**: 提供无代码模板或自定义构建器，收集用户反馈。
- **数据仓库**: 同步 Stripe、Hubspot 等外部工具的数据，并与产品数据联合查询。
- **数据管道**: 对数据进行自定义过滤和转换，支持实时发送至 25+ 工具或批量导出至数据仓库。
- **AI 可观测性**: 捕获 LLM 应用的追踪、生成、延迟和成本数据。
- **工作流**: 创建自动化操作或向用户发送消息的工作流。

**技术亮点**: 基于 Python 构建，采用开源与商业混合模式，提供慷慨的免费月度额度；支持自托管（Hobby 部署）和云端（US/EU）两种使用方式，并集成了 MCP（模型上下文协议）以便在编辑器中直接操控。

---
## 6. [microsoft/TypeScript](https://github.com/microsoft/TypeScript)
- **语言**: Go
- **Stars**: 110,385
- **简介**: TypeScript is a superset of JavaScript that compiles to clean JavaScript output.

### AI 总结
**简介**: TypeScript 是 JavaScript 的超集，通过添加可选类型支持，编译为可读的标准 JavaScript，适用于大型应用开发。

**核心功能**:
- 为 JavaScript 提供可选静态类型系统，增强代码可读性和可维护性
- 支持面向大型应用的开发，兼容任何浏览器、主机和操作系统
- 编译输出干净、可读的标准 JavaScript 代码
- 提供在线 Playground 供快速体验，支持稳定版和夜间版安装

**技术亮点**: 基于 Go 语言实现编译器，具备高性能的类型检查和代码转换能力；项目遵循 Microsoft 开源行为准则，拥有活跃的社区贡献和 CI/CD 集成。

---
## 7. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 275,670
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码代理（coding agents）的完整软件开发方法论，基于可组合的技能（skills）和初始指令构建，让代理自动遵循规范流程工作。

**核心功能**:
- **需求澄清**: 代理不会贸然写代码，而是先通过对话明确用户真实目标，并逐步展示简短易读的规格说明。
- **计划制定**: 在用户确认设计后，生成清晰、可执行的实施计划，强调 TDD（红/绿测试驱动）、YAGNI（不做多余功能）和 DRY（不重复代码）原则。
- **子代理驱动开发**: 用户批准后，启动子代理（subagent）独立处理每个工程任务，自动检查、审查并持续推进，可自主工作数小时。
- **自动触发**: 技能自动激活，无需用户手动干预，代理启动即具备 Superpowers 能力。
- **多平台支持**: 提供针对 Claude Code、Codex、Cursor、Gemini CLI、GitHub Copilot CLI 等十余种编码代理工具的安装方式。

**技术亮点**: 采用 Shell 脚本实现，以插件/扩展形式集成到各类代理环境；支持官方插件市场（如 Claude、Codex）和自定义 marketplace 分发；通过 session-start 钩子自动激活，实现零配置启动。

---
## 8. [santifer/career-ops](https://github.com/santifer/career-ops)
- **语言**: JavaScript
- **Stars**: 67,471
- **简介**: Open-source AI job search: scan job portals, evaluate listings with a structured A-F rubric into a 1.0-5.0 score, tailor your CV, track applications — runs locally in your AI coding CLI (Claude Code, Codex, OpenCode, Antigravity…)

### AI 总结
**简介**: career-ops 是一个开源 AI 求职助手，帮助求职者扫描招聘网站、评估职位、定制简历并追踪申请进度，直接在本地 AI 编码 CLI 中运行。

**核心功能**:
- 扫描多个招聘门户网站，自动收集职位列表
- 使用结构化的 A-F 评分标准评估职位，转换为 1.0-5.0 的量化分数
- 根据目标职位自动定制和优化个人简历（CV）
- 全程追踪求职申请状态和进度
- 支持多语言文档（17 种语言），包括中文、日文、韩文、西班牙文等
- 提供实时 star 增长遥测图表和社区 Discord 支持

**技术亮点**:
- 基于 JavaScript 构建，同时支持 Node.js 和 Go 运行时
- 专为 AI 编码 CLI 设计（Claude Code、Codex、OpenCode、Antigravity、Qwen、Kimi、GitHub Copilot 等）
- 使用 Playwright 进行浏览器自动化，实现招聘网站数据抓取
- 采用多智能体（Multi-Agent）架构，支持 agent-skill-standard
- 由 Claude Code 驱动开发，已获 WIRED 和 Business Insider 等媒体报道

---
## 9. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 4,416
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，为开发者工具、框架和 SaaS 产品提供标准化的插件规范与实现。

**核心功能**:
- **开发工具类插件**: 包含持续学习、团队协作、代码审查（Thermos 热核分支审查）、CLI 设计模式、PR 渲染画布等 10+ 个开发提效插件
- **生产力集成**: 提供 Gmail、Google Drive、Calendar 等办公套件插件，支持邮件管理、文件共享和会议调度
- **第三方服务集成**: 覆盖 GitHub、Salesforce、Playwright、Zoom、HubSpot、Intercom 等 15+ 主流 SaaS 工具的深度集成
- **插件脚手架**: 内置 `create-plugin` 工具，支持快速创建和验证新插件
- **SDK 支持**: 提供 TypeScript SDK（`cursor-sdk`），方便开发者构建自定义应用和自动化脚本

**技术亮点**: 采用标准化的 `.cursor-plugin/plugin.json` 清单格式，每个插件为独立目录；支持 TypeScript 开发、CLI 驱动的可靠性设计（含幂等性、dry-run 模式）、并行子代理编排（Orchestrate）及多模态能力（如 Playwright 真实浏览器操作）。

---
## 10. [modular/modular](https://github.com/modular/modular)
- **语言**: Mojo
- **Stars**: 28,695
- **简介**: The Modular Platform (includes MAX & Mojo)

### AI 总结
**简介**: Modular Platform 是一个统一的 AI 开发与部署平台，包含 MAX 框架（用于模型推理与部署）和 Mojo 语言（一种面向 AI 的高性能编程语言）。

**核心功能**:
- **MAX 框架**: 提供高性能模型推理服务，包含 OpenAI 兼容的端点（`/max/python/max/serve`）和基于 Python 的模型流水线构建工具（`/max/python/max/pipelines`）
- **Mojo 语言**: 包含编译器（`/KGEN`）和标准库（`/mojo/stdlib`），支持高性能计算与 AI 开发
- **MAX 加速器库**: 提供底层内核优化（`/max/kernels`），用于加速深度学习计算
- **丰富的代码示例**: 提供 MAX 和 Mojo 的示例代码，帮助开发者快速上手
- **社区与协作**: 支持贡献者参与标准库、加速器库和模型架构的开发，并提供 Discord、论坛、Meetup 等社区渠道

**技术亮点**: 基于 Apache License v2.0（含 LLVM Exceptions）开源，采用 Mojo 语言编写核心组件；MAX 框架支持 OpenAI 兼容接口，便于集成现有生态；平台整合了编译器、标准库、加速内核和推理服务，形成端到端的 AI 开发部署解决方案。

---
