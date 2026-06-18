---
tags:
  - github-trending
  - daily
date: 2026-06-18
created: 2026-06-18T01:55:44.306Z
---

# 2026-06-18 GitHub Trending Top 10

## 1. [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)
- **语言**: C
- **Stars**: 5,398
- **简介**: High-performance code intelligence MCP server. Indexes codebases into a persistent knowledge graph — average repo in milliseconds. 158 languages, sub-ms queries, 99% fewer tokens. Single static binary, zero dependencies.

### AI 总结
**简介**: 一个高性能代码智能 MCP 服务器，将代码库索引为持久化知识图谱，支持毫秒级查询和极低令牌消耗。

**核心功能**:
- 超高速索引：平均仓库毫秒级索引，Linux 内核（2800万行代码）仅需3分钟
- 158种语言支持：通过 tree-sitter AST 分析全面解析，结合混合 LSP 语义类型解析（支持Python、TypeScript、C++等10种语言）
- 14个 MCP 工具：提供丰富的代码结构查询能力，单次图查询替代数十次文件搜索
- 即插即用：单静态二进制文件，无依赖，支持 macOS/Linux/Windows，自动适配11种编码代理
- 内置3D图可视化界面：在 localhost:9749 交互式探索知识图谱
- 基础设施即代码索引：支持 Dockerfile、Kubernetes 清单等作为图节点索引

**技术亮点**:
- 纯 C 语言编写，零依赖，单静态二进制部署
- RAM优先管道：LZ4压缩、内存SQLite、融合Aho-Corasick模式匹配
- 混合 LSP 语义类型解析增强 tree-sitter AST 分析
- 所有处理100%本地化，代码不离开本机
- 支持 SLSA 3级安全标准，每次发布经 VirusTotal 扫描

---
## 2. [n0-computer/iroh](https://github.com/n0-computer/iroh)
- **语言**: Rust
- **Stars**: 9,672
- **简介**: IP addresses break, dial keys instead. Modular networking stack in Rust.

### AI 总结
**简介**: Iroh 是一个基于 Rust 的模块化网络栈，通过公钥寻址替代 IP 地址，提供快速、可靠的连接管理。

**核心功能**:
- **公钥拨号**: 支持通过公钥直接连接对端，自动发现并维护最优连接路径。
- **NAT 穿透**: 自动尝试打洞建立直连，失败时回退到公共中继服务器。
- **预构建协议**: 提供 iroh-blobs（内容寻址 blob 传输）、iroh-gossip（发布-订阅网络）、iroh-docs（最终一致键值存储）等协议。

**技术亮点**:
- **基于 QUIC 协议**: 使用 noq 实现 QUIC 连接，提供认证加密、并发流、数据报传输，避免队头阻塞。
- **模块化架构**: 核心库（iroh）与中继（iroh-relay）、基础类型（iroh-base）、DNS 服务器（iroh-dns-server）分离。
- **跨语言支持**: 通过 iroh-ffi 提供 FFI 绑定，支持其他语言调用。

---
## 3. [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)
- **语言**: Python
- **Stars**: 33,270
- **简介**: Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees.

### AI 总结
**简介**: 一键为AI Agent安装互联网能力，零API费用支持Twitter、Reddit、YouTube、B站、小红书等主流平台的数据读取与搜索。

**核心功能**:
- 一句话安装/更新：复制命令给Agent即可自动配置，无需手动折腾
- 多平台覆盖：支持网页、YouTube、B站、Twitter/X、Reddit、小红书、GitHub、LinkedIn、雪球、小宇宙等
- 零配置即用：部分平台无需任何配置即可使用（网页、YouTube、RSS、V2EX）
- Cookie安全方案：Cookie仅存本地，代码开源可审查，优先使用Cookie-Editor插件导出
- 自诊断工具：`agent-reach doctor` 一条命令检测各平台连通性并给出修复建议

**技术亮点**:
- 多后端路由架构：每个平台有“首选+备选”接入方式，某一路径失效时自动切换（如B站yt-dlp被封后自动切至bili-cli）
- MCP协议接入：搜索引擎通过MCP免费接入Exa，无需API Key
- 兼容所有Agent：Claude Code、OpenClaw、Cursor、Windsurf等任何能执行命令行的Agent均可使用
- 安全模式：提供`--safe`参数，仅提示所需系统包而不自动安装

---
## 4. [meshery/meshery](https://github.com/meshery/meshery)
- **语言**: TypeScript
- **Stars**: 11,027
- **简介**: Meshery, the cloud native manager

### AI 总结
**简介**: Meshery 是一个开源的云原生管理器，用于设计和管理所有基于 Kubernetes 的基础设施和应用程序。

**核心功能**:
- 提供可视化和协作的 GitOps 体验，摆脱 YAML 管理的束缚
- 支持 Kubernetes 多集群部署管理
- 作为可扩展平台，支持自定义设计和配置

**技术亮点**: 基于 TypeScript 构建，采用云原生架构，支持 Docker 部署和 Helm Chart 安装

---
## 5. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 231,133
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套为编码代理设计的完整软件开发方法论，基于可组合的技能和初始指令构建，让代理能高效工作。

**核心功能**:
- 自动引导用户明确需求并生成详细规格说明
- 制定清晰的实现计划，强调 TDD、YAGNI 和 DRY 原则
- 通过子代理驱动开发，自主执行任务并审查结果
- 支持多种编码代理平台（如 Claude Code、Cursor、Codex 等）

**技术亮点**: 基于 Shell 脚本实现，通过插件机制集成到多种代理工具中，支持自动触发和自主工作。

---
## 6. [google-research/timesfm](https://github.com/google-research/timesfm)
- **语言**: Python
- **Stars**: 21,930
- **简介**: TimesFM (Time Series Foundation Model) is a pretrained time-series foundation model developed by Google Research for time-series forecasting.

### AI 总结
**简介**: TimesFM 是 Google Research 开发的一个预训练时间序列基础模型，用于时间序列预测。

**核心功能**:
- 支持时间序列点预测和连续分位数预测（最多1000步）
- 支持最长16k上下文长度输入
- 提供PyTorch和Flax两种后端实现
- 支持协变量（通过XReg）和微调（通过HuggingFace Transformers + PEFT/LoRA）
- 提供Agent/Skill接口，便于集成到自动化工作流

**技术亮点**:
- 采用仅解码器架构（Decoder-only），论文发表于ICML 2024
- TimesFM 2.5仅200M参数（相比2.0的500M），支持16k上下文（相比2.0的2048）
- 支持连续分位数预测头（可选的30M参数模块）
- 在BigQuery ML、Google Sheets、Vertex Model Garden等Google产品中集成
- 提供多种安装方式（PyPI、本地）和详细的代码示例

---
## 7. [RocketChat/Rocket.Chat](https://github.com/RocketChat/Rocket.Chat)
- **语言**: TypeScript
- **Stars**: 45,595
- **简介**: The Secure CommsOS™ for mission-critical operations

### AI 总结
**简介**: Rocket.Chat 是一个基于 TypeScript 开发的完全开源、安全且高度可定制的团队通信平台，专为数据保护要求严苛的组织设计。

**核心功能**:
- **安全与主权**: 提供身份管理、端到端加密、基于角色和属性的访问控制等安全特性，确保通信私密安全。
- **团队协作**: 支持实时与异步消息、语音通话及联邦通信，实现无缝协作。
- **灵活部署与管理**: 支持自托管、云托管及气隙环境部署，具备可扩展架构和性能监控。
- **扩展与集成**: 可通过 Rocket.Chat Marketplace 安装公开应用，使用 Apps-Engine 构建自定义应用，并与外部系统集成。

**技术亮点**: 使用 TypeScript 开发，支持 Docker、Podman、Kubernetes 等多种部署方式，提供 Web、桌面及移动端应用，并具备原生联邦通信能力。

---
## 8. [continuedev/continue](https://github.com/continuedev/continue)
- **语言**: TypeScript
- **Stars**: 33,917
- **简介**: open-source coding agent

### AI 总结
**简介**: Continue 是一个开源的编码助手，支持 CLI、VS Code 和 JetBrains 插件，现已停止维护，最终版本为 2.0.0。

**核心功能**:
- 提供 CLI 工具，通过命令行与 AI 交互辅助编码
- 集成 VS Code 扩展，在编辑器中直接使用 AI 编码功能
- 支持 JetBrains 插件（推荐使用 CLI 替代）

**技术亮点**: 使用 TypeScript 开发，基于 Apache 2.0 开源协议，去除了匿名遥测和认证依赖，专注于提供纯粹的本地编码助手体验。

---
## 9. [penpot/penpot](https://github.com/penpot/penpot)
- **语言**: Clojure
- **Stars**: 50,110
- **简介**: Penpot: The open-source design tool for design and code collaboration

### AI 总结
**简介**: Penpot 是一款开源的设计平台，专为需要大规模构建数字产品的团队打造，强调设计基础设施的完全所有权，并支持自托管。

**核心功能**:
- 基于 SVG、CSS、HTML、JSON 等开放标准工作，支持浏览器使用或自部署。
- 实时协作，将设计以代码形式表达，便于开发者直接转换和加速产品交付。
- 原生设计令牌（Design Tokens）提供设计与开发间的单一事实源，确保一致性。
- MCP 服务器支持设计与代码间的多向工作流，实现可编程工作空间（含自动化、AI 驱动流程和插件系统）。
- CSS Grid 和 Flex Layout 支持响应式界面设计，使其从开始就模拟真实代码行为。

**技术亮点**: 使用 Clojure 语言开发，提供强大的开放 API 和插件系统，支持自托管，无供应商锁定。

---
## 10. [krahets/hello-algo](https://github.com/krahets/hello-algo)
- **语言**: Java
- **Stars**: 127,479
- **简介**: 《Hello 算法》：动画图解、一键运行的数据结构与算法教程。支持简中、繁中、English、日本語，提供 Python, Java, C++, C, C#, JS, Go, Swift, Rust, Ruby, Kotlin, TS, Dart 等代码实现

### AI 总结
**简介**: 《Hello 算法》是一本开源免费、新手友好的数据结构与算法入门教程，通过动画图解和可运行代码帮助读者轻松学习。

**核心功能**:
- 提供动画图解，清晰展示算法原理和数据结构底层实现
- 支持 Python、Java、C++、Go 等 12 种编程语言的代码一键运行
- 提供简体中文、繁体中文、英文、日文、俄文等多语言版本
- 支持在线阅读和 PDF/EPUB 离线下载

**技术亮点**: 采用多语言代码实现（Java 为主），结合动画与交互式编程，降低学习曲线，并支持社区贡献与翻译审阅。

---
