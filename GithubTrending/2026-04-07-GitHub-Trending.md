---
tags:
  - github-trending
  - daily
date: 2026-04-07
created: 2026-04-07T01:55:48.690Z
---

# 2026-04-07 GitHub Trending Top 10

## 1. [abhigyanpatwari/GitNexus](https://github.com/abhigyanpatwari/GitNexus)
- **语言**: TypeScript
- **Stars**: 23,501
- **简介**: GitNexus: The Zero-Server Code Intelligence Engine - GitNexus is a client-side knowledge graph creator that runs entirely in your browser. Drop in a GitHub repo or ZIP file, and get an interactive knowledge graph wit a built in Graph RAG Agent. Perfect for code exploration

### AI 总结
**简介**: GitNexus 是一个完全在浏览器中运行的客户端知识图谱创建工具，无需服务器，可将代码仓库转换为交互式知识图谱，并内置图增强检索（Graph RAG）智能体，用于代码探索与分析。

**核心功能**:
- **零服务器、浏览器端运行**：通过 Web UI 直接上传 GitHub 仓库或 ZIP 文件，在浏览器内即时生成交互式知识图谱。
- **支持 CLI 与 MCP 集成**：可通过命令行工具本地索引代码库，并通过模型上下文协议（MCP）为 Cursor、Claude Code 等 AI 编码助手提供深度的代码架构视图。
- **企业级功能**：提供 SaaS 或自托管的企业版，支持 PR 审查、自动更新代码维基、多仓库统一图谱等高级功能。

**技术亮点**:
- 使用 **Tree-sitter**（支持 WASM 和原生绑定）进行代码解析。
- 采用 **LadybugDB**（支持 WASM 内存存储和本地持久化）存储知识图谱。
- 架构支持“桥接模式”，允许 Web UI 连接本地 CLI 服务，直接浏览已索引的仓库。

---
## 2. [google-ai-edge/gallery](https://github.com/google-ai-edge/gallery)
- **语言**: Kotlin
- **Stars**: 17,903
- **简介**: A gallery that showcases on-device ML/GenAI use cases and allows people to try and use models locally.

### AI 总结
**简介**: Google AI Edge Gallery 是一个移动端应用，用于在设备本地探索、体验和评估开源的端侧机器学习与生成式AI模型。

**核心功能**:
- **智能体技能**: 为模型增强工具能力，如维基百科查询、交互式地图和视觉摘要卡片。
- **AI聊天与思考模式**: 进行多轮对话，并可查看模型逐步推理过程（支持Gemma 4等模型）。
- **图像问答**: 通过摄像头或相册，使用多模态模型识别物体、解决视觉问题。
- **音频转录**: 实时将语音录音转录或翻译为文本。
- **提示实验室**: 用于测试不同提示词和单轮用例，可精细控制模型参数。
- **移动操作**: 通过微调的FunctionGemma模型实现离线设备控制和自动化任务。
- **模型管理与基准测试**: 轻松下载或加载自定义模型，并运行基准测试评估性能。
- **100%端侧隐私**: 所有模型推理均在设备本地完成，无需网络，确保数据完全私密。

**技术亮点**: 专注于**端侧AI**，支持多种开源大语言模型（LLMs），最新版本集成了**Gemma 4**模型家族，并利用微调的**FunctionGemma**模型实现设备控制功能。应用为Kotlin开发，支持Android 12+和iOS 17+。

---
## 3. [google-ai-edge/LiteRT-LM](https://github.com/google-ai-edge/LiteRT-LM)
- **语言**: C++
- **Stars**: 2,037
- **简介**: 

### AI 总结
**简介**: Google 推出的高性能、生产就绪的开源推理框架，用于在边缘设备上部署大型语言模型。

**核心功能**:
- **广泛的平台支持**: 支持 Android、iOS、Web、桌面及物联网设备（如树莓派）。
- **硬件加速**: 利用 GPU 和 NPU 实现峰值性能。
- **多模态支持**: 支持视觉和音频输入。
- **工具调用**: 支持函数调用，赋能智能体工作流。
- **广泛的模型支持**: 支持 Gemma、Llama、Phi-4、Qwen 等多种主流模型。

**技术亮点**: 提供稳定的 Kotlin、Python、C++ API，支持从 Hugging Face 等源快速加载和运行模型，并已集成于 Chrome、Chromebook Plus、Pixel Watch 等 Google 产品中。

---
## 4. [immich-app/immich](https://github.com/immich-app/immich)
- **语言**: TypeScript
- **Stars**: 96,890
- **简介**: High performance self-hosted photo and video management solution.

### AI 总结
**简介**: Immich 是一个高性能、自托管的照片与视频管理解决方案，旨在为用户提供私有化部署的媒体资产管理服务。

**核心功能**:
- **自动备份与同步**: 支持移动端应用打开时自动备份，并可选择特定相册进行备份，防止资产重复。
- **多媒体管理**: 支持上传、查看、下载照片和视频，包括 RAW 格式、LivePhoto/MotionPhoto 以及 360 度图片。
- **智能搜索与整理**: 支持通过元数据、对象、人脸和 CLIP 进行搜索，并具备人脸识别与聚类功能。
- **协作与分享**: 提供多用户支持、相册、共享相册、公开分享及合作伙伴分享功能。
- **高级视图与工具**: 包含全局地图、时间线回忆（Memories）、虚拟滚动、归档、收藏夹、文件夹视图和标签管理。

**技术亮点**:
- 采用 TypeScript 开发，遵循 AGPLv3 开源协议。
- 提供完善的 Web 与移动端应用，支持离线使用（移动端）。
- 具备 OAuth 支持、API 密钥管理和可自定义的存储结构。
- 项目支持多语言国际化，拥有活跃的社区和 Discord 支持频道。

---
## 5. [KeygraphHQ/shannon](https://github.com/KeygraphHQ/shannon)
- **语言**: TypeScript
- **Stars**: 36,568
- **简介**: Shannon Lite is an autonomous, white-box AI pentester for web applications and APIs. It analyzes your source code, identifies attack vectors, and executes real exploits to prove vulnerabilities before they reach production.

### AI 总结
**简介**: Shannon 是一个由 Keygraph 开发的白盒 AI 渗透测试工具，用于自动分析 Web 应用和 API 的源代码，识别攻击向量并执行真实攻击以验证漏洞。

**核心功能**:
- **全自动操作**：单条命令即可启动完整渗透测试，自动处理登录、浏览器导航、漏洞利用和报告生成。
- **可复现的漏洞验证**：最终报告仅包含已通过实际攻击验证的漏洞，并提供可直接复现的攻击步骤。
- **代码感知的动态测试**：结合源代码分析来指导攻击策略，并通过浏览器和命令行工具对运行中的应用进行实时漏洞验证。
- **并行处理**：支持跨所有攻击类别并行执行漏洞分析和利用。

**技术亮点**: 采用 TypeScript 开发，集成了 Nmap、Subfinder 等安全工具进行侦察；其专业版（Shannon Pro）采用两阶段管道架构，首阶段通过构建代码属性图进行静态分析，第二阶段进行自主渗透测试，实现漏洞的交叉关联与精确定位。

---
## 6. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 28,208
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 开发的自进化 AI 代理，具备内置的学习循环，能够从经验中创建并改进技能，实现跨会话的持续学习和个性化交互。

**核心功能**:
- **多平台接入**: 支持通过 Telegram、Discord、Slack、WhatsApp、Signal 和 CLI 等多种方式与代理交互，实现跨平台对话连续性。
- **自我学习与改进**: 具备封闭的学习循环，可自主创建技能、在任务执行中自我改进，并利用会话搜索和总结实现跨会话记忆。
- **灵活的模型支持**: 支持连接 Nous Portal、OpenRouter、OpenAI 等多种模型提供商，用户可通过命令轻松切换，无代码锁定。
- **强大的调度与自动化**: 内置类似 cron 的调度器，支持用自然语言创建自动化任务（如每日报告、备份），并可在无人值守下运行。
- **并行与委派能力**: 可生成隔离的子代理并行处理工作流，支持通过 RPC 调用工具的 Python 脚本，以降低上下文成本。
- **灵活的部署选项**: 支持在本地、Docker、SSH、Daytona、Singularity 和 Modal 等多种后端运行，尤其适合在低成本 VPS 或 GPU 集群上部署。

**技术亮点**:
- 采用 **Honcho** 进行用户建模，兼容 **agentskills.io** 开放标准。
- 提供完整的终端用户界面（TUI），支持多行编辑、命令自动补全和流式工具输出。
- 支持无服务器持久化（如 Daytona 和 Modal），环境在闲置时可休眠以近乎零成本运行。
- 为研究场景提供批量轨迹生成、Atropos RL 环境和轨迹压缩等功能。

---
## 7. [tobi/qmd](https://github.com/tobi/qmd)
- **语言**: TypeScript
- **Stars**: 18,781
- **简介**: mini cli search engine for your docs, knowledge bases, meeting notes, whatever. Tracking current sota approaches while being all local

### AI 总结
**简介**: QMD 是一个本地化、多功能的命令行搜索引擎，专为索引和搜索个人文档、笔记、会议记录和知识库而设计。

**核心功能**:
- **混合搜索**: 支持关键词搜索 (`search`)、语义向量搜索 (`vsearch`) 以及结合了 BM25、向量搜索和 LLM 重排的混合查询 (`query`)。
- **文档管理**: 可创建和管理多个文档集合，支持通过路径、ID 或通配符模式获取单个或多个文档。
- **上下文关联**: 可为集合添加树状上下文描述，显著提升 LLM 在搜索结果中的上下文理解能力。
- **AI 代理集成**: 提供 JSON 和文件列表输出格式，便于 AI 代理工作流集成，并内置 MCP 服务器，支持与 Claude 等工具深度集成。
- **灵活部署**: 可作为全局命令行工具、Node.js/Bun 库使用，MCP 服务器支持 stdio 和 HTTP 两种传输模式，后者可实现模型常驻内存。

**技术亮点**: 采用 TypeScript 开发，核心技术栈结合了 BM25 全文检索、本地向量语义搜索（通过 `node-llama-cpp` 与 GGUF 模型）以及 LLM 重排序，所有计算均在本地设备上完成，保障隐私。

---
## 8. [TelegramMessenger/Telegram-iOS](https://github.com/TelegramMessenger/Telegram-iOS)
- **语言**: Swift
- **Stars**: 8,318
- **简介**: Telegram-iOS

### AI 总结
**简介**: Telegram iOS 客户端开源项目，为开发者提供了基于其API和源码构建自定义应用的完整指南和代码。

**核心功能**:
- 提供完整的Telegram iOS客户端源代码，可供研究和二次开发。
- 包含详细的编译指南，支持生成Xcode工程和构建IPA安装包。
- 明确了开发者使用其平台创建应用时的规范和要求（如申请独立API ID、品牌使用限制等）。

**技术亮点**:
- 使用Swift语言开发。
- 采用Bazel构建系统，通过Python脚本管理复杂的项目生成和构建流程。
- 支持灵活的代码签名配置，并提供了模拟器构建免签名的优化选项。

---
## 9. [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills)
- **语言**: Unknown
- **Stars**: 20,607
- **简介**: Agent skills for Obsidian. Teach your agent to use Markdown, Bases, JSON Canvas, and use the CLI.

### AI 总结
**简介**: 这是一个为 Obsidian 笔记软件设计的 Agent Skills 集合，旨在让 AI 助手能够使用 Markdown、Bases、JSON Canvas 等 Obsidian 特定格式，并通过 CLI 与 Obsidian 库交互。

**核心功能**:
- 提供创建和编辑 Obsidian 风味 Markdown（含 wikilinks、callouts 等语法）的技能。
- 提供创建和编辑 Obsidian Bases（含视图、过滤器、公式）的技能。
- 提供创建和编辑 JSON Canvas 文件的技能。
- 提供通过 Obsidian CLI 与库交互（包括插件和主题开发）的技能。
- 提供使用 Defuddle 工具从网页提取纯净 Markdown 以节省 Token 的技能。

**技术亮点**: 遵循 [Agent Skills 规范](https://agentskills.io/specification)，兼容 Claude Code、Codex CLI 和 OpenCode 等多种技能兼容的 AI 代理。

---
## 10. [ollama/ollama](https://github.com/ollama/ollama)
- **语言**: Go
- **Stars**: 167,723
- **简介**: Get up and running with Kimi-K2.5, GLM-5, MiniMax, DeepSeek, gpt-oss, Qwen, Gemma and other models.

### AI 总结
**简介**: Ollama 是一个开源项目，旨在帮助开发者快速启动和使用 Kimi-K2.5、GLM-5、MiniMax、DeepSeek、gpt-oss、Qwen、Gemma 等多种开源大语言模型。

**核心功能**:
- **模型运行与管理**: 提供命令行工具，支持直接运行、聊天和启动特定模型（如 Gemma 3）。
- **多平台集成**: 支持与 Claude Code、Codex、OpenClaw 等外部代理或应用连接，可构建跨平台（如 WhatsApp、Telegram）的 AI 助手。
- **丰富的 API 支持**: 提供 REST API 以及 Python 和 JavaScript 官方库，便于开发者将模型能力集成到自己的应用中。
- **便捷的部署方式**: 支持 macOS、Windows、Linux 系统的一键安装脚本，并提供 Docker 镜像。

**技术亮点**:
- **后端支持**: 基于 Georgi Gerganov 的 `llama.cpp` 项目，提供高效的本机模型推理。
- **活跃的社区生态**: 拥有大量社区集成项目，包括 Open WebUI、Lobe Chat、NextChat 等流行的 Web 和桌面聊天界面。

---
