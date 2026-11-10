---
tags:
  - github-trending
  - daily
date: 2026-11-10
created: 2026-11-10T01:55:43.202Z
---

# 2026-11-10 GitHub Trending Top 10

## 1. [anthropics/skills](https://github.com/anthropics/skills)
- **语言**: Python
- **Stars**: 191,047
- **简介**: Public repository for Agent Skills

### AI 总结
**简介**: Anthropic 官方开源的 Claude Agent Skills 实现仓库，提供可动态加载的技能示例、规范与模板，帮助 Claude 以可重复的方式完成特定任务。

**核心功能**:
- 提供覆盖创意设计、开发技术、企业沟通及文档处理等多领域的技能示例集合
- 开源 Claude 文档能力背后的核心技能（docx、pdf、pptx、xlsx），可作为复杂生产级技能的参考
- 包含 Agent Skills 规范（spec）与技能模板（template），便于开发者创建自定义技能
- 支持在 Claude Code（插件市场）、Claude.ai 及 Claude API 中安装与使用

**技术亮点**: 每个技能为自包含文件夹，以 `SKILL.md`（YAML frontmatter + Markdown 指令）定义元数据与行为，结构简洁、易于扩展；主要语言为 Python，多数技能采用 Apache 2.0 开源协议。

---
## 2. [meta/astryx](https://github.com/meta/astryx)
- **语言**: TypeScript
- **Stars**: 20,208
- **简介**: An open source design system that's fully customizable and agent ready

### AI 总结
**简介**: Astryx 是 Meta 开源的设计系统，历经八年内部打磨（支撑 13000+ 应用），基于 React 19+ 与 StyleX 构建，兼顾人工开发与 AI 智能体协作。

**核心功能**:
- 提供 150+ 无障碍组件，涵盖品牌级主题定制、暗黑模式、开箱即用模板与 CLI 工具
- 开放式内部结构：组件可在任意层级组合，底层构建块直接导出，支持 swizzle 将组件源码弹出至项目自行掌控
- 无样式锁定：消费端可用 `className` 配合 Tailwind、CSS Modules 或原生 CSS 覆盖样式
- 主题即 CSS 自定义属性覆盖，无需 fork 或包裹组件源码即可完成深度定制
- API、文档与 CLI 协同设计，让人与 AI 助手基于同一参考以相同方式构建

**技术亮点**: 基于 React 19+（peer 依赖）与 StyleX 编写样式；无需构建插件、PostCSS 或 Babel 配置，仅需 CSS 导入加主题 Provider 即可接入；支持 Next.js、Tailwind、Vite 与 CDN；CLI 可全局或项目级安装，便于开发者与编码智能体可靠调用。

---
## 3. [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock)
- **语言**: Python
- **Stars**: 107,159
- **简介**: Hunt down social media accounts by username across social networks

### AI 总结
**简介**: 通过用户名在多个社交网络上追踪对应的社交媒体账号。

**核心功能**:
- 根据用户名在大量社交平台中搜索匹配的账号
- 支持批量查询与结果输出

**技术亮点**: 基于 Python 实现，便于扩展和命令行使用

---
## 4. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco)
- **语言**: C++
- **Stars**: 16,934
- **简介**: Multi-Joint dynamics with Contact. A general purpose physics simulator.

### AI 总结
**简介**: MuJoCo 是 Google DeepMind 维护的通用物理引擎，专注于多关节动力学与接触仿真，服务于机器人、生物力学、图形动画及机器学习等领域的研究与开发。

**核心功能**:
- 提供 C API，运行时仿真模块经性能调优，基于 XML 编译器预分配的低层数据结构运行
- 支持原生桌面窗口与浏览器中的交互式可视化
- 提供大量物理相关计算工具函数
- 提供 Python 绑定及 Unity 游戏引擎插件
- 附带 MuJoCo Studio 应用与经典 `simulate` 查看器
- 提供在线 IPython/Colab 教程，涵盖入门、模型编辑、多线程 rollout、LQR、最小二乘、MJX 及可微物理等主题

**技术亮点**: 采用 C++ 实现；提供基于 JAX 的 MuJoCo XLA（MJX）分支；支持从物理步进自动推导解析梯度的可微物理训练；可通过 WebAssembly 在浏览器中运行（速度慢于原生 C）。

---
## 5. [anthropics/claude-quickstarts](https://github.com/anthropics/claude-quickstarts)
- **语言**: Python
- **Stars**: 20,039
- **简介**: A collection of projects designed to help developers quickly get started with building deployable applications using the Claude API

### AI 总结
**简介**: 该项目是 Anthropic 官方提供的 Claude API 快速入门项目合集，帮助开发者快速构建可部署的 AI 应用。

**核心功能**:
- **Customer Support Agent**：基于 Claude 的客户支持智能体，接入知识库实现 AI 辅助客服
- **Financial Data Analyst**：通过对话分析财务数据，支持交互式数据可视化
- **Computer Use Demo / Best Practices**：演示 Claude 控制桌面电脑的能力，并提供原生 macOS 参考实现及可靠性、成本优化最佳实践
- **Browser Use Demo / Browser Toolset**：基于 Playwright 或 CDP 的浏览器自动化参考实现，支持网页导航、DOM 交互、内容提取和表单填写
- **Computer Toolset**：基于 VNC（RFB 协议）的最小化电脑工具集示例
- **Autonomous Coding Agent**：基于 Claude Agent SDK 的双智能体模式，可跨多个会话逐步构建完整应用
- **Managed Agents 系列**：包括 Chat SDK 聊天应用、CopilotKit + AG-UI 个人财务助手、每日简报定时智能体等

**技术亮点**: 以 Python 为主，部分示例提供 TypeScript 版本；覆盖工具调用（computer_toolset、browser_toolset）、Playwright/CDP/VNC 驱动、Claude Agent SDK、Managed Agents 持久会话、AG-UI 协议、提示缓存、沙箱 shell 等能力，并强调与官方最佳实践指南配套。

---
## 6. [garrytan/gbrain](https://github.com/garrytan/gbrain)
- **语言**: TypeScript
- **Stars**: 32,184
- **简介**: Garry's Opinionated OpenClaw/Hermes Agent Brain

### AI 总结
**简介**: GBrain 是 Y Combinator CEO Garry Tan 开源的、可自托管的 AI Agent 记忆层，为现有 Agent 提供带来源溯源、可修正、跨 Agent 共享的显式记忆。

**核心功能**:
- **显式记忆存储**：存储带来源的事实，支持修正与撤回，同一记忆可在多个 Agent 间共享
- **渐进式检索**：起步为无密钥的关键词检索，按需叠加语义搜索、综合归纳与后台增强
- **综合回答层**：跨人物、公司、交易与想法输出带引用的完整答案，并显式标注知识空白
- **类型化知识图谱**：本地写入时自动抽取关联（无需 LLM 调用），支持毫秒级广度优先关系遍历
- **多接入方式**：可嵌入现有 Agent、通过 MCP 经 Tailscale 远程暴露，或连接托管版 gbrain.io
- **技能与知识共存**：本地 brain 内置记忆技能，支持授权目录共享与受控发布

**技术亮点**:
- 使用 TypeScript 开发，MIT 协议，支持免费自托管
- 通过 MCP 协议与 ChatGPT、Claude、Cursor、Grok Bot 等客户端集成
- 远程访问基于来源/操作授权与可见性过滤的权限模型
- 生产验证规模：15.5 万页面、2.4 万人、5,340 家公司、66 个自主 cron 任务
- 关系检索将生产环境 R@5 从 0.6626 提升至 0.7241（BrainBench 基准）

---
## 7. [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser)
- **语言**: Rust
- **Stars**: 48,522
- **简介**: Browser automation CLI for AI agents

### AI 总结
**简介**: agent-browser 是 Vercel Labs 推出的原生 Rust 命令行工具，为 AI 智能体提供可逐步驱动的浏览器自动化能力。

**核心功能**:
- `snapshot` 将页面转为紧凑文本，并为每个元素分配 `@e1` 形式的引用，智能体据此执行点击等操作后再次读取页面验证结果
- 浏览器在多次命令间保持打开，每步只需一次简短的 shell 调用，形成“快照—操作—验证”的循环
- 支持 CSS 选择器、文本、XPath 及语义定位（如按角色和名称查找按钮）
- 点击目标若被隐藏、禁用、移出视口或被遮挡时会明确失败，而非误报成功
- 提供与 CLI 版本匹配的 skills 机制，可加载核心循环说明及 electron、slack 等专项技能

**技术亮点**:
- 原生 Rust 实现，通过后台守护进程经 Chrome DevTools Protocol 控制浏览器，每个 `--session` 拥有独立守护进程与浏览器
- 默认使用 Chrome for Testing，并支持连接已运行 Chrome（`--cdp`/`--auto-connect`）、Lightpanda/Obscura 引擎、iOS 模拟器 Mobile Safari 及 Browserbase 等云浏览器
- 守护进程空闲一小时后自动关闭无头浏览器，配置会话持久化时会先保存状态
- 可通过 npm、Homebrew 或 npx 安装，遵循 Apache-2.0 许可

---
## 8. [ruvnet/RuView](https://github.com/ruvnet/RuView)
- **语言**: Rust
- **Stars**: 103,498
- **简介**: π RuView turns commodity WiFi signals into real-time spatial intelligence, vital sign monitoring, and presence detection — all without a single pixel of video.

### AI 总结
**简介**: RuView 是一个基于 Rust 开发的 WiFi 感知平台，利用普通 WiFi 信号的信道状态信息（CSI）实现穿墙空间感知、生命体征监测和人体存在检测，无需任何摄像头或可穿戴设备。

**核心功能**:
- **存在与占用检测**：穿墙检测人员存在、统计人数、追踪进出动态
- **生命体征监测**：非接触式测量呼吸频率和心率（睡眠或静坐状态下）
- **活动识别**：识别行走等人体活动，并支持跌倒风险、离床、异常静止等语义状态推断
- **智能家居集成**：原生支持 Home Assistant（MQTT）、Apple Home/HomePod（HAP-1.1）、Google Home、Amazon Alexa 及 Matter 桥接，每节点提供 21 个实体和 3 个 HA Blueprint

**技术亮点**:
- 使用低成本 ESP32 传感器采集 CSI（信道状态信息），纯物理信号感知，无隐私视频采集
- 语言为 Rust，提供预训练模型（HuggingFace: wifi-densepose-pretrained）与 AI 工具链
- 支持 Siri、Google Assistant、Alexa 语音查询各房间人员存在与生命体征，无需自定义技能

---
## 9. [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis)
- **语言**: Python
- **Stars**: 68,910
- **简介**: LLM 驱动的多市场股票智能分析系统：多源行情、实时新闻、决策看板与自动推送，支持零成本定时运行。 LLM-powered multi-market stock analysis system with multi-source market data, real-time news, decision dashboard, automated notifications, and cost-free scheduled runs.

### AI 总结
**简介**: 一个由 LLM 驱动的多市场股票智能分析系统，可每日自动生成决策报告并推送到多个即时通讯平台，支持零成本定时运行。

**核心功能**:
- **AI 决策报告**：输出核心结论、评分、趋势判断、买卖点位、风险警报、催化因素与操作检查清单
- **多市场数据聚合**：覆盖 A股、港股、美股、日股、韩股、台股及 ETF，整合行情、K 线、技术指标、新闻、公告与基本面数据
- **Web / 桌面工作台**：支持手动分析、任务进度跟踪、历史报告查看、回测、持仓与配置管理，含浅色/深色主题
- **Agent 策略问股**：支持多轮追问，内置均线、缠论、波浪、趋势、热点等 15 种策略，覆盖 Web/Bot/API
- **智能导入与补全**：支持图片、CSV/Excel、剪贴板导入，以及股票代码/名称/拼音/别名补全
- **自动化与推送**：通过 GitHub Actions、Docker、本地定时任务或 FastAPI 服务运行，推送至企业微信、飞书、Telegram、Discord、Slack、邮箱

**技术亮点**:
- 语言为 Python 3.10+，采用 MIT 协议，提供 Docker 镜像与 GitHub Actions 开箱即用部署
- 兼容多种 LLM（Modelflare、AIHubMix、Gemini、OpenAI 兼容、DeepSeek、通义千问、Claude、Ollama 本地模型等）
- 行情数据源可插拔：AkShare、Tushare、Pytdx、Baostock、YFinance、Longbridge，默认免费源零配置运行
- 集成多家新闻搜索 API（Anspire、SerpAPI、Tavily、Bocha、Brave、MiniMax、SearXNG）及可选的美股社交舆情数据

---
## 10. [homeassistant-ai/ha-mcp](https://github.com/homeassistant-ai/ha-mcp)
- **语言**: Python
- **Stars**: 6,018
- **简介**: Configure and automate Home Assistant with Claude, ChatGPT, and other AI assistants.

### AI 总结
**简介**: HA-MCP 是一个基于 MCP 协议的 Home Assistant 服务器，让 Claude、ChatGPT 等 AI 助手能够配置和自动化 Home Assistant。

**核心功能**:
- 提供 87 个工具，覆盖 Home Assistant 的配置与自动化操作
- 通过 HACS 或 Home Assistant Marketplace 以集成方式安装，服务器在进程内运行
- 支持所有 Home Assistant 安装类型（OS、Supervised、Container、Core），功能完全一致
- 支持远程访问（Secret URL / Home Assistant 登录）与本地网络接入两种客户端连接方式
- 支持管理员令牌或专用账户认证

**技术亮点**: 使用 Python 开发，基于 FastMCP 框架构建；采用进程内服务器架构，通过 HACS 集成分发，并配备 E2E 测试工作流保障质量。

---
