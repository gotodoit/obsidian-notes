---
tags:
  - github-trending
  - daily
date: 2026-02-25
created: 2026-02-25T01:55:48.237Z
---

# 2026-02-25 GitHub Trending Top 10

## 1. [huggingface/skills](https://github.com/huggingface/skills)
- **语言**: Python
- **Stars**: 5,388
- **简介**: 

### AI 总结
**简介**: Hugging Face Skills 是一个为 AI/ML 任务（如数据集创建、模型训练和评估）提供标准化技能定义的项目，可与主流 AI 编程助手工具（如 Claude Code、OpenAI Codex、Gemini CLI 和 Cursor）互操作。

**核心功能**:
- 提供一系列预定义的技能，涵盖 Hugging Face Hub 的 CLI 操作、数据集管理、模型训练、评估、论文发布等 AI/ML 工作流。
- 技能以独立文件夹形式打包，包含指导 AI 代理的指令、脚本和资源，遵循标准化的 Agent Skill 格式。
- 兼容多种 AI 编程助手，通过不同的配置文件（如 `AGENTS.md`、`gemini-extension.json`）或插件市场机制进行安装和集成。

**技术亮点**: 采用标准化的 [Agent Skill](https://agentskills.io/home) 格式，确保技能在不同 AI 代理工具间的可移植性和互操作性。

---
## 2. [muratcankoylan/Agent-Skills-for-Context-Engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering)
- **语言**: Python
- **Stars**: 9,945
- **简介**: A comprehensive collection of Agent Skills for context engineering, multi-agent architectures, and production agent systems. Use when building, optimizing, or debugging agent systems that require effective context management.

### AI 总结
**简介**: 一个专注于上下文工程、多智能体架构和生产级智能体系统的综合性智能体技能集合。

**核心功能**:
- 提供从基础概念到高级架构的系列技能，涵盖上下文基础、压缩、优化、评估及多智能体模式等。
- 包含开发方法论与认知架构技能，如基于BDI（信念-期望-意图）模型的理性智能体构建。
- 设计了渐进式披露的加载机制，确保智能体仅在需要时加载完整技能内容，以优化上下文使用。

**技术亮点**: 采用平台无关的设计理念，技能原理可迁移至Claude Code、Cursor等任何支持自定义指令的智能体平台；技能示例使用无需特定依赖的Python伪代码，注重概念与实践结合。

---
## 3. [OpenBB-finance/OpenBB](https://github.com/OpenBB-finance/OpenBB)
- **语言**: Python
- **Stars**: 61,903
- **简介**: Financial data platform for analysts, quants and AI agents.

### AI 总结
**简介**: OpenBB 是一个面向分析师、量化交易员和 AI 代理的开源金融数据平台，旨在整合多种数据源并提供统一的数据访问层。

**核心功能**:
- 作为“一次连接，随处消费”的基础设施层，整合专有、授权和公共数据源。
- 通过 Python 包、REST API、OpenBB Workspace（企业级 UI）、Excel 插件和 MCP 服务器等多种方式暴露数据。
- 提供企业级可视化界面 OpenBB Workspace，支持数据集可视化和集成 AI 代理。

**技术亮点**:
- 基于 Python 构建，可通过 `pip install openbb` 快速安装。
- 采用 FastAPI 构建本地 API 服务器，便于后端集成。
- 支持在 VS Code Dev Containers、GitHub Codespaces 和 Google Colab 等多种开发环境中快速启动。

---
## 4. [LadybirdBrowser/ladybird](https://github.com/LadybirdBrowser/ladybird)
- **语言**: C++
- **Stars**: 59,114
- **简介**: Truly independent web browser

### AI 总结
**简介**: Ladybird 是一款基于 Web 标准、采用全新引擎构建的独立网络浏览器。

**核心功能**:
- 采用多进程架构，包含主UI进程、多个WebContent渲染进程、ImageDecoder进程和RequestServer进程，以提升安全性和稳定性。
- 图像解码和网络连接在进程外进行，增强了对恶意内容的防护能力。
- 每个标签页拥有独立的、沙盒化的渲染器进程。

**技术亮点**:
- 浏览器核心库继承自 SerenityOS，包括 LibWeb（网页渲染引擎）、LibJS（JavaScript引擎）、LibWasm（WebAssembly实现）、LibCrypto/LibTLS（加密与TLS）、LibHTTP（HTTP客户端）、LibGfx（2D图形与图像处理）、LibUnicode（Unicode支持）、LibMedia（音视频播放）、LibCore（事件循环与OS抽象层）和 LibIPC（进程间通信）。
- 目前处于预发布阶段，主要面向开发者。支持 Linux、macOS、Windows（通过WSL2）等多种平台。

---
## 5. [x1xhlol/system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools)
- **语言**: Unknown
- **Stars**: 123,114
- **简介**: FULL Augment Code, Claude Code, Cluely, CodeBuddy, Comet, Cursor, Devin AI, Junie, Kiro, Leap.new, Lovable, Manus, NotionAI, Orchids.app, Perplexity, Poke, Qoder, Replit, Same.dev, Trae, Traycer AI, VSCode Agent, Warp.dev, Windsurf, Xcode, Z.ai Code, Dia & v0. (And other Open Sourced) System Prompts, Internal Tools & AI Models

### AI 总结
**简介**: 这是一个收集了众多主流AI编程助手和工具（如Cursor、Devin AI、Replit等）的系统提示词、内部工具和AI模型的仓库，旨在提供对其内部结构和功能的深入洞察。

**核心功能**:
- 汇集了超过30,000行代码，揭示了多种AI开发工具（如Claude Code、Cursor、VSCode Agent等）的系统提示词和内部配置。
- 作为一个信息聚合与分享平台，为开发者和研究者提供参考，以了解不同AI工具的内部工作机制。

**技术亮点**: 仓库本身不涉及具体的技术栈，但其内容涉及对多种闭源和开源AI工具内部机制的反向工程与汇总，具有很高的研究和参考价值。

---
## 6. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 60,504
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为 AI 编程代理设计的、基于可组合“技能”的软件开发框架与工作流。

**核心功能**:
- **智能工作流触发**：代理在编码前自动启动“头脑风暴”等技能，通过提问澄清需求，并分块呈现设计以供确认。
- **子代理驱动开发**：在计划获批后，启动子代理并行处理分解后的工程任务，并进行两阶段审查（规范符合性与代码质量）。
- **强制最佳实践**：强制执行真正的红绿测试驱动开发、YAGNI 和 DRY 原则，并内置代码审查、系统化调试等协作与质量保障技能。

**技术亮点**: 框架设计为与 Claude Code、Cursor、Codex 和 OpenCode 等主流 AI 编程平台/代理集成，通过插件市场或指令即可安装，技能在相关任务前自动触发，形成强制性工作流。

---
## 7. [ruvnet/ruvector](https://github.com/ruvnet/ruvector)
- **语言**: Rust
- **Stars**: 745
- **简介**: RuVector is a high performance vector and graph database built in Rust for AI, agentic systems, and real time analytics. It combines HNSW search, dynamic minimum cut coherence, graph intelligence, and self learning memory into one unified engine for scalable, low latency reasoning and structured retrieval.

### AI 总结
**简介**: RuVector 是一个用 Rust 编写的高性能向量和图数据库，专为 AI、智能体系统和实时分析设计，集成了自学习、图智能和统一引擎，旨在提供可扩展、低延迟的推理和结构化检索。

**核心功能**:
- **智能向量搜索与图查询**: 结合 HNSW 搜索、动态最小割一致性（Dynamic Minimum Cut Coherence）和图智能，支持 Cypher 语言进行关系查询。
- **自学习与持续优化**: 系统通过 GNN 层从每次查询中学习，使搜索结果随时间不断改进，并具备自我优化的神经架构（SONA）。
- **一体化 AI 引擎**: 内置本地 LLM 运行能力（支持 GGUF 格式）、46 种注意力机制、子线性求解器（如 PageRank）以及拓扑数据分析。
- **轻量级部署与扩展**: 支持单文件部署为自启动微服务（RVF 认知容器），可在 125 毫秒内启动；具备水平扩展、自动分片和多主复制能力。

**技术亮点**:
- **语言与架构**: 基于 Rust 开发，强调高性能与安全性。
- **存储与计算**: 支持自适应分层压缩（2-32 倍内存减少）、超平面 HNSW 索引、实时图更新（无需重建）。
- **分布式与协同**: 集成 Raft 共识、向量时钟冲突解决、突发流量扩展（10-50 倍容量）和类 Git 的分支数据管理。
- **跨平台与生态**: 提供 npm 包、WASM 支持，可运行于浏览器、移动设备、IoT 及裸机环境；采用 MIT 开源协议，完全免费。

---
## 8. [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling)
- **语言**: Python
- **Stars**: 12,673
- **简介**: 🕷️ An adaptive Web Scraping framework that handles everything from a single request to a full-scale crawl!

### AI 总结
**简介**: Scrapling 是一个自适应的 Python Web 爬虫框架，能够处理从单个请求到大规模并发抓取的各种场景。

**核心功能**:
- **自适应解析器**：能够学习网站的变化，当页面更新时自动重新定位目标元素。
- **智能请求器**：内置绕过 Cloudflare Turnstile 等反机器人系统的能力。
- **可扩展的爬虫框架**：支持并发、多会话抓取，具备暂停/恢复和自动代理轮换功能。
- **命令行工具**：提供便捷的 CLI 操作界面。
- **模型上下文协议支持**：集成了 MCP 服务器功能。

**技术亮点**: 框架采用模块化设计，支持同步/异步请求、无头浏览器渲染、实时统计与数据流式处理，旨在为开发者和普通用户提供高效、易用且功能全面的网页抓取解决方案。

---
## 9. [GVCLab/PersonaLive](https://github.com/GVCLab/PersonaLive)
- **语言**: Python
- **Stars**: 2,006
- **简介**: [CVPR 2026] PersonaLive! : Expressive Portrait Image Animation for Live Streaming

### AI 总结
**简介**: PersonaLive 是一个面向直播场景、能够生成无限长度、富有表现力的实时人像动画的扩散模型框架。

**核心功能**:
- **实时人像动画**: 根据输入的参考图像和驱动信号（如姿态），生成生动、连贯的人像动画。
- **流式生成**: 支持流式策略，可在有限的显存（如12GB VRAM）下生成长视频。
- **多平台部署**: 提供推理代码、预训练权重，并支持 WebUI 和 ComfyUI 插件。

**技术亮点**: 基于扩散模型，采用实时且可流式处理的架构，能够实现无限长度的动画生成，并已集成到主流AI工作流平台中。

---
## 10. [HunxByts/GhostTrack](https://github.com/HunxByts/GhostTrack)
- **语言**: Python
- **Stars**: 7,476
- **简介**: Useful tool to track location or mobile number

### AI 总结
**简介**: GhostTrack 是一个用于追踪地理位置、手机号码和社交媒体用户信息的开源情报（OSINT）工具。

**核心功能**:
- **IP 地址追踪**: 可追踪 IP 地址的地理位置等信息，并能与 Seeker 工具配合使用。
- **手机号码追踪**: 可根据手机号码搜索目标相关信息。
- **用户名追踪**: 可在社交媒体上根据用户名搜索目标信息。

**技术亮点**: 基于 Python 开发，提供命令行界面，支持在 Linux（deb）和 Termux 上安装运行。

---
