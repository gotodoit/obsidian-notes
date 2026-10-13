---
tags:
  - github-trending
  - daily
date: 2026-10-13
created: 2026-10-13T01:55:43.067Z
---

# 2026-10-13 GitHub Trending Top 9

## 1. [morluto/rea](https://github.com/morluto/rea)
- **语言**: TypeScript
- **Stars**: 160,477
- **简介**: Reverse engineer anything with agents, from app behavior down to native binaries.

### AI 总结
**简介**: REA 是一个基于 MCP 协议的逆向工程工具，让 AI Agent 能够分析二进制文件、应用程序和运行时行为，从应用功能一路追溯到原生二进制层面。

**核心功能**:
- 通过 MCP 将 Agent 连接到逆向工程工具，支持分析原生二进制、JavaScript/Electron 应用、.NET 程序集和网站
- 可在无源代码的情况下检查应用，解释功能实现原理并展示证据，帮助开发者在自己的项目中复现类似功能
- 支持终端直接调用（CLI），如 `analyze-javascript-application` 命令可分析提取的 JS/Electron 应用目录或 ASAR 包
- 原生分析可复用已有的 Hopper、Ghidra 或 IDA 安装，静态 JavaScript 分析无需原生引擎

**技术亮点**:
- 使用 TypeScript 开发，通过 `npx rea-agents setup` 一键完成 Agent 配置与工作流指令安装
- 分析在本地运行，结果包含证据和局限性说明，保证可追溯性
- 支持 Claude Code、Codex、Cursor、Gemini CLI、Grok Build 等多种主流 Agent
- 提供丰富的多语言文档（含简体中文、繁體中文、日本語、한국어等 18 种语言）

---
## 2. [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view)
- **语言**: JavaScript
- **Stars**: 53,759
- **简介**: A spy satellite simulator in your browser, except the data is real. Live open source spatial intelligence on a photorealistic 3D globe.

### AI 总结
**简介**: God's Eye View 是一个运行在浏览器中的间谍卫星模拟器，基于真实公开数据源，在逼真的 3D 地球上提供实时开源空间情报。

**核心功能**:
- **实时追踪与座舱视角**：追踪飞机、船舶、卫星等目标，可进入被追踪航班的座舱视角，摄像头全程锁定下方地形
- **点击追踪与摄像头联动**：点击任意目标即可锁定并绘制轨迹、展示完整元数据，追踪火灾或船只时可一键切换到最近的实时摄像头
- **语音控制与语音白板**：由实时 AI 智能体驱动的免手操作语音控制，可通过语音在地球上标注边界多边形、标记和路线
- **3D 机库与传感器滤镜**：提供真实的分机型 3D 飞机模型（787、ATR-72、MQ-9 等），并支持 CRT、NVG、FLIR 热成像、Noir、Snow 等 GLSL 传感器视觉效果
- **检测叠加与军事 HUD**：屏幕空间的目标检测框和 ID 标注，以及情报风格的战术抬头显示
- **气象与卫星过境**：动画展示 GFS/ECMWF 风场预报、雷达回波、卫星云图和闪电，支持查询卫星过境时间
- **分享链接**：摄像头位置、风格、图层乃至被追踪目标均可序列化为 URL，实现实时目标交接

**技术亮点**:
- 纯 JavaScript 实现，运行于浏览器本地，源代码可审查和扩展
- 每个数据图层为独立模块，便于扩展自定义数据源
- 无需 API 密钥即可启动，可选密钥在应用内添加
- 支持通过 Pinokio 一键安装或终端本地运行
- 数据源包括航班应答器、船舶信标、轨道根数、地震仪和公共摄像头等真实公开数据

---
## 3. [mksglu/context-mode](https://github.com/mksglu/context-mode)
- **语言**: TypeScript
- **Stars**: 27,337
- **简介**: Context window optimization for AI coding agents. Sandboxes tool output (98% reduction), persists session memory, and enforces routing across 17 platforms via MCP + hooks.

### AI 总结
**简介**: Context Mode 是一个面向 AI 编程代理的 MCP 服务器，通过沙箱化工具输出、持久化会话记忆和跨平台路由，解决上下文窗口被原始数据快速耗尽的问题。

**核心功能**:
- **上下文节省**：沙箱化工具输出，将原始数据隔离在上下文窗口之外，实现 98% 的压缩（如 315 KB 降至 5.4 KB）
- **会话连续性**：通过 SQLite 追踪文件编辑、git 操作、任务、错误和用户决策；对话压缩时利用 FTS5 索引和 BM25 搜索仅检索相关内容，让模型无缝续接
- **代码化思考**：引导 LLM 以编程方式处理任务，减少冗余输出和客套话对 token 的消耗
- **跨平台路由**：通过 MCP + hooks 在 17 个平台上强制执行路由策略

**技术亮点**: 基于 TypeScript 构建，采用 MCP 协议集成；使用 SQLite + FTS5 全文索引实现高效会话记忆检索，BM25 排序算法精准召回相关事件；支持 `--continue` 会话延续机制，非延续时自动清理历史数据保证会话隔离。

---
## 4. [storytold/artcraft](https://github.com/storytold/artcraft)
- **语言**: Rust
- **Stars**: 22,214
- **简介**: ArtCraft is an intentional crafting engine for artists, designers, and filmmakers

### AI 总结
**简介**: ArtCraft 是一款面向艺术家、设计师和电影制作人的交互式 AI 图像与视频创作 IDE，用 Rust 编写，将提示词转化为可视化创作流程。

**核心功能**:
- **Image to Location**：在一致的环境中放置虚拟角色，并在同一场景中规划多个镜头
- **3D 图像合成**：在 3D 空间中分层放置背景、前景和道具，构建具有深度的构图
- **2D 图像合成**：通过图像图层、背景移除和绘图工具组合场景
- **Image to 3D Mesh**：将图像转换为可精确定位、旋转和取景的 3D 对象
- **角色摆姿**：在生成最终镜头前摆好角色姿势并设置摄像机
- **Kitbashing 场景布局**：组合 3D 资产套件，控制摄像机角度、物体放置和景深

**技术亮点**: 使用 Rust 语言开发；支持 2D 与 3D 混合合成工作流；强调可重复、精确的视觉创作控制，而非单纯依赖提示词；提供桌面端应用（支持从源码构建），并有 Discord、YouTube、X、LinkedIn 等社区渠道。

---
## 5. [open-webui/open-webui](https://github.com/open-webui/open-webui)
- **语言**: Python
- **Stars**: 155,065
- **简介**: User-friendly AI Interface (Supports Ollama, OpenAI API, ...)

### AI 总结
**简介**: Open WebUI 是一个自托管、可扩展、功能丰富的 AI 交互界面，支持 Ollama 与 OpenAI 兼容 API，可完全离线运行。

**核心功能**:
- 支持 pip、uv、Docker、Kubernetes 等多种部署方式，提供 `:ollama` 与 `:cuda` 镜像
- 广泛模型与 API 集成：兼容 OpenAI API，可对接 LMStudio、GroqCloud、Mistral、OpenRouter、vLLM 等
- 细粒度 RBAC 与用户组权限管理，默认安全，按组定制体验
- 插件系统：支持 Filters、Actions、Pipes、Tools、Skills，并通过 MCP、MCPO、OpenAPI 工具服务器连接外部服务
- 模型与智能体：可封装基础模型为专用 Agent，支持动态变量与社区预设导入
- 借助 Open Terminal 实现智能体终端与文件系统操作，支持多步任务执行
- 内置 Notes 工作区、Channels 实时协作空间、持久记忆、日历与 AI 调度、自动化定时任务
- 响应式设计 + PWA，支持 Markdown/LaTeX，集成语音与视频通话（多种 STT/TTS 提供商）

**技术亮点**: 基于 Python 构建，采用 provider-agnostic 架构，支持本地与云端模型混合使用；具备插件化扩展能力（MCP/MCPO/OpenAPI），支持企业级终端隔离与资源限制，可完全离线部署保障数据主权。

---
## 6. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 52,703
- **简介**: Editorial diagram design for Claude Code, Codex, GitHub Copilot, Cursor, Factory Droid, and Pi. 44 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个面向 AI 编程助手（Claude Code、Cursor、GitHub Copilot 等）的 Agent Skill，用自然语言生成品牌化、自包含的 HTML + SVG 编辑级图表。

**核心功能**:
- 支持 44+ 种图表类型（架构图、象限图、时序图等），由 Agent 自动选择类型并输出单个可双击打开的 `.html` 文件
- 品牌适配：可读取指定网站的配色与字体，让后续所有图表自动匹配品牌风格
- 支持从 draw.io、Mermaid、Excalidraw 导入，并导出为 PNG / SVG
- 通过 `npx skills add` 跨宿主安装，兼容 Cursor、Claude Code、Codex、GitHub Copilot、Gemini CLI、Cline、Windsurf 等

**技术亮点**:
- 纯 HTML + SVG 实现，无阴影、无 Mermaid 风格，强调编辑级设计质感
- 跨 Agent 的 `skills` CLI 统一安装，支持 symlink 单副本多宿主共享，便于统一更新
- 官方提供 Claude Code 插件市场安装方式，支持后台自动更新

---
## 7. [lyogavin/airllm](https://github.com/lyogavin/airllm)
- **语言**: Jupyter Notebook
- **Stars**: 37,581
- **简介**: AirLLM 2.8T LLM inference with single 4GB GPU

### AI 总结
**简介**: AirLLM 是一个通过分层流式加载大幅降低推理显存占用的工具，让超大语言模型（最高 2.8T 参数）能在单张 4GB 显卡上运行，且无需量化、蒸馏或剪枝。

**核心功能**:
- 超大模型单卡推理：Kimi K3（2.8T）仅需 3.72GB 显存，DeepSeek-V3（671B）约 12GB，Qwen3-235B 约 3GB，70B 模型仅需 4GB。
- 小显存训练支持：Qwen3.8-Flash-Next（125B）可在 6GB 显存下训练，Qwen3.8-27B 在约 2GB 下训练（seq 512）。
- 自动模型识别：通过 `AutoModel` 自动检测模型类型，无需手动指定模型类。
- 广泛模型兼容：支持 Llama 3.x/4、Qwen 系列、DeepSeek V2/V3、Phi-4、Gemma、ChatGLM、Baichuan、Mistral、InternLM 等，并支持 FP8、8bit/4bit 量化及 safetensors。
- 跨平台支持：支持 CPU 推理与 MacOS 运行 70B 大模型。

**技术亮点**:
- 逐层流式加载：将模型按层拆分，推理时逐层加载，避免一次性载入全部权重。
- 预取优化（prefetching）：重叠模型加载与计算，提升约 10% 速度。
- 专家级流式加载：针对 MoE 模型（如 Kimi K3）仅加载 token 实际路由到的专家。
- n-gram 嵌入表文件映射：将超大嵌入表放在主机端文件映射，解码层流式加载。
- 训练时冻结权重逐层流式加载，适配器保留在 GPU 上。

---
## 8. [microsoft/BitNet](https://github.com/microsoft/BitNet)
- **语言**: C++
- **Stars**: 40,930
- **简介**: Official inference framework for 1-bit LLMs

### AI 总结
**简介**: microsoft/BitNet（bitnet.cpp）是微软官方推出的 1-bit LLM（如 BitNet b1.58）推理框架，支持在 CPU 和 GPU 上实现快速且无损的 1.58-bit 模型推理。

**核心功能**:
- 提供针对 1-bit/1.58-bit 模型优化的推理内核，支持 CPU 与 GPU（NPU 支持即将推出）
- 支持在单颗 CPU 上运行 100B 参数 BitNet b1.58 模型，速度可达 5-7 tokens/秒
- 支持 I2_S 量化转换与优化的嵌入模型推理（BitNet-embedding-0.6B/270M）
- 提供在线 Demo 及从源码构建的完整流程

**技术亮点**:
- 在 ARM CPU 上实现 1.37x–5.07x 加速，能耗降低 55.4%–70.0%
- 在 x86 CPU 上实现 2.37x–6.17x 加速，能耗降低 71.9%–82.2%
- 采用并行内核实现，支持可配置分块（tiling）与嵌入量化
- 基于 MIT 协议开源，使用 C++ 编写，配套多篇 arXiv 技术报告与 Hugging Face 模型集合

---
## 9. [Alishahryar1/free-claude-code](https://github.com/Alishahryar1/free-claude-code)
- **语言**: Python
- **Stars**: 59,176
- **简介**: Use Claude Code, Codex, VSCode, Pi, and OpenCode (and 6 other harnesses) for free (1.3B+ free tokens) from your terminal, app, IDE, or phone, and now from the browser with native browser sessions (multi-harness + multi-model) like OpenClaw (voice supported + ToS friendly)

### AI 总结
**简介**: 一个聚合 61 个合规服务商、每月提供 13 亿+ 免费 token 的开源工具，让 Claude Code、Codex、VS Code 等 11 种编码代理共享统一模型目录，支持终端、IDE、浏览器和手机多端使用。

**核心功能**:
- **多代理统一接入**：支持 Claude Code、Codex、Pi、OpenCode、Cline、Hermes、Aider、VS Code Chat 等 11 种编码代理，共用一套模型配置。
- **海量免费额度**：整合 61 个符合服务商条款的提供方，每月免费 token 超 13 亿，涵盖免费、付费、订阅及本地模型。
- **断网自动切换**：重试耗尽后自动切换到下一个已配置模型，无需重启当前任务，所有客户端通用。
- **Token 用量优化**：可选 RTK 过滤命令输出、Headroom 压缩工具结果，配合 5 项内置优化，最高降低 90% token 消耗。
- **浏览器原生 Code 会话**：在浏览器中选择文件夹直接运行 Codex，支持实时与后台模式，并可自由切换服务商/模型。
- **多端覆盖**：支持终端、桌面应用、VS Code、JetBrains、Discord、Telegram 等入口。
- **语音输入**：通过本地 Whisper 或 NVIDIA NIM 转写，实现语音转代码。
- **完整代理能力**：支持流式响应、工具调用、原生交错思考、图片发送，并可独立路由 Fable、Opus、Sonnet、Haiku 等模型。

**技术亮点**: 基于 Python 3.14 开发，使用 uv 作为包管理器，Pytest 测试，Ty 类型检查，Ruff 格式化，Loguru 日志；采用 AGPL v3 开源协议，架构上通过统一模型目录适配多代理与多服务商，并强调合规性与服务商条款友好。

---
