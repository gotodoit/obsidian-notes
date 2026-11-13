---
tags:
  - github-trending
  - daily
date: 2026-11-13
created: 2026-11-13T01:55:42.794Z
---

# 2026-11-13 GitHub Trending Top 10

## 1. [GoogleChrome/modern-web-guidance-src](https://github.com/GoogleChrome/modern-web-guidance-src)
- **语言**: TypeScript
- **Stars**: 3,082
- **简介**: Keep your coding agent up to date with the latest web best practices

### AI 总结
**简介**: Modern Web Guidance 是 Google Chrome 团队主导的源仓库，旨在为编码 Agent 注入现代 Web 平台的专业知识与最佳实践，引导其生成基于原生 Web 能力的高性能代码。

**核心功能**:
- 通过交互式向导一键安装到编码 Agent，将精选的 Web 最佳实践指南注入 Agent 上下文窗口
- 支持指南搜索（search）、按 ID 检索（retrieve）以及扫描代码库中的遗留模式（legacy-scan）以推动现代化改造
- 覆盖用户体验（View Transitions、动画）、CSS 布局（容器查询、subgrid、oklch）、性能优化（预加载、INP 诊断、scheduler.yield）、表单与 UI（Popover API、锚点定位）等核心领域
- 指南设计注重 token 效率，通过评估机制裁剪模型已掌握的基础内容

**技术亮点**: 基于 TypeScript 开发；由 Google Chrome、Microsoft Edge、Mozilla Firefox 及 MDN 团队共同维护；提供 CLI 工具（npx modern-web-guidance）及在线评估仪表盘；强调平台级 API、内置无障碍能力与轻量回退方案，避免臃肿的 polyfill 和遗留库。

---
## 2. [openai/codex-security](https://github.com/openai/codex-security)
- **语言**: TypeScript
- **Stars**: 12,457
- **简介**: OpenAI's Codex Security CLI and TypeScript SDK for finding, validating, and fixing security vulnerabilities. npm: https://www.npmjs.com/package/@openai/codex-security

### AI 总结
**简介**: OpenAI 推出的安全扫描工具，提供 Codex 插件、CLI 与 TypeScript SDK，用于发现、验证并修复代码中的安全漏洞。

**核心功能**:
- 扫描仓库、指定路径或 Git 变更，支持标准扫描与深度扫描（结果去重）
- 验证候选漏洞、生成补丁并核验已有修复
- 生成 `SECURITY.md` 政策草稿、保存威胁模型
- 浏览历史扫描与发现项，识别重复、按自定义标准评估严重性、基于源码与 Git 历史推荐负责人
- 导入第三方扫描器结果，或发布报告至 Codex Security Cloud
- 与 Linear、Jira、GitHub 集成跟踪漏洞，支持导出 SARIF、JSON、CSV
- 支持 CI、容器及跨仓库批量自动化扫描

**技术亮点**: 基于 TypeScript 实现，提供 npm 包 `@openai/codex-security` 与同名 CLI（`cs`）；要求 Node.js 22.13+/24/26 及 Python 3.10+；支持 `OPENAI_API_KEY`/`CODEX_API_KEY` 环境变量认证，并可通过共享状态目录在 Git worktree 间复用扫描历史。

---
## 3. [nvm-sh/nvm](https://github.com/nvm-sh/nvm)
- **语言**: Shell
- **Stars**: 96,022
- **简介**: Node Version Manager - POSIX-compliant bash script to manage multiple active node.js versions.

### AI 总结
**简介**: nvm 是一个符合 POSIX 规范的 bash 脚本工具，用于在命令行中快速安装和切换多个 Node.js 版本。

**核心功能**:
- 按用户安装、按 shell 调用的 Node.js 版本管理，支持安装、更新、卸载多个版本
- 通过 `nvm use` 在不同 Node.js 版本间快速切换（如 24、22、20 等）
- 支持 `.nvmrc` 文件，可在进入目录时自动切换版本，并提供 bash/zsh/fish 的深度 shell 集成
- 支持安装时迁移全局包、离线安装、从文件读取默认全局包、使用 Node 二进制镜像（可传 Authorization 头）
- 提供 bash 补全、自定义颜色、环境变量配置，以及 Docker、Alpine Linux、WSL 等场景的安装与排障说明

**技术亮点**: 纯 Shell 实现，兼容 sh、dash、ksh、zsh、bash 等任意 POSIX 兼容 shell，可运行于 Unix、macOS 和 Windows WSL；采用按用户、按 shell 的轻量设计，不依赖系统级安装。

---
## 4. [pookjw/HermesEnabler](https://github.com/pookjw/HermesEnabler)
- **语言**: Objective-C
- **Stars**: 1,550
- **简介**: Enable Hermès Watch Faces on any Apple Watch devices

### AI 总结
**简介**: HermesEnabler 2 是一款基于 Objective-C 的工具，可让任意 Apple Watch 设备启用爱马仕（Hermès）表盘，仅支持 watchOS 27.0 至 27.3 beta 1。

**核心功能**:
- 在非爱马仕版 Apple Watch 上解锁并启用 Hermès 专属表盘
- 提供 macOS（Sideloadly 安装 IPA 或 Xcode 直接构建）与 Windows（借助 WatchBridge 工具）两种安装路径
- 支持通过 USB 完成开发者模式准备，后续安装与续签可改用 Wi-Fi

**技术亮点**: 以 Objective-C 编写的 iPhone 宿主应用 + Watch 应用双端 IPA 结构；依赖开发者模式与签名机制（Sideloadly / WatchBridge 签名安装）；集成 Gester 项目代码；强调固定 Bundle Identifier 与 MobileGestalt 备份以保障数据留存。

---
## 5. [we-promise/sure](https://github.com/we-promise/sure)
- **语言**: Ruby
- **Stars**: 13,953
- **简介**: The personal finance app for everyone (by everyone)

### AI 总结
**简介**: Sure 是一个面向所有人的开源个人财务管理应用，由社区维护的 Maybe Finance 项目分支，支持自托管。

**核心功能**:
- 个人财务与财富管理仪表盘（现金流、净资产、支出与资金流出等可视化）
- 内置 AI 助手，可回答储蓄等财务相关问题
- 支持多客户端访问：浏览器、macOS 桌面应用、移动应用、API 客户端及 LLM 代理
- 支持通过 Docker 自托管部署
- 提供演示数据以便快速体验与开发调试

**技术亮点**:
- 基于 Ruby 开发，依赖 PostgreSQL 与 Redis
- 采用 AGPLv3 开源许可证
- 集成 Skylight 性能监控，公开问题请求与堆栈追踪面板
- 提供国际化 README 与 DeepWiki/Dosu 等 AI 辅助文档工具

---
## 6. [QwenLM/qwen-code](https://github.com/QwenLM/qwen-code)
- **语言**: TypeScript
- **Stars**: 29,842
- **简介**: An open-source AI coding agent that lives in your terminal.

### AI 总结
**简介**: Qwen Code 是 QwenLM 开源的终端 AI 编程智能体（TypeScript 实现），可运行在终端、编辑器、桌面端、浏览器和聊天工具中。

**核心功能**:
- 开箱即用的智能体能力：Auto-Memory、Auto-Skills、SubAgents、Agent Teams、MCP 及动态工作流，无需额外配置
- 多协议支持：兼容 OpenAI、Anthropic、Gemini、Qwen API，也可接入 Ollama / vLLM 等本地或第三方模型，并支持运行时切换
- 多端覆盖：提供 IDE 插件（VS Code、Zed、JetBrains）、桌面应用、Web UI、SDK，以及 Telegram、钉钉、微信、飞书等聊天集成
- 快速安装与上手：支持一键脚本、NPM（需 Node.js 22+）、Homebrew 安装，会话内通过 `/auth` 登录 Qwen 账号或配置 API Key

**技术亮点**: 基于 TypeScript 开发，框架与 Qwen 模型均为开源且协同演进，无厂商锁定；项目自身采用 AI 驱动的开发方式（用自身智能体提 issue、提交 PR、审查代码和跑测试）；另有 Qwen Code 1.0 Preview 分支整合了 Qoder 的智能体框架能力。

---
## 7. [ashhart/TensorFold](https://github.com/ashhart/TensorFold)
- **语言**: Zig
- **Stars**: 1,950
- **简介**: LLM Inference Engine for Metal, CUDA and Vulkan.

### AI 总结
**简介**: TensorFold 是一个用 Zig 编写的 LLM 推理引擎，可在 Apple Silicon 和 NVIDIA GPU 上直接提供语言模型服务，无需 Python 或 MLX 环境。

**核心功能**:
- 直接读取模型检查点、对请求进行分词，并运行 Metal 或 CUDA 内核完成推理服务
- 提供 OpenAI 兼容的 HTTP API（chat/completions、completions、Responses、Anthropic Messages），可通过 `tensorfold pull` 下载模型、`tensorfold serve` 启动服务
- 支持本地检查点目录及已有 Hugging Face 缓存，并提供本地 Web 应用 `tensorfold web` 用于选择与运行模型

**技术亮点**:
- 以 Zig 编写为单一二进制，通过 Homebrew 或发布压缩包分发，无 Python/MLX 依赖
- 后端覆盖 Metal（Apple Silicon）与 CUDA（需 CUDA 13.0 / 驱动 R580+，支持 GB10 等）、并提及 Vulkan
- 面向多贡献者与 AI 代理协作，配套 ATC（Agent Traffic Control）工具进行任务认领、心跳与冲突检测，避免重复工作

---
## 8. [nodejs/node](https://github.com/nodejs/node)
- **语言**: JavaScript
- **Stars**: 123,606
- **简介**: Node.js JavaScript runtime ✨🐢🚀✨

### AI 总结
**简介**: Node.js 是一个开源、跨平台的 JavaScript 运行时环境，由 OpenJS Foundation 支持，采用开放治理模式。

**核心功能**:
- 提供跨平台 JavaScript 运行时，支持多种发布类型（Alpha、Current、LTS、Nightly）以满足不同场景需求
- 提供二进制文件、安装包和源码压缩包的下载，并支持通过 SHA 校验和 PGP 签名验证二进制文件的完整性
- 遵循语义化版本控制（SemVer），LTS 版本提供长达 30 个月的长期支持（从首次 Current 发布起总计 36 个月）
- 提供完整的 API 文档和版本特定文档，方便开发者查阅

**技术亮点**: 采用开放治理模型，由技术指导委员会（TSC）负责管理；拥有明确的发布节奏（每年 4 月发布新主版本，10 月转为 LTS）；使用 CITGM 对 Alpha 版本进行测试；项目遵循行为准则（Code of Conduct），鼓励协作与建设性意见交流。

---
## 9. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 116,699
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 一套面向 AI 编码代理的生产级工程技能包，将资深工程师的工作流、质量门禁和最佳实践编码为可复用的技能，覆盖软件开发全生命周期。

**核心功能**:
- 9 个斜杠命令映射开发流程（`/spec` 定义需求、`/plan` 制定计划、`/build` 增量构建、`/test` 测试验证、`/constraints` 设定质量约束、`/review` 合并前审查、`/webperf` 性能审计、`/code-simplify` 代码简化、`/ship` 发布上线）
- 技能根据当前任务自动激活（如设计 API 触发 `api-and-interface-design`，构建 UI 触发 `frontend-ui-engineering`）
- 支持 `/build auto` 自动模式：批准计划后自主完成全部任务的规划与实现，仍保持测试驱动和逐任务提交
- 通过开放的 skills CLI 一条命令安装到 70+ 代理（Claude Code、Cursor、Codex、Copilot、Cline 等），也支持按技能单独安装
- 提供 Claude Code 插件市场原生集成及本地开发方式

**技术亮点**: 基于 JavaScript 实现；以技能（Skills）为核心单元组织，配合斜杠命令自动激活对应技能；采用"先规格后代码、小原子任务、测试即证明"的工程理念，将开发流程分为 DEFINE→PLAN→BUILD→VERIFY→REVIEW→SHIP 六个阶段。

---
## 10. [meta/astryx](https://github.com/meta/astryx)
- **语言**: TypeScript
- **Stars**: 26,602
- **简介**: An open source design system that's fully customizable and agent ready

### AI 总结
**简介**: Astryx 是 Meta 开源的设计系统，历经八年内部打磨，提供 150+ 可访问组件、主题定制与 CLI，同时面向开发者和 AI 助手。

**核心功能**:
- 150+ 无障碍组件，支持品牌级主题、暗色模式与开箱即用的模板
- 开放式内部结构：组件可在任意层级组合，底层构建块直接导出，`swizzle` 可将组件源码弹出到项目中自行掌控
- 无样式锁定：内部用 StyleX 编写样式，但消费方可用 `className` 配合 Tailwind、CSS Modules 或原生 CSS 覆盖
- 主题即 CSS 自定义属性覆盖，无需 fork 或包装组件源码即可深度定制
- 配套 CLI 与文档，让人类和 AI 助手基于同一套参考以相同方式构建

**技术亮点**: 基于 React 19+ 与 StyleX 构建，TypeScript 编写；无需构建插件、PostCSS 或 Babel 配置，导入预构建 CSS 即可使用类型化组件；API、文档和 CLI 协同设计，原生支持 agent 工作流。

---
