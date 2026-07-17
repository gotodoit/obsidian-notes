---
tags:
  - github-trending
  - daily
date: 2026-07-17
created: 2026-07-17T01:55:44.134Z
---

# 2026-07-17 GitHub Trending Top 10

## 1. [apache/ossie](https://github.com/apache/ossie)
- **语言**: Python
- **Stars**: 915
- **简介**: Apache Ossie, industry wide specification effort to standardize how we exchange semantic metadata across analytics, AI and BI platforms, providing a vendor neutral, single source of truth for semantic data

### AI 总结
**简介**: Apache Ossie 是一个开源项目，旨在标准化跨分析、AI 和 BI 平台的语义元数据交换，提供厂商中立、统一的语义数据事实来源。

**核心功能**:
- 提供基于 JSON/YAML 的单一规范，支持任意工具读写语义模型
- 包含参考转换器，可在 Ossie 与其他语义格式（如 dbt、GoodData、Polaris、Salesforce）之间互转
- 提供语义模型验证工具，确保模型符合 Ossie 规范
- 包含完整示例模型（如 TPC-DS 模型）和核心规范文档

**技术亮点**: 使用 Python 开发，核心规范基于 JSON/YAML 格式，提供机器可读的 schema 定义（spec.yaml 和 osi-schema.json），支持厂商无关的语义数据交换

---
## 2. [Nutlope/hallmark](https://github.com/Nutlope/hallmark)
- **语言**: CSS
- **Stars**: 10,958
- **简介**: Anti-AI-slop design skill for Claude Code, Cursor, and Codex.

### AI 总结
**简介**: Hallmark 是一个专为 Claude Code、Cursor 和 Codex 设计的设计技能，旨在生成不像是 AI 生成的独特 UI 界面。

**核心功能**:
- **生成新 UI**：为每个需求选择不同的宏观结构和主题，生成独一无二的页面，而非套用模板。
- **审计现有代码**：使用 `hallmark audit <target>` 命令，根据反模式对现有代码进行评分，生成问题清单。
- **重新设计**：使用 `hallmark redesign <target>` 命令，保留内容、信息架构和品牌，但重构结构和风格。
- **提取设计 DNA**：使用 `hallmark study <screenshot | URL>` 命令，从优秀设计中提取宏观结构、字体搭配和色彩锚点，并生成可移植的 `design.md` 文件。

**技术亮点**: 内置 57 个反 AI 生成模式检查门（slop-test gates）和输出前自我批评机制，确保输出脱离大模型训练出的常见分布。提供 20 种内置主题，并支持根据创意需求进行完全定制（Custom）设计。

---
## 3. [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut)
- **语言**: TypeScript
- **Stars**: 74,046
- **简介**: The open-source CapCut alternative

### AI 总结
**简介**: 一个免费开源的跨平台视频编辑器，致力于成为CapCut的替代品，支持Web、桌面和移动端。

**核心功能**:
- 提供编辑器API和插件优先架构，支持第三方插件
- 支持桌面端、移动端和浏览器端统一代码库
- 内置MCP服务器（AI代理支持）和脚本编辑标签
- 支持无头模式（自动化、批量渲染）

**技术亮点**: 采用Rust核心实现跨平台统一代码库，使用TypeScript开发，支持proto工具链和Moon工作流管理。

---
## 4. [PostHog/posthog](https://github.com/PostHog/posthog)
- **语言**: Python
- **Stars**: 35,857
- **简介**: 🦔 PostHog is the leading platform for building self-driving products. Our developer tools – AI observability, analytics, session replay, flags, experiments, error tracking, logs, and more – capture all the context agents need to diagnose problems, uncover opportunities, and ship fixes. Steer it all from Slack, web, desktop, or the MCP.

### AI 总结
**简介**: PostHog 是领先的开源产品分析平台，提供构建自驱型产品所需的全套工具，支持从数据中自动诊断问题、发现机会并修复缺陷。

**核心功能**:
- 自驱模式：自动将产品数据信号转化为研究报告和代码拉取请求
- 产品分析：自动捕获或手动埋点，支持可视化或SQL分析用户行为
- Web分析：监控网站流量、用户会话、转化率、Web指标和收入
- 会话回放：观看真实用户与网站或移动应用的交互过程
- 功能标志：安全地向特定用户或群体发布新功能
- 实验：测试变更并衡量其对目标指标的统计影响
- 错误跟踪：追踪错误、获取警报并解决问题
- 日志：采集、搜索和分析日志数据
- 调查：提供无代码调查模板或自定义调查构建器
- 数据仓库：同步外部工具数据并与产品数据一起查询
- 数据管道：对传入数据运行自定义过滤和转换，实时发送到25+工具
- AI可观测性：捕获LLM应用的追踪、生成、延迟和成本
- 工作流：创建自动化操作或向用户发送消息的工作流
- 多端操控：支持通过Slack、Web、桌面应用或编辑器MCP进行控制

**技术亮点**: 基于Python开发，支持自托管部署，提供慷慨的免费月额度，支持Docker部署，拥有活跃的社区贡献和持续更新。

---
## 5. [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter)
- **语言**: Rust
- **Stars**: 65,992
- **简介**: A coding agent for open models like Kimi K3

### AI 总结
**简介**: 一个为低成本模型（如 Kimi K3）优化的编码智能体，基于 Rust 实现，提供类似 Codex 的交互界面和强大的 Agent 能力。

**核心功能**:
- 提供多种模型“ harness ”（如 kimi-code, claude-code, deepseek-tui 等），可动态切换以适配不同模型。
- 支持 ACP（Agent Client Protocol）协议，可作为编辑器或第三方客户端的智能体代理。
- 内置 QA 技能，可驱动真实浏览器或原生应用进行 Web 和桌面应用的测试与操作。
- 支持原生沙箱执行命令（macOS/Linux/Windows），并集成 MCP、技能、钩子、权限和 `AGENTS.md` 等高级功能。

**技术亮点**:
- 使用 **Rust** 重写了 Kimi 官方推荐的 harness，实现高性能。
- 兼容 OpenAI Codex 的执行协议，可直接替换 Codex SDK。
- 支持本地配置和会话状态管理（`~/.openinterpreter`）。
- 提供 TUI 界面，可通过 `/model` 和 `/harness` 命令实时切换模型和引擎。

---
## 6. [PrismML-Eng/Bonsai-demo](https://github.com/PrismML-Eng/Bonsai-demo)
- **语言**: Shell
- **Stars**: 1,525
- **简介**: Bonsai Demo

### AI 总结
**简介**: Bonsai-demo 是一个用于在本地运行 Bonsai 系列高效语言模型的演示仓库，支持 1-bit 和三元量化模型。

**核心功能**:
- 支持在 Mac (Metal)、Linux/Windows (CUDA, Vulkan, ROCm) 或 CPU 上本地运行 Bonsai 和 Ternary-Bonsai 模型。
- 提供快速启动脚本 (`setup.sh` / `setup.ps1`)，一键安装依赖、下载模型和二进制文件。
- 支持多种模型尺寸（27B, 8B, 4B, 1.7B）和两个模型系列（1-bit 和 Ternary），可灵活切换。
- 最新的 Bonsai 27B 系列支持视觉-语言能力（图片、截图、PDF 分析）、原生 OpenAI 风格工具调用和 MCP 服务器集成。
- 提供基于 llama.cpp 的推理服务，默认在 `http://localhost:8080` 启动聊天、视觉和工具调用界面。

**技术亮点**: 采用极低比特量化技术（1-bit Q1_0 和三元 Q2_0），Bonsai-27B 模型仅需约 1.125 bits/权重，可在现代手机上运行；三元 Bonsai-27B (~1.7 bits/权重) 在保持高质量的同时进一步优化性能；模型已合并至上游 llama.cpp 项目。

---
## 7. [hasaneyldrm/exercises-dataset](https://github.com/hasaneyldrm/exercises-dataset)
- **语言**: HTML
- **Stars**: 15,053
- **简介**: 1,324-exercise fitness dataset — animation GIFs, 180×180 thumbnails, muscle-group & equipment data, and step-by-step instructions in 6 languages. The exercise data layer behind the LogPress app.

### AI 总结
**简介**: 一个包含 1,324 个健身动作的综合性数据集，为 LogPress 应用提供数据支持。
**核心功能**:
- 提供 1,324 个健身动作的动画 GIF、180×180 缩略图、肌肉群、器材等结构化数据
- 包含 10 种语言的分步动作说明
- 内置交互式浏览器，支持搜索、筛选和详情查看
- 提供开发者设置指南，包含 SQL 建表语句、多语言 API 示例和 LLM 提示词
**技术亮点**: 纯前端 HTML 工具，无需服务器即可运行；数据格式清晰，可直接集成到健身应用中。

---
## 8. [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)
- **语言**: Python
- **Stars**: 122,922
- **简介**: 100+ AI Agent & RAG apps you can actually run — clone, customize, ship.

### AI 总结
**简介**: 一个包含 100+ 个开源 AI 智能体、智能体技能和 RAG 应用的仓库，支持克隆、自定义和部署。

**核心功能**:
- 提供多种 AI 智能体模板，包括智能体技能（如 Project Graveyard）、初级 AI 智能体（如 AI Travel Agent）和高级 AI 智能体（如 AI Fraud Investigation Agent）。
- 支持语音 AI 智能体（如 Insurance Claim Live Agent Team）和常驻智能体（如 Always-on HN Briefing Agent）。
- 可通过 `npx skills add` 命令为编码智能体添加新技能，或通过 `git clone` 和 `pip install` 快速运行任意智能体。

**技术亮点**: 使用 Python 构建，兼容 Claude、Gemini、GPT、DeepSeek、Llama、Qwen 等多种模型；采用 Apache-2.0 开源协议；所有应用均经过端到端测试，支持 Streamlit 部署。

---
## 9. [lobehub/lobehub](https://github.com/lobehub/lobehub)
- **语言**: TypeScript
- **Stars**: 80,177
- **简介**: 🤯 LobeHub is your Chief Agent Operator, organizing your agents into 7×24 operations by hiring, scheduling, and reporting on your entire AI team.

### AI 总结
**简介**: LobeHub 是一个 AI 代理运营平台，通过雇佣、调度和报告整个 AI 团队，实现 7×24 小时的自动化工作流管理。

**核心功能**:
- **Operator（运营）**: 以代理为工作单元，实现 AI 团队的自动化运营
- **Create（创建）**: 支持创建和管理 AI 代理
- **Collaborate（协作）**: 可扩展的新型协作网络
- **Evolve（进化）**: 支持人与代理的共同进化

**技术亮点**: 基于 TypeScript 构建，支持 Docker 部署、Vercel/Zeabur/Sealos/阿里云等平台一键部署，提供环境变量配置，拥有完善的插件生态系统。

---
## 10. [YimMenu/YimMenuV2](https://github.com/YimMenu/YimMenuV2)
- **语言**: C++
- **Stars**: 1,506
- **简介**: Experimental menu for GTA 5: Enhanced

### AI 总结
**简介**: 这是一个针对GTA5增强版（Enhanced）的实验性模组菜单，基于C++20开发，旨在通过模板化实践探索模组菜单的基础架构。

**核心功能**:
- 提供模组菜单的基础框架实现
- 包含游戏特定功能的实现模块
- 提供非游戏特定的通用工具函数

**技术亮点**: 采用C++20模板化设计，项目结构清晰分为core（核心基础）、game（游戏特定实现）和util（通用工具）三个模块。

---
