---
tags:
  - github-trending
  - daily
date: 2026-06-02
created: 2026-06-02T01:55:43.192Z
---

# 2026-06-02 GitHub Trending Top 10

## 1. [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **语言**: Python
- **Stars**: 138,587
- **简介**: Python tool for converting files and office documents to Markdown.

### AI 总结
**简介**: MarkItDown 是一个轻量级 Python 工具，用于将多种文件格式转换为 Markdown，以便与 LLM 和文本分析管道配合使用。

**核心功能**:
- 支持转换 PDF、PowerPoint、Word、Excel、图片、音频、HTML、CSV、JSON、XML、ZIP、YouTube URL、EPub 等格式
- 提供命令行工具，支持文件输入、输出重定向和管道操作
- 支持可选依赖安装，可按需激活特定文件格式转换
- 支持第三方插件扩展，例如 OCR 插件可增强 PDF、DOCX 等格式的文本提取

**技术亮点**:
- 基于 Python 3.10+，通过 pip 或源码安装，支持虚拟环境管理
- 输出注重保留文档结构（标题、列表、表格、链接等），对 LLM 友好且 token 高效
- 提供插件机制，可通过 `#markitdown-plugin` 标签发现社区插件

---
## 2. [nesquena/hermes-webui](https://github.com/nesquena/hermes-webui)
- **语言**: Python
- **Stars**: 11,378
- **简介**: Hermes WebUI: The best way to use Hermes Agent from the web or from your phone!

### AI 总结
**简介**: Hermes WebUI 是一个轻量级、深色主题的 Web 界面，让你在浏览器或手机上使用 Hermes Agent，实现与 CLI 几乎 1:1 的功能体验。

**核心功能**:
- 三面板布局：左侧会话导航、中央聊天、右侧工作区文件浏览
- 支持会话管理、项目标签、工具调用卡片
- 内置模型、配置文件和工作区控制（Composer Footer）
- 圆形上下文环显示令牌用量
- Hermes 控制中心集中管理所有设置和会话工具
- 支持深色/浅色主题切换
- 通过 SSH 隧道安全访问，支持远程和手机使用
- 单命令启动，无需额外构建步骤

**技术亮点**:
- 纯 Python + 原生 JavaScript 实现，无框架、无构建工具
- 与 Hermes Agent 原生集成，利用现有模型和配置
- 支持 Docker 单容器/多容器部署
- 架构清晰：后端/前端分离，状态目录管理

---
## 3. [supermemoryai/supermemory](https://github.com/supermemoryai/supermemory)
- **语言**: TypeScript
- **Stars**: 24,017
- **简介**: Memory engine and app that is extremely fast, scalable. The Memory API for the AI era.

### AI 总结
**简介**: Supermemory 是一个为 AI 提供持久记忆和上下文引擎的开源项目，能自动从对话中学习、提取事实并构建用户画像，解决 AI 跨对话遗忘问题。

**核心功能**:
- **记忆管理**: 自动从对话中提取事实，处理时间变化、矛盾信息并自动遗忘过期内容
- **用户画像**: 自动维护用户上下文（稳定事实+近期活动），调用仅需约50ms
- **混合搜索**: 结合 RAG 与记忆系统，一次查询即可同时获取知识库文档和个性化上下文
- **连接器**: 支持 Google Drive、Gmail、Notion、OneDrive、GitHub 等数据源自动同步
- **多模态提取**: 支持 PDF、图片（OCR）、视频（转录）、代码（AST感知分块）处理

**技术亮点**: 采用 TypeScript 构建，在 LongMemEval、LoCoMo、ConvoMem 三大 AI 记忆基准测试中排名第一；提供统一的记忆结构和本体论，支持 npm/pypi 包及 MCP 服务器集成。

---
## 4. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)
- **语言**: Python
- **Stars**: 76,908
- **简介**: 利用AI大模型，一键生成高清短视频 Generate short videos with one click using AI LLM.

### AI 总结
**简介**: MoneyPrinterTurbo 是一款利用 AI 大模型，只需提供主题或关键词，即可一键生成高清短视频的工具。

**核心功能**:
- **AI 自动生成文案**：支持根据主题或关键词自动生成视频文案，也支持用户自定义。
- **多种视频尺寸**：支持竖屏 9:16（1080x1920）和横屏 16:9（1920x1080）的高清视频。
- **批量生成**：支持一次生成多个视频，方便挑选最满意的结果。
- **丰富的自定义选项**：可调整视频片段时长、字幕（字体、位置、颜色、大小、描边）、背景音乐（随机或指定，可调节音量）。
- **多语言与语音**：支持中文和英文文案，以及多种语音合成，并可实时试听。
- **高清无版权素材**：视频素材来源高清且无版权，也支持使用本地素材。

**技术亮点**:
- 采用完整的 **MVC 架构**，代码结构清晰，易于维护。
- 支持 **API** 和 **Web 界面** 两种使用方式。
- 集成了 **OpenAI**、**Azure**、**Google Gemini**、**DeepSeek**、**通义千问** 等多种主流 AI 模型。

---
## 5. [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling)
- **语言**: Python
- **Stars**: 58,105
- **简介**: 🕷️ An adaptive Web Scraping framework that handles everything from a single request to a full-scale crawl!

### AI 总结
**简介**: Scrapling 是一个自适应 Web 抓取框架，能处理从单次请求到大规模爬取的全场景任务。

**核心功能**:
- 使用自适应解析器，在网页更新时自动重新定位目标元素
- 内置多种抓取器，可绕过 Cloudflare Turnstile 等反爬系统
- 支持并发、多会话爬取，具备暂停/恢复和自动代理轮换功能
- 提供实时统计和流式输出的快速爬取体验
- 拥有命令行界面 (CLI) 和 MCP 服务器支持

**技术亮点**: 基于 Python，支持同步和异步抓取器 (Fetcher/AsyncFetcher/StealthyFetcher/DynamicFetcher)，集成了反检测、代理轮换和自适应解析技术。

---
## 6. [pbakaus/impeccable](https://github.com/pbakaus/impeccable)
- **语言**: JavaScript
- **Stars**: 32,757
- **简介**: The design language that makes your AI harness better at design.

### AI 总结
**简介**: Impeccable 是一个为 AI 前端设计助手提供专业设计语言和命令集的工具，包含 23 个设计命令、7 个领域参考文件和 27 条反模式规则，帮助 AI 生成更高质量、更独特的前端设计。

**核心功能**:
- **23 个设计命令**: 包括 craft（全流程设计）、audit（技术审查）、critique（UX 评审）、polish（最终打磨）等，覆盖从构思到发布的完整设计流程
- **7 个领域参考文件**: 提供排版、色彩、空间、动效、交互、响应式、UX 写作等专业设计规范
- **27 条确定性反模式规则 + 12 条 LLM 评审规则**: 自动检测并避免常见设计陷阱（如过度使用 Inter 字体、卡片嵌套、灰色文字等）
- **CLI 和浏览器扩展**: 无需 API 密钥即可运行反模式检查
- **"Live" 模式**: 在浏览器中实时迭代设计变体

**技术亮点**: 基于 Anthropic 的 frontend-design skill 扩展，提供 7 个 Markdown 格式的领域参考文件作为 AI 上下文，支持通过 `/impeccable` 命令与 AI 进行设计协作，并提供独立的反模式检查工具。

---
## 7. [p-e-w/heretic](https://github.com/p-e-w/heretic)
- **语言**: Python
- **Stars**: 23,050
- **简介**: Fully automatic censorship removal for language models

### AI 总结
**简介**: Heretic 是一个全自动去除语言模型审查（安全对齐）的工具，通过消融技术实现高性能去审查。

**核心功能**:
- 自动移除Transformer语言模型中的审查机制，无需昂贵的后训练
- 支持大多数稠密模型、多模态模型、MoE架构及混合模型（如Qwen3.5）
- 内置参数优化器，自动寻找高质量消融参数，最小化拒绝回答次数和KL散度
- 提供模型评估功能，可对比去审查模型与原始模型的性能差异

**技术亮点**: 基于定向消融（abliteration）技术，结合Optuna的TPE参数优化器，实现完全自动化的去审查过程，在保持原始模型能力的同时有效抑制拒绝回答。

---
## 8. [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin)
- **语言**: TypeScript
- **Stars**: 19,122
- **简介**: Official Compound Engineering plugin for Claude Code, Codex, Cursor, and more

### AI 总结
**简介**: 这是一个为 AI 编程助手（如 Claude Code、Cursor 等）设计的官方插件，通过一系列技能和代理，让每次工程工作都为后续工作积累正向收益，实现“复合工程”。

**核心功能**:
- **战略与规划**: 通过 `/ce-strategy` 制定产品战略，使用 `/ce-brainstorm` 和 `/ce-plan` 进行需求讨论和实现计划。
- **执行与调试**: 使用 `/ce-work` 执行计划，通过 `/ce-debug` 系统化排查和修复缺陷。
- **审查与沉淀**: 通过 `/ce-code-review` 和 `/ce-doc-review` 进行多代理代码审查，并使用 `/ce-compound` 将学习经验文档化。
- **产品监控**: 使用 `/ce-product-pulse` 生成时间窗口内的产品使用和性能报告。

**技术亮点**: 采用 TypeScript 开发，包含 37 个技能和 51 个代理，强调“80% 在计划与审查，20% 在编码”的工作流哲学，通过结构化提示和知识复用，降低技术债务。

---
## 9. [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)
- **语言**: Python
- **Stars**: 81,807
- **简介**: TradingAgents: Multi-Agents LLM Financial Trading Framework

### AI 总结
**简介**: TradingAgents 是一个基于多智能体 LLM 的金融交易框架，通过模拟真实交易公司的运作模式，利用多个专业化的 AI 智能体协作进行市场分析和交易决策。

**核心功能**:
- 部署多个专业 LLM 智能体（基本面分析师、情绪分析师、技术分析师、交易员、风险管理团队等）协同工作
- 智能体通过动态讨论机制确定最优交易策略
- 支持多语言、多模型提供商（GPT-5.x、Gemini 3.x、Claude 4.x、Grok 4.x 等）
- 提供回测功能和结构化输出智能体（研究经理、交易员、投资组合经理）
- 支持 Docker 部署、代理配置和跨平台稳定性

**技术亮点**:
- 基于 Python 构建的多智能体 LLM 架构
- 集成 LangGraph 检查点恢复和持久化决策日志
- 统一模型目录，支持 API 密钥自动检测和远程 Ollama 支持
- 提供结构化输出和五级评分体系
- 支持多种 LLM 提供商（OpenAI、Anthropic、Google、DeepSeek、Qwen 等）

---
## 10. [revfactory/harness](https://github.com/revfactory/harness)
- **语言**: HTML
- **Stars**: 5,174
- **简介**: A meta-skill that designs domain-specific agent teams, defines specialized agents, and generates the skills they use.

### AI 总结
**简介**: Harness 是一个为 Claude Code 设计的团队架构工厂，能够根据用户输入的领域描述，自动生成由多个专业智能体组成的协作团队及其所需技能。

**核心功能**:
- **智能体团队设计**: 提供 6 种预定义的团队架构模式（如管道、扇出/扇入、专家池、生产者-评审者、监督者、层级委派）供选择。
- **技能自动生成**: 根据领域描述，自动生成智能体所需的技能，并采用渐进式披露机制优化上下文管理。
- **编排与协调**: 实现智能体间的数据传递、错误处理和团队协作协议。
- **验证与测试**: 提供触发器验证、干运行测试以及带/不带技能的对比测试。

**技术亮点**: 位于 Claude Code 生态系统的 L3 元工厂层，作为团队架构工厂，可与其他 L3 工具（如 Archon）组合使用。

---
