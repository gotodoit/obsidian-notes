---
tags:
  - github-trending
  - daily
date: 2026-04-15
created: 2026-04-15T01:55:49.013Z
---

# 2026-04-15 GitHub Trending Top 10

## 1. [forrestchang/andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills)
- **语言**: Unknown
- **Stars**: 34,268
- **简介**: A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.

### AI 总结
**简介**: 一个名为 `CLAUDE.md` 的单一文件，旨在通过四大核心原则来改进 Claude Code 等大型语言模型在编码时的行为，解决其常见的错误假设、过度工程化等问题。

**核心功能**:
- **四大指导原则**：包含“先思考后编码”、“简单性优先”、“精准修改”和“目标驱动执行”，直接针对 LLM 编码的痛点。
- **行为规范**：为 LLM 提供具体的行为准则，例如明确陈述假设、避免过度抽象、仅修改必要代码、将任务转化为可验证的成功标准。
- **灵活部署**：可作为 Claude Code 插件全局安装，或作为项目级的 `CLAUDE.md` 文件使用。

**技术亮点**: 通过一个轻量级的配置文件（`CLAUDE.md`）来系统性地引导和约束 LLM 的代码生成与编辑行为，强调目标驱动和验证循环，提升代码质量和开发效率。

---
## 2. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 55,902
- **简介**: A Claude Code plugin that automatically captures everything Claude does during your coding sessions, compresses it with AI (using Claude's agent-sdk), and injects relevant context back into future sessions.

### AI 总结
**简介**: 一个为 Claude Code 设计的持久化记忆压缩系统插件，能自动记录编码会话内容，并使用 AI 进行压缩，以便在未来的会话中注入相关上下文。

**核心功能**:
- 自动捕获 Claude 在编码会话期间的所有操作。
- 利用 AI（基于 Claude 的 agent-sdk）对捕获的内容进行智能压缩。
- 将压缩后的相关上下文自动注入到未来的会话中，提供连续性支持。

**技术亮点**: 基于 TypeScript 开发，集成了 Claude 的 agent-sdk 进行 AI 驱动的上下文压缩与管理。

---
## 3. [jamiepine/voicebox](https://github.com/jamiepine/voicebox)
- **语言**: TypeScript
- **Stars**: 17,398
- **简介**: The open-source voice synthesis studio

### AI 总结
**简介**: Voicebox 是一个开源的、本地优先的语音合成与克隆工作室，可作为 ElevenLabs 的免费替代品。

**核心功能**:
- **语音克隆与合成**: 支持从几秒音频克隆声音，并使用5种TTS引擎（Qwen3-TTS、LuxTTS、Chatterbox Multilingual、Chatterbox Turbo、HumeAI TADA）生成23种语言的语音。
- **后期处理与编辑**: 提供音高变换、混响、延迟等音频效果，并配备多音轨时间线编辑器，用于创作对话、播客等。
- **API与集成**: 提供REST API，便于将语音合成功能集成到其他项目中。
- **本地化与隐私**: 所有模型和语音数据均在本地机器处理，确保完全隐私。

**技术亮点**: 使用 Tauri (Rust) 框架构建，提供原生性能（非Electron），支持跨平台运行（macOS、Windows、Linux，并支持多种硬件加速后端如CUDA、Metal、ROCm）。

---
## 4. [pascalorg/editor](https://github.com/pascalorg/editor)
- **语言**: TypeScript
- **Stars**: 11,686
- **简介**: Create and share 3D architectural projects.

### AI 总结
**简介**: 一个基于 React Three Fiber 和 WebGPU 构建的 3D 建筑编辑器，用于创建和分享建筑项目。

**核心功能**:
- 提供 3D 场景编辑能力，支持创建和管理建筑、楼层、墙体、区域等多种节点。
- 支持场景状态的持久化存储（IndexedDB）与完整的撤销/重做功能。
- 采用“编辑器”与“查看器”分离的架构，便于复用和定制。

**技术亮点**:
- 使用 **Turborepo 管理的 TypeScript 单体仓库**，核心逻辑（`@pascal-app/core`）、3D渲染（`@pascal-app/viewer`）和编辑器UI（`apps/editor`）分离。
- 采用 **React Three Fiber** 进行 3D 渲染，并利用 **Zustand** 进行状态管理。
- 设计了**扁平化的节点数据结构**和**场景注册表（Scene Registry）**，实现节点与 Three.js 对象的高效映射与查询。

---
## 5. [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **语言**: Python
- **Stars**: 108,522
- **简介**: Python tool for converting files and office documents to Markdown.

### AI 总结
**简介**: 一个由微软开发的轻量级 Python 工具，专注于将多种文件和办公文档（如 PDF、Word、Excel、PPT）转换为结构化的 Markdown 格式，以便于大型语言模型（LLM）和文本分析管道使用。

**核心功能**:
- 支持广泛的文件格式转换，包括 PDF、Office 文档、图像、音频、HTML、文本格式、ZIP、YouTube 链接和 EPUB 等。
- 提供命令行界面（CLI）和 Python API 两种使用方式，支持文件路径输入和管道操作。
- 通过可选的依赖项分组（如 `[pdf]`、`[docx]`）实现按需安装，以控制依赖和功能。
- 集成了 MCP（模型上下文协议）服务器，便于与 Claude Desktop 等 LLM 应用程序集成。

**技术亮点**:
- 采用模块化设计，依赖项按功能分组，优化了安装和部署。
- 底层处理基于文件流，无需创建临时文件，提升了效率和资源利用率。
- 输出为 Markdown 格式，在保留文档关键结构（标题、列表、表格、链接等）的同时，具有较高的令牌效率，适合 LLM 处理。

---
## 6. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 152,383
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为 AI 编码代理设计的、基于可组合“技能”的软件开发框架和工作流，旨在引导代理进行系统化、高质量的开发。

**核心功能**:
- **引导式设计**：在编码前，通过提问澄清需求，并分块呈现设计文档供用户确认。
- **结构化实施**：基于批准的设计，创建清晰、细粒度的实施计划，强调 TDD、YAGNI 和 DRY 原则。
- **子代理驱动开发**：启动子代理按计划执行工程任务，并自动进行代码审查和质量检查。
- **自动化技能触发**：根据开发阶段（如构思、计划、实施、测试、审查）自动调用相应技能，强制执行标准化工作流。

**技术亮点**: 基于 Shell 脚本实现，提供跨多种主流 AI 开发平台（如 Claude Code、Cursor、Codex、GitHub Copilot CLI 等）的插件化安装和集成方案。

---
## 7. [chrislgarry/Apollo-11](https://github.com/chrislgarry/Apollo-11)
- **语言**: Assembly
- **Stars**: 66,382
- **简介**: Original Apollo 11 Guidance Computer (AGC) source code for the command and lunar modules.

### AI 总结
**简介**: 该项目托管了阿波罗11号任务中指令舱和登月舱的原始制导计算机（AGC）汇编源代码。

**核心功能**:
- 提供阿波罗11号指令舱（Comanche 055）和登月舱（Luminary 099）的完整、可编译的原始源代码。
- 作为一个历史代码的存档库，欢迎提交PR以修正转录错误或补充遗漏文件。

**技术亮点**: 使用原始的AGC汇编语言，可通过Virtual AGC项目进行编译和模拟。

---
## 8. [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund)
- **语言**: Python
- **Stars**: 54,193
- **简介**: An AI Hedge Fund Team

### AI 总结
**简介**: 这是一个用于教育研究的AI对冲基金概念验证项目，通过模拟多位著名投资大师风格的智能体协作，生成股票交易信号，但不进行真实交易。

**核心功能**:
- 集成19个不同角色的智能体，涵盖估值、基本面、技术面、市场情绪分析和风险管理等多个维度。
- 提供命令行界面和Web应用两种运行方式，支持对指定股票代码和时间范围进行分析。
- 包含回测功能，用于评估策略历史表现。
- 支持多种大语言模型API（如OpenAI、Groq）以及本地Ollama模型。

**技术亮点**: 采用Python开发，使用Poetry管理依赖，通过模块化的多智能体架构模拟完整的投资决策流程。

---
## 9. [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos)
- **语言**: Python
- **Stars**: 17,831
- **简介**: Kronos: A Foundation Model for the Language of Financial Markets

### AI 总结
**简介**: Kronos 是首个专注于金融市场K线序列的开源基础模型，旨在处理金融数据的高噪声特性，并支持多种量化任务。

**核心功能**:
- 提供从迷你到大型不同参数规模的预训练模型，适用于不同计算需求。
- 支持基于K线序列的金融预测，并提供在线演示。

**技术亮点**: 采用两阶段框架，包括专门的K线量化分词器和自回归Transformer模型，能够将多维OHLCV数据转换为分层离散令牌进行建模。

---
## 10. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 84,704
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 开发、具备自我学习和成长能力的 AI 代理框架。

**核心功能**:
- **多平台接入**：支持通过 Telegram、Discord、Slack、CLI 等多种方式进行交互，并保持跨平台对话连续性。
- **自我学习与记忆**：具备内置的学习循环，能够从经验中创建技能、在使用中改进技能，并利用搜索和总结实现跨会话记忆。
- **灵活部署**：可在本地、Docker、SSH、云服务器乃至无服务器架构（如 Modal）上运行，成本效益高。
- **多模型支持**：兼容 Nous Portal、OpenRouter、Hugging Face、OpenAI 等众多模型提供商，可轻松切换。
- **自动化与并行**：内置定时任务调度器，支持创建并行工作的子代理，并能将多步骤流程简化为脚本。

**技术亮点**:
- 提供功能完整的终端用户界面，支持多行编辑、命令自动补全和流式工具输出。
- 采用模块化设计，与 `agentskills.io` 开放标准兼容，并集成 Honcho 进行用户建模。
- 支持批量轨迹生成和强化学习环境，适用于工具调用模型的训练研究。

---
