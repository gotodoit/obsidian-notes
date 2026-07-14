---
tags:
  - github-trending
  - daily
date: 2026-07-14
created: 2026-07-14T01:55:42.995Z
---

# 2026-07-14 GitHub Trending Top 10

## 1. [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut)
- **语言**: TypeScript
- **Stars**: 66,573
- **简介**: The open-source CapCut alternative

### AI 总结
**简介**: OpenCut 是一款免费开源、跨平台的视频编辑器，旨在成为 CapCut 的替代品，支持 Web、桌面和移动端。

**核心功能**:
- 跨平台支持：基于 Rust 核心实现一套代码库覆盖桌面、移动端和浏览器。
- 编辑器 API：提供可扩展的编辑器接口。
- 插件系统：优先支持第三方插件，采用插件优先架构。
- 脚本编辑器：内置脚本标签页，支持自动化与批量渲染。
- 无头模式：支持自动化处理和批量渲染任务。
- MCP 服务器：为 AI 代理提供集成接口。

**技术亮点**: 使用 TypeScript 开发，核心基于 Rust 实现跨平台统一架构，采用 moon 工具链管理多应用（Web、API、桌面端）开发。

---
## 2. [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading)
- **语言**: Python
- **Stars**: 21,806
- **简介**: "Vibe-Trading: Your Personal Trading Agent"

### AI 总结
**简介**: Vibe-Trading 是一个个人交易代理工具，通过一条命令即可赋予代理全面的交易能力。

**核心功能**:
- **个人交易代理**: 提供一键式命令，让用户快速启动并运行交易代理。
- **策略开发与管理**: 包含策略开发管理器，支持将学术论文和券商研究转化为注册因子/策略，并具备自动化 IC/夏普比率衰减监控。
- **影子账户**: 支持影子账户功能，用于模拟交易和策略测试。
- **API 与 MCP 支持**: 提供 API 和 MCP（模型上下文协议）接口，便于集成和扩展。
- **回测与分析**: 支持回测功能，并在回测指标中展示已实现的投资组合换手率。

**技术亮点**: 采用 Python 3.11+ 开发，后端基于 FastAPI，前端使用 React 19，支持多语言（英文、中文、日文、韩文、阿拉伯文），并通过 Docker 多阶段构建、AST 加固回测沙箱、短寿命 SSE 认证票据等安全措施保障系统安全。

---
## 3. [moeru-ai/airi](https://github.com/moeru-ai/airi)
- **语言**: TypeScript
- **Stars**: 41,909
- **简介**: 💖🧸 Self hosted, you-owned Grok Companion, a container of souls of waifu, cyber livings to bring them into our worlds, wishing to achieve Neuro-sama's altitude. Capable of realtime voice chat, Minecraft, Factorio playing. Web / macOS / Windows supported.

### AI 总结
**简介**: AIRI 是一个自托管的、类似 Grok 的 AI 伴侣项目，旨在复现 Neuro-sama 的能力，让用户拥有自己的 AI 虚拟角色（waifu），支持实时语音聊天、游戏互动（Minecraft、Factorio），并提供 Web、macOS 和 Windows 客户端。

**核心功能**:
- 实时语音对话
- 支持 Minecraft 和 Factorio 游戏内互动
- 跨平台支持：Web、macOS、Windows

**技术亮点**: 使用 TypeScript 开发，支持自托管部署，开源社区活跃（Discord、Telegram、QQ 群）。

---
## 4. [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)
- **语言**: Python
- **Stars**: 119,677
- **简介**: 100+ AI Agent & RAG apps you can actually run — clone, customize, ship.

### AI 总结
**简介**: 一个包含 100+ 个可直接运行的 AI Agent 和 RAG 应用模板的“菜谱式”项目，旨在帮助开发者快速克隆、定制并发布生产级 LLM 应用。

**核心功能**:
- 提供覆盖 AI Agents、RAG、多智能体团队、语音代理等领域的即用模板
- 所有模板均为原创并经过端到端测试，确保 3 条命令即可运行
- 支持切换 Claude、Gemini、GPT、Llama 等多种大模型提供商
- 每个特色模板配有免费的分步教程（来自 Unwind AI）

**技术亮点**:
- 技术栈涵盖 Agent Skills、MCP Agents、Fine-tuning 等现代 AI 架构
- Apache-2.0 开源协议，无付费墙、无注册、无遥测
- 采用 Python 语言，基于 Streamlit 等框架构建

---
## 5. [Nutlope/hallmark](https://github.com/Nutlope/hallmark)
- **语言**: CSS
- **Stars**: 5,196
- **简介**: Anti-AI-slop design skill for Claude Code, Cursor, and Codex.

### AI 总结
**简介**: Hallmark 是一个专为 Claude Code、Cursor 和 Codex 设计的设计技能，旨在生成看起来不像是 AI 生成的网页 UI。

**核心功能**:
- **生成新 UI**: 根据需求自动选择宏观结构，应用规则集，并通过 57 项“反AI味”测试后返回结果。
- **审计现有代码**: 使用 `hallmark audit <target>` 命令对现有代码进行反模式评分，生成问题清单。
- **重新设计**: 使用 `hallmark redesign <target>` 命令保留内容、信息架构和品牌，但重建不同的结构。
- **学习设计风格**: 使用 `hallmark study <screenshot | URL>` 从目标设计中提取“DNA”（宏观结构、字体搭配、色彩锚点），并可输出可移植的 `design.md` 文件。

**技术亮点**: 采用 CSS 实现，内置 20 种不同主题，通过 57 项“反AI味”测试门控和预输出自我批评机制，确保生成结果不落入 AI 常见的模板化分布。支持按 `T` 键循环切换主题。

---
## 6. [Raphire/Win11Debloat](https://github.com/Raphire/Win11Debloat)
- **语言**: PowerShell
- **Stars**: 50,907
- **简介**: A simple, lightweight PowerShell script that allows you to remove pre-installed apps, disable telemetry, as well as perform various other changes to declutter and customize your Windows experience. Win11Debloat works for both Windows 10 and Windows 11.

### AI 总结
**简介**: Win11Debloat 是一个轻量级的 PowerShell 脚本，用于移除预装应用、禁用遥测并自定义 Windows 体验，同时支持 Windows 10 和 11。

**核心功能**:
- **应用移除**: 一键删除多种预装应用，并支持通过 Microsoft Store 恢复。
- **隐私与内容控制**: 禁用遥测、诊断数据、活动历史、应用启动跟踪和定向广告；关闭 Windows、锁屏及 Microsoft 中的提示和建议。
- **界面定制**: 移除侵入性界面元素，优化用户体验。
- **命令行支持**: 提供强大的命令行接口，支持参数自定义脚本行为。
- **设置导出/导入**: 可导出和导入偏好设置，快速在多台设备上应用相同配置。
- **高级功能**: 支持 Windows Audit 模式，并可对其他 Windows 用户账户进行更改。

**技术亮点**: 纯 PowerShell 实现，无需安装；支持通过 `irm` 命令在线下载并直接运行；提供图形菜单界面和命令行参数双重交互方式。

---
## 7. [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify)
- **语言**: Python
- **Stars**: 84,801
- **简介**: AI coding assistant skill (Claude Code, Codex, OpenCode, Cursor, Gemini CLI, and more). Turn any folder of code, SQL schemas, R scripts, shell scripts, docs, papers, images, or videos into a queryable knowledge graph. App code + database schema + infrastructure in one graph.

### AI 总结
**简介**: graphify 是一个 AI 编程助手技能，能将任意文件夹（代码、SQL 模式、PDF、图片等）转化为可查询的知识图谱，支持 Claude Code 等多种 AI 工具。

**核心功能**:
- 通过 `/graphify` 命令一键将当前或指定文件夹构建为知识图谱
- 支持多种文件类型：代码（AST 解析）、文档、PDF、图片（Claude 视觉提取概念关系）
- 生成交互式 HTML 图谱、Obsidian 仓库、维基风格文章、详细报告等多种输出
- 支持增量更新（`--update`）、文件监控自动同步（`--watch`）、Git 提交钩子自动构建
- 可查询图谱、查找节点路径、解释概念，并支持多种导出格式（SVG、GraphML、Neo4j）

**技术亮点**: 使用 tree-sitter 进行代码 AST 解析与调用图构建，结合 Claude 视觉能力处理多模态输入，采用 SHA256 缓存实现增量处理，相比直接读取原始文件可减少 71.5 倍 Token 消耗。

---
## 8. [hasaneyldrm/exercises-dataset](https://github.com/hasaneyldrm/exercises-dataset)
- **语言**: HTML
- **Stars**: 12,650
- **简介**: 1,324-exercise fitness dataset — animation GIFs, 180×180 thumbnails, muscle-group & equipment data, and step-by-step instructions in 6 languages. The exercise data layer behind the LogPress app.

### AI 总结
**简介**: 一个包含 1,324 个健身动作的综合数据集，配有动画 GIF、缩略图、肌肉群/器械数据以及 9 种语言的分步指导，为 LogPress 应用提供数据层支持。

**核心功能**:
- **1,324 个动作数据**：每个动作都包含唯一 ID、名称、类别、目标肌肉、辅助肌肉、所需器械和多语言指导。
- **多媒体资源**：为每个动作提供 180×180 缩略图和动画 GIF。
- **多语言支持**：指导说明支持英语、西班牙语、意大利语、土耳其语、俄语、中文、印地语、波兰语和韩语共 9 种语言。
- **交互式浏览器**：提供 `index.html`，支持实时搜索、按类别/器械/目标肌肉筛选，以及无限滚动浏览。
- **开发者集成指南**：提供 `setup.html`，包含数据库建表 SQL、API 集成代码示例（JavaScript, Python, C#, Java, PHP, Go, cURL）以及 LLM 提示模板。

**技术亮点**: 纯客户端 HTML 工具，无需服务器即可运行；数据以 JSON 格式存储；媒体资源来自 Gym visual 并遵循特定许可。

---
## 9. [github/spec-kit](https://github.com/github/spec-kit)
- **语言**: Python
- **Stars**: 120,636
- **简介**: 💫 Toolkit to help you get started with Spec-Driven Development

### AI 总结
**简介**: Spec Kit 是一个开源工具包，旨在通过规范驱动开发（Spec-Driven Development）帮助开发者更快地构建高质量软件，专注于产品场景和可预测结果。

**核心功能**:
- 提供 Specify CLI 工具，用于初始化项目和生成可执行规范
- 支持通过 `/speckit.constitution` 命令创建项目治理原则和开发指南
- 支持通过 `/speckit.specify` 命令描述构建目标，聚焦于“做什么”和“为什么”
- 集成主流 AI 编码代理（如 GitHub Copilot），支持斜杠命令交互
- 提供扩展和预设机制，支持角色化捆绑包设置

**技术亮点**: 基于 Python 开发，使用 uv 工具管理安装和升级，实现规范直接生成工作实现而非仅作为指导。

---
## 10. [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills)
- **语言**: JavaScript
- **Stars**: 38,614
- **简介**: Marketing skills for Claude Code and AI agents. CRO, copywriting, SEO, analytics, and growth engineering.

### AI 总结
**简介**: 为 AI 代理（如 Claude Code）提供营销技能的 Markdown 文件集合，帮助技术营销人员和创始人执行转化优化、文案撰写、SEO、分析和增长工程等任务。

**核心功能**:
- 提供 30+ 个营销技能，涵盖 SEO、CRO、文案、广告、增长、销售和策略等领域
- 技能之间可相互引用和依赖，以 `product-marketing` 技能为基础，先理解产品、受众和定位
- 每个技能包含详细的场景描述、工作流程和最佳实践，AI 代理可自动识别并应用

**技术亮点**: 基于 Agent Skills 规范构建，兼容 Claude Code、OpenAI Codex、Cursor、Windsurf 等主流 AI 编码代理；使用 Markdown 格式，易于集成和扩展；支持社区贡献和 PR。

---
