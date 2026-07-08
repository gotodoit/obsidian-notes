---
tags:
  - github-trending
  - daily
date: 2026-07-08
created: 2026-07-08T01:55:52.969Z
---

# 2026-07-08 GitHub Trending Top 10

## 1. [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)
- **语言**: TypeScript
- **Stars**: 11,104
- **简介**: AI-powered job application framework built on Claude Code. Fork it, fill in your profile, and let Claude evaluate jobs, tailor CVs, write cover letters, and prepare you for interviews.

### AI 总结
**简介**: 一个基于 Claude Code 的 AI 求职框架，通过填写个人资料即可让 AI 自动评估职位、定制简历、撰写求职信并准备面试。

**核心功能**:
- **个人资料设置** (`/setup`)：支持从文档文件夹、粘贴简历或访谈方式自动生成个人画像
- **职位搜索** (`/scrape`)：自动搜索多个求职门户，去重并按匹配度排序展示
- **智能评估** (`/rank`)：对批量职位进行框架化评分，生成排名短名单
- **自动申请** (`/apply`)：评估匹配度、生成定制化简历（LaTeX）和求职信，经审核代理修订后输出终稿
- **结果追踪** (`/outcome`)：记录申请进展（面试、录用、拒绝等），归档提交材料

**技术亮点**:
- 基于 Claude Code CLI 构建，语言和国家无关的核心框架
- 丹麦市场求职门户搜索工具（Jobindex、Jobnet 等）可替换为本地职位板
- 采用双代理流水线（起草+审核），编码职业指导最佳实践
- 支持 LaTeX 编译（lualatex/xelatex），可选 ATS 可解析性检查

---
## 2. [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)
- **语言**: Rust
- **Stars**: 20,797
- **简介**: Privacy first, AI meeting assistant with 4x faster Parakeet/Whisper live transcription, speaker diarization, and Ollama summarization built on Rust. 100% local processing. no cloud required. Meetily (Meetly Ai - https://meetily.ai) is the #1 Self-hosted, Open-source Ai meeting note taker for macOS & Windows.

### AI 总结
**简介**: Meetily 是一款基于 Rust 构建的隐私优先 AI 会议助手，支持 4 倍速 Parakeet/Whisper 实时转录、说话人分离和 Ollama 摘要，所有处理均在本地完成，无需云端。

**核心功能**:
- 实时会议转录与说话人分离
- 本地 AI 摘要生成
- 支持 macOS 和 Windows
- 100% 本地处理，保护数据隐私
- 离线运行，兼容多种会议平台

**技术亮点**: 基于 Rust 构建，使用 Parakeet/Whisper 进行转录，集成 Ollama 进行摘要，支持自托管和开源定制。

---
## 3. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 72,206
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 一个为 AI 编码代理提供“生产级工程技能”的开源项目，通过预定义的技能和工作流，帮助 AI 代理遵循资深工程师的最佳实践进行软件开发。

**核心功能**:
- **开发全生命周期支持**: 提供 8 个斜杠命令，涵盖从需求定义（`/spec`）、计划（`/plan`）、构建（`/build`）、测试（`/test`）到审查（`/review`）、性能审计（`/webperf`）、代码简化（`/code-simplify`）和发布（`/ship`）的完整流程。
- **自动化构建流程**: 支持 `/build auto` 命令，在用户一次批准计划后，自动执行所有任务，实现无人干预的增量开发。
- **上下文感知技能激活**: 技能会根据当前任务（如设计 API、构建 UI）自动激活，无需手动切换。
- **多代理平台兼容**: 通过 [skills CLI](https://github.com/vercel-labs/skills) 可安装到 70 多个 AI 代理中，包括 Claude Code、Cursor、Codex、Copilot、Cline 等。

**技术亮点**:
- **基于 Markdown 的技能定义**: 所有技能封装为 `SKILL.md` 文件，易于理解和修改。
- **模块化与可组合**: 提供 24 个独立的技能，可按需选择安装（如 `code-review-and-quality`、`test-driven-development`）。
- **原生集成支持**: 为 Claude Code、Cursor、Gemini CLI、Windsurf 等主流代理提供原生插件或规则配置方式。
- **开源与社区驱动**: 项目托管在 GitHub 上，遵循 MIT 开源协议。

---
## 4. [ruvnet/RuView](https://github.com/ruvnet/RuView)
- **语言**: Rust
- **Stars**: 78,532
- **简介**: π RuView turns commodity WiFi signals into real-time spatial intelligence, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: RuView 是一个基于 WiFi 信号的无接触式空间感知平台，能够穿透墙壁实现人员检测、生命体征监测和活动识别，无需摄像头或可穿戴设备。

**核心功能**:
- **存在与占用检测**：透过墙壁检测人员，追踪进出和计数
- **生命体征监测**：无接触测量呼吸频率和心率
- **活动识别**：识别行走、坐姿、手势、跌倒等动作
- **环境映射**：通过射频指纹识别房间、检测家具移动和新物体
- **睡眠质量分析**：整夜监测，包括睡眠阶段分类和呼吸暂停筛查
- **智能家居集成**：原生支持 Home Assistant、Apple Home、Google Home、Alexa 和 Matter 协议，提供 21 个实体节点（含 11 个原始信号和 10 个语义状态）

**技术亮点**:
- 基于 Rust 开发，运行在低至 9 美元的 ESP32 传感器上
- 利用信道状态信息（CSI）和脉冲神经网络实现本地学习，30 秒内适应新环境
- 多频段 WiFi 网格扫描（6 个信道），利用邻居路由器作为免费雷达源
- 8KB 的 4-bit 量化模型，在树莓派上微秒级推理，时间三元组准确率达 82.3%
- 通过 Ed25519 见证链实现加密认证，无需云端或互联网

---
## 5. [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)
- **语言**: JavaScript
- **Stars**: 53,054
- **简介**: Extracted system prompts from Anthropic - Claude Fable 5, Opus 4.8, Claude Code, Claude Design. OpenAI - ChatGPT 5.5 Thinking, GPT 5.5 Instant, Codex. Google - Gemini 3.5 Flash, 3.1 Pro, Antigravity. xAI - Grok, Cursor, Copilot, VS Code, Perplexity, and more. Updated regularly.

### AI 总结
**简介**: 该项目系统性地收集并持续更新各大AI聊天机器人（如Claude、ChatGPT、Gemini、Grok等）的内部系统提示词（System Prompts），旨在透明化这些模型的底层指令。

**核心功能**:
- 提供Anthropic、OpenAI、Google、xAI、Microsoft等公司最新AI模型的系统提示词原文。
- 支持不同模型版本的对比（如Claude Opus 4.8 vs Fable 5的差异）。
- 涵盖多种产品形态，包括网页版、桌面应用、代码编辑器（VS Code、Copilot）、移动端及API版本。
- 定期更新，并接受社区贡献（Pull Request）。

**技术亮点**:
- 项目本身为纯文档仓库，使用Markdown文件存储提示词，技术门槛低。
- 通过GitHub的版本控制功能，可追踪提示词的历史变更。
- 额外提供Diff工具链接，方便用户直观比较不同版本间的指令差异。

---
## 6. [TencentCloud/CubeSandbox](https://github.com/TencentCloud/CubeSandbox)
- **语言**: Rust
- **Stars**: 8,485
- **简介**: Instant, Concurrent, Secure & Lightweight Sandbox for AI Agents.

### AI 总结
**简介**: CubeSandbox 是一个基于 RustVMM 和 KVM 构建的即时、并发、安全且轻量的沙箱服务，专为 AI 代理设计，可在 60ms 内创建硬件隔离的沙箱，内存开销低于 5MB。

**核心功能**:
- **即时启动**: 沙箱创建时间低于 60ms，支持高并发和高密度部署。
- **硬件级隔离**: 基于 KVM 实现硬件级安全隔离，确保代理运行环境安全。
- **E2B SDK 兼容**: 兼容 E2B 接口，可无缝集成现有工具链。
- **自动暂停/恢复**: 空闲沙箱自动挂起，请求时自动唤醒，优化资源利用。
- **快照与回滚**: 支持事件级快照、即时克隆和状态回滚（v0.3.0 引入）。
- **凭证保险库**: 代理调用外部 API 时，密钥不进入沙箱，增强安全性。
- **网络策略强化**: 支持每沙箱流量令牌和策略路由出口。

**技术亮点**: 采用 RustVMM 和 KVM 技术栈，支持单节点部署和轻松扩展至多节点集群，已加入 CNCF Landscape。

---
## 7. [AhmadIbrahiim/Website-downloader](https://github.com/AhmadIbrahiim/Website-downloader)
- **语言**: HTML
- **Stars**: 4,041
- **简介**: 💡 Download the complete source code of any website (including all assets). [ Javascripts, Stylesheets, Images ] using Node.js

### AI 总结
**简介**: 一个基于 Node.js 的网站源码下载器，可完整下载任意网站的全部资源（包括 JS、CSS、图片等），并打包压缩后通过 Socket 通道发送给用户。

**核心功能**:
- 使用 `wget` 递归下载网站所有页面及资源文件（HTML、CSS、JS、图片等）
- 自动转换链接为相对路径，支持离线浏览
- 通过 Socket 实时传输下载后的压缩包给用户
- 提供一键部署到 Replit、Glitch、Railway、Render 等多个云平台

**技术亮点**:
- 技术栈：Node.js + `wget` + `archiver` + Socket.io
- 使用 `wget` 的高级参数（`--mirror`、`--convert-links`、`--page-requisites` 等）实现完整镜像下载
- 支持实时进度反馈和压缩包即时传输

---
## 8. [steipete/CodexBar](https://github.com/steipete/CodexBar)
- **语言**: Swift
- **Stars**: 17,051
- **简介**: Show usage stats for OpenAI Codex and Claude Code, without having to login.

### AI 总结
**简介**: CodexBar 是一款 macOS 菜单栏应用，无需登录即可实时显示 OpenAI Codex、Claude Code 等 AI 编码提供商的用量统计和重置倒计时。

**核心功能**:
- **用量监控**: 在菜单栏显示各 AI 提供商（如 Codex、OpenAI、Claude、Cursor、Gemini 等 57+ 个）的 token/额度/费用限制，并高亮显示重置倒计时。
- **多模式显示**: 支持每个提供商独立显示状态图标，或合并图标模式通过切换器查看。
- **数据来源多样**: 支持 OAuth、设备流、API 密钥、浏览器 Cookie、本地文件等多种方式复用现有会话，无需存储密码。
- **状态与告警**: 轮询提供商状态，在菜单栏显示故障徽章和图标覆盖层。
- **CLI 配置**: 通过命令行启用/禁用提供商、设置 API 密钥，支持脚本化批量管理。

**技术亮点**:
- 基于 Swift 开发，仅支持 macOS 14+。
- 无 Dock 图标，极简 UI，动态菜单栏图标。
- 隐私优先设计，不存储用户密码。
- 支持 Homebrew、AUR 和 CLI 压缩包安装（macOS/Linux）。

---
## 9. [dotnet/skills](https://github.com/dotnet/skills)
- **语言**: C#
- **Stars**: 4,318
- **简介**: Repository for skills to assist AI coding agents with .NET and C#

### AI 总结
**简介**: 这是 .NET 团队为 AI 编程助手（如 Copilot、Claude Code、Cursor、Codex CLI）精心策划的一套核心技能和自定义代理集合，旨在提升 .NET 和 C# 开发效率。

**核心功能**:
- **语言与开发**: 提供 C# 语言服务器 (LSP) 集成及高级 .NET 开发技能。
- **构建与测试**: 涵盖 MSBuild 构建诊断、性能优化、测试运行、生成、分析及框架迁移。
- **数据与诊断**: 提供 .NET 数据访问（EF Core）、性能调查、调试和故障分析技能。
- **包管理与升级**: 支持 NuGet 包管理、依赖管理及 .NET 项目跨版本迁移和升级。
- **框架与UI**: 包含 ASP.NET Core、Blazor、.NET MAUI 等框架的开发、诊断和故障排除技能。
- **AI与模板**: 提供 AI/ML 集成（LLM、RAG、MCP）和 .NET 模板引擎（项目脚手架、模板创作）技能。

**技术亮点**: 遵循 [agentskills.io](https://agentskills.io) 开放标准，支持作为插件市场集成到主流 AI 编码工具（Copilot CLI、VS Code、Cursor、Codex CLI），并提供准确性和效率评分仪表盘。

---
## 10. [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)
- **语言**: C#
- **Stars**: 10,070
- **简介**: OfficeCLI is the first and best Office suite purpose-built for AI agents to read, edit, and automate Word, Excel, and PowerPoint files. Free, open-source, single binary, no Office installation required.

### AI 总结
**简介**: OfficeCLI 是全球首个专为 AI 智能体设计的开源 Office 套件，通过单行命令实现对 Word、Excel、PowerPoint 文件的读取、编辑与自动化操作，无需安装 Office 软件。

**核心功能**:
- **AI 智能体集成**：支持 Claude Code、Cursor、Windsurf、GitHub Copilot 等主流 AI 编码工具，智能体可自动安装并调用 OfficeCLI 命令创建、读取、编辑文档。
- **多格式支持**：覆盖 .docx、.xlsx、.pptx 文件，提供创建、添加内容、实时预览、修改和删除等操作。
- **实时预览与反馈闭环**：内置 HTML 渲染引擎，可将文档转换为 HTML 或 PNG，支持浏览器实时预览，实现“渲染→观察→修正”的迭代流程。
- **自然语言驱动**：可通过 AionUi 桌面应用或 CLI 命令行，用自然语言描述需求即可自动生成文档。

**技术亮点**:
- **单二进制文件**：无依赖，跨平台运行（macOS/Linux/Windows），支持通过 curl、brew、npm 等一键安装。
- **内置 HTML 渲染引擎**：高保真还原文档格式，为 AI 提供视觉反馈能力，支持实时预览与动态更新。
- **零 Office 依赖**：无需安装 Microsoft Office 或任何第三方库，独立运行。
- **Apache 2.0 开源许可**：代码完全开放，社区驱动。

---
