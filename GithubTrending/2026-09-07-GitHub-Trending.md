---
tags:
  - github-trending
  - daily
date: 2026-09-07
created: 2026-09-07T01:55:44.111Z
---

# 2026-09-07 GitHub Trending Top 10

## 1. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 251,421
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个面向 AI 编程代理（如 Claude Code、Codex、Opencode、Cursor 等）的性能优化与增强系统，提供技能、直觉、记忆、安全与研究优先的开发能力。

**核心功能**:
- **代理增强**: 为多种 AI 编程代理提供统一的技能、直觉与记忆扩展能力
- **安全防护**: 通过 AgentShield 等组件增强代理操作的安全性
- **一键安装**: 通过 `npx ecc-universal setup` 提供规范化引导式安装
- **多平台支持**: 兼容 Claude Code、Codex、Opencode、Cursor 等主流代理工具
- **生态集成**: 提供 GitHub App、npm 包、插件系统等多种集成方式
- **多语言文档**: 支持 13 种语言的文档与社区支持

**技术亮点**: 基于 JavaScript/TypeScript 构建，支持 Shell、Python、Go、Java、Perl 等多语言环境；采用插件化架构（`ecc@ecc` 插件作用域）；通过 npm 包（`ecc-universal`、`ecc-agentshield`）分发；提供官方 GitHub App 与网站生态；遵循 MIT 开源协议。

---
## 2. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 254,673
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: 这是 Matt Pocock 开源的一套真实工程实践 AI Agent Skills，帮助开发者在使用 Claude Code、Codex 等编码代理时提升工程效率，而非仅仅“氛围编程”。

**核心功能**:
- **对齐需求**: 提供 `/grill-me` 和 `/grill-with-docs` 技能，通过“拷问式”问答让代理在动手前充分理解需求，避免误解
- **流程自定义**: 通过 `/setup-matt-pocock-skills` 一次性配置，支持选择问题跟踪器（GitHub/Linear/本地文件）和标签体系
- **灵活安装**: 支持 Claude Code 插件（自动更新）或 `npx skills` 拷贝到本地自由修改
- **可组合技能集**: 技能设计小巧、易扩展、可组合，适配任何 AI 模型

**技术亮点**: 采用 Shell 脚本实现，基于数十年工程经验沉淀；提供两种分发哲学（托管订阅式插件 vs 本地可编辑文件），支持多代理（Claude Code、Codex 等）安装，并附带架构决策记录（ADR）文档。

---
## 3. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 32,434
- **简介**: 38 editorial diagram types for Claude Code, Codex, and Pi. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个为 AI 编程助手（Claude Code、Codex 等）提供 39 种高质量编辑级图表类型的技能库，输出自包含的 HTML + SVG，告别千篇一律的圆角框和 Mermaid 风格。

**核心功能**:
- **39 种图表类型**：涵盖架构图、流程图、时序图、状态机、ER 图、时间线、泳道图、象限图、雷达图、循环/飞轮图等，每种均提供浅色、深色和全编辑风格三种静态变体
- **语义化模式系统**：将行为与布局分离，队列、策略追踪、信任边界等概念可复用现有图表类型，无需增加类型数量
- **品牌匹配**：通过读取你的网站，60 秒内匹配品牌视觉风格
- **格式转换**：可将 draw.io 或 Mermaid 源文件重绘为指定格式、尺寸和细节级别
- **可选动效**：默认输出静态 HTML，也可为有序讲解启用可访问的动画效果
- **零依赖**：无构建步骤、无 JavaScript、无外部图片依赖，浏览器直接打开即可

**技术亮点**: 纯 HTML + SVG 实现，无阴影、无外部依赖；内置 10 种以上布局语法（Sankey、鱼骨图、Wardley 地图、看板、用户旅程、部署图、依赖图、UML 类图、故事地图、数据库 schema）；遵循"少即是多"的设计哲学（密度 4/10，强调色仅用于 1-2 个关键元素）；兼容 Agent Skills 标准。

---
## 4. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 242,576
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是由 Nous Research 构建的自我改进型 AI 代理，具备内置学习循环，能从经验中创建技能、跨会话记忆并持续深化对用户的了解，且支持在任何基础设施上运行。

**核心功能**:
- **真实终端界面**: 完整 TUI，支持多行编辑、斜杠命令自动补全、对话历史、中断重定向和流式工具输出
- **多平台接入**: 通过单一网关进程支持 Telegram、Discord、Slack、WhatsApp、Signal 和 CLI，含语音备忘录转录和跨平台对话连续性
- **闭环学习机制**: 代理策划记忆并周期性提醒，复杂任务后自动创建技能，技能在使用中自我改进，支持 FTS5 会话搜索与 LLM 摘要实现跨会话回忆，兼容 agentskills.io 开放标准
- **定时自动化**: 内置 cron 调度器，可将自然语言任务（日报、备份、审计）投递到任意平台，无人值守运行
- **委派与并行**: 可生成隔离子代理处理并行工作流，支持通过 RPC 调用工具的 Python 脚本，将多步骤管线压缩为零上下文开销
- **任意环境运行**: 支持七种终端后端（本地、Docker、SSH、Singularity、Modal、Daytona、Vercel Sandbox），Daytona 和 Modal 提供无服务器持久化，空闲时休眠唤醒，成本极低
- **研究就绪**: 支持批量轨迹生成和轨迹压缩，用于训练下一代工具调用模型

**技术亮点**: 模型无关设计（支持 Nous Portal、OpenRouter、OpenAI 及自定义端点，通过 `hermes model` 切换）；基于 Honcho 的辩证用户建模；跨平台网关架构；支持 $5 VPS 到 GPU 集群的弹性部署；一键安装脚本（Linux/macOS/WSL2/Termux 及 Windows 原生 PowerShell 支持）。

---
## 5. [openai/skills](https://github.com/openai/skills)
- **语言**: Python
- **Stars**: 25,637
- **简介**: Skills Catalog for Codex

### AI 总结
**简介**: openai/skills 是 Codex 的 Agent Skills 技能目录仓库，用于存储和分发可复用的指令、脚本和资源，但目前已被弃用，相关功能迁移至 OpenAI Plugins 仓库。

**核心功能**:
- 提供技能分类目录：`.system`（自动安装）、`.curated`（精选）、`.experimental`（实验性）三类技能
- 支持通过 `$skill-installer` 命令在 Codex 中安装精选或实验性技能
- 每个技能包含独立的 `LICENSE.txt` 文件，明确许可条款
- 技能可被 AI 代理自动发现并用于完成特定任务

**技术亮点**: 遵循 Agent Skills 开放标准（agentskills.io），采用"一次编写，处处使用"的设计理念，技能以文件夹形式封装指令、脚本和资源，便于团队和个人在 Codex 中重复使用。

---
## 6. [anomalyco/opencode](https://github.com/anomalyco/opencode)
- **语言**: TypeScript
- **Stars**: 205,285
- **简介**: The open source coding agent.

### AI 总结
**简介**: OpenCode 是一个开源的 AI 编程代理，提供终端界面和桌面应用，帮助开发者自动完成编码任务。

**核心功能**:
- 内置两种可切换的代理模式：`build`（默认，全权限开发代理）和 `plan`（只读代理，用于代码分析和规划，默认禁止文件编辑，运行 bash 命令前需授权）
- 内置 `general` 子代理，用于复杂搜索和多步骤任务，可通过 `@general` 调用
- 提供跨平台安装方式（curl 脚本、npm、Homebrew、Scoop、Chocolatey、pacman、mise、nix 等）
- 支持桌面应用（BETA），覆盖 macOS、Windows、Linux 平台
- 支持自定义安装目录（通过环境变量 `OPENCODE_INSTALL_DIR`、`XDG_BIN_DIR` 等指定）

**技术亮点**:
- 使用 TypeScript 开发
- 提供终端 UI（Terminal UI）和桌面应用两种交互界面
- 支持 `Tab` 键快速切换代理模式
- 文档支持多语言（20+ 种语言）

---
## 7. [blader/humanizer](https://github.com/blader/humanizer)
- **语言**: Python
- **Stars**: 44,304
- **简介**: Agent skill that removes signs of AI-generated writing from text

### AI 总结
**简介**: Humanizer 是一个 Agent skill，用于去除文本中的 AI 写作痕迹，让 AI 生成的文字读起来更像真人手写，而不改变原意。

**核心功能**:
- **文本去 AI 化改写**: 将 AI 味浓重的文本改写为自然的人类风格，保持原意不变
- **语音匹配**: 支持用户提供个人写作样本，让改写结果匹配用户的节奏、措辞、标点习惯
- **文件级处理**: 可直接指定文件路径，仅改写散文内容，保留代码、数据、frontmatter 和链接
- **过程透明**: 粘贴文本时展示完整改写流程（初稿、批判性点评、最终版本），不虚构事实，缺少细节时会主动询问
- **25 种 AI 写作模式检测**: 按强度与频率编号，涵盖"铺垫代替陈述""规则化节奏"等常见 AI 文体特征

**技术亮点**: 纯 Markdown 实现，兼容任何支持 skills 的 Agent（Claude Code、Claude Desktop 等）；通过 `npx skills` 或 `/plugin` 命令安装；基于语言模型多轮迭代（标记问题→重写→对照检查→输出终稿）的检测-改写机制。

---
## 8. [llvm/llvm-project](https://github.com/llvm/llvm-project)
- **语言**: LLVM
- **Stars**: 40,224
- **简介**: The LLVM Project is a collection of modular and reusable compiler and toolchain technologies.

### AI 总结
**简介**: LLVM 是一个模块化、可复用的编译器与工具链基础设施，用于构建高度优化的编译器、优化器和运行时环境。

**核心功能**:
- 提供中间表示（IR）处理工具链，包括汇编器、反汇编器、位码分析器和位码优化器
- 支持将 IR 转换为目标平台的对象文件
- 通过 Clang 前端支持 C、C++、Objective-C 和 Objective-C++ 等 C 系语言编译
- 集成 libc++ C++ 标准库实现
- 提供 LLD 链接器

**技术亮点**:
- 采用模块化架构设计，各组件（如 Clang、libc++、LLD）可独立使用或组合
- 基于 LLVM 位码（bitcode）作为统一中间表示，实现多语言前端与多目标后端的解耦
- 拥有活跃的社区生态，提供 Discourse 论坛、Discord 聊天、Office Hours 等多种沟通渠道

---
## 9. [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail)
- **语言**: JavaScript
- **Stars**: 129,471
- **简介**: Makes your AI agent think like the laziest senior dev in the room. The best code is the code you never wrote.

### AI 总结
**简介**: Ponytail 是一个让 AI 编程助手像“最懒的资深开发”一样思考的工具——用最少的代码完成任务，目标是让 AI 生成更简洁、更高效的代码。

**核心功能**:
- **极致代码精简**: 引导 AI 用最少的代码实现功能，平均减少 54% 的代码量（最高可达 94%）
- **内置“懒惰”提示词**: 将资深开发者的思维方式（“浏览器自带功能就不要引入库”）注入 AI agent
- **兼容主流 AI 编程工具**: 支持 20+ 种 AI agent 工具（如 Claude Code 等）
- **安全可靠**: 在减少代码的同时保持 100% 的安全性（相比简单粗暴的“写一行代码”提示词更安全）
- **性能优化**: 平均降低 20% 成本、27% 耗时、22% token 消耗

**技术亮点**:
- 基于 JavaScript 实现，以 skill/prompt 方式注入 AI agent
- 经过真实场景基准测试（基于 FastAPI + React 真实项目、12 个功能任务、Haiku 4.5 模型验证）
- 提供完整的基准测试结果和可复现方案

---
## 10. [ruvnet/ruflo](https://github.com/ruvnet/ruflo)
- **语言**: TypeScript
- **Stars**: 70,999
- **简介**: 🌊 The original agent meta-harness. Deploy intelligent multi-player swarms, coordinate autonomous workflows, and build conversational AI systems. Features adaptive memory, self-learning intelligence, RAG integration, and native Claude Code / Codex / Hermes and many more Integrated

### AI 总结
**简介**: Ruflo 是一个面向 Claude Code 和 Codex 的智能体元框架（Agent Meta-Harness），为 AI 智能体提供工具、记忆、循环、沙箱和协调控制，使其能够自主协作、自我学习并执行复杂工作流。

**核心功能**:
- **多智能体编排**: 支持智能体自组织成 swarm（集群），协同处理任务，实现多智能体协作
- **自适应记忆系统**: 智能体具备跨会话记忆能力，可从每次任务中学习并持续优化自身行为
- **RAG 集成**: 内置检索增强生成能力，支持知识库接入与上下文增强
- **联邦通信**: 支持跨机器的安全智能体通信，无需数据泄露即可实现分布式协作
- **100+ 专业智能体**: 预置大量专用智能体，覆盖不同场景需求
- **企业级安全防护**: 内置安全护栏，保障企业环境下的数据安全与合规
- **原生集成**: 无缝支持 Claude Code、Codex、Hermes 等多种 AI 工具链

**技术亮点**: 基于 TypeScript 构建，采用"智能体 = 模型 + 框架"的架构理念，提供 CLI 与 MCP 双接口；通过 `npx ruflo init` 即可快速部署，配有可视化 UI Beta（flo.ruv.io）；采用自学习/自优化的智能体架构设计，支持学习循环反馈机制，生态下载量超 810 万次。

---
