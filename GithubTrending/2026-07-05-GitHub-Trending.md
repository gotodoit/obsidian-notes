---
tags:
  - github-trending
  - daily
date: 2026-07-05
created: 2026-07-05T01:55:42.699Z
---

# 2026-07-05 GitHub Trending Top 10

## 1. [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)
- **语言**: JavaScript
- **Stars**: 24,494
- **简介**: Use Codex from Claude Code to review code or delegate tasks.

### AI 总结
**简介**: 一个让 Claude Code 用户能直接调用 OpenAI Codex 进行代码审查或任务委托的插件。

**核心功能**:
- **`/codex:review`**: 对当前未提交的更改或分支进行只读代码审查。
- **`/codex:adversarial-review`**: 进行可引导的挑战性审查，质疑实现决策和设计取舍。
- **`/codex:rescue`**: 将任务（如调查 Bug、尝试修复）委托给 Codex 后台处理。
- **任务管理**: 提供 `/codex:transfer`、`/codex:status`、`/codex:result`、`/codex:cancel` 等命令来管理后台任务和会话。

**技术亮点**: 基于 JavaScript 开发，需要 Node.js 18.18+ 环境，通过 Claude Code 的插件市场安装，并依赖 OpenAI Codex CLI 工具。

---
## 2. [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)
- **语言**: JavaScript
- **Stars**: 84,010
- **简介**: 🪨 why use many token when few token do trick — Claude Code skill that cuts 65% of tokens by talking like caveman

### AI 总结
**简介**: Caveman 是一个让 AI 编码助手用“原始人语”回答问题的技能/插件，可减少约 65% 的输出 Token 而保持技术准确性。

**核心功能**:
- 安装后，AI 代理（如 Claude Code、Codex、Cursor 等 30+ 种）会自动使用精简语言回答，代码和错误信息保持原样。
- 提供 6 级精简程度（lite/full/ultra 等），可随时切换。
- 支持一键安装，自动检测并为机器上所有支持的代理配置，也可单独安装。
- 可通过命令 `/caveman` 开启，或说“normal mode”关闭。

**技术亮点**: 基于 JavaScript 开发，通过修改代理的指令/规则文件实现输出精简，无需改变模型知识或输入 Token。

---
## 3. [alibaba/page-agent](https://github.com/alibaba/page-agent)
- **语言**: TypeScript
- **Stars**: 23,139
- **简介**: JavaScript in-page GUI agent. Control web interfaces with natural language.

### AI 总结
**简介**: Page Agent 是一个基于 JavaScript 的页面内 GUI 代理，允许用户通过自然语言控制网页界面。

**核心功能**:
- **简单集成**: 无需浏览器扩展、Python 或无头浏览器，仅通过内联 JavaScript 即可实现，所有操作在网页内完成。
- **基于文本的 DOM 操作**: 无需截图或多模态 LLM，直接操作 DOM 元素。
- **自带 LLM 支持**: 用户可自由选择和使用自己的大语言模型。
- **可选 Chrome 扩展**: 支持多页面任务，并提供 MCP 服务器（测试版）供外部控制。
- **快速集成**: 提供 CDN 一键引入和 NPM 安装两种方式，支持通过自然语言执行点击、填表等操作。

**技术亮点**: 基于 TypeScript 开发，采用文本驱动的 DOM 操作而非截图识别，支持多种 LLM 接入（如阿里云 DashScope API），提供轻量级 IIFE 包和模块化 NPM 包。

---
## 4. [usestrix/strix](https://github.com/usestrix/strix)
- **语言**: Python
- **Stars**: 36,100
- **简介**: Open-source AI penetration testing tool to find and fix your app’s vulnerabilities.

### AI 总结
**简介**: Strix 是一个开源的 AI 渗透测试工具，通过自主 AI 代理动态运行代码、发现并验证漏洞，帮助开发者快速修复应用安全问题。

**核心功能**:
- **全栈渗透测试**：内置侦察、利用和验证工具，提供完整的攻击测试能力。
- **多代理协同**：支持多 AI 代理团队协作，可扩展并发测试。
- **真实漏洞验证**：生成可用的概念验证（PoC），避免误报。
- **开发者优先 CLI**：提供可操作的漏洞发现与修复指导。
- **自动修复与报告**：自动生成安全补丁和合规就绪的渗透测试报告。

**技术亮点**: 基于 Python 开发，支持多种 LLM 提供商（如 OpenAI、Anthropic、Google），通过 Docker 沙箱运行，与 GitHub Actions 和 CI/CD 流水线无缝集成，实现自动化漏洞拦截。

---
## 5. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)
- **语言**: TypeScript
- **Stars**: 45,789
- **简介**: Chrome DevTools for coding agents

### AI 总结
**简介**: `chrome-devtools-mcp` 是一个 MCP 服务器，允许 AI 编码助手（如 Antigravity、Claude 等）通过 Chrome DevTools 控制和检查实时浏览器，实现自动化、调试和性能分析。

**核心功能**:
- **性能洞察**: 录制 Chrome 跟踪并提取可操作的性能建议。
- **高级浏览器调试**: 分析网络请求、截图、检查控制台消息（含源码映射堆栈）。
- **可靠自动化**: 基于 Puppeteer 自动执行操作并等待结果。

**技术亮点**:
- 基于 Chrome DevTools 和 Puppeteer 构建。
- 支持 MCP 协议，可集成多种 AI 编码工具。
- 提供 CLI 模式，支持无 MCP 使用。
- 提供 Slim 模式，适用于基础浏览器任务。

---
## 6. [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)
- **语言**: Rust
- **Stars**: 15,320
- **简介**: Privacy first, AI meeting assistant with 4x faster Parakeet/Whisper live transcription, speaker diarization, and Ollama summarization built on Rust. 100% local processing. no cloud required. Meetily (Meetly Ai - https://meetily.ai) is the #1 Self-hosted, Open-source Ai meeting note taker for macOS & Windows.

### AI 总结
**简介**: Meetily 是一款基于 Rust 构建、注重隐私的 AI 会议助手，支持 4 倍速 Parakeet/Whisper 实时转录、说话人分离和 Ollama 摘要生成，所有处理均在本地完成，无需云端。

**核心功能**:
- **实时本地转录**: 利用 Parakeet/Whisper 模型实现 4 倍速实时语音转文字
- **说话人分离**: 识别并区分不同发言者
- **智能摘要生成**: 通过 Ollama 模型自动生成会议摘要
- **完全离线运行**: 所有数据处理均在本地设备完成，无需网络连接
- **跨平台支持**: 兼容 macOS 和 Windows 系统
- **企业级隐私保护**: 数据完全自托管，无供应商锁定风险

**技术亮点**:
- 基于 Rust 语言开发，确保高性能和内存安全
- 使用开源 AI 模型（Whisper、Ollama）替代昂贵 API
- 支持多种会议平台，可离线工作
- 提供社区版和 PRO 版（增强准确性、高级导出、自定义工作流）

---
## 7. [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)
- **语言**: JavaScript
- **Stars**: 48,960
- **简介**: Extracted system prompts from Anthropic - Claude Fable 5, Opus 4.8, Claude Code, Claude Design. OpenAI - ChatGPT 5.5 Thinking, GPT 5.5 Instant, Codex. Google - Gemini 3.5 Flash, 3.1 Pro, Antigravity. xAI - Grok, Cursor, Copilot, VS Code, Perplexity, and more. Updated regularly.

### AI 总结
**简介**: 一个持续更新的系统提示词泄露库，收录了 Anthropic、OpenAI、Google、xAI 等主流 AI 聊天机器人的系统指令。

**核心功能**:
- 收集并公开 Claude、ChatGPT、Gemini、Grok 等数十款 AI 模型的系统提示词
- 提供模型间的差异对比（如 Claude Opus 4.8 → Fable 5）
- 定期更新，覆盖最新模型版本及官方/第三方集成提示

**技术亮点**: 基于 JavaScript 维护的纯文档仓库，支持社区 PR 贡献，通过 GitHub 徽章和流量图监控活跃度。

---
## 8. [harvard-edge/cs249r_book](https://github.com/harvard-edge/cs249r_book)
- **语言**: Python
- **Stars**: 26,582
- **简介**: Machine Learning Systems

### AI 总结
**简介**: 这是哈佛大学面向机器学习系统的开源教科书与课程资源库，旨在将AI工程确立为与软件工程、计算机工程并列的基础学科。

**核心功能**:
- 提供两卷在线教科书（Vol I & Vol II）及配套实验（Labs）
- 包含从零实现的微型深度学习框架TinyTorch
- 提供MLSys·im模拟器与StaffML教学管理工具
- 支持多语言（中/日/韩）翻译版本

**技术亮点**:
- 基于Python/Jupyter生态，集成CI/CD自动化验证（Book/TinyTorch/Labs/Kits等独立工作流）
- 采用CC-BY-NC-SA 4.0开源协议
- 提供硬件套件（Kits）支持嵌入式AI实践
- 目标2026年由MIT Press出版纸质版

---
## 9. [rommapp/romm](https://github.com/rommapp/romm)
- **语言**: Python
- **Stars**: 10,217
- **简介**: A beautiful, powerful, self-hosted rom manager and player.

### AI 总结
**简介**: RomM 是一个自托管的 ROM 管理器和播放器，支持扫描、增强、浏览和游玩游戏合集，界面简洁响应式。

**核心功能**:
- 从 IGDB、Screenscraper 和 MobyGames 获取元数据，丰富游戏库
- 从 SteamGridDB 获取自定义封面和图标
- 显示 Retroachievements 成就
- 支持 400+ 平台
- 使用 EmulatorJS 和 RuffleRS 在浏览器中直接游玩游戏
- 支持多碟游戏、DLC、修改版、补丁、手册和自定义标签
- 支持上传、更新、删除游戏，以及分享库给好友
- 提供 Playnite、Android、CFWs 等官方应用

**技术亮点**: 基于 Python 开发，支持 Docker 部署，使用多种 API 获取元数据和封面，集成浏览器端模拟器。

---
## 10. [ogulcancelik/herdr](https://github.com/ogulcancelik/herdr)
- **语言**: Rust
- **Stars**: 11,477
- **简介**: agent multiplexer that lives in your terminal.

### AI 总结
**简介**: herdr 是一个运行在终端中的代理多路复用器，让你在一个终端里管理所有编码代理，实时查看它们的状态。

**核心功能**:
- 每个代理拥有独立的真实终端，支持全屏 TUI 正确渲染
- 侧边栏显示代理状态：🔴阻塞、🟡工作中、🔵已完成、🟢空闲
- 支持工作区、标签页和窗格，可通过鼠标拖拽分割
- 后台服务器保持会话持久，断开后可重新连接（包括通过 SSH 从手机连接）
- 提供本地 Socket API 和 CLI，代理可自主驱动，支持多语言插件

**技术亮点**:
- 单一 Rust 二进制文件（约10MB），无依赖，支持 Linux/macOS（Windows 测试版）
- 无需 GUI、Electron、账户或遥测，直接在终端中运行
- 相比 tmux 和 GUI 代理管理器，兼具持久化会话、真实终端视图和代理状态感知能力

---
