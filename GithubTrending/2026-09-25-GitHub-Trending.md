---
tags:
  - github-trending
  - daily
date: 2026-09-25
created: 2026-09-25T01:55:42.762Z
---

# 2026-09-25 GitHub Trending Top 10

## 1. [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch)
- **语言**: Python
- **Stars**: 56,600
- **简介**: Learn it. Build it. Ship it for others.

### AI 总结
**简介**: 一份从零开始系统学习 AI 工程的免费开源课程，涵盖 523 节课、20 个阶段，帮助学习者亲手构建并交付 AI 应用。

**核心功能**:
- **完整课程体系**：20 个阶段、523 节课、约 342 小时内容，覆盖从环境搭建、数学基础到 LLM 工程与 Agent 工程的完整路径
- **目标导向学习**：可按具体目标（如构建 LLM 应用、构建 Agent、使用 MCP 等）直接进入对应阶段，无需逐节浏览
- **可复用产出物**：每节课都产出一个可复用成果，如提示词、技能、Agent、MCP 服务器
- **多语言支持**：提供西班牙语、法语、中文、日语等 13 种语言的翻译落地页
- **双端访问**：同一套课程代码可在 GitHub 和官网同步学习

**技术亮点**: 使用 Python、TypeScript、Rust、Julia 多语言教学；采用 MIT 开源协议；课程内容与官网（aiengineeringfromscratch.com）共享同一份代码；翻译内容通过 `translations` 分支以机器翻译方式维护，英文为权威版本。

---
## 2. [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight)
- **语言**: Python
- **Stars**: 27,818
- **简介**: Hindsight: Agent Memory That Learns

### AI 总结
**简介**: Hindsight 是一个让 AI Agent 能够随时间学习和进化的记忆系统，超越传统对话历史回忆，专注于让 Agent 真正"学会"而非仅仅"记住"。

**核心功能**:
- **三种核心操作**：Retain（保留）、Recall（回忆）、Reflect（反思），构建完整的记忆生命周期
- **多种记忆类型**：支持 Observations（观察）、Mental Models & Knowledge Pages（心智模型与知识页面）、Memory Banks（记忆库）
- **LLM Wrapper 集成**：仅需 2 行代码即可为 Agent 添加记忆能力
- **多平台支持**：提供 Python 嵌入式模式（无需服务器）、MCP Server、以及丰富的框架集成
- **Docker 一键部署**：支持 25+ LLM 提供商（OpenAI、Anthropic、Gemini、Ollama 等）

**技术亮点**:
- 在 LongMemEval 基准测试上达到 SOTA 性能，结果由 Virginia Tech 和华盛顿邮报独立复现
- 克服了 RAG 和知识图谱等传统方案的缺陷
- 支持 Python 嵌入式运行，无需独立服务器
- 已在财富 500 强企业和 AI 初创公司中投入生产使用
- 提供持续更新的基准测试平台（含准确率、延迟和成本数据）

---
## 3. [dream-num/univer](https://github.com/dream-num/univer)
- **语言**: TypeScript
- **Stars**: 17,775
- **简介**: The Office Harness for AI Agents — Spreadsheets, Docs, Slides, Canvas, Relational Tables, and PDF in one runtime.

### AI 总结
**简介**: Univer 是一个开源的高性能 Office SDK，用于在自有产品中嵌入电子表格、文档、演示文稿等办公编辑能力。

**核心功能**:
- 支持电子表格、文档、演示文稿、Bases、看板及 PDF（即将推出）等多种办公形态
- 可嵌入 SaaS 产品、内部工具、BI 工作流或 AI 应用中
- 支持浏览器与 Node.js 服务端运行，架构统一
- 通过插件架构按需组合功能，支持自定义插件、命令、服务和 UI 组件
- 提供统一的 Facade API，便于扩展与集成
- 支持跨工具内容组合与嵌入，数据引用联动更新，人与 AI Agent 可协作编辑同一文件

**技术亮点**:
- 基于 TypeScript 开发
- 采用插件化架构，灵活可扩展
- 基于 Canvas 渲染，性能高
- 内置公式引擎
- 同一套 Facade API 同时兼容浏览器和 Node.js 环境
- 存储与计算共享统一运行时，支持跨工具数据联动

---
## 4. [google/ax](https://github.com/google/ax)
- **语言**: Go
- **Stars**: 10,495
- **简介**: Google's open agentic orchestration runtime

### AI 总结
**简介**: AX 是 Google 开源的高吞吐量声明式 Agent 编排运行时，用于在集群中运行大规模自主 Agent 工作负载。

**核心功能**:
- **Task**: 在隔离沙箱中运行不可信 Agent 代码，支持 CPU/内存限制，可通过 `ax ssh` 进入运行中的沙箱调试
- **Workspace**: 预配置 Git 仓库、MCP 服务器和技能包，让每个 Agent 启动即就绪
- **Model**: 声明式配置平台使用的 LLM 及其凭据（来自 Kubernetes Secret）
- **生命周期管理**: 支持 `ax suspend` / `ax resume` 暂停和恢复空闲 Agent，精确从断点继续
- **CLI 操作**: 类 kubectl 的命令行体验（`apply`、`get`、`watch`、`describe`、`ssh` 等）

**技术亮点**:
- 基于 Kubernetes 风格的声明式 API（`ax.io/v1alpha1`），使用 YAML 清单定义任务
- 构建在 Agent Substrate 之上实现沙箱化执行
- 控制平面通过 gRPC 通信，部署于 Kubernetes 集群（`ax-system` 命名空间），使用 Redis 作为支撑组件
- 使用 `ko` 构建和部署容器镜像
- 支持通过 atenet 路由器从集群内外访问运行中的任务
- 单集群设计目标为运行数十亿任务

---
## 5. [NVIDIA/Model-Optimizer](https://github.com/NVIDIA/Model-Optimizer)
- **语言**: Python
- **Stars**: 4,092
- **简介**: A unified library of SOTA model optimization techniques like quantization, distillation, pruning, neural architecture search, speculative decoding, etc. It compresses deep learning models for downstream deployment frameworks like TensorRT-LLM, TensorRT, vLLM, etc. to optimize inference speed.

### AI 总结
**简介**: NVIDIA 推出的统一模型优化库，集成量化、剪枝、蒸馏等 SOTA 技术，压缩深度学习模型以加速下游推理部署。

**核心功能**:
- 支持量化（含 NVFP4/FP8）、剪枝、神经架构搜索（NAS）、蒸馏、投机解码与稀疏化等优化技术
- 提供 Python API，支持 Hugging Face、PyTorch、ONNX 模型输入，可组合多种优化技术并导出量化检查点
- 与 Megatron-Bridge、Megatron-LM、Hugging Face Accelerate 集成，支持训练相关的推理优化
- 导出的检查点可无缝部署至 SGLang、TensorRT-LLM、TensorRT、vLLM 等推理框架

**技术亮点**:
- 统一的 Hugging Face 导出 API，同时支持 transformers 与 diffusers 模型
- 量化感知蒸馏（QAD）技术可在激进量化下恢复精度，兼顾模型体积与吞吐提升
- 提供 Minitron 剪枝+蒸馏、Puzzletron 异构剪枝与 NAS 等端到端优化方案
- 深度融入 NVIDIA AI 软件生态，面向大模型（如 Nemotron 系列）部署优化

---
## 6. [FxEmbed/FxEmbed](https://github.com/FxEmbed/FxEmbed)
- **语言**: TypeScript
- **Stars**: 5,372
- **简介**: Fix X/Twitter and Bluesky embeds! Use multiple images, videos, polls, translations and more on Discord, Telegram and others

### AI 总结
**简介**: FxEmbed 是一个用于修复 X/Twitter 和 Bluesky 链接嵌入效果的开源服务，让链接在 Discord、Telegram 等平台上能正确展示图片、视频、投票等内容。

**核心功能**:
- 修复嵌入内容：支持多图、视频、投票、引用推文、翻译等在 Discord、Telegram 等平台的展示
- 链接转换：在 `twitter.com` 前加 `fx`、`x.com` 前加 `fixup`、`bsky.app` 前加 `fx` 即可触发修复
- 多平台支持：覆盖 FxTwitter、FixupX、FxBluesky 三个服务
- 支持自托管，提供 Docker 部署方案
- 提供完整文档、API 参考和多语言翻译（Crowdin）

**技术亮点**:
- 基于 TypeScript 开发，使用 esbuild 构建
- 部署为 Cloudflare Worker，Docker 镜像通过 Wrangler 运行本地 Workers 运行时（基于 `node:24-bookworm-slim`，因 workerd 依赖 glibc）
- 通过 `Host` 请求头进行路由分发，支持多域名 realm 前缀
- 采用 MIT 许可证

---
## 7. [anthropics/financial-services](https://github.com/anthropics/financial-services)
- **语言**: Python
- **Stars**: 37,364
- **简介**: 

### AI 总结
**简介**: Anthropic 推出的金融服务行业 AI 代理工具集，为投资银行、股票研究、私募股权和财富管理等场景提供可部署的参考代理、技能和数据连接器。

**核心功能**:
- **Agents（命名代理）** ：覆盖端到端工作流，包括 Pitch Agent（可比公司分析、先例交易、LBO 到品牌推介材料）、Market Researcher（行业概览与竞争格局）、Earnings Reviewer（财报电话会与文件到模型更新和笔记草稿）、Model Builder（DCF、LBO、三表模型、可比公司分析，直接操作 Excel）、GL Reconciler（总账对账与根因追踪）、Month-End Closer（月末结账）、KYC Screener（客户准入文件解析与规则引擎）等
- **Vertical Plugins（垂直插件）** ：按金融子行业打包的技能、斜杠命令和数据连接器（如 `/comps`、`/dcf`、`/earnings`），可独立安装
- **双部署模式**：同一套系统提示和技能，既可作为 Claude Cowork 插件安装，也可通过 Claude Managed Agents API 部署在自有工作流引擎中
- **合作伙伴插件**：包含 LSEG、S&P Global 等合作方构建的插件
- **Microsoft 365 集成**：提供管理工具用于配置 Claude Microsoft 365 加载项

**技术亮点**: 基于 Python 构建；采用插件化架构，每个代理插件自包含并捆绑所需技能；支持通过 `/v1/agents` 部署的 Managed Agent 模板；提供部署脚本（deploy-managed-agent.sh）、校验工具（check.py、validate.py）和编排工具（orchestrate.py）；所有输出均需人工审核确认，不构成投资建议。

---
## 8. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 50,342
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: CLI-Anything 是 HKUDS 推出的开源项目，旨在让所有软件变为 Agent 原生（Agent-Native），通过自动生成 CLI 工具来弥合 AI Agent 与全球软件之间的鸿沟。

**核心功能**:
- **CLI-Hub 社区仓库**：通过 `pip install cli-anything-hub` 安装后使用 `cli-hub install <name>` 浏览、安装和管理社区构建的 CLI 工具，支持通过 PR 贡献自己的 CLI。
- **一键生成 CLI**：一条命令即可让任意软件对 Pi、OpenClaw、nanobot、Cursor、Claude Code 等 AI Agent 可用。
- **实时演示与预览**：提供 demo 展示 AI Agent 使用生成的 CLI 及预览、实时预览、轨迹循环来产出真实产物（如 CAD 构建、3D 场景、图表、游戏玩法、字幕等）。
- **社区共建**：支持贡献者注册和 CLI 心愿单请求，审核合并后可成为社区贡献者。

**技术亮点**:
- 基于 **Python ≥3.10** 开发，使用 **Click ≥8.0** 构建命令行界面。
- 采用 **pytest** 进行测试，拥有 **2,461 个通过测试**，覆盖单元测试与端到端测试。
- 输出支持 **JSON 与人类可读** 两种格式。
- 采用 **Apache 2.0** 开源协议，并有配套技术报告（arXiv:2606.03854）。

---
## 9. [mvt-project/mvt](https://github.com/mvt-project/mvt)
- **语言**: Python
- **Stars**: 14,732
- **简介**: MVT (Mobile Verification Toolkit) helps with conducting forensics of mobile devices in order to find signs of a potential compromise.

### AI 总结
**简介**: MVT 是由 Amnesty International 安全实验室开发的开源移动设备取证工具包，用于检测 Android 和 iOS 设备是否被间谍软件入侵。

**核心功能**:
- 对 Android 和 iOS 设备进行取证分析，查找潜在入侵痕迹（`mvt-ios` 和 `mvt-android` 命令）
- 支持导入公开的威胁指标（IOCs），扫描设备中与已知间谍软件活动相关的痕迹
- 提供插件机制，可通过插件包扩展额外的取证模块和命令
- 支持 Shell 自动补全（Bash、Zsh、Fish）

**技术亮点**:
- 基于 Python 开发，可通过 `pip3 install mvt` 或 `uv tool install mvt` 安装
- 起源于 Pegasus Project，附带完整的技术取证方法论
- 最新 v3 分支引入了破坏性变更，可能影响依赖其输出的脚本
- 面向技术人员和调查人员，需具备数字取证和命令行操作能力，非普通用户自助工具

---
## 10. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 291,240
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编程智能体的完整软件开发方法论，通过可组合的技能（skills）和自动触发机制，让 AI 编程助手遵循规范的开发流程。

**核心功能**:
- **需求澄清**：智能体在编码前先与用户沟通，明确真实意图并逐步梳理出规格说明
- **分块审阅**：将设计文档拆成小段展示，便于用户阅读和确认
- **实现计划生成**：产出清晰到"初级工程师也能执行"的详细计划，强调 TDD、YAGNI 和 DRY 原则
- **子智能体驱动开发**：用户确认后自动启动多智能体协作，逐个完成任务并自我审查，可自主连续工作数小时
- **自动触发**：技能自动激活，用户无需额外操作

**技术亮点**:
- 基于 Shell 实现，采用可组合的技能框架架构
- 支持广泛的编码智能体平台，包括 Claude Code、Codex、Cursor、Gemini CLI、GitHub Copilot CLI、Devin CLI、Factory Droid、OpenCode、Qwen Code 等十余种
- 提供官方插件市场安装方式，并支持企业级商业服务

---
