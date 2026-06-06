---
tags:
  - github-trending
  - daily
date: 2026-06-06
created: 2026-06-06T01:55:44.634Z
---

# 2026-06-06 GitHub Trending Top 10

## 1. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 183,193
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 构建的、具备自我改进能力的 AI 代理，能在不同会话间学习并成长。

**核心功能**:
- **自我学习循环**: 自动从经验中创建技能，在使用过程中自我改进，并跨会话搜索和记忆。
- **多平台接入**: 支持 Telegram、Discord、Slack、WhatsApp、Signal 和 CLI，通过单一网关进程实现跨平台对话连续性。
- **定时自动化**: 内置 cron 调度器，支持自然语言设置每日报告、夜间备份等无人值守任务。
- **任务并行与委派**: 可生成隔离的子代理处理并行工作流，并支持通过 RPC 调用工具。
- **可插拔模型**: 支持 200+ 模型（OpenRouter、OpenAI 等），可通过命令自由切换，无代码锁定。

**技术亮点**: 基于 Python 构建，支持本地、Docker、SSH、Modal、Daytona 等六种终端后端；提供全功能 TUI 界面；兼容 agentskills.io 开放标准；具备批处理轨迹生成和压缩能力，可用于训练下一代工具调用模型。

---
## 2. [chopratejas/headroom](https://github.com/chopratejas/headroom)
- **语言**: Python
- **Stars**: 14,552
- **简介**: Compress tool outputs, logs, files, and RAG chunks before they reach the LLM. 60-95% fewer tokens, same answers. Library, proxy, MCP server.

### AI 总结
**简介**: Headroom 是一个上下文压缩层，可在 AI 代理读取工具输出、日志、RAG 块和文件之前对其进行压缩，在保持回答质量的同时减少 60-95% 的 Token 消耗。

**核心功能**:
- **压缩库**: 提供 `compress(messages)` 函数，支持 Python 和 TypeScript，可内联集成到任何应用中
- **代理模式**: 支持 `headroom proxy` 零代码改动代理，以及 `headroom wrap` 一键封装 Claude、Codex、Cursor 等主流 AI 代理
- **MCP 服务器**: 提供 `headroom_compress`、`headroom_retrieve`、`headroom_stats` 等工具，兼容任何 MCP 客户端
- **跨代理记忆**: 在 Claude、Codex、Gemini 等代理间共享存储，自动去重
- **`headroom learn`**: 挖掘失败会话，自动向 `CLAUDE.md`/`AGENTS.md` 写入修正
- **可逆压缩 (CCR)**: 原始数据永不删除，LLM 可按需通过 `headroom_retrieve` 恢复

**技术亮点**:
- **6 种压缩算法**: 包括 SmartCrusher (JSON)、CodeCompressor (AST)、Kompress-base (文本/HuggingFace 模型)
- **ContentRouter**: 自动检测内容类型并选择最优压缩器
- **CacheAligner**: 稳定前缀以命中 KV 缓存，提高推理效率
- **本地优先**: 所有压缩均在本地运行，数据不离开用户环境
- **跨语言支持**: 同时提供 Python 和 npm 包，支持多语言生态

---
## 3. [CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit)
- **语言**: TypeScript
- **Stars**: 32,707
- **简介**: The Frontend Stack for Agents & Generative UI. React + Angular. Makers of the AG-UI Protocol

### AI 总结
生成总结时发生错误。

---
## 4. [lfnovo/open-notebook](https://github.com/lfnovo/open-notebook)
- **语言**: TypeScript
- **Stars**: 26,035
- **简介**: An Open Source implementation of Notebook LM with more flexibility and features

### AI 总结
**简介**: Open Notebook 是一个开源的、注重隐私的 Notebook LM 替代品，提供更灵活的功能和更多 AI 模型支持。

**核心功能**:
- **数据隐私**: 支持自托管，完全掌控你的研究数据
- **多 AI 模型**: 支持 18+ 提供商，包括 OpenAI、Anthropic、Ollama、LM Studio 等
- **多模态内容管理**: 支持 PDF、视频、音频、网页等多种内容格式
- **专业播客生成**: 支持 1-4 个说话者的高级多说话者播客生成
- **智能搜索**: 支持全文搜索和向量搜索
- **上下文聊天**: 基于研究内容的 AI 对话
- **多语言 UI**: 支持英语、中文、日语、俄语等多种语言

**技术亮点**: 基于 Python、Next.js、React、SurrealDB 和 LangChain 构建，提供 Docker、云或本地部署选项，拥有完整的 REST API 接口。

---
## 5. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 208,384
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个跨多 AI 编程助手（如 Claude Code、Cursor、Codex 等）的代理性能优化系统，提供技能、记忆、安全扫描和研究优先开发等能力，支持 12+ 语言生态。

**核心功能**:
- 跨平台代理工作流：统一管理 Codex、Claude Code、Cursor、OpenCode 等 AI 助手的配置和规则
- 技能与本能系统：内置生产级代理技能、钩子、规则和 MCP 配置
- 记忆优化与持续学习：支持记忆管理和自适应学习机制
- 安全扫描：集成代理安全扫描功能
- 研究优先开发：提供 Hermes 操作员故事和跨架构指南
- 多语言支持：提供 11 种语言的文档和社区支持

**技术亮点**:
- 基于 JavaScript/TypeScript 构建，同时支持 Shell、Python、Go、Java 等多语言生态
- 采用 MIT 开源许可，提供免费 OSS 版本和付费 Pro 版本（GitHub App）
- 经过 10+ 个月高强度实际产品开发验证，跨 7 个主流 AI 代理平台
- 架构设计为“harness-native”，可直接嵌入不同 AI 工具的工作流

---
## 6. [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)
- **语言**: Python
- **Stars**: 21,590
- **简介**: Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees.

### AI 总结
**简介**: Agent Reach 是一个为 AI Agent 提供互联网能力的开源命令行工具，让 Agent 能够免费访问、搜索和读取 Twitter、Reddit、YouTube、GitHub、Bilibili、小红书等多个平台的内容。

**核心功能**:
- **多平台支持**：无需配置即可读取网页、YouTube字幕/RSS/微博；配置Cookie后解锁Twitter搜索、小红书、抖音、LinkedIn等平台
- **全网搜索**：通过MCP接入免费搜索引擎，无需API Key
- **一键安装与更新**：Agent只需复制一句安装命令即可自动完成所有依赖配置
- **健康诊断**：`agent-reach doctor`命令一键检测各渠道连通性并给出修复建议
- **隐私安全**：Cookie仅存本地，代码完全开源可审查

**技术亮点**:
- 基于Python 3.10+，整合yt-dlp、twitter-cli、rdt-cli、Jina Reader等开源工具
- 自动检测环境（本地/服务器），适配不同代理需求
- 通过SKILL.md注册Agent技能，实现智能路由到对应上游工具
- 兼容Claude Code、OpenClaw、Cursor、Windsurf等主流Agent平台

---
## 7. [NVIDIA/cosmos](https://github.com/NVIDIA/cosmos)
- **语言**: Jupyter Notebook
- **Stars**: 9,422
- **简介**: NVIDIA Cosmos is an open platform of world models, datasets, and tools that enables developers to build Physical AI for robots, autonomous vehicles, smart infrastructure, and more.

### AI 总结
**简介**: NVIDIA Cosmos 是一个开放的世界模型、数据集和工具平台，帮助开发者构建用于机器人、自动驾驶和智能基础设施等领域的物理AI。

**核心功能**:
- **世界理解**: 分析图像和视频，生成描述、时序事件、空间定位、物理合理性判断及因果推理。
- **世界生成**: 根据文本、图像、视频或动作输入，生成图像、视频、同步音频以及动作条件序列。
- **动作建模**: 在机器人、摄像机运动、自我中心运动及自动驾驶场景中预测策略动作、逆动力学和正动力学。
- **灵活部署**: 支持通过Diffusers和Transformers进行Python开发，并通过vLLM-Omni和vLLM提供OpenAI兼容的服务接口。
- **后训练适配**: 提供Cosmos框架的训练配方，支持视觉、动作和推理工作流的定制化微调（即将推出）。

**技术亮点**: 采用统一的混合Transformer（Mixture-of-Transformers, MoT）架构，结合自回归Transformer（AR）用于推理和扩散Transformer（DM）用于多模态生成，支持语言、图像、视频、音频和动作序列的联合处理与生成，并通过3D多维旋转位置编码（mRoPE）统一跨模态的时空结构表示。

---
## 8. [666ghj/MiroFish](https://github.com/666ghj/MiroFish)
- **语言**: Python
- **Stars**: 64,722
- **简介**: A Simple and Universal Swarm Intelligence Engine, Predicting Anything. 简洁通用的群体智能引擎，预测万物

### AI 总结
**简介**: MiroFish 是一款基于多智能体技术的下一代 AI 预测引擎，通过构建高保真平行数字世界，模拟个体交互与社会演化，实现对未来的精准推演。

**核心功能**:
- **智能体驱动预测**: 自动从现实世界提取种子信息（如新闻、政策、金融信号），构建拥有独立个性、长期记忆和行为逻辑的智能体群体，并在数字空间中进行自由交互与演化。
- **上帝视角变量注入**: 用户可从宏观视角动态注入变量，观察其对模拟世界的影响，从而在无数次仿真中优化决策。
- **自然语言交互**: 用户只需上传种子材料（如数据分析报告、小说故事）并用自然语言描述预测需求，即可获得详细的预测报告和可深度交互的数字世界。
- **宏观与微观双模式**: 宏观层面作为决策者的零风险推演实验室（如政策测试），微观层面作为个人用户的创意沙盒（如推演小说结局、探索想象场景）。

**技术亮点**: 多智能体群体智能引擎、高保真平行世界构建、基于涌现行为的复杂系统模拟。

---
## 9. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 28,227
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: /last30days 是一个 AI 代理驱动的搜索引擎，能够并行搜索 Reddit、X、YouTube、Hacker News、Polymarket 等多个平台，并基于用户真实互动（点赞、投票、金钱）对结果进行评分，最终合成一份接地气的总结报告。

**核心功能**:
- **多平台并行搜索**: 同时搜索 Reddit、X、YouTube、TikTok、Hacker News、Polymarket、GitHub 等平台的近期内容。
- **基于真实互动的评分**: 使用点赞、投票、市场赔率等信号对搜索结果进行排序，而非传统编辑算法。
- **AI 代理合成总结**: 自动将分散在各平台的信息整合成一份简洁、有重点的摘要报告。
- **零配置快速启动**: Reddit、HN、Polymarket、GitHub 开箱即用，运行一次后可通过交互式向导解锁更多平台。
- **支持多种 AI 主机**: 兼容 Claude Code、Codex、Cursor、Copilot、Gemini CLI 等 50 多种 Agent Skills 主机。

**技术亮点**:
- **Python 语言实现**: 项目核心使用 Python 开发。
- **插件化架构**: 通过 Agent Skills 生态系统，可方便地集成到各种 AI 开发工具和工作流中。
- **API 桥接策略**: 通过让用户提供自己的 API 密钥和浏览器会话，绕过了单一 AI 模型无法访问所有封闭平台的限制，实现了跨平台信息聚合。

---
## 10. [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)
- **语言**: Python
- **Stars**: 80,557
- **简介**: Turn any PDF or image document into structured data for your AI. A powerful, lightweight OCR toolkit that bridges the gap between images/PDFs and LLMs. Supports 100+ languages.

### AI 总结
**简介**: PaddleOCR 是一款全球领先的轻量级 OCR 工具包，能将 PDF 和图片转化为结构化的、可供 AI/LLM 直接使用的数据，支持 100+ 语言。

**核心功能**:
- **智能文档解析**: 支持将复杂 PDF 和图片转换为 Markdown 或 JSON 格式的结构化数据，包含文本、表格、公式等元素。
- **SOTA 文档视觉语言模型**: 内置 PaddleOCR-VL-1.6 (0.9B) 模型，在文档解析基准上准确率达 96.3%，支持古代文档、生僻字、印章、图表等复杂场景。
- **结构感知转换**: 基于 PP-StructureV3，提供比视觉模型更精细的坐标信息（如表格单元格坐标），实现精准的结构还原。

**技术亮点**: 采用 Python 开发，支持 CPU、GPU、XPU、NPU 等多种硬件，兼容 Linux、Windows、macOS 操作系统。

---
