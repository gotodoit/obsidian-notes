---
tags:
  - github-trending
  - daily
date: 2026-10-30
created: 2026-10-30T01:55:43.656Z
---

# 2026-10-30 GitHub Trending Top 10

## 1. [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)
- **语言**: Python
- **Stars**: 50,198
- **简介**: DeepTutor: Lifelong Personalized Tutoring. https://deeptutor.info/.

### AI 总结
**简介**: DeepTutor 是香港大学数据科学实验室（HKUDS）开源的一款支持终身个性化辅导的 AI 教学系统，提供配套文档站点 deeptutor.info。

**核心功能**:
- 面向学习者的终身个性化辅导体验
- 提供 CLI 命令行与 Agent 原生交互接口
- 构建 EduHub 技能社区生态，支持技能扩展与共享
- 多语言文档支持（中、英、日、法、俄、阿拉伯语等十余种语言）

**技术亮点**:
- 后端基于 Python 3.11+，前端采用 Next.js 16
- 采用 Apache 2.0 开源协议
- 附带 arXiv 论文（2604.26962）说明技术方案
- 提供 Discord、飞书、微信等社区协作渠道，Roadmap 公开征集贡献

---
## 2. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 308,604
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码 Agent 的完整软件开发方法论，由一组可组合的技能（skills）和初始指令构成，让 Agent 在写代码前先澄清需求、设计、规划，再以子 Agent 驱动的方式自主完成实现。

**核心功能**:
- **需求澄清与规格设计**：Agent 启动后不急于写代码，而是先退一步询问用户真实目标，从对话中提炼规格，并分段展示以便阅读和确认。
- **可执行的实现计划**：设计确认后生成清晰的实现计划，标准是“连缺乏判断力、没有项目上下文、讨厌测试的初级工程师也能照着做”，强调红/绿 TDD、YAGNI 和 DRY。
- **子 Agent 驱动的开发流程**：用户确认后启动 subagent-driven-development，由多个 Agent 逐项完成工程任务并检查、评审彼此的工作，可连续数小时按计划自主推进。
- **技能自动触发**：技能会根据场景自动激活，用户无需额外操作。
- **多平台安装支持**：提供 Claude Code、Codex、Cursor、Gemini CLI、GitHub Copilot CLI、Qwen Code 等十余种编码 Agent 的安装方式。

**技术亮点**: 基于 Shell 实现；采用可组合技能（composable skills）架构，配合初始指令确保 Agent 主动加载并使用这些技能；支持各平台插件市场或扩展机制分发安装。

---
## 3. [pbakaus/impeccable](https://github.com/pbakaus/impeccable)
- **语言**: Rust
- **Stars**: 95,441
- **简介**: The design vocabulary for your coding agent. Steer with polish and bolder, review with critique and audit, catch AI slop before it ships.

### AI 总结
**简介**: Impeccable 是为编码智能体提供的一套设计词汇表，通过标准化命令帮助 AI 生成更有设计感的界面，并在交付前拦截“AI 味”十足的平庸设计。

**核心功能**:
- **设计引导（Steer）**: 通过 `bolder`、`quieter`、`distill`、`colorize`、`typeset`、`layout`、`animate`、`delight`、`overdrive` 等命令，用具体词汇替代模糊的“让它更出彩”，精准控制设计方向。
- **设计审查（Review）**: `critique` 按可用性启发式对设计打分并排序修复优先级；`audit` 检查可访问性、性能、主题与响应式行为，按 P0（阻断）到 P3（打磨）分级。
- **AI 味检测器**: 62 条确定性规则标记常见 AI 设计套路（如紫蓝渐变、卡片套卡片、彩色背景上的灰字），以及内边距拥挤、标题层级跳跃等质量问题，无需 LLM 或 API Key。
- **收尾与打磨（Finish）**: `polish`、`harden`、`clarify`、`adapt`、`optimize`、`onboard` 等命令处理错误、国际化、溢出、文案、多设备适配与首屏流程。
- **上下文文件**: `init` 生成 `PRODUCT.md` 记录产品目标，`document` 生成 `DESIGN.md` 固化现有视觉系统，保证后续改动不偏离品牌风格。
- **实时迭代**: `live` 支持在浏览器中选取元素并循环切换变体，`generate` 自动生成指定元素的多个变体。

**技术亮点**: 项目使用 Rust 实现；采用确定性规则引擎（非 LLM）进行设计检测；提供 24 个命令的完整工作流；兼容 Claude Code、Cursor、Codex CLI、GitHub Copilot、Gemini CLI 等 20 余种编码工具；通过 `npx impeccable install` 快速安装。

---
## 4. [JetBrains/thinkrail](https://github.com/JetBrains/thinkrail)
- **语言**: TypeScript
- **Stars**: 6,041
- **简介**: Vibe code with pi in a lightweight, real IDE that customises itself around the way you work — The Vibe You Need

### AI 总结
**简介**: ThinkRail 是 JetBrains 孵化的一款 TypeScript 编写的 agentic IDE，围绕 `pi` 编码智能体构建，能随使用不断学习项目、逐步定制自身能力。

**核心功能**:
- **隔离工作区**：将任意 git 仓库作为项目，以 `git worktree` 切出独立工作区（各自分支与目录），智能体可并行工作且不干扰主检出；完成的 workspace 会自动归入项目"搁架"，并支持发布、推送、开 PR、查看 CI 与评审状态、合并等一站式操作。
- **围绕智能体的真实 IDE**：可拆分的工作台，包含 Monaco 编辑器标签、带实时 git 变更标记的文件树与 Changed 视图、终端和文档，均作用于当前工作区；支持在文件与 diff 上留锚点评审评论并作为结构化上下文发送给聊天，或直接用本机 IDE 打开工作区。
- **流式对话**：每个工作区可并发多个 `pi` 会话，各自独立模型并实时显示 token 与成本；可中途干预、排队追问、委派子智能体，并协作维护共享计划，每个完成步骤可单独提交与评审。
- **Specs 作为事实来源**：代码旁维护互联的 `SPEC.md` 图谱，智能体通过专用 `spec_*` 工具读取、检索与维护，使意图跨会话留存；只读 Specs 工具在工作台中以树形呈现。
- **技能与工作流**：直接读取你为其他编码智能体保留的可移植 Agent Skills，并内置项目搭建、设计头脑风暴、发布 PR 等工作流。

**技术亮点**: 基于 TypeScript 实现；以 `@earendil-works/pi-coding-agent` 为核心智能体；采用 `git worktree` 实现工作区隔离；集成 Monaco 编辑器；通过 living specs 图谱与可复用技能为智能体提供持久项目知识，并计划加入完整扩展支持，让 ThinkRail 按实际工作方式自建工具。

---
## 5. [milind-soni/OpenMausBot](https://github.com/milind-soni/OpenMausBot)
- **语言**: TypeScript
- **Stars**: 7,526
- **简介**: Open-source Grok Bot alternative with a virtual machine that bots can use

### AI 总结
**简介**: OpenMausBot 是一个开源版 Grok Bot 替代方案，将 AI 智能体团队做成类似即时通讯应用的交互界面，每个"联系人"都是一个可独立运行的 AI 智能体。

**核心功能**:
- 侧边栏中的每个 Bot 都是真实智能体（底层运行 Claude 或 Codex），拥有独立人格、模型、云端计算机和已连接的应用程序
- 像聊天联系人一样与 Bot 对话、观察其工作过程，并对关键操作进行审批
- 采用自带智能体（BYOA）模式，本地优先运行在用户已有的模型之上

**技术亮点**: 基于 TypeScript（严格模式）、React 19 和 Electron 构建，支持 macOS（Apple 芯片与 Intel）、Windows 和 Ubuntu 多平台桌面端；项目由 boat.dev 提供支持，与 xAI、Meta、OpenAI、Manus 均无关联，且明确声明不涉及任何加密货币。

---
## 6. [nightly-labs/openbot](https://github.com/nightly-labs/openbot)
- **语言**: TypeScript
- **Stars**: 3,910
- **简介**: A local-first desktop workspace for persistent AI teammates. Run Codex, Claude, and Grok with dedicated workspaces, task queues, file sharing, browser control, and agent-to-agent collaboration.

### AI 总结
**简介**: OpenBot 是一个本地优先的桌面工作区，让 Codex、Claude、Grok 等多个 AI 智能体作为持久化“AI 队友”在独立空间中长期协作。

**核心功能**:
- 支持 Codex App Server、Claude Code、Grok CLI，并通过 ACP 接入 OpenCode、Gemini、Cursor CLI、Cline CLI 等多种智能体
- 每个智能体拥有独立工作区、会话、模型/推理配置及上下文监控（长对话自动压缩）
- FIFO 消息队列，支持暂停、恢复、取消及崩溃安全持久化
- 智能体间消息、回复、表情、图片与管理式文件传输
- 共享桌面频道聊天，支持任务归属、显式委派、历史共享及停止/恢复/重新分配/归档/恢复
- 持久化内嵌浏览器，智能体可打开、检查并控制页面
- 可选 Computer Use（macOS/Windows/Linux，通过 `cua-driver` 子进程）
- 自定义 OpenAI 兼容端点与自定义 ACP 智能体，自动检测本地模型服务（Ollama、LM Studio）

**技术亮点**: TypeScript 开发，基于 Electron 风格的桌面应用架构（AppImage/DMG/EXE 分发）；本地优先设计（数据本地存储、隐私安全诊断导出）；账户系统基于 Cloudflare Workers + D1；支持 ACP 协议扩展与多平台（macOS 13+、Windows 10+、Linux x64/arm64）。注意当前为开发预览版，智能体默认以 `danger-full-access` 和 `approvalPolicy: never` 运行，需谨慎使用。

---
## 7. [elayadesign/ai-design-skills](https://github.com/elayadesign/ai-design-skills)
- **语言**: Unknown
- **Stars**: 12,208
- **简介**: 

### AI 总结
**简介**: 一个面向 AI 编程工具（Claude Code、Cursor、Codex、Windsurf 等）的设计技能集合仓库，每个技能以自包含文件夹形式提供，可按需安装。

**核心功能**:
- 提供可插拔的设计技能，目前包含 `landing-page-design`：从零构建落地页，涵盖需求引导提问、页面结构、转化文案，以及完整的视觉系统（字体、间距、圆角、动效）
- 支持多种 AI 工具的安装方式：Claude Code 通过 `.claude/skills` 目录克隆，Cursor 通过 `.cursor/rules` 或设置界面导入，Codex/Windsurf/Cline 等复制 `SKILL.md` 到对应规则文件
- 支持无终端场景：可将 `SKILL.md` 上传至 Claude.ai 项目或作为附件使用
- 设计价值观（字体、颜色、间距、动效）集中在一个区块，Fork 后修改该区块即可自动同步到整个技能

**技术亮点**: 基于 Markdown 规则文件（`SKILL.md`）的轻量技能架构，与工具无关、跨平台复用；采用模块化自包含文件夹设计，便于按需安装和扩展；MIT 开源许可，可自由使用、修改和商用。

---
## 8. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 104,848
- **简介**: Persistent Context Across Sessions for Every Agent – Captures everything your agent does during sessions, compresses it with AI, and injects relevant context back into future sessions. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode + More

### AI 总结
**简介**: Claude-Mem 是一个为 AI 编程代理提供跨会话持久记忆的压缩系统，最初为 Claude Code 构建，可捕获代理在会话中的所有操作，用 AI 压缩后在未来会话中注入相关上下文。

**核心功能**:
- 跨会话持久上下文：记录代理在每次会话中的完整行为，避免重复解释和上下文丢失
- AI 压缩：将捕获的会话内容自动压缩为精简记忆，降低上下文占用
- 上下文回注：在后续会话中自动注入与当前任务相关的历史记忆
- 多代理兼容：支持 Claude Code、OpenClaw、Codex、Gemini、Hermes、Copilot、OpenCode 等多种代理工具

**技术亮点**: 基于 TypeScript 开发，要求 Node.js ≥ 20.0.0，采用 Apache 2.0 开源协议；项目提供 30 余种语言的国际化文档，并被收录于 Awesome Claude Code 及 Trendshift 榜单。

---
## 9. [CopilotKit/OpenBot](https://github.com/CopilotKit/OpenBot)
- **语言**: TypeScript
- **Stars**: 8,184
- **简介**: Open-source AI coworkers that each get a computer of their own: a browser, files and tools, with every action decided before it happens and recorded after. Bring any AG-UI agent.

### AI 总结
**简介**: OpenBot 是 CopilotKit 开源的自托管 AI 同事平台，每个 AI 同事拥有独立的浏览器、文件和工具，所有动作先决策后记录，可接入任意 AG-UI 智能体。

**核心功能**:
- 每个 AI 同事配备真实浏览器（独立登录）、独立文件和仅限授权的工具，动作执行前决策、执行后留痕
- 支持接入任意 AG-UI 协议智能体（LangGraph、Mastra、CrewAI 等框架或手写均可），以独立频道形式作为同事运行
- 内置通用助手、知识库、风险分析师等示例同事，另提供 10 个金融场景模板（费用审核、会议跟进、发布说明、工单分诊等），通过配置即可添加
- 所有对计算机、文件、MCP 服务器和组件的操作统一经过一个网关进行决策与记录
- 支持人工接管：可实时观看 AI 工作，在敏感操作时接管控制权再交还

**技术亮点**: 基于 TypeScript 开发，采用 Docker Compose 一键部署，数据存储于自有 PostgreSQL；模型可自由选择（不内置模型，凭据加密存储且不记日志）；基于 AG-UI 开放协议实现框架无关的智能体集成；以模板形式发布（非托管产品），所有 workspace 私有，需克隆后替换示例租户包自行运行；当前处于 Beta 阶段，MIT 许可。

---
## 10. [togg53192-cmd/jailbreaks](https://github.com/togg53192-cmd/jailbreaks)
- **语言**: Unknown
- **Stars**: 9,112
- **简介**: LIST OF ALL MY JAILBREAKS

### AI 总结
**简介**: 一个收录了 32 份系统提示词、人格设定与 Agent 操作规范的提示词集合，覆盖 26+ 个前沿闭源、开放权重及免费隐身模型。

**核心功能**:
- 提供完整可粘贴的系统提示词、人格定义、工作区策略、`AGENTS.md` 文件、配置块及 Ollama Modelfile
- 覆盖多类模型：OpenCode Zen 免费隐身模型、GLM/DeepSeek/Kimi/Qwen/Gemma/GPT-OSS 开放权重系列、Claude/Gemini/Grok/Mistral 闭源前沿模型
- 按厂商与模型分类整理（Anthropic、Zhipu、DeepSeek、Moonshot、xAI、NVIDIA、Google、Mistral、Alibaba 等），便于按目标模型检索
- 每个文件均为完整版本，不含摘要或片段截取

**技术亮点**: 聚焦指令层级、人格框架、提示冲突与策略覆盖等提示工程手法，同时可作为研究提示注入防御与指令操纵抵抗的参考资料；项目声明仅限研究与教育用途，禁止用于危害他人、规避法律或违反平台服务条款。

---
