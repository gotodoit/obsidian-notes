---
tags:
  - github-trending
  - daily
date: 2026-10-25
created: 2026-10-25T01:55:42.884Z
---

# 2026-10-25 GitHub Trending Top 10

## 1. [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill)
- **语言**: JavaScript
- **Stars**: 44,663
- **简介**: A coding-agent skill for multi-phase security audits with independently verified, machine-readable findings

### AI 总结
**简介**: Cloudflare 开源的安全审计技能，将编码 Agent 转化为多阶段安全审计器，产出经独立验证、机器可读的漏洞发现。

**核心功能**:
- 六阶段结构化审计流程：侦察（架构与覆盖台账）→ 覆盖驱动的漏洞狩猎 → 候选验证 → 结构化输出（`findings.json`）→ 独立记录核验 → 目标无关的报告生成
- 按目标类型提供专项攻击类提示词：内存安全/二进制、AI/LLM、Web 协议与认证、客户端、供应链、云与部署、RPC 与消息、资源耗尽、数据隔离、桌面/移动与本地 IPC
- 三类明确判定：`confirmed`（有完整来源追溯）、`needs_validation`（存在未解决事实且无严重性）、`rejected`（被证伪）
- 对同一仓库多次运行可累加：复用历史台账与发现，定向补缺并重新验证变更源码
- 零依赖校验脚本：`validate-findings.cjs` 与 `validate-coverage-ledger.cjs`，配套测试文件

**技术亮点**: 采用隔离 Agent 编排与"覆盖台账"驱动的审计架构，每个候选交由全新验证者尝试证伪，最终结论再由独立 Agent 复核；输出受 `report-schema.json` 约束，保证机器可读与可追溯；该技能是 Cloudflare 漏洞发现框架的单一仓库起点，可通过 Skills CLI 一键安装。

---
## 2. [NVIDIA/OpenShell](https://github.com/NVIDIA/OpenShell)
- **语言**: Rust
- **Stars**: 19,495
- **简介**: OpenShell is the safe, private runtime for autonomous AI agents.

### AI 总结
**简介**: NVIDIA OpenShell 是一个用 Rust 编写的安全、私密的自主 AI 智能体运行时，通过策略声明和内核级强制隔离，让智能体在受限环境中安全地访问文件、网络和凭据。

**核心功能**:
- **内核级强制隔离**：每个智能体运行在独立沙箱中，内核控制其可访问的文件、可发起的系统调用，所有网络连接在离开沙箱前须通过策略检查。
- **凭据安全代理**：智能体无法直接接触真实凭据，OpenShell 仅在请求发往已批准端点时注入凭据。
- **形式化验证的策略变更**：策略变更生效前，通过形式化验证标记出高风险的新增访问（如携带凭据访问新主机、调用新 API 方法），需人工审核。
- **沙箱与策略管理**：支持镜像、运行时、GPU 和生命周期管理，提供文件系统、网络和进程规则。
- **Provider 与 Gateway**：凭据仅在批准端点生效，Gateway 作为沙箱、策略和访问的控制平面，支持通过 Helm 部署到 Kubernetes。
- **可扩展性**：提供中间件、拦截器和计算驱动扩展接口，并提供 Agent Skills 与 SDK。

**技术亮点**: 使用 Rust 实现；采用内核插桩（kernel instrumentation）在运行时强制策略；结合形式化验证预判策略变更影响；架构上由 Gateway、Supervisor 和 Sandbox 三层组成；支持 Linux、Apple Silicon macOS 及 WSL 2，兼容 Docker、Podman 或主机虚拟化。

---
## 3. [aws/agent-toolkit-for-aws](https://github.com/aws/agent-toolkit-for-aws)
- **语言**: Python
- **Stars**: 3,144
- **简介**: Official, AWS-supported MCP servers, skills, and plugins to help AI agents build on AWS

### AI 总结
**简介**: AWS 官方推出的 Agent Toolkit，为 AI 编程代理提供工具、知识和护栏，帮助其在 AWS 上构建、部署和管理应用。

**核心功能**:
- 提供官方支持的 MCP 服务器、技能（skills）和插件，覆盖服务选型、CDK/CloudFormation、无服务器、容器、存储、可观测性、计费、SDK 使用和部署等场景
- 支持通过 Amazon Bedrock 和 AgentCore 构建 AI 代理（aws-agents 插件）
- 提供数据湖、分析和 ETL 工作流支持，集成 S3 Tables、AWS Glue 和 Athena（aws-data-analytics 插件）
- 提供 DevSecOps 能力，包括事件调查、代码审查、UAT、漏洞扫描和渗透测试（aws-agents-for-devsecops 插件）
- 面向初创企业提供架构、成本、安全及 AWS Activate 指导，并支持从 Azure、GCP、Heroku 等平台迁移（aws-startup-advisor 插件）
- 可通过 AWS CLI 直接在终端使用（`aws configure agent-toolkit`）

**技术亮点**: 基于 Python 开发，采用 MCP（Model Context Protocol）服务器架构，兼容 Claude Code、Codex、Cursor、Devin、Kiro、fx 等主流 AI 编程代理，通过插件市场机制分发，已进入 GA 阶段，采用 Apache 2.0 许可证。

---
## 4. [Nutlope/hallmark](https://github.com/Nutlope/hallmark)
- **语言**: CSS
- **Stars**: 32,196
- **简介**: Anti-AI-slop design skill for Claude Code, Cursor, and Codex.

### AI 总结
**简介**: Hallmark 是 Together AI 推出的设计技能，面向 Claude Code、Cursor、Codex 和 OpenCode，专门避免生成“一眼 AI”的页面。

**核心功能**:
- 提供 48 套主题（材质、配色、字体、组件与纹理），每次构建从目录中抽取三套，围绕访客目标组织页面并收尾于核心操作。
- 在真实浏览器中检查并拦截典型 AI 痕迹：标题上方的小字标签、字距大写标签、标题中的单色词、空框架页面、错位的首屏、页尾邮件订阅、虚假表单等，最后由全新上下文的审查者复核。
- 检查分三层：Floor（对比度、焦点、减弱动效、虚构事实、移动端布局，绝不放过）、Reflex（模型默认习惯，可有理由地记录豁免）、Finish（工艺细节，不阻塞发布）。
- 支持 `custom` 按提示词从零设计；可指向 URL、开发服务器或应用自动截图真实产品；内置 755 张开放授权照片并按主题署名。
- 提供 `/hallmark redesign <path>`（保留内容与接线重建页面）和 `/hallmark audit <path>`（仅报告）两种模式。

**技术亮点**: 主题以不超过 8 KB 的单文件形式存放于 `references/themes/`，构建时只读取一个；主题只定义材质而不规定页面结构，因此同一主题可生成不同页面；项目以 CSS 为主。

---
## 5. [luongnv89/claude-howto](https://github.com/luongnv89/claude-howto)
- **语言**: Python
- **Stars**: 44,588
- **简介**: A visual, example-driven guide to Claude Code — from basic concepts to advanced agents, with copy-paste templates that bring immediate value.

### AI 总结
**简介**: 一份面向 Claude Code 的视觉化、示例驱动学习指南，帮助开发者从基础概念进阶到高级 Agent 编排。

**核心功能**:
- 10 个教程模块，覆盖斜杠命令、记忆、子代理、Hooks、MCP 服务器、插件等全部 Claude Code 特性
- 提供可直接复制使用的配置模板（斜杠命令、CLAUDE.md、Hook 脚本、MCP 配置、子代理定义等）
- 内置自评估机制（`/self-assessment`、`/lesson-quiz`），按水平生成个性化学习路径
- 通过 Mermaid 图解展示各特性内部工作原理，并教授如何将多特性组合成自动化工作流（代码审查、部署、文档生成）

**技术亮点**: 以 Python 实现，采用渐进式学习路线（约 11-13 小时从入门到精通），多语言支持（英/越/中/乌/日），MIT 协议开源，项目曾登 GitHub Trending 榜首。

---
## 6. [pbakaus/impeccable](https://github.com/pbakaus/impeccable)
- **语言**: Rust
- **Stars**: 86,453
- **简介**: The design language that makes your AI harness better at design.

### AI 总结
**简介**: Impeccable 是一套面向 AI 编码代理的设计指导工具，帮助 AI 生成的前端界面摆脱千篇一律的模板感，产出更具设计品质的页面。

**核心功能**:
- **统一初始化流程**：通过 `/impeccable init` 收集持久的产品上下文并写入 `PRODUCT.md`，后续命令可据此理解受众、目标、约束和语气，避免与视觉方向混淆。
- **24 个设计命令**：提供 `polish`、`audit`、`critique`、`distill`、`animate`、`bolder`、`quieter` 等共享设计词汇，覆盖从规划（shape）、评审（critique/audit）到打磨（polish）、增强（bolder/delight/overdrive）的完整流程。
- **62 条确定性检测规则**：CLI 和浏览器扩展可离线运行这些规则（无需 LLM 和 API Key），并配合 LLM 专属的评审检查。
- **实时浏览器迭代**：`live` 和 `generate` 命令支持在浏览器中直接迭代元素、生成变体。
- **反模式指导**：明确列出应避免的常见问题，如滥用 Inter/Arial 字体、彩色背景上的灰字、卡片嵌套卡片、弹跳缓动等。

**技术亮点**: 项目使用 Rust 编写，核心为一个自包含的二进制引擎（首次运行可自动下载至 `~/.impeccable/bin/`），技能本身无需运行时依赖，仅通过轻量启动脚本调用；确定性检测规则可在无 LLM 环境下离线运行，降低使用门槛。

---
## 7. [pollen-robotics/microduck](https://github.com/pollen-robotics/microduck)
- **语言**: Rust
- **Stars**: 11,020
- **简介**: A Tiny biped duck robot 🦆

### AI 总结
**简介**: Microduck 是 Pollen Robotics 开源的一款约 25 厘米、800 克的微型双足鸭子机器人，本仓库是其运行在 Rockchip RK3566 上的“大脑”软件，使用 Rust 编写。

**核心功能**:
- 基于强化学习策略驱动 15 个舵机，以 50 Hz 控制循环实现行走、翻滚、捡拾物品、跌倒后自主站起、坐下、踢球、前进及发声等动作
- 支持手柄操控、蓝牙（`duckctl`）远程控制、摄像头 WebRTC 推流与深度传感器服务
- 提供签名验证、健康门控、可回滚的 OTA 更新机制，避免刷机变砖
- 附带 MuJoCo 仿真环境，可在无实体机器人时运行真实守护进程进行调试

**技术亮点**: 采用 Rust 单 workspace、无框架架构，由 `robotd`、`updaterd`、`configd`、`btd`、`padd`、`mediad`、`tofd` 等多个守护进程组成，通过 Unix socket 上的统一 JSON-RPC 契约通信；策略由配套仓库 `microduck_rl` 使用 MuJoCo + PPO 训练并导出为 ONNX 加载，实现 sim2real。

---
## 8. [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli)
- **语言**: TypeScript
- **Stars**: 108,079
- **简介**: An open-source AI agent that brings the power of Gemini directly into your terminal.

### AI 总结
**简介**: Gemini CLI 是 Google 开源的 AI 终端代理工具（TypeScript 编写），让开发者直接在命令行中调用 Gemini 模型能力。

**核心功能**:
- 代码理解与生成：查询、编辑大型代码库，基于 PDF、图片或草图等多媒体输入生成新应用
- 自然语言调试：用自然语言排查问题、定位故障
- 自动化与集成：自动化查询 PR、处理复杂 rebase 等运维任务，支持通过 MCP 服务器扩展能力（如 Imagen、Veo、Lyria 媒体生成），并可在脚本中非交互式运行
- 多种认证方式：支持 Google 账号 OAuth 登录、Gemini API Key（可选模型与按量计费）、Vertex AI（面向企业生产环境）

**技术亮点**: 基于 TypeScript 开发；提供 npx、npm、Homebrew、MacPorts、Anaconda 多种安装方式；设有 Preview（每周二）、Stable（每周二）、Nightly（每日）三条发布通道，便于按稳定性需求选择版本。

> ⚠️ 注意：README 顶部提示，自 2026 年 6 月 18 日起，免费版及 Google One 用户的 Gemini CLI 已被 Antigravity CLI 取代；且本项目未针对最新 Gemini 模型（如 Gemini 4 Argon）优化，追求最佳体验建议使用 Antigravity CLI。

---
## 9. [jbiaojerry/ebook-treasure-chest](https://github.com/jbiaojerry/ebook-treasure-chest)
- **语言**: Python
- **Stars**: 22,644
- **简介**: 欢迎来到电子书下载宝库，一个汇聚了各类电子书下载链接的地方。无论你是喜欢阅读经典文学、经管励志、终身学习、职场创业、技术手册还是其他类型的书籍，这里都能满足你的需求。 该库涵盖了帆书app(原樊登读书)、微信读书、京东读书、喜马拉雅等读书app的大部分电子书。

### AI 总结
**简介**: 一个汇聚多平台电子书下载链接的资源库，涵盖帆书、微信读书、京东读书、喜马拉雅等读书 App 的大部分电子书，每本书提供 epub、mobi、azw3 三种格式。

**核心功能**:
- 按标签分类索引电子书，涵盖文学、历史、科普、管理、技术等上百个分类，并标注各分类书籍数量
- 提供 GitHub Pages 在线实时搜索页面，支持输入书名、作者或分类关键词即时匹配
- 支持多关键词搜索（空格分隔），便于快速定位目标书籍
- 每本电子书提供 epub、mobi、azw3 三种常见格式，适配不同阅读设备

**技术亮点**: 项目以 Python 为主要语言，通过 GitHub Pages 部署静态搜索页面实现前端实时检索，并利用 Markdown 分类文件组织索引目录。

---
## 10. [makecindy/cindy](https://github.com/makecindy/cindy)
- **语言**: TypeScript
- **Stars**: 4,123
- **简介**: Consider it done. The open-source AI agent that works out of the box · 想到，就能做到。开源、开箱即用的 AI Agent。

### AI 总结
**简介**: Cindy 是一款开源、开箱即用的本地 AI Agent 客户端，将多种 harness、模型与工具整合为一体，在用户自己的电脑上完成真实工作。

**核心功能**:
- 多 Harness 融合：首批支持 Claude Code 与 Codex，模型与 harness 可自由混搭并在任务中途切换，工作区、记忆、技能与工具保持连续
- 并行与协作：单个任务可由不同 harness × 模型组合的 agent 进行规划、并行执行与评审
- 多端驱动：可操控浏览器、电脑和手机，并支持从即时通讯（IM）和定时任务发起工作
- 可塑性强：支持记忆纠错、技能复用、自动化定时任务、MCP 接入内部工具，以及插件扩展（规划中）
- 灵活接入模型：可使用官方托管服务、复用已有的 Claude Code / Codex 订阅、自带 API Key 或本地模型

**技术亮点**: 基于 TypeScript 构建，采用 pnpm monorepo 架构，包含 Electron 桌面端（`apps/desktop`）、Expo / React Native 移动端（`apps/mobile`）及共享能力包（认证、设备互联、agent 编排、模型提供商等）；工具二进制（claude-code、codex、ripgrep）按平台在安装时下载，Android 平台工具经 sha256 校验；后端服务独立于本仓库，客户端以 Apache-2.0 协议开源。

---
