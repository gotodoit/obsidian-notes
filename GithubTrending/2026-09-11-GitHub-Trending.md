---
tags:
  - github-trending
  - daily
date: 2026-09-11
created: 2026-09-11T01:55:43.288Z
---

# 2026-09-11 GitHub Trending Top 10

## 1. [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)
- **语言**: Python
- **Stars**: 38,457
- **简介**: A skill to stop your coding agent from burying the answer. ADHD-friendly output.

### AI 总结
**简介**: 一个让 AI 编程助手直接给出答案、不再铺垫废话的 Claude 技能，输出风格面向 ADHD 用户优化。

**核心功能**:
- 强制“行动优先”：先给下一步操作，再给解释
- 多步骤任务自动编号，列表最多 5 项
- 每轮对话重述当前状态，结尾给出一个具体下一步
- 禁止寒暄、总结、收尾客套话（如“希望有帮助”）
- 错误信息平铺直叙，时间估算具体到分钟

**技术亮点**: 基于 Claude Code 插件机制实现，核心规则定义在 `skills/i-have-adhd/SKILL.md` 中，支持 fork 后自定义规则；提供多语言 README（中、日、韩、泰、越、葡等）。

---
## 2. [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view)
- **语言**: JavaScript
- **Stars**: 24,422
- **简介**: A spy satellite simulator in your browser, except the data is real. Live open source spatial intelligence on a photorealistic 3D globe.

### AI 总结
**简介**: God's Eye View 是一个运行在浏览器中的开源"间谍卫星模拟器"，将航班、船舶、卫星、地震、交通和公共摄像头等真实公开数据实时汇聚在一个照片级 3D 地球上进行空间情报探索。

**核心功能**:
- **实况数据图层**：实时追踪飞机、船舶、卫星、地震、交通流量与公共摄像头，多数数据源为实时或定期刷新
- **驾驶舱视角**：可进入任意被追踪航班的座舱，摄像机全程跟随地形
- **点击追踪**：锁定任意目标，绘制渐隐轨迹并展示完整元数据，可从火灾/船只一键切换至最近的实时摄像头
- **语音白板与语音控制**：通过实时 AI 智能体用语音在世界地图上标注边界、标记与路线
- **3D 机库**：按机型提供真实 3D 模型（787、ATR-72、Citation、Bell 206、MQ-9 等），靠近时自动从图标切换为模型
- **传感器视觉滤镜**：基于 GLSL 的 CRT、NVG、FLIR/热成像、Noir、Snow 等效果
- **检测叠加层与军事 HUD**：屏幕空间包围盒与 ID 标注，配合情报风格战术抬头显示
- **场景导演与分享链接**：录制电影级镜头巡游，并将相机、风格、图层乃至追踪目标序列化为 URL

**技术亮点**:
- 纯 JavaScript 实现，完全在浏览器本地运行，源代码可审查与扩展
- 每个数据图层为独立模块，支持自由增删与自定义扩展
- 无需 API Key 即可启动，默认使用 Esri 卫星影像与免密钥地形，OSM 作为回退方案
- 可选集成 Cesium ion token 实现照片级 3D 渲染
- 支持通过 Pinokio 一键安装或终端本地运行
- 项目曾登顶 GitHub Trending 日榜与周榜第一（2026 年 8 月）

---
## 3. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 284,725
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，基于可组合的技能（skills）与初始指令构建，让 AI 代理自动遵循规范化的开发流程。

**核心功能**:
- **需求澄清**：代理不会直接写代码，而是先追问用户真实意图，逐步提炼出规格说明
- **分块评审**：将设计文档切成易读的小块展示给用户确认
- **实现规划**：生成足够清晰、可供初级工程师执行的实施计划，强调 TDD、YAGNI、DRY
- **子代理驱动开发**：确认后启动多代理并行推进任务，自动检查与评审，可长时间自主工作而不偏离计划
- **自动触发技能**：技能自动生效，无需额外操作

**技术亮点**:
- 以 Shell 实现，基于可组合技能（composable skills）架构
- 支持广泛的编码代理平台：Claude Code、Codex（App/CLI）、Cursor、Gemini CLI、GitHub Copilot CLI、Devin CLI、Factory Droid、OpenCode 等十余种
- 提供官方与自建插件市场两种安装渠道，支持各平台独立的插件/扩展安装机制

---
## 4. [alsk1992/CloddsBot](https://github.com/alsk1992/CloddsBot)
- **语言**: TypeScript
- **Stars**: 1,685
- **简介**: Open Source AI trading agent that operates autonomously across 1000+ markets - Polymarket, Kalshi, Binance, Hyperliquid, Solana DEXs, 5 EVM chains. Scans for edge, executes instantly, manages risk while you sleep. Agent commerce protocol for machine-to-machine payments. Self-hosted. Built on Claude.

### AI 总结
**简介**: Clodds 是一个基于 Claude 构建的开源自主 AI 交易终端，支持在 1000+ 市场（预测市场、加密货币现货、永续合约、代币发行等）中自动扫描交易机会、即时执行并管理风险。

**核心功能**:
- 覆盖 10+ 预测市场（Polymarket、Kalshi 等）和 7 家期货交易所（Binance、Hyperliquid 等），支持 Solana 生态（Jupiter、Pump.fun、Raydium 等）及 5 条 EVM 链
- 内置 118+ 交易策略，支持巨鲸追踪、套利检测、跟单交易和 DCA 机器人
- 支持 Bittensor 子网挖矿（TAO）和代币发行交易
- 提供 21 个消息平台接入渠道，可通过自然语言对话完成全部操作
- 自托管部署，内置 WebChat 浏览器界面，支持无限历史记录和上下文压缩
- 包含机器间支付协议（Agent Commerce Protocol）

**技术亮点**: 基于 TypeScript 5.3 开发，要求 Node.js ≥22；采用 Claude 作为 AI 核心引擎；架构上支持多链集成（Solana + EVM）、多交易所聚合、REST API 会话管理；WebChat 采用追加式数据库存储实现无限消息历史，并通过 LLM 自动摘要实现长对话上下文压缩。项目为 Colosseum Agent Hackathon 而建，12 天内完成开发。

---
## 5. [Tencent/teamai-cli](https://github.com/Tencent/teamai-cli)
- **语言**: TypeScript
- **Stars**: 3,828
- **简介**: Make Every Team AI Native

### AI 总结
**简介**: 腾讯开源的 TypeScript CLI 工具，通过统一管理团队技能、规则、MCP 和知识库，让各类 AI 编程助手实现"团队 AI 原生化"。

**核心功能**:
- 跨多 Agent 统一管理：支持 Claude Code、Codex、CodeBuddy、WorkBuddy、OpenCode、Cursor 等主流 AI 编程助手，统一分发 skills、rules、docs、env、agents、hooks、mcp 等资源
- 团队共享经验仓库：团队管理员在 Git 托管平台（GitHub、GitLab、GitCode、CNB、TGit 等）创建共享仓库，成员通过 `teamai init` 一键初始化，自动拉取最新配置，无需手动同步
- 支持项目级与用户级两种安装范围（`--scope user` 可安装到 `~` 目录）
- 提供模板生态（teamai-hub），可基于预置的生产级 skills、rules 和 review agents 快速起步
- 三层架构：Team Execution（统一执行方式）、Team Context（beta，让 Agent 理解团队）、Team Improvement（beta，让执行反哺团队）

**技术亮点**: 采用 TypeScript 开发，通过 npm 全局安装（`npm install -g teamai-cli`）；基于 Git 仓库实现团队配置的版本化分发与自动同步；覆盖 13 项能力维度（skills、rules、docs、env、agents、hooks、mcp、learnings、codebase、teamwiki、usage、sessions、dashboard），并对不同 Agent 提供差异化的能力支持矩阵；MIT 协议开源。

---
## 6. [AlexsJones/llmfit](https://github.com/AlexsJones/llmfit)
- **语言**: Rust
- **Stars**: 35,765
- **简介**: Hundreds of models & providers. One command to find what runs on your hardware.

### AI 总结
**简介**: llmfit 是一款用 Rust 编写的命令行工具，可自动检测本机硬件配置，帮助用户快速找到能在自己设备上流畅运行的开源大语言模型。

**核心功能**:
- **硬件自动检测**：识别 CPU 核心数、系统内存、独立/集成 GPU、VRAM 及统一内存架构（支持 NVIDIA CUDA、Apple Silicon、AMD ROCm、Intel OneAPI）。
- **模型兼容性评估**：根据模型参数量、上下文长度和量化格式（GGUF、AWQ、GPTQ、EXL2）预测内存占用与每秒 token 生成速度，并从质量、速度、适配度、上下文四个维度打分。
- **交互式 TUI 与 Web 面板**：默认提供零依赖终端界面，也支持功能丰富的 Web 仪表盘。
- **REST API**：暴露标准 HTTP JSON 接口（`/api/v1/system`、`/api/v1/models`），便于集成到编排器和自动化部署流程。
- **基准测试与结果共享**：可下载模型、启动服务并实测真实 tok/s，结果可直接从 TUI 提交为 PR 回馈项目，本地实测数据会替换估算值。
- **本地运行时支持**：兼容 Ollama、llama.cpp、MLX、Docker Model Runner、LM Studio 等后端，支持多 GPU 和 MoE 架构。

**技术亮点**: 使用 Rust 开发，跨平台支持 macOS（Apple Silicon 与 Intel）、Linux（x86_64 与 ARM64）及 Windows（x86_64）；提供 TUI 和 CLI 双模式；支持动态量化选择与速度估算；已通过 SignPath 代码签名。

---
## 7. [liquidslr/system-design-notes](https://github.com/liquidslr/system-design-notes)
- **语言**: Unknown
- **Stars**: 18,822
- **简介**: Notes of the book System Desgin Interview - An Insider's Guide

### AI 总结
**简介**: 该项目是《System Design Interview - An Insider's Guide》一书的学习笔记，系统整理了分布式系统设计的核心知识点。

**核心功能**:
- 整理系统设计面试常见题目的解题思路与方案
- 归纳可扩展性、可用性、一致性等核心概念
- 提供典型系统（如限流、缓存、消息队列等）的设计笔记

**技术亮点**: 内容偏向系统设计方法论与架构模式，涉及负载均衡、数据库分片、缓存策略、CAP 理论等分布式系统技术栈，适合面试准备与架构学习。

---
## 8. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 37,793
- **简介**: 38 editorial diagram types for Claude Code, Codex, and Pi. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一套为 Claude Code、Codex、Pi 等 AI 编程助手打造的编辑级图表生成技能，提供 39 种自包含 HTML + SVG 图表类型，风格克制、无阴影、无 Mermaid 廉价感。

**核心功能**:
- 提供 39 种编辑级图表类型（架构图、流程图、时序图、状态机、ER 图、时间线、泳道图、四象限、雷达图、飞轮循环等），每种均含 minimal light、minimal dark、full-editorial 三种静态变体
- 2.5.10 新增十种布局语法：Sankey、鱼骨图、Wardley map、看板、用户旅程、部署图、依赖图、UML 类图、故事地图、数据库 schema
- 语义模式将行为描述与布局分离，队列、策略追踪、信任边界等可复用现有类型而无需扩展类型数量
- 支持将 draw.io、Mermaid、Excalidraw 源文件按指定格式、尺寸和细节级别重绘
- 静态 HTML 为默认输出，可选动画用于有序说明；60 秒内读取网站即可匹配品牌配色

**技术亮点**: 纯自包含 HTML + SVG，无构建步骤、无 JavaScript、无外部图片依赖，浏览器直接打开即可；强调"删除是最高质量的操作"，每个节点都需证明其存在价值，强调色仅保留给读者应最先关注的 1–2 个元素，目标信息密度为 4/10。

---
## 9. [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2)
- **语言**: JavaScript
- **Stars**: 30,878
- **简介**: Prompt as Code | GPT Image 2 / 2.5 提示词与案例库，530+ 个案例、20+ 套工业级模板与可复用 Skills，新增 2.5 同提示词对比专区，附完整提示词与生成记录，持续更新。

### AI 总结
**简介**: 一个以 "Prompt as Code" 为理念的 GPT Image 2 / 2.5 提示词与案例库，收录 530+ 个案例、20+ 套工业级模板与可复用 Skills。

**核心功能**:
- 提供 530+ 个逆向工程案例与 20+ 套工业级模板，附带完整提示词与生成记录
- 新增 GPT Image 2.5 同提示词对比专区，支持拖动分割线、并排视图、图片放大与生成设置查看
- 配套可视化网站，支持大图预览、提示词复制、按风格/场景筛选及登录后测试生成
- 提供可复用 Skills 与社区交流群，持续更新案例与教程

**技术亮点**: 基于 JavaScript 构建，配套在线画廊网站（gpt-image2.canghe.ai）；覆盖 GPT Image 2.5 的 Sunburst（精准编辑）与 Flare（快速生成）两种模型；所有案例均为 100% 原创 AI 重写，并保留可验证的生成条件记录。

---
## 10. [armory3d/armorpaint](https://github.com/armory3d/armorpaint)
- **语言**: C
- **Stars**: 4,430
- **简介**: Graphics Creation Tools

### AI 总结
**简介**: ArmorPaint 是一款基于 C 语言开发的开源 3D PBR 纹理绘制软件，面向开发者开放全部源码。

**核心功能**:
- 3D PBR 纹理绘制
- 支持多平台编译运行（Windows、Linux、macOS、Android、iOS、WASM）
- 提供本地化文件生成与数据文件嵌入工具

**技术亮点**:
- 使用 C 语言编写，通过 `base/make` 脚本统一构建流程，生成各平台原生工程（Visual Studio、Xcode、Android Studio）
- 支持 WASM 目标编译，可运行于浏览器环境
- 支持 C23 `#embed` 特性嵌入数据文件
- 开发版源码免费开放，官方编译二进制为付费分发以支持项目持续开发

---
