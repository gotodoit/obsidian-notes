---
tags:
  - github-trending
  - daily
date: 2026-08-20
created: 2026-08-20T01:55:44.171Z
---

# 2026-08-20 GitHub Trending Top 10

## 1. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)
- **语言**: Python
- **Stars**: 110,837
- **简介**: 利用 AI 大模型和自动化工作流，根据主题或关键词一键生成高清短视频。Generate HD short videos from a topic or keyword with an automated AI workflow.

### AI 总结
**简介**: MoneyPrinterTurbo 是一款基于 AI 大模型和自动化工作流的一站式短视频生成工具，输入主题或关键词即可自动产出高清短视频。

**核心功能**:
- 自动生成视频脚本：基于主题/关键词，由 AI 大模型撰写文案
- 智能匹配素材：自动提炼素材搜索关键词并匹配对应画面
- 自动生成字幕与背景音乐：全流程自动化合成
- 输出高清短视频：支持一键生成成片
- 提供 WebUI 与 API 两种使用界面

**技术亮点**:
- 基于 Python 3.11+，跨平台支持 Windows/macOS/Linux
- 集成 Kimi K3、豆包、DeepSeek、Qwen 等主流大模型驱动文案与素材匹配
- 支持 OpenAI 标准接口，兼容多模态模型生态（生图/视频模型）

---
## 2. [volcengine/OpenViking](https://github.com/volcengine/OpenViking)
- **语言**: Python
- **Stars**: 30,245
- **简介**: Self-evolving Context Database for AI Agents. Unify Agent Memory, Knowledge RAG and Skills.

### AI 总结
**简介**: OpenViking 是一个面向 AI Agent 的开源上下文数据库，将记忆、知识和技能统一为 `viking://` 虚拟文件系统，让 Agent 像操作文件一样管理自身上下文。

**核心功能**:
- **统一上下文文件系统**: 记忆、资源、技能均通过 `viking://` URI 定位，支持 `ls`、`tree`、`find` 等确定性操作
- **三级分层加载 (L0/L1/L2)**: 写入时自动生成摘要、概览、详情三层内容，按任务需求按需加载，显著降低 Token 消耗
- **目录递归检索**: 先定位最高分目录，再逐层深入，保证检索结果携带完整上下文
- **可观测检索轨迹**: 每次查询保留目录浏览路径，便于调试和追溯错误结果来源
- **会话自动沉淀记忆**: 会话提交后异步提取用户偏好和 Agent 经验，转化为长期记忆

**技术亮点**: 基于 Python 实现，采用虚拟文件系统协议设计（`viking://`），支持多语言文档（中/英/日），提供可交互的 Web Studio 在线演示，遵循 AGPLv3 开源协议。

---
## 3. [chaitanyagiri/munder-difflin](https://github.com/chaitanyagiri/munder-difflin)
- **语言**: TypeScript
- **Stars**: 2,713
- **简介**: local multi-agent harness

### AI 总结
**简介**: Munder Difflin 是一个开源的本地多智能体协调工具（multi-agent harness），能将你已有的终端编码 CLI（如 Claude Code、Codex、Grok 等）转化为一个自我协作的“智能体办公室”，由你的数字克隆（Michael）负责调度。

**核心功能**:
- **终端即智能体**: 将 `claude`、`codex`、`grok`、`kimi`、`qwen`、`copilot` 等 CLI 会话包装为真实进程（基于 `node-pty`），在伪终端中运行并通过 xterm.js 渲染。
- **可视化办公楼层**: 每个智能体以 Pixi.js 绘制的头像呈现，在 2D 办公楼层中走动、工作，互相投递消息信封。
- **蜂群式协调机制**: 智能体读写长期记忆并处理邮箱；路由器在邮箱间转发消息；GOD 智能体（Michael）负责任务分配、裁决和升级。
- **毫秒级记忆层**: 采用 markdown 优先的记忆存储与语义召回索引，让智能体跨会话记忆并瞬时检索。
- **自带密钥与本地 LLM 支持**: 支持 BYOK（bring-your-own keys）和本地模型，兼容多种主流智能体 CLI。

**技术亮点**: 基于 Electron、React、TypeScript、Pixi.js、xterm.js 和 node-pty 构建；支持 macOS、Windows、Linux 三平台；采用“GOD 智能体 + 路由器 + 记忆层”的架构，实现任务编排、消息路由与长期记忆的分离设计。

---
## 4. [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills)
- **语言**: Python
- **Stars**: 29,868
- **简介**: 817 structured cybersecurity skills for AI agents · Mapped to 6 frameworks: MITRE ATT&CK, NIST CSF 2.0, MITRE ATLAS, D3FEND, NIST AI RMF & MITRE F3 (Fight Fraud) · agentskills.io standard · Works with Claude Code, GitHub Copilot, Codex CLI, Cursor, Gemini CLI & 20+ platforms · 29 security domains · Apache 2.0

### AI 总结
**简介**: 面向 AI 智能体的最大开源网络安全技能库，提供 817 个结构化技能，覆盖 29 个安全领域，并映射到 6 个行业安全框架。

**核心功能**:
- **817 个生产级网络安全技能**：涵盖威胁检测、取证分析、云安全、AI 安全、反欺诈等 29 个安全领域，每个技能遵循 agentskills.io 开放标准，可为 AI 智能体提供相当于资深安全分析师的专家级指导
- **六大框架映射**：技能分别映射至 MITRE ATT&CK（805 个）、NIST CSF 2.0（804 个）、MITRE D3FEND（139 个）、NIST AI RMF（97 个）、MITRE F3（94 个）和 MITRE ATLAS（93 个），每个技能按类型映射到相关框架
- **多平台兼容**：支持 Claude Code、GitHub Copilot、Codex CLI、Cursor、Gemini CLI 及 26+ 主流 AI 平台，克隆后即可让智能体获得安全分析能力
- **授权安全用途**：包含红队 C2、钓鱼模拟、漏洞利用等攻击性/双重用途技术，仅限授权渗透测试、安全研究和教育场景使用

**技术亮点**: Python 实现，采用 agentskills.io 开放标准定义技能格式；框架映射采用按技能类型差异化关联策略（如取证技能映射 ATT&CK+CSF，AI 安全技能增加 ATLAS 和 AI RMF）；基于 MITRE ATT&CK v19.1、NIST CSF 2.0、MITRE ATLAS 2026.07 等最新框架版本；Apache 2.0 开源协议，支持社区贡献。

---
## 5. [nautechsystems/nautilus_trader](https://github.com/nautechsystems/nautilus_trader)
- **语言**: Rust
- **Stars**: 26,458
- **简介**: Production-grade Rust-native trading engine with deterministic event-driven architecture

### AI 总结
**简介**: NautilusTrader 是一个开源、生产级的 Rust 原生多资产多交易所交易引擎，采用确定性事件驱动架构，以 Python 作为策略逻辑与控制层的控制平面。

**核心功能**:
- 多资产、多交易所支持：覆盖加密货币（CEX/DEX）、传统市场（外汇、股票、期货、期权）及博彩交易所，可通过模块化适配器接入任意支持 REST API 或 WebSocket 的场所
- 研究到生产无缝衔接：同一执行语义和确定性时间模型同时用于研究与实盘，策略无需修改代码即可从研究部署至生产，实现研究-实盘一致性
- 事件驱动架构：Python 负责策略逻辑、配置与编排，Rust 核心提供高性能执行引擎，支持纯 Rust 编写交易系统以满足关键任务需求
- 确定性模拟与实盘执行：系统统一覆盖研究、模拟与实盘交易全流程

**技术亮点**: 基于 Rust 核心，采用 mimalloc 内存分配器与 tokio 异步网络框架，提供类型安全与线程安全保证；支持 Linux、macOS、Windows 多平台，兼容 Python 3.12-3.14 及 Rust 1.97.1。

---
## 6. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 223,893
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: 这是 Matt Pocock 开源的一套面向真实工程实践的 AI 编码代理技能集（Skills），源自其个人 `.agents` 目录，旨在解决 AI 编码代理在实际开发中的常见痛点，而非单纯“氛围编程”。

**核心功能**:
- **安装即用**：支持通过 Claude Code 插件（`claude plugins install mattpocock-skills`）或 `npx skills@latest add mattpocock/skills` 快速安装，并适配 Codex 等主流代理。
- **一键初始化**：运行 `/setup-matt-pocock-skills` 即可完成项目配置，包括选择问题追踪器（GitHub/Linear/本地文件）、设置标签规则及文档存储位置。
- **需求对齐（Grilling）**：提供 `/grill-me` 和 `/grill-with-docs` 技能，通过代理主动提问的方式，在开发前深度澄清需求，避免“代理没做对”的沟通偏差。
- **精简输出控制**：内置技能帮助约束代理的回复冗长问题，提升对话效率。

**技术亮点**: 技能设计遵循“小而可组合”原则，基于 Shell 实现，强调可编辑、可定制（非只读捆绑），支持用户自由修改并随项目演进；同时提供 ADR 记录架构决策，并通过 `skills.sh` 支持增量更新。

---
## 7. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 274,306
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码代理（Coding Agents）的完整软件开发方法论，基于一组可组合的技能构建，旨在让 AI 代理遵循规范化的开发流程，从需求澄清到测试驱动开发全程自动化。

**核心功能**:
- **自动触发的工作流**: 代理启动后不会直接写代码，而是先通过对话引导用户明确真正的目标和需求。
- **规格与计划生成**: 将对话提炼为可读的规格说明，并在用户确认后生成清晰、可执行的实现计划（强调 TDD、YAGNI、DRY 原则）。
- **子代理驱动开发**: 用户批准后，代理会启动子代理逐个完成工程任务，并进行自查和审查，可自主连续工作数小时而不偏离计划。
- **多平台插件支持**: 提供针对主流编码工具的安装方式，包括 Claude Code、Cursor、Codex、Gemini CLI、GitHub Copilot CLI、Devin CLI 等十余种平台。

**技术亮点**: 基于 Shell 脚本实现的可组合技能框架；通过会话启动钩子（session-start hook）实现零配置自动激活；采用插件市场机制分发，支持官方市场与第三方市场注册。

---
## 8. [jundot/omlx](https://github.com/jundot/omlx)
- **语言**: Python
- **Stars**: 19,852
- **简介**: LLM inference server with continuous batching & SSD caching for Apple Silicon — managed from the macOS menu bar

### AI 总结
**简介**: oMLX 是一款专为 Apple Silicon Mac 优化的 LLM 推理服务器，支持连续批处理和 SSD 缓存，并可通过菜单栏轻松管理。

**核心功能**:
- **菜单栏管理**: 通过 macOS 菜单栏应用直接控制模型加载、切换和服务器启停
- **连续批处理**: 支持动态请求批处理，提升推理吞吐量
- **分层 KV 缓存**: 热内存层 + 冷 SSD 层持久化缓存，对话中途切换上下文时历史缓存仍可复用
- **模型灵活管理**: 固定常驻模型、按需自动交换重型模型、自定义上下文长度
- **多端集成**: 支持 OpenClaw、OpenCode、Codex、Hermes Agent、Copilot 等工具连接
- **多语言支持**: 提供中、英、韩、日文文档

**技术亮点**:
- 基于 Python 3.11–3.13，要求 macOS 15.0+ 和 Apple Silicon（M1–M4）
- 提供原生自定义内核（如 GLM-5.2 融合 DSA 预填充），推理速度提升约 30 倍（M3 Ultra 上 845 vs ~29 tok/s）
- 支持 MCP（Model Context Protocol）协议扩展
- 提供 macOS 应用（含自动更新）、Homebrew 安装包和源码安装三种部署方式
- 内置 CLI 工具 (`omlx start/stop/restart`) 和后台服务模式（崩溃自动重启）

---
## 9. [santifer/career-ops](https://github.com/santifer/career-ops)
- **语言**: JavaScript
- **Stars**: 65,824
- **简介**: Open-source AI job search: scan job portals, evaluate listings with a structured A-F rubric into a 1.0-5.0 score, tailor your CV, track applications — runs locally in your AI coding CLI (Claude Code, Codex, OpenCode, Antigravity…)

### AI 总结
**简介**: career-ops 是一个开源的 AI 求职助手，能在本地 AI 编程 CLI（如 Claude Code、Codex、OpenCode 等）中自动扫描招聘网站、评估职位、定制简历并跟踪申请进度。

**核心功能**:
- **职位扫描与评估**: 自动抓取招聘平台上的职位列表，并使用结构化的 A-F 评分标准对职位进行 1.0-5.0 分的量化打分
- **简历定制**: 根据职位评估结果自动生成个性化简历，适配不同岗位需求
- **申请跟踪**: 系统化管理求职申请流程，记录每个职位的申请状态
- **本地运行**: 完全在本地 AI 编程 CLI 环境中运行，支持 Claude Code、Codex、OpenCode、Antigravity 等多种工具
- **多语言支持**: 提供 17 种语言的文档（含简体中文）

**技术亮点**: 基于 Node.js 构建，采用多智能体（Multi-Agent）架构设计，集成了 Playwright 用于网页自动化抓取，并遵循 agent-skill-standard 标准，可兼容多种主流 AI 编程 CLI 环境。项目作者实测评估了 740+ 职位、生成了 100+ 份个性化简历，并最终成功入职理想岗位。

---
## 10. [immich-app/immich](https://github.com/immich-app/immich)
- **语言**: TypeScript
- **Stars**: 111,893
- **简介**: High performance self-hosted photo and video management solution.

### AI 总结
**简介**: Immich 是一个高性能的自托管照片和视频管理解决方案，支持多平台访问，旨在为用户提供类似 Google Photos 的体验，同时完全掌控自己的数据。

**核心功能**:
- **多端支持**: 提供 Web 和移动端应用，覆盖 iOS 和 Android 平台
- **自动备份**: 应用打开时自动备份照片和视频，支持后台备份和选择性相册备份
- **智能管理**: 支持元数据（EXIF、地图）查看、按元数据/物体/人脸/CLIP 搜索、人脸识别与聚类
- **丰富的组织功能**: 相册与共享相册、收藏、归档、标签、文件夹视图、堆叠照片、全球地图
- **高级特性**: 支持 LivePhoto/MotionPhoto、360 度图像、RAW 格式、OAuth 认证、API Keys、公开分享、记忆回顾（x 年前）、离线支持
- **多用户支持**: 提供完整的用户管理功能，支持合作伙伴共享
- **防止重复**: 自动检测并防止资源重复上传

**技术亮点**: 基于 TypeScript 开发，采用 AGPLv3 开源协议；支持用户自定义存储结构；提供虚拟滚动以优化大量媒体文件的浏览性能；支持多语言界面（20+ 种语言）；提供在线演示环境供用户体验。

---
