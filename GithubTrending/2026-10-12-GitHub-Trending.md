---
tags:
  - github-trending
  - daily
date: 2026-10-12
created: 2026-10-12T01:55:42.472Z
---

# 2026-10-12 GitHub Trending Top 8

## 1. [morluto/rea](https://github.com/morluto/rea)
- **语言**: TypeScript
- **Stars**: 107,613
- **简介**: Reverse engineer anything with agents, from app behavior down to native binaries.

### AI 总结
**简介**: REA 是一个基于 MCP 协议的逆向工程工具，借助 AI Agent 帮助开发者从应用行为一路分析到原生二进制，理解任意软件功能的实现原理。

**核心功能**:
- **多目标逆向分析**：支持原生二进制、JavaScript/Electron 应用、.NET 程序集以及网站等多种目标类型
- **Agent 集成**：通过 MCP 服务器将逆向工具接入 Claude Code、Codex、Cursor、Gemini CLI 等 AI 编程助手
- **证据驱动的结论**：分析结果附带证据和局限性说明，而非仅给出黑盒结论
- **终端直接使用**：提供 `rea` CLI 命令，可在终端独立执行分析任务
- **本地化运行**：所有分析在本地执行，保障数据隐私
- **原生分析引擎对接**：可复用已有的 Hopper、Ghidra 或 IDA 安装环境

**技术亮点**:
- 基于 TypeScript 开发，通过 npm 包 `rea-agents` 分发，一条 `npx rea-agents setup` 即可完成配置
- 采用 MCP（Model Context Protocol）作为 Agent 与工具之间的通信标准
- 静态 JavaScript 分析无需依赖原生分析引擎，降低使用门槛
- 提供结构化的 JSON 输出（模块、导入、Electron 边界等），便于脚本化与自动化集成
- 支持多语言文档（含中文、日文、韩文等十余种语言）

---
## 2. [boykopovar/AnyPS5](https://github.com/boykopovar/AnyPS5)
- **语言**: C++
- **Stars**: 30,270
- **简介**: Tool for automatic PS5 executables porting to Linux and Windows

### AI 总结
**简介**: AnyPS5 是一个用 C++ 编写的工具，可将 PS5 可执行文件自动移植到 Linux 和 Windows 平台，无需模拟器或独立运行时进程。

**核心功能**:
- 通过 relinker 将 PS5 可执行文件转换为目标系统的原生格式
- 提供系统 prx 库的实现，支持动态链接
- 着色器重编译器可将着色器转换为 SPIR-V 格式
- 支持 SDL 映射的游戏手柄（含模拟摇杆和扳机），以及键盘鼠标配置

**技术亮点**: 采用重链接与原生动态链接方案而非模拟器架构；不依赖任何受版权保护的固件、密钥或专有库；遇到不支持状态时严格抛出 `std::runtime_error` 并终止进程；使用 GPLv2 许可证。

---
## 3. [storytold/artcraft](https://github.com/storytold/artcraft)
- **语言**: Rust
- **Stars**: 18,102
- **简介**: ArtCraft is an intentional crafting engine for artists, designers, and filmmakers

### AI 总结
**简介**: ArtCraft 是一款面向艺术家、设计师和电影制作人的交互式 AI 图像与视频创作 IDE，将提示词生成转变为可视化、可复现的创作过程。

**核心功能**:
- **图像到场景（Image to Location）**：在一致的环境中放置虚拟角色，并在同一空间中规划多个镜头
- **3D 图像合成**：在 3D 空间中分层背景、前景和道具，构建具有纵深感的构图
- **2D 图像合成**：通过图层、背景移除和绘图工具进行场景编排
- **图像转 3D 网格**：将图像转为可精确摆放、旋转和取景的 3D 对象
- **角色姿态控制**：在生成最终镜头前摆好角色姿势并设置相机
- **Kitbashing 场景布景**：组合 3D 资产套件来控制相机角度、物体位置和景深

**技术亮点**: 使用 Rust 语言开发；支持 2D 与 3D 双模式创作流程；可自由选择适配的 AI 模型；提供桌面端下载与源码构建方式。

---
## 4. [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design)
- **语言**: HTML
- **Stars**: 50,449
- **简介**: Editorial diagram design for Claude Code, Codex, GitHub Copilot, Cursor, Factory Droid, and Pi. 44 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop.

### AI 总结
**简介**: 一个为 AI 编程助手设计的 Agent Skill，能够用自包含的 HTML + SVG 生成编辑级品质的图表，支持 44 种图表类型，风格克制无阴影，拒绝 Mermaid 式的粗糙输出。

**核心功能**:
- 支持 44 种图表类型，涵盖架构图、象限图、时序图等常见需求
- 用自然语言向 Agent 描述需求即可生成图表，输出单个可双击打开的 `.html` 文件
- 可导入 draw.io、Mermaid、Excalidraw 文件，支持导出为 PNG / SVG
- 支持品牌定制，可抓取指定网站的配色和字体，让所有图表保持品牌一致
- 兼容 Claude Code、Codex、GitHub Copilot、Cursor、Gemini CLI、Cline、Windsurf 等多种 Agent Skills 宿主

**技术亮点**:
- 输出为自包含的 HTML + SVG，无需额外依赖，单个文件即可打开
- 通过 `npx skills add` 跨宿主安装，支持 symlink 统一管理多宿主副本
- Claude Code 提供插件市场安装方式，支持自动更新和 slash 命令
- 采用 Agent Skill 架构（`SKILL.md` + `references/` + `assets/` + `scripts/`），Agent 会先声明图表类型和方案再生成
- MIT 协议开源

---
## 5. [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view)
- **语言**: JavaScript
- **Stars**: 51,773
- **简介**: A spy satellite simulator in your browser, except the data is real. Live open source spatial intelligence on a photorealistic 3D globe.

### AI 总结
**简介**: God's Eye View 是一个运行在浏览器中的开源“间谍卫星模拟器”，以逼真的 3D 地球实时呈现航班、船舶、卫星、地震、交通和公共摄像头等真实公开数据。

**核心功能**:
- **驾驶舱视角**：进入被追踪航班的内部视角，镜头全程锁定下方地形。
- **点击即追踪**：锁定任意飞机、船只或火点，绘制渐隐轨迹并展示完整元数据，可一键跳转到最近的实时摄像头。
- **多源实时图层**：整合航班应答机、船舶信标、轨道元素、地震仪和公共摄像头数据，覆盖 250 公里范围内的所有目标。
- **语音交互与白板**：通过实时 AI 代理实现免手操作，可用语音在世界地图上绘制边界多边形、标记和路线。
- **3D 机库与传感器滤镜**：按机型加载真实 3D 模型（787、ATR-72、MQ-9 等），并支持 CRT、夜视、热成像、黑白等 GLSL 后处理效果。
- **天气与卫星过境**：动画展示 GFS/ECMWF 风场、雷达、云层和闪电，语音查询任意卫星的升起、过顶和落下时间。
- **分享链接**：相机、样式、图层和追踪目标可序列化为 URL，实现实时目标交接。

**技术亮点**: 基于 JavaScript 构建，采用模块化图层架构，每个数据源为独立模块；支持通过 Pinokio 一键安装或本地终端运行，无需 API 密钥即可启动，可选密钥在应用内添加；提供军事级 HUD、检测叠加层和场景导演等电影级视觉工具。

---
## 6. [pytorch/pytorch](https://github.com/pytorch/pytorch)
- **语言**: Python
- **Stars**: 104,523
- **简介**: Tensors and Dynamic neural networks in Python with strong GPU acceleration

### AI 总结
**简介**: PyTorch 是一个提供 GPU 加速张量计算与基于磁带式自动微分的动态神经网络构建能力的 Python 深度学习框架。

**核心功能**:
- **张量计算**：类似 NumPy 的张量库，支持强大的 GPU 加速，提供切片、索引、数学运算、线性代数、归约等丰富例程
- **动态神经网络**：基于磁带式（tape-based）自动微分系统构建深度神经网络，支持反向模式自动微分，网络行为可任意改变且无延迟或开销
- **模块化组件**：包含 `torch.autograd`（自动微分）、`torch.nn`（神经网络库）、`torch.multiprocessing`（跨进程内存共享的多进程）、`torch.utils`（DataLoader 等工具）

**技术亮点**:
- 采用磁带式自动微分（tape-based autograd）实现动态计算图，区别于 TensorFlow、Theano、Caffe 等静态图框架
- GPU 就绪的张量库，张量可驻留 CPU 或 GPU
- 支持与 NumPy、SciPy、Cython 等 Python 包无缝集成扩展
- Python 优先（Python First）的设计理念，提供命令式（Imperative）编程体验
- 支持 NVIDIA CUDA、AMD ROCm、Intel GPU 等多种硬件加速后端

---
## 7. [lyogavin/airllm](https://github.com/lyogavin/airllm)
- **语言**: Jupyter Notebook
- **Stars**: 36,537
- **简介**: AirLLM 70B inference with single 4GB GPU

### AI 总结
**简介**: AirLLM 是一个通过分层流式加载大幅降低推理显存占用的工具，可在单张 4GB 显卡上运行 70B 乃至 2.8T 参数的超大语言模型，无需量化、蒸馏或剪枝。

**核心功能**:
- 超大模型低显存推理：70B 模型仅需 4GB 显存，DeepSeek-V3 (671B) 约 12GB，Kimi K3 (2.8T) 仅 3.72GB，Qwen3-235B 约 3GB
- 小显存训练支持：冻结权重逐层流式加载，适配器保留在 GPU 上，Qwen3.8-27B 可在约 2GB 显存下训练
- 多模型与多平台兼容：支持 Llama 3.x/4、Qwen 系列、DeepSeek V2/V3、Phi-4、Gemma、ChatGLM、Mistral 等，并支持 CPU 推理与 MacOS
- 提供统一的 `AutoModel` 接口，自动识别模型类型，并支持 8bit/4bit 量化

**技术亮点**:
- 核心机制为分层流式加载（layer-by-layer streaming），将模型权重按层加载以复用显存
- 引入预取（prefetching）机制，重叠模型加载与计算以提升速度
- 针对 MoE 模型实现按专家流式加载，仅载入 token 实际路由到的专家
- 支持 FP8 模型、safetensors 及非分片模型，基于 PyTorch 与 HuggingFace transformers 生态

---
## 8. [chrislgarry/Apollo-11](https://github.com/chrislgarry/Apollo-11)
- **语言**: Assembly
- **Stars**: 74,281
- **简介**: Original Apollo 11 Guidance Computer (AGC) source code for the command and lunar modules.

### AI 总结
**简介**: 阿波罗11号制导计算机（AGC）指令舱与登月舱的原始汇编源代码仓库。

**核心功能**:
- 保存指令舱（Comanche055 / Colossus 2A）与登月舱（Luminary099 / Luminary 1A）的原始 AGC 源码
- 由 Virtual AGC 与 MIT 博物馆数字化转录，面向公众开放
- 接受 PR 修正转录与原始扫描件之间的差异，或补充遗漏文件

**技术亮点**: 使用 AGC 汇编语言编写，需借助 yaYUL 汇编器编译；代码属公有领域，附有合同与审批记录（含 Margaret H. Hamilton 署名），并提供 30 余种语言的 README 翻译。

---
