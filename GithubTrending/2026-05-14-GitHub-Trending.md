---
tags:
  - github-trending
  - daily
date: 2026-05-14
created: 2026-05-14T01:55:44.799Z
---

# 2026-05-14 GitHub Trending Top 10

## 1. [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman)
- **语言**: Rust
- **Stars**: 5,650
- **简介**: Your Personal AI super intelligence. Private, Simple and extremely powerful.

### AI 总结
**简介**: OpenHuman 是一款开源的个人 AI 超级智能助手，注重隐私、简洁性和强大性能，旨在无缝融入用户的日常生活。

**核心功能**:
- **简洁 UI 与人类化交互**: 提供桌面端体验，通过简单的引导流程即可快速上手，无需终端或复杂配置；内置桌面吉祥物，能说话、对环境做出反应、加入 Google Meet 并长期记忆用户行为。
- **118+ 第三方集成与自动获取**: 支持 Gmail、Notion、GitHub、Slack 等主流服务的 OAuth 一键连接，每 20 分钟自动拉取最新数据并存入记忆树，无需手动轮询。
- **记忆树与 Obsidian 知识库**: 将连接的数据转化为 ≤3k token 的 Markdown 块，构建本地优先的层级摘要树（存储于 SQLite），同时生成兼容 Obsidian 的 .md 文件，支持浏览和编辑。
- **内置工具集**: 包含网络搜索、网页抓取、完整编码工具（文件系统、Git、lint、测试、grep）以及原生语音功能（语音转文字、ElevenLabs 语音合成、吉祥物唇形同步、Google Meet 实时交互）。
- **智能 Token 压缩 (TokenJuice)**: 在工具调用、抓取结果、邮件正文等所有内容进入 LLM 前，自动进行压缩（如 HTML 转 Markdown、缩短 URL、移除非 ASCII 字符），节省 token 消耗。

**技术亮点**: 使用 Rust 语言开发，采用本地优先架构（SQLite 存储记忆树）；支持模型路由，自动为不同任务分配推理、快速或视觉 LLM，并可选集成 Ollama 实现本地 AI 处理。

---
## 2. [rohitg00/agentmemory](https://github.com/rohitg00/agentmemory)
- **语言**: TypeScript
- **Stars**: 7,735
- **简介**: #1 Persistent memory for AI coding agents based on real-world benchmarks

### AI 总结
**简介**: agentmemory 是一个为 AI 编程代理提供持久化记忆的 TypeScript 库，基于真实世界基准测试构建，确保代理无需重复解释上下文。

**核心功能**:
- **持久化记忆存储**: 为 Claude Code、Cursor、Gemini CLI 等主流 AI 代理提供持久化记忆，支持 hooks、MCP 或 REST API 集成。
- **混合搜索与知识图谱**: 扩展了 Karpathy 的 LLM Wiki 模式，集成置信度评分、生命周期管理、知识图谱和混合搜索。
- **零外部依赖**: 无需外部数据库，内置 51 个 MCP 工具、12 个自动 hooks，并附带实时查看器。
- **高性能基准**: 检索 R@5 召回率达 95.2%，Token 消耗减少 92%，拥有 827 个测试用例。

**技术亮点**: 基于 iii 引擎构建，提供 MCP 服务器支持，跨代理共享同一记忆服务器，并包含实时查看器与 iii 控制台。

---
## 3. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 189,605
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套为编码代理设计的完整软件开发方法论，基于可组合的技能和初始指令，确保代理遵循规范流程。

**核心功能**:
- **需求澄清与设计**: 在编码前自动引导用户明确需求，生成可审查的设计文档。
- **计划生成**: 将设计分解为小型任务（2-5分钟），每个任务包含文件路径、完整代码和验证步骤。
- **子代理驱动开发**: 使用独立代理按计划执行任务，自动审查工作并持续迭代，支持长时间自主运行。
- **多平台支持**: 兼容 Claude Code、Codex CLI、Cursor 等主流编码代理工具。

**技术亮点**: 基于 Shell 脚本实现，强调 TDD、YAGNI 和 DRY 原则；通过可组合技能和子代理架构提升开发效率。

---
## 4. [yikart/AiToEarn](https://github.com/yikart/AiToEarn)
- **语言**: TypeScript
- **Stars**: 12,980
- **简介**: Let's use AI to Earn!

### AI 总结
**简介**: AiToEarn 是一个面向 OPC（一人公司）和创作者的 AI 内容营销智能体平台，通过 AI Agent 自动化帮助用户在多个主流社交平台实现内容变现、发布、互动与创作。

**核心功能**:
- **内容赚钱 (Monetize)**: 提供 CPS、CPE、CPM 三种结算模式，帮助创作者通过完成商家推广任务赚取收益。
- **内容发布 (Publish)**: 一键将内容分发至抖音、小红书、YouTube、TikTok 等 10+ 全球主流平台，并支持日历排期。
- **内容互动 (Engage)**: 通过浏览器插件实现自动点赞、收藏、关注，以及 AI 智能回复评论、挖掘高转化信号和品牌监测。
- **内容创作 (Create)**: 通过 Agent 自动调用视频/图片生成模型，完成视频制作、图文创作及批量生成任务。

**技术亮点**:
- 基于 TypeScript 开发，支持多种部署方式（网页直接使用、Docker 私有部署、源码开发）。
- 提供 API Key 及 MCP 协议支持，可集成到 Claude、Cursor 等 AI 助手中使用。
- 采用 AI Agent 自动化流程，整合多个生成模型（如 Grok、Veo、Nano Banana 等）实现一站式内容制作。

---
## 5. [influxdata/telegraf](https://github.com/influxdata/telegraf)
- **语言**: Go
- **Stars**: 17,017
- **简介**: Agent for collecting, processing, aggregating, and writing metrics, logs, and other arbitrary data.

### AI 总结
**简介**: Telegraf 是一个用 Go 编写的代理，用于收集、处理、聚合和写入指标、日志及其他任意数据。

**核心功能**:
- 提供超过 300 种插件，覆盖系统监控、云服务、消息传递等多种场景
- 支持用户自定义代码来高效收集、转换和传输数据
- 通过 TOML 配置文件实现用户友好的设置体验
- 可编译为无外部依赖的独立静态二进制文件，简化部署流程

**技术亮点**:
- 使用 Go 语言开发，编译为单一静态二进制文件，部署简单
- 采用插件化架构，输入、处理、输出各环节均可灵活组合
- 社区活跃，拥有超过 1200 名贡献者

---
## 6. [millionco/react-doctor](https://github.com/millionco/react-doctor)
- **语言**: TypeScript
- **Stars**: 9,302
- **简介**: Your agent writes bad React. This catches it

### AI 总结
**简介**: 一个用于检测和捕获 React 代码中不良实践的工具，帮助开发者提升代码质量。

**核心功能**:
- 自动检测 React 代码中的常见错误和反模式
- 提供清晰的错误提示和改进建议

**技术亮点**: 基于 TypeScript 开发，支持静态代码分析

---
## 7. [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- **语言**: Python
- **Stars**: 21,158
- **简介**: A set of ready to use Agent Skills for research, science, engineering, analysis, finance and writing.

### AI 总结
**简介**: 一个包含135个即用型科学与研究技能的AI代理工具包，支持生物学、化学、医学等多领域复杂工作流。

**核心功能**:
- 提供135个预定义科学技能，覆盖生物信息学、化学信息学、蛋白质组学、临床研究、医学影像等17个领域
- 支持AI代理执行多步骤科学工作流，如基因分析、分子对接、药物发现、时间序列预测等
- 集成100+科学数据库和专用Python库（如单细胞RNA-seq、分子动力学、地理空间分析等）
- 兼容Cursor、Claude Code、Codex等主流AI代理，遵循开放Agent Skills标准

**技术亮点**: 基于Python构建，采用Agent Skills开放标准实现跨平台兼容；通过预定义技能文档和示例代码增强AI代理的科学计算能力；支持与K-Dense BYOK桌面端开源AI协同科学家工具集成。

---
## 8. [danielmiessler/Personal_AI_Infrastructure](https://github.com/danielmiessler/Personal_AI_Infrastructure)
- **语言**: TypeScript
- **Stars**: 13,394
- **简介**: Agentic AI Infrastructure for magnifying HUMAN capabilities.

### AI 总结
**简介**: Personal AI Infrastructure (PAI) 是一个旨在增强人类能力的智能体 AI 基础设施，作为一个“生活操作系统”，帮助用户捕捉当前状态并驱动向理想状态演进。

**核心功能**:
- 提供统一的 Pulse 守护进程，在 `localhost:31337` 提供生活仪表盘
- 通过 DA（数字助理）身份层进行个性化交互
- 包含 Algorithm v6.3.0，支持从当前状态到理想状态的七阶段演进，具备分类器驱动模式
- 使用 ISA 原语实现通用的“理想状态”表述
- 提供 45 项技能、171 个工作流和 37 个钩子，支持结构隐私隔离

**技术亮点**: 基于 TypeScript 开发，使用 Bun 运行时，集成 Claude AI，支持一键安装（`curl -sSL https://ourpai.ai/install.sh | bash`）。

---
## 9. [supertone-inc/supertonic](https://github.com/supertone-inc/supertonic)
- **语言**: Swift
- **Stars**: 4,395
- **简介**: Lightning-Fast, On-Device, Multilingual TTS — running natively via ONNX.

### AI 总结
**简介**: Supertonic 是一个基于 ONNX Runtime 的本地多语言文本转语音（TTS）系统，支持离线推理、低延迟且保护隐私。

**核心功能**:
- **多语言支持**: Supertonic 3 版本支持 31 种语言，v2 版本支持 5 种语言
- **边缘端部署**: 通过 Voice Builder 可将用户声音转换为可部署的、拥有永久所有权的 TTS 模型
- **多平台 SDK**: 提供 Python、Swift、Node.js、Java、C++、C#、Go、Rust 等多种语言和平台的 SDK 示例
- **多种声音风格**: 提供 M1-M5、F1-F5 等预置声音风格，可灵活切换

**技术亮点**:
- **本地推理**: 基于 ONNX Runtime，完全在设备端运行，无需网络或 API 调用
- **高性能**: 优化后的 ONNX 模型（通过 OnnxSlim）实现闪电般快速推理
- **自动模型管理**: 首次运行时自动从 Hugging Face 下载模型资产

---
## 10. [CloakHQ/CloakBrowser](https://github.com/CloakHQ/CloakBrowser)
- **语言**: Python
- **Stars**: 9,565
- **简介**: Stealth Chromium that passes every bot detection test. Drop-in Playwright replacement with source-level fingerprint patches. 30/30 tests passed.

### AI 总结
**简介**: CloakBrowser 是一款基于 Chromium 源码级修改的隐身浏览器，能通过所有机器人检测测试，可作为 Playwright/Puppeteer 的即插即用替代品。

**核心功能**:
- 通过 49 个 C++ 源码级补丁修改指纹（Canvas、WebGL、音频、字体、GPU、屏幕、WebRTC、网络时序等），绕过反机器人系统
- 支持 `humanize=True` 参数，模拟人类鼠标曲线、键盘输入和滚动模式，通过行为检测
- 获得 0.9 的 reCAPTCHA v3 评分，通过 Cloudflare Turnstile、FingerprintJS 等 30+ 检测站点
- 提供 Python 和 JavaScript 两种语言的 API，与 Playwright/Puppeteer 兼容，只需替换导入语句
- 自动下载和更新隐身 Chromium 二进制文件，零配置
- 内置浏览器配置文件管理器，支持创建独立指纹、代理和持久会话（Docker 部署）

**技术亮点**: 基于 Chromium 源码级 C++ 补丁修改浏览器指纹，而非 JS 注入或配置补丁；支持 Docker 一键运行测试；免费开源，无订阅限制。

---
