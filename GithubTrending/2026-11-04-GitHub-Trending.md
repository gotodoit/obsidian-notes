---
tags:
  - github-trending
  - daily
date: 2026-11-04
created: 2026-11-04T01:55:42.617Z
---

# 2026-11-04 GitHub Trending Top 10

## 1. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 111,960
- **简介**: Persistent Context Across Sessions for Every Agent – Captures everything your agent does during sessions, compresses it with AI, and injects relevant context back into future sessions. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode + More

### AI 总结
**简介**: Claude-Mem 是一个为 AI 编程代理设计的持久化记忆压缩系统，能够捕获代理会话中的全部操作，用 AI 压缩后在未来会话中注入相关上下文。

**核心功能**:
- 跨会话持久化上下文：记录代理在每次会话中执行的所有操作，避免重复沟通和上下文丢失
- AI 驱动的记忆压缩：自动将冗长的会话内容压缩为精简摘要
- 上下文智能注入：在后续会话中自动检索并注入相关历史上下文
- 多代理兼容：支持 Claude Code、OpenClaw、Codex、Gemini、Hermes、Copilot、OpenCode 等多种 AI 编程代理

**技术亮点**: 基于 TypeScript 开发，要求 Node.js ≥ 20.0.0；采用 Apache 2.0 开源协议；提供 30 种语言的国际化文档；被 Awesome Claude Code 收录，并登上 GitHub Trending 日榜。

---
## 2. [vercel-labs/agent-desktop](https://github.com/vercel-labs/agent-desktop)
- **语言**: Rust
- **Stars**: 12,884
- **简介**: Computer use CLI for AI agents

### AI 总结
**简介**: Vercel Labs 推出的 AI 智能体桌面操作工具，通过系统无障碍树（Accessibility Tree）让 AI 无需截图即可“看见”并操作 macOS、Windows 和 Linux 上的桌面应用。

**核心功能**:
- **无障碍树快照**：读取桌面应用的 UI 元素并以 JSON 返回，每个可交互元素附带唯一 ref（含快照 ID），供智能体精准定位
- **基于 ref 的操作与验证**：智能体通过 ref 执行点击/输入，再重新快照比对结果，形成“观察—操作—验证”循环
- **多平台支持**：macOS（AX API）、Windows（UI Automation）、Linux（AT-SPI）统一抽象
- **双形态交付**：提供 CLI 与 C 库两种调用方式，并内置与版本匹配的智能体使用指南（`skills get`）
- **无头操作**：默认不移动指针、不改变焦点，可选 `--headed` 启用物理输入
- **安全提示**：快照、剪贴板、截图等可能含隐私内容，提醒避免进入公开日志

**技术亮点**:
- 使用 Rust 编写，跨平台原生二进制（x64 / ARM64），通过 `PlatformAdapter` trait 在编译期选择对应平台实现
- 不依赖截图或像素匹配，完全基于 OS 无障碍 API，稳定性更高
- 内置快照失效检测（`STALE_REF` / `AMBIGUOUS_TARGET`），强制重新快照以保证操作准确性
- 通过 npm 全局安装，也支持 Homebrew 及 GitHub Releases 原生包，便于集成到各类智能体框架
- 采用 Apache-2.0 开源协议

---
## 3. [max-sixty/worktrunk](https://github.com/max-sixty/worktrunk)
- **语言**: Rust
- **Stars**: 10,528
- **简介**: Worktrunk is a CLI for Git worktree management, designed for parallel AI agent workflows

### AI 总结
**简介**: Worktrunk 是一个用 Rust 编写的 Git worktree 管理 CLI，专为并行运行 AI agent 的工作流而设计，让 worktree 的使用像分支一样简单。

**核心功能**:
- 通过分支名直接切换/管理工作树（如 `wt switch feat`），路径按可配置模板自动计算，无需手动 `git worktree add` 加 `cd`
- 提供三个核心命令，覆盖 worktree 的创建、切换与清理等常见操作
- 支持 hooks 自动化本地工作流，并提供 copy-on-write 构建缓存以加速并行构建
- 面向多 agent 并行场景，便于同时管理 5-10+ 个独立工作目录，避免相互干扰

**技术亮点**: 使用 Rust 开发；以分支名寻址 worktree，命令同时兼容分支名与 worktree 路径；配套完整文档站点 worktrunk.dev，采用 MIT OR Apache-2.0 双许可。

---
## 4. [JustVugg/colibri](https://github.com/JustVugg/colibri)
- **语言**: C
- **Stars**: 47,267
- **简介**: A hierarchical inference engine for frontier MoE models: hot experts on the GPU (CUDA, Vulkan), warm ones in RAM, cold ones streamed from NVMe. Written in C, runs on the hardware you already own.

### AI 总结
**简介**: colibri 是一个用 C 编写的分层推理引擎，通过将 MoE 模型的热门专家放在 GPU、温专家放在内存、冷专家从 NVMe 流式读取，让普通硬件也能运行数百亿参数的超大开源模型。

**核心功能**:
- 支持 13 个推理引擎，覆盖 GLM-5.2/5.3、Kimi K3、DeepSeek V4 Flash、Qwen3.6、OLMoE 等十余种语言模型，以及图像生成（Qwen-Image-2.1）和决策模型（Laya、GLiNER2.5-Decide）
- 一键式安装脚本（Windows 的 `START-HERE.bat`、Linux/macOS 的 `start-here.sh`），自动检测硬件、推荐适配模型、下载并启动
- 直接读取已发布的 GGUF 文件，无需转换
- 内置 OpenAI 兼容与 Anthropic 兼容的 API 接口，并提供浏览器仪表盘

**技术亮点**: 纯 C 实现，每个模型家族对应一个文件；采用分层专家存储架构（GPU 显存 → RAM → NVMe 流式读取）；支持 CPU、Vulkan（任意 GPU）和 CUDA（NVIDIA）多种后端；最低仅需 8 GB 内存和 22 GB 磁盘空间即可运行最小模型。

---
## 5. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 311,514
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: Matt Pocock 分享的日常 AI 编码代理技能集合，强调真实工程实践而非“氛围编程”，设计小巧、可组合、可自由改造。

**核心功能**:
- `/grill-me` 与 `/grill-with-docs`：通过与代理的“拷问式”对话，在动手前对齐需求，减少沟通偏差
- `/triage`：结合自定义标签对工单进行分诊管理
- `/setup-matt-pocock-skills`：每个仓库运行一次，配置问题追踪器、分诊标签和文档保存位置
- 支持多代理平台安装：Claude Code、Codex、GitHub Copilot、Gemini CLI 及其他代理（如 Cursor、Windsurf、Amp 等）

**技术亮点**: 以 Shell 为主，技能以可编辑的 Markdown 文件组织；提供插件市场自动更新与 `npx skills` 手动管理两种安装方式；兼容任意模型，避免像 GSD、BMAD、Spec-Kit 那样接管流程而剥夺开发者控制权。

---
## 6. [p-e-w/heretic](https://github.com/p-e-w/heretic)
- **语言**: Python
- **Stars**: 38,832
- **简介**: Training-free language model modification: Remove censorship, suppress slop, reduce sycophancy, and more

### AI 总结
**简介**: Heretic 是一个无需训练即可修改语言模型行为的 Python 工具，让普通用户也能在个人硬件上移除模型审查、抑制废话、减少谄媚等。

**核心功能**:
- **移除审查/拒绝**（默认行为）：抑制模型的安全拒绝回复
- **减少废话（slop）**：通过 `config.noslop.toml` 配置
- **减少谄媚（sycophancy）**：通过 `config.nosyco.toml` 配置
- **调整幽默感**：通过 `config.nohumor.toml` 配置
- **改变情感对齐**：通过 `config.emotions.toml` 配置
- 支持将处理后的模型保存、上传至 Hugging Face、对话测试或运行标准基准测试

**技术亮点**:
- 无需昂贵训练，基于对比示例提示和匹配评分器，使用数学技术引导模型行为
- 支持通过 bitsandbytes 进行 4-bit 即时量化以降低显存需求
- 兼容多数稠密模型、部分多模态模型、多种 MoE 架构及现代混合模型
- 启动时自动基准测试以确定最优批大小（RTX 3090 处理 Qwen3-4B 约 30-40 分钟）
- 社区已发布数千个 Heretic 模型，在 MMLU、GSM8K 等基准上表现优于同类 abliteration 工具
- 要求 Python 3.10+ 和 PyTorch 2.6+，通过 `pip install -U heretic-llm` 安装，命令行即可使用

---
## 7. [spotify/portal-ai-plugins](https://github.com/spotify/portal-ai-plugins)
- **语言**: TypeScript
- **Stars**: 3,054
- **简介**: 

### AI 总结
**简介**: Spotify 官方推出的 TypeScript 插件，将 Spotify Portal 集成到 Claude Code、Codex、Cursor 和 pi 等编码代理环境中，提供围绕 Portal CLI 的聚焦工作流。

**核心功能**:
- **环境配置**：为当前编码代理环境设置 Portal CLI 认证（`setup`），并提供只读就绪诊断（`doctor`）
- **目录与文档检索**：通过自然语言查询搜索软件目录和技术文档（`search`）
- **服务简报**：生成包含归属、健康状态、事件和文档信息的简明服务简报（`service`）
- **安全调用动作**：发现、预览并安全调用 Portal 动作，内置帮助、dry-run 和确认保护（`actions`）
- **Fleetshift 管理**：创建、运行、检查、排查 shift，完成后开 PR，并支持按请求停止运行
- **反馈提交**：向 Portal 团队提交关于 CLI 的反馈（`feedback`）
- **shunt 插件（仅 Claude Code）**：将 I/O 密集型任务（批量文件读取、样板代码生成）路由到 AiKA 上更廉价的 worker 模型，以节省 token

**技术亮点**: 基于 TypeScript 开发，通过 `npx @spotify/portal-cli` 调用上游 CLI；采用插件市场（marketplace）分发模式，支持多代理平台安装；工作流设计强调只读诊断、dry-run 预览与人工确认等安全机制。

---
## 8. [floci-io/floci](https://github.com/floci-io/floci)
- **语言**: Java
- **Stars**: 28,837
- **简介**: Light, fluffy, and always free - The AWS Local Emulator alternative

### AI 总结
**简介**: Floci 是一个免费开源、轻量级的本地 AWS 模拟器，用于开发、测试和 CI 环境，无需云账号、认证令牌或付费功能门槛。

**核心功能**:
- 在本地提供 AWS 形态的服务，所有服务统一通过 `http://localhost:4566` 访问，兼容 AWS SDK、CLI、Terraform、CDK、OpenTofu 及测试套件
- 支持任意已发布的 AWS 区域及分区，凭据可使用任意非空值（除非显式启用更严格的服务级认证检查）
- 提供官方 CLI（`floci start` / `floci env`）快速启动并导出本地 AWS 环境变量，同时支持 Docker Compose 部署
- 附带浏览器 Web 控制台（`http://localhost:4566/_floci/ui`），可查看本地模拟器中的资源
- 可作为 LocalStack 的直接替代品，仅需替换镜像即可迁移
- 提供 Testcontainers 集成支持
- 各版本发布附带适用于 Linux、macOS 和 Windows 的独立 `floci-aws` 原生二进制文件（无需 Docker）

**技术亮点**:
- 使用 Java 开发，以 Docker 镜像（`floci/floci`）形式分发，采用 MIT 许可证
- 属于 Floci 多云模拟器家族（AWS/Azure/GCP/OCI），各成员使用不同端口（AWS 为 4566）
- 设计理念为"轻量、免费、无门槛"，强调开箱即用的本地开发体验

---
## 9. [Usagi-org/ai-goofish-monitor](https://github.com/Usagi-org/ai-goofish-monitor)
- **语言**: Python
- **Stars**: 16,461
- **简介**: 基于 Playwright 和AI实现的闲鱼多任务实时/定时监控与智能分析系统，配备了功能完善的后台管理UI。帮助用户从闲鱼海量商品中，找到心仪产品。

### AI 总结
**简介**: 基于 Playwright 与 AI 的闲鱼多任务实时/定时监控系统，配备完整 Web 管理界面，帮助用户从海量商品中高效筛选心仪产品。

**核心功能**:
- Web 可视化管理：任务管理、账号管理、AI 标准编辑、运行日志、结果浏览
- AI 驱动：支持自然语言创建任务，多模态模型深度分析商品
- 多任务并发：独立配置关键词、价格、筛选条件和 AI Prompt
- 高级筛选：包邮、发布时间范围、省/市/区三级区域筛选
- 即时通知：支持 ntfy.sh、企业微信、Bark、Telegram、Webhook 等多渠道
- 定时调度：支持 Cron 配置周期性任务
- 账号与代理轮换：多账号管理、任务绑定账号、代理池轮换与失败重试
- Docker 一键容器化部署

**技术亮点**:
- 技术栈：Python + FastAPI 后端、Playwright 爬虫、Vite 前端、SQLite 主存储
- 架构特点：AI 任务创建采用后台异步 job 流程（202 + 轮询进度）；SQLite 自动建库建表并兼容导入旧数据（config.json/jsonl/price_history）；Docker 镜像内置 Chromium，无需宿主机额外安装浏览器；支持 WebSocket 实时通信与多渠道通知集成

---
## 10. [anomalyco/hex](https://github.com/anomalyco/hex)
- **语言**: Rust
- **Stars**: 4,617
- **简介**: Local voice dictation for mac, windows and linux

### AI 总结
**简介**: Hex 是一款用 Rust 编写的跨平台（macOS、Windows、Linux）本地语音听写工具，按住快捷键说话即可将语音转写并粘贴到当前应用。

**核心功能**:
- 按住快捷键说话，松开后自动将转写文本粘贴到当前应用
- 全程本地转写，首次运行需下载语音模型，之后数据不离开本机
- 提供 Labs 实验性功能入口（位于侧边栏底部）
- 覆盖 macOS（Apple Silicon）、Windows（x64/ARM64）、Linux（x86_64/ARM64）多平台，提供 DMG、Installer、deb、rpm、可执行文件等安装包
- 支持 Homebrew、AUR、Linux 安装脚本和 Nix 等多种安装方式
- 提供 Stable 稳定版与 Dev 开发版双通道下载

**技术亮点**: 使用 Rust 开发；采用本地设备端语音转写架构，强调隐私与离线可用；不接受 Pull Request，通过 Issue 反馈问题。

---
