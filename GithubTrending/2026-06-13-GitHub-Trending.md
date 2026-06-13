---
tags:
  - github-trending
  - daily
date: 2026-06-13
created: 2026-06-13T01:55:43.615Z
---

# 2026-06-13 GitHub Trending Top 10

## 1. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: Shell
- **Stars**: 56,855
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: 该项目为 AI 编程代理提供了一套生产级的工程技能，将资深工程师的工作流、质量门禁和最佳实践编码为技能，确保代理在软件开发的各个阶段（从定义到发布）都能一致地遵循。

**核心功能**:
- **生命周期命令**: 提供 7 个斜杠命令 (`/spec`, `/plan`, `/build`, `/test`, `/review`, `/code-simplify`, `/ship`)，分别对应软件开发的不同阶段（定义、计划、构建、测试、审查、简化、发布），并自动激活相应的技能。
- **自动构建模式**: `/build auto` 命令允许在批准一次计划后，由代理自动完成计划的生成和所有任务的实现，每个任务仍保持测试驱动和独立提交，并在失败时暂停。
- **智能上下文感知**: 技能会根据当前操作自动激活，例如设计 API 时触发 `api-and-interface-design` 技能，构建 UI 时触发 `frontend-ui-engineering` 技能。
- **跨平台兼容**: 支持在 Claude Code、Cursor、Gemini CLI、Windsurf、GitHub Copilot 等多种主流 AI 编程工具中安装和使用。

**技术亮点**:
- **纯 Markdown 技能**: 所有技能文件均为纯 Markdown 格式，可被任何接受系统提示或指令文件的代理使用，具有极高的通用性和可移植性。
- **插件化架构**: 作为插件发布，支持通过各平台的市场或本地克隆方式进行安装，易于集成和扩展。

---
## 2. [music-assistant/server](https://github.com/music-assistant/server)
- **语言**: Python
- **Stars**: 1,789
- **简介**: Music Assistant is a free, opensource Media library manager that connects to your streaming services and a wide range of connected speakers. The server is the beating heart, the core of Music Assistant and must run on an always-on device like a Raspberry Pi, a NAS or an Intel NUC or alike.

### AI 总结
**简介**: Music Assistant 是一个免费开源的媒体库管理器，可连接流媒体服务和多种智能音箱，其服务器需在常开设备上运行。

**核心功能**:
- 支持连接多种流媒体服务和智能音箱设备
- 提供媒体库集中管理功能
- 与 Home Assistant 深度集成，支持自动化控制

**技术亮点**: 基于 Python 开发，依赖 Docker 容器或 Home Assistant 插件方式运行，需 ffmpeg 等外部组件支持。

---
## 3. [mattermost/mattermost](https://github.com/mattermost/mattermost)
- **语言**: TypeScript
- **Stars**: 37,638
- **简介**: Mattermost is an open source platform for secure collaboration across the entire software development lifecycle..

### AI 总结
**简介**: Mattermost 是一个开源、自托管的协作平台，提供安全聊天、工作流自动化、语音/屏幕共享和AI集成，覆盖软件开发全生命周期。

**核心功能**:
- 团队即时消息与频道管理
- 工作流自动化与DevSecOps集成
- 语音通话与屏幕共享
- AI功能集成（如智能回复、自动化）
- 跨平台客户端支持（Web、桌面、移动端）

**技术亮点**: 基于Go和React构建，单Linux二进制部署，依赖PostgreSQL，每月16日发布MIT许可新版本，支持Docker、Kubernetes、Helm等多种部署方式，提供API、Webhook、Slash命令和插件扩展。

---
## 4. [apple/container](https://github.com/apple/container)
- **语言**: Swift
- **Stars**: 35,150
- **简介**: A tool for creating and running Linux containers using lightweight virtual machines on a Mac. It is written in Swift, and optimized for Apple silicon.

### AI 总结
**简介**: `container` 是苹果开源的一款工具，用于在 Mac（Apple Silicon）上创建和运行 Linux 容器，以轻量级虚拟机的方式运行。

**核心功能**:
- 支持创建、运行和管理 OCI 兼容的容器镜像
- 可从标准容器仓库拉取和推送镜像
- 提供系统服务管理（启动/停止/卸载）
- 支持升级、降级和保留用户数据的卸载选项

**技术亮点**:
- 使用 Swift 编写，针对 Apple Silicon 优化
- 基于 [Containerization](https://github.com/apple/containerization) Swift 包实现底层容器、镜像和进程管理
- 利用 macOS 26 的虚拟化和网络增强特性
- 生产 OCI 兼容镜像，与其他容器工具互操作

---
## 5. [iptv-org/iptv](https://github.com/iptv-org/iptv)
- **语言**: TypeScript
- **Stars**: 118,053
- **简介**: Collection of publicly available IPTV channels from all over the world

### AI 总结
**简介**: 收集全球公开可用的 IPTV 频道播放列表的开源项目。

**核心功能**:
- 提供全球 IPTV 频道的主播放列表（`index.m3u`）及分类播放列表
- 支持通过电子节目指南（EPG）获取频道节目信息
- 提供频道数据库和 API 接口，便于开发者集成

**技术亮点**: 基于 TypeScript 开发，通过 GitHub Actions 自动更新播放列表，数据源来自 `iptv-org/database` 仓库

---
## 6. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 226,032
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一套为编码代理设计的完整软件开发方法论，基于可组合的技能和初始指令，确保代理遵循规范的开发流程。

**核心功能**:
- **需求澄清**: 代理不会直接写代码，而是先通过提问梳理需求，生成可验证的设计文档。
- **隔离工作区**: 设计批准后，自动创建独立分支和隔离工作区，确保项目基线干净。
- **任务拆解**: 将实现计划分解为2-5分钟的细粒度任务，每个任务包含精确文件路径、完整代码和验证步骤。
- **子代理驱动开发**: 启动子代理逐任务执行，自动审查工作，支持数小时自主开发而不偏离计划。
- **多平台支持**: 兼容 Claude Code、Codex CLI、Cursor 等主流编码代理平台，提供统一方法论。

**技术亮点**: 基于 Shell 脚本实现，采用可组合技能架构，强调 TDD、YAGNI、DRY 原则，通过子代理并行执行提升开发效率。

---
## 7. [refactoringhq/tolaria](https://github.com/refactoringhq/tolaria)
- **语言**: TypeScript
- **Stars**: 15,786
- **简介**: Desktop app to manage markdown knowledge bases

### AI 总结
**简介**: Tolaria 是一款跨平台桌面应用，用于管理基于 Markdown 的知识库，支持 macOS、Windows 和 Linux。

**核心功能**:
- 以文件优先的方式管理笔记，所有数据均为纯 Markdown 文件，可移植且无需导出
- 基于 Git 的版本管理，每个知识库都是一个 Git 仓库，支持完整历史记录和远程同步
- 离线优先，无需账户、订阅或云依赖，数据完全由用户掌控
- 支持通过类型（Types）作为导航辅助，而非强制模式，便于组织笔记
- 内置 AI 集成支持，可配合 Claude Code、Codex CLI 等工具使用
- 键盘优先设计，提供强大的命令面板和编辑器快捷键

**技术亮点**: 基于 Tauri、React 和 TypeScript 构建，采用 Rust 原生性能与 Web 开发效率结合的架构，支持离线运行且无供应商锁定。

---
## 8. [maziyarpanahi/openmed](https://github.com/maziyarpanahi/openmed)
- **语言**: Python
- **Stars**: 3,198
- **简介**: open-source healthcare ai

### AI 总结
**简介**: OpenMed 是一个本地优先的开源医疗 AI 工具，可在设备端完成临床文本的结构化分析、实体提取和 PII 脱敏，无需联网或调用云端 API。

**核心功能**:
- **临床实体提取**: 一行代码即可从临床文本中提取疾病、药物等结构化信息。
- **PII 脱敏**: 内置 Nemotron 隐私过滤器，实时识别和移除患者姓名、地址、ID 等敏感信息。
- **1000+ 专业医疗模型**: 支持 12 种语言，涵盖 247 个 PII 检测检查点，全部在本地运行。
- **多平台支持**: 提供 Python 库和 Swift 框架（OpenMedKit），可在 iPhone、iPad、Mac 上离线运行。

**技术亮点**:
- 基于 Apple MLX 框架，在 Apple Silicon 设备上实现全设备端推理。
- 采用 Apache-2.0 开源许可，无供应商锁定，数据不离开本地网络。
- 支持 Python 3.10+，可通过 PyPI 一键安装，并集成 Hugging Face 模型仓库。

---
## 9. [LMCache/LMCache](https://github.com/LMCache/LMCache)
- **语言**: Python
- **Stars**: 8,644
- **简介**: LMCache: Supercharge Your LLM with the Fastest KV Cache Layer

### AI 总结
**简介**: LMCache 是一个通过 KV 缓存层加速 LLM 推理的开源项目，支持跨 vLLM 实例共享缓存以降低首 token 延迟。

**核心功能**:
- 提供 KV 缓存加速层，显著降低长上下文场景下的首 token 生成时间（TTFT）
- 支持跨多个 vLLM 实例共享前缀 KV 缓存，减少重复计算
- 提供 Docker 化快速部署方案，支持单 GPU 和多 GPU 环境

**技术亮点**:
- 基于 Python 实现，与 vLLM 推理引擎深度集成
- 通过 LMCache 后端服务器实现分布式缓存共享
- 支持通过配置文件灵活调整缓存策略

---
## 10. [phuryn/pm-skills](https://github.com/phuryn/pm-skills)
- **语言**: Unknown
- **Stars**: 17,009
- **简介**: PM Skills Marketplace: 100+ agentic skills, commands, and plugins — from discovery to strategy, execution, launch, and growth.

### AI 总结
**简介**: PM Skills Marketplace 是一个为 AI 助手（如 Claude Code、Cowork）设计的插件市场，提供 100+ 个产品管理技能、命令和插件，覆盖从发现、策略、执行到增长的全流程，帮助产品经理做出更好的产品决策。

**核心功能**:
- **Skills（技能）**: 内置 68 个经过验证的 PM 框架（如机会解决方案树、优先级排序），AI 助手可自动按需加载，无需手动调用。
- **Commands（命令）**: 提供 42 个用户触发的端到端工作流（如 `/discover` 链式调用 brainstorm-ideas → identify-assumptions → prioritize-assumptions → brainstorm-experiments），命令间可无缝衔接。
- **Plugins（插件）**: 将相关技能和命令打包为 9 个可安装插件（如发现、策略、执行、增长等），一键安装即可获得全套能力。

**技术亮点**: 采用模块化插件架构，支持 Claude Code（CLI）、Claude Cowork（图形界面）和 Codex CLI（OpenAI）多种安装方式；技能通过上下文自动加载，无需显式调用，降低使用门槛；命令链式设计模拟真实 PM 工作流，提升决策效率。

---
