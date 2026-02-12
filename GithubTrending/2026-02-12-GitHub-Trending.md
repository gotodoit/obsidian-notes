---
tags:
  - github-trending
  - daily
date: 2026-02-12
created: 2026-02-12T01:55:46.743Z
---

# 2026-02-12 GitHub Trending Top 7

## 1. [google/langextract](https://github.com/google/langextract)
- **语言**: Python
- **Stars**: 30,509
- **简介**: A Python library for extracting structured information from unstructured text using LLMs with precise source grounding and interactive visualization.

### AI 总结
**简介**: LangExtract 是一个由 Google 开发的 Python 库，利用大语言模型从非结构化文本中提取结构化信息，并强调精确的原文定位和交互式可视化。

**核心功能**:
- **精确原文定位**: 将提取的每个信息点映射到源文本中的确切位置，支持可视化高亮，便于追溯和验证。
- **可靠结构化输出**: 基于用户提供的少量示例强制执行一致的输出模式，利用受控生成技术确保结果的结构化。
- **长文档优化**: 通过优化的文本分块、并行处理和多轮处理策略，解决从大型文档中提取信息的“大海捞针”难题。
- **交互式可视化**: 即时生成独立的交互式 HTML 文件，用于在原始上下文中可视化和审查数千个提取的实体。
- **灵活的 LLM 支持**: 支持多种模型，从云端 LLM（如 Google Gemini 系列）到通过内置 Ollama 接口运行的本地开源模型。
- **领域自适应**: 仅需少量示例即可定义任何领域的提取任务，无需对模型进行微调。

**技术亮点**: 采用基于提示词和少量示例的上下文学习方式，结合文本分块、并行处理等策略，并内置对 Gemini、OpenAI、Ollama 等模型接口的支持。

---
## 2. [github/gh-aw](https://github.com/github/gh-aw)
- **语言**: Go
- **Stars**: 1,741
- **简介**: GitHub Agentic Workflows

### AI 总结
**简介**: GitHub Agentic Workflows 是一个 Go 语言项目，旨在让用户能够使用自然语言 Markdown 编写智能体工作流，并在 GitHub Actions 中安全地运行。

**核心功能**:
- 使用自然语言 Markdown 编写工作流，降低自动化脚本的编写门槛。
- 与 GitHub Actions 深度集成，可直接在平台上运行这些智能体工作流。
- 提供全面的安全防护机制（守护栏），包括默认只读权限、沙箱执行和输入净化等。

**技术亮点**:
- **安全架构**: 默认运行在只读权限下，通过多层防护（如沙箱、网络隔离、供应链安全、工具白名单、编译时验证）确保执行安全。
- **扩展生态**: 拥有配套项目如 Agent Workflow Firewall (AWF) 用于网络出口控制，以及 MCP Gateway 用于集中管理模型上下文协议服务器调用。

---
## 3. [microsoft/PowerToys](https://github.com/microsoft/PowerToys)
- **语言**: C#
- **Stars**: 129,414
- **简介**: Microsoft PowerToys is a collection of utilities that supercharge productivity and customization on Windows

### AI 总结
**简介**: Microsoft PowerToys 是一个由微软官方开发的 Windows 系统增强工具集，旨在通过一系列实用工具提升用户的生产力和自定义体验。

**核心功能**:
- 提供超过 25 个独立的实用工具，涵盖系统定制、效率提升和日常任务优化。
- 主要工具包括：窗口布局管理（FancyZones）、快速启动器（PowerToys Run）、文件批量重命名（PowerRename）、颜色拾取器（Color Picker）、键盘管理器（Keyboard Manager）、文本提取器（Text Extractor）等。

**技术亮点**: 项目主要使用 C# 语言开发，是一个开源的、持续更新的 Windows 桌面应用程序集合。

---
## 4. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)
- **语言**: TypeScript
- **Stars**: 23,998
- **简介**: Chrome DevTools for coding agents

### AI 总结
**简介**: Chrome DevTools MCP 是一个基于 Model-Context-Protocol (MCP) 的服务器，能让 AI 编程助手（如 Claude、Cursor）连接并控制真实的 Chrome 浏览器，实现自动化、调试和性能分析。

**核心功能**:
- **性能洞察**: 利用 Chrome DevTools 记录性能追踪数据，并提供可操作的性能分析。
- **高级浏览器调试**: 分析网络请求、截取屏幕截图、检查浏览器控制台消息（支持源码映射堆栈跟踪）。
- **可靠自动化**: 基于 Puppeteer 自动化 Chrome 操作，并自动等待操作结果。

**技术亮点**:
- 作为 MCP 服务器，为 AI 助手提供标准化的浏览器控制接口。
- 底层整合了 Chrome DevTools Protocol 和 Puppeteer 库。
- 支持与 Google CrUX API 集成以获取真实用户体验数据（可禁用）。

---
## 5. [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin)
- **语言**: TypeScript
- **Stars**: 8,484
- **简介**: Official Claude Code compound engineering plugin

### AI 总结
**简介**: 这是一个官方的 Claude Code 复合工程插件市场，旨在通过工具链让每一次工程工作都比上一次更容易。

**核心功能**:
- 提供 `/workflows:plan`、`/workflows:work`、`/workflows:review`、`/workflows:compound` 等命令，覆盖从规划、执行、审查到知识沉淀的完整开发工作流。
- 包含一个 Bun/TypeScript CLI 工具，可将 Claude Code 插件转换为 OpenCode、Codex 和 Factory Droid 等实验性格式。
- 支持将个人 Claude Code 配置（技能和 MCP 服务器）同步到 OpenCode 或 Codex 环境。

**技术亮点**: 项目基于 TypeScript 开发，使用 Bun 运行时，并提供了将插件和配置在不同 AI 编码助手平台（Claude Code, OpenCode, Codex, Factory Droid）之间进行转换和同步的能力。

---
## 6. [patchy631/ai-engineering-hub](https://github.com/patchy631/ai-engineering-hub)
- **语言**: Jupyter Notebook
- **Stars**: 28,649
- **简介**: In-depth tutorials on LLMs, RAGs and real-world AI agent applications.

### AI 总结
**简介**: 这是一个专注于 AI 工程实践的综合性学习与项目资源库，提供了大量关于大语言模型、检索增强生成和 AI 智能体应用的教程与项目。

**核心功能**:
- 提供 **93+ 个生产就绪项目**，涵盖从入门到高级的所有技能水平。
- 包含 **LLMs、RAG、智能体** 等领域的深度教程和真实世界应用案例。
- 项目按难度分级，便于用户循序渐进地学习和构建技能。

**技术亮点**:
- 项目广泛使用主流开源模型和技术栈，如 **Llama、Gemma、Qwen、DeepSeek、Ollama、LlamaIndex、CrewAI** 等。
- 涵盖多种应用场景，包括 **OCR、聊天界面、RAG 系统、多模态处理、AI 智能体工作流**。

---
## 7. [cheahjs/free-llm-api-resources](https://github.com/cheahjs/free-llm-api-resources)
- **语言**: Python
- **Stars**: 9,539
- **简介**: A list of free LLM inference resources accessible via API.

### AI 总结
**简介**: 一个收集了可通过 API 免费访问或提供试用额度的大型语言模型（LLM）推理资源的列表项目。

**核心功能**:
- 汇总并分类整理了多个提供免费或试用额度的 LLM API 服务提供商。
- 为每个提供商列出了具体的免费模型、使用限制（如请求频率、每日额度）和官方链接。

**技术亮点**: 项目使用 Python 脚本 (`src/pull_available_models.py`) 自动生成 README 文件，确保列表信息的时效性和准确性。

---
