---
tags:
  - github-trending
  - daily
date: 2026-03-11
created: 2026-03-11T01:55:48.463Z
---

# 2026-03-11 GitHub Trending Top 10

## 1. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 25,616
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个包含多种专业化 AI 代理角色的集合，旨在通过具备独特个性和工作流程的 AI 助手来提升开发与设计工作效率。

**核心功能**:
- 提供涵盖工程、设计等多个领域的专业化 AI 代理，如前端开发、后端架构、UI/UX 设计等。
- 支持与多种开发工具（如 Claude Code、Cursor、Aider 等）快速集成，方便调用。
- 每个代理都具备明确的专业领域、个性特质、工作流程和可交付成果。

**技术亮点**: 项目主要提供代理配置（Shell 脚本），支持通过脚本一键生成并安装到多种主流 AI 编程助手和 IDE 工具中，实现开箱即用的 AI 专家团队集成。

---
## 2. [666ghj/MiroFish](https://github.com/666ghj/MiroFish)
- **语言**: Python
- **Stars**: 14,301
- **简介**: A Simple and Universal Swarm Intelligence Engine, Predicting Anything. 简洁通用的群体智能引擎，预测万物

### AI 总结
**简介**: MiroFish 是一个基于多智能体技术的群体智能预测引擎，能够通过输入种子信息（如新闻、报告或小说）构建高保真的数字平行世界，并模拟其中智能体的交互演化，从而生成预测报告。

**核心功能**:
- **平行世界构建**：根据用户提供的文本材料（如舆情报告、小说），自动抽取信息并构建一个包含众多具备独立人格和记忆的智能体的数字世界。
- **未来推演预测**：在构建的数字世界中，通过“上帝视角”动态注入变量，模拟智能体的社会交互与演化，推演事件或故事的可能走向。
- **交互式报告生成**：模拟结束后，系统会生成详细的预测报告，并允许用户与模拟世界中的智能体或报告生成代理进行深度对话。

**技术亮点**:
- **多智能体模拟**：核心引擎依赖大量具备长期记忆和行为逻辑的智能体进行自由交互，以捕捉群体涌现现象。
- **GraphRAG 与记忆管理**：利用图谱增强检索（GraphRAG）技术构建知识，并集成 Zep Cloud 服务来管理智能体的长期记忆。
- **现代化技术栈**：项目采用前后端分离架构，前端基于 Node.js，后端使用 Python (≥3.11)，并推荐使用 `uv` 作为 Python 包管理器，支持 Docker 一键部署。

---
## 3. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 3,826
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是由 Nous Research 开发的一款具备自我学习能力的 AI 智能体，能够从经验中创建并改进技能，实现跨会话的持续成长。

**核心功能**:
- **自我改进的学习闭环**: 具备内置学习循环，可从复杂任务中自主创建技能，并在使用中自我改进。支持基于 LLM 总结的跨会话记忆搜索和用户建模。
- **多平台与多模态接入**: 支持通过单一网关进程接入 Telegram、Discord、Slack、CLI 等多种平台，并支持语音备忘录转录。
- **灵活部署与模型无关**: 可在多种环境（本地、Docker、SSH、Serverless 等）运行，并支持无缝切换 Nous Portal、OpenRouter、OpenAI 等众多模型提供商，无厂商锁定。
- **自动化与并行处理**: 内置定时任务调度器，支持自然语言描述自动化任务。可生成隔离的子代理进行并行工作流处理。
- **完整的终端界面**: 提供功能齐全的终端用户界面，支持多行编辑、命令自动补全、对话历史和流式工具输出。

**技术亮点**:
- 采用模块化设计，支持多种终端后端和模型端点。
- 集成 Honcho 进行用户建模，并兼容 agentskills.io 开放标准。
- 提供研究支持功能，如批量轨迹生成和 Atropos RL 环境，用于训练下一代工具调用模型。

---
## 4. [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo)
- **语言**: TypeScript
- **Stars**: 11,985
- **简介**: Test your prompts, agents, and RAGs. AI Red teaming, pentesting, and vulnerability scanning for LLMs. Compare performance of GPT, Claude, Gemini, Llama, and more. Simple declarative configs with command line and CI/CD integration.

### AI 总结
**简介**: Promptfoo 是一个用于评估和红队测试 LLM 应用的 CLI 工具和库，旨在帮助开发者构建安全、可靠的 AI 应用。

**核心功能**:
- **自动化评估与测试**：支持对提示词、模型和 RAG 系统进行自动化测试和评估。
- **红队测试与安全扫描**：提供针对 LLM 应用的红队测试、渗透测试和漏洞扫描功能。
- **多模型对比**：可并排比较 OpenAI、Claude、Gemini、Llama 等多种主流模型的表现。
- **CI/CD 集成**：支持在持续集成/持续部署流程中自动化运行检查。
- **代码扫描**：可审查 Pull Request 中与 LLM 相关的安全和合规问题。
- **团队协作**：支持与团队共享评估结果和报告。

**技术亮点**:
- **开发者友好**：提供命令行工具、声明式配置、实时重载和缓存等功能。
- **隐私保护**：评估过程 100% 在本地运行，提示词和敏感数据不会外传。
- **灵活可扩展**：支持任何 LLM API 和编程语言，拥有活跃的开源社区。
- **生产验证**：已为服务数千万用户的生产级 LLM 应用提供支持。
- **技术栈**：基于 TypeScript 开发，可通过 npm、brew、pip 等多种方式安装。

---
## 5. [GoogleCloudPlatform/generative-ai](https://github.com/GoogleCloudPlatform/generative-ai)
- **语言**: Jupyter Notebook
- **Stars**: 15,766
- **简介**: Sample code and notebooks for Generative AI on Google Cloud, with Gemini on Vertex AI

### AI 总结
**简介**: 这是一个 Google Cloud 官方提供的资源库，包含用于在 Google Cloud 和 Vertex AI 上使用、开发和管理生成式 AI 工作流的示例代码、笔记本和应用程序。

**核心功能**:
- 提供 Gemini 系列模型（包括最新的 Gemini 3.1 Pro）的入门教程、用例演示、函数调用等示例。
- 涵盖 Vertex AI Search（企业搜索）、RAG 与 Grounding、Imagen 图像生成与编辑、Chirp 语音处理等多种生成式 AI 应用场景。
- 包含详细的 Google Cloud 环境、SDK 及笔记本（Colab/Vertex AI Workbench）设置指南。

**技术亮点**: 专注于 Google Cloud 的生成式 AI 全栈技术，核心基于 Vertex AI 平台，整合了 Gemini、Imagen、Chirp 等前沿模型，并提供从环境配置到生产级应用（如 Agent 开发）的完整示例。

---
## 6. [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund)
- **语言**: Python
- **Stars**: 47,624
- **简介**: An AI Hedge Fund Team

### AI 总结
**简介**: 这是一个用于教育研究的AI驱动对冲基金概念验证项目，通过模拟多位著名投资大师风格的智能体协作，对股票进行分析并生成交易信号，但不进行真实交易。

**核心功能**:
- 集成18个功能各异的智能体，涵盖估值、基本面、技术面、市场情绪分析和风险管理等多个维度。
- 支持命令行界面和Web应用两种运行方式，提供灵活的操作体验。
- 可配置使用OpenAI、Groq、Anthropic、DeepSeek或本地Ollama等多种大语言模型作为推理引擎。

**技术亮点**: 项目采用Python开发，使用Poetry进行依赖管理，架构上实现了多智能体协作决策系统，并支持通过环境变量灵活配置API密钥。

---
## 7. [karpathy/nanochat](https://github.com/karpathy/nanochat)
- **语言**: Python
- **Stars**: 46,269
- **简介**: The best ChatGPT that $100 can buy.

### AI 总结
**简介**: nanochat 是一个极简、可修改的实验框架，用于在单GPU节点上训练大型语言模型，能以极低成本复现GPT-2级别模型。

**核心功能**:
- 覆盖LLM全流程：分词、预训练、微调、评估、推理及类ChatGPT的Web UI对话界面。
- 通过单一复杂度参数（`--depth`）自动配置并训练一系列计算最优的模型。
- 提供完整的“GPT-2速通”脚本，可在约2小时（成本约48美元）内训练出达到GPT-2能力的模型。

**技术亮点**:
- 专为单GPU节点设计，代码简洁、易于修改。
- 包含社区驱动的“Time-to-GPT-2”排行榜，追踪并优化训练效率。
- 支持在8×H100等GPU节点上高效运行，并能向下兼容单GPU环境。

---
## 8. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 76,632
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为 AI 编码智能体设计的、基于可组合“技能”的软件开发框架和工作流。

**核心功能**:
- **引导式设计**：在编码前通过提问澄清需求，并以可消化的小块呈现设计供用户确认。
- **结构化实施**：基于批准的设计，创建清晰、细粒度的实施计划，强调 TDD、YAGNI 和 DRY 原则。
- **子智能体驱动开发**：启动子智能体按计划执行工程任务，并进行检查和评审，实现长时间自主工作。
- **自动化技能触发**：内置多种技能（如测试驱动开发、系统化调试、代码审查），在相关任务前自动触发，强制执行标准化工作流。

**技术亮点**: 采用基于 Shell 的插件化架构，支持在 Claude Code、Cursor、Codex 和 OpenCode 等多种 AI 编码平台中安装和运行。

---
## 9. [alibaba/page-agent](https://github.com/alibaba/page-agent)
- **语言**: TypeScript
- **Stars**: 3,687
- **简介**: JavaScript in-page GUI agent. Control web interfaces with natural language.

### AI 总结
**简介**: 一个运行在网页内的 JavaScript GUI 代理，允许用户使用自然语言控制 Web 界面。

**核心功能**:
- **易于集成**：无需浏览器扩展、Python 或无头浏览器，仅需在页面内引入 JavaScript。
- **基于文本的 DOM 操作**：无需截图、OCR 或多模态大语言模型，也无需特殊权限。
- **支持自带 LLM**：可灵活接入用户自己的大语言模型。
- **美观的 UI 与人机协同**：提供友好的交互界面。
- **可选 Chrome 扩展**：支持跨浏览器标签页的多页面任务。

**技术亮点**:
- 基于 TypeScript 开发。
- 采用客户端（浏览器内）架构，专为网页增强设计，而非服务端自动化。
- 项目灵感与部分组件源自优秀的开源项目 `browser-use`。

---
## 10. [sepinf-inc/IPED](https://github.com/sepinf-inc/IPED)
- **语言**: Java
- **Stars**: 2,223
- **简介**: IPED Digital Forensic Tool. It is an open source software that can be used to process and analyze digital evidence, often seized at crime scenes by law enforcement or in a corporate investigation by private examiners.

### AI 总结
**简介**: IPED 是一款开源的数字取证工具，由巴西联邦警察的取证专家开发，用于高效处理和分析执法或企业调查中获取的数字证据。

**核心功能**:
- 支持多种磁盘镜像和文件系统格式（如 RAW/DD、E01、VMDK 等）的解码与处理。
- 提供强大的索引与搜索能力，包括文件内容、元数据及未分配空间的快速检索。
- 内置多种分析模块，如哈希计算、签名分析、文件分类、递归容器扩展、数据雕刻、OCR 文字识别等。
- 支持高级功能，如相似图像/人脸识别、时间线分析、命名实体识别、加密检测以及可定制的脚本扩展（JavaScript/Python）。

**技术亮点**:
- 基于 Java 开发，跨平台支持（Windows/Linux），具备高并发处理能力，实测处理速度可达 400GB/小时。
- 集成 Sleuthkit 库进行底层镜像解析，并支持多案例处理（可达 1.35 亿项）。
- 模块化设计，可通过脚本和外部工具灵活扩展，并提供了针对特定场景（如儿童性虐待材料调查）的专用处理模式。

---
