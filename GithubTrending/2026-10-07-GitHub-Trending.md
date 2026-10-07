---
tags:
  - github-trending
  - daily
date: 2026-10-07
created: 2026-10-07T01:55:42.819Z
---

# 2026-10-07 GitHub Trending Top 10

## 1. [tester-army/e2e](https://github.com/tester-army/e2e)
- **语言**: TypeScript
- **Stars**: 6,380
- **简介**: Next generation e2e testing framework for web and mobile apps.

### AI 总结
**简介**: TesterArmy 推出的下一代端到端测试框架，用自然语言描述测试目标，由 AI Agent 驱动 Web 与移动应用完成测试。

**核心功能**:
- 自然语言测试：通过 `agent.act()` 描述操作目标，用 `agent.assert()` 验证结果，可与传统定位器断言混用
- 智能录制回放：Agent 步骤会记录动作，后续运行直接回放，仅在应用变化时才调用模型，无 Agent 步骤的测试完全不需要模型
- 多端支持：Web 端基于 Playwright 覆盖 Chromium/Firefox/WebKit，移动端支持 iOS/Android 模拟器与仿真器
- 灵活模型接入：支持自带订阅、API Key 或本地模型
- 快速初始化：`npx e2e init` 自动生成配置与示例测试

**技术亮点**:
- 基于 TypeScript 编写，模块化包结构（SDK/CLI、Web 引擎、移动引擎、GitHub 报告器、云端浏览器等）
- 提供 Vite、Next.js、Expo、SwiftUI 等框架的完整示例项目
- 内置 GitHub PR 评论报告器，便于 CI 集成
- 文档随 npm 包分发，支持编码 Agent 离线读取
- 采用 Apache-2.0 协议，当前处于 1.0 前的活跃开发阶段

---
## 2. [mattpocock/skills](https://github.com/mattpocock/skills)
- **语言**: Shell
- **Stars**: 278,189
- **简介**: Skills for Real Engineers. Straight from my .agents directory.

### AI 总结
**简介**: Matt Pocock 分享的日常真实工程开发用 AI Agent 技能集，强调小巧、可组合、可控，拒绝“氛围编程”。

**核心功能**:
- 提供多种工程技能，如 `/grill-me`（需求拷问）、`/grill-with-docs`（带文档的需求拷问）、`/triage`（工单分类）等
- 支持 Claude Code 插件安装和 `skills.sh` 可编辑文件安装两种方式
- 通过 `/setup-matt-pocock-skills` 一次性配置 issue tracker、标签和文档保存路径
- 兼容任意模型和多种编码 Agent（Claude Code、Codex 等）

**技术亮点**: 以 Shell 为主要语言，技能设计基于数十年工程经验，强调可组合与可修改；与 GSD、BMAD、Spec-Kit 等“接管流程”的方案不同，保留开发者控制权，便于定位和修复流程中的问题。

---
## 3. [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad)
- **语言**: Python
- **Stars**: 18,007
- **简介**: Give your agent CAD superpowers.

### AI 总结
**简介**: text-to-cad 是一个为 AI Agent 赋予 CAD 超能力的插件，让 Agent 能够在本地生成 3D 模型并完成制造相关任务。

**核心功能**:
- 生成 STEP、GLB、STL、3MF 等多种格式的 3D 模型
- 提供面向制造的设计检查（DFM）并生成工程图纸
- 对接主流 3D 打印、钣金和 CNC 加工服务
- 支持 Claude Code、Codex、Cursor、Gemini、Grok 等主流 Agent（通过插件或 skills 框架）

**技术亮点**:
- 基于 Python（3.11+），通过 uv 管理运行时
- 底层采用 build123d 0.11 与 Open CASCADE 7.9 构建 CAD 能力
- 提供本地 MCP 服务器（`cadgen mcp`）与浏览器 CAD Viewer 查看模型
- 发布为 PyPI 包 `cadgen`，采用 MIT 许可证

---
## 4. [boykopovar/AnyPS5](https://github.com/boykopovar/AnyPS5)
- **语言**: C++
- **Stars**: 6,644
- **简介**: Tool for automatic PS5 executables porting to Linux and Windows

### AI 总结
**简介**: AnyPS5 是一个用 C++ 编写的工具，可将 PS5 可执行文件自动移植到 Linux 和 Windows 平台，无需模拟器或独立运行时进程。

**核心功能**:
- 通过 relinker 将 PS5 可执行文件转换为目标系统的原生格式
- 提供系统 prx 库实现，支持动态链接
- 着色器重编译器可生成 SPIR-V（经 Spirv-Tools 验证）
- 支持 SDL 映射的游戏手柄（含摇杆和扳机），键鼠可通过 `anyps5-input.ini` 配置
- 维护已验证游戏兼容性列表

**技术亮点**:
- 采用原生移植方案而非模拟，直接动态链接系统库
- 着色器重编译为 SPIR-V，构建时可选用 Spirv-Tools 验证
- 遇到不支持状态严格抛出 `std::runtime_error` 并终止进程，行为明确
- 使用 GPLv2 许可证，定位为互操作性、研究与保存用途

---
## 5. [pbakaus/impeccable](https://github.com/pbakaus/impeccable)
- **语言**: JavaScript
- **Stars**: 77,720
- **简介**: The design language that makes your AI harness better at design.

### AI 总结
**简介**: Impeccable 是一套面向 AI 编程助手的前端设计指导技能，通过 1 个技能、24 个命令和 60 条确定性检测规则，帮助 AI 生成更高质量、避免模板化套路的界面设计。

**核心功能**:
- **一键安装与初始化**：通过 `npx impeccable install` 安装，`/impeccable init` 将产品核心信息（受众、目的、约束、语气等）记录到 `PRODUCT.md`，为后续命令提供持久上下文。
- **24 个设计命令**：覆盖设计全流程，如 `craft`（完整设计构建）、`shape`（编码前规划）、`critique`（UX 评审）、`audit`（技术质量检查）、`polish`（最终打磨）、`bolder`/`quieter`（调节设计强度）、`animate`（动效）、`colorize`（配色）等，并支持 `pin` 创建独立快捷命令。
- **60 条确定性检测规则**：CLI 和浏览器扩展可在无 LLM、无 API Key 的情况下运行确定性规则，并结合 LLM 进行纯评审检查。
- **实时浏览器迭代**：`live` 模式支持在浏览器中直接对元素进行视觉变体迭代，`generate` 可自动生成指定元素的变体。
- **反模式指导**：内置明确的设计避坑指南，如避免滥用 Inter/Arial 字体、彩色背景上的灰字、纯黑/灰、卡片嵌套卡片、过时的弹跳缓动等。

**技术亮点**:
- 以 JavaScript 实现，技能本身无需运行时，通过轻量启动器调用自包含的 Impeccable 引擎二进制文件（首次运行下载至 `~/.impeccable/bin/`）。
- 将产品事实（`PRODUCT.md`）与视觉方向（`DESIGN.md`）分离记录，避免将产品真相与表层视觉混淆。
- 确定性规则与 LLM 评审分离，前者无需 API Key 即可离线运行，兼顾效率与深度。

---
## 6. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 97,203
- **简介**: Persistent Context Across Sessions for Every Agent – Captures everything your agent does during sessions, compresses it with AI, and injects relevant context back into future sessions. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode + More

### AI 总结
生成总结时发生错误。

---
## 7. [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)
- **语言**: Python
- **Stars**: 54,433
- **简介**: A skill to stop your coding agent from burying the answer. ADHD-friendly output.

### AI 总结
**简介**: 一个让 AI 编码助手输出"先说结论、步骤清晰"的 ADHD 友好型技能插件，避免答案被冗长废话淹没。

**核心功能**:
- 强制 AI 助手先给出下一步行动，而非铺垫和寒暄
- 多步骤任务自动编号，列表不超过 5 项
- 每轮对话重申当前状态，结尾给出一个具体可执行的下一步
- 抑制无关发散内容，错误信息直接陈述
- 提供具体时间估计（分钟级），让进展可视化

**技术亮点**: 基于 Python 实现的 Claude 插件/skill，通过 `SKILL.md` 定义 10 条输出规则；支持 fork 后自定义规则并重新安装；灵感来源于《The Adult ADHD Tool Kit》，针对 LLM 响应方式做了适配。

---
## 8. [morluto/rea](https://github.com/morluto/rea)
- **语言**: TypeScript
- **Stars**: 9,615
- **简介**: Reverse engineer anything with agents, from app behavior down to native binaries.

### AI 总结
**简介**: REA 是一个基于 MCP 协议的逆向工程工具，让 AI Agent 能够从应用行为一直分析到原生二进制层面，帮助开发者理解任意软件功能的实现原理。

**核心功能**:
- 通过 MCP 连接 AI Agent，无需源码即可检查应用并解释功能实现方式，同时提供证据和局限性说明
- 支持多种目标类型的分析：原生二进制文件、JavaScript/Electron 应用、.NET 程序集以及网站
- 提供终端命令行直接使用，如对 JavaScript/Electron 应用树或 ASAR 包进行分析
- 支持 Claude Code、Cursor、GitHub Copilot CLI、VS Code 等主流 AI 编程助手

**技术亮点**:
- 基于 TypeScript 开发，要求 Node.js 22.19+，通过 npm 包 `rea-agents` 分发
- 原生分析可复用已有的 Hopper 或 Ghidra 安装，静态 JavaScript 分析无需额外引擎
- 所有分析在本地运行，Setup 过程会展示变更内容并备份现有配置，确保安全可控
- 采用 MCP（Model Context Protocol）架构，将逆向工程工具统一接入 Agent 工作流

---
## 9. [deepseek-ai/DeepGEMM](https://github.com/deepseek-ai/DeepGEMM)
- **语言**: Cuda
- **Stars**: 8,723
- **简介**: DeepGEMM: clean and efficient BLAS kernel library on GPU

### AI 总结
**简介**: DeepGEMM 是 DeepSeek 开源的高性能 GPU 张量核心内核库，统一封装了大语言模型所需的 GEMM、MoE、索引评分等核心计算原语。

**核心功能**:
- 支持 FP8、FP4、BF16 多种精度的 GEMM 内核（NT/TN/NN/TT 布局）
- 融合 MoE 与通信重叠（Mega MoE）、MQA 评分（lightning indexer）、HyperConnection 等
- 分组 GEMM（仅按 M 轴分组，N/K 固定）及权重梯度内核（稠密与 MoE 反向）
- 运行时通过 DeepJIT 编译，安装时无需 CUDA 编译

**技术亮点**:
- 基于 CUTLASS/CuTe 概念但避免重度模板依赖，代码简洁易读，适合学习 NVIDIA GPU 内核优化
- 性能对标甚至超越专家调优库，H800 上实测可达 1550 TFLOPS
- 支持 SM90/SM100 架构，SM100 支持全部内存布局；SM90 使用 FP32 缩放因子，SM100 使用 UE8M0 打包格式
- 已推出 Ascend 版本（DeepGEMM-Ascend），并持续引入局部域特性、稀疏索引器、Mega Gate 等优化

---
## 10. [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)
- **语言**: Shell
- **Stars**: 157,852
- **简介**: A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

### AI 总结
**简介**: The Agency 是一个精心打造的 AI 智能体角色集合，每个智能体都具备专属领域专长、独特个性与可交付成果，可一键安装到 Claude Code、Cursor、Codex、Gemini 等多种主流 AI 编程工具中。

**核心功能**:
- 提供覆盖工程、安全、设计、社区运营等多个领域的专业化 AI 智能体，每个智能体拥有独特的声音、沟通风格和工作流程
- 支持通过原生桌面应用（macOS / Linux / Windows）浏览全量智能体名册并一键安装，自动保持更新
- 提供 Shell 脚本安装方式，支持交互式向导、按团队/部门筛选安装，以及按单个智能体精确安装
- 可生成适配多种工具的集成文件，兼容 Claude Code、Cursor、Codex、Gemini CLI、GitHub Copilot、Aider、Windsurf、OpenCode、Qwen 等十余种工具
- 每个智能体文件包含身份与个性特征、核心任务与工作流、带代码示例的技术交付物、成功指标与沟通风格

**技术亮点**: 基于 Shell 脚本实现自动化安装与转换流程（`install.sh`、`convert.sh`），支持按部门（division）和智能体（agent）粒度灵活筛选；提供 `--dry-run` 预览、`--list teams/agents` 列表查询等 CLI 能力；通过 `runbooks.json` 管理团队名册，实现可复用的智能体编队配置；配套原生桌面应用实现跨平台一键安装与自动更新。

---
