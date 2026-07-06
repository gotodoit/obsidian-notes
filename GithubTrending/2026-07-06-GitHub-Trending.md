---
tags:
  - github-trending
  - daily
date: 2026-07-06
created: 2026-07-06T01:55:43.626Z
---

# 2026-07-06 GitHub Trending Top 10

## 1. [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)
- **语言**: Rust
- **Stars**: 17,137
- **简介**: Privacy first, AI meeting assistant with 4x faster Parakeet/Whisper live transcription, speaker diarization, and Ollama summarization built on Rust. 100% local processing. no cloud required. Meetily (Meetly Ai - https://meetily.ai) is the #1 Self-hosted, Open-source Ai meeting note taker for macOS & Windows.

### AI 总结
**简介**: Meetily 是一款基于 Rust 构建、完全本地运行的开源 AI 会议助手，提供隐私优先的实时转录、讲话人分离和摘要功能，无需云服务。

**核心功能**:
- 实时转录：支持 4 倍速度的 Parakeet/Whisper 模型，在本地设备上实时捕获会议内容。
- 讲话人分离：自动识别并区分不同发言者，提升会议记录的清晰度。
- 智能摘要：利用 Ollama 模型在本地生成会议摘要，无需联网。
- 完全离线运行：所有数据处理在本地完成，确保数据主权和隐私安全。

**技术亮点**:
- 使用 Rust 语言开发，确保高性能和内存安全。
- 集成开源 AI 模型（Parakeet/Whisper 和 Ollama），避免依赖昂贵 API。
- 支持 macOS 和 Windows 平台，易于自托管和定制。

---
## 2. [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)
- **语言**: JavaScript
- **Stars**: 25,519
- **简介**: Use Codex from Claude Code to review code or delegate tasks.

### AI 总结
**简介**: 一个为 Claude Code 用户设计的插件，使其能直接在现有工作流中调用 OpenAI Codex 进行代码审查或任务委派。

**核心功能**:
- `/codex:review`: 对当前未提交更改或分支进行只读代码审查。
- `/codex:adversarial-review`: 进行可引导的对抗性审查，挑战实现方案和设计决策。
- `/codex:rescue`: 将调试、修复或任务委派给 Codex 子代理处理。
- `/codex:transfer`, `/codex:cancel`, `/codex:status`, `/codex:result`: 管理会话移交、后台任务状态查询和取消。

**技术亮点**: 基于 JavaScript 开发，依赖 Node.js 18.18+；支持后台运行和任务结果异步获取；通过 Claude Code 的插件市场安装，与现有工作流无缝集成。

---
## 3. [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)
- **语言**: JavaScript
- **Stars**: 50,032
- **简介**: Extracted system prompts from Anthropic - Claude Fable 5, Opus 4.8, Claude Code, Claude Design. OpenAI - ChatGPT 5.5 Thinking, GPT 5.5 Instant, Codex. Google - Gemini 3.5 Flash, 3.1 Pro, Antigravity. xAI - Grok, Cursor, Copilot, VS Code, Perplexity, and more. Updated regularly.

### AI 总结
**简介**: 该项目持续收集并公开各大AI聊天机器人（如Claude、ChatGPT、Gemini等）的系统提示词（System Prompt），旨在揭示其背后的运行规则。

**核心功能**:
- 收录并维护来自Anthropic、OpenAI、Google、xAI、Microsoft等公司多个AI模型的系统提示词。
- 提供不同模型版本之间的提示词差异对比（如Claude Opus 4.8 vs Fable 5）。
- 项目内容定期更新，并接受社区贡献（PRs Welcome）。

**技术亮点**: 项目以JavaScript为主要语言，利用GitHub仓库进行文档管理和版本对比，方便开发者追踪提示词变化。

---
## 4. [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)
- **语言**: JavaScript
- **Stars**: 57,576
- **简介**: Taste-Skill - gives your AI good taste. stops the AI from generating boring, generic slop

### AI 总结
**简介**: 一个为 AI 前端开发提供“审美品味”的 Agent Skills 框架，旨在让 AI 生成的界面摆脱千篇一律的模板化样式，输出更具设计感、布局、排版、动感和间距更优秀的代码。

**核心功能**:
- **提升 AI 前端审美**: 提供可移植的 Agent Skills，强化 AI 构建的界面，使其拥有更强的布局、排版、动感和间距，而非生成无聊的通用 UI。
- **图像生成参考板**: 包含用于生成参考板（网页、移动端、品牌套件）的图像生成技能，可与 ChatGPT Images 等生成器配合使用。
- **一键安装与集成**: 支持通过 `npx skills add` 命令一键安装，兼容 Codex、Cursor、Claude Code 等主流 AI 编程工具。

**技术亮点**:
- **基于 Agent Skills 标准**: 兼容 Vercel Labs 的 Agent Skills 标准，易于集成和扩展。
- **模块化技能设计**: 每个技能职责单一，用户可根据需要选择安装，支持按需更新和版本锁定（v1/v2）。

---
## 5. [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills)
- **语言**: Python
- **Stars**: 20,601
- **简介**: 337 Claude Code skills & agent skills & plugins (30+ Agents, 70+ custom commands, 330+ skills, customizable references, scripts)for Claude Code, Codex, Gemini CLI, Cursor, and 8 more coding agents — engineering, marketing, product, compliance, C-level advisory, research, business operations, commercial & finance, and your daily productivity skills.

### AI 总结
**简介**: 一个包含354个生产级技能的、最全面的开源AI编码代理技能库，支持13种主流编码工具。

**核心功能**:
- **多平台兼容**: 原生支持Claude Code、OpenAI Codex、Gemini CLI、Cursor等13种AI编码代理
- **技能包丰富**: 涵盖工程、DevOps、市场营销(含AEO)、安全、合规、C级咨询、学术研究等30+领域
- **插件化安装**: 支持按领域分模块安装技能包，如工程技能、产品技能、营销技能等
- **代理与角色系统**: 提供96个专业代理和7种角色人格，支持跨领域协作
- **自动化工具**: 包含593个纯Python标准库CLI脚本和711个参考模板文件

**技术亮点**:
- **零依赖Python工具**: 所有593个脚本仅使用Python标准库，无需pip安装
- **标准技能格式**: 采用统一的agentskills.io SKILL.md标准，便于跨平台转换
- **灵活转换机制**: 通过`scripts/convert.sh`脚本可适配更多编码工具
- **预生成安装树**: 为Hermes Agent和Mistral Vibe提供预生成的技能目录结构

---
## 6. [rommapp/romm](https://github.com/rommapp/romm)
- **语言**: Python
- **Stars**: 10,558
- **简介**: A beautiful, powerful, self-hosted rom manager and player.

### AI 总结
**简介**: RomM 是一个自托管的 ROM 管理器和播放器，支持扫描、增强、浏览和游玩游戏合集，拥有美观且响应式的界面。

**核心功能**:
- 从 IGDB、Screenscraper、MobyGames 等来源自动获取游戏元数据和封面
- 支持 400+ 平台，多碟游戏、DLC、MOD、补丁和手册
- 直接在浏览器中通过 EmulatorJS 和 RuffleRS 游玩游戏
- 支持标签解析、筛选和自定义标签
- 可分享游戏库给朋友，并设置访问权限
- 提供 Playnite、Android、CFWs 等官方应用

**技术亮点**: 基于 Python 开发，采用自托管架构，集成多个游戏元数据 API（IGDB、Screenscraper、MobyGames、SteamGridDB、Retroachievements），支持跨平台部署和多端客户端。

---
## 7. [ogulcancelik/herdr](https://github.com/ogulcancelik/herdr)
- **语言**: Rust
- **Stars**: 12,105
- **简介**: agent multiplexer that lives in your terminal.

### AI 总结
**简介**: herdr 是一个运行在终端中的智能体多路复用器，让你在一个终端窗口内同时管理多个编码智能体，并实时查看它们的状态。

**核心功能**:
- 每个智能体拥有独立的真实终端，支持全屏 TUI 应用的正确渲染
- 侧边栏实时显示智能体状态（阻塞、工作中、完成、空闲）
- 支持工作区、标签页和面板的鼠标拖动与拆分
- 后台服务器保持会话持久化，支持断开后重新连接（包括通过 SSH 从手机连接）
- 提供本地 Socket API 和 CLI，智能体可自行驱动，支持多语言插件

**技术亮点**:
- 单个约 10MB 的 Rust 二进制文件，无外部依赖
- 支持 Linux、macOS 和 Windows（Beta）
- 原生鼠标支持，无需额外配置即可用鼠标操作面板

---
## 8. [alibaba/page-agent](https://github.com/alibaba/page-agent)
- **语言**: TypeScript
- **Stars**: 23,939
- **简介**: JavaScript in-page GUI agent. Control web interfaces with natural language.

### AI 总结
**简介**: Page Agent 是一个基于 JavaScript 的页面内 GUI 代理，允许用户通过自然语言控制网页界面。

**核心功能**:
- **轻松集成**: 无需浏览器扩展、Python 或无头浏览器，只需在页面中引入 JavaScript 即可运行。
- **基于文本的 DOM 操作**: 不依赖截图或多模态 LLM，直接操作网页文本元素。
- **自带 LLM 支持**: 用户可自由选择和使用自己的大语言模型。
- **可选 Chrome 扩展**: 支持多页面任务，并可通过 MCP 服务器从外部控制浏览器。

**技术亮点**:
- 纯 TypeScript 实现，无外部依赖。
- 支持通过 npm 安装或 CDN 一键集成。
- 提供免费测试 API 用于快速评估。

---
## 9. [harvard-edge/cs249r_book](https://github.com/harvard-edge/cs249r_book)
- **语言**: Python
- **Stars**: 26,862
- **简介**: Machine Learning Systems

### AI 总结
**简介**: 哈佛大学推出的开源教科书项目，系统教授人工智能系统的工程化设计与实现，旨在弥合AI模型开发与系统工程之间的鸿沟。

**核心功能**:
- 提供完整的两卷本在线教科书（Vol I & Vol II），涵盖ML系统原理与实践
- 集成TinyTorch深度学习框架教学实现、Jupyter实验环境及硬件套件
- 提供MLSys·im系统模拟器、StaffML人员管理工具及教学幻灯片资源
- 支持多语言（中/日/韩/英）文档与社区贡献机制

**技术亮点**: 采用GitHub Actions自动化验证流水线（覆盖书籍、实验、硬件套件等模块），基于Python生态构建，计划2026年由MIT Press出版纸质版。

---
## 10. [usestrix/strix](https://github.com/usestrix/strix)
- **语言**: Python
- **Stars**: 37,171
- **简介**: Open-source AI penetration testing tool to find and fix your app’s vulnerabilities.

### AI 总结
**简介**: Strix 是一个开源的 AI 渗透测试工具，通过自主 AI 代理动态运行代码、发现并验证应用程序漏洞，提供真实可用的概念验证，帮助开发者快速修复安全问题。

**核心功能**:
- **全栈渗透测试工具包**：内置侦察、利用和验证模块，开箱即用
- **多代理协同**：多个 AI 渗透测试代理协作，可扩展扫描规模
- **真实漏洞验证**：生成可工作的 PoC（概念验证），避免传统扫描器的误报
- **开发者友好的 CLI**：提供可操作的发现结果和修复指导
- **自动修复与报告**：自动生成安全补丁和合规性渗透测试报告

**技术亮点**:
- 基于 Python 开发，支持 Docker 沙箱环境运行
- 支持多种 LLM 提供商（OpenAI、Anthropic、Google 等）
- 集成 CI/CD 流水线（GitHub Actions、GitLab 等），实现自动化的持续渗透测试
- 提供全栈平台（app.strix.ai），支持一键自动修复和持续学习

---
