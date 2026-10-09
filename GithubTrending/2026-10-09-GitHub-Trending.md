---
tags:
  - github-trending
  - daily
date: 2026-10-09
created: 2026-10-09T01:55:41.806Z
---

# 2026-10-09 GitHub Trending Top 9

## 1. [boykopovar/AnyPS5](https://github.com/boykopovar/AnyPS5)
- **语言**: C++
- **Stars**: 15,977
- **简介**: Tool for automatic PS5 executables porting to Linux and Windows

### AI 总结
**简介**: AnyPS5 是一个用 C++ 编写的工具，可将 PS5 可执行文件自动移植到 Linux 和 Windows 平台，无需模拟器或独立运行时进程。

**核心功能**:
- 通过 relinker 将 PS5 可执行文件转换为目标系统的原生格式
- 提供系统 prx 库实现，支持动态链接
- 支持 SDL 映射的游戏手柄（含摇杆和扳机），并可通过 `anyps5-input.ini` 配置键鼠操作
- 着色器重编译器可生成 SPIR-V（可选 Spirv-Tools 验证）

**技术亮点**: 采用原生格式转换与动态链接方案而非模拟器；不支持的状态严格抛出 `std::runtime_error` 并终止进程；已有一款 2D 平台游戏（Dreaming Sarah）在 GTX 1050 Ti / i5-7500 上稳定 60 fps 运行；项目采用 GPLv2 许可，定位为互操作性、研究与兼容性用途。

---
## 2. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 46,443
- **简介**: Editorial diagram design for Claude Code, Codex, GitHub Copilot, Factory Droid, and Pi. 42 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一套面向 AI 编程助手（Claude Code、Codex、GitHub Copilot 等）的编辑级图表设计技能，提供 42 种自包含 HTML + SVG 图表类型，拒绝 Mermaid 式粗糙输出。

**核心功能**:
- 覆盖 42 种图表类型，包括架构图、流程图、时序图、状态机、ER 图、时间线、泳道图、象限图、雷达图，以及 Sankey、鱼骨图、Wardley 地图、看板、用户旅程、UML 类图、数据库 Schema 等
- 每种图表提供三种静态变体：极简浅色、极简深色、完整编辑风格，可直接在浏览器中打开
- 通过语义模式（semantic patterns）将行为描述与布局分离，队列、策略追踪、信任边界等可复用现有类型而无需新增图表种类
- 支持将 draw.io、Mermaid、Excalidraw 源文件按指定格式、尺寸和细节级别重绘
- 读取网站即可在 60 秒内匹配品牌配色

**技术亮点**: 纯 HTML + SVG 自包含输出，无构建步骤、无 JavaScript、无外部图片依赖；静态输出为默认模式，可选无障碍动效用于有序讲解；强调克制的设计原则——无阴影、无通用圆角框，目标信息密度 4/10，强调色仅保留给最需关注的 1–2 个元素。

---
## 3. [morluto/rea](https://github.com/morluto/rea)
- **语言**: TypeScript
- **Stars**: 27,306
- **简介**: Reverse engineer anything with agents, from app behavior down to native binaries.

### AI 总结
**简介**: REA 是一个基于 TypeScript 的逆向工程工具，通过 MCP 协议让 AI Agent 能够分析原生二进制、应用程序及运行时行为，帮助开发者理解任意软件功能的实现原理。

**核心功能**:
- 支持分析原生二进制文件（Native Binaries）、JavaScript/Electron 应用、.NET 程序集以及网站
- 通过 MCP 将逆向工具接入 AI Agent（如 Claude Code、Cursor、Gemini CLI 等），实现对话式逆向分析
- 同时提供终端 CLI 命令，可独立使用（如 `analyze-javascript-application`）
- 分析结果附带证据链和局限性说明，确保结论可追溯
- 本地运行分析，保护隐私

**技术亮点**:
- 基于 MCP（Model Context Protocol）架构，可无缝集成多种主流 AI 编程助手
- 原生分析可对接 Hopper 或 Ghidra 等现有逆向引擎
- 静态 JavaScript 分析无需额外引擎依赖
- 要求 Node.js 22.19+，通过 `npx rea-agents setup` 一键完成配置
- 提供多语言文档支持，采用 MIT 开源协议

---
## 4. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 281,169
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: Matt Pocock 分享的日常真实工程开发用 AI Agent 技能集合，强调小巧、可组合、可自由改造，而非"氛围编程"。

**核心功能**:
- 提供 `/grill-me` 和 `/grill-with-docs` 等技能，通过"拷问式对话"让 Agent 在动手前充分对齐需求，解决沟通偏差这一最常见失败模式
- 支持 Claude Code、Codex、GitHub Copilot、Gemini CLI 及其他 Agent 的一键或手动安装，并提供 `/setup-matt-pocock-skills` 完成仓库级初始化（选择 issue 追踪器、标签、文档路径）
- 技能按工程（engineering）与效率（productivity）分类，可随项目复制为可编辑文件，便于按需修改

**技术亮点**: 以 Shell 为主实现，设计上强调小型化与可组合性，不绑定特定模型；通过插件市场自动更新或 `npx skills` 手动管理，兼容多种主流编码 Agent 生态。

---
## 5. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 98,514
- **简介**: Persistent Context Across Sessions for Every Agent – Captures everything your agent does during sessions, compresses it with AI, and injects relevant context back into future sessions. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode + More

### AI 总结
生成总结时发生错误。

---
## 6. [EpicGames/raddebugger](https://github.com/EpicGames/raddebugger)
- **语言**: C
- **Stars**: 8,127
- **简介**: A native, user-mode, multi-process, graphical debugger.

### AI 总结
**简介**: RAD Debugger 是 Epic Games 开发的一款原生、用户态、多进程图形化调试器，目前处于 Alpha 阶段，主要面向 Windows x64 本地调试。

**核心功能**:
- 支持本地 Windows x64 调试，基于 PDB 调试信息
- 多进程调试能力，原生用户态图形界面
- 配套 RAD Debug Info (RDI) 自定义调试信息格式，可按需将 PDB 转换为 RDI
- 配套 RAD Linker 高性能链接器，专为超大型可执行文件设计，生成标准 PDB 并可原生输出 RDI
- 提供 `radbin` 工具，支持调试信息格式转换与文本转储

**技术亮点**:
- 使用 C 语言开发，采用自研 RDI 调试信息格式替代直接解析 PDB/DWARF
- RAD Linker 针对巨型项目优化，测试中链接速度提升 50%，启用大内存页可再提速 25%
- 链接器命令行语法完全兼容 MSVC，默认按 CPU 核心数多线程链接
- 未来计划支持 Linux 原生调试、DWARF 调试信息及链接器的 Linux 移植

---
## 7. [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)
- **语言**: Python
- **Stars**: 27,619
- **简介**: Open source repository of plugins primarily intended for knowledge workers to use in Claude Cowork

### AI 总结
**简介**: Anthropic 开源的面向知识工作者的 Claude 插件集合，为不同职能角色提供专业技能、工具连接和自动化工作流。

**核心功能**:
- 提供 11 个开箱即用的角色插件，覆盖销售、产品管理、市场营销、法务、财务、数据分析、客户支持、企业搜索、生物研究等领域
- 每个插件捆绑技能（Skills）、连接器（Connectors）、斜杠命令（Commands）和子代理，针对特定职能定制
- 支持通过 MCP 协议连接外部工具（如 Slack、Notion、Jira、HubSpot、Snowflake 等）
- 支持安装现成插件或基于自身公司工具与流程进行自定义扩展

**技术亮点**:
- 基于 Python 开发，采用统一的文件化插件结构（`plugin.json` 清单 + `.mcp.json` 工具连接 + `commands/` + `skills/`）
- 通过 MCP（Model Context Protocol）实现与外部工具和数据的标准化集成
- 同时兼容 Claude Cowork 和 Claude Code，支持通过 CLI 安装（`claude plugin marketplace add` / `claude plugin install`）
- 技能自动触发，斜杠命令显式调用，插件安装后自动激活

---
## 8. [storytold/artcraft](https://github.com/storytold/artcraft)
- **语言**: Rust
- **Stars**: 8,106
- **简介**: ArtCraft is an intentional crafting engine for artists, designers, and filmmakers

### AI 总结
**简介**: ArtCraft 是一款面向艺术家、设计师和影视创作者的可控 AI 图像与视频创作引擎，以“艺术家的 IDE”为定位，将提示词生成转变为可视化、可复现的创作流程。

**核心功能**:
- **Image to Location**：将虚拟角色置于一致的环境中，支持在同一场景内规划多个镜头
- **3D 图像合成**：在 3D 空间中分层布置背景、前景和道具，构建具有纵深的构图
- **2D 图像合成**：通过图层、背景去除和绘图工具组合场景
- **图像转 3D 网格**：将图片转为可精确摆放、旋转和取景的 3D 对象
- **角色姿态控制**：在生成最终镜头前，先摆好角色姿态并设置相机
- **Kitbashing 场景布局**：组合 3D 资产套件，控制相机角度、物体位置和景深

**技术亮点**: 使用 Rust 语言开发；支持 2D 合成与 3D 场景搭建相结合的工作流；可自由选择适配的 AI 模型，强调精确、可重复的创作结果。

---
## 9. [liquidslr/system-design-notes](https://github.com/liquidslr/system-design-notes)
- **语言**: Unknown
- **Stars**: 24,669
- **简介**: Notes of the book System Desgin Interview - An Insider's Guide

### AI 总结
**简介**: 该项目是《System Design Interview - An Insider's Guide》一书的学习笔记整理。

**核心功能**:
- 整理系统设计面试相关的核心知识点
- 提供书中重要概念的笔记与总结

**技术亮点**: 以笔记形式呈现，内容围绕系统设计面试方法论与案例展开。

---
