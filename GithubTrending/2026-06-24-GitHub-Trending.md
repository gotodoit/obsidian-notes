---
tags:
  - github-trending
  - daily
date: 2026-06-24
created: 2026-06-24T01:55:43.368Z
---

# 2026-06-24 GitHub Trending Top 10

## 1. [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)
- **语言**: Python
- **Stars**: 15,827
- **简介**: World's first open-source, agentic video production system. 12 pipelines, 52 tools, 500+ agent skills. Turn your AI coding assistant into a full video production studio.

### AI 总结
**简介**: OpenMontage 是全球首个开源的智能视频制作系统，可将 AI 编码助手转化为完整的视频制作工作室。

**核心功能**:
- 通过自然语言描述需求，AI 自动完成研究、脚本、素材生成、剪辑和最终合成
- 支持真实视频制作：从免费素材库获取动态视频片段并进行时间线编辑，而非仅生成图片动画
- 提供 12 条制作管线、52 个工具和 500+ 智能体技能
- 支持多种生成方式：AI 生成视频/图片、素材库检索、图像动画等

**技术亮点**:
- 基于 Python 开发，采用智能体架构
- 集成 Remotion 动画引擎、Veo/Kling 视频生成、FLUX 图像生成、WhisperX 字幕等
- 支持多种 AI 提供商（OpenAI、fal.ai 等）
- 极低成本：示例视频制作仅需 $0.15-$1.33

---
## 2. [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis)
- **语言**: Python
- **Stars**: 47,118
- **简介**: LLM 驱动的多市场股票智能分析系统：多源行情、实时新闻、决策看板与自动推送，支持零成本定时运行。 LLM-powered multi-market stock analysis system with multi-source market data, real-time news, decision dashboard, automated notifications, and cost-free scheduled runs.

### AI 总结
**简介**: 基于 LLM 的多市场股票智能分析系统，支持 A股、港股、美股、日股、韩股，可每日自动分析并推送决策仪表盘。

**核心功能**:
- **AI 决策报告**: 自动生成核心结论、评分、趋势、买卖点位、风险警报等分析报告
- **多市场数据聚合**: 整合行情、K线、技术指标、资金流、新闻、公告和基本面数据
- **Web/桌面工作台**: 支持手动分析、历史报告、回测、持仓、配置管理
- **Agent 策略问股**: 支持均线、缠论、波浪、趋势等 15 种内置策略的多轮追问
- **智能导入与补全**: 支持图片、CSV/Excel、剪贴板导入；股票代码/名称自动补全
- **自动化与推送**: 支持 GitHub Actions、Docker、本地定时任务，推送至企业微信、飞书、Telegram、Discord、Slack、邮箱

**技术亮点**: 采用 LLM 驱动分析，支持多种 AI 模型（Gemini、OpenAI、DeepSeek、Claude、Ollama 等），集成多个数据源（AkShare、Tushare、YFinance 等），支持零成本 GitHub Actions 定时运行，提供完整的 Docker 和 FastAPI 部署方案。

---
## 3. [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills)
- **语言**: Python
- **Stars**: 19,745
- **简介**: 817 structured cybersecurity skills for AI agents · Mapped to 6 frameworks: MITRE ATT&CK, NIST CSF 2.0, MITRE ATLAS, D3FEND, NIST AI RMF & MITRE F3 (Fight Fraud) · agentskills.io standard · Works with Claude Code, GitHub Copilot, Codex CLI, Cursor, Gemini CLI & 20+ platforms · 29 security domains · Apache 2.0

### AI 总结
**简介**: 这是一个为 AI 代理提供 817 个结构化网络安全技能的开源库，覆盖 29 个安全领域，并映射至 6 个主流行业框架。

**核心功能**:
- **结构化技能库**: 提供 817 个生产级网络安全技能，涵盖数字取证、威胁情报、云安全等 29 个领域。
- **多框架映射**: 每个技能均映射至 MITRE ATT&CK、NIST CSF 2.0、MITRE ATLAS、D3FEND、NIST AI RMF 和 MITRE F3 等 6 个框架，实现跨框架统一覆盖。
- **兼容多平台**: 支持 Claude Code、GitHub Copilot、Codex CLI、Cursor、Gemini CLI 等 26 个以上 AI 平台。
- **开放标准**: 遵循 agentskills.io 开放标准，便于集成与扩展。

**技术亮点**: 采用 Python 开发，遵循 Apache 2.0 开源协议，是首个实现跨 6 个行业框架统一映射的开源技能库。

---
## 4. [garrytan/gstack](https://github.com/garrytan/gstack)
- **语言**: TypeScript
- **Stars**: 114,120
- **简介**: Use Garry Tan's exact Claude Code setup: 23 opinionated tools that serve as CEO, Designer, Eng Manager, Release Manager, Doc Engineer, and QA

### AI 总结
**简介**: gstack 将 Claude Code 转变为一个虚拟工程团队，包含 23 个专业工具和 8 个强力工具，帮助个人开发者像二十人团队一样高效交付产品。

**核心功能**:
- **虚拟团队角色**: 提供 CEO、设计师、工程经理、发布经理、文档工程师和 QA 等 23 个专业化工具，通过斜杠命令调用
- **全流程自动化**: 支持从产品构思（/office-hours）、架构审查（/plan-eng-review）、设计审查、代码审查（/review）、QA 测试（/qa）到发布部署（/ship）的完整开发流程
- **安全与质量保障**: 包含安全审计（/cso，运行 OWASP + STRIDE）、自动化回归测试（/canary）、性能基准测试（/benchmark）等工具
- **团队协作模式**: 支持团队模式，自动为共享仓库配置 gstack，确保团队成员使用统一工具链

**技术亮点**: 基于 TypeScript 构建，与 Claude Code 深度集成；所有工具均为 Markdown 格式、MIT 开源许可；安装仅需 30 秒，依赖 Git、Bun 和 Node.js

---
## 5. [bytedance/deer-flow](https://github.com/bytedance/deer-flow)
- **语言**: Python
- **Stars**: 73,956
- **简介**: An open-source long-horizon SuperAgent harness that researches, codes, and creates. With the help of sandboxes, memories, tools, skill, subagents and message gateway, it handles different levels of tasks that could take minutes to hours.

### AI 总结
**简介**: DeerFlow 是一个开源的长周期超级代理编排框架，能够通过子代理、记忆和沙箱等组件，处理从几分钟到数小时的复杂任务。

**核心功能**:
- **子代理编排**: 支持调用多个子代理协同完成复杂任务
- **记忆管理**: 提供长期记忆机制，提升任务连续性和上下文理解
- **沙箱与文件系统**: 提供安全的隔离环境，用于代码执行和文件操作
- **技能与工具扩展**: 支持通过可扩展的技能和工具（如 Claude Code 集成）增强代理能力
- **上下文工程**: 优化上下文管理，提升长周期任务的执行效率
- **消息网关**: 集成 IM 通道，支持即时消息交互

**技术亮点**: 采用 Python 3.12+ 和 Node.js 22+ 构建，支持 Docker 部署和本地开发；集成了 InfoQuest 智能搜索工具集，并兼容 LangSmith 和 Langfuse 追踪；推荐使用 Doubao-Seed-2.0-Code、DeepSeek v3.2 等先进模型。

---
## 6. [koala73/worldmonitor](https://github.com/koala73/worldmonitor)
- **语言**: TypeScript
- **Stars**: 59,125
- **简介**: Real-time global intelligence dashboard. AI-powered news aggregation, geopolitical monitoring, and infrastructure tracking in a unified situational awareness interface

### AI 总结
**简介**: World Monitor 是一个基于 AI 的实时全球情报仪表盘，整合新闻聚合、地缘政治监控与基础设施追踪，提供统一态势感知界面。

**核心功能**:
- 500+ 经 AI 合成的新闻摘要，覆盖 15 个类别
- 双地图引擎（3D 地球与 WebGL 平面地图），支持 56 种地图图层
- 跨流信号关联分析（军事、经济、灾害等）
- 国家不稳定指数（CII）评分，覆盖 31 个一级国家
- 金融雷达（29 个交易所、大宗商品、加密货币等）
- 支持本地 AI 运行（Ollama），无需 API 密钥
- 单一代码库生成 6 个网站变体（世界、科技、金融等）
- 原生桌面应用（Tauri 2），支持 macOS/Windows/Linux
- 24 种语言界面，含本地语言新闻源与 RTL 支持

**技术亮点**: 基于 TypeScript 构建，采用 Tauri 2 桌面框架、globe.gl 与 deck.gl 地图引擎，支持多平台分发与单代码库多站点部署。

---
## 7. [palmier-io/palmier-pro](https://github.com/palmier-io/palmier-pro)
- **语言**: Swift
- **Stars**: 8,449
- **简介**: macOS video editor built for AI

### AI 总结
**简介**: Palmier Pro 是一款专为 AI 设计的开源 macOS 视频编辑器，支持在时间线内与 AI 代理协作生成和编辑视频。

**核心功能**:
- 内置 Seedance、Kling、Nano Banana Pro 等 SOTA 模型，可在时间线内直接生成视频和图像
- 通过 MCP 协议连接 Claude、Codex、Cursor 等 AI 代理，实现人机协作编辑
- 提供原生 Swift 构建的视频编辑能力，对标 Adobe Premiere Pro
- 支持多语言界面（包括简体中文）

**技术亮点**: 使用 Swift 原生开发，通过 HTTP MCP 服务器（`http://127.0.0.1:19789/mcp`）实现与 AI 代理的集成，编辑器核心完全开源（GPLv3），仅生成式 AI 处理部分闭源。

---
## 8. [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- **语言**: Python
- **Stars**: 30,861
- **简介**: Official, Anthropic-managed directory of high quality Claude Code Plugins.

### AI 总结
**简介**: Anthropic官方维护的高质量Claude Code插件目录，提供内部与第三方插件的发现、安装与管理。  
**核心功能**:  
- 提供结构化插件目录，区分内部插件（`/plugins`）与外部社区插件（`/external_plugins`）  
- 支持通过命令行`/plugin install`或`/plugin > Discover`浏览安装插件  
- 定义插件标准结构（含`.claude-plugin/plugin.json`、MCP配置、命令/代理/技能等模块）  
- 支持“技能包”插件（Skill-bundle），允许无清单文件的仓库通过声明式配置暴露技能子集  
**技术亮点**: 采用Python开发，基于MCP（Model Context Protocol）服务器配置与严格/非严格模式插件清单，支持git-subdir源引用与SHA校验。

---
## 9. [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice)
- **语言**: HTML
- **Stars**: 59,501
- **简介**: from vibe coding to agentic engineering - practice makes claude perfect

### AI 总结
**简介**: 一个专注于 Claude Code 最佳实践的开源项目，涵盖从“氛围编码”到“智能体工程”的全方位指南，旨在帮助开发者高效使用 Claude Code 进行开发。

**核心功能**:
- **智能体 (Subagents)**: 提供 `.claude/agents/` 目录下的配置与最佳实践指南。
- **命令 (Commands)**: 包含 `.claude/commands/` 目录下的自定义命令实现与建议。
- **技能 (Skills)**: 展示 `.claude/skills/` 目录下的技能定义、最佳实践及官方技能资源。
- **工作流 (Workflows)**: 演示编排工作流的实现方式，如天气编排器。
- **钩子 (Hooks)**: 提供 `.claude/hooks/` 的使用指南与最佳实践。
- **MCP 服务器**: 涵盖 `.claude/settings.json` 和 `.mcp.json` 的配置与最佳实践。
- **插件 (Plugins)**: 介绍可分发包及市场创建方法。
- **设置 (Settings)**: 包含 `.claude/settings.json` 的权限、模型配置、输出样式、沙箱等最佳实践。

**技术亮点**: 项目基于 HTML 构建，通过清晰的结构化文档和标签（如最佳实践、已实现、编排工作流）引导用户快速定位和使用 Claude Code 的各种核心功能，并得到社区与企业的支持。

---
## 10. [revfactory/harness](https://github.com/revfactory/harness)
- **语言**: HTML
- **Stars**: 7,452
- **简介**: A meta-skill that designs domain-specific agent teams, defines specialized agents, and generates the skills they use.

### AI 总结
**简介**: Harness 是一个为 Claude Code 设计的团队架构工厂插件，能根据领域描述自动生成专业化智能体团队及其技能。

**核心功能**:
- **智能体团队设计** — 提供6种架构模式（管道、扇出/扇入、专家池、生产者-评审者、监督者、层级委派）
- **技能自动生成** — 为智能体自动生成技能，支持渐进式披露以优化上下文管理
- **团队编排** — 实现智能体间数据传递、错误处理和团队协调协议
- **验证测试** — 提供触发器验证、模拟测试和对比测试功能

**技术亮点**:
- 位于 Claude Code 生态系统的 L3 元工厂层，属于团队架构工厂子层
- 通过简单指令（如 "build a harness for this project"）即可触发完整流程
- 自动生成 `.claude/agents/` 和 `.claude/skills/` 目录结构

---
