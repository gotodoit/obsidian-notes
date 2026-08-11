---
tags:
  - github-trending
  - daily
date: 2026-08-11
created: 2026-08-11T01:55:44.659Z
---

# 2026-08-11 GitHub Trending Top 10

## 1. [semantica-agi/semantica](https://github.com/semantica-agi/semantica)
- **语言**: Python
- **Stars**: 4,159
- **简介**: Graph-Native Infrastructure for Context and Accountable AI Systems

### AI 总结
**简介**: Semantica 是一个面向 AI 系统的图原生基础设施，帮助企业数据构建上下文图谱和知识图谱，实现可解释、可审计的决策智能，被誉为“AI Agent 的开源 Palantir”。

**核心功能**:
- **上下文图谱构建**: 从企业原始数据中提取关键信息，构建 Context Graph 和知识图谱，无需依赖 LLM
- **决策智能与因果推理**: 支持图分析和因果推理，内置完整的决策溯源（provenance）机制
- **本体管理与知识建模**: 提供 Ontology Hub 进行知识建模和本体管理，支持 W3C 标准
- **端到端可追溯性**: 所有决策过程可解释、可追踪、可审计，满足金融等强监管领域合规要求
- **多语言图存储支持**: 兼容 RDF 和 LPG 两种图数据模型，支持多种图数据库后端

**技术亮点**: 
- 采用 Python 开发，支持 Python 3.8+，通过 pip 一键安装
- 纯确定性基础设施层，不依赖 LLM 即可完成图构建、推理和溯源
- 开源、可自托管、可审计，零厂商锁定
- 支持与 Databricks Unity Catalog、Snowflake 等数据平台集成，无需导出数据即可构建治理完善的 lineage 知识图谱
- MIT 开源协议，拥有活跃的社区支持（Discord、YouTube 演示等）

---
## 2. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 141,869
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个集成了多种个性化 AI 专家的开源项目，可像组建梦之队一样为你的工作流配备各类专业 AI 助手。

**核心功能**:
- **多领域专家代理**: 提供从前端开发、UI 设计到 Reddit 社区运营等各类专业 AI 代理，每个代理都有独特的性格、工作流程和可交付成果
- **多工具集成**: 支持 Claude Code、Cursor、Codex、Gemini CLI、OpenCode、Aider、Windsurf 等十余种主流 AI 编码工具
- **灵活安装**: 提供桌面应用（macOS/Linux/Windows）、命令行脚本和手动复制三种安装方式，可按需选择特定团队或代理
- **生产级就绪**: 每个代理都包含身份特征、核心任务、技术交付物（含代码示例）、成功指标和沟通风格

**技术亮点**:
- 基于 Shell 脚本构建的自动化安装/转换系统，支持 `--tool`、`--division`、`--agent` 等参数细粒度控制
- 提供交互式安装向导，可自动检测已安装的工具并生成对应集成文件
- 原生桌面应用（Agency Agents）支持一键浏览和安装全部代理，并自动更新

---
## 3. [NanmiCoder/MediaCrawler](https://github.com/NanmiCoder/MediaCrawler)
- **语言**: Python
- **Stars**: 61,088
- **简介**: 小红书笔记 | 评论爬虫、抖音视频 | 评论爬虫、快手视频 | 评论爬虫、B 站视频 ｜ 评论爬虫、微博帖子 ｜ 评论爬虫、百度贴吧帖子 ｜ 百度贴吧评论回复爬虫 | 知乎问答文章｜评论爬虫

### AI 总结
**简介**: MediaCrawler 是一个基于 Playwright 的多平台自媒体数据采集工具，支持小红书、抖音、快手、B站、微博、贴吧、知乎等主流平台的公开信息抓取。

**核心功能**:
- 支持 7 大平台（小红书、抖音、快手、B站、微博、贴吧、知乎）的关键词搜索、指定帖子ID爬取、二级评论、创作者主页爬取
- 提供登录态缓存、IP代理池支持，以及评论词云图生成
- 支持断点续爬（Pro 版）、多账号 + IP代理池（Pro 版）
- 支持自媒体内容拆解 Agent（Pro 版）和多平台首页信息流推荐（Pro 版）

**技术亮点**:
- 基于 Playwright 浏览器自动化框架，通过保留登录态的浏览器上下文环境获取签名参数，无需 JS 逆向
- 默认使用 CDP 模式连接用户已有 Chrome 浏览器，复用浏览器登录状态，降低平台风控检测风险
- 使用 uv 作为 Python 包管理工具，保证依赖一致性
- 提供开源版与 Pro 版（企业级架构、代码重构优化、去除 Playwright 依赖）

---
## 4. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 85,768
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 这是一个为 AI 编码代理提供生产级工程技能的开源项目，将资深工程师的工作流程、质量门禁和最佳实践封装为技能，帮助 AI 代理在开发全阶段保持一致的高标准。

**核心功能**:
- **8 个斜杠命令映射开发生命周期**: `/spec`(定义)、`/plan`(规划)、`/build`(构建)、`/test`(测试)、`/review`(评审)、`/webperf`(性能审计)、`/code-simplify`(代码简化)、`/ship`(发布)
- **自动技能激活**: 根据当前任务自动触发相应技能，如设计 API 时激活接口设计技能，构建 UI 时激活前端工程技能
- **`/build auto` 自动模式**: 生成计划并自主实现所有任务，只需一次批准，每个任务仍保持测试驱动和单独提交，遇失败或风险自动暂停
- **支持 70+ 代理工具**: 通过开源 skills CLI 可安装到 Claude Code、Cursor、Codex、Copilot、Cline 等主流代理
- **灵活安装方式**: 支持一次性安装全部 24 个技能、按需选择单个技能，或通过原生插件市场集成

**技术亮点**: 采用 JavaScript 编写，提供完整的开发流程封装（定义→规划→构建→验证→评审→发布）；支持多种安装路径（npx CLI、Claude Code 插件市场、Cursor 目录同步）；技能设计遵循"测试即证明"、"清晰优于巧技"等工程原则。

---
## 5. [paperclipai/paperclip](https://github.com/paperclipai/paperclip)
- **语言**: TypeScript
- **Stars**: 76,535
- **简介**: The open-source app everyone uses to manage agents at work

### AI 总结
**简介**: Paperclip 是一个开源的多智能体编排平台，通过任务管理界面帮助企业协调和管理 AI 代理团队，实现业务目标的自动化运营。

**核心功能**:
- **智能体任务管理**: 以任务管理器为交互界面，支持定义业务目标、分配任务、审核工作成果
- **团队组织与治理**: 支持构建 AI 代理的组织架构（如 CEO、CTO、工程师等角色），提供预算控制、权限管理和目标对齐机制
- **多智能体协调**: 兼容 OpenClaw、Claude Code、Codex、Cursor、Bash、HTTP 等多种代理和工具，统一协调工作
- **成本监控与预算管理**: 实时追踪各代理的工作成本，支持设置预算限制
- **自主运行与审计**: 支持 24/7 无人值守运行，同时保留人工审计和干预能力
- **移动端管理**: 支持从手机端监控和管理自主业务运营

**技术亮点**: 基于 Node.js 服务端和 React 前端的全栈架构，采用 TypeScript 开发，遵循 MIT 开源协议。核心设计围绕四大支柱：任务管理、组织结构、训练体系和基础设施，以"心跳机制"实现异构代理的统一接入，提供从目标定义到团队组建再到执行监控的完整闭环流程。

---
## 6. [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent)
- **语言**: TypeScript
- **Stars**: 13,134
- **简介**: A self-improving RLM agent for coding workflows and long-running autonomous tasks.

### AI 总结
**简介**: Prime Agent 是一个开源的、可自我改进的递归语言模型（RLM）智能体，专为编码工作流和长时间运行的自主任务设计。

**核心功能**:
- **程序化一切操作**: 内置持久化 IPython 作为模型工具，文件操作、Shell 命令、工具调用、子智能体和上下文管理均通过代码完成
- **内置子智能体系统**: 通过 `rlm(...)` 生成真实子智能体，支持并行或后台工作，并以编程方式返回结果
- **自我改进的 Harness**: `/refine` 命令可审查当前轨迹，对补充状态应用小规模、有证据支持的更新，且支持快照回滚
- **可执行的技能系统**: 技能是可导入的 Python 包，内置技能创建器可将重复工作流转化为项目或个人技能
- **后台会话支持**: 守护进程支持的智能体在终端断开后继续运行，可随时重新连接
- **智能体间直接通信**: 运行的智能体可直接交换消息和相互编排，无需经过用户中转
- **长任务持续执行**: 自动压缩、持久目标、心跳、调度、自主模式和保留子智能体确保跨会话进度不丢失

**技术亮点**: 基于 TypeScript 构建，采用递归语言模型（RLM）架构，将上下文视为变量（prompt-as-a-variable），工具调用视为函数调用（programmatic tool calling）；结合持久化 Python 控制环境和持久化 Harness 状态，使工作上下文和可复用操作模式超越单个聊天窗口的限制。

---
## 7. [LadybirdBrowser/ladybird](https://github.com/LadybirdBrowser/ladybird)
- **语言**: C++
- **Stars**: 65,271
- **简介**: Truly independent web browser

### AI 总结
**简介**: Ladybird 是一个真正独立的网页浏览器，基于全新的 Web 标准引擎构建，目前处于预 alpha 阶段，适合开发者使用。

**核心功能**:
- 多进程架构：主 UI 进程、多个 WebContent 渲染进程、ImageDecoder 进程和 RequestServer 进程分离
- 安全设计：图像解码和网络连接在独立进程中运行，增强对恶意内容的防护；每个标签页拥有独立的沙箱化渲染进程
- 现代 Web 支持：旨在构建完整、可用的现代 Web 浏览器
- 跨平台：支持 Linux、macOS、Windows（通过 WSL2）及其他 \*Nixes 系统

**技术亮点**:
- 继承自 SerenityOS 的核心库组件，包括 LibWeb（渲染引擎）、LibJS（JavaScript 引擎）、LibWasm（WebAssembly 实现）、LibCrypto/LibTLS（加密与 TLS）、LibHTTP（HTTP/1.1 客户端）、LibGfx（2D 图形与图像解码）、LibUnicode（Unicode 和区域支持）、LibMedia（音视频播放）、LibCore（事件循环与 OS 抽象层）和 LibIPC（进程间通信）
- 采用 2-clause BSD 许可证开源

---
## 8. [ruvnet/RuView](https://github.com/ruvnet/RuView)
- **语言**: Rust
- **Stars**: 89,383
- **简介**: π RuView turns commodity WiFi signals into real-time spatial intelligence, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: RuView 是一个基于 WiFi 信号（CSI）的无线感知平台，无需摄像头即可实现穿墙的人体检测、生命体征监测和空间智能，并用 Rust 实现。

**核心功能**:
- **存在与占用检测** — 穿墙识别人体、计数、追踪进出房间
- **生命体征监测** — 无接触测量呼吸频率和心率，支持睡眠监测与呼吸暂停筛查
- **活动识别** — 通过 CSI 时间模式识别行走、坐姿、手势及跌倒
- **环境映射** — 基于 RF 指纹识别房间、检测家具移动和新物体
- **无摄像头姿态估计** — 从 WiFi CSI 中估算 17 个身体关键点
- **智能家居集成** — 原生支持 Home Assistant、Apple Home、Google Home、Alexa（通过 MQTT 或 Matter 桥接），每个节点输出 21 个实体（11 个原始信号 + 10 个推断语义状态）
- **本地自动化** — HOMECORE 提供状态管理、历史记录、自动化、Wasm 插件和语音钩子
- **AI 辅助运维** — RuView MetaHarness 提供引导式校准、训练、验证和声称检查

**技术亮点**: 基于 ESP32 低成本传感器采集 CSI 数据；采用 Rust 实现；包含完整模型工作流（录制 CSI、训练模型、加载 RVF 文件、切换 LoRA 配置）；支持多模态 RF 融合（WiFi、雷达、UWB、蜂窝感知）；内置隐私治理（隐私策略、不确定性、溯源和见证记录）；提供可签名 Wasm 插件机制和 HomeKit 桥接。

---
## 9. [danielmiessler/LifeOS](https://github.com/danielmiessler/LifeOS)
- **语言**: TypeScript
- **Stars**: 17,945
- **简介**: ⛰️A General Hill-climbing AI harness that helps you move from Current State to Ideal State in both Life and Work.

### AI 总结
**简介**: LifeOS 是一个通用人工智能（AI）操作框架，旨在帮助用户利用 AI 从当前状态（Current State）迈向理想状态（Ideal State），覆盖生活与工作的方方面面。

**核心功能**:
- **状态迁移引擎**: 以“从当前状态到理想状态”为核心概念，驱动 AI 辅助用户实现目标。
- **意图工程（Intent Engineering）**: 支持用户定义和优化意图，让 AI 更精准地理解需求。
- **通用爬山算法（General Hill Climbing）**: 通过迭代优化逐步逼近理想状态。
- **个性化上下文管理**: 捕获用户的身份、价值观和目标，使 AI 具备“了解你”的能力。
- **TELOS 框架与算法**: 提供结构化的任务分解与执行路径。
- **技能系统（Skill System）与钩子系统（Hook System）**: 支持可扩展的技能模块和自动化触发机制。
- **Pulse 与语音交互**: 集成活动流（Pulse）和语音功能，增强交互体验。
- **安全与学习机制**: 内置安全层和持续学习能力，确保系统可靠演进。

**技术亮点**: 基于 TypeScript 构建，使用 Bun 作为运行时，深度集成 Claude Code 等 AI 编码工具；采用模块化架构（如 Cortex、Synapse、Atlas、Ledger 等组件），支持通过自然语言提示词一键安装，并内置 Hermes Sidecar 等辅助进程。

---
## 10. [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)
- **语言**: TypeScript
- **Stars**: 165,125
- **简介**: The context API to search, scrape, and interact with the web at scale. 🔥

### AI 总结
**简介**: Firecrawl 是一个开源的 Web 数据 API，用于大规模搜索、抓取和交互网页，将网页内容转换为干净的 Markdown 或结构化数据，供 AI 代理使用。

**核心功能**:
- **Search**: 搜索网页并获取结果的完整页面内容
- **Scrape**: 将任意 URL 转换为 Markdown、HTML、截图或结构化 JSON
- **Interact**: 抓取页面后，通过 AI 提示或代码与页面交互（点击、滚动、输入等）
- **Crawl**: 单次请求抓取网站所有 URL
- **Map**: 快速发现网站上的所有 URL
- **Batch Scrape**: 异步批量抓取数千个 URL
- **Agent**: 通过自然语言描述自动完成数据收集任务
- **Media parsing**: 解析 PDF、DOCX 等网页托管文件内容

**技术亮点**:
- 采用 TypeScript 开发，提供 Python、Node.js、CLI 和 cURL 多种调用方式
- 行业领先的可靠性，覆盖 96% 的网页（含 JS 重页面），P95 延迟仅 3.4 秒
- 内置代理轮换、速率限制、JS 屏蔽内容处理等机制，零配置即可使用
- 支持 MCP（Model Context Protocol）客户端集成，可连接任意 AI 代理
- 输出针对 LLM 优化，减少 token 消耗，支持结构化 JSON 输出

---
