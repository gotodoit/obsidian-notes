---
tags:
  - github-trending
  - daily
date: 2026-11-24
created: 2026-11-24T01:55:44.205Z
---

# 2026-11-24 GitHub Trending Top 10

## 1. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- **语言**: Python
- **Stars**: 19,846
- **简介**: A Claude Code skill bundle for bug hunting and external red-team work - 84 skills, 15 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.

### AI 总结
**简介**: Claude-BugHunter 是一个面向漏洞挖掘与外部红队工作的 Claude Code 技能包，内置 84 个技能、15 个斜杠命令，覆盖 24 类核心漏洞的 681 条已披露报告模式，并附带企业身份与基础设施攻击矩阵。

**核心功能**:
- **思维框架**：通过 `bb-methodology` 与 `redteam-mindset` 提供五阶段非线性工作流、批判性思维框架和红队操作纪律。
- **Web 应用狩猎**：58 个 `hunt-*` 技能，源自 681 份 HackerOne 披露报告，涵盖各类漏洞的检测模式、Payload、绕过表和利用链模板。
- **外围攻击**：企业平台攻击链（M365/Entra、Okta、vCenter、SSL-VPN 设备、SharePoint、云 IAM），包含 2024–2026 年 CVE 链及凭据后提权路径。
- **交付与报告**：`triage-validation` 结合报告输出与 `evidence-hygiene`，提供七问门禁、VRT 感知的严重性评级、OOS 反驳、PII 脱敏及红队交付物。
- **自动触发**：用自然语言描述测试目标即可自动加载对应技能，无需按名称调用。

**技术亮点**: 基于 Claude Code 技能系统实现，支持插件市场安装（`/plugin marketplace add`）或脚本复制安装（bash/PowerShell）；集成 Burp MCP 与 HackerOne MCP（可选 API 凭据）；提供独立的 `cbh` CLI（可通过 pipx 安装）和 `hunt` 项目脚手架工具；已在授权红队、漏洞挖掘及 DVWA、OWASP Juice Shop、Hacker101 等公开训练平台验证。项目以 Python 编写。

---
## 2. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 325,110
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，由可组合的技能（skills）与初始指令构成，让智能体自动遵循规范化的开发流程。

**核心功能**:
- 需求澄清：智能体不会直接写代码，而是先退一步询问用户的真实目标，并从对话中提炼出规格说明，分块展示以便阅读和确认。
- 实现计划：设计确认后生成清晰的实现计划，强调红/绿 TDD、YAGNI 和 DRY 原则。
- 子智能体驱动开发：用户确认后启动子智能体逐项完成工程任务，自动检查与评审工作成果，可长时间自主推进而不偏离计划。
- 自动触发：技能会自动激活，用户无需额外操作即可让编码智能体具备 Superpowers 能力。
- 多平台支持：提供 Claude Code、Antigravity、Codex App/CLI、Cursor、Devin CLI、Factory Droid、Gemini CLI、GitHub Copilot CLI、OpenCode、Qwen Code 等多种智能体环境的安装方式。

**技术亮点**: 以 Shell 实现，采用可组合技能架构；技能描述可引导模型在对话开始时自动加载；支持通过插件市场、扩展或 CLI 命令灵活安装与更新；面向企业用户提供商业支持服务。

---
## 3. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 63,701
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: CLI-Anything 是香港大学数据科学实验室（HKUDS）开源的项目，旨在为各类软件自动生成 Agent 可调用的命令行接口（CLI），让 AI Agent 能够直接操作现实世界中的软件。

**核心功能**:
- **一键生成 CLI**：为任意软件生成 Agent 可用的命令行封装，兼容 Pi、OpenClaw、nanobot、Cursor、Claude Code 等主流 Agent 工具
- **CLI-Hub 社区仓库**：通过 `pip install cli-anything-hub` 安装后，可用 `cli-hub install <name>` 浏览、安装和管理社区贡献的 CLI，也支持提交 PR 添加自己的 CLI
- **真实场景演示**：提供 18 个应用的 Demo，展示 AI Agent 借助生成的 CLI 完成 CAD 建模、3D 场景、图表、游戏逻辑、字幕等实际产物
- **社区共建机制**：支持贡献者报名构建新 CLI harness，以及提交软件/服务的 wishlist 需求

**技术亮点**: 基于 Python（≥3.10）与 Click 框架构建，输出同时支持 JSON 与人类可读格式；测试体系覆盖单元与端到端，共 2,461 项测试通过；提供技术报告（arXiv:2606.03854），采用 Apache 2.0 许可，并配有中、日、德多语言文档。

---
## 4. [jingyaogong/minimind](https://github.com/jingyaogong/minimind)
- **语言**: Python
- **Stars**: 69,502
- **简介**: 🧠 两小时从 0 训出你的 64M 大模型。Train your own 64M LLM from scratch in 2 hours.

### AI 总结
**简介**: MiniMind 是一个从零开始、仅需约 2 小时和 3 元 GPU 成本即可训练出 64M 超小语言模型的开源项目，同时提供完整的大模型训练链路代码与教程。

**核心功能**:
- 提供完整的 MiniMind-LLM 结构代码（Dense + MoE），主线结构对齐 Qwen3 / Qwen3-MoE 生态
- 覆盖 Pretrain、SFT、LoRA、RLHF-DPO、RLAIF（PPO / GRPO / CISPO）、Tool Use、Agentic RL、自适应思考与模型蒸馏等全流程训练代码
- 提供 Tokenizer 训练代码，支持 `<tool_call>`、`<tool_response>`、`<think>` 等模板标记
- 开源全阶段高质量数据集（收集、蒸馏、清洗、去重）
- 提供兼容 OpenAI API 协议的极简服务端与基于 Streamlit 的聊天 WebUI
- 支持 C-Eval、C-MMLU、OpenBookQA 等第三方测评集评测，及 YaRN 长文本外推

**技术亮点**:
- 所有核心算法与关键模块均使用 PyTorch 原生从 0 实现，不依赖第三方高层抽象接口
- 兼容 transformers、trl、peft 等主流框架，以及 llama.cpp、vllm、ollama、Llama-Factory 等推理/训练生态
- 支持单机单卡与多卡（DDP、DeepSpeed）训练，支持 wandb / swanlab 可视化与动态启停训练
- 模型体积极其轻量，主线最小版本约为 GPT-3 的 1/2700，普通个人 GPU 即可完成训练与复现
- 拓展了视觉模型 MiniMind-V、多模态 Omni 模型 MiniMind-O、扩散语言模型与线性模型等衍生方向

---
## 5. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 18,828
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，提供面向主流开发工具、框架和 SaaS 产品的插件规范与官方插件集合，每个插件均为独立目录并带有 `.cursor-plugin/plugin.json` 清单。

**核心功能**:
- **开发工具类插件**：涵盖教学辅助（Teaching）、持续学习记忆更新（Continual Learning）、团队协作工作流（Cursor Team Kit）、深度代码审查（Thermos）、插件脚手架（Create Plugin）、迭代式 AI 循环（Ralph Loop）、仓库兼容性扫描（Agent Compatibility）、CLI 设计模式（CLI for Agents）、PR 差异画布（PR Review Canvas）、文档画布（Docs Canvas）、TypeScript SDK 应用构建（Cursor SDK）、Origin API 开发（Origin Apps）、并行云代理编排（Orchestrate）、高质量编码工作流（pstack、dyl-stack）、决策咨询（Advisor）及语音集成（Grok Voice）等。
- **生产力类插件**：集成 Gmail、Google Drive、Google Calendar、Google Docs、Google Sheets、Google Slides，支持邮件管理、文件读写共享、日程安排和文档编辑。
- **集成类插件**：接入 Google Ads、Google Analytics、Google Search Console、Gong、Salesforce 等，支持广告投放报告、GA4 分析、搜索表现查询和销售数据洞察。

**技术亮点**: 采用 TypeScript 开发；插件以独立目录形式组织，统一通过 `.cursor-plugin/plugin.json` 清单声明元数据；支持并行子代理、结构化交接、画布渲染等 Agent 编排能力，并提供脚手架工具用于快速创建和校验新插件。

---
## 6. [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)
- **语言**: TypeScript
- **Stars**: 207,972
- **简介**: Knowledge infrastructure to make your agents smarter. Search, scrape and access 550+ data providers through one API.

### AI 总结
**简介**: Firecrawl 是一套面向 AI Agent 的知识基础设施，可将网站内容抓取并转换为干净的 Markdown，通过统一 API 完成搜索、抓取并接入 550+ 数据提供方。

**核心功能**:
- **Firecrawl Local**：以单个二进制文件在本地运行，支持 scrape、crawl、map，无需数据库、队列或容器
- **Firecrawl Cloud**：托管服务，提供本地版全部能力的规模化版本，并额外支持搜索和 Alexandria 数据提供方
- **自托管部署**：从 `apps/api` 部署完整服务端，包含独立队列、worker 和数据库
- **MCP 集成**：通过 `init` 自动将 Firecrawl Local 注册为 Claude Code、Cursor、Windsurf、Gemini CLI、Codex 等工具的 MCP 服务器
- **本地 API 服务**：`serve` 在 3002 端口提供 Firecrawl v2 API，现有 SDK 代码可直接对接
- **多格式解析**：支持 JavaScript 渲染页面（复用本地 Chrome/Chromium）、PDF 和 Office 文档

**技术亮点**: 主要使用 TypeScript 开发；提供 Rust 编写的本地二进制（`cargo install firecrawl-local`）及 Node.js 22+ 的 MCP 服务；同时提供 Python 等语言的 SDK，可通过自定义 API URL 连接本地或云端实例。

---
## 7. [nginx/nginx](https://github.com/nginx/nginx)
- **语言**: C
- **Stars**: 33,065
- **简介**: The official NGINX Open Source repository.

### AI 总结
**简介**: NGINX 官方开源仓库，全球最流行的 Web 服务器、高性能负载均衡器、反向代理、API 网关和内容缓存软件。

**核心功能**:
- **Web 服务器**：提供高性能的静态内容服务与 HTTP 处理能力
- **负载均衡**：支持多种策略将流量分发至后端服务器
- **反向代理 / API 网关**：统一入口转发请求，支持 TLS 加密
- **内容缓存**：缓存后端响应以降低延迟、减轻源站压力
- **速率限制**：控制请求频率，防止滥用
- **模块化架构**：通过静态或动态模块扩展功能，可用 `nginx -V` 查看已编译模块

**技术亮点**: 使用 C 语言开发，采用模块化设计（静态/动态模块）；以简化版 2-clause BSD 许可证开源；提供 Stable 与 Mainline 双版本二进制包，覆盖主流 Linux 发行版、FreeBSD 与 Windows；企业版发行、商业支持与培训由 F5 提供。

---
## 8. [openvinotoolkit/openvino](https://github.com/openvinotoolkit/openvino)
- **语言**: C++
- **Stars**: 12,291
- **简介**: OpenVINO™ is an open source toolkit for optimizing and deploying AI inference

### AI 总结
**简介**: OpenVINO™ 是 Intel 开源的深度学习推理优化与部署工具包，帮助开发者将训练好的模型高效部署到从边缘到云端的多种硬件平台。

**核心功能**:
- **推理优化**：提升计算机视觉、语音识别、生成式 AI、自然语言处理（含大小语言模型）等任务的深度学习性能
- **灵活模型支持**：兼容 PyTorch、TensorFlow、ONNX、Keras、PaddlePaddle、JAX/Flax 等框架训练的模型，并可通过 Optimum Intel 直接集成 Hugging Face Hub 上的 transformers 和 diffusers 模型，无需原始框架即可转换部署
- **广泛平台兼容**：支持在 CPU（x86、ARM）、GPU（Intel 集成与独立显卡）及 AI 加速器（Intel NPU）上推理，降低资源需求
- **活跃社区生态**：提供文档、教程、Notebooks、示例代码及多语言发行包（PyPI、NPM、Anaconda、Homebrew）

**技术亮点**: 以 C++ 实现核心，提供 Python 等多种语言接口；支持模型转换与跨平台推理部署；配套 OpenVINO Notebooks 提供 LLM 聊天机器人、YOLOv11 优化、文生图、LLaVa 多模态助手、Whisper 语音识别等实战示例。

---
## 9. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 71,013
- **简介**: Editorial diagram design for Claude Code, Codex, GitHub Copilot, Cursor, Factory Droid, Qoder, and Pi. 52 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个面向 AI 编程助手（Claude Code、Cursor、GitHub Copilot 等）的 Agent 技能，通过自然语言指令生成品牌化的自包含 HTML + SVG 图表，支持 52 种图表类型。

**核心功能**:
- 支持 52 种图表类型，涵盖架构图、象限图、时序图等常见场景
- 用自然语言描述需求即可生成图表，Agent 自动选择图表类型并输出单个可双击打开的 `.html` 文件
- 品牌定制：可抓取指定网站的配色与字体，使所有图表与品牌风格一致
- 支持从 draw.io、Mermaid、Excalidraw、PlantUML 导入，可导出 PNG / SVG
- 兼容多种 Agent 宿主，通过 `npx skills add` 一键安装，Claude Code 支持插件市场与自动更新

**技术亮点**: 输出为自包含的 HTML + SVG 单文件，无外部依赖；强调"编辑级"设计美学（无阴影、拒绝 Mermaid 式粗糙风格）；项目以 HTML 为主要语言，采用 MIT 许可证。

---
## 10. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 73,464
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个 AI agent 技能，可并行搜索 Reddit、X、YouTube、HN、Polymarket 等多个平台，并按真实用户互动（点赞、投票、真金白银）打分，最终由 AI 综合成一份有依据的摘要。

**核心功能**:
- 跨平台并行搜索：覆盖 Reddit、X/Twitter、YouTube、Hacker News、Polymarket、GitHub、arXiv、TikTok、Techmeme 及网页等来源
- 按真实互动排序：以 Reddit 点赞、X 喜欢、YouTube 转录、Polymarket 赔率等真实参与度作为评分依据，而非编辑推荐
- AI 综合摘要：由 agent 判定并整合多源信息，输出单一简报
- 零配置上手：Reddit、HN、Polymarket、GitHub 开箱即用，运行一次后向导可在 30 秒内解锁其余平台
- 多宿主安装：支持 Claude Code 插件市场，以及 Codex、Cursor、Copilot、Gemini CLI 等 50+ Agent Skills 宿主

**技术亮点**: 基于 Python 实现；采用"自带密钥 + 浏览器会话"方式桥接各平台封闭 API；通过 agent 并行检索与交叉评分，解决单一 AI 无法同时访问多平台数据的问题。

---
