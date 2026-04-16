---
tags:
  - github-trending
  - daily
date: 2026-04-16
created: 2026-04-16T01:55:49.826Z
---

# 2026-04-16 GitHub Trending Top 10

## 1. [forrestchang/andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills)
- **语言**: Unknown
- **Stars**: 43,353
- **简介**: A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.

### AI 总结
**简介**: 一个包含 Karpathy 启发的四大编码原则的 `CLAUDE.md` 文件，旨在改进 Claude Code 的行为，解决 LLM 编码中的常见陷阱。

**核心功能**:
- **编码前思考**: 要求模型明确陈述假设、呈现多种解释、在必要时提出异议，并在困惑时主动澄清。
- **简洁优先**: 倡导编写最简代码，避免过度设计、不必要的抽象和推测性功能。
- **精准修改**: 只修改与任务直接相关的代码，不“顺手”改进无关代码或格式，并清理自己引入的冗余。
- **目标驱动执行**: 将指令转化为可验证的成功标准（如先写测试），并制定分步验证计划，让模型能自主循环直至达标。

**技术亮点**: 以单文件 (`CLAUDE.md`) 或 Claude Code 插件的形式提供，通过一套清晰的行为准则直接约束和引导 LLM 的编码过程，提升代码质量和开发效率。

---
## 2. [pascalorg/editor](https://github.com/pascalorg/editor)
- **语言**: TypeScript
- **Stars**: 12,690
- **简介**: Create and share 3D architectural projects.

### AI 总结
**简介**: 一个基于 React Three Fiber 和 WebGPU 构建的 3D 建筑编辑器，用于创建和分享建筑项目。

**核心功能**:
- 提供完整的 3D 场景编辑能力，支持创建建筑、楼层、墙体、楼板、区域等多种节点。
- 支持场景状态管理，包括节点的增删改查、撤销/重做以及数据持久化。
- 包含独立的查看器组件，可将 3D 场景嵌入到其他应用中。

**技术亮点**:
- **架构**: 采用 Turborepo 管理的 Monorepo 结构，核心逻辑（`@pascal-app/core`）、3D 渲染（`@pascal-app/viewer`）和编辑器应用（`apps/editor`）分离，职责清晰。
- **状态管理**: 使用 Zustand 状态库，并为不同模块（场景、查看器、编辑器）设计了独立的 Store。
- **3D 渲染**: 基于 React Three Fiber，并实现了场景注册表（Scene Registry）以高效映射数据节点与 Three.js 对象。
- **数据持久化**: 通过 Zustand 中间件将场景数据保存到 IndexedDB，并集成 Zundo 提供 50 步的撤销/重做功能。

---
## 3. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **语言**: TypeScript
- **Stars**: 57,905
- **简介**: A Claude Code plugin that automatically captures everything Claude does during your coding sessions, compresses it with AI (using Claude's agent-sdk), and injects relevant context back into future sessions.

### AI 总结
**简介**: 一个为 Claude Code 设计的持久化记忆压缩系统插件，能自动记录编码会话内容，利用 AI 压缩并注入相关上下文到未来会话中。

**核心功能**:
- 自动捕获 Claude 在编码会话中的所有操作
- 使用 AI（基于 Claude 的 agent-sdk）对捕获内容进行智能压缩
- 将压缩后的相关上下文智能注入到未来的编码会话中

**技术亮点**: 基于 TypeScript 开发，利用 Claude 的 agent-sdk 实现 AI 驱动的上下文压缩与检索。

---
## 4. [Lordog/dive-into-llms](https://github.com/Lordog/dive-into-llms)
- **语言**: Jupyter Notebook
- **Stars**: 29,547
- **简介**: 《动手学大模型Dive into LLMs》系列编程实践教程

### AI 总结
**简介**: 这是一个名为《动手学大模型》的系列编程实践教程，旨在通过Jupyter Notebook形式的实践项目，帮助学习者快速入门大模型相关的开发与应用。

**核心功能**:
- 提供从大模型微调部署、提示学习、知识编辑到数学推理、模型水印、越狱攻击、多模态模型、GUI智能体等多个主题的实践教程。
- 每个主题均配套课件、详细教程文档和可运行的Jupyter Notebook脚本，方便动手实践。
- 项目属公益性质，完全免费，并持续更新，近期新增了国产化大模型开发全流程教程及数学推理、GUI Agent等新主题。

**技术亮点**: 教程内容基于上海交通大学相关课程讲义拓展，覆盖大模型前沿技术领域，并积极整合社区资源（如华为昇腾社区），提供理论与实践结合的完整学习路径。

---
## 5. [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund)
- **语言**: Python
- **Stars**: 55,105
- **简介**: An AI Hedge Fund Team

### AI 总结
**简介**: 这是一个用于教育研究的AI驱动对冲基金概念验证项目，通过模拟多位著名投资大师风格的智能体协作，生成股票交易信号，但不进行真实交易。

**核心功能**:
- 集成19个不同角色的智能体，涵盖估值、基本面、技术面、市场情绪分析和风险管理。
- 提供命令行界面和Web应用两种运行方式，支持对指定股票代码进行分析。
- 包含回测功能，可评估策略在历史时间段的表现。
- 支持多种大语言模型API（如OpenAI、Groq）以及本地Ollama模型。

**技术亮点**: 采用Python开发，使用Poetry管理依赖，通过模块化的多智能体架构模拟完整的投资决策流程。

---
## 6. [chrislgarry/Apollo-11](https://github.com/chrislgarry/Apollo-11)
- **语言**: Assembly
- **Stars**: 66,819
- **简介**: Original Apollo 11 Guidance Computer (AGC) source code for the command and lunar modules.

### AI 总结
**简介**: 该项目托管了阿波罗11号任务中指令舱和登月舱的原始制导计算机（AGC）汇编源代码。

**核心功能**:
- 提供阿波罗11号指令舱（Comanche 055）和登月舱（Luminary 099）制导计算机的完整源代码。
- 作为历史代码的存档库，接受与原始扫描件对比的纠错和改进贡献。

**技术亮点**: 使用原始的 yaYUL 汇编器，代码已数字化并进入公共领域，可供编译和研究。

---
## 7. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 154,380
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为 AI 编程助手（Agent）设计的、基于可组合“技能”的智能软件开发框架与工作流。

**核心功能**:
- **智能规划与设计**：在编码前，通过对话明确需求，并分块呈现可审阅的设计方案。
- **子代理驱动开发**：将任务分解为原子级步骤，由独立的子代理执行并经过两阶段审查。
- **强制测试驱动开发**：在整个实现过程中强制执行“红-绿-重构”的 TDD 循环。
- **自动化工作流**：内置从头脑风暴、Git 工作区管理到代码审查、分支收尾的完整自动化流程。

**技术亮点**: 采用基于“技能”的插件化架构，技能在任务前自动触发，形成一套强制的、非建议性的开发方法论，支持在 Claude Code、Cursor、Codex 等多种 AI 编程平台中运行。

---
## 8. [jamiepine/voicebox](https://github.com/jamiepine/voicebox)
- **语言**: TypeScript
- **Stars**: 18,323
- **简介**: The open-source voice synthesis studio

### AI 总结
**简介**: Voicebox 是一个开源的、本地优先的语音合成与克隆工作室，可作为 ElevenLabs 的免费替代品。

**核心功能**:
- **语音克隆**：支持从几秒钟的音频中克隆声音。
- **多引擎语音合成**：集成 Qwen3-TTS、LuxTTS、Chatterbox Multilingual 等 5 种 TTS 引擎，支持 23 种语言。
- **后期处理效果**：提供音高变换、混响、延迟、合唱、压缩等多种音频效果。
- **故事编辑器**：提供多音轨时间线编辑器，用于创作对话、播客和叙事内容。
- **API 优先**：提供 REST API，便于将语音合成功能集成到其他项目中。

**技术亮点**: 采用 Tauri (Rust) 框架构建，非 Electron，提供原生性能。支持本地运行，确保模型和语音数据的完全隐私。支持多种硬件平台（macOS MLX/Metal、Windows CUDA、Linux、AMD ROCm 等）。

---
## 9. [public-apis/public-apis](https://github.com/public-apis/public-apis)
- **语言**: Python
- **Stars**: 423,398
- **简介**: A collective list of free APIs

### AI 总结
**简介**: 一个由社区和 APILayer 共同维护的免费公共 API 集合项目，旨在为开发者提供来自多个领域的丰富 API 资源。

**核心功能**:
- 提供大量来自不同领域的免费公共 API 列表，供开发者用于自己的产品。
- 社区驱动，由成员手动精心整理和维护。
- 包含 APILayer 旗下多个热门 API 的详细介绍和快速调用入口（如 IP 定位、股票数据、天气信息等）。

**技术亮点**: 项目本身主要是一个列表仓库，其亮点在于社区化的内容管理和维护模式，并提供了便捷的 Postman 按钮，允许开发者一键导入并测试 API 集合。

---
## 10. [vercel-labs/open-agents](https://github.com/vercel-labs/open-agents)
- **语言**: TypeScript
- **Stars**: 2,665
- **简介**: An open source template for building cloud agents.

### AI 总结
**简介**: 一个用于在 Vercel 上构建和运行后台编码智能体的开源参考应用模板。

**核心功能**:
- 提供完整的 Web UI、智能体运行时、沙箱编排和 GitHub 集成，实现从提示到代码变更的自动化流程。
- 支持基于聊天的编码智能体，具备文件操作、搜索、Shell、任务、技能和 Web 工具等多种能力。
- 支持持久化的多步骤执行、流式响应和任务取消。
- 提供基于快照、可休眠和恢复的隔离 Vercel 沙箱环境。
- 支持在沙箱内克隆仓库、分支工作，并可选择自动提交、推送和创建 PR。
- 支持通过只读链接分享会话，并可选配语音输入（通过 ElevenLabs）。

**技术亮点**:
- **三层架构**: 采用“Web -> 智能体工作流 -> 沙箱虚拟机”的分离设计，智能体不运行在沙箱内部，通过工具与其交互。
- **关键设计**: 智能体执行与请求生命周期解耦，沙箱生命周期可独立休眠/恢复，模型/供应商选择与沙箱实现可独立演进。
- **技术栈**: 基于 TypeScript，使用 Vercel Workflow SDK 管理运行，依赖 PostgreSQL、Redis/Upstash KV 等。

---
