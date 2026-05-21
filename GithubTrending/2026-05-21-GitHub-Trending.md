---
tags:
  - github-trending
  - daily
date: 2026-05-21
created: 2026-05-21T01:55:44.445Z
---

# 2026-05-21 GitHub Trending Top 10

## 1. [colbymchenry/codegraph](https://github.com/colbymchenry/codegraph)
- **语言**: TypeScript
- **Stars**: 9,795
- **简介**: Pre-indexed code knowledge graph for Claude Code, Codex, Cursor, and OpenCode — fewer tokens, fewer tool calls, 100% local

### AI 总结
**简介**: CodeGraph 是一个为 Claude Code、Cursor、Codex 和 OpenCode 等 AI 编程助手提供预索引代码知识图谱的工具，可显著降低 Token 消耗和工具调用次数，实现 100% 本地化运行。

**核心功能**:
- **预索引代码知识图谱**：为 AI 代理提供符号关系、调用图和代码结构，使其无需扫描文件即可快速查询
- **支持多种 AI 编程助手**：兼容 Claude Code、Cursor、Codex CLI 和 opencode
- **一键初始化**：通过 `npx @colbymchenry/codegraph` 交互式安装，自动配置代理
- **项目快速集成**：使用 `codegraph init -i` 命令初始化项目

**技术亮点**: 
- 基于 **TypeScript** 开发
- 采用 **MCP (Model Context Protocol)** 服务器架构
- 跨平台支持（Windows、macOS、Linux）
- 平均降低 **35%** 成本、**59%** Token 消耗、**49%** 响应时间、**70%** 工具调用次数
- 代码库越大，性能提升越明显（如 VS Code 10k 文件场景下成本降低 35%，工具调用减少 72%）

---
## 2. [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills)
- **语言**: Python
- **Stars**: 16,288
- **简介**: Academic Research Skills for Claude Code: research → write → review → revise → finalize

### AI 总结
**简介**: 一个面向学术研究的 Claude Code 技能套件，覆盖从研究到发表的完整流程，采用人机协作模式避免全自动 AI 研究的常见缺陷。

**核心功能**:
- 研究规划：通过苏格拉底式对话引导论文结构设计
- 引用管理：自动查找参考文献、格式化引用，并检测幻觉引用（L3 层级风险）
- 写作质量检查：识别机器生成文本的模式，支持风格校准（学习用户历史作品风格）
- 完整性验证：7 模式阻断检查清单，可选的审计模式（`ARS_CLAIM_AUDIT=1`）验证引用与声明的匹配度
- 全流程支持：research → write → review → revise → finalize

**技术亮点**:
- 基于 Claude Code 插件系统，30 秒安装（CLI / VS Code / JetBrains）
- 引用审计系统：三层定位锚点（locator anchors）+ 5 种 HIGH-WARN 阻断类别
- 校准机制：20 元组黄金标准集，FNR<0.15 + FPR<0.10 验收阈值
- 参考 PaperOrchestra 架构：Semantic Scholar API 验证、VLM 图表验证、反泄露协议

---
## 3. [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman)
- **语言**: Rust
- **Stars**: 23,724
- **简介**: Your Personal AI super intelligence. Private, Simple and extremely powerful.

### AI 总结
**简介**: OpenHuman 是一款开源的个人 AI 超级智能助手，强调隐私、简洁和强大，旨在深度融入用户的日常生活。

**核心功能**:
- **人性化桌面体验**: 拥有一个桌面吉祥物，能说话、对环境做出反应，甚至作为真实参与者加入 Google Meet，并在后台持续思考。
- **118+ 第三方集成**: 通过一键 OAuth 连接 Gmail、Notion、GitHub、Slack、Stripe 等应用，并自动每 20 分钟拉取最新数据到记忆树中。
- **记忆树**: 具备长期记忆能力，能跨周记住用户，无需重复上下文。

**技术亮点**: 使用 Rust 语言开发，采用 Composio 连接器层管理第三方集成，支持自动数据拉取和后台持续运行。

---
## 4. [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills)
- **语言**: Unknown
- **Stars**: 140,982
- **简介**: A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.

### AI 总结
**简介**: 这是一个基于 Andrej Karpathy 对 LLM 编码陷阱的观察，通过单个 `CLAUDE.md` 文件来改进 Claude Code 行为的指南。

**核心功能**:
- **Think Before Coding**: 强制显式推理，要求陈述假设、呈现多种解释、在适当时提出异议，并在困惑时停止寻求澄清。
- **Simplicity First**: 对抗过度工程化，坚持最小代码量解决问题，不添加未请求的功能、抽象或错误处理。
- **Surgical Changes**: 仅修改必须修改的代码，不“改进”无关代码、注释或格式，并只清理自己修改产生的遗留物。
- **Goal-Driven Execution**: 将命令式任务转化为可验证的目标，通过先写测试再实现的方式循环执行直到成功。

**技术亮点**: 提供作为 Claude Code 插件（推荐）或 `CLAUDE.md` 文件（逐项目）的安装方式，并附带 Cursor 项目规则支持，确保指南在不同 IDE 中一致应用。

---
## 5. [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch)
- **语言**: Python
- **Stars**: 9,633
- **简介**: Learn it. Build it. Ship it for others.

### AI 总结
**简介**: 一套从零构建AI工程能力的开源课程，覆盖数学基础到自主智能体，旨在弥补学生使用AI工具时“会用但不懂原理”的差距。

**核心功能**:
- **系统性学习路径**: 包含20个阶段、435节课，从线性代数、反向传播到多智能体系统，逐步进阶。
- **动手实践**: 每节课遵循“从数学推导到代码实现”的流程，先手写算法，再用生产级库（如PyTorch）复现。
- **多语言支持**: 使用Python、TypeScript、Rust、Julia四种语言实现算法，产出可复用的提示词、技能、智能体或MCP服务器。
- **开源可部署**: 所有内容免费、MIT协议，可在本地笔记本上运行。

**技术亮点**: 采用“先理解原理，再使用框架”的教学方法，确保学习者能解释损失曲线、注意力机制等底层原理；课程结构包含20个相互依赖的阶段，从数学到生产部署形成完整闭环。

---
## 6. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 38,565
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: CLI-Anything 是一个开源项目，旨在通过为任何软件生成命令行接口（CLI），使其能够被 AI 智能体（如 Pi、OpenClaw、Cursor、Claude Code 等）原生调用和操作，从而弥合 AI 与现有软件之间的鸿沟。

**核心功能**:
- **一键生成 CLI 接口**: 为任意软件创建标准的命令行接口，使其对 AI 智能体“就绪”。
- **CLI-Hub 社区市场**: 提供 `cli-hub install <name>` 命令，方便浏览、安装和管理社区贡献的 CLI 工具，用户也可通过 PR 贡献自己的 CLI。
- **丰富的演示与测试**: 展示了 AI 智能体通过生成的 CLI 完成 CAD 建模、3D 场景、图表、游戏等任务的示例，并拥有 2000+ 个通过测试。
- **支持多种智能体**: 兼容 Pi、OpenClaw、nanobot、Cursor、Claude Code 等多种 AI 智能体平台。

**技术亮点**: 基于 Python 开发，使用 Click 库构建 CLI，支持 JSON 与人类可读的双重输出格式，并通过严格的单元测试和端到端测试（覆盖率 100%）确保稳定性。

---
## 7. [can1357/oh-my-pi](https://github.com/can1357/oh-my-pi)
- **语言**: TypeScript
- **Stars**: 5,444
- **简介**: ⌥ AI Coding agent for the terminal — hash-anchored edits, optimized tool harness, LSP, Python, browser, subagents, and more

### AI 总结
**简介**: oh-my-pi 是一个为终端设计的 AI 编码代理，它集成了 IDE 功能，提供哈希锚定编辑、优化的工具集、LSP、Python 执行、浏览器集成、子代理等能力，旨在提供一个开箱即用且功能强大的代理界面。

**核心功能**:
- **代码执行与工具调用**: 支持持久的 Python 和 Bun 工作进程，这些内核可以回调代理自身的工具（如读取、搜索、任务），实现跨语言协作。
- **LSP 集成**: 语言服务器协议 (LSP) 直接嵌入到每次写入操作中，支持重命名、引用查找等精确的代码编辑，并能自动更新相关文件和导入。
- **丰富的内置工具**: 提供 32 个内置工具，包括高效的读取（摘要文件）、搜索（极速）、LSP 操作（13 种）和 DAP 操作（27 种）。
- **多模型支持**: 支持 40 多种 AI 模型，并通过优化的编辑格式和提示词，显著提升模型的首次尝试成功率和输出效率。

**技术亮点**: 核心代码约 27,000 行 Rust，使用 TypeScript 构建，支持 macOS、Linux 和 Windows 平台。项目基于 Pi 开发，并进行了大量增强。

---
## 8. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 200,106
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套为编码代理设计的完整软件开发方法论，基于可组合的技能和初始指令，确保代理在编写代码前先进行设计规划和任务分解。

**核心功能**:
- **设计先行**：在写代码前通过对话提炼需求，生成可读的简短设计文档供用户审核。
- **实施计划**：根据批准的设计，制定清晰的任务计划，遵循 TDD、YAGNI 和 DRY 原则。
- **子代理驱动开发**：用户确认后，代理自动分解任务并执行，支持长时间自主工作。
- **多平台支持**：兼容 Claude Code、Codex CLI、Cursor 等主流编码代理工具。

**技术亮点**: 采用 Shell 脚本实现，通过可组合的技能模块自动触发流程，无需用户额外操作；支持多种代理平台的插件或扩展安装。

---
## 9. [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- **语言**: Python
- **Stars**: 20,822
- **简介**: Official, Anthropic-managed directory of high quality Claude Code Plugins.

### AI 总结
**简介**: Anthropic 官方维护的高质量 Claude Code 插件目录市场，提供内部和第三方插件的发现、安装与管理。

**核心功能**:
- 提供官方和社区第三方插件的集中目录
- 支持通过 `/plugin install` 命令或图形界面安装插件
- 分类管理内部插件（`/plugins`）和外部插件（`/external_plugins`）

**技术亮点**: 采用标准化插件结构（`.claude-plugin/` 元数据、`.mcp.json` 配置、命令/代理/技能模块），支持 MCP 服务器集成，并建立第三方插件质量与安全审核机制。

---
## 10. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 102,883
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个提供多领域、个性鲜明、交付导向的 AI 专家代理集合，让您能像组建一支全能团队一样，高效完成各种开发与运营任务。

**核心功能**:
- **专业化 AI 代理团队**: 包含前端、后端、移动端、AI 工程师、DevOps、安全工程师等多个领域的专家代理，每个代理都有明确的职责、个性和工作流程。
- **一键安装与集成**: 提供脚本支持快速安装到 Claude Code、GitHub Copilot、Cursor 等多种主流 AI 开发工具，也可手动复制使用。
- **即用型交付物**: 每个代理文件都包含身份设定、核心任务、技术交付物（含代码示例）和成功指标，可直接使用或参考。

**技术亮点**:
- **Shell 脚本驱动**: 使用 Shell 脚本实现代理的安装、转换和集成，操作简单。
- **多工具兼容**: 支持 Claude Code、GitHub Copilot、Cursor、Aider、Windsurf 等 10 余种 AI 开发工具。
- **生产就绪**: 代理经过实战测试，专注于可衡量的交付成果，而非简单的提示词模板。

---
