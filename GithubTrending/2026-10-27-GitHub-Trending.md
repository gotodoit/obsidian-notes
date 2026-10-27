---
tags:
  - github-trending
  - daily
date: 2026-10-27
created: 2026-10-27T01:55:43.234Z
---

# 2026-10-27 GitHub Trending Top 10

## 1. [Nutlope/hallmark](https://github.com/Nutlope/hallmark)
- **语言**: CSS
- **Stars**: 36,471
- **简介**: Anti-AI-slop design skill for Claude Code, Cursor, and Codex.

### AI 总结
**简介**: Hallmark 是 Together AI 推出的一个面向 Claude Code、Codex、Cursor 和 OpenCode 的设计技能，旨在让 AI 生成的网页摆脱“AI 味”，呈现专业设计质感。

**核心功能**:
- **主题系统**：从 48 个主题（每个主题是一套材质，包含纸张、字体、色彩、表面、组件与纹理）中抽取三个，围绕访客的真实目的构建页面，主题只定义视觉材质，不规定内容结构。
- **任务导向构建**：页面按类别功能布局，如预订页能预订、商店能售卖、订阅页能订阅，核心操作放在类别惯常位置并作为页面收尾。
- **真实浏览器检查**：在真实浏览器中对结果进行 lint，检测“机器感”特征，如每个标题上方的眉标、字距放大的大写标签、标题中单个彩色词、空框架页面、错位首屏、页尾强行邮件订阅、假表单等。
- **分级门禁**：Floor 级（对比度、焦点、减少动效、虚构事实、手机布局损坏）绝不允许发布；Reflex 级为模型默认倾向，可有理由地记录后覆盖；Finish 级为工艺细节，不阻塞发布。
- **定制与真实素材**：支持纯 prompt 定制设计；可指向 URL、开发服务器或应用自动截图；内置 755 张开放授权照片并按主题署名。
- **重设计与审计**：`/hallmark redesign <path>` 保留内容与接线重建页面，`/hallmark audit <path>` 仅输出报告。

**技术亮点**: 以 CSS 为主要语言；主题以单文件形式存放于 `references/themes/`，每个不超过 8 KB 并配效果图，构建时只读取一个；引入全新上下文的评审者做最终把关。

---
## 2. [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)
- **语言**: Python
- **Stars**: 116,181
- **简介**: TradingAgents: Multi-Agents LLM Financial Trading Framework

### AI 总结
**简介**: TradingAgents 是 Tauric Research 开发的多智能体 LLM 金融交易框架（Python），通过多个大模型智能体协作完成金融分析与交易决策。

**核心功能**:
- 多智能体协作分析：分析师、研究经理、交易员、组合经理等角色分工，支持并行分析加速
- 回测与决策记录：按股票与日期网格回测，严格遵循时点数据（point-in-time），避免未来函数，并持久化决策日志
- 灵活模型与供应商配置：可为不同模型层级指定不同供应商，兼容 OpenAI、DeepSeek、Qwen、GLM、Bedrock 等多种模型
- 数据接入：整合 SEC EDGAR 财报、FRED 宏观数据、Yahoo 新闻/搜索、Alpha Vantage、Polymarket 等数据源
- 报告与 CLI：报告导出为单一 HTML 页面，CLI 支持通过参数无提示运行及断点续跑

**技术亮点**: 基于 LangGraph 构建智能体工作流，支持检查点恢复；强调时点数据完整性与回测隔离；提供 Docker 部署、环境变量配置（`TRADINGAGENTS_*`）及多语言支持，并有配套 arXiv 论文（2412.20138）。

---
## 3. [JetBrains/thinkrail](https://github.com/JetBrains/thinkrail)
- **语言**: TypeScript
- **Stars**: 2,965
- **简介**: Vibe code with pi in a lightweight, real IDE that customises itself around the way you work — The Vibe You Need

### AI 总结
**简介**: ThinkRail 是 JetBrains 孵化的一款 agentic IDE，围绕 `pi` 编码智能体构建，通过隔离工作区和"活规格"让智能体随使用不断学习并适应你的工作方式。

**核心功能**:
- **隔离工作区**：将任意 git 仓库作为项目，用 `git worktree` 切分出独立分支和工作目录，支持多个智能体并行工作而不干扰主检出；合并好分支、删除其余分支，闲置工作区会自动归档到项目侧栏。
- **真实 IDE 体验**：基于 Monaco 编辑器的可拆分工作台，包含文件树、实时 git 变更标记、终端和文档，均限定在当前工作区内；支持在文件和 diff 上留评论并作为结构化上下文发给对话。
- **流式对话**：每个工作区可运行多个并发 `pi` 会话，各自独立模型并实时显示 token 与成本；支持中途引导、排队后续指令、委派子智能体，并共享可编辑的执行计划。
- **规格即事实来源**：代码旁维护 `SPEC.md` 文件连接图，智能体通过专用 `spec_*` 工具读取、搜索和维护，使意图跨会话保留。
- **技能与工作流**：支持可移植的 Agent 技能，复用项目知识与能力。

**技术亮点**: 使用 TypeScript 开发；以 `pi` 编码智能体（npm 包 `@earendil-works/pi-coding-agent`）为核心，结合 git worktree 实现工作隔离，并通过活规格与技能机制赋予智能体持久化的项目知识；后续计划加入完整扩展支持，让 IDE 能根据实际工作方式自建工具。

---
## 4. [makecindy/cindy](https://github.com/makecindy/cindy)
- **语言**: TypeScript
- **Stars**: 6,549
- **简介**: Consider it done. The open-source AI agent that works out of the box · 想到，就能做到。开源、开箱即用的 AI Agent。

### AI 总结
**简介**: Cindy 是一个开源、开箱即用的本地 AI Agent 客户端，将多种 harness、模型和工具整合为一体，在你自己的电脑上完成真实工作。

**核心功能**:
- 多 harness 与多模型自由混用：首批支持 Claude Code 和 Codex，可在任务中途切换，工作区、记忆、技能与工具保持连续；同一任务可由不同 harness × 模型组合并行规划、执行与审查
- 可驱动浏览器、电脑和手机，并支持从 IM 与定时任务发起工作
- 可塑的记忆（跨 harness 共享纠正结果）、技能（一次教学处处复用）、自动化（定时自运行并回报）以及 MCP 接入内部工具与业务系统
- 支持插件扩展功能、UI 与交互（开放市场规划中），源码可审计、fork 与回馈
- 模型接入灵活：官方 Cindy 服务、复用已付费的 Claude Code / Codex Coding Plan、自有 API Key 或本地模型
- 支持免登录模式使用本地 Agent（服务端能力不可用）

**技术亮点**: TypeScript 编写，pnpm monorepo 架构；包含 Electron 桌面端（`apps/desktop`）、Expo / React Native 移动端（`apps/mobile`）及共享能力包（认证、设备连接、Agent 编排、模型提供商等）；工具二进制（claude-code、codex、ripgrep、Android platform-tools）按平台在安装或打包时下载并校验；采用 Apache-2.0 协议开源，后端服务独立于本仓库。

---
## 5. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 289,890
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个面向 AI 编码代理的“代理运行框架性能优化系统”，为 Claude Code、Codex、Opencode、Cursor 等工具提供技能、直觉、记忆、安全与研究优先的开发能力。

**核心功能**:
- **技能与直觉（Skills & Instincts）**：为编码代理注入可复用的技能与行为直觉，提升任务执行的准确性与效率。
- **记忆（Memory）**：为代理提供跨会话的上下文记忆能力，减少重复说明与上下文丢失。
- **安全（Security）**：内置安全机制，并提供 `ecc-agentshield` 安全防护包。
- **研究优先开发（Research-first Development）**：引导代理在动手前先进行调研，提高方案质量。
- **多代理支持**：兼容 Claude Code、Codex、Opencode、Cursor 等多种代理运行环境。
- **多语言文档**：提供包括简体中文、繁体中文、日文、韩文等在内的 16 种语言 README。

**技术亮点**:
- 以 JavaScript 为主要语言，同时涉及 Shell、TypeScript、Python、Go、Java、Perl 等多种技术栈。
- 以 `ecc@ecc` 插件形式分发，提供 npm 包（`ecc-universal`、`ecc-agentshield`）及 GitHub App 等多种安装渠道。
- 采用 MIT 开源协议，拥有独立官网（ecc.tools）与 Discord 社区，并强调仅从官方渠道安装以防范恶意镜像。

---
## 6. [pbakaus/impeccable](https://github.com/pbakaus/impeccable)
- **语言**: Rust
- **Stars**: 89,270
- **简介**: The design language that makes your AI harness better at design.

### AI 总结
**简介**: Impeccable 是一套面向 AI 编程代理的前端设计语言与工具，通过 1 个技能（skill）、24 条命令、实时浏览器迭代和 62 条确定性检测规则，避免 AI 生成千篇一律的模板化前端设计。

**核心功能**:
- **初始化流程**：`/impeccable init` 一次性收集产品上下文并写入 `PRODUCT.md`，后续命令据此了解受众、目的、约束与语气。
- **24 条设计命令**：通过 `/impeccable <command>` 调用，涵盖 `craft`、`shape`、`critique`、`audit`、`polish`、`bolder`、`quieter`、`distill`、`harden`、`animate`、`colorize`、`typeset`、`layout`、`live`、`generate` 等，也可用 `pin` 创建独立快捷命令。
- **确定性检测**：62 条规则由 CLI 和浏览器扩展本地运行，无需 LLM 和 API Key；另含仅依赖 LLM 的评审检查。
- **反模式指南**：明确禁止滥用字体（如 Inter、Arial）、彩色背景上的灰字、纯黑纯灰、卡片嵌套卡片、弹跳缓动等常见 AI 设计痕迹。
- **实时浏览器迭代**：`live` 与 `generate` 命令支持在浏览器中直接迭代和生成元素变体。

**技术亮点**: 项目以 Rust 实现，核心为自包含二进制引擎，无需独立运行时；通过轻量启动脚本（含 Windows 版 `impeccable.cmd`）调用，首次运行时自动下载至 `~/.impeccable/bin/`，Node 仅用于安装环节。

---
## 7. [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector)
- **语言**: Python
- **Stars**: 22,249
- **简介**: Security scanner for AI agent skills. Detect vulnerabilities, malicious patterns, security risks, prompt injection, data exfiltration, and supply-chain risks in Claude Code, Codex, and MCP skills before you install them.

### AI 总结
**简介**: NVIDIA 开源的 AI Agent 技能安全扫描器，可在安装前检测 Claude Code、Codex、MCP 等 Agent 技能中的漏洞、恶意模式与供应链风险。

**核心功能**:
- 多格式输入扫描：支持 Git 仓库、URL、zip 文件、目录及单文件
- 覆盖 17 类共 71 种漏洞模式，包括提示注入、数据外泄、权限提升、供应链风险、过度自主、系统提示泄露、记忆投毒、工具滥用、危险代码（AST）、污点追踪、YARA 签名、MCP 最小权限与工具投毒等
- 两阶段分析：快速静态分析 + 可选 LLM 语义评估
- 实时漏洞查询：通过 OSV.dev 获取 CVE 数据，支持离线回退
- 多种报告输出：Terminal、JSON、Markdown、SARIF
- 0-100 风险评分与严重性标签、修复建议
- 基线/误报抑制：通过 glob 规则或指纹基线过滤已知问题，复扫仅呈现新增风险

**技术亮点**: 基于 Python 3.12+，采用两阶段分析流水线架构（静态分析 + LLM 语义评估），集成 AST 分析与 YARA 签名检测，遵循 fail-closed 资源边界设计；支持 Docker 部署与 MCP/Pi/OpenCode 扩展集成，是 NVIDIA Verified Skills 流水线的组成部分，采用 Apache 2.0 协议。

---
## 8. [pollen-robotics/microduck](https://github.com/pollen-robotics/microduck)
- **语言**: Rust
- **Stars**: 12,450
- **简介**: A Tiny biped duck robot 🦆

### AI 总结
**简介**: Microduck 是 Pollen Robotics 开源的微型双足机器鸭（约 25 cm、800 g），本仓库是其运行在 Rockchip RK3566 上的“大脑”固件。

**核心功能**:
- 基于强化学习策略的 50 Hz 控制循环，驱动 15 个舵机，支持行走、翻滚、捡拾、摔倒后自主起身、坐下、踢球、叫声等动作
- 支持手柄操控、蓝牙（`duckctl`）远程控制及 WebRTC 摄像头推流
- 带签名校验、健康检查与回滚机制的安全 OTA 更新系统
- 提供 MuJoCo 仿真环境，可在无实体机器人时运行真实守护进程进行开发调试

**技术亮点**:
- 全 Rust 实现，无框架，单一 workspace
- 多守护进程架构（`robotd`、`updaterd`、`configd`、`btd`、`padd`、`mediad`、`tofd`），通过 Unix socket 上的统一 JSON-RPC 契约通信
- 策略由配套仓库 microduck_rl 使用 MuJoCo + PPO 训练，经 sim2real 流程导出为 ONNX 供本仓库加载

---
## 9. [nightly-labs/openbot](https://github.com/nightly-labs/openbot)
- **语言**: TypeScript
- **Stars**: 1,512
- **简介**: A local-first desktop workspace for persistent AI teammates. Run Codex, Claude, and Grok with dedicated workspaces, task queues, file sharing, browser control, and agent-to-agent collaboration.

### AI 总结
**简介**: OpenBot 是一个本地优先的桌面工作区，让 Codex、Claude、Grok 等 AI 智能体作为持久化“AI 队友”在独立工作空间中运行并相互协作。

**核心功能**:
- 支持 Codex App Server、Claude Code、Grok CLI，并通过 ACP 接入 OpenCode、Gemini、Cursor CLI、Cline CLI 等多种智能体
- 每个智能体拥有独立工作区、会话、模型与推理配置，支持提示词驱动的创建与编辑
- FIFO 消息队列，支持暂停、恢复、取消及崩溃安全持久化
- 智能体间消息、回复、表情、图片与文件传输，支持共享频道聊天与任务委派
- 持久化内嵌浏览器，智能体可打开、检查并控制页面
- 每智能体上下文监控与自动压缩，防止长对话超出模型窗口
- 支持自定义 OpenAI 兼容端点、自定义 ACP 智能体，自动检测本地模型服务（Ollama、LM Studio）
- 可选 macOS/Windows/Linux 的 Computer Use 能力

**技术亮点**: 基于 TypeScript 构建的本地优先桌面应用；采用 ACP 协议统一接入多类智能体；账号 API 运行于 Cloudflare Workers 与 D1；提供本地数据与隐私安全诊断导出。注意当前为开发预览版，智能体以 `danger-full-access` 和免审批策略运行，需谨慎使用。

---
## 10. [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)
- **语言**: Python
- **Stars**: 103,685
- **简介**: Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees.

### AI 总结
**简介**: Agent Reach 是一个基于 Python 的 CLI 工具，为 AI Agent 打通登录墙、视频内容、中文平台等"够不着"的互联网数据源，一条命令获取结构化数据，零 API 费用。

**核心功能**:
- 统一读取与搜索 Twitter、Reddit、YouTube、GitHub、Bilibili、小红书等平台
- 突破登录墙，访问需账号才能使用的功能（如小红书搜笔记、X 查账号动态）
- 提取视频内容，支持 B站/YouTube 字幕及语音转文字
- 覆盖中文平台（B站、小红书、V2EX、雪球）并返回干净的结构化数据
- 通过 `agent-reach channels` 等子命令管理可用渠道

**技术亮点**: Python 3.10+ 实现，MIT 协议开源；以 CLI 形式集成，可被 Claude Code、Codex、OpenClaw 等 CLI Agent 直接调用，无需额外 API 费用。

---
