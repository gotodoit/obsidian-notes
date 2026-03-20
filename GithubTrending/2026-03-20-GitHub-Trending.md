---
tags:
  - github-trending
  - daily
date: 2026-03-20
created: 2026-03-20T01:55:49.271Z
---

# 2026-03-20 GitHub Trending Top 10

## 1. [opendataloader-project/opendataloader-pdf](https://github.com/opendataloader-project/opendataloader-pdf)
- **语言**: Java
- **Stars**: 5,756
- **简介**: PDF Parser for AI-ready data. Automate PDF accessibility. Open-source.

### AI 总结
**简介**: 一个开源的 PDF 解析器，专注于为 AI 应用提取结构化数据并自动化 PDF 无障碍（可访问性）处理。

**核心功能**:
- **AI 数据提取**：支持从数字、扫描或已标记的 PDF 中提取 Markdown、JSON（带元素边界框）、HTML 等格式，为 RAG/LLM 管道提供数据。
- **PDF 无障碍自动化**：提供端到端的布局分析和自动标记功能，可将未标记的 PDF 转换为符合标准的“已标记 PDF”，以支持无障碍合规。

**技术亮点**:
- **高性能与高精度**：在基准测试中综合提取准确率排名第一（0.90），表格提取准确率达 0.93，本地模式处理速度达 0.05 秒/页。
- **混合 AI 模式**：结合确定性本地处理与 AI 增强，以处理复杂页面、扫描件、无边框表格和公式。
- **开放标准与验证**：与 PDF 协会及 veraPDF 团队合作，遵循“良好标记 PDF”规范，输出可通过 veraPDF 自动验证。
- **多语言 SDK**：提供 Python、Node.js 和 Java SDK，易于集成。

---
## 2. [langchain-ai/open-swe](https://github.com/langchain-ai/open-swe)
- **语言**: Python
- **Stars**: 7,065
- **简介**: An Open-Source Asynchronous Coding Agent

### AI 总结
**简介**: 一个开源的异步编码代理框架，旨在帮助企业构建内部专用的、可安全集成到现有工作流程（如 Slack、Linear）的智能编码助手。

**核心功能**:
- **代理编排**：基于 Deep Agents 框架构建，可自定义编排逻辑、工具和中间件。
- **云端沙盒**：每个任务在独立的远程 Linux 沙盒环境中运行，提供完全隔离的执行环境，支持 Modal、Daytona 等多种提供商。
- **精选工具集**：提供执行 Shell 命令、读写文件、调用 API、提交代码并创建 GitHub PR、在 Linear 和 Slack 中回复等核心工具。
- **上下文管理**：通过项目内的 `AGENTS.md` 文件和源代码为代理提供任务背景信息。

**技术亮点**:
- 架构基于 **LangGraph** 和 **Deep Agents**，借鉴了 Stripe、Ramp 等公司的内部代理设计模式。
- 采用“先隔离，再授权”的安全原则，所有操作均在沙盒内进行，与生产环境隔离。
- 支持多任务并行执行，每个任务拥有独立的持久化沙盒环境。

---
## 3. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 99,344
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为 AI 编程助手（Agent）设计的、基于可组合“技能”的软件开发框架与工作流。

**核心功能**:
- **引导式设计**：在编码前，通过对话引导用户明确需求，并分块呈现设计文档供确认。
- **结构化实施**：在批准设计后，制定详细的、面向初级工程师的实施计划，强调 TDD、YAGNI 和 DRY 原则。
- **子代理驱动开发**：启动子代理来执行每个工程任务，并进行检查和评审，可实现数小时的自主工作。
- **自动化技能触发**：内置一系列自动化技能（如头脑风暴、TDD、代码审查、分支管理等），在相应场景下自动激活，强制执行标准化工作流。

**技术亮点**: 采用“技能”作为核心构建块，框架与多种主流 AI 编程平台（如 Claude Code、Cursor、Codex、OpenCode、Gemini CLI）集成，提供统一的、可自动触发的 Agentic 开发方法论。

---
## 4. [jarrodwatts/claude-hud](https://github.com/jarrodwatts/claude-hud)
- **语言**: JavaScript
- **Stars**: 8,562
- **简介**: A Claude Code plugin that shows what's happening - context usage, active tools, running agents, and todo progress

### AI 总结
**简介**: 一个用于 Claude Code 的插件，在输入框下方实时显示会话状态，包括上下文使用情况、活跃工具、运行中的代理和待办事项进度。

**核心功能**:
- **状态概览**: 实时显示项目路径、Git分支、当前模型和订阅计划。
- **上下文监控**: 以进度条形式直观展示上下文窗口的占用率，防止溢出。
- **活动追踪**: 监控 Claude 的文件读写、搜索等工具活动，以及子代理的运行状态。
- **进度跟踪**: 实时显示待办任务列表的完成进度。
- **高度可配置**: 提供多种预设布局（完整/精简/极简），并支持通过命令或配置文件深度自定义显示内容和样式。

**技术亮点**: 基于 Claude Code 原生的 `statusline API` 开发，通过解析标准输入（stdin）和会话记录（transcript JSONL）获取数据，无需额外窗口或 tmux，更新频率约 300ms，能准确获取原生令牌数据并适配包括 1M 上下文在内的各种会话规模。

---
## 5. [unslothai/unsloth](https://github.com/unslothai/unsloth)
- **语言**: Python
- **Stars**: 56,738
- **简介**: Unified web UI for training and running open models like Qwen, DeepSeek, gpt-oss and Gemma locally.

### AI 总结
**简介**: Unsloth 是一个用于在本地训练和运行开源大模型（如 Qwen、DeepSeek、Gemma 等）的统一 Web 界面。

**核心功能**:
- **推理**: 支持搜索、下载、运行模型（GGUF、LoRA、safetensors），提供工具调用、代码执行、文件上传聊天等功能，并可自动调整推理参数和导出模型。
- **训练**: 支持对 500 多种模型进行全参数微调、预训练等，训练速度提升最高 2 倍，显存占用减少最高 70%，并提供实时训练监控、可视化数据工作流和多 GPU 训练支持。

**技术亮点**: 提供 Web UI（Unsloth Studio）和代码库（Unsloth Core）两种使用方式，支持跨平台（Windows、Linux、macOS），并针对 NVIDIA、AMD、Apple MLX 等硬件平台进行优化。

---
## 6. [mobile-dev-inc/Maestro](https://github.com/mobile-dev-inc/Maestro)
- **语言**: Kotlin
- **Stars**: 12,465
- **简介**: Painless E2E Automation for Mobile and Web

### AI 总结
**简介**: Maestro 是一个开源的移动端和 Web 端 UI 及端到端测试框架，旨在通过简单的 YAML 语法实现快速、跨平台的自动化测试。

**核心功能**:
- **跨平台覆盖**: 支持在模拟器、仿真器或真实设备上测试 Android、iOS 和 Web 应用（包括 React Native、Flutter 和混合应用）。
- **人性化的 YAML 流程**: 使用 `launchApp`、`tapOn`、`assertVisible` 等直观命令编写测试流程，无需编译，易于上手。
- **强大的稳定性和智能等待**: 内置对测试不稳定性的容忍机制和自动等待功能，无需手动添加 `sleep()` 即可处理动态 UI。
- **快速迭代与简易安装**: 通过单一脚本即可安装，测试流程为解释执行，支持快速编写和运行。

**技术亮点**: 基于 Kotlin 开发，汲取了 Appium、Espresso、UIAutomator、XCTest、Selenium、Playwright 等框架的经验，提供了一个解释型执行引擎。项目还提供了商业化的 Maestro Studio（可视化测试 IDE）和 Maestro Cloud（并行测试云服务）来扩展功能。

---
## 7. [tw93/Mole](https://github.com/tw93/Mole)
- **语言**: Shell
- **Stars**: 41,972
- **简介**: 🐹 Deep clean and optimize your Mac.

### AI 总结
**简介**: Mole 是一个用于深度清理和优化 macOS 系统的 Shell 脚本工具。

**核心功能**:
- **深度清理**: 一键清除系统缓存、日志、浏览器残留文件等，释放大量磁盘空间。
- **智能卸载**: 彻底卸载应用程序及其相关的启动代理、偏好设置和隐藏残留文件。
- **磁盘分析**: 可视化磁盘使用情况，查找大文件，并支持重建缓存、刷新系统服务。
- **实时监控**: 显示 CPU、GPU、内存、磁盘和网络的实时状态仪表盘。
- **安全设计**: 提供 `--dry-run` 预览模式、路径验证、受保护目录规则和操作日志，确保操作安全可控。

**技术亮点**:
- **一体化二进制文件**: 将 CleanMyMac、AppCleaner 等多款工具的功能集成于单个二进制文件中，无需安装依赖。
- **灵活的安装与使用**: 支持通过 Homebrew 或安装脚本快速安装，提供丰富的命令行参数和交互式菜单。
- **注重安全**: 采用保守的清理边界和明确的确认机制，高风险操作前需用户确认，并提供详细的审计和安全文档。

---
## 8. [newton-physics/newton](https://github.com/newton-physics/newton)
- **语言**: Python
- **Stars**: 3,237
- **简介**: An open-source, GPU-accelerated physics simulation engine built upon NVIDIA Warp, specifically targeting roboticists and simulation researchers.

### AI 总结
**简介**: Newton 是一个基于 NVIDIA Warp 构建的开源、GPU 加速的物理模拟引擎，主要面向机器人学和仿真研究领域。

**核心功能**:
- 提供 GPU 加速的物理模拟，支持机器人动力学仿真。
- 集成 MuJoCo Warp 作为其主要后端，并扩展了 Warp 的 `warp.sim` 模块。
- 支持 OpenUSD 格式，便于场景描述和数据交换。
- 支持可微分模拟和用户自定义扩展，便于快速迭代和算法研究。

**技术亮点**:
- **GPU 优先计算**：利用 NVIDIA GPU（Maxwell 架构或更新）进行高性能并行计算。
- **跨平台**：支持 Linux、Windows 和 macOS（CPU 模式）。
- **现代工具链**：推荐使用 `uv` 进行源码安装和管理。
- **社区驱动**：作为 Linux Foundation 项目，由社区共同构建和维护，由 Disney Research、Google DeepMind 和 NVIDIA 共同发起。

---
## 9. [louis-e/arnis](https://github.com/louis-e/arnis)
- **语言**: Rust
- **Stars**: 10,804
- **简介**: Generate any location from the real world in Minecraft with a high level of detail.

### AI 总结
**简介**: 一个用 Rust 编写的开源工具，能够基于真实世界的地理和建筑数据，生成细节丰富、高度准确的《我的世界》Java版和基岩版世界。

**核心功能**:
- 利用 OpenStreetMap 的地理空间数据和海拔数据，生成反映真实世界地形、地貌和建筑结构的《我的世界》世界。
- 提供图形用户界面（GUI），用户可通过地图矩形工具选择区域并自定义生成设置（如世界比例、生成建筑内部等）。
- 支持生成大规模地图，并可通过其在线服务 MapSmith 在浏览器中生成世界，无需安装。

**技术亮点**:
- 采用 Rust 语言开发，注重模块化设计，将数据获取、处理和世界生成等组件清晰分离。
- 专注于性能优化，旨在保持世界生成过程的速度和效率。
- 提供跨平台支持，可在 Windows、macOS 和 Linux 上运行。

---
## 10. [FujiwaraChoki/MoneyPrinterV2](https://github.com/FujiwaraChoki/MoneyPrinterV2)
- **语言**: Python
- **Stars**: 16,098
- **简介**: Automate the process of making money online.

### AI 总结
**简介**: MoneyPrinterV2 是一个用于自动化在线赚钱流程的 Python 应用程序。

**核心功能**:
- Twitter 机器人（支持定时任务调度）
- YouTube Shorts 自动化（支持定时任务调度）
- 联盟营销（结合亚马逊与 Twitter）
- 寻找本地企业并进行冷接触

**技术亮点**: 项目采用模块化架构，是原项目的完全重写版，需要 Python 3.12 环境运行。

---
