---
tags:
  - github-trending
  - daily
date: 2026-07-19
created: 2026-07-19T01:55:43.281Z
---

# 2026-07-19 GitHub Trending Top 10

## 1. [Robbyant/lingbot-map](https://github.com/Robbyant/lingbot-map)
- **语言**: Python
- **Stars**: 12,977
- **简介**: A feed-forward 3D foundation model for reconstructing scenes from streaming data

### AI 总结
**简介**: LingBot-Map 是一个基于前馈架构的 3D 基础模型，能够从流式数据中实时重建场景。

**核心功能**:
- 流式 3D 重建：支持从连续视频帧流（超过 10,000 帧）中增量式构建场景。
- 交互式演示：提供 `demo.py` 脚本，支持关键帧间隔、窗口推理、天空掩码等参数调节。
- 离线渲染管线：通过 `batch_demo.py` 支持长视频的高质量离线渲染。
- 多数据集评估：内置 KITTI、Oxford Spires、VBR、TUM-D 等 8 个数据集的评估基准。

**技术亮点**:
- 几何上下文 Transformer（GCT）架构：通过锚点上下文、姿态参考窗口和轨迹记忆统一处理坐标对齐、密集几何线索和长程漂移校正。
- 高效流式推理：采用分页 KV 缓存注意力机制，在 518×378 分辨率下可实现约 20 FPS 的稳定推理。
- 支持 PyTorch 2.8（CUDA 12.8）和 FlashInfer 后端，提供编译加速选项。

---
## 2. [apache/ossie](https://github.com/apache/ossie)
- **语言**: Python
- **Stars**: 1,281
- **简介**: Apache Ossie, industry wide specification effort to standardize how we exchange semantic metadata across analytics, AI and BI platforms, providing a vendor neutral, single source of truth for semantic data

### AI 总结
**简介**: Apache Ossie 是一个开源的行业规范项目，旨在标准化跨分析、AI 和 BI 平台的语义元数据交换，提供厂商中立的语义数据单一来源。

**核心功能**:
- 提供基于 JSON 和 YAML 的单一语义模型规范，任何工具均可读写
- 包含核心规范、机器可读的 schema 和参考文档
- 提供参考转换器，支持与 dbt、GoodData、Polaris、Salesforce 等格式互转
- 包含示例语义模型（如完整的 TPC-DS 模型）
- 提供语义模型验证工具

**技术亮点**: 基于 Python 开发，采用 JSON/YAML 格式规范，支持多平台语义元数据标准化交换，提供厂商中立的统一语义数据源。

---
## 3. [PostHog/posthog](https://github.com/PostHog/posthog)
- **语言**: Python
- **Stars**: 36,607
- **简介**: 🦔 PostHog is the leading platform for building self-driving products. Our developer tools – AI observability, analytics, session replay, flags, experiments, error tracking, logs, and more – capture all the context agents need to diagnose problems, uncover opportunities, and ship fixes. Steer it all from Slack, web, desktop, or the MCP.

### AI 总结
**简介**: PostHog 是一个开源平台，提供构建自驱动产品所需的全部工具，包括 AI 可观测性、分析、会话回放、功能标志、实验、错误追踪、日志等，并支持从 Slack、Web、桌面或 MCP 进行控制。

**核心功能**:
- **自驱动模式**: 将产品数据中的信号（如错误、愤怒点击）自动转化为研究报告和拉取请求。
- **产品分析**: 自动捕获或手动埋点，支持基于事件的分析和 SQL 查询。
- **Web 分析**: 监控网站流量和用户会话，提供类似 GA 的仪表盘。
- **会话回放**: 观看真实用户与网站或移动应用的交互过程，诊断问题。
- **功能标志**: 安全地向特定用户或用户群推出新功能。
- **实验**: 测试变更并衡量其对目标指标的统计影响，支持无代码实验。
- **错误追踪**: 追踪错误、接收警报并解决问题。
- **日志**: 引入、搜索和分析日志数据。
- **调查**: 提供无代码调查模板和自定义调查构建器。
- **数据仓库**: 同步外部工具数据（如 Stripe、Hubspot）并与产品数据联合查询。
- **数据管道**: 对传入数据运行自定义过滤和转换，实时或批量导出到 25+ 工具。
- **AI 可观测性**: 捕获 LLM 应用的追踪、生成、延迟和成本。
- **工作流**: 创建自动化工作流执行操作或向用户发送消息。

**技术亮点**: 基于 Python 开发，支持云部署和自托管，提供慷慨的免费月度配额。

---
## 4. [ibelick/ui-skills](https://github.com/ibelick/ui-skills)
- **语言**: TypeScript
- **Stars**: 5,041
- **简介**: Skills for Design Engineers

### AI 总结
**简介**: 一个面向设计工程师的 UI 技能工具集，提供 CLI 来路由任务到合适的 UI 技能。  
**核心功能**:  
- 通过 `npx ui-skills` 快速启动 CLI 工具  
- 按类别（如 motion）列出 UI 技能  
- 获取特定技能（如 baseline-ui）的详细信息  
**技术亮点**: 基于 TypeScript 开发，通过 CLI 提供即用型技能路由。

---
## 5. [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch)
- **语言**: Python
- **Stars**: 39,119
- **简介**: Learn it. Build it. Ship it for others.

### AI 总结
**简介**: 一个从零开始构建AI工程能力的开源课程，包含503节课、20个阶段，覆盖从数学基础到自主多智能体系统的完整学习路径。

**核心功能**:
- 提供系统化的AI工程课程，涵盖线性代数、深度学习、Transformer、LLM、多模态、Agent工程等20个阶段
- 每个课程都包含可运行的代码实现（Python/TypeScript/Rust/Julia）和可复用的产出物（提示词、技能、Agent、MCP服务器）
- 基于“先推导数学，再编写代码，最后测试”的教学循环，确保理解算法底层原理
- 支持本地运行，完全免费开源（MIT协议）

**技术亮点**: 采用多语言实现（Python/TypeScript/Rust/Julia），从原始数学构建每个算法（反向传播、分词器、注意力机制、Agent循环），包含完整的生产级基础设施和自主系统设计。

---
## 6. [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)
- **语言**: Python
- **Stars**: 20,190
- **简介**: Local-first code intelligence graph for MCP and CLI. Builds a persistent map of your codebase so AI coding tools read only what matters, with benchmarked context reductions on reviews and large-repo workflows.

### AI 总结
**简介**: 一个本地优先的代码智能图工具，为 MCP 和 CLI 提供代码库结构映射，显著减少 AI 代码审查时的 Token 消耗。

**核心功能**:
- 使用 Tree-sitter 构建代码库的结构化图，并增量跟踪变更。
- 通过 MCP 协议为 AI 编程工具提供精确的代码上下文，减少冗余读取。
- 一键安装并自动配置 Codex、Claude Code、Cursor 等 14 种主流 AI 编程平台。
- 提供 `build`、`install`、`uninstall` 等命令行工具，支持 Git 和 SVN 项目。

**技术亮点**: 基于 Python 3.10+，使用 Tree-sitter 进行语法解析，通过 MCP 协议与 AI 工具集成，支持增量更新，可大幅降低代码审查时的 Token 使用量（实测降低 38x 至 528x）。

---
## 7. [elder-plinius/G0DM0D3](https://github.com/elder-plinius/G0DM0D3)
- **语言**: TypeScript
- **Stars**: 9,519
- **简介**: LIBERATED AI CHAT

### AI 总结
**简介**: G0DM0D3 是一个完全开源、注重隐私、支持多模型的 AI 聊天界面，旨在突破后训练层的限制，用于红队测试、认知研究和自由的 AI 交互。

**核心功能**:
- **多模型提供商**: 支持 OpenRouter 上的 60 多种模型、Venice 的 44 种模型，以及本地模型。
- **GODMODE CLASSIC**: 并行运行 5 种经过实战测试的提示词与模型组合，以找到最佳响应。
- **ULTRAPLINIAN**: 跨 5 个层级（12-60 个 OpenRouter 模型）的多模型评估引擎，提供综合评分。
- **本地模型支持**: 通过 Ollama、LM Studio、llama.cpp 或 vLLM 在本地硬件上运行 ULTRAPLINIAN。
- **Parseltongue**: 用于红队测试的输入扰动引擎，包含 3 个强度级别的 33 种技术。
- **AutoTune**: 跨 20 个查询上下文的上下文自适应采样参数引擎。
- **隐私控制**: 可关闭的应用遥测功能，支持无日志或纯本地模式。
- **本地历史记录**: 对话和设置存储在浏览器中，支持导出/导入。
- **响应式设计**: 支持桌面端和移动端。

**技术亮点**:
- **技术栈**: TypeScript，单文件核心 UI (`index.html`)。
- **架构**: 无构建步骤，可静态部署，遥测端点作为独立的 Cloudflare Pages Function 实现。
- **隐私优先**: 默认仅收集元数据，可完全禁用，支持纯本地模式。

---
## 8. [lyogavin/airllm](https://github.com/lyogavin/airllm)
- **语言**: Jupyter Notebook
- **Stars**: 23,342
- **简介**: AirLLM 70B inference with single 4GB GPU

### AI 总结
**简介**: AirLLM 是一个能让 70B 大语言模型在单张 4GB GPU 上运行的高效推理库，无需量化、蒸馏或剪枝，甚至支持 405B Llama 3.1 和 671B DeepSeek-V3 等超大规模模型。

**核心功能**:
- 支持在极低显存（4GB GPU）上运行 70B 级别的大模型，如 Llama 3、Qwen3 等
- 支持 FP8 模型格式，可运行 DeepSeek-V3（671B）在约 12GB 显存、Qwen3-235B 在约 3GB 显存
- 通过 `AutoModel` 自动检测模型类型，兼容 Hugging Face 仓库 ID 或本地路径
- 支持 CPU 推理、8bit/4bit 量化、非分片模型加载
- 提供 MacOS 支持，可在 Mac 上运行 70B 模型
- 内置预取技术，将模型加载与计算重叠，提升约 10% 的推理速度
- 支持模型压缩，实现约 3 倍运行时加速

**技术亮点**:
- 基于层分片（layer sharding）技术，将模型逐层加载到 GPU 内存，大幅降低推理显存需求
- 采用预取机制优化 I/O 与计算重叠，提升推理效率
- 支持多种主流模型架构（Llama、Qwen、DeepSeek、ChatGLM、Mistral 等），通过 `AutoModel` 实现一键加载
- 提供 FP8 等低精度格式支持，进一步压缩显存占用

---
## 9. [KnockOutEZ/wigolo](https://github.com/KnockOutEZ/wigolo)
- **语言**: TypeScript
- **Stars**: 1,256
- **简介**: The go-to web for your AI coding agent — local-first search, fetch, crawl & research over MCP. No API keys, no cloud, $0/query. Public beta.

### AI 总结
**简介**: wigolo 是一个本地优先的 AI 智能体网页智能工具，无需 API 密钥、无需云服务、按查询计费为零，通过 MCP 协议提供搜索、抓取、爬取和研究等功能。

**核心功能**:
- 搜索、获取、爬取、提取、缓存、相似查找和研究等网页相关工具
- 支持自主收集循环的智能体模式
- 可作为 MCP 服务器、REST/MCP 端点或通过 SDK 嵌入使用
- 支持多种 AI 智能体客户端（Claude Code、Cursor、Codex 等）
- 结果包含带引用的证据片段，便于智能体引用和验证

**技术亮点**: 采用 TypeScript 开发，基于 MCP（Model Context Protocol）协议，支持本地浏览器引擎和端侧模型，无需外部 API 密钥即可运行核心功能，所有数据存储在本地 `~/.wigolo/` 目录下。兼容多种 AI 框架（LangChain、CrewAI、LlamaIndex 等）和客户端。

---
## 10. [codecrafters-io/build-your-own-x](https://github.com/codecrafters-io/build-your-own-x)
- **语言**: Markdown
- **Stars**: 528,301
- **简介**: Master programming by recreating your favorite technologies from scratch.

### AI 总结
**简介**: 一个汇集了从零开始重建各种经典技术（如3D渲染器、数据库、操作系统等）的优质教程合集，旨在通过动手实践加深对技术原理的理解。

**核心功能**:
- 提供30+类技术的重建教程，涵盖3D渲染器、AI模型、区块链、数据库、Docker、操作系统等
- 每个技术分类下包含多语言（C++、Python、Java、JavaScript等）的详细步骤指南
- 教程来源包括知名博客、开源项目、书籍和视频课程

**技术亮点**: 采用"从零重建"的学习方法，强调通过实践掌握核心技术原理；教程覆盖从底层系统（处理器、内存分配器）到上层应用（Web浏览器、搜索引擎）的完整技术栈。

---
