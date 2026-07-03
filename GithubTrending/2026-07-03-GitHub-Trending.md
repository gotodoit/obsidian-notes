---
tags:
  - github-trending
  - daily
date: 2026-07-03
created: 2026-07-03T01:55:45.066Z
---

# 2026-07-03 GitHub Trending Top 10

## 1. [usestrix/strix](https://github.com/usestrix/strix)
- **语言**: Python
- **Stars**: 32,327
- **简介**: Open-source AI penetration testing tool to find and fix your app’s vulnerabilities.

### AI 总结
**简介**: Strix 是一款开源的 AI 渗透测试工具，能够像真实黑客一样自主发现并修复应用漏洞。

**核心功能**:
- 完整的渗透测试工具集：自动执行侦察、漏洞利用和验证
- 多智能体编排：多个 AI 渗透测试代理协同工作，可扩展
- 真实漏洞验证：生成实际的概念验证 (PoC)，避免误报
- 开发者优先的 CLI：提供可操作发现和修复指导
- 自动修复与报告：生成安全补丁和符合合规要求的渗透测试报告
- CI/CD 集成：支持在每次 Pull Request 时自动扫描，阻止不安全代码进入生产环境

**技术亮点**: 基于 Python 开发，使用 Docker 沙箱隔离运行，支持多种 LLM 提供商（如 OpenAI、Anthropic、Google 等），采用多智能体架构实现自动化渗透测试。

---
## 2. [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)
- **语言**: JavaScript
- **Stars**: 81,050
- **简介**: 🪨 why use many token when few token do trick — Claude Code skill that cuts 65% of tokens by talking like caveman

### AI 总结
**简介**: 一个让 AI 编程助手（如 Claude Code、Cursor 等）用“穴居人”风格说话的开源技能/插件，可减少约 75% 的输出 token，同时保持技术准确性。

**核心功能**:
- **多级别压缩**: 支持 `lite`（去掉废话）、`full`（默认穴居人）、`ultra`（电报式）、`wenyan`（文言文）四种压缩等级，一键切换。
- **内置命令**: 提供 `/caveman` 压缩对话、`/caveman-commit` 生成短提交信息、`/caveman-review` 一行式 PR 评论、`/caveman-stats` 统计 token 节省量、`/caveman-compress` 压缩记忆文件。
- **多语言支持**: 保留用户使用的自然语言（如葡萄牙语、西班牙语），仅压缩表达风格，代码、命令和错误信息保持不变。
- **广泛兼容**: 支持 Claude Code、Codex、Gemini、Cursor、Windsurf、Cline、Copilot 等 30 多种 AI 编程助手。

**技术亮点**: 基于 JavaScript 实现，通过修改 AI 回复风格来减少 token 消耗，不牺牲技术准确度；提供一键安装脚本（curl 或 PowerShell），安装约 30 秒，需 Node ≥18。

---
## 3. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 125,558
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个可部署的AI专家团队集合，每个代理具备专业领域知识、独特个性和可交付成果，可集成到多种开发工具中。

**核心功能**:
- **即装即用的AI代理库**：提供覆盖前端开发、Reddit运营、安全审计等16个领域的专业AI代理
- **多工具集成**：支持Claude Code、Cursor、Codex、Gemini CLI、Aider等10+主流开发工具
- **灵活安装**：提供桌面应用（推荐）、CLI脚本、手动复制三种安装方式
- **按需部署**：支持按团队/代理粒度选择性安装，避免工具限制（如OpenCode的119代理上限）
- **自动更新**：桌面应用可自动保持代理文件为最新版本

**技术亮点**:
- Shell脚本驱动的跨平台安装系统（macOS/Linux/Windows）
- 模块化代理设计：每个代理包含身份特征、核心工作流、技术交付物和成功指标
- 支持`--dry-run`预览模式，提供安装前代理数量警告机制

---
## 4. [hasaneyldrm/exercises-dataset](https://github.com/hasaneyldrm/exercises-dataset)
- **语言**: HTML
- **Stars**: 9,293
- **简介**: A comprehensive dataset of 433 fitness exercises. Each entry includes name, category, target muscle group, equipment, instructions, thumbnail image, and animation video.

### AI 总结
**简介**: 一个包含1324个健身动作的结构化多语言数据集，附带开发者脚手架工具，帮助快速搭建健身应用后端。

**核心功能**:
- **结构化健身数据集**: 提供1324个健身动作的元数据，包括名称、类别、目标肌肉、所需器材、分步指导等。
- **多语言支持**: 动作指导支持英语、西班牙语、意大利语、土耳其语、俄语和中文6种语言。
- **交互式浏览器**: 提供一个无需服务器的HTML页面，支持实时搜索、按类别/器材/目标肌肉筛选、无限滚动浏览所有动作。
- **开发者设置指南**: 提供另一个HTML页面，分步指导如何将数据集集成到自己的应用中（如数据库设置）。

**技术亮点**:
- **纯客户端工具**: 交互式浏览器和设置指南均为HTML文件，无需后端服务器，直接在浏览器中打开即可使用。
- **JSON数据格式**: 数据集以JSON文件形式提供，便于程序解析和集成。
- **媒体引用**: 数据集不直接包含图片/GIF等媒体文件，但保留原始媒体ID，供有权限的用户从官方CDN获取。

---
## 5. [santifer/career-ops](https://github.com/santifer/career-ops)
- **语言**: JavaScript
- **Stars**: 57,872
- **简介**: AI-powered job search system built on Claude Code. 14 skill modes, Go dashboard, PDF generation, batch processing.

### AI 总结
**简介**: Career-Ops 是一个基于 AI 的求职系统，利用 Claude Code 等 AI 代理，帮助求职者批量搜索、筛选职位并生成个性化简历，最终实现高效求职。

**核心功能**:
- **14 种技能模式**: 提供多种搜索和匹配模式，覆盖不同求职策略。
- **Go 仪表盘**: 使用 Go 语言构建的实时仪表盘，用于监控求职进度和数据。
- **PDF 生成**: 自动为匹配的职位生成个性化简历（CV）的 PDF 文件。
- **批量处理**: 支持大规模职位列表的批量评估和简历生成。

**技术亮点**: 基于 JavaScript 和 Node.js 构建，集成了 Claude Code、OpenCode、GitHub Copilot 等多种 AI 代理 CLI，并使用 Playwright 进行自动化操作、Bubble Tea 构建终端 UI。

---
## 6. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 244,484
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套面向编码代理的完整软件开发方法论，基于可组合的技能和初始指令构建，让代理能自动遵循规范流程。

**核心功能**:
- **需求澄清**: 代理不会直接写代码，而是先与用户沟通，逐步提炼出清晰的规格说明。
- **设计评审**: 将规格说明分块展示给用户，确保设计得到确认后再推进。
- **实施计划**: 生成清晰、可执行的实现计划，强调真正的红/绿 TDD、YAGNI 和 DRY 原则。
- **子代理驱动开发**: 批准后，启动子代理独立处理每个工程任务，并自动审查工作，可自主运行数小时。

**技术亮点**: 基于 Shell 脚本实现，通过插件形式集成到 Claude Code、Cursor、Codex CLI 等多种主流编码代理工具中，技能自动触发，无需额外操作。

---
## 7. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp)
- **语言**: TypeScript
- **Stars**: 45,103
- **简介**: Chrome DevTools for coding agents

### AI 总结
**简介**: 一个基于MCP协议的Chrome DevTools服务器，让AI编程助手能够控制和检查实时Chrome浏览器，实现自动化调试、性能分析和浏览器自动化。

**核心功能**:
- **性能洞察**: 利用Chrome DevTools记录追踪并提取可操作的性能见解
- **高级浏览器调试**: 分析网络请求、截图、检查浏览器控制台消息（支持源码映射堆栈跟踪）
- **可靠自动化**: 基于Puppeteer自动执行Chrome操作并等待结果

**技术亮点**:
- 基于TypeScript开发，采用Model-Context-Protocol (MCP)标准
- 支持Google Chrome和Chrome for Testing，提供CLI工具
- 提供Slim精简模式用于基础浏览器任务

---
## 8. [browser-use/video-use](https://github.com/browser-use/video-use)
- **语言**: Python
- **Stars**: 13,826
- **简介**: Edit videos with coding agents

### AI 总结
**简介**: video-use 是一个开源工具，允许开发者通过 Claude Code 等编码代理，用自然语言指令编辑视频，自动生成最终成品。

**核心功能**:
- 自动剪辑：智能剔除填充词（如 “umm”、“uh”）和片段间的静音部分。
- 自动调色：为每个片段应用暖色电影、中性冲击或自定义 ffmpeg 链的调色方案。
- 智能音频处理：在每个剪辑点添加 30ms 淡入淡出，消除爆音。
- 字幕生成：以自定义风格（默认两词大写块）烧录字幕。
- 动画叠加：通过 HyperFrames、Remotion、Manim 或 PIL 并行生成动画叠加层。
- 自我评估：在每次剪辑边界对渲染输出进行自我评估，确保质量。
- 会话记忆：将项目状态持久化到 `project.md`，支持后续会话接续工作。

**技术亮点**: 采用双层次视频理解架构（音频转录文本 + 视觉时间线快照），避免直接处理原始视频帧，大幅降低 token 消耗；支持通过 ElevenLabs Scribe 进行词级时间戳和说话人识别。

---
## 9. [actions/checkout](https://github.com/actions/checkout)
- **语言**: TypeScript
- **Stars**: 8,167
- **简介**: Action for checking out a repo

### AI 总结
**简介**: actions/checkout 是一个 GitHub Actions，用于将仓库代码检出到工作区，供工作流使用。

**核心功能**:
- 将指定仓库（默认当前仓库）的代码检出到 `$GITHUB_WORKSPACE` 目录
- 支持通过 `repository` 和 `ref` 参数指定仓库、分支、标签或 SHA
- 默认只获取触发工作流的单个提交，通过 `fetch-depth: 0` 可获取完整历史
- 支持通过 `token` 或 SSH 密钥进行认证，并自动在 post-job 阶段清理凭据
- 提供 `persist-credentials` 选项控制凭据持久化方式（v6 起存储在临时文件）
- v7 新增 `allow-unsafe-pr-checkout` 参数，用于安全处理 fork PR 检出

**技术亮点**: 使用 TypeScript 开发；v7 迁移至 ESM 模块；v6 优化凭据安全性；v5 升级至 node24 运行时。

---
## 10. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 225,217
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个面向 AI 代码代理（如 Claude Code、Codex、Cursor 等）的“代理操作系统”，提供技能、直觉、记忆优化、安全扫描和研究优先开发等核心能力，帮助开发者跨多种代理工具高效构建真实产品。

**核心功能**:
- **技能与直觉系统**：内置可复用的代理技能、钩子、规则和 MCP 配置，支持跨代理环境（Codex、Claude Code、Cursor、OpenCode、Gemini 等）无缝工作。
- **记忆与持续学习**：提供记忆优化和持续学习机制，让代理在长期项目中保持上下文和效率。
- **安全扫描与研究优先开发**：集成安全扫描功能，并支持研究驱动的开发流程，确保代码质量和安全性。
- **跨代理工作流**：支持在多个 AI 代理工具间协调工作，实现统一的工程工作流。
- **命令行兼容**：提供传统命令兼容层（shims），方便迁移和集成。
- **GitHub App 与 npm 包分发**：可通过 GitHub App 和 npm 包（`ecc-universal`、`ecc-agentshield`）安装使用。

**技术亮点**: 基于 JavaScript/TypeScript 开发，支持 Shell、Python、Go、Java、Perl 等多语言生态；采用模块化架构（Hermes 操作层），提供跨代理的统一系统；拥有 211K+ Star、32K+ Fork 和 230+ 贡献者，社区活跃。

---
