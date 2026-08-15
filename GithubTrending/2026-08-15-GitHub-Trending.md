---
tags:
  - github-trending
  - daily
date: 2026-08-15
created: 2026-08-15T01:55:43.638Z
---

# 2026-08-15 GitHub Trending Top 10

## 1. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 17,307
- **简介**: 29 editorial diagram types for Claude Code. Self-contained HTML + SVG. No shadows, no Mermaid-slop.

### AI 总结
**简介**: 一个为 Claude Code 等 AI 编程助手设计的图表生成技能库，提供 29 种编辑级质量的 HTML+SVG 图表模板，让 AI 生成的图表不再千篇一律。

**核心功能**:
- 内置 29 种图表类型：涵盖架构图、流程图、时序图、状态机、ER 图、时间线、泳道图、象限图、树形图、组织架构图、维恩图、金字塔、雷达图、循环飞轮图等
- 三种静态变体：每类图表均提供极简浅色、极简深色、全编辑风格三种样式
- 品牌适配能力：通过读取网站自动匹配品牌视觉风格，60 秒内完成定制
- 格式转换功能：可将 draw.io 或 Mermaid 源码重新绘制为指定格式、尺寸和细节级别
- 语义化模式描述：将行为与布局分离，队列、策略追踪等场景可复用现有图表类型
- 零依赖输出：纯 HTML+SVG，无构建步骤、无 JavaScript、无外部图片依赖，可直接浏览器打开

**技术亮点**: 采用语义化模式描述与布局分离的架构设计，静态 HTML 为默认输出，可选无障碍动效支持；设计理念强调"少即是多"——每个节点都有存在价值，强调色仅用于引导读者关注 1-2 个重点，目标视觉密度控制在 4/10。

---
## 2. [cactus-compute/needle](https://github.com/cactus-compute/needle)
- **语言**: Python
- **Stars**: 5,628
- **简介**: 14MB foundation model for tiny devices; phones, wearables, smart home, and robots.

### AI 总结
**简介**: Needle 2 是一个专为微型设备（手机、可穿戴设备、智能家居、机器人）设计的开源 45M 参数基础模型，整个模型打包为单个 14MB 二进制文件，运行完整会话仅需约 28MB 内存。

**核心功能**:
- **工具调用**: 通过装饰器声明工具，模型自动选择调用并填充参数，返回结构化 JSON 结果
- **结构化提取**: 支持 Pydantic 模型声明，从文本中提取结构化数据并返回类型化对象
- **置信度门控**: 每个响应携带校准的置信度分数，可设定阈值决定执行或升级处理
- **工具检索**: 支持大型工具目录，内置检索头每轮仅呈现前五个最相关工具
- **有界内存**: 256 token 滑动窗口配合工具 KV 固定，无论对话多长总内存保持在 28MB 附近
- **模型微调**: 支持 LoRA 微调，导出时合并适配器，可从浏览器 UI 直接操作

**技术亮点**: 基于 Simple Attention Network 架构（Hadamard MLP 替代 FFN、GQA 注意力、engram 键值记忆、多通道超连接），使用 Cactus Quants 压缩至 CQ2-bit 精度，采用字节级语法约束（从 schema 编译）确保输出格式，支持完全离线推理（无网络请求），在 5x-70x 更小的体积下与 FunctionGemma 270M、LFM2.5 230M 等模型性能相当。

---
## 3. [megadose/holehe](https://github.com/megadose/holehe)
- **语言**: Python
- **Stars**: 12,860
- **简介**: holehe allows you to check if the mail is used on different sites like twitter, instagram and will retrieve information on sites with the forgotten password function.

### AI 总结
**简介**: holehe 是一个 OSINT 工具，用于通过邮箱地址检测其在 Twitter、Instagram 等 120 多个平台上的账号注册情况，并利用"忘记密码"功能获取关联信息。

**核心功能**:
- 批量检测邮箱在 120+ 网站（如 Twitter、Instagram、Snapchat、Adobe 等）的账号注册情况
- 通过"忘记密码"功能被动获取部分脱敏的恢复邮箱、手机号等关联信息
- 支持 CLI 命令行和 Python API 两种使用方式，可嵌入现有应用
- 检测过程不会向目标邮箱发送任何通知，保持隐蔽性
- 模块化设计，每个网站对应独立检测模块，输出统一 JSON 格式数据（包含 exists、rateLimit、emailrecovery 等字段）

**技术亮点**:
- 基于 Python 3 开发，使用 `trio` 异步框架和 `httpx` HTTP 客户端实现高效并发请求
- 提供 PyPI、GitHub 源码和 Docker 三种安装方式，支持 Docker 容器化部署
- 内置频率限制检测（rateLimit），可识别被目标网站限流的情况
- 支持 Maltego 转换插件（holehe-maltego），可集成到图形化情报分析工具
- 开源项目，采用 GPL v3.0 许可证，仅供教育用途

---
## 4. [macro-inc/macro](https://github.com/macro-inc/macro)
- **语言**: Rust
- **Stars**: 3,041
- **简介**: Macro is a unified workspace for teams: email, chat, docs, tasks, agents, calls, and CRM — @-linked together with shared AI memory.

### AI 总结
**简介**: Macro 是一个面向团队的一体化工作空间，将邮件、聊天、文档、任务、智能代理、通话和 CRM 整合为单一系统，并通过共享 AI 记忆实现所有内容的 @ 链接与搜索。

**核心功能**:
- **统一收件箱**: 支持多 Gmail 账户聚合、键盘快捷键优先的邮件体验，并与消息、@提及和任务合并为单一列表
- **消息与频道**: 专为深度技术讨论设计的频道和私信功能
- **任务管理**: Linear 风格的任务系统，与频道、邮件和智能代理深度集成
- **实时协作文档**: 基于 CRDT 的 Markdown 原生文档，支持 @提及和实时协同编辑
- **Canvas 画布**: 2D 白板，可嵌入任务、文件和邮件的 @链接
- **智能代理 (Agents)**: 拥有团队级统一记忆，可代表用户执行操作
- **通话记录**: 自动录音、转写并记录到团队记忆供代理使用
- **文件存储**: 从邮件和频道自动导入，支持全文搜索
- **CRM 客户管理**: 客户/联系人对象、自定义属性、邮件同步与数据丰富
- **GitHub 集成**: Pull Request 关联任务、嵌入频道并可供代理访问

**技术亮点**: 使用 Rust 和 SolidJS 构建，强调速度与可靠性；所有数据块共享同一后端，跨文档、任务、邮件等实体间的引用以**双向图**结构原生存储；模块化"积木式"架构设计，各功能表面可独立扩展但深度互联。

---
## 5. [smicallef/spiderfoot](https://github.com/smicallef/spiderfoot)
- **语言**: Python
- **Stars**: 20,953
- **简介**: SpiderFoot automates OSINT for threat intelligence and mapping your attack surface.

### AI 总结
**简介**: SpiderFoot 是一款开源的自动化 OSINT（开源情报）工具，用于威胁情报收集和攻击面测绘，支持通过 Web 界面或命令行操作。

**核心功能**:
- 提供 Web UI 和 CLI 两种使用方式，内置 Web 服务器
- 集成 200+ 模块，覆盖域名枚举、邮箱/电话/人名提取、IP 地理定位、端口扫描、数据泄露搜索、暗网搜索等
- 支持多种目标类型：IP、域名、主机名、CIDR、ASN、邮箱、电话、用户名、人名、比特币地址
- YAML 配置的关联引擎，内置 37 条预定义规则
- 支持 CSV/JSON/GEXF 格式导出，SQLite 后端存储
- 集成 TOR 以支持暗网搜索，可调用 DNSTwist、Nmap、Whatweb 等第三方工具
- 提供 Dockerfile 便于容器化部署

**技术亮点**: 基于 Python 3.7+ 开发，采用发布者/订阅者模型驱动模块间数据流转，实现自动化数据提取与关联分析；MIT 开源协议，自 2012 年起持续活跃维护。

---
## 6. [citrolabs/ego-lite](https://github.com/citrolabs/ego-lite)
- **语言**: JavaScript
- **Stars**: 10,384
- **简介**: The fastest browser for AI agents to run browser automation, built for sharing your logged-in browser state with your AI agents, like Codex or Claude Code, without disturbing you. Zero cost, zero config.

### AI 总结
**简介**: ego lite 是一款专为 AI 智能体设计的极速浏览器，让你和 AI 代理并行工作，共享登录状态，无需额外配置即可运行浏览器自动化任务。

**核心功能**:
- **并行工作空间**: 每个 AI 代理拥有独立的 Space，你的标签页与代理的任务互不干扰，后台快速完成任务
- **无缝登录共享**: 首次启动可迁移 Chrome 数据，代理直接继承你的登录态、Cookie、扩展和书签
- **零配置接入**: 通过 `ego-browser` 技能一键安装，支持自然语言指令驱动代理执行浏览器任务
- **代码优先架构**: 能力封装为 JavaScript 函数供代理直接调用，复杂工作流比传统 CLI 方式快 2.5 倍，工具调用次数更少
- **隐私保护**: 浏览数据仅存本地，只记录你是否选择迁移 Chrome 数据

**技术亮点**: 基于 JavaScript 构建，采用代码调用而非 CLI 交互模式，为代理提供高效的函数级 API；当前支持 macOS（Apple Silicon 和 Intel），Windows/Linux 版本在规划中。

---
## 7. [holaboss-ai/holaOS](https://github.com/holaboss-ai/holaOS)
- **语言**: TypeScript
- **Stars**: 7,311
- **简介**: Open-source All in One AI agent workspace. Run any agent — Claude Code, Codex — across your tools (100+ integrations + MCP), apps, browser, and files, with shared memory. Built-in models or BYOK.

### AI 总结
**简介**: holaOS 是一个开源的 All-in-One AI 智能体工作台，让你在本地优先的工作空间中运行任意 AI 智能体（如 Claude Code、Codex），并共享统一的记忆、工具和集成。

**核心功能**:
- **多智能体统一工作区**：可并排运行 Claude Code、Codex 及内置 holaOS 智能体，无需切换，所有智能体共享相同的记忆、工具、技能和应用
- **共享记忆系统**：上下文、偏好和项目历史存储在本地纯文本文件中，跨会话和跨智能体持久保存，可随时读取和编辑
- **灵活模型接入**：内置最新前沿模型（Kimi K3、GLM 5.2、GPT 5.6、Claude Opus 5 等），零配置开箱即用；同时支持 BYOK（自带密钥）接入 OpenAI、Anthropic 或兼容端点
- **广泛集成生态**：支持 100+ 工具集成及 MCP（Model Context Protocol），覆盖应用、浏览器和文件系统

**技术亮点**: 基于 Electron 构建跨平台桌面应用（支持 macOS Apple Silicon/Intel、Windows、Linux），使用 TypeScript 开发，采用 Modified Apache 2.0 开源许可证，本地优先架构确保数据自主可控。

---
## 8. [github/spec-kit](https://github.com/github/spec-kit)
- **语言**: Python
- **Stars**: 128,538
- **简介**: 💫 Toolkit to help you get started with Spec-Driven Development

### AI 总结
**简介**: Spec Kit 是一个开源工具包，帮助开发者采用“规范驱动开发”（Spec-Driven Development）方法论，将可执行规范直接转化为可工作的软件实现，适用于任何 AI 编程代理。

**核心功能**:
- **Specify CLI 工具**: 提供命令行工具，支持快速安装（通过 uv 或 PyPI）、项目初始化（`specify init`）以及自我升级管理（`specify self upgrade/check`）
- **项目宪法创建**: 通过 `/speckit.constitution` 命令为项目建立治理原则和开发指南，指导后续所有开发工作
- **AI 代理集成**: 支持多种 AI 编程代理（如 GitHub Copilot CLI、Codex CLI 等），以斜杠命令或技能模式调用
- **可扩展架构**: 提供扩展与预设机制，支持按角色配置的 Bundles，适应不同团队和项目需求
- **文档与社区支持**: 提供完整文档（GitHub Pages）、中英文双语支持及社区驱动的发展模式

**技术亮点**: 基于 Python 构建，依赖 uv 包管理器；CLI 支持从 Git 仓库或 PyPI 安装，具备自更新机制（自动检测 uv tool 或 pipx 安装方式）；采用规范即代码（Spec-as-Code）理念，使规范具备可执行性。

---
## 9. [lightningpixel/modly](https://github.com/lightningpixel/modly)
- **语言**: TypeScript
- **Stars**: 5,953
- **简介**: Desktop app to generate 3D models from images or prompt using local AI — runs entirely on your GPU

### AI 总结
**简介**: Modly 是一款本地开源的桌面应用，利用 GPU 上的 AI 模型将图片或文字提示词转换为 3D 模型，支持 Windows、Linux 和 Apple Silicon macOS。

**核心功能**:
- **图片/提示词生成 3D 网格**: 将任意照片或文字描述转换为 3D 模型，全程本地运行，数据不出设备
- **扩展系统**: 支持通过 GitHub 仓库安装外部模型和处理流程扩展，官方提供 Hunyuan3D、TripoSG、Trellis2 等多种模型扩展
- **可视化工作流**: 提供节点式工作流编辑，支持从图片到网格生成再到场景添加的完整流程，并在运行前校验连接有效性
- **模型后处理**: 支持对导入的网格进行平滑和减面优化，并将结果写回工作区
- **CLI 自动化接口**: 提供 Python CLI 工具，支持健康检查、模型管理、工作流状态查询和命令行生成 3D 模型，便于代理和脚本集成
- **实时系统监控**: 顶栏显示实时 RAM 使用情况

**技术亮点**: 采用 Electron + TypeScript 前端与 Python FastAPI 后端架构，支持 GPU 加速的本地 AI 推理；内置扩展机制允许动态加载第三方模型仓库；CLI 与桌面应用通过 REST API 通信，并区分规范接口、遗留接口和实验性接口；跨平台打包支持 Apple Silicon 原生构建。

---
## 10. [infiniflow/ragflow](https://github.com/infiniflow/ragflow)
- **语言**: Go
- **Stars**: 88,394
- **简介**: RAGFlow is a leading open-source Retrieval-Augmented Generation (RAG) engine that fuses cutting-edge RAG with Agent capabilities to create a superior context layer for LLMs

### AI 总结
**简介**: RAGFlow 是一个领先的开源检索增强生成（RAG）引擎，将前沿 RAG 技术与 Agent 能力深度融合，为大型语言模型（LLM）构建高质量上下文层。

**核心功能**:
- 融合 RAG 与 Agent 能力，提供企业级可扩展的简化 RAG 工作流
- 内置预构建 Agent 模板，助力开发者高效构建生产级 AI 系统
- 提供云端服务（cloud.ragflow.io）与自托管部署选项（支持 Docker）
- 支持多语言文档（中/英/日/韩/法/阿等 12 种语言）
- 提供完整的文档、路线图及社区支持（Discord、X/Twitter）

**技术亮点**:
- 基于 Go 语言开发，采用 Apache-2.0 开源协议
- 核心为"上下文引擎"（Context Engine），可将复杂数据转换为高保真、高精度的 AI 系统
- 支持从源码构建 Docker 镜像及开发环境启动，具备灵活的配置能力
- 提供 DeepWiki 集成，便于开发者深入理解代码架构

---
