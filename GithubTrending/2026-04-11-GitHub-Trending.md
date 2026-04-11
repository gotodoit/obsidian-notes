---
tags:
  - github-trending
  - daily
date: 2026-04-11
created: 2026-04-11T01:55:46.530Z
---

# 2026-04-11 GitHub Trending Top 10

## 1. [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **语言**: Python
- **Stars**: 99,794
- **简介**: Python tool for converting files and office documents to Markdown.

### AI 总结
**简介**: 由微软开发的 Python 工具，专注于将多种文件和办公文档（如 PDF、Word、Excel、PPT 等）高效地转换为适合大语言模型处理的 Markdown 格式。

**核心功能**:
- 支持广泛的文件格式转换，包括 PDF、Office 文档、图像、音频、HTML、压缩包、YouTube 视频字幕等。
- 提供命令行工具和 Python API 两种使用方式，支持文件路径输入和管道操作。
- 采用模块化设计，依赖项按需安装（如 `pip install 'markitdown[pdf, docx]'`），以优化安装体积。

**技术亮点**:
- 专为 LLM 和文本分析流程优化，转换时注重保留文档的核心结构（标题、列表、表格、链接等）。
- 提供 MCP 服务器，便于与 Claude Desktop 等 LLM 应用集成。
- 从 0.1.0 版本起，底层接口重构为完全基于二进制流处理，不再创建临时文件，提升了效率和兼容性。

---
## 2. [coleam00/Archon](https://github.com/coleam00/Archon)
- **语言**: TypeScript
- **Stars**: 15,670
- **简介**: The first open-source harness builder for AI coding. Make AI coding deterministic and repeatable.

### AI 总结
**简介**: Archon 是一个开源的 AI 编码工作流引擎，旨在通过定义 YAML 工作流，使 AI 编码过程变得确定性和可重复。

**核心功能**:
- **定义工作流**：将开发流程（如规划、实现、验证、代码审查、创建 PR）编码为 YAML 文件，确保每次执行步骤一致。
- **隔离运行**：每个工作流运行都在独立的 Git 工作树中进行，支持并行处理多个任务而互不冲突。
- **混合执行**：工作流可组合确定性节点（如 Bash 脚本、测试、Git 操作）与 AI 节点（如规划、代码生成、审查），仅在需要智能的地方使用 AI。
- **多平台便携**：工作流定义一次，即可通过 CLI、Web UI、Slack、Telegram 或 GitHub 等多种方式运行。

**技术亮点**:
- 使用 **TypeScript** 开发。
- 工作流设计理念类似于 **Dockerfile**（基础设施）和 **GitHub Actions**（CI/CD），但专注于 AI 编码流程。
- 提供交互式循环和人工审批节点，支持“设置后不管”的自动化体验。

---
## 3. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 52,274
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 构建的、具备自我学习和进化能力的 AI 代理框架。

**核心功能**:
- **多平台接入**：支持通过 Telegram、Discord、Slack、CLI 等多种方式交互，并保持跨平台对话连续性。
- **内置学习循环**：能够从经验中创建技能，并在使用中自我改进，具备记忆管理和会话搜索能力。
- **灵活的模型支持**：可无缝切换使用 Nous Portal、OpenRouter、OpenAI 等多种模型提供商，无代码锁定。
- **强大的调度与自动化**：内置定时任务调度器，支持用自然语言创建自动化任务（如每日报告）。
- **并行与委派**：可生成隔离的子代理并行处理任务，支持通过 RPC 调用工具编写 Python 脚本。
- **多样化部署**：支持在本地、Docker、SSH、Modal 等多种后端运行，成本低廉，可实现服务器无感知休眠。

**技术亮点**: 采用模块化设计，支持多种 LLM 提供商；集成了 Honcho 用户建模和 agentskills.io 开放标准；具备研究支持功能，如批量轨迹生成和 Atropos RL 环境。

---
## 4. [rowboatlabs/rowboat](https://github.com/rowboatlabs/rowboat)
- **语言**: TypeScript
- **Stars**: 11,747
- **简介**: Open-source AI coworker, with memory

### AI 总结
**简介**: Rowboat 是一个开源的、具备长期记忆功能的本地优先 AI 协作者，它能将你的工作内容转化为知识图谱并据此行动。

**核心功能**:
- **构建与利用知识图谱**：连接电子邮件和会议笔记，构建并维护一个可长期积累、可编辑的 Markdown 知识图谱。
- **智能辅助工作**：基于知识图谱上下文，自动生成简报、邮件、文档、PDF 幻灯片，并为会议做准备。
- **多模态交互**：支持语音输入/输出、语音备忘录，并能自动提取关键信息更新图谱。
- **本地优先与隐私**：所有数据默认存储在本地，确保隐私安全。

**技术亮点**:
- **技术栈**：基于 TypeScript 开发。
- **架构特点**：采用本地优先设计，使用与 Obsidian 兼容的 Markdown 笔记库作为“工作记忆”，透明且可手动编辑。
- **扩展性**：支持通过 API 密钥集成多种外部服务（如 Deepgram、ElevenLabs、Exa、Composio），并可通过 MCP 服务器连接更多工具。

---
## 5. [multica-ai/multica](https://github.com/multica-ai/multica)
- **语言**: TypeScript
- **Stars**: 6,142
- **简介**: The open-source managed agents platform. Turn coding agents into real teammates — assign tasks, track progress, compound skills.

### AI 总结
**简介**: Multica 是一个开源的托管智能体平台，旨在将编程智能体转变为真正的团队成员，实现任务分配、进度追踪和技能复用的自动化协作。

**核心功能**:
- **智能体即队友**: 像分配任务给同事一样将问题分配给智能体，它们会自主领取工作、编写代码、报告障碍并更新状态。
- **自主执行**: 完整的任务生命周期管理（排队、认领、开始、完成/失败），通过 WebSocket 进行实时进度流式传输。
- **可复用技能**: 每个解决方案都能成为团队可复用的技能，如部署、迁移、代码审查，持续增强团队能力。
- **统一运行时**: 单一仪表板管理所有计算资源，支持本地守护进程和云端运行时，自动检测可用 CLI 并实时监控。
- **多工作区**: 通过工作区级别的隔离，跨团队组织工作，每个工作区拥有独立的智能体、问题和设置。

**技术亮点**: 基于 TypeScript 开发，提供 Docker 自部署方案，支持与 Claude Code、Codex、OpenClaw、OpenCode 等多种智能体 CLI 集成，采用 WebSocket 实现实时通信。

---
## 6. [forrestchang/andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills)
- **语言**: Unknown
- **Stars**: 11,785
- **简介**: A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.

### AI 总结
**简介**: 一个名为 `CLAUDE.md` 的单一文件，旨在通过四大核心原则来改进 Claude Code 等 AI 编程助手的行为，使其代码生成更可靠、更简洁。

**核心功能**:
- **先思考后编码**: 要求 AI 明确陈述假设、呈现多种解读、在必要时提出质疑，并在困惑时主动寻求澄清。
- **简单至上**: 强制 AI 生成解决当前问题所需的最简代码，避免过度设计、不必要的抽象和功能蔓延。
- **精准修改**: 指令 AI 只修改与任务直接相关的代码，不擅自“改进”无关代码、注释或格式，并匹配现有代码风格。
- **目标驱动执行**: 将指令转化为可验证的成功标准（如先写测试再实现），使 AI 能够自主循环直到达成目标。

**技术亮点**: 提炼自 Andrej Karpathy 对 LLM 编程缺陷的观察，以一份轻量的配置文件（`CLAUDE.md`）作为“提示工程”的最佳实践，可全局安装为 Claude Code 插件，也可按项目单独配置。

---
## 7. [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos)
- **语言**: Python
- **Stars**: 12,729
- **简介**: Kronos: A Foundation Model for the Language of Financial Markets

### AI 总结
**简介**: Kronos 是首个面向金融市场K线序列的开源基础模型，专门用于理解和预测金融时间序列数据。

**核心功能**:
- 提供不同参数规模的预训练模型（mini, small, base），可直接用于金融预测任务。
- 包含一个专门为多维K线数据（OHLCV）设计的层级化分词器，将连续数据转化为离散token。
- 支持通过微调脚本，将模型适配到用户自定义的量化任务上。
- 提供在线演示，可实时可视化模型对BTC/USDT等交易对的未来价格预测。

**技术亮点**: 采用两阶段框架，先由专用分词器量化数据，再由仅解码器的自回归Transformer进行预训练，专门处理金融数据的高噪声特性。模型在超过45个全球交易所的数据上训练。

---
## 8. [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)
- **语言**: Python
- **Stars**: 16,003
- **简介**: "DeepTutor: Agent-Native Personalized Learning Assistant"

### AI 总结
**简介**: DeepTutor 是一个基于智能体原生架构的个性化AI辅导助手，旨在提供灵活、持久且可交互的学习体验。

**核心功能**:
- **TutorBot**: 支持多通道（如Discord、飞书、微信）的持久性自主AI导师，可进行个性化辅导。
- **多种学习模式**: 提供指导式学习、协同写作等不同交互模式，并支持灵活切换。
- **强大的RAG与知识库**: 支持增量文档上传、可配置的RAG管道，并能从多种文档格式中提取知识。
- **个性化评估与练习**: 具备防重复的测验生成能力，并支持学习进度跟踪与可视化。

**技术亮点**:
- **智能体原生架构**: 采用两层插件模型（工具+能力），支持CLI和SDK入口，实现了约20万行的架构重写。
- **现代化技术栈**: 后端基于Python 3.11+，前端使用Next.js 16，并支持多种大语言模型和嵌入模型提供商。
- **国际化与社区**: 提供多语言界面（包括完整中文支持），并拥有活跃的Discord、微信等社区生态。

---
## 9. [opendataloader-project/opendataloader-pdf](https://github.com/opendataloader-project/opendataloader-pdf)
- **语言**: Java
- **Stars**: 14,822
- **简介**: PDF Parser for AI-ready data. Automate PDF accessibility. Open-source.

### AI 总结
**简介**: 一个用于从PDF中提取AI就绪结构化数据并自动化PDF可访问性合规的开源Java解析器。

**核心功能**:
- **数据提取**: 支持从数字、扫描和标记PDF中提取Markdown、JSON（带边界框）和HTML，专为RAG/LLM管道设计。
- **可访问性自动化**: 提供端到端的布局分析和自动标记功能，可将未标记PDF转换为符合规范的标记PDF（Tagged PDF）。

**技术亮点**:
- **高性能与准确性**: 在基准测试中综合提取准确率排名第一（0.907），表格提取准确率达0.928，本地模式处理速度为0.015秒/页。
- **混合AI模式**: 结合确定性本地模式与AI混合模式，以处理复杂页面、扫描件OCR（80+语言）、无边框表格和公式。
- **行业标准合规**: 与PDF协会及Dual Lab（veraPDF）合作开发，遵循“良好标记PDF”规范，输出可通过veraPDF自动验证。
- **多语言SDK**: 提供Python、Node.js和Java SDK，并支持LangChain集成。

---
## 10. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 145,806
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个基于可组合“技能”的智能体驱动软件开发框架与工作流，旨在引导编码智能体（如 Claude、Cursor 等）以结构化、自动化的方式完成从设计到实现的完整开发过程。

**核心功能**:
- **结构化工作流**：提供从需求澄清、设计规划、任务分解到代码实现的完整自动化流程，包括头脑风暴、Git工作树管理、计划编写、子智能体驱动开发等强制执行的步骤。
- **技能库驱动**：内置一系列可自动触发的核心技能，例如测试驱动开发（TDD）、代码审查请求、开发分支收尾等，确保开发过程遵循最佳实践（如YAGNI、DRY）。
- **多平台支持**：支持在 Claude Code、Cursor、Codex、OpenCode、GitHub Copilot CLI、Gemini CLI 等多种AI编码助手和平台上安装与运行。

**技术亮点**:
- **子智能体驱动开发**：通过创建独立的子智能体来执行具体任务，并进行两阶段审查（规范符合性、代码质量），实现长时间自主、不偏离计划的开发。
- **强调工程实践**：强制推行真正的红/绿TDD循环、最小化实现（YAGNI）和代码复用（DRY），并将设计拆解为易于验证的微小任务。

---
