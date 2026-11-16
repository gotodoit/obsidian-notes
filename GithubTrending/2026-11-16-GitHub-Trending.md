---
tags:
  - github-trending
  - daily
date: 2026-11-16
created: 2026-11-16T01:55:42.301Z
---

# 2026-11-16 GitHub Trending Top 10

## 1. [dream-num/univer](https://github.com/dream-num/univer)
- **语言**: TypeScript
- **Stars**: 26,025
- **简介**: Build your own AI office with Univer Office SDK. Bring editing, calculation, collaboration, and file processing into your product for people and AI agents. Built on an extensible open-source core.

### AI 总结
**简介**: Univer 是一个基于 TypeScript 的开源 Office SDK，帮助开发者在自己的产品或 AI Agent 中嵌入表格、文档编辑、计算、协作与文件处理能力。

**核心功能**:
- 开箱即用的开源表格（Sheets）与文档（Docs）编辑器
- 支持将可编辑内容接入自有应用或 AI Agent（通过 Facade API 与事件机制）
- 支持跨功能的组合编辑与撤销/重做
- 可扩展的插件化架构，便于为自定义功能划定边界
- 提供 CLI、Agent 集成与开发者技能等生态工具，以及参考应用 Univer Workspace

**技术亮点**: 使用 TypeScript 构建；采用可扩展的开源核心架构；通过 Facade API 与事件系统连接应用和 Agent；拥有完善的文档、API Reference、多语言 README 及活跃的社区生态（Discord、Open Collective 等）。

---
## 2. [ag-ui-protocol/ag-ui](https://github.com/ag-ui-protocol/ag-ui)
- **语言**: TypeScript
- **Stars**: 17,924
- **简介**: AG-UI: the Agent-User Interaction Protocol. Bring Agents into Frontend Applications.

### AI 总结
**简介**: AG-UI 是一个开放、轻量、基于事件的 Agent-用户交互协议，用于标准化 AI Agent 与前端应用之间的连接方式。

**核心功能**:
- 实时流式 Agent 对话
- 双向状态同步
- 生成式 UI 与结构化消息
- 实时上下文增强
- 前端工具集成
- Human-in-the-loop（人在回路）协作

**技术亮点**:
- 基于 TypeScript 实现，提供约 16 种标准事件类型
- 灵活中间件层，兼容任意事件传输方式（SSE、WebSockets、webhooks 等），支持宽松的事件格式匹配
- 自带参考 HTTP 实现与默认连接器，可通过 `npx create-ag-ui-app` 快速创建应用
- 与 MCP（为 Agent 提供工具）、A2A（Agent 间通信）互补，共同构成 Agent 协议栈

---
## 3. [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills)
- **语言**: TypeScript
- **Stars**: 9,333
- **简介**: A library of Agent Skills designed to work with the Stitch MCP server. Each skill follows the Agent Skills open standard, for compatibility with coding agents such as Antigravity, Gemini CLI, Claude Code, Cursor.

### AI 总结
**简介**: 这是 Google Stitch 的 Agent Skills 与插件集合，遵循 Agent Skills 开放标准，可与 Codex、Antigravity、Gemini CLI、Claude Code、Cursor、OpenCode 等编码代理配合使用。

**核心功能**:
- **插件化安装**：提供 `stitch-design`（设计）、`stitch-build`（构建与组件）、`stitch-utilities`（工具助手）三类插件，支持按需组合安装
- **多代理兼容**：针对 Codex 提供 Marketplace/CLI 安装，Claude Code 与 Cursor 通过 `npx plugins` 安装，OpenCode 支持手动安装
- **按需安装技能**：可通过 `npx skills add` 选择性安装单个技能（需注意技能间依赖关系）
- **设计工作流技能**：如 `code-to-design` 可将前端代码（React、Vue 等）转换为 Stitch 设计，`generate-design` 用于生成设计

**技术亮点**: 基于 TypeScript 开发，遵循 Agent Skills 开放标准，依赖 Stitch MCP 服务器运行；支持稀疏检出（sparse checkout）加速克隆，并针对 OpenCode 的工具命名与技能命名规范（kebab-case）做了适配说明。

---
## 4. [backnotprop/plannotator](https://github.com/backnotprop/plannotator)
- **语言**: TypeScript
- **Stars**: 11,884
- **简介**: The workspace to stay in the loop and on top of agents - shape, decide, plan, annotate, review code, share with team, and send all feedback to agents with one click.

### AI 总结
**简介**: Plannotator 是一个面向 AI 编程代理的本地浏览器评审工具，让开发者对代理生成的计划、文档和代码变更进行标注，并将反馈一键回传给代理。

**核心功能**:
- **文档与计划评审**：对计划、规格、Markdown、HTML 及其他交互式产物进行行内标注和评论，反馈直接发送给代理执行
- **代码评审**：评审本地变更或远程 PR，在 diff 上评论和给出代码建议，支持 Git、GitButler、Jujutsu、Perforce、GitHub 和 GitLab
- **Plannotator Inbox**：统一的本地收件箱窗口，集中查看多个代理留下的消息、问题和待评审文件，点击即可回复，不阻塞代理会话
- **多代理集成**：通过插件、钩子和命令接入 Claude Code、Codex、Copilot CLI、Gemini CLI、OpenCode、Kiro、Droid、Amp、Pi 等主流编码代理
- **AI 辅助评审**：可就评审内容向 AI 提问，或启动 AI 评审自动在 diff 上生成评论

**技术亮点**: 基于 TypeScript 开发；采用本地浏览器界面 + 代理插件/钩子架构，反馈通过插件回传为代理的下一轮输入；支持 HTML 产物渲染标注与多版本控制系统（含 jj、p4）的差异评审。

---
## 5. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)
- **语言**: TypeScript
- **Stars**: 57,000
- **简介**: Chrome DevTools for coding agents

### AI 总结
**简介**: Chrome DevTools MCP 是一个基于 TypeScript 的 MCP 服务器与 CLI 工具，让 AI 编码助手（如 Claude、Cursor、Copilot）能够控制并检查真实的 Chrome 浏览器。

**核心功能**:
- **性能洞察**：利用 Chrome DevTools 记录 trace 并提取可执行的性能优化建议
- **高级浏览器调试**：分析网络请求、截图、查看控制台消息（含 source map 堆栈）
- **可靠自动化**：基于 Puppeteer 执行浏览器操作并自动等待结果
- **双形态接入**：既可作为 MCP 服务器集成到 AI 客户端，也可通过 `chrome-devtools` CLI 在终端直接控制浏览器

**技术亮点**: 基于 TypeScript 开发，采用 MCP（Model-Context-Protocol）协议对接 AI 编码助手；底层使用 Puppeteer 实现浏览器自动化，并复用 Chrome DevTools 前端进行 trace 分析；支持通过 CrUX API 获取真实用户性能数据（可用 `--no-performance-crux` 关闭），并提供使用统计与更新检查的开关选项。

---
## 6. [alibaba/open-code-review](https://github.com/alibaba/open-code-review)
- **语言**: Go
- **Stars**: 52,150
- **简介**: Secure, fast, efficient, battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level comments, built-in multi-language ruleset (NPE, thread-safety, XSS, SQL injection), OpenAI & Anthropic compatible.

### AI 总结
**简介**: 阿里巴巴开源的一款 AI 驱动的代码审查 CLI 工具，源自其内部经大规模验证的官方 AI 代码审查助手，只需配置模型端点即可使用。

**核心功能**:
- 读取 Git diff，将变更文件发送给可配置的 LLM，生成行级精度的结构化审查评论
- 支持 Agent 工具调用：可读取完整文件内容、搜索代码库、检查其他变更文件以获取上下文，实现深度审查而非表层 diff 反馈
- `ocr scan` 命令支持审查整个文件，适用于审计陌生代码库或无有效 diff 的目录
- 内置多语言规则集，覆盖 NPE、线程安全、XSS、SQL 注入等常见缺陷

**技术亮点**:
- 混合架构：确定性流水线 + LLM Agent
- 使用 Go 语言开发
- 兼容 OpenAI 与 Anthropic 模型接口
- 在 50 个开源仓库、200 个真实 PR、10 种语言的基准测试中，相比通用 Agent（如 Claude Code）精度与 F1 显著更高，token 消耗仅约 1/9，审查速度更快（以牺牲部分召回率换取低噪声）

---
## 7. [Tencent/LoopForge](https://github.com/Tencent/LoopForge)
- **语言**: Go
- **Stars**: 1,559
- **简介**: Self-hosted workflows for coding-agent delivery. Orchestrate CodeBuddy, Codex and Claude Code with scripts and human approval gates. Includes Local workflows for coding assistants.

### AI 总结
**简介**: LoopForge 是腾讯开源的自托管工作流平台，让团队通过编码智能体（CodeBuddy、Codex、Claude Code 等）以可重复、可审批的方式交付软件。

**核心功能**:
- **聊天式交付**：向 Main Bot 描述需求，自动创建 Docker 沙箱、检出仓库、委派项目角色并提交 PR/MR。
- **SOP 工作流**：将验证过的工作方式固化为标准流程（智能体、脚本、人工审批门与子 SOP 节点按序执行），确保每次需求以相同方式交付。
- **角色分离**：规划、实现、评审、测试各自拥有独立的提示词、执行器、模型、规则、Skills 与 MCP 工具。
- **人工介入控制**：在审批门确认，可将任务退回指定步骤、重试或从任意节点重新运行，也能在聊天中暂停、恢复或接管运行中的 SOP。
- **需求追踪**：聊天与 SOP 两条路径共享同一需求体系，所有变更可回溯并计入交付与成本报告。
- **LoopForge Local**：面向本地编码助手的本地工作流。

**技术亮点**: 使用 Go 语言开发；基于 Docker 实现自托管沙箱隔离；MIT 协议开源；提供 npm 包 `loopforge-cli`；支持多种编码智能体 CLI（CodeBuddy、Codex、Claude Code、OpenCode、Cursor CLI 等）。

---
## 8. [ggml-org/ggml](https://github.com/ggml-org/ggml)
- **语言**: C++
- **Stars**: 15,932
- **简介**: Tensor library for machine learning

### AI 总结
**简介**: ggml 是一个用 C/C++ 编写的轻量级、可移植、高效的机器学习张量库，零依赖且开箱即用。

**核心功能**:
- 纯 C/C++ 实现，无任何外部依赖，编译配置简单
- 跨平台支持 x86、ARM、RISC-V、LoongArch、PowerPC、s390x 及 WebAssembly
- 针对 x86、ARM、RISC-V 提供 SIMD 优化内核
- 广泛的后端支持：CPU、GPU、NPU 及浏览器
- 支持 2 至 8 位整数量化，以及 MXFP4、NVFP4 微缩放格式
- 运行时零内存分配

**技术亮点**: 采用 CMake 构建，提供 GGUF 文件格式用于模型存储；面向 llama.cpp 生态，核心库改动通过 llama.cpp 仓库提交 PR 以获得更好的测试与评审。

---
## 9. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- **语言**: Python
- **Stars**: 6,499
- **简介**: A Claude Code skill bundle for bug hunting and external red-team work - 82 skills, 15 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.

### AI 总结
**简介**: Claude-BugHunter 是一个面向漏洞挖掘和外部红队工作的 Claude Code 技能包，内置 83 个技能、15 个斜杠命令和 681 条公开报告模式，覆盖 24 类核心漏洞。

**核心功能**:
- **方法论与红队思维**：提供五阶段非线性工作流、批判性思维框架和红队操作规范。
- **Web 应用漏洞挖掘**：58 个 `hunt-*` 技能，基于 681 份 HackerOne 公开报告整理，包含检测模式、Payload、绕过表和攻击链模板。
- **企业边界攻击**：覆盖 M365/Entra、Okta、vCenter、SSL-VPN、SharePoint、云 IAM 等平台的 2024–2026 CVE 攻击链及凭据后提权。
- **分诊与报告输出**：包含 7-Question Gate、VRT 感知的严重性评级、OOS 反驳、PII 脱敏和红队交付物。
- **自动技能加载**：用自然语言描述测试目标即可自动匹配并加载相关技能，无需按名称调用。
- **Burp MCP 集成与项目脚手架**：支持 Burp 联动和 `hunt` 项目目录初始化。

**技术亮点**: 基于 Claude Code 技能系统，支持插件市场安装（命名空间隔离）和复制安装两种方式；提供独立的 `cbh` CLI（可通过 pipx 安装）；技能按主题自动触发，并已在授权红队、漏洞挖掘及 DVWA、OWASP Juice Shop 等公开训练平台验证。

---
## 10. [GoogleChrome/modern-web-guidance-src](https://github.com/GoogleChrome/modern-web-guidance-src)
- **语言**: TypeScript
- **Stars**: 7,234
- **简介**: Keep your coding agent up to date with the latest web best practices

### AI 总结
**简介**: GoogleChrome/modern-web-guidance-src 是 Modern Web Guidance 的源仓库，为编码智能体提供现代 Web 平台最佳实践与浏览器兼容性指导，帮助其摆脱过时模式。

**核心功能**:
- 通过 CLI 将专家策划的现代 Web 指南注入编码智能体的上下文窗口
- 提供搜索（search）、按 ID 检索（retrieve）、遗留模式扫描（legacy-scan）等命令
- 覆盖用户体验、CSS 布局、性能、表单与 UI 等多个核心领域
- 引导智能体使用现代浏览器 API、平台级性能与无障碍能力，以及轻量级回退方案

**技术亮点**: 基于 TypeScript 开发；指南设计注重 token 效率，通过评估剔除模型已掌握的通用内容；由 Google Chrome、Microsoft Edge、Mozilla Firefox 和 MDN 团队共同维护。

---
