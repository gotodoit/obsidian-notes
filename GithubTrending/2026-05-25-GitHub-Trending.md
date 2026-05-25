---
tags:
  - github-trending
  - daily
date: 2026-05-25
created: 2026-05-25T01:55:43.552Z
---

# 2026-05-25 GitHub Trending Top 10

## 1. [Lum1104/Understand-Anything](https://github.com/Lum1104/Understand-Anything)
- **语言**: TypeScript
- **Stars**: 26,222
- **简介**: Graphs that teach > graphs that impress. Turn any code into an interactive knowledge graph you can explore, search, and ask questions about. Works with Claude Code, Codex, Cursor, Copilot, Gemini CLI, and more.

### AI 总结
**简介**: 一个将任意代码库、知识库或文档转化为交互式知识图谱的工具，支持可视化探索、搜索和提问。

**核心功能**:
- **结构图探索**: 将代码库渲染为交互式知识图谱，每个文件、函数和类都是可点击的节点，支持查看摘要、关系及引导式导览
- **业务逻辑理解**: 切换到领域视图，以水平图形式展示代码映射到的实际业务流程、领域和步骤
- **知识库分析**: 解析 Karpathy 模式的 LLM 维基，生成带有社区聚类的力导向知识图谱，自动发现隐含关系
- **引导式导览**: 自动生成按依赖排序的架构导览，帮助按正确顺序学习代码库
- **模糊与语义搜索**: 支持按名称或含义搜索，例如“哪些部分处理身份验证？”
- **差异影响分析**: 在提交前可视化变更对系统的影响范围

**技术亮点**: 基于 TypeScript 开发，采用多智能体流水线分析项目，构建包含文件、函数、类和依赖的知识图谱，兼容 Claude Code、Codex、Cursor、Copilot、Gemini CLI 等多种 AI 编码工具。

---
## 2. [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch)
- **语言**: Python
- **Stars**: 16,166
- **简介**: Learn it. Build it. Ship it for others.

### AI 总结
**简介**: 这是一个从零开始系统学习 AI 工程的免费开源课程，包含 435 节课、20 个阶段，覆盖 Python、TypeScript、Rust、Julia 四种语言，强调从数学推导到代码实现的全链路学习。

**核心功能**:
- 分阶段课程体系：从数学基础、机器学习、深度学习，到 Transformer、LLM、Agent 和自主系统，共 20 个递进阶段
- 每节课遵循“问题→概念→手写实现→使用框架→产出可复用成果”的六步学习循环
- 产出实际可用的 AI 构件：提示词、技能、Agent、MCP 服务器等
- 支持四种编程语言（Python、TypeScript、Rust、Julia），可在本地运行

**技术亮点**: 采用“先手写数学实现，再使用生产框架”的独特教学法，确保学习者深入理解底层原理；课程结构清晰，每个阶段都产出可复用的工程制品。

---
## 3. [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- **语言**: Python
- **Stars**: 27,277
- **简介**: Official, Anthropic-managed directory of high quality Claude Code Plugins.

### AI 总结
**简介**: Anthropic 官方维护的 Claude Code 高质量插件目录，提供内部和第三方插件的安装与管理。  
**核心功能**:  
- 通过 `/plugin install {插件名}@claude-plugins-official` 命令或 `/plugin > Discover` 浏览安装插件  
- 支持内部插件（Anthropic 开发）和外部插件（社区提交，需审核）  
- 插件遵循标准结构（包含 plugin.json、MCP 配置、命令、代理、技能等模块）  
**技术亮点**: 基于 MCP 服务器架构，提供标准化的插件目录结构，集成 Claude Code 插件系统，强调安全信任机制。

---
## 4. [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)
- **语言**: Python
- **Stars**: 14,096
- **简介**: Open source repository of plugins primarily intended for knowledge workers to use in Claude Cowork

### AI 总结
**简介**: 这是一个开源插件仓库，旨在将 Claude 转变为特定角色（如销售、客服、产品经理等）的专家，提升知识工作者的工作效率。

**核心功能**:
- **11 个预置角色插件**: 提供针对销售、客服、产品管理、市场营销、法律、财务、数据、生物研究等不同职位的开箱即用插件。
- **自定义工作流与技能**: 每个插件包含领域知识（Skills）、显式命令（Commands）和外部工具连接（Connectors），可深度定制以适应团队和公司的特定流程。
- **即用型 Slash 命令**: 提供如 `/sales:call-prep`、`/data:write-query` 等快捷命令，快速触发复杂工作流。
- **多平台兼容**: 同时支持 Claude Cowork 和 Claude Code。

**技术亮点**: 采用标准化的插件结构（`manifest.json`、`.mcp.json`、`commands/`、`skills/`），通过 MCP（Model Context Protocol）服务器连接外部工具（如 Slack、Jira、HubSpot、Snowflake 等），实现文件化、模块化的插件管理。

---
## 5. [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills)
- **语言**: Unknown
- **Stars**: 152,237
- **简介**: A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.

### AI 总结
**简介**: 该项目提供了一个 `CLAUDE.md` 文件，基于 Andrej Karpathy 对 LLM 编码陷阱的观察，用于改善 Claude Code 的行为。

**核心功能**:
- **Think Before Coding**: 强制显式推理，明确假设、呈现多种解释，并在必要时提出质疑。
- **Simplicity First**: 避免过度工程化，只实现解决问题所需的最小代码，拒绝不必要的抽象和灵活性。
- **Surgical Changes**: 精准修改，只改动与任务直接相关的代码，不“顺手”修改无关内容。
- **Goal-Driven Execution**: 将任务转化为可验证的目标（如“先写测试，再让测试通过”），让 LLM 自主迭代直至成功。

**技术亮点**: 通过单个 `CLAUDE.md` 文件或 Claude Code 插件集成，可跨项目使用，并支持 Cursor 等编辑器。

---
## 6. [earendil-works/pi](https://github.com/earendil-works/pi)
- **语言**: TypeScript
- **Stars**: 53,975
- **简介**: AI agent toolkit: coding agent CLI, unified LLM API, TUI & web UI libraries, Slack bot, vLLM pods

### AI 总结
**简介**: Pi 是一个面向 AI 智能体的工具包，包含可扩展的编码智能体 CLI、统一的 LLM API、终端 UI 库和 Slack 机器人等组件。

**核心功能**:
- **交互式编码智能体 CLI**：提供可扩展的命令行编码助手，支持工具调用和状态管理
- **统一多提供商 LLM API**：聚合 OpenAI、Anthropic、Google 等多种大语言模型接口
- **终端 UI 库**：基于差分渲染的 TUI 组件库
- **会话共享与协作**：支持将开源编码会话发布到 Hugging Face，帮助改进编码智能体

**技术亮点**:
- TypeScript 全栈开发，采用 monorepo 架构管理多包
- 供应链安全强化：依赖精确锁定版本、锁文件验证、生命周期脚本白名单、CI 审计
- 支持从源码运行和本地发布测试，兼容 npm 和 Bun 包管理器

---
## 7. [Alishahryar1/free-claude-code](https://github.com/Alishahryar1/free-claude-code)
- **语言**: Python
- **Stars**: 29,193
- **简介**: Use claude-code for free in the terminal, VSCode extension or discord like OpenClaw (voice supported)

### AI 总结
**简介**: Free Claude Code 是一个开源代理工具，允许用户通过自定义 Anthropic 兼容的代理，免费在终端、VSCode 扩展或 Discord 中使用 Claude Code 功能，支持多种免费、付费或本地模型。

**核心功能**:
- **多客户端支持**: 支持 Claude Code CLI、VSCode 扩展、JetBrains ACP 以及 Discord/Telegram 机器人远程编码会话。
- **17种后端提供商**: 包括 NVIDIA NIM、OpenRouter、Google AI Studio (Gemini)、DeepSeek、Mistral、Ollama、LM Studio 等，灵活选择模型。
- **按模型路由**: 可将不同模型（如 Opus、Sonnet、Haiku）和回退流量发送到不同提供商。
- **流式处理与工具使用**: 支持流式传输、工具调用、推理/思考块处理及本地请求优化。
- **本地管理 UI**: 提供 `/admin` 界面，用于编辑代理设置、验证更改和检查提供商状态（仅本地访问）。
- **可选集成**: 支持语音笔记转录（Whisper 或 NVIDIA NIM）及 VSCode 扩展使用。

**技术亮点**: 基于 Python 3.14 开发，使用 `uv` 包管理器、`Pytest` 测试、`Ruff` 代码格式化、`Loguru` 日志记录，并通过 `Ty` 进行类型检查。架构上作为 Anthropic Messages API 的即插即用代理，保持 Claude Code 客户端协议稳定。

---
## 8. [colbymchenry/codegraph](https://github.com/colbymchenry/codegraph)
- **语言**: TypeScript
- **Stars**: 22,205
- **简介**: Pre-indexed code knowledge graph for Claude Code, Codex, Cursor, OpenCode, and Hermes Agent — fewer tokens, fewer tool calls, 100% local

### AI 总结
**简介**: CodeGraph 是一个为 Claude Code、Cursor、Codex、OpenCode 和 Hermes Agent 等 AI 编程助手提供预索引代码知识图谱的工具，可显著降低 Token 消耗、工具调用次数，且完全本地运行。

**核心功能**:
- **预索引代码知识图谱**：为 AI 代理提供符号关系、调用图和代码结构，实现即时查询，无需扫描文件。
- **显著提升效率**：平均降低 35% 成本、57% Token、46% 耗时和 71% 工具调用次数（基于 7 个真实开源项目基准测试）。
- **一键安装与配置**：无需 Node.js 环境，单命令即可安装并自动配置支持的 AI 代理。
- **项目初始化与卸载**：通过 `codegraph init -i` 初始化项目，`codegraph uninstall` 一键移除所有代理配置。

**技术亮点**:
- 使用 TypeScript 开发，自带运行时，无需编译，跨平台一致运行。
- 支持 Windows、macOS、Linux 全平台。
- 采用 MCP 服务器架构，与主流 AI 编程代理无缝集成。

---
## 9. [multica-ai/multica](https://github.com/multica-ai/multica)
- **语言**: TypeScript
- **Stars**: 32,534
- **简介**: The open-source managed agents platform. Turn coding agents into real teammates — assign tasks, track progress, compound skills.

### AI 总结
**简介**: Multica 是一个开源托管智能体平台，旨在将编码智能体转化为真正的队友，可分配任务、跟踪进度并积累技能。

**核心功能**:
- **智能体即队友**: 像给同事分配任务一样将问题分配给智能体，它们能自主编写代码、报告阻塞并更新状态。
- **小队（Squads）**: 将智能体（和人类）分组到领导智能体下，领导决定任务分配，保持团队扩展时的路由稳定。
- **自主执行**: 支持完整的任务生命周期管理（入队、认领、开始、完成/失败），通过 WebSocket 实时流式传输进度。
- **自动驾驶（Autopilots）**: 为智能体安排定期工作，支持 Cron 触发器、Webhooks 或手动运行，自动创建问题并路由给智能体。
- **可复用技能**: 每次解决方案都成为团队的可复用技能，如部署、迁移、代码审查等。
- **统一运行时**: 一个仪表盘管理所有计算资源，支持本地守护进程和云运行时，自动检测可用 CLI 并实时监控。
- **多工作区**: 通过工作区级隔离组织跨团队工作，每个工作区拥有自己的智能体、问题和设置。

**技术亮点**: 采用 TypeScript 开发，支持与 Claude Code、Codex、GitHub Copilot CLI 等多种智能体客户端集成，提供 Homebrew 和脚本快速安装方式。

---
## 10. [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos)
- **语言**: Python
- **Stars**: 25,809
- **简介**: Kronos: A Foundation Model for the Language of Financial Markets

### AI 总结
**简介**: Kronos 是首个专为金融市场 K 线数据设计的开源基础模型，基于全球 45+ 交易所数据训练。

**核心功能**:
- 提供多尺寸预训练模型（Kronos-mini/small/base/large），支持不同计算需求
- 通过 `KronosPredictor` 类实现金融市场 K 线预测（如 BTC/USDT 未来 24 小时走势）
- 提供在线演示页面可视化预测结果
- 支持微调脚本，可适配自定义量化任务

**技术亮点**:
- 采用创新的两阶段框架：专用分词器将多维 OHLCV 数据量化为分层离散令牌，再通过自回归 Transformer 预训练
- 基于解码器架构设计，专门处理金融数据的高噪声特性
- 模型已开源至 Hugging Face Hub，支持 2048 和 512 两种上下文长度

---
