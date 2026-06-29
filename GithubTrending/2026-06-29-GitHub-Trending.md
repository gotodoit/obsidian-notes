---
tags:
  - github-trending
  - daily
date: 2026-06-29
created: 2026-06-29T01:55:44.307Z
---

# 2026-06-29 GitHub Trending Top 10

## 1. [simplex-chat/simplex-chat](https://github.com/simplex-chat/simplex-chat)
- **语言**: Haskell
- **Stars**: 15,107
- **简介**: SimpleX - the first messaging network operating without user identifiers of any kind - 100% private by design! iOS, Android and desktop apps 📱!

### AI 总结
**简介**: SimpleX 是首个完全去中心化、不依赖任何用户标识符的隐私优先消息网络，支持 iOS、Android 和桌面端。

**核心功能**:
- 无任何用户标识符（如手机号、邮箱、用户名）的端到端加密通信
- 双重棘轮加密协议，额外保护消息和元数据
- 跨平台移动应用（iOS/Android）及终端命令行界面（Linux/MacOS/Windows）
- 支持用户创建和加入群组，通过 SimpleX 目录发现公共群组

**技术亮点**: 基于 Haskell 开发，采用去中心化网络架构，无需全局用户身份标识，通过 SMP 协议实现匿名连接；已通过 Trail of Bits 安全审计，并获得 Privacy Guides、Whonix 等隐私社区推荐。

---
## 2. [ripienaar/free-for-dev](https://github.com/ripienaar/free-for-dev)
- **语言**: HTML
- **Stars**: 125,313
- **简介**: A list of SaaS, PaaS and IaaS offerings that have free tiers of interest to devops and infradev

### AI 总结
**简介**: 一个为开发者和 DevOps 人员整理的 SaaS、PaaS、IaaS 等服务的免费套餐列表。

**核心功能**:
- 汇总了各类云服务（如 GCP、AWS）的永久免费额度
- 按类别整理，涵盖分析、API、CI/CD、监控、托管等数十个领域
- 由社区通过 Pull Request 持续维护更新，已有 1600+ 贡献者

**技术亮点**: 项目以 HTML 静态列表形式呈现，通过 Awesome List 跟踪更新状态，并严格限定收录范围（仅限 as-a-Service 且提供长期免费套餐的服务）。

---
## 3. [commaai/openpilot](https://github.com/commaai/openpilot)
- **语言**: Python
- **Stars**: 62,418
- **简介**: openpilot is an operating system for robotics. Currently, it upgrades the driver assistance system on 300+ supported cars.

### AI 总结
**简介**: openpilot 是一个机器人操作系统，目前可升级超过 300 款车型的驾驶辅助系统。

**核心功能**:
- 支持 300+ 车型的驾驶辅助系统升级
- 提供多种软件分支（稳定版、预览版、夜间版、开发版）
- 支持 comma four 等硬件设备即插即用
- 提供安全模型和软件在环测试

**技术亮点**:
- 基于 Python 开发，遵循 ISO26262 安全标准
- 采用 C 语言编写安全模型代码（panda）
- 拥有持续集成测试和软件在环测试体系
- 开源社区驱动，支持自定义硬件和开发贡献

---
## 4. [xbtlin/ai-berkshire](https://github.com/xbtlin/ai-berkshire)
- **语言**: Python
- **Stars**: 5,406
- **简介**: AI 时代的伯克希尔：基于 Claude Code / Codex 的价值投资研究框架。巴菲特·芒格·段永平·李录四大师方法论 + 多Agent并行研究。| AI-era Berkshire: a value investing research framework built for Claude Code / Codex. 4 masters' methodologies + multi-agent adversarial analysis.

### AI 总结
**简介**: AI Berkshire 是一个基于 Claude Code / Codex 的价值投资研究框架，将巴菲特、芒格、段永平、李录四位大师的方法论系统化，通过多 Agent 并行实现专业级投资研究。

**核心功能**:
- **16 个 Skill 入口**：覆盖深度研究、财报分析、行业筛选、持仓管理、思维工具等场景
- **多 Agent 并行研究**：4 个独立 Agent 同时研究同一家公司，各自搜索验证并独立给出结论
- **四大师视角对抗**：自动从四位大师的方法论出发，产生真实的多视角分析张力
- **结构化反偏见机制**：内置信息评级、逆向检验、快速否决、反共识检查、留白原则
- **金融数据精确校验**：使用 `decimal.Decimal` 进行精确计算，关键数据交叉验证
- **可复现研究流程**：确保同一标准下不同公司、不同时间的分析结果可横向对比

**技术亮点**:
- Python 实现，使用 `decimal.Decimal` 确保金融计算精度
- 基于 Claude Code / Codex 的 Agent 框架，支持多 Agent 并行与独立搜索
- Mermaid 架构图（可编辑源码），支持三层设计：Skill 层、Agent 层、工具层
- 内置实盘验证：2024 年收益 +69.29%，2025 年至今 +66.38%，大幅跑赢全球主要指数

---
## 5. [Robbyant/lingbot-map](https://github.com/Robbyant/lingbot-map)
- **语言**: Python
- **Stars**: 8,249
- **简介**: A feed-forward 3D foundation model for reconstructing scenes from streaming data

### AI 总结
**简介**: LingBot-Map 是一个前馈式3D基础模型，专为从流式数据中重建场景而设计。

**核心功能**:
- **流式3D重建**: 能够以约20 FPS的速度处理超过10,000帧的长序列视频，实现稳定的流式重建。
- **交互式演示**: 提供 `demo.py` 脚本，支持关键帧间隔、窗口推理、天空遮罩等多种可视化选项。
- **离线渲染**: 提供 `batch_demo.py` 管道，支持对超长视频（如25,000帧）进行离线渲染。
- **多数据集评估**: 已发布针对KITTI、Oxford Spires等多个数据集的评估基准。

**技术亮点**:
- **几何上下文Transformer**: 通过锚点上下文、位姿参考窗口和轨迹记忆，在单一流式框架中统一了坐标定位、密集几何线索和长程漂移校正。
- **高效流式推理**: 采用前馈架构和分页KV缓存注意力机制，在518×378分辨率下实现稳定推理。
- **模型权重**: 已在HuggingFace和ModelScope平台发布预训练模型。

---
## 6. [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)
- **语言**: C
- **Stars**: 19,777
- **简介**: High-performance code intelligence MCP server. Indexes codebases into a persistent knowledge graph — average repo in milliseconds. 158 languages, sub-ms queries, 99% fewer tokens. Single static binary, zero dependencies.

### AI 总结
**简介**: codebase-memory-mcp 是一个高性能的代码智能 MCP 服务器，能将代码库索引为持久化的知识图谱，支持 158 种语言，毫秒级处理速度，单静态二进制文件，零依赖。

**核心功能**:
- **超快索引**：平均仓库毫秒级完成索引，Linux 内核（2800 万行代码，7.5 万个文件）仅需 3 分钟
- **即插即用**：单静态二进制文件，支持 macOS/Linux/Windows，无需 Docker、运行时依赖或 API 密钥
- **多语言支持**：内置 tree-sitter 语法分析，支持 158 种编程语言
- **智能查询**：5 个结构化查询仅需约 3,400 tokens，相比逐文件搜索节省 120 倍 tokens
- **多代理兼容**：自动检测并配置 11 种主流 AI 编码代理（Claude Code、Codex CLI 等）
- **内置可视化**：提供 3D 交互式知识图谱 UI，可通过 localhost:9749 访问
- **基础设施即代码索引**：支持 Dockerfile、Kubernetes 清单等资源节点和跨引用

**技术亮点**: 采用 tree-sitter AST 分析 + Hybrid LSP 语义类型解析（覆盖 Python、TypeScript 等 10 种语言），RAM-first 管道（LZ4 压缩、内存 SQLite、Aho-Corasick 模式匹配），100% 本地处理，代码永不离开本机。

---
## 7. [cupy/cupy](https://github.com/cupy/cupy)
- **语言**: Python
- **Stars**: 11,532
- **简介**: NumPy & SciPy for GPU

### AI 总结
**简介**: CuPy 是一个与 NumPy/SciPy 兼容的 GPU 加速数组计算库，可作为 NVIDIA CUDA 或 AMD ROCm 平台上的直接替代品。

**核心功能**:
- 提供与 NumPy/SciPy 一致的 API，支持在 GPU 上执行数组运算
- 支持通过 RawKernels 调用现有 CUDA C/C++ 程序
- 提供 Streams 和 CUDA Runtime API 等底层 CUDA 特性访问

**技术亮点**: 基于 Python 实现，支持 NVIDIA CUDA 和 AMD ROCm 双平台，可通过 pip、conda 和 Docker 多方式安装。

---
## 8. [altic-dev/FluidVoice](https://github.com/altic-dev/FluidVoice)
- **语言**: Swift
- **Stars**: 3,774
- **简介**: FluidVoice - Fastest macOS Offline Dictation app - Voice to Text fully Local. One ⭐ takes us a long way :))

### AI 总结
**简介**: FluidVoice 是一款 macOS 上最快的离线语音转文字应用，完全本地运行，支持多种语音模型和 AI 增强。

**核心功能**:
- **语音转文字**: 支持 Nemotron Speech 3.5、Parakeet Flash/ v3/v2、Cohere、Apple Speech、Whisper 等多种模型，实现离线实时听写
- **Fluid Intelligence**: 本地 AI 引擎提供智能格式化、上下文感知大写和后处理增强，无需联网或 API 密钥
- **命令模式**: 通过语音控制 Mac，如启动应用、运行快捷指令、触发系统操作
- **写入模式**: 在任何应用的文本框中语音输入或重写文本
- **主题切换**: 自适应亮/暗主题，带紧凑工具栏切换器

**技术亮点**:
- 使用 Swift 开发，完全开源 (GPLv3)
- 重建的 Parakeet 实现实现近乎零延迟的语音识别
- 核心听写功能免费，Fluid Intelligence 作为私有本地 AI 运行时提供高级增强
- 支持 Homebrew 一键安装 (`brew install --cask fluidvoice`)
- 提供历史记录与统计功能

---
## 9. [opendatalab/MinerU](https://github.com/opendatalab/MinerU)
- **语言**: Python
- **Stars**: 71,649
- **简介**: Transforms complex documents like PDFs and Office docs into LLM-ready markdown/JSON for your Agentic workflows.

### AI 总结
**简介**: MinerU 是一个开源工具，能将 PDF 和 Office 等复杂文档转换为适合大语言模型（LLM）处理的 Markdown 或 JSON 格式，助力 Agentic 工作流。

**核心功能**:
- 支持 PDF、Office 文档等多种格式的复杂文档解析与转换
- 输出为 Markdown 或 JSON 格式，便于 LLM 直接使用
- 提供 Web 应用和 API 接口，方便集成到工作流中

**技术亮点**: 基于 Python 开发，开源社区活跃（GitHub 高星数），支持通过 PyPI 安装，并集成 Hugging Face 在线演示。

---
## 10. [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading)
- **语言**: Python
- **Stars**: 14,364
- **简介**: "Vibe-Trading: Your Personal Trading Agent"

### AI 总结
**简介**: Vibe-Trading 是一个个人交易助手，通过一条命令即可赋予智能体全面的交易能力。

**核心功能**:
- 支持跨平台设置与开发环境，自动处理 Windows TypeScript 构建和后端启动
- 提供影子账户功能，支持基于 RSI 和先前收益条件的条件入场策略
- 集成内容过滤恢复机制，可跳过 LLM 内容审核命中并生成警告
- 支持 tushare 数据加载器，可路由 ETF/LOF、指数和港股数据
- 提供 MCP OAuth 缓存键清理和文件工具隔离读写根目录功能

**技术亮点**: 基于 Python 3.11+、FastAPI 后端和 React 19 前端构建，支持多语言文档，提供 API/MCP 接口，采用 MIT 开源许可证。

---
