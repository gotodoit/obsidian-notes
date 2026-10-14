---
tags:
  - github-trending
  - daily
date: 2026-10-14
created: 2026-10-14T01:55:43.326Z
---

# 2026-10-14 GitHub Trending Top 9

## 1. [morluto/rea](https://github.com/morluto/rea)
- **语言**: TypeScript
- **Stars**: 209,495
- **简介**: Reverse engineer anything with agents, from app behavior down to native binaries.

### AI 总结
**简介**: REA 是一个基于 TypeScript 的 MCP 工具，让 AI Agent 能够对二进制文件、应用程序和运行时行为进行逆向工程分析。

**核心功能**:
- 通过 Agent 检查原生二进制文件、JavaScript/Electron 应用、.NET 程序集和网站，无需源码即可理解功能实现
- 支持从终端直接调用相同工具，分析结果附带证据和局限性说明
- 可复用已有的 Hopper、Ghidra 或 IDA 安装进行原生分析，静态 JavaScript 分析无需原生引擎

**技术亮点**: 基于 MCP（Model Context Protocol）协议集成到 Agent 工作流中，通过 `npx rea-agents setup` 一键配置；分析在本地运行，支持 Claude Code、Codex、Cursor、Gemini CLI 等多种 Agent；提供多语言文档（含中文、日文、韩文等 20 种语言）。

---
## 2. [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view)
- **语言**: JavaScript
- **Stars**: 55,484
- **简介**: A spy satellite simulator in your browser, except the data is real. Live open source spatial intelligence on a photorealistic 3D globe.

### AI 总结
**简介**: God's Eye View 是一个运行在浏览器中的开源间谍卫星模拟器，将真实的公开数据（航班、船舶、卫星、地震、摄像头等）汇聚在一个照片级逼真的 3D 地球上，支持实时追踪与语音交互。

**核心功能**:
- **驾驶舱视角**：进入被追踪航班的机内视角，摄像机全程锁定下方地形
- **点击追踪**：点击任意目标即可锁定、绘制轨迹、展示元数据，并一键跳转至最近的实时摄像头
- **语音白板**：通过语音在地球上标注边界多边形、标记和路线
- **3D 机库**：真实机型模型（787、ATR-72、MQ-9 等），目标靠近时从图标切换为 3D 模型
- **传感器滤镜**：GLSL 实现的 CRT、夜视、FLIR 热成像、黑白等视觉效果
- **军事 HUD 与检测叠加**：战术抬头显示及屏幕空间目标检测框
- **天气图层**：GFS/ECMWF 风场动画、雷达回波、云层、闪电及飓风路径追踪（无需密钥）
- **卫星过境查询**：语音询问任意已加载卫星的下次过境时间及可见性
- **分享链接**：将相机、样式、图层乃至追踪目标序列化为 URL，实现实时交接

**技术亮点**:
- 纯 JavaScript 实现，完全在浏览器本地运行，代码可审计可扩展
- 每个数据图层为独立模块，便于自行添加数据源
- 集成实时 AI 代理实现免手语音控制
- 照片级 3D 地球渲染，支持 GLSL 着色器自定义视觉风格
- 支持 Pinokio 一键安装或本地终端运行，无需 API 密钥即可启动
- 曾在 GitHub Trending 日榜与周榜登顶，并获得 JavaScript 之父 Brendan Eich 好评

---
## 3. [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio)
- **语言**: Python
- **Stars**: 63,460
- **简介**: VoiceStudio is the open-source, fully-local ElevenLabs alternative — voice cloning, voice design, video dubbing, dictation, transcription & audiobook creation in 646 languages.

### AI 总结
**简介**: VoiceStudio 是一个开源、完全本地运行的 ElevenLabs 替代方案，支持 646 种语言的语音克隆、语音设计、视频配音、听写、转录与有声书制作。

**核心功能**:
- **语音克隆与设计**：克隆已有声音或通过描述自定义设计音色
- **视频配音**：为视频添加带时间轴对齐的语音
- **听写与转录**：通过浮动小组件进行口述，支持音频转录
- **有声书与批量任务**：制作故事、有声书，支持批处理作业和监听文件夹
- **本地 API 与 MCP**：面向智能体提供本地接口，支持可复用配方
- **多引擎支持**：默认使用基于 k2-fsa/OmniVoice 的引擎，也可切换其他引擎

**技术亮点**:
- 基于 Python 开发，桌面端采用 Electron 构建
- 完全本地化运行，数据不出本机，远程服务为可选
- 支持多种硬件加速：NVIDIA GPU（CUDA）、Apple Silicon（Metal/MPS），无独显也可在 CPU 上运行
- 提供一键安装脚本（macOS/Linux/Windows）及 Docker 部署方案
- 采用 AGPL-3.0 开源协议

---
## 4. [mksglu/context-mode](https://github.com/mksglu/context-mode)
- **语言**: TypeScript
- **Stars**: 28,282
- **简介**: Context window optimization for AI coding agents. Sandboxes tool output (98% reduction), persists session memory, and enforces routing across 17 platforms via MCP + hooks.

### AI 总结
**简介**: Context Mode 是一个面向 AI 编程代理的上下文窗口优化 MCP 服务器，通过沙箱化工具输出、持久化会话记忆和智能路由，解决上下文膨胀与丢失问题。

**核心功能**:
- **上下文节省**：将工具原始输出沙箱化，315 KB 压缩至 5.4 KB，减少 98% 的上下文占用
- **会话连续性**：用 SQLite 跟踪文件编辑、git 操作、任务、错误和用户决策，通过 FTS5 索引 + BM25 检索在压缩后精准恢复相关上下文
- **代码化思考**：引导 LLM 以代码方式处理任务，减少冗余输出和客套话
- **跨平台路由**：通过 MCP + hooks 在 17 个平台上强制执行统一路由策略

**技术亮点**: 基于 TypeScript 构建，采用 MCP 协议集成，使用 SQLite + FTS5 全文索引 + BM25 检索实现高效记忆持久化与召回；支持会话隔离（未 `--continue` 则立即删除旧数据）；采用 ELv2 许可证，已被 Microsoft、Google、Meta、NVIDIA 等团队使用。

---
## 5. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 54,211
- **简介**: Editorial diagram design for Claude Code, Codex, GitHub Copilot, Cursor, Factory Droid, and Pi. 44 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个面向 AI 编程助手的 Agent Skill，用自包含的 HTML + SVG 生成编辑级品质的图表，替代 Mermaid 风格的粗糙输出。

**核心功能**:
- 支持 45 种图表类型，覆盖架构图、象限图、时序图等常见需求
- 用自然语言向 Agent 描述需求，自动选择图表类型、说明方案并输出单个可双击打开的 `.html` 文件
- 可通过 `onboard` 抓取指定网站的配色与字体，让后续所有图表匹配品牌风格
- 支持从 draw.io、Mermaid、Excalidraw 导入，并导出为 PNG / SVG
- 兼容 Cursor、Claude Code、Codex、GitHub Copilot、Gemini CLI、Cline、Windsurf 等 Agent Skills 宿主

**技术亮点**: 输出为单文件 HTML + SVG，无外部依赖、无阴影；通过 `npx skills add` 跨宿主安装，多目录时推荐符号链接以统一更新；仅支持 MIT 协议，官方构建仅来自本仓库。

---
## 6. [vercel-labs/skills](https://github.com/vercel-labs/skills)
- **语言**: TypeScript
- **Stars**: 34,546
- **简介**: The open agent skills tool - npx skills

### AI 总结
**简介**: Vercel Labs 推出的开源 Agent Skills 生态 CLI 工具，通过 `npx skills` 命令让开发者便捷地安装、使用和分发 AI 编码代理技能。

**核心功能**:
- **技能安装**：`npx skills add <source>` 支持从 GitHub、GitLab、Azure Repos、任意 Git URL 或本地路径安装技能，支持私有仓库认证。
- **即用不装**：`npx skills use` 可临时生成技能提示词（prompt），支持管道输出给 Claude 等工具，或通过 `--agent` 直接启动交互式编码代理。
- **广泛的代理支持**：兼容 OpenCode、Claude Code、Codex、Cursor 等 80 种主流 AI 编码代理。
- **灵活选项**：支持全局安装（`-g`）、指定代理（`-a`）、按名称选择技能（`-s`）、列出可用技能（`-l`）等。

**技术亮点**: 基于 TypeScript 开发，通过 npm 分发（`npx skills`）；采用多级认证回退策略（Git 凭证 → GitHub CLI → SSH）处理私有仓库访问，且不读取或打印用户凭证，保障安全性；支持多种源格式（GitHub 简写、完整 URL、GitLab、Azure DevOps、SSH、本地路径）。

---
## 7. [lyogavin/airllm](https://github.com/lyogavin/airllm)
- **语言**: Jupyter Notebook
- **Stars**: 38,363
- **简介**: AirLLM 2.8T LLM inference with single 4GB GPU

### AI 总结
**简介**: AirLLM 是一个通过分层流式加载大幅降低大模型推理显存占用的工具，可在单张 4GB 显卡上运行 70B 乃至 2.8T 参数的超大语言模型，无需量化、蒸馏或剪枝。

**核心功能**:
- 极低显存推理：70B 模型仅需 4GB，Kimi K3 (2.8T) 约 3.72GB，DeepSeek-V3 (671B) 约 12GB，Qwen3-235B 约 3GB
- 小显存训练支持：通过流式加载冻结权重、适配器保留在 GPU 上，125B 模型可在 6GB 显存下训练
- 广泛的模型兼容：支持 Llama 3.x/4、Qwen 系列、DeepSeek V2/V3、Phi-4、Gemma、ChatGLM、Baichuan、Mistral、InternLM 等，并提供统一的 `AutoModel` 自动识别模型类型
- 跨平台支持：支持 CPU 推理与 MacOS 运行 70B 模型，兼容 safetensors 及 8bit/4bit 量化

**技术亮点**:
- 逐层流式加载（layer-by-layer streaming）与预取（prefetching），重叠模型加载与计算以提升速度
- 针对 MoE 模型的按专家流式加载（per-expert streaming），仅加载 token 实际路由到的专家
- n-gram 嵌入表采用主机端文件映射，解码层流式加载，进一步压缩显存占用
- 基于 Jupyter Notebook 实现，代码采用 Apache 2.0 许可

---
## 8. [storytold/artcraft](https://github.com/storytold/artcraft)
- **语言**: Rust
- **Stars**: 25,795
- **简介**: ArtCraft is an intentional crafting engine for artists, designers, and filmmakers

### AI 总结
**简介**: ArtCraft 是一款面向艺术家、设计师和电影制作人的交互式 AI 图像与视频创作 IDE，用可视化工具将提示词转化为精确、可重复的创作流程。

**核心功能**:
- **Image to Location**：将虚拟角色置于一致的环境中，在同一场景内规划多个镜头
- **3D 图像合成**：在 3D 空间中分层布置背景、前景和道具，构建具有深度的构图
- **2D 图像合成**：通过图像图层、背景移除和绘图工具进行场景合成
- **Image to 3D Mesh**：将图像转化为可精确定位、旋转和取景的 3D 对象
- **角色姿态设定**：在生成最终镜头前摆好角色姿态并设置相机
- **场景布局与 Kitbashing**：组合 3D 资产套件来控制相机角度、物体位置和景深

**技术亮点**: 使用 Rust 语言开发；支持 2D 构图与 3D 场景搭建相结合的工作流；用户可选择适合自己项目的 AI 模型；支持从源码构建，提供 GitHub Releases 下载。

---
## 9. [xtool-org/xtool](https://github.com/xtool-org/xtool)
- **语言**: Swift
- **Stars**: 9,462
- **简介**: Cross-platform Xcode replacement. Build and deploy iOS apps with SwiftPM on Linux, Windows, macOS.

### AI 总结
**简介**: xtool 是一个跨平台的 Xcode 替代工具，基于 SwiftPM 在 Linux、Windows 和 macOS 上构建和部署 iOS 应用。

**核心功能**:
- 将 SwiftPM 包构建为 iOS 应用
- 对 iOS 应用进行签名与安装
- 以编程方式与 Apple Developer Services 交互
- 提供设备管理功能（列出设备、安装/卸载应用、启动应用）
- 提供命令行工具及可复用的 XKit 库

**技术亮点**: 使用 Swift 编写，基于 SwiftPM 构建系统，采用开放标准复刻 Xcode 功能；提供 CLI 工具链（setup、auth、sdk、new、dev、ds、devices 等子命令），并支持作为 SwiftPM 依赖库（XKit）集成到自有应用中。

---
