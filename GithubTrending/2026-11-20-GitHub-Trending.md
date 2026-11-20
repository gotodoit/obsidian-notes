---
tags:
  - github-trending
  - daily
date: 2026-11-20
created: 2026-11-20T01:55:48.888Z
---

# 2026-11-20 GitHub Trending Top 10

## 1. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- **语言**: Python
- **Stars**: 12,600
- **简介**: A Claude Code skill bundle for bug hunting and external red-team work - 82 skills, 15 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.

### AI 总结
**简介**: Claude-BugHunter 是一个面向漏洞挖掘与外部红队工作的 Claude Code 技能包，将 Claude 从聊天机器人转变为资深漏洞研究员或红队操作员。

**核心功能**:
- **思维框架**：`bb-methodology` 与 `redteam-mindset` 提供五阶段非线性工作流、批判性思维框架及红队操作纪律。
- **Web 应用狩猎**：58 个 `hunt-*` 技能，基于 681 份已披露的 HackerOne 报告整理，涵盖各类漏洞的检测模式、Payload、绕过表和攻击链模板。
- **外围攻击**：针对企业平台（M365/Entra、Okta、vCenter、SSL-VPN 设备、SharePoint、云 IAM）的 2024–2026 年 CVE 攻击链及获取凭据后的提权路径。
- **交付与合规**：`triage-validation`、报告生成与 `evidence-hygiene`，包括 7 问门禁、VRT 感知严重性评级、OOS 反驳、PII 脱敏及红队交付物。
- **自动触发**：用自然语言描述测试目标即可自动加载对应技能，无需按名称调用。

**技术亮点**:
- 基于 Claude Code 技能系统构建，共 83 个技能、15 个斜杠命令，覆盖 24 类核心漏洞（其中 433 条报告模式可单独引用与审计）。
- 提供两种安装方式：插件市场安装（命名空间隔离、随版本更新）或脚本复制安装（macOS/Linux/Windows），后者附带 `hunt` 项目脚手架。
- 集成 Burp MCP 与 HackerOne MCP（可选 API 凭据，仅用于读取私有项目与个人报告）。
- 提供独立 `cbh` CLI（可通过 pipx 安装），已在授权红队、漏洞挖掘及 DVWA、OWASP Juice Shop 等公开训练平台验证。

---
## 2. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 322,119
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，基于可组合的技能（skills）和引导指令，让 AI 代理按规范流程完成从需求梳理到实现的全过程。

**核心功能**:
- **需求澄清**：智能体不直接写代码，而是先退一步询问用户的真实目标，梳理出规格说明。
- **分块评审**：将规格以易读的短块形式呈现给用户逐段确认。
- **实现计划**：设计通过后生成清晰的实施计划，强调真正的红/绿 TDD、YAGNI 和 DRY 原则。
- **子代理驱动开发**：用户确认后启动多子代理并行推进各工程任务，自动检查与审查工作成果，可长时间自主执行而不偏离计划。
- **自动触发**：技能自动生效，无需额外操作，智能体即具备 Superpowers 能力。
- **多平台安装支持**：覆盖 Claude Code、Codex、Cursor、Gemini CLI、GitHub Copilot CLI、Qwen Code 等十余种编码工具。

**技术亮点**: 以 Shell 为主实现；采用可组合技能架构与 marketplace/插件机制分发；内置子代理编排与自动化工作流，并提供企业级商业支持服务。

---
## 3. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 60,600
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: CLI-Anything 是香港大学数据科学实验室（HKUDS）开源的项目，旨在为各类软件自动生成命令行接口（CLI），让 AI Agent 能够直接操作现实世界的软件，实现"所有软件 Agent 原生"。

**核心功能**:
- **一键生成 CLI**：为任意软件生成 agent-ready 的命令行封装，可直接对接 Pi、OpenClaw、nanobot、Cursor、Claude Code 等 AI Agent 工具。
- **CLI-Hub 社区中心**：通过 `pip install cli-anything-hub` 安装后，可用 `cli-hub install <name>` 浏览、安装和管理社区构建的 CLI，并支持提交 PR 贡献自己的 CLI。
- **预览与轨迹循环**：AI Agent 可结合预览（preview）、实时预览和轨迹循环生成真实产物，如 CAD 建模、3D 场景、图表、游戏玩法、字幕等。
- **社区共建机制**：支持贡献者报名构建新 CLI harness，以及提交软件/服务支持心愿单。

**技术亮点**: 基于 Python（≥3.10）开发，使用 Click（≥8.0）构建命令行界面，Pytest 测试全部通过（2,461 项测试），支持 JSON 与人类可读双格式输出，采用 Apache 2.0 许可，并提供 arXiv 技术报告。

---
## 4. [jingyaogong/minimind](https://github.com/jingyaogong/minimind)
- **语言**: Python
- **Stars**: 66,927
- **简介**: 🧠 两小时从 0 训出你的 64M 大模型。Train your own 64M LLM from scratch in 2 hours.

### AI 总结
**简介**: MiniMind 是一个从零开始、低成本（约 3 元 GPU 租用成本、2 小时训练）训练 64M 超小语言模型的开源项目，同时是一套覆盖大模型全流程的可复现教程。

**核心功能**:
- 提供完整的 MiniMind-LLM 结构代码（Dense + MoE），主线结构对齐 Qwen3 / Qwen3-MoE 生态
- 覆盖 Pretrain、SFT、LoRA、RLHF-DPO、RLAIF（PPO / GRPO / CISPO）、Tool Use、Agentic RL、自适应思考与模型蒸馏等完整训练链路
- 提供 Tokenizer 与分词器训练代码，以及全阶段高质量开源数据集（含收集、蒸馏、清洗与去重）
- 提供兼容 OpenAI API 协议的极简服务端和基于 Streamlit 的聊天 WebUI，支持思考展示与多轮 Tool Call
- 支持 C-Eval、C-MMLU、OpenBookQA 等第三方测评，支持 YaRN 长文本外推
- 拓展视觉模型 MiniMind-V、多模态 Omni 模型 MiniMind-O、扩散语言模型与线性注意力模型

**技术亮点**: 所有核心算法与关键模块均使用 PyTorch 原生从零实现，不依赖 transformers/trl/peft 等框架的高层封装；兼容 transformers、trl、peft、llama.cpp、vllm、ollama、Llama-Factory 等主流生态；支持单卡与多卡（DDP、DeepSpeed）训练及 wandb/swanlab 可视化；采用 Apache 2.0 协议开源。

---
## 5. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 17,574
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，汇集面向主流开发工具、框架和 SaaS 产品的插件规范与官方插件，每个插件为独立目录并带有 `.cursor-plugin/plugin.json` 清单。

**核心功能**:
- **开发工具类插件**：覆盖教学辅助（Teaching）、持续学习记忆（Continual Learning）、团队工作流（Cursor Team Kit）、深度分支审查（Thermos）、插件脚手架（Create Plugin）、迭代式 AI 循环（Ralph Loop）、仓库兼容性扫描（Agent Compatibility）、面向 Agent 的 CLI 设计（CLI for Agents）、PR 审查画布（PR Review Canvas）、文档画布（Docs Canvas）等。
- **Agent 编排与协作**：提供 Cursor SDK 用于构建应用与自动化，Orchestrate 支持将大型任务分发到并行云端 Agent（规划者/执行者/验证者），Advisor 可在关键决策前咨询更强模型。
- **第三方集成**：包括 Gmail、Google Drive/Calendar/Docs/Sheets/Slides 等生产力工具，以及 Google Ads、Google Analytics、Search Console、Gong、Salesforce 等业务集成插件。

**技术亮点**: 采用 TypeScript 开发；插件以独立目录组织，通过统一的 `.cursor-plugin/plugin.json` 清单定义元数据（名称、作者、分类、描述），便于在插件市场中分发与复用。

---
## 6. [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)
- **语言**: TypeScript
- **Stars**: 204,283
- **简介**: Knowledge infrastructure to make your agents smarter. Search, scrape and 550+ data providers through one API.

### AI 总结
**简介**: Firecrawl 是一套面向 AI Agent 的知识基础设施，可将网站内容转换为干净的 Markdown，并通过统一 API 提供搜索、抓取及 550+ 数据源接入能力。

**核心功能**:
- **Firecrawl Local**：以单一二进制在本地运行，支持 scrape、crawl、map 和批量抓取，无需数据库、队列或容器
- **MCP 服务器集成**：通过 `firecrawl-local init` 自动将 Firecrawl 注册为 Claude Code、Cursor、Windsurf、Gemini CLI、Codex 等 AI 工具的 MCP 服务器
- **本地 API 服务**：`serve` 命令在 localhost:3002 提供兼容 Firecrawl v2 的 API，现有 SDK 代码可直接复用
- **Firecrawl Cloud**：托管服务，在 Local 能力基础上提供规模化运行、搜索及 Alexandria 的 550+ 数据源
- **自托管部署**：可从 `apps/api` 部署完整服务端，包含队列、Worker 和数据库

**技术亮点**:
- 主仓库语言为 TypeScript，Firecrawl Local 基于 Rust 实现并通过 crates.io 分发
- 复用本机已有 Chrome/Chromium 渲染 JavaScript 页面，PDF 与 Office 文档本地解析
- 提供 Python 等多语言 SDK，支持自定义 API URL 对接本地或云端服务
- 三种使用形态（Local / Cloud / 自托管）共享同一套 SDK 与 API 协议

---
## 7. [nginx/nginx](https://github.com/nginx/nginx)
- **语言**: C
- **Stars**: 32,350
- **简介**: The official NGINX Open Source repository.

### AI 总结
**简介**: NGINX 官方开源仓库，用 C 语言编写，是全球最流行的 Web 服务器、高性能负载均衡器、反向代理、API 网关和内容缓存软件。

**核心功能**:
- Web 服务器：提供静态内容服务与 HTTP 处理能力
- 负载均衡与反向代理：支持高性能的流量分发与代理转发
- API 网关与内容缓存：可作为统一入口并缓存响应内容
- 模块化架构：通过静态或动态模块扩展功能，可用 `nginx -V` 查看已编译的静态模块
- 跨平台支持：为主流操作系统和 Linux 发行版提供二进制包，支持从源码构建

**技术亮点**: 采用 C 语言开发，基于模块化设计（静态/动态模块）；以简化版 2-clause BSD 类许可证开源；由 F5, Inc 提供企业版发行、商业支持与培训。

---
## 8. [openvinotoolkit/openvino](https://github.com/openvinotoolkit/openvino)
- **语言**: C++
- **Stars**: 11,577
- **简介**: OpenVINO™ is an open source toolkit for optimizing and deploying AI inference

### AI 总结
**简介**: OpenVINO™ 是 Intel 开源的一款用于优化和部署深度学习模型推理的工具包，主要使用 C++ 开发。

**核心功能**:
- **推理优化**：提升计算机视觉、语音识别、生成式 AI、自然语言处理（含大/小语言模型）等任务的深度学习性能
- **灵活的模型支持**：兼容 PyTorch、TensorFlow、ONNX、Keras、PaddlePaddle、JAX/Flax 训练的模型，并可通过 Optimum Intel 直接集成 Hugging Face Hub 上的 transformers 和 diffusers 模型，无需原始框架即可转换部署
- **广泛的平台兼容性**：支持从边缘到云端的部署，可在 CPU（x86、ARM）、GPU（Intel 集成与独立显卡）及 AI 加速器（Intel NPU）上推理

**技术亮点**:
- 采用 C++ 实现，提供 Python、Node.js、Conda、Homebrew 等多渠道分发（如 `pip install openvino`）
- 配套丰富的教程与示例资源，包括 OpenVINO Notebooks、LLM 聊天机器人、YOLOv11 优化、文生图、LLaVa 多模态助手、Whisper 语音识别等
- 拥有活跃的社区生态，覆盖多种领域深度学习性能增强

---
## 9. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 68,662
- **简介**: Editorial diagram design for Claude Code, Codex, GitHub Copilot, Cursor, Factory Droid, Qoder, and Pi. 45 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个面向 AI 编程代理的图表绘制技能，用自然语言指令生成单文件 HTML + SVG 的编辑级图表，支持 51 种图表类型。

**核心功能**:
- 通过自然语言描述生成架构图、象限图、时序图等多种图表，代理自动选择图表类型并给出计划
- 支持 51 种图表类型，输出为自包含的单个 `.html` 文件，双击即可打开
- 品牌定制：可从指定网站抓取配色和字体，让所有图表风格保持一致
- 支持从 draw.io、Mermaid、Excalidraw、PlantUML 导入，并可导出 PNG / SVG
- 兼容多种代理宿主（Claude Code、Cursor、Codex、GitHub Copilot、Gemini CLI、Cline、Windsurf 等），通过 `npx skills add` 一键安装

**技术亮点**:
- 纯 HTML + SVG 实现，无阴影、不依赖 Mermaid，追求编辑级设计质感
- 以 Agent Skill 形式分发（`SKILL.md` + references/assets/scripts），跨宿主通用
- 提供 Claude Code 插件市场安装方式，支持自动更新与斜杠命令

---
## 10. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 70,827
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个由 AI Agent 驱动的跨平台研究工具，能并行搜索 Reddit、X、YouTube、HN、Polymarket 等平台，并按真实用户互动数据评分后合成一份有据可依的摘要。

**核心功能**:
- 多平台并行检索：覆盖 Reddit、X/Twitter、YouTube、Hacker News、Polymarket、GitHub、TikTok、arXiv、Techmeme 等，零配置即可使用 Reddit、HN、Polymarket、GitHub 等源。
- 按真实互动评分：以 Reddit 点赞、X 喜欢、YouTube 字幕、TikTok 互动、Polymarket 真实资金赔率等作为排序依据，而非编辑推荐。
- AI Agent 综合研判：由 AI Agent 作为裁判，将多源信息合成为一份连贯、有依据的简报。
- 灵活安装与集成：支持 Claude Code 插件市场一键安装，也支持通过 `npx skills add` 接入 Codex、Cursor、Copilot、Gemini CLI 等 50+ Agent Skills 宿主。
- 典型场景：会前调研人物/公司近 30 天动态、销售通话前了解企业实况、旅行前查询社区口碑等。

**技术亮点**: 基于 Python 实现；采用 v4 流水线架构，运行时技能规范以 `skills/last30days/SKILL.md` 为唯一事实来源；通过用户自带的 API Key 与浏览器会话打通各平台封闭生态，由 Agent 统一调度、交叉评分，并配有安装向导在 30 秒内解锁更多数据源。

---
