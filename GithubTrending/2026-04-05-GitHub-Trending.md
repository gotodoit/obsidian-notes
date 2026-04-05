---
tags:
  - github-trending
  - daily
date: 2026-04-05
created: 2026-04-05T01:55:45.702Z
---

# 2026-04-05 GitHub Trending Top 8

## 1. [Blaizzy/mlx-vlm](https://github.com/Blaizzy/mlx-vlm)
- **语言**: Python
- **Stars**: 3,614
- **简介**: MLX-VLM is a package for inference and fine-tuning of Vision Language Models (VLMs) on your Mac using MLX.

### AI 总结
**简介**: MLX-VLM 是一个基于苹果 MLX 框架的 Python 包，用于在 Mac 上进行视觉语言模型和全模态模型的推理与微调。

**核心功能**:
- **多模态推理**：支持图像、音频以及图像+音频的联合输入，进行文本生成。
- **多种使用方式**：提供命令行接口、基于 Gradio 的聊天界面以及 Python API，方便不同场景下的调用。
- **模型微调**：支持对视觉语言模型进行微调。
- **广泛的模型支持**：内置对 DeepSeek-OCR、Phi-4、Gemma 4、Granite Vision 等众多流行模型的支持，并提供详细的模型专属文档。

**技术亮点**:
- **基于 MLX 框架**：专为苹果芯片优化，能在 Mac 上实现高效的本地运行。
- **高级推理特性**：支持“思维预算”控制（用于链式思考模型）、视觉特征缓存、TurboQuant KV 缓存和激活量化（CUDA）等技术，以提升性能和效率。

---
## 2. [onyx-dot-app/onyx](https://github.com/onyx-dot-app/onyx)
- **语言**: Python
- **Stars**: 24,280
- **简介**: Open Source AI Platform - AI Chat with advanced features that works with every LLM

### AI 总结
**简介**: Onyx 是一个开源的 AI 平台，提供了一个功能丰富的界面，可与任何大型语言模型配合工作，并支持一键部署。

**核心功能**:
- **智能检索与问答**：提供基于混合索引和AI代理的增强检索生成能力。
- **深度研究**：支持多步骤研究流程，生成深度报告。
- **自定义智能体**：可构建具有独特指令、知识和操作能力的AI代理。
- **网络搜索**：集成多种搜索引擎和网络爬虫，获取最新信息。
- **文件与代码处理**：支持生成可下载的文档、图形，并在沙箱中执行代码。
- **多模态交互**：具备语音聊天和图像生成功能。
- **扩展与集成**：通过内置50+连接器或模型上下文协议与外部应用交互。

**技术亮点**: 支持 Docker、Kubernetes、Helm/Terraform 等多种部署方式；提供标准版和轻量版两种部署模式以适应不同资源需求；兼容所有主流LLM提供商（如 Ollama、OpenAI、Anthropic 等）；企业级功能包括单点登录、基于角色的访问控制和团队协作。

---
## 3. [Yeachan-Heo/oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex)
- **语言**: TypeScript
- **Stars**: 15,689
- **简介**: OmX - Oh My codeX: Your codex is not alone. Add hooks, agent teams, HUDs, and so much more.

### AI 总结
**简介**: oh-my-codex (OMX) 是一个为 OpenAI Codex CLI 构建的工作流增强层，旨在通过预设的智能工作流、可复用的技能和角色，以及持久化的项目状态管理，提升 Codex 的开发体验和效率。

**核心功能**:
- 提供标准化的智能工作流，包含 `$deep-interview`（深度澄清）、`$ralplan`（计划审批）、`$team`（团队并行执行）和 `$ralph`（持久化完成循环）等核心技能。
- 支持通过 `.omx/` 目录持久化存储项目指导、计划、日志和运行状态。
- 允许通过 `AGENTS.md` 文件定义项目范围内的专家角色和指导。

**技术亮点**: 基于 TypeScript 开发，作为 Node.js (>=20) 的全局命令行工具，与 OpenAI Codex CLI 深度集成，通过预设的提示词和工作流来增强 Codex 的执行引擎。

---
## 4. [siddharthvaddem/openscreen](https://github.com/siddharthvaddem/openscreen)
- **语言**: TypeScript
- **Stars**: 20,034
- **简介**: Create stunning demos for free. Open-source, no subscriptions, no watermarks, and free for commercial use. An alternative to Screen Studio.

### AI 总结
**简介**: OpenScreen 是一个免费、开源的屏幕录制与演示制作工具，可作为 Screen Studio 的轻量级替代品，用于创建美观的产品演示和操作教程。

**核心功能**:
- 录制全屏或指定窗口，支持麦克风和系统音频捕获。
- 提供自动或手动缩放功能，可自定义缩放深度、时长和位置。
- 支持视频裁剪、背景自定义（壁纸、纯色、渐变）、运动模糊效果。
- 可添加文本、箭头、图片等标注，并支持剪辑片段修剪与分段速度调整。
- 支持多种宽高比和分辨率导出。

**技术亮点**: 基于 Electron、React、TypeScript、Vite、PixiJS 和 dnd-timeline 构建，跨平台支持 macOS、Windows 和 Linux。

---
## 5. [telegramdesktop/tdesktop](https://github.com/telegramdesktop/tdesktop)
- **语言**: C++
- **Stars**: 30,841
- **简介**: Telegram Desktop messaging app

### AI 总结
**简介**: Telegram Desktop 是 Telegram 官方推出的跨平台桌面端即时通讯应用，基于 Telegram API 和 MTProto 安全协议。

**核心功能**:
- 官方 Telegram 桌面客户端，支持消息、媒体、群组和频道等完整通讯功能。
- 提供 Windows、macOS 和 Linux 等多平台支持，包括便携版本。
- 支持较旧的系统版本（如 Windows XP、macOS 10.6 等），有对应的历史版本存档。

**技术亮点**:
- 使用 C++ 编写，基于 Qt 框架构建用户界面。
- 核心依赖 Telegram API 和 MTProto 协议确保通讯安全。
- 集成了众多高质量第三方库，如 OpenSSL（加密）、WebRTC（实时通信）、FFmpeg（媒体处理）、CMake（构建系统）等。
- 项目采用 GPLv3 许可证（附带 OpenSSL 例外），并提供详细的各平台构建指南。

---
## 6. [block/goose](https://github.com/block/goose)
- **语言**: Rust
- **Stars**: 35,716
- **简介**: an open source, extensible AI agent that goes beyond code suggestions - install, execute, edit, and test with any LLM

### AI 总结
**简介**: Goose 是一个用 Rust 编写的开源、可扩展的本地 AI 智能体，能够自主自动化复杂的开发任务。

**核心功能**:
- 超越代码建议，能够从零开始构建项目、编写和执行代码、调试故障。
- 编排工作流并与外部 API 交互，实现任务自动化。
- 支持多模型配置，可与任何 LLM 配合使用以优化性能和成本。
- 无缝集成 MCP 服务器，提供桌面应用和 CLI 两种使用方式。

**技术亮点**: 基于 Rust 开发，采用多模型架构，支持通过 MCP 服务器进行扩展，并允许构建自定义发行版。

---
## 7. [microsoft/agent-framework](https://github.com/microsoft/agent-framework)
- **语言**: Python
- **Stars**: 8,714
- **简介**: A framework for building, orchestrating and deploying AI agents and multi-agent workflows with support for Python and .NET.

### AI 总结
**简介**: Microsoft Agent Framework 是一个由微软推出的、支持 Python 和 .NET 的多语言框架，用于构建、编排和部署从简单聊天代理到复杂多代理工作流的 AI 智能体。

**核心功能**:
- **图基工作流**：支持基于数据流连接代理和确定性函数，具备流式处理、检查点、人工干预和时间旅行能力。
- **多语言支持**：提供 Python 和 C#/.NET 的完整框架支持，并保持一致的 API。
- **可观测性**：内置 OpenTelemetry 集成，便于分布式追踪、监控和调试。
- **多代理提供商支持**：支持多种大语言模型提供商，并持续扩展。
- **中间件系统**：灵活的中间件系统，用于请求/响应处理、异常处理和自定义管道。
- **开发者工具**：提供交互式开发界面（DevUI）用于开发、测试和调试工作流。

**技术亮点**: 框架包含实验性的 AF Labs 包，用于前沿功能探索（如基准测试、强化学习）；提供从 Semantic Kernel 和 AutoGen 的迁移指南；并采用模块化设计，便于安装和使用。

---
## 8. [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock)
- **语言**: Python
- **Stars**: 79,389
- **简介**: Hunt down social media accounts by username across social networks

### AI 总结
**简介**: 一个用于通过用户名在多个社交网络上查找对应账户的 Python 工具。

**核心功能**:
- 支持在数百个社交网络和网站上搜索指定用户名。
- 提供命令行界面，可一次性搜索多个用户名，并支持多种输出格式（文本、JSON、HTML、CSV）。
- 支持使用 Tor 网络进行匿名查询。

**技术亮点**: 基于 Python 开发，使用 `requests` 和 `colorama` 等库，支持异步操作以提高搜索速度，并可通过 Docker 容器化部署。

---
