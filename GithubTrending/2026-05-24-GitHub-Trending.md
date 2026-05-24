---
tags:
  - github-trending
  - daily
date: 2026-05-24
created: 2026-05-24T01:55:43.200Z
---

# 2026-05-24 GitHub Trending Top 10

## 1. [Lum1104/Understand-Anything](https://github.com/Lum1104/Understand-Anything)
- **语言**: TypeScript
- **Stars**: 21,676
- **简介**: Graphs that teach > graphs that impress. Turn any code into an interactive knowledge graph you can explore, search, and ask questions about. Works with Claude Code, Codex, Cursor, Copilot, Gemini CLI, and more.

### AI 总结
**简介**: 一个能将任何代码库、知识库或文档转化为可交互、可搜索的知识图谱的工具，帮助开发者快速理解项目结构。

**核心功能**:
- 将代码库解析为交互式知识图谱，每个文件、函数、类都作为可点击节点
- 支持模糊搜索和语义搜索，可按名称或含义查找内容
- 自动生成架构导览，按依赖顺序引导学习代码库
- 提供变更影响分析，可视化代码改动的影响范围
- 支持知识库分析，可将LLM wiki转化为带聚类的知识图谱

**技术亮点**:
- 采用TypeScript开发，使用多智能体管道分析项目
- 作为Claude Code插件运行，同时兼容Codex、Cursor、Copilot、Gemini CLI等工具
- 支持领域视图切换，展示业务逻辑和流程映射

---
## 2. [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- **语言**: Python
- **Stars**: 26,498
- **简介**: Official, Anthropic-managed directory of high quality Claude Code Plugins.

### AI 总结
**简介**: Anthropic官方维护的Claude Code高质量插件目录市场。

**核心功能**:
- 提供官方和第三方插件的集中发现与安装（通过`/plugin install`命令或界面浏览）
- 区分内部插件（`/plugins`）和社区外部插件（`/external_plugins`）
- 支持通过提交表单向市场贡献第三方插件（需通过质量与安全审核）

**技术亮点**: 采用标准化插件结构（含`.claude-plugin/plugin.json`元数据、`.mcp.json`配置、可选commands/agents/skills模块），基于Python实现。

---
## 3. [colbymchenry/codegraph](https://github.com/colbymchenry/codegraph)
- **语言**: TypeScript
- **Stars**: 19,600
- **简介**: Pre-indexed code knowledge graph for Claude Code, Codex, Cursor, OpenCode, and Hermes Agent — fewer tokens, fewer tool calls, 100% local

### AI 总结
**简介**: CodeGraph 是一个预索引的代码知识图谱工具，专为 Claude Code、Cursor、Codex 等 AI 编程助手设计，通过提供符号关系、调用图和代码结构，显著降低使用成本、减少工具调用次数，并完全本地运行。

**核心功能**:
- 为 AI 编程助手提供预索引的语义代码知识图谱，减少文件扫描和工具调用
- 支持一键安装（无需 Node.js）和项目初始化，自动配置主流 AI 编程助手
- 提供基准测试验证的性能提升：平均节省 35% 成本、70% 工具调用、49% 时间

**技术亮点**: 使用 TypeScript 开发，跨平台支持（Windows/macOS/Linux），自包含运行时无需编译，支持 MCP 服务器协议集成。

---
## 4. [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch)
- **语言**: Python
- **Stars**: 13,823
- **简介**: Learn it. Build it. Ship it for others.

### AI 总结
**简介**: 一套完整的、从零开始的AI工程课程，涵盖435节课和20个阶段，旨在弥补学生使用AI工具与专业应用之间的技能差距。

**核心功能**:
- **系统性课程**: 20个阶段、435节课，从数学基础到自主智能体系统，覆盖Python、TypeScript、Rust、Julia四种语言。
- **动手实践**: 每节课遵循“问题→数学推导→代码实现→测试→产出可复用工件”的循环，确保深入理解而非表面使用。
- **从零构建**: 先手写实现算法（如反向传播、分词器、注意力机制），再使用生产级框架，理解底层原理。
- **完整产出**: 每节课产生可复用的提示词、技能、智能体或MCP服务器等工件。

**技术亮点**: 采用分阶段递进式架构（数学→ML基础→深度学习→视觉/NLP/语音→Transformer→GenAI→LLM→智能体→生产部署），课程结构清晰；支持本地运行，开源且遵循MIT许可。

---
## 5. [Fincept-Corporation/FinceptTerminal](https://github.com/Fincept-Corporation/FinceptTerminal)
- **语言**: Python
- **Stars**: 23,139
- **简介**: FinceptTerminal is a modern finance application offering advanced market analytics, investment research, and economic data tools, designed for interactive exploration and data-driven decision-making in a user-friendly environment.

### AI 总结
**简介**: FinceptTerminal 是一款面向现代金融的智能终端应用，提供机构级别的市场分析、投资研究和经济数据工具，助力用户进行数据驱动的交互式决策。

**核心功能**:
- **权益研究**: 提供深入的股票研究与分析工具。
- **投资组合管理**: 支持投资组合的构建、监控与优化。
- **新闻聚合**: 实时获取并筛选全球金融新闻。
- **节点编辑器**: 提供可视化数据流与自动化工作流编辑能力。

**技术亮点**: 采用 C++20 和 Qt6 构建高性能前端，结合 Python 3.11+ 进行数据处理与 AI 自动化，支持无限数据源连接，并基于 AGPL-3.0 开源协议。

---
## 6. [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills)
- **语言**: Unknown
- **Stars**: 149,718
- **简介**: A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.

### AI 总结
**简介**: 一个基于 Andrej Karpathy 对 LLM 编码陷阱的观察，通过单个 `CLAUDE.md` 文件改善 Claude Code 行为的指南。

**核心功能**:
- **Think Before Coding**: 要求显式陈述假设、呈现多种解释、在必要时提出反对，并在困惑时停下来询问澄清。
- **Simplicity First**: 只写解决问题所需的最少代码，避免过度工程、不必要的抽象和未要求的功能。
- **Surgical Changes**: 只修改必须修改的代码，不“改进”相邻代码，清理仅由自己更改产生的遗留内容。
- **Goal-Driven Execution**: 将指令性任务转化为可验证的目标，通过测试优先和明确的成功标准让 LLM 自主循环执行。

**技术亮点**: 以单个 `CLAUDE.md` 文件作为核心，提供插件（Claude Code Plugin）和文件复制（CLAUDE.md / Cursor 规则）两种安装方式，可无缝集成到 Claude Code 和 Cursor 等开发环境中。

---
## 7. [dotnet/skills](https://github.com/dotnet/skills)
- **语言**: C#
- **Stars**: 2,755
- **简介**: Repository for skills to assist AI coding agents with .NET and C#

### AI 总结
**简介**: 该仓库是 .NET 团队为 AI 编码助手精心策划的核心技能和自定义代理集合，遵循 Agent Skills 开放标准，旨在帮助 AI 高效处理 .NET 和 C# 相关开发任务。

**核心功能**:
- **提供丰富的 .NET 技能插件**：涵盖 .NET 核心编码、数据访问 (EF Core)、性能诊断、MSBuild 构建、NuGet 包管理、项目升级、MAUI 开发、AI/ML 集成、模板引擎、测试、ASP.NET Core 以及 .NET 11 新特性等 12 个领域。
- **支持多种主流 AI 编码工具**：可无缝集成到 Copilot CLI、Claude Code、VS Code、Cursor 和 OpenAI Codex 等工具中，通过插件市场或命令行安装使用。
- **提供可视化仪表盘**：通过 GitHub Pages 提供插件的准确性和效率评分趋势，方便用户评估和选择。

**技术亮点**: 基于 C# 开发，遵循 [agentskills.io](https://agentskills.io) 开放标准，采用插件化架构，支持多平台（VS Code、Cursor、Codex CLI 等）集成，并包含针对 .NET 生态（如 MSBuild、EF Core、NuGet）的深度定制技能。

---
## 8. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)
- **语言**: TypeScript
- **Stars**: 41,350
- **简介**: Chrome DevTools for coding agents

### AI 总结
**简介**: 一个基于 MCP 协议的工具，让 AI 编码助手（如 Antigravity、Claude、Cursor 等）能够控制和检查 Chrome 浏览器，实现自动化调试与性能分析。

**核心功能**:
- **性能分析**: 录制 Chrome 性能追踪，提取可操作性能洞察。
- **高级浏览器调试**: 分析网络请求、截图、检查控制台消息（支持源映射堆栈跟踪）。
- **可靠自动化**: 基于 Puppeteer 自动执行 Chrome 操作并等待结果。

**技术亮点**: 使用 TypeScript 开发，基于 Model-Context-Protocol (MCP) 协议，集成了 Chrome DevTools 和 Puppeteer。

---
## 9. [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills)
- **语言**: Python
- **Stars**: 7,462
- **简介**: 754 structured cybersecurity skills for AI agents · Mapped to 5 frameworks: MITRE ATT&CK, NIST CSF 2.0, MITRE ATLAS, D3FEND & NIST AI RMF · agentskills.io standard · Works with Claude Code, GitHub Copilot, Codex CLI, Cursor, Gemini CLI & 20+ platforms · 26 security domains · Apache 2.0

### AI 总结
**简介**: 一个开源网络安全技能库，为AI代理提供754个结构化技能，覆盖26个安全领域并映射至5个行业框架。

**核心功能**:
- 提供754个生产级网络安全技能，覆盖数字取证、威胁狩猎、云安全等26个领域
- 每个技能同时映射至MITRE ATT&CK、NIST CSF 2.0、MITRE ATLAS、MITRE D3FEND和NIST AI RMF五大框架
- 兼容Claude Code、GitHub Copilot、Codex CLI、Cursor、Gemini CLI等26+AI平台
- 支持通过`npx skills add`或Git clone快速部署，即插即用

**技术亮点**:
- 采用agentskills.io开放标准格式，确保跨平台兼容性
- 使用Python编写，结构化技能库支持自动化集成
- 统一跨框架映射，一个技能满足五个合规检查点
- 社区驱动项目，采用Apache 2.0开源协议

---
## 10. [presenton/presenton](https://github.com/presenton/presenton)
- **语言**: TypeScript
- **Stars**: 6,398
- **简介**: Open-Source AI Presentation Generator and API (Gamma, Beautiful AI, Decktopus Alternative)

### AI 总结
**简介**: Presenton 是一个开源的 AI 演示文稿生成器，提供 API 支持，可作为 Gamma、Beautiful AI 和 Decktopus 的替代方案。

**核心功能**:
- 支持通过 Docker 自托管 Web 版，或下载桌面应用（Mac/Windows/Linux）
- 兼容 OpenAI、Gemini、Vertex AI、Azure OpenAI 等主流 AI 模型，以及 Ollama 本地模型
- 提供 AI 演示文稿生成 API，支持从提示词或上传文档生成内容
- 自定义模板和主题，支持 HTML 和 Tailwind CSS 设计
- 导出为可编辑的 PPTX 和 PDF 格式
- 内置 MCP 服务器，支持通过模型上下文协议生成演示文稿

**技术亮点**: 基于 TypeScript 开发，采用 Apache 2.0 开源协议，支持自托管和本地运行，提供 Docker 一键部署，支持多模型混合使用（文本和图像生成），内置 Electron 桌面应用框架。

---
