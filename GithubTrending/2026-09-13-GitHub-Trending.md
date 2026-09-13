---
tags:
  - github-trending
  - daily
date: 2026-09-13
created: 2026-09-13T01:55:43.261Z
---

# 2026-09-13 GitHub Trending Top 10

## 1. [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view)
- **语言**: JavaScript
- **Stars**: 29,986
- **简介**: A spy satellite simulator in your browser, except the data is real. Live open source spatial intelligence on a photorealistic 3D globe.

### AI 总结
**简介**: 一个运行在浏览器中的开源间谍卫星模拟器，基于真实公开数据源，在逼真的 3D 地球上提供实时空间情报可视化。

**核心功能**:
- **实况追踪**：实时显示飞机、船舶、卫星、地震、交通流量及公共摄像头画面
- **座舱视角**：进入被追踪航班的驾驶舱，相机全程跟随地形飞行
- **点击追踪**：点击任意目标即可锁定并显示完整元数据、轨迹尾迹，并可一键跳转至最近实况摄像头
- **语音控制**：通过实时 AI 代理实现免提语音操控，支持语音白板标注
- **3D 机库**：按机型显示真实 3D 飞机模型（787、ATR-72、MQ-9 等），靠近时自动从图标切换为模型
- **传感器滤镜**：GLSL 着色器模拟 CRT、夜视、FLIR 热成像、黑白、雪地等视觉效果
- **军事 HUD**：战术平视显示器，呈现情报风格的遥测数据
- **分享链接**：相机位置、样式、图层及追踪目标均可序列化为 URL 分享

**技术亮点**:
- 纯 JavaScript 实现，完全在浏览器本地运行，代码可审查可扩展
- 每个数据图层为独立模块，方便添加自定义数据源
- 集成真实公开数据源（航班应答机、船舶信标、轨道根数、地震仪、公共摄像头）
- 支持无 API 密钥启动，可通过 Pinokio 或终端本地运行
- 交通数据基于真实道路聚合位置数据模拟，CCTV 姿态和火箭发射轨迹为粗略估算
- 曾在 GitHub Trending 日榜和周榜排名第一

---
## 2. [melgarafael/DeskcommCRM](https://github.com/melgarafael/DeskcommCRM)
- **语言**: TypeScript
- **Stars**: 1,821
- **简介**: Open-source AI sales OS — self-hosted CRM with native AI agents + WhatsApp (WAHA). Open alternative to Kommo, Octadesk & Intercom for any business that sells by chat. MCP-ready, multi-tenant, LGPD.

### AI 总结
**简介**: DeskcommCRM 是一款开源、可自托管的 AI 销售操作系统，为通过聊天成交的企业提供原生 AI 智能体与 WhatsApp（WAHA）集成的 CRM，是 Kommo、Octadesk 和 Intercom 的开源替代方案。

**核心功能**:
- 原生 AI 智能体，可在 WhatsApp 中自动接待、筛选和促成销售
- 集成 WhatsApp（WAHA），支持通过 QR 码连接自有号码
- 多租户架构与 MCP-ready，支持 LGPD 合规
- 提供一键式 VPS 安装脚本（与 HostGator 合作），无需手动安装 Node、pnpm 或编译

**技术亮点**:
- 基于 Next.js 16 + TypeScript（严格模式）构建
- 使用 Supabase（Postgres + Auth + Storage）作为数据层
- 自托管部署，单命令安装（app + WhatsApp + 数据库），支持 Docker
- 采用 MIT 开源许可证，数据完全由用户掌控

---
## 3. [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)
- **语言**: JavaScript
- **Stars**: 65,436
- **简介**: Extracted system prompts from Anthropic - Claude Fable 5.1, Opus 5, Claude Design, Claude Code. OpenAI - ChatGPT GPT-6-Astra, Codex. Google - Gemini 3.8 Flash, 3.1 Pro, Antigravity. xAI - Grok, Grok Bot, Cursor, Kimi and more! Updated regularly.

### AI 总结
**简介**: 一个持续更新的开源仓库，收集并逐字记录 Anthropic、OpenAI、Google、xAI 等主流 AI 产品的系统提示词（System Prompts）。

**核心功能**:
- 汇总各大厂商 AI 模型的系统提示词，覆盖 Claude（Fable 5.1、Opus 5、Design、Code、Cowork、Science）、ChatGPT（GPT-5.6/6-Astra）、Codex、Gemini（3.7/3.8 Flash、3.1 Pro）、Grok（4.5/4.6、Bot）、Perplexity、Kimi、Cursor、Meta Muse Code、OpenCode 等
- 按厂商和模型分类组织，提供直达各提示词文件的链接
- 维护"最新新增/变更"表格，标注日期与对应文件，便于追踪版本迭代
- 收录配套资源，如 Claude Design 的 53 个工具、22 项技能和 10 个起始组件

**技术亮点**: 以 JavaScript 为主要语言；内容被《华盛顿邮报》互动报道及 CEPS AI World 实时数据看板引用，社区接受 PR 贡献，更新频率较高。

---
## 4. [nab138/iloader](https://github.com/nab138/iloader)
- **语言**: TypeScript
- **Stars**: 3,091
- **简介**: User friendly sideloader

### AI 总结
**简介**: iloader 是一款基于 TypeScript 与 Tauri 构建的跨平台 iOS 侧载工具，帮助用户轻松安装 SideStore 等应用并导入配对文件。

**核心功能**:
- 一键安装 SideStore（或 LiveContainer + SideStore），自动导入证书并放置 rppairing 与 lockdown 配对文件
- 支持导入任意 IPA 文件
- 智能错误提示，帮助用户快速定位并解决常见问题
- 管理 StikDebug、SideStore、Protokolle 等应用中的配对文件
- 查看并吊销开发证书与应用 ID

**技术亮点**:
- 前端使用 TypeScript，桌面端基于 Tauri 框架（Rust + Web 技术栈）
- 依赖 idevice 与 isideload 实现与 iOS 设备的通信及应用安装
- 支持多平台（Windows / macOS / Linux / NixOS），并提供 Homebrew、AUR、Fedora COPR 等社区维护的安装渠道
- 内置国际化（i18next）支持，方便社区贡献多语言翻译

---
## 5. [Flowseal/zapret-discord-youtube](https://github.com/Flowseal/zapret-discord-youtube)
- **语言**: Batchfile
- **Stars**: 33,211
- **简介**: 

### AI 总结
**简介**: 基于 zapret 的 Windows 批处理工具，用于绕过 DPI 封锁，恢复 Discord 和 YouTube 的访问。

**核心功能**:
- 提供多种 DPI 绕过策略（general、ALT、FAKE 等），可手动测试并选择可用方案
- 通过 `service.bat` 将策略安装为 Windows 服务实现开机自启，支持状态检查与卸载
- 支持 Game Filter 模式，扩展绕过范围至使用 UDP/TCP 高端口的游戏等服务
- 支持 IPSet Filter 模式，按 `ipset-all.txt` 列表控制绕过目标
- 附带安全 DNS 配置指引（Chrome、Firefox、Windows 11、Keenetic 路由器）

**技术亮点**:
- 基于 WinDivert 进行流量拦截与过滤，二进制文件来自官方 zapret-win-bundle 并提供哈希校验
- 纯 Batchfile 实现，无需额外运行时，开箱即用
- 明确提示杀软误报风险（WinDivert 常被标记为 RiskTool），并给出排除配置建议

---
## 6. [jihe520/MathModelAgent](https://github.com/jihe520/MathModelAgent)
- **语言**: Python
- **Stars**: 5,138
- **简介**: 🤖📐专为数学建模设计的 Agent & skills ,自动完成数学建模，生成一份完整的可以直接提交的论文。 An Agent Designed for Mathematical Modeling ,Automatically complete mathmodel and generate a complete paper ready for submission.

### AI 总结
**简介**: MathModelAgent 是一个专为数学建模竞赛设计的自动化 Agent，能从问题分析、建模、编码到论文排版全流程自动完成，生成可直接提交的论文。

**核心功能**:
- 端到端自动化：一条 `/1start-mathmodel` 命令完成分析、建模、编码、绘图、论文排版与验收
- 多 Agent 协作：建模手、代码手、论文手分工，每个 Agent 可配置不同模型
- 代码解释器：支持本地 Jupyter（保存为 notebook）及云端 E2B / Daytona
- 17 套 Typst 论文模板：覆盖国赛、华数杯、华为杯、MCM/ICM 等中英文赛事，自动匹配并生成 PDF
- 内置建模知识库：含建模规范、模型选择决策树（AHP、TOPSIS、ARIMA、GA 等）与评分标准
- 9 步自动验收：文本泄漏检测、数值一致性校验、Typst 编译、PDF 可视化检查
- 桌面版开箱即用：内置 Claude Code 与全套 SKILLS，无需配置 Python/Node.js/Redis

**技术亮点**:
- 基于 SKILLS 驱动架构，不再自建 Harness 层，可运行于 Claude Code / Codex 等 Harness
- 通过 litellm 支持所有主流模型，workflow agentless 设计降低成本
- 支持 RAG 知识库（ChromaDB + Rerank）、Web Search（Tavily/OpenAlex）、HIL 人机协作与四层容错机制
- 采用 Typst 排版生态，每个阶段为独立 Skill，可组合、可单独调用、可扩展
- 姊妹项目 sci-box 提供科研图表与 draw.io 流程图模板

---
## 7. [Sonarr/Sonarr](https://github.com/Sonarr/Sonarr)
- **语言**: C#
- **Stars**: 15,932
- **简介**: Smart PVR for newsgroup and bittorrent users.

### AI 总结
**简介**: Sonarr 是一款面向 Usenet 和 BitTorrent 用户的智能 PVR（个人视频录像机）工具，使用 C# 开发，可自动监控、下载、整理和升级剧集资源。

**核心功能**:
- 监控多个 RSS 源，自动检测并抓取喜爱剧集的最新集数
- 自动整理和重命名下载的剧集文件，支持完全自定义命名规则
- 扫描现有媒体库，自动补全缺失的剧集
- 在出现更高质量格式时自动升级已下载文件（如从 DVD 升级到 Blu-Ray）
- 下载失败自动重试其他发布源
- 支持手动搜索，可查看未自动下载的原因
- 完整集成 SABnzbd、NZBGet 下载客户端
- 与 Kodi、Plex 集成，支持通知、媒体库更新和元数据管理
- 支持特别篇和多集合并发布的剧集

**技术亮点**:
- 基于 C# 开发，跨平台支持 Windows、Linux、macOS、Raspberry Pi 等主流平台
- 采用 GNU GPL v3 开源协议
- 提供 v4 Beta API 文档，便于第三方集成和扩展
- 拥有完善的社区支持体系（论坛、Discord、IRC、Reddit、Wiki）

---
## 8. [alsk1992/CloddsBot](https://github.com/alsk1992/CloddsBot)
- **语言**: TypeScript
- **Stars**: 2,519
- **简介**: Open Source AI trading agent that operates autonomously across 1000+ markets - Polymarket, Kalshi, Binance, Hyperliquid, Solana DEXs, 5 EVM chains. Scans for edge, executes instantly, manages risk while you sleep. Agent commerce protocol for machine-to-machine payments. Self-hosted. Built on Claude.

### AI 总结
**简介**: CloddsBot 是一个基于 Claude 构建的开源自主 AI 交易代理，可在 1000+ 市场（预测市场、加密货币现货、永续合约、代币发行、Bittensor 挖矿）中自动扫描套利机会、即时执行交易并管理风险。

**核心功能**:
- 覆盖 10 个预测市场（Polymarket、Kalshi 等）和 7 个期货交易所（Binance、Hyperliquid 等），支持 Solana 生态（Jupiter、Pump.fun、Raydium、Orca）及 5 条 EVM 链
- 内置 118+ 交易策略，支持巨鲸追踪、套利检测、跟单交易和 DCA 机器人
- 通过 21 个消息平台进行自然语言对话式交易，并提供内置 WebChat 浏览器界面
- 支持代币发行、Bittensor 子网 TAO 挖矿及投资组合管理
- 自托管部署，提供机器对机器支付的 Agent 商业协议

**技术亮点**: 基于 TypeScript 5.3 开发，要求 Node.js 22+；由 Claude 驱动；采用追加式数据库存储实现无限聊天历史；通过 `clodds onboard` 向导快速完成配置，WebChat 默认运行于 `localhost:18789`。

---
## 9. [yuliskov/SmartTube](https://github.com/yuliskov/SmartTube)
- **语言**: Java
- **Stars**: 33,224
- **简介**: Browse media content with your own rules on Android TV

### AI 总结
**简介**: SmartTube 是一款面向 Android TV 和电视盒子的免费开源媒体客户端，让用户以自己的规则浏览和播放来自各种公开来源的内容。

**核心功能**:
- 支持 SponsorBlock 集成、可调节播放速度、8K 分辨率、60fps 播放和 HDR
- 提供直播聊天查看、可自定义按钮，且无需 Google 服务即可运行
- 拥有简洁的 TV 优化界面和活跃的国际社区

**技术亮点**:
- 基于 Java 开发，采用 TV 优化界面设计
- 不依赖 Google Services，兼容 Android 4.3（KitKat）及以上设备
- 使用一次性连接码机制，权限受限，保障用户账户安全

---
## 10. [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)
- **语言**: Python
- **Stars**: 137,643
- **简介**: 100+ AI Agents, Agent Skills and RAG Apps - Free and Open Source.

### AI 总结
**简介**: 一个包含 100+ 开源 AI Agent、Agent Skills 与 RAG 应用的项目，全部手工构建、端到端测试，采用 Apache-2.0 许可，支持 Claude、Gemini、GPT、DeepSeek、Llama、Qwen 等模型。

**核心功能**:
- **Agent Skills**：通过一条命令为编码代理安装新技能（如 Project Graveyard、First Reader、Scope Creep Detector、Commit Archaeologist），兼容 Claude Code、Codex、Cursor 等
- **丰富的应用模板**：涵盖语音 AI 代理（如保险理赔实时团队）、多代理应用（如 AI 房屋改造、AI 欺诈调查）、常驻代理（如 HN 简报）等
- **快速上手**：支持 10 秒安装技能或 30 秒克隆运行任意代理（如 Streamlit 启动旅行代理）
- **持续更新**：每周发布新模板，并提供 Unwind AI 上的分步教程

**技术亮点**: 基于 Python 构建，集成 Streamlit 等框架，支持多种主流及开源大模型，提供端到端可运行代码与安全/评估 CI 门槛。

---
