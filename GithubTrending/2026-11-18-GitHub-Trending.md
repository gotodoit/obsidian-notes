---
tags:
  - github-trending
  - daily
date: 2026-11-18
created: 2026-11-18T01:55:43.231Z
---

# 2026-11-18 GitHub Trending Top 10

## 1. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- **语言**: Python
- **Stars**: 9,400
- **简介**: A Claude Code skill bundle for bug hunting and external red-team work - 82 skills, 15 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.

### AI 总结
**简介**: Claude-BugHunter 是一个面向漏洞挖掘与外部红队工作的 Claude Code 技能包，安装后可将 Claude Code 转变为资深漏洞挖掘研究员或红队操作员。

**核心功能**:
- **思维框架**：`bb-methodology` + `redteam-mindset` 提供五阶段非线性工作流、批判性思维框架与红队操作纪律
- **Web 应用漏洞挖掘**：58 个 `hunt-*` 技能，基于 681 份公开 HackerOne 报告整理，包含各漏洞类别的检测模式、Payload、绕过表和攻击链模板
- **企业边界攻击**：覆盖 M365/Entra、Okta、vCenter、SSL-VPN 设备、SharePoint、云 IAM 等平台的 2024–2026 CVE 攻击链及凭据后提权
- **交付与收尾**：`triage-validation` + 报告 + `evidence-hygiene`，包含 7 问题门禁、VRT 感知的严重性评级、OOS 反驳、PII 脱敏和红队交付物
- **自动触发**：用自然语言描述测试目标，相关技能自动加载，无需按名称调用

**技术亮点**:
- 共 83 个技能、15 个斜杠命令，覆盖 24 个核心漏洞类别，681 份披露报告模式（其中 433 份可单独引用与审计）
- 支持两种安装方式：Claude Code 插件市场安装（推荐，带命名空间、版本更新）或脚本复制安装到 `~/.claude/`
- 提供 `cbh` 命令行运行器（支持 `pipx` 独立安装）与 `hunt` 项目文件夹脚手架
- 集成 Burp MCP，支持多智能体运行环境，已在授权红队、漏洞挖掘及 DVWA、OWASP Juice Shop、Hacker101 等公开训练平台验证
- 主要语言为 Python

---
## 2. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 69,112
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个由 AI Agent 驱动的多平台搜索技能，聚合 Reddit、X、YouTube、HN、Polymarket、GitHub 等来源，按真实用户互动数据打分并生成有依据的摘要。

**核心功能**:
- 并行搜索 Reddit、X/Twitter、YouTube、TikTok、Hacker News、Polymarket、arXiv、Techmeme、GitHub 等多个平台，按 upvote、点赞、真实资金赔率等信号排序
- 零配置即可使用 Reddit、HN、Polymarket、GitHub（以及公司相关的专利和招聘页面），通过向导快速接入 X、YouTube、TikTok 等需密钥的平台
- 由 AI Agent 裁判将多源结果综合成一份简明摘要，适用于会前调研、人物背景调查、行业趋势追踪等场景
- 支持 Claude Code 插件市场安装，也可通过 `npx skills add` 接入 Codex、Cursor、Copilot、Gemini CLI 等 50+ Agent Skills 宿主

**技术亮点**: 采用"自带密钥/浏览器会话"方式突破各平台 API 壁垒，让单个 Agent 同时检索多个封闭花园；Python 实现，运行时规范以 `skills/last30days/SKILL.md` 为准，具备 GitHub Actions 校验流程。

---
## 3. [alibaba/open-code-review](https://github.com/alibaba/open-code-review)
- **语言**: Go
- **Stars**: 53,768
- **简介**: Secure, fast, efficient, battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level comments, built-in multi-language ruleset (NPE, thread-safety, XSS, SQL injection), OpenAI & Anthropic compatible.

### AI 总结
**简介**: 阿里巴巴开源的一款 AI 驱动的代码审查 CLI 工具，基于“确定性流水线 + LLM Agent”混合架构，经阿里内部大规模验证后开源。

**核心功能**:
- 读取 Git diff，将变更文件交由具备工具调用能力的 LLM Agent 审查，生成精确到行级的结构化评论
- Agent 可读取完整文件内容、检索代码库、查看其他变更文件以获取上下文，实现深度审查而非表层反馈
- `ocr scan` 支持对无有效 diff 的整个文件/目录进行审查，适用于陌生代码库审计
- 内置多语言规则集，覆盖 NPE、线程安全、XSS、SQL 注入等常见缺陷

**技术亮点**:
- 混合架构：确定性流水线 + LLM Agent 协同工作
- 采用 Go 语言开发，兼容 OpenAI 与 Anthropic 模型接口
- 在真实基准测试中，相比通用 Agent（如 Claude Code）精度与 F1 显著更高，Token 消耗仅约 1/9，但召回率更低（有意以精度优先、减少噪音）
- 支持 Windows/macOS/Linux，可对接 Claude Code、Codex、Cursor、Kimi Code 等 Agent
- 通过 OpenSSF Best Practices 金牌认证

---
## 4. [Tencent/LoopForge](https://github.com/Tencent/LoopForge)
- **语言**: Go
- **Stars**: 3,218
- **简介**: Self-hosted workflows for coding-agent delivery. Orchestrate CodeBuddy, Codex and Claude Code with scripts and human approval gates. Includes Local workflows for coding assistants.

### AI 总结
**简介**: LoopForge 是腾讯开源的自托管工作流平台，让团队通过编码智能体（Coding Agent）以可重复、可审批的方式交付软件。

**核心功能**:
- **对话式工作台（Main Bot）**：在聊天中描述需求，Main Bot 自动创建 Docker 沙箱、拉取仓库、调度项目角色并提交 PR/MR。
- **SOP 标准化工作流**：将验证过的工作方式固化为 SOP（智能体 + 脚本 + 人工审批节点的标准流程），按固定阶段重复交付，支持任一步骤回退、重试或重跑。
- **角色分离**：规划、实现、审查、测试各自拥有独立的提示词、执行器、模型、规则、Skills 与 MCP 工具，可作为 SOP 节点或聊天中的子智能体运行。
- **人工审批关卡**：在关键节点内置人工审核与批准机制，确保交付质量可控。
- **多智能体 CLI 支持**：集成 CodeBuddy、Codex、Claude Code、OpenCode、Cursor CLI、Kimi Code 等多种编码智能体命令行工具。
- **需求追踪**：聊天与 SOP 两条路径共享同一需求记录，所有变更可追溯并计入交付与成本报告。

**技术亮点**:
- 使用 Go 语言开发，采用 MIT 许可证。
- 基于 Docker 的自托管沙箱隔离架构，所有数据运行在自有基础设施上。
- 提供 npm 包 `loopforge-cli`，支持本地编码助手工作流。

---
## 5. [dream-num/univer](https://github.com/dream-num/univer)
- **语言**: TypeScript
- **Stars**: 28,926
- **简介**: Build your own AI office with Univer Office SDK. Bring editing, calculation, collaboration, and file processing into your product for people and AI agents. Built on an extensible open-source core.

### AI 总结
**简介**: Univer 是一个基于 TypeScript 的开源 Office SDK，帮助开发者在自有产品或 AI Agent 中集成电子表格、文档编辑、计算、协作与文件处理能力，构建自己的 AI 办公应用。

**核心功能**:
- 开箱即用的开源电子表格（Sheets）与文档（Docs）编辑器
- 支持将可编辑内容接入自有应用或 AI Agent（通过 Facade API 与事件机制）
- 支持跨功能的编辑组合与撤销/重做
- 可扩展的插件式架构，便于自定义功能并明确功能边界
- 提供 CLI、Agent 集成与开发者技能等生态工具

**技术亮点**: 采用 TypeScript 编写，基于可扩展的开源内核与模块化架构设计；提供 Facade API 与事件机制连接应用和 Agent；包含 Univer Workspace 作为 Office SDK 参考应用，并具备完善的 API 文档与多语言 README 支持。

---
## 6. [getarcaneapp/arcane](https://github.com/getarcaneapp/arcane)
- **语言**: Go
- **Stars**: 9,353
- **简介**: Modern Docker Management, Designed for Everyone

### AI 总结
**简介**: Arcane 是一款面向所有人设计的现代化 Docker 管理工具，使用 Go 语言开发。

**核心功能**:
- 提供现代化的 Docker 管理界面与仪表盘
- 支持多语言本地化（通过 Crowdin 平台协作翻译）
- 提供官方文档站，涵盖安装配置与开发指南

**技术亮点**:
- 基于 Go 语言开发（模块路径 `getarcane.dev/arcane/v3`）
- 采用 BSD-3-Clause 开源许可证
- 提供 SBOM（软件物料清单）以增强安全性与透明度
- 当前 `main` 分支为 v3 版本，2.x 版本维护于 `release/2.x.x` 分支
- 功能请求统一迁移至 GitHub Discussions，Issues 仅用于 Bug 报告以聚焦优先级

---
## 7. [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills)
- **语言**: TypeScript
- **Stars**: 10,122
- **简介**: A library of Agent Skills designed to work with the Stitch MCP server. Each skill follows the Agent Skills open standard, for compatibility with coding agents such as Antigravity, Gemini CLI, Claude Code, Cursor.

### AI 总结
**简介**: 这是 Google Stitch 的 Agent Skills 与插件集合，遵循 Agent Skills 开放标准，可配合 Stitch MCP 服务器在多种编码智能体中使用。

**核心功能**:
- 提供 `stitch-design`（设计工作流，如代码转设计、生成设计）、`stitch-build`（构建与组件）、`stitch-utilities`（工具辅助）三类插件
- 支持按插件市场或选择性方式安装技能，适配 Codex、Claude Code、Cursor 等智能体，OpenCode 需手动安装
- 技能依赖 Stitch MCP 服务器，需先完成 MCP 配置与凭证设置

**技术亮点**: 基于 TypeScript 实现；采用 Agent Skills 开放标准与插件市场（marketplace）+ 稀疏检出（sparse checkout）机制；通过 `npx plugins` / `npx skills` 统一分发，兼容多智能体生态。

---
## 8. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 16,917
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，提供面向主流开发工具、框架和 SaaS 产品的插件规范与官方插件集合，每个插件为独立目录并自带 `plugin.json` 清单。

**核心功能**:
- **开发工具类插件**：涵盖代码评审（Thermos、PR Review Canvas）、任务并行编排（Orchestrate）、CLI 设计规范（CLI for Agents）、插件脚手架（Create Plugin）、迭代式 AI 循环（Ralph Loop）等
- **生产力与集成类插件**：提供 Gmail、Google Drive/Calendar/Docs/Sheets/Slides 等办公工具，以及 Google Ads、Analytics、Search Console、Gong、Salesforce 等 SaaS 集成
- **开发辅助能力**：包括 Cursor SDK（TypeScript 构建应用）、文档画布渲染（Docs Canvas）、语音交互（Grok Voice）、模型咨询（Advisor）等

**技术亮点**: 采用 TypeScript 开发；插件以根目录独立子目录形式组织，通过统一的 `.cursor-plugin/plugin.json` 清单进行标准化管理，便于扩展与分发。

---
## 9. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 319,370
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，通过可组合的技能和初始指令，让智能体自动遵循规范化的开发流程。

**核心功能**:
- 启动即介入需求澄清：智能体不会直接写代码，而是先退一步询问用户真正想达成的目标
- 规格分块呈现：将提炼出的需求规格拆成易于阅读消化的短片段供用户确认
- 生成可执行的实施计划：计划详细到"没有项目背景、不爱测试的初级工程师"也能照做，强调红/绿 TDD、YAGNI 和 DRY
- 子智能体驱动开发：用户确认后，由多个子智能体逐项完成工程任务，并自动检查、评审工作成果，可连续自主工作数小时而不偏离计划
- 技能自动触发：无需额外操作，编码智能体启动后即自动获得 Superpowers 能力
- 多平台安装支持：覆盖 Claude Code、Antigravity、Codex、Cursor、Devin CLI、Factory Droid、Gemini CLI、GitHub Copilot CLI、OpenCode、Qwen Code 等十余种智能体工具

**技术亮点**: 以 Shell 为主要语言实现；采用"可组合技能 + 初始指令"的架构，通过自动触发的技能机制将方法论注入各类编码智能体；支持插件市场、扩展、CLI 命令等多种安装方式，并为企业用户提供商业支持渠道。

---
## 10. [ag-ui-protocol/ag-ui](https://github.com/ag-ui-protocol/ag-ui)
- **语言**: TypeScript
- **Stars**: 20,032
- **简介**: AG-UI: the Agent-User Interaction Protocol. Bring Agents into Frontend Applications.

### AI 总结
**简介**: AG-UI 是一个开放、轻量、基于事件的协议，用于标准化 AI Agent 与前端应用之间的双向连接。

**核心功能**:
- 通过统一的双向事件流替代各框架的自定义接线，Agent 发出类型化事件，任意客户端均可渲染
- 支持流式输出、生成式 UI、共享状态、人工介入（Human-in-the-loop）、前端工具调用与子 Agent
- 同一 Agent 可同时驱动 Web、移动端、终端及 Slack/Teams 等客户端
- 提供 CLI 脚手架（`create-ag-ui-app`），快速生成对接指定 Agent 框架的前端应用

**技术亮点**: 1.0 版本拥有稳定冻结的规范（基于 JSON Schema），TypeScript、Python、.NET SDK 均由规范生成且双向向后兼容；可与 MCP（工具）和 A2A（Agent 间协作）协同工作，兼容 LangChain、CrewAI、Mastra、Google ADK、Microsoft Agent Framework、Pydantic AI 等多种框架，采用 MIT 许可证。

---
