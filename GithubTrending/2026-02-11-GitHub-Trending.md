---
tags:
  - github-trending
  - daily
date: 2026-02-11
created: 2026-02-11T01:55:51.481Z
---

# 2026-02-11 GitHub Trending Top 10

## 1. [google/langextract](https://github.com/google/langextract)
- **语言**: Python
- **Stars**: 28,551
- **简介**: A Python library for extracting structured information from unstructured text using LLMs with precise source grounding and interactive visualization.

### AI 总结
**简介**: LangExtract 是一个由 Google 开发的 Python 库，利用大语言模型从非结构化文本中提取结构化信息。

**核心功能**:
- **精确溯源与可视化**：将提取的每个实体映射回原文的精确位置，并生成交互式 HTML 文件进行可视化审查。
- **可靠的结构化输出**：基于用户提供的少量示例，强制执行一致的输出模式，确保结果结构稳定。
- **长文档优化**：通过文本分块、并行处理和多轮处理策略，高效处理大型文档，提高召回率。
- **灵活的模型支持**：支持云端模型（如 Google Gemini）和本地开源模型（通过 Ollama 接口）。
- **领域自适应**：仅需少量示例即可定义任何领域的提取任务，无需对模型进行微调。

**技术亮点**: 采用基于提示词和少样本示例的指令驱动提取，利用 LLM 的世界知识，并支持可控生成以确保输出格式。

---
## 2. [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi)
- **语言**: TypeScript
- **Stars**: 14,473
- **简介**: Free, local, open-source 24/7 Cowork and OpenClaw for Gemini CLI, Claude Code, Codex, OpenCode, Qwen Code, Goose CLI, Auggie, and more | 🌟 Star if you like it!

### AI 总结
**简介**: AionUi 是一个免费、本地化、开源的图形界面工具，旨在为多种命令行 AI 工具（如 Gemini CLI、Claude Code 等）提供统一的协作界面和 7x24 小时自动化支持。

**核心功能**:
- **多智能体模式**：为多种命令行 AI 工具（如 Gemini CLI、Claude Code、OpenClaw 等）提供统一的图形界面，支持自动检测和本地多会话管理。
- **随处访问**：支持通过 WebUI 在任意设备浏览器访问，并可集成 Telegram、飞书等聊天平台进行交互。
- **定时任务**：支持使用自然语言设置定时任务，实现 AI 助手的自动化、无人值守运行。

**技术亮点**: 基于 TypeScript 开发，跨平台（支持 macOS、Windows、Linux），采用本地数据存储以确保安全性，并支持灵活的远程访问和平台集成配置。

---
## 3. [KeygraphHQ/shannon](https://github.com/KeygraphHQ/shannon)
- **语言**: TypeScript
- **Stars**: 19,789
- **简介**: Fully autonomous AI hacker to find actual exploits in your web apps. Shannon has achieved a 96.15% success rate on the hint-free, source-aware XBOW Benchmark.

### AI 总结
**简介**: Shannon 是一个完全自主的 AI 渗透测试工具，旨在通过分析源代码并执行真实攻击来发现 Web 应用中的实际可利用漏洞。

**核心功能**:
- **完全自主操作**：单条命令启动，AI 自动处理包括 2FA/TOTP 登录、浏览器导航在内的所有步骤，并生成最终报告。
- **提供可复现的漏洞利用证明**：生成渗透测试报告，包含可复制粘贴的漏洞验证代码，以消除误报并提供可操作结果。
- **覆盖关键 OWASP 漏洞**：当前可识别并验证注入、XSS、SSRF 及身份验证/授权绕过等关键漏洞。
- **代码感知的动态测试**：分析源代码以智能指导攻击策略，并在运行的应用上通过浏览器和命令行执行真实攻击以确认风险。
- **集成安全工具**：利用 Nmap、Subfinder、WhatWeb、Schemathesis 等工具进行深度环境分析和侦察。
- **并行处理**：并行运行分析和漏洞利用阶段，以加快报告生成速度。

**技术亮点**: 基于 TypeScript 开发，采用白盒测试模式，集成了先进的侦察工具和 LLM 驱动的数据流分析引擎（Shannon Pro 版本），在无提示、源码感知的 XBOW 基准测试中取得了 96.15% 的成功率。

---
## 4. [github/gh-aw](https://github.com/github/gh-aw)
- **语言**: Go
- **Stars**: 1,355
- **简介**: GitHub Agentic Workflows

### AI 总结
**简介**: GitHub Agentic Workflows 是一个 Go 语言项目，它允许开发者使用自然语言 Markdown 编写智能体工作流，并在 GitHub Actions 中安全地运行。

**核心功能**:
- 使用自然语言 Markdown 编写 AI 驱动的自动化工作流。
- 在 GitHub Actions 环境中执行工作流，实现仓库任务的自动化。
- 提供全面的安全护栏（Guardrails），包括默认只读权限、沙箱执行、网络隔离和工具白名单等。

**技术亮点**:
- **安全架构**: 默认运行在只读权限下，通过 `safe-outputs` 进行安全的写操作，并集成了沙箱、输入净化、供应链安全（SHA 固定依赖）和编译时验证等多层防护。
- **扩展生态**: 包含配套项目如 **Agent Workflow Firewall (AWF)** 用于网络出口控制，以及 **MCP Gateway** 用于集中管理模型上下文协议（MCP）服务器的调用。

---
## 5. [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin)
- **语言**: TypeScript
- **Stars**: 8,179
- **简介**: Official Claude Code compound engineering plugin

### AI 总结
**简介**: 这是一个官方的 Claude Code 复合工程插件市场，旨在通过工具化流程让工程工作产生复利效应，使后续工作越来越容易。

**核心功能**:
- **插件市场与安装**: 提供 Claude Code 插件市场，可便捷安装 `compound-engineering` 插件。
- **多平台转换工具**: 包含一个 Bun/TypeScript CLI 工具，可将 Claude Code 插件转换为实验性的 OpenCode 和 Codex 格式。
- **个人配置同步**: 支持将个人 Claude Code 配置（技能和 MCP 服务器）同步到 OpenCode 或 Codex 平台。
- **复合工程工作流**: 提供 `/workflows:plan`、`/workflows:work`、`/workflows:review`、`/workflows:compound` 四个核心命令，覆盖从规划、执行、审查到知识沉淀的完整开发周期。

**技术亮点**: 项目使用 TypeScript 开发，并构建了 Bun/TypeScript CLI 工具链，实现了跨平台（Claude Code、OpenCode、Codex）的插件格式转换与配置同步。其架构强调通过规划与审查前置（80%精力）来保证代码质量，使工程实践能够“复利”积累。

---
## 6. [hsliuping/TradingAgents-CN](https://github.com/hsliuping/TradingAgents-CN)
- **语言**: Python
- **Stars**: 16,681
- **简介**: 基于多智能体LLM的中文金融交易框架 - TradingAgents中文增强版

### AI 总结
**简介**: TradingAgents-CN 是一个基于多智能体与大语言模型（LLM）的中文金融交易学习与分析框架，专注于为中文用户提供合规的股票研究、策略实验与AI金融技术学习平台。

**核心功能**:
- **多智能体股票分析**：集成多个AI分析师角色，支持对A股、港股、美股进行基本面、技术面等多维度分析。
- **企业级系统架构**：提供完整的用户权限管理、配置中心、实时通知、自选股管理与模拟交易系统。
- **多数据源与模型支持**：统一管理Tushare、AkShare等数据源，并支持OpenAI、Google AI及自定义LLM端点，具备智能模型选择能力。
- **专业报告导出**：支持将分析结果导出为Markdown、Word、PDF等多种格式的专业报告。
- **灵活的部署方式**：提供绿色版（Windows）、Docker容器化部署（支持多架构）和本地源码部署三种方案。

**技术亮点**:
- **现代化技术栈**：采用 FastAPI + Vue 3 + Element Plus 的前后端分离架构，替代原版的Streamlit，性能与可扩展性显著提升。
- **双数据库设计**：结合 MongoDB 与 Redis，实现高效数据存储与缓存管理。
- **容器化与多架构支持**：通过Docker Compose提供一键部署，并支持x86_64和ARM64（如Apple Silicon）平台。
- **混合许可证模式**：核心框架开源（Apache 2.0），但前端（`frontend/`）和后端应用（`app/`）部分需商业授权，强调版权保护。

---
## 7. [gitbutlerapp/gitbutler](https://github.com/gitbutlerapp/gitbutler)
- **语言**: Rust
- **Stars**: 19,038
- **简介**: The GitButler version control client, backed by Git, powered by Tauri/Rust/Svelte

### AI 总结
**简介**: GitButler 是一个基于 Git 构建的现代化版本控制客户端，提供图形界面（GUI）和命令行界面（CLI），专为 AI 驱动的工作流设计。

**核心功能**:
- **堆叠分支**：轻松创建基于其他分支的堆叠分支，支持自动重新堆叠以方便修改提交。
- **并行分支**：支持同时处理多个分支，无需频繁切换。
- **简易提交管理**：通过拖放或简单 CLI 命令实现提交的撤销、重写、修改、移动、拆分和压缩。
- **操作时间线与撤销**：记录所有操作和变更，支持轻松撤销或恢复。
- **一流的冲突处理**：提交可标记为冲突状态，并可在任意时间、任意顺序解决。
- **代码托管平台集成**：集成 GitHub 和 GitLab，方便管理拉取请求、分支和 CI 状态。
- **AI 工具集成**：内置 AI 助手，帮助生成提交信息、分支名称和 PR 描述等。

**技术亮点**: 桌面应用基于 Tauri 构建，前端使用 Svelte 和 TypeScript，后端使用 Rust；CLI 工具同样由 Rust 驱动。

---
## 8. [carlvellotti/claude-code-pm-course](https://github.com/carlvellotti/claude-code-pm-course)
- **语言**: MDX
- **Stars**: 835
- **简介**: Interactive course teaching Product Managers how to use Claude Code effectively

### AI 总结
**简介**: 一个面向产品经理的交互式课程，教授如何高效使用 Claude Code 进行日常工作。

**核心功能**:
- **基础操作教学**：涵盖文件操作、@提及、代理使用、自定义子代理创建和项目记忆（CLAUDE.md）等核心功能。
- **高级场景实践**：指导如何与AI协作撰写产品需求文档（PRD）、进行数据分析以及制定产品战略。
- **交互式学习路径**：提供循序渐进的动手实践模块，包含明确的启动命令（如 `/start-1-1`）和分步指导。

**技术亮点**: 课程内容采用 MDX 格式，并设计了与 Claude Code 深度集成的交互式学习流程，强调在工具内按指引操作，避免提前进行不必要的环境配置。

---
## 9. [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)
- **语言**: Python
- **Stars**: 93,638
- **简介**: Collection of awesome LLM apps with AI Agents and RAG using OpenAI, Anthropic, Gemini and opensource models.

### AI 总结
**简介**: 一个精心整理的、汇集了使用RAG、AI智能体、多智能体团队、MCP、语音智能体等技术构建的优秀大语言模型应用的开源集合。

**核心功能**:
- 展示和分类基于多种大模型（如OpenAI、Anthropic、Gemini及开源模型Qwen、Llama等）构建的实用LLM应用。
- 提供从入门级到更复杂的AI智能体项目示例，涵盖博客转播客、数据分析等多个领域。
- 旨在为开发者提供学习、灵感和贡献的平台，推动LLM应用开源生态发展。

**技术亮点**: 项目聚焦于结合**AI智能体**、**检索增强生成**、**多智能体协作**及**模型上下文协议**等前沿技术栈构建应用。

---
## 10. [drawdb-io/drawdb](https://github.com/drawdb-io/drawdb)
- **语言**: JavaScript
- **Stars**: 36,336
- **简介**: Free, simple, and intuitive online database diagram editor and SQL generator.

### AI 总结
**简介**: drawDB 是一个免费、简单直观的在线数据库图表编辑器和 SQL 生成工具。

**核心功能**:
- 在浏览器中通过点击即可轻松构建数据库实体关系图。
- 支持将图表导出为 SQL 脚本。
- 提供高度可定制的编辑器，且无需注册账户即可使用。

**技术亮点**: 项目基于 JavaScript 开发，支持通过 npm 脚本进行本地开发与构建，并提供了 Docker 镜像以方便部署。

---
