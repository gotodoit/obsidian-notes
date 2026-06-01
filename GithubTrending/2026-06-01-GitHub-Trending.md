---
tags:
  - github-trending
  - daily
date: 2026-06-01
created: 2026-06-01T01:55:43.842Z
---

# 2026-06-01 GitHub Trending Top 10

## 1. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)
- **语言**: Python
- **Stars**: 74,394
- **简介**: 利用AI大模型，一键生成高清短视频 Generate short videos with one click using AI LLM.

### AI 总结
**简介**: 基于AI大模型，一键生成高清短视频的开源工具。

**核心功能**:
- 输入主题或关键词，全自动生成视频文案、素材、字幕和背景音乐
- 支持竖屏(9:16)和横屏(16:9)高清视频尺寸
- 支持批量生成视频，可调节视频片段时长
- 支持中英文文案、多种语音合成、自定义字幕样式
- 支持多种AI模型接入（OpenAI、DeepSeek、Moonshot等）
- 支持在线高清无版权素材和本地素材

**技术亮点**: 采用MVC架构，代码结构清晰；支持API和Web界面；支持Docker部署和Google Colab在线运行。

---
## 2. [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **语言**: Python
- **Stars**: 135,119
- **简介**: Python tool for converting files and office documents to Markdown.

### AI 总结
**简介**: MarkItDown 是微软推出的轻量级 Python 工具，用于将多种文件格式转换为 Markdown，方便 LLM 和文本分析流程处理。

**核心功能**:
- 支持 PDF、PPT、Word、Excel、图片、音频、HTML、CSV/JSON/XML、ZIP、YouTube 链接、EPUB 等格式
- 提供命令行工具，支持管道输入和输出重定向
- 可通过插件扩展功能，如 OCR 支持
- 可选依赖安装，按需激活特定文件格式支持

**技术亮点**: 基于 Python 3.10+，采用模块化设计，核心转换逻辑保持轻量，利用可选依赖和插件机制灵活扩展，输出 Markdown 格式保留文档结构（标题、列表、表格、链接等）。

---
## 3. [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling)
- **语言**: Python
- **Stars**: 56,693
- **简介**: 🕷️ An adaptive Web Scraping framework that handles everything from a single request to a full-scale crawl!

### AI 总结
**简介**: Scrapling 是一个自适应的 Web 抓取框架，能处理从单次请求到大规模爬取的所有任务。

**核心功能**:
- **自适应解析**: 解析器能学习网站变化，在页面更新时自动重新定位元素。
- **反爬绕过**: 内置的抓取器能开箱即用地绕过 Cloudflare Turnstile 等反机器人系统。
- **爬虫框架**: 支持多会话并发爬取，具备暂停/恢复和自动代理轮换功能。
- **命令行界面 (CLI)**: 提供 CLI 工具，方便操作。
- **MCP 服务器**: 支持 AI 代理集成。

**技术亮点**: 采用 Python 编写，支持同步和异步抓取器（如 `StealthyFetcher`、`DynamicFetcher`），具备实时统计和流式处理能力，可结合 AI 代理技能使用。

---
## 4. [nesquena/hermes-webui](https://github.com/nesquena/hermes-webui)
- **语言**: Python
- **Stars**: 10,031
- **简介**: Hermes WebUI: The best way to use Hermes Agent from the web or from your phone!

### AI 总结
**简介**: 为 Hermes Agent 提供轻量级 Web 界面，实现与 CLI 近乎 1:1 的功能对等，支持通过手机或浏览器远程管理。

**核心功能**:
- **三栏式布局**: 左侧会话导航、中央聊天面板、右侧工作区文件浏览，支持暗色/亮色主题切换
- **完整会话管理**: 支持项目标签、工具调用卡片、会话历史，与 CLI 完全对等
- **文件浏览器**: 工作区文件内联预览，无需额外配置即可操作
- **安全访问**: 通过 SSH 隧道加密连接，单命令启动即可从任意设备访问

**技术亮点**:
- 纯 Python + Vanilla JS 实现，无需构建步骤/框架/打包工具
- 复用现有 Hermes Agent 配置与模型，零额外配置
- 自动上下文环显示 Token 用量，底部合成工具栏集成模型/配置文件/工作区控制

---
## 5. [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin)
- **语言**: TypeScript
- **Stars**: 18,726
- **简介**: Official Compound Engineering plugin for Claude Code, Codex, Cursor, and more

### AI 总结
**简介**: 一个面向 AI 编程助手（如 Claude Code、Cursor）的插件，通过结构化工作流（规划、执行、审查、沉淀）实现“复合工程”，让每次开发工作都降低后续工作的难度。

**核心功能**:
- **策略与创意**: `/ce-strategy` 维护产品策略文档，`/ce-ideate` 生成并筛选创意。
- **规划与执行**: `/ce-brainstorm` 交互式需求分析，`/ce-plan` 制定实施计划，`/ce-work` 按计划执行任务。
- **审查与调试**: `/ce-code-review` 多智能体代码审查，`/ce-debug` 系统性故障排查。
- **知识沉淀**: `/ce-compound` 将学习经验文档化，`/ce-product-pulse` 生成产品运行报告。

**技术亮点**: 基于 TypeScript 开发，采用“80% 规划与评审，20% 执行”的理念，通过 37 个技能和 51 个智能体实现开发流程的自动化和知识复用。

---
## 6. [github/docs](https://github.com/github/docs)
- **语言**: TypeScript
- **Stars**: 19,744
- **简介**: The open-source repo for docs.github.com

### AI 总结
**简介**: GitHub Docs 是 docs.github.com 的开源仓库，允许社区贡献文档内容。
**核心功能**:
- 提供 GitHub 官方文档的公开开源版本，支持外部贡献者参与内容编辑（.md 文件）
- 与私有仓库 `github/docs-internal` 同步，确保员工和外部贡献的变更保持一致
- 提供贡献指南和入门资源，帮助新贡献者参与开源协作
**技术亮点**: 使用 TypeScript 构建，采用双许可证（文档使用 CC BY 4.0，代码使用 MIT）

---
## 7. [OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM)
- **语言**: Python
- **Stars**: 23,574
- **简介**: VoxCPM2: Tokenizer-Free TTS for Multilingual Speech Generation, Creative Voice Design, and True-to-Life Cloning

### AI 总结
**简介**: VoxCPM2 是一个基于扩散自回归架构的无分词器文本转语音系统，支持多语言语音生成、创意语音设计和逼真语音克隆。

**核心功能**:
- **多语言语音生成**: 支持 30 种语言，无需语言标签即可直接合成语音
- **语音设计**: 通过自然语言描述（如性别、年龄、语气、情感）创建全新语音，无需参考音频
- **可控语音克隆**: 从短参考音频克隆任意声音，并可调节情感、节奏等风格参数
- **终极克隆**: 通过参考音频及其文本转录，完美保留音色、节奏、情感和风格等所有语音细节
- **48kHz 高质量音频**: 直接输出 48kHz 录音室级音频，无需外部上采样器
- **实时流式合成**: 在 NVIDIA RTX 4090 上 RTF 低至 ~0.3，通过 Nano-vLLM 或 vLLM-Omni 加速可降至 ~0.13

**技术亮点**: 采用无分词器（Tokenizer-Free）的端到端扩散自回归架构，基于 MiniCPM-4 骨干网络训练，使用 AudioVAE V2 的非对称编解码设计实现内置超分辨率，支持 PagedAttention 和 OpenAI 兼容 API。

---
## 8. [revfactory/harness](https://github.com/revfactory/harness)
- **语言**: HTML
- **Stars**: 4,629
- **简介**: A meta-skill that designs domain-specific agent teams, defines specialized agents, and generates the skills they use.

### AI 总结
**简介**: Harness 是一个面向 Claude Code 的团队架构工厂，能够根据领域描述自动生成专用的 Agent 团队及其技能。

**核心功能**:
- **Agent 团队设计** — 提供6种架构模式（Pipeline、Fan-out/Fan-in、Expert Pool、Producer-Reviewer、Supervisor、Hierarchical Delegation），根据输入自动选择并配置
- **技能自动生成** — 为每个 Agent 自动生成 `.claude/skills/` 下的技能文件，采用渐进式披露设计以优化上下文管理
- **编排与集成** — 支持 Agent 间数据传递、错误处理及团队协调协议
- **验证与测试** — 包含触发验证、干运行测试、有无技能对比测试等

**技术亮点**: 位于 Claude Code 生态的 L3 Meta-Factory 层（团队架构工厂子层），通过6种预定义团队模式将领域描述转化为 Agent 定义（`.claude/agents/`）和技能文件。

---
## 9. [FareedKhan-dev/train-llm-from-scratch](https://github.com/FareedKhan-dev/train-llm-from-scratch)
- **语言**: Jupyter Notebook
- **Stars**: 2,994
- **简介**: A straightforward method for training your LLM, from downloading data to generating text.

### AI 总结
**简介**: 该项目提供了一个从零开始训练你自己的大语言模型（LLM）的完整方法，涵盖从数据下载到文本生成的全流程。

**核心功能**:
- **从零实现Transformer**: 基于PyTorch和“Attention is All You Need”论文，从零构建Transformer模型。
- **支持多规模模型训练**: 提供脚本，可在单GPU上训练百万（13M）或十亿（2B）参数级别的LLM。
- **提供完整训练流程**: 包含数据准备、模型架构（MLP、单头/多头注意力、Transformer Block）、批处理、训练循环、模型保存和文本生成等完整步骤。
- **提供示例输出**: 展示了训练后的13M参数模型生成的文本样例。

**技术亮点**:
- 使用 **PyTorch** 框架实现。
- 训练数据使用大规模、开源的 **Pile 数据集**。
- 提供了针对不同GPU（如A100、RTX 3090、V100等）的训练可行性对比，帮助用户选择合适的硬件。

---
## 10. [supermemoryai/supermemory](https://github.com/supermemoryai/supermemory)
- **语言**: TypeScript
- **Stars**: 23,380
- **简介**: Memory engine and app that is extremely fast, scalable. The Memory API for the AI era.

### AI 总结
**简介**: Supermemory 是一个为 AI 打造的极速、可扩展的记忆引擎和应用，旨在解决 AI 在对话间遗忘上下文的问题，被公认为行业领先的记忆基准方案。

**核心功能**:
- **智能记忆管理**: 自动从对话中提取事实，处理时间变化、矛盾信息，并具备自动遗忘功能。
- **用户画像构建**: 自动维护用户上下文，包括稳定事实和近期活动，调用延迟约 50ms。
- **混合搜索**: 将 RAG 检索与个性化记忆结合在单一查询中，同时获取知识库文档和用户上下文。
- **多源连接器**: 支持 Google Drive、Gmail、Notion、OneDrive、GitHub 等第三方服务自动同步，并支持实时 Webhook。
- **多模态内容提取**: 支持 PDF、图片（OCR）、视频（转录）、代码（AST 感知分块）等多种文件格式。

**技术亮点**: 基于 TypeScript 构建，提供单一 API 即可集成记忆、RAG、用户画像和连接器功能，无需配置向量数据库或嵌入管道。支持 npm 和 PyPI 包分发，并提供 MCP 服务器、浏览器扩展及多种 AI 工具（如 Claude Code）的插件。

---
