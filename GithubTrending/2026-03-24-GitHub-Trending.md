---
tags:
  - github-trending
  - daily
date: 2026-03-24
created: 2026-03-24T01:55:50.578Z
---

# 2026-03-24 GitHub Trending Top 10

## 1. [FujiwaraChoki/MoneyPrinterV2](https://github.com/FujiwaraChoki/MoneyPrinterV2)
- **语言**: Python
- **Stars**: 23,028
- **简介**: Automate the process of making money online.

### AI 总结
**简介**: 一个用于自动化在线赚钱流程的 Python 应用程序。

**核心功能**:
- Twitter 机器人（支持定时任务调度）
- YouTube Shorts 自动化（支持定时任务调度）
- 联盟营销（亚马逊 + Twitter）
- 寻找本地企业并进行冷接触

**技术亮点**: 采用模块化架构，是原项目的完全重写版，支持通过脚本直接调用核心功能。

---
## 2. [bytedance/deer-flow](https://github.com/bytedance/deer-flow)
- **语言**: Python
- **Stars**: 39,603
- **简介**: An open-source SuperAgent harness that researches, codes, and creates. With the help of sandboxes, memories, tools, skill, subagents and message gateway, it handles different levels of tasks that could take minutes to hours.

### AI 总结
**简介**: DeerFlow 是一个由字节跳动开源的超级智能体框架，通过编排子智能体、记忆和沙箱，利用可扩展技能处理从几分钟到数小时不等的复杂任务。

**核心功能**:
- **智能体编排**：通过子智能体、技能和工具集协同工作，处理多层次任务。
- **沙箱环境**：提供安全的代码执行和文件系统操作环境。
- **上下文与记忆**：支持长短期记忆管理和上下文工程，优化任务处理。
- **多模型支持**：推荐并支持使用豆包、DeepSeek、Kimi等大语言模型。

**技术亮点**:
- 采用Python 3.12+和Node.js 22+技术栈，支持Docker一键部署。
- 集成了字节跳动的InfoQuest智能搜索与爬取工具集。
- 提供Claude Code集成、MCP服务器和IM通道等高级功能。
- 采用模块化设计，具备高度可扩展的技能和工具系统。

---
## 3. [Crosstalk-Solutions/project-nomad](https://github.com/Crosstalk-Solutions/project-nomad)
- **语言**: TypeScript
- **Stars**: 13,461
- **简介**: Project N.O.M.A.D, is a self-contained, offline survival computer packed with critical tools, knowledge, and AI to keep you informed and empowered—anytime, anywhere.

### AI 总结
**简介**: Project N.O.M.A.D. 是一个自包含、优先离线的生存知识服务器，集成了关键工具、知识和本地AI，旨在让用户随时随地获取信息并保持自主能力。

**核心功能**:
- **AI聊天与知识库**: 基于Ollama的本地AI聊天，支持文档上传和语义搜索（通过Qdrant实现RAG）。
- **离线信息库**: 通过Kiwix提供离线维基百科、医学参考、电子书等资源。
- **教育平台**: 集成Kolibri，提供可汗学院课程与进度跟踪。
- **离线地图**: 通过ProtoMaps提供可下载的区域地图。
- **数据工具**: 集成CyberChef，用于加密、编码、哈希和数据分析。
- **笔记系统**: 通过FlatNotes支持本地Markdown笔记。
- **系统基准测试**: 内置硬件评分与社区排行榜。
- **便捷设置向导**: 提供引导式首次配置和精选内容集合。

**技术亮点**: 项目采用TypeScript开发，核心是一个管理UI（“指挥中心”）和API，通过Docker编排一系列容器化工具和资源，实现一键安装、配置和更新。它强调离线优先和硬件无关性，但为充分发挥AI功能，推荐使用性能较强的GPU设备。

---
## 4. [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi)
- **语言**: Go
- **Stars**: 13,033
- **简介**: Fully autonomous AI Agents system capable of performing complex penetration testing tasks

### AI 总结
**简介**: PentAGI 是一个基于 Go 语言开发的、能够执行复杂渗透测试任务的全自主人工智能代理系统。

**核心功能**:
- **全自主渗透测试**: AI 代理可自动决策并执行渗透测试步骤，支持任务监控与智能规划。
- **专业工具集成**: 内置 20 多种专业安全工具（如 nmap、metasploit、sqlmap）。
- **智能记忆与知识图谱**: 具备长期存储研究结果的能力，并集成 Neo4j 知识图谱以追踪语义关系。
- **多源信息收集**: 集成内置浏览器及多个外部搜索系统（如 Tavily、Perplexity、Google 等），用于全面信息收集。
- **团队协作与监控**: 支持专家代理任务委派，并提供详细的日志记录与 Grafana/Prometheus 实时监控。
- **全面报告生成**: 可生成包含漏洞利用指南的详细报告。

**技术亮点**:
- **微服务架构**: 采用基于 Docker 的沙箱隔离环境，支持水平扩展。
- **灵活的后端与 AI 支持**: 使用 PostgreSQL（含 pgvector 扩展）进行持久化存储，并支持 10 多种 LLM 提供商及聚合器。
- **现代化接口与 API**: 提供直观的 Web UI 以及完整的 REST 和 GraphQL API（支持 Bearer 令牌认证）。

---
## 5. [browser-use/browser-use](https://github.com/browser-use/browser-use)
- **语言**: Python
- **Stars**: 83,694
- **简介**: 🌐 Make websites accessible for AI agents. Automate tasks online with ease.

### AI 总结
**简介**: 一个用于让AI智能体自动化操作网页的Python库，旨在简化在线任务自动化流程。

**核心功能**:
- 提供简洁的API，让开发者能够快速构建基于LLM的网页自动化智能体。
- 支持多种主流LLM（如Google Gemini、Anthropic Claude）作为智能体的“大脑”。
- 提供本地运行和云端服务两种模式，云端服务提供更强的性能、隐身能力和可扩展性。

**技术亮点**: 基于Python异步编程，支持通过`uv`工具快速安装和管理依赖，并提供了详细的基准测试来评估不同LLM模型在真实网页任务上的成功率。

---
## 6. [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)
- **语言**: Python
- **Stars**: 39,393
- **简介**: TradingAgents: Multi-Agents LLM Financial Trading Framework

### AI 总结
**简介**: TradingAgents 是一个基于大语言模型（LLM）的多智能体金融交易框架，旨在模拟真实交易公司的动态协作，以进行市场分析和交易决策。

**核心功能**:
- 部署多种专业化的LLM智能体（如基本面分析师、情绪分析师、技术分析师、交易员、风险管理团队）进行协作分析。
- 支持多模型提供商（如GPT-5.x、Gemini 3.x、Claude 4.x、Grok 4.x）和最新的模型版本。
- 提供动态讨论机制，让智能体共同寻找最优交易策略。

**技术亮点**: 采用多智能体系统架构，将复杂的交易任务分解为专业角色，实现了可扩展且稳健的市场分析与决策流程。框架支持最新的LLM API（如OpenAI Responses API、Anthropic effort control）并注重跨平台稳定性。

---
## 7. [tinygrad/tinygrad](https://github.com/tinygrad/tinygrad)
- **语言**: Python
- **Stars**: 31,889
- **简介**: You like pytorch? You like micrograd? You love tinygrad! ❤️

### AI 总结
**简介**: Tinygrad 是一个介于 PyTorch 和 micrograd 之间的、轻量级且可深度定制的端到端深度学习框架。

**核心功能**:
- 提供包含自动微分（autograd）功能的张量库。
- 包含中间表示（IR）和编译器，能够进行内核融合与代码生成。
- 支持即时编译（JIT）和图执行。
- 内置神经网络层（nn）、优化器（optim）和数据集（datasets）模块，支持完整的模型训练流程。

**技术亮点**:
- **设计理念**：借鉴了 PyTorch 的易用性、JAX 的函数式变换与基于 IR 的自动微分，以及 TVM 的调度与代码生成，但保持代码精简和高度可读性。
- **惰性求值**：支持操作融合，可将多个计算步骤优化为单个内核执行。
- **多后端支持**：支持多种硬件加速后端，包括 CPU、CUDA、Metal、OpenCL、AMD、WebGPU 等，且易于扩展。
- **透明性**：整个编译器、IR 和内核生成过程对开发者可见且易于修改。

---
## 8. [affaan-m/everything-claude-code](https://github.com/affaan-m/everything-claude-code)
- **语言**: JavaScript
- **Stars**: 102,093
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: 一个用于优化 AI 代理（如 Claude Code、Cursor 等）性能的完整系统，包含技能、记忆、安全等模块。

**核心功能**:
- **性能优化系统**: 提供技能、本能、内存优化、持续学习和安全扫描等功能。
- **多语言支持**: 支持包括简体中文在内的 7 种语言，并提供了详细的指南文档。
- **生产就绪**: 提供可直接用于生产的代理、钩子、命令、规则和 MCP 配置。
- **选择性安装**: 支持基于清单的架构，允许针对性安装组件和增量更新。

**技术亮点**: 项目采用多语言技术栈（包括 TypeScript、Python、Go、Java 等），并提供了 Token 优化、内存持久化、验证循环、并行化和子代理编排等高级功能。

---
## 9. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 11,619
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 开发的自进化 AI 代理，具备内置的学习循环，能够从经验中创建并改进技能，并支持在多种平台上运行和交互。

**核心功能**:
- **自我进化与学习**：具备封闭的学习循环，能够从复杂任务中自主创建技能，并在使用中自我改进。集成了基于 Honcho 的用户建模和跨会话记忆搜索。
- **多平台与多模态接入**：支持通过终端 CLI 或统一的网关进程与 Telegram、Discord、Slack、WhatsApp、Signal 等平台进行交互，实现跨平台对话连续性。
- **灵活的模型与部署**：支持连接 Nous Portal、OpenRouter、OpenAI 等众多模型提供商，无需更改代码即可切换。可在本地、Docker、SSH、Serverless（如 Modal）等多种环境中部署，成本可控。
- **强大的自动化能力**：内置定时任务调度器，支持用自然语言描述自动化任务。可以生成并管理并行工作的子代理，以优化复杂工作流。

**技术亮点**:
- 提供功能完整的终端用户界面，支持多行编辑、命令自动补全和流式工具输出。
- 采用与 `agentskills.io` 开放标准兼容的技能系统。
- 支持批量轨迹生成和 Atropos RL 环境，便于进行工具调用模型的研究和训练。

---
## 10. [jingyaogong/minimind](https://github.com/jingyaogong/minimind)
- **语言**: Python
- **Stars**: 42,606
- **简介**: 🚀🚀 「大模型」2小时完全从0训练26M的小参数GPT！🌏 Train a 26M-parameter GPT from scratch in just 2h!

### AI 总结
**简介**: 一个旨在让开发者从零开始，以极低成本（约3元）和短时间（约2小时）训练超小型语言模型（26M参数）的开源项目，并提供了大模型全流程的极简实现与教程。

**核心功能**:
- **从零训练**: 提供从分词器训练、数据清洗到模型预训练（Pretrain）的完整代码。
- **全流程微调与对齐**: 支持监督微调（SFT）、LoRA微调、直接偏好优化（DPO）以及强化学习（RLAIF，如PPO/GRPO）等训练阶段。
- **多模态拓展**: 提供了视觉语言模型（VLM）版本 MiniMind-V。
- **易于部署与集成**: 模型兼容主流框架（如 transformers, trl），并提供了OpenAI API协议的服务端和Streamlit WebUI，支持 llama.cpp、vllm 等推理引擎。

**技术亮点**:
- **极简原生实现**: 核心算法（如MoE、DPO、PPO）均使用PyTorch从零实现，不依赖第三方抽象接口，便于学习底层原理。
- **轻量与高效**: 模型参数量极小（最小仅25.8M），可在消费级GPU（如NVIDIA 3090）上快速训练和推理。
- **全面的技术栈**: 覆盖了现代LLM训练的关键技术，包括模型蒸馏、YaRN长文本外推、动态启停训练以及单机多卡（DDP/DeepSpeed）支持。

---
