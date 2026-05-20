---
tags:
  - github-trending
  - daily
date: 2026-05-20
created: 2026-05-20T01:55:44.346Z
---

# 2026-05-20 GitHub Trending Top 10

## 1. [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman)
- **语言**: Rust
- **Stars**: 21,407
- **简介**: Your Personal AI super intelligence. Private, Simple and extremely powerful.

### AI 总结
**简介**: OpenHuman 是一个开源的个人 AI 超级智能助手，注重隐私、简洁和强大性能，旨在无缝融入用户的日常生活。

**核心功能**:
- **简洁的 UI 优先体验**: 提供清洁的桌面界面和简短的上手路径，无需终端或复杂配置，即可在几秒内启动并运行智能代理。
- **桌面吉祥物交互**: 拥有一个会说话、对周围环境有反应、能作为真实参与者加入 Google Meet 的桌面吉祥物，它能在后台持续思考并记住用户跨周的活动。
- **118+ 第三方集成与自动获取**: 通过一键 OAuth 连接 Gmail、Notion、GitHub、Slack 等主流服务，代理每 20 分钟自动拉取最新数据到记忆树中。
- **记忆树与 Obsidian Wiki**: 构建本地优先的知识库，将用户数据和活动自动整理为 Markdown 块并评分，实现长期记忆和上下文感知。

**技术亮点**: 使用 Rust 语言开发，强调本地优先和隐私保护，支持跨平台（macOS、Linux、Windows）的一键安装脚本。

---
## 2. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 37,749
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: CLI-Anything 旨在通过为任何软件生成命令行接口，让所有软件都能被 AI 智能体原生调用，弥合 AI 与现有软件之间的鸿沟。

**核心功能**:
- **一键生成 CLI**: 为任意软件自动生成命令行接口，使其能被 AI 智能体直接操控。
- **CLI-Hub 中心**: 提供社区驱动的 CLI 包注册中心，支持一键安装、浏览和管理 ( `pip install cli-anything-hub` )。
- **多智能体兼容**: 生成的 CLI 可无缝对接 Pi、OpenClaw、Cursor、Claude Code 等主流 AI 智能体框架。
- **丰富的社区生态**: 支持社区贡献新的 CLI 封装，并提供了 Wishlist 功能让用户请求支持特定软件。
- **实时预览与轨迹循环**: 支持 AI 智能体通过生成的 CLI 进行实时预览和轨迹循环，以生成 CAD、3D 场景、图表等实际作品。

**技术亮点**: 项目基于 Python 开发，使用 Click 库构建 CLI，支持 JSON 和人类可读的输出格式，并拥有 100% 通过的单元与端到端测试覆盖。

---
## 3. [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills)
- **语言**: Python
- **Stars**: 14,196
- **简介**: Academic Research Skills for Claude Code: research → write → review → revise → finalize

### AI 总结
**简介**: 一个面向学术研究的 Claude Code 技能套件，覆盖从研究到发表的完整流程。

**核心功能**:
- 全流程学术研究支持：研究 → 写作 → 审阅 → 修订 → 定稿
- 引用与文献管理：自动查找参考文献、格式化引用，并检查引用真实性（针对幻觉引用问题）
- 写作质量检查：检测机器生成文本模式，进行风格校准以匹配用户个人写作风格
- 完整性审查：7 模式阻断检查清单，防止 AI 自主研究失败模式（如实现错误、幻觉结果、方法造假等）
- 可选审计模式：通过获取源文献判断引用是否支持论点，识别未支持声明、负面约束违反、虚构引用等五类高风险问题

**技术亮点**:
- 基于 Claude Code 插件系统，支持 CLI / VS Code / JetBrains
- 采用人机协同（human-in-the-loop）设计，避免完全自动化 AI 研究的致命缺陷
- 集成 Semantic Scholar API 验证、反泄露协议、VLM 图表验证等先进技术
- 提供校准模式，可通过用户提供的黄金标准集测量自身假阴性/假阳性率

---
## 4. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 198,479
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套为编码代理设计的完整软件开发方法论，基于可组合的技能和初始指令，确保代理遵循最佳实践。

**核心功能**:
- **设计先行**: 在编写代码前，代理会通过提问引导用户明确需求，生成并展示设计文档供用户确认。
- **规划执行**: 设计批准后，代理制定包含具体文件路径、完整代码和验证步骤的细粒度实施计划。
- **子代理驱动开发**: 批准后启动子代理按任务逐一开发，并自动检查和审查工作，可实现数小时自主运行。
- **多平台支持**: 支持 Claude Code、Codex CLI、Codex App、Factory Droid、Gemini CLI、OpenCode、Cursor、GitHub Copilot CLI 等主流编码代理工具。

**技术亮点**: 采用 Shell 脚本实现，强调 TDD（测试驱动开发）、YAGNI（你不会需要它）和 DRY（不要重复自己）原则，通过插件市场安装，技能自动触发，无需用户额外操作。

---
## 5. [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- **语言**: Python
- **Stars**: 20,233
- **简介**: Official, Anthropic-managed directory of high quality Claude Code Plugins.

### AI 总结
**简介**: 官方维护的Claude Code高质量插件目录，提供可信赖的插件安装与管理服务。  
**核心功能**:  
- 提供Anthropic内部插件与第三方社区插件的集中管理  
- 支持通过命令行或插件发现界面直接安装插件  
- 设定插件质量标准与安全审核流程  
**技术亮点**: 采用标准化插件目录结构（含元数据、MCP服务器配置、命令/代理/技能模块），基于Python构建。

---
## 6. [rohitg00/agentmemory](https://github.com/rohitg00/agentmemory)
- **语言**: TypeScript
- **Stars**: 14,207
- **简介**: #1 Persistent memory for AI coding agents based on real-world benchmarks

### AI 总结
**简介**: agentmemory 是一个为 AI 编程代理提供持久化记忆的开源库，基于真实世界基准测试，让代理无需重复解释上下文。

**核心功能**:
- **持久化记忆存储**: 为 Claude Code、Cursor、Gemini CLI 等主流 AI 编程代理提供跨会话记忆能力
- **MCP 服务器支持**: 提供 53 个 MCP 工具，兼容任何 MCP 客户端
- **实时记忆查看器**: 内置可视化工具，可实时查看和管理代理记忆
- **自动钩子系统**: 12 个自动钩子，支持记忆生命周期管理
- **演示与快速集成**: 一键启动记忆服务器，并自动连接主流编程代理

**技术亮点**:
- 基于 iii 引擎构建，零外部数据库依赖
- 融合 Karpathy 的 LLM Wiki 模式，加入置信度评分、知识图谱和混合搜索
- 检索 R@5 达 95.2%，令牌消耗减少 92%
- 使用 TypeScript 编写，通过 950+ 测试用例

---
## 7. [CloakHQ/CloakBrowser](https://github.com/CloakHQ/CloakBrowser)
- **语言**: Python
- **Stars**: 16,669
- **简介**: Stealth Chromium that passes every bot detection test. Drop-in Playwright replacement with source-level fingerprint patches. 30/30 tests passed.

### AI 总结
**简介**: CloakBrowser 是一个基于 Chromium 的隐形浏览器，通过 C++ 源码级指纹修改，能通过所有机器人检测测试，可作为 Playwright/Puppeteer 的即插即用替代品。

**核心功能**:
- 提供 49 个 C++ 源码级补丁，修改 canvas、WebGL、音频、字体、GPU、屏幕、WebRTC、网络时序、自动化信号等指纹
- 支持 `humanize=True` 参数，模拟人类鼠标轨迹、键盘时序和滚动模式
- 通过 Cloudflare Turnstile、FingerprintJS、BrowserScan 等 30+ 检测网站测试
- 提供 Python 和 JavaScript 的 Playwright/Puppeteer 即插即用替代接口
- 自动下载和更新隐形 Chromium 二进制文件，零配置
- 支持 Docker 一键测试：`docker run --rm cloakhq/cloakbrowser cloaktest`

**技术亮点**: 基于 C++ 源码级修改 Chromium 指纹，而非 JS 注入或配置补丁；支持 Python 和 JavaScript 双语言生态；提供自托管的浏览器配置文件管理器（类似 Multilogin/GoLogin 的替代方案）。

---
## 8. [rtk-ai/rtk](https://github.com/rtk-ai/rtk)
- **语言**: Rust
- **Stars**: 50,947
- **简介**: CLI proxy that reduces LLM token consumption by 60-90% on common dev commands. Single Rust binary, zero dependencies

### AI 总结
**简介**: RTK 是一个高性能的 CLI 代理工具，通过过滤和压缩命令输出，可将 LLM 的 token 消耗降低 60-90%，以单一 Rust 二进制文件提供零依赖的解决方案。

**核心功能**:
- **Token 节省**: 在常见开发命令（如 `ls`、`cat`、`git status`、`cargo test` 等）上实现 60-92% 的 token 节省，如 30 分钟 Claude Code 会话中总 token 从约 118,000 降至约 23,900。
- **命令重写**: 支持 Hook 代理（如 Claude Code、Copilot）自动将 Bash 命令（如 `git status`）重写为 `rtk git status`，无需手动调用。
- **多 AI 工具集成**: 通过 `rtk init` 命令初始化支持多种工具，包括 Claude Code、Gemini CLI、Codex、Cursor、Windsurf、Cline、Kilo Code 等。
- **跨平台安装**: 提供 Homebrew、curl 脚本、Cargo 和预编译二进制等多种安装方式，支持 macOS、Linux 和 Windows。

**技术亮点**: 单一 Rust 二进制文件，零依赖；支持 100+ 命令，处理开销低于 10ms；使用 MIT 许可证开源。

---
## 9. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 101,680
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个开箱即用的AI专家代理集合，每个代理都具备特定领域的专长、个性、工作流程和可交付成果，旨在帮助开发者快速组建专属的“AI梦之队”。

**核心功能**:
- **丰富的代理角色库**: 提供包括前端开发、后端架构、移动开发、AI工程师、DevOps自动化、安全工程师等在内的数十个专业AI代理。
- **即插即用**: 支持与Claude Code、GitHub Copilot、Cursor、Aider等多种主流AI编程工具集成，一键安装即可使用。
- **生产就绪**: 每个代理都经过实战检验，包含详细的个性描述、核心任务、技术交付物（含代码示例）和成功指标。

**技术亮点**:
- **Shell脚本驱动**: 提供 `install.sh` 和 `convert.sh` 脚本，支持一键安装和自动检测目标工具，简化集成流程。
- **多工具兼容**: 通过统一的Markdown代理定义文件，可灵活适配Claude Code、Copilot、Aider、Windsurf等十余种不同的AI开发环境。

---
## 10. [colbymchenry/codegraph](https://github.com/colbymchenry/codegraph)
- **语言**: TypeScript
- **Stars**: 6,703
- **简介**: Pre-indexed code knowledge graph for Claude Code, Codex, Cursor, and OpenCode — fewer tokens, fewer tool calls, 100% local

### AI 总结
**简介**: CodeGraph 是一个预索引代码知识图谱工具，为 Claude Code、Cursor、Codex 和 OpenCode 等 AI 编码助手提供语义代码智能，可减少 92% 的工具调用并提升 71% 的探索速度，且完全本地运行。

**核心功能**:
- 为 AI 编码助手提供预索引的知识图谱，包含符号关系、调用图和代码结构
- 支持一键初始化项目：`codegraph init -i`
- 交互式安装器自动配置 Claude Code、Cursor、Codex CLI 和 opencode
- 支持跨语言代码查询（如 Python+Rust）

**技术亮点**: TypeScript 构建，通过预索引知识图谱替代传统文件扫描（grep/glob/Read），将探索代理的多次文件读取转化为单次图谱查询。基准测试显示在 VS Code（59,377 节点）等大型代码库上实现 0 次文件读取。

---
