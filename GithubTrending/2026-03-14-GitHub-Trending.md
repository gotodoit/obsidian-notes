---
tags:
  - github-trending
  - daily
date: 2026-03-14
created: 2026-03-14T01:55:52.939Z
---

# 2026-03-14 GitHub Trending Top 10

## 1. [microsoft/BitNet](https://github.com/microsoft/BitNet)
- **语言**: Python
- **Stars**: 34,009
- **简介**: Official inference framework for 1-bit LLMs

### AI 总结
**简介**: bitnet.cpp 是微软官方推出的用于 1 比特大语言模型（如 BitNet b1.58）的高效推理框架。

**核心功能**:
- 支持在 CPU 和 GPU 上进行**快速**且**无损**的 1.58 比特模型推理。
- 通过优化的内核，在 ARM 和 x86 CPU 上实现了显著的推理速度提升（1.37x 至 6.17x）和能耗降低（55.4% 至 82.2%）。
- 能够在单 CPU 上运行高达 100B 参数的模型，实现接近人类阅读速度（5-7 tokens/秒）的推理。

**技术亮点**:
- 基于 `llama.cpp` 框架和 `T-MAC` 的查找表方法构建。
- 提供可配置分块的并行内核实现和嵌入量化支持，带来额外 1.15x 至 2.1x 的加速。
- 支持多种内核（I2_S, TL1, TL2）以适应不同硬件平台。

---
## 2. [langflow-ai/openrag](https://github.com/langflow-ai/openrag)
- **语言**: Python
- **Stars**: 2,277
- **简介**: OpenRAG is a comprehensive, single package Retrieval-Augmented Generation platform built on Langflow, Docling, and Opensearch.

### AI 总结
**简介**: OpenRAG 是一个基于 Langflow、Docling 和 OpenSearch 构建的一体化检索增强生成平台，旨在实现智能的文档搜索和 AI 驱动的对话。

**核心功能**:
- **开箱即用**：预集成了所有核心工具，安装即可运行。
- **智能代理工作流**：支持重排序和多智能体协调的高级编排。
- **文档解析与摄取**：能智能处理现实世界中结构复杂的文档数据。
- **可视化工作流构建器**：基于 Langflow 的拖拽式界面，便于快速迭代。
- **模块化企业扩展**：可按需扩展功能。
- **企业级搜索**：基于 OpenSearch，支持生产级的大规模部署。

**技术亮点**: 采用 FastAPI 和 Next.js 构建，核心由 OpenSearch、Langflow 和 Docling 驱动，提供 Python 和 TypeScript/JavaScript SDK，并支持通过 Model Context Protocol 连接 Cursor、Claude Desktop 等 AI 助手。

---
## 3. [lightpanda-io/browser](https://github.com/lightpanda-io/browser)
- **语言**: Zig
- **Stars**: 15,521
- **简介**: Lightpanda: the headless browser designed for AI and automation

### AI 总结
**简介**: Lightpanda 是一个专为无头（headless）场景设计的开源浏览器，旨在为AI智能体、LLM训练、网页抓取和测试提供快速、低内存占用的自动化解决方案。

**核心功能**:
- 支持JavaScript执行和部分Web API。
- 通过Chrome DevTools Protocol (CDP) 与Playwright、Puppeteer、chromedp等主流自动化工具兼容。
- 提供命令行工具，支持直接抓取网页内容或启动CDP服务器。

**技术亮点**:
- 使用Zig语言编写。
- 性能卓越：相比Chrome，内存占用减少9倍，执行速度快11倍，且启动迅速。
- 提供多种安装方式，包括直接下载二进制文件（Linux/macOS）和使用Docker镜像。

---
## 4. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 81,951
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个基于可组合“技能”的智能体软件开发框架与工作流，旨在引导和增强AI编程助手（如Claude、Cursor）的开发过程。

**核心功能**:
- **结构化工作流**: 提供从需求澄清、设计评审、任务规划、子智能体驱动开发到代码审查的完整自动化开发流程。
- **自动化技能触发**: 内置多种技能（如测试驱动开发、系统化调试、Git工作树管理等），在开发任务中自动触发，强制执行最佳实践。
- **多平台支持**: 支持在Claude Code、Cursor、Codex、OpenCode、Gemini CLI等多种AI编程助手和平台上安装使用。

**技术亮点**: 采用“子智能体驱动开发”架构，将复杂任务分解为可由独立子智能体执行的微任务，并通过两阶段审查确保代码质量，支持长时间自主运行而不偏离原计划。

---
## 5. [public-apis/public-apis](https://github.com/public-apis/public-apis)
- **语言**: Python
- **Stars**: 409,509
- **简介**: A collective list of free APIs

### AI 总结
**简介**: 一个由社区和 APILayer 共同维护的免费公共 API 集合项目，旨在为开发者提供一个可直接用于产品的、涵盖多个领域的 API 宝藏库。

**核心功能**:
- 提供大量来自不同领域的免费公共 API 列表。
- 社区驱动，由成员手动精心整理和维护。
- 与 APILayer 平台深度集成，提供快速 API 集成方案。

**技术亮点**: 项目本身是一个列表（元数据）仓库，主要语言为 Python。其亮点在于社区协作的维护模式和与 APILayer 商业服务的结合，为开发者提供了从发现到集成的便捷路径。

---
## 6. [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo)
- **语言**: TypeScript
- **Stars**: 15,306
- **简介**: Test your prompts, agents, and RAGs. Red teaming/pentesting/vulnerability scanning for AI. Compare performance of GPT, Claude, Gemini, Llama, and more. Simple declarative configs with command line and CI/CD integration.

### AI 总结
**简介**: 一个用于评估、测试和红队测试大语言模型（LLM）应用的开源 CLI 和库，旨在帮助开发者构建安全、可靠的 AI 应用。

**核心功能**:
- **自动化评估与测试**：通过声明式配置，自动化测试提示词（prompts）、代理（agents）和检索增强生成（RAG）系统。
- **红队测试与安全扫描**：提供漏洞扫描和红队测试功能，以增强 LLM 应用的安全性。
- **多模型性能对比**：支持并排比较 OpenAI、Anthropic、Gemini、Llama 等多种主流 LLM 的性能。
- **CI/CD 集成**：可与持续集成/持续部署流程无缝集成，实现自动化检查。
- **代码扫描**：在拉取请求中审查与 LLM 相关的安全和合规问题。
- **结果共享**：提供 Web 查看器和命令行界面，方便团队查看和分享评估结果。

**技术亮点**:
- **开发者友好**：基于 TypeScript 开发，提供 CLI、Node.js 包和直观的 Web 界面，支持热重载和缓存。
- **隐私保护**：评估过程 100% 在本地运行，确保提示词和敏感数据不会外泄。
- **灵活可扩展**：支持几乎所有主流 LLM API，并可通过配置适配自定义模型或编程语言。
- **生产验证**：已在服务千万级用户的生产环境中得到验证，稳定可靠。

---
## 7. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 40,255
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个精心设计的 AI 智能体集合，提供具备专业领域知识、独特个性和交付成果的各类 AI 专家，旨在全方位提升开发与工作流程。

**核心功能**:
- **专业化智能体**: 提供涵盖前端开发、后端架构、移动应用、AI工程、DevOps、安全、嵌入式、区块链等多个工程领域的专家智能体。
- **多工具集成**: 支持与 Claude Code、Cursor、Aider、Windsurf、GitHub Copilot 等多种开发工具快速集成，方便调用。
- **生产就绪**: 每个智能体都包含明确的身份设定、工作流程、技术交付物示例和成功指标，开箱即用。

**技术亮点**: 项目主要提供智能体配置（如 Shell 脚本），其价值在于精心设计的提示工程（Prompt Engineering），为不同开发场景和工具链提供了可直接部署的、人格化的 AI 助手解决方案。

---
## 8. [dolthub/dolt](https://github.com/dolthub/dolt)
- **语言**: Go
- **Stars**: 21,088
- **简介**: Dolt – Git for Data

### AI 总结
**简介**: Dolt 是一个将 Git 版本控制理念应用于数据的 SQL 数据库，支持像操作 Git 仓库一样对数据进行分支、克隆、合并等操作。

**核心功能**:
- 作为兼容 MySQL 的 SQL 数据库，支持通过标准 SQL 接口读写数据和模式。
- 提供完整的 Git 式命令行界面（CLI），支持 `clone`、`branch`、`commit`、`merge`、`push`、`pull` 等版本控制操作。
- 支持通过 MySQL 二进制日志复制，将现有 MySQL 数据库设置为 Dolt 副本，实现数据变更的自动提交。

**技术亮点**: 使用 Go 语言开发，将数据库表（而非文件）作为版本控制的基本单位，实现了数据库与分布式版本控制系统的深度集成。

---
## 9. [google/A2UI](https://github.com/google/A2UI)
- **语言**: TypeScript
- **Stars**: 13,063
- **简介**: 

### AI 总结
**简介**: A2UI 是一个开源项目，包含一个用于表示可更新的智能体生成用户界面的优化格式和一组初始渲染器，旨在让智能体能够生成或填充丰富的用户界面。

**核心功能**:
- 提供一种声明式的 JSON 数据格式，允许智能体描述 UI 的“意图”，而非直接生成可执行代码。
- 客户端应用程序根据其本地的、受信任的组件库（如 Flutter、Angular、Lit 等）来渲染这些描述，确保安全性和跨平台一致性。
- 支持 UI 的增量更新，便于在对话过程中实现渐进式渲染和响应式用户体验。

**技术亮点**:
- **安全优先**：采用声明式数据格式，客户端维护受信任的预批准 UI 组件目录，智能体只能请求渲染目录中的组件。
- **LLM友好**：UI 表示为带有 ID 引用的扁平组件列表，便于 LLM 增量生成。
- **框架无关与可移植**：将 UI 结构与实现分离，同一 A2UI JSON 负载可在基于不同框架（如 Web、Flutter、React、SwiftUI）构建的多个客户端上渲染。
- **开放注册模式**：允许开发者将服务器端类型映射到自定义客户端实现，并支持通过“智能包装器”连接现有 UI 组件。

---
## 10. [fishaudio/fish-speech](https://github.com/fishaudio/fish-speech)
- **语言**: Python
- **Stars**: 26,881
- **简介**: SOTA Open Source TTS

### AI 总结
**简介**: Fish Speech 是一个开源的、达到当前最先进水平的文本转语音系统。

**核心功能**:
- 支持多语言、多说话人及多轮对话的语音生成。
- 提供细粒度的韵律和情感控制，可通过自然语言标签（如 `[laugh]`、`[super happy]`）进行内联控制。

**技术亮点**: 采用结合强化学习对齐的双自回归架构，在超过1000万小时的多语言音频数据上训练，旨在生成自然、真实且富有情感的语音。

---
