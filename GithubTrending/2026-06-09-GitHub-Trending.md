---
tags:
  - github-trending
  - daily
date: 2026-06-09
created: 2026-06-09T01:55:45.444Z
---

# 2026-06-09 GitHub Trending Top 10

## 1. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 34,680
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个AI代理驱动的搜索引擎，能够跨Reddit、X、YouTube、Hacker News、Polymarket等多个平台搜索内容，并根据真实用户参与度（点赞、投票、金钱押注）进行评分，最终合成一份基于事实的摘要。

**核心功能**:
- **跨平台聚合搜索**: 并行搜索Reddit、X、YouTube、TikTok、Instagram Reels、Hacker News、Polymarket、GitHub、Digg等多个平台的内容。
- **基于真实参与度的评分系统**: 使用平台的点赞、投票、评论和真实金钱押注（Polymarket）作为评分依据，而非编辑推荐或搜索引擎算法。
- **AI代理智能摘要**: 由AI代理将来自不同平台的搜索结果整合成一份简洁、有洞见的摘要。
- **零配置与可扩展**: Reddit、Hacker News、Polymarket、GitHub即开即用，可通过设置向导快速解锁X、YouTube、TikTok等平台。
- **多AI主机支持**: 兼容Claude Code、Codex、Cursor、Copilot、Gemini CLI等50多种AI代理主机。

**技术亮点**:
- **Python实现**: 使用Python构建核心逻辑。
- **代理架构**: 采用AI代理作为核心，连接并协调各个“围墙花园”平台。
- **插件化部署**: 支持通过插件市场或`npx skills`命令安装，易于集成到不同AI开发环境。

---
## 2. [RyanCodrai/turbovec](https://github.com/RyanCodrai/turbovec)
- **语言**: Python
- **Stars**: 8,947
- **简介**: A vector index built on TurboQuant, written in Rust with Python bindings

### AI 总结
**简介**: turbovec 是一个基于 Google TurboQuant 算法、用 Rust 编写并提供 Python 绑定的高效向量索引库，能以极低内存占用实现比 FAISS 更快的向量搜索。

**核心功能**:
- **在线增量索引**：支持实时添加向量，无需预训练或参数调优，无需重建索引。
- **快速搜索**：通过手写的 SIMD 内核（NEON/AVX-512BW）实现比 FAISS IndexPQFastScan 快 12-20% 的搜索性能。
- **带过滤的搜索**：支持通过 ID 允许列表或位掩码进行搜索时过滤，在 SIMD 内核级别直接处理，避免过度获取。
- **纯本地运行**：无需托管服务，数据不离开本地或 VPC，可配合开源嵌入模型实现完全隔离的 RAG 流水线。
- **稳定的 ID 管理**：提供 `IdMapIndex` 支持用户自定义外部 ID，可持久化、删除和按 ID 搜索。
- **框架集成**：提供 LangChain、LlamaIndex、Haystack、Agno 等框架的即插即用集成。

**技术亮点**: 基于 Google 的 TurboQuant 数据无关量化算法，匹配香农失真下界，无需码本训练；采用 Rust 编写，核心使用手写 SIMD 内核（ARM NEON 和 x86 AVX-512BW）实现高性能；支持 4-bit 量化，1000 万文档仅需 4 GB 内存（原需 31 GB）。

---
## 3. [google/skills](https://github.com/google/skills)
- **语言**: Python
- **Stars**: 12,454
- **简介**: Agent Skills for Google products and technologies

### AI 总结
**简介**: 这是一个为 Google 产品和技术提供 Agent Skills 的开源仓库，支持通过命令行快速安装和使用。

**核心功能**:
- 提供 Gemini API、Managed Agents API 等 Google Cloud 服务的 Agent Skills
- 包含 AlloyDB、BigQuery、Cloud Run 等 Google Cloud 基础服务的技能模块
- 提供 Google Cloud 最佳实践指南（如身份验证、网络可观测性、Well-Architected Framework 六大支柱）

**技术亮点**: 基于 Python 开发，通过 `npx skills add` 命令实现模块化安装，支持按需选择安装特定技能，遵循 Apache 2.0 开源协议。

---
## 4. [refactoringhq/tolaria](https://github.com/refactoringhq/tolaria)
- **语言**: TypeScript
- **Stars**: 13,616
- **简介**: Desktop app to manage markdown knowledge bases

### AI 总结
**简介**: Tolaria 是一款跨平台桌面应用，用于管理基于 Markdown 的个人知识库，强调文件优先、离线可用和开源。

**核心功能**:
- 管理 Markdown 知识库，支持个人知识管理、团队文档组织、AI 上下文存储等多种场景
- 基于 Git 的版本管理，支持完整历史记录和远程仓库
- 离线优先，无需账户或订阅，数据完全归用户所有
- 支持 AI 集成（Claude Code、Codex CLI 等），提供 AGENTS 文件辅助配置
- 键盘优先设计，提供命令面板和高效编辑器
- 支持通过 Homebrew 或手动下载安装，兼容 macOS、Windows 和 Linux

**技术亮点**: 使用 TypeScript 开发，基于 Tauri（Rust）和 React 构建，采用文件优先的架构设计，支持 YAML frontmatter 标准格式，所有数据以纯文本 Markdown 文件存储，无任何专有格式或锁定。

---
## 5. [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)
- **语言**: Python
- **Stars**: 24,263
- **简介**: Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees.

### AI 总结
**简介**: 一个零API费用的命令行工具，为AI Agent赋予浏览和搜索Twitter、Reddit、YouTube等主流互联网平台的能力。

**核心功能**:
- **多平台支持**: 无需配置即可阅读网页、YouTube字幕、RSS订阅，配置后解锁Twitter、B站、小红书、抖音等平台的搜索与内容获取
- **一键安装/更新**: 用户只需复制安装命令给AI Agent，即可自动完成所有依赖安装和配置
- **健康诊断**: 提供 `agent-reach doctor` 命令，快速检查各平台连接状态并给出修复建议
- **安全与隐私**: Cookie仅存储在本地，代码完全开源，支持安全安装模式

**技术亮点**:
- 基于Python 3.10+开发，通过MCP协议集成免费搜索引擎（无需API Key）
- 底层整合yt-dlp、twitter-cli、rdt-cli、Jina Reader等成熟工具，自动追踪更新
- 兼容Claude Code、OpenClaw、Cursor、Windsurf等主流AI Agent平台

---
## 6. [danielmiessler/Personal_AI_Infrastructure](https://github.com/danielmiessler/Personal_AI_Infrastructure)
- **语言**: TypeScript
- **Stars**: 15,453
- **简介**: Agentic AI Infrastructure for magnifying HUMAN capabilities.

### AI 总结
**简介**: PAI 是一个以放大人类能力为目标的 Agentic AI 基础设施，旨在成为每个人的“生活操作系统”。

**核心功能**:
- **统一 Pulse 守护进程**: 提供本地生活仪表盘 (`localhost:31337`)，集中管理和监控个人 AI 活动。
- **数字助理 (DA) 身份层**: 为每个用户创建专属的 AI 身份与交互层。
- **Algorithm v6.3.0**: 采用七阶段“当前状态 → 理想状态”的算法框架，通过分类器驱动实现智能决策。
- **ISA 原语**: 通用“理想状态”表述，用于统一和指导 AI 行动。
- **丰富的技能与工作流**: 内置 45 项技能、171 个工作流和 37 个钩子，覆盖多种自动化场景。
- **结构性隐私**: 通过隔离区域实现数据安全与隐私保护。

**技术亮点**:
- **技术栈**: 基于 TypeScript 构建，使用 Bun 运行时，并深度集成 Claude。
- **架构特点**: 采用 Agentic AI 架构，强调“当前状态 → 理想状态”的闭环驱动，并内置结构化的隐私隔离机制。

---
## 7. [santifer/career-ops](https://github.com/santifer/career-ops)
- **语言**: JavaScript
- **Stars**: 50,568
- **简介**: AI-powered job search system built on Claude Code. 14 skill modes, Go dashboard, PDF generation, batch processing.

### AI 总结
**简介**: Career-Ops 是一个基于 AI 的求职系统，能将任何 AI 编码 CLI 转化为求职指挥中心，帮助求职者高效筛选和申请工作。

**核心功能**:
- **智能评估**: 使用 A-F 评分系统（10 个加权维度）对职位进行结构化评估
- **自动生成 PDF**: 为每个职位描述生成 ATS 优化的个性化简历
- **批量处理**: 通过子代理并行评估 10+ 个职位
- **自动扫描**: 自动扫描 Greenhouse、Ashby、Lever 等招聘门户和公司页面
- **全流程追踪**: 在单一数据源中追踪所有申请，包含完整性检查

**技术亮点**: 基于 Claude Code 构建，使用 Playwright 进行网页导航，Go 语言开发仪表盘，支持 14 种技能模式，采用 Node.js 和 Bubble Tea 框架，支持多代理并行处理。

---
## 8. [phuryn/pm-skills](https://github.com/phuryn/pm-skills)
- **语言**: Unknown
- **Stars**: 12,731
- **简介**: PM Skills Marketplace: 100+ agentic skills, commands, and plugins — from discovery to strategy, execution, launch, and growth.

### AI 总结
**简介**: PM Skills Marketplace 是一个为 AI 助手（如 Claude Code、Cowork）设计的技能市场，提供超过 100 个产品管理技能、命令和插件，覆盖从产品发现到增长的全流程。

**核心功能**:
- **技能库**: 包含 68 个独立 PM 技能，如发现、假设映射、优先级排序、战略制定等，可自动加载或手动触发。
- **命令工作流**: 42 个链式命令（如 `/discover`、`/write-prd`），将多个技能串联成端到端流程，并支持流程间无缝衔接。
- **插件系统**: 9 个可安装插件包，涵盖发现、战略、执行、上市、增长等 PM 领域，一键安装全部或按需选择。
- **多平台兼容**: 支持 Claude Cowork、Claude Code 和 Codex CLI（OpenAI），安装方式简单统一。

**技术亮点**: 技能采用框架化编码（如 Teresa Torres、Marty Cagan 的经典方法论），命令自动建议下一步流程，插件通过 GitHub marketplace 分发，支持开源贡献（MIT 许可）。

---
## 9. [openai/plugins](https://github.com/openai/plugins)
- **语言**: JavaScript
- **Stars**: 2,333
- **简介**: OpenAI Plugins

### AI 总结
**简介**: 这是一个由 OpenAI 维护的 Codex 插件示例集合，展示了如何构建和扩展 Codex 的能力。

**核心功能**:
- 提供丰富的插件示例，涵盖 Figma、Notion、iOS/macOS/Web 应用构建、Expo 等场景
- 每个插件包含标准化的 `plugin.json` 清单文件，支持 skills、agents、commands 等扩展组件
- 支持 MCP（Model Context Protocol）和公共技能包，便于插件集成与复用

**技术亮点**: 基于 JavaScript 开发，采用模块化插件架构，通过清单文件统一管理插件配置与扩展组件

---
## 10. [Andyyyy64/whichllm](https://github.com/Andyyyy64/whichllm)
- **语言**: Python
- **Stars**: 3,502
- **简介**: Find the local LLM that actually runs and performs best on your hardware. Ranked by real, recency-aware benchmarks, not parameter count. One command, run it instantly.

### AI 总结
**简介**: 一款能根据用户硬件自动推荐最适合的本地大语言模型（LLM）的命令行工具，基于真实基准评分而非仅看参数量。

**核心功能**:
- **硬件自动检测与推荐**: 自动识别 GPU/CPU/RAM 配置，从 HuggingFace 实时获取并排名最适合的模型。
- **硬件模拟与规划**: 支持 `--gpu "RTX 4090"` 等参数，模拟未拥有的硬件进行推荐；或通过 `plan` 命令查找运行特定模型所需的 GPU。
- **一键运行与代码生成**: 直接通过 `run` 命令下载并启动模型聊天；`snippet` 命令可生成可直接运行的 Python 代码片段。
- **JSON 输出与脚本集成**: 支持 `--json` 参数输出结构化数据，方便在自动化脚本（如配合 `jq`）中使用。

**技术亮点**:
- **综合基准评分**: 融合 LiveBench、Aider、Chatbot Arena ELO 等多个真实基准，进行证据分级（direct/variant/base/interpolated/self-reported），并主动拒绝虚假数据。
- **时效性感知**: 对过时的基准结果按时间线降权，确保最新模型不被旧数据压制。
- **架构感知估算**: 根据模型架构（如 GQA KV cache、MoE 参数拆分）和硬件带宽精确估算 VRAM 占用和推理速度。
- **实时数据与离线回退**: 默认从 HuggingFace API 实时获取数据，同时内置冻结的离线数据作为备份。

---
