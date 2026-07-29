---
tags:
  - github-trending
  - daily
date: 2026-07-29
created: 2026-07-29T01:55:43.362Z
---

# 2026-07-29 GitHub Trending Top 10

## 1. [pascalorg/editor](https://github.com/pascalorg/editor)
- **语言**: TypeScript
- **Stars**: 18,767
- **简介**: Create and share 3D architectural projects.

### AI 总结
**简介**: 一个基于 React Three Fiber 和 WebGPU 构建的 3D 建筑编辑器，用于创建和分享 3D 建筑项目。

**核心功能**:
- **场景编辑**: 支持节点层级管理（Site → Building → Level → Wall/Slab/Roof 等），提供 CRUD 操作和脏节点跟踪
- **3D 渲染**: 基于 React Three Fiber 的 WebGPU 渲染，包含默认相机/控制器和后处理效果
- **多包架构**: 分离为 core（场景状态/模式）、viewer（3D 渲染运行时）、editor（编辑工具和 UI）、nodes（内置节点定义）四个独立包
- **状态管理**: 使用 Zustand 管理场景数据、查看器状态和编辑器状态，支持 IndexedDB 持久化和撤销/重做

**技术亮点**:
- **技术栈**: TypeScript + React Three Fiber + WebGPU + Zustand + Turborepo
- **架构特点**: 采用扁平节点字典存储（非嵌套树），通过 parentId 建立关系；支持内置插件系统（@pascal-app/nodes）动态加载节点定义
- **数据流**: 每个包拥有独立 Zustand store，支持在 React 组件和外部回调中访问状态

---
## 2. [jenkinsci/jenkins](https://github.com/jenkinsci/jenkins)
- **语言**: Java
- **Stars**: 26,080
- **简介**: Jenkins automation server

### AI 总结
**简介**: Jenkins 是领先的开源自动化服务器，基于 Java 构建，提供超过 2000 个插件，用于自动化软件开发流程中的各类任务。

**核心功能**:
- 自动构建项目
- 运行测试以尽早发现缺陷
- 执行静态代码分析
- 自动化部署流程

**技术亮点**: 采用 Java 开发，支持插件化架构，提供 Weekly 和 LTS 两个发布线，支持 WAR 文件、Docker 镜像、原生包等多种分发方式。

---
## 3. [moeru-ai/airi](https://github.com/moeru-ai/airi)
- **语言**: TypeScript
- **Stars**: 44,796
- **简介**: 💖🧸 Self hosted, you-owned Grok Companion, a container of souls of waifu, cyber livings to bring them into our worlds, wishing to achieve Neuro-sama's altitude. Capable of realtime voice chat, Minecraft, Factorio playing. Web / macOS / Windows supported.

### AI 总结
**简介**: Project AIRI 是一个自托管的 AI 伴侣项目，旨在复现类似 Neuro-sama 的虚拟角色，支持实时语音聊天和游戏互动。

**核心功能**:
- 实时语音对话
- 支持 Minecraft 和 Factorio 游戏互动
- 跨平台支持 Web / macOS / Windows / Linux
- 自托管，用户完全掌控数据

**技术亮点**: 基于 TypeScript 开发，提供多语言支持（中文、日文、俄文等），采用容器化架构部署。

---
## 4. [andrewyng/aisuite](https://github.com/andrewyng/aisuite)
- **语言**: Python
- **Stars**: 15,696
- **简介**: Simple, unified interface to multiple Generative AI providers

### AI 总结
**简介**: aisuite 是一个轻量级 Python 库，为多个生成式 AI 提供商提供统一的聊天补全和智能体 API。

**核心功能**:
- **统一聊天补全 API**: 提供类似 OpenAI 的统一接口，支持 OpenAI、Anthropic、Google、Mistral、Ollama 等多家提供商，只需更改模型名字符串即可切换提供商
- **智能体 API**: 支持为模型提供 Python 函数作为工具、多轮对话循环、预置工具包（文件、Git、Shell）和 MCP 服务器集成
- **流式传输**: 支持从多个提供商获取流式响应，使用相同的循环处理不同提供商的流式数据

**技术亮点**: 采用分层架构设计（聊天补全 API → 智能体 API → OpenWorker 桌面应用），模型命名格式为 `<提供商>:<模型名称>`，支持自定义工具策略和权限管理。

---
## 5. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 234,847
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个面向 AI 编程助手（如 Claude Code、Codex、Cursor 等）的代理工具性能优化系统，提供技能、直觉、记忆、安全及研究优先的开发支持。

**核心功能**:
- 为 AI 编程代理提供性能优化与行为控制系统
- 内置代理技能、直觉和记忆管理模块
- 安全与防护功能（AgentShield）
- 支持 GitHub App 集成，可免费安装并用于公共仓库
- 多语言文档支持（中、英、日、韩等 12 种语言）

**技术亮点**: 基于 JavaScript/TypeScript 开发，同时兼容 Shell、Python、Go、Java、Perl 等多种语言环境；提供 npm 包（ecc-universal、ecc-agentshield）和 GitHub App 两种分发方式；采用 MIT 开源协议。

---
## 6. [hello245m/free-stockdb](https://github.com/hello245m/free-stockdb)
- **语言**: HTML
- **Stars**: 1,319
- **简介**: 面向 A 股日K、分钟K与ETF分钟数据的本地量化引擎，集成增量同步、本地缓存、复权、批量查询、回测与指标计算。

### AI 总结
**简介**: 面向A股与ETF的本地量化数据引擎，支持日K、分钟K及tick级数据的增量同步、清洗、复权、批量查询、回测与指标计算，实现数据工程与策略研究的解耦。

**核心功能**:
- **本地数据存储与管理**: 数据落盘至用户磁盘，支持Zstd压缩，增量同步与断点续传，离线可用。
- **多频率全市场数据**: 覆盖日/周/月/1/5/15/30分钟K线及tick级数据，内置股票、ETF及1200+概念板块映射。
- **批量查询与计算**: 提供`get_data()`批量查询任意代码、时间、频率与字段；`zb.get()`计算39种技术指标与5种指数；`bk.get()`实现股票与板块双向查询。
- **五种调用方式**: 支持Python SDK、HTTP API、Excel/WPS宏、HTML网页及AI MCP协议，满足多种集成场景。
- **数据源可控**: 支持自定义同步节点、本地目录或离线快照，数据源变更不影响已有数据与研究。

**技术亮点**: 采用C++时序引擎与Rust计算核心，指标计算比pandas快3倍；通过`sync_url.txt`配置数据源，实现数据更新与策略研究的完全解耦；内置完整复权因子，支持前/后/不复权查询。

---
## 7. [huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech)
- **语言**: Python
- **Stars**: 7,293
- **简介**: Build local voice agents with open-source models

### AI 总结
**简介**: 一个低延迟、全模块化的语音智能体流水线（VAD -> STT -> LLM -> TTS），提供与 OpenAI Realtime 兼容的 WebSocket API，支持完全本地或混合部署。

**核心功能**:
- **端到端语音对话**: 集成语音活动检测 (VAD)、语音转文字 (STT)、大语言模型 (LLM) 和文字转语音 (TTS) 四个组件，形成完整的语音智能体流水线。
- **OpenAI Realtime 兼容**: 暴露与 OpenAI Realtime API 兼容的 WebSocket 接口，任何兼容客户端均可直接连接。
- **组件可替换**: 流水线中的每一个组件（STT、LLM、TTS）都支持多种后端，可通过 CLI 参数轻松切换。
- **支持本地与云端模型**: LLM 可指向 OpenAI API、Hugging Face Inference Providers，或本地的 vLLM/llama.cpp 服务器，实现完全本地化部署。

**技术亮点**:
- 基于 Python，使用队列连接多线程流水线，实现低延迟。
- 默认使用 Parakeet TDT (STT) + OpenAI 兼容 LLM + Qwen3-TTS (TTS) 的组合。
- 支持 CUDA、Apple Silicon (mlx-audio) 及 CPU 等多种硬件加速后端。

---
## 8. [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill)
- **语言**: Python
- **Stars**: 11,472
- **简介**: Turn any technical book PDF into a Claude Code skill — ready to study, reference, and use while you work.

### AI 总结
**简介**: 将技术书籍、文档或源码集合转化为结构化、可被AI代理按需加载的技能文件，让你在工作时随时通过命令查询和引用。

**核心功能**:
- **一键转换**：支持 PDF、EPUB、DOCX、MD、HTML、RTF、MOBI 等格式，输入文件/文件夹/通配符即可生成技能。
- **按需加载**：生成 `SKILL.md`（核心模型+章节索引）、按章节拆分的文件、词汇表、模式集和速查表。章节文件仅在提问时加载，节省上下文令牌（相比直接输入全书可减少 24-51 倍令牌数）。
- **多代理兼容**：遵循开放的 Agent Skills 标准，生成的技能可直接用于 GitHub Copilot CLI、Amp 和 Claude Code。
- **超越书籍**：同样适用于内部文档、架构决策记录、运行手册等结构化知识。

**技术亮点**:
- **Python 实现**，通过智能蒸馏提取框架、决策规则、反模式等结构化信息，而非简单摘要。
- **按需加载架构**：章节文件独立存储，不占用技能预算，仅在用户查询相关主题时被代理读取，避免幻觉。
- **广泛的格式支持**：覆盖主流电子书和文档格式，输入灵活。

---
## 9. [opengeos/GeoLibre](https://github.com/opengeos/GeoLibre)
- **语言**: TypeScript
- **Stars**: 3,426
- **简介**: A lightweight, cloud-native GIS platform for visualizing, exploring, and analyzing geospatial data. It runs in the web browser, on the desktop, on mobile, and inside Jupyter notebooks.

### AI 总结
**简介**: 一个轻量级、云原生的开源 GIS 平台，用于可视化、探索和分析地理空间数据，支持网页、桌面、移动端和 Jupyter 环境运行。

**核心功能**:
- 多平台支持：浏览器、桌面（Windows/macOS/Linux）、Android 和 Jupyter Notebook
- 3D 瓦片渲染与交互式地图可视化
- 行星级底图支持（月球、火星等天体）
- 时间滑块动画分析
- 自动生成图层图例
- 本地化数据隐私保护

**技术亮点**: 基于 Tauri v2、React、TypeScript、MapLibre GL JS、DuckDB-WASM Spatial 和 deck.gl 构建，同一代码库可编译为原生桌面应用、Android 应用及 Web 应用。

---
## 10. [paperswithbacktest/awesome-systematic-trading](https://github.com/paperswithbacktest/awesome-systematic-trading)
- **语言**: Python
- **Stars**: 9,654
- **简介**: A curated list of awesome libraries, packages, strategies, books, blogs, tutorials for systematic trading.

### AI 总结
**简介**: 一个精选的系统化交易（量化交易）资源列表，包含库、策略、书籍、视频、博客和课程。

**核心功能**:
- 收录了97个用于研究和实盘交易的库与包（如回测框架、交易机器人、分析工具等）
- 整理了40多种由机构与学术界描述的交易策略（涵盖股票、债券、加密货币等）
- 提供了55本适合初学者和专业人士的书籍，以及23个视频和访谈
- 包含博客、课程等学习资源

**技术亮点**: 以Python为主要语言，资源按人气（GitHub星数）排序，并分类为回测、数据分析、机器学习、时间序列分析等模块。

---
