---
tags:
  - github-trending
  - daily
date: 2026-10-18
created: 2026-10-18T01:55:43.065Z
---

# 2026-10-18 GitHub Trending Top 10

## 1. [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- **语言**: Python
- **Stars**: 41,810
- **简介**: Official, Anthropic-managed directory of high quality Claude Code Plugins.

### AI 总结
**简介**: Anthropic 官方维护的 Claude Code 高质量插件目录，汇集内部与第三方插件，支持通过 Claude Code 插件系统直接安装。

**核心功能**:
- 插件市场：提供 `/plugins`（Anthropic 内部插件）和 `/external_plugins`（第三方及社区插件）两类目录
- 一键安装：通过 `/plugin install {plugin-name}@claude-plugins-official` 或 `/plugin > Discover` 浏览安装
- 标准化插件结构：统一包含 `plugin.json` 元数据，以及可选的 MCP 配置、斜杠命令、Agent、Skill 定义
- 插件名不可变机制：通过 `renames` 映射表实现旧插件名的透明迁移，避免用户安装失效
- Skill 捆绑插件：支持 `strict: false` 模式，直接从源仓库声明多个 `SKILL.md` 技能目录
- 外部插件提交：第三方合作伙伴可通过提交表单申请收录，需满足质量与安全标准

**技术亮点**: 采用基于 JSON 的插件清单（`plugin.json`、`.mcp.json`、`marketplace.json`）驱动，支持 MCP 服务器集成与 Skill 注册（`<plugin-name>:<skill-name>` 命名空间）；项目以 Python 实现，插件源支持 git-subdir 方式引用并锁定 commit SHA，保证可复现性。

---
## 2. [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)
- **语言**: Python
- **Stars**: 50,476
- **简介**: The job search that runs on your machine. AI job application framework built on Claude Code: evaluate postings, tailor CVs, write cover letters, prep interviews. Fork it and own it.

### AI 总结
**简介**: 一个基于 Claude Code 构建的 AI 求职申请框架，可在本地运行，帮助用户完成职位评估、简历定制、求职信撰写和面试准备。

**核心功能**:
- `/setup`：填写个人资料，生成结构化档案文件
- `/scrape`：搜索招聘门户（主要面向丹麦市场，如 Jobindex、Jobnet、Akademikernes Jobbank），展示带匹配评分的职位列表
- `/apply <url>`：评估职位匹配度并评分，用 LaTeX 生成定制化简历与求职信，经 Reviewer agent 评审后迭代修订
- `/interview`：辅助面试准备
- 内置职业指导最佳实践：结构化评估标准、前瞻性求职信框架、可选薪资对标

**技术亮点**:
- 基于 Claude Code CLI 的 agent 工作流，采用 drafter-reviewer 双角色流水线
- 核心工作流与语言、国家无关，招聘门户搜索技能可按本地市场替换
- 使用 LaTeX 排版（简历用 `lualatex`，求职信用 `xelatex`）
- 技术栈：Python 3.10+、Bun（招聘搜索 CLI 工具）、LaTeX 发行版
- 支持 ATS 可解析性检查（可选 `pypdf`）

---
## 3. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 282,547
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个面向 AI 编码代理的"性能优化操作系统"，为 Claude Code、Codex、Opencode、Cursor 等代理工具提供技能、本能、记忆、安全与研究优先的开发能力。

**核心功能**:
- **技能与本能系统**：为代理提供可复用的技能模块和"本能"式行为，提升任务执行的一致性与效率
- **记忆机制**：让代理在跨会话、跨任务中保留上下文与经验
- **安全防护（AgentShield）**：通过 `ecc-agentshield` 包为代理运行提供安全层
- **研究优先开发**：强调先调研再动手的开发流程，减少盲目生成
- **多代理兼容**：同一套 `ecc@ecc` 插件可接入 Claude Code、Codex、Opencode、Cursor 等多种代理宿主
- **多语言文档**：提供简体中文、日语、韩语、德语、西班牙语等 16 种语言 README

**技术亮点**:
- 以 JavaScript 为主，辅以 Shell、TypeScript、Python、Go、Java、Perl 等多语言组件
- 通过 npm 包（`ecc-universal`、`ecc-agentshield`）、GitHub App 和原生插件命令（`ecc@ecc`）多渠道分发
- 采用 MIT 开源协议，配套 Discord 社区与官方站点 ecc.tools
- 官方明确警示仅从可信渠道安装，防范第三方镜像的恶意篡改风险

---
## 4. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 54,083
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: CLI-Anything 是香港大学数据科学实验室（HKUDS）开源的项目，旨在为各类软件自动生成 CLI 封装，让 AI Agent 能够直接调用和操作任意软件，实现“所有软件 Agent 原生”。

**核心功能**:
- **CLI 自动生成**：为任意软件生成命令行接口（harness），使 Pi、OpenClaw、Cursor、Claude Code 等 AI Agent 可以直接操作该软件
- **CLI-Hub 社区中心**：通过 `pip install cli-anything-hub` 安装后，可用 `cli-hub install <name>` 浏览、安装和管理社区构建的 CLI，并支持通过 PR 贡献自己的 CLI
- **真实场景演示**：提供 18 个应用示例，AI Agent 借助生成的 CLI 及预览、实时预览、轨迹循环等机制产出 CAD 构建、3D 场景、图表、游戏、字幕等真实成果
- **社区共建机制**：支持贡献者报名、CLI 需求愿望清单（wishlist）提交，以及 Hermes 编排技能等扩展能力

**技术亮点**: 基于 Python（≥3.10）开发，使用 Click（≥8.0）构建命令行界面，测试采用 pytest 且 2461 项测试全部通过，覆盖单元与端到端测试；输出同时支持 JSON 与人类可读格式，便于 Agent 解析和人工查看；采用 Apache 2.0 许可证，并提供 arXiv 技术报告。

---
## 5. [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- **语言**: Python
- **Stars**: 52,274
- **简介**: Turn any AI agent into an AI Scientist. The #1 Agent Skills library for science, used by 250,000+ scientists worldwide. 177 ready-to-use validated skills plus 100+ scientific databases covering biology, chemistry, medicine, and drug discovery. Compatible with Cursor, Claude Code, Codex, Pi, Antigravity, and the open Agent Skills standard.

### AI 总结
**简介**: K-Dense 推出的开源科研技能库，为 AI Agent 提供 177 个经过验证的科学技能与 100+ 科学数据库接入能力，可将任意 AI Agent 转变为“AI 科学家”。

**核心功能**:
- 覆盖生物学、化学、医学、药物发现、物理、工程、地球科学、数据分析与科学传播等领域的 177 个即用型技能，每个技能包含特定包、数据源或工作流的使用指南及科学规范与验证检查
- 集成 100+ 科学数据库，支持真实科研工作流（如文献检索、数据处理、实验分析）
- 兼容 Cursor、Claude Code、Codex、Google Antigravity 等宿主，并遵循开放的 Agent Skills 标准与 Agent Plugins 标准，可作为单一插件整体加载
- 配套开源桌面 AI 协作科学家 K-Dense BYOK，支持自带 API Key、40+ 模型选择与本地数据存储

**技术亮点**: 基于 Python 实现，采用 Agent Skills 开放标准与 Agent Plugins 打包规范（plugin.json + skills/），具备可移植性；配套 GitHub Actions 安全扫描与技能测试流水线，并有 arXiv 论文（2609.00065）作为方法论支撑，MIT 协议开源。

---
## 6. [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory)
- **语言**: Rust
- **Stars**: 9,938
- **简介**: Solution for long term memory for agent coding CLIs and to facilitate handoff between different agent vendors

### AI 总结
**简介**: ai-memory 是一个用 Rust 编写的长期记忆解决方案，让 AI 编码代理在不同工具、项目和机器之间无缝交接工作，无需重复解释上下文。

**核心功能**:
- **跨代理记忆共享**：支持 Claude Code、Codex、Cursor、Gemini CLI 等二十多种代理工具共享同一份记忆，切换工具时自动生成带类型的交接记录（记录进度、失败方案和待解决问题）
- **跨项目与跨机器延续**：用户的工作习惯画像（包管理器、测试布局、架构偏好）自动应用到新仓库；记忆存储在自托管服务器上，桌面端未完成的项目可在笔记本上继续
- **团队协作**：多人共享同一服务器时，项目知识全员可检索，个人交接保持私密，内置多用户认证、归属追踪和审计日志
- **纯 Markdown 存储**：记忆以 git 管理的 `.md` 文件为唯一真实来源，可用 grep、Obsidian 或手动编辑，数据库仅为可重建的派生索引
- **静默自动捕获**：通过生命周期钩子记录提示词、工具调用和会话边界，经隐私边界清洗后由服务器整理为可读页面，默认零 LLM 调用
- **无 LLM 的记忆老化机制**：按可调周期衰减记忆，常用记忆衰减更慢；冷记忆可压缩为持久事实而非删除，近似重复项合并，潜在矛盾标记，全程无 API 调用
- **可选的“做梦”功能**：配置 LLM 后，空闲时后台将冷笔记重写为连贯页面，源版本始终保留，默认关闭

**技术亮点**: 基于 Rust（1.95+）构建；采用 git 支持的 Markdown wiki 作为存储层，数据库为可随时重建的派生索引，无需向量库；交接采用带所有者、一次性认领的类型化协议；隐私清洗在类型化边界完成，远程服务器仅接收代理和会话标识，不接触本地转录内容；默认路径零 LLM 依赖，所有内容修改类功能（压缩、去重、分层衰减曲线）默认关闭，需手动开启。

---
## 7. [android/skills](https://github.com/android/skills)
- **语言**: Kotlin
- **Stars**: 8,438
- **简介**: 

### AI 总结
**简介**: Android 官方推出的 AI 优化模块化技能库，通过标准化 Markdown 指令文件帮助 AI 代理更好地理解和执行 Android 开发最佳实践。

**核心功能**:
- 提供遵循开放标准（agent skills）的 SKILL.md 技能文件，为 LLM 提供特定领域和工作流的技术规范
- 聚焦 LLM 表现较弱的用例和工作流，而非基础 Jetpack Compose 等已成熟领域
- 支持通过 Android CLI 安装单个或全部技能（`android skills add`），并可指定目标代理和项目路径
- 支持批量或单个技能更新（`android skills update`）
- 可作为代理插件安装（支持 Claude Code、Codex 等）
- 代理会根据任务自动激活相关技能

**技术亮点**: 基于 Kotlin；采用开放标准 agent skills 的 Markdown 规范；与 Gemini、Antigravity、Android Studio、Android CLI 等工具链集成；遵循 Apache License 2.0 开源协议。

---
## 8. [stablyai/orca](https://github.com/stablyai/orca)
- **语言**: TypeScript
- **Stars**: 95,456
- **简介**: Orca is the place for working with a fleet of agents (e.g. Grok Bot, Claude Code). Run any coding agent with your own subscription. Available on desktop, mobile and remote runtime.

### AI 总结
**简介**: Orca 是一个用 TypeScript 开发的 AI 代理编排器，让开发者能在桌面、移动端和远程运行时并行运行 Codex、Claude Code、OpenCode、Pi 等多种编码代理，并使用自己的订阅。

**核心功能**:
- **并行 Worktree**：将同一提示分发给多个代理，每个代理运行在独立的 git worktree 中，便于对比结果并合并最优方案
- **移动端伴侣应用**：通过 iOS/Android 应用远程监控和操控代理，代理完成时收到通知并发送后续指令
- **终端分屏**：Ghostty 级终端，支持 WebGL 渲染、无限分屏，且重启后保留回滚缓冲
- **设计模式**：在真实 Chromium 窗口中点击任意 UI 元素，将其 HTML、CSS 和截图直接注入代理提示词
- **GitHub 与 Linear 原生集成**：在应用内浏览 PR、Issue 和项目看板，从任务直接打开 worktree 并评审
- **SSH Worktree**：在远程高性能机器上运行代理，支持完整文件编辑、git、终端、自动重连和端口转发

**技术亮点**: 基于 TypeScript 构建，支持 macOS、Windows、Linux 多平台；采用 git worktree 隔离机制实现多代理并行；终端基于 Ghostty 级 WebGL 渲染；MIT 开源协议。

---
## 9. [anthropics/claude-code](https://github.com/anthropics/claude-code)
- **语言**: TypeScript
- **Stars**: 151,781
- **简介**: Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands.

### AI 总结
**简介**: Claude Code 是 Anthropic 推出的终端智能编码工具，能理解代码库并通过自然语言命令加速日常开发任务。

**核心功能**:
- 执行常规编码任务、解释复杂代码
- 处理 Git 工作流
- 支持终端、IDE 以及 GitHub 中 @claude 调用
- 提供可扩展的插件系统（自定义命令与 agent）
- 内置 `/bug` 命令上报问题

**技术亮点**: 基于 TypeScript 开发，要求 Node.js 18+；安装方式支持脚本一键安装（macOS/Linux/Windows）、Homebrew、WinGet，npm 安装已弃用；注重数据隐私保护（限制敏感信息保留期、禁止将反馈用于模型训练）。

---
## 10. [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio)
- **语言**: Python
- **Stars**: 73,449
- **简介**: VoiceStudio is the open-source, fully-local ElevenLabs alternative — voice cloning, voice design, video dubbing, dictation, transcription & audiobook creation in 646 languages.

### AI 总结
**简介**: VoiceStudio 是一个开源、完全本地运行的 ElevenLabs 替代方案，支持 646 种语言的语音克隆、语音设计、视频配音、听写、转写和有声书制作。

**核心功能**:
- 语音克隆与自定义语音设计
- 视频配音（带时间轴的语音合成）
- 听写（悬浮小组件）与音频转写
- 故事、有声书及批量任务生成
- 本地 API 与 MCP 接口，可供智能体调用
- 可复用配方（recipes）与监听文件夹自动化

**技术亮点**:
- 基于 Python 后端与 Electron 桌面应用架构
- 默认引擎为 k2-fsa/OmniVoice，支持多引擎切换
- 完全本地运行，支持 NVIDIA CUDA、Apple Silicon Metal（MPS）加速，无独显时可用 CPU 运行
- 提供跨平台安装（macOS/Linux 一键脚本、Windows PowerShell、Docker），支持 macOS `.dmg`、Windows `.exe`、Linux `.AppImage`/`.deb`
- 采用 AGPL-3.0 开源协议

---
