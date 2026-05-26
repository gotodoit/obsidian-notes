---
tags:
  - github-trending
  - daily
date: 2026-05-26
created: 2026-05-26T01:55:43.650Z
---

# 2026-05-26 GitHub Trending Top 10

## 1. [Lum1104/Understand-Anything](https://github.com/Lum1104/Understand-Anything)
- **语言**: TypeScript
- **Stars**: 31,366
- **简介**: Graphs that teach > graphs that impress. Turn any code into an interactive knowledge graph you can explore, search, and ask questions about. Works with Claude Code, Codex, Cursor, Copilot, Gemini CLI, and more.

### AI 总结
**简介**: 一个将任何代码库、知识库或文档转化为交互式知识图谱的工具，支持探索、搜索和提问，可与 Claude Code、Codex、Cursor 等主流 AI 编程工具配合使用。

**核心功能**:
- **交互式知识图谱**: 将代码库中的文件、函数、类等元素可视化为可点击、搜索的节点，显示自然语言摘要和关系。
- **业务逻辑视图**: 将代码映射为水平布局的业务流程图，展示领域、流程和步骤。
- **知识库分析**: 解析 Karpathy 风格的 LLM wiki，利用 LLM 代理发现隐式关系、提取实体，生成带社区聚类的知识图谱。
- **架构导览**: 自动生成按依赖关系排序的代码架构漫游，帮助按正确顺序学习代码库。
- **模糊与语义搜索**: 支持按名称或语义搜索，如“哪些部分处理认证？”。
- **变更影响分析**: 在提交前直观展示代码修改会影响到系统的哪些部分。

**技术亮点**: 使用 TypeScript 开发，基于多智能体管道进行代码分析，构建包含文件、函数、类和依赖关系的知识图谱；提供交互式 Web 仪表盘，支持力导向图可视化。

---
## 2. [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)
- **语言**: Python
- **Stars**: 15,544
- **简介**: Open source repository of plugins primarily intended for knowledge workers to use in Claude Cowork

### AI 总结
**简介**: anthropics/knowledge-work-plugins 是一个开源插件仓库，旨在通过 Claude Cowork 和 Claude Code 将 AI 转化为特定角色、团队和公司的专业助手，提升知识工作者的效率和一致性。

**核心功能**:
- **11个预建插件**: 覆盖生产力、销售、客服、产品管理、营销、法律、财务、数据、企业搜索、生物研究及插件管理，每个插件捆绑特定角色的技能、工具连接器和斜杠命令。
- **自定义工作流**: 通过技能（自动触发的领域知识）和命令（手动触发的显式操作）定制插件，适配公司的工具、术语和流程。
- **工具集成**: 通过 MCP 服务器连接 Slack、Notion、Jira、HubSpot、Snowflake 等外部工具，实现数据拉取和操作。
- **即装即用**: 支持从 Cowork 直接安装或通过 Claude Code 命令行添加，插件安装后自动激活。

**技术亮点**: 
- **文件化结构**: 每个插件遵循统一目录结构（`.claude-plugin/plugin.json` 清单、`.mcp.json` 工具连接、`commands/` 和 `skills/` 目录），便于定制和扩展。
- **MCP 协议支持**: 使用 Model Context Protocol 标准化工具集成，确保与外部系统的互操作性。
- **Python 实现**: 基于 Python 开发，兼容 Claude 生态，强调模块化和可复用性。

---
## 3. [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch)
- **语言**: Python
- **Stars**: 18,719
- **简介**: Learn it. Build it. Ship it for others.

### AI 总结
**简介**: 一个从零开始学习AI工程的开源课程，涵盖数学基础到生产级AI系统，共435节课、20个阶段，支持Python/TypeScript/Rust/Julia四种语言。

**核心功能**:
- **完整课程体系**: 从线性代数、机器学习基础到Transformer、LLM、多智能体系统，共20个递进阶段
- **动手实践驱动**: 每节课遵循“问题→概念→手写实现（无框架）→生产库应用”的六步学习法
- **多语言支持**: 同一算法用Python、TypeScript、Rust、Julia四种语言实现
- **可复用产出**: 每节课生成一个可复用的AI制品（提示词、技能、智能体、MCP服务器）
- **本地运行**: 所有代码和实验可在个人笔记本上完成

**技术亮点**: 
- 采用“Build It/Use It”双轨制教学：先手写原始数学实现（反向传播、分词器、注意力机制），再使用PyTorch等生产框架
- 项目结构标准化：每节课包含code/（代码）、docs/（文档）、outputs/（产出物）三个目录
- 开源MIT协议，免费使用，配套网站aiengineeringfromscratch.com

---
## 4. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 192,433
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个为 AI 编程助手（如 Claude Code、Cursor 等）打造的性能优化系统，提供技能、本能、记忆、安全和研究优先的开发能力。

**核心功能**:
- 提供完整的技能、本能和记忆优化系统，支持持续学习和安全扫描
- 跨平台兼容 Claude Code、Codex、Cursor、OpenCode、Gemini 等多种 AI 编程助手
- 包含 Hermes 操作器故事、MCP 配置和传统命令 shim
- 提供 GitHub App 集成，支持私有仓库的 PR 审计和免费套餐
- 支持 12+ 种语言生态和多种编程语言（TypeScript、Python、Go、Java 等）

**技术亮点**: 基于 JavaScript 开发，采用 MIT 开源许可，支持跨多种 AI 编程助手的统一架构，包含 hooks、rules 和 MCP 配置，经过 10 个月以上的实际产品开发测试。

---
## 5. [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills)
- **语言**: Python
- **Stars**: 9,284
- **简介**: 754 structured cybersecurity skills for AI agents · Mapped to 5 frameworks: MITRE ATT&CK, NIST CSF 2.0, MITRE ATLAS, D3FEND & NIST AI RMF · agentskills.io standard · Works with Claude Code, GitHub Copilot, Codex CLI, Cursor, Gemini CLI & 20+ platforms · 26 security domains · Apache 2.0

### AI 总结
**简介**: 一个包含 754 个结构化网络安全技能的开源库，为 AI 代理提供专家级安全分析能力，并映射至五大行业框架。

**核心功能**:
- **结构化技能库**: 提供 754 个涵盖 26 个安全领域（如恶意软件分析、云安全等）的生产级技能，每个技能均遵循 agentskills.io 开放标准。
- **五框架映射**: 每个技能同时映射到 MITRE ATT&CK、NIST CSF 2.0、MITRE ATLAS、D3FEND 和 NIST AI RMF 五大框架，实现跨框架统一覆盖。
- **AI平台兼容**: 支持 Claude Code、GitHub Copilot、OpenAI Codex CLI、Cursor、Gemini CLI 等 26 个以上 AI 平台，可通过 `npx skills add` 或 `git clone` 快速集成。

**技术亮点**: 基于 Python 实现，采用 agentskills.io 开放标准，提供统一的技能描述结构；支持通过 npx 命令或 Git 克隆直接集成到主流 AI 开发工具中。

---
## 6. [colbymchenry/codegraph](https://github.com/colbymchenry/codegraph)
- **语言**: TypeScript
- **Stars**: 25,214
- **简介**: Pre-indexed code knowledge graph for Claude Code, Codex, Cursor, OpenCode, and Hermes Agent — fewer tokens, fewer tool calls, 100% local

### AI 总结
**简介**: CodeGraph 是一个为 AI 编程助手（如 Claude Code、Cursor 等）提供预索引代码知识图谱的工具，可显著降低 token 消耗、减少工具调用并完全本地运行。

**核心功能**:
- 为代码库构建预索引的知识图谱，包含符号关系、调用图和代码结构
- 与主流 AI 编程代理（Claude Code、Cursor、Codex CLI、opencode、Hermes Agent）集成
- 支持一键安装和自动配置，无需 Node.js 环境
- 提供交互式初始化（`codegraph init -i`）和卸载（`codegraph uninstall`）命令
- 跨平台支持（Windows、macOS、Linux）

**技术亮点**: 使用 TypeScript 开发，捆绑自运行环境，无需编译或原生构建；通过 MCP 服务器协议与 AI 代理集成；在 7 种语言、7 个真实开源代码库测试中平均节省 35% 成本、减少 71% 工具调用。

---
## 7. [manaflow-ai/cmux](https://github.com/manaflow-ai/cmux)
- **语言**: Swift
- **Stars**: 19,516
- **简介**: Ghostty-based macOS terminal with vertical tabs and notifications for AI coding agents

### AI 总结
**简介**: cmux 是一款基于 Ghostty 的 macOS 终端，专为 AI 编码代理设计，提供垂直标签和通知功能。

**核心功能**:
- **通知环**: 当编码代理需要关注时，窗格显示蓝色环，标签页亮起
- **通知面板**: 集中查看所有待处理通知，一键跳转到最新未读
- **内置浏览器**: 可分割终端窗口，支持可脚本化的 API
- **垂直+水平标签**: 侧边栏显示 git 分支、PR 状态、工作目录、监听端口和最新通知
- **SSH 支持**: 为远程机器创建工作区，浏览器窗格通过远程网络路由，支持拖拽上传
- **Claude Code Teams**: 一键运行 Claude Code 的队友模式，无需 tmux

**技术亮点**: 基于 Swift 和 AppKit 原生构建，非 Electron；支持 Ghostty 配置；GPU 加速渲染；支持自定义命令和脚本化 API。

---
## 8. [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills)
- **语言**: Unknown
- **Stars**: 155,080
- **简介**: A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.

### AI 总结
**简介**: 该项目提供一份基于 Andrej Karpathy 对 LLM 编码陷阱观察的 `CLAUDE.md` 文件，旨在改善 Claude Code 的行为，解决其常见的错误假设、过度复杂化代码和误改无关代码等问题。

**核心功能**:
- **Think Before Coding**: 强制显式推理，要求明确陈述假设、呈现多种解释，并在必要时提出质疑。
- **Simplicity First**: 倡导最简代码，禁止过度工程化、不必要的抽象和未请求的功能。
- **Surgical Changes**: 限制修改范围，只改动必要代码，不“优化”或清理无关代码。
- **Goal-Driven Execution**: 将任务转化为可验证的成功标准（如测试先行），让 LLM 自主循环直至达标。

**技术亮点**: 通过单个 `CLAUDE.md` 文件以插件或项目配置形式注入 Claude Code，同时提供对 Cursor 编辑器的支持。

---
## 9. [Fincept-Corporation/FinceptTerminal](https://github.com/Fincept-Corporation/FinceptTerminal)
- **语言**: Python
- **Stars**: 23,903
- **简介**: FinceptTerminal is a modern finance application offering advanced market analytics, investment research, and economic data tools, designed for interactive exploration and data-driven decision-making in a user-friendly environment.

### AI 总结
**简介**: FinceptTerminal 是一个面向现代金融分析的终端工具，提供高级市场分析、投资研究和经济数据工具，旨在通过交互式探索辅助数据驱动决策。

**核心功能**:
- **权益研究**: 提供深入的股票研究与分析功能。
- **投资组合管理**: 支持投资组合的构建、跟踪与优化。
- **新闻聚合**: 集成实时金融新闻，辅助信息获取。
- **节点编辑器**: 提供可视化节点编辑工具，用于自定义数据流与自动化分析流程。

**技术亮点**: 基于 Python 3.11+ 开发，采用 C++20 与 Qt6 构建高性能用户界面，支持 AI 自动化与无限数据连接，遵循 AGPL-3.0 开源协议。

---
## 10. [paperless-ngx/paperless-ngx](https://github.com/paperless-ngx/paperless-ngx)
- **语言**: Python
- **Stars**: 41,358
- **简介**: A community-supported supercharged document management system: scan, index and archive all your documents

### AI 总结
**简介**: Paperless-ngx 是一个社区支持的文档管理系统，可将实体文档转换为可搜索的在线存档。
**核心功能**:
- 扫描、索引和归档文档
- 支持文档搜索和在线存档
- 可通过 Docker 快速部署
- 提供社区支持和多语言翻译
**技术亮点**: 基于 Python 构建，使用 Docker 容器化部署，支持 GitHub Actions CI/CD，集成 Crowdin 翻译平台。

---
