---
tags:
  - github-trending
  - daily
date: 2026-02-26
created: 2026-02-26T01:55:47.318Z
---

# 2026-02-26 GitHub Trending Top 10

## 1. [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling)
- **语言**: Python
- **Stars**: 15,148
- **简介**: 🕷️ An adaptive Web Scraping framework that handles everything from a single request to a full-scale crawl!

### AI 总结
**简介**: Scrapling 是一个自适应的 Python Web 爬虫框架，能够处理从单次请求到大规模并发爬取的所有任务。

**核心功能**:
- **自适应解析器**: 能够学习网站的变化，在页面更新时自动重新定位目标元素，确保数据提取的稳定性。
- **智能请求器**: 内置多种请求器（如 `StealthyFetcher`），可绕过 Cloudflare Turnstile 等反机器人系统，支持无头模式和网络空闲检测。
- **可扩展的爬虫框架**: 提供 `Spider` 基类，支持并发、多会话的爬取，具备暂停/恢复和自动代理轮换功能。
- **命令行工具与 MCP 支持**: 提供 CLI 工具，并支持模型上下文协议（MCP），便于集成和自动化。

**技术亮点**: 框架设计强调“为爬虫开发者而生”，支持实时统计和流式处理，性能出色。其核心在于通过 `adaptive=True` 等参数实现解析逻辑的自我调整，并能轻松从简单数据提取扩展到复杂的分布式爬虫架构。

---
## 2. [huggingface/skills](https://github.com/huggingface/skills)
- **语言**: Python
- **Stars**: 6,419
- **简介**: 

### AI 总结
**简介**: Hugging Face Skills 是一个遵循 Agent Skills 标准格式的技能库，为 AI 代理（如 Claude Code、Codex、Gemini CLI 和 Cursor）提供了一系列用于处理 Hugging Face 生态任务的标准化指令和脚本。

**核心功能**:
- 提供多种预定义技能，涵盖 Gradio 应用构建、Hugging Face Hub 的 CLI 操作、数据集管理、模型评估和训练任务。
- 兼容主流 AI 编程代理工具（Claude Code、OpenAI Codex、Google Gemini CLI、Cursor），通过标准化的 `SKILL.md` 文件或工具特定格式（如 `gemini-extension.json`）提供指导。
- 支持灵活的安装方式，可通过插件市场、本地复制/链接或直接安装脚本集成到不同的代理环境中。

**技术亮点**: 采用开源的 [Agent Skills](https://agentskills.io/specification) 标准化格式，确保技能在不同工具间的互操作性；同时为不支持技能的工具提供了统一的 `agents/AGENTS.md` 文件作为回退方案。

---
## 3. [abhigyanpatwari/GitNexus](https://github.com/abhigyanpatwari/GitNexus)
- **语言**: TypeScript
- **Stars**: 3,753
- **简介**: GitNexus: The Zero-Server Code Intelligence Engine - GitNexus is a client-side knowledge graph creator that runs entirely in your browser. Drop in a GitHub repo or ZIP file, and get an interactive knowledge graph wit a built in Graph RAG Agent. Perfect for code exploration

### AI 总结
**简介**: GitNexus 是一个完全在浏览器中运行的客户端知识图谱引擎，无需服务器，可将任何代码库（GitHub 仓库或 ZIP 文件）转换为交互式知识图谱，并内置图 RAG 智能体，用于代码探索与分析。

**核心功能**:
- **零服务器/浏览器端运行**：所有处理均在本地浏览器中完成，保障隐私，无需上传代码到远程服务器。
- **代码库知识图谱化**：自动解析代码库，构建包含依赖关系、调用链、代码簇和执行流程的知识图谱。
- **智能工具集成**：提供 Web UI 进行可视化图谱探索和 AI 对话，以及 CLI + MCP（模型上下文协议）工具，为 Cursor、Claude Code 等 AI 编码助手提供深度的代码架构上下文。
- **双模式使用**：支持便捷的 Web 界面进行快速探索，也支持通过 CLI 本地索引大型代码库，并通过“桥接模式”让 Web UI 访问本地已索引的仓库。

**技术亮点**:
- 采用 **TypeScript** 开发。
- 使用 **Tree-sitter**（支持原生绑定和 WASM 版本）进行精准的代码解析。
- 利用 **KuzuDB** 图数据库（支持原生版本和 WASM 版本）高效存储和查询知识图谱。
- 通过 **MCP 协议**与主流 AI 编码工具（Claude Code, Cursor, Windsurf, OpenCode）深度集成，增强其代码理解能力。

---
## 4. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 61,892
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个基于可组合“技能”和预设指令构建的、面向编码智能体的完整软件开发工作流框架。

**核心功能**:
- **智能工作流触发**：在编码任务开始前，自动触发“头脑风暴”技能，通过提问澄清需求并生成可审阅的设计文档。
- **子智能体驱动开发**：在计划批准后，启动子智能体并行处理分解后的工程任务，并自动进行代码审查和质量检查。
- **强制测试驱动开发**：在实现过程中强制执行“红-绿-重构”的TDD循环，确保代码质量。
- **Git工作树集成**：在开发时自动创建隔离的Git工作树和分支，保持主工作区清洁。
- **全流程自动化**：涵盖从设计、计划、编码、测试、审查到分支收尾的完整开发闭环，技能在相关任务前自动检查并应用。

**技术亮点**: 基于Shell脚本实现，强调技能的组合性与自动触发；深度集成主流的AI编码助手平台（如Claude Code、Cursor、Codex、OpenCode）；其“子智能体驱动开发”架构支持长时间自主运行而不偏离原计划。

---
## 5. [muratcankoylan/Agent-Skills-for-Context-Engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering)
- **语言**: Python
- **Stars**: 10,769
- **简介**: A comprehensive collection of Agent Skills for context engineering, multi-agent architectures, and production agent systems. Use when building, optimizing, or debugging agent systems that require effective context management.

### AI 总结
**简介**: 一个专注于上下文工程、多智能体架构和生产级智能体系统的综合性智能体技能集合。

**核心功能**:
- 提供从基础到高级的上下文工程技能，涵盖上下文基础、退化模式、压缩策略等。
- 包含构建智能体系统的架构技能，如多智能体模式、内存系统、工具设计和文件系统上下文管理。
- 提供用于系统优化和评估的操作技能，包括上下文优化、评估框架和高级LLM评判技术。
- 涵盖项目开发方法论和基于BDI（信念-期望-意图）模型的认知架构技能。

**技术亮点**:
- **渐进式披露设计**: 技能按需加载，优化上下文使用效率。
- **平台无关性**: 技能基于可迁移的原则设计，适用于Claude Code、Cursor等多种智能体平台。
- **理论与实践结合**: 提供概念基础和Python伪代码示例，便于理解和跨环境应用。

---
## 6. [datawhalechina/hello-agents](https://github.com/datawhalechina/hello-agents)
- **语言**: Python
- **Stars**: 22,003
- **简介**: 📚 《从零开始构建智能体》——从零开始的智能体原理与实践教程

### AI 总结
**简介**: 一个从零开始、理论与实战并重的智能体（Agent）系统构建教程，旨在帮助开发者从大语言模型的使用者转变为智能体系统的构建者。

**核心功能**:
- 提供从智能体基础理论、发展历史到核心架构的完整知识体系。
- 包含动手实践环节，指导使用低代码平台（如Coze、Dify）和主流代码框架（如AutoGen、LangGraph）。
- 引导开发者从零开始构建自研的智能体框架（HelloAgents）。
- 涵盖高级主题，如记忆与检索、上下文工程、智能体通信协议、Agentic-RL模型训练和性能评估。
- 通过综合案例（如智能旅行助手、赛博小镇）进行实战演练。

**技术亮点**: 教程内容覆盖了AI Native Agent的核心技术栈，包括OpenAI原生API、Transformer模型、RAG、多种智能体通信协议（MCP、A2A等）以及从SFT到GRPO的LLM训练流程。

---
## 7. [bytedance/deer-flow](https://github.com/bytedance/deer-flow)
- **语言**: TypeScript
- **Stars**: 20,469
- **简介**: An open-source SuperAgent harness that researches, codes, and creates. With the help of sandboxes, memories, tools, skills and subagents, it handles different levels of tasks that could take minutes to hours.

### AI 总结
**简介**: DeerFlow 是一个开源的超级智能体框架，通过编排子智能体、记忆和沙箱环境，结合可扩展的技能库，以处理从几分钟到数小时不等的复杂任务。

**核心功能**:
- **技能与工具**: 提供可扩展的技能和工具库，增强智能体的能力。
- **子智能体**: 支持编排多个子智能体协同工作。
- **沙箱与文件系统**: 提供安全的代码执行环境，支持本地、Docker及Kubernetes等多种运行模式。
- **上下文工程**: 优化任务执行的上下文管理。
- **长期记忆**: 为智能体提供持久化记忆能力。

**技术亮点**: 基于 TypeScript 开发，采用 LangChain 集成主流大模型（如 GPT-4），支持通过 MCP 服务器扩展功能，并提供 Docker 一键部署。

---
## 8. [VectifyAI/PageIndex](https://github.com/VectifyAI/PageIndex)
- **语言**: Python
- **Stars**: 17,728
- **简介**: 📑 PageIndex: Document Index for Vectorless, Reasoning-based RAG

### AI 总结
**简介**: PageIndex 是一个无需向量数据库和分块的、基于推理的检索增强生成（RAG）系统，它通过构建文档的层次化树状索引并利用大语言模型进行推理检索，以模拟人类专家处理复杂文档的方式。

**核心功能**:
- **无向量数据库检索**：利用文档结构和LLM推理进行检索，而非传统的向量相似性搜索。
- **无需分块**：将文档组织成自然的章节结构，而非人工分割的文本块。
- **类人检索**：模拟人类专家浏览和提取复杂文档知识的过程，进行基于推理的检索。
- **更好的可解释性与可追溯性**：检索过程基于推理，可追溯且可解释，并提供页面和章节引用。

**技术亮点**: 采用**层次化树状索引**架构，通过“生成目录树”和“基于树搜索的推理检索”两步流程实现。该系统在专业长文档处理上表现出色，并在FinanceBench基准测试中达到了领先的准确率。

---
## 9. [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU)
- **语言**: Python
- **Stars**: 10,818
- **简介**: Memory for 24/7 proactive agents like openclaw (moltbot, clawdbot).

### AI 总结
**简介**: memU 是一个为 24/7 全天候主动式 AI 智能体设计的内存框架，旨在通过结构化记忆降低长期运行成本，并使其能够主动理解用户意图。

**核心功能**:
- **全天候主动运行**: 作为持续在后台工作的内存智能体，永不睡眠且不会遗忘。
- **用户意图捕捉**: 自动理解和记忆用户的目标、偏好及跨会话的上下文。
- **成本高效**: 通过缓存洞察和避免冗余的大语言模型调用，显著降低长期运行的令牌成本。
- **类文件系统内存管理**: 将记忆组织为类似文件系统的层次结构（类别、记忆项、交叉引用、挂载资源），实现结构化、可搜索和可移植的知识管理。

**技术亮点**: 采用类文件系统的内存架构，实现记忆的自动分类、交叉引用和资源挂载，构建互联的知识图谱；支持 Python 3.13+，并通过减少上下文长度来优化大语言模型令牌使用。

---
## 10. [ruvnet/ruvector](https://github.com/ruvnet/ruvector)
- **语言**: Rust
- **Stars**: 1,200
- **简介**: RuVector is a High Performance, Real-Time, Self-Learning, Vector Graph Neural Network, and Database built in Rust.

### AI 总结
**简介**: RuVector 是一个用 Rust 构建的高性能、实时、自学习的向量图神经网络和数据库。

**核心功能**:
- **智能向量搜索与图查询**：不仅存储和搜索向量嵌入，还支持类似 Neo4j 的 Cypher 图查询，并能通过图神经网络（GNN）使搜索结果随时间推移而自我优化。
- **一体化 AI 与机器学习**：内置本地运行 LLM 的能力（支持 GGUF 格式），提供预训练模型，并集成了 46 种注意力机制、脉冲神经网络等多种先进 AI 模块。
- **分布式与可扩展架构**：具备 Raft 共识、多主复制、自动分片和突发扩容能力，支持水平扩展，无按向量收费。
- **独特的部署与运行模式**：可作为“认知容器”以单个文件（`.rvf`）形式部署，快速自举为微服务，支持离线运行和 Git 式的数据分支管理。

**技术亮点**: 采用 Rust 语言开发，核心架构集成了 HNSW 索引、证明门控图变换器（8个已验证模块）、子线性求解器（如 PageRank）等先进技术，并通过 eBPF、见证链等技术实现轻量、安全、可验证的容器化部署。

---
