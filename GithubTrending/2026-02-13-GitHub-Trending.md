---
tags:
  - github-trending
  - daily
date: 2026-02-13
created: 2026-02-13T01:55:48.356Z
---

# 2026-02-13 GitHub Trending Top 10

## 1. [tambo-ai/tambo](https://github.com/tambo-ai/tambo)
- **语言**: TypeScript
- **Stars**: 9,032
- **简介**: Generative UI SDK for React

### AI 总结
**简介**: Tambo AI 是一个用于 React 的开源生成式 UI 工具包，旨在帮助开发者构建能够动态渲染和更新用户界面的智能体。

**核心功能**:
- **声明式组件注册**：使用 Zod 模式定义 React 组件及其属性，使智能体能够理解并调用合适的组件。
- **全栈解决方案**：提供 React SDK 和用于处理对话状态与智能体执行的后端（可选择云端托管或自托管）。
- **流式基础设施**：支持将 LLM 生成的组件属性实时流式传输到前端组件，并自动处理取消、错误恢复和重连。
- **智能体集成**：内置智能体对话循环，支持 OpenAI、Anthropic、Gemini 等多种 LLM，并可集成 LangChain、Mastra 等框架。

**技术亮点**: 基于 TypeScript，采用全栈架构，通过 Zod 模式实现类型安全的组件定义与 LLM 工具调用，并提供了云端与 Docker 自托管两种部署选项。

---
## 2. [danielmiessler/Personal_AI_Infrastructure](https://github.com/danielmiessler/Personal_AI_Infrastructure)
- **语言**: TypeScript
- **Stars**: 7,531
- **简介**: Agentic AI Infrastructure for magnifying HUMAN capabilities.

### AI 总结
**简介**: 一个旨在通过智能体化AI基础设施来放大个人能力、帮助人们进行自我发现并追求人生目标的个人AI栈项目。

**核心功能**:
*   **激活个人潜力**: 通过AI辅助的自我发现，帮助用户识别、阐明并追求自己的人生目标。
*   **提供顶级AI能力**: 致力于让世界上最好的AI技术对每个人都可及，而非仅为少数人服务。
*   **模块化与可组合**: 提供“包”（Packs）和“捆绑包”（Bundles）等组件，允许用户构建和定制自己的个人AI基础设施。

**技术亮点**: 项目主要使用 **TypeScript** 开发，并采用 **Bun** 运行时。其架构强调“智能体化”（Agentic），并引入了诸如双通道能力选择、并行执行等特性。

---
## 3. [google/langextract](https://github.com/google/langextract)
- **语言**: Python
- **Stars**: 31,429
- **简介**: A Python library for extracting structured information from unstructured text using LLMs with precise source grounding and interactive visualization.

### AI 总结
**简介**: LangExtract 是一个由 Google 开发的 Python 库，利用大语言模型从非结构化文本中提取结构化信息。

**核心功能**:
- **精确溯源**：将提取的每个信息点映射回源文本中的确切位置，支持可视化高亮，便于追溯和验证。
- **可靠的结构化输出**：基于用户提供的少量示例，强制执行一致的输出模式，确保结果的结构化与可靠性。
- **长文档优化**：通过优化的文本分块、并行处理和多轮扫描策略，有效处理大型文档的提取任务。
- **交互式可视化**：自动生成独立的交互式 HTML 文件，用于在原始上下文中直观地审查数千个提取的实体。
- **灵活的 LLM 支持**：支持多种模型，包括云端 LLM（如 Google Gemini）和通过 Ollama 接口运行的本地开源模型。
- **领域自适应**：仅需少量示例即可定义任何领域的提取任务，无需对模型进行微调。

**技术亮点**: 基于 Python 和 LLM 技术栈，通过提示工程和少样本示例引导模型，并利用受控生成等技术保证输出质量。

---
## 4. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)
- **语言**: TypeScript
- **Stars**: 24,409
- **简介**: Chrome DevTools for coding agents

### AI 总结
**简介**: Chrome DevTools MCP 是一个基于 Model-Context-Protocol (MCP) 的服务器，允许 AI 编程助手（如 Claude、Cursor 等）连接并控制真实的 Chrome 浏览器，实现自动化、调试和性能分析。

**核心功能**:
- **性能洞察**: 利用 Chrome DevTools 记录性能追踪数据，并提供可操作的性能分析建议。
- **高级浏览器调试**: 支持分析网络请求、截取屏幕截图、检查浏览器控制台消息（包含源码映射的堆栈跟踪）。
- **可靠自动化**: 基于 Puppeteer 自动化 Chrome 浏览器操作，并自动等待操作结果。

**技术亮点**:
- 基于 **TypeScript** 开发，作为 **MCP 服务器** 运行。
- 底层整合了 **Chrome DevTools Protocol** 和 **Puppeteer** 以实现浏览器控制。
- 支持与多种主流 AI 助手/IDE（如 Claude Code、Antigravity、Cline 等）通过 MCP 协议集成。

---
## 5. [microsoft/PowerToys](https://github.com/microsoft/PowerToys)
- **语言**: C#
- **Stars**: 129,656
- **简介**: Microsoft PowerToys is a collection of utilities that supercharge productivity and customization on Windows

### AI 总结
**简介**: Microsoft PowerToys 是一个由微软官方开发的 Windows 系统增强工具集，旨在通过一系列实用程序来提升用户的生产力和系统自定义能力。

**核心功能**:
- 提供超过 25 个独立的实用工具，涵盖系统优化、文件管理、效率提升等多个方面。
- 代表性工具包括：窗口布局管理工具 FancyZones、快速启动器 PowerToys Run、文件批量重命名工具 PowerRename、颜色拾取器 Color Picker、屏幕标尺 Screen Ruler、OCR 文本提取工具 Text Extractor 等。

**技术亮点**: 项目主要使用 C# 语言开发，是微软在 Windows 平台上构建的开源、模块化系统工具集，其架构允许各个实用程序独立运行和更新。

---
## 6. [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi)
- **语言**: TypeScript
- **Stars**: 15,396
- **简介**: Free, local, open-source 24/7 Cowork and OpenClaw for Gemini CLI, Claude Code, Codex, OpenCode, Qwen Code, Goose CLI, Auggie, and more | 🌟 Star if you like it!

### AI 总结
**简介**: AionUi 是一个免费、本地化、开源的图形界面工具，旨在为多种命令行 AI 工具（如 Gemini CLI、Claude Code 等）提供统一的协作平台。

**核心功能**:
- **多智能体模式**：为多种命令行 AI 工具提供统一的图形界面，支持自动检测和集成本地工具，并具备本地存储和多会话管理。
- **随处访问**：支持通过 WebUI 或集成 Telegram、Lark 等聊天平台，实现跨设备的远程访问。
- **定时任务**：支持使用自然语言设置定时任务，实现 AI 助手的自动化、无人值守运行。

**技术亮点**: 基于 TypeScript 开发，支持跨平台（macOS/Windows/Linux），采用本地化部署以保障数据安全，并提供灵活的远程访问和集成方案。

---
## 7. [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)
- **语言**: Python
- **Stars**: 94,364
- **简介**: Collection of awesome LLM apps with AI Agents and RAG using OpenAI, Anthropic, Gemini and opensource models.

### AI 总结
**简介**: 一个精心整理的、汇集了各类优秀大语言模型（LLM）应用项目的资源库。

**核心功能**:
- 收集并展示基于RAG、AI智能体、多智能体团队、MCP、语音智能体等技术构建的LLM应用。
- 项目涵盖使用OpenAI、Anthropic、Google、xAI等商业模型以及Qwen、Llama等开源模型的应用程序。
- 旨在为开发者提供灵感、学习案例，并促进LLM应用开源生态的发展。

**技术亮点**: 项目集合体现了当前LLM应用开发的主流技术栈，包括检索增强生成（RAG）、智能体（Agent）框架、模型上下文协议（MCP）以及多模型集成。

---
## 8. [rowboatlabs/rowboat](https://github.com/rowboatlabs/rowboat)
- **语言**: TypeScript
- **Stars**: 5,193
- **简介**: Open-source AI coworker, with memory

### AI 总结
**简介**: Rowboat 是一个开源的、具备长期记忆功能的本地优先 AI 协作者，能将工作内容转化为知识图谱并据此行动。

**核心功能**:
- **构建与利用知识图谱**：连接电子邮件和会议笔记，构建并维护一个可长期积累、可编辑的 Obsidian 兼容 Markdown 知识图谱。
- **智能辅助工作**：基于知识图谱上下文，自动生成会议简报、起草邮件、创建文档和 PDF 演示文稿等。
- **后台智能体**：可运行后台智能体自动处理重复性任务，如草拟邮件回复、生成每日语音备忘录等。
- **支持语音备忘录**：录制语音备忘录可自动提取关键信息并更新知识图谱。

**技术亮点**: 采用 TypeScript 开发，强调本地优先和隐私保护，所有数据以纯 Markdown 格式存储在用户本地设备上。

---
## 9. [github/gh-aw](https://github.com/github/gh-aw)
- **语言**: Go
- **Stars**: 2,022
- **简介**: GitHub Agentic Workflows

### AI 总结
**简介**: GitHub Agentic Workflows 是一个允许开发者使用自然语言 Markdown 编写智能体工作流，并在 GitHub Actions 中安全运行的 Go 语言项目。

**核心功能**:
- 使用自然语言 Markdown 编写工作流，降低自动化门槛。
- 在 GitHub Actions 环境中运行，与现有 CI/CD 流程集成。
- 提供多层安全防护（如默认只读权限、沙箱执行、输入净化、网络隔离等），确保 AI 智能体在受控边界内安全运行。

**技术亮点**:
- **安全架构**: 内置沙箱、安全输出、工具白名单、编译时验证等多层防护机制。
- **生态集成**: 提供配套项目如 Agent Workflow Firewall（网络出口控制）和 MCP Gateway（统一 HTTP 网关），增强安全与集成能力。

---
## 10. [unslothai/unsloth](https://github.com/unslothai/unsloth)
- **语言**: Python
- **Stars**: 52,050
- **简介**: Fine-tuning & Reinforcement Learning for LLMs. 🦥 Train OpenAI gpt-oss, DeepSeek, Qwen, Llama, Gemma, TTS 2x faster with 70% less VRAM.

### AI 总结
**简介**: Unsloth 是一个用于大语言模型（LLM）微调和强化学习的开源 Python 库，旨在显著提升训练速度并大幅降低显存消耗。

**核心功能**:
- 支持多种主流大语言模型的微调，包括 OpenAI gpt-oss、DeepSeek、Qwen、Llama、Gemma 以及 TTS 模型。
- 提供免费的 Google Colab 和 Kaggle 入门 Notebook，用户可快速上手进行模型训练和部署。
- 支持多种任务类型，包括标准微调、GRPO（强化学习）、视觉多模态、文本转语音（TTS）和嵌入模型训练。

**技术亮点**: 通过底层优化，实现高达 2 倍的训练加速和高达 80% 的显存（VRAM）节省。

---
