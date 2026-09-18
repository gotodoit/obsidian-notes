---
tags:
  - github-trending
  - daily
date: 2026-09-18
created: 2026-09-18T01:55:43.126Z
---

# 2026-09-18 GitHub Trending Top 10

## 1. [alibaba/open-code-review](https://github.com/alibaba/open-code-review)
- **语言**: Go
- **Stars**: 34,879
- **简介**: Fast, efficient, battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level comments, built-in multi-language ruleset (NPE, thread-safety, XSS, SQL injection), OpenAI & Anthropic compatible.

### AI 总结
**简介**: 阿里巴巴开源的企业级 AI 代码审查 CLI 工具，基于确定性流水线 + LLM Agent 的混合架构，经阿里内部大规模验证。

**核心功能**:
- 读取 Git diff，通过具备工具调用能力的 LLM Agent 生成精确到行级的结构化审查评论
- 支持全文件扫描（`ocr scan`），适用于审计无有效 diff 的陌生代码库
- 内置多语言规则集，覆盖 NPE、线程安全、XSS、SQL 注入等常见缺陷
- 兼容 OpenAI 与 Anthropic 模型接口，配置模型端点即可使用
- 支持 Claude Code、Codex、Cursor、Kimi Code 等多种 Agent，跨 Windows/macOS/Linux 平台

**技术亮点**:
- 混合架构：确定性流水线 + LLM Agent 协同，兼顾准确性与效率
- 相比通用 Agent（如 Claude Code），在相同模型下 Precision 与 F1 显著更高，Token 消耗仅约 1/9，审查速度更快（刻意以较低 Recall 换取低噪声）
- 基于 50 个开源仓库、200 个真实 PR、10 种编程语言、80+ 资深工程师交叉验证的 AACR-Bench 基准测试
- Go 语言实现，已获 OpenSSF Gold 最佳实践认证

---
## 2. [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill)
- **语言**: JavaScript
- **Stars**: 10,758
- **简介**: A coding-agent skill for multi-phase security audits with independently verified, machine-readable findings

### AI 总结
**简介**: Cloudflare 开源的编码代理技能，通过多阶段编排将 AI 代理转变为安全审计员，产出经过独立验证的机器可读漏洞发现。

**核心功能**:
- **六阶段结构化审计流程**：侦察（绘制架构与信任边界）→ 覆盖驱动的漏洞搜寻 → 候选漏洞验证 → 结构化输出 → 独立记录验证 → 目标中立报告生成
- **覆盖账本（coverage-ledger.json）驱动**：将代码面拆分为账本单元分配给隔离的猎手代理，并由覆盖批评者查找遗漏
- **三态判定机制**：`confirmed`（含完整溯源与有界观测结果）、`needs_validation`（存在未解决事实、不含严重性）、`rejected`（已被证伪）
- **独立验证**：每个候选漏洞交由全新验证代理尝试证伪，最终结论再由独立代理复核
- **增量审计**：多次运行结果可叠加，利用历史账本和发现定位缺口、重验变更代码
- **零依赖校验工具**：`validate-findings.cjs` 与 `validate-coverage-ledger.cjs` 在流程各阶段强制校验输出格式

**技术亮点**:
- 内置丰富的攻击类知识库，覆盖内存安全/二进制/内核、AI/LLM 提示注入、Web 协议与认证、客户端 DOM 注入、供应链与发布、云与部署、RPC 与消息队列、资源耗尽、数据隔离与生命周期、桌面/移动与本地 IPC 等
- 采用 `report-schema.json` 定义统一的机器可读发现格式，便于自动化消费
- 通过 Skills CLI（`npx skills add`）安装，支持全局与项目级部署
- 源自 Cloudflare 漏洞发现平台（vulnerability harness）的原始单仓库版本，具工业级实践背景

---
## 3. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 95,875
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 一套面向 AI 编码代理的生产级工程技能库，将资深工程师的工作流、质量门禁和最佳实践编码为可复用的技能，让 AI 代理在开发各阶段保持一致的行为。

**核心功能**:
- **9 个斜杠命令**覆盖完整开发生命周期：`/spec`（定义需求）、`/plan`（任务规划）、`/build`（增量实现）、`/test`（测试验证）、`/constraints`（质量约束）、`/review`（合并前审查）、`/webperf`（性能审计）、`/code-simplify`（代码简化）、`/ship`（发布上线）
- **自动化技能激活**：根据当前任务自动触发对应技能，如设计 API 触发 `api-and-interface-design`，构建 UI 触发 `frontend-ui-engineering`
- **`/build auto` 自主模式**：批准计划后自动生成并执行所有任务，仍保持测试驱动和逐任务提交，遇失败或高风险步骤时暂停
- **单技能按需安装**：支持通过 `npx skills add` 安装全部 25 个技能或指定单个技能

**技术亮点**: 基于 JavaScript 开发，通过开放的 skills CLI 可安装到 70+ 种 AI 代理（Claude Code、Cursor、Codex、Copilot、Cline 等）；提供 Claude Code 插件市场原生集成和 Cursor 规则文件集成方式；每个技能独立打包，遵循红绿重构等强制工程规范。

---
## 4. [Tencent/BrowserSkill](https://github.com/Tencent/BrowserSkill)
- **语言**: TypeScript
- **Stars**: 4,239
- **简介**: Let AI agents use your real, logged-in browser without interrupting your work. CLI + extension for browser automation across any shell-capable AI agent.

### AI 总结
**简介**: BrowserSkill 是腾讯开源的一款工具，通过 CLI 与浏览器扩展的组合，让各类 AI Agent 直接操控用户已登录的真实浏览器，且不打断用户的正常使用。

**核心功能**:
- **复用真实登录状态**：Agent 可直接操作已登录的网站，无需额外的测试账号
- **不打断用户工作**：浏览器任务在独立的可见 Agent 窗口中运行，用户可继续使用自己的浏览器
- **兼容任意 Agent**：任何能调用 shell 的 Agent 均可通过 `bsk` CLI 使用，不绑定特定模型或框架
- **内置人工介入机制**：遇到验证码、登录、确认弹窗等步骤时，Agent 可请求用户接管并在完成后继续
- **整页截图**：支持通过快捷操作或 `bsk screenshot --full-page` 命令捕获长图

**技术亮点**:
- 采用 CLI/守护进程 + 浏览器扩展双运行时架构，CLI 负责命令调度，扩展负责页面操作
- 支持 macOS（Apple Silicon/Intel）、Linux（x64/ARM64）、Windows x64
- 兼容 Chrome 与 Microsoft Edge 等 Chromium 系浏览器，Firefox 在规划中
- 提供一键式 Agent 安装方式，也支持手动安装 CLI 与商店扩展
- 针对沙箱环境提供持久化守护进程方案（`BSK_HOME` + `BSK_AUTO_START=0`）

---
## 5. [alphaXiv/OpenResearch](https://github.com/alphaXiv/OpenResearch)
- **语言**: Rust
- **Stars**: 4,977
- **简介**: Turn your coding agents into research agents

### AI 总结
**简介**: OpenResearch 是一个本地优先的研究代理工作空间，可将 Claude Code、Codex、OpenCode、Cursor 等编码代理转变为能进行文献综述、假设生成、实验运行和产出研究成果的研究代理。

**核心功能**:
- **并行探索**：为每个研究方向提供独立的代理会话和隔离的 git worktree
- **可复现实验**：以 git 原生实验树追踪变体，每次运行都会获得其记录提交的不可变归档
- **上下文证据**：将日志、差异、文件、结果和产物与产生它们的工作绑定
- **代理可选**：支持 Claude Code、Codex、OpenCode、Cursor，可按会话选择 harness 和模型
- **计算可选**：支持本地、自有基础设施或托管的 OpenResearch 计算
- **本地所有权**：项目、对话、实验、运行、日志、代码和产物均保存在用户机器上
- **自动研究（Autoresearch）**：可自主完成"提出想法→修改代码→启动实验→检查证据→决定下一步"的完整循环，多个代理可并行探索不同方向
- **随处运行**：同一提交快照可本地、SSH 远程或运行于 Slurm、Kubernetes、Ray、Hugging Face Jobs、Modal、Tinker 等平台

**技术亮点**: 使用 Rust 语言开发；提供 CLI 工具（`orx`）及本地仪表盘（`http://127.0.0.1:4791`）；通过 `orx install-skills` 集成到编码代理；支持连接 LM Studio、oMLX、Ollama 等本地模型；`orx up --remote user@host` 可在远程 GPU 旁运行工作空间并在笔记本浏览器中操作。

---
## 6. [anthropics/claude-code](https://github.com/anthropics/claude-code)
- **语言**: TypeScript
- **Stars**: 145,893
- **简介**: Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands.

### AI 总结
**简介**: Claude Code 是 Anthropic 推出的终端智能编码工具，通过自然语言命令理解代码库、执行日常任务并加速开发流程。

**核心功能**:
- 执行常规编码任务，解释复杂代码逻辑
- 处理 Git 工作流，支持终端、IDE 及 GitHub 多平台使用
- 提供插件机制，可通过自定义命令和 Agent 扩展功能
- 内置 `/bug` 命令快速反馈问题

**技术亮点**: 基于 TypeScript 开发，运行于 Node.js 18+ 环境；支持多种安装方式（安装脚本、Homebrew、WinGet、NPM）；注重数据隐私保护，限制敏感信息保留期限并明确禁止将反馈用于模型训练。

---
## 7. [NationalSecurityAgency/ghidra](https://github.com/NationalSecurityAgency/ghidra)
- **语言**: Java
- **Stars**: 78,520
- **简介**: Ghidra is a software reverse engineering (SRE) framework

### AI 总结
**简介**: Ghidra 是由美国国家安全局（NSA）研究部门开发并维护的一款软件逆向工程（SRE）框架，提供跨平台的高端代码分析工具。

**核心功能**:
- 支持反汇编、汇编、反编译、图形化展示和脚本编写等多种分析能力
- 兼容多种处理器指令集和可执行文件格式
- 支持交互式与自动化两种运行模式
- 用户可使用 Java 或 Python 开发自定义扩展组件和脚本

**技术亮点**: 基于 Java 构建，支持 Windows、macOS 和 Linux 平台；专为解决复杂 SRE 任务中的规模化和团队协作问题而设计，提供可定制、可扩展的研究平台；支持通过 Eclipse GhidraDev 插件或 VS Code 进行扩展开发。

---
## 8. [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)
- **语言**: Python
- **Stars**: 24,582
- **简介**: Open source repository of plugins primarily intended for knowledge workers to use in Claude Cowork

### AI 总结
**简介**: Anthropic 开源的知识工作者插件集合，将 Claude 定制为特定岗位、团队和公司的专家助手。

**核心功能**:
- 提供 11 个面向不同职能的插件：生产力、销售、客户支持、产品管理、市场营销、法务、财务、数据、企业搜索、生物研究及插件管理
- 每个插件打包了技能（Skills）、连接器（Connectors）、斜杠命令（Slash Commands）和子代理，覆盖具体岗位的完整工作流
- 支持通过 Cowork 或 Claude Code 一键安装，安装后自动激活，技能按需触发，命令可显式调用
- 支持企业自定义，适配公司自身的工具、术语和流程

**技术亮点**:
- 基于 MCP（Model Context Protocol）连接外部工具（如 Slack、Jira、HubSpot、Snowflake 等）
- 统一插件结构：`.claude-plugin/plugin.json`（清单）、`.mcp.json`（工具连接）、`commands/`（斜杠命令）、`skills/`（领域知识）
- 完全基于文件驱动，便于版本管理和分发
- 兼容 Claude Cowork 和 Claude Code 两个平台

---
## 9. [Tencent/WeKnora](https://github.com/Tencent/WeKnora)
- **语言**: Go
- **Stars**: 26,292
- **简介**: Open-source LLM knowledge platform: turn raw documents into a queryable RAG, an autonomous reasoning agent, and a self-maintaining Wiki.

### AI 总结
**简介**: WeKnora 是腾讯开源、基于 Go 构建的 LLM 知识平台，可将原始文档转化为可查询的 RAG、自主推理 Agent 与自维护 Wiki。

**核心功能**:
- **RAG 快速问答**：面向日常查询的语义检索与问答能力
- **ReAct Agent**：自主编排检索、MCP 工具、租户技能目录、Docker/E2B/Cube 沙箱及网络搜索，处理多步复杂任务
- **Wiki 模式**：将原始文档提炼为自维护、互链的 Markdown 知识库，支持交互式知识图谱、手动编辑、版本历史与一键回滚
- **跨会话长期记忆**：记住用户身份与高频问题
- **知识管理**：树状文件夹视图保留上传目录结构，支持分块编辑、diff 与回退
- **多源接入**：飞书 Wiki/Drive、GitLab、腾讯 IMA、Notion、语雀、钉钉文档、RSS 等，支持 PDF/Word/图片/Excel/XMind 等 10+ 格式
- **多端问答**：可通过企业微信、飞书、Slack、Telegram 等 IM 渠道直接服务
- **企业级能力**：多工作区 RBAC（4 级角色矩阵 + 资源归属 + 审计日志）、作用域 API Key、多实例存储后端、网站嵌入组件

**技术亮点**:
- 语言：Go；采用完全模块化架构，可替换 LLM、向量数据库与存储后端
- LLM 兼容性：支持 OpenAI、DeepSeek、Qwen、智谱、混元、Gemini、MiniMax、NVIDIA、LiteLLM、Ollama 等 20+ 提供商
- 可观测性：集成 Langfuse，并提供运行时任务队列看板与 worker 池治理
- 部署：支持本地与私有云自托管，保障数据主权；Office 文件可通过 anydoc 进程内解析
- 许可证：MIT

---
## 10. [abue-ammar/tinycast](https://github.com/abue-ammar/tinycast)
- **语言**: Swift
- **Stars**: 6,163
- **简介**: Tinycast — a tiny, fully native macOS launcher, hotkeys, and clipboard history.

### AI 总结
**简介**: Tinycast 是一款完全原生、轻量的 macOS 启动器，集应用启动、全局热键与剪贴板历史于一体，内存占用低于 100 MB。

**核心功能**:
- **应用启动器**：模糊搜索并启动任意应用，支持固定收藏、查看运行中的应用、批量退出应用。
- **全局热键与单应用热键**：一个快捷键随时唤出面板；可为单个应用绑定按键，实现聚焦/隐藏切换。
- **文件搜索**：基于 Spotlight 从指定文件夹打开文件与目录，无需自建索引。
- **剪贴板历史**：支持文本与图片，可搜索并粘贴回原应用。
- **计算器**：在面板内直接进行数学运算、单位换算及实时货币/加密货币换算。
- **Quicklinks**：将 URL、搜索、文件或深链转为命令，支持输入、剪贴板、日期等占位符。
- **Apple 快捷指令**：搜索并运行系统快捷指令，支持别名与全局热键。
- **代码片段**：可复用的 Markdown 模板，支持动态占位符、参数、嵌套引用与关键词展开。
- **自定义命令**：通过模糊搜索或专属全局热键运行命名 shell 命令。
- **窗口管理**：34 种 Rectangle 风格操作，涵盖半屏、四分之一、三分之一、尺寸调整、微移、跨屏、全屏与空间切换。
- **系统操作**：锁屏、睡眠、重启、清空废纸篓、切换外观、蓝牙、静音、显示隐藏文件等。
- **日历与会议**：在空面板和菜单栏显示下一场会议，一键或自动加入。
- **笔记**：无限量纯 Markdown 文件集中于浮动编辑器，可从面板搜索。
- **Emoji 选择器**：可搜索的 Emoji 网格，一键唤出。
- **AI 对话**：使用自有 API Key 或已安装的 AI 账号，在面板中对话，默认关闭。
- **快速操作**：对任意应用中选中文本进行语法修正、改写、翻译或摘要。
- **Raycast 扩展**：原生运行已有 Raycast 扩展，以 SwiftUI 渲染。
- **备份与导入**：导出设置为文件，或从 Raycast 导入配置。

**技术亮点**: 基于 Swift

---
