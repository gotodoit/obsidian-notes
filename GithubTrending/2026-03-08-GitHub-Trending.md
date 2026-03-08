---
tags:
  - github-trending
  - daily
date: 2026-03-08
created: 2026-03-08T01:55:49.631Z
---

# 2026-03-08 GitHub Trending Top 10

## 1. [666ghj/MiroFish](https://github.com/666ghj/MiroFish)
- **语言**: Python
- **Stars**: 5,694
- **简介**: A Simple and Universal Swarm Intelligence Engine, Predicting Anything. 简洁通用的群体智能引擎，预测万物

### AI 总结
**简介**: MiroFish 是一个基于多智能体技术的群体智能引擎，旨在通过构建高保真的平行数字世界来模拟和预测未来事件。

**核心功能**:
- **平行世界构建**: 从现实世界的种子信息（如新闻、政策、金融信号）出发，自动构建包含成千上万具备独立人格、记忆和行为逻辑的智能体的数字世界。
- **交互与推演**: 用户可以从“上帝视角”动态注入变量，观察智能体在数字世界中的自由交互与社会演化，从而推演未来走向。
- **预测报告生成**: 用户只需上传种子材料并用自然语言描述预测需求，系统即可生成详尽的预测报告，并提供可深度交互的数字世界。
- **多场景应用**: 支持从严肃的宏观决策（如政策、公关模拟）到微观的个人创意（如小说结局推演）等多种预测和仿真场景。

**技术亮点**:
- **多智能体架构**: 核心基于具备长期记忆和行为逻辑的智能体进行社会演化模拟。
- **GraphRAG 技术**: 用于知识图谱构建和记忆管理，支撑高保真世界的创建。
- **双平台并行模拟**: 系统支持并行模拟，能够动态解析需求并更新时序记忆。
- **现代化技术栈**: 项目使用 Python (≥3.11, ≤3.12) 作为后端，Node.js (18+) 作为前端，并采用 `uv` 作为 Python 包管理器，支持 Docker 容器化部署。

---
## 2. [openai/skills](https://github.com/openai/skills)
- **语言**: Python
- **Stars**: 12,734
- **简介**: Skills Catalog for Codex

### AI 总结
**简介**: OpenAI 的 Codex AI 代理的技能目录，包含可复用的指令、脚本和资源包，用于帮助团队和个人完成特定任务。

**核心功能**:
- 提供预构建的技能目录，包含系统、精选和实验性技能。
- 支持通过 `$skill-installer` 命令在 Codex 中便捷地安装技能。
- 遵循 Agent Skills 开放标准，实现“一次编写，随处使用”。

**技术亮点**: 基于 Python，采用模块化的技能文件夹结构，每个技能包含独立的许可证和资源。

---
## 3. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 10,797
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个包含多种专业 AI 代理角色的集合，旨在通过具备独特个性和工作流程的专家级 AI 助手来提升各类工作流程的效率。

**核心功能**:
- 提供涵盖工程、设计、营销等多个领域的专业化 AI 代理，如前端开发、后端架构、UI 设计、社区运营等。
- 每个代理都具备明确的专业领域、个性特质、工作流程和可交付成果。
- 支持快速集成到 Claude Code 环境中使用，或作为独立的参考模板进行复制和适配。

**技术亮点**: 项目以 Shell 脚本组织，核心是精心设计的提示词（Prompt）模板，定义了每个代理的身份、任务和交互方式，便于在支持 AI 助手的开发环境中直接部署和调用。

---
## 4. [GoogleCloudPlatform/generative-ai](https://github.com/GoogleCloudPlatform/generative-ai)
- **语言**: Jupyter Notebook
- **Stars**: 13,551
- **简介**: Sample code and notebooks for Generative AI on Google Cloud, with Gemini on Vertex AI

### AI 总结
**简介**: 这是一个由 Google Cloud 官方维护的示例代码和 Jupyter Notebook 仓库，旨在展示如何在 Google Cloud 上使用 Vertex AI 和 Gemini 等模型进行生成式 AI 开发。

**核心功能**:
- 提供 Gemini 模型（包括最新的 Gemini 3.1 Pro）的入门教程、用例演示、函数调用和示例应用。
- 涵盖 Vertex AI Search（企业搜索）、检索增强生成（RAG）与信息溯源（Grounding）等主题。
- 包含使用 Vertex AI Imagen API（图像生成与编辑）和 Vertex AI Chirp API（语音处理）构建解决方案的示例。
- 提供 Google Cloud 环境、Vertex AI Python SDK 以及 Colab 和 Vertex AI Workbench 笔记本环境的设置指南。

**技术亮点**: 专注于 Google Cloud 的生成式 AI 全栈技术，核心围绕 Vertex AI 平台及其集成的 Gemini、Imagen、Chirp 等先进模型，并提供从环境配置到生产级应用（如智能体）的完整学习路径。

---
## 5. [agentjido/jido](https://github.com/agentjido/jido)
- **语言**: Elixir
- **Stars**: 1,426
- **简介**: 🤖 Autonomous agent framework for Elixir. Built for distributed, autonomous behavior and dynamic workflows.

### AI 总结
**简介**: Jido 是一个用 Elixir 语言编写的自主智能体框架，专注于构建分布式、自主行为且支持动态工作流的多智能体系统。

**核心功能**:
- **纯函数式智能体架构**: 智能体为不可变数据结构，通过 `cmd/2` 函数处理动作，实现状态转换与指令生成。
- **基于指令的副作用管理**: 将外部副作用（如网络请求、进程创建）抽象为明确的指令，由 OTP 运行时统一执行。
- **OTP 运行时集成**: 基于 GenServer 提供生产级部署支持，内置智能体父子层次结构与生命周期管理。
- **可组合的插件系统**: 支持通过能力模块扩展智能体功能，实现状态隔离与自动模式合并。
- **多智能体编排**: 提供直接执行、有限状态机等多种执行策略，支持复杂工作流的规划与协调。

**技术亮点**: 采用纯函数式设计（灵感源于 Elm/Redux）与 OTP 运行时相结合，在 Elixir/Erlang 生态中形式化了智能体模式，实现了业务逻辑与副作用分离、确定性测试以及清晰的生产部署路径。

---
## 6. [QwenLM/Qwen-Agent](https://github.com/QwenLM/Qwen-Agent)
- **语言**: Python
- **Stars**: 15,035
- **简介**: Agent framework and applications built upon Qwen>=3.0, featuring Function Calling, MCP, Code Interpreter, RAG, Chrome extension, etc.

### AI 总结
**简介**: Qwen-Agent 是一个基于通义千问大模型（Qwen>=3.0）构建的智能体（Agent）框架和应用集合，旨在开发具备指令遵循、工具使用、规划和记忆能力的LLM应用。

**核心功能**:
- **智能体框架**：提供基于Qwen大模型的指令遵循、工具调用、规划和记忆能力开发框架。
- **多样化应用示例**：内置浏览器助手、代码解释器（Code Interpreter）、自定义助手等多种示例应用。
- **工具与集成**：支持函数调用（Function Calling）、模型上下文协议（MCP）、检索增强生成（RAG）等关键功能。
- **便捷部署**：支持通过阿里云灵积（DashScope）API或本地部署开源Qwen模型（如通过vLLM、Ollama）来使用模型服务。

**技术亮点**:
- **模块化与可扩展**：通过可选依赖（如 `[gui]`, `[rag]`）灵活支持Gradio GUI、RAG、代码解释器等高级功能。
- **生产级后端**：作为官方[Qwen Chat](https://chat.qwen.ai/)的后端，具备实际应用验证。
- **持续更新**：紧密跟进Qwen模型系列（如Qwen3.5、QwQ-32B）并集成其最新特性（如并行多步工具调用、视觉工具调用）。

---
## 7. [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund)
- **语言**: Python
- **Stars**: 46,586
- **简介**: An AI Hedge Fund Team

### AI 总结
**简介**: 一个用于教育目的的概念验证项目，旨在探索利用多智能体协作的AI系统进行投资决策，不进行真实交易。

**核心功能**:
- 集成了18个不同投资风格的AI智能体（如价值投资、成长投资、宏观交易等）协同工作，模拟专业对冲基金团队。
- 提供命令行界面和Web应用两种运行方式，支持对指定股票代码进行分析并生成交易信号。
- 支持多种大语言模型API（如OpenAI、Groq等），并可选择使用本地Ollama模型运行。

**技术亮点**:
- 采用Python开发，使用Poetry进行依赖管理。
- 架构上实现了模块化的智能体系统，包括估值、基本面、技术面、情绪分析、风险管理和投资组合管理等专门角色。

---
## 8. [microsoft/hve-core](https://github.com/microsoft/hve-core)
- **语言**: PowerShell
- **Stars**: 756
- **简介**: A refined collection of Hypervelocity Engineering components (instructions, prompts, agents, and skills) to start your project off right, or upgrade your existing projects to get the most out of all Copilots

### AI 总结
**简介**: HVE Core 是一个由微软推出的企业级提示工程框架，旨在通过约束式AI工作流和结构化方法，帮助开发者（从个人到大型团队）更高效地利用 GitHub Copilot 进行开发。

**核心功能**:
- 提供一套包含专用智能体（Agents）、可复用提示（Prompts）、指令集（Instructions）和技能包（Skills）的完整组件库。
- 采用 RPI（研究→规划→实现）方法论，将复杂工程任务分解为不同阶段，引导AI生成经过验证的可靠产出。
- 支持通过 VS Code 扩展或 Copilot CLI 插件快速安装和集成。

**技术亮点**: 采用约束式AI工作流设计，通过JSON模式验证和清晰的职责边界来防止AI行为失控，将优化目标从“看似合理的代码”转向“经过验证的真相”。

---
## 9. [toeverything/AFFiNE](https://github.com/toeverything/AFFiNE)
- **语言**: TypeScript
- **Stars**: 64,713
- **简介**: There can be more than Notion and Miro. AFFiNE(pronounced [ə‘fain]) is a next-gen knowledge base that brings planning, sorting and creating all together. Privacy first, open-source, customizable and ready to use.

### AI 总结
**简介**: AFFiNE 是一个注重隐私、本地优先的开源知识库与协作平台，集成了文档、白板和表格功能，旨在成为 Notion 和 Miro 的融合替代品。

**核心功能**:
- **融合画布**: 将文档、白板与表格深度融合，支持在无边画布上自由放置富文本、便签、网页嵌入、多视图数据库、形状和幻灯片等多种模块。
- **多模态 AI 助手**: 集成 AI 功能，可辅助生成工作报告、幻灯片、思维导图，甚至直接绘制和编码原型。
- **本地优先与实时协作**: 数据默认存储在本地，同时支持云端实时同步和跨平台协作。
- **自托管与高度可定制**: 支持自行部署和管理，未来将开放插件社区和第三方模块。

**技术亮点**: 基于 TypeScript 开发，采用“模块化”架构（受 Blocksuite 启发），强调本地优先的数据处理与实时同步能力。

---
## 10. [shadcn-ui/ui](https://github.com/shadcn-ui/ui)
- **语言**: TypeScript
- **Stars**: 108,193
- **简介**: A set of beautifully-designed, accessible components and a code distribution platform. Works with your favorite frameworks. Open Source. Open Code.

### AI 总结
**简介**: 一个设计精美、可访问的开源组件库，支持自定义和扩展，可用于构建自己的组件库。

**核心功能**:
- 提供一系列设计精美的 UI 组件
- 支持自定义、扩展和二次开发
- 可与多种流行前端框架配合使用

**技术亮点**: 基于 TypeScript 开发，采用开放代码模式，允许开发者直接使用和修改源代码。

---
