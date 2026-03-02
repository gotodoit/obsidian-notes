---
tags:
  - github-trending
  - daily
date: 2026-03-02
created: 2026-03-02T01:55:50.498Z
---

# 2026-03-02 GitHub Trending Top 10

## 1. [moeru-ai/airi](https://github.com/moeru-ai/airi)
- **语言**: TypeScript
- **Stars**: 20,318
- **简介**: 💖🧸 Self hosted, you-owned Grok Companion, a container of souls of waifu, cyber livings to bring them into our worlds, wishing to achieve Neuro-sama's altitude. Capable of realtime voice chat, Minecraft, Factorio playing. Web / macOS / Windows supported.

### AI 总结
**简介**: AIRI 是一个自托管、用户拥有的虚拟伴侣（AI 老婆/数字生命）容器项目，旨在复现 Neuro-sama 的体验，将虚拟角色带入现实世界。

**核心功能**:
- 支持实时语音聊天。
- 能够游玩 Minecraft、Factorio 等游戏。
- 提供 Web、macOS 和 Windows 客户端。

**技术亮点**: 项目基于 TypeScript 开发，利用现代大语言模型（如 ChatGPT、Claude）驱动，并拥有专注于 RAG、记忆系统、嵌入式数据库等功能的子项目生态。

---
## 2. [ruvnet/wifi-densepose](https://github.com/ruvnet/wifi-densepose)
- **语言**: Rust
- **Stars**: 17,748
- **简介**: WiFi DensePose turns commodity WiFi signals into real-time human pose estimation, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: WiFi DensePose 是一个利用普通WiFi信号实现实时人体姿态估计、生命体征监测和存在检测的开源项目，无需任何摄像头或可穿戴设备。

**核心功能**:
- **人体姿态估计**: 通过分析信道状态信息（CSI）扰动，实时重建人体姿态。
- **生命体征监测**: 检测呼吸频率（6-30次/分钟）和心率（40-120次/分钟）。
- **存在与运动检测**: 基于信号强度变化，实现低延迟的存在感知。
- **穿墙感知**: 利用WiFi信号的穿透性，可在墙壁、家具等障碍物后工作。
- **灾难响应**: 支持通过废墟检测被困人员并进行伤情分类（START检伤分类）。

**技术亮点**: 项目使用Rust语言编写，核心是基于物理的信号处理和机器学习（如注意力网络、图算法）。它依赖于能提供CSI数据的硬件（如ESP32-S3或研究网卡），并采用自学习架构，无需标注数据即可从原始WiFi信号中学习。

---
## 3. [ruvnet/ruflo](https://github.com/ruvnet/ruflo)
- **语言**: TypeScript
- **Stars**: 17,339
- **简介**: 🌊 The leading agent orchestration platform for Claude. Deploy intelligent multi-agent swarms, coordinate autonomous workflows, and build conversational AI systems. Features enterprise-grade architecture, distributed swarm intelligence, RAG integration, and native Claude Code / Codex Integration

### AI 总结
**简介**: Ruflo 是一个基于 Claude Code 的企业级 AI 智能体编排平台，用于部署和协调多智能体集群，以完成复杂的软件工程任务。

**核心功能**:
- **多智能体集群编排**: 支持部署和协调 60 多个具备自学习能力的专业化智能体。
- **企业级架构**: 提供分布式集群智能、RAG 集成、容错共识机制和企业级安全性。
- **原生 Claude 集成**: 深度集成 Claude Code / Codex，作为核心开发平台。

**技术亮点**:
- **自学习/自优化架构**: 包含路由、集群、智能体、记忆和 LLM 提供者的完整学习循环。
- **RuVector 智能层**: 集成了 SONA（自优化）、EWC++（防遗忘）、HNSW（高速检索）、LoRA 微调、Int8 量化等多种先进 AI 技术。
- **灵活的集群拓扑**: 支持网状、分层、环形、星形等多种协调拓扑和共识协议（如 Raft、BFT）。

---
## 4. [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **语言**: Python
- **Stars**: 89,011
- **简介**: Python tool for converting files and office documents to Markdown.

### AI 总结
**简介**: MarkItDown 是微软开源的一个轻量级 Python 工具，专注于将多种文件和办公文档（如 PDF、Word、Excel、PPT 等）高效地转换为 Markdown 格式，以便于大语言模型（LLM）和文本分析流程使用。

**核心功能**:
- 支持广泛的文件格式转换，包括 PDF、Office 文档、图像（OCR）、音频（语音转录）、HTML、文本格式（CSV/JSON/XML）、ZIP、YouTube 链接和 EPub 等。
- 提供命令行工具和 Python API 两种使用方式，支持文件路径输入和管道操作。
- 通过可选的依赖分组（如 `[pdf]`、`[docx]`）实现按需安装，保持核心轻量化。
- 现已提供 MCP（Model Context Protocol）服务器，便于与 Claude Desktop 等 LLM 应用集成。

**技术亮点**:
- 设计目标明确：为 LLM 和文本分析优化，注重保留文档结构（标题、列表、表格、链接等）而非高保真视觉呈现。
- 架构优化：从 0.1.0 版本起，转换接口改为直接操作二进制文件流，不再创建临时文件，提升了效率和资源利用率。
- 依赖管理灵活：采用 `pip install 'markitdown[all]'` 安装全部功能，或按需选择特定格式的依赖。

---
## 5. [bytedance/deer-flow](https://github.com/bytedance/deer-flow)
- **语言**: Python
- **Stars**: 23,000
- **简介**: An open-source SuperAgent harness that researches, codes, and creates. With the help of sandboxes, memories, tools, skills and subagents, it handles different levels of tasks that could take minutes to hours.

### AI 总结
**简介**: DeerFlow 是一个由字节跳动开源的超级智能体框架，它通过编排子智能体、记忆和沙箱，利用可扩展的技能来处理从几分钟到数小时不等的复杂任务。

**核心功能**:
- **技能与工具**: 提供可扩展的技能和工具库，增强智能体的能力。
- **子智能体**: 支持编排多个子智能体协同工作。
- **沙箱与文件系统**: 提供安全的沙箱环境，支持文件系统操作。
- **上下文工程**: 优化和管理任务执行的上下文。
- **长期记忆**: 具备长期记忆能力，用于存储和回顾信息。

**技术亮点**: 基于 Python 开发，采用 LangChain 集成大语言模型，支持 Docker 容器化部署，并提供了配置驱动的模型管理和安全的沙箱执行环境。

---
## 6. [alibaba/OpenSandbox](https://github.com/alibaba/OpenSandbox)
- **语言**: Python
- **Stars**: 3,400
- **简介**: OpenSandbox is a general-purpose sandbox platform for AI applications, offering multi-language SDKs, unified sandbox APIs, and Docker/Kubernetes runtimes for scenarios like Coding Agents, GUI Agents, Agent Evaluation, AI Code Execution, and RL Training.

### AI 总结
**简介**: OpenSandbox 是阿里巴巴开源的一个通用 AI 应用沙箱平台，为构建和运行 AI 应用（如代码智能体、GUI 智能体、AI 代码执行等）提供安全、隔离的执行环境。

**核心功能**:
- **多语言 SDK**: 提供 Python、Java/Kotlin、JavaScript/TypeScript、C#/.NET 等多种语言的沙箱开发工具包。
- **统一沙箱协议**: 定义了沙箱生命周期管理和执行的标准 API，支持扩展自定义沙箱运行时。
- **灵活的运行时**: 内置支持 Docker 和高性能 Kubernetes 运行时，既支持本地运行，也支持大规模分布式调度。
- **丰富的沙箱环境**: 内置命令行、文件系统和代码解释器等基础环境，并提供浏览器自动化（Chrome, Playwright）、桌面环境（VNC, VS Code）等高级场景示例。
- **网络策略管理**: 提供统一的入口网关（Ingress Gateway）和针对每个沙箱的出口流量控制（Egress Controls）。

**技术亮点**: 采用容器化（Docker/Kubernetes）技术实现资源隔离与调度，通过定义标准化的沙箱协议实现跨语言和运行时的统一管理，并内置了面向 AI 应用（如代码解释、GUI 交互）的专用环境组件。

---
## 7. [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)
- **语言**: Python
- **Stars**: 98,726
- **简介**: Collection of awesome LLM apps with AI Agents and RAG using OpenAI, Anthropic, Gemini and opensource models.

### AI 总结
**简介**: 一个精心整理的、汇集了各类优秀大语言模型（LLM）应用的开源项目集合。

**核心功能**:
- 展示和收集基于 RAG、AI 智能体、多智能体团队、MCP、语音智能体等技术构建的 LLM 应用。
- 涵盖使用 OpenAI、Anthropic、Google Gemini、xAI 以及 Qwen、Llama 等开源模型的应用程序。
- 提供从入门级到进阶的 AI 智能体项目示例，方便学习和实践。

**技术亮点**: 项目聚焦于当前 LLM 应用开发的前沿技术栈，包括检索增强生成、AI 智能体、模型上下文协议等，并支持多种主流和开源模型。

---
## 8. [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills)
- **语言**: Python
- **Stars**: 10,318
- **简介**: A set of ready to use Agent Skills for research, science, engineering, analysis, finance and writing.

### AI 总结
**简介**: 一个包含148+个即用型科学、研究、工程、分析和金融技能的集合，遵循开放的Agent Skills标准，可将支持该标准的AI助手（如Cursor、Claude Code）转变为强大的研究助理。

**核心功能**:
- 提供覆盖生物信息学、化学信息学、临床研究、医学影像、机器学习、物理学、工程学、数据分析和科学写作等十多个领域的预设技能。
- 集成访问超过250个科学和金融数据库与数据源，如PubMed、ChEMBL、SEC EDGAR、Alpha Vantage等。
- 支持复杂的多步骤科学工作流，使AI代理能够无缝使用专业的科学库、数据库和工具。

**技术亮点**: 基于Python，遵循开放的[Agent Skills](https://agentskills.io/)标准，技能经过精心设计，提供文档和示例，显著提升了AI代理在专业工作流中的可靠性和能力。

---
## 9. [basecamp/omarchy](https://github.com/basecamp/omarchy)
- **语言**: Shell
- **Stars**: 20,744
- **简介**: Beautiful, Modern & Opinionated Linux

### AI 总结
**简介**: 一个由 DHH 创建、美观现代且具有鲜明设计主张的 Linux 发行版。

**核心功能**:
- 提供一个美观且现代化的 Linux 桌面环境。
- 集成了一套经过精心挑选和配置的软件与工具（Opinionated）。

**技术亮点**: 基于 Shell 脚本进行系统配置与管理。

---
## 10. [X-PLUG/MobileAgent](https://github.com/X-PLUG/MobileAgent)
- **语言**: Python
- **Stars**: 7,709
- **简介**: Mobile-Agent: The Powerful GUI Agent Family

### AI 总结
**简介**: Mobile-Agent 是阿里巴巴通义实验室推出的一个强大的图形用户界面（GUI）智能体家族，旨在实现跨桌面、移动端和浏览器的自动化操作。

**核心功能**:
- 提供多平台GUI自动化能力，支持桌面、移动设备和浏览器。
- 发布了一系列GUI智能体基础模型（如GUI-Owl 1.5系列），在20多个GUI基准测试中达到SOTA水平。
- 提供在线演示和API，方便用户快速体验和集成。

**技术亮点**: 基于Qwen3-VL构建，支持端到端任务、视觉定位、工具/MCP调用以及长程记忆，并提供了从2B到235B不同规模的模型。

---
