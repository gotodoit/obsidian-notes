---
tags:
  - github-trending
  - daily
date: 2026-06-03
created: 2026-06-03T01:55:43.455Z
---

# 2026-06-03 GitHub Trending Top 10

## 1. [chopratejas/headroom](https://github.com/chopratejas/headroom)
- **语言**: Python
- **Stars**: 6,603
- **简介**: Compress tool outputs, logs, files, and RAG chunks before they reach the LLM. 60-95% fewer tokens, same answers. Library, proxy, MCP server.

### AI 总结
**简介**: Headroom 是一个为 AI Agent 和 LLM 设计的上下文压缩层，可在不影响回答质量的前提下，将工具输出、日志、文件等内容的 Token 消耗减少 60-95%。

**核心功能**:
- **库模式**: 在 Python 或 TypeScript 应用中直接调用 `compress(messages)` 进行压缩
- **代理模式**: 通过 `headroom proxy --port 8787` 运行透明代理，无需修改代码
- **Agent 封装**: 一键封装 Claude、Codex、Cursor、Aider 等主流 AI Agent
- **MCP 服务器**: 提供 `headroom_compress`、`headroom_retrieve`、`headroom_stats` 等 MCP 工具
- **跨 Agent 记忆**: 在 Claude、Codex、Gemini 等 Agent 间共享记忆存储，自动去重
- **学习机制**: `headroom learn` 可从失败会话中挖掘经验，自动写入 `CLAUDE.md` / `AGENTS.md`
- **可逆压缩 (CCR)**: 原始数据本地保留，LLM 可按需通过 `headroom_retrieve` 获取

**技术亮点**: 支持 6 种压缩算法（SmartCrusher、CodeCompressor、Kompress-base 等），通过 ContentRouter 自动识别内容类型并选择最优压缩器；CacheAligner 稳定前缀以最大化 KV 缓存命中率；本地优先运行，数据无需离开本地环境。

---
## 2. [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **语言**: Python
- **Stars**: 141,241
- **简介**: Python tool for converting files and office documents to Markdown.

### AI 总结
**简介**: MarkItDown 是一个轻量级 Python 工具，用于将多种文件格式和办公文档转换为 Markdown 文本，便于 LLM 及文本分析流程使用。

**核心功能**:
- 支持转换 PDF、PowerPoint、Word、Excel、图像（EXIF 元数据和 OCR）、音频（EXIF 元数据和语音转录）、HTML、CSV/JSON/XML、ZIP、YouTube 链接、EPub 等格式。
- 提供命令行工具，支持直接转换文件、指定输出文件或通过管道输入内容。
- 支持第三方插件扩展，例如 OCR 插件可增强 PDF 等格式的文本提取能力。

**技术亮点**: 基于 Python 3.10+，采用可选依赖机制按需安装文件格式支持（如 `[pdf]`、`[docx]`），输出聚焦文档结构（标题、列表、表格、链接等）以适配 LLM 的 Markdown 理解能力。

---
## 3. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 204,047
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个跨 AI 智能体平台（如 Codex、Claude Code、Cursor 等）的智能体性能优化系统，提供技能、直觉、记忆、安全及研究优先的开发工具集。

**核心功能**:
- 跨平台智能体工作流：支持在多种 AI 智能体工具（Codex、Claude Code、Cursor、OpenCode 等）间无缝迁移与使用
- 技能与直觉系统：内置可复用的技能、直觉规则和内存优化机制，提升智能体工作效率
- 安全扫描与持续学习：提供安全扫描功能，并支持持续学习与记忆优化
- 企业级扩展：通过 ECC Pro 提供私有仓库支持、GitHub App 集成及 PR 审计功能
- 多语言生态：支持 12+ 语言生态系统，包括 Shell、TypeScript、Python、Go 等

**技术亮点**: 采用 JavaScript 开发，支持跨多智能体平台（7 种以上）的统一架构；提供 NPM 包（ecc-universal、ecc-agentshield）和 GitHub App 集成；MIT 开源许可，拥有 182K+ Stars 和 170+ 贡献者的活跃社区生态。

---
## 4. [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling)
- **语言**: Python
- **Stars**: 59,223
- **简介**: 🕷️ An adaptive Web Scraping framework that handles everything from a single request to a full-scale crawl!

### AI 总结
**简介**: Scrapling 是一个自适应的 Python 网页抓取框架，能够处理从单次请求到大规模爬取的所有任务。

**核心功能**:
- **自适应解析**: 解析器能学习网站变化，当页面更新时自动重新定位目标元素。
- **反爬虫绕过**: 内置的 Fetcher（如 StealthyFetcher）可开箱即用地绕过 Cloudflare Turnstile 等反爬系统。
- **可扩展爬虫**: 支持并发、多会话爬取，具备暂停/恢复和自动代理轮换功能。
- **多种抓取模式**: 提供同步、异步、高隐匿性和动态渲染等多种 Fetcher，适应不同场景。
- **命令行工具 (CLI)**: 提供便捷的命令行界面用于抓取操作。
- **AI/MCP 集成**: 支持 MCP 服务器和 AI Agent 技能，便于与智能体结合使用。

**技术亮点**: 基于 Python，采用自适应解析算法应对网站结构变化；内置多种 Fetcher（含 StealthyFetcher）以绕过现代反爬机制；爬虫框架支持实时统计、流式输出和高并发；提供完整的文档和社区支持。

---
## 5. [nesquena/hermes-webui](https://github.com/nesquena/hermes-webui)
- **语言**: Python
- **Stars**: 12,576
- **简介**: Hermes WebUI: The best way to use Hermes Agent from the web or from your phone!

### AI 总结
**简介**: Hermes WebUI 是一个轻量级、深色主题的 Web 应用，旨在通过浏览器或手机提供与 Hermes Agent CLI 几乎 1:1 的交互体验，无需额外构建步骤或框架。

**核心功能**:
- **三面板布局**: 左侧侧边栏管理会话和导航，中央区域进行聊天，右侧浏览工作区文件。
- **全面功能对等**: 支持 CLI 的所有操作，包括会话管理、模型选择、配置文件和工具调用。
- **控制中心**: 提供设置和会话工具的集中管理面板，并配有圆形上下文环显示令牌使用情况。
- **持久记忆**: 自动保存用户配置、代理笔记和技能系统，跨会话保留上下文。
- **自托管调度**: 支持 cron 任务，离线时运行并通过 Telegram、Discord、Slack 等 10+ 平台交付结果。
- **多模型支持**: 兼容 OpenAI、Anthropic、Google、DeepSeek、OpenRouter 等提供商。
- **移动端访问**: 可通过 SSH 隧道安全地从手机或远程设备访问。

**技术亮点**: 纯 Python 后端 + 原生 JavaScript 前端，无构建工具或框架依赖；支持 Docker 单/多容器部署；可自动发现现有 Hermes 配置。

---
## 6. [reconurge/flowsint](https://github.com/reconurge/flowsint)
- **语言**: TypeScript
- **Stars**: 4,537
- **简介**: A modern platform for visual, flexible, and extensible graph-based investigations. For cybersecurity analysts and investigators.

### AI 总结
**简介**: Flowsint 是一个开源的 OSINT 图形探索工具，专为网络安全分析师和调查人员设计，支持可视化、灵活且可扩展的基于图形的调查。

**核心功能**:
- 图形化调查界面：通过可视化图形界面探索实体间的关系
- 自动化数据丰富：内置域名、IP、ASN、CIDR、社交媒体、组织、加密货币、网站、电子邮件、电话、个人等多个类别的丰富器
- 集成工作流：支持通过 N8n 连接器与其他工作流集成
- 隐私保护：所有数据存储在本地，确保调查隐私

**技术亮点**:
- 使用 TypeScript 开发，采用模块化架构（flowsint-core、flowsint-types、flowsint-enrichers、flowsint-api、flowsint-app）
- 基于 Docker 和 Make 的快速部署
- 后端使用 FastAPI 和 Celery，数据库支持 PostgreSQL 和 Neo4j
- 支持丰富的第三方服务集成（如 Maigret、Gravatar、数据泄露检查等）

---
## 7. [OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM)
- **语言**: Python
- **Stars**: 25,161
- **简介**: VoxCPM2: Tokenizer-Free TTS for Multilingual Speech Generation, Creative Voice Design, and True-to-Life Cloning

### AI 总结
**简介**: VoxCPM2 是一个无需分词器的端到端文本转语音 (TTS) 系统，支持多语言语音生成、创意语音设计和逼真的语音克隆。

**核心功能**:
- **30语言多语种合成**: 支持 30 种语言的文本直接合成语音，无需语言标签。
- **语音设计**: 仅通过自然语言描述（性别、年龄、语气等）即可创建全新语音，无需参考音频。
- **可控语音克隆**: 从短参考片段克隆语音，并可控制情感、节奏等风格参数，同时保留原始音色。
- **终极克隆**: 提供参考音频及其文本，模型可无缝延续参考音频的每个语音细节（音色、节奏、情感、风格）。
- **48kHz 高质量音频输出**: 直接输出 48kHz 录音室级音频，内置超分辨率功能。
- **实时流式合成**: 在 NVIDIA RTX 4090 上实时因子 (RTF) 低至 ~0.3，支持 Nano-vLLM 或 vLLM-Omni 加速。

**技术亮点**: 基于 2B 参数的 MiniCPM-4 骨干网络，采用无分词器的扩散自回归架构，直接在端到端模型中生成连续语音表征，绕过离散分词。模型在超过 200 万小时的多语言语音数据上训练，并使用 AudioVAE V2 的非对称编解码设计实现 48kHz 输出。

---
## 8. [stefan-jansen/machine-learning-for-trading](https://github.com/stefan-jansen/machine-learning-for-trading)
- **语言**: Jupyter Notebook
- **Stars**: 18,502
- **简介**: Code for Machine Learning for Algorithmic Trading, 2nd edition.

### AI 总结
**简介**: 本书（第二版）旨在以全面且实用的方式展示机器学习如何为算法交易策略增加价值，涵盖从线性回归到深度强化学习的广泛技术。

**核心功能**:
- **数据与特征工程**: 涵盖数据获取、金融特征工程及投资组合管理。
- **策略设计与评估**: 使用监督和无监督学习算法设计并评估多空策略。
- **文本信号提取**: 从SEC文件、财报电话会议记录等金融文本数据中提取可交易信号。
- **深度学习应用**: 使用CNN、RNN等模型处理市场和另类数据，通过生成对抗网络生成合成数据，并利用深度强化学习训练交易代理。

**技术亮点**: 包含超过150个Jupyter Notebook示例，复现前沿研究，并演示从模型训练、回测到策略评估的完整ML交易工作流程。

---
## 9. [jamwithai/production-agentic-rag-course](https://github.com/jamwithai/production-agentic-rag-course)
- **语言**: Python
- **Stars**: 6,402
- **简介**: 

### AI 总结
**简介**: 一个面向学习者的实践课程，通过构建生产级RAG系统（arXiv论文策展人），系统性地掌握检索增强生成技术从基础设施到Agentic RAG的完整开发流程。

**核心功能**:
- 自动化的学术论文获取与解析管道（arXiv API集成）
- 生产级BM25关键词搜索（支持过滤与相关性评分）
- 混合检索系统（关键词+语义向量搜索）
- 完整的RAG管道（本地LLM、流式响应、Gradio界面）
- Agentic RAG（LangGraph驱动的智能决策与自适应检索）
- Telegram机器人集成（移动端对话式AI访问）

**技术亮点**:
- 采用"先搜索后AI"的专业路径（BM25基础→向量增强→混合检索）
- 全Docker化基础设施（FastAPI + PostgreSQL + OpenSearch + Airflow）
- 生产级监控与优化（Langfuse追踪 + Redis缓存）
- 智能RAG代理（文档评分、查询重写、越界检测防护）
- 端到端透明追踪（完整推理步骤记录）

---
## 10. [supermemoryai/supermemory](https://github.com/supermemoryai/supermemory)
- **语言**: TypeScript
- **Stars**: 24,672
- **简介**: Memory engine and app that is extremely fast, scalable. The Memory API for the AI era.

### AI 总结
**简介**: Supermemory 是一个面向 AI 时代的极速、可扩展的记忆引擎和应用，旨在为 AI 提供持久化的上下文记忆能力。

**核心功能**:
- **AI 记忆管理**: 自动从对话中提取事实，处理时间变化、矛盾信息，并支持自动遗忘过期内容。
- **用户画像**: 自动维护用户上下文，包含稳定事实和近期活动，单次调用仅需约 50ms。
- **混合搜索**: 在同一查询中结合 RAG（检索增强生成）与记忆，同时检索知识库文档和个性化上下文。
- **多模态提取器**: 支持 PDF、图片（OCR）、视频（转录）、代码（AST 感知分块）等多种格式。
- **连接器**: 与 Google Drive、Gmail、Notion、OneDrive、GitHub 等第三方服务自动同步，支持实时 Webhook。

**技术亮点**: 使用 TypeScript 构建，在 LongMemEval、LoCoMo、ConvoMem 三大 AI 记忆基准测试中排名第一。提供 NPM 和 PyPI 包，支持通过 MCP 服务器与 Claude、Cursor 等 AI 客户端集成。

---
