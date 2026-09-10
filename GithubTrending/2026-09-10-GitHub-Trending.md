---
tags:
  - github-trending
  - daily
date: 2026-09-10
created: 2026-09-10T01:55:42.696Z
---

# 2026-09-10 GitHub Trending Top 10

## 1. [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)
- **语言**: Python
- **Stars**: 34,769
- **简介**: A skill to stop your coding agent from burying the answer. ADHD-friendly output.

### AI 总结
**简介**: 一个让编码助手输出更简洁直接的 Python 技能插件，避免答案被冗长废话淹没，适合追求高效阅读的开发者。

**核心功能**:
- 强制"行动优先"输出：先给下一步操作，再给编号步骤，最后给一个明确的后续动作
- 抑制寒暄、跑题和总结性废话（如 "Hope this helps!"、"Great question!"）
- 每轮对话重申当前状态，让上下文始终清晰
- 长列表自动分组排序，每组最多五项，避免信息过载
- 提供具体的分钟级时间估算，而非模糊的"一会儿"

**技术亮点**:
- 基于 Claude 插件/Skill 机制，通过 `SKILL.md` 定义 10 条输出规则
- 支持 fork 后自定义规则并替换上游版本
- 提供多语言 README（中、日、韩、泰、越、葡等），MIT 协议开源

---
## 2. [Tencent/teamai-cli](https://github.com/Tencent/teamai-cli)
- **语言**: TypeScript
- **Stars**: 3,034
- **简介**: Make Every Team AI Native

### AI 总结
**简介**: TeamAI 是腾讯开源的一款 CLI 工具，旨在统一管理团队在多种 AI 编码代理（如 Claude Code、Codex、Cursor 等）中的技能、规则、MCP 与知识，让每个团队实现 AI 原生化。

**核心功能**:
- **统一资源管理**：跨 Claude Code、Codex、CodeBuddy、WorkBuddy、OpenCode、Cursor 等多个 AI 代理，集中管理团队的 skills、rules、docs、agents、hooks、MCP 和环境配置。
- **团队共享与自动同步**：通过 Git 仓库（支持 GitHub、GitLab、GitCode、CNB、TGit 或私有服务）共享团队经验，成员初始化后每次 AI 会话自动拉取最新资源，无需手动同步。
- **灵活的初始化方式**：支持项目级（默认）与用户级（`--scope user`）两种资源安装范围，适配不同使用场景。
- **模板快速起步**：可基于 teamai-hub 提供的生产级模板（含 skills、rules、review agents）快速创建团队仓库。
- **三层产品架构**：
  - Team Execution：让每个代理按团队方式工作（init/pull/push、skills、rules、MCP 等）
  - Team Context（beta）：让每个代理理解团队（recall、learnings、代码库图谱、teamwiki）
  - Team Improvement（beta）：让每次执行反哺团队（基于摩擦的分享学习、会话、摘要、仪表盘）

**技术亮点**:
- 使用 TypeScript 开发，通过 npm 全局安装（`npm install -g teamai-cli`）。
- 采用 MIT 开源许可，具备完整的 CI 流程与 npm 发布体系。
- 架构上以「团队执行 × 团队上下文 × 团队改进」三层模型组织能力，覆盖从日常执行到知识沉淀的完整闭环。

---
## 3. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 284,061
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，基于可组合的技能（skills）和初始指令构建，让智能体自动遵循规范化的开发流程。

**核心功能**:
- 自动触发技能机制：编码智能体启动后无需额外操作，技能自动生效
- 需求澄清与规格生成：智能体先与用户确认真正目标，分块展示规格供审阅
- 实现计划生成：输出足够清晰的实施计划，强调红/绿 TDD、YAGNI 和 DRY 原则
- 子智能体驱动开发：按任务逐一推进，自动检查与审查工作成果，可自主运行数小时不偏离计划

**技术亮点**:
- 跨平台支持广泛，覆盖 Claude Code、Codex、Cursor、Gemini CLI、GitHub Copilot CLI、Devin CLI 等十余种编码工具
- 采用插件/扩展机制安装，各平台有独立安装方式
- 以 Shell 为主要语言实现
- 提供企业级商业支持服务

---
## 4. [pascalorg/editor](https://github.com/pascalorg/editor)
- **语言**: TypeScript
- **Stars**: 22,956
- **简介**: Open-source 3D architectural editor with a local CLI, MCP tools, and practical workflows for humans and AI agents.

### AI 总结
**简介**: Pascal Editor 是一个开源、本地优先的 3D 建筑编辑器，基于 React Three Fiber 和 WebGPU 构建，支持浏览器和 CLI 运行，并可通过 MCP 连接 AI 代理。

**核心功能**:
- 通过 `npx @pascal-app/cli editor` 一键启动本地编辑器，自动分配端口并将项目数据持久化到 `~/.pascal/data/pascal.db`
- 内置认证的 MCP 服务，支持 AI 代理（如 Claude Code）通过 `pascal mcp connect` 接入
- 提供 agent skills（如 `pascal-3d`、`furniture-fit`），可通过 skills.sh 或 Claude 插件安装
- 支持只读家具候选输入检查（需使用 GitHub 预览版 CLI）

**技术亮点**:
- 技术栈：TypeScript + React Three Fiber + WebGPU
- 本地优先架构，数据存储于本地 SQLite，无需账号或 API key，项目不会自动上传
- 模块化 npm 包设计（`@pascal-app/core`、`@pascal-app/viewer`、`@pascal-app/cli`）
- 支持多客户端共享场景状态，并可通过独立 `PASCAL_HOME` 目录实现并发隔离

---
## 5. [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad)
- **语言**: Python
- **Stars**: 15,049
- **简介**: A library of agent skills for CAD, CAE and CAM

### AI 总结
**简介**: text-to-cad 是一个面向 CAD、CAE 和 CAM 的 agent 技能库，可从本地项目文件生成、检查、检索、切片并交付 CAD 与机器人描述产物。

**核心功能**:
- **CAD**：根据自然语言或图片请求创建和编辑 CAD 模型，以 STEP 为主要输出，支持导出 STL、3MF 和 GLB
- **CAD Viewer**：在本地浏览器中预览 CAD 和机器人文件
- **step.parts**：查找现成的 STEP 零件，如螺丝、轴承、电机和连接器
- **DXF**：从 Python 源码或 CAD 几何生成 2D DXF 图纸，如轮廓、模板、垫片和切割布局
- **URDF**：编写包含链接、关节、限位、惯性和网格的机器人结构文件
- **SRDF**：为 MoveIt 规划添加语义信息
- **SDF**：用于仿真
- **SRDF / MoveIt2**：支持逆运动学等 MoveIt2 工作流

**技术亮点**: 基于 Python 3.11+，支持 STEP、STL、3MF、URDF、SDF、SRDF 等多种工业与机器人格式，采用模块化 skill 架构，可让 agent 获得针对 CAD、制造、机器人描述、仿真和本地审查的专注工作流。

---
## 6. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 36,650
- **简介**: 38 editorial diagram types for Claude Code, Codex, and Pi. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一套面向 Claude Code、Codex、Pi 等 AI 编程助手的编辑级图表生成技能，提供 39 种自包含 HTML + SVG 图表类型，无需 Figma 或 Mermaid。

**核心功能**:
- 提供 39 种编辑级图表类型，涵盖架构图、流程图、时序图、状态机、ER 图、时间线、泳道图、四象限图、雷达图、飞轮循环图等
- 每种图表提供三种静态变体：极简浅色、极简深色、完整编辑风格，可直接在浏览器打开，无需构建步骤或外部依赖
- 支持语义化模式描述，将行为与布局分离，队列、策略追踪、信任边界等可复用现有类型而无需新增图表种类
- 可将 draw.io、Mermaid 或 Excalidraw 源文件按指定格式、尺寸和细节层级重绘
- 通过读取用户网站，60 秒内匹配品牌配色与风格
- 2.5.10 版本新增十种布局语法：桑基图、鱼骨图、Wardley 地图、看板、用户旅程、部署图、依赖图、UML 类图、故事地图、数据库 Schema

**技术亮点**:
- 纯 HTML + SVG 实现，无 JavaScript、无构建步骤、无外部图片依赖
- 静态输出为默认模式，可选动画用于有序解释场景
- 设计理念强调极简与克制：无阴影、无通用圆角框、强调色仅用于 1–2 个关键视觉焦点，目标信息密度为 4/10
- 兼容 Agent Skills 生态，支持 Claude Code、Codex、Factory Droid、Pi 等多种宿主

---
## 7. [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)
- **语言**: Python
- **Stars**: 103,986
- **简介**: TradingAgents: Multi-Agents LLM Financial Trading Framework

### AI 总结
**简介**: TradingAgents 是一个模拟真实交易公司运作模式的多智能体 LLM 金融交易框架，由 TauricResearch 开源。

**核心功能**:
- 部署多种专业化 LLM 智能体，涵盖基本面分析师、情绪专家、技术分析师、交易员等多个角色
- 支持多提供商 LLM 接入（GPT-5.x、Gemini 3.x、Claude 4.x、Grok 4.x、DeepSeek、Qwen、GLM 等）
- 集成 FRED、Polymarket、Alpha Vantage 等数据源，支持宏观、情绪与市场数据
- 提供 CLI 工具、Docker 支持、回测与决策日志功能
- 支持多语言、检查点恢复（checkpoint resume）及结构化输出

**技术亮点**: 基于 LangGraph 构建多智能体协作架构，支持结构化输出智能体（研究经理、交易员、投资组合经理）；具备前瞻性偏差（look-ahead）过滤、路径遍历防护、可配置 LLM 重试预算及跨平台稳定性；提供 OpenAI 兼容端点接入能力。

---
## 8. [liquidslr/system-design-notes](https://github.com/liquidslr/system-design-notes)
- **语言**: Unknown
- **Stars**: 18,032
- **简介**: Notes of the book System Desgin Interview - An Insider's Guide

### AI 总结
**简介**: 这是《System Design Interview - An Insider's Guide》一书的学习笔记仓库，系统整理了分布式系统设计的核心知识点。

**核心功能**:
- 归纳书中系统设计面试的核心概念与答题框架
- 记录典型系统设计案例（如限流、一致性哈希、缓存、消息队列等）的要点
- 作为面试复习与知识查阅的速查笔记

**技术亮点**: 内容围绕大规模分布式系统设计展开，涵盖可扩展性、可用性、一致性、分区等架构主题，属于纯文档型知识库，不含具体代码实现。

---
## 9. [openai/plugins](https://github.com/openai/plugins)
- **语言**: JavaScript
- **Stars**: 6,213
- **简介**: OpenAI Plugins

### AI 总结
**简介**: OpenAI 官方维护的 Codex 插件示例集合，展示如何通过标准化清单和多种配套文件扩展 Codex 的能力。

**核心功能**:
- 每个插件位于 `plugins/<name>/` 目录下，必须包含 `.codex-plugin/plugin.json` 清单文件
- 支持可选配套结构，包括 `skills/`、`.app.json`、`.mcp.json`、插件级 `agents/`、`commands/`、`hooks.json`、`assets/` 等
- 默认插件市场配置位于 `.agents/plugins/marketplace.json`，API Key 登录用户使用独立的 `.agents/plugins/api_marketplace.json`
- 提供多个丰富示例插件，如 `figma`（设计转代码）、`notion`（知识与会议管理）、`build-ios-apps` / `build-macos-apps`（SwiftUI 开发）、`build-web-apps`（部署/支付/数据库）、`expo`（React Native 与 EAS 工作流）、`netlify`、`remotion`、`google-slides` 等

**技术亮点**: 基于 JavaScript 生态，采用清单驱动的插件架构，结合 Skills 与 MCP（Model Context Protocol）扩展机制，支持市场化的插件分发与发现。

---
## 10. [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2)
- **语言**: JavaScript
- **Stars**: 30,089
- **简介**: Prompt as Code | GPT-Image2 工业级提示词引擎与模板库，530+ 个案例逆向工程，20+ 套工业级模板，并提炼出Skills，持续更新中

### AI 总结
**简介**: 一个面向 GPT-Image2 的工业级提示词引擎与模板库，通过“Prompt as Code”理念将提示词工程化，提供 530+ 逆向工程案例与 20+ 套工业级模板。

**核心功能**:
- **案例库**：收录 544 个逆向工程案例（标注 100% 原创 AI 重写），可直接浏览、复制完整提示词
- **模板库**：20+ 套工业级提示词模板，并提炼为可复用的 Skills，持续更新
- **可视化网站**：提供在线画廊体验，支持大图预览、按风格/场景筛选、Google 登录后测试生成，并可跳回 GitHub 源案例
- **GPT Image 2.5 Spotlight**：新增 Sunburst（精准编辑）与 Flare（快速生成）对比展示，含 4 个真实复现案例及可拖拽分割线对比视图
- **社区与生态**：提供交流群、微信公众号（苍何）更新推送，以及赞助商接入

**技术亮点**:
- **Prompt as Code**：将提示词视为可版本化、可复用的代码资产进行管理
- **多语言支持**：README 提供英文、简体中文、日语版本
- **技术栈**：JavaScript 构建，配套独立可视化站点（gpt-image2.canghe.ai）
- **案例数据化**：每个案例保留原始画廊图片与完整提示词，生成条件与模型 ID 标注规范，演示样例单独标记

---
