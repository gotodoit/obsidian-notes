---
tags:
  - github-trending
  - daily
date: 2026-05-04
created: 2026-05-04T01:55:43.717Z
---

# 2026-05-04 GitHub Trending Top 9

## 1. [ruvnet/ruflo](https://github.com/ruvnet/ruflo)
- **语言**: TypeScript
- **Stars**: 39,086
- **简介**: 🌊 The leading agent orchestration platform for Claude. Deploy intelligent multi-agent swarms, coordinate autonomous workflows, and build conversational AI systems. Features enterprise-grade architecture, self-learning swarm intelligence, RAG integration, and native Claude Code / Codex Integration

### AI 总结
**简介**: Ruflo 是一个为 Claude Code 设计的领先多智能体编排平台，支持部署、协调和构建智能体集群，具备自学习、RAG 集成和企业级架构。

**核心功能**:
- 编排 100+ 专业 AI 智能体，支持跨机器、团队和信任边界的协作
- 智能体自组织成集群，具备自学习和跨会话记忆能力
- 提供联邦通信机制，允许不同机器上的智能体安全协作而不泄露数据
- 支持 RAG 集成、知识图谱构建和向量数据库，用于智能检索和记忆管理
- 提供 32 个插件，涵盖编排、记忆、智能、代码质量、安全合规等模块

**技术亮点**:
- 基于 TypeScript 开发，支持 WASM 内核（Rust 实现策略引擎、嵌入和证明系统）
- 原生集成 Claude Code / Codex，通过插件系统扩展技能、命令和 MCP 工具
- 采用自学习/自优化架构，包含路由、集群、智能体、记忆和 LLM 提供者循环
- 支持 GPU 加速搜索（ruvector）和混合搜索（Graph RAG）

---
## 2. [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)
- **语言**: Python
- **Stars**: 65,372
- **简介**: TradingAgents: Multi-Agents LLM Financial Trading Framework

### AI 总结
**简介**: TradingAgents 是一个基于多智能体 LLM 的金融交易框架，通过模拟真实交易公司的协作模式，由多个专业 AI 代理共同分析市场并制定交易策略。

**核心功能**:
- 多智能体协作：部署基本面分析师、情绪专家、技术分析师、交易员和风险管理团队等角色，动态讨论并优化交易决策
- 支持多种 LLM 提供商：兼容 GPT-5.x、Gemini 3.x、Claude 4.x、Grok 4.x 等主流模型
- 结构化输出与持久化：代理输出结构化数据，支持 LangGraph 检查点恢复和决策日志记录
- 回测与日期保真：提供回测功能并确保日期准确性
- 跨平台支持：包含 Docker 部署、Windows UTF-8 编码修复及代理支持

**技术亮点**:
- 基于 Python 构建，采用多智能体系统架构
- 集成 LangGraph 实现工作流管理与检查点恢复
- 统一模型目录，支持多提供商、多语言（含中文）及代理配置
- 提供 CLI 和 Python 包两种使用方式，便于研究和集成

---
## 3. [soxoj/maigret](https://github.com/soxoj/maigret)
- **语言**: Python
- **Stars**: 23,855
- **简介**: 🕵️‍♂️ Collect a dossier on a person by username from 3000+ sites

### AI 总结
**简介**: Maigret 是一个强大的 Python 工具，仅通过用户名即可在 3000 多个网站上搜集某人的公开信息，无需 API 密钥。

**核心功能**:
- **海量网站支持**: 默认检查 500 个高流量网站，可通过 `-a` 参数扫描全部 3000+ 站点，或使用 `--tags` 按类别/国家筛选。
- **信息提取**: 从用户主页和网站 API 中提取账号所有者的所有可用信息，包括其他账号链接。
- **递归搜索**: 利用发现的用户名和其他 ID 进行递归搜索，深度挖掘关联信息。
- **报告导出**: 支持生成 PDF、HTML、XMind 等多种格式的报告。
- **反封锁机制**: 能够检测并部分绕过网站封锁、审查和验证码。
- **Python 集成**: 可作为库导入到 Python 项目中，进行程序化搜索。
- **Tor/I2P 支持**: 支持检查 Tor 和 I2P 网络上的网站和域名。

**技术亮点**: 基于 Python 3.10+ 开发，采用自动更新的站点数据库，支持离线回退，并提供 Web 界面用于图形化浏览和报告下载。

---
## 4. [Hmbown/DeepSeek-TUI](https://github.com/Hmbown/DeepSeek-TUI)
- **语言**: Rust
- **Stars**: 2,204
- **简介**: Coding agent for DeepSeek models that runs in your terminal

### AI 总结
**简介**: 一个专为 DeepSeek 模型设计的终端原生编码助手，利用其超长上下文和前缀缓存，提供强大的代码操作能力。
**核心功能**:
- **原生 RLM**: 并行分发多个廉价模型进行批量分析或并行推理。
- **思维链流式显示**: 实时展示模型的推理过程。
- **完整工具套件**: 包括文件操作、Shell 执行、Git 管理、网络搜索、子代理和 MCP 服务器。
- **超大上下文管理**: 支持 1M token 上下文，并具备智能压缩功能。
- **三种交互模式**: 计划（只读探索）、代理（交互式审批）、YOLO（全自动）。
- **会话保存与恢复**: 支持长时间会话的断点续传。
- **工作区回滚**: 通过侧边 Git 实现操作前后的快照回滚。
- **HTTP/SSE 运行时 API**: 支持无头代理工作流。
- **实时成本追踪**: 监控每次交互的 token 使用和成本。
**技术亮点**: 采用 **Rust** 语言开发，单二进制文件部署，无需 Node/Python 运行时。架构遵循 **dispatcher → TUI → engine → tools** 模式，集成了 **ratatui** 界面、异步引擎、类型化工具注册中心和 LSP 诊断子系统。

---
## 5. [AIDC-AI/Pixelle-Video](https://github.com/AIDC-AI/Pixelle-Video)
- **语言**: Python
- **Stars**: 10,022
- **简介**: 🚀 AI 全自动短视频引擎 | AI Fully Automated Short Video Engine

### AI 总结
**简介**: Pixelle-Video 是一个AI全自动短视频引擎，只需输入主题即可自动完成文案、配图、配音、配乐和视频合成。

**核心功能**:
- 全自动生成：输入主题，自动完成从文案到视频的完整流程
- AI智能文案：根据主题自动创作解说词
- AI生成配图/视频：每句话自动配上AI插图或动态视频内容
- AI语音合成：支持Edge-TTS、Index-TTS等多种TTS方案
- 背景音乐：支持添加BGM增强氛围
- 多种视觉风格和尺寸：支持竖屏、横屏，多种模板可选
- 扩展模块：支持数字人口播、图生视频、动作迁移
- 自定义素材：支持用户上传照片/视频，AI分析生成脚本

**技术亮点**:
- 基于ComfyUI架构，支持原子能力灵活组合（如替换生图模型为FLUX、替换TTS为ChatTTS等）
- 支持多种AI模型：GPT、通义千问、DeepSeek、Ollama等
- 模块化设计，每个环节均支持灵活定制
- 支持RunningHub并行处理和API配置

---
## 6. [browserbase/skills](https://github.com/browserbase/skills)
- **语言**: JavaScript
- **Stars**: 1,839
- **简介**: Claude Agent SDK with a web browsing tool

### AI 总结
**简介**: 为 Claude Code 提供网页浏览和 Browserbase 平台自动化操作能力的技能插件集合。

**核心功能**:
- 通过 CLI 命令自动化浏览器交互，支持远程 Browserbase 会话、反爬虫隐身、验证码解决和住宅代理
- 使用官方 `bb` CLI 管理 Browserbase 平台资源（会话、项目、上下文等）
- 部署无服务器浏览器自动化到 Browserbase 云端
- 诊断和修复失败的浏览器自动化（检测反爬虫、选择器、时序、认证等）
- 捕获完整的 DevTools 协议跟踪并分页搜索
- 显示使用统计、会话分析和成本预测仪表盘
- 同步本地 Chrome 的 cookies 到 Browserbase 持久上下文
- 免浏览器抓取静态页面的 HTML 或 JSON
- 免浏览器搜索网页并返回结构化结果
- AI 驱动的对抗性 UI 测试，基于 git 差异或全应用探索

**技术亮点**: 基于 JavaScript 开发，与 Claude Code 深度集成，结合 Browserbase 平台和 Stagehand 框架，支持本地和远程浏览器会话管理。

---
## 7. [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp)
- **语言**: TypeScript
- **Stars**: 19,540
- **简介**: A MCP for Claude Desktop / Claude Code / Windsurf / Cursor to build n8n workflows for you

### AI 总结
**简介**: n8n-MCP 是一个基于 TypeScript 的 MCP 服务器，为 AI 助手（如 Claude）提供全面的 n8n 节点文档、属性和操作访问能力，使其能辅助构建 n8n 工作流。

**核心功能**:
- **全面节点覆盖**: 提供 1,650 个 n8n 节点（820 个核心 + 830 个社区节点）的结构化访问。
- **深度文档集成**: 覆盖 87% 的官方文档，包括节点属性（99%）、操作（63.6%）和 AI 工具（265 种变体）。
- **模板与示例库**: 包含 2,352 个工作流模板和 156 个从流行模板中提取的排名配置。
- **多 IDE 集成**: 支持 Claude Code、VS Code、Cursor、Windsurf 等主流 AI 开发环境。
- **灵活部署**: 提供托管服务（免费层每日 100 次调用）和自托管选项（npx、Docker、Railway）。

**技术亮点**: 采用 Model Context Protocol (MCP) 标准，作为 AI 和 n8n 自动化平台之间的桥梁；通过结构化数据访问（节点、属性、操作、模板）实现高覆盖率（99.96% AI 元数据覆盖）；提供安全警告和开发/生产环境分离建议。

---
## 8. [1jehuang/jcode](https://github.com/1jehuang/jcode)
- **语言**: Rust
- **Stars**: 3,450
- **简介**: Coding Agent Harness

### AI 总结
**简介**: jcode 是一个用 Rust 构建的下一代编码代理框架，专注于多会话工作流、无限可定制性和高性能。

**核心功能**:
- 支持多会话并行工作流，提升编码效率
- 提供记忆演示功能，支持上下文感知
- 跨平台支持（Linux、macOS、Windows）
- 一键安装脚本，支持多种安装方式

**技术亮点**:
- 采用 Rust 语言开发，极致优化性能与资源效率
- 单会话内存占用仅 27.8 MB（关闭本地嵌入），远低于同类工具（如 Claude Code 占用 386.6 MB）
- 十会话场景下内存仅 260.8 MB，比同类工具节省 2-7 倍资源

---
## 9. [openwrt/openwrt](https://github.com/openwrt/openwrt)
- **语言**: C
- **Stars**: 26,626
- **简介**: This repository is a mirror of https://git.openwrt.org/openwrt/openwrt.git It is for reference only and is not active for check-ins. We will continue to accept Pull Requests here. They will be merged via staging trees then into openwrt.git.

### AI 总结
**简介**: OpenWrt 是一个面向嵌入式设备的 Linux 操作系统，提供可写文件系统和包管理，支持高度自定义。

**核心功能**:
- 提供完整可写文件系统和包管理，允许用户自由选择应用和配置
- 支持多种架构的固件下载，并提供固件选择器帮助用户快速迁移
- 提供开发框架，允许开发者在不构建完整固件的情况下构建应用
- 支持通过 `opkg` 包管理器安装社区维护的各类包

**技术亮点**:
- 基于 C 语言开发，使用 GNU/Linux、BSD 或 macOS 系统构建
- 提供交叉编译工具链，支持自定义固件构建（`make menuconfig` + `make`）
- 采用模块化架构，通过子仓库管理 LuCI 界面、路由、视频等不同类别包

---
