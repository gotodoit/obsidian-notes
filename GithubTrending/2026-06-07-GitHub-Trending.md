---
tags:
  - github-trending
  - daily
date: 2026-06-07
created: 2026-06-07T01:55:43.756Z
---

# 2026-06-07 GitHub Trending Top 10

## 1. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 28,857
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: /last30days 是一个 AI 驱动的搜索代理，能并行搜索 Reddit、X、YouTube、HN、Polymarket 等多个平台，根据真实用户互动（点赞、投票、金钱）评分并生成综合摘要。

**核心功能**:
- 跨平台并行搜索：同时查询 Reddit、X、YouTube、TikTok、Hacker News、Polymarket、GitHub 等，获取各平台最新内容。
- 基于真实互动的评分：按 Reddit 投票、X 点赞、YouTube 转录、Polymarket 赔率等指标排序，而非编辑推荐。
- AI 智能合成摘要：AI 代理裁判将多源信息融合为一份简洁、有依据的总结。
- 零配置即用：Reddit、HN、Polymarket 和 GitHub 开箱即用，其他平台通过安装向导快速配置。
- 支持多种安装方式：兼容 Claude Code、Codex、Cursor、Copilot、Gemini CLI 等 50+ 代理技能宿主。

**技术亮点**:
- Python 实现，采用 v3 管道架构
- 通过 `npx skills add` 或 `plugin marketplace` 一键安装，自动更新
- 利用各平台自有 API 和认证机制，突破单一 AI 的数据孤岛限制

---
## 2. [CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit)
- **语言**: TypeScript
- **Stars**: 33,230
- **简介**: The Frontend Stack for Agents & Generative UI. React, Angular, Mobile, Slack, and more. Makers of the AG-UI Protocol

### AI 总结
生成总结时发生错误。

---
## 3. [MemPalace/mempalace](https://github.com/MemPalace/mempalace)
- **语言**: Python
- **Stars**: 54,302
- **简介**: The best-benchmarked open-source AI memory system. And it's free.

### AI 总结
**简介**: MemPalace 是一个本地优先、开源且免费的 AI 记忆系统，以 96.6% R@5 的原始准确率在 LongMemEval 基准测试中表现最佳，且无需调用任何外部 API。
**核心功能**:
- **逐字存储与语义检索**: 直接存储对话历史原文，并通过语义搜索进行检索，不进行摘要、提取或改写。
- **结构化索引**: 将人和项目组织为“翼”，主题组织为“房间”，原始内容存储在“抽屉”中，支持范围限定的搜索。
- **可插拔的后端存储**: 默认使用 ChromaDB，支持无缝切换至 sqlite_exact、Qdrant、pgvector 等后端。
- **命令行工具与 MCP 服务**: 提供 CLI 及 Docker 镜像，可作为 MCP 服务器使用，能轻松集成进 Claude Code 等客户端。
**技术亮点**: 支持本地精确向量检查 (sqlite_exact)、远程 REST (Qdrant) 和 SQL/JSONB (pgvector) 等多种后端；提供 Docker 部署，支持 GPU 加速。

---
## 4. [danielmiessler/Personal_AI_Infrastructure](https://github.com/danielmiessler/Personal_AI_Infrastructure)
- **语言**: TypeScript
- **Stars**: 14,977
- **简介**: Agentic AI Infrastructure for magnifying HUMAN capabilities.

### AI 总结
**简介**: PAI 是一个旨在放大人类能力的代理型 AI 基础设施，作为“生活操作系统”运行，帮助用户从当前状态过渡到理想状态。

**核心功能**:
- **Pulse 守护进程**: 统一的生活仪表盘，运行在 `localhost:31337`，提供生活状态监控。
- **DA (数字助理) 身份层**: 为用户提供个性化的 AI 身份和交互界面。
- **算法 v6.3.0**: 七阶段流程，从“当前状态”到“理想状态”，支持分类器驱动模式和层级。
- **ISA 原语**: 通用“理想状态”表述工具，用于定义和追踪目标。
- **技能、工作流与钩子**: 预置 45 项技能、171 个工作流和 37 个钩子，支持自动化操作。
- **结构隐私**: 通过隔离区域实现数据安全和隐私保护。

**技术亮点**: 基于 TypeScript 构建，使用 Bun 运行时，集成 Claude AI 能力，采用模块化架构（Packs 和 Releases），支持一键安装（`curl -sSL https://ourpai.ai/install.sh | bash`）。

---
## 5. [openai/plugins](https://github.com/openai/plugins)
- **语言**: JavaScript
- **Stars**: 1,787
- **简介**: OpenAI Plugins

### AI 总结
**简介**: 该项目是 OpenAI 维护的 Codex 插件示例集合，每个插件包含清单文件和可选组件，用于扩展 Codex 的功能。
**核心功能**:
- 提供 Figma、Notion 等官方插件的完整示例，覆盖设计、项目管理、应用开发等场景
- 支持自定义插件开发，包含清单文件（plugin.json）和多类型组件（技能、命令、钩子等）
- 集成 MCP（Model Context Protocol）和技能系统，实现跨平台功能扩展
**技术亮点**: 使用 JavaScript 实现插件架构，支持插件级代理、命令系统和资产资源管理，基于 manifest 驱动的模块化设计。

---
## 6. [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)
- **语言**: Python
- **Stars**: 22,358
- **简介**: Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees.

### AI 总结
**简介**: Agent Reach 是一个开源 CLI 工具，为 AI Agent 提供零配置、零 API 费用的互联网能力，支持一键接入 Twitter、Reddit、YouTube、GitHub、B站、小红书等主流平台。

**核心功能**:
- **多平台内容读取**: 直接阅读网页、YouTube 字幕、B站视频、GitHub 仓库、RSS 源等，无需额外配置
- **全网搜索与交互**: 支持 Twitter、Reddit、小红书、微博、微信公众号等平台的搜索、浏览、发帖、评论等操作
- **一键安装与更新**: 只需复制一句命令给 Agent，即可自动完成所有工具安装和环境配置
- **内置诊断工具**: 通过 `agent-reach doctor` 命令一键检测各平台连接状态并给出修复建议
- **隐私安全**: Cookie 仅存本地，代码完全开源，支持安全模式安装

**技术亮点**: Python 3.10+ 编写，通过 CLI 集成 yt-dlp、twitter-cli、rdt-cli、Jina Reader、MCP 等上游工具，兼容 Claude Code、OpenClaw、Cursor、Windsurf 等所有支持命令行的 Agent 平台。

---
## 7. [sveltejs/svelte](https://github.com/sveltejs/svelte)
- **语言**: JavaScript
- **Stars**: 86,998
- **简介**: web development for the rest of us

### AI 总结
**简介**: Svelte 是一种全新的 Web 应用构建方式，通过编译器将声明式组件转换为高效 JavaScript，精准更新 DOM。

**核心功能**:
- 将声明式组件编译为高效 JavaScript
- 通过编译器实现精准的 DOM 更新
- 提供 MIT 开源许可，支持社区贡献

**技术亮点**: 基于编译器的框架设计，无需虚拟 DOM，直接生成手术式更新 DOM 的 JavaScript 代码。

---
## 8. [nginx/nginx](https://github.com/nginx/nginx)
- **语言**: C
- **Stars**: 30,696
- **简介**: The official NGINX Open Source repository.

### AI 总结
**简介**: NGINX 是全球最流行的开源 Web 服务器，同时具备高性能负载均衡、反向代理、API 网关和内容缓存功能。

**核心功能**:
- **Web 服务器**: 提供高性能的静态和动态内容服务
- **负载均衡**: 支持多种算法分发流量到后端服务器
- **反向代理**: 接收客户端请求并转发至上游服务器
- **API 网关**: 管理、路由和限制 API 请求
- **内容缓存**: 缓存静态或动态内容以加速响应
- **速率限制**: 控制请求频率，防止滥用

**技术亮点**: 采用 C 语言开发，模块化架构（支持静态和动态模块扩展），通过事件驱动模型实现高并发和低资源占用。

---
## 9. [aquasecurity/trivy](https://github.com/aquasecurity/trivy)
- **语言**: Go
- **Stars**: 36,007
- **简介**: Find vulnerabilities, misconfigurations, secrets, SBOM in containers, Kubernetes, code repositories, clouds and more

### AI 总结
**简介**: Trivy 是一个全面且多功能的开源安全扫描器，用于检测容器、Kubernetes、代码仓库、云环境等中的漏洞、错误配置、密钥和软件物料清单（SBOM）。

**核心功能**:
- 扫描容器镜像、文件系统、Git 仓库、虚拟机镜像和 Kubernetes 集群中的安全问题
- 检测操作系统包和软件依赖的已知漏洞（CVE）
- 发现基础设施即代码（IaC）问题和错误配置
- 识别敏感信息和密钥泄露
- 分析软件许可证信息

**技术亮点**: 使用 Go 语言开发，支持多种扫描目标和扫描器，可集成到 GitHub Actions、Kubernetes Operator、VS Code 插件等平台，提供 canary 构建版本用于测试。

---
## 10. [golang/go](https://github.com/golang/go)
- **语言**: Go
- **Stars**: 134,513
- **简介**: The Go programming language

### AI 总结
**简介**: Go 是一种开源编程语言，旨在简化构建简单、可靠且高效的软件。
**核心功能**:
- 提供二进制发行版，支持从 https://go.dev/dl/ 下载并安装
- 支持从源码安装，适用于无二进制发行版的系统和架构
- 通过 https://go.dev/doc/contribute 提供贡献指南，鼓励社区参与
**技术亮点**: 采用 BSD 风格许可证，使用 Git 仓库管理（主仓库位于 go.googlesource.com，GitHub 镜像同步）

---
