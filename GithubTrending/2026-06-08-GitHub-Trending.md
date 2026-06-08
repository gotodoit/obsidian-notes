---
tags:
  - github-trending
  - daily
date: 2026-06-08
created: 2026-06-08T01:55:44.242Z
---

# 2026-06-08 GitHub Trending Top 10

## 1. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 31,190
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: /last30days 是一个 AI agent 驱动的搜索引擎，能从 Reddit、X、YouTube、HN、Polymarket 等多个平台并行搜索，并根据真实用户的点赞、投币等互动行为对结果进行评分，合成一份有依据的摘要。

**核心功能**:
- **多平台并行搜索**: 同时搜索 Reddit、X、YouTube、TikTok、HN、Polymarket、GitHub 等平台，打破信息孤岛。
- **基于真实互动的评分**: 使用 Reddit 的赞、X 的喜欢、Polymarket 的赌注等真实用户行为作为评分依据，而非编辑推荐。
- **AI 智能摘要**: 由 AI agent 综合所有搜索结果，生成一份简洁、有依据的摘要。
- **零配置快速启动**: Reddit、HN 等平台无需额外配置即可使用，并内置设置向导，可快速解锁 X、YouTube 等平台。

**技术亮点**:
- **Python 实现**: 基于 Python 构建。
- **Agent Skills 生态**: 兼容 Claude Code、Codex、Cursor、Copilot、Gemini CLI 等 50+ 主流 Agent 工具。
- **插件化架构**: 通过 `npx skills add` 或 `plugin` 命令轻松安装，支持全局或项目级使用。

---
## 2. [opencv/opencv](https://github.com/opencv/opencv)
- **语言**: C++
- **Stars**: 88,114
- **简介**: Open Source Computer Vision Library

### AI 总结
**简介**: OpenCV 是一个开源的计算机视觉库，提供丰富的图像和视频处理功能，广泛应用于学术与工业领域。

**核心功能**:
- 图像处理（滤波、变换、特征检测等）
- 视频分析与目标跟踪
- 机器学习与深度学习模型支持
- 相机标定与三维重建

**技术亮点**: 基于 C++ 开发，提供 Python、Java、MATLAB 等多语言接口，支持 GPU 加速，拥有活跃的社区与完善的文档。

---
## 3. [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)
- **语言**: Shell
- **Stars**: 36,782
- **简介**: Taste-Skill - gives your AI good taste. stops the AI from generating boring, generic slop

### AI 总结
**简介**: Taste-Skill 是一个为 AI 前端代理提供“品味”的开源框架，旨在通过可移植的 Agent Skills 让 AI 生成更具设计感、更少模板化的用户界面。

**核心功能**:
- **增强 AI 界面设计**：提供预定义的技能，用于提升 AI 生成界面的布局、排版、动效和间距，避免生成单调乏味的“模板化”内容。
- **支持代码与图像生成**：包含用于代码生成的技能和用于生成参考板（网页、移动端、品牌套件）的图像生成技能。
- **兼容主流 AI 代理**：可与 Codex、Cursor、Claude Code 等工具配合使用，也可直接复制 SKILL.md 文件或在 ChatGPT 对话中使用。
- **单次安装，多技能选择**：通过 `npx skills add` 命令即可安装所有技能，或使用 `--skill` 参数单独安装特定技能（如 `design-taste-frontend`）。
- **版本管理与升级**：提供 v2（实验性重写版）和 v1（稳定版）两个版本，用户可按需选择或升级。

**技术亮点**:
- **基于 Agent Skills 框架**：利用 Vercel 的 `agent-skills` CLI 工具实现技能的发现和安装，架构清晰、易于扩展。
- **Shell 脚本驱动**：项目主要使用 Shell 脚本实现，轻量且易于集成到各种开发工作流中。
- **设计系统映射**：技能能够推断设计语言，调整“方差/动效/密度”等参数，并执行严格的预检和重设计审计协议。

---
## 4. [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **语言**: Python
- **Stars**: 186,018
- **简介**: The agent that grows with you

### AI 总结
**简介**: Hermes Agent 是一个由 Nous Research 构建的自我进化 AI 代理，具备内置学习循环，能通过经验创建技能、跨会话记忆用户信息，并可在低至 5 美元的 VPS 或 GPU 集群上运行。

**核心功能**:
- **自我学习循环**: 自主从复杂任务中创建技能，并在使用中自我改进；通过定期提示和 FTS5 会话搜索实现跨会话记忆。
- **多平台支持**: 通过单一网关进程支持 Telegram、Discord、Slack、WhatsApp、Signal 和 CLI，并具备语音备忘录转录和跨平台对话连续性。
- **定时自动化**: 内置 cron 调度器，支持自然语言设定每日报告、夜间备份等任务，可投递至任何平台。
- **任务委派与并行**: 可生成隔离子代理处理并行工作流，通过 RPC 调用工具编写 Python 脚本，简化多步骤任务。
- **灵活部署**: 支持本地、Docker、SSH、Singularity、Modal 和 Daytona 六种终端后端；Modal 和 Daytona 提供无服务器持久化，空闲时几乎零成本。
- **模型无关**: 支持 Nous Portal、OpenRouter、OpenAI 等 200+ 模型，可通过 `hermes model` 命令随时切换，无代码锁定。

**技术亮点**: 使用 Python 构建，集成 FTS5 全文搜索与 LLM 摘要实现记忆系统，兼容 agentskills.io 开放标准，支持通过 Honcho 进行辩证用户建模，并提供批处理轨迹生成与压缩功能以支持研究用途。

---
## 5. [lfnovo/open-notebook](https://github.com/lfnovo/open-notebook)
- **语言**: TypeScript
- **Stars**: 27,306
- **简介**: An Open Source implementation of Notebook LM with more flexibility and features

### AI 总结
**简介**: Open Notebook 是一个开源、注重隐私的 Notebook LM 替代品，提供更灵活、功能更丰富的 AI 笔记与研究体验。

**核心功能**:
- 🔒 **数据隐私与自托管**：完全掌控数据，支持本地部署，确保研究隐私安全。
- 🤖 **多模型 AI 支持**：兼容 18+ 提供商（如 OpenAI、Anthropic、Ollama、LM Studio），可自由选择模型。
- 📚 **多模态内容管理**：支持 PDF、视频、音频、网页等多种内容类型的导入与组织。
- 🎙️ **专业播客生成**：支持 1-4 个自定义角色的多说话人播客生成。
- 🔍 **智能搜索**：提供全文搜索和向量搜索，快速检索所有内容。
- 💬 **上下文聊天**：基于研究内容的 AI 对话，实现智能问答。
- 🌐 **多语言界面**：支持英语、中文、日语、俄语等多种语言。

**技术亮点**: 基于 Python、Next.js、React、SurrealDB 和 LangChain 构建，提供完整的 REST API 接口，支持 Docker 一键部署，实现 100% 本地运行和无限可定制性。

---
## 6. [yikart/AiToEarn](https://github.com/yikart/AiToEarn)
- **语言**: TypeScript
- **Stars**: 18,810
- **简介**: Let's use AI to Earn!

### AI 总结
**简介**: AiToEarn 是一个面向 OPC（一人公司）和创作者的一站式 AI 内容营销平台，通过 AI Agent 自动化实现内容创作、分发、互动与变现。

**核心功能**:
- **💰 Monetize (内容赚钱)**: 提供 CPS、CPE、CPM 三种结果导向的结算模式，帮助创作者通过发布内容完成商家推广任务来赚钱。
- **📢 Publish (内容发布 Agent)**: 支持一键将内容分发至抖音、YouTube、TikTok 等 10+ 全球主流平台，并提供日历排期功能。
- **💬 Engage (内容互动 Agent)**: 通过浏览器插件实现自动点赞、收藏、关注，并提供 AI 智能回复、评论挖掘和品牌监测功能。
- **🎨 Create (内容创作 Agent)**: Agent 驱动的自动化内容制作，支持调用多种 AI 模型（如 Grok、Veo、Nano Banana）进行视频/图文生成、翻译、剪辑和批量创作。

**技术亮点**: 基于 TypeScript 开发，采用 AI Agent 架构重构内容制作与分发流程；支持 Docker 一键私有化部署，并兼容 MCP 协议，可在 Claude、Cursor 等 AI 工具中直接调用。

---
## 7. [aaif-goose/goose](https://github.com/aaif-goose/goose)
- **语言**: Rust
- **Stars**: 47,538
- **简介**: an open source, extensible AI agent that goes beyond code suggestions - install, execute, edit, and test with any LLM

### AI 总结
**简介**: goose 是一个开源的、可扩展的通用 AI 代理，支持桌面应用、CLI 和 API，可用于代码、工作流等多种任务。

**核心功能**:
- 支持 macOS、Linux 和 Windows 原生桌面应用
- 提供完整的 CLI 终端工作流和可嵌入的 API
- 兼容 15+ 大语言模型提供商（Anthropic、OpenAI、Google、Ollama 等）
- 通过 Model Context Protocol 连接 70+ 扩展

**技术亮点**: 使用 Rust 语言构建，注重性能和可移植性；隶属于 Linux 基金会下的 Agentic AI Foundation；支持自定义发行版构建。

---
## 8. [Crosstalk-Solutions/project-nomad](https://github.com/Crosstalk-Solutions/project-nomad)
- **语言**: TypeScript
- **Stars**: 29,755
- **简介**: Project N.O.M.A.D, is a self-contained, offline survival computer packed with critical tools, knowledge, and AI to keep you informed and empowered—anytime, anywhere.

### AI 总结
**简介**: Project N.O.M.A.D. 是一个自包含、离线优先的知识与教育服务器，集成了关键工具、知识库和 AI，确保用户随时随地都能获取信息和赋能。

**核心功能**:
- **AI 聊天与知识库**：本地 AI 聊天，支持文档上传和语义搜索（RAG）。
- **离线信息库**：提供离线维基百科、医学参考、电子书等。
- **教育平台**：Khan Academy 课程，支持进度追踪和多用户。
- **离线地图**：可下载的区域地图，支持搜索和导航。
- **数据工具**：加密、编码和数据分析工具。
- **笔记系统**：本地 Markdown 笔记。
- **系统基准测试**：硬件评分与社区排行榜。

**技术亮点**: 基于 Docker 容器化编排，使用 Ollama 和 Qdrant 实现本地 AI，Kiwix 提供离线内容，Kolibri 支持教育，ProtonMaps 提供地图，CyberChef 处理数据。采用 TypeScript 开发，支持 Debian 系统快速安装。

---
## 9. [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp)
- **语言**: C++
- **Stars**: 115,356
- **简介**: LLM inference in C/C++

### AI 总结
**简介**: llama.cpp 是一个高性能、轻量级的 C/C++ 大语言模型推理引擎，支持在本地和云端多种硬件上运行，无需复杂依赖。

**核心功能**:
- **模型推理**: 支持 LLaMA、Mistral 等多种文本和多模态模型的本地推理
- **量化支持**: 提供 1.5-bit 到 8-bit 的多种整数量化方案，降低显存占用并加速推理
- **多种部署方式**: 支持命令行、OpenAI 兼容 API 服务器、Docker 容器、浏览器 WebGPU 等多种运行方式
- **模型管理**: 可直接从 Hugging Face 下载和缓存模型，支持 GGUF 格式，便于跨工具共享

**技术亮点**:
- 纯 C/C++ 实现，无外部依赖，跨平台兼容性好
- 深度优化 Apple Silicon（ARM NEON、Accelerate、Metal），x86 架构（AVX/AVX2/AVX512/AMX），RISC-V 架构（RVV 等）
- 支持 NVIDIA GPU（CUDA）、AMD GPU（HIP）、Intel GPU（Vulkan/SYCL）等多种 GPU 后端
- CPU+GPU 混合推理，可处理超出显存容量的大模型

---
## 10. [RyanCodrai/turbovec](https://github.com/RyanCodrai/turbovec)
- **语言**: Python
- **Stars**: 7,246
- **简介**: A vector index built on TurboQuant, written in Rust with Python bindings

### AI 总结
**简介**: turbovec 是一个基于 Google TurboQuant 算法的高效向量索引库，用 Rust 编写并提供 Python 绑定，能以极低内存占用存储和快速搜索大规模向量数据。

**核心功能**:
- **在线增量索引**: 无需预训练或参数调优，添加向量后自动索引，支持动态扩展
- **高性能搜索**: 支持 SIMD 加速（ARM NEON 和 x86 AVX-512BW），搜索速度比 FAISS IndexPQFastScan 快 12–20%
- **搜索时过滤**: 支持通过 ID 白名单或位掩码进行过滤，在 SIMD 内核级别实现高效筛选，避免过度读取
- **纯本地运行**: 无需外部服务，数据不离开本地或 VPC，适合隐私敏感场景
- **持久化存储**: 支持索引的序列化与加载，索引文件格式为 `.tq` 或 `.tvim`
- **框架集成**: 提供 LangChain、LlamaIndex、Haystack、Agno 等框架的即插即用替换组件

**技术亮点**: 基于 Google Research 的 TurboQuant 算法（数据无关量化器，匹配香农失真下界），无需码本训练；使用 Rust 编写核心内核，通过 NEON 和 AVX-512BW 指令集实现 SIMD 加速；支持混合检索架构，可与 SQL、BM25 等外部系统结合使用。

---
