---
tags:
  - github-trending
  - daily
date: 2026-06-10
created: 2026-06-10T01:55:44.050Z
---

# 2026-06-10 GitHub Trending Top 10

## 1. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 37,449
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个AI智能体搜索引擎，跨平台聚合Reddit、X、YouTube等社交媒体的内容，按用户真实互动（点赞、投票、金钱）评分，生成综合摘要。

**核心功能**:
- 并行搜索Reddit、X、YouTube、TikTok、Hacker News、Polymarket、GitHub等平台
- 基于点赞、投票、金钱等真实用户信号对结果评分
- AI智能体自动综合多平台信息生成简洁摘要
- 零配置即用，支持通过安装向导解锁更多平台

**技术亮点**: 使用Python开发，通过API密钥和浏览器会话桥接各平台围墙花园，实现跨平台统一搜索与评分

---
## 2. [RyanCodrai/turbovec](https://github.com/RyanCodrai/turbovec)
- **语言**: Python
- **Stars**: 10,228
- **简介**: A vector index built on TurboQuant, written in Rust with Python bindings

### AI 总结
**简介**: turbovec 是一个基于 Google TurboQuant 算法的高效向量索引库，使用 Rust 编写并提供 Python 绑定，能以极低内存占用实现比 FAISS 更快的搜索。

**核心功能**:
- **在线增量索引**：无需训练阶段，直接添加向量即可索引，支持动态增长
- **过滤搜索**：支持通过 ID 白名单或位掩码在搜索时进行过滤，SIMD 内核直接处理过滤逻辑
- **混合检索**：可与外部系统（SQL、BM25 等）结合，先筛选候选集再精排
- **框架集成**：提供 LangChain、LlamaIndex、Haystack、Agno 等框架的即插即用替代
- **持久化**：支持索引的写入与加载，包括带稳定 ID 的 IdMapIndex

**技术亮点**:
- 基于 Google TurboQuant 算法（数据无关量化器，无需码本训练）
- 手写 NEON (ARM) 和 AVX-512BW (x86) SIMD 内核，比 FAISS IndexPQFastScan 快 12-20%
- 10M 文档的 float32 向量从 31GB 压缩至 4GB 内存
- 纯本地运行，支持完全离线部署的 RAG 系统

---
## 3. [roboflow/supervision](https://github.com/roboflow/supervision)
- **语言**: Python
- **Stars**: 43,031
- **简介**: We write your reusable computer vision tools. 💜

### AI 总结
**简介**: Supervision 是一个开源的 Python 库，提供可复用的计算机视觉工具，用于加载数据集、绘制检测结果和统计检测数量等。

**核心功能**:
- **模型无关的检测**: 支持与 Ultralytics、Transformers、MMDetection 等主流库集成，可处理分类、检测和分割任务。
- **高度可定制的标注器**: 提供丰富的可视化工具（如 BoxAnnotator），用于在图像或视频上绘制检测结果。
- **数据集管理工具**: 支持加载、分割、合并和保存数据集（如 COCO、YOLO 格式），并提供便捷的 API。

**技术亮点**: 基于 Python 3.9+，设计为模型无关架构，通过连接器（connectors）无缝对接多种深度学习库，同时集成 Roboflow 生态（如 Inference、Autodistill）。

---
## 4. [opencv/opencv](https://github.com/opencv/opencv)
- **语言**: C++
- **Stars**: 88,663
- **简介**: Open Source Computer Vision Library

### AI 总结
**简介**: OpenCV 是一个开源的计算机视觉库，提供丰富的图像和视频处理功能。
**核心功能**:
- 图像处理（滤波、变换、特征检测等）
- 视频分析与目标跟踪
- 机器学习与深度学习支持
**技术亮点**: 基于 C++ 实现，提供 Python、Java 等多语言接口，支持跨平台部署，拥有活跃的社区和丰富的扩展模块（opencv_contrib）。

---
## 5. [refactoringhq/tolaria](https://github.com/refactoringhq/tolaria)
- **语言**: TypeScript
- **Stars**: 14,366
- **简介**: Desktop app to manage markdown knowledge bases

### AI 总结
**简介**: Tolaria 是一个免费开源的桌面应用，用于管理基于 Markdown 的知识库，支持离线使用且无供应商锁定。

**核心功能**:
- **文件优先**：笔记以纯 Markdown 文件形式存储，可跨编辑器使用，数据完全归用户所有。
- **Git 优先**：每个知识库都是一个 Git 仓库，支持完整版本历史和远程同步，无需依赖 Tolaria 服务器。
- **离线优先**：无需账户或订阅，完全离线工作，停止使用应用也不会丢失数据。
- **AI 集成**：支持与 Claude Code、Codex CLI 等 AI 工具配合使用，提供 AGENTS 文件供 AI 参考。
- **键盘优先**：针对高级用户设计，支持通过键盘快速操作编辑器与命令面板。
- **类型作为导航工具**：通过类型（Types）辅助笔记分类和查找，而非强制执行数据模式。

**技术亮点**: 使用 TypeScript 开发，基于 Tauri、React 和 Rust 构建，支持 macOS、Windows 和 Linux。代码开源，社区可通过 Homebrew 或 GitHub Releases 安装。

---
## 6. [aaif-goose/goose](https://github.com/aaif-goose/goose)
- **语言**: Rust
- **Stars**: 48,513
- **简介**: an open source, extensible AI agent that goes beyond code suggestions - install, execute, edit, and test with any LLM

### AI 总结
**简介**: goose 是一个开源、可扩展的通用 AI 代理，支持桌面应用、CLI 和 API，可在本地运行，用于代码、工作流及更多任务。

**核心功能**:
- 提供 macOS、Linux 和 Windows 原生桌面应用，以及 CLI 终端工作流和可嵌入的 API
- 支持 15+ 大语言模型提供商（Anthropic、OpenAI、Google、Ollama 等），可通过 API 密钥或现有订阅使用
- 通过 Model Context Protocol (MCP) 开放标准连接 70+ 扩展

**技术亮点**: 使用 Rust 语言构建，注重性能和可移植性；隶属于 Linux 基金会下的 Agentic AI Foundation (AAIF)；支持自定义发行版构建（预配置提供商、扩展和品牌）。

---
## 7. [Andyyyy64/whichllm](https://github.com/Andyyyy64/whichllm)
- **语言**: Python
- **Stars**: 4,118
- **简介**: Find the local LLM that actually runs and performs best on your hardware. Ranked by real, recency-aware benchmarks, not parameter count. One command, run it instantly.

### AI 总结
**简介**: 自动检测硬件配置，从HuggingFace实时排名推荐最适合本地运行的LLM模型，一键运行。

**核心功能**:
- **硬件自动检测** — 识别NVIDIA/AMD/Apple Silicon/CPU，计算VRAM/显存/内存容量
- **智能模型排名** — 基于真实基准测试（LiveBench、Chatbot Arena等）评分，结合硬件适配度与推理速度
- **一键对话启动** — `whichllm run` 直接下载模型并启动聊天会话
- **硬件模拟与升级对比** — `--gpu` 参数模拟未购硬件，`upgrade` 命令比较升级候选
- **代码片段生成** — `whichllm snippet` 输出可直接运行的Python调用代码
- **JSON输出** — `--json` 支持脚本化处理

**技术亮点**:
- **Recency-aware评分** — 时间衰减算法防止旧模型占用高排名，实时标注基准数据快照日期
- **证据分级系统** — 为每个评分标记置信度等级（direct/variant/base/interpolated/self-reported），自动拒绝虚假上传者声明
- **架构感知估算** — 考虑GQA KV缓存、MoE激活参数、统一内存/PCIe部分卸载等硬件特性
- **实时数据+离线回退** — 从HuggingFace API实时获取模型，内置冻结缓存应对限流

---
## 8. [TapXWorld/ChinaTextbook](https://github.com/TapXWorld/ChinaTextbook)
- **语言**: Roff
- **Stars**: 73,518
- **简介**: 所有小初高、大学PDF教材。

### AI 总结
**简介**: 一个开源的中国中小学及大学PDF教材合集，旨在免费提供教育资源，促进教育公平，并帮助海外华人了解国内教育。

**核心功能**:
- 提供小学至高中各年级的PDF教材下载
- 覆盖数学、语文、英语等主要学科
- 包含人教版等主流教材版本

**技术亮点**: 使用GitHub作为资源存储和分发平台，所有教材以PDF格式直接提供，无需额外工具即可访问。

---
## 9. [x1xhlol/system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools)
- **语言**: Unknown
- **Stars**: 139,187
- **简介**: FULL Augment Code, Claude Code, Cluely, CodeBuddy, Comet, Cursor, Devin AI, Junie, Kiro, Leap.new, Lovable, Manus, NotionAI, Orchids.app, Perplexity, Poke, Qoder, Replit, Same.dev, Trae, Traycer AI, VSCode Agent, Warp.dev, Windsurf, Xcode, Z.ai Code, Dia & v0. (And other Open Sourced) System Prompts, Internal Tools & AI Models

### AI 总结
**简介**: 这是一个收集了众多AI工具（如Cursor、Claude Code、Devin AI等）系统提示词、内部工具和AI模型的综合性开源仓库。

**核心功能**:
- 汇总并公开了超过20种主流AI工具的系统提示词（System Prompts）
- 提供AI工具的内部工具和模型信息
- 为AI开发者和安全研究人员提供参考资源

**技术亮点**: 持续追踪AI工具的最新提示词和模型更新，并针对AI初创公司提供提示词注入和系统提示提取的安全风险警告与防护服务（ZeroLeaks）。

---
## 10. [yikart/AiToEarn](https://github.com/yikart/AiToEarn)
- **语言**: TypeScript
- **Stars**: 19,968
- **简介**: Let's use AI to Earn!

### AI 总结
**简介**: AiToEarn 是一个面向 OPC（一人公司）和创作者的 AI 内容营销智能体平台，通过 AI Agent 自动化帮助用户在全球主流平台构建、分发并变现内容。

**核心功能**:
- **💰 Monetize（内容赚钱）**: 创作者可在平台出售内容以完成商家推广任务，支持 CPS、CPE、CPM 三种结算模式。
- **📢 Publish（内容发布 Agent）**: 一键将内容分发至抖音、小红书、TikTok、YouTube 等 10+ 主流平台，并支持日历排期管理。
- **💬 Engage（内容互动 Agent）**: 通过浏览器插件实现自动点赞、收藏、关注，AI 智能回复评论，挖掘高转化信号，并监测品牌讨论。
- **🎨 Create（内容创作 Agent）**: 自动调用视频/图片生成模型（如 Grok、Veo、Seedance、Nano Banana），支持视频翻译、剪辑，以及批量内容生成。

**技术亮点**: 基于 TypeScript 开发，支持 Docker 一键部署、MCP 协议集成（可在 Claude、Cursor 等 AI 工具中使用）、以及 OpenClaw（龙虾）平台集成。

---
