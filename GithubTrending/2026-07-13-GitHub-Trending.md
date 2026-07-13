---
tags:
  - github-trending
  - daily
date: 2026-07-13
created: 2026-07-13T01:55:43.869Z
---

# 2026-07-13 GitHub Trending Top 10

## 1. [Dicklesworthstone/destructive_command_guard](https://github.com/Dicklesworthstone/destructive_command_guard)
- **语言**: Rust
- **Stars**: 2,961
- **简介**: The Destructive Command Guard (dcg) is for blocking dangerous git and shell commands from being executed by agents.

### AI 总结
**简介**: dcg 是一个高性能的防护钩子，在 AI 编码代理执行危险命令前进行拦截，保护你的代码免受意外删除。

**核心功能**:
- **零配置保护**：开箱即用，自动拦截危险的 git 和文件系统命令。
- **50+ 安全策略包**：覆盖数据库、Kubernetes、Docker、AWS/GCP/Azure、Terraform 等场景。
- **Heredoc/内联脚本扫描**：可检测并拦截 `python -c "os.remove(...)"` 等内嵌脚本中的破坏性操作。
- **智能上下文检测**：能区分 `grep "rm -rf"`（数据）和 `rm -rf /`（执行）等不同场景。
- **丰富的终端输出**：在 stderr 上提供人性化的拒绝面板、规则上下文和建议，同时保持 stdout 的机器可读性。
- **原生支持多种 AI 代理**：包括 Claude Code、Codex CLI、Gemini CLI、Copilot CLI、Cursor IDE 等。

**技术亮点**: 使用 Rust 编写，采用 SIMD 加速的过滤机制，实现亚毫秒级延迟；支持 Linux、macOS 和 Windows（WSL/原生）；通过安装脚本自动检测平台并配置代理钩子。

---
## 2. [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP)
- **语言**: TypeScript
- **Stars**: 8,005
- **简介**: This is MCP server for Claude that gives it terminal control, file system search and diff file editing capabilities

### AI 总结
**简介**: Desktop Commander MCP 是一个为 Claude 等 AI 助手提供终端控制、文件系统搜索和差异文件编辑能力的 MCP 服务器。

**核心功能**:
- **增强终端控制**: 执行长时运行命令、管理进程、支持命令超时和后台执行，并提供输出分页功能。
- **全面文件操作**: 支持读写文本、Excel、PDF、DOCX 文件；创建、移动、搜索目录和文件；提供递归目录列表和负偏移读取。
- **智能代码编辑**: 支持外科手术式文本替换、全文件重写及基于模式替换，可同时处理多个文件。
- **内存代码执行**: 无需保存文件即可执行 Python、Node.js、R 等代码，支持即时数据分析（如 CSV/JSON/Excel）。
- **远程 AI 控制**: 支持通过 Remote MCP 从 ChatGPT、Claude 网页等远程使用。

**技术亮点**: 基于 TypeScript 构建，并集成 MCP Filesystem Server 以增强搜索和替换功能，使用 Model Context Protocol (MCP) 协议与 AI 客户端通信。

---
## 3. [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading)
- **语言**: Python
- **Stars**: 20,612
- **简介**: "Vibe-Trading: Your Personal Trading Agent"

### AI 总结
**简介**: Vibe-Trading 是一款由 HKUDS 开发的个人交易代理工具，通过一条命令即可赋予用户全面的交易能力，支持回测、策略开发、实时交易等多种功能。

**核心功能**:
- **策略开发与管理**: 支持将学术论文和券商研究报告转化为注册因子/策略，并自动监控 IC（信息系数）和夏普比率衰减，实现策略生命周期管理。
- **回测与优化**: 提供印度股票（NSE/BSE）回测支持、PIT 安全的基础因子层（Alpha Zoo → 460 因子）以及换手率感知的优化器。
- **多数据源与适配器**: 集成 16 个适配器的 IM 通道运行时，支持 Binance USD-M 永续合约历史数据、本地数据加载器（OHLCV 重采样）以及可选 QVeris 高级数据。
- **端到端研究调度**: 支持计划性研究任务自动化，结合 FastMCP 传输和 OpenAI 兼容的 LLM 网关（如 Requesty）。
- **API 与 MCP 支持**: 提供 API 服务器和 MCP（模型上下文协议）接口，便于集成到其他应用中。

**技术亮点**: 基于 Python 3.11+、FastAPI 后端和 React 19 前端，支持多语言文档（中、英、日、韩、阿拉伯语），采用模块化架构，通过 pip 一键安装（`vibe-trading-ai`），并拥有活跃的社区支持（飞书、微信、Discord）。

---
## 4. [PrefectHQ/prefect](https://github.com/PrefectHQ/prefect)
- **语言**: Python
- **Stars**: 23,163
- **简介**: Prefect is a workflow orchestration framework for building resilient data pipelines in Python.

### AI 总结
**简介**: Prefect 是一个用于构建弹性数据管道的 Python 工作流编排框架，能将简单脚本轻松提升为生产级工作流。

**核心功能**:
- 支持调度、缓存、重试和基于事件的自动化，帮助数据团队自信地自动化数据处理流程。
- 提供自托管 Prefect Server 或托管 Prefect Cloud 仪表盘，用于监控工作流活动。
- 通过 `flow` 和 `task` 装饰器实现工作流的编排与观察，支持复杂分支逻辑和依赖管理。

**技术亮点**: 基于 Python 3.10+，使用装饰器模式简化工作流定义，集成 HTTP 请求库（如 httpx）进行外部数据交互，支持 cron 调度和事件驱动部署。

---
## 5. [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)
- **语言**: Python
- **Stars**: 118,609
- **简介**: 100+ AI Agent & RAG apps you can actually run — clone, customize, ship.

### AI 总结
**简介**: Awesome LLM Apps 是一个包含100多个可直接运行的AI Agent和RAG应用模板的集合，旨在帮助开发者快速克隆、定制并部署生产级LLM应用。

**核心功能**:
- 提供100+随时可运行的AI Agent、RAG、多智能体协作、语音代理等模板
- 支持多种主流大模型（Claude、Gemini、GPT、Llama、Qwen、xAI等），可配置切换
- 所有模板均为自包含的完整源代码，只需3条命令即可运行
- 附赠免费的分步教程（来自Unwind AI平台）
- 支持本地运行，无需注册或付费

**技术亮点**:
- 基于Python构建，覆盖现代AI技术栈（AI Agents、RAG、MCP Agents、Voice Agents、Agent Skills、Fine-tuning）
- Apache-2.0开源协议，可自由复刻、修改和商业化
- 所有模板均为原创并经过端到端测试，非简单收集整合

---
## 6. [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks)
- **语言**: Jupyter Notebook
- **Stars**: 48,445
- **简介**: A collection of notebooks/recipes showcasing some fun and effective ways of using Claude.

### AI 总结
**简介**: 这是一个面向开发者的 Claude 模型实用指南和代码示例集合，包含可直接复用的 Jupyter Notebook 代码片段。

**核心功能**:
- 文本分类、检索增强生成、摘要等基础能力应用
- 集成外部工具（计算器、SQL查询、客户服务代理）
- 第三方数据源整合（Pinecone向量数据库、Wikipedia、网页内容）
- 多模态应用（图像理解、图表解析、表单提取、图像生成）
- PDF文档解析与自动化评估

**技术亮点**: 提供 Python 示例代码但支持跨语言适配，包含子代理架构、JSON 模式输出等高级技术，需配合 Claude API 密钥使用。

---
## 7. [home-assistant/core](https://github.com/home-assistant/core)
- **语言**: Python
- **Stars**: 89,086
- **简介**: 🏡 Open source home automation that puts local control and privacy first.

### AI 总结
**简介**: Home Assistant 是一个开源的家庭自动化平台，优先考虑本地控制和隐私保护，适合在树莓派或本地服务器上运行。  
**核心功能**:  
- 支持通过模块化架构集成多种设备和服务，易于扩展。  
- 提供自动化功能，允许用户创建自定义规则和场景。  
- 拥有丰富的集成库，覆盖智能家居设备、传感器等。  
**技术亮点**: 基于 Python 开发，采用模块化设计，支持通过社区贡献快速添加新组件。

---
## 8. [Crosstalk-Solutions/project-nomad](https://github.com/Crosstalk-Solutions/project-nomad)
- **语言**: TypeScript
- **Stars**: 33,819
- **简介**: Project N.O.M.A.D, is a self-contained, offline survival computer packed with critical tools, knowledge, and AI to keep you informed and empowered—anytime, anywhere.

### AI 总结
**简介**: Project N.O.M.A.D. 是一个自包含、离线优先的知识与教育服务器，集成了关键工具、知识和 AI，确保用户在任何地点、任何时间都能获取信息与支持。

**核心功能**:
- **AI 聊天与知识库**: 本地 AI 聊天，支持文档上传和语义搜索 (RAG)。
- **信息图书馆**: 离线访问 Wikipedia、医学参考、电子书等 (Kiwix)。
- **教育平台**: Khan Academy 课程，支持进度跟踪和多用户 (Kolibri)。
- **离线地图**: 可下载的区域地图，支持离线查看和搜索 (ProtoMaps)。
- **数据工具**: 加密、编码、哈希和数据分析 (CyberChef)。
- **笔记功能**: 本地 Markdown 笔记 (FlatNotes)。
- **系统基准测试**: 硬件评分与社区排行榜。
- **应用商店 (Supply Depot)**: 一键安装 PDF 工具、文件浏览器、密码管理器等应用，并支持自定义 Docker 容器。
- **自动更新**: 可选的自动化核心软件、应用和离线内容更新。

**技术亮点**: 基于 TypeScript 开发，采用 Docker 容器化架构，通过管理 UI ("Command Center") 和 API 编排所有工具与资源，支持 Debian 系统一键安装。

---
## 9. [ColeMurray/background-agents](https://github.com/ColeMurray/background-agents)
- **语言**: TypeScript
- **Stars**: 2,268
- **简介**: An open-source background agents coding system

### AI 总结
**简介**: 一个受 Ramp Inspect 启发的开源后台编码代理系统，支持在后台异步执行编码任务。

**核心功能**:
- 后台任务执行：在后台处理编码任务，用户可同时专注于其他工作
- 完整开发环境支持：提供 Node.js、Python、git、浏览器自动化、VS Code 等环境
- 多渠道接入：支持 Web UI、Slack、GitHub PR、Linear 议题、Webhooks 等多种触发方式
- 多人协作：支持实时多人会话协作
- 自动创建 PR：使用用户 OAuth 令牌创建 PR，确保正确归属
- 计划任务与自动化：支持 cron 作业、Sentry 告警、webhook 自动触发
- 并行子任务：可在独立沙箱中同时运行多个子任务
- 模型选择：支持 Anthropic Claude、OpenAI Codex、OpenCode Zen 等多种 AI 模型

**技术亮点**: 采用 Cloudflare Workers 作为控制平面，使用 Durable Objects 管理会话状态，结合 SQLite 数据库和 D1 数据库；GitHub App 集成实现单租户部署，令牌架构包括 GitHub App Token、用户 OAuth Token、沙箱认证 Token、WebSocket Token 等。

---
## 10. [k1tbyte/Wand-Enhancer](https://github.com/k1tbyte/Wand-Enhancer)
- **语言**: C#
- **Stars**: 6,975
- **简介**: Advanced UX and interoperability extension for Wand (WeMod) app

### AI 总结
**简介**: WandEnhancer 是一个开源工具，用于扩展 Wand (WeMod) 应用的本地配置和用户体验，提供高级自定义功能，且完全本地运行，无需网络请求。

**核心功能**:
- 本地环境配置管理和新版本自动兼容性调整
- 高级布局和主题自定义（仅客户端侧）
- AI 功能集成
- 远程 Web 面板：允许通过手机（同一 Wi-Fi 或 VPN）控制应用功能，通过扫描二维码连接
- 自定义脚本注入：支持在补丁时注入 JavaScript 脚本，用于调整或修复客户端 UI（需启用 Remote Web Panel 补丁）

**技术亮点**:
- 语言: C#
- 开源可审计，安全透明（无网络请求）
- 通过 GitHub Actions 构建可执行文件，不提供官方预编译二进制文件
- 自定义脚本注入利用渲染器注入机制，提供 `WandEnhancer` 辅助 API（如 `log`、`remoteUrl`、`apiVersion`）
- 远程面板使用 TCP 端口 `3223`，支持 Tailscale 等 VPN 跨网络访问

---
