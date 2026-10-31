---
tags:
  - github-trending
  - daily
date: 2026-10-31
created: 2026-10-31T01:55:43.334Z
---

# 2026-10-31 GitHub Trending Top 10

## 1. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 106,312
- **简介**: Persistent Context Across Sessions for Every Agent – Captures everything your agent does during sessions, compresses it with AI, and injects relevant context back into future sessions. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode + More

### AI 总结
**简介**: Claude-Mem 是一个为 AI 编程助手提供跨会话持久化记忆的压缩系统，最初为 Claude Code 构建，现已兼容多种 Agent。

**核心功能**:
- 自动捕获 Agent 在会话期间的所有操作记录
- 利用 AI 对捕获内容进行压缩存储
- 在后续会话中自动注入相关上下文，实现跨会话记忆延续
- 支持 Claude Code、OpenClaw、Codex、Gemini、Hermes、Copilot、OpenCode 等多种 Agent

**技术亮点**: 基于 TypeScript 开发，要求 Node.js >= 20.0.0；采用 Apache 2.0 开源协议；提供 30 余种语言的国际化文档支持。

---
## 2. [milind-soni/OpenMausBot](https://github.com/milind-soni/OpenMausBot)
- **语言**: TypeScript
- **Stars**: 8,701
- **简介**: Open-source Grok Bot alternative with a virtual machine that bots can use

### AI 总结
**简介**: OpenMausBot 是一个开源的 Grok Bot 替代方案，以聊天应用的形式为用户提供一队可自定义的 AI 智能体（机器人）。

**核心功能**:
- 侧边栏中每个机器人都是一个真实智能体（底层运行 Claude 或 Codex），拥有独立人格、模型、云端计算机和已连接的应用
- 像联系人一样与机器人对话，可实时观察其工作过程，并对关键操作进行审批
- 自带虚拟机供机器人使用，支持本地优先、自备智能体（bring-your-own-agent）模式

**技术亮点**: 基于 TypeScript（严格模式）开发，前端采用 React 19，桌面端使用 Electron 打包，支持 macOS（Apple silicon / Intel）、Windows 和 Ubuntu 多平台发布。

---
## 3. [pbakaus/impeccable](https://github.com/pbakaus/impeccable)
- **语言**: Rust
- **Stars**: 97,125
- **简介**: The design vocabulary for your coding agent. Steer with polish and bolder, review with critique and audit, catch AI slop before it ships.

### AI 总结
**简介**: Impeccable 是为 AI 编码助手提供的一套设计词汇与审查工具，通过命令化指令引导 Agent 产出更有设计感的界面，并在交付前拦截千篇一律的“AI 味”设计。

**核心功能**:
- **设计引导命令**：`bolder`、`quieter`、`distill`、`colorize`、`typeset`、`layout`、`animate`、`delight`、`overdrive` 等，用精确词汇替代“让它更出彩”这类模糊需求。
- **设计审查**：`critique` 基于可用性启发式给出打分式 UX 评审并排序修复优先级；`audit` 检查可访问性、性能、主题与响应式，问题按 P0–P3 分级。
- **AI 味检测**：内置 62 条确定性规则，识别 Inter 字体滥用、紫蓝渐变、卡片嵌套、彩色背景灰字等常见套路，无需 LLM 或 API Key。
- **交付收尾**：`polish`、`harden`、`clarify`、`adapt`、`optimize`、`onboard` 覆盖上线前的细节打磨与边界情况。
- **实时迭代**：`live` 可在浏览器中选取元素并循环切换变体，`generate` 批量生成指定元素的方案。
- **上下文文件**：`init` 生成 `PRODUCT.md` 记录产品定位与约束，`document` 将现有视觉体系沉淀为 `DESIGN.md`，`extract` 抽取重复模式进设计系统。

**技术亮点**: 基于 Rust 实现；采用纯规则驱动的确定性检测（不依赖大模型），保证结果稳定可复现；通过斜杠命令（`/impeccable <command> <target>`）深度集成 Claude Code、Cursor、Codex CLI、GitHub Copilot、Gemini CLI 等 20 余种编码工具；支持命令固定（`pin`）以生成快捷指令。

---
## 4. [CopilotKit/OpenBot](https://github.com/CopilotKit/OpenBot)
- **语言**: TypeScript
- **Stars**: 8,815
- **简介**: Open-source AI coworkers that each get a computer of their own: a browser, files and tools, with every action decided before it happens and recorded after. Bring any AG-UI agent.

### AI 总结
**简介**: OpenBot 是 CopilotKit 开源的自托管 AI 同事平台，每个 AI 同事拥有独立的浏览器、文件和工具权限，所有操作在执行前决策、执行后记录，可通过 AG-UI 协议接入任意智能体。

**核心功能**:
- 每个 AI 同事配备独立浏览器（含独立登录态）、文件空间，以及仅限授权的工具集
- 所有对电脑、文件、MCP 服务器或组件的操作都经过统一网关，执行前决策、执行后留痕
- 支持接入任意 AG-UI 协议的智能体（框架编写或手写），接入后即成为拥有独立频道的同事
- 用户可实时观看 AI 在独立屏幕上工作，在敏感操作前接管，完成后交还控制权
- 以组件而非纯文本形式作答，适配更丰富的交互展示
- 内置 General Assistant、Knowledge 等示例同事，另有 10 余个金融场景同事模板可按需启用或自行编写

**技术亮点**: 基于 TypeScript 开发，使用 Docker Compose 一键拉起全部组件；数据存储于自有 PostgreSQL；模型可自选（不预置模型，管理员提供加密凭据）；基于 AG-UI 开放协议构建，强调可克隆、可定制的模板化设计，完全运行在自有基础设施上（MIT 协议，当前为 Beta 阶段）。

---
## 5. [Renhuai123/ziwei-doushu](https://github.com/Renhuai123/ziwei-doushu)
- **语言**: TypeScript
- **Stars**: 11,249
- **简介**: 紫微斗数开源排盘引擎 — 基于倪海厦《天纪》体系，含完整排盘算法、四化系统、格局知识库、古籍原文数据

### AI 总结
**简介**: 基于倪海厦《天纪》体系的紫微斗数开源排盘引擎，提供完整排盘算法、四化系统、格局知识库及古籍原文数据。

**核心功能**:
- 完整紫微斗数排盘算法，含真太阳时校正、中国夏令时判定与钟表时间换算
- 四化系统与格局知识库，断语按倪师原话及《全书》原文逐句校正
- 古籍原文数据与「古籍引证」知识库（405 处可逐字查证）
- 开源解读数据集：v4.0 覆盖 67.5 万张命盘 × 13 维，共 877 万段解读，按年份分文件下载
- 倪师《天纪·紫微斗数》原话语料 1848 条，附集数与时间点可回放

**技术亮点**: TypeScript 实现，模块化拆分排盘引擎（algorithm、sihua、patterns、true-solar-time、clock-adjust、cities 等）；代码采用 MIT 协议，数据集采用 CC BY 4.0，倪师原话部分为 CC BY-NC-SA 4.0；支持海外出生地经度修正与流派设置切换。

---
## 6. [expo/skills](https://github.com/expo/skills)
- **语言**: Shell
- **Stars**: 3,907
- **简介**: A collection of AI agent skills for working with Expo projects and Expo Application Services

### AI 总结
**简介**: Expo 官方推出的 AI agent 技能集合，帮助 AI 编程助手正确构建、部署、升级和调试 Expo 应用及 EAS 服务。

**核心功能**:
- 为 AI agent 提供聚焦的 Expo 知识，涵盖 Expo API 使用时机、常见工作流结构，以及 Expo、EAS、React Native、iOS、Android 的关键约束
- 支持通过 skills CLI 一键安装全部技能（`npx skills@latest add expo/skills --skill '*'`），兼容 Cursor、OpenCode、GitHub Copilot、Windsurf、Gemini、Cline 等多种 AI 编程工具
- 支持 Claude Code 和 Codex 通过官方插件市场安装，并由市场统一管理更新
- 提供 `expo-overview` 入口技能，用于在任务模糊时自动路由到具体技能
- 框架类开源技能覆盖项目结构、Expo Router 路由、动画手势、原生 UI、设计系统、`@expo/ui` 组件、数据请求、DOM 组件、Web 迁移原生、原生模块等场景
- 服务类技能（EAS 相关）在描述中标注免费/付费边界，并附成本与套餐限制说明

**技术亮点**: 以 `SKILL.md` 文件形式分发技能，由 agent 根据任务上下文和技能描述自动选择；官方文档与 Expo CLI、EAS CLI 仍作为事实来源，技能负责帮助 agent 正确应用；采用插件市场与 CLI 双通道分发，兼顾更新便利性与工具兼容性。

---
## 7. [macro-inc/macro](https://github.com/macro-inc/macro)
- **语言**: Rust
- **Stars**: 5,883
- **简介**: Macro is a unified workspace for teams: email, chat, docs, tasks, agents, calls, and CRM — @-linked together with shared AI memory.

### AI 总结
**简介**: Macro 是一款面向团队的一体化工作空间，将邮件、消息、文档、任务、AI 代理、通话和 CRM 统一到单一快速界面，并通过共享的团队级 AI 记忆将一切 @ 关联起来。

**核心功能**:
- **邮件（Email）**：多账户统一收件箱、键盘快捷键、共享收件箱，支持 Gmail，并提供面向 AI 代理的搜索工具。
- **消息（Messages）**：面向专注技术讨论的频道和私信。
- **任务（Tasks）**：受 Linear 启发的任务系统，与频道、邮件和代理深度集成。
- **文档（Docs）**：基于 CRDT 的实时协作、Markdown 原生文档，支持 @ 提及。
- **画布（Canvas）**：可嵌入任务、文件和邮件 @ 链接的 2D 看板。
- **代理（Agents）**：统一的团队级记忆，可代替用户执行操作。
- **通话（Calls）**：录制、转录并记录到团队记忆中，供代理使用。
- **文件存储**：从邮件和频道自动导入，完全可搜索。
- **拉取请求（Pull Requests）**：关联任务、可嵌入频道、供代理使用。
- **CRM**：客户与联系人对象、自定义属性、邮件同步与信息增强。

**技术亮点**: 前端采用 SolidJS，后端采用 Rust 以保证速度与可靠性；所有模块共享同一后端，文档与任务、频道消息与邮件之间的交叉引用以**双向图**原生存储；文档基于 CRDT 实现实时协作；各模块按模块化"积木"理念设计，可扩展且可组合。

---
## 8. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 307,510
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: mattpocock/skills 是 Matt Pocock 从个人 `.agents` 目录中提炼的一套面向真实工程开发的 AI Agent 技能集，强调小而可组合、可控可改，而非"氛围编程"。

**核心功能**:
- **需求对齐（Grilling 会话）**：`/grill-me` 与 `/grill-with-docs` 让 Agent 在动手前通过提问澄清需求，解决人机沟通错位问题，是仓库中最受欢迎的技能。
- **精简输出**：针对 Agent 回复过于冗长的问题，通过技能约束表达方式，让交流更聚焦。
- **初始化配置**：`/setup-matt-pocock-skills` 按仓库运行一次，配置所用 issue 追踪器（GitHub、GitLab、本地文件等）、triage 标签及文档保存位置。
- **多 Agent 安装支持**：提供 Claude Code、Codex、GitHub Copilot（CLI/VS Code）、Gemini CLI 及通用 Agent 的安装方式，支持插件自动更新或手动可编辑文件两种模式。

**技术亮点**: 以 Shell 为主实现，技能按 `engineering` 与 `productivity` 分类组织；设计上强调小体积、易改造、可组合，兼容任意模型，避免像 GSD、BMAD、Spec-Kit 那样接管整个流程而剥夺用户控制权；通过 skills.sh 与各 Agent 插件市场分发，安装约 30 秒完成。

---
## 9. [pingdotgg/t3code](https://github.com/pingdotgg/t3code)
- **语言**: TypeScript
- **Stars**: 32,778
- **简介**: 

### AI 总结
**简介**: T3 Code 是一个“智能体控制台”（agent harness control surface），让你通过移动端、Web 端或桌面端远程控制本机上已安装的 AI 编程智能体。

**核心功能**:
- 统一控制本机已安装并登录的多种智能体：Claude Code、Codex、Cursor、Grok Build、OpenCode 和 Google Antigravity
- 提供 iOS、Android 移动 App、Web 应用（app.t3.codes）和 Electron 桌面应用，支持手机或另一台机器远程访问
- 支持通过 MCP 与外部智能体（Claude Code、Codex、ChatGPT 等）连接
- 提供权限模式、键盘快捷键、项目设置、外观偏好、多账号（Codex/Claude）等配置能力
- 支持以命令行方式（`t3`、`npx t3@latest`）运行本地服务，并可安装为后台服务、一键更新
- 覆盖多平台分发：winget、scoop、Homebrew、.deb、AUR、Nix/nixpkgs 以及 GitHub Releases

**技术亮点**: 基于 TypeScript 开发；使用 Vite+（`vp` 命令行工具）作为构建与开发工具链；采用 Electron 构建桌面端，并提供 CLI 服务端 + 本地 Web 应用的双端架构，强调高性能与远程可用性；项目完全开源，便于自行 fork 和定制。项目目前处于早期阶段，以修复小问题为主，暂不接受大型功能贡献。

---
## 10. [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)
- **语言**: Python
- **Stars**: 51,813
- **简介**: DeepTutor: Lifelong Personalized Tutoring. https://deeptutor.info/.

### AI 总结
**简介**: DeepTutor 是香港大学数据科学实验室（HKUDS）开源的终身个性化 AI 辅导系统，面向学习者提供持续、可定制的智能教学体验。

**核心功能**:
- 终身个性化辅导：围绕学习者长期学习过程提供个性化教学支持
- 多语言支持：README 提供简体中文、繁体中文、日语、西班牙语、法语、阿拉伯语、俄语、印地语、葡萄牙语、泰语、波兰语等十余种语言版本
- 提供 CLI 与 Agent 原生接口，便于开发者集成与二次开发
- 配套 EduHub 技能社区生态，支持扩展教学能力

**技术亮点**:
- 后端基于 Python 3.11+，前端采用 Next.js 16
- 采用 Apache 2.0 开源协议，并有对应 arXiv 论文支撑
- 提供完善的文档站点（deeptutor.info）、Discord/飞书/微信社区及贡献指南，工程化与社区运营较成熟

---
