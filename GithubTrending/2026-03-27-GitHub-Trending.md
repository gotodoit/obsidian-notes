---
tags:
  - github-trending
  - daily
date: 2026-03-27
created: 2026-03-27T01:55:49.939Z
---

# 2026-03-27 GitHub Trending Top 9

## 1. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 10,381
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个能跨多个平台（Reddit、X、YouTube、Hacker News、Polymarket等）自动研究指定主题并生成带真实引用的综合性总结的AI智能体技能。

**核心功能**:
- **多平台聚合研究**: 自动搜索Reddit、X、Bluesky、YouTube、TikTok、Instagram、Hacker News、Polymarket及全网在过去30天内的相关内容。
- **智能分析与总结**: 通过多信号质量排名相关性评分、跨平台收敛检测等复杂管道处理结果，并生成基于数据的、带引用的综合性叙述报告。
- **比较模式**: 支持“X vs Y”式对比查询，进行三次并行研究，生成包含优劣势对比、数据驱动结论的并排分析报告。
- **结果自动归档**: 每次运行都会将完整的简报以Markdown格式自动保存到本地文档目录，构建个人研究库。

**技术亮点**:
- **模块化数据源集成**: 支持ScrapeCreators API（覆盖Reddit、TikTok、Instagram）、Bird客户端（免费X搜索）等多种数据源。
- **复合评分管道**: 采用双向文本相似性、参与度速度归一化、来源权威性加权、跨平台收敛检测和时间衰减等多维度算法对结果进行排序。
- **配置与扩展性**: 支持项目级环境变量配置（`.claude/last30days.env`），并拥有超过455个测试的广泛测试覆盖。

---
## 2. [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode)
- **语言**: TypeScript
- **Stars**: 12,707
- **简介**: Teams-first Multi-agent orchestration for Claude Code

### AI 总结
**简介**: 一个为 Claude Code 设计的、团队优先的多智能体编排工具，旨在提供零学习曲线的开发体验。

**核心功能**:
- **团队模式**：作为核心编排方式，支持通过 `/team` 命令或 `omc team` CLI 指令，以管道化流程（计划、需求、执行、验证、修复）协同多个智能体完成任务。
- **多模型支持**：支持调用 Claude、Codex 和 Gemini 模型协同工作，可通过 `/ccg` 技能进行三模型综合咨询。
- **快速启动与深度访谈**：提供简单的三步安装设置流程，并通过 `/deep-interview` 技能在编码前使用苏格拉底式提问来澄清需求、暴露隐藏假设。
- **tmux CLI 工作器**：从 v4.4.0 开始，通过 `omc team` 命令可动态创建和管理基于 tmux 的 Codex、Gemini 或 Claude CLI 工作器面板，任务完成后自动关闭，无闲置资源消耗。

**技术亮点**:
- **零学习曲线设计**：强调无需学习 Claude Code 本身即可使用。
- **TypeScript 开发**：项目主要使用 TypeScript 语言。
- **灵活的部署方式**：既可作为 Claude Code 插件安装，也可通过 npm 全局安装 CLI 工具（包名为 `oh-my-claude-sisyphus`）。

---
## 3. [virattt/dexter](https://github.com/virattt/dexter)
- **语言**: TypeScript
- **Stars**: 19,016
- **简介**: An autonomous agent for deep financial research

### AI 总结
**简介**: Dexter 是一个用于深度金融研究的自主智能体，能够通过任务规划、自我反思和实时市场数据进行分析。

**核心功能**:
- **智能任务规划**：自动将复杂的金融查询分解为结构化的研究步骤。
- **自主执行**：选择并执行适当的工具来收集金融数据。
- **自我验证**：检查自身工作并进行迭代，直至任务完成。
- **实时金融数据**：访问损益表、资产负债表和现金流量表。
- **安全特性**：内置循环检测和步骤限制，防止无限执行。

**技术亮点**: 项目使用 TypeScript 开发，基于 Bun 运行时，并集成了 OpenAI、Financial Datasets 等外部 API 以获取数据和智能。

---
## 4. [ruvnet/RuView](https://github.com/ruvnet/RuView)
- **语言**: Rust
- **Stars**: 43,226
- **简介**: π RuView: WiFi DensePose turns commodity WiFi signals into real-time human pose estimation, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: RuView 是一个基于边缘AI的感知系统，利用Wi-Fi等环境信号实现无摄像头、无穿戴设备的人体姿态估计、生命体征监测和存在检测。

**核心功能**:
- **人体姿态估计**: 通过分析Wi-Fi信道状态信息（CSI）扰动，实时重建人体姿态（DensePose）。
- **生命体征监测**: 实时检测呼吸频率（6-30 BPM）和心率（40-120 BPM）。
- **存在与运动感知**: 基于信号强度（RSSI）方差和运动频带功率，实现低延迟（<1ms）的存在检测。
- **穿墙感知**: 利用菲涅尔区几何和多径建模，实现穿透墙壁的感知（深度可达5米）。

**技术亮点**:
- **边缘AI与自学习**: 基于Rust构建，运行于低成本ESP32硬件，无需互联网、云服务或标注数据，系统可在本地持续自学习与适应。
- **高性能信号处理**: 姿态估计处理速度高达54K fps，系统包含1300+测试用例，确保可靠性。
- **模块化与可部署**: 提供Docker镜像和Rust crate，支持快速部署和验证。

---
## 5. [bytedance/deer-flow](https://github.com/bytedance/deer-flow)
- **语言**: Python
- **Stars**: 48,510
- **简介**: An open-source long-horizon SuperAgent harness that researches, codes, and creates. With the help of sandboxes, memories, tools, skill, subagents and message gateway, it handles different levels of tasks that could take minutes to hours.

### AI 总结
**简介**: DeerFlow 是一个由字节跳动开源的、用于编排子代理、记忆和沙箱以处理长时间跨度复杂任务的超级智能体框架。

**核心功能**:
- **子代理编排**：通过协调多个子代理来分解和处理复杂任务。
- **技能与工具集成**：提供可扩展的技能库，并集成了字节跳动的智能搜索工具 InfoQuest。
- **沙箱与文件系统**：提供安全的执行环境，支持代码执行和文件操作。
- **长期记忆与上下文工程**：具备记忆能力，能管理长对话和任务上下文。

**技术亮点**:
- **多语言支持**：提供 Python (3.12+) 和 Node.js (22+) 环境。
- **容器化部署**：推荐使用 Docker 进行一键部署和运行。
- **模型友好**：官方推荐使用豆包、DeepSeek、Kimi 等大模型来驱动。
- **架构重构**：2.0 版本为完全重写，采用全新的超级智能体架构。

---
## 6. [Vaibhavs10/insanely-fast-whisper](https://github.com/Vaibhavs10/insanely-fast-whisper)
- **语言**: Jupyter Notebook
- **Stars**: 11,267
- **简介**: 

### AI 总结
**简介**: 一个基于 Transformers 和 Flash Attention 2 的极速音频转录命令行工具，能在约 98 秒内转录 2.5 小时的音频。

**核心功能**:
- 提供命令行界面，支持本地音频文件或 URL 的快速转录。
- 支持多种 Whisper 模型，包括 OpenAI 的 Whisper-large-v3 和 Distil-whisper。
- 支持转录和翻译任务，并可指定输出语言。

**技术亮点**: 利用 Hugging Face Transformers、Optimum 库及 Flash Attention 2 技术，结合半精度（fp16）、批处理（batching）和 BetterTransformer 等优化，实现 GPU（NVIDIA 和 Mac MPS）上的极致转录速度。

---
## 7. [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope)
- **语言**: Python
- **Stars**: 20,473
- **简介**: Build and run agents you can see, understand and trust.

### AI 总结
**简介**: AgentScope 是一个面向生产环境、易于使用的智能体框架，旨在构建可见、可理解且可信赖的智能体。

**核心功能**:
- **简单易用**：内置 ReAct 智能体、工具、技能、人机交互、记忆、规划、实时语音、评估和模型微调，可快速上手。
- **高度可扩展**：提供丰富的生态系统集成（工具、记忆、可观测性），内置支持 MCP 和 A2A 协议，并通过消息中心实现灵活的多智能体编排。
- **生产就绪**：支持本地部署、云端无服务器部署或 Kubernetes 集群部署，并内置 OpenTelemetry 支持。

**技术亮点**:
- 基于 Python 3.10+，采用 Apache 2.0 开源协议。
- 设计理念强调利用大语言模型的推理和工具使用能力，而非用严格的提示词和固执的编排来约束它们。
- 近期新增实时语音智能体、数据库支持与记忆压缩、A2A 协议、TTS 等高级功能。

---
## 8. [twentyhq/twenty](https://github.com/twentyhq/twenty)
- **语言**: TypeScript
- **Stars**: 41,293
- **简介**: Building a modern alternative to Salesforce, powered by the community.

### AI 总结
**简介**: Twenty 是一个由社区驱动的开源 CRM，旨在构建一个现代化的 Salesforce 替代方案。

**核心功能**:
- 个性化布局：支持筛选、排序、分组、看板和表格视图。
- 自定义对象和字段：灵活定义数据模型。
- 权限管理：通过自定义角色创建和管理权限。
- 工作流自动化：支持触发器和动作实现流程自动化。
- 集成功能：支持邮件、日历事件、文件等。

**技术亮点**: 基于 TypeScript 开发，支持自托管和本地部署，注重现代用户体验设计。

---
## 9. [datalab-to/chandra](https://github.com/datalab-to/chandra)
- **语言**: Python
- **Stars**: 6,199
- **简介**: OCR model that handles complex tables, forms, handwriting with full layout.

### AI 总结
**简介**: Chandra OCR 2 是一个先进的OCR模型，能将图像和PDF转换为保留完整布局信息的结构化HTML、Markdown或JSON，并擅长处理复杂表格、表单、手写体和多语言文档。

**核心功能**:
- 将文档转换为带详细布局信息的Markdown、HTML或JSON格式。
- 支持90多种语言的OCR，在手写体、表格、数学公式和复杂布局方面表现优异。
- 准确重建表单（包括复选框），并能提取图像、图表并添加标题和结构化数据。
- 提供两种推理模式：本地（HuggingFace）和远程（vLLM服务器）。

**技术亮点**: 模型在公开的olmocr基准测试中表现领先，并在多语言基准测试中取得显著提升；提供轻量级的vLLM部署方式和便捷的CLI工具链。

---
