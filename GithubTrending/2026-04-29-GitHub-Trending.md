---
tags:
  - github-trending
  - daily
date: 2026-04-29
created: 2026-04-29T01:55:43.934Z
---

# 2026-04-29 GitHub Trending Top 10

## 1. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 37,731
- **简介**: Skills for Real Engineers. Straight from my .claude directory.

### AI 总结
**简介**: 一套由资深工程师设计的、可组合、易适配的 AI 代理技能集，旨在解决实际工程开发中的常见问题，而非“氛围编程”。

**核心功能**:
- **需求对齐**: 提供 `/grill-me` 和 `/grill-with-docs` 技能，通过“盘问”环节让 AI 代理在动手前深入理解你的需求，消除沟通偏差。
- **建立共享语言**: 通过 `/grill-with-docs` 技能，引导你与 AI 共同创建项目的共享语言文档（如 `CONTEXT.md`），减少冗余表述，让代码命名和沟通更精准。
- **快速集成**: 提供一键安装脚本 (`npx skills@latest add`)，可选择性安装技能并运行 `/setup-matt-pocock-skills` 完成配置（如选择问题跟踪器、标签和文档存储位置）。

**技术亮点**: 技能设计遵循“小而精、易适配、可组合”原则，基于 Shell 脚本实现，与 Claude Code、Codex 等主流编码代理兼容。

---
## 2. [abhigyanpatwari/GitNexus](https://github.com/abhigyanpatwari/GitNexus)
- **语言**: TypeScript
- **Stars**: 32,678
- **简介**: GitNexus: The Zero-Server Code Intelligence Engine - GitNexus is a client-side knowledge graph creator that runs entirely in your browser. Drop in a GitHub repo or ZIP file, and get an interactive knowledge graph wit a built in Graph RAG Agent. Perfect for code exploration

### AI 总结
**简介**: GitNexus 是一个完全在浏览器中运行的零服务器代码智能引擎，可将 GitHub 仓库或 ZIP 文件转换为交互式知识图谱，并内置 Graph RAG 代理，助力代码探索与分析。

**核心功能**:
- **知识图谱生成**: 将任意代码库索引为知识图谱，追踪依赖、调用链、集群和执行流等所有关系。
- **Web UI 交互式分析**: 通过浏览器可视化图谱并直接与代码对话，适合快速探索和演示。
- **CLI + MCP 集成**: 本地索引仓库，通过 MCP 协议连接 Cursor、Claude Code 等 AI 代理，提供深度架构视图，提升代码编辑可靠性。
- **隐私与本地运行**: 所有处理在浏览器或本地完成，无需服务器，确保数据安全。

**技术亮点**: 基于 TypeScript 开发，使用 Tree-sitter 进行代码解析（支持 WASM 和原生绑定），LadybugDB 作为存储引擎（支持 WASM 内存模式和原生持久化），通过 MCP 协议与主流 AI 工具无缝集成；提供企业版（SaaS/自托管），支持多仓库、自动重索引和 PR 评审等高级功能。

---
## 3. [ComposioHQ/awesome-codex-skills](https://github.com/ComposioHQ/awesome-codex-skills)
- **语言**: Python
- **Stars**: 4,044
- **简介**: A curated list of practical Codex skills for automating workflows across the Codex CLI and API.

### AI 总结
**简介**: 这是一个精选的实用 Codex 技能合集，旨在通过 Codex CLI 和 API 自动化工作流程。

**核心功能**:
- 提供即装即用的 Codex 技能安装器，可快速将技能部署到 Codex 环境中。
- 涵盖开发工具、生产力协作、通信写作、数据分析及元工具等多个类别。
- 支持通过描述触发技能，实现邮件发送、问题创建、Slack 消息发布等超过 1000 个应用的自动化操作。

**技术亮点**: 使用 Python 开发的模块化技能安装脚本，技能以标准化 `SKILL.md` 格式组织，包含元数据，便于 Codex 自动识别和按需加载。

---
## 4. [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice)
- **语言**: Python
- **Stars**: 44,876
- **简介**: Open-Source Frontier Voice AI

### AI 总结
**简介**: VibeVoice 是微软开源的前沿语音 AI 模型系列，包含文本转语音（TTS）和自动语音识别（ASR）模型，支持长音频、多语言和实时处理。

**核心功能**:
- **VibeVoice-ASR**: 统一语音转文本模型，可处理长达 60 分钟的音频，生成包含说话人、时间戳和内容的转录，支持 50+ 语言和用户自定义上下文。
- **VibeVoice-TTS**: 长文本多说话人语音合成模型，支持生成最长 90 分钟、最多 4 个不同说话人的语音。
- **VibeVoice-Realtime-0.5B**: 实时文本转语音模型，支持流式文本输入和鲁棒的长语音生成，提供多语言和多种英语风格语音。

**技术亮点**: 采用超低帧率（7.5 Hz）的连续语音分词器（声学和语义），结合大语言模型（LLM）和扩散头（Diffusion Head）的“下一 token 扩散”框架，在保持音频保真度的同时提升长序列处理的计算效率。

---
## 5. [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates)
- **语言**: Python
- **Stars**: 26,174
- **简介**: CLI tool for configuring and monitoring Claude Code

### AI 总结
**简介**: 一个为 Anthropic 的 Claude Code 提供开箱即用配置、AI 代理、自定义命令和外部集成的 CLI 工具和模板库，帮助开发者快速增强开发工作流。

**核心功能**:
- **组件安装**: 通过 `npx claude-code-templates@latest` 命令行交互式安装或指定参数安装 AI 代理、自定义命令、MCP 集成、设置、钩子和技能。
- **模板浏览**: 提供 [aitmpl.com](https://aitmpl.com) 网页界面，可浏览和安装 100+ 预置组件。
- **开发工具**: 包含 Claude Code Analytics 等额外工具，用于实时监控 AI 驱动的开发会话和性能指标。

**技术亮点**: 基于 Python 开发，提供 npm 包分发，支持通过命令行参数一键安装完整开发栈（如 `--agent --command --mcp`），并集成了 GitHub、PostgreSQL、Stripe、AWS 等外部服务（MCPs）。

---
## 6. [HunxByts/GhostTrack](https://github.com/HunxByts/GhostTrack)
- **语言**: Python
- **Stars**: 10,669
- **简介**: Useful tool to track location or mobile number

### AI 总结
**简介**: GhostTrack 是一个用于追踪位置或手机号码的 OSINT 信息收集工具。
**核心功能**:
- IP 追踪：可获取目标 IP 地址相关信息，支持与 Seeker 工具联动获取目标 IP。
- 手机号追踪：查询目标手机号码的关联信息。
- 用户名追踪：搜索目标用户在社交媒体上的信息。
**技术亮点**: 基于 Python 开发，支持 Linux 和 Termux 环境，通过命令行交互操作。

---
## 7. [fspecii/ace-step-ui](https://github.com/fspecii/ace-step-ui)
- **语言**: JavaScript
- **Stars**: 1,723
- **简介**: 🎵 The Ultimate Open Source Suno Alternative - Professional UI for ACE-Step 1.5 AI Music Generation. Free, local, unlimited. Stop paying for Suno!

### AI 总结
**简介**: ACE-Step UI 是一款开源的、本地运行的 AI 音乐生成工具，提供媲美 Suno 的专业级界面，完全免费且无使用限制。

**核心功能**:
- **完整歌曲生成**: 支持生成最长 4 分钟以上、带人声和歌词的完整歌曲
- **多种生成模式**: 提供纯器乐、自定义（BPM/调性/拍号）、批量生成和 AI 增强模式
- **高级参数控制**: 支持参考音频、音频翻唱、局部重绘、随机种子和推理步骤调节
- **歌词与提示词编辑器**: 内置歌词编辑器、AI 格式助手和预设提示词模板
- **专业音乐管理界面**: 类 Spotify 界面，包含底部播放器、曲库管理、点赞和播放列表功能

**技术亮点**: 基于 React 18、TypeScript 5 和 TailwindCSS 构建，采用 SQLite 实现本地优先存储，支持 LAN 网络共享，完全离线运行确保隐私安全。

---
## 8. [public-apis/public-apis](https://github.com/public-apis/public-apis)
- **语言**: Python
- **Stars**: 428,213
- **简介**: A collective list of free APIs

### AI 总结
**简介**: 一个由社区维护的免费公共 API 集合列表，涵盖多个领域，供开发者用于产品开发。

**核心功能**:
- 提供来自多个领域的免费公共 API 列表
- 由社区成员和 APILayer 团队共同维护和更新
- 包含可直接在 Postman 中运行的 API 示例

**技术亮点**: 使用 Python 语言，通过 Markdown 表格形式组织 API 数据，并集成 Postman 按钮实现一键调用演示。

---
## 9. [CJackHwang/ds2api](https://github.com/CJackHwang/ds2api)
- **语言**: Go
- **Stars**: 2,356
- **简介**: Deepseek to API: A lightweight, high-performance full-stack middleware converting client protocols to universal APIs. Supports multi-account rotation, compiled binaries, Vercel Serverless, and Docker. Compatible with Google, Claude, and OpenAI API formats.

### AI 总结
**简介**: 一个轻量高性能的全栈中间件，用于将客户端协议转换为通用API，支持多账户轮转、编译二进制、Vercel Serverless和Docker部署。

**核心功能**:
- 多账户自动轮转，提升API调用稳定性
- 兼容Google、Claude、OpenAI等主流API格式
- 支持编译二进制、Vercel Serverless和Docker多种部署方式
- 高性能协议转换，降低客户端接入成本

**技术亮点**: 使用Go语言开发，提供全栈中间件架构，支持多平台部署（二进制/Vercel/Docker），实现协议统一转换。

---
## 10. [Alishahryar1/free-claude-code](https://github.com/Alishahryar1/free-claude-code)
- **语言**: Python
- **Stars**: 17,562
- **简介**: Use claude-code for free in the terminal, VSCode extension or via discord like openclaw

### AI 总结
**简介**: 免费使用 Claude Code CLI、VS Code 扩展或 Discord 等客户端的代理工具，可将 Claude Code 的 Anthropic API 流量路由到免费的第三方或本地模型。

**核心功能**:
- 将 Claude Code 的 API 调用透明代理到 NVIDIA NIM、OpenRouter、DeepSeek、LM Studio、llama.cpp 或 Ollama 等后端
- 支持按模型层级（Opus、Sonnet、Haiku）分别路由到不同提供商
- 支持流式传输、工具调用、推理/思考块处理及本地请求优化
- 可选 Discord 或 Telegram 机器人包装，实现远程编码会话
- 可选通过本地 Whisper 或 NVIDIA NIM 进行语音笔记转录

**技术亮点**: 使用 Python 3.14、uv 包管理、FastAPI/Uvicorn 构建；采用 OpenAI 聊天翻译或 Anthropic Messages 协议与后端通信；支持多提供商动态路由和模型映射。

---
