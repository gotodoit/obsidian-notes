---
tags:
  - github-trending
  - daily
date: 2026-04-18
created: 2026-04-18T01:55:51.799Z
---

# 2026-04-18 GitHub Trending Top 10

## 1. [EvoMap/evolver](https://github.com/EvoMap/evolver)
- **语言**: JavaScript
- **Stars**: 4,293
- **简介**: The GEP-Powered Self-Evolution Engine for AI Agents. Genome Evolution Protocol. | evomap.ai

### AI 总结
**简介**: Evolver 是一个基于基因组进化协议（GEP）驱动的 AI 智能体自我进化引擎，旨在将临时的提示词调整转化为可审计、可复用的进化资产。

**核心功能**:
- **GEP 引导的进化**: 扫描运行时日志和错误模式，从资产库中匹配最佳基因或胶囊，生成严格遵循协议的进化提示。
- **审计与追溯**: 记录完整的进化事件，确保每次进化步骤的可追溯性和可审计性。
- **灵活的运行模式**: 支持单次运行、需人工确认的审查模式以及作为后台守护进程的连续循环模式。
- **网络与离线能力**: 核心功能可完全离线运行，也可选择连接 EvoMap 网络以使用技能共享、进化排行榜等平台特性。

**技术亮点**:
- **基于 Git 的版本控制**: 利用 Git 进行回滚、影响范围计算和固化操作，确保进化过程的安全与可控。
- **协议约束设计**: 通过 GEP 协议对进化过程进行约束和引导，保障进化的规范性和有效性。
- **JavaScript/Node.js 实现**: 要求 Node.js >= 18 环境，便于集成与部署。

---
## 2. [lsdefine/GenericAgent](https://github.com/lsdefine/GenericAgent)
- **语言**: Python
- **Stars**: 3,666
- **简介**: Self-evolving agent: grows skill tree from 3.3K-line seed, achieving full system control with 6x less token consumption

### AI 总结
**简介**: GenericAgent 是一个极简、自进化的自主智能体框架，其核心仅约3000行代码，通过9个原子工具和一个约100行的智能体循环，赋予大型语言模型对本地计算机（包括浏览器、终端、文件系统、键鼠输入、屏幕视觉和移动设备）的系统级控制能力。

**核心功能**:
- **自进化**: 每次解决新任务后，自动将执行路径固化为技能，形成专属的个人技能树，能力随使用而增长。
- **极简架构**: 核心代码约3000行，智能体循环约100行，无复杂依赖，部署开销为零。
- **强大执行**: 注入真实浏览器（保留登录会话），通过9个原子工具直接控制系统。
- **高兼容性**: 支持Claude、Gemini、Kimi、MiniMax等主流模型，跨平台运行。
- **高令牌效率**: 上下文窗口小于30K，远低于其他智能体（200K-1M），分层内存确保相关知识始终在范围内，成本更低、成功率更高。

**技术亮点**:
- **自进化机制**: 通过“自主探索 -> 固化技能 -> 写入记忆层 -> 后续直接调用”的循环，实现能力的持续积累。
- **原子工具集**: 提供浏览器、终端、文件系统、键鼠、ADB等9个底层工具，实现全面的系统控制。
- **分层记忆与技能库**: 支持技能的持久化存储与直接复用，并已发布百万级规模的技能库。

---
## 3. [SimoneAvogadro/android-reverse-engineering-skill](https://github.com/SimoneAvogadro/android-reverse-engineering-skill)
- **语言**: Shell
- **Stars**: 2,763
- **简介**: Claude Code skill to support Android app's reverse engineering

### AI 总结
**简介**: 一个用于 Claude Code 的插件，旨在通过反编译 Android 应用文件来提取和分析其使用的 HTTP API。

**核心功能**:
- 支持反编译 APK、XAPK、JAR 和 AAR 文件，支持使用 jadx 或 Fernflower/Vineflower 引擎。
- 自动提取并记录应用中的 API 端点，包括 Retrofit、OkHttp 调用、硬编码 URL 和认证模式。
- 分析应用结构（如清单、包结构）并追踪从界面组件到网络调用的完整调用流程。
- 提供处理混淆代码（如 ProGuard/R8）的策略。

**技术亮点**: 集成了 jadx、Fernflower/Vineflower 和 dex2jar 等成熟的 Android 逆向工程工具链，提供自动化脚本和自然语言交互，简化了 API 提取与分析流程。

---
## 4. [BasedHardware/omi](https://github.com/BasedHardware/omi)
- **语言**: Dart
- **Stars**: 9,865
- **简介**: AI that sees your screen, listens to your conversations and tells you what to do

### AI 总结
**简介**: Omi 是一个开源的“第二大脑”AI助手，它能实时捕捉你的屏幕内容和对话，进行转录、总结并生成待办事项，同时提供一个能记住你所有见闻的AI聊天功能，支持桌面、手机和可穿戴设备。

**核心功能**:
- **多模态感知**: 实时捕获屏幕内容和对话音频。
- **智能处理**: 对内容进行实时转录、生成摘要和行动项。
- **记忆聊天**: 提供基于所有历史见闻的AI对话功能。
- **多平台支持**: 提供macOS应用、iOS/Android移动应用、Web版本及可穿戴设备支持。

**技术亮点**:
- **跨平台架构**: 前端使用Swift/SwiftUI (macOS)、Flutter (移动端)，后端使用Python (FastAPI)。
- **模块化后端**: 集成了语音活动检测(VAD)、说话人分离(Diarizer)、Deepgram语音识别(STT)及多种LLM。
- **全栈开源**: 项目完全开源，涵盖从设备固件(nRF/Zephyr, ESP32-S3)到云端服务的完整技术栈。

---
## 5. [Lordog/dive-into-llms](https://github.com/Lordog/dive-into-llms)
- **语言**: Jupyter Notebook
- **Stars**: 31,546
- **简介**: 《动手学大模型Dive into LLMs》系列编程实践教程

### AI 总结
**简介**: 这是一个名为《动手学大模型》的系列编程实践教程，旨在通过Jupyter Notebook形式的实践项目，帮助学习者快速入门大模型相关的开发与应用。

**核心功能**:
- 提供从大模型微调部署、提示工程到高级主题（如知识编辑、数学推理、安全攻击）的完整实践教程。
- 每个主题均配套课件、详细说明文档和可运行的Jupyter Notebook脚本，方便动手实践。
- 项目包含国产化大模型全流程开发教程，并与高校课程结合，具有教学和公益性质。

**技术亮点**: 教程覆盖大模型多个前沿领域，包括模型水印、越狱攻击、隐写术、多模态模型和GUI智能体，注重安全与实用并重，并提供持续更新。

---
## 6. [Donchitos/Claude-Code-Game-Studios](https://github.com/Donchitos/Claude-Code-Game-Studios)
- **语言**: Shell
- **Stars**: 11,816
- **简介**: Turn Claude Code into a full game dev studio — 49 AI agents, 72 workflow skills, and a complete coordination system mirroring real studio hierarchy.

### AI 总结
**简介**: 一个将 Claude Code 会话转变为结构化游戏开发工作室的框架，通过 49 个专业 AI 代理和 72 个工作流技能，模拟真实工作室的层级与协作。

**核心功能**:
- **分层代理系统**: 提供导演、部门主管、专家三个层级的 49 个专业 AI 代理，覆盖设计、编程、美术、音频、叙事、QA 等全流程。
- **标准化工作流**: 内置 72 个斜杠命令技能，支持从项目启动、设计系统、创建史诗/用户故事到开发、测试的完整游戏开发流程。
- **自动化与质量管控**: 包含 12 个钩子用于自动验证，11 条路径范围的编码规则，以及 39 个文档模板，确保项目规范与质量。

**技术亮点**: 支持 Godot 4、Unity、Unreal Engine 5 三大主流游戏引擎，并为每个引擎配备了专门的代理和子专家，架构设计上模拟了真实游戏工作室的协作与审核层级。

---
## 7. [jamiepine/voicebox](https://github.com/jamiepine/voicebox)
- **语言**: TypeScript
- **Stars**: 19,879
- **简介**: The open-source voice synthesis studio

### AI 总结
**简介**: Voicebox 是一个开源的、本地优先的语音合成与克隆工作室，可作为 ElevenLabs 的免费替代品。

**核心功能**:
- **语音克隆与合成**: 支持从几秒音频克隆声音，并使用5种TTS引擎（Qwen3-TTS、LuxTTS、Chatterbox Multilingual等）生成23种语言的语音。
- **后期处理与编辑**: 提供音高变换、混响、延迟等音频效果，并配备多音轨时间线编辑器，用于创作对话、播客等。
- **隐私与本地化**: 所有模型和语音数据均在本地设备处理，确保完全隐私。
- **API集成**: 提供REST API，便于开发者将语音合成功能集成到自己的项目中。

**技术亮点**: 采用 Tauri (Rust) 框架构建，而非 Electron，以获得更好的原生性能。支持跨平台运行（macOS、Windows、Linux）及多种硬件加速（Apple MLX/Metal、NVIDIA CUDA、AMD ROCm、Intel Arc）。

---
## 8. [lukilabs/craft-agents-oss](https://github.com/lukilabs/craft-agents-oss)
- **语言**: TypeScript
- **Stars**: 4,304
- **简介**: 

### AI 总结
**简介**: Craft Agents 是一个基于 Claude Agent SDK 和 Pi SDK 构建的开源桌面应用，旨在提供一个直观、文档中心化且支持多任务处理的智能体（Agent）工作平台。

**核心功能**:
- **无缝连接多种服务**：支持通过自然语言指令连接 MCP 服务器、REST API（如 Linear, Gmail, Slack）以及本地数据库，无需手动配置文件。
- **多会话与工作流管理**：提供桌面应用级的会话管理、状态工作流（如待办、进行中、完成）和标记功能。
- **多模型与多提供商支持**：可同时连接 Claude、Google AI Studio、ChatGPT Plus、GitHub Copilot 或 OpenAI 等多种 AI 提供商。
- **技能与自动化**：支持通过描述创建自定义技能，并具备事件驱动的自动化能力。
- **实时与无重启更新**：所有更改（如新技能、新数据源）即时生效，无需重启应用。

**技术亮点**:
- **技术栈**：基于 TypeScript 开发，使用 Bun 作为运行时和包管理器，采用 Electron 构建桌面应用。
- **架构理念**：遵循“智能体原生软件”原则，强调通过自然语言描述而非代码或 CLI 来驱动和定制所有功能。
- **高度可定制**：应用本身完全使用 Craft Agents 构建，任何自定义功能都可通过提示词实现。

---
## 9. [Tracer-Cloud/opensre](https://github.com/Tracer-Cloud/opensre)
- **语言**: Python
- **Stars**: 1,474
- **简介**: Build your own AI SRE agents. The open source toolkit for the AI era ✨

### AI 总结
**简介**: OpenSRE 是一个用于构建和训练 AI SRE（站点可靠性工程）智能体的开源框架，旨在帮助用户在自己的基础设施上自动调查和响应生产环境事故。

**核心功能**:
- **构建自定义 AI SRE 智能体**: 提供框架用于创建可连接现有 60+ 工具、定义自定义工作流的 AI 智能体。
- **提供训练与评估环境**: 包含用于强化学习的合成事故模拟套件和真实世界的端到端测试，以训练和评估智能体。
- **支持本地与云端部署**: 可通过 CLI 快速安装、启动，并支持部署到 Railway 等平台。
- **事故调查自动化**: 通过智能体自动收集和分析分散在日志、指标、追踪等信息中的证据，进行根因分析。

**技术亮点**:
- 采用 **LangGraph** 运行时，需要 **Postgres** 和 **Redis** 作为后端服务支持。
- 测试体系包含**合成 RCA 测试套件**（评估根因准确性、证据需求）和**真实端到端测试**（覆盖 Kubernetes、EC2、Lambda 等云场景）。
- 项目处于 **Public Alpha** 阶段，核心工作流已可用，但 API 和集成仍在积极开发中。

---
## 10. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 157,805
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为编码智能体（AI助手）设计的、基于可组合技能的软件开发方法论与框架，旨在引导智能体进行系统化、高质量的开发。

**核心功能**:
- **引导式设计**：在编码前，通过对话澄清需求，并以可读的模块化方式呈现设计供用户确认。
- **结构化实施**：基于批准的设计，创建详细到可由初级工程师遵循的、强调TDD、YAGNI和DRY原则的实施计划。
- **子代理驱动开发**：启动子代理流程，让智能体自主执行计划中的工程任务，并进行检查和评审，可长时间自主工作而不偏离计划。
- **自动化技能触发**：内置一系列在开发各阶段自动触发的强制性技能（如头脑风暴、使用Git工作树、编写计划、测试驱动开发、代码审查等），确保流程规范。

**技术亮点**: 框架本身用Shell编写，但其核心价值在于定义了一套与具体AI平台（如Claude、OpenAI Codex、Cursor、GitHub Copilot CLI等）集成的、标准化的智能体开发工作流和技能库。

---
