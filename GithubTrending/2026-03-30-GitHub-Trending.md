---
tags:
  - github-trending
  - daily
date: 2026-03-30
created: 2026-03-30T01:55:49.610Z
---

# 2026-03-30 GitHub Trending Top 10

## 1. [luongnv89/claude-howto](https://github.com/luongnv89/claude-howto)
- **语言**: Python
- **Stars**: 6,864
- **简介**: A visual, example-driven guide to Claude Code — from basic concepts to advanced agents, with copy-paste templates that bring immediate value.

### AI 总结
**简介**: 一个通过可视化教程和即用模板，帮助开发者从入门到精通掌握 Claude Code 的示例驱动指南。

**核心功能**:
- 提供从基础概念到高级代理的10个模块化教程，包含清晰的学习路径。
- 包含大量可直接复制粘贴的生产级配置模板（如斜杠命令、钩子脚本、MCP配置）。
- 内置自我评估和交互式测验（`/self-assessment`, `/lesson-quiz`），帮助用户定位知识缺口。

**技术亮点**: 采用 Mermaid 图表直观展示 Claude Code 各功能内部工作原理，强调特性组合（如命令、内存、子代理、钩子）以构建自动化工作流。

---
## 2. [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice)
- **语言**: Python
- **Stars**: 27,428
- **简介**: Open-Source Frontier Voice AI

### AI 总结
**简介**: VibeVoice 是微软开源的前沿语音AI模型家族，包含文本到语音和语音识别两大核心能力。

**核心功能**:
- **VibeVoice-TTS**: 长文本语音合成模型，支持合成长达90分钟的语音，并模拟最多4个不同的说话人。
- **VibeVoice-ASR**: 语音识别模型，能一次性处理长达60分钟的音频，生成包含说话人、时间戳和内容的结构化转录，支持超过50种语言。
- **VibeVoice‑Realtime‑0.5B**: 实时文本转语音模型，支持流式文本输入和长语音生成。

**技术亮点**:
- 采用**7.5 Hz超低帧率**的连续语音分词器（声学和语义），在保持音频保真度的同时显著提升长序列处理的计算效率。
- 基于**Next-Token Diffusion**框架，结合大语言模型理解文本上下文，并使用扩散头生成高质量语音。
- ASR模型已集成至 **Hugging Face Transformers** 库，便于使用。

---
## 3. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 16,837
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 开发的自进化 AI 代理，具备内置学习循环，能够从经验中创建并改进技能，实现跨会话的持续学习和个性化交互。

**核心功能**:
- **多平台接入**：支持通过 Telegram、Discord、Slack、WhatsApp、Signal 等即时通讯工具以及 CLI 终端进行交互。
- **自我学习与技能管理**：具备闭环学习循环，可自主创建技能、在任务中自我改进，并利用会话搜索和总结实现跨会话记忆。
- **灵活部署与模型支持**：可在多种环境（如本地、Docker、SSH、无服务器平台）运行，并支持切换 Nous Portal、OpenRouter、OpenAI 等多种模型提供商，无需修改代码。
- **自动化与并行处理**：内置定时任务调度器，支持自然语言描述自动化任务；可生成隔离子代理以并行处理工作流。
- **研究友好**：提供批量轨迹生成、强化学习环境和轨迹压缩等功能，支持下一代工具调用模型的训练研究。

**技术亮点**:
- 采用模块化设计，支持与 `agentskills.io` 开放标准及 `Honcho` 用户建模系统兼容。
- 提供六种终端后端，包括支持低成本休眠唤醒的无服务器方案（如 Daytona 和 Modal）。
- 具备完整的终端用户界面（TUI），支持多行编辑、命令自动补全和流式工具输出。

---
## 4. [OpenBB-finance/OpenBB](https://github.com/OpenBB-finance/OpenBB)
- **语言**: Python
- **Stars**: 64,035
- **简介**: Financial data platform for analysts, quants and AI agents.

### AI 总结
**简介**: OpenBB 是一个面向分析师、量化交易员和 AI 代理的开源金融数据平台，旨在整合多种数据源并提供统一的数据访问层。

**核心功能**:
- 提供“一次连接，随处消费”的基础设施层，统一整合专有、授权和公共数据源。
- 通过 Python 包、REST API、OpenBB Workspace（企业级 UI）、Excel 插件和 MCP 服务器等多种方式暴露数据。
- 支持将本地运行的 ODP 后端与云端 OpenBB Workspace 无缝集成，实现数据与 AI 代理的协同工作。

**技术亮点**:
- 基于 Python 构建，可通过 PyPI 快速安装 (`pip install openbb`)。
- 后端采用 FastAPI (通过 Uvicorn 运行)，提供高性能的 API 服务。
- 架构设计灵活，支持数据源和 AI 代理的模块化集成与扩展。

---
## 5. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 123,059
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个基于可组合“技能”和初始指令构建的、用于编码智能体的完整软件开发工作流框架。

**核心功能**:
- **智能规划与设计**：引导用户明确需求，生成易于审阅的模块化设计文档和详细的实现计划。
- **子智能体驱动开发**：通过创建子智能体来执行工程任务，并自动进行代码审查，支持长时间自主工作。
- **强制执行最佳实践**：内置并自动触发多项开发技能，如真正的红绿测试驱动开发、YAGNI和DRY原则。
- **全流程自动化**：覆盖从头脑风暴、Git工作区管理、计划执行、代码审查到分支收尾的完整开发周期。

**技术亮点**: 采用基于“技能”的插件化架构，技能在任务前自动触发，形成强制性的工作流。支持多种主流AI编码平台（如Claude Code、Cursor、Codex等）。

---
## 6. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 42,625
- **简介**: A Claude Code plugin that automatically captures everything Claude does during your coding sessions, compresses it with AI (using Claude's agent-sdk), and injects relevant context back into future sessions.

### AI 总结
**简介**: 一个为 Claude Code 设计的持久化记忆压缩系统，能自动记录编码会话内容，并通过 AI 压缩后为未来会话提供相关上下文。

**核心功能**:
- 自动捕获 Claude 在编码会话期间的所有操作
- 使用 AI（基于 Claude 的 agent-sdk）对捕获的内容进行智能压缩
- 将压缩后的相关上下文注入到未来的会话中，实现记忆延续

**技术亮点**: 基于 TypeScript 开发，利用 Claude 的 agent-sdk 实现 AI 驱动的上下文压缩与检索。

---
## 7. [hacksider/Deep-Live-Cam](https://github.com/hacksider/Deep-Live-Cam)
- **语言**: Python
- **Stars**: 85,336
- **简介**: real time face swap and one-click video deepfake with only a single image

### AI 总结
**简介**: Deep-Live-Cam 是一个基于 Python 的实时人脸替换和视频深度伪造工具，仅需一张图片即可一键生成。

**核心功能**:
- **实时人脸替换**: 支持通过摄像头或视频流进行实时换脸。
- **多功能应用场景**: 包括保留原嘴部动作的“嘴部蒙版”、在多个目标上同时应用不同面孔的“面部映射”、实时替换电影角色面孔、直播表演、制作表情包以及在 Omegle 等平台上使用。
- **简易操作**: 宣称仅需三步（选择面孔、选择摄像头、点击直播）即可完成实时深度伪造。

**技术亮点**: 项目基于 ONNX 模型（如 GFPGANv1.4 和 inswapper_128_fp16.onnx），提供预构建版本（支持 Windows、Mac Silicon 和 CPU）以简化部署，并内置了内容审核机制以防止处理不当媒体。

---
## 8. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 15,409
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个能够跨 Reddit、X、YouTube、Hacker News、Polymarket 和网络等平台，自动研究任何主题并生成有据可查的总结的 AI 智能体技能。

**核心功能**:
- **多平台聚合研究**：自动搜索 Reddit、X（Twitter）、YouTube、Hacker News、Bluesky、Instagram、TikTok 及 Polymarket 预测市场等近 30 天的内容。
- **智能分析与总结**：通过多信号质量排名、相关性评分、去重和跨平台收敛检测，生成带有真实引用的、数据驱动的叙述性总结。
- **对比研究模式**：支持“X vs Y”式对比查询，进行三次并行研究，生成包含优劣势、对比表格和数据驱动结论的并排比较报告。
- **自动存档**：每次运行的研究简报会自动以 `.md` 文件形式保存到本地 `~/Documents/Last30Days/` 目录，构建个人研究库。

**技术亮点**:
- **复合评分管道**：采用双向文本相似性（含同义词扩展）、参与度标准化、来源权威加权、跨平台收敛检测和时间衰减等多维度算法对结果进行排名。
- **模块化配置**：支持通过项目根目录的 `.claude/last30days.env` 文件进行每项目 API 密钥配置，并支持 ScrapeCreators API 统一覆盖多个社交平台。
- **广泛的测试覆盖**：拥有超过 455 个测试，覆盖所有模块，确保稳定性。

---
## 9. [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code)
- **语言**: TypeScript
- **Stars**: 42,748
- **简介**: Bash is all you need - A nano claude code–like 「agent harness」, built from 0 to 1

### AI 总结
**简介**: 一个从零到一构建的、类似 Claude Code 的轻量级智能体“驾驭”框架，强调“模型即智能体”的核心哲学。

**核心功能**:
- 提供一个用于构建和运行真实智能体的工程化框架（Harness）。
- 旨在通过简洁的 Bash 脚本和 TypeScript 实现，将训练好的模型（智能体）接入环境并使其执行任务。

**技术亮点**: 基于 TypeScript 开发，倡导摒弃复杂的“提示词工程”流水线，回归以训练模型为核心的智能体本质。

---
## 10. [fastfetch-cli/fastfetch](https://github.com/fastfetch-cli/fastfetch)
- **语言**: C
- **Stars**: 21,159
- **简介**: A maintained, feature-rich and performance oriented, neofetch like system information tool.

### AI 总结
**简介**: Fastfetch 是一个类似 neofetch 的系统信息获取工具，专注于高性能和高度可定制化，主要用于在终端中以美观的方式展示系统信息。

**核心功能**:
- 跨平台支持：兼容 Linux、macOS、Windows 8.1+、Android、FreeBSD、OpenBSD、NetBSD、DragonFly、Haiku 和 SunOS 等多个操作系统。
- 丰富的自定义选项：用户可以通过配置文件自定义显示内容和样式，项目提供了多种预设示例。
- 高性能：主要使用 C 语言编写，注重执行效率和响应速度。

**技术亮点**:
- 采用 C 语言开发，确保底层性能和高效率。
- 支持模块化配置，允许用户灵活调整显示模块和布局。
- 提供广泛的包管理器支持，包括 Homebrew、APT、Pacman、DNF 等，便于在不同系统上安装和更新。

---
