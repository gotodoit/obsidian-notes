---
tags:
  - github-trending
  - daily
date: 2026-03-03
created: 2026-03-03T01:55:51.024Z
---

# 2026-03-03 GitHub Trending Top 9

## 1. [ruvnet/wifi-densepose](https://github.com/ruvnet/wifi-densepose)
- **语言**: Rust
- **Stars**: 22,163
- **简介**: WiFi DensePose turns commodity WiFi signals into real-time human pose estimation, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: 一个利用普通WiFi信号实现无摄像头、无穿戴设备的实时人体姿态估计、生命体征监测和存在检测的Rust项目。

**核心功能**:
- **实时人体姿态估计**: 通过分析WiFi信道状态信息（CSI）的扰动，重建人体姿态。
- **生命体征监测**: 检测呼吸频率（6-30次/分钟）和心率（40-120次/分钟）。
- **存在与运动感知**: 实现低延迟（<1ms）的人员存在检测。
- **穿墙感知**: 利用菲涅尔区几何和多径建模，实现穿墙人体感知（最深可达5米）。
- **灾难响应**: 支持通过废墟检测被困人员并进行伤情严重程度分类（START检伤分类）。

**技术亮点**:
- **技术栈**: 使用Rust语言实现，性能优异（姿态估计可达54K fps），提供Docker镜像（132 MB）便于部署。
- **信号处理**: 基于物理的CSI信号处理与机器学习相结合。
- **硬件支持**: 支持ESP32-S3等多节点网状网络进行CSI流式传输，实现多静态感知和360度覆盖。
- **隐私优先**: 仅使用WiFi无线电波，不存储任何图像或视频，保护用户隐私。

---
## 2. [moeru-ai/airi](https://github.com/moeru-ai/airi)
- **语言**: TypeScript
- **Stars**: 21,448
- **简介**: 💖🧸 Self hosted, you-owned Grok Companion, a container of souls of waifu, cyber livings to bring them into our worlds, wishing to achieve Neuro-sama's altitude. Capable of realtime voice chat, Minecraft, Factorio playing. Web / macOS / Windows supported.

### AI 总结
**简介**: AIRI 是一个自托管、用户拥有的 AI 伴侣/虚拟角色容器项目，旨在将赛博生命（如虚拟女友、数字宠物）带入现实世界，其灵感来源于 Neuro-sama。

**核心功能**:
- 支持实时语音聊天。
- 能够与用户互动并游玩《我的世界》、《异星工厂》等游戏。
- 提供 Web、macOS 和 Windows 客户端。

**技术亮点**: 项目基于 TypeScript 开发，并利用现代大语言模型（如 ChatGPT、Claude）驱动角色扮演与对话，拥有独立的子项目组织用于管理 RAG、记忆系统、嵌入式数据库等组件。

---
## 3. [anthropics/prompt-eng-interactive-tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial)
- **语言**: Jupyter Notebook
- **Stars**: 31,632
- **简介**: Anthropic's Interactive Prompt Engineering Tutorial

### AI 总结
**简介**: Anthropic 推出的交互式提示工程教程，旨在通过实践练习帮助用户掌握在 Claude 模型上构建高效提示词的技能。

**核心功能**:
- 提供从基础到高级的9个章节教程，涵盖提示词结构、清晰指令、角色分配、输出格式化、思维链等核心概念。
- 每个章节均包含“示例练习场”和配套练习题，支持用户即时修改提示并观察 Claude 的响应变化。
- 包含行业用例实战（如法律、金融、编程）和高级方法附录（如提示链、工具使用），以构建复杂提示。

**技术亮点**: 教程基于 Jupyter Notebook 实现交互式学习，主要使用 Claude 3 Haiku 模型进行演示，并提供了 Google Sheets 版本以提升用户体验。

---
## 4. [ruvnet/ruflo](https://github.com/ruvnet/ruflo)
- **语言**: TypeScript
- **Stars**: 18,085
- **简介**: 🌊 The leading agent orchestration platform for Claude. Deploy intelligent multi-agent swarms, coordinate autonomous workflows, and build conversational AI systems. Features enterprise-grade architecture, distributed swarm intelligence, RAG integration, and native Claude Code / Codex Integration

### AI 总结
**简介**: Ruflo 是一个基于 TypeScript 开发的企业级 AI 智能体编排平台，专为 Claude 设计，用于部署和管理协调工作的多智能体集群。

**核心功能**:
- **多智能体集群编排**: 支持部署和协调 60 多个具备自学习能力的专业智能体，共同处理复杂的软件工程任务。
- **企业级架构**: 提供分布式集群智能、RAG 集成、原生 Claude Code/Codex 集成以及企业级安全性。
- **智能路由与学习循环**: 包含 Q-Learning 路由器、专家混合模型以及一个完整的“检索-判断-提炼-巩固-路由”学习闭环，实现系统自我优化。

**技术亮点**:
- **底层性能**: 使用 Rust 编写的 WASM 内核来驱动策略引擎、嵌入和证明系统。
- **RuVector 智能层**: 集成了 SONA（自优化）、EWC++（防遗忘）、Flash Attention、HNSW（高速近邻搜索）、LoRA 微调、Int8 量化等多种先进算法以提升性能和效率。
- **灵活的集群拓扑与共识机制**: 支持网状、分层、环形、星形等多种拓扑结构，并可选用 Raft、BFT、Gossip、CRDT 等共识协议。

---
## 5. [alibaba/OpenSandbox](https://github.com/alibaba/OpenSandbox)
- **语言**: Python
- **Stars**: 4,374
- **简介**: OpenSandbox is a general-purpose sandbox platform for AI applications, offering multi-language SDKs, unified sandbox APIs, and Docker/Kubernetes runtimes for scenarios like Coding Agents, GUI Agents, Agent Evaluation, AI Code Execution, and RL Training.

### AI 总结
**简介**: OpenSandbox 是阿里巴巴开源的一个通用 AI 应用沙箱平台，为多种 AI 应用场景提供安全、隔离的执行环境。

**核心功能**:
- **多语言 SDK**: 提供 Python、Java/Kotlin、JavaScript/TypeScript、C#/.NET 等多种语言的沙箱 SDK。
- **统一沙箱协议与 API**: 定义了沙箱生命周期管理和执行的标准 API，支持扩展自定义沙箱运行时。
- **灵活的运行时支持**: 内置支持 Docker 和高性能 Kubernetes 运行时，既支持本地运行，也支持大规模分布式调度。
- **丰富的沙箱环境**: 内置命令行、文件系统和代码解释器环境，并提供浏览器自动化（Chrome, Playwright）、桌面环境（VNC, VS Code）等示例。
- **网络策略管理**: 提供统一的入口网关（Ingress Gateway）和针对每个沙箱的出口流量控制（Egress Controls）。

**技术亮点**: 采用容器化技术（Docker/Kubernetes）作为底层隔离与运行基础，通过定义标准化的沙箱协议，实现了运行时的可扩展性，并针对 AI Agent、代码执行、强化学习训练等场景提供了开箱即用的环境支持。

---
## 6. [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **语言**: Python
- **Stars**: 89,643
- **简介**: Python tool for converting files and office documents to Markdown.

### AI 总结
**简介**: 一个由微软开发的轻量级 Python 工具，专注于将多种文件和办公文档（如 PDF、Word、Excel、PPT 等）转换为结构化的 Markdown 格式，以便于大语言模型（LLM）和文本分析管道使用。

**核心功能**:
- 支持广泛的文件格式转换，包括 PDF、Office 文档、图像、音频、HTML、压缩包、YouTube 视频链接等。
- 提供命令行界面（CLI）和 Python API 两种使用方式，支持文件路径输入和管道操作。
- 通过可选的依赖项分组（如 `[pdf]`, `[docx]`）实现按需安装，保持工具轻量化。
- 集成了 MCP（模型上下文协议）服务器，便于与 Claude Desktop 等 LLM 应用程序集成。

**技术亮点**:
- 设计目标明确，旨在为 LLM 处理保留文档的核心结构（标题、列表、表格、链接等），而非追求高保真的人类可读渲染。
- 采用流式处理接口，无需创建临时文件，提升了处理效率和资源利用率。
- 基于 Python 3.10+，依赖管理清晰，支持通过 `pip install 'markitdown[all]'` 一键安装全部功能。

---
## 7. [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills)
- **语言**: Python
- **Stars**: 11,111
- **简介**: A set of ready to use Agent Skills for research, science, engineering, analysis, finance and writing.

### AI 总结
**简介**: 一个包含148+个即用型科学、研究、工程、分析和金融技能的集合，遵循开放的Agent Skills标准，可将AI助手转变为强大的跨学科研究助理。

**核心功能**:
- 提供涵盖生物信息学、化学信息学、临床研究、医学影像、机器学习、材料科学、物理学、工程学等十多个科学领域的148个预定义技能。
- 集成了对250多个科学和金融数据库（如PubMed、ChEMBL、SEC EDGAR、Alpha Vantage等）的访问能力。
- 支持复杂、多步骤的科学工作流自动化，从数据分析、可视化到实验室协议和科学写作。

**技术亮点**: 基于Python，遵循开放的Agent Skills标准，可与支持该标准的AI代理（如Cursor、Claude Code、Codex）无缝协作，通过封装专业科学库和API提供可靠、文档化的技能调用。

---
## 8. [superset-sh/superset](https://github.com/superset-sh/superset)
- **语言**: TypeScript
- **Stars**: 3,538
- **简介**: IDE for the AI Agents Era - Run an army of Claude Code, Codex, etc. on your machine

### AI 总结
**简介**: Superset 是一个专为 AI 智能体时代设计的集成开发环境，允许开发者在本地机器上并行运行和管理多个 CLI 编码智能体。

**核心功能**:
- **并行执行**：可同时运行 10 个以上的编码智能体。
- **工作区隔离**：每个任务都在独立的 Git 工作树中运行，避免相互干扰。
- **集中监控**：在一个界面中监控所有智能体状态，并在需要关注时获得通知。
- **内置工具**：提供内置的差异查看器和编辑器，方便快速审查和编辑代码变更。
- **通用兼容**：支持任何可在终端运行的 CLI 智能体，如 Claude Code、Cursor Agent、GitHub Copilot 等。

**技术亮点**: 基于 TypeScript 和 Bun 运行时构建，采用 Git 工作树实现任务隔离，并集成了 Caddy 反向代理以支持 Electric SQL 流。

---
## 9. [servo/servo](https://github.com/servo/servo)
- **语言**: Rust
- **Stars**: 35,766
- **简介**: Servo aims to empower developers with a lightweight, high-performance alternative for embedding web technologies in applications.

### AI 总结
**简介**: Servo 是一个用 Rust 语言编写的、旨在为开发者提供轻量级、高性能的嵌入式 Web 技术替代方案的原型浏览器引擎。

**核心功能**:
- 提供高性能的 Web 渲染引擎，支持在应用程序中嵌入 Web 技术。
- 支持在多种主流操作系统和平台上进行开发和构建，包括 64 位 macOS、Linux、Windows、OpenHarmony 和 Android。

**技术亮点**: 项目完全采用 Rust 语言开发，充分利用其内存安全和并发特性，旨在构建一个并行化的现代浏览器引擎。

---
