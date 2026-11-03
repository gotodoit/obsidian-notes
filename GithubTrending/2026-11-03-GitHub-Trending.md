---
tags:
  - github-trending
  - daily
date: 2026-11-03
created: 2026-11-03T01:55:43.134Z
---

# 2026-11-03 GitHub Trending Top 10

## 1. [vercel-labs/agent-desktop](https://github.com/vercel-labs/agent-desktop)
- **语言**: Rust
- **Stars**: 9,881
- **简介**: Computer use CLI for AI agents

### AI 总结
**简介**: Vercel Labs 推出的 AI Agent 桌面操作工具，通过操作系统无障碍树让 AI 读取和操控桌面应用。

**核心功能**:
- **快照与引用操作**：`snapshot` 返回带 ref 的 JSON 元素树，Agent 通过 ref 执行点击等动作，再快照验证，无需像素匹配
- **跨平台 CLI 与 C 库**：支持 macOS、Windows、Linux，提供 npm 全局安装及原生二进制包
- **无头默认模式**：动作经无障碍 API 完成，不移动指针、不抢占焦点，`--headed` 才启用物理输入
- **面向 Agent 的自带文档**：内置 `skills get` 命令输出操作循环、平台差异等版本匹配文档，可集成到 Agent 框架

**技术亮点**: 基于 Rust 实现原生 CLI 与 C 库；采用“观察—操作—再观察”的引用式交互循环，避免像素匹配；通过快照 ID 绑定 ref 并在 UI 变化时返回 `STALE_REF`/`AMBIGUOUS_TARGET` 保障操作可靠性；依赖 macOS 辅助功能权限、Windows 完整性级别、Linux 的 at-spi2-core。

---
## 2. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 110,782
- **简介**: Persistent Context Across Sessions for Every Agent – Captures everything your agent does during sessions, compresses it with AI, and injects relevant context back into future sessions. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode + More

### AI 总结
**简介**: Claude-Mem 是一个为 Claude Code 等 AI 编程代理打造的持久化记忆压缩系统，通过记录、压缩并回注会话上下文，让代理在跨会话时保持记忆连续性。

**核心功能**:
- 捕获代理在会话中的所有操作记录
- 利用 AI 对会话内容进行压缩摘要
- 将相关上下文自动注入后续会话，实现跨会话持久记忆
- 兼容 Claude Code、OpenClaw、Codex、Gemini、Hermes、Copilot、OpenCode 等多种代理

**技术亮点**: 基于 TypeScript 开发，要求 Node.js ≥ 20.0.0，采用 Apache 2.0 许可；提供多语言文档（30+ 种语言），并入选 Awesome Claude Code 及 Vercel OSS Program。

---
## 3. [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling)
- **语言**: Python
- **Stars**: 92,958
- **简介**: 🕷️ The BEST Web Scraping framework that handles everything from a single request to a full-scale crawl! Don't be shy, join here: https://discord.gg/EMgGbDceNQ and follow here for daily tips and tricks: https://x.com/Scrapling_dev

### AI 总结
**简介**: Scrapling 是一个 Python Web 爬虫框架，覆盖从单次请求到大规模爬取的完整场景。

**核心功能**:
- 提供多种选择器（Selection methods），用于灵活解析和提取页面数据
- 内置多种 Fetcher，适配不同抓取需求（含反爬、代理等场景）
- 支持 Spiders 爬虫架构，可扩展至全站级大规模爬取
- 提供代理与反封锁（Proxy & Blocking）处理能力

**技术亮点**: 基于 Python 实现；提供完善的文档（Read the Docs）、Docker 镜像、PyPI 包分发及 AI Agent 技能集成；支持多语言 README；具备测试流水线与活跃社区（Discord、X）。

---
## 4. [hyprwm/Hyprland](https://github.com/hyprwm/Hyprland)
- **语言**: C++
- **Stars**: 39,956
- **简介**: Hyprland is an independent, highly customizable, dynamic tiling Wayland compositor that doesn't sacrifice on its looks.

### AI 总结
**简介**: Hyprland 是一个 100% 独立开发、高度可定制的动态平铺 Wayland 合成器，在追求视觉表现力的同时不牺牲外观。

**核心功能**:
- 丰富的视觉效果：渐变边框、多种模糊、动画、发光、阴影等
- 高度可定制，支持自定义贝塞尔曲线与弹簧曲线动画
- 强大的插件支持，内置插件管理器
- 支持 Tearing，提升游戏性能
- 配置保存后即时重载，全局快捷键可传递给应用
- 窗口模式：平铺 / 伪平铺 / 浮动 / 全屏
- 特殊工作区（scratchpad）、窗口组（标签模式）
- 强大的窗口 / 显示器 / 图层规则
- 基于 Socket 的 IPC，原生 IME 与输入面板支持
- 完全动态工作区，支持多种布局（Dwindle、Scrolling、Master、Monocle、Lua 自定义布局、插件自定义布局）及每工作区独立布局

**技术亮点**: 使用 C++ 编写；完全独立实现，不依赖 wlroots、libweston、kwin 或 mutter；代码库易扩展、可读性强；开发活跃且敢于采用前沿特性。

---
## 5. [Donchitos/Claude-Code-Game-Studios](https://github.com/Donchitos/Claude-Code-Game-Studios)
- **语言**: Shell
- **Stars**: 33,606
- **简介**: Turn Claude Code into a full game dev studio — 49 AI agents, 72 workflow skills, and a complete coordination system mirroring real studio hierarchy.

### AI 总结
**简介**: Claude Code Game Studios 是一个将单次 Claude Code 会话转化为完整游戏开发工作室的配置框架，通过 49 个 AI 代理和 74 个工作流技能模拟真实工作室的层级协作体系。

**核心功能**:
- **49 个专业化 AI 代理**：按三层工作室层级组织（总监层、部门主管层、专员层），覆盖设计、编程、美术、音频、叙事、QA、制作等领域，每个代理有明确职责、升级路径和质量关卡
- **74 个工作流技能**：提供覆盖各开发阶段的斜杠命令（如 `/start`、`/design-system`、`/create-epics`、`/dev-story`、`/story-done` 等）
- **15 个自动化钩子**：在提交、推送、资源变更、设计文档读写、会话生命周期等环节执行自动校验与审计追踪
- **14 条路径作用域规则**：针对玩法、引擎、AI、UI、网络代码及场景资源文件等强制编码标准
- **62 个文档模板**：涵盖 GDD、UX 规格、ADR、冲刺计划、HUD 设计、无障碍设计等
- **多引擎支持**：内置三大主流游戏引擎的代理集，按项目选择对应组合

**技术亮点**: 基于 Claude Code 的子代理机制构建，采用分层代理架构（总监/主管/专员三级）模拟真实工作室管理流程；代理通过 frontmatter 声明模型（总监层用 Opus，部分主管与专员用 Sonnet，其余继承会话模型）；结合 Hooks 与 Rules 实现提交前校验和路径级编码约束，形成从头脑风暴到上线的结构化质量门控体系。

---
## 6. [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken)
- **语言**: Python
- **Stars**: 16,094
- **简介**: FreeToken brings datacenter-scale model serving to your desktop. Run massive models locally, fast and efficiently.

### AI 总结
**简介**: FreeToken 是一个边缘原生的 MoE（混合专家）推理引擎，让用户在个人电脑等消费级硬件上本地运行 290B+ 参数的前沿开源大模型，并提供交互级速度。

**核心功能**:
- **快速边缘运行时**：带宽自适应 CPU–GPU 协同执行、全层双缓冲预填充流式传输、全局 LRU 专家缓存、图兼容执行及 FTW 快速权重格式。
- **语义感知缓存**：通过语义锚点检查点保存循环状态与 KV 缓存，避免 Agent 上下文编辑（工具调用、思考块等）时的冗余重算。
- **弹性显存管理**：运行时动态在专家缓存与 KV 内存间重新分配 VRAM，无需重启引擎或重载权重。
- **广泛模型与生态支持**：支持 DeepSeek-V4-Flash、Qwen3.6-35B-A3B、GLM-5.2 等前沿 MoE 模型及 MXFP4/NVFP4/FP8/BF16 量化格式，提供 Anthropic/OpenAI 兼容 API，可接入 Codex、Claude Code 等编程与工具调用 Agent。
- **多类消费硬件**：覆盖笔记本、游戏台式机与工作站 GPU，原生支持 NVIDIA RTX 30/40/50 系列。

**技术亮点**: 将 GPU、CPU、主机内存与互连视为统一的弹性推理平台；采用 $q^\star$ 带宽自适应策略实现异构资源协同；提供桌面 GUI 应用与 CLI（支持 uv/pip 安装）；设计上借鉴了 SGLang、vLLM、FlashInfer、llama.cpp 等项目；采用 Apache 2.0 协议。

---
## 7. [pingdotgg/t3code](https://github.com/pingdotgg/t3code)
- **语言**: TypeScript
- **Stars**: 42,052
- **简介**: 

### AI 总结
**简介**: T3 Code 是一个“智能体控制台”，让你通过 iOS/Android 移动端、Web 端和 Electron 桌面端统一控制本机已安装的各类 AI 编程智能体。

**核心功能**:
- 跨平台远程控制：通过移动 App、Web 应用和桌面客户端管理本机智能体，支持远程访问
- 多智能体兼容：支持 Claude Code、Codex、Cursor、Grok Build、OpenCode、Google Antigravity 和 fx，复用已有订阅
- 多种安装方式：提供命令行一键安装（`t3` 服务）、桌面应用（winget/scoop/Homebrew/deb/AUR/Nix），以及免安装的 `npx t3@latest`
- 后台服务与更新：`t3 service install` 常驻后台运行，`t3 update` 升级版本
- 完善的用户文档：覆盖权限模式、快捷键、项目设置、MCP 外部智能体连接、多账号、源码控制集成等

**技术亮点**: 基于 TypeScript 开发；采用服务端 + 多端客户端的架构（本地服务配合 Web/桌面/移动端）；构建工具链使用 Vite+（`vp`）；强调性能、远程就绪与真正开放（可自由 fork 定制）；项目处于早期阶段，暂不广泛接受外部贡献。

---
## 8. [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos)
- **语言**: Python
- **Stars**: 46,024
- **简介**: Kronos: A Foundation Model for the Language of Financial Markets

### AI 总结
**简介**: Kronos 是首个面向金融市场 K 线（蜡烛图）序列的开源基础模型，在超过 45 个全球交易所的数据上训练，论文已被 AAAI 2026 接收。

**核心功能**:
- 基于 `KronosPredictor` 类对金融 K 线进行预测，内置数据预处理与归一化流程
- 提供多种规模的预训练模型（Kronos-mini/small/base/large），适配不同算力与应用需求，模型托管于 Hugging Face
- 提供在线 Demo，可视化展示 BTC/USDT 未来 24 小时的预测结果
- 支持微调脚本，可将模型适配到自定义量化任务

**技术亮点**: 采用两阶段架构——专用 Tokenizer 先将多维 OHLCV 连续数据量化为分层离散 token，再由 decoder-only 自回归 Transformer 在这些 token 上预训练；针对金融数据高噪声特性专门设计，区别于通用时间序列基础模型（TSFM）。

---
## 9. [kornia/kornia](https://github.com/kornia/kornia)
- **语言**: Python
- **Stars**: 12,141
- **简介**: 🐍 Geometric Computer Vision Library for Spatial AI

### AI 总结
**简介**: Kornia 是一个基于 PyTorch 的可微分计算机视觉库，为空间 AI 提供丰富的可微分图像处理与几何视觉算法。

**核心功能**:
- 提供 1200+ 公共算子，涵盖相机模型、对极几何、最小求解器与 RANSAC、特征检测/描述/匹配、边缘检测、形态学、Lab 与 Bayer 颜色、图像损失与指标等，多数无 torchvision 对应实现
- 支持单次批处理调用中为每个样本传入独立参数（如 `(B,2)` 的 sigma、`(B,)` 旋转角度、`(B,2,3)`/`(B,3,3)` 变换矩阵）
- 提供批量最小求解器与鲁棒估计：`find_fundamental`（7 点/8 点法）、`find_essential`（5 点法）、DLT 单应、`solve_pnp_dlt`，以及可在设备上采样与评分的 `RANSAC`
- 支持可微分几何：深度与 3D 互转（`depth_to_3d_v2`、`unproject_points`、`project_points`）、`warp_frame_depth`、`remap`、Brown–Conrady 与 Kannala–Brandt 畸变相机模型，以及李群（`So3`、`Se3`）
- 提供带标注的增强：`AugmentationSequential` 对图像、掩码、框和关键点应用同一采样变换并支持逆变换

**技术亮点**: 构建于 PyTorch 之上，无缝集成现有 AI 工作流，支持批变换、自动微分与 GPU 加速；0.9.1 起在设备端校验参数以避免主机同步；RANSAC 支持 `compile=True` 将整个估计流程编译为单一计算图在设备上运行；项目定位为 PyTorch 生态中可微分计算机视觉与几何的参考实现与可执行规范。

---
## 10. [JustVugg/colibri](https://github.com/JustVugg/colibri)
- **语言**: C
- **Stars**: 46,592
- **简介**: Run frontier MoE models on hardware you already own — pure C, zero deps, experts streamed from disk. Tiny engine, immense model. 🐦

### AI 总结
**简介**: colibri 是一个用纯 C 编写的轻量推理引擎，通过将 MoE 模型的专家权重按需从磁盘流式加载，让普通硬件也能运行数百亿参数的前沿大模型。

**核心功能**:
- 支持 13 个引擎，覆盖 GLM-5.2/5.3、Kimi K3、DeepSeek V4 Flash、Qwen3.6/3.8-Flash-Next、OLMoE 等语言模型，以及 Qwen-Image-2.1 图像模型和 Laya、GLiNER2.5-Decide 等决策模型
- 一键安装脚本自动检测机器内存、磁盘、CPU/GPU，推荐可运行的模型并完成下载（支持断点续传）与启动
- 内置本地服务，提供 OpenAI 兼容（`/v1`）和 Anthropic 兼容接口，附带浏览器 Dashboard
- 可直接读取已发布的 GGUF 文件，无需转换

**技术亮点**:
- 纯 C 实现、零依赖，每个模型家族对应一个源文件
- 核心思路是 MoE 稀疏激活：每个 token 只用到模型的一小部分，该部分常驻内存，其余专家按需从磁盘读取，从而以极小内存占用（示例中 744B 模型常驻约 9.9 GB）运行超大模型
- 支持纯 CPU 推理，并可通过 Vulkan 使用任意 GPU、通过 CUDA 使用 NVIDIA 显卡
- 最低 8 GB 内存、22 GB 磁盘即可上手，显卡可选

---
