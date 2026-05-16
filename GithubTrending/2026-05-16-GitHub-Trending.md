---
tags:
  - github-trending
  - daily
date: 2026-05-16
created: 2026-05-16T01:55:44.379Z
---

# 2026-05-16 GitHub Trending Top 10

## 1. [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman)
- **语言**: Rust
- **Stars**: 9,098
- **简介**: Your Personal AI super intelligence. Private, Simple and extremely powerful.

### AI 总结
**简介**: OpenHuman 是一款开源、注重隐私的个人 AI 超级智能助手，旨在通过简洁的桌面界面和强大的代理能力，无缝融入用户的日常生活。

**核心功能**:
- **桌面伙伴与会议代理**: 拥有可说话的桌面吉祥物，能感知环境、加入 Google Meet 作为真实参与者，并在后台持续思考。
- **118+ 第三方集成与自动抓取**: 一键 OAuth 连接 Gmail、Notion、GitHub 等应用，每 20 分钟自动拉取最新数据存入记忆树。
- **本地优先的记忆树与 Obsidian Wiki**: 将连接的数据转化为 Markdown 摘要，存入本地 SQLite 数据库，并生成可编辑的 Obsidian 知识库。
- **内置全能工具集**: 集成网络搜索、网页抓取、完整代码工具（文件系统、Git、lint、test、grep）以及原生语音支持（语音转文字、ElevenLabs 语音合成、唇形同步）。

**技术亮点**: 使用 **Rust** 开发，确保高性能与安全性；采用 **SQLite** 实现本地优先的持久化存储；基于 **Obsidian** 工作流构建可浏览编辑的知识库。

---
## 2. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 192,865
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套为编码代理设计的完整软件开发方法论，基于可组合的技能和初始指令，确保代理遵循规范流程。

**核心功能**:
- **需求梳理**: 在编写代码前，通过提问和探索细化想法，并生成设计文档。
- **隔离工作区**: 设计批准后，自动创建独立分支和工作区，确保项目设置和测试基线干净。
- **任务分解**: 将设计拆分为2-5分钟的小任务，每个任务包含精确文件路径、完整代码和验证步骤。
- **子代理驱动开发**: 启动子代理依次执行工程任务，并自动检查和审查工作，支持长时间自主运行。

**技术亮点**: 以 Shell 脚本为基础，采用插件形式集成到 Claude Code、Codex CLI、Cursor 等主流编码工具中，强调 TDD、YAGNI 和 DRY 原则。

---
## 3. [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- **语言**: Python
- **Stars**: 22,476
- **简介**: A set of ready to use Agent Skills for research, science, engineering, analysis, finance and writing.

### AI 总结
**简介**: Scientific Agent Skills 是一个包含 135 项即用型科研技能的开放标准工具集，可将任何兼容的 AI 代理转变为强大的跨学科研究助手。

**核心功能**:
- 覆盖生物信息学、化学信息学、蛋白质组学、临床研究、医疗 AI、医学影像、机器学习、材料科学、物理学、工程仿真、数据分析、地理空间科学、实验室自动化、科学写作、多组学、蛋白质工程等 17 个科研领域
- 提供 135 项预定义的 Agent Skills，支持复杂多步骤科学工作流的自动执行
- 集成 100+ 科学数据库和专用库（如癌症基因组学、药物-靶点结合、分子动力学、RNA 速度等）的即用型接口
- 与 Cursor、Claude Code、Codex 等主流 AI 代理工具无缝集成

**技术亮点**: 基于开放的 [Agent Skills](https://agentskills.io/) 标准构建，采用 Python 实现，兼容任何支持该标准的 AI 代理；提供 K-Dense BYOK 桌面端开源工具，支持 40+ 模型、本地数据存储及可选云端扩展。

---
## 4. [supertone-inc/supertonic](https://github.com/supertone-inc/supertonic)
- **语言**: Swift
- **Stars**: 6,070
- **简介**: Lightning-Fast, On-Device, Multilingual TTS — running natively via ONNX.

### AI 总结
**简介**: Supertonic 是一个基于 ONNX Runtime 的本地化、多语言文本转语音（TTS）系统，支持在设备上快速运行，无需云端或 API 调用。

**核心功能**:
- **多语言支持**: 最新 v3 版本支持 31 种语言，v2 支持 5 种语言。
- **本地推理**: 所有模型在设备上运行，保护隐私，无需联网。
- **多种语音风格**: 提供多种预设语音（如 M1、M3、F3 等），并支持通过 Voice Builder 创建自定义语音。
- **跨平台 SDK**: 支持 Python、Node.js、浏览器、Java、C++、C#、Go、Swift、Rust 等多种语言和平台。
- **自动模型下载**: 首次运行时自动从 Hugging Face 下载模型资产。

**技术亮点**: 基于 ONNX Runtime 实现高效推理，使用 OnnxSlim 优化模型，支持 Git LFS 管理大型模型文件。

---
## 5. [ruvnet/RuView](https://github.com/ruvnet/RuView)
- **语言**: Rust
- **Stars**: 57,535
- **简介**: π RuView turns commodity WiFi signals into real-time spatial intelligence, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: RuView 是一个基于 WiFi 信号的空间感知平台，利用低成本的 ESP32 传感器采集信道状态信息（CSI），实现穿墙人员检测、生命体征监测、活动识别等功能，无需摄像头或可穿戴设备。

**核心功能**:
- **人员存在与占用检测**：穿墙检测人员、计数、追踪进出
- **生命体征监测**：无接触测量呼吸频率和心率
- **活动识别**：从 CSI 时序模式中识别行走、坐姿、手势、跌倒等
- **环境映射**：通过射频指纹识别房间、检测家具移动和新物体
- **睡眠质量分析**：整夜监测，含睡眠阶段分类和呼吸暂停筛查

**技术亮点**:
- **纯边缘计算**：基于 ESP32 网格（最低 $9/节点）和 Cognitum Seed，无需云、摄像头或互联网
- **脉冲神经网络**：30 秒内本地适应环境，多频段网格扫描利用邻居路由器作为免费雷达源
- **密码学认证**：通过 Ed25519 见证链对每次测量进行加密认证
- **无摄像头姿态估计**：支持 17 个 COCO 关键点姿态估计，基于 10 个传感器信号无标签训练（源自 CMU 的 DensePose From WiFi 研究）
- **技术栈**：Rust 语言实现，支持 Docker 多架构部署，通过 crates.io 分发包

---
## 6. [influxdata/telegraf](https://github.com/influxdata/telegraf)
- **语言**: Go
- **Stars**: 17,420
- **简介**: Agent for collecting, processing, aggregating, and writing metrics, logs, and other arbitrary data.

### AI 总结
**简介**: Telegraf 是一个用 Go 语言编写的插件驱动型代理，用于收集、处理、聚合和写入指标、日志及其他任意数据。

**核心功能**:
- 提供超过 300 个插件，覆盖系统监控、云服务、消息传递、日志、网络设备等广泛领域
- 支持用户自定义代码来高效收集、转换和传输数据
- 通过 TOML 配置文件定义输入、处理和输出插件，实现灵活的数据管道

**技术亮点**:
- 编译为独立的静态二进制文件，无外部依赖，部署流程精简
- 拥有超过 1,200 名贡献者的活跃社区驱动开发
- 支持多种数据格式和协议，包括 OpenTelemetry、Prometheus、Kafka、MQTT 等

---
## 7. [anthropics/skills](https://github.com/anthropics/skills)
- **语言**: Python
- **Stars**: 135,175
- **简介**: Public repository for Agent Skills

### AI 总结
**简介**: Anthropic 官方发布的 Agent Skills 公共仓库，包含一系列可被 Claude 动态加载的指令、脚本和资源，用于提升其在特定任务上的表现。

**核心功能**:
- **技能示例**: 提供涵盖创意设计、技术开发、企业通信和文档处理等领域的多种技能示例
- **文档技能**: 开源了驱动 Claude 文档能力的核心技能（docx、pdf、pptx、xlsx），供开发者参考
- **技能规范与模板**: 包含 Agent Skills 标准规范和一个基础的技能创建模板
- **多平台集成**: 支持在 Claude Code、Claude.ai 和 Claude API 中使用这些技能

**技术亮点**: 采用文件夹+SKILL.md 的简单结构（YAML 头信息+指令），通过动态加载机制让 Claude 按需调用特定技能集，部分核心技能以源码可用形式发布。

---
## 8. [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp)
- **语言**: TypeScript
- **Stars**: 20,903
- **简介**: A MCP for Claude Desktop / Claude Code / Windsurf / Cursor to build n8n workflows for you

### AI 总结
**简介**: n8n-MCP 是一个模型上下文协议（MCP）服务器，为 Claude 等 AI 助手提供对 n8n 自动化平台 1,650 个节点（820 核心 + 830 社区）的全面文档、属性和操作访问，使其能够理解和构建 n8n 工作流。

**核心功能**:
- **提供 n8n 节点知识库**: 包含 1,650 个节点的详细属性（99% 覆盖率）、操作（63.6% 覆盖率）和文档（87% 覆盖率），以及 265 个 AI 工具变体。
- **集成模板与示例**: 提供 2,352 个工作流模板（99.96% AI 元数据覆盖率）和 156 个从热门模板中提取的排名配置。
- **支持多种 AI 工具和 IDE**: 可连接 Claude Desktop/Code、VS Code、Cursor、Windsurf、Codex 等。
- **提供多种部署选项**: 支持云端免费试用（dashboard.n8n-mcp.com）、自托管（npx、Docker、Railway）以及本地/生产 n8n 集成。

**技术亮点**: 基于 TypeScript 开发，采用模型上下文协议（MCP），覆盖 n8n 平台 1,650 个节点的结构化数据，并提供了 5,418 个通过测试的高可靠性保障。

---
## 9. [NVIDIA-AI-Blueprints/video-search-and-summarization](https://github.com/NVIDIA-AI-Blueprints/video-search-and-summarization)
- **语言**: Python
- **Stars**: 1,162
- **简介**: Suite of reference architectures for building GPU-accelerated vision agents and AI-powered video analytics applications.

### AI 总结
**简介**: NVIDIA 的 Video Search and Summarization (VSS) 蓝图提供了一套参考架构，用于构建基于 GPU 加速的视觉 AI 智能体，能够对实时和存储的视频数据进行搜索、摘要和问答分析。

**核心功能**:
- **实时视频智能**: 从视频流中实时提取视觉特征、语义嵌入和上下文理解。
- **下游分析**: 将原始检测元数据丰富为轨迹、事件和经过验证的告警。
- **智能体与离线处理**: 通过模型上下文协议 (MCP) 提供自然语言搜索、视觉问答、视频摘要和片段检索等工具。

**技术亮点**:
- 集成 NVIDIA NIM 微服务，使用 Cosmos-Reason2-8B 和 Nemotron-Nano-9B-v2 等视觉语言模型 (VLM) 及大语言模型 (LLM)。
- 提供多种参考工作流，包括快速问答与报告生成、告警验证、实时异常检测、视频搜索和长视频摘要。

---
## 10. [oven-sh/bun](https://github.com/oven-sh/bun)
- **语言**: Rust
- **Stars**: 90,627
- **简介**: Incredibly fast JavaScript runtime, bundler, test runner, and package manager – all in one

### AI 总结
**简介**: Bun 是一个极快的全栈 JavaScript/TypeScript 工具包，集成了运行时、打包器、测试运行器和包管理器于一体。

**核心功能**:
- **JavaScript/TypeScript 运行时**: 可作为 Node.js 的即插即用替代品，直接运行 `.ts`、`.jsx` 等文件，启动速度和内存占用显著优化。
- **内置包管理器**: 兼容 npm 生态，支持 `install`、`add`、`remove`、`update` 等命令，速度远超传统方案。
- **测试运行器**: 提供 `bun test` 命令，无需额外配置即可运行测试。
- **脚本运行器**: 通过 `bun run` 执行 `package.json` 中的脚本。
- **打包器**: 内置高性能打包能力，支持模块解析和插件扩展。

**技术亮点**: 使用 Zig 语言编写，底层基于 JavaScriptCore 引擎，实现极致的启动速度和低内存占用；同时支持 Linux、macOS 和 Windows 多平台。

---
