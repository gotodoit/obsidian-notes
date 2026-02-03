---
tags:
  - github-trending
  - daily
date: 2026-02-03
created: 2026-02-03T22:31:47.383Z
---

# 2026-02-03 GitHub Trending Top 10

> [!INFO]
> 本日报由 AI 自动生成，精选 GitHub Trending 前 10 项目。

## 1. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 20,057
- **简介**: A Claude Code plugin that automatically captures everything Claude does during your coding sessions, compresses it with AI (using Claude's agent-sdk), and injects relevant context back into future sessions.

### AI 总结
**简介**: 一个为 Claude Code 设计的持久化记忆压缩系统插件，能自动捕获编码会话中的所有操作，利用 AI 进行压缩，并在未来的会话中注入相关上下文。

**核心功能**:
- 自动捕获 Claude 在编码会话中的所有操作和观察结果。
- 使用 AI（基于 Claude 的 agent-sdk）对捕获的内容进行语义压缩和总结。
- 将压缩后的记忆作为上下文，智能地注入到未来的 Claude Code 会话中，实现跨会话的知识连续性。

**技术亮点**: 基于 TypeScript 开发，集成了 Claude 的 agent-sdk 进行 AI 驱动的语义总结和上下文管理。

---
## 2. [masoncl/review-prompts](https://github.com/masoncl/review-prompts)
- **语言**: Python
- **Stars**: 306
- **简介**: AI review prompts

### AI 总结
**简介**: 一个为 Linux 内核和 systemd 开发提供 AI 辅助代码审查提示词的项目。

**核心功能**:
- 提供针对 Linux 内核和 systemd 项目的专用 AI 审查、调试和验证提示词。
- 通过安装脚本快速集成到 Claude Code 等 AI 工具中。
- 支持智能上下文加载，根据工作目录自动加载对应项目的知识和技能。

**技术亮点**:
- 采用“技能文件”和“斜杠命令”架构，实现按需加载领域特定知识。
- 与 semcode 工具集成，优化代码导航和语义搜索体验。
- 项目结构清晰，包含详细的子系统文档和常见错误模式库。

---
## 3. [openai/skills](https://github.com/openai/skills)
- **语言**: Python
- **Stars**: 2,955
- **简介**: Skills Catalog for Codex

### AI 总结
**简介**: OpenAI 的 Codex AI 代理技能目录，包含可复用的指令、脚本和资源包，用于帮助 AI 代理完成特定任务。

**核心功能**:
- 提供预构建的技能包，涵盖系统、精选和实验性类别，供 AI 代理直接发现和使用。
- 支持通过 `$skill-installer` 命令在 Codex 中便捷地安装和管理技能。
- 遵循 Agent Skills 开放标准，实现“一次编写，随处使用”的共享能力。

**技术亮点**: 基于 Python 实现，采用模块化的文件夹结构组织技能，并与 GitHub 仓库深度集成，便于技能的分发和版本管理。

---
## 4. [automazeio/ccpm](https://github.com/automazeio/ccpm)
- **语言**: Shell
- **Stars**: 6,671
- **简介**: Project management system for Claude Code using GitHub Issues and Git worktrees for parallel agent execution.

### AI 总结
**简介**: 一个基于 GitHub Issues 和 Git worktrees 的 Claude Code 项目管理与并行执行系统，旨在通过规范驱动开发来提升协作效率和代码质量。

**核心功能**:
- 将产品需求文档（PRD）分解为史诗和 GitHub Issues，实现从需求到代码的完整可追溯性。
- 利用 Git worktrees 支持多个 AI 代理并行执行不同的任务，避免工作阻塞。
- 以 GitHub Issues 作为协作中心，实现人机无缝交接和团队透明协作。

**技术亮点**: 采用 Shell 脚本实现，核心架构结合了 GitHub Issues（作为状态和上下文数据库）与 Git worktrees（实现并行开发），强调规范驱动而非随意编码。

---
## 5. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 43,443
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个基于可组合“技能”的智能体驱动软件开发框架与工作流，旨在引导编码智能体（如 Claude、Codex、OpenCode）进行系统化、高质量的软件开发。

**核心功能**:
- **交互式设计**：通过提问和对话提炼需求，并以可消化的小块呈现设计方案供用户确认。
- **结构化实施**：在批准设计后，创建强调TDD、YAGNI和DRY原则的详细、分步实施计划。
- **子智能体驱动开发**：启动子智能体按计划执行工程任务，并进行两阶段审查（规范符合性、代码质量），支持长时间自主工作。
- **自动化技能触发**：在任务执行前自动检查并应用相关技能（如测试驱动开发、系统化调试、代码审查、Git工作树管理等），形成强制性工作流。

**技术亮点**: 框架设计为可组合的技能库，支持通过插件市场（Claude Code）或手动配置（Codex、OpenCode）安装，实现了与不同编码智能体平台的无缝集成。

---
## 6. [virattt/dexter](https://github.com/virattt/dexter)
- **语言**: TypeScript
- **Stars**: 10,047
- **简介**: An autonomous agent for deep financial research

### AI 总结
**简介**: Dexter 是一个用 TypeScript 编写的自主金融研究智能体，能够将复杂的金融问题分解为可执行的研究任务，并利用实时市场数据进行分析和验证。

**核心功能**:
- **智能任务规划**：自动将复杂查询分解为结构化的研究步骤。
- **自主执行与验证**：选择并执行工具来收集金融数据，并能自我检查工作结果并进行迭代优化。
- **实时数据接入**：可访问损益表、资产负债表和现金流量表等实时金融数据。
- **安全控制**：内置循环检测和步骤限制，防止执行失控。

**技术亮点**:
- 基于 **Bun** 运行时环境。
- 支持多种大模型 API（OpenAI、Anthropic、Google、xAI、OpenRouter）及本地 **Ollama**。
- 集成 **Financial Datasets API** 获取金融数据，并可选配 **Exa** 或 **Tavily** 进行网络搜索。
- 包含完整的评估套件，使用 **LangSmith** 进行跟踪和“LLM 即裁判”的评分方法。
- 详细的调试支持，所有工具调用和推理步骤均以 JSONL 格式记录在 `.dexter/scratchpad/` 目录中。

---
## 7. [karpathy/nanochat](https://github.com/karpathy/nanochat)
- **语言**: Python
- **Stars**: 41,992
- **简介**: The best ChatGPT that $100 can buy.

### AI 总结
**简介**: nanochat 是一个极简、可修改的实验框架，用于在单GPU节点上训练大型语言模型（LLM），覆盖从分词、预训练、微调到评估、推理和聊天界面的全流程。

**核心功能**:
- 提供完整的LLM训练与部署流程，包括预训练、微调、评估和推理。
- 包含一个类似ChatGPT的Web聊天界面，可与训练好的模型交互。
- 通过 `runs/speedrun.sh` 脚本，可在约3小时内以约73美元的成本复现GPT-2级别模型的训练。

**技术亮点**:
- 代码简洁、易于修改，基于PyTorch实现。
- 支持多GPU（如8×H100）训练，也可在单GPU上通过梯度累积运行。
- 项目持续优化，通过FP8等新技术提升训练效率，并维护性能排行榜追踪“达到GPT-2水平所需时间”。

---
## 8. [kovidgoyal/calibre](https://github.com/kovidgoyal/calibre)
- **语言**: Python
- **Stars**: 23,918
- **简介**: The official source code repository for the calibre ebook manager

### AI 总结
**简介**: Calibre 是一个功能强大、跨平台的开源电子书管理工具。

**核心功能**:
- **电子书管理**: 支持查看、转换、编辑和编目所有主流电子书格式。
- **设备同步**: 可与电子书阅读器设备进行通信和传输。
- **元数据获取**: 能够从互联网自动获取书籍的元数据信息。
- **新闻下载**: 可以下载报纸并将其转换为电子书，便于阅读。

**技术亮点**: 项目使用 Python 语言开发，支持 Linux、Windows 和 macOS 三大操作系统，拥有完整的持续集成（CI）流程和活跃的社区支持。

---
## 9. [OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev)
- **语言**: Python
- **Stars**: 29,758
- **简介**: ChatDev 2.0: Dev All through LLM-powered Multi-Agent Collaboration

### AI 总结
**简介**: ChatDev 2.0 (DevAll) 是一个零代码的多智能体编排平台，旨在通过大语言模型驱动的多智能体协作，让用户无需编程即可快速构建和执行定制化的复杂任务系统。

**核心功能**:
- **零代码多智能体平台**：用户通过简单配置即可定义智能体、工作流和任务，无需编写代码。
- **开发一切**：能够编排复杂场景，如数据可视化、3D生成和深度研究等多样化任务。
- **多智能体协作**：支持智能体（如CEO、CTO、程序员等）通过功能研讨会进行协作，自动化软件开发生命周期（设计、编码、测试、文档编写）。

**技术亮点**:
- **多智能体协作网络**：采用有向无环图（MacNet）支持大规模智能体间的语言交互与任务导向协作。
- **可学习的中央编排器**：基于强化学习优化的编排器，能动态激活和排序智能体，构建高效、上下文感知的推理路径。
- **经验迭代优化**：引入“迭代经验精炼”方法，通过指导者与助手智能体优化经验，高效适应新任务。

---
## 10. [pedramamini/Maestro](https://github.com/pedramamini/Maestro)
- **语言**: TypeScript
- **Stars**: 1,480
- **简介**: Agent Orchestration Command Center

### AI 总结
**简介**: Maestro 是一款面向键盘操作的高级用户的跨平台桌面应用，旨在高效编排和管理多个AI代理与项目，实现并行开发和自动化任务执行。

**核心功能**:
- **Git Worktrees**: 支持在隔离的分支上并行运行AI代理，实现无冲突的并行开发。
- **Auto Run & Playbooks**: 基于文件系统的任务运行器，可批量处理Markdown清单，支持可重复的工作流程和长时间无人值守运行。
- **Group Chat**: 在单一对话中协调多个AI代理，由主持AI编排讨论并综合响应。
- **Mobile Remote Control**: 内置Web服务器，可通过手机远程监控和控制所有代理。
- **Command Line Interface**: 提供完整的CLI，支持无头操作和脚本集成。
- **Multi-Agent Management**: 并行运行无限代理和终端会话，每个代理拥有独立的工作区和上下文。
- **Dual-Mode Sessions**: 每个代理同时具备AI终端和命令终端，支持无缝切换。

**技术亮点**: 基于TypeScript开发，采用键盘优先设计，支持可扩展的斜杠命令、强大的输出过滤、Git深度集成以及会话自动发现与导入。

---
