---
tags:
  - github-trending
  - daily
date: 2026-06-14
created: 2026-06-14T01:55:43.991Z
---

# 2026-06-14 GitHub Trending Top 10

## 1. [iptv-org/iptv](https://github.com/iptv-org/iptv)
- **语言**: TypeScript
- **Stars**: 119,160
- **简介**: Collection of publicly available IPTV channels from all over the world

### AI 总结
**简介**: 全球公开IPTV频道集合，提供可直接使用的直播流播放列表。

**核心功能**:
- 提供主播放列表（index.m3u）及按国家、类型分类的多个子列表
- 支持EPG电子节目指南下载（需配合iptv-org/epg工具）
- 提供API接口文档和频道数据库（iptv-org/database）

**技术亮点**: 基于TypeScript开发，通过GitHub Actions自动更新播放列表，采用开放式数据架构（数据库、API、播放列表分离）。

---
## 2. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: Shell
- **Stars**: 58,436
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 为 AI 编码代理提供生产级工程技能的规则集和工作流，确保代理在开发全周期中遵循资深工程师的最佳实践。

**核心功能**:
- 提供 7 个斜杠命令（`/spec`、`/plan`、`/build`、`/test`、`/review`、`/code-simplify`、`/ship`），覆盖从定义到发布的完整开发周期。
- 支持 24 个专业技能，如 API 设计、前端 UI 工程等，可根据上下文自动激活。
- 提供 `/build auto` 模式，一次审批后自主执行计划中的每个任务，但保留测试驱动和故障暂停机制。
- 兼容 Claude Code、Cursor、Gemini CLI 等主流 AI 编码工具，支持插件或规则配置方式集成。

**技术亮点**: 技能以纯 Markdown 格式编写，可被任何接受系统提示或指令文件的代理使用；通过目录结构（`/spec`、`/plan` 等）和命令行工具实现模块化、可复用的工程规范注入。

---
## 3. [chatwoot/chatwoot](https://github.com/chatwoot/chatwoot)
- **语言**: Ruby
- **Stars**: 30,874
- **简介**: Open-source live-chat, email support, omni-channel desk. An alternative to Intercom, Zendesk, Salesforce Service Cloud etc. 🔥💬

### AI 总结
**简介**: Chatwoot 是一个开源的、自托管的现代客户支持平台，可作为 Intercom、Zendesk 等商业工具的替代方案。

**核心功能**:
- **全渠道收件箱**: 整合网站实时聊天、邮件、Facebook、Instagram、WhatsApp、Telegram 等渠道的客户对话。
- **AI 智能助手 (Captain)**: 自动处理常见查询，减轻客服工作量，提供即时准确回复。
- **帮助中心门户**: 发布帮助文章和常见问题解答，支持客户自助服务。
- **协作与生产力工具**: 包括私密笔记、@提及、标签、快捷键、预设回复、自动分配、多语言支持、自定义视图、工作时间和自动回复等。
- **客户数据与细分**: 提供联系人管理、客户细分、主动营销活动、自定义属性和预聊天表单。
- **强大集成**: 支持 Slack、Dialogflow、Shopify、Google 翻译等第三方服务。

**技术亮点**: 基于 Ruby 语言开发，提供 Docker 镜像，支持一键部署到 Heroku 和 DigitalOcean 等云平台。

---
## 4. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 226,967
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为编码代理设计的完整软件开发方法论，构建在一组可组合的技能和初始指令之上，确保代理遵循规范流程。

**核心功能**:
- **设计驱动开发**：代理在编写代码前会先进行需求梳理和设计讨论，生成可读的规格文档。
- **分阶段工作流**：包括头脑风暴、使用 Git Worktrees 隔离工作区、编写详细计划以及子代理驱动开发，确保按计划执行。
- **自动化代理协作**：支持子代理独立处理任务并自动审查，可连续自主工作数小时。

**技术亮点**: 基于 Shell 脚本，支持多种编码代理平台（如 Claude Code、Codex CLI、Gemini CLI 等），通过插件市场分发，强调 TDD、YAGNI 和 DRY 原则。

---
## 5. [apple/container](https://github.com/apple/container)
- **语言**: Swift
- **Stars**: 36,333
- **简介**: A tool for creating and running Linux containers using lightweight virtual machines on a Mac. It is written in Swift, and optimized for Apple silicon.

### AI 总结
**简介**: `container` 是苹果官方推出的工具，用于在 Mac（Apple 芯片）上以轻量级虚拟机的方式创建和运行 Linux 容器。

**核心功能**:
- 创建并运行兼容 OCI 规范的 Linux 容器镜像
- 支持从标准容器仓库拉取和推送镜像
- 提供完整的命令行工具，支持容器的系统管理（启动、停止、卸载）
- 支持通过脚本进行升级、降级和卸载操作

**技术亮点**:
- 使用 Swift 语言编写，针对 Apple 芯片深度优化
- 底层依赖 [Containerization](https://github.com/apple/containerization) Swift 包，实现容器、镜像和进程管理
- 利用 macOS 26 新增的虚拟化和网络增强特性
- 全面兼容 OCI 镜像标准，可与其他 OCI 工具互操作

---
## 6. [music-assistant/server](https://github.com/music-assistant/server)
- **语言**: Python
- **Stars**: 2,009
- **简介**: Music Assistant is a free, opensource Media library manager that connects to your streaming services and a wide range of connected speakers. The server is the beating heart, the core of Music Assistant and must run on an always-on device like a Raspberry Pi, a NAS or an Intel NUC or alike.

### AI 总结
**简介**: Music Assistant 是一个免费开源的媒体库管理器，能够连接流媒体服务和多种智能音箱，其核心服务器需在 Raspberry Pi、NAS 或 Intel NUC 等常开设备上运行。

**核心功能**:
- 连接多个流媒体服务并统一管理媒体库
- 支持广泛的智能音箱设备
- 可与 Home Assistant 集成，实现自动化控制
- 提供 Docker 容器或 Home Assistant 插件两种部署方式

**技术亮点**: 基于 Python 开发，依赖 ffmpeg 和自定义二进制组件，无法作为独立 pypi 包运行，需通过 Docker 或 Home Assistant 插件部署。

---
## 7. [kenn-io/agentsview](https://github.com/kenn-io/agentsview)
- **语言**: Go
- **Stars**: 2,373
- **简介**: Local-first session intelligence and analytics for coding agents, supporting Claude Code, Codex, and more than 20 other agents. Also: 100x faster replacement for ccusage!

### AI 总结
**简介**: Agentsview 是一个本地优先的 AI 编程代理会话智能分析与成本追踪工具，支持 Claude Code、Codex 等 20 多种代理，可作为 ccusage 的 100 倍速替代品。

**核心功能**:
- 浏览、搜索和追踪所有 AI 编程代理的会话与成本
- 提供命令行和 Docker 部署方式，支持 SQLite 本地存储
- 支持远程访问（SSH 端口转发、反向代理、远程开发环境）
- 提供 PostgreSQL 和 DuckDB 数据库后端支持
- 支持 Quack 协议实现远程 DuckDB 数据访问

**技术亮点**:
- 采用 Go 语言开发，单二进制文件部署，无需账户
- 使用本地 SQLite 数据库索引会话数据，查询速度快
- 支持 DNS 重绑定攻击防护（Host 头验证）
- 提供 Docker Compose 生产部署示例

---
## 8. [LMCache/LMCache](https://github.com/LMCache/LMCache)
- **语言**: Python
- **Stars**: 8,900
- **简介**: LMCache: Supercharge Your LLM with the Fastest KV Cache Layer

### AI 总结
**简介**: LMCache 是一个高性能的 KV 缓存层，旨在通过加速大语言模型的 KV 缓存处理，显著提升 LLM 推理速度。

**核心功能**:
- 支持在单个 GPU 上部署 vLLM + LMCache，通过共享 KV 缓存降低长上下文问答的首 Token 延迟（TTFT）
- 支持跨多个 vLLM 实例共享前缀 KV 缓存，实现多实例间的缓存复用，显著减少响应延迟

**技术亮点**: 基于 Docker 容器化部署，支持 vLLM 框架集成，通过 LMCache 后端服务器实现分布式 KV 缓存共享，优化 GPU 内存利用率。

---
## 9. [microsoft/PowerToys](https://github.com/microsoft/PowerToys)
- **语言**: C
- **Stars**: 134,680
- **简介**: Microsoft PowerToys is a collection of utilities that supercharge productivity and customization on Windows

### AI 总结
**简介**: Microsoft PowerToys 是微软开发的 Windows 实用工具集，旨在通过一系列工具提升系统可定制性和日常操作效率。

**核心功能**:
- 高级粘贴：智能处理剪贴板内容格式
- 始终置顶：固定窗口置于其他窗口之上
- 唤醒：阻止电脑进入睡眠或待机模式
- 颜色选择器：从屏幕任意位置拾取颜色值
- FancyZones：自定义窗口布局管理器
- 文件资源管理器插件：增强文件预览和缩略图功能
- 键盘管理器：重映射按键和快捷键
- 鼠标实用工具：高亮、定位和跨设备控制鼠标
- PowerToys Run：快速启动应用和搜索文件
- 图像大小调整器：批量调整图片尺寸
- 批量重命名：基于规则的强大文件重命名工具

**技术亮点**: 基于 C#/.NET 开发，采用模块化架构，支持 Windows 原生集成（如任务栏、文件资源管理器），提供 30+ 独立可选的实用工具组件。

---
## 10. [andrewyng/aisuite](https://github.com/andrewyng/aisuite)
- **语言**: Python
- **Stars**: 14,130
- **简介**: Simple, unified interface to multiple Generative AI providers

### AI 总结
**简介**: aisuite 是一个轻量级 Python 库，提供统一的 LLM 调用接口，并内置了桌面 AI 助手 OpenCoworker。

**核心功能**:
- **统一聊天补全 API**：以 OpenAI 风格接口统一调用 OpenAI、Anthropic、Google 等多款模型，切换模型只需更改字符串。
- **Agents API**: 支持为模型赋予 Python 函数作为工具，实现多轮交互循环，并集成文件、Git、Shell 等现成工具包及 MCP 服务器。
- **OpenCoworker 桌面 AI 助手**: 基于 aisuite 构建的桌面应用，可聊天、深度研究、执行任务、创建文档、支持定时自动化。

**技术亮点**: 采用分层架构，底层为统一的聊天补全 API，上层为 Agents API，支持自带 API 密钥或使用 Ollama 本地运行。

---
