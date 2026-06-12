---
tags:
  - github-trending
  - daily
date: 2026-06-12
created: 2026-06-12T01:55:43.899Z
---

# 2026-06-12 GitHub Trending Top 10

## 1. [apple/container](https://github.com/apple/container)
- **语言**: Swift
- **Stars**: 32,651
- **简介**: A tool for creating and running Linux containers using lightweight virtual machines on a Mac. It is written in Swift, and optimized for Apple silicon.

### AI 总结
**简介**: container 是苹果推出的 Swift 工具，可在 Mac（Apple Silicon）上创建并运行基于轻量级虚拟机的 Linux 容器，兼容 OCI 镜像规范。

**核心功能**:
- 创建、运行和管理 Linux 容器（作为轻量级虚拟机）
- 拉取、推送和运行 OCI 兼容的容器镜像（支持标准容器仓库）
- 提供系统服务管理（启动/停止/升级/卸载）
- 支持通过脚本进行版本升级或降级，并保留或清除用户数据

**技术亮点**:
- 使用 Swift 编写，专为 Apple Silicon 优化
- 依赖 [Containerization](https://github.com/apple/containerization) Swift 包实现底层容器、镜像和进程管理
- 要求 macOS 26 及以上版本，利用新虚拟化和网络增强特性
- 目前处于活跃开发阶段（0.x 版本，小版本内保持稳定，大版本可能包含破坏性变更）

---
## 2. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: Shell
- **Stars**: 54,872
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 该项目为 AI 编码智能体提供了一套生产级工程技能，将资深工程师的工作流、质量门禁和最佳实践编码为智能体可遵循的指令。

**核心功能**:
- 提供 7 个斜杠命令 (`/spec`, `/plan`, `/build`, `/test`, `/review`, `/code-simplify`, `/ship`)，映射完整的开发周期，自动激活相应技能。
- 包含 24 个独立的 Markdown 技能文件，覆盖 API 设计、前端工程、测试驱动开发等场景。
- 提供 `/build auto` 自动模式，在一次性批准计划后，自主完成所有任务的实现、测试和提交。
- 支持 Claude Code、Cursor、Gemini CLI、Windsurf、GitHub Copilot 等多种主流 AI 编程工具和 IDE。

**技术亮点**: 技能以纯 Markdown 格式编写，与任何接受系统提示或指令文件的智能体兼容，具备极强的可移植性。

---
## 3. [maziyarpanahi/openmed](https://github.com/maziyarpanahi/openmed)
- **语言**: Python
- **Stars**: 2,790
- **简介**: open-source healthcare ai

### AI 总结
**简介**: OpenMed 是一个本地优先的开源医疗 AI 工具，专为临床文本处理设计，可在设备端完全离线运行，无需云端或网络调用。

**核心功能**:
- 实体提取：从临床文本中提取疾病、药物等结构化信息，支持 1,000+ 专业医疗模型
- PII 脱敏：实时识别并移除患者姓名、地址、ID 等个人隐私信息，保护数据安全
- 多语言支持：覆盖 12 种语言，包括中文、英语、西班牙语等
- 跨平台运行：支持 Python 编程和 iOS/iPadOS/macOS 原生应用（通过 OpenMedKit 和 Apple MLX）

**技术亮点**:
- 基于本地硬件（如 Apple Silicon）运行，使用 Apple MLX 框架加速推理
- 提供 247 个 PII 检测检查点，确保隐私过滤的准确性
- 采用 Apache-2.0 开源许可证，完全免费且无供应商锁定

---
## 4. [phuryn/pm-skills](https://github.com/phuryn/pm-skills)
- **语言**: Unknown
- **Stars**: 16,262
- **简介**: PM Skills Marketplace: 100+ agentic skills, commands, and plugins — from discovery to strategy, execution, launch, and growth.

### AI 总结
**简介**: PM Skills Marketplace 是一个为 AI 助手（如 Claude Code）设计的技能市场，提供超过 100 种产品管理技能、命令和插件，覆盖从发现、策略到执行、发布和增长的完整产品生命周期。

**核心功能**:
- **技能 (Skills)**: 内置 68 个基于成熟 PM 框架（如 Teresa Torres、Marty Cagan）的技能，自动按需加载，提供领域知识和分析框架。
- **命令 (Commands)**: 用户通过 `/discover`、`/write-prd` 等 42 个命令触发端到端工作流，可串联多个技能完成复杂任务。
- **插件 (Plugins)**: 9 个按 PM 领域（如发现、策略、执行）分组的可安装包，一次性安装即可获得所有技能和命令。
- **工作流衔接**: 命令执行后自动建议下一步相关命令，贴合产品经理的实际工作流程。

**技术亮点**: 采用技能-命令-插件的分层架构设计，技能可被多个命令复用；支持 Claude Cowork、Claude Code 和 Codex CLI 等多种 AI 助手，通过 GitHub 市场安装即可使用。

---
## 5. [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector)
- **语言**: Python
- **Stars**: 2,709
- **简介**: Security scanner for AI agent skills. Detect vulnerabilities, malicious patterns, and security risks.

### AI 总结
**简介**: SkillSpector 是 NVIDIA 开源的 AI 智能体技能安全扫描器，用于在安装前检测漏洞、恶意模式和安全隐患。

**核心功能**:
- 支持多格式输入：扫描 Git 仓库、URL、ZIP 文件、目录或单个文件
- 检测 64 种漏洞模式，覆盖 16 类安全风险（如提示注入、数据泄露、权限提升、供应链攻击等）
- 提供两阶段分析：快速静态分析 + 可选的 LLM 语义评估
- 支持实时漏洞查询（通过 OSV.dev 获取 CVE 数据，并自动离线回退）
- 输出多种报告格式：终端、JSON、Markdown 和 SARIF
- 提供 0-100 风险评分及严重等级标签与建议

**技术亮点**: 基于 Python 开发，支持 OpenAI、Anthropic、NVIDIA 及本地 Ollama 等 LLM 提供商的语义分析，集成 AST 分析、污点追踪和 YARA 签名等高级检测技术。

---
## 6. [soxoj/maigret](https://github.com/soxoj/maigret)
- **语言**: Python
- **Stars**: 32,637
- **简介**: 🕵️‍♂️ Collect a dossier on a person by username from 3000+ sites

### AI 总结
**简介**: Maigret 是一款强大的开源个人信息搜集工具，仅通过用户名即可在 3000 多个网站上搜索并收集该用户的所有公开信息。

**核心功能**:
- 支持搜索 3000+ 网站，默认检查流量最高的 500 个网站，也可通过 `-a` 参数进行全站扫描
- 从个人资料页面和网站 API 中提取所有可用信息，包括关联的其他账号链接
- 支持递归搜索，利用发现的用户名和其他 ID 进行深层挖掘
- 提供基于标签（网站类别、国家）的过滤功能，支持按需定向搜索
- 具备智能规避机制，可检测并部分绕过封锁、审查和验证码
- 支持 Tor 和 I2P 匿名网络，并可检查域名信息
- 内置 Web 界面，可将结果以图形化方式展示，并支持多种格式报告下载
- 提供可选的 AI 分析模式，通过 OpenAI 兼容 API 自动生成调查摘要

**技术亮点**: 纯 Python 实现，无需 API Key，支持作为 Python 库嵌入其他项目；自动从 GitHub 更新网站数据库（每 24 小时一次），离线时自动回退到内置数据库；支持代理和多种输出格式。

---
## 7. [x1xhlol/system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools)
- **语言**: Unknown
- **Stars**: 139,887
- **简介**: FULL Augment Code, Claude Code, Cluely, CodeBuddy, Comet, Cursor, Devin AI, Junie, Kiro, Leap.new, Lovable, Manus, NotionAI, Orchids.app, Perplexity, Poke, Qoder, Replit, Same.dev, Trae, Traycer AI, VSCode Agent, Warp.dev, Windsurf, Xcode, Z.ai Code, Dia & v0. (And other Open Sourced) System Prompts, Internal Tools & AI Models

### AI 总结
**简介**: 收集并公开大量AI工具（如Claude Code、Cursor、Devin AI等）的系统提示词、内部工具及AI模型的仓库，并附带安全提醒和赞助支持选项。

**核心功能**:
- 汇总各类AI开发工具的系统提示词与内部模型信息
- 提供加密货币、Patreon、Ko-fi等多种捐赠渠道支持项目
- 集成Star历史图表，展示项目增长趋势

**技术亮点**: 项目引用Trendshift和Star History等工具展示流行度，并提供开源监控平台Latitude-LLM的推广链接。

---
## 8. [refactoringhq/tolaria](https://github.com/refactoringhq/tolaria)
- **语言**: TypeScript
- **Stars**: 15,421
- **简介**: Desktop app to manage markdown knowledge bases

### AI 总结
**简介**: Tolaria 是一款跨平台桌面应用，用于管理基于 Markdown 的个人知识库，支持离线优先、Git 版本控制，并内置 AI 集成能力。

**核心功能**:
- 基于纯 Markdown 文件的知识库管理，支持 YAML frontmatter，数据完全可移植
- 每个知识库均为 Git 仓库，支持完整版本历史与任意 Git 远程仓库
- 离线优先设计，无需账户、订阅或云端依赖
- AI 优先但非绑定，支持 Claude Code、Codex CLI、Gemini CLI 等 AI 工具集成
- 键盘优先操作，提供强大的命令面板和编辑器
- 支持 macOS、Windows、Linux，可通过 Homebrew 或 GitHub Releases 安装

**技术亮点**: 基于 Tauri + React + TypeScript 构建，使用 Rust 作为底层，支持跨平台原生性能；采用文件优先架构，无专有格式锁定；内置 AGENTS 文件供 AI 代理自动理解知识库结构。

---
## 9. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 224,893
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套为编码代理设计的完整软件开发方法论，基于一组可组合的技能和初始指令构建，确保代理遵循规范流程。

**核心功能**:
- **头脑风暴**: 在编写代码前，通过提问细化想法，探索替代方案，并以可读的区块呈现设计供验证。
- **Git 工作树隔离**: 在设计批准后，创建独立工作空间和新分支，运行项目设置并验证测试基线。
- **编写计划**: 将工作分解为 2-5 分钟的小任务，每个任务包含精确文件路径、完整代码和验证步骤。
- **子代理驱动开发**: 启动子代理处理每个工程任务，自动审查工作，支持长达数小时的自主运行。

**技术亮点**: 基于 Shell 脚本实现，支持多种代理平台（Claude Code、Codex CLI、Cursor 等）；强调 TDD、YAGNI 和 DRY 原则；通过自动触发的技能系统实现零额外操作。

---
## 10. [restic/restic](https://github.com/restic/restic)
- **语言**: Go
- **Stars**: 34,179
- **简介**: Fast, secure, efficient backup program

### AI 总结
**简介**: restic 是一款用 Go 语言编写的快速、安全、高效的跨平台备份工具。

**核心功能**:
- 支持多种存储后端，包括本地目录、SFTP、HTTP REST 服务器、Amazon S3、OpenStack Swift、BackBlaze B2、Microsoft Azure Blob Storage、Google Cloud Storage 以及通过 rclone 集成的众多服务
- 提供备份、恢复和挂载功能，可通过 FUSE 挂载仓库浏览历史快照
- 支持数据加密，保证数据机密性和完整性
- 支持增量备份和数据去重，仅存储实际变化的数据
- 提供快照验证功能，确保数据可恢复

**技术亮点**:
- 使用 Go 语言开发，跨平台支持 Linux、macOS、Windows、FreeBSD、OpenBSD
- 采用密码学技术保护数据，支持不可信存储环境
- 支持可重现构建，确保二进制文件与源代码完全一致
- 使用 FUSE 文件系统挂载功能，便于浏览和恢复历史版本

---
