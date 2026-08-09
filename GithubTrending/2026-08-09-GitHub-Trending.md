---
tags:
  - github-trending
  - daily
date: 2026-08-09
created: 2026-08-09T01:55:44.920Z
---

# 2026-08-09 GitHub Trending Top 10

## 1. [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent)
- **语言**: TypeScript
- **Stars**: 9,012
- **简介**: A self-improving RLM agent for coding workflows and long-running autonomous tasks.

### AI 总结
**简介**: Prime Agent 是一个开源的、自我改进的递归语言模型（RLM）智能体，专为编码工作流和长期自主任务设计。

**核心功能**:
- **程序化一切操作**: 内置持久化 IPython 作为模型工具，文件操作、Shell 命令、工具调用和上下文管理均通过代码完成
- **内置子智能体**: 通过 `rlm(...)` 生成真实子智能体，支持并行或后台工作，并以编程方式返回结果
- **自我改进的 Harness**: `/refine` 命令可审查当前轨迹，对补充状态进行小规模、有证据支持的更新，且支持回滚
- **可执行的技能系统**: 技能作为可导入的 Python 包，内置技能创建器可将重复工作流转化为项目或个人技能
- **后台会话支持**: 守护进程支持的智能体在终端断开后继续运行，可随时重新连接
- **智能体间直接通信**: 运行中的智能体可互相交换消息和编排任务，无需经过用户中转
- **长任务持续执行**: 自动压缩、持久目标、心跳、调度、自主模式和保留子智能体确保跨会话进度不丢失

**技术亮点**:
- 基于递归语言模型（RLM）架构，将上下文视为变量（prompt-as-a-variable），子智能体作为函数调用
- 采用持续 Harness（Continual Harness）设计，将补充提示、记忆和技能描述作为持久状态存储
- TypeScript 构建，集成持续集成（CI）和二进制构建流水线
- 提供命令行工具（attach、resume、status、doctor 等）管理会话和后台服务

---
## 2. [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)
- **语言**: JavaScript
- **Stars**: 84,591
- **简介**: Production-grade engineering skills for AI coding agents.

### AI 总结
**简介**: agent-skills 是一个为 AI 编码代理提供生产级工程技能的仓库，将资深工程师的工作流、质量关卡和最佳实践打包成技能，让 AI 代理在开发各阶段保持一致行为。

**核心功能**:
- **8 个斜杠命令映射开发生命周期**: `/spec`（需求定义）、`/plan`（计划）、`/build`（增量构建）、`/test`（测试验证）、`/review`（代码审查）、`/webperf`（性能审计）、`/code-simplify`（代码简化）、`/ship`（生产发布）
- **`/build auto` 自动化模式**: 一次批准计划后自动执行所有任务，每个任务仍保持测试驱动和独立提交，遇错自动暂停
- **技能自动触发**: 根据当前工作内容（如设计 API、构建 UI）自动激活相应技能
- **共 24 个技能**: 涵盖代码审查、面试式需求分析、测试驱动开发（红-绿-重构）等
- **多代理支持**: 通过 `npx skills add` 一键安装到 70+ 代理（Claude Code、Cursor、Codex、Copilot 等），支持单技能或全量安装

**技术亮点**: 基于 Vercel Labs 的 skills CLI 实现跨代理分发；支持 Claude Code 原生插件市场集成和本地开发模式；技能采用结构化目录组织，支持 `references/` 共享检查清单；整体架构遵循"定义-计划-构建-验证-审查-发布"的工程流水线设计。

---
## 3. [TapXWorld/ChinaTextbook](https://github.com/TapXWorld/ChinaTextbook)
- **语言**: Roff
- **Stars**: 77,950
- **简介**: 所有小初高、大学PDF教材。

### AI 总结
**简介**: 一个开源的中国中小学及大学PDF教材资源库，旨在免费提供义务教育阶段教材，促进教育资源共享。
**核心功能**:
- 提供小学至高中各年级、各学科（如数学）的人教版PDF教材下载
- 按学段（小学/初中/高中/大学）和学科分类整理，便于查找
- 覆盖上下学期全部教材，支持直接在线预览或下载
**技术亮点**: 项目以GitHub仓库形式托管，采用Markdown链接索引，资源文件按年级/出版社/学科三级目录组织，便于维护和扩展。

---
## 4. [google/skills](https://github.com/google/skills)
- **语言**: Python
- **Stars**: 16,754
- **简介**: Agent Skills for Google products and technologies

### AI 总结
**简介**: 这是 Google 官方维护的 Agent Skills 仓库，为 Google 产品和技术（尤其是 Google Cloud）提供可复用的 Agent 技能集合，当前处于积极开发阶段。

**核心功能**:
- 提供面向 Google Cloud 的入门技能（如认证、基础构建、上手引导）
- 涵盖多产品解决方案技能（如架构工作流、数据湖仓 AI、RAG 企业搜索、GKE AI 迁移等）
- 提供 AI/ML 相关技能（如 Agent Platform 的推理、调优、模型管理、Gemini API 集成等）
- 提供基础设施技能（如 GKE 的创建、网络、存储、备份、多租户、生产化等）
- 支持通过 `npx skills add google/skills` 一键安装并按需选择技能

**技术亮点**: 基于 Agent Skills 标准（agentskills.io），采用 Python 实现，按技能目录化组织，覆盖 Google Cloud 全栈（AI/ML、GKE 基础设施、数据服务），与 Google Agent Platform 深度集成。

---
## 5. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 210,058
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: 这是一个由 Matt Pocock 维护的 AI 编程代理技能集合，源自其日常真实工程实践，旨在提升编码代理（如 Claude Code、Codex）的实用性，而非“vibe coding”。

**核心功能**:
- **`/grill-me` 与 `/grill-with-docs`**: 通过“拷问会话”让代理在动工前向你提出细节问题，确保需求对齐，避免代理误解意图。
- **`/setup-matt-pocock-skills`**: 一键初始化配置，支持选择问题追踪器（GitHub、Linear 或本地文件）、标签规则及文档保存位置。
- **`/triage`**: 基于标签对工单进行分类管理。
- **可组合的小型技能**: 设计为轻量、易修改、可自由组合，不强制绑定流程，适配任意模型。

**技术亮点**:
- 双安装模式：通过 Claude Code 插件（托管只读、自动更新）或 `npx skills`（复制可编辑文件到项目，支持手动更新）。
- 基于数十年工程经验（如 DDD 中的统一语言、Pragmatic Programmer 思想）设计，解决代理常见失败模式（需求错位、输出冗余）。
- 纯 Shell 实现，依赖最小，兼容多种代理环境，并提供架构决策记录（ADR）支持演进。

---
## 6. [goauthentik/authentik](https://github.com/goauthentik/authentik)
- **语言**: Python
- **Stars**: 23,986
- **简介**: The authentication glue you need.

### AI 总结
**简介**: authentik 是一个开源的身份提供商（IdP），为现代应用提供统一的 SSO 认证解决方案，支持从个人实验室到大型生产集群的自托管部署。

**核心功能**:
- 支持多种认证协议：SAML、OAuth2/OIDC、LDAP、RADIUS 等
- 提供企业级身份管理能力，可作为 Okta、Auth0、Entra ID 等商业 IdP 的开源替代方案
- 支持多种部署方式：Docker Compose、Kubernetes (Helm Chart)、AWS CloudFormation、DigitalOcean Marketplace
- 提供现代化的 Web 管理界面和用户门户（支持亮色/暗色主题）
- 支持多语言翻译（通过 Transifex 协作平台）

**技术亮点**: 基于 Python 开发，采用模块化架构（核心服务、outpost 代理、Web 前端分离构建），提供完整的 CI/CD 流水线和代码覆盖率保障，开源版本采用 MIT 许可协议。

---
## 7. [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)
- **语言**: Python
- **Stars**: 96,503
- **简介**: TradingAgents: Multi-Agents LLM Financial Trading Framework

### AI 总结
**简介**: TradingAgents 是一个基于多智能体 LLM 的金融交易框架，模拟真实交易公司的运作模式，通过多个专业智能体协作分析市场并做出交易决策。

**核心功能**:
- 多智能体协作：部署基本面分析师、情绪专家、技术分析师、交易员和风险管理团队等多个智能体，共同评估市场状况
- 动态策略讨论：智能体之间进行动态讨论以确定最优交易策略
- 多提供商 LLM 支持：支持 GPT-5.x、Gemini 3.x、Claude 4.x、Grok 4.x、DeepSeek、Qwen、GLM 等多种模型
- 回测功能：提供回测引擎，支持历史数据验证交易策略
- 多语言支持：支持德语、西班牙语、法语、日语、韩语、葡萄牙语、俄语和中文
- 结构化输出：支持 Research Manager、Trader、Portfolio Manager 等智能体的结构化输出
- 数据源集成：支持 FRED、Polymarket、Alpha Vantage 等数据供应商

**技术亮点**: 基于 Python 实现，采用 LangGraph 检查点恢复机制，支持 Docker 部署，提供 CLI 和 Python 包两种使用方式，具备 API 密钥自动检测、代理支持、跨平台稳定性（含 Windows UTF-8 修复）等特性，并支持任何兼容 OpenAI 的端点。

---
## 8. [google/guava](https://github.com/google/guava)
- **语言**: Java
- **Stars**: 51,855
- **简介**: Google core libraries for Java

### AI 总结
**简介**: Guava 是 Google 提供的 Java 核心库，包含丰富的集合类型、不可变集合、图库以及并发、I/O、哈希、原语、字符串等实用工具，被广泛应用于 Google 及众多其他公司的 Java 项目中。

**核心功能**:
- 新增集合类型：提供 Multimap、Multiset、BiMap 等扩展集合
- 不可变集合：提供线程安全、内存高效的不可变集合实现
- 图库：支持图数据结构的创建、遍历与算法操作
- 并发工具：简化多线程编程，提供监听器、原子值、限流器等
- I/O 与哈希：提供便捷的文件读写、流处理及哈希函数封装
- 原语与字符串工具：支持基本类型转换、字符串拼接、分割与匹配等操作

**技术亮点**:
- 提供 JRE 与 Android 双版本，适配不同运行环境（JDK 8+ 或 Android）
- 通过 Maven 或 Gradle 轻松集成，支持 `implementation` 与 `api` 依赖配置
- 严格遵循二进制兼容性承诺，非 `@Beta` API 长期稳定
- 提供 `@Beta` 注解标记易变 API，并配套 Guava Beta Checker 工具防止误用

---
## 9. [LadybirdBrowser/ladybird](https://github.com/LadybirdBrowser/ladybird)
- **语言**: C++
- **Stars**: 65,001
- **简介**: Truly independent web browser

### AI 总结
**简介**: Ladybird 是一个真正独立、基于 Web 标准构建的新型浏览器引擎项目，目前处于预 alpha 阶段，仅供开发者使用。

**核心功能**:
- 多进程架构：主 UI 进程、多个 WebContent 渲染进程、图像解码进程和请求服务器进程分离
- 安全性设计：图像解码和网络连接在独立进程中运行，每个标签页拥有独立的沙箱化渲染进程
- 完整的现代 Web 支持：致力于构建完整可用的现代浏览器
- 跨平台支持：支持 Linux、macOS、Windows（WSL2）及其他类 Unix 系统

**技术亮点**: 基于 C++ 实现，核心组件继承自 SerenityOS 项目，包括：
- LibWeb（Web 渲染引擎）、LibJS（JavaScript 引擎）、LibWasm（WebAssembly 实现）
- LibCrypto/LibTLS（加密与 TLS）、LibHTTP（HTTP/1.1 客户端）
- LibGfx（2D 图形与图像解码）、LibUnicode（Unicode 与本地化支持）
- LibMedia（音视频播放）、LibCore（事件循环与操作系统抽象层）、LibIPC（进程间通信）

---
## 10. [denoland/celld](https://github.com/denoland/celld)
- **语言**: Rust
- **Stars**: 2,589
- **简介**: self-hosted, distributed Durable Objects

### AI 总结
**简介**: celld 是一个用 Rust 编写的开源守护进程，让你在自己的机器上运行 Cloudflare Workers 和 Durable Objects，实现自托管的分布式持久对象存储。

**核心功能**:
- **Durable Objects 自托管**: 每个对象对应一个独立的 SQLite 数据库，按名称寻址，应用天然分片，避免单库争用和故障爆炸半径
- **S3 兼容存储协调**: 节点仅通过共享的 S3 兼容存储桶协调，无控制平面或共识服务，对象存储 CAS 保证单节点持有权
- **持续复制与休眠**: 每个 cell 的 SQLite 数据库持续复制到存储桶；空闲 cell 可休眠至近乎零资源占用，唤醒时从存储桶恢复状态
- **部署与运行**: 支持 `celld deploy` 部署 Worker 项目（需要 esbuild），提供 Docker 镜像和安装/卸载脚本
- **安全机制**: 对等节点间通信采用 HMAC 认证、时钟绑定、重放保护；拒绝公网直接暴露，建议使用 WireGuard 或 Tailscale 加密网络
- **运维诊断**: `celld diagnose` 命令枚举节点租约并主动探测，输出资源占用、可达性和协议兼容性报告；支持压力驱逐（可选）

**技术亮点**: 基于 V8 引擎执行 Wrangler bundles；去中心化架构设计——存储桶即持久事实源，节点可替换；无成员协议、无故障检测器、无共识服务；支持 x86-64 和 ARM64 Linux 平台。

---
