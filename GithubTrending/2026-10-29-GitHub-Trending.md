---
tags:
  - github-trending
  - daily
date: 2026-10-29
created: 2026-10-29T01:55:43.100Z
---

# 2026-10-29 GitHub Trending Top 10

## 1. [JetBrains/thinkrail](https://github.com/JetBrains/thinkrail)
- **语言**: TypeScript
- **Stars**: 5,124
- **简介**: Vibe code with pi in a lightweight, real IDE that customises itself around the way you work — The Vibe You Need

### AI 总结
**简介**: ThinkRail 是 JetBrains 孵化的一款 TypeScript 编写的智能体 IDE，围绕 `pi` 编码智能体构建，能随使用不断学习并适配个人工作方式。

**核心功能**:
- **隔离工作区**：将任意 git 仓库作为项目，以 `git worktree` 切分出独立分支和工作目录的工作区，支持多个智能体并行工作，并可自动归档、恢复已完成或闲置的工作区。
- **围绕智能体的真实 IDE**：可分割的 Monaco 编辑器、带实时 git 变更标记的文件树、终端和文档，支持在文件与 diff 上留锚定评审评论并作为结构化上下文发送给对话。
- **流式智能体对话**：每个工作区可运行多个并发 `pi` 会话，各自独立模型并实时显示 token 与费用；支持中途引导、排队追问、委派子智能体和共享计划。
- **Specs 作为事实来源**：与代码并存的 `SPEC.md` 文件连通图，智能体通过专用 `spec_*` 工具读取、检索和维护，使意图跨会话延续。
- **技能与工作流**：可直接读取已有的可移植 Agent Skills，内置工作流引导项目搭建、设计头脑风暴和 PR 交付。
- **GitHub 集成**：顶栏展示分支相对 `origin` 与 PR 的状态，一键发布、推送或创建 PR，并查看 CI 检查与评审结果。

**技术亮点**: 基于 TypeScript 开发；以 `pi` 编码智能体为核心，采用 git worktree 实现工作区隔离，Monaco 作为编辑器内核，并通过可扩展的 Specs 图与 Skills 机制实现持久化项目知识与能力自扩展。

---
## 2. [elayadesign/ai-design-skills](https://github.com/elayadesign/ai-design-skills)
- **语言**: Unknown
- **Stars**: 11,190
- **简介**: 

### AI 总结
**简介**: 一个面向 AI 编程工具（Claude Code、Cursor、Codex、Windsurf 等）的设计技能集合，每个技能为独立文件夹，可按需安装。

**核心功能**:
- **landing-page-design**：从零构建落地页，涵盖需求提问、页面结构、转化文案，以及完整的视觉系统（字体、间距、圆角、动效）
- 支持多工具安装：Claude Code（克隆到 `.claude/skills`）、Cursor（下载到 `.cursor/rules`）、Codex/Windsurf/Cline（复制 `SKILL.md` 到对应规则文件）、Claude.ai（上传至 Project 或对话附件）
- 可自定义：每个技能的设计值（字体、颜色、间距、动效）集中在文件底部一处，Fork 后修改即可全局生效

**技术亮点**: 基于 Markdown 规则文件（`SKILL.md`）的轻量技能架构，每个技能自包含、即插即用；`landing-page-design` 的内容真实感与动效思路改编自 MIT 许可的 Leonxlnx/taste-skill 项目；整体采用 MIT 许可，可自由使用、修改与商用。

---
## 3. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 307,492
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，由一组可组合的技能和初始指令构成，让智能体自动遵循规范化的开发流程。

**核心功能**:
- **需求澄清与规格设计**：智能体不会直接写代码，而是先退一步询问真实目标，从对话中提炼规格，并以易于消化的小块形式呈现给用户确认
- **实现计划生成**：设计确认后，生成足够清晰的实施计划，强调红/绿 TDD、YAGNI 和 DRY 原则
- **子智能体驱动开发**：用户确认后启动子智能体逐个完成工程任务，自动检查与审查工作成果，可长时间自主按计划推进而不偏离
- **自动触发**：技能自动触发，无需额外操作，智能体即具备 Superpowers 能力

**技术亮点**: 基于 Shell 实现；采用可组合技能（composable skills）架构；支持多种编码智能体平台（Claude Code、Cursor、Gemini CLI、Codex、GitHub Copilot CLI、Qwen Code 等十余种 harness），各平台独立安装；提供官方与自建插件市场两种分发方式；另有商业支持服务。

---
## 4. [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)
- **语言**: Python
- **Stars**: 48,093
- **简介**: DeepTutor: Lifelong Personalized Tutoring. https://deeptutor.info/.

### AI 总结
**简介**: DeepTutor 是香港大学数据科学实验室（HKUDS）开源的终身个性化 AI 辅导系统，提供自适应、可持续的学习陪伴体验。

**核心功能**:
- 终身个性化辅导：围绕学习者长期成长提供持续、定制的教学支持
- 多语言支持：README 提供中、英、日、韩、法、阿、俄等十余种语言版本，面向全球用户
- 双接口形态：同时提供 Web 应用与 Agent 原生的 CLI 命令行接口
- 技能生态：配套 EduHub 技能社区，支持扩展教学能力
- 活跃的社区协作：通过 Discord、飞书、微信群及 Roadmap 议题接受贡献与反馈

**技术亮点**:
- 后端基于 Python 3.11+，前端采用 Next.js 16
- 采用 Agent 原生（Agent-native）架构设计
- 以 Apache 2.0 协议开源，并有配套 arXiv 论文支撑
- 项目热度较高，曾登上 GitHub Trending 日榜与 Trendshift 榜单

---
## 5. [macro-inc/macro](https://github.com/macro-inc/macro)
- **语言**: Rust
- **Stars**: 5,445
- **简介**: Macro is a unified workspace for teams: email, chat, docs, tasks, agents, calls, and CRM — @-linked together with shared AI memory.

### AI 总结
**简介**: Macro 是一款用 Rust 构建、面向团队的一体化工作空间，将邮件、聊天、文档、任务、Agent、通话和 CRM 通过共享 AI 记忆与 @ 关联整合到单一快速界面中。

**核心功能**:
- **Email**：多账户统一收件箱、键盘优先操作、共享收件箱与 Gmail 集成，并内置 AI 工具与 MCP 接口
- **Messages**：面向技术讨论的频道与私信
- **Tasks**：Linear 风格任务管理，与频道、邮件、Agent 深度集成
- **Docs**：基于 CRDT 的实时协作、Markdown 原生文档，支持 @mentions
- **Canvas**：2D 画布，可嵌入任务、文件、邮件的 @ 链接
- **Agents**：团队级统一记忆，可代为执行操作
- **Calls**：通话录制、转写并写入团队记忆供 Agent 使用
- **File storage**：从邮件和频道自动导入文件，支持全文搜索
- **Pull requests**：关联任务、嵌入频道，并可被 Agent 访问
- **CRM**：客户与联系人对象、自定义属性、邮件同步与信息补全

**技术亮点**: 前端采用 SolidJS，后端采用 Rust，兼顾速度与可靠性；所有模块共享同一后端，文档与任务、频道消息与邮件之间的交叉引用以**双向图**原生存储；文档基于 CRDT 实现实时协作；每个界面按用途专门构建而非通用组件拼装，模块化设计如乐高般可组合扩展。

---
## 6. [Nutlope/hallmark](https://github.com/Nutlope/hallmark)
- **语言**: CSS
- **Stars**: 40,791
- **简介**: Anti-AI-slop design skill for Claude Code, Cursor, and Codex.

### AI 总结
**简介**: Hallmark 是 Together AI 推出的设计技能，适用于 Claude Code、Codex、Cursor 和 OpenCode，旨在让 AI 生成的页面摆脱"AI 味"，呈现真实的人类设计质感。

**核心功能**:
- **五十套主题材质**：从 50 种"材质"（纸张、字体、色彩、表面、组件与纹理）中抽取三套构建页面，每个主题不超过 8KB，附带成品页示意图
- **以任务为导向的布局**：根据页面类别（预订、售卖、订阅等）将核心操作放在合理位置，并以该操作收尾
- **真实浏览器 lint 检查**：在真实浏览器中检测机器生成痕迹（如每个标题上方的小标签、标题中单个着色词、空框架页面、结尾千篇一律的邮件订阅表单等）
- **分级质量门禁**：Floor（对比度、焦点、减少动效、虚构事实、移动端布局等，绝不发布）、Reflex（模型默认倾向，可记录理由后覆盖）、Finish（工艺细节，不阻塞发布）
- **自定义设计**：仅凭提示词按同一规则与检查生成定制页面
- **真实产品截图**：指向 URL、开发服务器或应用即可自动截图
- **755 张开放授权照片**：按主题挑选并在页面标注出处
- **重设计与审计**：`/hallmark redesign <path>` 重建页面并保留内容与接线；`/hallmark audit <path>` 仅输出报告

**技术亮点**: 采用"材质而非模板"的设计理念——主题只定义视觉材质，不规定页面内容与顺序，因此同一主题下不同提示词会产出不同页面；引入全新上下文的审查者做最终把关；以 CSS 为主要实现语言。

---
## 7. [pbakaus/impeccable](https://github.com/pbakaus/impeccable)
- **语言**: Rust
- **Stars**: 92,804
- **简介**: The design vocabulary for your coding agent. Steer with polish and bolder, review with critique and audit, catch AI slop before it ships.

### AI 总结
**简介**: Impeccable 是一套面向 AI 编码代理的设计词汇工具，通过命令化指令帮助开发者引导、审查和打磨界面设计，避免 AI 生成千篇一律的“设计垃圾”。

**核心功能**:
- **引导设计方向**：提供 `bolder`、`quieter`、`distill`、`colorize`、`typeset`、`layout`、`animate`、`delight`、`overdrive` 等命令，用精确词汇替代“让它更出彩”这类模糊指令
- **设计审查**：`critique` 按可用性启发式打分并排序修复优先级；`audit` 检查可访问性、性能、主题和响应式行为，按 P0–P3 分级
- **AI 套路检测**：62 条确定性规则识别紫色渐变、卡片嵌套卡片、圆角图标块等常见 AI 设计痕迹，无需 LLM 或 API Key
- **收尾与迭代**：`polish`、`harden`、`clarify`、`adapt`、`optimize`、`onboard` 完成上线前打磨；`live` 支持浏览器内选取元素并循环切换变体
- **上下文管理**：`init` 生成 `PRODUCT.md`，`document` 生成 `DESIGN.md`，`extract` 提炼设计系统，共 24 个命令

**技术亮点**: 基于 Rust 开发，通过 `npx impeccable install` 安装；兼容 Claude Code、Cursor、Codex CLI、GitHub Copilot、Gemini CLI 等 20 余种编码工具；采用确定性规则引擎而非 LLM 做设计检测，结果稳定且零 API 成本。

---
## 8. [makecindy/cindy](https://github.com/makecindy/cindy)
- **语言**: TypeScript
- **Stars**: 8,138
- **简介**: Consider it done. The open-source AI agent that works out of the box · 想到，就能做到。开源、开箱即用的 AI Agent。

### AI 总结
**简介**: Cindy 是一款开源、开箱即用的 AI Agent，可连接多台电脑与手机，让用户在自己已有的设备和模型订阅上完成真实工作。

**核心功能**:
- **多设备统一协作**：在电脑、笔记本和手机间共享同一会话、文件与模型配置，支持从任意设备继续工作
- **内置手机远程桌面**：在手机上操作已连接的电脑，打开应用、输入内容，补充聊天之外的桌面操作能力
- **多 Agent 框架整合**：统一接入 Claude Code、Codex 与 Pi，可按任务切换框架与模型组合，并支持多 Agent 分工（规划、并行实现、独立评审）
- **真实工具环境作业**：直接操作文件、浏览器和应用，输出可包含图表、交互控件与富 HTML
- **自动化与外部渠道接入**：支持定时自动化任务，可通过 Slack、Telegram 等聊天渠道分派工作
- **可扩展与可定制**：支持 Skills、插件与 MCP，可在 SkillHub 发现扩展，并创建具有角色、指令和记忆的自定义 companion

**技术亮点**: 采用 TypeScript 开发；以用户电脑作为服务器，无需自建服务端或租用服务器；客户端基于 Apache-2.0 协议开源，可审计、可 Fork、可修改；支持 macOS、Windows、Linux、iOS 与 Android 多平台。

---
## 9. [nightly-labs/openbot](https://github.com/nightly-labs/openbot)
- **语言**: TypeScript
- **Stars**: 3,290
- **简介**: A local-first desktop workspace for persistent AI teammates. Run Codex, Claude, and Grok with dedicated workspaces, task queues, file sharing, browser control, and agent-to-agent collaboration.

### AI 总结
**简介**: OpenBot 是一个本地优先的桌面工作区，让多个 AI 编码智能体（Codex、Claude、Grok 等）以持久化"AI 队友"的形式并行协作。

**核心功能**:
- 支持 Codex App Server、Claude Code、Grok CLI，并通过 ACP 接入 OpenCode、Gemini、Cursor CLI、Cline CLI
- 每个智能体拥有独立工作区、会话、模型与上下文配置，支持长对话自动压缩
- FIFO 消息队列，支持暂停、恢复、取消及崩溃安全持久化
- 智能体间消息、回复、文件传输与共享频道协作（委派、重新分配、归档等）
- 内置持久化浏览器，智能体可打开、检查并控制页面
- 可选 Computer Use（macOS/Windows/Linux），通过 `cua-driver` 子进程实现
- 支持自定义 OpenAI 兼容端点与本地模型服务器（Ollama、LM Studio）检测

**技术亮点**: 基于 TypeScript 构建，采用本地优先架构；账号 API 运行于 Cloudflare Workers + D1；跨平台打包（macOS dmg、Windows exe、Linux AppImage）；注意当前为开发预览版，智能体默认以 `danger-full-access` 无审批模式运行，需谨慎使用。

---
## 10. [togg53192-cmd/jailbreaks](https://github.com/togg53192-cmd/jailbreaks)
- **语言**: Unknown
- **Stars**: 7,185
- **简介**: LIST OF ALL MY JAILBREAKS

### AI 总结
**简介**: 一个收录 32 份系统提示词、人格设定、工作区策略与智能体操作规范的提示词合集，覆盖闭源前沿模型、开源权重模型及免费隐身模型共 26 个以上目标。

**核心功能**:
- 按模型厂商分类整理提示词文件：OpenCode Zen 免费隐身模型、Anthropic Claude（Opus/Sonnet）、智谱 GLM/ZCode、DeepSeek、Moonshot Kimi、xAI Grok、NVIDIA Nemotron、Google Gemini、Mistral、阿里 Qwen 等
- 每份文件均为完整可直接粘贴使用的成品，包含系统提示词、人格定义、`AGENTS.md` 文件、配置块与 Ollama Modelfiles
- 覆盖编码智能体与工作区指令格式，以及 harness 专用配置
- 提供合集目录与使用说明入口，便于快速定位所需文件

**技术亮点**: 聚焦指令层级、人格框架、提示词冲突与策略覆盖对模型行为的影响，可作为研究提示注入防御与指令操纵抵抗能力的参考资料；仓库声明仅限研究与教育用途，并附有使用警告。

---
