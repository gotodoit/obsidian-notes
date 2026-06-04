---
tags:
  - github-trending
  - daily
date: 2026-06-04
created: 2026-06-04T01:55:43.943Z
---

# 2026-06-04 GitHub Trending Top 10

## 1. [chopratejas/headroom](https://github.com/chopratejas/headroom)
- **语言**: Python
- **Stars**: 9,881
- **简介**: Compress tool outputs, logs, files, and RAG chunks before they reach the LLM. 60-95% fewer tokens, same answers. Library, proxy, MCP server.

### AI 总结
**简介**: Headroom 是一个上下文压缩层，可在工具输出、日志、文件等数据到达 LLM 之前进行压缩，减少 60-95% 的 token 消耗，同时保持答案质量。

**核心功能**:
- **多形态集成**: 支持作为 Python/TypeScript 库、代理、MCP 服务器或一键包装 Claude/Codex/Cursor 等 AI 代理
- **智能压缩引擎**: 自动检测内容类型（JSON、代码、文本），选用合适的压缩算法（SmartCrusher、CodeCompressor、Kompress-base 模型）
- **可逆压缩 (CCR)**: 原始数据本地保存，LLM 可按需通过 `headroom_retrieve` 检索，确保信息不丢失
- **跨代理内存**: 在 Claude、Codex、Gemini 等代理间共享记忆，自动去重
- **自我学习**: `headroom learn` 从失败会话中挖掘经验，自动写入 `CLAUDE.md`/`AGENTS.md`

**技术亮点**:
- **6 种压缩算法**: 包括基于 AST 的代码压缩、JSON 结构化压缩和基于 Hugging Face 模型的文本压缩
- **CacheAligner 技术**: 稳定提示前缀，提升 LLM 提供商 KV 缓存的命中率
- **本地优先**: 所有数据在本地处理，无需上传到外部服务
- **全语言支持**: 提供 Python 和 TypeScript SDK，以及独立代理模式

---
## 2. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 205,814
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个跨多种 AI 编程助手平台（如 Codex、Claude Code、Cursor 等）的智能体工作性能优化系统，提供技能、直觉、记忆、安全及研究优先的开发能力。

**核心功能**:
- 支持跨平台智能体工作流，兼容 Codex、Claude Code、Cursor、OpenCode 等 7 种以上 AI 编程助手
- 提供完整的技能、直觉、记忆优化和持续学习能力
- 集成安全扫描和研究优先开发流程
- 包含生产就绪的智能体、钩子、规则、MCP 配置及遗留命令垫片
- 提供 Hermes 操作员故事和跨平台架构指南
- 支持 GitHub App 集成，提供私有仓库审计功能

**技术亮点**: 基于 JavaScript 开发，支持 Shell、TypeScript、Python、Go、Java、Perl、Markdown 等 12 种以上语言生态系统，采用 MIT 开源协议，拥有 182K+ Star 和 170+ 贡献者。

---
## 3. [aquasecurity/trivy](https://github.com/aquasecurity/trivy)
- **语言**: Go
- **Stars**: 35,424
- **简介**: Find vulnerabilities, misconfigurations, secrets, SBOM in containers, Kubernetes, code repositories, clouds and more

### AI 总结
**简介**: Trivy 是一个全面且多功能的开源安全扫描器，用于检测容器、Kubernetes、代码仓库、云环境等多种目标中的漏洞、错误配置、密钥和软件物料清单（SBOM）。

**核心功能**:
- **多目标扫描**：支持扫描容器镜像、文件系统、Git 仓库、虚拟机镜像和 Kubernetes 集群。
- **多类型检测**：可发现操作系统包和软件依赖（SBOM）、已知漏洞（CVE）、基础设施即代码（IaC）问题和错误配置、敏感信息与密钥、软件许可证。
- **广泛兼容性**：支持多种主流编程语言、操作系统和平台。
- **易用集成**：提供 Homebrew、Docker、GitHub Actions、Kubernetes Operator、VS Code 插件等多种安装和集成方式。

**技术亮点**: 采用 Go 语言开发，具备高性能和跨平台能力；提供 canary 构建版本用于快速迭代测试；支持通过命令行灵活指定扫描目标和扫描器类型。

---
## 4. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 179,218
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 构建的、具备自我学习和持续进化能力的 AI 代理，能够在多种平台上运行，并拥有内置的学习循环机制。

**核心功能**:
- **跨平台运行**: 支持 Telegram、Discord、Slack、WhatsApp、Signal 和命令行界面，所有平台通过单一网关进程管理。
- **闭环学习系统**: 代理能自主创建技能、在使用中自我改进，并通过周期性提示和对话搜索实现跨会话记忆。
- **计划任务自动化**: 内置 cron 调度器，支持自然语言配置的日报、夜间备份和每周审计等无人值守任务。
- **子代理并行处理**: 可生成隔离的子代理处理并行工作流，并通过 RPC 调用工具。
- **灵活部署**: 支持本地、Docker、SSH、Singularity、Modal 和 Daytona 等六种终端后端，可在 $5 VPS 或 GPU 集群上运行。
- **模型无锁定**: 支持 OpenAI、Nous Portal、OpenRouter、NVIDIA NIM 等 200+ 模型，通过 `hermes model` 命令即可切换。

**技术亮点**: 采用 FTS5 会话搜索与 LLM 摘要实现跨会话回忆，集成 Honcho 辩证用户建模，兼容 agentskills.io 开放标准，支持批处理轨迹生成和压缩以训练下一代工具调用模型。

---
## 5. [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **语言**: Python
- **Stars**: 142,935
- **简介**: Python tool for converting files and office documents to Markdown.

### AI 总结
**简介**: MarkItDown 是一个轻量级 Python 工具，用于将多种文件和办公文档格式转换为 Markdown，旨在供 LLM 和文本分析管道使用。

**核心功能**:
- 支持 PDF、PowerPoint、Word、Excel、图片、音频、HTML、CSV、JSON、XML、ZIP、YouTube 链接、EPub 等多种格式转换为 Markdown
- 保留文档结构（如标题、列表、表格、链接等）作为 Markdown 格式
- 提供命令行工具和 Python API 接口
- 支持通过可选依赖模块化安装不同文件格式的转换能力
- 支持第三方插件扩展（如 OCR 插件）

**技术亮点**:
- 采用 Python 3.10+ 开发，轻量级设计
- 输出高度 token 高效的 Markdown 格式，与主流 LLM 原生兼容
- 支持流式输入输出和管道操作
- 通过插件架构支持可扩展性

---
## 6. [nesquena/hermes-webui](https://github.com/nesquena/hermes-webui)
- **语言**: Python
- **Stars**: 13,118
- **简介**: Hermes WebUI: The best way to use Hermes Agent from the web or from your phone!

### AI 总结
**简介**: Hermes WebUI 是一个轻量级、深色主题的网页应用，为 Hermes Agent 提供与 CLI 几乎完全一致的操作体验，可通过浏览器或手机安全访问（如通过 SSH 隧道）。

**核心功能**:
- **三栏布局**: 左侧会话导航、中间聊天、右侧工作区文件浏览。
- **会话与记忆持久化**: 支持会话管理、项目标签、工具调用卡片，并继承 Hermes Agent 的跨会话记忆。
- **设置与安全**: 内置密码配置、主题切换（深色/浅色）、模型和配置文件选择。
- **工作区文件管理**: 内联预览文件，支持文件浏览。
- **移动端友好**: 可通过手机浏览器访问。

**技术亮点**:
- **纯 Python + 原生 JS**: 无构建步骤、无框架、无打包器。
- **与 Hermes Agent 深度集成**: 复用现有 Hermes 设置和模型，无需额外配置。
- **支持 SSH 隧道安全访问**，并可配合 Tailscale 等工具实现远程/手机访问。

---
## 7. [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling)
- **语言**: Python
- **Stars**: 60,308
- **简介**: 🕷️ An adaptive Web Scraping framework that handles everything from a single request to a full-scale crawl!

### AI 总结
**简介**: Scrapling 是一个自适应的 Web 抓取框架，能处理从单次请求到全规模爬取的所有任务。

**核心功能**:
- **自适应解析**: 自动学习网站变化，在页面更新时重新定位目标元素。
- **反爬绕过**: 内置对 Cloudflare Turnstile 等反机器人系统的绕过能力。
- **并发爬虫**: 支持多会话并发爬取，具备暂停/恢复和自动代理轮换功能。
- **多类型抓取器**: 提供 Fetcher、AsyncFetcher、StealthyFetcher、DynamicFetcher 等多种抓取器。
- **实时统计与流式输出**: 支持高速爬取时的实时状态监控和数据流式传输。
- **CLI 与 MCP 支持**: 提供命令行界面和 MCP (Model Context Protocol) 服务器，便于集成 AI 代理。

**技术亮点**: 基于 Python 构建，采用自适应解析引擎，支持无头浏览器模式，集成了代理轮换、网络空闲等待等高级功能，并提供全面的文档和 AI 代理技能目录。

---
## 8. [opendataloader-project/opendataloader-pdf](https://github.com/opendataloader-project/opendataloader-pdf)
- **语言**: Java
- **Stars**: 23,320
- **简介**: PDF Parser for AI-ready data. Automate PDF accessibility. Open-source.

### AI 总结
**简介**: OpenDataLoader PDF 是一款开源的 PDF 解析与无障碍自动化工具，专为 AI 数据提取与 PDF 无障碍改造设计，在提取准确率基准测试中排名第一（0.907）。

**核心功能**:
- **AI 数据提取**: 将 PDF（包括扫描件、数字文档、已标记文档）转换为 Markdown、JSON（含边界框）、HTML 等结构化格式，适用于 RAG/LLM 流水线。
- **混合模式解析**: 本地确定性模式与 AI 混合模式结合，支持复杂页面（多栏、科学论文、表格、公式、图片/图表描述），内置 OCR（80+ 语言）。
- **PDF 无障碍自动化**: 自动对未标记 PDF 进行布局分析与自动标记，生成屏幕阅读器友好的 Tagged PDF，是首个端到端生成 Tagged PDF 的开源工具。
- **企业级扩展**: 企业版附加组件支持 PDF/UA 导出与无障碍工作室，遵循 Well-Tagged PDF 规范，通过 veraPDF 自动验证。

**技术亮点**: 基于 Java 11+ 开发，提供 Python、Node.js、Java SDK；与 PDF 协会及 Dual Lab（veraPDF 开发者）合作，确保规范合规；表格提取准确率达 0.928，本地模式处理速度为 0.015 秒/页。

---
## 9. [odoo/odoo](https://github.com/odoo/odoo)
- **语言**: Python
- **Stars**: 51,962
- **简介**: Odoo. Open Source Apps To Grow Your Business.

### AI 总结
**简介**: Odoo 是一套基于 Web 的开源商业应用套件，提供从 CRM 到 ERP 的全方位企业管理工具。

**核心功能**:
- 开源 CRM 客户关系管理
- 网站构建器与电子商务
- 仓库管理与项目管理系统
- 财务记账与会计
- 销售点（POS）系统
- 人力资源与市场营销
- 制造管理

**技术亮点**: 基于 Python 开发，采用模块化架构，各应用既可独立使用也可无缝集成形成完整 ERP 系统；提供标准化安装流程、在线学习资源及开发者教程。

---
## 10. [Open-LLM-VTuber/Open-LLM-VTuber](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber)
- **语言**: Python
- **Stars**: 8,988
- **简介**: Talk to any LLM with hands-free voice interaction, voice interruption, and Live2D taking face running locally across platforms

### AI 总结
**简介**: Open-LLM-VTuber 是一款支持实时语音交互、视觉感知与 Live2D 虚拟形象的跨平台 AI 伴侣，可完全离线运行。

**核心功能**:
- 支持与任意 LLM 进行免提语音对话与语音打断
- 集成 Live2D 虚拟角色，支持自定义外观与性格
- 提供 Web 版和桌面客户端，桌面版支持透明背景桌面宠物模式
- 支持 Windows、macOS、Linux 全平台运行
- 聊天记录持久化存储，可继续未完成的对话

**技术亮点**: 后端整合多种 LLM 推理、文本转语音与语音识别方案；支持 HTTPS 远程访问；采用 Python 开发，提供 Docker 部署支持。

---
