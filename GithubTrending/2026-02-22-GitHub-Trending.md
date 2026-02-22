---
tags:
  - github-trending
  - daily
date: 2026-02-22
created: 2026-02-22T01:55:46.267Z
---

# 2026-02-22 GitHub Trending Top 10

## 1. [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi)
- **语言**: Go
- **Stars**: 5,616
- **简介**: ✨ Fully autonomous AI Agents system capable of performing complex penetration testing tasks

### AI 总结
**简介**: PentAGI 是一个基于人工智能、能够自主执行复杂渗透测试任务的全自动安全测试系统。

**核心功能**:
- **全自主AI代理**: 由AI驱动，能自动决策并执行渗透测试步骤。
- **专业工具集成**: 内置超过20种专业安全工具（如nmap、metasploit、sqlmap）。
- **智能记忆与知识图谱**: 具备长期存储研究结果的能力，并集成Neo4j知识图谱以追踪语义关系。
- **全面的信息收集**: 集成内置浏览器和多种外部搜索系统（如Tavily、Google、DuckDuckGo）进行情报搜集。
- **团队协作与监控**: 支持任务委派给专业化AI代理，并提供详细的日志记录与Grafana/Prometheus监控。
- **详细报告生成**: 可生成包含漏洞利用指南的全面报告。

**技术亮点**:
- **微服务架构**: 采用基于Docker的沙盒隔离环境，支持水平扩展。
- **灵活的后端与AI支持**: 使用PostgreSQL（含pgvector扩展）进行持久化存储，并支持多种LLM提供商（如OpenAI、Anthropic、Ollama、AWS Bedrock等）。
- **现代化接口与API**: 提供直观的Web UI，以及完整的REST和GraphQL API（支持Bearer令牌认证）。
- **自托管部署**: 可通过Docker Compose快速部署，用户对数据和部署拥有完全控制权。

---
## 2. [abhigyanpatwari/GitNexus](https://github.com/abhigyanpatwari/GitNexus)
- **语言**: TypeScript
- **Stars**: 1,055
- **简介**: GitNexus: The Zero-Server Code Intelligence Engine - GitNexus is a client-side knowledge graph creator that runs entirely in your browser. Drop in a GitHub repo or ZIP file, and get an interactive knowledge graph wit a built in Graph RAG Agent. Perfect for code exploration

### AI 总结
**简介**: GitNexus 是一个完全在浏览器或本地运行的零服务器代码智能引擎，可将任何代码库索引为知识图谱，并通过智能工具（如MCP服务器和Web UI）为AI智能体提供深度的代码上下文。

**核心功能**:
- **代码库索引与分析**：将代码库（GitHub仓库或ZIP文件）转换为包含依赖、调用链、集群和执行流的交互式知识图谱。
- **AI智能体集成**：通过MCP（模型上下文协议）服务器为Cursor、Claude Code等AI编码助手提供深度代码感知能力，避免其遗漏依赖或破坏调用链。
- **双模式使用**：提供CLI+MCP模式用于日常开发，以及基于浏览器的Web UI用于快速探索和可视化分析。
- **隐私与本地化**：所有处理均在本地或浏览器内完成，无需网络连接或服务器，保障代码隐私。

**技术亮点**:
- 使用**KuzuDB**（本地或WASM版本）作为高性能图数据库存储知识图谱。
- 集成**Tree-sitter**（原生或WASM）进行精准的代码解析。
- 通过**MCP协议**与主流AI编辑器深度集成，并为Claude Code提供自动增强的PreToolUse钩子。

---
## 3. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 57,031
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个基于可组合“技能”和初始指令构建的、面向编码智能体的完整软件开发工作流框架。

**核心功能**:
- **智能规划与设计**：通过对话引导用户明确需求，并生成易于审阅和批准的设计文档与详细实施计划。
- **子智能体驱动开发**：将任务分解为小单元，由独立的子智能体执行，并自动进行两阶段代码审查（规范符合性与代码质量）。
- **强制执行最佳实践**：内置技能强制实施真正的红/绿测试驱动开发、YAGNI和DRY原则，确保代码质量。
- **自动化工作流管理**：涵盖从头脑风暴、Git工作区管理、计划执行到代码审查和分支收尾的完整开发周期。

**技术亮点**: 采用基于技能的插件化架构，技能在相关任务前自动触发，无缝集成于 Claude Code、Cursor、Codex 和 OpenCode 等多种AI编码平台。

---
## 4. [huggingface/skills](https://github.com/huggingface/skills)
- **语言**: Python
- **Stars**: 1,694
- **简介**: 

### AI 总结
**简介**: Hugging Face Skills 是一个为 AI/ML 任务（如数据集创建、模型训练和评估）提供标准化定义的项目，旨在与主流 AI 编码代理工具（如 OpenAI Codex、Claude Code、Gemini CLI 和 Cursor）实现互操作。

**核心功能**:
- 提供一系列自包含的“技能”文件夹，每个技能包含任务指令、脚本和资源，供 AI 代理执行特定用例。
- 支持通过统一的格式（如 `SKILL.md`、`AGENTS.md`、`gemini-extension.json`）与多种编码代理工具集成。
- 包含多个开箱即用的技能，涵盖 Hugging Face Hub 的 CLI 操作、数据集管理、模型训练、评估、论文发布等核心 ML 工作流。

**技术亮点**:
- 遵循标准化的 [Agent Skill](https://agentskills.io/home) 格式，确保跨工具兼容性。
- 通过单一代码库同时支持 Claude Code、OpenAI Codex、Google Gemini CLI 和 Cursor 等多种代理生态。
- 提供自动化脚本（如 `./scripts/publish.sh`）来生成和维护不同代理所需的清单文件。

---
## 5. [PowerShell/PowerShell](https://github.com/PowerShell/PowerShell)
- **语言**: C#
- **Stars**: 51,554
- **简介**: PowerShell for every system!

### AI 总结
**简介**: PowerShell 是一个跨平台（Windows、Linux、macOS）的自动化与配置工具/框架，包含命令行外壳、脚本语言和处理 cmdlet 的框架。

**核心功能**:
- 跨平台自动化与配置管理
- 优化处理结构化数据（如 JSON、CSV、XML）
- 集成 REST API 和对象模型
- 提供命令行 shell 和脚本语言

**技术亮点**: 基于 .NET Core C# 开发，支持多平台，提供 PowerShell SDK NuGet 包，采用 MIT 开源协议。

---
## 6. [anthropics/claude-code](https://github.com/anthropics/claude-code)
- **语言**: Shell
- **Stars**: 68,432
- **简介**: Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands.

### AI 总结
**简介**: Claude Code 是一个基于终端的智能编程助手，通过自然语言命令帮助开发者理解代码库、执行常规任务并处理 Git 工作流。

**核心功能**:
- 通过自然语言命令执行常规编码任务
- 解释复杂代码段
- 处理 Git 工作流

**技术亮点**: 支持多平台安装（MacOS/Linux/Windows），提供插件系统扩展功能，集成数据收集与隐私保护机制。

---
## 7. [stan-smith/FossFLOW](https://github.com/stan-smith/FossFLOW)
- **语言**: TypeScript
- **Stars**: 17,790
- **简介**: Make beautiful isometric infrastructure diagrams

### AI 总结
**简介**: FossFLOW 是一个基于 TypeScript 和 React 的开源等距图表绘制工具，支持在线使用和本地部署。

**核心功能**:
- 通过拖放组件和连接工具，轻松创建美观的等距基础设施图。
- 提供完整的离线支持，可作为渐进式 Web 应用在浏览器中运行。
- 支持通过 Docker 快速部署，并默认启用服务器端存储以持久化图表。

**技术亮点**:
- 采用 Monorepo 结构，包含独立的组件库和应用包。
- 基于 React 和 Isoflow 库构建，并已分叉发布为 NPM 包。
- 提供丰富的开发命令，支持库与应用分别构建、测试及发布。

---
## 8. [ggml-org/ggml](https://github.com/ggml-org/ggml)
- **语言**: C++
- **Stars**: 14,067
- **简介**: Tensor library for machine learning

### AI 总结
**简介**: 一个用 C++ 编写的、专注于机器学习的轻量级张量库。

**核心功能**:
- 提供低层级的跨平台实现。
- 支持整数量化。
- 内置自动微分功能。
- 包含 ADAM 和 L-BFGS 优化器。

**技术亮点**:
- **无第三方依赖**：项目自包含，简化部署。
- **运行时零内存分配**：优化性能，减少开销。
- **广泛的硬件支持**：支持 CUDA、hipBLAS (AMD) 和 SYCL (Intel) 进行加速，并可编译至 Android 平台。

---
## 9. [Stremio/stremio-web](https://github.com/Stremio/stremio-web)
- **语言**: JavaScript
- **Stars**: 9,465
- **简介**: Stremio - Freedom to Stream

### AI 总结
**简介**: Stremio 是一个现代化的媒体中心，通过可安装的插件为用户提供一站式视频娱乐解决方案。

**核心功能**:
- 发现、观看和组织来自各种插件的视频内容
- 提供看板、发现和元数据详情等直观界面

**技术亮点**: 基于 JavaScript 开发，使用 Node.js 和 npm 进行构建和依赖管理，支持开发服务器和产品级构建。

---
## 10. [HandsOnLLM/Hands-On-Large-Language-Models](https://github.com/HandsOnLLM/Hands-On-Large-Language-Models)
- **语言**: Jupyter Notebook
- **Stars**: 22,578
- **简介**: Official code repo for the O'Reilly Book - "Hands-On Large Language Models"

### AI 总结
**简介**: 这是 O'Reilly 书籍《Hands-On Large Language Models》（也被作者戏称为“图解 LLM 书”）的官方代码仓库，旨在通过大量可视化图表和代码示例，帮助读者学习和实践大语言模型。

**核心功能**:
- 提供与书籍章节完全对应的 Jupyter Notebook 代码示例，涵盖从语言模型基础到高级应用的完整学习路径。
- 所有代码示例均针对 Google Colab 环境优化，支持免费使用 T4 GPU，便于快速上手和实验。

**技术亮点**: 项目以 Jupyter Notebook 为主要形式，内容覆盖大语言模型的核心技术栈，包括 Transformer 架构、分词与嵌入、文本分类、聚类、主题建模及提示工程等。

---
