---
tags:
  - github-trending
  - daily
date: 2026-08-16
created: 2026-08-16T01:55:43.592Z
---

# 2026-08-16 GitHub Trending Top 10

## 1. [cordiverse/cordis](https://github.com/cordiverse/cordis)
- **语言**: TypeScript
- **Stars**: 4,087
- **简介**: Meta-Framework of Spatiotemporal Composability

### AI 总结
**简介**: Cordis 是一个基于 TypeScript 的元框架，专注于时空组合性（Spatiotemporal Composability），旨在为复杂时空数据应用提供统一的组合化开发范式。

**核心功能**:
- 提供时空维度的组件化组合能力，支持将时间与空间逻辑解耦并灵活编排
- 内置元框架层，允许开发者自定义组合规则与扩展协议
- 支持模块化核心包（`packages/core`），便于按需集成与轻量化部署
- 面向地理信息系统、物联网、实时仿真等需要时空联动的场景

**技术亮点**: 采用 TypeScript 构建，强调类型安全与可组合性；架构上采用元框架设计，将核心逻辑与具体领域实现分离，便于跨项目复用与生态扩展。

---
## 2. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 18,661
- **简介**: 29 editorial diagram types for Claude Code. Self-contained HTML + SVG. No shadows, no Mermaid-slop.

### AI 总结
**简介**: 一个为 Claude Code 等 AI 编程助手设计的图表生成技能库，提供 27 种编辑级品质的 HTML+SVG 图表类型，无需 Figma 或繁琐的样式调整。

**核心功能**:
- 提供 27 种视觉图表类型（架构图、流程图、时序图、状态机、ER 图、时间线、泳道图、象限图、嵌套图、树形图、组织架构图、维恩图、层级堆栈、金字塔/漏斗图、顾问 2×2、雷达图、循环图、IT 现状图等），每种均包含 minimal light、minimal dark、full-editorial 三种静态变体
- 作为 Claude Code、Codex 和 Pi 的 agent skill，可通过自然语言描述直接生成图表
- 支持语义化模式描述，将行为与布局分离，队列、策略追踪、信任边界等可复用现有图表类型
- 可读取网站内容，在 60 秒内匹配品牌风格
- 支持将 draw.io 或 Mermaid 源文件按指定格式、尺寸和细节级别重新绘制
- 可选的无障碍动效支持（默认保持静态输出）

**技术亮点**: 纯 HTML+SVG 实现，无构建步骤、无 JavaScript 依赖、无外部图片资源，可直接在浏览器打开；采用编辑级设计原则（无阴影、无通用圆角框），强调信息密度控制和强调色精准使用。

---
## 3. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 2,955
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，为开发者提供面向常用开发工具、框架和 SaaS 产品的插件规范与官方实现，每个插件独立成目录并包含 `plugin.json` 清单文件。

**核心功能**:
- **开发工具类插件**: 涵盖持续学习（AGENTS.md 增量记忆更新）、团队协作工作流（CI/代码审查/发布）、分支深度审查（安全与代码质量审计）、插件脚手架创建、仓库兼容性扫描、面向编码代理的 CLI 设计模式等。
- **可视化增强插件**: PR 审查画布（按重要性分组展示 diff）、文档画布（将架构笔记/API 文档渲染为可导航的交互式画布）。
- **SDK 与自动化**: 基于 Cursor TypeScript SDK 构建应用与 CI 流水线（含运行时选择、鉴权、流式处理、MCP 支持），以及并行云代理编排工具。
- **生产力集成（第三方 MCP）**: 通过 Google 远程 MCP 服务器连接 Gmail、Google Drive、Google Calendar。
- **业务系统集成（第三方 MCP）**: 覆盖 CRM 与销售场景，包括 Salesforce、HubSpot、Apollo.io、Intercom、Docusign、Gong、Ashby、Circleback 等官方远程 MCP 服务器接入。

**技术亮点**: 采用 TypeScript 编写，基于 `.cursor-plugin/plugin.json` 清单的插件规范；广泛集成 MCP（Model Context Protocol）远程服务器；提供可复用的代理工作流模式（并行子代理、规划器-执行器-验证器架构）。

---
## 4. [cactus-compute/needle](https://github.com/cactus-compute/needle)
- **语言**: Python
- **Stars**: 6,080
- **简介**: 14MB foundation model for tiny devices; phones, wearables, smart home, and robots.

### AI 总结
**简介**: Needle 2 是一个面向工具调用、设备使用和结构化提取的 45M 参数开源模型，整个模型打包为单个 14MB 二进制文件，可在约 28MB RAM 中运行完整会话，专为手机、可穿戴设备、智能家居和机器人等小型设备设计。

**核心功能**:
- **工具调用**: 通过装饰器声明工具，模型自动选择调用并填充参数，执行后返回结构化结果
- **结构化提取**: 支持 Pydantic 模型声明数据形状，从文本中提取类型化对象
- **工具检索**: 内置检索头可从大型工具目录中每轮仅渲染前五个最相关工具
- **置信度门控**: 每个响应携带校准的置信度分数，可设置阈值决定执行或升级处理
- **有界内存**: 256-token 滑动窗口配合 KV 固定机制，无论对话多长总内存保持在 28MB 附近
- **浏览器游乐场**: 提供 Web UI 进行模型交互测试和微调操作
- **LoRA 微调**: 支持在冻结基座上微调并导出合并后的 `.cact` 权重文件

**技术亮点**: 基于 Simple Attention Network 架构（Hadamard MLP 替代 FFN、GQA 注意力、engram 键值记忆、多通道超连接），使用 Cactus Quants 压缩至 CQ2-bit（2 bits），权重直接烘焙进推理引擎，无需独立模型文件，推理过程零网络请求；字节级语法编译自声明 schema 约束每个 token 的生成。

---
## 5. [unslothai/unsloth](https://github.com/unslothai/unsloth)
- **语言**: Python
- **Stars**: 72,063
- **简介**: Local UI to run and train LLMs and diffusion models, including Qwen3.8, Kimi K3, MiniMax-H3, Gemma 4, DeepSeek-V4, FLUX and more.

### AI 总结
**简介**: Unsloth 是一款本地桌面应用，用于运行和训练 LLM 及扩散模型，支持 Qwen3.8、Kimi K3、MiniMax-H3、Gemma 4、DeepSeek-V4、FLUX 等模型。

**核心功能**:
- **模型运行与构建**: 支持运行和训练 LLM、扩散模型、嵌入模型、音频模型，并集成 Agent 工具（Claude Code、Codex、MCP）、搜索与 RAG、图像/视频/音频处理。
- **硬件兼容**: 支持 CPU、NVIDIA、AMD、Intel、macOS 及多 GPU 环境，并可通过 Cloudflare HTTPS 实现远程安全访问。
- **微调与部署**: 支持 LoRA、QLoRA、全量微调、预训练、强化学习（RL、GRPO、DPO）、FP8 等，训练速度提升 2 倍且显存占用降低 70%。
- **导出与 API**: 支持导出 GGUF、NVFP4、FP8 等格式，提供 OpenAI 兼容 API 及云服务商连接。
- **数据构建**: 通过 Data Recipes 从 PDF、CSV、DOCX 等文件构建数据集。

**技术亮点**: 跨平台桌面应用（Windows/macOS/Linux），提供一键安装脚本（curl/PowerShell），支持多模态模型训练与推理，并集成远程访问和强化学习等高级特性。

---
## 6. [public-apis/public-apis](https://github.com/public-apis/public-apis)
- **语言**: Python
- **Stars**: 460,214
- **简介**: A collective list of free APIs

### AI 总结
**简介**: public-apis 是一个由社区维护的免费公共 API 集合列表，涵盖多个领域的可用 API 资源。

**核心功能**:
- 提供大量免费公共 API 的精选列表，涵盖 IP 定位、股票数据、天气查询、航班信息、邮件验证等多个领域
- 支持通过 APILayer 统一套件集成生产级 REST API，使用一个账号、一个仪表盘和一个 API 密钥即可访问多种服务
- 提供 Postman 集合，方便开发者快速测试和集成 API
- 社区驱动，由成员持续贡献和维护 API 列表

**技术亮点**: 项目使用 Python 编写，提供标准化的 API 分类和描述格式，支持通过 Postman 快速运行测试，并集成了 Discord 社区支持。

---
## 7. [MakazhanAlpamys/Soup](https://github.com/MakazhanAlpamys/Soup)
- **语言**: Python
- **Stars**: 1,683
- **简介**: Fine-tune LLMs from one YAML. Layer streaming trains an 8B model on a 4 GB laptop GPU.

### AI 总结
**简介**: Soup 是一个通过单一 YAML 配置即可微调大语言模型（LLM）的 CLI 工具，支持在 4 GB 显存的笔记本 GPU 上训练 8B 模型，无需 SSH 或繁琐的环境配置。

**核心功能**:
- **一条命令微调**: `soup init` + `soup train` 即可完成配置和训练，无需手动管理基础设施
- **Layer Streaming 技术**: 将冻结的基础模型分块送入 GPU，在 4 GB 显存（如 RTX 3050 Laptop）上实现 8B 模型微调，峰值显存仅 3.32 GB，速度达 119.6 tok/s
- **零 SSH 依赖**: 完全本地运行，支持 QLoRA 量化，无需云 GPU 或远程服务器
- **自动配置**: 自动处理 batch size、GPU 检测、量化等参数
- **模型评估命令**: `soup ship` 提供发布门禁，可检测模型是否真正改进或回归

**技术亮点**: 基于 Python 3.10-3.12，采用 NF4 量化 + LoRA 微调，Layer Streaming 技术确保与常规训练 bit-exact 一致（已通过 Colab T4 独立验证）；支持 Apache-2.0 开源协议，提供完整基准测试和学术论文（DOI: 10.5281/zenodo.21771064）。

---
## 8. [github/spec-kit](https://github.com/github/spec-kit)
- **语言**: Python
- **Stars**: 129,213
- **简介**: 💫 Toolkit to help you get started with Spec-Driven Development

### AI 总结
**简介**: Spec Kit 是一个开源工具包，帮助开发者通过“规范驱动开发”（Spec-Driven Development）流程，在使用任何 AI 编程代理时先定义“要构建什么”再动手编码，从而生成高质量软件。

**核心功能**:
- **可执行的规范**: 将传统规范文档转化为可直接生成工作实现的“可执行规范”，而非仅作为编码参考。
- **Specify CLI 工具**: 提供命令行工具 `specify-cli`，支持项目初始化（`specify init`）、自我升级（`specify self upgrade`）和更新检查（`specify self check`）。
- **AI 代理集成**: 支持多种 AI 编码代理（如 GitHub Copilot、Codex CLI 等），通过 `/speckit.*` 斜杠命令或 `$speckit-*` 命令快速调用。
- **项目原则建立**: 通过 `/speckit.constitution` 命令为项目创建治理原则和开发指南，指导后续开发。
- **扩展与预设**: 支持用户自定义扩展和预设，以及基于角色的 Bundles 配置，适配不同团队角色。
- **多语言文档**: 提供英文和简体中文 Readme，降低上手门槛。

**技术亮点**: 基于 Python 构建，依赖 `uv` 工具安装，支持从 Git 或 PyPI 发布；CLI 设计注重无提示操作和幂等性（如升级命令自动检测安装方式）；社区驱动，强调组织级应用和无限扩展性。

---
## 9. [megadose/holehe](https://github.com/megadose/holehe)
- **语言**: Python
- **Stars**: 13,124
- **简介**: holehe allows you to check if the mail is used on different sites like twitter, instagram and will retrieve information on sites with the forgotten password function.

### AI 总结
**简介**: holehe 是一个 OSINT 工具，用于检查邮箱是否在 Twitter、Instagram 等 120 多个网站上注册过账号，并利用“忘记密码”功能获取相关信息。

**核心功能**:
- 批量检测邮箱在 120+ 网站（如 Twitter、Instagram、Snapchat 等）的账号注册情况
- 通过“忘记密码”功能提取部分脱敏的恢复邮箱和手机号码
- 支持 CLI 命令行和 Python API 两种使用方式，可嵌入现有应用
- 不触发目标邮箱的警报通知，静默检测
- 输出标准化 JSON 格式结果，包含 exists、rateLimit、emailrecovery、phoneNumber 等字段

**技术亮点**:
- 基于 Python 3 开发，使用 trio 异步框架和 httpx 异步 HTTP 客户端提升并发效率
- 模块化架构设计，每个网站对应独立检测模块，易于扩展
- 提供 Docker 容器化部署，安装使用便捷
- 支持 Maltego 转换插件，便于可视化情报分析
- 内置速率限制检测机制，可识别网站的反爬限制

---
## 10. [altic-dev/FluidVoice](https://github.com/altic-dev/FluidVoice)
- **语言**: Swift
- **Stars**: 10,340
- **简介**: Fastest and only macOS Dictation app with on-device STT and custom trained AI enhancement model. A local Wispr Flow alternative. DM us on X for an easter egg 😉 - https://x.com/fluidvoiceapp

### AI 总结
**简介**: FluidVoice 是一款开源的 macOS 语音转文字听写应用，采用端侧 AI 增强技术，号称是目前最快且唯一支持本地 STT 的 macOS 听写工具，可视为 Wispr Flow 的本地替代方案。

**核心功能**:
- **本地语音识别**: 支持多种语音模型（NVIDIA Parakeet、Nemotron Speech 3.5、Cohere、Apple Speech、Whisper 等），实现说话与文字上屏几乎零延迟
- **Fluid Intelligence 本地 AI 增强**: 完全离线的本地 AI 模型，提供智能格式化、上下文感知大写、后处理等增强功能，无需云端、无需 API 密钥，数据不出 Mac
- **命令模式**: 通过语音在 Mac 上执行任意操作
- **写作模式**: 在任何应用的任何文本框中语音输入或改写文本
- **主题适配**: 自适应浅色/深色主题，支持工具栏快速切换
- **全新引导流程**: 语言优先的语音引擎设置、真实听写试用和 AI 增强配置一站式完成

**技术亮点**: 基于 Swift 开发，核心 STT 引擎采用 NVIDIA Parakeet 重构实现超低延迟；AI 增强层（Fluid Intelligence）为独立维护的私有本地运行时，与 GPLv3 开源主程序分离；支持 Homebrew 安装（`brew install --cask fluidvoice`）。

---
