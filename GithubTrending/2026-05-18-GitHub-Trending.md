---
tags:
  - github-trending
  - daily
date: 2026-05-18
created: 2026-05-18T01:55:45.146Z
---

# 2026-05-18 GitHub Trending Top 10

## 1. [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman)
- **语言**: Rust
- **Stars**: 13,414
- **简介**: Your Personal AI super intelligence. Private, Simple and extremely powerful.

### AI 总结
**简介**: OpenHuman 是一个开源的个性化 AI 助手，旨在私密、简单且强大地融入日常生活。

**核心功能**:
- **简洁的 UI 优先体验**: 提供桌面端应用，通过短引导流程即可快速配置并使用，无需终端或复杂设置；包含一个桌面吉祥物，能说话、响应环境、加入 Google Meet 并长期记忆。
- **118+ 第三方集成**: 支持 Gmail、Notion、GitHub、Slack、Stripe 等主流服务的一键 OAuth 连接，每 20 分钟自动拉取最新数据到记忆树中。
- **记忆树 + Obsidian 笔记**: 本地优先的知识库，将连接的数据转化为 Markdown 片段并构建分层摘要树，存储在本地 SQLite 中，同时生成兼容 Obsidian 的 .md 文件供浏览和编辑。
- **内置工具**: 包含网页搜索、网页抓取爬虫等即用功能。

**技术亮点**: 使用 Rust 语言开发，采用本地优先的 SQLite 存储和分层记忆树架构，支持自动数据拉取和上下文感知。

---
## 2. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 35,685
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: CLI-Anything 是一个开源项目，旨在通过生成统一的命令行接口，让任何软件都能被 AI 智能体原生调用和操控。

**核心功能**:
- **一键生成 CLI 接口**：为任意软件生成可供 AI 智能体（如 Pi、Claude Code）使用的命令行接口。
- **CLI-Hub 生态市场**：提供 `pip install cli-anything-hub` 安装的中央仓库，支持浏览、安装和管理社区构建的 CLI 工具。
- **丰富的应用演示**：展示了 AI 智能体通过生成的 CLI 完成 CAD 构建、3D 场景、图表、游戏字幕等 18 个实际应用案例。
- **社区贡献与协作**：支持开发者提交新的 CLI 工具或请求为特定软件创建 CLI。

**技术亮点**: 基于 Python (≥3.10) 和 Click (≥8.0) 框架，通过 `npx skills` 统一管理技能包，支持 JSON 与人类可读的双输出格式，单元与端到端测试覆盖率100%，拥有持续更新的公共注册表元数据。

---
## 3. [calcom/cal.diy](https://github.com/calcom/cal.diy)
- **语言**: TypeScript
- **Stars**: 43,294
- **简介**: Scheduling infrastructure for absolutely everyone.

### AI 总结
**简介**: Cal.diy 是一个社区驱动的、100% MIT 开源的个人日程调度平台，是 Cal.com 的社区版，专为希望完全自托管且无商业依赖的用户设计。

**核心功能**:
- 支持个人日程管理与预约安排
- 完全自托管，无需 Cal.com 账户或授权密钥
- 提供开源社区版，移除所有企业/商业版功能
- 支持本地开发和 Docker 部署

**技术亮点**:
- 技术栈：Next.js、tRPC、React.js、Tailwind CSS、Prisma.io、Daily.co
- 代码 100% MIT 许可，无“开源核心”分裂
- 社区维护，欢迎贡献者直接参与

---
## 4. [oven-sh/bun](https://github.com/oven-sh/bun)
- **语言**: Rust
- **Stars**: 91,730
- **简介**: Incredibly fast JavaScript runtime, bundler, test runner, and package manager – all in one

### AI 总结
**简介**: Bun 是一个极快的全栈 JavaScript/TypeScript 工具包，集成了运行时、打包器、测试运行器和包管理器。

**核心功能**:
- **JavaScript 运行时**: 作为 Node.js 的即插即用替代品，启动速度和内存占用大幅优化，原生支持 TypeScript 和 JSX。
- **包管理器**: 兼容 npm 生态，支持 `bun install`、`bun add`、`bun remove`、`bun update` 等命令，速度远超现有方案。
- **测试运行器**: 内置 `bun test`，可高效运行单元测试。
- **脚本运行器**: 通过 `bun run` 执行 `package.json` 中的脚本。

**技术亮点**: 使用 Zig 语言编写，底层基于 JavaScriptCore 引擎，显著降低启动时间和内存占用；支持 Linux、macOS 和 Windows 多平台。

---
## 5. [Anil-matcha/Open-Generative-AI](https://github.com/Anil-matcha/Open-Generative-AI)
- **语言**: JavaScript
- **Stars**: 15,158
- **简介**: Open-source alternative to AI video platforms — Free AI image & video generation studio with 200+ models (Flux, Midjourney, Kling, Sora, Veo). No content filters. Self-hosted, MIT licensed.

### AI 总结
**简介**: Open Generative AI 是一个免费、开源的 AI 图像与视频生成平台，支持 200+ 模型（如 Flux、Midjourney、Kling 等），无内容过滤，可自托管，基于 MIT 许可。

**核心功能**:
- 使用 200+ 先进模型生成 AI 图像和视频
- 提供在线版本（无需安装）和桌面应用（支持 macOS、Windows、Linux）
- 包含图像、视频、口型同步、影院四个工作室
- 支持通过 AI 编码代理（如 Claude Code、Codex）自动化媒体生成流程

**技术亮点**:
- 基于 JavaScript 构建，支持 Electron 桌面应用
- 提供无过滤的自托管解决方案，保障用户隐私
- 集成 200+ 模型，覆盖主流 AI 图像/视频生成技术
- 开源且 MIT 许可，便于二次开发和定制

---
## 6. [BigBodyCobain/Shadowbroker](https://github.com/BigBodyCobain/Shadowbroker)
- **语言**: Python
- **Stars**: 7,128
- **简介**: Open-source intelligence for the global theater. Track everything from the corporate/private jets of the wealthy, and spy satellites, to seismic events in one unified interface. Hook an AI agent up to have it parse through data and find previously unseen correlations. The knowledge is available to all but rarely aggregated in the open, until now.

### AI 总结
**简介**: ShadowBroker 是一个开源的实时地理空间情报平台，聚合全球60多个公开数据源，将飞机、船舶、卫星、地震等多元信息统一呈现在一个暗黑风格地图界面中。

**核心功能**:
- 实时追踪全球飞机（含空军一号、富豪私人飞机）、船舶（含AIS舰船、超级游艇）和卫星（按任务类型着色）
- 集成11,000+ CCTV摄像头、KiwiSDR短波电台、警察扫描仪、Meshtastic网格电台等实时数据流
- 右键点击地球任意位置获取国家档案、元首信息及最新Sentinel-2卫星图像
- 支持AI智能体（Claude/GPT/LangChain等）通过HMAC签名通道协作分析数据
- 内置InfoNet去中心化通信测试网，支持匿名消息、死信交换和终端CLI
- 显示GPS干扰区（基于飞机应答器数据）、地震火山、野火（NASA FIRMS）和空气质量数据
- 支持SAR合成孔径雷达地面变化检测，可穿透云层探测毫米级地表形变

**技术亮点**: 基于Next.js + MapLibre GL前端、FastAPI + Python后端，支持35+可切换数据图层、4种可视化模式（默认/卫星/FLIR/夜视/CRT），完全本地运行不收集用户数据，支持Shodan集成和HMAC签名智能体通信协议。

---
## 7. [tech-leads-club/agent-skills](https://github.com/tech-leads-club/agent-skills)
- **语言**: TypeScript
- **Stars**: 3,569
- **简介**: The secure, validated skill registry for professional AI coding agents. Extend Antigravity, Claude Code, Cursor, Copilot and more with absolute confidence.

### AI 总结
**简介**: Agent Skills 是一个为专业 AI 编码代理提供安全、经过验证的技能注册表，允许用户放心地扩展 Antigravity、Claude Code、Cursor、Copilot 等工具。

**核心功能**:
- 提供已验证、测试且安全的技能库，作为 AI 代理的“插件”，赋予其新工作流、模式和专业知识。
- 支持多种主流 AI 编码代理，包括 Claude Code、Cline、Aider、Antigravity、Amazon Q 等。
- 通过 CLI 工具实现技能的安装与管理，并内置 MCP Server 集成能力。

**技术亮点**: 使用 TypeScript 开发，基于 Nx Cloud 进行构建管理，采用语义化版本发布；通过静态分析、内容哈希锁定、人工审核和 Snyk Agent Scan 扫描等多重防护机制确保安全性。

---
## 8. [NirDiamant/agents-towards-production](https://github.com/NirDiamant/agents-towards-production)
- **语言**: Jupyter Notebook
- **Stars**: 19,946
- **简介**: End-to-end, code-first tutorials for building production-grade GenAI agents. From prototype to enterprise deployment.

### AI 总结
**简介**: 一个开源的实战手册，提供从原型到企业级部署的全栈 GenAI 智能体构建教程。

**核心功能**:
- 提供 28 个生产级教程，涵盖有状态工作流、向量记忆、实时网络搜索 API、Docker 部署、FastAPI 端点、安全护栏、GPU 扩展、浏览器自动化、微调、多智能体协调、可观测性、评估和 UI 开发。
- 教程为代码优先，端到端，从零开始构建生产就绪的 AI 智能体。
- 社区驱动，欢迎贡献和星标。

**技术亮点**: 使用 Jupyter Notebook 编写，涉及 LangGraph、LangChain、RAG、向量数据库、FastAPI、Docker、GPU 部署等关键技术栈。

---
## 9. [dograh-hq/dograh](https://github.com/dograh-hq/dograh)
- **语言**: Python
- **Stars**: 1,701
- **简介**: Open Source Voice Agent Platform

### AI 总结
**简介**: Dograh 是一个开源的语音 AI 代理平台，可作为 Vapi 和 Retell 的自托管替代方案，通过拖放工作流构建器快速创建生产级语音机器人。

**核心功能**:
- 拖放式工作流构建器，可在 2 分钟内创建语音机器人
- 支持呼入和呼出电话，内置电话集成（Twilio、Vonage 等）
- 支持自定义 LLM、TTS、STT 模型，并可切换提供商
- 测试模式，可端到端测试语音代理
- 自动生成 API 密钥，零配置启动

**技术亮点**: 基于 Python 构建，采用 Docker 容器化部署，模块化架构支持灵活组件替换，BSD 2-Clause 开源许可，支持自托管和云端使用。

---
## 10. [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- **语言**: Python
- **Stars**: 23,846
- **简介**: A set of ready to use Agent Skills for research, science, engineering, analysis, finance and writing.

### AI 总结
**简介**: 一个包含135个即用型科研技能的开放标准工具包，支持任何兼容Agent Skills协议的AI代理，可将其转变为跨学科研究助手。

**核心功能**:
- 覆盖生物信息学、药物发现、蛋白质组学、临床研究、医疗AI、医学影像、机器学习、材料科学、物理学、工程仿真、数据分析、地理空间科学、实验室自动化、科学写作、多组学、蛋白质工程等17个科学领域
- 提供与100+科学数据库及专业库（如单细胞RNA-seq、分子对接、DICOM处理等）的预定义交互接口
- 支持Cursor、Claude Code、Codex等多种AI代理平台，可执行多步骤复杂科学工作流

**技术亮点**: 基于开放Agent Skills标准构建，采用Python实现，通过显式定义的技能文档和示例代码增强AI代理在科学计算中的可靠性与表现力。

---
