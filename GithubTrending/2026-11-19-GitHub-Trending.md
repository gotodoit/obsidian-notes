---
tags:
  - github-trending
  - daily
date: 2026-11-19
created: 2026-11-19T01:55:44.849Z
---

# 2026-11-19 GitHub Trending Top 10

## 1. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 17,228
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，提供面向主流开发工具、框架和 SaaS 产品的插件规范与官方插件集合，每个插件以独立目录形式存在并配有 `.cursor-plugin/plugin.json` 清单文件。

**核心功能**:
- **开发工具类插件**：涵盖教学辅助（Teaching）、持续学习记忆更新（Continual Learning）、团队工作流（Cursor Team Kit）、深度安全与代码质量审计（Thermos）、插件脚手架生成（Create Plugin）、迭代式 AI 循环（Ralph Loop）、仓库兼容性扫描（Agent Compatibility）、CLI 设计规范（CLI for Agents）、PR 差异画布渲染（PR Review Canvas）、文档画布（Docs Canvas）、TypeScript SDK 应用构建（Cursor SDK）、Origin API 开发（Origin Apps）、并行云代理任务编排（Orchestrate）、高质量代码工作流（pstack / dyl-stack）、强模型咨询（Advisor）及 Grok 语音集成（Grok Voice）等。
- **生产力类插件**：集成 Gmail、Google Drive、Google Calendar、Google Docs、Google Sheets、Google Slides，支持邮件管理、文件读写共享、日程安排和文档编辑。
- **集成类插件**：对接 Google Ads、Google Analytics、Google Search Console、Gong、Salesforce 等，支持广告投放报告、GA4 数据分析、搜索性能查询及销售数据洞察。

**技术亮点**: 使用 TypeScript 开发；采用插件化架构，每个插件为仓库根目录下的独立目录，通过统一的 `.cursor-plugin/plugin.json` 清单进行声明管理；插件按 Utilities、Developer Tools、Productivity、Integrations 等类别组织，支持第三方与社区作者贡献。

---
## 2. [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)
- **语言**: Python
- **Stars**: 59,792
- **简介**: "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/

### AI 总结
**简介**: HKUDS/CLI-Anything 是一个 Python 项目，旨在为各类软件自动生成命令行接口（CLI），让 AI Agent 能够直接操作现实世界的软件，弥合 AI 与软件生态之间的鸿沟。

**核心功能**:
- 为任意软件生成 Agent 可用的 CLI，支持 Pi、OpenClaw、nanobot、Cursor、Claude Code 等 Agent 平台
- 提供 CLI-Hub 社区中心（`pip install cli-anything-hub` + `cli-hub install <name>`），可浏览、安装和管理社区构建的 CLI
- 支持预览、实时预览与轨迹循环，让 Agent 产出真实制品（CAD 构建、3D 场景、图表、游戏画面、字幕等）
- 开放贡献机制：可提交新 CLI harness 或软件心愿单请求

**技术亮点**: 基于 Python ≥3.10 与 Click ≥8.0 构建，输出支持 JSON 与人类可读双格式；测试体系完善（2,461 项测试通过，覆盖单元与端到端测试），采用 Apache 2.0 许可，并有配套 arXiv 技术报告。

---
## 3. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 70,057
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个 AI Agent 技能，可跨 Reddit、X、YouTube、HN、Polymarket 等多个平台并行检索任意话题，并按真实用户互动（点赞、投票、真金白银的赔率）打分，最终由 AI 综合成一份有据可循的摘要。

**核心功能**:
- 多源并行搜索：一次性覆盖 Reddit、X/Twitter、YouTube、Hacker News、Polymarket、GitHub、arXiv、TikTok、Techmeme 等平台，以及专利和招聘页面
- 按真实互动排序：以 Reddit 点赞、X 喜欢、YouTube 字幕、Polymarket 赔率等真实用户行为作为排序依据，而非编辑推荐
- AI 综合摘要：由 AI Agent 担任裁判，将多平台结果融合成一份统一的简报
- 零配置开箱即用：Reddit、HN、Polymarket、GitHub 无需配置即可使用，运行一次后向导可在 30 秒内解锁其余平台
- 多宿主安装：支持 Claude Code 插件市场、Codex、Cursor、Copilot、Gemini CLI 等 50+ Agent Skills 宿主

**技术亮点**: 基于 Python 实现；采用"自带密钥/浏览器会话"的方式桥接各平台封闭 API，让单个 Agent 同时访问多个原本互不相通的数据源；提供 SKILL.md 作为运行时技能规范，并通过 GitHub Actions 进行校验。

---
## 4. [getarcaneapp/arcane](https://github.com/getarcaneapp/arcane)
- **语言**: Go
- **Stars**: 9,832
- **简介**: Modern Docker Management, Designed for Everyone

### AI 总结
**简介**: Arcane 是一款面向所有人的现代化 Docker 管理工具，当前 `main` 分支为 v3 版本。

**核心功能**:
- 提供现代化的 Docker 管理界面与仪表盘
- 支持多语言本地化（通过 Crowdin 协作翻译）
- 提供官方文档站点，涵盖安装、配置与开发指南

**技术亮点**: 使用 Go 语言开发（模块路径 `getarcane.dev/arcane/v3`），采用 BSD-3-Clause 开源协议，提供 SBOM 清单以增强安全透明度，并集成 Snyk 漏洞检测。

---
## 5. [NVIDIA/SkillEvaluator](https://github.com/NVIDIA/SkillEvaluator)
- **语言**: Python
- **Stars**: 3,747
- **简介**: Multi-tier framework for evaluating AI agent skills and plugins with quality gates, semantic overlap detection, synthetic evaluation dataset generation, and live agent evaluation that measures how skills affect agent behavior.

### AI 总结
**简介**: NVIDIA 开源的多层级 AI Agent 技能与插件评估框架，用于在合并前检查技能质量，并量化技能对 Agent 行为的实际影响。

**核心功能**:
- **质量与安全门禁**：基于 500+ 静态规则和检测模式做校验，无需 LLM 密钥即可运行
- **语义重叠检测**：识别技能间的重复与冲突，支持去重
- **合成评估数据集生成**：自动构建用于评测的数据集
- **实时 Agent 评估**：对比启用/禁用技能时的运行结果，衡量技能带来的实际提升（skill lift）
- **Harness 兼容性检查**：在无 API 密钥、不运行 Agent 的情况下，预判 Codex、Claude Code、opencode 等框架能否正确加载技能
- **CI 集成**：通过 `skillevaluator ci init` 一键生成 GitHub/GitLab 的 CI 模板，实现自动化质量与安全门禁

**技术亮点**: 采用三层分级评估架构（静态检查 → 去重 → 实时 Agent 评估），纯 Python 实现，支持 Python 3.12–3.14，可通过 pip/uv 安装；提供 CLI、CI 模板与 Agent 技能三种接入方式，并属于 NVIDIA Verified Skills 流水线的一部分。

---
## 6. [nvm-sh/nvm](https://github.com/nvm-sh/nvm)
- **语言**: Shell
- **Stars**: 96,158
- **简介**: Node Version Manager - POSIX-compliant bash script to manage multiple active node.js versions.

### AI 总结
**简介**: nvm 是一个符合 POSIX 规范的 bash 脚本工具，用于在命令行中快速安装和切换多个 Node.js 版本。

**核心功能**:
- 一行命令安装并切换不同 Node.js 版本（如 `nvm install 24`、`nvm use 22`）
- 支持按用户安装、按 shell 调用，兼容 sh、dash、ksh、zsh、bash 等 POSIX 兼容 shell
- 提供安装/更新脚本，并支持 Docker、Ansible、Git 安装及手动安装等多种部署方式
- 支持全局包在版本间迁移、离线安装、从文件安装默认全局包
- 支持 `.nvmrc` 文件，可在进入目录时自动切换 Node 版本（bash/zsh/fish 集成）
- 支持自定义镜像源、版本列表展示、自定义颜色、Bash 自动补全等

**技术亮点**: 纯 Shell（bash）实现，遵循 POSIX 标准，跨平台支持 Unix、macOS 与 Windows WSL；采用按用户、按 shell 的轻量设计，通过环境变量与 shell 集成实现版本管理，具备完善的测试与 CI 流程。

---
## 7. [astral-sh/uv](https://github.com/astral-sh/uv)
- **语言**: Rust
- **Stars**: 92,240
- **简介**: An extremely fast Python package and project manager, written in Rust.

### AI 总结
**简介**: uv 是一个用 Rust 编写的极速 Python 包与项目管理器，由 Ruff 团队 Astral 打造。

**核心功能**:
- 一体化替代 `pip`、`pip-tools`、`pipx`、`poetry`、`pyenv`、`twine`、`virtualenv` 等多个工具
- 项目管理：依赖与环境管理，支持通用 lockfile 和 Cargo 风格 workspaces
- 脚本运行：支持单文件脚本及内联依赖元数据声明
- Python 版本安装与管理
- 工具运行与安装（类似 pipx，提供 `uvx` 别名）
- 兼容 pip 的命令行接口，可无缝替换获得性能提升
- 项目构建与发布

**技术亮点**: 使用 Rust 编写，比 `pip` 快 10-100 倍；采用全局缓存实现依赖去重、节省磁盘空间；可通过 `curl` 或 `pip` 安装，无需预先具备 Rust 或 Python 环境；跨平台支持 macOS、Linux 和 Windows。

---
## 8. [google-research/paper-orchestra](https://github.com/google-research/paper-orchestra)
- **语言**: Python
- **Stars**: 4,331
- **简介**: PaperOrchestra is a multi-agent framework for automated AI research paper writing.

### AI 总结
**简介**: PaperOrchestra 是 Google Cloud AI Research 推出的多智能体框架，可将原始研究材料（想法与实验日志）自动转化为可投稿的 LaTeX 学术论文。

**核心功能**:
- **多智能体流水线**：由大纲生成、文献综述、章节写作、内容精炼、图表绘制等专用智能体协同完成端到端论文生成
- **文献综合**：自动检索、优先级排序并整合相关文献
- **可视化生成**：自动生成数据图表，并支持插入概念示意图
- **LaTeX 自动化**：按目标会议模板输出可直接投稿的 LaTeX 稿件

**技术亮点**: 基于 Python 3.11 与 Conda 环境构建，支持 Gemini（Vertex AI / API Key）和 OpenAI 等多种 LLM 后端，集成 Semantic Scholar 文献检索 API；提供 Bash 脚本与 Python CLI 两种调用方式，并附带 Streamlit 交互式演示前端；项目还包含自动评估模块（autoraters）与可扩展的会议 LaTeX 模板目录。

---
## 9. [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills)
- **语言**: TypeScript
- **Stars**: 10,416
- **简介**: A library of Agent Skills designed to work with the Stitch MCP server. Each skill follows the Agent Skills open standard, for compatibility with coding agents such as Antigravity, Gemini CLI, Claude Code, Cursor.

### AI 总结
**简介**: 面向 Google Stitch 的 Agent Skills 与插件库，遵循 Agent Skills 开放标准，可与 Codex、Antigravity、Gemini CLI、Claude Code、Cursor、OpenCode 等编码智能体配合使用。

**核心功能**:
- 提供 `stitch-design`（设计类技能，如将前端代码转换为 Stitch 设计、生成设计）、`stitch-build`（构建与组件类技能）、`stitch-utilities`（工具与辅助类技能）三组插件
- 支持整体安装插件套件或按需选择性安装单个技能（需注意技能间存在依赖关系）
- 针对不同智能体提供差异化安装方式：Codex 通过插件市场（CLI 或 UI，支持 sparse 稀疏检出）、Claude Code 与 Cursor 通过 `npx plugins add` 按项目/工作区安装、OpenCode 需手动复制技能目录并配置远程 MCP 条目

**技术亮点**: 基于 TypeScript 实现；遵循 Agent Skills 开放标准以获得跨智能体兼容性；依赖 Stitch MCP 服务器运行；提供 `npx skills` / `npx plugins` 命令行工具管理安装；对 OpenCode 有命名规范适配要求（技能名需为小写 kebab-case 并与目录名一致，工具名需映射为其内置名称）。

---
## 10. [sveltejs/svelte](https://github.com/sveltejs/svelte)
- **语言**: JavaScript
- **Stars**: 89,631
- **简介**: web development for the rest of us

### AI 总结
**简介**: Svelte 是一种全新的 Web 应用构建方式，通过编译器将声明式组件转换为高效的原生 JavaScript 代码。

**核心功能**:
- 将声明式组件编译为高效的 JavaScript 代码
- 精准地（surgically）更新 DOM，而非依赖运行时框架
- 提供官方文档与 Discord 社区支持

**技术亮点**: 采用编译时架构（编译器型框架），在构建阶段将组件转换为优化的原生 JS，避免运行时虚拟 DOM 开销；项目基于 JavaScript，采用 MIT 开源协议，由志愿者社区驱动开发。

---
