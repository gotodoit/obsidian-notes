---
tags:
  - github-trending
  - daily
date: 2026-06-25
created: 2026-06-25T01:55:43.516Z
---

# 2026-06-25 GitHub Trending Top 10

## 1. [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)
- **语言**: Python
- **Stars**: 19,563
- **简介**: World's first open-source, agentic video production system. 12 pipelines, 52 tools, 500+ agent skills. Turn your AI coding assistant into a full video production studio.

### AI 总结
**简介**: OpenMontage 是全球首个开源的智能体视频制作系统，能将 AI 编程助手转变为完整的视频制作工作室。

**核心功能**:
- 支持自然语言描述视频需求，智能体自动完成研究、脚本、素材生成、剪辑和最终合成
- 包含 12 条流水线、52 种工具和 500 多种智能体技能
- 能够生成真正的视频（基于免费库存镜头和开放档案的真实运动片段），而非简单的图像动画
- 支持多种视频风格，包括电影预告片、动画短片、产品广告和动漫风格动画

**技术亮点**: 基于 Python 构建，集成 FLUX、Veo、Kling 等多种 AI 视频/图像生成模型，使用 Remotion 进行合成，支持 WhisperX 字幕生成和多种 AI 语音合成（如 Chirp3-HD），成本极低（部分项目仅需 $0.15-$1.33）

---
## 2. [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis)
- **语言**: Python
- **Stars**: 48,582
- **简介**: LLM 驱动的多市场股票智能分析系统：多源行情、实时新闻、决策看板与自动推送，支持零成本定时运行。 LLM-powered multi-market stock analysis system with multi-source market data, real-time news, decision dashboard, automated notifications, and cost-free scheduled runs.

### AI 总结
**简介**: 一个基于 AI 大模型的智能股票分析系统，支持 A股/港股/美股/日股/韩股，每日自动生成决策仪表盘并推送至多种通讯工具，可零成本定时运行。

**核心功能**:
- AI 决策报告：自动生成包含评分、趋势、买卖点、风险警报等内容的分析报告
- 多市场数据聚合：支持 A股、港股、美股、日股、韩股，整合行情、K线、新闻、公告、基本面等数据
- 自动化与推送：通过 GitHub Actions/Docker/本地定时任务自动运行，支持企业微信、飞书、Telegram、Discord、Slack、邮件推送
- Web/桌面工作台：提供手动分析、任务进度、历史报告、回测、持仓和配置管理界面
- Agent 策略问股：支持均线、缠论、波浪、趋势等 15 种内置策略的多轮追问
- 智能导入与补全：支持图片、CSV/Excel、剪贴板导入，以及股票代码/名称/拼音的自动补全

**技术亮点**: 采用 Python 3.10+ 开发，集成多种 AI 模型（Anspire、Gemini、OpenAI 兼容、DeepSeek、Ollama 本地模型等）与数据源（AkShare、Tushare、YFinance、TickFlow 等），支持 GitHub Actions 零成本部署和 Docker 容器化运行。

---
## 3. [apple/container](https://github.com/apple/container)
- **语言**: Swift
- **Stars**: 42,283
- **简介**: A tool for creating and running Linux containers using lightweight virtual machines on a Mac. It is written in Swift, and optimized for Apple silicon.

### AI 总结
**简介**: `container` 是苹果官方推出的 Swift 工具，专为 Apple Silicon Mac 设计，用于创建和运行基于轻量级虚拟机的 Linux 容器。

**核心功能**:
- **OCI 兼容**：支持拉取、运行和推送标准 OCI 容器镜像，可与任何容器仓库交互。
- **系统服务管理**：提供 `container system start/stop` 命令管理后台服务。
- **安装与升级**：提供签名安装包和自动更新/卸载脚本，支持版本回退并保留用户数据。
- **引导与文档**：包含交互式教程、技术概览、命令参考和 API 文档。

**技术亮点**: 基于 Swift 开发，利用 macOS 26 虚拟化与网络新特性；底层依赖 [Containerization](https://github.com/apple/containerization) 包实现容器、镜像和进程管理；当前处于活跃开发阶段，API 稳定性仅在补丁版本内保证。

---
## 4. [interviewstreet/hiring-agent](https://github.com/interviewstreet/hiring-agent)
- **语言**: Python
- **Stars**: 2,223
- **简介**: AI agent to evaluate and score resumes.

### AI 总结
**简介**: 一个利用AI对简历进行公平、可解释性评分的人才筛选工具。

**核心功能**:
- **简历解析与结构化**: 自动将PDF简历转换为Markdown文本，并利用LLM提取为结构化的JSON数据（如工作经验、技能等）。
- **GitHub信号增强**: 自动获取候选人的GitHub资料和仓库信息，对项目进行分类和评估，作为简历之外的补充参考。
- **公平性评分**: 通过严格的评分逻辑，结合类别评分、证据、加分和扣分项，输出客观且可解释的最终评估结果。

**技术亮点**:
- **模块化流水线架构**: 清晰划分为PDF解析、LLM提取、GitHub增强、评分等多个独立模块，易于维护和扩展。
- **支持多种LLM后端**: 既支持使用Ollama完全本地运行（如gemma3模型），也支持使用Google Gemini云端API，兼顾隐私与性能。
- **使用Jinja模板驱动**: 通过`prompts/templates/`下的Jinja模板精细控制LLM对不同简历章节的提取指令，提高了输出的稳定性和准确性。

---
## 5. [JCodesMore/ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template)
- **语言**: TypeScript
- **Stars**: 19,364
- **简介**: Clone any website with one command using AI coding agents

### AI 总结
**简介**: 一个基于AI编码代理的反向工程模板，可将任意网站一键克隆为现代Next.js代码库。

**核心功能**:
- 支持通过一条命令 `/clone-website <URL>` 自动克隆目标网站
- 自动执行侦察、设计令牌提取、组件规范生成和并行构建
- 兼容Claude Code、Codex CLI、Cursor等12+主流AI编码代理

**技术亮点**:
- 基于Next.js 16 + React 19 + TypeScript严格模式
- 采用shadcn/ui（Radix原语）+ Tailwind CSS v4（oklch设计令牌）
- 多阶段流水线：侦察→基础更新→组件规范→并行构建

---
## 6. [revfactory/harness](https://github.com/revfactory/harness)
- **语言**: HTML
- **Stars**: 7,759
- **简介**: A meta-skill that designs domain-specific agent teams, defines specialized agents, and generates the skills they use.

### AI 总结
**简介**: Harness 是一个面向 Claude Code 的团队架构工厂，只需输入领域描述，即可自动生成由多个专业智能体组成的协作团队及其技能，支持六种预设团队架构模式。

**核心功能**:
- **智能体团队设计**: 提供六种架构模式（流水线、扇出/扇入、专家池、生产者-审查者、监督者、层级委派），可根据任务需求自动选择最优团队结构。
- **技能自动生成**: 为每个智能体自动生成技能文件，并采用渐进式信息披露机制优化上下文管理效率。
- **编排与集成**: 实现智能体间的数据传递、错误处理和团队协作协议。
- **验证与测试**: 提供触发验证、试运行测试以及有无技能对比测试等功能。

**技术亮点**:
- 位于 Claude Code 生态系统的 L3 元工厂层，作为团队架构工厂子层与其他元工厂（如运行时配置工厂）互补共存。
- 自动生成 `.claude/agents/` 和 `.claude/skills/` 目录结构，无缝集成到 Claude Code 工作流。
- 支持通过插件市场或全局技能安装，部署灵活。

---
## 7. [flutter/flutter](https://github.com/flutter/flutter)
- **语言**: Dart
- **Stars**: 177,351
- **简介**: Flutter makes it easy and fast to build beautiful apps for mobile and beyond

### AI 总结
**简介**: Flutter 是 Google 推出的开源 SDK，用于从单一代码库构建移动、Web 和桌面端美观且高性能的应用程序。

**核心功能**:
- 支持 iOS、Android、Web、Windows、macOS、Linux 等多平台开发
- 提供丰富的预构建组件（Material Design 和 Cupertino 风格）
- 支持热重载，实现代码修改后即时预览，无需重启应用
- 通过 FFI 和平台通道轻松访问原生代码和平台特定 API

**技术亮点**: 基于 Dart 语言，使用 Skia/Impeller 硬件加速 2D 图形引擎，支持 AOT 编译为 ARM/x86 机器码及 WebAssembly，确保原生级性能。

---
## 8. [andreknieriem/headunit-revived](https://github.com/andreknieriem/headunit-revived)
- **语言**: Kotlin
- **Stars**: 1,429
- **简介**: Headunit App for displaying Android Auto

### AI 总结
**简介**: 一个基于 Kotlin 开发的开源 Android 应用，可将 Android 平板或手机变身为 Android Auto 接收器。

**核心功能**:
- 支持有线 USB 连接和无线连接（推荐使用 Wireless Helper 伴侣应用）
- 提供 Legacy 无线连接选项（Wireless Launcher 或原生 Android Auto 服务器）
- 支持通过 Intent 自动化触发无线连接（适配 Tasker、MacroDroid 等工具）
- 提供多种设置选项（如像素密度调节解决地图触摸问题）

**技术亮点**: 采用 Kotlin 语言开发，支持 USB 原生协议与 libusb 兼容性优化，集成 Wi-Fi Direct、蓝牙自动启动和 NSD 网络发现技术。

---
## 9. [stablyai/orca](https://github.com/stablyai/orca)
- **语言**: TypeScript
- **Stars**: 6,832
- **简介**: Orca is the ADE for working with a fleet of parallel agents. Run any coding agent with your own subscription. Available on desktop and mobile.

### AI 总结
**简介**: Orca 是一个 AI 编排器（ADE），可让您并行运行多个编码代理（如 Codex、ClaudeCode），每个代理在独立的 git 工作区中运行，并支持桌面和移动端监控。

**核心功能**:
- **移动端伴侣**: 通过手机监控和引导代理，接收完成通知并发送后续指令。
- **并行工作区**: 将同一提示分发给多个代理，每个代理在独立的 git 工作区中运行，便于比较结果和合并最佳方案。
- **终端分屏**: 支持 WebGL 渲染的 Ghostty 级终端，无限分屏，重启后保留滚动历史。
- **设计模式**: 在真实 Chromium 窗口中点击 UI 元素，自动提取其 HTML、CSS 和截图，直接注入代理提示。
- **GitHub & Linear 原生集成**: 在应用内浏览 PR、Issues 和项目看板，从任务直接创建工作区，无需切换上下文。
- **SSH 工作区**: 在远程服务器上运行代理，支持完整文件编辑、git 操作、终端、自动重连和端口转发。

**技术亮点**: 使用 TypeScript 构建，支持 macOS、Windows 和 Linux 三平台，采用 WebGL 终端渲染和 Chromium 嵌入式浏览器架构。

---
## 10. [google-labs-code/design.md](https://github.com/google-labs-code/design.md)
- **语言**: TypeScript
- **Stars**: 17,391
- **简介**: A format specification for describing a visual identity to coding agents. DESIGN.md gives agents a persistent, structured understanding of a design system.

### AI 总结
**简介**: DESIGN.md 是一个用于向编码代理描述视觉标识的格式规范，通过结构化的设计令牌和设计原理，让代理持久理解设计系统。

**核心功能**:
- **设计令牌定义**: 支持颜色、排版、圆角、间距、组件等机器可读的设计令牌，使用YAML front matter格式
- **设计原理说明**: 通过Markdown正文提供人类可读的设计决策背景和适用规则
- **规范验证(Lint)**: 提供CLI工具验证DESIGN.md文件，检测令牌引用错误、WCAG对比度问题，输出结构化JSON结果
- **版本差异对比(diff)**: 比较两个设计系统版本，检测令牌级别的增删改变化和回归问题

**技术亮点**: 使用TypeScript实现，提供npx命令行工具；设计令牌支持CSS颜色格式（hex、rgb、oklch等）、Token Reference引用机制；组件支持变体（hover、active等）表达；输出结构化JSON供代理程序消费。

---
