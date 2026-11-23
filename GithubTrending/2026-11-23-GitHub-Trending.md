---
tags:
  - github-trending
  - daily
date: 2026-11-23
created: 2026-11-23T01:55:44.840Z
---

# 2026-11-23 GitHub Trending Top 10

## 1. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- **语言**: Python
- **Stars**: 17,902
- **简介**: A Claude Code skill bundle for bug hunting and external red-team work - 82 skills, 15 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.

### AI 总结
**简介**: Claude-BugHunter 是一个面向 Claude Code 的即插即用技能包，将 Claude 从普通聊天机器人转变为资深漏洞挖掘研究员或红队操作员，用于 Web 应用漏洞挖掘和企业外部红队工作。

**核心功能**:
- **思维框架层**：内置 `bb-methodology` 和 `redteam-mindset`，提供五阶段非线性工作流、批判性思维框架和红队操作纪律。
- **Web 应用挖掘**：58 个 `hunt-*` 技能，基于 681 份公开披露的 HackerOne 报告整理，涵盖各类漏洞的检测模式、Payload、绕过表和攻击链模板。
- **外围攻击面**：针对 M365/Entra、Okta、vCenter、SSL-VPN 设备、SharePoint、云 IAM 等企业平台，提供 2024–2026 年 CVE 攻击链及凭据后提权路径。
- **交付与合规**：`triage-validation`、报告生成和 `evidence-hygiene`，包含 7 问门禁、VRT 感知的严重性评级、OOS 反驳、PII 脱敏和红队交付物。
- **自动触发**：用自然语言描述测试目标即可自动加载对应技能，无需按名称调用。
- **集成支持**：支持 Burp MCP 集成、HackerOne MCP（可选）、`cbh` CLI 和 `hunt` 项目脚手架。

**技术亮点**: 采用四层叠加架构（思维 → Web 挖掘 → 外围攻击 → 交付），共 83 个技能和 15 个斜杠命令，覆盖 24 类核心漏洞；支持插件市场安装与脚本复制安装两种方式，插件模式下技能以 `claude-bughunter:` 命名空间加载并随版本更新；已在授权红队、漏洞挖掘项目及 DVWA、OWASP Juice Shop、Hacker101 等公开训练平台验证。

---
## 2. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 324,199
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，基于可组合的技能（skills）和初始指令构建，让智能体自动遵循规范化的开发流程。

**核心功能**:
- **需求澄清与规格设计**：智能体不会直接写代码，而是先退一步询问真实意图，从对话中提炼规格，并以易于阅读的分块形式呈现给用户确认。
- **可执行的实施计划**：设计确认后生成清晰到“初级工程师也能照做”的计划，强调真正的红/绿 TDD、YAGNI 和 DRY 原则。
- **子智能体驱动开发**：用户确认后启动 subagent-driven-development 流程，由多个智能体逐个完成工程任务、检查并评审彼此工作，可自主连续工作数小时而不偏离计划。
- **技能自动触发**：技能会自动激活，用户无需额外操作，编码智能体即自动具备 Superpowers 能力。
- **多平台支持**：提供 Claude Code、Antigravity、Codex、Cursor、Devin CLI、Factory Droid、Gemini CLI、GitHub Copilot CLI、OpenCode、Qwen Code 等多种智能体环境的安装方式。

**技术亮点**: 以 Shell 为主要语言实现；采用可组合技能架构，通过 `using-superpowers` 等技能描述在对话开始时引导模型加载；支持插件市场与仓库直装两种分发方式；提供商业支持服务。

---
## 3. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 62,815
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: HKUDS 推出的 CLI-Anything 项目，旨在通过生成命令行接口（CLI）让所有软件都能被 AI Agent 原生调用，弥合 AI Agent 与现有软件生态之间的鸿沟。

**核心功能**:
- **一键生成 CLI**：为任意软件生成可被 Pi、OpenClaw、nanobot、Cursor、Claude Code 等 AI Agent 调用的命令行接口。
- **CLI-Hub 社区仓库**：提供 `cli-anything-hub` 包，支持浏览、安装和管理社区构建的 CLI（`pip install cli-anything-hub` 后执行 `cli-hub install <name>`）。
- **真实场景演示**：展示 AI Agent 借助生成的 CLI 配合预览与轨迹循环，产出 CAD 构建、3D 场景、图表、游戏玩法、字幕等真实成果。
- **社区共建机制**：支持贡献者提交新 CLI、提交软件愿望清单（Wishlist），经审核合并后成为社区贡献者。

**技术亮点**: 基于 Python（≥3.10）开发，使用 Click（≥8.0）构建命令行，采用 pytest 进行单元与端到端测试（2,461 项测试通过），输出支持 JSON 与人类可读双格式；采用 Apache 2.0 开源协议，并有配套 arXiv 技术报告。

---
## 4. [jingyaogong/minimind](https://github.com/jingyaogong/minimind)
- **语言**: Python
- **Stars**: 68,709
- **简介**: 🧠 两小时从 0 训出你的 64M 大模型。Train your own 64M LLM from scratch in 2 hours.

### AI 总结
**简介**: MiniMind 是一个从零开始训练超小语言模型（约 64M 参数）的开源项目，仅需约 2 小时和 3 元 GPU 成本即可完成训练，同时提供完整的大模型训练链路与教程。

**核心功能**:
- 提供完整的 MiniMind-LLM 结构代码（Dense + MoE），主线结构对齐 Qwen3 / Qwen3-MoE 生态
- 覆盖 Pretrain、SFT、LoRA、RLHF-DPO、RLAIF（PPO / GRPO / CISPO）、Tool Use、Agentic RL、自适应思考与模型蒸馏等完整训练流程
- 提供 Tokenizer 与分词器训练代码，支持 `<tool_call>`、`<tool_response>`、`<think>` 等模板标记
- 提供全阶段开源数据（收集、蒸馏、清洗、去重后的高质量数据集）
- 提供兼容 OpenAI API 协议的极简服务端与基于 Streamlit 的聊天 WebUI
- 拓展视觉模型 MiniMind-V、多模态 Omni 模型 MiniMind-O、扩散语言模型 MiniMind-dLM、线性模型 MiniMind-Linear

**技术亮点**:
- 所有核心算法与模块均使用 PyTorch 原生从零实现，不依赖第三方高层抽象接口
- 兼容 transformers、trl、peft 等主流框架，以及 llama.cpp、vllm、ollama 等推理引擎和 Llama-Factory 训练框架
- 支持单机单卡与单机多卡（DDP、DeepSpeed）训练，支持 wandb / swanlab 可视化与动态启停训练
- 支持 C-Eval、C-MMLU、OpenBookQA 等第三方测评集评测，并支持 YaRN 实现 RoPE 长文本外推
- 采用 Apache 2.0 协议开源，完全免费

---
## 5. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 18,470
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，汇集面向主流开发工具、框架和 SaaS 产品的插件规范与官方插件，每个插件为独立目录并自带 `.cursor-plugin/plugin.json` 清单。

**核心功能**:
- **开发工具插件**：涵盖教学技能映射（Teaching）、增量记忆更新（Continual Learning）、团队 CI/代码审查工作流（Cursor Team Kit）、深度安全与代码质量审计（Thermos）、插件脚手架（Create Plugin）、迭代式 AI 循环（Ralph Loop）、仓库兼容性扫描（Agent Compatibility）、面向 Agent 的 CLI 设计模式（CLI for Agents）、PR 差异画布（PR Review Canvas）、文档画布（Docs Canvas）等。
- **任务编排与协作**：Orchestrate 将大型任务拆分到并行云端 Agent（规划者、执行者、验证者），Advisor 在关键决策前咨询更强模型，pstack/dyl-stack 提供可并行的严谨 Agent 工作流。
- **SDK 与 API 集成**：Cursor SDK 支持用 TypeScript 构建应用与自动化；Origin Apps 提供基于 Cursor Origin API 的开发技能。
- **生产力与第三方集成**：Gmail、Google Drive/Calendar/Docs/Sheets/Slides 等生产力插件，以及 Google Ads、Google Analytics、Search Console、Gong、Salesforce 等 SaaS 集成插件。

**技术亮点**: 使用 TypeScript 开发；采用“根目录独立插件 + 统一 manifest”的架构，便于插件独立维护与市场分发；插件覆盖从代码审查、任务编排到第三方 API 集成的完整 Agent 工作流生态。

---
## 6. [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)
- **语言**: TypeScript
- **Stars**: 207,077
- **简介**: Knowledge infrastructure to make your agents smarter. Search, scrape and access 550+ data providers through one API.

### AI 总结
**简介**: Firecrawl 是一套面向 AI Agent 的知识基础设施，可将网页转换为干净的 Markdown，并通过统一 API 提供搜索、抓取及 550+ 数据源访问能力。

**核心功能**:
- **网页抓取与转换**：将网页抓取并转为干净的 Markdown，支持本地渲染 JavaScript 页面、解析 PDF 与 Office 文档
- **站点爬取与映射**：`crawl` 按站点批量抓取并逐页保存，`map` 列出站点全部 URL
- **MCP 服务集成**：`init` 自动为 Claude Code、Cursor、Windsurf、Gemini CLI、Codex 等 AI 工具注册为 MCP 服务器
- **本地 API 服务**：`serve` 在 localhost:3002 提供 Firecrawl v2 API，兼容官方 SDK，本地路由无需 API Key
- **云端扩展**：Firecrawl Cloud 提供规模化托管服务、搜索能力及 Alexandria 的 550+ 数据源

**技术亮点**: 主体采用 TypeScript 实现；Firecrawl Local 以 Rust 编写、通过 crates.io 分发，可单二进制运行且无需数据库、队列或容器；支持自托管部署（含独立队列、Worker 与数据库），并提供 Python 等多语言 SDK。

---
## 7. [nginx/nginx](https://github.com/nginx/nginx)
- **语言**: C
- **Stars**: 32,891
- **简介**: The official NGINX Open Source repository.

### AI 总结
**简介**: NGINX 官方开源仓库，用 C 语言编写的全球最流行的 Web 服务器、高性能负载均衡器、反向代理、API 网关和内容缓存软件。

**核心功能**:
- Web 服务器：提供静态内容服务与 HTTP 请求处理
- 负载均衡与反向代理：支持高性能的流量分发与代理转发
- API 网关：统一管理后端 API 流量
- 内容缓存：加速内容分发、降低后端压力
- 模块化扩展：通过静态或动态模块按需扩展功能（可用 `nginx -V` 查看已编译的静态模块）

**技术亮点**:
- 采用 C 语言开发，注重高性能与低资源占用
- 模块化架构，功能由独立模块组合而成，支持静态编译与动态加载
- 基于配置文件驱动（configuration-driven），配置灵活
- 采用 BSD 2-Clause 许可证，开源免费；企业版发行、商业支持与培训由 F5, Inc 提供
- 官方提供主流操作系统与 Linux 发行版的二进制包，并建议优先使用官方包或本仓库源码以确保获得最新特性、修复与安全补丁

---
## 8. [openvinotoolkit/openvino](https://github.com/openvinotoolkit/openvino)
- **语言**: C++
- **Stars**: 12,095
- **简介**: OpenVINO™ is an open source toolkit for optimizing and deploying AI inference

### AI 总结
**简介**: OpenVINO™ 是 Intel 开源的一款用于优化和部署深度学习模型推理的工具包，主要使用 C++ 编写。

**核心功能**:
- **推理优化**：提升计算机视觉、语音识别、生成式 AI、自然语言处理（含大/小语言模型）等任务的深度学习性能。
- **灵活的模型支持**：支持 PyTorch、TensorFlow、ONNX、Keras、PaddlePaddle、JAX/Flax 等框架训练的模型，并可通过 Optimum Intel 直接集成 Hugging Face Hub 上的 transformers 和 diffusers 模型，无需原始框架即可转换和部署。
- **广泛的平台兼容性**：支持在 CPU（x86、ARM）、GPU（Intel 集成与独立显卡）及 AI 加速器（Intel NPU）上推理，覆盖从边缘到云端的多种平台。
- **社区与生态**：提供丰富的教程、Notebook 示例（如 LLM 聊天机器人、YOLOv11 优化、文生图、LLaVa 多模态助手、Whisper 语音识别）和 Python/C++ 示例。

**技术亮点**: 采用 C++ 实现，提供 Python、Node.js 等多语言发行包（PyPI、NPM、Anaconda、Homebrew），支持跨框架模型转换与部署，覆盖 CPU/GPU/NPU 多种硬件加速，并配套 OpenVINO Notebooks 与 GenAI 生态。

---
## 9. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 70,333
- **简介**: Editorial diagram design for Claude Code, Codex, GitHub Copilot, Cursor, Factory Droid, Qoder, and Pi. 45 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个面向 AI 编码代理的图表绘制技能，用纯 HTML + SVG 生成自包含的编辑级图表，告别 Mermaid 式粗糙风格。

**核心功能**:
- 支持 51 种图表类型（架构图、象限图、时序图等），代理会根据自然语言描述自动选择类型并生成单个 `.html` 文件
- 可导入 draw.io、Mermaid、Excalidraw、PlantUML 等格式，支持导出 PNG / SVG
- 品牌定制：通过 `Onboard diagram-design to <你的网站>` 自动抓取站点配色与字体，让所有图表匹配品牌风格
- 兼容 Cursor、Claude Code、Codex、GitHub Copilot、Qoder、Gemini CLI、Windsurf 等多种 Agent Skills 宿主

**技术亮点**: 输出为单文件自包含 HTML + SVG，无需外部依赖、无阴影等装饰噪音；通过 `npx skills add` 跨代理安装，多宿主场景推荐 Symlink 方式以统一更新；Claude Code 提供插件市场与自动更新支持。

---
## 10. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 72,762
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个由 AI Agent 驱动的搜索技能，能并行检索 Reddit、X、YouTube、HN、Polymarket 等多个平台并按真实用户互动数据打分，最终合成一份有据可依的摘要。

**核心功能**:
- 跨平台并行搜索：覆盖 Reddit、X/Twitter、YouTube、Hacker News、Polymarket、TikTok、arXiv、Techmeme、GitHub 及网页等十余个来源
- 按真实互动打分：以 Reddit 点赞、X 喜欢、YouTube 字幕、TikTok 互动、Polymarket 真金白银赔率等信号排序，而非编辑推荐
- AI Agent 综合研判：由 agent 作为裁判，将多源结果整合成一份连贯简报
- 零配置上手：Reddit、HN、Polymarket、GitHub 及专利/招聘页面开箱即用；运行一次后向导可在 30 秒内解锁 X、YouTube、TikTok、arXiv 等
- 多宿主安装：支持 Claude Code 插件市场，以及 Codex、Cursor、Copilot、Gemini CLI 等 50+ Agent Skills 宿主

**技术亮点**: 基于 Python 实现；采用"自带密钥与浏览器会话"（BYOK + 浏览器登录态）的方式打通各平台封闭 API；通过 agent 并行检索、交叉打分与综合生成，弥补单一 AI 无法同时访问多平台的数据孤岛问题。

---
