---
tags:
  - github-trending
  - daily
date: 2026-09-26
created: 2026-09-26T01:55:42.844Z
---

# 2026-09-26 GitHub Trending Top 10

## 1. [paperclipai/paperclip](https://github.com/paperclipai/paperclip)
- **语言**: TypeScript
- **Stars**: 85,028
- **简介**: The open-source app everyone uses to manage agents at work

### AI 总结
**简介**: Paperclip 是一个开源 AI 智能体编排平台，用于像管理公司一样管理一支 AI 智能体团队，帮助团队围绕业务目标协作运行。

**核心功能**:
- **目标驱动编排**：定义业务目标（如"打造第一的 AI 笔记应用做到 100 万美元 MRR"），雇佣 CEO、CTO、工程师、设计师、营销等任意智能体组建团队，审批策略后一键运行。
- **多智能体兼容**：支持 OpenClaw、Claude Code、Codex、Cursor、Bash、HTTP 等多种智能体/工具，只要能被"心跳"调度即可纳入团队。
- **任务管理式体验**：以类似任务管理器的界面呈现，底层提供组织架构、预算、治理、目标对齐和智能体协调能力。
- **成本与预算监控**：统一仪表盘追踪工作进度与成本，设置预算并强制执行。
- **审批与审查机制**：通过审批、评审门禁和可审计的例程/工作流，让智能体 7×24 自主运行的同时保留人工介入与核查能力。
- **移动端管理**：支持从手机端管理自主运行的业务。

**技术亮点**:
- 采用 **Node.js 服务端 + React UI** 架构。
- 使用 **TypeScript** 开发。
- 以 **MIT 许可证**开源。
- 围绕四大支柱构建：智能体任务管理器、组织架构、训练与基础设施。

---
## 2. [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- **语言**: Python
- **Stars**: 36,948
- **简介**: Official, Anthropic-managed directory of high quality Claude Code Plugins.

### AI 总结
**简介**: Anthropic 官方维护的 Claude Code 高质量插件目录，汇集内部与第三方插件供用户安装使用。

**核心功能**:
- 提供 `/plugins`（Anthropic 内部插件）与 `/external_plugins`（第三方及社区插件）两类插件目录
- 支持通过 `/plugin install {plugin-name}@claude-plugins-official` 或 `/plugin > Discover` 直接安装
- 第三方合作伙伴可通过提交表单申请插件上架，需满足质量与安全标准
- 定义标准化插件结构（含 `plugin.json`、`.mcp.json`、commands、agents、skills 等）
- 支持 skill-bundle 插件（通过 `strict: false` 与显式 `skills` 数组声明无 manifest 的技能包）
- 提供 `renames` 映射机制，实现插件重命名时旧安装的自动迁移

**技术亮点**:
- 插件 `name` 字段为不可变 slug，通过 `displayName` 控制 UI 显示名，避免破坏已安装用户
- 支持 `git-subdir` 源类型，可从仓库子目录提取技能，路径支持多层级嵌套
- 每个技能以 `<plugin-name>:<skill-name>` 形式注册，便于命名空间隔离
- 基于 Python 实现，遵循 Claude Code 官方插件市场规范

---
## 3. [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight)
- **语言**: Python
- **Stars**: 29,845
- **简介**: Hindsight: Agent Memory That Learns

### AI 总结
**简介**: Hindsight 是一个让 AI Agent 能够随时间学习进化的记忆系统，专注于让 Agent 真正"学习"而非仅仅"记住"对话历史。

**核心功能**:
- **长期记忆管理**: 在 LongMemEval 基准测试中达到业界领先水平，在长期记忆任务上表现最优
- **三大核心操作**: 提供 retain（保留）、recall（回忆）、reflect（反思）三种记忆操作
- **多种记忆类型**: 支持观察（observations）、心智模型与知识页面（mental models & knowledge pages）、记忆库（banks）等概念
- **灵活集成**: 支持 LLM Wrapper（仅需 2 行代码）、MCP Server、编码 Agent（Claude Code、Cursor 等）及多种平台集成
- **多 LLM 提供商支持**: 兼容 25+ LLM 提供商（OpenAI、Anthropic、Gemini、Groq、Bedrock、DeepSeek 等），也支持本地 Ollama 部署
- **Python 嵌入式模式**: 无需服务器即可直接嵌入使用

**技术亮点**:
- 基于 Python 开发，提供 Docker 一键部署方案（API 端口 8888，UI 端口 9999）
- 克服了 RAG 和知识图谱等传统技术的缺陷，在长期记忆任务上实现 SOTA 性能
- 基准测试结果由 Virginia Tech Sanghani 中心和华盛顿邮报独立复现验证
- 已在财富 500 强企业和多家 AI 初创公司中投入生产使用
- 提供配套论文（arXiv:2512.12818）、在线基准测试平台及云端服务

---
## 4. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 291,677
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，通过可组合技能与自动触发机制，让 AI 代理在写代码前先完成需求梳理、设计确认与计划制定。

**核心功能**:
- **需求先行**：智能体不会直接写代码，而是先引导用户明确真实目标，逐步梳理出规格说明
- **分块设计确认**：将规格以易于阅读和消化的短片段呈现给用户，获得确认后再继续
- **可执行的实现计划**：生成足够清晰、面向"缺乏判断力且厌恶测试的初级工程师"也能遵循的计划，强调红/绿 TDD、YAGNI 和 DRY 原则
- **子代理驱动开发**：用户确认后启动多子代理流程，逐个完成工程任务并检查、审查其工作，可持续自主推进数小时而不偏离计划
- **自动触发**：技能自动激活，无需额外操作，编码智能体即具备 Superpowers 能力
- **多平台支持**：覆盖 Claude Code、Antigravity、Codex App/CLI、Cursor、Devin CLI、Factory Droid、Gemini CLI、GitHub Copilot CLI、Grok Build CLI、Kimi Code、OpenCode、Pi、Qwen Code、Hermes Agent、Muse 等众多编码工具

**技术亮点**:
- 基于**可组合技能（composable skills）**架构，通过初始指令确保智能体主动调用这些技能
- 采用**子代理驱动开发（subagent-driven-development）**模式，实现任务分发、结果审查与持续推进
- 以 Shell 为主要实现语言，各平台通过插件市场或扩展机制独立安装
- 提供商业支持渠道（sales@primeradiant.com），面向企业级使用场景

---
## 5. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 269,745
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: Matt Pocock 分享的日常真实工程用 AI Agent 技能集，强调小巧、可组合、可自由改造，而非"氛围编程"。

**核心功能**:
- `/grill-me` 与 `/grill-with-docs`：通过追问式对话让 Agent 充分理解需求，解决人机沟通错位问题
- `/triage`：配合工单系统标签进行问题分类
- `/setup-matt-pocock-skills`：每个仓库运行一次，配置 issue 跟踪器（GitHub / Linear / 本地文件）、标签及文档存放位置
- 支持多种编码 Agent（Claude Code、Codex 等），可与任意模型配合使用

**技术亮点**:
- 提供两种安装哲学：Claude Code 插件（只读、自动更新、订阅式）与 skills.sh（复制可编辑文件到项目、可自行魔改）
- 安装器支持按需挑选技能，并指定目标编码 Agent
- 基于数十年工程经验设计，反对 GSD、BMAD、Spec-Kit 等"接管流程"式方案，主张保留开发者控制权
- 主要语言为 Shell

---
## 6. [dream-num/univer](https://github.com/dream-num/univer)
- **语言**: TypeScript
- **Stars**: 18,458
- **简介**: The Office Harness for AI Agents — Spreadsheets, Docs, Slides, Canvas, Relational Tables, and PDF in one runtime.

### AI 总结
**简介**: Univer 是一个开源的高性能 Office SDK，用于在自有产品中嵌入电子表格、文档和演示文稿等办公能力，同时支持 AI Agent 在同一运行时中协同工作。

**核心功能**:
- 支持电子表格、文档、演示文稿、Bases、看板及 PDF（即将推出）等多种办公形态
- 可通过插件架构按需组合功能，或使用预设快速启动
- 提供统一的 Facade API，可在浏览器和 Node.js 环境中运行
- 支持服务端工作簿/文档处理，与浏览器端采用相同架构
- 可通过自定义插件、命令、服务和 UI 组件扩展行为
- 支持内容跨工具组合嵌入，链接数据和引用可同步更新
- 支持人与 AI Agent 在同一文件中协作

**技术亮点**: 基于 TypeScript 开发，采用 Canvas 渲染和插件化架构，内置公式引擎，提供跨浏览器与 Node.js 的统一 Facade API，实现存储与计算的共享运行时。

---
## 7. [anthropics/skills](https://github.com/anthropics/skills)
- **语言**: Python
- **Stars**: 178,330
- **简介**: Public repository for Agent Skills

### AI 总结
**简介**: Anthropic 官方开源的 Agent Skills 仓库，提供 Claude 动态加载的技能示例与规范，涵盖创意设计、技术开发、企业工作流和文档处理等场景。

**核心功能**:
- 提供多种预置技能示例，包括艺术/音乐/设计、Web 应用测试、MCP 服务器生成、企业通信与品牌等
- 包含 Claude 文档能力的底层实现技能：docx、pdf、pptx、xlsx（source-available，非开源）
- 提供 Agent Skills 规范（`./spec`）和技能模板（`./template`），支持自定义技能开发
- 支持通过 Claude Code 插件市场、Claude.ai 和 Claude API 三种方式安装使用
- 每个技能为独立文件夹，包含 `SKILL.md`（YAML frontmatter + 指令），结构简洁易扩展

**技术亮点**: 基于 Python；技能以文件夹为单位、通过 `SKILL.md` 声明式定义（仅需 `name` 和 `description` 两个字段）；采用插件市场机制分发（`/plugin marketplace add anthropics/skills`）；多数技能为 Apache 2.0 开源，文档类技能为 source-available 供开发者参考生产级实现。

---
## 8. [androoAGI/starnet](https://github.com/androoAGI/starnet)
- **语言**: JavaScript
- **Stars**: 491
- **简介**: A living pixel-art station where real AI agents do real work. Local-first desktop agent harness - bring your own key, watch your crew actually run.

### AI 总结
**简介**: StarNet 是一个本地优先的桌面 AI 智能体工作台，将真实运行的 AI 智能体组织进一座像素风太空站，站内布局直接映射为智能体的工作流与权限。

**核心功能**:
- **多智能体协作**: 创建具有不同角色、人格和装备的智能体，可同时并发运行，每个智能体拥有独立工作区、记忆、转录记录和受限权限。
- **自带模型密钥**: 支持粘贴 OpenRouter 密钥，或登录 Anthropic、OpenAI、Google 等账号，密钥存储于操作系统钥匙串，不进入前端。
- **跨渠道消息接入**: 可将智能体接入 Telegram、Discord、Slack、Signal、Matrix，远程与站点交互。
- **Night Shift 无人值守**: 站点持续运行，智能体在明确可调的权限范围内工作，所有离线操作均有日志可审查。
- **配方、技能与定时任务**: 支持启动多步骤配方、授予可复用技能、按 cron 计划执行任务。
- **任务简报与 OUTBOX**: 遇到歧义时通过已连接渠道提出具体选项问题；交付物以真实文件形式落入 OUTBOX。
- **MCP 连接器与语音**: 支持接入 MCP 服务器及 OAuth 连接器；支持按住说话输入与统一语音输出。
- **真实账本**: 花费、预算与运行历史持久化到磁盘，如实展示。

**技术亮点**: 采用本地 Node sidecar 流式处理模型调用；工具执行经过显式能力与授权检查；智能体记忆、转录、花费、任务和调度均持久化到磁盘；像素站点的视觉呈现是对实时运行时状态的投影，界面绝不宣称 harness 无法证明的状态。基于 JavaScript 开发，支持 Windows 与 macOS，遵循 MIT 协议。

---
## 9. [derv82/wifit3](https://github.com/derv82/wifit3)
- **语言**: Python
- **Stars**: 939
- **简介**: Wifite but USB-only & cross-platform.

### AI 总结
**简介**: wifit3 是一款仅依赖 USB 无线网卡、跨 Linux/Windows/macOS 三平台的独立 Wi-Fi 安全审计工具，可视为 Wifite 的现代化重写版。

**核心功能**:
- **侦察与分析**：多网卡聚合抓包、2.4/5GHz 实时跳频扫描、AP/客户端厂商指纹识别、隐藏网络（VAP）去隐匿、实时数据包速率面板。
- **WPA/WPA2 攻击**：握手包被动嗅探与定向去认证捕获，支持导出 `.pcap`/`.hc22000`；PMKID 主动关联与被动嗅探。
- **WPA3 降级攻击**：EvilTwin 克隆 AP，通过 CSA、BTM、去认证驱逐客户端以捕获握手包，支持单/多网卡。
- **WPS 恢复套件**：PixieDust（Null/Static Secret 两种模式）、PushButton 按键明文 PSK 提取、可断点续跑的 PIN 暴力破解（含已知 PIN 库与锁死监控）。
- **WEP 套件**：纯 Python 实现的 ARP 重放、ChopChop、假认证与 PTW 密钥恢复。

**技术亮点**:
- 内置无线协议栈，绕过内核驱动版本兼容问题与 Windows NDIS，实现三平台一致体验。
- 零运行时依赖：不依赖 `aircrack-ng`/`reaver`，纯 Python 实现，基于 PyUSB 与 Textual 库。
- 使用 Astral `uv` 管理依赖，支持 PyInstaller 打包为独立可执行文件，开箱即用。
- 覆盖 Atheros、MediaTek、Realtek、Ralink 等主流芯片组，兼容大量常见 USB 网卡（如 ALFA 系列、Panda 系列）。

---
## 10. [kelseyhightower/kubernetes-the-hard-way](https://github.com/kelseyhightower/kubernetes-the-hard-way)
- **语言**: Unknown
- **Stars**: 50,128
- **简介**: Bootstrap Kubernetes the hard way. No scripts.

### AI 总结
**简介**: 一个通过手动方式从零搭建 Kubernetes 集群的教程项目，旨在帮助学习者深入理解集群引导的每个环节，而非追求自动化。

**核心功能**:
- 提供 13 个循序渐进的实验步骤，涵盖从环境准备、证书生成、etcd 集群引导到控制平面与工作节点搭建的完整流程
- 指导搭建一个包含单节点控制平面和两个工作节点的基础 Kubernetes 集群
- 涵盖 kubectl 远程访问配置、Pod 网络路由配置及集群冒烟测试

**技术亮点**:
- 全程手动操作，不使用任何自动化脚本，强调对每个引导步骤的理解
- 涉及核心组件：Kubernetes v1.32.x、containerd v2.1.x、CNI v1.6.x、etcd v3.6.x
- 需要 4 台 ARM64 或 AMD64 架构的机器（1 台 Jumpbox + 1 控制平面 + 2 工作节点）
- 采用 CC BY-NC-SA 4.0 许可协议，明确声明不适用于生产环境

---
