---
tags:
  - github-trending
  - daily
date: 2026-07-16
created: 2026-07-16T01:55:43.769Z
---

# 2026-07-16 GitHub Trending Top 10

## 1. [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut)
- **语言**: TypeScript
- **Stars**: 71,885
- **简介**: The open-source CapCut alternative

### AI 总结
**简介**: OpenCut 是一款免费开源的视频编辑器，支持 Web、桌面和移动端，旨在成为 CapCut 的替代品。

**核心功能**:
- 编辑器 API
- 一流的第三方插件支持（基于插件优先架构）
- 跨平台支持：桌面、移动端和浏览器（基于 Rust 核心）
- MCP 服务器（用于 AI 代理）
- 无头模式（自动化、批量渲染）
- 编辑器内脚本面板

**技术亮点**: 使用 TypeScript 开发，核心基于 Rust，支持从单一代码库构建多平台应用。

---
## 2. [Nutlope/hallmark](https://github.com/Nutlope/hallmark)
- **语言**: CSS
- **Stars**: 8,634
- **简介**: Anti-AI-slop design skill for Claude Code, Cursor, and Codex.

### AI 总结
**简介**: Hallmark 是一个为 Claude Code、Cursor 和 Codex 设计的设计技能，旨在生成不像是 AI 生成的独特 UI。

**核心功能**:
- **生成 UI**: 默认模式下，为给定需求选择宏观结构、应用 20 种主题之一，并通过 57 个“抄袭检测”门控和输出前自我批评，拒绝 LLM 常见的输出。
- **审计**: `hallmark audit <target>` 命令，对现有代码进行反模式评分，仅生成问题列表，不修改代码。
- **重新设计**: `hallmark redesign <target>` 命令，保留内容和品牌，但丢弃原有结构，用不同的设计指纹重建。
- **学习**: `hallmark study <screenshot | URL>` 命令，从用户欣赏的设计中提取“DNA”（宏观结构、字体搭配、色彩锚点），并可选输出可移植的 `design.md` 文件。

**技术亮点**: 基于 CSS，通过 57 个门控逻辑和自批评机制，确保每次生成的设计在结构、主题和细节上都独一无二，避免了模板化的 AI 痕迹。

---
## 3. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 172,364
- **简介**: Skills for Real Engineers. Straight from my .claude directory.

### AI 总结
**简介**: 这是 Matt Pocock 分享的一套工程技能集合，旨在通过小型、可组合、易定制的 AI 代理技能，帮助开发者解决编码代理中的常见问题，实现真正的工程开发而非“氛围编码”。

**核心功能**:
- **快速安装与设置**：通过 `npx skills@latest add mattpocock/skills` 命令，可快速将所需技能安装到编码代理中，并自动配置问题追踪器（GitHub/Linear/本地文件）、标签和文档存储。
- **对齐需求 (`/grill-me`, `/grill-with-docs`)**：在开始编码前，通过详细提问来对齐用户与代理之间的需求，避免“代理没理解我想要什么”的常见失败模式。
- **Claude Code 插件支持**：提供原生插件安装方式，可将整个技能集作为只读、自动更新的托管包安装到 Claude Code 中，无需手动维护。
- **技能可组合与可定制**：所有技能设计为小型、易于修改，支持按需选择并自由组合，适配任何模型。

**技术亮点**: 基于 Shell 实现，使用 `skills.sh` 安装器或 Claude Code 插件两种安装哲学（可编辑 vs 只读更新）；技能设计遵循工程经验，强调小型化、可组合性和用户控制权。

---
## 4. [moeru-ai/airi](https://github.com/moeru-ai/airi)
- **语言**: TypeScript
- **Stars**: 42,530
- **简介**: 💖🧸 Self hosted, you-owned Grok Companion, a container of souls of waifu, cyber livings to bring them into our worlds, wishing to achieve Neuro-sama's altitude. Capable of realtime voice chat, Minecraft, Factorio playing. Web / macOS / Windows supported.

### AI 总结
**简介**: 一个自托管的、类 Neuro-sama 的 AI 伴侣项目，旨在将虚拟角色带入现实世界，支持实时语音聊天、游戏互动等功能。

**核心功能**:
- 实时语音聊天
- 支持 Minecraft、Factorio 等游戏互动
- 提供 Web、macOS、Windows 客户端

**技术亮点**: 使用 TypeScript 开发，支持自托管部署，跨平台兼容。

---
## 5. [Dicklesworthstone/destructive_command_guard](https://github.com/Dicklesworthstone/destructive_command_guard)
- **语言**: Rust
- **Stars**: 4,784
- **简介**: The Destructive Command Guard (dcg) is for blocking dangerous git and shell commands from being executed by agents.

### AI 总结
**简介**: 一个高性能的 AI 编码代理命令拦截钩子，在执行前阻止破坏性命令，保护你的工作免受意外删除。

**核心功能**:
- **零配置保护**: 开箱即用，自动拦截危险的 git 和文件系统命令。
- **50+ 安全包**: 支持数据库、Kubernetes、Docker、AWS/GCP/Azure、Terraform 等。
- **子毫秒级延迟**: 采用 SIMD 加速过滤，几乎无感知。
- **Heredoc/内联脚本扫描**: 能检测并阻止 `python -c "os.remove(...)"` 等嵌入的破坏性脚本。
- **智能上下文检测**: 能区分 `grep "rm -rf"`（数据）和 `rm -rf /`（执行），避免误伤。
- **丰富的终端输出**: 在 stderr 上输出人性化的拒绝面板、规则上下文和建议。
- **代理安全流**: 机器可读的钩子输出保留在 stdout，而丰富的 UI 信息保留在 stderr。

**技术亮点**: 使用 Rust 编写，具备 SIMD 加速能力，支持 Linux、macOS 和 Windows (WSL/原生)，并可与 Claude Code、Codex CLI、Gemini CLI、Copilot CLI、Cursor 等多种 AI 代理工具集成。

---
## 6. [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading)
- **语言**: Python
- **Stars**: 23,738
- **简介**: "Vibe-Trading: Your Personal Trading Agent"

### AI 总结
**简介**: Vibe-Trading 是一个基于 Python 的个人交易智能体，通过一条命令即可赋予用户全面的交易能力。

**核心功能**:
- 提供个人交易智能体，支持自动化交易策略
- 支持回测正确性与投资组合工作室，确保因果关系和顺序无关性
- 集成多种市场数据源（如 Longbridge、Tushare 等），支持历史数据回退层
- 支持 MCP 服务器（Streamable HTTP），提供现代传输协议
- 提供 Web 设置界面和 CLI 引导，支持 NVIDIA NIM 等一流提供商

**技术亮点**: 使用 Python 3.11+、FastAPI 后端、React 19 前端，支持 PyPI 安装，采用 MIT 开源协议。

---
## 7. [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter)
- **语言**: Rust
- **Stars**: 65,514
- **简介**: A coding agent for low-cost models

### AI 总结
**简介**: Open Interpreter 是一个针对低成本模型优化的编码代理，基于 Rust 开发，是 OpenAI Codex 的分支。

**核心功能**:
- 通过终端与模型交互，支持多种模型提供商和 Rust 原生模型 harness（如 native、claude-code、swe-agent 等）
- 内置 QA 技能，可驱动真实浏览器或原生应用进行界面测试
- 支持原生沙箱隔离（macOS/Linux/Windows），保证安全运行
- 可作为 Agent Client Protocol 代理与编辑器集成

**技术亮点**: 采用 Rust 语言实现高性能 harness 仿真，通过 `/harness` 切换不同模型运行时环境，支持本地配置持久化（`~/.openinterpreter`）及多种扩展机制（exec、MCP、skills、hooks）。

---
## 8. [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)
- **语言**: Python
- **Stars**: 26,301
- **简介**: DeepTutor: Lifelong Personalized Tutoring. https://deeptutor.info/.

### AI 总结
**简介**: DeepTutor 是一个基于 Python 的终身个性化辅导系统，旨在通过 AI 技术提供持续、个性化的学习辅导。

**核心功能**:
- 支持个性化终身学习辅导，根据学习者需求动态调整教学内容
- 提供文档管理功能，支持从知识库中删除单个失败文档（v1.5.1）
- 集成 LlamaIndex 文档解析功能，优化文档处理流程（v1.5.0）
- 提供 CLI 和 Agent 原生接口，便于命令行和自动化操作
- 多语言文档支持（包括中文、英文、日文等12种语言）

**技术亮点**:
- 基于 Python 3.11+ 和 Next.js 16 构建
- 采用 Apache 2.0 开源协议
- 提供详细的在线文档（deeptutor.info）和社区支持（Discord、飞书、微信）
- 主动邀请社区贡献，维护清晰的贡献指南和路线图

---
## 9. [HenryNdubuaku/maths-cs-ai-compendium](https://github.com/HenryNdubuaku/maths-cs-ai-compendium)
- **语言**: TypeScript
- **Stars**: 5,933
- **简介**: Become a cracked AI/ML Research Engineer

### AI 总结
**简介**: 一本面向AI/ML研究工程师的开源、非传统教科书，从零基础讲解数学、计算机科学和人工智能。

**核心功能**:
- 提供从向量、矩阵到深度学习、多模态学习等17个章节的系统化知识体系
- 包含MCP服务器，允许AI助手（如Claude Code、Cursor）将本知识库作为知识库使用
- 涵盖面试准备材料，已有用户凭此通过DeepMind、OpenAI等公司面试

**技术亮点**: 基于TypeScript构建，强调直觉优先、真实世界背景的讲解方式，支持通过GitHub Pages在线阅读。

---
## 10. [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)
- **语言**: Python
- **Stars**: 121,945
- **简介**: 100+ AI Agent & RAG apps you can actually run — clone, customize, ship.

### AI 总结
**简介**: 一个包含100多个开源AI智能体和RAG应用的仓库，支持克隆、自定义和部署，与Claude、Gemini、GPT等多种模型兼容。

**核心功能**:
- 提供Agent Skills（如项目墓地分析、自我优化技能），可一键添加到编码助手
- 包含入门级AI智能体（如旅行规划、播客生成、医疗影像分析等单文件应用）
- 涵盖高级智能体（如欺诈调查、房屋翻新设计）和语音AI代理（如保险理赔实时处理）
- 支持始终在线的智能体（如自动抓取Hacker News简报）

**技术亮点**: 使用Python开发，支持Streamlit快速部署，提供npx一键安装技能和git克隆运行两种方式，所有技能通过安全与评估CI测试。

---
