---
tags:
  - github-trending
  - daily
date: 2026-06-27
created: 2026-06-27T01:55:44.299Z
---

# 2026-06-27 GitHub Trending Top 10

## 1. [simplex-chat/simplex-chat](https://github.com/simplex-chat/simplex-chat)
- **语言**: Haskell
- **Stars**: 12,626
- **简介**: SimpleX - the first messaging network operating without user identifiers of any kind - 100% private by design! iOS, Android and desktop apps 📱!

### AI 总结
**简介**: SimpleX 是首个完全去中心化、不依赖任何用户标识符（如手机号、邮箱）的隐私优先消息网络，支持 iOS、Android 和桌面端。

**核心功能**:
- 无任何用户标识符：无需手机号、邮箱或用户名即可建立连接，保护元数据隐私。
- 端到端加密：采用双重棘轮加密协议，并附加额外加密层保障消息安全。
- 多平台支持：提供 iOS、Android 原生应用及 Linux/MacOS/Windows 终端命令行工具。
- 群组与目录：用户可通过 SimpleX 目录创建或加入群组，支持 bot 自动管理。

**技术亮点**: 基于 Haskell 语言开发，架构设计强调隐私保护（无用户标识符、元数据零泄露），通过双重加密层和去中心化消息中继（SMP 协议）实现抗审查通信。

---
## 2. [google-labs-code/design.md](https://github.com/google-labs-code/design.md)
- **语言**: TypeScript
- **Stars**: 21,312
- **简介**: A format specification for describing a visual identity to coding agents. DESIGN.md gives agents a persistent, structured understanding of a design system.

### AI 总结
**简介**: DESIGN.md 是一种为编码代理描述视觉标识的格式规范，旨在为设计系统提供持久、结构化的理解。

**核心功能**:
- 通过YAML front matter定义机器可读的设计令牌（如颜色、排版、间距等）
- 通过Markdown正文提供人类可读的设计原理说明
- 支持lint验证：检查令牌引用、WCAG对比度，输出结构化JSON结果
- 支持diff对比：检测两个版本设计系统间的令牌级和文本级差异

**技术亮点**: 基于TypeScript开发，提供CLI工具（`npx @google/design.md`），支持令牌引用（如`{colors.primary}`）和组件变体（如`button-primary-hover`）表达。

---
## 3. [commaai/openpilot](https://github.com/commaai/openpilot)
- **语言**: Python
- **Stars**: 61,799
- **简介**: openpilot is an operating system for robotics. Currently, it upgrades the driver assistance system on 300+ supported cars.

### AI 总结
**简介**: openpilot 是一个开源的机器人操作系统，目前可为300多款车型升级辅助驾驶系统。

**核心功能**:
- 支持300+款车型的辅助驾驶功能升级
- 提供多个预构建分支（稳定版、测试版、每日构建版等）
- 支持 comma four 等硬件设备即插即用
- 提供完整的开发工具链和社区贡献机制

**技术亮点**:
- 基于 Python 开发，遵循 ISO26262 功能安全标准
- 使用 C 语言实现安全模型代码（panda 模块）
- 每项提交都经过软件在环测试
- 提供开源工具集（openpilot tools）和完整的 API 文档

---
## 4. [kunchenguid/no-mistakes](https://github.com/kunchenguid/no-mistakes)
- **语言**: Go
- **Stars**: 3,446
- **简介**: git push no-mistakes

### AI 总结
**简介**: 一个本地 Git 代理工具，在推送代码前自动运行 AI 驱动的验证流水线，确保所有检查通过后才推送并创建 PR。

**核心功能**:
- **隔离验证**：在独立的 disposable worktree 中运行验证流水线，不干扰当前工作
- **AI 驱动流水线**：自动执行 review、test、docs、lint 等检查，安全修复自动应用，需要人工判断的问题会升级处理
- **三种触发方式**：通过 `git push no-mistakes`、`no-mistakes` TUI 或 `/no-mistakes` 代理技能触发
- **多代理支持**：兼容 claude、codex、copilot 等主流 AI 编码代理
- **自动 PR**：所有检查通过后自动推送并创建干净的 PR

**技术亮点**: 使用 Go 语言开发，支持 macOS/Linux/Windows 多平台，采用本地 Git 代理架构实现非阻塞验证。

---
## 5. [grafana/grafana](https://github.com/grafana/grafana)
- **语言**: TypeScript
- **Stars**: 74,920
- **简介**: The open and composable observability and data visualization platform. Visualize metrics, logs, and traces from multiple sources like Prometheus, Loki, Elasticsearch, InfluxDB, Postgres and many more.

### AI 总结
**简介**: Grafana 是一个开源的可观测性和数据可视化平台，支持从 Prometheus、Loki、Elasticsearch 等多种数据源查询、可视化、告警和分析指标、日志及链路数据。

**核心功能**:
- **可视化**: 提供灵活快速的客户端图表及多种面板插件，支持各类指标和日志的展示。
- **动态仪表盘**: 通过模板变量创建可复用的动态仪表盘，顶部提供下拉选择器。
- **探索指标**: 支持即席查询和动态下钻，可并排比较不同时间范围、查询和数据源。
- **探索日志**: 从指标无缝切换到日志，保留标签过滤，支持快速搜索或实时流式查看。
- **告警**: 可视化定义告警规则，持续评估并发送通知到 Slack、PagerDuty 等系统。
- **混合数据源**: 同一图表中混合使用不同数据源，支持按查询指定数据源。

**技术亮点**: 基于 TypeScript 和 Go 构建，采用插件化架构，支持自定义数据源和面板插件，社区活跃，提供丰富的文档和贡献指南。

---
## 6. [ripienaar/free-for-dev](https://github.com/ripienaar/free-for-dev)
- **语言**: HTML
- **Stars**: 123,752
- **简介**: A list of SaaS, PaaS and IaaS offerings that have free tiers of interest to devops and infradev

### AI 总结
**简介**: 这是一个为开发者和运维人员整理的、提供永久免费层的SaaS/PaaS/IaaS服务清单，涵盖云平台、数据分析、CI/CD等基础设施工具。

**核心功能**:
- 按类别（如云服务商、CI/CD、监控、存储等）列出超过50类免费服务
- 每个服务附有具体免费额度说明（如GCP的e2-micro实例、Firestore每日读写限制）
- 严格筛选：仅收录提供长期（≥1年）免费层的托管服务，排除自托管方案和短期试用
- 社区驱动：由1600+贡献者通过Pull Request持续更新

**技术亮点**: 分类清晰（含“生成式AI”“低代码平台”等新兴类别），且从安全角度要求免费层必须支持SSO和TLS。

---
## 7. [opendatalab/MinerU](https://github.com/opendatalab/MinerU)
- **语言**: Python
- **Stars**: 70,449
- **简介**: Transforms complex documents like PDFs and Office docs into LLM-ready markdown/JSON for your Agentic workflows.

### AI 总结
**简介**: MinerU 是一个将复杂文档（如 PDF、Office 文件）转换为 LLM 就绪的 Markdown 或 JSON 格式的开源工具，专为智能代理工作流设计。

**核心功能**:
- 支持 PDF 和 Office 文档的解析与格式转换
- 输出 LLM 可直接处理的 Markdown 或 JSON 数据
- 提供 Web 应用和 HuggingFace 在线演示

**技术亮点**: 基于 Python 开发，集成文档解析与结构化输出能力，适用于 AI 工作流数据预处理。

---
## 8. [alchaincyf/zhangxuefeng-skill](https://github.com/alchaincyf/zhangxuefeng-skill)
- **语言**: Unknown
- **Stars**: 9,266
- **简介**: 张雪峰.skill — 张雪峰的认知操作系统。高考志愿/考研/职业规划的实战思维框架。由女娲.skill生成。

### AI 总结
**简介**: 张雪峰的认知操作系统，一个可运行的思维框架，而非简单的语录合集。

**核心功能**:
- **高考志愿/考研/职业规划咨询**: 基于张雪峰的思维模型，提供个性化、接地气的择校、选专业、职业发展建议。
- **心智模型驱动**: 内置“社会筛子论”、“就业倒推法”、“阶层现实主义”、“不可替代性检验”等核心模型，分析问题而非复读语录。
- **多场景应用**: 覆盖高考、考研、AI时代职业规划、家庭条件与理想选择等多种现实场景。

**技术亮点**:
- **Agent Skills 协议**: 基于开放的 Agent Skills 标准开发，可跨平台运行（Claude Code、Codex、Cursor 等50+ runtime）。
- **一键安装**: 支持 `npx skills add` 命令自动安装，兼容主流AI agent运行时。
- **深度调研提炼**: 基于5本著作、15+篇深度采访、30+条语录和完整人生时间线，提炼出核心心智模型与表达DNA。

---
## 9. [mauriceboe/TREK](https://github.com/mauriceboe/TREK)
- **语言**: TypeScript
- **Stars**: 7,683
- **简介**: A self-hosted travel/trip planner with real-time collaboration, interactive maps, PWA support, SSO, budgets, packing lists, and more.

### AI 总结
**简介**: TREK 是一款自托管的实时协作旅行规划工具，集成了地图、预算、行李清单、日记和 AI 功能。

**核心功能**:
- **行程规划**: 支持拖拽式日计划、交互式地图（Leaflet/Mapbox GL，含3D建筑、路线可视化）、地点搜索（Google Places/OpenStreetMap）、地点导入（Google Maps/Naver Maps列表、GPX/KML等文件）、日备注、路线优化、天气预报（16天）和分类筛选。
- **旅行管理**: 预订管理（航班、住宿等，支持从邮件/PDF导入）、费用追踪与分摊（Splitwise风格）、行李清单（分类、模板、用户分配）、旅行日记和已访问国家地图集。
- **协作与部署**: 支持实时协作、PWA、SSO单点登录，并提供Docker镜像，可自托管部署。

**技术亮点**: 使用 TypeScript 开发，基于 Docker 部署，集成了 Leaflet/Mapbox GL 地图、Google Places/OpenStreetMap 地点搜索、Open-Meteo 天气 API、KDE Itinerary 预订导入，并支持 AGPL v3 开源许可。

---
## 10. [xbtlin/ai-berkshire](https://github.com/xbtlin/ai-berkshire)
- **语言**: Python
- **Stars**: 3,145
- **简介**: AI 时代的伯克希尔：基于 Claude Code 的价值投资研究框架。巴菲特·芒格·段永平·李录四大师方法论 + 多Agent并行研究。| AI-era Berkshire: a value investing research framework built on Claude Code. 4 masters' methodologies + multi-agent adversarial analysis.

### AI 总结
**简介**: AI Berkshire 是一个基于 Claude Code 的多智能体价值投资研究框架，系统化整合巴菲特、芒格、段永平、李录四位大师的投资方法论，可实现专业级投资研究，其真实账户实盘两年累计收益超146万元。

**核心功能**:
- **四大师视角对抗分析**：同时启动4个独立Agent，分别从商业模式、财务估值、逆向思考、长期确定性四个维度并行研究，产生真实观点冲突以规避盲点
- **强制结构化输出**：生成包含“通过/不通过/灰色地带”的明确结论，附带具体价格区间和分层建议，避免AI常见的模棱两可
- **内置多层反偏见机制**：包括信息丰富度评级、芒格式逆向检验、快速否决清单（8条红线）、反共识检查、留白原则等，防止决策幻觉
- **精确金融数据校验**：使用`decimal.Decimal`进行精确计算，关键数据强制双源交叉验证，避免LLM心算错误（如市值单位混淆）
- **可复现的研究流程**：16个标准化Skill入口，确保不同公司、不同时间的分析结构一致，支持横向对比和纵向追踪

**技术亮点**: 基于Claude Code的Agent架构，实现多Agent并行搜索与独立决策；集成Python精确计算工具链（`financial_rigor.py`）；采用Mermaid可视化架构图；全Skill模块化设计（深度研究/财报分析/行业筛选等16个入口）

---
