---
tags:
  - github-trending
  - daily
date: 2026-05-05
created: 2026-05-05T01:55:46.180Z
---

# 2026-05-05 GitHub Trending Top 10

## 1. [ruvnet/ruflo](https://github.com/ruvnet/ruflo)
- **语言**: TypeScript
- **Stars**: 41,507
- **简介**: 🌊 The leading agent orchestration platform for Claude. Deploy intelligent multi-agent swarms, coordinate autonomous workflows, and build conversational AI systems. Features enterprise-grade architecture, self-learning swarm intelligence, RAG integration, and native Claude Code / Codex Integration

### AI 总结
**简介**: Ruflo 是一个为 Claude Code 设计的多智能体 AI 编排平台，支持协调 100+ 专业 AI 智能体跨机器、团队和信任边界协作。

**核心功能**:
- 多智能体集群编排：支持智能体自组织成集群，协同完成复杂任务
- 自学习与记忆系统：智能体从每次任务中学习，跨会话保留记忆，自动优化行为模式
- RAG 集成与知识管理：提供混合搜索、图遍历、多样性排序等智能检索，支持知识图谱构建
- 联邦协作：不同机器上的智能体可安全通信，不泄露数据
- 32 个插件化模块：覆盖核心编排、记忆、智能、代码质量、安全合规等领域
- Claude Code 原生集成：作为插件安装后，自动路由任务、学习模式、协调后台智能体

**技术亮点**: 基于 Rust 的 WASM 内核驱动策略引擎、嵌入和证明系统；采用 TypeScript 构建；支持 GPU 加速搜索（ruvector）、本地 LLM 路由（ruvllm）、Playwright 浏览器自动化测试。

---
## 2. [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)
- **语言**: Python
- **Stars**: 67,591
- **简介**: TradingAgents: Multi-Agents LLM Financial Trading Framework

### AI 总结
**简介**: TradingAgents 是一个基于多智能体 LLM 的金融交易框架，模拟真实交易公司运作，通过多个专业 AI 智能体协作进行市场评估和交易决策。

**核心功能**:
- 部署多个 LLM 驱动的专业智能体（基本面分析师、情绪专家、技术分析师、交易员、风险管理团队等）
- 智能体之间进行动态讨论，共同确定最优交易策略
- 支持结构化输出智能体（研究经理、交易员、投资组合经理）
- 提供回测功能，支持多种日期精度
- 支持多种 LLM 提供商（GPT-5.x、Gemini 3.x、Claude 4.x、Grok 4.x、DeepSeek、Qwen、GLM、Azure 等）
- 支持 LangGraph 检查点恢复和持久化决策日志

**技术亮点**:
- 多智能体协作架构，模拟真实交易公司层级
- 支持 Docker 部署和跨平台运行（含 Windows UTF-8 编码修复）
- 统一模型目录，支持五级评分体系
- 集成多种 API（OpenAI Responses API、Anthropic effort control 等）

---
## 3. [browserbase/skills](https://github.com/browserbase/skills)
- **语言**: JavaScript
- **Stars**: 2,130
- **简介**: Claude Agent SDK with a web browsing tool

### AI 总结
**简介**: Browserbase Skills 是一套为 Claude Code 提供的技能插件，通过浏览器自动化和官方 `bb` CLI 实现强大的 Web 浏览与自动化能力。

**核心功能**:
- **浏览器自动化**: 支持远程 Browserbase 会话，具备反机器人隐身、CAPTCHA 解决和住宅代理功能
- **CLI 集成**: 提供 `browserbase-cli` 技能，可操作 Browserbase 平台 API（会话、项目、上下文、扩展、抓取、仪表盘）
- **无服务器部署**: 通过 `functions` 技能将无服务器浏览器自动化部署到 Browserbase 云端
- **调试与诊断**: 包含 `site-debugger`（分析机器人检测、选择器、时机、认证和验证码问题）和 `browser-trace`（捕获完整 DevTools 协议跟踪）
- **数据获取与搜索**: 无需浏览器即可获取静态页面 HTML/JSON 或执行网络搜索
- **UI 测试**: 支持 AI 驱动的对抗性 UI 测试，分析 git 差异或探索整个应用以发现错误
- **工具集成**: 提供 cookie 同步、使用统计仪表盘等功能

**技术亮点**: 基于 JavaScript 开发，与 Claude Code 深度集成，利用 Browserbase 的 Stagehand 框架，支持反机器人隐身、CAPTCHA 解决、住宅代理等高级浏览器自动化特性

---
## 4. [Hmbown/DeepSeek-TUI](https://github.com/Hmbown/DeepSeek-TUI)
- **语言**: Rust
- **Stars**: 4,050
- **简介**: Coding agent for DeepSeek models that runs in your terminal

### AI 总结
**简介**: DeepSeek TUI 是一个基于 DeepSeek V4 模型、运行在终端中的编码助手，支持 100 万 token 上下文、MCP 客户端、沙箱和持久化任务队列，无需 Node 或 Python 运行时，仅需单个二进制文件。

**核心功能**:
- **原生 RLM 查询**：并行分发 1–16 个廉价子模型进行批量分析和推理
- **思维链流式显示**：实时观察模型思考过程
- **完整工具集**：文件操作、Shell 执行、Git、Web 搜索/浏览、补丁应用、子代理、MCP 服务器
- **100 万 token 上下文**：自动智能压缩，支持前缀缓存以降低成本
- **三种模式**：计划（只读探索）、代理（交互式审批）、YOLO（自动审批）
- **推理努力级别**：通过 Shift+Tab 在 off→high→max 间切换
- **会话保存/恢复**：支持长时间运行的会话检查点
- **工作区回滚**：基于侧边 Git 的快照回滚，不影响主仓库
- **持久化任务队列**：后台任务在重启后仍可存活
- **HTTP/SSE 运行时 API**：支持无头代理工作流
- **MCP 协议**：连接模型上下文协议服务器扩展工具
- **LSP 诊断**：编辑后自动显示内联错误/警告
- **用户记忆**：可选的跨会话偏好文件
- **本地化 UI**：支持英语、日语、简体中文、葡萄牙语
- **实时成本追踪**：每轮和会话级别的 token 使用与成本估算
- **技能系统**：可组合、可安装的指令包，无需后端服务

**技术亮点**:
- 使用 **Rust** 语言开发，性能高效
- 架构为 `deepseek`（调度 CLI）→ `deepseek-tui`（伴随二进制）→ ratatui 界面 ↔ 异步引擎 ↔ OpenAI 兼容流式客户端
- 工具调用通过类型化注册中心（Shell、文件操作、Git、Web、子代理、MCP、RLM）路由，结果流式返回对话
- 引擎管理会话状态、轮次追踪、持久化任务队列和 LSP 子系统，

---
## 5. [soxoj/maigret](https://github.com/soxoj/maigret)
- **语言**: Python
- **Stars**: 24,880
- **简介**: 🕵️‍♂️ Collect a dossier on a person by username from 3000+ sites

### AI 总结
**简介**: Maigret 是一个基于 Python 的开源工具，可通过用户名在 3000+ 个网站上搜集目标人物的公开信息，无需 API 密钥。

**核心功能**:
- 支持 3000+ 个网站，默认扫描流量排名前 500 的站点，支持按类别/国家筛选
- 从个人资料页面和站点 API 提取账号所有者的公开信息，包括关联的其他账号链接
- 支持递归搜索，利用发现的用户名和 ID 进行深入调查
- 可生成 PDF、HTML、XMind 等格式的报告
- 提供 Web 界面用于可视化结果和下载报告

**技术亮点**: 基于 Python 3.10+，可嵌入其他 Python 项目作为库使用；支持 Tor 和 I2P 网站；具备自动更新的站点数据库，离线时可回退到内置数据库；能检测并部分绕过封锁、审查和 CAPTCHA。

---
## 6. [qbittorrent/qBittorrent](https://github.com/qbittorrent/qBittorrent)
- **语言**: C++
- **Stars**: 37,058
- **简介**: qBittorrent BitTorrent client

### AI 总结
**简介**: qBittorrent 是一个基于 Qt 和 libtorrent 的开源 BitTorrent 客户端，旨在提供快速、稳定且功能丰富的替代方案。

**核心功能**:
- 支持 Unicode 和多语言界面
- 集成 IP 到国家的地理位置解析（基于 DB-IP 数据库）
- 提供完整的 BitTorrent 协议支持
- 支持源代码和二进制文件的数字签名验证

**技术亮点**: 使用 C++ 和 Qt 框架开发，底层依赖 libtorrent-rasterbar 库，支持跨平台运行，并通过 CI、Coverity 等工具保证代码质量。

---
## 7. [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp)
- **语言**: TypeScript
- **Stars**: 19,930
- **简介**: A MCP for Claude Desktop / Claude Code / Windsurf / Cursor to build n8n workflows for you

### AI 总结
**简介**: n8n-MCP 是一个 MCP 服务器，为 AI 助手（如 Claude、Cursor 等）提供对 n8n 节点文档、属性和操作的全面访问，帮助它们构建 n8n 工作流。

**核心功能**:
- **提供全面的 n8n 节点知识**：覆盖 1650 个 n8n 节点（820 个核心节点 + 830 个社区节点），包括详细的节点属性（99% 覆盖率）、操作（63.6% 覆盖率）和文档（87% 覆盖率）。
- **集成丰富的模板和示例**：提供 2352 个工作流模板和 156 个从热门模板中提取的真实世界配置示例，帮助 AI 理解如何构建工作流。
- **支持多种 AI 客户端**：可与 Claude Desktop、Claude Code、VS Code、Cursor、Windsurf 等多种 AI 驱动的 IDE 和工具集成。
- **提供云端和自托管部署选项**：提供免费云端服务（dashboard.n8n-mcp.com）和通过 npx、Docker、Railway 等方式的自托管方案。

**技术亮点**: 使用 TypeScript 开发，构建为 MCP (Model Context Protocol) 服务器，作为 n8n 自动化平台和 AI 模型之间的桥梁，提供结构化的节点知识访问。

---
## 8. [1jehuang/jcode](https://github.com/1jehuang/jcode)
- **语言**: Rust
- **Stars**: 3,930
- **简介**: Coding Agent Harness

### AI 总结
**简介**: jcode 是一个用 Rust 编写的新一代编码代理框架（Coding Agent Harness），专注于提升多会话工作流、无限可定制性和高性能。

**核心功能**:
- 支持多会话（multi-session）工作流，可同时管理多个活跃会话
- 提供极致的资源效率优化，内存占用显著低于同类工具（如 Claude Code、Cursor Agent 等）
- 跨平台支持（Linux、macOS、Windows），提供一键脚本安装

**技术亮点**:
- 使用 Rust 语言开发，确保高性能和低资源消耗
- 单会话仅占用 27.8 MB 内存（关闭本地嵌入时），10 个会话仅 117 MB，远低于同类竞品（如 Claude Code 单会话 386.6 MB）
- 启动速度极快，针对多会话扩展场景进行了深度优化

---
## 9. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 92,705
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个提供多种专业AI代理角色的集合，每个代理都拥有独特个性、专长领域和可交付成果，旨在像组建一支永不休息的AI专家团队一样，随时为你的工作流赋能。

**核心功能**:
- **专业角色代理**：提供涵盖前端开发、后端架构、移动开发、AI工程、DevOps、安全工程等多种角色的AI代理，每个代理都有明确的任务定义和交付标准。
- **多工具集成**：支持与Claude Code、GitHub Copilot、Cursor、Aider、Windsurf等主流AI编码工具集成，通过脚本一键安装或手动复制配置。
- **即插即用**：通过简单的脚本命令（如`./scripts/install.sh --tool claude-code`）即可将代理配置安装到指定工具中，激活后即可调用特定专家模式。
- **可参考文档**：每个代理文件包含身份特质、核心工作流、代码示例和成功指标，可作为自定义AI助手的参考模板。

**技术亮点**: 基于Shell脚本实现跨工具集成，代理配置以Markdown文件存储，通过`install.sh`和`convert.sh`脚本实现自动化部署，支持多种主流AI开发工具。

---
## 10. [virattt/dexter](https://github.com/virattt/dexter)
- **语言**: TypeScript
- **Stars**: 23,225
- **简介**: An autonomous agent for deep financial research

### AI 总结
**简介**: Dexter 是一个专为金融研究设计的自主智能体，能够通过任务规划、自我反思和实时市场数据，自动将复杂的金融问题转化为清晰的研究计划并执行。

**核心功能**:
- **智能任务规划**: 自动将复杂查询分解为结构化的研究步骤
- **自主执行**: 选择并执行合适的工具来收集金融数据
- **自我验证**: 检查自身工作并迭代直至任务完成
- **实时金融数据**: 访问利润表、资产负债表和现金流量表
- **安全特性**: 内置循环检测和步骤限制，防止失控执行

**技术亮点**: 使用 TypeScript 构建，依赖 Bun 运行时，集成多种 LLM 提供商（如 OpenAI、Anthropic、Google）和金融数据 API（Financial Datasets API），支持通过 LangSmith 进行评估，并提供 WhatsApp 集成和调试追踪功能。

---
