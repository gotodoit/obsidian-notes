---
tags:
  - github-trending
  - daily
date: 2026-09-23
created: 2026-09-23T01:55:42.413Z
---

# 2026-09-23 GitHub Trending Top 8

## 1. [anthropics/financial-services](https://github.com/anthropics/financial-services)
- **语言**: Python
- **Stars**: 36,367
- **简介**: 

### AI 总结
**简介**: Anthropic 推出的金融服务行业 AI 代理工具集，为投资银行、股票研究、私募股权和财富管理等场景提供参考代理、技能和数据连接器，支持 Claude Cowork 插件和 Claude Managed Agents API 两种部署方式。

**核心功能**:
- **覆盖与咨询**: Pitch Agent（一键生成可比公司分析、先例交易、LBO 及品牌化推介材料）、Meeting Prep Agent（客户会议前简报包）
- **研究与建模**: Market Researcher（行业概览、竞争格局、同行对比）、Earnings Reviewer（财报电话会+文件→模型更新→笔记草稿）、Model Builder（Excel 中实时构建 DCF、LBO、三表模型、可比公司分析）
- **基金管理与财务运营**: Valuation Reviewer（GP 包估值、LP 报告）、GL Reconciler（总账对账、根因追溯、签批路由）、Month-End Closer（应计、结转、差异分析）、Statement Auditor（LP 报表分发前审计）
- **运营与准入**: KYC Screener（解析准入文件、运行规则引擎、标记缺口）
- **垂直插件**: 按 FSI 垂直领域打包的技能、斜杠命令和数据连接器（如 `/comps`、`/dcf`、`/earnings`），可独立安装

**技术亮点**:
- 单一来源双模式部署：同一系统提示和技能既可作 Cowork 插件安装，也可通过 Managed Agents API（`/v1/agents`）部署在自有工作流引擎后
- 每个代理插件自包含，捆绑所需技能，安装即用
- 所有输出均需人工审核签批，不构成投资建议、不执行交易、不绑定风险、不记账、不批准准入
- 仓库包含 `managed-agent-cookbooks/`（含 `agent.yaml`、子代理、安全说明）、`claude-for-msft-365-install/`（Microsoft 365 加载项管理工具）及部署/校验脚本
- 支持合作伙伴插件（LSEG、S&P Global）

---
## 2. [agent-substrate/substrate](https://github.com/agent-substrate/substrate)
- **语言**: Go
- **Stars**: 2,994
- **简介**: Agent Substrate: the core system

### AI 总结
**简介**: Agent Substrate 是一个面向自主智能体时代的安全优先执行运行时，通过高密度多路复用技术，在少量物理节点上运行海量有状态 Actor。

**核心功能**:
- **Actor 生命周期管理**：支持创建/销毁、挂起/恢复 Actor，并实时将其分配到 Worker 上
- **高密度多路复用**：利用智能体应用大部分时间处于空闲的特性，实现 30 倍以上的超配（如 250 个 Actor 运行在 8 个 Pod 上）
- **亚秒级恢复**：支持每秒 500+ 次挂起/恢复操作，恢复延迟低于 500ms
- **状态持久化**：通过全状态快照，在休眠周期中完整保留内存和文件系统状态
- **流量路由**：将传入请求路由到对应的 Actor

**技术亮点**:
- 基于 **Go** 语言开发，底层依托 **Kubernetes** 进行基础设施供给和 Worker 生命周期管理
- 支持多种沙箱技术（**microVM**、**gVisor**），提供内核级和网络级零信任隔离
- 框架无关，兼容 ADK、LangChain、Claude Code、MCP 等多种智能体技术栈
- 与 Agent Executor、kagent 等生态项目集成，支持端到端智能体部署及 RL 场景优化
- 当前处于早期开发阶段，API 尚不稳定，暂不适合生产环境使用

---
## 3. [dream-num/univer](https://github.com/dream-num/univer)
- **语言**: TypeScript
- **Stars**: 15,478
- **简介**: The Office Harness for AI Agents — Spreadsheets, Docs, Slides, Canvas, Relational Tables, and PDF in one runtime.

### AI 总结
**简介**: Univer 是一个全栈、同构的办公 SDK，用于在自有产品中构建电子表格、文档和演示等生产力体验。

**核心功能**:
- 支持电子表格、文档、演示、画布、关系表和 PDF 等多种办公场景
- 基于插件架构，可按需组合、替换、懒加载或扩展功能
- 提供统一的 Facade API，覆盖工作簿、区域、公式和文档操作
- 支持浏览器和 Node.js 同构运行，可在服务端进行无头处理
- 内置公式引擎和 Canvas 渲染，适配大规模数据场景
- 支持深色模式，UI 组件与渲染引擎均可自适应主题

**技术亮点**: 采用 TypeScript 开发，基于 Canvas 渲染和插件化架构，具备同构设计（浏览器 + Node.js）、专用公式引擎、框架适配器及预设配置，适合嵌入 SaaS、内部工具、BI 流程和 AI 应用中。

---
## 4. [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates)
- **语言**: Python
- **Stars**: 31,144
- **简介**: CLI tool for configuring and monitoring Claude Code

### AI 总结
**简介**: 一个用于配置和监控 Anthropic Claude Code 的 CLI 工具，提供开箱即用的 AI 智能体、自定义命令、设置、钩子、MCP 集成及项目模板。

**核心功能**:
- 提供 100+ 可即用的 AI agents、commands、settings、hooks 和 MCPs 组件
- 支持通过 `npx claude-code-templates@latest` 一键安装完整开发栈或交互式浏览安装
- 支持按需安装特定组件（如 `--agent`、`--command`、`--setting`、`--hook`、`--mcp`）
- 提供 aitmpl.com 网页界面用于浏览和安装模板
- 内置对第三方服务（如 Bright Data）的 Skills 和 MCP 集成支持

**技术亮点**: 基于 Python 开发，通过 npm 分发（`npx` 直接运行）；采用模块化组件架构，支持 agents/commands/settings/hooks/MCPs 多类型扩展；已获 Vercel OSS、Neon、Claude for Open Source 等开源项目支持。

---
## 5. [google/ax](https://github.com/google/ax)
- **语言**: Go
- **Stars**: 7,670
- **简介**: Google's open agentic orchestration runtime

### AI 总结
**简介**: AX 是 Google 开源的声明式智能体编排运行时，基于 Go 构建，运行在 Agent Substrate 之上，用于在集群中大规模调度隔离的自主智能体任务。

**核心功能**:
- **Task**：在具备 CPU/内存限制的隔离沙箱中运行不可信智能体代码
- **Workspace**：预配置 Git 仓库、MCP 服务器和技能包，让智能体启动即就绪
- **Gateway**：将出站流量限制在显式主机白名单内
- **Model**：配置平台使用的 LLM 及凭据（来自 Kubernetes Secret）
- 支持 `ax suspend` / `ax resume` 暂停与恢复任务，`ax ssh` 进入运行中的智能体排查

**技术亮点**:
- 声明式 YAML 清单（`ax.io/v1alpha1`），通过 `ax apply` 一键下发，CLI 设计对标 `kubectl`
- 基于 Agent Substrate 实现沙箱化执行，面向单集群数十亿任务的吞吐量设计
- 控制平面通过 gRPC 通信，使用 `ko` 构建部署，落地于 Kubernetes 的 `ax-system` 命名空间
- 项目仍处于早期阶段，核心概念与协议可能发生重大破坏性变更

---
## 6. [mvt-project/mvt](https://github.com/mvt-project/mvt)
- **语言**: Python
- **Stars**: 14,130
- **简介**: MVT (Mobile Verification Toolkit) helps with conducting forensics of mobile devices in order to find signs of a potential compromise.

### AI 总结
**简介**: MVT 是由 Amnesty International 安全实验室开发的移动设备取证工具包，用于检测 Android 和 iOS 设备是否被间谍软件入侵。

**核心功能**:
- 支持对 Android 和 iOS 设备进行取证分析，识别潜在的入侵痕迹
- 支持导入公开的入侵指标（IOCs），扫描设备中已知间谍软件活动的痕迹
- 提供 `mvt-ios`、`mvt-android` 和 `mvt` 三个命令，分别处理对应平台的取证任务及通用操作
- 支持通过插件包扩展额外的取证模块和命令
- 提供 Shell 自动补全功能（支持 Bash、Zsh、Fish）

**技术亮点**:
- 基于 Python 开发，可通过 `pip3 install mvt` 或 `uv tool install mvt` 快速安装
- 源自 Pegasus Project，配套发布了技术取证方法论，由 Amnesty International 持续维护
- 注意：v3 分支引入了破坏性变更，可能影响依赖旧版输出的脚本；该工具面向取证研究人员和技术人员，非终端用户自评估工具

---
## 7. [superdesigndev/treg](https://github.com/superdesigndev/treg)
- **语言**: Python
- **Stars**: 2,245
- **简介**: OpenRouter for agent tools. Join community here: https://discord.gg/6mQYYfFMAn

### AI 总结
**简介**: Treg 是面向 AI Agent 工具的「OpenRouter」——用一个 base URL 和一个 token，即可调用 60+ 供应商的 3000+ 工具端点，按次计费、无需逐一注册供应商账号。

**核心功能**:
- **统一工具目录**：聚合 SEO/外链、社交趋势、人物与企业信息富化、广告、爬虫、图像与视频生成等 3000+ 端点，覆盖 60+ 供应商，按调用计费（低至 1 美分起），无需向供应商注册。
- **自带工具接入**：支持团队成员注册自有付费 API、OAuth 连接、厂商 CLI（如 `stripe`、`gh`、`vercel`）及 `SKILL.md` 技能包，自有密钥优先于 treg 密钥且不计费。
- **CLI 与 Agent 集成**：提供 `treg` 命令行（搜索、调用、查余额、健康检查），并可作为 Claude Code 插件或通过 `npx skills` 接入其他 Agent。
- **凭证托管**：由服务端注入鉴权，代理只做转发不修改上游，调用方无需持有密钥，兼容上游 API 变更。

**技术亮点**:
- 采用「代理中继而非建模」架构，服务端注入认证（支持多绑定，如 OAuth bearer + `developer-token` 头），使调用方永不接触密钥。
- 工具抽象为 endpoint（`base_url` + 凭证绑定）与 CLI（注入凭证运行厂商二进制）两类，skill/bundle 将配方、密钥与工具打包注册。
- 基于 Python 实现，提供托管版 treg.to 并支持自托管。

---
## 8. [browser-use/video-use](https://github.com/browser-use/video-use)
- **语言**: Python
- **Stars**: 25,869
- **简介**: Edit videos with coding agents

### AI 总结
**简介**: video-use 是一个 100% 开源的视频编辑工具，让 Claude Code 等编码智能体通过对话方式自动完成视频剪辑，输出 `final.mp4`。

**核心功能**:
- 自动去除口癖（如 umm、uh）和无效停顿，实现精准剪辑
- 自动调色（暖色电影感、中性锐利或自定义 ffmpeg 链）
- 每个剪切点添加 30ms 音频淡入淡出，消除爆音
- 按自定义风格烧录字幕（默认 2 词大写分块）
- 通过 HyperFrames、Remotion、Manim 或 PIL 并行生成动画叠加层
- 在渲染输出的每个剪切边界进行自评估，发现问题自动修复重渲染（最多 3 次）
- 通过 `project.md` 持久化会话记忆，支持跨会话续编

**技术亮点**:
- **"读"视频而非"看"视频**：LLM 不直接分析画面，而是通过两层结构理解视频——Layer 1 为 ElevenLabs Scribe 生成的词级时间戳转录（打包成约 12KB 的 `takes_packed.md`），Layer 2 为按需生成的 `timeline_view` 视觉合成图（胶片条+波形+词标签）。相比逐帧分析的 4500 万 token，此方案仅需 12KB 文本加少量 PNG。
- **流水线架构**：转录 → 打包 → LLM 推理 → 生成 EDL → 渲染 → 自评估，形成闭环。
- **技术栈**：Python、ffmpeg、ElevenLabs API、uv 包管理，支持 Claude Code、Codex 等多种智能体接入。

---
