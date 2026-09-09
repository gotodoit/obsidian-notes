---
tags:
  - github-trending
  - daily
date: 2026-09-09
created: 2026-09-09T01:55:44.527Z
---

# 2026-09-09 GitHub Trending Top 10

## 1. [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)
- **语言**: Python
- **Stars**: 30,650
- **简介**: A skill to stop your coding agent from burying the answer. ADHD-friendly output.

### AI 总结
**简介**: 这是一个为编码助手设计的技能/插件，让 AI 输出更符合 ADHD（注意力缺陷多动障碍）人群的阅读习惯——直接给答案，不绕弯子。

**核心功能**:
- **行动优先**: 回答直接以具体操作开头，不做无意义的铺垫和寒暄
- **步骤编号**: 多步骤任务按编号清晰列出，避免信息混乱
- **规则约束**: 内置 10 条输出规则（如"先给下一步行动"、"抑制跑题"、"列表不超过 5 项"、"不要'希望这有帮助'"等）
- **可定制**: 支持 fork 后修改 SKILL.md 文件，自定义规则后重新安装
- **多语言支持**: 提供英文、简体中文、日文、韩文、葡萄牙语、越南语、泰语等多语言文档

**技术亮点**: 基于 Claude Code 插件系统开发，以 SKILL.md 为核心规则文件，通过 CLI 命令实现插件的安装、卸载和替换，采用 MIT 开源协议。

---
## 2. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 34,918
- **简介**: 38 editorial diagram types for Claude Code, Codex, and Pi. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个面向 Claude Code、Codex 等 AI 编程工具的图表设计技能库，提供 39 种编辑级质量的 HTML + SVG 图表类型，让 AI 生成的图表摆脱"通用圆角框"的廉价感。

**核心功能**:
- **39 种图表类型**: 涵盖架构图、流程图、时序图、状态机、ER 模型、时间线、泳道图、象限图、雷达图、循环/飞轮图等，每种均提供极简浅色、极简深色、全编辑风格三种静态变体
- **语义化模式系统**: 将行为与布局分离描述，队列、策略追踪、信任边界等场景可直接复用现有类型，无需增加类型数量
- **智能重绘能力**: 可读取 draw.io 或 Mermaid 源文件，按指定格式、尺寸和细节级别重新绘制图表
- **品牌快速匹配**: 通过读取网站内容，约 60 秒内即可匹配用户品牌风格
- **零依赖交付**: 所有图表均为自包含 HTML + SVG，无构建步骤、无 JavaScript、无外部图片依赖，浏览器直接打开即可使用
- **可选动效支持**: 静态输出为默认，针对有序讲解场景可启用无障碍动效

**技术亮点**: 纯 HTML + SVG 实现，无外部依赖；强调"编辑级设计"理念——无阴影、无 Mermaid 式粗糙输出，采用语义模式与布局分离的架构设计，支持 Agent Skills 兼容主机；设计密度目标 4/10，强调极简与留白，强调色仅用于读者应最先关注的 1–2 个关键元素。

---
## 3. [openai/skills](https://github.com/openai/skills)
- **语言**: Python
- **Stars**: 26,533
- **简介**: Skills Catalog for Codex

### AI 总结
**简介**: openai/skills 是 Codex 的 Agent Skills 技能目录，现已弃用，相关资源已迁移至 OpenAI Plugins 仓库。

**核心功能**:
- 提供可直接在 Codex 中使用的技能集合，包括系统级（`.system`）、精选级（`.curated`）和实验级（`.experimental`）三类技能
- 支持通过 `$skill-installer` 命令在 Codex 中按名称或 GitHub URL 安装技能
- 每个技能包含独立的指令、脚本和资源，且带有各自的 LICENSE.txt 许可文件

**技术亮点**:
- 基于 Agent Skills 开放标准（agentskills.io），实现"一次编写，处处使用"的技能封装模式
- 技能按目录分级管理（系统/精选/实验），便于区分稳定性和适用场景
- 当前项目已弃用，官方推荐迁移至 [OpenAI Plugins](https://github.com/openai/plugins) 仓库，并参照 [Build plugins](https://developers.openai.com/codex/plugins/build) 指南创建技能插件

---
## 4. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 254,340
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个面向 AI 编程代理（如 Claude Code、Codex 等）的性能优化系统，提供技能、本能、记忆、安全与研究优先的开发能力。

**核心功能**:
- **代理性能优化**: 为 AI 编程代理提供系统级的性能调优与增强
- **技能与记忆管理**: 支持代理的技能库扩展与长期记忆存储
- **安全防护 (AgentShield)**: 提供代理安全防护机制，防止恶意代码注入
- **跨平台兼容**: 支持 Claude Code、Codex、Opencode、Cursor 等多种 AI 编程工具
- **一键安装**: 通过 `npx ecc-universal setup` 命令快速完成安装与配置
- **多语言支持**: 提供 13 种语言的文档（中、英、日、韩、葡、西等）

**技术亮点**: 基于 JavaScript/TypeScript 构建，提供 npm 包（`ecc-universal`、`ecc-agentshield`）与 GitHub App 集成，支持 Shell、Python、Go、Java 等多种编程语言环境，采用插件作用域（plugin scope）机制实现安全、可更新的安装方式。

---
## 5. [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes)
- **语言**: TypeScript
- **Stars**: 47,801
- **简介**: Write HTML. Render video. Built for agents.

### AI 总结
**简介**: HyperFrames 是一个开源框架，可将 HTML、CSS、媒体和可交互动画转换为确定性 MP4 视频，专为 AI 智能体设计。

**核心功能**:
- **HTML 转视频**: 将 HTML/CSS 代码及媒体资源渲染为 MP4 视频，支持本地 CLI、AI 编码智能体和托管工作流
- **AI 智能体集成**: 内置 20 个技能（Skills），支持 Claude Code、Cursor、Gemini CLI、Codex 等智能体，通过自然语言描述即可生成视频
- **多工作流支持**: 提供 `/hyperframes` 路由器，可针对视频、演示文稿或合成端口等不同创作请求自动选择对应工作流
- **完整生产流程**: 涵盖规划视频、编写 HTML、绑定可交互动画、添加媒体、代码检查、预览和渲染的完整闭环
- **Codex 插件打包**: 支持生成符合 Codex 上传限制的插件归档文件

**技术亮点**: 基于 TypeScript 构建，采用模块化技能架构（核心技能集 + 按需安装），提供 npm 包分发和 CLI 工具，支持交互式技能选择器与非交互式命令安装模式，要求 Node.js >= 22。

---
## 6. [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills)
- **语言**: JavaScript
- **Stars**: 48,846
- **简介**: Marketing skills for Claude Code and AI agents. CRO, copywriting, SEO, analytics, and growth engineering.

### AI 总结
**简介**: 这是一个面向 AI 编程代理（如 Claude Code、Cursor 等）的营销技能库，提供 CRO、文案、SEO、分析和增长工程相关的专业工作流，帮助技术营销人员和创始人用 AI 完成营销任务。

**核心功能**:
- **产品营销基础**: `product-marketing` 技能作为所有其他技能的前置依赖，先理解产品、受众和定位再执行任务
- **SEO 与内容**: 包含 seo-audit、ai-seo、site-arch、schema、content、aso 等技能，覆盖 SEO 审计、内容优化和应用商店优化
- **转化率优化 (CRO)**: 提供 cro、signup、onboarding、popups、paywalls、ab-testing 等技能，针对落地页和用户流程进行转化提升
- **文案与内容创作**: 涵盖 copywriting、copy-edit、cold-email、emails、social、video、image、sms 等技能，适用于各类营销文案撰写和编辑
- **付费投放与分析**: 包含 ads、ad-creative、analytics 等技能，支持广告创意生成和效果测量
- **增长与留存**: 提供 referrals、free-tools、churn-prevent、community、lead-magnet、co-mktg 等技能，覆盖用户推荐、留存和社区运营
- **销售与 GTM**: 包含 revops、sales-enable、launch、pricing、competitors、prospecting 等技能，辅助上市策略和销售赋能
- **策略与洞察**: 提供 mktg-ideas、mktg-psych、customer-research 等技能，支持营销创意、心理学应用和客户调研

**技术亮点**: 基于 Agent Skills 规范（Markdown 格式），兼容多种 AI 代理；技能间通过共享上下文相互引用，形成模块化架构；MIT 开源许可，支持社区贡献；通过 Verified Partners 机制集成第三方工具（如 Converly 转化追踪、Ploy AI 建站平台），并保持中立推荐。

---
## 7. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 283,395
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码代理（coding agents）的完整软件开发方法论，基于可组合的技能集和初始指令构建，让代理自动遵循规范化的开发流程。

**核心功能**:
- **需求澄清与规格提炼**: 代理不会直接写代码，而是先询问用户真实目标，并将讨论结果逐步拆解成易于阅读的规格说明供用户确认。
- **自动生成实现计划**: 设计确认后，代理会制定清晰的实施计划，强调真正的红/绿 TDD（测试驱动开发）、YAGNI（不做多余功能）和 DRY（避免重复）原则。
- **子代理驱动开发**: 用户批准后，系统启动子代理逐一执行工程任务，自动检查与审查工作成果，可自主连续工作数小时而不偏离既定计划。
- **多平台插件支持**: 支持 Claude Code、Cursor、Codex、Gemini CLI、GitHub Copilot CLI 等十余种主流编码代理工具，安装方式各异。

**技术亮点**: 基于 Shell 脚本实现，采用可组合技能（composable skills）架构，通过会话启动钩子自动触发，无需用户手动干预即可让代理获得完整的开发方法论能力。

---
## 8. [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills)
- **语言**: Unknown
- **Stars**: 211,483
- **简介**: A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.

### AI 总结
**简介**: 这是一个基于 Andrej Karpathy 对 LLM 编程缺陷观察总结的单一 CLAUDE.md 文件，旨在改善 Claude Code 的编程行为。

**核心功能**:
- **Think Before Coding（先思考再编码）**：要求模型明确陈述假设、呈现多种解释、在困惑时停止并寻求澄清，避免盲目猜测
- **Simplicity First（简洁优先）**：对抗过度工程化，禁止添加未要求的功能、不必要的抽象和灵活性
- **Surgical Changes（外科手术式修改）**：只改动任务必需的代码，不"顺手"修改无关内容，但需清理自己改动产生的孤儿代码
- **Goal-Driven Execution（目标驱动执行）**：将命令式任务转化为可验证的成功标准（如"写测试让失败通过"），支持多步骤任务的验证循环

**技术亮点**:
- 提供两种安装方式：Claude Code 插件市场安装（跨项目生效）或直接追加到项目 CLAUDE.md
- 附带 Cursor 项目规则文件（.cursor/rules/karpathy-guidelines.mdc），可在 Cursor 编辑器中复用相同准则
- 将复杂行为准则提炼为四条可操作原则，每条配有明确的"测试"判断标准，便于模型和开发者自查

---
## 9. [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **语言**: Python
- **Stars**: 181,727
- **简介**: Python tool for converting files and office documents to Markdown.

### AI 总结
**简介**: MarkItDown 是一个轻量级 Python 工具，可将多种文件格式（如 PDF、Office 文档、图片等）转换为 Markdown，便于 LLM 和文本分析管道使用。

**核心功能**:
- 支持转换 PDF、PowerPoint、Word、Excel、图片（EXIF 和 OCR）、音频（转录）、HTML、CSV/JSON/XML、ZIP、YouTube URL、EPub 等格式
- 提供命令行工具，支持文件输入、输出重定向和管道操作
- 可选依赖按需安装（如 `[pdf]`、`[docx]`、`[xlsx]` 等），也可使用 `[all]` 一键安装全部
- 支持第三方插件扩展，可通过 `--use-plugins` 启用，如 OCR 插件可提取文档中嵌入图片的文字
- 保留文档结构（标题、列表、表格、链接等）为 Markdown 格式，输出 token 高效

**技术亮点**: 基于 Python 3.10+，采用模块化转换器架构；支持插件机制（社区可通过 `#markitdown-plugin` 搜索）；提供 Azure Document Intelligence 和 Azure Content Understanding 等云服务集成选项，并内置安全注意事项（建议在不可信环境中使用最小权限的 `convert_*` 函数）。

---
## 10. [jo-inc/camofox-browser](https://github.com/jo-inc/camofox-browser)
- **语言**: JavaScript
- **Stars**: 10,529
- **简介**: Stealth headless browser for AI agents — bypass Cloudflare, bot detection, and anti-scraping. Drop-in Puppeteer/Playwright replacement.

### AI 总结
**简介**: camofox-browser 是一个基于 Camoufox（Firefox 分支）的隐身无头浏览器服务器，专为 AI 代理设计，可在 C++ 层面绕过 Cloudflare、机器人检测和反爬虫机制，是 Puppeteer/Playwright 的即插即用替代品。

**核心功能**:
- **C++ 级反检测**：在 JavaScript 执行前伪造 `navigator.hardwareConcurrency`、WebGL 渲染器、AudioContext、屏幕几何、WebRTC 等指纹，无 shims、无痕迹
- **元素引用系统**：提供稳定的 `e1`、`e2`、`e3` 标识符，方便 AI 代理可靠地点击和交互
- **Token 高效快照**：使用可访问性快照而非原始 HTML，体积减少约 90%，降低 LLM token 消耗
- **会话隔离**：每个用户独立的 cookies/存储，支持 Netscape 格式 cookie 文件导入
- **搜索宏命令**：内置 `@google_search`、`@youtube_search`、`@amazon_search`、`@reddit_subreddit` 等 15+ 个常用站点快捷操作
- **YouTube 字幕提取**：通过 yt-dlp 提取视频字幕，无需 API key
- **VNC 交互式登录**：通过 noVNC 可视化登录网站，导出存储状态供代理复用
- **结构化数据提取**：支持 JSON Schema 驱动的 `POST /tabs/:tabId/extract` 端点，通过 `x-ref` 映射属性到快照元素
- **会话追踪**：可选的 Playwright trace 捕获（截图 + DOM 快照 + 网络），提供 API 列出/获取/删除
- **部署友好**：支持 Docker、Fly.io、Railway，空闲时内存仅 ~40MB，适合树莓派或低配 VPS
- **附加能力**：文件上传、代理 + GeoIP 路由、JSON 结构化日志、快照截图、大页面分页处理、下载捕获、DOM 图片提取

**技术亮点**:
- 基于 Camoufox——Firefox 分支，在 C++ 实现层面进行指纹伪造，而非 JS 层 shim
- 提供 REST API 服务（默认

---
