---
tags:
  - github-trending
  - daily
date: 2026-11-15
created: 2026-11-15T01:55:42.852Z
---

# 2026-11-15 GitHub Trending Top 10

## 1. [backnotprop/plannotator](https://github.com/backnotprop/plannotator)
- **语言**: TypeScript
- **Stars**: 11,160
- **简介**: The workspace to stay in the loop and on top of agents - shape, decide, plan, annotate, review code, share with team, and send all feedback to agents with one click.

### AI 总结
**简介**: Plannotator 是一个面向 AI 编码代理的本地浏览器审阅工作区，让开发者对代理产出的计划、文档、HTML 制品和代码变更进行标注，并将反馈一键回传给代理。

**核心功能**:
- **文档与计划标注**：对计划、规格说明、Markdown、HTML 等制品进行行内标注和评论，反馈直接发送给代理执行
- **代码审阅**：审阅本地改动或远程 PR，在 diff 上评论并给出代码建议，支持 Git、GitButler、Jujutsu（jj）、Perforce、GitHub、GitLab
- **Plannotator Inbox**：统一的本地收件窗口，汇集多个代理留下的消息、问题和待审文件，点击即可回复，且不会阻塞代理会话
- **HTML 制品标注**：直接对渲染后的 HTML 制品进行标注
- **内置 AI 辅助**：可针对审阅内容向 AI 提问，或启动 AI 审阅自动在 diff 上发布评论
- **多代理集成**：通过插件、钩子和命令接入 Claude Code、Codex、Copilot CLI、Gemini CLI、OpenCode、Kiro、Droid、Amp、Pi 等编码代理，Inbox 还支持个人助理类代理

**技术亮点**: 基于 TypeScript 开发，采用本地浏览器界面 + 插件/钩子架构，通过 `plannotator inbox` 等命令与各类代理会话双向通信，反馈可作为代理的下一轮输入。

---
## 2. [GoogleChrome/modern-web-guidance-src](https://github.com/GoogleChrome/modern-web-guidance-src)
- **语言**: TypeScript
- **Stars**: 6,090
- **简介**: Keep your coding agent up to date with the latest web best practices

### AI 总结
**简介**: GoogleChrome/modern-web-guidance-src 是 Modern Web Guidance 的源码仓库，为编码 Agent 注入现代 Web 平台的最佳实践与浏览器兼容性知识，帮助其摆脱过时的旧模式。

**核心功能**:
- 通过 CLI 向导一键安装，将专家整理的 Web 指南注入编码 Agent 的上下文窗口
- 支持按关键词搜索指南、按 ID 检索指南，以及扫描代码库中的遗留模式并给出现代化建议
- 覆盖用户体验、CSS 布局、性能、表单与 UI 等核心领域，涵盖 View Transitions、容器查询、Popover API、`scheduler.yield` 等现代特性
- 指南经过评估与裁剪以保持 token 高效，聚焦现代浏览器 API、性能与无障碍、轻量级降级方案

**技术亮点**: 基于 TypeScript 开发，提供 `npx modern-web-guidance` 即用命令；内置评估仪表盘用于校准内容质量；由 Google Chrome、Microsoft Edge、Mozilla Firefox 与 MDN 团队共同维护。

---
## 3. [tradermonty/claude-trading-skills](https://github.com/tradermonty/claude-trading-skills)
- **语言**: Python
- **Stars**: 4,851
- **简介**: Claude Code skills for equity investors and traders — market analysis, technical charting, economic calendars, screeners, and trading strategy development.

### AI 总结
**简介**: 一个基于 Claude Skills 的交易工作流工具包，帮助时间有限的个人投资者结构化市场复盘、风险管理、交易计划与决策改进流程。

**核心功能**:
- 每日 15 分钟市场状态检查（市场宽度、趋势、仓位暴露分析）
- 每周核心长期投资组合复盘（ETF、股息股、持仓管理）
- 仅在风险允许时筛选波段交易候选（VCP 筛选、回撤熔断、技术分析、仓位计算、交易前纪律检查）
- 交易记忆闭环：记录每笔已平仓交易并进行信号复盘学习
- 月度绩效复盘与规则调整（含回测专家技能）
- 提供机器可读的 workflow 清单，明确技能、决策关卡与产出物顺序

**技术亮点**: 基于 Python 开发，采用 Claude Skills 架构；提供结构化 YAML workflow 清单与可视化示例输出；基础路径无需付费 API，可选集成 Alpaca（组合数据）与 FMP（筛选器）等外部数据源；遵循 MIT 开源协议，仅用于教育与流程改进，不构成投资建议。

---
## 4. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)
- **语言**: TypeScript
- **Stars**: 56,330
- **简介**: Chrome DevTools for coding agents

### AI 总结
**简介**: `chrome-devtools-mcp` 是 Chrome DevTools 团队推出的 MCP 服务器兼 CLI 工具，让 AI 编码助手（如 Claude、Cursor、Copilot）能够控制和检查真实的 Chrome 浏览器。

**核心功能**:
- 性能洞察：通过 Chrome DevTools 录制 trace 并提取可执行的性能优化建议
- 高级调试：分析网络请求、截图、查看控制台消息（含 source map 堆栈追踪）
- 可靠自动化：基于 Puppeteer 执行浏览器操作并自动等待结果

**技术亮点**: 基于 TypeScript 开发，以 MCP 服务器和 CLI 双形态提供；底层使用 Puppeteer 实现浏览器自动化，复用 Chrome DevTools 前端能力；支持通过 CrUX API 获取真实用户性能数据（可关闭），并内置使用统计与更新检查机制（均可通过参数或环境变量退出）。

---
## 5. [alibaba/open-code-review](https://github.com/alibaba/open-code-review)
- **语言**: Go
- **Stars**: 51,461
- **简介**: Secure, fast, efficient, battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level comments, built-in multi-language ruleset (NPE, thread-safety, XSS, SQL injection), OpenAI & Anthropic compatible.

### AI 总结
**简介**: Open Code Review 是阿里巴巴开源的一款 AI 代码审查 CLI 工具，源自其内部服务数万名开发者、发现数百万代码缺陷的 AI 代码审查助手，配置模型端点即可使用。

**核心功能**:
- 读取 Git diff，通过具备工具调用能力的 Agent 将变更文件发送给可配置的 LLM，生成行级精度的结构化审查评论
- Agent 可读取完整文件内容、搜索代码库、查看其他变更文件以获取上下文，实现深度审查而非表层 diff 反馈
- 提供 `ocr scan` 命令，可审查整个文件，适用于审计陌生代码库或无有效 diff 的目录
- 内置多语言规则集，覆盖 NPE、线程安全、XSS、SQL 注入等常见缺陷

**技术亮点**:
- 混合架构：确定性流水线 + LLM Agent
- 兼容 OpenAI 与 Anthropic 模型接口
- 基于 Go 语言开发，支持 Windows、macOS、Linux 平台，并集成 Claude Code、Codex、Cursor、Kimi Code 等 Agent
- 在 50 个开源仓库、200 个真实 PR、10 种编程语言的基准测试中，相比通用 Agent（Claude Code）在同等模型下 Precision 与 F1 显著更高，Token 消耗仅约 1/9，审查速度更快（以牺牲部分 Recall 换取更低噪声）

---
## 6. [QwenLM/qwen-code](https://github.com/QwenLM/qwen-code)
- **语言**: TypeScript
- **Stars**: 30,362
- **简介**: An open-source AI coding agent that lives in your terminal.

### AI 总结
**简介**: Qwen Code 是 QwenLM 开源的一款 TypeScript 编写的 AI 编程智能体，可在终端、编辑器、桌面、浏览器和聊天工具中运行。

**核心功能**:
- 开箱即用的智能体能力：内置 Auto-Memory、Skills、SubAgents、MCP，并提供 Agent Teams、Agent Arena、Dynamic Workflows 等实验性/可选功能
- 多协议支持：兼容 OpenAI、Anthropic、Gemini、Qwen API，以及 Ollama / vLLM 等第三方或本地模型，支持运行时切换
- 多平台集成：提供 IDE 插件（VS Code、Zed、JetBrains）、桌面应用、Web UI、SDK，以及 Telegram、钉钉、微信、企业微信、飞书等聊天集成
- 便捷安装与使用：支持一键安装脚本、NPM（需 Node.js 22+）、Homebrew，通过 `qwen` 命令在项目目录启动，支持订阅账号或 API Key 认证

**技术亮点**: 基于 TypeScript 开发；框架与 Qwen 模型均为开源、协同演进，无厂商锁定；项目自身使用其智能体和模型进行 issue、PR、代码审查与测试，体现自迭代能力；提供 1.0 Preview 版本，融合 Qoder 的 agent harness 能力。

---
## 7. [dream-num/univer](https://github.com/dream-num/univer)
- **语言**: TypeScript
- **Stars**: 24,521
- **简介**: Build your own AI office with Univer Office SDK. Bring editing, calculation, collaboration, and file processing into your product for people and AI agents. Built on an extensible open-source core.

### AI 总结
**简介**: Univer 是一个基于 TypeScript 的开源 Office SDK，帮助开发者在自己的产品或 AI Agent 中集成表格、文档编辑、计算、协作与文件处理能力。

**核心功能**:
- 开箱即用的开源表格（Sheets）与文档（Docs）编辑器
- 支持将可编辑内容接入自有应用或 AI Agent
- 提供 Facade API 与事件机制，实现应用与 Agent 的联动
- 支持跨功能编辑的组合与撤销/重做
- 可扩展的插件化架构，方便划定自定义功能边界
- 配套 CLI、Agent 集成与参考应用（Univer Workspace）

**技术亮点**: 使用 TypeScript 构建，采用可扩展的开源内核与模块化架构；提供完整文档、API 参考与多语言支持，兼具开源能力与商业扩展（Scope and Licensing）路径。

---
## 8. [ag-ui-protocol/ag-ui](https://github.com/ag-ui-protocol/ag-ui)
- **语言**: TypeScript
- **Stars**: 17,387
- **简介**: AG-UI: the Agent-User Interaction Protocol. Bring Agents into Frontend Applications.

### AI 总结
**简介**: AG-UI 是一个开放、轻量、基于事件的 Agent-用户交互协议，用于标准化 AI Agent 与前端应用之间的连接方式。

**核心功能**:
- 实时流式 Agent 聊天
- 双向状态同步
- 生成式 UI 与结构化消息
- 实时上下文增强
- 前端工具集成
- 人机协作（Human-in-the-loop）

**技术亮点**: 基于 TypeScript 实现；采用约 16 种标准事件类型的事件驱动架构，并配有灵活的中间层，兼容 SSE、WebSocket、Webhook 等多种传输方式，支持宽松的事件格式匹配；提供参考 HTTP 实现与默认连接器。该协议与 MCP（为 Agent 提供工具）、A2A（Agent 间通信）互补，专注于将 Agent 带入面向用户的应用，可通过 `npx create-ag-ui-app` 快速创建应用。

---
## 9. [ashhart/TensorFold](https://github.com/ashhart/TensorFold)
- **语言**: Zig
- **Stars**: 2,168
- **简介**: LLM Inference Engine for Metal, CUDA and Vulkan.

### AI 总结
**简介**: TensorFold 是一个用 Zig 编写的 LLM 推理引擎，可在 Apple Silicon 和 NVIDIA GPU 上直接加载并服务语言模型，无需 Python 或 MLX 环境。

**核心功能**:
- 读取模型 checkpoint、对请求进行分词，并直接运行 Metal 或 CUDA 内核
- 通过 `pull` / `serve` 命令下载并启动模型服务，提供兼容 OpenAI 的 `/v1/chat/completions`、completions、Responses 和 Anthropic Messages 接口
- 支持本地 checkpoint 目录及已有 Hugging Face 缓存，并提供本地 Web 应用（`tensorfold web`）用于模型选择与运行
- 内置 Agent Traffic Control（ATC）协作流程，帮助贡献者与编码代理避免重复工作和冲突

**技术亮点**: 使用 Zig 构建单一原生二进制；直接对接 Metal（Apple Silicon）与 CUDA 13（NVIDIA，需驱动 R580+、glibc 2.28+）GPU 内核；提供 Homebrew 安装和 Linux 预编译归档（aarch64/x86_64），并附带校验和验证与 Windows 原生构建指南。

---
## 10. [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)
- **语言**: Go
- **Stars**: 120,094
- **简介**: 🪨 why use many token when few token do trick. Viral skill + proxy for coding agents that cuts 65% of tokens by talking like a caveman.

### AI 总结
**简介**: Caveman 是一个用 Go 编写的代理工具（Proxy/Skill），通过让 AI 编码代理“像穴居人一样说话”来大幅削减 token 消耗，官方称可减少约 65% 的 token，同时保持代码输出精确。

**核心功能**:
- **说少（Say Less）**：将代理的自然语言解释压缩为极简表达（如 63 token 缩到 20 token），分 `/caveman`、`/ultracave`、`/megacave` 三档，答案正确性不变。
- **读少（Read Less）**：整段会话输入 token 减少 33.2%（54 次 Claude Code 运行、18/18 答案正确）。
- **Auto 模式**：在 85 个编码任务上比 Opus 5.5 便宜 54%，得分相同。
- **Blocks 代码模式**：一次写成脚本，单次测试输出从 397 token 降到 76 token。
- **一键安装**：`npx @caveman-ai/cli@latest`，自动识别本机代理与登录信息，兼容 Claude Code、Codex、Gemini CLI、OpenCode 等 30+ 代理。
- **Caveman Code**：免费的多代理统一窗口客户端（Mac），宣称比 Codex 便宜 21%、比 Claude Code 便宜 14%～76%。

**技术亮点**:
- 语言为 Go，通过 CLI 代理层拦截并改写代理的输入/输出，而非替换模型本身。
- 本地运行，复用用户已有的 API key 与 Claude Pro/Max 订阅登录。
- 效果有第三方佐证：Adobe Research 论文（八款模型上便宜 1.4～2.4 倍）、JetBrains A/B 测试、Elasticsearch Labs 复现，并登上 Hacker News 与 GitHub Trending 榜首。
- 采用 Apache-2.0 许可证，需 Node.js 22.13+ 环境。

---
