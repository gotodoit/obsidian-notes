---
tags:
  - github-trending
  - daily
date: 2026-07-04
created: 2026-07-04T01:55:44.129Z
---

# 2026-07-04 GitHub Trending Top 10

## 1. [usestrix/strix](https://github.com/usestrix/strix)
- **语言**: Python
- **Stars**: 34,700
- **简介**: Open-source AI penetration testing tool to find and fix your app’s vulnerabilities.

### AI 总结
**简介**: Strix 是一个开源的人工智能渗透测试工具，能够自主发现并修复应用程序中的安全漏洞。

**核心功能**:
- 提供完整的渗透测试工具包，包括侦察、利用和验证
- 多智能体编排，支持AI渗透测试团队协作和扩展
- 真实漏洞验证，生成有效的概念验证（PoC）而非误报
- 开发者优先的CLI工具，提供可操作的发现结果和修复指南
- 自动修复与报告生成，可产生安全补丁和合规就绪的渗透测试报告

**技术亮点**:
- 基于Python开发，支持多LLM提供商（OpenAI、Anthropic、Google等）
- 使用Docker沙箱环境运行，确保测试安全隔离
- 支持CI/CD集成（GitHub Actions等），可在每次拉取请求时自动扫描
- 提供全栈渗透测试平台（app.strix.ai），支持持续学习和DevSecOps集成

---
## 2. [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc)
- **语言**: JavaScript
- **Stars**: 23,243
- **简介**: Use Codex from Claude Code to review code or delegate tasks.

### AI 总结
**简介**: 一个为 Claude Code 用户设计的插件，允许在 Claude Code 工作流中直接调用 OpenAI Codex 进行代码审查或任务委派。

**核心功能**:
- **代码审查**: 支持普通审查 (`/codex:review`) 和对抗性审查 (`/codex:adversarial-review`)，可对当前更改或整个分支进行审查
- **任务委派**: 通过子代理 (`/codex:rescue`) 将调试、修复等任务交给 Codex 处理，支持后台运行和恢复历史任务
- **后台作业管理**: 提供 `/codex:status`、`/codex:result` 和 `/codex:cancel` 命令管理后台任务

**技术亮点**:
- 基于 JavaScript 开发，需 Node.js 18.18+
- 通过 Claude Code 的插件系统集成，支持 `/plugin` 命令安装
- 支持 ChatGPT 订阅或 OpenAI API 密钥认证，使用 OpenAI Codex 作为底层引擎

---
## 3. [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)
- **语言**: JavaScript
- **Stars**: 82,968
- **简介**: 🪨 why use many token when few token do trick — Claude Code skill that cuts 65% of tokens by talking like caveman

### AI 总结
**简介**: Caveman 是一个 AI 编程助手插件/技能，能让 Claude Code、Codex、Cursor 等 30+ 智能体以“穴居人”风格简短回复，减少 65% 的输出 Token。

**核心功能**:
- **Token 节省**: 将智能体回答精简为最简形式，减少 65% 输出 Token，技术细节零损失。
- **多智能体兼容**: 支持 Claude Code、Codex、Gemini、Cursor、Windsurf、Cline、Copilot 等 30+ 主流 AI 编程助手。
- **一键安装**: 通过一条命令自动检测并安装至本机所有支持的智能体，支持 macOS/Linux/Windows。
- **多级精简模式**: 提供 `lite`、`full`（默认）、`ultra` 等 6 级精简强度，可随时切换。
- **开关控制**: 使用 `/caveman` 命令开启，说“normal mode”即可恢复普通模式。

**技术亮点**:
- **JavaScript 实现**: 轻量级插件，依赖 Node ≥18。
- **智能体无关架构**: 通过统一的技能注册机制（`npx skills add`）兼容多种 AI 助手。

---
## 4. [elastic/elasticsearch](https://github.com/elastic/elasticsearch)
- **语言**: Java
- **Stars**: 77,345
- **简介**: Free and Open Source, Distributed, RESTful Search Engine

### AI 总结
**简介**: 一个免费开源、分布式、RESTful 的搜索引擎。
**核心功能**:
- 分布式全文搜索与分析
- 实时数据索引与检索
- 支持多种数据源与查询方式
**技术亮点**: 基于 Java 开发，采用分布式架构，使用 Lucene 作为底层搜索引擎，提供 RESTful API 接口。

---
## 5. [actions/checkout](https://github.com/actions/checkout)
- **语言**: TypeScript
- **Stars**: 8,267
- **简介**: Action for checking out a repo

### AI 总结
**简介**: actions/checkout 是一个 GitHub Action，用于在 workflow 中检出仓库代码，支持指定分支、标签或 SHA。

**核心功能**:
- 将仓库代码检出到 `$GITHUB_WORKSPACE` 目录
- 默认只获取触发 workflow 的单个 commit，可通过 `fetch-depth: 0` 获取所有历史
- 支持通过 token 或 SSH 密钥进行身份验证，自动在本地 git 配置中持久化凭证，并在 job 结束后清理
- 提供 `allow-unsafe-pr-checkout` 选项以安全处理 fork PR 的检出
- 当 Git 版本低于 2.18 时，自动回退使用 REST API 下载文件

**技术亮点**:
- 使用 TypeScript 开发，已迁移至 ESM 模块化架构
- 凭证存储改进：v6 起将凭证存储在 `$RUNNER_TEMP` 下的独立文件，而非直接写入 `.git/config`
- 支持 node24 运行时（v5 起），需匹配特定 Actions Runner 版本

---
## 6. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)
- **语言**: TypeScript
- **Stars**: 45,503
- **简介**: Chrome DevTools for coding agents

### AI 总结
**简介**: 一个基于MCP协议的Chrome DevTools工具，让AI编程助手（如Antigravity、Claude等）能够实时控制、调试和分析Chrome浏览器。

**核心功能**:
- **性能分析**: 利用Chrome DevTools记录追踪并提取可操作的性能洞察
- **高级调试**: 分析网络请求、截取屏幕截图、检查浏览器控制台消息（含源码映射堆栈跟踪）
- **可靠自动化**: 基于Puppeteer实现Chrome操作自动化，并自动等待操作结果

**技术亮点**:
- 基于TypeScript开发，使用Puppeteer进行浏览器自动化控制
- 支持MCP协议，可无缝集成到多种AI编程助手中
- 提供CLI模式，支持无MCP环境使用
- 支持Slim模式，适合仅需基础浏览器操作的场景

---
## 7. [ansible/ansible](https://github.com/ansible/ansible)
- **语言**: Python
- **Stars**: 69,213
- **简介**: Ansible is a radically simple IT automation platform that makes your applications and systems easier to deploy and maintain. Automate everything from code deployment to network configuration to cloud management, in a language that approaches plain English, using SSH, with no agents to install on remote systems. https://docs.ansible.com.

### AI 总结
**简介**: Ansible 是一个极其简单的 IT 自动化平台，通过 SSH 实现无代理的配置管理、应用部署、云编排等任务，使用接近自然语言的语法。

**核心功能**:
- **配置管理**: 自动化系统和服务器的配置与维护。
- **应用部署**: 简化多节点应用部署流程。
- **云编排**: 管理云资源（如 AWS、Azure）的创建和配置。
- **任务执行**: 支持临时命令的批量并行执行。
- **网络自动化**: 自动化网络设备配置与变更。
- **零宕机滚动更新**: 结合负载均衡实现无缝更新。

**技术亮点**:
- **无代理架构**: 基于 SSH 协议，无需在远程主机安装代理。
- **YAML 语法**: 使用人类可读的 Playbook 描述基础设施。
- **模块化设计**: 支持 Python 及任意动态语言开发模块。
- **并行执行**: 默认并行管理多台机器，提升效率。
- **最小化依赖**: 仅需 Python 和 SSH，支持非 root 用户操作。

---
## 8. [facebook/astryx](https://github.com/facebook/astryx)
- **语言**: TypeScript
- **Stars**: 4,686
- **简介**: An open source design system that's fully customizable and agent ready

### AI 总结
**简介**: Astryx 是 Meta 内部使用八年、开源的可定制设计系统，支持 13,000+ 应用，专为人类和 AI 代理协作构建而设计。

**核心功能**:
- 150+ 可访问的 React 组件，支持品牌级主题、暗黑模式和开箱即用的模板
- 提供 CLI 工具，用于组件文档、模板、脚手架、主题和代码迁移
- 通过 CSS 自定义属性实现无需包装的主题定制，支持 Tailwind、CSS Modules 等样式方案
- 组件支持“swizzle”机制，可导出完整源码到项目中直接修改

**技术亮点**: 基于 React 和 StyleX 构建，对消费者透明；无需构建插件即可使用预编译 CSS；API、文档和 CLI 统一设计，确保人类和 AI 代理以相同方式构建。

---
## 9. [rommapp/romm](https://github.com/rommapp/romm)
- **语言**: Python
- **Stars**: 9,821
- **简介**: A beautiful, powerful, self-hosted rom manager and player.

### AI 总结
**简介**: RomM 是一款自托管的 ROM 管理器和播放器，支持扫描、丰富元数据、浏览和在线游玩游戏合集。

**核心功能**:
- 从 IGDB、Screenscraper、MobyGames 等多源获取游戏元数据
- 从 SteamGridDB 获取自定义封面
- 显示 Retroachievements 成就
- 支持 400+ 平台
- 通过 EmulatorJS 和 RuffleRS 直接在浏览器中游玩
- 支持多盘游戏、DLC、模组、补丁、手册等
- 基于文件名的标签解析和筛选
- 提供官方移动端、桌面端和手持设备应用

**技术亮点**: 基于 Python 开发，采用自托管架构，支持 Docker 部署，集成多种第三方 API 实现元数据和成就管理。

---
## 10. [harvard-edge/cs249r_book](https://github.com/harvard-edge/cs249r_book)
- **语言**: Python
- **Stars**: 26,184
- **简介**: Machine Learning Systems

### AI 总结
**简介**: 由哈佛大学推出的开源教材项目，旨在系统教授人工智能系统工程（AI Engineering）的原理与实践，帮助学习者掌握构建高效、可靠、安全的端到端智能系统的方法。

**核心功能**:
- 提供完整的机器学习系统教材（在线版及2026年MIT Press纸质版），涵盖从理论到实践的全面内容
- 包含TinyTorch（轻量级深度学习框架）、Labs（实验教程）、MLSys·im（模拟器）等配套教学工具
- 支持多语言版本（中、日、韩等），并提供Slides、Instructor指南、StaffML等教学资源
- 集成CI/CD自动化验证流程，确保教材、实验、工具包的持续更新与质量

**技术亮点**: 基于Python生态，采用模块化设计将教材、实验、模拟器、轻量级框架整合为统一教学体系；通过GitHub Actions实现多组件自动化测试与部署；项目遵循CC-BY-NC-SA 4.0开源协议，支持社区协作与捐赠。

---
