---
tags:
  - github-trending
  - daily
date: 2026-08-18
created: 2026-08-18T01:55:44.397Z
---

# 2026-08-18 GitHub Trending Top 10

## 1. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)
- **语言**: Python
- **Stars**: 106,178
- **简介**: 利用 AI 大模型和自动化工作流，根据主题或关键词一键生成高清短视频。Generate HD short videos from a topic or keyword with an automated AI workflow.

### AI 总结
**简介**: MoneyPrinterTurbo 是一款基于 AI 大模型与自动化工作流的一站式短视频生成工具，输入主题或关键词即可自动产出高清短视频。

**核心功能**:
- 自动生成视频脚本：根据主题或关键词，由 AI 大模型撰写文案
- 智能匹配视频素材：自动提炼素材搜索关键词并匹配合适的画面
- 自动生成字幕与背景音乐：无需手动编辑，全流程自动化
- 一键合成高清短视频：输出成品视频，支持 WebUI 和 API 两种交互方式

**技术亮点**:
- 基于 Python 3.11+ 构建，支持 Windows / macOS / Linux 跨平台运行
- 采用 AI 工作流驱动，集成 Kimi K3（Moonshot AI）等大模型，具备原生视觉能力与 100 万 Token 上下文，可精准理解内容并驱动素材匹配
- 提供 WebUI 图形界面与 API 接口，方便集成到其他系统
- 支持对接火山引擎豆包、DeepSeek、Qwen 等多种主流 LLM 与多模态模型生态

---
## 2. [usestrix/strix](https://github.com/usestrix/strix)
- **语言**: Python
- **Stars**: 54,248
- **简介**: Open-source AI penetration testing tool to find and fix your app’s vulnerabilities.

### AI 总结
**简介**: Strix 是一个开源的人工智能渗透测试工具，通过自主 AI 黑客代理动态运行代码、发现并验证应用漏洞，并提供修复建议。

**核心功能**:
- **完整渗透测试工具包** - 内置侦察、漏洞利用和验证能力，开箱即用
- **多代理协同** - 支持多 AI 渗透测试代理协作，可横向扩展
- **真实漏洞验证** - 生成可用的概念验证（PoC），避免传统扫描器的误报问题
- **开发者友好 CLI** - 提供可操作的发现结果与修复指导
- **自动修复与报告** - 自动生成安全补丁及合规级渗透测试报告
- **CI/CD 集成** - 支持 GitHub Actions 等流水线，在每次 Pull Request 自动扫描并阻断不安全代码进入生产环境

**技术亮点**: 基于 Python 构建，采用 Docker 沙箱隔离运行环境，支持多 LLM 提供商（OpenAI、Anthropic、Google 等），采用多代理编排架构模拟真实黑客行为，并提供云平台版本（app.strix.ai）实现持续渗透测试与 DevSecOps 工具链集成（GitHub、GitLab、Slack、Jira 等）。

---
## 3. [nautechsystems/nautilus_trader](https://github.com/nautechsystems/nautilus_trader)
- **语言**: Rust
- **Stars**: 25,958
- **简介**: Production-grade Rust-native trading engine with deterministic event-driven architecture

### AI 总结
**简介**: NautilusTrader 是一个开源、生产级、基于 Rust 原生构建的多资产、多交易场所交易引擎，采用确定性事件驱动架构，以 Python 作为策略逻辑与控制面的控制层。

**核心功能**:
- **多资产多场所支持**：资产类别无关，可接入加密货币交易所（CEX/DEX）、传统市场（外汇、股票、期货、期权）及博彩交易所，通过模块化适配器支持任意具有 REST API 或 WebSocket 流的场所
- **研究与实盘统一**：同一执行语义和确定性时间模型在研究和实盘系统中运行，策略从研究到生产无需修改代码，实现研究-实盘一致性，降低部署风险
- **高性能 Rust 核心**：使用 mimalloc 分配器和 tokio 异步网络，提供编译型交易引擎的性能与安全性，同时支持纯 Rust 编写关键任务交易系统
- **Python 控制平面**：Python 作为系统组合和策略开发的灵活控制层，负责策略逻辑、配置和编排

**技术亮点**: Rust 原生核心（类型与线程安全）、确定性事件驱动架构、mimalloc 内存分配器、tokio 异步运行时、支持多平台（Linux x86_64/ARM64、macOS ARM64、Windows x86_64）及多 Python 版本（3.12-3.14）

---
## 4. [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory)
- **语言**: Rust
- **Stars**: 2,114
- **简介**: Solution for long term memory for agent coding CLIs and to facilitate handoff between different agent vendors

### AI 总结
**简介**: ai-memory 是一个为 AI 编码代理提供长期记忆的 Rust 工具，让用户在切换不同代理（如 Claude Code、Codex）时无需重新解释项目架构、失败方案或未决问题。

**核心功能**:
- **跨代理会话记忆**: 支持在 Claude Code、Codex、Command Code、Devin CLI、OpenCode、Cursor、Gemini CLI 等主流 AI 编码代理间无缝切换，保留上下文和项目记忆
- **生命周期钩子集成**: 通过 MCP 配置和生命周期钩子（如 SessionStart、Stop）自动捕获会话上下文，支持会话结束时的总结与交接
- **会话管理**: 提供 `finalize-session` 命令手动生成最终总结/交接文档，`run` 命令支持跨工具的工作流连续恢复
- **多平台支持**: 支持 Linux（Docker/ARM64）、macOS（原生二进制）、Windows（WSL2 及实验性原生支持）
- **可配置捕获规则**: 支持捕获排除、可选助手最终回合捕获（双 opt-in）、会话级自动隔离等细粒度控制

**技术亮点**:
- 使用 Rust 编写，提供原生高性能二进制（支持 macOS aarch64/x86_64、Windows x86_64）
- 采用 MCP（Model Context Protocol）标准集成多种代理，通过 TypeScript 插件/扩展机制适配不同工具
- 架构上区分"托管工作流"（`ai-memory run`）和直接启动模式，支持项目本地会话数据库恢复
- 提供 stdio 桥接实现会话级自动作用域隔离，通过 `hookSpecificOutput.additionalContext` 等机制注入交接上下文

---
## 5. [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills)
- **语言**: Python
- **Stars**: 28,472
- **简介**: 817 structured cybersecurity skills for AI agents · Mapped to 6 frameworks: MITRE ATT&CK, NIST CSF 2.0, MITRE ATLAS, D3FEND, NIST AI RMF & MITRE F3 (Fight Fraud) · agentskills.io standard · Works with Claude Code, GitHub Copilot, Codex CLI, Cursor, Gemini CLI & 20+ platforms · 29 security domains · Apache 2.0

### AI 总结
**简介**: 一个面向 AI 代理的开源网络安全技能库，包含 817 个结构化技能，覆盖 29 个安全领域，并映射到 6 个主流安全框架。

**核心功能**:
- **817 个生产级网络安全技能**：涵盖威胁检测、取证分析、红队操作、云安全、AI 安全等 29 个安全领域，每个技能遵循 agentskills.io 开放标准。
- **六大框架映射**：技能分别映射到 MITRE ATT&CK（805 个）、NIST CSF 2.0（804 个）、MITRE D3FEND（139 个）、NIST AI RMF（97 个）、MITRE F3（94 个）和 MITRE ATLAS（93 个），按技能类型匹配相关框架。
- **多平台兼容**：支持 Claude Code、GitHub Copilot、Codex CLI、Cursor、Gemini CLI 及 26+ 主流 AI 平台。
- **即插即用**：克隆仓库后指向 AI 代理，即可为安全调查提供专家级指导。

**技术亮点**:
- 基于 Python 实现，遵循 agentskills.io 开放标准，采用 Apache 2.0 开源协议。
- 框架映射采用按技能类型定制策略（如取证技能映射 ATT&CK + CSF，AI 安全技能额外映射 ATLAS 和 AI RMF），而非一刀切。
- 包含红队 C2、钓鱼模拟等攻防双用途技术，明确限定仅限授权测试与教育场景。

---
## 6. [AlexsJones/llmfit](https://github.com/AlexsJones/llmfit)
- **语言**: Rust
- **Stars**: 32,320
- **简介**: Hundreds of models & providers. One command to find what runs on your hardware.

### AI 总结
**简介**: llmfit 是一个终端工具，用于根据你的硬件配置（RAM、CPU、GPU）自动匹配并推荐合适的 LLM 模型，一条命令即可找出能在你机器上流畅运行的模型。

**核心功能**:
- 自动检测硬件并评估数百个模型在质量、速度、适配度和上下文窗口方面的表现
- 支持交互式 TUI 和经典 CLI 两种模式
- 支持多 GPU、MoE 架构、动态量化选择、速度估算
- 集成多种本地运行时提供商（Ollama、llama.cpp、MLX、Docker Model Runner、LM Studio）
- 内置基准测试功能：可实测 tok/s 并提交结果回项目，优化模型适配表
- 提供 Docker/Podman 容器运行方式，支持 JSON 输出便于自动化

**技术亮点**: 使用 Rust 编写，通过 Scoop、Homebrew、MacPorts、uv/pip 多平台分发，支持 Docker 镜像部署；项目附带详细的文档体系（TUI 指南、基准测试指南、CLI 自动化文档等），并有姊妹项目形成生态（sympozium、llmserve、llama-panel）。

---
## 7. [santifer/career-ops](https://github.com/santifer/career-ops)
- **语言**: JavaScript
- **Stars**: 64,716
- **简介**: Open-source AI job search: scan job portals, evaluate listings with a structured A-F rubric into a 1.0-5.0 score, tailor your CV, track applications — runs locally in your AI coding CLI (Claude Code, Codex, OpenCode, Antigravity…)

### AI 总结
**简介**: career-ops 是一个开源 AI 求职助手，使用多智能体系统扫描招聘网站、评估职位、定制简历并跟踪申请流程，可直接在 AI 编程 CLI 中本地运行。

**核心功能**:
- **职位扫描与评估**: 自动扫描多个招聘网站，使用结构化的 A-F 评分标准对职位进行 1.0-5.0 分制打分
- **简历定制**: 根据目标职位自动生成个性化简历
- **申请跟踪**: 管理并跟踪所有求职申请进度
- **本地运行**: 在 Claude Code、Codex、OpenCode、Antigravity 等 AI 编程终端中本地执行，无需云端服务
- **多语言支持**: 提供 17 种语言的文档（含简体中文）

**技术亮点**:
- 基于 Claude Code 构建，兼容 Agent Skill Standard，可运行于多种 AI CLI 环境
- 使用 Node.js/Go 编写，集成 Playwright 用于网页自动化
- 采用多智能体架构，支持结构化评分模型和自动化简历生成

---
## 8. [jundot/omlx](https://github.com/jundot/omlx)
- **语言**: Python
- **Stars**: 19,012
- **简介**: LLM inference server with continuous batching & SSD caching for Apple Silicon — managed from the macOS menu bar

### AI 总结
**简介**: oMLX 是一款专为 Apple Silicon Mac 优化的 LLM 推理服务器，支持连续批处理和 SSD 缓存，并可通过 macOS 菜单栏直接管理。

**核心功能**:
- 连续批处理（Continuous batching）提升推理吞吐效率
- 分层 KV 缓存：热内存层 + 冷 SSD 层，对话中途切换上下文时历史缓存仍可复用
- macOS 菜单栏管理界面，支持一键启动/停止/重启服务器
- 支持通过 CLI、Apple Shortcuts 控制服务器
- 集成 MCP（Model Context Protocol）支持
- 内置模型下载与管理，支持 GLM-5.2、MiniMax M3、Qwen3.5 等模型家族的本地化部署
- 提供原生自定义内核加速（需 Xcode 编译，官方 DMG 预编译），GLM-5.2 融合 DSA 预填充速度提升约 30 倍

**技术亮点**:
- 基于 Python 3.11–3.13，要求 macOS 15.0+ 与 Apple Silicon（M1–M4）
- 采用 Metal 工具链构建自定义内核，支持模型家族专属优化
- 提供 macOS App（含自动更新）、Homebrew、源码三种安装方式
- 设计目标兼顾便利性与控制力：常驻模型内存固定、按需自动切换重模型、可设上下文限制

---
## 9. [immich-app/immich](https://github.com/immich-app/immich)
- **语言**: TypeScript
- **Stars**: 111,196
- **简介**: High performance self-hosted photo and video management solution.

### AI 总结
**简介**: Immich 是一个高性能的自托管照片和视频管理解决方案，支持多用户、跨平台（移动端和 Web）使用，并提供类似 Google Photos 的丰富功能。

**核心功能**:
- **媒体管理**: 上传、查看、下载照片和视频，支持 RAW 格式、LivePhoto/MotionPhoto、360 度图片展示
- **自动备份**: 移动端支持应用打开时自动备份、后台备份及选择性相册备份
- **智能搜索**: 支持按元数据、物体、人脸和 CLIP 语义搜索，并具备人脸识别与聚类功能
- **组织与共享**: 相册/共享相册、收藏、归档、标签、文件夹视图、全局地图、合作伙伴共享、公开分享
- **多用户与权限**: 多用户支持、管理员用户管理、OAuth 认证、API 密钥
- **增强体验**: 回忆（几年前）、堆叠照片、虚拟滚动、离线支持（移动端）、只读图库

**技术亮点**: 基于 TypeScript 开发，采用 AGPLv3 开源协议，提供完整的 Web 和移动端（iOS/Android）支持，文档完善（含多语言翻译），并附有在线演示环境供用户体验。

---
## 10. [cordiverse/cordis](https://github.com/cordiverse/cordis)
- **语言**: TypeScript
- **Stars**: 5,633
- **简介**: Meta-Framework of Spatiotemporal Composability

### AI 总结
**简介**: Cordis 是一个基于 TypeScript 的时空可组合性元框架，旨在通过统一的抽象层实现跨时空维度的模块化组合与调度。

**核心功能**:
- 提供时空数据与逻辑的元建模能力，支持位置、时间与实体关系的声明式组合
- 内置可插拔的组件化架构，允许开发者按需扩展时空计算、存储与交互模块
- 支持多种运行时适配（如浏览器、Node.js），实现跨环境的一致行为
- 提供高阶组合 API，用于构建复杂的时空依赖流程与事件驱动逻辑

**技术亮点**: 采用 TypeScript 全栈开发，强调类型安全的元编程；核心设计基于分层抽象（元模型 → 组合层 → 运行时），支持依赖注入与策略模式，便于定制化集成。

---
