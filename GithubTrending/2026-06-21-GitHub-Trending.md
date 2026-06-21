---
tags:
  - github-trending
  - daily
date: 2026-06-21
created: 2026-06-21T01:55:43.552Z
---

# 2026-06-21 GitHub Trending Top 10

## 1. [palmier-io/palmier-pro](https://github.com/palmier-io/palmier-pro)
- **语言**: Swift
- **Stars**: 3,420
- **简介**: macOS video editor built for AI

### AI 总结
**简介**: Palmier Pro 是一款为 AI 打造的 macOS 视频编辑器，支持用户与 AI 代理在时间线上协同生成和编辑视频。

**核心功能**:
- 原生 Swift 视频编辑：从头构建的 Swift 原生视频编辑器，提供类似 Premiere Pro 的专业编辑体验，并融入 AI 工作流。
- 内置生成式 AI：支持在时间线内直接使用 Seedance、Kling、Nano Banana Pro 等 SOTA 模型生成视频和图像。
- 与 AI 代理集成：通过 MCP 协议连接 Claude、Codex、Cursor 等代理，或使用内置代理协同编辑同一项目。

**技术亮点**: 基于 Swift 原生开发，通过 MCP 服务器（http://127.0.0.1:19789/mcp）提供接口，支持 Claude、Codex、Cursor、Claude Desktop 等工具的集成。编辑器核心、MCP 服务器及代理聊天功能开源，仅生成式 AI 处理部分闭源。

---
## 2. [penpot/penpot](https://github.com/penpot/penpot)
- **语言**: Clojure
- **Stars**: 51,462
- **简介**: Penpot: The open-source design tool for design and code collaboration

### AI 总结
**简介**: Penpot 是一款开源的设计平台，专为需要大规模构建数字产品的团队打造，强调设计基础设施的完全所有权，支持自托管和开放标准。

**核心功能**:
- **实时协作**: 支持团队在浏览器或自托管服务器上实时协作设计。
- **设计令牌**: 原生支持设计令牌，为设计与开发提供统一事实来源，确保一致性和可扩展性。
- **MCP 服务器**: 通过多方向工作流桥接设计与代码，支持自动化、AI 驱动工作流和集成。
- **插件系统**: 可扩展平台功能，集成其他应用并定制解决方案。
- **CSS Grid 与 Flex 布局**: 支持设计响应式界面，行为与真实代码一致。
- **检查模式**: 提供即用代码，方便开发者直接使用。

**技术亮点**: 基于 Clojure 开发，使用 SVG、CSS、HTML、JSON 等开放标准，支持自托管，并拥有强大的开放 API 和插件系统。

---
## 3. [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)
- **语言**: Python
- **Stars**: 7,096
- **简介**: World's first open-source, agentic video production system. 12 pipelines, 52 tools, 500+ agent skills. Turn your AI coding assistant into a full video production studio.

### AI 总结
**简介**: OpenMontage 是全球首个开源的智能体视频制作系统，能将AI编程助手转变为完整的视频制作工作室。

**核心功能**:
- 12条制作管线、52种工具、500+智能体技能，支持文本描述生成完整视频
- 从免费素材库和开放档案中检索真实运动片段，编辑时间线并渲染成品
- 支持多种视频类型：AI生成视频、图片动画视频、产品广告、动画短片等
- 提供从概念、脚本、场景规划到最终合成的全流程自动化

**技术亮点**: 基于Python构建，集成Veo、Kling v3、FLUX等AI生成模型，支持Remotion合成引擎、WhisperX字幕、多平台API（OpenAI、fal.ai等），成本低至$0.15。

---
## 4. [tursodatabase/turso](https://github.com/tursodatabase/turso)
- **语言**: Rust
- **Stars**: 20,350
- **简介**: Turso is an in-process SQL database, compatible with SQLite.

### AI 总结
**简介**: Turso 是一个用 Rust 编写的进程内 SQL 数据库，兼容 SQLite。
**核心功能**:
- 兼容 SQLite 的 SQL 方言、文件格式和 C API
- 支持 `BEGIN CONCURRENT` 多版本并发控制（MVCC）以提升写入吞吐量
- 提供变更数据捕获（CDC）功能，支持实时追踪数据库变化
- 多语言绑定支持，包括 Go、JavaScript、Java、.NET、Python、Rust 和 WebAssembly
- 支持向量搜索和向量操作
- 改进的 schema 管理，包括扩展的 `ALTER` 支持和更快的 schema 变更
- 实验性功能包括：静态加密、基于 DBSP 的增量计算、基于 tantivy 的全文搜索、多进程 WAL 协调
**技术亮点**:
- 使用 Rust 语言开发，提供高性能和内存安全
- 在 Linux 上支持基于 `io_uring` 的异步 I/O
- 跨平台支持 Linux、macOS、Windows 和浏览器（通过 WebAssembly）

---
## 5. [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)
- **语言**: C
- **Stars**: 9,394
- **简介**: High-performance code intelligence MCP server. Indexes codebases into a persistent knowledge graph — average repo in milliseconds. 158 languages, sub-ms queries, 99% fewer tokens. Single static binary, zero dependencies.

### AI 总结
**简介**: 一个高性能的代码智能 MCP 服务器，可将代码库索引为持久化知识图谱，支持 158 种语言，查询速度毫秒级，且为单一静态二进制文件，零依赖。

**核心功能**:
- **超高速索引**：平均仓库在毫秒级内完成全索引，Linux 内核（2800 万行代码，7.5 万文件）仅需 3 分钟。
- **即插即用**：单一静态二进制文件，支持 macOS、Linux、Windows，无需 Docker、运行时依赖或 API 密钥，下载后运行 `install` 即可。
- **广泛语言支持**：通过内置的 tree-sitter 语法解析支持 158 种编程语言，并针对 Python、TypeScript、Go 等 11 种语言提供增强的 Hybrid LSP 语义类型解析。
- **极低 Token 消耗**：结构查询仅需约 3,400 tokens，比逐文件搜索减少 120 倍。
- **多 Agent 兼容**：自动检测并配置 11 种主流 AI 编码代理（如 Claude Code、Codex CLI、VS Code 等）。
- **内置 3D 图可视化**：提供可选的 UI 二进制文件，可在 `localhost:9749` 交互式浏览知识图谱。
- **基础设施即代码索引**：将 Dockerfile、Kubernetes 清单等作为图节点索引，并建立交叉引用。
- **提供 14 个 MCP 工具**：用于执行各种代码结构查询。

**技术亮点**: 使用 C 语言编写，基于 tree-sitter 进行 AST 分析，采用 RAM 优先的索引流水线（LZ4 压缩、内存 SQLite、Aho-Corasick 模式匹配）。所有处理 100% 本地完成，代码不离开本机。项目设计已发布在 arXiv 预印本上，并经过 31 个真实仓库的评估。

---
## 6. [google-research/timesfm](https://github.com/google-research/timesfm)
- **语言**: Python
- **Stars**: 24,564
- **简介**: TimesFM (Time Series Foundation Model) is a pretrained time-series foundation model developed by Google Research for time-series forecasting.

### AI 总结
**简介**: TimesFM 是 Google Research 开发的一个预训练时间序列基础模型，用于时间序列预测。

**核心功能**:
- 支持时间序列点预测和分位数预测
- 提供从 PyPI 安装的 Python 包，支持 Torch 和 Flax 后端
- 支持协变量预测（通过 XReg）
- 提供 HuggingFace Transformers + PEFT (LoRA) 微调示例
- 支持 Agent 和 Skill 功能

**技术亮点**: 采用 decoder-only 架构，最新模型 TimesFM 2.5 参数量 200M，支持最长 16k 上下文长度和 1k 预测范围，集成 BigQuery ML、Google Sheets 和 Vertex Model Garden 等 Google 产品。

---
## 7. [twentyhq/twenty](https://github.com/twentyhq/twenty)
- **语言**: TypeScript
- **Stars**: 50,874
- **简介**: The open alternative to Salesforce, designed for AI.

### AI 总结
**简介**: Twenty 是一个开源 CRM 系统，旨在作为 Salesforce 的替代方案，专为 AI 时代设计。

**核心功能**:
- **快速云部署**: 在 twenty.com 上注册即可在 1 分钟内创建工作空间，无需管理基础设施。
- **应用构建**: 通过 Twenty CLI 和 SDK，以代码方式定义对象、字段和视图，并发布到工作空间。
- **自托管**: 支持使用 Docker Compose 在自有基础设施上部署，也提供本地开发指南。
- **可扩展构建块**: 提供对象、视图、工作流和代理等现代 CRM 构建块，支持以代码方式扩展。

**技术亮点**: 基于 TypeScript 开发，提供 CLI 工具和 SDK，支持对象、字段、视图的代码化定义，并集成了 Docker 自托管能力。

---
## 8. [Kong/insomnia](https://github.com/Kong/insomnia)
- **语言**: TypeScript
- **Stars**: 39,339
- **简介**: The open-source, cross-platform API client for GraphQL, REST, WebSockets, SSE and gRPC. With Cloud, Local and Git storage.

### AI 总结
**简介**: Insomnia 是一个开源、跨平台的 API 客户端，支持 GraphQL、REST、WebSockets、SSE 和 gRPC 等多种协议，并提供本地、云端和 Git 存储选项。

**核心功能**:
- 调试 API：支持多种流行协议和格式。
- 设计 API：内置原生 OpenAPI 编辑器和可视化预览。
- 测试 API：支持原生测试套件和集合运行器。
- 模拟 API：使用云端或自托管模拟服务器。
- 构建 CI/CD 管道：通过原生 Insomnia CLI 进行代码检查和测试。
- 协作：支持多种协作功能，并可安装第三方插件。
- 多种存储方式：支持本地保险库、Git 同步和云端同步（可选端到端加密）。

**技术亮点**: 基于 TypeScript 开发；支持跨平台（Mac、Windows、Linux）；提供私有环境功能，确保敏感配置本地存储；兼容 HTTP 兼容协议。

---
## 9. [tw93/Pake](https://github.com/tw93/Pake)
- **语言**: Rust
- **Stars**: 54,853
- **简介**: 🤱🏻 Turn any webpage into a desktop app with one command.

### AI 总结
**简介**: Pake 是一个用 Rust 编写的命令行工具，可一键将任何网页转化为轻量级桌面应用，支持 macOS、Windows 和 Linux。

**核心功能**:
- **一键打包**: 通过 CLI 或在线构建，无需复杂配置即可将网页打包为桌面应用。
- **轻量高效**: 应用体积仅约 5MB，比 Electron 小近 20 倍，内存占用更低。
- **功能丰富**: 支持快捷键、沉浸式窗口、拖拽、样式自定义和广告移除。
- **预置应用**: 提供 WeRead、Twitter、ChatGPT 等热门网页的预打包版本，可直接下载使用。

**技术亮点**:
- 基于 Rust 和 Tauri 框架，性能优于传统 JavaScript 框架，内存占用更低。
- 支持跨平台打包（Mac、Windows、Linux），并提供 CLI 和在线构建两种使用方式。

---
## 10. [chopratejas/headroom](https://github.com/chopratejas/headroom)
- **语言**: Python
- **Stars**: 41,957
- **简介**: Compress tool outputs, logs, files, and RAG chunks before they reach the LLM. 60-95% fewer tokens, same answers. Library, proxy, MCP server.

### AI 总结
**简介**: Headroom 是一个上下文压缩层，可在 AI 代理读取工具输出、日志、文件等之前进行压缩，减少 60-95% 的 token 数，同时保持答案质量。

**核心功能**:
- **压缩库** — 在 Python 或 TypeScript 应用中内联调用 `compress(messages)` 进行压缩
- **代理模式** — 通过 `headroom proxy` 作为透明代理运行，无需修改代码；或通过 `headroom wrap` 一键封装 Claude Code、Cursor 等代理
- **MCP 服务器** — 提供 `headroom_compress`、`headroom_retrieve`、`headroom_stats` 等工具，供任何 MCP 客户端使用
- **跨代理记忆** — 在 Claude、Codex、Gemini 等代理间共享存储，自动去重
- **`headroom learn`** — 挖掘失败会话，自动将修正写入 `CLAUDE.md` / `AGENTS.md`
- **输出 token 缩减** — 裁剪模型写回的内容（如仪式性代码、重复思考），不仅压缩输入
- **可逆压缩 (CCR)** — 原始内容本地缓存，LLM 可按需通过 `headroom_retrieve` 检索

**技术亮点**: 采用 ContentRouter 自动识别内容类型并选择最佳压缩器（SmartCrusher 压缩 JSON、CodeCompressor 基于 AST 压缩代码、Kompress-base 压缩文本）；CacheAligner 稳定前缀以利用 LLM 提供商的 KV 缓存；支持本地优先运行，数据不外泄。

---
