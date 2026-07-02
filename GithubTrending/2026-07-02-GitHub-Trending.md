---
tags:
  - github-trending
  - daily
date: 2026-07-02
created: 2026-07-02T01:55:44.192Z
---

# 2026-07-02 GitHub Trending Top 10

## 1. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 123,542
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个由精心打造的AI代理角色组成的集合，每个代理都是具有独特个性、专业流程和可交付成果的领域专家，旨在通过一键安装无缝集成到多种开发工具中。

**核心功能**:
- **即用型AI代理团队**: 提供涵盖前端开发、Reddit社区管理、安全检查等多个领域的专业AI代理，每个代理都有详细的身份、工作流程和交付标准。
- **一键安装到主流工具**: 支持通过原生桌面应用或脚本，将代理安装到Claude Code、Cursor、Codex、Gemini CLI、OpenCode、Qwen等10多种开发工具中。
- **灵活的选择性安装**: 允许用户按工具、按团队或按单个代理进行选择性安装，避免安装不需要的代理。
- **自动更新与集成**: 推荐的桌面应用支持自动更新，确保代理文件保持最新。

**技术亮点**:
- **Shell脚本驱动**: 核心安装和转换逻辑由Shell脚本 (`install.sh`, `convert.sh`) 实现，轻量且跨平台兼容。
- **多工具适配**: 通过脚本自动生成针对不同工具（如Claude Code、Cursor、Copilot等）的配置文件，实现广泛的集成能力。
- **模块化代理设计**: 每个代理以独立的Markdown文件存在，内容结构化，易于浏览、修改和扩展。

---
## 2. [usestrix/strix](https://github.com/usestrix/strix)
- **语言**: Python
- **Stars**: 29,788
- **简介**: Open-source AI penetration testing tool to find and fix your app’s vulnerabilities.

### AI 总结
**简介**: Strix 是一款开源的 AI 渗透测试工具，可自主发现并修复应用程序中的安全漏洞。

**核心功能**:
- **全栈渗透测试工具集**：内置侦察、漏洞利用和验证工具
- **多智能体编排**：支持多个 AI 渗透测试代理协同工作
- **真实漏洞验证**：生成可用的 PoC（概念验证），而非误报
- **开发者友好的 CLI**：提供可操作的结果与修复建议
- **自动修复与报告**：自动生成安全补丁和合规渗透测试报告
- **CI/CD 集成**：支持 GitHub Actions 等流水线，自动拦截不安全的代码

**技术亮点**: 基于 Python 开发，使用 Docker 沙箱运行，支持 OpenAI、Anthropic、Google 等多种 LLM 提供商，采用多智能体协作架构，能动态运行代码并生成可验证的 PoC。

---
## 3. [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading)
- **语言**: Python
- **Stars**: 16,581
- **简介**: "Vibe-Trading: Your Personal Trading Agent"

### AI 总结
**简介**: Vibe-Trading 是一个个人交易代理，通过一条命令即可赋予代理全面的交易能力。

**核心功能**:
- 支持通过 WebSocket、Telegram、Slack、Discord、微信、飞书等 16 种内置即时通讯渠道运行交易代理会话
- 提供 CLI 命令行、REST API 和 Web UI 三种方式来管理渠道状态、启动/停止会话及配对发送方
- 集成 Trading 212 只读连接器，支持账户、持仓、订单、历史和工具元数据查询
- 内置可选的 PreTradeAdvisoryInterface 安全咨询接口，记录交易建议但不绕过授权、紧急停止和审计追踪

**技术亮点**: 后端基于 FastAPI，前端基于 React 19，采用 Python 3.11+，支持 pip 安装，遵循 MIT 开源协议。架构上提供 SDK 支持的消息适配器扩展机制。

---
## 4. [hasaneyldrm/exercises-dataset](https://github.com/hasaneyldrm/exercises-dataset)
- **语言**: HTML
- **Stars**: 8,460
- **简介**: A comprehensive dataset of 433 fitness exercises. Each entry includes name, category, target muscle group, equipment, instructions, thumbnail image, and animation video.

### AI 总结
**简介**: 一个包含 1,324 项健身练习的结构化多语言数据集，附带开发者设置向导，用于快速搭建健身应用后端。

**核心功能**:
- **结构化数据集**: 提供 1,324 项练习的元数据，包括名称、类别、目标肌肉群、所需器材、分步指导等。
- **多语言支持**: 练习指导支持 6 种语言（英语、西班牙语、意大利语、土耳其语、俄语、中文）。
- **交互式浏览器**: 提供 `index.html`，可在浏览器中实时搜索、按类别/器材/目标肌肉筛选练习，并查看多语言详情。
- **开发者设置向导**: 提供 `setup.html`，分步指导如何将数据集集成到应用中（例如数据库设置、API 代码生成、LLM 提示词）。

**技术亮点**: 纯客户端 HTML 工具，无需服务器即可运行；数据格式为 JSON；不包含媒体文件，仅提供 `media_id` 引用。

---
## 5. [facebook/astryx](https://github.com/facebook/astryx)
- **语言**: TypeScript
- **Stars**: 2,691
- **简介**: An open source design system that's fully customizable and agent ready

### AI 总结
**简介**: Astryx 是 Meta 内部开发并开源的设计系统，已用于 13000+ 应用，提供 150+ 可访问组件、品牌主题、暗黑模式和 CLI，支持人类与 AI 助手以相同方式构建。

**核心功能**:
- 提供 150+ 可访问的 React 组件及预构建 CSS，零构建插件依赖
- 支持品牌级主题定制（含 7 个预置主题）和暗黑模式
- 内置 CLI 用于组件文档、模板、脚手架、主题和代码迁移
- 开放组件内部结构，支持 swizzle 机制将组件源码弹出到项目中
- 无样式锁定，可通过 className 覆盖（支持 Tailwind、CSS Modules 等）

**技术亮点**:
- 基于 React 和 StyleX 构建，但对使用者透明
- 主题通过 CSS 自定义属性覆盖实现，无需包装组件
- API、文档和 CLI 统一设计，确保人类与 AI 构建方式一致
- 支持 Next.js、Vite、CDN 等多种集成方式

---
## 6. [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)
- **语言**: TypeScript
- **Stars**: 9,570
- **简介**: Never stop coding. Free AI gateway: one endpoint, 231+ providers (50+ free), connect Claude Code, Codex, Cursor, Cline & Copilot to FREE Claude/GPT/Gemini. RTK+Caveman stacked compression saves 15-95% tokens, smart auto-fallback, MCP/A2A, multimodal APIs, Desktop/PWA.

### AI 总结
**简介**: OmniRoute 是一个免费的 AI 网关，通过单一端点连接 236 个 AI 提供商（其中 50+ 免费），支持 Claude Code、Codex、Cursor 等工具，并提供智能压缩以节省 tokens。

**核心功能**:
- **多提供商路由**：支持 236 个 AI 提供商（50+ 免费），包括 Claude、GPT、Gemini 等，自动故障转移。
- **智能压缩**：采用 RTK + Caveman 压缩技术，可节省 15-95% 的 tokens。
- **免费额度聚合**：每月聚合约 1.6B 免费 tokens（首月可达 2.1B），并支持无上限的永久免费提供商。
- **多平台兼容**：支持 Claude Code、Codex、Cursor、Cline、Copilot 等 CLI/编码代理工具。
- **多模态 API**：支持文本、图像等多模态输入输出。
- **MCP/A2A 协议**：支持 Model Context Protocol 和 Agent-to-Agent 通信。

**技术亮点**: 使用 TypeScript 开发，支持 17 种路由策略，提供桌面端（Electron）和 PWA 版本，支持 Docker 部署，开源且本地优先。

---
## 7. [allenai/olmocr](https://github.com/allenai/olmocr)
- **语言**: Python
- **Stars**: 18,293
- **简介**: Toolkit for linearizing PDFs for LLM datasets/training

### AI 总结
**简介**: olmocr 是一个用于将 PDF 和基于图像的文档转换为干净、可读的纯文本格式的工具包，专为 LLM 数据集和训练设计。

**核心功能**:
- 将 PDF、PNG、JPEG 文档转换为干净的 Markdown 文本
- 支持公式、表格、手写体和复杂格式
- 自动移除页眉和页脚，保持自然阅读顺序（支持多栏、插图和图文混排）
- 高效转换，每百万页成本低于 200 美元
- 提供完整的基准测试套件（olmOCR-Bench），覆盖 7,000+ 测试用例

**技术亮点**:
- 基于 7B 参数视觉语言模型（VLM），需要 GPU 运行
- 支持 vllm 推理管线，官方 Docker 镜像支持
- 持续迭代更新，最新模型（v0.4.0）通过合成数据和强化学习训练，在 olmOCR-Bench 上提升约 4 分
- 提供开源训练代码，方便用户自行训练模型

---
## 8. [logto-io/logto](https://github.com/logto-io/logto)
- **语言**: TypeScript
- **Stars**: 13,282
- **简介**: 🧑‍🚀 Authentication and authorization infrastructure for SaaS and AI apps, built on OIDC and OAuth 2.1 with multi-tenancy, SSO, and RBAC.

### AI 总结
**简介**: Logto 是一个面向 SaaS 和 AI 应用的开源身份认证与授权基础设施，基于 OIDC 和 OAuth 2.1 构建，支持多租户、企业 SSO 和 RBAC。

**核心功能**:
- 原生支持多租户、企业 SSO 和基于角色的访问控制（RBAC）
- 提供预构建的登录流程、可自定义的 UI 以及 30+ 框架的 SDK
- 全面支持 OIDC、OAuth 2.1 和 SAML 协议，无需处理协议细节
- 开箱即用支持 Model Context Protocol 和基于代理的 AI 架构

**技术亮点**: 基于 TypeScript 开发，采用现代身份认证协议栈，提供云服务和开源部署两种方式，支持 Docker Compose 和 Node.js 快速启动。

---
## 9. [togatoga/karukan](https://github.com/togatoga/karukan)
- **语言**: Rust
- **Stars**: 588
- **简介**: Japanese Input Method System for Linux, macOS, Neural Kana-Kanji Conversion Engine

### AI 总结
**简介**: Karukan 是一个基于 Rust 开发的日语输入法系统，采用神经网络进行假名到汉字的转换，支持 Linux 和 macOS 平台。

**核心功能**:
- 神经网络假名汉字转换：基于 GPT-2 模型，通过 llama.cpp 推理实现高质量转换
- 实时转换：输入同时显示转换结果，无需按空格键（可通过 `Ctrl+Shift+L` 切换）
- 上下文感知：根据周围文本优化转换结果
- 用户习惯学习：记住用户选择的转换结果，并支持预测输入
- 系统词典：基于 SudachiDict 构建
- 候选词重写（移植自 Mozc）：自动生成半角片假名、大小写、全半角、数字格式等变体
- 表情符号输入：支持假名读音（如 `ぴえん` → 🥺）和 Slack 风格 `:trigger` 查询

**技术亮点**: 采用 Rust 语言开发，模块化架构（fcitx5 前端、macOS 前端、共享 IME 引擎、核心引擎、CLI 工具）；使用 llama.cpp 运行 GPT-2 神经网络模型；集成 Mozc 的候选词重写逻辑；支持 MIT 和 Apache-2.0 双许可证。

---
## 10. [Mebus/cupp](https://github.com/Mebus/cupp)
- **语言**: Python
- **Stars**: 6,251
- **简介**: Common User Passwords Profiler (CUPP)

### AI 总结
**简介**: CUPP 是一个用 Python 编写的交互式密码分析工具，用于根据用户个人信息生成可能的弱密码字典，可用于合法渗透测试或取证调查。

**核心功能**:
- 交互式提问：通过问答方式收集用户信息（如生日、昵称、宠物名等），自动生成针对性密码字典
- 字典扩展：支持对现有字典文件进行扩展和增强
- 默认凭据解析：直接从 Alecto DB 解析默认用户名和密码
- 下载预置字典：支持从远程仓库下载大型密码列表

**技术亮点**: 基于 Python 3，提供命令行交互界面，通过配置文件（cupp.cfg）自定义规则，集成多种密码生成策略（如组合、变形、附加符号等）

---
