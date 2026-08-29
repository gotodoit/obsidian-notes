---
tags:
  - github-trending
  - daily
date: 2026-08-29
created: 2026-08-29T01:55:43.969Z
---

# 2026-08-29 GitHub Trending Top 10

## 1. [tt-a1i/archify](https://github.com/tt-a1i/archify)
- **语言**: JavaScript
- **Stars**: 27,589
- **简介**: Agent skill for beautiful, verifiable architecture, workflow, sequence, data-flow, and lifecycle diagrams—self-contained HTML with motion and crisp export.

### AI 总结
**简介**: Archify 是一个 Node.js 渲染与验证系统，可将代码库或系统描述直接转化为精美的交互式系统架构图，支持在聊天中生成、展示与分享。

**核心功能**:
- **五类图表与多主题** — 支持架构、工作流、时序、数据流和生命周期图，提供 4 种预设、深/浅色主题及内置品牌标识
- **架构变更审查** — 对比两个已验证快照（Before / Delta / After），精确呈现新增、删除、修改、移动和重路由的事实
- **交互式探索** — 节点搜索、溯源验证、上下游路由追踪、角色对比，以及可播放的引导式故事，全程不虚构拓扑
- **单文件输出与导出** — 生成自包含 HTML，并支持导出 PNG、SVG、WebM 及 1200×630 分享卡片

**技术亮点**: 基于类型化 JSON 中间表示（IR）与确定性编译，确保图表可验证、可复现；支持 Cursor、Claude Code、Codex CLI 和 OpenCode 等主流 Agent 环境，通过 `npx skills add tt-a1i/archify -g` 一键安装；采用 MIT 开源协议，当前开发版本为 v2.16.0-dev.0。

---
## 2. [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- **语言**: Python
- **Stars**: 36,657
- **简介**: Turn any AI agent into an AI Scientist. The #1 Agent Skills library for science, used by 175,000+ scientists worldwide. 163 ready-to-use validated skills plus 100+ scientific databases covering biology, chemistry, medicine, and drug discovery. Compatible with Cursor, Claude Code, Codex, Pi, Antigravity, and the open Agent Skills standard.

### AI 总结
**简介**: 一个将任意AI代理转变为AI科学家的开源技能库，提供163个经过验证的科学技能和100+科学数据库，覆盖生物学、化学、医学和药物发现领域，已被全球175,000+科学家使用。

**核心功能**:
- **163个即用型科学技能**：涵盖癌症基因组学、千人基因组查询、调控序列预测、病原体变异监测、分析方法验证、PK/PD建模与剂量选择、生物医学文献检索、药物-靶点结合、分子动力学、RNA速度分析、微生物组基础模型、地理空间科学、时间序列预测等
- **100+科学数据库集成**：支持78+个科学数据库的直接访问和查询，覆盖多学科领域
- **多代理兼容性**：支持Cursor、Claude Code、Codex、Google Antigravity等主流AI代理，遵循开放的Agent Skills标准
- **Agent Plugins支持**：可作为便携式插件包加载，插件兼容客户端可将整个集合作为单一插件加载
- **复杂多步骤科研工作流**：能够执行跨生物学、化学、医学等领域的端到端研究任务

**技术亮点**:
- 遵循开放的[Agent Skills](https://agentskills.io/)标准和[Agent Plugins](https://agent-plugins.org/)标准
- 基于Python实现，采用模块化技能架构
- 通过CI/CD流水线（安全扫描、技能测试）保障代码质量和安全性
- 配套开源AI协同科学家K-Dense BYOK，支持本地运行、自带API密钥、40+模型选择，可扩展至云端计算
- 提供丰富的社区资源：X、LinkedIn、YouTube、Reddit等渠道持续更新技能和演示

---
## 3. [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
- **语言**: Python
- **Stars**: 35,047
- **简介**: Official, Anthropic-managed directory of high quality Claude Code Plugins.

### AI 总结
**简介**: 这是 Anthropic 官方维护的 Claude Code 高质量插件目录，提供内部及第三方插件的集中安装与分发市场。

**核心功能**:
- 插件市场：通过 `/plugin install {plugin-name}@claude-plugins-official` 或 `/plugin > Discover` 直接安装插件
- 插件分类管理：`/plugins` 存放 Anthropic 内部插件，`/external_plugins` 存放来自合作伙伴和社区的第三方插件
- 标准化插件结构：每个插件包含 `.claude-plugin/plugin.json` 元数据，可选包含 MCP 服务器配置、斜杠命令、代理和技能定义
- 插件命名不可变机制：`name` 为不可变标识，支持通过 `renames` 映射实现旧插件名自动迁移
- 技能捆绑支持：允许无清单的仓库直接声明 `skills` 数组，支持跨子目录引用多个 `SKILL.md` 文件

**技术亮点**: 基于 JSON 清单驱动的插件系统，支持 `strict` 模式与技能捆绑模式；采用 git-subdir 源码引用方式（含 commit SHA 锁定）；通过 marketplace.json 实现插件重命名透明迁移；由 Anthropic 官方管理并对外部插件设置质量与安全审核标准。

---
## 4. [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view)
- **语言**: JavaScript
- **Stars**: 11,133
- **简介**: A spy satellite simulator in your browser, except the data is real. Live open source spatial intelligence on a photorealistic 3D globe.

### AI 总结
**简介**: 一个在浏览器中运行的“间谍卫星模拟器”，基于真实公开数据，在逼真的3D地球上实时追踪飞机、船只、卫星、地震、交通和公共摄像头。

**核心功能**:
- **实时全球追踪**: 基于公开信号（航空应答机、船舶信标、轨道要素、地震仪等）实时展示全球动态
- **驾驶舱视角**: 进入被追踪飞机的内部视角，地形随飞行持续变化
- **点击追踪与元数据**: 点击任意目标即可锁定、显示轨迹和完整元数据，并支持一键切换到最近的实时摄像头
- **语音控制与白板**: 通过AI代理进行免提语音控制，支持语音在世界上绘制注释、边界多边形和路线
- **3D机库与传感器效果**: 真实机型3D模型（787、ATR-72、MQ-9等），以及CRT、NVG、FLIR/热成像等GLSL传感器视觉风格
- **战术HUD与检测叠加**: 军事风格平视显示器，屏幕空间内显示目标的边界框和ID
- **场景导演与分享链接**: 制作电影级镜头巡游，将相机、样式、图层和追踪目标序列化到URL中实现实时交接

**技术亮点**: 基于JavaScript构建，使用Node.js 24.x/26.x，采用WebGL/GLSL着色器实现照片级3D地球渲染，客户端延迟一个轮询间隔以平滑插值，所有数据层均标注来源和新鲜度状态（实时/模拟/延迟/重建估计），支持API密钥配置。

---
## 5. [abhigyanpatwari/GitNexus](https://github.com/abhigyanpatwari/GitNexus)
- **语言**: TypeScript
- **Stars**: 46,167
- **简介**: GitNexus: The Zero-Server Code Intelligence Engine - GitNexus is a client-side knowledge graph creator that runs entirely in your browser. Drop in a git repository (Github, Gitlab, Azure, Local) or ZIP file, and get an interactive knowledge graph with a built in Graph RAG Agent. Perfect for code exploration

### AI 总结
**简介**: GitNexus 是一个完全在浏览器中运行的零服务器代码智能引擎，可将任意 Git 仓库或 ZIP 文件转化为交互式知识图谱，并内置 Graph RAG 智能代理，为 AI 编码助手提供深度代码架构分析能力。

**核心功能**:
- **代码知识图谱构建**: 自动索引代码库，追踪依赖关系、调用链、模块聚类与执行流程，生成完整的代码关系图谱
- **Graph RAG 智能代理**: 内置基于知识图谱的检索增强生成代理，支持对代码库进行自然语言问答与探索
- **多平台仓库支持**: 支持 GitHub、GitLab、Azure DevOps 及本地 Git 仓库，也可直接导入 ZIP 文件
- **AI 编辑器深度集成**: 通过 MCP (Model Context Protocol) 为 Cursor、Claude Code、Codex 等 AI 编码工具提供架构级上下文，减少错误编辑
- **一键式 CLI 工作流**: `npx gitnexus analyze` 完成索引、技能安装和上下文文件生成；`npx gitnexus setup` 自动配置编辑器 MCP
- **Web UI 交互界面**: 提供浏览器端聊天界面，无需安装即可快速探索任意代码仓库

**技术亮点**:
- 采用 TypeScript 构建，基于 tree-sitter 实现多语言语法解析（支持 Dart、Proto、Swift、Kotlin 等语言）
- 使用 ONNX Runtime 本地嵌入模型，支持离线语义检索
- 原生支持 MCP 协议，自动检测并配置主流 AI 编码工具
- 提供 AGENTS.md / CLAUDE.md 上下文文件自动生成机制
- 采用 PolyForm 非商业许可证，并提供企业版 SaaS/自托管方案

---
## 6. [JetBrains/go-modern-guidelines](https://github.com/JetBrains/go-modern-guidelines)
- **语言**: Go
- **Stars**: 2,615
- **简介**: Help AI coding agents write modern Go

### AI 总结
**简介**: 这是一个由 JetBrains 官方维护的 Go 代码规范指南仓库，旨在帮助 AI 编码助手编写更现代、更符合当前 Go 语言习惯的代码。

**核心功能**:
- 提供覆盖 Go 1.0 至 Go 1.27 的现代编码规范，包括 `max(a, b)`、`slices.Contains`、`cmp.Or(a, b, c)` 等新语法和标准库用法
- 自动检测项目 `go.mod` 中的 Go 版本，仅使用该版本及之前可用的语言特性和标准库
- 支持多种 AI 编码工具（Junie、Claude Code、Codex、Cursor），通过 marketplace/plugin 方式集成，AI 代理会在相关 Go 任务中自动调用这些规范
- 解决 AI 模型因训练数据滞后和频率偏差导致的生成过时 Go 代码问题，与 Go 团队 `modernize` 分析器的目标一致

**技术亮点**: 通过 CLI 工具（目标 Go 1.25+，支持自动工具链切换）分发规范，安装到本地缓存且不修改用户项目；以 SKILL.md 形式为 AI 代理提供显式参考，使新代码从一开始就采用现代惯用法，减少后续重构成本。

---
## 7. [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)
- **语言**: Python
- **Stars**: 53,351
- **简介**: World's first open-source, agentic video production system. 12 production pipelines, 100+ tools, 700+ agent skill and production-knowledge files. Turn your AI coding assistant into a full video production studio.

### AI 总结
**简介**: OpenMontage 是全球首个开源的智能体视频制作系统，能将 AI 编码助手转变为完整的视频制作工作室，支持从自然语言描述到成片的全自动生产流程。

**核心功能**:
- **12 条生产流水线**：覆盖概念、脚本、场景规划、素材生成、剪辑到最终合成的完整视频制作流程
- **100+ 工具集成**：整合视频生成（Veo、Kling v3）、图像生成、LLM、Remotion 合成等多种工具链
- **700+ 智能体技能与制作知识文件**：内置丰富的专业制作知识和技能库，供 AI 助手调用
- **真实视频素材检索**：可从免费素材库和开放档案中检索真实运动片段，剪辑成片，而非仅生成静态图片动画
- **纯自然语言驱动**：用户只需描述需求，代理自动完成研究、脚本、素材生成、编辑和最终合成
- **开源免费工作流**：支持完全开源/免费的视频制作路径，区别于常见的"动画化几张静态图"方案

**技术亮点**: 基于 Python 构建，采用智能体（agentic）架构，将 AI 编码助手扩展为多阶段视频生产系统；支持多种 AI 提供商（Claude、ChatGPT、DeepSeek 等）协作；具备从免费素材库构建语料库、检索运动片段并编排时间线的能力；采用 AGPLv3 开源协议。

---
## 8. [abi/screenshot-to-code](https://github.com/abi/screenshot-to-code)
- **语言**: Python
- **Stars**: 75,584
- **简介**: Drop in a screenshot and convert it to clean code (HTML/Tailwind/React/Vue)

### AI 总结
**简介**: 一款利用 AI 将截图、设计稿、Figma 设计和屏幕录制转换为干净、可运行代码（HTML/Tailwind/React/Vue 等）的开源工具。

**核心功能**:
- 支持多种技术栈转换：HTML + Tailwind、HTML + CSS、React + Tailwind、Vue + Tailwind、Bootstrap、Ionic + Tailwind
- 可将屏幕录制视频直接转换为可运行的功能原型
- 支持主流 AI 模型：Gemini 3 Flash/3.1 Pro、GPT-5.5/5.4 Mini、Claude Opus 4.6/4.8 等
- 资产提取功能：自动复用截图中的真实 Logo 和图片
- 图片编辑与背景移除（需配置 Replicate API）
- 支持模型对比，可在单次生成中比较多个模型的输出效果

**技术亮点**: 前后端分离架构（React/Vite 前端 + FastAPI 后端），使用 Playwright 实现无头浏览器截图预览功能（让 AI 渲染并自查生成的页面），支持 Docker 一键部署，可通过 Ollama 集成开源模型。

---
## 9. [cursor/plugins](https://github.com/cursor/plugins)
- **语言**: TypeScript
- **Stars**: 5,972
- **简介**: Cursor plugin specification and official plugins

### AI 总结
**简介**: Cursor 官方插件仓库，为开发者工具、框架和 SaaS 产品提供标准化插件，每个插件独立目录并包含 `.cursor-plugin/plugin.json` 清单文件。

**核心功能**:
- **教学与学习**: 提供技能映射、练习计划和教学回顾（Teaching 插件），以及持续学习机制（基于对话记录增量更新 AGENTS.md）
- **开发工作流增强**: 包含团队协作工具包（CI/代码审查/发布自动化）、PR 审查画布、文档画布、分支深度审查（Thermos）等
- **AI 代理优化**: 提供 CLI 设计模式、并行云代理编排（Orchestrate）、迭代自引用循环（Ralph Loop）等高级工作流
- **第三方集成**: 覆盖 Gmail、Google Drive/Calendar、Salesforce、GitHub、Playwright、Zoom、HubSpot、Intercom、DocuSign 等 20+ 主流 SaaS 服务
- **插件开发工具**: 提供脚手架工具（Create Plugin）和 TypeScript SDK，便于开发者构建自定义插件

**技术亮点**: 基于 TypeScript 开发，采用标准化的插件清单（plugin.json）机制，支持 CLI 驱动的代理兼容性扫描，以及结构化并行任务编排（planners/workers/verifiers）。

---
## 10. [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2)
- **语言**: JavaScript
- **Stars**: 24,279
- **简介**: Prompt as Code | GPT-Image2 工业级提示词引擎与模板库，530+ 个案例逆向工程，20+ 套工业级模板，并提炼出Skills，持续更新中

### AI 总结
**简介**: awesome-gpt-image-2 是一个面向 GPT-Image2 的工业级提示词引擎与模板库，基于“Prompt as Code”理念，通过 500+ 个逆向工程案例和 20+ 套工业级模板，帮助开发者高效生成高质量图像。

**核心功能**:
- **案例逆向工程库**: 收录 544 个真实案例，支持按风格或场景筛选，并可直接复制完整提示词。
- **工业级模板体系**: 提供 20+ 套可复用的提示词模板，覆盖多种图像生成场景。
- **可视化画廊网站**: 提供在线预览平台（gpt-image2.canghe.ai），支持大图预览、提示词复制、Google 登录后测试生成，并可跳转回 GitHub 源案例。
- **社区与生态支持**: 提供微信交流群、公众号（苍何）及 GitHub Sponsors 赞助通道。
- **多语言文档**: 支持英文、简体中文和日文。

**技术亮点**:
- 前端基于 JavaScript 构建，采用组件化架构（`src/assets` 等目录结构）。
- 集成赞助商 API（如 APIMart、hiapi），支持异步任务提交、轮询/回调获取结果，可批量生成图像。
- 提供可视化站点作为产品级体验入口，打通“浏览→复制→测试→溯源”完整链路。

---
