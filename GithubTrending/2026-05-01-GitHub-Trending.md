---
tags:
  - github-trending
  - daily
date: 2026-05-01
created: 2026-05-01T01:55:45.916Z
---

# 2026-05-01 GitHub Trending Top 10

## 1. [warpdotdev/warp](https://github.com/warpdotdev/warp)
- **语言**: Rust
- **Stars**: 49,315
- **简介**: Warp is an agentic development environment, born out of the terminal.

### AI 总结
**简介**: Warp 是一个基于终端、面向智能代理的现代化开发环境，旨在解决终端陈旧和代理工具难以扩展的问题。  
**核心功能**:  
- 提供现代化的终端界面，集成代码编辑功能，支持 AI 代理（如内置的 Oz）和第三方 CLI 代理（如 Claude Code、Codex、Gemini CLI）。  
- Oz 是一个云代理编排平台，可并行运行无限个可编程、可审计、可控制的代理，用于自动化任务和构建复杂工作流。  
- 支持通过主题、工作流等社区扩展点进行定制和协作。  
**技术亮点**: 使用 Rust 开发，计划开源 Rust UI 框架和客户端代码；依赖 Tokio、Alacritty、Hyper 等高性能开源库。

---
## 2. [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)
- **语言**: Python
- **Stars**: 57,819
- **简介**: TradingAgents: Multi-Agents LLM Financial Trading Framework

### AI 总结
**简介**: TradingAgents 是一个基于多智能体 LLM 的金融交易框架，模拟真实交易公司中不同角色的协作，进行市场评估和交易决策。

**核心功能**:
- 部署多个专业 LLM 智能体（基本面分析师、情绪专家、技术分析师、交易员、风险管理团队等）
- 智能体通过动态讨论协同评估市场状况并制定最优交易策略
- 支持多种 LLM 提供商（GPT-5.x、Gemini 3.x、Claude 4.x、DeepSeek、Qwen 等）
- 提供结构化输出智能体、LangGraph 检查点恢复、持久化决策日志
- 支持回测、Docker 部署、多语言界面

**技术亮点**:
- 多智能体协作架构，模拟真实交易公司角色分工
- 支持结构化输出（Research Manager、Trader、Portfolio Manager）
- 集成 LangGraph 工作流管理，支持断点恢复
- 统一模型目录，兼容多种主流 LLM 提供商
- 基于 Python 开发，提供 CLI 和包使用方式

---
## 3. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 49,600
- **简介**: Skills for Real Engineers. Straight from my .claude directory.

### AI 总结
**简介**: 这是一套由资深工程师 Matt Pocock 打造的开源 AI 代理技能集，旨在通过小巧、可组合、易定制的技能，解决开发者在实际编码中遇到的常见问题，提升编码效率与质量。

**核心功能**:
- **`/grill-me` 与 `/grill-with-docs` 技能**: 在编码开始前，引导 AI 代理向开发者提出详细问题，进行“拷问”以对齐需求，避免开发结果与预期不符。
- **建立共享语言**: 通过 `/grill-with-docs` 帮助团队构建项目专属的 `CONTEXT.md` 文件，让 AI 理解项目术语，减少冗余沟通，使变量、函数命名更一致。
- **一键快速安装**: 提供 `npx skills@latest add` 命令，30 秒内即可选择并安装所需技能到指定编码代理。
- **集成项目管理**: 安装后支持选择 GitHub、Linear 或本地文件作为问题追踪器，并支持通过标签进行任务分类（`/triage`）。

**技术亮点**: 基于 Shell 脚本构建，强调技能的小型化、可组合性和易适应性，可与任何 AI 模型配合使用，旨在让开发者保持对开发过程的控制权。

---
## 4. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 174,622
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套为编码代理设计的完整软件开发方法论，基于可组合的技能和初始指令，确保代理遵循正确的开发流程。

**核心功能**:
- **头脑风暴**：在编码前通过提问和探索细化需求，生成设计文档
- **Git 工作树管理**：创建隔离工作区，自动设置项目并验证测试基线
- **编写计划**：将设计拆分为 2-5 分钟的小任务，包含文件路径、代码和验证步骤
- **子代理驱动开发**：为每个任务分配独立子代理，执行规范与代码质量双重审查
- **测试驱动开发**：强制 RED-GREEN-REFACTOR 循环，确保先写测试再编码
- **代码审查**：在任务间自动检查代码与计划一致性，阻止严重问题
- **分支完成**：任务完成后自动验证测试，提供合并/PR/保留/丢弃选项

**技术亮点**: 基于 Shell 脚本实现，采用子代理架构实现自主开发，支持 Claude Code、OpenAI Codex、Cursor、GitHub Copilot 等多种编码代理平台。

---
## 5. [lukilabs/craft-agents-oss](https://github.com/lukilabs/craft-agents-oss)
- **语言**: TypeScript
- **Stars**: 5,582
- **简介**: 

### AI 总结
**简介**: Craft Agents 是一个基于 Agent Native 理念构建的开源桌面工具，旨在提供更直观、非 CLI 的多任务处理方式，让用户通过自然语言与任意 API、MCP 服务器或本地资源无缝交互。

**核心功能**:
- **即时连接任意资源**: 通过自然语言指令（如"添加 Linear 作为来源"）自动发现、配置并连接公开 API、MCP 服务器、本地文件系统或自定义 OpenAPI 接口，无需手动编辑配置文件。
- **多会话与工作流管理**: 支持桌面端多会话收件箱，包含状态管理（待办/进行中/完成）、标记、后台任务进度追踪及动态状态系统。
- **多模型与多提供商支持**: 可同时连接 Anthropic、Google AI Studio、ChatGPT Plus、GitHub Copilot 等多个 LLM 提供商，并按工作区设置默认模型。
- **技能与自动化系统**: 用户可通过自然语言描述创建或导入自定义技能（Agent 指令），并支持事件驱动的自动化流程。
- **丰富的协作与展示功能**: 支持流式响应、实时工具可视化、多文件 diff 对比、文件拖拽附件（图片/PDF/Office 文档自动转换）及主题定制。

**技术亮点**:
- **TypeScript 构建**: 基于 Electron 桌面框架，使用 Bun 包管理器，融合 Claude Agent SDK 与 Pi SDK。
- **Agent Native 架构**: 高度可定制，支持通过自然语言直接修改自身行为（项目自身即用 Craft Agents 构建），无需代码编辑器。
- **动态 MCP 与 REST 集成**: 支持 Stdio 本地子进程 MCP、远程 MCP 服务器，以及通过 OpenAPI 规范或截图直接接入自定义 REST API。
- **三级权限模式**: 提供探索、请求编辑、自动三种权限模式，并支持自定义规则，确保安全可控。

---
## 6. [public-apis/public-apis](https://github.com/public-apis/public-apis)
- **语言**: Python
- **Stars**: 429,553
- **简介**: A collective list of free APIs

### AI 总结
**简介**: 一个由社区维护的免费公共 API 集合，涵盖多个领域，供开发者用于自己的产品。

**核心功能**:
- 提供大量可免费使用的公共 API 列表
- 按领域分类，方便开发者查找
- 包含 APILayer 提供的 API 示例（如 IP 定位、天气、股票市场数据等）

**技术亮点**: 基于 Python 项目，社区驱动维护，支持通过 Postman 直接调用 API 进行测试。

---
## 7. [1jehuang/jcode](https://github.com/1jehuang/jcode)
- **语言**: Rust
- **Stars**: 1,905
- **简介**: Coding Agent Harness

### AI 总结
**简介**: jcode 是一个基于 Rust 开发的新一代编码代理工具，专为多会话工作流、无限可定制性和高性能而设计。

**核心功能**:
- 支持多会话工作流，可同时运行多个活动会话
- 提供高效的本地嵌入功能，支持灵活开关
- 跨平台支持（Linux、macOS、Windows）
- 提供一键安装脚本，支持多种安装方式

**技术亮点**: 采用 Rust 语言开发，在性能和资源效率上经过极致优化，RAM 占用显著低于同类工具（如 Claude Code、Cursor Agent、GitHub Copilot CLI 等），单会话内存最低仅 27.8 MB，10 个会话时仅 117 MB。

---
## 8. [soxoj/maigret](https://github.com/soxoj/maigret)
- **语言**: Python
- **Stars**: 20,860
- **简介**: 🕵️‍♂️ Collect a dossier on a person by username from 3000+ sites

### AI 总结
**简介**: Maigret 是一款基于用户名的开源情报收集工具，可自动在 3000 多个网站上搜索并汇总用户公开信息，无需 API 密钥。

**核心功能**:
- 支持 3000+ 网站（默认扫描 500 个高流量站点，支持全量扫描和按标签/国家过滤）
- 从个人资料页面和 API 中提取账号关联信息（如其他用户名、社交链接）
- 支持递归搜索：利用已发现的用户名和 ID 进行深层挖掘
- 提供网页界面，支持以图谱形式浏览结果并下载多种格式报告
- 自动检测并部分绕过封锁、审查和 CAPTCHA
- 支持 Tor 和 I2P 网站，可检查域名
- 可作为 Python 库嵌入项目中使用

**技术亮点**: 纯 Python 实现，依赖自动更新的站点数据库（每日从 GitHub 拉取），支持离线回退；集成 `socid_extractor` 库提取结构化数据；通过标签系统实现灵活的站点分类筛选。

---
## 9. [HunxByts/GhostTrack](https://github.com/HunxByts/GhostTrack)
- **语言**: Python
- **Stars**: 12,185
- **简介**: Useful tool to track location or mobile number

### AI 总结
**简介**: GhostTrack 是一个用于追踪位置和手机号的开源信息收集工具，基于 Python 开发。

**核心功能**:
- IP 追踪：可获取目标 IP 地址相关信息，支持与 Seeker 工具配合使用
- 手机号追踪：输入目标手机号，查询关联信息
- 用户名追踪：通过社交媒体用户名查找目标相关信息

**技术亮点**: 基于 Python 3 开发，支持 Linux (Debian) 和 Termux 平台，使用命令行交互界面

---
## 10. [iamgio/quarkdown](https://github.com/iamgio/quarkdown)
- **语言**: Kotlin
- **Stars**: 13,091
- **简介**: 🪐 Markdown with superpowers: from ideas to papers, presentations, websites, books, and knowledge bases.

### AI 总结
**简介**: Quarkdown 是一个基于 Markdown 的现代排版系统，支持将同一项目编译为论文、演示文稿、网站、书籍或知识库等多种输出格式。

**核心功能**:
- 多目标输出：从同一 Markdown 源文件编译为打印书籍、学术论文、知识库或交互式演示文稿
- 增强的 Markdown 语法（Quarkdown Flavor）：在 CommonMark/GFM 基础上扩展了函数调用、条件语句、循环等图灵完备功能
- 内置标准库：提供布局构建器、I/O、数学公式支持等开箱即用的功能
- 自定义函数与变量：允许在 Markdown 中定义函数和变量，支持创建可复用的库
- 实时预览与 VS Code 扩展：提供快速编译和编辑器集成支持

**技术亮点**: 使用 Kotlin 开发，基于图灵完备的 Markdown 扩展语法，支持动态内容生成和复杂的文档编排。

---
