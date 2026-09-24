---
tags:
  - github-trending
  - daily
date: 2026-09-24
created: 2026-09-24T01:55:42.277Z
---

# 2026-09-24 GitHub Trending Top 10

## 1. [anthropics/financial-services](https://github.com/anthropics/financial-services)
- **语言**: Python
- **Stars**: 36,967
- **简介**: 

### AI 总结
**简介**: Anthropic 推出的金融服务 AI 代理工具集，为投资银行、股票研究、私募股权和财富管理等场景提供可复用的智能代理、技能和数据连接器。

**核心功能**:
- **代理（Agents）**：覆盖全流程工作流，包括 Pitch Agent（路演材料生成）、Market Researcher（行业研究）、Earnings Reviewer（财报解读）、Model Builder（Excel 财务建模）、GL Reconciler（总账对账）、Month-End Closer（月末结账）、KYC Screener（客户尽职调查）等
- **垂直插件（Vertical Plugins）**：按金融垂直领域打包的技能、斜杠命令和数据连接器，支持 `/comps`、`/dcf`、`/earnings` 等快捷操作，可独立安装
- **双模式部署**：同一套系统提示和技能，既可作为 Claude Cowork 插件安装，也可通过 Claude Managed Agents API 部署到自有工作流引擎中
- **合作伙伴插件**：支持 LSEG、S&P Global 等第三方构建的插件

**技术亮点**:
- 基于 Python 开发，提供 `deploy-managed-agent.sh`、`validate.py`、`orchestrate.py` 等脚本工具链
- 每个代理插件自包含，内置所需技能，安装即用
- 提供 Managed Agent cookbook（`agent.yaml`、子代理配置、安全说明）支持 API 化部署
- 包含 Claude for Microsoft 365 插件的管理配置工具
- 所有输出均需人工审核确认，不构成投资建议，定位为辅助分析师起草工作产品

---
## 2. [google/ax](https://github.com/google/ax)
- **语言**: Go
- **Stars**: 9,128
- **简介**: Google's open agentic orchestration runtime

### AI 总结
**简介**: AX 是 Google 开源的智能体编排运行时，基于 Go 编写，用于在集群中大规模运行自主智能体工作负载。

**核心功能**:
- **Task**：在隔离沙箱中运行不可信智能体代码，支持 CPU/内存限制
- **Workspace**：预配置 Git 仓库、MCP 服务器和技能包，让智能体启动即就绪
- **Gateway**：通过显式主机白名单锁定出站网络流量
- **Model**：配置平台使用的 LLM 及凭据（来自 Kubernetes Secret）
- **生命周期管理**：支持 `ax suspend`/`ax resume` 暂停恢复、`ax ssh` 进入运行中的智能体
- **声明式清单**：所有配置以 `ax.io/v1alpha1` YAML 清单表达，一条命令即可应用

**技术亮点**:
- 构建于 [Agent Substrate](https://github.com/agent-substrate/substrate) 之上实现沙箱化执行，单集群可运行数十亿任务
- 使用体验类似 Kubernetes，CLI 采用 `kubectl` 风格（`apply`/`get`/`describe`/`watch`/`delete`）
- 控制平面通过 gRPC 通信，使用 `ko` 构建部署，依赖 Redis
- 注意：项目仍处于活跃开发阶段，稳定版发布前可能引入重大破坏性变更

---
## 3. [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates)
- **语言**: Python
- **Stars**: 31,514
- **简介**: CLI tool for configuring and monitoring Claude Code

### AI 总结
**简介**: davila7/claude-code-templates 是一个用于配置和监控 Anthropic Claude Code 的 CLI 工具，提供即用型 AI 代理、自定义命令、设置、钩子、MCP 集成和项目模板。

**核心功能**:
- 提供 100+ 现成的 AI 代理、命令、设置、钩子和 MCP 集成，可通过交互式 Web 界面 [aitmpl.com](https://aitmpl.com) 浏览和安装
- 支持通过 `npx claude-code-templates@latest` 一键安装完整开发栈或指定组件（如 `--agent`、`--command`、`--mcp` 等）
- 支持外部集成（MCP），例如连接 Bright Data 实现网页搜索、抓取和结构化数据源
- 提供配置和监控 Claude Code 的能力

**技术亮点**: 基于 Python 开发，通过 npm 包分发（`npx` 即可运行），采用 CLI 交互式安装方式；项目获得 Vercel OSS、Neon、Claude for Open Source 等开源计划支持，采用 MIT 许可证。

---
## 4. [BuilderIO/agent-native](https://github.com/BuilderIO/agent-native)
- **语言**: TypeScript
- **Stars**: 6,568
- **简介**: A framework for building agentic apps

### AI 总结
**简介**: Agent-Native 是一个开源 TypeScript 框架，用于构建将自主智能体能力与专用 UI 配对的智能体应用。

**核心功能**:
- **共享动作（Shared Actions）**：每个能力只需定义一次，智能体将其作为工具调用，UI 从代码中调用，两条路径共享相同的验证、权限和实现。
- **共享数据（Shared Data）**：智能体的工作结果出现在 UI 中，UI 中的操作也对智能体可见。
- **共享应用状态（Shared Application State）**：智能体可接收相关 UI 状态，如当前页面、选中记录或活跃视图。
- **内置能力**：包含智能体聊天、认证与权限、技能与记忆、自动化、智能体团队协作，以及 PostgreSQL 后端（生产用 PostgreSQL，本地用 PGlite）。
- **多协议暴露**：动作可同时通过 UI、HTTP、MCP、A2A 和 CLI 暴露。

**技术亮点**:
- 基于 TypeScript，使用 Zod 进行 schema 验证。
- 通过 `defineAction` 统一动作定义，一次编写即可在 UI、智能体、HTTP、MCP、A2A、CLI 多端复用。
- 支持任意 Nitro 兼容主机部署，可自带 LLM、SQL 数据库、工具和基础设施。
- 提供 `npx @agent-native/core` 快速创建项目的脚手架命令。

---
## 5. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 290,699
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套为编码智能体设计的完整软件开发方法论，基于可组合的技能（skills）和初始指令构建，让智能体自动遵循规范化开发流程。

**核心功能**:
- **需求澄清**：智能体不会直接写代码，而是先询问用户真正想做什么，逐步梳理出规格说明
- **分块设计评审**：将设计以易于阅读和消化的短片段呈现给用户确认
- **实施计划生成**：产出足够清晰的计划，强调红/绿 TDD、YAGNI 和 DRY 原则
- **子智能体驱动开发**：启动多个子智能体逐项完成工程任务，自动检查、审查并持续推进，可自主工作数小时不偏离计划
- **自动触发**：技能自动触发，无需用户额外操作

**技术亮点**:
- 基于 Shell 实现，采用可组合技能（composable skills）架构
- 支持广泛的编码智能体平台：Claude Code、Antigravity、Codex App/CLI、Cursor、Devin CLI、Factory Droid、Gemini CLI、GitHub Copilot CLI、Grok Build CLI、Kimi Code、OpenCode、Pi、Qwen Code、Hermes Agent、Muse 等
- 各平台安装方式独立，多以插件/扩展形式集成，支持市场安装或直接从仓库安装
- 提供商业支持渠道（企业级支持、额外工具和管理支出）

---
## 6. [dream-num/univer](https://github.com/dream-num/univer)
- **语言**: TypeScript
- **Stars**: 16,361
- **简介**: The Office Harness for AI Agents — Spreadsheets, Docs, Slides, Canvas, Relational Tables, and PDF in one runtime.

### AI 总结
**简介**: Univer 是一个开源的全栈同构 Office SDK，用于在自有产品中嵌入电子表格、文档和演示文稿等生产力体验。

**核心功能**:
- 支持电子表格、文档、演示文稿、Canvas、关系型表格和 PDF 的统一运行时
- 提供插件化架构，可按需组合、替换、懒加载或扩展功能
- 提供统一的 Facade API，覆盖工作簿、区域、公式和文档操作
- 支持浏览器端 UI 应用和 Node.js 无头处理，适用于 AI 代理和自动化场景
- 内置公式引擎和 Canvas 渲染，适配大规模复杂工作簿
- 支持深色/浅色主题，提供框架适配器和预设

**技术亮点**:
- 基于 TypeScript 开发，采用同构设计，浏览器与 Node.js 共享同一套架构
- 插件优先架构，支持自定义插件、命令、服务和 UI 组件扩展
- Canvas 渲染 + 专用公式引擎，保障复杂工作簿的响应性能
- 无头运行能力，可作为 AI 基础设施支撑代理和服务器端工作流

---
## 7. [Open-Dev-Society/OpenStock](https://github.com/Open-Dev-Society/OpenStock)
- **语言**: TypeScript
- **Stars**: 18,854
- **简介**: OpenStock is an open-source alternative to expensive market platforms. Track real-time prices, set personalized alerts, and explore detailed company insights — built openly, for everyone, forever free.

### AI 总结
**简介**: OpenStock 是 Open Dev Society 推出的开源金融市场追踪平台，作为昂贵商业行情平台的免费替代品，支持实时价格追踪、个性化提醒和公司深度洞察。

**核心功能**:
- 实时股价追踪与行情展示
- 个性化价格提醒（通过邮件通知）
- 详细的公司信息与洞察分析

**技术亮点**:
- **前端**: Next.js + TypeScript + Tailwind CSS + shadcn/ui + Radix UI
- **认证**: Better Auth
- **数据库**: MongoDB
- **后台任务**: Inngest（处理异步任务与定时调度）
- **邮件**: Nodemailer
- **数据源**: TradingView（图表）+ Finnhub（行情数据）
- **代码审查**: CodeRabbit
- **许可证**: AGPL-3.0（修改、分发或部署需以相同许可证开源并署名原作者）

---
## 8. [agent-substrate/substrate](https://github.com/agent-substrate/substrate)
- **语言**: Go
- **Stars**: 3,514
- **简介**: Agent Substrate: the core system

### AI 总结
**简介**: Agent Substrate 是一个面向自主智能体时代的安全默认执行运行时，基于 Go 语言开发，可在标准容器运行时基础上实现 10 倍密度的沙箱运行与高效多路复用。

**核心功能**:
- **Actor 生命周期管理**：支持创建/销毁、挂起/恢复等操作，恢复延迟低于 500ms，每秒可处理 500+ 次挂起/恢复激活
- **实时调度与流量路由**：将大量 Actor（智能体应用）映射到少量 Worker 上，实时分配并路由传入流量
- **状态持久化**：通过全状态快照，在休眠周期中完整保留易失性内存和文件系统状态
- **多沙箱技术支持**：兼容 microVM 和 gVisor 等多种沙箱技术，提供统一的生命周期操作

**技术亮点**:
- **零信任隔离**：原生内核级和网络级隔离，安全默认设计
- **高密度多路复用**：利用智能体应用大部分时间处于空闲的特性，实现 30 倍以上的超配（oversubscription）
- **基于 Kubernetes**：复用 K8s 的 Pod 和自动扩缩容能力进行基础设施管理，同时提供智能体专属调度以降低延迟
- **框架无关**：管理标准 OCI 容器，兼容 ADK、LangChain、Claude Code、MCP 等多种智能体框架
- **低倾向性设计**：不绑定特定智能体 SDK，而是作为大规模运行智能体的通用系统

> ⚠️ 项目处于早期开发阶段，API 可能变更，暂不适合生产环境使用。

---
## 9. [strands-agents/harness-sdk](https://github.com/strands-agents/harness-sdk)
- **语言**: Python
- **Stars**: 7,861
- **简介**: Build an agent harness and control it end-to-end. Open-source SDK for production AI agents in Python & TypeScript - any model, any cloud.

### AI 总结
**简介**: Strands Agents 是一个开源 SDK，用于在 Python 和 TypeScript 中构建和运行生产级 AI 代理，采用模型驱动方式，几行代码即可搭建代理。

**核心功能**:
- **生命周期控制**：支持轮次限制、Token 预算、取消操作和停止原因管理
- **工具与结构化输出**：内置工具系统和结构化输出能力
- **MCP 支持**：集成 Model Context Protocol 工具
- **多代理模式**：支持多代理协作模式
- **记忆与会话管理**：提供记忆机制和会话管理
- **模型可移植性**：支持任意模型和任意云平台
- **流式输出**：支持流式响应
- **安全防护**：内置 guardrails 安全机制
- **可观测性与评估**：支持 tracing 追踪和 evals 评估

**技术亮点**:
- 采用单体仓库（monorepo）架构，包含 Python/TypeScript 双语言 SDK、Harness、CLI 工具及文档站点
- 提供 `create_harness()`（Python）和 `createHarness()`（TypeScript）一键组装完整代理
- 无需托管控制平面，直接在用户进程内运行，适合替代手写代理循环
- 提供 `strands` CLI 工具，支持在终端中快速原型开发和对话
- 支持 Python（PyPI: strands-agents）和 TypeScript（npm: @strands-agents/sdk）双生态

---
## 10. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 49,949
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: 由港大数据智能实验室（HKUDS）推出的开源项目，旨在通过自动生成 CLI 工具，让所有软件都能被 AI Agent 原生调用。

**核心功能**:
- **一键生成 CLI**：为任意软件快速构建 agent-ready 的命令行接口，兼容 Pi、OpenClaw、Cursor、Claude Code 等主流 AI Agent 平台
- **CLI-Hub 社区中心**：通过 `pip install cli-anything-hub` 安装，再用 `cli-hub install <name>` 浏览、安装和管理社区贡献的 CLI 工具
- **实时预览与轨迹循环**：AI Agent 借助生成的 CLI 及预览、实时预览、轨迹循环机制，产出真实成果（如 CAD 建模、3D 场景、图表、游戏玩法、字幕等）
- **社区共建机制**：支持贡献者提交新 CLI 工具（PR 合并后即时更新至 Hub），也可提交软件/服务的 wishlist 请求

**技术亮点**:
- 基于 Python（≥3.10）开发，使用 Click（≥8.0）构建命令行界面
- 输出同时支持 JSON 与人类可读格式，便于 Agent 解析和人工调试
- 测试驱动开发：2,461 项测试全部通过，覆盖单元测试与端到端测试
- 已提供 18 个应用演示，配套 arXiv 技术报告（arXiv:2606.03854）
- 采用 Apache 2.0 开源协议

---
