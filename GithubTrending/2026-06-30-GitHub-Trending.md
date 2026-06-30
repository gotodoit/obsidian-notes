---
tags:
  - github-trending
  - daily
date: 2026-06-30
created: 2026-06-30T01:55:45.435Z
---

# 2026-06-30 GitHub Trending Top 10

## 1. [simplex-chat/simplex-chat](https://github.com/simplex-chat/simplex-chat)
- **语言**: Haskell
- **Stars**: 16,644
- **简介**: SimpleX - the first messaging network operating without user identifiers of any kind - 100% private by design! iOS, Android and desktop apps 📱!

### AI 总结
**简介**: SimpleX 是首个完全无用户标识符的隐私优先消息网络，支持 iOS、Android 和桌面端。

**核心功能**:
- 端到端加密通信，采用双重棘轮协议并附加加密层
- 保护消息内容和元数据（联系人、通信时间等）
- 支持移动端（iOS/Android）和终端 CLI 应用
- 提供用户群组、私密连接和开发者团队交流功能

**技术亮点**: 使用 Haskell 开发，无任何用户标识符设计，通过 SMP 协议实现去中心化消息传递。

---
## 2. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 118,956
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: 一个由精心设计的 AI 代理角色组成的集合，每个代理都是特定领域的专家，旨在为各种工作流提供生产就绪的交付成果。

**核心功能**:
- **专业化 AI 代理**: 提供从前端开发、UI 设计到安全审计、Reddit 社区运营等超过 16 个领域的专用 AI 代理。
- **一键安装**: 通过原生桌面应用（支持 macOS, Linux, Windows）或脚本，可将代理安装到 Claude Code、Cursor、Codex、Gemini CLI 等多种 AI 工具中。
- **灵活部署**: 支持选择性安装，用户可以只安装特定工具或特定领域的代理团队。
- **跨工具集成**: 支持与 Claude Code、Cursor、Aider、Windsurf、Copilot 等主流 AI 编码工具集成。

**技术亮点**:
- 基于 Shell 脚本实现跨平台安装和工具适配。
- 代理配置文件采用 Markdown 格式，包含身份、个性、工作流、交付物和成功指标等结构化信息。
- 提供原生桌面应用，实现无命令行、自动更新的安装体验。

---
## 3. [cupy/cupy](https://github.com/cupy/cupy)
- **语言**: Python
- **Stars**: 11,832
- **简介**: NumPy & SciPy for GPU

### AI 总结
**简介**: CuPy 是一个与 NumPy/SciPy 兼容的 GPU 加速数组计算库，旨在作为现有 NumPy/SciPy 代码在 NVIDIA CUDA 或 AMD ROCm 平台上的即插即用替代品。

**核心功能**:
- 提供与 NumPy/SciPy 一致的 API，支持 GPU 上的数组操作和科学计算。
- 兼容 NVIDIA CUDA 和 AMD ROCm 平台，通过 pip、conda 或 Docker 安装。
- 支持底层 CUDA 特性，如自定义 CUDA C/C++ 内核（RawKernels）、Stream 性能优化和直接调用 CUDA Runtime API。

**技术亮点**: 基于 CUDA/ROCm 架构，实现 GPU 加速的数组计算；支持多平台（x86_64、aarch64、ppc64le）和多安装方式（pip、conda、Docker）。

---
## 4. [altic-dev/FluidVoice](https://github.com/altic-dev/FluidVoice)
- **语言**: Swift
- **Stars**: 4,419
- **简介**: FluidVoice - Fastest macOS Offline Dictation app - Voice to Text fully Local. One ⭐ takes us a long way :))

### AI 总结
**简介**: FluidVoice 是一款为 macOS 设计的开源离线语音转文字听写应用，支持本地 AI 增强，无需联网即可实现快速、隐私安全的听写体验。

**核心功能**:
- **离线语音听写**: 支持多种本地模型（如 Nemotron Speech 3.5、Parakeet Flash/ v3/v2、Cohere、Apple Speech、Whisper），实现低延迟的语音转文字。
- **Fluid Intelligence**: 本地 AI 引擎，提供智能格式化、上下文感知大写和后处理增强，所有数据均在 Mac 上处理，不上传云端。
- **命令模式**: 通过语音控制 Mac，如启动应用、运行快捷指令、触发系统操作等。
- **写模式**: 在任何应用的文本框中通过语音编写或重写文本。
- **主题切换**: 支持自适应浅色/深色主题，并配有紧凑的工具栏切换器。
- **历史与统计**: 记录听写历史并提供使用统计。

**技术亮点**: 基于 Swift 开发，利用本地 AI 模型（如 NVIDIA Parakeet）实现极低延迟听写；采用 GPLv3 开源协议，核心听写功能免费，Fluid Intelligence 作为独立私有运行时提供高级增强。

---
## 5. [soxoj/maigret](https://github.com/soxoj/maigret)
- **语言**: Python
- **Stars**: 34,403
- **简介**: 🕵️‍♂️ Collect a dossier on a person by username from 3000+ sites

### AI 总结
**简介**: Maigret 是一个根据用户名从超过 3000 个网站收集目标人物档案的信息收集工具，无需 API 密钥。

**核心功能**:
- 支持 3000+ 网站的用户名搜索，默认检查 500 个高流量网站，可扩展至全部或按标签筛选。
- 从个人资料页面和网站 API 提取账户所有者的公开信息，包括关联的其他账户链接。
- 支持递归搜索，利用发现的用户名和 ID 进行深度挖掘。
- 可嵌入 Python 项目，作为库进行程序化调用。

**技术亮点**:
- 基于 Python 3.10+ 开发，依赖社区维护的网站检测规则。
- 集成反封锁和绕过审查机制，部分处理 CAPTCHA 验证。
- 提供 Web 界面和 Telegram 机器人等交互方式。

---
## 6. [commaai/openpilot](https://github.com/commaai/openpilot)
- **语言**: Python
- **Stars**: 62,783
- **简介**: openpilot is an operating system for robotics. Currently, it upgrades the driver assistance system on 300+ supported cars.

### AI 总结
**简介**: openpilot 是一个用于机器人技术的操作系统，目前已为超过300种车型升级了驾驶辅助系统。

**核心功能**:
- 支持300+车型的驾驶辅助系统升级
- 提供多种预构建分支（release、staging、nightly等）
- 支持comma four等专用硬件设备即插即用
- 提供社区贡献和开发工具支持

**技术亮点**:
- 基于Python开发，遵循ISO26262安全标准
- 采用C语言编写的panda安全模型代码
- 拥有软件在环测试（SIL）机制
- 支持GitHub Actions持续集成测试

---
## 7. [ripienaar/free-for-dev](https://github.com/ripienaar/free-for-dev)
- **语言**: HTML
- **Stars**: 126,754
- **简介**: A list of SaaS, PaaS and IaaS offerings that have free tiers of interest to devops and infradev

### AI 总结
**简介**: 这是一个为开发者和运维人员整理的 SaaS、PaaS、IaaS 等服务的免费套餐清单，帮助快速找到可用的免费资源。

**核心功能**:
- 提供主流云厂商（如 Google Cloud）的永久免费资源详情。
- 按类别（如 CI/CD、监控、存储、API、DNS 等）整理了大量服务的免费套餐。
- 涵盖基础设施、开发工具、数据分析、安全、协作等多个领域。
- 社区维护，通过 Pull Request 持续更新，已有 1600+贡献者。
- 严格筛选标准：仅收录提供真正免费套餐（非免费试用）且至少一年有效的 as-a-Service 产品。

**技术亮点**:
- 项目本身使用 HTML 构建，结构清晰，便于浏览和贡献。
- 基于社区协作模式，利用 GitHub 的 Pull Request 机制进行内容审核与更新。

---
## 8. [logto-io/logto](https://github.com/logto-io/logto)
- **语言**: TypeScript
- **Stars**: 12,693
- **简介**: 🧑‍🚀 Authentication and authorization infrastructure for SaaS and AI apps, built on OIDC and OAuth 2.1 with multi-tenancy, SSO, and RBAC.

### AI 总结
**简介**: 一个为 SaaS 和 AI 应用构建的现代、开源的身份验证和授权基础设施，基于 OIDC 和 OAuth 2.1，支持多租户、企业 SSO 和 RBAC。

**核心功能**:
- 开箱即用的多租户、企业单点登录（SSO）和基于角色的访问控制（RBAC）
- 预构建的登录流程、可自定义的用户界面，以及支持 30 多个框架的 SDK
- 全面支持 OIDC、OAuth 2.1 和 SAML 协议，无需处理协议复杂性
- 原生支持 Model Context Protocol (MCP) 和基于代理的 AI 架构

**技术亮点**: 使用 TypeScript 构建，提供 Docker Compose 和 Node.js 两种本地开发方式，支持云服务和 GitPod 快速启动，拥有丰富的第三方身份提供商（IdP）连接器生态。

---
## 9. [xbtlin/ai-berkshire](https://github.com/xbtlin/ai-berkshire)
- **语言**: Python
- **Stars**: 6,676
- **简介**: AI 时代的伯克希尔：基于 Claude Code / Codex 的价值投资研究框架。巴菲特·芒格·段永平·李录四大师方法论 + 多Agent并行研究。| AI-era Berkshire: a value investing research framework built for Claude Code / Codex. 4 masters' methodologies + multi-agent adversarial analysis.

### AI 总结
**简介**: 一个基于 Claude Code / Codex 的价值投资研究框架，融合巴菲特、芒格、段永平、李录四位大师的方法论，通过多 Agent 并行实现专业级投研。

**核心功能**:
- **四大师视角对抗**: 同时从商业模式、财务估值、逆向思考、长期确定性四个角度分析，产生真实矛盾与张力，避免单一视角盲点。
- **结构化反偏见机制**: 内置信息丰富度评级、芒格式逆向检验、快速否决清单、反共识检查、留白原则等多层防错机制。
- **多 Agent 并行研究**: 启动 4 个独立 Agent 同时研究一家公司，各自独立搜索、验证、结论，最后由 Team Lead 综合，实现 4 倍搜索量与信息源。
- **强制结论输出**: 输出通过/不通过/灰色地带，带具体价格区间和分层建议，不打太极。
- **金融数据精确性**: 所有计算使用 Python `decimal.Decimal`，关键数据至少 2 个独立来源交叉验证，避免 LLM 心算错误。
- **可复现研究流程**: 保证同一输入输出结构一致、深度一致，支持横向对比与纵向追踪。
- **18 个 Skill 入口**: 覆盖深度研究、财报分析、行业筛选、持仓管理、思维工具等场景，如 `/investment-team`、`/management-deep-dive`、`/private-company-research` 等。

**技术亮点**: 基于 Claude Code / Codex 的 Agent 框架，采用四 Agent 并行 + Team Lead 综合的架构，结合 Python `decimal.Decimal` 精确计算与实时金融数据检索，实现结构化、可验证的投资研究流程。

---
## 10. [browser-use/video-use](https://github.com/browser-use/video-use)
- **语言**: Python
- **Stars**: 11,964
- **简介**: Edit videos with coding agents

### AI 总结
**简介**: video-use 是一个开源工具，允许用户通过 Claude Code 等编码代理以自然语言对话的方式编辑视频，将原始素材剪辑成最终成品。

**核心功能**:
- 自动剪切填充词（如“umm”、“uh”）和片段的空白部分。
- 自动为每个片段进行调色（支持暖色电影感、中性鲜明等预设或自定义 ffmpeg 链）。
- 在每个剪切点自动添加 30ms 音频淡入淡出，避免爆音。
- 按用户风格生成字幕（默认采用2个单词大写分块，完全可定制）。
- 通过 HyperFrames、Remotion、Manim 或 PIL 等工具生成动画叠加层，支持并行子代理处理。
- 在渲染输出后对每个剪切边界进行自我评估，确保质量。
- 将会话记忆持久化到 `project.md` 文件中，方便下次会话继续。

**技术亮点**:
- 采用“文本+按需视觉”的架构，不直接分析视频帧，而是通过音频转录（ElevenLabs Scribe）和“timeline_view”PNG图像（包含胶片条、波形和词标签）为LLM提供结构化信息，极大降低了Token消耗（从4500万降至12KB文本加少量图片）。
- 核心管线为：转录 -> 打包 -> LLM推理 -> 编辑决策列表（EDL） -> 渲染 -> 自我评估（最多循环3次修正）。
- 支持通过 Browser Use Box 实现在VPS或Telegram上的持续编辑。

---
