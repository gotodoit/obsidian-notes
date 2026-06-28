---
tags:
  - github-trending
  - daily
date: 2026-06-28
created: 2026-06-28T01:55:43.978Z
---

# 2026-06-28 GitHub Trending Top 10

## 1. [simplex-chat/simplex-chat](https://github.com/simplex-chat/simplex-chat)
- **语言**: Haskell
- **Stars**: 13,887
- **简介**: SimpleX - the first messaging network operating without user identifiers of any kind - 100% private by design! iOS, Android and desktop apps 📱!

### AI 总结
**简介**: SimpleX 是首个完全去标识化的消息网络，实现 100% 隐私保护设计，支持 iOS、Android 和桌面端。

**核心功能**:
- 保护消息内容和元数据（与谁通信、通信时间）
- 双重棘轮端到端加密，并附加额外加密层
- 支持 iOS、Android 移动端应用及 Linux/MacOS/Windows 终端/命令行应用
- 提供 TestFlight 预览版供用户提前体验新功能
- 支持用户创建群组和社区，并通过 SimpleX Directory 发现

**技术亮点**: 使用 Haskell 语言开发，采用无用户标识符的隐私架构，结合双重棘轮加密技术确保通信安全。

---
## 2. [xbtlin/ai-berkshire](https://github.com/xbtlin/ai-berkshire)
- **语言**: Python
- **Stars**: 4,174
- **简介**: AI 时代的伯克希尔：基于 Claude Code 的价值投资研究框架。巴菲特·芒格·段永平·李录四大师方法论 + 多Agent并行研究。| AI-era Berkshire: a value investing research framework built on Claude Code. 4 masters' methodologies + multi-agent adversarial analysis.

### AI 总结
**简介**: 一套基于 Claude Code/Codex 的价值投资研究框架，将巴菲特、芒格、段永平、李录四位大师的方法论系统化，通过多 Agent 并行实现专业级投资研究。

**核心功能**:
- **多大师视角对抗**: 4 个独立 Agent 分别模拟四位大师视角，同时研究一家公司，产生真实观点冲突，避免盲点。
- **强制结构化决策**: 输出明确的“通过/不通过/灰色地带”结论，附带具体价格区间和分层建议，不打太极。
- **内置反偏见机制**: 包含信息丰富度评级、芒格式逆向检验、快速否决清单、反共识检查、留白原则等多层防错设计。
- **精确金融数据校验**: 使用 `decimal.Decimal` 进行精确计算，关键数据至少两个独立来源交叉验证，支持命令行工具校验市值等数据。
- **可复现研究流程**: 确保同一家公司不同时间或不同公司之间的研究输出结构一致、评分标准统一，便于横向对比和追踪变化。
- **18 个场景化 Skill**: 涵盖深度研究、财报分析、行业筛选、持仓管理等，按需选用，如 `/investment-team` 启动 4 个 Agent 并行研究。

**技术亮点**: 基于 Claude Code/Codex 的 Agent 架构，采用“Skill 层” + “Agent 层” + “工具层” 三层设计，实现多 Agent 并行搜索、独立判断与交叉验证。

---
## 3. [commaai/openpilot](https://github.com/commaai/openpilot)
- **语言**: Python
- **Stars**: 62,082
- **简介**: openpilot is an operating system for robotics. Currently, it upgrades the driver assistance system on 300+ supported cars.

### AI 总结
**简介**: openpilot 是一个机器人操作系统，目前可为 300 多款支持的汽车升级辅助驾驶系统。

**核心功能**:
- 升级车辆辅助驾驶系统
- 支持 300 多款车型
- 提供安装指引和社区支持
- 支持多种分支版本（稳定版、测试版、开发版）

**技术亮点**:
- 基于 Python 开发
- 遵循 ISO26262 安全标准
- 包含软件在环测试
- 使用 panda 硬件实现安全模型
- 支持 comma four 等硬件设备

---
## 4. [IceWhaleTech/CasaOS](https://github.com/IceWhaleTech/CasaOS)
- **语言**: Go
- **Stars**: 35,804
- **简介**: CasaOS - A simple, easy-to-use, elegant open-source Personal Cloud system.

### AI 总结
**简介**: CasaOS 是一个简单、易用、优雅的开源个人云系统，旨在帮助用户轻松管理家庭或小型办公环境中的数据与服务。

**核心功能**:
- 提供个人云存储与管理，支持文件、照片、视频等数据的集中存储和访问。
- 支持通过应用商店一键安装和管理 Docker 应用，扩展个人云功能。
- 提供直观的 Web 界面，方便用户监控系统资源、管理用户和权限。

**技术亮点**: 基于 Go 语言开发，采用轻量级架构，强调低资源占用和易部署性；支持 Docker 容器化应用生态，便于功能扩展。

---
## 5. [ripienaar/free-for-dev](https://github.com/ripienaar/free-for-dev)
- **语言**: HTML
- **Stars**: 124,189
- **简介**: A list of SaaS, PaaS and IaaS offerings that have free tiers of interest to devops and infradev

### AI 总结
**简介**: 这是一个收集了为开发者和DevOps人员提供免费 tier 的 SaaS、PaaS、IaaS 等云服务的清单。

**核心功能**:
- 分类整理超过1000种免费云服务，涵盖云计算、分析、API、CI/CD、监控、托管等领域
- 包含主流云厂商（如GCP、AWS、Azure）的永久免费套餐
- 社区驱动维护，由1600+贡献者通过Pull Request持续更新
- 严格筛选标准：仅收录提供真正免费层级（非试用）的服务，且时间限制类免费至少持续一年

**技术亮点**:
- 基于HTML构建的静态清单页面，便于快速浏览和搜索
- 采用Awesome List格式，支持通过Track Awesome List追踪更新
- 分类目录包含60+细分领域，从基础设施到工具协作全覆盖

---
## 6. [google-labs-code/design.md](https://github.com/google-labs-code/design.md)
- **语言**: TypeScript
- **Stars**: 22,365
- **简介**: A format specification for describing a visual identity to coding agents. DESIGN.md gives agents a persistent, structured understanding of a design system.

### AI 总结
**简介**: DESIGN.md 是一种格式规范，用于向编码代理描述视觉标识，为其提供持久且结构化的设计系统理解。

**核心功能**:
- **设计令牌与文档结合**: 通过 YAML 前端数据提供机器可读的设计令牌（如颜色、排版），配合 Markdown 正文提供人类可读的设计原理。
- **规范验证**: 提供 `lint` 命令，验证 DESIGN.md 文件是否符合规范，检查令牌引用错误、WCAG 对比度，并以结构化 JSON 输出结果。
- **版本对比**: 提供 `diff` 命令，对比两个设计系统版本，检测令牌和文本的回归变化。
- **组件定义**: 支持定义组件及其属性（如背景色、文字色、圆角），并支持变体（如悬停状态）。

**技术亮点**: 基于 TypeScript 开发，使用 YAML 和 Markdown 结合的结构化格式，通过 CLI 工具实现自动化验证和对比，输出结构化 JSON 供代理处理。

---
## 7. [microsoft/PowerToys](https://github.com/microsoft/PowerToys)
- **语言**: C
- **Stars**: 135,714
- **简介**: Microsoft PowerToys is a collection of utilities that supercharge productivity and customization on Windows

### AI 总结
**简介**: Microsoft PowerToys 是微软开发的一套 Windows 实用工具集，旨在提升生产力和自定义能力。

**核心功能**:
- **高级粘贴**：增强剪贴板功能，支持多种粘贴格式。
- **始终置顶**：将窗口固定在其他窗口之上。
- **唤醒**：防止电脑进入睡眠或锁屏模式。
- **颜色选择器**：快速拾取屏幕颜色并获取色值。
- **FancyZones**：自定义窗口布局管理器，提高多任务效率。
- **文件资源管理器加载项**：预览多种文件格式（如SVG、Markdown）。
- **Image Resizer**：批量调整图片尺寸。
- **键盘管理器**：重新映射按键和快捷键。
- **鼠标实用工具**：高亮鼠标位置、查找鼠标等。
- **PowerToys Run**：快速启动应用、搜索文件、执行命令。
- **PowerRename**：批量重命名文件。
- **Peek**：快速预览文件内容。
- **屏幕标尺**：测量屏幕上的像素距离。
- **快捷键指南**：显示 Windows 快捷键提示。
- **文本提取器 (OCR)**：从屏幕图像中识别并提取文字。
- **视频会议静音**：一键静音麦克风和摄像头。
- **窗口向导**：重新排列窗口布局。

**技术亮点**: 使用 C# 和 .NET 框架开发，模块化架构支持独立更新，提供丰富的 Windows API 集成和系统级优化。

---
## 8. [hugohe3/ppt-master](https://github.com/hugohe3/ppt-master)
- **语言**: Python
- **Stars**: 33,102
- **简介**: AI generates a real, editable PowerPoint from any document — native shapes & animations, speaker notes voiced as audio narration, and the option to follow your own .pptx template, not slide images · by Hugo He

### AI 总结
**简介**: PPT Master 是一个 AI 驱动的工具，能够将任意文档自动生成为原生可编辑的 PowerPoint 演示文稿（PPTX），支持动画、演讲者笔记和音频旁白，并允许用户自定义模板。

**核心功能**:
- **文档转PPT**: 从任意文档（如文本、PDF等）自动生成结构化的 PowerPoint 演示文稿。
- **原生可编辑**: 生成的PPTX文件包含原生形状、动画和布局，可直接在PowerPoint中编辑，而非静态图片。
- **演讲者笔记与音频**: 自动生成演讲者笔记，并支持将笔记转化为音频旁白。
- **自定义模板**: 用户可提供自己的 .pptx 模板，让AI生成内容时遵循模板样式。
- **多模型支持**: 兼容多种AI模型（如Claude、OpenAI、Gemini等），用户可根据成本和效果选择。

**技术亮点**: 采用 Python 开发，集成多种AI API（通过赞助商提供的中继服务），支持高并发和低成本调用。项目设计为开源工具，强调用户对生成内容的后续编辑能力，而非一次性完美输出。

---
## 9. [JCodesMore/ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template)
- **语言**: TypeScript
- **Stars**: 22,150
- **简介**: Clone any website with one command using AI coding agents

### AI 总结
**简介**: 一个基于 AI 编码代理，通过一条命令即可将任意网站逆向工程为整洁现代 Next.js 代码库的模板项目。

**核心功能**:
- **一键克隆**：在 AI 代理中运行 `/clone-website <目标网址>` 即可自动克隆网站。
- **多阶段流水线**：自动执行侦察（截图、设计令牌提取、交互扫描）、基础框架更新、组件规格编写和并行构建。
- **广泛代理支持**：推荐 Claude Code，同时兼容 Codex CLI、OpenCode、Cursor、GitHub Copilot 等 13 种主流 AI 编码代理。

**技术亮点**:
- 基于 **Next.js 16**（App Router、React 19、严格 TypeScript）构建。
- 使用 **shadcn/ui**（Radix 原语 + Tailwind CSS v4）和 **oklch 设计令牌**。
- 采用 **Lucide React** 作为默认图标，克隆时自动替换为提取的 SVG。

---
## 10. [garrytan/gstack](https://github.com/garrytan/gstack)
- **语言**: TypeScript
- **Stars**: 117,267
- **简介**: Use Garry Tan's exact Claude Code setup: 23 opinionated tools that serve as CEO, Designer, Eng Manager, Release Manager, Doc Engineer, and QA

### AI 总结
**简介**: gstack 是 YC 总裁 Garry Tan 公开的 Claude Code 配置，将 AI 代理转化为包含 CEO、设计师、QA 等 23 个角色的虚拟工程团队，帮助个人开发者实现团队级交付效率。

**核心功能**:
- **虚拟工程团队**: 通过 `/office-hours`、`/plan-ceo-review`、`/review`、`/qa` 等 23 个斜杠命令，模拟 CEO、设计、工程管理、QA、安全审计等角色
- **全流程自动化**: 覆盖从需求分析、架构设计、代码审查、质量测试到发布部署的完整开发链路
- **浏览器级 QA**: 支持连接真实浏览器进行端到端测试
- **安全审计**: 集成 OWASP + STRIDE 安全评估
- **团队协作**: 支持团队模式，自动为共享仓库启用配置

**技术亮点**: 基于 TypeScript 开发，依赖 Claude Code、Git、Bun 和 Node.js；采用 Markdown 驱动的命令系统；MIT 开源许可。

---
