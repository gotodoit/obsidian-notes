---
tags:
  - github-trending
  - daily
date: 2026-05-31
created: 2026-05-31T01:55:42.964Z
---

# 2026-05-31 GitHub Trending Top 10

## 1. [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **语言**: Python
- **Stars**: 132,468
- **简介**: Python tool for converting files and office documents to Markdown.

### AI 总结
**简介**: MarkItDown 是微软推出的轻量级 Python 工具，用于将多种文件格式转换为 Markdown，便于大语言模型和文本分析流程使用。

**核心功能**:
- 支持 PDF、PowerPoint、Word、Excel、图片、音频、HTML、CSV、JSON、XML、ZIP、YouTube 链接、EPub 等格式转换为 Markdown
- 提供命令行工具，支持管道输入和输出文件指定
- 支持可选依赖安装，可针对特定文件格式（如 PDF、DOCX、PPTX）单独安装依赖
- 支持第三方插件扩展，如 OCR 插件增强文本提取能力

**技术亮点**:
- 基于 Python 3.10+，轻量级设计，专注于保留文档结构（标题、列表、表格、链接等）
- 输出 Markdown 格式，与 GPT-4o 等大语言模型原生兼容，提高 token 效率
- 提供安全考虑文档，提醒用户在不可信环境中正确使用转换函数

---
## 2. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)
- **语言**: Python
- **Stars**: 72,022
- **简介**: 利用AI大模型，一键生成高清短视频 Generate short videos with one click using AI LLM.

### AI 总结
**简介**: MoneyPrinterTurbo 是一个基于 AI 大模型的短视频自动生成工具，只需提供主题或关键词即可全自动生成高清短视频。

**核心功能**:
- 支持 AI 自动生成视频文案，也可自定义文案
- 支持竖屏 9:16（1080x1920）和横屏 16:9（1920x1080）高清视频
- 支持批量视频生成，可一次生成多个视频并选择最佳
- 支持中文和英文文案，多种语音合成并可实时试听
- 支持字幕生成，可调整字体、位置、颜色、大小及描边
- 支持背景音乐，可随机或指定音乐文件并调节音量
- 视频素材高清无版权，也可使用本地素材

**技术亮点**:
- 采用完整的 MVC 架构，代码结构清晰，易于维护
- 支持 API 和 Web 界面双模式
- 支持 OpenAI、Moonshot、Azure、DeepSeek、Google Gemini 等多种大模型接入
- 提供 Windows 一键启动包、Docker 部署、Google Colab 等多种部署方式

---
## 3. [anthropics/claude-code](https://github.com/anthropics/claude-code)
- **语言**: Python
- **Stars**: 128,406
- **简介**: Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands.

### AI 总结
**简介**: Claude Code 是一个驻留在终端中的智能编码工具，能理解代码库，通过自然语言指令帮助开发者更快地编码、执行常规任务、解释复杂代码及处理 Git 工作流。

**核心功能**:
- 通过自然语言指令执行编码常规任务（如代码重构、文件操作等）
- 解释复杂代码逻辑，辅助理解代码库
- 处理 Git 工作流（如提交、分支管理等）
- 支持在终端、IDE 或通过 GitHub 上 @claude 使用
- 提供插件系统，可扩展自定义命令和智能体功能
- 支持通过 `/bug` 命令直接报告问题

**技术亮点**: 基于 Python 开发，通过 npm 或系统包管理器（如 Homebrew、WinGet）分发，支持跨平台（macOS、Linux、Windows）安装，集成了数据收集与隐私保护机制。

---
## 4. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 1,468
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，提供一系列面向开发者工具、框架和 SaaS 产品的插件，每个插件独立包含清单文件。

**核心功能**:
- 提供持续学习、团队协作、代码审查、文档渲染等开发者工具插件
- 支持通过 CLI 和 Cursor 代理进行仓库兼容性扫描与审计
- 提供并行任务编排、PR 差异可视化、文档画布等高级工作流
- 包含插件脚手架生成与验证工具
- 支持 MCP 服务器定义和自定义规则（.mdc 文件）

**技术亮点**: 基于 TypeScript 开发，采用多插件市场仓库结构，每个插件独立包含 plugin.json 清单、技能文件、规则文件及 MCP 配置，遵循 MIT 开源协议。

---
## 5. [revfactory/harness](https://github.com/revfactory/harness)
- **语言**: HTML
- **Stars**: 4,274
- **简介**: A meta-skill that designs domain-specific agent teams, defines specialized agents, and generates the skills they use.

### AI 总结
**简介**: Harness 是一个为 Claude Code 设计的元技能插件，能将领域描述自动转化为专用的智能体团队及其技能集，基于 6 种预定义的团队架构模式。

**核心功能**:
- **智能体团队设计** — 提供 6 种架构模式：管道、扇出/扇入、专家池、生产者-审查者、监督者和分层委派
- **技能自动生成** — 为智能体自动生成技能，并采用渐进式披露机制以优化上下文管理
- **团队编排** — 支持智能体间的数据传递、错误处理和团队协调协议
- **验证与测试** — 包含触发验证、预演测试以及带技能与不带技能的对比测试

**技术亮点**: 位于 Claude Code 生态系统的 L3 元工厂层，作为团队架构工厂，与运行时配置工厂（如 Archon）互补，可结合使用实现更完整的自动化代理系统。

---
## 6. [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin)
- **语言**: TypeScript
- **Stars**: 18,432
- **简介**: Official Compound Engineering plugin for Claude Code, Codex, Cursor, and more

### AI 总结
**简介**: 一个旨在通过规划、执行与知识积累的循环，降低后续工程工作难度的AI技能与代理插件，支持Claude Code、Codex、Cursor等工具。

**核心功能**:
- **策略与规划**: 通过`/ce-strategy`创建产品策略文档，`/ce-brainstorm`和`/ce-plan`进行交互式需求分析与实现规划。
- **执行与调试**: 使用`/ce-work`执行规划，`/ce-debug`系统性地复现和修复问题。
- **审查与复用**: 通过`/ce-code-review`和`/ce-doc-review`进行多代理代码审查，`/ce-compound`将学习成果文档化以便复用。
- **产品洞察**: 利用`/ce-product-pulse`生成指定时间窗口的产品使用与性能报告。

**技术亮点**: 基于TypeScript开发，采用“复合工程”理念（80%规划与审查，20%执行），内置37个技能和51个代理，通过MCP协议与多种AI编程工具集成。

---
## 7. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 199,335
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个为 AI 编程助手（如 Claude Code、Codex、Cursor 等）设计的跨平台代理性能优化系统，集成了技能、直觉、记忆、安全与研究优先的开发能力。

**核心功能**:
- **多平台兼容**: 支持 Codex、Claude Code、Cursor、OpenCode、Gemini、Zed、GitHub Copilot 等主流 AI 代理。
- **完整系统**: 提供技能、直觉、记忆优化、持续学习、安全扫描和研究优先开发等模块化能力。
- **生产就绪**: 包含代理、技能、钩子、规则、MCP 配置和命令兼容层，经过 10 个月以上的密集实际使用验证。

**技术亮点**:
- **跨语言生态**: 支持 Shell、TypeScript、Python、Go、Java、Perl、Markdown 等多种语言。
- **MIT 开源许可**: 核心代码永久开源，提供免费和付费（Pro）版本，付费版支持私有仓库和 GitHub App 集成。
- **多架构设计**: 采用“跨平台代理工作流”架构，支持在多种 AI 代理环境中无缝迁移和复用。

---
## 8. [OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM)
- **语言**: Python
- **Stars**: 22,775
- **简介**: VoxCPM2: Tokenizer-Free TTS for Multilingual Speech Generation, Creative Voice Design, and True-to-Life Cloning

### AI 总结
**简介**: VoxCPM2 是一个无需分词器的端到端文本转语音（TTS）系统，支持多语言语音生成、创意声音设计和逼真声音克隆，拥有 20 亿参数并基于 200 万小时多语言语音数据训练。

**核心功能**:
- **30 种语言多语言合成**: 支持直接输入文本合成语音，无需语言标签。
- **语音设计**: 仅通过自然语言描述（如性别、年龄、语调、情感）创建全新声音，无需参考音频。
- **可控声音克隆**: 通过短参考音频克隆声音，并可引导情感、节奏和表达风格。
- **终极克隆**: 提供参考音频及其文本转录，模型可无缝延续，保留音色、节奏、情感和风格。
- **48kHz 高质量音频输出**: 接受 16kHz 参考音频，直接输出 48kHz 工作室级音频，内置超分辨率功能。
- **上下文感知合成**: 自动根据文本内容推断合适的韵律和表现力。
- **实时流式处理**: 在 NVIDIA RTX 4090 上 RTF 低至 ~0.3，通过 Nano-vLLM 或 vLLM-Omni 可加速至 ~0.13。
- **完全开源与商用就绪**: 模型权重和代码基于 Apache-2.0 许可证发布。

**技术亮点**: 采用无分词器的端到端扩散自回归架构，直接生成连续语音表示；基于 MiniCPM-4 骨干网络；通过 AudioVAE V2 的非对称编解码设计实现 48kHz 输出。

---
## 9. [galilai-group/stable-worldmodel](https://github.com/galilai-group/stable-worldmodel)
- **语言**: Python
- **Stars**: 1,466
- **简介**: A platform for reproducible world model research and evaluation

### AI 总结
**简介**: stable-worldmodel 是一个用于可复现世界模型研究与评估的统一平台，提供数据收集、训练和模型预测控制评估的标准化接口。

**核心功能**:
- **统一接口**：为世界模型研究的三个核心阶段（数据收集、训练、MPC评估）提供一致化的API
- **标准化环境**：支持多种标准化环境，如推块任务 (PushT) 等
- **基准实现**：内置常见基线算法和规划求解器（如 CEM 求解器），并提供了 LeWM 和 DINO-WM 等参考实现
- **多格式数据支持**：支持 LanceDB、HDF5、文件夹和视频等多种数据存储格式，并可通过注册机制扩展
- **完整工作流**：从数据集收集、模型训练到评估的端到端流程，仅需少量代码即可完成

**技术亮点**:
- 基于 PyTorch 构建
- 使用 LanceDB 作为默认数据格式，支持追加友好和快速索引读取
- 提供可配置的存储路径 (`$STABLEWM_HOME`) 和灵活的格式注册系统
- 支持 LeRobot 数据集（Python 3.12+）

---
## 10. [Crosstalk-Solutions/project-nomad](https://github.com/Crosstalk-Solutions/project-nomad)
- **语言**: TypeScript
- **Stars**: 27,370
- **简介**: Project N.O.M.A.D, is a self-contained, offline survival computer packed with critical tools, knowledge, and AI to keep you informed and empowered—anytime, anywhere.

### AI 总结
**简介**: Project N.O.M.A.D. 是一个自包含、离线优先的知识与教育服务器，集成了关键工具、知识和 AI，旨在随时随地为用户提供信息支持。

**核心功能**:
- **AI 聊天与知识库**：通过 Ollama 和 Qdrant 实现本地 AI 对话、文档上传及语义搜索。
- **离线信息库**：利用 Kiwix 提供离线维基百科、医学参考、电子书等资源。
- **教育平台**：集成 Kolibri，提供可汗学院课程并支持进度追踪和多用户。
- **离线地图**：通过 ProtoMaps 下载区域地图，支持搜索和导航。
- **数据工具**：基于 CyberChef 实现加密、编码、哈希和数据分析。
- **笔记功能**：使用 FlatNotes 进行本地 Markdown 笔记记录。
- **系统基准测试**：内置硬件评分功能，并关联社区排行榜。

**技术亮点**:
- 基于 Docker 容器化编排，通过“指挥中心”管理 UI 和 API 自动处理安装、配置和更新。
- 支持在 Debian 系操作系统（推荐 Ubuntu）上通过终端脚本快速部署，也提供 Docker Compose 高级安装方式。
- 技术栈以 TypeScript 为主，整合了 Ollama、Qdrant、Kiwix、Kolibri、ProtoMaps 等开源工具。

---
