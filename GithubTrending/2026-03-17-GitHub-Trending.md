---
tags:
  - github-trending
  - daily
date: 2026-03-17
created: 2026-03-17T01:55:49.253Z
---

# 2026-03-17 GitHub Trending Top 10

## 1. [666ghj/MiroFish](https://github.com/666ghj/MiroFish)
- **语言**: Python
- **Stars**: 30,094
- **简介**: A Simple and Universal Swarm Intelligence Engine, Predicting Anything. 简洁通用的群体智能引擎，预测万物

### AI 总结
**简介**: MiroFish 是一个基于多智能体技术的通用群体智能引擎，旨在通过构建高保真的平行数字世界来模拟和预测各种现实或虚构场景的未来发展。

**核心功能**:
- **平行世界构建**：根据用户提供的“种子”信息（如新闻、报告、小说），自动生成一个包含成千上万具备独立人格、记忆和行为逻辑的智能体的数字世界。
- **动态推演预测**：用户可以从“上帝视角”动态注入变量，观察智能体间的社会演化，从而推演未来走向，生成详尽的预测报告。
- **深度交互**：支持与模拟世界中的任意智能体进行对话，或与负责生成报告的智能体进行交流，实现深度互动。

**技术亮点**:
- **多智能体架构**：核心采用多智能体技术，模拟复杂的社会互动与群体涌现现象。
- **GraphRAG 应用**：利用 GraphRAG 技术构建知识图谱，增强智能体的记忆与推理能力。
- **现代化技术栈**：项目采用 Python 后端与 Node.js 前端，支持 Docker 容器化部署，并集成了 Zep Cloud 用于记忆管理。

---
## 2. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 36,876
- **简介**: A Claude Code plugin that automatically captures everything Claude does during your coding sessions, compresses it with AI (using Claude's agent-sdk), and injects relevant context back into future sessions.

### AI 总结
**简介**: 一个为 Claude Code 设计的持久化记忆压缩系统插件，能自动捕获编码会话中的所有操作，利用 AI 进行压缩，并在未来的会话中注入相关上下文。

**核心功能**:
- 自动捕获 Claude 在编码会话期间的所有操作和观察结果。
- 使用 AI（基于 Claude 的 agent-sdk）对捕获的内容进行压缩和语义总结。
- 将压缩后的相关上下文智能地注入到未来的会话中，实现跨会话的持久化记忆。

**技术亮点**: 基于 TypeScript 开发，集成了 Claude 的 agent-sdk 进行 AI 驱动的语义压缩，并支持多语言文档。

---
## 3. [Crosstalk-Solutions/project-nomad](https://github.com/Crosstalk-Solutions/project-nomad)
- **语言**: TypeScript
- **Stars**: 1,857
- **简介**: Project N.O.M.A.D, is a self-contained, offline survival computer packed with critical tools, knowledge, and AI to keep you informed and empowered—anytime, anywhere.

### AI 总结
**简介**: Project N.O.M.A.D. 是一个自包含、优先离线的生存知识服务器，集成了关键工具、知识和本地AI，旨在让用户随时随地获取信息并保持自主能力。

**核心功能**:
- **AI聊天与知识库**：基于Ollama的本地AI聊天，支持文档上传和语义搜索（通过Qdrant实现RAG）。
- **离线信息库**：通过Kiwix提供离线版维基百科、医学参考、电子书等资源。
- **教育平台**：集成Kolibri，提供可汗学院课程及进度跟踪。
- **离线地图**：通过ProtoMaps提供可下载的区域地图。
- **数据工具**：集成CyberChef，用于加密、编码、哈希和数据分析。
- **笔记系统**：通过FlatNotes支持本地Markdown笔记。
- **系统基准测试**：内置硬件评分系统，并设有社区排行榜。

**技术亮点**: 采用Docker容器化架构，通过统一的管理UI（“指挥中心”）和API来编排所有工具和资源，实现一键安装、配置和更新。项目基于TypeScript开发，支持在无桌面环境的Debian系系统上以服务器模式运行。

---
## 4. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 88,766
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个基于可组合“技能”的智能体技能框架和软件开发方法论，旨在为编码智能体提供一个完整、自动化的工作流。

**核心功能**:
- **自动化工作流**: 引导智能体从需求澄清、设计确认、制定实现计划，到执行子智能体驱动开发、测试驱动开发和代码审查的完整流程。
- **可组合技能库**: 提供包括测试驱动开发、系统化调试、Git工作树管理等在内的一系列自动化技能，智能体会在任务前自动检查并应用相关技能。
- **多平台支持**: 支持在 Claude Code、Cursor、Codex、OpenCode 和 Gemini CLI 等多种AI编码助手和平台上安装使用。

**技术亮点**: 强调真正的红绿测试驱动开发、YAGNI和DRY原则，并通过“子智能体驱动开发”模式，使智能体能够长时间自主工作而不偏离计划。

---
## 5. [abhigyanpatwari/GitNexus](https://github.com/abhigyanpatwari/GitNexus)
- **语言**: TypeScript
- **Stars**: 15,652
- **简介**: GitNexus: The Zero-Server Code Intelligence Engine - GitNexus is a client-side knowledge graph creator that runs entirely in your browser. Drop in a GitHub repo or ZIP file, and get an interactive knowledge graph wit a built in Graph RAG Agent. Perfect for code exploration

### AI 总结
**简介**: GitNexus 是一个完全在浏览器中运行的客户端知识图谱创建工具，无需服务器，可为任何代码仓库生成交互式知识图谱，并内置图检索增强生成（Graph RAG）智能体，用于代码探索和分析。

**核心功能**:
- **零服务器架构**：整个工具在浏览器中运行，可直接拖入 GitHub 仓库或 ZIP 文件进行处理，无需后端服务器，保障隐私。
- **代码知识图谱构建**：自动将代码库索引为知识图谱，追踪依赖关系、调用链、集群和执行流等所有关联。
- **Graph RAG 智能体**：提供内置的图检索增强生成智能体，支持通过聊天方式与代码库交互，进行深度分析和查询。
- **双模式使用**：提供**Web UI**（无需安装，在线快速探索）和**CLI + MCP**（本地索引，通过模型上下文协议为AI编辑器/代理提供深度代码感知）两种方式。
- **编辑器集成**：通过MCP协议为 Claude Code、Cursor、Windsurf 等主流AI编码助手提供代码库的架构视图，增强其代码理解和编辑的准确性。

**技术亮点**:
- **客户端处理**：使用 Tree-sitter WASM 进行代码解析，LadybugDB WASM 进行图数据存储，完全在浏览器端完成。
- **模型上下文协议（MCP）**：通过标准协议与AI开发工具深度集成，为AI代理提供结构化的代码知识。
- **桥接模式**：支持本地CLI服务与Web UI联动，实现无需重复上传的大规模代码库浏览。

---
## 6. [lightpanda-io/browser](https://github.com/lightpanda-io/browser)
- **语言**: Zig
- **Stars**: 20,274
- **简介**: Lightpanda: the headless browser designed for AI and automation

### AI 总结
**简介**: Lightpanda 是一个专为 AI 代理和自动化设计的、从头编写的开源无头浏览器，使用 Zig 语言开发。

**核心功能**:
- 支持 JavaScript 执行和部分 Web API。
- 通过 Chrome DevTools Protocol 与 Playwright、Puppeteer、chromedp 等工具兼容。
- 提供命令行工具进行网页抓取和启动 CDP 服务器。
- 支持通过 Docker 镜像和二进制文件快速部署。

**技术亮点**:
- 非 Chromium 或 WebKit 分支，而是全新实现的浏览器，追求高性能和低资源占用。
- 据基准测试显示，其内存占用比 Chrome 低 9 倍，执行速度快 11 倍，且启动迅速。

---
## 7. [volcengine/OpenViking](https://github.com/volcengine/OpenViking)
- **语言**: Python
- **Stars**: 14,213
- **简介**: OpenViking is an open-source context database designed specifically for AI Agents(such as openclaw). OpenViking unifies the management of context (memory, resources, and skills) that Agents need through a file system paradigm, enabling hierarchical context delivery and self-evolving.

### AI 总结
**简介**: OpenViking 是一个专为 AI Agent（如 openclaw）设计的开源上下文数据库，它通过文件系统范式统一管理 Agent 所需的内存、资源和技能，实现分层上下文传递和自我进化。

**核心功能**:
- **统一上下文管理**：采用文件系统范式，将 Agent 的记忆、资源和技能进行结构化统一管理，解决传统 RAG 中上下文碎片化的问题。
- **分层上下文加载**：提供 L0/L1/L2 三层结构，支持按需加载，有效减少 Token 消耗和成本。
- **目录递归检索**：结合目录定位与语义搜索，支持原生文件系统检索方式，实现递归、精准的上下文获取。
- **可视化检索轨迹**：支持目录检索轨迹的可视化，使上下文检索过程可观察、可调试，便于优化检索逻辑。
- **自动会话管理与迭代**：自动压缩对话内容、资源引用和工具调用，提取长期记忆，使 Agent 能够在使用中自我迭代和变得更智能。

**技术亮点**:
- **文件系统范式**：创新地采用类文件系统的架构来组织和管理 Agent 上下文，替代了传统的扁平化向量存储模型。
- **多语言支持**：核心使用 Python 开发，同时提供了可选的 Rust CLI 工具，并需要 Go 语言来构建 AGFS 组件。
- **多模态支持**：需要视觉语言模型（VLM）进行图像和内容理解，以及嵌入模型进行向量化和语义检索，支持包括火山引擎在内的多个 VLM 提供商。

---
## 8. [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code)
- **语言**: TypeScript
- **Stars**: 29,365
- **简介**: Bash is all you need - A nano Claude Code–like agent, built from 0 to 1

### AI 总结
**简介**: 这是一个从零到一构建类 Claude Code 智能代码代理的学习项目，通过 12 个渐进式会话，逐步实现一个功能完整的纳米级 AI 代理。

**核心功能**:
- **基础代理循环**: 实现“用户消息 -> LLM -> 工具调用/响应”的核心循环模式。
- **渐进式机制叠加**: 从单一 Bash 工具循环开始，逐步增加规划、子任务、知识注入、上下文压缩、任务图、后台执行、多代理协作等 12 种机制。
- **多代理协作**: 支持创建具有独立工作目录和异步邮箱通信的持久化队友，实现任务自主认领与协作。
- **交互式学习平台**: 提供 Web 平台，包含可视化图表、源码查看器和交互式文档。

**技术亮点**: 项目采用 TypeScript 开发，核心架构基于简洁的代理循环模式，并通过分层设计，在不改变核心循环的前提下逐步叠加功能模块，清晰展示了 AI 代码代理的构建原理。

---
## 9. [p-e-w/heretic](https://github.com/p-e-w/heretic)
- **语言**: Python
- **Stars**: 15,312
- **简介**: Fully automatic censorship removal for language models

### AI 总结
**简介**: Heretic 是一个用于自动移除语言模型安全对齐（审查）的工具，无需昂贵的后训练。

**核心功能**:
- 完全自动地寻找并应用最优的“方向性消融”（abliteration）参数，以最小化模型的拒绝率和与原模型的KL散度。
- 支持通过命令行轻松使用，无需用户理解Transformer内部原理。
- 内置模型评估功能，可量化比较去审查效果。

**技术亮点**: 结合了先进的方向性消融算法实现与基于Optuna的TPE参数优化器，支持大多数密集型模型（包括多模态和多种MoE架构）。

---
## 10. [langchain-ai/deepagents](https://github.com/langchain-ai/deepagents)
- **语言**: Python
- **Stars**: 12,978
- **简介**: Agent harness built with LangChain and LangGraph. Equipped with a planning tool, a filesystem backend, and the ability to spawn subagents - well-equipped to handle complex agentic tasks.

### AI 总结
**简介**: Deep Agents 是一个基于 LangChain 和 LangGraph 构建的、开箱即用的智能体框架，旨在简化复杂智能体任务的开发。

**核心功能**:
- **任务规划与追踪**: 内置 `write_todos` 工具，用于任务分解和进度跟踪。
- **文件系统操作**: 提供 `read_file`、`write_file`、`edit_file`、`ls`、`glob`、`grep` 等工具，用于读写和管理上下文。
- **Shell访问与沙箱执行**: 通过 `execute` 工具运行命令（支持沙箱环境）。
- **子智能体调用**: 通过 `task` 工具委托工作，并拥有独立的上下文窗口。
- **智能上下文管理**: 支持长对话自动摘要，并将大输出自动保存到文件。

**技术亮点**: 基于 LangGraph 构建，提供生产级运行时支持（如流式处理、持久化、检查点）；模型提供商无关，支持任何具备工具调用能力的 LLM；支持通过 MCP 进行扩展。

---
