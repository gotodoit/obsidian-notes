---
tags:
  - github-trending
  - daily
date: 2026-11-05
created: 2026-11-05T01:55:43.211Z
---

# 2026-11-05 GitHub Trending Top 10

## 1. [NVIDIA/auto-ontology](https://github.com/NVIDIA/auto-ontology)
- **语言**: Python
- **Stars**: 5,147
- **简介**: Auto Ontology is a Python framework for building semantic, graph-based reasoning layers over data. It enables deterministic query generation, better context retrieval, and more explainable AI for LLM and agent workflows.

### AI 总结
**简介**: NVIDIA Auto Ontology 是一个 Python 框架，用于在数据之上构建基于语义图谱的推理层，为 LLM 与 Agent 工作流提供确定性的查询生成、更优的上下文检索和可解释的 AI 能力。

**核心功能**:
- **发现（Discover）**：从企业元数据生成企业本体，连接已有本体与语义模型，构建面向 AI 的知识图谱。
- **锚定（Ground）**：为指标、实体和关系提供可信的业务含义，并对齐跨系统不一致的定义。
- **校验（Validate）**：依据已认证的定义与数据血缘检查生成的查询，并为每个答案返回来源信息。
- **暴露（Expose）**：通过 MCP、CLI 和 API 向任意 Agent 框架提供上下文。
- **学习（Learn）**：将已认证的修正与使用反馈回本体，使共享上下文随每次提问持续改进。
- **自然语言查询结构化数据**：将问题翻译为 SQL 并在连接的数据库上执行（由 NVIDIA NIM 驱动）。

**技术亮点**:
- **前端**：Next.js 16（React 19、TypeScript、Tailwind CSS 4）、Better Auth、Prisma，提供 Web UI、认证与 API 网关。
- **后端**：FastAPI（Python 3.12+）、LangChain，负责聊天、NL-to-SQL、目录与数据源 API。
- **数据层**：Postgres + pgvector 同时承载应用元数据、语义目录/本体与向量存储；可选 HashiCorp Vault 安全存储连接凭据。
- **模型配置**：基于 NVIDIA NIM（可托管或自托管），通过 `<PREFIX>_ENDPOINT / _API_KEY / _MODEL` 三元组配置推理、非推理、嵌入与重排模型。
- **部署**：支持 Kubernetes Helm Chart 或本地 Docker Compose 灵活部署。
- **许可**：Apache License 2.0，当前不接受外部贡献。

---
## 2. [max-sixty/worktrunk](https://github.com/max-sixty/worktrunk)
- **语言**: Rust
- **Stars**: 11,064
- **简介**: Worktrunk is a CLI for Git worktree management, designed for parallel AI agent workflows

### AI 总结
**简介**: Worktrunk 是一个用 Rust 编写的 Git worktree 管理 CLI 工具，专为并行运行 AI Agent 工作流而设计，让 worktree 的使用像分支一样简单。

**核心功能**:
- 三个核心命令简化 worktree 的创建、切换与管理，无需重复输入分支名和路径
- 以分支名寻址 worktree，路径由可配置模板自动生成
- 支持 hooks 自动化本地工作流，并提供写时复制（copy-on-write）构建缓存等提升并行开发体验的功能

**技术亮点**: 基于 Rust 开发；针对 Claude Code、Codex 等 AI Agent 并行处理 5-10+ 任务的场景优化；提供完整文档站点 worktrunk.dev；采用 MIT OR Apache-2.0 双许可。

---
## 3. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 313,377
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: Matt Pocock 分享的日常 AI 编程 Agent 技能集，强调小巧、可组合、可自由改造，用于真实的工程开发而非“氛围编程”。

**核心功能**:
- `/grill-me` 与 `/grill-with-docs`：在动手前通过“拷问式”提问帮助开发者与 Agent 对齐需求，避免理解偏差
- `/triage`：结合自定义标签对工单进行分诊管理
- `/setup-matt-pocock-skills`：每个仓库运行一次，配置 issue 跟踪器（GitHub、GitLab、本地文件等）、分诊标签及文档保存位置
- 支持 Claude Code、Codex、GitHub Copilot、Gemini CLI 及其他主流 Agent 的插件化安装

**技术亮点**: 以 Shell 为主实现；采用插件市场机制（支持自动更新或手动更新两种模式）；技能按 engineering、productivity 分类组织，设计上保持小而可组合，不绑定特定模型，可与任意 Agent 配合使用。

---
## 4. [floci-io/floci](https://github.com/floci-io/floci)
- **语言**: Java
- **Stars**: 29,658
- **简介**: Light, fluffy, and always free - The AWS Local Emulator alternative

### AI 总结
**简介**: Floci 是一个免费开源的本地 AWS 模拟器，用 `docker compose up` 即可在本地运行 AWS 风格的服务，无需云账号、认证令牌或付费功能门槛。

**核心功能**:
- 本地模拟 AWS 服务，所有服务统一通过 `http://localhost:4566` 访问，兼容 AWS SDK、CLI、Terraform、CDK、OpenTofu 及测试套件
- 作为 LocalStack 的即插即用替代品，只需更换镜像即可迁移
- 提供官方 CLI（`floci start` / `floci env`）及 Linux/macOS/Windows 独立二进制，支持 Docker Compose 部署
- 内置 Web 控制台（`/_floci/ui`），可在浏览器中查看本地资源
- 属于多云端模拟器家族（AWS/Azure/GCP/OCI），AWS 成员使用 4566 端口

**技术亮点**: 基于 Java 开发，采用 Docker 镜像分发（`floci/floci`），MIT 许可证；支持全部分区的 AWS 区域，凭据可为任意非空值（除非显式启用更严格的服务级认证检查）；Web 控制台按需以 sidecar 容器方式启动，不占用启动资源。

---
## 5. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 112,891
- **简介**: Persistent Context Across Sessions for Every Agent – Captures everything your agent does during sessions, compresses it with AI, and injects relevant context back into future sessions. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode + More

### AI 总结
**简介**: Claude-Mem 是一个为 Claude Code 等 AI 编程代理打造的持久化记忆压缩系统，能够跨会话保留上下文，让代理在每次新会话中自动"记住"之前做过的事情。

**核心功能**:
- **会话捕获**：完整记录代理在每次会话中的所有操作与交互内容
- **AI 压缩**：利用 AI 对捕获的会话内容进行压缩提炼，降低存储与注入成本
- **上下文回注**：在未来的会话中自动注入相关历史上下文，实现跨会话的持续记忆
- **多代理兼容**：支持 Claude Code、OpenClaw、Codex、Gemini、Hermes、Copilot、OpenCode 等多种代理工具

**技术亮点**: 基于 TypeScript 开发，要求 Node.js >= 20.0.0；采用 Apache 2.0 开源协议；提供近 30 种语言的国际化文档；曾登上 GitHub Trending 日榜，并被 Awesome Claude Code 收录。

---
## 6. [vercel-labs/agent-desktop](https://github.com/vercel-labs/agent-desktop)
- **语言**: Rust
- **Stars**: 15,217
- **简介**: Computer use CLI for AI agents

### AI 总结
**简介**: Vercel Labs 推出的 AI Agent 桌面操作 CLI 工具，通过操作系统无障碍树让 AI 在 macOS、Windows 和 Linux 上查看并操作桌面应用，无需截图或像素匹配。

**核心功能**:
- 读取桌面应用的无障碍树并以 JSON 返回，每个可操作元素都带有一个 ref 引用
- 支持基于 ref 的点击、输入（type）、赋值（set-value）、剪贴板操作，并可通过重新快照验证结果
- 提供 `snapshot`、`click`、`status`、`permissions` 等命令，统一输出 JSON 信封格式
- 内置与版本匹配的 Agent 指南（skills），涵盖操作循环、ref 规则、验证与重试策略
- 默认无头执行（headless），可选 `--headed` 进行物理输入；支持 `--stdin` 传入敏感文本

**技术亮点**: 使用 Rust 编写，以 CLI 和 C 库双形态发布；核心通过 `PlatformAdapter` trait 抽象平台差异，分别对接 macOS 的 AX API、Windows 的 UI Automation 和 Linux 的 AT-SPI；跨平台支持 x64 与 ARM64，提供 npm、Homebrew 等安装方式，采用 Apache-2.0 协议。

---
## 7. [github/spec-kit](https://github.com/github/spec-kit)
- **语言**: Python
- **Stars**: 147,343
- **简介**: 💫 Toolkit to help you get started with SDD or any other process!

### AI 总结
**简介**: GitHub 开源的 Spec Kit 是一个面向 AI 编程代理的工具包，为其提供结构化流程、可复用模板和可追溯的产出，帮助开发者以规范驱动的方式完成开发任务。

**核心功能**:
- **规范驱动开发（SDD）**：从编写规格说明出发，贯穿规划、实现到收敛的完整开发流程，用于构建功能或应用。
- **缺陷修复**：诊断并修复异常行为，输出原因评估、范围明确的修复方案及验证记录。
- **想法评估**：基于证据判断某个想法是否值得投入，给出继续、澄清或终止的决策。
- **自定义流程**：支持基于可组合原语适配或组装其他开发流程。
- **扩展与预设机制**：通过 Extension 接入外部工具、添加命令与质量门禁，通过 Preset 定制模板、术语和规范标准。
- **工作流编排**：支持自动化提示词、命令、门禁和 Shell 任务，并可通过 overlay 修改已安装工作流。
- **组件目录与离线支持**：提供社区组件目录搜索（extension/preset/workflow/bundle），支持私有目录、认证及离线/防火墙环境部署。

**技术亮点**: 基于 Python 实现；采用"流程 + 可组合原语"的架构设计，核心内置 SDD，缺陷修复与评估以扩展形式按需安装；支持多语言文档（中、日、韩等）；具备多编码代理集成、钩子机制、项目级覆盖和制品溯源等工程化能力。

---
## 8. [The-PR-Agent/pr-agent](https://github.com/The-PR-Agent/pr-agent)
- **语言**: Python
- **Stars**: 14,788
- **简介**: 🚀 PR Agent: The Original Open-Source PR Reviewer. This project is not the Qodo free tier.

### AI 总结
**简介**: PR-Agent 是一个开源、AI 驱动的代码审查代理，由 Qodo 社区维护的遗留项目（注意：并非 Qodo 官方开源免费版）。

**核心功能**:
- 自动化 PR 审查：通过 `/review`、`/improve`、`/ask` 等工具对 Pull Request 进行 AI 分析与改进建议
- 多平台集成：支持 GitHub（含 GitHub Action）、GitLab、BitBucket、Azure DevOps、Gitea
- 多种使用方式：GitHub Action、本地 CLI、Docker、自托管、Webhook 部署
- 大 PR 处理：采用 PR Compression 策略，可有效处理小型和大型 PR
- 高度可定制：基于 JSON 的提示词配置，可自定义审查类别与行为

**技术亮点**: 使用 Python 开发；每个工具仅需单次 LLM 调用（约 30 秒、低成本）；支持 OpenAI GPT、Anthropic Claude、Google Gemini、DeepSeek、Mistral 及通过 LiteLLM 接入的任意模型（如 Azure OpenAI、AWS Bedrock、Vertex AI）；Git 平台 SDK 以可选依赖形式安装。

---
## 9. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)
- **语言**: Python
- **Stars**: 139,021
- **简介**: 利用 AI 大模型和自动化工作流，根据主题或关键词一键生成高清短视频。Generate HD short videos from a topic or keyword with an automated AI workflow.

### AI 总结
**简介**: MoneyPrinterTurbo 是一款基于 AI 大模型的一站式短视频生成工具，只需输入主题或关键词即可自动产出高清短视频。

**核心功能**:
- 根据主题/关键词自动生成视频脚本
- 自动匹配视频素材并生成字幕
- 自动生成背景音乐并合成高清短视频
- 提供 WebUI 与 API 两种使用方式

**技术亮点**: 基于 Python（3.11+）开发，采用自动化 AI 工作流，可接入 Kimi、火山引擎、MiniMax 等多家大模型/API 服务；跨平台支持 Windows、macOS 与 Linux。

---
## 10. [garrytan/gstack](https://github.com/garrytan/gstack)
- **语言**: TypeScript
- **Stars**: 139,368
- **简介**: Use Garry Tan's exact Claude Code setup: 23 opinionated tools that serve as CEO, Designer, Eng Manager, Release Manager, Doc Engineer, and QA

### AI 总结
**简介**: gstack 是 Y Combinator 总裁 Garry Tan 开源的 Claude Code 配置套件，通过 23 个斜杠命令将 AI 编程助手变成一支虚拟工程团队（CEO、设计师、工程经理、发布经理、文档工程师、QA）。

**核心功能**:
- `/office-hours`：审视产品定位并撰写设计文档，供其他技能复用
- `/review`：审查分支代码，发现能通过 CI 但在生产环境出问题的 Bug 并修复
- `/qa`：在真实浏览器中打开 staging URL（或本地 API、CLI、任务、Webhook），复现并修复 Bug
- `/autoplan` + `/ship`：端到端评审计划，执行测试、审查并提交 PR
- `/cso`：运行 OWASP + STRIDE 安全审计
- `/browse`、`/make-pdf`、`/diagram`：浏览器操作与文档、图表生成
- 团队模式：共享仓库自动更新，支持 `required`/`optional` 两种强制级别

**技术亮点**: 基于 TypeScript 开发，要求 Bun v1.4.2+ 与 Claude Code 环境；全部以 Markdown 斜杠命令实现，MIT 协议免费开源；支持 Claude Code 之外的多种 AI Agent（通过 `--host` 参数）；团队模式采用 `stable` 频道（每周一、四发布），每小时静默检查更新，不向仓库引入 vendored 文件。

---
