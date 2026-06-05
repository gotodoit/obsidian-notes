---
tags:
  - github-trending
  - daily
date: 2026-06-05
created: 2026-06-05T01:55:44.336Z
---

# 2026-06-05 GitHub Trending Top 10

## 1. [chopratejas/headroom](https://github.com/chopratejas/headroom)
- **语言**: Python
- **Stars**: 12,617
- **简介**: Compress tool outputs, logs, files, and RAG chunks before they reach the LLM. 60-95% fewer tokens, same answers. Library, proxy, MCP server.

### AI 总结
**简介**: Headroom 是一个针对 AI Agent 的上下文压缩层，能够在工具输出、日志、文件等数据到达 LLM 之前，将其压缩 60-95% 的 Token 数，同时保持答案质量不变。

**核心功能**:
- **Library**: 提供 Python/TypeScript 库，可在任何应用中直接调用 `compress(messages)` 进行压缩
- **Proxy**: 启动本地代理服务器（`headroom proxy --port 8787`），无需修改代码即可集成
- **Agent wrap**: 一键包装 Claude、Codex、Cursor、Aider、Copilot 等 AI Agent
- **MCP 服务器**: 提供 `headroom_compress`、`headroom_retrieve`、`headroom_stats` 等 MCP 工具
- **跨 Agent 记忆**: 在 Claude、Codex、Gemini 等 Agent 间共享存储，自动去重
- **`headroom learn`**: 挖掘失败会话，自动将修正写入 `CLAUDE.md`/`AGENTS.md`
- **可逆压缩 (CCR)**: 原始数据保存在本地，LLM 可按需通过 `headroom_retrieve` 恢复

**技术亮点**:
- **多算法压缩引擎**: ContentRouter 自动检测内容类型，选择 SmartCrusher（JSON）、CodeCompressor（AST）、Kompress-base（文本/Hugging Face 模型）等最佳压缩器
- **CacheAligner**: 稳定输入前缀，提高 LLM 提供商的 KV 缓存命中率
- **本地优先**: 所有压缩和原始数据存储均在本地运行，数据不外传
- **多语言支持**: 提供 Python 和 npm 包，支持 Python 和 TypeScript 生态
- **开源 (Apache 2.0)**: 完整的 CI、代码覆盖率、文档支持

---
## 2. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 181,074
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 构建的、具备自我学习能力的 AI 代理，它通过内置的学习循环从经验中创建技能，并能在不同会话间持续理解用户，且可部署在多种低成本基础设施上。

**核心功能**:
- **真正的终端界面 (TUI)**: 支持多行编辑、斜杠命令自动补全、对话历史、中断重定向及流式工具输出。
- **多平台部署**: 通过单一网关进程，可同时在 Telegram、Discord、Slack、WhatsApp、Signal 和 CLI 上运行，支持语音转录和跨平台对话连续性。
- **闭环学习系统**: 包含代理策划的记忆、周期性提示、自主技能创建与自我改进，以及基于 FTS5 的跨会话搜索和 Honcho 用户模型。
- **定时自动化**: 内置 cron 调度器，支持将报告、备份等任务以自然语言形式定时发送到任何平台。
- **并行委托**: 可生成隔离的子代理进行并行工作，并支持通过 RPC 调用工具的 Python 脚本，简化多步骤流程。
- **灵活的基础设施**: 支持本地、Docker、SSH、Singularity、Modal 和 Daytona 六种终端后端，其中 Modal 和 Daytona 提供无服务器持久化，空闲时成本极低。

**技术亮点**: 基于 Python 构建，支持 200+ 模型提供商（如 OpenRouter, NVIDIA NIM, OpenAI 等），兼容 agentskills.io 开放标准，并提供用于训练下一代工具调用模型的批量轨迹生成与压缩功能。

---
## 3. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 207,294
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个跨多种 AI 代理工具（如 Claude Code、Codex、Cursor 等）的“代理工具集性能优化系统”，提供技能、本能、记忆、安全及研究优先的开发能力。

**核心功能**:
- 提供技能（Skills）、本能（Instincts）、记忆优化（Memory optimization）和持续学习（Continuous learning）能力。
- 集成安全扫描（Security scanning）和研究优先的开发工作流（Research-first development）。
- 支持跨多种 AI 代理工具（Codex、Claude Code、Cursor、OpenCode、Gemini、Zed、GitHub Copilot 等）的统一工作流。
- 提供 MCP 配置、遗留命令 shim 以及生产就绪的代理和钩子（Hooks）。
- 包括 ECC Pro（私有仓库 GitHub App）、社区讨论和赞助选项。

**技术亮点**: 基于 JavaScript/TypeScript，并支持 Shell、Python、Go、Java、Perl 等多语言生态；采用 MIT 开源许可，支持 12+ 种语言文档；架构为“harness-native operator system”，通过 Hermes 操作层实现跨工具可复用层。

---
## 4. [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)
- **语言**: Python
- **Stars**: 79,917
- **简介**: Turn any PDF or image document into structured data for your AI. A powerful, lightweight OCR toolkit that bridges the gap between images/PDFs and LLMs. Supports 100+ languages.

### AI 总结
**简介**: PaddleOCR 是一款全球领先的轻量级 OCR 工具包，可将 PDF 和图像文档转换为结构化的、可供 LLM 使用的数据，支持 100 多种语言。

**核心功能**:
- **智能文档解析**: 提供 SOTA 的文档视觉语言模型 (PaddleOCR-VL-1.6)，可将文档解析为 Markdown 和 JSON 格式，在文本、公式和表格识别上表现优异。
- **结构感知转换**: 基于 PP-StructureV3 引擎，将复杂 PDF 和图像转换为 Markdown 或 JSON，并提供表格单元格等细粒度的坐标信息。

**技术亮点**: 基于 PaddlePaddle 深度学习框架，采用轻量级视觉-语言模型架构，在 OmniDocBench 基准测试中达到 96.3% 的准确率，支持 CPU、GPU、XPU、NPU 等多种硬件。

---
## 5. [github/spec-kit](https://github.com/github/spec-kit)
- **语言**: Python
- **Stars**: 108,606
- **简介**: 💫 Toolkit to help you get started with Spec-Driven Development

### AI 总结
**简介**: Spec Kit 是一个开源工具包，通过将规格说明变为可执行文件，帮助开发者聚焦产品场景和可预测结果，而非从头“凭感觉编码”，从而更快地构建高质量软件。

**核心功能**:
- **Spec-Driven Development**: 颠覆传统开发模式，将规格说明从“指导性文档”转变为“可执行文件”，直接生成工作实现。
- **Specify CLI**: 提供命令行工具，用于初始化项目、创建和管理规格说明。
- **AI Coding Agent 集成**: 支持与 Copilot、Codex CLI 等 AI 编码代理集成，通过 `/speckit.*` 或 `$speckit-*` 命令交互。
- **项目初始化与原则设定**: 通过 `specify init` 初始化项目，并使用 `/speckit.constitution` 命令建立项目治理原则和开发指南。
- **规格说明创建**: 使用 `/speckit.specify` 命令描述要构建的内容，聚焦“是什么”和“为什么”，而非技术栈。

**技术亮点**: 基于 Python 开发，依赖 `uv` 包管理器，支持通过 `uv tool install` 或 `pipx` 安装，并提供自管理升级命令（`specify self upgrade`）。

---
## 6. [NVIDIA/cosmos](https://github.com/NVIDIA/cosmos)
- **语言**: Jupyter Notebook
- **Stars**: 9,033
- **简介**: NVIDIA Cosmos is an open platform of world models, datasets, and tools that enables developers to build Physical AI for robots, autonomous vehicles, smart infrastructure, and more.

### AI 总结
**简介**: NVIDIA Cosmos 是一个开放的世界模型、数据集和工具平台，旨在帮助开发者构建面向机器人、自动驾驶和智能基础设施的物理 AI。

**核心功能**:
- **世界理解**: 分析图像和视频，生成描述、时间事件、下一步动作、空间定位、物理合理性及因果推理。
- **世界生成**: 从文本、图像、视频或动作输入生成图像、视频、同步音频及动作条件化的未来预测。
- **动作建模**: 支持机器人、相机运动、自我运动及自动驾驶场景的策略动作预测、逆动力学和正动力学建模。
- **灵活部署**: 提供 Diffusers/Transformers 用于 Python 开发，以及 vLLM-Omni/vLLM 用于 OpenAI 兼容的服务部署。

**技术亮点**:
- 采用统一的 **Mixture-of-Transformers (MoT)** 架构，融合自回归 Transformer（推理）与扩散 Transformer（生成），支持多模态联合处理。
- 使用 **3D 多维旋转位置嵌入 (mRoPE)** 编码空间、时间及跨模态结构，实现图像、视频、音频和动作序列的一致推理。

---
## 7. [lfnovo/open-notebook](https://github.com/lfnovo/open-notebook)
- **语言**: TypeScript
- **Stars**: 25,090
- **简介**: An Open Source implementation of Notebook LM with more flexibility and features

### AI 总结
**简介**: Open Notebook 是一个开源的、注重隐私的 Notebook LM 替代方案，提供更灵活的 AI 模型选择、多格式内容管理和专业播客生成功能。

**核心功能**:
- 🔒 **数据隐私**：支持自托管，确保研究数据完全私有
- 🤖 **多模型支持**：兼容 18+ AI 提供商（OpenAI、Anthropic、Ollama 等）
- 📚 **多模态内容管理**：PDF、视频、音频、网页等格式的组织与搜索
- 🎙️ **专业播客生成**：支持 1-4 个自定义角色的多说话人播客
- 🔍 **智能搜索**：全文搜索和向量搜索，跨内容检索
- 💬 **上下文对话**：基于研究内容的 AI 聊天
- 🌐 **多语言 UI**：支持英文、中文、日文等多语言

**技术亮点**:
- 技术栈：Python、Next.js、React、SurrealDB、LangChain
- 部署方式：Docker、云或本地部署，灵活可控
- 功能对比：比 Google Notebook LM 更灵活（自定义播客角色、API 访问、成本优化）

---
## 8. [Open-LLM-VTuber/Open-LLM-VTuber](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber)
- **语言**: Python
- **Stars**: 9,631
- **简介**: Talk to any LLM with hands-free voice interaction, voice interruption, and Live2D taking face running locally across platforms

### AI 总结
**简介**: Open-LLM-VTuber 是一个跨平台的语音交互 AI 伴侣，支持实时语音对话、视觉感知和 Live2D 虚拟形象，所有功能可完全离线运行。

**核心功能**:
- **免提语音交互**：支持语音打断、实时对话，可通过语音与 AI 互动。
- **Live2D 虚拟形象**：拥有生动的 Live2D 角色，支持自定义外观和人格（如虚拟女友/男友/宠物等）。
- **多平台支持**：兼容 Windows、macOS 和 Linux，提供 Web 版和桌面客户端（含透明背景桌面宠物模式）。
- **视觉感知**：支持视觉输入，让 AI 能“看到”环境并作出反应。
- **聊天记录持久化**：支持对话历史存储，可随时继续未完成的交流。

**技术亮点**:
- **跨平台运行**：基于 Python 开发，支持本地离线部署，无需联网即可使用。
- **多后端集成**：整合多种 LLM 推理、文本转语音（TTS）和语音识别（ASR）方案，提供灵活配置。
- **Docker 支持**：提供 Docker 镜像，简化部署流程。
- **活跃社区与文档**：拥有 Discord、Zulip 等开发社区，提供中文常见问题文档和用户指南。

---
## 9. [jwasham/coding-interview-university](https://github.com/jwasham/coding-interview-university)
- **语言**: Unknown
- **Stars**: 349,750
- **简介**: A complete computer science study plan to become a software engineer.

### AI 总结
**简介**: 一份为软件工程师面试准备的计算机科学自学计划，内容详尽，覆盖从基础到高级的面试知识点。

**核心功能**:
- 提供从零开始的系统化学习路线，涵盖算法、数据结构、系统设计等核心主题
- 包含每日学习计划、视频资源、书籍推荐及编程练习
- 支持多语言翻译（包括简体中文），降低非英语用户的学习门槛

**技术亮点**: 基于作者成功入职亚马逊的实战经验整理，重点覆盖大厂面试高频考点（如Big-O分析、哈希表、树等），并整合社区资源（如roadmap.sh计算机科学路线图）。

---
## 10. [github/copilot-sdk](https://github.com/github/copilot-sdk)
- **语言**: Java
- **Stars**: 8,991
- **简介**: Multi-platform SDK for integrating GitHub Copilot Agent into apps and services

### AI 总结
**简介**: GitHub Copilot SDK 是一个多平台开发工具包，允许开发者将 Copilot 的代理工作流集成到各种应用中，支持 Python、TypeScript、Go、.NET、Java 和 Rust 等多种语言。

**核心功能**:
- 提供与 Copilot CLI 相同的生产级代理运行时，支持程序化调用
- 支持定义代理行为，自动处理规划、工具调用、文件编辑等任务
- 跨平台支持，覆盖 Node.js/TypeScript、Python、Go、.NET、Rust 和 Java

**技术亮点**: 基于 GitHub Copilot 引擎，采用多语言 SDK 架构（Java 为 Maven/Gradle 兼容），附带 Cookbook 示例文档，简化集成流程。

---
