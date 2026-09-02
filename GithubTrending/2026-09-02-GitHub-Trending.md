---
tags:
  - github-trending
  - daily
date: 2026-09-02
created: 2026-09-02T01:55:45.105Z
---

# 2026-09-02 GitHub Trending Top 10

## 1. [Gitlawb/openclaude](https://github.com/Gitlawb/openclaude)
- **语言**: TypeScript
- **Stars**: 31,345
- **简介**: runs anywhere. uses anything

### AI 总结
**简介**: OpenClaude 是一个开源的编码智能体 CLI，为云端和本地模型提供商提供统一的终端优先工作流。

**核心功能**:
- 支持多种模型后端：OpenAI 兼容 API、Gemini、GitHub Models、Codex OAuth、Codex、Ollama、Atomic Chat 等
- 统一的终端工作流：包含提示词、工具、智能体、MCP、斜杠命令和流式输出
- 可在任意环境中运行，适配多种模型提供商
- 提供 VS Code 扩展支持

**技术亮点**:
- 使用 TypeScript 开发，通过 npm 分发
- 采用模块化架构，支持多种模型提供商的无缝切换
- 拥有活跃的社区生态，与 GitLawb、Bankr.bot、Atomic Chat、Xiaomi MiMo、Atlas Cloud、AI/ML API、Novita AI 等合作伙伴集成
- 通过 GitHub Actions 实现自动化 PR 检查和发布流程

---
## 2. [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills)
- **语言**: Python
- **Stars**: 44,935
- **简介**: Academic Research Skills for Claude Code: research → write → review → revise → finalize

### AI 总结
**简介**: 这是一个为 Claude Code 打造的学术研究技能套件，覆盖从研究到发表的完整工作流程，采用人机协作模式而非全自动化，帮助研究者完成文献检索、引用格式化、数据验证和逻辑一致性检查等繁琐工作。

**核心功能**:
- **全流程研究管线**: 覆盖 research → write → review → revise → finalize 的完整学术研究流程，通过 `/ars-plan` 以苏格拉底式对话引导梳理论文结构
- **引用完整性审计**: 支持三层层级引用锚点，可追溯来源出处；v3.8 新增可选审计模式（`ARS_CLAIM_AUDIT=1`），自动抓取引用源并判断论证是否得到支持
- **风格校准与质量检查**: 从过往作品中学习用户写作风格，检测机器生成文本的常见模式，提升写作质量而非伪装 AI 使用痕迹
- **完整性门控机制**: Stage 2.5 和 Stage 4.5 设置 7 模式阻塞检查清单，审稿人支持可选的校准模式，可测量自身的假阴性/假阳性率
- **风险信号提示**: 在引用时标记声明-忠实度差距（内部术语 "L3"），对 claim-not-supported、fabricated-reference 等五类高风险问题实施门控拒绝

**技术亮点**: 基于 Lu et al. (2026, *Nature*) 的 The AI Scientist 和 Zhao et al. (2026) 对 1.11 亿条引用的语料级审计结果设计，内置信任链 frontmatter 用于来源溯源，提供 20 元组黄金标准校准集（FNR<0.15 + FPR<0.10 接受阈值），支持 30 秒快速安装（Claude Code CLI / VS Code / JetBrains，v3.7.0+）。

---
## 3. [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC)
- **语言**: TypeScript
- **Stars**: 29,564
- **简介**: Open Multi-Agent Interactive Classroom — Get an immersive, multi-agent learning experience in just one click

### AI 总结
**简介**: OpenMAIC 是一个开源的多智能体互动课堂平台，只需一次点击即可获得沉浸式多智能体学习体验，支持一键生成完整课程。

**核心功能**:
- **Agent 工作台**：通过对话式界面规划、构建和修改整个课程，支持课程大纲制定与逐页内容生成
- **持久化会话**：服务端支持的课程构建会话可跨重启存活，支持随时取消、恢复和调整
- **会话材料上传**：支持上传文档、音频、视频或从网络搜索获取素材，智能体基于这些材料构建课程
- **20+ 内置技能**：涵盖幻灯片、测验、互动组件、PBL（项目式学习）、图片、视频、语音及 `.pptx` 导入等课程工具
- **提供商中立设计**：可自由接入自己的模型、媒体、搜索提供商和存储后端
- **OpenClaw 集成与 Lemonade 本地 AI**：支持本地 AI 推理与外部智能体工具集成

**技术亮点**: 基于 Next.js 16、React 19、TypeScript 5 构建，采用 LangGraph 1.1 实现多智能体编排，使用 Tailwind CSS 4 进行样式设计；支持一键部署到 Vercel，提供可插拔的持久化存储架构；相关论文发表于 JCST'26。

---
## 4. [iv-org/invidious](https://github.com/iv-org/invidious)
- **语言**: Crystal
- **Stars**: 23,778
- **简介**: Invidious is an alternative front-end to YouTube

### AI 总结
**简介**: Invidious 是一个开源的 YouTube 替代前端，旨在提供轻量、无广告、无追踪的观看体验，使用 Crystal 语言开发。

**核心功能**:
- 无广告、无追踪、无需 JavaScript，支持浅色/深色主题
- 订阅功能独立于 Google 账号，支持频道通知
- 音频模式（支持移动端后台播放）和 Reddit 评论支持
- 支持从 YouTube、NewPipe、FreeTube 导入订阅/观看历史，并可导出数据
- 提供开发者 API，支持嵌入式视频播放
- 多语言支持（通过 Weblate 社区翻译）

**技术亮点**:
- 使用 Crystal 语言编写，不依赖官方 YouTube API
- 无贡献者许可协议（CLA），完全开源（AGPLv3 许可证）
- 支持自托管，提供公共实例列表，并推荐配合隐私重定向浏览器扩展使用

---
## 5. [jingyaogong/minimind](https://github.com/jingyaogong/minimind)
- **语言**: Python
- **Stars**: 57,131
- **简介**: 🧠 Train a 64M-parameter LLM from scratch in just 2h!

### AI 总结
**简介**: MiniMind 是一个从零开始训练超小规模大语言模型（约64M参数）的开源项目，仅需约3元成本和2小时即可完成训练，旨在降低 LLM 学习门槛。

**核心功能**:
- 提供完整的大模型训练链路：预训练（Pretrain）、监督微调（SFT）、LoRA、RLHF（DPO）、RLAIF（PPO/GRPO/CISPO）、工具调用、Agentic RL、模型蒸馏等
- 支持 Dense 和 MoE 两种模型结构，主线对齐 Qwen3/Qwen3-MoE 生态
- 包含 Tokenizer 训练代码，支持 `<think>`、`<tool_call>` 等模板标记
- 提供全阶段开源高质量数据集（含收集、蒸馏、清洗去重）
- 兼容 transformers、trl、peft 等主流框架，以及 llama.cpp、vllm、ollama 等推理引擎
- 支持单机单卡/多卡（DDP、DeepSpeed）训练，支持 wandb/swanlab 可视化
- 提供兼容 OpenAI API 的服务端和基于 Streamlit 的聊天 WebUI
- 支持 C-Eval、C-MMLU 等第三方评测集，支持 YaRN 长文本外推
- 拓展了视觉模型 MiniMind-V、多模态 MiniMind-O、扩散语言模型等衍生项目

**技术亮点**: 核心算法全部使用 PyTorch 从零原生实现，不依赖第三方库高层抽象；模型体积约为 GPT-3 的 1/2700，普通个人 GPU 即可复现；覆盖从数据清洗到强化学习的完整 LLM 训练流程，兼具教学与实战价值。

---
## 6. [3b1b/manim](https://github.com/3b1b/manim)
- **语言**: Python
- **Stars**: 92,581
- **简介**: Animation engine for explanatory math videos

### AI 总结
**简介**: Manim 是一个用于创建精确编程动画的引擎，专为制作解释性数学视频而设计，由 3Blue1Brown 作者开发。

**核心功能**:
- 提供精确的编程动画引擎，可创建高质量数学解释视频
- 支持 LaTeX 公式渲染，方便展示数学表达式
- 包含丰富的动画场景示例（如 `OpeningManimExample`），便于快速上手
- 支持通过命令行直接渲染动画场景
- 兼容 Python 3.10+，支持 Windows、Linux、macOS 多平台

**技术亮点**: 基于 Python 构建，依赖 FFmpeg（视频处理）、OpenGL（渲染）和 LaTeX（公式排版）；项目分为 ManimGL（本仓库）和社区版（ManimCommunity/manim）两个分支，本仓库为原始版本，包名为 `manimgl`，采用 MIT 开源协议。

---
## 7. [firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector)
- **语言**: Rust
- **Stars**: 17,961
- **简介**: Fast Rust library for PDF inspection, classification, and text extraction. Intelligently detects scanned vs text-based PDFs to enable smart routing decisions.

### AI 总结
**简介**: pdf-inspector 是一个用 Rust 编写的高性能 PDF 检测与文本提取库，能在毫秒级识别 PDF 是文本型还是扫描型，并智能决定是否触发 OCR，从而避免不必要的昂贵 OCR 开销。

**核心功能**:
- **智能分类**：在 10-50ms 内识别 PDF 为 TextBased、Scanned、ImageBased 或 Mixed 类型，并提供置信度评分和逐页 OCR 路由建议
- **文本提取**：支持位置感知提取，包含字体信息、X/Y 坐标，自动处理多栏阅读顺序
- **Markdown 转换**：自动识别标题（H1-H4）、列表、代码块、表格、粗体/斜体、URL 链接和分页符
- **表格检测**：双模式检测（基于矩形绘制操作 + 基于文本对齐启发式），支持跨页表格和金融表格
- **选择性 OCR**：仅对需要 OCR 的页面进行本地渲染和处理，支持 PP-OCRv6 Small 模型，并保留逐页来源追踪
- **多语言绑定**：提供 Python、Node.js 和浏览器 WebAssembly 绑定，支持在浏览器中本地运行

**技术亮点**:
- 完整支持 CID 字体（ToUnicode CMap 解码）和多种编码（UTF-16BE、UTF-8、Latin-1）
- 文档单次加载共享解析结果，避免重复 I/O
- 默认构建保持纯提取，OCR 相关依赖（PDFium、ONNX Runtime）按需加载
- 在 opendataloader-bench 基准测试中，综合得分 0.875 领先于 PyMuPDF4LLM、MarkItDown 等方案，200 份文档仅需 0.47 秒

---
## 8. [browser-use/video-use](https://github.com/browser-use/video-use)
- **语言**: Python
- **Stars**: 22,978
- **简介**: Edit videos with coding agents

### AI 总结
**简介**: video-use 是一个开源工具，让你通过 Claude Code 等编码代理，用自然语言对话的方式完成视频剪辑，无需任何预设或菜单操作。

**核心功能**:
- **智能剪辑**: 自动剪掉口头禅（如"umm"、"uh"）、错误开头和拍摄间隙的空白片段
- **自动调色**: 为每个片段应用电影感暖色调、中性色调或自定义 ffmpeg 调色链
- **音频平滑过渡**: 每个剪切点自动添加 30ms 音频淡入淡出，避免爆音
- **字幕烧录**: 支持自定义字幕样式，默认使用两词大写块格式
- **动画叠加**: 通过 HyperFrames、Remotion、Manim 或 PIL 生成动画覆盖层，每个动画由并行子代理独立生成
- **自动质检**: 在每次剪切边界自动评估渲染输出，发现问题自动修复并重新渲染（最多重试 3 次）
- **会话记忆**: 将项目状态持久化到 `project.md`，下次会话可无缝续接

**技术亮点**:
- **"让 LLM 读视频而非看视频"** 的创新架构：通过 ElevenLabs Scribe 生成带词级时间戳和说话人分离的文字稿（约 12KB），替代传统逐帧分析（约 45M tokens），大幅降低计算成本
- **双重视觉感知层**: 文字稿作为主要输入 + 按需生成时间线视觉合成图（胶片条 + 波形 + 词标签）用于决策点检查
- **完整流水线**: 转写 → 打包 → LLM 推理 → 生成 EDL 剪辑列表 → 渲染 → 自评估循环
- **多代理并行架构**: 动画生成和视频剪辑由独立子代理并行执行
- 基于 Python，依赖 ffmpeg 和 ElevenLabs API，支持与 Claude Code、Codex、Hermes 等主流编码代理集成

---
## 9. [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- **语言**: Python
- **Stars**: 41,569
- **简介**: Turn any AI agent into an AI Scientist. The #1 Agent Skills library for science, used by 190,000+ scientists worldwide. 165 ready-to-use validated skills plus 100+ scientific databases covering biology, chemistry, medicine, and drug discovery. Compatible with Cursor, Claude Code, Codex, Pi, Antigravity, and the open Agent Skills standard.

### AI 总结
**简介**: 一个包含163个即用型科研技能和100+科学数据库的开源库，可将任何AI代理（如Cursor、Claude Code、Codex等）转变为跨生物学、化学、医学和药物发现领域的AI科学家助手。

**核心功能**:
- **科研技能库**: 提供163个经过验证的技能，涵盖癌症基因组学、PK/PD建模、分子动力学、RNA速率分析、微生物组基础模型、地理空间科学和时间序列预测等
- **科学数据库集成**: 支持100+科学数据库，包括个体级1000 Genomes查询、病原体变异监测、生物医学文献检索、药物-靶点结合分析等
- **多平台兼容**: 支持开放Agent Skills标准，可无缝运行于Cursor、Claude Code、Codex、Google Antigravity等主流AI代理工具
- **即插即用**: 既可作为Agent Skills标准包使用，也可作为Agent Plugins插件包（plugin.json + skills/）整体加载
- **复杂工作流执行**: 支持多步骤科研工作流的自动化执行，覆盖从文献检索到数据建模的完整研究流程

**技术亮点**:
- 遵循开放Agent Skills标准和Agent Plugins标准，确保跨平台可移植性
- 基于Python构建，包含完整的CI/CD（安全扫描和技能测试自动化）
- 提供配套的K-Dense BYOK开源桌面端AI共同科学家工具，支持本地部署和云端扩展（Modal）

---
## 10. [handsomestWei/patent-disclosure-skill](https://github.com/handsomestWei/patent-disclosure-skill)
- **语言**: Python
- **Stars**: 6,747
- **简介**: 中国专利.skill：专利点挖掘与交底书（发明/实用/外观）编写，通俗解读专利，嗅探政策动向，辅助审查答复。

### AI 总结
**简介**: 一个面向发明人/申请人的中国专利辅助技能，覆盖专利点挖掘、交底书编写（发明/实用新型/外观）、专利通俗解读、政策嗅探与审查答复辅助，支持将解读结果沉淀为个人 Obsidian 专利知识库。

**核心功能**:
- **专利交底书编写**: 支持发明/实用新型/外观设计三种类型分模板成文，自动生成 mermaid 框图、结构线稿（含部件序号）、外观线稿，可输出可编辑 Word 文档，支持多版本迭代与修改追溯
- **个人专利检索**: 基于国知局高级查询，按发明人/申请人检索公开专利清单，支持分页遍历与同名过滤
- **项目扫描与专利点挖掘**: 自动扫描项目文档/代码（含 .docx/.pptx 转 Markdown），按类型梳出可申请专利点，支持候选点讨论与融合
- **查新检索**: 优先调用国知局中国专利公布公告接口，异常时降级 WebSearch，著录信息写入交底书第一章
- **专利通俗解读**: 将公开专利用通俗语言解读为笔记与图谱，入库 Obsidian，支持双链、知识图谱、Canvas 叙事线，构建私有专利情报层
- **专利分析与比对**: 基于知识库进行同族对照、技术路线梳理、差异点扫描

**技术亮点**: Python 3.9+，基于 Playwright 实现国知局 CNIPA 数据抓取；支持 CAD (.step/.stp) 三维模型自动提取多视角投影图；图生图/文生图生成外观线稿；mermaid 框图自动生成；Obsidian CLI 集成；模块化工具链（cnipa_epub_search.py、project_scan.md 等）；MIT 开源协议。

---
