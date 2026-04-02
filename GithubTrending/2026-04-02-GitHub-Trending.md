---
tags:
  - github-trending
  - daily
date: 2026-04-02
created: 2026-04-02T01:55:47.087Z
---

# 2026-04-02 GitHub Trending Top 7

## 1. [anthropics/claude-code](https://github.com/anthropics/claude-code)
- **语言**: Shell
- **Stars**: 101,273
- **简介**: Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands.

### AI 总结
**简介**: Claude Code 是一个基于终端的智能编码助手，能够理解代码库并通过自然语言命令帮助开发者执行任务、解释代码和处理 Git 工作流。

**核心功能**:
- 通过自然语言命令执行日常编码任务
- 解释复杂代码段
- 处理 Git 工作流（如提交、分支管理等）

**技术亮点**: 支持多平台安装（MacOS/Linux/Windows），提供插件系统扩展功能，并集成反馈收集机制。

---
## 2. [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice)
- **语言**: Python
- **Stars**: 34,485
- **简介**: Open-Source Frontier Voice AI

### AI 总结
**简介**: VibeVoice 是微软开源的前沿语音AI模型家族，包含文本转语音和自动语音识别两大核心能力。

**核心功能**:
- **VibeVoice-ASR**: 统一的语音转文本模型，支持单次处理长达60分钟的音频，生成带说话人、时间戳和内容的结构化转录，并支持用户自定义上下文，原生支持超过50种语言。
- **VibeVoice-TTS**: 长文本、多说话人文本转语音模型（注：TTS代码已从仓库移除，但相关技术报告和实时版本仍在）。
- **VibeVoice‑Realtime‑0.5B**: 实时文本转语音模型，支持流式文本输入和稳健的长语音生成。

**技术亮点**:
- 采用创新的**7.5 Hz超低帧率连续语音分词器**（声学和语义），在保持音频保真度的同时极大提升了长序列处理的计算效率。
- 基于**Next-Token Diffusion**框架，利用大语言模型进行语音生成。
- ASR模型已集成至 **Hugging Face Transformers** 库，并支持 **vLLM** 进行快速推理。

---
## 3. [google-research/timesfm](https://github.com/google-research/timesfm)
- **语言**: Python
- **Stars**: 12,184
- **简介**: TimesFM (Time Series Foundation Model) is a pretrained time-series foundation model developed by Google Research for time-series forecasting.

### AI 总结
**简介**: TimesFM 是 Google Research 开发的一个预训练时间序列基础模型，专注于时间序列预测任务。

**核心功能**:
- 提供预训练的时间序列预测基础模型，支持开箱即用的预测。
- 支持点预测和连续分位数预测，可输出均值及10%到90%的分位数。
- 支持协变量（通过 XReg）输入，以增强预测效果。
- 提供 PyTorch 和 Flax (JAX) 两种后端实现，以适应不同的部署和性能需求。

**技术亮点**:
- **解码器架构**: 采用仅解码器（decoder-only）的 Transformer 架构。
- **模型高效**: 最新 2.5 版本参数量为 2 亿，相比 2.0 版本的 5 亿参数更精简。
- **长上下文**: 支持高达 16K 的上下文长度，能处理更长的历史序列。
- **量化预测**: 通过一个可选的 3000 万参数分位数头，支持高达 1000 步预测范围的连续分位数输出。

---
## 4. [luongnv89/claude-howto](https://github.com/luongnv89/claude-howto)
- **语言**: Python
- **Stars**: 15,688
- **简介**: A visual, example-driven guide to Claude Code — from basic concepts to advanced agents, with copy-paste templates that bring immediate value.

### AI 总结
**简介**: 一个面向 Claude Code 的视觉化、示例驱动的学习指南，提供从基础概念到高级代理的完整学习路径和可直接复用的模板。

**核心功能**:
- 提供结构化的渐进式学习路径，包含 10 个教程模块，涵盖从基础命令到自定义代理团队等所有 Claude Code 功能。
- 提供大量可直接复制粘贴的生产级配置模板，包括斜杠命令、钩子脚本、MCP 配置和子代理定义等。
- 内置交互式自我评估和测验功能（如 `/self-assessment` 和 `/lesson-quiz`），帮助用户定位知识缺口并制定个性化学习计划。

**技术亮点**: 采用 Mermaid 图表进行可视化教学，帮助理解功能内部原理；项目与 Claude Code 版本保持同步（当前支持 v2.2.0）。

---
## 5. [axios/axios](https://github.com/axios/axios)
- **语言**: JavaScript
- **Stars**: 108,872
- **简介**: Promise based HTTP client for the browser and node.js

### AI 总结
**简介**: Axios 是一个基于 Promise 的、用于浏览器和 Node.js 的 HTTP 客户端库。
**核心功能**:
- 在浏览器中发送 XMLHttpRequests 请求
- 在 Node.js 中发送 HTTP 请求
- 支持 Promise API
- 拦截请求和响应
- 转换请求和响应数据
- 自动转换 JSON 数据
- 客户端支持防御 XSRF
**技术亮点**: 基于 Promise，提供简洁的 API，支持请求/响应拦截器，具备良好的浏览器和 Node.js 兼容性。

---
## 6. [openai/codex](https://github.com/openai/codex)
- **语言**: Rust
- **Stars**: 71,799
- **简介**: Lightweight coding agent that runs in your terminal

### AI 总结
**简介**: OpenAI Codex CLI 是一个轻量级的本地终端编码助手。

**核心功能**:
- 在终端中直接运行，提供 AI 驱动的编码辅助。
- 支持通过 npm 或 Homebrew 等包管理器全局安装。
- 可与 ChatGPT Plus/Pro/Team/Edu/Enterprise 订阅计划关联使用，也支持 API 密钥。

**技术亮点**: 使用 Rust 语言开发，提供跨平台（macOS, Linux）的预编译二进制文件。

---
## 7. [f/prompts.chat](https://github.com/f/prompts.chat)
- **语言**: HTML
- **Stars**: 156,066
- **简介**: f.k.a. Awesome ChatGPT Prompts. Share, discover, and collect prompts from the community. Free and open source — self-host for your organization with complete privacy.

### AI 总结
**简介**: 一个免费开源的、全球最大的开源 AI 提示词库，原名 Awesome ChatGPT Prompts，支持 ChatGPT、Claude、Gemini 等多种 AI 模型。

**核心功能**:
- **社区驱动的提示词库**: 提供海量精选提示词示例，用户可浏览、分享、发现和收集来自社区的提示词。
- **交互式学习资源**: 提供免费的交互式提示工程指南（25+章节）和面向儿童的互动游戏式学习平台。
- **私有化部署**: 支持完全私有的自托管部署，可自定义品牌、主题和身份验证（如 GitHub/Google/Azure AD）。

**技术亮点**: 项目本身为 HTML 项目，提供便捷的部署方式（如 `npx` 快速启动、Docker 支持），并与 Hugging Face 数据集同步，便于数据交换和集成。

---
