---
tags:
  - github-trending
  - daily
date: 2026-07-07
created: 2026-07-07T01:55:44.903Z
---

# 2026-07-07 GitHub Trending Top 10

## 1. [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)
- **语言**: JavaScript
- **Stars**: 51,609
- **简介**: Extracted system prompts from Anthropic - Claude Fable 5, Opus 4.8, Claude Code, Claude Design. OpenAI - ChatGPT 5.5 Thinking, GPT 5.5 Instant, Codex. Google - Gemini 3.5 Flash, 3.1 Pro, Antigravity. xAI - Grok, Cursor, Copilot, VS Code, Perplexity, and more. Updated regularly.

### AI 总结
**简介**: 一个持续更新的系统提示词泄露库，收录了 Anthropic、OpenAI、Google、xAI 等主流 AI 聊天机器人的系统指令。

**核心功能**:
- 收集并公开 Claude、ChatGPT、Gemini、Grok 等 AI 模型的系统提示词
- 提供不同版本（如 Claude Fable 5、Opus 4.8）的提示词对比（含 Diff 链接）
- 涵盖多种集成场景：Claude Code、GitHub Copilot、VS Code Agent、Zed AI 等
- 定期更新，跟踪最新模型与官方提示词变化

**技术亮点**:
- 使用 JavaScript 编写，通过 GitHub 流量徽章和提交记录展示活跃度
- 支持 PR 贡献，欢迎社区提交新的系统提示词
- 被《华盛顿邮报》引用，具备媒体影响力

---
## 2. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 70,885
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 一个为 AI 编码代理提供生产级工程技能的规则和指令集合，帮助代理遵循资深工程师的工作流程、质量门禁和最佳实践。

**核心功能**:
- 提供 24 个生产级工程技能，覆盖从需求定义到发布的完整开发周期。
- 通过 8 个斜杠命令 (`/spec`, `/plan`, `/build`, `/test` 等) 激活对应技能，实现自动化工作流。
- 支持 `/build auto` 一键式自动执行：批准计划后，代理自动完成所有任务的实现、测试和提交，遇到失败会暂停。
- 技能会根据当前任务（如设计 API、构建 UI）自动激活，无需手动切换。
- 提供 `npx skills add` 快速安装，支持 70+ 种 AI 代理（Claude Code, Cursor, Copilot 等）。

**技术亮点**:
- 基于 JavaScript 开发，通过 CLI 工具 (`skills`) 和插件市场分发。
- 原生集成 Claude Code、Cursor、Gemini CLI、Windsurf 等主流 AI 编码工具。
- 遵循“测试驱动开发”、“小步迭代”、“先规范后代码”等工程原则，确保代码质量和可维护性。

---
## 3. [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)
- **语言**: Rust
- **Stars**: 19,460
- **简介**: Privacy first, AI meeting assistant with 4x faster Parakeet/Whisper live transcription, speaker diarization, and Ollama summarization built on Rust. 100% local processing. no cloud required. Meetily (Meetly Ai - https://meetily.ai) is the #1 Self-hosted, Open-source Ai meeting note taker for macOS & Windows.

### AI 总结
**简介**: Meetily 是一款基于 Rust 构建、注重隐私的 AI 会议助手，支持实时转录、说话人识别和会议总结，所有处理均在本地完成，无需云端。

**核心功能**:
- **实时转录**: 支持 Parakeet/Whisper 模型，速度提升 4 倍，实现低延迟的语音转文字。
- **说话人识别**: 自动区分不同发言者，便于跟踪会议参与者的对话内容。
- **会议总结**: 集成 Ollama 模型，本地生成会议摘要，无需联网。
- **完全本地化**: 100% 本地处理，数据不离开设备，保障隐私安全。
- **跨平台支持**: 兼容 macOS 和 Windows 系统，可离线使用。

**技术亮点**:
- 采用 **Rust** 语言开发，确保高性能和内存安全。
- 基于 **Ollama** 和 **Whisper/Parakeet** 等开源 AI 模型，实现完全自托管。
- 架构设计注重数据主权，无供应商锁定，符合企业合规要求。

---
## 4. [ruvnet/RuView](https://github.com/ruvnet/RuView)
- **语言**: Rust
- **Stars**: 77,554
- **简介**: π RuView turns commodity WiFi signals into real-time spatial intelligence, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: RuView 是一个基于 WiFi 信号的非接触式空间感知平台，利用普通 WiFi 实现穿墙人体检测、生命体征监测和活动识别，无需摄像头或穿戴设备。

**核心功能**:
- **穿墙存在检测** — 检测人员存在、计数及进出房间
- **生命体征监测** — 无接触测量呼吸频率和心率
- **活动识别** — 识别行走、坐姿、手势、跌倒等动作
- **环境映射** — 通过射频指纹识别房间、检测家具移动和新物体
- **睡眠质量分析** — 整夜监测睡眠阶段分类和呼吸暂停筛查
- **智能家居集成** — 原生支持 Home Assistant、Apple Home、Google Home、Alexa 和 Matter 协议

**技术亮点**:
- 基于 ESP32 低成本硬件（每节点约 9 美元），完全本地边缘计算
- 使用 Channel State Information (CSI) 从 WiFi 信号提取空间信息
- 采用脉冲神经网络（SNN）实现 30 秒内环境自适应学习
- 多频段 6 信道扫描，利用邻居路由器作为免费雷达源
- 模型仅 8 KB（4 bit 量化），可在树莓派上微秒级运行
- 通过 Ed25519 见证链实现加密认证
- 预训练模型已发布在 Hugging Face，时间三元组准确率 82.3%

---
## 5. [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)
- **语言**: JavaScript
- **Stars**: 59,003
- **简介**: Taste-Skill - gives your AI good taste. stops the AI from generating boring, generic slop

### AI 总结
**简介**: Taste-Skill 是一个为 AI 代理提供的前端框架，旨在通过注入设计品味，避免生成千篇一律、无聊的界面，产出更具视觉吸引力的 UI。

**核心功能**:
- **提升 AI 生成界面的设计质量**: 通过预设的设计规则，强化布局、排版、动效和间距，替代默认的样板化 UI。
- **提供可移植的 Agent Skills**: 包含代码生成和图像生成两种技能，可通过 `npx skills add` 命令轻松安装到 Codex、Cursor、Claude 等工具中。
- **图像生成参考板**: 内置用于生成 Web、移动端、品牌套件等参考板的图像技能，可与 ChatGPT Images 等生成器配合使用。
- **提供多种预设技能**: 包含 `design-taste-frontend`（默认，v2 实验版）和 `design-taste-frontend-v1`（稳定版）等多种技能，满足不同需求。

**技术亮点**: 基于 JavaScript 开发，与 Vercel 的 Agent Skills 生态系统兼容，使用 `SKILL.md` 文件定义技能，支持通过 CLI 或直接复制文件进行安装和升级。

---
## 6. [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills)
- **语言**: Python
- **Stars**: 21,182
- **简介**: 345 Claude Code skills & agent skills & plugins (30+ Agents, 70+ custom commands, 330+ skills, customizable references, scripts)for Claude Code, Codex, Gemini CLI, Cursor, and 8 more coding agents — engineering, marketing, product, compliance, C-level advisory, research, business operations, commercial & finance, and your daily productivity skills.

### AI 总结
**简介**: claude-skills 是一个拥有 355 个生产级技能的、最全面的开源 AI 编码代理技能库，支持 Claude Code、OpenAI Codex、Gemini CLI、Cursor 等 13 种编码工具。

**核心功能**:
- **海量即用技能**: 提供 355 个覆盖工程、DevOps、营销、安全、合规、C-level 咨询、学术研究、企业运营等领域的模块化技能包。
- **多代理支持**: 原生支持 13 种主流 AI 编码代理，包括 Claude Code、Codex、Gemini CLI、Cursor 等。
- **结构化知识体系**: 每个技能包含 SKILL.md 指令文件、602 个 Python 脚本（纯标准库，零依赖）和 711 个参考文档/模板/清单。
- **三种协作模式**: 清晰区分 Skills（如何执行任务）、Agents（执行什么任务）和 Personas（谁在思考），支持组合编排。
- **一键安装**: 提供针对 Claude Code (插件市场) 和 Gemini CLI (脚本) 的快速安装命令，支持按领域（工程、产品、营销等）批量安装。

**技术亮点**:
- **纯 Python 标准库**: 所有 602 个 CLI 脚本仅依赖 Python 标准库，无需任何 `pip install`，跨平台兼容。
- **多工具适配架构**: 通过 `scripts/convert.sh` 脚本，可轻松将技能转换为更多工具的格式，实现“一次构建，多处运行”。
- **模块化与可组合**: 技能、代理、角色三者解耦，用户可根据需求灵活组合，构建定制化的 AI 工作流。

---
## 7. [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)
- **语言**: JavaScript
- **Stars**: 26,301
- **简介**: Use Codex from Claude Code to review code or delegate tasks.

### AI 总结
**简介**: 一个用于 Claude Code 的插件，允许用户在 Claude Code 工作流中直接调用 OpenAI Codex 进行代码审查或任务委派。

**核心功能**:
- **代码审查**: 提供 `/codex:review` 命令，对当前未提交的更改或分支进行只读代码审查。
- **对抗性审查**: 提供 `/codex:adversarial-review` 命令，对实现方案、设计选择和潜在风险进行可引导的挑战性审查。
- **任务委派与后台管理**: 通过 `/codex:rescue` 将调试、修复等任务委派给 Codex 后台执行，并使用 `/codex:status`、`/codex:result` 和 `/codex:cancel` 管理任务状态。

**技术亮点**: 基于 JavaScript 开发，通过 Claude Code 的插件系统集成，利用 Node.js 18.18+ 环境运行，支持后台任务和模型选择（如指定 `--model` 参数）。

---
## 8. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 49,793
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: /last30days 是一个 AI 代理驱动的搜索引擎，能够跨 Reddit、X、YouTube、HN、Polymarket 和 GitHub 等多个平台并行搜索，并基于用户互动（如点赞、投票、实际金钱）对结果评分，最终生成一份综合摘要。

**核心功能**:
- **多平台并行搜索**: 同时搜索 Reddit、X、YouTube、TikTok、Hacker News、Polymarket、GitHub 等平台，获取分散在不同“围墙花园”中的信息。
- **基于真实互动的评分**: 使用 Reddit 的点赞、X 的喜欢、YouTube 的转录、Polymarket 的真实金钱赔率等作为评分依据，而非编辑推荐。
- **AI 代理合成摘要**: 利用 AI 代理将来自多个平台的搜索结果整合成一份简洁、有根据的摘要。
- **零配置快速启动**: Reddit、HN、Polymarket 和 GitHub 无需额外配置即可使用，并通过 30 秒的设置向导解锁 X、YouTube、TikTok 等更多平台。

**技术亮点**: 基于 Python 开发，采用 Agent Skills 架构，支持通过 `npx skills add` 或 `plugin` 命令轻松安装到 Claude Code、Cursor、Copilot 等 50 多个 AI 代理平台。

---
## 9. [ogulcancelik/herdr](https://github.com/ogulcancelik/herdr)
- **语言**: Rust
- **Stars**: 12,905
- **简介**: agent multiplexer that lives in your terminal.

### AI 总结
**简介**: herdr 是一个运行在终端中的代理多路复用器，让你在一个终端内同时管理多个编码代理，并实时查看它们的状态。

**核心功能**:
- **每个代理拥有独立真实终端**：每个代理运行在自己的真实终端内，支持全屏 TUI 应用，而非模拟终端。
- **代理状态一目了然**：侧边栏直观显示每个代理的状态（阻塞、工作中、完成、空闲），无需额外配置。
- **工作区、标签页和窗格**：支持按仓库或文件夹组织，可通过鼠标点击、拖拽进行分割和排列。
- **持久化会话**：断开连接后后台服务器保持代理和窗格存活，可随时从任何终端（包括通过 SSH 的手机）重新连接。
- **跨平台运行**：单个约 10MB 的 Rust 二进制文件，支持 Linux、macOS 和 Windows，无依赖，可在任何支持 SSH 的环境中运行。
- **可脚本化**：提供本地 Socket API 和 CLI，代理可驱动，并支持用任意语言编写插件。

**技术亮点**: 使用 Rust 开发，单二进制文件，无 GUI、无 Electron、无账户、无遥测，轻量高效。

---
## 10. [bradautomates/claude-video](https://github.com/bradautomates/claude-video)
- **语言**: Python
- **Stars**: 4,281
- **简介**: Give Claude the ability to watch any video. /watch downloads, extracts frames, transcribes, hands it all to Claude.

### AI 总结
**简介**: 一个让 Claude 能够“观看”任何视频的插件，通过下载、提取关键帧、转录字幕，将视频内容呈现给 Claude。

**核心功能**:
- 支持 YouTube、Loom、TikTok 等数百个平台视频 URL 及本地视频文件（.mp4、.mov 等）。
- 自动提取场景感知或快速关键帧，配合时间戳转录字幕，让 Claude 同时“看到”画面和“听到”音频。
- 提供不同帧预算模式（efficient/balanced/token-burner），平衡 token 消耗与分析精度。
- 内置字幕获取（优先免费原生字幕，无字幕时自动调用 Whisper API 转录）。

**技术亮点**: 采用 yt-dlp 下载视频/字幕，ffmpeg 提取帧，Whisper（Groq 或 OpenAI）作为转录后备，所有帧以 JPEG 格式直接嵌入 Claude 上下文。

---
