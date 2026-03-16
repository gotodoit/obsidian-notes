---
tags:
  - github-trending
  - daily
date: 2026-03-16
created: 2026-03-16T01:55:52.739Z
---

# 2026-03-16 GitHub Trending Top 10

## 1. [lightpanda-io/browser](https://github.com/lightpanda-io/browser)
- **语言**: Zig
- **Stars**: 18,708
- **简介**: Lightpanda: the headless browser designed for AI and automation

### AI 总结
**简介**: Lightpanda 是一个专为 AI 智能体和自动化任务设计的、从头构建的无头浏览器，使用 Zig 语言编写。

**核心功能**:
- 支持 JavaScript 执行和部分 Web API。
- 通过 Chrome DevTools Protocol 与 Playwright、Puppeteer、chromedp 等主流自动化工具兼容。
- 提供命令行工具，支持直接抓取网页内容或启动 CDP 服务器。

**技术亮点**:
- **非 Chromium/WebKit 分支**：完全自主开发，旨在实现高性能和低资源消耗。
- **极致性能**：相比 Chrome，内存占用减少 9 倍，执行速度快 11 倍，并支持瞬时启动。
- **轻量部署**：提供适用于 Linux、macOS 的预编译二进制文件以及 Docker 镜像，便于集成。

---
## 2. [Crosstalk-Solutions/project-nomad](https://github.com/Crosstalk-Solutions/project-nomad)
- **语言**: TypeScript
- **Stars**: 1,141
- **简介**: Project N.O.M.A.D, is a self-contained, offline survival computer packed with critical tools, knowledge, and AI to keep you informed and empowered—anytime, anywhere.

### AI 总结
**简介**: Project N.O.M.A.D. 是一个自包含、优先离线的生存知识服务器，集成了关键工具、知识和本地AI，旨在让用户随时随地获取信息并保持自主能力。

**核心功能**:
- **AI聊天与知识库**: 基于Ollama的本地AI聊天，支持文档上传和语义搜索（通过Qdrant实现RAG）。
- **离线信息库**: 通过Kiwix提供离线版维基百科、医学参考、电子书等资源。
- **教育平台**: 集成Kolibri，提供可汗学院课程及进度跟踪。
- **离线地图**: 通过ProtoMaps提供可下载的区域地图。
- **数据工具**: 集成CyberChef，用于加密、编码、哈希和数据分析。
- **笔记系统**: 通过FlatNotes支持本地Markdown笔记。
- **系统基准测试**: 内置硬件评分与社区排行榜。

**技术亮点**: 采用Docker容器化架构，通过统一的管理UI和API（“指挥中心”）来编排所有工具和资源，实现一键安装、配置和更新。项目基于TypeScript开发，推荐在配备GPU的高性能硬件上运行以获得完整的AI体验。

---
## 3. [volcengine/OpenViking](https://github.com/volcengine/OpenViking)
- **语言**: Python
- **Stars**: 12,506
- **简介**: OpenViking is an open-source context database designed specifically for AI Agents(such as openclaw). OpenViking unifies the management of context (memory, resources, and skills) that Agents need through a file system paradigm, enabling hierarchical context delivery and self-evolving.

### AI 总结
**简介**: OpenViking 是一个专为 AI Agent（如 openclaw）设计的开源上下文数据库，它通过文件系统范式统一管理 Agent 所需的内存、资源和技能，实现分层上下文传递和自我进化。

**核心功能**:
- **统一上下文管理**: 采用“文件系统范式”，将 Agent 所需的记忆、资源和技能进行结构化组织，解决传统 RAG 中上下文碎片化的问题。
- **分层上下文加载**: 提供 L0/L1/L2 三层结构，支持按需加载，有效减少 Token 消耗和成本。
- **目录递归检索**: 结合原生文件系统检索与语义搜索，通过目录定位实现递归、精准的上下文获取。
- **可视化检索轨迹**: 支持目录检索路径的可视化，使上下文检索过程可观察、可调试。
- **自动会话管理与迭代**: 自动压缩对话内容、资源引用和工具调用，提取长期记忆，使 Agent 越用越智能。

**技术亮点**: 基于 Python 开发，采用创新的文件系统架构来组织和管理 Agent 上下文，支持多模态 VLM 模型和嵌入模型，并提供了 Python 包和 Rust CLI 两种使用方式。

---
## 4. [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code)
- **语言**: TypeScript
- **Stars**: 27,998
- **简介**: Bash is all you need - A nano Claude Code–like agent, built from 0 to 1

### AI 总结
**简介**: 这是一个从零到一构建类 Claude Code 智能代码代理的学习项目，通过 12 个渐进式会话，逐步揭示其核心代理模式与实现机制。

**核心功能**:
- **基础代理循环**: 实现“用户 -> LLM -> 工具执行 -> 结果返回”的核心交互循环。
- **渐进式能力增强**: 从单一工具循环开始，逐步增加任务规划、子代理、上下文管理、后台执行、多代理协作与工作区隔离等机制。
- **教学与可视化**: 提供交互式 Web 平台，用于可视化学习路径、查看源代码和图表。

**技术亮点**: 项目采用 TypeScript 语言，其架构核心是一个稳定不变的代理循环，所有高级功能（如任务图、异步邮箱、工作树隔离）均作为分层机制叠加其上，展示了如何构建一个模块化、可扩展的 AI 编码代理。

---
## 5. [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice)
- **语言**: HTML
- **Stars**: 17,054
- **简介**: practice made claude perfect

### AI 总结
**简介**: 这是一个关于 Claude Code 最佳实践的仓库，旨在通过实践来掌握和优化 Claude Code 的各项功能。

**核心功能**:
- **命令 (Commands)**: 用户可调用的提示模板，用于编排工作流。
- **子代理 (Subagents)**: 在独立上下文中运行的自主智能体，拥有自定义工具、权限和身份。
- **技能 (Skills)**: 可配置、可预加载的知识模块，支持上下文分叉和渐进式披露。
- **工作流 (Workflows)**: 通过命令、代理和技能的组合编排复杂任务。
- **钩子 (Hooks)**: 在特定事件上于智能体循环外运行的确定性脚本。
- **MCP 服务器**: 连接外部工具、数据库和 API 的模型上下文协议。
- **插件 (Plugins)**: 可分发的能力包，包含技能、子代理、钩子和 MCP 服务器。
- **设置 (Settings)**: 分层级的配置系统，涵盖权限、模型、输出样式、沙箱等。

**技术亮点**: 项目系统性地展示了 Claude Code 的架构特点，特别是其 **命令 → 代理 → 技能** 的编排工作流，以及通过 MCP 协议扩展能力、通过钩子实现确定性操作等高级功能。

---
## 6. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 86,026
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个基于可组合“技能”的智能体技能框架和软件开发方法论，旨在为编码智能体提供一个完整、自动化的开发工作流。

**核心功能**:
- **智能规划与设计**：在编码前通过对话明确需求，生成易于审阅的设计文档和详细的实现计划。
- **子智能体驱动开发**：通过启动子智能体来执行工程任务，并自动进行代码审查和质量检查，支持长时间自主工作。
- **强制执行最佳实践**：内置工作流强制进行真正的测试驱动开发（TDD），并遵循 YAGNI、DRY 等原则。
- **全流程自动化**：从头脑风暴、Git工作区管理、计划执行到代码审查和分支收尾，提供端到端的自动化开发支持。

**技术亮点**:
- **技能库架构**：提供一套可组合的自动化“技能”（如测试驱动开发、系统化调试），智能体在任务前会自动检查并触发相关技能。
- **多平台支持**：支持 Claude Code、Cursor、Codex、OpenCode、Gemini CLI 等多种AI编码助手和平台。

---
## 7. [p-e-w/heretic](https://github.com/p-e-w/heretic)
- **语言**: Python
- **Stars**: 14,727
- **简介**: Fully automatic censorship removal for language models

### AI 总结
**简介**: Heretic 是一个用于自动移除语言模型“安全对齐”（即审查）的 Python 工具。

**核心功能**:
- 全自动移除语言模型的审查机制，无需昂贵的后训练。
- 通过结合方向性消融（“abliteration”）技术和基于 Optuna 的参数优化器，自动寻找最优解。
- 在最小化模型拒绝回答次数的同时，也最小化与原模型的 KL 散度，以最大程度保留原始模型的智能。

**技术亮点**: 采用先进的“方向性消融/abliteration”技术，并结合 TPE 参数优化器（Optuna）实现完全自动化运行。

---
## 8. [666ghj/MiroFish](https://github.com/666ghj/MiroFish)
- **语言**: Python
- **Stars**: 27,364
- **简介**: A Simple and Universal Swarm Intelligence Engine, Predicting Anything. 简洁通用的群体智能引擎，预测万物

### AI 总结
**简介**: MiroFish 是一个基于多智能体技术的群体智能预测引擎，能够通过输入现实世界的“种子”信息，自动构建高保真的平行数字世界进行社会演化模拟，从而生成预测报告。

**核心功能**:
- **平行世界构建**：上传文本材料（如报告、新闻、小说）作为种子，自动生成包含成千上万具备独立人格和记忆的智能体的数字世界。
- **未来推演预测**：用户可注入变量，观察智能体在数字世界中的交互与演化，从“上帝视角”推演事件或故事的可能走向。
- **深度交互与报告**：生成详细的预测报告，并允许用户与模拟世界中的任意智能体或报告生成代理进行对话。

**技术亮点**:
- 采用**多智能体（Multi-Agent）** 架构，智能体具备长期记忆和行为逻辑。
- 利用 **GraphRAG** 进行知识图谱构建和记忆管理。
- 支持 **OpenAI SDK 兼容** 的多种大语言模型（如阿里百炼的 qwen-plus）。
- 提供**源码部署**和 **Docker 容器化**两种部署方式，便于快速启动。

---
## 9. [abhigyanpatwari/GitNexus](https://github.com/abhigyanpatwari/GitNexus)
- **语言**: TypeScript
- **Stars**: 14,371
- **简介**: GitNexus: The Zero-Server Code Intelligence Engine - GitNexus is a client-side knowledge graph creator that runs entirely in your browser. Drop in a GitHub repo or ZIP file, and get an interactive knowledge graph wit a built in Graph RAG Agent. Perfect for code exploration

### AI 总结
**简介**: GitNexus 是一个完全在浏览器中运行的客户端知识图谱引擎，无需服务器，通过上传 GitHub 仓库或 ZIP 文件即可生成交互式代码知识图谱，并内置图检索增强生成（Graph RAG）智能体，用于代码探索与分析。

**核心功能**:
- **零服务器知识图谱构建**: 在浏览器端将任意代码库（GitHub 仓库或本地 ZIP）索引为包含依赖、调用链、集群和执行流关系的知识图谱。
- **Graph RAG 智能体**: 提供基于图谱的交互式 AI 聊天功能，使 AI 助手能深度理解代码架构，避免遗漏依赖或破坏调用链。
- **双模式使用**: 提供 **Web UI** 用于快速可视化探索和聊天；提供 **CLI + MCP（模型上下文协议）** 用于本地深度索引，并与 Cursor、Claude Code 等 AI 编码助手深度集成，为其提供持久的代码库上下文。

**技术亮点**:
- **完全客户端/本地运行**: 利用浏览器 IndexedDB（LadybugDB WASM）或本地 LadybugDB 实现数据存储与处理，保障隐私。
- **集成 MCP 协议**: 通过标准 MCP 服务器为各类 AI 编码工具提供结构化代码知识工具。
- **Tree-sitter 解析**: 使用 Tree-sitter（WASM 或本地绑定）进行精准的代码语法解析。
- **桥接模式**: CLI 本地服务可与 Web UI 连接，实现无需重复上传即可浏览所有已索引仓库。

---
## 10. [topoteretes/cognee](https://github.com/topoteretes/cognee)
- **语言**: Python
- **Stars**: 13,938
- **简介**: Knowledge Engine for AI Agent Memory in 6 lines of code

### AI 总结
**简介**: Cognee 是一个开源的 Python 知识引擎，旨在通过简单的代码为 AI 智能体构建个性化、动态且持续学习的记忆系统。

**核心功能**:
- **统一知识基础设施**：支持任意格式或结构的数据摄取，结合向量搜索和图数据库，使文档既能按语义搜索又能按关系连接。
- **持久化与学习型智能体**：支持从反馈中学习、上下文管理以及跨智能体知识共享。
- **可靠且可信的智能体**：提供用户/租户隔离、可追溯性、OTEL 收集和审计特性。

**技术亮点**: 结合了向量搜索、图数据库和认知科学方法，支持本地运行、本体论基础和多模态处理。

---
