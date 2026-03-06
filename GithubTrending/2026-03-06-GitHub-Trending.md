---
tags:
  - github-trending
  - daily
date: 2026-03-06
created: 2026-03-06T01:55:51.161Z
---

# 2026-03-06 GitHub Trending Top 10

## 1. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Unknown
- **Stars**: 7,650
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个精心设计的 AI 智能体集合，提供从工程、设计到营销等各领域的专家级 AI 助手，旨在通过具备个性和专业流程的智能体来彻底改变工作流程。

**核心功能**:
- 提供多个高度专业化、具备独特个性和沟通风格的 AI 智能体，覆盖前端开发、后端架构、UI/UX 设计、品牌营销、社区运营等广泛领域。
- 每个智能体都专注于交付可衡量的成果，如实际代码、设计流程和具体策略，并包含经过实战检验的工作流程。
- 支持快速集成到 Claude Code 等开发环境中，或作为独立的参考模板进行复制和适配。

**技术亮点**: 项目本身是一个智能体配置与提示词集合，主要设计用于与 Claude 等大型语言模型配合使用，提供了一套即用型、生产就绪的专家级 AI 助手解决方案。

---
## 2. [TheCraigHewitt/seomachine](https://github.com/TheCraigHewitt/seomachine)
- **语言**: Python
- **Stars**: 1,667
- **简介**: A specialized Claude Code workspace for creating long-form, SEO-optimized blog content for any business. This system helps you research, write, analyze, and optimize content that ranks well and serves your target audience.

### AI 总结
**简介**: 一个基于 Claude Code 的 AI 工作空间，专门用于为任何企业研究、撰写、分析和优化长篇 SEO 博客内容。

**核心功能**:
- **全流程内容创作**：提供从 `/research`（研究）、`/write`（撰写）到 `/optimize`（优化）和 `/analyze-existing`（分析现有内容）的完整命令工作流。
- **专业化智能体**：集成内容分析、SEO优化、元标签创建、内部链接、关键词映射、性能分析等多个 AI 智能体，自动执行优化任务。
- **数据驱动与集成**：支持集成 Google Analytics 4、Google Search Console 和 DataForSEO API，以获取实时性能洞察和进行高级 SEO 分析（如搜索意图检测、可读性评分）。

**技术亮点**:
- **基于 Claude Code 与 Anthropic API**：核心运行环境。
- **Python 数据分析栈**：依赖 `nltk`、`textstat`、`scikit-learn`、`beautifulsoup4` 等库进行 NLP 处理和网页分析。
- **上下文驱动**：通过可定制的品牌声音、风格指南、SEO 指南等上下文文件，确保内容符合品牌调性。

---
## 3. [KeygraphHQ/shannon](https://github.com/KeygraphHQ/shannon)
- **语言**: TypeScript
- **Stars**: 31,834
- **简介**: Shannon Lite is a fully autonomous AI pentester for web apps and APIs. 96.15% (100/104 exploits) on a hint-free, source-aware variant of the XBOW benchmark.

### AI 总结
**简介**: Shannon 是一个由 Keygraph 开发的全自动、白盒 AI 渗透测试工具，用于对 Web 应用和 API 进行源代码分析和实时漏洞利用验证。

**核心功能**:
- **全自动操作**：单条命令即可启动完整渗透测试，自动处理登录、浏览器导航、漏洞利用和报告生成。
- **可复现的漏洞验证**：最终报告仅包含已通过实际利用验证的漏洞，并提供可直接复现的证明。
- **代码感知的动态测试**：结合源代码分析来指导攻击策略，并通过浏览器和 CLI 工具对运行中的应用进行实时漏洞验证。
- **集成安全工具**：在侦察和发现阶段利用 Nmap、Subfinder 等工具。
- **并行处理**：支持跨所有攻击类别并行进行漏洞分析和利用。

**技术亮点**: 基于 TypeScript 开发，采用白盒测试架构，支持与 Claude (AWS Bedrock/Google Vertex AI) 等 AI 模型集成，并分为开源版 (Shannon Lite, AGPL-3.0) 和商业版 (Shannon Pro) 两个产品线。

---
## 4. [aquasecurity/trivy](https://github.com/aquasecurity/trivy)
- **语言**: Go
- **Stars**: 32,891
- **简介**: Find vulnerabilities, misconfigurations, secrets, SBOM in containers, Kubernetes, code repositories, clouds and more

### AI 总结
**简介**: Trivy 是一个用 Go 编写的综合性安全扫描器，用于在容器、Kubernetes、代码仓库和云环境中发现漏洞、错误配置、密钥和软件物料清单 (SBOM)。

**核心功能**:
- **支持多种扫描目标**：容器镜像、文件系统、Git 仓库、虚拟机镜像和 Kubernetes 集群。
- **提供多种安全扫描**：检测操作系统包和软件依赖 (SBOM)、已知漏洞 (CVE)、基础设施即代码 (IaC) 问题与错误配置、敏感信息和密钥，以及软件许可证。

**技术亮点**:
- 采用 Go 语言开发，具有良好的性能和跨平台支持。
- 提供多种安装方式（如 Homebrew、Docker、二进制文件）和丰富的集成生态（如 GitHub Actions、Kubernetes Operator、VS Code 插件）。
- 支持通过 Canary 构建进行持续集成和测试。

---
## 5. [moeru-ai/airi](https://github.com/moeru-ai/airi)
- **语言**: TypeScript
- **Stars**: 27,470
- **简介**: 💖🧸 Self hosted, you-owned Grok Companion, a container of souls of waifu, cyber livings to bring them into our worlds, wishing to achieve Neuro-sama's altitude. Capable of realtime voice chat, Minecraft, Factorio playing. Web / macOS / Windows supported.

### AI 总结
**简介**: AIRI 是一个自托管、用户拥有的 AI 伴侣/虚拟角色容器项目，旨在将赛博生命体（如虚拟女友、数字宠物）带入现实世界，其灵感来源于 Neuro-sama。

**核心功能**:
- 支持实时语音聊天。
- 能够与用户互动并游玩《我的世界》、《异星工厂》等游戏。
- 提供 Web、macOS 和 Windows 客户端。

**技术亮点**: 项目基于 TypeScript 开发，并利用现代大语言模型（如 ChatGPT、Claude）的能力，拥有一个专门的组织用于管理其衍生的子项目，包括 RAG、记忆系统、嵌入式数据库、Live2D 工具等。

---
## 6. [inclusionAI/AReaL](https://github.com/inclusionAI/AReaL)
- **语言**: Python
- **Stars**: 4,102
- **简介**: Lightning-Fast RL for LLM Reasoning and Agents. Made Simple & Flexible.

### AI 总结
**简介**: AReaL 是一个开源、完全异步的大规模强化学习训练系统，专为大型推理模型和智能体设计，旨在帮助用户轻松、经济地构建自己的AI智能体。

**核心功能**:
- 支持智能体强化学习和在线RL训练，可通过简单替换 `base_url` 实现无缝定制。
- 提供稳定、完全异步的RL训练，具备行业领先的训练速度。
- 提供前沿性能的智能体，覆盖数学、代码、搜索和客服等多个领域。

**技术亮点**: 基于开源项目 ReaLHF 构建，采用完全异步的架构，支持在昇腾NPU设备上运行，并提供了轻量化的 AReaL-lite 版本以方便研究和快速原型开发。

---
## 7. [microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners)
- **语言**: Jupyter Notebook
- **Stars**: 14,930
- **简介**: This open-source curriculum introduces the fundamentals of Model Context Protocol (MCP) through real-world, cross-language examples in .NET, Java, TypeScript, JavaScript, Rust and Python. Designed for developers, it focuses on practical techniques for building modular, scalable, and secure AI workflows from session setup to service orchestration.

### AI 总结
**简介**: 这是一个由微软推出的开源入门课程，旨在通过 .NET、Java、TypeScript、JavaScript、Rust 和 Python 等多语言的实际案例，教授开发者如何构建模块化、可扩展且安全的 AI 工作流。

**核心功能**:
- 提供关于模型上下文协议（MCP）基础知识的实践性课程。
- 包含从会话设置到服务编排的完整 AI 工作流构建技术。
- 课程内容以 Jupyter Notebook 形式呈现，便于学习和实验。

**技术亮点**:
- **多语言支持**: 课程示例涵盖 .NET、Java、TypeScript、JavaScript、Rust 和 Python 等多种主流编程语言。
- **国际化**: 通过 GitHub Action 自动化维护，提供超过 50 种语言的翻译版本。
- **高效协作**: 项目鼓励社区贡献，提供了清晰的 Fork、Clone 指引，并设有 Discord 社区供开发者交流。

---
## 8. [CodebuffAI/codebuff](https://github.com/CodebuffAI/codebuff)
- **语言**: TypeScript
- **Stars**: 3,878
- **简介**: Generate code from the terminal!

### AI 总结
**简介**: Codebuff 是一个开源的 AI 代码助手，能通过自然语言指令理解和编辑你的代码库。

**核心功能**:
- **多智能体协作**: 通过协调文件选择、规划、编辑和审查等专门智能体，协同理解项目并进行精确修改。
- **终端操作**: 提供 CLI 工具，安装后可直接在项目目录中通过自然语言指令执行复杂编码任务（如修复漏洞、添加功能）。
- **自定义智能体**: 支持开发者通过 TypeScript 定义文件创建和定制自己的智能体工作流，实现程序化控制。
- **生产级 SDK**: 提供独立的 SDK 包，允许在应用程序中集成并运行智能体。

**技术亮点**: 采用基于 TypeScript 的多智能体架构，支持通过 OpenRouter 调用多种大语言模型（如 Claude、GPT、Qwen 等），而非绑定单一供应商。

---
## 9. [FujiwaraChoki/MoneyPrinterV2](https://github.com/FujiwaraChoki/MoneyPrinterV2)
- **语言**: Python
- **Stars**: 14,713
- **简介**: Automate the process of making money online.

### AI 总结
**简介**: MoneyPrinterV2 是一个用于自动化在线赚钱流程的 Python 应用程序，是原项目的完全重写版。

**核心功能**:
- Twitter 机器人（支持定时任务调度）
- YouTube Shorts 自动化（支持定时任务调度）
- 联盟营销（亚马逊 + Twitter）
- 寻找本地企业并进行冷接触

**技术亮点**: 采用模块化架构，需要 Python 3.12 运行，社区提供了多语言版本（如中文版 MoneyPrinterTurbo）。

---
## 10. [agentscope-ai/ReMe](https://github.com/agentscope-ai/ReMe)
- **语言**: Python
- **Stars**: 1,831
- **简介**: ReMe: Memory Management Kit for Agents - Remember Me, Refine Me.

### AI 总结
**简介**: ReMe 是一个专为 AI 智能体设计的记忆管理框架，旨在解决智能体在长对话中上下文窗口有限和历史会话无法继承的问题。

**核心功能**:
- **文件式记忆系统 (ReMeLight)**：将记忆以可读、可编辑的 Markdown 文件形式存储，便于管理和迁移。
- **向量式记忆系统**：支持基于向量的语义记忆搜索，实现混合检索。
- **记忆压缩与摘要**：自动压缩历史对话为摘要，并将重要信息持久化到文件中。
- **工具结果管理**：自动处理和管理过大的工具输出结果，进行压缩和缓存清理。

**技术亮点**: 采用文件与向量双存储系统，集成了 ReActAgent 进行结构化摘要生成，并支持 BM25 与向量混合检索，实现了可感知上下文的 Token 管理。

---
