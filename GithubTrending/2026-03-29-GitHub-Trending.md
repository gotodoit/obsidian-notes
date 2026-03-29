---
tags:
  - github-trending
  - daily
date: 2026-03-29
created: 2026-03-29T01:55:46.905Z
---

# 2026-03-29 GitHub Trending Top 9

## 1. [hacksider/Deep-Live-Cam](https://github.com/hacksider/Deep-Live-Cam)
- **语言**: Python
- **Stars**: 84,359
- **简介**: real time face swap and one-click video deepfake with only a single image

### AI 总结
**简介**: Deep-Live-Cam 是一个基于 Python 的实时人脸替换与视频深度伪造工具，仅需单张图片即可一键生成。

**核心功能**:
- **实时人脸替换**: 支持通过摄像头或视频流进行实时换脸。
- **一键视频深度伪造**: 仅需一张目标人脸图片，即可快速生成换脸视频。
- **多功能应用场景**: 支持口型遮罩（保留原始嘴部动作）、多目标同时换脸、实时电影换脸、直播表演、制作表情包以及在 Omegle 等平台使用。
- **内置内容审核**: 包含防止处理不当内容（如裸露、暴力等）的检查机制。

**技术亮点**: 项目基于 ONNX 模型（如 GFPGAN、inswapper），支持 CPU、NVIDIA/AMD GPU 以及 Mac Silicon 平台，并提供预编译版本以简化非技术用户的部署流程。

---
## 2. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 120,839
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个基于可组合“技能”的智能体技能框架和软件开发方法论，旨在为编码智能体提供完整的工作流。

**核心功能**:
- **智能规划与设计**：在编码前通过对话提炼需求，分块展示设计供确认，并制定详细的实现计划。
- **子智能体驱动开发**：通过启动子智能体来执行工程任务，并自动进行审查和检查，支持长时间自主工作。
- **强制执行TDD**：在实现过程中强制进行红-绿-重构的测试驱动开发循环。
- **自动化代码审查**：在任务间自动请求代码审查，并根据严重性问题报告。
- **分支与工作区管理**：在批准设计后自动创建隔离的工作区和分支，并在开发完成后进行清理。

**技术亮点**: 基于可组合的“技能”库，技能在相关任务前自动触发，形成强制性的工作流（如系统化调试、TDD），而非建议。支持多种AI编码平台（如Claude Code、Cursor、Codex、OpenCode、Gemini CLI）。

---
## 3. [SakanaAI/AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2)
- **语言**: Python
- **Stars**: 3,489
- **简介**: The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search

### AI 总结
**简介**: AI Scientist-v2 是一个端到端的自主科研代理系统，能够通过智能体树搜索自动生成假设、运行实验、分析数据并撰写科学论文。

**核心功能**:
- **自主科研流程**: 全流程自动化，涵盖从研究想法生成、实验设计、数据分析到论文撰写的完整科研周期。
- **跨领域探索**: 不依赖人工模板，可泛化应用于机器学习等多个领域，进行开放式科学探索。
- **智能体树搜索**: 采用渐进式智能体树搜索策略，由一个实验管理智能体进行引导和协调。

**技术亮点**:
- **多模型支持**: 支持 OpenAI、Gemini 及通过 AWS Bedrock 调用的 Claude 等大型语言模型。
- **集成外部工具**: 可选集成 Semantic Scholar API 进行文献检索以提升研究新颖性。
- **安全警告**: 代码会执行由 LLM 生成的代码，存在安全风险，必须在受控的沙箱环境（如 Docker 容器）中运行。

---
## 4. [virattt/dexter](https://github.com/virattt/dexter)
- **语言**: TypeScript
- **Stars**: 20,219
- **简介**: An autonomous agent for deep financial research

### AI 总结
**简介**: Dexter 是一个用于深度金融研究的自主智能体，能够通过任务规划、自我反思和实时市场数据进行分析。

**核心功能**:
- **智能任务规划**：自动将复杂的金融问题分解为结构化的研究步骤。
- **自主执行与验证**：选择并执行工具以收集金融数据，同时检查自身工作并进行迭代优化。
- **实时金融数据访问**：获取收入报表、资产负债表和现金流量表等市场数据。
- **安全特性**：内置循环检测和步骤限制，防止执行失控。

**技术亮点**: 基于 TypeScript 开发，使用 Bun 运行时，支持 OpenAI、Anthropic 等多种大语言模型 API，并集成 Financial Datasets、Exa 等数据源，提供完整的评估和调试工具链。

---
## 5. [twentyhq/twenty](https://github.com/twentyhq/twenty)
- **语言**: TypeScript
- **Stars**: 42,447
- **简介**: Building a modern alternative to Salesforce, powered by the community.

### AI 总结
**简介**: Twenty 是一个由社区驱动的开源 CRM，旨在构建一个现代化的 Salesforce 替代方案。

**核心功能**:
- 个性化布局：支持筛选、排序、分组、看板和表格视图
- 自定义对象和字段：灵活配置数据模型
- 权限管理：通过自定义角色创建和管理权限
- 工作流自动化：支持触发器和动作实现流程自动化
- 集成功能：支持邮件、日历事件、文件等

**技术亮点**: 基于 TypeScript 开发，支持自托管和本地部署，采用模块化设计，未来将支持插件生态系统。

---
## 6. [onyx-dot-app/onyx](https://github.com/onyx-dot-app/onyx)
- **语言**: Python
- **Stars**: 19,768
- **简介**: Open Source AI Platform - AI Chat with advanced features that works with every LLM

### AI 总结
**简介**: Onyx 是一个功能丰富、可自托管的开源 AI 平台，提供了一个能与任何大语言模型（LLM）协同工作的聊天界面。

**核心功能**:
- **自定义智能体**：可构建具有独特指令、知识和操作能力的 AI 代理。
- **网络搜索与深度研究**：支持多种搜索引擎，并能进行多步骤的深度研究。
- **RAG（检索增强生成）**：提供混合搜索和知识图谱，用于处理上传的文件和来自连接器的文档。
- **多源连接器**：可从超过 40 个应用程序中获取知识、元数据和访问信息。
- **代码解释器与图像生成**：支持执行代码分析数据，以及根据提示生成图像。
- **协作与管理**：包含聊天分享、用户管理、使用分析等功能。

**技术亮点**:
- **模型无关性**：兼容所有主流 LLM（如 OpenAI, Anthropic, Gemini）及自托管模型（如 Ollama, vLLM）。
- **灵活部署**：支持 Docker、Kubernetes、Terraform 等多种部署方式，并提供了主流云服务商的部署指南。
- **企业级特性**：具备企业级搜索、SSO/RBAC 安全控制、文档权限管理等高级功能，适合从个人到大型团队的各种规模使用。

---
## 7. [datalab-to/chandra](https://github.com/datalab-to/chandra)
- **语言**: Python
- **Stars**: 7,606
- **简介**: OCR model that handles complex tables, forms, handwriting with full layout.

### AI 总结
**简介**: Chandra OCR 2 是一个先进的 OCR 模型，能够将图像和 PDF 文档转换为结构化的 HTML、Markdown 或 JSON 格式，同时完整保留原始布局信息。

**核心功能**:
- 支持 90 多种语言的文档识别，在表格、数学公式、布局和文本准确性方面表现出色。
- 能够精确处理复杂表格、表单（包括复选框）、手写内容以及数学公式。
- 提供两种推理模式：本地运行（通过 HuggingFace）和远程服务（通过 vLLM 服务器）。
- 可将文档转换为 Markdown、HTML 或 JSON 格式，并提取图像、图表，添加标题和结构化数据。

**技术亮点**:
- 模型在公开的 olmocr 基准测试中表现优异，并在多语言内部基准测试上有显著提升。
- 提供便捷的 CLI 工具和交互式 Streamlit 应用，支持快速安装和部署。
- 采用 Apache 2.0 代码许可证和 OpenRAIL-M 模型许可证。

---
## 8. [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope)
- **语言**: Python
- **Stars**: 21,633
- **简介**: Build and run agents you can see, understand and trust.

### AI 总结
**简介**: AgentScope 是一个面向生产环境、易于使用的智能体（Agent）框架，旨在利用大语言模型不断增强的推理和工具使用能力来构建可理解、可信赖的智能体。

**核心功能**:
- **简单易用**：内置 ReAct 智能体、工具、技能、人机交互、记忆、规划、实时语音、评估和模型微调等功能，可快速上手。
- **高度可扩展**：拥有丰富的生态系统集成（工具、记忆、可观测性），内置支持 MCP 和 A2A 协议，并提供灵活的多智能体编排与工作流消息中心。
- **生产就绪**：支持本地部署、云端无服务器部署或 Kubernetes 集群部署，并内置 OpenTelemetry 支持。

**技术亮点**:
- 采用 Python 3.10+ 开发，遵循 Apache-2.0 开源协议。
- 设计理念强调利用模型自身能力，而非用严格的提示词和固执的编排来约束模型。
- 近期特性包括实时语音智能体、数据库支持与记忆压缩、A2A 协议、TTS 支持以及 Anthropic Agent Skill 集成。

---
## 9. [apache/superset](https://github.com/apache/superset)
- **语言**: TypeScript
- **Stars**: 71,478
- **简介**: Apache Superset is a Data Visualization and Data Exploration Platform

### AI 总结
**简介**: Apache Superset 是一个现代化的、企业级的开源商业智能（BI）与数据探索平台，用于快速构建数据可视化和仪表盘。

**核心功能**:
- 提供**无代码界面**，可快速构建图表。
- 内置强大的基于 Web 的 **SQL 编辑器**，支持高级查询。
- 拥有轻量级的**语义层**，可快速定义自定义维度和指标。
- 支持**几乎所有 SQL 数据库或数据引擎**。
- 提供丰富的**可视化图表库**，从基础图表到地理空间可视化。
- 具备可配置的**缓存层**以减轻数据库负载。
- 提供高度可扩展的**安全角色和身份验证**选项。
- 开放 **API** 以支持程序化定制。

**技术亮点**: 采用云原生架构设计，具备良好的可扩展性；主要使用 TypeScript 开发；项目在 Apache 2.0 许可证下开源，拥有活跃的社区和持续集成。

---
