---
tags:
  - github-trending
  - daily
date: 2026-05-29
created: 2026-05-29T01:55:44.983Z
---

# 2026-05-29 GitHub Trending Top 10

## 1. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)
- **语言**: Python
- **Stars**: 66,521
- **简介**: 利用AI大模型，一键生成高清短视频 Generate short videos with one click using AI LLM.

### AI 总结
**简介**: 只需提供视频主题或关键词，即可利用AI大模型全自动生成高清短视频的工具。

**核心功能**:
- AI自动生成视频文案，或支持自定义文案
- 支持竖屏9:16和横屏16:9两种高清视频尺寸
- 支持批量生成视频，可一次生成多个并选择最满意的
- 支持中文和英文视频文案，多种语音合成及实时试听
- 支持字幕生成（可调整字体、位置、颜色、大小、描边）和背景音乐（随机或指定，可调音量）
- 视频素材高清无版权，也可使用本地素材

**技术亮点**: 采用完整的MVC架构，代码结构清晰，支持API和Web界面；可接入OpenAI、DeepSeek、通义千问、Google Gemini等多种主流AI模型。

---
## 2. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 197,340
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个跨多种 AI 编程助手（如 Claude Code、Codex、Cursor 等）的代理工作流性能优化系统，提供技能、直觉、记忆、安全扫描和研究优先开发等完整能力。

**核心功能**:
- 技能系统：支持可复用的代理技能和钩子
- 记忆优化：持续学习和记忆管理机制
- 安全扫描：集成安全检测功能
- 跨平台兼容：支持 Codex、Claude Code、Cursor、OpenCode、Gemini、Zed、GitHub Copilot 等 7 种 AI 代理框架
- 生产就绪：经过 10 多个月实际产品开发验证的规则、MCP 配置和遗留命令适配
- 多语言生态：覆盖 12+ 种语言的文档和社区

**技术亮点**: 使用 JavaScript/TypeScript 构建，支持 Shell、Python、Go、Java、Perl 等多语言环境；采用 MIT 开源许可，提供 OSS 免费版和 Pro 付费版（GitHub App 模式）；架构上实现跨代理框架的统一操作层和 Hermes 操作员故事系统。

---
## 3. [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)
- **语言**: Shell
- **Stars**: 26,530
- **简介**: Taste-Skill - gives your AI good taste. stops the AI from generating boring, generic slop

### AI 总结
**简介**: Taste-Skill 是一个为 AI 代理提供“好品味”的前端框架，旨在替代 AI 生成的千篇一律、枯燥的界面，产出更具设计感、布局更强、动效更佳、间距更合理的 UI。

**核心功能**:
- **提供可移植的“代理技能”**：通过 `npx skills add` 命令，为 Codex、Cursor、Claude 等 AI 代理安装特定的技能包，使其在生成代码时遵循更优秀的设计范式。
- **包含多种技能变体**：提供多个技能包（如 `design-taste-frontend` v2、v1 版本、GPT 专用版等），用户可根据具体 AI 工具和工作流选择合适的版本。
- **支持图像生成**：包含用于生成参考板（网页、移动端、品牌套件）的图像生成技能，可与 ChatGPT Images 等生成器配合使用。
- **升级界面设计标准**：通过硬性规则（如禁止使用 em-dash）和设计系统映射，强制 AI 输出更强的布局、排版、动效和间距，杜绝“样板间”式的低质量 UI。

**技术亮点**: 基于 Shell 脚本和 `npx skills add` 工具链，通过 `SKILL.md` 文件定义可安装的“代理技能”，实现与主流 AI 代码代理（Codex, Cursor, Claude）的无缝集成。

---
## 4. [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop)
- **语言**: Unknown
- **Stars**: 6,447
- **简介**: A skill file for removing AI tells from prose

### AI 总结
**简介**: 一个用于去除AI写作痕迹（如固定短语、结构套路）的技能文件，可应用于Claude或其他大语言模型。

**核心功能**:
- **短语过滤**：移除AI常见开场白、强调词、商业术语、所有副词及模糊陈述。
- **结构去套路**：识别并消除二元对比、否定列表、戏剧化碎片句、设问句、虚假动因等结构性陈词滥调。
- **句子级规则**：禁止Wh-开头句、破折号、碎片化断句、极端用词，强制使用主动语态。
- **评分系统**：从直接性、节奏、信任感、真实性、信息密度五个维度打分，低于35/50需修改。

**技术亮点**:
- 模块化技能结构，包含核心指令文件（SKILL.md）与参考文件（短语、结构、示例），便于集成到Claude Code、Claude Projects或API系统提示中。
- 支持自定义配置与按需加载参考文件，灵活适配不同使用场景。

---
## 5. [twentyhq/twenty](https://github.com/twentyhq/twenty)
- **语言**: TypeScript
- **Stars**: 47,883
- **简介**: The open alternative to Salesforce, designed for AI.

### AI 总结
**简介**: Twenty 是一个开源的 CRM 系统，旨在替代 Salesforce，并为 AI 技术设计。

**核心功能**:
- **自定义 CRM 构建**: 提供对象、字段、视图等构建块，允许开发者通过代码定义和扩展 CRM 功能。
- **多部署方式**: 支持云端快速启动、本地自托管（Docker Compose）以及通过 CLI 构建应用。
- **应用开发与发布**: 提供 Twenty CLI 和 SDK，支持将自定义对象、视图、代理和逻辑函数发布到工作区。

**技术亮点**: 采用 TypeScript 开发，支持代码化定义 CRM 模型（对象、字段等），并集成 Docker Compose 进行自托管部署。

---
## 6. [DigitalPlatDev/FreeDomain](https://github.com/DigitalPlatDev/FreeDomain)
- **语言**: HTML
- **Stars**: 170,772
- **简介**: DigitalPlat FreeDomain: Free Domain For Everyone

### AI 总结
**简介**: DigitalPlat FreeDomain 是一个提供免费域名注册服务的项目，旨在让每个人都能拥有数字身份。

**核心功能**:
- 提供多种免费域名后缀（如 .DPDNS.ORG、.US.KG 等）
- 支持用户将域名托管到任意 DNS 提供商（如 Cloudflare、FreeDNS）
- 提供域名管理仪表盘和详细教程
- 已服务超过 500,000 个域名注册

**技术亮点**: 基于 HTML 构建，项目自述从 15 岁时的 DNS 实验发展而来，目前通过 Discord 社区提供支持，并设有滥用报告机制（abuse@digitalplat.org）。

---
## 7. [byoungd/English-level-up-tips](https://github.com/byoungd/English-level-up-tips)
- **语言**: Unknown
- **Stars**: 48,591
- **简介**: An advanced guide to learn English which might benefit you a lot 🎉 . 离谱的英语学习指南/英语学习教程/英语学习/学英语

### AI 总结
**简介**: 一份系统、详细的英语进阶学习指南，涵盖听说读写全技能，并融合AI辅助学习，旨在帮助学习者高效、自然地掌握英语。

**核心功能**:
- **系统化学习路径**: 按英语水平等级（CEFR）划分，提供从理解、词汇、听力、阅读、口语到写作的完整学习章节。
- **AI 辅助学习**: 专门章节介绍如何利用 Gemini、ChatGPT、Claude 等 AI 工具构建听说读写训练回路，作为学习加速器。
- **实用资源与工具**: 推荐可信 AI 资源库（ku0.com），并提供词库、辅助工具等资源。
- **社区与文档**: 提供多语言版本（中/英），支持在线（知乎、GitHub Pages、GitBook）阅读。

**技术亮点**:
- **持续更新的 AI 章节**: 2026版系统回答 AI 工具选择、训练流程设计及分工使用策略，而非通用 Prompt。
- **特色 SVG 图示**: 使用可视化图标引导各章节内容，直观展示学习路径。

---
## 8. [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **语言**: Python
- **Stars**: 127,800
- **简介**: Python tool for converting files and office documents to Markdown.

### AI 总结
**简介**: MarkItDown 是微软开源的 Python 工具，用于将 PDF、Office 文档、图片、音频等多种文件格式转换为 Markdown 文本，便于 LLM 和文本分析管道使用。

**核心功能**:
- 支持 PDF、PowerPoint、Word、Excel、图片、音频、HTML、CSV、JSON、XML、EPUB、YouTube URL 等多种文件格式转换为 Markdown
- 提供命令行工具和 Python API，支持管道输入和输出文件指定
- 支持通过插件扩展功能，如 OCR 插件可增强 PDF 等文件的文本提取
- 可选依赖安装，用户可根据需要仅安装特定格式的转换支持（如 `[pdf, docx, pptx]`）

**技术亮点**:
- 使用 Python 3.10+，轻量级设计，专注于为 LLM 提供 token 高效的 Markdown 输出
- 保留文档结构（标题、列表、表格、链接等），输出适合文本分析工具消费
- 支持通过 `pip install 'markitdown[all]'` 一键安装所有依赖，或按需安装特定格式支持
- 内置安全考虑，建议在不可信环境中使用最小权限的 `convert_*` 函数

---
## 9. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 211,138
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套为编码代理设计的完整软件开发方法论，基于可组合的技能和初始指令，让代理从设计到实现都遵循规范流程。

**核心功能**:
- **需求澄清**：代理在写代码前主动提问，引导用户明确需求，并生成可读的设计文档。
- **隔离开发**：设计批准后，自动创建独立工作空间和新分支，确保项目基线干净。
- **任务分解**：将实现计划拆解为2-5分钟的小任务，每个任务包含文件路径、完整代码和验证步骤。
- **子代理驱动开发**：启动子代理依次执行任务，自动审查工作，支持数小时自主开发。

**技术亮点**: 基于Shell脚本构建，支持多种编码代理平台（Claude Code、Codex CLI、Cursor等），通过插件市场分发，强调TDD、YAGNI和DRY原则。

---
## 10. [revfactory/harness](https://github.com/revfactory/harness)
- **语言**: HTML
- **Stars**: 3,910
- **简介**: A meta-skill that designs domain-specific agent teams, defines specialized agents, and generates the skills they use.

### AI 总结
**简介**: Harness 是一个为 Claude Code 设计的团队架构工厂，能根据项目描述自动生成专业化的智能体团队及技能。

**核心功能**:
- **智能体团队设计**：提供 6 种预定义架构模式（Pipeline、Fan-out/Fan-in、Expert Pool、Producer-Reviewer、Supervisor 和 Hierarchical Delegation）
- **技能自动生成**：基于渐进式披露原则，自动生成智能体所需的专业技能文件
- **团队编排**：实现智能体间的数据传递、错误处理和协作协议
- **验证测试**：支持触发验证、干运行测试以及有无技能的对比测试

**技术亮点**:
- 位于 Claude Code 生态系统的 L3 元工厂层，属于团队架构工厂子层
- 输入领域描述 → 输出完整的智能体定义 (.claude/agents/) 和技能文件 (.claude/skills/)
- 支持多语言触发（英语、韩语、日语）

---
