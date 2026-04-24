---
tags:
  - github-trending
  - daily
date: 2026-04-24
created: 2026-04-24T01:55:45.001Z
---

# 2026-04-24 GitHub Trending Top 10

## 1. [huggingface/ml-intern](https://github.com/huggingface/ml-intern)
- **语言**: Python
- **Stars**: 3,423
- **简介**: 🤗 ml-intern: an open-source ML engineer that reads papers, trains models, and ships ML models

### AI 总结
**简介**: 一个开源ML工程师助手，能自主阅读论文、训练模型并部署ML模型。

**核心功能**:
- 交互式聊天与无头模式：支持实时对话或单次指令自动执行
- 深度集成Hugging Face生态：可直接访问文档、数据集、模型仓库和论文
- 代码搜索与生成：通过GitHub搜索代码，自主编写并提交高质量ML代码
- 沙箱执行与MCP服务器工具：安全运行代码并扩展工具能力

**技术亮点**:
- 基于litellm的LLM调用架构，支持多种模型（如Anthropic Claude）
- 智能上下文管理：自动压缩对话历史（170k token阈值）并上传至Hugging Face
- Doom循环检测器：自动识别重复工具调用模式并注入修正提示
- 模块化工具路由（ToolRouter）：统一管理文档搜索、代码执行、作业提交等操作

---
## 2. [zilliztech/claude-context](https://github.com/zilliztech/claude-context)
- **语言**: TypeScript
- **Stars**: 8,461
- **简介**: Code search MCP for Claude Code. Make entire codebase the context for any coding agent.

### AI 总结
**简介**: 一个 MCP 插件，为 Claude Code 等 AI 编程助手提供语义代码搜索，将整个代码库作为上下文，帮助 AI 高效理解大型项目。

**核心功能**:
- **语义代码搜索**: 通过语义搜索技术，从整个代码库中快速找到所有相关代码，无需多轮探索。
- **上下文注入**: 将搜索结果直接注入到 Claude 的上下文中，使 AI 拥有完整的代码库视野。
- **成本控制**: 使用向量数据库高效存储代码库，仅将相关代码纳入上下文，避免加载整个目录，从而降低大型代码库的使用成本。

**技术亮点**:
- **TypeScript**: 使用 TypeScript 语言开发。
- **MCP (Model Context Protocol)**: 基于 MCP 协议，可集成到 Claude Code、OpenAI Codex CLI 等 AI 编程助手中。
- **向量数据库**: 后端依赖 Zilliz Cloud 向量数据库进行代码存储和检索。
- **OpenAI Embedding**: 使用 OpenAI 的嵌入模型进行代码语义化处理。

---
## 3. [HKUDS/RAG-Anything](https://github.com/HKUDS/RAG-Anything)
- **语言**: Python
- **Stars**: 18,213
- **简介**: "RAG-Anything: All-in-One RAG Framework"

### AI 总结
**简介**: RAG-Anything 是一个基于 LightRAG 构建的全能型多模态 RAG 框架，支持文本、图像、表格和公式的智能检索与生成。

**核心功能**:
- 多模态查询与处理：支持文本、图像、表格和公式的联合检索与生成，并集成 VLM 增强查询模式，实现视觉与文本上下文的深度分析
- 上下文感知配置模块：智能整合相关上下文信息，增强多模态内容处理效果
- 一键安装与快速启动：通过 pip 包 `raganything` 安装，支持 Python 3.10 环境
- 社区支持：提供 Discord 和微信社区交流渠道

**技术亮点**: 基于 LightRAG 框架，采用 Python 3.10 技术栈，支持 VLM（视觉语言模型）增强的多模态分析，具备上下文感知的智能配置模块，提供 uv 包管理器支持

---
## 4. [Z4nzu/hackingtool](https://github.com/Z4nzu/hackingtool)
- **语言**: Python
- **Stars**: 61,124
- **简介**: ALL IN ONE Hacking Tool For Hackers

### AI 总结
**简介**: 一个为安全研究人员和渗透测试者设计的“All-in-One”黑客工具合集，整合了超过185种工具，涵盖20个类别。

**核心功能**:
- **模块化工具分类**: 包含匿名隐藏、信息收集、无线攻击、SQL注入、钓鱼攻击、Web攻击、逆向工程、DDOS攻击、XSS攻击、Active Directory、云安全、移动安全等20个类别。
- **智能菜单与搜索**: 支持通过关键词搜索（`/query`）、标签过滤（`t`）、以及基于需求的工具推荐（`r`）。
- **批量操作与管理**: 支持一键安装某个类别下的所有工具（`97`），并显示每个工具的安装状态（✔/✘）。
- **跨平台兼容**: 支持 Linux、Kali Linux、Parrot OS 和 macOS，并能根据系统自动隐藏不兼容的工具。
- **便捷安装与更新**: 提供一键安装脚本，并支持对单个工具进行智能更新（自动检测git pull/pip upgrade/go install）。

**技术亮点**: 基于Python 3.10+开发，采用OS感知菜单、Docker本地构建（无外部镜像）、智能更新机制，并提供丰富的交互式命令行界面。

---
## 5. [ruvnet/RuView](https://github.com/ruvnet/RuView)
- **语言**: Rust
- **Stars**: 49,854
- **简介**: π RuView: WiFi DensePose turns commodity WiFi signals into real-time human pose estimation, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: RuView 是一个将普通 WiFi 信号转化为实时人体姿态估计、生命体征监测和存在检测的传感平台，无需摄像头或可穿戴设备。

**核心功能**:
- 穿墙人体存在检测与计数
- 无接触呼吸率和心率监测
- 活动识别（行走、坐姿、手势、跌倒）
- 基于 WiFi 信号的环境映射（房间识别、家具移动检测）
- 睡眠质量监测（睡眠阶段分类和呼吸暂停筛查）
- 人体姿态估计（17个 COCO 关键点）

**技术亮点**:
- 基于 Rust 开发，利用 ESP32-S3 硬件采集信道状态信息（CSI）
- 边缘计算架构，无需云端，支持多节点 ESP32 网格
- 采用脉冲神经网络（SNN），30秒内完成本地环境自适应学习
- 支持无摄像头训练（10个传感器信号）和摄像头监督训练（92.9% PCK@20）
- 多频段 WiFi 网格扫描，利用邻居路由器作为免费雷达发射源
- 所有测量通过 Ed25519 见证链进行加密认证
- 支持 Docker 模拟运行，无需硬件即可体验

---
## 6. [Anil-matcha/Open-Generative-AI](https://github.com/Anil-matcha/Open-Generative-AI)
- **语言**: JavaScript
- **Stars**: 6,994
- **简介**: Uncensored, open-source alternative to Higgsfield AI, Freepik, Krea, Openart AI — Free, unrestricted AI image & video generation studio with 200+ models (Flux, Midjourney, Kling, Sora, Veo). No content filters. Self-hosted, MIT licensed.

### AI 总结
**简介**: 一个免费、开源、无审查的AI图像与视频生成工具，提供200+模型（如Flux、Midjourney、Kling等），支持本地部署（MIT许可），是Higgsfield AI等商业服务的替代品。

**核心功能**:
- **AI图像与视频生成**: 集成200+前沿模型，涵盖图像、视频、口型同步和影院四大工作室。
- **无内容过滤**: 不限制生成内容，完全开放。
- **多平台支持**: 提供macOS、Windows、Linux桌面应用，也可在线使用（无需安装）。
- **一键安装**: 提供DMG/EXE/AppImage等安装包，简化部署流程。

**技术亮点**: 基于JavaScript（Electron）构建，支持本地自托管，采用MIT开源协议；提供macOS Gatekeeper和Windows SmartScreen的绕过指南；针对Ubuntu 24.04+的AppArmor限制提供解决方案。

---
## 7. [Alishahryar1/free-claude-code](https://github.com/Alishahryar1/free-claude-code)
- **语言**: Python
- **Stars**: 5,666
- **简介**: Use claude-code for free in the terminal, VSCode extension or via discord like openclaw

### AI 总结
**简介**: 一个免费代理工具，可让您无需 Anthropic API 密钥即可免费使用 Claude Code CLI 和 VSCode 扩展。

**核心功能**:
- **零成本使用**: 支持通过 NVIDIA NIM（40次/分钟免费）、OpenRouter、DeepSeek、LM Studio（本地）和 llama.cpp（本地）等多种提供商免费运行 Claude Code。
- **即插即用**: 只需设置 2 个环境变量，无需修改 Claude Code 客户端或扩展。
- **多模型路由**: 可为 Opus、Sonnet、Haiku 等模型分别指定不同的提供商和模型，实现灵活混合。
- **思维链支持**: 能解析模型输出的 `<think>` 标签和 `reasoning_content`，并将其转换为原生 Claude 思维块。
- **工具调用自动解析**: 自动将模型以文本形式输出的工具调用解析为结构化的工具使用。
- **请求优化**: 本地拦截 5 类琐碎的 API 调用，节省配额和延迟。
- **智能限流**: 采用主动滚动窗口限流、响应式 429 指数退避和可选并发上限。
- **Discord/Telegram 机器人**: 支持远程自主编码，具有树形线程、会话持久化和实时进度显示。
- **子代理控制**: 强制拦截任务工具调用，防止失控的子代理。

**技术亮点**: 使用 Python 3.14 开发，采用 `uv` 项目管理，使用 `pytest` 测试，使用 `ruff` 进行代码格式化，使用 `loguru` 进行日志记录，并提供了清晰的 `BaseProvider` 和 `MessagingPlatform` 抽象基类，便于扩展新的提供商和平台。

---
## 8. [open-metadata/OpenMetadata](https://github.com/open-metadata/OpenMetadata)
- **语言**: TypeScript
- **Stars**: 12,957
- **简介**: OpenMetadata is a unified metadata platform for data discovery, data observability, and data governance powered by a central metadata repository, in-depth column level lineage, and seamless team collaboration.

### AI 总结
**简介**: OpenMetadata 是一个统一的元数据平台，用于数据发现、数据可观测性和数据治理，由中央元数据存储库、深度列级血缘和无缝团队协作驱动。

**核心功能**:
- 数据发现：通过关键词搜索、数据关联和高级查询，在单一位置查找和探索所有数据资产。
- 数据协作：通过事件通知、警报、公告、任务和对话线程，与团队沟通、交流和协作。
- 数据质量与 Profiler：使用无代码方式定义和运行数据质量测试，监控结果，构建数据信任。
- 数据治理：定义数据域和数据产品，分配所有者，使用标签和术语分类数据资产，并支持自动分类。
- 数据洞察与 KPI：通过报告和平台分析了解组织数据状态，设置关键绩效指标并跟踪目标。
- 数据血缘：端到端追踪和可视化数据资产的来源和转换，支持列级血缘和无代码编辑器编辑。

**技术亮点**: 基于开放元数据标准和 API，采用元数据模式、元数据存储、元数据 API 和可插拔的摄取框架（支持 84+ 连接器）的架构。使用 TypeScript 开发。

---
## 9. [microsoft/ai-agents-for-beginners](https://github.com/microsoft/ai-agents-for-beginners)
- **语言**: Jupyter Notebook
- **Stars**: 58,832
- **简介**: 12 Lessons to Get Started Building AI Agents

### AI 总结
**简介**: 微软推出的AI Agent入门教程，包含12节课程，帮助初学者掌握构建AI Agent的全部知识。

**核心功能**:
- 提供12节系统课程，涵盖AI Agent基础概念到构建实践
- 支持50+种语言的多语言翻译，通过GitHub Action自动更新
- 提供稀疏检出(clone)方式，避免下载大量翻译文件

**技术亮点**: 基于Jupyter Notebook的交互式学习方式，支持多语言自动化翻译协作

---
## 10. [PowerShell/PowerShell](https://github.com/PowerShell/PowerShell)
- **语言**: C#
- **Stars**: 52,800
- **简介**: PowerShell for every system!

### AI 总结
**简介**: PowerShell 是一个跨平台（Windows、Linux、macOS）的自动化配置工具和框架，包含命令行 shell、脚本语言和 cmdlet 处理框架，优化处理结构化数据（JSON、CSV、XML）和 REST API。

**核心功能**:
- 跨平台自动化与配置管理
- 支持结构化数据处理（JSON、CSV、XML 等）
- 集成 REST API 和对象模型交互
- 提供命令行 shell 和脚本语言
- 支持自定义 cmdlet 扩展

**技术亮点**: 基于 C# 开发，使用 .NET Core 框架，支持多平台构建和部署；社区驱动的开源项目，包含 RFC 流程和贡献指南。

---
