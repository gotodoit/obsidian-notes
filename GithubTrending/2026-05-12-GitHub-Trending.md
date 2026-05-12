---
tags:
  - github-trending
  - daily
date: 2026-05-12
created: 2026-05-12T01:55:47.606Z
---

# 2026-05-12 GitHub Trending Top 10

## 1. [bytedance/UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop)
- **语言**: TypeScript
- **Stars**: 33,039
- **简介**: The Open-Source Multimodal AI Agent Stack: Connecting Cutting-Edge AI Models and Agent Infra

### AI 总结
**简介**: 字节跳动开源的多模态AI智能体平台，包含通用AI Agent（Agent TARS）和桌面应用（UI-TARS Desktop）两个项目，通过GUI Agent和视觉能力连接前沿AI模型与智能体基础设施。

**核心功能**:
- **Agent TARS**: 提供CLI和Web UI界面，通过多模态大语言模型和MCP工具实现类人任务完成，支持终端、计算机、浏览器和产品集成
- **UI-TARS Desktop**: 基于UI-TARS模型的原生桌面GUI Agent，支持本地和远程计算机及浏览器操作
- 远程计算机/浏览器操作器（v0.2.0新增），无需配置即可远程控制设备
- 事件流查看器用于数据流追踪和调试（v0.3.0新增）
- 支持AIO智能体沙箱作为隔离执行环境

**技术亮点**: 基于TypeScript开发，采用多模态大语言模型与GUI Agent技术，集成MCP工具生态，提供跨平台SDK工具包，支持流式处理、运行时统计和结构化数据显示

---
## 2. [CloakHQ/CloakBrowser](https://github.com/CloakHQ/CloakBrowser)
- **语言**: Python
- **Stars**: 6,239
- **简介**: Stealth Chromium that passes every bot detection test. Drop-in Playwright replacement with source-level fingerprint patches. 30/30 tests passed.

### AI 总结
**简介**: CloakBrowser 是一个开源的隐身 Chromium 浏览器，通过 C++ 源码级指纹修改，能通过所有机器人检测测试，可作为 Playwright/Puppeteer 的即插即用替代品。

**核心功能**:
- **源码级隐身**：49个 C++ 源码补丁，修改 canvas、WebGL、音频、字体、GPU、屏幕、WebRTC 等指纹，通过 30+ 检测网站测试
- **人类行为模拟**：`humanize=True` 参数一键开启类人鼠标轨迹、键盘节奏和滚动模式，通过行为检测
- **高 reCAPTCHA v3 分数**：服务器验证可达 0.9 分，行为完全像真实用户
- **自动更新**：后台自动检查并下载最新隐身构建版本
- **多语言支持**：Python (`pip install cloakbrowser`) 和 JavaScript (`npm install cloakbrowser`)，零配置自动下载二进制文件
- **浏览器配置文件管理**：提供自托管替代 Multilogin/GoLogin 的配置文件管理器，支持代理和持久会话

**技术亮点**: 基于 Chromium 内核的 C++ 源码级修改，非 JS 注入或配置补丁；支持 Playwright/Puppeteer 的同步和异步 API 兼容；Docker 一键运行测试；可选 geoip 自动检测代理 IP 时区/语言环境。

---
## 3. [yikart/AiToEarn](https://github.com/yikart/AiToEarn)
- **语言**: TypeScript
- **Stars**: 10,844
- **简介**: Let's use AI to Earn!

### AI 总结
**简介**: 为“一人公司”(OPC)和创作者打造的一站式AI内容营销平台，通过AI自动化实现内容变现、分发与互动。

**核心功能**:
- **💰 内容赚钱 (Monetize)**: 创作者可通过完成商家推广任务赚取佣金，支持按成交(CPS)、互动(CPE)、播放量(CPM)三种结算模式。
- **📢 内容发布 (Publish)**: 一键将内容分发至抖音、小红书、YouTube、TikTok等10+全球主流平台，并支持日历排期。
- **💬 内容互动 (Engage)**: 通过浏览器插件实现自动点赞、收藏、评论，并利用AI进行智能回复、评论挖掘和品牌监测。
- **🎨 内容创作 (Create)**: 通过AI Agent自动完成视频生成、图文制作、翻译和剪辑，支持批量内容创作。

**技术亮点**:
- 采用 **TypeScript** 开发，支持 **Docker** 一键部署及源码开发。
- 提供 **MCP 协议** 支持，可集成到 Claude、Cursor 等AI助手中使用。
- 支持 **OpenClaw (龙虾)** 平台内嵌使用，扩展性强。

---
## 4. [playcanvas/supersplat](https://github.com/playcanvas/supersplat)
- **语言**: TypeScript
- **Stars**: 7,372
- **简介**: 3D Gaussian Splat Editor

### AI 总结
**简介**: SuperSplat Editor 是一款免费开源的 3D 高斯泼溅编辑器，用于在浏览器中查看、编辑、优化和发布 3D 高斯泼溅数据。

**核心功能**:
- 支持 3D 高斯泼溅的查看、编辑、优化和发布
- 基于 Web 技术构建，无需下载安装，直接在浏览器中运行
- 提供多语言本地化支持，可添加和测试新语言翻译

**技术亮点**: 使用 TypeScript 开发，基于 Node.js 18+ 构建，支持本地开发环境的热重载功能。

---
## 5. [datawhalechina/easy-vibe](https://github.com/datawhalechina/easy-vibe)
- **语言**: JavaScript
- **Stars**: 9,956
- **简介**: 💻 vibe coding 2026 | Your first modern Coding course for beginners to master step by step.

### AI 总结
**简介**: Easy-Vibe 是一个面向零基础初学者的现代编程入门课程，旨在通过“会说话就能做应用”的理念，帮助用户一步步掌握编程和 AI 应用开发。

**核心功能**:
- 提供从零开始的学习地图，清晰引导用户避免“学了就忘”
- 包含逐步可视化教程，如同私教般详细讲解
- 提供沉浸式模拟编码环境，通过虚拟鼠标引导快速掌握 IDE 核心操作
- 以动画形式直观展示 AI 原理（如图像生成）和 RAG 数据流
- 支持多语言（中、英、日、西、法等），并配有交互式教程

**技术亮点**: 基于 JavaScript 构建，采用 Vercel 部署，集成交互式组件和动画演示，降低 AI 和编程学习门槛。

---
## 6. [decolua/9router](https://github.com/decolua/9router)
- **语言**: JavaScript
- **Stars**: 8,387
- **简介**: Unlimited FREE AI coding. Connect Claude Code, Codex, Cursor, Cline, Copilot, Antigravity to FREE Claude/GPT/Gemini via 40+ providers. Auto-fallback, RTK -40% tokens, never hit limits.

### AI 总结
**简介**: 9Router 是一个免费且无限的 AI 路由与 Token 节省工具，可将各类 AI 编码工具连接到 40 多个 AI 提供商和 100 多个模型。

**核心功能**:
- **RTK Token 节省器**: 自动压缩工具输出内容，每次请求可节省 20-40% 的 Token。
- **智能自动回退**: 按层级自动切换（订阅 → 廉价 → 免费），确保编码不中断。
- **多账户轮询**: 支持同一提供商下的多账户轮询，充分利用订阅配额。
- **通用兼容性**: 兼容 Claude Code、Codex、Cursor、Cline 等所有主流 AI 编码工具。

**技术亮点**:
- **Node.js** (npm 包) 与 **Next.js** 前端仪表盘
- 提供 **OpenAI 兼容 API** 端点，易于集成
- 支持 **格式转换** (OpenAI ↔ Claude)，实现跨模型无缝通信

---
## 7. [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman)
- **语言**: Rust
- **Stars**: 1,520
- **简介**: Your Personal AI super intelligence. Private, Simple and extremely powerful.

### AI 总结
**简介**: OpenHuman 是一个开源的个人 AI 超级智能助手，注重隐私、简洁和强大性能。

**核心功能**:
- **桌面化智能体**: 提供简洁的 UI 和桌面吉祥物，能说话、响应环境、加入 Google Meet 会议，并长期记忆用户行为。
- **118+ 第三方集成**: 一键 OAuth 连接 Gmail、Notion、GitHub、Slack 等工具，自动每 20 分钟拉取数据更新记忆树。
- **记忆树 + Obsidian 知识库**: 本地优先，将数据转化为 Markdown 片段并存入 SQLite，同时生成可浏览的 Obsidian 兼容笔记库。
- **开箱即用工具集**: 内置网页搜索、抓取、编程工具（文件系统、Git、Lint、测试、grep）、语音功能（STT/TTS、唇形同步、Google Meet 支持）和模型路由。
- **智能令牌压缩 (TokenJuice)**: 自动压缩工具调用、邮件、网页等数据，减少 80% 的 Token 消耗和延迟。

**技术亮点**: 使用 Rust 开发，支持本地 AI（Ollama）和云端模型路由，数据完全本地存储于 SQLite。

---
## 8. [millionco/react-doctor](https://github.com/millionco/react-doctor)
- **语言**: TypeScript
- **Stars**: 8,093
- **简介**: Your agent writes bad React. This catches it

### AI 总结
**简介**: 一个用于检测和捕获React代码中不良实践的静态分析工具。  
**核心功能**:  
- 自动检测React代码中的潜在问题（如性能隐患、反模式）  
- 提供可配置的规则集以适配不同项目规范  
**技术亮点**: 基于TypeScript开发，利用AST解析实现精准代码分析。

---
## 9. [Lordog/dive-into-llms](https://github.com/Lordog/dive-into-llms)
- **语言**: Jupyter Notebook
- **Stars**: 37,334
- **简介**: 《动手学大模型Dive into LLMs》系列编程实践教程

### AI 总结
**简介**: 由上海交通大学课程讲义拓展而来的大模型入门编程实践教程，提供免费、公益的动手学习资源。

**核心功能**:
- 提供从微调部署、提示学习到模型安全等10个主题的完整教程，含课件、实验手册和Jupyter脚本
- 覆盖大模型开发全流程，包括国产化适配方案（华为昇腾支持）
- 提供交互式Notebook环境，支持直接运行和实验

**技术亮点**: 基于Jupyter Notebook的实践教学，涵盖微调、提示工程、知识编辑、数学推理、模型水印、越狱攻击、隐写术、多模态模型、GUI Agent和智能体安全等技术方向

---
## 10. [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)
- **语言**: Python
- **Stars**: 162,907
- **简介**: Stable Diffusion web UI

### AI 总结
**简介**: Stable Diffusion web UI 是一个基于 Gradio 库实现的 Stable Diffusion 图形化界面工具，提供丰富的图像生成与编辑功能。

**核心功能**:
- 支持 txt2img 和 img2img 两种基础模式
- 一键安装与运行脚本（需预先安装 Python 和 Git）
- 图像外补全（Outpainting）和内补全（Inpainting）
- 彩色草图（Color Sketch）与提示矩阵（Prompt Matrix）
- 稳定扩散放大（Stable Diffusion Upscale）
- 注意力机制：支持通过 `((text))` 或 `(text:权重)` 语法调整模型对特定文本的关注度
- 循环处理（Loopback）与 X/Y/Z 参数三维绘图
- 文本反转（Textual Inversion）嵌入训练（支持 8GB 显存）
- 额外工具标签页：集成 GFPGAN、CodeFormer、RealESRGAN、ESRGAN、SwinIR、LDSR 等图像修复与放大模型
- 采样方法选择与高级噪声设置（如 eta 值调整）
- 实时中断生成、4GB 显存支持、批次种子固定
- 生成参数保存（PNG/EXIF）与拖拽恢复
- 设置页面与自定义脚本扩展
- 负向提示（Negative Prompt）与风格保存
- 变体生成、种子尺寸调整、CLIP 提示反推
- 提示编辑（Prompt Editing）、批处理、高分辨率修复（Highres Fix）
- 实时检查点加载与合并
- 可组合扩散（Composable Diffusion）与无令牌限制
- DeepDanbooru 集成与 xformers 加速
- 训练标签页：超网络（Hypernetworks）和嵌入（Embeddings）训练

**技术亮点**: 基于 Gradio 构建 Web 界面，支持多种神经网络模型（GFPGAN、CodeFormer、RealESRGAN 等）作为扩展工具，通过 `--xformers` 参数实现显著性能提升，支持自定义脚本与社区扩展，提供灵活的注意力权重调整和参数可视化调试功能。

---
