---
tags:
  - github-trending
  - daily
date: 2026-11-07
created: 2026-11-07T01:55:43.168Z
---

# 2026-11-07 GitHub Trending Top 10

## 1. [zed-industries/zed](https://github.com/zed-industries/zed)
- **语言**: Rust
- **Stars**: 93,660
- **简介**: Code at the speed of thought – Zed is a high-performance, multiplayer code editor from the creators of Atom and Tree-sitter.

### AI 总结
**简介**: Zed 是由 Atom 和 Tree-sitter 创作者打造的高性能多人协作代码编辑器，采用 Rust 编写。

**核心功能**:
- 高性能、支持多人实时协作的代码编辑体验
- 支持 macOS、Linux、Windows 平台，可通过官网直接下载或包管理器安装（Web 版尚在规划中）

**技术亮点**: 使用 Rust 语言开发以保证性能；源码主要以 GPL-3.0-or-later 许可发布，部分组件采用 Apache-2.0，并使用 `cargo-about` 自动化管理第三方依赖的开源许可合规。

---
## 2. [NVIDIA/auto-ontology](https://github.com/NVIDIA/auto-ontology)
- **语言**: Python
- **Stars**: 9,087
- **简介**: Auto Ontology is a Python framework for building semantic, graph-based reasoning layers over data. It enables deterministic query generation, better context retrieval, and more explainable AI for LLM and agent workflows.

### AI 总结
**简介**: NVIDIA Auto Ontology 是一个基于 Python 的语义图谱推理层框架，用于为 LLM 和 Agent 工作流构建可信、可解释的数据上下文层。

**核心功能**:
- **发现（Discover）**：从企业元数据生成本体，连接已有本体与语义模型，构建面向 AI 的知识图谱。
- **落地（Ground）**：为指标、实体和关系提供可信的业务语义，并跨系统协调不一致的定义。
- **校验（Validate）**：依据认证定义与血缘检查生成的查询，为每个答案返回数据来源。
- **暴露（Expose）**：通过 MCP、CLI 和 API 向任意 Agent 框架提供上下文。
- **学习（Learn）**：将认证修正与使用反馈回灌本体，使共享上下文随每次提问不断改进。
- **自然语言查询**：将问题翻译为 SQL 并在连接的数据库上执行，由 NVIDIA NIM 驱动。

**技术亮点**:
- 前端采用 Next.js 16（React 19、TypeScript、Tailwind CSS 4）、Better Auth 与 Prisma；后端基于 FastAPI（Python 3.12+）与 LangChain。
- 使用 Postgres + pgvector 同时存储应用元数据、本体目录与向量，支持可选 HashiCorp Vault 管理连接凭据。
- 推理依赖 NVIDIA NIM（托管 API 或自托管），支持 LLM、Embedding、Rerank 多角色模型三元组配置。
- 提供 Kubernetes Helm Chart 与 Docker Compose 两种部署方式，采用 Apache 2.0 许可。

---
## 3. [rails/rails](https://github.com/rails/rails)
- **语言**: Ruby
- **Stars**: 59,032
- **简介**: Ruby on Rails

### AI 总结
**简介**: Ruby on Rails 是一个基于 MVC 模式的 Web 应用框架，内置创建数据库驱动 Web 应用所需的全部组件。

**核心功能**:
- **Model 层**：通过 Active Record 将数据库行映射为对象并封装业务逻辑，也可使用普通 Ruby 类或 Active Model 接口
- **View 层**：由 Action View 处理模板渲染，常用 ERB（HTML 内嵌 Ruby），用于生成控制器响应或邮件正文
- **Controller 层**：由 Action Pack（Action Dispatch + Action Controller）负责路由与处理 HTTP 请求，可返回 HTML、JSON、XML、PDF 等
- **附加组件**：Action Mailer（发送邮件）、Action Mailbox（接收邮件）、Active Job（后台任务）、Action Cable（WebSocket）、Active Storage（文件存储）、Action Text（富文本）、Active Support（工具类库）

**技术亮点**: 遵循 MVC 分层架构，各核心组件（Active Record、Active Model、Action Pack、Action View）可脱离 Rails 独立使用；采用 MIT 开源协议；通过 `gem install rails` 与 `rails new` 即可快速搭建项目。

---
## 4. [mpv-player/mpv](https://github.com/mpv-player/mpv)
- **语言**: C
- **Stars**: 37,886
- **简介**: 🎥 Command line media player

### AI 总结
**简介**: mpv 是一款自由开源的命令行媒体播放器，基于 C 语言开发，支持广泛的媒体格式、音视频编解码器与字幕类型。

**核心功能**:
- 支持多种媒体文件格式、音视频编解码器及字幕类型
- 提供丰富的命令行参数，可通过 `--hwdec` 显式启用硬件解码
- 内置 OSC 伪图形界面（依赖 Lua），并支持 youtube-dl 集成
- 提供用户脚本扩展机制（User Scripts）与完整的手册文档

**技术亮点**: 采用 Meson 构建系统；主视频输出基于着色器进行渲染与缩放，而非 GPU 固定功能硬件；依赖 FFmpeg、libplacebo、libass 等库；支持 nvdec/vaapi 硬件解码；对低功耗 GPU 提供 `--profile=fast` 优化配置。

---
## 5. [rust-lang/rust](https://github.com/rust-lang/rust)
- **语言**: Rust
- **Stars**: 121,464
- **简介**: Empowering everyone to build reliable and efficient software.

### AI 总结
**简介**: Rust 编程语言的主源码仓库，包含编译器、标准库和文档，致力于让每个人都能构建可靠且高效的软件。

**核心功能**:
- 高性能：运行快速且内存高效，适用于关键服务、嵌入式设备，并易于与其他语言集成。
- 高可靠性：借助丰富的类型系统和所有权模型保障内存与线程安全，在编译期减少缺陷。
- 高生产力：提供完善文档、注重诊断质量的编译器，以及 Cargo（包管理与构建工具）、rustfmt（自动格式化）、Clippy（代码检查）和 rust-analyzer（编辑器支持）等工具链。

**技术亮点**: 采用所有权与借用检查机制实现编译期内存安全；拥有完整的官方工具生态（Cargo、rustfmt、Clippy、rust-analyzer）；采用 MIT 与 Apache 2.0 双许可，商标由 Rust Foundation 持有和保护。

---
## 6. [react/react](https://github.com/react/react)
- **语言**: JavaScript
- **Stars**: 252,263
- **简介**: The library for web and native user interfaces.

### AI 总结
**简介**: React 是一个用于构建 Web 和原生用户界面的 JavaScript 库，采用声明式、组件化的方式开发交互式 UI。

**核心功能**:
- **声明式渲染**：为每个状态设计简单视图，数据变化时 React 高效更新并渲染正确的组件，代码更可预测、易理解、易调试
- **组件化开发**：构建封装自身状态的组件，再组合成复杂 UI，组件逻辑用 JavaScript 编写，可轻松传递数据并将状态与 DOM 分离
- **一次学习，随处编写**：不假设技术栈，可在不重写现有代码的情况下开发新功能，支持通过 Node 进行服务端渲染，并通过 React Native 驱动移动应用
- **渐进式采用**：可按需使用任意多或任意少的 React，支持快速上手、添加到现有项目或创建全新应用

**技术亮点**: 使用 JSX（类 HTML 语法，非必需但提升可读性）；提供完整文档体系（快速入门、教程、状态管理、高级指南、API 参考等）；采用 MIT 许可证；支持服务端渲染与跨平台（React Native）开发。

---
## 7. [angular/angular](https://github.com/angular/angular)
- **语言**: TypeScript
- **Stars**: 101,372
- **简介**: Deliver web apps with confidence 🚀

### AI 总结
**简介**: Angular 是一个基于 TypeScript/JavaScript 的现代 Web 开发平台，用于构建移动端和桌面端 Web 应用。

**核心功能**:
- 组件与模板系统，支持构建可复用的 UI
- 表单处理（Forms）
- 服务端渲染（SSR）
- 懒加载（Lazy Loading）与路由
- 动画支持（Animations）
- Angular Elements，可将组件打包为自定义元素
- Schematics 代码生成工具

**技术亮点**: 采用 TypeScript 为主要开发语言，提供 Angular CLI 命令行工具与 Angular Material 组件库，具备跨平台、高性能、可扩展的特点，并拥有完善的工具链生态。

---
## 8. [symfony/symfony](https://github.com/symfony/symfony)
- **语言**: PHP
- **Stars**: 31,438
- **简介**: The Symfony PHP framework

### AI 总结
**简介**: Symfony 是一个用于 Web 和控制台应用的 PHP 框架，同时提供一套可复用的 PHP 组件，被数千个 Web 应用及多数主流 PHP 项目所采用。

**核心功能**:
- 支持 Web 应用与控制台应用开发
- 提供可独立复用的 PHP 组件库
- 通过 Composer 安装，并严格遵循语义化版本规范
- 提供可预测、对企业友好的发布流程，包含 LTS（长期支持）版本

**技术亮点**: 基于 PHP 构建；采用组件化架构，组件可独立复用；严格遵循 SemVer 语义化版本；拥有完善的文档体系（入门指南、组件文档、最佳实践）和活跃的社区支持渠道（GitHub Discussions、Slack 等）。

---
## 9. [prometheus/prometheus](https://github.com/prometheus/prometheus)
- **语言**: Go
- **Stars**: 67,194
- **简介**: The Prometheus monitoring system and time series database.

### AI 总结
**简介**: Prometheus 是 CNCF 旗下的系统与服务监控系统及时间序列数据库，用 Go 语言编写，能够按设定间隔从目标采集指标、评估规则表达式、展示结果并在条件满足时触发告警。

**核心功能**:
- 多维度数据模型：时间序列由指标名称和一组键值维度定义
- PromQL 查询语言：强大且灵活，充分利用数据的多维特性
- 指标采集：基于 HTTP 拉取模型，同时支持通过中间网关推送批量任务的时序数据
- 目标发现：支持服务发现或静态配置
- 告警与可视化：支持规则评估触发告警，提供多种图形与仪表盘支持
- 联邦：支持分层与水平联邦

**技术亮点**:
- 不依赖分布式存储，单个服务器节点自治运行
- 采用 HTTP pull 模型采集时序数据
- 提供预编译二进制、Docker 镜像（Quay.io / Docker Hub）及源码构建（Go + NodeJS + npm，支持 `make build` 内置 Web 资源）等多种安装方式
- 通过 CI、govulncheck、OpenSSF Scorecard、OSS-Fuzz 等多重质量与安全检测

---
## 10. [google/skills](https://github.com/google/skills)
- **语言**: Python
- **Stars**: 22,851
- **简介**: Agent Skills for Google products and technologies

### AI 总结
**简介**: Google 官方维护的 Agent Skills 仓库，为 Google Cloud 等 Google 产品与技术提供可直接安装的 AI Agent 技能集合。

**核心功能**:
- 通过 `npx skills add google/skills` 一键安装技能，支持按需选择技能、目标 Agent 及安装范围（项目级/全局）
- 通过 `npx skills update` 更新已安装技能，并可清理过时技能
- 覆盖 Google Cloud 入门（IAM 认证授权、基础搭建、上手引导）
- 提供多产品解决方案技能，如解决方案架构工作流、多 Agent 安全、RAG 企业搜索、GKE 推理迁移、无服务器 Web 应用等
- 提供丰富的 AI/ML 技能，涵盖 Agent Platform 的模型部署、调优、Prompt 管理、RAG Engine、故障排查，以及 Gemini API、Genkit（Dart/Go/JS/Python）、BigQuery AI/ML 等

**技术亮点**: 基于 Agent Skills 开放规范（agentskills.io），以 Python 实现；技能按“入门 / 多产品方案 / AI·ML”分类组织，依托 Node.js 的 npx 分发，便于与多种 Agent 工具集成。

---
