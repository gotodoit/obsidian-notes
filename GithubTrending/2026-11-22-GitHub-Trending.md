---
tags:
  - github-trending
  - daily
date: 2026-11-22
created: 2026-11-22T01:55:43.624Z
---

# 2026-11-22 GitHub Trending Top 10

## 1. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- **语言**: Python
- **Stars**: 16,122
- **简介**: A Claude Code skill bundle for bug hunting and external red-team work - 82 skills, 15 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.

### AI 总结
**简介**: Claude-BugHunter 是一个面向漏洞挖掘与外部红队工作的 Claude Code 技能包，将 Claude 从聊天机器人转变为资深漏洞赏金研究员或红队操作员。

**核心功能**:
- **思维框架**：内置 `bb-methodology` 与 `redteam-mindset`，提供五阶段非线性工作流、批判性思维框架和红队操作纪律
- **Web 应用漏洞挖掘**：58 个 `hunt-*` 技能，基于 681 份公开披露的 HackerOne 报告整理，涵盖各类漏洞的检测模式、Payload、绕过表和攻击链模板
- **企业边界突破**：覆盖 M365/Entra、Okta、vCenter、SSL-VPN 设备、SharePoint、云 IAM 等平台的 2024–2026 年 CVE 攻击链及凭据后提权
- **交付与报告**：提供 `triage-validation`、报告撰写和 `evidence-hygiene`，包含 7 问门禁、VRT 感知的严重性评级、OOS 反驳、PII 脱敏和红队交付物
- **自动触发**：用自然语言描述测试目标即可自动加载相关技能，无需按名称调用

**技术亮点**: 采用分层技能架构（思维 → Web 挖掘 → 边界突破 → 交付），集成 Burp MCP 与 HackerOne MCP；支持插件式安装（命名空间隔离、版本更新）或脚本复制安装，附带 `cbh` CLI 和 `hunt` 项目脚手架工具；经过授权红队、漏洞赏金及 DVWA、OWASP Juice Shop 等公开训练平台实战验证。

---
## 2. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 323,757
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，由可组合的技能（skills）和初始指令构建，让智能体自动遵循规范化的开发流程。

**核心功能**:
- **需求澄清与规格设计**：智能体不会直接写代码，而是先退一步询问真实目标，将对话提炼成规格，并以易于消化的短块形式呈现给你确认。
- **实现计划生成**：设计确认后，生成清晰到"缺乏判断力、无项目上下文、厌恶测试的初级工程师"也能执行的实现计划，强调红/绿 TDD、YAGNI 和 DRY。
- **子智能体驱动开发**：说"go"后启动 subagent-driven-development 流程，由多个智能体逐项完成工程任务、检查并审查彼此工作，可持续自主工作数小时而不偏离计划。
- **自动触发**：技能会自动触发，无需额外操作，编码智能体即自然具备 Superpowers 能力。

**技术亮点**:
- 基于 Shell 实现，采用可组合技能（composable skills）架构。
- 广泛适配多种编码智能体平台，包括 Claude Code、Antigravity、Codex App/CLI、Cursor、Devin CLI、Factory Droid、Gemini CLI、GitHub Copilot CLI、Grok Build CLI、Kimi Code、OpenCode、Pi、Qwen Code、Hermes Agent、Muse 等，各平台通过插件市场或扩展方式独立安装。

---
## 3. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 62,099
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: HKUDS/CLI-Anything 是一个 Python 项目，旨在为各类软件生成命令行接口（CLI），让 AI Agent 能够直接调用和操作这些软件，实现“所有软件皆为 Agent 原生”。

**核心功能**:
- 一键为任意软件生成 Agent 可用的 CLI，兼容 Pi、OpenClaw、nanobot、Cursor、Claude Code 等 Agent 工具
- 提供 CLI-Hub 社区中心，可通过 `pip install cli-anything-hub` 后使用 `cli-hub install <name>` 浏览、安装和管理社区构建的 CLI
- 支持预览、实时预览和轨迹循环，让 Agent 产出真实工件（如 CAD 构建、3D 场景、图表、游戏画面、字幕等）
- 开放贡献机制，支持提交新 CLI 构建请求和软件支持愿望清单

**技术亮点**: 基于 Python ≥3.10 和 Click ≥8.0 构建，输出支持 JSON 与人类可读双格式；测试覆盖单元与端到端场景，共有 2,461 项测试通过；采用 Apache 2.0 许可证，并有配套技术报告（arXiv:2606.03854）。

---
## 4. [jingyaogong/minimind](https://github.com/jingyaogong/minimind)
- **语言**: Python
- **Stars**: 68,169
- **简介**: 🧠 两小时从 0 训出你的 64M 大模型。Train your own 64M LLM from scratch in 2 hours.

### AI 总结
**简介**: MiniMind 是一个从零开始训练超小语言模型的开源项目，仅需约 3 元成本和 2 小时即可训练出约 64M 参数的 LLM。

**核心功能**:
- 提供完整的 MiniMind-LLM 结构代码（Dense + MoE），主线结构对齐 Qwen3 / Qwen3-MoE 生态
- 覆盖 Pretrain、SFT、LoRA、RLHF-DPO、RLAIF（PPO / GRPO / CISPO）、Tool Use、Agentic RL、自适应思考与模型蒸馏等完整训练流程
- 提供 Tokenizer 与分词器训练代码，支持 `<tool_call>`、`<tool_response>`、`<think>` 等模板标记
- 提供全阶段开源数据，覆盖收集、蒸馏、清洗与去重后的高质量数据集
- 提供兼容 OpenAI API 协议的极简服务端及基于 Streamlit 的聊天 WebUI
- 支持在 C-Eval、C-MMLU、OpenBookQA 等第三方测评集上评测，支持 YaRN 实现 RoPE 长文本外推
- 拓展视觉模型 MiniMind-V、多模态 Omni 模型 MiniMind-O、扩散语言模型及线性模型

**技术亮点**: 所有核心算法代码均使用 PyTorch 原生从零实现，不依赖第三方高层抽象接口；兼容 `transformers`、`trl`、`peft` 等主流框架及 `llama.cpp`、`vllm`、`ollama` 等推理引擎；支持单机单卡与单机多卡（DDP、DeepSpeed）训练，支持 wandb / swanlab 可视化与动态启停训练；基于 Apache 2.0 协议开源。

---
## 5. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 18,121
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，收录面向主流开发工具、框架和 SaaS 产品的插件，每个插件均为仓库根目录下的独立目录，并带有自己的 `.cursor-plugin/plugin.json` 清单文件。

**核心功能**:
- **开发工具类插件**：提供教学技能映射、持续学习记忆更新、团队 CI/代码审查/发布工作流、深度安全与代码质量审计（Thermos）、新插件脚手架与校验、迭代式 AI 循环（Ralph Loop）、仓库兼容性扫描、面向 Agent 的 CLI 设计模式、PR 差异画布、文档画布、TypeScript SDK 应用构建、Origin API 开发、并行云 Agent 任务编排、严谨 Agent 工作流（pstack/dyl-stack）、决策前咨询更强模型（Advisor）、Grok 语音集成等。
- **生产力类插件**：覆盖 Gmail、Google Drive、Google Calendar、Google Docs、Google Sheets、Google Slides，支持邮件管理、文件读写共享、日程安排与文档表格演示文稿编辑。
- **集成类插件**：Google Ads 广告投放报告与关键词研究、Google Analytics GA4 报告与属性配置、Google Search Console 搜索表现查询与站点地图管理、Gong 账户摘要与通话简报、Salesforce 等第三方 SaaS 集成。

**技术亮点**: 采用 TypeScript 开发；插件以独立目录 + 标准清单文件（`plugin.json`）的模块化结构组织，便于单独分发与维护；部分插件引入并行子 Agent、结构化任务交接、可视化评审画布等 Agent 编排模式。

---
## 6. [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)
- **语言**: TypeScript
- **Stars**: 206,243
- **简介**: Knowledge infrastructure to make your agents smarter. Search, scrape and access 550+ data providers through one API.

### AI 总结
**简介**: Firecrawl 是一套面向 AI Agent 的知识基础设施，通过统一 API 完成网页搜索、抓取与数据访问，支持本地运行、云端托管和自托管三种使用方式。

**核心功能**:
- **网页抓取与转换**：将网站内容转换为干净的 Markdown，支持单页抓取（scrape）、整站爬取（crawl）和 URL 列表映射（map）。
- **本地运行（Firecrawl Local）**：以单二进制形式在本地机器运行，无需数据库、队列或容器，可通过 `cargo install firecrawl-local` 安装。
- **MCP 服务器集成**：通过 `firecrawl-local init` 自动识别并配置 Claude Code、Cursor、Windsurf、Gemini CLI、Codex 等 AI 工具。
- **本地 API 服务**：`serve` 命令在 3002 端口提供 Firecrawl v2 API，兼容现有 SDK，本地路由无需 API Key。
- **云端服务（Firecrawl Cloud）**：提供规模化托管服务，并可通过 Firecrawl Alexandria 接入 550+ 数据提供方。
- **自托管部署**：可从 `apps/api` 部署完整服务器，包含独立的队列、Worker 和数据库。

**技术亮点**: 项目主要使用 TypeScript 开发；本地组件基于 Rust 构建（通过 crates.io 分发），利用本机已有的 Chrome/Chromium 渲染 JavaScript 页面，并在本地解析 PDF 和 Office 文档；提供多语言 SDK，可与本地、云端和自托管三种模式通用。

---
## 7. [nginx/nginx](https://github.com/nginx/nginx)
- **语言**: C
- **Stars**: 32,739
- **简介**: The official NGINX Open Source repository.

### AI 总结
**简介**: NGINX 官方开源仓库，用 C 语言编写的高性能 Web 服务器、反向代理、负载均衡器、API 网关和内容缓存软件。

**核心功能**:
- Web 服务器：处理静态与动态内容请求
- 反向代理与负载均衡：高性能转发与流量分发
- API 网关：统一入口管理后端服务
- 内容缓存：加速内容分发
- 模块化架构：通过静态或动态模块扩展功能
- 支持 TLS/SSL 加密、限流等配置能力

**技术亮点**: 采用 C 语言开发，模块化设计（静态/动态模块可编译或运行时加载）；提供 Stable 与 Mainline 双版本二进制包，覆盖主流 Linux、FreeBSD、Windows 平台；采用简化版 2-clause BSD 类许可证开源，企业版与商业支持由 F5 提供。

---
## 8. [openvinotoolkit/openvino](https://github.com/openvinotoolkit/openvino)
- **语言**: C++
- **Stars**: 11,941
- **简介**: OpenVINO™ is an open source toolkit for optimizing and deploying AI inference

### AI 总结
**简介**: OpenVINO™ 是 Intel 开源的深度学习推理优化与部署工具包，主要使用 C++ 开发，支持从边缘到云端的 AI 模型高效推理。

**核心功能**:
- **推理优化**：提升计算机视觉、语音识别、生成式 AI、自然语言处理（含大/小语言模型）等任务的深度学习性能
- **灵活模型支持**：兼容 PyTorch、TensorFlow、ONNX、Keras、PaddlePaddle、JAX/Flax 等框架训练的模型，并可通过 Optimum Intel 直接集成 Hugging Face Hub 上的 transformers 与 diffusers 模型，无需原始框架即可转换部署
- **广泛平台兼容**：支持在 CPU（x86、ARM）、GPU（Intel 集成与独立显卡）及 AI 加速器（Intel NPU）上推理，降低资源需求
- **多语言分发**：提供 PyPI、NPM、Anaconda、Homebrew 等安装渠道，支持 Python、C++ 等开发方式
- **丰富教程生态**：提供 OpenVINO Notebooks 示例，涵盖 LLM 聊天机器人、YOLOv11 优化、文生图、LLaVa 多模态助手、Whisper 语音识别等场景

**技术亮点**: 基于 C++ 实现的高性能推理引擎；支持跨异构硬件（CPU/GPU/NPU）部署；提供模型转换与量化优化能力；配套 Generative AI 专项仓库（openvino.genai）及完整文档、基准测试与社区生态。

---
## 9. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 69,821
- **简介**: Editorial diagram design for Claude Code, Codex, GitHub Copilot, Cursor, Factory Droid, Qoder, and Pi. 45 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个面向 AI 编码代理的图表设计技能，能将自然语言需求生成为单文件 HTML + SVG 的编辑级图表，覆盖 51 种图表类型，主打无阴影、拒绝 Mermaid 式粗糙风格。

**核心功能**:
- 支持 51 种图表类型，由代理自动选择类型并说明方案，最终输出可双击打开的自包含 `.html` 文件
- 适配 Claude Code、Cursor、Codex、GitHub Copilot、Qoder、Gemini CLI、Cline、Windsurf、Amp 等多种 Agent Skills 宿主
- 通过 `npx skills add cathrynlavery/diagram-design` 一键安装，Claude Code 另支持插件市场安装与自动更新
- 品牌定制：可将图表接入指定网站，自动提取配色与字体，使后续图表风格统一
- 支持从 draw.io、Mermaid、Excalidraw、PlantUML 导入，并可导出 PNG / SVG

**技术亮点**: 纯 HTML + SVG 实现，零外部依赖的单文件输出；跨代理的 `skills` CLI 安装机制支持符号链接统一管理多宿主；采用 MIT 开源协议。

---
## 10. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 72,028
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个 AI Agent 技能，能跨 Reddit、X、YouTube、HN、Polymarket 等多个平台并行研究任意话题，并按真实用户互动（点赞、投票、真金白银）评分后合成一份有据可依的摘要。

**核心功能**:
- **多平台并行搜索**：同时检索 Reddit、X/Twitter、YouTube、Hacker News、Polymarket、TikTok、arXiv、Techmeme、专利与招聘页面等来源，突破单一 AI 平台的封闭生态。
- **按真实互动评分**：以 Reddit 点赞、X 喜欢、YouTube 字幕、TikTok 互动量、Polymarket 赔率等真实用户注意力与资金信号作为排序依据，而非编辑推荐。
- **AI Agent 综合摘要**：由 AI Agent 作为裁判，将各平台结果交叉比对后合成为一份简明的 grounded 摘要。
- **零配置快速上手**：Reddit、HN、Polymarket、GitHub 开箱即用；通过 30 秒配置向导可解锁 X、YouTube、TikTok、arXiv 等更多来源。
- **多宿主安装**：支持 Claude Code 插件市场安装，也可通过 `npx skills add` 用于 Codex、Cursor、Copilot、Gemini CLI 等 50+ Agent Skills 宿主。

**技术亮点**: 使用 Python 实现；采用"自带密钥/浏览器会话"（BYOK）模式桥接各平台独立 API 与鉴权；以 Agent Skill 规范（skills/last30days/SKILL.md）作为命令与配置的唯一事实来源，并提供多语言 README 与 CI 校验流程。

---
