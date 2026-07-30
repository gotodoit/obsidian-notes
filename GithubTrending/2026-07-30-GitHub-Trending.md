---
tags:
  - github-trending
  - daily
date: 2026-07-30
created: 2026-07-30T01:55:43.418Z
---

# 2026-07-30 GitHub Trending Top 10

## 1. [opengeos/GeoLibre](https://github.com/opengeos/GeoLibre)
- **语言**: TypeScript
- **Stars**: 4,078
- **简介**: A lightweight, cloud-native GIS platform for visualizing, exploring, and analyzing geospatial data. It runs in the web browser, on the desktop, on mobile, and inside Jupyter notebooks.

### AI 总结
**简介**: GeoLibre 是一个轻量级、云原生的开源 GIS 平台，用于可视化、探索和分析地理空间数据，支持在 Web 浏览器、桌面、移动端及 Jupyter Notebook 中运行，并保障数据本地化和隐私。

**核心功能**:
- 支持 3D Tiles 渲染与交互式地图可视化
- 内置时间滑块，可动态展示地理数据的时间序列变化（如建筑年代演变）
- 提供行星级底图（月球、火星等），并自动适配对应天体的椭球体测量
- 自动生成图层符号图例，支持多图层叠加（如建筑、地铁线路）
- 跨平台部署：Web 端、原生桌面应用（Windows/macOS/Linux）、Android 移动端

**技术亮点**:
- 基于 **Tauri v2** + **React** + **TypeScript** 构建，实现跨平台原生性能
- 核心渲染引擎：**MapLibre GL JS**（地图）、**deck.gl**（数据可视化）、**DuckDB-WASM Spatial**（本地空间数据处理）
- 同一代码库适配多种运行环境，响应式设计支持移动端小屏
- 内置插件系统，支持扩展功能（如大气效果插件）

---
## 2. [moeru-ai/airi](https://github.com/moeru-ai/airi)
- **语言**: TypeScript
- **Stars**: 45,405
- **简介**: 💖🧸 Self hosted, you-owned Grok Companion, a container of souls of waifu, cyber livings to bring them into our worlds, wishing to achieve Neuro-sama's altitude. Capable of realtime voice chat, Minecraft, Factorio playing. Web / macOS / Windows supported.

### AI 总结
**简介**: 一个自托管的 AI 伴侣项目，旨在复现类似 Neuro-sama 的虚拟角色，支持实时语音聊天和游戏互动。

**核心功能**:
- 实时语音对话
- 支持 Minecraft、Factorio 等游戏互动
- 提供 Web、macOS、Windows 桌面应用
- 支持多语言界面（中文、日文、俄文等）

**技术亮点**: 基于 TypeScript 开发，自托管架构，支持跨平台部署

---
## 3. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 235,611
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个为 Claude Code、Codex、Cursor 等 AI 编码代理提供性能优化的“代理框架操作系统”，专注于技能、本能、记忆、安全与研究优先的开发。

**核心功能**:
- 提供代理性能调优系统，增强 AI 编码代理的效率和能力
- 支持技能、本能、记忆和安全模块的集成与管理
- 提供 GitHub App 和 npm 包 (`ecc-universal`, `ecc-agentshield`) 两种安装方式
- 支持公共和私有仓库（Pro 版），社区版免费开源

**技术亮点**: 基于 JavaScript 开发，同时支持 Shell、TypeScript、Python、Go、Java、Perl 等多种语言环境；提供 Discord 社区和官方网站支持，MIT 许可证开源。

---
## 4. [huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech)
- **语言**: Python
- **Stars**: 7,888
- **简介**: Build local voice agents with open-source models

### AI 总结
**简介**: 一个低延迟、模块化的语音代理流水线，用于构建本地语音助手，兼容 OpenAI Realtime API。

**核心功能**:
- 完整的语音代理流水线：语音活动检测 (VAD) → 语音转文字 (STT) → 大语言模型 (LLM) → 文字转语音 (TTS)
- 提供 OpenAI Realtime 兼容的 WebSocket API，支持任意兼容客户端连接
- 所有组件均可替换，支持本地或远程模型后端（如 Hugging Face、vLLM、llama.cpp）
- 支持实时语音交互、流式文本和工具调用

**技术亮点**:
- 基于 Silero VAD v5 进行语音边界检测和对话轮次管理
- 默认使用 Parakeet TDT 进行本地 STT，Qwen3-TTS 进行本地语音合成
- 采用多线程架构，每个组件运行在独立线程并通过队列连接
- 支持 CUDA 加速，并提供平台特定的依赖管理（macOS 使用 mlx-audio，其他平台使用 GGML 后端）

---
## 5. [1jehuang/jcode](https://github.com/1jehuang/jcode)
- **语言**: Rust
- **Stars**: 13,487
- **简介**: The most RAM efficient harness

### AI 总结
**简介**: jcode 是一个用 Rust 编写的高性能、内存效率极高的 AI 编程助手（harness），旨在成为最省内存的智能编码工具。

**核心功能**:
- 提供极其高效的内存管理，在单会话和多会话场景下均大幅优于同类工具（如 Claude Code、Cursor Agent 等）
- 支持多平台（Linux、macOS、Windows），提供一键安装脚本
- 提供完整的文档、基准测试和社区支持（Discord）

**技术亮点**: 使用 Rust 语言开发，通过禁用本地嵌入（local embedding off）可将单会话内存占用降至 27.8 MB，相比同类工具节省 5-14 倍内存；多会话场景下内存扩展性极佳（10 会话仅 117 MB）。

---
## 6. [grokability/snipe-it](https://github.com/grokability/snipe-it)
- **语言**: PHP
- **Stars**: 14,461
- **简介**: A free open source IT asset/license management system

### AI 总结
**简介**: Snipe-IT 是一个免费开源的 IT 资产/许可证管理系统，基于 Laravel 12 构建，用于跟踪硬件、软件许可证等资产。

**核心功能**:
- 资产跟踪：记录谁拥有哪台笔记本电脑、何时购买等信息，以便正确折旧
- 软件许可证管理：处理软件许可证的分配和合规性
- 支持多种部署环境：可在 Mac OSX、Linux 和 Windows 上运行，并提供 Docker 镜像
- 提供 JSON REST API，支持第三方模块和库集成
- 多语言翻译支持

**技术亮点**: 基于 Laravel 12 框架开发，支持 Docker 部署，提供 JSON REST API，通过 Crowdin 实现社区翻译，拥有活跃的社区和频繁的版本更新。

---
## 7. [deepfakes/faceswap](https://github.com/deepfakes/faceswap)
- **语言**: Python
- **Stars**: 56,312
- **简介**: Deepfakes Software For All

### AI 总结
**简介**: FaceSwap 是一款基于深度学习的开源工具，用于在图片和视频中识别并替换人脸。

**核心功能**:
- 提取人脸特征（Extract）
- 训练人脸替换模型（Train）
- 将训练好的模型应用到目标媒体上（Convert）
- 提供图形用户界面（GUI）方便操作

**技术亮点**: 使用 Python 开发，基于深度学习技术（如神经网络），支持多种模型如 Phaze-A 和 Villain，拥有完整的文档和社区支持。

---
## 8. [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice)
- **语言**: Python
- **Stars**: 51,314
- **简介**: Open-Source Frontier Voice AI

### AI 总结
**简介**: VibeVoice 是微软开源的前沿语音 AI 模型系列，涵盖文本转语音 (TTS) 和自动语音识别 (ASR) 两大核心能力。

**核心功能**:
- **VibeVoice-ASR**: 支持超过50种语言的统一语音转文本模型，可一次性处理长达60分钟的音频，并生成包含说话人、时间戳和内容的结构化转录文本。
- **VibeVoice-TTS**: 长文本多说话人语音合成模型，支持合成长达90分钟、最多4个不同说话人的语音，已被 ICLR 2026 接收为 Oral 论文。
- **VibeVoice-Realtime-0.5B**: 实时文本转语音模型，支持流式文本输入和稳健的长文本语音生成，并提供了多语言和多种英语风格的声音。
- **边缘推理**: 通过 VibeVoice-ASR-BitNet 引擎，在 CPU 上实现实时推理，无需 GPU。

**技术亮点**:
- 采用连续语音分词器（声学和语义），实现超低帧率处理。
- 通过异构量化（I8_S + I2_S）将 ASR 模型从 4.62 GB 压缩至 1.58 GB。
- 原生支持多语言，集成 vLLM 推理引擎以加速，并提供 Hugging Face Transformers 集成。

---
## 9. [different-ai/openwork](https://github.com/different-ai/openwork)
- **语言**: TypeScript
- **Stars**: 17,962
- **简介**: The open-source alternative to Claude Cowork (powered by opencode)

### AI 总结
**简介**: OpenWork 是一个免费、开源的桌面应用，旨在共享 AI 工作流，是 Claude Cowork 和 Codex 的开源替代品，支持 macOS、Windows 和 Linux。

**核心功能**:
- 通过 OpenWork MCP 与 Codex、Claude Code、Cursor 等 AI 代理集成，复用技能、MCP 和连接服务。
- 提供桌面应用作为专用工作区，并支持从已有代理直接使用。
- 包含管理界面（OpenWork Den），用于发布能力、管理访问权限、配置共享或个人连接。
- 支持跨团队和组织的推理供应、成员管理、策略设置和技能发布。

**技术亮点**: 基于 TypeScript 开发，使用 MCP（模型上下文协议）实现远程集成，支持 OAuth 认证，提供 `search_capabilities` 和 `execute_capability` 工具接口，本地开发采用 pnpm 和 Electron。

---
## 10. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 263,322
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: 一套为编码代理设计的完整软件开发方法论，基于一组可组合的技能和初始指令，让代理自动遵循规范流程工作。

**核心功能**:
- 自动引导代理在编码前先确认用户真实需求，并生成可读的规格说明
- 将设计拆分为短块供用户审阅，确认后生成清晰的实现计划（强调TDD、YAGNI、DRY原则）
- 通过子代理驱动开发流程，自动分配任务、审查工作成果，可自主运行数小时

**技术亮点**: Shell脚本构建的可组合技能框架，支持Claude Code、Cursor、GitHub Copilot CLI等十余种主流编码代理工具的插件化安装。

---
