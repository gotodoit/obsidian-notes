---
tags:
  - github-trending
  - daily
date: 2026-08-07
created: 2026-08-07T01:55:45.265Z
---

# 2026-08-07 GitHub Trending Top 10

## 1. [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory)
- **语言**: TypeScript
- **Stars**: 16,451
- **简介**: TencentDB Agent Memory is a team-level memory hub for AI Agents — turning conversations, docs, and code into four reusable memory assets (Chat Memory, Skill, LLM-Wiki, Code-Graph) that are governed, shared, and equipped across agents and frameworks.

### AI 总结
**简介**: TencentDB Agent Memory 是一个团队级 AI Agent 记忆中枢，将对话、文档和代码转化为四种可复用的记忆资产（Chat Memory、Skill、LLM-Wiki、Code-Graph），实现记忆的治理、共享与跨框架复用。

**核心功能**:
- **符号化短期记忆**: 将繁重的工具日志压缩为紧凑的 Mermaid 符号，大幅降低 Token 消耗并提升任务成功率
- **分层长期记忆**: 将碎片化对话提炼为结构化的人物画像和场景，替代扁平向量存储
- **四种记忆资产**: 支持对话记忆（Chat Memory）、技能（Skill）、LLM 知识库（LLM-Wiki）和代码图谱（Code-Graph）
- **跨会话经验复用**: 让 Agent 学习工作流程、保留任务上下文并复用过往经验，避免人类重复解释
- **渐进式披露机制**: 通过 `node_id` 支持层级下钻，仅在出错时访问底层细节

**技术亮点**: 采用 TypeScript 构建，基于**记忆分层**（L0 对话 → L1 原子事实 → L2 场景 → L3 人物画像）和**符号化记忆**双支柱架构。实测数据表现优异：与 OpenClaw 集成后 Token 消耗最高降低 **61.38%**，任务通过率相对提升 **51.52%**，PersonaMem 准确率从 48% 提升至 **76%**。支持 OpenClaw、Hermes 等框架，通过 npm 分发，MIT 开源协议。

---
## 2. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 82,975
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 该项目为 AI 编程代理提供了一套生产级工程技能，将资深工程师的工作流、质量门禁和最佳实践编码为可复用的技能包，帮助 AI 代理在开发全流程中保持一致的高质量输出。

**核心功能**:
- **8 个斜杠命令**：映射完整开发生命周期，包括 `/spec`（定义）、`/plan`（规划）、`/build`（构建）、`/test`（测试）、`/review`（审查）、`/webperf`（性能）、`/code-simplify`（简化）、`/ship`（发布），每个命令自动激活对应技能
- **自动技能触发**：根据当前任务类型自动激活相关技能，如 API 设计触发 `api-and-interface-design`，UI 构建触发 `frontend-ui-engineering`
- **`/build auto` 自动化模式**：一次审批计划后自动执行所有任务，每个任务仍遵循测试驱动开发并独立提交，遇失败或风险自动暂停
- **24 个可独立安装的技能**：支持按需安装单个技能（如 `code-review-and-quality`、`interview-me`、`test-driven-development`），也可通过 CLI 一键安装全部
- **多代理兼容**：通过 `npx skills add` 命令可安装到 70+ 代理（Claude Code、Cursor、Codex、Copilot、Cline 等），并支持原生插件市场集成

**技术亮点**:
- 基于 JavaScript 实现，采用 `npx skills` CLI 分发机制
- 支持插件市场安装（Claude Code）和本地目录同步（Cursor）两种集成方式
- 技能包采用模块化结构，每个技能独立存放于 `skills/<name>/` 目录
- 内置测试驱动开发（红-绿-重构）和代码审查（五维审查）等工程方法论
- 提供自动化构建模式，在减少人工干预的同时保留验证环节

---
## 3. [cloudflare/computer](https://github.com/cloudflare/computer)
- **语言**: TypeScript
- **Stars**: 4,842
- **简介**: Give your agent a computer 👾

### AI 总结
**简介**: Cloudflare Computer 是一个基于 Durable Object 的虚拟文件系统，为 AI 智能体提供可执行的计算环境。

**核心功能**:
- **虚拟文件系统**: 以 SQLite 为权威存储，通过 Durable Object 提供文件系统抽象
- **多后端执行**: 支持容器（FUSE 挂载）、隔离 Shell（just-bash）、隔离 JavaScript（ECMAScript 模块）三种运行后端
- **统一执行入口**: 通过 `workspace.runtime.exec(source, { backend })` 单一 API 执行命令或模块
- **懒连接机制**: 后端在首次使用时才建立连接，灵活切换
- **独立文件系统模式**: 可不附带任何后端，单独使用文件系统能力

**技术亮点**:
- 基于 Cloudflare Durable Objects + SQLite 实现权威状态管理
- 使用 capnweb RPC 协议同步容器内文件系统状态
- 支持 FUSE 挂载、Dynamic Workers、Workers RPC 等 Cloudflare 原生技术
- 提供 `ws:git`、`ws:artifacts` 等可信模块，支持文件导入和制品发布
- 采用 monorepo 结构，包含 `@cloudflare/dofs`、`@cloudflare/computer-rpc`、`@cloudflare/computerd` 等子包

> ⚠️ 注意：该项目目前为**预览版**，API 不稳定，仅适用于实验和原型开发，不建议生产使用。

---
## 4. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 207,136
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: 这是 Matt Pocock 开源的一套面向真实工程场景的 AI 编码代理技能集，源自其日常使用的 `.agents` 目录，旨在解决 AI 编码代理常见问题，而非“vibe coding”。

**核心功能**:
- **技能安装与管理**：支持通过 Claude Code 插件（自动更新）或 `npx skills@latest add` 命令安装，可灵活选择技能并适配 Codex 等代理，也可作为普通文件复制进项目自由修改。
- **一键初始化**：运行 `/setup-matt-pocock-skills` 可配置问题追踪器（GitHub/Linear/本地文件）、工单标签和文档保存位置。
- **需求对齐（Grilling）**：提供 `/grill-me` 和 `/grill-with-docs` 技能，通过向代理提问详细问题来消除沟通偏差，确保代理真正理解需求后再动手。
- **组合式技能设计**：技能体积小巧、易于修改和组合，可适配任意模型，基于数十年工程经验沉淀。

**技术亮点**: 采用 Shell 编写，支持双模式分发（托管只读插件 vs 可编辑文件）；内置架构决策记录（ADR，如 `0002-ship-as-a-claude-code-plugin.md`）；通过 `skills.sh` 生态实现跨代理兼容。

---
## 5. [goauthentik/authentik](https://github.com/goauthentik/authentik)
- **语言**: Python
- **Stars**: 23,143
- **简介**: The authentication glue you need.

### AI 总结
**简介**: authentik 是一个开源的身份提供者（IdP），为现代 SSO 提供认证粘合层，支持多种协议，适合从个人实验室到大型生产集群的自托管部署。

**核心功能**:
- 支持 SAML、OAuth2/OIDC、LDAP、RADIUS 等多种认证协议
- 提供企业级身份管理，可替代 Okta、Auth0、Entra ID 等商业 IdP 产品
- 支持多种部署方式：Docker Compose、Kubernetes (Helm Chart)、AWS CloudFormation、DigitalOcean Marketplace
- 提供明亮/暗色主题的管理界面和应用门户

**技术亮点**: 基于 Python 开发，采用模块化架构（core、outpost、web 三部分独立构建），具备完整的 CI/CD 流程和代码覆盖率监控，支持多语言翻译（Transifex），采用 MIT 开源协议（企业版功能另有 EE License）。

---
## 6. [huangruiteng/loopx](https://github.com/huangruiteng/loopx)
- **语言**: Python
- **Stars**: 2,899
- **简介**: Lightweight loop engineering state kernel for long-running AI agent teams. Agent-loop agnostic across Codex, Claude Code, and other coding agents, with durable goals, quota-aware auto-wake, executable todos, evidence logs, and verifiable handoffs.

### AI 总结
**简介**: LoopX 是一个轻量级的循环工程状态内核，为长时间运行的 AI Agent 团队提供本地控制平面，让 Codex、Claude Code 等编码代理在受控回合中稳定执行目标、门禁、待办和交接。

**核心功能**:
- **持久化状态管理**: 统一管理目标、门禁、待办事项、范围、证据和配额，确保跨回合、跨工具、跨代理的工作可审查、可重启、易交接
- **代理无关设计**: 不替代代理运行时，与 Codex、Claude Code、Cursor 或自定义运行时兼容，注册代理作为对等节点协作
- **配额感知自动唤醒**: 根据配额决定下一个执行周期，避免无意义持续消耗资源
- **可执行待办与证据日志**: 每个回合后写入证据、交接信息和下一个待办，保持进度可追溯
- **可验证交接机制**: 通过声明、租约、任务边界和能力类型化决定谁执行下一步，无需持久领导者身份
- **人工判断门控**: 需要人类决策时提出具体问题并等待，安全回退时仅运行有界代理切片

**技术亮点**: 采用 Python 3.11+ 实现，本地优先架构；核心模型类似于"代理原生看板"，卡片携带身份、权限、证据和延续信息，移动操作通过验证算子（claim、gate、monitor、writeback）执行；状态层是唯一事实来源，看板仅为投影视图。

---
## 7. [google/guava](https://github.com/google/guava)
- **语言**: Java
- **Stars**: 51,644
- **简介**: Google core libraries for Java

### AI 总结
**简介**: Guava 是 Google 提供的 Java 核心库，包含丰富的集合类型、不可变集合、图库以及并发、I/O、哈希、原生类型和字符串处理等工具，被 Google 内部及众多外部公司广泛使用。

**核心功能**:
- 新增集合类型：提供 multimap 和 multiset 等扩展集合
- 不可变集合：支持创建不可修改的集合实例
- 图库：提供图数据结构的实现和算法
- 工具类库：涵盖并发、I/O、哈希、原生类型、字符串处理等实用工具

**技术亮点**:
- 双版本支持：提供 JRE 版（JDK 1.8+）和 Android 版两种 flavor，通过 Maven 版本号区分（如 `33.6.0-jre` 和 `33.6.0-android`）
- API 稳定性保障：非 `@Beta` API 保证长期二进制兼容，`@Beta` API 可能变更但提供 Guava Beta Checker 工具检测
- 支持快照版本：通过 `999.0.0-HEAD-jre-SNAPSHOT` 获取 master 分支最新构建

---
## 8. [TapXWorld/ChinaTextbook](https://github.com/TapXWorld/ChinaTextbook)
- **语言**: Roff
- **Stars**: 77,143
- **简介**: 所有小初高、大学PDF教材。

### AI 总结
**简介**: 一个开源的中国中小学及大学PDF教材合集，旨在免费提供教育资源，促进教育公平。
**核心功能**:
- 提供小学至高中各年级的数学（人教版）教材PDF下载，按年级和学期分类
- 覆盖小初高及大学阶段的教材资源
- 面向国内用户及海外华人家庭，便于获取国内教育内容
**技术亮点**: 基于GitHub仓库直接托管PDF文件，以Markdown链接形式组织目录，便于浏览和下载。

---
## 9. [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)
- **语言**: Python
- **Stars**: 186,027
- **简介**: AutoGPT is the vision of accessible AI for everyone, to use and to build on. Our mission is to provide the tools, so that you can focus on what matters.

### AI 总结
**简介**: AutoGPT 是一个开源平台，允许用户用自然语言描述任务，构建、部署并运行能完成完整工作流的 AI 代理。

**核心功能**:
- **AutoPilot**: 用自然语言描述任务，自动将对话转化为可运行的 AI 代理
- **Agents 仪表盘**: 集中查看所有代理的运行状态、成本和待处理操作
- **Marketplace 市场**: 浏览社区分享的现成代理，一键添加到自己的库中并自定义
- **Build 可视化构建器**: 通过拖拽、连接、分支和检查模块，精确控制代理的每一步流程
- **灵活运行方式**: 支持按需运行、定时调度或由触发器启动代理

**技术亮点**: 基于 Python 构建，提供托管平台（AutoGPT Platform）和自托管（Self-host）两种部署方式；平台管理基础设施、模型访问、凭证和更新，用户只需专注于代理的实际工作；拥有 185,000+ GitHub Stars，并获得 OpenAI 创始成员 Andrej Karpathy 等行业领袖的推荐。

---
## 10. [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)
- **语言**: Python
- **Stars**: 29,045
- **简介**: Local-first code intelligence graph for MCP and CLI. Builds a persistent map of your codebase so AI coding tools read only what matters, with benchmarked context reductions on reviews and large-repo workflows.

### AI 总结
**简介**: 一个本地优先的代码智能图谱工具，通过 Tree-sitter 构建代码结构地图并接入 MCP/CLI，让 AI 编程工具只读取必要的代码上下文，显著减少 token 消耗。

**核心功能**:
- 一键安装配置：自动检测并配置 Codex、Claude Code、Cursor、Gemini CLI 等 15+ 主流 AI 编程工具
- 增量代码追踪：基于 Tree-sitter 构建代码结构图，持久化存储代码库映射
- 精准上下文提供：通过 MCP 协议为 AI 助手提供精确的代码上下文，避免重复读取整个代码库
- 多平台支持：支持 CLI 命令行操作和 GitHub Action 集成
- 基准测试验证：在代码审查和大型仓库工作流中实现可量化的上下文缩减（如审查 flask 代码库时 token 消耗减少 71 倍）

**技术亮点**: 基于 Tree-sitter 语法解析器构建代码结构图谱，支持 Python 3.10+，采用 MCP（Model Context Protocol）标准协议，提供 pip/pipx 安装方式，支持增量更新和平台原生 hooks/skills 注入。

---
