---
tags:
  - github-trending
  - daily
date: 2026-10-20
created: 2026-10-20T01:55:43.479Z
---

# 2026-10-20 GitHub Trending Top 10

## 1. [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)
- **语言**: Python
- **Stars**: 57,435
- **简介**: The job search that runs on your machine. AI job application framework built on Claude Code: evaluate postings, tailor CVs, write cover letters, prep interviews. Fork it and own it.

### AI 总结
**简介**: 一个基于 Claude Code 构建的 AI 求职申请框架，可本地运行，帮助用户评估职位、定制简历、撰写求职信并准备面试。

**核心功能**:
- `/setup`：填写个人档案，生成结构化的个人资料文件
- `/scrape`：搜索招聘门户（目前面向丹麦市场，如 Jobindex、Jobnet 等），返回带匹配度评分的职位列表
- `/apply <url>`：评估职位匹配度并打分，随后用 LaTeX 定制简历与求职信，经 Reviewer 代理评审、修订后输出终稿
- `/interview`：辅助面试准备
- 内置职业指导最佳实践，包括结构化评估标准、前瞻性求职信框架及可选薪资对标

**技术亮点**: 基于 Claude Code CLI 的代理工作流，采用"起草-审阅"双代理流水线；Python 3.10+ 与 Bun 构建 CLI 工具；使用 LaTeX（`lualatex` 编译简历、`xelatex` 编译求职信）生成定制文档；核心工作流与语言/国家无关，招聘门户搜索技能可按本地职位板替换；可选 `pypdf` 进行 ATS 可解析性检查。

---
## 2. [anomalyco/opencode](https://github.com/anomalyco/opencode)
- **语言**: TypeScript
- **Stars**: 217,863
- **简介**: The open source coding agent.

### AI 总结
**简介**: OpenCode 是一个用 TypeScript 编写的开源 AI 编程智能体，提供终端 UI 和桌面应用两种形态。

**核心功能**:
- 内置 **build**（默认，完整开发权限）和 **plan**（只读，用于代码分析与探索）两种智能体，可通过 `Tab` 键切换
- 提供 **general** 子代理，用于复杂搜索和多步骤任务，可在消息中通过 `@general` 调用
- 支持多种安装方式：安装脚本、npm/bun/pnpm/yarn、Homebrew、Pacman/AUR、mise、Nix
- 提供桌面应用（Beta），覆盖 macOS（Apple Silicon/Intel）、Windows 和 Linux（.deb/.rpm/.AppImage）

**技术亮点**: 基于 TypeScript 开发；安装脚本遵循 XDG 规范并支持自定义安装目录（`$OPENCODE_INSTALL_DIR`、`$XDG_BIN_DIR` 等）；文档提供 20 多种语言版本，社区活跃于 Discord。

---
## 3. [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory)
- **语言**: Rust
- **Stars**: 11,388
- **简介**: Solution for long term memory for agent coding CLIs and to facilitate handoff between different agent vendors

### AI 总结
**简介**: ai-memory 是一个用 Rust 编写的 AI 编码 Agent 长期记忆方案，让不同厂商的编码 CLI 共享同一份项目记忆，实现跨工具、跨项目、跨机器的任务交接。

**核心功能**:
- **跨 Agent 交接**：支持 Claude Code、Codex、Cursor、Gemini CLI 等 20+ 编码工具共享一份记忆，在任务中途切换 Agent 时自动交接进度、失败尝试和待解决问题（交接采用带所有者的类型化协议，每个交接只被认领一次）。
- **会话级续接**：通过 `ai-memory run` 启动 Agent，可携带上一 Agent 的共享工作流及本地原生历史的临时投影，精确续接细节；远程服务器仅接收工具与会话标识，不接触本地记录内容。
- **跨项目与跨机器**：用户工作习惯画像（包管理器、测试布局、架构习惯）会在每个新仓库会话启动时注入；记忆存放在自建服务器上，桌面端未完成的项目可在笔记本上原样恢复。
- **团队共享**：多人指向同一服务器即可按项目共享知识，个人交接保持私密，内置多用户认证、个人归属和审计日志（非付费功能）。
- **纯 Markdown 存储**：以 Git 版本管理的普通 `.md` 文件为唯一事实来源，可用 grep、Obsidian 或手工编辑，数据库仅为可随时重建的派生索引，无向量库。
- **静默捕获与零 LLM 依赖**：通过生命周期钩子自动记录提示、工具调用和会话边界，经类型化隐私边界清洗后入库；默认路径（捕获、搜索、交接）无需任何 API Key。
- **无 LLM 的记忆老化**：按可调层级曲线衰减记忆，被使用的记忆衰减更慢；冷记忆可压缩为持久事实（文件路径、错误码、决策），近重复合并、矛盾标记，全部零 API 调用，且不硬删除（原文保留在 Git 中可恢复）。
- **可选"做梦"整合**：配置 LLM 后可启用后台整合，在空闲时将冷笔记簇重写为连贯页面，不删除源版本、默认关闭，且需通过召回评测才可能成为默认行为。

**技术亮点**: 使用 Rust（1.95+）开发，MIT 许可；架构上采用 Git 支撑

---
## 4. [Comfy-Org/ComfyUI](https://github.com/Comfy-Org/ComfyUI)
- **语言**: Python
- **Stars**: 139,780
- **简介**: The most powerful and modular diffusion model GUI, api and backend with a graph/nodes interface. The fastest local inference engine in the world.

### AI 总结
**简介**: ComfyUI 是一款面向视觉专业人士的强大模块化 AI 创作引擎，通过节点图界面支持图像、视频、3D 模型、音频等多种内容的生成。

**核心功能**:
- 可视化节点图界面，无需编写代码即可构建和复用图像、视频、音频、3D 及文本工作流
- 支持子图复用、工作流模板、App Mode（将复杂工作流封装为简洁 UI）以及本地 API，便于集成到生产管线
- 原生支持大量最新开源模型（如图像生成的 SD1.5、SDXL、Flux.1、Qwen Image，图像编辑的 Flux Kontext、OmniGen2，以及视频生成等）
- 通过 Partner Nodes 接入 Nano Banana、Seedance、Hunyuan3D 等闭源模型
- 提供 Windows/Linux/macOS 桌面应用、便携安装包及官方云版本 Comfy Cloud

**技术亮点**: 采用异步队列、局部图重执行、智能 VRAM/RAM 管理、模型卸载及量化模型支持等优化技术；借助异步权重流式传输技术，可在低至 4GB 显存 + 8GB 内存的消费级硬件上较快运行大型开源模型，是当前针对扩散模型优化程度最高的本地推理引擎之一。

---
## 5. [ruvnet/ruflo](https://github.com/ruvnet/ruflo)
- **语言**: TypeScript
- **Stars**: 77,220
- **简介**: 🌊 The original agent harness. Deploy intelligent multi-player swarms, coordinate autonomous workflows, and build conversational AI systems. Features adaptive memory, self-learning intelligence, federation, vector RAG integration, and native Claude Code / Codex / Hermes and many more Integrated

### AI 总结
**简介**: Ruflo 是面向 Claude Code 和 Codex 的智能体元框架（agent meta-harness），用于部署多智能体协作集群、编排自主工作流并构建对话式 AI 系统。

**核心功能**:
- 多智能体集群部署与自主工作流协调
- 自适应记忆与自学习智能能力
- 联邦式架构与向量 RAG 集成
- 原生集成 Claude Code / Codex / Hermes 等多种 MCP 客户端
- 提供可视化控制台（Console）与终端 UI（TUI），可查看 Overview、Cost、Swarm、Events、Missions 等面板
- 通过插件市场快速安装（ruflo-core、ruflo-console、ruflo-mods）
- 可选 ruOS 桌面环境，支持通过 MCP 连接 ChatGPT 或 Claude

**技术亮点**: 基于 TypeScript 开发，以 npm 包形式分发（`npx ruflo`）；采用 MCP（Model Context Protocol）标准对接各类 AI 客户端，支持 stdio 本地服务器；模块化插件架构（Core / Console / Mods）实现基础工具、控制台与路由策略的分离；配套 RuVector 提供本地向量检索、持久化上下文与图关系记忆。

---
## 6. [stablyai/orca](https://github.com/stablyai/orca)
- **语言**: TypeScript
- **Stars**: 98,347
- **简介**: Orca is the place for working with a fleet of agents (e.g. Grok Bot, Claude Code). Run any coding agent with your own subscription. Available on desktop, mobile and remote runtime.

### AI 总结
**简介**: Orca 是一个 AI 智能体编排器，让开发者用自有订阅在桌面、移动端和远程运行时并行运行 Codex、Claude Code、OpenCode、Pi 等编码智能体。

**核心功能**:
- **并行 Worktree**：将同一提示分发给多个智能体，各自在独立的 git worktree 中运行，便于对比结果并合并优胜方案
- **移动伴侣应用**：通过 iOS/Android 手机监控和操控智能体，任务完成时接收通知并远程发送后续指令
- **终端分屏**：Ghostty 级终端，支持 WebGL 渲染、无限分屏，且重启后保留回滚历史
- **设计模式**：在真实 Chromium 窗口中点击任意 UI 元素，将其 HTML、CSS 和截图直接注入智能体提示词
- **GitHub 与 Linear 原生集成**：应用内浏览 PR、Issue 和项目看板，可从任务直接打开 worktree 并完成评审
- **SSH Worktree**：在远程高性能机器上运行智能体，支持完整文件编辑、git、终端、自动重连和端口转发

**技术亮点**: 基于 TypeScript 开发，采用 Electron 风格的跨平台桌面架构（支持 macOS/Windows/Linux），集成 WebGL 终端渲染与嵌入式 Chromium 浏览器，提供桌面端与移动端协同的远程运行时能力，项目采用 MIT 许可证。

---
## 7. [headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom)
- **语言**: Python
- **Stars**: 76,271
- **简介**: Compress tool outputs, logs, files, and RAG chunks before they reach the LLM. 20% fewer tokens for coding agents, 60-95% fewer tokens for JSON, same answers. Library, proxy, MCP server.

### AI 总结
**简介**: Headroom 是一个在内容进入 LLM 之前进行上下文压缩的本地化工具，可显著减少 token 消耗（编码代理约减少 20%，JSON 减少 60-95%）且保持回答质量不变。

**核心功能**:
- 多种接入方式：Python/TypeScript 库、代理模式（`headroom proxy`）、一行命令包装主流代理工具（Claude、Codex、Cursor、Aider 等）、MCP 服务器
- 压缩对象覆盖工具输出、日志、文件、RAG 片段和对话历史
- 跨代理共享记忆存储（Claude、Codex、Gemini、Grok），自动去重
- `headroom learn` 挖掘失败会话并生成修正建议写入配置文件
- 输出 token 压缩（减少模型回写内容）
- 可逆压缩（CCR）：原始内容本地缓存，按需检索

**技术亮点**: 采用流水线架构（CacheAligner → ContentRouter → CCR），内置 SmartCrusher（JSON 处理）、CodeCompressor（基于 AST 的代码压缩）和 Kompress-v2-base（HuggingFace 文本压缩模型）；所有压缩在本地完成，数据不外传；提供 Apache 2.0 开源许可，同时发布 PyPI 和 npm 包。

---
## 8. [withmarbleapp/os-taxonomy](https://github.com/withmarbleapp/os-taxonomy)
- **语言**: JavaScript
- **Stars**: 6,162
- **简介**: 

### AI 总结
**简介**: Marble 发布的开放儿童学习技能分类体系，将小学阶段的学习内容拆解为细粒度微主题并构建先修依赖图，对齐多国课程标准。

**核心功能**:
- **微主题图谱**：1,591 个可教学微主题（涵盖科学、数学、英语等 8 个学科），每个主题包含描述、掌握证据标准、类型、学科领域与适龄范围
- **先修依赖图**：3,225 条有向无环依赖边，标注 `hard`/`soft` 强度及一句话理由，可反向推导"解锁"关系
- **课程标准对齐**：每个微主题关联其来源标准（NGSS、Common Core、英国国家课程等）
- **教学研究数据**：覆盖科学与数学共 1,051 条记录，含教学法、学习活动、反馈与评估指导（部分主题暂无覆盖）
- **领域摘要**：176 条面向家长的分学科、分年龄段段落式概述
- **结构化数据文件**：全部数据以 UTF-8 JSON 存于 `data/`，附 JSON Schema 与含 SHA-256 校验和的 manifest

**技术亮点**: 采用图数据结构（节点 + 有向无环边）建模学习路径；数据以纯 JSON 文件分发并提供 JSON Schema 校验；主语言为 JavaScript；通过 `topicId` 外键关联主题、依赖、标准与教学研究，便于程序化消费与二次开发。

---
## 9. [Kruk2/jasna](https://github.com/Kruk2/jasna)
- **语言**: Python
- **Stars**: 2,926
- **简介**: Video restoration tool

### AI 总结
**简介**: Jasna 是一款基于 GPU 运行的免费视频与图像马赛克修复工具，提供图形界面和命令行两种使用方式。

**核心功能**:
- 自动检测视频中的马赛克区域并仅修复该区域，画面其余部分保持不变
- 提供两种修复模型：免费的快速模型 **BasicVSR++**，以及面向支持者、更注重细节的 **LTX**（仅限 NVIDIA）
- 内置 Segment Editor，可预览并手动选择只修复指定片段
- 支持 VR180 视频与静态图片修复（SD 1.5，面向支持者）
- Video Player 支持实时预览修复效果，无需先导出文件

**技术亮点**:
- 基于 Python 开发，依赖 GPU 加速：NVIDIA GTX 16 系 / RTX 20 系及以上（计算能力 7.5+），AMD RX 7000/9000 为实验性支持
- 首次运行会针对本机 GPU 编译优化模型，耗时约 15–60 分钟，之后可复用 `model_weights` 目录
- 对磁盘与路径有要求：需本地 SSD、英文路径，不支持网络磁盘
- 采用免费基础模型 + 付费支持者模型（UNet 4x、SD 1.5、LTX）的许可模式，许可证仅通过官方渠道获取

---
## 10. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 55,273
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: HKUDS/CLI-Anything 是一个旨在为任意软件生成 CLI（命令行接口）工具的项目，让 AI Agent 能够直接调用和操作各类软件，实现"软件 Agent 原生"。

**核心功能**:
- 为各类软件自动生成可被 AI Agent 调用的 CLI 工具，支持 Pi、OpenClaw、nanobot、Cursor、Claude Code 等 Agent 平台
- 提供 CLI-Hub 社区中心（`pip install cli-anything-hub` + `cli-hub install <name>`），可浏览、安装和管理社区构建的 CLI
- 支持预览、实时预览和轨迹循环，帮助 Agent 产出真实成果（如 CAD 构建、3D 场景、图表、游戏玩法、字幕等）
- 开放贡献机制：可提交 PR 添加自己的 CLI，或提交 wishlist 请求支持特定软件

**技术亮点**: 基于 Python（≥3.10）开发，使用 Click 构建命令行界面，pytest 测试覆盖率与端到端测试全部通过（2,461 项测试通过），输出支持 JSON 与人类可读双格式；采用 Apache 2.0 开源协议，并提供 arXiv 技术报告。

---
