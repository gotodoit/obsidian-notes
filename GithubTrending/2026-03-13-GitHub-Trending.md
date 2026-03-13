---
tags:
  - github-trending
  - daily
date: 2026-03-13
created: 2026-03-13T01:55:51.405Z
---

# 2026-03-13 GitHub Trending Top 10

## 1. [microsoft/BitNet](https://github.com/microsoft/BitNet)
- **语言**: Python
- **Stars**: 32,431
- **简介**: Official inference framework for 1-bit LLMs

### AI 总结
**简介**: bitnet.cpp 是微软官方推出的用于 1 比特大语言模型（如 BitNet b1.58）的高效推理框架。

**核心功能**:
- 提供优化的内核，支持在 CPU 和 GPU 上进行**快速**且**无损**的 1.58 比特模型推理。
- 在 CPU 上实现显著性能提升（ARM 平台 1.37x-5.07x，x86 平台 2.37x-6.17x）和能耗降低（55.4%-82.2%）。
- 支持在单 CPU 上运行百亿参数模型，达到接近人类阅读速度（5-7 词元/秒），极大增强了在本地设备运行大模型的可能性。

**技术亮点**:
- 基于 `llama.cpp` 框架和 `T-MAC` 的查找表方法构建。
- 最新优化引入了可配置分块的并行内核实现和嵌入量化支持，带来了额外的 1.15x 到 2.1x 加速。
- 支持多种内核（如 I2_S, TL1, TL2）以适应不同硬件平台（x86, ARM）。

---
## 2. [fishaudio/fish-speech](https://github.com/fishaudio/fish-speech)
- **语言**: Python
- **Stars**: 26,394
- **简介**: SOTA Open Source TTS

### AI 总结
**简介**: Fish Speech 是一个开源的、基于 Python 的 SOTA（最先进）文本转语音（TTS）系统。

**核心功能**:
- 支持多语言（约50种语言）和多说话人的高质量语音合成。
- 提供细粒度的韵律和情感控制，可通过自然语言标签（如 `[laugh]`、`[whispers]`）进行内联控制。
- 支持多种部署和使用方式，包括命令行推理、WebUI、服务器部署和 Docker。

**技术亮点**: 采用结合强化学习对齐的双自回归架构（Dual-Autoregressive），在超过1000万小时的音频数据上训练，旨在生成自然、真实且富有情感的语音。

---
## 3. [langflow-ai/openrag](https://github.com/langflow-ai/openrag)
- **语言**: Python
- **Stars**: 1,587
- **简介**: OpenRAG is a comprehensive, single package Retrieval-Augmented Generation platform built on Langflow, Docling, and Opensearch.

### AI 总结
**简介**: OpenRAG 是一个基于 Langflow、Docling 和 OpenSearch 构建的、开箱即用的检索增强生成平台，旨在实现智能的文档搜索与对话。

**核心功能**:
- **智能文档处理与搜索**：支持上传、解析和查询文档，通过大语言模型和语义搜索提供基于知识的对话。
- **可视化工作流编排**：提供基于 Langflow 的拖放式界面，用于快速构建和迭代 RAG 工作流。
- **企业级可扩展性**：利用 OpenSearch 支持大规模生产级搜索，并提供模块化企业插件。
- **多语言 SDK 支持**：提供 Python 和 TypeScript/JavaScript SDK，便于集成到现有应用中。
- **模型上下文协议支持**：可通过 MCP 连接 Cursor、Claude Desktop 等 AI 助手。

**技术亮点**: 技术栈整合了 FastAPI（后端）、Next.js（前端）、OpenSearch（向量数据库/搜索引擎）、Langflow（工作流引擎）和 Docling（文档解析），构成了一个功能完备、生产就绪的 RAG 平台。

---
## 4. [InsForge/InsForge](https://github.com/InsForge/InsForge)
- **语言**: TypeScript
- **Stars**: 3,122
- **简介**: Give agents everything they need to ship fullstack apps. The backend built for agentic development.

### AI 总结
**简介**: InsForge 是一个专为AI编程智能体和AI代码编辑器构建的后端开发平台，通过语义层为智能体提供可理解、可操作的后端基础设施。

**核心功能**:
- **语义层抽象**: 将数据库、认证、存储、函数等后端原语通过语义层暴露，使AI智能体能够理解、推理和端到端操作。
- **后端上下文管理**: 智能体可以获取后端原语的文档和可用操作，直接配置原语，并通过结构化模式检查后端状态和日志。
- **一体化后端服务**: 集成了认证、数据库、存储、边缘函数、模型网关和部署等核心后端功能。

**技术亮点**: 基于TypeScript开发，采用Docker Compose进行本地部署，通过MCP（Model Context Protocol）服务器与智能体连接，架构上实现了智能体与后端基础设施之间的语义桥梁。

---
## 5. [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight)
- **语言**: Python
- **Stars**: 3,103
- **简介**: Hindsight: Agent Memory That Learns

### AI 总结
**简介**: Hindsight 是一个旨在让智能体能够随时间学习的智能体记忆系统，超越了传统对话历史记忆，专注于实现智能体的持续学习能力。

**核心功能**:
- **记忆存储与检索**：通过 `retain` 和 `recall` 方法，智能体可以存储信息并根据查询进行搜索。
- **情境感知响应**：通过 `reflect` 方法，生成基于记忆和情境的智能响应。
- **无缝集成**：提供 LLM Wrapper，仅需两行代码即可为现有智能体添加记忆功能；也提供 SDK 和 HTTP API 供深度集成。

**技术亮点**:
- **性能卓越**：在 LongMemEval 基准测试中取得了最先进的性能，是当前最准确的智能体记忆系统之一。
- **多模态部署**：支持 Docker 快速部署（推荐），并可选择使用外部 PostgreSQL 数据库。
- **多语言客户端**：提供 Python (`hindsight-client`) 和 Node.js/TypeScript (`@vectorize-io/hindsight-client`) SDK。
- **多模型支持**：支持 OpenAI、Anthropic、Gemini、Groq、Ollama、LM Studio 等多种 LLM 提供商。

---
## 6. [alibaba/page-agent](https://github.com/alibaba/page-agent)
- **语言**: TypeScript
- **Stars**: 6,108
- **简介**: JavaScript in-page GUI agent. Control web interfaces with natural language.

### AI 总结
**简介**: 一个运行在网页内的 JavaScript GUI 智能体，允许用户使用自然语言控制网页界面。

**核心功能**:
- **易于集成**：无需浏览器扩展、Python 或无头浏览器，仅需在页面内引入 JavaScript。
- **基于文本的 DOM 操作**：无需截图或多模态大模型，直接操作 DOM。
- **自带大模型**：支持用户接入自己的大语言模型。
- **美观的交互界面**：提供带有人类反馈循环的友好用户界面。
- **多页面任务**：提供可选的 Chrome 扩展，以支持跨浏览器标签页的任务。

**技术亮点**:
- 基于 TypeScript 开发。
- 采用纯前端方案，所有操作均在用户浏览器页面内完成。
- 项目灵感与部分组件源自开源项目 `browser-use`，专注于客户端网页增强。

---
## 7. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 80,021
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为 AI 编程代理（如 Claude、Cursor 等）设计的、基于可组合“技能”的智能体化软件开发框架与工作流。

**核心功能**:
- **结构化工作流**：引导代理从需求澄清、设计评审、制定详细实施计划，到最终执行，形成完整的开发闭环。
- **子代理驱动开发**：通过创建子代理来执行计划中的每个工程任务，并进行两阶段审查，支持长时间自主工作。
- **强制最佳实践**：内建并自动强制执行测试驱动开发、YAGNI、DRY 等工程原则，确保代码质量。
- **技能库**：提供包括系统化调试、代码审查、Git 工作树管理等可自动触发的技能模块。

**技术亮点**: 采用“技能”作为核心抽象，能根据不同开发场景（如构思、计划、编码、调试）自动触发相应流程，无缝集成到多种主流 AI 编程平台（Claude Code, Cursor, Codex, OpenCode, Gemini CLI）。

---
## 8. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 6,196
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是由 Nous Research 开发的一款具备自我学习和成长能力的 AI 代理，支持在多种云环境和客户端上运行。

**核心功能**:
- **自我改进的学习闭环**：能够从经验中创建技能，在使用中优化技能，并建立跨会话的用户模型。
- **多平台接入**：支持通过 Telegram、Discord、Slack、CLI 等多种方式进行交互，实现跨平台对话连续性。
- **灵活的模型支持**：可无缝切换使用 Nous Portal、OpenRouter、OpenAI 等多种模型提供商，无供应商锁定。
- **自动化与并行处理**：内置定时任务调度器，可生成子代理并行处理工作流，并能将多步骤流程整合。
- **随处部署**：支持在本地、Docker、SSH、Modal 等多种后端运行，具备低成本、服务器无感知的休眠与唤醒能力。

**技术亮点**:
- 采用 **Honcho** 进行用户建模，兼容 **agentskills.io** 开放标准。
- 提供完整的终端用户界面，支持多行编辑、命令自动补全和流式工具输出。
- 具备研究友好特性，如批量轨迹生成和轨迹压缩，用于训练下一代工具调用模型。

---
## 9. [666ghj/MiroFish](https://github.com/666ghj/MiroFish)
- **语言**: Python
- **Stars**: 19,303
- **简介**: A Simple and Universal Swarm Intelligence Engine, Predicting Anything. 简洁通用的群体智能引擎，预测万物

### AI 总结
**简介**: MiroFish 是一个基于多智能体技术的群体智能预测引擎，能够通过输入种子信息（如新闻、报告或故事）构建高保真的数字平行世界，并模拟智能体交互来推演和预测未来。

**核心功能**:
- **平行世界构建**：自动从现实世界的种子材料（新闻、政策、小说等）中提取信息，构建包含独立人格、记忆和行为逻辑的智能体数字世界。
- **未来推演预测**：用户可通过“上帝视角”注入变量，观察成千上万智能体的社会演化，生成详尽的预测报告。
- **深度交互**：支持与模拟世界中的任意智能体对话，并与报告生成智能体进行交互，探索不同可能性。

**技术亮点**:
- 采用多智能体（Multi-Agent）架构，结合长期记忆与行为逻辑进行社会模拟。
- 利用 GraphRAG 进行知识图谱构建和实体关系抽取，增强模拟的真实性。
- 支持 OpenAI SDK 格式的多种大语言模型（如阿里百炼的 qwen-plus），并集成 Zep Cloud 进行记忆管理。
- 提供源码部署和 Docker 容器化部署，便于快速搭建和扩展。

---
## 10. [google-ai-edge/LiteRT](https://github.com/google-ai-edge/LiteRT)
- **语言**: C++
- **Stars**: 1,676
- **简介**: LiteRT, successor to TensorFlow Lite. is Google's On-device framework for high-performance ML & GenAI deployment on edge platforms, via efficient conversion, runtime, and optimization

### AI 总结
**简介**: LiteRT 是 Google 推出的下一代端侧设备高性能机器学习与生成式 AI 部署框架，作为 TensorFlow Lite 的继任者，专注于高效的模型转换、运行时和优化。

**核心功能**:
- 提供高效的模型转换、运行时和优化，用于在边缘平台上部署高性能 ML 和生成式 AI。
- 支持先进的 GPU/NPU 硬件加速，以提升推理性能。
- 提供统一的 NPU 加速访问，为开发者提供一致的体验。
- 支持生成式 AI 模型的高性能、简易集成。

**技术亮点**:
- **新的编译模型 API**：支持自动加速器选择、真正的异步执行和高效的 I/O 缓冲区处理。
- **统一的 NPU 加速**：无缝集成主流芯片供应商的 NPU。
- **卓越的 GPU 性能**：采用先进的 GPU 加速技术，通过新的缓冲区互操作性实现零拷贝并降低延迟。
- **跨平台支持**：支持 Linux、macOS、Windows 及 Android 等主流平台。

---
