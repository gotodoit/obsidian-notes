---
tags:
  - github-trending
  - daily
date: 2026-07-09
created: 2026-07-09T01:55:48.671Z
---

# 2026-07-09 GitHub Trending Top 10

## 1. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 74,203
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 一套为 AI 编码代理设计的、封装了资深工程师工作流、质量门禁和最佳实践的工程技能集，涵盖从需求定义到交付上线的完整开发周期。

**核心功能**:
- **8 个斜杠命令**: 提供 `/spec`、`/plan`、`/build`、`/test`、`/review`、`/ship` 等命令，映射开发生命周期的每个阶段，自动激活相应的技能。
- **自动化构建 (`/build auto`)**: 在规格确定后，自动生成计划并逐个实现任务，以测试驱动且独立提交的方式运行，遇失败或风险自动暂停。
- **自动技能激活**: 根据开发者当前的操作（如设计 API、构建 UI）自动触发对应的专业技能。
- **广泛兼容性**: 通过 `npx skills` CLI 支持 70+ 种 AI 代理（如 Claude Code, Cursor, Copilot），并提供原生集成指南。

**技术亮点**:
- **基于 Markdown 的技能包**: 技能以 `SKILL.md` 文件形式存在，可复制到 `.cursor/rules/` 等规则目录中直接使用。
- **可组合与可扩展**: 支持按需安装全部 24 个技能或单个技能（如 `code-review-and-quality`、`test-driven-development`），便于定制工作流。

---
## 2. [ruvnet/RuView](https://github.com/ruvnet/RuView)
- **语言**: Rust
- **Stars**: 79,163
- **简介**: π RuView turns commodity WiFi signals into real-time spatial intelligence, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: RuView 是一个基于 WiFi 信号的无接触感知平台，利用普通路由器信号实现穿墙空间感知、生命体征监测和存在检测，无需摄像头或可穿戴设备。

**核心功能**:
- **存在与占用检测**：穿墙识别人体、计数、追踪进出
- **生命体征监测**：无接触测量呼吸率和心率，支持睡眠监测
- **活动识别**：识别行走、坐姿、手势、跌倒等动作
- **环境映射**：通过射频指纹识别房间、检测家具移动和新物体
- **智能家居集成**：原生支持 Home Assistant、Apple Home、Google Home、Alexa 等平台

**技术亮点**:
- 使用 ESP32 低成本传感器（约 $9/节点）采集 WiFi 信道状态信息 (CSI)
- 基于脉冲神经网络 (SNN) 的本地学习，30秒内适应新环境
- 边缘计算，无需云端或互联网，支持 Ed25519 密码学认证
- 预训练模型仅 8KB (4-bit 量化)，在树莓派上微秒级推理
- 多频段 WiFi 扫描，可利用邻居路由器作为雷达信号源

---
## 3. [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory)
- **语言**: TypeScript
- **Stars**: 7,683
- **简介**: TencentDB Agent Memory delivers fully local long-term memory for AI Agents via a 4-tier progressive pipeline, with zero external API dependencies.

### AI 总结
**简介**: TencentDB Agent Memory 是一款为 AI 智能体提供全本地化、分层式长期记忆的 TypeScript 工具，通过四级渐进式流水线实现零外部 API 依赖。

**核心功能**:
- **符号化短时记忆**: 将繁重的工具日志压缩为紧凑的 Mermaid 符号，减少 Token 消耗并提升任务成功率。
- **分层长期记忆**: 将碎片化对话提炼为结构化的用户画像（Persona）和场景（Scenario），替代扁平向量存储。
- **渐进式上下文管理**: 智能体仅需关注顶层结构，在出错时通过 node_id 下钻至底层细节。
- **技能生成分层**: 从执行轨迹中推导通用解决方案模式，实现经验复用。

**技术亮点**: 采用四级语义金字塔（L0对话→L1原子事实→L2场景→L3画像）进行记忆分层，结合符号化记忆与异构存储，在基准测试中实现 Token 消耗降低最多 61.38%，成功率提升 51.52%。

---
## 4. [prisma/prisma](https://github.com/prisma/prisma)
- **语言**: TypeScript
- **Stars**: 46,578
- **简介**: Next-generation ORM for Node.js & TypeScript | PostgreSQL, MySQL, MariaDB, SQL Server, SQLite, MongoDB and CockroachDB

### AI 总结
**简介**: Prisma 是 Node.js 和 TypeScript 的下一代 ORM，支持 PostgreSQL、MySQL、SQLite 等多种数据库。

**核心功能**:
- Prisma Client：自动生成且类型安全的查询构建器，用于 Node.js 和 TypeScript 后端应用
- Prisma Migrate：声明式数据建模与迁移系统
- Prisma Studio：图形化界面，用于查看和编辑数据库数据

**技术亮点**: 基于 TypeScript 开发，通过 Prisma schema 文件定义数据模型和生成器，支持多种数据库（包括关系型和非关系型），可与 REST、GraphQL、gRPC 等 API 架构集成。

---
## 5. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 50,780
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: /last30days 是一个 AI 代理驱动的搜索引擎，聚合 Reddit、X、YouTube 等平台内容，并按真实用户互动（点赞、投票、金钱）排序，生成接地气的总结。

**核心功能**:
- **多平台聚合搜索**: 同时搜索 Reddit、X、YouTube、TikTok、Hacker News、Polymarket、GitHub 等平台，获取最新内容。
- **基于互动的评分排序**: 按 Reddit 点赞、X 点赞、YouTube 播放量、Polymarket 赔率等真实用户行为评分，而非编辑推荐。
- **AI 代理综合总结**: AI 代理将各平台结果合成一份简洁、有依据的摘要，提供深度洞察。
- **零配置快速上手**: Reddit、HN、Polymarket 和 GitHub 开箱即用，运行一次后可通过设置向导解锁更多平台。

**技术亮点**: 使用 Python 开发，集成多个平台的独立 API 和认证，通过代理桥接“围墙花园”，实现跨平台数据并行检索与智能评分。

---
## 6. [argoproj/argo-cd](https://github.com/argoproj/argo-cd)
- **语言**: Go
- **Stars**: 23,439
- **简介**: Declarative Continuous Deployment for Kubernetes

### AI 总结
**简介**: Argo CD 是一个基于 GitOps 理念的 Kubernetes 声明式持续交付工具。

**核心功能**:
- 应用定义、配置和环境声明式管理，并支持版本控制
- 自动化部署和生命周期管理，具备可审计性和易理解性
- 提供可视化 UI 界面和实时演示环境

**技术亮点**:
- 使用 Go 语言开发，集成 SLSA 3 级安全标准
- 支持 Helm Chart 部署，通过 Artifact HUB 分发
- 具备完整的 CI/CD 集成测试和代码覆盖率保障
- 活跃的社区支持，包括 Slack 频道、GitHub Discussions 和定期社区会议

---
## 7. [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)
- **语言**: C#
- **Stars**: 11,943
- **简介**: OfficeCLI is the first and best Office suite purpose-built for AI agents to read, edit, and automate Word, Excel, and PowerPoint files. Free, open-source, single binary, no Office installation required.

### AI 总结
**简介**: OfficeCLI 是首个专为 AI 代理设计的办公套件，通过单行命令实现对 Word、Excel、PowerPoint 的读写、编辑和自动化操作。

**核心功能**:
- **AI 代理集成**: 支持 Claude Code、Cursor、Windsurf、GitHub Copilot 等 AI 编码代理，无需额外配置即可操作 Office 文档
- **文档创建与编辑**: 支持创建、添加、设置和删除 PowerPoint 幻灯片、Word 文档和 Excel 电子表格内容
- **实时预览**: 内置 HTML 渲染引擎，可将 .docx/.xlsx/.pptx 文件渲染为 HTML 或 PNG，支持实时预览反馈
- **跨平台二进制**: 提供单一可执行文件，无需安装 Office，支持 macOS、Linux 和 Windows

**技术亮点**: C# 开发，单二进制分发，无依赖，内置 HTML 渲染引擎实现“渲染→查看→修复”闭环，支持通过 curl 或 npm 快速安装

---
## 8. [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)
- **语言**: JavaScript
- **Stars**: 54,244
- **简介**: Extracted system prompts from Anthropic - Claude Fable 5, Opus 4.8, Claude Code, Claude Design. OpenAI - ChatGPT 5.5 Thinking, GPT 5.5 Instant, Codex. Google - Gemini 3.5 Flash, 3.1 Pro, Antigravity. xAI - Grok, Cursor, Copilot, VS Code, Perplexity, and more. Updated regularly.

### AI 总结
**简介**: 该项目持续收集并公开了各大 AI 聊天机器人（如 Claude、ChatGPT、Gemini、Grok 等）的系统提示词（System Prompts），并定期更新。

**核心功能**:
- **系统提示词收集**: 收录了 Anthropic (Claude Fable 5, Opus 4.8等)、OpenAI (GPT-5.5, Codex等)、Google (Gemini 3.5 Flash等)、xAI (Grok) 以及 Copilot、VS Code 等工具的系统提示词。
- **版本对比**: 提供模型间的系统提示词差异对比 (如 Claude Opus 4.8 → Fable 5)。
- **持续更新**: 项目保持活跃，定期更新最新模型的系统提示词。

**技术亮点**: 项目本身基于 JavaScript，主要利用 Markdown 文件组织和管理内容，并支持社区贡献 (PRs Welcome)。

---
## 9. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 249,865
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为编码代理设计的完整软件开发方法论，基于一组可组合的技能和初始指令，让代理能够自动执行规范制定、实现计划、子代理驱动的开发等流程。

**核心功能**:
- 自动引导用户定义需求规格，避免直接跳入编码
- 生成可读性高的实现计划，强调 TDD、YAGNI 和 DRY 原则
- 采用子代理驱动开发模式，自动分解任务、执行并审查工作
- 支持多个主流编码代理平台（Claude Code、Cursor、GitHub Copilot CLI 等）的插件安装

**技术亮点**: 基于 Shell 脚本实现，提供跨平台的插件化安装机制，通过自动触发的技能系统实现无需人工干预的代理工作流。

---
## 10. [alibaba/zvec](https://github.com/alibaba/zvec)
- **语言**: C++
- **Stars**: 14,430
- **简介**: A lightweight, lightning-fast, in-process vector database

### AI 总结
**简介**: Zvec 是一个轻量级、超高速的开源进程内向量数据库，可直接嵌入应用程序，已在阿里巴巴集团内部得到生产验证。

**核心功能**:
- **向量搜索**: 支持稠密向量和稀疏向量，提供从内存到磁盘的多种索引类型，可在毫秒级搜索数十亿向量。
- **全文搜索 (FTS)**: 原生支持基于关键词的全文搜索，可通过自然语言或结构化表达式查询字符串字段。
- **混合搜索**: 在单个查询中融合向量相似性、全文搜索和结构化过滤器，以获得精确结果。
- **持久化存储**: 通过预写日志 (WAL) 保证数据持久性，即使进程崩溃或断电也不会丢失数据。
- **并发访问**: 支持多进程同时读取同一集合，写入为单进程独占。

**技术亮点**:
- **进程内库**: 以库形式运行，无需独立服务器，可部署于笔记本、服务器、CLI 工具或边缘设备。
- **多语言 SDK**: 提供 Python、Node.js、Go、Rust、Dart/Flutter 等多种官方 SDK。
- **v0.5.0 新特性**: 引入 DiskANN 磁盘索引以降低内存占用，新增 Go/Rust SDK 及可视化工具 Zvec Studio，并支持 RISC-V 架构。

---
