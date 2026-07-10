---
tags:
  - github-trending
  - daily
date: 2026-07-10
created: 2026-07-10T01:55:43.011Z
---

# 2026-07-10 GitHub Trending Top 10

## 1. [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)
- **语言**: TypeScript
- **Stars**: 19,149
- **简介**: AI-powered job application framework built on Claude Code. Fork it, fill in your profile, and let Claude evaluate jobs, tailor CVs, write cover letters, and prepare you for interviews.

### AI 总结
**简介**: AI 驱动的求职申请框架，基于 Claude Code，可自动评估职位、定制简历、撰写求职信和准备面试。

**核心功能**:
- 通过 `/setup` 命令填充个人资料（支持从文档文件夹、粘贴简历或面试问答三种方式）
- 通过 `/scrape` 命令自动搜索多个求职门户并去重，按匹配度排序展示职位
- 通过 `/apply <url>` 命令评估职位匹配度，生成定制化 LaTeX 简历和求职信，并支持审阅者代理进行优化
- 通过 `/rank` 命令对批量职位进行评分，生成排名短名单
- 内置求职最佳实践，包括结构化评估标准、前瞻性求职信框架和可选薪资基准

**技术亮点**: 基于 Claude Code CLI 和 Python 3.10+，使用 Bun 管理 CLI 工具，LaTeX (lualatex/xelatex) 生成简历和求职信，支持丹麦市场求职门户（Jobindex、Jobnet 等），架构设计为语言和国家无关，可轻松替换为其他地区求职平台。

---
## 2. [SmartlyDressedGames/U3-SDK](https://github.com/SmartlyDressedGames/U3-SDK)
- **语言**: C#
- **Stars**: 2,057
- **简介**: Source code for Unturned, a free open-world zombie survival sandbox game.

### AI 总结
**简介**: Unturned 是一款免费的开源开放世界僵尸生存沙盒游戏，其源代码托管在 SmartlyDressedGames/U3-SDK 仓库中，采用 C# 语言开发。  
**核心功能**:  
- 提供完整的游戏源代码，支持玩家和开发者自由修改与扩展  
- 集成 Unity 2022.3.62f3 引擎，实现跨平台运行与编辑  
- 支持从本地安装的 Steam 版 Unturned 加载二进制文件和模组资源  
- 提供 `Assets/GameStartup.unity` 场景，可直接在 Unity 编辑器中运行调试  
**技术亮点**:  
- 基于 Unity 引擎开发，结合 Visual Studio 的 **Game development with Unity** + **.NET desktop development** 工作负载进行代码修改  
- 依赖 Steam 运行库，实现游戏内容与模组的动态加载  
- 配套官方文档与教程（如热追踪导弹代码演示），降低二次开发门槛

---
## 3. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 75,929
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 一套为 AI 编码代理打造的、封装了高级工程师最佳实践的“技能”，用于指导代理在开发各阶段遵循规范的工作流和质量门禁。

**核心功能**:
- **8 个斜杠命令**: 映射完整开发生命周期，包括 `/spec`（定义）、`/plan`（规划）、`/build`（构建）、`/test`（测试）、`/review`（审查）、`/webperf`（性能审计）、`/code-simplify`（代码简化）和 `/ship`（发布）。
- **自动技能激活**: 根据编码上下文（如设计 API、构建 UI）自动启用相应技能。
- **一键自动化**: `/build auto` 命令可自动生成计划并逐步实现所有任务，仅在失败或风险步骤时暂停。
- **跨平台兼容**: 支持 Claude Code、Cursor、Gemini CLI、Windsurf 等 70+ 种 AI 编码代理。

**技术亮点**: 基于 JavaScript 开发，通过 `npx skills add` 或原生插件方式集成，采用“技能”即 `SKILL.md` 文件的模块化设计，将工程规范封装为可复用的代理指令。

---
## 4. [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md)
- **语言**: Unknown
- **Stars**: 99,765
- **简介**: A collection of DESIGN.md files analysis by popular brand design systems. Drop one into your project and let coding agents generate a matching UI.

### AI 总结
**简介**: 一个收集流行品牌设计系统 `DESIGN.md` 文件的资源库，开发者可将其放入项目，让 AI 编码代理生成匹配的 UI。

**核心功能**:
- 提供从真实网站提取的、可直接使用的 `DESIGN.md` 文件集合
- 支持开发者复制文件到项目根目录，AI 代理即可理解 UI 设计语言
- 允许用户请求特定网站的 `DESIGN.md` 文件

**技术亮点**:
- 基于 Google Stitch 提出的 `DESIGN.md` 概念，使用纯文本 Markdown 格式
- 包含分析过的设计模式、设计令牌和规则，用于生成高质量 UI
- 无需 Figma 导出、JSON 模式或特殊工具，即插即用

---
## 5. [iOfficeAI/OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)
- **语言**: C#
- **Stars**: 13,511
- **简介**: OfficeCLI is the first and best Office suite purpose-built for AI agents to read, edit, and automate Word, Excel, and PowerPoint files. Free, open-source, single binary, no Office installation required.

### AI 总结
**简介**: OfficeCLI 是全球首个专为 AI 智能体设计的 Office 套件，通过命令行让 AI 完全控制 Word、Excel 和 PowerPoint 文件。

**核心功能**:
- 支持 AI 智能体在单行代码内读取、编辑和自动化 Office 文档
- 内置 HTML 渲染引擎，可将 .docx/.xlsx/.pptx 文件渲染为 HTML 或 PNG，实现“渲染→查看→修复”闭环
- 提供实时预览功能，通过 `watch` 命令在浏览器中即时查看文档变更
- 支持自然语言创建和编辑文档（通过 AionUi 桌面应用）

**技术亮点**:
- 采用 C# 开发，单二进制文件，无需安装 Office 或依赖
- 跨平台支持（macOS/Linux/Windows），提供 brew、npm 等多种安装方式
- 自动检测并安装到 Claude Code、Cursor、Windsurf 等主流 AI 编码工具中

---
## 6. [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP)
- **语言**: TypeScript
- **Stars**: 6,586
- **简介**: This is MCP server for Claude that gives it terminal control, file system search and diff file editing capabilities

### AI 总结
**简介**: Desktop Commander MCP 是一个为 Claude 等 AI 助手提供终端控制、文件系统搜索和文件差异编辑能力的 MCP 服务器。

**核心功能**:
- **远程 AI 控制**: 支持从 ChatGPT、Claude Web 等远程控制桌面环境
- **增强终端命令**: 支持交互式进程控制、命令超时、后台执行和会话管理
- **文件操作与编辑**: 支持读写文本、Excel、PDF、DOCX 文件，并提供代码搜索替换和差异编辑能力
- **内存代码执行**: 直接在内存中运行 Python、Node.js、R 代码，无需保存文件
- **文件预览 UI**: 在 Claude Desktop 中提供 Markdown 渲染、内嵌图片、展开式内容和内置编辑器的文件预览界面
- **进程管理**: 支持列出和终止进程，管理 SSH、数据库等长时间运行的进程

**技术亮点**:
- 基于 TypeScript 开发，构建于 MCP Filesystem Server 之上
- 支持远程 MCP 协议，可与多种 AI 服务集成
- 提供进程输出分页功能，防止上下文溢出
- 支持负偏移文件读取（类似 Unix tail 命令）

---
## 7. [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks)
- **语言**: Jupyter Notebook
- **Stars**: 47,184
- **简介**: A collection of notebooks/recipes showcasing some fun and effective ways of using Claude.

### AI 总结
**简介**: 这是一个为开发者提供的 Claude API 应用示例集合，包含可直接复用的代码和指南。

**核心功能**:
- **基础能力演示**：提供文本分类、检索增强生成（RAG）、摘要等核心功能的实现代码
- **工具集成**：展示如何将 Claude 与外部工具结合，如客户服务代理、计算器、SQL 查询
- **第三方集成**：支持与 Pinecone 向量数据库、Wikipedia、网页内容等外部数据源对接
- **多模态能力**：包含图像识别、图表解读、表单内容提取以及通过 Stable Diffusion 生成图像的示例
- **高级技巧**：涵盖子代理模式、PDF 上传处理、自动化评估和 JSON 模式输出

**技术亮点**: 使用 Jupyter Notebook 编写，以 Python 为主，但概念可适配其他语言。提供从基础 API 调用到复杂场景（如多模态、RAG、工具调用）的完整代码示例。

---
## 8. [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi)
- **语言**: Go
- **Stars**: 19,434
- **简介**: Fully autonomous AI Agents system capable of performing complex penetration testing tasks

### AI 总结
**简介**: PentAGI 是一个基于 AI 的全自动渗透测试系统，能在隔离的 Docker 环境中自主执行复杂的安全测试任务。

**核心功能**:
- 完全自主的 AI 代理，自动规划并执行渗透测试步骤
- 内置 20+ 专业安全工具（如 nmap、metasploit、sqlmap）
- 智能长期记忆系统，存储研究成果和成功方法
- 知识图谱集成（Graphiti + Neo4j），实现语义关系追踪
- 网络情报收集，通过内置浏览器和多种外部搜索 API
- 专业团队分工，支持研究、开发和基础设施任务的 AI 代理委派
- 详细漏洞报告生成，附带利用指南
- 实时监控与日志记录（Grafana/Prometheus）

**技术亮点**: 使用 Go 语言开发，基于 Docker 沙箱隔离运行，支持 PostgreSQL + pgvector 持久化存储，集成多种 LLM 提供商（Ollama、OpenAI、Anthropic、Gemini 等），提供 REST 和 GraphQL API，支持 OAuth 认证和 Langfuse 可观测性集成。

---
## 9. [unclecode/crawl4ai](https://github.com/unclecode/crawl4ai)
- **语言**: Python
- **Stars**: 71,857
- **简介**: 🚀🤖 Crawl4AI: Open-source LLM Friendly Web Crawler & Scraper. Don't be shy, join here: https://discord.gg/jP8KfhDhyN

### AI 总结
**简介**: Crawl4AI 是一个开源、对 LLM 友好的网络爬虫和抓取工具，能将网页内容转换为干净的 Markdown 格式，供 RAG、AI Agent 和数据管道使用。

**核心功能**:
- **LLM 就绪输出**: 生成带有标题、表格、代码和引用提示的智能 Markdown。
- **高速异步爬取**: 内置异步浏览器池、缓存机制，实现高效抓取。
- **全面控制**: 支持会话管理、代理、Cookie、用户脚本和钩子。
- **自适应智能**: 学习网站模式，仅抓取关键内容。
- **灵活部署**: 无密钥依赖，支持 CLI、Docker 和云环境。

**技术亮点**: 基于 Python 开发，支持 Docker 部署，集成了异步浏览器池和缓存机制，提供安全加固的 API 服务器（默认启用认证）。

---
## 10. [imthenachoman/How-To-Secure-A-Linux-Server](https://github.com/imthenachoman/How-To-Secure-A-Linux-Server)
- **语言**: Unknown
- **Stars**: 29,105
- **简介**: An evolving how-to guide for securing a Linux server.

### AI 总结
**简介**: 一份持续更新的 Linux 服务器安全加固指南，旨在帮助用户提升服务器安全性并理解安全原理。

**核心功能**:
- 覆盖 SSH 服务器安全配置（密钥认证、2FA/MFA、限制访问组等）
- 基础安全措施（sudo/su 权限控制、FireJail 沙箱、密码策略、自动安全更新）
- 网络安全防护（UFW 防火墙、PSAD 入侵检测、Fail2Ban/CrowdSec 应用防护）
- 系统审计与监控（AIDE 文件完整性、ClamAV 反病毒、Rkhunter/Chrootkit 根kit检测、Lynis 安全审计、OSSEC 主机入侵检测）
- 提供 Ansible Playbook 自动化部署支持

**技术亮点**: 采用模块化结构，从 SSH 到网络到审计逐层深入；支持 UFW/iptables 防火墙、Fail2Ban/CrowdSec 双重应用防护；集成多种安全审计工具（Lynis、OSSEC）和根kit检测工具；提供配套 Ansible 自动化方案。

---
