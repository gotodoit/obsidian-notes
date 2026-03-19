---
tags:
  - github-trending
  - daily
date: 2026-03-19
created: 2026-03-19T01:55:47.573Z
---

# 2026-03-19 GitHub Trending Top 6

## 1. [jarrodwatts/claude-hud](https://github.com/jarrodwatts/claude-hud)
- **语言**: JavaScript
- **Stars**: 7,136
- **简介**: A Claude Code plugin that shows what's happening - context usage, active tools, running agents, and todo progress

### AI 总结
**简介**: 一个用于 Claude Code 的插件，在输入框下方实时显示会话状态，包括上下文使用情况、活跃工具、运行中的智能体和任务进度。

**核心功能**:
- **状态概览**: 实时显示项目路径、Git分支、当前模型和计划名称。
- **上下文监控**: 以进度条形式直观展示上下文窗口的使用率，并随使用率变化颜色（绿→黄→红）。
- **活动追踪**: 监控并显示 Claude 的文件读写、搜索等工具活动，以及正在运行的子智能体状态。
- **任务进度**: 实时跟踪待办事项的完成进度。
- **高度可配置**: 提供多种预设布局（完整/精简/极简），并支持通过命令或配置文件深度自定义显示内容和样式。

**技术亮点**: 基于 Claude Code 的原生状态栏 API 开发，通过解析标准输入和会话转录 JSONL 数据来获取信息，无需额外窗口或 tmux，更新频率约 300 毫秒，并能准确适配不同大小的上下文窗口（包括最新的 100 万上下文会话）。

---
## 2. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 96,350
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为 AI 编程代理设计的、基于可组合“技能”的自动化软件开发框架与工作流。

**核心功能**:
- **智能规划与设计**：在编码前，通过对话明确需求，生成并分段展示可审阅的设计规格。
- **子代理驱动开发**：将任务分解为小单元，由独立的子代理执行，并经过两阶段审查（规格符合性、代码质量）。
- **强制执行TDD**：在实现过程中强制进行“红-绿-重构”的测试驱动开发循环。
- **自动化工作流管理**：集成从构思、Git工作树管理、计划执行到代码审查和分支收尾的完整闭环流程。

**技术亮点**: 基于可组合的“技能”库，技能在任务前自动触发，形成一套强制的、非建议性的工作流。支持多平台（Claude Code, Cursor, Codex, OpenCode, Gemini CLI）。

---
## 3. [unslothai/unsloth](https://github.com/unslothai/unsloth)
- **语言**: Python
- **Stars**: 55,872
- **简介**: Unified web UI for training and running open models like Qwen, DeepSeek, gpt-oss and Gemma locally.

### AI 总结
**简介**: Unsloth 是一个用于在本地训练和运行开源大模型（如 Qwen、DeepSeek、Gemma 等）的统一 Web 界面。

**核心功能**:
- **推理**: 支持搜索、下载、运行模型（GGUF、LoRA、safetensors），具备工具调用、代码执行、自动调参、多格式文件上传聊天等功能。
- **训练**: 支持对 500+ 模型进行全参数微调、预训练等，训练速度最高提升 2 倍，显存占用减少高达 70%，并提供实时监控和数据可视化。
- **数据管理**: 提供可视化节点工作流，可从 PDF、CSV 等文件自动创建和编辑训练数据集。
- **多平台与硬件支持**: 支持 Windows、Linux、macOS 系统，兼容 NVIDIA、AMD（部分）和 Apple MLX（即将推出）硬件，并支持多 GPU 训练。

**技术亮点**: 采用高效的训练优化技术（如 4-bit、FP8 训练），显著降低显存消耗；提供统一的 Web UI 和代码库（Core）两种使用方式；支持模型导出为多种格式（GGUF、safetensors）。

---
## 4. [newton-physics/newton](https://github.com/newton-physics/newton)
- **语言**: Python
- **Stars**: 2,927
- **简介**: An open-source, GPU-accelerated physics simulation engine built upon NVIDIA Warp, specifically targeting roboticists and simulation researchers.

### AI 总结
**简介**: Newton 是一个基于 NVIDIA Warp 构建的开源、GPU 加速的物理模拟引擎，主要面向机器人学和仿真研究领域。

**核心功能**:
- 提供 GPU 加速的物理模拟，支持机器人动力学仿真。
- 集成 MuJoCo Warp 作为其主要后端，并扩展了 Warp 的 `warp.sim` 模块。
- 支持 OpenUSD 格式，便于场景描述和资产交换。
- 强调可微分性和用户自定义扩展性，支持快速迭代和可扩展的仿真。

**技术亮点**:
- 基于 NVIDIA Warp 和 CUDA，利用 GPU 进行高性能并行计算。
- 支持 Linux、Windows 和 macOS（CPU 模式）多平台。
- 由 Linux Foundation 托管，社区驱动维护，采用 Apache-2.0 开源协议。
- 由 Disney Research、Google DeepMind 和 NVIDIA 共同发起。

---
## 5. [shadps4-emu/shadPS4](https://github.com/shadps4-emu/shadPS4)
- **语言**: C++
- **Stars**: 29,896
- **简介**: PlayStation 4 emulator for Windows, Linux and macOS written in C++

### AI 总结
**简介**: shadPS4 是一个用 C++ 编写的早期 PlayStation 4 模拟器，支持 Windows、Linux 和 macOS 平台。

**核心功能**:
- 跨平台运行 PlayStation 4 游戏，已成功运行《血源诅咒》、《黑暗之魂：重制版》、《荒野大镖客》等多款游戏。
- 提供命令行核心版本，并推荐用户下载独立的 QtLauncher 以获得图形用户界面。
- 项目处于早期开发阶段，通过 Discord 社区、X（Twitter）和官方网站提供支持与更新。

**技术亮点**:
- 采用 C++ 编写，注重性能与跨平台兼容性。
- 提供详细的构建指南，支持 Docker、Windows、Linux 和 macOS 环境，便于开发者参与贡献。

---
## 6. [langchain-ai/open-swe](https://github.com/langchain-ai/open-swe)
- **语言**: Python
- **Stars**: 6,392
- **简介**: An Open-Source Asynchronous Coding Agent

### AI 总结
**简介**: 一个基于 LangGraph 和 Deep Agents 构建的开源异步编码代理框架，旨在帮助企业构建内部专用的、具备安全边界的智能编码助手。

**核心功能**:
- **代理架构**: 基于 Deep Agents 框架构建，支持自定义编排、工具和中间件，便于升级和定制。
- **隔离沙箱**: 每个任务在独立的云端 Linux 沙箱环境中运行，提供完整的 Shell 权限，确保操作安全隔离。
- **精选工具集**: 提供一套聚焦于开发工作流的核心工具，包括执行 Shell 命令、文件操作、Git 提交与创建 PR、以及与 Slack 和 Linear 等外部系统通信。
- **上下文管理**: 结合项目文档（如 `AGENTS.md`）和源代码为代理提供精准的上下文信息。

**技术亮点**: 基于 LangGraph 和 Deep Agents 框架，支持多沙箱提供商（如 Modal、Daytona），采用异步、并发的任务执行模型。

---
