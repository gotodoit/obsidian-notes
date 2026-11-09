---
tags:
  - github-trending
  - daily
date: 2026-11-09
created: 2026-11-09T01:55:42.755Z
---

# 2026-11-09 GitHub Trending Top 9

## 1. [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock)
- **语言**: Python
- **Stars**: 103,730
- **简介**: Hunt down social media accounts by username across social networks

### AI 总结
**简介**: 一个用 Python 编写的工具，可通过用户名跨社交网络追踪对应的社交媒体账号。

**核心功能**:
- 根据用户名在多个社交平台上搜索并定位账号
- 汇总并展示各平台上的账号存在情况

**技术亮点**: 基于 Python 实现，便于安装与扩展，适用于 OSINT 信息收集场景。

---
## 2. [dsx-ai-factory/nvke](https://github.com/dsx-ai-factory/nvke)
- **语言**: Go
- **Stars**: 871
- **简介**: NVIDIA Kubernetes Engine (NVKE). A management plane for GPU Kubernetes on bare metal.

### AI 总结
**简介**: NVIDIA Kubernetes Engine (NVKE) 是一个面向自有 NVIDIA GPU 裸金属基础设施的管理平面，让平台团队能够像提供托管服务一样，为客户创建并运维独立的 Kubernetes 集群。

**核心功能**:
- 通过 NVKE API 或 `nvkectl` 创建独立的工作负载集群，每个集群拥有自己的控制平面、etcd 和节点池
- 管理工作负载集群生命周期：创建、扩缩容和删除节点池，升级 Kubernetes，替换节点
- 基于 TPM 与 SPIFFE/SPIRE 实现节点身份认证，节点通过认证后才获得加入集群的凭据，并支持按集群加密 etcd 数据
- 通过 NVIDIA Infra Controller (NICo) 供给 GPU 机器，并借助配套项目 NVKR 构建节点镜像与组件制品

**技术亮点**: 采用 Go 编写；架构上并非 Kubernetes 发行版，而是“自托管的 Kubernetes 集群工厂”——由临时种子集群搭建管理集群，管理平面再通过 CAPNICo 调用 NICo 驱动各工作负载集群；节点运行 nvke-agent，可选集成 AICR 加速运行时与可观测性组件。当前为预览版本，不建议用于生产环境。

---
## 3. [milind-soni/OpenMausBot](https://github.com/milind-soni/OpenMausBot)
- **语言**: TypeScript
- **Stars**: 18,336
- **简介**: Open-source Grok Bot alternative with a virtual machine that bots can use

### AI 总结
**简介**: OpenMausBot 是一个开源的 Grok Bot 替代方案，以聊天应用形式提供一支可自定义的本地 AI 机器人团队，每个机器人都是运行在本地、拥有独立人格与虚拟机的真实 Agent。

**核心功能**:
- **多 Agent 聊天体验**：侧边栏每个机器人都是独立 Agent（底层运行 Claude 或 Codex），拥有各自的人格、模型、云端计算机和已连接应用，像联系人一样对话，可观察其工作过程并审批关键操作。
- **自带 Agent 与本地优先**：支持接入用户已有的 `claude`、`codex` 等 Agent，数据与运行均本地化，无需依赖特定厂商。
- **跨平台桌面客户端**：提供 macOS（Apple Silicon / Intel，签名公证）、Windows x64 和 Ubuntu 24.04 安装包。

**技术亮点**: 采用 TypeScript（严格模式）开发，基于 React 19 构建界面、Electron 实现跨平台桌面应用；架构上强调 bring-your-own-agent、local-first 理念，每个 Bot 配备独立虚拟机与模型配置。

---
## 4. [anthropics/claude-quickstarts](https://github.com/anthropics/claude-quickstarts)
- **语言**: Python
- **Stars**: 19,458
- **简介**: A collection of projects designed to help developers quickly get started with building deployable applications using the Claude API

### AI 总结
**简介**: Anthropic 官方推出的 Claude API 快速入门项目集，提供多个可直接部署、易于定制的示例应用，帮助开发者快速上手 Claude API 开发。

**核心功能**:
- **Customer Support Agent**：基于知识库的 AI 客服助手，展示自然语言理解与生成能力
- **Financial Data Analyst**：结合交互式数据可视化的金融数据分析助手
- **Computer Use Demo**：让 Claude 控制桌面电脑的环境与工具，支持最新的 `computer_toolset_20260801` 工具集
- **Computer Use Best Practices**：原生 macOS 的计算机使用参考实现，演示显式工具定义、图像尺寸优化、提示缓存、沙箱 shell、轨迹记录等最佳实践
- **Browser Use Demo**：基于 Playwright 的浏览器自动化参考实现，支持导航、DOM 交互、内容提取与表单填写
- **Browser Toolset Quickstart**：基于 CDP 的最小浏览器工具集示例（Python/TypeScript）
- **Computer Toolset Quickstart**：基于 VNC 的最小计算机工具集示例（Python/TypeScript）
- **Autonomous Coding Agent**：基于 Claude Agent SDK 的双代理（初始化 + 编码）自主编程代理，可跨会话构建完整应用
- **Managed Agents 系列**：包括 Chat SDK（浏览器聊天应用，可适配 Slack/Teams/Discord 等）、CopilotKit + AG-UI（个人财务助手，支持生成式 UI）、Daily Brief（定时汇总 Slack 与 GitHub PR 的简报代理）

**技术亮点**: 以 Python 为主，涵盖 Claude Agent SDK、Managed Agents、计算机/浏览器工具集（CDP、VNC/RFB）、Playwright、CopilotKit、AG-UI 协议、Vercel Chat SDK 等技术栈；每个示例均提供可扩展的基础框架，部分示例明确标注为教学用途而非生产代码。

---
## 5. [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser)
- **语言**: Rust
- **Stars**: 47,658
- **简介**: Browser automation CLI for AI agents

### AI 总结
**简介**: agent-browser 是 Vercel Labs 推出的原生 Rust 浏览器自动化 CLI，让 AI agent 通过逐条 shell 命令驱动浏览器，以无障碍树形式读取页面并操作元素。

**核心功能**:
- `snapshot` 将页面转为紧凑文本，每个元素附带 `@e1` 之类的 ref，供 agent 引用并操作
- 支持点击、获取 URL 等命令，浏览器在命令间保持打开，形成「快照 → 操作 → 再快照验证」的循环
- 除 ref 外还支持 CSS 选择器、文本、XPath 和语义定位器（如 `find role button click --name "Submit"`）
- 点击目标隐藏、禁用、超出视口或被遮挡时会明确报错而非误报成功
- 内置与 CLI 版本匹配的 skills，便于 agent 加载核心循环与命令参考

**技术亮点**: 基于 Rust 构建，命令通过后台 daemon 经 Chrome DevTools Protocol 控制浏览器，每个 `--session` 独立 daemon 与浏览器实例，空闲一小时自动退出并可持久化状态；默认使用 Chrome for Testing，也支持连接现有 Chrome（`--cdp`/`--auto-connect`）、Lightpanda/Obscura 引擎、iOS 模拟器 Safari 及 Browserbase 等云浏览器；可通过 npm、Homebrew 或 npx 快速安装。

---
## 6. [meta/astryx](https://github.com/meta/astryx)
- **语言**: TypeScript
- **Stars**: 16,959
- **简介**: An open source design system that's fully customizable and agent ready

### AI 总结
**简介**: Astryx 是 Meta 开源的设计系统，历经八年内部打磨、支撑 13,000+ 应用，现以 Beta 版本对外开放，主打完全可定制与面向 AI Agent 的协作开发。

**核心功能**:
- 提供 150+ 无障碍组件，涵盖品牌级主题定制、暗色模式、开箱即用模板及 CLI 工具
- 开放式内部结构：组件可在任意层级组合，底层构建块直接导出，支持通过 swizzle 将组件源码弹出到项目中自主维护
- 无样式锁定：组件内部使用 StyleX 编写样式，但消费方可用 Tailwind、CSS Modules 或原生 CSS 通过 `className` 覆盖
- 主题即一组 CSS 自定义属性覆盖，设计师无需 fork 或包裹组件源码即可深度定制外观
- 安装即用：导入预构建 CSS + 类型化 React 组件，无需构建插件或采纳额外样式库

**技术亮点**: 基于 React 19+ 与 StyleX 构建；API、文档与 CLI 协同设计，使人类开发者与 AI 助手基于同一套参考以相同方式构建；提供全局/项目级 CLI 安装方案，便于编码 Agent 直接调用。

---
## 7. [anthropics/skills](https://github.com/anthropics/skills)
- **语言**: Python
- **Stars**: 189,703
- **简介**: Public repository for Agent Skills

### AI 总结
**简介**: Anthropic 官方开源的 Claude Agent Skills 公共仓库，提供可动态加载的技能示例，用于扩展 Claude 在特定任务上的表现。

**核心功能**:
- 提供自包含的技能文件夹（每个含 `SKILL.md` 指令与元数据），覆盖创意设计、开发技术、企业通信及文档处理等场景
- 开源 Claude 文档能力背后的核心技能（`docx`、`pdf`、`pptx`、`xlsx`），作为复杂生产级技能参考
- 支持通过 Claude Code 插件市场、Claude.ai 及 Claude API 安装和使用技能
- 附带技能规范（`spec`）与技能模板（`template`），便于开发者创建自定义技能

**技术亮点**: 基于 Python 实现；技能采用 `SKILL.md`（YAML frontmatter + Markdown 指令）的轻量目录结构，可被 Claude 动态加载；多数技能以 Apache 2.0 协议开源，可直接复用与二次开发。

---
## 8. [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco)
- **语言**: C++
- **Stars**: 16,446
- **简介**: Multi-Joint dynamics with Contact. A general purpose physics simulator.

### AI 总结
**简介**: MuJoCo 是由 Google DeepMind 维护的通用物理仿真引擎，全称为 Multi-Joint dynamics with Contact，专注于机器人、生物力学、图形动画与机器学习等领域中铰接结构与环境交互的快速精确仿真。

**核心功能**:
- 提供 C API，运行时仿真模块针对性能优化，基于 XML 编译器预分配的低层数据结构运行
- 内置原生桌面窗口与浏览器中的交互式可视化，并提供大量物理相关计算工具函数
- 提供 Python 绑定以及 Unity 游戏引擎插件
- 支持浏览器内在线体验（WebAssembly 版 MuJoCo Studio），可拖放自有模型
- 提供多个在线教程 Notebook，涵盖入门、模型编辑、多线程 rollout、LQR 控制、非线性最小二乘、MJX（JAX 版）及可微物理训练

**技术亮点**: 采用 C++ 实现，运行时高度优化；提供 JAX 分支 MuJoCo XLA（MJX）以支持可微物理与自动梯度训练；发布 Linux（x86-64/AArch64）、Windows（x86-64）、macOS（通用）预编译二进制，也可从源码构建。

---
## 9. [ranxianglei/billion-context](https://github.com/ranxianglei/billion-context)
- **语言**: TypeScript
- **Stars**: 5,193
- **简介**: A context-compression plugin for month-long single sessions (billions of tokens) ,small context windows (a 100K context is enough) and token savings (5x fewer tokens) .上下文压缩插件，月级长会话会话， 兼顾小窗口(100k上下文足矣)省token(省5倍token) . billion-context is all you need

### AI 总结
**简介**: billion-context 是一个用 TypeScript 编写的上下文压缩插件，面向超长单会话场景，让小窗口模型也能支撑月级、十亿级 token 的持续对话。

**核心功能**:
- 上下文压缩：将长会话历史压缩后送入模型，100K 上下文窗口即可满足使用。
- 节省 token：官方称可减少约 5 倍 token 消耗。
- 支持超长会话：单次会话可持续一个月、累计处理数十亿 token。
- 多客户端兼容：Readme 展示了 Claude Code、Codex、OpenCode、Gemini CLI、Kimi、Qwen Code、GitHub Copilot CLI、Aider、goose 等大量 AI 编程工具的适配图标。
- 通过 npm 全局安装使用（`npm install -g billion-context`）。

**技术亮点**: 基于 TypeScript 实现，以插件形式嵌入现有 AI 编程/对话客户端，主打高压缩质量与低 token 成本的平衡；已在 npm 发布并采用开源许可证。

---
