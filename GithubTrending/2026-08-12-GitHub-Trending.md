---
tags:
  - github-trending
  - daily
date: 2026-08-12
created: 2026-08-12T01:55:44.173Z
---

# 2026-08-12 GitHub Trending Top 10

## 1. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 143,305
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个集合了多种专业化 AI 代理（Agent）的开源项目，每个代理都拥有独特的个性、工作流程和可交付成果，可集成到 Claude Code、Cursor、Codex 等主流 AI 编程工具中。

**核心功能**:
- **丰富的代理阵容**: 涵盖前端开发、UI 设计、Reddit 社区运营、创意内容生成、事实核查等多个领域的专业化 AI 代理，每个代理都有明确的角色定位和交付物
- **多工具集成**: 支持一键安装到 Claude Code、Cursor、Codex、Gemini CLI、OpenCode、Aider、Windsurf 等 15+ 种 AI 编程工具
- **灵活的选择性安装**: 支持按团队（division）或单个代理（agent）粒度进行安装，也可通过交互式向导挑选所需组合
- **跨平台桌面应用**: 提供 macOS、Linux、Windows 原生应用（Agency Agents），无需命令行即可浏览和安装代理，并支持自动更新
- **生产级设计**: 每个代理文件包含身份特征、核心使命、工作流程、代码示例、成功指标和沟通风格，可直接作为参考或复制使用

**技术亮点**: 基于 Shell 脚本实现自动化安装与配置；支持多工具适配层自动转换代理格式；提供 `--dry-run` 预演模式和 `--list teams` 团队清单查看功能；针对 OpenCode 的代理数量限制提供智能警告和子集安装建议。

---
## 2. [semantica-agi/semantica](https://github.com/semantica-agi/semantica)
- **语言**: Python
- **Stars**: 4,928
- **简介**: Graph-Native Infrastructure for Context and Accountable AI Systems

### AI 总结
**简介**: Semantica 是一个基于图原生的开源基础设施层，为 AI 系统提供上下文管理和可问责的决策智能，号称“AI Agents 的开源 Palantir”。

**核心功能**:
- **Context Graph 构建**: 从企业数据中提取关键信息，构建上下文图（Context Graph）和知识图谱（KG），无需依赖 LLM 即可完成图构建
- **决策智能与因果推理**: 支持在知识图谱上运行图分析和因果推理，内置完整的决策溯源（decision provenance）机制
- **本体管理与知识建模**: 提供本体（Ontology）管理和知识建模能力，支持 W3C 标准，兼容 RDF 和 LPG（Labeled Property Graph）两种图存储格式
- **端到端可追溯性**: 所有决策过程可解释、可追踪、可审计，特别针对金融借贷等高风险强监管场景设计

**技术亮点**:
- **多语言图存储**: 支持 Polyglot Graph Storage，兼容 RDF 和 LPG，确保与现有数据栈互通
- **确定性基础设施层**: 位于 LLM、向量数据库和 Agent 框架之下，图构建、推理和溯源均不依赖 LLM，保证确定性输出
- **零厂商锁定**: 完全开源、可自托管、可审计、可治理，支持直接集成 Databricks Unity Catalog 和 Snowflake 数据仓库，无需导出数据即可构建治理完善的 lineage 知识图谱
- **Python 3.8+ 支持**: 通过 `pip install semantica` 快速安装，采用 MIT 开源许可证

---
## 3. [nvm-sh/nvm](https://github.com/nvm-sh/nvm)
- **语言**: Shell
- **Stars**: 94,493
- **简介**: Node Version Manager - POSIX-compliant bash script to manage multiple active node.js versions

### AI 总结
**简介**: nvm 是一个 POSIX 兼容的 Node.js 版本管理器，允许用户通过命令行快速安装、切换和管理多个 Node.js 版本。

**核心功能**:
- 快速安装任意版本的 Node.js（如 `nvm install 24`）
- 在多个 Node.js 版本间自由切换（如 `nvm use 22`）
- 支持 `.nvmrc` 文件，自动切换目录对应的 Node 版本
- 支持离线安装、镜像源配置（含自定义镜像及 Authorization 认证）
- 支持全局包迁移（安装或切换版本时迁移全局 npm 包）
- 支持设置默认 Node 版本、自定义输出颜色
- 提供 Bash 补全功能，支持 Docker 环境安装
- 兼容 sh、bash、zsh、ksh、dash 等 POSIX shell，支持 Unix、macOS 和 Windows WSL

**技术亮点**: 采用纯 Shell 脚本实现，无需外部依赖；支持 per-user 安装和 per-shell 调用；提供自动化安装/更新脚本，并有完善的测试体系（GitHub Actions）和 CII 最佳实践认证。

---
## 4. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 86,241
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: agent-skills 是一套为 AI 编码代理准备的生产级工程技能包，将资深工程师的开发工作流、质量门禁和最佳实践编码为可复用的技能，帮助代理在开发全流程中保持一致的高标准。

**核心功能**:
- **8 个斜杠命令覆盖开发生命周期**: `/spec`（需求定义）、`/plan`（任务规划）、`/build`（增量构建）、`/test`（测试验证）、`/review`（代码审查）、`/webperf`（性能审计）、`/code-simplify`（代码简化）、`/ship`（生产发布），每个命令自动激活对应技能。
- **技能自动触发**: 根据当前工作内容（如 API 设计、前端 UI 构建）自动加载相应技能，无需手动干预。
- **`/build auto` 自动化模式**: 一次批准计划后，代理可自主完成所有任务的规划与实现，每个任务仍保持测试驱动并单独提交，遇错或高风险步骤自动暂停。
- **一键安装，兼容 70+ 代理**: 通过 `npx skills add addyosmani/agent-skills` 可安装全部 24 个技能，也支持按需单独安装单个技能（如代码审查、需求访谈、TDD）。
- **原生集成支持**: 提供 Claude Code（推荐，支持 marketplace 安装）、Cursor（`.cursor/skills/` + `.cursor/rules/`）等主流工具的详细配置指南。

**技术亮点**: 采用 Skills CLI（Vercel Labs）作为安装与分发机制；技能包遵循“定义-规划-构建-验证-审查-发布”的六阶段流水线架构；以 SKILL.md 格式封装工作流，支持跨工具（Claude Code、Cursor、Codex、Copilot、Cline 等）复用；内置 TDD（红-绿-重构）、五维代码审查等工程实践。

---
## 5. [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis)
- **语言**: Python
- **Stars**: 62,163
- **简介**: LLM 驱动的多市场股票智能分析系统：多源行情、实时新闻、决策看板与自动推送，支持零成本定时运行。 LLM-powered multi-market stock analysis system with multi-source market data, real-time news, decision dashboard, automated notifications, and cost-free scheduled runs.

### AI 总结
**简介**: 基于 AI 大模型的 A股/港股/美股/日股/韩股/台股多市场股票智能分析系统，每日自动生成决策仪表盘并推送至多平台，支持零成本定时运行。

**核心功能**:
- **AI 决策报告**: 自动生成核心结论、评分、趋势判断、买卖点位、风险警报及操作检查清单
- **多市场数据聚合**: 覆盖 A股、港股、美股、日股、韩股、台股及 ETF，整合行情、K线、技术指标、新闻、公告、基本面等数据
- **Web/桌面工作台**: 支持手动分析、任务进度追踪、历史报告查看、回测、持仓管理及深色/浅色主题
- **Agent 策略问股**: 内置均线、缠论、波浪、趋势、热点、事件等 15 种策略，支持多轮追问，覆盖 Web/Bot/API
- **智能导入与补全**: 支持图片、CSV/Excel、剪贴板导入，自动补全股票代码/名称/拼音/别名
- **自动化与多渠道推送**: 支持 GitHub Actions、Docker、本地定时任务、FastAPI 服务，推送至企业微信、飞书、Telegram、Discord、Slack、邮箱

**技术亮点**:
- **多 AI 模型支持**: 兼容 Anspire、AIHubMix、Gemini、OpenAI、DeepSeek、通义千问、Claude、Ollama 本地模型等
- **多数据源架构**: 内置 AkShare、Baostock、YFinance 等免费行情源（零配置可运行），支持 TickFlow、Tushare、Longbridge 等 token 型稳定数据源
- **灵活部署**: 支持 GitHub Actions 免费定时运行（5 分钟部署）、Docker 容器化及本地运行，无需服务器
- **多语言支持**: 提供简体中文、英文、繁体中文文档，Docker 镜像就绪

---
## 6. [vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag)
- **语言**: Python
- **Stars**: 3,842
- **简介**: The ultimate RAG for your monorepo. Query, understand, and edit multi-language codebases with the power of AI and knowledge graphs

### AI 总结
**简介**: Code-Graph-RAG 是一个面向多语言代码仓库的 RAG（检索增强生成）工具，通过知识图谱让开发者可以用自然语言查询、理解和编辑整个 monorepo 中的代码。

**核心功能**:
- **自然语言代码查询**: 用自然语言提问，获取基于代码真实结构的准确回答
- **多语言解析**: 通过 Tree-sitter 解析混合语言代码库，在 Memgraph 中构建统一的知识图谱
- **结构化搜索与替换**: 基于 AST 模式（ast-grep）查找和重写代码，支持跨代码库的结构化变换，而非依赖文本或正则
- **数据流追踪**: 新增 `FLOWS_TO` 污点边，追踪值在赋值、函数调用和 I/O 汇点间的流向，支持 10 种语言（Python、JavaScript、TypeScript/TSX、Go、Java、Rust、C++、C、C#）
- **代码检索与编辑**: 检索任意函数的实际源码，并支持直接编辑和优化代码

**技术亮点**:
- 使用 Tree-sitter 进行多语言代码解析，Memgraph 作为图数据库存储知识图谱
- 采用可插拔的 ast-grep 层，通过单个 YAML 模式文件即可添加新语言支持（如 Ruby），无需手写解析器
- 提供 Agent 工具接口，将结构化搜索和数据流追踪暴露为可调用的智能体工具
- 具备完整的 CI/CD 集成（GitHub Actions、Codecov、SonarCloud、OpenSSF Scorecard），并提供企业级支持服务

---
## 7. [anthropics/skills](https://github.com/anthropics/skills)
- **语言**: Python
- **Stars**: 168,158
- **简介**: Public repository for Agent Skills

### AI 总结
**简介**: anthropics/skills 是 Anthropic 官方发布的 Claude Agent Skills 公共仓库，包含技能示例、规范文档和模板，帮助开发者创建和使用可复用的技能来增强 Claude 在特定任务上的表现。

**核心功能**:
- **技能示例库**: 提供涵盖创意设计（艺术、音乐）、技术开发（Web 测试、MCP 服务器生成）和企业工作流（沟通、品牌）等多领域的技能示例
- **文档技能**: 内置支持 Claude 文档能力的 docx、pdf、pptx、xlsx 技能，作为复杂技能的参考实现
- **技能规范与模板**: 包含 Agent Skills 规范文档和可直接使用的技能模板，仅需 `SKILL.md` 文件加 YAML frontmatter 即可创建技能
- **多平台集成**: 支持在 Claude Code（通过插件市场安装）、Claude.ai（付费计划直接使用）和 Claude API 中使用
- **即插即用**: 通过 `/plugin marketplace add anthropics/skills` 命令即可注册为 Claude Code 插件市场，快速安装技能集

**技术亮点**: 技能以文件夹形式组织，每个技能包含 `SKILL.md` 文件（含 YAML frontmatter 元数据和指令），支持 Claude 按需动态加载；仓库采用 Apache 2.0 开源许可（文档技能为 source-available），使用 Python 作为主要语言。

---
## 8. [3b1b/manim](https://github.com/3b1b/manim)
- **语言**: Python
- **Stars**: 90,200
- **简介**: Animation engine for explanatory math videos

### AI 总结
**简介**: Manim 是 3Blue1Brown 作者开发的数学动画引擎，用于创建精确的程序化数学讲解视频。

**核心功能**:
- 通过 Python 代码精确控制动画元素，实现数学概念的视觉化演示
- 提供丰富的几何图形、函数图像、坐标轴等数学对象库
- 支持 LaTeX 公式渲染，可展示复杂的数学表达式
- 内置多种动画效果（变换、移动、淡入淡出等），支持自定义动画逻辑
- 提供命令行工具 `manimgl`，可快速渲染并预览动画场景

**技术亮点**:
- 基于 Python 3.10+，依赖 FFmpeg（视频处理）、OpenGL（渲染）、LaTeX（公式排版）
- 采用场景（Scene）驱动架构，用户通过定义场景类来组织动画流程
- 与社区版（ManimCommunity）区分，本仓库为原版 ManimGL，包名为 `manimgl`，注重视频制作的灵活性和创作自由度

---
## 9. [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)
- **语言**: Python
- **Stars**: 34,763
- **简介**: DeepTutor: Lifelong Personalized Tutoring. https://deeptutor.info/.

### AI 总结
**简介**: DeepTutor 是一个面向终身个性化辅导的开源 AI 教学平台，提供自适应学习体验与智能辅导能力。

**核心功能**:
- 个性化辅导：根据学习者情况提供定制化的教学路径与反馈
- 终身学习支持：支持长期学习过程中的知识追踪与记忆管理
- 多语言支持：提供中、英、日、西、法、阿、俄等 11 种语言界面
- CLI 代理原生接口：提供命令行交互方式，便于开发者集成与自动化使用
- 社区生态：通过 EduHub 技能社区共享与复用教学技能

**技术亮点**:
- 基于 Python 3.11+ 构建，前端采用 Next.js 16
- 集成 LightRAG 索引技术，支持高效的知识检索与记忆管理
- 提供 Discord、飞书、微信等社区支持，鼓励贡献者参与 Roadmap 规划
- 采用 Apache 2.0 开源协议，持续迭代发布新版本

---
## 10. [stablyai/orca](https://github.com/stablyai/orca)
- **语言**: TypeScript
- **Stars**: 42,829
- **简介**: Orca is the ADE for working with a fleet of parallel agents. Run any coding agent with your own subscription. Available on desktop, mobile and VPS.

### AI 总结
**简介**: Orca 是一款面向并行 AI 代理编排的桌面与移动端应用，支持同时运行多个编码代理（如 Codex、ClaudeCode 等）并在独立工作树中跟踪管理。

**核心功能**:
- **并行工作树**: 将同一提示词分发给多个代理，每个代理在独立 git 工作树中运行，便于对比结果并合并最佳方案
- **移动端伴侣应用**: 支持 iOS 和 Android，可随时监控代理进度、接收完成通知并远程发送后续指令
- **终端分屏**: 基于 Ghostty 的终端，支持 WebGL 渲染、无限分屏和重启后保留滚动历史
- **设计模式**: 在真实 Chromium 窗口中点击 UI 元素，自动将 HTML、CSS 和截图注入代理提示词
- **原生 GitHub 与 Linear 集成**: 应用内浏览 PR、Issue 和项目看板，从任务直接创建工作树，无需切换上下文
- **SSH 工作树**: 支持在远程高性能服务器上运行代理，包含完整文件编辑、git 和终端功能，支持自动重连和端口转发

**技术亮点**: 使用 TypeScript 开发，跨平台支持 macOS、Windows 和 Linux；采用 WebGL 终端渲染技术；内置 Chromium 嵌入式浏览器；遵循 MIT 开源协议，提供桌面、移动端和 VPS 多端部署方案。

---
