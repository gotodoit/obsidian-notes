---
tags:
  - github-trending
  - daily
date: 2026-11-25
created: 2026-11-25T01:55:44.637Z
---

# 2026-11-25 GitHub Trending Top 10

## 1. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- **语言**: Python
- **Stars**: 21,522
- **简介**: A Claude Code skill bundle for bug hunting and external red-team work - 84 skills, 15 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.

### AI 总结
**简介**: Claude-BugHunter 是一个面向漏洞挖掘与外部红队工作的 Claude Code 技能包，内置 84 个技能、15 个斜杠命令和 681 条已披露报告模式，覆盖 24 类核心漏洞。

**核心功能**:
- **方法论与思维框架**：通过 `bb-methodology` 和 `redteam-mindset` 提供五阶段非线性工作流、批判性思维框架和红队操作纪律。
- **Web 应用漏洞挖掘**：58 个 `hunt-*` 技能，基于 681 份 HackerOne 披露报告整理，包含各类漏洞的检测模式、Payload、绕过表和攻击链模板。
- **企业边界攻击**：覆盖 M365/Entra、Okta、vCenter、SSL-VPN、SharePoint、云 IAM 等平台的 2024–2026 CVE 攻击链及凭据后提权。
- **分诊与报告输出**：提供 7-Question Gate、VRT 感知的严重性评级、OOS 反驳、PII 脱敏和红队交付物模板。
- **自动技能加载**：用自然语言描述测试目标即可自动匹配并加载相关技能，无需按名称调用。

**技术亮点**: 基于 Claude Code 技能系统构建，支持插件市场安装和脚本复制安装两种方式；集成 Burp MCP 与 HackerOne MCP（可选 API 凭据）；提供 `cbh` 命令行工具和 `hunt` 项目脚手架；已在授权红队、漏洞挖掘及 DVWA、OWASP Juice Shop、Hacker101 等公开训练平台验证。

---
## 2. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 325,852
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，基于可组合技能与初始指令构建，让智能体自动遵循规范化的开发流程。

**核心功能**:
- **需求澄清与规格输出**：智能体启动后不急于写代码，而是先追问真实意图，将需求整理成分段可读的规格说明供用户确认。
- **可执行的实现计划**：设计确认后生成清晰到“初级工程师也能照做”的实施计划，强调红/绿 TDD、YAGNI 与 DRY 原则。
- **子智能体驱动开发**：用户确认后启动子智能体逐项完成工程任务，自动检查与评审工作成果，可长时间自主推进而不偏离计划。
- **自动触发**：技能在对话中自动激活，无需额外操作。
- **多平台安装支持**：提供 Claude Code、Codex、Cursor、Gemini CLI、GitHub Copilot CLI、OpenCode 等多种智能体运行环境的安装方式。

**技术亮点**: 采用可组合技能（composable skills）架构，以 Shell 为主要实现语言；技能通过描述自动触发加载，支持插件市场与命令行安装，并针对不同智能体平台提供独立安装路径。

---
## 3. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 64,848
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: HKUDS/CLI-Anything 是一个 Python 项目，旨在为各类软件自动生成 CLI 封装，让 AI Agent 能够直接操作现有软件，实现“让所有软件 Agent-Native”。

**核心功能**:
- 一条命令行即可将任意软件变为可供 Pi、OpenClaw、nanobot、Cursor、Claude Code 等 AI Agent 调用的 CLI 工具
- 提供 CLI-Hub 社区中心，可通过 `pip install cli-anything-hub` 安装，并用 `cli-hub install <name>` 浏览、安装和管理社区构建的 CLI
- 支持 AI Agent 借助生成的 CLI 完成 CAD 建模、3D 场景、图表、游戏、字幕等真实产物制作
- 提供贡献者计划与 CLI 需求清单机制，支持社区提交新 CLI 封装或请求特定软件支持

**技术亮点**: 基于 Python ≥3.10 与 Click ≥8.0 构建，输出支持 JSON 与人类可读两种格式；配套 pytest 单元与端到端测试（宣称 2,461 项测试通过），采用 Apache 2.0 许可，并有 arXiv 技术报告支撑。

---
## 4. [jingyaogong/minimind](https://github.com/jingyaogong/minimind)
- **语言**: Python
- **Stars**: 70,254
- **简介**: 🧠 两小时从 0 训出你的 64M 大模型。Train your own 64M LLM from scratch in 2 hours.

### AI 总结
**简介**: MiniMind 是一个从零开始训练超小语言模型（约 64M 参数）的开源项目，主打低成本（约 3 元 GPU 租用）与短耗时（2 小时 SFT），同时提供完整的大模型训练链路与教程。

**核心功能**:
- 提供完整的 MiniMind-LLM 结构代码（Dense + MoE），主线结构对齐 Qwen3 / Qwen3-MoE 生态
- 覆盖 Pretrain、SFT、LoRA、RLHF-DPO、RLAIF（PPO / GRPO / CISPO）、Tool Use、Agentic RL、自适应思考与模型蒸馏等全流程训练
- 提供 Tokenizer 训练代码与全阶段开源数据集（含收集、蒸馏、清洗、去重）
- 支持 C-Eval、C-MMLU、OpenBookQA 等第三方评测，及 YaRN 长文本外推
- 提供兼容 OpenAI API 的极简服务端与基于 Streamlit 的聊天 WebUI
- 拓展视觉、多模态 Omni、扩散语言模型、线性模型等衍生项目

**技术亮点**: 所有核心算法与模块均用 PyTorch 原生从零实现，不依赖第三方高层封装；兼容 transformers、trl、peft、llama.cpp、vllm、ollama、Llama-Factory 等生态；支持单机单卡与多卡（DDP、DeepSpeed）训练，支持 wandb / swanlab 可视化；Apache 2.0 协议完全开源免费。

---
## 5. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 19,235
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，提供面向主流开发工具、框架和 SaaS 产品的插件规范与官方插件集合，每个插件以独立目录形式存在并带有 `.cursor-plugin/plugin.json` 清单。

**核心功能**:
- **开发工具类插件**：涵盖教学辅助（Teaching）、持续学习记忆更新（Continual Learning）、团队协作工作流（Cursor Team Kit）、深度安全与代码质量审计（Thermos）、插件脚手架生成（Create Plugin）、迭代式 AI 循环（Ralph Loop）、仓库兼容性扫描（Agent Compatibility）、CLI 设计模式（CLI for Agents）、PR 差异审查画布（PR Review Canvas）、文档画布（Docs Canvas）等
- **Agent 编排与协作**：Orchestrate 支持将大型任务拆分给并行云端 Agent（规划者、执行者、验证者及结构化交接）；Advisor 可在关键决策前咨询更强模型
- **SDK 与 API 支持**：Cursor SDK 用于构建应用、脚本与自动化；Origin Apps 提供基于 Cursor Origin API 的构建技能
- **生产力集成**：Gmail、Google Drive、Google Calendar、Google Docs、Google Sheets、Google Slides 等日常办公工具
- **第三方集成**：Google Ads、Google Analytics、Google Search Console、Gong、Salesforce 等业务系统

**技术亮点**: 采用 TypeScript 开发；插件以仓库根目录下的独立目录组织，通过统一的 `.cursor-plugin/plugin.json` 清单进行声明与校验；支持并行子 Agent 编排、结构化任务交接以及可选的 PR 合并流程。

---
## 6. [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)
- **语言**: TypeScript
- **Stars**: 208,973
- **简介**: Knowledge infrastructure to make your agents smarter. Search, scrape and access 550+ data providers through one API.

### AI 总结
**简介**: Firecrawl 是一款为 AI Agent 提供知识基础设施的开源工具，可将网站内容转换为干净的 Markdown，并通过统一 API 访问 550+ 数据源。

**核心功能**:
- **网页抓取（Scrape）**：将单个网页转换为 Markdown，支持 JavaScript 渲染页面及 PDF、Office 文档解析
- **站点爬取（Crawl）**：按页爬取整个站点，可限制数量并输出为 Markdown 文件
- **站点映射（Map）**：列出站点上的所有 URL
- **MCP 服务器集成**：一行命令自动接入 Claude Code、Cursor、Windsurf、Gemini CLI、Codex 等 AI 工具
- **本地 API 服务**：在 localhost:3002 提供 Firecrawl v2 API，兼容官方 SDK
- **三种使用方式**：本地运行（Firecrawl Local）、云端托管（Firecrawl Cloud）、自托管部署

**技术亮点**: 主体使用 TypeScript 开发；Firecrawl Local 以 Rust 编写并可通过 crates.io 安装；支持 Docker 部署；自托管版本包含队列、Worker 和数据库的完整架构；提供多语言 SDK，本地路由无需 API Key。

---
## 7. [nginx/nginx](https://github.com/nginx/nginx)
- **语言**: C
- **Stars**: 33,227
- **简介**: The official NGINX Open Source repository.

### AI 总结
**简介**: NGINX 官方开源仓库，用 C 语言编写，是全球最流行的 Web 服务器、高性能负载均衡器、反向代理、API 网关和内容缓存软件。

**核心功能**:
- Web 服务器：提供静态内容服务与 HTTP 处理能力
- 高性能负载均衡与反向代理
- API 网关与内容缓存
- 模块化架构：支持静态模块与动态模块，可按需扩展功能

**技术亮点**: 基于 C 语言实现；采用模块化设计，各模块独立扩展核心功能；遵循简化版 2-clause BSD 类许可证；提供适用于主流操作系统和 Linux 发行版的二进制包，支持从源码构建；企业版发行、商业支持与培训由 F5, Inc 提供。

---
## 8. [openvinotoolkit/openvino](https://github.com/openvinotoolkit/openvino)
- **语言**: C++
- **Stars**: 12,473
- **简介**: OpenVINO™ is an open source toolkit for optimizing and deploying AI inference

### AI 总结
**简介**: OpenVINO™ 是 Intel 推出的开源工具包，用于优化和部署深度学习模型推理，支持从边缘到云的多平台高效部署。

**核心功能**:
- **推理优化**：提升计算机视觉、语音识别、生成式 AI、自然语言处理（含大/小语言模型）等任务性能
- **灵活模型支持**：兼容 PyTorch、TensorFlow、ONNX、Keras、PaddlePaddle、JAX/Flax 训练的模型，并可通过 Optimum Intel 直接集成 Hugging Face Hub 上的 transformers 与 diffusers 模型，无需原始框架即可转换部署
- **广泛平台兼容**：支持 CPU（x86、ARM）、GPU（Intel 集成与独立显卡）及 AI 加速器（Intel NPU）推理，降低资源需求
- **丰富生态**：提供 Notebooks 教程、Python/C++ 示例、生成式 AI 支持（openvino.genai）及活跃社区

**技术亮点**: 以 C++ 实现核心，提供 Python、Node.js 等多语言分发（PyPI、NPM、Conda、Homebrew）；支持模型转换与跨平台推理优化，覆盖 LLM 聊天机器人、YOLOv11、文生图、多模态助手、Whisper 语音识别等典型场景。

---
## 9. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 72,095
- **简介**: Editorial diagram design for Claude Code, Codex, GitHub Copilot, Cursor, Factory Droid, Qoder, and Pi. 52 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个面向 AI 编程代理的“技能”插件，让代理用自然语言直接生成自包含 HTML + SVG 的编辑级风格图表，覆盖 52 种图表类型，拒绝 Mermaid 式的粗糙输出。

**核心功能**:
- 用自然语言向代理描述需求（如架构图、四象限图、时序图），代理自动选择图表类型、说明方案并输出单个可双击打开的 `.html` 文件
- 支持 52 种图表类型，涵盖架构、象限、时序等常见场景
- 支持品牌定制：可让代理抓取指定网站的配色与字体，使后续图表风格统一
- 支持从 draw.io、Mermaid、Excalidraw、PlantUML 导入，并导出 PNG / SVG
- 兼容多种代理宿主：Cursor、Claude Code、Codex、GitHub Copilot、Qoder、Gemini CLI、Cline、Windsurf、Amp 等

**技术亮点**: 输出为单文件自包含的 HTML + SVG，无外部依赖；通过 `npx skills add` 或 Claude Code 插件市场安装，支持自动更新；提供构建脚本以适配 Claude Desktop 的 200 文件上传限制；采用 MIT 开源许可。

---
## 10. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 74,252
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个 AI Agent 技能，可跨 Reddit、X、YouTube、HN、Polymarket 等多平台并行检索任意话题，并基于真实用户互动数据合成有据可依的总结。

**核心功能**:
- 多源并行搜索：同时检索 Reddit、X/Twitter、YouTube、Hacker News、Polymarket、TikTok、arXiv、Techmeme、GitHub 及专利/招聘页面等
- 真实互动评分：以 Reddit 点赞、X 喜欢、YouTube 转录、TikTok 互动、Polymarket 真金白银赔率等“人群投票”信号排序，而非编辑推荐
- AI Agent 综合judge：将多平台结果汇总为一份精炼简报
- 零配置开箱即用：Reddit、HN、Polymarket、GitHub 无需配置；一次运行后向导可在 30 秒内解锁 X、YouTube、TikTok、arXiv 等
- 多宿主安装：支持 Claude Code（插件市场自动更新）、Codex、Cursor、Copilot、Gemini CLI 等 50+ Agent Skills 宿主

**技术亮点**: 基于 Python 实现；采用“自带密钥 + 浏览器会话”的方式桥接各平台封闭 API，使 Agent 能聚合多个孤岛平台的数据；通过插件市场与 `npx skills add` 分发，支持全局或按项目安装；运行时规范以 `skills/last30days/SKILL.md` 为唯一事实来源。

---
