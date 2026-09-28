---
tags:
  - github-trending
  - daily
date: 2026-09-28
created: 2026-09-28T01:55:41.980Z
---

# 2026-09-28 GitHub Trending Top 9

## 1. [paperclipai/paperclip](https://github.com/paperclipai/paperclip)
- **语言**: TypeScript
- **Stars**: 90,041
- **简介**: The open-source app everyone uses to manage agents at work

### AI 总结
**简介**: Paperclip 是一款开源的 AI 智能体团队管理应用，用 Node.js 服务端 + React 前端编排多个 AI 智能体协同完成业务目标。

**核心功能**:
- 定义业务目标并“雇佣”智能体团队（CEO、CTO、工程师、设计师、营销等），分配目标后统一跟踪工作与成本
- 支持接入多种智能体来源（OpenClaw、Claude Code、Codex、Cursor、Bash、HTTP），任何能接收心跳的智能体都可被纳入
- 提供组织架构、预算与治理、目标对齐、审批与审核门等机制，可 24/7 自主运行并随时审计
- 从仪表盘或手机端监控进度、成本与预算，像使用任务管理器一样管理智能体

**技术亮点**:
- 技术栈为 TypeScript / Node.js 服务端 + React UI
- 围绕四大支柱构建：任务、组织、训练与基础设施
- 采用 MIT 开源协议

---
## 2. [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight)
- **语言**: Python
- **Stars**: 37,435
- **简介**: Hindsight: Agent Memory That Learns

### AI 总结
**简介**: Hindsight 是一个让 AI Agent 能够随时间学习和进化的记忆系统，而非仅仅回忆对话历史。

**核心功能**:
- **记忆操作**: 提供 retain（保留）、recall（回忆）、reflect（反思）三种核心操作
- **多种记忆类型**: 支持 observations（观察）、mental models（心智模型）、knowledge pages（知识页面）等记忆形式
- **记忆库（Banks）**: 通过记忆库组织和管理 Agent 的记忆
- **灵活集成**: 支持 LLM Wrapper（2 行代码接入）、MCP Server、编码 Agent 等多种集成方式
- **多平台支持**: 提供 Python 嵌入式模式（无需服务器）、Docker 部署、Python/NPM 客户端

**技术亮点**:
- 在 LongMemEval 长期记忆基准测试中达到 SOTA 性能，超越 RAG 和知识图谱等方案
- 支持 25+ LLM 提供商（OpenAI、Anthropic、Gemini、Groq、Bedrock、VertexAI、DeepSeek 等），也支持本地模型（Ollama）
- 基准测试结果已由 Virginia Tech 和华盛顿邮报独立复现
- 已在财富 500 强企业和 AI 初创公司中投入生产使用
- 基于 Python 开发，采用 MIT 开源协议

---
## 3. [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio)
- **语言**: Python
- **Stars**: 40,271
- **简介**: VoiceStudio is the open-source, fully-local ElevenLabs alternative — voice cloning, voice design, video dubbing, dictation, transcription & audiobook creation in 646 languages.

### AI 总结
**简介**: VoiceStudio 是一个完全本地运行的开源 ElevenLabs 替代方案，支持 646 种语言的语音克隆、语音设计、视频配音、听写、转录和有声书制作。

**核心功能**:
- **语音克隆与设计**：克隆已有声音，或通过描述自定义设计声音
- **视频配音**：为视频添加带时间轴对齐的语音配音
- **听写与转录**：通过浮动小组件进行语音听写，支持音频转录
- **有声书与批量任务**：生成故事、有声书，支持批处理作业
- **本地 API 与 MCP**：为智能体提供本地 API 和 MCP 接口，支持可选的远程工作节点

**技术亮点**:
- 基于 Python 开发，默认引擎为 k2-fsa/OmniVoice，支持切换其他引擎
- 提供 Electron 桌面应用，支持 macOS / Linux 一键安装，另有 Windows 和 Docker 安装方式
- 所有本地工作流在用户自有硬件上运行，远程服务为可选，使用分析需用户授权
- 采用 AGPL-3.0 开源协议，CI/CD 流程完善

---
## 4. [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch)
- **语言**: Python
- **Stars**: 59,361
- **简介**: Learn it. Build it. Ship it for others.

### AI 总结
**简介**: 一个从零开始系统学习 AI 工程的开源课程项目，覆盖从数学基础到生产级 LLM 应用与智能体开发的完整路径。

**核心功能**:
- **523 节课程、20 个阶段、约 342 小时内容**，涵盖 Python、TypeScript、Rust、Julia 多语言实现
- **按目标选择学习路径**：新手基础、数学与 ML、LLM 工程、Agent 工程、编码智能体实战、MCP 协议等
- **每节课产出可复用工件**：提示词、技能、智能体、MCP 服务器
- **多语言支持**：提供简体中文、日语、韩语、西班牙语等 12 种语言的翻译页面
- **双端同步**：GitHub 与官网使用同一套课程代码

**技术亮点**: 采用 MIT 开源协议；以 Python 为主要语言，辅以 TypeScript、Rust、Julia；课程内容以阶段（phases）和 JSON 学习路径组织，支持机器翻译分支（`translations`）与多语言 i18n 架构。

---
## 5. [InfinityLoop1308/PipePipe](https://github.com/InfinityLoop1308/PipePipe)
- **语言**: Shell
- **Stars**: 6,597
- **简介**: An open-source Android app to let you browse YouTube and other services freely.

### AI 总结
**简介**: PipePipe 是一个基于 NewPipe 深度定制的开源 Android 应用，旨在让用户更自由、稳定地浏览 YouTube 及 BiliBili 等视频服务。

**核心功能**:
- **YouTube 增强**：集成 SponsorBlock 跳过赞助片段、ReturnYouTubeDislike 恢复 dislikes 显示、显示原始标题、登录访问受限/付费内容
- **媒体播放**：弹幕样式显示直播聊天、支持 AV1/VP9 编解码器、音乐播放器模式与后台播放
- **内容过滤**：高级搜索过滤器、按关键词或频道过滤、屏蔽 Shorts 和付费视频
- **播放控制**：滑动跳转与全屏手势、长按加速播放、睡眠定时器
- **播放列表增强**：一键下载完整播放列表、本地播放列表与历史记录内搜索排序

**技术亮点**: 采用硬分叉（hard fork）策略独立于 NewPipe 开发，可快速修复问题并高频更新功能；登录 Cookie 仅在指定场景（如 YouTube 播放流获取）中使用，保障隐私安全；支持 AV1/VP9 高效编解码。

---
## 6. [vercel-labs/scriptc](https://github.com/vercel-labs/scriptc)
- **语言**: TypeScript
- **Stars**: 5,418
- **简介**: TypeScript-to-Native Compiler

### AI 总结
**简介**: scriptc 是 Vercel Labs 推出的实验性 TypeScript/JavaScript 原生编译器，可将 TS/JS 代码编译为 IR、C、LLVM IR、汇编、原生可执行文件及 WebAssembly 模块。

**核心功能**:
- 将 TypeScript/JavaScript 编译为多种输出格式：类型化 IR、可读 C 代码、文本 LLVM IR、原生汇编、目标文件、原生可执行文件以及 WebAssembly 模块
- 支持静态编译，生成不依赖 Node 或 JS 引擎的原生可执行文件
- 对无法静态编译的代码（如 npm 包、`any` 类型）可通过 `--dynamic` 选项嵌入 quickjs-ng 运行时
- 提供 `scriptc coverage` 命令，展示程序静态编译覆盖率并给出诊断信息
- 支持常用 Node API（如 `node:http`）编译到原生运行时

**技术亮点**:
- 基于 TypeScript 编译器进行解析和类型检查
- 源码级输出（IR/C/LLVM）仅需 Node.js 24+，无需额外编译器
- 在 macOS 15+ arm64 上使用捆绑的 helper 和预编译运行时包，clang 仅作为平台链接驱动
- 静态构建包含小型原生运行时，不含 Node 或 JS 引擎
- 目标平台覆盖 macOS、Linux、Windows 及 WASI Preview 1 的 WebAssembly
- 采用 Apache-2.0 许可证

---
## 7. [mvschwarz/openrig](https://github.com/mvschwarz/openrig)
- **语言**: TypeScript
- **Stars**: 1,012
- **简介**: Multi-agent harness that runs Claude Code and Codex together as one system

### AI 总结
**简介**: OpenRig 是一个多智能体编排工具，将 Claude Code 和 Codex 等多个 AI 编码代理统一管理为一个持久化、有组织的团队系统。

**核心功能**:
- 通过 YAML 定义代理团队，一条命令即可启动整个 rig
- 支持 lead agent 协调跨团队专家，统一接收结果和待决策事项
- 提供共享 TUI 仪表盘，实时查看各代理的运行状态、模型、上下文和状态
- 内置任务队列系统，支持向指定代理发送任务并追踪执行结果
- 支持 Claude Code 与 Codex 在同一 rig 中协同工作，由 owner/checker 等角色分工

**技术亮点**:
- 基于 TypeScript 开发，通过 npm 包 `@openrig/cli` 分发
- 依赖 Node.js 20/22/24 及 tmux，支持 Bun 安装
- 启动时会写入 provider hooks 和 workspace trust 设置，需提前了解对机器的改动
- 提供 `--dry-run` 和 `--plan` 等安全预览机制，便于在正式应用前审查变更

---
## 8. [dream-num/univer](https://github.com/dream-num/univer)
- **语言**: TypeScript
- **Stars**: 20,363
- **简介**: The Office Harness for AI Agents — Spreadsheets, Docs, Slides, Canvas, Relational Tables, and PDF in one runtime.

### AI 总结
**简介**: Univer 是一个开源的高性能 Office SDK，用于在自有产品中嵌入电子表格、文档、演示等办公能力，并支持人与 AI Agent 在同一文件中协作。

**核心功能**:
- 支持电子表格、文档、演示、Bases、Boards 及即将推出的 PDF 等多种办公形态
- 可嵌入 SaaS、内部工具、BI 工作流或 AI 应用中，也可在服务端运行相同的处理架构
- 通过插件架构按需组合功能，支持预设快速启动
- 提供自定义插件、命令、服务、UI 组件和 Facade API 扩展能力
- 同一运行时支持跨工具内容组合与数据引用联动，人与 AI Agent 可协同编辑

**技术亮点**: 基于 TypeScript 开发，采用插件化架构与 Canvas 渲染，内置公式引擎，提供统一的 Facade API，可在浏览器和 Node.js 环境中运行。

---
## 9. [willfaust/Madeira](https://github.com/willfaust/Madeira)
- **语言**: C
- **Stars**: 826
- **简介**: Run x86-64 Windows PC games on jailed iOS via FEX-Emu + Wine + DXMT

### AI 总结
**简介**: Madeira 是一个在非越狱 iOS 设备上运行 x86-64 Windows PC 游戏的研究项目，通过 Wine + FEX-Emu + DXMT 组合实现。

**核心功能**:
- 在非越狱 iPhone 上运行 Windows PC 游戏
- 通过 FEX-Emu 实现 x86-64 → ARM64 指令翻译
- 通过 DXMT 实现 D3D11 → Metal 图形转换
- 以单一 Mach 进程运行，wineserver 作为线程而非独立进程

**技术亮点**:
- 技术栈：Wine (ARM64EC) + FEX-Emu + DXMT
- 需要 JIT，iOS 上依赖调试器附加（使用 StikDebug）
- 通过侧载安装，无法上架 App Store
- 免费 Apple ID 签名有效期为 7 天，需每周重装（容器保留，存档不丢失）
- 构建涉及多条链：Wine 库、ARM64EC PE 模块、FEX、DXMT 及 iOS 应用，使用 `xcodebuild` 构建
- 依赖子模块指向包含 iOS 适配的 fork，上游克隆无法直接构建
- 开发基于 A15 (iPhone 13 Pro)，Thumper 和 ULTRAKILL 可玩
- 许可证：GPL-3.0-or-later，fork 与上游许可不同（wine 重新许可为 GPL-3.0-or-later，FEX/dxmt 保留 MIT 但修改部分为 GPL-3.0-or-later）

---
