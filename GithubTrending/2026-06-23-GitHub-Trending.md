---
tags:
  - github-trending
  - daily
date: 2026-06-23
created: 2026-06-23T01:55:43.980Z
---

# 2026-06-23 GitHub Trending Top 10

## 1. [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)
- **语言**: Python
- **Stars**: 12,256
- **简介**: World's first open-source, agentic video production system. 12 pipelines, 52 tools, 500+ agent skills. Turn your AI coding assistant into a full video production studio.

### AI 总结
**简介**: OpenMontage 是全球首个开源、智能体驱动的视频制作系统，可将 AI 编程助手转变为完整的视频制作工作室。

**核心功能**:
- 支持通过自然语言描述，由智能体自动完成研究、脚本编写、素材生成、剪辑和最终合成
- 提供12条视频制作管道、52种工具和500+智能体技能，覆盖从图像到真实视频的多种工作流
- 支持免费/开源工作流，可从免费素材库和开放档案构建真实视频，而非仅生成动画图像
- 集成多种AI模型（如Veo、Kling、FLUX、OpenAI等），实现低成本高质量视频制作（示例成本低至$0.15-$1.33）

**技术亮点**:
- 基于Python开发，采用Remotion动画引擎实现高级视频合成
- 支持多模型集成（视频生成、图像生成、TTS、字幕识别等），实现全流程自动化
- 采用智能体架构，支持通过API密钥快速接入不同AI服务提供商

---
## 2. [palmier-io/palmier-pro](https://github.com/palmier-io/palmier-pro)
- **语言**: Swift
- **Stars**: 7,451
- **简介**: macOS video editor built for AI

### AI 总结
**简介**: Palmier Pro 是一款专为 AI 打造的 macOS 开源视频编辑器，支持在时间线中与 AI 智能体协同生成和编辑视频。

**核心功能**:
- **Swift 原生视频编辑**：从零构建的 macOS 视频编辑器，对标 Premiere Pro，并深度集成 AI 工作流。
- **内置生成式 AI**：支持 Seedance、Kling、Nano Banana Pro 等模型，在时间线内直接生成视频和图像。
- **智能体集成**：通过 MCP 服务器连接 Claude/Codex/Cursor 等 AI 智能体，或使用内置智能体协同编辑项目。

**技术亮点**: 使用 Swift 原生开发，支持 MCP 协议（通过 HTTP 暴露接口），生成式 AI 处理部分为闭源，编辑器核心功能完全开源。

---
## 3. [jamiepine/voicebox](https://github.com/jamiepine/voicebox)
- **语言**: TypeScript
- **Stars**: 32,313
- **简介**: The open-source AI voice studio. Clone, dictate, create.

### AI 总结
**简介**: Voicebox 是一个本地优先的开源 AI 语音工作室，集语音克隆、文本转语音、语音输入和 AI 代理语音输出于一体，完全在本地运行。

**核心功能**:
- **语音克隆与生成**: 从几秒音频中零样本克隆声音，支持 7 种 TTS 引擎、23 种语言，并包含 50+ 预设音色。
- **语音输入与听写**: 通过全局热键进行听写（支持按键说话或切换模式），在 macOS 上支持自动粘贴，应用内每个文本字段都有麦克风按钮。
- **AI 代理语音输出**: 通过单一工具调用 (`voicebox.speak`)，任何支持 MCP 的 AI 代理（如 Claude Code、Cursor）都能用你克隆的声音说话。
- **语音个性与后期处理**: 为声音配置添加自由形式的角色描述，通过本地 LLM 进行撰写、重写或回复；支持音高、混响、延迟等后期效果。
- **故事编辑器**: 多轨时间线，用于创建对话、播客和叙事内容。

**技术亮点**: 基于 Tauri (Rust) 构建，提供原生性能；支持 macOS (MLX/Metal)、Windows (CUDA)、Linux (AMD ROCm, Intel Arc) 及 Docker 部署；提供 REST API 和内置 MCP 服务器。

---
## 4. [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills)
- **语言**: Python
- **Stars**: 18,755
- **简介**: 817 structured cybersecurity skills for AI agents · Mapped to 6 frameworks: MITRE ATT&CK, NIST CSF 2.0, MITRE ATLAS, D3FEND, NIST AI RMF & MITRE F3 (Fight Fraud) · agentskills.io standard · Works with Claude Code, GitHub Copilot, Codex CLI, Cursor, Gemini CLI & 20+ platforms · 29 security domains · Apache 2.0

### AI 总结
**简介**: 为AI代理提供817个结构化网络安全技能的顶级开源库，覆盖29个安全领域，并映射至6个行业框架。

**核心功能**:
- 提供817个生产级网络安全技能，涵盖29个安全领域
- 每个技能均映射至MITRE ATT&CK、NIST CSF 2.0、MITRE ATLAS、D3FEND、NIST AI RMF和MITRE F3六大框架
- 支持Claude Code、GitHub Copilot、Codex CLI、Cursor、Gemini CLI等26+个AI平台
- 遵循agentskills.io开放标准，具备跨框架统一覆盖能力

**技术亮点**: 采用Python开发，基于agentskills.io标准，实现单一技能同时满足多个框架合规要求，为AI代理提供专家级安全分析指导。

---
## 5. [penpot/penpot](https://github.com/penpot/penpot)
- **语言**: Clojure
- **Stars**: 52,898
- **简介**: Penpot: The open-source design tool for design and code collaboration

### AI 总结
**简介**: Penpot 是一款开源的设计平台，旨在促进设计与代码的协作，让团队完全掌控设计基础设施。

**核心功能**:
- 支持 SVG、CSS、HTML 和 JSON 等开放标准，可直接在浏览器中使用或自托管部署。
- 实时协作，帮助团队扩展设计规模，并将设计更贴近产品开发。
- 原生设计令牌（Design Tokens）提供设计与开发之间的单一事实来源，确保一致性。
- 通过 MCP 服务器实现设计与代码之间的多向工作流。
- 提供强大的开放 API 和插件系统，支持自动化、AI 驱动的工作流和集成。
- 支持 CSS Grid 和 Flex 布局，帮助设计响应式界面。

**技术亮点**: 基于 Clojure 构建，采用自托管、开源架构，强调代码化设计表达，支持插件和 MCP 服务器。

---
## 6. [Stirling-Tools/Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF)
- **语言**: TypeScript
- **Stars**: 82,978
- **简介**: #1 PDF Application on GitHub that lets you edit PDFs on any device anywhere

### AI 总结
**简介**: Stirling PDF 是一个功能强大的开源 PDF 处理平台，支持在桌面、浏览器或自托管服务器上编辑、转换、自动化处理 PDF，无需将文档发送至外部服务。

**核心功能**:
- **50+ PDF 工具**: 提供编辑、合并、拆分、签名、编辑、转换、OCR、压缩等丰富功能。
- **自动化与工作流**: 支持在 UI 中通过无代码管道和 API 处理大量 PDF。
- **企业级特性**: 支持 SSO、审计日志和灵活的本地部署。
- **开发者平台**: 提供 REST API 集成几乎所有工具。
- **多语言界面**: 支持 40+ 种语言。

**技术亮点**: 基于 TypeScript 开发，支持 Docker 快速部署（`docker run -p 8080:8080 docker.stirlingpdf.com/stirlingtools/stirling-pdf`），采用开放核心（open-core）许可模式。

---
## 7. [garrytan/gstack](https://github.com/garrytan/gstack)
- **语言**: TypeScript
- **Stars**: 113,191
- **简介**: Use Garry Tan's exact Claude Code setup: 23 opinionated tools that serve as CEO, Designer, Eng Manager, Release Manager, Doc Engineer, and QA

### AI 总结
**简介**: Garry Tan 的开源“软件工厂”，将 Claude Code 转化为一个包含 CEO、设计师、工程经理等 23 种角色的虚拟工程团队，让单人开发者具备团队的交付能力。

**核心功能**:
- **多角色协作指令集**: 提供 23 个专家角色（如 `/office-hours`、`/plan-ceo-review`、`/review`、`/qa`、`/ship`），覆盖从产品构思、设计评审、代码审查到发布部署的全流程。
- **自动化工作流**: 包括自动规划、安全审计、设计回归、金丝雀发布、性能基准测试等 8 个高级工具，将复杂工程流程指令化。
- **零配置集成**: 通过一条命令即可安装，自动将工具集注入到 Claude Code 的 CLAUDE.md 中，支持团队共享。

**技术亮点**: 基于 TypeScript 开发，依赖 Claude Code、Bun、Node.js 和 Git；所有工具均为 Markdown 驱动的斜杠命令，采用 MIT 开源协议。

---
## 8. [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes)
- **语言**: TypeScript
- **Stars**: 30,046
- **简介**: Write HTML. Render video. Built for agents.

### AI 总结
**简介**: HyperFrames 是一个开源框架，用于将 HTML、CSS、媒体和可搜索动画转换为确定性 MP4 视频。

**核心功能**:
- 支持通过 AI 编码代理或 CLI 创建视频，提供“技能”系统指导代理完成规划、编写、渲染等流程。
- 提供 `frame.md` 设计系统，将品牌设计规范适配为视频帧，便于 AI 代理生成一致风格。
- 包含预览、渲染、资源目录、展示案例等工具链。

**技术亮点**: 基于 TypeScript 开发，要求 Node.js 22+ 和 FFmpeg。

---
## 9. [tursodatabase/turso](https://github.com/tursodatabase/turso)
- **语言**: Rust
- **Stars**: 21,508
- **简介**: Turso is an in-process SQL database, compatible with SQLite.

### AI 总结
**简介**: Turso 是一个用 Rust 编写的、与 SQLite 兼容的进程内 SQL 数据库。

**核心功能**:
- **SQLite 兼容**: 兼容 SQLite 的 SQL 方言、文件格式和 C API。
- **高写入吞吐**: 通过多版本并发控制（MVCC）提供 `BEGIN CONCURRENT` 特性。
- **变更数据捕获（CDC）**: 支持实时追踪数据库变更。
- **多语言绑定**: 提供 Go、JavaScript、Java、.NET、Python、Rust 和 WebAssembly 等语言的客户端库。
- **向量支持**: 支持精确搜索和向量操作。
- **改进的模式管理**: 支持扩展的 `ALTER` 语句和更快的模式变更。
- **跨平台**: 支持 Linux、macOS、Windows 以及通过 WebAssembly 支持浏览器。

**技术亮点**: 使用 Rust 编写，支持 Linux 上的异步 I/O (`io_uring`)，并包含多项实验性功能（如静态加密、基于 DBSP 的增量计算、基于 Tantivy 的全文搜索、多进程 WAL 协调）。

---
## 10. [bytedance/deer-flow](https://github.com/bytedance/deer-flow)
- **语言**: Python
- **Stars**: 73,301
- **简介**: An open-source long-horizon SuperAgent harness that researches, codes, and creates. With the help of sandboxes, memories, tools, skill, subagents and message gateway, it handles different levels of tasks that could take minutes to hours.

### AI 总结
**简介**: DeerFlow 是一个开源的超智能体（SuperAgent）编排框架，通过子智能体、记忆、沙箱和可扩展技能，能够处理从几分钟到几小时的长周期复杂任务。

**核心功能**:
- **子智能体编排**：支持创建和管理多个子智能体协同完成复杂任务。
- **技能与工具扩展**：提供可扩展的技能和工具系统，包括 Claude Code 集成。
- **沙箱与文件系统**：提供安全的沙箱环境，支持文件操作和代码执行。
- **上下文工程**：优化上下文管理，提升长任务处理效率。
- **长期记忆**：支持持久化记忆，实现跨会话的知识积累。
- **MCP 服务器与 IM 通道**：支持消息通信协议和即时通讯通道集成。

**技术亮点**:
- 基于 Python 3.12+ 和 Node.js 22+ 构建
- 支持 Docker 一键部署，提供本地开发和容器化两种运行模式
- 集成 LangSmith 和 Langfuse 追踪能力
- 推荐配合豆包 Seed-2.0-Code、DeepSeek v3.2 等大模型使用
- 支持 InfoQuest 智能搜索工具集

---
