---
tags:
  - github-trending
  - daily
date: 2026-04-01
created: 2026-04-01T01:55:49.968Z
---

# 2026-04-01 GitHub Trending Top 10

## 1. [luongnv89/claude-howto](https://github.com/luongnv89/claude-howto)
- **语言**: Python
- **Stars**: 13,216
- **简介**: A visual, example-driven guide to Claude Code — from basic concepts to advanced agents, with copy-paste templates that bring immediate value.

### AI 总结
**简介**: 一个面向 Claude Code 的视觉化、示例驱动的学习指南，提供从基础概念到高级代理的完整学习路径和可复用的代码模板。

**核心功能**:
- 提供结构化的渐进式学习路径，包含 10 个教程模块，覆盖从基础命令到自定义代理团队等所有 Claude Code 功能。
- 包含大量可直接复制粘贴的生产级配置模板，如斜杠命令、钩子脚本、MCP 配置和子代理定义。
- 通过 Mermaid 图表直观展示功能内部工作原理，帮助理解而不仅仅是使用。
- 内置自我评估功能，可通过 `/self-assessment` 或 `/lesson-quiz` 命令在 Claude Code 中直接进行知识测试和查漏补缺。

**技术亮点**: 项目采用 Python 语言，内容与 Claude Code 版本（v2.2.0）保持同步，并通过可视化图表和交互式命令增强学习体验。

---
## 2. [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice)
- **语言**: Python
- **Stars**: 33,210
- **简介**: Open-Source Frontier Voice AI

### AI 总结
**简介**: VibeVoice 是微软开源的前沿语音AI模型家族，包含文本到语音（TTS）和自动语音识别（ASR）模型。

**核心功能**:
- **VibeVoice-ASR**: 统一的语音转文本模型，支持单次处理长达60分钟的长音频，生成包含说话人、时间戳和内容的结构化转录，并支持用户自定义上下文。
- **VibeVoice-TTS**: 长文本、多说话人文本转语音模型（注：根据README，TTS代码已因使用问题被移除，但相关技术报告和实时模型仍在）。
- **VibeVoice‑Realtime‑0.5B**: 支持流式文本输入和长语音生成的实时文本转语音模型。

**技术亮点**:
- 采用**7.5 Hz超低帧率**的连续语音分词器（声学和语义），在保持音频保真度的同时显著提升长序列处理的计算效率。
- 基于**下一代扩散模型**框架。
- ASR模型原生支持**超过50种语言**，并已集成至Hugging Face Transformers库。
- 支持**vLLM推理**以加速ASR。

---
## 3. [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode)
- **语言**: TypeScript
- **Stars**: 19,164
- **简介**: Teams-first Multi-agent orchestration for Claude Code

### AI 总结
**简介**: 一个为 Claude Code 设计的、团队优先的多智能体编排工具，旨在提供零学习曲线的自动化开发体验。

**核心功能**:
- **多智能体团队协作**：支持创建由多个 Claude、Codex 或 Gemini 智能体组成的团队，以管道化方式（规划、执行、验证、修复）协同完成任务。
- **自动化工作流**：通过简单的自然语言指令（如 `/autopilot`）即可自动构建项目，例如生成 REST API。
- **深度需求访谈**：提供 `/deep-interview` 技能，通过苏格拉底式提问帮助用户在编码前澄清模糊想法和隐藏假设。
- **混合模型协同**：通过 `/ccg` 技能，可同时调用 Codex、Gemini 和 Claude 模型，综合各模型优势进行代码审查、架构分析或 UI 设计。
- **CLI 驱动的 Tmux 工作器**：从 v4.4.0 开始，支持通过 `omc team` 命令在 tmux 会话中按需启动和关闭真实的 CLI 工作进程，避免资源闲置。

**技术亮点**:
- **语言/框架**: TypeScript。
- **架构**: 提供插件市场安装和 npm 全局 CLI 安装两种方式，灵活适配不同使用场景。
- **集成**: 深度集成 Claude Code 实验性团队功能，并支持与 OpenAI Codex CLI 和 Gemini CLI 协同工作。

---
## 4. [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice)
- **语言**: HTML
- **Stars**: 28,786
- **简介**: practice made claude perfect

### AI 总结
**简介**: 这是一个关于 Claude Code 最佳实践的集合项目，旨在通过实践帮助开发者更好地使用 Claude Code 的各项功能。

**核心功能**:
- **子代理 (Subagents)**: 在独立上下文中运行的自主执行者，可配置自定义工具、权限、模型和身份。
- **命令 (Commands)**: 注入到现有上下文中的用户调用式提示模板，用于编排工作流。
- **技能 (Skills)**: 可配置、可预加载、可自动发现的上下文知识注入，支持上下文分叉和渐进式披露。
- **工作流 (Workflows)**: 通过命令编排复杂任务，例如天气查询工作流。
- **钩子 (Hooks)**: 在特定事件（如代理循环外）运行的用户自定义处理器。
- **MCP 服务器**: 通过模型上下文协议连接外部工具、数据库和 API。
- **插件 (Plugins)**: 可分发包，包含技能、子代理、钩子等组件。
- **设置 (Settings)**: 分层配置系统，管理权限、模型、输出样式、沙箱和快捷键等。

**技术亮点**: 项目系统化地整理了 Claude Code 的核心概念，并提供了最佳实践和具体实现案例，涵盖了从代理、命令到工作流编排和外部集成的完整开发生态。

---
## 5. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 20,428
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 开发的自进化 AI 代理，具备内置学习循环，能够从经验中创建并改进技能，实现跨会话的持续学习和个性化交互。

**核心功能**:
- **多平台接入**: 支持通过 Telegram、Discord、Slack、WhatsApp、Signal 等即时通讯平台以及 CLI 终端界面进行交互。
- **自我学习与记忆**: 具备代理管理的记忆系统，可自主创建技能并在使用中自我改进，支持跨会话的全文搜索和 LLM 摘要回忆。
- **灵活部署与运行**: 可在本地、Docker、SSH、Daytona、Singularity 和 Modal 等多种后端上运行，支持在低成本 VPS 或 GPU 集群上部署，并利用无服务器架构实现近乎零成本的闲置休眠。
- **多模型支持**: 兼容 Nous Portal、OpenRouter、OpenAI、Kimi/Moonshot 等多种模型提供商，可通过命令轻松切换，无代码锁定。
- **自动化与并行处理**: 内置定时任务调度器，可生成子代理进行并行工作流处理，并能将多步骤流程压缩为低上下文的单次调用。

**技术亮点**: 采用模块化设计，支持与 `agentskills.io` 开放标准兼容，集成了 Honcho 用户建模，并提供研究就绪的功能如批量轨迹生成和 Atropos RL 环境。

---
## 6. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 128,260
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为 AI 编码代理设计的、基于可组合“技能”的软件开发框架与工作流，旨在引导代理进行系统化、高质量的开发。

**核心功能**:
- **智能规划与设计**：在编码前，通过对话澄清需求，分块呈现并确认设计方案。
- **子代理驱动开发**：将任务分解为小单元，由独立的子代理执行，并经过严格的代码审查。
- **强制执行TDD**：在实现过程中强制进行“红-绿-重构”的测试驱动开发循环。
- **自动化工作流**：集成从头脑风暴、Git工作树管理、计划编写到代码审查和分支收尾的完整自动化流程。

**技术亮点**:
- **技能触发机制**：代理在任务前自动检查并触发相关技能，确保工作流被强制执行。
- **多平台支持**：提供对 Claude Code、Cursor、Codex、OpenCode、GitHub Copilot CLI 和 Gemini CLI 等多种AI编码工具和环境的安装支持。

---
## 7. [microsoft/agent-lightning](https://github.com/microsoft/agent-lightning)
- **语言**: Python
- **Stars**: 16,241
- **简介**: The absolute trainer to light up AI agents.

### AI 总结
**简介**: 微软开源的 Agent Lightning 是一个 AI 智能体训练框架，旨在以极低的代码改动成本，优化和增强各类 AI 代理的性能。

**核心功能**:
- **零代码/低代码优化**：几乎无需修改现有代码，即可将现有智能体转化为可优化的对象。
- **框架无关性**：支持与任何智能体框架（如 LangChain、AutoGen、CrewAI 等）或无框架的纯 Python 代码集成。
- **选择性优化**：可在多智能体系统中，有针对性地优化其中一个或多个智能体。
- **多算法支持**：集成了强化学习、自动提示优化、监督微调等多种训练算法。

**技术亮点**: 采用最小化侵入式设计，允许用户的智能体保持原有运行方式，同时通过算法进行优化。项目提供了 PyPI 包、详细文档和活跃的社区支持。

---
## 8. [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)
- **语言**: Python
- **Stars**: 74,224
- **简介**: Turn any PDF or image document into structured data for your AI. A powerful, lightweight OCR toolkit that bridges the gap between images/PDFs and LLMs. Supports 100+ languages.

### AI 总结
**简介**: PaddleOCR 是一个功能强大、轻量级的开源 OCR 工具包，旨在将任何 PDF 或图像文档转换为可供 AI 处理的结构化数据，支持 100 多种语言。

**核心功能**:
- **智能文档解析**：提供行业领先的轻量级视觉语言模型 **PaddleOCR-VL-1.5**，擅长处理扭曲、扫描、屏幕截图、光照不均和倾斜等复杂文档，并输出 Markdown 或 JSON 格式的结构化数据。
- **结构感知转换**：基于 **PP-StructureV3**，可将复杂的 PDF 和图像无缝转换为 Markdown 或 JSON，并提供表格单元格、文本坐标等细粒度信息。

**技术亮点**:
- 支持多种硬件平台（CPU、GPU、XPU、NPU）和操作系统（Linux、Windows、macOS）。
- 拥有庞大的用户和项目生态，被 Dify、RAGFlow 等顶级项目采用，是构建智能 RAG 和 Agent 应用的基石。

---
## 9. [Dimillian/Skills](https://github.com/Dimillian/Skills)
- **语言**: Shell
- **Stars**: 2,880
- **简介**: My Codex Skills

### AI 总结
**简介**: 一个面向 Apple 平台开发、GitHub 工作流、代码审查与重构等场景的、可复用的开发技能集合库。

**核心功能**:
- 生成 App Store 更新日志：从 Git 历史自动创建面向用户的版本发布说明。
- 多智能体代码审查与缺陷调查：通过“审查群”和“缺陷狩猎群”模式，系统化分析代码变更和定位问题根因。
- 性能分析与优化：提供针对 React 组件和 SwiftUI 应用的运行时性能诊断与优化建议。
- 项目重构与代码质量提升：支持批量重构编排、代码简化审查以及 Swift 并发、SwiftUI 视图模式等专项重构。
- 平台特定开发支持：包含 iOS 应用调试、macOS 应用打包（支持 Tuist 和 SwiftPM）等技能。

**技术亮点**: 基于 Codex 技能框架，采用模块化、自包含的技能设计，集成了 `gh` CLI、XcodeBuildMCP 等工具，并强调通过多智能体协作（Swarm）模式提升代码审查与问题排查的效率。

---
## 10. [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock)
- **语言**: Python
- **Stars**: 75,569
- **简介**: Hunt down social media accounts by username across social networks

### AI 总结
**简介**: 一个用于通过用户名在多个社交网络上查找对应账户的 Python 工具。

**核心功能**:
- 支持在超过 300 个社交网站上搜索指定用户名。
- 提供命令行界面，支持同时搜索多个用户名。
- 支持将搜索结果以 JSON、CSV 等格式输出到文件。

**技术亮点**: 基于 Python 开发，使用异步请求（`aiohttp`）来提高搜索速度，并支持通过代理进行网络请求。

---
