---
tags:
  - github-trending
  - daily
date: 2026-05-11
created: 2026-05-11T01:55:45.548Z
---

# 2026-05-11 GitHub Trending Top 10

## 1. [bytedance/UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop)
- **语言**: TypeScript
- **Stars**: 32,184
- **简介**: The Open-Source Multimodal AI Agent Stack: Connecting Cutting-Edge AI Models and Agent Infra

### AI 总结
**简介**: 字节跳动开源的多模态AI Agent桌面应用，基于UI-TARS模型提供原生GUI Agent能力，支持本地和远程的计算机及浏览器操作。

**核心功能**:
- 本地和远程计算机操作
- 本地和远程浏览器操作
- 支持UI-TARS-1.5高级模型
- 提供跨平台GUI自动化SDK

**技术亮点**: 基于TypeScript开发，采用多模态AI Agent架构，集成MCP工具生态，支持流式处理和事件流追踪。

---
## 2. [anthropics/financial-services](https://github.com/anthropics/financial-services)
- **语言**: Python
- **Stars**: 18,924
- **简介**: 

### AI 总结
**简介**: 一个为金融服务行业（投资银行、股权研究、私募股权和财富管理）设计的Claude参考代理、技能和数据连接器集合。

**核心功能**:
- 提供端到端工作流代理，如Pitch Agent（制作推介材料）、Market Researcher（市场研究）、Model Builder（财务建模）和GL Reconciler（总账对账）
- 支持两种部署方式：作为Claude Cowork插件安装，或通过Claude Managed Agents API部署
- 包含垂直技能插件，如comps、DCF、earnings等独立功能模块
- 提供KYC Screener、Statement Auditor等运营和合规自动化工具

**技术亮点**: 基于Claude平台构建，采用插件化架构（agent-plugins和vertical-plugins分离），支持Cowork和Managed Agents两种运行模式，包含完整的agent.yaml配置、子代理和事件驱动示例，提供Microsoft 365集成工具和自动化部署脚本。

---
## 3. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: Shell
- **Stars**: 38,494
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 为 AI 编码代理提供生产级工程技能的规则和工具集，确保开发流程的质量和一致性。

**核心功能**:
- 提供7个映射到开发生命周期的斜杠命令（/spec, /plan, /build, /test, /review, /code-simplify, /ship），自动激活对应技能
- 包含22个结构化技能（21个生命周期技能+1个元技能），每个技能包含工作流步骤、验证门和反合理化表格
- 支持多种AI编码工具（Claude Code, Cursor, Gemini CLI, Windsurf, OpenCode, GitHub Copilot, Kiro IDE等）

**技术亮点**:
- 技能以纯Markdown格式编写，可跨平台使用
- 遵循“规范先行”、“原子化任务”、“增量构建”等工程最佳实践
- 自动根据开发活动（如设计API、构建UI）触发相应技能

---
## 4. [CloakHQ/CloakBrowser](https://github.com/CloakHQ/CloakBrowser)
- **语言**: Python
- **Stars**: 4,791
- **简介**: Stealth Chromium that passes every bot detection test. Drop-in Playwright replacement with source-level fingerprint patches. 30/30 tests passed.

### AI 总结
**简介**: CloakBrowser 是一个基于 Chromium 的隐身浏览器，在 C++ 源码层面修改了浏览器指纹，能够通过所有机器人检测测试，可作为 Playwright/Puppeteer 的直接替代品。

**核心功能**:
- **源级指纹修改**: 通过 49 个 C++ 源码级别的补丁，修改了 canvas、WebGL、音频、字体、GPU、屏幕、WebRTC、网络时序、自动化信号等指纹特征
- **人性化行为模拟**: 支持 `humanize=True` 参数，自动模拟人类鼠标轨迹、键盘输入节奏和滚动模式
- **高 reCAPTCHA v3 评分**: 服务器验证可达 0.9 分的人类级别评分
- **广泛兼容性**: 通过 Cloudflare Turnstile、FingerprintJS、BrowserScan 等 30+ 个检测网站的测试
- **自动更新二进制**: 后台自动检查更新，始终使用最新的隐身构建版本
- **一键安装**: 支持 `pip install cloakbrowser` 和 `npm install cloakbrowser`，二进制文件自动下载
- **免费开源**: 无订阅、无使用限制
- **浏览器配置管理**: 提供自托管的浏览器配置管理器，支持创建独立指纹、代理和持久会话的浏览器配置

**技术亮点**: 基于 Chromium 的 C++ 源码级指纹修改、支持 Python 和 JavaScript 双语言 API、自动更新的隐身二进制文件、支持 Docker 部署（`docker run --rm cloakhq/cloakbrowser cloaktest`）

---
## 5. [HKUDS/AI-Trader](https://github.com/HKUDS/AI-Trader)
- **语言**: Python
- **Stars**: 15,611
- **简介**: "AI-Trader: 100% Fully-Automated Agent-Native Trading"

### AI 总结
**简介**: AI-Trader 是一个 100% 全自动的、面向 AI Agent 的交易平台，让 AI 代理能够像人类一样进行交易、协作和策略分享。

**核心功能**:
- **🤖 即时 Agent 集成**: 只需向任意 AI 代理发送一条消息，即可在数秒内完成注册和接入。
- **💬 集体智能交易**: 支持多个 Agent 之间协作、辩论，自动挖掘最佳交易想法。
- **📊 一键跟单**: 跟随顶尖交易者，实时镜像其持仓和操作。
- **🌐 跨平台信号同步**: 支持在主流券商（如 Binance, Coinbase, Interactive Brokers）之间同步交易信号。
- **🎯 三种信号类型**: 提供讨论策略、操作复制、协作讨论等不同维度的交易信号。
- **⭐ 奖励系统**: 通过发布信号和获得关注者来赚取积分。

**技术亮点**: 采用 FastAPI + React 前后端分离架构，支持 Polymarket 模拟交易和自动结算，兼容所有主流 AI Agent（如 Claude Code, Codex, Cursor 等）。

---
## 6. [jundot/omlx](https://github.com/jundot/omlx)
- **语言**: Python
- **Stars**: 13,321
- **简介**: LLM inference server with continuous batching & SSD caching for Apple Silicon — managed from the macOS menu bar

### AI 总结
**简介**: oMLX 是一个专为 Apple Silicon Mac 优化的 LLM 推理服务器，支持连续批处理和分层 KV 缓存，并可通过菜单栏管理。

**核心功能**:
- 支持文本 LLM、视觉语言模型 (VLM)、OCR 模型、嵌入模型和重排序模型的推理
- 提供 macOS 菜单栏应用和 Web 管理界面，支持实时监控、模型管理、聊天和基准测试
- 支持连续批处理和多层 KV 缓存（内存+SSD），提升推理效率
- 兼容 OpenAI API，任何 OpenAI 兼容客户端均可连接
- 提供内置聊天 UI，支持多种语言（英文、中文、日文、韩文、俄文等）

**技术亮点**:
- 基于 Apple Silicon (M1/M2/M3/M4) 优化，利用 MLX 框架
- 分层 KV 缓存：热数据驻留内存，冷数据缓存在 SSD，即使上下文变化也能复用历史缓存
- 支持 MCP (Model Context Protocol) 协议扩展
- 通过 Homebrew 或源码安装，支持后台服务运行

---
## 7. [datawhalechina/easy-vibe](https://github.com/datawhalechina/easy-vibe)
- **语言**: JavaScript
- **Stars**: 9,210
- **简介**: 💻 vibe coding 2026 | Your first modern Coding course for beginners to master step by step.

### AI 总结
**简介**: 面向零基础初学者的现代编程入门课程，倡导“会说话就会做应用”的理念，通过可视化教程和互动组件，帮助用户逐步掌握编码技能。

**核心功能**:
- 提供从零开始的清晰学习地图，解决“学了就忘”的痛点
- 包含逐步引导的可视化教程，如同私人导师般的详细演示
- 沉浸式模拟编码环境，通过虚拟鼠标引导快速掌握IDE核心操作
- 以动画形式可视化AI原理（如图像生成、RAG数据流），降低学习门槛
- 支持多语言界面（含简体中文、英文、日文等9种语言）

**技术亮点**: 基于JavaScript实现，采用交互式组件和GIF动画演示，结合在线文档平台提供即时可用的学习体验。

---
## 8. [playcanvas/supersplat](https://github.com/playcanvas/supersplat)
- **语言**: TypeScript
- **Stars**: 6,842
- **简介**: 3D Gaussian Splat Editor

### AI 总结
**简介**: SuperSplat Editor 是一款免费开源的 3D 高斯溅射（3D Gaussian Splatting）编辑器，基于 Web 技术构建，支持在浏览器中直接使用。

**核心功能**:
- 3D 高斯溅射模型的查看、编辑、优化与发布
- 支持浏览器端运行，无需下载安装
- 提供在线编辑器版本（https://superspl.at/editor）
- 支持多语言本地化

**技术亮点**: 基于 TypeScript 开发，使用 Node.js 构建，支持本地开发环境的热重载。

---
## 9. [lsdefine/GenericAgent](https://github.com/lsdefine/GenericAgent)
- **语言**: Python
- **Stars**: 10,543
- **简介**: Self-evolving agent: grows skill tree from 3.3K-line seed, achieving full system control with 6x less token consumption

### AI 总结
**简介**: GenericAgent是一个自进化的最小化自主代理框架，核心代码仅约3K行，通过让LLM自我演化技能树，以极低的Token消耗实现完整的系统控制。

**核心功能**:
- **自进化机制**: 每次完成任务后自动将执行路径结晶为技能，形成专属技能树，能力随使用增长。
- **最小化架构**: 核心代码约3000行，Agent Loop约100行，无复杂依赖，零部署开销。
- **强执行能力**: 注入真实浏览器（保留登录会话），通过9个原子工具直接控制系统（浏览器、终端、文件系统、键盘鼠标、屏幕视觉、移动设备ADB）。
- **高兼容性**: 支持Claude、Gemini、Kimi、MiniMax等主流模型，跨平台运行。
- **Token高效**: 上下文窗口<30K（其他代理通常200K-1M），分层记忆确保知识精准，减少幻觉，降低成本。

**技术亮点**: 自进化技能树机制、分层记忆架构、9原子工具+~100行Agent Loop的极简设计、支持多种LLM模型和跨平台操作。

---
## 10. [decolua/9router](https://github.com/decolua/9router)
- **语言**: JavaScript
- **Stars**: 7,337
- **简介**: Unlimited FREE AI coding. Connect Claude Code, Codex, Cursor, Cline, Copilot, Antigravity to FREE Claude/GPT/Gemini via 40+ providers. Auto-fallback, RTK -40% tokens, never hit limits.

### AI 总结
**简介**: 9Router 是一个免费 AI 路由与令牌节省工具，可将 Claude Code、Cursor 等 AI 代码工具连接到 40+ 免费/廉价 AI 提供商，并自动切换以确保持续编码。

**核心功能**:
- **RTK 令牌节省器**：自动压缩工具输出内容，每次请求节省 20-40% 令牌
- **智能自动回退**：按订阅 → 廉价 → 免费三层顺序自动切换，零停机
- **多账户轮询**：支持同一提供商多账户轮询，最大化使用订阅配额
- **格式转换**：自动在 OpenAI 和 Claude 格式间转换，兼容各类 CLI 工具
- **配额跟踪与刷新**：实时监控配额使用，自动刷新免费令牌

**技术亮点**: 基于 Next.js 构建，提供 Web 控制面板（`localhost:20128`），对外暴露 OpenAI 兼容 API 端点（`/v1`），支持 40+ 提供商和 100+ 模型，通过 npm 全局安装即可使用。

---
