---
tags:
  - github-trending
  - daily
date: 2026-08-13
created: 2026-08-13T01:55:44.256Z
---

# 2026-08-13 GitHub Trending Top 10

## 1. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 10,654
- **简介**: 29 editorial diagram types for Claude Code. Self-contained HTML + SVG. No shadows, no Mermaid-slop.

### AI 总结
**简介**: 一个为 Claude Code 等 AI 编程助手设计的图表生成技能，提供 27 种编辑级质量的 HTML+SVG 图表类型，无需 Figma 或 Mermaid 即可生成设计师认可的专业图表。

**核心功能**:
- **27 种视觉图表类型**: 涵盖架构图、流程图、时序图、状态机、ER 图、时间线、泳道图、象限图、树形图、组织架构图、维恩图、金字塔图、雷达图、循环图等
- **三种静态变体**: 每种图表类型均提供极简浅色、极简深色和完整编辑风格三种版本，可直接在浏览器打开
- **品牌匹配**: 通过读取网站内容，60 秒内自动匹配品牌风格
- **语义化模式**: 将行为与布局分离描述，队列、策略追踪、信任边界等场景可复用现有图表类型
- **格式转换**: 支持将 draw.io 或 Mermaid 源文件重绘为指定格式、尺寸和细节级别
- **可选动效**: 支持有序讲解的动效模式，默认保持静态输出

**技术亮点**: 纯 HTML + SVG 实现，无构建步骤、无 JavaScript 依赖、无外部图片依赖；采用语义化系统模式设计，扩展新图表类型无需增加类型数量；强调编辑级设计质量（无阴影、无通用圆角框）。

---
## 2. [macro-inc/macro](https://github.com/macro-inc/macro)
- **语言**: Rust
- **Stars**: 1,869
- **简介**: Macro is a unified workspace for teams: email, chat, docs, tasks, agents, calls, and CRM — @-linked together with shared AI memory.

### AI 总结
**简介**: Macro 是一个为团队打造的一体化工作空间，将邮件、聊天、文档、任务、AI 代理、通话和 CRM 统一到一个基于共享 AI 记忆的快速界面中，所有内容通过 @ 链接实现互联互通。

**核心功能**:
- **统一收件箱**: 支持多账户 Gmail 聚合，采用键盘优先设计，将邮件、消息、@提及和任务整合到同一列表，方便快速处理。
- **团队沟通与协作**: 提供频道和私信功能，专为技术讨论设计；实时协同文档基于 CRDT 构建，支持 Markdown 和 @提及。
- **任务与项目管理**: 类 Linear 的任务系统，与频道、邮件和 AI 代理深度集成。
- **AI 代理与团队记忆**: 具备统一的团队级记忆，代理可代表用户执行操作，并能跨收件箱检索信息（如直接从邮件附件中解析 PDF 内容）。
- **CRM 与客户管理**: 支持客户/联系人对象、自定义属性、邮件同步和数据丰富。
- **扩展功能块**: 包含 2D 画布（嵌入 @链接）、通话录制与转录、文件自动归档（从邮件/频道导入）、GitHub PR 集成等功能模块，所有模块共享同一后端，交叉引用以双向图结构原生存储。

**技术亮点**: 使用 Rust 和 SolidJS 构建，强调速度与可靠性；所有功能块基于模块化、可扩展的架构设计，共享统一后端，支持双向图数据模型；内置 AI 工具/MCP 接口，为代理提供精准的信息检索与操作能力。

---
## 3. [semantica-agi/semantica](https://github.com/semantica-agi/semantica)
- **语言**: Python
- **Stars**: 5,756
- **简介**: Graph-Native Infrastructure for Context and Accountable AI Systems

### AI 总结
**简介**: Semantica 是一个开源的图原生基础设施平台，旨在为 AI 代理提供可解释、可审计的上下文管理和决策智能能力，被称为“AI 代理的开源 Palantir”。

**核心功能**:
- **上下文图与知识图谱构建**: 从企业原始数据中自动提取关键信息，构建上下文图（Context Graph）和知识图谱（KG），无需依赖 LLM 即可完成图构建
- **因果推理与图分析**: 支持在图结构上运行图分析和因果推理，为高风险的业务决策（如信贷审批）提供确定性推理能力
- **完整决策溯源**: 内置端到端的决策溯源机制，确保每个 AI 决策都可解释、可追踪、可审计，满足监管合规要求
- **本体论管理**: 提供本体建模和知识建模工具，支持企业级知识体系的标准化管理
- **多语言图存储兼容**: 支持 RDF 和 LPG 两种图数据模型，兼容 W3C 标准，可与 Databricks Unity Catalog 和 Snowflake 等数据平台无缝集成

**技术亮点**: 采用 Python 构建，支持 Python 3.8+，使用 Polyglot Graph Storage 架构实现多图数据库兼容；作为确定性基础设施层，可独立于 LLM 运行，避免对向量数据库的单一依赖；完全开源、可自托管、可审计，无供应商锁定，特别适合金融、医疗等强监管行业场景。

---
## 4. [stablyai/orca](https://github.com/stablyai/orca)
- **语言**: TypeScript
- **Stars**: 43,940
- **简介**: Orca is the ADE for working with a fleet of parallel agents. Run any coding agent with your own subscription. Available on desktop, mobile and VPS.

### AI 总结
**简介**: Orca 是一个面向 AI 开发者的桌面端编排工具（ADE），可同时运行多个编码代理（如 Codex、ClaudeCode、OpenCode 等），支持桌面、移动端和 VPS 部署，让开发者以自有订阅并行管理多个 AI 代理。

**核心功能**:
- **并行工作树（Parallel Worktrees）**: 将一个提示词同时分发给多个代理，每个代理在独立的 git 工作树中运行，可对比结果并合并最优方案
- **移动端伴侣应用**: 支持 iOS/Android，可远程监控代理运行状态，接收完成通知并随时随地发送后续指令
- **终端分屏**: 基于 Ghostty 的 WebGL 渲染终端，支持无限分屏和重启后保留滚动历史
- **设计模式（Design Mode）**: 在真实 Chromium 窗口中点击任意 UI 元素，自动将其 HTML、CSS 和截图注入代理提示词
- **原生 GitHub & Linear 集成**: 应用内浏览 PR、Issue 和项目看板，可从任意任务直接创建工作树，无需切换上下文
- **SSH 工作树**: 支持在远程高性能服务器上运行代理，包含完整文件编辑、git 和终端功能，支持自动重连和端口转发

**技术亮点**: 基于 TypeScript 构建，采用 WebGL 渲染终端，支持跨平台（macOS/Windows/Linux），配备嵌入式 Chromium 浏览器，通过原生集成实现 GitHub/Linear 工作流无缝衔接，并支持移动端远程操控。

---
## 5. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 144,601
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个集合了多种专业AI代理（Agent）的“代理机构”，每个代理都有独特的个性、专长和可交付成果，可直接集成到主流AI编程工具中。

**核心功能**:
- **丰富的代理角色库**: 涵盖前端开发、UI设计、Reddit运营、创意注入、现实检查等各类专业AI代理，每个代理都有明确的身份、工作流程和交付物定义。
- **多工具集成**: 支持一键安装到Claude Code、Cursor、Codex、Gemini CLI、OpenCode、Copilot、Aider、Windsurf等十余种主流AI编程工具。
- **灵活的选择性安装**: 支持按工具、按团队（division）或按具体代理（agent）进行选择性安装，避免安装不需要的代理，并可预览安装内容（dry-run）。
- **原生桌面应用**: 提供macOS、Linux和Windows原生应用（Agency Agents），无需命令行，通过图形界面浏览和安装代理，并支持自动更新。
- **交互式安装向导**: 提供脚本化安装方式，可自动检测已安装的工具，并支持交互式选择要安装的工具和团队。

**技术亮点**: 基于Shell脚本实现跨工具代理格式转换和安装；代理文件采用Markdown格式，内容结构化（包含身份、使命、技术交付物、成功指标等）；提供`convert.sh`和`install.sh`脚本，支持`--tool`、`--division`、`--agent`、`--dry-run`等参数，并针对OpenCode的代理数量限制提供了安装警告。

---
## 6. [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos)
- **语言**: Python
- **Stars**: 36,948
- **简介**: Kronos: A Foundation Model for the Language of Financial Markets

### AI 总结
**简介**: Kronos 是首个开源金融K线（OHLCV）基础模型，基于45+全球交易所数据训练，专为金融市场语言设计。

**核心功能**:
- 多尺度K线预测：支持BTC/USDT等交易对的未来走势预测（提供实时在线Demo）
- 层次化离散分词：将连续K线数据转换为分层离散token，适配自回归Transformer
- 多模型规模选择：提供mini（4.1M）、small（24.7M）、base（102.3M）三个开源版本，满足不同计算需求
- 微调支持：已发布微调脚本，可适配用户自定义任务
- 统一量化任务：作为通用模型支撑多样化的金融定量任务

**技术亮点**:
- 基于decoder-only Transformer架构，采用两阶段框架：专用分词器（Kronos-Tokenizer） + 自回归预训练
- 针对金融数据高噪声特性设计，区别于通用时间序列基础模型（TSFM）
- 模型权重托管于Hugging Face，论文已发表于arXiv并被AAAI 2026接收

---
## 7. [NanmiCoder/MediaCrawler](https://github.com/NanmiCoder/MediaCrawler)
- **语言**: Python
- **Stars**: 62,000
- **简介**: 小红书笔记 | 评论爬虫、抖音视频 | 评论爬虫、快手视频 | 评论爬虫、B 站视频 ｜ 评论爬虫、微博帖子 ｜ 评论爬虫、百度贴吧帖子 ｜ 百度贴吧评论回复爬虫 | 知乎问答文章｜评论爬虫

### AI 总结
**简介**: MediaCrawler 是一个基于 Playwright 的多平台自媒体数据采集工具，支持小红书、抖音、快手、B站、微博、贴吧、知乎等主流平台的公开信息抓取。

**核心功能**:
- 支持关键词搜索、指定帖子 ID 爬取、二级评论、指定创作者主页爬取
- 支持登录态缓存、IP 代理池、生成评论词云图
- 覆盖小红书、抖音、快手、B 站、微博、贴吧、知乎七大平台
- 提供 MediaCrawlerPro 付费版本，支持断点续爬、多账号管理、去除 Playwright 依赖等进阶功能

**技术亮点**:
- 基于 Playwright 浏览器自动化框架，无需 JS 逆向即可获取签名参数
- 通过保留登录态的浏览器上下文环境，利用 JS 表达式获取数据
- 默认使用 CDP 模式连接已有 Chrome 浏览器，复用登录状态和 Cookie，降低风控检测风险
- 使用 uv 作为 Python 包管理工具，保证依赖一致性

---
## 8. [hugohe3/ppt-master](https://github.com/hugohe3/ppt-master)
- **语言**: Python
- **Stars**: 45,641
- **简介**: AI turns documents or topics into real, native PowerPoint decks—with native shapes, transitions and animations, data-backed charts and tables on demand, audio narration from speaker notes, and support for your own .pptx templates. · by Hugo He

### AI 总结
**简介**: PPT Master 是一个利用 AI 将文档或主题自动生成原生 PowerPoint 演示文稿的开源工具，支持原生形状、过渡动画、数据图表、音频旁白及自定义模板。

**核心功能**:
- 从 PDF、DOCX、网页等文档或主题自动生成可编辑的 PPTX 文件
- 生成原生 PowerPoint 形状、过渡效果和动画，非图片式输出
- 按需创建数据驱动的图表和表格
- 从演讲者备注自动生成音频旁白
- 支持用户自定义 .pptx 模板，保持品牌一致性
- 支持多种主流 AI 模型（通过 Kimi、Claude、OpenAI、Gemini 等 API 接入）

**技术亮点**: 基于 Python 实现，采用 AI 驱动的文档理解与结构化叙事生成流程，支持多模态输入（文本、图片、网页），兼容多种 LLM API 提供商，提供免费开源（MIT 许可证）且拥有活跃的社区支持。

---
## 9. [infiniflow/ragflow](https://github.com/infiniflow/ragflow)
- **语言**: Go
- **Stars**: 87,572
- **简介**: RAGFlow is a leading open-source Retrieval-Augmented Generation (RAG) engine that fuses cutting-edge RAG with Agent capabilities to create a superior context layer for LLMs

### AI 总结
**简介**: RAGFlow 是一个领先的开源检索增强生成（RAG）引擎，融合前沿 RAG 与 Agent 能力，为 LLM 构建高质量上下文层，支持企业级 RAG 工作流。

**核心功能**:
- 提供深度文档理解与精准的上下文检索，将复杂数据转化为高保真、可投入生产的 AI 系统
- 内置预构建的 Agent 模板，支持快速搭建基于 Agent 的智能应用
- 提供全流程 RAG 工作流，可适配不同规模企业的需求
- 支持云端服务（cloud.ragflow.io）与自托管部署（Docker/源码），灵活适配不同使用场景

**技术亮点**: 采用 Go 语言开发，基于“上下文引擎”架构设计，支持多语言文档（README 提供 12 种语言版本），拥有活跃的社区生态（Discord、Twitter），遵循 Apache-2.0 开源协议，提供完善的文档与路线图。

---
## 10. [paperclipai/paperclip](https://github.com/paperclipai/paperclip)
- **语言**: TypeScript
- **Stars**: 77,756
- **简介**: The open-source app everyone uses to manage agents at work

### AI 总结
**简介**: Paperclip 是一个开源的 AI 智能体编排平台，用于管理工作场景中的多智能体团队，将 AI 智能体视为“员工”，帮助用户像管理公司一样管理它们。

**核心功能**:
- **智能体任务管理**: 声明目标，智能体自动执行任务，用户审核输出结果，支持任务审批与审查关卡
- **组织架构管理**: 支持“雇佣”多个 AI 智能体（如 CEO、CTO、工程师等），构建虚拟团队并分配角色
- **目标对齐与治理**: 将业务目标分解为可执行任务，内置预算控制、成本监控与治理策略
- **多智能体协调**: 支持 OpenClaw、Claude Code、Codex、Cursor、Bash、HTTP 等多种智能体/工具接入，统一协调工作
- **实时监控仪表盘**: 从单一面板跟踪所有智能体的工作进度、成本和状态，支持移动端管理

**技术亮点**: 基于 Node.js 后端 + React 前端构建，采用 TypeScript 开发，通过“心跳”机制与各类智能体集成，实现跨平台的智能体编排与自动化管理。

---
