---
tags:
  - github-trending
  - daily
date: 2026-11-17
created: 2026-11-17T01:55:43.059Z
---

# 2026-11-17 GitHub Trending Top 10

## 1. [ag-ui-protocol/ag-ui](https://github.com/ag-ui-protocol/ag-ui)
- **语言**: TypeScript
- **Stars**: 19,064
- **简介**: AG-UI: the Agent-User Interaction Protocol. Bring Agents into Frontend Applications.

### AI 总结
**简介**: AG-UI 是一个开放、轻量、基于事件的协议，用于标准化 AI Agent 与前端应用之间的连接方式。

**核心功能**:
- 用统一的双向事件流替代各框架的自定义接线，Agent 发出类型化事件，任意客户端均可渲染
- 支持流式输出、工具调用、共享状态更新、人工介入（Human-in-the-loop）、前端工具和子 Agent
- 同一个 Agent 可同时驱动 Web、移动端、终端或 Slack 等不同客户端
- 提供 CLI 脚手架（`create-ag-ui-app`），快速生成对接所选 Agent 框架的前端应用

**技术亮点**: 1.0 版本提供稳定冻结的规范（含 JSON Schema），TypeScript、Python、.NET SDK 均由规范生成，且与 0.x 双向向后兼容；与 MCP（工具）和 A2A（Agent）协同工作，兼容 LangChain、CrewAI、Mastra、Google ADK、Microsoft Agent Framework、Pydantic AI 等框架。

---
## 2. [backnotprop/plannotator](https://github.com/backnotprop/plannotator)
- **语言**: TypeScript
- **Stars**: 12,601
- **简介**: The workspace to stay in the loop and on top of agents - shape, decide, plan, annotate, review code, share with team, and send all feedback to agents with one click.

### AI 总结
**简介**: Plannotator 是一个面向 AI 编码代理的本地浏览器审阅工具，让开发者在代理提出计划、文档或代码变更时进行标注、评论，并一键将反馈回传给代理。

**核心功能**:
- **文档与计划标注**：对计划、规格说明、Markdown、HTML 及交互式产物进行批注，反馈直接发送给代理
- **代码审查**：支持审查本地变更或远程 PR，在 diff 上评论并建议代码，兼容 Git、GitButler、Jujutsu、Perforce、GitHub、GitLab；大型变更可启动"引导式审查"，由代理将 diff 按重要性分章节
- **Plannotator Inbox**：统一的本地窗口，代理在后台工作时留下消息、问题、文件和审查请求，用户可随时点击回答或标注，回复自动返回对应会话，不会阻塞代理会话
- **多代理集成**：通过插件、钩子和命令接入 Claude Code、Codex、Copilot CLI、Gemini CLI、OpenCode、Kiro、Droid、Amp、Pi 等编码代理，Inbox 还支持个人助理类工具

**技术亮点**: 基于 TypeScript 开发，采用本地浏览器界面作为审阅层；通过插件/钩子机制与各类代理深度集成，实现反馈的自动化回传；支持多种版本控制系统与代码托管平台的审查工作流。

---
## 3. [dream-num/univer](https://github.com/dream-num/univer)
- **语言**: TypeScript
- **Stars**: 27,826
- **简介**: Build your own AI office with Univer Office SDK. Bring editing, calculation, collaboration, and file processing into your product for people and AI agents. Built on an extensible open-source core.

### AI 总结
**简介**: Univer 是一个基于 TypeScript 的开源 Office SDK，帮助开发者在自己的产品或 AI Agent 中集成表格、文档编辑、计算、协作与文件处理能力，打造属于自己的 AI 办公应用。

**核心功能**:
- 开箱即用的开源表格（Sheets）与文档（Docs）编辑器
- 可接入自有应用或 AI Agent 的编辑与文件处理能力
- 支持协作编辑与计算能力
- 通过 Facade API 与事件机制连接应用和智能体
- 提供可扩展的核心架构，支持自定义功能边界与跨功能编辑的撤销/重做

**技术亮点**: 使用 TypeScript 开发；采用可扩展的开源核心架构，功能模块边界清晰；通过 Facade API 和事件系统实现应用与 Agent 的集成；同时提供开源与商业扩展的生态体系。

---
## 4. [tradermonty/claude-trading-skills](https://github.com/tradermonty/claude-trading-skills)
- **语言**: Python
- **Stars**: 6,345
- **简介**: Claude Code skills for equity investors and traders — market analysis, technical charting, economic calendars, screeners, and trading strategy development.

### AI 总结
**简介**: Claude Trading Skills 是一套基于 Claude Skills 的交易工作流工具包，面向时间有限的个人投资者，帮助结构化市场复盘、风险管理、交易计划与日志改进，而非代替用户做买卖决策。

**核心功能**:
- **每日市场研判**：15 分钟市场环境检查（市场广度分析、趋势分析、仓位暴露指导）
- **投资组合复盘**：每周长期组合审查（组合管理、股息审查监控、交易记忆）
- **波段机会筛选**：仅在风险允许时筛选波段候选（VCP 筛选、回撤熔断、技术分析、仓位计算、盘前纪律闸门）
- **交易记忆闭环**：记录每笔已平仓交易并进行信号复盘
- **月度绩效审查**：回顾月度表现并调整交易规则
- **工作流清单**：以机器可读的 YAML manifest 定义技能、决策闸门与产物的执行顺序

**技术亮点**: 基于 Python 开发，采用 Claude Skills 工作流架构；通过 `workflows/` 下的 YAML manifest 编排技能与决策闸门；支持 FMP、Alpaca 等数据 API，同时提供无需付费 API 的手动 CSV 降级路径；遵循 MIT 协议开源，附完整文档站与示例输出。

---
## 5. [getarcaneapp/arcane](https://github.com/getarcaneapp/arcane)
- **语言**: Go
- **Stars**: 8,773
- **简介**: Modern Docker Management, Designed for Everyone

### AI 总结
**简介**: Arcane 是一款面向所有人的现代化 Docker 管理工具，当前 `main` 分支为 v3 版本。

**核心功能**:
- 提供现代化的 Docker 管理界面（Dashboard）
- 支持多语言本地化（通过 Crowdin 协作翻译）
- 提供软件物料清单（SBOM）以增强安全与透明度

**技术亮点**: 使用 Go 语言开发（包路径 `getarcane.dev/arcane/v3`），采用 BSD-3-Clause 开源协议，并通过 Snyk 进行漏洞检测；功能请求已迁移至 GitHub Discussions，Issues 仅用于 Bug 报告以聚焦优先级。

---
## 6. [DeanChensj/jiangshan-map](https://github.com/DeanChensj/jiangshan-map)
- **语言**: JavaScript
- **Stars**: 6,834
- **简介**: 江山时序 · 中国历史交互地图时间轴 (403 BCE – Present) | Interactive Historical Atlas of China across 18 dynasties, 198 territory snapshots, ancient-to-modern place genealogy & classical poetry routes

### AI 总结
**简介**: 江山时序（jiangshan-map）是一个覆盖公元前403年战国时期至今、跨越18个历史时期与198个疆域快照的中国历史交互式地图时间轴。

**核心功能**:
- **时间轴疆域演化**：拖动时间轴即可回看各时期政权版图，支持多政权同屏对照（战国七雄、三国、南北朝、五代十国、宋辽西夏大理金等），并可用虚线“幽灵边界”对比相邻阶段疆域的得失变化。
- **古地名与历史地标追踪**：点击城市可查看其古今地名沿革（如长安两千年间的多个名称）、重要历史事件、战略关隘、诗词与战场地标。
- **帝王与纪年信息**：时间轴上方气泡显示当前年份在位君主，中文界面同时展示年号纪年（如“唐太宗·贞观四年”）。
- **政权档案与快速定位**：悬停图例高亮政权疆域，点击可查看该政权的存续时间、都城与简史，并缩放至其版图。

**技术亮点**: 基于 JavaScript 构建，提供多语言界面（英、简中、繁中、日），以交互式羊皮纸地图风格呈现，无需纸质地图集即可完成时空漫游。

---
## 7. [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills)
- **语言**: TypeScript
- **Stars**: 9,753
- **简介**: A library of Agent Skills designed to work with the Stitch MCP server. Each skill follows the Agent Skills open standard, for compatibility with coding agents such as Antigravity, Gemini CLI, Claude Code, Cursor.

### AI 总结
**简介**: 这是 Google Stitch 的 Agent Skills 与插件集合，遵循 Agent Skills 开放标准，可让各类编码 Agent 在 Stitch 平台上完成设计与构建任务。

**核心功能**:
- 提供三大插件套件：`stitch-design`（设计工作流）、`stitch-build`（构建与组件）、`stitch-utilities`（工具与辅助）
- 支持设计相关技能，例如将前端代码（React、Vue 等）转换为 Stitch 设计（code-to-design）、生成设计（generate-design）等
- 支持插件整体安装与按需选择技能安装两种方式，并可通过 `npx plugins` / `npx skills` 命令管理

**技术亮点**:
- 基于 TypeScript 实现，遵循 Agent Skills 开放标准
- 兼容多种编码 Agent：Codex、Antigravity、Gemini CLI、Claude Code、Cursor、OpenCode
- 依赖 Stitch MCP Server 运行，支持 Codex 插件市场、Claude Code/Cursor 的 npx 安装，以及 OpenCode 手动安装与 MCP 远程配置
- 支持稀疏检出（sparse checkout）以加快克隆速度，并允许按需组合安装插件

---
## 8. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 68,163
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个 AI 代理技能，可并行搜索 Reddit、X、YouTube、HN、Polymarket 等平台，按真实用户互动数据评分并合成有据可依的摘要。

**核心功能**:
- 跨平台并行检索：覆盖 Reddit、X/Twitter、YouTube、TikTok、HN、Polymarket、GitHub、arXiv、Techmeme 等十余个来源
- 按真实互动评分：以 Reddit 点赞、X 喜欢、YouTube 转录、TikTok 互动、Polymarket 真金白银赔率等作为排序依据，而非编辑推荐
- AI 代理裁判合成：将多平台分散信息整合为一份简明简报
- 零配置开箱即用：Reddit、HN、Polymarket、GitHub 无需配置即可使用，设置向导可在 30 秒内解锁其余平台
- 多宿主安装：支持 Claude Code（插件市场自动更新）以及 Codex、Cursor、Copilot、Gemini CLI 等 50+ Agent Skills 宿主

**技术亮点**: 基于 Python 实现；采用 v4 流水线架构，运行时技能规范以 `skills/last30days/SKILL.md` 为唯一事实来源；通过自带 API 密钥与浏览器会话桥接各平台封闭生态，实现单代理跨平台统一检索与交叉评分。

---
## 9. [NVIDIA/SkillEvaluator](https://github.com/NVIDIA/SkillEvaluator)
- **语言**: Python
- **Stars**: 2,749
- **简介**: Multi-tier framework for evaluating AI agent skills and plugins with quality gates, semantic overlap detection, synthetic evaluation dataset generation, and live agent evaluation that measures how skills affect agent behavior.

### AI 总结
**简介**: NVIDIA SkillEvaluator 是一个用于评估和改进 AI Agent 技能与插件的多层级框架，可衡量技能对任务结果和 Agent 行为的实际影响。

**核心功能**:
- **分层评估（Tiers）**：从无需 LLM 的确定性质量检查（Tier 1）到基于模型评分的评估，再到实时 Agent 评估（Tier 3），逐层深入。
- **质量门禁与安全检查**：对技能的描述、结构、安全性等做静态校验，并检测技能之间的语义重叠。
- **Harness 兼容性检查**：几秒内判断技能能否被 Claude Code、Codex、Copilot CLI 等不同 Agent 加载，并给出具体原因（如描述超长、目录未被扫描）。
- **合成评估数据集生成**：自动生成评测数据集，支撑模型化评分与反馈。
- **实时 Agent 评估**：对比"有技能"与"无技能"的运行结果，量化技能对 Agent 行为的真实影响。
- **CI 集成**：通过 `skillevaluator ci init` 一键生成 GitHub 配置，自动检查每次技能变更。

**技术亮点**: 基于 Python 3.12–3.14 开发，提供统一 CLI（`validate`、`quality-check`、`harness-check` 等命令）；采用无 LLM 推理的确定性检查降低使用门槛，同时支持 NVIDIA Build API 进行模型化评分；兼容 Agent Skills 规范，是 NVIDIA Verified Skills 流水线的一部分，采用 Apache 2.0 开源许可。

---
## 10. [alibaba/open-code-review](https://github.com/alibaba/open-code-review)
- **语言**: Go
- **Stars**: 52,978
- **简介**: Secure, fast, efficient, battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level comments, built-in multi-language ruleset (NPE, thread-safety, XSS, SQL injection), OpenAI & Anthropic compatible.

### AI 总结
**简介**: 阿里巴巴开源的一款 AI 代码审查 CLI 工具，基于确定性流水线 + LLM Agent 的混合架构，经过阿里内部大规模实战验证。

**核心功能**:
- 读取 Git diff，将变更文件发送给可配置的 LLM Agent，生成精确到行级别的结构化审查评论
- Agent 具备工具调用能力，可读取完整文件内容、搜索代码库、查看其他变更文件以获取上下文，实现深度审查而非表面 diff 反馈
- `ocr scan` 命令支持对整文件进行审查，适用于审计陌生代码库或无有效 diff 的目录
- 内置多语言规则集，覆盖 NPE、线程安全、XSS、SQL 注入等常见缺陷模式

**技术亮点**:
- 混合架构：确定性流水线 + LLM Agent 相结合
- 兼容 OpenAI 与 Anthropic 模型接口，配置模型端点即可使用
- 基准测试（AACR-Bench，50 个开源仓库、200 个真实 PR、10 种编程语言）显示：相比通用 Agent（如 Claude Code），在相同底层模型下 Precision 与 F1 显著更高，Token 消耗仅约 1/9，审查速度更快（以牺牲部分 Recall 换取低噪声）
- 使用 Go 语言开发，支持 Windows / macOS / Linux，可与 Claude Code、Codex、Cursor、Kimi Code 等 Agent 配合使用
- 已获 OpenSSF Best Practices 金牌认证

---
