---
tags:
  - github-trending
  - daily
date: 2026-11-28
created: 2026-11-28T01:55:42.582Z
---

# 2026-11-28 GitHub Trending Top 10

## 1. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- **语言**: Python
- **Stars**: 26,149
- **简介**: A Claude Code skill bundle for bug hunting and external red-team work - 85 skills, 16 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.

### AI 总结
**简介**: Claude-BugHunter 是一个面向 Claude Code 的自包含技能包，用于漏洞挖掘和外部红队工作，内置 85 个技能、16 个斜杠命令和 681 条公开报告模式，覆盖 24 类核心漏洞。

**核心功能**:
- **思维框架**：`bb-methodology` 与 `redteam-mindset` 提供五阶段非线性工作流、批判性思维框架和红队操作纪律。
- **Web 应用漏洞挖掘**：58 个 `hunt-*` 技能基于 681 份 HackerOne 公开报告整理，包含各类漏洞的检测模式、Payload、绕过表和利用链模板。
- **企业边界攻击**：覆盖 M365/Entra、Okta、vCenter、SSL-VPN 设备、SharePoint、云 IAM 等平台，提供 2024–2026 年 CVE 利用链及获取凭据后的提权路径。
- **交付与合规**：`triage-validation`、报告生成和 `evidence-hygiene` 模块提供 7-Question Gate、VRT 感知的严重性评级、OOS 反驳、PII 脱敏和红队交付物。
- **自动触发**：用自然语言描述测试目标，相关技能会自动加载，无需按名称调用。
- **两种安装方式**：可作为 Claude Code 插件安装（推荐），也可以克隆后运行脚本复制安装；另有独立的 `cbh` CLI（通过 pipx 安装）和 `hunt` 项目脚手架工具。

**技术亮点**: 基于 Claude Code 技能系统构建，采用四层架构（思维 → Web 漏洞挖掘 → 边界攻击 → 交付）；集成 Burp MCP 与 HackerOne MCP（可选 API 凭据）；主要语言为 Python；已在授权红队项目、DVWA、OWASP Juice Shop、Hacker101 等公开训练平台上验证。

---
## 2. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 328,347
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，由可组合的技能（skills）和引导指令构成，让 AI 编码代理按规范流程完成开发任务。

**核心功能**:
- **需求澄清与规格拆解**：智能体不会直接写代码，而是先与用户沟通明确真实目标，再将规格分块呈现，便于阅读和确认。
- **可执行的实施计划**：设计确认后生成足够清晰的实现计划，强调红/绿 TDD、YAGNI 和 DRY 原则。
- **子代理驱动开发**：用户确认后启动多子代理协作流程，逐个完成工程任务并检查、审查工作成果，可长时间自主推进而不偏离计划。
- **自动触发的技能机制**：技能在对话中自动生效，用户无需额外操作即可获得完整方法论支持。
- **广泛的工具兼容**：提供 Claude Code、Codex、Cursor、Gemini CLI、GitHub Copilot CLI、OpenCode 等多种编码代理的安装方式。

**技术亮点**: 基于 Shell 实现；采用可组合技能架构，通过技能描述自动引导模型加载；支持插件市场与扩展机制，适配多种主流 AI 编码工具生态。

---
## 3. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 67,028
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: HKUDS 团队推出的开源项目，旨在通过自动生成 CLI（命令行接口）让所有软件都能被 AI Agent 原生调用，打通 AI 智能体与现有软件生态之间的鸿沟。

**核心功能**:
- **CLI 自动生成**：为各类软件生成可直接被 Agent 调用的命令行接口，让 Cursor、Claude Code、OpenClaw 等 AI 工具能够操作任意软件。
- **CLI-Hub 社区中心**：提供命令行工具集散平台，可通过 `pip install cli-anything-hub` 安装后使用 `cli-hub install <name>` 浏览、安装和管理社区构建的 CLI。
- **实时预览与轨迹循环**：Agent 借助生成的 CLI 配合预览、实时预览和轨迹循环机制，可产出 CAD 构建、3D 场景、图表、游戏玩法、字幕等真实成果。
- **社区共建机制**：支持贡献者提交新的 CLI harness，并设有需求清单（wishlist）供用户请求特定软件或服务的支持。

**技术亮点**: 基于 Python（≥3.10）开发，使用 Click 构建命令行界面，Pytest 测试全部通过（2,461 项测试），输出支持 JSON 与人类可读双格式；采用 Apache 2.0 开源协议，并提供 arXiv 技术报告。

---
## 4. [jingyaogong/minimind](https://github.com/jingyaogong/minimind)
- **语言**: Python
- **Stars**: 72,230
- **简介**: 🧠 两小时从 0 训出你的 64M 大模型。Train your own 64M LLM from scratch in 2 hours.

### AI 总结
**简介**: MiniMind 是一个从零开始训练超小语言模型（约 64M 参数）的开源项目，最低成本约 3 元、训练约 2 小时即可完成，旨在降低 LLM 学习与复现门槛。

**核心功能**:
- 提供完整的 MiniMind-LLM 结构代码（Dense + MoE），主线结构对齐 Qwen3 / Qwen3-MoE 生态
- 覆盖 Pretrain、SFT、LoRA、RLHF-DPO、RLAIF（PPO / GRPO / CISPO）、Tool Use、Agentic RL、自适应思考与模型蒸馏等完整训练链路
- 提供 Tokenizer 与分词器训练代码，支持 `<tool_call>`、`<tool_response>`、`<think>` 等模板标记
- 提供全阶段开源数据（收集、蒸馏、清洗、去重后的高质量数据集）
- 支持单机单卡与多卡训练（DDP、DeepSpeed），支持 wandb / swanlab 可视化与动态启停
- 支持 C-Eval、C-MMLU、OpenBookQA 等第三方评测，并可通过 YaRN 实现 RoPE 长文本外推
- 提供兼容 OpenAI API 协议的极简服务端及基于 Streamlit 的聊天 WebUI
- 拓展视觉模型 MiniMind-V、多模态 Omni 模型 MiniMind-O、扩散语言模型 MiniMind-dLM、线性模型 MiniMind-Linear

**技术亮点**: 核心算法与模块均用 PyTorch 原生从零实现，不依赖第三方高层抽象接口；兼容 transformers / trl / peft 及 llama.cpp、vllm、ollama、Llama-Factory 等生态；模型体积极小（约为 GPT-3 的 1/2700），适合个人 GPU 训练与复现；采用 Apache 2.0 协议完全开源。

---
## 5. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 20,022
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，汇集面向主流开发工具、框架和 SaaS 产品的官方插件，每个插件均为仓库根目录下的独立目录，并带有自己的 `.cursor-plugin/plugin.json` 清单文件。

**核心功能**:
- **开发工作流插件**：涵盖教学辅助（Teaching）、增量记忆更新（Continual Learning）、团队协作（Cursor Team Kit）、深度安全与代码质量审计（Thermos）、插件脚手架（Create Plugin）等。
- **AI 智能体编排**：提供迭代自引用循环（Ralph Loop）、并行云智能体任务分发（Orchestrate）、强模型决策咨询（Advisor）、仓库兼容性扫描（Agent Compatibility）等能力。
- **CLI 与 SDK 支持**：包含面向编码智能体的 CLI 设计模式（CLI for Agents）以及基于 TypeScript SDK 构建应用与自动化（Cursor SDK）。
- **评审与文档可视化**：将 PR 差异按重要性分组渲染为评审画布（PR Review Canvas），并将文档渲染为可导航画布（Docs Canvas）。
- **第三方产品集成**：覆盖 Gmail、Google Drive/Calendar/Docs/Sheets/Slides、Google Ads/Analytics/Search Console、Gong、Salesforce 等生产力与集成类插件。

**技术亮点**: 项目以 TypeScript 为主要语言；采用“一插件一目录 + 统一清单文件”的模块化结构，便于独立开发、分发与市场化管理；插件覆盖 Utilities、Developer Tools、Productivity、Integrations 等多个分类，兼顾官方自研与社区作者贡献。

---
## 6. [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)
- **语言**: TypeScript
- **Stars**: 211,710
- **简介**: Knowledge infrastructure to make your agents smarter. Search, scrape and access 550+ data providers through one API.

### AI 总结
**简介**: Firecrawl 是面向 AI Agent 的知识基础设施，通过统一 API 提供搜索、抓取和访问 550+ 数据源的能力，可将网站转换为干净的 Markdown。

**核心功能**:
- **Firecrawl Local**：单二进制在本地运行，无需数据库、队列或容器，即可抓取、爬取和映射网站，并可作为 MCP 服务器接入 AI Agent
- **Firecrawl Cloud**：托管服务，支持大规模运行、搜索以及通过 Firecrawl Alexandria 访问 550+ 数据提供商
- **自托管**：从 `apps/api` 部署完整服务端，自带队列、Worker 和数据库
- **多方式接入**：提供 CLI（`firecrawl-local scrape/crawl/map`）、MCP 服务器（`init` 自动配置 Claude Code、Cursor、Windsurf 等工具）以及 localhost v2 API（`serve`）
- **文档解析**：本地解析 PDF 和 Office 文档，利用本机 Chrome/Chromium 渲染需 JavaScript 的页面

**技术亮点**: 主体使用 TypeScript 开发；Local 版本基于 Rust 构建并从 crates.io 安装；MCP 服务器需 Node.js 22+；兼容现有 Firecrawl SDK，可通过设置 `api_url` 无缝切换到本地服务；`init` 命令会自动备份配置文件后写入 MCP 配置。

---
## 7. [nginx/nginx](https://github.com/nginx/nginx)
- **语言**: C
- **Stars**: 33,669
- **简介**: The official NGINX Open Source repository.

### AI 总结
**简介**: NGINX 官方开源仓库，全球最流行的 Web 服务器、高性能负载均衡器、反向代理、API 网关和内容缓存软件，采用 C 语言编写，基于简化的 2-clause BSD 类许可证发布。

**核心功能**:
- Web 服务器：提供高性能的静态内容服务
- 负载均衡与反向代理：支持高并发流量分发
- API 网关：统一管理和路由 API 请求
- 内容缓存：加速内容分发、降低后端压力
- 模块化扩展：通过静态或动态模块扩展功能（可用 `nginx -V` 查看已编译的静态模块）
- 支持 SSL/TLS 加密、速率限制等常用能力

**技术亮点**: 采用模块化架构，核心功能由独立模块组成，支持静态模块（编译期定义）与动态模块（运行期加载）；跨平台支持主流 Linux 发行版、FreeBSD 和 Windows；提供 Stable 与 Mainline 双版本二进制包；企业级发行版、商业支持与培训由 F5, Inc 提供。

---
## 8. [openvinotoolkit/openvino](https://github.com/openvinotoolkit/openvino)
- **语言**: C++
- **Stars**: 12,960
- **简介**: OpenVINO™ is an open source toolkit for optimizing and deploying AI inference

### AI 总结
**简介**: OpenVINO™ 是 Intel 开源的一款用于优化和部署深度学习模型推理的 C++ 工具包，支持从边缘到云端的多种硬件平台。

**核心功能**:
- **推理优化**：提升计算机视觉、语音识别、生成式 AI、自然语言处理（大/小语言模型）等任务的深度学习性能
- **灵活的模型支持**：兼容 PyTorch、TensorFlow、ONNX、Keras、PaddlePaddle、JAX/Flax 训练的模型，并可通过 Optimum Intel 直接集成 Hugging Face Hub 上的 transformers 和 diffusers 模型，无需原始框架即可转换和部署
- **广泛的平台兼容性**：支持在 CPU（x86、ARM）、GPU（Intel 集成与独立显卡）及 AI 加速器（Intel NPU）上高效推理，降低资源需求
- **丰富的教程与示例**：提供 OpenVINO Notebooks，涵盖 LLM 聊天机器人、YOLOv11 优化、文生图、LLaVa 多模态助手、Whisper 语音识别等实战案例

**技术亮点**: 采用 C++ 实现，提供 Python、Node.js 等多语言分发（PyPI、NPM、Conda、Homebrew），支持跨框架模型转换与部署，并拥有活跃的社区生态与完善的文档体系。

---
## 9. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 74,478
- **简介**: Editorial diagram design for Claude Code, Codex, GitHub Copilot, Cursor, Factory Droid, Qoder, and Pi. 52 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个面向 AI 编程助手的图表绘制技能，用单个自包含的 HTML + SVG 文件生成符合品牌风格的编辑级图表。

**核心功能**:
- 支持 52 种图表类型，包括架构图、象限图、时序图等
- 用自然语言向 Agent 描述需求，自动选择图表类型并生成可直接双击打开的 `.html` 文件
- 提供品牌适配功能，可从指定网站抓取配色和字体，让图表风格与品牌一致
- 支持从 draw.io、Mermaid、Excalidraw、PlantUML 导入，并可导出为 PNG 或 SVG
- 兼容 Claude Code、Codex、GitHub Copilot、Cursor、Qoder 等多种 Agent 宿主，并可通过 `npx skills add` 或 Claude Code 插件市场安装

**技术亮点**: 使用自包含 HTML + SVG 输出，无阴影、不依赖 Mermaid；以 Agent Skill 形式分发，支持插件自动更新、CI 校验，并采用 MIT 许可证。

---
## 10. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 76,389
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个 AI Agent 技能，可跨 Reddit、X、YouTube、HN、Polymarket 及网页并行检索任意话题，再由 AI 综合生成有据可依的摘要。

**核心功能**:
- 多平台并行搜索：同时检索 Reddit、X/Twitter、YouTube、Hacker News、Polymarket、GitHub、arXiv、TikTok、Techmeme 等来源，突破各平台“围墙花园”限制
- 按真实互动排序：以 Reddit 点赞、X 喜欢、YouTube 转录、Polymarket 真金白银赔率等社区信号打分，而非编辑推荐
- AI 综合摘要：由 AI Agent 作为裁判，将分散信息整合成一份聚焦“最近 30 天”的简报
- 零配置开箱即用：Reddit、HN、Polymarket、GitHub 无需配置即可使用，设置向导可在 30 秒内解锁其余平台
- 多宿主安装：支持 Claude Code 插件市场、Codex、Cursor、Copilot、Gemini CLI 等 50+ Agent Skills 宿主

**技术亮点**: 基于 Python 实现；采用 Agent Skill 规范（SKILL.md 作为运行时规格来源）；通过用户自带 API Key 与浏览器会话桥接多个独立平台，实现并行检索与跨源评分；提供多语言 README 与 CI 校验工作流。

---
