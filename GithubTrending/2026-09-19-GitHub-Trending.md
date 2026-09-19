---
tags:
  - github-trending
  - daily
date: 2026-09-19
created: 2026-09-19T01:55:42.709Z
---

# 2026-09-19 GitHub Trending Top 10

## 1. [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill)
- **语言**: JavaScript
- **Stars**: 13,790
- **简介**: A coding-agent skill for multi-phase security audits with independently verified, machine-readable findings

### AI 总结
**简介**: Cloudflare 开源的安全审计技能，将编码智能体转化为多阶段安全审计器，通过隔离智能体协作产出可独立验证、机器可读的漏洞发现。

**核心功能**:
- **六阶段结构化审计流程**：侦察（架构与信任边界映射）→ 覆盖率驱动的漏洞挖掘 → 候选漏洞验证 → 结构化输出（`findings.json`）→ 独立记录验证 → 目标无关报告生成
- **三态结论体系**：`confirmed`（完整溯源与可观测结果）、`needs_validation`（存在未解决事实且无严重性评级）、`rejected`（已证伪候选）
- **多次运行增量叠加**：复用历史账本与发现，针对变化源码重新验证，避免将陈旧或未解决工作误判为已覆盖
- **内置零依赖校验器**：`validate-coverage-ledger.cjs` 与 `validate-findings.cjs` 确保覆盖率账本与发现记录符合 JSON Schema
- **丰富的攻击类别提示库**：覆盖内存安全/二进制、AI/LLM、Web 协议与认证、客户端、供应链、云部署、RPC 消息、资源耗尽、数据隔离、桌面移动端等多个领域

**技术亮点**: 基于多智能体隔离协作架构，每个候选漏洞交由全新验证者尝试证伪，最终结论再经独立智能体二次核验；采用覆盖率账本（coverage ledger）驱动挖掘，防止遗漏；通过 JSON Schema 强制约束输出格式，保证机器可读与可复现；该项目是 Cloudflare 全舰队漏洞发现系统（vulnerability harness）的单仓库起点。

---
## 2. [anthropics/claude-code](https://github.com/anthropics/claude-code)
- **语言**: TypeScript
- **Stars**: 146,317
- **简介**: Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands.

### AI 总结
**简介**: Claude Code 是 Anthropic 推出的终端智能编程工具，通过自然语言命令理解代码库、执行日常任务并处理 Git 工作流。

**核心功能**:
- 通过自然语言命令执行常规编程任务、解释复杂代码
- 处理 Git 工作流，支持在终端、IDE 或 GitHub 中通过 @claude 调用
- 提供可扩展插件系统，支持自定义命令和代理

**技术亮点**: 基于 TypeScript 开发，要求 Node.js 18+，支持 macOS/Linux/Windows 多平台安装（curl、Homebrew、WinGet 等），npm 安装方式已弃用

---
## 3. [alibaba/open-code-review](https://github.com/alibaba/open-code-review)
- **语言**: Go
- **Stars**: 36,713
- **简介**: Secure, fast, efficient, battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level comments, built-in multi-language ruleset (NPE, thread-safety, XSS, SQL injection), OpenAI & Anthropic compatible.

### AI 总结
**简介**: 阿里巴巴开源的企业级 AI 代码审查 CLI 工具，基于确定性流水线 + LLM Agent 的混合架构，经过阿里内部大规模验证。

**核心功能**:
- 读取 Git diff，通过具备工具调用能力的 Agent 将变更文件发送给可配置 LLM，生成精确到行级的结构化审查评论
- Agent 可读取完整文件内容、搜索代码库、查看其他变更文件以获取上下文，实现深度审查
- `ocr scan` 命令支持对无有效 diff 的整个文件进行审查，适用于陌生代码库审计
- 内置多语言规则集，覆盖 NPE、线程安全、XSS、SQL 注入等常见缺陷
- 仅需配置模型端点即可使用，兼容 OpenAI 与 Anthropic

**技术亮点**:
- 混合架构：确定性流水线 + LLM Agent 相结合
- 基于 Go 语言开发，支持 Windows / macOS / Linux
- 兼容 Claude Code、Codex、Cursor、Kimi Code 等多种 Agent
- 相比通用 Agent（如 Claude Code），在相同底层模型下 Precision 与 F1 显著更高，Token 消耗仅为约 1/9，审查速度更快
- 已在 AACR-Bench 基准（50 个开源仓库、200 个真实 PR、10 种语言、80+ 资深工程师交叉验证）上评测
- 通过 OpenSSF Gold 最佳实践认证

---
## 4. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 262,096
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个面向 AI 编码代理（Agent Harness）的性能优化系统，为 Claude Code、Codex、Opencode、Cursor 等工具提供技能、本能、记忆、安全与研究优先的开发能力。

**核心功能**:
- **技能与本能（Skills & Instincts）**: 为编码代理注入可复用的技能模块和直觉式行为模式
- **记忆系统（Memory）**: 为代理提供跨会话的上下文记忆能力
- **安全防护（Security）**: 内置 `ecc-agentshield` 安全组件，保障代理运行安全
- **研究优先开发（Research-first Development）**: 强调先调研再编码的开发范式
- **多平台支持**: 兼容 Claude Code、Codex、Opencode、Cursor 等多种 AI 编码工具
- **插件化安装**: 通过 `ecc@ecc` 插件、npm 包（`ecc-universal`、`ecc-agentshield`）及 GitHub App 多种渠道分发

**技术亮点**:
- 以 JavaScript 为主要语言，同时集成 Shell、TypeScript、Python、Go、Java、Perl 等多语言生态
- 提供 npm 包、GitHub App、CLI 插件等多种分发形态，安装灵活
- 支持 13 种语言文档（含简繁中文），社区国际化程度高
- 采用 MIT 开源协议，拥有 Discord 社区与官方网站（ecc.tools）支持

---
## 5. [Tencent/BrowserSkill](https://github.com/Tencent/BrowserSkill)
- **语言**: TypeScript
- **Stars**: 5,331
- **简介**: Let AI agents use your real, logged-in browser without interrupting your work. CLI + extension for browser automation across any shell-capable AI agent.

### AI 总结
**简介**: BrowserSkill 是腾讯开源的工具，让 AI Agent 直接复用你已登录的真实浏览器，在不打断你日常使用的前提下完成自动化任务。

**核心功能**:
- **复用真实登录态**：Agent 直接操作你已登录的网站，无需单独的测试账号
- **互不干扰**：浏览器任务在独立的可视化 Agent Window 中运行，你可以继续使用自己的浏览器
- **通用 Agent 支持**：任何能调用 shell 的 Agent（Cursor、Claude Code、Codex、OpenClaw、CodeBuddy 等）均可通过 `bsk` CLI 使用，不锁定特定模型或框架
- **内建 Human-in-the-loop**：遇到验证码、登录、确认弹窗等人类专属步骤时，Agent 可请求你接管，完成后继续执行
- **整页截图**：支持 Quick actions 或 `bsk screenshot --session <id> --full-page` 命令截取长图

**技术亮点**:
- 采用 **CLI/daemon + 浏览器扩展** 双组件本地运行时架构
- 支持 macOS（Apple Silicon / Intel）、Linux（x64 / ARM64）、Windows x64
- 兼容 Chrome 与 Microsoft Edge，其他 Chromium 内核浏览器（支持未打包扩展）预期可用，Firefox 在计划中
- 支持沙箱环境部署（通过共享 `BSK_HOME` 与 `BSK_AUTO_START=0` 保持 daemon 持久化）
- 使用 TypeScript 开发

---
## 6. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 96,423
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 该项目为 AI 编程助手提供一套生产级工程技能（Skills），将资深工程师的工作流、质量门禁和最佳实践打包，让 AI 代理在开发各阶段保持一致的行为规范。

**核心功能**:
- **9 个斜杠命令覆盖完整开发生命周期**：`/spec`（定义需求）、`/plan`（任务规划）、`/build`（增量构建）、`/test`（测试验证）、`/constraints`（质量约束）、`/review`（合并前审查）、`/webperf`（性能审计）、`/code-simplify`（代码简化）、`/ship`（发布上线）
- **自动化构建模式**：`/build auto` 可在一次审批后自动生成计划并逐任务实现，每个任务仍遵循测试驱动并单独提交，遇失败或高风险步骤自动暂停
- **技能自动激活**：根据当前工作内容自动触发相关技能，如设计 API 触发 `api-and-interface-design`，构建 UI 触发 `frontend-ui-engineering`
- **灵活安装方式**：支持通过 `npx skills` 一键安装至 70+ 代理（Claude Code、Cursor、Codex、Copilot、Cline 等），也支持单个技能按需安装或原生插件集成

**技术亮点**: 基于 JavaScript 实现，通过开放 skills CLI 实现跨代理兼容；采用技能模块化设计，每个技能可独立安装使用；提供 Claude Code 插件市场原生集成及 Cursor 的 `.cursor/skills/` 目录同步方案。

---
## 7. [TencentCloud/Octop](https://github.com/TencentCloud/Octop)
- **语言**: Python
- **Stars**: 3,970
- **简介**: A smarter, self-hosted AI assistant — multi-user, multi-agent.

### AI 总结
**简介**: Octop 是腾讯云开源的一款自托管 AI 助手，采用多用户、多智能体架构，支持通过 Web、CLI 及多种 IM 渠道进行交互，数据完全保留在本地。

**核心功能**:
- **多用户专家团队**：支持管理员与多用户共享，内置专家库可按场景切换不同专家
- **MBTI 人格系统**：提供 16 种人格模板及互动测试，为每个智能体赋予独特性格
- **多渠道接入**：支持 Web Dashboard、飞书、钉钉、QQ、Discord、企业微信及 HTTP/SSE/WebSocket 编程接口
- **连接器生态**：集成腾讯套件（文档、微博热搜、新闻等），支持 OAuth 与 MCP 网关扩展
- **知识库与 RAG**：基于私有文档的语义检索，让智能体回答有据可依
- **终端 AI+ / 浏览器 AI+ / 远程桌面**：浏览器内交互式 Shell、无头 Chromium 网页自动化、跨平台远程桌面
- **ACP 双向集成**：支持 IDE/终端 AI 工作流，可委托 OpenCode / Claude Code 并设权限门控
- **插件系统**：支持第三方插件扩展，内置插件按需启用

**技术亮点**:
- 基于 Python 3.12+，MIT 协议开源，单进程启动即可运行全部服务
- 内置安全机制：JWT 多用户隔离、工具审批、Shell 命令护栏、PII 脱敏
- 可插拔存储后端：本地磁盘、Docker 容器、PostgreSQL 或 COS/S3
- 便携式记忆（harness-memory），记忆随工作区迁移
- 所有数据统一存放于 `~/.octop/`，默认 SQLite，可选 PostgreSQL

---
## 8. [Fission-AI/OpenSpec](https://github.com/Fission-AI/OpenSpec)
- **语言**: TypeScript
- **Stars**: 69,373
- **简介**: Spec-driven development (SDD) for AI coding assistants.

### AI 总结
**简介**: OpenSpec 是一个面向 AI 编程助手的规格驱动开发（SDD）框架，通过结构化的 Markdown 规格文档引导 AI 完成从需求探索到代码实现的全流程。

**核心功能**:
- **规格驱动工作流**：通过 `/opsx:explore`、`/opsx:propose`、`/opsx:apply`、`/opsx:archive` 等命令，让 AI 先产出提案、规格、设计文档和任务清单，经人工确认后再写代码
- **纯 Markdown 规格**：需求与场景以普通 Markdown 编写，无需学习特殊语法，AI 负责撰写、开发者负责审阅
- **跨仓库协作（Stores）**：支持将规划独立成仓库，让 API、Web、共享库等多个代码库共享同一份规格，团队与各类编码代理均可读取
- **变更归档机制**：完成的变更自动归档并更新规格，保持文档与代码同步

**技术亮点**: 基于 TypeScript 开发，以 npm 包 `@fission-ai/openspec` 发布；采用"流体而非僵化、迭代而非瀑布"的设计哲学，兼容棕地项目，可从个人项目扩展至企业级；项目自身即用 OpenSpec 构建，仓库内提供真实规格与变更示例。

---
## 9. [ankitects/anki](https://github.com/ankitects/anki)
- **语言**: Rust
- **Stars**: 31,215
- **简介**: Anki is a smart spaced repetition flashcard program

### AI 总结
**简介**: Anki 是一款智能间隔重复闪卡程序，本仓库为其桌面版源代码。

**核心功能**:
- 基于间隔重复算法帮助用户高效记忆
- 提供闪卡学习与复习功能

**技术亮点**: 主要使用 Rust 语言开发，拥有完善的 CI 流程、文档和代码覆盖率检测。

---
## 10. [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)
- **语言**: Python
- **Stars**: 24,892
- **简介**: Open source repository of plugins primarily intended for knowledge workers to use in Claude Cowork

### AI 总结
**简介**: Anthropic 开源的知识工作插件集合，为 Claude Cowork（兼容 Claude Code）提供面向特定职能角色的专业化能力扩展。

**核心功能**:
- 提供 11 个开箱即用的职能插件：生产力、销售、客户支持、产品管理、市场营销、法务、财务、数据、企业搜索、生物研究及插件管理
- 每个插件封装特定岗位所需的技能（Skills）、斜杠命令（Commands）、工具连接器（Connectors）和子代理
- 通过 MCP 协议连接外部工具（如 Slack、Notion、Jira、Salesforce、Snowflake 等），实现跨系统数据拉取与操作
- 支持企业按自身工具链、术语和流程自定义插件，使 Claude 适配团队特定工作方式

**技术亮点**:
- 基于文件的标准插件结构：`plugin.json` 清单 + `.mcp.json` 工具连接 + `commands/` 显式命令 + `skills/` 自动触发领域知识
- 通过 MCP（Model Context Protocol）服务器集成第三方工具生态
- 兼容 Cowork 与 Claude Code 双平台，支持 marketplace 方式一键安装（`claude plugin marketplace add` / `claude plugin install`）
- 技能自动激活机制：相关场景下 Skills 自动生效，斜杠命令按需调用

---
