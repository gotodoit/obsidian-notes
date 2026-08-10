---
tags:
  - github-trending
  - daily
date: 2026-08-10
created: 2026-08-10T01:55:44.139Z
---

# 2026-08-10 GitHub Trending Top 10

## 1. [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent)
- **语言**: TypeScript
- **Stars**: 11,250
- **简介**: A self-improving RLM agent for coding workflows and long-running autonomous tasks.

### AI 总结
**简介**: Prime Agent 是一个开源的、可自我改进的递归语言模型（RLM）智能体，专为编码工作流和长时间运行的自主任务设计。

**核心功能**:
- **程序化一切操作**: 内置持久化 IPython 作为模型工具，文件操作、Shell 命令、工具调用、子代理和上下文管理均通过代码完成
- **内置子代理系统**: 通过 `rlm(...)` 生成真实子代理，支持并行或后台工作，并以编程方式返回结果
- **可自我改进的 Harness**: `/refine` 命令能审查当前轨迹，对补充性 harness 状态进行小规模、基于证据的更新，且支持快照回滚
- **可执行技能**: 技能作为可导入的 Python 包存在，内置技能创建器可将重复工作流转化为项目或个人技能
- **后台会话支持**: 守护进程支撑的代理在终端断开后仍持续运行，可随时重新连接
- **代理间直接通信**: 运行中的代理可互相交换消息和编排任务，无需全部经由用户中转
- **长任务持续执行**: 自动压缩、持久目标、心跳、调度、自主模式和保留子代理确保跨轮次和终端会话的进度保持

**技术亮点**: 基于 TypeScript 构建，核心架构围绕两大抽象——递归语言模型（RLM，将上下文视为变量、工具视为函数调用）和持续 Harness（将提示、记忆、技能描述和子代理规范存储为持久状态）。安装采用带 SHA-256 校验的二进制分发，支持 macOS/Linux，提供完整的 CLI 命令集（agents、attach、resume、status、doctor、update、shutdown）。

---
## 2. [vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag)
- **语言**: Python
- **Stars**: 3,030
- **简介**: The ultimate RAG for your monorepo. Query, understand, and edit multi-language codebases with the power of AI and knowledge graphs

### AI 总结
**简介**: Code-Graph-RAG 是一个面向多语言单体仓库（monorepo）的 RAG 工具，通过解析代码结构构建知识图谱，让你用自然语言查询、理解和编辑整个代码库。

**核心功能**:
- **自然语言问答**：用日常语言提问代码库相关问题，答案基于真实代码结构
- **源码检索**：按名称或意图直接获取任意函数、类、方法或模块的源代码
- **AI 辅助代码编辑**：通过 Agent 直接修改代码，支持结构化搜索与替换（基于 AST 模式匹配）
- **多语言支持**：通过 Tree-sitter 解析混合语言代码库，统一图谱模式管理 monorepo
- **知识图谱构建**：提取函数、类、方法、模块及其关联关系，存储于 Memgraph 图数据库

**技术亮点**:
- 基于 **Tree-sitter** 解析代码，结合 **Memgraph** 构建统一知识图谱
- 引入可插拔 **ast-grep** 分层，支持从单个 YAML 模式文件快速添加新语言（如 Ruby）
- 提供 Agent 工具集，支持跨代码库的结构化（AST 级）搜索与重写
- 企业级支持与持续集成（CI）、代码覆盖率（Codecov）、质量门禁（SonarCloud）等工程化保障

---
## 3. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 140,759
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个开源的 AI 代理（Agent）集合，提供数十个具有独特个性、专业流程和可交付成果的 AI 专家，可一键安装到主流 AI 编程工具中，快速组建你的“AI 梦之队”。

**核心功能**:
- **丰富的 AI 代理库**: 涵盖前端开发、UI 设计、Reddit 社区运营、创意注入、现实核查等多个领域的专业化代理，每个代理都有独特的性格、工作流程和成功指标。
- **多工具集成**: 支持将代理安装到 Claude Code、Cursor、Codex、Gemini CLI、OpenCode、Copilot、Aider、Windsurf 等 15+ 主流 AI 编程工具中。
- **灵活安装方式**: 提供桌面应用（支持 macOS/Linux/Windows，可自动更新）、命令行脚本、手动复制三种安装方式，并支持按团队或单个代理选择性安装。
- **交互式安装向导**: 自动检测已安装的工具，支持 `--division` 和 `--agent` 参数精准安装，并提供 `--dry-run` 预览模式。
- **生产级可用**: 每个代理都经过实战测试，包含真实代码示例、可量化交付物和沟通风格定义。

**技术亮点**: 基于 Shell 脚本实现跨平台安装器，支持多工具配置自动转换；代理文件采用 Markdown 格式定义，包含身份、性格、核心任务、技术交付物等结构化内容；提供官方桌面应用（Agency Agents）实现图形化一键安装与自动更新。

---
## 4. [pranshuparmar/witr](https://github.com/pranshuparmar/witr)
- **语言**: Go
- **Stars**: 20,711
- **简介**: Why is this running? Trace any process, port, container, or file back to what started it - CLI + TUI.

### AI 总结
**简介**: witr 是一个用于回答“为什么这个进程/端口/容器/文件在运行”的命令行工具，通过追踪启动链来揭示系统上各运行实体的因果来源，支持 CLI 输出和交互式 TUI 仪表盘。

**核心功能**:
- **进程溯源**: 追踪任意进程、端口、容器或文件，回溯到其启动的完整链条（如 systemd → PM2 → node）
- **交互式 TUI**: 提供可视化仪表盘，直观展示运行实体的来源和依赖关系
- **机器可读输出**: 支持 JSON 格式输出，便于脚本集成和自动化
- **跨平台支持**: 兼容 Linux、macOS、Windows 和 FreeBSD，提供多种安装方式（脚本、包管理器）
- **浏览器演示**: 提供无需安装的在线模拟环境，方便快速体验

**技术亮点**: 使用 Go 语言开发，编译为单一静态二进制文件，无运行时依赖；支持通过 Homebrew、Conda、AUR、Winget、npm 等主流包管理器分发，并已集成到 Repology 生态中。

---
## 5. [google-deepmind/weathernext](https://github.com/google-deepmind/weathernext)
- **语言**: Python
- **Stars**: 7,101
- **简介**: 

### AI 总结
**简介**: WeatherNext 是 Google DeepMind 和 Google Research 开发的全球中程大气与气旋预报模型系列，包含 WeatherNext 2 (WN2) 及其前代模型 GraphCast 和 GenCast。

**核心功能**:
- **WeatherNext 2 全球天气预报**: 0.25° 分辨率（约30km），可预测 100m 风速，支持从 ECMWF HRES 业务化初始条件直接初始化
- **WeatherNext Cyclones 气旋预报**: 专门用于热带气旋预测，提供多个时间版本（<2023、<2024、<2025），其中 <2025 版本曾在 2025 年大西洋飓风季实况运行
- **WeatherNext Cyclones Mini 轻量版**: 1° 分辨率，适合低内存/算力环境（如本地测试或单 TPU/GPU），同样支持气旋预报
- **多平台数据获取**: 支持通过 Google Cloud（Earth Engine、BigQuery、Vertex AI）、WeatherLab、OpenMeteo 直接访问每日预测数据，无需自行运行模型
- **预训练模型权重**: 提供多个版本的预训练权重文件（.npz 格式），覆盖不同训练数据截止时间

**技术亮点**:
- 采用**联合概率预报**方法（FGN/WN2 技术报告 arXiv:2506.10772），从边际分布实现 skillful 的概率天气预报
- 同时支持**确定性预报**（GraphCast，图神经网络）和**扩散模型集成预报**（GenCast）两种前代架构
- 模型输出经业务化验证，2025 年大西洋飓风季实况运行，论文发表于 Nature（s41586-026-10953-2）

---
## 6. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 85,172
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: agent-skills 是一个为 AI 编码代理提供生产级工程技能的开源项目，将资深工程师的工作流程、质量门禁和最佳实践打包成技能，供 AI 代理在开发各阶段遵循。

**核心功能**:
- **8 个斜杠命令**: 映射完整开发生命周期，包括 `/spec`（需求定义）、`/plan`（任务规划）、`/build`（增量构建）、`/test`（测试验证）、`/review`（代码审查）、`/webperf`（性能审计）、`/code-simplify`（代码简化）和 `/ship`（生产发布）
- **自动技能激活**: 根据当前任务自动触发相应技能，如设计 API 时激活 `api-and-interface-design`，构建 UI 时激活 `frontend-ui-engineering`
- **`/build auto` 自动模式**: 一次批准计划后自动执行所有任务，每个任务仍保持测试驱动和独立提交，遇到失败或风险步骤会自动暂停
- **跨 70+ 代理支持**: 通过 `npx skills add` 一键安装到 Claude Code、Cursor、Codex、Copilot、Cline 等主流 AI 编码工具
- **原生集成**: 支持 Claude Code 插件市场安装和 Cursor 的 `.cursor/skills/` 目录同步
- **24 项技能可选**: 支持按需单独安装特定技能（如 `code-review-and-quality`、`interview-me`、`test-driven-development`）

**技术亮点**: 基于 Skills CLI（Vercel Labs 开源）构建，采用技能包与共享检查清单（`references/`）分离的模块化架构，以 JavaScript 编写，遵循"规范先行、小步提交、测试即证明"的工程原则。

---
## 7. [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis)
- **语言**: Python
- **Stars**: 61,239
- **简介**: LLM 驱动的多市场股票智能分析系统：多源行情、实时新闻、决策看板与自动推送，支持零成本定时运行。 LLM-powered multi-market stock analysis system with multi-source market data, real-time news, decision dashboard, automated notifications, and cost-free scheduled runs.

### AI 总结
**简介**: 一个基于 AI 大模型的多市场股票智能分析系统，支持 A股/港股/美股/日股/韩股/台股，每日自动生成决策报告并推送到多个通讯平台，可零成本通过 GitHub Actions 定时运行。

**核心功能**:
- AI 决策报告：自动生成核心结论、评分、趋势判断、买卖点位、风险警报、催化因素和操作检查清单
- 多市场数据聚合：覆盖 6 个股票市场及 ETF，整合行情、K 线、技术指标、新闻、公告、基本面等数据
- Web/桌面工作台：支持手动分析、任务进度跟踪、历史报告查看、回测、持仓管理和主题切换
- Agent 策略问股：支持多轮追问，内置均线、缠论、波浪、趋势、热点、事件、成长、预期等 15 种策略
- 智能导入与补全：支持图片、CSV/Excel、剪贴板导入，自动补全股票代码/名称/拼音/别名
- 自动化与推送：支持 GitHub Actions、Docker、本地定时任务、FastAPI 服务，推送至企业微信/飞书/Telegram/Discord/Slack/邮件

**技术亮点**: 采用 Python 3.10+ 构建，支持多种 AI 模型（Gemini、OpenAI 兼容、DeepSeek、通义千问、Claude、Ollama 等），集成多源免费行情数据（AkShare、Baostock、YFinance 等）和多种新闻搜索 API，支持 Docker 部署与 GitHub Actions 零成本定时运行，具备完整的 CI 流程和 MIT 开源许可。

---
## 8. [goauthentik/authentik](https://github.com/goauthentik/authentik)
- **语言**: Python
- **Stars**: 24,294
- **简介**: The authentication glue you need.

### AI 总结
**简介**: authentik 是一个开源的身份提供商（IdP），为现代应用提供统一的单点登录（SSO）认证解决方案。

**核心功能**:
- 支持多种认证协议：SAML、OAuth2/OIDC、LDAP、RADIUS 等
- 提供企业级身份管理，可替代 Okta、Auth0、Entra ID 等商业 IdP 产品
- 支持多种部署方式：Docker Compose、Kubernetes（Helm Chart）、AWS CloudFormation 和 DigitalOcean Marketplace
- 提供明亮/暗黑两种主题的现代化管理界面和用户门户

**技术亮点**: 基于 Python 开发，采用核心服务（core）、边缘代理（outpost）和 Web 前端分离的架构设计，支持从个人实验室到大型生产集群的灵活扩展，代码开源（MIT 许可证），企业版提供额外功能。

---
## 9. [google/skills](https://github.com/google/skills)
- **语言**: Python
- **Stars**: 17,257
- **简介**: Agent Skills for Google products and technologies

### AI 总结
**简介**: 这是 Google 官方提供的 Agent Skills 仓库，包含用于 Google 产品和技术（尤其是 Google Cloud）的预构建技能集合，可通过 npx 快速安装到 AI 代理中。

**核心功能**:
- **Google Cloud 入门技能**: 提供认证、基础搭建、平台入门引导等上手技能
- **多产品解决方案技能**: 涵盖架构设计、数据分析、数据湖仓、AI 代理部署、多模态流式 AI、RAG 企业搜索、无服务器 Web 应用等端到端解决方案
- **AI/ML 平台技能**: 支持 Agent Platform 的模型部署、调优、推理、提示词管理、RAG 引擎、模型注册、故障排查等全生命周期管理，以及 BigQuery AI/ML、Gemini API 系列技能
- **基础设施技能 (GKE)**: 提供 GKE 集群创建、网络、存储、自动扩缩容、备份容灾、多租户、生产化、可靠性、升级维护、TPU 监控等 20+ 项 Kubernetes 运维技能

**技术亮点**: 基于 Agent Skills 开放标准，采用 Python 编写，支持通过 `npx skills add google/skills` 命令行工具选择性安装，技能模块化组织，覆盖从入门到生产级部署的完整 Google Cloud 技术栈。

---
## 10. [Comfy-Org/ComfyUI](https://github.com/Comfy-Org/ComfyUI)
- **语言**: Python
- **Stars**: 125,580
- **简介**: The most powerful and modular diffusion model GUI, api and backend with a graph/nodes interface.

### AI 总结
**简介**: ComfyUI 是一个功能强大且模块化的 AI 内容创作引擎，以节点图/图形界面为核心，支持图像、视频、3D 模型、音频等多种内容生成，并提供 API 和后端集成能力。

**核心功能**:
- **可视化节点图工作流**: 通过无代码的节点图界面构建和复用图像、视频、音频、3D 和文本工作流，支持子图复用、工作流模板和应用模式（App Mode）。
- **广泛的模型支持**: 原生支持最新的开源模型（如 Stable Diffusion 系列、Flux.1/2、Wan 2.1/2.2、HunyuanVideo 等），并通过 API 节点接入最佳闭源模型（如 Nano Banana、Seedance、Hunyuan3D）。
- **多平台与部署方式**: 支持 Windows、Linux 和 macOS，提供桌面应用、Windows 便携版、手动安装以及官方云服务（Comfy Cloud）多种使用方式。
- **生产级 API 集成**: 提供本地 API 端点，可无缝集成到生产管道和应用中，支持异步队列、部分图重执行等高级特性。

**技术亮点**: 基于 Python 构建，采用异步队列调度和部分图重执行机制，具备智能 VRAM/RAM 管理和模型卸载功能，支持量化模型，能够高效地在本地执行复杂工作流。

---
