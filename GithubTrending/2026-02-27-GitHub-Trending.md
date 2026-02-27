---
tags:
  - github-trending
  - daily
date: 2026-02-27
created: 2026-02-27T01:55:46.947Z
---

# 2026-02-27 GitHub Trending Top 10

## 1. [clockworklabs/SpacetimeDB](https://github.com/clockworklabs/SpacetimeDB)
- **语言**: Rust
- **Stars**: 20,896
- **简介**: Development at the speed of light

### AI 总结
**简介**: SpacetimeDB 是一个将数据库与服务器功能合二为一的关系型数据库系统，旨在实现“光速开发”。

**核心功能**:
- **数据库与服务器一体化**：客户端可直接连接到数据库，无需部署独立的中间层服务器。
- **模块化应用逻辑**：允许开发者将应用逻辑（称为“模块”）作为高级存储过程直接上传到数据库中运行。
- **简化部署**：整个应用可以用 Rust 语言编写，并作为单个二进制文件部署，无需管理微服务、容器、Kubernetes 等复杂基础设施。

**技术亮点**:
- 使用 **Rust** 语言构建。
- 采用 **BSL 1.1** 许可证。
- 架构上实现了客户端与数据库的直接交互，将权限和授权逻辑内置于数据库模块中。

---
## 2. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 63,420
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个基于可组合“技能”的智能体软件开发框架与工作流，旨在引导编码智能体（如 Claude、Cursor 等）进行系统化、高质量的软件开发。

**核心功能**:
- **自动化工作流**：从需求澄清、设计评审到实现计划，提供完整的开发流程，智能体会在任务前自动触发相关技能。
- **子智能体驱动开发**：通过将任务分解为小块，派遣独立的子智能体执行，并进行两阶段代码审查，支持长时间自主工作。
- **强制最佳实践**：内置测试驱动开发（TDD）、YAGNI、DRY 等原则，确保代码质量，例如强制先写失败测试再编码。

**技术亮点**: 采用模块化技能库设计，技能（如系统化调试、Git 工作树管理、代码审查）可组合并自动触发，无缝集成到 Claude Code、Cursor、Codex 和 OpenCode 等主流智能体编码平台中。

---
## 3. [muratcankoylan/Agent-Skills-for-Context-Engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering)
- **语言**: Python
- **Stars**: 11,757
- **简介**: A comprehensive collection of Agent Skills for context engineering, multi-agent architectures, and production agent systems. Use when building, optimizing, or debugging agent systems that require effective context management.

### AI 总结
**简介**: 一个专注于上下文工程、多智能体架构和生产级智能体系统的综合性智能体技能集合。

**核心功能**:
- 提供从基础概念到高级架构的完整技能体系，涵盖上下文基础、压缩、优化及多智能体模式等。
- 包含实用的开发方法论和认知架构技能，如项目开发流程和基于BDI（信念-期望-意图）模型的理性智能体构建。
- 设计了渐进式披露和平台无关的架构，确保技能能高效加载并适用于多种智能体平台。

**技术亮点**: 采用平台无关的设计哲学，技能以Python伪代码示例呈现，强调可迁移的工程原则而非具体实现。其技能架构被学术研究引用为静态技能架构的基础工作。

---
## 4. [bytedance/deer-flow](https://github.com/bytedance/deer-flow)
- **语言**: TypeScript
- **Stars**: 21,144
- **简介**: An open-source SuperAgent harness that researches, codes, and creates. With the help of sandboxes, memories, tools, skills and subagents, it handles different levels of tasks that could take minutes to hours.

### AI 总结
**简介**: DeerFlow 是一个开源的超级智能体框架，通过编排子智能体、记忆和沙箱环境，并借助可扩展的技能，来处理从几分钟到数小时不等的复杂任务。

**核心功能**:
- **技能与工具**: 提供可扩展的技能和工具集，以增强智能体的能力。
- **子智能体**: 支持编排多个子智能体协同工作。
- **沙箱与文件系统**: 提供安全的代码执行环境，支持本地、Docker及Kubernetes等多种运行模式。
- **上下文工程**: 优化和管理智能体的上下文信息。
- **长期记忆**: 为智能体提供持久化记忆能力。

**技术亮点**: 基于 TypeScript 开发，采用 LangChain 集成主流大模型（如 GPT-4），支持通过 MCP 服务器扩展功能，并提供 Docker 一键部署。

---
## 5. [huggingface/skills](https://github.com/huggingface/skills)
- **语言**: Python
- **Stars**: 6,990
- **简介**: 

### AI 总结
**简介**: Hugging Face Skills 是一个遵循 Agent Skills 标准格式的仓库，为 AI 代理（如 Claude Code、Codex、Gemini CLI、Cursor）提供了一系列可复用的技能定义，用于执行 Hugging Face 生态相关的 AI/ML 任务。

**核心功能**:
- 提供多种预定义技能，涵盖 Gradio 应用构建、Hugging Face Hub 的 CLI 操作、数据集管理、模型评估和训练任务提交等。
- 兼容主流 AI 编程代理工具（Claude Code、OpenAI Codex、Google Gemini CLI、Cursor），通过统一的 `SKILL.md` 文件格式提供指导。
- 支持多种安装和集成方式，用户可根据自己使用的代理工具，通过命令行、插件市场或文件链接等方式快速安装技能。

**技术亮点**: 遵循开放的 [Agent Skills](https://agentskills.io/specification) 标准，通过 `SKILL.md` 文件（含 YAML 前言）封装指令和资源，实现了技能在不同 AI 代理工具间的互操作性。

---
## 6. [farion1231/cc-switch](https://github.com/farion1231/cc-switch)
- **语言**: Rust
- **Stars**: 20,704
- **简介**: A cross-platform desktop All-in-One assistant tool for Claude Code, Codex, OpenCode & Gemini CLI.

### AI 总结
**简介**: 一个基于 Tauri 构建的跨平台桌面应用，集成了 Claude Code、Codex、OpenCode 和 Gemini CLI 等多种 AI 编程助手。

**核心功能**:
- 提供对 Claude Code、Codex、OpenCode 和 Gemini CLI 等 AI 编程工具的统一桌面界面。
- 支持 Windows、macOS 和 Linux 三大主流操作系统。

**技术亮点**: 使用 Rust 语言开发，并基于 Tauri 2 框架构建，确保了应用的性能和跨平台能力。

---
## 7. [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling)
- **语言**: Python
- **Stars**: 16,884
- **简介**: 🕷️ An adaptive Web Scraping framework that handles everything from a single request to a full-scale crawl!

### AI 总结
**简介**: Scrapling 是一个自适应的 Python Web 爬虫框架，能够处理从单次请求到大规模并发爬取的所有任务。

**核心功能**:
- **自适应解析器**：能够学习网站的变化，在页面更新时自动重新定位目标元素。
- **智能请求器**：内置绕过 Cloudflare Turnstile 等反机器人系统的能力。
- **可扩展的爬虫框架**：支持并发、多会话爬取，具备暂停/恢复和自动代理轮换功能。
- **命令行工具**：提供便捷的 CLI 操作界面。
- **模型上下文协议**：支持 MCP 服务器，便于与 AI 工具集成。

**技术亮点**: 框架采用模块化设计，提供同步/异步、隐身、动态渲染等多种请求器；支持实时统计和流式处理，性能出色；其解析器具备“自适应”模式，能应对网站结构变更，提升爬虫的健壮性。

---
## 8. [ruvnet/claude-flow](https://github.com/ruvnet/claude-flow)
- **语言**: TypeScript
- **Stars**: 14,986
- **简介**: 🌊 The leading agent orchestration platform for Claude. Deploy intelligent multi-agent swarms, coordinate autonomous workflows, and build conversational AI systems. Features enterprise-grade architecture, distributed swarm intelligence, RAG integration, and native Claude Code / Codex Integration

### AI 总结
**简介**: Ruflo (Claude-Flow) 是一个基于 TypeScript 开发的企业级 AI 智能体编排平台，旨在将 Claude Code 转化为一个强大的多智能体开发平台，用于协调和部署复杂的软件工程任务。

**核心功能**:
- **多智能体集群协调**: 支持部署和协调超过 60 个专业化智能体，形成具备自学习能力的集群，支持多种网络拓扑结构。
- **企业级架构与安全**: 提供生产就绪的编排框架，包含分布式集群智能、RAG 集成、原生 Claude Code 集成以及企业级安全特性。
- **自我学习与优化**: 内置自我学习循环，智能体能够通过检索、判断、提炼、巩固和路由等步骤持续优化任务执行。

**技术亮点**:
- **RuVector 智能层**: 集成了 SONA（自优化）、EWC++（防遗忘）、Flash Attention、HNSW（高速向量检索）、LoRA 微调、Int8 量化等多种先进算法，显著提升性能和效率。
- **灵活的编排与路由**: 采用 Q-Learning 路由器、混合专家模型以及丰富的技能与钩子，实现智能的任务分配和流程控制。
- **分布式共识与内存**: 支持 Raft、BFT 等共识机制，并配备 AgentDB 内存系统，确保系统的可靠性与状态持久化。

---
## 9. [ruvnet/ruvector](https://github.com/ruvnet/ruvector)
- **语言**: Rust
- **Stars**: 1,606
- **简介**: RuVector is a High Performance, Real-Time, Self-Learning, Vector Graph Neural Network, and Database built in Rust.

### AI 总结
**简介**: RuVector 是一个用 Rust 构建的高性能、实时、自学习的向量图神经网络和数据库。

**核心功能**:
- **智能向量搜索与图查询**: 支持向量存储与搜索，并能通过 Cypher 语言进行图关系查询，搜索结果会随着使用而自我优化。
- **本地 AI 与机器学习**: 内置功能可在本地运行 LLM 模型，并集成了多种注意力机制、图神经网络和自优化神经架构。
- **一体化部署与扩展**: 支持以单个文件（认知容器）形式快速启动为微服务，具备水平扩展、自动分片和多主复制等分布式系统能力。

**技术亮点**: 采用 Rust 开发，核心特性包括自学习 GNN 索引、证明门控图变换器、超球面 HNSW 索引、eBPF 技术、Raft 共识算法，并支持 WASM。

---
## 10. [moonshine-ai/moonshine](https://github.com/moonshine-ai/moonshine)
- **语言**: C
- **Stars**: 5,293
- **简介**: Fast and accurate automatic speech recognition (ASR) for edge devices

### AI 总结
**简介**: Moonshine Voice 是一个专为边缘设备设计的开源、实时、高精度自动语音识别（ASR）工具包。

**核心功能**:
- **全设备端运行**：无需网络、账户、API密钥或信用卡，确保快速响应和隐私安全。
- **实时流式处理**：针对实时语音应用优化，在用户说话时即开始处理，实现低延迟。
- **开箱即用的高级API**：提供转录、说话人识别（声纹分离）和命令识别（支持语义匹配）等完整解决方案，降低开发门槛。
- **多平台与多语言支持**：可在 Python、iOS、Android、macOS、Linux、Windows、Raspberry Pi 及 IoT 设备上运行，支持英语、西班牙语、中文、日语、韩语、越南语、乌克兰语和阿拉伯语。

**技术亮点**:
- **基于前沿研究**：模型完全从头训练，在高端模型上精度超越 Whisper Large V3，同时提供小至 26MB 的轻量模型。
- **统一的跨平台库**：使用 C 语言核心，确保在不同硬件和操作系统上的一致性和高性能。

---
