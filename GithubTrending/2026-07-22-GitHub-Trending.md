---
tags:
  - github-trending
  - daily
date: 2026-07-22
created: 2026-07-22T01:55:43.322Z
---

# 2026-07-22 GitHub Trending Top 10

## 1. [koala73/worldmonitor](https://github.com/koala73/worldmonitor)
- **语言**: TypeScript
- **Stars**: 65,614
- **简介**: Real-time global intelligence dashboard. AI-powered news aggregation, geopolitical monitoring, and infrastructure tracking in a unified situational awareness interface

### AI 总结
**简介**: 一个基于AI的实时全球情报仪表盘，聚合新闻、地缘政治和基础设施数据，提供统一态势感知界面。

**核心功能**:
- AI驱动的新闻聚合与地缘政治监控
- 基础设施实时追踪与态势感知
- 多领域变体支持（科技、金融、大宗商品、能源等）
- 跨平台桌面客户端（Windows/macOS/Linux）
- 多语言SDK支持（npm/CLI、Python、Ruby、Go）

**技术亮点**: 使用TypeScript构建，提供Web应用、桌面客户端及多语言API接口，支持MCP协议集成。

---
## 2. [bojieli/ai-agent-book](https://github.com/bojieli/ai-agent-book)
- **语言**: Python
- **Stars**: 14,741
- **简介**: 《深入理解 AI Agent：设计原理与工程实践》（李博杰 著）开源主仓库：全书正文、编译版 PDF 与按章配套代码

### AI 总结
**简介**: 《深入理解 AI Agent：设计原理与工程实践》开源书籍仓库，系统讲解 AI Agent 从基础原理到生产级工程实践的完整知识体系。

**核心功能**:
- 提供全书 10 章正文、编译版 PDF/EPUB 电子书及 88 个配套实验代码
- 支持中文、英文、中文繁体、泰米尔语、越南语共 5 种语言版本
- 按章组织代码项目（70+ 可独立运行），覆盖上下文工程、工具、评估、后训练等核心主题

**技术亮点**:
- 核心公式 "Agent = LLM + 上下文 + 工具" 贯穿全书，理论与实践紧密结合
- 代码项目涵盖 MCP 协议、RAG 知识库、Coding Agent、多 Agent 协作等前沿技术
- 提供 API 密钥申请指南（Kimi、智谱、Siliconflow、火山引擎、OpenRouter），方便读者上手实践

---
## 3. [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph)
- **语言**: Python
- **Stars**: 24,599
- **简介**: Local-first code intelligence graph for MCP and CLI. Builds a persistent map of your codebase so AI coding tools read only what matters, with benchmarked context reductions on reviews and large-repo workflows.

### AI 总结
**简介**: code-review-graph 是一个本地优先的代码智能图工具，通过 Tree-sitter 构建代码结构映射，为 AI 编码工具提供精准上下文，大幅减少 Token 消耗。

**核心功能**:
- 构建持久化代码结构图，支持增量更新
- 通过 MCP 协议为 AI 工具提供精准代码上下文
- 一键安装配置，自动检测并适配 Codex、Claude Code、Cursor、Windsurf、GitHub Copilot 等 14+ 主流 AI 编码平台
- 支持 Git 和 SVN 项目，提供对称的卸载命令

**技术亮点**: 基于 Tree-sitter 解析引擎构建代码结构图，支持 Python 3.10+，通过 MCP (Model Context Protocol) 实现与 AI 工具的标准化集成，实测在 6 个真实仓库中实现 38 倍至 528 倍的 Token 缩减。

---
## 4. [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)
- **语言**: Unknown
- **Stars**: 6,922
- **简介**: A skill for your coding agent to stop it from burying the answer. ADHD-friendly output.

### AI 总结
**简介**: 一个针对编程助手的技能包，让AI输出更简洁直接，避免冗长铺垫，适合注意力不易集中的人群。

**核心功能**:
- 强制AI直接输出下一步行动，而非解释性废话
- 多步骤任务自动编号，清晰可执行
- 每轮对话结束时给出一个具体的下一步操作
- 抑制无关的联想和建议，聚焦当前任务
- 每次对话重新陈述当前状态，避免遗忘上下文
- 提供具体的时间估算（如“3分钟”而非“一会儿”）
- 让进展和成果可视化，增强成就感
- 错误反馈直白、不修饰
- 列表项限制在5条以内，避免信息过载
- 禁止使用“希望这能帮到你”等客套收尾

**技术亮点**:
- 支持Claude Code和Codex等主流编程助手
- 通过插件市场安装，无需本地克隆即可使用
- 规则可自定义：Fork后修改SKILL.md文件即可调整个性化输出风格

---
## 5. [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad)
- **语言**: JavaScript
- **Stars**: 9,167
- **简介**: A collection of agent skills for CAD, robotics and hardware design

### AI 总结
**简介**: 一个为 CAD、机器人和硬件设计提供智能体技能库的开源项目，支持通过自然语言生成和编辑 3D 模型及机器人描述文件。

**核心功能**:
- 通过自然语言或图像请求创建/编辑 CAD 模型，支持 STEP、STL、3MF、GLB 等格式导出
- 提供 CAD 模型、G-code 和机器人文件的本地浏览器预览
- 查找标准 STEP 零件（如螺丝、轴承、电机等）
- 生成 2D DXF 图纸（轮廓、模板、垫片等）
- 创建机器人 URDF 文件（关节、惯性、网格等）
- 为 URDF 添加 MoveIt 规划组、末端执行器和碰撞规则
- 生成 SDF 仿真模型和场景（含物理、传感器、灯光）
- 检查 DXF/STEP 文件并上传至 SendCutSend
- 将网格文件切片为 FDM 打印机 G-code
- 支持 Bambu Lab 打印机的验证、上传和打印控制

**技术亮点**: 基于 Python 3.11+ 开发，采用模块化技能架构，支持多种行业标准格式（STEP/URDF/SDF/SRDF），集成 CAD 预览器和 3D 打印切片功能。

---
## 6. [1jehuang/jcode](https://github.com/1jehuang/jcode)
- **语言**: Rust
- **Stars**: 10,342
- **简介**: The most intelligent agent harness for code

### AI 总结
**简介**: jcode 是一个用 Rust 构建的高性能、可无限定制的下一代编码代理工具，专为多会话工作流设计。

**核心功能**:
- 支持多会话工作流，可同时运行多个编码会话
- 提供极致的资源效率和性能优化，内存占用显著低于同类工具
- 支持 macOS、Linux 和 Windows 平台，提供一键安装脚本

**技术亮点**: 使用 Rust 语言开发，内存占用极低（单会话 27.8 MB，10 会话 117 MB），启动速度快，性能远超 Claude Code、Cursor Agent 等同类工具。

---
## 7. [oblien/openship](https://github.com/oblien/openship)
- **语言**: TypeScript
- **Stars**: 6,266
- **简介**: Self-hosted deployment platform

### AI 总结
**简介**: Openship 是一个开源、可自托管的部署平台，内置 CI/CD，支持通过桌面应用、Web 仪表盘或 CLI 管理应用和基础设施。

**核心功能**:
- 内置 CI/CD：支持推送即部署、预览环境、回滚等
- 全栈支持：Node、Python、Go、Rust、PHP、Ruby、Java、.NET、Docker、Monorepo 等
- 完整后端服务：Postgres、MySQL、MongoDB、Redis、WebSockets、存储等
- 域名与 SSL：自动 Let's Encrypt 证书、通配符域名、自动续期
- CDN：边缘缓存、HTTP/3、Brotli 压缩、即时清除
- 邮件服务器：内置 SMTP，支持 DKIM/SPF/DMARC，无需第三方服务
- 备份：定时备份数据库和卷，一键恢复
- 实时监控：实时构建日志、容器指标和资源使用情况
- 可扩展性：云端自动扩展，自托管支持多节点
- 可移植性：标准 Docker 容器，可在不同提供商间迁移
- 支持 Docker Compose 直接部署

**技术亮点**: 采用 TypeScript 开发，提供桌面应用、Web 仪表盘、CLI 三种界面，以及 REST API 和 MCP（AI 代理协议）用于集成与自动化。支持零配置部署，自动检测技术栈并构建配置。可部署到任意 Linux 服务器（VPS、裸金属、多节点）或 Openship Cloud 托管服务。

---
## 8. [AstrBotDevs/AstrBot](https://github.com/AstrBotDevs/AstrBot)
- **语言**: Python
- **Stars**: 37,485
- **简介**: AI Agent Assistant & development framework that integrates lots of IM platforms, LLMs, plugins and AI feature, and can be your openclaw alternative. ✨

### AI 总结
**简介**: AstrBot 是一个开源的全能 AI Agent 聊天机器人平台，集成主流即时通讯应用，帮助个人、开发者和团队快速构建生产级 AI 应用。

**核心功能**:
- 支持 AI 大语言模型对话、多模态、Agent、MCP、技能、知识库、角色设定和自动上下文压缩
- 集成 Dify、阿里云百炼、Coze 等 Agent 平台
- 多平台支持：QQ、企业微信、飞书、钉钉、微信公众号、Telegram、Slack 等
- 插件扩展系统，提供 1000+ 插件一键安装
- Agent 沙箱功能，确保安全运行

**技术亮点**: 基于 Python 3.12+ 开发，支持 Docker 部署，提供完整的文档和插件市场，采用模块化架构设计，易于扩展和定制。

---
## 9. [every-app/open-seo](https://github.com/every-app/open-seo)
- **语言**: TypeScript
- **Stars**: 6,621
- **简介**: Open source alternative to Semrush and Ahrefs

### AI 总结
**简介**: OpenSEO 是一个开源的 SEO 工具，旨在作为 Semrush 和 Ahrefs 的轻量级、高性价比替代方案，支持自托管和 AI 代理集成。

**核心功能**:
- 关键词研究、排名追踪、竞争对手分析、反向链接、网站审计和 AI 可见性分析。
- 内置 MCP 服务器，可与 Claude Code、OpenClaw 等 AI 代理连接，提供可复用的 SEO 工作流。
- 提供托管版本（$10/月）和自托管选项（Docker 或 Cloudflare），仅需 DataForSEO API 密钥即可按需付费。

**技术亮点**: 基于 TypeScript 构建，采用模块化架构，支持通过 MCP 协议与 AI 代理交互，并支持 Docker 和 Cloudflare 两种自托管方案，便于定制和扩展。

---
## 10. [tradesdontlie/tradingview-mcp](https://github.com/tradesdontlie/tradingview-mcp)
- **语言**: JavaScript
- **Stars**: 4,854
- **简介**: AI-assisted TradingView chart analysis — connect Claude Code to your TradingView Desktop for personal workflow automation

### AI 总结
**简介**: 一个将 Claude Code 连接到本地 TradingView Desktop 应用的开源桥接工具，通过 Chrome DevTools 协议实现 AI 辅助图表分析与工作流自动化。

**核心功能**:
- **Pine Script 开发** — 在 AI 辅助下编写、注入、编译、调试和迭代脚本
- **图表操作** — 切换品种、时间周期、缩放日期、添加/删除指标
- **视觉分析** — 读取图表指标值、价格水平与注释
- **绘图工具** — 绘制趋势线、水平线、矩形、文本标注
- **警报管理** — 创建、列出、删除价格警报
- **回放练习** — 逐步回放历史K线，模拟交易操作
- **截图捕获** — 捕捉图表状态供 AI 视觉分析
- **多窗格布局** — 设置 2x2、3x1 等网格布局，每个窗格可加载不同品种
- **实时监控** — 通过 JSONL 流式输出本地图表数据
- **CLI 支持** — 所有 MCP 工具均可作为 `tv` 命令行使用，支持管道与 JSON 输出

**技术亮点**:
- 基于 Chrome DevTools Protocol (CDP) 与本地 Electron 应用通信，所有数据处理均在本地完成
- 采用 MCP (Model Context Protocol) 架构，使 LLM 代理能通过结构化工具 API 操控桌面端金融应用
- 不连接 TradingView 服务器、不存储或传输市场数据、不绕过付费限制，仅作为人机协作的接口层

---
