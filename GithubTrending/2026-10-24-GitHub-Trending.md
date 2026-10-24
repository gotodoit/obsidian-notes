---
tags:
  - github-trending
  - daily
date: 2026-10-24
created: 2026-10-24T01:55:42.719Z
---

# 2026-10-24 GitHub Trending Top 8

## 1. [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill)
- **语言**: JavaScript
- **Stars**: 42,213
- **简介**: A coding-agent skill for multi-phase security audits with independently verified, machine-readable findings

### AI 总结
**简介**: Cloudflare 开源的安全审计技能，将编码 Agent 转化为多阶段安全审计器，产出经过独立验证、机器可读的审计结论。

**核心功能**:
- 六阶段结构化审计流程：侦察建图 → 覆盖度驱动的漏洞狩猎 → 候选验证（由全新验证者尝试证伪）→ 结构化输出 → 独立记录复核 → 目标中立报告生成
- 按目标类型提供多套攻击类提示词库，覆盖内存安全/二进制、AI/LLM、Web 协议与认证、客户端、供应链、云与部署、RPC/消息、资源耗尽、数据隔离、桌面/移动与本地 IPC 等场景
- 产出 `findings.json`（含 `confirmed` / `needs_validation` / `rejected` 三种判定）、`coverage-ledger.json`，并派生 `REPORT.md`、`FINDINGS-DETAIL.md`、`NEEDS-VALIDATION.md`
- 支持对同一仓库多次增量审计：复用历史账本与结论，针对缺口、变更源码和遗留未决项继续推进

**技术亮点**: 基于 JavaScript，提供零依赖的 `validate-findings.cjs` 与 `validate-coverage-ledger.cjs` 校验器及配套测试，配合 `report-schema.json` 保证输出可机器校验；通过隔离 Agent 分工与“新验证者复核”机制降低误报，是 Cloudflare 漏洞发现体系（vulnerability harness）的单仓库雏形。

---
## 2. [php/php-src](https://github.com/php/php-src)
- **语言**: C
- **Stars**: 41,573
- **简介**: The PHP Interpreter

### AI 总结
**简介**: PHP 官方解释器源码仓库，一个以 C 语言实现、面向 Web 开发的通用脚本语言。

**核心功能**:
- 提供 PHP 语言的完整解释器实现（词法/语法解析、编译与执行）
- 内置大量核心扩展，并支持通过 PIE/PECL 安装第三方扩展
- 附带完整的测试套件（`make test`），支持并行测试与按目录定向测试
- 支持从源码构建（autoconf/bison/re2c），并提供 Windows 预编译二进制

**技术亮点**:
- 使用 C 语言开发，构建流程基于 autoconf、bison、re2c
- 采用 Modified BSD（BSD-3-Clause）许可证
- 集成 GitHub Actions 持续测试与 OSS-Fuzz 模糊测试
- 新特性需经 RFC 流程评审，贡献通过 Fork + Pull Request 方式合并

---
## 3. [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)
- **语言**: Python
- **Stars**: 32,247
- **简介**: Open source repository of plugins primarily intended for knowledge workers to use in Claude Cowork

### AI 总结
**简介**: Anthropic 开源的 11 个知识工作插件合集，面向 Claude Cowork（兼容 Claude Code），将 Claude 定制为特定岗位的专业助手。

**核心功能**:
- 覆盖 11 个职能领域：生产力、销售、客户支持、产品管理、营销、法务、财务、数据、企业搜索、生物研究及插件管理
- 每个插件打包专属技能（Skills）、连接器（Connectors）、斜杠命令（Slash Commands）和子代理（Sub-agents）
- 通过 MCP 服务器连接 Slack、Notion、Jira、HubSpot、Snowflake、Microsoft 365 等外部工具
- 支持从 Cowork 市场一键安装，或在 Claude Code 中通过命令行安装（如 `claude plugin install sales@knowledge-work-plugins`）
- 提供插件管理插件，便于按企业自身工具、术语和流程定制插件

**技术亮点**:
- 基于 Python 开发，统一插件目录结构（`plugin.json` 清单、`.mcp.json` 工具连接、`commands/`、`skills/`）
- 技能自动触发、命令显式调用，全部组件文件化，便于扩展与定制
- 基于 Model Context Protocol（MCP）实现外部工具集成

---
## 4. [NVIDIA/OpenShell](https://github.com/NVIDIA/OpenShell)
- **语言**: Rust
- **Stars**: 18,829
- **简介**: OpenShell is the safe, private runtime for autonomous AI agents.

### AI 总结
**简介**: OpenShell 是 NVIDIA 推出的、面向自主 AI 智能体的安全私有运行时，用 Rust 编写，让智能体在受控沙箱内读写文件、安装软件包、调用 API 和使用凭证，同时不泄露数据、密钥或网络访问权限。

**核心功能**:
- **策略驱动的权限管控**：用户通过策略声明每个智能体可访问的文件、系统调用和网络端点，OpenShell 在运行时强制执行。
- **内核级隔离沙箱**：每个智能体运行在独立沙箱中，文件访问、系统调用和网络连接均受内核控制，网络连接离开沙箱前需通过策略检查。
- **凭证安全代理**：智能体无法接触真实凭证，OpenShell 仅在发往已批准端点的请求中注入凭证。
- **策略变更形式化验证**：策略变更生效前，用形式化验证标记出新增的高风险访问（如访问新主机、调用新 API），需人工审核。
- **CLI 与快速上手**：提供一键安装脚本和 `openshell sandbox create` 命令，快速创建沙箱。
- **Agent Skills**：通过 `npx skills add NVIDIA/OpenShell` 安装技能，让编码智能体学会驱动 OpenShell CLI、编写沙箱策略和调试网关。
- **Kubernetes 部署与扩展性**：支持用 Helm 部署网关，并提供中间件、拦截器和计算驱动等扩展接口。

**技术亮点**: 采用 Rust 实现；架构由网关（gateway）、监督器（supervisor）和沙箱（sandbox）组成；结合内核级强制隔离与形式化验证双重机制；支持 Linux、Apple Silicon 上的 macOS 以及 WSL 2（实验性），依赖 Docker、Podman 或主机虚拟化；提供 Python SDK（PyPI 包 `openshell`）和 Apache 2.0 开源许可。

---
## 5. [Renhuai123/ziwei-doushu](https://github.com/Renhuai123/ziwei-doushu)
- **语言**: TypeScript
- **Stars**: 6,890
- **简介**: 紫微斗数开源排盘引擎 — 基于倪海厦《天纪》体系，含完整排盘算法、四化系统、格局知识库、古籍原文数据

### AI 总结
**简介**: 基于倪海厦《天纪》体系的紫微斗数开源排盘引擎（TypeScript），包含完整排盘算法、四化系统、格局知识库与古籍原文数据。

**核心功能**:
- 完整排盘算法：真太阳时校正、中国夏令时处理、农历/公历互转、十二神煞、运限上下文等
- 四化系统与格局知识库，13 维解读数据集 v4.0（67.5 万张命盘 × 13 维，共 877 万段解读，解压后 56.6 GB，按年份分 77 个文件下载）
- 倪师《天纪·紫微斗数》原话语料 1848 条，每条可回放并标注出处
- 在线体验站点 metisziwei.com，开放排盘、AI 解读与命盘历史

**技术亮点**: TypeScript 实现，模块化设计（算法、流派配置、真太阳时、农历转换等独立模块）；配备 5 条排盘回归测试与 GitHub Actions CI；代码 MIT、数据集 CC BY 4.0、倪师原话 CC BY-NC-SA 4.0 的分层许可。

---
## 6. [SnailSploit/Claude-Red](https://github.com/SnailSploit/Claude-Red)
- **语言**: Python
- **Stars**: 8,520
- **简介**: claude-red is a curated library of offensive security skills designed for the Claude skills system. Each skill is a structured SKILL.md file that primes Claude with expert-level methodology for a specific attack surface — from SQLi to shellcode, EDR evasion to exploit development.

### AI 总结
**简介**: Claude-Red 是一个面向 Claude Skills 系统的进攻性安全技能库，通过结构化的 `SKILL.md` 文件让 Claude 化身具备专家级方法论的上下文感知红队操作员。

**核心功能**:
- 提供 78 个技能文件，覆盖 23 个安全领域，包括 Web 应用、无线、云、移动、IoT、AD、漏洞开发、模糊测试、后渗透等
- 技能按对话触发条件按需加载（如提及 SQL 注入即加载 `offensive-sqli`），未使用的技能不占用上下文
- 支持多种部署方式：Claude Skills 系统自动加载、Claude Code 系统提示注入、Claude.ai 手动粘贴，以及 `install.sh` 脚本按类别安装
- 每个技能包含特定攻击面的技术、工具、边缘情况和升级路径，适用于授权红队、漏洞赏金、安全研究、CTF 和操作员培训

**技术亮点**: 采用模块化 `SKILL.md` 结构（Markdown 驱动），支持稀疏检出按类别安装；技能索引按 23 个类别组织，涵盖从侦察到 C2 的完整攻击链；项目以 Python 编写，MIT 许可。

---
## 7. [OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM)
- **语言**: Python
- **Stars**: 40,279
- **简介**: VoxCPM2: Tokenizer-Free TTS for Multilingual Speech Generation, Creative Voice Design, and True-to-Life Cloning

### AI 总结
**简介**: VoxCPM2 是 OpenBMB 推出的无分词器（Tokenizer-Free）文本转语音系统，基于扩散自回归架构直接生成连续语音表示，支持多语言合成、创意音色设计与高保真声音克隆。

**核心功能**:
- **30 语言多语言合成**：无需语言标签，直接输入文本即可合成，另支持四川话、粤语、吴语等 9 种中文方言
- **Voice Design 音色设计**：仅凭自然语言描述（性别、年龄、语气、情感、语速等）即可创建全新音色，无需参考音频
- **可控声音克隆**：基于短参考音频克隆音色，并可选风格引导来调节情感、语速与表达
- **终极克隆**：同时提供参考音频及其转写文本，完整还原音色、节奏、情感与风格等细节
- **48kHz 高品质音频**：接受 16kHz 参考音频，经 AudioVAE V2 非对称编解码直接输出 48kHz 录音室级音频，内置超分辨率
- **上下文感知合成**：根据文本内容自动推断合适的韵律与表现力
- **实时流式推理**：RTF 低至约 0.3（RTX 4090），借助 Nano-vLLM 或 vLLM-Omni 可加速至约 0.13

**技术亮点**:
- 2B 参数模型，基于 **MiniCPM-4** 骨干网络，训练数据超 200 万小时多语言语音
- 采用**扩散自回归架构**，绕过离散分词，端到端生成连续语音表示
- **AudioVAE V2** 非对称编解码设计，实现低采样输入到 48kHz 输出的直接转换
- 支持 vLLM-Omni 官方多模态部署，具备 PagedAttention 与 OpenAI 兼容 API
- 权重与代码以 **Apache-2.0** 协议开源，可免费商用

---
## 8. [nodejs/node](https://github.com/nodejs/node)
- **语言**: JavaScript
- **Stars**: 122,888
- **简介**: Node.js JavaScript runtime ✨🐢🚀✨

### AI 总结
**简介**: Node.js 是一个开源、跨平台的 JavaScript 运行时环境，由 OpenJS Foundation 支持，采用开放治理模型。

**核心功能**:
- 提供跨平台 JavaScript 运行时，支持在服务器端运行 JavaScript
- 遵循语义化版本（SemVer），提供 Alpha、Current、LTS、Nightly 四种发布类型
- 提供二进制包、安装程序和源码压缩包的下载，并支持 SHA 校验和 PGP 签名验证
- 提供完整的 API 文档，并支持按版本查阅

**技术亮点**: 采用开放治理模型（含技术指导委员会 TSC），LTS 版本提供 30 个月长期支持（从首个 Current 发布起共 36 个月至生命周期结束），LTS 发布线使用按字母顺序排列的代号命名，并通过 CITGM 进行发布测试。

---
