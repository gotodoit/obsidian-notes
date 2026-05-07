---
tags:
  - github-trending
  - daily
date: 2026-05-07
created: 2026-05-07T01:55:44.928Z
---

# 2026-05-07 GitHub Trending Top 10

## 1. [Hmbown/DeepSeek-TUI](https://github.com/Hmbown/DeepSeek-TUI)
- **语言**: Rust
- **Stars**: 14,285
- **简介**: Coding agent for DeepSeek models that runs in your terminal

### AI 总结
**简介**: 一个基于 DeepSeek V4 模型、在终端中运行的编码助手，支持代码编辑、命令执行、Web 搜索等功能。

**核心功能**:
- **多模式操作**: 支持 Plan（只读探索）、Agent（交互式审批）、YOLO（自动审批）三种模式
- **全工具套件**: 文件操作、Shell 执行、Git 管理、Web 搜索/浏览、补丁应用、子代理、MCP 服务器
- **智能会话管理**: 会话保存/恢复、工作区回滚、持久化任务队列
- **自动模式**: 根据每轮任务自动选择模型和思考级别
- **实时反馈**: 流式显示推理过程、LSP 诊断集成、成本追踪
- **多语言支持**: 支持中、英、日、葡萄牙语界面
- **技能系统**: 可组合的指令包，支持从 GitHub 安装

**技术亮点**:
- **Rust 实现**的高性能 TUI（基于 ratatui 框架）
- **1M-token 上下文窗口**支持，含前缀缓存感知的成本报告
- **MCP 协议**集成，可扩展外部工具
- **原生 RLM**（递归语言模型）支持批处理分析
- **多种安装方式**: npm、Cargo、Homebrew、直接下载预编译二进制

---
## 2. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: Shell
- **Stars**: 30,647
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 该项目为AI编码代理提供了一套生产级的工程技能，将资深工程师的工作流、质量门禁和最佳实践编码为结构化指令，使AI代理能在软件开发的各个阶段一致地遵循。

**核心功能**:
- **开发生命周期命令**: 提供7个斜杠命令（`/spec`, `/plan`, `/build`, `/test`, `/review`, `/code-simplify`, `/ship`），分别对应从需求定义到生产交付的各个阶段，自动激活相应的技能。
- **20个结构化技能**: 包含从想法提炼、规范驱动开发、计划与任务分解到代码简化等20个技能，每个技能都包含步骤、验证门禁和反合理化表。
- **多平台兼容**: 支持在Claude Code、Cursor、Gemini CLI、Windsurf、OpenCode、GitHub Copilot、Kiro IDE及Codex等多种AI代理工具中安装和使用。

**技术亮点**: 技能以纯Markdown文件形式存在，通过`SKILL.md`和`AGENTS.md`等标准文件与不同AI工具集成，实现了跨平台、可插拔的工程最佳实践封装。

---
## 3. [PriorLabs/TabPFN](https://github.com/PriorLabs/TabPFN)
- **语言**: Python
- **Stars**: 6,592
- **简介**: ⚡ TabPFN: Foundation Model for Tabular Data ⚡

### AI 总结
**简介**: TabPFN 是一个基于 Transformer 架构的表格数据基础模型，支持分类与回归任务，无需数据预处理即可直接使用。

**核心功能**:
- 提供 `TabPFNClassifier` 和 `TabPFNRegressor` 开箱即用的分类/回归接口
- 支持多种模型版本切换（如 V2.5、V2.6）
- 通过批预测模式提升大规模测试集推理效率
- 提供 Colab 交互式 Notebook 快速上手教程
- 配套生态系统包含客户端、扩展库（可解释性、无监督、嵌入提取、多类分类等）

**技术亮点**: 基于纯合成数据训练的 Transformer 架构，无需数据缩放或独热编码；GPU 推荐以获得最优性能（8GB VRAM 即可运行大多数场景）。

---
## 4. [docusealco/docuseal](https://github.com/docusealco/docuseal)
- **语言**: Ruby
- **Stars**: 14,922
- **简介**: Open source DocuSign alternative. Create, fill, and sign digital documents ✍️

### AI 总结
**简介**: DocuSeal 是一个开源的文档填写与数字签名平台，可作为 DocuSign 的替代方案，支持在任意设备上创建、填写和签署 PDF 表单。

**核心功能**:
- PDF 表单构建器（所见即所得），支持 12 种字段类型（签名、日期、文件、复选框等）
- 每个文档支持多个签署人，自动通过 SMTP 发送邮件
- 文件存储支持本地磁盘或 AWS S3、Google Storage、Azure Cloud 等云服务
- 自动 PDF 电子签名及签名验证
- 用户管理、移动端优化、支持 7 种 UI 语言和 14 种签署语言
- 提供 API 和 Webhooks 用于集成

**技术亮点**: 基于 Ruby 开发，支持 Docker 快速部署（可选用 SQLite、PostgreSQL 或 MySQL 数据库），并提供针对 Heroku、Railway、DigitalOcean、Render 等平台的一键部署方案。Pro 版本支持白标、SAML/SSO、HTML/PDF/DOCX 模板创建及嵌入式签名表单（React/Vue/Angular/JavaScript 组件）。

---
## 5. [LearningCircuit/local-deep-research](https://github.com/LearningCircuit/local-deep-research)
- **语言**: Python
- **Stars**: 5,682
- **简介**: ~95% on SimpleQA (e.g. Qwen3.6-27B on a 3090). Supports all local and cloud LLMs (llama.cpp, Ollama, Google, ...). 10+ search engines - arXiv, PubMed, your private documents. Everything Local & Encrypted.

### AI 总结
**简介**: 一个开源的 AI 研究助手，支持本地运行，可连接多种 LLM 和搜索引擎，实现深度、可溯源的研究工作流。

**核心功能**:
- 支持所有本地和云端 LLM（如 llama.cpp、Ollama、Google 等），可在 NVIDIA 3090 上运行 Qwen3.6-27B 达到约 95% 的 SimpleQA 准确率
- 集成 10+ 搜索引擎，包括 arXiv、PubMed 等学术源，并支持私有文档检索
- 所有数据本地存储且加密（使用 SQLCipher），用户完全掌控数据隐私

**技术亮点**:
- 基于 Python 开发，支持 Docker 一键部署（CPU/GPU 版本）和 pip 安装
- 预编译 wheels 提供 SQLCipher 加密支持，无需手动编译
- 采用多 LLM 协作的代理式研究架构，自动生成含引用来源的深度研究报告

---
## 6. [LadybirdBrowser/ladybird](https://github.com/LadybirdBrowser/ladybird)
- **语言**: C++
- **Stars**: 62,994
- **简介**: Truly independent web browser

### AI 总结
**简介**: Ladybird 是一款基于全新引擎、完全独立的 Web 浏览器，目前处于预 alpha 阶段，仅适合开发者使用。

**核心功能**:
- 多进程架构，包含主 UI 进程、WebContent 渲染器进程、ImageDecoder 进程和 RequestServer 进程
- 每个标签页拥有独立的渲染器进程，并与其他系统部分隔离
- 支持图像解码和网络连接在进程外处理，增强安全性
- 继承自 SerenityOS 的核心库组件，包括 Web 渲染引擎、JavaScript 引擎、WebAssembly 实现等

**技术亮点**: 使用 C++ 开发，采用多进程架构；核心技术栈包括 LibWeb（Web 渲染引擎）、LibJS（JavaScript 引擎）、LibWasm（WebAssembly 实现）、LibCrypto/LibTLS（加密和传输层安全）、LibHTTP（HTTP/1.1 客户端）、LibGfx（2D 图形库）、LibUnicode（Unicode 和本地化支持）、LibMedia（音视频播放）、LibCore（事件循环和操作系统抽象层）和 LibIPC（进程间通信）。

---
## 7. [InsForge/InsForge](https://github.com/InsForge/InsForge)
- **语言**: TypeScript
- **Stars**: 8,477
- **简介**: InsForge is a Postgres-based backend with auth, storage, compute, hosting, and AI gateway. Built for coding agents.

### AI 总结
**简介**: InsForge 是一个基于 Postgres 的后端平台，专为 AI 编码代理设计，提供认证、存储、计算、托管和 AI 网关等后端原语。

**核心功能**:
- **语义层交互**: 作为 AI 编码代理与后端原语之间的语义层，使代理能够理解、推理和操作后端系统。
- **后端上下文工程**: 提供文档和可用操作的获取、后端原态配置以及后端状态和日志的结构化检查。
- **后端原语支持**: 包括认证、数据库、存储、边缘函数等完整后端能力。

**技术亮点**:
- 基于 TypeScript 开发，采用 Postgres 作为核心数据库。
- 支持 Docker 快速本地部署，提供 MCP 服务器集成。
- 采用语义层架构，专为 AI 原生开发者优化。

---
## 8. [virattt/dexter](https://github.com/virattt/dexter)
- **语言**: TypeScript
- **Stars**: 24,381
- **简介**: An autonomous agent for deep financial research

### AI 总结
**简介**: Dexter 是一个专为金融研究设计的自主智能体，能够通过任务规划、自我反思和实时市场数据，自动完成复杂的金融分析工作。

**核心功能**:
- **智能任务规划**: 自动将复杂查询分解为结构化的研究步骤
- **自主执行**: 选择并执行合适的工具来获取金融数据
- **自我验证**: 检查自身工作并迭代优化，直至获得可靠结果
- **实时金融数据**: 支持获取损益表、资产负债表和现金流量表等数据
- **安全机制**: 内置循环检测和步骤限制，防止无限执行

**技术亮点**:
- 使用 TypeScript 开发，基于 Bun 运行时
- 集成 OpenAI、Anthropic、Google 等多种 LLM 提供商
- 支持 Financial Datasets API 获取机构级市场数据
- 通过 Exa/Tavily API 实现网络搜索能力
- 提供评估套件，使用 LangSmith 和 LLM-as-judge 进行正确性评分
- 支持 WhatsApp 集成和交互式/开发模式运行

---
## 9. [anthropics/financial-services](https://github.com/anthropics/financial-services)
- **语言**: Python
- **Stars**: 9,196
- **简介**: 

### AI 总结
**简介**: 专为金融服务行业（投资银行、股权研究、私募股权和财富管理）设计的Claude代理、技能和数据连接器集合，支持作为Cowork插件或通过Managed Agents API部署。

**核心功能**:
- **覆盖与咨询**: 提供Pitch Agent（制作推介材料）和Meeting Prep Agent（客户会议简报）
- **研究与建模**: 包括Market Researcher（行业研究）、Earnings Reviewer（财报分析）、Model Builder（DCF/LBO/三表模型）
- **基金管理与财务运营**: Valuation Reviewer（估值审核）、GL Reconciler（总账对账）、Month-End Closer（月末结账）、Statement Auditor（报表审计）
- **运营与入职**: KYC Screener（合规筛查）

**技术亮点**: 
- 同一代码库同时支持Cowork插件和Managed Agent API两种部署方式
- 插件按垂直领域（投资银行、私募股权等）分类，支持独立安装
- 包含合作伙伴构建的插件（LSEG、S&P Global）和MCP连接器
- 提供完整的Managed Agent部署指南（agent.yaml、子代理、安全配置）

---
## 10. [ruvnet/ruflo](https://github.com/ruvnet/ruflo)
- **语言**: TypeScript
- **Stars**: 45,309
- **简介**: 🌊 The leading agent orchestration platform for Claude. Deploy intelligent multi-agent swarms, coordinate autonomous workflows, and build conversational AI systems. Features enterprise-grade architecture, self-learning swarm intelligence, RAG integration, and native Claude Code / Codex Integration

### AI 总结
**简介**: Ruflo 是 Claude Code 的多智能体 AI 编排平台，支持协调 100+ 专业 AI 代理跨机器、团队和信任边界协作，实现自学习、自优化的智能体网络。

**核心功能**:
- **多智能体编排**: 支持代理自组织成群体（Swarm），自动路由任务并协调工作流
- **自学习记忆系统**: 代理能从每个任务中学习，跨会话保留记忆，并持续优化行为模式
- **联邦通信**: 代理可跨机器安全通信，不泄露数据，支持企业级安全边界
- **RAG 集成**: 支持检索增强生成，提升代理知识获取和响应能力
- **一键初始化**: 通过 `npx ruflo init` 快速为 Claude Code 添加智能体神经系统

**技术亮点**: TypeScript 构建，基于 Cognitum.One 代理架构，底层采用 Rust 引擎处理嵌入、记忆和插件系统；支持 Claude Code 和 Codex 原生插件集成，提供 CLI 和 MCP 协议接口。

---
