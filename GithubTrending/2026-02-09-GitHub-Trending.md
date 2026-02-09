---
tags:
  - github-trending
  - daily
date: 2026-02-09
created: 2026-02-09T10:00:16.699Z
---

# 2026-02-09 GitHub Trending Top 10

## 1. [KeygraphHQ/shannon](https://github.com/KeygraphHQ/shannon)
- **语言**: TypeScript
- **Stars**: 15,024
- **简介**: Fully autonomous AI hacker to find actual exploits in your web apps. Shannon has achieved a 96.15% success rate on the hint-free, source-aware XBOW Benchmark.

### AI 总结
**简介**: Shannon 是一个完全自主的 AI 渗透测试工具，旨在通过分析源代码并执行真实攻击来发现 Web 应用中的实际可利用漏洞。

**核心功能**:
- **全自主操作**：单命令启动，AI 自动处理包括 2FA/TOTP 登录、浏览器导航在内的所有测试步骤。
- **提供可复现的渗透报告**：生成包含已验证漏洞和可直接复现的攻击证明（PoC）的报告，减少误报。
- **覆盖关键 OWASP 漏洞**：当前专注于检测和验证注入、XSS、SSRF 及身份验证/授权绕过等漏洞。
- **代码感知的动态测试**：结合源代码分析与动态浏览器/命令行攻击，智能引导攻击策略。
- **集成安全工具**：利用 Nmap、Subfinder、WhatWeb、Schemathesis 等工具进行深度环境侦察。
- **并行处理**：并行执行分析和攻击阶段，以加快测试速度。

**技术亮点**: 基于 TypeScript 开发，采用白盒测试方法，其专业版（Shannon Pro）集成了受 LLMDFA 论文启发的、由 LLM 驱动的数据流分析引擎，用于企业级代码分析。

---
## 2. [pydantic/monty](https://github.com/pydantic/monty)
- **语言**: Rust
- **Stars**: 3,362
- **简介**: A minimal, secure Python interpreter written in Rust for use by AI

### AI 总结
**简介**: Monty 是一个用 Rust 编写的、极简且安全的 Python 解释器，专为 AI 代理运行其生成的代码而设计。

**核心功能**:
*   运行一个合理的 Python 代码子集，足以满足 AI 代理的表达需求。
*   完全隔离宿主环境：文件系统、环境变量和网络访问均通过开发者可控的外部函数调用实现。
*   可调用宿主提供的函数，且仅限授权函数。
*   支持完整的现代 Python 类型提示，并内置 `ty` 工具进行类型检查。
*   可在外部函数调用处将解释器状态快照为字节，支持存储和后续恢复。
*   启动极快（从代码到执行结果 <1μs），运行时性能与 CPython 相近。
*   可从 Rust、Python 或 JavaScript 调用，无 CPython 依赖。
*   可控制资源使用：跟踪内存、分配、栈深度和执行时间，并在超出预设限制时取消执行。
*   收集 `stdout` 和 `stderr` 并返回给调用者。
*   支持通过宿主代码运行异步或同步代码。

**技术亮点**:
*   **语言/架构**: 使用 Rust 编写，确保内存安全和性能。
*   **安全性**: 通过沙箱机制和严格的资源/环境控制，安全地执行不受信任的 AI 生成代码。
*   **轻量级**: 极简设计，避免了基于完整容器的沙箱方案带来的开销和复杂性。
*   **跨语言**: 提供 Python、JavaScript/TypeScript 和 Rust 的调用接口，易于集成。

---
## 3. [openai/skills](https://github.com/openai/skills)
- **语言**: Python
- **Stars**: 7,288
- **简介**: Skills Catalog for Codex

### AI 总结
**简介**: OpenAI 为 Codex 构建的一个可复用 AI 代理技能目录，包含指令、脚本和资源。

**核心功能**:
- **技能目录**：提供预置的 `.system`、`.curated` 和 `.experimental` 三类技能，供 AI 代理发现和使用。
- **技能安装**：支持通过 `$skill-installer` 命令或 GitHub 目录 URL 在 Codex 中便捷安装技能。
- **标准化与复用**：遵循 Agent Skills 开放标准，实现“一次编写，随处使用”的团队协作能力封装。

**技术亮点**: 基于 Python，采用模块化文件夹结构组织技能，并通过明确的安装流程和许可文件（LICENSE.txt）管理技能生命周期。

---
## 4. [virattt/dexter](https://github.com/virattt/dexter)
- **语言**: TypeScript
- **Stars**: 13,085
- **简介**: An autonomous agent for deep financial research

### AI 总结
**简介**: Dexter 是一个用 TypeScript 编写的自主金融研究智能体，能够将复杂的金融问题分解为结构化任务，并利用实时市场数据进行分析、验证和迭代，最终提供数据支持的答案。

**核心功能**:
- **智能任务规划**：自动将复杂查询分解为结构化的研究步骤。
- **自主执行**：选择并调用合适的工具来收集金融数据。
- **自我验证**：检查自身工作并进行迭代，直至任务完成。
- **实时数据接入**：访问损益表、资产负债表和现金流量表等市场数据。
- **安全控制**：内置循环检测和步骤限制，防止无限执行。

**技术亮点**:
- 基于 Bun 运行时和 TypeScript 开发。
- 支持多种 AI 模型 API（OpenAI、Anthropic、Google、XAI、OpenRouter）及本地 Ollama。
- 集成专业金融数据源（Financial Datasets API）和网络搜索（Exa/Tavily）。
- 包含基于 LangSmith 的评估套件和 LLM-as-judge 评分机制。
- 提供详细的调试日志（JSONL 格式的暂存器文件），记录完整的工具调用和推理过程。

---
## 5. [microsoft/litebox](https://github.com/microsoft/litebox)
- **语言**: Rust
- **Stars**: 1,588
- **简介**: A security-focused library OS supporting kernel- and user-mode execution

### AI 总结
**简介**: LiteBox 是一个专注于安全的库操作系统，旨在通过大幅缩减与主机的接口来减少攻击面，支持内核模式和非内核模式执行。

**核心功能**:
- 提供类似 `nix`/`rustix` 的 Rust 风格“北向”接口，并支持多种“南向”平台接口。
- 支持跨平台运行未修改的 Linux 程序（例如在 Windows 上运行 Linux 程序）。
- 提供沙箱功能，可在 Linux 上安全运行 Linux 应用程序。
- 支持在 SEV SNP、OP-TEE 和 LVBS 等平台上运行程序。

**技术亮点**: 采用 Rust 语言编写，设计灵活，支持多种北向-南向接口组合，便于在不同场景下实现互操作性。

---
## 6. [google/langextract](https://github.com/google/langextract)
- **语言**: Python
- **Stars**: 25,017
- **简介**: A Python library for extracting structured information from unstructured text using LLMs with precise source grounding and interactive visualization.

### AI 总结
**简介**: LangExtract 是一个由 Google 开源的 Python 库，利用大语言模型从非结构化文本中提取结构化信息。

**核心功能**:
- **精准溯源**：将提取的每个实体映射回原文中的确切位置，支持可视化高亮，便于追溯和验证。
- **可靠的结构化输出**：基于用户提供的少量示例强制执行一致的输出模式，确保结果结构稳定。
- **长文档优化**：通过优化的文本分块、并行处理和多轮处理策略，有效应对大文档中的信息提取挑战。
- **交互式可视化**：可即时生成独立的交互式 HTML 文件，用于在原始上下文中查看和审查数千个提取的实体。
- **灵活的 LLM 支持**：支持多种模型，从云端 LLM（如 Google Gemini 系列）到通过内置 Ollama 接口运行的本地开源模型。
- **领域自适应**：仅需少量示例即可为任何领域定义提取任务，无需对模型进行微调。

**技术亮点**: 该库基于 Python，利用 LLM 的世界知识，通过精心设计的提示词和少样本示例来引导模型行为，并强调提取的准确性依赖于所选模型、任务复杂度及提示的清晰度。

---
## 7. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 48,192
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个基于可组合“技能”和初始指令构建的、用于编码智能体的完整软件开发工作流框架。

**核心功能**:
- **智能规划与设计**：通过对话提炼需求，分块呈现设计文档供确认，并制定详细的、遵循TDD/YAGNI/DRY原则的实现计划。
- **子智能体驱动开发**：在计划批准后，启动子智能体流程，让智能体自主执行每个工程任务，并进行检查和评审，可实现数小时的自主工作。
- **自动化技能触发**：提供涵盖测试、调试、协作的丰富技能库（如测试驱动开发、系统化调试、代码评审等），并在任务前自动检查并触发相关技能，形成强制性工作流。

**技术亮点**: 基于Shell脚本，通过插件系统（支持Claude Code、Codex、OpenCode等平台）集成，强调可组合的“技能”架构和子智能体（subagent）协作模式。

---
## 8. [OpenBMB/MiniCPM-o](https://github.com/OpenBMB/MiniCPM-o)
- **语言**: Python
- **Stars**: 23,536
- **简介**: A Gemini 2.5 Flash Level MLLM for Vision, Speech, and Full-Duplex Multimodal Live Streaming on Your Phone

### AI 总结
**简介**: MiniCPM-o 是一个能在手机上运行的、性能接近 Gemini 2.5 Flash 的多模态大语言模型系列，支持图像、视频、文本和音频输入，并提供高质量的文本与语音输出。

**核心功能**:
- **全双工多模态实时流**：支持实时视频、音频输入与语音、文本输出同时进行，互不阻塞，可实现“边看、边听、边说”的实时全模态对话和主动交互。
- **强大的多模态理解与生成**：具备卓越的视觉理解（如OCR）、语音对话（支持双语实时对话和语音克隆）及文本生成能力。
- **高效的端侧部署**：模型参数量小（如4.5版本为90亿参数），专为在手机等设备上进行高性能、高效率的本地部署而设计。

**技术亮点**:
- 模型架构针对强性能与高效部署优化，并配套发布了高性能的 `llama.cpp-omni` 推理框架和 WebRTC 演示，支持在 Mac 等本地设备上进行低延迟的全双工通信体验。

---
## 9. [likec4/likec4](https://github.com/likec4/likec4)
- **语言**: TypeScript
- **Stars**: 2,496
- **简介**: Visualize, collaborate, and evolve the software architecture with always actual and live diagrams from your code

### AI 总结
**简介**: LikeC4 是一个基于代码的软件架构建模语言和工具集，能够从代码中生成实时、最新的架构图，实现架构的可视化、协作与演进。

**核心功能**:
- 提供一种建模语言，用于描述软件架构。
- 从架构模型自动生成并实时更新架构图。
- 支持自定义符号、元素类型和多层嵌套架构模型，灵活适应不同需求。
- 提供 VSCode 扩展、CLI 工具、在线 Playground 和演示模板。

**技术亮点**: 基于 TypeScript 开发，灵感来源于 C4 模型和 Structurizr DSL，但提供了更高的自定义灵活性。

---
## 10. [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi)
- **语言**: TypeScript
- **Stars**: 13,494
- **简介**: Free, local, open-source 24/7 Cowork and OpenClaw for Gemini CLI, Claude Code, Codex, OpenCode, Qwen Code, Goose CLI, Auggie, and more | 🌟 Star if you like it!

### AI 总结
**简介**: AionUi 是一款免费、本地化、开源的 AI 协作工具，为多种命令行 AI 工具（如 Gemini CLI、Claude Code 等）提供统一的图形化界面，支持 7x24 小时远程访问和自动化任务。

**核心功能**:
- **多智能体模式与统一界面**：自动检测本地已安装的 CLI AI 工具（如 Gemini CLI、Claude Code），并提供统一的图形化操作界面，告别命令行。
- **随时随地远程访问**：支持通过 WebUI 浏览器、Telegram、飞书等多种方式从任何设备远程访问和使用你的 AI 助手。
- **计划任务与自动化**：可设置定时任务，让 AI 助手在指定时间自动执行工作，实现全天候无人值守运行。

**技术亮点**: 基于 TypeScript 开发，跨平台（支持 macOS、Windows、Linux），采用本地数据存储保障安全，支持多会话并行与独立上下文管理。

---
