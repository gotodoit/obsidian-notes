---
tags:
  - github-trending
  - daily
date: 2026-02-19
created: 2026-02-19T01:55:44.807Z
---

# 2026-02-19 GitHub Trending Top 10

## 1. [alibaba/zvec](https://github.com/alibaba/zvec)
- **语言**: C++
- **Stars**: 4,925
- **简介**: A lightweight, lightning-fast, in-process vector database

### AI 总结
**简介**: 由阿里巴巴开源的轻量级、超高速、进程内向量数据库，旨在直接嵌入应用程序，提供低延迟、可扩展的相似性搜索。

**核心功能**:
- **极速搜索**: 可在毫秒级时间内搜索数十亿向量。
- **简单易用**: 无需服务器或复杂配置，安装即可使用。
- **支持稠密与稀疏向量**: 原生支持单次调用中的多向量查询。
- **混合搜索**: 可结合语义相似性和结构化过滤器以获得精确结果。
- **随处运行**: 作为进程内库，可在笔记本、服务器、CLI工具乃至边缘设备中运行。

**技术亮点**: 基于阿里巴巴经过实战检验的向量搜索引擎 **Proxima** 构建，提供生产级性能。支持 Python 和 Node.js，可在 Linux (x86_64, ARM64) 和 macOS (ARM64) 平台上运行。

---
## 2. [p-e-w/heretic](https://github.com/p-e-w/heretic)
- **语言**: Python
- **Stars**: 8,050
- **简介**: Fully automatic censorship removal for language models

### AI 总结
**简介**: Heretic 是一个用于自动移除语言模型“安全对齐”（即审查）的工具，无需昂贵的后训练。

**核心功能**:
- 结合先进的“方向性消融”（abliteration）技术与基于Optuna的TPE参数优化器，实现完全自动化的模型去审查。
- 通过协同最小化模型的拒绝率和与原模型的KL散度，在移除审查的同时，尽可能保留原模型的智能和能力。
- 提供内置的模型评估功能，支持对去审查效果进行量化评估。

**技术亮点**: 采用基于Transformer架构的“方向性消融”（abliteration）技术，并集成Optuna进行超参数优化，支持大多数密集模型（包括多模态模型）和多种MoE架构。

---
## 3. [OpenCTI-Platform/opencti](https://github.com/OpenCTI-Platform/opencti)
- **语言**: TypeScript
- **Stars**: 8,703
- **简介**: Open Cyber Threat Intelligence Platform

### AI 总结
**简介**: OpenCTI 是一个开源的网络威胁情报平台，用于帮助组织构建、存储、组织和可视化网络威胁相关的技术与非技术信息。

**核心功能**:
- 基于 STIX2 标准结构化威胁情报数据，支持技术信息（如 TTPs、可观测指标）和非技术信息（如归因建议、受害者分析）的管理。
- 提供强大的数据关联能力，支持信息之间的链接、首次/末次发现时间、置信度等级等元数据管理。
- 支持与外部工具集成（如 MISP、TheHive、MITRE ATT&CK），并通过连接器实现数据自动导入导出（如 CSV、STIX2 格式）。
- 包含社区版（CE）和企业版（EE），企业版提供更多高级功能。

**技术亮点**:
- 采用现代 Web 应用架构，包含 GraphQL API 和用户体验导向的前端。
- 使用 TypeScript 开发，支持 Docker 容器化部署。
- 内置知识推理引擎，可从现有数据中自动推导新关系，提升情报分析效率。

---
## 4. [QwenLM/qwen-code](https://github.com/QwenLM/qwen-code)
- **语言**: TypeScript
- **Stars**: 18,851
- **简介**: An open-source AI agent that lives in your terminal.

### AI 总结
**简介**: 一个开源的、运行在终端中的AI智能体，专为代码理解和开发任务优化。

**核心功能**:
- **多协议支持与免费额度**：支持OpenAI、Anthropic、Gemini等兼容API，或通过通义千问OAuth登录获得每日1000次免费请求。
- **智能体工作流**：提供丰富的内置工具（技能、子智能体），实现完整的智能体工作流，提供类似Claude Code的体验。
- **终端优先，IDE友好**：专为命令行开发者设计，同时支持与VS Code、Zed和JetBrains IDE集成。

**技术亮点**:
- **开源协同演进**：框架与底层模型（Qwen3-Coder）均为开源，并协同发展和发布。
- **TypeScript开发**：项目使用TypeScript语言编写。
- **灵活的认证方式**：支持OAuth（推荐）和API-KEY两种认证方式，适配不同环境（如CI、容器）。

---
## 5. [NirDiamant/RAG_Techniques](https://github.com/NirDiamant/RAG_Techniques)
- **语言**: Jupyter Notebook
- **Stars**: 25,270
- **简介**: This repository showcases various advanced techniques for Retrieval-Augmented Generation (RAG) systems. RAG systems combine information retrieval with generative models to provide accurate and contextually rich responses.

### AI 总结
**简介**: 这是一个专注于展示检索增强生成（RAG）系统各种高级技巧的综合性教程资源库。

**核心功能**:
- 提供一系列前沿的 RAG 技术教程，旨在提升 RAG 系统的准确性、效率和上下文丰富度。
- 作为研究者和实践者的宝贵资源，旨在推动 RAG 领域的创新边界。

**技术亮点**: 项目内容以 Jupyter Notebook 形式呈现，便于学习和实践。

---
## 6. [harvard-edge/cs249r_book](https://github.com/harvard-edge/cs249r_book)
- **语言**: JavaScript
- **Stars**: 19,701
- **简介**: Introduction to Machine Learning Systems

### AI 总结
**简介**: 这是一个由哈佛大学推出的开源机器学习系统工程教科书项目，旨在教授如何设计、构建和评估端到端的智能系统。

**核心功能**:
- 提供完整的开源机器学习系统工程教科书，支持在线阅读和PDF/EPUB下载。
- 包含名为“TinyTorch”的实践框架，引导学习者从CNN到Transformer进行动手编码。
- 提供与Arduino、树莓派等边缘设备配套的硬件套件和实验，用于系统部署实践。
- 构建了一个从理论、概念、最佳实践到动手实验和实际部署的完整学习体系。

**技术亮点**: 项目采用开源学习栈模式，将教科书理论（JavaScript编写）、Python实践框架（TinyTorch）与边缘计算硬件实验紧密结合，并通过GitHub Actions实现持续的集成验证。

---
## 7. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 54,492
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为编码智能体构建的、基于可组合“技能”的软件开发工作流框架，旨在引导智能体进行系统化、高质量的开发。

**核心功能**:
- **引导式设计**：在编码前通过提问澄清需求，并分块呈现设计文档供用户确认。
- **结构化实施**：在批准设计后，制定详细的、面向初级工程师的、强调TDD/YAGNI/DRY原则的实施计划。
- **子智能体驱动开发**：启动子智能体流程，让智能体自主执行工程任务，并进行检查和评审，可长时间自主工作。
- **自动化技能触发**：内置多种技能（如头脑风暴、测试驱动开发、系统化调试、代码审查等），在相关任务前自动触发，强制执行标准化工作流。

**技术亮点**: 基于可组合的“技能”库构建，支持与 Claude Code、Cursor、Codex、OpenCode 等多种AI编码平台/工具集成，实现了“子智能体驱动开发”的自动化工作模式。

---
## 8. [HailToDodongo/pyrite64](https://github.com/HailToDodongo/pyrite64)
- **语言**: C++
- **Stars**: 1,303
- **简介**: N64 Game-Engine and Editor using libdragon & tiny3d

### AI 总结
**简介**: 一个基于 libdragon 和 tiny3d 的任天堂 N64 游戏引擎与编辑器。

**核心功能**:
- 提供用于 N64 开发的游戏引擎，支持 3D 图形渲染。
- 包含一个集成的编辑器，用于创建和编辑游戏内容。

**技术亮点**: 基于 libdragon（N64 开发库）和 tiny3d（3D 图形库）构建，专注于 N64 平台的游戏开发。

---
## 9. [ComposioHQ/composio](https://github.com/ComposioHQ/composio)
- **语言**: TypeScript
- **Stars**: 26,773
- **简介**: Composio powers 1000+ toolkits, tool search, context management, authentication, and a sandboxed workbench to help you build AI agents that turn intent into action.

### AI 总结
**简介**: Composio 是一个为AI智能体（Agent）提供强大工具集成能力的开发平台，通过SDK帮助开发者轻松构建能将意图转化为行动的AI应用。

**核心功能**:
- **丰富的工具集成**: 提供超过1000种工具包（toolkits），涵盖搜索、上下文管理、身份验证等功能。
- **多框架支持**: 提供TypeScript和Python两种官方SDK，并支持与OpenAI Agents、LangChain、LlamaIndex、Anthropic等多种主流AI框架和平台无缝集成。
- **沙盒工作台**: 提供一个沙盒化的工作环境，方便开发者测试和构建AI智能体。
- **简化开发流程**: 通过简单的API调用，即可为智能体获取并配置所需工具，快速实现与外部API（如HackerNews）的交互。

**技术亮点**: 采用TypeScript开发，提供类型安全的SDK；支持OpenAPI规范，便于生成和更新API文档；设计上同时兼容Node.js和浏览器环境。

---
## 10. [p2r3/convert](https://github.com/p2r3/convert)
- **语言**: TypeScript
- **Stars**: 1,464
- **简介**: Truly universal online file converter

### AI 总结
**简介**: 一个真正通用的在线文件转换工具，支持跨媒体格式转换，并注重用户隐私（文件在本地处理）。

**核心功能**:
- 支持广泛的跨媒体文件格式转换（例如，视频转文档）。
- 完全在浏览器本地运行，无需上传文件到服务器，保护隐私。
- 提供简单直观的Web界面，支持拖放文件操作。

**技术亮点**: 基于TypeScript开发，使用Bun和Vite进行本地开发，支持Docker部署，并利用Puppeteer（Chromium）处理复杂转换任务。

---
