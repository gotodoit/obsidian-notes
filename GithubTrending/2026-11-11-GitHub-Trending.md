---
tags:
  - github-trending
  - daily
date: 2026-11-11
created: 2026-11-11T01:55:43.152Z
---

# 2026-11-11 GitHub Trending Top 10

## 1. [meta/astryx](https://github.com/meta/astryx)
- **语言**: TypeScript
- **Stars**: 22,978
- **简介**: An open source design system that's fully customizable and agent ready

### AI 总结
**简介**: Astryx 是 Meta 开源的设计系统，历经八年内部打磨（支撑 13,000+ 应用），基于 React 19+ 与 StyleX 构建，兼顾人类开发者与 AI 助手的协作开发。

**核心功能**:
- 提供 150+ 无障碍组件，支持品牌级主题定制、暗色模式、开箱即用模板与 CLI 工具
- 开放式内部结构：组件可任意层级组合，底层模块直接导出，支持 swizzle 将组件源码弹出到项目内自行维护
- 无样式锁定：通过 `className` 可用 Tailwind、CSS Modules 或原生 CSS 覆盖样式
- 主题即 CSS 自定义属性覆盖，无需 fork 或包裹组件源码即可深度定制
- API、文档与 CLI 统一设计，人与 AI 助手使用同一套参考与工具链

**技术亮点**: 基于 React 19+ 与 StyleX 编写样式（对使用者透明）；无需构建插件、PostCSS 或 Babel 配置，仅需导入预构建 CSS 并使用带类型的 React 组件；提供全局 CLI 安装模式，让任意目录下的编码助手都能识别 Astryx。

---
## 2. [anthropics/skills](https://github.com/anthropics/skills)
- **语言**: Python
- **Stars**: 192,378
- **简介**: Public repository for Agent Skills

### AI 总结
**简介**: Anthropic 官方开源的 Claude Agent Skills 示例仓库，展示如何通过模块化的指令、脚本与资源文件夹扩展 Claude 在特定任务上的能力。

**核心功能**:
- 提供覆盖创意设计、开发技术、企业通信、文档处理等多领域的技能示例，每个技能以独立文件夹形式组织，内含 `SKILL.md` 指令与元数据
- 开源 Claude 文档能力背后的核心技能（docx、pdf、pptx、xlsx），供开发者参考复杂生产级技能的实现模式
- 提供 Agent Skills 规范（`./spec`）与技能模板（`./template`），方便开发者快速创建自定义技能
- 支持在 Claude Code（通过 Plugin Marketplace 安装）、Claude.ai 及 Claude API 三种环境中使用

**技术亮点**: 基于 Python 实现；技能采用轻量级结构，仅需一个含 YAML frontmatter（`name`、`description`）的 `SKILL.md` 文件即可定义；多数技能以 Apache 2.0 协议开源，可直接复用与二次开发。

---
## 3. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 115,204
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 一套面向 AI 编程代理的生产级工程技能包，将资深工程师的工作流、质量关卡和最佳实践打包成可复用技能，让 AI 代理在开发各阶段保持一致的行为。

**核心功能**:
- **9 个斜杠命令**覆盖完整开发生命周期：`/spec`（先写规格再写代码）、`/plan`（拆分为原子任务）、`/build`（增量构建）、`/test`（测试即证明）、`/constraints`（统一质量约束）、`/review`（合并前审查）、`/webperf`（Web 性能审计）、`/code-simplify`（代码简化）、`/ship`（发布上线）
- **`/build auto` 自动化模式**：批准计划后自主生成计划并逐项实现，每个任务仍遵循测试驱动并单独提交，遇失败或高风险步骤会暂停
- **技能自动激活**：根据当前任务类型自动触发对应技能（如设计 API 触发接口设计技能、构建 UI 触发前端工程技能）
- **25 个可单独安装的技能**，支持按需挑选，如 `code-review-and-quality`、`interview-me`、`test-driven-development`

**技术亮点**: 基于 JavaScript 实现；通过开放的 skills CLI 一条命令安装到 70+ 种 AI 代理（Claude Code、Cursor、Codex、Copilot、Cline 等）；Claude Code 支持插件市场安装；技能按 `skills/<name>/` 目录组织，配合仓库级 `references/` 共享清单，但单独安装技能时该共享目录不会一并复制。

---
## 4. [anthropics/claude-quickstarts](https://github.com/anthropics/claude-quickstarts)
- **语言**: Python
- **Stars**: 20,522
- **简介**: A collection of projects designed to help developers quickly get started with building deployable applications using the Claude API

### AI 总结
**简介**: Anthropic 官方推出的 Claude API 快速入门项目合集，帮助开发者快速搭建可部署的 AI 应用。

**核心功能**:
- **Customer Support Agent**：基于知识库的 AI 客服系统，演示 Claude 的自然语言理解与生成能力
- **Financial Data Analyst**：通过对话交互进行金融数据分析，结合交互式数据可视化
- **Computer Use Demo**：让 Claude 控制桌面电脑的环境与工具，支持最新 `computer_toolset_20260801` 工具集
- **Computer Use Best Practices**：原生 macOS 的计算机使用智能体参考实现，演示显式工具定义、图像裁剪、提示缓存、服务端压缩、批量工具调用等最佳实践
- **Browser Use Demo**：基于 Playwright 的浏览器自动化完整参考实现，可导航网站、操作 DOM、提取内容、填写表单
- **Browser / Computer Toolset Quickstart**：分别基于 CDP 和 VNC 的最小化工具集示例（Python + TypeScript），展示接口用法
- **Autonomous Coding Agent**：基于 Claude Agent SDK 的双智能体模式（初始化 + 编码），可跨会话构建完整应用，通过 git 持久化进度
- **Managed Agents 系列**：包括 Chat SDK 浏览器聊天应用（支持 Slack、Teams、Discord 等多平台适配）、CopilotKit + AG-UI 个人财务助手、以及定时推送 Slack/GitHub 摘要的 Daily Brief 智能体

**技术亮点**: 以 Python 为主，部分示例提供 TypeScript 版本；涵盖 Agent SDK、Managed Agents、工具集（computer/browser toolset）、AG-UI 协议、Playwright、CDP、VNC/RFB 等技术栈；强调提示缓存、批量调用、沙箱化等可靠且低成本的智能体构建模式。

---
## 5. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco)
- **语言**: C++
- **Stars**: 17,388
- **简介**: Multi-Joint dynamics with Contact. A general purpose physics simulator.

### AI 总结
**简介**: MuJoCo（Multi-Joint dynamics with Contact）是 Google DeepMind 维护的通用物理仿真引擎，用于机器人学、生物力学、图形动画和机器学习等领域中铰接结构与环境的快速精确仿真。

**核心功能**:
- 提供 C API，运行时仿真模块针对性能优化，基于 XML 编译器预分配的低层数据结构运行
- 支持原生桌面窗口与浏览器中的交互式可视化
- 提供大量用于计算物理相关量的工具函数
- 提供 Python 绑定以及 Unity 游戏引擎插件
- 支持浏览器内体验（WebAssembly 版 MuJoCo Studio），可拖放自己的模型

**技术亮点**: 采用 C++ 实现；内置 XML 模型编译器与预分配数据结构以最大化运行时性能；提供基于 JAX 的 MuJoCo XLA（MJX）分支，支持可微物理与自动求导训练策略；提供多线程 `rollout` 模块及非线性最小二乘求解器。

---
## 6. [we-promise/sure](https://github.com/we-promise/sure)
- **语言**: Ruby
- **Stars**: 12,008
- **简介**: The personal finance app for everyone (by everyone)

### AI 总结
**简介**: Sure 是一个面向所有人的开源个人财务管理应用，由社区维护，是已废弃的 Maybe Finance 项目的分支延续。

**核心功能**:
- 个人财务与财富管理仪表盘（现金流、净资产、支出与流出等）
- 内置 AI 助手，可回答储蓄等财务相关问题
- 支持多客户端访问：浏览器、macOS 桌面应用、移动应用、API 客户端及 LLM 代理
- 支持 Docker 自托管部署

**技术亮点**: 基于 Ruby 开发，依赖 PostgreSQL（>9.3）与 Redis（>5.4）；采用 AGPLv3 开源协议；集成 Skylight 公开性能监控面板以排查数据密集型请求的性能问题。

---
## 7. [homeassistant-ai/ha-mcp](https://github.com/homeassistant-ai/ha-mcp)
- **语言**: Python
- **Stars**: 6,697
- **简介**: Configure and automate Home Assistant with Claude, ChatGPT, and other AI assistants.

### AI 总结
**简介**: HA-MCP 是一个基于 Python 的 MCP 服务器，让 Claude、ChatGPT 等 AI 助手能够配置和自动化管理 Home Assistant。

**核心功能**:
- 提供 87 个工具，覆盖 Home Assistant 的配置与自动化管理
- 推荐通过 HACS 或 Marketplace 安装 HA-MCP 集成，以进程内方式运行完整服务器
- 支持所有 Home Assistant 安装类型（OS、Supervised、Container、Core），功能完全一致
- 支持管理员令牌或专用账户认证，提供远程访问（Secret URL / Home Assistant 登录）与本地网络访问两种连接方式

**技术亮点**: 基于 FastMCP 框架构建，采用进程内（in-process）服务器架构；要求 Home Assistant 2026.8.0+，集成版本 9.0.0 起支持管理员账户配置；注意 v7.3.0 起 `ha_config_set_yaml` 已移至 beta。

---
## 8. [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser)
- **语言**: Rust
- **Stars**: 49,252
- **简介**: Browser automation CLI for AI agents

### AI 总结
**简介**: agent-browser 是 Vercel Labs 推出的原生 Rust 浏览器自动化 CLI，让 AI Agent 通过逐条 shell 命令驱动浏览器完成网页操作。

**核心功能**:
- `snapshot` 将页面转换为紧凑的可访问性树文本，为每个元素分配 `@e1` 形式的 ref，Agent 通过 ref 执行点击等操作
- 支持 `open`、`click`、`get url`、`close` 等命令，浏览器在命令间保持打开，每步只需一次短 shell 调用
- 支持 CSS 选择器、文本、XPath 及语义定位器（如 `find role button click --name "Submit"`）
- 点击目标隐藏、禁用、超出视口或被遮挡时明确报错而非误报成功
- 内置 `skills` 命令向 AI Agent 提供与其版本匹配的使用说明和命令参考

**技术亮点**:
- 原生 Rust 实现，通过后台 daemon 经 Chrome DevTools Protocol 控制浏览器，每个 `--session` 拥有独立 daemon 与浏览器实例
- 默认使用 Chrome for Testing，也可通过 `--cdp`/`--auto-connect` 连接已有 Chrome，或选用 Lightpanda、Obscura 引擎及 Browserbase 等云浏览器
- 支持 iOS 模拟器中的 Mobile Safari，daemon 空闲一小时后自动保存状态并退出
- 通过 npm 全局安装、Homebrew 或 `npx` 免安装使用，采用 Apache-2.0 许可证

---
## 9. [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock)
- **语言**: Python
- **Stars**: 109,049
- **简介**: Hunt down social media accounts by username across social networks

### AI 总结
**简介**: 一款用 Python 编写的开源工具，可通过用户名在多个社交网络中追踪对应的账号。

**核心功能**:
- 根据指定用户名批量搜索多个社交平台上的账号
- 支持跨社交网络的账号关联查找

**技术亮点**: 基于 Python 实现，便于安装与扩展

---
## 10. [tokio-rs/topcoat](https://github.com/tokio-rs/topcoat)
- **语言**: Rust
- **Stars**: 6,847
- **简介**: A batteries-included framework for building web apps

### AI 总结
**简介**: Topcoat 是 tokio-rs 推出的模块化、开箱即用的 Rust 全栈 Web 框架，主打简洁与开发效率，目前处于早期实验阶段，API 可能发生破坏性变更。

**核心功能**:
- 服务端渲染：所有标记在服务端渲染，组件可为异步并直接查询数据库，无需独立 API 层
- 客户端响应式：`$(...)` 表达式为类型检查的 Rust 代码，初次渲染在服务端执行，同时转译为 JavaScript 在浏览器即时运行，无需 wasm 包或客户端构建步骤
- 服务端分片更新（`#[shard]`）：标记为 shard 的组件在其 `$(...)` 参数变化时由服务端重新渲染并原地替换 HTML
- HTML 模板宏 `view!`：贴近 HTML 与 Rust 语法，支持 `for`、`if` 等原生控制流
- 模块化路由：可基于源码模块结构自动推断路由树，无需构建步骤
- 提供 `topcoat fmt` CLI 命令自动格式化 `view!` 等宏代码

**技术亮点**: 基于 Rust 与 Tokio 异步运行时；采用模块化架构；通过宏实现服务端渲染与客户端交互的无缝结合，避免传统前后端分离的样板代码与 wasm 打包开销；采用 MIT 许可证。

---
