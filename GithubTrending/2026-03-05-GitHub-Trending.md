---
tags:
  - github-trending
  - daily
date: 2026-03-05
created: 2026-03-05T01:55:49.950Z
---

# 2026-03-05 GitHub Trending Top 10

## 1. [KeygraphHQ/shannon](https://github.com/KeygraphHQ/shannon)
- **语言**: TypeScript
- **Stars**: 30,470
- **简介**: Shannon Lite is a fully autonomous AI pentester for web apps and APIs. 96.15% (100/104 exploits) on a hint-free, source-aware variant of the XBOW benchmark.

### AI 总结
**简介**: Shannon 是一个由 Keygraph 开发的白盒 AI 渗透测试工具，用于自动分析 Web 应用和 API 的源代码并执行真实攻击以验证漏洞。

**核心功能**:
- **全自动操作**：单条命令即可启动完整渗透测试，自动处理登录、浏览器导航、漏洞利用和报告生成。
- **可复现的漏洞验证**：最终报告仅包含已成功利用的漏洞，并提供可直接复现的攻击证明。
- **代码感知的动态测试**：结合源代码分析与实时浏览器/CLI 攻击，针对运行中的应用进行验证。
- **集成安全工具**：在侦察阶段利用 Nmap、Subfinder 等工具。

**技术亮点**: 基于 TypeScript 开发，采用并行处理架构，支持与 AWS Bedrock 和 Google Vertex AI 集成。提供开源版（Shannon Lite，AGPL-3.0）和商业版（Shannon Pro）两个版本。

---
## 2. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Unknown
- **Stars**: 5,532
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个精心设计的 AI 智能体集合，提供从工程、设计到营销等各领域的专业化、人格化 AI 助手，旨在直接提升工作流程效率。

**核心功能**:
- **专业化智能体**：提供涵盖前端开发、后端架构、UI/UX设计、品牌营销、社区运营等领域的多个专家级 AI 助手。
- **即插即用**：支持快速集成到 Claude Code 等环境中，通过简单指令即可激活并使用特定专家模式。
- **交付导向**：每个智能体都具备独特的个性、明确的工作流程，并专注于产出可执行的代码、设计或策略等具体成果。

**技术亮点**: 项目本身是一个智能体配置与提示词的集合，主要设计用于与 Claude 等大型语言模型配合使用，通过高度结构化的提示工程来模拟不同领域的专家行为。

---
## 3. [aquasecurity/trivy](https://github.com/aquasecurity/trivy)
- **语言**: Go
- **Stars**: 868
- **简介**: Find vulnerabilities, misconfigurations, secrets, SBOM in containers, Kubernetes, code repositories, clouds and more

### AI 总结
**简介**: Trivy 是一个用 Go 编写的综合性安全扫描器，用于在容器、Kubernetes、代码仓库、云等多种目标中查找漏洞、错误配置、密钥和软件物料清单（SBOM）。

**核心功能**:
- **支持多种扫描目标**：容器镜像、文件系统、Git 仓库、虚拟机镜像和 Kubernetes 集群。
- **提供多种安全扫描**：检测操作系统包和软件依赖（SBOM）、已知漏洞（CVE）、基础设施即代码（IaC）问题与错误配置、敏感信息和密钥，以及软件许可证。
- **广泛的集成与支持**：支持主流编程语言、操作系统和平台，并集成了 GitHub Actions、Kubernetes Operator、VS Code 插件等多种工具。

**技术亮点**:
- 采用 Go 语言开发，具备良好的跨平台性能和易部署性。
- 提供多种安装方式（如 Homebrew、Docker、二进制文件下载）和灵活的 CLI 使用方式。
- 拥有活跃的社区支持和丰富的生态系统集成。

---
## 4. [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills)
- **语言**: Python
- **Stars**: 12,755
- **简介**: A set of ready to use Agent Skills for research, science, engineering, analysis, finance and writing.

### AI 总结
**简介**: 一个包含170多个即用型科学和研究技能的Python工具集，可将AI助手转变为跨学科研究助理。

**核心功能**:
- 提供生物信息学、化学信息学、临床研究、医学影像、机器学习、材料科学等17个领域的专业技能
- 支持复杂多步骤科学工作流的自动化执行
- 兼容支持Agent Skills标准的AI代理（如Cursor、Claude Code、Codex等）

**技术亮点**: 基于开源的Agent Skills标准，集成了250多个专业数据库和科学工具库，提供完整的文档和示例。

---
## 5. [CodebuffAI/codebuff](https://github.com/CodebuffAI/codebuff)
- **语言**: TypeScript
- **Stars**: 3,584
- **简介**: Generate code from the terminal!

### AI 总结
**简介**: Codebuff 是一个开源的 AI 代码助手，能通过自然语言指令理解和编辑你的代码库。

**核心功能**:
- **多智能体协同工作**：通过文件选择、规划、编辑和审查等专门智能体协作，精准理解和修改代码。
- **命令行工具**：通过简单的 `codebuff` 命令，即可在终端中直接使用自然语言指令（如“修复 SQL 注入漏洞”）来修改代码。
- **自定义智能体开发**：支持开发者通过 TypeScript 定义和创建自定义智能体，实现复杂的工作流和程序化控制。
- **生产级 SDK**：提供 `@codebuff/sdk` 包，允许在应用程序中集成并运行智能体。

**技术亮点**:
- **架构**：采用多智能体系统架构，相比单一模型工具，能提供更好的上下文理解、更准确的编辑和更少的错误。
- **模型支持**：支持通过 OpenRouter 使用多种模型（如 Claude、GPT、Qwen、DeepSeek 等），不锁定单一供应商。
- **开发友好**：提供 TypeScript 类型定义和生成器，支持混合 AI 生成与程序化控制，智能体可生成子智能体并执行多步骤流程。

---
## 6. [agentscope-ai/ReMe](https://github.com/agentscope-ai/ReMe)
- **语言**: Python
- **Stars**: 1,638
- **简介**: ReMe: Memory Management Kit for Agents - Remember Me, Refine Me.

### AI 总结
**简介**: ReMe 是一个专为 AI 智能体设计的记忆管理框架，旨在解决智能体在长对话中上下文窗口有限和历史会话无法继承的问题。

**核心功能**:
- **文件化记忆系统 (ReMeLight)**: 将记忆存储为可读、可编辑的 Markdown 文件，便于查看、修改和迁移。
- **向量化记忆系统**: 支持基于向量的语义记忆搜索，实现混合检索。
- **记忆压缩与摘要**: 自动将历史对话压缩为摘要，并将重要信息持久化到文件中。
- **工具结果管理**: 自动管理过大的工具输出结果，进行压缩和缓存清理。

**技术亮点**:
- 采用 **文件与向量双存储系统**，兼顾可读性与高效检索。
- 通过 **ReActAgent** 驱动记忆的压缩与摘要生成。
- 提供 **Token感知的内存管理** 和 **混合检索（向量+BM25）** 能力。
- 设计为轻量级工具包，易于集成到现有智能体框架中。

---
## 7. [alibaba/OpenSandbox](https://github.com/alibaba/OpenSandbox)
- **语言**: Python
- **Stars**: 6,001
- **简介**: OpenSandbox is a general-purpose sandbox platform for AI applications, offering multi-language SDKs, unified sandbox APIs, and Docker/Kubernetes runtimes for scenarios like Coding Agents, GUI Agents, Agent Evaluation, AI Code Execution, and RL Training.

### AI 总结
**简介**: OpenSandbox 是阿里巴巴开源的一个通用 AI 应用沙箱平台，提供多语言 SDK、统一的沙箱 API 以及 Docker/Kubernetes 运行时，适用于编码智能体、GUI 智能体、智能体评估、AI 代码执行和强化学习训练等多种场景。

**核心功能**:
- **多语言 SDK**: 提供 Python、Java/Kotlin、JavaScript/TypeScript、C#/.NET 等多种语言的沙箱 SDK。
- **统一的沙箱协议**: 定义了沙箱生命周期管理和执行 API，支持扩展自定义沙箱运行时。
- **灵活的运行时支持**: 内置支持 Docker 和高性能 Kubernetes 运行时，可实现本地运行和大规模分布式调度。
- **丰富的沙箱环境**: 内置命令行、文件系统和代码解释器，并提供了浏览器自动化（Chrome, Playwright）和桌面环境（VNC, VS Code）等示例。
- **网络策略管理**: 提供统一的入口网关（Ingress Gateway）和针对每个沙箱的出口控制（Egress Controls）。

**技术亮点**:
- 采用微服务架构，核心组件（如入口网关、出口控制器）可独立部署和扩展。
- 支持通过配置文件（TOML）灵活管理沙箱服务器。
- 提供了从基础沙箱操作到复杂场景（如代码解释器）的完整示例和异步编程接口。

---
## 8. [FujiwaraChoki/MoneyPrinterV2](https://github.com/FujiwaraChoki/MoneyPrinterV2)
- **语言**: Python
- **Stars**: 14,222
- **简介**: Automate the process of making money online.

### AI 总结
**简介**: MoneyPrinterV2 是一个用 Python 编写的自动化在线赚钱应用程序，是原项目的完全重写版本。

**核心功能**:
- Twitter 机器人（支持定时任务调度）
- YouTube Shorts 自动化发布（支持定时任务调度）
- 联盟营销（结合亚马逊与 Twitter）
- 寻找本地企业并进行冷接触

**技术亮点**: 采用模块化架构，需要 Python 3.12 环境运行，并集成了第三方 AI 服务（如 KittenTTS、gpt4free）。

---
## 9. [ItzCrazyKns/Perplexica](https://github.com/ItzCrazyKns/Perplexica)
- **语言**: TypeScript
- **Stars**: 30,889
- **简介**: Perplexica is an AI-powered answering engine.

### AI 总结
**简介**: Perplexica 是一个注重隐私、可自托管的 AI 问答引擎，能够结合网络知识和多种 AI 模型提供带来源引用的答案。

**核心功能**:
- **多模型支持**：支持本地 LLM（通过 Ollama）以及 OpenAI、Claude、Gemini、Groq 等云端模型。
- **智能搜索模式**：提供速度、平衡和质量三种模式，适应不同搜索需求。
- **多样化搜索源**：支持网页、讨论、学术论文、图片和视频搜索，并可限定特定网站。
- **文件上传分析**：支持上传 PDF、文本、图片等文件并针对内容提问。
- **隐私保护搜索**：内置 SearxNG 搜索引擎，保护用户搜索隐私。

**技术亮点**: 基于 TypeScript 开发，采用 Docker 容器化部署，架构设计注重隐私和安全，支持本地化运行。

---
## 10. [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope)
- **语言**: Python
- **Stars**: 17,399
- **简介**: Build and run agents you can see, understand and trust.

### AI 总结
**简介**: AgentScope 是一个面向生产环境、易于使用的智能体框架，旨在构建可见、可理解且可信赖的智能体。

**核心功能**:
- **简单易用**: 内置 ReAct 智能体、工具、技能、人机协同、记忆、规划、实时语音、评估和模型微调等功能，可快速上手。
- **高度可扩展**: 提供大量生态系统集成（工具、记忆、可观测性），内置支持 MCP 和 A2A 协议，并通过消息中心实现灵活的多智能体编排与工作流。
- **生产就绪**: 支持本地部署、云端无服务器部署或 K8s 集群部署，并内置 OpenTelemetry 支持。

**技术亮点**: 基于 Python 3.10+，采用 Apache 2.0 开源协议。框架设计充分利用大语言模型的推理和工具使用能力，而非通过严格的提示词和固执的编排来限制它们。

---
