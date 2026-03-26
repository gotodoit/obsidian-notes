---
tags:
  - github-trending
  - daily
date: 2026-03-26
created: 2026-03-26T01:55:49.487Z
---

# 2026-03-26 GitHub Trending Top 10

## 1. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 7,772
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个AI智能体技能，能跨Reddit、X、YouTube、Hacker News、Polymarket和网络等平台研究过去30天的任何话题，并生成有真实引用的综合摘要。

**核心功能**:
- 跨平台聚合研究：从Reddit、X、Bluesky、YouTube、TikTok、Instagram、Hacker News、Polymarket和全网抓取过去30天的内容。
- 智能分析与摘要：通过多信号质量排名相关性评分、去重和收敛检测，生成有数据支持的叙述性总结和对比报告。
- 支持对比模式：可进行“X vs Y”式查询，生成并行的研究报告和对比表格。
- 自动保存与个人知识库：每次运行自动将完整简报保存为Markdown文件至本地文档文件夹。

**技术亮点**:
- 采用Python开发，支持在Claude Code和ClawHub平台安装使用。
- 集成ScrapeCreators API，一个密钥覆盖Reddit、TikTok和Instagram三个数据源。
- 实现复杂的多源评分管道，包括文本相似性、参与度标准化、来源权威权重和跨平台收敛检测。
- 支持项目级环境配置（`.claude/last30days.env`）和会话启动时的自动配置验证。
- 拥有超过455个测试用例的广泛测试覆盖。

---
## 2. [bytedance/deer-flow](https://github.com/bytedance/deer-flow)
- **语言**: Python
- **Stars**: 46,356
- **简介**: An open-source SuperAgent harness that researches, codes, and creates. With the help of sandboxes, memories, tools, skill, subagents and message gateway, it handles different levels of tasks that could take minutes to hours.

### AI 总结
**简介**: DeerFlow 是一个由字节跳动开源的超级智能体框架，通过编排子智能体、记忆和沙箱环境，能够处理从几分钟到数小时不等的复杂任务。

**核心功能**:
- **智能体编排**：通过子智能体、技能和工具集协同工作，处理多层次任务。
- **沙箱环境**：提供安全的代码执行和文件系统操作环境。
- **长期记忆**：支持上下文工程，实现跨会话的记忆管理。
- **多模型支持**：推荐并支持使用豆包、DeepSeek、Kimi等大语言模型。

**技术亮点**:
- **架构**：采用模块化设计，包含技能库、消息网关、MCP服务器等可扩展组件。
- **技术栈**：基于 Python 3.12+ 和 Node.js 22+，支持 Docker 一键部署。
- **集成**：无缝集成字节跳动的 InfoQuest 智能搜索与爬取工具集。

---
## 3. [BerriAI/litellm](https://github.com/BerriAI/litellm)
- **语言**: Python
- **Stars**: 40,680
- **简介**: Python SDK, Proxy Server (AI Gateway) to call 100+ LLM APIs in OpenAI (or native) format, with cost tracking, guardrails, loadbalancing and logging. [Bedrock, Azure, OpenAI, VertexAI, Cohere, Anthropic, Sagemaker, HuggingFace, VLLM, NVIDIA NIM]

### AI 总结
**简介**: LiteLLM 是一个 Python SDK 和代理服务器（AI Gateway），旨在通过统一的 OpenAI 格式调用超过 100 种不同的 LLM API。

**核心功能**:
- **统一接口调用**: 提供标准化的 OpenAI 格式接口，支持调用包括 Bedrock、Azure、OpenAI、VertexAI、Anthropic、Groq 等在内的众多 LLM 服务。
- **代理服务器（AI Gateway）**: 可作为独立的代理服务器运行，提供虚拟密钥管理、成本追踪、防护、负载均衡和日志记录等企业级功能。
- **多协议支持**: 不仅支持传统的 `/chat/completions` 等端点，还支持新兴的 A2A（Agent-to-Agent）协议，可用于调用 LangGraph、Pydantic AI 等代理框架。

**技术亮点**: 采用 Python 开发，通过 SDK 和代理服务器的组合，实现了对异构 LLM 服务的抽象和统一管理，简化了多模型集成的复杂性。

---
## 4. [pascalorg/editor](https://github.com/pascalorg/editor)
- **语言**: TypeScript
- **Stars**: 6,867
- **简介**: Create and share 3D architectural projects.

### AI 总结
**简介**: 一个基于 React Three Fiber 和 WebGPU 构建的 3D 建筑编辑器，用于创建和分享建筑项目。

**核心功能**:
- 提供交互式 3D 编辑环境，支持创建和编辑建筑、楼层、墙体、门窗等元素。
- 采用清晰的分层架构，将核心数据逻辑、3D 渲染和编辑器 UI 分离，便于维护和扩展。
- 内置强大的状态管理（Zustand）与持久化（IndexedDB）功能，支持撤销/重做操作。

**技术亮点**:
- **技术栈**: TypeScript, React, Next.js (Turborepo 管理), React Three Fiber, WebGPU。
- **架构**: 采用 Monorepo 结构，核心包（`@pascal-app/core`）负责数据模型与状态，渲染包（`@pascal-app/viewer`）处理 3D 渲染，应用（`apps/editor`）专注于编辑器交互。
- **状态管理**: 使用 Zustand 分模块管理场景、视图和编辑器状态，并集成 Zundo 实现撤销/重做。
- **渲染与更新**: 通过“节点渲染器”组件化生成 3D 对象，配合“系统”在渲染循环中高效更新几何体和变换。

---
## 5. [letta-ai/claude-subconscious](https://github.com/letta-ai/claude-subconscious)
- **语言**: TypeScript
- **Stars**: 1,474
- **简介**: Give Claude Code a subconscious

### AI 总结
**简介**: 一个为 Claude Code 提供后台记忆与智能提示的 Letta 代理插件。

**核心功能**:
- **会话监控与学习**：后台监听 Claude Code 的会话记录，并读取代码库文件。
- **持久化记忆**：跨会话、项目和时间为 Claude Code 建立并维护记忆。
- **智能提示**：在每次用户输入前，通过标准输出“低语”提供上下文、模式和提醒。
- **非阻塞运行**：基于 Letta Code SDK 在后台异步运行，不影响主会话流程。

**技术亮点**:
- 基于 **Letta 平台**的代理系统，具备文件读取（Read）、搜索（Grep、Glob）和网络访问等工具能力。
- 采用 **TypeScript** 开发，通过 SDK 与 Claude Code 集成，架构清晰（主代理与后台代理分离）。

---
## 6. [ruvnet/ruflo](https://github.com/ruvnet/ruflo)
- **语言**: TypeScript
- **Stars**: 26,258
- **简介**: 🌊 The leading agent orchestration platform for Claude. Deploy intelligent multi-agent swarms, coordinate autonomous workflows, and build conversational AI systems. Features enterprise-grade architecture, distributed swarm intelligence, RAG integration, and native Claude Code / Codex Integration

### AI 总结
**简介**: RuFlo 是一个基于 TypeScript 开发的企业级 AI 智能体编排平台，专为 Claude Code 设计，用于部署和管理协同工作的多智能体集群。

**核心功能**:
- **多智能体集群编排**: 支持部署和协调超过 100 个具备自学习能力的专业化智能体，共同处理复杂的软件工程任务。
- **企业级架构**: 提供分布式集群智能、RAG（检索增强生成）集成，并原生支持 Claude Code/Codex。
- **智能路由与学习循环**: 包含 Q-Learning 路由器、专家混合模型以及一个完整的“检索-判断-提炼-巩固-路由”学习闭环，实现系统自我优化。

**技术亮点**:
- **底层性能**: 核心策略引擎、嵌入和证明系统由 Rust 编写的 WASM 内核驱动，强调高性能。
- **高级算法集成**: 架构中包含 SONA（自优化神经网络）、EWC++（防止灾难性遗忘）、Flash Attention、HNSW（近似最近邻搜索）等多种先进机器学习与优化算法。
- **灵活的集群拓扑**: 支持网状、分层、环形、星形等多种智能体网络拓扑和共识机制（如 Raft、BFT）。

---
## 7. [Crosstalk-Solutions/project-nomad](https://github.com/Crosstalk-Solutions/project-nomad)
- **语言**: TypeScript
- **Stars**: 16,671
- **简介**: Project N.O.M.A.D, is a self-contained, offline survival computer packed with critical tools, knowledge, and AI to keep you informed and empowered—anytime, anywhere.

### AI 总结
**简介**: Project N.O.M.A.D. 是一个自包含、离线优先的知识与教育服务器，集成了关键工具、知识和AI，旨在让用户随时随地获取信息并保持自主能力。

**核心功能**:
- **AI聊天与知识库**：基于Ollama的本地AI聊天，支持文档上传和语义搜索（通过Qdrant实现RAG）。
- **离线信息库**：通过Kiwix提供离线维基百科、医学参考、电子书等资源。
- **教育平台**：通过Kolibri提供可汗学院课程，支持进度跟踪和多用户。
- **离线地图**：通过ProtoMaps提供可下载的区域地图，支持搜索和导航。
- **数据工具**：集成CyberChef，提供加密、编码、哈希和数据分析功能。
- **本地笔记**：通过FlatNotes支持Markdown的本地笔记应用。
- **系统基准测试**：内置硬件评分系统，并设有社区排行榜。

**技术亮点**: 项目采用Docker容器化架构，通过一个统一的“指挥中心”管理界面和API来编排所有工具和服务，实现了便捷的安装、配置和更新。核心栈包括TypeScript、Ollama、Qdrant、Kiwix、Kolibri等。

---
## 8. [ruvnet/RuView](https://github.com/ruvnet/RuView)
- **语言**: Rust
- **Stars**: 42,341
- **简介**: π RuView: WiFi DensePose turns commodity WiFi signals into real-time human pose estimation, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: RuView 是一个基于 Rust 的、无需摄像头或可穿戴设备的边缘 AI 感知系统，它利用 WiFi 等环境信号实现实时人体姿态估计、生命体征监测和存在检测。

**核心功能**:
- **人体姿态估计**: 通过分析 WiFi 信道状态信息（CSI）扰动，实时重建人体姿态（DensePose）。
- **生命体征监测**: 检测呼吸频率（6-30 BPM）和心率（40-120 BPM）。
- **存在与运动感知**: 基于信号方差和运动频带功率，实现低延迟（<1ms）的存在检测。
- **穿墙感知**: 利用菲涅尔区几何和多径建模，实现一定深度（可达5米）的感知。

**技术亮点**:
- **边缘智能与自学习**: 基于 RuVector 自学习向量内存系统，系统在边缘设备（如 ESP32）上本地运行和学习，无需互联网、云服务或标注数据，并能持续适应环境。
- **高性能与低成本**: 核心处理使用 Rust 实现，姿态估计速度可达 54K fps；硬件成本低，推荐方案为 ESP32-S3 传感器网格（约 54 美元）。
- **完整的信号处理流水线**: 提供从 CSI 数据采集到姿态、生命体征提取的完整物理信号处理和机器学习流程。

---
## 9. [supermemoryai/supermemory](https://github.com/supermemoryai/supermemory)
- **语言**: TypeScript
- **Stars**: 19,236
- **简介**: Memory engine and app that is extremely fast, scalable. The Memory API for the AI era.

### AI 总结
**简介**: Supermemory 是一个专为 AI 应用设计的、极速且可扩展的记忆与上下文引擎，旨在为 AI 提供持久记忆和智能上下文管理。

**核心功能**:
- **记忆管理**: 自动从对话中提取事实，处理信息的时间变化、矛盾，并实现自动遗忘。
- **用户画像**: 自动维护用户上下文（稳定事实 + 近期活动），调用延迟约 50ms。
- **混合搜索**: 在单一查询中结合 RAG 与记忆，同时获取知识库文档和个性化上下文。
- **多源连接器**: 支持 Google Drive、Gmail、Notion、OneDrive、GitHub 等，通过实时 Webhook 自动同步。
- **多模态提取**: 支持处理 PDF、图像（OCR）、视频（转录）、代码（基于 AST 的分块）等多种格式。

**技术亮点**: 基于 TypeScript 开发，提供统一的记忆结构与本体论，在 LongMemEval、LoCoMo 和 ConvoMem 三大 AI 记忆基准测试中均排名第一。提供 npm 和 PyPI 包，并支持通过 MCP 协议与多种开发工具（如 Claude、Cursor、VSCode）快速集成。

---
## 10. [FujiwaraChoki/MoneyPrinterV2](https://github.com/FujiwaraChoki/MoneyPrinterV2)
- **语言**: Python
- **Stars**: 25,619
- **简介**: Automate the process of making money online.

### AI 总结
**简介**: MoneyPrinter V2 是一个用 Python 编写的自动化在线赚钱应用程序，是原项目的完全重写版本。

**核心功能**:
- Twitter 机器人（支持定时任务调度）
- YouTube Shorts 自动化（支持定时任务调度）
- 联盟营销（亚马逊 + Twitter）
- 寻找本地企业并进行冷接触

**技术亮点**: 采用模块化架构，需要 Python 3.12 环境运行，并集成了社区开发的工具如 KittenTTS 和 gpt4free。

---
