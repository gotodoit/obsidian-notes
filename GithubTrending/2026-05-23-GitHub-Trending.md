---
tags:
  - github-trending
  - daily
date: 2026-05-23
created: 2026-05-23T01:55:43.542Z
---

# 2026-05-23 GitHub Trending Top 10

## 1. [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- **语言**: Python
- **Stars**: 25,012
- **简介**: Official, Anthropic-managed directory of high quality Claude Code Plugins.

### AI 总结
**简介**: Anthropic 官方维护的高质量 Claude Code 插件目录，提供精选的插件市场。

**核心功能**:
- 提供官方及第三方插件的集中发现与安装
- 支持通过 `/plugin install` 命令或插件浏览界面安装插件
- 区分内部插件（Anthropic 开发）和外部插件（社区与合作伙伴提交）

**技术亮点**: 基于 MCP（Model Context Protocol）服务器配置，插件结构标准化（含 plugin.json 元数据、MCP 配置、命令/代理/技能模块）

---
## 2. [colbymchenry/codegraph](https://github.com/colbymchenry/codegraph)
- **语言**: TypeScript
- **Stars**: 16,644
- **简介**: Pre-indexed code knowledge graph for Claude Code, Codex, Cursor, OpenCode, and Hermes Agent — fewer tokens, fewer tool calls, 100% local

### AI 总结
**简介**: CodeGraph 是一个为 Claude Code、Cursor 等 AI 编码助手提供预索引代码知识图谱的工具，能显著降低 token 消耗、减少工具调用次数，且完全本地运行。

**核心功能**:
- 为代码库构建符号关系、调用图和代码结构的预索引知识图谱
- 支持 Claude Code、Cursor、Codex CLI、OpenCode、Hermes Agent 等多种 AI 编码助手
- 提供一键安装（无需 Node.js）和项目初始化命令
- 支持一键卸载，自动清除所有已配置代理的集成设置

**技术亮点**:
- 使用 TypeScript 开发，捆绑自运行环境，无需编译或原生构建
- 跨平台支持 Windows、macOS、Linux
- 平均降低 35% 成本、59% token 消耗、49% 响应时间、70% 工具调用次数
- 代码库越大效果越显著，大型仓库可实现零文件读取的即时查询

---
## 3. [ruvnet/RuView](https://github.com/ruvnet/RuView)
- **语言**: Rust
- **Stars**: 64,059
- **简介**: π RuView turns commodity WiFi signals into real-time spatial intelligence, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: RuView 是一个基于 WiFi 信号的空间智能感知平台，无需摄像头即可实现穿墙人体检测、生命体征监测和活动识别。

**核心功能**:
- **穿墙人体存在与占用检测** — 实时感知人员位置、进出统计，无需任何穿戴设备
- **无接触生命体征监测** — 通过 CSI 信号分析呼吸频率（6–30 BPM）和心率（40–120 BPM）
- **活动识别与环境映射** — 识别行走、坐姿、跌倒等动作，并通过 RF 指纹识别房间布局变化
- **睡眠质量分析** — 支持整夜监测，包含睡眠阶段分类和呼吸暂停筛查

**技术亮点**:
- 基于低成本 ESP32-S3 节点（最低 $9/个）和 Cognitum Seed 边缘硬件，完全离线运行
- 使用脉冲神经网络（SNN）实现 30 秒内自适应环境学习，多频段（6 个 WiFi 信道）扫描
- 模型仅 8 KB（4-bit 量化），在树莓派上微秒级推理，验证集上 100% 存在检测准确率
- 所有测量通过 Ed25519 见证链提供加密认证，支持 Docker 多架构部署

---
## 4. [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch)
- **语言**: Python
- **Stars**: 11,982
- **简介**: Learn it. Build it. Ship it for others.

### AI 总结
**简介**: 一个从零开始构建AI工程能力的开源课程，包含435课、20个阶段，覆盖Python/TypeScript/Rust/Julia四门语言，强调数学推导到生产部署的完整闭环。

**核心功能**:
- 提供20个递进式学习阶段（数学基础→ML/DL→视觉/NLP/语音→Transformer→LLM→Agent→多智能体系统→生产部署）
- 每课包含“从零实现”和“生产库使用”双轨模式，先手写算法再对比框架
- 产出可复用的AI工件：提示词、技能、Agent、MCP服务器等
- 支持本地运行，所有代码/文档/输出均按统一文件夹结构组织

**技术亮点**: 线性代数→反向传播→注意力机制→Agent循环的完整知识链，无框架依赖的原生实现，支持Python/TypeScript/Rust/Julia多语言实践。

---
## 5. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)
- **语言**: TypeScript
- **Stars**: 40,988
- **简介**: Chrome DevTools for coding agents

### AI 总结
**简介**: 一个基于 MCP 协议的工具，允许 AI 编码助手（如 Antigravity、Claude 等）控制、检查并调试 Chrome 浏览器，实现自动化、深度调试和性能分析。

**核心功能**:
- **性能洞察**: 使用 Chrome DevTools 记录跟踪并提取可操作的性能建议。
- **高级调试**: 分析网络请求、截图、检查控制台消息（含源码映射堆栈）。
- **可靠自动化**: 通过 Puppeteer 自动执行 Chrome 操作并等待结果。

**技术亮点**:
- 基于 Model-Context-Protocol (MCP) 标准构建，兼容多种 AI 编码客户端。
- 采用 TypeScript 开发，依赖 Puppeteer 和 Chrome DevTools 前端。
- 支持 `--slim` 模式用于轻量级浏览器操作，并提供 CLI 工具。

---
## 6. [dotnet/skills](https://github.com/dotnet/skills)
- **语言**: C#
- **Stars**: 2,542
- **简介**: Repository for skills to assist AI coding agents with .NET and C#

### AI 总结
**简介**: .NET 团队为 AI 编码助手（如 Copilot、Claude Code）精心策划的一系列 .NET 与 C# 核心技能和自定义代理的集合。

**核心功能**:
- 提供覆盖 .NET 开发全流程的插件，包括核心编码、数据访问、调试诊断、构建、包管理、项目升级、MAUI、AI/ML、模板引擎、测试、ASP.NET Core 及 .NET 11 新特性。
- 支持在 Copilot CLI、Claude Code、VS Code、Cursor、Codex CLI 等多种 AI 编码工具中安装和使用。
- 提供仪表盘，用于追踪和展示各插件的准确性与效率评分趋势。

**技术亮点**: 遵循 [agentskills.io](https://agentskills.io) 开放标准，确保跨平台兼容性；以 C# 为主要开发语言，模块化插件架构便于扩展和维护。

---
## 7. [Lum1104/Understand-Anything](https://github.com/Lum1104/Understand-Anything)
- **语言**: TypeScript
- **Stars**: 18,740
- **简介**: Graphs that teach > graphs that impress. Turn any code into an interactive knowledge graph you can explore, search, and ask questions about. Works with Claude Code, Codex, Cursor, Copilot, Gemini CLI, and more.

### AI 总结
**简介**: 将任意代码库、知识库或文档转化为交互式知识图谱，支持探索、搜索和提问，帮助开发者快速理解复杂项目。

**核心功能**:
- **结构图探索**: 以交互式知识图谱展示代码库中的文件、函数、类等节点，支持点击、搜索和查看关系摘要。
- **业务逻辑视图**: 切换到领域视图，将代码映射为水平图展示业务过程、流程和步骤。
- **知识库分析**: 解析Karpathy风格的LLM维基，生成带社区聚类的力导向知识图谱，自动提取隐式关系和实体。
- **引导式导览**: 自动生成架构导览，按依赖顺序逐步讲解代码库。
- **模糊与语义搜索**: 支持按名称或含义搜索，例如“哪些部分处理认证？”。
- **差异影响分析**: 在提交前可视化显示变更对系统的影响范围。

**技术亮点**: 基于TypeScript开发，采用多智能体管道分析项目，支持与Claude Code、Codex、Cursor、Copilot、Gemini CLI等多种AI编码工具集成。

---
## 8. [odoo/odoo](https://github.com/odoo/odoo)
- **语言**: Python
- **Stars**: 51,147
- **简介**: Odoo. Open Source Apps To Grow Your Business.

### AI 总结
**简介**: Odoo 是一套基于 Web 的开源商业应用套件，旨在帮助企业高效运营。

**核心功能**:
- 开源 CRM 客户关系管理
- 网站构建器与电子商务平台
- 仓库、项目与制造管理
- 计费与会计模块
- 销售点系统与人力资源
- 营销自动化工具

**技术亮点**: 采用 Python 开发，所有应用既可独立运行，也能无缝集成，形成完整的企业资源计划系统。

---
## 9. [byJoey/cfnew](https://github.com/byJoey/cfnew)
- **语言**: Unknown
- **Stars**: 13,316
- **简介**: 

### AI 总结
**简介**: CFnew 是一个部署在 Cloudflare Workers/Pages 上的多功能代理管理终端，提供图形化配置、订阅转换、延迟测试等功能，支持多种代理协议和客户端。

**核心功能**:
- 多协议支持：VLESS、Trojan、xhttp，可同时启用
- 图形化管理：通过 KV 存储配置，修改后立即生效，无需重新部署
- 订阅转换：内置 Clash、Surge、Sing-box 等客户端的配置生成，不依赖外部服务
- 延迟测试与优选：自动测速并优选 IP，支持地区筛选和延迟排序
- API 管理：支持通过 API 动态添加/删除优选 IP
- 多客户端兼容：支持 CLASH、SURGE、SING-BOX、LOON 等主流客户端，自动识别 User-Agent 返回对应格式
- 多语言界面：支持中文和波斯语，根据浏览器语言自动切换

**技术亮点**:
- 基于 Cloudflare Workers/Pages 无服务器架构，利用 KV 存储实现配置持久化
- 内置传输优化（参考 GrainTCP 思路），提升 WebSocket/TCP 转发效率
- 支持 ECH（加密客户端问候）和 ALPN 自定义，增强安全性
- 客户端可通过 WebSocket path 参数覆盖连接级变量，实现灵活配置

---
## 10. [trimstray/the-book-of-secret-knowledge](https://github.com/trimstray/the-book-of-secret-knowledge)
- **语言**: Unknown
- **Stars**: 223,226
- **简介**: A collection of inspiring lists, manuals, cheatsheets, blogs, hacks, one-liners, cli/web tools and more.

### AI 总结
**简介**: 一个汇集了各类实用列表、手册、速查表、博客、技巧、命令行/Web工具等资源的宝藏仓库，旨在为系统管理员、运维、渗透测试人员和安全研究员等提供一站式知识库。

**核心功能**:
- **命令行工具 (CLI Tools)**: 收集了包括 Shell、网络、系统管理等在内的各种命令行工具和技巧。
- **GUI & Web 工具**: 整理了图形界面工具和在线 Web 服务，方便日常操作。
- **系统/网络/容器**: 涵盖了系统服务、网络配置、容器编排等领域的深入资料。
- **手册/教程/博客**: 提供了丰富的技术手册、实操教程和优质博客/播客/视频资源。
- **渗透测试与安全**: 汇集了黑客技术、渗透测试方法和安全研究相关的资源。
- **速查表与 Shell 技巧**: 包含各种技术速查表、实用 Shell 单行命令和函数。

**技术亮点**: 项目采用 Markdown + HTML 编写，结构清晰，易于贡献和维护；通过目录 (TOC) 实现快速导航；接受 Pull Request 和财务赞助，社区活跃。

---
