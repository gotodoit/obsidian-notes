---
tags:
  - github-trending
  - daily
date: 2026-08-31
created: 2026-08-31T01:55:43.985Z
---

# 2026-08-31 GitHub Trending Top 10

## 1. [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC)
- **语言**: TypeScript
- **Stars**: 24,197
- **简介**: Open Multi-Agent Interactive Classroom — Get an immersive, multi-agent learning experience in just one click

### AI 总结
**简介**: OpenMAIC 是一个开源的多智能体交互式课堂平台，用户只需输入一句话提示词，即可自动生成完整的沉浸式课程内容。

**核心功能**:
- **一键课程生成**：通过单条提示词自动生成完整课程，涵盖课件、测验、互动练习、PBL 项目、图片、视频、语音等多种内容形式
- **Agent 工作台**：提供聊天式工作界面，可规划课程大纲、构建和修改每个页面，支持从用户上传的文档、音视频或网络搜索内容中提取素材
- **持久化会话**：服务端支持会话中断后恢复，可随时取消、暂停和继续课程构建流程
- **20+ 内置技能**：包括幻灯片、测验、互动组件、图像、视频、语音生成及 `.pptx` 导入等
- **OpenClaw 集成与 Lemonade 本地 AI**：支持外部工具集成和本地 AI 推理

**技术亮点**: 基于 Next.js 16、React 19、TypeScript 5、LangGraph 1.1 和 Tailwind CSS 4 构建；采用提供商中立设计，支持自定义模型、媒体、搜索服务和存储后端；支持 Vercel 一键部署。

---
## 2. [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- **语言**: Python
- **Stars**: 39,356
- **简介**: Turn any AI agent into an AI Scientist. The #1 Agent Skills library for science, used by 190,000+ scientists worldwide. 165 ready-to-use validated skills plus 100+ scientific databases covering biology, chemistry, medicine, and drug discovery. Compatible with Cursor, Claude Code, Codex, Pi, Antigravity, and the open Agent Skills standard.

### AI 总结
**简介**: 一个包含163个即用型科研技能和100+科学数据库的开源项目，可将任何AI代理转变为全能AI科学家，支持生物学、化学、医学和药物发现等领域。

**核心功能**:
- **163个验证过的科研技能**: 涵盖癌症基因组学、PK/PD建模、分子动力学、RNA速度分析、微生物组基础模型、地理空间科学、时间序列预测等
- **100+科学数据库集成**: 包括个体级1000 Genomes查询、监管序列预测、病原体变异监测、生物医学文献检索、药物-靶点结合等
- **多AI代理兼容**: 支持Cursor、Claude Code、Codex、Google Antigravity等遵循开放Agent Skills标准的工具
- **插件化部署**: 作为Agent Plugins包（plugin.json + skills/），可一键加载整个技能集合
- **配套工具K-Dense BYOK**: 免费开源的桌面端AI协同科学家，支持40+模型、本地数据存储和云端扩展

**技术亮点**: 基于开放Agent Skills标准构建，采用Python实现，通过GitHub Actions进行安全扫描和技能测试，同时支持Agent Skills和Agent Plugins双标准，具备便携式插件架构。

---
## 3. [Lakr233/vphone-cli](https://github.com/Lakr233/vphone-cli)
- **语言**: Swift
- **Stars**: 9,657
- **简介**: 

### AI 总结
**简介**: vphone-cli 是一个基于 Apple Virtualization.framework 和 PCC 研究虚拟机基础设施的工具，可在 Apple Silicon Mac 上启动虚拟 iPhone。

**核心功能**:
- 一键创建并启动完整的虚拟 iPhone 虚拟机（自动完成下载、补丁、DFU 恢复、CFW 安装和首次启动）
- 支持 5 种固件变体（`less`、`regular`、`dev`、`jb`、`exp`），提供从保留 iOS 安全机制到完整越狱（含 Sileo、TrollStore 自动安装）的渐进式安全绕过能力
- 提供完整的 VM 生命周期管理命令（创建、克隆、导出/导入、重命名、删除、配置 CPU/内存）
- 支持手动分步构建 VM（固件准备、补丁、DFU 恢复、CFW 安装）
- 支持通过 SSH（端口 22222）和 VNC（端口 5901）连接虚拟机
- 支持从本地 IPSW 文件更新到更新的 iOS 版本

**技术亮点**: 基于 Swift 开发，利用 Apple Virtualization.framework 实现硬件虚拟化；通过 SIP/AMFI 放宽获取私有 PV=3 权限；使用 APFS 克隆实现快速 VM 复制；支持 zstd/xz 压缩导出；所有数据存储在 `~/.vphone/` 下，可通过环境变量重定向。

---
## 4. [tt-a1i/archify](https://github.com/tt-a1i/archify)
- **语言**: JavaScript
- **Stars**: 34,838
- **简介**: Agent skill for beautiful, verifiable architecture, workflow, sequence, data-flow, and lifecycle diagrams—self-contained HTML with motion and crisp export.

### AI 总结
**简介**: Archify 是一个用于 Cursor、Claude Code 等 AI 编程助手的 Agent 技能，能将代码库或系统描述直接转换为精美的交互式系统架构图（HTML/SVG），支持在聊天中生成、审查和分享。

**核心功能**:
- **五种图表类型** — 支持架构、工作流、时序、数据流和生命周期图，提供四种预设风格、深/浅色主题及内置品牌标识
- **架构变更审查** — 对比两个验证快照，以 Before / Delta / After 视图精确展示新增、删除、修改、移动和重路由的事实
- **交互式探索** — 节点搜索、溯源验证、上下游路由追踪、角色对比，以及可播放的引导式故事（不虚构拓扑）
- **单文件输出与分享** — 生成自包含 HTML，并可导出 PNG、SVG、WebM 及 1200×630 分享卡片

**技术亮点**: 基于 Node.js 的确定性渲染与验证系统；Agent 生成类型化 JSON 中间表示（IR），由 Archify 编译为 HTML/SVG，确保输出可验证、可信任；无需仓库即可在任意 Agent 聊天中描述系统并生成图表。

---
## 5. [p-e-w/heretic](https://github.com/p-e-w/heretic)
- **语言**: Python
- **Stars**: 29,200
- **简介**: Fully automatic censorship removal for language models

### AI 总结
**简介**: Heretic 是一个全自动去除语言模型审查（安全对齐）的工具，无需昂贵的后训练即可实现模型去审查。

**核心功能**:
- **全自动去审查**: 自动寻找高质量的 abliteration 参数，无需理解 transformer 内部原理，只需运行命令行即可
- **保持模型智能**: 同时最小化拒绝回答数量和与原始模型的 KL 散度，在去除审查的同时最大程度保留原始模型的智能水平
- **内置评估功能**: 提供评估命令（如 `heretic --model ... --evaluate-model ...`），可复现模型去审查效果指标
- **广泛模型支持**: 支持大多数密集模型、多模态模型、多种 MoE 架构，以及 Qwen3.5 等混合模型

**技术亮点**: 结合了方向消融（directional ablation，即 "abliteration"）的先进实现与基于 Optuna 的 TPE 参数优化器，实现完全自动化的参数寻优。经测试，Heretic 生成的去审查模型在拒绝抑制效果上与人工作品相当，但 KL 散度更低（如 gemma-3-12b-it 上 KL 散度仅为 0.16，远低于人工 abliteration 的 0.45-1.04），表明对原始模型能力的损伤更小。

---
## 6. [unclecode/crawl4ai](https://github.com/unclecode/crawl4ai)
- **语言**: Python
- **Stars**: 80,260
- **简介**: 🚀🤖 Crawl4AI: Open-source LLM Friendly Web Crawler & Scraper. Don't be shy, join here: https://discord.gg/jP8KfhDhyN

### AI 总结
**简介**: Crawl4AI 是一个开源的、面向 LLM 友好的网络爬虫与数据抓取工具，能将网页内容转化为干净的 Markdown 格式，供 RAG、AI 代理和数据管道使用。

**核心功能**:
- **LLM 就绪输出**: 智能生成包含标题、表格、代码块和引用提示的结构化 Markdown
- **深度爬取与崩溃恢复**: 支持 `resume_state` 和 `on_state_change` 回调，可恢复长时间运行的爬取任务
- **预取模式**: `prefetch=True` 模式可将 URL 发现速度提升 5-10 倍
- **完全可控**: 支持会话管理、代理、Cookie、用户脚本和钩子函数
- **自适应智能**: 学习网站模式，只探索相关内容
- **安全加固**: 修复了 Docker API 的 RCE、SSRF、认证绕过等关键漏洞，默认启用认证
- **部署灵活**: 零密钥要求，支持 CLI 和 Docker API 服务器

**技术亮点**: 基于 Python 构建，使用异步浏览器池技术实现高性能抓取；采用 Playwright headless-shell 打包；支持 GPU 加速的 Docker 构建；提供 MemoryAdaptiveDispatcher 自适应调度器；内置 DomainMapper 域名映射功能；架构上以安全为默认（loopback 绑定、请求体作为不可信边界）。

---
## 7. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 60,523
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个由 AI 代理驱动的搜索工具，能并行搜索 Reddit、X、YouTube、HN、Polymarket 等平台，根据真实用户互动（点赞、投票、金钱下注）排序，并综合生成一份有依据的摘要简报。

**核心功能**:
- **跨平台并行搜索**: 同时检索 Reddit、X/Twitter、YouTube、TikTok、Instagram Reels、Hacker News、Polymarket 及 GitHub 等多个"围墙花园"平台，获取 Google 无法触及的内容。
- **人群评分排序**: 以 Reddit 点赞、X 喜欢、YouTube 字幕、TikTok 互动、Polymarket 真金白银的赔率等真实用户信号为排序依据，而非编辑推荐。
- **AI 代理综合简报**: 由 AI 代理作为"裁判"，将分散在各平台的碎片信息（如推文、帖子、播客转录）提炼成一份简洁、可操作的摘要。
- **零配置快速上手**: 开箱即用支持 Reddit、HN、Polymarket 和 GitHub；通过 30 秒的设置向导可解锁 X、YouTube、TikTok、arXiv 等更多数据源。
- **多宿主兼容**: 支持 Claude Code（推荐，自动更新）、Codex、Cursor、Copilot、Gemini CLI 等 50+ 支持 Agent Skills 的宿主，也可通过 npx 全局或项目级安装。

**技术亮点**: 采用 Agent Skills 规范（SKILL.md 为运行时源），允许用户自带 API 密钥和浏览器会话以桥接各平台封闭生态；支持多语言 README（含简体中文）。

---
## 8. [majd/ipatool](https://github.com/majd/ipatool)
- **语言**: Go
- **Stars**: 10,233
- **简介**: Command-line tool that allows searching and downloading app packages (known as ipa files) for iOS, iPadOS, tvOS, and visionOS from the App Store.

### AI 总结
**简介**: ipatool 是一个命令行工具，用于在 App Store 中搜索并下载 iOS、iPadOS、tvOS 和 visionOS 应用的 ipa 安装包文件。

**核心功能**:
- **搜索应用**: 通过关键词搜索 App Store 上的应用，支持按平台（iPhone、iPad、Apple TV、VisionOS）筛选并限制结果数量
- **账户认证**: 支持登录、查看当前账户信息以及撤销 App Store 凭据
- **获取应用许可**: 通过 bundle identifier 获取应用的许可证
- **列出已购应用**: 分页展示当前账户拥有的应用列表
- **查看可用版本**: 查询指定应用所有可下载的历史版本
- **下载 ipa 文件**: 通过应用 ID 或 bundle identifier 下载应用安装包，支持指定特定版本

**技术亮点**: 采用 Go 语言开发，支持 Windows、Linux 和 macOS 多平台；提供 JSON 输出格式和 non-interactive 模式，便于脚本自动化集成；支持通过 Homebrew 安装（macOS）。

---
## 9. [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)
- **语言**: Unknown
- **Stars**: 93,346
- **简介**: A collection of MCP servers.

### AI 总结
**简介**: 一个精选的 Model Context Protocol (MCP) 服务器资源列表，旨在通过标准化服务器实现扩展 AI 模型与本地及远程资源的交互能力。

**核心功能**:
- 收录大量生产级和实验性的 MCP 服务器实现，涵盖文件访问、数据库连接、API 集成等多种场景
- 提供详细的分类目录（如浏览器自动化、数据库、开发者工具、金融、安全等 40+ 类别），便于快速查找
- 支持多语言 README（英文、中文、日文、韩文等），并配有 Web 端目录（glama.ai/mcp/servers）与仓库同步
- 提供清晰的图例系统，标注服务器实现的语言（Python、TypeScript、Go、Rust 等）、范围（云服务/本地服务/嵌入式）及操作系统支持
- 包含 MCP 教程、社区资源（Reddit/Discord）和相关客户端列表链接

**技术亮点**: 基于 Model Context Protocol 开放协议，通过标准化服务器实现让 AI 模型安全地交互本地与远程资源；采用社区驱动维护模式，使用徽章系统标注多语言支持和实现细节，并同步维护 Web 目录。

---
## 10. [checkstyle/checkstyle](https://github.com/checkstyle/checkstyle)
- **语言**: Java
- **Stars**: 9,217
- **简介**: Checkstyle is a development tool to help programmers write Java code that adheres to a coding standard. By default it supports the Google Java Style Guide and Sun Code Conventions, but is highly configurable. It can be invoked with an ANT task and a command line program.

### AI 总结
**简介**: Checkstyle 是一个帮助 Java 开发者遵循编码标准的开发工具，默认支持 Google Java Style 和 Sun Code Conventions，且高度可配置。

**核心功能**:
- 代码风格检查：自动检测 Java 代码中不符合编码标准的违规项（如 switch 分支穿透等）
- 高度可配置：支持自定义检查规则和配置文件（XML 格式）
- 多种调用方式：支持命令行工具、ANT 任务以及 Maven/Gradle 构建集成
- 丰富的内置检查：涵盖命名规范、代码复杂度、重复代码、注释规范等多类检查项
- 支持主流 Java 风格指南：默认内置 Google Java Style Guide 和 Sun Code Conventions

**技术亮点**:
- 基于 Java 开发，使用 ANTLR 进行语法解析，Apache Commons 和 Google Guava 提供基础工具支持
- 通过 Picocli 实现命令行参数解析
- 提供完整的 API 文档（Javadoc）和 HTML 格式的配置文档
- 持续集成完善，支持多平台构建（AppVeyor、CircleCI、Azure 等）
- 开源免费，采用 GNU LGPL v2.1 许可证

---
