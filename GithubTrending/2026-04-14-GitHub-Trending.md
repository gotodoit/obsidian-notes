---
tags:
  - github-trending
  - daily
date: 2026-04-14
created: 2026-04-14T01:55:50.163Z
---

# 2026-04-14 GitHub Trending Top 10

## 1. [forrestchang/andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills)
- **语言**: Unknown
- **Stars**: 25,569
- **简介**: A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.

### AI 总结
**简介**: 一个名为 `CLAUDE.md` 的单一文件，旨在通过四大核心原则来改进 Claude Code 等 AI 编程助手的行为，解决其常见的编码陷阱。

**核心功能**:
- **编码前思考**: 强制 AI 明确陈述假设、呈现多种解释并在必要时提出质疑，避免隐藏的困惑和错误假设。
- **简单性优先**: 严格遵循需求，避免过度工程化、不必要的抽象和功能膨胀，追求用最少的代码解决问题。
- **精准修改**: 在编辑现有代码时，只修改与任务直接相关的部分，不“顺手”改进无关代码、注释或格式。
- **目标驱动执行**: 将指令转化为可验证的成功标准（如先写测试），让 AI 能够自主循环直到目标达成。

**技术亮点**: 项目理念源自 Andrej Karpathy 对 LLM 编码缺陷的观察，其解决方案以简洁的指导原则形式呈现，可通过安装 Claude Code 插件或直接添加 `CLAUDE.md` 文件到项目中来应用。

---
## 2. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 77,629
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 开发的自进化 AI 代理，具备内置学习循环，能够从经验中创建并改进技能，实现跨会话的持续学习和个性化交互。

**核心功能**:
- **多平台接入**: 支持 Telegram、Discord、Slack、WhatsApp、Signal 和 CLI 等多种交互方式，通过单一网关进程统一管理。
- **自我学习与记忆**: 具备代理管理的记忆系统，可自主创建技能并在使用中自我改进，支持跨会话的全文搜索和 LLM 摘要回忆。
- **灵活部署**: 支持在本地、Docker、SSH、Daytona、Singularity 和 Modal 等多种环境中运行，包括成本极低的服务器无感知架构。
- **任务自动化**: 内置 cron 调度器，支持用自然语言定义并自动执行每日报告、备份等定时任务。
- **并行处理**: 可以生成隔离的子代理进行并行工作流处理，并能通过 RPC 调用工具编写 Python 脚本以简化复杂流程。

**技术亮点**: 支持多种模型提供商（如 Nous Portal、OpenRouter、OpenAI 等），可轻松切换而无须修改代码；采用模块化工具配置；兼容 `agentskills.io` 开放标准；并集成了用于下一代工具调用模型训练的轨迹生成与压缩等研究功能。

---
## 3. [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos)
- **语言**: Python
- **Stars**: 17,048
- **简介**: Kronos: A Foundation Model for the Language of Financial Markets

### AI 总结
**简介**: Kronos 是首个专注于金融市场“语言”——K线序列的开源基础模型，基于超过45个全球交易所的数据进行预训练。

**核心功能**:
- 对多维K线（OHLCV）数据进行分层离散化编码，生成金融时序的专用令牌。
- 作为统一的基础模型，支持多种量化金融任务，如价格预测。

**技术亮点**: 采用两阶段框架，先由专用分词器量化数据，再由自回归Transformer进行预训练，专门处理金融数据的高噪声特性。模型家族提供从4.1M到499.2M不同参数规模的版本。

---
## 4. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 53,422
- **简介**: A Claude Code plugin that automatically captures everything Claude does during your coding sessions, compresses it with AI (using Claude's agent-sdk), and injects relevant context back into future sessions.

### AI 总结
**简介**: 一个为 Claude Code 设计的持久化记忆压缩系统插件，能自动记录编码会话内容，利用 AI 压缩并注入相关上下文到未来会话中。

**核心功能**:
- 自动捕获 Claude 在编码会话中的所有操作
- 使用 AI（基于 Claude 的 agent-sdk）对捕获内容进行智能压缩
- 将压缩后的相关上下文自动注入到未来的编码会话中

**技术亮点**: 基于 TypeScript 开发，利用 Claude 的 agent-sdk 实现 AI 驱动的上下文压缩与检索。

---
## 5. [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **语言**: Python
- **Stars**: 107,049
- **简介**: Python tool for converting files and office documents to Markdown.

### AI 总结
**简介**: 由微软开发的轻量级 Python 工具，专注于将多种文件和办公文档转换为 Markdown 格式，以便于大语言模型（LLM）和文本分析管道使用。

**核心功能**:
- 支持转换多种格式，包括 PDF、PowerPoint、Word、Excel、图像、音频、HTML、CSV/JSON/XML、ZIP、YouTube 视频、EPub 等。
- 提供命令行接口（CLI）和 Python API 两种使用方式，支持文件路径输入和管道操作。
- 依赖项按功能分组，支持按需安装以控制包大小（如 `pip install 'markitdown[pdf, docx]'`）。
- 现已提供 MCP（模型上下文协议）服务器，可与 Claude Desktop 等 LLM 应用集成。

**技术亮点**:
- 设计目标是为文本分析工具保留文档的重要结构（如标题、列表、表格、链接），输出为 LLM 原生理解且标记效率高的 Markdown。
- 从 0.1.0 版本起，采用基于二进制流的转换接口，不再创建临时文件，提升了效率。
- 需要 Python 3.10 或更高版本，建议在虚拟环境中使用。

---
## 6. [multica-ai/multica](https://github.com/multica-ai/multica)
- **语言**: TypeScript
- **Stars**: 11,198
- **简介**: The open-source managed agents platform. Turn coding agents into real teammates — assign tasks, track progress, compound skills.

### AI 总结
**简介**: Multica 是一个开源的托管智能体平台，旨在将编程智能体转变为真正的团队成员，实现任务分配、进度追踪和技能复用。

**核心功能**:
- **智能体即队友**：可以像给同事分配任务一样，将问题分配给智能体。智能体拥有个人资料，出现在看板上，能主动发表评论、创建问题和报告阻碍。
- **自主执行**：支持完整的任务生命周期管理（排队、认领、开始、完成/失败），并通过 WebSocket 进行实时进度流式传输。
- **可复用技能**：每个解决方案都能转化为整个团队可复用的技能，如部署、迁移、代码审查，从而随时间积累团队能力。
- **统一运行时**：一个仪表板管理所有计算资源，支持本地守护进程和云运行时，自动检测可用的 CLI 并进行实时监控。
- **多工作区**：通过工作区级别的隔离，跨团队组织工作，每个工作区拥有自己的智能体、问题和设置。

**技术亮点**: 基于 TypeScript 开发，提供 CLI 工具，支持自托管（需 Docker），并兼容 Claude Code、Codex、OpenClaw 和 OpenCode 等多种智能体提供商。

---
## 7. [coleam00/Archon](https://github.com/coleam00/Archon)
- **语言**: TypeScript
- **Stars**: 17,637
- **简介**: The first open-source harness builder for AI coding. Make AI coding deterministic and repeatable.

### AI 总结
**简介**: Archon 是一个开源的 AI 编码工作流引擎，旨在通过定义 YAML 工作流，使 AI 辅助的软件开发过程变得确定且可重复。

**核心功能**:
- **定义工作流**：将开发流程（如规划、实现、验证、代码审查、创建 PR）编码为 YAML 文件，确保每次执行步骤一致。
- **隔离运行**：每个工作流运行都在独立的 Git 工作树中进行，支持并行处理多个任务而互不冲突。
- **混合执行**：将确定性节点（如 Bash 脚本、测试、Git 操作）与 AI 节点（如规划、代码生成、审查）组合，只在需要智能的地方调用 AI。
- **多平台触发**：工作流可通过 CLI、Web UI、Slack、Telegram 或 GitHub 等多种方式触发，保持行为一致。

**技术亮点**: 使用 TypeScript 开发，工作流定义采用 YAML，通过类似 n8n 的节点式架构来编排 AI 编码代理的任务，并支持循环和人工交互节点以实现迭代开发和审批。

---
## 8. [snarktank/ralph](https://github.com/snarktank/ralph)
- **语言**: TypeScript
- **Stars**: 16,546
- **简介**: Ralph is an autonomous AI agent loop that runs repeatedly until all PRD items are complete.

### AI 总结
**简介**: Ralph 是一个基于 AI 编码工具（Amp 或 Claude Code）的自主代理循环，通过迭代执行直至完成产品需求文档中的所有任务。

**核心功能**:
- 通过 `/prd` 和 `/ralph` 技能，将自然语言需求转化为结构化的 `prd.json` 任务列表。
- 运行 `ralph.sh` 脚本，循环调用 AI 工具，自动选取并实现最高优先级的未完成用户故事。
- 每次迭代均为全新的 AI 实例，仅通过 Git 历史、`progress.txt` 和 `prd.json` 来保持记忆和进度。

**技术亮点**: 采用 Bash 脚本驱动，支持 Amp 和 Claude Code 两种 AI 工具，通过技能（Skills）和插件市场实现与 AI 工具的深度集成，并提供了交互式流程图来可视化工作流程。

---
## 9. [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund)
- **语言**: Python
- **Stars**: 52,991
- **简介**: An AI Hedge Fund Team

### AI 总结
**简介**: 这是一个用于教育目的的概念验证项目，旨在探索利用由多个AI智能体组成的“团队”来模拟投资决策，不进行真实交易。

**核心功能**:
- 集成了19个模拟不同投资大师（如巴菲特、芒格、达摩达兰等）和不同分析维度（估值、基本面、技术面、情绪等）的AI智能体。
- 支持通过命令行界面运行，对指定股票代码进行分析并生成模拟交易决策。
- 提供回测功能，可在特定时间段内评估策略表现。
- 支持通过API连接多种大语言模型（如OpenAI、Groq等）或本地Ollama模型。

**技术亮点**: 采用多智能体协作架构，使用Python开发，依赖Poetry进行包管理，并通过环境变量配置API密钥。

---
## 10. [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks)
- **语言**: Jupyter Notebook
- **Stars**: 39,563
- **简介**: A collection of notebooks/recipes showcasing some fun and effective ways of using Claude.

### AI 总结
**简介**: 一个由 Anthropic 官方维护的 Jupyter Notebook 集合，旨在通过可复用的代码示例和指南，帮助开发者高效地使用 Claude API 进行开发。

**核心功能**:
- **文本处理能力**：提供分类、摘要、检索增强生成（RAG）等核心 NLP 任务的实现示例。
- **工具与集成**：展示如何将 Claude 与外部工具（如计算器、SQL）和第三方服务（如 Pinecone、Wikipedia）结合，扩展其功能。
- **多模态应用**：包含视觉能力（解读图像、图表、PDF）和图像生成（结合 Stable Diffusion）的实践指南。
- **高级技巧**：涵盖子代理协作、自动化评估、JSON 模式等进阶开发技术。

**技术亮点**: 项目以 Python 和 Jupyter Notebook 为主要载体，紧密围绕 Claude API 构建，重点演示了提示工程、工具调用（Tool Use）以及与大模型生态（如向量数据库）的集成。

---
