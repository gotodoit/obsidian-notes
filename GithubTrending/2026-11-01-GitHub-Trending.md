---
tags:
  - github-trending
  - daily
date: 2026-11-01
created: 2026-11-01T01:55:43.294Z
---

# 2026-11-01 GitHub Trending Top 10

## 1. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 107,927
- **简介**: Persistent Context Across Sessions for Every Agent – Captures everything your agent does during sessions, compresses it with AI, and injects relevant context back into future sessions. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode + More

### AI 总结
**简介**: Claude-Mem 是一个为 Claude Code 等 AI 编码代理提供跨会话持久化记忆的压缩系统，能捕获代理会话中的操作、用 AI 压缩后在未来会话中注入相关上下文。

**核心功能**:
- 自动捕获代理在会话中的所有操作记录
- 使用 AI 对捕获内容进行压缩存储
- 在后续会话中注入相关上下文，实现跨会话的持久记忆
- 兼容 Claude Code、OpenClaw、Codex、Gemini、Hermes、Copilot、OpenCode 等多种代理工具

**技术亮点**: 基于 TypeScript 开发，要求 Node.js >= 20.0.0，采用 Apache 2.0 开源协议；作为 Vercel OSS 计划项目，提供多语言文档支持（含中文、日文、韩文等 30 余种语言）。

---
## 2. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 308,431
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: mattpocock/skills 是开发者 Matt Pocock 从自己 `.agents` 目录中开源的一套日常工程技能（Agent Skills），强调小巧、可组合、可改造，用于真正的软件开发而非"氛围编程"。

**核心功能**:
- `/grill-me` 与 `/grill-with-docs`：通过"拷问式"提问让 Agent 在动手前与你充分对齐需求，解决最常见的意图错位问题（作者最受欢迎的技能）。
- `/triage`：结合 Issue 跟踪器与标签体系对工单进行分诊管理。
- `/setup-matt-pocock-skills`：每个仓库运行一次，配置问题跟踪器（GitHub、GitLab、本地文件等）、分诊标签与文档存放位置。
- 技能按 `engineering` 与 `productivity` 两类组织，可单独安装、按需组合。

**技术亮点**: 以 Shell 为主，兼容 Claude Code、Codex、GitHub Copilot、Gemini CLI 及 Cursor、Windsurf、Amp 等多种 Agent；支持插件自动更新或 `npx skills` 手动安装两种模式；设计上刻意保持轻量、可编辑、模型无关，避免像 GSD、BMAD、Spec-Kit 那样接管流程而剥夺开发者控制权。

---
## 3. [Donchitos/Claude-Code-Game-Studios](https://github.com/Donchitos/Claude-Code-Game-Studios)
- **语言**: Shell
- **Stars**: 31,215
- **简介**: Turn Claude Code into a full game dev studio — 49 AI agents, 72 workflow skills, and a complete coordination system mirroring real studio hierarchy.

### AI 总结
**简介**: 将单次 Claude Code 会话转变为完整游戏开发工作室，通过 49 个专业 AI 智能体和 74 个工作流技能模拟真实工作室层级协作。

**核心功能**:
- **49 个专业智能体**：按三级工作室架构组织（总监层、部门主管层、专家层），覆盖设计、编程、美术、音频、叙事、QA 和生产等领域，每个智能体有明确职责、升级路径和质量关卡
- **74 个斜杠命令技能**：覆盖完整工作流阶段（`/start`、`/design-system`、`/create-epics`、`/create-stories`、`/dev-story`、`/story-done` 等）
- **15 个自动化钩子**：在提交、推送、资源变更、设计文档读写、会话生命周期等环节执行验证与审计
- **14 条路径作用域规则**：针对游戏玩法、引擎、AI、UI、网络代码等不同路径强制执行编码标准
- **62 个文档模板**：包含 GDD、UX 规范、ADR、冲刺计划、HUD 设计、无障碍设计等
- **多引擎支持**：为三大主流游戏引擎提供对应的智能体集合

**技术亮点**:
- 基于 Claude Code 构建，采用 Shell 语言实现
- 三级智能体层级架构（总监 → 部门主管 → 专家），模拟真实工作室的职责划分与升级机制
- 每个智能体在 frontmatter 中声明模型：总监层使用 Opus，部分主管和专家使用 Sonnet，其余继承会话模型
- 通过钩子、规则和模板形成完整的质量门禁与协调系统，从头脑风暴到发布全程保持项目组织性

---
## 4. [pingdotgg/t3code](https://github.com/pingdotgg/t3code)
- **语言**: TypeScript
- **Stars**: 35,678
- **简介**: 

### AI 总结
**简介**: T3 Code 是一个“智能体控制台”，让你通过移动端、Web 端和桌面端远程控制本机已安装的 AI 编程智能体。

**核心功能**:
- 统一控制 Claude Code、Codex、Cursor、Grok Build、OpenCode 和 Google Antigravity 等多种智能体
- 提供 iOS/Android 移动应用、Web 应用和基于 Electron 的桌面应用三种客户端
- 支持远程访问：可从手机或其他机器操控本机智能体
- 支持通过 MCP 与外部智能体连接
- 可作为后台服务运行，支持多账户配置与源码管理集成

**技术亮点**: 基于 TypeScript 开发，使用 Vite+ 工具链（`vp` 命令行）；采用客户端/服务端架构，由本地 `t3` 服务端驱动各客户端；完全开源，便于用户自行 fork 和定制。项目处于早期阶段，目前主要接受小型修复类贡献。

---
## 5. [Renhuai123/ziwei-doushu](https://github.com/Renhuai123/ziwei-doushu)
- **语言**: TypeScript
- **Stars**: 12,307
- **简介**: 紫微斗数开源排盘引擎 — 基于倪海厦《天纪》体系，含完整排盘算法、四化系统、格局知识库、古籍原文数据

### AI 总结
**简介**: 基于倪海厦《天纪》体系的紫微斗数开源排盘引擎，提供完整排盘算法、四化系统、格局知识库与古籍原文数据，并配套发布大规模解读数据集。

**核心功能**:
- 完整紫微斗数排盘算法，支持真太阳时校正、中国夏令时判定、海外出生地时区修正
- 四化系统与格局知识库，内置《紫微斗数全书》古籍原文数据（古籍引证 405 处）
- 13 维解读数据集 v4.0：67.5 万张命盘 × 13 维 = 877 万段解读，覆盖 1950–2026 年真实日期，按年份分 77 个文件发布
- 倪师《天纪·紫微斗数》原话语料 1848 条，每条标注出处、可回放
- 在线体验平台 OURANIC（ouranic.cn），开放排盘、AI 解读与命盘历史

**技术亮点**: 使用 TypeScript 开发，模块化设计（算法、四化、格局、真太阳时、夏令时、城市经度等独立模块）；代码 MIT 许可、数据集 CC BY 4.0、倪师原话 CC BY-NC-SA 4.0 分层授权；配套 CI、贡献指南与英文 README。

---
## 6. [milind-soni/OpenMausBot](https://github.com/milind-soni/OpenMausBot)
- **语言**: TypeScript
- **Stars**: 9,669
- **简介**: Open-source Grok Bot alternative with a virtual machine that bots can use

### AI 总结
**简介**: OpenMausBot 是一个开源的 Grok Bot 替代方案，以聊天应用形式提供一组可自定义的 AI 智能体团队，支持本地优先运行。

**核心功能**:
- 侧边栏每个机器人都是真实智能体（底层运行 Claude 或 Codex），拥有独立人格、模型、云电脑和已连接应用
- 像通讯录一样与机器人对话、观察其工作，并对关键操作进行审批
- 支持自带智能体（bring-your-own-agent），基于用户已有模型本地运行

**技术亮点**: 使用 TypeScript（严格模式）与 React 19 构建，基于 Electron 实现 macOS、Windows、Ubuntu 跨平台桌面应用；项目为独立开源项目，与 xAI、Meta、OpenAI、Manus 均无关联。

---
## 7. [pbakaus/impeccable](https://github.com/pbakaus/impeccable)
- **语言**: Rust
- **Stars**: 98,327
- **简介**: The design vocabulary for your coding agent. Steer with polish and bolder, review with critique and audit, catch AI slop before it ships.

### AI 总结
**简介**: Impeccable 是一套面向编码 Agent 的设计词汇与命令系统，通过结构化指令引导 AI 生成更高质量、更具设计感的界面，并在交付前拦截“AI 味”设计。

**核心功能**:
- **设计引导命令**：`bolder`、`quieter`、`distill`、`colorize`、`typeset`、`layout`、`animate`、`delight`、`overdrive` 等，用于放大、收敛、精简、配色、排版与动效调整
- **审查与审计**：`critique` 基于可用性启发式给出评分式 UX 评审并排序修复优先级；`audit` 检查可访问性、性能、主题与响应式行为，按 P0–P3 分级
- **交付前收尾**：`polish`、`harden`、`clarify`、`adapt`、`optimize`、`onboard` 覆盖边缘情况、文案、多端适配与首屏体验
- **实时迭代**：`live` 在浏览器中点选元素并循环切换变体，`generate` 自动生成指定元素的多个变体
- **上下文与规划**：`init` 生成 `PRODUCT.md`，`document` 沉淀 `DESIGN.md`，`shape` 在写代码前规划 UX，`extract` 抽取重复模式进设计系统
- **Slop 检测器**：62 条确定性规则识别紫色渐变、卡片嵌套、灰字彩底等典型 AI 设计痕迹，无需 LLM 或 API Key

**技术亮点**: 项目以 Rust 实现；采用“命令 + 目标”的窄范围交互范式以提升效果；通过 `PRODUCT.md`/`DESIGN.md` 持久化项目上下文；兼容 Claude Code、Cursor、Codex CLI、GitHub Copilot、Gemini CLI 等 20 余种编码工具。

---
## 8. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 310,087
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，基于可组合的技能（skills）和初始指令构建，让智能体自动遵循规范化的开发流程。

**核心功能**:
- **需求澄清与规格设计**：智能体不会直接写代码，而是先追问真实目标，将规格拆分成可读的小块供用户确认。
- **实现计划生成**：设计确认后产出清晰的实施计划，强调红/绿 TDD、YAGNI 和 DRY 原则。
- **子智能体驱动开发**：用户确认后启动子智能体流程，逐个完成工程任务并自检审查，可长时间自主工作而不偏离计划。
- **自动触发**：技能自动生效，无需额外操作，智能体即具备 Superpowers 能力。
- **多平台安装支持**：覆盖 Claude Code、Codex、Cursor、Gemini CLI、GitHub Copilot CLI、Qwen Code 等十余种智能体工具。

**技术亮点**: 采用可组合技能架构，以 Shell 为主要语言；通过插件/扩展机制适配不同智能体平台（如 Claude 插件市场、Gemini 扩展、Cursor 插件等），并提供企业级商业支持服务。

---
## 9. [lightpanda-io/browser](https://github.com/lightpanda-io/browser)
- **语言**: Zig
- **Stars**: 39,277
- **简介**: Lightpanda: the headless browser designed for AI and automation

### AI 总结
**简介**: Lightpanda 是一款专为 AI 智能体和自动化场景从零构建的无头浏览器，使用 Zig 语言编写，并非 Chromium 或 WebKit 的分支。

**核心功能**:
- 提供 URL 抓取与页面内容导出，支持 `--dump html`、`--dump markdown`、`--dump png`、`--dump pdf` 等多种输出格式
- 内置 CDP（Chrome DevTools Protocol）服务器（默认端口 9222），可对接 Puppeteer、Playwright 等自动化客户端
- 支持 `--obey-robots` 遵循 robots.txt 协议，适合爬虫与自动化任务

**技术亮点**:
- 完全从零实现的独立浏览器内核，采用 Zig 语言开发，而非基于现有浏览器引擎修改
- 性能显著优于无头 Chrome：在 933 个真实网页、100 页并发的基准测试中，内存占用约 123MB（对比 2GB，约省 16 倍），执行时间约 5s（对比 46s，约快 9 倍）
- 提供 Homebrew、AUR、Nix、Docker 及 nightly 二进制等多种安装方式，覆盖 Linux（x86_64/aarch64）、macOS 和 WSL2 环境
- 注意：Linux 二进制依赖 glibc（x86_64 需 2.35+，arm64 需 2.38+），不支持 musl 发行版和 Android/Termux 原生运行

---
## 10. [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)
- **语言**: Python
- **Stars**: 52,860
- **简介**: DeepTutor: Lifelong Personalized Tutoring. https://deeptutor.info/.

### AI 总结
**简介**: DeepTutor 是香港大学数据智能实验室（HKUDS）开源的一款“终身个性化辅导”系统，基于 Python 构建，提供 Web 界面与 CLI 两种使用方式。

**核心功能**:
- 面向长期学习的个性化辅导，强调“终身”陪伴式教学体验
- 提供 Agent 原生的 CLI 接口，可直接在命令行中与辅导智能体交互
- 配套 EduHub 技能社区生态，支持扩展与共享教学技能
- 多语言文档支持（中、英、日、韩、法、德、阿、俄、印地、葡、泰、波等十余种语言）

**技术亮点**:
- 后端采用 Python 3.11+，前端基于 Next.js 16 构建
- Apache 2.0 开源许可，附有 arXiv 论文（2604.26962）说明技术方案
- 项目曾登上 GitHub Trending 日榜，社区活跃（Discord、飞书、微信群），并提供公开路线图供社区投票与共建

---
