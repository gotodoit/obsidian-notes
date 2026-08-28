---
tags:
  - github-trending
  - daily
date: 2026-08-28
created: 2026-08-28T01:55:45.212Z
---

# 2026-08-28 GitHub Trending Top 10

## 1. [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view)
- **语言**: JavaScript
- **Stars**: 8,230
- **简介**: A spy satellite simulator in your browser, except the data is real. Live open source spatial intelligence on a photorealistic 3D globe.

### AI 总结
**简介**: God's Eye View 是一个在浏览器中运行的间谍卫星模拟器，基于真实公开数据，在逼真的3D地球上实时展示全球飞机、船舶、卫星、地震、交通和公共摄像头等空间情报。

**核心功能**:
- **3D 地球实时追踪**: 在逼真的 3D 地球上实时展示飞机、船舶、卫星、地震、交通和公共摄像头等公开数据源
- **座舱视角**: 可进入被追踪航班内部，以飞行员视角观察地形
- **点击追踪**: 点击任意目标即可锁定追踪，显示轨迹和完整元数据，并可一键切换到最近的实时摄像头
- **语音控制与白板**: 支持通过语音指令控制应用，并可通过语音在世界上绘制标注、边界多边形和路线
- **3D 模型库**: 包含真实飞机模型（787、ATR-72 等），追踪目标靠近时自动从图标切换为 3D 模型
- **多种视觉风格**: 支持 CRT、夜视、FLIR/热成像、黑白、雪地等 GLSL 传感器视觉效果
- **军事 HUD 与检测叠加**: 提供战术风格平视显示器和屏幕上所有目标的边界框与 ID 标注
- **场景导演与分享**: 可录制电影级相机巡游，并将相机、样式、图层和追踪目标序列化到 URL 中分享

**技术亮点**: 基于 Node.js 24.x 构建，使用 JavaScript 开发；所有数据层均标注来源和实时状态（部分/延迟/模拟/不可用）；客户端故意将航班渲染延迟一个轮询间隔以实现平滑插值；支持无 API 密钥的模拟层和带密钥的实时层。

---
## 2. [zedeus/nitter](https://github.com/zedeus/nitter)
- **语言**: Nim
- **Stars**: 13,897
- **简介**: Alternative Twitter front-end

### AI 总结
**简介**: Nitter 是一个免费开源的 Twitter 替代前端，专注于隐私保护和性能优化，无需 JavaScript 即可浏览 Twitter 内容。

**核心功能**:
- 无 JavaScript 和广告，所有请求通过后端代理，客户端不直接与 Twitter 通信
- 防止 Twitter 追踪用户的 IP 地址或浏览器指纹
- 使用 Twitter 非官方 API，无需开发者账号
- 轻量级设计（页面体积比官方版小约 15 倍，加载速度快 2-4 倍）
- 支持 RSS 订阅源、主题切换和移动端响应式设计
- AGPLv3 许可证，禁止私有化实例部署

**技术亮点**:
- 使用 Nim 语言开发，依赖 libpcre、libsass 和 Redis/Valkey 缓存
- 支持 Docker 多架构部署（amd64 和 arm64）
- 可配置反向代理（Nginx/Apache）以增强安全性和性能
- 未来计划添加账户系统、推文归档和开发者 API

> ⚠️ 注意：2026 年 8 月 24 日，X Corp.（原 Twitter）已向 Nitter 发送停止侵权函，要求永久关闭所有实例和项目仓库。

---
## 3. [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2)
- **语言**: JavaScript
- **Stars**: 23,096
- **简介**: Prompt as Code | GPT-Image2 工业级提示词引擎与模板库，530+ 个案例逆向工程，20+ 套工业级模板，并提炼出Skills，持续更新中

### AI 总结
**简介**: 一个面向 GPT-Image2 的工业级提示词引擎与模板库，包含 530+ 个逆向工程案例和 20+ 套工业级模板，以 "Prompt as Code" 理念帮助开发者高效生成 AI 图像。

**核心功能**:
- **案例库与模板**: 提供 530+ 个逆向工程案例和 20+ 套工业级提示词模板，覆盖多种风格与场景
- **可视化画廊网站**: 在线浏览案例、预览大图、一键复制完整提示词，支持按风格/场景筛选，登录后可测试生成
- **Skills 提炼**: 从案例中提炼出可复用的 Skills，便于系统化学习和应用
- **多语言支持**: 提供英文、简体中文、日文版本的文档
- **社区与交流**: 设有微信交流群和公众号，持续更新案例与教程

**技术亮点**:
- 基于 JavaScript 开发，提供配套的在线画廊网站
- 采用 "Prompt as Code" 理念，将提示词工程化、模块化
- 支持通过 API 平台（如 APIMart、hiapi）集成 GPT-Image2 的图像生成能力，涵盖文生图、图像编辑、1K-4K 分辨率等场景
- 项目已登上 Trendshift 趋势榜，社区活跃度高

---
## 4. [tt-a1i/archify](https://github.com/tt-a1i/archify)
- **语言**: JavaScript
- **Stars**: 23,506
- **简介**: Agent skill for beautiful, verifiable architecture, workflow, sequence, data-flow, and lifecycle diagrams—self-contained HTML with motion and crisp export.

### AI 总结
**简介**: Archify 是一个 Node.js 渲染与验证系统，可将代码库或系统描述直接转化为精美的交互式架构图、流程图、时序图等，生成自包含的 HTML 文件，支持动画与多种格式导出。

**核心功能**:
- **五种图表类型与四种预设**：支持架构图、工作流、时序图、数据流和生命周期图，内置明暗主题与品牌标识
- **变更对比审查**：可将两个验证快照进行 Before / Delta / After 对比，精确呈现新增、删除、修改、移动和重路由的细节
- **交互式探索**：支持节点搜索、溯源验证、上下游路径追踪、角色对比，以及引导式故事播放，确保拓扑信息真实可靠
- **单文件交付**：由类型化 JSON 中间表示（IR）确定性编译生成自包含 HTML，同时导出 PNG、SVG、WebM 及 1200×630 分享卡片
- **多 Agent 支持**：兼容 Cursor、Claude Code、Codex CLI 和 OpenCode，通过 `npx skills add tt-a1i/archify -g` 快速安装

**技术亮点**: 基于类型化 JSON IR 的确定性渲染管线，确保每次生成结果一致可验证；采用纯 JavaScript/Node.js 实现，生成零依赖的自包含 HTML/SVG，支持有限动画效果；内置 Proof Lab 画廊展示 11 个真实场景的验证产物。

---
## 5. [JetBrains/go-modern-guidelines](https://github.com/JetBrains/go-modern-guidelines)
- **语言**: Go
- **Stars**: 2,127
- **简介**: Help AI coding agents write modern Go

### AI 总结
**简介**: 这是 JetBrains 官方发布的指南仓库，旨在帮助 AI 编码代理编写现代 Go 代码，覆盖从 Go 1.0 到 Go 1.27 的最新特性。

**核心功能**:
- 提供专门的指南文件，引导 AI 代理使用现代 Go 惯用法（如 `max(a,b)` 替代 if-else、`slices.Contains` 替代手写循环、`cmp.Or` 替代 nil 检查链）
- 自动检测项目 `go.mod` 中的 Go 版本，只使用该版本及之前可用的语言特性和标准库
- 解决 AI 模型的训练数据滞后和频率偏差问题，避免生成过时的 Go 代码
- 支持 Junie、Claude Code、Codex、Cursor 等主流 AI 编码工具，通过 marketplace 插件方式分发

**技术亮点**: 与 Go 官方 `modernize` 分析器目标一致，但面向新代码生成场景；使用小型 CLI 工具（Go 1.25+）实现插件安装，支持自动工具链切换；通过 skills.sh 可扩展到其他 AI 代理。

---
## 6. [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- **语言**: Python
- **Stars**: 34,701
- **简介**: Official, Anthropic-managed directory of high quality Claude Code Plugins.

### AI 总结
**简介**: Anthropic 官方维护的 Claude Code 高质量插件目录，收录内部及第三方插件供用户安装使用。

**核心功能**:
- **插件目录管理**: 分为 `/plugins`（Anthropic 内部插件）和 `/external_plugins`（第三方社区插件）两类
- **一键安装**: 支持通过 `/plugin install {plugin-name}@claude-plugins-official` 命令或 `/plugin > Discover` 浏览安装
- **插件提交机制**: 第三方合作伙伴可提交插件，需满足质量和安全标准
- **标准插件结构**: 定义统一的插件目录结构（含 `plugin.json` 元数据、MCP 配置、命令、代理、技能等）
- **Skill 打包支持**: 支持无 manifest 的 skill 仓库直接声明技能并注册为 `<plugin-name>:<skill-name>`

**技术亮点**:
- **插件名称不可变机制**: 名称作为不可变 slug，重命名需通过 `renames` 映射自动迁移用户安装
- **skill-bundle 插件声明**: 支持 `strict: false` 配合显式 `skills` 数组，可跨多个子目录精选技能
- **基于 Claude Code 插件系统**: 深度集成 MCP 服务器配置，遵循官方插件市场 schema

---
## 7. [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- **语言**: Python
- **Stars**: 35,340
- **简介**: Turn any AI agent into an AI Scientist. The #1 Agent Skills library for science, used by 175,000+ scientists worldwide. 163 ready-to-use validated skills plus 100+ scientific databases covering biology, chemistry, medicine, and drug discovery. Compatible with Cursor, Claude Code, Codex, Pi, Antigravity, and the open Agent Skills standard.

### AI 总结
**简介**: 一个包含163个即用型科学技能和100+科学数据库的开源Agent技能库，可将任何AI代理转变为AI科学家，支持生物学、化学、医学和药物发现等领域的研究工作流。

**核心功能**:
- **163个经过验证的科学技能**：涵盖癌症基因组学、千人基因组查询、调控序列预测、病原体变异监测、PK/PD建模与剂量选择、药物-靶点结合、分子动力学、RNA速度分析、微生物组基础模型、地球空间科学、时间序列预测等
- **100+科学数据库集成**：提供生物医学文献检索、监管文献获取、知识图谱搜索、科学ML资源发现等数据访问能力
- **跨平台兼容**：支持Cursor、Claude Code、Codex、Google Antigravity等主流AI代理，遵循开放的Agent Skills标准
- **插件化部署**：可作为Agent Plugins包（`plugin.json` + `skills/`）整体加载
- **配套工具K-Dense BYOK**：免费开源的桌面端AI协同科学家，支持自备API密钥、40+模型选择，提供完整研究空间

**技术亮点**: 基于Python实现，遵循Agent Skills和Agent Plugins双开放标准；采用模块化技能架构，每个技能独立验证并经过安全扫描；支持复杂的多步骤科学研究工作流编排；通过CI/CD流水线（Security Scan、Skill Tests）保障代码质量和安全性。

---
## 8. [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail)
- **语言**: JavaScript
- **Stars**: 114,103
- **简介**: Makes your AI agent think like the laziest senior dev in the room. The best code is the code you never wrote.

### AI 总结
**简介**: Ponytail 是一个让 AI 编程助手像“最懒的资深工程师”一样思考的开源工具，通过内置 skill 引导 AI 用最少代码完成任务，平均减少 54% 代码量（最高 94%），同时保持 100% 安全。

**核心功能**:
- **极简代码生成**: 引导 AI 优先使用浏览器原生功能（如 `<input type="date">`）替代第三方库和冗余组件，避免过度工程化
- **多智能体兼容**: 支持 20+ AI 编程代理（Claude Code 等），通过 skill 机制无缝集成
- **性能优化**: 实测相比无 skill 基线，减少 54% 代码行数、22% token 消耗、20% 成本、27% 耗时
- **安全兜底**: 在激进精简代码的同时保留完整安全机制（对比裸 prompt 的 95% 安全率，保持 100%）
- **可复现基准测试**: 提供基于真实开源项目（FastAPI+React）的 12 项功能任务评测方案，支持自行验证效果

**技术亮点**: 纯 JavaScript 实现，采用 Agentic skill 机制（非简单 prompt 模板），通过对比实验验证（Haiku 4.5 模型，n=4）证明其在代码量、token、成本、时间四个维度全面优于 terse-prose 和 YAGNI prompt 方案，且不牺牲安全性。

---
## 9. [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)
- **语言**: Python
- **Stars**: 52,418
- **简介**: World's first open-source, agentic video production system. 12 production pipelines, 100+ tools, 700+ agent skill and production-knowledge files. Turn your AI coding assistant into a full video production studio.

### AI 总结
**简介**: OpenMontage 是全球首个开源的智能体视频制作系统，可将 AI 编程助手转变为完整的视频制作工作室，支持通过自然语言描述完成从研究、脚本、素材生成到剪辑合成的全流程视频制作。

**核心功能**:
- **12 条生产流水线**：覆盖不同类型的视频制作场景，内置 100+ 工具和 700+ 智能体技能与制作知识文件
- **真实视频生成**：区别于常见的"静态图片动画化"方案，智能体可从免费素材库和开放档案中检索真实运动片段，剪辑成时间线并渲染成片
- **自然语言驱动**：用户只需用日常语言描述需求，智能体自动处理调研、脚本编写、素材生成、剪辑和最终合成
- **多模态 AI 集成**：支持视频生成、图像生成和 LLM API 的统一接入，兼容 300+ 精选模型
- **社区与协作**：支持多 AI 代理（Claude、ChatGPT、DeepSeek 等）在同一对话中协作，可云端运行、跨平台使用

**技术亮点**: 基于 Python 构建，采用智能体驱动架构，整合 Remotion 合成、Kling/Veo 等视频生成模型，提供 AGPLv3 开源许可，并配有完整的 Agent Guide 和 PR Review Guide 文档。

---
## 10. [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch)
- **语言**: Python
- **Stars**: 50,190
- **简介**: Learn it. Build it. Ship it for others.

### AI 总结
**简介**: 一个从零开始系统学习AI工程的开源课程，包含511节课、20个阶段，覆盖Python/TypeScript/Rust/Julia多语言，目标是让学习者不仅学会AI，还能亲手构建并交付可复用的AI产品。

**核心功能**:
- **完整课程体系**: 511节课、20个阶段、约329小时学习时长，从环境搭建、数学基础到LLM工程、Agent开发全覆盖
- **多路径学习**: 提供按目标选择的学习路线（如新手入门、LLM应用开发、Agent构建、MCP协议、Agent Skills、Claude认证等），无需从头扫课
- **实战导向**: 每节课都产出一个可复用的成果物（prompt、技能、agent、MCP服务器等），强调"边学边建"
- **多语言支持**: 项目主页提供12种语言翻译，课程页面支持机器翻译
- **双平台访问**: 同一课程代码支持在GitHub和官方网站（aiengineeringfromscratch.com）上学习
- **免费开源**: MIT许可证，完全免费

**技术亮点**: 覆盖Python、TypeScript、Rust、Julia四种语言；课程体系包含20个阶段的结构化设计；提供MCP（Model Context Protocol）和Agent Skills的专项学习路径；配套官方认证（Claude认证）备考资源；项目作者还开发了与任意agent/聊天助手兼容的Agent Memory持久化记忆工具。

---
