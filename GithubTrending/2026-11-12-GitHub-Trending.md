---
tags:
  - github-trending
  - daily
date: 2026-11-12
created: 2026-11-12T01:55:43.175Z
---

# 2026-11-12 GitHub Trending Top 10

## 1. [meta/astryx](https://github.com/meta/astryx)
- **语言**: TypeScript
- **Stars**: 25,085
- **简介**: An open source design system that's fully customizable and agent ready

### AI 总结
**简介**: Astryx 是 Meta 开源的设计系统，历经八年内部打磨（支撑 13000+ 应用），基于 React 19+ 与 StyleX 构建，兼顾人类开发者与 AI 助手协作，目前处于 Beta 阶段。

**核心功能**:
- 提供 150+ 无障碍组件，涵盖品牌级主题、暗色模式、开箱即用模板及 CLI 工具
- 开放式内部结构：组件可在任意层级组合，底层构建块直接导出，并可通过 swizzle 将组件完整源码弹出到项目中自行掌控
- 无样式锁定：样式用 StyleX 编写但对使用者透明，可用 Tailwind、CSS Modules 或原生 CSS 通过 `className` 覆盖
- 无需包装即可定制：主题即一组 CSS 自定义属性覆盖，设计师无需 fork 或包裹组件源码即可打造专属风格
- 面向人与 Agent 共同设计：API、文档与 CLI 统一设计，人类和 AI 助手基于同一参考以相同方式构建

**技术亮点**: 基于 React 19+（peer 依赖）与 StyleX 样式方案；采用预构建 CSS + 类型化 React 组件的使用方式，无需构建插件、PostCSS 或 Babel 配置；CLI 支持项目级与全局安装，方便 AI 编码助手直接调用；采用 MIT 许可证。

---
## 2. [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis)
- **语言**: Python
- **Stars**: 70,319
- **简介**: LLM 驱动的多市场股票智能分析系统：多源行情、实时新闻、决策看板与自动推送，支持零成本定时运行。 LLM-powered multi-market stock analysis system with multi-source market data, real-time news, decision dashboard, automated notifications, and cost-free scheduled runs.

### AI 总结
**简介**: 一个由 LLM 驱动的多市场股票智能分析系统，可每日自动分析自选股并将「决策仪表盘」推送到企业微信、飞书、Telegram 等渠道，支持零成本定时运行。

**核心功能**:
- **AI 决策报告**：输出核心结论、评分、趋势判断、买卖点位、风险警报、催化因素与操作检查清单
- **多市场数据聚合**：覆盖 A股、港股、美股、日股、韩股、台股及 ETF，汇聚行情、K线、技术指标、新闻、公告与基本面数据
- **Web 与桌面工作台**：支持手动分析、任务进度、历史报告、回测、持仓与配置管理，并提供浅色、深色主题
- **Agent 策略问股**：支持多轮追问，内置均线、缠论、波浪、趋势、热点等 15 种策略，覆盖 Web、Bot 与 API
- **智能导入与补全**：支持图片、CSV、Excel、剪贴板导入，以及股票代码、名称、拼音、别名的补全
- **自动化与推送**：通过 GitHub Actions、Docker、本地定时任务或 FastAPI 服务运行，并推送到企业微信、飞书、Telegram、Discord、Slack、邮箱

**技术亮点**: 基于 Python 3.10+，采用 MIT 协议；AI 模型兼容 Modelflare、Gemini、OpenAI、DeepSeek、通义千问、Claude、Ollama 等；行情源集成 AkShare、Tushare、Pytdx、Baostock、YFinance、Longbridge；新闻搜索接入 SerpAPI、Tavily、Bocha、Brave 等；内置免费数据源可零配置运行，同时支持 Docker 与 GitHub Actions 一键部署。

---
## 3. [GoogleChrome/modern-web-guidance-src](https://github.com/GoogleChrome/modern-web-guidance-src)
- **语言**: TypeScript
- **Stars**: 1,805
- **简介**: 

### AI 总结
**简介**: GoogleChrome/modern-web-guidance-src 是 Modern Web Guidance 的源码仓库，提供将现代 Web 平台专业知识、最佳实践与浏览器兼容性数据注入编码 Agent 的技能集合，引导开发者远离过时模式。

**核心功能**:
- 通过 CLI 向导一键安装（`npx modern-web-guidance@latest install`），将精选指南注入编码 Agent 的上下文窗口
- 支持搜索指南、按 ID 检索指南，以及扫描代码库中的遗留模式并给出现代化建议
- 覆盖用户体验（View Transitions、进出场动画）、CSS 布局（容器查询、subgrid、oklch）、性能优化（预加载、INP 诊断、`scheduler.yield`）、表单与 UI（Popover API、锚点定位、原生验证）等核心领域
- 指南设计注重 token 效率，通过评测剪除模型已掌握的冗余内容

**技术亮点**: 使用 TypeScript 开发；由 Google Chrome、Microsoft Edge、Mozilla Firefox 和 MDN 团队及 Web 开发社区共同维护；提供评估仪表盘用于指南的编写、校准与评测；强调现代浏览器原生 API、性能与无障碍，并引导使用轻量回退方案而非重型 polyfill。

---
## 4. [shadcn/improve](https://github.com/shadcn/improve)
- **语言**: Unknown
- **Stars**: 10,933
- **简介**: Use your most capable model to audit your codebase and write plans for cheaper models to execute.

### AI 总结
**简介**: shadcn/improve 是一个 Agent Skill，用能力最强的模型审计代码库并编写实施计划，再交给更便宜的模型执行，计划本身就是最终产物。

**核心功能**:
- 全量审计代码库，按九大类别（正确性、安全、性能、测试覆盖、技术债、依赖迁移、DX、文档、方向建议）并行派出子代理排查，每条发现均附带 `file:line` 证据、影响、工作量与置信度
- 对审计结果进行复核（Vet），重新核对每个引用位置以剔除误报，并记录被否决项的原因以避免重复出现
- 按杠杆率（影响 ÷ 工作量，按置信度加权）排序发现，由用户挑选后生成独立计划文件至 `plans/`，附索引、优先级顺序与依赖图
- 支持多种模式：`quick`（低成本快速扫描）、`deep`（全量深度）、`security`/`perf`/`tests`/`bugs`（定向审计）、`branch`（仅审计当前分支改动）、`next`（功能方向建议）
- `execute` 可将计划分派给更便宜的模型在隔离 worktree 中执行，并对照计划审查 diff 后给出结论；`reconcile` 用于刷新待办清单；`--issues` 可将计划发布为 GitHub Issue

**技术亮点**: 以 Agent Skills 格式分发（`npx skills add shadcn/improve`），可运行于任何支持该格式的 Agent；计划为纯 Markdown，任何 Agent 或人类均可接手。Recon 阶段会提取仓库的构建/测试/lint 命令作为每份计划的验证门禁，并读取 ADR、PRD、`CONTEXT.md` 等文档以避免重复标记已有取舍。计划面向"最弱可行执行者"编写，强调自包含、精确步骤、验证门禁与 STOP 条件。

---
## 5. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 115,985
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 一套面向 AI 编程代理的生产级工程技能包，将资深工程师的工作流程、质量门禁和最佳实践封装成可复用技能，让 AI 代理在开发各阶段保持一致行为。

**核心功能**:
- 9 个斜杠命令覆盖完整开发生命周期：`/spec`（定义需求）、`/plan`（制定计划）、`/build`（增量构建）、`/test`（测试验证）、`/constraints`（设定质量约束）、`/review`（合并前审查）、`/webperf`（Web 性能审计）、`/code-simplify`（代码简化）、`/ship`（发布上线）
- `/build auto` 自动模式：一次审批后自动生成计划并逐任务实现，每个任务仍保持测试驱动与独立提交，遇失败或高风险步骤自动暂停
- 技能可根据当前工作内容自动激活（如设计 API 触发 `api-and-interface-design`，构建 UI 触发 `frontend-ui-engineering`）
- 通过开放的 skills CLI 一键安装到 70+ 代理（Claude Code、Cursor、Codex、Copilot、Cline 等），也支持按需安装单个技能

**技术亮点**:
- 以 JavaScript 实现，围绕"定义→计划→构建→验证→审查→发布"六阶段流水线组织技能
- 提供 Claude Code 插件市场原生集成方式，支持命名空间命令（如 `/agent-skills:review`）避免与内置命令冲突
- 共 25 个技能，采用仓库级 `references/` 共享清单结构；单技能安装时存在共享清单不可用的可移植性限制（已在 issue #361 跟踪）

---
## 6. [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser)
- **语言**: Rust
- **Stars**: 49,902
- **简介**: Browser automation CLI for AI agents

### AI 总结
**简介**: agent-browser 是 Vercel Labs 推出的原生 Rust 浏览器自动化 CLI，让 AI Agent 通过逐条 shell 命令驱动浏览器完成网页操作。

**核心功能**:
- `snapshot` 将页面转换为紧凑的可访问性树文本，每个元素附带 `@e1` 形式的引用（ref），Agent 通过引用执行点击等操作
- 支持 `open`、`click`、`get url`、`close` 等命令，浏览器在命令间保持打开，每步仅需一次简短调用
- 除 ref 外，还支持 CSS 选择器、文本、XPath 和语义定位器（如 `find role button click --name "Submit"`）
- 点击目标不可见、被遮挡或超出视口时会明确失败而非误报成功
- 内置与 CLI 版本匹配的 skills（`skills get core` 等），方便接入 AI Agent 工作流

**技术亮点**:
- Rust 原生实现，通过后台 daemon 经 Chrome DevTools Protocol 控制浏览器，每个 `--session` 独立 daemon 与浏览器实例
- 默认使用 Chrome for Testing，支持 `--cdp`/`--auto-connect` 连接现有 Chrome，可切换 Lightpanda、Obscura 引擎、iOS 模拟器 Mobile Safari 及 Browserbase 等云浏览器
- 空闲一小时后自动关闭无头浏览器并退出，配置会话持久化时先保存状态
- 通过 npm/Homebrew 分发，支持 `npx` 免安装运行

---
## 7. [we-promise/sure](https://github.com/we-promise/sure)
- **语言**: Ruby
- **Stars**: 12,997
- **简介**: The personal finance app for everyone (by everyone)

### AI 总结
**简介**: Sure 是一个面向所有人的个人财务管理应用，是已停止开发的 Maybe Finance 项目的社区维护分支，采用 Ruby 开发并支持自托管。

**核心功能**:
- 个人财务与财富管理，提供现金流、净资产、支出与资金流出等仪表盘视图
- 内置 AI 助手，可回答关于储蓄等财务问题
- 支持多端访问：浏览器、macOS 桌面应用、移动应用、API 客户端及 LLM 代理
- 支持通过 Docker 自托管部署

**技术亮点**: 基于 Ruby 开发，依赖 PostgreSQL（>9.3）和 Redis（>5.4）；采用 AGPLv3 开源协议；使用 Skylight 提供公开的性能监控面板，便于定位和优化数据密集型请求的性能问题。

---
## 8. [homeassistant-ai/ha-mcp](https://github.com/homeassistant-ai/ha-mcp)
- **语言**: Python
- **Stars**: 7,395
- **简介**: Configure and automate Home Assistant with Claude, ChatGPT, and other AI assistants.

### AI 总结
**简介**: HA-MCP 是一个基于 Python 的 MCP 服务器，让 Claude、ChatGPT 等 AI 助手能够配置和自动化 Home Assistant 智能家居系统。

**核心功能**:
- 提供 87 个工具，覆盖 Home Assistant 的配置与自动化管理
- 通过 HACS 或 Marketplace（HA 2026.11+）以集成方式安装，在进程内运行完整服务器
- 兼容 Home Assistant OS、Supervised、Container、Core 等所有安装类型，功能完全一致
- 支持管理员访问令牌或专用账户认证，并提供远程访问（Secret URL / HA 登录）与本地网络访问两种客户端连接方式

**技术亮点**: 基于 FastMCP 框架构建；采用进程内服务器架构，随 Home Assistant 集成直接运行；具备端到端（E2E）测试流程；注意 v7.3.0 起 `ha_config_set_yaml` 已移至 beta 功能。

---
## 9. [openai/codex-security](https://github.com/openai/codex-security)
- **语言**: TypeScript
- **Stars**: 11,781
- **简介**: OpenAI's Codex Security CLI and TypeScript SDK for finding, validating, and fixing security vulnerabilities. npm: https://www.npmjs.com/package/@openai/codex-security

### AI 总结
**简介**: OpenAI 推出的代码安全工具，提供 CLI 和 TypeScript SDK，用于发现、验证并修复代码中的安全漏洞。

**核心功能**:
- 扫描仓库、指定路径或 Git 变更，支持 Standard 与 Deep 两种扫描模式（Deep 会重复 Standard 扫描并返回去重后的结果）
- 验证候选漏洞、生成补丁，并核验已有修复是否有效
- 生成 `SECURITY.md` 策略草案与威胁模型，供后续评审
- 浏览历史扫描与发现，识别重复项，按自定义标准评估严重程度，并结合源码与 Git 历史推荐负责人
- 导入第三方扫描器结果，可本地保存或发布至 Codex Security Cloud
- 将发现同步至 Linear、Jira、GitHub，或导出为 SARIF、JSON、CSV
- 支持跨仓库/组件的批量扫描，可用于 CI 与容器环境

**技术亮点**: 基于 TypeScript 实现，提供 npm 包 `@openai/codex-security`；CLI 命令 `cs` 与 `codex-security` 等价，可通过 `npx` 免全局安装；运行环境要求 Node.js 22.13.0+/24.x/26.x 与 Python 3.10+；支持 `OPENAI_API_KEY`/`CODEX_API_KEY` 环境变量用于 CI 无头运行，并提供 SDK 编程式调用（`CodexSecurity.run()`）。

---
## 10. [TheAlgorithms/Java](https://github.com/TheAlgorithms/Java)
- **语言**: Java
- **Stars**: 67,049
- **简介**: All Algorithms implemented in Java

### AI 总结
**简介**: TheAlgorithms/Java 是一个用 Java 实现各类算法的开源教育项目，旨在帮助学习者理解和练习算法。

**核心功能**:
- 收录大量用 Java 实现的算法，完整列表见 DIRECTORY.md
- 支持通过 Gitpod.io 在线运行、编辑算法代码，一键进入开发环境
- 提供持续集成构建与代码覆盖率检查（GitHub Actions、Codecov）
- 提供贡献指南（CONTRIBUTING.md），方便社区参与贡献

**技术亮点**: 纯 Java 实现；使用 GitHub Actions 做构建验证、Codecov 做覆盖率统计、Gitpod 提供云端开发环境、Discord 作为社区交流渠道。算法实现以教学为目的，效率可能低于 Java 标准库。

---
