---
tags:
  - github-trending
  - daily
date: 2026-05-09
created: 2026-05-09T01:55:45.826Z
---

# 2026-05-09 GitHub Trending Top 10

## 1. [anthropics/financial-services](https://github.com/anthropics/financial-services)
- **语言**: Python
- **Stars**: 15,296
- **简介**: 

### AI 总结
**简介**: 这是一个专为金融服务行业设计的Claude智能体集合，涵盖投资银行、股权研究、私募股权和财富管理等场景，支持作为Cowork插件或通过Managed Agents API部署。

**核心功能**:
- **覆盖与咨询**: Pitch Agent（端到端生成竞品分析、先例交易、LBO到品牌推介材料）、Meeting Prep Agent（生成客户会议简报包）
- **研究与建模**: Market Researcher（行业概览与竞争分析）、Earnings Reviewer（财报电话+文件→模型更新→笔记草稿）、Model Builder（在Excel中运行DCF、LBO、三表模型）
- **基金管理与财务运营**: Valuation Reviewer（处理GP数据包并生成LP报告）、GL Reconciler（发现账目差异并追溯根因）、Month-End Closer（处理应计、滚动和差异分析）、Statement Auditor（审计LP报表）
- **运营与入职**: KYC Screener（解析入职文档并运行规则引擎，标记缺失项）

**技术亮点**: 采用“同一来源两种方式”架构——系统提示和技能集完全一致，既可作为Claude Cowork插件直接安装，也可通过Claude Managed Agents API部署到自有工作流引擎；每个Agent插件自包含所需技能，支持独立安装和微调。

---
## 2. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: Shell
- **Stars**: 35,515
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 一套为 AI 编码代理设计的、包含生产级工程技能的工作流与最佳实践集合。

**核心功能**:
- 提供 7 个映射到开发生命周期的斜杠命令（/spec, /plan, /build, /test, /review, /code-simplify, /ship），自动激活相应技能。
- 包含 21 个结构化的技能文件（SKILL.md），涵盖从构思、规划、构建到测试、审查、发布的完整流程。
- 支持多种主流 AI 编码工具（如 Claude Code, Cursor, Gemini CLI, Windsurf, GitHub Copilot 等），提供相应的集成指南。

**技术亮点**: 采用纯 Markdown 文件定义技能，具有极高的可移植性和兼容性，任何接受系统提示或指令文件的 AI 代理均可使用。

---
## 3. [Hmbown/DeepSeek-TUI](https://github.com/Hmbown/DeepSeek-TUI)
- **语言**: Rust
- **Stars**: 21,886
- **简介**: Coding agent for DeepSeek models that runs in your terminal

### AI 总结
**简介**: DeepSeek TUI 是一款基于终端的编码助手，专为 DeepSeek V4 模型设计，支持流式推理、本地文件编辑、工具调用和自动模式。

**核心功能**:
- **自动模型选择**: 通过 `--model auto` 或 `/model auto` 自动为每轮对话选择模型和思考级别
- **流式推理**: 实时显示 DeepSeek 模型的推理过程
- **完整工具集**: 支持文件操作、Shell 命令、Git 管理、网页搜索/浏览、补丁应用、子代理和 MCP 服务器
- **三种模式**: 计划模式（只读探索）、代理模式（交互式审批）、YOLO 模式（自动审批）
- **会话保存/恢复**: 支持断点续传和长时间会话管理
- **工作区回滚**: 通过侧边 Git 快照实现每轮操作的前后对比和恢复
- **耐久任务队列**: 后台任务可在重启后继续执行
- **HTTP/SSE API**: 支持无头代理工作流
- **MCP 协议**: 集成 Model Context Protocol 服务器扩展工具能力
- **LSP 诊断**: 编辑后自动通过 rust-analyzer、pyright 等工具显示内联错误/警告
- **多语言 UI**: 支持英文、日文、简体中文、巴西葡萄牙文自动检测
- **实时成本追踪**: 每轮和会话级别的 token 使用量和费用估算

**技术亮点**: 基于 Rust 构建，使用 ratatui 终端界面框架和异步引擎，支持 OpenAI 兼容流式客户端；工具调用通过类型化注册表（shell、文件操作、Git、Web、子代理、MCP、RLM）路由；内置 LSP 子系统在编辑后自动将诊断信息注入模型上下文。

---
## 4. [z-lab/dflash](https://github.com/z-lab/dflash)
- **语言**: Python
- **Stars**: 3,860
- **简介**: DFlash: Block Diffusion for Flash Speculative Decoding

### AI 总结
**简介**: DFlash 是一个轻量级块扩散模型，专为推测解码（Speculative Decoding）设计，旨在实现高效、高质量的并行草稿生成。

**核心功能**:
- 支持多种主流大语言模型（如 Gemma、Qwen、Llama、DeepSeek 等）的推测解码加速。
- 提供多种后端集成（Transformers、SGLang、vLLM、MLX），便于用户在不同环境下部署。
- 通过 Docker 和 pip 简化安装流程，并提供针对特定模型（如 Gemma4）的专用构建。

**技术亮点**:
- 基于块扩散（Block Diffusion）架构，实现并行草稿生成，提升解码速度。
- 支持滑动窗口注意力（SWA）等高级技术，适配不同模型架构。
- 训练方法开源，允许用户自定义训练 DFlash 草稿模型以加速任意 LLM。

---
## 5. [decolua/9router](https://github.com/decolua/9router)
- **语言**: JavaScript
- **Stars**: 5,634
- **简介**: Unlimited FREE AI coding. Connect Claude Code, Codex, Cursor, Cline, Copilot, Antigravity to FREE Claude/GPT/Gemini via 40+ providers. Auto-fallback, RTK -40% tokens, never hit limits.

### AI 总结
**简介**: 9Router 是一个免费且无限的 AI 路由与令牌节省工具，能连接 Claude Code、Cursor、Copilot 等 40 多个 AI 提供商和 100 多个模型，通过智能降级和自动压缩技术节省 20-40% 的令牌消耗。

**核心功能**:
- **RTK 令牌节省器**：自动压缩工具输出内容，每次请求节省 20-40% 的令牌
- **自动降级策略**：订阅 → 廉价 → 免费，实现零停机，最大化利用每个订阅配额
- **多账户轮询**：支持按提供商进行多账户轮询，分散请求负载
- **通用集成**：兼容所有主流 CLI 工具（Claude Code、Codex、Cursor、Cline 等）
- **格式翻译**：自动在 OpenAI 和 Claude 格式之间转换
- **免费提供商连接**：内置 Kiro AI、OpenCode Free 等无需注册的免费提供商

**技术亮点**: 基于 JavaScript 开发的智能路由中间件，提供 OpenAI 兼容的 API 端点（`http://localhost:20128/v1`），通过三层降级策略（Subscription → Cheap → Free）和 RTK 令牌压缩算法实现永不中断且成本最低的 AI 编码体验。

---
## 6. [CloakHQ/CloakBrowser](https://github.com/CloakHQ/CloakBrowser)
- **语言**: Python
- **Stars**: 3,080
- **简介**: Stealth Chromium that passes every bot detection test. Drop-in Playwright replacement with source-level fingerprint patches. 30/30 tests passed.

### AI 总结
**简介**: CloakBrowser 是一个基于 Chromium 的隐形浏览器，通过 C++ 源码级指纹修改，能够通过所有机器人检测测试，可作为 Playwright/Puppeteer 的即插即用替代品。

**核心功能**:
- **隐形浏览**：49 个 C++ 源码级补丁，修改 Canvas、WebGL、音频、字体、GPU、屏幕、WebRTC、网络时序、自动化信号和 CDP 输入行为，通过 30+ 检测网站测试
- **人性化模拟**：`humanize=True` 参数一键启用类人鼠标轨迹、键盘时序和滚动模式，通过行为检测
- **高 reCAPTCHA v3 分数**：获得 0.9 分（人类水平，服务器验证）
- **自动更新**：后台自动检查更新，始终使用最新隐形构建
- **零配置安装**：`pip install cloakbrowser` 或 `npm install cloakbrowser`，首次运行自动下载二进制文件（约 200MB）
- **浏览器配置文件管理器**：自托管替代 Multilogin、GoLogin、AdsPower，支持创建独特指纹、代理和持久会话的浏览器配置文件，通过 noVNC 在浏览器中启动和交互

**技术亮点**: Python/JavaScript 双语言支持；Playwright/Puppeteer API 兼容，仅需修改导入语句即可迁移；Docker 快速试用命令 `docker run --rm cloakhq/cloakbrowser cloaktest`；可选 GeoIP 自动检测代理 IP 时区/区域设置。

---
## 7. [awslabs/aidlc-workflows](https://github.com/awslabs/aidlc-workflows)
- **语言**: Python
- **Stars**: 1,773
- **简介**: AI-Driven Life Cycle (AI-DLC) adaptive workflow steering rules for AI coding agents

### AI 总结
**简介**: AI-DLC (AI-Driven Development Life Cycle) 是一个由 AWS 实验室开发的自适应软件开发生命周期工作流，通过规则驱动 AI 编码代理，提升开发效率与质量。

**核心功能**:
- **自适应工作流**: 提供三阶段自适应工作流，动态调整开发流程以适应项目需求。
- **多平台支持**: 支持 Kiro、Amazon Q Developer、Cursor、Cline、Claude Code、GitHub Copilot 等多种 AI 编码代理和 IDE。
- **规则驱动**: 包含核心工作流规则和详细规则，通过规则文件引导 AI 代理行为。
- **质量与成本控制**: 强调对 AI 输出进行审查，并关注模型使用成本。

**技术亮点**:
- 基于 Python 开发，提供跨平台（macOS/Linux/Windows）的安装脚本（Bash/PowerShell/CMD）。
- 采用模块化规则结构（`aws-aidlc-rules` 核心规则 + `aws-aidlc-rule-details` 详细规则），便于扩展和维护。

---
## 8. [HKUDS/AI-Trader](https://github.com/HKUDS/AI-Trader)
- **语言**: Python
- **Stars**: 14,666
- **简介**: "AI-Trader: 100% Fully-Automated Agent-Native Trading"

### AI 总结
**简介**: AI-Trader 是一个 100% 全自动的、面向 AI Agent 的交易平台，允许 AI Agent 像人类一样进行交易、协作和策略分享。

**核心功能**:
- **🤖 即时 Agent 集成**: 通过发送一条消息即可让任何 AI Agent 快速接入平台。
- **💬 集体智能交易**: 支持 Agent 之间协作、辩论，自动发现最佳交易想法。
- **📊 一键跟单**: 实时跟随顶级交易者的策略和持仓。
- **🌐 跨平台信号同步**: 无缝连接主流券商（如 Binance、Coinbase），同步交易信号。
- **🎯 三种信号类型**: 提供讨论策略、操作跟单、协作讨论三种模式。
- **⭐ 奖励系统**: 发布信号和获得关注者均可赚取积分。

**技术亮点**: 采用 FastAPI 后端 + React 前端架构，支持生产级稳定性（后台 Worker 与 Web 服务分离），兼容 Polymarket 等模拟交易环境。

---
## 9. [LearningCircuit/local-deep-research](https://github.com/LearningCircuit/local-deep-research)
- **语言**: Python
- **Stars**: 6,753
- **简介**: ~95% on SimpleQA (e.g. Qwen3.6-27B on a 3090). Supports all local and cloud LLMs (llama.cpp, Ollama, Google, ...). 10+ search engines - arXiv, PubMed, your private documents. Everything Local & Encrypted.

### AI 总结
**简介**: Local Deep Research 是一款由用户控制的 AI 研究助手，支持本地运行以保护隐私，可集成多种 LLM 和搜索引擎，构建可搜索的知识库。

**核心功能**:
- 支持本地和云端 LLM（如 llama.cpp、Ollama、Google 等），在 SimpleQA 基准测试中达到约 95% 的准确率
- 集成 10 多种搜索引擎（包括 arXiv、PubMed 等）及私有文档搜索
- 所有数据本地存储并加密（使用 SQLCipher），用户完全掌控数据
- 提供 Docker 快速部署和 pip 安装选项，支持 Windows、macOS 和 Linux

**技术亮点**:
- 基于 Python 开发，支持 Docker 容器化部署（含 GPU 加速选项）
- 使用 SQLCipher 加密数据库，通过 OpenSSF Scorecard、CodeQL、Semgrep 等安全扫描工具验证
- 支持多种部署方式：Docker Run、Docker Compose 或 pip 安装

---
## 10. [lobehub/lobehub](https://github.com/lobehub/lobehub)
- **语言**: TypeScript
- **Stars**: 76,516
- **简介**: The ultimate space for work and life — to find, build, and collaborate with agent teammates that grow with you. We are taking agent harness to the next level — enabling multi-agent collaboration, effortless agent team design, and introducing agents as the unit of work interaction.

### AI 总结
**简介**: LobeHub 是一个致力于打造人类与 AI Agent 协同进化网络的工作与生活空间，旨在通过多智能体协作、团队设计和工作单元化，重新定义人机交互方式。

**核心功能**:
- **Agent 工作单元化**: 将 AI Agent 作为基本的工作交互单位，支持创建、发现和协作。
- **多智能体协作**: 支持多个 Agent 协同工作，并允许用户轻松设计 Agent 团队。
- **MCP 插件与市场**: 提供 MCP 插件的一键安装功能及市场，扩展 Agent 能力。
- **智能联网搜索**: 集成智能互联网搜索功能。
- **思维链与分支对话**: 支持思维链展示和对话分支，便于复杂推理和多路径探索。
- **Artifacts 支持**: 支持生成和展示代码、文档等制品。
- **文件上传与知识库**: 支持文件上传和构建知识库。
- **多模型服务商支持**: 集成多种模型服务，并支持本地大语言模型（LLM）。
- **多模态能力**: 包括模型视觉识别、TTS/STT 语音对话、文本到图像生成。
- **插件系统**: 支持基于函数调用的插件系统。
- **Agent 市场**: 提供类似 GPTs 的 Agent 市场。
- **自托管与多用户管理**: 支持通过 Docker 或 Vercel 等方式自托管，并支持多用户管理。
- **跨平台体验**: 支持渐进式 Web 应用（PWA）和移动设备适配。
- **自定义主题**: 提供可自定义的主题。

**技术亮点**: 基于 TypeScript 构建，采用现代设计组件与工具，支持 Docker 部署、Vercel 部署，并集成了 MCP（Model Context Protocol）协议。

---
