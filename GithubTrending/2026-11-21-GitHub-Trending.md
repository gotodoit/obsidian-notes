---
tags:
  - github-trending
  - daily
date: 2026-11-21
created: 2026-11-21T01:55:43.720Z
---

# 2026-11-21 GitHub Trending Top 10

## 1. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- **语言**: Python
- **Stars**: 14,340
- **简介**: A Claude Code skill bundle for bug hunting and external red-team work - 82 skills, 15 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.

### AI 总结
**简介**: Claude-BugHunter 是一个面向漏洞挖掘和外部红队工作的 Claude Code 技能包，内置 83 个技能、15 个斜杠命令和 681 条已披露报告模式，覆盖 24 类核心漏洞。

**核心功能**:
- **方法论与思维框架**：通过 `bb-methodology` 和 `redteam-mindset` 提供五阶段非线性工作流、批判性思维框架和红队操作纪律
- **Web 应用漏洞挖掘**：58 个 `hunt-*` 技能，源自 681 份 HackerOne 公开报告，包含按漏洞类别的检测模式、payload、绕过表和攻击链模板
- **企业边界攻击**：覆盖 M365/Entra、Okta、vCenter、SSL-VPN、SharePoint、云 IAM 等平台的 2024–2026 CVE 攻击链及凭据后提权
- **分诊与交付**：`triage-validation` 配合报告与证据卫生技能，提供七问门禁、VRT 感知的严重性评级、OOS 反驳、PII 脱敏和红队交付物
- **自动加载**：用自然语言描述测试目标即可自动匹配并加载对应技能，无需按名称调用
- **参与目录脚手架与 Burp MCP 集成**：辅助组织测试项目并接入 Burp 工具链

**技术亮点**: 基于 Claude Code 技能系统构建，支持插件市场安装（命名空间隔离、版本更新）和脚本复制安装两种方式；另提供独立的 `cbh` CLI（可通过 pipx 安装）和 `hunt` 参与目录脚手架；可选接入 HackerOne MCP 读取私有项目与个人报告，并已在授权红队、漏洞挖掘及 DVWA、OWASP Juice Shop 等公开训练平台验证。

---
## 2. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 322,862
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码 Agent 的完整软件开发方法论，由可组合的技能（skills）和初始指令构成，让 Agent 自动遵循规范化的开发流程。

**核心功能**:
- **需求澄清**：Agent 不会直接写代码，而是先退一步询问用户的真实目标，从对话中提炼出规格说明，并以易于阅读的小块形式呈现给用户确认。
- **实现计划**：设计确认后，生成足够清晰、可供初级工程师执行的实现计划，强调严格的红/绿 TDD、YAGNI 和 DRY 原则。
- **子 Agent 驱动开发**：用户确认后启动 subagent-driven-development 流程，由多个 Agent 逐项完成工程任务，并检查、审查彼此的工作，可自主连续工作数小时而不偏离计划。
- **自动触发**：技能会自动触发，用户无需额外操作即可获得完整方法论支持。
- **多平台安装**：支持 Claude Code、Antigravity、Codex App/CLI、Cursor、Devin CLI、Factory Droid、Gemini CLI、GitHub Copilot CLI、OpenCode、Qwen Code 等多种编码工具。

**技术亮点**: 以 Shell 为主要语言实现；采用可组合技能架构，通过初始指令确保 Agent 自动加载并使用技能；内置面向企业的商业支持渠道。

---
## 3. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 61,417
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: CLI-Anything 旨在让所有软件都能被 AI Agent 原生调用，通过生成命令行接口（CLI）在 AI Agent 与各类软件之间搭建桥梁。

**核心功能**:
- 一键为任意软件生成 Agent 可用的 CLI，兼容 Pi、OpenClaw、nanobot、Cursor、Claude Code 等 Agent 工具
- 提供 CLI-Hub 社区中心，支持浏览、安装和管理社区构建的 CLI（`pip install cli-anything-hub` 后 `cli-hub install <name>`）
- 支持 AI Agent 通过生成的 CLI 配合预览、实时预览和轨迹循环，产出 CAD 构建、3D 场景、图表、游戏玩法、字幕等真实产物
- 开放社区贡献与 CLI 需求请求机制，支持用户提交新 CLI 构建或功能愿望清单

**技术亮点**: 基于 Python（≥3.10）开发，使用 Click（≥8.0）构建命令行界面，采用 pytest 进行单元与端到端测试（2,461 项测试通过），输出支持 JSON 与人类可读两种格式；采用 Apache 2.0 开源协议，并配有技术报告（arXiv:2606.03854）。

---
## 4. [jingyaogong/minimind](https://github.com/jingyaogong/minimind)
- **语言**: Python
- **Stars**: 67,702
- **简介**: 🧠 两小时从 0 训出你的 64M 大模型。Train your own 64M LLM from scratch in 2 hours.

### AI 总结
**简介**: MiniMind 是一个从零开始、仅需约 3 元成本和 2 小时训练即可复现 64M 超小语言模型的开源项目，同时是一套面向 LLM 入门与实践的完整教程。

**核心功能**:
- 提供 Dense 与 MoE 两种 MiniMind-LLM 结构代码，主线对齐 Qwen3 / Qwen3-MoE 生态
- 覆盖 Pretrain、SFT、LoRA、RLHF-DPO、RLAIF（PPO / GRPO / CISPO）、Tool Use、Agentic RL、自适应思考与模型蒸馏等完整训练链路
- 提供 Tokenizer 训练代码及全阶段高质量开源数据集（含收集、蒸馏、清洗与去重）
- 提供兼容 OpenAI API 协议的极简服务端与基于 Streamlit 的聊天 WebUI，支持 `reasoning_content`、`tool_calls`、`open_thinking`
- 支持 C-Eval、C-MMLU、OpenBookQA 等评测，并通过 YaRN 实现 RoPE 长文本外推
- 拓展视觉模型 MiniMind-V、多模态 Omni 模型 MiniMind-O、扩散语言模型与线性注意力模型

**技术亮点**:
- 核心算法与关键模块均使用 PyTorch 原生从 0 实现，不依赖第三方高层抽象接口
- 兼容 `transformers`、`trl`、`peft` 等主流框架，以及 `llama.cpp`、`vllm`、`ollama`、`Llama-Factory` 等推理/训练引擎
- 支持单机单卡与单机多卡（DDP、DeepSpeed）训练，支持 wandb / swanlab 可视化与动态启停
- 主线最小版本体积约为 GPT-3 的 1/2700，普通个人 GPU 即可完成训练与复现，采用 Apache 2.0 协议开源

---
## 5. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 17,857
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，为流行开发工具、框架和 SaaS 产品提供标准化插件规范与官方插件集合，每个插件以独立目录形式存在并包含自己的 `.cursor-plugin/plugin.json` 清单。

**核心功能**:
- 提供插件规范与脚手架工具（`create-plugin`），支持新插件的创建与校验
- 面向开发流程的插件：团队协作套件（`cursor-team-kit`）、深度代码审计与分支审查（`thermos`）、PR 差异画布（`pr-review-canvas`）、文档画布（`docs-canvas`）
- 面向 AI 代理工作流的插件：并行任务编排（`orchestrate`）、迭代自循环（`ralph-loop`）、代理兼容性扫描（`agent-compatibility`）、CLI 设计模式（`cli-for-agent`）、咨询更强模型（`advisor`）
- 生产力集成插件：Gmail、Google Drive、Google Calendar、Google Docs、Google Sheets、Google Slides 等
- 第三方服务集成插件：Google Ads、Google Analytics、Google Search Console、Gong、Salesforce 等
- 开发者工具与 SDK：Cursor TypeScript SDK、Origin Apps API 构建技能、Grok 语音集成

**技术亮点**: 采用 TypeScript 开发；插件采用标准化清单（manifest）架构，每个插件为仓库根目录下的独立目录，便于分发与市场集成；涵盖多代理编排、并行子代理、结构化交接等先进 AI 工作流模式。

---
## 6. [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)
- **语言**: TypeScript
- **Stars**: 205,311
- **简介**: Knowledge infrastructure to make your agents smarter. Search, scrape and access 550+ data providers through one API.

### AI 总结
**简介**: Firecrawl 是一款面向 AI Agent 的知识基础设施，可将网站内容转换为干净的 Markdown，并通过统一 API 搜索、抓取和访问 550+ 数据源。

**核心功能**:
- **网页抓取与爬取**：将网页转换为 Markdown，支持整站爬取、URL 映射、PDF 与 Office 文档解析
- **MCP 服务器集成**：一键将 Firecrawl Local 注册为 MCP 服务器，接入 Claude Code、Cursor、Windsurf、Gemini CLI 等 AI 工具
- **本地 API 服务**：在 localhost:3002 提供 Firecrawl v2 API，兼容现有 SDK，无需 API Key
- **三种使用方式**：Firecrawl Local（本地单二进制运行）、Firecrawl Cloud（托管服务，含搜索与 Alexandria 数据源）、自托管（完整服务端部署）

**技术亮点**: 项目以 TypeScript 为主，Firecrawl Local 基于 Rust 构建并通过 crates.io 分发；本地抓取无需数据库、队列或容器，借助本机 Chrome/Chromium 渲染 JavaScript 页面；提供多语言 SDK，支持 Docker 部署，服务端具备队列、Worker 与数据库的完整架构。

---
## 7. [nginx/nginx](https://github.com/nginx/nginx)
- **语言**: C
- **Stars**: 32,579
- **简介**: The official NGINX Open Source repository.

### AI 总结
**简介**: NGINX 官方开源仓库，用 C 语言编写，是全球最流行的 Web 服务器、高性能负载均衡器、反向代理、API 网关和内容缓存软件。

**核心功能**:
- Web 服务器：提供静态内容服务与请求处理
- 负载均衡与反向代理：支持高并发流量分发
- API 网关：统一管理后端服务入口
- 内容缓存：提升响应速度并降低后端压力
- 模块化扩展：通过静态或动态模块扩展功能（可用 `nginx -V` 查看已编译的静态模块）
- TLS 加密、限流等开箱即用的配置能力

**技术亮点**: 采用 C 语言开发，模块化架构（静态/动态模块）；提供 Stable 与 Mainline 双版本二进制包，覆盖 Linux、FreeBSD、Windows 等主流平台；采用简化的 2-clause BSD 类许可证；支持从源码编译定制，企业级发行版与商业支持由 F5 提供。

---
## 8. [openvinotoolkit/openvino](https://github.com/openvinotoolkit/openvino)
- **语言**: C++
- **Stars**: 11,795
- **简介**: OpenVINO™ is an open source toolkit for optimizing and deploying AI inference

### AI 总结
**简介**: OpenVINO™ 是 Intel 开源的一款用于优化和部署深度学习模型推理的工具套件，主要使用 C++ 开发。

**核心功能**:
- **推理优化**：提升计算机视觉、语音识别、生成式 AI、自然语言处理（含大/小语言模型）等任务的深度学习性能。
- **灵活的模型支持**：兼容 PyTorch、TensorFlow、ONNX、Keras、PaddlePaddle、JAX/Flax 等主流框架训练的模型，并可通过 Optimum Intel 直接集成 Hugging Face Hub 上的 transformers 和 diffusers 模型，无需原始框架即可转换与部署。
- **广泛的平台兼容性**：降低资源需求，支持从边缘到云端的部署，可在 CPU（x86、ARM）、GPU（Intel 集成与独立显卡）及 AI 加速器（Intel NPU）上推理。
- **丰富的教程与示例**：提供 OpenVINO Notebooks，涵盖 LLM 聊天机器人、YOLOv11 优化、文生图、LLaVa 多模态助手、Whisper 语音识别等实战案例。

**技术亮点**: 采用 C++ 实现，提供 Python、Node.js 等多语言发行包（PyPI、NPM、Anaconda、Homebrew），支持跨框架模型转换与多硬件后端推理，并拥有活跃的社区生态与完善的文档体系。

---
## 9. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 69,302
- **简介**: Editorial diagram design for Claude Code, Codex, GitHub Copilot, Cursor, Factory Droid, Qoder, and Pi. 45 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个面向 AI 编程代理的图表设计技能，让代理用纯文本指令生成自包含 HTML + SVG 的品牌化编辑风格图表。

**核心功能**:
- 支持 51 种图表类型（架构图、象限图、时序图等），由代理自动选择类型并说明绘制计划
- 输出单个自包含 `.html` 文件，双击即可打开，无需外部依赖
- 支持品牌定制：可通过 onboarding 抓取指定网站的配色与字体，使后续图表风格统一
- 支持从 draw.io、Mermaid、Excalidraw、PlantUML 导入，并可导出 PNG / SVG
- 兼容 Cursor、Claude Code、Codex、GitHub Copilot、Qoder、Gemini CLI、Cline、Windsurf 等多种 Agent Skills 宿主

**技术亮点**: 基于 HTML + SVG 渲染，无阴影、强调编辑排版质感（明确拒绝 Mermaid 式粗糙图表）；以 Agent Skill 形式分发，通过 `npx skills add` 或 Claude Code 插件市场安装，支持多宿主根目录软链接共享同一份技能副本，MIT 许可。

---
## 10. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 71,465
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个由 AI agent 驱动的跨平台搜索引擎技能，能在 Reddit、X、YouTube、HN、Polymarket 等平台并行检索任意话题，并综合生成有据可依的摘要。

**核心功能**:
- **多平台并行搜索**：同时检索 Reddit、X/Twitter、YouTube、Hacker News、Polymarket、TikTok、arXiv、Techmeme、GitHub 等多个平台，突破单一 AI 无法访问所有平台的信息孤岛。
- **按真实互动度评分**：以 Reddit 点赞、X 喜欢、YouTube 转录、TikTok 互动、Polymarket 真金白银下注等真实用户参与度作为排序依据，而非编辑推荐。
- **AI 综合摘要**：由 AI agent 担任评审，将多源信息融合成一份有依据的简报，适用于会议前调研人物、销售前了解企业近况等场景。
- **零配置开箱即用**：Reddit、HN、Polymarket、GitHub 无需配置即可使用；运行一次后可通过向导在 30 秒内解锁 X、YouTube、TikTok、arXiv 等更多来源。
- **多宿主兼容**：支持 Claude Code（插件市场自动更新）以及 Codex、Cursor、Copilot、Gemini CLI 等 50+ Agent Skills 宿主，可通过 `npx skills add` 全局或按项目安装。

**技术亮点**: 基于 Python 实现；采用"自带密钥/浏览器会话"（BYOK）模式桥接各平台独立 API 与鉴权；通过 agent judge 机制对多源结果交叉评分与综合；遵循 Agent Skills 规范（`skills/last30days/SKILL.md` 为运行时规格源）。

---
