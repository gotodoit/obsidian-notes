---
tags:
  - github-trending
  - daily
date: 2026-10-08
created: 2026-10-08T01:55:42.126Z
---

# 2026-10-08 GitHub Trending Top 10

## 1. [morluto/rea](https://github.com/morluto/rea)
- **语言**: TypeScript
- **Stars**: 15,495
- **简介**: Reverse engineer anything with agents, from app behavior down to native binaries.

### AI 总结
**简介**: REA 是一个基于 MCP 协议的反向工程工具，让 AI Agent 能够从应用行为一直分析到原生二进制层面，帮助开发者理解和复现任意软件功能。

**核心功能**:
- 通过 Agent 调查应用功能，无需源代码即可解释实现原理并生成可用的替代版本
- 支持多种分析目标：原生二进制、JavaScript/Electron 应用、.NET 程序集以及网站
- 提供终端直接调用能力，分析在本地运行，并附带结论背后的证据与局限性说明
- 支持 Hopper、Ghidra 等原生分析引擎，静态 JavaScript 分析无需额外引擎
- 兼容 Claude Code、Cursor、Gemini CLI、VS Code 等多种主流 AI 编程助手

**技术亮点**: 基于 TypeScript 开发，采用 MCP（Model Context Protocol）作为 Agent 与工具间的通信标准；通过 `npx rea-agents setup` 一键注册并配置工作流指令，安装过程会展示变更、备份配置并需用户确认；要求 Node.js 22.19+，采用 MIT 许可证。

---
## 2. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 279,666
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: Matt Pocock 分享的日常工程用 AI Agent 技能集，主打小巧、可组合、可自由改造，适用于任何模型。

**核心功能**:
- 提供 `/grill-me`、`/grill-with-docs` 等技能，通过"拷问式"提问帮 Agent 理清需求，解决人机沟通偏差
- 提供 `/triage` 等技能，结合 issue tracker（GitHub、GitLab、本地文件等）和标签进行工单分类
- 通过 `setup-matt-pocock-skills` 一次性配置每个仓库的 issue tracker、标签习惯和文档存放位置

**技术亮点**:
- 双安装路径：Claude Code 官方插件市场（只读托管、自动更新）与 skills.sh（复制可编辑文件到项目，便于魔改）
- 支持任意 Agent（Claude Code、Codex 等），通过 `npx skills@latest add mattpocock/skills` 安装
- 定位为"真正的工程"而非"氛围编程"，强调小、易适配、可组合，避免 GSD/BMAD/Spec-Kit 那种接管流程、难以调试的模式

---
## 3. [boykopovar/AnyPS5](https://github.com/boykopovar/AnyPS5)
- **语言**: C++
- **Stars**: 10,734
- **简介**: Tool for automatic PS5 executables porting to Linux and Windows

### AI 总结
**简介**: AnyPS5 是一款用 C++ 编写的工具，可将 PS5 可执行文件自动移植到 Linux 和 Windows 平台，无需模拟器或独立运行时进程。

**核心功能**:
- 通过 relinker 将 PS5 可执行文件转换为目标系统的原生格式
- 提供系统 prx 库实现，支持动态链接
- 支持 SDL 映射的游戏手柄（含摇杆和扳机），可通过 `anyps5-input.ini` 配置键鼠操作
- 着色器重编译器可生成经 Spirv-Tools 验证的 SPIR-V

**技术亮点**: 采用原生格式转换与动态链接方案，而非模拟器架构；未支持状态严格抛出 `std::runtime_error` 并输出至 stderr 后终止进程；项目采用 GPLv2 许可，定位为互操作性、研究与兼容性用途。

---
## 4. [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)
- **语言**: Python
- **Stars**: 55,157
- **简介**: A skill to stop your coding agent from burying the answer. ADHD-friendly output.

### AI 总结
**简介**: 一个让编码 AI 助手输出更简洁直接的技能插件，避免把答案埋在冗长废话里，适合注意力容易分散的开发者。

**核心功能**:
- 强制 AI 先给行动建议，多步骤任务用编号列表呈现
- 每轮对话末尾给出一个具体的下一步操作
- 抑制无关话题、限制列表不超过 5 项、给出具体时间估算（分钟而非“一会儿”）
- 去除客套开场白、总结和结尾寒暄（如“Hope this helps!”）
- 错误信息直接陈述，不绕弯子

**技术亮点**: 基于 Python 实现，以 Claude 插件/技能形式安装（`SKILL.md` 定义 10 条输出规则）；支持多语言 README；可 fork 后自定义规则并替换上游插件。

---
## 5. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 45,028
- **简介**: Editorial diagram design for Claude Code, Codex, GitHub Copilot, Factory Droid, and Pi. 42 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 为 AI 编程助手提供编辑级品质图表设计的技能包，用自包含 HTML + SVG 替代 Mermaid 等工具生成的“通用圆角框”图表。

**核心功能**:
- 支持 42 种图表类型，涵盖架构图、流程图、时序图、状态机、ER 图、时间线、泳道图、象限图、雷达图、Sankey、鱼骨图、Wardley 图、看板、用户旅程、部署图、依赖图、UML 类图、故事地图、数据库 Schema 等
- 每种图表提供三种静态变体：极简亮色、极简暗色、完整编辑风格，可直接在浏览器打开，无需构建步骤
- 语义模式将行为描述与布局解耦，队列、策略追踪、信任边界等可复用最近似类型而无需扩充类型数量
- 可将 draw.io、Mermaid 或 Excalidraw 源文件按指定格式、尺寸和细节级别重绘
- 通过读取用户网站，60 秒内匹配品牌风格

**技术亮点**:
- 纯 HTML + SVG 输出，无阴影、无 JavaScript、无外部图片依赖、无构建步骤
- 静态输出为默认模式，可选无障碍动效用于有序说明
- 兼容 Claude Code、Codex、GitHub Copilot、Factory Droid、Pi 及 Agent Skills 兼容宿主
- 设计理念强调“删除优先”，强调色仅用于 1–2 个核心焦点，目标信息密度为 4/10
- 2.0 引入带共享记忆中枢的飞轮（Loop）模式，虚线表示回写

---
## 6. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 102,847
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 为 AI 编码代理提供生产级工程技能库，将资深工程师的工作流、质量门禁和最佳实践打包成可复用技能，让 AI 在开发全流程中保持一致行为。

**核心功能**:
- **9 个斜杠命令覆盖开发生命周期**：`/spec`（定义需求）、`/plan`（拆解任务）、`/build`（增量构建）、`/test`（测试验证）、`/constraints`（质量约束）、`/review`（合并前审查）、`/webperf`（性能审计）、`/code-simplify`（代码简化）、`/ship`（发布上线）
- **技能自动激活**：根据当前任务类型自动触发对应技能，如设计 API 触发接口设计技能、构建 UI 触发前端工程技能
- **`/build auto` 自主模式**：一次批准计划后可自动实现所有任务，仍保持测试驱动和逐任务提交，遇失败或高风险步骤暂停
- **灵活安装方式**：支持 `npx skills` 命令行一键安装（适配 70+ 代理工具），也支持 Claude Code、Cursor 等原生集成

**技术亮点**: 基于 JavaScript 实现，以技能（Skill）为核心单元组织工程知识；提供 25 个预置技能，涵盖代码审查、需求访谈、测试驱动开发等；通过技能 CLI 实现跨工具可移植性，兼容 Claude Code、Cursor、Codex、Copilot、Cline 等主流 AI 编码代理。

---
## 7. [EpicGames/raddebugger](https://github.com/EpicGames/raddebugger)
- **语言**: C
- **Stars**: 7,874
- **简介**: A native, user-mode, multi-process, graphical debugger.

### AI 总结
**简介**: Epic Games 推出的原生、用户态、多进程图形化调试器，目前处于 Alpha 阶段，主要支持 Windows x64 本地调试。

**核心功能**:
- 支持 Windows x64 本地调试，基于 PDB 调试信息
- 多进程、图形化调试体验
- 配套 `radbin` 工具，可将 PDB 等原生调试信息转换为自定义 RDI 格式
- 附带 RAD Linker 性能链接器，用于生成 x64 PE/COFF 二进制文件，兼容 MSVC 命令行语法

**技术亮点**:
- 使用 C 语言开发，强调原生性能
- 自定义 RAD Debug Info (RDI) 格式替代 PDB/DWARF，支持按需转换
- RAD Linker 针对超大项目优化，测试中链接速度提升约 50%；启用大内存页后可再提升约 25%
- 计划未来支持 Linux 原生调试与 DWARF 调试信息

---
## 8. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 97,749
- **简介**: Persistent Context Across Sessions for Every Agent – Captures everything your agent does during sessions, compresses it with AI, and injects relevant context back into future sessions. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode + More

### AI 总结
生成总结时发生错误。

---
## 9. [manaflow-ai/cmux](https://github.com/manaflow-ai/cmux)
- **语言**: Swift
- **Stars**: 27,860
- **简介**: Open source Ghostty-based macOS terminal with vertical tabs and notifications for AI coding agents. Built for multitasking, organization, and programmability.

### AI 总结
**简介**: cmux 是一款基于 Ghostty 构建的开源 macOS 终端，专为 AI 编程代理设计，提供垂直标签页和通知功能，面向多任务处理、组织管理和可编程性。

**核心功能**:
- **通知环与通知面板**：当编程代理需要关注时，窗格显示蓝色光环、标签页亮起；所有待处理通知集中展示，可快速跳转到最近未读项
- **垂直 + 水平标签页**：侧边栏显示 git 分支、关联 PR 状态/编号、工作目录、监听端口及最新通知文本，支持水平和垂直分屏
- **内置浏览器**：可与终端并排分屏，提供从 agent-browser 移植的可脚本化 API
- **SSH 支持**：`cmux ssh user@remote` 为远程机器创建工作区，浏览器窗格走远程网络，拖拽图片可通过 scp 上传
- **Claude Code Teams**：`cmux claude-teams` 一键运行 Claude Code 队友模式，队友以原生分屏形式启动，无需 tmux
- **浏览器导入**：从 Chrome、Firefox、Arc 等 20+ 浏览器导入 cookie、历史记录和会话
- **自定义命令**：通过 `cmux.json` 定义项目专属操作，从命令面板启动
- **可编程**：提供 CLI 和 socket API，可创建工作区、分屏、发送按键及自动化浏览器

**技术亮点**:
- 使用 Swift 和 AppKit 构建的原生 macOS 应用，非 Electron，启动快、内存占用低
- 兼容 Ghostty，读取现有 `~/.config/ghostty/config` 中的主题、字体和颜色配置
- 由 libghostty 提供 GPU 加速渲染，画面流畅
- 提供丰富的键盘快捷键支持

---
## 10. [trycua/cua](https://github.com/trycua/cua)
- **语言**: Rust
- **Stars**: 28,770
- **简介**: Scale computer-use 2.0 with open-source drivers, cross-OS fleets, and benchmarks for training, evaluation, and data generation.

### AI 总结
**简介**: Cua 是一套面向 Computer-Use 2.0 的开源工具链，为 AI Agent 提供可操作的完整桌面环境，覆盖驱动、虚拟机、决策模型与评测基准。

**核心功能**:
- **Cua Spaces**: 桌面应用，在 Mac、自有机器或自有云账户（AWS/GCP/Modal）上为 Agent 创建完整桌面（macOS/Linux/Omarchy 镜像），支持应用「传送」保持登录态、人机多光标协同操作。
- **Cua Driver**: 跨 macOS、Windows、Linux 的桌面自动化驱动，可检视并操作本地应用。
- **Lume**: 在 Apple Silicon 上本地运行 macOS 和 Linux 虚拟机。
- **Cua Bench**: 创建任务、评测 Agent 并导出轨迹，用于训练、评估与数据生成。
- **CUA-S1**: 面向计算机操作决策的小型专用模型。
- **Cua SDK 与 CLI**: 安装 `cua` 命令行工具并创建本地沙盒。

**技术亮点**: 以 Rust 为主要语言，提供跨操作系统（macOS/Windows/Linux）的驱动与虚拟机方案；支持自带 Agent 和模型，也可使用专用 CUA-S1 模型；通过 Cua Keyvault 在本地加密保存会话凭据，仅在用户批准后向 Space 开放；镜像内置 `cua-spacesd`，Space 启动即向 Agent 暴露进程、文件、截图和输入能力。

---
