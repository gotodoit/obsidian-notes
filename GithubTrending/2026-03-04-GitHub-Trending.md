---
tags:
  - github-trending
  - daily
date: 2026-03-04
created: 2026-03-04T01:55:49.310Z
---

# 2026-03-04 GitHub Trending Top 10

## 1. [ruvnet/RuView](https://github.com/ruvnet/RuView)
- **语言**: Rust
- **Stars**: 25,404
- **简介**: π RuView: WiFi DensePose turns commodity WiFi signals into real-time human pose estimation, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: RuView 是一个利用普通WiFi信号实现实时人体姿态估计、生命体征监测和存在检测的系统，无需摄像头或可穿戴设备。

**核心功能**:
- **人体姿态估计**: 通过分析WiFi信道状态信息（CSI）的扰动，重建人体姿态。
- **生命体征监测**: 检测呼吸频率（6-30次/分钟）和心率（40-120次/分钟）。
- **存在与运动检测**: 实现亚毫秒级延迟的存在感知。
- **穿墙感知**: 利用菲涅尔区几何和多径建模，支持穿墙检测（深度可达5米）。
- **多目标跟踪**: 可同时跟踪多人的姿态和生命体征。

**技术亮点**:
- **技术栈**: 核心系统使用Rust编写，性能极高（姿态估计可达54K fps）。
- **边缘智能**: 提供可在ESP32等边缘设备上独立运行的模块，无需网络连接或云端费用。
- **硬件支持**: 需要支持CSI的硬件（如ESP32-S3或研究网卡）以实现完整功能。
- **架构文档**: 项目包含44份架构决策记录（ADR）和7个领域驱动设计（DDD）模型，设计严谨。

---
## 2. [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills)
- **语言**: Python
- **Stars**: 11,968
- **简介**: A set of ready to use Agent Skills for research, science, engineering, analysis, finance and writing.

### AI 总结
**简介**: 一个包含170多个即用型科学和研究技能的Python工具集，可将AI助手转变为跨学科研究助理。

**核心功能**:
- 提供涵盖生物信息学、药物发现、临床研究、机器学习、材料科学等领域的170多种预定义技能
- 支持与250多个科学数据库和工具的无缝集成
- 兼容遵循开放Agent Skills标准的AI代理（如Cursor、Claude Code等）

**技术亮点**: 基于开放的Agent Skills标准构建，提供结构化的技能文档和示例，支持复杂多步骤科学工作流的自动化执行。

---
## 3. [moeru-ai/airi](https://github.com/moeru-ai/airi)
- **语言**: TypeScript
- **Stars**: 22,199
- **简介**: 💖🧸 Self hosted, you-owned Grok Companion, a container of souls of waifu, cyber livings to bring them into our worlds, wishing to achieve Neuro-sama's altitude. Capable of realtime voice chat, Minecraft, Factorio playing. Web / macOS / Windows supported.

### AI 总结
**简介**: AIRI 是一个自托管、用户拥有的 AI 伴侣/虚拟角色容器项目，旨在复现 Neuro-sama 的体验，将赛博生命带入现实世界。

**核心功能**:
- 支持实时语音聊天。
- 能够游玩 Minecraft、Factorio 等游戏。
- 提供 Web、macOS 和 Windows 客户端。

**技术亮点**: 项目使用 TypeScript 开发，并基于现代大语言模型（如 ChatGPT、Claude）构建，拥有独立的子项目组织，专注于 RAG、记忆系统、嵌入式数据库、Live2D 工具等组件。

---
## 4. [CodebuffAI/codebuff](https://github.com/CodebuffAI/codebuff)
- **语言**: TypeScript
- **Stars**: 3,286
- **简介**: Generate code from the terminal!

### AI 总结
**简介**: Codebuff 是一个开源的 AI 代码助手，能通过自然语言指令理解和编辑你的代码库。

**核心功能**:
- **多智能体协作**: 通过协调文件选取、规划、编辑和审查等专门智能体，精准理解和修改代码。
- **终端直接操作**: 提供 CLI 工具，安装后即可在项目目录中通过自然语言指令（如“修复 SQL 注入漏洞”）执行复杂代码任务。
- **高度可定制**: 支持开发者创建自定义智能体，通过 TypeScript 定义其行为、工具和工作流程。
- **生产级 SDK**: 提供 `@codebuff/sdk` 包，允许在应用程序中集成并运行智能体。

**技术亮点**: 采用 TypeScript 开发，其多智能体架构能更好地理解项目上下文，相比单一模型工具错误更少。支持通过 OpenRouter 灵活选用多种 AI 模型（如 Claude、GPT、Qwen 等），而非锁定单一供应商。

---
## 5. [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope)
- **语言**: Python
- **Stars**: 17,048
- **简介**: Build and run agents you can see, understand and trust.

### AI 总结
**简介**: AgentScope 是一个面向生产环境、易于使用的智能体（Agent）框架，旨在构建可观察、可理解和可信赖的智能体。

**核心功能**:
- **简单易用**：内置 ReAct 智能体、工具、技能、人机交互、记忆、规划、实时语音、评估和模型微调，可在 5 分钟内快速构建智能体。
- **高度可扩展**：拥有丰富的生态系统集成（工具、记忆、可观测性），内置支持 MCP 和 A2A 协议，并提供灵活的多智能体编排与工作流消息中心。
- **生产就绪**：支持本地部署、云端无服务器部署或 K8s 集群部署，并内置 OpenTelemetry 支持。

**技术亮点**: 基于 Python 3.10+，采用 Apache-2.0 开源协议。框架设计充分利用大语言模型的推理和工具使用能力，而非通过严格的提示词和强制的编排来约束模型。

---
## 6. [agentscope-ai/ReMe](https://github.com/agentscope-ai/ReMe)
- **语言**: Python
- **Stars**: 1,302
- **简介**: ReMe: Memory Management Kit for Agents - Remember Me, Refine Me.

### AI 总结
**简介**: ReMe 是一个专为 AI 智能体设计的记忆管理框架，旨在解决智能体在长对话中上下文受限和会话状态丢失的问题。

**核心功能**:
- **文件式记忆系统**：将记忆存储为可读、可编辑的 Markdown 文件，便于查看、修改和迁移。
- **向量式记忆系统**：支持基于语义的智能记忆检索。
- **记忆压缩与摘要**：自动压缩历史对话为摘要，并将重要信息持久化存储。
- **上下文检查与记忆搜索**：管理上下文长度限制，并支持基于语义的记忆搜索。

**技术亮点**:
- 采用模块化设计，包含文件存储、文件监控、嵌入模型、上下文检查器、压缩器和摘要器等核心组件。
- 支持 Python 3.10+，使用 Apache 2.0 开源协议。

---
## 7. [LMCache/LMCache](https://github.com/LMCache/LMCache)
- **语言**: Python
- **Stars**: 7,402
- **简介**: Supercharge Your LLM with the Fastest KV Cache Layer

### AI 总结
**简介**: LMCache 是一个为大型语言模型（LLM）提供高速 KV 缓存层的核心库，旨在通过共享 KV 缓存来显著提升推理性能。

**核心功能**:
- 为 vLLM 推理引擎提供高性能的 KV 缓存层，大幅降低后续请求的首次令牌生成时间。
- 支持在多个独立的 vLLM 实例之间共享前缀 KV 缓存，实现跨实例的缓存复用。

**技术亮点**: 基于 Docker 容器化部署，与 vLLM 深度集成，通过独立的 LMCache 后端服务器实现分布式缓存共享。

---
## 8. [superset-sh/superset](https://github.com/superset-sh/superset)
- **语言**: TypeScript
- **Stars**: 4,197
- **简介**: IDE for the AI Agents Era - Run an army of Claude Code, Codex, etc. on your machine

### AI 总结
**简介**: Superset 是一个专为 AI 智能体时代设计的集成开发环境（IDE），允许开发者在本地机器上同时运行和管理多个 CLI 编码智能体（如 Claude Code、Codex 等）。

**核心功能**:
- **并行执行**：可同时运行 10 个以上的编码智能体。
- **工作树隔离**：每个任务都在独立的 Git 工作树和分支中运行，避免相互干扰。
- **集中监控**：在一个界面中监控所有智能体状态，并在需要关注时接收通知。
- **内置差异查看器**：无需离开应用即可审查和编辑智能体所做的更改。
- **通用兼容性**：支持任何可在终端运行的 CLI 智能体。

**技术亮点**: 项目使用 TypeScript 开发，基于 Bun 运行时，并集成了 Caddy 反向代理（用于 Electric SQL 流）。它通过 Git 工作树实现任务隔离，并提供了可自定义的键盘快捷键系统。

---
## 9. [aquasecurity/trivy](https://github.com/aquasecurity/trivy)
- **语言**: Go
- **Stars**: 557
- **简介**: Find vulnerabilities, misconfigurations, secrets, SBOM in containers, Kubernetes, code repositories, clouds and more

### AI 总结
**简介**: Trivy 是一款用 Go 编写的综合性安全扫描器，用于在容器、Kubernetes、代码仓库、云环境等多种目标中查找漏洞、错误配置、敏感信息和软件物料清单（SBOM）。

**核心功能**:
- **支持多种扫描目标**：容器镜像、文件系统、Git 仓库、虚拟机镜像和 Kubernetes 集群。
- **提供多种安全扫描**：检测操作系统包和软件依赖（SBOM）、已知漏洞（CVE）、基础设施即代码（IaC）问题与错误配置、敏感信息与密钥，以及软件许可证。

**技术亮点**: 采用 Go 语言开发，支持广泛的编程语言、操作系统和平台，并提供了丰富的集成选项（如 GitHub Actions、Kubernetes Operator、VS Code 插件）以及多种安装方式（Homebrew、Docker、二进制文件）。

---
## 10. [alibaba/OpenSandbox](https://github.com/alibaba/OpenSandbox)
- **语言**: Python
- **Stars**: 5,420
- **简介**: OpenSandbox is a general-purpose sandbox platform for AI applications, offering multi-language SDKs, unified sandbox APIs, and Docker/Kubernetes runtimes for scenarios like Coding Agents, GUI Agents, Agent Evaluation, AI Code Execution, and RL Training.

### AI 总结
**简介**: OpenSandbox 是阿里巴巴开源的一个面向 AI 应用的通用沙箱平台，提供多语言 SDK、统一的沙箱 API 以及 Docker/Kubernetes 运行时，适用于代码智能体、GUI 智能体、智能体评估等多种场景。

**核心功能**:
- **多语言 SDK**: 提供 Python、Java/Kotlin、JavaScript/TypeScript、C#/.NET 等多种语言的沙箱 SDK。
- **统一的沙箱协议**: 定义了沙箱生命周期管理和执行 API，支持扩展自定义沙箱运行时。
- **灵活的运行时支持**: 内置支持 Docker 和高性能 Kubernetes 运行时，可实现本地运行和大规模分布式调度。
- **丰富的沙箱环境**: 内置命令行、文件系统和代码解释器环境，并提供了浏览器自动化、桌面环境等多种示例。
- **网络策略管理**: 提供统一的入口网关和针对每个沙箱的出口流量控制。

**技术亮点**:
- 采用容器化技术，支持 Docker 和 Kubernetes，便于部署和扩展。
- 定义了标准化的沙箱协议，具有良好的可扩展性。
- 提供了从基础命令执行到复杂代码解释的完整 API 示例。

---
