---
tags:
  - github-trending
  - daily
date: 2026-09-16
created: 2026-09-16T01:55:43.051Z
---

# 2026-09-16 GitHub Trending Top 10

## 1. [alibaba/open-code-review](https://github.com/alibaba/open-code-review)
- **语言**: Go
- **Stars**: 28,732
- **简介**: Fast, efficient, battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level comments, built-in multi-language ruleset (NPE, thread-safety, XSS, SQL injection), OpenAI & Anthropic compatible.

### AI 总结
**简介**: 阿里巴巴开源的 AI 代码审查 CLI 工具，源自集团内部大规模验证的代码审查助手，通过混合架构（确定性流水线 + LLM Agent）实现精准的行级代码审查。

**核心功能**:
- 读取 Git diff，通过具备工具调用能力的 Agent 将变更文件发送给可配置的 LLM，生成结构化、行级精度的审查评论
- Agent 可读取完整文件内容、搜索代码库、检查其他变更文件以获取上下文，实现深度审查而非表面 diff 反馈
- 内置多语言规则集，覆盖 NPE、线程安全、XSS、SQL 注入等常见缺陷
- 支持 `ocr scan` 对无有意义 diff 的整个文件或陌生代码库进行审计式审查
- 兼容 OpenAI 与 Anthropic 模型接口，支持 Claude Code、Codex、Cursor 等 Agent 平台，跨 Windows/macOS/Linux 运行

**技术亮点**:
- 混合架构：确定性流水线 + LLM Agent 相结合，兼顾效率与深度
- 在阿里规模下久经考验，两年内服务数万名开发者，识别数百万代码缺陷
- 基准测试（AACR-Bench，50 个开源仓库、200 个真实 PR、10 种语言、1505 个标注问题）显示：相同底层模型下，相比通用 Agent（Claude Code）精度与 F1 显著更高，token 消耗仅约 1/9，审查速度更快；召回率较低是刻意权衡，优先保证精度、减少噪音
- 使用 Go 语言开发，已发布 npm 包，获 OpenSSF Gold 最佳实践认证

---
## 2. [JustVugg/colibri](https://github.com/JustVugg/colibri)
- **语言**: C
- **Stars**: 33,899
- **简介**: Run frontier MoE models on hardware you already own — pure C, zero deps, experts streamed from disk. Tiny engine, immense model. 🐦

### AI 总结
**简介**: Colibrì 是一个用纯 C 编写的轻量级 MoE 推理引擎，通过将显存、内存和磁盘统一为多级推理层级，让消费级硬件也能运行 744B 至 2.8T 参数的前沿混合专家模型。

**核心功能**:
- 在消费级及异构硬件上运行前沿 MoE 大模型（如 GLM-5.2/5.3 744B、Kimi K3 2.8T、DeepSeek V4 系列、Qwen3 系列等九个模型家族）
- 将存储、RAM、VRAM 视为统一推理层级（AI memory multitiering），专家权重按需从磁盘流式加载
- 提供统一前端：`coli chat`（对话）、`coli serve`（服务）、`coli web`（Web 仪表盘）
- Web 可视化面板：实时 token 指标、显存/内存/磁盘层级条、专家大脑视图（19,456 个专家的路由热力）与专家图谱（按主题聚类的 3D 星系）
- 每个模型仅一个 C 文件，零引擎依赖

**技术亮点**:
- 纯 C 实现，无第三方引擎依赖，代码体量极小
- 多级内存分层架构：将 VRAM、RAM、磁盘整合为单一推理层级，突破硬件容量限制
- 强调语义保证——默认策略绝不静默改变模型精度或路由器语义，速度可降但模型定义不可被悄悄改写
- 覆盖模型格式、存储 I/O、调度、内核、推测解码、CPU/GPU 重叠等全栈优化
- 定位为开放研究平台，以可复现的端到端测量为实验评判标准
- 示例性能：744B 模型在 6×RTX 5090 上实现 4 tok/s、TTFT 1.6s、磁盘读取为 0

---
## 3. [ever-co/ever-gauzy](https://github.com/ever-co/ever-gauzy)
- **语言**: TypeScript
- **Stars**: 6,693
- **简介**: Ever® Gauzy™ - Open Business Management Platform (ERP/CRM/HRM/ATS/PM) - https://gauzy.co

### AI 总结
**简介**: Ever Gauzy 是一个面向协作、按需和共享经济场景的开源商业管理平台，集成 ERP、CRM、HRM、ATS 和项目管理等核心业务模块。

**核心功能**:
- 人力资源管理（HRM）：员工管理、入职流程、绩效监控、考勤与时间追踪
- 客户关系管理（CRM）：联系人管理、销售管道、提案与日程安排
- 企业资源规划（ERP）：财务与成本管理、会计、发票、库存与供应链管理
- 项目管理（PM）：项目与任务管理、目标/KPI/OKR 追踪
- 招聘管理（ATS）：候选人追踪与面试安排
- 时间追踪：员工工时、活动与生产力监控、工时表
- 其他：多组织管理、多币种、多语言、角色权限、数据导入导出、集成（Upwork、HubStaff 等）、暗色/亮色主题

**技术亮点**: 基于 TypeScript 构建，提供 Headless API 架构（API 文档见 api.gauzy.co/docs），前端采用 Angular，配套桌面计时器应用；另有基于 React/Next.js 和 React Native/Expo 的 Ever Teams 平台对接其 API。

---
## 4. [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio)
- **语言**: Python
- **Stars**: 31,047
- **简介**: VoiceStudio is the open-source, fully-local ElevenLabs alternative — voice cloning, voice design, video dubbing, dictation, transcription & audiobook creation in 646 languages.

### AI 总结
**简介**: VoiceStudio 是一个完全本地运行的开源 ElevenLabs 替代方案，支持语音克隆、设计、视频配音、听写、转录和有声书制作，覆盖 646 种语言。

**核心功能**:
- 语音克隆与语音设计，支持从音频克隆和按设计创建声音
- 视频配音、听写、转录、故事与有声书批量生成
- 集成 16 个 TTS 引擎和 11 个 ASR 引擎，可在模型目录或快捷键切换
- 提供桌面应用、本地 REST/SSE/WebSocket API、OpenAI 兼容音频 API 及 MCP Server
- 支持语音到语音转换（Convert）工作流

**技术亮点**:
- 完全本地化运行，无需账号、API Key、订阅或用量计费，数据默认留在本机
- 支持 CUDA、Apple Silicon MPS/MLX、ROCm、CPU 及可选远程 worker 多种计算后端
- 跨平台支持 macOS 13.3+（Apple Silicon）、Windows 10/11 x64、Linux x86_64（glibc 2.39+）及 Docker
- 采用 AGPL-3.0 许可，下载模型遵循各自上游条款
- 当前处于活跃 beta 阶段，正在进行 Electron 重写

---
## 5. [Homebrew/BrewUI](https://github.com/Homebrew/BrewUI)
- **语言**: Swift
- **Stars**: 1,394
- **简介**: 📺 Homebrew's official macOS GUI

### AI 总结
**简介**: BrewUI 是 Homebrew 官方推出的 macOS 图形界面应用，让不习惯命令行的用户也能安全地发现、安装、更新和管理 Homebrew 软件包，同时保持对底层操作的完全透明。

**核心功能**:
- 通过原生图形界面完成 Homebrew 软件包的查找、安装、更新与管理
- 完整展示底层 Homebrew 的实际操作，不隐藏任何执行细节
- 提供 Configuration 标签页与 Doctor 报告，呈现 Homebrew 环境状态
- 支持应用自我升级（self-upgrade）

**技术亮点**:
- 采用 Swift 6.0（严格并发）与 SwiftUI 构建，使用 Swift Package Manager 管理依赖
- 要求 macOS Tahoe 26 及以上
- 数据来源为 `brew` CLI 与 Homebrew JSON API
- 始终通过 `/bin/zsh` 并配合 `--no-rcs --no-global-rcs` 启动 Homebrew，使用干净的环境变量，配置统一由 `brew.env` 文件管理
- 开发流程集成 Mint、SwiftFormat、SwiftLint 与 Git hooks，提交时自动执行格式化和严格校验
- 采用 AGPL-3.0 许可证，包含网络使用条款

---
## 6. [melgarafael/DeskcommCRM](https://github.com/melgarafael/DeskcommCRM)
- **语言**: TypeScript
- **Stars**: 2,859
- **简介**: Open-source AI sales OS — self-hosted CRM with native AI agents + WhatsApp (WAHA). Open alternative to Kommo, Octadesk & Intercom for any business that sells by chat. MCP-ready, multi-tenant, LGPD.

### AI 总结
**简介**: DeskcommCRM 是一款开源的 AI 销售操作系统，将原生 AI 智能体与 WhatsApp 聊天集成在自托管 CRM 中，是 Kommo、Octadesk 和 Intercom 的开源替代方案。

**核心功能**:
- AI 智能体直接在 WhatsApp 中接待、筛选并促成销售
- 多租户架构，支持 MCP 协议，适配 LGPD（巴西数据保护法）
- 一条命令即可在 VPS 上完成完整部署（应用 + WhatsApp + 数据库）
- 通过二维码在引导流程中连接 WhatsApp 账号
- 支持 OpenRouter、Anthropic 或 OpenAI 作为 AI 后端

**技术亮点**: 基于 TypeScript（严格模式）+ Next.js 16 构建，使用 Supabase（Postgres + Auth + Storage）作为后端，通过 Docker 容器化部署，与 HostGator 合作提供一键 VPS 安装套件，采用 MIT 开源协议。

---
## 7. [alphaXiv/OpenResearch](https://github.com/alphaXiv/OpenResearch)
- **语言**: Rust
- **Stars**: 3,399
- **简介**: Turn your coding agents into research agents

### AI 总结
**简介**: OpenResearch 是一个本地优先的研究代理工作空间，可将 Claude Code、Codex、OpenCode、Cursor 等编码代理转变为能进行文献综述、假设提出、实验运行和成果产出的研究代理。

**核心功能**:
- **并行探索**：为每个研究方向提供独立的代理会话和隔离的 git worktree
- **可复现实验**：以 git 原生实验树追踪变体，每次运行都保存对应提交的不可变归档
- **上下文证据链**：将日志、diff、文件、结果和产物与其产生的工作绑定
- **代理与算力自由选择**：支持多种编码代理，可本地运行、自有基础设施或托管算力
- **Autoresearch**：可自主完成"提想法→改代码→跑实验→看证据→决定下一步"的完整循环
- **本地所有权**：项目、对话、实验、运行、日志、代码和产物均保留在用户机器上
- **多环境运行**：同一份源码快照可运行于本地、SSH、Slurm、Kubernetes、Ray、Hugging Face Jobs、Modal、Tinker 等平台

**技术亮点**:
- 使用 Rust 编写，提供 CLI（`orx`）与本地仪表盘（`http://127.0.0.1:4791`）
- 支持安装技能到编码代理（`orx install-skills`），提供 `orx` 系列命令管理项目、实验、运行和日志
- 支持连接 LM Studio、oMLX、Ollama 等本地模型及自定义端点
- 远程模式通过 `orx up --remote user@host` 在远程 GPU 旁运行工作区，无需发布仓库

---
## 8. [NationalSecurityAgency/ghidra](https://github.com/NationalSecurityAgency/ghidra)
- **语言**: Java
- **Stars**: 76,744
- **简介**: Ghidra is a software reverse engineering (SRE) framework

### AI 总结
**简介**: Ghidra 是由美国国家安全局（NSA）研究部门开发并维护的软件逆向工程（SRE）框架，提供一套功能完备的高端软件分析工具。

**核心功能**:
- 反汇编、汇编与反编译
- 图形化分析与脚本编写
- 支持多种处理器指令集和可执行文件格式
- 支持交互式与自动化两种运行模式
- 允许使用 Java 或 Python 开发自定义扩展组件和脚本

**技术亮点**: 基于 Java 构建，支持 Windows、macOS 和 Linux 多平台运行；采用可定制、可扩展的架构设计，专为解决复杂 SRE 任务中的规模化与团队协作问题而打造；构建依赖 JDK 25、Gradle 9.1.0+ 及 Python3。

---
## 9. [danny-avila/LibreChat](https://github.com/danny-avila/LibreChat)
- **语言**: TypeScript
- **Stars**: 43,862
- **简介**: Enhanced ChatGPT Clone: Features Agents, MCP, Skills, DeepSeek, Anthropic, AWS, OpenAI, Responses API, Azure, Groq, o1, GPT-5, Mistral, OpenRouter, Vertex AI, Gemini, Artifacts, AI model switching, message search, Code Interpreter, langchain, DALL-E-3, OpenAPI Actions, Functions, Secure Multi-User Auth, Presets, open-source for self-hosting. Active

### AI 总结
**简介**: LibreChat 是一个功能增强的开源 ChatGPT 替代方案，支持多模型切换、多用户认证与自托管部署。

**核心功能**:
- 支持多种 AI 模型与服务商：Anthropic (Claude)、AWS Bedrock、OpenAI、Azure OpenAI、Google、Vertex AI、Groq、Mistral、OpenRouter、DeepSeek、Gemini 等
- Agent 管理：创建、更新、删除 Agent，管理 Agent 文件与 Skills，支持 OIDC 身份认证
- 附加工作区（实验性）：为每个 Agent 配置默认工作区，支持文件读写、搜索和 Bash 执行
- 代码审批控制：对文件写入和命令执行可选 Ask / Allow / Deny，支持 Full access 模式
- 上下文管理：手动上下文压缩、上下文用量查看（对话、工具流量、缓存、成本等）
- 统一附件上传：自动路由至模型或提取文本，按需启用 File Search 和 Code 工具
- 内置 Code Interpreter、DALL-E-3、OpenAPI Actions、Functions、Artifacts
- 安全多用户认证、预设（Presets）、消息搜索、AI 模型切换
- 可观测性：支持 OpenTelemetry 日志导出、Langfuse 追踪、浏览器诊断标记

**技术亮点**: 基于 TypeScript 开发，集成 LangChain；支持 Redis 存活检测、DocumentDB 协调、OpenID 与 MCP OAuth 会话、租户隔离；提供 Railway、Zeabur、Sealos 一键部署方案；活跃维护（当前版本 v0.8.8-rc3）。

---
## 10. [pacifio/atlas](https://github.com/pacifio/atlas)
- **语言**: Rust
- **Stars**: 4,645
- **简介**: Source control for agents. Use multiple coding agents, track their changes and query them in one place

### AI 总结
**简介**: Atlas 是一款为编码 Agent 打造的源码控制工具，将每次 Agent 运行的提交与会话上下文（提示词、工具调用、推理过程）关联起来，让多个 Agent 在同一代码库上协同工作并共享记忆。

**核心功能**:
- **提交可追溯**：每次提交（checkpoint）都关联到产生它的会话，保留提示词、工具调用和文件变更，数月后仍可查询。
- **多 Agent 并行运行**：支持 Claude Code、Codex、Atlas 自带 Agent 及 ACP 注册表中的任意 Agent 在同一窗口、同一代码库上并排运行，中途切换无需重来。
- **统一共享记忆**：不同 Agent 之间的决策、计划、文件变更、失败记录和架构笔记自动共享，基于设备端匹配当前提问内容。
- **笔记即上下文**：`.atlas/knowledge/` 中的 Markdown 以及已有的 `CLAUDE.md`、`AGENTS.md` 会自动喂给项目中的所有 Agent。
- **`@` 引用任意内容**：文件、文件夹、符号、分支、提交、笔记、论文和历史会话均在本地解析后注入提示词。
- **本地优先**：代码、笔记和会话默认保存在本地，需要团队同步时可登录并创建组织。

**技术亮点**: 基于 Rust 与 Tauri 构建，主要支持 macOS 平台（Linux/Windows 可从同一代码库编译但未测试），采用 MIT 许可证。

---
