---
tags:
  - github-trending
  - daily
date: 2026-05-15
created: 2026-05-15T01:55:44.048Z
---

# 2026-05-15 GitHub Trending Top 10

## 1. [ruvnet/RuView](https://github.com/ruvnet/RuView)
- **语言**: Rust
- **Stars**: 56,099
- **简介**: π RuView turns commodity WiFi signals into real-time spatial intelligence, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: RuView 是一个将普通 WiFi 信号转化为实时空间感知、生命体征监测与存在检测的传感平台，无需任何摄像头。

**核心功能**:
- **存在与占用检测**: 隔墙识别人体、计数、追踪进出
- **生命体征监测**: 无接触测量呼吸频率（6-30 BPM）和心率（40-120 BPM）
- **活动识别**: 通过 CSI 时序模式识别行走、坐姿、跌倒等动作
- **姿态估计**: 利用 WiFi 信号推断 17 个 COCO 关键点（基于 DensePose From WiFi 研究）
- **环境映射**: 通过射频指纹识别房间、检测家具移动与新增物体
- **睡眠监测**: 整夜监测，支持睡眠阶段分类与呼吸暂停筛查

**技术亮点**:
- 基于 ESP32 低功耗传感器网格（单节点低至 $9），搭配 Cognitum Seed 实现边缘 AI
- 使用信道状态信息（CSI）进行信号捕获，支持多频段网格扫描（6 个 WiFi 信道）
- 采用脉冲神经网络（SNN）实现本地自适应学习（<30 秒）
- 通过 Ed25519 见证链实现每次测量的密码学认证
- 支持无摄像头训练（10 个传感器信号）与摄像头监督训练（目标 PCK@20 > 35%）
- 完全边缘运行，无需云端、摄像头或互联网

---
## 2. [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman)
- **语言**: Rust
- **Stars**: 7,822
- **简介**: Your Personal AI super intelligence. Private, Simple and extremely powerful.

### AI 总结
**简介**: OpenHuman 是一款开源的个人 AI 超级智能助手，注重隐私、简洁和强大性能，旨在深度融入用户的日常生活。

**核心功能**:
- **UI 优先的桌面体验**: 提供简洁的桌面界面和引导流程，无需终端或复杂配置即可快速启动，包含会说话、反应、加入 Google Meet 的桌面吉祥物。
- **118+ 第三方集成与自动抓取**: 通过一键 OAuth 连接 Gmail、Notion、GitHub 等应用，每 20 分钟自动抓取新数据并存入记忆树。
- **记忆树与 Obsidian Wiki**: 本地优先的知识库，将连接数据转化为 Markdown 片段并构建层级摘要树，存储在 SQLite 中，同时生成可编辑的 Obsidian 兼容笔记库。
- **内置工具集**: 包含网页搜索、抓取、编码工具（文件系统、Git、lint、测试、grep）、原生语音（STT/TTS）及 Google Meet 支持。
- **智能 Token 压缩 (TokenJuice)**: 在调用任何 LLM 模型前，自动压缩工具调用、抓取结果等数据，减少 Token 消耗。

**技术亮点**: 使用 Rust 语言开发，支持模型路由（推理/快速/视觉模型）及可选本地 Ollama AI，采用 SQLite 存储本地数据，结合 Obsidian 知识管理流程。

---
## 3. [rohitg00/agentmemory](https://github.com/rohitg00/agentmemory)
- **语言**: TypeScript
- **Stars**: 9,019
- **简介**: #1 Persistent memory for AI coding agents based on real-world benchmarks

### AI 总结
**简介**: agentmemory 是一个为 AI 编码代理提供持久化记忆的 TypeScript 库，基于真实世界基准测试，让编码代理无需重复解释即可记住一切。

**核心功能**:
- **持久化记忆管理**: 为 Claude Code、Cursor、Gemini CLI 等编码代理提供持久化记忆，支持钩子、MCP 或 REST API。
- **51 个 MCP 工具**: 提供丰富的 MCP 工具集成，便于代理调用。
- **12 个自动钩子**: 支持自动化的钩子机制，简化记忆操作。
- **无外部数据库依赖**: 零外部数据库依赖，轻量级实现。
- **实时查看器**: 提供实时记忆查看器，监控记忆状态。
- **iii 控制台**: 集成 iii 控制台，增强管理能力。

**技术亮点**:
- **基于 iii 引擎**: 构建于 iii 引擎之上，提供高性能基础。
- **高检索精度**: 检索 R@5 达 95.2%，显著减少 token 使用量（92%）。
- **TypeScript 实现**: 使用 TypeScript 编写，类型安全。
- **827 个测试通过**: 高测试覆盖率，保证稳定性。

---
## 4. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 191,283
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为编码代理设计的完整软件开发方法论，基于一组可组合的技能和初始指令，确保代理遵循高效、规范的开发流程。

**核心功能**:
- **需求分析与设计**: 在编码前主动引导用户明确目标，生成可读的设计文档，并分块展示以供审核。
- **隔离工作环境**: 设计批准后，自动创建隔离分支和工作目录，运行项目设置并验证测试基线。
- **任务分解与计划**: 将工作拆分为小型可执行任务（2-5分钟），包含具体文件路径、完整代码和验证步骤。
- **子代理驱动开发**: 通过子代理按计划执行任务，自动审查工作，支持长时间自主运行（如Claude可连续工作数小时）。
- **多平台支持**: 集成Claude Code、Codex CLI、Cursor、GitHub Copilot CLI等主流编码代理工具。

**技术亮点**: 基于Shell脚本构建，采用插件化架构，通过市场机制分发；强调TDD（测试驱动开发）、YAGNI（你不会需要它）和DRY（不要重复自己）原则。

---
## 5. [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- **语言**: Python
- **Stars**: 21,826
- **简介**: A set of ready to use Agent Skills for research, science, engineering, analysis, finance and writing.

### AI 总结
**简介**: 一个包含135个即用型科研技能的开放标准Agent Skills集合，可将AI代理转变为跨学科研究助手。

**核心功能**:
- 覆盖生物信息学、化学信息学、蛋白质组学、临床研究、医学影像、材料科学、物理天文、工程仿真、数据分析、地理空间科学等17个科学领域
- 支持100+科学数据库的即插即用访问
- 与Cursor、Claude Code、Codex等主流AI代理工具兼容
- 提供配套桌面端开源AI协同科学家工具K-Dense BYOK

**技术亮点**: 基于开放Agent Skills标准构建，使用Python语言开发，支持多模型（40+模型）和本地/云端（Modal）混合部署，所有技能均附带精选文档和示例代码。

---
## 6. [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos)
- **语言**: Python
- **Stars**: 24,851
- **简介**: Kronos: A Foundation Model for the Language of Financial Markets

### AI 总结
**简介**: Kronos 是首个针对金融市场 K 线序列的开源基础模型，基于 45+ 全球交易所数据训练。

**核心功能**:
- 支持金融 K 线（OHLCV）数据的预测与量化任务
- 提供在线 Demo 演示 BTC/USDT 交易对未来 24 小时走势预测
- 开源多种规模的预训练模型（Kronos-mini/small/base），支持微调

**技术亮点**:
- 采用两阶段框架：先通过专用分词器将连续 K 线数据量化为层级离散 token，再使用自回归 Transformer 进行预训练
- 基于 Python 实现，模型托管于 Hugging Face Hub，代码开源

---
## 7. [roboflow/supervision](https://github.com/roboflow/supervision)
- **语言**: Python
- **Stars**: 38,902
- **简介**: We write your reusable computer vision tools. 💜

### AI 总结
**简介**: Roboflow 的 Supervision 是一个开源的 Python 工具库，旨在提供可复用的计算机视觉工具，帮助开发者轻松加载、标注、分析和处理图像、视频及检测结果。

**核心功能**:
- **模型无关的检测集成**: 支持与 Ultralytics、Transformers、MMDetection 等主流模型库无缝对接，统一输出 `Detections` 对象。
- **丰富的可视化标注器**: 提供高度可定制的标注器（如 BoxAnnotator），用于在图像或视频上绘制检测框、标签等。
- **数据集处理工具**: 支持加载、分割、合并和保存 COCO、YOLO 等格式的数据集，便于训练前的数据准备。
- **区域计数与追踪**: 提供工具来统计指定区域内的检测数量，以及对象追踪功能。

**技术亮点**: 基于 Python 3.9+，遵循模型无关的设计哲学，通过统一的检测接口简化多模型集成；依赖 OpenCV 进行图像处理，并支持通过 pip 快速安装。

---
## 8. [influxdata/telegraf](https://github.com/influxdata/telegraf)
- **语言**: Go
- **Stars**: 17,228
- **简介**: Agent for collecting, processing, aggregating, and writing metrics, logs, and other arbitrary data.

### AI 总结
**简介**: Telegraf 是一个用 Go 语言编写的代理，用于收集、处理、聚合和写入指标、日志及其他任意数据。

**核心功能**:
- 提供超过 300 种插件，涵盖系统监控、云服务、消息传递、网络设备、日志、数据库等多个领域
- 支持用户自定义代码来高效地采集、转换和传输数据
- 通过 TOML 配置文件进行灵活设置，允许用户定义输入源和输出目标
- 支持多种输出，包括时序数据库、消息队列、云服务等

**技术亮点**:
- 编译为独立的静态二进制文件，无外部依赖，部署流程简洁
- 插件架构高度模块化，社区贡献活跃（超过 1200 名贡献者）
- 支持通过 Exec、HTTP、SQL 等通用插件扩展功能

---
## 9. [supertone-inc/supertonic](https://github.com/supertone-inc/supertonic)
- **语言**: Swift
- **Stars**: 5,376
- **简介**: Lightning-Fast, On-Device, Multilingual TTS — running natively via ONNX.

### AI 总结
**简介**: Supertonic 是一个基于 ONNX Runtime 的本地化、多语言文本转语音（TTS）系统，支持在设备上快速运行，无需云服务。

**核心功能**:
- 支持 31 种语言（v3 版本），提高阅读准确率并减少重复/跳过错误
- 提供 Python SDK（可通过 `pip install supertonic` 安装），支持自动下载模型
- 提供 Voice Builder 工具，可将用户声音转化为可部署的 TTS 模型
- 跨平台支持，包括 Node.js、浏览器、Java、C++、C#、Go、Swift、Rust 等运行时示例

**技术亮点**:
- 基于 ONNX Runtime 实现本地推理，保护隐私且低延迟
- 通过 OnnxSlim 优化 ONNX 模型，提升性能
- 模型托管在 Hugging Face，支持 Git LFS 下载
- 提供 Flutter SDK 支持 macOS 兼容性

---
## 10. [Genymobile/scrcpy](https://github.com/Genymobile/scrcpy)
- **语言**: C
- **Stars**: 141,380
- **简介**: Display and control your Android device

### AI 总结
**简介**: scrcpy 是一款通过 USB 或 TCP/IP 连接，在电脑上实时显示并操控 Android 设备的轻量级开源工具，无需 root 权限或安装应用。

**核心功能**:
- 屏幕镜像与音频转发（Android 11+）
- 双向复制粘贴、文件拖放
- 虚拟显示与摄像头镜像（Android 12+）
- 屏幕录制与截图
- 物理键盘、鼠标、游戏手柄模拟（HID 模式）
- OTG 模式（无需 USB 调试）
- 支持 Linux/Windows/macOS 平台

**技术亮点**: 基于 C 语言开发，原生性能（30-120fps，延迟 35-70ms），支持 H.264/H.265 编码，提供 V4L2 虚拟摄像头（Linux 专属），无后台残留，完全开源免费。

---
