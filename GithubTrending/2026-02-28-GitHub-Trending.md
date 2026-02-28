---
tags:
  - github-trending
  - daily
date: 2026-02-28
created: 2026-02-28T01:55:50.686Z
---

# 2026-02-28 GitHub Trending Top 10

## 1. [ruvnet/wifi-densepose](https://github.com/ruvnet/wifi-densepose)
- **语言**: Python
- **Stars**: 9,355
- **简介**: Production-ready implementation of InvisPose - a revolutionary WiFi-based dense human pose estimation system that enables real-time full-body tracking through walls using commodity mesh routers

### AI 总结
**简介**: 一个基于WiFi信号、利用信道状态信息（CSI）和机器学习实现实时、隐私保护的人体姿态估计系统，无需摄像头即可进行穿墙追踪。

**核心功能**:
- **隐私优先**：使用WiFi信号进行姿态检测，无需摄像头。
- **实时处理**：延迟低于50毫秒，姿态估计达30 FPS。
- **多人追踪**：可同时追踪多达10人。
- **多场景应用**：针对医疗保健、健身、智能家居和安全等领域优化。
- **企业级API**：提供生产级API，包含身份验证、速率限制和监控。
- **硬件无关**：兼容标准WiFi路由器和接入点。
- **全面分析**：支持跌倒检测、活动识别和占用监控。
- **实时流传输**：通过WebSocket提供实时姿态数据流。

**技术亮点**:
- **高性能Rust实现**：提供Rust版本（v2），相比Python版本（v1）在关键处理环节（如CSI预处理、特征提取）有数百至数千倍的性能提升，内存占用更低（约100MB），并支持WASM。
- **灾难响应模块（WiFi-Mat）**：专为搜救行动设计，可检测生命体征（呼吸、心跳）并进行3D定位和伤员分类。
- **高测试覆盖率**：项目测试覆盖率达到100%，Rust版本包含107个测试。
- **现代化技术栈**：基于Python 3.8+和FastAPI构建，提供Docker支持，并通过PyPI分发。

---
## 2. [bytedance/deer-flow](https://github.com/bytedance/deer-flow)
- **语言**: TypeScript
- **Stars**: 21,894
- **简介**: An open-source SuperAgent harness that researches, codes, and creates. With the help of sandboxes, memories, tools, skills and subagents, it handles different levels of tasks that could take minutes to hours.

### AI 总结
**简介**: DeerFlow 是一个开源的超级智能体框架，通过编排子智能体、记忆和沙箱环境，结合可扩展的技能库，能够处理从几分钟到数小时不等的复杂任务。

**核心功能**:
- **子智能体编排**：协调多个子智能体分工合作。
- **沙箱与文件系统**：提供本地执行、Docker容器及Kubernetes Pod等多种安全隔离的执行环境。
- **技能与工具**：支持通过可扩展的技能和工具（包括MCP服务器）来增强智能体能力。
- **上下文工程与长期记忆**：具备高级的上下文管理能力和长期记忆机制，以支持复杂、持续的任务。

**技术亮点**: 基于TypeScript开发，采用LangChain，支持Docker容器化部署，提供多模式沙箱执行环境，架构上实现了从深度研究框架到通用超级智能体平台的全面重写（2.0版本）。

---
## 3. [moonshine-ai/moonshine](https://github.com/moonshine-ai/moonshine)
- **语言**: C
- **Stars**: 5,858
- **简介**: Fast and accurate automatic speech recognition (ASR) for edge devices

### AI 总结
**简介**: Moonshine Voice 是一个专为边缘设备设计的开源、实时、高精度自动语音识别（ASR）工具包。

**核心功能**:
- **全设备端运行**：无需网络、账户或API密钥，确保快速响应和隐私安全。
- **实时流式处理**：针对低延迟应用优化，可在用户说话时同步处理。
- **多任务高级API**：提供开箱即用的转录、说话人识别（声纹分离）和语义命令识别等完整解决方案。
- **多平台与多语言支持**：可在 Python、iOS、Android、macOS、Linux、Windows、树莓派及物联网设备上运行，支持英语、西班牙语、中文、日语、韩语、越南语、乌克兰语和阿拉伯语等多种语言。

**技术亮点**:
- **基于前沿研究**：模型从头训练，在高端模型上精度优于 Whisper Large V3，同时提供小至26MB的轻量模型。
- **统一的C/C++核心库**：确保跨平台的一致性和高性能。

---
## 4. [muratcankoylan/Agent-Skills-for-Context-Engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering)
- **语言**: Python
- **Stars**: 12,414
- **简介**: A comprehensive collection of Agent Skills for context engineering, multi-agent architectures, and production agent systems. Use when building, optimizing, or debugging agent systems that require effective context management.

### AI 总结
**简介**: 一个专注于上下文工程、多智能体架构和生产级智能体系统的综合性智能体技能集合。

**核心功能**:
- 提供从基础概念到高级架构的完整技能模块，涵盖上下文基础、多智能体模式、内存系统、工具设计等。
- 包含智能体系统的开发、评估与优化技能，如上下文优化、评估框架和高级评估技术。
- 引入新的认知架构技能，如基于BDI（信念-欲望-意图）模型的形式化推理。

**技术亮点**: 采用渐进式披露和平台无关的设计哲学，技能以Python伪代码示例实现，强调可转移的原理而非特定供应商实现。

---
## 5. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 64,800
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个基于可组合“技能”的智能体软件开发框架与方法论，旨在为编码智能体提供一套完整、自动化的开发工作流。

**核心功能**:
- **自动化工作流**: 从需求澄清、设计确认到实施计划，引导智能体按结构化流程开发。
- **子智能体驱动开发**: 将任务分解后，由独立的子智能体执行并经过两阶段代码审查，支持长时间自主运行。
- **强制最佳实践**: 内置技能强制实施测试驱动开发、YAGNI、DRY等工程原则，并自动触发代码审查。
- **多平台支持**: 提供Claude Code、Cursor、Codex和OpenCode等主流AI编码助手的安装与集成方案。

**技术亮点**: 基于Shell脚本构建的技能库，涵盖测试、调试、协作等多个领域，技能在任务前自动触发，将方法论转化为强制执行的智能体行为。

---
## 6. [ruvnet/ruflo](https://github.com/ruvnet/ruflo)
- **语言**: TypeScript
- **Stars**: 15,691
- **简介**: 🌊 The leading agent orchestration platform for Claude. Deploy intelligent multi-agent swarms, coordinate autonomous workflows, and build conversational AI systems. Features enterprise-grade architecture, distributed swarm intelligence, RAG integration, and native Claude Code / Codex Integration

### AI 总结
**简介**: Ruflo 是一个面向 Claude 的企业级 AI 智能体编排平台，用于部署和管理多智能体集群，以协调复杂的自主工作流和构建对话式 AI 系统。

**核心功能**:
- **多智能体集群编排**: 支持部署和协调 60 多个具备自学习能力的专业化智能体，支持多种集群拓扑结构（网状、分层、环形、星形）和共识机制。
- **企业级架构**: 提供分布式集群智能、RAG 集成、原生 Claude Code/Codex 集成，并具备容错和安全性。
- **智能路由与学习循环**: 包含 Q-Learning 路由器、专家混合模型以及一个完整的“检索-判断-提炼-巩固-路由”学习闭环，实现系统自我优化。

**技术亮点**:
- **底层架构**: 核心策略引擎、嵌入和证明系统由 Rust 编写的 WASM 内核驱动。
- **RuVector 智能层**: 集成了多项高性能 AI 技术，包括 SONA（自优化）、EWC++（防遗忘）、Flash Attention、HNSW（高速向量检索）、LoRA 微调、Int8 量化以及 9 种强化学习算法。
- **技术栈**: 基于 TypeScript 开发，提供 CLI/MCP 服务器作为入口。

---
## 7. [datawhalechina/hello-agents](https://github.com/datawhalechina/hello-agents)
- **语言**: Python
- **Stars**: 23,060
- **简介**: 📚 《从零开始构建智能体》——从零开始的智能体原理与实践教程

### AI 总结
**简介**: 这是一个名为《从零开始构建智能体》的系统性、实践导向的中文教程项目，旨在帮助开发者从零开始深入理解并亲手构建真正的 AI Native 智能体。

**核心功能**:
- **系统学习路径**: 提供从智能体基础理论、发展历史到大语言模型原理的完整知识体系。
- **动手实践指南**: 涵盖从使用低代码平台（如 Coze、Dify）到主流代码框架（如 AutoGen、LangGraph），再到从零自研智能体框架的全流程实践。
- **高级技能扩展**: 深入讲解记忆与检索（RAG）、上下文工程、智能体通信协议（MCP、A2A）、Agentic-RL 模型训练以及性能评估等高级主题。
- **综合项目实战**: 通过开发“智能旅行助手”、“赛博小镇”等综合案例，将所学知识融会贯通。

**技术亮点**: 教程内容覆盖了智能体构建的完整技术栈，强调 **AI 原生（AI Native）** 的构建理念，并引导学习者穿透框架表象，深入核心架构与经典范式（如 ReAct、Plan-and-Solve）。项目配套了自研的 **HelloAgents 框架** 作为实践示例。

---
## 8. [abhigyanpatwari/GitNexus](https://github.com/abhigyanpatwari/GitNexus)
- **语言**: TypeScript
- **Stars**: 6,242
- **简介**: GitNexus: The Zero-Server Code Intelligence Engine - GitNexus is a client-side knowledge graph creator that runs entirely in your browser. Drop in a GitHub repo or ZIP file, and get an interactive knowledge graph wit a built in Graph RAG Agent. Perfect for code exploration

### AI 总结
**简介**: GitNexus 是一个完全在浏览器中运行的客户端知识图谱创建工具，无需服务器，可将任何代码库（GitHub 仓库或 ZIP 文件）转换为交互式知识图谱，并内置 Graph RAG 智能体，用于代码探索和分析。

**核心功能**:
- **零服务器/浏览器端运行**: 整个处理过程在用户浏览器中完成，保障隐私，无需上传代码到远程服务器。
- **代码库智能索引**: 将代码库（包括依赖关系、调用链、代码簇和执行流）自动构建成知识图谱。
- **提供多种使用方式**: 支持 Web UI 进行快速可视化探索和对话，也提供 CLI 和 MCP 服务器模式，深度集成到 Claude Code、Cursor 等 AI 编码助手中，为其提供深度的代码架构上下文。
- **增强 AI 代理能力**: 通过 MCP 为 AI 编码助手提供知识图谱工具和技能，使其能理解代码关系，避免遗漏依赖和破坏调用链。

**技术亮点**:
- 采用 TypeScript 开发。
- 使用 Tree-sitter（支持原生绑定和 WASM 版本）进行代码解析。
- 使用 KuzuDB（支持原生版本和 WASM 版本）作为图数据库存储知识图谱。
- 支持 MCP 协议，与主流 AI 辅助编程工具实现深度集成。

---
## 9. [moeru-ai/airi](https://github.com/moeru-ai/airi)
- **语言**: TypeScript
- **Stars**: 18,363
- **简介**: 💖🧸 Self hosted, you-owned Grok Companion, a container of souls of waifu, cyber livings to bring them into our worlds, wishing to achieve Neuro-sama's altitude. Capable of realtime voice chat, Minecraft, Factorio playing. Web / macOS / Windows supported.

### AI 总结
**简介**: AIRI 是一个自托管、用户所有的 AI 伴侣/虚拟角色容器项目，旨在将赛博生命（如虚拟女友、数字宠物）带入现实世界，并期望达到 Neuro-sama 的水平。

**核心功能**:
- 支持实时语音聊天。
- 能够游玩 Minecraft、Factorio 等游戏。
- 支持 Web、macOS 和 Windows 平台。

**技术亮点**: 项目使用 TypeScript 开发，并集成了现代大型语言模型（如 ChatGPT、Claude）的能力，拥有专门的组织用于管理其衍生的子项目（如 RAG、记忆系统、嵌入式数据库等）。

---
## 10. [anthropics/claude-code](https://github.com/anthropics/claude-code)
- **语言**: Shell
- **Stars**: 71,191
- **简介**: Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands.

### AI 总结
**简介**: Claude Code 是一个基于终端的智能编码助手，能够理解代码库并通过自然语言命令帮助开发者执行任务、解释代码和处理 Git 工作流。

**核心功能**:
- 通过自然语言命令执行日常编码任务
- 解释复杂代码段
- 处理 Git 工作流（如提交、分支管理等）
- 支持在终端、IDE 或 GitHub 中通过 @claude 标记使用

**技术亮点**:
- 支持多平台安装（macOS/Linux 通过 curl 或 Homebrew，Windows 通过 PowerShell 或 WinGet）
- 提供插件系统扩展功能
- 集成反馈机制（支持 /bug 命令直接报告问题）

---
