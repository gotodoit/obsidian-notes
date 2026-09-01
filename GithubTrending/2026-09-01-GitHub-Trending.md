---
tags:
  - github-trending
  - daily
date: 2026-09-01
created: 2026-09-01T01:55:43.944Z
---

# 2026-09-01 GitHub Trending Top 10

## 1. [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC)
- **语言**: TypeScript
- **Stars**: 27,232
- **简介**: Open Multi-Agent Interactive Classroom — Get an immersive, multi-agent learning experience in just one click

### AI 总结
**简介**: OpenMAIC 是一个开源的沉浸式多智能体互动课堂平台，用户只需一次点击即可获得完整的智能体驱动学习体验，并支持通过智能体工作台构建课程。

**核心功能**:
- **智能体工作台**：以聊天为先的课程构建工作区，可规划、构建和修订完整课程
- **一键课程生成**：输入提示词即可生成完整课程，并支持手动调整
- **持久化会话**：服务端支持的会话可跨重启存活，支持取消、恢复和随时引导
- **会话材料**：支持上传文档、音频、视频或从网络搜索获取材料，供智能体构建课程
- **20+ 内置技能**：涵盖幻灯片、测验、互动内容、PBL、图片、视频、语音及 `.pptx` 导入
- **中立设计**：可自由接入自有的模型、媒体、搜索提供商和存储后端

**技术亮点**: 基于 Next.js 16、React 19、TypeScript 5 构建，使用 LangGraph 1.1 编排多智能体流程，Tailwind CSS 4 负责界面样式；支持 OpenAI/Anthropic 等多种 LLM 提供商，集成 OpenClaw 和 Lemonade 本地 AI，可通过 Vercel 一键部署。

---
## 2. [tt-a1i/archify](https://github.com/tt-a1i/archify)
- **语言**: JavaScript
- **Stars**: 38,920
- **简介**: Agent skill for beautiful, verifiable architecture, workflow, sequence, data-flow, and lifecycle diagrams—self-contained HTML with motion and crisp export.

### AI 总结
**简介**: Archify 是一个 Node.js 渲染与验证系统，可将代码库或系统描述直接转化为精美的交互式架构图、流程图、时序图等，并输出为自包含的 HTML/SVG 文件。

**核心功能**:
- **五类图表与多种预设** — 支持架构、工作流、时序、数据流和生命周期图，提供四种预设风格、暗/亮主题及内置品牌标识
- **架构变更对比** — 在合并前对比两个已验证快照，精确展示新增、移除、修改、移动和重路由的变更（Before / Delta / After）
- **交互式探索** — 支持节点搜索、打开修订验证的源码、追踪上下游路由、对比角色，以及播放引导式故事
- **一键导出与分享** — 生成自包含 HTML，并可导出 PNG、SVG、WebM 及 1200×630 分享卡片

**技术亮点**: 基于类型化 JSON 中间表示（IR）和确定性编译校验，确保图表准确可靠；支持 Cursor、Claude Code、Codex CLI 和 OpenCode 等 Agent 工具，可通过 `npx skills add tt-a1i/archify -g` 快速安装，无需仓库即可使用。

---
## 3. [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- **语言**: Python
- **Stars**: 40,777
- **简介**: Turn any AI agent into an AI Scientist. The #1 Agent Skills library for science, used by 190,000+ scientists worldwide. 165 ready-to-use validated skills plus 100+ scientific databases covering biology, chemistry, medicine, and drug discovery. Compatible with Cursor, Claude Code, Codex, Pi, Antigravity, and the open Agent Skills standard.

### AI 总结
**简介**: 一个开源的 Agent Skills 库，提供 163 个经过验证的科研技能和 100+ 科学数据库，可将任何 AI 代理转变为全能科研助手，适用于生物、化学、医学和药物发现等领域，已服务全球 190,000+ 科学家。

**核心功能**:
- **163 个即用型科研技能**：覆盖癌症基因组学、千人基因组查询、调控序列预测、病原体变异监测、PK/PD 建模与剂量选择、药物-靶点结合、分子动力学、RNA 速率分析、微生物组基础模型、地理空间科学、时间序列预测等
- **100+ 科学数据库集成**：支持生物医学文献检索、监管文献获取、知识图谱搜索、科学 ML 资源发现（Hugging Science）
- **多代理兼容**：支持 Cursor、Claude Code、Codex、Google Antigravity 等任意兼容开放 Agent Skills 标准的 AI 代理
- **插件化部署**：可作为 Agent Plugins 包（plugin.json + skills/）整体加载
- **配套工具 K-Dense BYOK**：免费开源的本地 AI 协同科学家，支持 BYOK（自带 API 密钥）、40+ 模型选择，提供完整研究工作台

**技术亮点**:
- 基于开放 [Agent Skills](https://agentskills.io/) 标准构建，同时兼容 [Agent Plugins](https://agent-plugins.org/) 标准
- 采用 Python 开发，包含自动化安全扫描和技能测试 CI/CD 流程
- 支持复杂多步骤科研工作流的执行，覆盖从文献检索到建模分析的完整科研链路

---
## 4. [k1tbyte/Wand-Enhancer](https://github.com/k1tbyte/Wand-Enhancer)
- **语言**: C#
- **Stars**: 23,401
- **简介**: Advanced UX and interoperability extension for Wand (WeMod) app

### AI 总结
**简介**: WandEnhancer 是一个开源工具，用于扩展 Wand（WeMod）应用的本地客户端配置并改善其用户体验。

**核心功能**:
- 本地环境配置管理
- 自动兼容新版本客户端的调整
- 高级布局与主题自定义（仅客户端侧）
- AI 功能集成
- 远程网页面板（可通过手机控制应用功能）

**技术亮点**:
- 基于 .NET 的补丁程序，通过修改 Wand 本地安装文件实现功能增强
- 使用 `version.dll` 代理文件，在 Wand 自身进程内修改 Electron 的 ASAR 完整性 fuse 字节，不注入外部进程
- 支持自定义 JavaScript 脚本注入到 Wand 渲染进程（需启用远程网页面板补丁）
- 内置远程网页面板，通过 LAN HTTP/WebSocket 服务器（TCP 3223 端口）提供手机控制能力
- 通过 GitHub Actions 构建，不发布官方预编译二进制文件，用户需从自己的 fork 构建

---
## 5. [majd/ipatool](https://github.com/majd/ipatool)
- **语言**: Go
- **Stars**: 10,562
- **简介**: Command-line tool that allows searching and downloading app packages (known as ipa files) for iOS, iPadOS, tvOS, and visionOS from the App Store.

### AI 总结
**简介**: ipatool 是一个命令行工具，用于在 App Store 中搜索并下载 iOS、iPadOS、tvOS 和 visionOS 应用的 IPA 安装包文件。

**核心功能**:
- **账户认证**: 支持登录、查看账户信息及撤销 App Store 凭据，并可通过 `--non-interactive` 实现非交互式认证
- **应用搜索**: 按关键词搜索多平台应用，支持指定平台（iphone/ipad/appletv/visionos）和自定义结果数量
- **应用获取**: 通过 bundle identifier 获取应用的许可证，并可列出账户已购买的应用（支持分页）
- **版本管理**: 查看指定应用的所有可用历史版本，支持按应用 ID 或 bundle identifier 查询
- **IPA 下载**: 下载应用安装包，可指定具体版本或默认获取最新版

**技术亮点**: 基于 Go 语言开发，跨平台支持（Windows/Linux/macOS），提供文本和 JSON 两种输出格式，支持通过 Homebrew 安装，采用 MIT 开源协议。

---
## 6. [jingyaogong/minimind](https://github.com/jingyaogong/minimind)
- **语言**: Python
- **Stars**: 56,182
- **简介**: 🧠 Train a 64M-parameter LLM from scratch in just 2h!

### AI 总结
**简介**: MiniMind 是一个从零开始、用极低成本（约3元GPU费用、2小时训练时间）训练 64M 超小语言模型的开源项目，旨在降低 LLM 学习门槛，让个人 GPU 也能完整复现大模型训练全流程。

**核心功能**:
- 提供完整的 MiniMind-LLM 结构代码（Dense + MoE），主线对齐 Qwen3/Qwen3-MoE 生态
- 覆盖 Pretrain、SFT、LoRA、RLHF-DPO、RLAIF（PPO/GRPO/CISPO）、Tool Use、Agentic RL、模型蒸馏等全流程训练代码
- 开源全阶段高质量数据集（含收集、蒸馏、清洗、去重）
- 提供 Tokenizer 训练、Chat WebUI、OpenAI API 兼容服务端、C-Eval 等第三方评测支持
- 支持单机单卡/多卡（DDP、DeepSpeed）训练，兼容 transformers、trl、peft、llama.cpp、vllm、ollama 等主流框架
- 拓展视觉模态模型 MiniMind-V、多模态 Omni 模型 MiniMind-O、扩散语言模型（dLM）及线性注意力模型

**技术亮点**: 核心算法全部基于 PyTorch 原生实现，不依赖第三方高层抽象接口；模型体积仅为 GPT-3 的 1/2700；支持 YaRN 长文本外推、wandb/swanlab 可视化、RoPE 等先进技术；Apache 2.0 协议开源，免费商用。

---
## 7. [Osmantic/ODS](https://github.com/Osmantic/ODS)
- **语言**: Python
- **Stars**: 5,522
- **简介**: Turn your PC, Mac, or Linux box into an AI server. LLM inference, chat UI, voice, agents, workflows, RAG, and image generation.

### AI 总结
**简介**: ODS（Osmantic Deployment System）是一个将 PC、Mac 或 Linux 设备转化为私有 AI 服务器的开源部署系统，无需云服务或订阅即可在本地运行完整 AI 功能栈。

**核心功能**:
- **本地模型推理** — 在自有硬件上运行开源大语言模型
- **ChatGPT 风格 Web UI** — 通过浏览器与模型对话
- **控制面板** — 统一管理模型、服务、GPU 状态、扩展和安装配置
- **语音、智能体与工作流** — 支持构建可监听、对话、调用工具并自动完成任务的自动化流程
- **RAG 与本地搜索** — 连接本地文档、私有搜索和检索增强生成工作流
- **图像生成** — 本地运行图像生成工具，无需将提示词发送至托管 API
- **隐私与运维** — 服务认证、密钥管理、可观测性和诊断集中在一个本地栈

**技术亮点**: 基于 Docker 容器化编排，提供一键安装脚本（支持 Linux/macOS 的 curl 命令和 Windows PowerShell 安装），自动适配硬件选择模型；采用零前置依赖的引导方式，并配备发布级验证体系（涵盖全新安装、产品流程、模型能力、生命周期恢复等测试）；代码仓库区分公共文档与产品运行时（`ods/` 目录），支持稳定版本（v2.6.0）和活跃开发分支（main）双通道发布，并提供可审计的安装信任机制与分叉兼容性。

---
## 8. [checkstyle/checkstyle](https://github.com/checkstyle/checkstyle)
- **语言**: Java
- **Stars**: 9,422
- **简介**: Checkstyle is a development tool to help programmers write Java code that adheres to a coding standard. By default it supports the Google Java Style Guide and Sun Code Conventions, but is highly configurable. It can be invoked with an ANT task and a command line program.

### AI 总结
**简介**: Checkstyle 是一个帮助 Java 程序员编写符合编码标准的开发工具，默认支持 Google Java Style Guide 和 Sun Code Conventions，且高度可配置。

**核心功能**:
- **代码规范检查**: 自动检测 Java 代码中违反编码标准的问题，如 switch 语句的 fall-through 等
- **高度可配置**: 通过 XML 配置文件自定义检查规则，支持 200+ 种检查项
- **多方式调用**: 支持命令行程序、ANT 任务，并可集成到 Maven 等构建工具
- **自动化集成**: 提供丰富的 CI/CD 集成支持，包括 AppVeyor、CircleCI、Azure Pipelines 等
- **文档完善**: 提供 HTML 格式的完整检查项文档和 API Javadoc

**技术亮点**:
- 基于 Java 开发，使用 ANTLR 进行代码解析，Apache Commons、Google Guava 等成熟库
- 支持与主流构建工具和 CI 系统无缝集成
- 采用 LGPL v2.1 开源许可证，拥有活跃的社区贡献和讨论平台

---
## 9. [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill)
- **语言**: PowerShell
- **Stars**: 33,189
- **简介**: Reverse Engineering / Authorized Penetration Testing / Security Research Skill Router Pack AI-powered routing + On-demand toolchain bootstrapping + Self-evolving knowledge base Supports Claude Code, Kiro, Cursor, Cline, and other AI coding clients 逆向/渗透/安全技能路由包 - AI 自动路由 + 按需自举工具链 + 自动进化经验库 | 支持 Claude Code / Kiro / Cursor / Cline 等代码 AI 客户端

### AI 总结
**简介**: reverse-skill 是一个面向 AI 编程助手的网络安全技能路由包，能在逆向工程、渗透测试和安全研究场景下自动为 AI 代理选择正确的方法论和工具链。

**核心功能**:
- **智能路由**: 包含 43 条路由规则(R0–R44)，当 AI 代理遇到 APK、二进制、前端 JS 加密、CTF 挑战或渗透测试目标时，自动匹配正确的处理流程
- **按需工具链自举**: 自动检测并引导安装所需工具(如 jadx、apktool、Frida、IDA、BurpSuite)，避免 AI 猜测命令
- **场景化工作流**: 从任务输入 → 规则匹配 → 场景技能 → 工具/MCP/脚本 → 时间线记录 → 证据链 → 报告输出的完整可重复流程
- **自进化经验库**: 复用过往经验，避免重复犯错，持续积累领域知识
- **跨平台兼容**: 支持 Windows + Ubuntu，且与 Claude Code、Kiro、Cursor、Cline 等多种 AI 客户端无关

**技术亮点**:
- 单一结构化配置驱动路由核心，通过跨平台 CI 验证(173 个回归测试用例)
- 模块化设计：核心路由逻辑与客户端适配器分离，44 个核心技能模块独立追踪
- 支持 MCP 服务器集成，提供 ops 契约和 AI 引导文档(README_AI.md)

---
## 10. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 245,269
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个面向 AI 编程代理（如 Claude Code、Codex 等）的性能优化系统，提供技能、本能、记忆、安全与研究优先的开发支持。

**核心功能**:
- 代理编排优化：为 Claude Code、Codex、Opencode、Cursor 等 AI 编程工具提供统一的代理性能调优能力
- 技能与本能系统：内置可扩展的技能库和自适应行为机制，提升代理在复杂任务中的执行效率
- 记忆管理：支持跨会话的上下文记忆持久化，减少重复学习成本
- 安全防护（AgentShield）：提供代理安全层，防止恶意指令注入和未授权操作
- 一键安装与升级：通过 `npx ecc-universal setup` 快速完成安装、更新或迁移，支持 Node.js 18+ 和 Claude Code 2.1+
- 多语言文档支持：覆盖 12 种语言（含中文、日文、韩文等），降低全球开发者使用门槛

**技术亮点**: 基于 JavaScript/TypeScript 构建，提供 npm 包（`ecc-universal`、`ecc-agentshield`）和 GitHub App 多渠道分发；采用插件化架构（`ecc@ecc` 插件作用域）实现与主流 AI 编程工具的深度集成；支持 Shell、Python、Go、Java、Perl 等多种语言环境；遵循 MIT 开源协议，社区活跃度高（含 Discord 支持）。

---
