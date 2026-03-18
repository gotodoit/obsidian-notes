---
tags:
  - github-trending
  - daily
date: 2026-03-18
created: 2026-03-18T01:55:50.933Z
---

# 2026-03-18 GitHub Trending Top 6

## 1. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 92,567
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为 AI 编程助手设计的智能技能框架和软件开发工作流，通过一系列可组合的“技能”和初始指令，引导助手以结构化、自动化的方式完成从设计到实现的完整开发过程。

**核心功能**:
- **结构化工作流**: 提供从需求澄清、设计评审、任务规划、子代理驱动开发到代码审查的完整自动化流程。
- **自动化技能触发**: 内置多种技能（如测试驱动开发、系统化调试、Git工作树管理等），在相关任务前自动触发，强制执行最佳实践。
- **多平台支持**: 支持 Claude Code、Cursor、Codex、OpenCode、Gemini CLI 等多种 AI 编程助手和 IDE。

**技术亮点**: 基于“子代理驱动开发”架构，强调真正的红绿测试驱动开发、YAGNI 和 DRY 原则，确保开发过程规范且可自主运行数小时而不偏离计划。

---
## 2. [codecrafters-io/build-your-own-x](https://github.com/codecrafters-io/build-your-own-x)
- **语言**: Markdown
- **Stars**: 479,897
- **简介**: Master programming by recreating your favorite technologies from scratch.

### AI 总结
**简介**: 一个通过从零开始复现各类核心技术来深入学习编程的项目集合。

**核心功能**:
- 提供分步骤、高质量的教程，指导用户从零构建各种技术。
- 涵盖领域广泛，包括3D渲染器、数据库、操作系统、区块链、AI模型、网络栈等数十个类别。

**技术亮点**: 教程涉及多种编程语言（如C++、Python、Java、Go、JavaScript等），遵循“无法创造则无法理解”的理念，强调实践出真知。

---
## 3. [abhigyanpatwari/GitNexus](https://github.com/abhigyanpatwari/GitNexus)
- **语言**: TypeScript
- **Stars**: 16,767
- **简介**: GitNexus: The Zero-Server Code Intelligence Engine - GitNexus is a client-side knowledge graph creator that runs entirely in your browser. Drop in a GitHub repo or ZIP file, and get an interactive knowledge graph wit a built in Graph RAG Agent. Perfect for code exploration

### AI 总结
**简介**: GitNexus 是一个完全在浏览器中运行的客户端知识图谱创建工具，无需服务器，可为任何代码仓库生成交互式知识图谱并内置图增强检索（Graph RAG）智能体，助力代码探索与分析。

**核心功能**:
- **零服务器、浏览器内运行**：通过 Web UI 直接上传 GitHub 仓库或 ZIP 文件，即可在浏览器中生成并交互式探索代码知识图谱。
- **本地 CLI 与 MCP 集成**：通过命令行工具在本地索引代码库，并通过模型上下文协议（MCP）为 Cursor、Claude Code 等 AI 编码助手提供深度的代码架构感知能力。
- **双模式使用**：提供便捷的 Web UI 用于快速探索和演示，以及功能完整的 CLI + MCP 模式用于日常开发，支持“桥接模式”将两者连接。
- **智能代码分析**：利用知识图谱追踪代码中的依赖关系、调用链、集群和执行流，使 AI 代理能避免遗漏依赖、破坏调用链等问题。

**技术亮点**:
- **前端技术栈**：基于 TypeScript 开发，使用 Tree-sitter WASM 进行代码解析，LadybugDB WASM 用于浏览器内存储。
- **本地处理**：CLI 版本使用 Tree-sitter 原生绑定和 LadybugDB 实现快速、持久的本地索引，保障隐私。
- **生态集成**：深度集成主流 AI 编码工具（如 Claude Code、Cursor、Windsurf），通过 MCP 协议和自动生成的上下文文件（如 `AGENTS.md`）增强其代码理解能力。

---
## 4. [langchain-ai/deepagents](https://github.com/langchain-ai/deepagents)
- **语言**: Python
- **Stars**: 14,194
- **简介**: Agent harness built with LangChain and LangGraph. Equipped with a planning tool, a filesystem backend, and the ability to spawn subagents - well-equipped to handle complex agentic tasks.

### AI 总结
**简介**: Deep Agents 是一个基于 LangChain 和 LangGraph 构建的、开箱即用的智能体框架，旨在简化复杂智能体任务的开发。

**核心功能**:
- **任务规划与跟踪**: 内置 `write_todos` 工具，用于任务分解和进度追踪。
- **文件系统操作**: 提供 `read_file`、`write_file`、`ls`、`grep` 等工具，支持读写和搜索上下文。
- **Shell命令执行**: 通过 `execute` 工具运行命令（支持沙盒环境）。
- **子智能体调用**: 通过 `task` 工具委托工作，并拥有独立的上下文窗口。
- **智能上下文管理**: 支持长对话自动摘要，并能将大输出保存至文件。

**技术亮点**: 基于 LangGraph 构建，提供生产级运行时支持（如流式处理、持久化、检查点）；模型提供商无关，支持任何具备工具调用能力的 LLM；采用 MIT 开源协议，完全可扩展。

---
## 5. [jarrodwatts/claude-hud](https://github.com/jarrodwatts/claude-hud)
- **语言**: JavaScript
- **Stars**: 5,684
- **简介**: A Claude Code plugin that shows what's happening - context usage, active tools, running agents, and todo progress

### AI 总结
**简介**: 一个用于 Claude Code 的插件，在输入框下方实时显示会话状态，包括上下文使用情况、活跃工具、运行中的代理和待办事项进度。

**核心功能**:
- **状态概览**: 实时显示项目路径、Git分支、当前模型和计划名称。
- **上下文监控**: 以进度条形式直观展示上下文窗口的使用率，并支持显示API使用率限制。
- **活动追踪**: 监控并显示Claude正在进行的文件读写、编辑、搜索等工具活动。
- **代理与任务管理**: 展示正在运行的子代理状态及其任务，并跟踪待办事项的实时完成进度。

**技术亮点**:
- 基于Claude Code的原生**状态栏API**，无需额外窗口或tmux，兼容任何终端。
- 直接从Claude Code获取原生令牌数据，而非估算，准确度高。
- 通过解析会话转录流（JSONL）来获取工具、代理和待办事项的活动信息。
- 提供可配置的预设（完整/精简/最小化）和详细的配置选项，支持自定义布局、显示元素和颜色。

---
## 6. [cloudflare/workerd](https://github.com/cloudflare/workerd)
- **语言**: C++
- **Stars**: 7,841
- **简介**: The JavaScript / Wasm runtime that powers Cloudflare Workers

### AI 总结
**简介**: workerd 是 Cloudflare 开源的、基于其 Workers 平台相同代码构建的 JavaScript/Wasm 服务器运行时。

**核心功能**:
- **作为应用服务器**：用于自托管为 Cloudflare Workers 设计的应用程序。
- **作为开发工具**：用于在本地开发和测试 Workers 代码。
- **作为可编程 HTTP 代理**：高效地拦截、修改和路由网络请求。

**技术亮点**:
- **基于标准**：内置 API 基于 Web 平台标准（如 `fetch`）。
- **Nanoservices 架构**：支持将应用拆分为解耦、可独立部署的组件，调用时性能接近本地函数调用。
- **同质化部署**：可将所有 nanoservices 部署到集群中的每台机器，简化负载均衡。
- **基于能力的绑定配置**：通过能力绑定而非全局命名空间来连接服务和外部资源，提高代码可组合性并免疫 SSRF 攻击。
- **始终向后兼容**：版本号对应一个日期（兼容性日期），可配置到过去日期以模拟当时的 API 行为。
- **警告**：workerd 本身并非强化的沙箱，运行不可信代码时需在虚拟机等安全沙箱内使用。

---
