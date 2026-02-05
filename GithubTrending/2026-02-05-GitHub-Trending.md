---
tags:
  - github-trending
  - daily
date: 2026-02-05
created: 2026-02-05T22:31:48.981Z
---

# 2026-02-05 GitHub Trending Top 10

> [!INFO]
> 本日报由 AI 自动生成，精选 GitHub Trending 前 10 项目。

## 1. [bytedance/UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop)
- **语言**: TypeScript
- **Stars**: 26,670
- **简介**: The Open-Source Multimodal AI Agent Stack: Connecting Cutting-Edge AI Models and Agent Infra

### AI 总结
**简介**: 一个开源的、多模态AI智能体栈，包含Agent TARS和UI-TARS-desktop两个项目，旨在通过前沿的多模态大模型和工具集成，提供更接近人类的任务完成方式。

**核心功能**:
- **Agent TARS**: 提供CLI和Web UI，将GUI智能体和视觉能力集成到终端、计算机、浏览器和产品中，支持与多种现实世界工具（MCP）的无缝集成。
- **UI-TARS-desktop**: 一个桌面应用程序，基于UI-TARS模型提供原生的GUI智能体，支持本地和远程的计算机与浏览器操作员。

**技术亮点**:
- 基于TypeScript开发。
- 支持多模态（GUI、视觉）AI智能体。
- 集成模型上下文协议（MCP）工具，连接现实世界工具。
- 提供AIO智能体沙箱作为隔离的执行环境。
- 包含SDK，用于构建跨平台的GUI自动化智能体。

---
## 2. [openai/skills](https://github.com/openai/skills)
- **语言**: Python
- **Stars**: 4,237
- **简介**: Skills Catalog for Codex

### AI 总结
**简介**: OpenAI 的 Codex AI 代理技能目录，包含可复用的指令、脚本和资源，用于帮助 AI 代理完成特定任务。

**核心功能**:
- 提供预构建的技能包，涵盖系统、精选和实验性类别，供 AI 代理直接发现和使用。
- 支持通过内置的 `$skill-installer` 工具轻松安装和管理技能。
- 遵循开放的 Agent Skills 标准，实现“一次编写，随处使用”的跨团队能力复用。

**技术亮点**: 基于 Python 实现，采用模块化的文件夹结构组织技能，并通过 GitHub 仓库进行集中管理和分发。

---
## 3. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 23,652
- **简介**: A Claude Code plugin that automatically captures everything Claude does during your coding sessions, compresses it with AI (using Claude's agent-sdk), and injects relevant context back into future sessions.

### AI 总结
**简介**: 一个为 Claude Code 设计的持久化记忆压缩系统插件，能自动捕获编码会话中的所有操作，并通过 AI 压缩，将相关上下文注入未来的会话中。

**核心功能**:
- 自动捕获 Claude Code 在编码会话期间的所有操作和观察结果。
- 使用 AI（基于 Claude 的 agent-sdk）对捕获的内容进行压缩和语义总结。
- 将压缩后的记忆作为上下文，智能地注入到未来的会话中，实现跨会话的知识连续性。

**技术亮点**: 基于 TypeScript 开发，集成了 Claude 的 agent-sdk 进行 AI 驱动的记忆压缩与检索，并支持多语言文档。

---
## 4. [j178/prek](https://github.com/j178/prek)
- **语言**: Rust
- **Stars**: 5,487
- **简介**: ⚡ Better `pre-commit`, re-engineered in Rust

### AI 总结
**简介**: prek 是一个用 Rust 重写的、更快的 `pre-commit` 替代品，旨在提供无依赖、高性能的 Git 钩子管理。

**核心功能**:
- 完全兼容原版 `pre-commit` 的配置文件和钩子。
- 提供单一二进制文件，无需 Python 或其他运行时环境。
- 内置对 monorepo（工作区模式）的支持。
- 与 `uv` 集成，用于管理 Python 虚拟环境和依赖。
- 改进了 Python、Node.js、Bun、Go、Rust 和 Ruby 等工具链的安装，支持钩子间共享。
- 内置了一些常用钩子的 Rust 原生实现。

**技术亮点**: 采用 Rust 编写，性能优于原版 `pre-commit`，磁盘空间使用更高效。

---
## 5. [topoteretes/cognee](https://github.com/topoteretes/cognee)
- **语言**: Python
- **Stars**: 11,824
- **简介**: Memory for AI Agents in 6 lines of code

### AI 总结
**简介**: Cognee 是一个开源的 Python 库，旨在用极简的代码为 AI 智能体构建准确、持久且动态的记忆系统。

**核心功能**:
- 将原始数据（如对话、文件、图像、音频转录）转化为 AI 可用的统一记忆层。
- 用基于图数据库和向量搜索的 ECL（提取、认知化、加载）管道替代传统的 RAG 系统。
- 提供高度可定制的模块化数据管道，支持从 30 多种数据源进行数据摄取。
- 提供内置的搜索端点，使文档既能按语义搜索，又能通过关系连接。

**技术亮点**: 结合了向量搜索与图数据库技术，构建了可扩展的模块化记忆架构，旨在降低开发成本和基础设施复杂度。

---
## 6. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 45,286
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为 AI 编程代理设计的、基于可组合“技能”的软件开发框架与工作流方法论。

**核心功能**:
- **智能设计引导**：在编码前通过提问引导用户明确需求，并分块呈现设计文档以供审阅。
- **结构化实施计划**：生成详细到文件路径和代码片段的、可供初级工程师遵循的原子级任务计划。
- **子代理驱动开发**：通过派遣独立的子代理执行每个任务，并进行两阶段（规范符合性、代码质量）审查，实现自动化开发。
- **强制测试驱动开发**：强制执行“红-绿-重构”的 TDD 循环，确保代码质量。
- **集成代码审查**：在任务间自动请求代码审查，并根据问题严重性决定是否阻塞流程。
- **Git 工作流管理**：自动创建隔离的 Git 工作树分支，并在开发完成后提供合并、PR等清理选项。

**技术亮点**: 采用基于 Shell 脚本的“技能”库架构，技能在代理执行任务前自动触发，将复杂的开发流程（如调试、协作、测试）模块化为可复用的强制工作流。

---
## 7. [aquasecurity/trivy](https://github.com/aquasecurity/trivy)
- **语言**: Go
- **Stars**: 31,349
- **简介**: Find vulnerabilities, misconfigurations, secrets, SBOM in containers, Kubernetes, code repositories, clouds and more

### AI 总结
**简介**: Trivy 是一款用 Go 编写的综合性安全扫描器，用于在容器、Kubernetes、代码仓库、云环境等多种目标中查找安全问题。

**核心功能**:
- **支持多种扫描目标**：容器镜像、文件系统、Git 仓库、虚拟机镜像和 Kubernetes 集群。
- **提供多种安全扫描**：检测操作系统包和软件依赖（SBOM）、已知漏洞（CVE）、基础设施即代码（IaC）问题与错误配置、敏感信息和密钥，以及软件许可证。

**技术亮点**:
- 采用 Go 语言开发，具有良好的跨平台性和性能。
- 支持广泛的编程语言、操作系统和平台。
- 提供多种安装方式（如 Homebrew、Docker、二进制包）和丰富的集成生态（如 GitHub Actions、Kubernetes Operator、VS Code 插件）。

---
## 8. [fish-shell/fish-shell](https://github.com/fish-shell/fish-shell)
- **语言**: Rust
- **Stars**: 32,367
- **简介**: The user-friendly command line shell.

### AI 总结
**简介**: Fish Shell 是一个为 macOS、Linux 等系统设计的智能且用户友好的命令行 shell。

**核心功能**:
-   语法高亮与自动建议：输入时提供语法高亮和命令建议，无需额外配置。
-   智能补全：提供功能强大的 Tab 键自动补全功能。
-   易于获取：支持通过包管理器（如 Homebrew、apt）、安装程序或从源码构建等多种方式安装。

**技术亮点**: 项目主要使用 Rust 语言开发，构建系统依赖 CMake 和 C 编译器，并可选集成 PCRE2 和 gettext 等库。

---
## 9. [nvm-sh/nvm](https://github.com/nvm-sh/nvm)
- **语言**: Shell
- **Stars**: 91,362
- **简介**: Node Version Manager - POSIX-compliant bash script to manage multiple active node.js versions

### AI 总结
**简介**: nvm 是一个基于 POSIX 兼容的 bash 脚本，用于在命令行中快速安装和管理多个 Node.js 版本。

**核心功能**:
- 允许用户通过命令行快速安装、切换和使用不同版本的 Node.js。
- 支持在单个用户环境中安装，并在每个 shell 会话中调用。
- 兼容多种 POSIX 兼容的 shell（如 sh, dash, ksh, zsh, bash）和平台（Unix, macOS, Windows WSL）。

**技术亮点**:
- 提供便捷的安装和更新脚本，支持通过 cURL 或 Wget 一键安装。
- 支持通过 `.nvmrc` 文件自动切换项目所需的 Node.js 版本。
- 具备完善的测试、环境变量配置和 Bash 自动补全功能。

---
## 10. [linshenkx/prompt-optimizer](https://github.com/linshenkx/prompt-optimizer)
- **语言**: TypeScript
- **Stars**: 19,319
- **简介**: 一款提示词优化器，助力于编写高质量的提示词

### AI 总结
**简介**: 一个强大的 AI 提示词优化工具，旨在帮助用户编写高质量的提示词，以提升 AI 模型的输出质量。

**核心功能**:
- **智能优化**：支持一键优化提示词，并可进行多轮迭代改进。
- **双模式优化**：涵盖系统提示词和用户提示词两种优化场景。
- **对比测试**：提供原始提示词与优化后提示词的实时对比功能。
- **多模型集成**：支持 OpenAI、Gemini、DeepSeek、智谱AI、SiliconFlow 等主流 AI 模型。
- **图像生成**：集成文生图（T2I）和图生图（I2I）功能，支持 Gemini、Seedream 等图像模型。
- **高级测试**：提供上下文变量管理、多轮会话测试和工具调用（Function Calling）支持。
- **多端部署**：提供 Web 应用、桌面应用、Chrome 插件和 Docker 部署四种使用方式。

**技术亮点**:
- **安全架构**：采用纯客户端处理，用户数据直接与 AI 服务商交互，不经过中间服务器。
- **多协议支持**：支持 Model Context Protocol (MCP) 协议，可与 Claude Desktop 等应用集成。
- **灵活部署**：支持 Vercel 一键部署、Docker 容器化部署，并提供自动更新的桌面应用。

---
