---
tags:
  - github-trending
  - daily
date: 2026-02-10
created: 2026-02-10T02:32:19.545Z
---

# 2026-02-10 GitHub Trending Top 10

## 1. [KeygraphHQ/shannon](https://github.com/KeygraphHQ/shannon)
- **语言**: TypeScript
- **Stars**: 17,515
- **简介**: Fully autonomous AI hacker to find actual exploits in your web apps. Shannon has achieved a 96.15% success rate on the hint-free, source-aware XBOW Benchmark.

### AI 总结
**简介**: Shannon 是一个完全自主的 AI 渗透测试工具，旨在通过分析源代码并执行真实攻击来发现 Web 应用中的实际可利用漏洞。

**核心功能**:
- **完全自主操作**：单条命令即可启动渗透测试，AI 自动处理包括 2FA/TOTP 登录、浏览器导航到生成报告在内的所有环节。
- **提供可复现的渗透测试报告**：生成包含已验证漏洞和可直接复现的攻击证明（PoC）的报告，减少误报。
- **覆盖关键 OWASP 漏洞**：目前专注于识别和验证注入、XSS、SSRF 以及身份验证/授权绕过等关键漏洞。
- **代码感知的动态测试**：结合源代码分析来指导攻击策略，并在运行的应用上通过浏览器和命令行执行真实攻击以确认风险。
- **集成安全工具**：利用 Nmap、Subfinder、WhatWeb 和 Schemathesis 等工具进行深度环境侦察和分析。
- **并行处理**：通过并行化分析和利用阶段来加速测试过程。

**技术亮点**:
- 基于 TypeScript 开发。
- 在无提示、源码感知的 XBOW 基准测试中取得了 96.15% 的成功率。
- 提供两个版本：AGPL-3.0 许可的 **Shannon Lite**（白盒测试）和功能更强大的商业版 **Shannon Pro**。

---
## 2. [virattt/dexter](https://github.com/virattt/dexter)
- **语言**: TypeScript
- **Stars**: 13,592
- **简介**: An autonomous agent for deep financial research

### AI 总结
**简介**: Dexter 是一个用 TypeScript 编写的自主金融研究智能体，能够将复杂的金融问题分解为结构化任务，并利用实时市场数据进行分析和验证。

**核心功能**:
- **智能任务规划**: 自动将复杂查询分解为分步研究计划。
- **自主执行与验证**: 调用工具获取金融数据，并具备自我检查和迭代优化的能力。
- **实时数据接入**: 可访问财务报表（如利润表、资产负债表、现金流表）等实时市场数据。
- **安全与可观测性**: 内置循环检测和步骤限制以防止无限执行，并提供详细的运行日志用于调试。

**技术亮点**: 项目基于 Bun 运行时，支持 OpenAI、Anthropic 等多种大模型 API，并集成了 Financial Datasets 等专业金融数据源。其架构包含评估套件（使用 LangSmith 跟踪和 LLM 作为评判）以及本地调试用的详细运行记录（Scratchpad）。

---
## 3. [pydantic/monty](https://github.com/pydantic/monty)
- **语言**: Rust
- **Stars**: 3,995
- **简介**: A minimal, secure Python interpreter written in Rust for use by AI

### AI 总结
**简介**: Monty 是一个用 Rust 编写的、极简且安全的 Python 解释器，专为 AI 代理运行其生成的代码而设计。

**核心功能**:
- **安全沙箱**: 完全隔离宿主环境（文件系统、环境变量、网络），仅允许调用开发者明确授权的宿主函数。
- **高性能与轻量**: 启动时间极快（<1微秒），运行时性能与 CPython 相当，且无 CPython 依赖，可嵌入 Rust、Python 或 JavaScript 环境。
- **资源与状态控制**: 可监控并限制内存、栈深度和执行时间，并支持将解释器状态快照为字节以持久化存储和恢复。
- **类型检查与异步支持**: 内置对现代 Python 类型提示的支持（集成 `ty`），并可运行异步或同步的宿主代码。

**技术亮点**: 采用 Rust 编写，实现了一个功能受限但高度可控的 Python 子集解释器，旨在替代传统的容器化沙箱方案，为 AI 代理提供安全、低延迟的代码执行环境。

---
## 4. [hsliuping/TradingAgents-CN](https://github.com/hsliuping/TradingAgents-CN)
- **语言**: Python
- **Stars**: 16,284
- **简介**: 基于多智能体LLM的中文金融交易框架 - TradingAgents中文增强版

### AI 总结
**简介**: TradingAgents-CN 是一个基于多智能体与大语言模型（LLM）的中文金融交易分析学习框架，专注于为中文用户提供合规的股票研究与策略实验平台，支持A股、港股、美股分析，定位为学习与研究用途。

**核心功能**:
- **多智能体股票分析**: 集成多个AI分析师角色，对股票进行基本面、技术面等多维度分析。
- **企业级系统架构**: 提供完整的用户权限管理、配置中心、实时通知、自选股管理和模拟交易系统。
- **多数据源与模型支持**: 统一管理Tushare、AkShare等数据源，并支持动态配置OpenAI、Google AI等多种LLM供应商。
- **专业报告导出**: 支持将分析结果导出为Markdown、Word、PDF等多种格式的专业报告。
- **灵活的部署方式**: 提供绿色版（Windows）、Docker容器化部署和本地源码安装三种方式。

**技术亮点**:
- **现代化技术栈**: 采用 FastAPI（后端）、Vue 3 + Element Plus（前端）的全新架构，替代原Streamlit，性能大幅提升。
- **双数据库架构**: 使用 MongoDB 与 Redis 组合，实现高效数据存储与缓存。
- **容器化与多架构支持**: 提供完整的Docker Compose配置，支持x86_64和ARM64（如Apple Silicon）平台。
- **混合许可证模式**: 核心框架部分采用Apache 2.0开源，而前端（`frontend/`）和应用后端（`app/`）需商业授权。

---
## 5. [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi)
- **语言**: TypeScript
- **Stars**: 13,870
- **简介**: Free, local, open-source 24/7 Cowork and OpenClaw for Gemini CLI, Claude Code, Codex, OpenCode, Qwen Code, Goose CLI, Auggie, and more | 🌟 Star if you like it!

### AI 总结
**简介**: AionUi 是一个免费、本地化、开源的图形界面工具，为多种命令行 AI 工具（如 Gemini CLI、Claude Code 等）提供统一的 7x24 小时协同工作环境。

**核心功能**:
- **多智能体模式**：自动检测本地已安装的 CLI AI 工具，并提供统一的图形化界面，告别命令行操作。
- **随时随地访问**：支持通过 WebUI 浏览器、Telegram、飞书等多种方式远程访问，实现跨设备使用。
- **计划任务**：可设置定时任务，让 AI 助手按计划自动执行工作，实现全天候无人值守运行。

**技术亮点**: 基于 TypeScript 开发，支持跨平台（macOS/Windows/Linux），采用本地数据存储保障安全，并提供多会话管理和独立上下文。

---
## 6. [public-apis/public-apis](https://github.com/public-apis/public-apis)
- **语言**: Python
- **Stars**: 397,258
- **简介**: A collective list of free APIs

### AI 总结
**简介**: 一个由社区和 APILayer 共同维护的免费公共 API 集合项目，涵盖了众多领域的 API 资源。

**核心功能**:
- 提供来自多个领域的、可免费使用的公共 API 详细列表。
- 社区驱动，鼓励用户贡献和维护 API 信息。
- 包含 APILayer 旗下多个热门 API（如 IP 定位、股票数据、天气信息等）的快速访问和测试入口。

**技术亮点**: 项目本身是一个 Python 项目，主要作为 API 目录和文档。其亮点在于社区化的内容管理和维护模式，并通过与 Postman 集成方便开发者直接测试 API。

---
## 7. [github/gh-aw](https://github.com/github/gh-aw)
- **语言**: Go
- **Stars**: 945
- **简介**: GitHub Agentic Workflows

### AI 总结
**简介**: GitHub Agentic Workflows 是一个允许开发者使用自然语言 Markdown 编写智能代理工作流，并在 GitHub Actions 中安全运行的 Go 语言项目。

**核心功能**:
- 使用自然语言 Markdown 编写工作流，降低自动化门槛。
- 在 GitHub Actions 环境中运行，与现有 CI/CD 流程集成。
- 提供多层安全防护（如默认只读权限、沙箱执行、输入净化、网络隔离等），确保 AI 代理在受控边界内安全运行。

**技术亮点**:
- **安全架构**: 默认只读权限、沙箱执行、输入净化、网络隔离、依赖 SHA 锁定、工具白名单、编译时验证。
- **配套工具**: 包含用于网络出口控制的 Agent Workflow Firewall (AWF) 和用于集中访问管理的 MCP Gateway。

---
## 8. [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)
- **语言**: Python
- **Stars**: 93,183
- **简介**: Collection of awesome LLM apps with AI Agents and RAG using OpenAI, Anthropic, Gemini and opensource models.

### AI 总结
**简介**: 一个精心整理的、汇集了各类优秀大语言模型（LLM）应用的开源项目集合，涵盖AI智能体、RAG、多智能体团队、MCP、语音智能体等多种技术。

**核心功能**:
- 收集并展示基于OpenAI、Anthropic、Gemini、xAI及开源模型（如Qwen、Llama）构建的实用LLM应用。
- 提供从入门级到高级的AI智能体项目示例，例如博客转播客智能体、分手恢复助手等。
- 旨在帮助开发者探索LLM在不同领域（如代码库、邮箱）的创造性应用，并学习相关技术。

**技术亮点**: 项目聚焦于当前LLM应用开发的前沿技术栈，包括检索增强生成（RAG）、AI智能体（Agents）、多智能体协作（Multi-agent Teams）、模型上下文协议（MCP）以及语音智能体（Voice Agents）。

---
## 9. [gitbutlerapp/gitbutler](https://github.com/gitbutlerapp/gitbutler)
- **语言**: Rust
- **Stars**: 18,664
- **简介**: The GitButler version control client, backed by Git, powered by Tauri/Rust/Svelte

### AI 总结
**简介**: GitButler 是一个基于 Git 构建的现代化版本控制客户端，提供图形界面（GUI）和命令行界面（CLI），专为 AI 驱动的工作流设计。

**核心功能**:
- **堆叠分支**：轻松创建基于其他分支的分支，支持自动重新堆叠以方便修改提交。
- **并行分支**：支持同时处理多个分支，无需频繁切换。
- **简易提交管理**：通过拖放或简单 CLI 命令实现提交的撤销、重写、修改、移动、拆分和压缩。
- **撤销时间线**：记录所有操作和变更，支持轻松撤销或恢复任何操作。
- **一流的冲突处理**：变基操作始终成功，冲突提交可随时按任意顺序标记和解决。
- **代码托管平台集成**：支持 GitHub 和 GitLab 认证，方便创建和更新 Pull Request、获取 CI 状态等。
- **AI 工具集成**：内置 AI 助手，帮助生成提交信息、分支名称、PR 描述等，并支持为现代代理系统安装钩子或技能。

**技术亮点**: 桌面应用基于 Tauri 构建，前端使用 Svelte 和 TypeScript，后端使用 Rust 编写；CLI 工具同样由 Rust 后端引擎驱动。

---
## 10. [microsoft/litebox](https://github.com/microsoft/litebox)
- **语言**: Rust
- **Stars**: 1,738
- **简介**: A security-focused library OS supporting kernel- and user-mode execution

### AI 总结
**简介**: LiteBox 是一个专注于安全的库操作系统，旨在通过大幅缩减与主机的接口来减少攻击面，支持内核模式和非内核模式执行。

**核心功能**:
- 提供沙盒化环境，可在不同平台上安全运行应用程序
- 支持多种使用场景，如在 Windows 上运行未经修改的 Linux 程序、在 Linux 上沙盒化 Linux 应用、在 SEV SNP 上运行程序等
- 通过“北向”接口（受 `nix`/`rustix` 启发）和“南向”平台接口实现灵活互操作

**技术亮点**: 使用 Rust 语言开发，采用模块化设计，便于连接不同的“北向-南向”接口对，适用于多样化的安全隔离场景。

---
