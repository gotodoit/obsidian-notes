---
tags:
  - github-trending
  - daily
date: 2026-09-15
created: 2026-09-15T01:55:42.521Z
---

# 2026-09-15 GitHub Trending Top 10

## 1. [JustVugg/colibri](https://github.com/JustVugg/colibri)
- **语言**: C
- **Stars**: 32,149
- **简介**: Run frontier MoE models on hardware you already own — pure C, zero deps, experts streamed from disk. Tiny engine, immense model. 🐦

### AI 总结
**简介**: Colibrì 是一个用纯 C 编写的轻量级 MoE 推理引擎，通过将存储、内存和显存统一为多级推理层级，让消费级硬件也能运行 744B 至 2.8T 参数的前沿 MoE 大模型。

**核心功能**:
- 支持九大模型家族（GLM-5.2/5.3 744B、Kimi K3 2.8T、DeepSeek V4 系列、Qwen 系列、OLMoE 等），每个模型对应一个 C 文件，共用 `coli chat` / `coli serve` / `coli web` 前端
- 专家权重从磁盘流式加载，按需驻留显存/内存，实现超大模型的本地推理
- 提供 Web 仪表盘，实时可视化 token 指标、硬件状态、专家分层与路由热度（Brain 页、Atlas 页）

**技术亮点**:
- 纯 C 实现，零引擎依赖，将 VRAM、RAM、磁盘视为单一多级内存层级（AI memory multitiering）
- 默认策略不静默改变模型精度或路由语义，保证语义正确性；速度无 SLA，但端到端可复现测量作为实验取舍标准
- 覆盖模型格式、内存层级、存储 I/O、放置调度、内核、推测解码、CPU/GPU 重叠等全栈系统优化
- 示例：744B 模型在 6× RTX 5090 上实现 4 tok/s、TTFT 1.6s、磁盘零读取的完全专家驻留

---
## 2. [alibaba/open-code-review](https://github.com/alibaba/open-code-review)
- **语言**: Go
- **Stars**: 25,869
- **简介**: Fast, efficient, battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level comments, built-in multi-language ruleset (NPE, thread-safety, XSS, SQL injection), OpenAI & Anthropic compatible.

### AI 总结
**简介**: 阿里巴巴开源的 AI 代码审查 CLI 工具，基于混合架构（确定性流水线 + LLM Agent），经阿里内部大规模验证，可精确到行级生成审查意见。

**核心功能**:
- 读取 Git diff，将变更文件交由具备工具调用能力的 LLM Agent 进行深度审查，生成行级精度的结构化评论
- Agent 可读取完整文件内容、搜索代码库、查看其他变更文件以获取上下文，实现超越表层 diff 的深度审查
- `ocr scan` 支持对整个文件进行审查，适用于审计陌生代码库或无有效 diff 的目录
- 内置多语言规则集，覆盖 NPE、线程安全、XSS、SQL 注入等常见缺陷
- 兼容 OpenAI 与 Anthropic 模型接口，支持 Claude Code、Codex、Cursor 等 Agent

**技术亮点**:
- 混合架构：确定性流水线 + LLM Agent 协同工作
- 基于 50 个开源仓库、200 个真实 PR、10 种编程语言构建的 AACR-Bench 基准测试，由 80+ 资深工程师交叉验证（1,505 条标注问题）
- 相比通用 Agent（如 Claude Code），在相同底层模型下 Precision 与 F1 显著更高，Token 消耗仅约 1/9，审查速度更快
- 以精度优先为设计取舍，主动降低 Recall 以减少噪音干扰
- 使用 Go 语言开发，跨平台支持 Windows / macOS / Linux，获 OpenSSF Gold 认证

---
## 3. [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE)
- **语言**: Python
- **Stars**: 8,372
- **简介**: YuE2: frontier music generation with symbolic planning, zero-shot covers, and agentic music editing.

### AI 总结
**简介**: YuE2 是新一代前沿音乐生成模型，通过符号化规划将歌词与风格提示转化为可编辑的乐谱，再渲染成带人声与伴奏的完整歌曲。

**核心功能**:
- **高质量歌曲生成**：在 WildSongBench 上媲美 Suno v5/v6，best-of-8 取得 6.9632 SongBench Avg 最高均值
- **白盒符号化规划**：旋律与和弦以显式乐谱形式呈现，人和 Agent 均可读取、播放并修改
- **零样本翻唱**：将转录歌曲重新演绎为全新风格
- **Agent 音乐编辑**：通过对话对乐谱、编曲、歌词进行迭代修改（演示中 9 步 14 版从国语流行改为英文爵士）

**技术亮点**:
- **AR–NAR Mixture-of-Transformers 骨干**：自回归预测乐谱与语义 token，再用 flow matching 生成声学潜变量
- **VAE 解码**：将潜变量解码为 48 kHz 立体声，无需量化
- **分阶段 Python API**：`plan()` → `generate_semantic()` → `synthesize()` → `decode()`
- **配套模型与基准**：MERT2、SheetSage2、WildSongBench（WSB）
- **环境要求**：Linux / Python 3.12 / 支持 BF16 的 NVIDIA GPU（24 GB 显存）

---
## 4. [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio)
- **语言**: Python
- **Stars**: 29,280
- **简介**: VoiceStudio is the open-source, fully-local ElevenLabs alternative — voice cloning, voice design, video dubbing, dictation, transcription & audiobook creation in 646 languages.

### AI 总结
**简介**: VoiceStudio 是一个完全本地运行的开源 ElevenLabs 替代方案，支持语音克隆、语音设计、视频配音、听写、转录和有声书制作，覆盖 646 种语言。

**核心功能**:
- **语音克隆与设计**：通过音频克隆声音，或按设计创建全新声音，支持语音到语音转换
- **视频配音**：支持文件上传或 URL 导入，内置项目管理面板可重新打开历史配音项目
- **听写与转录**：集成多种 ASR 引擎，支持长音频转录
- **有声书与批量生成**：支持故事、有声书和批量音频生成工作流
- **多引擎切换**：内置 16 个 TTS 引擎和 11 个 ASR 引擎，可通过快捷键 Ctrl/Cmd+E 快速切换

**技术亮点**:
- 完全本地化运行，无需账号、API Key、订阅或用量计费
- 支持 CUDA、Apple Silicon MPS/MLX、Linux ROCm、CPU 及可选远程 Worker 多种计算后端
- 提供桌面应用、本地 REST/SSE/WebSocket API、OpenAI 兼容音频 API 和 MCP Server 多种接口
- 跨平台支持 macOS 13.3+（Apple Silicon）、Windows 10/11 x64、Linux x86_64（glibc 2.39+）及 Docker
- 基于 Python 开发，采用 AGPL-3.0 许可证
- 当前处于活跃 Beta 阶段，正在进行 Electron 重写

---
## 5. [666ghj/MiroFish](https://github.com/666ghj/MiroFish)
- **语言**: Python
- **Stars**: 73,188
- **简介**: A Simple and Universal Swarm Intelligence Engine, Predicting Anything. 简洁通用的群体智能引擎，预测万物

### AI 总结
**简介**: MiroFish 是一个基于多智能体技术的通用群体智能预测引擎，通过构建高保真平行数字世界来推演未来走向。

**核心功能**:
- **种子信息提取与数字世界构建**：从真实世界（突发新闻、政策草案、金融信号等）提取种子信息，自动构建高保真平行数字世界
- **大规模智能体自由交互**：数千个具备独立人格、长期记忆和行为逻辑的智能体在数字世界中自由交互与社会演化
- **上帝视角变量注入**：用户可从全局视角动态注入变量，精确推演未来轨迹
- **自然语言预测**：只需上传种子材料并用自然语言描述预测需求，即可获得详细预测报告和可深度交互的数字世界

**技术亮点**:
- 基于 Python 开发，采用多智能体（Multi-Agent）架构
- 支持 Docker 部署
- 提供在线演示环境（Live Demo）和 DeepWiki 文档
- 应用场景覆盖宏观决策推演（政策/公关零风险测试）与微观创意沙盒（小说结局推演等）

---
## 6. [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)
- **语言**: Python
- **Stars**: 81,310
- **简介**: Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees.

### AI 总结
**简介**: Agent Reach 是一个开源 Python CLI 工具，为 AI Agent 一键接入互联网能力，免费读取和搜索 Twitter、Reddit、YouTube、GitHub、B站、小红书等平台内容。

**核心功能**:
- 多平台内容读取：支持 YouTube 字幕提取、Reddit 搜索、Twitter 搜索、B站视频总结、小红书内容查看、网页阅读、RSS 订阅等
- 全网语义搜索（通过 MCP 接入，免费无需 API Key）
- 一条命令完成安装与更新，兼容 Claude Code、Cursor、Windsurf 等任意可执行命令行的 Agent
- 自带 `agent-reach doctor` 诊断命令，快速定位各平台连通性问题
- 多后端路由（首选 + 备选），某接入方式失效时自动切换，用户无感

**技术亮点**:
- 基于 Python 3.10+，MIT 开源协议
- 零 API 费用，所有工具开源、API 免费，Cookie 仅存本地保障隐私
- 持续追踪各平台风控变化并自动适配（如 B站风控封禁后自动切换至 bili-cli）
- 唯一潜在成本为服务器代理（约 $1/月），本地运行无需额外费用

---
## 7. [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)
- **语言**: JavaScript
- **Stars**: 66,787
- **简介**: Extracted system prompts from Anthropic - Claude Fable 5.1, Opus 5, Claude Design, Claude Code. OpenAI - ChatGPT GPT-6-Astra, Codex. Google - Gemini 3.8 Flash, 3.1 Pro, Antigravity. xAI - Grok, Grok Bot, Cursor, Kimi and more! Updated regularly.

### AI 总结
**简介**: 一个持续收集并逐字记录各大 AI 聊天机器人系统提示词（System Prompts）的开源仓库，覆盖 Anthropic、OpenAI、Google、xAI 等主流厂商。

**核心功能**:
- 收录 Anthropic Claude 系列（Fable 5.1、Opus 5、Sonnet 5、Claude Code、Claude Design、Claude Cowork 等）的完整系统提示词
- 收录 OpenAI 系列（ChatGPT GPT-6-Astra、Codex、GPT-5.6 等）的系统提示词
- 收录 Google（Gemini 3.8 Flash、3.7 Flash、3.1 Pro、Antigravity）、xAI（Grok 4.6、Grok Bot）、Perplexity、Kimi、Meta Muse Code、Cursor 等多平台提示词
- 提供按厂商和模型分类的目录结构，附带最近更新记录表，持续追踪新版本

**技术亮点**:
- 以 Markdown 文件组织内容，按厂商分目录（Anthropic、OpenAI、Google、xAI 等），便于查阅和引用
- 被《华盛顿邮报》和 CEPS' AI World 等媒体引用作为数据来源，具有一定行业影响力
- 仓库以 JavaScript 为主要语言，欢迎社区通过 PR 贡献新内容

---
## 8. [rlaope/oh-my-hermes](https://github.com/rlaope/oh-my-hermes)
- **语言**: Python
- **Stars**: 2,067
- **简介**: All in one plugin for Hermes Agent ⚚ the coding intelligence, a long-term memory system and model optimized workflow packages

### AI 总结
**简介**: oh-my-hermes（OMH）是 Hermes Agent 的一体化增强插件，在保留 Hermes 原生能力的基础上，为其添加长期记忆系统与模型优化的工作流层。

**核心功能**:
- 工作流编排：覆盖规划、研究、创作、编码交接与运维等场景，明确证据边界
- 长期记忆系统：为 Hermes Agent 提供项目级记忆能力
- 模型优化工作流包：将普通请求转化为清晰的能力调用与可追溯的执行记录
- 原生技能调度：在治理路径下将 Hermes 原生技能作为能力运行，不替换或隐藏底层编码执行器
- 一键安装：支持 macOS/Linux（curl 脚本）与 Windows（PowerShell）快速部署

**技术亮点**: 采用"操作层"架构设计，位于 Hermes 原生技能之上，负责问题框定、工作流与证据门控选择；Hermes 仍作为自然语言交互界面，OMH 作为受控执行路径存在，Python 实现，并提供多语言文档（英/韩/日/中）与 GitHub Pages 站点。

---
## 9. [localsend/localsend](https://github.com/localsend/localsend)
- **语言**: Dart
- **Stars**: 91,350
- **简介**: An open-source cross-platform alternative to AirDrop

### AI 总结
**简介**: LocalSend 是一款免费开源的跨平台文件与消息传输工具，是 AirDrop 的替代方案，无需联网即可在局域网内安全分享文件。

**核心功能**:
- 在同一局域网内的附近设备之间安全传输文件和消息，无需互联网连接
- 不依赖外部服务器或第三方中转，通信直接发生在设备之间
- 支持 Windows、macOS、Linux、Android、iOS、Fire OS 等多平台，并提供多种安装渠道（应用商店、包管理器、安装包等）
- 提供命令行界面（CLI），支持脚本化与自动化使用

**技术亮点**: 基于 Dart 开发，采用 REST API 与 HTTPS 加密实现设备间通信；无需中心服务器，架构去中心化，传输快速且可靠。

---
## 10. [dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden)
- **语言**: Rust
- **Stars**: 67,535
- **简介**: Unofficial Bitwarden compatible server written in Rust, formerly known as bitwarden_rs

### AI 总结
**简介**: Vaultwarden 是一个用 Rust 编写的非官方 Bitwarden 兼容服务器，适合资源有限的自托管场景，可完美替代官方重量级服务。

**核心功能**:
- 个人密码库（Personal Vault）管理
- Send 安全分享功能
- 附件（Attachments）支持
- 网站图标（Website Icons）自动获取
- 个人 API Key 支持
- 组织（Organizations）功能，包含集合、密码共享与成员角色管理

**技术亮点**: 基于 Rust 构建，兼容官方 Bitwarden 客户端（移动端、桌面端、浏览器扩展等），提供 Docker 镜像（Docker Hub、ghcr.io、Quay.io），采用 AGPL-3.0 许可证，社区活跃（Matrix、GitHub Discussions、Discourse 多渠道支持）。

---
