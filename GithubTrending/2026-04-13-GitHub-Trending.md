---
tags:
  - github-trending
  - daily
date: 2026-04-13
created: 2026-04-13T01:55:47.735Z
---

# 2026-04-13 GitHub Trending Top 10

## 1. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 67,345
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 构建的、具备自我学习和改进能力的 AI 智能体，支持多平台交互和灵活部署。

**核心功能**:
- **自我改进的学习循环**：能够从经验中创建技能，在使用中改进技能，并通过记忆管理和会话搜索来持久化知识。
- **多平台与多模态接口**：提供功能完整的终端界面（TUI），并可通过单一网关进程支持 Telegram、Discord、Slack、CLI 等多种平台，支持语音备忘录转录。
- **灵活的模型与部署**：支持连接 Nous Portal、OpenRouter、OpenAI 等众多模型提供商，无需修改代码即可切换。可在 VPS、GPU 集群或 Modal/Daytona 等无服务器基础设施上运行，成本低廉。
- **自动化与并行处理**：内置定时任务调度器，支持自然语言描述自动化任务。可以生成隔离的子代理进行并行工作流处理。
- **研究就绪**：支持批量轨迹生成、RL 环境和轨迹压缩，用于训练下一代工具调用模型。

**技术亮点**: 采用模块化设计，支持六种终端后端（本地、Docker、SSH、Daytona、Singularity、Modal）；集成了用于用户建模的 Honcho 和兼容 agentskills.io 开放标准；具备完整的工具调用和 RPC 脚本编写能力。

---
## 2. [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos)
- **语言**: Python
- **Stars**: 15,841
- **简介**: Kronos: A Foundation Model for the Language of Financial Markets

### AI 总结
**简介**: Kronos 是首个专注于金融市场K线图序列的开源基础模型，旨在理解和预测金融时间序列数据。

**核心功能**:
- **金融K线序列建模**: 专门处理包含开盘价、最高价、最低价、收盘价和成交量（OHLCV）的多维、高噪声金融数据。
- **多任务统一框架**: 通过预训练，模型可支持多种量化金融任务，如价格预测。
- **提供预训练模型**: 在Hugging Face上发布了不同参数规模的模型（如Kronos-mini, small, base），并提供了微调脚本供用户适配特定任务。

**技术亮点**:
- **两阶段架构**: 1) 使用专门的Tokenizer将连续K线数据量化为分层离散token；2) 基于自回归Transformer进行预训练。
- **大规模数据训练**: 基于全球超过45个交易所的数据进行训练。
- **开源与易用**: 模型完全开源，提供实时演示和详细的快速入门指南。

---
## 3. [forrestchang/andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills)
- **语言**: Unknown
- **Stars**: 17,055
- **简介**: A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.

### AI 总结
**简介**: 一个名为 `CLAUDE.md` 的单一文件，旨在通过四大核心原则来优化 Claude Code 的编码行为，解决大语言模型在编程时常见的假设错误、过度设计等问题。

**核心功能**:
- **编码前思考**: 要求模型明确陈述假设、呈现多种解读、在必要时提出质疑，并在困惑时主动寻求澄清。
- **简单性优先**: 倡导用最少的代码解决问题，避免添加未要求的功能、抽象或“灵活性”，防止过度工程化。
- **精准修改**: 只修改与任务直接相关的代码，不“顺手”改进相邻代码、注释或格式，并清理自身改动产生的冗余。
- **目标驱动执行**: 将指令转化为可验证的成功标准（如先写测试再实现），使模型能自主循环直至目标达成。

**技术亮点**: 项目本身不依赖特定技术栈，其核心是提出一套可操作的、基于原则的“提示工程”方法，以配置文件（`CLAUDE.md`）或 Claude Code 插件的形式集成到开发工作流中，直接引导和约束 AI 编码助手的输出行为。

---
## 4. [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **语言**: Python
- **Stars**: 104,882
- **简介**: Python tool for converting files and office documents to Markdown.

### AI 总结
**简介**: 一个由微软开发的轻量级 Python 工具，专注于将多种文件和办公文档转换为 Markdown 格式，以便于大语言模型（LLM）和文本分析流程使用。

**核心功能**:
- 支持转换多种格式，包括 PDF、PowerPoint、Word、Excel、图像、音频、HTML、CSV/JSON/XML、ZIP、YouTube 视频、EPub 等。
- 提供命令行界面（CLI）和 Python API 两种使用方式，支持文件路径输入和管道操作。
- 依赖项按功能模块化，可通过可选安装（如 `pip install 'markitdown[pdf, docx]'`）来精确控制支持的格式。

**技术亮点**:
- 采用模块化、可扩展的架构，支持通过插件自定义转换器。
- 从 0.1.0 版本起，底层接口改为直接处理二进制流，不再创建临时文件，提升了效率。
- 提供了 MCP（Model Context Protocol）服务器，便于与 Claude Desktop 等 LLM 应用程序集成。

---
## 5. [multica-ai/multica](https://github.com/multica-ai/multica)
- **语言**: TypeScript
- **Stars**: 9,487
- **简介**: The open-source managed agents platform. Turn coding agents into real teammates — assign tasks, track progress, compound skills.

### AI 总结
**简介**: Multica 是一个开源的、可管理的智能体平台，旨在将编程智能体转变为真正的“团队成员”，实现任务分配、进度追踪和技能复用的自动化协作。

**核心功能**:
- **智能体即队友**：可以像分配任务给同事一样将问题分配给智能体，它们拥有个人资料，出现在看板上，并能主动发布评论、创建问题和报告障碍。
- **自主执行**：支持完整的任务生命周期管理（排队、认领、开始、完成/失败），并通过 WebSocket 提供实时进度流，实现“设置即忘”的自动化。
- **可复用技能**：每个解决方案都能转化为整个团队可复用的技能，如部署、迁移、代码审查，使团队能力随时间不断积累。
- **统一运行时**：一个仪表板管理所有计算资源，支持本地守护进程和云运行时，自动检测可用的 CLI 并实时监控。
- **多工作区**：通过工作区级别的隔离，跨团队组织工作，每个工作区拥有独立的智能体、问题和设置。

**技术亮点**: 基于 TypeScript 开发，提供 CLI 工具和 Web 应用，支持自托管（需 Docker），兼容 Claude Code、Codex、OpenClaw 和 OpenCode 等多种智能体提供商。

---
## 6. [coleam00/Archon](https://github.com/coleam00/Archon)
- **语言**: TypeScript
- **Stars**: 17,093
- **简介**: The first open-source harness builder for AI coding. Make AI coding deterministic and repeatable.

### AI 总结
**简介**: Archon 是一个开源的 AI 编码工作流引擎，旨在通过定义 YAML 工作流，使 AI 编程过程变得确定性和可重复。

**核心功能**:
- **定义工作流**：通过 YAML 文件定义开发流程（如规划、实现、验证、代码审查、创建 PR），确保每次执行步骤一致。
- **智能与确定性结合**：在工作流中混合使用确定性节点（如 bash 脚本、测试）和 AI 节点（如规划、代码生成），仅在需要智能的地方调用 AI。
- **隔离执行**：每个工作流运行都在独立的 git 工作树中进行，支持并行处理多个任务而互不冲突。
- **多平台便携**：工作流定义在项目仓库中，可通过 CLI、Web UI、Slack、Telegram 或 GitHub 等多种方式触发和运行。

**技术亮点**: 使用 TypeScript 开发，采用类似 Dockerfile 和 GitHub Actions 的声明式工作流理念，将 AI 编码过程工程化。

---
## 7. [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice)
- **语言**: HTML
- **Stars**: 39,151
- **简介**: practice made claude perfect

### AI 总结
**简介**: 这是一个关于 Claude Code 最佳实践的指南项目，旨在帮助开发者从“氛围编码”过渡到“智能体工程”，通过实践来精通 Claude 的使用。

**核心功能**:
- **子智能体**：在独立上下文中运行的自主体，拥有自定义工具、权限、模型和持久身份。
- **命令**：注入到现有上下文中的知识，是用于工作流编排的简单用户调用提示模板。
- **技能**：可配置、可预加载、可自动发现的知识注入，支持上下文分叉和渐进式披露。
- **工作流**：通过命令（如天气编排器）实现复杂任务的自动化编排。
- **钩子**：在智能体循环外特定事件上运行的用户定义处理程序（脚本、HTTP、提示、智能体）。
- **MCP 服务器**：通过模型上下文协议连接外部工具、数据库和 API。
- **插件**：可分发包，包含技能、子智能体、钩子、MCP 服务器和 LSP 服务器。
- **设置**：分层配置系统，管理权限、模型配置、输出样式和沙箱环境。

**技术亮点**: 项目围绕 Claude Code 的官方功能构建，强调通过 `.claude/` 目录下的配置文件（如 agents, commands, skills, settings.json）和 MCP 协议来实现模块化、可配置的智能体工程与工作流编排。

---
## 8. [OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM)
- **语言**: Python
- **Stars**: 11,370
- **简介**: VoxCPM2: Tokenizer-Free TTS for Multilingual Speech Generation, Creative Voice Design, and True-to-Life Cloning

### AI 总结
**简介**: VoxCPM2 是一个无需分词器（Tokenizer-Free）的端到端文本转语音（TTS）系统，支持多语言语音生成、创意语音设计和逼真的声音克隆。

**核心功能**:
- **多语言合成**：支持30种语言及多种中文方言，无需语言标签即可直接合成。
- **语音设计**：仅通过自然语言描述（如性别、年龄、语调）即可生成全新的声音，无需参考音频。
- **可控声音克隆**：根据短参考音频克隆音色，并可引导情感、语速等风格，同时保持音色。
- **极致克隆**：结合参考音频及其文本转录，能无缝延续并精确复现原声的所有细节（音色、节奏、情感）。
- **高质量音频输出**：直接生成48kHz工作室级音频，内置超分辨率，无需外部上采样器。

**技术亮点**: 基于 **扩散自回归架构** 的端到端模型，绕过了离散分词过程；采用 **MiniCPM-4** 作为骨干网络；支持实时流式合成（RTF可低至约0.3）；模型权重和代码在 **Apache-2.0** 许可下完全开源。

---
## 9. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 50,189
- **简介**: A Claude Code plugin that automatically captures everything Claude does during your coding sessions, compresses it with AI (using Claude's agent-sdk), and injects relevant context back into future sessions.

### AI 总结
**简介**: 一个为 Claude Code 设计的持久化记忆压缩系统插件，能自动记录编码会话内容，利用 AI 压缩并注入相关上下文到未来会话中。

**核心功能**:
- 自动捕获 Claude 在编码会话中的所有操作
- 使用 AI（基于 Claude 的 agent-sdk）对捕获的内容进行压缩
- 将压缩后的相关上下文智能注入到未来的会话中

**技术亮点**: 基于 TypeScript 开发，利用 Claude 的 agent-sdk 实现 AI 驱动的上下文压缩与检索。

---
## 10. [ahujasid/blender-mcp](https://github.com/ahujasid/blender-mcp)
- **语言**: Python
- **Stars**: 19,171
- **简介**: 

### AI 总结
**简介**: BlenderMCP 是一个通过 Model Context Protocol (MCP) 将 Blender 与 Claude AI 连接起来的项目，使 AI 能够直接交互和控制 Blender，实现提示辅助的 3D 建模与场景操作。

**核心功能**:
- **双向通信**: 通过基于套接字的服务器连接 Claude AI 与 Blender。
- **对象操作**: 在 Blender 中创建、修改和删除 3D 对象。
- **材质控制**: 应用和修改材质与颜色。
- **场景检查**: 获取当前 Blender 场景的详细信息。
- **代码执行**: 从 Claude 在 Blender 中运行任意 Python 代码。
- **模型与资产支持**: 支持搜索下载 Sketchfab 模型、使用 Poly Haven API 资产、通过 Hunyuan3D 和 Hyper3D Rodin 生成 3D 模型。
- **远程与视图支持**: 支持在远程主机上运行，并能查看 Blender 视口截图以更好地理解场景。

**技术亮点**:
- **架构清晰**: 系统由两个核心组件构成——Blender 插件 (`addon.py`) 和实现 MCP 协议的 Python 服务器 (`server.py`)。
- **生态集成**: 提供与 Claude Desktop、Cursor 及 Visual Studio Code 的详细集成配置指南。
- **现代化工具链**: 依赖 `uv` 包管理器进行安装和管理，提升了部署效率。

---
