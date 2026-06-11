---
tags:
  - github-trending
  - daily
date: 2026-06-11
created: 2026-06-11T01:55:44.121Z
---

# 2026-06-11 GitHub Trending Top 10

## 1. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: Shell
- **Stars**: 51,926
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 为 AI 编码代理提供生产级工程技能的指令集，涵盖软件开发生命周期的各个阶段。

**核心功能**:
- **7 个斜杠命令**：提供 `/spec`、`/plan`、`/build`、`/test`、`/review`、`/code-simplify`、`/ship` 命令，分别对应定义、计划、构建、测试、审查、简化代码和发布等开发环节。
- **自动技能激活**：根据当前开发活动（如设计 API 或构建 UI）自动触发相应的工程技能。
- **多平台支持**：支持在 Claude Code、Cursor、Gemini CLI、Windsurf、GitHub Copilot 等多种 AI 编码代理工具中安装和使用。
- **自动化构建**：`/build auto` 命令可自动生成计划并执行所有任务，仅在批准计划后自主运行，但仍保持测试驱动和逐个提交。

**技术亮点**: 采用 Shell 语言编写，所有技能以纯 Markdown 格式存储，可被任何接受系统提示或指令文件的 AI 代理使用，无需特定技术栈依赖。

---
## 2. [phuryn/pm-skills](https://github.com/phuryn/pm-skills)
- **语言**: Unknown
- **Stars**: 14,973
- **简介**: PM Skills Marketplace: 100+ agentic skills, commands, and plugins — from discovery to strategy, execution, launch, and growth.

### AI 总结
**简介**: PM Skills Marketplace 是一个为 AI 助手（如 Claude Code、Cowork）设计的技能市场，提供 100+ 个产品管理技能、命令和插件，覆盖从产品发现、策略、执行到上线和增长的完整工作流。

**核心功能**:
- **技能系统**: 68 个内置 PM 框架技能（如发现、假设映射、优先级排序、策略），可自动加载或强制调用
- **命令工作流**: 42 个链式命令（如 `/discover`、`/write-prd`、`/plan-launch`），将多个技能组合成端到端流程
- **插件化安装**: 9 个可安装的插件包（如发现、策略、执行、市场研究、AI 交付），覆盖 PM 各领域
- **跨助手兼容**: 支持 Claude Code、Claude Cowork、Codex CLI 等 AI 助手
- **流程衔接**: 命令完成后自动建议相关下一步命令，匹配 PM 工作流

**技术亮点**: 采用技能-命令-插件三层架构，技能可被多个命令共享，支持自动加载和强制加载；插件化设计便于按领域安装和管理；与多种 AI 助手原生兼容。

---
## 3. [refactoringhq/tolaria](https://github.com/refactoringhq/tolaria)
- **语言**: TypeScript
- **Stars**: 14,942
- **简介**: Desktop app to manage markdown knowledge bases

### AI 总结
**简介**: Tolaria 是一款跨平台桌面应用，用于管理基于 Markdown 的个人知识库，强调文件优先、离线优先和开源。

**核心功能**:
- **文件优先**: 所有笔记均为纯 Markdown 文件，可移植、无锁定。
- **Git 优先**: 每个知识库都是一个 Git 仓库，支持完整版本历史和任意远程仓库。
- **离线优先**: 无需账户、订阅或云依赖，完全离线工作。
- **AI 集成**: 支持 Claude Code、Codex CLI 等 AI 工具，提供 AGENTS 文件供 AI 理解。
- **键盘优先**: 专为高效键盘操作设计，包括强大的命令面板。
- **类型系统**: 类型作为导航辅助，而非强制模式，无必填字段。

**技术亮点**: 使用 Tauri、React 和 TypeScript 构建，支持 macOS、Windows 和 Linux。

---
## 4. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 39,125
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个AI代理驱动的搜索引擎，聚合Reddit、X、YouTube等多个平台的内容，根据用户参与度（点赞、评论等）评分并生成总结。

**核心功能**:
- 并行搜索多个平台（Reddit、X、YouTube、Hacker News、Polymarket、GitHub等），获取最新30天的内容
- 根据真实用户参与度（点赞、评论、交易等）对结果进行评分排序
- 通过AI代理综合所有来源信息，生成简洁、有依据的摘要

**技术亮点**:
- 零配置即可使用，通过插件市场或npx命令快速安装
- 支持用户自带API密钥和浏览器会话，突破各平台围墙花园限制
- 使用Python开发，支持50多种AI代理宿主环境

---
## 5. [soxoj/maigret](https://github.com/soxoj/maigret)
- **语言**: Python
- **Stars**: 32,054
- **简介**: 🕵️‍♂️ Collect a dossier on a person by username from 3000+ sites

### AI 总结
**简介**: Maigret 是一个基于用户名从 3000+ 个网站收集个人档案的 OSINT 工具，无需 API 密钥即可运行。

**核心功能**:
- 支持 3000+ 个网站的用户名搜索，默认检查 500 个高流量站点，可指定 `-a` 扫描全部或通过 `--tags` 按类别/国家过滤
- 自动从个人资料页面和网站 API 提取账户所有者的公开信息（包括关联账户链接）
- 支持递归搜索，利用发现的用户名和其他 ID 进行深度挖掘
- 提供网页界面，支持图表化浏览结果并一键导出多种格式报告
- 可选 AI 分析模式（`--ai`），通过 OpenAI 兼容 API 将原始发现转化为简短调查摘要

**技术亮点**: Python 3.10+，内置自动更新的站点数据库（每 24 小时从 GitHub 同步），支持 Tor 和 I2P 网络，具备反封锁和反审查检测能力

---
## 6. [x1xhlol/system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools)
- **语言**: Unknown
- **Stars**: 139,540
- **简介**: FULL Augment Code, Claude Code, Cluely, CodeBuddy, Comet, Cursor, Devin AI, Junie, Kiro, Leap.new, Lovable, Manus, NotionAI, Orchids.app, Perplexity, Poke, Qoder, Replit, Same.dev, Trae, Traycer AI, VSCode Agent, Warp.dev, Windsurf, Xcode, Z.ai Code, Dia & v0. (And other Open Sourced) System Prompts, Internal Tools & AI Models

### AI 总结
**简介**: 收集并公开了众多主流AI工具（如Cursor、Devin AI、Claude Code等）的系统提示词、内部工具与模型信息的仓库。

**核心功能**:
- 收录了超过20款AI工具的系统提示词（System Prompts）
- 提供AI工具的内部工具与模型信息
- 通过公开信息帮助开发者了解AI产品背后的提示工程

**技术亮点**: 专注于提示词逆向工程与安全审计，项目还关联了ZeroLeaks安全服务，用于识别AI系统的提示注入和系统提示提取风险。

---
## 7. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 223,637
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套为编码代理设计的完整软件开发方法论，基于可组合的技能和初始指令，确保代理在开发过程中遵循规范流程。

**核心功能**:
- **需求澄清**: 代理不会直接写代码，而是先通过对话引导用户明确真实需求，生成可读的设计文档。
- **规划驱动开发**: 在设计批准后，代理制定清晰的实现计划，强调 TDD、YAGNI 和 DRY 原则。
- **子代理驱动开发**: 代理将任务分解为小块，启动子代理独立执行工程任务，并自动审查工作，支持长时间自主运行。
- **多平台支持**: 提供插件安装方式，支持 Claude Code、Codex CLI、Cursor 等多种编码代理平台。

**技术亮点**: 基于 Shell 脚本实现，通过可组合的技能自动触发，无需用户额外操作；采用子代理架构实现任务分解与并行执行。

---
## 8. [masterking32/MasterDnsVPN](https://github.com/masterking32/MasterDnsVPN)
- **语言**: Go
- **Stars**: 5,236
- **简介**: Advanced DNS tunneling VPN for censorship bypass, optimized beyond DNSTT and SlipStream with low-overhead ARQ, resolver load balancing, high packet-loss stability and speed.

### AI 总结
**简介**: MasterDnsVPN 是一个基于 DNS 隧道的 VPN 工具，专为绕过网络审查而设计，在性能上优于 DNSTT 和 SlipStream，具有低开销 ARQ、解析器负载均衡、高丢包稳定性和高速等特点。

**核心功能**:
- 使用 DNS 隧道技术实现 VPN 功能，绕过网络审查
- 支持低开销的自动重传请求（ARQ），提高数据传输可靠性
- 实现 DNS 解析器负载均衡，优化连接稳定性
- 在高丢包网络环境下保持稳定连接和高速传输

**技术亮点**: 使用 Go 语言开发，采用先进的 DNS 隧道技术，结合低开销 ARQ 协议和解析器负载均衡算法，在速度和稳定性上超越传统 DNSTT 和 SlipStream 方案。

---
## 9. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)
- **语言**: Python
- **Stars**: 85,100
- **简介**: 利用AI大模型，一键生成高清短视频 Generate short videos with one click using AI LLM.

### AI 总结
**简介**: MoneyPrinterTurbo 是一个利用 AI 大模型一键生成高清短视频的开源工具，用户只需提供主题或关键词即可自动完成文案、素材、字幕、背景音乐及视频合成。

**核心功能**:
- AI 自动生成或自定义视频文案
- 支持竖屏 (9:16) 和横屏 (16:9) 高清视频尺寸
- 批量视频生成，支持片段时长、字幕样式、背景音乐等细节调节
- 集成多种语音合成、字幕描边、本地素材上传功能
- 支持 OpenAI、通义千问、DeepSeek 等多种大模型接入

**技术亮点**:
- 采用 MVC 架构，代码结构清晰，支持 API 和 Web 界面双模式
- 集成 Pexels、Pixabay、Coverr 等无版权高清素材源
- 支持 Docker 部署、Windows 一键启动包及 Google Colab 在线体验

---
## 10. [maziyarpanahi/openmed](https://github.com/maziyarpanahi/openmed)
- **语言**: Python
- **Stars**: 2,314
- **简介**: open-source healthcare ai

### AI 总结
**简介**: OpenMed 是一个本地优先的开源医疗 AI 工具，能够将临床文本转化为结构化信息，所有处理均在设备端完成，无需云端或网络连接。

**核心功能**:
- **实体提取**: 从临床文本中提取疾病、药物等医学实体，支持 1000+ 专业模型。
- **PII 去标识化**: 实时识别并脱敏患者姓名、地址、ID 等个人隐私信息，保护数据安全。
- **多语言支持**: 支持英语、简体中文、西班牙语等 12 种语言。

**技术亮点**:
- **完全本地运行**: 基于 Apple MLX 框架，支持在 iPhone、iPad、macOS 等设备上离线运行，数据永不离开设备。
- **丰富的模型库**: 提供 1000+ 专用医疗模型，包括 247 个 PII 检测检查点，覆盖多种临床场景。
- **跨平台兼容**: 提供 Python 库和 Swift 框架（OpenMedKit），一行代码即可集成，适用于从脚本到原生应用的多种开发环境。
- **开源协议**: 采用 Apache-2.0 许可，免费且无供应商锁定。

---
