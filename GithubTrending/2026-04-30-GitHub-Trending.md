---
tags:
  - github-trending
  - daily
date: 2026-04-30
created: 2026-04-30T01:55:45.331Z
---

# 2026-04-30 GitHub Trending Top 10

## 1. [warpdotdev/warp](https://github.com/warpdotdev/warp)
- **语言**: Rust
- **Stars**: 44,331
- **简介**: Warp is an agentic development environment, born out of the terminal.

### AI 总结
**简介**: Warp 是一个基于终端的智能开发环境，旨在通过现代化 UI 和 AI 智能体（Oz）解决传统终端与云规模智能体开发的痛点。

**核心功能**:
- 现代化终端：集成代码编辑功能，提升终端使用体验。
- 内置智能体 Oz：支持运行 Claude Code、Codex 等 CLI 智能体，实现云端并行任务自动化。
- 云智能体编排平台：可创建、审计和操控无限并行智能体，用于自动化重复性任务。
- 跨平台支持：提供下载和文档，支持 macOS 等系统。

**技术亮点**: 使用 Rust 语言开发，计划开源 Rust UI 框架及客户端代码；依赖 Tokio、Alacritty、NuShell 等高性能开源库。

---
## 2. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 44,942
- **简介**: Skills for Real Engineers. Straight from my .claude directory.

### AI 总结
**简介**: 一套专为真实工程场景设计的、轻量可组合的 AI Agent 技能集合，旨在解决与编码代理协作时的常见问题。

**核心功能**:
- **`/grill-me`**: 在执行任务前，通过详细的“拷问”环节对齐用户与 Agent 的意图，避免开发偏差。
- **`/grill-with-docs`**: 在 `/grill-me` 基础上，额外帮助用户与 Agent 建立共享语言，并生成架构决策记录 (ADR)，减少冗长沟通。
- **`/triage`**: 支持问题分类，可根据标签管理任务。
- **一键安装**: 通过 `npx skills@latest add` 命令快速安装并配置到主流编码代理中。

**技术亮点**:
- **Shell 脚本实现**: 基于 Shell 语言，轻量且易于修改和组合。
- **工程经验驱动**: 核心逻辑源自数十年软件开发实践，强调控制力、适应性和可组合性。
- **可定制配置**: 安装时允许用户自定义问题追踪系统（GitHub/Linear/本地文件）和文档存储位置。

---
## 3. [HunxByts/GhostTrack](https://github.com/HunxByts/GhostTrack)
- **语言**: Python
- **Stars**: 11,606
- **简介**: Useful tool to track location or mobile number

### AI 总结
**简介**: GhostTrack 是一个用于追踪地理位置、手机号码和用户名的信息收集（OSINT）工具。

**核心功能**:
- **IP 追踪**: 获取目标 IP 地址的相关信息，可结合 Seeker 工具联动使用。
- **手机号追踪**: 根据目标手机号码搜索并获取相关信息。
- **用户名追踪**: 在社交媒体上搜索目标用户名并获取相关信息。

**技术亮点**: 基于 Python 开发，支持 Linux 和 Termux 平台，通过命令行交互操作。

---
## 4. [ComposioHQ/awesome-codex-skills](https://github.com/ComposioHQ/awesome-codex-skills)
- **语言**: Python
- **Stars**: 4,830
- **简介**: A curated list of practical Codex skills for automating workflows across the Codex CLI and API.

### AI 总结
**简介**: 一个精选的实用 Codex 技能集合，用于通过 Codex CLI 和 API 自动化工作流程。

**核心功能**:
- 提供丰富的 Codex 技能，涵盖开发、生产力、沟通、数据分析等多个类别
- 支持一键安装或手动安装技能到 Codex 环境中
- 包含多种实用技能：代码审查、代码库迁移、部署流水线、会议记录等
- 技能以模块化指令包形式存在，Codex 根据元数据自动触发匹配任务

**技术亮点**:
- 基于 Python 开发的 Skill Installer 工具，支持从 GitHub 仓库自动安装技能
- 技能使用 `SKILL.md` 文件定义元数据和执行步骤，保持上下文简洁高效
- 支持 1000+ 应用集成，扩展 Codex 能力超越文本生成

---
## 5. [1jehuang/jcode](https://github.com/1jehuang/jcode)
- **语言**: Rust
- **Stars**: 1,398
- **简介**: Coding Agent Harness

### AI 总结
**简介**: jcode 是一个下一代编码代理工具，旨在通过多会话工作流、无限可定制性和高性能来提升技能上限。

**核心功能**:
- 支持多会话工作流，可同时运行多个代理会话
- 提供无限可定制性，允许用户根据需求配置代理行为
- 专注于性能优化，在内存占用和启动速度上显著优于同类工具

**技术亮点**: 使用 Rust 语言开发，注重资源效率，在单会话和多会话场景下内存占用远低于 Claude Code、Cursor Agent、GitHub Copilot CLI 等同类工具（单会话低至 27.8 MB，10 会话仅 117 MB）。

---
## 6. [abhigyanpatwari/GitNexus](https://github.com/abhigyanpatwari/GitNexus)
- **语言**: TypeScript
- **Stars**: 33,363
- **简介**: GitNexus: The Zero-Server Code Intelligence Engine - GitNexus is a client-side knowledge graph creator that runs entirely in your browser. Drop in a GitHub repo or ZIP file, and get an interactive knowledge graph wit a built in Graph RAG Agent. Perfect for code exploration

### AI 总结
**简介**: GitNexus 是一款完全运行在浏览器中的零服务器代码智能引擎，能将GitHub仓库或ZIP文件转化为交互式知识图谱，并内置图检索增强生成（Graph RAG）智能体，助力代码探索与分析。

**核心功能**:
- **代码知识图谱构建**: 自动索引代码库中的依赖、调用链、集群和执行流，生成完整的知识图谱。
- **Web UI 交互式探索**: 在浏览器中提供可视化图谱浏览和AI对话功能，无需安装即可使用。
- **CLI + MCP 模式**: 通过命令行工具和MCP协议（模型上下文协议）连接AI代理（如Cursor、Claude Code、Codex等），为日常开发提供可靠的架构视图。
- **本地隐私保护**: 所有处理均在本地完成，支持离线使用和持久化存储（通过LadybugDB）。
- **Bridge 桥接模式**: 通过`gitnexus serve`命令连接CLI和Web UI，无需重复上传或索引即可浏览本地已索引的仓库。

**技术亮点**: 采用TypeScript开发，使用Tree-sitter进行代码解析（原生或WASM模式），LadybugDB作为存储引擎（原生或WASM模式），支持图检索增强生成（Graph RAG）智能体。

---
## 7. [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice)
- **语言**: Python
- **Stars**: 45,718
- **简介**: Open-Source Frontier Voice AI

### AI 总结
**简介**: VibeVoice 是微软开源的语音 AI 模型家族，同时支持文本转语音 (TTS) 和自动语音识别 (ASR)。

**核心功能**:
- **VibeVoice-TTS**: 可生成最长 90 分钟、最多 4 位说话人的多说话人语音合成。
- **VibeVoice-ASR**: 一次性处理长达 60 分钟的音频，输出带说话人、时间戳和内容的结构化转录，原生支持 50+ 种语言。
- **VibeVoice-Realtime-0.5B**: 支持流式文本输入的实时语音合成，并包含多语言和多种英语风格实验语音。

**技术亮点**:
- 核心创新在于使用**连续语音分词器**（声学与语义），以超低帧率 **7.5 Hz** 运行，高效保留音频质量并提升长序列处理效率。
- 采用**下一代扩散框架**，结合大语言模型 (LLM) 理解上下文与对话流，以及扩散头生成高保真声学细节。

---
## 8. [CJackHwang/ds2api](https://github.com/CJackHwang/ds2api)
- **语言**: Go
- **Stars**: 2,737
- **简介**: Deepseek to API: A lightweight, high-performance full-stack middleware converting client protocols to universal APIs. Supports multi-account rotation, compiled binaries, Vercel Serverless, and Docker. Compatible with Google, Claude, and OpenAI API formats.

### AI 总结
**简介**: 一个轻量级高性能的全栈中间件，用于将客户端协议转换为通用API，支持多账户轮换和多种部署方式。

**核心功能**:
- 多账户自动轮换，提高API可用性
- 支持编译二进制、Vercel Serverless和Docker三种部署方式
- 兼容Google、Claude和OpenAI API格式

**技术亮点**: 使用Go语言开发，采用全栈中间件架构设计，支持多种部署模式。

---
## 9. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 173,190
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为编码智能体设计的完整软件开发方法论，基于一组可组合的技能和初始指令，确保智能体遵循规范流程。

**核心功能**:
- **头脑风暴与设计**: 在编码前通过提问和探索来提炼想法，并分段展示设计供用户确认。
- **隔离工作区管理**: 使用 Git worktrees 创建独立分支，自动运行项目设置并验证测试基线。
- **详细计划生成**: 将设计拆分为2-5分钟的微型任务，每个任务包含精确文件路径、完整代码和验证步骤。
- **子代理驱动开发**: 为每个任务分派新子代理，执行两阶段审查（规范合规性和代码质量），支持自动或人工检查点。
- **测试驱动开发 (TDD)**: 强制执行 RED-GREEN-REFACTOR 循环，确保测试先于代码编写。
- **代码审查与分支完成**: 自动审查代码是否符合计划，并在任务完成后提供合并/PR/丢弃选项。

**技术亮点**: 采用 Shell 脚本实现，通过自动触发的技能链实现端到端自动化；支持多种平台（Claude Code、OpenAI Codex CLI、Cursor、GitHub Copilot CLI 等）的插件化安装。

---
## 10. [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis)
- **语言**: Python
- **Stars**: 32,818
- **简介**: LLM驱动的 A/H/美股智能分析器：多数据源行情 + 实时新闻 + LLM决策仪表盘 + 多渠道推送，零成本定时运行，纯白嫖. LLM-powered stock analysis system for A/H/US markets.

### AI 总结
**简介**: LLM驱动的A/H/美股智能分析系统，每日自动分析自选股并推送决策仪表盘，支持零成本定时运行。

**核心功能**:
- **AI决策仪表盘**: 一句话结论、评分、买卖点位、风险警报及操作检查清单
- **多维度分析**: 技术面、实时行情、筹码分布、新闻舆情、公告、资金流与基本面聚合
- **全球市场支持**: A股、港股、美股及常见ETF
- **市场策略系统**: 内置A股复盘、美股Regime、均线、缠论、波浪、情绪周期等策略
- **大盘复盘**: 每日市场概览、指数表现、涨跌统计与板块强弱
- **双主题工作台**: 手动分析、配置管理、历史报告、回测、持仓管理
- **智能导入与补全**: 支持图片、CSV/Excel、剪贴板导入，代码/名称/拼音/别名补全
- **AI回测验证**: 历史分析事后验证，查看方向准确率和模拟收益
- **Agent问股**: 多轮策略问答，支持11种内置策略
- **多渠道推送**: 企业微信、飞书、Telegram、Discord、Slack、邮件
- **自动化运行**: 支持GitHub Actions、Docker、本地定时任务和FastAPI服务模式

**技术亮点**: 基于Python，集成AIHubMix、Gemini、OpenAI兼容、DeepSeek等主流AI模型；行情数据支持TickFlow、AkShare、Tushare等；新闻搜索支持Anspire、SerpAPI、Tavily等；社交舆情集成Stock Sentiment API。

---
