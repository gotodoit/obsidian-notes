---
tags:
  - github-trending
  - daily
date: 2026-02-14
created: 2026-02-14T01:55:51.204Z
---

# 2026-02-14 GitHub Trending Top 10

## 1. [SynkraAI/aios-core](https://github.com/SynkraAI/aios-core)
- **语言**: JavaScript
- **Stars**: 436
- **简介**: Synkra AIOS: AI-Orchestrated System for Full Stack Development - Core Framework v4.0

### AI 总结
**简介**: Synkra AIOS 是一个由人工智能驱动的、可自我修改的通用 AI 代理框架，专注于全栈开发，采用“CLI优先”的架构理念。

**核心功能**:
- **AI 驱动的双阶段工作流**：提供“代理规划”和“上下文工程开发”两个关键创新阶段，由专门的 AI 代理（如分析师、产品经理、架构师、Scrum Master、开发、QA）协作完成从需求规划到代码实现的完整闭环。
- **CLI 优先架构**：将命令行界面作为系统的核心和唯一真相源，所有执行、决策和自动化首先在此完成，UI 仅用于辅助观察和管理。
- **全面的可观测性**：提供实时仪表盘、日志、指标和时间线，用于监控 CLI 中 AI 代理的活动和决策过程。

**技术亮点**:
- **架构**：明确分层（CLI → 可观测性 → UI），强调功能必须 100% 通过 CLI 运行后才考虑 UI。
- **技术栈**：基于 Node.js (>=18.0.0)，使用 npm 包管理，提供完整的 CI/CD 集成和测试覆盖。
- **生态**：支持多语言文档，提供跨平台（macOS、Windows、Linux）安装指南，并遵循开源贡献规范。

---
## 2. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)
- **语言**: TypeScript
- **Stars**: 24,732
- **简介**: Chrome DevTools for coding agents

### AI 总结
**简介**: Chrome DevTools MCP 是一个基于 Model-Context-Protocol (MCP) 的服务器，它能让 AI 编程助手（如 Claude、Cursor 等）连接并控制一个正在运行的 Chrome 浏览器，从而进行自动化、调试和性能分析。

**核心功能**:
- **性能洞察**: 利用 Chrome DevTools 记录性能追踪数据，并提供可操作的性能改进建议。
- **高级浏览器调试**: 分析网络请求、截取屏幕截图、检查浏览器控制台消息（支持源码映射的堆栈跟踪）。
- **可靠自动化**: 基于 Puppeteer 自动化 Chrome 中的操作，并自动等待操作结果。

**技术亮点**:
- 作为 MCP 服务器，为 AI 助手提供了标准化的浏览器控制接口。
- 底层整合了 Chrome DevTools Protocol 和 Puppeteer，实现强大的浏览器操控能力。
- 支持通过 Google CrUX API 获取真实用户性能数据，以补充实验室数据。

---
## 3. [danielmiessler/Personal_AI_Infrastructure](https://github.com/danielmiessler/Personal_AI_Infrastructure)
- **语言**: TypeScript
- **Stars**: 8,069
- **简介**: Agentic AI Infrastructure for magnifying HUMAN capabilities.

### AI 总结
**简介**: 一个旨在通过智能体化AI基础设施来放大个人能力、帮助人们进行自我发现并追求个人目标的个人AI栈项目。

**核心功能**:
*   **激活个人潜力**：通过AI辅助的自我发现，帮助人们识别、阐明并追求自己的人生目标。
*     **提供顶级AI能力**：致力于让世界上最好的AI技术能够被每个人所使用。
*   **模块化与可组合**：提供“包”（Packs）和“捆绑包”（Bundles）等组件，允许用户构建和定制自己的AI工作流。

**技术亮点**: 项目主要使用 **TypeScript** 开发，并采用 **Bun** 运行时。其架构强调智能体（Agentic）模式，并引入了“双通道能力选择”、“并行执行”等设计来提升思考深度和执行效率。

---
## 4. [patchy631/ai-engineering-hub](https://github.com/patchy631/ai-engineering-hub)
- **语言**: Jupyter Notebook
- **Stars**: 29,323
- **简介**: In-depth tutorials on LLMs, RAGs and real-world AI agent applications.

### AI 总结
**简介**: 这是一个专注于 AI 工程实践的综合性学习与项目资源库，提供从入门到高级的教程和超过 93 个生产就绪项目。

**核心功能**:
- 提供涵盖 LLM、RAG、智能体等主题的深度教程。
- 包含大量按难度分级（初级、中级、高级）的实战项目，例如 OCR 应用、聊天界面、RAG 系统和工作流代理。
- 旨在帮助不同水平的开发者通过动手实践掌握 AI 工程技能。

**技术亮点**: 项目广泛使用主流开源模型（如 Llama、Gemma、Qwen、DeepSeek）和框架（如 LlamaIndex、Streamlit、CrewAI），并强调本地部署和实际应用。

---
## 5. [TelegramMessenger/MTProxy](https://github.com/TelegramMessenger/MTProxy)
- **语言**: C
- **Stars**: 5,888
- **简介**: 

### AI 总结
**简介**: 一个由 Telegram 官方维护的、用于搭建 MTProto 代理服务器的轻量级工具。

**核心功能**:
- 编译生成 MTProto 代理服务器二进制文件。
- 运行代理服务，为 Telegram 客户端提供连接支持。
- 支持多工作进程、随机数据包填充（以规避 ISP 检测）和统计信息查询。
- 提供 Systemd 服务配置示例，便于在 Linux 系统中以服务形式运行和管理。
- 支持通过 Docker 镜像部署（但官方镜像可能已过时）。

**技术亮点**:
- 使用 C 语言编写，性能高效。
- 通过 `setuid()` 降低运行权限，增强安全性。
- 支持动态获取并定期更新 Telegram 服务器配置和代理密钥。
- 可配置随机数据包填充，提升代理的隐蔽性。

---
## 6. [google-deepmind/superhuman](https://github.com/google-deepmind/superhuman)
- **语言**: TeX
- **Stars**: 378
- **简介**: 

### AI 总结
**简介**: Google DeepMind Superhuman Reasoning 团队发布的用于评估和推进AI数学推理能力的项目与数据集集合。

**核心功能**:
- **AlphaGeometry/AlphaGeometry2**: 解决奥林匹克几何问题的AI系统，分别达到IMO铜牌和银牌水平。
- **IMO Bench**: 一套用于评估AI数学推理能力的先进基准，包含短答题、证明题和自动评分数据集。
- **Aletheia**: 一个由Gemini Deep Think驱动的数学研究智能体，能够迭代生成、验证和修订解决方案。

**技术亮点**: 项目集成了大型语言模型（如Gemini Deep Think）进行复杂推理，并提供了结构化、专家验证的数学问题数据集以推动AI推理研究。

---
## 7. [cheahjs/free-llm-api-resources](https://github.com/cheahjs/free-llm-api-resources)
- **语言**: Python
- **Stars**: 10,661
- **简介**: A list of free LLM inference resources accessible via API.

### AI 总结
**简介**: 一个收集了可通过 API 免费访问或提供试用额度的大型语言模型（LLM）推理资源的列表项目。

**核心功能**:
- 分类整理并提供多家主流厂商（如 OpenRouter、Google AI Studio、NVIDIA、Mistral、HuggingFace 等）的免费 LLM API 服务链接。
- 详细列出各服务商提供的具体模型（如 Gemma、Llama、Mistral 系列等）及其使用限制（如请求频率、每日额度）。
- 区分“完全免费提供商”和“提供试用额度的提供商”两大类，方便用户按需选择。

**技术亮点**: 项目使用 Python 脚本 (`src/pull_available_models.py`) 自动生成和维护 README 内容，确保列表信息的时效性和准确性。

---
## 8. [HandsOnLLM/Hands-On-Large-Language-Models](https://github.com/HandsOnLLM/Hands-On-Large-Language-Models)
- **语言**: Jupyter Notebook
- **Stars**: 21,162
- **简介**: Official code repo for the O'Reilly Book - "Hands-On Large Language Models"

### AI 总结
**简介**: 这是 O'Reilly 书籍《Hands-On Large Language Models》（也被作者戏称为“图解 LLM 书”）的官方代码仓库，旨在通过大量可视化图表和代码示例，帮助读者学习和实践大语言模型。

**核心功能**:
- 提供与书籍各章节配套的 Jupyter Notebook 代码示例。
- 所有示例均设计为可在 Google Colab 上免费运行，便于快速上手和实践。

**技术亮点**: 项目以 Jupyter Notebook 为主要形式，内容涵盖从语言模型基础、Transformer 内部机制到文本分类、聚类、提示工程等核心应用，强调实践性和可视化教学。

---
## 9. [THUDM/slime](https://github.com/THUDM/slime)
- **语言**: Python
- **Stars**: 4,086
- **简介**: slime is an LLM post-training framework for RL Scaling.

### AI 总结
**简介**: slime 是一个专为大语言模型强化学习后训练设计的高性能框架。

**核心功能**:
- **高性能训练**: 通过连接 Megatron 与 SGLang，支持多种模式下的高效训练。
- **灵活数据生成**: 通过自定义数据生成接口和基于服务器的引擎，支持任意训练数据生成工作流。

**技术亮点**:
- **模块化架构**: 包含训练（Megatron）、推演（SGLang + 路由）和数据缓冲三大核心模块，实现训练与数据生成的解耦。
- **广泛模型支持**: 支持 GLM-4 系列、Qwen 系列、DeepSeek V3 系列及 Llama 3 等多种主流模型。
- **赋能前沿研究**: 已成功应用于物理推理（P1）、可验证环境强化学习（RLVE）、GPU内核生成（TritonForge）等多个创新项目。

---
## 10. [DebugSwift/DebugSwift](https://github.com/DebugSwift/DebugSwift)
- **语言**: Swift
- **Stars**: 1,445
- **简介**: A toolkit to make debugging iOS applications easier 🚀

### AI 总结
**简介**: DebugSwift 是一个专为 Swift 应用设计的综合性调试工具包，旨在简化和提升 iOS 应用的调试体验。

**核心功能**:
- **网络检查器**：监控 HTTP/WebSocket 请求与响应，支持内容格式化、加密解密和请求限制。
- **性能监控**：实时监测 CPU、内存、FPS，自动检测内存泄漏和主线程违规。
- **应用工具**：提供崩溃报告、控制台日志、设备信息、APNS 令牌管理及自定义操作。
- **界面工具**：包含网格覆盖、3D视图层级检查、触摸指示器、动画控制和 SwiftUI 渲染跟踪。
- **资源管理**：支持浏览沙盒文件、查看/修改 UserDefaults、检查 Keychain 和数据库。

**技术亮点**: 支持 Swift 6.0+ 和 Xcode 16.0+，提供 Swift Package Manager、CocoaPods（含 XCFramework 分发）两种安装方式，并原生支持 Apple Silicon Mac 的 arm64 模拟器架构。

---
