---
tags:
  - github-trending
  - daily
date: 2026-10-17
created: 2026-10-17T01:55:42.509Z
---

# 2026-10-17 GitHub Trending Top 10

## 1. [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- **语言**: Python
- **Stars**: 40,631
- **简介**: Official, Anthropic-managed directory of high quality Claude Code Plugins.

### AI 总结
**简介**: Anthropic 官方维护的 Claude Code 高质量插件目录，汇集内部与第三方插件，支持通过 Claude Code 插件系统直接安装。

**核心功能**:
- 提供 `/plugins`（Anthropic 内部插件）与 `/external_plugins`（第三方及社区插件）两类插件目录
- 支持通过 `/plugin install {plugin-name}@claude-plugins-official` 或 `/plugin > Discover` 浏览安装
- 定义统一的插件结构规范（plugin.json、.mcp.json、commands、agents、skills 等）
- 支持技能捆绑插件（Skill-bundle），无需 plugin.json 即可通过 `strict: false` 与 `skills` 数组声明技能
- 通过 `renames` 映射实现插件重命名的自动迁移，避免已安装用户报错

**技术亮点**:
- 插件名称作为不可变 slug，重命名需通过 `.claude-plugin/marketplace.json` 中的 `renames` 映射透明迁移
- 支持 git-subdir 源与显式 skills 路径声明，可跨多级目录精选技能子集
- 每个技能以 `<plugin-name>:<skill-name>` 形式注册
- 提供官方文档与提交表单，第三方插件需满足质量与安全标准方可上架

---
## 2. [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- **语言**: Python
- **Stars**: 51,540
- **简介**: Turn any AI agent into an AI Scientist. The #1 Agent Skills library for science, used by 250,000+ scientists worldwide. 177 ready-to-use validated skills plus 100+ scientific databases covering biology, chemistry, medicine, and drug discovery. Compatible with Cursor, Claude Code, Codex, Pi, Antigravity, and the open Agent Skills standard.

### AI 总结
**简介**: K-Dense 推出的科学领域 Agent Skills 库，提供 177 个经过验证的开箱即用技能和 100+ 科学数据库，可将任意 AI Agent 转变为 AI 科学家，已被全球 25 万+ 科研人员使用。

**核心功能**:
- **177 个科学技能**：覆盖生物学、化学、医学、物理学、工程学、地球科学、数据分析与科学传播，每个技能针对特定软件包、数据源或工作流提供科学规范与验证检查
- **100+ 科学数据库集成**：涵盖生物、化学、医学与药物发现领域
- **多宿主兼容**：支持 Cursor、Claude Code、Codex、Google Antigravity 等兼容 Agent Skills 标准的客户端
- **配套工具 K-Dense BYOK**：免费开源桌面端 AI 科研助手，支持自带 API Key、40+ 模型选择、本地数据存储与云端扩展

**技术亮点**:
- 遵循开放的 Agent Skills 标准（agentskills.io），同时作为可移植的 Agent Plugins 包（`plugin.json` + `skills/`）分发
- 基于 Python 实现，版本 v2.72.0，采用 MIT 许可证
- 配套学术论文发表于 arXiv（2609.00065），具备完整的 CI 安全扫描与技能测试流程

---
## 3. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 281,551
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个面向 AI 编码代理（Agent Harness）的性能优化系统，为 Claude Code、Codex、Opencode、Cursor 等工具提供技能、本能、记忆、安全与研究优先的开发能力。

**核心功能**:
- **技能与本能（Skills & Instincts）**：为编码代理注入可复用的技能模块与行为本能，提升任务执行效率。
- **记忆系统（Memory）**：为代理提供持久化记忆能力，支持跨会话的上下文保持。
- **安全防护（Security）**：通过 `ecc-agentshield` 等组件保障代理运行安全。
- **研究优先开发（Research-first Development）**：强调先调研再动手的开发范式。
- **多平台支持**：兼容 Claude Code、Codex、Opencode、Cursor 等多种代理环境，并提供 `ecc-universal` 通用包。
- **便捷安装**：支持 Claude Code 引导式安装与原生插件命令，通过 `ecc@ecc` 插件统一接入。

**技术亮点**:
- 以 JavaScript 为主，同时涉及 Shell、TypeScript、Python、Go、Java、Perl 等多语言生态。
- 提供 npm 包（`ecc-universal`、`ecc-agentshield`）、GitHub App 及插件等多种分发形式。
- 采用 MIT 开源许可，拥有活跃的 Discord 社区与多语言文档支持（含简体中文等 16 种语言）。

---
## 4. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 53,529
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: CLI-Anything 是香港大学数据科学实验室（HKUDS）推出的开源项目，旨在通过自动生成命令行接口（CLI），让所有软件都能被 AI Agent 原生调用，弥合 AI 智能体与现有软件生态之间的鸿沟。

**核心功能**:
- **CLI 自动生成**：为任意软件快速生成 agent-ready 的命令行接口，使其可被 Pi、OpenClaw、nanobot、Cursor、Claude Code 等 AI Agent 直接调用
- **CLI-Hub 社区中心**：通过 `pip install cli-anything-hub` 安装后，使用 `cli-hub install <name>` 浏览、安装和管理社区构建的 CLI 工具，支持一键提交 PR 贡献自己的 CLI
- **真实场景演示**：展示 AI Agent 借助生成的 CLI 完成 CAD 建模、3D 场景搭建、图表绘制、游戏玩法、字幕生成等实际任务
- **预览与轨迹循环**：支持 preview、live preview 和 trajectory loops，让 Agent 在迭代中产出真实可用的制品

**技术亮点**:
- 基于 Python（≥3.10）构建，使用 Click（≥8.0）实现命令行框架
- 测试覆盖完善，2,461 项测试全部通过，涵盖单元测试与端到端测试，覆盖率 100%
- 输出同时支持 JSON 与人类可读格式，便于 Agent 解析与人工调试
- 采用 Apache 2.0 开源协议，配有 arXiv 技术报告（arXiv:2606.03854）
- 活跃的社区生态，支持贡献者注册与 CLI 愿望清单提交，并持续收录新软件适配（如 ArcGIS Pro、Hermes skill 等）

---
## 5. [mksglu/context-mode](https://github.com/mksglu/context-mode)
- **语言**: TypeScript
- **Stars**: 30,249
- **简介**: Context window optimization for AI coding agents. Sandboxes tool output (98% reduction), persists session memory, and enforces routing across 17 platforms via MCP + hooks.

### AI 总结
**简介**: Context Mode 是一款面向 AI 编程代理的上下文窗口优化工具，通过沙箱化工具输出、持久化会话记忆和跨平台路由，大幅降低上下文消耗。

**核心功能**:
- **上下文节省**：沙箱化工具输出，将原始数据（如 Playwright 快照、GitHub issues、访问日志）阻隔在上下文窗口之外，实现 98% 的体积缩减（315 KB → 5.4 KB）
- **会话连续性**：通过 SQLite 追踪文件编辑、git 操作、任务、错误和用户决策；会话压缩时利用 FTS5 索引和 BM25 搜索仅检索相关内容，模型可无缝续接；未使用 `--continue` 时旧会话数据立即清除
- **用代码思考**：引导 LLM 以编程方式处理任务，减少冗余输出和客套话，从输入输出两端节省 token
- **跨平台路由**：通过 MCP + hooks 在 17 个平台上强制执行路由策略

**技术亮点**: 基于 TypeScript 构建的 MCP 服务器；采用 SQLite + FTS5 全文索引 + BM25 检索实现高效会话记忆管理；已获 Hacker News 头版第一名（570+ 分），被 Microsoft、Google、Meta、Amazon、NVIDIA 等团队使用；采用 ELv2 许可证。

---
## 6. [ruvnet/ruflo](https://github.com/ruvnet/ruflo)
- **语言**: TypeScript
- **Stars**: 75,652
- **简介**: 🌊 The original agent harness. Deploy intelligent multi-player swarms, coordinate autonomous workflows, and build conversational AI systems. Features adaptive memory, self-learning intelligence, federation, vector RAG integration, and native Claude Code / Codex / Hermes and many more Integrated

### AI 总结
**简介**: Ruflo 是面向 Claude Code 和 Codex 的智能体元框架（agent meta-harness），为 AI 代理提供工具、记忆、循环、沙箱与控制能力，使其从单纯运行升级为协同工作。

**核心功能**:
- **多智能体集群**：100+ 专用代理可自组织成 swarm，支持多玩家协作与自主工作流编排
- **自适应记忆与自学习**：内置持久上下文、向量 RAG 集成与反馈学习机制
- **联邦通信**：支持跨机器的联邦式通信
- **企业级安全护栏**：提供路由与策略执行（Mods）
- **多种接入方式**：Claude Code 插件（core/console/mods）、MCP 服务器（NPX 启动）、独立终端 UI（TUI）
- **可选 ruOS 桌面**：通过 MCP 连接 ChatGPT 或 Claude

**技术亮点**:
- 基于 TypeScript 开发，通过 NPX（`npx ruflo@latest`）快速初始化
- 采用 MCP（Model Context Protocol）协议与 Claude Code / Codex 等客户端集成
- 架构分层清晰：Core 提供基础工具，Console 提供代理驾驶舱，Mods 负责路由与策略
- 配套 RuVector 实现本地向量搜索、持久上下文、图关系与反馈学习
- 提供 14 章《RuFlo Explained》指南，覆盖从基础概念到记忆、代理团队、插件、成本与验证的完整路径

---
## 7. [android/skills](https://github.com/android/skills)
- **语言**: Kotlin
- **Stars**: 8,093
- **简介**: 

### AI 总结
**简介**: Android 官方推出的 AI 优化模块化技能库，通过标准化 Markdown 文件帮助 AI 代理更好地理解和执行 Android 开发任务。

**核心功能**:
- 提供针对 LLM 表现薄弱环节的专用技能（SKILL.md），补充 Jetpack Compose 最佳实践等已有优势领域之外的开发知识
- 支持通过 Android CLI 安装单个技能（如 `r8-analyzer`）或批量安装全部技能（`--all`），并可指定目标代理和项目路径
- 支持作为 Claude Code 和 Codex 的插件安装（`/plugin install` 或 `codex plugin marketplace add`）
- 支持技能更新（`android skills update --all` 或指定技能名）
- 代理会根据任务自动激活相关技能，无需手动指定

**技术亮点**:
- 遵循 [agentskills.io](https://agentskills.io/home) 开放标准，以 Markdown 文件作为技术规范载体
- 基于 Kotlin 开发，与 Android 生态深度集成
- 聚焦 LLM 评估中表现不足的用例和工作流，而非重复 LLM 已擅长的领域
- 使用 Apache License 2.0 开源许可

---
## 8. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 300,696
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，通过可组合的技能和自动触发机制，让 AI 编码助手先理解需求、再规划实现、最后自主执行开发任务。

**核心功能**:
- **需求澄清与规格设计**: 智能体不会直接写代码，而是先引导用户明确真实目标，逐步梳理出规格说明，并以易于阅读的片段形式呈现给用户确认。
- **实现计划生成**: 在用户确认设计后，生成清晰到"初级工程师也能照做"的实施计划，强调红/绿 TDD、YAGNI 和 DRY 原则。
- **子智能体驱动开发**: 用户确认后启动 subagent-driven-development 流程，各智能体逐项完成工程任务，自动检查与审查工作成果，可持续自主运行数小时而不偏离计划。
- **自动技能触发**: 技能自动激活，用户无需额外操作即可让编码智能体获得 Superpowers 能力。
- **多平台支持**: 支持 Claude Code、Codex、Cursor、Gemini CLI、GitHub Copilot CLI、Qwen Code、Kimi Code、Devin CLI 等十余种编码智能体平台。

**技术亮点**:
- 基于可组合技能（composable skills）构建的方法论框架，语言以 Shell 为主。
- 采用子智能体驱动开发架构，实现任务级自主执行与审查闭环。
- 支持通过官方或自建插件市场（如 Claude 插件市场）一键安装，覆盖主流 AI 编程工具生态。
- 提供商业支持渠道，适用于企业级使用场景。

---
## 9. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 11,980
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，为开发者工具、框架和 SaaS 产品提供标准化插件，每个插件以独立目录形式组织并配有 `.cursor-plugin/plugin.json` 清单文件。

**核心功能**:
- **开发工具类插件**: 涵盖代码审查（Thermos、PR Review Canvas）、文档渲染（Docs Canvas）、并行任务编排（Orchestrate）、Agent 兼容性扫描、CLI 设计模式、插件脚手架（Create Plugin）等
- **学习与工作流插件**: 包括教学技能映射（Teaching）、增量学习记忆更新（Continual Learning）、团队 CI/代码审查工作流（Cursor Team Kit）、迭代式 AI 循环（Ralph Loop）等
- **第三方集成插件**: 支持 Gmail、Google Drive/Calendar/Docs/Sheets/Slides、Salesforce、Gong、Playwright、GitHub 等生产力与集成工具
- **SDK 与 API 支持**: 提供 TypeScript SDK 用于构建应用和自动化，以及基于 Cursor Origin API 的开发技能

**技术亮点**: 采用 TypeScript 开发，插件架构标准化——每个插件为仓库根目录下的独立目录，通过统一的 `.cursor-plugin/plugin.json` 清单进行配置，便于扩展和分发。

---
## 10. [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio)
- **语言**: Python
- **Stars**: 71,298
- **简介**: VoiceStudio is the open-source, fully-local ElevenLabs alternative — voice cloning, voice design, video dubbing, dictation, transcription & audiobook creation in 646 languages.

### AI 总结
**简介**: VoiceStudio 是一个完全本地运行的开源 ElevenLabs 替代方案，支持 646 种语言的语音克隆、语音设计、视频配音、听写、转录和有声书制作。

**核心功能**:
- **语音克隆与设计**：克隆已有声音或通过描述设计全新声音
- **视频配音**：为视频添加时间对齐的配音
- **听写与转录**：通过浮动小组件进行语音听写和音频转录
- **有声书与批量任务**：支持故事、有声书制作及批处理作业
- **本地 API 与 MCP**：为智能体提供本地 API 和 MCP 接口
- **可复用配方与监听文件夹**：支持工作流自动化

**技术亮点**:
- 基于 Python 开发，默认使用 k2-fsa/OmniVoice 引擎，支持切换其他引擎
- 提供 Electron 桌面应用，支持 macOS、Windows、Linux 及 Docker 部署
- 硬件加速：NVIDIA GPU（CUDA）、Apple Silicon（Metal/MPS），无独显时可用 CPU 运行
- 所有本地工作流在用户自有硬件上运行，远程服务为可选，使用分析需用户同意
- 采用 AGPL-3.0 开源协议

---
