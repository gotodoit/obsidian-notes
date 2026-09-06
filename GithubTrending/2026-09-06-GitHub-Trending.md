---
tags:
  - github-trending
  - daily
date: 2026-09-06
created: 2026-09-06T01:55:44.068Z
---

# 2026-09-06 GitHub Trending Top 10

## 1. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 252,709
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: 这是一套由资深工程师 Matt Pocock 维护的 Agent Skills 集合，用于提升 Claude Code、Codex 等编码代理在实际工程开发中的表现，而非简单的"氛围编程"。

**核心功能**:
- **对齐式提问**: 通过 `/grill-me` 和 `/grill-with-docs` 技能，在开发前让 AI 代理主动向开发者提问，澄清需求，避免"代理没按我的想法做"的常见失败模式
- **轻量可组合**: 技能被设计为小型、易于修改和组合，不采用 GSD、BMAD 等"接管流程"的重型方案，保留开发者控制权
- **一键安装配置**: 支持通过 Claude Code 插件（只读托管、自动更新）或 `npx skills` 命令（可编辑文件、手动更新）两种方式安装，并运行 `/setup-matt-pocock-skills` 完成初始化（选择问题追踪器、标签策略、文档存储位置）
- **工程化工作流**: 包含问题分类（triage）、文档创建等日常工程操作技能，适配 GitHub、Linear 或本地文件

**技术亮点**: 基于 Shell 实现，兼容多种 AI 代理（Claude Code、Codex 等）；提供双模式安装（订阅式插件 vs 可编辑副本）；技能集遵循领域驱动设计理念，内置 ADR（架构决策记录）文档，支持可演进的设计。

---
## 2. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 249,949
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个面向 AI 编程代理（如 Claude Code、Codex 等）的代理性能优化系统，提供技能、直觉、记忆、安全与研究优先的开发能力。

**核心功能**:
- 支持 Claude Code、Codex、Opencode、Cursor 等多种 AI 编程代理
- 通过 `npx ecc-universal setup` 提供一键式引导安装
- 提供插件管理（`ecc@ecc` 插件作用域），支持安全安装、更新与迁移
- 包含技能、直觉、记忆模块，增强代理的上下文感知与执行能力
- 提供安全防护（AgentShield）功能，保障代理运行安全
- 提供 GitHub App 集成（ECC Tools），支持仓库级自动化操作
- 支持多语言文档（13 种语言），覆盖全球开发者社区

**技术亮点**: 基于 JavaScript/TypeScript 构建，兼容 Shell、Python、Go、Java、Perl 等多语言环境；通过 npm 包（`ecc-universal`、`ecc-agentshield`）分发，支持插件化架构与钩子（hook）配置；需要 Node.js 18+、Git 和 Claude Code 2.1+ 环境。

---
## 3. [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail)
- **语言**: JavaScript
- **Stars**: 127,997
- **简介**: Makes your AI agent think like the laziest senior dev in the room. The best code is the code you never wrote.

### AI 总结
**简介**: Ponytail 是一个让 AI 编程助手像“最懒的资深工程师”一样思考的工具——用最少的代码完成任务，避免过度工程化。

**核心功能**:
- **代码极简化**: 引导 AI 用最简洁的方式实现功能（例如用原生 `<input type="date">` 替代复杂的日期选择器库）
- **跨 20+ AI Agent 兼容**: 可应用于 Claude Code 等多种主流 AI 编程代理
- **显著降低资源消耗**: 实测减少约 54% 代码量、20% 成本和 27% 耗时
- **保持安全底线**: 在精简代码的同时，100% 保留安全防护，优于同类“YAGNI + 单行代码”提示词方案（后者安全率仅 95%）

**技术亮点**:
- 基于 JavaScript 实现，采用 Skill 机制注入 Agent 工作流
- 提供可复现的基准测试框架（基于真实 FastAPI + React 开源仓库的 12 个功能任务，n=4 重复实验）
- 支持多语言文档（英文/西班牙文/韩文），通过 npm 包分发（`@dietrichgebert/ponytail`），MIT 开源协议

---
## 4. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 242,036
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是由 Nous Research 构建的自我改进型 AI 代理，具备内置学习循环，能跨会话积累经验、自主创建技能并深化对用户的理解，且可运行于从低配 VPS 到 GPU 集群的多种环境。

**核心功能**:
- **真正的终端界面 (TUI)**: 支持多行编辑、斜杠命令自动补全、对话历史、中断重定向及流式工具输出。
- **多平台接入**: 通过单一网关进程支持 Telegram、Discord、Slack、WhatsApp、Signal 和 CLI，并支持语音备忘录转录和跨平台对话连续性。
- **闭环学习机制**: 代理策展记忆并定期提示；复杂任务后自主创建技能且技能在使用中自我改进；具备 FTS5 会话搜索和 LLM 摘要，实现跨会话回忆；集成 Honcho 辩证用户建模，兼容 agentskills.io 开放标准。
- **定时自动化**: 内置 cron 调度器，可用自然语言设定每日报告、夜间备份、每周审计等无人值守任务。
- **任务委派与并行**: 可生成隔离的子代理处理并行工作流，并支持通过 RPC 调用工具的 Python 脚本，将多步流水线压缩为低成本步骤。
- **随处运行**: 支持七种终端后端（本地、Docker、SSH、Singularity、Modal、Daytona、Vercel Sandbox），其中 Daytona 和 Modal 提供无服务器持久化，空闲时休眠、按需唤醒，成本极低。
- **研究就绪**: 支持批量轨迹生成和轨迹压缩，用于训练下一代工具调用模型。

**技术亮点**: 基于 Python 构建，采用 uv 管理依赖；模型无关设计，支持 Nous Portal、OpenRouter、OpenAI 及自定义端点，通过 `hermes model` 命令无缝切换；安装脚本支持 Linux/macOS/WSL2/Termux 及 Windows 原生 PowerShell（含便携版 Git Bash 隔离方案）。

---
## 5. [fmtlib/fmt](https://github.com/fmtlib/fmt)
- **语言**: C++
- **Stars**: 25,574
- **简介**: A modern formatting library

### AI 总结
**简介**: {fmt} 是一个开源的 C++ 格式化库，提供快速、安全的字符串格式化方案，作为 C stdio 和 C++ iostreams 的现代替代品。

**核心功能**:
- 支持 Python 风格格式化语法，包括位置参数（用于本地化）
- 实现 C++20 `std::format` 和 C++23 `std::print` 标准
- 提供安全的 `printf` 实现，支持 POSIX 位置参数扩展
- 支持用户自定义类型的格式化扩展
- 便携式 Unicode 支持
- 支持日期和时间格式化（chrono 类型）
- 可选的 header-only 配置模式（`FMT_HEADER_ONLY` 宏）

**技术亮点**:
- 基于 Dragonbox 算法的 IEEE 754 浮点数格式化，保证正确舍入、最短表示和往返保证
- 高性能：速度快于标准库的 `(s)printf`、iostreams、`to_string` 和 `to_chars`
- 编译期错误检测，完全类型安全，自动内存管理防止缓冲区溢出
- 代码体积小（最小配置仅需 3 个文件），无外部依赖，采用宽松的 MIT 许可证
- 跨平台输出一致，支持较老编译器，高质量代码（`-Wall -Wextra -pedantic` 下无警告）
- 默认区域设置无关，保证输出一致性

---
## 6. [anthropics/skills](https://github.com/anthropics/skills)
- **语言**: Python
- **Stars**: 174,578
- **简介**: Public repository for Agent Skills

### AI 总结
**简介**: Anthropic 官方发布的 Agent Skills 公共仓库，包含 Claude 可动态加载的技能示例、规范文档和模板，用于提升模型在特定任务上的表现。

**核心功能**:
- **示例技能集合**: 涵盖创意设计（艺术、音乐）、开发技术（Web 测试、MCP 服务器生成）及企业流程（通信、品牌）等多种场景，每个技能以独立文件夹 + `SKILL.md` 文件形式组织
- **文档技能**: 内置驱动 Claude 文档能力的 docx/pdf/pptx/xlsx 处理技能（源码可用，非开源），供开发者参考复杂生产级技能实现
- **技能规范与模板**: 提供 Agent Skills 标准规范（`spec` 目录）和技能创建模板（`template` 目录），支持快速开发自定义技能
- **多平台集成**: 支持 Claude Code 插件市场一键安装、Claude.ai 直接使用，以及通过 Claude API 调用预置或自定义技能

**技术亮点**: 采用轻量级 YAML frontmatter（仅需 `name` 和 `description` 字段）+ Markdown 指令的技能定义格式；技能可随需动态加载，实现重复性任务标准化；仓库遵循 Apache 2.0 开源协议（文档技能除外）。

---
## 7. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 31,713
- **简介**: 38 editorial diagram types for Claude Code, Codex, and Pi. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个为 Claude Code、Codex 等 AI 编程工具设计的图表生成技能库，提供 39 种编辑级质量的 HTML+SVG 图表类型，让 AI 生成的图表不再"丑陋"。

**核心功能**:
- **39 种图表类型**: 涵盖架构图、流程图、时序图、状态机、ER 图、时间线、泳道图、象限图、雷达图、循环图、Sankey、鱼骨图、Wardley 图、看板、用户旅程、部署图、依赖图、UML 类图、故事地图、数据库 schema 等
- **三种静态变体**: 每种图表类型提供 minimal light、minimal dark、full-editorial 三种风格，可直接在浏览器打开，无构建步骤、无 JavaScript、无外部图片依赖
- **品牌自动匹配**: 通过读取你的网站，60 秒内匹配品牌视觉风格
- **语义化模式**: 语义模式将行为与布局分离，队列、策略追踪、信任边界等可复用现有类型，无需增加类型数量
- **格式转换**: 可重绘 draw.io 或 Mermaid 源文件，并指定格式、尺寸和详细程度
- **可选动画**: 2.3 版本起支持无障碍动画，静态输出仍为默认

**技术亮点**: 纯 HTML+SVG 自包含文件，无阴影效果、无 Mermaid 依赖；采用"少即是多"的设计理念（目标密度 4/10），强调编辑级排版质量；新增 2.5.10 版本加入 10 种布局语法，支持 Agent Skills 兼容主机。

---
## 8. [anomalyco/opencode](https://github.com/anomalyco/opencode)
- **语言**: TypeScript
- **Stars**: 204,696
- **简介**: The open source coding agent.

### AI 总结
**简介**: OpenCode 是一个开源的 AI 编程代理，提供终端 UI 和桌面应用，帮助开发者高效完成编码任务。

**核心功能**:
- 内置两种可切换的代理模式（Tab 键切换）：`build`（默认，具备完整权限的开发代理）和 `plan`（只读代理，用于代码分析和探索，默认禁止文件编辑，执行命令前需授权）
- 提供 `general` 子代理，用于复杂搜索和多步骤任务，可通过 `@general` 调用
- 支持多平台安装（npm、Homebrew、Scoop、Choco、pacman、Nix 等）及桌面应用（macOS、Windows、Linux）
- 提供丰富的多语言文档支持

**技术亮点**: 使用 TypeScript 开发，支持灵活的安装路径配置（遵循 XDG 规范），拥有活跃的社区和完整的 CI/CD 发布流程，同时提供终端 UI 和桌面客户端两种交互方式。

---
## 9. [ruvnet/ruflo](https://github.com/ruvnet/ruflo)
- **语言**: TypeScript
- **Stars**: 70,706
- **简介**: 🌊 The original agent meta-harness. Deploy intelligent multi-player swarms, coordinate autonomous workflows, and build conversational AI systems. Features adaptive memory, self-learning intelligence, RAG integration, and native Claude Code / Codex / Hermes and many more Integrated

### AI 总结
**简介**: Ruflo 是一个为 Claude Code 和 Codex 设计的智能体元框架（agent meta-harness），通过提供工具、记忆、循环、沙箱和控制层，让 AI 智能体不仅能够运行，还能协作完成复杂任务。

**核心功能**:
- **多智能体编排**: 支持部署智能多玩家智能体群（swarms），自主协调工作流
- **自适应记忆与自学习**: 智能体从每次任务中学习，跨会话记忆，形成持续优化的学习闭环
- **RAG 集成**: 内置检索增强生成能力，增强智能体的知识获取与推理
- **联邦通信**: 支持跨机器的安全智能体通信，不泄露数据
- **100+ 专业智能体**: 提供丰富的预构建智能体，覆盖多种应用场景
- **企业级安全防护**: 内置安全护栏，保障企业级应用的数据安全
- **广泛生态集成**: 原生支持 Claude Code、Codex、Hermes 等主流 AI 工具

**技术亮点**: 基于 TypeScript 开发，采用"模型 + 框架"的架构理念（Agent = Model + Harness），通过 CLI/MCP 接口实现路由分发，形成"用户 → 路由器 → 智能体群 → 智能体 → 记忆 → LLM 提供商"的自学习架构，支持一键初始化（`npx ruflo init`），并附带可视化 UI 测试版（flo.ruv.io）。

---
## 10. [humanlayer/skills](https://github.com/humanlayer/skills)
- **语言**: TypeScript
- **Stars**: 2,724
- **简介**: 

### AI 总结
**简介**: HumanLayer 提供的 Claude Code 技能集合，通过 `npx skills add` 命令快速安装，用于增强开发工作流。

**核心功能**:
- **improve-claude-md**: 使用 `<important if>` 块重写 CLAUDE.md，提升指令遵循度
- **narrow-react-prop-types**: 收窄 React 组件 prop 类型，匹配实际代码路径（而非 Storybook/测试/模拟数据状态）
- **build-iterated-agentic-loop**: 构建仓库本地技能及迭代式编码代理 GitHub Actions 工作流（含提示词、记忆文件和参考模板）
- **design-control-loop**: 通过访谈设计代理控制回路（传感器、控制器、执行器、干扰），并生成可本地运行的组件和定时编码代理工作流
- **show-me**: 用简洁图表、代码形状草图和聚焦 HTML 工件解释当前主题

**技术亮点**: 基于 TypeScript，采用 Claude Code 的斜杠命令交互模式，技能通过 `npx` 一键安装，强调本地代码库的自动化重构与代理工作流设计。

---
