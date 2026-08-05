---
tags:
  - github-trending
  - daily
date: 2026-08-05
created: 2026-08-05T01:55:43.878Z
---

# 2026-08-05 GitHub Trending Top 10

## 1. [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory)
- **语言**: TypeScript
- **Stars**: 13,716
- **简介**: TencentDB Agent Memory is a team-level memory hub for AI Agents — turning conversations, docs, and code into four reusable memory assets (Chat Memory, Skill, LLM-Wiki, Code-Graph) that are governed, shared, and equipped across agents and frameworks.

### AI 总结
**简介**: TencentDB Agent Memory 是一个团队级 AI Agent 记忆中枢，将对话、文档和代码转化为四种可复用的记忆资产（Chat Memory、Skill、LLM-Wiki、Code-Graph），实现跨 Agent 和框架的治理、共享与装备。

**核心功能**:
- **符号化短期记忆**: 将繁重的工具日志压缩为紧凑的 Mermaid 符号，显著降低 Token 消耗并提升任务成功率
- **分层长期记忆**: 将碎片化对话提炼为结构化的人物画像和场景，取代扁平向量存储
- **四种记忆资产**: 支持 Chat Memory（对话记忆）、Skill（技能）、LLM-Wiki（知识库）、Code-Graph（代码图谱）的复用与共享
- **跨框架集成**: 支持 OpenClaw、Hermes 等主流 Agent 框架，提供 npm 包直接接入
- **渐进式披露**: 通过分层架构（原始输出→步骤摘要→轻量画布）实现高效的上下文管理与按需检索

**技术亮点**: 采用 TypeScript 构建，核心架构基于**记忆分层**（L0 对话 → L1 原子事实 → L2 场景 → L3 人物画像）与**符号化记忆**双支柱设计。集成 OpenClaw 后实测 Token 使用量降低最高 61.38%，任务成功率相对提升 51.52%，PersonaMem 准确率从 48% 提升至 76%。

---
## 2. [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill)
- **语言**: PowerShell
- **Stars**: 17,969
- **简介**: Reverse Engineering / Authorized Penetration Testing / Security Research Skill Router Pack AI-powered routing + On-demand toolchain bootstrapping + Self-evolving knowledge base Supports Claude Code, Kiro, Cursor, Cline, and other AI coding clients 逆向/渗透/安全技能路由包 - AI 自动路由 + 按需自举工具链 + 自动进化经验库 | 支持 Claude Code / Kiro / Cursor / Cline 等代码 AI 客户端

### AI 总结
**简介**: reverse-skill 是一个面向 AI 编程助手的网络安全技能路由包，帮助 AI 在遇到逆向工程、渗透测试等任务时自动选择正确的方法论和工具链。

**核心功能**:
- **智能任务路由**: 通过 MASTER-ROUTING 和 routing 矩阵，将 APK、ELF、JS 加密、CTF 等不同类型的任务自动路由到对应的处理流程
- **按需工具链自举**: 自动检测并索引 jadx、apktool、Frida、IDA、BurpSuite 等安全工具，根据任务类型按需加载工具链
- **自进化经验库**: 将每次任务的 Evidence→Finding→Path 记录到时间线和报告中，形成可复用的经验库，避免重复犯错
- **多客户端支持**: 兼容 Claude Code、Kiro、Cursor、Cline 等主流 AI 编程客户端
- **跨平台支持**: 提供 Windows、Linux/macOS、Kali Linux 专属的安装和工具索引脚本

**技术亮点**: 采用 PowerShell 为主要脚本语言，结合 Python、Node.js、Java 等多语言工具链；内置 MCP (Model Context Protocol) 服务器支持；通过 `RULES.md` + `MASTER-ROUTING` 双层路由机制实现 AI 任务的标准化处理流程；提供严格的授权渗透测试工作流（case-init/scope.md 确保目标授权后再执行操作）。

---
## 3. [firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector)
- **语言**: Rust
- **Stars**: 10,098
- **简介**: Fast Rust library for PDF inspection, classification, and text extraction. Intelligently detects scanned vs text-based PDFs to enable smart routing decisions.

### AI 总结
**简介**: pdf-inspector 是一个用 Rust 编写的高性能 PDF 检查与文本提取库，能在无需 OCR 的情况下智能区分文本型与扫描型 PDF，并快速转换为结构化 Markdown。

**核心功能**:
- **智能分类** — 通过采样内容流在 10-50ms 内将 PDF 分类为 TextBased、Scanned、ImageBased 或 Mixed，并提供置信度分数与逐页 OCR 路由建议
- **文本提取** — 支持位置感知提取，包含字体信息、X/Y 坐标，自动处理多栏阅读顺序
- **Markdown 转换** — 自动识别标题（H1-H4）、列表、代码块、表格、粗体/斜体、URL 链接及分页符
- **表格检测** — 双模式检测（基于矩形绘图操作与文本对齐启发式），支持跨页财务表格和脚注
- **CID 字体支持** — 支持 ToUnicode CMap 解码，涵盖 Type0/Identity-H 字体及多种编码格式
- **多栏布局** — 自动检测报纸式分栏、顺序阅读及 RTL 文本支持
- **编码问题检测** — 自动标记损坏的字体编码，便于调用方回退到 OCR
- **跨语言绑定** — 提供 Python、Node.js 和浏览器 WebAssembly 绑定，可在浏览器端本地运行

**技术亮点**: 纯 Rust 实现，无 ML 模型和外部服务依赖；单次文档解析即可同时完成检测与提取，避免冗余 I/O；在基准测试中综合得分（0.875）、阅读顺序（0.915）和表格识别（0.814）均优于 PyMuPDF4LLM、markitdown 等竞品，处理 200 份文档仅需 0.47 秒。

---
## 4. [uber/ADR](https://github.com/uber/ADR)
- **语言**: Python
- **Stars**: 698
- **简介**: ADR secures enterprise AI agents through observability, security benchmarking, and threat detection. Deployed at Uber.

### AI 总结
**简介**: ADR 是 Uber 开源的面向企业 AI 代理的安全检测与响应系统，已部署于 Uber 生产环境，相关论文被 MLSys 2026 接收。

**核心功能**:
- **可观测性**: 跨 macOS、Linux、Windows 平台采集 7+ AI 编码工具（如 Cursor、Claude Code、Codex）及内部自动化、客服代理的意图、工具调用和执行轨迹
- **安全基准测试 (ADR-Bench)**: 包含 300+ 任务、133 个 MCP 服务器，覆盖全部 17 种代理攻击技术
- **威胁检测**: 采用双层架构，先高召回率分流，再对可疑会话进行深度代理推理
- **风险预防**: 在有害操作造成影响前进行拦截（该组件暂未开源）

**技术亮点**: 
- 基于 Python 实现，采用双代理检测器架构
- 提供完整的可复现评估流程（`docs/REPRODUCIBILITY.md`），支持从打包基准到生成论文图表的端到端工作流
- 开源部分包含 Sensor（遥测采集）、Detection（基准+检测）、Detector（双代理检测器），并支持 `llamafirewall` 无密钥快速测试
- 基准数据为合成数据（模拟凭证、仿真环境、提示注入场景），仅限防御性安全研究使用，遵循 Apache 2.0 许可证

---
## 5. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 266,514
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个为编码代理设计的完整软件开发方法论框架，基于可组合的技能和初始指令，让 AI 代理自动遵循规范化的开发流程。

**核心功能**:
- **需求澄清**: 代理不会直接写代码，而是先与用户对话，明确真正要解决的问题
- **规格展示**: 将讨论得出的规格以易读的短块形式呈现，方便用户审阅确认
- **实现规划**: 生成清晰、可执行的实施计划，强调真正的红/绿 TDD、YAGNI 和 DRY 原则
- **子代理驱动开发**: 用户批准后，代理通过子代理逐项执行工程任务，自动检查审查工作，可自主运行数小时
- **自动触发**: 技能自动激活，无需用户额外配置操作

**技术亮点**: 采用 Shell 编写的插件化架构，支持多种主流编码工具（Claude Code、Cursor、Gemini CLI、GitHub Copilot CLI 等），通过官方或第三方插件市场分发，并提供企业级商业支持服务。

---
## 6. [microsoft/generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners)
- **语言**: Jupyter Notebook
- **Stars**: 116,295
- **简介**: 21 Lessons, Get Started Building with Generative AI

### AI 总结
**简介**: 微软出品的面向初学者的生成式人工智能课程，包含21个手把手教学课程，帮助开发者从零开始构建生成式AI应用。

**核心功能**:
- 提供21个系统化课程，覆盖生成式AI的核心概念、提示工程、文本/图像/代码生成等主题
- 每个课程包含独立的学习模块，配有Jupyter Notebook实践代码和示例
- 支持50+种语言翻译，通过GitHub Action自动保持多语言版本同步更新
- 提供社区支持，包括Discord讨论群组和完整的开源许可证

**技术亮点**: 基于Jupyter Notebook的教学环境，课程内容涵盖OpenAI、Hugging Face等主流生成式AI工具链，并针对不同语言提供本地化部署方案（支持稀疏检出以减小仓库体积）。

---
## 7. [cypress-io/cypress](https://github.com/cypress-io/cypress)
- **语言**: TypeScript
- **Stars**: 50,803
- **简介**: Fast, easy and reliable testing for anything that runs in a browser.

### AI 总结
**简介**: Cypress 是一个快速、简单且可靠的浏览器端测试工具，专为现代 Web 应用设计。

**核心功能**:
- 支持在浏览器中运行的一切内容的端到端测试
- 提供简单易用的安装方式，支持 npm、yarn 和 pnpm 包管理器
- 内置测试运行器和可视化界面，方便调试和查看测试结果
- 支持在 Mac、Linux 和 Windows 平台上运行
- 提供 Cypress Cloud 集成，可展示测试状态和测试数量徽章
- 拥有活跃的社区支持，包括 Discord 聊天和 StackShare 集成

**技术亮点**: 基于 TypeScript 开发，采用 MIT 开源许可证，支持持续集成（CI）集成，提供 CircleCI 等工具的自动化测试支持，并拥有完善的贡献指南和文档体系。

---
## 8. [lyogavin/airllm](https://github.com/lyogavin/airllm)
- **语言**: Jupyter Notebook
- **Stars**: 28,420
- **简介**: AirLLM 70B inference with single 4GB GPU

### AI 总结
**简介**: AirLLM 是一个大幅降低大模型推理内存占用的工具，让 70B 级大语言模型能在单张 4GB 显存的 GPU 上运行，无需量化、蒸馏或剪枝。

**核心功能**:
- **超低显存推理**: 70B 模型在 4GB GPU 上运行，405B Llama 3.1 在 8GB 上运行，DeepSeek-V3 (671B) 在 ~12GB 上运行，Kimi K3 (2.8T) 在 3.72GB 显存内运行
- **支持模型广泛**: 支持 Llama 3.x/4、Qwen3/Qwen2.5、DeepSeek V2/V3、Phi-4、Gemma、ChatGLM、Baichuan、Mistral、InternLM 等主流模型
- **多种推理模式**: 支持 CPU 推理、MacOS 推理、非分片模型推理
- **模型压缩加速**: 提供 8bit/4bit 量化支持，模型压缩可带来 3 倍运行速度提升
- **自动模型识别**: 通过 AutoModel 自动检测模型类型，无需手动指定模型类
- **预取优化**: 通过预取机制重叠模型加载与计算，提升 10% 推理速度

**技术亮点**: 采用逐专家流式加载（per-expert streaming）技术，对于稀疏 MoE 模型一次只加载一个专家而非整个层，从而大幅降低显存占用；支持 FP8 模型格式；同时通过模型压缩和预取机制优化推理性能。

---
## 9. [webpack/webpack](https://github.com/webpack/webpack)
- **语言**: JavaScript
- **Stars**: 65,941
- **简介**: A bundler for javascript and friends. Packs many modules into a few bundled assets. Code Splitting allows for loading parts of the application on demand. Through "loaders", modules can be CommonJs, AMD, ES6 modules, CSS, Images, JSON, Coffeescript, LESS, ... and your custom stuff.

### AI 总结
**简介**: webpack 是一个用于 JavaScript 及其生态的模块打包器，将多个模块打包成少量静态资源，支持按需加载和资源转换。

**核心功能**:
- **模块打包**：支持 ES Modules、CommonJS、AMD 等多种模块规范，可混合使用并打包为单个 bundle 或多个异步加载的 chunk
- **代码分割（Code Splitting）**：允许将应用拆分为多个按需加载的块，减少初始加载时间
- **Loader 机制**：通过 loader 预处理各类文件，如将 TypeScript 编译为 JavaScript、将图片转为 Base64、编译 Handlebars 模板等
- **插件系统**：高度模块化的插件接口，webpack 自身功能也基于此构建，可灵活扩展以满足自定义需求
- **依赖解析**：在编译阶段解析依赖关系，减少运行时体积

**技术亮点**: 
- 基于 Node.js 构建，使用 JavaScript 开发，支持所有 ES5 兼容浏览器（IE8 及以下不支持）
- 编译时依赖解析架构，降低运行时开销
- 丰富的生态体系，拥有大量官方和社区插件（如 mini-css-extract-plugin 等）
- 活跃的社区支持，包括 TSC 技术委员会、核心贡献者、赞助商体系（含 Open Collective 赞助计划）

---
## 10. [gabime/spdlog](https://github.com/gabime/spdlog)
- **语言**: C++
- **Stars**: 29,381
- **简介**: Fast C++ logging library.

### AI 总结
**简介**: spdlog 是一个快速、仅头文件的 C++ 日志库，以性能为首要目标，支持同步和异步模式。
**核心功能**:
- 仅头文件设计，复制即可使用，兼容 C++11 编译器
- 支持多种日志目标：控制台（带颜色）、轮转文件、每日文件、syslog、Windows 调试器
- 基于 fmt 库的丰富格式化语法，可选 printf 风格支持
- 支持异步日志模式、多/单线程 logger、条件日志、运行时/编译时日志级别过滤
- 可通过实现 sink 接口轻松扩展自定义日志目标
**技术亮点**: 基于 fmt 库实现高性能格式化；Benchmark 显示同步模式比 boost log 快约 10 倍，异步模式性能优异；支持多平台（Linux、Windows、macOS、Android 等）。

---
