---
tags:
  - github-trending
  - daily
date: 2026-03-15
created: 2026-03-15T01:55:49.081Z
---

# 2026-03-15 GitHub Trending Top 10

## 1. [volcengine/OpenViking](https://github.com/volcengine/OpenViking)
- **语言**: Python
- **Stars**: 10,650
- **简介**: OpenViking is an open-source context database designed specifically for AI Agents(such as openclaw). OpenViking unifies the management of context (memory, resources, and skills) that Agents need through a file system paradigm, enabling hierarchical context delivery and self-evolving.

### AI 总结
**简介**: OpenViking 是一个专为 AI Agent（如 openclaw）设计的开源上下文数据库，它通过文件系统范式统一管理 Agent 所需的内存、资源和技能，实现分层上下文传递和自我进化。

**核心功能**:
- **统一上下文管理**：采用文件系统范式，将 Agent 的记忆、资源和技能进行结构化组织，解决传统 RAG 中上下文碎片化的问题。
- **分层上下文加载**：提供 L0/L1/L2 三层结构，支持按需加载，显著降低 Token 消耗和成本。
- **目录递归检索**：结合目录定位与语义搜索，实现递归且精确的上下文获取，提升检索效果。
- **可视化检索轨迹**：支持目录检索路径的可视化，使上下文检索过程可观察、可调试。
- **自动会话管理**：自动压缩对话内容、资源引用和工具调用，提取长期记忆，使 Agent 能够自我迭代、越用越智能。

**技术亮点**: 采用创新的“文件系统范式”架构，支持多模态模型（VLM 和 Embedding 模型），提供 Python 包和 Rust CLI 两种安装方式，并具备跨平台（Linux、macOS、Windows）运行能力。

---
## 2. [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- **语言**: Python
- **Stars**: 11,338
- **简介**: Official, Anthropic-managed directory of high quality Claude Code Plugins.

### AI 总结
**简介**: Anthropic 官方维护的 Claude Code 插件目录，收录了高质量的第三方及内部开发的插件。

**核心功能**:
- 提供官方认证和社区贡献的 Claude Code 插件市场。
- 支持通过命令行或图形界面直接安装插件。
- 定义了标准化的插件结构，便于开发和集成。

**技术亮点**: 采用标准化的 `.claude-plugin/plugin.json` 元数据格式和可选的 MCP 服务器配置，结构清晰，支持扩展命令、代理和技能。

---
## 3. [dimensionalOS/dimos](https://github.com/dimensionalOS/dimos)
- **语言**: Python
- **Stars**: 867
- **简介**: The Dimensional Framework

### AI 总结
**简介**: Dimensional (dimos) 是一个用于通用机器人技术的现代操作系统框架，旨在通过Python构建物理空间应用，并原生支持智能体控制。

**核心功能**:
- **导航与建图**: 提供SLAM、动态避障、路径规划和自主探索功能，支持原生和ROS两种方式。
- **感知**: 集成检测器、3D投影、视觉语言模型（VLM）和音频处理等感知能力。
- **智能体控制与MCP**: 支持通过自然语言指令控制机器人（例如“去厨房”），并构建本地或托管的多智能体系统。
- **空间记忆**: 实现时空检索增强生成（RAG）、动态记忆、物体定位与持久化。

**技术亮点**:
- **跨平台硬件支持**: 兼容多种机器人形态，包括四足机器人（如Unitree Go2）、人形机器人（如Unitree G1）、机械臂和无人机。
- **现代化技术栈**: 基于Python，无需ROS即可运行；支持Nix flakes、Docker和CUDA。
- **原生智能体集成**: 智能体可作为原生模块运行，直接订阅嵌入式数据流（如激光雷达、摄像头、控制回路）。

---
## 4. [p-e-w/heretic](https://github.com/p-e-w/heretic)
- **语言**: Python
- **Stars**: 13,796
- **简介**: Fully automatic censorship removal for language models

### AI 总结
**简介**: Heretic 是一个用于自动移除语言模型审查（即“安全对齐”）的 Python 工具。

**核心功能**:
- 完全自动地移除语言模型的审查机制，无需昂贵的后训练。
- 通过结合方向性消融（“abliteration”）技术和基于 Optuna 的参数优化器，在最小化模型拒绝回答数量的同时，也最小化与原模型的 KL 散度。
- 提供内置的模型评估功能，方便用户验证去审查效果。

**技术亮点**: 采用先进的“方向性消融”（abliteration）算法，并结合 TPE 参数优化器（Optuna），实现了无需人工干预的高质量模型去审查。

---
## 5. [langflow-ai/openrag](https://github.com/langflow-ai/openrag)
- **语言**: Python
- **Stars**: 2,729
- **简介**: OpenRAG is a comprehensive, single package Retrieval-Augmented Generation platform built on Langflow, Docling, and Opensearch.

### AI 总结
**简介**: OpenRAG 是一个基于 Langflow、Docling 和 OpenSearch 构建的、开箱即用的检索增强生成（RAG）平台，用于实现智能文档搜索和 AI 对话。

**核心功能**:
- **开箱即用**：预集成了所有核心工具，安装即可运行。
- **智能文档处理**：能够处理复杂的真实世界数据，进行智能解析和知识库构建。
- **可视化工作流构建**：提供基于 Langflow 的拖放式界面，用于快速设计和迭代 RAG 工作流。
- **企业级搜索**：依托 OpenSearch 提供可扩展的生产级性能。
- **多语言 SDK 支持**：提供 Python 和 TypeScript/JavaScript SDK，便于集成到现有应用中。

**技术亮点**: 平台基于 FastAPI 和 Next.js 构建，核心技术栈包括 Langflow（工作流编排）、Docling（文档解析）和 OpenSearch（向量检索），并支持通过 Model Context Protocol (MCP) 连接 Cursor、Claude Desktop 等 AI 助手。

---
## 6. [lightpanda-io/browser](https://github.com/lightpanda-io/browser)
- **语言**: Zig
- **Stars**: 17,138
- **简介**: Lightpanda: the headless browser designed for AI and automation

### AI 总结
**简介**: Lightpanda 是一个专为无头（headless）场景设计的开源浏览器，旨在为AI智能体、LLM训练、网页抓取和测试提供快速、高效的Web自动化。

**核心功能**:
- 支持JavaScript执行和部分Web API。
- 通过Chrome DevTools Protocol (CDP) 与Playwright、Puppeteer、chromedp等主流自动化工具兼容。
- 提供命令行工具，可直接抓取网页内容或启动CDP服务器。

**技术亮点**:
- 使用Zig语言编写，性能出色：启动极快，执行速度比Chrome快11倍，内存占用比Chrome少9倍。
- 提供Docker镜像和跨平台（Linux、macOS、Windows WSL2）的预编译二进制文件，便于部署和集成。

---
## 7. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 43,878
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个包含多种专业化 AI 代理角色的集合，旨在通过具备独特个性和工作流程的“专家”来提升开发和工作效率。

**核心功能**:
- 提供涵盖前端、后端、移动开发、AI工程、DevOps、安全等多个工程领域的专业化AI代理。
- 支持与多种开发工具（如 Claude Code、Cursor、Aider 等）快速集成，方便调用。
- 每个代理都具备明确的职责、个性、工作流程和可交付成果，开箱即用。

**技术亮点**: 项目主要提供代理配置（Shell脚本），支持跨工具集成，具备良好的可扩展性和实用性。

---
## 8. [fishaudio/fish-speech](https://github.com/fishaudio/fish-speech)
- **语言**: Python
- **Stars**: 27,235
- **简介**: SOTA Open Source TTS

### AI 总结
**简介**: Fish Speech 是一个开源的、目前最先进的文本转语音（TTS）系统。

**核心功能**:
- 支持多语言、多说话人以及多轮对话的语音生成。
- 提供细粒度的韵律和情感控制，可通过自然语言标签（如 `[laugh]`、`[super happy]`）进行内联控制。
- 提供多种使用方式，包括命令行推理、WebUI、服务器部署和Docker容器化。

**技术亮点**: 采用强化学习对齐和双自回归架构，在超过1000万小时的多语言音频数据上训练，旨在生成自然、真实且富有情感的语音。其旗舰模型S2-Pro拥有40亿参数。

---
## 9. [InsForge/InsForge](https://github.com/InsForge/InsForge)
- **语言**: TypeScript
- **Stars**: 4,193
- **简介**: Give agents everything they need to ship fullstack apps. The backend built for agentic development.

### AI 总结
**简介**: InsForge 是一个专为 AI 编程智能体和 AI 代码编辑器构建的后端开发平台，通过语义层为智能体提供可理解、可操作的后端原语。

**核心功能**:
- **语义层抽象**：将数据库、身份验证、存储、函数等后端原语通过语义层暴露，使 AI 智能体能够理解、推理和端到端操作。
- **后端上下文管理**：智能体可以获取后端原语的文档和可用操作，直接配置原语，并通过结构化模式检查后端状态与日志。
- **多原语支持**：集成了认证、数据库、存储、边缘函数、模型网关和部署等核心后端服务。

**技术亮点**: 基于 TypeScript 开发，采用 Docker 容器化部署，通过 MCP（Model Context Protocol）服务器与智能体连接，并获得了 Vercel OSS 计划的支持。

---
## 10. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 83,547
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为 AI 编码智能体设计的、基于可组合“技能”的软件开发框架和工作流。

**核心功能**:
- **智能规划与设计**：在编写代码前，通过对话明确需求，并以可读的模块化方式呈现设计供用户确认。
- **子智能体驱动开发**：在用户批准计划后，启动子智能体流程，将任务分解为小单元并自动执行、审查和推进。
- **强制执行最佳实践**：内置并自动触发多项强制技能，如测试驱动开发、代码审查和 Git 工作流管理，确保开发质量。

**技术亮点**: 采用基于 Shell 脚本的“技能”库架构，技能可组合且能根据上下文自动触发，无缝集成到 Claude Code、Cursor、Codex 等多种 AI 编码平台中。

---
