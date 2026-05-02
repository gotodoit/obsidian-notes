---
tags:
  - github-trending
  - daily
date: 2026-05-02
created: 2026-05-02T01:55:43.306Z
---

# 2026-05-02 GitHub Trending Top 9

## 1. [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)
- **语言**: Python
- **Stars**: 59,956
- **简介**: TradingAgents: Multi-Agents LLM Financial Trading Framework

### AI 总结
**简介**: TradingAgents 是一个基于多智能体 LLM 的金融交易框架，模拟真实交易公司运作，通过专业代理协作评估市场并制定交易策略。

**核心功能**:
- 部署多个专业 LLM 代理（基本面分析师、情绪专家、技术分析师、交易员、风险管理团队等）进行市场分析
- 代理间动态讨论以确定最优交易策略
- 支持结构化输出代理（研究经理、交易员、投资组合经理）
- 提供背测功能、多语言支持及 Docker 部署

**技术亮点**:
- 基于 LangGraph 实现检查点恢复和持久化决策日志
- 支持多种 LLM 提供商（DeepSeek、Qwen、GLM、Azure、GPT-5.x、Gemini 3.x、Claude 4.x、Grok 4.x 等）
- 统一的模型目录和五级评级量表
- 集成 OpenAI Responses API 和 Anthropic 努力控制
- 跨平台稳定性及 Windows UTF-8 编码修复

---
## 2. [soxoj/maigret](https://github.com/soxoj/maigret)
- **语言**: Python
- **Stars**: 21,702
- **简介**: 🕵️‍♂️ Collect a dossier on a person by username from 3000+ sites

### AI 总结
**简介**: Maigret 是一个基于 Python 的开源工具，仅通过用户名即可在 3000+ 网站上搜索并收集个人档案信息，无需 API 密钥。

**核心功能**:
- 支持 3000+ 网站，默认扫描前 500 个高流量站点，可通过参数扩展至全部或按标签筛选
- 从个人资料页面和网站 API 提取所有可用信息，包括关联账号链接
- 支持递归搜索，利用发现的用户名和其他 ID 进一步挖掘
- 提供 Web 界面，支持结果图形式浏览和多种格式报告下载
- 自动从 GitHub 更新站点数据库，离线时使用内置数据库
- 支持 Tor 和 I2P 网站检查，可部分绕过封锁和验证码

**技术亮点**: 使用 Python 3.10+，可嵌入其他 Python 项目作为库使用，支持标签过滤（按类别和国家）、自动数据库更新与离线回退，被专业 OSINT 工具集成使用。

---
## 3. [warpdotdev/warp](https://github.com/warpdotdev/warp)
- **语言**: Rust
- **Stars**: 51,521
- **简介**: Warp is an agentic development environment, born out of the terminal.

### AI 总结
**简介**: Warp 是一个基于终端的智能开发环境，结合了现代终端与云端智能代理功能。

**核心功能**:
- 提供现代化的终端界面，支持代码编辑和智能提示等特性
- 内置智能代理 Oz，可编排无限数量的并行云端代理，实现自动化任务
- 支持运行 Claude Code、Codex、Gemini CLI 等第三方 CLI 代理
- 提供云端驱动的代理平台，支持可编程、可审计和可操控的并行任务执行

**技术亮点**: 使用 Rust 语言开发，计划开源 Rust UI 框架和客户端代码；依赖 Tokio、Alacritty、NuShell 等高性能开源组件。

---
## 4. [1jehuang/jcode](https://github.com/1jehuang/jcode)
- **语言**: Rust
- **Stars**: 2,379
- **简介**: Coding Agent Harness

### AI 总结
**简介**: jcode 是一个用 Rust 构建的下一代编码智能体工具，旨在提升技能上限，支持多会话工作流、无限可定制性和高性能。

**核心功能**:
- 支持多会话工作流，可同时运行多个编码会话
- 提供无限可定制性，用户可根据需求灵活配置
- 性能优化，资源效率极高，RAM 占用远低于同类工具（如 Claude Code、Cursor Agent 等）

**技术亮点**: 使用 Rust 语言开发，注重内存和启动性能优化；支持本地嵌入关闭选项以进一步降低资源消耗；跨平台支持 Linux、macOS 和 Windows。

---
## 5. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 52,628
- **简介**: Skills for Real Engineers. Straight from my .claude directory.

### AI 总结
**简介**: 一套专为真实工程场景设计的轻量级、可组合的AI Agent技能集，旨在解决编码Agent常见的沟通偏差和冗长问题。

**核心功能**:
- **`/grill-me` 与 `/grill-with-docs` 对齐会话**：通过引导Agent提问，在开发前与开发者深度对齐需求，避免误解。
- **建立共享语言**：通过`/grill-with-docs`技能，自动创建项目术语表（`CONTEXT.md`），让Agent和开发者使用统一的精简语言，减少冗余输出。
- **一键安装与配置**：通过`npx skills@latest add`命令快速安装，并自动配置议题追踪器（GitHub/Linear/本地文件）和文档存储位置。

**技术亮点**: 基于Shell脚本实现，强调“小而精、易适配、可组合”的设计哲学，支持与Claude Code、Codex等主流编码Agent集成。

---
## 6. [browserbase/skills](https://github.com/browserbase/skills)
- **语言**: JavaScript
- **Stars**: 1,198
- **简介**: Claude Agent SDK with a web browsing tool

### AI 总结
**简介**: browserbase/skills 是一个为 Claude Code 提供浏览器自动化与平台管理能力的技能集，基于 JavaScript 实现。

**核心功能**:
- 提供 11 种技能，涵盖浏览器自动化、CLI 工具、无服务器函数部署、调试、搜索、UI 测试等
- 支持远程 Browserbase 会话，具备反机器人隐身、CAPTCHA 解决和住宅代理功能
- 可同步本地 Chrome Cookie 到 Browserbase 持久化上下文，实现已认证站点访问
- 集成 `bb` CLI，管理会话、项目、上下文、扩展、抓取和仪表盘等平台 API 工作流
- 包含 AI 驱动的对抗性 UI 测试，分析 git diff 或探索全应用以发现 bug

**技术亮点**: 基于 Claude Code 插件系统，利用 DevTools 协议追踪、CDP 数据流分桶、无服务器浏览器自动化等技术栈，支持本地与远程浏览器环境无缝切换。

---
## 7. [simstudioai/sim](https://github.com/simstudioai/sim)
- **语言**: TypeScript
- **Stars**: 28,165
- **简介**: Build, deploy, and orchestrate AI agents. Sim is the central intelligence layer for your AI workforce.

### AI 总结
**简介**: Sim 是一个开源平台，用于构建、部署和编排 AI 代理，支持连接 1000+ 集成和 LLM，打造智能工作流。

**核心功能**:
- **可视化工作流构建**: 通过画布直观地设计代理工作流，连接代理、工具和模块，并即时运行。
- **Copilot 增强**: 使用自然语言生成节点、修复错误和迭代流程，提升开发效率。
- **向量数据库集成**: 上传文档到向量存储，让代理基于特定内容进行问答。

**技术亮点**: 基于 TypeScript 开发，支持 Docker 快速部署（包括 Ollama 本地 AI 模型），提供云托管版本，并集成 Discord 和 Twitter 社区支持。

---
## 8. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 175,657
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套为编码代理设计的完整软件开发方法论，基于可组合的技能和初始指令，让代理自动遵循规范工作流程。

**核心功能**:
- **自动化工作流**: 从构思、设计、计划到实施，代理按步骤执行，包括头脑风暴、Git工作树隔离、子代理驱动开发、TDD、代码审查和分支完成。
- **子代理驱动开发**: 将任务拆分为小任务，分派子代理执行，并自动进行两阶段审查（规范合规性和代码质量）。
- **测试驱动开发**: 强制RED-GREEN-REFACTOR循环，确保测试先行，并包含反模式参考。
- **系统性调试**: 提供4阶段根因分析流程，帮助定位和修复问题。

**技术亮点**: 基于Shell脚本实现，通过插件市场支持Claude Code、OpenAI Codex CLI、Cursor、OpenCode、GitHub Copilot CLI和Gemini CLI等多平台集成。

---
## 9. [Flowseal/zapret-discord-youtube](https://github.com/Flowseal/zapret-discord-youtube)
- **语言**: Batchfile
- **Stars**: 26,976
- **简介**: 

### AI 总结
**简介**: 这是一个基于 zapret 的 Windows 工具，用于解除对 Discord、YouTube 等服务的网络封锁。
**核心功能**:
- 提供多种手动启动策略（如 general.bat），用户可测试不同策略（ALT、FAKE 等）以找到绕过封锁的有效方案。
- 支持将策略安装为 Windows 服务以实现开机自启，并提供服务管理、状态检查、游戏/UDP 流量过滤模式切换、IP 集过滤等高级功能。
- 要求用户启用 Secure DNS（如 Chrome/Firefox/Windows 11 设置）以确保工具正常工作。
**技术亮点**: 使用 WinDivert 驱动拦截和过滤流量（Windows 下替代 Linux 的 iptables/NFQUEUE），所有二进制文件源自上游 zapret-win-bundle 项目。

---
