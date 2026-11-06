---
tags:
  - github-trending
  - daily
date: 2026-11-06
created: 2026-11-06T01:55:43.357Z
---

# 2026-11-06 GitHub Trending Top 10

## 1. [NVIDIA/auto-ontology](https://github.com/NVIDIA/auto-ontology)
- **语言**: Python
- **Stars**: 7,434
- **简介**: Auto Ontology is a Python framework for building semantic, graph-based reasoning layers over data. It enables deterministic query generation, better context retrieval, and more explainable AI for LLM and agent workflows.

### AI 总结
**简介**: NVIDIA Auto Ontology 是一个基于 Python 的开源框架，用于在数据之上构建语义化、图化的推理层，为 LLM 与智能体工作流提供确定性的查询生成、更优的上下文检索和更可解释的 AI 能力。

**核心功能**:
- **发现（Discover）**：从企业元数据生成本体，接入已有的本体与语义模型，构建面向 AI 的知识图谱。
- **锚定（Ground）**：为指标、实体和关系提供可信的业务含义，并对齐跨系统间不一致的定义。
- **校验（Validate）**：依据经过认证的定义与血缘检查生成的查询，并在每个答案中返回来源溯源信息。
- **暴露（Expose）**：通过 MCP、CLI 和 API 将上下文提供给任意智能体框架。
- **学习（Learn）**：将经过认证的修正与使用反馈回本体，使共享上下文随每次提问持续改进。
- **自然语言查询结构化数据**：由 NVIDIA NIM 驱动，将问题翻译为 SQL 并在连接的数据库上执行。

**技术亮点**:
- 前端采用 Next.js 16（React 19、TypeScript、Tailwind CSS 4）、Better Auth 与 Prisma，提供聊天、分析、数据目录等 Web UI。
- 后端基于 FastAPI（Python 3.12+）与 LangChain，负责对话/NL-to-SQL、目录与数据源 API；另有独立的 FastAPI 摄取 worker 负责表格数据嵌入。
- 使用 Postgres + pgvector 同时承载应用元数据、目录与本体以及向量存储；可选集成 HashiCorp Vault 安全存储连接凭据。
- 通过模型三元组（`<PREFIX>_ENDPOINT`、`<PREFIX>_API_KEY`、`<PREFIX>_MODEL`）灵活配置推理、非推理、嵌入与重排模型，默认使用 NVIDIA NIM 端点。
- 支持 Helm Chart（Kubernetes）与 Docker Compose（本地）两种部署方式。
- 采用 Apache License 2.0 开源许可，当前不接受外部贡献。

---
## 2. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 315,308
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: Matt Pocock 分享的日常工程实践用 AI Agent 技能集合，强调小巧、可组合、可控，而非"氛围编程"。

**核心功能**:
- `/grill-me` 与 `/grill-with-docs`：通过"拷问式"提问帮助用户在动手前与 Agent 对齐需求，避免理解偏差
- `/triage`：配合用户自定义标签进行工单分类管理
- `/setup-matt-pocock-skills`：每个仓库运行一次，配置 issue 跟踪器（GitHub/GitLab/本地文件等）、标签与文档保存位置
- 支持 Claude Code、Codex、GitHub Copilot、Gemini CLI 及其他 Agent（cursor、opencode、devin、windsurf、amp、pi 等）

**技术亮点**: 以 Shell 编写，基于插件市场与 `npx skills` 分发，支持自动或手动更新；技能设计为小而可组合、模型无关，可与任意 LLM 配合使用，区别于 GSD、BMAD、Spec-Kit 等"接管流程"的重型方案。

---
## 3. [garrytan/gstack](https://github.com/garrytan/gstack)
- **语言**: TypeScript
- **Stars**: 139,970
- **简介**: Use Garry Tan's exact Claude Code setup: 23 opinionated tools that serve as CEO, Designer, Eng Manager, Release Manager, Doc Engineer, and QA

### AI 总结
**简介**: gstack 是 Y Combinator 总裁 Garry Tan 开源的 Claude Code 配置方案，通过 23 个斜杠命令把 AI 编程助手变成一支虚拟工程团队（CEO、设计师、工程经理、发布经理、文档工程师、QA），全部基于 Markdown 实现，MIT 协议免费。

**核心功能**:
- `/office-hours`：扮演 CEO 角色，挑战你的产品定位并产出设计文档，供其他技能读取
- `/review`：代码审查，找出能通过 CI 但在生产环境出问题的 Bug，并修复明显问题
- `/qa`：启动真实浏览器访问 staging URL（或本地 API/CLI/任务/webhook），复现并修复 Bug
- `/autoplan` 与 `/ship`：端到端评审计划，并自动执行测试、审查和提交 PR
- `/cso`：安全官角色，运行 OWASP + STRIDE 审计
- 团队模式：一条命令让仓库内所有队友自动获得 gstack 并保持自动更新

**技术亮点**: TypeScript 实现；依赖 Claude Code、Git、Bun v1.4.2+（Windows 需 Node.js）；推荐搭配 Aside 浏览器以复用真实登录会话；支持 `--host auto` 安装到 Codex 等多种 AI Agent 宿主；团队模式采用 `stable` 发布通道（每周一、四发版）并带每小时一次的静默自动更新检查。

---
## 4. [Usagi-org/ai-goofish-monitor](https://github.com/Usagi-org/ai-goofish-monitor)
- **语言**: Python
- **Stars**: 17,603
- **简介**: 基于 Playwright 和AI实现的闲鱼多任务实时/定时监控与智能分析系统，配备了功能完善的后台管理UI。帮助用户从闲鱼海量商品中，找到心仪产品。

### AI 总结
**简介**: 基于 Playwright 与 AI 的闲鱼多任务实时/定时监控系统，配备完整 Web 管理界面，帮助用户从海量商品中精准筛选心仪产品。

**核心功能**:
- **Web 可视化管理**：任务、账号、AI 标准、运行日志与结果浏览一站式管理
- **AI 驱动任务创建**：支持自然语言描述需求，由多模态模型深度分析商品
- **多任务并发监控**：每个任务可独立配置关键词、价格、筛选条件与 AI Prompt
- **高级筛选**：支持包邮、发布时间范围、省/市/区三级区域筛选
- **多渠道即时通知**：支持 ntfy.sh、企业微信、Bark、Telegram、Webhook 等
- **定时调度**：通过 Cron 配置周期性监控任务
- **账号与代理轮换**：多账号管理、任务绑定账号、代理池轮换与失败重试

**技术亮点**:
- 技术栈：Python（FastAPI 后端）+ Playwright（浏览器自动化）+ 前端 Web UI（Vite 构建）
- 存储：SQLite 作为主存储，自动建库建表并兼容导入旧版 JSON 数据
- 部署：支持 Docker 一键部署，镜像内置 Chromium，无需宿主机额外安装浏览器
- 架构：AI 任务创建采用后台异步 Job 流程，支持进度轮询；提供任务创建、登录校验等 REST API

---
## 5. [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling)
- **语言**: Python
- **Stars**: 98,032
- **简介**: 🕷️ The BEST Web Scraping framework that handles everything from a single request to a full-scale crawl! Don't be shy, join here: https://discord.gg/EMgGbDceNQ and follow here for daily tips and tricks: https://x.com/Scrapling_dev

### AI 总结
**简介**: Scrapling 是一个 Python 编写的现代 Web 抓取框架，覆盖从单次请求到大规模爬取的完整场景。

**核心功能**:
- 灵活的选择器（Selection methods），用于高效解析和提取页面数据
- 多种 Fetcher（抓取器），适配不同请求与反爬场景
- Spiders 爬虫架构，支持大规模爬取任务
- 代理与反封锁（proxy & blocking）处理能力
- 提供 AI Agent Skill 与 OpenClaw Skill 集成，便于在 AI 工作流中使用

**技术亮点**: 基于 Python 构建，发布至 PyPI 并提供 Docker 镜像；拥有完整文档（Read the Docs）、CI 测试流程，以及 Discord 社区和 X 渠道支持；README 提供简体中文等多语言版本。

---
## 6. [vercel-labs/agent-desktop](https://github.com/vercel-labs/agent-desktop)
- **语言**: Rust
- **Stars**: 16,930
- **简介**: Computer use CLI for AI agents

### AI 总结
**简介**: Vercel Labs 推出的 AI Agent 计算机操作 CLI 工具，通过操作系统无障碍树（accessibility tree）让 AI 直接观察和操控 macOS、Windows、Linux 桌面应用，无需截图或像素匹配。

**核心功能**:
- **快照与元素引用**：读取桌面应用的无障碍树并以 JSON 返回，每个可交互元素带唯一 `ref`，Agent 通过 ref 执行点击、输入等操作
- **观察-操作循环**：Agent 执行操作后重新读取 UI 验证结果，循环逻辑由调用方 Agent 自行实现（工具本身不含模型）
- **多命令支持**：`snapshot`、`click`、`type`、`set-value`、`clipboard-set` 等，统一输出单个 JSON 信封
- **无头模式**：默认通过无障碍 API 操作，不移动指针、不抢占焦点；`--headed` 可启用物理输入
- **密集应用导航**：支持 `--skeleton` 先映射整体结构，再用 `--root` 下钻到具体区域
- **多安装方式**：npm 全局安装、GitHub Releases 原生包、Homebrew，含 x64/ARM64 原生二进制

**技术亮点**: Rust 编写，以 CLI 和 C 库两种形式分发；通过 `agent-desktop-core` 与 `PlatformAdapter` trait 抽象跨平台实现；基于无障碍树而非视觉方案，天然轻量且无需 GPU；ref 绑定快照，UI 变化时返回 `STALE_REF`/`AMBIGUOUS_TARGET` 强制重新观察，保证操作可靠性；支持 `--stdin` 传递敏感文本避免出现在进程参数中。

---
## 7. [max-sixty/worktrunk](https://github.com/max-sixty/worktrunk)
- **语言**: Rust
- **Stars**: 11,530
- **简介**: Worktrunk is a CLI for Git worktree management, designed for parallel AI agent workflows

### AI 总结
**简介**: Worktrunk 是一个用 Rust 编写的 Git worktree 管理命令行工具，专为并行运行 AI 智能体（如 Claude Code、Codex）的工作流而设计，让 worktree 的使用像分支一样简单。

**核心功能**:
- 三个核心命令简化 worktree 操作：通过分支名直接寻址 worktree，路径由可配置模板自动计算，无需手动输入冗长的 `git worktree add` 和 `cd` 命令
- 支持并行 AI 智能体工作流：每个智能体拥有独立工作目录，可同时管理 5-10+ 个并行任务而不互相干扰
- 提供 hooks 自动化本地工作流，并支持 copy-on-write 构建缓存，简化多并行变更场景下的日常操作
- 命令既接受分支名，也接受 worktree 的路径，操作灵活

**技术亮点**: 使用 Rust 语言开发；MIT 或 Apache-2.0 双许可；提供完整文档站点（worktrunk.dev）；具备 CI 与 Codecov 覆盖率保障；发布后迅速成为最受欢迎的 git worktree 管理器之一。

---
## 8. [google/skills](https://github.com/google/skills)
- **语言**: Python
- **Stars**: 22,396
- **简介**: Agent Skills for Google products and technologies

### AI 总结
**简介**: 该仓库提供面向 Google 产品与技术（含 Google Cloud）的 Agent Skills 集合，帮助 AI Agent 快速获得云端开发与架构能力。

**核心功能**:
- 通过 `npx skills add google/skills` 一键安装技能，可选择具体技能、目标 Agent 及安装范围（项目级或全局）
- 支持 `npx skills update` 更新已安装技能，并可清理过时技能
- 覆盖 Google Cloud 入门：IAM 认证授权、基础架构搭建、上云引导
- 提供多产品解决方案技能：解决方案架构工作流、多 Agent 安全、Agentic 分析、开放数据湖仓、AI Agent 构建部署、AlloyDB 混合搜索、RAG 企业搜索、GKE AI 迁移、无服务器 Web 应用等
- 提供 AI/ML 技能：Agent Platform 的审计、告警、端点、评估、推理、模型部署与调优、Prompt 管理、RAG Engine、故障排查，以及 Gemini API、Genkit（Dart/Go/JS/Python）、Live API、MCP Server 等

**技术亮点**: 基于 Agent Skills 开放规范（agentskills.io），通过 npm/npx 分发；技能按云入门、多产品方案、AI/ML 分类组织，每个技能对应独立目录；主要语言为 Python，深度集成 Google Cloud、Gemini、BigQuery、GKE、AlloyDB、Apigee 等生态。

---
## 9. [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser)
- **语言**: Rust
- **Stars**: 45,928
- **简介**: Browser automation CLI for AI agents

### AI 总结
**简介**: agent-browser 是 Vercel Labs 推出的原生 Rust CLI 工具，为 AI Agent 提供可逐条命令驱动的浏览器自动化能力。

**核心功能**:
- `snapshot` 将页面转换为紧凑的可访问性树文本，每个元素附带 `@e1` 形式的引用，Agent 可基于引用执行点击等操作
- 浏览器在命令之间保持打开状态，每步操作只需一次简短的 shell 调用，形成“快照 → 操作 → 再快照验证”的循环
- 支持 CSS 选择器、文本、XPath 及语义定位器（如 `find role button click --name "Submit"`）
- 点击目标隐藏、禁用、超出视口或被遮挡时明确报错而非误报成功
- 内置与 CLI 版本匹配的 skills，可通过 `agent-browser skills get core` 加载给 Agent 使用

**技术亮点**:
- 原生 Rust 实现，通过后台守护进程经 Chrome DevTools Protocol 控制浏览器
- 每个 `--session` 拥有独立守护进程与浏览器实例，默认空闲一小时后关闭无头浏览器并保存状态
- 默认使用 Chrome for Testing，另可附加运行中的 Chrome（`--cdp`/`--auto-connect`）、切换 Lightpanda/Obscura 引擎、驱动 iOS 模拟器中的 Mobile Safari，或接入 Browserbase、Browserless、Kernel 等云浏览器
- 支持 npm、Homebrew、npx 多种安装方式，采用 Apache-2.0 许可证

---
## 10. [scenario-labs/skills](https://github.com/scenario-labs/skills)
- **语言**: Python
- **Stars**: 3,091
- **简介**: Get production-ready images, video, audio, and 3D from any AI agent: skills that pick the right model, price before spending, and keep characters and brands consistent through the Scenario MCP, plus expert teams that drive Blender, Maya, ZBrush, Unreal, and Unity.

### AI 总结
**简介**: Scenario Agent Skills 是一套面向 AI 编程代理（Claude Code、Cursor、Codex、Copilot 等 70+ 工具）的 Agent Skills 集合，通过 Scenario MCP 服务器生成生产级图像、视频、音频、3D 资产，并提供驱动 Blender、Maya、ZBrush、Unreal、Unity 等专业软件的专家技能团队。

**核心功能**:
- 通过 Scenario MCP 生成图像、视频、音频、纹理、天空盒、3D 资产及自定义训练模型
- 自动选择合适模型、生成前预估成本，并在多次生成中保持角色与品牌一致性
- 提供按角色/目标分组的技能包（如 2D 艺术家、制作人、游戏美术、ChatGPT 宠物等），支持一键安装
- 专家工具族可驱动本机安装的 DCC 软件与游戏引擎（ZBrush、Blender、Maya、Unreal Engine、Unity、Godot、Roblox Studio），源自专家教程、会议演讲与官方文档

**技术亮点**: 遵循 Agent Skills 开放格式（agentskills.io）；基于 Python 实现；提供 CI 工作流与 OpenSSF Scorecard 安全评分；采用 MIT 许可证；通过 npx 命令按技能或技能组灵活安装。

---
