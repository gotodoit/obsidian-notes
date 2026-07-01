---
tags:
  - github-trending
  - daily
date: 2026-07-01
created: 2026-07-01T01:55:45.610Z
---

# 2026-07-01 GitHub Trending Top 10

## 1. [hasaneyldrm/exercises-dataset](https://github.com/hasaneyldrm/exercises-dataset)
- **语言**: HTML
- **Stars**: 6,758
- **简介**: A comprehensive dataset of 433 fitness exercises. Each entry includes name, category, target muscle group, equipment, instructions, thumbnail image, and animation video.

### AI 总结
**简介**: 一个包含1324项健身运动的结构化多语言数据集，并附带开发者脚手架工具，用于快速构建健身应用后端。

**核心功能**:
- **结构化数据集**: 提供1324项健身运动的JSON数据，包含名称、类别、目标肌肉群、所需器械、分步指导等字段。
- **多语言支持**: 指导说明支持英语、西班牙语、意大利语、土耳其语、俄语和中文6种语言。
- **交互式浏览器**: 提供`index.html`文件，可离线在浏览器中搜索、筛选和浏览所有运动项目的元数据与多语言指导。
- **开发者设置向导**: 提供`setup.html`文件，引导开发者完成数据库模式设计、API代码生成和LLM提示词构建等步骤。

**技术亮点**:
- **纯前端工具**: 交互式浏览器和设置向导均为纯HTML文件，无需服务器，直接在浏览器中运行。
- **结构化JSON数据**: 数据以标准JSON格式存储，易于集成到任何应用或机器学习项目中。
- **数据来源与扩展**: 基于ExerciseDB v1数据集，并额外添加了5种语言的翻译和格式化清理。

---
## 2. [usestrix/strix](https://github.com/usestrix/strix)
- **语言**: Python
- **Stars**: 28,167
- **简介**: Open-source AI penetration testing tool to find and fix your app’s vulnerabilities.

### AI 总结
**简介**: Strix 是一个开源的 AI 渗透测试工具，能够像真实黑客一样动态运行你的代码，自动发现并验证应用漏洞，同时提供修复建议。  
**核心功能**:  
- **全栈渗透测试工具集**：内置侦察、漏洞利用和验证能力，开箱即用。  
- **多智能体协作**：多个 AI 渗透测试代理协同工作，可扩展测试规模。  
- **真实漏洞验证**：生成可工作的概念验证（PoC），避免误报。  
- **开发者友好 CLI**：提供可操作的漏洞发现和修复指导。  
- **自动修复与报告**：自动生成安全补丁和合规性渗透测试报告。  
- **CI/CD 集成**：无缝对接 GitHub Actions 等流水线，在每次提交时自动扫描并阻止不安全代码。  
**技术亮点**:  
- 基于 Python 开发，依赖 Docker 沙箱环境运行。  
- 支持多种 LLM 提供商（如 OpenAI、Anthropic、Google 等）作为 AI 驱动引擎。  
- 提供云端平台（app.strix.ai）实现持续渗透测试、一键自动修复和 DevSecOps 集成（GitHub、GitLab、Slack 等）。

---
## 3. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 120,999
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个开箱即用的 AI 专家代理集合，每个代理都拥有独特的个性、专业领域和可交付成果，可集成到多种开发工具中。  
**核心功能**:  
- **多样化专家代理**: 提供覆盖工程、安全、设计、内容创作等领域的 16+ 个团队，每个代理都有明确的身份、工作流和产出标准。  
- **一键集成**: 通过桌面应用或脚本，可将代理安装到 Claude Code、Cursor、Gemini CLI、OpenCode 等主流 AI 开发工具中。  
- **灵活安装**: 支持按工具、按团队、按单个代理进行选择性安装，并自动处理工具兼容性。  
- **交互式向导**: 提供交互式安装脚本，自动检测已安装的工具并引导用户选择所需代理。  
**技术亮点**:  
- **Shell 脚本驱动**: 所有安装、转换和集成逻辑均基于 Shell 脚本实现，轻量且跨平台。  
- **多工具兼容**: 原生支持 10+ 种 AI 开发工具，并提供统一的代理格式转换接口。  
- **自动化更新**: 桌面应用支持自动更新，确保代理列表始终保持最新。

---
## 4. [altic-dev/FluidVoice](https://github.com/altic-dev/FluidVoice)
- **语言**: Swift
- **Stars**: 4,944
- **简介**: Fastest and only macOS Dictation app with on-device STT and custom trained AI enhancement model - Local Wispr Flow alternative. One ⭐ takes us a long way :)) Windows, iOS and Linux coming soon.

### AI 总结
**简介**: FluidVoice 是一款开源的 macOS 语音转文字听写应用，支持本地设备端 STT 和自定义 AI 增强模型，可作为 Wispr Flow 的本地替代方案。

**核心功能**:
- **设备端语音转文字**: 支持多种语音模型（如 Nemotron Speech、Parakeet、Whisper 等），无需联网即可完成听写。
- **Fluid Intelligence 本地 AI 增强**: 私有本地 AI 运行时，提供智能格式化、上下文感知大写和后处理，数据不离开 Mac。
- **命令模式**: 通过语音在 Mac 上执行任何操作。
- **写作模式**: 在任何应用的文本框中语音输入或重写文本。
- **自适应主题**: 支持亮/暗主题切换，并配有紧凑工具栏。
- **历史与统计**: 记录听写历史和使用统计。

**技术亮点**: 使用 Swift 开发，基于设备端 STT 模型和私有本地 AI 增强模型，支持 GPLv3 开源许可。

---
## 5. [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute)
- **语言**: TypeScript
- **Stars**: 8,579
- **简介**: Never stop coding. Free AI gateway: one endpoint, 231+ providers (50+ free), connect Claude Code, Codex, Cursor, Cline & Copilot to FREE Claude/GPT/Gemini. RTK+Caveman stacked compression saves 15-95% tokens, smart auto-fallback, MCP/A2A, multimodal APIs, Desktop/PWA.

### AI 总结
**简介**: OmniRoute 是一个免费、开源的 AI 网关，通过单一端点连接 236 家 AI 提供商（其中 50+ 家免费），并集成了智能压缩与自动回退功能，旨在让开发者“永不停止编码”。

**核心功能**:
- **多提供商聚合**: 支持 236 家 AI 提供商（含 50+ 免费层级），通过一个统一端点对接 Claude、GPT、Gemini 等模型。
- **智能自动回退**: 当主提供商限流或失败时，自动切换到备用提供商，确保服务不中断。
- **极致 Token 压缩**: 采用 RTK + Caveman 压缩技术，可节省 15%–95% 的 Token 消耗，显著降低成本。
- **丰富的路由策略**: 内置 17 种路由策略，支持灵活配置请求分发。
- **全平台兼容**: 支持 Claude Code、Codex、Cursor、Cline、Copilot 等主流 CLI 和编码代理，并提供 MCP/A2A 协议支持。
- **多模态与桌面端**: 支持多模态 API，并提供桌面版（Electron）和 PWA 应用。

**技术亮点**: 基于 TypeScript 开发；采用 RTK + Caveman 压缩算法；支持 Docker 部署；提供 npm 包、CLI 工具及多语言界面（41+ 种语言）。

---
## 6. [browser-use/video-use](https://github.com/browser-use/video-use)
- **语言**: Python
- **Stars**: 12,635
- **简介**: Edit videos with coding agents

### AI 总结
**简介**: video-use 是一个开源工具，允许用户通过与 Claude Code 等编码智能体聊天的方式，自动编辑视频，将原始素材转化为最终成品。

**核心功能**:
- **智能剪辑**: 自动去除填充词（如“umm”、“uh”）和镜头间的空白片段。
- **自动调色**: 为每个片段应用预设或自定义的 FFmpeg 调色链（如暖色电影感、中性冲击感）。
- **音频优化**: 在每个剪辑点自动添加 30ms 的音频淡入淡出，消除爆音。
- **字幕生成**: 自动烧录可自定义风格的字幕（默认为两词一组的大写格式）。
- **动画覆盖**: 支持通过 HyperFrames、Remotion、Manim 或 PIL 等工具，以并行子代理方式生成动画覆盖层。
- **自我评估**: 在展示结果前，会在每个剪辑点对渲染输出进行自我评估，确保质量。
- **会话记忆**: 将项目状态持久化到 `project.md` 文件中，方便后续会话无缝衔接。

**技术亮点**: 采用“LLM 不观看视频，而是读取视频”的创新方法，通过两层结构化数据（音频转录文本和视觉合成图）替代海量原始帧，极大降低了 token 消耗。其流水线为：转录 -> 打包 -> LLM 推理 -> 编辑决策列表 -> 渲染 -> 自我评估（失败则最多重试3次）。

---
## 7. [xbtlin/ai-berkshire](https://github.com/xbtlin/ai-berkshire)
- **语言**: Python
- **Stars**: 7,528
- **简介**: AI 时代的伯克希尔：基于 Claude Code / Codex 的价值投资研究框架。巴菲特·芒格·段永平·李录四大师方法论 + 多Agent并行研究。| AI-era Berkshire: a value investing research framework built for Claude Code / Codex. 4 masters' methodologies + multi-agent adversarial analysis.

### AI 总结
**简介**: 一套基于 Claude Code / Codex 的价值投资研究框架，将巴菲特、芒格、段永平、李录四位大师的方法论系统化，通过多 Agent 并行实现专业级投资研究。

**核心功能**:
- **多视角对抗分析**: 巴菲特（财务估值）、芒格（逆向思考）、段永平（商业模式）、李录（长期确定性）四大师视角独立研究并综合，产生真实矛盾与张力，避免盲点。
- **强制结论与结构化输出**: 输出“通过/不通过/灰色地带”的明确结论，并附带具体价格区间与分层建议（激进/稳健/保守），杜绝模糊分析。
- **内置反偏见机制**: 包含信息丰富度评级、芒格式逆向检验、快速否决清单（8条红线）、反共识检查、留白原则等，防止虚假确定性。
- **金融数据精确校验**: 使用 Python `decimal.Decimal` 进行精确计算，自动校验市值、单位等关键数据，确保数据严谨性。
- **可复现的研究流程**: 同一标准、同一格式的 CheckList 筛选，支持7家公司横向对比、半年后重新分析对比，团队研究结果可对齐。
- **多Agent并行研究**: `/investment-team` 启动4个独立 Agent 同时进行网络搜索、数据交叉验证与独立结论，由 Team Lead 综合，实现4倍信息源与4个独立视角。

**技术亮点**:
- **三层架构**: Skill 层（16个场景化入口）、Agent 层（4 Agent 并行对抗）、工具层（精确计算、实时检索、报告抽检）。
- **18个可复用 Skill**: 涵盖深度研究（如 `/investment-research`）、财报分析、行业筛选、持仓管理、思维工具等，按场景选用。
- **实盘验证**: 2024年收益 +69.29%，2025年至今 +66.38%，连续两年大幅跑赢全球主要指数（标普500、恒生指数等），两年累计实盘收益超146万元。
- **技术栈**: Python（核心计算）、Claude Code / Codex（AI Agent）、Mermaid（架构图）、富途证券（实盘数据）。

---
## 8. [Mebus/cupp](https://github.com/Mebus/cupp)
- **语言**: Python
- **Stars**: 6,111
- **简介**: Common User Passwords Profiler (CUPP)

### AI 总结
**简介**: CUPP 是一个基于用户个人信息（如生日、昵称、宠物名等）生成可能密码的渗透测试工具，用于评估密码强度或进行取证调查。

**核心功能**:
- **交互式密码分析**: 通过问答方式收集用户信息，生成针对性的密码字典。
- **字典扩展**: 支持对现有字典文件进行扩展和优化。
- **在线字典下载**: 从内置仓库下载常用弱密码列表。
- **Alecto 数据库集成**: 自动解析 Alecto DB 中的默认用户名和密码。

**技术亮点**: 纯 Python 实现，依赖简单（仅需 Python 3），支持通过配置文件自定义规则。

---
## 9. [ripienaar/free-for-dev](https://github.com/ripienaar/free-for-dev)
- **语言**: HTML
- **Stars**: 127,340
- **简介**: A list of SaaS, PaaS and IaaS offerings that have free tiers of interest to devops and infradev

### AI 总结
**简介**: 一个收集对DevOps和基础设施开发者有用的、提供免费套餐的SaaS、PaaS和IaaS服务列表。

**核心功能**:
- 分类整理各大云服务商（如GCP、AWS等）的永久免费资源。
- 涵盖分析、API、CDN、CI/CD、监控、数据库、托管、安全等数十个技术领域的免费服务。
- 由社区通过Pull Request共同维护，确保信息的时效性和准确性。

**技术亮点**: 基于HTML的静态列表，通过GitHub协作和Awesome List跟踪机制管理，内容聚焦于“即服务”产品，明确排除自托管软件和短期试用。

---
## 10. [google/agents-cli](https://github.com/google/agents-cli)
- **语言**: Python
- **Stars**: 4,224
- **简介**: The CLI and skills that turn any coding assistant into an expert at creating, evaluating, and deploying AI agents on Google Cloud.

### AI 总结
**简介**: `agents-cli` 是一个 CLI 工具，能将任何代码助手转变为在 Google Cloud 上构建、评估和部署 AI Agent 的专家。

**核心功能**:
- **项目脚手架**: 快速创建、增强和升级 Agent 项目（`scaffold` 命令）。
- **Agent 评估**: 支持生成评估数据、运行评分、比较结果及分析失败模式（`eval` 命令）。
- **一键部署**: 将 Agent 部署到 Agent Runtime、Cloud Run 或 GKE 等 Google Cloud 服务（`deploy` 命令）。
- **Gemini Enterprise 发布**: 将 Agent 注册到 Gemini Enterprise 平台（`publish` 命令）。
- **技能注入**: 为代码助手提供关于工作流、ADK API、评估、部署和可观测性等领域的专业知识。

**技术亮点**: 基于 Python 开发，无缝集成 uv 和 Node.js 生态，支持 Antigravity CLI、Claude Code、Codex 等多种代码助手，并提供全面的 Agent 开发、评估、部署与可观测性能力。

---
