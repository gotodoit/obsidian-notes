---
tags:
  - github-trending
  - daily
date: 2026-06-26
created: 2026-06-26T01:55:44.132Z
---

# 2026-06-26 GitHub Trending Top 10

## 1. [google-labs-code/design.md](https://github.com/google-labs-code/design.md)
- **语言**: TypeScript
- **Stars**: 19,338
- **简介**: A format specification for describing a visual identity to coding agents. DESIGN.md gives agents a persistent, structured understanding of a design system.

### AI 总结
**简介**: 一种格式化规范，用于向编码代理描述视觉标识，使代理能持久、结构化地理解设计系统。

**核心功能**:
- **DESIGN.md 格式**: 结合机器可读的设计令牌（YAML 前置元数据）和人类可读的设计原理（Markdown 正文）。
- **验证与检查**: 通过 `npx @google/design.md lint DESIGN.md` 命令验证文件是否符合规范、检查令牌引用错误、WCAG 对比度等，并输出结构化 JSON 结果。
- **差异比较**: 通过 `npx @google/design.md diff DESIGN.md DESIGN-v2.md` 命令比较两个版本的设计系统，检测令牌和正文的回归变化。

**技术亮点**: 基于 TypeScript 实现，提供 CLI 工具用于验证和差异比较，支持 YAML 和 Markdown 混合的规范格式，定义了完整的令牌类型（颜色、排版、尺寸、组件属性）和消费行为规则。

---
## 2. [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)
- **语言**: Python
- **Stars**: 22,159
- **简介**: World's first open-source, agentic video production system. 12 pipelines, 52 tools, 500+ agent skills. Turn your AI coding assistant into a full video production studio.

### AI 总结
**简介**: OpenMontage 是全球首个开源的、基于智能代理的视频制作系统，能将你的 AI 编程助手转变为完整的视频制作工作室。

**核心功能**:
- **自然语言驱动**: 只需用自然语言描述需求，代理即可自动完成研究、脚本、素材生成、编辑和最终合成。
- **真实视频制作**: 并非简单的图片动画，而是能从免费素材库和开放档案中检索真实运动片段，剪辑并渲染成完整视频。
- **多种管道 (Pipelines)**: 内置12条视频制作管道和52种工具，支持超过500种代理技能，覆盖从概念到成片的全流程。
- **低成本高效率**: 支持多种AI服务提供商（如OpenAI、Veo、Kling等），可生成高质量视频，成本极低（例如制作一个60秒动画短片的成本仅为1.33美元）。

**技术亮点**: 该项目使用 **Python** 构建，集成了多种AI模型（如FLUX、Kling、Veo、GPT-Image、Chirp3、WhisperX）和 **Remotion** 合成引擎，能够自动化处理文本、图像、音频、视频和字幕的生成与编辑。

---
## 3. [xbtlin/ai-berkshire](https://github.com/xbtlin/ai-berkshire)
- **语言**: Python
- **Stars**: 1,973
- **简介**: AI 时代的伯克希尔：基于 Claude Code 的价值投资研究框架。巴菲特·芒格·段永平·李录四大师方法论 + 多Agent并行研究。| AI-era Berkshire: a value investing research framework built on Claude Code. 4 masters' methodologies + multi-agent adversarial analysis.

### AI 总结
**简介**: 一套基于 Claude Code、融合四位价值投资大师方法论的多 Agent 投资研究框架，通过 AI 实现专业级投研深度与决策纪律。

**核心功能**:
- **四大师视角对抗分析**: 从巴菲特、芒格、段永平、李录四个独立视角并行研究同一家公司，输出有张力的综合结论。
- **结构化反偏见机制**: 内置信息丰富度评级、逆向检验、快速否决清单、反共识检查等，防止 AI 给出“看似正确”的结论。
- **精确金融数据校验**: 使用 `decimal.Decimal` 进行精确计算，并通过多源交叉验证与手算校验，避免 LLM 常见的计算错误。
- **可复现的标准化输出**: 确保不同公司、不同时间的研究报告结构一致，支持横向对比与纵向追踪。
- **16 个场景化 Skill**: 覆盖深度研究、财报分析、行业筛选、持仓管理、思维工具等完整投研流程。

**技术亮点**: 基于 Claude Code 的 Agent 层架构，每个 Skill 内部由 4 个独立 Agent 并行搜索、判断、挑战，最后由 Team Lead 综合；工具层集成精确计算与实时检索，保证数据严谨性。

---
## 4. [mauriceboe/TREK](https://github.com/mauriceboe/TREK)
- **语言**: TypeScript
- **Stars**: 6,730
- **简介**: A self-hosted travel/trip planner with real-time collaboration, interactive maps, PWA support, SSO, budgets, packing lists, and more.

### AI 总结
**简介**: TREK 是一个自托管的实时协作旅行规划器，集地图、预算、打包清单、旅行日志和 AI 功能于一体。

**核心功能**:
- **交互式旅行规划**: 支持拖拽式日程安排、3D地图（Leaflet/Mapbox GL）、路线优化和天气预测。
- **费用管理**: 追踪和分摊旅行开支（类似Splitwise），支持多币种、按人/日分解结算。
- **资源管理**: 预订管理（航班/住宿/餐厅，支持从邮件和PDF导入）、打包清单（分类/模板/用户分配）。
- **实时协作**: 支持多人同时编辑，PWA 离线支持，SSO 单点登录。
- **地图与数据导入**: 集成 Google Places/OpenStreetMap 搜索，支持导入 Google Maps/Naver Maps 列表及 GPX/KML/KMZ/GeoJSON 文件。

**技术亮点**: 基于 TypeScript 构建，使用 Leaflet/Mapbox GL 实现高性能地图渲染，支持 Docker 一键部署，集成 AI 功能，采用 AGPL v3 开源协议。

---
## 5. [apple/container](https://github.com/apple/container)
- **语言**: Swift
- **Stars**: 43,237
- **简介**: A tool for creating and running Linux containers using lightweight virtual machines on a Mac. It is written in Swift, and optimized for Apple silicon.

### AI 总结
**简介**: `container` 是苹果官方推出的工具，用于在 Mac（Apple 芯片）上通过轻量级虚拟机创建和运行 Linux 容器，基于 Swift 编写并针对 Apple silicon 优化。

**核心功能**:
- 创建、运行和管理 OCI 兼容的 Linux 容器镜像（支持从标准注册表拉取和推送镜像）。
- 提供命令行工具，支持系统服务启停、安装/升级/卸载（含用户数据保留选项）。
- 包含完整教程、命令参考和技术概览文档，并支持 API 文档浏览。

**技术亮点**:
- 基于 Swift 编写，深度集成 macOS 26 的虚拟化和网络新特性。
- 底层依赖 [Containerization](https://github.com/apple/containerization) Swift 包实现容器、镜像和进程管理。
- 目前处于活跃开发阶段（0.x 版本），稳定性和 API 在补丁版本内保证，次要版本可能包含破坏性变更。

---
## 6. [JCodesMore/ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template)
- **语言**: TypeScript
- **Stars**: 20,482
- **简介**: Clone any website with one command using AI coding agents

### AI 总结
**简介**: 一个利用 AI 编码代理，通过一条命令即可将任何网站逆向工程为整洁、现代的 Next.js 代码库的模板。

**核心功能**:
- **一键克隆**: 通过 `/clone-website <目标URL>` 命令，AI 代理自动完成网站克隆。
- **多阶段流水线**: 包括侦察、基础设置、组件规范和并行构建阶段，自动提取设计令牌、资产和组件。
- **广泛代理支持**: 推荐使用 Claude Code，同时支持 Codex CLI、OpenCode、Cursor 等十余种主流 AI 编码代理。

**技术亮点**:
- 基于 **Next.js 16** (App Router、React 19、TypeScript strict)、**shadcn/ui** (Radix + Tailwind CSS v4) 和 **Lucide React**。
- 采用 **MIT 开源协议**。

---
## 7. [every-app/open-seo](https://github.com/every-app/open-seo)
- **语言**: TypeScript
- **Stars**: 2,552
- **简介**: Open source alternative to Semrush and Ahrefs

### AI 总结
**简介**: OpenSEO 是一款开源的 SEO 工具，作为 Semrush 和 Ahrefs 的替代品，提供按需付费、用户自主可控的 SEO 解决方案，并支持 AI 代理集成。

**核心功能**:
- 关键词研究：发现值得投入的主题，评估需求并确定内容优先级。
- 排名追踪：监控关键词在桌面端和移动端的排名变化，支持 SERP 特性检测。
- 网站洞察：分析域名的可见性变化，聚焦影响收入的页面。
- 外链分析：查看链接来源、吸引链接的页面以及链接的新增或丢失情况。
- 网站审计：及早发现技术问题，确保搜索引擎顺利抓取和排名。
- AI 品牌可见性：查看品牌在 AI 回答中的出现情况，包括竞争对手提及和来源覆盖。
- AI 搜索提示探索：追踪用户在 AI 工具中搜索你所在市场时可能使用的提示词。
- MCP 服务器集成：支持 AI 代理（如 Claude Code、Codex）直接通过 MCP 执行 SEO 任务。
- Agent Skills：预置可复用的工作流，如 SEO 项目设置、关键词聚类、竞争分析等。

**技术亮点**: 基于 TypeScript 开发，提供自托管（Docker、Cloudflare）和托管版本，支持 DataForSEO API 按需付费，无订阅费用，提供 MCP 服务器和 Agent Skills 以增强 AI 代理的 SEO 能力。

---
## 8. [garrytan/gstack](https://github.com/garrytan/gstack)
- **语言**: TypeScript
- **Stars**: 115,848
- **简介**: Use Garry Tan's exact Claude Code setup: 23 opinionated tools that serve as CEO, Designer, Eng Manager, Release Manager, Doc Engineer, and QA

### AI 总结
**简介**: gstack 是 Garry Tan 分享的一套 Claude Code 配置，包含 23 个高度定制化的工具，能将 AI 代码助手转变为一个包含 CEO、设计师、工程经理、QA 等角色的虚拟工程团队，帮助个人开发者实现接近传统团队的生产力。

**核心功能**:
- **虚拟工程团队角色**: 提供 23 个专家角色（如 CEO、设计师、工程经理、QA 主管）和 8 个强力工具，通过斜杠命令调用。
- **全流程自动化**: 覆盖从产品构思（如 `/office-hours`）、架构审查（`/plan-ceo-review`）、代码审查（`/review`）、质量保证（`/qa`）到发布部署（`/ship`, `/land-and-deploy`）的完整开发流程。
- **一键安装与团队模式**: 通过一条命令即可在本地安装，并支持在共享仓库中启用团队模式，让所有协作者自动获得相同配置。

**技术亮点**:
- **语言**: TypeScript
- **架构**: 基于 Claude Code 的 Markdown 斜杠命令系统，所有工具均为 MIT 开源许可。
- **核心**: 通过结构化的角色和流程，将 AI 的生成能力转化为可重复、可审计的工程实践，显著提升了逻辑代码变更的效率（作者声称 2026 年的日产出是 2013 年的 810 倍）。

---
## 9. [aws/agent-toolkit-for-aws](https://github.com/aws/agent-toolkit-for-aws)
- **语言**: Python
- **Stars**: 1,147
- **简介**: Official, AWS-supported MCP servers, skills, and plugins to help AI agents build on AWS

### AI 总结
**简介**: AWS 官方推出的工具包，帮助 AI 编码代理在 AWS 上构建、部署和管理应用程序。

**核心功能**:
- 提供集成插件，支持 Claude Code、Codex、Cursor、Kiro 等主流 AI 编码代理
- 包含多个功能插件：aws-core（核心 AWS 技能，如 CDK/CloudFormation、无服务器、容器、存储、SDK 使用等）、aws-agents（基于 Amazon Bedrock 构建 AI 代理）、aws-data-analytics（数据湖、分析、ETL 工作流）、aws-agents-for-devsecops（安全审查、漏洞扫描、渗透测试）
- 支持通过 MCP 服务器配置和技能安装，实现与 AWS 服务的无缝交互

**技术亮点**: 使用 Python 开发，基于 MCP（Model Context Protocol）服务器架构，支持插件化扩展，提供官方支持的技能和防护措施。

---
## 10. [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills)
- **语言**: Python
- **Stars**: 21,268
- **简介**: 817 structured cybersecurity skills for AI agents · Mapped to 6 frameworks: MITRE ATT&CK, NIST CSF 2.0, MITRE ATLAS, D3FEND, NIST AI RMF & MITRE F3 (Fight Fraud) · agentskills.io standard · Works with Claude Code, GitHub Copilot, Codex CLI, Cursor, Gemini CLI & 20+ platforms · 29 security domains · Apache 2.0

### AI 总结
**简介**: 一个为 AI 代理提供 817 个结构化网络安全技能的开源库，覆盖 29 个安全领域，并映射到六个主流安全框架。

**核心功能**:
- 提供 817 个生产级网络安全技能，涵盖 29 个安全领域，包括恶意软件分析、云安全、身份安全等。
- 每个技能均映射到 MITRE ATT&CK、NIST CSF 2.0、MITRE ATLAS、D3FEND、NIST AI RMF 和 MITRE F3 六个行业框架。
- 兼容 Claude Code、GitHub Copilot、Codex CLI、Cursor、Gemini CLI 等 26 个以上 AI 平台。
- 遵循 agentskills.io 开放标准，技能结构统一，便于 AI 代理直接使用。

**技术亮点**: 使用 Python 开发，采用 agentskills.io 开放标准，实现跨框架统一映射。

---
