---
tags:
  - github-trending
  - daily
date: 2026-02-23
created: 2026-02-23T01:55:46.340Z
---

# 2026-02-23 GitHub Trending Top 9

## 1. [huggingface/skills](https://github.com/huggingface/skills)
- **语言**: Python
- **Stars**: 2,680
- **简介**: 

### AI 总结
**简介**: Hugging Face Skills 是一个为 AI/ML 任务（如数据集创建、模型训练和评估）提供标准化技能定义的项目，可与主流 AI 编码代理工具（如 Claude Code、Codex、Gemini CLI 和 Cursor）无缝集成。

**核心功能**:
- 提供一系列即用型技能，涵盖 Hugging Face Hub 的 CLI 操作、数据集管理、模型训练、评估、论文发布等任务。
- 遵循标准化的 Agent Skill 格式，每个技能都是一个包含指令、脚本和资源的独立文件夹。
- 兼容多种 AI 代理工具，通过统一的仓库结构（如 `AGENTS.md`、`gemini-extension.json` 和 Cursor 插件清单）提供支持。

**技术亮点**: 采用跨平台兼容设计，通过 `SKILL.md` 文件的 YAML 前导元数据定义技能，并提供了针对 Claude Code、OpenAI Codex、Google Gemini CLI 和 Cursor 的专用安装与集成指南。

---
## 2. [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi)
- **语言**: Go
- **Stars**: 7,060
- **简介**: ✨ Fully autonomous AI Agents system capable of performing complex penetration testing tasks

### AI 总结
**简介**: PentAGI 是一个基于人工智能、能够自主执行复杂渗透测试任务的全自动安全测试系统。

**核心功能**:
- **全自主AI代理**: AI驱动的代理可自动判断并执行渗透测试步骤。
- **专业工具集成**: 内置超过20种专业安全工具（如nmap、metasploit、sqlmap）。
- **智能记忆与知识图谱**: 具备长期存储研究结果的能力，并集成Neo4j知识图谱以追踪语义关系。
- **全面的信息收集**: 集成内置浏览器和多种外部搜索系统（如Tavily、Google、DuckDuckGo）进行情报搜集。
- **团队协作与监控**: 支持任务委派给专业AI代理，并提供详细的日志记录与Grafana/Prometheus监控。
- **详细报告生成**: 可生成包含漏洞利用指南的全面报告。

**技术亮点**:
- **架构**: 基于微服务的可扩展架构，所有操作在沙盒化的Docker环境中运行以确保隔离。
- **存储**: 使用PostgreSQL（含pgvector扩展）持久化存储所有命令和输出。
- **部署**: 支持通过Docker Compose快速部署，为自托管解决方案。
- **灵活性**: 支持多种LLM提供商（如OpenAI、Anthropic、Ollama、AWS Bedrock等）和自定义配置，并提供REST与GraphQL API。

---
## 3. [anthropics/claude-code](https://github.com/anthropics/claude-code)
- **语言**: Shell
- **Stars**: 68,985
- **简介**: Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands.

### AI 总结
**简介**: Claude Code 是一个基于终端的智能编码助手，通过自然语言命令帮助开发者理解代码库、执行常规任务并处理 Git 工作流。

**核心功能**:
- 通过自然语言命令执行日常编码任务
- 解释复杂代码逻辑
- 处理 Git 工作流

**技术亮点**: 支持多平台安装（macOS/Linux/Windows），提供插件系统扩展功能，集成数据收集与隐私保护机制。

---
## 4. [x1xhlol/system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools)
- **语言**: Unknown
- **Stars**: 117,872
- **简介**: FULL Augment Code, Claude Code, Cluely, CodeBuddy, Comet, Cursor, Devin AI, Junie, Kiro, Leap.new, Lovable, Manus, NotionAI, Orchids.app, Perplexity, Poke, Qoder, Replit, Same.dev, Trae, Traycer AI, VSCode Agent, Warp.dev, Windsurf, Xcode, Z.ai Code, Dia & v0. (And other Open Sourced) System Prompts, Internal Tools & AI Models

### AI 总结
**简介**: 这是一个收集并公开了众多流行AI编程助手和工具（如Cursor、Devin AI、v0等）内部系统提示词、工具和模型信息的仓库。

**核心功能**:
- 汇集了超过30,000行代码，揭示了Claude Code、Cursor、Devin AI、Replit、v0等30余款AI工具的内部运作机制。
- 提供对AI工具系统提示词、内部工具和模型配置的结构与功能洞察。

**技术亮点**: 仓库内容主要涉及对各类闭源和开源AI工具内部系统的逆向工程与信息聚合，为开发者研究和理解AI助手行为提供了宝贵的一手资料。

---
## 5. [Stremio/stremio-web](https://github.com/Stremio/stremio-web)
- **语言**: JavaScript
- **Stars**: 9,716
- **简介**: Stremio - Freedom to Stream

### AI 总结
**简介**: Stremio 是一个现代化的媒体中心，为用户提供一站式视频娱乐解决方案。

**核心功能**:
- 通过易于安装的插件（addons）来发现、观看和组织视频内容。
- 提供直观的界面，包括内容看板（Board）、发现（Discover）和元数据详情（Meta Details）等视图。

**技术亮点**: 基于 JavaScript 开发，使用 Node.js 和 npm 进行构建，支持开发服务器快速启动和生产环境构建。

---
## 6. [OpenBB-finance/OpenBB](https://github.com/OpenBB-finance/OpenBB)
- **语言**: Python
- **Stars**: 61,008
- **简介**: Financial data platform for analysts, quants and AI agents.

### AI 总结
**简介**: OpenBB 是一个面向分析师、量化交易员和 AI 代理的开源金融数据平台，旨在整合各类数据源并提供统一的数据访问层。

**核心功能**:
- 提供“一次连接，随处使用”的基础设施层，整合专有、授权和公共数据源。
- 通过 Python 包、OpenBB Workspace（企业级 UI）、Excel、MCP 服务器和 REST API 等多种方式暴露数据。
- 支持将本地运行的 ODP 后端与云端 OpenBB Workspace 无缝集成，实现数据与 AI 代理的联动。

**技术亮点**:
- 基于 Python 构建，可通过 `pip install openbb` 快速安装。
- 后端采用 FastAPI 框架，通过 Uvicorn 提供 API 服务。
- 支持在 VS Code Dev Containers、GitHub Codespaces 和 Google Colab 等多种开发环境中快速启动。

---
## 7. [cloudflare/agents](https://github.com/cloudflare/agents)
- **语言**: TypeScript
- **Stars**: 3,757
- **简介**: Build and deploy AI Agents on Cloudflare

### AI 总结
**简介**: Cloudflare Agents 是一个基于 Cloudflare Durable Objects 构建的、用于开发和部署具备持久化状态和生命周期的 AI Agent 的 TypeScript SDK。

**核心功能**:
- **持久化状态与实时同步**: 每个 Agent 拥有独立的状态和存储，状态变更可自动同步到所有连接的客户端。
- **声明式可调用方法**: 通过 `@callable()` 装饰器定义类型安全的远程方法，调用如同本地函数。
- **丰富的内置能力**: 支持调度任务、WebSocket 实时通信、AI 聊天、MCP 协议、工作流、邮件处理、SQL 查询等多种功能。
- **前端无缝集成**: 提供 React Hooks（如 `useAgent`）和 Vanilla JS 客户端，便于前端快速接入。

**技术亮点**: 基于 Cloudflare Durable Objects 实现，Agent 在空闲时休眠、按需唤醒，支持海量实例（如每用户一个）且闲置时无成本。架构上集成了状态管理、实时通信与 AI 能力，适用于游戏房间、用户会话等场景。

---
## 8. [abhigyanpatwari/GitNexus](https://github.com/abhigyanpatwari/GitNexus)
- **语言**: TypeScript
- **Stars**: 1,531
- **简介**: GitNexus: The Zero-Server Code Intelligence Engine - GitNexus is a client-side knowledge graph creator that runs entirely in your browser. Drop in a GitHub repo or ZIP file, and get an interactive knowledge graph wit a built in Graph RAG Agent. Perfect for code exploration

### AI 总结
**简介**: GitNexus 是一个完全在浏览器中运行的客户端知识图谱创建工具，无需服务器，可将代码仓库转换为交互式知识图谱，并内置图RAG智能体，用于代码探索与分析。

**核心功能**:
- **零服务器架构**：直接在浏览器中处理GitHub仓库或ZIP文件，构建代码知识图谱，保障隐私。
- **智能代码分析**：将代码库索引为包含依赖、调用链、集群和执行流等关系的知识图谱。
- **双模式使用**：提供Web UI（可视化图谱探索与AI聊天）和CLI + MCP（本地索引并与AI代理深度集成）。
- **AI代理增强**：通过MCP（模型上下文协议）为Cursor、Claude Code等编辑器提供深度代码库上下文，提升AI编码的准确性和可靠性。

**技术亮点**:
- **客户端处理**：使用KuzuDB WASM（Web UI）和原生KuzuDB（CLI）进行图数据存储与查询。
- **代码解析**：集成Tree-sitter（WASM/原生绑定）进行精准的代码语法分析。
- **编辑器集成**：全面支持Claude Code（MCP、技能和PreToolUse钩子）、Cursor、Windsurf和OpenCode。

---
## 9. [stan-smith/FossFLOW](https://github.com/stan-smith/FossFLOW)
- **语言**: TypeScript
- **Stars**: 18,189
- **简介**: Make beautiful isometric infrastructure diagrams

### AI 总结
**简介**: 一个基于 TypeScript 的开源等距视图图表绘制工具，用于创建美观的基础设施图。

**核心功能**:
- 提供拖放式界面，可从组件库中轻松添加节点和连接线。
- 支持在线使用（PWA）和离线操作，也可通过 Docker 快速部署。
- 允许以多种格式（PNG、SVG、JSON）导出和导入图表。

**技术亮点**: 采用 React 和 Isoflow 库构建，项目为包含独立库和应用的 Monorepo 结构，并支持 Docker 容器化部署。

---
