---
tags:
  - github-trending
  - daily
date: 2026-02-02
created: 2026-02-02T22:31:48.064Z
---

# 2026-02-02 GitHub Trending Top 10

> [!INFO]
> 本日报由 AI 自动生成，精选 GitHub Trending 前 10 项目。

## 1. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 17,982
- **简介**: A Claude Code plugin that automatically captures everything Claude does during your coding sessions, compresses it with AI (using Claude's agent-sdk), and injects relevant context back into future sessions.

### AI 总结
**简介**: 一个为 Claude Code 设计的持久化记忆压缩系统，能自动捕获编码会话中的操作，通过 AI 压缩并注入相关上下文到未来的会话中。

**核心功能**:
- 自动捕获 Claude 在编码会话期间的所有操作和观察结果。
- 使用 AI（基于 Claude 的 agent-sdk）对捕获的内容进行语义压缩和摘要。
- 将压缩后的相关上下文信息注入到未来的会话中，实现跨会话的知识连续性。

**技术亮点**:
- 基于 TypeScript 开发。
- 集成了 MCP（Model Context Protocol）搜索工具。
- 支持多语言文档，具备国际化能力。
- 采用 AGPL 3.0 开源协议。

---
## 2. [ThePrimeagen/99](https://github.com/ThePrimeagen/99)
- **语言**: Lua
- **Stars**: 3,023
- **简介**: Neovim AI agent done right

### AI 总结
**简介**: 一个为 Neovim 设计的、旨在优化 AI 工作流的智能代理插件，目前处于早期开发阶段。

**核心功能**:
- **AI 辅助编码**: 提供 `fill_in_function` 和 `visual` 等命令，通过 AI 自动补全或修改代码。
- **规则与技能系统**: 支持通过 `@` 触发自动补全，引入自定义技能规则（`SKILL.md`）和项目级代理文件（如 `AGENT.md`）来引导和限制 AI 行为。
- **请求控制**: 提供停止所有 AI 请求的功能。

**技术亮点**:
- **Lua 开发**: 专为 Neovim 生态打造。
- **可扩展配置**: 支持自定义规则路径、日志级别和自动加载项目特定的 Markdown 指导文件。
- **与 `cmp` 集成**: 实现了在提示输入时的技能自动补全功能。

---
## 3. [termux/termux-app](https://github.com/termux/termux-app)
- **语言**: Java
- **Stars**: 49,896
- **简介**: Termux - a terminal emulator application for Android OS extendible by variety of packages.

### AI 总结
**简介**: Termux 是一款为 Android 系统设计的终端模拟器应用，它提供了一个可扩展的 Linux 环境。

**核心功能**:
- 在 Android 设备上提供完整的终端模拟器体验。
- 通过包管理器（如 `apt` 或 `pkg`）安装各种软件包，扩展其功能。
- 提供一系列可选的插件应用，如 Termux:API（访问设备 API）、Termux:Boot（开机启动）、Termux:Float（悬浮窗口）等，以增强终端的使用场景。

**技术亮点**:
- 项目本身（用户界面和终端模拟）使用 Java 开发。
- 采用模块化设计，核心应用与功能插件（如 API、任务自动化等）分离，通过共享用户 ID (`com.termux`) 和签名密钥协同工作。
- 支持 Android 7.0 及以上版本（对 Android 5/6 的支持有限）。

---
## 4. [pedramamini/Maestro](https://github.com/pedramamini/Maestro)
- **语言**: TypeScript
- **Stars**: 1,256
- **简介**: Agent Orchestration Command Center

### AI 总结
**简介**: Maestro 是一款面向键盘操作的高级用户的跨平台桌面应用，旨在高效编排和管理多个AI代理与项目，实现并行开发和自动化任务执行。

**核心功能**:
- **Git Worktrees**：在隔离的分支上并行运行AI代理，实现无冲突的并行开发。
- **Auto Run & Playbooks**：基于文件系统的任务运行器，可批量处理Markdown清单，支持可重复的工作流和长时间无人值守运行。
- **Group Chat**：在单一对话中协调多个AI代理，由主持代理进行问题路由和响应合成。
- **移动远程控制**：内置Web服务器，支持通过二维码在手机端监控和控制所有代理。
- **命令行界面**：提供完整的CLI，支持无头操作和脚本集成。
- **多代理管理**：支持无限并行运行的代理和终端会话，每个代理拥有独立的工作空间和上下文。
- **消息队列**：在AI繁忙时自动排队消息，确保指令不丢失。

**技术亮点**: 基于TypeScript开发，采用键盘优先设计，支持可扩展的斜杠命令和强大的输出过滤（含正则表达式），并集成了深度Git功能（如自动仓库检测、差异查看器）。

---
## 5. [netbirdio/netbird](https://github.com/netbirdio/netbird)
- **语言**: Go
- **Stars**: 21,952
- **简介**: Connect your devices into a secure WireGuard®-based overlay network with SSO, MFA and granular access controls.

### AI 总结
**简介**: NetBird 是一个基于 WireGuard® 的开源平台，可轻松将设备连接至安全的覆盖网络，并提供 SSO、MFA 和细粒度访问控制。

**核心功能**:
- 建立基于 WireGuard 的点对点加密覆盖网络，无需复杂配置、端口转发或 VPN 网关。
- 提供集中式管理界面，支持 SSO/MFA、细粒度访问策略、活动日志和设备状态检查。
- 支持自动化网络配置，包括批量设备注册、公共 API 和 Terraform 提供商。
- 跨平台支持，涵盖 Linux、macOS、Windows、Android、iOS、OpenWRT、Docker 和无服务器环境。

**技术亮点**:
- 使用内核 WireGuard 实现高性能加密隧道。
- 支持 NAT 穿透（BPF）和连接中继回退，确保连接可靠性。
- 集成 Rosenpass 以实现抗量子加密。
- 提供自托管选项和快速启动脚本。

---
## 6. [OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev)
- **语言**: Python
- **Stars**: 29,351
- **简介**: ChatDev 2.0: Dev All through LLM-powered Multi-Agent Collaboration

### AI 总结
**简介**: ChatDev 2.0 (DevAll) 是一个零代码的多智能体编排平台，旨在通过简单的配置让用户无需编程即可构建和执行定制化的多智能体系统，以完成复杂任务。

**核心功能**:
- **零代码多智能体平台**：用户可通过配置定义智能体、工作流和任务，快速构建定制化系统。
- **支持复杂场景编排**：可应用于数据可视化、3D生成、深度研究等多种复杂场景。
- **多智能体协作范式**：平台基于智能体间通过语言交互进行协作的范式，支持从链式到更复杂的拓扑结构。

**技术亮点**: 基于大语言模型驱动的多智能体协作，其架构支持可学习的中央编排器，并能通过强化学习进行优化，以动态激活和排序智能体，构建高效、上下文感知的推理路径。

---
## 7. [autobrr/qui](https://github.com/autobrr/qui)
- **语言**: Go
- **Stars**: 2,800
- **简介**: A fast, single-binary qBittorrent web UI: manage multiple instances, automate torrent workflows, and cross-seed across trackers.

### AI 总结
**简介**: qui 是一个用 Go 编写的、快速且现代化的 qBittorrent Web 管理界面，支持从单一轻量级应用管理多个 qBittorrent 实例。

**核心功能**:
- **单二进制文件**: 无需依赖，下载即可运行。
- **多实例管理**: 集中管理所有 qBittorrent 实例。
- **跨站点辅种**: 自动在不同 Tracker 间查找并添加匹配的种子。
- **自动化规则**: 基于条件的种子管理工作流。
- **备份与恢复**: 支持计划快照和多种恢复模式。
- **反向代理**: 为外部应用提供透明的 qBittorrent 代理。

**技术亮点**:
- 使用 Go 语言开发，性能优异，尤其擅长处理大量种子。
- 采用单二进制架构，部署和分发极其简单。

---
## 8. [badlogic/pi-mono](https://github.com/badlogic/pi-mono)
- **语言**: TypeScript
- **Stars**: 5,535
- **简介**: AI agent toolkit: coding agent CLI, unified LLM API, TUI & web UI libraries, Slack bot, vLLM pods

### AI 总结
**简介**: Pi Monorepo 是一个用于构建 AI 智能体和管理大语言模型（LLM）部署的 TypeScript 工具集。

**核心功能**:
- **统一 LLM API**: 提供支持多供应商（如 OpenAI、Anthropic、Google 等）的统一 API。
- **智能体运行时**: 包含工具调用和状态管理的智能体运行时核心。
- **交互式编程助手**: 提供命令行界面（CLI）的交互式编程智能体。
- **Slack 机器人**: 可将 Slack 消息委托给编程智能体处理的机器人。
- **用户界面库**: 提供支持差异渲染的终端 UI 库和用于 AI 聊天界面的 Web 组件。
- **部署管理**: 提供用于在 GPU Pod 上管理 vLLM 部署的 CLI 工具。

**技术亮点**: 采用 TypeScript 开发，项目结构为 Monorepo，包含多个功能独立的包，便于集成和使用。

---
## 9. [VectifyAI/PageIndex](https://github.com/VectifyAI/PageIndex)
- **语言**: Python
- **Stars**: 12,460
- **简介**: 📑 PageIndex: Document Index for Vectorless, Reasoning-based RAG

### AI 总结
**简介**: PageIndex 是一个无需向量数据库和文档分块的、基于推理的检索增强生成（RAG）系统，它通过构建文档的层次化树状索引并利用LLM进行推理搜索，实现了类人的文档检索。

**核心功能**:
- **无需向量数据库**：利用文档结构和LLM推理进行检索，而非向量相似性搜索。
- **无需文档分块**：将文档组织成自然的章节结构，而非人工划分的片段。
- **类人检索**：模拟人类专家在复杂文档中导航和提取知识的方式。
- **更好的可解释性与可追溯性**：检索基于可追溯和可解释的推理过程，并提供页面和章节引用。

**技术亮点**: 采用**层次化树状索引**架构，通过“生成目录树”和“基于树搜索的推理检索”两步法，实现代理式、上下文感知的检索。该系统在专业长文档处理上表现出色，在特定基准测试中达到了领先的准确率。

---
## 10. [karpathy/nanochat](https://github.com/karpathy/nanochat)
- **语言**: Python
- **Stars**: 41,590
- **简介**: The best ChatGPT that $100 can buy.

### AI 总结
**简介**: nanochat 是一个极简、可修改的 LLM 实验框架，旨在单 GPU 节点上实现从分词、预训练、微调、评估到推理和聊天界面的全流程。

**核心功能**:
- 以极低成本（约 73 美元，3小时）复现 GPT-2 级别（1.6B）模型的训练。
- 提供完整的训练与评估脚本，并包含一个类似 ChatGPT 的 Web 聊天界面。
- 支持在单 GPU 或多 GPU（如 8x H100）节点上运行，代码简洁且易于修改。

**技术亮点**: 基于 PyTorch，利用 `torchrun` 进行分布式训练，通过优化实现了训练效率的显著提升（相比 2019 年成本降低约 99.8%）。

---
