---
tags:
  - github-trending
  - daily
date: 2026-04-10
created: 2026-04-10T01:55:48.061Z
---

# 2026-04-10 GitHub Trending Top 10

## 1. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 44,899
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 开发的自进化 AI 代理，其核心特点是内置了学习循环，能够从经验中创建并改进技能，实现跨会话的持续学习和个性化。

**核心功能**:
- **多平台接入**：支持通过 Telegram、Discord、Slack、CLI 等多种方式与代理交互，实现跨平台对话连续性。
- **自我进化与记忆**：具备代理策划的记忆系统，能自主创建技能并在使用中自我改进，支持跨会话的全文搜索和 LLM 摘要回忆。
- **灵活部署与模型支持**：可在多种环境（如本地、Docker、SSH、无服务器平台）运行，并支持切换多个主流模型提供商（如 Nous Portal、OpenRouter、OpenAI 等），无需更改代码。
- **自动化与并行处理**：内置定时任务调度器，可生成自然语言报告；支持生成隔离的子代理进行并行工作流处理。
- **研究友好**：提供批量轨迹生成、强化学习环境和轨迹压缩等功能，便于训练下一代工具调用模型。

**技术亮点**: 采用模块化设计，支持多种终端后端和无服务器架构（如 Modal），实现低成本休眠与按需唤醒；兼容 `agentskills.io` 开放标准，并集成了用于用户建模的 Honcho 技术。

---
## 2. [forrestchang/andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills)
- **语言**: Unknown
- **Stars**: 10,531
- **简介**: A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.

### AI 总结
**简介**: 一个受 Andrej Karpathy 启发的 `CLAUDE.md` 文件，旨在通过四项核心原则来改进 Claude Code 的编码行为，解决 LLM 常见的编码陷阱。

**核心功能**:
- **思考先行**: 强制模型在编码前明确陈述假设、呈现多种解释，并在必要时请求澄清，避免隐藏的困惑和错误的假设。
- **简洁至上**: 倡导用最少的代码解决问题，反对过度工程化、添加未请求的功能或创建不必要的抽象。
- **精准修改**: 要求只修改与任务直接相关的代码，不“顺手”重构或清理无关的现有代码和注释，保持代码风格的统一。
- **目标驱动**: 将指令转化为可验证的成功标准（如先写测试再实现），使模型能够自主循环直到目标达成，减少反复澄清。

**技术亮点**: 该方案并非一个技术栈，而是一套行为准则。其核心亮点在于将 Karpathy 对 LLM 编码缺陷的观察提炼为可操作的、原则性的指导文件（`CLAUDE.md`），并提供了便捷的安装方式（可作为 Claude Code 插件全局安装，或作为项目级配置文件），从而系统性地提升 AI 编程助手的输出质量和可控性。

---
## 3. [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)
- **语言**: Python
- **Stars**: 14,932
- **简介**: "DeepTutor: Agent-Native Personalized Learning Assistant"

### AI 总结
**简介**: DeepTutor 是一个基于智能体原生架构的个性化 AI 辅导助手，旨在提供灵活、持久且个性化的学习体验。

**核心功能**:
- **TutorBot**: 支持多通道（如 Discord、飞书、微信）的持久化自主 AI 导师，能够进行长期、个性化的辅导。
- **灵活模式切换**: 提供多种交互模式，包括 CLI（命令行界面）、SDK 以及 Web 界面（基于 Next.js 16）。
- **个性化学习模块**: 包含协同写作（Co-Writer）、引导式学习（Guided Learning）以及基于记忆的持久化会话。
- **强大的知识处理**: 支持增量文档上传、灵活的 RAG（检索增强生成）管道以及多格式文档解析（如通过 Docling 实现 RAG-Anything）。

**技术亮点**:
- **智能体原生架构**: 采用两层插件模型（工具 + 能力），进行了彻底的重构。
- **多模型与供应商支持**: 原生集成 OpenAI、Anthropic 等多家 LLM 和嵌入模型供应商，无需依赖 LiteLLM。
- **技术栈**: 后端主要使用 Python (3.11+)，前端使用 Next.js 16，采用 Apache 2.0 开源协议。
- **国际化与本地化**: 提供包括中文在内的多语言完整覆盖，并拥有活跃的社区支持（Discord、微信、飞书等）。

---
## 4. [OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM)
- **语言**: Python
- **Stars**: 7,705
- **简介**: VoxCPM2: Tokenizer-Free TTS for Multilingual Speech Generation, Creative Voice Design, and True-to-Life Cloning

### AI 总结
**简介**: VoxCPM2 是一个无需分词器的端到端文本转语音系统，支持多语言语音生成、创意语音设计和逼真声音克隆。

**核心功能**:
- **多语言合成**: 支持30种语言及多种中文方言，无需语言标签即可直接合成。
- **创意语音设计**: 仅通过自然语言描述（如性别、年龄、语调）即可生成全新音色，无需参考音频。
- **可控声音克隆**: 通过短音频片段克隆音色，并可控制情感、语速等风格，同时保持原音色。
- **高保真克隆**: 结合参考音频及其文本转录，能无缝延续并精确复现原声的所有细节（音色、节奏、情感）。
- **高质量音频**: 直接输出48kHz高品质音频，内置超分辨率，无需外部上采样。

**技术亮点**: 基于 **MiniCPM-4** 主干网络，采用 **无分词器的扩散自回归架构**，直接生成连续语音表示。模型参数量为 **2B**，在超过 **200万小时** 的多语言语音数据上训练，支持实时流式合成。

---
## 5. [opendataloader-project/opendataloader-pdf](https://github.com/opendataloader-project/opendataloader-pdf)
- **语言**: Java
- **Stars**: 13,858
- **简介**: PDF Parser for AI-ready data. Automate PDF accessibility. Open-source.

### AI 总结
**简介**: 一个开源的 Java PDF 解析器，专注于为 AI 提供结构化数据并自动化 PDF 可访问性处理。

**核心功能**:
- **AI 数据提取**：支持从数字、扫描或已标记的 PDF 中提取 Markdown、JSON（含元素边界框）、HTML 等格式，专为 RAG/LLM 管道设计。
- **自动化可访问性处理**：提供端到端的布局分析和自动标记功能，可将无标签 PDF 转换为符合规范的“标记 PDF”（Tagged PDF）。

**技术亮点**:
- **高性能与高精度**：在基准测试中综合提取准确率排名第一（0.907），表格提取准确率达 0.928，本地模式处理速度达 0.015 秒/页。
- **混合 AI 模式**：结合确定性本地处理与 AI 增强，以处理复杂页面、扫描件（内置 OCR）、无边框表格和公式。
- **标准化与验证**：与 PDF 协会及 veraPDF 团队合作，遵循“良好标记 PDF”规范，输出可通过自动化工具验证。
- **多语言 SDK**：提供 Python、Node.js 和 Java SDK，易于集成。

---
## 6. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 143,820
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为 AI 编程代理设计的、基于可组合“技能”的软件开发框架和工作流，旨在引导代理进行系统化、高质量的开发。

**核心功能**:
- **智能引导与规划**：在编码前，通过对话明确需求，并生成易于审阅的设计文档和详细的、分步的工程实施计划。
- **子代理驱动开发**：通过启动子代理来执行计划中的每个独立任务，并进行两阶段审查（规范符合性与代码质量），实现长时间自主工作。
- **强制最佳实践**：强制执行测试驱动开发、YAGNI、DRY等原则，确保代码质量。
- **集成化工作流**：提供从头脑风暴、Git工作区管理、计划执行到代码审查和分支收尾的完整、自动化开发流程。

**技术亮点**:
- **技能库架构**：核心是一套可组合、自动触发的“技能”，代理在任务前会自动检查并应用相关技能，将方法论固化为强制工作流。
- **多平台支持**：支持 Claude Code、Cursor、Codex、OpenCode、GitHub Copilot CLI 和 Gemini CLI 等多种AI编码平台和工具。

---
## 7. [TheCraigHewitt/seomachine](https://github.com/TheCraigHewitt/seomachine)
- **语言**: Python
- **Stars**: 5,224
- **简介**: A specialized Claude Code workspace for creating long-form, SEO-optimized blog content for any business. This system helps you research, write, analyze, and optimize content that ranks well and serves your target audience.

### AI 总结
**简介**: SEO Machine 是一个基于 Claude Code 构建的、用于为任何企业创建长篇 SEO 优化博客内容的专业工作空间。

**核心功能**:
- **全流程内容管理**: 提供从 `/research`（研究）、`/write`（撰写）、`/analyze-existing`（分析现有内容）到 `/optimize`（优化）和 `/publish-draft`（发布草稿）的完整命令集。
- **专业化智能代理**: 集成了内容分析、SEO优化、元标签创建、内链建议、关键词映射、性能分析、标题生成等众多自动化代理。
- **深度SEO与数据分析**: 支持搜索意图识别、关键词密度分析、可读性评分、SEO质量评级，并能集成 Google Analytics、Google Search Console 和 DataForSEO API 获取实时性能洞察。
- **品牌化与上下文驱动**: 通过自定义品牌声音、风格指南、SEO指南和示例文章等上下文文件，确保所有内容符合品牌调性。

**技术亮点**: 项目基于 Python，技术栈包括用于数据分析的 `scikit-learn`、用于自然语言处理的 `nltk` 和 `textstat`，以及用于网页抓取的 `beautifulsoup4`，并通过 Claude Code 平台实现智能化的交互式工作流。

---
## 8. [coleam00/Archon](https://github.com/coleam00/Archon)
- **语言**: TypeScript
- **Stars**: 14,445
- **简介**: The first open-source harness builder for AI coding. Make AI coding deterministic and repeatable.

### AI 总结
**简介**: Archon 是一个开源的 AI 编码工作流引擎，旨在通过定义 YAML 工作流，使 AI 辅助编码过程变得确定性和可重复。

**核心功能**:
- **定义工作流**：通过 YAML 文件定义开发流程（如规划、实现、验证、代码审查、创建 PR），确保每次执行步骤一致。
- **智能与确定性结合**：在工作流中混合 AI 节点（如规划、代码生成）与确定性节点（如 bash 脚本、测试），仅在需要智能的地方使用 AI。
- **隔离执行**：每个工作流运行都在独立的 git 工作树中进行，支持并行处理多个任务而互不冲突。
- **多平台便携**：工作流定义一次后，可提交至代码库，并通过 CLI、Web UI、Slack、Telegram 或 GitHub 等多种方式一致运行。

**技术亮点**: 使用 TypeScript 开发，采用类似 n8n 的工作流引擎架构，将 Dockerfile 和 GitHub Actions 的理念应用于 AI 编码流程。

---
## 9. [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos)
- **语言**: Python
- **Stars**: 12,212
- **简介**: Kronos: A Foundation Model for the Language of Financial Markets

### AI 总结
**简介**: Kronos 是首个专门为金融市场K线序列设计的开源基础模型，基于超过45个全球交易所的数据进行预训练。

**核心功能**:
- 通过两阶段框架处理金融数据：先由专用分词器将连续的多维K线数据（OHLCV）量化为分层离散词元，再由自回归Transformer进行预训练。
- 提供不同规模的预训练模型（如mini、small、base），支持多样化的量化任务，如市场预测。
- 提供在线演示，可实时可视化模型对交易对（如BTC/USDT）的未来价格预测。

**技术亮点**:
- 采用解码器架构的Transformer模型，专门针对高噪声金融数据设计。
- 模型及分词器已开源并托管于Hugging Face平台，便于下载和使用。
- 项目提供完整的微调脚本，支持用户针对特定任务进行模型适配。

---
## 10. [YishenTu/claudian](https://github.com/YishenTu/claudian)
- **语言**: TypeScript
- **Stars**: 6,860
- **简介**: An Obsidian plugin that embeds Claude Code as an AI collaborator in your vault

### AI 总结
**简介**: 一个将 Claude Code 等 AI 编程助手嵌入到 Obsidian 知识库中，使其能直接读写、搜索和操作库内文件的插件。

**核心功能**:
- **AI 协作聊天**: 在侧边栏与 AI 助手对话，助手可直接读取、写入、编辑和搜索知识库中的文件。
- **行内编辑**: 选中文本或使用快捷键，可在笔记中直接编辑并查看词级差异预览。
- **多样化交互**: 支持斜杠命令、技能调用、`@提及`文件或工具、计划模式以及自定义指令模式。
- **外部工具集成**: 支持通过 MCP 协议连接外部工具，扩展助手能力。
- **多标签与对话管理**: 支持多聊天标签页、完整的对话历史、分支和恢复功能。

**技术亮点**: 基于 TypeScript 开发，深度集成 Claude Code/Codex CLI，支持 Model Context Protocol 以连接外部服务，数据本地存储，无遥测。

---
