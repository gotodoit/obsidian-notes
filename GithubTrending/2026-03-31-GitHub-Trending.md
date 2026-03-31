---
tags:
  - github-trending
  - daily
date: 2026-03-31
created: 2026-03-31T01:55:48.958Z
---

# 2026-03-31 GitHub Trending Top 10

## 1. [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice)
- **语言**: Python
- **Stars**: 30,597
- **简介**: Open-Source Frontier Voice AI

### AI 总结
**简介**: VibeVoice 是微软开源的前沿语音AI模型家族，包含文本转语音和语音识别两大核心功能。

**核心功能**:
- **文本转语音**：提供长文本、多说话人语音合成能力，支持实时流式生成。
- **语音识别**：支持长达60分钟音频的单次识别，能生成带说话人、时间戳和内容的结构化转录，并支持用户自定义上下文。

**技术亮点**:
- 采用**7.5 Hz超低帧率**的连续语音分词器，在保持音频保真度的同时显著提升长序列处理效率。
- 基于**下一词扩散**框架，结合大语言模型理解文本上下文，并使用扩散头生成高质量音频。
- 模型已集成至 **Hugging Face Transformers** 库，并支持 **vLLM** 以加速推理。

---
## 2. [luongnv89/claude-howto](https://github.com/luongnv89/claude-howto)
- **语言**: Python
- **Stars**: 9,999
- **简介**: A visual, example-driven guide to Claude Code — from basic concepts to advanced agents, with copy-paste templates that bring immediate value.

### AI 总结
**简介**: 一个面向 Claude Code 的视觉化、示例驱动的学习指南，提供从基础概念到高级代理的完整学习路径和可复用的代码模板。

**核心功能**:
- 提供结构化的渐进式学习路径，包含 10 个教程模块，涵盖从基础命令到自定义代理团队等所有 Claude Code 功能。
- 包含大量可直接复制粘贴的生产级配置模板，如斜杠命令、CLAUDE.md 模板、钩子脚本和 MCP 配置。
- 通过 Mermaid 图表直观展示各功能内部工作原理，帮助理解其设计逻辑。
- 内置自我评估功能，支持在 Claude Code 中运行 `/self-assessment` 或 `/lesson-quiz` 命令来检测知识盲区并生成个性化学习路线。

**技术亮点**: 项目采用 Python 语言，内容与 Claude Code 版本（v2.2.0）保持同步，并通过可视化图表和交互式测验提升学习效率。

---
## 3. [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice)
- **语言**: HTML
- **Stars**: 26,267
- **简介**: practice made claude perfect

### AI 总结
**简介**: 这是一个关于 Claude Code 最佳实践的文档项目，旨在通过实践帮助开发者更好地使用 Claude Code 的各项功能。

**核心功能**:
- **子代理 (Subagents)**: 在独立上下文中运行的自主执行者，可配置自定义工具、权限、模型和身份。
- **命令 (Commands)**: 用户可调用的提示模板，用于编排工作流。
- **技能 (Skills)**: 可配置、可预加载、可自动发现的知识注入模块，支持上下文分叉和渐进式披露。
- **工作流 (Workflows)**: 用于任务编排，例如天气查询协调器。
- **钩子 (Hooks)**: 在特定事件（如代理循环外）运行的用户自定义处理器。
- **MCP 服务器**: 通过模型上下文协议连接外部工具、数据库和 API。
- **插件 (Plugins)**: 可分发包，包含技能、子代理、钩子、MCP 服务器等。
- **设置 (Settings)**: 分层配置系统，涵盖权限、模型配置、输出样式、沙箱、快捷键等。

**技术亮点**: 项目系统性地整理了 Claude Code 的核心概念（代理、命令、技能）及其实现，并强调了通过工作流编排、MCP 协议集成外部资源以及灵活的配置系统来构建高效开发实践。

---
## 4. [hacksider/Deep-Live-Cam](https://github.com/hacksider/Deep-Live-Cam)
- **语言**: Python
- **Stars**: 86,405
- **简介**: real time face swap and one-click video deepfake with only a single image

### AI 总结
**简介**: Deep-Live-Cam 是一个基于 Python 的实时人脸替换和视频深度伪造工具，仅需单张图片即可一键生成效果。

**核心功能**:
- **实时人脸替换**: 支持通过摄像头或视频流进行实时换脸。
- **多功能应用场景**: 包括口型遮罩（保留原始嘴部动作）、多目标同时换脸、实时电影换脸、直播表演、表情包制作以及在 Omegle 等平台上的互动。
- **简易操作流程**: 宣称仅需三步（选择人脸、选择摄像头、点击直播）即可完成实时深度伪造。

**技术亮点**: 项目基于 ONNX 模型（如 GFPGANv1.4 和 inswapper_128_fp16.onnx）实现，支持 CPU 和 GPU（包括 NVIDIA、AMD 及 Mac Silicon）运行，并提供预编译版本以简化非技术用户的安装过程。

---
## 5. [OpenBB-finance/OpenBB](https://github.com/OpenBB-finance/OpenBB)
- **语言**: Python
- **Stars**: 64,555
- **简介**: Financial data platform for analysts, quants and AI agents.

### AI 总结
**简介**: OpenBB 是一个面向分析师、量化交易员和 AI 代理的开源金融数据平台，旨在整合多种数据源并提供统一的数据访问层。

**核心功能**:
- 提供“一次连接，随处消费”的基础设施层，整合专有、授权和公共数据源。
- 通过 Python 包、REST API、MCP 服务器等多种方式暴露数据，支持量化研究、AI 助手和仪表板等下游应用。
- 提供企业级用户界面 OpenBB Workspace，用于数据可视化和集成 AI 代理。

**技术亮点**: 基于 Python 构建，采用 FastAPI 提供本地 API 服务器，支持通过 pip 快速安装，并可与 VS Code Dev Containers、GitHub Codespaces 和 Google Colab 等云开发环境集成。

---
## 6. [freeCodeCamp/freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp)
- **语言**: TypeScript
- **Stars**: 439,749
- **简介**: freeCodeCamp.org's open-source codebase and curriculum. Learn math, programming, and computer science for free.

### AI 总结
**简介**: freeCodeCamp 是一个开源、免费、自定进度的在线学习平台，提供全面的全栈开发和计算机科学课程，旨在帮助成年人转型进入科技行业。

**核心功能**:
- 提供多个免费的开发者认证，涵盖响应式网页设计、JavaScript、前后端开发、Python、关系数据库等。
- 提供免费的英语、西班牙语和中文语言能力认证（Beta版）。
- 平台包含数千个交互式编程挑战、项目实践和认证考试。
- 拥有活跃的社区支持，包括论坛、YouTube频道、技术出版物和Discord服务器。

**技术亮点**: 项目主要使用 TypeScript 开发，是一个功能完整的全栈学习平台。

---
## 7. [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock)
- **语言**: Python
- **Stars**: 74,763
- **简介**: Hunt down social media accounts by username across social networks

### AI 总结
**简介**: 一个用于通过用户名在多个社交网络上查找对应账户的 Python 工具。

**核心功能**:
- 支持在超过 300 个社交网站上搜索指定用户名。
- 提供命令行界面，支持多种参数（如超时设置、JSON输出、代理等）进行灵活搜索。
- 支持将搜索结果以多种格式（纯文本、JSON、CSV）保存到文件。

**技术亮点**: 基于 Python 开发，通过异步请求提高搜索效率，并支持通过代理和 Tor 网络进行匿名查询。

---
## 8. [apache/superset](https://github.com/apache/superset)
- **语言**: TypeScript
- **Stars**: 71,956
- **简介**: Apache Superset is a Data Visualization and Data Exploration Platform

### AI 总结
**简介**: Apache Superset 是一个现代化的、企业级的开源商业智能（BI）和数据可视化 Web 应用程序。

**核心功能**:
- 提供**无需代码的界面**，用于快速构建图表。
- 内置强大的基于 Web 的 **SQL 编辑器**，支持高级查询。
- 提供轻量级的**语义层**，用于快速定义自定义维度和指标。
- 支持**几乎任何 SQL 数据库或数据引擎**。
- 拥有丰富的**可视化图表库**，从简单的条形图到地理空间图表。
- 具备可配置的**缓存层**以减轻数据库负载。
- 提供高度可扩展的**安全角色和身份验证**选项。
- 开放 **API** 以支持程序化定制。

**技术亮点**: 采用云原生架构设计，使用 TypeScript 等现代技术栈，具备良好的可扩展性。

---
## 9. [fastfetch-cli/fastfetch](https://github.com/fastfetch-cli/fastfetch)
- **语言**: C
- **Stars**: 21,427
- **简介**: A maintained, feature-rich and performance oriented, neofetch like system information tool.

### AI 总结
**简介**: Fastfetch 是一个类似于 neofetch 的系统信息获取工具，专注于高性能和高度可定制化，使用 C 语言编写。

**核心功能**:
- 跨平台支持：兼容 Linux、macOS、Windows 8.1+、Android、FreeBSD、OpenBSD、NetBSD、DragonFly、Haiku 和 SunOS 等多种操作系统。
- 丰富的自定义选项：提供多种预设配置和主题，允许用户自定义信息显示内容和样式。
- 高性能：采用 C 语言编写，优化了执行速度，相比同类工具响应更快。

**技术亮点**:
- 使用 C 语言实现，强调性能和低资源占用。
- 支持模块化设计，便于扩展和集成新的系统信息模块。
- 提供详细的安装指南，覆盖主流包管理器（如 apt、pacman、brew、scoop 等），方便用户快速部署。

---
## 10. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 18,688
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 开发、具备自我学习和成长能力的 AI 代理框架。

**核心功能**:
- **多平台接入**: 支持通过 CLI 终端界面以及 Telegram、Discord、Slack、WhatsApp、Signal 等多种即时通讯平台与代理交互。
- **内置学习循环**: 代理能够从经验中创建技能，在使用中改进技能，并建立跨会话的用户模型，实现知识持久化。
- **灵活的模型支持**: 可无缝切换使用 Nous Portal、OpenRouter、OpenAI 等多种模型提供商或自定义端点，无供应商锁定。
- **强大的自动化与并行能力**: 内置定时任务调度器，支持创建并行工作的子代理，并能将多步骤任务管道简化为单次交互。
- **随处部署**: 支持在本地、Docker、SSH、Modal 等多种后端运行，成本效益高，可在低至 5 美元的 VPS 上运行。

**技术亮点**: 采用模块化设计，支持多种终端后端；集成了 Honcho 用户建模和 agentskills.io 开放标准；具备研究就绪功能，如批量轨迹生成和 Atropos RL 环境。

---
