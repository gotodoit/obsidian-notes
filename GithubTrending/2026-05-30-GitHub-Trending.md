---
tags:
  - github-trending
  - daily
date: 2026-05-30
created: 2026-05-30T01:55:43.415Z
---

# 2026-05-30 GitHub Trending Top 10

## 1. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)
- **语言**: Python
- **Stars**: 69,746
- **简介**: 利用AI大模型，一键生成高清短视频 Generate short videos with one click using AI LLM.

### AI 总结
**简介**: MoneyPrinterTurbo 是一款利用 AI 大模型，根据主题或关键词一键生成高清短视频的开源工具。

**核心功能**:
- **AI自动生成**：支持 AI 自动生成视频文案，也支持用户自定义文案。
- **多种视频尺寸**：支持竖屏 9:16 和横屏 16:9 高清视频。
- **批量生成**：支持一次生成多个视频，方便用户筛选。
- **丰富定制选项**：支持调节视频片段时长、多种语音合成、字幕样式（字体、位置、颜色、大小、描边）和背景音乐设置。
- **高清无版权素材**：视频素材来源高清且无版权，也支持使用本地素材。

**技术亮点**:
- **MVC架构**：代码结构清晰，易于维护，同时支持 API 和 Web 界面。
- **多模型接入**：支持 OpenAI、Moonshot、DeepSeek、通义千问、Google Gemini、Ollama 等多种 AI 模型。
- **多平台部署**：支持 Windows 一键启动、MacOS/Linux 本地部署、Docker 部署以及 Google Colab 在线运行。

---
## 2. [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **语言**: Python
- **Stars**: 130,026
- **简介**: Python tool for converting files and office documents to Markdown.

### AI 总结
**简介**: MarkItDown 是微软推出的轻量级 Python 工具，用于将多种文件格式转换为 Markdown，便于 LLM 及文本分析管线处理。

**核心功能**:
- 支持 PDF、Word、Excel、PowerPoint、HTML、EPub、图片、音频、YouTube 链接等格式转 Markdown。
- 提供命令行工具，支持管道输入和 `-o` 输出文件。
- 可选依赖安装，按需激活特定文件格式支持。
- 支持第三方插件扩展，如 OCR 插件。

**技术亮点**:
- 专注于保留文档结构（标题、列表、表格、链接等）为 Markdown，兼顾人类可读性与 LLM 友好性。
- 基于 Python 3.10+，依赖管理灵活，支持 `pip` 和源码安装。
- 内置安全提示，强调在不可信环境中对输入进行清洗。

---
## 3. [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin)
- **语言**: TypeScript
- **Stars**: 18,150
- **简介**: Official Compound Engineering plugin for Claude Code, Codex, Cursor, and more

### AI 总结
**简介**: Compound Engineering 是一个官方插件，为 Claude Code、Codex、Cursor 等 AI 编码助手提供技能和代理，帮助开发者将 80% 的精力投入在规划和审查，20% 投入执行，从而降低技术债务、加速后续开发。

**核心功能**:
- **战略与规划**: 通过 `/ce-strategy` 创建产品策略，`/ce-ideate` 进行创意生成与评估，`/ce-brainstorm` 交互式梳理需求并生成文档，`/ce-plan` 制定详细实现计划。
- **执行与调试**: 使用 `/ce-work` 配合工作树和任务跟踪执行计划，`/ce-debug` 系统性复现故障、追踪根因并修复。
- **审查与学习**: 通过 `/ce-code-review` 进行多代理代码审查，`/ce-compound` 将学习成果文档化，方便后续复用。
- **产品洞察**: `/ce-product-pulse` 生成时间窗口内的使用、性能、错误报告，并保存为可浏览的时间线。

**技术亮点**: 基于 TypeScript 开发，采用多代理协作架构，内置 37 个技能和 51 个代理，支持与主流 AI 编码工具（Claude Code、Cursor 等）集成，并通过工作树和任务跟踪实现高效的执行闭环。

---
## 4. [twentyhq/twenty](https://github.com/twentyhq/twenty)
- **语言**: TypeScript
- **Stars**: 48,426
- **简介**: The open alternative to Salesforce, designed for AI.

### AI 总结
**简介**: Twenty 是一个开源 CRM 系统，旨在作为 Salesforce 的替代方案，专为 AI 时代设计，让技术团队能够像构建代码一样构建和定制 CRM。

**核心功能**:
- **自定义应用构建**: 通过 CLI 工具和 SDK，以代码方式定义对象、字段和视图，快速搭建定制化 CRM 应用。
- **灵活部署**: 支持云端快速启动（twenty.com）、本地自托管（Docker Compose）以及本地开发环境搭建。
- **模块化组件**: 提供对象、视图、工作流和代理等现代 CRM 构建块，并允许通过代码进行扩展。

**技术亮点**: 基于 TypeScript 开发，提供 `twenty-sdk` 和 CLI 工具（`create-twenty-app`），支持以声明式代码定义业务逻辑，并集成 AI 能力。

---
## 5. [anthropics/claude-code](https://github.com/anthropics/claude-code)
- **语言**: Python
- **Stars**: 127,897
- **简介**: Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands.

### AI 总结
**简介**: Claude Code 是一个驻留在终端中的智能编码工具，能理解你的代码库，通过自然语言命令协助你更快地编码。

**核心功能**:
- 执行日常编码任务（如解释复杂代码、处理 Git 工作流）
- 支持在终端、IDE 或通过 GitHub @claude 使用
- 提供插件系统，扩展自定义命令和代理功能
- 通过 `/bug` 命令直接报告问题

**技术亮点**: 基于 Node.js 18+ 开发，支持多平台安装（MacOS/Linux/Windows），使用 npm 包管理。

---
## 6. [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)
- **语言**: Shell
- **Stars**: 28,175
- **简介**: Taste-Skill - gives your AI good taste. stops the AI from generating boring, generic slop

### AI 总结
**简介**: Taste-Skill 是一个为 AI Agent 提供“品味”的框架，通过注入设计准则（布局、排版、动效、间距）来避免生成“粗制滥造”（slop）的 UI 界面，同时支持图片生成技能。

**核心功能**:
- **多种 Agent 技能**: 提供不同的 Agent 技能（如 `design-taste-frontend` v2、`gpt-taste` 等），用于提升 AI 输出的代码质量或生成高保真参考图。
- **一键安装**: 通过 `npx skills add` 命令行工具，可快速将技能安装到 Codex、Cursor、Claude Code 等主流 AI 开发工具中。
- **支持图片生成**: 包含用于生成参考板（网页、移动端、品牌套件）的图片生成技能，可与 ChatGPT Images 等工具配合使用。
- **版本迭代与兼容**: 提供 v2（实验性重写版）和 v1（稳定版）技能，用户可根据项目需求选择或升级。

**技术亮点**: 基于 **Shell** 脚本和 **Agent Skills** 标准构建，通过 `SKILL.md` 文件定义规则，实现与多种 AI 前端工具的无缝集成。

---
## 7. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 1,307
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，提供开发者工具、框架和 SaaS 产品的插件规范与实现。

**核心功能**:
- 提供多种开发者工具插件，包括持续学习、团队协作、代码审查、文档渲染等功能
- 支持插件市场管理，每个插件包含独立的 manifest 文件、技能、规则和 MCP 服务器定义
- 包含插件创建和验证工具，以及 CLI 设计模式、并行任务编排等高级功能

**技术亮点**: 基于 TypeScript 开发，采用多插件市场仓库结构，每个插件独立目录包含 `.cursor-plugin/plugin.json` 清单文件，支持 agent 技能（SKILL.md）、Cursor 规则（.mdc 文件）和 MCP 服务器定义。

---
## 8. [run-llama/liteparse](https://github.com/run-llama/liteparse)
- **语言**: Rust
- **Stars**: 7,345
- **简介**: A fast, helpful, and open-source document parser

### AI 总结
**简介**: LiteParse 是一个开源的、快速轻量的文档解析工具，专注于本地化、高质量的空间文本解析，支持 PDF、DOCX 等多种格式。

**核心功能**:
- **快速文本解析**: 基于 PDFium 实现空间文本提取，并输出带边界框的结构化数据。
- **灵活的 OCR 系统**: 内置 Tesseract，同时支持接入 EasyOCR、PaddleOCR 等任意 HTTP OCR 服务器。
- **多格式输入与输出**: 支持 PDF、DOCX、XLSX、PPTX 和图片输入，输出为 JSON（含边界框）、纯文本或 PNG 截图。
- **跨语言与跨平台**: 提供 Rust、Node.js/TypeScript、Python、WASM 绑定，支持 Linux、macOS 和 Windows。

**技术亮点**: 采用 Rust 核心引擎，通过 PDFium 和 OCR 融合技术实现高效解析；支持本地运行，无云依赖；具备截图生成功能，便于 LLM 代理处理。

---
## 9. [galilai-group/stable-worldmodel](https://github.com/galilai-group/stable-worldmodel)
- **语言**: Python
- **Stars**: 1,260
- **简介**: A platform for reproducible world model research and evaluation

### AI 总结
**简介**: stable-worldmodel 是一个用于可复现世界模型研究和评估的 Python 平台，提供数据收集、模型训练和模型预测控制评估的统一接口。

**核心功能**:
- 提供标准化的环境套件，支持数据收集、模型训练和评估全流程
- 内置常见基线模型（如 LeWM、DINO-WM）和规划求解器（如 CEMSolver）的参考实现
- 支持多种数据格式（LanceDB、HDF5、文件夹、视频），并可通过格式注册表扩展

**技术亮点**: 基于 PyTorch 实现，支持 LanceDB 的高效索引读取和追加写入，提供完整的文档和测试覆盖。

---
## 10. [byoungd/English-level-up-tips](https://github.com/byoungd/English-level-up-tips)
- **语言**: Unknown
- **Stars**: 49,650
- **简介**: An advanced guide to learn English which might benefit you a lot 🎉 . 离谱的英语学习指南/英语学习教程/英语学习/学英语

### AI 总结
**简介**: 一份详尽的英语进阶指南，旨在帮助学习者高效、自然地掌握英语，并融入AI辅助学习。

**核心功能**:
- 提供从理解、词汇、听力、阅读到口语、写作的系统性学习路径
- 新增AI学习章节，指导如何将Gemini、ChatGPT等工具串成完整训练流程
- 包含CEFR等级参考、特色学习模块、词库及个人经验分享

**技术亮点**: 整合AI工具（Gemini、ChatGPT、Claude等）作为英语学习加速器，设计听说读写训练回路

---
