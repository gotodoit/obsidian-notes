---
tags:
  - github-trending
  - daily
date: 2026-09-14
created: 2026-09-14T01:55:43.098Z
---

# 2026-09-14 GitHub Trending Top 10

## 1. [JustVugg/colibri](https://github.com/JustVugg/colibri)
- **语言**: C
- **Stars**: 29,929
- **简介**: Run frontier MoE models on hardware you already own — pure C, zero deps, experts streamed from disk. Tiny engine, immense model. 🐦

### AI 总结
**简介**: Colibrì 是一个纯 C 编写、零依赖的 MoE 推理引擎，通过将存储、内存和显存统一为多级推理层级，让消费级硬件也能运行 744B 至 2.8T 参数的前沿 MoE 模型。

**核心功能**:
- 支持九大模型家族（GLM-5.2/5.3、Inkling、Kimi K3、DeepSeek V4 系列、Qwen3.8-Flash-Next、Qwen3.6、OLMoE），每个模型仅需一个 C 文件
- 统一前端命令 `coli chat` / `coli serve` / `coli web`，提供对话、服务和 Web 仪表盘三种交互方式
- Web 仪表盘可视化实时指标：VRAM/RAM/磁盘分层、专家路由热度、Token 延迟分解，以及专家大脑（Brain）和专家图谱（Atlas）页面

**技术亮点**:
- **AI 内存多级化**：将 VRAM、RAM 和存储视为单一层级，专家权重从磁盘流式加载，实现 744B 模型在 6× RTX 5090 上 4 tok/s、TTFT 1.6s 的推理表现
- **纯 C 零依赖**：引擎本身无外部依赖，代码规模精简，便于修改和实验
- **语义保证**：默认策略绝不静默改变模型精度或路由器语义，速度可因内存不足下降，但模型定义不被悄悄改写
- **开放研究平台**：鼓励在模型格式、内存层级、存储 I/O、调度、内核、推测解码和 CPU/GPU 重叠等方向进行激进系统实验，以端到端可复现测量为准绳

---
## 2. [ever-co/ever-gauzy](https://github.com/ever-co/ever-gauzy)
- **语言**: TypeScript
- **Stars**: 5,133
- **简介**: Ever® Gauzy™ - Open Business Management Platform (ERP/CRM/HRM/ATS/PM) - https://gauzy.co

### AI 总结
**简介**: Ever Gauzy 是一个基于 TypeScript 构建的开源商业管理平台，面向协作、按需和共享经济场景，集成 ERP、CRM、HRM、ATS 和项目管理等核心业务模块。

**核心功能**:
- 人力资源管理（HRM）：时间追踪、员工绩效监控、入职管理、休假审批
- 客户关系管理（CRM）：联系人管理、销售管道、提案与报价
- 企业资源规划（ERP）：财务与成本管理、会计、发票、库存与供应链
- 项目管理：任务、目标/KPI、日程与事件管理
- 人才招聘（ATS）：候选人追踪与面试管理
- 其他：多组织管理、多币种、多语言、数据导入导出、角色权限、第三方集成（Upwork、HubStaff 等）

**技术亮点**: 采用 TypeScript 开发，提供 Headless API（REST），支持 Web UI 和桌面计时器应用；配套 Ever Teams 平台基于 React (Next.js) / React Native (Expo) 技术栈，可对接 Gauzy 无头 API；支持多种主题（暗色/亮色/企业/材料），采用 AGPL v3 开源协议。

---
## 3. [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view)
- **语言**: JavaScript
- **Stars**: 31,987
- **简介**: A spy satellite simulator in your browser, except the data is real. Live open source spatial intelligence on a photorealistic 3D globe.

### AI 总结
**简介**: 一个基于浏览器的开源间谍卫星模拟器，在逼真的 3D 地球上实时呈现真实的公开空间情报数据。

**核心功能**:
- **实况追踪**：实时显示飞机、舰船、卫星、地震、交通和公共摄像头等公开数据源
- **座舱视角**：可进入被追踪航班的驾驶舱，相机全程锁定下方地形
- **点击追踪**：锁定任意目标，绘制渐隐轨迹并展示完整元数据，火灾或船只可一键移交至最近实况摄像头
- **语音控制**：由实时 AI 代理驱动的免手操作语音指令，并支持语音在世界地图上标注边界、标记和路线
- **3D 机库**：按机型呈现真实 3D 飞机模型（787、ATR-72、Citation、Bell 206、MQ-9），目标接近时从图标切换为 3D 模型
- **传感器滤镜**：通过 GLSL 着色器叠加 CRT、夜视、FLIR 热成像、黑白、雪景等视觉效果
- **军事 HUD 与检测叠加**：战术平显与情报风格遥测，屏幕空间检测框和 ID 标注
- **分享链接**：相机、样式、图层乃至被追踪目标均可序列化为 URL，实现实况目标移交
- **场景导演**：可录制电影级相机巡游用于剪辑和演示

**技术亮点**:
- 使用 JavaScript 开发，运行于浏览器本地，所有源码可审查、可扩展
- 每个数据图层均为独立模块，便于添加自定义数据源
- 无需 API 密钥即可启动，使用 Esri 卫星影像与无密钥地形（OSM 作为回退），可在应用内按需添加可选密钥
- 支持通过 Pinokio 一键安装或从终端本地运行
- 交通数据基于真实道路与聚合位置数据模拟，CCTV 机位和火箭发射轨迹为粗略估算
- 项目曾登上 GitHub Trending 日榜与周榜第一（2026 年 8 月），并在 Product Hunt 获得当日第 8 名

---
## 4. [tech-leads-club/agent-skills](https://github.com/tech-leads-club/agent-skills)
- **语言**: TypeScript
- **Stars**: 5,679
- **简介**: The secure, validated skill registry for professional AI coding agents. Extend Antigravity, Claude Code, Cursor, Copilot and more with absolute confidence.

### AI 总结
**简介**: 一个面向专业 AI 编程代理的安全、经验证的技能注册库，可为 Claude Code、Cursor、Copilot 等工具扩展经过测试的能力。

**核心功能**:
- 提供打包好的技能（指令与资源），像插件一样扩展 AI 代理的工作流和专业知识
- 支持将技能安装到多种 AI 编程代理，涵盖 Claude Code、Cline、Aider、Antigravity、Amazon Q 等
- 内置 MCP Server，并提供 CLI 工具进行技能管理与安装

**技术亮点**:
- 100% TypeScript 编写，要求 Node.js >= 22，采用 Nx Cloud 与 semantic-release 进行构建和发布
- 安全加固：100% 开源无二进制、CI/CD 静态分析、lockfile 与内容哈希保证完整性、人工审核提示词
- CLI 采用纵深防御（输入净化、路径隔离、符号链接防护、原子锁文件、审计追踪），发布前经 Snyk Agent Scan 扫描

---
## 5. [melgarafael/DeskcommCRM](https://github.com/melgarafael/DeskcommCRM)
- **语言**: TypeScript
- **Stars**: 2,215
- **简介**: Open-source AI sales OS — self-hosted CRM with native AI agents + WhatsApp (WAHA). Open alternative to Kommo, Octadesk & Intercom for any business that sells by chat. MCP-ready, multi-tenant, LGPD.

### AI 总结
**简介**: DeskcommCRM 是一款开源的 AI 销售操作系统，自托管 CRM 内置原生 AI 智能体并集成 WhatsApp（基于 WAHA），定位为 Kommo、Octadesk 和 Intercom 的开放替代方案，面向所有通过聊天进行销售的业务。

**核心功能**:
- AI 智能体在 WhatsApp 内完成接待、线索资格筛选与销售转化
- 自托管部署，无月费、无功能锁定，数据完全归用户所有
- 通过 QR 码连接 WhatsApp 号码，支持 Meta 官方渠道
- 一键式 VPS 安装脚本（与 HostGator 合作），无需手动安装 Node/pnpm 或编译
- 多租户支持，符合 LGPD（巴西数据保护法），MCP-ready

**技术亮点**:
- 技术栈：Next.js 16 + TypeScript（strict 模式）+ Supabase（Postgres + Auth + Storage）
- 基于 Docker 的部署方案，提供 HostGator 专用安装套件与生产运行手册
- 安装器自动生成密钥、创建 Postgres 扩展、应用完整 schema 并初始化管理员账户
- 支持通过 OpenRouter、Anthropic 或 OpenAI 接入 AI 能力
- 采用 MIT 许可证，提供 CI 流程与多语言文档（葡/英/西）

---
## 6. [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)
- **语言**: Python
- **Stars**: 58,484
- **简介**: World's first open-source, agentic video production system. 12 production pipelines, 100+ tools, 700+ agent skill and production-knowledge files. Turn your AI coding assistant into a full video production studio.

### AI 总结
**简介**: OpenMontage 是全球首个开源、Agent 驱动的视频制作系统，可将 AI 编程助手转变为完整的视频制作工作室。

**核心功能**:
- **12 条制作流水线 + 100+ 工具**：覆盖从概念、脚本、分镜到剪辑、合成的完整流程，并附带 700+ Agent 技能与制作知识文件。
- **自然语言驱动**：用日常语言描述需求，Agent 自动完成调研、脚本撰写、素材生成、剪辑与最终合成。
- **真实视频制作能力**：可从免费素材库和开放档案中检索真实动态片段，剪辑成时间线并渲染成片，而非仅将静态图"动起来"。
- **示例作品**：已产出科幻预告片《SIGNAL FROM TOMORROW》与 60 秒皮克斯风格动画短片《THE LAST BANANA》。

**技术亮点**:
- 语言：Python
- 采用 Agent 架构，集成 Veo（视频生成）、Kling v3（动画生成）、Remotion（视频合成）等工具链
- 支持多家 AI 提供商，兼容免费/开源工作流
- 许可证：AGPLv3；曾登顶 GitHub Trending 日榜第一

---
## 7. [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)
- **语言**: JavaScript
- **Stars**: 66,080
- **简介**: Extracted system prompts from Anthropic - Claude Fable 5.1, Opus 5, Claude Design, Claude Code. OpenAI - ChatGPT GPT-6-Astra, Codex. Google - Gemini 3.8 Flash, 3.1 Pro, Antigravity. xAI - Grok, Grok Bot, Cursor, Kimi and more! Updated regularly.

### AI 总结
**简介**: 该项目收集并整理了各大 AI 聊天机器人（ChatGPT、Claude、Gemini、Grok 等）泄露的原始系统提示词，供研究者和开发者了解 AI 在首次对话前接收的隐藏指令与规则。

**核心功能**:
- 收录 Anthropic（Claude Fable 5.1、Opus 5、Sonnet 5、Claude Code、Claude Design 等）的系统提示词
- 收录 OpenAI（ChatGPT GPT-6-Astra、Codex、GPT-5.6 等）的系统提示词
- 收录 Google（Gemini 3.8 Flash、3.1 Pro、Antigravity 等）的系统提示词
- 收录 xAI（Grok 4.6、Grok Bot）、Kimi、Perplexity、Meta Muse Code、Cursor 等多个平台的提示词
- 提供按厂商和模型分类的目录结构，并持续更新最新版本（含日期和链接）

**技术亮点**: 项目以 Markdown 文档为主要载体，按厂商（Anthropic、OpenAI、Google、xAI 等）分目录组织；使用 JavaScript 辅助管理；被《华盛顿邮报》和 CEPS' AI World 等媒体引用作为报道和可视化数据来源。

---
## 8. [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi)
- **语言**: Go
- **Stars**: 24,002
- **简介**: Fully autonomous AI Agents system capable of performing complex penetration testing tasks

### AI 总结
**简介**: PentAGI 是一个基于 Go 语言开发的全自主 AI 智能体系统，专为执行复杂渗透测试任务而设计。

**核心功能**:
- 全自主渗透测试：AI 智能体自动规划并执行渗透测试步骤，支持可选的执行监控和智能任务规划
- 内置 20+ 专业安全工具（nmap、metasploit、sqlmap 等）
- 安全隔离的 Docker 沙箱环境，所有操作完全隔离
- 智能记忆系统：长期存储研究结果和成功方法以供复用
- 专家团队协作：研究、开发、基础设施等专用 AI 智能体分工协作
- 网络情报收集：内置浏览器抓取及多种外部搜索 API 集成（Tavily、Firecrawl、Perplexity、DuckDuckGo 等）
- 可选知识图谱集成（基于 Graphiti + Neo4j）
- 完善的监控与报告：Grafana/Prometheus 集成，自动生成详细漏洞报告

**技术亮点**:
- 采用 Go 语言构建，基于 Docker 容器化部署
- 支持多种 LLM 提供商（OpenAI、Anthropic、Gemini、AWS Bedrock、DeepSeek、Ollama、Qwen 等）
- 可选知识图谱（Graphiti + Neo4j）实现语义关系追踪
- 集成 Langfuse 进行可观测性与监控
- 支持 GitHub/Google OAuth 登录
- 提供现代化 Web UI 和完整 API 接口

---
## 9. [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE)
- **语言**: Python
- **Stars**: 7,782
- **简介**: YuE2: frontier music generation with symbolic planning, zero-shot covers, and agentic music editing.

### AI 总结
**简介**: YuE2 是新一代音乐生成模型，通过符号化规划实现高质量歌曲创作、零样本翻唱与智能体音乐编辑。

**核心功能**:
- **歌曲创作**：输入歌词与风格提示，自动生成旋律与和弦规划，再渲染为含人声与伴奏的完整歌曲
- **零样本翻唱**：将转录的歌曲以全新风格重新演绎
- **智能体编辑**：通过对话式交互修改乐谱、编曲与歌词，生成新版本

**技术亮点**:
- 采用 AR–NAR Mixture-of-Transformers 架构，自回归预测乐谱与语义 token，再用流匹配生成声学潜变量，VAE 解码为 48 kHz 立体声
- 符号化规划使旋律与和弦成为可读、可编辑的显式控制，支持白盒式音乐生成
- 在 WildSongBench 上达到 6.9632 SongBench Avg（best-of-8），与 Suno v5/v6 具有竞争力
- 分阶段 Python API：`plan()` → `generate_semantic()` → `synthesize()` → `decode()`

---
## 10. [yuliskov/SmartTube](https://github.com/yuliskov/SmartTube)
- **语言**: Java
- **Stars**: 33,465
- **简介**: Browse media content with your own rules on Android TV

### AI 总结
**简介**: SmartTube 是一款面向 Android TV 和电视盒子的免费开源媒体客户端，支持用户按自己的规则浏览和播放各类公开媒体内容。

**核心功能**:
- 干净的 TV 优化界面，支持 SponsorBlock 跳过赞助片段
- 可调节播放速度，支持 8K 分辨率、60fps 及 HDR
- 支持查看直播聊天、自定义按钮
- 无需 Google 服务即可运行

**技术亮点**:
- 基于 Java 开发，兼容 Android 4.3 (KitKat) 及以上设备
- 不依赖 Google Services，支持 F-Droid 及 GitHub 分发
- 使用一次性连接码机制，权限受限，安全性较高
- 明确不支持手机、平板及非 Android 平台（如 Tizen、webOS、Apple TV）

---
