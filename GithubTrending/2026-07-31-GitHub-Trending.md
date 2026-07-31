---
tags:
  - github-trending
  - daily
date: 2026-07-31
created: 2026-07-31T01:55:44.764Z
---

# 2026-07-31 GitHub Trending Top 10

## 1. [huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech)
- **语言**: Python
- **Stars**: 8,930
- **简介**: Build local voice agents with open-source models

### AI 总结
**简介**: 一个基于开源模型构建本地语音代理的低延迟、模块化语音流水线工具，提供与 OpenAI Realtime 兼容的 WebSocket API。

**核心功能**:
- 完整的语音代理流水线：VAD → STT → LLM → TTS，每个组件均可替换
- 提供 OpenAI Realtime 兼容的 WebSocket 服务端，任何兼容客户端可直接连接
- 支持多种 LLM 后端：云端托管服务、HF Inference Providers、本地 vLLM 或 llama.cpp 服务器
- 支持流式文本和工具调用输出，以及实时部分转写
- 支持多语言和多种运行模式（本地音频、服务器模式）
- 简单的 CLI 启动方式，支持通过命令行参数灵活配置各组件

**技术亮点**:
- 四组件级联架构，每个组件独立线程运行并通过队列连接，实现低延迟
- 默认使用 Silero VAD v5、Parakeet TDT (STT)、Qwen3-TTS (语音合成)，支持 GGML 和 Apple Silicon 的 mlx-audio 后端
- 已在生产环境中作为数千台 Reachy Mini 机器人的对话后端运行
- 支持完全本地部署的开源技术栈，无需依赖云端服务
- 平台相关的依赖通过 pyproject.toml 自动解析（macOS/非 macOS）

---
## 2. [microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners)
- **语言**: Jupyter Notebook
- **Stars**: 54,043
- **简介**: 12 Weeks, 24 Lessons, AI for All!

### AI 总结
**简介**: 微软推出的12周、24课时的AI入门课程，面向初学者的免费教育项目，涵盖AI基础理论与实践。

**核心功能**:
- 12周24课时的结构化AI学习路径，包含实战练习、测验和实验
- 覆盖TensorFlow、PyTorch等主流AI工具，并涉及AI伦理议题
- 提供50+种语言的多语言支持，包括中文（简体/繁体）等
- 支持Binder在线运行，无需本地环境即可体验课程代码
- 社区活跃，支持PR贡献和Discord/Gitter讨论

**技术亮点**: 基于Jupyter Notebook的交互式教学，采用Sketchnote视觉笔记辅助理解，并支持通过sparse checkout方式精简克隆（避免多语言翻译文件占用过大存储空间）。

---
## 3. [paperswithbacktest/awesome-systematic-trading](https://github.com/paperswithbacktest/awesome-systematic-trading)
- **语言**: Python
- **Stars**: 11,088
- **简介**: A curated list of awesome libraries, packages, strategies, books, blogs, tutorials for systematic trading.

### AI 总结
**简介**: 一个精选的系统化交易（量化交易）资源列表，涵盖策略开发与运行所需的论文、软件、书籍和文章。

**核心功能**:
- 收录 97 个用于研究和实盘交易的库与包，涵盖回测框架（如 vnpy、zipline、backtrader）、交易机器人、数据分析、指标计算、风险管理、券商 API、数据源、机器学习等类别
- 整理 40+ 个由机构与学术界描述的交易策略，覆盖债券、商品、货币、股票、加密资产等资产类别
- 精选 55 本适合初学者和专业人士的书籍，以及 23 个视频/访谈、博客和课程资源
- 每个库按编程语言分类，并依据 GitHub 星标数降序排列，便于快速筛选高人气工具
- 提供中文版 Readme（README_zh.md），并引导用户访问 paperswithbacktest.com 获取更多 Python 实现的策略内容

**技术亮点**: 以 Python 为主要语言生态，采用 Markdown 表格结构化展示资源，并通过 GitHub Stars 徽章实时反映项目热度；同时支持社区贡献（通过 Issue 提交建议）和社交分享。

---
## 4. [different-ai/openwork](https://github.com/different-ai/openwork)
- **语言**: TypeScript
- **Stars**: 18,777
- **简介**: The open-source alternative to Claude Cowork (powered by opencode)

### AI 总结
**简介**: OpenWork 是一个免费开源的桌面应用，旨在共享 AI 工作流，可作为 Claude Cowork 和 Codex 的开源替代品，支持 macOS、Windows 和 Linux。

**核心功能**:
- 通过 OpenWork MCP 将技能、MCP 连接和已连接服务（如 Google Workspace、Microsoft 365）集成到 Codex、Claude Code、Cursor 等 AI 代理中
- 提供 `search_capabilities` 和 `execute_capability` 两个工具，用于发现和执行可用的能力
- 支持创建、共享和复用 AI 工作流，可分享给同事或朋友
- 提供 OpenWork Den 管理平面，用于团队/组织级的管理，包括模型提供商访问控制、成员与团队管理、桌面策略配置、技能与插件发布及分配
- 支持导入 Anthropic 兼容插件，并通过 OpenWork MCP 提供其技能和远程 MCP
- 桌面应用可作为专用工作区，但非必需，可直接从现有 AI 代理使用

**技术亮点**: 基于 TypeScript 开发，采用 Electron 构建跨平台桌面应用；通过远程 MCP 服务器（HTTPS）实现与多种 AI 代理的兼容集成；支持多 git worktree 并行开发（`pnpm dev:worktree`），自动管理独立开发配置文件和端口分配。

---
## 5. [WhiskeySockets/Baileys](https://github.com/WhiskeySockets/Baileys)
- **语言**: JavaScript
- **Stars**: 10,444
- **简介**: Socket-based TS/JavaScript API for WhatsApp Web

### AI 总结
**简介**: Baileys 是一个基于 WebSocket 的 TypeScript 库，用于直接与 WhatsApp Web API 交互，无需浏览器或 Selenium。

**核心功能**:
- 通过 WebSocket 直接连接 WhatsApp Web，无需 Selenium 或 Chromium，节省约 500MB 内存
- 支持 WhatsApp 多设备版本和 Web 版本
- 支持通过 QR 码或配对码连接账号
- 提供会话保存/恢复功能
- 支持事件处理（消息、群组、投票等）
- 支持缓存群组元数据、重试系统和投票解密
- 提供完整的数据存储实现接口

**技术亮点**:
- 纯 TypeScript/JavaScript 实现，基于 WebSocket 协议
- 无需浏览器环境，资源占用低
- 提供稳定版和 edge 版（最新功能）两种安装渠道
- 社区维护，提供 Discord 支持和官方文档（baileys.wiki）
- 支持业务级付费支持服务

---
## 6. [pascalorg/editor](https://github.com/pascalorg/editor)
- **语言**: TypeScript
- **Stars**: 20,140
- **简介**: Create and share 3D architectural projects.

### AI 总结
**简介**: Pascal Editor 是一个基于 React Three Fiber 和 WebGPU 的 3D 建筑编辑器，用于创建和分享三维建筑项目。

**核心功能**:
- 3D 建筑场景编辑：支持创建 Site（场地）、Building（建筑）、Level（楼层）层级结构，包含墙体、楼板、天花板、屋顶、区域、门窗等建筑元素
- 节点系统：基于扁平字典存储的节点层级结构，支持节点的创建、更新、删除和父子关系管理
- 场景状态管理：使用 Zustand 管理场景状态，支持 IndexedDB 持久化存储和撤销/重做功能
- 多包架构：提供 `@pascal-app/core`、`@pascal-app/viewer`、`@pascal-app/editor`、`@pascal-app/nodes` 等多个 npm 包，支持按需集成
- 插件化扩展：内置节点注册表插件，可通过 `loadPlugin` 加载扩展功能

**技术亮点**: 
- 基于 WebGPU 的高性能 3D 渲染
- Turborepo monorepo 架构，分离核心逻辑（core）、渲染运行时（viewer）、编辑工具（editor）和内置节点（nodes）
- 使用 Zustand 分模块管理状态（场景、视图、编辑器），支持 React 组件内订阅和外部访问
- 支持多种楼层显示模式（堆叠/分解/独立）和相机预设

---
## 7. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 55,580
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: /last30days 是一个 AI 智能体驱动的搜索技能，可并行检索 Reddit、X、YouTube、HN、Polymarket 等平台内容，按真实用户互动（点赞、投票、资金）评分，并综合生成一份有据可依的摘要简报。

**核心功能**:
- **多平台并行搜索**: 同时检索 Reddit、X/Twitter、YouTube、TikTok、Instagram Reels、Hacker News、Polymarket、GitHub 等 50+ 平台，突破单一平台"围墙花园"限制
- **真实用户评分机制**: 以 Reddit 点赞、X 点赞、YouTube 字幕、TikTok 互动、Polymarket 真金白银赔率等作为内容重要性排序依据，而非编辑推荐
- **AI 智能体综合评判**: 将分散在各平台的碎片信息汇总为一份简洁简报，例如搜索某人可得到其本月动态、社区讨论热度、GitHub PR 活跃度等
- **零配置快速上手**: Reddit、HN、Polymarket、GitHub 开箱即用；运行一次后 30 秒设置向导解锁 X、YouTube、TikTok 等更多源
- **多宿主兼容**: 支持 Claude Code（市场自动更新）、Codex、Cursor、Copilot、Gemini CLI 及 50+ Agent Skills 宿主，通过 `npx skills add` 一条命令安装

**技术亮点**: 采用 Agent Skills 规范（SKILL.md 为运行时唯一事实源），支持自带 API 密钥和浏览器会话以桥接各平台；Python 实现并行抓取与评分管道，当前为 v3 版本。

---
## 8. [dotnet/aspnetcore](https://github.com/dotnet/aspnetcore)
- **语言**: C#
- **Stars**: 38,298
- **简介**: ASP.NET Core is a cross-platform .NET framework for building modern cloud-based web applications on Windows, Mac, or Linux.

### AI 总结
**简介**: ASP.NET Core 是微软开源的跨平台 .NET 框架，用于构建现代云端互联网应用（如 Web 应用、IoT 应用和移动后端），支持 Windows、Mac 和 Linux 平台。

**核心功能**:
- 跨平台运行：基于 .NET 运行时，可在 Windows、Mac、Linux 上开发部署
- 模块化架构：由低开销的模块化组件构成，构建方案时保持灵活性
- 云原生优化：专为云端或本地部署设计，提供优化的开发框架
- 每周社区直播（Community Standup）与公开路线图，跟踪开发进展
- 提供每日构建版本下载，支持源码编译和贡献

**技术亮点**: 使用 C# 语言，基于开源跨平台的 .NET 运行时；采用模块化组件设计，保持最小开销；与 Entity Framework Core、Razor 编译器、.NET Runtime 等生态项目紧密集成；采用 MIT 许可证，并通过 .NET Foundation 治理。

---
## 9. [microsoft/PowerToys](https://github.com/microsoft/PowerToys)
- **语言**: C
- **Stars**: 137,142
- **简介**: Microsoft PowerToys is a collection of utilities that supercharge productivity and customization on Windows

### AI 总结
**简介**: Microsoft PowerToys 是一套用于自定义 Windows 并简化日常任务的实用工具合集，包含超过 30 个功能模块。

**核心功能**:
- **窗口管理**: FancyZones（窗口布局）、Always on Top（置顶窗口）、Crop And Lock（裁剪锁定）
- **批量操作**: PowerRename（批量重命名）、Image Resizer（图片尺寸调整）、File Explorer Add-ons（文件预览增强）
- **快捷启动**: PowerToys Run（快速启动器）、Command Palette（命令面板）、Shortcut Guide（快捷键指南）
- **输入增强**: Keyboard Manager（键盘映射）、Quick Accent（快速输入重音符号）、Mouse Utilities（鼠标工具）
- **系统工具**: Hosts File Editor（Hosts 编辑）、Environment Variables（环境变量管理）、Registry Preview（注册表预览）
- **其他效率工具**: Advanced Paste（智能粘贴）、Color Picker（取色器）、Awake（保持唤醒）、Peek（快速预览）、Mouse Without Borders（跨设备鼠标共享）

**技术亮点**: 基于 C# 开发，采用模块化架构设计，支持 WinUI 3 与现代 Windows API，通过 GitHub 开源协作持续迭代，提供统一的设置界面和自动更新机制。

---
## 10. [ansible/ansible](https://github.com/ansible/ansible)
- **语言**: Python
- **Stars**: 69,894
- **简介**: Ansible is a radically simple IT automation platform that makes your applications and systems easier to deploy and maintain. Automate everything from code deployment to network configuration to cloud management, in a language that approaches plain English, using SSH, with no agents to install on remote systems. https://docs.ansible.com.

### AI 总结
**简介**: Ansible 是一个极其简单的 IT 自动化平台，通过 SSH 实现配置管理、应用部署和云资源编排，无需在远程系统安装代理。

**核心功能**:
- 配置管理与应用部署：支持零停机滚动更新和负载均衡等复杂变更
- 云资源预配置与多节点编排：覆盖从代码部署到网络配置的自动化场景
- 即席任务执行与网络自动化：支持并行批量管理多台机器
- 基于人类可读语言描述基础设施：接近纯英语的声明式语法
- 模块化扩展：支持使用 Python 以外的任意动态语言开发模块

**技术亮点**:
- 无代理架构：基于现有 SSH 守护进程，无需安装额外软件或开放端口
- 极简上手：设置过程简单，学习曲线平缓，支持非 root 用户操作
- 即时管理新机器：无需引导安装任何软件即可接入新节点
- 安全优先：强调可审计性、易审查和内容重写，模块可动态开发
- 并行执行能力：快速批量管理机器，支持多种平台安装（pip 或包管理器）

---
