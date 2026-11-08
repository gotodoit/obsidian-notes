---
tags:
  - github-trending
  - daily
date: 2026-11-08
created: 2026-11-08T01:55:43.895Z
---

# 2026-11-08 GitHub Trending Top 10

## 1. [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser)
- **语言**: Rust
- **Stars**: 46,861
- **简介**: Browser automation CLI for AI agents

### AI 总结
**简介**: agent-browser 是 Vercel Labs 推出的原生 Rust 命令行工具，为 AI Agent 提供可通过 shell 逐条命令驱动的浏览器自动化能力。

**核心功能**:
- `snapshot` 将页面转换为紧凑文本，并为每个元素分配 `@e1` 形式的引用，Agent 通过引用执行点击等操作，再重新读取页面验证结果
- 浏览器在命令之间保持打开，每一步只需一次简短的 shell 调用；支持 CSS 选择器、文本、XPath 及语义定位器（如 `find role button click --name "Submit"`）
- 点击目标隐藏、禁用、超出视口或被遮挡时会明确失败而非误报成功
- 内置与 CLI 版本匹配的 skills（`skills get core` 等），可直接装入 Agent 框架
- 支持多种浏览器引擎与接入方式：Chrome for Testing（默认）、CDP 附加、Lightpanda、Obscura、iOS 模拟器中的 Mobile Safari，以及 Browserbase 等云浏览器提供商

**技术亮点**: 采用 Rust 编写；命令通过后台守护进程经 Chrome DevTools Protocol 控制浏览器，每个 `--session` 拥有独立守护进程与浏览器，空闲一小时后自动关闭并保存状态；支持 npm、Homebrew、npx 多种安装方式，采用 Apache-2.0 许可。

---
## 2. [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill)
- **语言**: JavaScript
- **Stars**: 65,790
- **简介**: A coding-agent skill for multi-phase security audits with independently verified, machine-readable findings

### AI 总结
**简介**: Cloudflare 开源的编码智能体技能，通过多阶段流程对代码库进行结构化安全审计，产出经过独立验证、机器可读的漏洞发现记录。

**核心功能**:
- **六阶段审计流程**：侦察（架构、信任边界、输入面梳理）→ 覆盖驱动的漏洞狩猎（按账本单元分配隔离猎手）→ 候选验证（由全新验证者尝试证伪）→ 结构化输出（生成 `confirmed`/`needs_validation`/`rejected` 记录并做 schema 校验）→ 独立记录复核（新智能体复核最终来源声明）→ 目标无关报告（生成 `REPORT.md` 等文档）。
- **覆盖账本机制**：通过 `coverage-ledger.json` 追踪审计覆盖情况，并用 `validate-coverage-ledger.cjs` 在各阶段校验，避免遗漏。
- **增量式多次运行**：对同一仓库的多次审计可累加，利用历史账本和发现定位缺口、复核变更源码，不把过期或未解决的工作当作已覆盖。
- **多目标攻击类别库**：内置内存安全/二进制、AI/LLM、Web 协议与认证、客户端、供应链、云与部署、RPC 与消息、资源耗尽、数据隔离、桌面/移动与本地 IPC 等专用狩猎提示集。
- **零依赖校验工具**：提供 `validate-findings.cjs` 与 `validate-coverage-ledger.cjs` 两个零依赖校验器及配套测试。

**技术亮点**: 采用多智能体隔离协作架构（父智能体调度、独立猎手与验证者分工），以机器可读的 JSON 账本和发现记录为核心数据流，配合 JSON Schema 校验保证输出一致性；该技能是 Cloudflare 漏洞发现框架的单一仓库起点版本，可通过 Skills CLI 一键安装。

---
## 3. [google/skills](https://github.com/google/skills)
- **语言**: Python
- **Stars**: 23,433
- **简介**: Agent Skills for Google products and technologies

### AI 总结
**简介**: 该仓库收录了面向 Google 产品与技术（含 Google Cloud）的 Agent Skills 集合，可通过 `npx skills add google/skills` 一键安装到目标 Agent 中。

**核心功能**:
- **安装与更新**：通过 `npx skills add google/skills` 按需选择技能、目标 Agent 与安装范围（项目级/全局），并可用 `npx skills update` 升级至最新版本、清理废弃技能。
- **Google Cloud 入门**：提供 IAM 认证授权、Foundation Builder、Onboarding 等入门技能。
- **多产品解决方案**：覆盖架构设计、多 Agent 安全、跨云 Agentic 分析、无边界数据湖仓、AI Agent 构建部署、混合检索（AlloyDB）、GKE 推理迁移、RAG 企业搜索、n-tier Serverless Web 应用等场景。
- **AI/ML 能力**：涵盖 Agent Platform 的访问审计、告警配置、端点管理、评估、推理、Model Garden 部署、模型注册与调优、Prompt 管理、RAG Engine、故障排查，以及 BigQuery AI/ML、Gemini API、Genkit（Dart/Go/JS/Python）、LiveAPI、Pathways 调试等技能。

**技术亮点**: 采用 Agent Skills 标准格式组织，每个技能独立成目录，便于按需组合；以 Python 为主要语言，聚焦 Google Cloud 与 Gemini/Genkit 生态，并提供 `skills.sh` 徽章与在线安装入口。

---
## 4. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 317,754
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: mattpocock/skills 是 Matt Pocock 从自己 `.agents` 目录中整理出的一套日常工程用 AI Agent 技能集，主打“真实工程”而非“氛围编程”，强调小而可组合、可自由改造。

**核心功能**:
- 提供 `/grill-me` 与 `/grill-with-docs` 等技能，在动手前通过“拷问式问答”让 Agent 深入理解需求，解决人与 Agent 之间的沟通错位问题
- 面向多种 Agent 提供安装方式：Claude Code、Codex、GitHub Copilot（CLI/VS Code）、Gemini CLI 及其他兼容 Agent
- 安装后运行 `/setup-matt-pocock-skills`，一次性配置 issue 追踪器、triage 标签和文档保存位置
- 技能按工程类（engineering）与效率类（productivity）分类，可单独选用

**技术亮点**: 以 Shell 为主要语言，技能设计为小型、易适配、可组合，兼容任意模型；支持插件自动更新（Claude Code、Codex、Copilot）或手动更新（Gemini CLI、npx 方式），避免重复安装导致技能重复。

---
## 5. [anthropics/skills](https://github.com/anthropics/skills)
- **语言**: Python
- **Stars**: 188,823
- **简介**: Public repository for Agent Skills

### AI 总结
**简介**: Anthropic 官方开源的 Claude Agent Skills 示例仓库，展示如何通过模块化的指令文件夹教 Claude 可重复地完成专项任务。

**核心功能**:
- 提供覆盖创意设计、开发技术、企业沟通、文档处理等多领域的 Skill 示例，供开发者参考与借鉴
- 开源 Claude 文档能力的底层实现（`docx`、`pdf`、`pptx`、`xlsx`），作为生产级复杂 Skill 的参考范本
- 附带 Agent Skills 规范（`spec`）与 Skill 模板（`template`），便于快速创建自定义 Skill
- 支持在 Claude Code（通过插件市场安装）、Claude.ai（付费计划内置）和 Claude API 中直接使用

**技术亮点**: 每个 Skill 以独立文件夹自包含，核心为带 YAML frontmatter（必填 `name` 与 `description`）的 `SKILL.md`；Claude 按需动态加载指令、脚本与资源；主体采用 Python，多数 Skill 以 Apache 2.0 协议开源；官方声明内容仅供演示与教学，实际行为可能与 Claude 生产实现存在差异。

---
## 6. [meta/astryx](https://github.com/meta/astryx)
- **语言**: TypeScript
- **Stars**: 14,572
- **简介**: An open source design system that's fully customizable and agent ready

### AI 总结
**简介**: Astryx 是 Meta 开源的设计系统，历经八年内部打磨（支撑 13000+ 应用），基于 React 19 与 StyleX 构建，面向人类开发者与 AI 助手协同使用，目前处于 Beta 阶段。

**核心功能**:
- 提供 150+ 无障碍组件，涵盖品牌级主题定制、暗色模式、开箱即用的模板及 CLI 工具
- 开放式内部结构：组件可在任意层级组合，底层构建块直接导出，并支持通过 swizzle 将组件源码弹出到项目中自行掌控
- 无样式锁定：样式用 StyleX 编写但对使用方透明，可用 Tailwind、CSS Modules 或原生 CSS 通过 `className` 覆盖
- 主题即一组 CSS 自定义属性覆盖，无需 fork 或包装组件即可完成深度定制
- API、文档与 CLI 统一设计，使人与 AI 助手基于同一套参考进行构建

**技术亮点**: 基于 React 19+（peer 依赖）与 StyleX；导入预构建 CSS 即可使用类型化 React 组件，无需构建插件或 PostCSS/Babel 配置；CLI 支持项目级与全局安装，便于 AI 编码助手随处调用。

---
## 7. [prometheus/prometheus](https://github.com/prometheus/prometheus)
- **语言**: Go
- **Stars**: 67,452
- **简介**: The Prometheus monitoring system and time series database.

### AI 总结
**简介**: Prometheus 是 CNCF 旗下的开源系统与服务监控系统，同时也是一个时序数据库，使用 Go 语言开发。

**核心功能**:
- 按设定间隔从目标采集指标，评估规则表达式，展示结果并在满足条件时触发告警
- 提供 PromQL 强大灵活的查询语言，支持多维数据模型（指标名 + 键值维度定义时间序列）
- 支持服务发现或静态配置发现目标，支持通过中间网关推送批量任务的时间序列
- 提供多种图形化与仪表盘支持，以及分层与水平联邦能力

**技术亮点**:
- 不依赖分布式存储，单个服务器节点自治运行
- 采用 HTTP 拉取（pull）模型采集时间序列
- 多维度数据模型结合 PromQL，充分发挥维度查询能力
- 提供预编译二进制、Docker 镜像（Quay.io / Docker Hub）及源码构建（Go + NodeJS + npm）多种安装方式

---
## 8. [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock)
- **语言**: Python
- **Stars**: 100,570
- **简介**: Hunt down social media accounts by username across social networks

### AI 总结
**简介**: 一个用 Python 编写的开源工具，通过用户名在多个社交网络上追踪和定位对应的社交媒体账号。

**核心功能**:
- 根据用户名在数百个社交平台上批量查询账号是否存在
- 支持命令行使用，快速输出各平台的匹配结果

**技术亮点**: 基于 Python 实现，采用模块化的站点配置方式，便于扩展新的社交平台检测规则。

---
## 9. [milind-soni/OpenMausBot](https://github.com/milind-soni/OpenMausBot)
- **语言**: TypeScript
- **Stars**: 17,040
- **简介**: Open-source Grok Bot alternative with a virtual machine that bots can use

### AI 总结
**简介**: OpenMausBot 是一款开源的 Grok Bot 替代方案，将 AI 智能体以聊天应用的形式呈现，每个机器人都是运行在本地的真实智能体。

**核心功能**:
- 侧边栏中每个机器人都是独立智能体（底层运行 Claude 或 Codex），拥有各自的人格、模型、云电脑和已连接应用
- 像联系人一样与机器人对话，可观察其工作过程并对关键操作进行审批
- 每个智能体配备可使用的虚拟机/云电脑环境
- 支持自带智能体（bring-your-own-agent）、本地优先，运行在用户已有的模型之上

**技术亮点**: 采用 TypeScript（strict 模式）开发，前端基于 React 19，通过 Electron 构建跨平台桌面应用（支持 macOS Apple silicon/Intel、Windows x64、Ubuntu 24.04 x64）。项目独立开发，与 xAI、Meta、OpenAI、Manus 均无关联，且明确声明不涉及任何加密货币。

---
## 10. [astral-sh/ruff](https://github.com/astral-sh/ruff)
- **语言**: Rust
- **Stars**: 50,985
- **简介**: An extremely fast Python linter and code formatter, written in Rust.

### AI 总结
**简介**: Ruff 是一个用 Rust 编写的极快的 Python linter 和代码格式化工具，旨在以单一接口替代 Flake8、Black、isort 等多个工具。

**核心功能**:
- 速度比现有 linter（如 Flake8）和格式化工具（如 Black）快 10-100 倍
- 可通过 `pip` 安装，支持 `pyproject.toml` 配置
- 与 Flake8、isort、Black 实现即插即用的兼容
- 内置缓存机制，避免重复分析未变更文件
- 支持自动修复（如自动移除未使用的导入）
- 内置超过 900 条规则，原生重实现了 flake8-bugbear 等流行插件
- 提供 VS Code 等编辑器的官方集成
- 支持 monorepo 的分层级联配置

**技术亮点**: 使用 Rust 编写以获得极致性能；兼容 Python 3.15；由 Astral 公司（uv、ty 的创造者）支持，已被 Apache Airflow、FastAPI、Pandas、SciPy 等大型开源项目采用。

---
