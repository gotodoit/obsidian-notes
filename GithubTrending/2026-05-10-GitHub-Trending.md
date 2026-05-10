---
tags:
  - github-trending
  - daily
date: 2026-05-10
created: 2026-05-10T01:55:44.590Z
---

# 2026-05-10 GitHub Trending Top 10

## 1. [anthropics/financial-services](https://github.com/anthropics/financial-services)
- **语言**: Python
- **Stars**: 17,446
- **简介**: 

### AI 总结
**简介**: 这是一个为金融服务行业（投资银行、股权研究、私募股权和财富管理）设计的Claude参考代理、技能和数据连接器集合，支持作为Cowork插件或通过Managed Agents API部署。

**核心功能**:
- **覆盖与咨询**: 提供Pitch Agent（创建品牌推介材料）和Meeting Prep Agent（生成客户会议简报包）
- **研究与建模**: 包括Market Researcher（行业分析）、Earnings Reviewer（财报审查与模型更新）和Model Builder（DCF/LBO/三表模型）
- **基金管理与财务运营**: 包含Valuation Reviewer（估值审查）、GL Reconciler（总账对账）、Month-End Closer（月末结账）和Statement Auditor（报表审计）
- **运营与入职**: 提供KYC Screener（文档解析与规则检查）

**技术亮点**: 
- 基于Python开发，采用“同一来源两种方式”架构（Cowork插件 + Managed Agents API）
- 每个代理插件自包含（捆绑所需技能），支持独立安装或垂直技能包安装
- 包含完整的仓库布局（代理插件、垂直插件、合作伙伴插件、管理代理食谱和部署脚本）

---
## 2. [bytedance/UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop)
- **语言**: TypeScript
- **Stars**: 31,431
- **简介**: The Open-Source Multimodal AI Agent Stack: Connecting Cutting-Edge AI Models and Agent Infra

### AI 总结
**简介**: bytedance/UI-TARS-desktop 是一个开源的多模态 AI Agent 堆栈，包含 Agent TARS（通用多模态 AI Agent 命令行/Web 工具）和 UI-TARS Desktop（基于 UI-TARS 模型的桌面 GUI Agent 应用），旨在通过连接前沿 AI 模型与 Agent 基础设施，实现接近人类的任务完成方式。

**核心功能**:
- **Agent TARS**: 提供 CLI 和 Web UI，集成多模态 LLM 和 MCP 工具，支持流式输出、运行时设置、事件流查看器和 AIO agent Sandbox 隔离执行环境。
- **UI-TARS Desktop**: 提供本地和远程计算机及浏览器操作功能，支持 UI-TARS-1.5 模型，具备远程控制、浏览器操作和 GUI 自动化能力。
- **跨平台 SDK**: 提供 UI TARS SDK，用于构建 GUI 自动化 Agent。
- **云部署**: 支持云端部署教程，便于扩展和使用。

**技术亮点**: 采用 TypeScript 开发，结合多模态 LLM（如 UI-TARS-1.5）、MCP 工具集成、流式处理、沙箱隔离执行环境（AIO agent Sandbox），以及远程操作技术，实现跨终端、浏览器和产品的智能自动化。

---
## 3. [rohitg00/agentmemory](https://github.com/rohitg00/agentmemory)
- **语言**: TypeScript
- **Stars**: 3,459
- **简介**: #1 Persistent memory for AI coding agents based on real-world benchmarks

### AI 总结
**简介**: agentmemory 是一款基于真实世界基准测试构建的持久化内存库，专为 AI 编码代理设计，使其能够跨会话记住所有上下文，避免重复解释。

**核心功能**:
- **持久化记忆**: 为 Claude Code、Cursor、Gemini CLI 等编码代理提供长期记忆存储，支持 MCP 客户端集成。
- **混合搜索**: 结合置信度评分、生命周期管理、知识图谱与混合搜索，扩展了 Karpathy 的 LLM Wiki 模式。
- **零外部依赖**: 无需外部数据库，内置 51 个 MCP 工具和 12 个自动钩子，实现 95.2% 的检索召回率 (R@5) 并减少 92% 的 token 消耗。
- **多代理兼容**: 通过钩子、MCP 或 REST API 与所有主流编码代理（如 Claude Code、Cursor、Codex CLI 等）协同工作。

**技术亮点**: 基于 iii 引擎构建，采用 TypeScript 开发，提供 827 个通过测试，支持实时查看器和 iii 控制台。

---
## 4. [datawhalechina/hello-agents](https://github.com/datawhalechina/hello-agents)
- **语言**: Python
- **Stars**: 45,712
- **简介**: 📚 《从零开始构建智能体》——从零开始的智能体原理与实践教程

### AI 总结
**简介**: 从零开始的智能体（AI Agent）原理与实践教程，系统讲解如何构建AI原生智能体。

**核心功能**:
- 覆盖智能体核心原理、经典范式（ReAct、Plan-and-Solve等）与完整发展史
- 手把手实现低代码平台（Coze、Dify、n8n）与主流框架（AutoGen、LangGraph）的智能体搭建
- 从零自研智能体框架（HelloAgents），实现上下文工程、记忆系统、通信协议（MCP/A2A）等高级技术
- 提供Agentic RL训练（SFT到GRPO）、智能体性能评估与综合案例（旅行助手、赛博小镇）

**技术亮点**: 基于OpenAI原生API自研框架，融合LLM基础、多智能体协作、记忆检索与协议通信，包含完整实战训练流程。

---
## 5. [datawhalechina/easy-vibe](https://github.com/datawhalechina/easy-vibe)
- **语言**: JavaScript
- **Stars**: 8,548
- **简介**: 💻 vibe coding 2026 | Your first modern programming course for beginners to master step by step.

### AI 总结
**简介**: 面向零基础初学者的现代编程入门课程，主打“会说话就能做应用”的轻松学习理念。

**核心功能**:
- 提供从零开始的清晰学习地图，解决“学了就忘”问题
- 包含步骤式可视化教程，模拟私教一对一指导
- 提供沉浸式模拟编码环境，通过虚拟鼠标引导快速掌握IDE核心操作
- 通过动画直观展示AI生成图像原理（扩散模型）
- 以交互式游戏方式学习RAG（检索增强生成）完整数据流程
- 可视化终端概念教学，降低命令行学习门槛

**技术亮点**: 基于JavaScript构建，支持多语言（中/英/日/西/法/韩/阿/越/德），采用交互式组件和动画教学，集成AI原理可视化演示。

---
## 6. [rowboatlabs/rowboat](https://github.com/rowboatlabs/rowboat)
- **语言**: TypeScript
- **Stars**: 13,799
- **简介**: Open-source AI coworker, with memory

### AI 总结
**简介**: Rowboat 是一个开源 AI 同事，能够将工作内容转化为知识图谱并据此采取行动，所有数据在本地运行。

**核心功能**:
- 连接邮箱和会议记录，构建长期知识图谱
- 根据上下文生成文档、PPT、会议简报等实际产出
- 支持语音备忘录，自动提取关键信息更新知识图谱
- 提供可查看、编辑的知识图谱（基于 Markdown）
- 支持追踪人员、公司或主题的实时笔记

**技术亮点**: 基于 TypeScript 开发，采用本地优先架构，使用 Obsidian 兼容的 Markdown 笔记库作为透明的工作记忆，集成 Gmail、Google Calendar 和 Fireflies 等服务，支持 MCP 服务器和 Composio 外部工具扩展。

---
## 7. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)
- **语言**: TypeScript
- **Stars**: 38,838
- **简介**: Chrome DevTools for coding agents

### AI 总结
**简介**: 一个基于MCP协议的Chrome DevTools服务器，允许AI编码代理（如Gemini、Claude、Cursor、Copilot）实时控制、检查和调试Chrome浏览器。

**核心功能**:
- 性能洞察：利用Chrome DevTools记录跟踪并提取可操作的性能建议
- 高级浏览器调试：分析网络请求、截图、检查控制台消息（含源码映射堆栈跟踪）
- 可靠自动化：基于Puppeteer实现浏览器操作自动化并自动等待结果

**技术亮点**: 基于TypeScript开发，采用MCP（Model-Context-Protocol）架构，整合Chrome DevTools与Puppeteer，支持Slim模式简化基础浏览器任务，提供CLI工具。

---
## 8. [masterking32/MasterDnsVPN](https://github.com/masterking32/MasterDnsVPN)
- **语言**: Go
- **Stars**: 2,553
- **简介**: Advanced DNS tunneling VPN for censorship bypass, optimized beyond DNSTT and SlipStream with low-overhead ARQ, resolver load balancing, high packet-loss stability and speed.

### AI 总结
**简介**: MasterDnsVPN 是一款基于 DNS 隧道的 VPN 工具，专为绕过网络审查设计，性能优于 DNSTT 和 SlipStream，具备低开销 ARQ、解析器负载均衡、高丢包稳定性及高速传输能力。

**核心功能**:
- 通过 DNS 隧道实现 VPN 连接，绕过网络审查限制
- 支持低开销自动重传请求（ARQ），提高数据可靠性
- 集成解析器负载均衡，优化 DNS 查询性能
- 在高丢包网络环境下保持稳定连接和传输速度

**技术亮点**: 使用 Go 语言开发，采用先进的 DNS 隧道技术，结合 ARQ 协议与负载均衡架构，提升隧道传输效率和抗干扰能力。

---
## 9. [playcanvas/supersplat](https://github.com/playcanvas/supersplat)
- **语言**: TypeScript
- **Stars**: 6,328
- **简介**: 3D Gaussian Splat Editor

### AI 总结
**简介**: SuperSplat Editor 是一款免费开源的 3D 高斯泼溅（3D Gaussian Splatting）编辑器，基于 Web 技术构建，可直接在浏览器中运行，无需下载安装。

**核心功能**:
- 检查、编辑、优化和发布 3D 高斯泼溅数据
- 支持多语言本地化，社区可贡献翻译
- 提供在线版本，访问 https://superspl.at/editor 即可使用

**技术亮点**: 基于 TypeScript 开发，使用 Node.js 18+ 构建，支持开发者本地热重载开发环境

---
## 10. [Lordog/dive-into-llms](https://github.com/Lordog/dive-into-llms)
- **语言**: Jupyter Notebook
- **Stars**: 36,489
- **简介**: 《动手学大模型Dive into LLMs》系列编程实践教程

### AI 总结
**简介**: 上海交通大学《动手学大模型》系列编程实践教程，提供大模型入门的免费公益编程参考。

**核心功能**:
- **微调与部署**: 指导如何对预训练模型进行微调并部署为可用的Demo。
- **提示学习与思维链**: 讲解大模型API调用与推理，通过提示工程提升模型表现。
- **知识编辑**: 教学如何编辑语言模型中的特定知识并进行验证。
- **数学推理**: 演示如何通过蒸馏技术让大模型学会数学推理（如迷你R1）。
- **模型水印**: 在文本生成中嵌入不可见的水印。
- **越狱攻击**: 介绍如何攻破大模型的安全防线，以提升安全性。
- **大模型隐写**: 在流畅回答中嵌入只有特定方识别的隐藏信息。
- **多模态模型**: 探索多模态大语言模型的理解与生成能力。
- **GUI智能体**: 实现AI Agent自动完成点外卖、回消息等任务。
- **智能体安全**: 关注AI Agent的安全性（内容待更新）。

**技术亮点**: 使用Jupyter Notebook作为编程实践环境，提供课件、教程、脚本三合一资源，支持华为昇腾等国产化平台。

---
