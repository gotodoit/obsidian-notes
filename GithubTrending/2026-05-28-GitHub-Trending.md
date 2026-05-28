---
tags:
  - github-trending
  - daily
date: 2026-05-28
created: 2026-05-28T01:55:43.768Z
---

# 2026-05-28 GitHub Trending Top 10

## 1. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)
- **语言**: Python
- **Stars**: 62,315
- **简介**: 利用AI大模型，一键生成高清短视频 Generate short videos with one click using AI LLM.

### AI 总结
**简介**: 一个利用AI大模型，只需提供主题或关键词即可全自动生成高清短视频的开源工具。

**核心功能**:
- 支持AI自动生成视频文案，也支持自定义文案
- 支持竖屏9:16和横屏16:9两种高清视频尺寸
- 支持批量视频生成，可选择最满意的版本
- 支持中文和英文视频文案，以及多种语音合成
- 支持字幕生成，可自定义字体、位置、颜色、大小等
- 支持背景音乐，可随机或指定音乐文件并调节音量
- 视频素材高清无版权，也支持使用本地素材

**技术亮点**:
- 采用完整的MVC架构，代码结构清晰，易于维护
- 支持API和Web界面两种使用方式
- 支持OpenAI、DeepSeek、通义千问、Google Gemini等多种大模型接入
- 支持Docker、一键启动包、Google Colab等多种部署方式

---
## 2. [Lum1104/Understand-Anything](https://github.com/Lum1104/Understand-Anything)
- **语言**: TypeScript
- **Stars**: 40,033
- **简介**: Graphs that teach > graphs that impress. Turn any code into an interactive knowledge graph you can explore, search, and ask questions about. Works with Claude Code, Codex, Cursor, Copilot, Gemini CLI, and more.

### AI 总结
**简介**: 将任何代码库、知识库或文档转化为交互式知识图谱，支持探索、搜索和提问，适用于多种AI编码工具。

**核心功能**:
- **交互式知识图谱**: 将代码库可视化为节点（文件、函数、类等），支持点击、搜索和探索。
- **业务逻辑视图**: 切换到领域视图，将代码映射为水平图展示业务流程、域和步骤。
- **知识库分析**: 解析LLM维基（如Karpathy模式），生成力导向知识图谱，包含社区聚类和隐含关系发现。
- **引导式导览**: 自动生成按依赖顺序排列的架构导览，帮助按正确顺序学习代码库。
- **模糊与语义搜索**: 通过名称或含义搜索，例如“哪些部分处理认证？”可返回相关结果。
- **差异影响分析**: 分析代码变更的影响范围。

**技术亮点**: 使用TypeScript开发，基于多智能体管道分析项目，生成知识图谱，并提供交互式仪表盘。

---
## 3. [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop)
- **语言**: Unknown
- **Stars**: 5,753
- **简介**: A skill file for removing AI tells from prose

### AI 总结
**简介**: 一个用于去除AI写作痕迹的Claude技能文件，通过检测和移除AI特有的短语、结构模式，使文本更自然。

**核心功能**:
- 识别并移除AI常用短语（如开场白、强调词、商业术语、副词等）
- 检测并修正结构陈词滥调（二元对比、被动语态、戏剧化碎片化等）
- 执行句子级规则（禁止Wh-开头、破折号、极端词汇，要求主动语态）
- 提供1-10分的评分维度（直接性、节奏、信任度、真实性、密度）

**技术亮点**: 采用模块化技能结构，包含核心指令（SKILL.md）和参考文件（短语、结构、示例），支持Claude Code、Claude Projects、自定义指令和API调用多种集成方式。

---
## 4. [affaan-m/ECC](https://github.com/affaan-m/ECC)
- **语言**: JavaScript
- **Stars**: 196,101
- **简介**: The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

### AI 总结
**简介**: ECC 是一个面向 AI 代理工作流的"马具原生操作员系统"，为 Claude Code、Codex、Cursor 等 AI 代理提供技能、本能、记忆优化、安全扫描和研究优先开发能力。

**核心功能**:
- 提供完整的代理系统：包括技能、本能、记忆优化、持续学习、安全扫描和研究优先开发
- 跨平台兼容：支持 Claude Code、Codex、Cursor、OpenCode、Gemini、Zed、GitHub Copilot 等多种 AI 代理框架
- 生产就绪：经过 10 个月以上日常使用和真实产品开发验证的代理、技能、钩子、规则、MCP 配置和遗留命令 shim
- 商业与开源双轨：提供免费 MIT 许可的开源版本和面向私有仓库的 ECC Pro GitHub App 服务

**技术亮点**: 基于 JavaScript/TypeScript 构建，支持 Shell、Python、Go、Java、Perl、Markdown 等 12+ 种语言生态系统，采用跨代理框架架构设计，拥有 182K+ Stars 和 28K+ Forks 的社区规模。

---
## 5. [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)
- **语言**: Python
- **Stars**: 17,312
- **简介**: Open source repository of plugins primarily intended for knowledge workers to use in Claude Cowork

### AI 总结
**简介**: 这是一个开源的插件集合，旨在通过为特定角色、团队和公司定制技能、工具和工作流程，将 Claude 转变为专业的领域专家。

**核心功能**:
- **预构建角色插件**: 提供 11 个针对不同职能（如销售、营销、客户支持、产品管理、法律、财务等）的即用型插件。
- **自定义工作流**: 允许用户通过技能、命令和连接器，定制 Claude 如何执行任务和使用工具，以匹配公司的特定流程。
- **Slash 命令与自动技能**: 支持显式触发的命令（如 `/sales:call-prep`）和 Claude 自动调用的领域知识技能。
- **外部工具连接**: 通过 MCP 服务器，将 Claude 连接到 Slack、Jira、Notion、Salesforce 等数十种常用企业工具和数据库。

**技术亮点**:
- **插件结构**: 每个插件遵循标准文件结构（`manifest.json`, `commands/`, `skills/`），便于创建和共享。
- **兼容性**: 专为 Claude Cowork 设计，同时兼容 Claude Code。
- **基于文件**: 所有组件基于文件，易于版本控制和分发。

---
## 6. [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)
- **语言**: Shell
- **Stars**: 24,387
- **简介**: Taste-Skill - gives your AI good taste. stops the AI from generating boring, generic slop

### AI 总结
**简介**: 一个为 AI 代理提供“品味”的开源框架，通过可移植的 Agent Skills 升级 AI 构建的界面，使其摆脱模板化的平庸设计。

**核心功能**:
- **设计品味提升**: 提供更强的布局、排版、动效和间距规则，让 AI 生成的界面不再千篇一律。
- **图像生成技能**: 包含用于生成参考板（Web、移动端、品牌套件）的技能，可配合 ChatGPT Images 等工具使用。
- **多工具兼容**: 支持通过 `npx skills add` 命令安装，可与 Codex、Cursor、Claude Code 等主流 AI 编码工具协同工作。
- **单技能安装**: 支持按需安装单个技能（如 `design-taste-frontend`），无需全部加载。
- **版本管理**: 提供 v2（实验性）和 v1 版本，用户可根据项目需求选择或锁定版本。

**技术亮点**: 基于 Shell 脚本和 `SKILL.md` 文件格式，利用 `agent-skills` CLI 工具实现轻量级、可移植的技能安装与管理。

---
## 7. [p-e-w/heretic](https://github.com/p-e-w/heretic)
- **语言**: Python
- **Stars**: 22,042
- **简介**: Fully automatic censorship removal for language models

### AI 总结
**简介**: Heretic 是一款全自动去除语言模型审查（安全对齐）的工具，基于方向消融（abliteration）技术，无需昂贵后训练即可生成去审查模型。

**核心功能**:
- 自动优化消融参数，通过最小化拒绝回答次数和 KL 散度，保留模型原始智能
- 支持大多数稠密模型、多模态模型、MoE 架构及部分混合模型（如 Qwen3.5）
- 内置评估功能，可对比去审查前后模型的拒绝率和 KL 散度

**技术亮点**: 结合方向消融（abliteration）与基于 TPE 的超参数优化器（Optuna），实现全自动参数搜索，无需理解 Transformer 内部原理即可使用。

---
## 8. [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos)
- **语言**: Python
- **Stars**: 26,899
- **简介**: Kronos: A Foundation Model for the Language of Financial Markets

### AI 总结
**简介**: Kronos 是首个专为金融市场 K 线数据设计的开源基础模型，基于全球 45+ 交易所数据训练。

**核心功能**:
- 支持金融 K 线（OHLCV）数据的预测与分析
- 提供在线演示（BTC/USDT 24小时预测）
- 开源多个预训练模型（Kronos-mini/small/base）
- 支持模型微调以适应特定任务

**技术亮点**:
- 采用两阶段框架：专用分词器将连续 K 线数据量化为分层离散令牌，再通过自回归 Transformer 预训练
- 模型家族覆盖 4.1M 至 499.2M 参数，适配不同计算需求
- 论文已被 AAAI 2026 接收，代码与模型权重在 Hugging Face 开源

---
## 9. [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills)
- **语言**: Python
- **Stars**: 11,003
- **简介**: 754 structured cybersecurity skills for AI agents · Mapped to 5 frameworks: MITRE ATT&CK, NIST CSF 2.0, MITRE ATLAS, D3FEND & NIST AI RMF · agentskills.io standard · Works with Claude Code, GitHub Copilot, Codex CLI, Cursor, Gemini CLI & 20+ platforms · 26 security domains · Apache 2.0

### AI 总结
**简介**: 一个包含754个结构化网络安全技能的开源库，为AI代理提供专家级安全分析能力，覆盖26个安全领域并映射到5个行业框架。

**核心功能**:
- 提供754个生产级网络安全技能，覆盖数字取证、云安全、威胁情报等26个安全领域
- 每个技能同时映射到MITRE ATT&CK、NIST CSF 2.0、MITRE ATLAS、D3FEND和NIST AI RMF五个框架
- 支持通过npx或git clone快速部署，兼容Claude Code、GitHub Copilot、Cursor等20+AI平台
- 采用agentskills.io开放标准格式，确保技能库的跨平台可移植性

**技术亮点**: Python编写，遵循agentskills.io标准规范；每个技能包含跨框架映射矩阵（如ATT&CK T1071 + NIST CSF DE.CM + ATLAS AML.T0047等）；社区驱动项目（Apache 2.0许可），支持PR贡献。

---
## 10. [twentyhq/twenty](https://github.com/twentyhq/twenty)
- **语言**: TypeScript
- **Stars**: 47,357
- **简介**: The open alternative to Salesforce, designed for AI.

### AI 总结
**简介**: Twenty 是一个开源的、面向 AI 设计的 Salesforce 替代品，为技术团队提供构建自定义 CRM 的模块。

**核心功能**:
- 支持快速云端部署，一分钟内即可创建工作区。
- 提供 CLI 工具，允许开发者以代码方式定义对象、字段和视图，并发布为独立应用。
- 支持 Docker Compose 自托管部署，并可通过本地开发环境贡献代码。
- 内置现代 CRM 所需的核心模块（对象、视图、工作流和智能代理）。

**技术亮点**: 使用 TypeScript 开发，提供 CLI 和 SDK（twenty-sdk）用于声明式应用构建，支持版本化管理 CRM 配置。

---
