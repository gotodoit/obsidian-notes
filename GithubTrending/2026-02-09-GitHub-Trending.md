---
tags:
  - github-trending
  - daily
date: 2026-02-09
created: 2026-02-09T09:07:12.564Z
---

# 2026-02-09 GitHub Trending Top 10

## 1. [KeygraphHQ/shannon](https://github.com/KeygraphHQ/shannon)
- **语言**: TypeScript
- **Stars**: 14,761
- **简介**: Fully autonomous AI hacker to find actual exploits in your web apps. Shannon has achieved a 96.15% success rate on the hint-free, source-aware XBOW Benchmark.

### AI 总结
**简介**: Shannon 是一个完全自主的 AI 渗透测试工具，旨在通过分析源代码并执行真实攻击来发现 Web 应用中的实际可利用漏洞。

**核心功能**:
- **完全自主操作**：单条命令启动渗透测试，AI 自动处理包括 2FA/Google 登录在内的复杂流程，直至生成最终报告。
- **代码感知的动态测试**：结合源代码分析来指导攻击策略，并在运行的应用上通过浏览器和命令行执行真实攻击以验证漏洞。
- **提供可复现的渗透测试报告**：报告专注于已验证的可利用发现，包含可直接复现的漏洞证明，以减少误报。
- **覆盖关键 OWASP 漏洞**：当前可识别并验证注入、XSS、SSRF 及身份验证/授权绕过等关键漏洞。

**技术亮点**:
- 集成多种安全工具（如 Nmap, Subfinder, WhatWeb, Schemathesis）进行深度侦察。
- 采用并行处理架构，以加速分析和漏洞利用阶段。
- 提供两个版本：开源 AGPL-3.0 协议的 **Shannon Lite**（白盒测试）和具备高级数据流分析引擎的商用 **Shannon Pro**。

---
## 2. [pydantic/monty](https://github.com/pydantic/monty)
- **语言**: Rust
- **Stars**: 3,308
- **简介**: A minimal, secure Python interpreter written in Rust for use by AI

### AI 总结
**简介**: Monty 是一个用 Rust 编写的、极简且安全的 Python 解释器，专为 AI 代理运行其生成的代码而设计。

**核心功能**:
- **安全沙箱**: 完全隔离宿主环境（文件系统、环境变量、网络访问），所有外部访问均通过开发者可控的函数调用实现。
- **高性能嵌入**: 启动时间极快（<1微秒），运行时性能与 CPython 相近，可直接嵌入到 Rust、Python 或 JavaScript 应用中。
- **资源与状态控制**: 可监控并限制内存、栈深度和执行时间；支持在执行点将解释器状态快照保存为字节，以便后续恢复。
- **类型检查**: 内置对现代 Python 类型提示的支持，并集成了 `ty` 工具进行类型检查。
- **输出收集**: 能够收集并返回代码执行过程中的标准输出和标准错误。

**技术亮点**:
- 使用 **Rust** 编写，无 CPython 依赖，确保了安全性和跨语言调用能力。
- 架构针对 **AI 代理生成代码** 这一单一场景进行优化，在提供必要功能的同时，刻意不支持标准库（除少数模块）和第三方库，以保持极简与安全。

---
## 3. [openai/skills](https://github.com/openai/skills)
- **语言**: Python
- **Stars**: 7,250
- **简介**: Skills Catalog for Codex

### AI 总结
**简介**: OpenAI 为 Codex 提供的技能目录，包含一系列可供 AI 代理发现和使用的指令、脚本和资源，以实现特定任务。

**核心功能**:
- **技能目录**：提供 `.system`、`.curated` 和 `.experimental` 三类技能，涵盖不同成熟度和用途。
- **技能安装**：支持通过 `$skill-installer` 命令或 GitHub 目录 URL 轻松安装技能。
- **标准化与复用**：遵循 Agent Skills 开放标准，实现“一次编写，随处使用”。

**技术亮点**: 基于 Python 实现，采用模块化文件夹结构组织技能，并与 Codex 深度集成，支持技能的热发现与安装。

---
## 4. [virattt/dexter](https://github.com/virattt/dexter)
- **语言**: TypeScript
- **Stars**: 13,049
- **简介**: An autonomous agent for deep financial research

### AI 总结
**简介**: Dexter 是一个用 TypeScript 编写的自主金融研究智能体，能够将复杂的金融问题分解为结构化任务，并利用实时市场数据进行分析和验证。

**核心功能**:
- **智能任务规划**: 自动将复杂查询分解为分步研究计划。
- **自主执行与验证**: 选择并执行工具以收集金融数据，并能自我检查工作结果并进行迭代优化。
- **实时数据接入**: 可访问损益表、资产负债表和现金流量表等机构级市场数据。
- **安全与可观测性**: 内置循环检测和步骤限制以防止失控执行，并提供详细的运行日志用于调试。

**技术亮点**: 项目基于 Bun 运行时，支持 OpenAI、Anthropic 等多种大模型 API，并集成了 LangSmith 用于评估追踪，采用 LLM-as-judge 方法进行结果评分。

---
## 5. [microsoft/litebox](https://github.com/microsoft/litebox)
- **语言**: Rust
- **Stars**: 1,574
- **简介**: A security-focused library OS supporting kernel- and user-mode execution

### AI 总结
**简介**: LiteBox 是一个专注于安全的库操作系统，旨在通过大幅缩减与主机的接口来减少攻击面，支持内核模式和非内核模式执行。

**核心功能**:
- 提供类似 `nix`/`rustix` 的 Rust 风格“北向”接口，支持多种“南向”平台适配。
- 实现跨平台运行，例如在 Windows 上运行未经修改的 Linux 程序。
- 提供沙箱功能，可在 Linux 上安全运行 Linux 应用程序。
- 支持在 SEV SNP、OP-TEE、LVBS 等平台上运行程序。

**技术亮点**: 采用模块化设计，通过“北向”与“南向”接口的灵活配对，实现广泛的用例兼容性，并使用 Rust 语言编写以提升安全性。

---
## 6. [google/langextract](https://github.com/google/langextract)
- **语言**: Python
- **Stars**: 24,991
- **简介**: A Python library for extracting structured information from unstructured text using LLMs with precise source grounding and interactive visualization.

### AI 总结
**简介**: LangExtract 是一个由 Google 开源的 Python 库，利用大语言模型从非结构化文本中提取结构化信息。

**核心功能**:
- **精准溯源**：将提取的每个信息点精确映射回原文位置，支持可视化高亮，便于追溯和验证。
- **可靠的结构化输出**：基于用户提供的少量示例强制执行一致的输出模式，利用受控生成确保结果结构稳健。
- **长文档优化**：通过优化的文本分块、并行处理和多轮处理策略，解决从大型文档中提取信息的“大海捞针”难题。
- **交互式可视化**：即时生成独立的交互式 HTML 文件，用于在原始上下文中查看和审查数千个提取的实体。
- **灵活的 LLM 支持**：支持多种模型，从云端 LLM（如 Google Gemini 系列）到通过内置 Ollama 接口运行的开源本地模型。
- **领域自适应**：仅需少量示例即可为任何领域定义提取任务，无需对模型进行微调。

**技术亮点**: 采用基于提示词和少样本示例的指令驱动提取，结合文本分块与并行处理技术以高效处理长文档。

---
## 7. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 48,155
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个基于可组合“技能”的智能体驱动软件开发框架与工作流，旨在引导编码智能体（如 Claude）进行系统化、高质量的软件开发。

**核心功能**:
- **智能设计引导**：通过“头脑风暴”技能，在编码前与用户对话，提炼需求并分块呈现设计方案供确认。
- **结构化实施**：在批准设计后，自动生成包含具体文件路径和验证步骤的详细实施计划。
- **子智能体驱动开发**：将计划分解为小任务，为每个任务启动独立的子智能体执行，并包含两阶段代码审查。
- **强制测试驱动开发**：在实现过程中强制执行“红-绿-重构”的 TDD 循环，确保测试先行。
- **集成 Git 工作流**：自动创建隔离的 Git 工作树分支，并在开发完成后提供合并、PR 等清理选项。

**技术亮点**: 该框架构建了一套自动触发的强制性技能工作流，将软件工程最佳实践（如 TDD、YAGNI、DRY）与多智能体协作（子智能体开发、并行派遣）相结合，实现了长时间自主、不偏离计划的开发过程。

---
## 8. [OpenBMB/MiniCPM-o](https://github.com/OpenBMB/MiniCPM-o)
- **语言**: Python
- **Stars**: 23,525
- **简介**: A Gemini 2.5 Flash Level MLLM for Vision, Speech, and Full-Duplex Multimodal Live Streaming on Your Phone

### AI 总结
**简介**: MiniCPM-o 是一个能在手机上运行的、性能接近 Gemini 2.5 Flash 的多模态大语言模型系列，支持图像、视频、文本、音频输入以及文本和语音输出。

**核心功能**:
- **全双工多模态实时流式交互**: 支持实时视频、音频输入与语音、文本输出同时进行，互不阻塞，可实现“边看、边听、边说”的实时全模态对话和主动交互。
- **强大的多模态理解与生成**: 具备优秀的视觉理解（如OCR）、多语言支持和高质量、自然的双语实时语音对话及语音克隆能力。
- **高效的端侧部署**: 模型参数量小（如4B/9B），架构高效，专为在手机等设备上进行高性能、低延迟的本地部署而设计。

**技术亮点**:
- 采用端到端模型架构，统一处理多种模态的输入与输出。
- 配套发布了高性能的 `llama.cpp-omni` 推理框架和基于 WebRTC 的演示，支持在 Mac 等本地设备上进行低延迟的全双工通信体验。
- 使用了 RLAIF-V 对齐技术，相关研究成果被 CVPR 2025 收录。

---
## 9. [likec4/likec4](https://github.com/likec4/likec4)
- **语言**: TypeScript
- **Stars**: 2,485
- **简介**: Visualize, collaborate, and evolve the software architecture with always actual and live diagrams from your code

### AI 总结
**简介**: LikeC4 是一个“架构即代码”的工具，通过代码生成实时、可协作的软件架构图。

**核心功能**:
- 提供一种建模语言，用于描述软件架构，并支持从模型生成图表。
- 支持自定义或定义自己的符号、元素类型和任意数量的嵌套架构层级。
- 提供 CLI 工具、VS Code 扩展和在线 Playground，方便本地预览和在线体验。

**技术亮点**: 基于 TypeScript 开发，灵感来源于 C4 模型和 Structurizr DSL，但提供了更高的灵活性。

---
## 10. [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi)
- **语言**: TypeScript
- **Stars**: 13,460
- **简介**: Free, local, open-source 24/7 Cowork and OpenClaw for Gemini CLI, Claude Code, Codex, OpenCode, Qwen Code, Goose CLI, Auggie, and more | 🌟 Star if you like it!

### AI 总结
**简介**: AionUi 是一个免费、本地化、开源的图形界面工具，为多种命令行AI工具（如Gemini CLI、Claude Code等）提供统一的协作界面，支持7×24小时无人值守运行。

**核心功能**:
- **多智能体模式**：自动检测本地已安装的AI命令行工具，并提供统一的图形界面，告别命令行操作。
- **跨平台远程访问**：支持通过WebUI（浏览器）或集成Telegram、飞书等聊天平台，在任何设备上远程访问和使用AI助手。
- **定时任务**：可设置计划任务，让AI助手在指定时间自动执行工作，实现全天候自动化。

**技术亮点**: 基于TypeScript开发，支持macOS、Windows、Linux多平台，采用本地数据存储保障安全，支持多会话并行管理。

---
