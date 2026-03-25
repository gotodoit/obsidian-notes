---
tags:
  - github-trending
  - daily
date: 2026-03-25
created: 2026-03-25T01:55:50.346Z
---

# 2026-03-25 GitHub Trending Top 10

## 1. [pascalorg/editor](https://github.com/pascalorg/editor)
- **语言**: TypeScript
- **Stars**: 5,328
- **简介**: 

### AI 总结
**简介**: Pascal Editor 是一个基于 React Three Fiber 和 WebGPU 构建的 3D 建筑编辑器。

**核心功能**:
- 提供 3D 场景编辑能力，支持创建和管理建筑、楼层、墙体、区域等多种节点。
- 采用状态驱动架构，通过 Zustand 状态库管理场景、视图和编辑器状态，并支持持久化与撤销/重做。
- 实现了渲染与逻辑分离的模块化设计，核心逻辑、3D渲染和编辑器界面分别位于独立的包中。

**技术亮点**:
- **技术栈**: 使用 TypeScript、Next.js、React Three Fiber、WebGPU 和 Turborepo 单仓架构。
- **架构特点**: 采用“节点-渲染器-系统”模式，节点数据扁平化存储，通过注册表高效映射到 Three.js 对象，系统组件在渲染循环中异步处理几何更新。

---
## 2. [bytedance/deer-flow](https://github.com/bytedance/deer-flow)
- **语言**: Python
- **Stars**: 43,462
- **简介**: An open-source SuperAgent harness that researches, codes, and creates. With the help of sandboxes, memories, tools, skill, subagents and message gateway, it handles different levels of tasks that could take minutes to hours.

### AI 总结
**简介**: DeerFlow 是一个由字节跳动开源的超级智能体框架，它通过编排子智能体、记忆和沙箱，利用可扩展的技能来处理从几分钟到数小时的不同复杂度的任务。

**核心功能**:
- **子智能体编排**: 协调多个子智能体共同完成任务。
- **沙箱与文件系统**: 提供安全的代码执行和文件操作环境。
- **长期记忆**: 支持智能体在任务执行过程中保留和利用历史信息。
- **技能与工具集成**: 拥有可扩展的技能库，并集成了Claude Code等工具。
- **上下文工程**: 优化和管理智能体的上下文信息。

**技术亮点**:
- **多语言支持**: 后端主要使用 Python 3.12+，前端/构建涉及 Node.js 22+。
- **架构重构**: 2.0 版本是完全重写的版本，与 1.x 版本无代码共享。
- **部署灵活**: 推荐使用 Docker 进行容器化部署，也支持本地开发模式。
- **模型友好**: 官方推荐使用豆包、DeepSeek、Kimi 等大语言模型运行。
- **集成生态**: 集成了字节跳动的 InfoQuest 智能搜索与爬取工具集。

---
## 3. [supermemoryai/supermemory](https://github.com/supermemoryai/supermemory)
- **语言**: TypeScript
- **Stars**: 18,594
- **简介**: Memory engine and app that is extremely fast, scalable. The Memory API for the AI era.

### AI 总结
**简介**: Supermemory 是一个专为 AI 设计的、极速且可扩展的记忆与上下文引擎，旨在解决 AI 在对话间遗忘信息的问题。

**核心功能**:
- **记忆管理**: 自动从对话中提取事实，处理时间变化、矛盾信息，并自动遗忘过期内容。
- **用户画像**: 自动维护用户上下文（稳定事实 + 近期活动），调用延迟约 50ms。
- **混合搜索**: 在单一查询中结合 RAG 与记忆，同时检索知识库文档和个性化上下文。
- **多源连接器**: 支持自动同步 Google Drive、Gmail、Notion、OneDrive、GitHub 等，并具备实时 Webhook。
- **多模态提取**: 支持处理 PDF、图像（OCR）、视频（转录）、代码（基于 AST 的分块）等多种格式。

**技术亮点**: 基于 TypeScript 开发，提供统一的记忆结构与本体论，在 LongMemEval、LoCoMo 和 ConvoMem 三大 AI 记忆基准测试中排名第一。提供 npm 和 PyPI 包，支持通过 API、MCP 服务器及多种插件（如 Claude Code、OpenCode）快速集成。

---
## 4. [FujiwaraChoki/MoneyPrinterV2](https://github.com/FujiwaraChoki/MoneyPrinterV2)
- **语言**: Python
- **Stars**: 24,866
- **简介**: Automate the process of making money online.

### AI 总结
**简介**: MoneyPrinter V2 是一个用 Python 编写的自动化在线赚钱工具，是原项目的完全重写版，专注于更广泛的功能和模块化架构。

**核心功能**:
- Twitter 机器人（支持 CRON 作业调度）
- YouTube Shorts 自动化（支持 CRON 作业调度）
- 联盟营销（亚马逊 + Twitter）
- 寻找本地企业并进行冷接触

**技术亮点**: 采用模块化架构，需要 Python 3.12 运行，并集成了社区贡献的多语言版本（如中文版 MoneyPrinterTurbo）。

---
## 5. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)
- **语言**: Python
- **Stars**: 52,665
- **简介**: 利用AI大模型，一键生成高清短视频 Generate short videos with one click using AI LLM.

### AI 总结
**简介**: MoneyPrinterTurbo 是一个基于 AI 大模型的自动化短视频生成工具，用户只需提供主题或关键词，即可全自动生成包含文案、素材、字幕和背景音乐的高清短视频。

**核心功能**:
- 支持通过 Web 界面和 API 两种方式操作，代码采用 MVC 架构，易于维护。
- 可根据主题自动生成视频文案，也支持自定义文案。
- 支持多种视频尺寸（如竖屏 9:16 和横屏 16:9）和批量视频生成。
- 集成字幕生成与自定义功能（字体、颜色、位置等），并支持背景音乐。
- 视频素材来源高清且无版权，也支持使用本地素材。
- 支持多种 AI 模型接入，包括 OpenAI、Moonshot、DeepSeek、通义千问、文心一言等。

**技术亮点**:
- 支持多种主流和国产大语言模型，方便不同地区用户选择。
- 提供 Google Colab 在线体验和 Windows 一键启动包，降低使用门槛。
- 项目结构清晰，具备完整的 Web 和 API 接口，便于二次开发与集成。

---
## 6. [Crosstalk-Solutions/project-nomad](https://github.com/Crosstalk-Solutions/project-nomad)
- **语言**: TypeScript
- **Stars**: 15,383
- **简介**: Project N.O.M.A.D, is a self-contained, offline survival computer packed with critical tools, knowledge, and AI to keep you informed and empowered—anytime, anywhere.

### AI 总结
**简介**: Project N.O.M.A.D. 是一个自包含、优先离线的生存知识服务器，集成了关键工具、知识和本地AI，旨在让用户随时随地获取信息并保持自主能力。

**核心功能**:
- **AI聊天与知识库**: 基于Ollama的本地AI聊天，支持文档上传和语义搜索（通过Qdrant实现RAG）。
- **离线信息库**: 通过Kiwix提供离线维基百科、医学参考、电子书等资源。
- **教育平台**: 集成Kolibri，提供可汗学院课程及进度跟踪。
- **离线地图**: 通过ProtoMaps提供可下载的区域地图。
- **数据工具**: 集成CyberChef，用于加密、编码、哈希和数据分析。
- **本地笔记**: 通过FlatNotes支持Markdown的本地笔记应用。
- **系统基准测试**: 硬件性能评分与社区排行榜。

**技术亮点**: 项目采用Docker容器化架构，通过一个统一的“指挥中心”管理界面和API来编排所有工具与服务，实现一键安装、配置和更新。核心栈包括TypeScript、Docker、Ollama、Qdrant、Kiwix和Kolibri。

---
## 7. [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)
- **语言**: Python
- **Stars**: 40,908
- **简介**: TradingAgents: Multi-Agents LLM Financial Trading Framework

### AI 总结
**简介**: TradingAgents 是一个基于大型语言模型（LLM）的多智能体金融交易框架，旨在模拟真实交易公司的运作模式，通过分工协作的智能体进行市场分析和交易决策。

**核心功能**:
- 部署专业化的LLM智能体团队，包括基本面分析师、情绪分析师、新闻分析师、技术分析师、交易员和风险管理团队。
- 智能体之间进行动态讨论，以协同评估市场状况并确定最优交易策略。
- 支持多种主流LLM提供商（如GPT-5.x、Gemini 3.x、Claude 4.x、Grok 4.x）和最新的模型版本。

**技术亮点**: 采用多智能体系统架构，将复杂的交易任务分解为专业化角色，实现了可扩展、鲁棒的市场分析与决策流程。框架支持多语言，并提供了跨平台的稳定性。

---
## 8. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 5,619
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个能够跨多个平台（Reddit、X、YouTube、Hacker News、Polymarket 等）自动研究指定主题，并生成带真实引用的综合性摘要的 AI Agent 技能。

**核心功能**:
- **多平台聚合研究**：自动搜索过去30天内 Reddit、X、Bluesky、YouTube、TikTok、Instagram、Hacker News、Polymarket 及全网内容。
- **智能分析与摘要**：通过多信号质量排名、相关性评分、去重和跨平台收敛检测，生成基于数据的、带引用的综合性叙述报告。
- **对比研究模式**：支持“X vs Y”格式的查询，进行并行研究并提供并排比较、优劣势分析和数据驱动的结论。
- **结果自动归档**：每次运行都会将完整的简报自动保存为 Markdown 文件，构建个人研究库。

**技术亮点**:
- 采用 **Python** 开发，支持在 Claude Code 和 ClawHub 平台安装使用。
- 集成 **ScrapeCreators API**，一个密钥覆盖 Reddit、TikTok、Instagram 三个数据源。
- 实现复杂的 **复合评分管道**，包括双向文本相似性、参与度标准化、来源权威性加权和时效性衰减。
- 支持 **项目级环境配置** 和 **会话启动时自动配置验证**，拥有超过455个测试用例的广泛测试覆盖。

---
## 9. [ruvnet/ruflo](https://github.com/ruvnet/ruflo)
- **语言**: TypeScript
- **Stars**: 25,138
- **简介**: 🌊 The leading agent orchestration platform for Claude. Deploy intelligent multi-agent swarms, coordinate autonomous workflows, and build conversational AI systems. Features enterprise-grade architecture, distributed swarm intelligence, RAG integration, and native Claude Code / Codex Integration

### AI 总结
**简介**: RuFlo 是一个基于 TypeScript 开发的企业级 AI 智能体编排平台，专为 Claude Code 设计，用于部署和协调多智能体集群，以完成复杂的软件工程任务。

**核心功能**:
- **多智能体集群编排**: 支持部署和协调 60 多个具备自学习能力的专业化智能体，支持多种集群拓扑结构。
- **企业级架构**: 包含路由层、集群协调层、资源管理层和 RuVector 智能层，具备容错共识机制和安全特性。
- **原生集成与扩展**: 深度集成 Claude Code，并支持 GPT、Gemini、Ollama 等多种 LLM 提供商，提供 RAG 集成。

**技术亮点**:
- **自学习/自优化架构**: 采用包含检索、判断、提炼、巩固和路由的闭环学习循环。
- **RuVector 智能层**: 集成了 SONA（自优化）、EWC++（防遗忘）、Flash Attention、HNSW（高效向量搜索）等多种高性能算法。
- **底层性能**: 使用 Rust 编写的 WASM 内核驱动策略引擎、嵌入和证明系统，强调高性能与效率。

---
## 10. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 12,577
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 开发、具备自我学习和成长能力的 AI 代理，支持在多种环境和平台上运行。

**核心功能**:
- **多平台接入**：支持通过 Telegram、Discord、Slack、WhatsApp、Signal 等即时通讯工具以及 CLI 终端进行交互。
- **自我学习与技能进化**：具备内置的学习循环，能够从经验中创建技能，并在使用中不断改进，支持跨会话记忆搜索和用户建模。
- **灵活部署与运行**：可在本地、Docker、SSH、云服务器（如 $5 VPS）、GPU 集群以及 Daytona、Modal 等无服务器基础设施上运行，成本低廉。
- **多模型支持**：兼容 Nous Portal、OpenRouter、OpenAI、Kimi 等多种模型提供商，可通过命令轻松切换，无供应商锁定。
- **自动化与并行处理**：内置定时任务调度器，可生成子代理并行处理工作流，并能将多步骤任务编译为 Python 脚本以降低上下文开销。

**技术亮点**:
- 提供功能完整的终端用户界面（TUI），支持多行编辑、命令自动补全和流式工具输出。
- 采用模块化架构，集成了 Honcho 用户建模和 agentskills.io 开放标准。
- 支持研究用途，如批量轨迹生成、Atropos RL 环境和轨迹压缩，用于训练下一代工具调用模型。

---
