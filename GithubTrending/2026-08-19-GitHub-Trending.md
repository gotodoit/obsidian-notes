---
tags:
  - github-trending
  - daily
date: 2026-08-19
created: 2026-08-19T01:55:44.469Z
---

# 2026-08-19 GitHub Trending Top 10

## 1. [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)
- **语言**: Python
- **Stars**: 108,645
- **简介**: 利用 AI 大模型和自动化工作流，根据主题或关键词一键生成高清短视频。Generate HD short videos from a topic or keyword with an automated AI workflow.

### AI 总结
**简介**: MoneyPrinterTurbo 是一款一站式 AI 短视频生成工具，只需提供主题或关键词，即可自动完成脚本撰写、素材匹配、字幕生成、背景音乐合成，最终输出高清短视频。

**核心功能**:
- 输入主题或关键词，自动生成视频脚本
- 智能匹配视频素材、字幕和背景音乐
- 一键合成并输出高清短视频
- 提供 WebUI 和 API 两种交互界面

**技术亮点**: 基于 Python 3.11+ 开发，支持 Windows、macOS、Linux 多平台，集成 AI 大模型（如 Kimi K3）驱动内容创作与素材关键词提炼。

---
## 2. [chaitanyagiri/munder-difflin](https://github.com/chaitanyagiri/munder-difflin)
- **语言**: TypeScript
- **Stars**: 2,074
- **简介**: local multi-agent harness

### AI 总结
**简介**: Munder Difflin 是一个将终端 AI 编码 CLI（如 Claude Code、Codex、Grok 等）包装为多智能体协作系统的桌面应用，让多个 AI 代理像办公室员工一样协同工作。

**核心功能**:
- **多代理编排**: 将 `claude`、`codex`、`grok`、`kimi`、`qwen`、`copilot` 等终端 CLI 包装为独立代理，组成自我协调的团队
- **代理可视化**: 代理以 Pixi.js 渲染的 2D 办公室形象呈现，工作时走动到工位，消息传递时信封在桌面间飞行
- **代理记忆系统**: 基于 Markdown 的记忆层配合语义检索索引，代理可跨会话记忆并以毫秒级速度回忆
- **代理间通信**: 代理可读取记忆、处理邮箱消息，由路由器在收件箱间传递消息
- **中央协调机制**: 通过 GOD 代理（Michael）进行任务分配、路由和升级，用户只需与 Michael 对话即可管理整个团队
- **跨平台支持**: 支持 macOS、Windows、Linux，兼容自带 API 密钥和本地 LLM

**技术亮点**: 采用 Electron + React + TypeScript 构建桌面应用，使用 Pixi.js 进行 2D 可视化渲染，xterm.js + node-pty 实现真实的伪终端进程管理，支持多种主流 AI 编码 CLI 的无缝集成。

---
## 3. [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory)
- **语言**: Rust
- **Stars**: 2,760
- **简介**: Solution for long term memory for agent coding CLIs and to facilitate handoff between different agent vendors

### AI 总结
**简介**: ai-memory 是一个为 AI 编码代理提供长期记忆的 Rust 工具，支持在不同代理工具之间无缝切换和任务交接，避免重复解释架构或已探索的方案。

**核心功能**:
- **跨代理记忆持久化**: 在 Claude Code、Codex、OpenCode、Gemini CLI 等主流代理工具间共享会话上下文，实现任务中途切换后继续执行
- **生命周期钩子集成**: 通过 MCP 配置和生命周期钩子（SessionStart/Stop 等）自动捕获和注入上下文
- **会话最终化**: 提供 `finalize-session` 命令生成总结和交接文档
- **托管工作流**: `ai-memory run` 支持跨工具的无缝会话恢复（支持 Claude Code、Codex、OpenCode、Pi、Crush 等 12+ 工具）
- **捕获排除机制**: 原生命令支持排除敏感或无关内容，确保记忆质量
- **多平台支持**: Linux（Docker/Arch 包）、macOS（原生二进制）、Windows（WSL2/实验性原生支持）

**技术亮点**: 采用 Rust 编写，通过 MCP（Model Context Protocol）标准与各代理工具集成；支持会话感知的自动作用域隔离（stdio 桥接）；提供 TypeScript 插件生成（如 OpenCode、Pi、OMP）以增强原生集成；跨平台发布多架构二进制（amd64/arm64）。

---
## 4. [volcengine/OpenViking](https://github.com/volcengine/OpenViking)
- **语言**: Python
- **Stars**: 29,439
- **简介**: Self-evolving Context Database for AI Agents. Unify Agent Memory, Knowledge RAG and Skills.

### AI 总结
**简介**: OpenViking 是一个面向 AI Agent 的开源上下文数据库，将记忆、资源和技能统一为 `viking://` 虚拟文件系统，让 Agent 像操作文件一样管理自身上下文。

**核心功能**:
- **统一上下文文件系统**: 记忆、资源和技能均以 `viking://` URI 呈现，Agent 可通过 `ls`、`tree`、`find` 等命令确定性定位和操作上下文
- **三层分级加载（L0/L1/L2）**: 内容写入时自动生成摘要、概览和详情三个层级，按任务需求按需加载，显著降低 Token 消耗
- **目录递归检索**: 向量搜索先定位最高得分目录，再逐层深入，保证检索结果携带完整上下文
- **可观测检索轨迹**: 每次查询保留目录浏览路径，结果异常时可精确定位问题来源
- **会话自动沉淀为记忆**: 会话提交后异步提取用户偏好和 Agent 经验，转化为长期记忆

**技术亮点**: 基于 Python 实现，采用三级上下文分层架构（抽象层/概览层/详情层）、目录式递归检索机制、虚拟文件系统协议（`viking://`）设计，配套提供 OpenViking Studio 在线演示平台，遵循 AGPLv3 开源协议。

---
## 5. [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills)
- **语言**: Python
- **Stars**: 29,234
- **简介**: 817 structured cybersecurity skills for AI agents · Mapped to 6 frameworks: MITRE ATT&CK, NIST CSF 2.0, MITRE ATLAS, D3FEND, NIST AI RMF & MITRE F3 (Fight Fraud) · agentskills.io standard · Works with Claude Code, GitHub Copilot, Codex CLI, Cursor, Gemini CLI & 20+ platforms · 29 security domains · Apache 2.0

### AI 总结
**简介**: 一个面向 AI 代理的开源网络安全技能库，包含 817 个结构化技能，覆盖 29 个安全领域，并映射到 6 个主流安全框架。

**核心功能**:
- **817 个生产级网络安全技能**: 涵盖 29 个安全领域（如取证、红队、云安全、AI 安全等），每个技能遵循 agentskills.io 开放标准
- **6 大框架映射**: MITRE ATT&CK (805 个技能)、NIST CSF 2.0 (804)、MITRE D3FEND (139)、NIST AI RMF (97)、MITRE F3 (94)、MITRE ATLAS (93)，每个技能按类型映射到相关框架
- **跨平台兼容**: 支持 Claude Code、GitHub Copilot、Codex CLI、Cursor、Gemini CLI 等 26+ AI 平台
- **即插即用**: 克隆仓库并指向 AI 代理即可获得专家级安全分析指导（如内存取证、检测规则编写、云安全事件范围界定等）

**技术亮点**:
- 基于 agentskills.io 开放标准构建，Apache 2.0 开源协议
- 采用框架感知的映射策略（如取证技能映射 ATT&CK + CSF，AI 安全技能额外映射 ATLAS + AI RMF）
- 包含防御性（D3FEND）、攻击性（ATT&CK/ATLAS）及反欺诈（F3）多维度覆盖
- 社区驱动项目，欢迎 PR 贡献

---
## 6. [public-apis/public-apis](https://github.com/public-apis/public-apis)
- **语言**: Python
- **Stars**: 464,627
- **简介**: A collective list of free APIs

### AI 总结
**简介**: public-apis 是一个由社区维护的免费公共 API 集合列表，涵盖众多领域，供开发者在其产品中自由使用。

**核心功能**:
- 收录了大量免费公共 API，覆盖 IP 定位、股票数据、天气信息、航班查询、邮件验证、搜索抓取等多个领域
- 由社区成员和 APILayer 团队共同人工筛选和维护，确保 API 质量
- 提供 APILayer 统一套件，支持通过一个账户、一个仪表盘和一个 API 密钥集成多个生产级 REST API
- 提供 Postman 集合，方便开发者快速测试和集成 API
- 设有 Discord 服务器，供开发者获取更新、提问和社区交流

**技术亮点**: 项目采用 Python 编写，以 Markdown 表格形式组织 API 列表，结构清晰易检索；支持通过 APILayer 平台实现多 API 统一认证和管理，并提供 Postman 集成便于快速上手。

---
## 7. [basecamp/omarchy](https://github.com/basecamp/omarchy)
- **语言**: Shell
- **Stars**: 26,451
- **简介**: Beautiful, Modern & Opinionated Linux

### AI 总结
**简介**: Omarchy 是由 DHH 打造的一款美观、现代且高度个性化的 Linux 发行版。

**核心功能**:
- 提供开箱即用的现代化桌面体验，注重视觉美观与整体设计感
- 采用“有主见”（Opinionated）的默认配置，减少用户自定义负担，专注高效使用
- 基于社区驱动，遵循 MIT 开源协议，免费使用与修改

**技术亮点**: 基于 Shell 脚本构建，强调简洁配置与快速部署，适合追求一致性与美观的 Linux 用户。

---
## 8. [agalwood/Motrix](https://github.com/agalwood/Motrix)
- **语言**: TypeScript
- **Stars**: 53,705
- **简介**: A full-featured download manager.

### AI 总结
**简介**: Motrix 是一款功能全面的现代化下载管理器，支持 HTTP、FTP、BitTorrent 和磁力链接等多种下载协议，以简洁易用为设计核心。

**核心功能**:
- 支持 BitTorrent 下载，包含文件级选择和磁力链接支持
- 内置 tracker 列表管理，支持自动更新和健康检查
- 支持 UPnP 和 NAT-PMP 端口映射，优化 P2P 连接
- 提供上传/下载限速功能，支持多套限速配置
- SQLite 会话持久化，重启后可恢复下载任务
- 可自定义仪表盘，展示传输统计和实时活动
- 系统通知和应用内通知中心，下载完成即时提醒
- QuickJS 插件沙箱机制，支持细粒度权限控制和应用内插件市场
- Chrome/Firefox 浏览器扩展，一键接管浏览器下载
- 官方命令行客户端 `@motrix/cli`，支持日常终端使用和 AI 代理
- Docker 就绪的无头服务器模式，支持远程 CLI 和设备码配对
- 系统托盘集成和开机自启动
- 支持 `motrix://`、`magnet:` 协议和 `.torrent` 文件关联

**技术亮点**: 基于 Electron、React 和 TypeScript 重构，采用 UI 与下载核心分离的架构设计。核心通信基于开放的 MDXP 协议（基于 JSON-RPC 2.0），支持桌面应用和无头服务器两种运行模式，插件运行在隔离的沙箱环境中。

---
## 9. [NawfalMotii79/PLFM_RADAR](https://github.com/NawfalMotii79/PLFM_RADAR)
- **语言**: PLSQL
- **Stars**: 24,332
- **简介**: Open-source, low-cost 10.5 GHz PLFM phased array RADAR system

### AI 总结
**简介**: AERIS-10 是一个开源的、低成本的 10.5 GHz 相控阵雷达系统，采用脉冲线性调频（LFM）调制，旨在让研究人员、无人机开发者和 SDR 爱好者能够低成本地探索相控阵雷达技术。

**核心功能**:
- **双版本可选**: AERIS-10N（Nexus）3km 探测距离，8x16 贴片天线阵列；AERIS-10E（Extended）20km 探测距离，32x16 介质填充缝隙波导阵列
- **全电子波束控制**: 俯仰和方位角均支持 ±45° 电子扫描
- **先进信号处理**: 板载 FPGA 处理脉冲压缩、多普勒 FFT、MTI 和 CFAR
- **Python GUI**: 用户友好的图形界面，集成地图显示
- **GPS/IMU 集成**: 实时位置和姿态校正
- **模块化设计**: 独立的电源管理、频率合成和射频板卡

**技术亮点**: 硬件采用 CERN-OHL-P 许可，软件采用 MIT 许可；核心硬件包括 AD9523-1 时钟发生器、ADF4382 频率合成器、ADAR1000 4 通道移相器、ADTR1107 前端芯片、XC7A50T FPGA 和 STM32F746 微控制器；FPGA 负责完整的雷达信号处理链（chirp 生成、I/Q 下变频、脉冲压缩、多普勒处理等），STM32 负责上电时序和系统配置，支持混合自动增益控制（AGC）跨层协同。

---
## 10. [jundot/omlx](https://github.com/jundot/omlx)
- **语言**: Python
- **Stars**: 19,427
- **简介**: LLM inference server with continuous batching & SSD caching for Apple Silicon — managed from the macOS menu bar

### AI 总结
**简介**: oMLX 是一款专为 Apple Silicon Mac 打造的 LLM 推理服务器，支持连续批处理与 SSD 分层 KV 缓存，并可通过 macOS 菜单栏直接管理。

**核心功能**:
- 菜单栏管理：通过 macOS 菜单栏应用即可启动/停止服务器、下载模型、配置上下文长度，无需命令行操作
- 连续批处理（Continuous Batching）：提升 GPU 利用率与并发请求吞吐量
- 分层 KV 缓存（Tiered KV Caching）：热内存层 + 冷 SSD 层持久化缓存，对话中途变更上下文时历史缓存仍可复用，适配 Claude Code 等编码工具
- 多模型管理：支持常驻内存模型与按需自动换入重模型，灵活设置上下文限制
- CLI 与 MCP 支持：提供轻量 `~/.omlx/bin/omlx` 命令，可集成 Apple Shortcuts；可选安装 MCP（Model Context Protocol）支持
- 多语言文档：提供英文、中文、韩文、日文版本

**技术亮点**: 基于 Python 3.11-3.13，要求 macOS 15+ 与 Apple Silicon（M1-M4）；内置针对 GLM-5.2 / MiniMax M3 / Qwen3.5 的原生自定义 Metal 内核（可选编译），GLM-5.2 融合 DSA 预填充速度提升约 30 倍（M3 Ultra 实测 845 vs ~29 tok/s）；支持 Homebrew 安装与后台服务自动重启；提供预编译 DMG 应用含自动更新。

---
