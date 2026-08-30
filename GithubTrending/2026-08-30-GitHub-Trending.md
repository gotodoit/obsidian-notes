---
tags:
  - github-trending
  - daily
date: 2026-08-30
created: 2026-08-30T01:55:44.212Z
---

# 2026-08-30 GitHub Trending Top 10

## 1. [tt-a1i/archify](https://github.com/tt-a1i/archify)
- **语言**: JavaScript
- **Stars**: 31,231
- **简介**: Agent skill for beautiful, verifiable architecture, workflow, sequence, data-flow, and lifecycle diagrams—self-contained HTML with motion and crisp export.

### AI 总结
**简介**: Archify 是一个 Node.js 渲染与验证系统，可将代码库或系统描述直接转化为精美、可验证的交互式架构图，支持在 Cursor、Claude Code、Codex CLI 和 OpenCode 等 AI 代理环境中使用。

**核心功能**:
- **五种图表类型与四种预设**：支持架构、工作流、时序、数据流和生命周期图，内置明暗主题与品牌标识，附带有限动画效果
- **架构变更审查**：对比两个已验证快照，精确显示新增、删除、修改、移动和重路由的变更（Before / Delta / After）
- **交互式探索**：支持节点搜索、溯源验证、上下游路径追踪、角色对比以及引导式故事播放
- **多格式导出**：生成自包含 HTML 文件，并可导出 PNG、SVG、WebM 及 1200×630 分享卡片

**技术亮点**: 采用类型化 JSON 中间表示（IR）与确定性编译机制，确保渲染结果可靠可验证；通过 `npx skills add tt-a1i/archify -g` 一键安装，当前开发版本为 v2.16.0-dev.0，基于 MIT 许可证开源。

---
## 2. [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view)
- **语言**: JavaScript
- **Stars**: 12,676
- **简介**: A spy satellite simulator in your browser, except the data is real. Live open source spatial intelligence on a photorealistic 3D globe.

### AI 总结
**简介**: 一个在浏览器中运行的“间谍卫星模拟器”，基于真实公开数据，在逼真的 3D 地球上实时追踪全球飞机、船舶、卫星、地震、交通和公共摄像头。

**核心功能**:
- **实时全球追踪**: 集成飞机、船舶、卫星、地震、交通和公共摄像头等公开数据源，并在地球上实时可视化。
- **沉浸式驾驶舱视角**: 可“乘坐”被追踪的航班，体验从空中俯瞰地形的第一人称视角。
- **点击追踪与元数据**: 点击任何目标即可锁定视角、显示轨迹和完整元数据，并能一键切换到最近的实时摄像头。
- **语音控制与白板**: 支持通过实时 AI 代理进行语音交互，并可通过语音在世界上绘制标注、边界和路线。
- **多样化的视觉模式**: 提供 CRT、NVG、FLIR/热成像、Noir、Snow 等多种 GLSL 传感器视觉风格，以及军事风格 HUD 和检测叠加层。
- **3D 模型与场景导演**: 展示飞机等目标的真实 3D 模型，并支持创建电影级相机巡游路径。
- **链接分享与快速重置**: 将当前视图状态（包括追踪目标）序列化为 URL 进行分享，并支持一键或语音重置地球视图。

**技术亮点**: 基于 JavaScript 构建，使用 Node.js 运行时；采用公开数据源（如 ADS-B 飞机应答机、AIS 船舶信标、轨道根数、地震仪等），并在数据不可用时明确标注为模拟或估算状态；利用 GLSL 着色器实现视觉特效；支持实时 AI 语音代理交互。

---
## 3. [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- **语言**: Python
- **Stars**: 37,977
- **简介**: Turn any AI agent into an AI Scientist. The #1 Agent Skills library for science, used by 190,000+ scientists worldwide. 165 ready-to-use validated skills plus 100+ scientific databases covering biology, chemistry, medicine, and drug discovery. Compatible with Cursor, Claude Code, Codex, Pi, Antigravity, and the open Agent Skills standard.

### AI 总结
**简介**: 一个将任意 AI 智能体转化为 AI 科学家的开源技能库，提供 163 个经过验证的科研技能和 100+ 科学数据库，覆盖生物学、化学、医学和药物发现等领域，兼容主流 AI 编程工具与开放 Agent Skills 标准。

**核心功能**:
- **165 个即用型科研技能**: 涵盖癌症基因组学、千人基因组查询、调控序列预测、病原体变异监测、PK/PD 建模、药物-靶点结合、分子动力学、RNA 速率分析、微生物组基础模型、地理空间科学、时间序列预测等
- **100+ 科学数据库集成**: 支持生物医学文献检索、监管文献获取、知识图谱搜索等跨学科数据访问
- **多平台兼容**: 支持 Cursor、Claude Code、Codex、Google Antigravity 等主流 AI 编程助手，遵循开放 Agent Skills 标准
- **插件化部署**: 可作为 Agent Plugins 包（`plugin.json` + `skills/`）一键加载，支持复杂多步骤科研工作流自动化
- **配套免费工具 K-Dense BYOK**: 开源的本地 AI 协同科学家，支持自备 API 密钥、40+ 模型选择，提供网页搜索、文件处理等完整研究环境

**技术亮点**: 基于 Python 构建，遵循开放 Agent Skills 标准和 Agent Plugins 规范；包含持续集成（安全扫描、技能测试）保障质量；支持本地运行（BYOK）与云端扩展（Modal）；采用模块化技能架构，便于跨学科组合复用。

---
## 4. [tailscale/tailcat](https://github.com/tailscale/tailcat)
- **语言**: Go
- **Stars**: 3,529
- **简介**: like netcat, but over Tailscale's data plane, without Tailscale's control plane

### AI 总结
**简介**: Tailcat 是一个基于 Tailscale 数据平面（而非控制平面）构建的 netcat 替代工具，提供点对点 WireGuard 加密隧道，无需 Tailscale 账号或 root 权限。

**核心功能**:
- **管道传输**: 在两端机器间通过 stdin/stdout 安全传输数据，服务端生成临时连接令牌，客户端凭令牌连接
- **端口转发**: 通过 `--serve` 参数将本地 TCP 端口（如 8080、8443）暴露给远程客户端访问
- **免认证 SSH**: 在 Linux/macOS 上运行 `--serve=no-auth-ssh` 即可提供无需认证的 SSH 服务（也可代理到系统 SSH）
- **Ping 测试**: 验证连接并报告数据路径（DERP 中继或直连），支持 `--until-direct` 等待直连建立
- **SOCKS5 代理**: 通过隧道提供 SOCKS5 代理，令牌可直接作为 URL 主机名使用
- **退出节点**: 支持 `--serve=exit-node` 模式，让客户端访问服务端所在网络
- **令牌解析**: 可离线解析连接令牌内容（WireGuard 公钥和 DERP 区域信息）为 JSON

**技术亮点**: 基于 Tailscale 的 magicsock 数据平面，使用 WireGuard 加密，通过 DERP 服务器进行 NAT 穿透和兜底中继；默认使用免费限流的 DERP 中继（https://tailcat.dev/derpmap.json），也可自建；提供 Go 库（`github.com/tailscale/tailcat`）和 CLI 工具；支持 WebAssembly 编译，有实验性浏览器端演示；完全开源，支持 Nix flakes 安装。

---
## 5. [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC)
- **语言**: TypeScript
- **Stars**: 22,325
- **简介**: Open Multi-Agent Interactive Classroom — Get an immersive, multi-agent learning experience in just one click

### AI 总结
**简介**: OpenMAIC 是一个开源的多智能体互动课堂平台，通过一次点击即可获得沉浸式多智能体学习体验，支持用 AI 智能体自动构建完整课程。

**核心功能**:
- **智能体工作台**：通过聊天方式规划、构建和修改整个课程，实现"一次提示，生成完整课程"
- **持久化会话**：服务器端运行的会话可跨重启保留，支持随时取消、恢复和调整
- **课程素材管理**：支持上传文档、音频、视频或从网络搜索获取素材，智能体基于这些素材构建课程
- **20+ 内置技能**：涵盖幻灯片、测验、互动内容、PBL、图像、视频、语音及 `.pptx` 导入等课程工具
- **一键部署**：支持 Vercel 一键部署，并提供实时在线演示

**技术亮点**: 基于 Next.js 16、React 19、TypeScript 5 构建，使用 LangGraph 1.1 作为智能体编排框架，Tailwind CSS 4 负责样式；采用"设计中立"架构，支持自带模型、媒体、搜索提供商和存储后端；集成 OpenClaw 和 Lemonade 本地 AI 方案，支持 FunASR 本地语音识别；已发表学术论文（JCST'26）。

---
## 6. [p-e-w/heretic](https://github.com/p-e-w/heretic)
- **语言**: Python
- **Stars**: 28,716
- **简介**: Fully automatic censorship removal for language models

### AI 总结
**简介**: Heretic 是一个全自动去除语言模型审查（安全对齐）的工具，无需昂贵的后训练，通过方向消融（abliteration）技术实现模型去审查。

**核心功能**:
- 全自动去审查：自动优化消融参数，无需理解 transformer 内部原理，只需运行命令行即可操作
- 保持模型智能：通过最小化拒绝次数和 KL 散度，在去除审查的同时尽可能保留原始模型的推理能力
- 内置评估功能：可对比去审查前后模型在"有害"提示词上的拒绝率和"无害"提示词上的 KL 散度
- 广泛模型支持：支持大多数稠密模型、多模态模型、多种 MoE 架构及混合模型（如 Qwen3.5）

**技术亮点**: 结合了高级方向消融（abliteration）实现（基于 Arditi et al. 2024 及 Lai 2025 的投影消融方法），并使用 Optuna 的 TPE 参数优化器自动搜索高质量消融参数。

---
## 7. [bigskysoftware/htmx](https://github.com/bigskysoftware/htmx)
- **语言**: JavaScript
- **Stars**: 49,125
- **简介**: </> htmx - high power tools for HTML

### AI 总结
**简介**: htmx 是一个轻量级、无依赖的 JavaScript 库，让你直接在 HTML 中使用属性即可实现 AJAX、CSS 过渡、WebSocket 和服务器推送事件，从而构建现代用户界面。

**核心功能**:
- **AJAX 请求**: 通过 `hx-post`、`hx-get` 等属性，让任意 HTML 元素发起 HTTP 请求，不再局限于 `<a>` 和 `<form>`。
- **响应替换**: 使用 `hx-swap` 等属性，灵活控制服务器响应替换页面元素的方式（如替换整个按钮或局部内容）。
- **CSS 过渡**: 支持在 AJAX 请求前后应用 CSS 过渡动画，提升页面交互体验。
- **WebSocket 与 SSE**: 通过扩展支持 WebSocket 和 Server Sent Events，实现实时通信。
- **事件触发**: 支持 `click`、`submit` 等多种事件触发请求，不局限于传统表单提交。
- **扩展性**: 提供扩展机制，允许自定义功能，且压缩后仅约 14k，无任何依赖。

**技术亮点**: 基于超文本（HATEOAS）理念，通过 HTML 属性（如 `hx-post`、`hx-swap`）简化前端开发，强调 REST 架构风格；使用 Mocha、Chai 和 Sinon 进行测试，支持 npm 安装（`htmx.org`）。

---
## 8. [JetBrains/go-modern-guidelines](https://github.com/JetBrains/go-modern-guidelines)
- **语言**: Go
- **Stars**: 2,875
- **简介**: Help AI coding agents write modern Go

### AI 总结
**简介**: JetBrains 官方项目，为 AI 编码代理提供现代 Go 语言编程规范，帮助代理写出符合最新 Go 版本特性的代码。

**核心功能**:
- 提供从 Go 1.0 到 1.27 的完整特性指南，涵盖 `modernize` 分析器涉及的所有功能
- 自动检测项目 `go.mod` 中的 Go 版本，并使用该版本及之前可用的语言特性和标准库
- 支持 Junie、Claude Code、Codex、Cursor 等主流 AI 编码代理的插件/扩展安装
- 通过 marketplace 机制分发，首次使用时自动安装 CLI 工具
- 鼓励使用现代惯用法（如 `max(a, b)` 替代 if-else、`slices.Contains` 替代手写循环、`cmp.Or` 替代 nil 检查链）

**技术亮点**:
- 解决 AI 编码代理生成过时 Go 代码的两大痛点：训练数据滞后（模型不了解训练截止后的新特性）和频率偏差（模型倾向于选择训练数据中更常见的旧模式）
- 与 Go 团队官方方向一致，通过 `modernize` 分析器自动更新现有代码，本指南则确保新代码从一开始就是现代风格
- CLI 工具安装在本地缓存（如 `~/.cache/go-modern-guidelines`），不修改用户项目，支持 Go 1.25+ 及自动工具链切换

---
## 9. [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)
- **语言**: Python
- **Stars**: 73,935
- **简介**: A curated list of awesome Claude Skills, resources, and tools for customizing Claude AI workflows

### AI 总结
**简介**: 一个精选的 Claude Skills 资源列表，收录了 1000+ 个生产可用的 Claude Skills 和插件，帮助用户定制 Claude AI 工作流，并支持 Claude Code、Cursor、Gemini CLI 等多种编码代理。

**核心功能**:
- 提供 1000+ 个现成的 Claude Skills，涵盖文档处理、开发工具、数据分析、业务营销、沟通写作、创意媒体、生产力、协作管理、安全系统等多个类别
- 通过 Composio MCP Gateway 为 Skills 提供真实世界操作能力，支持 1000+ 应用集成（发送邮件、创建 issue、发布 Slack 消息等），内置认证、团队权限控制、审计日志
- 提供 connect-apps 插件，快速将 Claude 连接到 1000+ 应用，支持一键安装和设置
- 支持 Skills 的渐进式加载机制——会话开始时仅加载技能名称和描述（约 100 tokens），完整内容按需加载，使单个代理可承载数百个技能而不膨胀上下文窗口
- 提供创建自定义 Skills 的指南和贡献指南

**技术亮点**: 基于 Anthropic 于 2025 年 10 月推出、12 月开源的 Skills 开放标准（SKILL.md + YAML frontmatter），已获得 Claude Code、Claude.ai、OpenAI Codex、Cursor、Gemini CLI 等主流代理支持；采用渐进式加载架构优化上下文窗口使用效率；通过 Composio MCP Gateway 实现标准化的外部系统连接（认证、传输、工具发现）。

---
## 10. [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)
- **语言**: Python
- **Stars**: 54,100
- **简介**: World's first open-source, agentic video production system. 12 production pipelines, 100+ tools, 700+ agent skill and production-knowledge files. Turn your AI coding assistant into a full video production studio.

### AI 总结
**简介**: OpenMontage 是全球首个开源、智能体驱动的视频制作系统，可将 AI 编程助手转变为完整的视频制作工作室。

**核心功能**:
- **自然语言视频创作**: 用户用自然语言描述需求，AI 智能体自动完成研究、脚本撰写、素材生成、剪辑和最终合成
- **12 条生产流水线**: 内置 12 条完整的视频制作流水线，覆盖不同类型的视频制作需求
- **100+ 工具集成**: 集成超过 100 种视频制作相关工具，包括视频生成、图像生成、剪辑等
- **700+ 智能体技能与知识文件**: 内置丰富的专业制作知识和智能体技能库，确保视频制作质量
- **真实视频素材支持**: 支持从免费素材库和开放档案中检索真实运动素材，编辑成时间轴并渲染成片，而非简单的静态图动画
- **完整视频制作能力**: 涵盖概念设计、脚本编写、场景规划、AI 生成运动片段、配乐和最终合成全流程

**技术亮点**: 基于 Python 构建，采用智能体驱动架构，结合 AI 生成模型（如 Veo、Kling）与 Remotion 合成技术，支持多模态 AI 推理平台接入（如 Atlas Cloud 统一 API），并可通过 Bloome 实现多 AI 智能体协作。

---
