---
tags:
  - github-trending
  - daily
date: 2026-06-20
created: 2026-06-20T01:55:44.045Z
---

# 2026-06-20 GitHub Trending Top 10

## 1. [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)
- **语言**: C
- **Stars**: 8,273
- **简介**: High-performance code intelligence MCP server. Indexes codebases into a persistent knowledge graph — average repo in milliseconds. 158 languages, sub-ms queries, 99% fewer tokens. Single static binary, zero dependencies.

### AI 总结
**简介**: 一个高性能的代码智能 MCP 服务器，能将代码库索引为持久化知识图谱，支持毫秒级查询，显著减少令牌消耗。

**核心功能**:
- **极速索引**: 平均仓库毫秒级完成全索引，Linux 内核（2800万行代码、7.5万文件）仅需3分钟。
- **即插即用**: 单一静态二进制文件，无依赖、无运行时环境要求，下载后运行 `install` 即可自动配置11种编码代理。
- **多语言支持**: 通过 tree-sitter 支持158种语言的 AST 分析，并对 Python、TypeScript、C++ 等9种语言提供混合 LSP 语义类型解析。
- **知识图谱查询**: 提供14个 MCP 工具，支持函数、类、调用链、HTTP 路由等结构化查询，单次查询仅需约3,400 tokens，比逐文件搜索减少120倍。
- **内置可视化**: 可选的3D交互式图谱 UI，运行于 localhost:9749，方便探索知识结构。
- **基础设施即代码索引**: 支持 Dockerfiles、Kubernetes 清单等作为图谱节点进行索引和交叉引用。

**技术亮点**: 纯 C 语言编写，零依赖；采用 RAM 优先管道（LZ4 压缩、内存 SQLite、Aho-Corasick 模式匹配）实现极致性能；所有处理完全本地化，代码不离开本机；通过 SLSA 3 级和 VirusTotal 扫描确保安全。

---
## 2. [google-research/timesfm](https://github.com/google-research/timesfm)
- **语言**: Python
- **Stars**: 24,099
- **简介**: TimesFM (Time Series Foundation Model) is a pretrained time-series foundation model developed by Google Research for time-series forecasting.

### AI 总结
**简介**: TimesFM 是 Google Research 开发的预训练时间序列基础模型，专门用于时间序列预测。

**核心功能**:
- 支持高精度时间序列点预测和分位数预测（10th-90th 分位数）
- 提供多种预训练模型版本（2.5/2.0/1.0），支持 16k 上下文长度和 1k 预测范围
- 支持连续分位数预测头（可选 30M 参数）
- 提供基于 HuggingFace Transformers + PEFT (LoRA) 的微调示例
- 支持协变量（通过 XReg）和 Agent 技能集成
- 集成到 Google 产品生态（BigQuery ML、Google Sheets、Vertex Model Garden）

**技术亮点**: 基于 decoder-only 架构（ICML 2024 论文），2.5 版本仅 200M 参数（较 2.0 的 500M 降低），支持 PyTorch 和 Flax 双后端推理，具备强制翻转不变性、输入归一化、分位数交叉修正等高级特性。

---
## 3. [palmier-io/palmier-pro](https://github.com/palmier-io/palmier-pro)
- **语言**: Swift
- **Stars**: 1,955
- **简介**: macOS video editor built for AI

### AI 总结
**简介**: Palmier Pro 是一款专为 AI 打造的 macOS 开源视频编辑器，支持用户与 AI 代理在时间线中协同生成和编辑视频。

**核心功能**:
- 原生 Swift 构建的视频编辑器，对标 Adobe Premiere Pro 并集成 AI 工作流
- 内置生成式 AI，支持 Seedance、Kling、Nano Banana Pro 等模型直接在时间线内生成视频和图像
- 通过 MCP 协议与 Claude、Codex、Cursor 等 AI 代理集成，支持应用内代理协作编辑

**技术亮点**: 使用 Swift 原生开发，基于 Apple Silicon 的 macOS 26 (Tahoe) 平台；编辑器核心、MCP 服务器和代理聊天功能完全开源（GPLv3），仅生成式 AI 处理部分闭源。

---
## 4. [koala73/worldmonitor](https://github.com/koala73/worldmonitor)
- **语言**: TypeScript
- **Stars**: 57,278
- **简介**: Real-time global intelligence dashboard. AI-powered news aggregation, geopolitical monitoring, and infrastructure tracking in a unified situational awareness interface

### AI 总结
**简介**: 一个基于AI的实时全球情报仪表盘，聚合新闻、监控地缘政治与基础设施，提供统一的态势感知界面。

**核心功能**:
- **AI新闻聚合**: 整合500+经过筛选的新闻源，覆盖15个类别，由AI自动生成简报。
- **双地图引擎**: 支持3D地球仪 (globe.gl) 和 WebGL 平面地图 (deck.gl)，提供56种地图图层。
- **跨流关联分析**: 识别军事、经济、灾害等事件间的关联信号与升级趋势。
- **国家不稳定指数 (CII)**: 对31个一级国家进行压力评分（CII v8）。
- **金融雷达**: 监控29个证券交易所、大宗商品、加密货币及7种市场复合信号。
- **本地AI支持**: 可运行Ollama，无需API密钥即可本地处理。
- **多站点变体**: 从一个代码库生成6种主题站点（世界、科技、金融等）。
- **原生桌面应用**: 基于Tauri 2构建，支持macOS、Windows和Linux。
- **多语言支持**: 提供24种语言界面及本地语言新闻源。

**技术亮点**: 使用TypeScript开发，采用单一代码库构建多站点及桌面应用，架构支持本地AI部署与实时数据流处理。

---
## 5. [aishwaryanr/awesome-generative-ai-guide](https://github.com/aishwaryanr/awesome-generative-ai-guide)
- **语言**: HTML
- **Stars**: 27,643
- **简介**: A one stop repository for generative AI research updates, interview resources, notebooks and much more!

### AI 总结
**简介**: 一个一站式生成式AI资源中心，汇集研究动态、面试资料、实战教程及免费课程，助力开发者快速掌握GenAI技术。

**核心功能**:
- **月度精选论文列表**: 每月更新最佳生成式AI论文。
- **面试准备资源**: 提供常见面试题及备考指南。
- **免费课程体系**: 包括Applied LLMs Mastery、GenAI Genius、AI Evals等认证课程（超90门）。
- **实战代码仓库**: 提供开发GenAI应用的Notebook和代码库。
- **学习路线图**: 覆盖RAG、LLM基础、智能体等主题的按日规划路线。
- **AI工具推荐**: 整理全栈AI应用开发工具清单。

**技术亮点**: 基于HTML构建，内容结构化分层，集成Notion课程平台与GitHub仓库，支持证书认证体系。

---
## 6. [BuilderIO/agent-native](https://github.com/BuilderIO/agent-native)
- **语言**: TypeScript
- **Stars**: 1,060
- **简介**: A framework for building agent-native applications.

### AI 总结
**简介**: Agent-Native 是一个开源的 TypeScript 框架，用于构建“代理原生”应用，其核心理念是让自主代理（Agent）与用户界面（UI）深度融合、双向同步，而非仅作为聊天框存在。

**核心功能**:
- **Agent 与 UI 完全同步**: 共享同一数据库和状态，任何一方的更改都会即时反映在另一方。
- **实时多人协作**: 支持人类与代理在同一文档中实时协作，包括 CRDT 合并、光标和选中状态等。
- **上下文感知**: 代理能感知用户当前关注的内容，支持选中文本后直接下达指令。
- **可复用集成**: 通过 Dispatch 模块连接外部服务，管理密钥和账户元数据，供多个应用共享。
- **三种应用形态**: 同一套底层技术支持构建为无头 API、富聊天界面或完整的全功能应用。
- **应用自我改进**: 代理能自主为应用添加新功能、修复 Bug 并优化 UI。
- **代理间通信 (A2A)**: 不同应用中的代理可以相互发现和调用，跨应用协作。
- **无锁定**: 支持任何 Drizzle 兼容的 SQL 数据库以及任何 Nitro 兼容的主机环境。

**技术亮点**: 采用 TypeScript 构建，后端无关（支持任意 SQL 数据库和主机），通过 `defineAction` 定义一次即可用于 UI、Agent、HTTP、MCP、A2A 和 CLI 等多种场景。内置了 Agent 运行时（含聊天、工具、技能、记忆、任务、可观测性等），并原生支持 A2A、MCP 等协议。

---
## 7. [chopratejas/headroom](https://github.com/chopratejas/headroom)
- **语言**: Python
- **Stars**: 38,800
- **简介**: Compress tool outputs, logs, files, and RAG chunks before they reach the LLM. 60-95% fewer tokens, same answers. Library, proxy, MCP server.

### AI 总结
**简介**: Headroom 是一个 AI 上下文压缩层，可在工具输出、日志、文件等到达大模型前压缩内容，节省 60-95% 的 token 数，同时保持答案质量。

**核心功能**:
- **库模式**: 在 Python 或 TypeScript 应用中通过 `compress(messages)` 直接调用压缩
- **代理模式**: 通过 `headroom proxy` 运行本地代理，零代码修改即可压缩请求
- **智能压缩**: 支持 JSON 压缩、AST 代码压缩和文本压缩，自动识别内容类型选择最佳算法
- **可逆压缩 (CCR)**: 缓存原始内容，LLM 可通过 `headroom_retrieve` 按需获取完整信息
- **跨代理记忆**: 共享存储支持 Claude、Codex、Gemini 等工具间的去重记忆
- **学习机制**: `headroom learn` 可从失败会话中挖掘经验，自动写入 `CLAUDE.md` / `AGENTS.md`
- **输出 token 缩减**: 不仅压缩输入，还可减少模型输出中的冗余内容

**技术亮点**: 采用 ContentRouter 自动识别内容类型、CacheAligner 稳定前缀以利用 KV 缓存、6 种压缩算法（包括基于 Hugging Face 的 Kompress-v2-base 模型），支持本地优先运行确保数据安全，提供 MCP 服务器接口。

---
## 8. [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)
- **语言**: Python
- **Stars**: 6,314
- **简介**: World's first open-source, agentic video production system. 12 pipelines, 52 tools, 500+ agent skills. Turn your AI coding assistant into a full video production studio.

### AI 总结
**简介**: 首个开源智能体视频制作系统，支持通过自然语言描述全自动完成视频生产。

**核心功能**:
- 12条视频制作流水线，覆盖从脚本、素材生成到剪辑的全流程
- 52个工具模块，支持真实视频素材检索、AI生成图像/视频、语音合成、字幕制作等
- 500+智能体技能，可通过AI编码助手调用完成复杂视频项目
- 支持多模态输出：AI生成图像动画、实拍素材剪辑、混合风格视频

**技术亮点**:
- 基于Remotion动画引擎实现零视频API的图像动画（相机运动、粒子特效、交叉淡入淡出）
- 集成Veo、Kling v3、FLUX等AI视频/图像生成模型，支持免费开源工作流（如免费素材库检索）
- 支持WhisperX词级字幕、Chirp3-HD语音、自动版权音乐匹配
- 单项目最低成本仅$0.15（纯图像动画）至$1.33（含AI视频片段）

---
## 9. [zai-org/GLM-5](https://github.com/zai-org/GLM-5)
- **语言**: Unknown
- **Stars**: 4,592
- **简介**: GLM-5: From Vibe Coding to Agentic Engineering

### AI 总结
**简介**: GLM-5 系列是由 z.ai 开发的面向复杂系统工程和长周期代理任务的开源大语言模型，包含 GLM-5、GLM-5.1 和 GLM-5.2 三个版本，在编码、推理和长上下文处理上实现显著突破。

**核心功能**:
- **GLM-5.2**: 支持稳定的 1M token 长上下文，具备可调节思考强度的增强编码能力，在 Terminal-Bench 2.1 和 SWE-bench Pro 等基准测试中达到开源模型最强水平。
- **GLM-5.1**: 面向代理工程，在 SWE-Bench Pro、NL2Repo 和 Terminal-Bench 2.0 上取得领先性能，擅长通过数百轮迭代和工具调用持续优化复杂问题。
- **GLM-5**: 744B 参数（40B 激活）规模，在推理、编码和代理任务上取得开源模型最佳表现，并在 Vending Bench 2 长周期运营基准中排名第一。

**技术亮点**:
- **IndexShare 架构**: 在稀疏注意力层间复用索引器，1M 上下文长度下每 token FLOPs 减少 2.9 倍。
- **MTP 推测解码**: 改进的预测层将接受长度提升最高 20%。
- **DeepSeek Sparse Attention (DSA)**: 降低部署成本，保持长上下文能力。
- **异步 RL 基础设施 slime**: 大幅提升强化学习训练吞吐量和效率，支持更细粒度的后训练迭代。

---
## 10. [withastro/flue](https://github.com/withastro/flue)
- **语言**: TypeScript
- **Stars**: 5,847
- **简介**: The sandbox agent framework.

### AI 总结
**简介**: Flue 是一个用 TypeScript 构建的自主智能体框架，提供可编程的 harness，让开发者能够构建能独立完成复杂任务的 AI 智能体。

**核心功能**:
- **Agents**: 构建能在对话和事件中保持上下文、自主完成目标的智能体
- **Workflows**: 运行结构化自动化，用代码引导智能体从输入到输出
- **Sandboxes**: 为智能体提供安全的执行环境，支持本地、远程或虚拟容器
- **Durable Execution**: 智能体在失败和重启时能持久化恢复进度
- **Subagents**: 定义专业化角色，让智能体委派任务给合适的专家
- **Tools**: 为智能体提供类型化的 API 调用、数据查询和变更操作
- **Skills**: 封装可复用的专业知识和流程，智能体可按需加载
- **MCP Servers**: 通过开放协议连接认证的工具和服务
- **Observability**: 集成 OpenTelemetry、Braintrust、Sentry 等监控工具
- **Channels**: 接收来自 Slack、Teams、Discord、GitHub 等平台的验证事件

**技术亮点**: 基于 TypeScript 的类型安全架构，支持多种部署环境（Node.js、Cloudflare Workers、GitHub Actions 等），提供 CLI 工具和客户端 SDK，采用模块化包设计（`@flue/runtime`、`@flue/cli`、`@flue/sdk`）。

---
