---
tags:
  - github-trending
  - daily
date: 2026-07-24
created: 2026-07-24T01:55:44.130Z
---

# 2026-07-24 GitHub Trending Top 10

## 1. [block/buzz](https://github.com/block/buzz)
- **语言**: Rust
- **Stars**: 7,029
- **简介**: A hive mind communication platform

### AI 总结
**简介**: Buzz 是一个自托管的团队协作平台，让人类和 AI 智能体在同一个工作空间中共同工作，基于 Nostr 协议的事件日志架构。

**核心功能**:
- **人机协作空间**：人类和 AI 智能体作为平等的频道成员，共享相同的身份模型和审计追踪
- **事件日志驱动**：所有消息、反应、工作流步骤、代码审查和 Git 事件都是签名事件，形成统一的审计记录
- **智能体集成**：AI 智能体可以打开仓库、发送补丁、审查代码、运行工作流、编排其他智能体、创建频道等
- **上下文搜索**：跨对话、补丁、工作流运行和审批的统一搜索
- **频道管理**：快速创建公共/私有频道，将功能分支转化为协作房间
- **媒体评论**：在视频等媒体上锚定帧级评论
- **自托管部署**：默认单中继部署，支持多租户托管部署

**技术亮点**: 使用 Rust 编写，基于 Nostr 协议的事件日志架构，统一的身份模型（人类和智能体使用相同类型的密钥签名），支持 Postgres、Redis 和对象存储的后端架构。

---
## 2. [koala73/worldmonitor](https://github.com/koala73/worldmonitor)
- **语言**: TypeScript
- **Stars**: 71,699
- **简介**: Real-time global intelligence dashboard. AI-powered news aggregation, geopolitical monitoring, and infrastructure tracking in a unified situational awareness interface

### AI 总结
**简介**: World Monitor 是一个基于 AI 的实时全球情报仪表盘，聚合新闻、地缘政治监控和基础设施跟踪，提供统一态势感知界面。

**核心功能**:
- AI 驱动的新闻聚合与实时情报更新
- 地缘政治事件监控与可视化
- 基础设施状态跟踪
- 多领域变体支持（科技、金融、大宗商品、能源等）
- 跨平台桌面应用与 Web 访问

**技术亮点**: 采用 TypeScript 构建，提供 npm、PyPI、RubyGems、Go 等多语言 SDK，支持 Windows、macOS、Linux 桌面端，集成 MCP 协议，采用 AGPL v3 开源许可。

---
## 3. [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos)
- **语言**: Python
- **Stars**: 33,091
- **简介**: Kronos: A Foundation Model for the Language of Financial Markets

### AI 总结
**简介**: Kronos 是首个面向金融 K 线（OHLCV 数据）的开源基础模型，基于全球 45 家交易所的数据训练。

**核心功能**:
- 支持金融 K 线序列的预测与量化分析。
- 提供多尺寸预训练模型（Kronos-mini、small、base、large），适配不同计算需求。
- 附带在线 Demo，可可视化 BTC/USDT 未来 24 小时预测结果。

**技术亮点**:
- 采用两阶段框架：专用分词器将连续多维度 K 线数据量化为分层离散 token，再通过自回归 Transformer 进行预训练。
- 所有模型均开源在 Hugging Face，支持微调脚本。

---
## 4. [Pumpkin-MC/Pumpkin](https://github.com/Pumpkin-MC/Pumpkin)
- **语言**: Rust
- **Stars**: 8,946
- **简介**: Empowering everyone to host fast and efficient Minecraft servers.

### AI 总结
**简介**: 一个用 Rust 构建的高性能、可定制 Minecraft 服务器，致力于提供快速、安全、兼容性强的游戏体验。

**核心功能**:
- 支持 Java 版和基岩版（开发中）最新协议
- 提供区块加载（支持三种模式）、世界保存、光照、实体生成等世界管理功能
- 实现玩家移动、动画、背包、经验、饥饿、副手等完整玩家交互
- 支持非生物实体、实体效果、Boss、村民等实体系统（部分 W.I.P）
- 集成 Bungeecord 和 Velocity 代理支持
- 提供 RCON、Query、命令、权限、翻译等服务器管理功能
- 通过 TOML 配置文件实现高度可定制化

**技术亮点**: 采用 Rust 语言开发，利用多线程技术最大化性能和效率；遵循原版游戏机制，同时注重安全性（防范已知安全漏洞）；为插件开发提供基础框架。

---
## 5. [citrolabs/ego-lite](https://github.com/citrolabs/ego-lite)
- **语言**: JavaScript
- **Stars**: 1,700
- **简介**: The best browser for both you and your AI agents work in parallel.

### AI 总结
**简介**: ego lite 是一款专为人类用户与 AI 代理并行工作而设计的浏览器，让代理在独立空间中运行任务，同时用户标签页保持独立。

**核心功能**:
- **代理专用空间**: 每个 AI 代理拥有完全隔离的工作空间，用户浏览不受干扰，可随时查看或接管代理运行
- **并行多任务处理**: 支持多个代理或任务在同一浏览器内同时运行，互不干扰
- **一键数据迁移**: 首次启动时可将 Chrome 数据（登录信息、Cookie、扩展、书签）迁移至 ego lite，代理可直接使用真实登录状态
- **自然语言指令**: 通过 `/ego-browser` 命令用自然语言描述任务，代理自动执行并反馈结果
- **代码基础架构**: 暴露 JavaScript 函数供代理直接调用，比传统 CLI 方式复杂任务速度提升 2.5 倍，减少 token 消耗

**技术亮点**: 基于 JavaScript 实现，采用代码驱动而非 CLI 驱动的架构，代理通过直接调用 JavaScript 函数完成多步任务，显著提升效率和成功率。

---
## 6. [chrislgarry/Apollo-11](https://github.com/chrislgarry/Apollo-11)
- **语言**: Assembly
- **Stars**: 71,126
- **简介**: Original Apollo 11 Guidance Computer (AGC) source code for the command and lunar modules.

### AI 总结
**简介**: 该项目是阿波罗11号指令舱和登月舱的原始阿波罗制导计算机（AGC）源代码，以汇编语言编写，由虚拟AGC和MIT博物馆数字化，旨在作为原始代码的存档仓库。

**核心功能**:
- 提供指令舱（Comanche055）和登月舱（Luminary099）的AGC完整源代码
- 支持多语言翻译的README文档（超过30种语言）
- 接受针对转录与原始扫描件差异的PR贡献

**技术亮点**: 基于yaYUL汇编器编译，代码源自MIT博物馆的硬拷贝数字化图像，由Margaret H. Hamilton领导开发，属于公共领域代码。

---
## 7. [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)
- **语言**: TypeScript
- **Stars**: 27,279
- **简介**: Never stop coding. Free MIT AI gateway: one endpoint, 290+ providers (90+ free), 500+ models — Kimi, Claude, GPT, OpenAI, Gemini, GLM, DeepSeek, MiniMax. Works with Claude Code, Codex, Cursor, OpenCode, Cline & Copilot. Quota-aware auto-fallback, RTK+Caveman compression saves 15-95% tokens, MCP/A2A, Desktop/PWA. Built by 500+ contributors

### AI 总结
**简介**: OmniRoute 是一个免费的开源 AI 网关，通过单个端点连接 250 多家 AI 提供商（其中 90 多家免费），支持 500 多个模型，旨在让开发者无缝使用各种 AI 工具且无需担心限额。

**核心功能**:
- **统一接入**: 通过一个端点即可访问 Claude、GPT、Gemini、Kimi、DeepSeek 等 250+ 提供商和 500+ 模型。
- **智能路由与自动回退**: 内置 18 种路由策略，当某个提供商达到配额限制时自动切换到备用提供商，确保服务不中断。
- **极致压缩节省 Token**: 采用 RTK + Caveman 压缩技术，可节省 15-95% 的 Token 消耗，大幅降低成本。
- **海量免费额度**: 聚合各免费层，每月可获得约 16 亿免费 Token（首月最高约 21 亿）。
- **广泛兼容性**: 兼容 Claude Code、Codex、Cursor、Cline、Copilot 等主流编码代理和 CLI 工具。
- **多平台运行**: 提供桌面应用（Electron）、PWA 网页版、Docker 镜像和 npm 包，支持 CLI、MCP 和 A2A 协议。
- **社区驱动**: 由 500 多名贡献者共同构建，社区活跃。

**技术亮点**: 使用 TypeScript 开发，采用 MIT 开源协议。核心架构为网关模式，集成了配额感知的自动回退、多策略路由和高效的 Token 压缩算法。

---
## 8. [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)
- **语言**: Python
- **Stars**: 69,462
- **简介**: A curated list of awesome Claude Skills, resources, and tools for customizing Claude AI workflows

### AI 总结
**简介**: 一个精选的 Claude Skills 资源合集，提供超过 1000 个生产就绪的实用技能和插件，用于定制 Claude AI 工作流，并支持连接 500+ 应用实现自动化操作。

**核心功能**:
- 提供涵盖文档处理、开发工具、数据分析、商业营销等 10 大类的丰富技能库
- 内置 `connect-apps` 插件，让 Claude 能执行发送邮件、创建 GitHub Issue、发布 Slack 等真实操作
- 支持 Claude Code、Claude.ai、OpenAI Codex、Cursor、Gemini CLI 等多种 AI 代理
- 技能采用渐进式加载机制，每个技能仅占用约 100 tokens 的上下文窗口

**技术亮点**:
- 基于 Composio 实现 500+ 应用的无缝认证和连接
- 遵循 Anthropic 发布的开放技能标准（SKILL.md + YAML 元数据）
- 与 MCP 服务器和工具形成三层架构：MCP 负责访问、工具负责动作、技能定义工作流

---
## 9. [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad)
- **语言**: JavaScript
- **Stars**: 10,022
- **简介**: A collection of agent skills for CAD, robotics and hardware design

### AI 总结
**简介**: 一个面向 CAD、机器人及硬件设计智能体的技能库，支持通过自然语言或图像生成/编辑 CAD 模型、机器人描述文件等。

**核心功能**:
- **CAD 生成与编辑**: 通过自然语言或图像请求创建/编辑 CAD 模型，支持导出 STEP、STL、3MF、GLB 格式
- **CAD 预览**: 在本地浏览器中预览 CAD、G-code 及机器人文件
- **标准件查找**: 查找螺丝、轴承、电机、连接器等现成 STEP 标准件
- **2D DXF 绘图**: 从 Python 源码或 CAD 几何创建 2D DXF 图纸（如轮廓、模板、垫片）
- **机器人描述文件**: 创建 URDF（含连杆、关节、惯性参数）、SRDF（MoveIt 规划组）和 SDF（仿真模型/世界）
- **制造集成**: 验证 DXF/STEP 文件并上传至 SendCutSend；将网格文件切片为 FDM G-code
- **3D 打印控制**: 在 Bambu Lab 打印机上干运行、上传及启动打印任务

**技术亮点**:
- 基于 JavaScript/Python 构建，通过模块化技能包实现 CAD、机器人、仿真、制造全流程覆盖
- 支持 STEP/STL/3MF/URDF/SDF/SRDF 等多种工业标准格式的互操作
- 集成实际制造服务（SendCutSend）和 3D 打印设备（Bambu Lab）的端到端工作流

---
## 10. [agegr/pi-web](https://github.com/agegr/pi-web)
- **语言**: TypeScript
- **Stars**: 2,383
- **简介**: Web UI for the pi coding agent

### AI 总结
**简介**: Pi Web 是 pi coding agent 的本地 Web UI，提供会话浏览、实时聊天、模型配置、技能管理和项目文件预览等功能。

**核心功能**:
- **会话浏览与管理**: 按项目浏览历史对话，支持从早期消息继续或分支会话，切换 Git 工作树。
- **实时聊天与文件预览**: 在浏览器中与 agent 实时交互，同时浏览项目文件并预览源代码、文档、图片、音频和 PDF。
- **模型与技能配置**: 通过 Web UI 管理模型、登录/API 密钥、模型测试和技能开关，无需终端操作。
- **会话状态可视化**: 清晰展示上下文使用量、成本、压缩状态和系统提示详情。

**技术亮点**:
- 基于 TypeScript 开发，使用 Next.js 框架。
- 支持 HTTP 代理环境变量，适用于需要代理的网络环境。
- 通过 SSE 事件驱动 agent 会话和实时通信。

---
