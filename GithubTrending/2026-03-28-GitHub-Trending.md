---
tags:
  - github-trending
  - daily
date: 2026-03-28
created: 2026-03-28T01:55:50.912Z
---

# 2026-03-28 GitHub Trending Top 10

## 1. [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)
- **语言**: Python
- **Stars**: 12,723
- **简介**: AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary

### AI 总结
**简介**: 一个能自动研究指定主题在过去30天内于Reddit、X、YouTube、Hacker News、Polymarket等多个平台上的动态，并生成带真实引用的综合性总结的AI智能体技能。

**核心功能**:
- **多平台聚合研究**：并行搜索Reddit、X、Bluesky、YouTube、TikTok、Instagram、Hacker News、Polymarket及全网内容，分析社区的点赞、分享、投注和视频讨论趋势。
- **智能分析与总结**：通过多信号质量排名相关性评分、跨平台收敛检测和时序衰减等复合评分管道处理结果，最终生成基于数据的、有引用的叙述性报告。
- **对比研究模式**：支持“X vs Y”形式的对比查询，进行三次并行研究，生成包含优势、劣势、对比表格和数据驱动结论的并排比较报告。
- **自动存档与配置**：每次运行自动将完整简报保存为Markdown文件至本地文档库，并支持项目级环境配置文件进行个性化API密钥管理。

**技术亮点**:
- 采用Python开发，集成了ScrapeCreators API（覆盖Reddit、TikTok、Instagram）。
- 实现复杂的多源数据融合管道，包括查询扩展、去重、文本相似性计算（含同义词扩展和词元重叠）以及基于参与度、权威性和时效性的加权评分。
- 针对Polymarket预测市场采用五因子加权复合排名（文本相关性、交易量、流动性深度、价格变动速度、结果竞争性）。
- 提供Claude Code插件和ClawHub命令行两种安装方式，支持在会话开始时自动验证配置。

---
## 2. [hacksider/Deep-Live-Cam](https://github.com/hacksider/Deep-Live-Cam)
- **语言**: Python
- **Stars**: 83,110
- **简介**: real time face swap and one-click video deepfake with only a single image

### AI 总结
**简介**: Deep-Live-Cam 是一款基于 Python 的实时人脸替换和视频深度伪造工具，仅需单张图片即可一键操作。

**核心功能**:
- **实时换脸**: 支持摄像头、视频流或本地视频的实时人脸替换。
- **多功能应用**: 支持保留原嘴部动作的“嘴部遮罩”、多目标同时换脸的“面部映射”、实时观看电影换脸、直播表演以及制作表情包等场景。
- **一键操作**: 提供三步快速启动流程（选择人脸、选择摄像头、点击直播），简化使用。

**技术亮点**: 项目基于 ONNX 模型（如 GFPGAN、inswapper）实现高效推理，并提供预编译版本（支持 Windows/Mac/CPU/GPU）以降低部署难度，同时内置了内容安全审查机制以防止不当内容处理。

---
## 3. [SakanaAI/AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2)
- **语言**: Python
- **Stars**: 2,881
- **简介**: The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search

### AI 总结
**简介**: AI Scientist-v2 是一个端到端的自主智能体系统，能够通过智能体树搜索进行自动化科学研究，并已生成首篇完全由AI撰写且通过同行评审的研讨会论文。

**核心功能**:
- **自主科研流程**: 能够自主生成研究假设、运行实验、分析数据并撰写科学论文。
- **跨领域泛化**: 相比前代版本，它减少了对人工编写模板的依赖，能够泛化应用于机器学习等多个领域。
- **探索性研究**: 采用渐进式智能体树搜索策略，由一个实验管理智能体引导，更适合开放式的科学探索。

**技术亮点**:
- **架构**: 采用基于智能体的树搜索架构，由实验管理智能体进行协调。
- **模型支持**: 支持 OpenAI、Gemini（通过 OpenAI API）以及 Claude（通过 AWS Bedrock）等多种大语言模型。
- **环境要求**: 基于 Linux 和 CUDA 的 PyTorch 环境运行，并集成了 Semantic Scholar API 用于文献检索。
- **安全警告**: 代码会执行由LLM生成的代码，存在潜在风险，必须在受控的沙箱环境（如 Docker 容器）中运行。

---
## 4. [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice)
- **语言**: Python
- **Stars**: 24,704
- **简介**: Open-Source Frontier Voice AI

### AI 总结
**简介**: VibeVoice 是微软开源的前沿语音AI模型家族，包含文本到语音（TTS）和自动语音识别（ASR）模型。

**核心功能**:
- **VibeVoice-ASR**: 统一的语音转文本模型，支持单次处理长达60分钟的音频，生成包含说话人、时间戳和内容的结构化转录，原生支持超过50种语言，并已集成至Hugging Face Transformers库。
- **VibeVoice-Realtime-TTS**: 实时文本转语音模型，支持流式文本输入和稳健的长语音生成，提供多语言和多种风格的实验性语音。
- **VibeVoice-TTS**: 长文本、多说话人文本转语音模型（注：根据项目公告，其核心TTS代码因使用问题已被移除）。

**技术亮点**:
- 采用创新的**7.5 Hz超低帧率连续语音分词器**（声学和语义），在保持音频保真度的同时显著提升长序列处理的计算效率。
- 基于 **“下一词扩散”框架**，结合大型语言模型理解文本上下文，并使用扩散头生成高保真声学细节。
- 支持 **vLLM推理** 以加速ASR模型的推理速度。

---
## 5. [twentyhq/twenty](https://github.com/twentyhq/twenty)
- **语言**: TypeScript
- **Stars**: 42,028
- **简介**: Building a modern alternative to Salesforce, powered by the community.

### AI 总结
**简介**: Twenty 是一个由社区驱动的开源 CRM，旨在构建一个现代化的 Salesforce 替代方案。

**核心功能**:
- 个性化布局：支持过滤器、排序、分组、看板和表格视图。
- 自定义对象和字段：灵活定义数据模型。
- 权限管理：通过自定义角色创建和管理权限。
- 工作流自动化：使用触发器和动作实现流程自动化。
- 集成功能：支持邮件、日历事件、文件等。

**技术亮点**: 基于 TypeScript 开发，支持自托管和本地部署，并计划构建插件生态系统。

---
## 6. [datalab-to/chandra](https://github.com/datalab-to/chandra)
- **语言**: Python
- **Stars**: 7,040
- **简介**: OCR model that handles complex tables, forms, handwriting with full layout.

### AI 总结
**简介**: Chandra OCR 2 是一个先进的 OCR 模型，可将图像和 PDF 转换为结构化的 HTML/Markdown/JSON，同时完整保留布局信息。

**核心功能**:
- 支持 90 多种语言的文档识别，在表格、数学公式、布局和文本准确性方面表现出色。
- 准确重建表单（包括复选框）、表格、数学公式和复杂布局。
- 提供两种推理模式：本地（HuggingFace）和远程（vLLM 服务器）。
- 提供托管 API 和免费在线体验平台。

**技术亮点**: 模型在公开的 olmocr 基准测试中表现优异，并针对多语言场景进行了专门优化和基准测试。

---
## 7. [obra/superpowers](https://github.com/obra/superpowers)
- **语言**: Shell
- **Stars**: 118,611
- **简介**: An agentic skills framework & software development methodology that works.

### AI 总结
**简介**: Superpowers 是一个基于可组合“技能”的智能体技能框架和软件开发方法论，旨在为编码智能体提供一套完整、自动化的开发工作流。

**核心功能**:
- **自动化工作流管理**: 从需求澄清、设计确认、实施计划到子智能体驱动开发，提供端到端的自动化流程。
- **可组合技能库**: 内置多种自动化技能，如测试驱动开发、系统化调试、代码审查请求等，智能体会在任务前自动检查并应用相关技能。
- **多平台支持**: 支持 Claude Code、Cursor、Codex、OpenCode 和 Gemini CLI 等多种AI编码助手和平台。

**技术亮点**: 强调真正的红绿测试驱动开发、YAGNI和DRY原则，并通过“子智能体驱动开发”模式，使智能体能够长时间自主工作而不偏离计划。

---
## 8. [virattt/dexter](https://github.com/virattt/dexter)
- **语言**: TypeScript
- **Stars**: 19,706
- **简介**: An autonomous agent for deep financial research

### AI 总结
**简介**: Dexter 是一个用 TypeScript 编写的自主金融研究智能体，能够将复杂的金融问题分解为结构化任务，并利用实时市场数据进行分析和验证。

**核心功能**:
- **智能任务规划**: 自动将复杂查询分解为结构化的研究步骤。
- **自主执行与验证**: 选择并执行工具以获取金融数据，并能自我检查工作并迭代优化。
- **实时数据接入**: 可访问损益表、资产负债表和现金流量表等实时市场数据。
- **安全与可靠性**: 内置循环检测和步骤限制，防止执行失控。

**技术亮点**:
- 基于 **Bun** 运行时环境。
- 支持多种大语言模型 API（OpenAI、Anthropic、Google、XAI、OpenRouter）及本地 **Ollama**。
- 集成专业金融数据 API（Financial Datasets）和网络搜索 API（Exa/Tavily）。
- 包含基于 **LangSmith** 的评估套件，采用 LLM-as-judge 方法进行评分。
- 提供详细的调试支持，所有工具调用和推理步骤均记录在 `.dexter/scratchpad/` 目录下的 JSONL 文件中。

---
## 9. [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode)
- **语言**: TypeScript
- **Stars**: 13,988
- **简介**: Teams-first Multi-agent orchestration for Claude Code

### AI 总结
**简介**: 一个为 Claude Code 设计的、团队优先的多智能体编排框架，旨在提供零学习曲线的开发体验。

**核心功能**:
- **团队模式**：作为核心编排方式，支持多智能体协作，执行流程为 `team-plan → team-prd → team-exec → team-verify → team-fix`。
- **快速启动**：通过简单的插件安装和设置命令即可开始使用，支持 `autopilot` 等指令自动构建项目。
- **深度访谈**：提供 `/deep-interview` 指令，通过苏格拉底式提问帮助用户在编码前理清需求和设计。
- **多模型支持**：通过 `omc team` 命令可创建基于 tmux 的 Codex、Gemini 或 Claude CLI 工作进程，实现按需分配和混合模型协作。
- **向后兼容**：为 OpenAI Codex CLI 用户提供同等的 `oh-my-codex` 项目体验。

**技术亮点**:
- 基于 TypeScript 开发。
- 采用 CLI 和插件化设计，与 Claude Code 深度集成。
- 利用 tmux 管理独立的工作进程，实现资源按需分配与回收。

---
## 10. [FreeCAD/FreeCAD](https://github.com/FreeCAD/FreeCAD)
- **语言**: C++
- **Stars**: 29,675
- **简介**: Official source code of FreeCAD, a free and opensource multiplatform 3D parametric modeler.

### AI 总结
**简介**: FreeCAD 是一个开源、跨平台、基于参数化建模的 3D CAD 设计软件，适用于产品设计、机械工程和建筑等领域。

**核心功能**:
- **参数化建模**：通过修改模型历史中的参数来轻松调整设计。
- **2D 与 3D 互转**：支持绘制带几何约束的 2D 草图，并以此为基础构建 3D 对象，也能从 3D 模型生成高质量工程图。
- **多领域适用**：满足从爱好者到专业工程师、学生到教师等不同用户的设计需求。
- **跨平台运行**：支持 Windows、macOS 和 Linux 操作系统。

**技术亮点**:
- 基于强大的 **OpenCASCADE** 几何内核。
- 使用 **Coin3D** 库进行 3D 场景表示。
- 提供广泛的 **Python API** 支持脚本和扩展。
- 采用 **Qt** 框架构建图形用户界面。

---
