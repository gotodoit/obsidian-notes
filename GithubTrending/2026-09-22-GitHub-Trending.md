---
tags:
  - github-trending
  - daily
date: 2026-09-22
created: 2026-09-22T01:55:42.665Z
---

# 2026-09-22 GitHub Trending Top 10

## 1. [BuilderIO/agent-native](https://github.com/BuilderIO/agent-native)
- **语言**: TypeScript
- **Stars**: 5,941
- **简介**: A framework for building agentic apps

### AI 总结
**简介**: Agent-Native 是一个开源 TypeScript 框架，用于构建将自主智能体与专用 UI 配对的智能体应用。

**核心功能**:
- **共享 Actions**：每个能力只需定义一次，智能体将其作为工具调用，UI 也可从代码中调用，共享同一套验证、权限和实现逻辑
- **共享数据**：智能体完成的工作会呈现在 UI 中，UI 中的操作也对智能体可见
- **共享应用状态**：智能体可获取相关 UI 状态（如当前页面、选中记录、活动视图）
- **内置能力**：智能体聊天、认证与权限、技能与记忆、自动化任务、智能体团队、PostgreSQL 后端
- **多协议暴露**：同一 Action 可通过 UI、HTTP、MCP、A2A 和 CLI 访问
- **开源示例智能体**：提供 Clips、Design 等可直接使用或参考的智能体模板

**技术亮点**: 基于 TypeScript 构建，使用 Zod 进行 schema 验证；采用 Action 层作为 UI 与智能体的统一交互抽象；生产环境使用 PostgreSQL，本地开发使用 PGlite，兼容任意 Nitro 托管环境；支持自带 LLM、数据库和基础设施。

---
## 2. [trycua/cua](https://github.com/trycua/cua)
- **语言**: HTML
- **Stars**: 25,719
- **简介**: Scale computer-use 2.0 with open-source drivers, cross-OS fleets, and benchmarks for training, evaluation, and data generation.

### AI 总结
**简介**: Cua 是一个开源项目，为 AI 智能体提供可操作的计算机环境，涵盖桌面自动化、云端隔离桌面、本地 macOS 虚拟机、专用决策模型及评测基准。

**核心功能**:
- **Cua Fleets**: 提供隔离的云端 Linux 桌面池，支持通过 Sandbox SDK 执行命令、截图和操作应用
- **Cua Driver**: 跨平台（macOS/Windows/Linux）桌面自动化驱动，可检查和操作应用程序
- **Lume**: 在 Apple Silicon 上创建本地 macOS 和 Linux 虚拟机
- **CUA-S1**: 面向计算机使用决策的小型专用模型
- **Cua Bench**: 用于创建任务、评估智能体和导出轨迹的基准测试工具

**技术亮点**: 支持"Computer-Use 2.0"范式——智能体可在同一任务中灵活切换代码、API 和图形界面；兼容用户自带的智能体和模型；提供从本地 VM 到云端 Fleet 的完整部署方案；项目以 HTML 为主要语言，配套详尽的文档和教程体系。

---
## 3. [Open-Dev-Society/OpenStock](https://github.com/Open-Dev-Society/OpenStock)
- **语言**: TypeScript
- **Stars**: 17,788
- **简介**: OpenStock is an open-source alternative to expensive market platforms. Track real-time prices, set personalized alerts, and explore detailed company insights — built openly, for everyone, forever free.

### AI 总结
**简介**: OpenStock 是一个开源免费的市场行情追踪平台，旨在替代昂贵的商业金融数据服务，支持实时股价、个性化提醒和公司深度洞察。

**核心功能**:
- 实时追踪股票价格
- 设置个性化价格提醒
- 查看详细的公司信息与洞察
- 集成 TradingView 图表与 Finnhub 市场数据

**技术亮点**:
- 基于 Next.js + TypeScript 构建，使用 Tailwind CSS、shadcn/ui 和 Radix UI 打造界面
- 采用 Better Auth 进行身份认证，MongoDB 存储数据
- 使用 Inngest 处理后台任务调度，Nodemailer 发送邮件通知
- 集成 TradingView 图表与 Finnhub 金融数据 API
- 采用 AGPL-3.0 开源协议，修改或部署需以相同协议开源并署名

---
## 4. [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory)
- **语言**: Rust
- **Stars**: 7,715
- **简介**: Solution for long term memory for agent coding CLIs and to facilitate handoff between different agent vendors

### AI 总结
**简介**: ai-memory 是一个用 Rust 编写的长期记忆解决方案，让 AI 编程代理在跨工具、跨机器、跨团队协作时共享上下文，实现无缝任务交接。

**核心功能**:
- **跨代理记忆共享**：支持 Claude Code、Codex、Cursor、Gemini CLI 等 20 多种代理，在一个代理中中断的任务可由另一个代理直接接续，无需重新解释架构或失败方案
- **跨机器同步**：记忆存储在自托管服务器上，桌面端未完成的项目可在笔记本上继续，知识保持一致
- **团队协作**：多人指向同一服务器即可共享项目知识，内置多用户认证、个人归属和审计日志
- **纯 Markdown 存储**：以 git 管理的 `.md` 文件为真相来源，数据库仅为可重建的派生索引，支持 grep、Obsidian 编辑和 rsync
- **静默捕获工作过程**：通过生命周期钩子自动记录提示、工具调用和会话边界，经类型化隐私边界脱敏后整合为可读页面，默认路径零 LLM 调用
- **透明可控**：单一自包含二进制文件，提供明确的清除命令、实测写入上限（约 700/s）和完整变更审计日志

**技术亮点**:
- 采用 Rust 编写（要求 1.95+），单一自包含二进制
- 工作流程为：捕获（hooks 静默观察）→ 整合（会话结束时生成 wiki 页面）→ 召回（搜索 + 简报注入）→ 交接（下一代理接管）
- 支持全文、实体、链接及可选向量融合排序
- 跨代理交接为强类型协议，所有权明确、仅可认领一次
- 记忆源为 git 支持的 Markdown wiki，数据库可随时从文件重建，无需维护向量存储
- 支持 Linux、macOS、WSL2，原生 Windows 为实验性支持

---
## 5. [coder/coder](https://github.com/coder/coder)
- **语言**: Go
- **Stars**: 16,440
- **简介**: Secure environments for developers and their agents

### AI 总结
**简介**: Coder 是一个自托管的云开发环境和 AI 编程代理平台，用 Terraform 定义工作空间，通过安全隧道连接，空闲时自动关闭。

**核心功能**:
- 用 Terraform 定义云开发环境（支持 EC2、Kubernetes Pod、Docker 容器等）
- 空闲资源自动关闭以节省成本，开发者入职从数天缩短至数秒
- 在自有基础设施上运行 AI 编程代理，支持任意模型（Anthropic、OpenAI、Google、Bedrock、自托管）
- AI 代理无 LLM 凭证存于工作空间，每次操作绑定用户身份
- 提供集中的模型治理、成本追踪和审计日志

**技术亮点**: 采用 Go 语言开发；工作空间通过 Wireguard® 安全隧道连接；支持 PostgreSQL 13+ 生产部署；AI 代理循环在自有基础设施的控制平面中执行。

---
## 6. [anthropics/financial-services](https://github.com/anthropics/financial-services)
- **语言**: Python
- **Stars**: 35,854
- **简介**: 

### AI 总结
**简介**: Anthropic 推出的金融服务行业 AI 代理工具集，为投资银行、股票研究、私募股权和财富管理等场景提供参考代理、技能和数据连接器，支持 Cowork 插件和 Claude Managed Agents API 两种部署方式。

**核心功能**:
- **代理（Agents）**: 提供端到端工作流代理，包括 Pitch Agent（可比公司分析、先例交易、LBO → 品牌推介材料）、Market Researcher（行业概览、竞争格局、同行比较）、Earnings Reviewer（财报电话会+文件 → 模型更新 → 研报草稿）、Model Builder（DCF、LBO、三表模型、可比公司分析，直接在 Excel 中运行）、GL Reconciler（发现差异、追溯根因、路由审批）、Month-End Closer（应计、结转、差异分析）、KYC Screener（解析入驻文件、运行规则引擎、标记缺口）等
- **垂直插件（Vertical Plugins）**: 按金融服务垂直领域打包的技能、斜杠命令和数据连接器，可独立安装使用（如 `/comps`、`/dcf`、`/earnings`）
- **双部署模式**: 同一套系统提示和技能，既可作为 Claude Cowork 插件安装，也可通过 Claude Managed Agents API 部署在自有工作流引擎后
- **合作伙伴插件**: 包含 LSEG、S&P Global 等合作伙伴编写的插件
- **Microsoft 365 集成**: 提供管理工具用于配置 Claude Microsoft 365 加载项

**技术亮点**:
- 基于 Python 开发，采用插件化架构，每个代理插件自包含（打包其使用的技能，安装即用）
- 支持 Claude Code CLI 安装（`claude plugin marketplace add` / `claude plugin install`）
- 提供 Managed Agent 部署方案，包含 `agent.yaml`、叶子工作子代理、steering-event 示例及每个代理的安全说明
- 所有输出均需人工审核签字，代理不做出投资建议、执行交易、绑定风险、记账或批准入驻，强调合规与人工监督

---
## 7. [cloudflare/quiche](https://github.com/cloudflare/quiche)
- **语言**: Rust
- **Stars**: 12,369
- **简介**: 🥧 Savoury implementation of the QUIC transport protocol and HTTP/3

### AI 总结
**简介**: Cloudflare 开源的 QUIC 传输协议与 HTTP/3 的 Rust 实现，提供处理 QUIC 数据包和连接状态的底层 API。

**核心功能**:
- 实现 IETF 规范的 QUIC 传输协议与 HTTP/3
- 提供底层 API 处理 QUIC 数据包及连接状态管理，I/O 与事件循环由应用层负责
- 附带命令行工具（quiche-client、quiche-server）用于测试和实验

**技术亮点**:
- 使用 Rust 编写，配置对象（`Config`）可跨多个连接共享
- 已被 Cloudflare 边缘网络 HTTP/3、Android DNS 解析器（DoH3）以及 curl 等项目采用
- 支持 TLS 配置（基于 BoringSSL），并提供丰富的连接参数（流控、拥塞控制、空闲超时等）供应用按需配置

---
## 8. [mvt-project/mvt](https://github.com/mvt-project/mvt)
- **语言**: Python
- **Stars**: 13,615
- **简介**: MVT (Mobile Verification Toolkit) helps with conducting forensics of mobile devices in order to find signs of a potential compromise.

### AI 总结
**简介**: MVT 是由 Amnesty International 安全实验室开发的移动设备取证工具包，用于检测 Android 和 iOS 设备是否被间谍软件入侵。

**核心功能**:
- 对 Android 和 iOS 设备进行取证分析，收集有助于识别潜在入侵的痕迹
- 支持使用公开的入侵指标（IOCs）扫描设备，检测已知间谍软件活动的痕迹
- 提供 `mvt-ios` 和 `mvt-android` 两个平台专用命令，以及 `mvt` 通用命令（版本查询、插件管理、IOC 下载等）
- 支持 Shell 自动补全（Bash、Zsh、Fish）及插件扩展机制

**技术亮点**:
- 基于 Python 开发，可通过 PyPI（`pip3 install mvt`）或 uv 安装
- 起源于 Pegasus 项目，配套发布技术取证方法论，由 Amnesty International 持续维护
- 面向技术人员和调查人员，需具备数字取证知识和命令行操作能力

---
## 9. [zhouxiaoka/autoclip](https://github.com/zhouxiaoka/autoclip)
- **语言**: Python
- **Stars**: 8,288
- **简介**: AutoClip : AI-powered video clipping and highlight generation · 一款智能高光提取与剪辑的二创工具

### AI 总结
**简介**: AutoClip 是一款基于 AI 的智能视频剪辑工具，能自动分析长视频并提取高光片段，快速生成适合分享的精彩内容。

**核心功能**:
- **素材导入**：支持本地视频、YouTube 与 B 站链接，可附带 SRT 字幕
- **高光发现**：从字幕提取大纲、话题时间线、精彩度评分和片段标题
- **自动剪辑**：生成视频切片并组合推荐合集，支持手动调整顺序
- **发布导出**：提供抖音、小红书、YouTube Shorts、B 站导出预设，支持烧录字幕与标题卡
- **多模型支持**：可接入通义千问、OpenAI 兼容接口、Gemini、硅基流动，以及 Ollama / LM Studio 本地模型
- **多端使用**：提供桌面应用（macOS / Windows）、Docker Web 界面和 CLI / MCP 三种方式

**技术亮点**:
- 基于 Python 开发，桌面端采用 Tauri 构建
- 支持 CLI 批量编排与 MCP 协议接入，便于自动化流水线集成
- 无字幕视频可通过 faster-whisper 进行语音转写
- 界面支持中、英、日、韩、西、葡、俄、法八种语言
- 适合访谈、播客、课程和直播回放等长视频场景的二创剪辑

---
## 10. [ruanyf/weekly](https://github.com/ruanyf/weekly)
- **语言**: Unknown
- **Stars**: 103,994
- **简介**: 科技爱好者周刊，每周五发布

### AI 总结
**简介**: 阮一峰发起的科技爱好者周刊，每周五发布，记录值得分享的科技内容、文章、软件与资源。

**核心功能**:
- 每周五定期发布一期科技周刊，内容涵盖科技资讯、技术文章、软件工具与资源推荐
- 欢迎读者通过提交 Issue 投稿文章、软件或资源
- 讨论区设有《谁在招人》免费程序员招聘帖，提供大量就业与实习信息
- 以文档形式归档历期内容（docs/issue-XXX.md），覆盖 2024 年至今数百期

**技术亮点**: 项目以 Markdown 文档归档为主，无特定编程语言实现；采用 GitHub Issues 作为投稿与招聘信息的主要交互渠道，结构轻量、便于检索与阅读。

---
