---
tags:
  - github-trending
  - daily
date: 2026-10-26
created: 2026-10-26T01:55:43.411Z
---

# 2026-10-26 GitHub Trending Top 10

## 1. [makecindy/cindy](https://github.com/makecindy/cindy)
- **语言**: TypeScript
- **Stars**: 4,936
- **简介**: Consider it done. The open-source AI agent that works out of the box · 想到，就能做到。开源、开箱即用的 AI Agent。

### AI 总结
**简介**: Cindy 是一款开源、开箱即用的本地 AI Agent，将多种 harness、模型和工具整合为一体，可直接在用户自己的电脑上使用真实文件和已登录应用完成实际工作。

**核心功能**:
- 多 harness 与多模型自由混用：首批支持 Claude Code 和 Codex，可在任务进行中切换模型或 harness，而工作区、记忆、技能和工具保持连续
- 支持多 Agent 协同：同一任务可由不同 harness × 模型组合的 Agent 分别规划、并行执行和审查
- 可驱动浏览器、电脑和手机，并能从即时通讯（IM）和定时任务接收工作
- 记忆（纠正一次即长期生效并跨 harness 共享）、技能（一次教授、处处复用）、自动化（周期性任务自动调度与汇报）
- 通过 MCP 接入内部工具和业务系统，并支持插件扩展功能、UI 与交互
- 灵活的模型接入方式：官方 Cindy 服务、已有的 Claude Code / Codex Coding Plan 授权、自有 API Key 或本地模型
- 支持跳过登录使用本地 Agent（此时服务端能力不可用）

**技术亮点**:
- 采用 pnpm monorepo 架构，包含 Electron 桌面端（`apps/desktop`）、Expo / React Native 移动端（`apps/mobile`）及共享能力包（认证、设备互联、Agent 编排、模型提供方等）
- 技术栈为 TypeScript，要求 Node.js 22.x、pnpm 10.x 和 Git LFS
- 桌面端工具二进制（claude-code、codex、ripgrep）按平台在安装时下载，Android platform-tools 在打包前拉取并进行 sha256 校验
- 后端服务独立于本仓库，客户端源码以 Apache-2.0 协议开源，可审计、分支和扩展

---
## 2. [Nutlope/hallmark](https://github.com/Nutlope/hallmark)
- **语言**: CSS
- **Stars**: 33,901
- **简介**: Anti-AI-slop design skill for Claude Code, Cursor, and Codex.

### AI 总结
**简介**: Hallmark 是一款面向 Claude Code、Codex、Cursor 和 OpenCode 的设计技能，旨在让 AI 生成的页面摆脱“AI 味”，呈现出真正经过设计的效果。

**核心功能**:
- **48 套主题材质**：每套主题是一个独立的“材质”（纸张、字体、色彩、表面质感等），自带成品页面示例；主题只决定视觉材质，不规定页面内容与结构，同一主题下不同提示词会生成不同页面。
- **按任务目标构建页面**：预订页能预订、商店页能售卖、订阅页能订阅，核心操作放在符合品类习惯的位置，并作为页面收尾。
- **真实产品截图**：可指向 URL、开发服务器或应用，自动捕获截图用于页面。
- **真实照片**：内置 755 张开放授权照片，按主题挑选并在页面中署名。
- **重设计与审计**：`/hallmark redesign <path>` 重建页面并保留内容与接线，`/hallmark audit <path>` 仅输出报告。
- **自定义设计**：输入 custom 即可仅依据提示词在相同规则与检查下进行设计。

**技术亮点**: 采用分层质量门禁机制——**Floor**（对比度、焦点、减少动效、虚构事实、移动端布局等）为绝不放行的硬底线；**Reflex**（模型易陷入的默认套路）可在有理由并记录在案时被覆盖；**Finish** 为不影响发布的工艺细节检查。最终由全新上下文的审查者做终审，并在真实浏览器中针对“机器感”特征（如每个标题上方的眉标、字距大写标签、标题中单个彩色词、空框架页面、错位的首屏等）进行 lint。主题文件位于 `references/themes/`，每个不超过 8 KB，构建时只读取一个。

---
## 3. [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio)
- **语言**: Python
- **Stars**: 86,932
- **简介**: VoiceStudio is the open-source, fully-local ElevenLabs alternative — voice cloning, voice design, video dubbing, dictation, transcription & audiobook creation in 646 languages.

### AI 总结
**简介**: VoiceStudio 是一个完全本地运行的开源语音工作台，定位为 ElevenLabs 的开源替代品，支持 646 种语言的语音克隆、语音设计、视频配音、听写、转录与有声书制作。

**核心功能**:
- 语音克隆与语音设计：克隆已有声音，或通过文字描述自定义生成音色
- 视频配音：为视频生成带时间轴对齐的语音
- 听写与转录：通过浮动小组件进行语音输入，支持音频转录
- 有声书与批量任务：支持故事、有声书制作及批量作业
- 本地 API 与 MCP 接口：供智能体调用，支持可复用配方与监听文件夹
- 模型管理：安装和管理本地语音模型，默认引擎为 k2-fsa/OmniVoice，也可切换其他引擎

**技术亮点**: 基于 Python 开发，桌面端使用 Electron 构建；全流程在本地硬件上运行，远程服务为可选项且分析数据需用户同意；OmniVoice GGUF 构建在 Windows/Linux 上可选启用 Vulkan 加速，并支持 CPU 回退；提供 macOS/Linux 一键安装脚本与 Windows PowerShell 安装方式，发布格式涵盖 `.dmg`、`.exe`、`.AppImage` 和 `.deb`；采用 AGPL-3.0 许可证。

---
## 4. [pbakaus/impeccable](https://github.com/pbakaus/impeccable)
- **语言**: Rust
- **Stars**: 87,763
- **简介**: The design language that makes your AI harness better at design.

### AI 总结
**简介**: Impeccable 是一套面向 AI 编程代理的设计语言与技能包，帮助 AI 生成的前端设计摆脱千篇一律的模板化风格。

**核心功能**:
- **一键初始化**：`/impeccable init` 将产品定位、受众、约束等持久化写入 `PRODUCT.md`，为后续命令提供稳定上下文
- **24 个设计命令**：通过 `/impeccable <command>` 调用，涵盖 `craft`、`critique`、`audit`、`polish`、`bolder`、`distill`、`animate`、`harden` 等，覆盖从规划、审查到打磨的完整设计流程
- **62 条确定性检测规则**：CLI 与浏览器扩展可在无 LLM、无 API Key 的情况下运行规则检测，配合 LLM 专属的批评性检查
- **实时浏览器迭代**：`live` 与 `generate` 命令支持在浏览器中直接迭代视觉方案
- **反模式指导**：明确规避滥用字体、彩色背景上的灰字、纯黑灰、卡片嵌套、过时弹性缓动等常见问题

**技术亮点**: 使用 Rust 编写核心引擎，以自包含二进制形式分发（首次运行自动下载至 `~/.impeccable/bin/`），技能本身无需独立运行时，Node 仅用于安装环节。

---
## 5. [pollen-robotics/microduck](https://github.com/pollen-robotics/microduck)
- **语言**: Rust
- **Stars**: 11,698
- **简介**: A Tiny biped duck robot 🦆

### AI 总结
**简介**: Microduck 是 Pollen Robotics 开发的一款约 25 厘米、800 克的微型双足鸭子机器人，本仓库是其运行在 Rockchip RK3566 上的“大脑”软件。

**核心功能**:
- 行走：通过手柄操控双足行走
- 轮式模式：安装轮子后切换为滚动模式
- 拾取物品：一键低头用喙拾取
- 自主起身：被推倒后可自行站起
- 其他动作：坐下、踢球、前进滚动、发出专属鸭叫声

**技术亮点**:
- 使用 Rust 编写，无框架，单一 workspace
- 50 Hz 控制循环驱动 15 个舵机，运行神经网络策略（ONNX 格式，由 microduck_rl 仓库用 MuJoCo + PPO 训练并 sim2real 导出）
- 多守护进程架构（robotd、updaterd、configd、btd、padd、mediad、tofd），通过 Unix socket 上的统一 JSON-RPC 契约通信
- 更新机制具备签名验证、健康门控和可回滚能力，防止变砖
- 提供 MuJoCo 仿真环境，可在无实体机器人时运行真实守护进程进行开发调试

---
## 6. [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)
- **语言**: Python
- **Stars**: 114,672
- **简介**: TradingAgents: Multi-Agents LLM Financial Trading Framework

### AI 总结
**简介**: TradingAgents 是 Tauric Research 推出的基于多智能体大语言模型（Multi-Agents LLM）的金融交易框架，用 Python 实现。

**核心功能**:
- 多智能体协作分析：分析师、研究员、交易员、投资组合经理等角色分工协作，完成从信息分析到交易决策的完整流程
- 回测与决策记录：支持按股票代码和日期网格回测，回测仅使用各分析日期当时已发布的数据，避免未来函数；每次决策都会持久化记录并结算
- 灵活模型配置：支持为不同模型层级指定不同提供商，管理层与分析层可运行在不同模型上；支持自备 ChatGPT Plus/Pro 计划运行
- 丰富数据源：集成 SEC EDGAR 财报、FRED 宏观数据、Polymarket、社交情绪、公司新闻等多种数据供应商
- 报告与命令行工具：运行结果可保存为单个 HTML 页面，CLI 支持通过 `--ticker`、`--date` 等参数无交互运行，并支持断点续跑

**技术亮点**: 采用 LangGraph 构建智能体工作流，支持图结构感知的检查点恢复；强调 point-in-time 数据完整性（避免前视偏差）；提供可验证的数据访问契约与扩展的提供商注册表（NVIDIA、Kimi、Groq、Mistral、Bedrock 及任意 OpenAI 兼容端点）；支持 Docker 部署、多语言和 `TRADINGAGENTS_*` 环境变量配置。

---
## 7. [Renhuai123/ziwei-doushu](https://github.com/Renhuai123/ziwei-doushu)
- **语言**: TypeScript
- **Stars**: 7,652
- **简介**: 紫微斗数开源排盘引擎 — 基于倪海厦《天纪》体系，含完整排盘算法、四化系统、格局知识库、古籍原文数据

### AI 总结
**简介**: 基于倪海厦《天纪》体系的紫微斗数开源排盘引擎，以 TypeScript 实现完整排盘算法，并配套发布大规模解读数据集。

**核心功能**:
- 完整紫微斗数排盘算法，含四化系统、格局知识库与古籍原文数据
- 真太阳时校正（经度差 + 均时差）、中国 1986–1991 夏令时处理、农历/公历互转与闰月边界处理
- 十二神煞、运限上下文（含童限）、星曜亮度流派配置
- 发布 v4.0 解读数据集：674,976 张命盘 × 13 维 = 877 万段解读，覆盖 1950–2026 年真实日期，按年份分 77 个文件下载
- 整理倪师《天纪·紫微斗数》原话 1848 条，逐条标注出处与视频时间点，可回放核对

**技术亮点**: TypeScript 编写，模块化拆分（排盘算法、真太阳时、农历转换、流派配置等独立模块）；配套 5 条排盘回归测试与 GitHub Actions CI；代码采用 MIT 协议，数据集采用 CC BY 4.0，倪师原话部分为 CC BY-NC-SA 4.0 非商用授权。

---
## 8. [JetBrains/thinkrail](https://github.com/JetBrains/thinkrail)
- **语言**: TypeScript
- **Stars**: 1,803
- **简介**: Vibe code with pi in a lightweight, real IDE that customises itself around the way you work — The Vibe You Need

### AI 总结
**简介**: ThinkRail 是 JetBrains 孵化的一款“智能体 IDE”，围绕 `pi` 编码智能体构建，通过隔离工作区和“活规格”让智能体持续学习项目，并随使用不断进化。

**核心功能**:
- **隔离工作区**：将任意 Git 仓库作为项目，以 `git worktree` 切分出独立工作区（独立分支与目录），智能体可并行工作且不干扰主检出；支持合并、搁置、自动归置，并集成 GitHub PR 全流程（发布、推送、CI 检查、评审、合并等）。
- **真正的 IDE 体验**：可拆分的 Monaco 编辑器标签、带实时 Git 变更标记的文件树、终端与文档，全部限定于当前工作区；支持在文件与 diff 上留下锚定评审评论并作为结构化上下文发送给对话。
- **流式对话**：每个工作区可同时运行多个 `pi` 会话，各自独立模型与 token/成本实时读数；支持中途引导、排队追问、委派子智能体，以及智能体与你共同编辑的共享计划（每步可单独提交评审）。
- **规格即事实来源**：与代码并存的 `SPEC.md` 连接图，智能体通过专用 `spec_*` 工具读写维护，意图跨会话保留，并在工作台以树形只读视图呈现。
- **技能与工作流**：原地读取已有的可移植 Agent Skills，内置项目搭建、设计头脑风暴、发布 PR 等工作流，通过你自己的 `gh` 推送分支并创建/更新 PR。
- **智能体工具扩展**：网页调研、对话内联图表、选项对比与文件预览（UI 变更前后对比图可像 diff 一样评论）；设置中可开关各扩展。
- **MCP 支持**：连接 `mcp.json` 中的 MCP 服务器，非只读调用前需在对话中确认，仓库定义的服务器需批准后启用，支持 OAuth 登录。
- **自带凭证**：可用 JetBrains AI 登录或通过 `pi` 自身的认证接入任意提供商，ThinkRail 无独立账号体系。
- **桌面应用或浏览器**：原生桌面应用，或通过 `thinkrail` CLI 在浏览器中打开同一应用。

**技术亮点**: 基于 TypeScript 开发；以 `

---
## 9. [coollabsio/coolify](https://github.com/coollabsio/coolify)
- **语言**: PHP
- **Stars**: 64,441
- **简介**: An open-source, self-hostable PaaS alternative to Vercel, Heroku & Netlify that lets you easily deploy static sites, databases, full-stack applications and 360+ one-click services on your own servers.

### AI 总结
**简介**: Coolify 是一个开源、可自托管的 PaaS 平台，作为 Vercel、Heroku、Netlify 的替代方案，让你在自己的服务器上轻松部署静态站点、数据库、全栈应用及 360+ 一键服务。

**核心功能**:
- **应用部署**：支持从 GitHub、GitLab、Bitbucket、Gitea 构建，兼容 Nixpacks、Railpack、Dockerfile、Docker Compose 及预构建镜像
- **数据库与服务**：部署托管数据库及 360+ 一键服务，支持持久化存储与自动生成凭据
- **自动化部署**：Git 推送自动部署、PR 预览环境、部署 Webhook、镜像回滚
- **网络管理**：自定义域名、自动 HTTPS 证书、反向代理、健康检查、容器网络
- **基础设施运维**：多服务器管理、部署与运行时日志、容器终端、资源监控
- **安全与备份**：数据库/存储备份、定时任务、环境变量与密钥管理、通知
- **工作流集成**：仪表盘、API、CLI、MCP 及基于团队的访问控制

**技术亮点**: 基于 PHP 开发；仅需 SSH 连接即可管理任意服务器（VPS、裸金属、树莓派等）；配置保留在自有服务器上，停止使用 Coolify 后运行资源仍可继续工作并保持可管理；提供自托管与 Coolify Cloud 两种模式，后者提供高可用与更低维护成本。

---
## 10. [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill)
- **语言**: JavaScript
- **Stars**: 47,002
- **简介**: A coding-agent skill for multi-phase security audits with independently verified, machine-readable findings

### AI 总结
**简介**: Cloudflare 开源的安全审计技能，将编码 Agent 转化为多阶段安全审计器，产出可独立验证、机器可读的审计结果。

**核心功能**:
- 六阶段结构化审计流程：侦察 → 覆盖率驱动的漏洞挖掘 → 候选验证 → 结构化输出 → 独立记录核验 → 目标无关报告
- 通过 `coverage-ledger.json` 追踪审计覆盖范围，用覆盖率批评者识别遗漏区域
- 每个候选漏洞交给全新验证器尝试证伪，并区分 `confirmed`、`needs_validation`、`rejected` 三种结论
- 内置多类攻击面提示词库，覆盖内存安全/二进制、AI/LLM、Web 协议与认证、客户端、供应链、云部署、RPC/消息、资源耗尽、数据隔离、桌面/移动端等场景
- 支持对同一仓库多次增量审计，利用历史台账定位缺口并复核变更代码

**技术亮点**: 基于 JavaScript 实现，提供零依赖校验脚本（`validate-findings.cjs`、`validate-coverage-ledger.cjs`）配合 JSON Schema 保证输出合规；采用隔离 Agent 分工与独立复核机制降低误报，是 Cloudflare 漏洞发现框架的单一仓库起点。

---
