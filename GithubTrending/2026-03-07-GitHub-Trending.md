---
tags:
  - github-trending
  - daily
date: 2026-03-07
created: 2026-03-07T01:55:50.845Z
---

# 2026-03-07 GitHub Trending Top 10

## 1. [moeru-ai/airi](https://github.com/moeru-ai/airi)
- **语言**: TypeScript
- **Stars**: 29,573
- **简介**: 💖🧸 Self hosted, you-owned Grok Companion, a container of souls of waifu, cyber livings to bring them into our worlds, wishing to achieve Neuro-sama's altitude. Capable of realtime voice chat, Minecraft, Factorio playing. Web / macOS / Windows supported.

### AI 总结
**简介**: AIRI 是一个自托管、用户所有的虚拟伴侣（AI 老婆/数字生命）容器项目，旨在复现 Neuro-sama，将虚拟角色带入现实世界。

**核心功能**:
- 支持实时语音聊天。
- 能够游玩 Minecraft、Factorio 等游戏。
- 提供 Web、macOS 和 Windows 客户端。

**技术亮点**: 项目使用 TypeScript 开发，并基于现代大语言模型（如 ChatGPT、Claude）构建，拥有一个专门的组织用于管理其衍生的子项目（如 RAG、记忆系统、嵌入式数据库等）。

---
## 2. [QwenLM/Qwen-Agent](https://github.com/QwenLM/Qwen-Agent)
- **语言**: Python
- **Stars**: 14,658
- **简介**: Agent framework and applications built upon Qwen>=3.0, featuring Function Calling, MCP, Code Interpreter, RAG, Chrome extension, etc.

### AI 总结
**简介**: Qwen-Agent 是一个基于通义千问大模型（Qwen>=3.0）构建的智能体（Agent）框架，旨在开发具备指令跟随、工具调用、规划和记忆能力的LLM应用。

**核心功能**:
- **智能体框架**：提供构建LLM应用的基础框架，支持函数调用（Function Calling）、规划、记忆等核心能力。
- **丰富应用示例**：内置浏览器助手、代码解释器（Code Interpreter）、自定义助手等多种示例应用。
- **多模态与工具集成**：支持视觉语言模型（如Qwen3-VL）进行图像分析、缩放、搜索等工具调用，并集成了RAG、MCP（Model Context Protocol）等技术。
- **灵活部署**：支持通过阿里云灵积（DashScope）API或本地部署（如vLLM、Ollama）开源Qwen模型来提供服务。

**技术亮点**:
- 支持**并行、多步、多轮次**的复杂工具调用。
- 提供**代码解释器**和**检索增强生成（RAG）** 等高级功能模块。
- 兼容**OpenAI API格式**，便于集成与部署。
- 包含**DeepPlanning智能体评估基准**，用于衡量智能体性能。

---
## 3. [microsoft/hve-core](https://github.com/microsoft/hve-core)
- **语言**: PowerShell
- **Stars**: 560
- **简介**: A refined collection of Hypervelocity Engineering components (instructions, prompts, agents) to start your project off right, or upgrade your existing projects to get the most out of all Copilots

### AI 总结
**简介**: Microsoft HVE Core 是一个企业级的提示工程框架，旨在通过约束式AI工作流和结构化方法，帮助开发者（从个人到大型团队）更高效地使用 GitHub Copilot。

**核心功能**:
- 提供一套专门的AI智能体（Agents）、可复用的提示词（Prompts）、指令集（Instructions）和技能包（Skills），用于处理研究、规划和实施等任务。
- 采用RPI（研究→规划→实施）方法论，将复杂工程任务结构化，引导AI生成经过验证的可靠输出。
- 支持通过VS Code扩展或Copilot CLI插件快速安装和集成。

**技术亮点**: 采用约束式AI工作流设计，通过JSON模式验证工件，将AI关注点分离为不同的工件类型以防止行为失控，从而优化从“看似合理的代码”到“已验证的真相”的目标。

---
## 4. [Ed1s0nZ/CyberStrikeAI](https://github.com/Ed1s0nZ/CyberStrikeAI)
- **语言**: Go
- **Stars**: 1,634
- **简介**: CyberStrikeAI is an AI-native security testing platform built in Go. It integrates 100+ security tools, an intelligent orchestration engine, role-based testing with predefined security roles, a skills system with specialized testing skills, and comprehensive lifecycle management capabilities.

### AI 总结
**简介**: CyberStrikeAI 是一个用 Go 语言构建的、AI 原生的安全测试平台，旨在通过集成大量工具和智能编排，实现从对话到漏洞发现的端到端自动化安全测试。

**核心功能**:
- **AI 智能决策与编排**: 集成 OpenAI 兼容模型（GPT、Claude 等），通过原生 MCP 协议驱动 AI 代理，实现自动化测试流程。
- **集成化安全工具库**: 内置 100 多种覆盖完整攻击链的安全工具，涵盖网络扫描、Web 应用扫描、漏洞利用、云安全、二进制分析等多个领域。
- **角色与技能系统**: 提供基于角色的测试（如渗透测试、CTF），并配备 20 多种预定义安全测试技能（如 SQL 注入、XSS），可灵活组合调用。
- **全生命周期管理**: 提供 Web 控制台，支持任务管理、漏洞管理、攻击链可视化、知识库检索以及审计日志等综合管理功能。
- **多渠道交互**: 支持 Web 界面、以及通过钉钉/飞书机器人进行移动端对话交互。

**技术亮点**:
- **原生 MCP 实现**: 支持 HTTP、stdio、SSE 等多种传输协议，并可联合外部 MCP 服务。
- **可扩展架构**: 支持基于 YAML 的工具配方扩展系统。
- **数据高效处理**: 支持大结果分页、压缩和可搜索归档。
- **知识管理与检索**: 内置支持向量搜索和混合检索的知识库。
- **安全与审计**: 提供密码保护的 Web UI、完整的审计日志和 SQLite 数据持久化。

---
## 5. [inclusionAI/AReaL](https://github.com/inclusionAI/AReaL)
- **语言**: Python
- **Stars**: 4,405
- **简介**: Lightning-Fast RL for LLM Reasoning and Agents. Made Simple & Flexible.

### AI 总结
**简介**: AReaL 是一个开源、完全异步的大规模强化学习训练系统，专为大型推理模型和智能体设计，旨在帮助用户轻松、经济地构建自己的AI智能体。

**核心功能**:
- 支持**智能体强化学习**和**在线RL训练**，通过简单替换 `base_url` 即可实现无缝定制。
- 提供**稳定**的完全异步RL训练，具备**行业领先的训练速度**和**卓越的可扩展性**。
- 能够训练出在数学、代码、搜索和客服等领域达到**顶尖水平**的智能体模型。

**技术亮点**:
- **完全异步架构**: 基于开源项目 ReaLHF 构建，实现了高性能的异步训练。
- **灵活与轻量**: 提供算法优先的轻量级版本 AReaL-lite，便于快速原型开发和算法研究。
- **多硬件支持**: 稳定支持在 **Ascend NPU 设备** 上进行训练。
- **开源生态**: 提供完整的训练细节、数据、基础设施及模型，便于复现结果。

---
## 6. [lingfengQAQ/webnovel-writer](https://github.com/lingfengQAQ/webnovel-writer)
- **语言**: Python
- **Stars**: 795
- **简介**: 基于 Claude Code 的长篇网文辅助创作系统，解决 AI 写作中的「遗忘」和「幻觉」问题，支持 200 万字量级 连载创作。

### AI 总结
生成总结时发生错误。

---
## 7. [openai/skills](https://github.com/openai/skills)
- **语言**: Python
- **Stars**: 12,027
- **简介**: Skills Catalog for Codex

### AI 总结
**简介**: OpenAI 官方维护的 Codex AI 代理技能目录，包含可复用的指令、脚本和资源集合。

**核心功能**:
- **技能目录管理**：提供预置（.system）、精选（.curated）和实验性（.experimental）三类技能，供 AI 代理发现和使用。
- **技能安装**：支持通过 `$skill-installer` 命令或 GitHub 目录 URL 快速安装技能。
- **标准化与复用**：遵循 Agent Skills 开放标准，实现“一次编写，随处使用”的能力封装。

**技术亮点**: 基于 Python 实现，采用模块化文件夹结构组织技能，每个技能包含独立的许可证文件（LICENSE.txt）。

---
## 8. [TheCraigHewitt/seomachine](https://github.com/TheCraigHewitt/seomachine)
- **语言**: Python
- **Stars**: 2,169
- **简介**: A specialized Claude Code workspace for creating long-form, SEO-optimized blog content for any business. This system helps you research, write, analyze, and optimize content that ranks well and serves your target audience.

### AI 总结
**简介**: 一个基于 Claude Code 的 AI 工作空间，专门用于为任何企业研究、撰写、分析和优化长篇 SEO 博客内容。

**核心功能**:
- **内容创作与管理**: 提供 `/research`、`/write`、`/rewrite` 等自定义命令，支持从研究、撰写到优化的完整内容工作流。
- **智能分析与优化**: 集成内容分析、SEO 优化、元标签创建、内部链接、关键词映射等专业代理，并提供 0-100 分的 SEO 质量评级。
- **数据驱动与集成**: 支持集成 Google Analytics 4、Google Search Console 和 DataForSEO API，以获取实时性能洞察。
- **品牌与风格定制**: 通过品牌声音、风格指南、SEO 指南和示例等上下文文件，确保内容符合品牌调性。

**技术亮点**: 基于 Python，集成了 NLP 库（nltk, textstat）、机器学习（scikit-learn）、网页抓取工具（beautifulsoup4）以及多个第三方 API，构建了一个数据驱动的 SEO 内容分析与生成系统。

---
## 9. [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund)
- **语言**: Python
- **Stars**: 46,340
- **简介**: An AI Hedge Fund Team

### AI 总结
**简介**: 这是一个用于教育研究的AI驱动对冲基金概念验证项目，通过模拟多位著名投资风格的智能体协作进行交易决策分析，不进行真实交易。

**核心功能**:
- 集成18个不同角色的智能体，涵盖价值投资、成长投资、宏观交易、风险管理和组合管理等多种策略。
- 支持命令行与Web应用两种运行方式，可分析指定股票代码在特定时间段内的交易信号。
- 提供估值、市场情绪、基本面和技术面等多维度分析，并生成最终投资组合建议。

**技术亮点**: 基于Python开发，使用Poetry管理依赖，支持OpenAI、Groq、Anthropic、DeepSeek等多种大语言模型API，并可选择本地Ollama运行。项目采用模块化的多智能体架构，模拟真实对冲基金的决策流程。

---
## 10. [aidenybai/react-grab](https://github.com/aidenybai/react-grab)
- **语言**: TypeScript
- **Stars**: 6,019
- **简介**: Select context for coding agents directly from your website

### AI 总结
**简介**: React Grab 是一个 React 开发工具库，允许开发者直接从网页中选择 UI 元素，一键复制其文件路径、React 组件和 HTML 源码，以提升 AI 编程助手（如 Cursor、Claude Code、Copilot）的上下文理解和工作效率。

**核心功能**:
- **元素选择与复制**：在开发环境中，悬停在 UI 元素上并按 `Cmd+C` (Mac) 或 `Ctrl+C` (Windows/Linux)，即可将该元素的源码和位置信息复制到剪贴板。
- **多框架集成**：提供对 Next.js (App/Pages 路由)、Vite、Webpack 等主流 React 框架和构建工具的简易安装支持。
- **插件系统**：支持通过插件扩展功能，可添加自定义的右键菜单操作、工具栏项目、生命周期钩子和主题覆盖。

**技术亮点**:
- 使用 TypeScript 开发，提供类型安全。
- 设计为轻量级开发工具，仅在开发环境（`NODE_ENV === 'development'`）下加载，不影响生产构建。
- 支持与模型上下文协议（MCP）集成，便于与 AI 编码代理深度协作。

---
