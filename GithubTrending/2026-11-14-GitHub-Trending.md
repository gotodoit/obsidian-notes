---
tags:
  - github-trending
  - daily
date: 2026-11-14
created: 2026-11-14T01:55:42.267Z
---

# 2026-11-14 GitHub Trending Top 10

## 1. [alibaba/open-code-review](https://github.com/alibaba/open-code-review)
- **语言**: Go
- **Stars**: 50,656
- **简介**: Secure, fast, efficient, battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level comments, built-in multi-language ruleset (NPE, thread-safety, XSS, SQL injection), OpenAI & Anthropic compatible.

### AI 总结
**简介**: 阿里巴巴开源的 AI 代码审查 CLI 工具，源自集团内部大规模验证的 AI 代码审查助手，通过配置模型端点即可使用。

**核心功能**:
- 读取 Git diff，将变更文件发送给支持工具调用的 LLM Agent，生成行级精度的结构化审查评论
- Agent 可读取完整文件内容、搜索代码库、查看其他变更文件以获取上下文，实现深度审查而非表面 diff 反馈
- `ocr scan` 命令可对无有效 diff 的完整文件进行审查，适用于审计陌生代码库或目录
- 内置多语言规则集，覆盖 NPE、线程安全、XSS、SQL 注入等常见缺陷

**技术亮点**:
- 采用混合架构：确定性流水线 + LLM Agent
- 兼容 OpenAI 与 Anthropic 模型接口
- 基于 Go 语言开发，支持 Windows / macOS / Linux
- 可与 Claude Code、Codex、Cursor、Kimi Code 等 Agent 集成
- 基准测试显示，相同底层模型下 Precision 与 F1 显著高于通用 Agent，Token 消耗仅约 1/9，且审查速度更快（以略低 Recall 换取更高精度）

---
## 2. [GoogleChrome/modern-web-guidance-src](https://github.com/GoogleChrome/modern-web-guidance-src)
- **语言**: TypeScript
- **Stars**: 4,901
- **简介**: Keep your coding agent up to date with the latest web best practices

### AI 总结
**简介**: GoogleChrome/modern-web-guidance-src 是 Modern Web Guidance 的源码仓库，为编码智能体注入现代 Web 平台最佳实践与浏览器兼容性数据，引导其远离过时的遗留写法。

**核心功能**:
- 通过 CLI 将专家策划的现代 Web 指南注入编码智能体的上下文窗口，覆盖近年的 Web 平台新特性
- 提供指南搜索（search）、按 ID 检索（retrieve）以及代码库遗留模式扫描（legacy-scan）能力
- 聚焦现代浏览器 API 的正确用法、性能与无障碍优化，以及轻量级降级方案而非重型 polyfill
- 指南经过评测校准，保持 token 高效，剔除模型已掌握的通用内容

**技术亮点**: 项目使用 TypeScript 开发，由 Google Chrome、Microsoft Edge、Mozilla Firefox 与 MDN 团队共同维护，并提供评估仪表盘用于指南质量的持续校准。

---
## 3. [openai/codex-security](https://github.com/openai/codex-security)
- **语言**: TypeScript
- **Stars**: 13,154
- **简介**: OpenAI's Codex Security CLI and TypeScript SDK for finding, validating, and fixing security vulnerabilities. npm: https://www.npmjs.com/package/@openai/codex-security

### AI 总结
**简介**: OpenAI 推出的 Codex Security 是一个用于发现、调查和修复代码安全漏洞的 CLI 工具与 TypeScript SDK，支持在 Codex、终端和自动化流程中使用。

**核心功能**:
- 扫描仓库、指定路径或 Git 变更，支持 Standard 与 Deep 两种扫描模式并去重结果
- 验证候选漏洞、生成补丁并校验已有修复
- 生成 `SECURITY.md` 安全策略文档并保存威胁模型
- 浏览历史扫描与发现、识别重复项、按自定义标准评估严重性并从源码与 Git 历史推荐负责人
- 导入第三方扫描器结果，支持导出 SARIF、JSON、CSV 及发布到 Codex Security Cloud
- 与 Linear、Jira、GitHub 集成跟踪漏洞
- 支持跨仓库/组件的批量扫描，可在 CI 和容器中自动化运行

**技术亮点**: 基于 TypeScript 实现，提供 npm 包 `@openai/codex-security`；CLI 命令 `cs` 与 `codex-security` 等价，可通过 `npx` 免安装运行；运行环境要求 Node.js 22.13+/24/26 及 Python 3.10+；提供 TypeScript SDK（`CodexSecurity` 类）和 GitHub Action，支持 API Key 与设备/SSH 登录认证，并通过 `CODEX_SECURITY_STATE_DIR` 在关联 Git worktree 间共享扫描历史。

---
## 4. [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis)
- **语言**: Python
- **Stars**: 71,649
- **简介**: LLM 驱动的多市场股票智能分析系统：多源行情、实时新闻、决策看板与自动推送，支持零成本定时运行。 LLM-powered multi-market stock analysis system with multi-source market data, real-time news, decision dashboard, automated notifications, and cost-free scheduled runs.

### AI 总结
**简介**: 一个由 LLM 驱动的多市场股票智能分析系统，可每日自动分析自选股并将「决策仪表盘」推送到多个即时通讯平台，支持零成本定时运行。

**核心功能**:
- AI 决策报告：输出核心结论、评分、趋势、买卖点位、风险警报、催化因素与操作检查清单
- 多市场数据聚合：覆盖 A股、港股、美股、日股、韩股、台股及 ETF，聚合行情、K 线、技术指标、新闻、公告与基本面数据
- Web / 桌面工作台：支持手动分析、任务进度、历史报告、回测、持仓与配置管理，含浅色/深色主题
- Agent 策略问股：支持多轮追问，内置均线、缠论、波浪、趋势、热点等 15 种策略，覆盖 Web/Bot/API
- 智能导入与补全：支持图片、CSV/Excel、剪贴板导入，以及代码/名称/拼音/别名补全
- 自动化与推送：通过 GitHub Actions、Docker、本地定时任务或 FastAPI 服务运行，推送至企业微信、飞书、Telegram、Discord、Slack 和邮箱

**技术亮点**: 基于 Python 3.10+，采用 MIT 协议；兼容 Modelflare、Gemini、OpenAI、DeepSeek、通义千问、Claude、Ollama 等多种 AI 模型；行情数据支持 AkShare、Baostock、YFinance 等免费源零配置运行，也可接入 Tushare、Longbridge 等 token 型数据源；新闻搜索集成 SerpAPI、Tavily、Brave、SearXNG 等；提供 Docker 镜像与 GitHub Actions 开箱即用的部署方式。

---
## 5. [we-promise/sure](https://github.com/we-promise/sure)
- **语言**: Ruby
- **Stars**: 14,773
- **简介**: The personal finance app for everyone (by everyone)

### AI 总结
**简介**: Sure 是一个面向所有人的个人财务管理应用，由社区维护的 Maybe Finance 开源分支，支持自托管部署。

**核心功能**:
- 个人财务与财富管理，涵盖现金流、净资产、支出与资金流出等仪表盘视图
- 内置 AI 助手，可就储蓄等财务问题提供问答
- 支持通过浏览器、macOS 桌面应用、移动应用、API 客户端及 LLM 代理访问
- 提供 Docker 自托管方案，并附带演示数据便于快速体验

**技术亮点**: 基于 Ruby 开发，依赖 PostgreSQL（>9.3）与 Redis（>5.4）；使用 Skylight 进行性能监控并提供公开性能仪表盘；采用 AGPLv3 开源协议。

---
## 6. [backnotprop/plannotator](https://github.com/backnotprop/plannotator)
- **语言**: TypeScript
- **Stars**: 10,477
- **简介**: The workspace to stay in the loop and on top of agents - shape, decide, plan, annotate, review code, share with team, and send all feedback to agents with one click.

### AI 总结
**简介**: Plannotator 是一个基于 TypeScript 构建的本地浏览器评审工具，为 AI 编码代理提供注释、决策、代码审查和反馈回传的协作界面。

**核心功能**:
- **文档与计划注释**：对计划、规格、Markdown、HTML 及交互式产物进行标注和评论，一键将反馈发送给代理
- **代码审查**：审查本地变更或远程 PR，在 diff 上评论并建议代码，支持 Git、GitButler、Jujutsu、Perforce、GitHub、GitLab
- **HTML 产物注释**：直接对渲染后的 HTML 产物进行标注
- **Plannotator Inbox**：统一的本地收件窗口，集中查看多个代理留下的消息、问题、文件与评审请求，点击即可回复且不阻塞代理会话
- **多代理集成**：通过插件、钩子和命令接入 Claude Code、Codex、Copilot CLI、Gemini CLI、OpenCode、Kiro、Droid、Amp、Pi 等编码代理，以及 Grok Bot、Muse、Hermes、OpenClaw 等个人助理
- **内置 AI 辅助**：可就审查内容向 AI 提问，或启动 AI 评审自动在 diff 上发布评论

**技术亮点**: 采用 TypeScript 开发；以本地浏览器为评审界面，通过插件/钩子/命令与代理深度集成；反馈以代理的下一轮对话形式回传，实现"人在回路"的异步协作模式。

---
## 7. [louislam/uptime-kuma](https://github.com/louislam/uptime-kuma)
- **语言**: JavaScript
- **Stars**: 93,875
- **简介**: A fancy self-hosted monitoring tool

### AI 总结
**简介**: Uptime Kuma 是一款易于使用的自托管监控工具，用于实时监测各类服务的在线状态。

**核心功能**:
- 支持 HTTP(s)、TCP、Ping、DNS、Websocket、Docker 容器、Steam 游戏服务器等多种监控类型
- 支持通过 Telegram、Discord、Slack、邮件（SMTP）等 90+ 种通知服务发送告警
- 提供美观、响应快速的实时 UI/UX 界面
- 支持多语言、多状态页面，并可将状态页面绑定到特定域名
- 支持 Ping 图表、证书信息查看、代理及 2FA 双因素认证
- 默认 20 秒监控间隔

**技术亮点**: 基于 JavaScript/Node.js（要求 >= 20.4）构建，推荐使用 Docker 或 PM2 部署，支持反向代理；注意不支持 NFS 等网络文件系统挂载。

---
## 8. [block/buzz](https://github.com/block/buzz)
- **语言**: Rust
- **Stars**: 37,308
- **简介**: A hive mind communication platform

### AI 总结
**简介**: Buzz 是一个可自托管的“蜂巢思维”协作平台，让人类与 AI 代理在同一工作空间中共同构建项目。

**核心功能**:
- **人机同室协作**：代理作为正式成员加入频道，拥有独立密钥和审计轨迹，权限按身份而非权限标志划分
- **统一事件日志**：消息、反应、工作流步骤、代码审查、Git 事件均为 Nostr 中签名的同一类事件，便于统一搜索与追溯
- **代理全功能操作**：代理可打开仓库、发送补丁、审查代码、运行工作流、编辑画布、编排其他代理、参与语音讨论、创建频道
- **功能分支即房间**：将补丁、CI、审查与合并决策集中在一个频道中，形成代码存在原因的完整记录
- **媒体帧级评论**：可在视频特定帧上锚定评论

**技术亮点**: 基于 Rust 构建，采用 Nostr 中继架构；所有状态均为社区本地化，URL 即工作空间权威标识；支持单中继单社区及多租户托管部署（共享 Postgres、Redis 和对象存储）；桌面应用独立仓库（block/buzz-app），移动端与中继在本仓库；采用 Apache 2.0 许可。

---
## 9. [tradermonty/claude-trading-skills](https://github.com/tradermonty/claude-trading-skills)
- **语言**: Python
- **Stars**: 4,195
- **简介**: Claude Code skills for equity investors and traders — market analysis, technical charting, economic calendars, screeners, and trading strategy development.

### AI 总结
**简介**: Claude Trading Skills 是一个基于 Claude Skills 的 Python 交易工作流工具包，帮助时间有限的个人投资者结构化市场复盘、风险管理、交易计划与交易日志，而非将买卖决策外包给 AI。

**核心功能**:
- 市场分析：市场宽度分析（market-breadth-analyzer）、趋势分析（uptrend-analyzer）、仓位/敞口建议（exposure-coach），支持 15 分钟每日市场检查
- 技术与选股：技术图表分析（technical-analyst）、VCP 形态筛选（vcp-screener）、回撤熔断（drawdown-circuit-breaker）、仓位计算（position-sizer）
- 组合与股息管理：组合管理（portfolio-manager）、股息复盘监控（kanchi-dividend-review-monitor），支持每周长期组合复盘
- 交易纪律与复盘：盘前纪律门禁（pre-trade-discipline-gate）、交易记忆（trader-memory-core）、信号事后分析（signal-postmortem）、回测专家（backtest-expert）
- 预置工作流清单（workflows/ 下的 YAML manifest）：每日市场状态、每周组合复盘、波段机会筛选、交易记忆闭环、月度绩效复盘

**技术亮点**: 采用 Claude Skills 机制与机器可读的 YAML 工作流清单（明确技能、决策门与产出物顺序）；支持 Alpaca、FMP 等外部数据 API，基础路径可无付费 API 运行；提供文档站点、示例输出与中/日/英多语言文档；MIT 许可，定位为教育研究用途，不构成投资建议。

---
## 10. [tailscale/tailcat](https://github.com/tailscale/tailcat)
- **语言**: Go
- **Stars**: 9,474
- **简介**: like netcat, but over Tailscale's data plane, without Tailscale's control plane

### AI 总结
**简介**: Tailcat 是 Tailscale 开源组件的重新组合，类似 netcat，但运行在 Tailscale 的数据平面上（不含控制平面），提供点对点的 WireGuard 加密隧道。

**核心功能**:
- 在两台机器间通过 stdin/stdout 管道传输数据，服务端生成临时地址供客户端连接
- 支持将本地 TCP 端口通过隧道转发（`tailcat serve`），并可做端口映射（如将端口代理到局域网内其他主机）
- 提供 Go 库（`github.com/tailscale/tailcat`）和 CLI 两种使用方式
- 支持多种安装方式（静态二进制、deb/rpm、Homebrew、Scoop、Snap、容器、Nix、AUR、conda-forge 及源码编译）
- 提供实验性的浏览器 WebAssembly 演示，可与 CLI 互操作

**技术亮点**:
- 基于 Tailscale 的 `magicsock` 数据平面，使用 WireGuard 端到端加密
- 通过 DERP 服务器完成 NAT 打洞引导，成功后升级为直连 P2P UDP 连接
- 连接元数据通过带外方式交换，无需 Tailscale 控制平面和账号
- 纯用户态实现，无需 root/管理员权限，不修改系统路由表和 DNS
- 可使用官方免费限速 DERP 中继，或自行搭建 DERP 服务器

---
