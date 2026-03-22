---
tags:
  - github-trending
  - daily
date: 2026-03-22
created: 2026-03-22T01:55:46.939Z
---

# 2026-03-22 GitHub Trending Top 9

## 1. [FujiwaraChoki/MoneyPrinterV2](https://github.com/FujiwaraChoki/MoneyPrinterV2)
- **语言**: Python
- **Stars**: 17,820
- **简介**: Automate the process of making money online.

### AI 总结
**简介**: MoneyPrinterV2 是一个用 Python 编写的自动化在线赚钱应用程序，是原项目的完全重写版本，具有更广泛的功能和模块化架构。

**核心功能**:
- Twitter 机器人（支持定时任务调度）
- YouTube Shorts 自动化发布（支持定时任务调度）
- 联盟营销（结合亚马逊与 Twitter）
- 寻找本地企业并进行冷启动推广

**技术亮点**: 采用模块化架构，支持通过脚本直接调用核心功能，需 Python 3.12 环境运行。

---
## 2. [systemd/systemd](https://github.com/systemd/systemd)
- **语言**: C
- **Stars**: 15,730
- **简介**: The systemd System and Service Manager

### AI 总结
**简介**: systemd 是一个用于 Linux 系统的系统和服务管理器。

**核心功能**:
- 作为系统初始化进程，负责引导用户空间并管理系统服务。
- 提供强大的服务管理能力，包括服务依赖、并行启动和进程监控。

**技术亮点**:
- 项目采用 C 语言编写，遵循严格的编码风格指南。
- 拥有完善的持续集成（CI）流程、安全漏洞赏金计划以及广泛的文档和社区支持。

---
## 3. [aquasecurity/trivy](https://github.com/aquasecurity/trivy)
- **语言**: Go
- **Stars**: 33,381
- **简介**: Find vulnerabilities, misconfigurations, secrets, SBOM in containers, Kubernetes, code repositories, clouds and more

### AI 总结
**简介**: Trivy 是一款由 Aqua Security 开发、使用 Go 语言编写的全面且多功能的开源安全扫描器。

**核心功能**:
- **支持多种扫描目标**：可扫描容器镜像、文件系统、Git 仓库、虚拟机镜像和 Kubernetes 集群。
- **提供全面的安全扫描**：能够发现操作系统包和软件依赖（SBOM）、已知漏洞（CVE）、基础设施即代码（IaC）问题与错误配置、敏感信息和密钥泄露，以及软件许可证问题。

**技术亮点**:
- 采用 Go 语言开发，具有良好的跨平台性和性能。
- 提供多种便捷的安装方式（如 Homebrew、Docker、二进制包）和丰富的平台集成（如 GitHub Actions、Kubernetes Operator、VS Code 插件）。
- 支持通过 Canary 版本快速获取最新功能（但不建议用于生产环境）。

---
## 4. [Crosstalk-Solutions/project-nomad](https://github.com/Crosstalk-Solutions/project-nomad)
- **语言**: TypeScript
- **Stars**: 6,829
- **简介**: Project N.O.M.A.D, is a self-contained, offline survival computer packed with critical tools, knowledge, and AI to keep you informed and empowered—anytime, anywhere.

### AI 总结
**简介**: Project N.O.M.A.D. 是一个自包含、离线优先的知识与教育服务器，集成了关键工具、知识和AI，旨在让用户随时随地获取信息并保持自主能力。

**核心功能**:
- **AI聊天与知识库**：基于 Ollama 和 Qdrant 的本地AI聊天，支持文档上传和语义搜索。
- **离线信息库**：通过 Kiwix 提供离线版维基百科、医学参考、电子书等资源。
- **教育平台**：集成 Kolibri，提供可汗学院课程与进度跟踪。
- **离线地图**：使用 ProtoMaps 提供可下载的区域地图。
- **数据工具**：集成 CyberChef，用于加密、编码、哈希和数据分析。
- **笔记系统**：基于 FlatNotes 的本地Markdown笔记。
- **系统基准测试**：硬件性能评分与社区排行榜。

**技术亮点**: 项目采用 TypeScript 开发，核心是一个基于 Docker 容器编排的管理UI（“指挥中心”）和API，可统一管理所有工具和资源的安装、配置与更新，实现开箱即用的离线体验。

---
## 5. [opendataloader-project/opendataloader-pdf](https://github.com/opendataloader-project/opendataloader-pdf)
- **语言**: Java
- **Stars**: 7,905
- **简介**: PDF Parser for AI-ready data. Automate PDF accessibility. Open-source.

### AI 总结
**简介**: 一个开源的 Java PDF 解析器，专注于为 AI 应用提取结构化数据并自动化 PDF 无障碍（可访问性）处理。

**核心功能**:
- **AI 数据提取**：将 PDF（包括数字版、扫描版、已标记版）转换为 Markdown、JSON（带元素边界框）、HTML 等格式，适用于 RAG/LLM 管道。
- **PDF 无障碍自动化**：提供端到端的布局分析和自动标记功能，可将未标记的 PDF 转换为符合规范的“标记 PDF”，并计划支持 PDF/UA 导出。

**技术亮点**:
- **高性能与高精度**：在基准测试中综合提取准确率排名第一（0.90），表格提取准确率达 0.93，本地模式处理速度约 0.05 秒/页。
- **混合 AI 模式**：结合确定性本地算法与 AI 模型，以处理复杂页面、扫描件 OCR（支持 80+ 语言）、无边框表格和公式。
- **行业合作与标准**：与 PDF 协会及 veraPDF 开发者合作，遵循“良好标记 PDF”规范，并通过 veraPDF 进行自动化验证。
- **多语言 SDK**：提供 Python、Node.js 和 Java SDK，易于集成。

---
## 6. [jarrodwatts/claude-hud](https://github.com/jarrodwatts/claude-hud)
- **语言**: JavaScript
- **Stars**: 10,470
- **简介**: A Claude Code plugin that shows what's happening - context usage, active tools, running agents, and todo progress

### AI 总结
**简介**: 一个用于 Claude Code 的插件，通过状态栏实时显示会话上下文使用情况、工具活动、运行中的代理和待办事项进度。

**核心功能**:
- **实时状态监控**: 在输入框下方常驻显示项目路径、上下文窗口使用率、API 使用时长和模型信息。
- **活动追踪**: 可视化展示 Claude 的文件读写、搜索等工具活动，以及子代理的运行状态和任务。
- **任务进度跟踪**: 实时显示待办事项列表的完成进度。
- **高度可配置**: 提供多种预设布局（完整/精简/极简），并支持通过命令或配置文件自定义显示内容和样式。

**技术亮点**: 基于 Claude Code 的原生状态栏 API 开发，通过解析标准输入和会话日志流获取实时数据，无需额外窗口或 tmux，更新频率约 300ms。

---
## 7. [protocolbuffers/protobuf](https://github.com/protocolbuffers/protobuf)
- **语言**: C++
- **Stars**: 70,947
- **简介**: Protocol Buffers - Google's data interchange format

### AI 总结
**简介**: Protocol Buffers (protobuf) 是 Google 开发的一种语言中立、平台中立、可扩展的结构化数据序列化机制。

**核心功能**:
- 提供协议编译器，用于将 `.proto` 文件编译成多种编程语言的代码。
- 为多种编程语言（如 C++、Java、Python、Go、C# 等）提供运行时库，用于序列化和反序列化结构化数据。

**技术亮点**:
- 支持使用 Bazel（支持 Bzlmod 和传统 WORKSPACE 方式）进行依赖管理和构建。
- 提供预编译的编译器二进制文件，方便非 C++ 用户快速安装使用。
- 强调版本稳定性，建议用户使用官方发布版本而非主分支，以避免不兼容的变更。

---
## 8. [vllm-project/vllm-omni](https://github.com/vllm-project/vllm-omni)
- **语言**: Python
- **Stars**: 3,517
- **简介**: A framework for efficient model inference with omni-modality models

### AI 总结
**简介**: vLLM-Omni 是一个基于 vLLM 的高效全模态模型推理与部署框架，旨在为所有人提供简单、快速且低成本的全模态模型服务。

**核心功能**:
- **全模态支持**: 支持文本、图像、视频和音频数据的处理与生成。
- **非自回归架构扩展**: 在 vLLM 自回归生成的基础上，扩展支持扩散变换器（DiT）等并行生成模型。
- **异构输出**: 能够生成从传统文本到多模态内容的多样化输出。
- **灵活易用**: 提供异构流水线抽象，无缝集成 Hugging Face 模型，支持多种并行策略和 OpenAI 兼容的 API 服务器。

**技术亮点**:
- **高性能**: 利用 vLLM 高效的 KV 缓存管理，并通过流水线阶段执行重叠实现高吞吐。
- **解耦架构**: 基于 OmniConnector 实现完全解耦，支持跨阶段的动态资源分配。
- **广泛兼容**: 支持 CUDA、ROCm、NPU、XPU 等多种硬件平台，并覆盖 Qwen-Omni、Bagel、MiMo-Audio、GLM-Image 等主流开源模型。

---
## 9. [louis-e/arnis](https://github.com/louis-e/arnis)
- **语言**: Rust
- **Stars**: 12,236
- **简介**: Generate any location from the real world in Minecraft with a high level of detail.

### AI 总结
**简介**: Arnis 是一个用 Rust 编写的开源工具，能够利用真实世界的地理和建筑数据，在 Minecraft 中生成高度精细且准确的地形与世界。

**核心功能**:
- 基于 OpenStreetMap 的地理空间数据和海拔数据，生成反映真实世界地理、地形和建筑的 Minecraft 世界（支持 Java 版 1.17+ 和基岩版）。
- 提供图形用户界面，允许用户通过地图矩形工具选择区域，并自定义生成设置（如世界比例、出生点、建筑内部生成等）。
- 支持通过命令行或 Nix 直接运行，进行无头生成，便于自动化或高级使用。

**技术亮点**:
- **模块化架构**：将数据获取、处理和世界生成等组件清晰分离，以提高可维护性和可扩展性。
- **跨平台支持**：旨在在 Windows、macOS 和 Linux 上流畅运行。
- **性能优化**：注重保持世界生成过程的速度和性能。
- **全面的文档**：提供详细的 GitHub Wiki，涵盖技术解释、FAQ、贡献指南和路线图。

---
