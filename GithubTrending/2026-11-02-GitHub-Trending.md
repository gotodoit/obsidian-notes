---
tags:
  - github-trending
  - daily
date: 2026-11-02
created: 2026-11-02T01:55:43.205Z
---

# 2026-11-02 GitHub Trending Top 10

## 1. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 109,363
- **简介**: Persistent Context Across Sessions for Every Agent – Captures everything your agent does during sessions, compresses it with AI, and injects relevant context back into future sessions. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode + More

### AI 总结
**简介**: Claude-Mem 是一个为 Claude Code 等 AI 编程助手提供跨会话持久记忆的压缩系统，能捕获会话内容、用 AI 压缩并注入未来会话。

**核心功能**:
- 捕获 Agent 在会话中的所有操作记录
- 使用 AI 对会话内容进行压缩存储
- 在后续会话中自动注入相关上下文，实现跨会话记忆
- 兼容 Claude Code、OpenClaw、Codex、Gemini、Hermes、Copilot、OpenCode 等多种 Agent

**技术亮点**:
- 基于 TypeScript 开发，要求 Node.js ≥ 20.0.0
- 采用 Apache 2.0 开源协议
- 支持多语言文档（含中文、日文、韩文等 30+ 语言）
- 曾登上 GitHub Trending 日榜，并被 Awesome Claude Code 收录

---
## 2. [lightpanda-io/browser](https://github.com/lightpanda-io/browser)
- **语言**: Zig
- **Stars**: 40,203
- **简介**: Lightpanda: the headless browser designed for AI and automation

### AI 总结
**简介**: Lightpanda 是一款专为 AI 智能体和自动化场景从零构建的无头浏览器，使用 Zig 语言编写，并非 Chromium 或 WebKit 的分支。

**核心功能**:
- 抓取网页并支持导出为 HTML、Markdown、PNG、PDF 等格式（`fetch --dump` 命令）
- 通过 CDP（Chrome DevTools Protocol）服务器与 Puppeteer、Playwright 等自动化客户端对接
- 提供官方 Docker 镜像，支持 Linux amd64/arm64

**技术亮点**:
- 使用 Zig 语言从零实现，相比 Chromium 无头模式内存占用约减少 16 倍、执行速度快约 9 倍（100 页面峰值内存 123MB vs 2GB，耗时 5s vs 46s）
- 支持 Homebrew、AUR、Nix Flake、预编译二进制及 Docker 多种安装方式
- 需 glibc 环境，不支持原生 Windows/Android（Windows 需通过 WSL2 使用）

---
## 3. [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos)
- **语言**: Python
- **Stars**: 45,427
- **简介**: Kronos: A Foundation Model for the Language of Financial Markets

### AI 总结
**简介**: Kronos 是首个面向金融市场 K 线（蜡烛图）序列的开源基础模型，基于全球 45+ 交易所数据预训练，论文已被 AAAI 2026 接收。

**核心功能**:
- 提供 Kronos-mini / small / base / large 四种规模的预训练模型（4.1M–499.2M 参数），均可在 Hugging Face 获取（large 暂未开源）
- 通过 `KronosPredictor` 类实现端到端的 K 线预测，自动完成数据预处理与归一化
- 提供 BTC/USDT 未来 24 小时走势的可视化在线 Demo
- 官方发布微调脚本，支持适配自定义量化任务

**技术亮点**:
- 采用两阶段框架：专用 tokenizer 先将多维 OHLCV 连续数据量化为分层离散 token，再由自回归 Transformer 在这些 token 上预训练
- 针对金融数据高噪声特性专门设计，区别于通用时间序列基础模型（TSFM）
- 基于 decoder-only 架构，统一支持多种量化任务；使用 Python 3.10+，依赖见 requirements.txt

---
## 4. [pingdotgg/t3code](https://github.com/pingdotgg/t3code)
- **语言**: TypeScript
- **Stars**: 38,146
- **简介**: 

### AI 总结
**简介**: T3 Code 是一个“智能体控制面板”，让你通过移动端、Web 和桌面应用远程控制本机上的多种 AI 编程智能体。

**核心功能**:
- 统一控制本机已安装的 Claude Code、Codex、Cursor、Grok Build、OpenCode、Antigravity、fx 等智能体
- 提供 iOS、Android 移动应用、Web 应用及基于 Electron 的桌面应用
- 支持远程访问（手机或其他机器）、权限模式、快捷键、项目设置与外观偏好配置
- 支持多账号接入、源码管理集成，并可作为后台服务运行
- 可通过 MCP 与外部智能体（如 Claude Code、Codex、ChatGPT）连接

**技术亮点**: 使用 TypeScript 开发；桌面端基于 Electron；构建工具采用 Vite+（需全局 `vp` 命令）；提供命令行安装脚本、`npx t3@latest` 免安装试用，并覆盖 winget、scoop、Homebrew、.deb、AUR、Nix 等多种分发渠道；项目完全开源，允许用户自行 fork 和定制。

---
## 5. [milind-soni/OpenMausBot](https://github.com/milind-soni/OpenMausBot)
- **语言**: TypeScript
- **Stars**: 10,583
- **简介**: Open-source Grok Bot alternative with a virtual machine that bots can use

### AI 总结
**简介**: OpenMausBot 是一个开源的 Grok Bot 替代方案，以聊天应用的形式提供一支由 AI 机器人组成的团队，每个机器人都能在本地运行真实 Agent，并拥有独立的虚拟机与已连接应用。

**核心功能**:
- 侧边栏中的每个机器人都是真实 Agent（底层运行 Claude 或 Codex），拥有独立人格、模型、云电脑和已连接应用
- 像聊联系人一样与机器人对话，可实时观察其工作过程，并对关键操作进行审批
- 支持自带 Agent、本地优先，可运行在用户已有的模型之上
- 提供 macOS（Apple Silicon / Intel）、Windows、Ubuntu 多平台安装包

**技术亮点**: 基于 TypeScript（严格模式）开发，前端使用 React 19，桌面端采用 Electron 跨平台架构，兼容 Claude 与 Codex 两类 Agent。

---
## 6. [public-apis/public-apis](https://github.com/public-apis/public-apis)
- **语言**: Python
- **Stars**: 494,662
- **简介**: A collective list of free APIs

### AI 总结
**简介**: 一个由社区维护的免费公共 API 集合仓库，汇总了覆盖多种领域的公开 API 资源。

**核心功能**:
- 提供跨领域的公共 API 清单，供开发者在产品中直接选用
- 由社区成员与 APILayer 团队人工整理与维护
- 附带 APILayer 统一套件介绍，可用单一账号、仪表盘和 API Key 接入多个生产级 REST API（如 IPstack、Marketstack、Weatherstack、Aviationstack 等）
- 提供 Postman 集合，支持快速试用

**技术亮点**: 仓库以 Python 为主，内容以 Markdown 文档形式组织；集成 APILayer 套件与 Postman 一键运行集合，便于快速验证与接入 API。

---
## 7. [cjpais/Handy](https://github.com/cjpais/Handy)
- **语言**: Rust
- **Stars**: 36,602
- **简介**: A free, open source, and extensible speech-to-text application that works completely offline.

### AI 总结
**简介**: Handy 是一款免费、开源、可扩展的跨平台桌面语音转文字应用，完全离线运行，按下快捷键说话即可将转录文本粘贴到任意输入框。

**核心功能**:
- 快捷键录音：支持按住录音/松开停止、点按切换两种模式，快捷键可自定义
- 本地转录：使用 Whisper 模型（Small/Medium/Turbo/Large，支持 GPU 加速）或 CPU 优化的 Parakeet V3（支持自动语言检测）
- 静音过滤：基于 Silero 的 VAD（语音活动检测）过滤静音片段
- 跨平台支持：Windows、macOS、Linux，提供 Homebrew、winget、.deb 等安装方式
- 扩展与集成：支持 Raycast 扩展（控制录音、浏览历史、管理词典、切换模型和语言），提供调试模式与 CLI 参数控制

**技术亮点**: 使用 Rust 开发；全流程本地处理，音频不上传云端，注重隐私；转录结果直接粘贴到当前应用；提供命令行远程控制（如 `--toggle-transcription`、`--cancel`）等 beta 功能。

---
## 8. [Donchitos/Claude-Code-Game-Studios](https://github.com/Donchitos/Claude-Code-Game-Studios)
- **语言**: Shell
- **Stars**: 32,357
- **简介**: Turn Claude Code into a full game dev studio — 49 AI agents, 72 workflow skills, and a complete coordination system mirroring real studio hierarchy.

### AI 总结
**简介**: 该项目将单次 Claude Code 会话转化为一个完整的游戏开发工作室，通过 49 个 AI 智能体、74 个工作流技能和完整的协调系统，模拟真实工作室的层级结构来辅助游戏开发。

**核心功能**:
- **49 个专业化智能体**：按真实工作室层级分为三层——总监层（创意、技术、制作）、部门主管层（游戏设计、主程、美术、音频、叙事、QA 等）和专家层（玩法程序、引擎程序、AI 程序、关卡设计、经济设计、技术美术等），每个智能体有明确职责、升级路径和质量关卡。
- **74 个工作流技能（Slash 命令）**：覆盖从启动、设计系统、创建史诗/故事、开发故事到故事完成的完整开发流程。
- **15 个自动化钩子**：在提交、推送、资源变更、设计文档读写、会话生命周期等环节进行自动验证，并包含智能体审计追踪和缺口检测。
- **14 条路径作用域规则**：针对玩法、引擎、AI、UI、网络代码及场景资源文件等强制执行编码标准。
- **62 个文档模板**：包括 GDD、UX 规格、ADR、冲刺计划、HUD 设计、无障碍设计等。
- **多引擎支持**：为三大主流游戏引擎提供对应的智能体集合。

**技术亮点**:
- 基于 Claude Code 构建，使用 Shell 语言实现，采用 MIT 许可证。
- 智能体按模型分层配置：三位总监使用 Opus，主程和十五位专家使用 Sonnet，其余三十位继承会话模型。
- 通过三层工作室层级（总监 → 部门主管 → 专家）实现结构化协作，包含升级路径和质量门禁，确保从头脑风暴到发布的全程组织性。

---
## 9. [kornia/kornia](https://github.com/kornia/kornia)
- **语言**: Python
- **Stars**: 11,819
- **简介**: 🐍 Geometric Computer Vision Library for Spatial AI

### AI 总结
**简介**: Kornia 是一个基于 PyTorch 的可微分计算机视觉库，面向空间 AI，提供可微的图像处理与几何视觉算法。

**核心功能**:
- 覆盖 1,200+ 公开算子，包括相机模型、对极几何、最小求解器与 RANSAC、特征检测/描述/匹配、边缘检测、形态学、Lab 与 Bayer 颜色、图像损失与指标等
- 支持单次批量调用中为每个样本传入独立参数（如 `(B, 2)` 的 sigma、`(B,)` 的旋转角度、`(B, 3, 3)` 的透视变换矩阵）
- 批量最小求解器与鲁棒估计：7 点/8 点基础矩阵、5 点本质矩阵、DLT 单应、PnP（DLT）以及单应/基础/本质模型的 RANSAC
- 可微几何：深度与 3D 互转、`warp_frame_depth`、`remap`、Brown–Conrady 与 Kannala–Brandt 畸变相机模型、李群（So3、Se3）
- 带标注的增强：`AugmentationSequential` 对图像、掩码、框和关键点施加同一采样变换并支持逆变换

**技术亮点**: 构建于 PyTorch 之上，无缝融入现有 AI 工作流，支持批量变换、自动微分与 GPU 加速；RANSAC 支持 `compile=True` 将整个估计流程编译为设备上的单一计算图；目标定位为 PyTorch 生态中可微视觉与几何的参考实现和可执行规范（明确的约定、一致性测试与诚实的基准）。

---
## 10. [beenuar/AiSOC](https://github.com/beenuar/AiSOC)
- **语言**: Python
- **Stars**: 6,256
- **简介**: Open-source AI Security Operations Center: alert fusion, LLM-agent triage, MITRE ATT&CK investigation, and a replayable decision ledger for every agent step. Self-hostable, runs with no API keys, MIT licensed. Ships an MCP server for Claude, Cursor and Continue.

### AI 总结
**简介**: AiSOC 是一个开源、可自托管的 AI 安全运营中心（SOC），通过可审计的 AI 代理对安全告警进行融合、调查与响应建议。

**核心功能**:
- **告警融合与检测**：归一化来自各类安全工具的遥测数据，运行 7023 条规则库中的 2538 条可执行规则，并将触发结果聚合为事件（Incident）。
- **LLM 代理分诊**：用 AI 代理对每个事件进行调查，完整记录每一步提示词与工具调用，形成可回放、可审计的决策账本。
- **MITRE ATT&CK 调查**：结合 ATT&CK 框架开展威胁调查，并给出处置建议，最终由人工审批后才触达厂商系统。
- **威胁情报回溯**：新威胁情报可对已收集的历史数据进行重新扫描。
- **MCP 服务器**：内置 MCP 服务器，可接入 Claude、Cursor、Continue 等工具。

**技术亮点**:
- 基于 Python 开发，采用 Docker Compose 一键部署（`make up`）。
- 无需 API Key 即可运行，内置本地模型（首次启动下载约 2GB），支持离线演示（`pip install aisoc-sandbox && aisoc-sandbox demo`，30 秒内跑通单条告警流程）。
- 支持 Windows 一键安装脚本、Linux/macOS 安装脚本及 GitHub Codespaces 部署。
- 采用 MIT 许可证，具备 CI、CodeQL、OpenSSF Scorecard 等安全与质量保障。

---
