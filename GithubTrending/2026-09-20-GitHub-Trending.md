---
tags:
  - github-trending
  - daily
date: 2026-09-20
created: 2026-09-20T01:55:42.247Z
---

# 2026-09-20 GitHub Trending Top 10

## 1. [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill)
- **语言**: JavaScript
- **Stars**: 16,442
- **简介**: A coding-agent skill for multi-phase security audits with independently verified, machine-readable findings

### AI 总结
**简介**: Cloudflare 开源的安全审计技能，将编码 Agent 转变为多阶段安全审计器，通过隔离 Agent 协作产出可独立验证、机器可读的漏洞发现。

**核心功能**:
- **六阶段审计流程**：侦察（架构/信任边界/输入面映射）→ 覆盖驱动的漏洞狩猎 → 候选验证（由全新验证者尝试证伪）→ 结构化输出 → 独立记录复核 → 目标中立的报告生成
- **结构化裁决**：将发现分为 `confirmed`（完整溯源+边界化结果）、`needs_validation`（存在未解决事实、无严重性评级）、`rejected`（已证伪）三类，并写入 `findings.json`
- **覆盖账本机制**：通过 `coverage-ledger.json` 跟踪审计覆盖范围，用覆盖批评者发现遗漏，多次运行可叠加复用历史账本与发现
- **多目标攻击面支持**：内置内存安全/二进制、AI/LLM、Web 协议与认证、客户端、供应链、云与部署、RPC 与消息、资源耗尽、数据隔离、桌面/移动与本地 IPC 等狩猎类别
- **零依赖校验工具**：提供 `validate-findings.cjs` 与 `validate-coverage-ledger.cjs` 对输出进行 schema 校验

**技术亮点**: 基于 JavaScript 实现，采用"父 Agent 编排 + 隔离子 Agent"的多智能体架构；每个候选漏洞由全新验证者独立复核，重要替换需再次独立验证，确保结论可复现；该技能是 Cloudflare 漏洞发现框架（vulnerability harness）的雏形与单仓库起点，支持通过 Skills CLI 一键安装。

---
## 2. [trycua/cua](https://github.com/trycua/cua)
- **语言**: HTML
- **Stars**: 24,451
- **简介**: Scale computer-use 2.0 with open-source drivers, cross-OS fleets, and benchmarks for training, evaluation, and data generation.

### AI 总结
**简介**: Cua 是一个开源项目，为 AI 代理提供可操作的计算机环境，涵盖桌面自动化、云端隔离桌面、本地 macOS 虚拟机、专用决策模型及评估基准，支持 Computer-Use 2.0 场景。

**核心功能**:
- **Cua Fleets**: 在云端快速分配隔离的 Linux 桌面，支持运行命令、截图及与应用程序交互
- **CUA-S1**: 专为计算机使用决策设计的小型专用模型，可搭配自有代理或模型使用
- **Cua Driver**: 跨平台（macOS、Windows、Linux）应用检查与操作工具，支持自动化控制
- **Lume**: 在 Apple Silicon 上创建本地 macOS 和 Linux 虚拟机，支持 SSH 连接
- **Cua Bench**: 创建任务、评估代理并导出轨迹，用于训练、评测和数据生成

**技术亮点**: 支持跨操作系统（macOS/Windows/Linux）的桌面自动化；提供云端沙箱 SDK 与本地 VM 双模式；采用模块化架构，用户可自带代理和模型；强调 Computer-Use 2.0 理念，即代理可在同一任务中灵活切换代码、API 和图形界面。

---
## 3. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 97,066
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 一套面向 AI 编码代理的生产级工程技能库，将资深工程师的工作流、质量门禁和最佳实践打包成可复用的技能，让 AI 代理在开发各阶段保持一致行为。

**核心功能**:
- **9 个斜杠命令覆盖开发全生命周期**：`/spec`（定义需求）→ `/plan`（拆解任务）→ `/build`（增量实现）→ `/test`（测试验证）→ `/constraints`（质量约束）→ `/review`（合并前审查）→ `/webperf`（性能审计）→ `/code-simplify`（代码简化）→ `/ship`（发布上线）。
- **自动技能激活**：根据当前任务自动触发对应技能，如设计 API 触发 `api-and-interface-design`，构建 UI 触发 `frontend-ui-engineering`。
- **`/build auto` 自主执行模式**：在规格确定后一次性生成计划并自动实现全部任务，仍保持测试驱动和逐任务提交，遇到失败或高风险步骤会暂停。
- **内置 25 个技能**：涵盖五轴代码审查、需求访谈、TDD（红-绿-重构）等，可通过 CLI 单独或批量安装。

**技术亮点**:
- 基于开放的 [skills CLI](https://github.com/vercel-labs/skills)，一条 `npx skills add` 命令即可安装到 Claude Code、Cursor、Codex、Copilot、Cline 等 70+ 代理工具。
- 支持多种集成方式：CLI 快速安装、Claude Code 插件市场、Cursor 的 `.cursor/skills/` 与 `.mdc` 规则分离、本地克隆开发。
- 强调"规格先于代码""小原子任务""测试即证明""清晰优于炫技"等工程原则，并以命令和技能的形式强制落地。

---
## 4. [coder/coder](https://github.com/coder/coder)
- **语言**: Go
- **Stars**: 15,634
- **简介**: Secure environments for developers and their agents

### AI 总结
**简介**: Coder 是一个自托管的云开发环境和 AI 编程代理平台，通过 Terraform 定义工作空间，并使用安全的 WireGuard 隧道连接。

**核心功能**:
- 使用 Terraform 定义云开发环境（支持 EC2 虚拟机、Kubernetes Pod、Docker 容器等）
- 自动关闭闲置资源以节省成本，实现秒级开发者入职
- 在自有基础设施上运行 AI 编程代理，支持接入任意模型（Anthropic、OpenAI、Google、Bedrock、自托管等）
- 集中式模型治理、成本追踪和审计日志，工作空间内不存储 LLM 凭证

**技术亮点**:
- 基于 Go 语言开发
- 工作空间通过安全的 WireGuard® 隧道连接
- 生产环境支持 PostgreSQL 13+ 数据库，并提供 `*.try.coder.app` 评估用访问地址
- 提供 AI Gateway 用于统一 AI 工具的身份认证、审计和成本控制
- 通过 OpenSSF 最佳实践和安全评分卡认证

---
## 5. [anthropics/claude-code](https://github.com/anthropics/claude-code)
- **语言**: TypeScript
- **Stars**: 146,729
- **简介**: Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands.

### AI 总结
**简介**: Claude Code 是 Anthropic 推出的终端智能编码工具，通过自然语言命令理解代码库、执行日常任务并处理 Git 工作流。

**核心功能**:
- 通过自然语言命令执行常规编码任务、解释复杂代码
- 处理 Git 工作流，支持在终端、IDE 或 GitHub 中通过 @claude 调用
- 提供插件系统，可通过自定义命令和代理扩展功能

**技术亮点**: 基于 TypeScript 开发，需 Node.js 18+ 环境；支持多种安装方式（curl 脚本、Homebrew、WinGet、npm）；内置 `/bug` 命令反馈机制；注重数据隐私保护，限制敏感信息保留期限并禁止将反馈用于模型训练。

---
## 6. [Open-Dev-Society/OpenStock](https://github.com/Open-Dev-Society/OpenStock)
- **语言**: TypeScript
- **Stars**: 16,081
- **简介**: OpenStock is an open-source alternative to expensive market platforms. Track real-time prices, set personalized alerts, and explore detailed company insights — built openly, for everyone, forever free.

### AI 总结
**简介**: OpenStock 是 Open Dev Society 推出的开源金融市场追踪平台，作为昂贵商业行情软件的免费替代方案，支持实时价格追踪、个性化提醒和公司深度洞察。

**核心功能**:
- 实时股价追踪与行情展示
- 个性化价格提醒（支持邮件通知）
- 详细的公司信息与洞察分析
- 基于 TradingView 的图表可视化

**技术亮点**:
- 前端：Next.js + TypeScript + Tailwind CSS + shadcn/ui + Radix UI
- 认证：Better Auth
- 数据存储：MongoDB
- 后台任务：Inngest
- 邮件服务：Nodemailer
- 行情数据：Finnhub + TradingView
- 开源协议：AGPL-3.0（修改或部署需以相同协议开源并署名原作者）

---
## 7. [higgsfield-ai/higgsfield](https://github.com/higgsfield-ai/higgsfield)
- **语言**: Jupyter Notebook
- **Stars**: 4,973
- **简介**: Fault-tolerant, highly scalable GPU orchestration, and a machine learning framework designed for training models with billions to trillions of parameters

### AI 总结
**简介**: Higgsfield 是一个开源、容错、高可扩展的 GPU 编排与机器学习框架，专为训练数十亿到数万亿参数的大模型（如 LLM）而设计。

**核心功能**:
- 为用户的训练任务分配独占或非独占的计算节点资源
- 支持 ZeRO-3 DeepSpeed API 和 PyTorch 完全分片数据并行（FSDP）API，实现万亿参数模型的高效分片
- 提供在分配节点上启动、执行和监控大型神经网络训练的框架
- 通过实验队列管理资源竞争
- 通过与 GitHub 和 GitHub Actions 的无缝集成，支持机器学习的持续集成

**技术亮点**:
- 基于标准 PyTorch 工作流，可兼容 DeepSpeed、Accelerate 或自定义分片方案
- 通过 Docker 和 GitHub Actions 实现自动化部署与实验管理，解决环境版本混乱与配置复杂的问题
- 已在 Azure、LambdaLabs、FluidStack 等云平台上验证，要求节点为 Ubuntu 系统、支持 SSH 及具备 sudo 权限的非 root 用户

---
## 8. [docling-project/docling](https://github.com/docling-project/docling)
- **语言**: Python
- **Stars**: 67,086
- **简介**: Get your documents ready for gen AI

### AI 总结
**简介**: Docling 是一个 Python 文档处理库，可将多种格式的文档解析并转换为适合生成式 AI 使用的结构化数据。

**核心功能**:
- 支持解析 PDF、DOCX、PPTX、XLSX、HTML、EPUB、图片、音频、视频、邮件、LaTeX 等十余种文档格式
- 提供高级 PDF 理解能力，包括页面布局、阅读顺序、表格结构、代码、公式和图像分类
- 统一的 DoclingDocument 表示格式，支持导出为 Markdown、HTML、JSON、DocTags 等多种格式
- 支持扫描件和图片的 OCR 识别，以及基于 ASR 模型的音频/视频转录
- 支持 USPTO 专利、JATS 论文、XBRL 财务报告等特定 XML 模式
- 可本地执行，适用于敏感数据和离线环境
- 提供 LangChain、LlamaIndex、Crew AI、Haystack 等框架的即插即用集成
- 支持 MCP 协议连接智能体，并可通过 API 服务器以服务形式运行
- 提供简洁的 CLI 命令行工具

**技术亮点**: 基于 Python 开发，采用 Pydantic v2 进行数据建模，支持 GraniteDocling 等视觉语言模型；使用 uv 和 Ruff 进行依赖管理与代码检查；项目托管于 LF AI & Data 基金会，采用 MIT 许可证，并遵循 OpenSSF 最佳实践。

---
## 9. [cloudflare/quiche](https://github.com/cloudflare/quiche)
- **语言**: Rust
- **Stars**: 12,026
- **简介**: 🥧 Savoury implementation of the QUIC transport protocol and HTTP/3

### AI 总结
**简介**: Cloudflare 开源的 QUIC 传输协议与 HTTP/3 的 Rust 实现，提供底层 API 处理 QUIC 数据包与连接状态。

**核心功能**:
- 实现 IETF 标准化的 QUIC 传输协议和 HTTP/3
- 提供低层级 API，由应用层负责 I/O（如 socket 处理）与事件循环（含定时器支持）
- 通过 `Config` 对象配置连接参数，包括 QUIC 版本、ALPN、流控、拥塞控制、空闲超时及 TLS 等
- 提供命令行工具 `quiche-client` 与 `quiche-server` 用于测试（非生产环境）
- 支持客户端 `connect()` 与服务端 `accept()` 连接建立，以及 `recv()` 处理入站数据包

**技术亮点**:
- 使用 Rust 编写，配置对象可在多个连接间共享
- 已被 Cloudflare 边缘网络 HTTP/3、Android DNS over HTTP/3 以及 curl 的 HTTP/3 支持所采用
- 采用 BSD-2-Clause 许可证

---
## 10. [asciimoo/hister](https://github.com/asciimoo/hister)
- **语言**: Go
- **Stars**: 5,239
- **简介**: Your own search engine

### AI 总结
**简介**: Hister 是一款用 Go 编写的私有搜索引擎，为你的浏览记录和本地文件建立全文索引，让你重新找回曾经接触过的信息。

**核心功能**:
- **全文索引**：对访问过的网页和本地文件内容建立索引，而非仅索引标题和 URL
- **浏览器自动索引**：通过 Firefox / Chrome 扩展自动保存新访问的页面
- **多端搜索**：支持 Web 界面、终端（TUI / 命令行）以及通过 MCP 接入的 AI 助手
- **强大查询语法**：支持字段过滤、短语、通配符、否定、别名和结果优先级
- **可选语义搜索**：通过自配置的 embeddings 端点按语义查找文档
- **内容导入**：支持爬虫抓取网站，以及导入浏览器历史、书签和本地目录
- **多用户支持**：在共享服务器上隔离各用户的文档与搜索结果

**技术亮点**:
- 使用 Go 1.26 开发，CGO 依赖需要 C 编译器
- 前端基于 Vite 构建，开发时支持热重载与 Go 后端自动重建（借助 air）
- 默认无遥测、无云同步，数据完全存储在自有服务器上，注重隐私
- 提供 Homebrew、Docker、Nix 等多种安装方式
- 采用 AGPLv3 许可证

---
