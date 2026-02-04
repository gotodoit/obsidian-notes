---
tags:
  - github-trending
  - daily
date: 2026-02-04
created: 2026-02-04T22:31:50.483Z
---

# 2026-02-04 GitHub Trending Top 10

> [!INFO]
> 本日报由 AI 自动生成，精选 GitHub Trending 前 10 项目。

## 1. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 22,373
- **简介**: A Claude Code plugin that automatically captures everything Claude does during your coding sessions, compresses it with AI (using Claude's agent-sdk), and injects relevant context back into future sessions.

### AI 总结
**简介**: 一个为 Claude Code 设计的持久化记忆压缩系统插件，能自动捕获编码会话中的操作，利用 AI 进行压缩，并在未来的会话中注入相关上下文。

**核心功能**:
- 自动捕获 Claude 在编码会话中的所有操作和观察结果。
- 使用 AI（基于 Claude 的 agent-sdk）对捕获的内容进行语义总结和压缩。
- 将压缩后的记忆作为上下文注入到未来的 Claude Code 会话中，实现跨会话的知识连续性。

**技术亮点**: 基于 TypeScript 开发，集成了 Claude 的 agent-sdk 进行智能内容处理，并支持多语言文档。

---
## 2. [openai/skills](https://github.com/openai/skills)
- **语言**: Python
- **Stars**: 3,622
- **简介**: Skills Catalog for Codex

### AI 总结
**简介**: OpenAI 的 Codex AI 代理技能目录，包含可复用的指令、脚本和资源，用于帮助 AI 代理完成特定任务。

**核心功能**:
- 提供预构建的技能包，涵盖系统、精选和实验性类别，供 AI 代理发现和使用。
- 支持通过命令行工具 `$skill-installer` 安装和管理技能。
- 技能遵循开放标准，可跨团队和个人重复使用，提升任务完成效率。

**技术亮点**: 基于 Python 实现，采用模块化目录结构，技能以独立文件夹形式组织，包含完整的说明文件和许可证。

---
## 3. [disler/claude-code-hooks-mastery](https://github.com/disler/claude-code-hooks-mastery)
- **语言**: Python
- **Stars**: 2,333
- **简介**: Master Claude Code Hooks

### AI 总结
**简介**: 这是一个用于深入学习和掌握 Claude Code Hooks 的 Python 项目，通过演示如何利用钩子对 Claude Code 的行为进行确定性（或非确定性）控制。

**核心功能**:
- 完整捕获并演示了 Claude Code 的 13 个钩子生命周期事件，包括 `UserPromptSubmit`、`PreToolUse`、`PostToolUse` 等。
- 展示了高级功能，如子代理（Sub-Agents）、元代理（Meta-Agent）和基于团队的验证系统（Team-Based Validation）。
- 提供了多种输出样式和自定义状态行的示例。

**技术亮点**:
- 采用 **Astral UV** 作为快速的 Python 包安装器和解析器。
- 架构基于 **UV 单文件脚本**，便于管理和运行。
- 集成了多种可选的外部服务（MCP 服务器），如 **ElevenLabs**（文本转语音）、**Firecrawl**（网络爬虫）以及 **OpenAI**、**Anthropic**、**Ollama** 等语言模型提供商，增强了功能扩展性。

---
## 4. [OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev)
- **语言**: Python
- **Stars**: 29,952
- **简介**: ChatDev 2.0: Dev All through LLM-powered Multi-Agent Collaboration

### AI 总结
**简介**: ChatDev 2.0 (DevAll) 是一个零代码、基于大语言模型的多智能体协作平台，旨在通过简单的配置快速构建和执行定制化的多智能体系统，以完成从软件开发到数据可视化、3D生成等复杂任务。

**核心功能**:
- **零代码多智能体编排**: 用户无需编程，即可通过配置定义智能体、工作流和任务，实现复杂场景的自动化。
- **全生命周期软件开发**: 继承自ChatDev 1.0，通过模拟虚拟软件公司（如CEO、CTO、程序员等角色）的研讨会，自动化完成软件的设计、编码、测试和文档编写。
- **支持多样化任务**: 平台不仅限于软件开发，还可应用于数据可视化、3D生成、深度研究、逻辑推理、故事生成等多种复杂任务场景。

**技术亮点**:
- **多智能体协作网络**: 采用有向无环图等拓扑结构支持大规模智能体间的语言交互与任务导向协作，支持上千智能体协作而不超出上下文限制。
- **可学习的中央编排器**: 在`puppeteer`分支中，引入了基于强化学习优化的中央编排器，能动态激活和排序智能体，构建高效、上下文感知的推理路径，提升推理质量并降低计算成本。
- **迭代经验精炼**: 引入“迭代经验精炼”方法，通过指导者和助手智能体获取、利用、传播和消除面向任务的经验，使多任务处理过程更短、更高效。

---
## 5. [ankitects/anki](https://github.com/ankitects/anki)
- **语言**: Rust
- **Stars**: 26,139
- **简介**: Anki is a smart spaced repetition flashcard program

### AI 总结
**简介**: Anki 是一款基于间隔重复算法的智能记忆卡片程序，旨在帮助用户高效记忆。

**核心功能**:
- 基于间隔重复算法，智能安排学习计划
- 支持创建和管理数字记忆卡片

**技术亮点**: 主要使用 Rust 语言开发，确保了高性能和可靠性。

---
## 6. [open-telemetry/opentelemetry-collector-contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib)
- **语言**: Go
- **Stars**: 4,344
- **简介**: Contrib repository for the OpenTelemetry Collector

### AI 总结
**简介**: OpenTelemetry Collector 的社区贡献组件仓库，用于存放不适合放入核心仓库的扩展组件。

**核心功能**:
- 提供大量由社区贡献的接收器（Receiver）、处理器（Processor）、导出器（Exporter）和扩展（Extension）组件。
- 作为官方发行版（contrib 版本）的一部分，与核心版一同发布，为用户提供更丰富的可观测性数据采集与处理能力。

**技术亮点**: 基于 Go 语言开发，采用 OpenTelemetry Collector 的插件化架构，允许开发者灵活扩展数据流水线。项目目前处于 Beta 阶段，拥有活跃的社区支持和持续集成流程。

---
## 7. [Canner/WrenAI](https://github.com/Canner/WrenAI)
- **语言**: TypeScript
- **Stars**: 13,885
- **简介**: ⚡️ GenBI (Generative BI) queries any database in natural language, generates accurate SQL (Text-to-SQL), charts (Text-to-Chart), and AI-powered business intelligence in seconds.

### AI 总结
**简介**: WrenAI 是一个开源的生成式商业智能（GenBI）代理，能够通过自然语言查询任何数据库，并在几秒钟内生成准确的 SQL、图表和 AI 驱动的商业智能分析。

**核心功能**:
- **自然语言查询数据**：支持用任何语言提问，自动生成精确的 SQL 查询和答案，降低 SQL 学习门槛。
- **生成式 BI 洞察**：AI 自动生成数据摘要、图表和报告，一键提供决策所需的上下文。
- **语义层**：通过 MDL 模型编码数据库模式、度量和关联，确保 LLM 输出的准确性和可控性。
- **API 集成**：提供 API 以便在应用程序中嵌入查询和图表生成功能，支持构建自定义代理、SaaS 功能和聊天机器人。

**技术亮点**: 项目采用 TypeScript 开发，其架构包含一个核心的语义引擎，作为 LLM 语义层的支柱，支持与多种大型语言模型（LLM）集成，并兼容包括 PostgreSQL、MySQL、BigQuery、Snowflake 等在内的主流数据库和数据仓库。

---
## 8. [pedramamini/Maestro](https://github.com/pedramamini/Maestro)
- **语言**: TypeScript
- **Stars**: 1,638
- **简介**: Agent Orchestration Command Center

### AI 总结
**简介**: Maestro 是一款跨平台的桌面应用，旨在通过键盘优先的设计，高效编排和管理多个AI代理与项目，实现并行开发和自动化任务执行。

**核心功能**:
- **并行多代理管理**：支持运行无限数量的AI代理和终端会话，每个代理拥有独立的工作空间和上下文。
- **自动运行与剧本**：基于文件系统的任务运行器，可批量处理Markdown清单，支持创建可重复的工作流程并自动执行。
- **Git工作树**：在隔离的分支上并行运行AI代理，实现无冲突的并行开发，并可一键创建PR。
- **群组聊天**：在单一对话中协调多个AI代理，由主持AI代理协调讨论并综合响应。
- **移动远程控制**：内置Web服务器，支持通过二维码在手机上监控和控制所有代理。
- **命令行界面**：提供完整的CLI，支持无头操作，可从cron作业或CI/CD管道运行剧本。

**技术亮点**: 基于TypeScript开发，采用键盘优先的响应式界面设计，支持与Claude Code、OpenAI Codex、OpenCode等多种AI工具无缝集成，并具备Git深度集成、会话自动发现及消息队列等高级功能。

---
## 9. [nvm-sh/nvm](https://github.com/nvm-sh/nvm)
- **语言**: Shell
- **Stars**: 91,239
- **简介**: Node Version Manager - POSIX-compliant bash script to manage multiple active node.js versions

### AI 总结
**简介**: nvm 是一个基于 POSIX 兼容 bash 脚本的 Node.js 版本管理器，允许用户在命令行中快速安装、切换和使用多个 Node.js 版本。

**核心功能**:
- 通过命令行快速安装和使用不同版本的 Node.js。
- 支持在多个活跃的 Node.js 版本之间轻松切换。
- 提供安装脚本，支持通过 cURL 或 Wget 一键安装和更新。
- 支持在多种 POSIX 兼容的 shell（如 bash、zsh）和平台（Unix、macOS、Windows WSL）上运行。

**技术亮点**: 采用纯 Shell 脚本实现，无需依赖其他语言环境；通过修改 shell 配置文件（如 `~/.bashrc`）实现环境变量的自动管理，确保版本切换的隔离性。

---
## 10. [microsoft/qlib](https://github.com/microsoft/qlib)
- **语言**: Python
- **Stars**: 36,510
- **简介**: Qlib is an AI-oriented Quant investment platform that aims to use AI tech to empower Quant Research, from exploring ideas to implementing productions. Qlib supports diverse ML modeling paradigms, including supervised learning, market dynamics modeling, and RL, and is now equipped with https://github.com/microsoft/RD-Agent to automate R&D process.

### AI 总结
**简介**: Qlib 是微软开源的、面向 AI 的量化投资平台，旨在利用人工智能技术赋能量化研究，从探索想法到实现生产部署。

**核心功能**:
- 支持多种机器学习建模范式，包括监督学习、市场动态建模和强化学习。
- 集成了 **RD-Agent**，这是一个基于大语言模型（LLM）的自主演进智能体框架，用于自动化量化研发过程，如因子挖掘和模型优化。
- 提供端到端的量化研究基础设施，包括数据处理、模型训练、回测和评估。

**技术亮点**:
- **多范式 AI 支持**: 整合了传统监督学习、时间序列模型（如 KRNN、HIST）以及强化学习框架。
- **自动化 R&D**: 通过 RD-Agent 实现 LLM 驱动的自动化因子发现与模型优化流程。
- **生产就绪**: 支持 Linux、Windows、macOS 多平台，提供完善的文档、测试和持续集成。

---
