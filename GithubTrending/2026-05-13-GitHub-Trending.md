---
tags:
  - github-trending
  - daily
date: 2026-05-13
created: 2026-05-13T01:55:44.794Z
---

# 2026-05-13 GitHub Trending Top 10

## 1. [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman)
- **语言**: Rust
- **Stars**: 2,807
- **简介**: Your Personal AI super intelligence. Private, Simple and extremely powerful.

### AI 总结
**简介**: OpenHuman 是一款开源的个人 AI 超级智能助手，注重隐私、简洁和强大性能，旨在深度融入用户的日常生活。

**核心功能**:
- **桌面端 UI 优先**: 提供简洁的桌面体验和快速启动流程，无需终端即可运行；拥有可说话的桌面吉祥物，能加入 Google Meet 作为真实参与者，并保持后台持续思考。
- **118+ 第三方集成**: 通过一键 OAuth 连接 Gmail、Notion、GitHub、Slack 等工具，自动每 20 分钟拉取最新数据到记忆树，无需手动轮询。
- **记忆树 + Obsidian Wiki**: 本地优先的知识库，将连接的数据转化为 Markdown 片段并构建分层摘要树，存储在本地 SQLite 中，并支持在 Obsidian 中浏览编辑。
- **内置工具集**: 包含网页搜索、网页抓取、完整的编码工具（文件系统、Git、lint、测试、grep）以及原生语音功能（语音输入、ElevenLabs 语音输出、吉祥物唇形同步）。
- **智能 Token 压缩 (TokenJuice)**: 所有工具调用和输入数据在进入大模型前都经过压缩层处理（如 HTML 转 Markdown、URL 缩短），大幅减少 token 消耗。

**技术亮点**: 使用 Rust 开发；采用模型路由将不同任务分配给最合适的 LLM；支持通过 Ollama 运行本地 AI 模型。

---
## 2. [rohitg00/agentmemory](https://github.com/rohitg00/agentmemory)
- **语言**: TypeScript
- **Stars**: 5,938
- **简介**: #1 Persistent memory for AI coding agents based on real-world benchmarks

### AI 总结
**简介**: agentmemory 是一个为 AI 编程代理提供持久化记忆的 TypeScript 库，基于真实世界基准测试，让代理不再需要重复解释上下文。

**核心功能**:
- 为 Claude Code、Cursor、Gemini CLI 等主流 AI 编程代理提供持久化记忆
- 支持通过 hooks、MCP 或 REST API 与任意代理集成，所有代理共享同一内存服务器
- 提供 51 个 MCP 工具、12 个自动 hooks，以及实时内存查看器
- 内置置信度评分、生命周期管理、知识图谱和混合搜索

**技术亮点**:
- 基于 iii 引擎构建，零外部数据库依赖
- 实现 95.2% 的检索召回率 (R@5)，减少 92% 的 token 消耗
- 拥有 827 个通过的测试，稳定性强

---
## 3. [CloakHQ/CloakBrowser](https://github.com/CloakHQ/CloakBrowser)
- **语言**: Python
- **Stars**: 7,951
- **简介**: Stealth Chromium that passes every bot detection test. Drop-in Playwright replacement with source-level fingerprint patches. 30/30 tests passed.

### AI 总结
**简介**: 一个基于 Chromium 源码级修改的隐身浏览器，能通过所有机器人检测测试，可作为 Playwright/Puppeteer 的即插即用替代品。

**核心功能**:
- **源码级修改**：通过 49 个 C++ 补丁修改浏览器指纹，包括 Canvas、WebGL、音频、字体、GPU、屏幕、WebRTC 等
- **人类行为模拟**：`humanize=True` 参数可模拟人类鼠标曲线、键盘输入节奏和滚动模式
- **高 reCAPTCHA 分数**：服务器验证的 reCAPTCHA v3 分数达 0.9
- **自动更新二进制文件**：后台自动检查更新，始终使用最新的隐身构建
- **零配置安装**：`pip install cloakbrowser` 或 `npm install cloakbrowser`，自动下载二进制文件
- **浏览器配置管理器**：提供自托管的多登录/GoLogin/AdsPower 替代方案，支持浏览器配置、代理和持久会话

**技术亮点**:
- 基于 Python/JavaScript，支持 Playwright 和 Puppeteer 的无缝迁移（仅需修改导入语句）
- 通过 Cloudflare Turnstile、FingerprintJS、BrowserScan 等 30+ 检测网站测试
- 提供 Docker 容器化部署（`docker run --rm cloakhq/cloakbrowser cloaktest`）
- 支持可选的地理位置自动检测（`cloakbrowser[geoip]`）

---
## 4. [apernet/hysteria](https://github.com/apernet/hysteria)
- **语言**: Go
- **Stars**: 20,252
- **简介**: Hysteria is a powerful, lightning fast and censorship resistant proxy.

### AI 总结
**简介**: Hysteria 是一个基于定制 QUIC 协议、具备强大抗审查能力且速度极快的网络代理工具。

**核心功能**:
- 支持 SOCKS5、HTTP 代理、TCP/UDP 转发、Linux TProxy 和 TUN 等多种代理模式
- 伪装成标准 HTTP/3 流量，有效抵抗网络审查与封锁
- 内置自定义认证、流量统计和访问控制功能，便于集成

**技术亮点**: 基于 Go 语言开发，使用定制化的 QUIC 协议在不可靠和高丢包网络环境下实现卓越性能；提供跨平台支持（覆盖主流操作系统和架构），并有完善的第三方应用生态。

---
## 5. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 76,227
- **简介**: Skills for Real Engineers. Straight from my .claude directory.

### AI 总结
**简介**: 这是一套面向专业工程师的 AI 代理技能集，旨在解决常见开发问题，提升与 AI 编码代理的协作效率。

**核心功能**:
- **`/grill-me`**: 在编码前通过详细提问帮助用户与 AI 对齐需求，减少误解。
- **`/grill-with-docs`**: 在`/grill-me`基础上增加建立共享语言和文档化决策（ADR）的功能，降低 AI 冗余输出，提升代码一致性。
- **快速安装与配置**: 通过`npx skills@latest add`一键安装，并自动引导用户设置问题追踪器、标签和文档存储位置。

**技术亮点**: 基于 Shell 脚本，强调技能的小型化、易适配和可组合性，与主流编码代理（如 Claude Code、Codex）兼容。

---
## 6. [anonfaded/FadCam](https://github.com/anonfaded/FadCam)
- **语言**: Java
- **Stars**: 2,226
- **简介**: Open-source, ad-free Android multimedia recorder with background video recording, screen recording, live streaming, and remote camera control

### AI 总结
**简介**: FadCam 是一款开源、无广告的 Android 多媒体录制套件，专注于隐私保护，支持后台视频录制、行车记录仪、屏幕录制、直播和远程摄像头控制。

**核心功能**:
- **后台视频录制**：在应用后台或手机锁屏状态下持续录制视频。
- **行车记录仪**：提供类似行车记录仪的循环录制和自动启动功能。
- **屏幕录制**：支持录制设备屏幕内容。
- **直播推流**：支持将摄像头画面实时推流到直播平台。
- **远程摄像头控制**：可通过其他设备远程控制摄像头录制。
- **多种安装渠道**：提供 F-Droid、IzzyOnDroid、Amazon Appstore 等无广告来源。

**技术亮点**:
- **Java 语言开发**：基于 Android 原生框架，确保性能和兼容性。
- **隐私优先**：项目隶属于 FadSec Lab 套件，强调无广告、无跟踪的隐私保护理念。
- **开源社区驱动**：支持通过 Patreon 获取 Pro 版，并提供 Discord 社区进行协作。

---
## 7. [millionco/react-doctor](https://github.com/millionco/react-doctor)
- **语言**: TypeScript
- **Stars**: 8,789
- **简介**: Your agent writes bad React. This catches it

### AI 总结
**简介**: 一个用于检测和修复 React 代码中常见问题的工具，帮助开发者避免写出糟糕的 React 代码。

**核心功能**:
- 自动检测 React 组件中的不良实践和反模式
- 提供代码修复建议和自动化重构能力
- 支持 TypeScript 类型安全的代码检查

**技术亮点**: 基于 TypeScript 构建，提供类型安全的静态分析能力，通过 AST 解析实现精准的代码模式识别

---
## 8. [rasbt/LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch)
- **语言**: Jupyter Notebook
- **Stars**: 93,831
- **简介**: Implement a ChatGPT-like LLM in PyTorch from scratch, step by step

### AI 总结
**简介**: 该仓库是《Build a Large Language Model (From Scratch)》一书的官方代码库，指导开发者从零开始用PyTorch逐步构建、预训练和微调一个类似ChatGPT的GPT风格大语言模型。

**核心功能**:
- 从零实现GPT-like LLM：涵盖从文本数据处理、注意力机制编码到模型训练的完整流程。
- 支持模型微调：提供代码加载预训练大模型权重，并针对下游任务进行微调。
- 配套书籍代码：按章节组织，提供Jupyter Notebook示例和练习解答，便于学习。

**技术亮点**:
- 使用PyTorch框架，代码清晰模块化，适合教学和自学。
- 包含跨平台（Linux/Windows/macOS）自动化测试，确保代码稳定性。
- 提供环境搭建指南和故障排除文档，降低入门门槛。

---
## 9. [datawhalechina/hello-agents](https://github.com/datawhalechina/hello-agents)
- **语言**: Python
- **Stars**: 48,298
- **简介**: 📚 《从零开始构建智能体》——从零开始的智能体原理与实践教程

### AI 总结
**简介**: 这是一本从零开始、理论与实战并重的智能体系统构建指南，旨在帮助开发者深入理解并亲手构建AI原生智能体。

**核心功能**:
- 系统讲解智能体核心原理、经典范式（如ReAct、Plan-and-Solve）与发展历史
- 手把手实现从零构建自己的智能体框架（HelloAgents）
- 覆盖低代码平台（Coze、Dify、n8n）与主流框架（AutoGen、LangGraph）的使用
- 深入高级技术：记忆与检索、上下文工程、智能体通信协议（MCP/A2A/ANP）
- 包含Agentic RL训练实战（从SFT到GRPO）
- 提供智能体性能评估与综合案例（智能旅行助手、赛博小镇等）

**技术亮点**: 基于OpenAI原生API自研框架；涵盖LLM基础、Agentic RL训练、多智能体通信协议；提供在线免费阅读与本地部署支持。

---
## 10. [yikart/AiToEarn](https://github.com/yikart/AiToEarn)
- **语言**: TypeScript
- **Stars**: 11,928
- **简介**: Let's use AI to Earn!

### AI 总结
**简介**: AiToEarn 是一个面向 OPC（一人公司）及创作者的 AI 内容营销智能体平台，旨在通过 AI 自动化帮助用户在全球主流社交平台上构建、分发并变现内容。

**核心功能**:
- **💰 内容赚钱 (Monetize)**: 提供 CPS、CPE、CPM 三种结算模式，帮助创作者通过完成商家推广任务来变现内容。
- **📢 内容发布 (Publish)**: 支持一键将内容分发至抖音、TikTok、YouTube、小红书等 10+ 主流平台，并提供日历排期功能。
- **💬 内容互动 (Engage)**: 通过浏览器插件实现自动点赞、收藏、关注，并利用 AI 进行智能回复、评论挖掘和品牌监测。
- **🎨 内容创作 (Create)**: 通过 Agent 自动化完成视频和图文内容的生成、翻译与剪辑，支持批量生产。

**技术亮点**: 基于 TypeScript 开发，提供网站、Docker 部署、MCP 协议（支持 Claude/Cursor 等 AI 助手）及源码开发等多种使用方式，并支持浏览器插件扩展。

---
