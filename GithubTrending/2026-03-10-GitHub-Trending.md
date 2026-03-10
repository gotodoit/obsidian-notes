---
tags:
  - github-trending
  - daily
date: 2026-03-10
created: 2026-03-10T01:55:52.861Z
---

# 2026-03-10 GitHub Trending Top 10

## 1. [GoogleCloudPlatform/generative-ai](https://github.com/GoogleCloudPlatform/generative-ai)
- **语言**: Jupyter Notebook
- **Stars**: 15,307
- **简介**: Sample code and notebooks for Generative AI on Google Cloud, with Gemini on Vertex AI

### AI 总结
**简介**: 这是一个由 Google Cloud 官方维护的代码库，提供了在 Google Cloud 上使用 Vertex AI 和 Gemini 等模型进行生成式 AI 开发的示例代码、Notebook 和资源。

**核心功能**:
- **Gemini 模型应用**: 包含从入门到高级应用的 Notebook，涵盖提示工程、函数调用等，并已更新支持最新的 Gemini 3.1 Pro 模型。
- **多模态 AI 开发**: 提供基于 Vertex AI Imagen API 的图像生成、编辑、视觉问答，以及基于 Chirp 模型的语音处理解决方案。
- **企业级搜索与 RAG**: 包含使用 Vertex AI Search 构建搜索引擎，以及实现检索增强生成和 Grounding 技术的相关示例。
- **环境与资源**: 提供了 Google Cloud 环境、SDK 和 Notebook 环境的设置指南，以及相关的学习资源列表。

**技术亮点**: 项目紧密集成 Google Cloud Vertex AI 平台，覆盖了生成式 AI 工作流的核心环节，包括大语言模型、多模态模型、企业搜索和 RAG，是学习 Google Cloud 生成式 AI 服务的实践宝库。

---
## 2. [openclaw/openclaw](https://github.com/openclaw/openclaw)
- **语言**: TypeScript
- **Stars**: 290,659
- **简介**: Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞

### AI 总结
**简介**: OpenClaw 是一个可部署在个人设备上的、跨平台、多通道的个人AI助手。

**核心功能**:
- 支持通过多种即时通讯平台（如 WhatsApp、Telegram、Slack、Discord 等）与助手交互。
- 支持语音交互（macOS/iOS/Android）和实时画布渲染。
- 提供命令行向导（`openclaw onboard`），引导用户完成网关、工作区、通道和技能的设置。

**技术亮点**:
- 使用 TypeScript 开发，运行时要求 Node.js ≥22。
- 支持通过 npm、pnpm 或 bun 安装。
- 支持多种 AI 模型提供商（如 OpenAI），并具备模型故障转移和认证轮换机制。
- 提供守护进程安装选项（launchd/systemd），确保服务持续运行。

---
## 3. [666ghj/MiroFish](https://github.com/666ghj/MiroFish)
- **语言**: Python
- **Stars**: 11,107
- **简介**: A Simple and Universal Swarm Intelligence Engine, Predicting Anything. 简洁通用的群体智能引擎，预测万物

### AI 总结
**简介**: MiroFish 是一个基于多智能体技术的群体智能预测引擎，能够通过输入种子信息（如新闻、报告或小说）构建高保真数字世界，并模拟智能体交互来推演未来走向。

**核心功能**:
- **预测推演**: 上传种子材料并用自然语言描述需求，即可获得详细的预测报告和一个可交互的数字世界。
- **平行世界构建**: 自动从现实世界信息中提取数据，构建包含成千上万具备独立人格和记忆的智能体的仿真环境。
- **多场景应用**: 支持宏观决策（如政策、舆情推演）和微观创意（如小说结局预测）等多种模拟场景。
- **深度交互**: 用户可与模拟世界中的任意智能体对话，或与生成报告的Agent进行深入交流。

**技术亮点**:
- 采用多智能体架构，结合GraphRAG进行知识图谱构建与记忆管理。
- 支持双平台并行模拟，动态更新时序记忆。
- 前后端分离，使用Python后端和Node.js前端，提供Docker容器化部署选项。
- 依赖LLM API（如阿里百炼平台）和Zep Cloud实现智能体记忆与交互。

---
## 4. [karpathy/nanochat](https://github.com/karpathy/nanochat)
- **语言**: Python
- **Stars**: 45,552
- **简介**: The best ChatGPT that $100 can buy.

### AI 总结
**简介**: nanochat 是一个极简、可修改的实验框架，用于在单GPU节点上训练大语言模型（LLM），旨在以极低成本（约100美元）复现GPT-2级别的模型。

**核心功能**:
- 覆盖LLM全流程：分词、预训练、微调、评估、推理及类ChatGPT的聊天界面。
- 通过单一参数（`--depth`）自动配置并训练一系列计算最优的模型。
- 提供完整的“GPT-2速通”脚本，可在约2-3小时内以约48美元成本完成训练。

**技术亮点**:
- 代码极简、可修改，专为单GPU节点设计。
- 自动优化超参数（宽度、头数、学习率等）。
- 支持多GPU并行训练，也可在单GPU上通过梯度累积运行。
- 维护“Time-to-GPT-2”排行榜，追踪社区在训练速度和效果上的进展。

---
## 5. [666ghj/BettaFish](https://github.com/666ghj/BettaFish)
- **语言**: Python
- **Stars**: 37,384
- **简介**: 微舆：人人可用的多Agent舆情分析助手，打破信息茧房，还原舆情原貌，预测未来走向，辅助决策！从0实现，不依赖任何框架。

### AI 总结
**简介**: BettaFish（微舆）是一个从零实现、不依赖框架的Python多智能体舆情分析系统，旨在通过AI驱动的全域监控和复合分析引擎，帮助用户打破信息茧房，还原舆情原貌并预测未来走向。

**核心功能**:
- **AI驱动的全域监控**：通过AI爬虫集群7x24小时覆盖微博、小红书、抖音等10+国内外主流社媒，实时捕获热点及海量用户评论。
- **多智能体协作分析**：设计5类专业Agent（如查询、媒体、洞察、报告Agent），通过“论坛”辩论机制协同工作，结合微调模型和统计模型进行深度多维分析。
- **多模态内容解析**：支持解析短视频内容（如抖音、快手）及提取搜索引擎中的结构化信息卡片（天气、股票等）。
- **公私域数据融合**：提供接口支持内部业务数据与公开舆情数据无缝集成，实现外部趋势与内部洞察的结合。
- **轻量化高扩展框架**：基于纯Python模块化设计，支持一键部署，便于开发者集成自定义模型与业务逻辑。

**技术亮点**:
- **从零实现**：不依赖外部框架，基于纯Python构建。
- **复合分析引擎**：融合多专业Agent、微调模型与统计模型，超越单一LLM限制。
- **论坛式协作机制**：引入辩论主持人模型，通过链式思维碰撞提升集体智能与决策质量。
- **完整数据分析链路**：与预测引擎项目MiroFish结合，形成从数据收集、分析到预测的闭环。

---
## 6. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 2,993
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是由 Nous Research 开发的一款具备自我学习和进化能力的 AI 智能体，能够在多种环境中部署，并通过多平台接口与用户交互。

**核心功能**:
- **自我进化学习循环**：具备内置学习机制，能够从经验中创建技能、在使用中改进技能、持久化知识，并能搜索过往对话以加深对用户的理解。
- **多平台与多模态接入**：支持通过 Telegram、Discord、Slack、CLI 等多种平台进行交互，并支持语音备忘录转录。
- **灵活的模型支持**：可无缝切换使用 Nous Portal、OpenRouter、OpenAI 等众多模型提供商或自定义端点，无供应商锁定。
- **强大的任务处理能力**：支持计划任务调度、并行化子代理工作流、编写调用工具的 Python 脚本，并能将多步骤流程简化为单次交互。
- **随处可部署**：支持在本地、Docker、SSH、Daytona、Modal 等多种后端运行，成本效益高，支持服务器无感知休眠。

**技术亮点**:
- **研究就绪**：支持批量轨迹生成、Atropos 强化学习环境以及用于训练下一代工具调用模型的轨迹压缩。
- **标准化与兼容性**：兼容 `agentskills.io` 开放标准，并集成了 `Honcho` 用户建模框架。
- **便捷的安装与管理**：提供一键安装脚本，内置 `hermes doctor` 等诊断和更新命令，简化运维。

---
## 7. [pbakaus/impeccable](https://github.com/pbakaus/impeccable)
- **语言**: JavaScript
- **Stars**: 3,008
- **简介**: The design language that makes your AI harness better at design.

### AI 总结
**简介**: Impeccable 是一个用于提升 AI 助手（如 Claude、Cursor 等）前端设计能力的技能与指令集，旨在通过专业指导和反模式规避来生成更优质、更专业的 UI 设计。

**核心功能**:
- **扩展的设计技能**：包含 7 个专业领域参考文件（如排版、色彩、动效、响应式设计等），为 AI 提供深入的设计知识。
- **17 条引导指令**：提供 `/audit`（审计）、`/polish`（润色）、`/distill`（提炼）等具体命令，用于审查、优化和增强设计。
- **精选反模式**：明确告知 AI 应避免的常见设计错误（如滥用卡片、使用过时字体、不当的色彩对比等）。

**技术亮点**: 项目以 JavaScript 编写，提供与主流 AI 编码工具（Cursor、Claude Code、Gemini CLI、Codex CLI）集成的即用型技能包，通过配置文件实现一键安装和上下文学习。

---
## 8. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 19,524
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个包含多个具备专业领域知识和鲜明个性的 AI 代理的集合，旨在像一支专业团队一样协助用户完成从工程设计到社区运营等各类任务。

**核心功能**:
- 提供多个高度专业化的 AI 代理，涵盖工程、设计、内容、社区、战略等多个领域。
- 支持与多种主流开发工具（如 Claude Code、Cursor、Aider 等）快速集成。
- 每个代理都具备独特的个性、明确的工作流程和可交付成果，开箱即用。

**技术亮点**: 项目主要提供代理配置与集成脚本（Shell），通过自动化脚本实现与多种 AI 辅助编程工具的无缝对接。

---
## 9. [alibaba/page-agent](https://github.com/alibaba/page-agent)
- **语言**: TypeScript
- **Stars**: 2,619
- **简介**: JavaScript in-page GUI agent. Control web interfaces with natural language.

### AI 总结
**简介**: Page Agent 是一个运行在网页内的 JavaScript GUI 代理，允许用户使用自然语言来控制网页界面。

**核心功能**:
- **易于集成**：无需浏览器扩展、Python 或无头浏览器，仅需在页面内引入 JavaScript。
- **基于文本的 DOM 操作**：无需截图、OCR 或多模态大语言模型，也无需特殊权限。
- **自带大语言模型**：支持用户接入自己的 LLM。
- **美观的交互界面**：支持人机协同操作。
- **可选 Chrome 扩展**：支持跨浏览器标签页的多页面任务。

**技术亮点**:
- 基于 TypeScript 开发，提供 NPM 包和 CDN 脚本两种集成方式。
- 设计用于客户端网页增强，而非服务端自动化。
- 项目灵感及部分组件源自优秀的开源项目 `browser-use`。

---
## 10. [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills)
- **语言**: Python
- **Stars**: 3,390
- **简介**: 169 production-ready skills & plugins for Claude Code, OpenAI Codex, and OpenClaw — engineering, marketing, product, compliance, C-level advisory, and more. Install via /plugin marketplace.

### AI 总结
**简介**: 一个为 Claude Code、OpenAI Codex 和 OpenClaw 等 AI 编程助手提供 170 个生产就绪技能与插件的开源库，旨在将通用 AI 助手转变为跨工程、产品、营销、合规等多个领域的专业专家。

**核心功能**:
- **模块化技能包**: 提供涵盖工程、产品、营销、项目管理、法规质量、C级咨询等 9 大领域的 170 个即用型技能，每个技能包含指令、工作流和 Python CLI 工具。
- **多平台原生支持**: 技能库可原生适配 Claude Code（插件市场）、OpenAI Codex、Gemini CLI 和 OpenClaw 四大平台。
- **便捷安装与管理**: 支持通过各平台的命令行或插件市场进行一键式批量或单个技能安装。

**技术亮点**: 采用模块化设计，每个技能包（`SKILL.md` + Python工具）独立且可复用；提供自动化安装脚本，并与主流 AI 编程助手生态深度集成。

---
