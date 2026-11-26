---
tags:
  - github-trending
  - daily
date: 2026-11-26
created: 2026-11-26T01:55:43.873Z
---

# 2026-11-26 GitHub Trending Top 10

## 1. [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- **语言**: Python
- **Stars**: 23,086
- **简介**: A Claude Code skill bundle for bug hunting and external red-team work - 85 skills, 16 slash commands, 681 disclosed-report patterns curated across 24 core vulnerability classes, plus enterprise identity + infrastructure attack matrices.

### AI 总结
**简介**: Claude-BugHunter 是一个面向漏洞挖掘与外部红队工作的 Claude Code 技能包，将 Claude 从聊天机器人转变为具备实战经验的高级漏洞研究员或红队操作员。

**核心功能**:
- **思维框架**：包含 `bb-methodology` 与 `redteam-mindset`，提供五阶段非线性工作流、批判性思维框架及红队操作纪律
- **Web 应用漏洞挖掘**：58 个 `hunt-*` 技能，基于 681 份公开 HackerOne 报告整理，涵盖各类漏洞的检测模式、Payload、绕过技巧表与利用链模板
- **边界资产攻击**：针对企业平台（M365/Entra、Okta、vCenter、SSL-VPN 设备、SharePoint、云 IAM）提供 2024–2026 年 CVE 利用链及获取凭据后的提权路径
- **成果交付**：`triage-validation`、报告生成与 `evidence-hygiene`，包含 7-Question Gate、VRT 感知严重性评级、OOS 反驳、PII 脱敏及红队交付物
- **自动触发**：用自然语言描述测试目标即可自动加载相关技能，无需按名称调用
- **配套工具**：`cbh` 命令行运行器、`hunt` 项目目录脚手架、Burp MCP 集成、HackerOne MCP（可选，用于读取私有项目与个人报告）

**技术亮点**: 基于 Claude Code 技能系统构建，采用四层架构（思考 → Web 漏洞挖掘 → 边界攻击 → 成果交付）；提供插件市场安装与脚本复制安装两种方式；85 个技能与 16 个斜杠命令按命名空间加载；已在授权红队项目及 DVWA、OWASP Juice Shop、Hacker101 等公开训练平台验证。

---
## 2. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 326,643
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码智能体的完整软件开发方法论，基于可组合的技能（skills）和初始指令构建，让智能体自动遵循规范化的开发流程。

**核心功能**:
- **需求澄清**：智能体不会直接写代码，而是先退一步询问用户的真实目标，并从对话中提炼出规格说明，分块展示以便阅读和消化。
- **实现计划**：设计确认后生成清晰的实现计划，强调真正的红/绿 TDD、YAGNI 和 DRY 原则。
- **子智能体驱动开发**：用户确认后启动子智能体逐项完成工程任务，自动检查与审查工作成果，可长时间自主推进而不偏离计划。
- **自动触发**：技能自动生效，无需额外操作，智能体即具备 Superpowers 能力。
- **多平台支持**：提供 Claude Code、Codex、Cursor、Gemini CLI、GitHub Copilot CLI、Qwen Code 等多种编码工具的安装方式。

**技术亮点**: 以 Shell 为主要语言；采用可组合技能（composable skills）架构，通过初始指令确保智能体自动加载并调用技能；支持通过插件市场或命令行一键安装，适配十余种主流编码智能体平台。

---
## 3. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 65,711
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: CLI-Anything 是香港大学数据科学实验室（HKUDS）开源的项目，旨在通过自动生成命令行接口（CLI），让各类软件原生支持 AI Agent 调用，打通 AI Agent 与现有软件生态之间的鸿沟。

**核心功能**:
- **一键生成 CLI**：只需一条命令，即可为任意软件生成可供 Pi、OpenClaw、nanobot、Cursor、Claude Code 等 AI Agent 直接调用的 CLI 封装。
- **CLI-Hub 社区中心**：通过 `pip install cli-anything-hub` 安装后，可用 `cli-hub install <name>` 浏览、安装和管理社区贡献的 CLI 工具，支持即时 PR 合并更新。
- **预览与轨迹循环**：AI Agent 可借助生成的 CLI 配合预览、实时预览和轨迹循环，产出 CAD 构建、3D 场景、图表、游戏玩法、字幕等真实制品。
- **社区共建机制**：支持贡献者注册新 CLI harness、提交软件/服务愿望清单（wishlist），以及提出新技能（如 Hermes skill）和注册表扩展（如 ArcGIS Pro）。

**技术亮点**: 基于 Python（≥3.10）开发，使用 Click 构建命令行界面，Pytest 实现 100% 通过率并覆盖单元与端到端测试；输出同时支持 JSON 与人类可读格式；项目采用 Apache 2.0 协议，配有技术报告（arXiv:2606.03854），并提供中文、日文、德文多语言文档。

---
## 4. [jingyaogong/minimind](https://github.com/jingyaogong/minimind)
- **语言**: Python
- **Stars**: 70,996
- **简介**: 🧠 两小时从 0 训出你的 64M 大模型。Train your own 64M LLM from scratch in 2 hours.

### AI 总结
**简介**: MiniMind 是一个从零开始训练超小语言模型（约 64M 参数）的开源项目，最低仅需约 3 元 GPU 成本和 2 小时训练时间，即可在普通个人 GPU 上完成训练与复现。

**核心功能**:
- 提供完整的 MiniMind-LLM 结构代码（Dense + MoE），主线结构对齐 Qwen3 / Qwen3-MoE 生态
- 覆盖 Pretrain、SFT、LoRA、RLHF-DPO、RLAIF（PPO / GRPO / CISPO）、Tool Use、Agentic RL、自适应思考与模型蒸馏等完整训练链路
- 提供 Tokenizer 与分词器训练代码，支持 `<tool_call>`、`<tool_response>`、`<think>` 等模板标记
- 开源全阶段高质量数据集（收集、蒸馏、清洗、去重）
- 提供兼容 OpenAI API 协议的极简服务端及基于 Streamlit 的聊天 WebUI
- 支持 C-Eval、C-MMLU、OpenBookQA 等第三方测评集评测及 YaRN 长文本外推
- 拓展视觉、多模态 Omni、扩散语言模型、线性模型等衍生项目

**技术亮点**: 所有核心算法与关键模块均使用 PyTorch 原生从零实现，不依赖第三方高层抽象接口；兼容 transformers / trl / peft 及 llama.cpp、vllm、ollama 等推理引擎；支持单机单卡与多卡（DDP、DeepSpeed）训练，支持 wandb / swanlab 可视化与动态启停训练；采用 Apache 2.0 协议完全开源免费。

---
## 5. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 19,540
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，收录面向主流开发工具、框架和 SaaS 产品的插件，每个插件为独立目录并带有 `.cursor-plugin/plugin.json` 清单。

**核心功能**:
- 提供开发工具类插件，如代码审查（Thermos、PR Review Canvas）、任务并行编排（Orchestrate）、CLI 设计规范（CLI for Agents）、插件脚手架（Create Plugin）等
- 提供生产力与集成类插件，覆盖 Gmail、Google Drive/Calendar/Docs/Sheets/Slides、Google Ads/Analytics/Search Console、Gong、Salesforce 等服务
- 提供 Cursor SDK，支持用 TypeScript 构建应用、脚本和自动化
- 提供学习与工作流类插件，如 Teaching、Continual Learning、Cursor Team Kit

**技术亮点**: 基于 TypeScript 开发；采用"根目录独立插件 + 统一 manifest"的模块化架构，便于插件独立维护与市场分发。

---
## 6. [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)
- **语言**: TypeScript
- **Stars**: 210,088
- **简介**: Knowledge infrastructure to make your agents smarter. Search, scrape and access 550+ data providers through one API.

### AI 总结
**简介**: Firecrawl 是一套面向 AI Agent 的知识基础设施，通过统一 API 将网站内容转为干净的 Markdown，并整合搜索与 550+ 数据源，让 Agent 更智能。

**核心功能**:
- **网页抓取与转换**：将网页抓取为干净的 Markdown，支持 PDF 与 Office 文档解析
- **站点爬取与映射**：`crawl` 按站点批量抓取并逐页保存，`map` 列出站点所有 URL
- **MCP 服务器集成**：通过 `init` 自动为 Claude Code、Cursor、Windsurf、Gemini CLI、Codex 等 AI 工具配置为 MCP 服务器
- **本地 API 服务**：`serve` 在 localhost:3002 提供 Firecrawl v2 API，兼容现有 SDK
- **云端扩展能力**：Firecrawl Cloud 提供结构化 JSON、Interact、Agent 及 Alexandria 的 550+ 数据源搜索

**技术亮点**: 项目以 TypeScript 为主，同时提供 Rust 实现的本地二进制（`cargo install firecrawl-local`）；支持三种部署形态——本地单二进制运行（无需数据库/队列/容器）、云端托管、以及基于 `apps/api` 的自托管（含队列、Worker 与数据库）；借助本机 Chrome/Chromium 渲染 JS 页面，无浏览器时静态页面仍可抓取。

---
## 7. [nginx/nginx](https://github.com/nginx/nginx)
- **语言**: C
- **Stars**: 33,381
- **简介**: The official NGINX Open Source repository.

### AI 总结
**简介**: NGINX 官方开源仓库，用 C 语言编写的高性能 Web 服务器、负载均衡器、反向代理、API 网关和内容缓存软件。

**核心功能**:
- Web 服务器：处理 HTTP/HTTPS 请求，支持静态内容服务
- 负载均衡：在多个后端服务器之间分发流量
- 反向代理与 API 网关：转发客户端请求至上游服务
- 内容缓存：缓存响应内容以提升性能
- 模块化架构：通过静态或动态模块扩展功能
- 支持 SSL/TLS 加密、速率限制等配置能力

**技术亮点**: 采用 C 语言开发，模块化设计（静态/动态模块），基于 BSD 2-Clause 许可证开源，提供稳定版与主线版二进制包，支持 Linux、FreeBSD、Windows 等多平台，并支持从源码编译定制构建。

---
## 8. [openvinotoolkit/openvino](https://github.com/openvinotoolkit/openvino)
- **语言**: C++
- **Stars**: 12,662
- **简介**: OpenVINO™ is an open source toolkit for optimizing and deploying AI inference

### AI 总结
**简介**: OpenVINO™ 是 Intel 推出的开源工具包，用于优化和部署深度学习模型推理，支持从边缘到云的多种平台。

**核心功能**:
- **推理优化**：提升计算机视觉、语音识别、生成式 AI、自然语言处理（含大/小语言模型）等任务的深度学习性能
- **灵活模型支持**：兼容 PyTorch、TensorFlow、ONNX、Keras、PaddlePaddle、JAX/Flax 训练的模型，并可通过 Optimum Intel 直接集成 Hugging Face Hub 的 transformers 与 diffusers 模型，无需原始框架即可转换部署
- **广泛平台兼容**：支持 CPU（x86、ARM）、GPU（Intel 集成与独立显卡）及 AI 加速器（Intel NPU）推理，降低资源需求
- **活跃社区生态**：提供文档、教程、Notebook 示例（如 LLM 聊天机器人、YOLOv11 优化、文生图、LLaVa 多模态、Whisper 语音识别）及 Python/C++ 示例

**技术亮点**: 主要使用 C++ 开发；提供 pip、NPM、Anaconda、Homebrew 等多渠道安装方式；配套 OpenVINO Notebooks 与 Generative AI 相关仓库，便于快速上手与生成式 AI 部署。

---
## 9. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 73,070
- **简介**: Editorial diagram design for Claude Code, Codex, GitHub Copilot, Cursor, Factory Droid, Qoder, and Pi. 52 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个面向 AI 编程助手（Claude Code、Codex、GitHub Copilot、Cursor 等）的图表生成技能，可将自然语言需求转成单文件 HTML + SVG 的编辑级图表。

**核心功能**:
- 支持 52 种图表类型，涵盖架构图、象限图、时序图等常见场景
- 用户用自然语言描述需求，代理自动选择图表类型、说明方案并生成可双击打开的 `.html` 文件
- 支持品牌定制：可抓取指定网站的配色与字体，使生成的图表与品牌风格一致
- 支持从 draw.io、Mermaid、Excalidraw、PlantUML 导入，并可导出为 PNG / SVG
- 通过 `npx skills add` 一条命令安装，兼容多种 Agent Skills 宿主

**技术亮点**: 输出为自包含的 HTML + SVG 单文件，不依赖外部资源；设计上强调编辑级质感（无阴影、拒绝 Mermaid 式的粗糙风格）；以 Agent Skill 形式分发，并提供 Claude Code 插件市场安装与自动更新机制。

---
## 10. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 75,136
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个由 AI agent 驱动的跨平台搜索引擎，聚合 Reddit、X、YouTube、HN、Polymarket 等平台内容，按真实用户互动数据打分并生成有据可依的摘要。

**核心功能**:
- 并行搜索多个平台（Reddit、X/Twitter、YouTube、TikTok、Hacker News、Polymarket、arXiv、Techmeme、GitHub、专利与招聘页面等），突破各平台数据孤岛
- 按真实用户行为（Reddit 点赞、X 喜欢、Polymarket 真金白银的赔率、YouTube 转录、TikTok 互动）打分排序，而非编辑推荐
- 由 AI agent 裁判综合多源信息，输出一份整合后的简要报告
- 零配置即可使用 Reddit、HN、Polymarket、GitHub 等源；运行一次后通过设置向导可快速解锁 X、YouTube、TikTok、arXiv 等更多来源
- 支持 Claude Code 插件市场安装，也兼容 Codex、Cursor、Copilot、Gemini CLI 等 50+ Agent Skills 宿主（通过 `npx skills add`）

**技术亮点**: 基于 Python 实现；采用多平台并行检索 + 用户互动数据加权评分 + AI agent 综合判定的流水线架构；通过用户自带 API 密钥和浏览器会话桥接各平台墙；运行时技能规范以 `skills/last30days/SKILL.md` 为准，支持自动更新。

---
