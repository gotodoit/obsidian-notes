---
tags:
  - github-trending
  - daily
date: 2026-07-23
created: 2026-07-23T01:55:43.682Z
---

# 2026-07-23 GitHub Trending Top 10

## 1. [koala73/worldmonitor](https://github.com/koala73/worldmonitor)
- **语言**: TypeScript
- **Stars**: 69,091
- **简介**: Real-time global intelligence dashboard. AI-powered news aggregation, geopolitical monitoring, and infrastructure tracking in a unified situational awareness interface

### AI 总结
**简介**: World Monitor 是一个基于 AI 的实时全球情报仪表盘，整合新闻聚合、地缘政治监控和基础设施追踪，提供统一态势感知界面。

**核心功能**:
- **AI 驱动的新闻聚合**: 自动收集并分析全球新闻，提供实时情报更新。
- **地缘政治监控**: 追踪国际政治动态与事件，支持多维度态势感知。
- **基础设施追踪**: 监控关键基础设施状态，覆盖能源、金融、商品等领域。
- **多平台变体支持**: 提供 Tech、Finance、Commodity、Happy、Energy 等专用监控面板。
- **跨语言与多SDK**: 支持中文文档，提供 npm、pip、gem、go 等多语言 SDK 及 CLI 工具。

**技术亮点**: 采用 TypeScript 构建，提供 Web 应用、桌面客户端（Windows/macOS/Linux）及多语言 SDK 集成；基于 AGPL v3 开源协议。

---
## 2. [ruvnet/RuView](https://github.com/ruvnet/RuView)
- **语言**: Rust
- **Stars**: 83,873
- **简介**: π RuView turns commodity WiFi signals into real-time spatial intelligence, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: RuView 是一个基于 WiFi 信号的空间感知平台，无需摄像头或可穿戴设备即可实现穿墙人体检测、生命体征监测和活动识别。

**核心功能**:
- **穿墙人体感知**：检测人员存在、位置、进出房间及人数统计
- **生命体征监测**：无接触测量呼吸频率和心率，支持睡眠监测与窒息筛查
- **活动识别**：识别行走、坐姿、手势、跌倒等动作，以及多房间移动轨迹
- **环境映射**：通过射频指纹识别房间，检测家具移动和新物体
- **智能家居集成**：原生支持 Home Assistant、Apple Home、Google Home、Alexa 和 Matter 协议

**技术亮点**:
- 基于 ESP32 低成本硬件（节点低至 $9）和 RISC-V 边缘计算
- 使用信道状态信息（CSI）从 WiFi 信号中提取时空模式
- 尖峰神经网络实现本地学习，30秒内适应新环境
- 模型仅 8KB（4-bit 量化），在树莓派上微秒级运行
- 支持多频段 WiFi 扫描（6 信道），利用邻居路由器作为雷达发射器
- 通过 Ed25519 见证链实现加密认证

---
## 3. [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)
- **语言**: Python
- **Stars**: 8,335
- **简介**: A skill for your coding agent to stop it from burying the answer. ADHD-friendly output.

### AI 总结
**简介**: 一个让编程助手直接输出答案、避免冗长废话的技能插件，专为ADHD友好设计。

**核心功能**:
- 以行动优先，提供清晰、步骤化的指令
- 自动抑制无关话题和客套话（如“Hope this helps!”）
- 支持Claude Code和Codex等编程助手

**技术亮点**: 基于Python实现，通过插件机制集成到Claude Code和Codex中；提供10条规则（如编号步骤、限定列表不超过5项）确保输出简洁高效。

---
## 4. [schollz/croc](https://github.com/schollz/croc)
- **语言**: Go
- **Stars**: 37,638
- **简介**: Easily and securely send things from one computer to another 🐊 📦

### AI 总结
**简介**: `croc` 是一款跨平台命令行工具，允许任意两台计算机之间安全、简便地传输文件和文件夹，支持端到端加密和断点续传。

**核心功能**:
- 任意两台计算机通过中继服务器传输数据
- 端到端加密（基于 PAKE 协议）
- 跨平台支持（Windows、Linux、macOS、Android 等）
- 支持多文件/文件夹传输
- 断点续传
- 无需本地服务器或端口转发
- 支持 IPv6 优先（IPv4 回退）和代理（如 Tor）

**技术亮点**:
- 使用 Go 语言开发，轻量高效
- 基于 PAKE（密码认证密钥协商）实现安全加密
- 通过中继服务器实现穿透传输，无需复杂网络配置
- 提供丰富的包管理安装方式（Homebrew、Scoop、Chocolatey、Nix、Docker 等）

---
## 5. [likec4/likec4](https://github.com/likec4/likec4)
- **语言**: TypeScript
- **Stars**: 4,296
- **简介**: Visualize, collaborate, and evolve the software architecture with always actual and live diagrams from your code

### AI 总结
**简介**: LikeC4 是一个基于代码生成实时软件架构图的建模语言与工具，灵感来自 C4 模型和 Structurizr DSL。

**核心功能**:
- 通过代码定义架构模型，自动生成实时、可交互的架构图
- 支持自定义符号、元素类型和任意嵌套层级，灵活适配不同架构需求
- 提供 CLI 工具 (`npx likec4 start`) 预览和生成图表
- 集成 VS Code 扩展，支持在编辑器中直接编辑和预览架构图
- 提供在线 Playground 和模板仓库，便于快速上手和协作

**技术亮点**: 使用 TypeScript 开发，基于 C4 模型思想但提供更高灵活性；支持从代码到图表的实时同步，并可通过 NPM 包、VS Code 扩展和 Open VSX 部署使用。

---
## 6. [chrislgarry/Apollo-11](https://github.com/chrislgarry/Apollo-11)
- **语言**: Assembly
- **Stars**: 70,631
- **简介**: Original Apollo 11 Guidance Computer (AGC) source code for the command and lunar modules.

### AI 总结
**简介**: 阿波罗11号制导计算机（AGC）的原始源代码，包含指令舱（Comanche055）和登月舱（Luminary099）的程序，由Virtual AGC和MIT博物馆数字化。

**核心功能**:
- 提供阿波罗11号登月任务中指令舱与登月舱制导计算机的完整汇编源码
- 支持通过Virtual AGC工具编译原始代码
- 包含多语言翻译的README文档

**技术亮点**: 使用Assembly语言编写，包含Colossus 2A（指令舱）和Luminary 1A（登月舱）两套AGC程序，采用yaYUL汇编器，代码为公共领域开源。

---
## 7. [jamiepine/voicebox](https://github.com/jamiepine/voicebox)
- **语言**: TypeScript
- **Stars**: 45,800
- **简介**: The open-source AI voice studio. Clone, dictate, create.

### AI 总结
**简介**: Voicebox 是一个本地优先的开源 AI 语音工作室，可克隆声音、生成语音、支持全局听写，并让 AI 代理使用你拥有的声音与你对话，是 ElevenLabs 和 WisprFlow 的开源替代方案。

**核心功能**:
- **语音克隆与生成**: 从几秒音频进行零样本克隆，支持 7 种 TTS 引擎、23 种语言和 50+ 预设声音。
- **语音输入**: 全局快捷键听写，支持推挽式或切换模式，基于 Whisper 的语音转文字，并可在 macOS 上自动粘贴。
- **智能处理**: 内置后处理效果（音高、混响、延迟等），自动分块与交叉淡入淡出支持无限长度内容。
- **故事编辑器**: 多轨时间线，用于创作对话、播客和叙事内容。
- **AI 代理集成**: 通过 MCP 协议，只需一个工具调用 (`voicebox.speak`) 即可让 AI 代理使用你克隆的声音说话。
- **语音个性**: 为语音配置文件附加自由形式的角色设定，并通过内置本地 LLM 进行撰写、改写或回复。

**技术亮点**: 基于 Tauri (Rust) 构建，原生性能；完全本地运行，保护隐私；提供 REST API 和内置 MCP 服务器；支持 macOS (MLX/Metal)、Windows (CUDA)、Linux、AMD ROCm、Intel Arc 和 Docker。

---
## 8. [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)
- **语言**: TypeScript
- **Stars**: 25,380
- **简介**: Never stop coding. Free MIT AI gateway: one endpoint, 268+ providers (50+ free), 500+ models — Kimi, Claude, GPT, OpenAI, Gemini, GLM, DeepSeek, MiniMax. Works with Claude Code, Codex, Cursor, OpenCode, Cline & Copilot. Quota-aware auto-fallback, RTK+Caveman compression saves 15-95% tokens, MCP/A2A, Desktop/PWA. Built by 500+ contributors

### AI 总结
**简介**: OmniRoute 是一个免费、开源的 MIT AI 网关，通过单一端点连接 250+ 提供商（90+ 免费），提供 500+ 模型，并集成了智能路由、压缩和故障转移功能。

**核心功能**:
- **多提供商路由**: 支持 Claude、GPT、Gemini 等 250+ AI 提供商，包括 90+ 免费层。
- **智能自动故障转移**: 基于配额感知，自动在提供商之间切换，避免服务中断。
- **高效压缩**: 采用 RTK + Caveman 压缩技术，可节省 15-95% 的 Token 消耗。
- **广泛兼容性**: 与 Claude Code、Codex、Cursor、Cline、Copilot 等主流 CLI 和编码代理无缝集成。
- **多平台部署**: 支持 Docker、npm、Electron 桌面应用及 PWA，可在任何地方运行。
- **多语言支持**: 提供 42+ 种语言的国际化版本。

**技术亮点**: 使用 TypeScript 构建，提供 18 种路由策略，支持 MCP/A2A 协议，每月聚合约 1.6B 免费 Token，社区贡献者超过 500 人。

---
## 9. [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos)
- **语言**: Python
- **Stars**: 32,620
- **简介**: Kronos: A Foundation Model for the Language of Financial Markets

### AI 总结
**简介**: Kronos 是首个面向金融市场的开源基础模型，专门针对全球45+交易所的K线数据训练。

**核心功能**:
- 提供多种规模的预训练模型（mini/small/base/large），支持不同计算需求
- 支持金融K线序列预测，通过KronosPredictor类简化预测流程
- 提供在线Demo演示BTC/USDT交易对24小时预测结果

**技术亮点**: 采用两阶段框架设计，包含专用分词器（将OHLCV数据量化为分层离散令牌）和自回归Transformer模型，处理金融数据的高噪声特性。

---
## 10. [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)
- **语言**: Python
- **Stars**: 68,808
- **简介**: A curated list of awesome Claude Skills, resources, and tools for customizing Claude AI workflows

### AI 总结
**简介**: 一个精选的 Claude Skills 资源列表，包含 1000+ 个生产就绪的实用技能和插件，用于定制 Claude AI 工作流程并提升生产力。

**核心功能**:
- 提供 1000+ 个预构建的 Claude Skills，涵盖文档处理、开发工具、数据分析、业务营销、沟通写作、创意媒体、生产力组织、协作项目管理、安全系统及应用自动化等类别
- 通过 connect-apps 插件，让 Claude 能够执行真实操作，如发送邮件、创建 Issue、发布到 Slack，连接 500+ 应用
- 支持 Claude.ai、Claude Code、Claude API、OpenAI Codex、Cursor、Gemini CLI 等多种 AI 代理

**技术亮点**: 基于 Anthropic 开放的 Skills 标准（SKILL.md + YAML 前端 + 按需加载），结合 Composio 实现应用集成与认证，支持渐进式加载（会话开始时仅加载技能名称和描述，完整指令在需要时加载），确保单个代理可承载数百个技能而不膨胀上下文窗口。

---
