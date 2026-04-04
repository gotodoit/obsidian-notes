---
tags:
  - github-trending
  - daily
date: 2026-04-04
created: 2026-04-04T01:55:46.919Z
---

# 2026-04-04 GitHub Trending Top 7

## 1. [Yeachan-Heo/oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex)
- **语言**: TypeScript
- **Stars**: 14,181
- **简介**: OmX - Oh My codeX: Your codex is not alone. Add hooks, agent teams, HUDs, and so much more.

### AI 总结
**简介**: oh-my-codex (OMX) 是一个为 OpenAI Codex CLI 构建的工作流增强层，旨在通过提供预设的智能体、技能和持久化状态管理，来提升 Codex 的开发体验和效率。

**核心功能**:
- 提供标准化的核心工作流，包含 `$deep-interview`（澄清需求）、`$ralplan`（制定计划）、`$team`（团队并行执行）和 `$ralph`（持续完成）等关键技能。
- 支持通过 `.omx/` 目录持久化存储项目指导、计划、日志和运行状态。
- 允许用户通过 `AGENTS.md` 文件定义项目范围内的智能体角色和指导。

**技术亮点**: 基于 TypeScript 开发，作为 Node.js (>=20) 的 npm 包运行，与 OpenAI Codex CLI 深度集成，并支持在 macOS/Linux (`tmux`) 和 Windows (`psmux`) 上实现持久的团队运行模式。

---
## 2. [onyx-dot-app/onyx](https://github.com/onyx-dot-app/onyx)
- **语言**: Python
- **Stars**: 23,320
- **简介**: Open Source AI Platform - AI Chat with advanced features that works with every LLM

### AI 总结
**简介**: Onyx 是一个开源的 AI 平台，作为大语言模型（LLM）的应用层，提供了一个功能丰富的界面，支持与所有主流 LLM 配合使用。

**核心功能**:
- **智能检索与生成**：提供基于混合索引和AI代理的增强检索生成（RAG）、深度研究、网络搜索、代码执行和文件生成。
- **自定义与集成**：支持构建具有独特指令、知识和行动的自定义AI代理，并通过超过50个开箱即用的连接器或MCP与外部应用交互。
- **多模态交互**：具备语音聊天、图像生成以及可下载文档/图形等多样化输出能力。

**技术亮点**:
- **灵活部署**：支持标准版和轻量版（Lite）两种部署模式，可通过Docker、Kubernetes、Helm/Terraform快速部署。
- **广泛兼容**：支持所有主流LLM提供商，包括自托管方案（如Ollama, vLLM）和商业API（如OpenAI, Anthropic）。
- **企业级特性**：内置单点登录（SSO）、基于角色的访问控制（RBAC）和团队协作功能。

---
## 3. [google-research/timesfm](https://github.com/google-research/timesfm)
- **语言**: Python
- **Stars**: 14,142
- **简介**: TimesFM (Time Series Foundation Model) is a pretrained time-series foundation model developed by Google Research for time-series forecasting.

### AI 总结
**简介**: TimesFM 是 Google Research 开发的一个预训练时间序列基础模型，专注于时间序列预测任务。

**核心功能**:
- 提供预训练的时间序列预测基础模型，支持单变量预测。
- 支持连续分位数预测，可输出均值及多个分位数（如10th至90th）的预测结果。
- 支持通过协变量（XReg）进行预测。
- 提供 PyTorch 和 Flax (JAX) 两种后端实现，以适应不同的硬件加速需求。

**技术亮点**:
- **模型架构**: 采用仅解码器（decoder-only）的 Transformer 架构。
- **模型版本**: 最新版本 TimesFM 2.5 参数量为 2 亿，支持长达 16k 的上下文长度和最高 1k 的预测步长。
- **部署集成**: 模型已集成至 Google BigQuery，可作为官方产品使用，同时也在 Hugging Face 上提供模型权重。

---
## 4. [siddharthvaddem/openscreen](https://github.com/siddharthvaddem/openscreen)
- **语言**: TypeScript
- **Stars**: 18,238
- **简介**: Create stunning demos for free. Open-source, no subscriptions, no watermarks, and free for commercial use. An alternative to Screen Studio.

### AI 总结
**简介**: OpenScreen 是一款免费、开源的屏幕录制与演示制作工具，可作为 Screen Studio 的轻量级替代品，用于创建美观的产品演示和操作教程。

**核心功能**:
- 录制全屏或特定窗口
- 添加自动或手动缩放（可自定义深度）
- 录制麦克风和系统音频
- 自定义缩放时长与位置
- 裁剪视频、添加背景（壁纸、纯色、渐变或自定义）
- 添加动态模糊、注释（文本、箭头、图像）
- 剪辑片段、自定义不同片段的速度
- 支持多种宽高比和分辨率导出

**技术亮点**: 基于 Electron、React、TypeScript、Vite、PixiJS 和 dnd-timeline 构建。

---
## 5. [dmtrKovalenko/fff.nvim](https://github.com/dmtrKovalenko/fff.nvim)
- **语言**: Rust
- **Stars**: 3,273
- **简介**: The fastest and the most accurate file search toolkit for AI agents, Neovim, Rust, C, and NodeJS

### AI 总结
**简介**: FFF.nvim 是一个专为 AI 智能体和 Neovim 设计的、注重性能和搜索准确性的极速模糊文件搜索工具包。

**核心功能**:
- **快速文件搜索**: 提供模糊文件匹配、全局搜索和多文件搜索功能，在大型代码库（如 Linux 内核）中表现优异。
- **AI 智能体集成**: 通过 MCP 协议为 AI 助手（如 Claude Code）提供内置“记忆”的文件搜索，减少 token 消耗和往返查询。
- **智能排序**: 搜索结果根据使用频率、Git 状态、文件大小、定义匹配等多种因素进行智能排序，提升准确性。

**技术亮点**: 使用 Rust 语言开发，通过预构建二进制文件或源码编译方式安装，强调极致的搜索性能和强大的容错（拼写错误容忍）体验。

---
## 6. [f/prompts.chat](https://github.com/f/prompts.chat)
- **语言**: HTML
- **Stars**: 157,198
- **简介**: f.k.a. Awesome ChatGPT Prompts. Share, discover, and collect prompts from the community. Free and open source — self-host for your organization with complete privacy.

### AI 总结
**简介**: 一个名为 prompts.chat 的开源项目，前身为 Awesome ChatGPT Prompts，是全球最大的开源 AI 提示词库，支持 ChatGPT、Claude、Gemini 等多种 AI 模型。

**核心功能**:
- 提供海量精选的 AI 提示词示例，供社区浏览、发现和收集。
- 支持私有化部署，可为组织提供完全私有的、可自定义品牌和主题的提示词库。
- 包含交互式提示工程指南和面向儿童的互动游戏化学习内容。

**技术亮点**: 项目本身为 HTML 项目，提供便捷的部署方式（如 `npx` 快速启动、Docker 部署），并支持与 GitHub、Google、Azure AD 等平台集成进行身份验证。

---
## 7. [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock)
- **语言**: Python
- **Stars**: 78,540
- **简介**: Hunt down social media accounts by username across social networks

### AI 总结
**简介**: 一个用于通过用户名在多个社交网络上查找对应账户的 Python 工具。

**核心功能**:
- 支持在数百个社交网站中搜索指定用户名。
- 提供命令行界面，可同时查询多个用户名。
- 支持将搜索结果保存为 JSON、CSV 等格式的文件。

**技术亮点**: 使用 Python 编写，通过异步请求提高搜索速度，并支持代理配置以绕过访问限制。

---
