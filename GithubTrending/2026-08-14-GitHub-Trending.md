---
tags:
  - github-trending
  - daily
date: 2026-08-14
created: 2026-08-14T01:55:44.147Z
---

# 2026-08-14 GitHub Trending Top 10

## 1. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 14,705
- **简介**: 29 editorial diagram types for Claude Code. Self-contained HTML + SVG. No shadows, no Mermaid-slop.

### AI 总结
**简介**: 一个为 Claude Code 等 AI 编程助手打造的图表生成技能库，提供 27 种编辑级质量的 HTML+SVG 图表类型，无需 Figma 或 Mermaid，即可生成与品牌风格一致的静态图表。

**核心功能**:
- 27 种视觉类型：涵盖架构图、流程图、时序图、状态机、ER 图、时间线、泳道图、象限图、嵌套图、树状图、组织架构图、维恩图、分层堆栈、金字塔/漏斗、咨询 2×2、雷达图、循环飞轮、IT 现状图、高层架构图、条形图、折线图等
- 三种静态变体：每种类型均提供极简浅色、极简深色、完整编辑风格三种版本，可直接在浏览器中打开，无构建步骤、无 JavaScript、无外部图片依赖
- 品牌匹配：通过读取网站自动匹配品牌风格，60 秒内完成定制
- 格式转换：可将 draw.io 或 Mermaid 源文件重绘为指定格式、尺寸和细节级别
- 语义化模式：将行为与布局分离描述，队列、策略追踪、信任边界等场景可复用现有类型，避免类型数量膨胀
- 可选动效：v2.3 起支持有序讲解的动效，但静态输出仍为默认

**技术亮点**: 自包含 HTML+SVG，无构建步骤、无运行时依赖；语义化设计理念（行为与布局解耦）；设计原则强调"每个节点都值得存在"，目标密度 4/10，强调克制与留白；支持 Claude Code、Codex、Pi 多平台代理技能。

---
## 2. [semantica-agi/semantica](https://github.com/semantica-agi/semantica)
- **语言**: Python
- **Stars**: 6,717
- **简介**: Graph-Native Infrastructure for Context and Accountable AI Systems

### AI 总结
**简介**: Semantica 是一个开源的图原生基础设施平台，为 AI 代理提供上下文管理和可审计的决策智能能力，被称为“AI 代理的开源 Palantir”。

**核心功能**:
- **上下文图构建**: 从企业数据中提取关键信息，构建上下文图和知识图谱（KG），无需依赖 LLM 即可完成图构建
- **决策溯源与审计**: 内置完整的决策溯源机制，确保 AI 决策可解释、可追溯、可审计，满足高监管行业合规要求
- **图分析与因果推理**: 支持在知识图谱上执行图分析和因果推理，提供确定性的推理能力
- **本体管理**: 支持知识建模和本体管理，帮助企业标准化领域知识
- **多语言图存储**: 支持 RDF 和 LPG（属性图）双模型，兼容 W3C 标准，实现跨系统互操作

**技术亮点**:
- **确定性基础设施层**: 位于 LLM、向量存储和代理框架之下，图构建、推理和溯源均不依赖 LLM，确保决策确定性
- **零厂商锁定**: 完全开源、可自托管、可审计，支持 Polyglot 图存储
- **企业数据集成**: 支持直接对接 Databricks Unity Catalog 和 Snowflake 仓库，将现有表转换为受治理、有血缘追踪的知识图谱，无需导出数据
- **Python 3.8+ 支持**，采用 MIT 开源协议，提供完整的文档、社区支持和演示视频

---
## 3. [anthropics/skills](https://github.com/anthropics/skills)
- **语言**: Python
- **Stars**: 169,060
- **简介**: Public repository for Agent Skills

### AI 总结
**简介**: Anthropic 官方发布的 Claude Agent Skills 公开仓库，包含技能示例、规范文档和模板，用于展示如何通过指令、脚本和资源增强 Claude 在特定任务上的表现。

**核心功能**:
- **技能示例集合**: 涵盖创意设计（艺术、音乐）、技术开发（Web 应用测试、MCP 服务器生成）和企业工作流（沟通、品牌）等多类技能，每个技能以独立文件夹 + `SKILL.md` 文件组织
- **文档处理技能**: 包含驱动 Claude 文档能力的 docx、pdf、pptx、xlsx 技能（源码可用，非开源），可作为复杂生产级技能的参考
- **技能规范与模板**: 提供 Agent Skills 标准规范（`spec` 目录）和基础技能模板（`template` 目录），帮助开发者快速创建自定义技能
- **多平台集成**: 支持通过 Claude Code 插件市场安装、Claude.ai 直接使用、Claude API 上传调用
- **技能创建简化**: 只需一个包含 YAML frontmatter（`name` + `description`）和指令内容的 `SKILL.md` 文件即可定义新技能

**技术亮点**: 采用声明式技能定义（YAML frontmatter + Markdown 指令），技能以自包含文件夹形式组织，支持动态加载机制；仓库同时包含 Apache 2.0 开源技能和源码可用（source-available）的生产级文档处理技能，展示了从简单到复杂的技能设计模式。

---
## 4. [cactus-compute/needle](https://github.com/cactus-compute/needle)
- **语言**: Python
- **Stars**: 4,980
- **简介**: 14MB foundation model for tiny devices; phones, wearables, smart home, and robots.

### AI 总结
**简介**: Needle 2 是一个面向微型设备（手机、穿戴设备、智能家居、机器人）的 45M 参数开源基础模型，整个模型打包为单个 14MB 二进制文件，完整会话仅需约 28MB 内存即可运行。

**核心功能**:
- **工具调用**: 通过 `@needle.tool` 装饰器描述工具，模型自动选择调用并填充参数，支持结构化 JSON 输出
- **结构化提取**: 通过 Pydantic 模型声明数据形状，`extract()` 方法直接从文本中提取类型化对象
- **工具检索**: 内置检索头可声明大型工具目录，每轮仅渲染最相关的五个工具
- **置信度门控**: 每个响应携带校准后的置信度分数，可设置阈值决定执行或升级处理
- **本地推理引擎**: 权重直接烘焙进引擎，无需单独模型文件，推理过程不依赖网络

**技术亮点**: 基于 Simple Attention Network 架构（Hadamard MLP 替代 FFN、GQA 注意力、engram 键值记忆、多通道超连接），采用 Cactus Quants 压缩至 CQ2-bit，支持 LoRA 微调并合并导出为单一 `.cact` 文件，内置字节级语法约束解码，256-token 滑动窗口配合 KV 固定保持内存恒定。

---
## 5. [altic-dev/FluidVoice](https://github.com/altic-dev/FluidVoice)
- **语言**: Swift
- **Stars**: 9,874
- **简介**: Fastest and only macOS Dictation app with on-device STT and custom trained AI enhancement model. A local Wispr Flow alternative. ⭐ helps a ton :) Windows & iOS waitlist open. Linux soon.

### AI 总结
**简介**: FluidVoice 是一款开源的 macOS 语音转文字听写应用，采用本地端侧语音识别与 AI 增强模型，是 Wispr Flow 的本地化替代方案，主打极速响应和隐私保护。

**核心功能**:
- **极速本地语音转文字**：支持 Parakeet、Whisper、Apple Speech 等多种语音模型，其中 Parakeet 实现近乎零延迟的实时听写
- **Fluid Intelligence 本地 AI 增强**：在设备端完成智能格式化、上下文感知大写、标点修复和后期处理，无需云端 API，数据不出 Mac
- **命令模式（Command Mode）**：通过语音直接操控 Mac 上的任意操作
- **写入模式（Write Mode）**：在任何应用的任意文本框中完成文本撰写或改写
- **自适应主题**：支持浅色/深色主题切换，配备紧凑工具栏切换器
- **全新引导流程**：语言优先的语音引擎设置 + 真实听写试用 + AI 增强配置一站式完成

**技术亮点**: 使用 Swift 开发，核心语音引擎基于 NVIDIA Nemotron Speech 3.5 / Parakeet 系列模型；Fluid Intelligence 为独立维护的私有本地 AI 运行时（GPLv3 开源核心 + 私有增强层）；支持 Homebrew 安装（`brew install --cask fluidvoice`）；计划扩展至 iOS、Windows 和 Linux 平台。

---
## 6. [unslothai/unsloth](https://github.com/unslothai/unsloth)
- **语言**: Python
- **Stars**: 71,081
- **简介**: Local UI to run and train LLMs and diffusion models, including Qwen3.8, Kimi K3, MiniMax-H3, Gemma 4, DeepSeek-V4, FLUX and more.

### AI 总结
**简介**: Unsloth 是一款本地桌面应用，用于运行和训练 LLM 及扩散模型，支持 Qwen3.8、Kimi K3、MiniMax-H3、Gemma 4、DeepSeek-V4、FLUX 等模型。

**核心功能**:
- **模型运行与训练**: 支持 LLM、扩散模型、嵌入模型、音频模型的本地运行和训练
- **智能体与工具集成**: 与 Claude Code、Codex、MCP 集成，支持工具调用和代码执行
- **搜索与 RAG**: 支持私有无限网页搜索、深度研究和检索增强生成
- **多模态支持**: 可运行和训练图像、视频扩散模型及多模态模型
- **微调优化**: 训练速度提升 2 倍，VRAM 占用减少 70%，支持强化学习、LoRA、QLoRA、全量微调、预训练、RL、GRPO、DPO 和 FP8
- **导出与部署**: 支持导出为 GGUF、NVFP4、FP8 等格式，并提供 OpenAI 兼容 API
- **数据集构建**: 支持从 PDF、CSV、DOCX 等文件构建数据集

**技术亮点**: 支持 CPU、NVIDIA、AMD、Intel、macOS 及多 GPU 配置；提供跨平台桌面应用（Windows、macOS、Linux）；支持通过 Cloudflare HTTPS 安全远程访问本地模型；提供一键安装脚本和社区支持（Discord、Twitter、Reddit）

---
## 7. [macro-inc/macro](https://github.com/macro-inc/macro)
- **语言**: Rust
- **Stars**: 2,620
- **简介**: Macro is a unified workspace for teams: email, chat, docs, tasks, agents, calls, and CRM — @-linked together with shared AI memory.

### AI 总结
**简介**: Macro 是一个面向团队的一体化工作空间，将邮件、聊天、文档、任务、智能体和 CRM 统一到一个界面中，并通过共享的团队级 AI 记忆实现所有内容的 @链接和搜索。

**核心功能**:
- **统一收件箱**: 支持多 Google 账号的邮件聚合，键盘优先操作，整合邮件、消息、@提及和任务于同一列表
- **消息与频道**: 专为技术讨论设计的频道和私信，与任务、邮件深度集成
- **任务管理**: Linear 风格的任务系统，与频道、邮件和智能体紧密联动
- **实时协作文档**: 基于 CRDT 的 Markdown 原生文档，支持@提及和实时协同编辑
- **Canvas 画布**: 2D 白板，可嵌入任务、文件和邮件的 @链接
- **团队级 AI 智能体**: 拥有统一团队记忆，可代表用户执行操作，支持跨收件箱的 MCP 工具接口
- **通话记录**: 自动录制、转录并存入团队记忆供智能体使用
- **文件存储**: 自动从邮件和频道导入，全文可搜索
- **CRM 管理**: 客户和联系人对象，自定义属性，邮件同步与数据丰富

**技术亮点**: 使用 Rust 和 SolidJS 构建，强调速度与可靠性；所有功能共享同一后端，文档、任务、消息和邮件之间的交叉引用以双向图（bidirectional graph）原生存储，模块化设计如乐高积木般可扩展。

---
## 8. [megadose/holehe](https://github.com/megadose/holehe)
- **语言**: Python
- **Stars**: 12,443
- **简介**: holehe allows you to check if the mail is used on different sites like twitter, instagram and will retrieve information on sites with the forgotten password function.

### AI 总结
**简介**: holehe 是一个 OSINT 工具，用于检查邮箱是否在 Twitter、Instagram 等 120+ 网站上注册过账号，并通过"忘记密码"功能获取相关信息。

**核心功能**:
- 检查邮箱在 120+ 个网站（如 Twitter、Instagram、Snapchat 等）上的注册情况
- 利用"忘记密码"功能提取部分脱敏的恢复邮箱和手机号码
- 不会向目标邮箱发送任何通知，保持隐蔽性
- 支持 CLI 命令行和 Python API 两种使用方式
- 提供模块化输出，包含 rateLimit、exists、emailrecovery、phoneNumber 等结构化字段
- 支持 Docker 部署，方便快速使用

**技术亮点**:
- 基于 Python 3 开发，使用 trio 异步框架和 httpx 客户端实现高效并发请求
- 模块化架构设计，每个网站对应独立模块，易于扩展和维护
- 提供 Maltego 转换工具集成，便于可视化分析
- 支持自定义模块输出格式，方便嵌入其他 Python 应用
- 开源免费，采用 GNU GPL v3.0 许可证

---
## 9. [smicallef/spiderfoot](https://github.com/smicallef/spiderfoot)
- **语言**: Python
- **Stars**: 20,683
- **简介**: SpiderFoot automates OSINT for threat intelligence and mapping your attack surface.

### AI 总结
**简介**: SpiderFoot 是一个开源的 OSINT（开源情报）自动化工具，用于威胁情报收集和攻击面测绘，支持通过 Web 界面或命令行操作。

**核心功能**:
- 提供 Web UI 和 CLI 两种使用方式，内置 Web 服务器
- 包含 200+ 模块，可集成 Shodan、HaveIBeenPwned、GreyNoise 等数十种数据源
- 支持 IP、域名、子网、ASN、邮箱、电话号码、用户名、比特币地址等多种目标实体扫描
- 具备 YAML 配置的关联引擎，内置 37 条预定义规则
- 支持 CSV/JSON/GEXF 格式导出、API 密钥管理、SQLite 后端存储
- 集成 TOR 支持暗网搜索，可调用 DNSTwist、Nmap、Whatweb 等第三方工具
- 提供数据可视化、Docker 部署支持
- 可用于主机/子域枚举、数据泄露搜索、端口扫描、社交账号枚举、S3/Azure 桶枚举等侦察场景

**技术亮点**: 基于 Python 3.7+ 开发，采用发布者/订阅者模块架构实现数据源间自动联动；MIT 许可证开源，自 2012 年起持续维护；提供 Dockerfile 便于容器化部署。

---
## 10. [NVIDIA-NeMo/Switchyard](https://github.com/NVIDIA-NeMo/Switchyard)
- **语言**: Rust
- **Stars**: 1,231
- **简介**: Switchyard lets LLM applications route traffic across models and providers while preserving native OpenAI and Anthropic API compatibility - enabling flexible model selection, benchmarking, and cost/performance optimization.

### AI 总结
**简介**: Switchyard 是一个用 Rust 编写的 LLM 流量代理与路由库，支持在多个模型和提供商之间路由请求，同时保持 OpenAI 和 Anthropic API 原生兼容，用于灵活模型选择、基准测试和成本/性能优化。

**核心功能**:
- **协议转换**: 在 OpenAI Chat、Anthropic Messages 和 OpenAI Responses 格式之间自动转换，使 Claude Code、Codex 等编码代理可使用原生 API 调用开源模型
- **多后端路由**: 支持随机路由、LLM 分类器路由、信号驱动阶段路由以及自定义路由算法，实现 A/B 测试、分级调用和流量分配
- **运维指标**: 内置 Prometheus 指标，涵盖请求数、错误率、延迟、token 用量和路由开销

**技术亮点**:
- 纯 Rust 实现，提供三种使用路径：启动器（launcher）包装编码代理、独立服务器（server）作为代理、库（library）嵌入自有 Rust 应用
- 库路径设计为无 HTTP 栈依赖，算法只做路由决策，模型调用交还调用方，便于集成到现有网关或代理
- 支持 vLLM、NVIDIA NIM、Ollama 及任意 OpenAI 兼容端点作为后端
- 可通过 TOML 配置文件声明路由规则，支持 `--dry-run` 校验配置

---
