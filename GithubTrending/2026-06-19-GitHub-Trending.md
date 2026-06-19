---
tags:
  - github-trending
  - daily
date: 2026-06-19
created: 2026-06-19T01:55:45.445Z
---

# 2026-06-19 GitHub Trending Top 10

## 1. [google-research/timesfm](https://github.com/google-research/timesfm)
- **语言**: Python
- **Stars**: 23,217
- **简介**: TimesFM (Time Series Foundation Model) is a pretrained time-series foundation model developed by Google Research for time-series forecasting.

### AI 总结
**简介**: TimesFM 是 Google Research 开发的一个预训练时间序列基础模型，用于时间序列预测任务。

**核心功能**:
- 支持时间序列点预测和连续分位数预测（最高 1000 步）
- 提供多种部署方式：BigQuery ML、Google Sheets、Vertex Model Garden
- 支持通过 HuggingFace Transformers + PEFT (LoRA) 进行微调
- 支持协变量（XReg）和智能体（Agent）扩展

**技术亮点**: 基于 decoder-only 架构，TimesFM 2.5 版本仅 200M 参数（相比 2.0 的 500M），支持最长 16k 上下文长度，提供 PyTorch 和 Flax 两种后端，可通过 pip 安装。

---
## 2. [n0-computer/iroh](https://github.com/n0-computer/iroh)
- **语言**: Rust
- **Stars**: 10,013
- **简介**: IP addresses break, dial keys instead. Modular networking stack in Rust.

### AI 总结
**简介**: iroh 是一个用 Rust 构建的模块化网络栈，旨在通过公钥而非 IP 地址实现可靠、高效的连接。

**核心功能**:
- **公钥拨号**: 通过公钥建立连接，自动寻找并维护最快路径，无需关心 IP 地址变化。
- **NAT 穿透**: 支持打洞技术尝试建立直连，失败时可回退到公共中继服务器。
- **内置协议**: 提供基于 BLAKE3 的内容寻址传输（iroh-blobs）、可扩展的发布-订阅网络（iroh-gossip）和最终一致性键值存储（iroh-docs）等预构建协议。

**技术亮点**:
- 基于 **QUIC** 协议（使用 noq 实现），提供加密、并发流、数据报传输并避免队头阻塞。
- 持续测量网络性能以确保连接速度最优。
- 支持 Rust 原生库及通过 FFI 绑定（iroh-ffi）从其他语言调用。

---
## 3. [freeCodeCamp/freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp)
- **语言**: TypeScript
- **Stars**: 449,555
- **简介**: freeCodeCamp.org's open-source codebase and curriculum. Learn math, programming, and computer science for free.

### AI 总结
**简介**: freeCodeCamp.org 是一个开源的编程学习平台，提供免费的数学、编程和计算机科学课程，已帮助超过10万人获得第一份开发者工作。

**核心功能**:
- 提供全栈 Web 开发和机器学习课程，包含数千个交互式编程挑战
- 颁发多种免费开发者认证，包括响应式网页设计、JavaScript、Python、关系数据库等
- 提供语言认证（英语、西班牙语、中文）和面试准备资源
- 拥有活跃的社区支持，包括论坛、YouTube 频道、技术文章和 Discord 服务器

**技术亮点**: 基于 TypeScript 构建的开源代码库，支持自定进度的学习模式，采用交互式课程设计（包括课程、实践、测验和项目），并集成认证考试系统。

---
## 4. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 232,457
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套为编程代理设计的完整软件开发方法论，基于可组合的技能和初始指令，帮助代理高效、自主地完成软件开发任务。

**核心功能**:
- **需求澄清**: 代理在开始编码前，会引导用户明确需求并生成可读的设计规范。
- **实施规划**: 根据设计规范制定清晰的实施计划，遵循 TDD、YAGNI 和 DRY 原则。
- **子代理驱动开发**: 代理将任务分解为工程子任务，由子代理独立执行、审查并推进，支持数小时无人干预的自主工作。
- **多平台支持**: 可集成到 Claude Code、Cursor、Codex CLI、Gemini CLI 等多个主流编程代理平台。

**技术亮点**: 基于 Shell 脚本实现，采用可组合技能架构和自动化触发机制，确保代理从启动到任务完成无缝协作。

---
## 5. [zai-org/GLM-5](https://github.com/zai-org/GLM-5)
- **语言**: Unknown
- **Stars**: 4,144
- **简介**: GLM-5: From Vibe Coding to Agentic Engineering

### AI 总结
**简介**: GLM-5系列是智谱AI推出的新一代大语言模型，专注于复杂系统工程和长周期智能体任务，从GLM-5到GLM-5.2逐步增强长上下文和编程能力。

**核心功能**:
- **GLM-5.2**: 旗舰模型，支持1M token稳定上下文，具备灵活推理深度的高级编程能力，在Terminal-Bench 2.1和SWE-bench Pro上达到开源最强水平
- **GLM-5.1**: 下一代智能体工程模型，在SWE-Bench Pro、NL2Repo和Terminal-Bench 2.0上取得SOTA性能，能通过反复迭代在数百轮工具调用中保持高效
- **GLM-5**: 744B参数(40B活跃)基础模型，在推理、编程和智能体任务上超越所有开源模型，在Vending Bench 2长期运营基准中排名开源第一

**技术亮点**:
- **IndexShare架构(GLM-5.2)**: 每四层稀疏注意力共享同一索引器，在1M上下文长度下降低每token FLOPs 2.9倍
- **改进的MTP层**: 用于推测解码，接受长度提升最高20%
- **DeepSeek稀疏注意力(GLM-5)**: 大幅降低部署成本同时保持长上下文能力
- **slime异步RL基础设施**: 提升强化学习训练吞吐量和效率，支持更精细的后训练迭代

---
## 6. [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)
- **语言**: C
- **Stars**: 7,088
- **简介**: High-performance code intelligence MCP server. Indexes codebases into a persistent knowledge graph — average repo in milliseconds. 158 languages, sub-ms queries, 99% fewer tokens. Single static binary, zero dependencies.

### AI 总结
**简介**: 一个高性能的代码智能 MCP 服务器，可将代码库索引为持久化知识图谱，支持 158 种编程语言，毫秒级索引、亚毫秒级查询。

**核心功能**:
- **超快索引**：平均仓库毫秒级完成索引，Linux 内核（2800 万行代码，7.5 万文件）仅需 3 分钟。
- **即插即用**：单一静态二进制文件，零依赖，支持 macOS、Linux、Windows，下载后运行 `install` 即可自动配置 11 种 AI 编码代理。
- **全面语言支持**：通过内置 tree-sitter 语法分析支持 158 种语言，并为 Python、TypeScript、Go、Rust 等 10 种语言提供混合 LSP 语义类型解析。
- **知识图谱查询**：14 个 MCP 工具，可搜索函数、类、调用链、HTTP 路由和跨服务链接，查询仅需亚毫秒级，令牌消耗比逐文件搜索减少 120 倍。
- **内置可视化**：提供可选的 3D 交互式图可视化 UI（默认 localhost:9749）。
- **基础设施即代码索引**：支持对 Dockerfile、Kubernetes 清单、Kustomize 覆盖等进行索引，生成带交叉引用的图节点。

**技术亮点**:
- **纯 C 语言编写**：单一静态二进制，零外部依赖，安全性高（SLSA 3 级，每版本经 70+ 杀毒引擎扫描）。
- **RAM 优先管道**：使用 LZ4 压缩、内存 SQLite 和 Aho-Corasick 模式匹配实现极致性能，索引后释放内存。
- **基于 tree-sitter 的 AST 分析**：内置 158 种语言的语法解析器，无需额外安装。
- **混合 LSP**：结合 tree-sitter 语法分析和 LSP 语义类型解析，提升代码理解准确性。
- **arXiv 研究论文支撑**：在 31 个真实仓库上评估，达到 83% 的答案质量，10 倍更少的令牌消耗，2.1 倍更少的工具调用。

---
## 7. [yifanfeng97/Hyper-Extract](https://github.com/yifanfeng97/Hyper-Extract)
- **语言**: Python
- **Stars**: 1,793
- **简介**: Transform unstructured text into structured knowledge with LLMs. Graphs, hypergraphs, and spatio-temporal extractions — with one command.

### AI 总结
**简介**: Hyper-Extract 是一个基于 LLM 的智能知识提取与演化框架，可将非结构化文本转换为持久化、强类型化的知识摘要，支持多种知识结构（如图、超图、时空图等）。

**核心功能**:
- 支持 8 种知识结构（列表、Pydantic 模型、知识图谱、超图、时空图等）
- 集成 10+ 种提取引擎（GraphRAG、LightRAG、Hyper-RAG 等）
- 提供 80+ 个 YAML 模板，覆盖金融、法律、医疗、工业等领域
- 支持增量演化，可不断扩展和优化知识库
- 提供交互式 CLI 工具，支持一键解析、查询和可视化

**技术亮点**:
- 基于 LLM 的结构化输出能力（json_schema 或 Function Calling）
- 支持多种部署方式：OpenAI、阿里云百炼、本地 vLLM 等
- 支持语义搜索（兼容 OpenAI-compatible 的嵌入模型）
- 提供 Python API 和命令行工具两种使用方式

---
## 8. [alibaba/zvec](https://github.com/alibaba/zvec)
- **语言**: C++
- **Stars**: 11,232
- **简介**: A lightweight, lightning-fast, in-process vector database

### AI 总结
**简介**: Zvec 是阿里巴巴开源的一款轻量、高速的嵌入式向量数据库，可直接嵌入应用进程，提供生产级的低延迟相似性搜索。

**核心功能**:
- **向量搜索**: 支持稠密向量和稀疏向量，提供多种向量索引类型，可在毫秒级搜索数十亿向量。
- **全文搜索**: 原生支持基于关键词的全文搜索，可对字符串字段进行自然语言或结构化查询。
- **混合搜索**: 在同一查询中融合向量相似性、全文搜索和结构化过滤器，实现精准检索。
- **持久化存储**: 通过预写日志 (WAL) 保证数据持久性，即使进程崩溃或断电也不会丢失数据。
- **并发访问**: 支持多进程同时读取同一集合，写入为单进程独占。

**技术亮点**:
- **嵌入式设计**: 作为进程内库运行，无需独立服务器，可部署于笔记本、服务器、边缘设备等多种环境。
- **多种SDK**: 提供 Python、Node.js、Go、Rust、Dart/Flutter 等官方 SDK，易于集成。
- **DiskANN索引**: 支持磁盘索引，大幅降低大规模数据集的内存占用。
- **多平台支持**: 兼容 Python 3.10-3.14，并支持 RISC-V 架构。

---
## 9. [withastro/flue](https://github.com/withastro/flue)
- **语言**: TypeScript
- **Stars**: 5,517
- **简介**: The sandbox agent framework.

### AI 总结
**简介**: Flue 是一个基于 TypeScript 的 Agent 框架（Harness Framework），用于构建自主 AI 代理和强大的 AI 工作流。

**核心功能**:
- **Agents**: 构建能跨对话和事件保持上下文、自主工作的代理
- **Workflows**: 运行结构化自动化，用代码引导代理从明确输入到完成结果
- **Sandboxes**: 提供安全沙箱环境，让代理使用工具、修改文件并自主完成实际工作
- **Durable Execution**: 支持代理在故障和重启时保留进度，实现持久化恢复
- **Subagents**: 定义不同任务的专业角色，让代理委托工作给对应专家
- **Tools**: 为代理提供类型安全的 API 调用、数据查询和受控变更操作
- **Skills**: 封装可复用的专业知识和工作流，代理可按需加载
- **MCP Servers**: 通过开放模型上下文协议连接认证工具和服务
- **Observability**: 集成 OpenTelemetry、Braintrust、Sentry 等可观测性工具
- **Channels**: 接收来自 Slack、Teams、Discord、GitHub 等平台的已验证事件

**技术亮点**: 基于 TypeScript，提供可编程的 Agent Harness，支持本地 CLI 运行或部署到 Node.js、Cloudflare Workers、GitHub Actions 等多种环境；采用模块化包设计（`@flue/runtime`、`@flue/cli`、`@flue/sdk`）。

---
## 10. [Kilo-Org/kilocode](https://github.com/Kilo-Org/kilocode)
- **语言**: TypeScript
- **Stars**: 22,175
- **简介**: Kilo is the all-in-one agentic engineering platform. Build, ship, and iterate faster with the most popular open source coding agent.

### AI 总结
**简介**: Kilo Code 是一个开源的 AI 编码代理平台，支持在 VS Code、JetBrains、CLI 等多种环境中运行，提供 500+ 模型选择且零加价。

**核心功能**:
- 多平台支持：在 VS Code、JetBrains、CLI 及云端均可运行，并支持自动化代码审查
- 500+ 模型自由切换：任务中可随时切换模型，仅按模型提供商定价付费，无需 API 密钥即可开始
- 始终在线 AI 代理（KiloClaw）：可部署常驻的 AI 代理，持续协助开发工作

**技术亮点**: 基于 TypeScript 开发，提供 npm/curl/Homebrew 等多种安装方式，支持 Windows、macOS、Linux 多平台二进制发布。

---
