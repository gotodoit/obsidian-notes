---
tags:
  - github-trending
  - daily
date: 2026-07-28
created: 2026-07-28T01:55:43.405Z
---

# 2026-07-28 GitHub Trending Top 10

## 1. [permissionlesstech/bitchat](https://github.com/permissionlesstech/bitchat)
- **语言**: Swift
- **Stars**: 32,321
- **简介**: bluetooth mesh chat, IRC vibes

### AI 总结
**简介**: 一个去中心化的点对点聊天应用，结合蓝牙Mesh网络（离线）与Nostr协议（全球）双传输架构，无需账户、手机号或中央服务器。

**核心功能**:
- **双传输架构**: 支持蓝牙Mesh离线通信和Nostr协议全球消息传递，智能切换。
- **基于位置频道**: 通过地理哈希坐标创建聊天室（如街区、城市、国家级别）。
- **私密消息端到端加密**: 蓝牙Mesh使用Noise协议，Nostr使用BitChat专有加密信封（XChaCha20-Poly1305）。
- **IRC风格命令**: 支持`/slap`、`/msg`、`/who`等传统命令。
- **紧急擦除功能**: 三击快速清除所有数据。
- **性能优化**: LZ4消息压缩、自适应电池模式、优化网络。

**技术亮点**: Swift原生开发，支持iOS和macOS；蓝牙Mesh采用多跳中继（最多7跳）和二进制协议；Nostr集成290+全球中继网络，使用临时密钥和地理哈希频道。

---
## 2. [amnezia-vpn/amnezia-client](https://github.com/amnezia-vpn/amnezia-client)
- **语言**: C++
- **Stars**: 13,850
- **简介**: Amnezia VPN Client (Desktop+Mobile)

### AI 总结
**简介**: Amnezia VPN 是一款开源的 VPN 客户端，支持桌面和移动端，核心特色是允许用户在自己的服务器上快速部署 VPN 服务。

**核心功能**:
- 一键部署：输入服务器 IP、SSH 登录名和密码，自动安装 VPN Docker 容器并连接
- 支持多种经典 VPN 协议：OpenVPN、WireGuard、IKEv2
- 支持流量混淆协议：OpenVPN over Cloak、Shadowsocks、AmneziaWG、XRay
- 支持分流功能：可指定网站或应用（仅限 Android 和桌面端）走 VPN
- 跨平台：支持 Windows、macOS、Linux、Android、iOS

**技术亮点**: 基于 C++ 开发，整合 OpenSSL、OpenVPN、Qt、WireGuard 等多个开源项目，采用 Docker 容器化部署方案。

---
## 3. [moeru-ai/airi](https://github.com/moeru-ai/airi)
- **语言**: TypeScript
- **Stars**: 44,073
- **简介**: 💖🧸 Self hosted, you-owned Grok Companion, a container of souls of waifu, cyber livings to bring them into our worlds, wishing to achieve Neuro-sama's altitude. Capable of realtime voice chat, Minecraft, Factorio playing. Web / macOS / Windows supported.

### AI 总结
**简介**: Project AIRI 是一个自托管的 AI 伴侣项目，旨在复现 Neuro-sama 的功能，让用户拥有属于自己的 AI 虚拟角色（waifu），支持实时语音聊天、玩 Minecraft 和 Factorio 等游戏，可在 Web、macOS 和 Windows 上运行。

**核心功能**:
- 实时语音聊天
- 支持 Minecraft 和 Factorio 游戏互动
- 自托管，用户拥有完全控制权
- 跨平台支持（Web / macOS / Windows）

**技术亮点**: 使用 TypeScript 开发，提供预编译的桌面安装包（Windows、macOS、Linux），支持多语言文档（中文、日文、俄文等），社区活跃（Discord、Telegram、QQ 群）。

---
## 4. [opengeos/GeoLibre](https://github.com/opengeos/GeoLibre)
- **语言**: TypeScript
- **Stars**: 2,725
- **简介**: A lightweight, cloud-native GIS platform for visualizing, exploring, and analyzing geospatial data. It runs in the web browser, on the desktop, on mobile, and inside Jupyter notebooks.

### AI 总结
**简介**: 一个轻量级、云原生、免费开源的GIS平台，支持在Web、桌面、移动端和Jupyter Notebook中可视化、探索和分析地理空间数据，同时保障数据本地化和隐私。

**核心功能**:
- 支持3D Tiles渲染、建筑三维挤出（按年份着色）及地铁线路叠加
- 内置行星底图（月球、火星等），自动适配不同天体的椭球体参数
- 提供时间滑块动画（如建筑按年份动态生成）
- 自动生成图层图例

**技术亮点**: 基于Tauri v2、React、TypeScript、MapLibre GL JS、DuckDB-WASM Spatial和deck.gl构建，同一代码库可编译为桌面应用（Windows/macOS/Linux）、Android应用及响应式Web应用。

---
## 5. [yorukot/superfile](https://github.com/yorukot/superfile)
- **语言**: Go
- **Stars**: 20,923
- **简介**: Pretty fancy and modern terminal file manager

### AI 总结
**简介**: superfile 是一款用 Go 编写的现代化终端文件管理器，界面美观且功能丰富。

**核心功能**:
- 提供直观的终端文件管理界面，支持常见文件操作（如复制、移动、删除等）
- 支持插件扩展和自定义主题
- 跨平台支持（Linux、macOS、Windows），并提供一键安装脚本
- 内置自动更新检查功能，可配置关闭

**技术亮点**: 使用 Go 语言开发，支持 Homebrew、Scoop、Winget 等多种包管理器安装，提供详细的快捷键自定义配置（含 Vim 模式）。

---
## 6. [NanmiCoder/MediaCrawler](https://github.com/NanmiCoder/MediaCrawler)
- **语言**: Python
- **Stars**: 58,247
- **简介**: 小红书笔记 | 评论爬虫、抖音视频 | 评论爬虫、快手视频 | 评论爬虫、B 站视频 ｜ 评论爬虫、微博帖子 ｜ 评论爬虫、百度贴吧帖子 ｜ 百度贴吧评论回复爬虫 | 知乎问答文章｜评论爬虫

### AI 总结
**简介**: 一款基于 Playwright 浏览器自动化的多平台自媒体数据采集工具，支持小红书、抖音、快手、B站、微博、贴吧、知乎等主流平台的公开信息抓取，无需逆向复杂的加密算法。

**核心功能**:
- 支持关键词搜索、指定帖子ID爬取、二级评论、指定创作者主页数据采集
- 支持登录态缓存、IP代理池、生成评论词云图
- 支持小红书、抖音、快手、B站、微博、贴吧、知乎等7个平台
- 提供Pro版本，支持断点续爬、多账号+IP代理池、去除Playwright依赖等高级功能

**技术亮点**:
- 基于Playwright浏览器自动化框架，利用JS表达式获取签名参数，无需逆向加密算法
- 默认使用CDP模式连接用户已有Chrome浏览器，复用登录态降低风控风险
- 采用uv包管理工具，依赖解析准确，支持多语言文档（中/英/西）

---
## 7. [pbakaus/impeccable](https://github.com/pbakaus/impeccable)
- **语言**: JavaScript
- **Stars**: 51,588
- **简介**: The design language that makes your AI harness better at design.

### AI 总结
**简介**: Impeccable 是一个为 AI 编码助手提供设计指导的工具，包含 1 个技能、23 个命令、实时浏览器迭代和 60 条确定性检测规则，用于提升 AI 生成前端设计的质量。

**核心功能**:
- **一键初始化**: 通过 `npx impeccable install` 和 `/impeccable init` 快速设置项目，生成 `PRODUCT.md` 和 `DESIGN.md` 设计上下文。
- **23 个设计命令**: 包括 `craft`、`polish`、`audit`、`critique`、`bolder`、`animate` 等，覆盖从 UX 规划到技术优化的全流程。
- **60 条确定性检测规则**: 无需 LLM 和 API 密钥即可运行，配合 LLM 审查检查，确保设计质量。
- **反模式指导**: 明确避免过度使用的字体、灰色文字、纯黑/灰、嵌套卡片和弹性缓动等常见问题。

**技术亮点**: 基于 JavaScript 实现，支持 CLI 和浏览器扩展，可集成到 Claude、Cursor、Codex、GitHub Copilot、Grok 等 AI 工具中，并提供实时浏览器迭代模式。

---
## 8. [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos)
- **语言**: Python
- **Stars**: 34,582
- **简介**: Kronos: A Foundation Model for the Language of Financial Markets

### AI 总结
**简介**: Kronos 是一个专为金融市场 K 线数据设计的首个开源基础模型，基于超过 45 个全球交易所的训练数据。

**核心功能**:
- 金融 K 线预测：支持对 BTC/USDT 等交易对进行未来 24 小时预测，并提供在线演示。
- 多模型选择：提供 Kronos-mini、small、base、large 等不同参数规模的预训练模型，适应多种计算需求。
- 微调脚本：已发布微调脚本，方便用户针对自有任务适配模型。

**技术亮点**: 采用两阶段框架：首先通过专用分词器将连续的多维 OHLCV 数据量化为层次化离散令牌，然后使用自回归 Transformer 进行预训练，以处理金融数据的高噪声特性。

---
## 9. [alibaba/open-code-review](https://github.com/alibaba/open-code-review)
- **语言**: Go
- **Stars**: 14,869
- **简介**: Open-source & free — Battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level comments, built-in fine-tuned ruleset (NPE, thread-safety, XSS, SQL injection), OpenAI & Anthropic compatible.

### AI 总结
**简介**: 阿里巴巴开源的高性能代码审查工具，基于混合架构（确定性流水线+LLM Agent）提供精准的行级评论，已在阿里巴巴大规模生产环境中验证。

**核心功能**:
- **AI驱动代码审查**: 读取Git差异，通过支持工具调用的Agent发送变更文件至可配置LLM，生成结构化行级评论
- **多模式审查**: 支持PR diff审查（`ocr review`）和全文件审查（`ocr scan`），适用于陌生代码库或无显著差异的目录
- **内置精细规则集**: 预置NPE、线程安全、XSS、SQL注入等安全与质量规则
- **多Agent支持**: 兼容Claude Code、Codex、Cursor等主流AI Agent
- **跨平台支持**: 可在Windows、macOS、Linux上运行

**技术亮点**:
- 使用Go语言开发，性能高效
- 混合架构：确定性流水线处理基础规则，LLM Agent处理复杂逻辑
- 在基准测试中，相比通用Agent（如Claude Code），使用相同模型时精度（Precision）和F1分数显著更高，且仅消耗约1/9的token，审查速度更快
- 基于50个热门开源仓库、200个真实PR和10种编程语言的基准测试，由80+资深工程师交叉验证

---
## 10. [jenkinsci/jenkins](https://github.com/jenkinsci/jenkins)
- **语言**: Java
- **Stars**: 25,899
- **简介**: Jenkins automation server

### AI 总结
**简介**: Jenkins 是领先的开源自动化服务器，基于 Java 构建，拥有超过 2000 个插件，支持自动化开发工作流中的各类任务。

**核心功能**:
- 自动化构建项目
- 运行测试以尽早发现缺陷
- 静态代码分析
- 自动化部署

**技术亮点**: 采用 Java 开发，提供双版本发布线（Weekly 和 LTS），支持 WAR 文件、Docker 镜像、原生包及安装器等多种分发形式。

---
