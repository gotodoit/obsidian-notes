---
tags:
  - github-trending
  - daily
date: 2026-07-15
created: 2026-07-15T01:55:43.525Z
---

# 2026-07-15 GitHub Trending Top 10

## 1. [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)
- **语言**: Python
- **Stars**: 120,863
- **简介**: 100+ AI Agent & RAG apps you can actually run — clone, customize, ship.

### AI 总结
**简介**: 一个包含 100 多个可实际运行的 AI Agent 和 RAG 应用的开放源码项目，支持克隆、自定义和部署。

**核心功能**:
- 提供多种 AI 代理技能，如项目墓地分析、自我改进代理技能等
- 包含入门级 AI 代理模板，如博客转播客、数据分析、医疗影像分析等
- 支持语音 AI 代理、高级单代理和多代理应用
- 提供始终在线的代理功能，如 Hacker News 简报代理

**技术亮点**: 基于 Python 开发，兼容 Claude、Gemini、GPT、DeepSeek、Llama、Qwen 等多种模型，采用 Apache-2.0 开源协议，支持 Streamlit 快速部署和 npx 一键安装代理技能。

---
## 2. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 170,347
- **简介**: Skills for Real Engineers. Straight from my .claude directory.

### AI 总结
**简介**: 一个为真实工程师设计的、可组合的AI编码代理技能集，旨在解决常见开发失败模式，提升工程效率。

**核心功能**:
- **快速安装**: 通过 `npx skills@latest add` 命令30秒快速安装，并支持作为 Claude Code 插件一键安装。
- **对齐与引导**: 提供 `/grill-me` 和 `/grill-with-docs` 技能，通过详细提问帮助开发者与代理对齐需求，避免误解。
- **工作流集成**: 支持 `/setup-matt-pocock-skills` 一键配置，可绑定 GitHub、Linear 或本地文件作为问题追踪器，并支持标签分类。
- **可定制与可组合**: 技能设计小巧、易于适配和组合，支持通过 skills.sh 复制到项目中进行修改，或通过插件保持只读更新。

**技术亮点**: 基于 Shell 脚本实现，兼容 Claude Code、Codex 等多种编码代理，提供 skills.sh 和插件两种安装哲学，满足不同定制需求。

---
## 3. [Dicklesworthstone/destructive_command_guard](https://github.com/Dicklesworthstone/destructive_command_guard)
- **语言**: Rust
- **Stars**: 4,429
- **简介**: The Destructive Command Guard (dcg) is for blocking dangerous git and shell commands from being executed by agents.

### AI 总结
**简介**: dcg (Destructive Command Guard) 是一款高性能的钩子程序，用于在 AI 编码代理执行前拦截并阻止破坏性的 git 和 shell 命令，保护工作成果免遭意外删除。

**核心功能**:
- **零配置保护**: 开箱即用，自动拦截危险的 git 和文件系统命令。
- **50+ 安全包**: 覆盖数据库、Kubernetes、Docker、AWS/GCP/Azure、Terraform 等多种场景。
- **Heredoc/内联脚本扫描**: 能够检测并阻止内嵌在 Python 命令 (`python -c "os.remove(...)"`) 或 shell 脚本中的破坏性操作。
- **智能上下文检测**: 区分对危险命令的引用（如 `grep "rm -rf"`）与实际执行（如 `rm -rf /`），避免误报。
- **丰富的终端输出**: 在 stderr 上提供人性化的拒绝面板、规则上下文和建议，同时在 stdout 上输出机器可读信息，兼容 CI 环境。

**技术亮点**: 使用 Rust 语言开发，采用 SIMD 加速过滤技术实现亚毫秒级延迟。支持 Linux、macOS 和 Windows (WSL/原生) 平台，并可通过一键安装脚本自动配置 Claude Code、Codex CLI、Gemini CLI、GitHub Copilot CLI 等多种主流 AI 编码代理的钩子。

---
## 4. [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut)
- **语言**: TypeScript
- **Stars**: 69,258
- **简介**: The open-source CapCut alternative

### AI 总结
**简介**: OpenCut 是一款免费开源的视频编辑器，支持 Web、桌面和移动端，旨在成为 CapCut 的替代品。

**核心功能**:
- 提供编辑器 API，支持第三方插件（基于插件优先架构）
- 支持桌面、移动端和浏览器多平台（基于 Rust 核心）
- 内置 MCP 服务器（AI 代理支持）
- 支持无头模式（自动化、批量渲染）
- 编辑器内集成脚本面板

**技术亮点**: 使用 TypeScript 开发，核心采用 Rust 实现跨平台统一代码库；支持插件优先架构和 MCP 服务器；提供 API 和无头模式便于自动化集成。

---
## 5. [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund)
- **语言**: Python
- **Stars**: 61,894
- **简介**: An AI Hedge Fund Team

### AI 总结
**简介**: 一个基于AI的模拟对冲基金系统，通过多个投资大师风格的智能体协作生成交易决策，仅用于教育和研究目的。

**核心功能**:
- 集成19个不同投资风格的AI智能体（如巴菲特、芒格、索罗斯等），模拟多种投资策略
- 支持股票内在价值估值、市场情绪分析、基本面和技术指标分析
- 提供风险管理和投资组合管理功能，自动生成交易信号和订单
- 支持命令行和Web界面两种运行方式
- 可配置多种LLM（如OpenAI、Groq等）和金融数据API

**技术亮点**: 采用多智能体协作架构，每个智能体模拟知名投资者的决策逻辑；支持本地LLM运行（通过Ollama）；使用Poetry管理依赖；提供完整的回测、模拟交易和实盘交易功能（正在开发中）。

---
## 6. [Nutlope/hallmark](https://github.com/Nutlope/hallmark)
- **语言**: CSS
- **Stars**: 6,193
- **简介**: Anti-AI-slop design skill for Claude Code, Cursor, and Codex.

### AI 总结
**简介**: Hallmark 是一个专为 Claude Code、Cursor 和 Codex 设计的 CSS 设计技能，旨在生成看起来不像是 AI 生成的网页界面。

**核心功能**:
- **生成新 UI**: 自动为需求选择宏观结构，应用 20 种主题之一，并通过 57 个“AI 味”检测门和自检机制，确保输出不落入 AI 模型的常见模式。
- **审计 (`hallmark audit`)**: 对现有代码进行评分，指出其存在的“AI 味”反模式，但不修改代码。
- **重设计 (`hallmark redesign`)**: 保留原有内容、信息架构和品牌，但彻底重构布局和视觉风格。
- **学习 (`hallmark study`)**: 从指定的截图或 URL 中提取优秀设计的“DNA”（如宏观结构、字体搭配、色彩锚点），并拒绝像素级克隆，可生成可移植的 `design.md` 文件。

**技术亮点**: 使用纯 CSS 实现，每个页面都是独立的 HTML + CSS 文件。核心在于一套包含 57 个规则的“AI 味”检测系统，以及根据需求动态选择主题和结构的生成策略，而非使用固定模板。

---
## 7. [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading)
- **语言**: Python
- **Stars**: 22,890
- **简介**: "Vibe-Trading: Your Personal Trading Agent"

### AI 总结
**简介**: Vibe-Trading 是一个个人交易智能体，通过一条命令即可赋予智能体全面的交易能力。

**核心功能**:
- 支持多种数据源与历史数据回测，包括 Longbridge、Tushare 等，并具备数据完整性检查
- 提供 MCP 服务器，支持 Streamable HTTP、文件写入恢复、相关性请求认证等现代传输协议
- 内置回测沙箱，具备 AST 加固的安全机制，阻止网络、子进程、eval、os.environ 等不安全操作
- 支持 NVIDIA NIM 作为一级提供商，Web 设置和 CLI 均可配置
- 提供 Shadow Account 影子账户功能，用于模拟交易

**技术亮点**: Python 3.11+、FastAPI 后端、React 19 前端；支持多语言文档（英文、中文、日文、韩文、阿拉伯文）；采用 Docker 多阶段构建与摘要固定镜像，实现安全加固；提供 PyPI 安装包，支持 Web 设置持久化配置。

---
## 8. [Raphire/Win11Debloat](https://github.com/Raphire/Win11Debloat)
- **语言**: PowerShell
- **Stars**: 51,735
- **简介**: A simple, lightweight PowerShell script that allows you to remove pre-installed apps, disable telemetry, as well as perform various other changes to declutter and customize your Windows experience. Win11Debloat works for both Windows 10 and Windows 11.

### AI 总结
**简介**: 一个轻量级的 PowerShell 脚本，用于一键移除 Windows 10/11 预装应用、禁用遥测并优化系统体验。

**核心功能**:
- 移除预装应用（如 Xbox、Cortana 等），并支持通过 Microsoft Store 恢复
- 禁用遥测、诊断数据、活动历史、应用启动跟踪和定向广告
- 关闭 Windows、锁屏及 Microsoft 产品中的提示、建议和广告

**技术亮点**: 纯 PowerShell 实现，无需安装；提供交互式菜单和命令行参数支持；兼容 Windows 10 和 11，支持审计模式和多用户设置；可导出/导入配置实现批量部署。

---
## 9. [hasaneyldrm/exercises-dataset](https://github.com/hasaneyldrm/exercises-dataset)
- **语言**: HTML
- **Stars**: 13,556
- **简介**: 1,324-exercise fitness dataset — animation GIFs, 180×180 thumbnails, muscle-group & equipment data, and step-by-step instructions in 6 languages. The exercise data layer behind the LogPress app.

### AI 总结
**简介**: 一个包含 1,324 个健身动作的综合数据集，为 LogPress 应用提供数据层支持，并提供动画 GIF、缩略图、详细元数据和多语言指导。

**核心功能**:
- **1,324 个健身动作数据**：包含每个动作的类别、身体部位、所需器材、目标肌群与辅助肌群等详细元数据。
- **动画与缩略图**：每个动作都配有动画 GIF 和 180×180 的缩略图。
- **多语言指导**：提供英语、西班牙语、意大利语、土耳其语、俄语、中文、印地语、波兰语和韩语共 9 种语言的分步指导。
- **交互式浏览器**：提供 `index.html` 文件，支持实时搜索、按类别/器材/目标肌群筛选，以及无限滚动浏览。
- **开发者集成指南**：提供 `setup.html` 文件，包含数据库建表 SQL（支持多种数据库）、多种编程语言的 API 集成示例代码，以及用于 LLM 的结构化提示词。

**技术亮点**: 纯前端交互（HTML/JS），无需服务器即可使用；数据结构化清晰，便于直接集成到健身应用中。

---
## 10. [penpot/penpot](https://github.com/penpot/penpot)
- **语言**: Clojure
- **Stars**: 56,174
- **简介**: Penpot: The open-source design platform for Product teams that need scalable collaboration.

### AI 总结
**简介**: Penpot 是一个开源的设计平台，专为需要可扩展协作的产品团队打造，让团队完全拥有设计基础设施的控制权。

**核心功能**:
- 支持自托管和浏览器使用，基于 SVG、CSS、HTML、JSON 等开放标准
- 实时协作，帮助团队规模化并拉近设计与产品的距离
- 原生设计令牌（Design Tokens），提供设计与开发之间的单一事实来源
- MCP 服务器实现设计与代码之间的多向工作流
- 强大的开放 API 和插件系统，支持自动化、AI 驱动工作流和集成
- CSS Grid 和 Flex 布局，支持设计响应式界面

**技术亮点**: 使用 Clojure 语言开发，采用代码化设计方法，使设计对开发者和 AI 可读，支持通过 MCP 服务器直接翻译为代码。

---
