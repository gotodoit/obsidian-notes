---
tags:
  - github-trending
  - daily
date: 2026-08-26
created: 2026-08-26T01:55:44.465Z
---

# 2026-08-26 GitHub Trending Top 10

## 1. [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2)
- **语言**: JavaScript
- **Stars**: 18,103
- **简介**: Prompt as Code | GPT-Image2 工业级提示词引擎与模板库，530+ 个案例逆向工程，20+ 套工业级模板，并提炼出Skills，持续更新中

### AI 总结
**简介**: awesome-gpt-image-2 是一个工业级 GPT-Image2 提示词引擎与模板库，将提示词视为代码，通过逆向工程 530+ 个案例并提炼出 20+ 套工业级模板，持续更新中。

**核心功能**:
- **530+ 逆向工程案例库**: 对 GPT-Image2 生成的案例进行系统逆向分析，提炼出可复用的提示词模式
- **20+ 工业级模板**: 覆盖多种风格与场景的标准化提示词模板，可直接应用于生产环境
- **可视化画廊网站**: 提供在线交互式画廊 (gpt-image2.canghe.ai)，支持大图预览、提示词一键复制、按风格/场景筛选、Google 登录后测试生成
- **多语言支持**: 提供英文、简体中文、日文三种语言的文档
- **社区生态**: 支持微信交流群与公众号（苍何），提供项目更新、新案例和实战教程

**技术亮点**: 项目采用 JavaScript 构建，将提示词工程抽象为"代码"范式，通过案例逆向工程提炼出系统化的模板体系；配套网站实现从浏览、筛选、复制到实际生成的完整产品闭环，并支持 GitHub 案例跳转溯源。

---
## 2. [anthropics/claude-plugins-community](https://github.com/anthropics/claude-plugins-community)
- **语言**: Python
- **Stars**: 1,783
- **简介**: Community plugin marketplace for Claude Cowork and Claude Code. Read-only mirror — submit plugins at clau.de/plugin-directory-submission.

### AI 总结
**简介**: 这是 Anthropic 官方维护的 Claude Cowork 和 Claude Code 社区插件市场仓库，提供经过安全审核的社区插件清单。
**核心功能**:
- 提供社区插件市场清单（`.claude-plugin/marketplace.json`），每日自动同步自 Anthropic 内部审核流程
- 支持 Claude Cowork 用户通过 claude.com/plugins 安装插件
- 支持 Claude Code 用户通过命令行添加市场并安装插件（`claude plugin marketplace add` + `claude plugin install`）
- 插件提交需通过官方渠道（clau.de/plugin-directory-submission），仓库不接受直接 PR
**技术亮点**:
- 只读镜像架构，所有变更由内部审核流水线驱动，确保安全性和一致性
- 每个插件均经过自动化安全扫描后才被批准分发
- 使用 Python 构建，与官方插件仓库（anthropics/claude-plugins-official）和知识工作插件仓库（anthropics/knowledge-work-plugins）形成生态互补

---
## 3. [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)
- **语言**: Python
- **Stars**: 35,346
- **简介**: The job search that runs on your machine. AI job application framework built on Claude Code: evaluate postings, tailor CVs, write cover letters, prep interviews. Fork it and own it.

### AI 总结
**简介**: 一个基于 Claude Code 的 AI 求职应用框架，在本地运行完整的求职流程——评估职位、定制简历、撰写求职信和准备面试，作者本人用它成功获得工作。

**核心功能**:
- `/setup`：填写个人资料，生成配置文件
- `/scrape`：搜索并抓取职位门户（支持丹麦市场 Jobindex、Jobnet 等，可替换为本地求职网站）
- `/apply <url>`：评估职位匹配度，给出评分与建议，定制生成 LaTeX 简历和求职信
- 内置"起草-评审"双智能体流水线，评审智能体对输出进行批判性改进
- 可选的薪酬基准测试和 ATS 可解析性检查（需 `pdftotext`）
- 面试准备辅助功能

**技术亮点**: 基于 Claude Code CLI 构建（兼容 Codex、Gemini CLI 等替代工具），Python 3.10+ 编写，使用 Bun 运行职位搜索 CLI 工具，简历用 `lualatex` 编译（含 fontawesome5 图标）、求职信用 `xelatex` 编译（依赖 fontspec），支持 TeX Live/MacTeX/TinyTeX/MiKTeX 等发行版，核心工作流语言和地区无关，可 fork 定制。

---
## 4. [apache/maka](https://github.com/apache/maka)
- **语言**: TypeScript
- **Stars**: 3,363
- **简介**: Apache Maka (Incubating) is a local-first AI agent workspace. Model messages, tool calls, tool results, permission decisions, and termination events are recorded as an append-only log.

### AI 总结
**简介**: Apache Maka (Incubating) 是一个本地优先的 AI Agent 工作空间，将模型消息、工具调用、权限决策等执行过程记录为可恢复的追加式日志，让 Agent 在用户自己的机器上完成真实工作。

**核心功能**:
- **本地优先架构**: 会话、设置和运行记录默认保存在本地，用户可自由选择云端 API、本地模型或兼容网关作为模型后端
- **完整执行记录**: 模型消息、工具调用、工具结果、终止事件均以追加式日志持久化，UI 和后续模型调用只是该记录的不同视图
- **上下文压缩不丢历史**: 可从下一轮提示中省略旧工具输出，但保留已保存的证据，兼顾上下文长度与历史完整性
- **统一运行时宿主**: 桌面端、终端 CLI 和 Eval 评估统一通过 Runtime Host 驱动 Agent，Eval 仅负责实验与评分
- **多交互界面**: 提供桌面应用（Electron + React，支持流式会话、工具时间线、分支、搜索）、TUI/CLI（`maka`、`maka run`）和可复现的 Eval 基准测试（`maka eval run`）
- **内置工具集**: 提供 `Read`、`Write`、`Edit`、`Bash`、`Glob`、`Grep` 等工具；Computer Use 和目录技能为可选功能，默认关闭
- **安全边界**: 超出沙箱的工具调用需审批授权，运行可中止，失败可分类

**技术亮点**: 基于 TypeScript 构建，采用追加式日志作为执行事实的单一数据源；支持多模型连接、流式输出、思考过程与用量统计；桌面端基于 Electron + React，支持 macOS Apple Silicon（早期公开版）和 Windows 预览版，Linux 即将支持；项目遵循 Apache 2.0 许可证，目前处于 Apache 孵化器阶段。

---
## 5. [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)
- **语言**: Python
- **Stars**: 100,292
- **简介**: TradingAgents: Multi-Agents LLM Financial Trading Framework

### AI 总结
**简介**: TradingAgents 是一个基于多智能体 LLM 的金融交易框架，模拟真实交易公司的协作流程，由多个专业 AI 代理共同评估市场并制定交易策略。

**核心功能**:
- **多智能体协作**: 部署基本面分析师、情绪专家、技术分析师、交易员和风险管理团队等专业 LLM 代理，通过动态讨论共同决策
- **多模型支持**: 兼容 GPT-5.x、Gemini 3.x、Claude 4.x、Grok 4.x、DeepSeek、Qwen、GLM 等主流 LLM 提供商
- **数据源集成**: 支持 FRED、Polymarket、Alpha Vantage 等市场数据源，以及加密货币情绪数据
- **回测与恢复**: 提供历史回测功能，支持 LangGraph checkpoint 断点续跑和持久化决策日志
- **多语言与跨平台**: 支持多语言界面、Docker 部署、Windows UTF-8 编码修复及代理配置

**技术亮点**: 基于 Python 实现，采用 LangGraph 图路由架构，提供结构化输出（如研究经理、交易员、投资组合经理），支持任意 OpenAI 兼容端点接入，具备 API 密钥自动检测、环境变量配置和 CI 质量门禁，并配套 arXiv 技术论文（2412.20138）。

---
## 6. [AgriciDaniel/claude-obsidian](https://github.com/AgriciDaniel/claude-obsidian)
- **语言**: Python
- **Stars**: 12,761
- **简介**: Self-organizing AI second brain for Obsidian + Claude Code. Drop any source and Claude reads, links, and files it into one connected knowledge graph of plain Markdown you own. AI note-taking, personal knowledge management (PKM), and an open-source Notion alternative. Based on Karpathy's LLM Wiki pattern.

### AI 总结
**简介**: claude-obsidian 是一个本地优先的 AI 第二大脑工具，让 Claude Code 将任意来源的资料自动转化为带引用的 Obsidian 知识库，构建可复用的个人知识图谱。

**核心功能**:
- **智能捕获与整理**: 通过可见的收件箱引入本地资料，在合成前保留不可变的内容寻址副本
- **证据溯源与核验**: 维护来源台账和声明台账，记录权威性、时效性、支持/矛盾关系、置信度和审查状态
- **知识连接与可视化**: 生成链接页面、索引、内容地图（Maps of Content）和 Obsidian Canvas 视图
- **复合知识循环**: 支持查询、研究、检索、代码检查（lint）和知识折叠，让每次使用都让知识库更有价值
- **并行安全机制**: 并行代理仅返回草稿，由单一编排器检查并应用可恢复的事务，避免知识库竞争冲突

**技术亮点**:
- 基于 Karpathy 的 LLM Wiki 模式构建
- 纯 Python 实现，输出为普通 Markdown/JSON 文件，用户完全拥有数据，无云端锁定
- 所有变更操作先预览 JSON 计划，经 SHA256 哈希审批后才执行，确保操作可审计、可恢复
- 兼容 Agent Skills 标准和 Claude Code 插件生态
- 可选工具自动检测，缺失适配器会明确降级而非模拟，能力边界诚实声明

---
## 7. [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch)
- **语言**: Python
- **Stars**: 49,030
- **简介**: Learn it. Build it. Ship it for others.

### AI 总结
**简介**: 一个从零开始系统学习 AI 工程的开源课程，包含 511 节课、20 个阶段，覆盖 Python/TypeScript/Rust/Julia，每节课都产出可复用的实际产物（提示词、技能、Agent、MCP 服务器），帮助学习者从理论到实战全面掌握 AI 工程。

**核心功能**:
- **结构化课程体系**: 511 节课分 20 个阶段，约 329 小时，从环境搭建、数学基础到 LLM 工程、Agent 工程和 MCP 协议，循序渐进
- **按目标快速选课**: 提供多种学习路径（如"我想构建 Agent"、"我想准备 Claude 认证"），无需从头扫描全部课程，可按需直达对应阶段
- **多语言支持**: 支持 12 种语言的翻译落地页，课程页面在 `translations` 分支提供机器翻译
- **双平台学习**: 同一课程代码可在 GitHub 和配套网站（aiengineeringfromscratch.com）上学习，并配有学习路径导航
- **认证备考**: 提供 Claude 认证的专项入门指南和认证学院资源

**技术亮点**: 覆盖 Python、TypeScript、Rust、Julia 多语言；每节课产出可复用产物（提示词、技能、Agent、MCP 服务器）；MIT 开源许可；配套网站提供数据统计（15 万+ 读者）；包含 Agent Memory 项目（持久化记忆，可与任意 Agent 或聊天助手配合使用）

---
## 8. [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman)
- **语言**: Rust
- **Stars**: 37,795
- **简介**: Your Personal AI super intelligence. A brain that builds a local-first memory of your life, a fantastic orchestrator of agent fleets and workflows, and a deep researcher.

### AI 总结
**简介**: OpenHuman 是一个开源的个人 AI 超级智能，以本地优先的方式构建你的生活记忆，并作为智能体舰队与工作流的卓越编排器及深度研究员。

**核心功能**:
- **持久记忆大脑**: 构建本地优先、持续累积的个人世界记忆
- **智能体编排器**: 在持久化图结构上运行多智能体舰队与复杂工作流
- **深度研究能力**: 在你完成操作前，自动扫描个人数据与网络信息
- **本地优先架构**: 数据与处理优先在本地完成，强调隐私与掌控

**技术亮点**:
- 使用 **Rust** 开发，注重性能与安全性
- 项目处于早期 Beta 阶段，但发布一周内连续九天登顶 GitHub 趋势榜
- 提供多平台安装方式（Homebrew、Debian/Ubuntu `.deb`、AUR 及安装脚本）
- 支持多语言文档（中、英、日、韩、德、乌尔都语）

---
## 9. [basecamp/omarchy](https://github.com/basecamp/omarchy)
- **语言**: Shell
- **Stars**: 31,319
- **简介**: Beautiful, Modern & Opinionated Linux

### AI 总结
**简介**: Omarchy 是由 DHH 打造的一款美观、现代且高度定制化的 Linux 发行版，强调开箱即用的体验与个人风格。  
**核心功能**:  
- 预配置的现代化桌面环境，注重视觉美观与交互流畅性  
- 高度“有主见”的默认设置，减少用户配置成本  
- 面向开发者的优化工作流，集成常用工具链  
**技术亮点**: 基于 Shell 脚本实现系统配置与自动化，遵循 MIT 开源协议，社区可自由修改与分发。

---
## 10. [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)
- **语言**: Python
- **Stars**: 134,250
- **简介**: 100+ AI Agents, Agent Skills and RAG Apps - Free and Open Source.

### AI 总结
**简介**: 一个包含 100+ 开源 AI 智能体、Agent Skills 和 RAG 应用的精选合集，支持 Claude、GPT、Gemini、Llama 等主流模型，可自由克隆、部署和商用。

**核心功能**:
- **Agent Skills 技能库**：提供 Project Graveyard（分析废弃项目原因）、Scope Creep Detector（检测需求蔓延）、Commit Archaeologist（追溯代码历史）等即装即用的编码智能体技能
- **多场景 AI 应用模板**：覆盖语音智能体（如保险理赔实时处理）、高级单/多智能体应用（如 AI 欺诈调查、家居改造设计）、常驻型智能体（如自动阅读 Hacker News 的简报助手）
- **快速启动方式**：支持 `npx skills add` 一键安装技能，或 `git clone` 后通过 Streamlit 快速运行完整应用
- **持续更新**：每周新增模板，可通过 Unwind AI 订阅获取最新内容

**技术亮点**: 基于 Python 构建，采用 Apache-2.0 开源协议；所有技能均通过安全审查和评估 CI 门禁；兼容 Claude Code、Codex、Cursor 等主流编码代理工具；每个应用均为端到端测试的完整可运行项目。

---
