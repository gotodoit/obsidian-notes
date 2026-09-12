---
tags:
  - github-trending
  - daily
date: 2026-09-12
created: 2026-09-12T01:55:43.040Z
---

# 2026-09-12 GitHub Trending Top 10

## 1. [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)
- **语言**: Python
- **Stars**: 41,922
- **简介**: A skill to stop your coding agent from burying the answer. ADHD-friendly output.

### AI 总结
**简介**: 一个让编码助手输出“ADHD 友好”结果的技能插件，强制 AI 先给答案、再讲细节，避免把关键信息埋在长篇大论里。

**核心功能**:
- 强制“行动优先”输出：先给出下一步操作，再补充说明
- 多步骤任务自动编号，列表最多 5 项
- 每轮对话重申当前状态，结尾给出一个具体的下一步
- 屏蔽无关发散内容，去除客套话（如“Hope this helps!”）和总结性废话
- 提供具体时间估算（以分钟计），让进展可见
- 错误信息直述事实，不绕弯子

**技术亮点**:
- 基于 Python 实现的 Claude Code 技能/插件，通过 `SKILL.md` 定义 10 条输出规则
- 支持 fork 后自定义规则并替换上游版本
- 提供多语言 README（中、日、韩、泰、越、葡等）
- 灵感来源于《The Adult ADHD Tool Kit》，但适配 LLM 的响应方式而非人类日程管理

---
## 2. [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view)
- **语言**: JavaScript
- **Stars**: 27,186
- **简介**: A spy satellite simulator in your browser, except the data is real. Live open source spatial intelligence on a photorealistic 3D globe.

### AI 总结
**简介**: 一个基于浏览器的开源间谍卫星模拟器，在逼真的 3D 地球上实时呈现真实的公开空间情报数据。

**核心功能**:
- **实时追踪**: 飞机、船舶、卫星、地震、交通及公共摄像头等实时数据图层
- **驾驶舱视角**: 可进入任意被追踪航班的内部视角，摄像头全程锁定下方地形
- **点击追踪**: 锁定任意目标，绘制轨迹并显示完整元数据，可一键跳转至最近的实时摄像头
- **语音交互**: 通过实时 AI 代理实现免手操作的语音控制与语音白板标注
- **3D 机库**: 按机型呈现真实飞机模型（787、ATR-72、MQ-9 等），靠近时自动从图标切换为 3D 模型
- **传感器滤镜**: 基于 GLSL 的 CRT、夜视、热成像、黑白等视觉效果
- **军事 HUD 与检测叠加**: 战术抬头显示及屏幕空间目标检测框
- **场景导演与分享链接**: 录制电影级镜头，并将视角、图层、追踪目标序列化为 URL

**技术亮点**:
- 纯 JavaScript 实现，完全在浏览器本地运行，代码可审查、可扩展
- 每个数据图层为独立模块，便于自行添加数据源
- 无需 API 密钥即可启动，使用 Esri 卫星影像与免密地形，OSM 作为回退方案，可选密钥在应用内添加
- 曾登上 GitHub Trending 日榜与周榜第一

---
## 3. [nab138/iloader](https://github.com/nab138/iloader)
- **语言**: TypeScript
- **Stars**: 2,917
- **简介**: User friendly sideloader

### AI 总结
**简介**: iloader 是一款基于 Tauri 构建的 TypeScript 桌面工具，用于便捷地为 iOS 设备侧载应用（如 SideStore）并管理配对文件。

**核心功能**:
- 一键安装 SideStore（或 LiveContainer + SideStore），自动导入证书并放置 rppairing 与 lockdown 配对文件
- 支持导入任意 IPA 文件
- 智能错误提示，帮助排查常见问题
- 管理 StikDebug、SideStore、Protokolle 等应用中的配对文件
- 查看并吊销开发证书与 App ID

**技术亮点**: 使用 Tauri 构建桌面应用，结合 Rust 与 TypeScript（Bun/Node.js）开发；依赖 idevice 与设备通信、isideload 完成应用安装与签名；支持多语言本地化（i18next），并提供 Windows、macOS、Linux 多平台安装方式。

---
## 4. [melgarafael/DeskcommCRM](https://github.com/melgarafael/DeskcommCRM)
- **语言**: TypeScript
- **Stars**: 1,365
- **简介**: Open-source AI sales OS — self-hosted CRM with native AI agents + WhatsApp (WAHA). Open alternative to Kommo, Octadesk & Intercom for any business that sells by chat. MCP-ready, multi-tenant, LGPD.

### AI 总结
**简介**: DeskcommCRM 是一款开源的 AI 销售操作系统，将原生 AI 代理与 WhatsApp 集成到自托管 CRM 中，是 Kommo、Octadesk 和 Intercom 的开放替代方案。

**核心功能**:
- AI 代理在 WhatsApp 内自动接待、筛选和完成销售
- 自托管部署，数据完全由用户掌控，无月费、无功能锁定
- 支持多租户，符合 LGPD（巴西数据保护法），MCP-ready
- 一键安装脚本，可在 VPS 上快速部署完整系统（应用 + WhatsApp + 数据库）

**技术亮点**: 基于 TypeScript 严格模式开发，采用 Next.js 16 框架，后端使用 Supabase（Postgres + Auth + Storage），通过 Docker 容器化部署，与 HostGator 合作提供一键安装工具包，支持 OpenRouter、Anthropic 或 OpenAI 的 AI 模型接入。

---
## 5. [vastsa/PI-Desktop](https://github.com/vastsa/PI-Desktop)
- **语言**: TypeScript
- **Stars**: 2,792
- **简介**: Local-first AI coding agent desktop: Electron + Rust host core + pi Agent Harness + user-installable plugins

### AI 总结
**简介**: PI-Desktop 是一个本地优先的 AI 编程智能体桌面工作台，基于 Electron + Rust 主机核心 + pi Agent Harness 构建，支持用户安装插件。

**核心功能**:
- **自带模型**: 支持 OpenAI、Anthropic、本地模型、托管网关及任意 OpenAI 兼容 API，可按会话切换多个提供商和模型
- **桌面优先**: 在统一工作区中管理项目、对话、审查、文件、预览、通知和扩展，不绑定特定编辑器或终端
- **可审查的权限层**: 智能体的读写文件和执行命令等特权操作需经过权限层，用户可审查 diff、检查命令输出并决定自主程度
- **三种工作模式**: Agent（直接执行）、Plan（先审批实现计划）、Goal（先审批结果和验收标准，由智能体选择路径）
- **可扩展**: 支持 Skills、MCP 服务器、Subagents 和可安装插件，插件可贡献工具、命令、面板、主题、服务等

**技术亮点**: Electron 桌面框架 + Rust 主机核心 + pi Agent Harness 架构；TypeScript 开发；支持 macOS、Windows、Linux 三平台；无强制账户、无强制中继、无编辑器锁定。

---
## 6. [armory3d/armorpaint](https://github.com/armory3d/armorpaint)
- **语言**: C
- **Stars**: 4,732
- **简介**: Graphics Creation Tools

### AI 总结
**简介**: ArmorPaint 是一款基于 C 语言开发的 3D PBR 纹理绘制软件，本仓库面向开发者开放全部开发过程。

**核心功能**:
- 3D PBR 纹理绘制
- 跨平台支持（Windows、Linux、macOS、Android、iOS、WASM）

**技术亮点**:
- 使用 C 语言开发，提供各平台原生编译方案（Visual Studio、Xcode、Android Studio 等）
- 支持 WASM 编译，可嵌入数据文件（需 clang 19+ 的 c23 #embed 支持）
- 提供本地化文件生成工具，便于多语言适配
- 采用 Armory3D 生态体系，源码完全开放，二进制发行版付费以支持项目发展

---
## 7. [alsk1992/CloddsBot](https://github.com/alsk1992/CloddsBot)
- **语言**: TypeScript
- **Stars**: 2,162
- **简介**: Open Source AI trading agent that operates autonomously across 1000+ markets - Polymarket, Kalshi, Binance, Hyperliquid, Solana DEXs, 5 EVM chains. Scans for edge, executes instantly, manages risk while you sleep. Agent commerce protocol for machine-to-machine payments. Self-hosted. Built on Claude.

### AI 总结
**简介**: Clodds 是一个基于 Claude 构建的开源自主 AI 交易终端，支持在 1000+ 市场（预测市场、加密货币现货、永续合约、代币发行等）中自动扫描套利机会、即时执行交易并管理风险。

**核心功能**:
- **多市场交易**: 覆盖 10 个预测市场（Polymarket、Kalshi 等）+ 7 个期货交易所（Binance、Hyperliquid 等），支持 Solana 生态（Jupiter、Pump.fun、Raydium、Orca）和 5 条 EVM 链（Base、ETH、Arbitrum、Optimism、Polygon）
- **118+ 交易策略**: 内置鲸鱼追踪、套利检测、跟单交易、DCA 定投机器人等策略
- **21 个消息平台接入**: 可通过任意主流聊天平台以自然语言对话方式进行交易和投资组合管理
- **内置 WebChat 界面**: 无需第三方依赖的浏览器终端，支持会话管理、上下文压缩、无限历史记录
- **Bittensor 子网挖矿**: 支持 TAO 代币挖矿
- **Agent 商务协议**: 支持机器间（M2M）自动支付

**技术亮点**:
- 基于 **TypeScript 5.3** 开发，要求 **Node.js ≥ 22**
- 由 **Claude** 提供 AI 推理能力，通过自然语言驱动全部交易操作
- 完全**自托管**，一条 `npm install -g clodds && clodds onboard` 即可完成部署
- 采用 MIT 开源协议，12 天内为 Solana Colosseum Agent Hackathon 完整开发
- 上线 14 天即获得 10,700+ 次 Git 克隆

---
## 8. [nashsu/llm_wiki](https://github.com/nashsu/llm_wiki)
- **语言**: TypeScript
- **Stars**: 18,757
- **简介**: LLM Wiki is a cross-platform desktop application that turns your documents into an organized, interlinked knowledge base — automatically. Instead of traditional RAG (retrieve-and-answer from scratch every time), the LLM incrementally builds and maintains a persistent wiki from your sources。

### AI 总结
**简介**: LLM Wiki 是一款跨平台桌面应用，利用 LLM 将个人文档自动转化为结构化、互链的持久化知识库，以“增量构建 Wiki”取代传统 RAG 的每次从头检索。

**核心功能**:
- **两步思维链摄取**：LLM 先分析再生成 Wiki 页面，支持来源溯源与增量缓存
- **多格式文档解析**：支持 PDF、Office、EPUB/MOBI、图片、网页剪藏及批量 URL，内置云端/本地 MinerU PDF 处理
- **多模态图片摄取**：从 PDF 提取图片并由视觉 LLM 生成描述，支持图片感知搜索与灯箱预览
- **知识图谱与社区发现**：4 信号关联模型（直接链接、来源重叠、Adamic-Adar、类型亲和）+ Louvain 聚类
- **向量语义搜索**：基于 LanceDB 的可选嵌入检索，兼容任意 OpenAI 兼容端点
- **深度研究**：LLM 优化搜索主题，通过 Tavily/SerpApi/SearXNG 多查询检索并自动摄取
- **Rust 后端 Chat Agent**：支持工具调用、工作区文件生成、Shell 审批与流式事件
- **持久化摄取队列**：串行处理，支持崩溃恢复、取消、重试与进度可视化
- **Chrome 网页剪藏**：一键抓取网页并自动入库
- **本地 HTTP API + MCP Server**：内置 `127.0.0.1:19828` JSON API 与 MCP 服务，支持混合搜索、图谱遍历与来源重扫

**技术亮点**: 基于 TypeScript 构建，采用 Rust 后端实现 Chat Agent 运行时；架构上以“知识编译一次、持续维护”替代传统 RAG 的重复推导模式，灵感源自 Karpathy 的 LLM Wiki 方法论；集成 Mermaid 图表渲染、Agent Skills 机制（`/skill` 调用本地 SKILL.md）及异步人工审核系统。

---
## 9. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 285,389
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，通过可组合的技能（skills）和自动触发的初始指令，让 AI 编码代理遵循规范的开发流程。

**核心功能**:
- **需求澄清**：代理在写代码前先退一步，通过对话挖掘真实需求，并分块展示规格说明供用户确认
- **实现计划**：设计确认后生成清晰可执行的实施计划，强调真正的红/绿 TDD、YAGNI 和 DRY 原则
- **子代理驱动开发**：用户确认后启动多代理协作流程，各代理逐项完成工程任务并接受审查，可持续自主工作数小时而不偏离计划
- **自动触发**：技能自动生效，无需用户额外操作，代理即具备 Superpowers 能力

**技术亮点**:
- 基于可组合的 skills 框架构建，支持自动触发机制
- 广泛兼容主流编码工具：Claude Code、Antigravity、Codex（App/CLI）、Cursor、Devin CLI、Factory Droid、Gemini CLI、GitHub Copilot CLI、Grok Build CLI、Kimi Code、OpenCode、Pi、Hermes Agent 等
- 以 Shell 为主要实现语言，提供企业级商业支持服务

---
## 10. [Sonarr/Sonarr](https://github.com/Sonarr/Sonarr)
- **语言**: C#
- **Stars**: 15,743
- **简介**: Smart PVR for newsgroup and bittorrent users.

### AI 总结
**简介**: Sonarr 是一款基于 C# 开发的智能 PVR（个人视频录像机）工具，专为 Usenet 和 BitTorrent 用户设计，用于自动监控、下载、整理和升级电视剧集。

**核心功能**:
- 监控多个 RSS 源，自动检测并抓取喜爱剧集的新剧集
- 自动对下载的文件进行排序和重命名，支持完全自定义命名规则
- 扫描现有媒体库，自动下载缺失的剧集
- 当有更高质量格式出现时，自动升级已下载文件的画质（如从 DVD 升级到 Blu-Ray）
- 下载失败自动重试其他发布版本
- 支持手动搜索，可查看某发布未被自动下载的原因
- 完整集成 SABnzbd 和 NZBGet 下载客户端
- 与 Kodi、Plex 深度集成，支持通知、媒体库更新和元数据处理
- 完整支持特别篇和多集连播的剧集

**技术亮点**:
- 基于 C# 开发，跨平台支持 Windows、Linux、macOS、Raspberry Pi 等
- 采用 GNU GPL v3 开源协议
- 提供 v4 Beta API 文档，便于第三方集成与扩展

---
