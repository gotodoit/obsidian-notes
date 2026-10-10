---
tags:
  - github-trending
  - daily
date: 2026-10-10
created: 2026-10-10T01:55:42.149Z
---

# 2026-10-10 GitHub Trending Top 10

## 1. [morluto/rea](https://github.com/morluto/rea)
- **语言**: TypeScript
- **Stars**: 47,551
- **简介**: Reverse engineer anything with agents, from app behavior down to native binaries.

### AI 总结
**简介**: REA 是一个基于 MCP 协议的逆向工程工具，让 AI 智能体能够分析二进制文件、应用程序和运行时行为，帮助开发者理解任意软件功能的实现原理。

**核心功能**:
- 通过智能体逆向分析原生二进制、JavaScript/Electron 应用、.NET 程序集及网站
- 支持从应用行为到二进制级别的功能还原与证据追踪
- 提供 CLI 命令行工具，可在终端直接分析 JavaScript/Electron 应用目录或 ASAR 包
- 一键集成主流 AI 智能体（Claude Code、Codex、Cursor、Gemini CLI 等）

**技术亮点**:
- 使用 TypeScript 开发，通过 npm 包 `rea-agents` 分发
- 基于 MCP（Model Context Protocol）协议连接智能体与逆向工具
- 本地化分析，结果附带证据与局限性说明
- 原生分析可对接 Hopper、Ghidra、IDA 等现有工具，静态 JS 分析无需原生引擎

---
## 2. [boykopovar/AnyPS5](https://github.com/boykopovar/AnyPS5)
- **语言**: C++
- **Stars**: 22,539
- **简介**: Tool for automatic PS5 executables porting to Linux and Windows

### AI 总结
**简介**: AnyPS5 是一个用 C++ 编写的工具，可将 PS5 可执行文件自动移植到 Linux 和 Windows 平台。

**核心功能**:
- 通过 relinker 将 PS5 可执行文件转换为目标系统的原生格式
- 提供系统 prx 库实现，支持动态链接，无需模拟器或独立运行时进程
- 包含着色器重编译器，可生成并验证 SPIR-V
- 支持 SDL 映射的游戏手柄（含摇杆和扳机），以及通过 `anyps5-input.ini` 配置键鼠操作

**技术亮点**: 采用重链接与原生动态链接方案而非模拟运行；不支持的状态会严格抛出 `std::runtime_error` 并终止进程；已有一款 2D 平台游戏（Dreaming Sarah）在 GTX 1050 Ti / i5-7500 上稳定 60 fps 运行；采用 GPLv2 许可，项目定位为互操作性、研究与兼容性用途。

---
## 3. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 282,789
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: Matt Pocock 开源的 AI 编码代理技能集，旨在用小型、可组合、可定制的技能替代 GSD、BMAD、Spec-Kit 等重型流程框架，帮助工程师进行真正的工程开发而非“氛围编程”。

**核心功能**:
- **需求对齐（Grilling 会话）**: 通过 `/grill-me` 和 `/grill-with-docs` 让代理在动手前详细追问需求，解决人与代理之间的沟通偏差问题
- **多代理支持**: 提供 Claude Code、Codex、GitHub Copilot、Gemini CLI 等主流代理的一键安装方式，也支持 Cursor、Windsurf 等其他代理
- **快速初始化**: 每个仓库运行一次 `/setup-matt-pocock-skills`，配置问题追踪器（GitHub/GitLab/本地文件）、分类标签和文档保存位置
- **自动/手动更新**: 插件方式自动更新，`skills.sh` 方式复制可编辑文件到项目中手动维护

**技术亮点**:
- 技能设计强调**小、易改、可组合**，不绑定特定模型，基于数十年工程经验
- 拒绝“框架接管流程”的思路，保留开发者对流程的控制权，避免流程本身产生难以排查的 bug
- 以 Shell 为主，通过插件市场（Claude Plugins、Codex Marketplace、Copilot Marketplace）分发，安装配置约 30 秒完成

---
## 4. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 47,937
- **简介**: Editorial diagram design for Claude Code, Codex, GitHub Copilot, Factory Droid, and Pi. 42 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个面向 AI 编程代理的图表设计技能，用自然语言生成品牌化的自包含 HTML+SVG 编辑风格图表。

**核心功能**:
- 支持 42+ 种图表类型（架构图、象限图、时序图等），由代理自动选择类型并规划后输出单个 `.html` 文件
- 可通过自然语言指令生成，例如"为我的应用画一张架构图"
- 支持从指定网站抓取配色和字体，使所有图表自动匹配品牌风格
- 兼容 Claude Code、Codex、GitHub Copilot、Cursor、Gemini CLI、Cline、Windsurf 等多种代理宿主

**技术亮点**:
- 输出为自包含的 HTML + SVG 单文件，双击即可打开，无需外部依赖
- 内置设计规则（无阴影、拒绝 Mermaid 式粗糙风格），强调编辑级排版美感
- 通过 `npx skills` CLI 跨宿主安装，支持符号链接实现一处更新多处生效
- 提供插件市场安装方式（Claude Code、Codex、Copilot、Factory Droid），支持自动更新与斜杠命令

---
## 5. [alibaba/open-code-review](https://github.com/alibaba/open-code-review)
- **语言**: Go
- **Stars**: 45,282
- **简介**: Secure, fast, efficient, battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level comments, built-in multi-language ruleset (NPE, thread-safety, XSS, SQL injection), OpenAI & Anthropic compatible.

### AI 总结
**简介**: 阿里巴巴开源的企业级 AI 代码审查 CLI 工具，源自其内部官方 AI 代码审查助手，经大规模实战验证后开源。

**核心功能**:
- 读取 Git diff，通过具备工具调用能力的 Agent 将变更文件发送给可配置的 LLM，生成精确到行级的结构化审查评论
- Agent 可读取完整文件内容、搜索代码库、检查其他变更文件以获取上下文，产出深度审查而非表层 diff 反馈
- `ocr scan` 命令支持审查整个文件，适用于审计陌生代码库或无有意义 diff 的目录
- 内置多语言规则集，覆盖 NPE、线程安全、XSS、SQL 注入等常见缺陷

**技术亮点**:
- 采用混合架构：确定性流水线 + LLM Agent
- 兼容 OpenAI 与 Anthropic 模型接口，仅需配置模型端点即可使用
- 基于 Go 语言开发，支持 Windows/macOS/Linux 平台，并适配 Claude Code、Codex、Cursor、Kimi Code 等 Agent
- 在 50 个开源仓库、200 个真实 PR、10 种编程语言的基准测试中，相比通用 Agent（Claude Code）精度与 F1 显著更高，Token 消耗仅约 1/9，审查速度更快（以略低的召回率换取更高的精度）

---
## 6. [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)
- **语言**: Python
- **Stars**: 28,291
- **简介**: Open source repository of plugins primarily intended for knowledge workers to use in Claude Cowork

### AI 总结
**简介**: Anthropic 开源的面向知识工作者的 Claude Cowork 插件集合，将 Claude 定制为特定职能领域的专家助手。

**核心功能**:
- 提供 11 个开箱即用的职能插件，覆盖销售、产品管理、市场营销、法务、财务、数据分析、客户支持、企业搜索、生物研究等领域
- 每个插件捆绑技能（Skills）、连接器（Connectors）、斜杠命令（Slash Commands）和子代理，适配特定岗位工作流
- 支持通过 MCP 协议连接外部工具（如 Slack、Notion、Jira、HubSpot、Snowflake 等）
- 提供插件管理插件（cowork-plugin-management），支持自定义和创建企业专属插件
- 兼容 Claude Cowork 和 Claude Code，可通过命令行安装

**技术亮点**:
- 基于文件驱动的插件架构（plugin.json 清单 + .mcp.json 工具连接 + commands/ + skills/）
- 通过 MCP（Model Context Protocol）服务器实现外部工具集成
- 技能自动触发，斜杠命令显式调用，兼顾自动化与可控性
- 语言：Python

---
## 7. [BerriAI/litellm](https://github.com/BerriAI/litellm)
- **语言**: Python
- **Stars**: 60,689
- **简介**: The fastest, litest AI Gateway. Rust core with Python SDK. Call 100+ LLM APIs in OpenAI (or native) format with cost tracking, guardrails, load balancing, and logging [Bedrock, Azure, OpenAI, Anthropic, OpenAI, VertexAI, vLLM, Nvidia NIM]

### AI 总结
**简介**: LiteLLM 是一个开源 AI 网关，提供统一接口以 OpenAI 格式调用 100+ LLM 提供商，支持 Python SDK 集成或代理服务器部署。

**核心功能**:
- 统一 API：以 OpenAI 格式调用 OpenAI、Anthropic、Gemini、Bedrock、Azure 等 100+ LLM 提供商
- 生产级网关：内置虚拟密钥、成本追踪、护栏、负载均衡和管理仪表盘
- 双模式使用：可作为 Python SDK 直接集成，或部署为集中式 AI Gateway 代理服务
- 一键部署：支持 Render、Railway、AWS、GCP 等平台快速部署

**技术亮点**: Rust 核心 + Python SDK 架构，P95 延迟仅 8ms（1k RPS），具备 drop-in OpenAI 兼容性，无需重写代码即可切换提供商。

---
## 8. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 104,015
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: Addy Osmani 推出的面向 AI 编程代理的生产级工程技能库，将资深工程师的工作流、质量门禁和最佳实践打包成可复用技能，让 AI 代理在开发各阶段保持一致行为。

**核心功能**:
- **9 个斜杠命令覆盖完整开发生命周期**：`/spec`（定义需求）、`/plan`（拆解任务）、`/build`（增量实现）、`/test`（测试验证）、`/constraints`（质量约束）、`/review`（合并前审查）、`/webperf`（性能审计）、`/code-simplify`（代码简化）、`/ship`（发布上线）
- **自动化技能触发**：根据当前任务自动激活对应技能，如设计 API 触发 `api-and-interface-design`，构建 UI 触发 `frontend-ui-engineering`
- **`/build auto` 自主执行模式**：一次性批准计划后自动生成并实现所有任务，仍保持测试驱动、逐任务提交，遇失败或高风险步骤会暂停
- **共 25 项技能**，可通过开放的 skills CLI 安装到 70+ 种 AI 代理（Claude Code、Cursor、Codex、Copilot、Cline 等）

**技术亮点**: 基于 JavaScript 实现；采用"技能即工作流"的架构，将开发阶段映射为命令与技能的自动组合；支持按需单独安装技能或全仓库集成，并提供 Claude Code 插件市场与 Cursor 规则等原生集成方式。

---
## 9. [storytold/artcraft](https://github.com/storytold/artcraft)
- **语言**: Rust
- **Stars**: 11,625
- **简介**: ArtCraft is an intentional crafting engine for artists, designers, and filmmakers

### AI 总结
**简介**: ArtCraft 是一款面向艺术家、设计师和电影制作人的交互式 AI 图像与视频创作 IDE，用 Rust 编写，通过可视化工具将提示词转化为精确、可重复的创作过程。

**核心功能**:
- **Image to Location**: 将虚拟角色置于一致的环境中，支持在同一场景中规划多个镜头
- **3D 图像合成**: 在 3D 空间中分层放置背景、前景和道具，构建具有纵深的构图
- **2D 图像合成**: 通过图像图层、背景移除和绘图工具组合场景
- **Image to 3D Mesh**: 将图像转化为可精确定位、旋转和取景的 3D 对象
- **角色摆姿**: 在生成最终镜头前调整角色姿态和相机位置
- **Kitbashing 场景布局**: 组合 3D 资产套件来控制相机角度、物体放置和景深

**技术亮点**: 使用 Rust 语言开发；支持 2D 构图与 3D 场景搭建的工作流融合；用户可自由选择适配的 AI 模型；提供桌面端下载和源码构建两种使用方式。

---
## 10. [Robbyant/lingbot-map](https://github.com/Robbyant/lingbot-map)
- **语言**: Python
- **Stars**: 17,726
- **简介**: [ECCV 2026 Best Paper Award Candidate] LingBot-Map: Geometric Context Transformer for Streaming 3D Reconstruction

### AI 总结
**简介**: LingBot-Map 是 Robbyant 团队提出的前馈式 3D 基础模型，用于流式三维重建，曾获 ECCV 2026 最佳论文奖提名。

**核心功能**:
- 流式 3D 重建：支持长序列（超过 10,000 帧）的实时在线重建
- 高效推理：前馈架构配合分页 KV cache 注意力，在 518×378 分辨率下可达约 20 FPS
- 提供交互式演示（`demo.py`）与离线渲染管线（`demo_render/batch_demo.py`）
- 支持多种数据集评测（KITTI、Oxford Spires、TUM-D、ETH3D、Tanks and Temples 等）
- 提供室内、室外、航拍等长视频示例

**技术亮点**:
- 几何上下文 Transformer（Geometric Context Transformer）：通过锚点上下文、位姿参考窗口和轨迹记忆，在单一流式框架内统一坐标定位、密集几何线索与长程漂移校正
- 支持 FlashInfer 与 SDPA 两种注意力后端，FlashInfer 性能更优
- 基于 PyTorch 2.8.0 + CUDA 12.8，模型权重已在 HuggingFace 与 ModelScope 发布，采用 Apache-2.0 许可

---
