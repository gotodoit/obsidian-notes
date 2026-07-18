---
tags:
  - github-trending
  - daily
date: 2026-07-18
created: 2026-07-18T01:55:44.174Z
---

# 2026-07-18 GitHub Trending Top 10

## 1. [codecrafters-io/build-your-own-x](https://github.com/codecrafters-io/build-your-own-x)
- **语言**: Markdown
- **Stars**: 527,405
- **简介**: Master programming by recreating your favorite technologies from scratch.

### AI 总结
**简介**: 这是一个精选的教程集合，旨在通过从零开始重建各种流行技术来帮助开发者深入掌握编程原理。

**核心功能**:
- 提供涵盖3D渲染器、AI模型、数据库、操作系统、编程语言等30+类技术的分步构建教程
- 每个技术类别包含多种编程语言（C++/Python/Java/Go等）的实现指南
- 教程来源于社区高质量资源，包含详细文档和视频教程

**技术亮点**:
- 遵循“无法创造即无法理解”的学习哲学，强调动手实践
- 覆盖从底层系统（内存分配器、网络栈）到上层应用（Web浏览器、搜索引擎）的完整技术栈
- 教程按技术领域分类组织，便于开发者按需学习

---
## 2. [PostHog/posthog](https://github.com/PostHog/posthog)
- **语言**: Python
- **Stars**: 36,203
- **简介**: 🦔 PostHog is the leading platform for building self-driving products. Our developer tools – AI observability, analytics, session replay, flags, experiments, error tracking, logs, and more – capture all the context agents need to diagnose problems, uncover opportunities, and ship fixes. Steer it all from Slack, web, desktop, or the MCP.

### AI 总结
**简介**: PostHog 是一个开源平台，专注于帮助开发者构建“自动驾驶”产品，提供从分析到自动修复的全套工具。

**核心功能**:
- **自动驾驶模式**: 自动检测产品数据中的信号（如错误、愤怒点击），生成研究报告和拉取请求。
- **产品分析**: 自动捕获或手动追踪事件，通过可视化或SQL分析用户行为。
- **会话回放**: 观看真实用户与网站或应用的交互，诊断问题并理解行为。
- **功能标志**: 安全地向特定用户或群体逐步发布新功能。
- **实验**: 通过A/B测试衡量变更对目标指标的统计影响。
- **错误追踪**: 跟踪错误、接收警报并解决问题。
- **日志管理**: 摄取、搜索和分析日志数据。
- **AI可观测性**: 捕获LLM应用的追踪、生成、延迟和成本。
- **数据仓库与管道**: 同步外部数据（如Stripe），进行过滤、转换和实时导出。

**技术亮点**: 基于Python开发，支持自托管或云服务，提供Slack、Web、桌面客户端及MCP（模型上下文协议）多种控制方式。

---
## 3. [HenryNdubuaku/maths-cs-ai-compendium](https://github.com/HenryNdubuaku/maths-cs-ai-compendium)
- **语言**: TypeScript
- **Stars**: 6,635
- **简介**: Become a cracked AI/ML Research Engineer

### AI 总结
**简介**: 一本面向AI/ML从业者的开源、非传统教科书，从零基础覆盖数学、计算机科学和人工智能核心知识，强调直觉理解和实际应用。

**核心功能**:
- 提供从向量、矩阵到深度学习、多模态、自主系统等17个章节的系统化知识体系
- 包含MCP服务器接口，允许AI助手（如Claude Code、Cursor）将知识库作为上下文使用
- 涵盖面试级实战内容（作者朋友凭此笔记进入DeepMind、OpenAI等公司）

**技术亮点**:
- 使用TypeScript构建，支持在线阅读和本地部署
- 集成MCP协议实现AI辅助学习
- 知识体系覆盖数学基础、经典ML、NLP/CV/语音、多模态、图神经网络、GPU编程等前沿领域

---
## 4. [Nutlope/hallmark](https://github.com/Nutlope/hallmark)
- **语言**: CSS
- **Stars**: 12,067
- **简介**: Anti-AI-slop design skill for Claude Code, Cursor, and Codex.

### AI 总结
**简介**: Hallmark 是一个为 Claude Code、Cursor 和 Codex 设计的设计技能，旨在生成不像是 AI 生成的网页界面。

**核心功能**:
- **生成新 UI**：自动为需求选择宏观结构、应用主题和反模式规则，并通过 57 项“AI 味”检测和自检，拒绝使用 LLM 的默认分布。
- **审计现有代码**：使用 `hallmark audit <target>` 命令，对现有代码进行反模式评分，仅输出问题列表，不修改代码。
- **重构设计**：使用 `hallmark redesign <target>` 命令，保留文案、信息架构和品牌，但彻底重构页面结构和视觉风格。
- **分析并提取设计 DNA**：使用 `hallmark study <screenshot | URL>` 命令，从你欣赏的设计中提取宏观结构、字体配对和颜色锚点，并可生成可移植的 `design.md` 文件。

**技术亮点**: 提供 20 种主题，支持按 `T` 键快速切换；内置 57 项“AI 味”检测门和预输出自我批评机制；支持“自定义”模式，为独特创意需求从头设计页面。

---
## 5. [github/copilot-sdk](https://github.com/github/copilot-sdk)
- **语言**: Java
- **Stars**: 9,800
- **简介**: Multi-platform SDK for integrating GitHub Copilot Agent into apps and services

### AI 总结
**简介**: 提供多平台 SDK，用于将 GitHub Copilot Agent 集成到应用和服务中。  
**核心功能**:  
- 通过 SDK 调用 Copilot 的 agent 运行时，支持 Python、TypeScript、Go、.NET、Java 和 Rust。  
- 可定义 agent 行为，由 Copilot 处理计划、工具调用和文件编辑等任务。  
**技术亮点**: 基于生产测试的 agent 运行时，无需自建编排逻辑，支持多种语言和包管理器（npm、PyPI、NuGet、Go、crates.io、Maven Central）。

---
## 6. [anthropics/cwc-workshops](https://github.com/anthropics/cwc-workshops)
- **语言**: TypeScript
- **Stars**: 1,589
- **简介**: 

### AI 总结
**简介**: Anthropic 提供的“Code with Claude”研讨会材料集合，包含多个实践工作坊，旨在通过 Claude 和 Claude Managed Agents 学习 AI 辅助开发、多智能体系统、评估驱动开发等高级技术。

**核心功能**:
- **模型选择与评估**: 学习如何通过 Claude Code SKILL 审计评估套件，在不同模型和推理参数间优化质量与成本。
- **多智能体系统构建**: 使用 Skills 和 MCP 将大型提示分解为多智能体系统，并通过评估验证每一步。
- **AI 辅助产品工作流**: 从访谈到规范、设计探索到 React 应用构建的完整 AI 辅助开发流程。
- **托管代理部署**: 通过实现小型函数将离线 SRE 代理聊天面板上线，支持日志搜索和工具调用。
- **代理配置竞赛**: 45 分钟内配置 Claude Managed Agent 驱动游戏机器人，以钻石数量和令牌消耗为评判标准。
- **代理记忆机制**: 从无记忆到跨会话持久化记忆，再到记忆合并服务的逐步实现。
- **评估驱动开发**: 通过 6 个迭代变体和双层评分机制，量化每次提示变更对 PPTX 生成质量的影响。
- **生产级代理系统**: 构建多智能体 M&A 研究团队，支持协调、并行研究、记忆存储和事件流 UI。
- **SEC 文件研究台**: 在 Next.js 控制台上构建自托管研究代理，支持定制工具、子代理专家和每周备忘录部署。

**技术亮点**: 使用 TypeScript 开发，基于 Claude Managed Agents、MCP（Model Context Protocol）、Next.js、Streamlit、Vite + React 等技术栈，涵盖评估驱动开发、多智能体协调、记忆管理、实时事件流等架构特点。

---
## 7. [PrismML-Eng/Bonsai-demo](https://github.com/PrismML-Eng/Bonsai-demo)
- **语言**: Shell
- **Stars**: 1,716
- **简介**: Bonsai Demo

### AI 总结
**简介**: Bonsai 是一个高效的语言模型系列，支持在 Mac、Linux 和 Windows 上本地运行，提供 1-bit 和三元量化版本，并新增了视觉语言模型 Bonsai 27B。

**核心功能**:
- 本地运行 Bonsai 系列模型（1-bit 和三元量化），支持 Metal、CUDA、Vulkan、ROCm 和 CPU
- 提供 Bonsai 27B 视觉语言模型，支持图片、截图和 PDF 理解
- 原生 OpenAI 风格工具调用和 MCP 服务器支持
- 支持 256k+ 长上下文和推理模式
- 通过 setup.sh/setup.ps1 一键安装和下载模型

**技术亮点**: 采用极低比特量化（1-bit ~1.125 bits/weight，三元 ~1.7 bits/weight），模型体积小（27B 模型可适配现代 iPhone），基于 llama.cpp 实现，支持 GGUF 和 MLX 格式。

---
## 8. [protocolbuffers/protobuf](https://github.com/protocolbuffers/protobuf)
- **语言**: C++
- **Stars**: 71,541
- **简介**: Protocol Buffers - Google's data interchange format

### AI 总结
**简介**: Protocol Buffers (protobuf) 是 Google 开发的、语言中立、平台中立的扩展机制，用于序列化结构化数据。

**核心功能**:
- 提供协议编译器 (protoc)，用于编译 `.proto` 文件
- 为多种编程语言提供运行时库，支持序列化和反序列化
- 支持通过 Bazel 构建系统进行依赖管理（Bzlmod 和 WORKSPACE）

**技术亮点**: 使用 C++ 实现核心编译器；支持 Java、Python、C#、Go 等多种语言运行时；提供预编译二进制文件，简化安装。

---
## 9. [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)
- **语言**: Python
- **Stars**: 19,767
- **简介**: Local-first code intelligence graph for MCP and CLI. Builds a persistent map of your codebase so AI coding tools read only what matters, with benchmarked context reductions on reviews and large-repo workflows.

### AI 总结
**简介**: 一个本地优先的代码智能图工具，通过构建代码库的结构化地图，帮助 AI 编程工具在代码审查时只读取必要的上下文，大幅减少 Token 消耗。

**核心功能**:
- 使用 Tree-sitter 构建代码的结构化地图，并增量跟踪变更
- 通过 MCP 协议为 AI 助手提供精确的上下文，避免重复读取代码库
- 一键安装并自动检测配置 Codex、Claude Code、Cursor、GitHub Copilot 等 14+ 个 AI 平台
- 支持从 Git/SVN 项目中无痕卸载，只移除自身文件，不影响其他配置

**技术亮点**: 基于 Python 3.10+ 和 Tree-sitter 解析器，支持 MCP 协议集成，提供 CLI 和 GitHub Action 两种使用方式，实测可将 Token 消耗降低 38 倍到 528 倍。

---
## 10. [docusealco/docuseal](https://github.com/docusealco/docuseal)
- **语言**: Ruby
- **Stars**: 17,856
- **简介**: Open source DocuSign alternative. Create, fill, and sign digital documents ✍️

### AI 总结
**简介**: DocuSeal 是一个开源的 DocuSign 替代品，用于创建、填写和签署数字文档。

**核心功能**:
- PDF 表单字段构建器（所见即所得）
- 支持 12 种字段类型（如签名、日期、文件、复选框等）
- 每份文档支持多个签署人
- 通过 SMTP 自动发送电子邮件
- 文件存储支持磁盘、AWS S3、Google Storage、Azure Cloud
- 自动 PDF 电子签名及签名验证
- 用户管理
- 移动端优化
- 支持 7 种 UI 语言和 14 种签署语言
- 提供 API 和 Webhooks 用于集成
- 易于在几分钟内部署

**技术亮点**:
- 基于 Ruby 开发
- 支持 Docker 和 Docker Compose 快速部署
- 默认使用 SQLite 数据库，可选 PostgreSQL 或 MySQL
- 支持通过环境变量 `DATABASE_URL` 配置数据库
- 提供嵌入式的签署表单和文档构建器组件（React、Vue、Angular、JavaScript）

---
