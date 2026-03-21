---
tags:
  - github-trending
  - daily
date: 2026-03-21
created: 2026-03-21T01:55:47.826Z
---

# 2026-03-21 GitHub Trending Top 9

## 1. [jarrodwatts/claude-hud](https://github.com/jarrodwatts/claude-hud)
- **语言**: JavaScript
- **Stars**: 9,567
- **简介**: A Claude Code plugin that shows what's happening - context usage, active tools, running agents, and todo progress

### AI 总结
**简介**: 一个用于 Claude Code 的插件，在输入框下方实时显示会话状态，包括上下文使用情况、活跃工具、运行中的代理和任务进度。

**核心功能**:
- **状态概览**: 实时显示项目路径、Git分支、当前使用的模型和计划名称。
- **上下文监控**: 以进度条形式直观展示上下文窗口的占用率，防止溢出。
- **活动追踪**: 显示Claude正在进行的文件读写、搜索编辑等工具活动。
- **代理与任务管理**: 展示正在运行的子代理状态及其任务，并跟踪待办事项的完成进度。

**技术亮点**: 基于Claude Code的原生状态栏API开发，通过解析标准输入（stdin）和会话记录（transcript JSONL）获取数据，无需额外窗口或tmux，可在任何终端中运行。

---
## 2. [langchain-ai/open-swe](https://github.com/langchain-ai/open-swe)
- **语言**: Python
- **Stars**: 7,657
- **简介**: An Open-Source Asynchronous Coding Agent

### AI 总结
**简介**: Open SWE 是一个开源的异步编码代理框架，旨在帮助组织构建类似 Stripe、Ramp 等公司的内部编码助手。

**核心功能**:
- 提供基于 LangGraph 和 Deep Agents 的代理架构，支持自定义编排、工具和中间件。
- 任务在隔离的云沙箱环境中运行，支持 Modal、Daytona 等多种提供商，确保安全与隔离。
- 内置精选工具集，包括执行 shell 命令、文件操作、Git 提交与 PR 创建、与 Linear 和 Slack 集成等。
- 支持从 `AGENTS.md` 和源代码中自动收集上下文，以指导代理行为。

**技术亮点**: 基于 LangGraph 和 Deep Agents 框架构建，采用云沙箱隔离、工具精选与上下文工程等架构模式，支持并行任务与持久化沙箱复用。

---
## 3. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 101,612
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为 AI 编码智能体设计的、基于可组合“技能”的软件开发框架与工作流方法论。

**核心功能**:
- **智能规划与设计**：在编码前，通过对话明确需求，生成并分段展示可审阅的设计规格。
- **子智能体驱动开发**：将任务分解为小单元，由独立的子智能体执行，并经过两阶段（规格符合度、代码质量）审查。
- **强制执行测试驱动开发**：在实现过程中强制遵循“红-绿-重构”的 TDD 循环，确保代码质量。
- **自动化工作流管理**：集成从头脑风暴、Git 工作树管理、代码审查到分支收尾的完整开发流程。

**技术亮点**: 采用基于“技能”的插件化架构，技能在任务前自动触发，形成一套强制的、非建议性的工作流。支持 Claude Code、Cursor、Codex、OpenCode、Gemini CLI 等多种 AI 开发平台。

---
## 4. [opendataloader-project/opendataloader-pdf](https://github.com/opendataloader-project/opendataloader-pdf)
- **语言**: Java
- **Stars**: 7,089
- **简介**: PDF Parser for AI-ready data. Automate PDF accessibility. Open-source.

### AI 总结
**简介**: 一个用于从PDF中提取AI就绪数据和自动化PDF可访问性合规的开源Java解析器。

**核心功能**:
- **AI数据提取**: 从任何PDF（数字、扫描、已标记）中提取结构化的Markdown、JSON（带边界框）和HTML，专为RAG/LLM管道设计。
- **自动化可访问性**: 提供端到端的布局分析和自动标记功能，可将未标记的PDF转换为符合规范的标记PDF（Tagged PDF），以应对全球可访问性法规。

**技术亮点**:
- **高性能与高精度**: 在基准测试中综合提取准确率排名第一（0.90），表格提取准确率达0.93，本地模式处理速度达0.05秒/页。
- **混合AI模式**: 结合确定性本地算法与AI，以处理复杂页面、扫描件OCR（80+语言）、无边框表格和公式。
- **行业合作与验证**: 与PDF协会及Dual Lab（veraPDF开发者）合作开发，遵循Well-Tagged PDF规范，并通过veraPDF进行自动化验证。
- **多语言SDK**: 提供Python、Node.js和Java SDK，支持快速集成。

---
## 5. [louis-e/arnis](https://github.com/louis-e/arnis)
- **语言**: Rust
- **Stars**: 11,607
- **简介**: Generate any location from the real world in Minecraft with a high level of detail.

### AI 总结
**简介**: Arnis 是一个用 Rust 编写的开源工具，能够利用真实世界的地理和建筑数据，在 Minecraft 中生成高细节、高精度的复杂世界。

**核心功能**:
- 基于 OpenStreetMap 的地理空间数据和海拔数据，生成反映真实世界地形、地貌和建筑的 Minecraft 世界。
- 支持生成任意真实世界地点，如家乡、大城市和自然景观。
- 提供图形用户界面，允许用户在地图上框选区域并自定义生成设置（如世界比例、出生点、建筑内部生成等）。
- 支持 Minecraft Java Edition (1.17+) 和 Bedrock Edition。

**技术亮点**:
- 采用 Rust 语言开发，注重性能优化和跨平台支持（Windows、macOS、Linux）。
- 项目架构强调模块化，将数据获取、处理和世界生成等组件清晰分离，以提高可维护性和可扩展性。
- 提供详细的命令行和 GUI 两种使用方式，并可通过 Nix 直接运行。

---
## 6. [newton-physics/newton](https://github.com/newton-physics/newton)
- **语言**: Python
- **Stars**: 3,481
- **简介**: An open-source, GPU-accelerated physics simulation engine built upon NVIDIA Warp, specifically targeting roboticists and simulation researchers.

### AI 总结
**简介**: Newton 是一个基于 NVIDIA Warp 构建的开源、GPU 加速的物理模拟引擎，主要面向机器人专家和仿真研究人员。

**核心功能**:
- 提供 GPU 加速的物理模拟计算，提升仿真性能与规模。
- 支持 OpenUSD，便于场景描述与数据交换。
- 具备可微分特性，支持基于梯度的优化和学习。
- 允许用户自定义扩展，实现快速迭代。

**技术亮点**:
- 核心基于 NVIDIA Warp 并集成了 MuJoCo Warp 作为主要后端。
- 由 Linux Foundation 支持，社区驱动维护。
- 支持 Linux、Windows 和 macOS（仅 CPU）平台，要求 NVIDIA GPU（Maxwell 或更新架构）。

---
## 7. [vas3k/TaxHacker](https://github.com/vas3k/TaxHacker)
- **语言**: TypeScript
- **Stars**: 1,959
- **简介**: Self-hosted AI accounting app. LLM analyzer for receipts, invoices, transactions with custom prompts and categories

### AI 总结
**简介**: TaxHacker 是一个自托管的AI会计应用，旨在通过大语言模型（LLM）为自由职业者、独立开发者和中小企业自动化处理收据、发票和交易，简化财务跟踪与税务申报。

**核心功能**:
- **AI智能分析**：支持上传收据、发票或PDF照片，自动识别并提取关键信息（如日期、金额、商户、商品明细），并存入结构化数据库。
- **多货币与加密货币支持**：自动检测文档中的货币，并基于交易日期的历史汇率进行转换，覆盖170多种法币和14种主流加密货币。
- **高度可定制化**：允许用户创建自定义类别、项目、字段，并可通过编写AI提示词来提取特定信息，满足个性化需求。
- **灵活的数据管理**：提供全文搜索、高级筛选、批量操作以及导入/导出功能，便于组织与检索交易记录。

**技术亮点**: 基于TypeScript开发，支持OpenAI、Google Gemini、Mistral等多种AI提供商，未来计划支持本地LLM；采用自托管架构，注重数据隐私与控制。

---
## 8. [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)
- **语言**: Python
- **Stars**: 34,148
- **简介**: TradingAgents: Multi-Agents LLM Financial Trading Framework

### AI 总结
**简介**: TradingAgents 是一个基于多智能体大语言模型（LLM）的金融交易框架，旨在模拟真实交易公司的动态协作。

**核心功能**:
- 部署专业化的LLM智能体（如基本面分析师、情绪分析师、技术分析师、交易员、风险管理团队）来协同评估市场状况并制定交易决策。
- 支持多提供商LLM（如GPT-5.x、Gemini 3.x、Claude 4.x、Grok 4.x），并持续更新模型覆盖范围。

**技术亮点**: 采用多智能体系统架构，将复杂的交易任务分解为不同专业角色，通过动态讨论来优化策略，实现了可扩展且稳健的市场分析与决策流程。

---
## 9. [openrocket/openrocket](https://github.com/openrocket/openrocket)
- **语言**: Java
- **Stars**: 2,226
- **简介**: Model-rocketry aerodynamics and trajectory simulation software

### AI 总结
**简介**: OpenRocket 是一款基于 Java 开发的免费、功能齐全的模型火箭空气动力学与弹道轨迹仿真软件，允许用户在真实建造和发射前进行火箭设计与模拟。

**核心功能**:
- 提供丰富的内置组件库，支持火箭的二维与三维可视化设计。
- 进行六自由度飞行模拟，并支持自动设计优化。
- 实时显示模拟的高度、速度和加速度数据。
- 支持多级火箭和发动机簇设计。
- 可导出设计到其他仿真程序（如 RockSim、RASAero II）或导出为 OBJ 文件用于 3D 打印。

**技术亮点**: 基于 Java 开发，具有跨平台特性；项目采用 GPL v3 开源协议，并拥有活跃的社区贡献和国际化支持。

---
