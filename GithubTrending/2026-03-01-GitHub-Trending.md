---
tags:
  - github-trending
  - daily
date: 2026-03-01
created: 2026-03-01T01:55:50.162Z
---

# 2026-03-01 GitHub Trending Top 10

## 1. [ruvnet/wifi-densepose](https://github.com/ruvnet/wifi-densepose)
- **语言**: Rust
- **Stars**: 11,286
- **简介**: Production-ready implementation of InvisPose - a revolutionary WiFi-based dense human pose estimation system that enables real-time full-body tracking through walls using commodity mesh routers

### AI 总结
**简介**: 一个基于 WiFi 信道状态信息（CSI）实现实时、无摄像头、隐私保护的全人体姿态估计系统。

**核心功能**:
- **隐私优先的姿态检测**: 利用普通 WiFi 信号（而非摄像头）进行人体姿态估计与追踪。
- **实时多目标追踪**: 支持高达 30 FPS 的实时处理，可同时追踪多达 10 人。
- **硬件兼容性强**: 支持从 ESP32 开发板到商用 WiFi 路由器等多种硬件方案。
- **企业级 API**: 提供包含身份验证、速率限制和监控的生产就绪级 API 及 WebSocket 流。

**技术亮点**:
- **高性能 Rust 实现**: 核心算法已移植至 Rust，相比 Python 版本，全处理流水线速度提升约 810 倍。
- **模块化硬件支持**: 提供从 ESP32-S3 传感器节点（用于捕获原始 CSI 数据）到 Rust 聚合器的完整硬件处理流水线。
- **全面的应用分析**: 内置跌倒检测、活动识别和占用监控等高级分析功能。

---
## 2. [moeru-ai/airi](https://github.com/moeru-ai/airi)
- **语言**: TypeScript
- **Stars**: 19,374
- **简介**: 💖🧸 Self hosted, you-owned Grok Companion, a container of souls of waifu, cyber livings to bring them into our worlds, wishing to achieve Neuro-sama's altitude. Capable of realtime voice chat, Minecraft, Factorio playing. Web / macOS / Windows supported.

### AI 总结
**简介**: AIRI 是一个自托管、用户所有的 AI 伴侣/虚拟角色容器项目，旨在将赛博生命（如虚拟女友、数字宠物）带入现实世界，并追求达到 Neuro-sama 的水平。

**核心功能**:
- 支持实时语音聊天。
- 能够游玩《我的世界》和《异星工厂》等游戏。
- 提供 Web、macOS 和 Windows 客户端。

**技术亮点**: 项目使用 TypeScript 开发，并基于现代大语言模型（如 ChatGPT、Claude）构建。其生态系统包含一个专门的组织（@proj-airi），用于管理相关的子项目，如 RAG、记忆系统、嵌入式数据库和 Live2D 工具等。

---
## 3. [anthropics/claude-code](https://github.com/anthropics/claude-code)
- **语言**: Shell
- **Stars**: 71,859
- **简介**: Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands.

### AI 总结
**简介**: Claude Code 是一个基于终端的智能编码助手，通过自然语言命令帮助开发者理解代码库、执行常规任务并处理 Git 工作流。

**核心功能**:
- 通过自然语言命令执行常规编码任务
- 解释复杂代码
- 处理 Git 工作流

**技术亮点**: 支持插件扩展功能，提供跨平台安装（MacOS/Linux/Windows），包含数据收集与隐私保护机制。

---
## 4. [tukaani-project/xz](https://github.com/tukaani-project/xz)
- **语言**: C
- **Stars**: 1,233
- **简介**: XZ Utils

### AI 总结
**简介**: XZ Utils 是一个集成了 LZMA 和 LZMA2 压缩算法的免费通用数据压缩软件。

**核心功能**:
- 提供 `liblzma` 库，这是一个具有类似 zlib API 的压缩库。
- 提供命令行工具 `xz`，用于压缩和解压 `.xz` 和 `.lzma` 格式的文件。

**技术亮点**: 核心压缩算法基于 LZMA/LZMA2，提供了高压缩比。其代码设计为高度可移植，支持 POSIX 系统（如 GNU/Linux）、类 POSIX 系统、Windows 以及一些其他系统。

---
## 5. [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)
- **语言**: Python
- **Stars**: 98,273
- **简介**: Collection of awesome LLM apps with AI Agents and RAG using OpenAI, Anthropic, Gemini and opensource models.

### AI 总结
**简介**: 一个精心整理的、展示如何利用RAG、AI智能体、多智能体团队、MCP、语音智能体等技术构建大型语言模型应用的资源集合。

**核心功能**:
- 汇集了使用OpenAI、Anthropic、Gemini、xAI及开源模型（如Qwen、Llama）构建的各类LLM应用。
- 涵盖多种应用场景，包括AI智能体、检索增强生成、多智能体协作等。
- 提供从入门到进阶的示例项目，帮助开发者学习和实践LLM应用开发。

**技术亮点**: 项目重点展示了RAG、AI Agents、Multi-agent Teams、MCP（Model Context Protocol）、Voice Agents等前沿LLM应用架构与技术。

---
## 6. [ruvnet/ruflo](https://github.com/ruvnet/ruflo)
- **语言**: TypeScript
- **Stars**: 16,577
- **简介**: 🌊 The leading agent orchestration platform for Claude. Deploy intelligent multi-agent swarms, coordinate autonomous workflows, and build conversational AI systems. Features enterprise-grade architecture, distributed swarm intelligence, RAG integration, and native Claude Code / Codex Integration

### AI 总结
**简介**: Ruflo 是一个基于 Claude Code 的企业级 AI 智能体编排平台，用于部署和协调多智能体集群，以完成复杂的软件工程任务。

**核心功能**:
- **多智能体集群编排**: 支持部署和协调 60 多个具备自学习能力的专业化智能体，支持多种集群拓扑结构（如网状、分层、环形、星形）。
- **企业级架构**: 具备分布式集群智能、RAG 集成、原生 Claude Code/Codex 集成，以及容错共识机制和安全特性。
- **智能路由与学习循环**: 采用 Q-Learning 路由器、专家混合模型和持续的学习循环（检索、判断、提炼、巩固、路由）来优化任务执行。

**技术亮点**: 平台底层使用 Rust 编写的 WASM 内核驱动策略引擎、嵌入和证明系统；集成了 RuVector 智能层，包含 SONA 自优化、EWC++ 防遗忘、Flash Attention 加速、HNSW 快速检索、LoRA 微调等多种先进算法与技术。

---
## 7. [bytedance/deer-flow](https://github.com/bytedance/deer-flow)
- **语言**: Python
- **Stars**: 22,620
- **简介**: An open-source SuperAgent harness that researches, codes, and creates. With the help of sandboxes, memories, tools, skills and subagents, it handles different levels of tasks that could take minutes to hours.

### AI 总结
**简介**: DeerFlow 是一个开源的超级智能体框架，通过编排子智能体、记忆和沙箱，并利用可扩展的技能来处理从几分钟到数小时不等的复杂任务。

**核心功能**:
- **技能与工具**: 提供可扩展的技能库，增强智能体的能力。
- **子智能体**: 支持编排多个子智能体协同工作。
- **沙箱与文件系统**: 提供安全的代码执行环境，支持本地、Docker及Kubernetes等多种运行模式。
- **上下文工程**: 优化智能体的上下文管理与提示工程。
- **长期记忆**: 为智能体提供持久化记忆能力。

**技术亮点**: 基于Python开发，深度集成LangChain，支持通过Docker快速部署，并提供了灵活的沙箱执行模式（本地、Docker、Kubernetes）以适应不同安全与隔离需求。

---
## 8. [Wei-Shaw/claude-relay-service](https://github.com/Wei-Shaw/claude-relay-service)
- **语言**: JavaScript
- **Stars**: 8,696
- **简介**: CRS-自建Claude Code镜像，一站式开源中转服务，让 Claude、OpenAI、Gemini、Droid 订阅统一接入，支持拼车共享，更高效分摊成本，原生工具无缝使用。

### AI 总结
**简介**: 一个用于自建 Claude API 中转服务的开源项目，支持多账户管理、成本分摊和统一接入多个AI服务。

**核心功能**:
- **多账户管理与智能轮换**：支持添加多个 Claude 账户，并能自动切换。
- **统一接入与成本分摊**：可将 Claude、OpenAI、Gemini 等服务的订阅统一接入，便于拼车共享以分摊成本。
- **数据安全与隐私保护**：所有请求直连官方 API，对话内容仅经过用户自己的服务器。
- **完整的使用监控**：提供详细的 Token 使用统计、成本分析和 Web 监控面板。
- **灵活的部署方式**：提供一键脚本部署和手动部署两种方式，支持 Docker。

**技术亮点**:
- 技术栈基于 **Node.js** 和 **Redis**，确保高性能和状态管理。
- 提供交互式管理脚本，简化安装、配置和运维流程。
- 支持代理、连接池、缓存等性能优化措施，并具备访问限制、速率控制等安全功能。

---
## 9. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 1,136
- **简介**: 

### AI 总结
**简介**: Hermes Agent 是一个完全开源的、可自主学习和成长的 AI 智能体，可部署在本地服务器上，通过连接多种通讯平台和利用持久化记忆，为用户提供个性化的自动化助手服务。

**核心功能**:
- **多平台接入**：支持 Telegram、Discord、Slack、WhatsApp 和 CLI，实现跨平台消息同步与交互。
- **持久化学习与技能库**：具备跨会话的持久记忆，可学习用户偏好和项目，并能将解决方案编写为可搜索、可共享的技能文档。
- **计划任务与自动化**：内置 cron 调度器，支持用自然语言设置定时任务并自动交付到任何平台。
- **并行工作与子代理**：可生成隔离的子代理进行并行工作流处理，并能编写 Python 脚本通过 RPC 调用自身工具。
- **安全的沙箱环境**：提供本地、Docker、SSH、Singularity 和 Modal 五种终端后端，支持持久工作空间和后台进程管理。

**技术亮点**:
- **模型无关性**：支持通过 Nous Portal、OpenRouter 或自定义 VLLM/SGLang 端点连接多种大模型，无需更改代码。
- **研究支持**：内置用于批量生成工具调用轨迹的批处理运行器，以及用于强化学习训练的 Atropos RL 环境。
- **现代化工具链**：使用 `uv` 作为快速的 Python 包管理器进行安装和管理。

---
## 10. [superset-sh/superset](https://github.com/superset-sh/superset)
- **语言**: TypeScript
- **Stars**: 2,457
- **简介**: IDE for the AI Agents Era - Run an army of Claude Code, Codex, etc. on your machine

### AI 总结
**简介**: Superset 是一个专为 AI 智能体时代设计的集成开发环境（IDE），允许开发者在本地机器上同时运行和管理多个 CLI 编码智能体（如 Claude Code、Codex 等）。

**核心功能**:
- **并行执行**：可同时运行 10 个以上的编码智能体。
- **工作区隔离**：每个任务都在独立的 Git 工作树中运行，避免相互干扰。
- **集中监控**：在一个界面中监控所有智能体状态，并在需要关注时获得通知。
- **内置差异查看器**：无需离开应用即可检查和编辑智能体生成的代码变更。
- **通用兼容性**：支持任何可在终端运行的 CLI 智能体。

**技术亮点**: 基于 TypeScript 开发，使用 Bun 运行时，通过 Caddy 实现反向代理，并采用 Git 工作树进行任务隔离。

---
