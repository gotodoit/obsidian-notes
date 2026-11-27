---
tags:
  - github-trending
  - daily
date: 2026-11-27
created: 2026-11-27T01:55:43.397Z
---

# 2026-11-27 GitHub Trending Top 10

## 1. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- **语言**: Python
- **Stars**: 24,669
- **简介**: A Claude Code skill bundle for bug hunting and external red-team work - 85 skills, 16 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.

### AI 总结
**简介**: Claude-BugHunter 是一个面向漏洞赏金挖掘与外部红队工作的 Claude Code 技能包，内置 85 个技能、16 个斜杠命令，以及覆盖 24 类核心漏洞的 681 条公开报告模式。

**核心功能**:
- **方法论与红队思维**：提供五阶段非线性工作流、批判性思维框架和红队操作纪律（`bb-methodology`、`redteam-mindset`）。
- **Web 应用漏洞挖掘**：58 个 `hunt-*` 技能，基于 681 份已披露的 HackerOne 报告整理，包含检测模式、Payload、绕过表和攻击链模板。
- **企业边界攻击**：覆盖 M365/Entra、Okta、vCenter、SSL-VPN、SharePoint、云 IAM 等平台的 2024–2026 CVE 链与凭据后提权。
- **交付与合规**：`triage-validation`、报告生成与 `evidence-hygiene`，包含 7-Question Gate、VRT 严重性评级、OOS 反驳、PII 脱敏和红队交付物。
- **自动触发**：用自然语言描述测试目标即可自动加载对应技能，无需按名称调用。

**技术亮点**: 以 Python 实现，支持 Claude Code 插件市场安装与脚本复制安装两种方式；集成 Burp MCP 与 HackerOne MCP（可选 API 凭据）；提供终端原生 `cbh` CLI（可通过 pipx 安装）和 `hunt` 项目脚手架；已在授权红队、赏金项目及 DVWA、OWASP Juice Shop 等公开训练平台验证。

---
## 2. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 327,528
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，通过可组合的技能与初始指令让智能体自动遵循规范化开发流程。

**核心功能**:
- 启动即先澄清需求：智能体不会直接写代码，而是先引导对话梳理真实目标，并分块展示规格供人审阅
- 设计确认后生成实现计划，强调红/绿 TDD、YAGNI 与 DRY，计划细到可让经验不足的初级工程师照做
- 采用子智能体驱动开发（subagent-driven development），逐个任务执行、检查与评审，可长时间自主推进而不偏离计划
- 技能自动触发，无需额外操作，智能体天然具备该能力
- 支持多平台安装：Claude Code、Codex（App/CLI）、Cursor、Gemini CLI、GitHub Copilot CLI、Devin CLI、Factory Droid、OpenCode、Qwen Code 等十余种工具

**技术亮点**: 以 Shell 为主实现；采用可组合技能（composable skills）架构，按不同 harness 分别安装；提供官方与自建插件市场两种分发渠道；内置可视化伴随遥测（visual companion telemetry）与商业支持选项。

---
## 3. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 66,400
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: HKUDS/CLI-Anything 是一个旨在让所有软件都能被 AI Agent 原生调用的开源项目，通过生成命令行接口（CLI）在 AI Agent 与各类软件之间搭建桥梁。

**核心功能**:
- **一键生成 CLI**：一条命令即可让任意软件对 Pi、OpenClaw、nanobot、Cursor、Claude Code 等 AI Agent 可用。
- **CLI-Hub 社区中心**：通过 `pip install cli-anything-hub` 安装后，可用 `cli-hub install <name>` 浏览、安装和管理社区构建的 CLI，并支持提交 PR 贡献自己的 CLI。
- **预览与轨迹循环**：AI Agent 可借助生成的 CLI 配合预览、实时预览和轨迹循环，产出真实工件，如 CAD 建模、3D 场景、图表、游戏内容、字幕等。
- **社区共建与需求征集**：支持报名成为贡献者构建新的 CLI harness，也可提交 wishlist 请求支持特定软件或服务。

**技术亮点**: 基于 Python（≥3.10）开发，使用 Click（≥8.0）构建命令行界面，采用 pytest 进行单元与端到端测试（2,461 项测试通过），输出支持 JSON 与人类可读两种格式，并遵循 Apache 2.0 开源协议。

---
## 4. [jingyaogong/minimind](https://github.com/jingyaogong/minimind)
- **语言**: Python
- **Stars**: 71,677
- **简介**: 🧠 两小时从 0 训出你的 64M 大模型。Train your own 64M LLM from scratch in 2 hours.

### AI 总结
**简介**: MiniMind 是一个从零开始、仅需约 3 元成本和 2 小时即可训练出 64M 超小语言模型的开源项目，同时是一套覆盖大模型全流程的入门教程。

**核心功能**:
- 提供完整的 MiniMind-LLM 结构代码（Dense + MoE，对齐 Qwen3 生态）及 Tokenizer 训练代码
- 覆盖 Pretrain、SFT、LoRA、RLHF-DPO、RLAIF（PPO / GRPO / CISPO）、Tool Use、Agentic RL、自适应思考与模型蒸馏等完整训练链路
- 提供全阶段开源数据（收集、蒸馏、清洗、去重后的高质量数据集）
- 支持第三方评测集（C-Eval、C-MMLU、OpenBookQA 等）及 YaRN 长文本外推
- 提供兼容 OpenAI API 协议的极简服务端与基于 Streamlit 的聊天 WebUI，支持思考展示、工具选择与多轮 Tool Call

**技术亮点**: 所有核心算法与关键模块均使用 PyTorch 原生从零实现，不依赖 transformers/trl/peft 等高层封装；支持单卡与多卡（DDP、DeepSpeed）训练，兼容 llama.cpp、vllm、ollama 等推理引擎及 Llama-Factory 训练框架；主线最小版本体积约为 GPT-3 的 1/2700，普通个人 GPU 即可复现。

---
## 5. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 19,796
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，提供面向主流开发工具、框架和 SaaS 产品的插件规范与官方插件集合，每个插件以独立目录形式组织，并包含各自的 `.cursor-plugin/plugin.json` 清单文件。

**核心功能**:
- **开发工具类插件**：涵盖教学辅助（Teaching）、持续学习记忆更新（Continual Learning）、团队工作流（Cursor Team Kit）、深度分支审查（Thermos）、插件脚手架生成（Create Plugin）、迭代式 AI 循环（Ralph Loop）、仓库兼容性扫描（Agent Compatibility）、CLI 设计模式（CLI for Agents）、PR 差异画布（PR Review Canvas）、文档画布（Docs Canvas）、TypeScript SDK 应用构建（Cursor SDK）、Origin API 技能（Origin Apps）、并行云代理任务编排（Orchestrate）、严格代理工作流（pstack / dyl-stack）、决策咨询（Advisor）以及 Grok 语音集成（Grok Voice）等。
- **生产力类插件**：集成 Gmail、Google Drive、Google Calendar、Google Docs、Google Sheets、Google Slides，支持邮件管理、文件读写共享、日程安排和文档编辑。
- **集成类插件**：对接 Google Ads、Google Analytics、Google Search Console、Gong、Salesforce 等第三方服务，支持广告投放分析、GA4 报告、搜索表现查询、销售洞察获取等操作。

**技术亮点**: 采用 TypeScript 作为主要开发语言；插件体系基于统一的 `.cursor-plugin/plugin.json` 清单规范，结构标准化、易于扩展；覆盖 AI 代理编排、并行任务分发、模型咨询、语音交互等前沿 Agent 工作流场景。

---
## 6. [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)
- **语言**: TypeScript
- **Stars**: 210,982
- **简介**: Knowledge infrastructure to make your agents smarter. Search, scrape and access 550+ data providers through one API.

### AI 总结
**简介**: Firecrawl 是一个知识基础设施项目，通过统一 API 为 AI Agent 提供网页搜索、抓取及 550+ 数据源访问能力，帮助 Agent 变得更智能。

**核心功能**:
- **Firecrawl Local**：以单一二进制在本地运行，将网页转换为干净的 Markdown，支持 scrape、crawl、map 等操作，并可作为 MCP 服务器接入 AI Agent
- **Firecrawl Cloud**：托管云服务，在本地能力基础上提供规模化运行、搜索及 Alexandria 的 550+ 数据源
- **自托管部署**：可从 `apps/api` 部署完整服务器，自带队列、Worker 和数据库
- **多语言 SDK**：提供与三种使用方式兼容的 SDK，代码可在本地与云端无缝切换
- **AI Agent 集成**：`init` 命令自动为 Claude Code、Cursor、Windsurf、Gemini CLI、Codex 等配置 MCP 服务器

**技术亮点**: 项目主要使用 TypeScript 开发；Firecrawl Local 基于 Rust 构建并通过 crates.io 分发；本地模式无需数据库、队列或容器，复用本机 Chrome/Chromium 渲染 JavaScript 页面并本地解析 PDF 与 Office 文档；`serve` 命令在 3002 端口提供 Firecrawl v2 API，兼容现有 SDK。

---
## 7. [nginx/nginx](https://github.com/nginx/nginx)
- **语言**: C
- **Stars**: 33,532
- **简介**: The official NGINX Open Source repository.

### AI 总结
**简介**: NGINX 官方开源仓库，是一款用 C 语言编写的高性能 Web 服务器、反向代理、负载均衡器、API 网关和内容缓存软件。

**核心功能**:
- Web 服务器：处理 HTTP/HTTPS 请求，提供静态内容服务
- 反向代理与负载均衡：将请求分发到后端服务器集群
- API 网关：统一管理和路由 API 请求
- 内容缓存：缓存响应内容以提升性能
- 模块化架构：通过静态或动态模块扩展功能
- TLS/SSL 支持：安装证书并启用加密传输
- 速率限制：控制请求频率，保护后端服务

**技术亮点**:
- 使用 C 语言开发，性能高、资源占用低
- 采用模块化设计，支持静态模块（编译时集成）和动态模块（运行时加载）
- 基于配置文件驱动，支持灵活的指令配置
- 采用 BSD 2-Clause 许可证，免费开源
- 由 F5, Inc 提供企业版发行、商业支持与培训
- 项目状态活跃，持续维护和开发

---
## 8. [openvinotoolkit/openvino](https://github.com/openvinotoolkit/openvino)
- **语言**: C++
- **Stars**: 12,829
- **简介**: OpenVINO™ is an open source toolkit for optimizing and deploying AI inference

### AI 总结
**简介**: OpenVINO™ 是 Intel 开源的一款用于优化和部署深度学习模型推理的工具包，主要使用 C++ 开发。

**核心功能**:
- **推理优化**：提升计算机视觉、语音识别、生成式 AI、自然语言处理（含大/小语言模型）等任务的深度学习性能。
- **灵活的模型支持**：支持 PyTorch、TensorFlow、ONNX、Keras、PaddlePaddle、JAX/Flax 等框架训练的模型；可通过 Optimum Intel 直接集成 Hugging Face Hub 上的 transformers 和 diffusers 模型，无需原始框架即可转换部署。
- **广泛的平台兼容性**：支持在 CPU（x86、ARM）、GPU（Intel 集成与独立显卡）及 AI 加速器（Intel NPU）上推理，覆盖从边缘到云端的多种平台。

**技术亮点**:
- 提供 Python（PyPI）、Node.js（NPM）、Conda、Homebrew 等多种分发与安装方式（如 `pip install -U openvino`）。
- 拥有丰富的教程与示例生态，包括 OpenVINO Notebooks，涵盖 LLM 聊天机器人、YOLOv11 优化、文生图、LLaVa 多模态助手、Whisper 语音识别等场景。
- 提供 Python 与 C++ 示例，以及面向生成式 AI 的配套项目 openvino.genai。

---
## 9. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 73,879
- **简介**: Editorial diagram design for Claude Code, Codex, GitHub Copilot, Cursor, Factory Droid, Qoder, and Pi. 52 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个面向 AI 编程代理的图表绘制技能，用自然语言指令生成自包含的 HTML + SVG 编辑级图表，支持 52 种图表类型。

**核心功能**:
- 通过自然语言提示让代理自动选择图表类型并生成单个 `.html` 文件，双击即可打开
- 覆盖 52 种图表类型（架构图、象限图、时序图等）
- 品牌定制：可抓取指定网站的配色和字体，使图表风格与品牌一致
- 支持从 draw.io、Mermaid、Excalidraw、PlantUML 导入
- 支持导出为 PNG / SVG
- 兼容多种宿主：Claude Code、Codex、GitHub Copilot、Cursor、Qoder、Gemini CLI、Cline、Windsurf、Amp 等

**技术亮点**:
- 输出为单个自包含 HTML + SVG 文件，无外部依赖
- 设计风格强调"编辑级"审美：无阴影、拒绝 Mermaid 式粗糙渲染
- 通过 `npx skills add` 一键安装，Claude Code 支持插件市场安装与自动更新
- 采用 MIT 开源协议

---
## 10. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 75,785
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个由 AI Agent 驱动的搜索技能，可并行检索 Reddit、X、YouTube、HN、Polymarket 等多个平台，并按真实用户互动（点赞、投票、真金白银的赔率）打分后合成一份有据可依的摘要。

**核心功能**:
- 多源并行搜索：同时覆盖 Reddit、X/Twitter、YouTube、Hacker News、Polymarket、GitHub、arXiv、TikTok、Techmeme 等平台，以及专利和招聘页面
- 真实互动排序：以 Reddit 投票、X 点赞、YouTube 转录、TikTok 互动、Polymarket 赔率等真人行为作为排序依据，而非编辑推荐
- AI 合成摘要：由 AI Agent 作为裁判，将各平台结果综合成一份简报（如用于会前背调、商业调研、出行攻略等场景）
- 零配置开箱即用：Reddit、HN、Polymarket、GitHub 无需配置即可使用；运行一次后通过向导 30 秒内可解锁 X、YouTube、TikTok、arXiv 等更多来源
- 多宿主安装：支持 Claude Code 插件市场安装，也支持 Codex、Cursor、Copilot、Gemini CLI 等 50+ Agent Skills 宿主（通过 `npx skills add`）

**技术亮点**: 采用 Python 实现，核心为 v4 版流水线（pipeline），运行时技能规范以 `skills/last30days/SKILL.md` 为唯一事实来源；通过“自带密钥 + 浏览器会话”的方式打通各平台封闭 API，让单个 Agent 跨平台聚合检索并交叉评分；提供多语言 README（含简体中文）及 GitHub Actions 校验流程。

---
