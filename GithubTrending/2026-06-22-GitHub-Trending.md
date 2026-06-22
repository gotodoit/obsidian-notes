---
tags:
  - github-trending
  - daily
date: 2026-06-22
created: 2026-06-22T01:55:44.870Z
---

# 2026-06-22 GitHub Trending Top 10

## 1. [palmier-io/palmier-pro](https://github.com/palmier-io/palmier-pro)
- **语言**: Swift
- **Stars**: 5,273
- **简介**: macOS video editor built for AI

### AI 总结
**简介**: 一款专为 AI 打造的 macOS 视频编辑器，开源且支持 AI 生成与智能代理协作。

**核心功能**:
- **原生 Swift 视频编辑**: 从零构建的 Swift 视频编辑器，对标 Premiere Pro，并融入 AI 工作流。
- **内置生成式 AI**: 支持 Seedance、Kling、Nano Banana Pro 等模型，在时间线内直接生成视频和图像。
- **代理集成**: 通过 MCP 协议连接 Claude/Codex/Cursor，或使用内置代理协同编辑同一项目。

**技术亮点**:
- 使用 Swift 语言原生开发。
- 集成 MCP 服务器（HTTP 接口），支持与外部 AI 代理交互。
- 编辑器核心（不含生成 AI 功能）完全开源（GPLv3 许可证）。
- 仅支持 Apple Silicon 芯片的 macOS 26 (Tahoe) 系统。

---
## 2. [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)
- **语言**: Python
- **Stars**: 8,866
- **简介**: World's first open-source, agentic video production system. 12 pipelines, 52 tools, 500+ agent skills. Turn your AI coding assistant into a full video production studio.

### AI 总结
**简介**: OpenMontage 是全球首个开源、智能体驱动的视频制作系统，能将你的 AI 编码助手转变为完整的视频制作工作室。

**核心功能**:
- **12 条制作管线、52 种工具、500+ 智能体技能**，覆盖从研究、脚本、素材生成到剪辑和最终合成的全流程。
- **支持真实视频制作**：智能体可从免费素材库和开放档案中检索真实运动片段，编辑成时间线并渲染成品，而非仅生成图片动画。
- **提供多种示例管线**：包括电影预告片、动画短片、产品广告、吉卜力风格动画等，展示从概念到成品的完整制作能力。
- **低成本高效制作**：示例项目最低仅需 $0.15 成本，即可生成高质量视频内容。

**技术亮点**:
- 基于 Python 开发，支持多种 AI 模型（如 Veo、Kling v3、FLUX、OpenAI gpt-image-1、Google Chirp3-HD 等）。
- 集成 Remotion 合成引擎、WhisperX 字幕、粒子特效、相机运动（缩放、平移、Ken Burns 效果）等专业视频处理技术。
- 采用智能体驱动架构，用户仅需用自然语言描述需求，系统自动完成全部制作流程。

---
## 3. [chopratejas/headroom](https://github.com/chopratejas/headroom)
- **语言**: Python
- **Stars**: 44,546
- **简介**: Compress tool outputs, logs, files, and RAG chunks before they reach the LLM. 60-95% fewer tokens, same answers. Library, proxy, MCP server.

### AI 总结
**简介**: Headroom 是一个上下文压缩层，用于在 AI 代理将工具输出、日志、文件和 RAG 块发送到 LLM 之前进行压缩，可减少 60-95% 的 token 数，同时保持答案质量。

**核心功能**:
- **多模式集成**: 提供 Python/TypeScript 库 (`compress()`)、代理 (`headroom proxy`)、一键包装 (`headroom wrap`) 和 MCP 服务器，无需代码更改即可集成到任何应用或代理中
- **智能压缩**: 通过 ContentRouter 自动检测内容类型，使用 SmartCrusher (JSON)、CodeCompressor (AST) 和 Kompress-base (文本) 等算法进行针对性压缩
- **跨代理记忆**: 共享存储，在 Claude、Codex、Gemini 等代理间自动去重，并支持 `headroom learn` 从失败会话中学习并修正配置
- **输出 Token 缩减**: 不仅压缩输入，还能减少模型输出的 Token，去除仪式性内容和重复代码
- **可逆压缩 (CCR)**: 本地缓存原始内容，LLM 可通过 `headroom_retrieve` 按需检索

**技术亮点**: 基于 Python 构建，采用本地优先、可逆压缩架构；利用 CacheAligner 稳定前缀以提升提供商的 KV 缓存命中率；提供完整的 MCP 服务器支持。

---
## 4. [tursodatabase/turso](https://github.com/tursodatabase/turso)
- **语言**: Rust
- **Stars**: 20,836
- **简介**: Turso is an in-process SQL database, compatible with SQLite.

### AI 总结
**简介**: Turso 是一个用 Rust 编写的进程内 SQL 数据库，与 SQLite 兼容。

**核心功能**:
- 兼容 SQLite 的 SQL 方言、文件格式和 C API。
- 支持 `BEGIN CONCURRENT` 通过多版本并发控制（MVCC）提高写入吞吐量。
- 支持变更数据捕获（CDC），用于实时跟踪数据库更改。
- 提供多语言绑定支持，包括 Go、JavaScript、Java、.NET、Python、Rust 和 WebAssembly。
- 支持向量搜索和向量操作。
- 改进的 schema 管理，包括扩展的 `ALTER` 支持和更快的 schema 变更。
- 提供异步 I/O 支持（Linux 上的 `io_uring`）。
- 跨平台支持 Linux、macOS、Windows 和浏览器（通过 WebAssembly）。

**技术亮点**: 使用 Rust 语言开发，基于 MVCC 实现并发控制，支持 `io_uring` 异步 I/O，提供加密、增量计算（DBSP）、全文搜索（Tantivy）和多进程 WAL 协调等实验性功能。

---
## 5. [penpot/penpot](https://github.com/penpot/penpot)
- **语言**: Clojure
- **Stars**: 52,277
- **简介**: Penpot: The open-source design tool for design and code collaboration

### AI 总结
**简介**: Penpot 是一款开源设计平台，专为需要规模化构建数字产品的团队打造，强调设计基础设施的完全所有权和开放标准。  
**核心功能**:  
- **设计代码协作**: 支持实时协作，设计以 SVG、CSS、HTML 等开放标准表达，便于开发者直接翻译为代码。  
- **设计令牌**: 原生支持设计令牌，提供设计与开发之间的单一事实来源，确保一致性。  
- **MCP 服务器**: 实现设计与代码之间的多向工作流，支持 AI 驱动流程和自动化。  
- **CSS Grid 和 Flex 布局**: 支持响应式设计，从开始就模拟真实代码行为。  
- **插件系统**: 可扩展平台功能，集成其他应用并定制解决方案。  
- **自托管与开源**: 支持浏览器使用或自行部署，满足合规与治理要求。  
**技术亮点**: 基于 Clojure 语言开发，采用开放标准（SVG、CSS、HTML、JSON），提供强大的开放 API 和 MCP 服务器，支持实时协作与自托管。

---
## 6. [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis)
- **语言**: Python
- **Stars**: 44,543
- **简介**: LLM 驱动的多市场股票智能分析系统：多源行情、实时新闻、决策看板与自动推送，支持零成本定时运行。 LLM-powered multi-market stock analysis system with multi-source market data, real-time news, decision dashboard, automated notifications, and cost-free scheduled runs.

### AI 总结
**简介**: 基于 LLM 的多市场股票智能分析系统，支持 A 股、港股、美股、日股、韩股，每日自动生成决策仪表盘并推送到多种渠道。

**核心功能**:
- **AI 决策报告**: 自动生成包含核心结论、评分、买卖点位、风险警报等内容的分析报告
- **多市场数据聚合**: 整合行情、K 线、技术指标、资金流、新闻、公告和基本面数据
- **Web/桌面工作台**: 支持手动分析、任务进度、历史报告、回测、持仓和配置管理
- **Agent 策略问股**: 支持多轮追问，内置均线、缠论、趋势、热点等 15 种策略
- **智能导入与补全**: 支持图片、CSV/Excel、剪贴板导入，股票代码/名称自动补全
- **自动化与推送**: 支持 GitHub Actions、Docker、本地定时任务，推送至企业微信、飞书、Telegram 等渠道

**技术亮点**:
- 采用 Python 开发，支持多种 AI 模型（Gemini、OpenAI、Claude、DeepSeek 等）
- 多数据源架构（TickFlow、AkShare、Tushare、YFinance 等行情源 + 多新闻搜索源）
- 支持 GitHub Actions 零成本定时运行和 Docker 容器化部署

---
## 7. [koala73/worldmonitor](https://github.com/koala73/worldmonitor)
- **语言**: TypeScript
- **Stars**: 58,119
- **简介**: Real-time global intelligence dashboard. AI-powered news aggregation, geopolitical monitoring, and infrastructure tracking in a unified situational awareness interface

### AI 总结
**简介**: World Monitor 是一个基于 AI 的实时全球情报仪表盘，集成了新闻聚合、地缘政治监控和基础设施追踪功能，提供统一的情境感知界面。

**核心功能**:
- 500+ 精选新闻源，覆盖15个类别，AI自动合成简报
- 双地图引擎（3D地球和WebGL平面地图），支持56种地图图层
- 跨领域事件关联分析（军事、经济、灾害等信号汇聚）
- 国家不稳定指数（CII）评分，覆盖31个一级国家
- 金融雷达，监控29个证券交易所、商品、加密货币等
- 本地AI支持（Ollama），无需API密钥
- 6种站点变体（世界、科技、金融等），基于同一代码库
- 原生桌面应用（Tauri 2），支持macOS、Windows和Linux
- 支持24种语言，包括本地语言新闻和RTL布局

**技术亮点**: 采用TypeScript开发，基于Tauri 2构建跨平台桌面应用，使用globe.gl和deck.gl实现双地图引擎，支持Ollama本地AI推理，全站点从单一代码库构建和发布。

---
## 8. [bytedance/deer-flow](https://github.com/bytedance/deer-flow)
- **语言**: Python
- **Stars**: 72,610
- **简介**: An open-source long-horizon SuperAgent harness that researches, codes, and creates. With the help of sandboxes, memories, tools, skill, subagents and message gateway, it handles different levels of tasks that could take minutes to hours.

### AI 总结
**简介**: DeerFlow 是一个开源的长周期超级智能体框架，能够通过子智能体、记忆、沙箱和可扩展技能，处理从几分钟到数小时不等的复杂任务。

**核心功能**:
- **子智能体编排**: 支持多智能体协作，自动分解并执行复杂任务
- **沙箱与文件系统**: 提供安全的代码执行和文件操作环境
- **长期记忆**: 支持上下文工程和持久化记忆，实现跨会话的智能体学习
- **可扩展技能与工具**: 内置丰富工具集，支持 Claude Code 等第三方集成
- **IM 渠道集成**: 支持通过消息网关进行交互

**技术亮点**:
- 基于 Python 3.12+ 和 Node.js 22+ 构建
- 提供 Docker 一键部署和本地开发两种运行模式
- 支持 LangSmith 和 Langfuse 追踪，便于调试和监控
- 集成 BytePlus InfoQuest 智能搜索与爬取工具集
- 推荐使用 Doubao-Seed-2.0-Code、DeepSeek v3.2 等先进模型

---
## 9. [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)
- **语言**: C
- **Stars**: 10,363
- **简介**: High-performance code intelligence MCP server. Indexes codebases into a persistent knowledge graph — average repo in milliseconds. 158 languages, sub-ms queries, 99% fewer tokens. Single static binary, zero dependencies.

### AI 总结
**简介**: 一个高性能的代码智能 MCP 服务器，可将代码库索引为持久化知识图谱，支持 158 种语言，毫秒级索引，亚毫秒级查询，仅需极少的令牌数。

**核心功能**:
- **极速索引**: 平均仓库毫秒级全索引，Linux 内核（2800 万行代码，7.5 万个文件）仅需 3 分钟。
- **即插即用**: 单一静态二进制文件，支持 macOS/Linux/Windows，无需 Docker、运行时依赖或 API 密钥。
- **广泛语言支持**: 通过内置 tree-sitter 语法支持 158 种语言，无需额外安装。
- **混合 LSP 增强**: 对 Python、TypeScript、Go、C++ 等 10 种语言提供语义类型解析，生成函数、类、调用链、HTTP 路由等知识图谱。
- **14 个 MCP 工具**: 提供丰富的代码结构查询接口（如搜索、定义跳转、引用查找等）。
- **内置 3D 图可视化**: 通过 localhost:9749 交互式浏览知识图谱。
- **多智能体兼容**: 自动检测并配置 Claude Code、Codex CLI、Gemini CLI 等 11 种编码代理。
- **基础设施即代码索引**: 支持 Dockerfile、Kubernetes 清单等资源索引为图节点。

**技术亮点**: 纯 C 语言实现，零依赖；使用 RAM 优先流水线（LZ4 压缩、内存 SQLite、Aho-Corasick 模式匹配）实现高速索引；所有处理 100% 本地化，代码不离开机器；通过 SLSA 3 级安全认证，每次发布版本均经过 VirusTotal 扫描。

---
## 10. [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills)
- **语言**: Python
- **Stars**: 17,733
- **简介**: 754 structured cybersecurity skills for AI agents · Mapped to 5 frameworks: MITRE ATT&CK, NIST CSF 2.0, MITRE ATLAS, D3FEND & NIST AI RMF · agentskills.io standard · Works with Claude Code, GitHub Copilot, Codex CLI, Cursor, Gemini CLI & 20+ platforms · 26 security domains · Apache 2.0

### AI 总结
**简介**: 一个包含754个结构化网络安全技能的开源库，为AI代理提供专家级安全分析能力，覆盖26个安全领域并映射到6个行业框架。

**核心功能**:
- **754个生产级网络安全技能**：涵盖恶意软件分析、云安全、网络威胁狩猎等26个安全领域
- **六大框架映射**：每个技能均映射到MITRE ATT&CK、NIST CSF 2.0、MITRE ATLAS、D3FEND、NIST AI RMF及MITRE F3反欺诈框架
- **跨平台兼容**：支持Claude Code、GitHub Copilot、Codex CLI、Cursor、Gemini CLI等26+AI平台
- **标准化格式**：遵循agentskills.io开放标准，技能以结构化JSON格式存储
- **社区驱动**：开源项目（Apache 2.0许可），欢迎贡献和扩展

**技术亮点**:
- **Python实现**：使用Python编写技能库的解析和管理工具
- **统一框架映射**：每个技能同时关联多个安全框架，实现跨框架合规性检查
- **MITRE F3反欺诈框架集成**：首次在开源技能库中涵盖94个金融欺诈相关技能
- **可扩展架构**：支持通过PR添加新技能和框架映射，易于集成到现有安全工具链

---
