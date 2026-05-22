---
tags:
  - github-trending
  - daily
date: 2026-05-22
created: 2026-05-22T01:55:44.242Z
---

# 2026-05-22 GitHub Trending Top 10

## 1. [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- **语言**: Python
- **Stars**: 22,566
- **简介**: Official, Anthropic-managed directory of high quality Claude Code Plugins.

### AI 总结
**简介**: 由 Anthropic 官方维护的高质量 Claude Code 插件目录，提供内部与第三方插件的发现与安装功能。  
**核心功能**:  
- 通过 `/plugin install {插件名}@claude-plugins-official` 命令直接安装插件  
- 支持在 `/plugin > Discover` 界面浏览和发现插件  
- 插件包含标准结构（元数据、MCP 服务器配置、命令、代理、技能等）  
**技术亮点**: 采用 Python 实现，插件目录分为内部（`/plugins`）和外部（`/external_plugins`）两部分，第三方插件需通过质量与安全审核后提交。

---
## 2. [colbymchenry/codegraph](https://github.com/colbymchenry/codegraph)
- **语言**: TypeScript
- **Stars**: 13,690
- **简介**: Pre-indexed code knowledge graph for Claude Code, Codex, Cursor, and OpenCode — fewer tokens, fewer tool calls, 100% local

### AI 总结
**简介**: CodeGraph 是一个为 Claude Code、Cursor、Codex、OpenCode 等 AI 编程助手提供预索引代码知识图的工具，可大幅减少 token 消耗和工具调用，实现 100% 本地化运行。

**核心功能**:
- 为 AI 编程助手提供预索引的代码知识图，包含符号关系、调用图和代码结构
- 支持 Claude Code、Cursor、Codex CLI、OpenCode、Hermes Agent 等多种 AI 编程工具
- 一键安装，无需 Node.js 环境，跨平台支持 Windows/macOS/Linux
- 通过 `codegraph init -i` 交互式初始化项目并自动配置 AI 助手

**技术亮点**:
- 使用 TypeScript 开发，自带运行时，无需编译和原生构建
- 平均可降低 35% 成本、减少 59% token 消耗、提升 49% 速度、减少 70% 工具调用
- 代码库越大效果越显著，大型项目中可实现零文件读取查询

---
## 3. [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills)
- **语言**: Unknown
- **Stars**: 143,301
- **简介**: A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.

### AI 总结
**简介**: 一个基于 Andrej Karpathy 对 LLM 编码缺陷的观察，通过单一 `CLAUDE.md` 文件改进 Claude Code 行为规范的项目。

**核心功能**:
- **先思考再编码**: 强制要求显式陈述假设、呈现多种解释、适时提出质疑，并在困惑时停止追问。
- **简洁优先**: 反对过度工程化，仅实现必要功能，避免冗余抽象和不必要的灵活性。
- **外科手术式修改**: 仅修改与任务直接相关的代码，不触碰或“改善”无关代码、注释或格式。
- **目标驱动执行**: 将任务转化为可验证的成功标准，并循环执行直至达成目标。

**技术亮点**: 通过单一配置文件（CLAUDE.md）即可集成到 Claude Code 或 Cursor 中，提供即插即用的编码行为规范。

---
## 4. [dotnet/skills](https://github.com/dotnet/skills)
- **语言**: C#
- **Stars**: 2,216
- **简介**: Repository for skills to assist AI coding agents with .NET and C#

### AI 总结
**简介**: dotnet/skills 是 .NET 团队为 AI 编码助手（如 Copilot CLI、Claude Code）提供的一套核心技能和自定义代理的仓库，遵循 Agent Skills 开放标准。

**核心功能**:
- **.NET 编码技能**: 提供处理常见 .NET 编码任务的技能集，包括核心开发、数据访问、诊断、构建、包管理、升级、MAUI、AI/ML、模板引擎、测试、ASP.NET Core 以及 .NET 11 新特性。
- **多平台集成**: 支持在 Copilot CLI / Claude Code、VS Code、Cursor 和 Codex CLI 等多种开发工具中安装和使用这些技能。
- **技能发现与管理**: 提供 `/skills`、`/agents` 等命令查看可用技能，并支持通过 marketplace 或本地路径安装、更新插件。

**技术亮点**: 基于 Agent Skills 开放标准 (agentskills.io)；提供准确性和效率评分仪表盘 (GitHub Pages)；支持多种 AI 编码工具和 IDE 的无缝集成。

---
## 5. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 201,579
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套为编码代理设计的完整软件开发方法论，基于可组合技能和初始指令构建，让代理能自动遵循最佳实践。

**核心功能**:
- **设计优先**: 代理在写代码前先通过对话梳理需求，生成可读的设计文档
- **规划驱动**: 将设计分解为 2-5 分钟的工程任务，每项任务包含文件路径、完整代码和验证步骤
- **子代理驱动开发**: 代理自动执行各工程任务，并检查、审查工作成果，可持续自主工作数小时
- **多平台支持**: 支持 Claude Code、Codex CLI、Cursor 等主流编码代理平台
- **自动触发**: 技能自动激活，无需手动干预

**技术亮点**: 基于 Shell 脚本实现，采用可组合技能架构；强调 TDD、YAGNI、DRY 原则；使用 Git Worktree 创建隔离工作区；通过插件市场分发。

---
## 6. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 39,155
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: CLI-Anything 是一个开源工具，通过为任意软件生成命令行接口，使 AI 代理能像人类一样操作软件，实现“所有软件原生支持代理”。

**核心功能**:
- **一键生成 CLI**: 为任何软件（如 CAD、3D 编辑、办公套件等）创建标准化命令行接口，兼容 Pi、OpenClaw、Cursor、Claude Code 等主流 AI 代理框架。
- **CLI-Hub 生态**: 提供社区驱动的命令行包管理器（`pip install cli-anything-hub`），可浏览、安装和管理社区贡献的 CLI 打包，支持一键贡献和愿望单提交。
- **丰富的演示与应用**: 支持 18 款以上软件（如 Rekordbox、Calibre、3MF、MiniMax、Zoom、Obsidian、LibreOffice 等），展示 AI 代理通过生成的 CLI 完成 CAD 建模、3D 场景、图表、游戏操作等实际任务。

**技术亮点**: 基于 Python 开发，依赖 Click 框架（≥8.0）；采用 JSON + 人类可读双输出格式；通过 pytest 实现 100% 单元测试和端到端测试覆盖；集成 `defusedxml` 等安全解析库处理不可信输入；架构支持动态注册和即时更新。

---
## 7. [rmyndharis/OpenWA](https://github.com/rmyndharis/OpenWA)
- **语言**: TypeScript
- **Stars**: 5,440
- **简介**: Free, Open Source, Self-Hosted WhatsApp API Gateway

### AI 总结
**简介**: OpenWA 是一个免费、开源、可自托管的 WhatsApp API 网关，旨在为开发者提供对消息基础设施的完全控制，避免供应商锁定和隐藏费用。

**核心功能**:
- 多会话管理：支持在同一实例上并发运行多个 WhatsApp 会话
- 全面消息能力：支持文本、媒体、消息反应、批量发送及状态追踪
- 丰富管理界面：提供现代化 React Web 仪表盘，用于管理会话、Webhook 和 API 密钥
- 安全认证：支持 API 密钥认证、HMAC 签名 Webhook、CIDR 白名单和审计日志
- 高级功能：包括群组 API、频道/新闻通讯、标签管理、代理和速率限制

**技术亮点**:
- 基于可插拔架构，支持无缝切换数据库（SQLite/PostgreSQL）、存储（本地/S3）和缓存（内存/Redis），无需修改代码
- 使用 TypeScript 和 NestJS 框架，提供 Docker 原生部署和 n8n 集成
- 包含交互式 Swagger API 文档和健康检查端点，适用于 Kubernetes 生产环境

---
## 8. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)
- **语言**: TypeScript
- **Stars**: 40,511
- **简介**: Chrome DevTools for coding agents

### AI 总结
**简介**: 一个基于 MCP 协议的 Chrome DevTools 服务器，让 AI 编程助手能够控制和检查实时 Chrome 浏览器，实现自动化、调试和性能分析。

**核心功能**:
- **性能洞察**: 利用 Chrome DevTools 录制性能轨迹并提取可操作的性能建议。
- **高级浏览器调试**: 分析网络请求、截图、检查控制台消息（含源码映射堆栈跟踪）。
- **可靠自动化**: 通过 Puppeteer 自动执行 Chrome 操作并等待结果。

**技术亮点**:
- 基于 TypeScript 开发，采用 MCP（Model-Context-Protocol）协议。
- 集成 Chrome DevTools 和 Puppeteer 进行深度浏览器控制。
- 支持 slim 模式（仅基础浏览器任务）和 headless 模式。

---
## 9. [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch)
- **语言**: Python
- **Stars**: 10,776
- **简介**: Learn it. Build it. Ship it for others.

### AI 总结
**简介**: 一个从零开始系统学习AI工程的免费开源课程，涵盖数学基础到生产部署的完整知识体系。

**核心功能**:
- 提供435节课程、20个阶段、约320小时的学习内容，覆盖Python/TypeScript/Rust/Julia四种语言
- 每节课遵循“问题→概念→从零构建→使用框架→产出”的六步闭环，确保理解底层原理
- 产出可复用的AI制品：提示词、技能、智能体、MCP服务器等
- 支持跳过已掌握阶段，但强调底层知识对上层实践的重要性

**技术亮点**: 采用“先手写数学实现，再使用生产级框架”的教学策略，课程结构从线性代数、反向传播、注意力机制等底层原理逐步递进到自主智能体集群和基础设施部署。

---
## 10. [teng-lin/notebooklm-py](https://github.com/teng-lin/notebooklm-py)
- **语言**: Python
- **Stars**: 14,395
- **简介**: Unofficial Python API and agentic skill for Google NotebookLM. Full programmatic access to NotebookLM's features—including capabilities the web UI doesn't expose—via Python, CLI, and AI agents like Claude Code, Codex, and OpenClaw.

### AI 总结
**简介**: notebooklm-py 是一个非官方的 Google NotebookLM Python API 和 AI 代理工具，提供对 NotebookLM 全部功能的编程访问，包括 Web UI 未公开的能力。

**核心功能**:
- **Python API、CLI 和 AI 代理集成**：支持通过 Python、命令行以及 Claude Code、Codex 等 AI 代理以编程方式操控 NotebookLM。
- **完整的 NotebookLM 功能覆盖**：可创建、管理笔记本，导入多种来源（URL、PDF、YouTube、Google Drive 等），进行聊天、研究和分享。
- **多种内容生成**：支持生成音频概述（播客）、视频概述、幻灯片、信息图、测验、抽认卡、报告、数据表和思维导图，并可下载为多种格式（MP3、MP4、PDF、PNG、CSV、JSON、Markdown 等）。
- **超越 Web UI 的功能**：提供批量下载、测验/抽认卡多种格式导出、思维导图 JSON 数据提取以及幻灯片 PPTX 导出等 Web 界面不支持的操作。

**技术亮点**: 基于 Python 开发，利用未公开的 Google API 实现全面功能；提供 CLI 和 AI 代理集成接口，支持异步工作流和自定义研究管道。

---
