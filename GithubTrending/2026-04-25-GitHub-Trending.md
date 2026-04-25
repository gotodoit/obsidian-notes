---
tags:
  - github-trending
  - daily
date: 2026-04-25
created: 2026-04-25T01:55:44.465Z
---

# 2026-04-25 GitHub Trending Top 10

## 1. [Alishahryar1/free-claude-code](https://github.com/Alishahryar1/free-claude-code)
- **语言**: Python
- **Stars**: 9,076
- **简介**: Use claude-code for free in the terminal, VSCode extension or via discord like openclaw

### AI 总结
**简介**: 一个免费代理工具，让用户无需 Anthropic API 密钥即可免费使用 Claude Code CLI 和 VSCode 扩展。

**核心功能**:
- **零成本使用**: 支持 NVIDIA NIM（40 次/分钟免费）、OpenRouter、DeepSeek、LM Studio（本地）和 llama.cpp（本地）五种提供商。
- **即插即用**: 只需设置 2 个环境变量，无需修改 Claude Code CLI 或 VSCode 扩展。
- **模型映射**: 可分别将 Opus、Sonnet、Haiku 路由到不同模型和提供商，自由混合使用。
- **思考令牌支持**: 解析 `<think>` 标签和 `reasoning_content` 为原生 Claude 思考块。
- **智能限流**: 主动滚动窗口限流 + 429 指数退避 + 可选并发限制。
- **Discord/Telegram 机器人**: 支持远程自主编程，包含树状线程、会话持久化和实时进度跟踪。
- **子代理控制**: 拦截任务工具，强制 `run_in_background=False`，防止子代理失控。

**技术亮点**: Python 3.14 实现，使用 `uv` 包管理，基于 `BaseProvider` 和 `MessagingPlatform` 抽象基类设计，易于扩展新提供商或平台。

---
## 2. [huggingface/ml-intern](https://github.com/huggingface/ml-intern)
- **语言**: Python
- **Stars**: 5,380
- **简介**: 🤗 ml-intern: an open-source ML engineer that reads papers, trains models, and ships ML models

### AI 总结
**简介**: 一个开源 AI 工程师，可自主研究论文、训练模型并部署 ML 模型。

**核心功能**:
- **交互式对话模式**：通过 CLI 启动聊天会话，与 AI 工程师交互。
- **无头模式**：直接输入单一 prompt 并自动执行，无需手动确认。
- **深度集成 Hugging Face 生态**：可访问文档、论文、数据集、模型仓库等资源。
- **安全执行控制**：对作业、沙箱等破坏性操作进行审批检查。
- **自动上下文管理**：支持消息历史自动压缩（170k tokens），并将会话上传至 Hugging Face。

**技术亮点**:
- **架构**：基于事件驱动的 `submission_loop` 和 `agent_loop`，支持异步操作和事件队列。
- **工具路由**：通过 `ToolRouter` 统一管理 HF 文档、GitHub 代码搜索、沙箱、计划等工具。
- **循环检测**：内置 “Doom Loop Detector”，可识别重复工具调用模式并注入修正提示。
- **模型支持**：通过 `litellm` 支持多种 LLM（如 Anthropic Claude），可通过 `--model` 参数切换。
- **安装便捷**：使用 `uv` 包管理器，支持全局安装后从任意目录调用 `ml-intern` 命令。

---
## 3. [google/osv-scanner](https://github.com/google/osv-scanner)
- **语言**: Go
- **Stars**: 9,524
- **简介**: Vulnerability scanner written in Go which uses the data provided by https://osv.dev

### AI 总结
**简介**: OSV-Scanner 是一个用 Go 编写的漏洞扫描工具，基于 OSV.dev 数据库，用于检测项目依赖中的已知漏洞。

**核心功能**:
- 支持扫描多种语言（C/C++、Go、Java、JavaScript、Python 等）和包管理器（npm、pip、Maven、Go Modules 等）的依赖。
- 可检测 Linux 系统包和容器镜像中的漏洞。
- 提供引导式修复建议，基于依赖深度、严重性等标准推荐版本升级。
- 使用调用分析减少误报，仅报告实际使用的易受攻击函数。

**技术亮点**: 底层利用 OSV-Scalibr 库实现可扩展性，数据库基于开放权威源（如 GitHub Security Advisories），并以机器可读的 OSV 格式存储精确的受影响版本信息，确保高准确性和可操作性。

---
## 4. [Z4nzu/hackingtool](https://github.com/Z4nzu/hackingtool)
- **语言**: Python
- **Stars**: 62,406
- **简介**: ALL IN ONE Hacking Tool For Hackers

### AI 总结
**简介**: hackingtool 是一个面向安全研究人员和渗透测试者的多合一黑客工具集，整合了超过 185 种工具，覆盖 20 个安全类别。

**核心功能**:
- **工具集成**: 集合了信息收集、无线攻击、SQL 注入、网络钓鱼、Web 攻击、逆向工程、DDOS、RAT 等 20 个类别的 185+ 工具。
- **智能搜索与推荐**: 支持通过 `/` 关键字搜索工具，通过 `t` 按标签（如 OSINT、C2、云安全）过滤，通过 `r` 根据用户需求（如“扫描网络”）推荐相关工具。
- **一键安装与管理**: 提供批量安装（类别内 `97` 选项）、智能更新（自动识别 git pull/pip upgrade/go install）、安装状态标记（✔/✘）及工具目录快速跳转。
- **跨平台适配**: 自动识别操作系统（Linux/Kali/Parrot/macOS），隐藏不兼容工具，并支持 Docker 本地构建。

**技术亮点**: 基于 Python 3.10+ 重写，采用现代语法；支持一键安装脚本（`curl -sSL ... | sudo bash`）；新增 Active Directory、云安全、移动安全三个类别。

---
## 5. [zilliztech/claude-context](https://github.com/zilliztech/claude-context)
- **语言**: TypeScript
- **Stars**: 9,023
- **简介**: Code search MCP for Claude Code. Make entire codebase the context for any coding agent.

### AI 总结
**简介**: Claude Context 是一个 MCP 插件，通过语义搜索为 Claude Code 等 AI 编程助手提供整个代码库的上下文，让 AI 能够高效理解和检索代码。

**核心功能**:
- **语义代码搜索**：利用向量数据库对代码库进行语义搜索，直接找到最相关的代码片段，无需多轮探索。
- **成本优化**：避免将整个目录加载到 Claude 请求中，仅将相关代码作为上下文，显著降低大型代码库的使用成本。
- **多客户端支持**：支持 Claude Code、OpenAI Codex CLI 等多种 AI 编程助手，通过 MCP 协议集成。
- **持久记忆扩展**：配套提供 memsearch 插件，实现跨会话的长期记忆功能。

**技术亮点**:
- 基于 **TypeScript** 开发，要求 Node.js >= 20.0.0 且 < 24.0.0。
- 依赖 **Zilliz Cloud**（向量数据库）和 **OpenAI 嵌入模型** 实现语义搜索。
- 提供 `@zilliz/claude-context-core` 和 `@zilliz/claude-context-mcp` 两个 npm 包，分别作为核心库和 MCP 服务器。
- 开源协议为 MIT，配备完整的文档、VS Code 扩展和 DeepWiki AI 文档支持。

---
## 6. [open-metadata/OpenMetadata](https://github.com/open-metadata/OpenMetadata)
- **语言**: TypeScript
- **Stars**: 13,366
- **简介**: OpenMetadata is a unified metadata platform for data discovery, data observability, and data governance powered by a central metadata repository, in-depth column level lineage, and seamless team collaboration.

### AI 总结
**简介**: OpenMetadata 是一个统一的元数据平台，用于数据发现、数据可观测性和数据治理，由中央元数据仓库、深度列级血缘和无缝团队协作驱动。

**核心功能**:
- **数据发现**: 通过关键词搜索、数据关联和高级查询，在单一位置查找和探索所有数据资产。
- **数据协作**: 与其他用户和团队在数据资产上进行沟通、交流和合作，支持事件通知、警报、公告、任务和对话线程。
- **数据质量和分析器**: 使用**无代码**方式定义和运行数据质量测试，监控结果，并通过协作将数据质量变为组织共享责任。
- **数据治理**: 强制执行数据策略和标准，包括定义数据域和数据产品、分配所有者、使用标签和术语分类数据资产，并支持自动分类。
- **数据洞察和 KPI**: 通过报告和平台分析了解组织数据状况，定义关键绩效指标并设置目标，支持按计划接收警报。
- **数据血缘**: 端到端追踪和可视化数据资产的来源和转换，支持列级血缘、查询过滤和无代码编辑器手动编辑。

**技术亮点**: 基于 TypeScript 开发，采用开放元数据标准和 API，包含元数据模式、元数据存储、元数据 API 和摄取框架四大组件，支持 84+ 连接器用于从各种数据源摄取元数据。

---
## 7. [PostHog/posthog](https://github.com/PostHog/posthog)
- **语言**: Python
- **Stars**: 33,128
- **简介**: 🦔 PostHog is an all-in-one developer platform for building successful products. We offer product analytics, web analytics, session replay, error tracking, feature flags, experimentation, surveys, data warehouse, a CDP, and an AI product assistant to help debug your code, ship features faster, and keep all your usage and customer data in one stack.

### AI 总结
**简介**: PostHog 是一个开源的、一体化的开发者平台，提供产品分析、网页分析、会话重放、错误跟踪、功能标志、实验、调查、数据仓库、CDP 和 AI 产品助手等功能，帮助团队构建成功的产品。

**核心功能**:
- **产品分析**: 自动捕获或手动埋点事件分析，支持可视化或 SQL 查询用户行为。
- **会话重放**: 观看真实用户会话，诊断问题并理解用户行为。
- **功能标志**: 安全地向特定用户或群组发布功能。
- **实验**: 无代码设置 A/B 测试，衡量变更对目标指标的统计影响。
- **错误跟踪**: 跟踪错误、接收警报并解决问题。
- **调查**: 提供无代码调查模板或自定义调查生成器。
- **数据仓库**: 同步外部工具（如 Stripe、Hubspot）数据，与产品数据一起查询。
- **数据管道**: 自定义数据过滤和转换，实时导出至 25+ 工具或 Webhook。
- **LLM 分析**: 捕获大语言模型应用的追踪、生成、延迟和成本。
- **工作流**: 创建自动化操作或发送用户消息的工作流。

**技术亮点**: 基于 Python 开发，支持 Docker 一键自托管（推荐 4GB 内存），提供慷慨的免费月度额度（如 100 万事件、5000 次录制），并拥有活跃的社区和贡献者生态。

---
## 8. [dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden)
- **语言**: Rust
- **Stars**: 59,179
- **简介**: Unofficial Bitwarden compatible server written in Rust, formerly known as bitwarden_rs

### AI 总结
**简介**: Vaultwarden 是 Bitwarden 服务端 API 的非官方 Rust 实现，旨在提供轻量级、资源友好的自托管密码管理方案。

**核心功能**:
- 完整的个人密码库管理（存储、分享、组织）
- 支持 Send 功能、附件上传和网站图标获取
- 支持组织与团队协作（集合、权限控制、密码共享）
- 提供个人 API 密钥用于自动化集成

**技术亮点**: 基于 Rust 语言开发，性能高效且内存占用低；完全兼容官方 Bitwarden 客户端；支持 Docker 容器化部署，镜像下载量超过百万次。

---
## 9. [Anil-matcha/Open-Generative-AI](https://github.com/Anil-matcha/Open-Generative-AI)
- **语言**: JavaScript
- **Stars**: 7,715
- **简介**: Uncensored, open-source alternative to Higgsfield AI, Freepik AI, Krea AI, Openart AI — Free, unrestricted AI image & video generation studio with 200+ models (Flux, Midjourney, Kling, Sora, Veo). No content filters. Self-hosted, MIT licensed.

### AI 总结
**简介**: Open Generative AI 是一个免费、开源、无审查的 AI 图像与视频生成平台，提供 200 多种先进模型，可替代 Higgsfield AI、Freepik AI 等商业工具。

**核心功能**:
- **多模态内容生成**: 支持图像、视频、口型同步、影院四种创作模式，涵盖 Flux、Midjourney、Kling、Sora 等 200+ 模型。
- **无内容过滤**: 完全无审查机制，不对生成内容施加限制，可自托管部署。
- **桌面应用支持**: 提供 macOS、Windows、Linux 一键安装版本，无需 Node.js 环境。
- **在线即用体验**: 托管版本可直接在浏览器中使用，无需本地安装。

**技术亮点**:
- 基于 JavaScript 开发，采用 MIT 开源协议，支持自托管部署。
- 集成 Happy Horse 1.0 等顶级视频生成模型，支持原生 1080p 文生视频与图生视频。
- 提供 Electron 桌面应用，跨平台兼容 Apple Silicon、Intel、ARM 架构。

---
## 10. [codecrafters-io/build-your-own-x](https://github.com/codecrafters-io/build-your-own-x)
- **语言**: Markdown
- **Stars**: 494,837
- **简介**: Master programming by recreating your favorite technologies from scratch.

### AI 总结
**简介**: 这是一个精选的教程合集，通过从零开始重建各种流行技术（如3D渲染器、数据库、操作系统等），帮助开发者深入掌握底层原理。

**核心功能**:
- 提供涵盖30+技术领域的详细分步指南，包括3D渲染器、AI模型、区块链、数据库、操作系统等
- 每个技术领域下收录多种语言（C++、Python、Java等）实现的教程资源
- 遵循"从零构建"原则，强调通过动手实践理解技术本质

**技术亮点**: 采用Markdown格式组织内容，按技术领域分类索引，每个教程明确标注编程语言和实现方式（文本/视频），覆盖从入门到高级的完整学习路径。

---
