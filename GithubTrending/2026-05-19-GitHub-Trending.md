---
tags:
  - github-trending
  - daily
date: 2026-05-19
created: 2026-05-19T01:55:45.388Z
---

# 2026-05-19 GitHub Trending Top 10

## 1. [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman)
- **语言**: Rust
- **Stars**: 17,455
- **简介**: Your Personal AI super intelligence. Private, Simple and extremely powerful.

### AI 总结
**简介**: OpenHuman 是一个开源的个人 AI 超级智能助理，注重隐私、简洁和强大性能，旨在融入用户的日常生活。

**核心功能**:
- **简单人性化的 UI 体验**: 提供直观的桌面界面和简短的上手引导，无需终端或复杂配置即可快速启动；包含一个桌面吉祥物，能说话、对环境做出反应、加入 Google Meet 会议，并持续在后台思考。
- **118+ 第三方集成与自动抓取**: 通过一键 OAuth 连接 Gmail、Notion、GitHub、Slack 等主流服务，代理自动将每个连接作为类型化工具使用，并每 20 分钟自动拉取新数据到内存树中，无需手动提示。
- **本地优先的记忆树与 Obsidian 知识库**: 将所有连接数据转化为 ≤3k-token 的 Markdown 块，构建分层摘要树并存储在本地 SQLite 数据库中；同时生成与 Obsidian 兼容的 `.md` 文件，形成本地知识库。

**技术亮点**: 使用 Rust 语言开发，强调性能与安全性；采用本地 SQLite 存储和 Markdown 格式，保障数据隐私与可移植性。

---
## 2. [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills)
- **语言**: Python
- **Stars**: 11,900
- **简介**: Academic Research Skills for Claude Code: research → write → review → revise → finalize

### AI 总结
**简介**: 一个为 Claude Code 设计的学术研究技能套件，覆盖从研究到发表的完整工作流，强调“人机协同”而非全自动化。

**核心功能**:
- **全流程支持**: 提供从研究规划、文献检索、写作、评审、修订到最终定稿的完整管道。
- **集成完整性检查**: 在多个阶段设置质量门禁（如Stage 2.5和4.5），可检测7类AI研究失败模式（如幻觉引用、方法论捏造）。
- **引用审计（v3.8）**: 可选审计模式，自动获取引用源并判断论文声明是否被支持，可识别5类高风险警告（如声明不被支持、虚构引用）。
- **风格校准**: 从用户过往作品中学习写作风格，提升文本质量，避免机器生成感。
- **写作质量检查**: 捕捉使文章显得机器生成的模式。

**技术亮点**: 基于Python，深度集成Claude Code CLI/VS Code/JetBrains环境；采用插件化架构（v3.7.0+），支持即装即用；提供可选的校准模式，允许用户使用黄金数据集测量工具的假阴性/假阳性率。

---
## 3. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 36,692
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: CLI-Anything 旨在通过为任意软件生成命令行接口（CLI），让 AI 代理能够原生地操作和使用这些软件，打破 AI 代理与现有软件之间的壁垒。

**核心功能**:
- **CLI 生成**: 为任意软件（如 QGIS、Unreal Insights、Shotcut 等）生成专用的命令行接口。
- **CLI-Hub**: 提供一个中心化的社区市场，用户可浏览、安装和管理所有由社区贡献的 CLI 工具。
- **AI 代理集成**: 生成的 CLI 可直接被 Pi、OpenClaw、Cursor、Claude Code 等 AI 代理调用，实现自动化操作。
- **丰富的演示**: 展示了 AI 代理通过生成的 CLI 完成 CAD 构建、3D 场景生成、图表制作等复杂任务。

**技术亮点**: 基于 Python 开发，采用 Click 框架构建 CLI，支持 JSON 和人类可读的输出格式，拥有 100% 通过的 pytest 测试覆盖率和 2,269 个通过测试，确保稳定可靠。

---
## 4. [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- **语言**: Python
- **Stars**: 24,422
- **简介**: A set of ready to use Agent Skills for research, science, engineering, analysis, finance and writing.

### AI 总结
**简介**: 一个包含 138 个即用型 Agent Skills 的开源项目，可将任何支持 Agent Skills 标准的 AI 代理转变为强大的科研助手，覆盖生物、化学、医学、工程等多个科学领域。

**核心功能**:
- **多领域科学技能库**：提供 138 个预定义技能，涵盖生物信息学、化学信息学、蛋白质组学、临床研究、医疗 AI、材料科学、物理学、工程仿真、地理空间科学等 17 个以上科学领域。
- **100+ 科学数据库集成**：技能可直接调用 78 个以上的科学数据库，支持复杂多步骤科研工作流。
- **跨平台兼容**：支持 Cursor、Claude Code、Codex 等主流 AI 代理，基于开放的 Agent Skills 标准。
- **提供免费桌面端 AI 协同科学家**：通过 K-Dense BYOK 项目，用户可使用自有 API 密钥在本地运行，数据安全可控，并可选择扩展至云端计算。

**技术亮点**: 基于开放的 [Agent Skills](https://agentskills.io/) 标准构建；为每个技能提供精心策划的文档和示例，使 AI 代理在特定科研工作流中表现更强大、更可靠；支持从本地桌面到云端计算（通过 Modal）的灵活部署。

---
## 5. [supertone-inc/supertonic](https://github.com/supertone-inc/supertonic)
- **语言**: Swift
- **Stars**: 8,375
- **简介**: Lightning-Fast, On-Device, Multilingual TTS — running natively via ONNX.

### AI 总结
**简介**: Supertonic 是一个基于 ONNX Runtime 的闪电般快速、设备端运行的多语言文本转语音（TTS）系统，支持本地推理，无需云端或 API 调用。

**核心功能**:
- **多语言支持**: 覆盖 31 种语言，并支持语言无关模式（`lang="na"`），无需单独适配器。
- **高速合成**: 低延迟实时合成，可在桌面、浏览器、移动设备甚至边缘设备上运行，例如快速将整个网页转换为音频。
- **高质量音频输出**: 直接生成 44.1kHz 16-bit WAV 格式的录音室级音频，无需外部上采样器。
- **表达标签**: 支持 10 种内联标签（如 `<laugh>`、`<breath>`、`<sigh>`），为语音增添自然的人类情感细节。
- **多运行时 SDK**: 提供 ONNX Runtime 下的 Python、Node.js、浏览器 (WebGPU)、Java、C++、C#、Go、Swift、iOS、Rust 和 Flutter 等示例。

**技术亮点**: 采用紧凑的 9900 万参数开源权重模型，体积远小于同类 0.7B-2B 参数模型，实现更小的下载量、更快的冷启动和更低的内存占用。完全设备端运行，零网络依赖，保障隐私，无需 GPU。

---
## 6. [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp)
- **语言**: C++
- **Stars**: 111,070
- **简介**: LLM inference in C/C++

### AI 总结
**简介**: llama.cpp 是一个高性能的 C/C++ 大语言模型推理引擎，支持在本地和云端多种硬件上运行。

**核心功能**:
- 支持多种主流大语言模型（如 LLaMA、Mistral、Falcon 等）及其微调版本
- 提供命令行工具 (`llama-cli`) 和 OpenAI 兼容 API 服务器 (`llama-server`)
- 支持从 Hugging Face 直接下载并运行模型（GGUF 格式）
- 支持多模态输入（图像等）的推理

**技术亮点**:
- 纯 C/C++ 实现，无外部依赖
- 深度优化 Apple Silicon（ARM NEON、Accelerate、Metal）
- 支持 x86（AVX/AVX2/AVX512/AMX）和 RISC-V（RVV 等）指令集
- 提供 1.5-bit 到 8-bit 多种量化方案，降低显存占用并加速推理
- 支持 NVIDIA/AMD/Moore Threads GPU 加速（CUDA/HIP/MUSA）
- 支持 CPU+GPU 混合推理，可运行超显存容量的大模型

---
## 7. [ruvnet/RuView](https://github.com/ruvnet/RuView)
- **语言**: Rust
- **Stars**: 59,934
- **简介**: π RuView turns commodity WiFi signals into real-time spatial intelligence, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: RuView 是一个基于 WiFi 信号的空间智能感知平台，无需摄像头即可实现穿墙人体检测、生命体征监测和姿态估计。

**核心功能**:
- **存在检测**：通过墙壁检测人员存在、计数和进出轨迹
- **生命体征监测**：无接触式呼吸率（6-30 BPM）和心率（40-120 BPM）测量
- **活动识别**：识别行走、坐姿、手势和跌倒等行为
- **姿态估计**：利用 WiFi 信号生成 17 个 COCO 关键点的人体姿态
- **环境映射**：通过射频指纹识别房间、检测家具移动和新物体

**技术亮点**:
- 基于 ESP32 低成本硬件（每节点 $9）和 Rust 语言实现
- 采用脉冲神经网络实现本地环境自适应学习（<30 秒）
- 多频段网格扫描利用邻居路由器作为免费雷达源
- 通过 Ed25519 见证链实现加密验证，无需云端和互联网
- 支持无相机训练（10 个传感器信号）和有相机监督训练（目标 PCK@20 ≥ 35%）

---
## 8. [CloakHQ/CloakBrowser](https://github.com/CloakHQ/CloakBrowser)
- **语言**: Python
- **Stars**: 15,299
- **简介**: Stealth Chromium that passes every bot detection test. Drop-in Playwright replacement with source-level fingerprint patches. 30/30 tests passed.

### AI 总结
**简介**: CloakBrowser 是一个通过 C++ 源码级修改 Chromium 指纹来绕过所有机器人检测的隐形浏览器，可作为 Playwright/Puppeteer 的即插即用替代品。

**核心功能**:
- **源码级反检测**: 49 个 C++ 补丁修改 Canvas、WebGL、音频、字体、GPU、屏幕、WebRTC 等指纹，使反机器人系统将其识别为正常浏览器。
- **即插即用替代**: 与 Playwright/Puppeteer 完全兼容的 API，仅需修改 import 语句即可无缝迁移。
- **人类行为模拟**: `humanize=True` 参数可启用类人鼠标曲线、键盘时序和滚动模式，轻松通过行为检测。
- **自动更新二进制**: 后台自动检查并下载最新隐身版本 Chromium，首次运行自动获取。
- **浏览器配置文件管理器**: 提供自托管的多登录/GoLogin/AdsPower 替代方案，支持创建唯一指纹、代理和持久会话的浏览器配置文件。

**技术亮点**: Python/JavaScript 双语言支持；基于 C++ 源码级 Chromium 修改；通过 Cloudflare Turnstile、FingerprintJS 等 30+ 检测站点测试；reCAPTCHA v3 得分 0.9；支持 Docker 一键运行。

---
## 9. [tech-leads-club/agent-skills](https://github.com/tech-leads-club/agent-skills)
- **语言**: TypeScript
- **Stars**: 4,069
- **简介**: The secure, validated skill registry for professional AI coding agents. Extend Antigravity, Claude Code, Cursor, Copilot and more with absolute confidence.

### AI 总结
**简介**: Agent Skills 是一个为专业 AI 编程代理提供安全、经过验证的技能注册中心，让开发者能放心地为 Antigravity、Claude Code、Cursor 等代理扩展功能。

**核心功能**:
- **安全技能市场**: 提供经过严格审查和验证的技能包，避免其他市场中存在的关键漏洞风险
- **多代理兼容**: 支持 Claude Code、Cline、Aider、Antigravity、Amazon Q 等多种主流 AI 编程代理
- **结构化技能定义**: 技能以标准化的目录结构组织，包含主指令、文件模板和按需文档
- **CLI 工具**: 提供命令行工具用于安装、管理技能，内置多重安全防护

**技术亮点**: 使用 TypeScript 开发，100% 开源；采用 Nx 管理单体仓库，使用语义化发布；CI/CD 集成静态分析和 Snyk Agent Scan 扫描确保安全；通过锁文件和内容哈希实现不可变完整性验证。

---
## 10. [BigBodyCobain/Shadowbroker](https://github.com/BigBodyCobain/Shadowbroker)
- **语言**: Python
- **Stars**: 7,758
- **简介**: Open-source intelligence for the global theater. Track everything from the corporate/private jets of the wealthy, and spy satellites, to seismic events in one unified interface. Hook an AI agent up to have it parse through data and find previously unseen correlations. The knowledge is available to all but rarely aggregated in the open, until now.

### AI 总结
**简介**: ShadowBroker 是一个开源的实时地理空间情报平台，聚合全球60多个公开数据源，将飞机、船舶、卫星、地震、CCTV等信号统一呈现在一个地图界面。

**核心功能**:
- **多域实时追踪**: 显示飞机(含空军一号、富豪专机)、船舶(含AIS渔船、超级游艇)、卫星、地震、野火、天气、空气质量的实时位置与状态
- **35+可切换数据层**: 包括GPS干扰区、CCTV摄像头、KiwiSDR短波电台、警察扫描仪、Mesh无线电节点、SAR地面变化检测等
- **交互式地图分析**: 右键点击任意地点获取国家档案、元首信息、人口数据、维基百科摘要和最新Sentinel-2卫星照片
- **AI代理集成**: 支持通过HMAC签名的命令通道连接AI代理(Claude、GPT等)，使其可读写所有数据层、放置标记、控制地图并发送警报
- **InfoNet去中心化通信**: 内置实验性测试网，支持匿名消息、Dead Drop点对点交换和终端CLI，无需注册账户
- **Shodan集成**: 可选接入Shodan API，将搜索结果作为本地调查覆盖层展示

**技术亮点**: 基于Next.js、MapLibre GL、FastAPI和Python构建；支持DEFAULT/SATELLITE/FLIR/NVG/CRT多种视觉模式；完全自托管后端，不收集用户数据；所有数据层在浏览器端渲染。

---
