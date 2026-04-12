---
tags:
  - github-trending
  - daily
date: 2026-04-12
created: 2026-04-12T01:55:47.525Z
---

# 2026-04-12 GitHub Trending Top 10

## 1. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 59,224
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 构建的、具备自我学习能力的 AI 代理，能够随着使用不断成长。

**核心功能**:
- **多平台接入**: 支持通过 Telegram、Discord、Slack、WhatsApp、Signal 以及 CLI 等多种方式与代理交互。
- **内置学习循环**: 代理能够从经验中创建技能，在使用中改进技能，并建立跨会话的用户模型。
- **灵活的模型支持**: 可无缝切换使用 Nous Portal、OpenRouter、OpenAI 等多种模型服务或自定义端点。
- **强大的调度与并行**: 内置定时任务调度器，并能派生子代理进行并行工作流处理。
- **随处运行**: 支持在本地、Docker、SSH、Modal 等多种后端运行，成本可控。

**技术亮点**: 采用模块化设计，支持多种 LLM 提供商；集成了 Honcho 用户建模和 agentskills.io 开放标准；提供完整的终端用户界面和跨会话的语义搜索与总结能力。

---
## 2. [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **语言**: Python
- **Stars**: 102,314
- **简介**: Python tool for converting files and office documents to Markdown.

### AI 总结
**简介**: 一个由微软开发的轻量级 Python 工具，专注于将多种文件和办公文档（如 PDF、Word、Excel、PPT 等）转换为结构化的 Markdown 格式，以便于大语言模型（LLM）和文本分析管道使用。

**核心功能**:
- 支持广泛的文件格式转换，包括 PDF、Office 文档、图像、音频、HTML、压缩包、YouTube 视频字幕、EPub 等。
- 提供命令行工具和 Python API 两种使用方式，支持文件路径输入和管道操作。
- 通过可选的依赖项分组（如 `[pdf]`, `[docx]`）实现按需安装，保持核心轻量化。
- 集成了 MCP（Model Context Protocol）服务器，便于与 Claude Desktop 等 LLM 应用集成。

**技术亮点**:
- 采用面向 LLM 的设计理念，输出注重保留文档结构（标题、列表、表格、链接等）且 Token 高效的 Markdown。
- 依赖管理灵活，通过 `pip install 'markitdown[all]'` 可一键安装全部转换器依赖。
- 从 0.1.0 版本起，底层接口改为直接处理二进制流，不再创建临时文件，提升了效率。

---
## 3. [coleam00/Archon](https://github.com/coleam00/Archon)
- **语言**: TypeScript
- **Stars**: 16,487
- **简介**: The first open-source harness builder for AI coding. Make AI coding deterministic and repeatable.

### AI 总结
**简介**: Archon 是一个开源的 AI 编码工作流引擎，旨在通过定义 YAML 工作流，使 AI 编码过程变得确定且可重复。

**核心功能**:
- **定义工作流**：将开发流程（如规划、实现、验证、代码审查、创建 PR）编码为 YAML 文件，确保每次执行的结构和顺序一致。
- **智能与确定性结合**：在流程中混合使用确定性节点（如 bash 脚本、测试、git 操作）和 AI 节点（如规划、代码生成、审查），AI 仅在能增加价值的环节运行。
- **隔离与并行**：每个工作流运行都在独立的 git 工作树中进行，支持并行处理多个任务而互不冲突。
- **多平台触发**：工作流定义一次后，可通过 CLI、Web UI、Slack、Telegram 或 GitHub 等多种方式触发和运行。

**技术亮点**:
- 使用 TypeScript 开发。
- 工作流设计理念借鉴了 Dockerfile（基础设施）和 GitHub Actions（CI/CD），并将其应用于 AI 编码领域。
- 提供交互式节点，支持在流程中暂停并等待人工输入（如审批环节）。

---
## 4. [forrestchang/andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills)
- **语言**: Unknown
- **Stars**: 13,680
- **简介**: A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.

### AI 总结
**简介**: 一个受 Andrej Karpathy 启发的 `CLAUDE.md` 文件，旨在通过四大核心原则来改进 Claude Code 的编码行为，解决大语言模型在编程中常见的错误假设、过度设计等问题。

**核心功能**:
- **先思考后编码**：强制模型明确陈述假设、呈现多种解释，并在必要时寻求澄清，避免隐藏困惑。
- **简单性优先**：倡导用最少的代码解决问题，反对过度工程化、添加未请求的特性或抽象。
- **精准修改**：要求只修改与任务直接相关的代码，不触碰无关的代码、注释或格式，并清理自己造成的冗余。
- **目标驱动执行**：将指令转化为可验证的成功标准（如先写测试再实现），使模型能自主循环直至目标达成。

**技术亮点**: 该方案并非一个技术栈，而是一套行为准则。其核心洞察在于利用大语言模型擅长“循环直至满足特定目标”的特性，通过定义清晰的验证标准来引导其行为，从而生成更简洁、精准且符合预期的代码。

---
## 5. [multica-ai/multica](https://github.com/multica-ai/multica)
- **语言**: TypeScript
- **Stars**: 7,981
- **简介**: The open-source managed agents platform. Turn coding agents into real teammates — assign tasks, track progress, compound skills.

### AI 总结
**简介**: Multica 是一个开源的托管智能体平台，旨在将编码智能体转变为真正的团队成员，实现任务分配、进度追踪和技能复用的自动化协作。

**核心功能**:
- **智能体即队友**：可像分配任务给同事一样将问题分配给智能体，智能体拥有个人资料，能主动在面板上显示、发表评论、创建问题并报告阻塞。
- **自主执行**：支持完整的任务生命周期管理（排队、认领、开始、完成/失败），并通过 WebSocket 进行实时进度流式传输。
- **可复用技能**：每个解决方案都能转化为团队可复用的技能，如部署、迁移、代码审查，从而随时间积累团队能力。
- **统一运行时**：通过单一仪表板管理所有计算资源，支持本地守护进程和云运行时，自动检测可用 CLI 并提供实时监控。
- **多工作区**：通过工作区级别的隔离，跨团队组织工作，每个工作区拥有独立的智能体、问题和设置。

**技术亮点**: 基于 TypeScript 开发，提供 CLI 工具和 Web 应用，支持自托管（需 Docker），兼容 Claude Code、Codex、OpenClaw 和 OpenCode 等多种智能体提供商。

---
## 6. [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice)
- **语言**: HTML
- **Stars**: 37,119
- **简介**: practice made claude perfect

### AI 总结
**简介**: 这是一个关于 Claude Code 最佳实践的集合项目，旨在通过实践帮助开发者从氛围编码过渡到智能体工程。

**核心功能**:
- **子代理 (Subagents)**: 在独立上下文中运行的自主智能体，可自定义工具、权限和模型。
- **命令 (Commands)**: 用户可调用的提示模板，用于编排工作流。
- **技能 (Skills)**: 可配置、可预加载的知识模块，支持上下文分叉和渐进式披露。
- **工作流 (Workflows)**: 通过命令（如天气编排器）实现的复杂任务自动化流程。
- **钩子 (Hooks)**: 在特定事件（如智能体循环外）运行的用户自定义处理器。
- **MCP 服务器**: 通过模型上下文协议连接外部工具、数据库和 API。
- **插件 (Plugins)**: 可分发的能力包，包含技能、子代理、钩子等。
- **设置 (Settings)**: 分层级的配置系统，用于管理权限、模型、输出风格等。

**技术亮点**: 项目围绕 Claude Code 的智能体架构构建，强调通过子代理、命令、技能和工作流等模块化组件实现复杂的工程化智能体应用，并支持通过 MCP 协议进行扩展。

---
## 7. [TapXWorld/ChinaTextbook](https://github.com/TapXWorld/ChinaTextbook)
- **语言**: Roff
- **Stars**: 67,803
- **简介**: 所有小初高、大学PDF教材。

### AI 总结
**简介**: 一个旨在免费、开源地提供中国小学、初中、高中及大学全套PDF教材的项目，以促进教育资源的普及和公平获取。

**核心功能**:
- **集中提供教材资源**：汇集了从小学到大学各年级、各学科（如数学）的官方PDF版教材，方便用户直接下载。
- **促进教育公平**：通过开源方式，对抗部分人利用公共教育资源牟利的行为，降低获取门槛，尤其服务于教育资源匮乏地区和海外华人家庭。

**技术亮点**: 项目本身不涉及复杂的技术栈，其核心价值在于资源的整理、归类与开源共享。项目结构清晰，按学段（小学、初中等）、学科和出版社（如人教版）组织文件，便于导航和使用。

---
## 8. [OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM)
- **语言**: Python
- **Stars**: 9,934
- **简介**: VoxCPM2: Tokenizer-Free TTS for Multilingual Speech Generation, Creative Voice Design, and True-to-Life Cloning

### AI 总结
**简介**: VoxCPM2 是一个无需分词器的端到端文本转语音系统，支持多语言语音生成、创意语音设计和逼真声音克隆。

**核心功能**:
- **多语言支持**: 支持30种语言及多种中国方言的文本输入与直接合成。
- **创意语音设计**: 仅通过自然语言描述（如性别、年龄、语调）即可生成全新声音，无需参考音频。
- **可控声音克隆**: 通过短音频片段克隆声音，并可引导情感、语速等风格，同时保留原始音色。
- **高质量音频输出**: 直接生成48kHz高品质音频，内置超分辨率，无需外部上采样器。
- **实时流式合成**: 在高端GPU上可实现实时合成。

**技术亮点**: 基于 **MiniCPM-4** 骨干网络，采用 **扩散自回归架构** 直接生成连续语音表示，避免了离散分词。模型参数量为20亿，在超过200万小时的多语言语音数据上训练。

---
## 9. [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos)
- **语言**: Python
- **Stars**: 14,316
- **简介**: Kronos: A Foundation Model for the Language of Financial Markets

### AI 总结
**简介**: Kronos 是首个专注于金融市场K线图序列的开源基础模型，旨在理解和预测金融时间序列数据。

**核心功能**:
- **金融K线序列建模**: 专门处理包含开盘价、最高价、最低价、收盘价和成交量（OHLCV）的多维、高噪声金融数据。
- **多任务统一框架**: 作为一个预训练的基础模型，可应用于多种量化任务，如价格预测、异常检测等。
- **提供在线演示**: 设有实时演示页面，可可视化模型对BTC/USDT等交易对的价格预测结果。

**技术亮点**:
- **两阶段架构**: 1) 使用专门的Tokenizer将连续K线数据量化为分层离散令牌；2) 基于自回归Transformer进行预训练。
- **开源模型系列**: 在Hugging Face上发布了不同参数规模（如4.1M到499.2M）的预训练模型，供社区使用和微调。
- **大规模数据训练**: 基于全球超过45个交易所的数据进行训练。

---
## 10. [opendataloader-project/opendataloader-pdf](https://github.com/opendataloader-project/opendataloader-pdf)
- **语言**: Java
- **Stars**: 15,632
- **简介**: PDF Parser for AI-ready data. Automate PDF accessibility. Open-source.

### AI 总结
**简介**: 一个开源的 Java PDF 解析器，专注于为 AI 提供结构化数据并自动化 PDF 可访问性处理。

**核心功能**:
- **AI 数据提取**：从数字、扫描或已标记的 PDF 中提取 Markdown、JSON（含元素边界框）、HTML 等格式，支持 RAG/LLM 管道。
- **PDF 可访问性自动化**：提供布局分析和自动标记功能，可将无标签 PDF 转换为符合规范的“标记 PDF”，并计划支持 PDF/UA 导出。

**技术亮点**:
- **基准测试领先**：在混合模式下总体提取准确率达 0.907，表格提取准确率达 0.928。
- **混合模式**：结合确定性本地处理与 AI 增强，以处理复杂页面、扫描件、表格和公式。
- **开放标准与协作**：与 PDF 协会及 veraPDF 团队合作，遵循“良好标记 PDF”规范。
- **多语言 SDK**：提供 Python、Node.js 和 Java SDK，易于集成。

---
