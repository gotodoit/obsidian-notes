---
tags:
  - github-trending
  - daily
date: 2026-08-03
created: 2026-08-03T01:55:43.805Z
---

# 2026-08-03 GitHub Trending Top 10

## 1. [microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners)
- **语言**: Jupyter Notebook
- **Stars**: 59,140
- **简介**: 12 Weeks, 24 Lessons, AI for All!

### AI 总结
**简介**: 微软推出的面向初学者的12周、24课时人工智能课程，涵盖实用教程、测验和实验，轻松入门AI领域。

**核心功能**:
- 系统化课程：12周24课时，从基础到进阶全面覆盖AI核心概念
- 实践导向：包含实用课程、测验和动手实验，支持TensorFlow和PyTorch等主流工具
- 多语言支持：提供50+种语言翻译版本，通过GitHub Action自动更新
- 社区互动：支持Binder在线运行、Discord/Gitter社区交流，欢迎PR贡献

**技术亮点**: 基于Jupyter Notebook开发，课程内容包含可视化草图笔记（Sketchnotes），支持稀疏检出（sparse checkout）优化克隆体验，采用自动化翻译工作流维护多语言版本。

---
## 2. [usekaneo/kaneo](https://github.com/usekaneo/kaneo)
- **语言**: TypeScript
- **Stars**: 6,197
- **简介**: 🎯 All you need. Nothing you don't. Open source project management that works for you, not against you.

### AI 总结
**简介**: Kaneo 是一款开源、自托管的项目管理工具，秉持“少即是多”的理念，提供简洁高效的界面，帮助团队专注于实际工作而非工具本身。

**核心功能**:
- **简洁界面**: 去除冗余按钮和通知，聚焦核心工作流
- **自托管部署**: 支持 Docker Compose 一键部署，数据完全由用户掌控
- **高性能体验**: 注重性能优化，操作流畅快速
- **开源免费**: 采用 MIT 许可证，可自由使用和修改

**技术亮点**:
- 基于 TypeScript 构建，类型安全可靠
- 提供 drim CLI 工具，实现自动化部署（含 HTTPS、数据库配置）
- 采用容器化架构（Kaneo + PostgreSQL），支持 `docker compose up` 快速启动
- 支持通过环境变量灵活配置，适配不同部署场景

---
## 3. [lyogavin/airllm](https://github.com/lyogavin/airllm)
- **语言**: Jupyter Notebook
- **Stars**: 25,720
- **简介**: AirLLM 70B inference with single 4GB GPU

### AI 总结
**简介**: AirLLM 是一个大幅降低大语言模型推理内存占用的工具，让 70B 参数模型可在单张 4GB 显卡上运行，无需量化、蒸馏或剪枝。

**核心功能**:
- 支持超大规模模型推理：405B Llama 3.1（8GB）、DeepSeek-V3 671B（~12GB）、Kimi K3 2.8T（<4GB）
- 通过逐专家流式加载（per-expert streaming）高效运行稀疏 MoE 模型
- 支持 FP8 模型格式及 8bit/4bit 量化
- 提供 AutoModel 接口，自动检测模型类型，简化调用
- 支持 CPU 推理及非分片模型加载
- 兼容主流模型架构：Llama 3.x/4、Qwen2.5/3、DeepSeek V2/V3、ChatGLM、Mistral、Baichuan、InternLM、Phi-4、Gemma 等
- 支持 MacOS 运行 70B 模型

**技术亮点**: 采用分层/逐专家流式加载机制，将模型权重按需从磁盘加载到显存，实现内存占用与模型规模解耦；集成预取技术（prefetching）重叠加载与计算过程，提升约 10% 推理速度；支持模型压缩技术，实现 3 倍推理加速。

---
## 4. [iv-org/invidious](https://github.com/iv-org/invidious)
- **语言**: Crystal
- **Stars**: 21,995
- **简介**: Invidious is an alternative front-end to YouTube

### AI 总结
**简介**: Invidious 是一个开源的 YouTube 替代前端，旨在提供轻量、无广告、无追踪的观看体验，使用 Crystal 语言开发。

**核心功能**:
- 轻量级设计，无需 JavaScript 即可使用
- 无广告、无追踪，支持亮/暗主题
- 独立于 Google 的订阅系统，支持频道通知
- 音频模式（支持移动端后台播放）
- 支持 Reddit 评论、多语言界面
- 数据导入导出：支持从 YouTube、NewPipe、FreeTube 导入订阅和观看历史，并导出至 NewPipe/FreeTube
- 提供开发者 API，支持嵌入式视频播放

**技术亮点**:
- 使用 Crystal 语言编写，不依赖官方 YouTube API
- 无 Contributor License Agreement (CLA)，采用 AGPLv3 许可证
- 支持自托管，提供公共实例列表，并推荐配合 Privacy Redirect 等浏览器扩展使用

---
## 5. [codecrafters-io/build-your-own-x](https://github.com/codecrafters-io/build-your-own-x)
- **语言**: Markdown
- **Stars**: 534,922
- **简介**: Master programming by recreating your favorite technologies from scratch.

### AI 总结
**简介**: 这是一个汇集了从零开始重建各类热门技术的优质教程清单，帮助开发者通过动手实践深入理解技术原理。

**核心功能**:
- 覆盖 30+ 技术领域，包括 3D 渲染器、AI 模型、数据库、Docker、操作系统、编程语言、Web 浏览器等
- 每个领域提供多语言、多平台的逐步教程链接（如 C++、Java、Python、Go、JavaScript 等）
- 按技术类别分类组织，方便快速定位感兴趣的主题
- 所有教程均为精选的高质量、可实操的指南

**技术亮点**: 以“费曼学习法”为核心理念（“无法创造的东西，就无法真正理解”），强调通过重建技术来掌握编程，教程涵盖从底层系统（如内存分配器、网络栈）到上层应用（如搜索引擎、文本编辑器）的完整技术栈。

---
## 6. [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill)
- **语言**: PowerShell
- **Stars**: 13,618
- **简介**: Reverse Engineering / Authorized Penetration Testing / Security Research Skill Router Pack AI-powered routing + On-demand toolchain bootstrapping + Self-evolving knowledge base Supports Claude Code, Kiro, Cursor, Cline, and other AI coding clients 逆向/渗透/安全技能路由包 - AI 自动路由 + 按需自举工具链 + 自动进化经验库 | 支持 Claude Code / Kiro / Cursor / Cline 等代码 AI 客户端

### AI 总结
**简介**: reverse-skill 是一个面向 AI 编程助手的网络安全技能路由包，帮助 AI 在遇到逆向工程、渗透测试和安全研究任务时自动选择正确的方法论和工具链。

**核心功能**:
- **智能路由**: 根据任务类型（APK、二进制、JS 加密、CTF、渗透目标）自动匹配对应的技能路径和方法论
- **工具链自举**: 自动检测并索引本机已安装的逆向/渗透工具（jadx、apktool、Frida、IDA、BurpSuite 等），按需引导 AI 使用正确工具
- **经验库进化**: 通过时间线和证据链记录，将每次任务的发现、结论和路径沉淀为可复用的知识库
- **多客户端兼容**: 支持 Claude Code、Kiro、Cursor、Cline、Codex CLI 等主流 AI 编程客户端
- **跨平台支持**: 提供 Windows、Linux/macOS、Kali Linux 专属的脚本和配置

**技术亮点**: 
- 采用 PowerShell 为主脚本语言，辅以 Python、Node.js、Bash 等构建多语言工具链
- 基于"路由矩阵"架构（MASTER-ROUTING + routing.md），实现从任务输入到报告输出的全流程标准化
- 内置 Ops 契约（授权确认、网络配置、范围界定），确保测试过程合法合规
- 集成 IDA Pro、radare2、Ghidra 等主流逆向工具，支持 Docker 容器化部署

---
## 7. [different-ai/openwork](https://github.com/different-ai/openwork)
- **语言**: TypeScript
- **Stars**: 20,352
- **简介**: The open-source alternative to Claude Cowork (powered by opencode)

### AI 总结
**简介**: OpenWork 是一个免费开源的桌面应用，作为 Claude Cowork 和 Codex 的开源替代品，用于跨工具共享 AI 工作流。

**核心功能**:
- 通过 OpenWork MCP 将技能、插件、MCP 连接及 Google Workspace / Microsoft 365 能力接入 Codex、Claude Code、Cursor 等 AI 代理
- 提供 `search_capabilities` 和 `execute_capability` 两个 MCP 工具，支持在任何兼容代理中直接使用
- 桌面应用提供专用工作区，但非必需——可直接从现有代理中使用
- OpenWork Den 管理控制平面：支持大规模推理配置、团队成员与访问管理、桌面策略设置、技能/插件市场发布与分配
- 支持导入 Anthropic 兼容插件，并通过 OpenWork MCP 提供其技能和远程 MCP

**技术亮点**:
- TypeScript 构建，基于 Electron 桌面框架
- 采用远程 MCP 服务器架构（`https://api.openworklabs.com/mcp/agent`），支持 OAuth 认证
- 开发模式支持多 worktree 并行运行（`pnpm dev:worktree`），自动派生独立配置文件、动态分配 CDP 和 Vite 端口，并默认启用模拟密钥链避免 macOS 系统弹窗阻塞

---
## 8. [microsoft/generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners)
- **语言**: Jupyter Notebook
- **Stars**: 114,816
- **简介**: 21 Lessons, Get Started Building with Generative AI

### AI 总结
**简介**: 微软出品的面向初学者的生成式人工智能入门课程，包含21个系统化实战教程。

**核心功能**:
- 21个系统化课程，涵盖生成式AI核心概念、提示工程、文本生成、图像生成、低代码AI应用等主题
- 配套Jupyter Notebook代码示例和实战项目，支持动手实践
- 提供Azure OpenAI等云服务配置指南，帮助开发者快速部署AI应用
- 支持50+种语言翻译，通过GitHub Action自动更新多语言文档
- 活跃的社区支持，提供Discord讨论组和PR欢迎机制

**技术亮点**: 基于Jupyter Notebook的交互式学习体验，覆盖Python编程、OpenAI API调用、LangChain框架等主流技术栈，课程内容紧跟生成式AI最新发展。

---
## 9. [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)
- **语言**: Python
- **Stars**: 64,754
- **简介**: Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees.

### AI 总结
**简介**: Agent-Reach 是一个为 AI Agent 提供互联网访问能力的开源 CLI 工具，让 Agent 能够读取和搜索 Twitter、Reddit、YouTube、GitHub、Bilibili、小红书等平台内容，无需支付 API 费用。

**核心功能**:
- **多平台覆盖**: 支持网页阅读、YouTube 字幕提取与搜索、RSS 订阅、全网语义搜索、GitHub 仓库访问、Twitter/X 推文读取与搜索、B站搜索与视频详情、Reddit 帖子与评论、Facebook/Instagram/小红书/LinkedIn/V2EX/雪球/小宇宙等平台
- **零配置快速上手**: 用户只需将安装指令复制给 Agent，即可自动完成安装配置，支持一句话更新
- **多后端自动切换**: 每个平台配备「首选 + 备选」多后端路由，接入方式失效时自动切换，用户无感知
- **自带诊断工具**: `agent-reach doctor` 命令一键检查各平台连通性并给出修复建议
- **安全隐私保护**: Cookie 仅存本地、代码完全开源、支持安全模式安装（不自动装系统包）

**技术亮点**: 基于 Python 3.10+，采用 MCP 接入实现免费语义搜索，通过 OpenCLI 复用浏览器登录态解决平台封锁问题，兼容所有能执行命令行的 Agent（Claude Code、OpenClaw、Cursor、Windsurf 等），MIT 开源协议。

---
## 10. [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory)
- **语言**: TypeScript
- **Stars**: 11,108
- **简介**: TencentDB Agent Memory is a team-level memory hub for AI Agents — turning conversations, docs, and code into four reusable memory assets (Chat Memory, Skill, LLM-Wiki, Code-Graph) that are governed, shared, and equipped across agents and frameworks.

### AI 总结
**简介**: TencentDB Agent Memory 是一个团队级 AI Agent 记忆中枢，将对话、文档和代码转化为四种可复用的记忆资产（对话记忆、技能、LLM 知识库、代码图谱），支持跨 Agent 和框架的治理、共享与装备。

**核心功能**:
- **符号化短期记忆**: 将繁重的工具日志压缩为紧凑的 Mermaid 符号，显著降低 Token 消耗并提升任务成功率
- **分层长期记忆**: 将碎片化对话蒸馏为结构化的人物画像和场景，取代扁平化向量存储
- **四种记忆资产**: 支持 Chat Memory（对话记忆）、Skill（技能）、LLM-Wiki（知识库）、Code-Graph（代码图谱）
- **跨会话经验复用**: 帮助 Agent 学习工作流程、保留任务上下文并复用过往经验

**技术亮点**:
- **记忆分层架构**: 采用统一的分层范式——短期上下文分层（原始输出→步骤摘要→Mermaid 画布）和长期个性化分层（L0 对话→L1 原子事实→L2 场景→L3 人物画像）
- **渐进式披露机制**: Agent 仅需关注顶层结构，通过 `node_id` 按需下钻至底层细节
- **显著性能提升**: 集成 OpenClaw 后 Token 消耗降低最高 61.38%，通过率提升 51.52%，PersonaMem 准确率从 48% 提升至 76%
- **TypeScript 实现**: 基于 Node.js（≥22.16），支持 npm 包分发，MIT 开源协议

---
