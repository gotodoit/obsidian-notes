---
tags:
  - github-trending
  - daily
date: 2026-10-28
created: 2026-10-28T01:55:43.406Z
---

# 2026-10-28 GitHub Trending Top 10

## 1. [elayadesign/ai-design-skills](https://github.com/elayadesign/ai-design-skills)
- **语言**: Unknown
- **Stars**: 9,469
- **简介**: 

### AI 总结
**简介**: 一个面向 AI 编程工具（Claude Code、Cursor、Codex、Windsurf 等）的设计技能集合，每个技能以独立文件夹形式提供，可按需安装。

**核心功能**:
- **landing-page-design**：从零构建落地页，涵盖需求提问、页面结构、转化文案，以及完整的视觉系统（字体、间距、圆角、动效）。
- **多工具兼容安装**：提供 Claude Code、Cursor、Codex、Windsurf、Cline 及 Claude.ai 的接入方式，统一以 `SKILL.md` 规则文件形式分发。
- **可自定义设计值**：每个技能的字体、颜色、间距、动效等设计参数集中在文件底部单一区块，Fork 后修改该区块即可整体调整风格。

**技术亮点**: 采用“自包含技能文件夹 + Markdown 规则文件”的轻量架构，不依赖特定工具链；通过 `SKILL.md` 适配各类 AI 工具的项目规则路径（如 `.cursor/rules`、`AGENTS.md`、`.windsurfrules`），实现跨平台复用。

---
## 2. [Nutlope/hallmark](https://github.com/Nutlope/hallmark)
- **语言**: CSS
- **Stars**: 39,091
- **简介**: Anti-AI-slop design skill for Claude Code, Cursor, and Codex.

### AI 总结
**简介**: Hallmark 是一个面向 Claude Code、Cursor、Codex 等 AI 编程工具的设计技能，旨在让 AI 生成的网页摆脱“AI 味”，产出真正像人设计、围绕用户目标构建的页面。

**核心功能**:
- **反 AI 套路设计**：内置检测规则，拒绝“每个标题上方的小字眉标”“彩色单词标题”“满屏空框或纯图片”“每页底部邮箱订阅”“假表单”等典型机器生成痕迹，并由全新上下文的审查者做最终把关。
- **分级质量门禁**：分三层——Floor（对比度、焦点、减少动效、虚构事实、手机布局等硬性底线，绝不放过）、Reflex（模型易犯的默认套路，有理由可记录在案后推翻）、Finish（不阻塞发布的工艺细节）。
- **五十套主题**：每套主题是一种“材质”（纸张、字体、色彩、表面、组件与纹理），附成品页效果图；主题只定义材质不规定页面结构，同一主题下两次生成会得到不同页面。
- **按任务构建页面**：预约页负责预约、商店页负责售卖、订阅页负责订阅，核心动作放在该类页面应有的位置并以它收尾。
- **真实产品与真实照片**：可指向 URL、开发服务器或应用自动截图；内置 755 张开放授权照片，按主题挑选并在页面上署名。
- **重设计与审计**：`/hallmark redesign <path>` 在保留内容和接线的前提下重建页面；`/hallmark audit <path>` 仅输出报告。

**技术亮点**: 项目以 CSS 为主要语言；主题以单文件形式组织（位于 `references/themes/`，每个不超过 8KB，构建时只读取一个），并在真实浏览器中对结果进行 lint 检测；支持定制页面（仅凭提示词按同一套规则设计）。

---
## 3. [nightly-labs/openbot](https://github.com/nightly-labs/openbot)
- **语言**: TypeScript
- **Stars**: 2,492
- **简介**: A local-first desktop workspace for persistent AI teammates. Run Codex, Claude, and Grok with dedicated workspaces, task queues, file sharing, browser control, and agent-to-agent collaboration.

### AI 总结
**简介**: OpenBot 是一个本地优先的桌面工作区，让 Codex、Claude、Grok 等多个 AI 代理各自拥有独立工作区和会话，并支持任务队列、文件共享、浏览器控制与代理间协作。

**核心功能**:
- 支持 Codex App Server、Claude Code、Grok CLI，并通过 ACP 接入 OpenCode、Gemini、Cursor CLI、Cline CLI 等代理
- 每个代理拥有独立会话与本地工作区，支持提示驱动的创建与编辑（含指令、头像）
- FIFO 消息队列，支持暂停、恢复、取消及崩溃安全持久化
- 代理间消息、回复、表情、图片与托管文件传输
- 共享桌面频道聊天，支持任务委派及 Stop/Resume/Reassign/Archive/Restore 控制
- 持久化内嵌浏览器，代理可打开、检查并控制网页
- 支持自定义 OpenAI 兼容端点与自定义 ACP 代理，自动检测本地模型服务（Ollama、LM Studio）
- 逐代理上下文监控，长对话前自动压缩
- 可选 Computer Use（macOS/Windows/Linux），通过 `cua-driver` 子进程实现

**技术亮点**: 基于 TypeScript 开发，采用本地优先架构；账号 API 运行于 Cloudflare Workers 与 D1；跨平台分发（macOS DMG、Windows 安装包、Linux AppImage），Linux 下附带 AppArmor 配置以适配受限的用户命名空间。项目采用 PolyForm Noncommercial 1.0.0 许可，目前为开发预览版，代理默认以 `danger-full-access` 和 `approvalPolicy: never` 运行，需谨慎使用。

---
## 4. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 306,476
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，基于可组合的技能（skills）与初始指令构建，让智能体自动遵循规范化开发流程。

**核心功能**:
- 需求澄清：智能体不会直接写代码，而是先退一步询问用户真正想达成的目标，从对话中提炼出规格说明。
- 分块评审：将规格说明拆成足够短、易于阅读消化的片段呈现给用户确认。
- 实现计划：设计通过后生成清晰可执行的计划，强调红/绿 TDD、YAGNI 与 DRY 原则。
- 子智能体驱动开发：用户确认后启动多智能体流程，逐个完成工程任务并检查、审查其产出，可持续自主工作数小时而不偏离计划。
- 自动触发：技能自动生效，用户无需额外操作即可让智能体获得 Superpowers 能力。
- 多平台安装支持：覆盖 Claude Code、Codex、Cursor、Gemini CLI、GitHub Copilot CLI、Qwen Code 等十余种编码智能体环境。

**技术亮点**: 以 Shell 为主要语言实现；采用可组合技能（composable skills）架构，通过初始指令确保智能体主动调用技能；支持各 harness 独立安装，并提供官方与自建插件市场两种分发渠道。

---
## 5. [pbakaus/impeccable](https://github.com/pbakaus/impeccable)
- **语言**: Rust
- **Stars**: 90,619
- **简介**: The design language that makes your AI harness better at design.

### AI 总结
**简介**: Impeccable 是一套面向 AI 编码代理的设计指导工具，通过技能、命令和检测规则帮助 AI 生成更优质的前端设计，摆脱千篇一律的 SaaS 模板风格。

**核心功能**:
- **一键初始化**：`/impeccable init` 记录产品持久事实到 `PRODUCT.md`，让后续命令理解受众、目标、约束和语气。
- **24 个设计命令**：涵盖 `craft`、`critique`、`polish`、`audit`、`bolder`、`quieter`、`distill`、`animate`、`harden`、`onboard` 等，覆盖从规划、审查到打磨的完整设计流程。
- **62 条确定性检测规则**：CLI 和浏览器扩展无需 LLM 或 API 密钥即可运行，另附 LLM 专属评审检查。
- **实时浏览器迭代**：`live` 和 `generate` 命令支持在浏览器中直接迭代和生成元素变体。
- **反模式指导**：明确列出应避免的设计陋习，如滥用 Inter 字体、紫蓝渐变、卡片嵌套卡片、彩色背景上的灰字等。

**技术亮点**: 核心引擎为 Rust 编写的自包含二进制文件，首次运行时下载至 `~/.impeccable/bin/`，无需独立运行时；通过 `npx impeccable install` 安装，Node 仅用于启动器；支持通过 `pin` 命令创建独立快捷方式。

---
## 6. [makecindy/cindy](https://github.com/makecindy/cindy)
- **语言**: TypeScript
- **Stars**: 7,506
- **简介**: Consider it done. The open-source AI agent that works out of the box · 想到，就能做到。开源、开箱即用的 AI Agent。

### AI 总结
**简介**: Cindy 是一款开源、开箱即用的 AI Agent，可将多台电脑与手机连接成统一工作环境，并整合 Claude Code、Codex、Pi 等现有 Agent 工作流。

**核心功能**:
- **多设备协同**：在电脑与手机间无缝接续同一会话、访问文件，共享其他设备上配置的模型提供商（含订阅、API 与本地模型），并支持手机远程桌面操作电脑。
- **多 Agent 整合**：统一接入 Claude Code、Codex、Pi 等 harness，可随时切换模型组合；支持多 Agent 分工协作（规划、并行实现、独立审查）。
- **真实工具操作**：直接操作文件、浏览器与应用，输出图表、交互控件和富 HTML；支持 automations 定时任务及 Slack、Telegram 等聊天渠道交付工作。
- **可扩展与定制**：通过 Skills、插件和 MCP 接入工具，在 SkillHub 发现扩展；可自定义角色、指令与记忆，沉淀可复用的工作方式。

**技术亮点**: 基于 TypeScript 开发，客户端采用 Apache-2.0 开源许可；以"个人电脑即服务器"架构实现免自托管的多设备远程访问，项目文件保留在本地；提供官方插件仓库与 CI 流程，支持社区共建。

---
## 7. [gitroomhq/postiz-app](https://github.com/gitroomhq/postiz-app)
- **语言**: TypeScript
- **Stars**: 39,422
- **简介**: 📨 The ultimate agentic social media scheduling tool 🤖

### AI 总结
**简介**: Postiz 是一个开源的社交媒体管理与智能体调度平台，支持内容的排期、自动化发布与效果分析，可自托管部署或使用云服务。

**核心功能**:
- 多平台内容排期发布，覆盖 Instagram、YouTube、LinkedIn、TikTok、X、Reddit、Threads、Mastodon、Bluesky、Slack、Discord 等主流社交平台
- 与多种 AI 智能体集成（如 ChatGPT、Claude、Cursor、MCP Server 等），实现智能化的内容创作与发布调度
- 提供内容分析能力，并配套 Public API、NodeJS SDK、N8N 自定义节点及 Make.com 集成，便于自动化工作流扩展

**技术亮点**: 基于 TypeScript 开发，采用 AGPL-3.0 开源协议；提供云端托管与自托管两种部署模式，并通过 SDK、API 和第三方自动化平台（N8N、Make.com）构建可扩展的集成生态。

---
## 8. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 290,926
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个面向 AI 编程代理（Agent Harness）的性能优化系统，为 Claude Code、Codex、Opencode、Cursor 等工具提供技能、直觉、记忆、安全与研究优先的开发能力。

**核心功能**:
- **技能与直觉（Skills & Instincts）**: 为编程代理注入可复用的技能与行为直觉，提升任务执行质量
- **记忆系统（Memory）**: 为代理提供持久化记忆能力，支持上下文延续
- **安全防护（Security）**: 提供 `ecc-agentshield` 安全组件，保障代理运行安全
- **研究优先开发（Research-first Development）**: 强调先调研再动手的开发范式
- **多平台适配**: 兼容 Claude Code、Codex、Opencode、Cursor 等多种代理工具，并提供插件（`ecc@ecc`）、GitHub App 与 npm 包（`ecc-universal`）多种安装方式

**技术亮点**: 以 JavaScript 为主，同时涉及 Shell、TypeScript、Python、Go、Java、Perl 等多语言生态；采用插件化架构（Claude Code 原生插件），提供 npm 包分发与 GitHub App 集成；文档支持 16 种语言本地化，采用 MIT 开源协议。

---
## 9. [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)
- **语言**: Python
- **Stars**: 46,011
- **简介**: DeepTutor: Lifelong Personalized Tutoring. https://deeptutor.info/.

### AI 总结
**简介**: DeepTutor 是香港大学数据科学实验室（HKUDS）推出的终身个性化 AI 辅导系统，提供持续陪伴式的学习体验。

**核心功能**:
- 终身个性化辅导：根据学习者情况提供持续、定制化的教学支持
- 多语言支持：README 提供中、英、日、法、阿拉伯、俄、印地、葡、泰、波兰等十余种语言版本
- CLI / Agent 原生接口：提供命令行与智能体交互方式
- 配套技能社区生态（EduHub），支持扩展与协作

**技术亮点**: 后端基于 Python 3.11+，前端采用 Next.js 16，遵循 Apache 2.0 开源协议，并有配套学术论文（arXiv:2604.26962）支撑；项目曾登上 GitHub Trending 日榜，社区活跃（Discord、飞书、微信群）。

---
## 10. [JetBrains/thinkrail](https://github.com/JetBrains/thinkrail)
- **语言**: TypeScript
- **Stars**: 4,061
- **简介**: Vibe code with pi in a lightweight, real IDE that customises itself around the way you work — The Vibe You Need

### AI 总结
**简介**: ThinkRail 是 JetBrains 孵化的一款 TypeScript 编写的智能体 IDE，围绕 `pi` 编码智能体构建，能通过“活规格文档”持续学习项目，并随使用逐步增强自身能力。

**核心功能**:
- **隔离工作区**：将任意 Git 仓库作为项目，以 `git worktree` 切分出独立分支和工作目录，支持智能体并行工作；工作区在 PR 合并/关闭或闲置一周后自动“沉降”到项目搁架，并可随时恢复；顶栏展示分支与 `origin`、PR 的状态，支持一键发布、推送、创建 PR、合并及处理 CI 失败。
- **围绕智能体的真实 IDE**：可分割的 Monaco 编辑器标签、带实时 Git 变更标记的 Files 树、终端与文档，均限定于当前工作区；支持在文件/差异上留锚定评审评论并作为结构化上下文发送给对话。
- **流式对话**：每个工作区可并发多个 `pi` 会话，各自独立模型并实时显示 token 与费用；支持引导运行中的回合、排队后续指令、委派子智能体，以及共享可编辑计划（每步可单独提交和评审）。
- **规格即事实来源**：代码旁维护由 `SPEC.md` 文件构成的关联图谱，智能体通过专用 `spec_*` 工具读取、搜索和维护，使意图跨会话留存；只读 Specs 工具在工作台中以树形渲染该图谱。
- **技能与工作流**：直接读取已有的可移植 Agent Skills，内置工作流引导项目搭建、设计头脑风暴及 PR 交付（推送分支并创建/更新 GitHub PR）。

**技术亮点**: 基于 TypeScript 与 Monaco 编辑器构建；以 `pi` 编码智能体为核心，结合 `git worktree` 实现工作区隔离；采用 `SPEC.md` 图谱式活规格与可复用技能实现持久项目知识，并规划完整的扩展支持，使 IDE 能按用户工作方式自建工具。

---
