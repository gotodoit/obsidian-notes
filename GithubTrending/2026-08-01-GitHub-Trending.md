---
tags:
  - github-trending
  - daily
date: 2026-08-01
created: 2026-08-01T01:55:45.240Z
---

# 2026-08-01 GitHub Trending Top 10

## 1. [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill)
- **语言**: PowerShell
- **Stars**: 10,773
- **简介**: Reverse Engineering / Authorized Penetration Testing / Security Research Skill Router Pack AI-powered routing + On-demand toolchain bootstrapping + Self-evolving knowledge base Supports Claude Code, Kiro, Cursor, Cline, and other AI coding clients 逆向/渗透/安全技能路由包 - AI 自动路由 + 按需自举工具链 + 自动进化经验库 | 支持 Claude Code / Kiro / Cursor / Cline 等代码 AI 客户端

### AI 总结
**简介**: reverse-skill 是一个面向 AI 编程客户端的网络安全技能路由包，为逆向工程、渗透测试和安全研究任务提供自动化的方法论路由、工具链自举和经验库进化能力。

**核心功能**:
- **智能任务路由**: 根据任务类型（APK、二进制、JS 加密、CTF 挑战等）自动匹配对应的方法论和操作流程，避免 AI 猜测命令
- **工具链按需自举**: 自动检测并索引本机可用工具（如 jadx、apktool、Frida、IDA 等），支持跨平台刷新工具索引
- **可重复工作流执行**: 从任务输入到报告输出的完整流程，包含 case-init、scope 定义、证据链追踪和现场日志记录
- **自进化知识库**: 复用历史经验，避免重复犯错，持续积累安全研究知识
- **多客户端支持**: 兼容 Claude Code、Kiro、Cursor、Cline、Codex CLI 等多种 AI 编程客户端

**技术亮点**: 基于 PowerShell 实现，集成了 Python、Node.js、Java 等多语言工具链，支持 Windows、Linux/macOS 和 Kali Linux 多平台部署；采用主路由（master-route.ps1）+ 场景技能包 + 操作契约的层级架构，配合工具索引和平台适配文档，确保 AI 代理能安全、合规地执行授权渗透测试任务。

---
## 2. [different-ai/openwork](https://github.com/different-ai/openwork)
- **语言**: TypeScript
- **Stars**: 19,533
- **简介**: The open-source alternative to Claude Cowork (powered by opencode)

### AI 总结
**简介**: OpenWork 是一款免费开源的桌面应用，旨在共享 AI 工作流，可作为 Claude Cowork 和 Codex 的开源替代品，支持 macOS、Windows 和 Linux。

**核心功能**:
- 通过 MCP 集成到 Codex、Claude Code、Cursor 等主流 AI 代理，复用技能、MCP 和已连接服务
- 提供独立桌面应用作为专用工作区，同时支持从已有代理直接使用
- 管理界面（OpenWork Den）支持团队协作，可发布能力、管理访问权限、配置共享或个性化连接
- 支持从任意兼容 MCP 的客户端远程调用，提供 `search_capabilities` 和 `execute_capability` 两个核心工具
- 支持导入 Anthropic 兼容插件，并通过市场发布技能和插件

**技术亮点**: 基于 TypeScript 开发，采用 MCP（Model Context Protocol）远程服务器架构（`https://api.openworklabs.com/mcp/agent`），支持 OAuth 认证；使用 Electron + Vite 构建桌面应用，支持多工作树并行开发（`pnpm dev:worktree`），具备独立的开发配置文件管理和模拟钥匙串机制。

---
## 3. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 56,245
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: /last30days 是一个 AI 智能体驱动的搜索引擎，并行搜索 Reddit、X、YouTube 等多个平台，按真实用户参与度（点赞、投票、下注）排序，并生成综合摘要。

**核心功能**:
- 跨平台并行搜索：同时检索 Reddit、X/Twitter、YouTube、TikTok、Instagram Reels、Hacker News、Polymarket 等平台内容
- 用户参与度评分：按真实用户的 upvotes、likes 和 Polymarket 真金白银的赔率进行排序，而非编辑推荐
- AI 智能体综合研判：自动将分散在各平台的讨论、帖子和视频转录合成一份精炼简报
- 零配置快速上手：Reddit、HN、Polymarket 和 GitHub 开箱即用；运行一次设置向导即可解锁 X、YouTube 等更多平台
- 多宿主支持：支持 Claude Code（推荐）、Codex、Cursor、Copilot、Gemini CLI 等 50+ Agent Skills 宿主，通过一行命令安装

**技术亮点**: 采用 Agent Skills 规范（SKILL.md）定义运行时行为；支持自带 API 密钥和浏览器会话，突破各平台封闭生态（walled garden）限制；v3 流水线架构，通过智能体桥接多个互不相通的平台数据源。

---
## 4. [paperswithbacktest/awesome-systematic-trading](https://github.com/paperswithbacktest/awesome-systematic-trading)
- **语言**: Python
- **Stars**: 11,776
- **简介**: A curated list of awesome libraries, packages, strategies, books, blogs, tutorials for systematic trading.

### AI 总结
**简介**: 这是一个精心整理的系统化交易（量化交易）资源大全，汇集了研究、开发和运行量化策略所需的论文、软件、书籍和文章。

**核心功能**:
- **97个库和包**：涵盖回测、实盘交易、交易机器人、数据分析、指标计算、风险管理和机器学习等，按编程语言分类并按星标排序
- **40+交易策略**：收录机构与学术界描述的跨资产类别策略（债券、商品、外汇、股票、加密货币等）
- **55本书籍**：从入门到专业，涵盖编程、加密货币、高频交易和机器学习等主题
- **23个视频与访谈**：提供可视化学习资源
- **博客和课程**：额外补充实践学习路径

**技术亮点**: 资源以 Python 为主，涵盖事件驱动框架（如 vnpy、zipline、backtrader）和向量化框架，支持数据源、经纪商 API、数据库、时间序列分析及可视化等完整量化研究链条，并配有中文版 README（README_zh.md）。

---
## 5. [microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners)
- **语言**: Jupyter Notebook
- **Stars**: 55,354
- **简介**: 12 Weeks, 24 Lessons, AI for All!

### AI 总结
**简介**: 微软推出的12周、24课时的AI入门课程，为初学者提供全面的人工智能学习路径，涵盖实践课程、测验和实验。

**核心功能**:
- 12周24课时的结构化AI学习课程，适合初学者
- 包含实践课程、测验和实验（labs），覆盖TensorFlow和PyTorch等工具
- 提供AI伦理相关教学内容
- 支持50+种语言翻译，通过GitHub Action自动维护更新
- 支持Binder在线运行，无需本地环境即可体验

**技术亮点**: 基于Jupyter Notebook编写，采用Sketchnote视觉笔记辅助教学，集成Binder在线执行环境，并通过GitHub Action实现多语言文档自动化同步。

---
## 6. [github/copilot-sdk](https://github.com/github/copilot-sdk)
- **语言**: Java
- **Stars**: 10,142
- **简介**: Multi-platform SDK for integrating GitHub Copilot Agent into apps and services

### AI 总结
**简介**: GitHub Copilot SDK 是一个多平台 SDK，允许开发者在自己的应用中嵌入 GitHub Copilot Agent 的代理工作流，复用生产级代理运行时，无需自建编排系统。

**核心功能**:
- 支持 Python、TypeScript、Go、.NET、Java 和 Rust 六种语言，提供对应的 SDK 包与安装方式
- 通过编程方式调用 Copilot Agent 运行时，可定义代理行为，由 Copilot 处理规划、工具调用、文件编辑等任务
- 提供 Cookbook 示例与 API 文档，帮助开发者快速集成

**技术亮点**: 基于 Copilot CLI 背后的生产级代理引擎，支持多语言生态（npm、PyPI、NuGet、Go modules、crates.io、Maven Central），可直接嵌入现有应用，减少编排开发成本。

---
## 7. [chatwoot/chatwoot](https://github.com/chatwoot/chatwoot)
- **语言**: Ruby
- **Stars**: 35,136
- **简介**: Open-source live-chat, email support, omni-channel desk. An alternative to Intercom, Zendesk, Salesforce Service Cloud etc. 🔥💬

### AI 总结
**简介**: Chatwoot 是一个开源、可自托管的现代客户支持平台，旨在替代 Intercom、Zendesk 和 Salesforce Service Cloud 等商业工具，提供全渠道客户沟通管理能力。

**核心功能**:
- **全渠道收件箱**: 统一管理来自网站实时聊天、电子邮件、Facebook、Instagram、Twitter、WhatsApp、Telegram、Line、SMS 等渠道的客户对话。
- **AI 助手 Captain**: 内置 AI 代理，可自动回复常见问题、减少客服工作量，让团队专注于复杂对话。
- **帮助中心门户**: 发布帮助文章、FAQ 和指南，支持客户自助服务，减少重复咨询。
- **协作与生产力工具**: 支持私密笔记、@提及、标签、快捷键、命令栏、预设回复、自动分配、多语言支持、自定义视图、工作时间与自动回复、团队与自动化工作流、客服容量管理。
- **客户数据与细分**: 提供联系人管理、客户细分、活动营销、自定义属性、会话前表单等功能。
- **丰富集成**: 支持 Slack、Dialogflow、Shopify、Google Translate 等第三方服务集成。

**技术亮点**: 基于 Ruby 构建，支持 Docker 部署和 Helm Chart，可一键部署到 Heroku 和 DigitalOcean；提供完整的自托管方案，保障客户数据主权；项目活跃度高，支持多语言国际化（通过 Crowdin 协作翻译），并具备持续集成和状态监控。

---
## 8. [agavra/tuicr](https://github.com/agavra/tuicr)
- **语言**: Rust
- **Stars**: 2,164
- **简介**: a code review TUI with vim keybindings

### AI 总结
**简介**: tuicr 是一个基于 Rust 的代码评审 TUI 工具，支持 vim 键位操作，可将评审结果导出至 GitHub、GitLab 或剪贴板。

**核心功能**:
- 终端内连续 diff 展示，支持 GitHub 风格流式滚动浏览所有变更文件
- 支持行级、范围级、文件级和评审级评论，类似 PR 评论体验
- 评审进度按文件或 hunk 粒度追踪，跨会话持久化保存
- 三种导出方式：推送真实评审至 GitHub/GitLab、复制结构化 Markdown 至剪贴板、或输出到 stdout
- 兼容 git、jj 和 mercurial，支持未提交变更、提交范围或任意 GitHub PR/GitLab MR
- 内置一键更新机制，支持 Homebrew、Cargo、Mise、Nix 及二进制文件管理

**技术亮点**: 单一静态二进制文件，无需运行时依赖；自动检测底层 VCS 工具（git/jj/hg）；集成 GitHub CLI (`gh`) 和 GitLab CLI (`glab`) 认证；采用原生 TUI 实现，提供完整 vim 操作模型（视觉模式、跳转、滚动等）。

---
## 9. [usekaneo/kaneo](https://github.com/usekaneo/kaneo)
- **语言**: TypeScript
- **Stars**: 5,115
- **简介**: 🎯 All you need. Nothing you don't. Open source project management that works for you, not against you.

### AI 总结
**简介**: Kaneo 是一款开源、可自托管、注重简洁高效的项目管理工具，致力于通过极简设计帮助团队专注于实际工作而非工具本身。

**核心功能**:
- 干净的界面设计，减少干扰，聚焦工作本身
- 支持自托管部署，确保数据完全由用户掌控
- 高性能表现，注重响应速度与用户体验
- 开源且采用宽松的 MIT 许可证，可自由使用和修改

**技术亮点**:
- 基于 TypeScript 开发，类型安全可靠
- 提供多种部署方式：支持 Docker Compose 快速部署，以及通过 drim CLI 工具实现一键部署（自动配置 HTTPS、数据库等）
- 使用 PostgreSQL 作为数据库，容器化编排，支持健康检查与自动重启

---
## 10. [geo-tp/ESP32-Bit-Pirate](https://github.com/geo-tp/ESP32-Bit-Pirate)
- **语言**: C++
- **Stars**: 5,028
- **简介**: A Hardware Hacking Tool with Web-Based CLI That Speaks Every Protocol

### AI 总结
**简介**: ESP32 Bus Pirate 是一个开源固件，可将 ESP32 设备转变为支持多种数字与无线协议的多功能硬件黑客工具，灵感源自经典的 Bus Pirate。

**核心功能**:
- **多协议支持**: 涵盖 I2C、SPI、UART、1-Wire、JTAG、CAN、I2S、红外、USB HID、蓝牙、Wi-Fi、Sub-GHz、RFID 等 20 余种协议模式。
- **交互式 CLI**: 通过 USB 串口或 WiFi 网页提供命令行界面，支持嗅探、发送、脚本编程及设备交互。
- **协议嗅探与工具链**: 内置 I2C/SPI/CAN/无线协议嗅探器，支持 EEPROM 转储、波特率自动检测、寄存器操作等调试工具。
- **脚本能力**: 支持 Bus Pirate 风格字节码指令及 Python 脚本，便于自动化测试。
- **无线攻击与信号分析**: 支持 Wi-Fi 嗅探/反认证、蓝牙 BLE 欺骗、Sub-GHz 扫描重放、红外 Device-B-Gone（80+ 协议）。
- **硬件外设支持**: 兼容 ESP32 S3 Dev Kit、M5 Cardputer 等设备，提供 PWM、伺服控制、LED 动画及 LittleFS 文件系统导入导出。

**技术亮点**: 基于 C++ 开发，采用模块化协议栈架构；支持通过 Web Flasher 一键安装固件；提供丰富的 Wiki 文档和脚本库；具备独立运行模式（如 Cardputer 键盘界面）。注意：当前分支为基于旧 Arduino 内核的遗留版本，新开发已迁移至 pioarduino 分支。

---
