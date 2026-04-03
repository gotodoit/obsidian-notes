---
tags:
  - github-trending
  - daily
date: 2026-04-03
created: 2026-04-03T01:55:47.330Z
---

# 2026-04-03 GitHub Trending Top 4

## 1. [siddharthvaddem/openscreen](https://github.com/siddharthvaddem/openscreen)
- **语言**: TypeScript
- **Stars**: 15,999
- **简介**: Create stunning demos for free. Open-source, no subscriptions, no watermarks, and free for commercial use. An alternative to Screen Studio.

### AI 总结
**简介**: OpenScreen 是一款免费、开源的屏幕录制与演示制作工具，可作为 Screen Studio 的轻量级替代品，用于创建美观的产品演示和操作教程。

**核心功能**:
- 录制全屏或特定窗口
- 添加自动或手动缩放（可自定义深度）
- 录制麦克风和系统音频
- 自定义缩放时长与位置
- 裁剪视频以隐藏部分内容
- 选择壁纸、纯色、渐变或自定义背景
- 为平移和缩放效果添加运动模糊
- 添加注释（文本、箭头、图像）
- 剪辑视频片段
- 自定义不同片段的速度
- 以不同宽高比和分辨率导出

**技术亮点**: 基于 Electron、React、TypeScript、Vite、PixiJS 和 dnd-timeline 构建。

---
## 2. [Yeachan-Heo/oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex)
- **语言**: TypeScript
- **Stars**: 11,831
- **简介**: OmX - Oh My codeX: Your codex is not alone. Add hooks, agent teams, HUDs, and so much more.

### AI 总结
**简介**: OMX 是一个为 OpenAI Codex CLI 设计的工作流增强层，旨在通过添加标准化的提示、工作流和运行时辅助，提升 Codex 的使用体验。

**核心功能**:
- 提供标准工作流，包含 `$deep-interview`（澄清意图）、`$ralplan`（批准计划）、`$team`（并行执行）和 `$ralph`（持续完成）等核心技能。
- 支持项目引导和状态管理，将项目指导、计划、日志和状态存储在 `.omx/` 目录下。
- 允许通过 `AGENTS.md` 文件定义专家角色和支持技能，以适应复杂任务需求。

**技术亮点**:
- 基于 TypeScript 开发，要求 Node.js 20+ 环境。
- 作为 Codex 的补充层，不替换其执行引擎，而是增强其任务路由、工作流和运行时管理能力。
- 支持在 macOS/Linux 上使用 `tmux` 或在 Windows 上使用 `psmux` 来实现持久的团队运行时环境。

---
## 3. [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks)
- **语言**: Unknown
- **Stars**: 36,417
- **简介**: Extracted system prompts from ChatGPT (GPT-5.4, GPT-5.3, Codex), Claude (Opus 4.6, Sonnet 4.6, Claude Code), Gemini (3.1 Pro, 3 Flash, CLI), Grok (4.2, 4), Perplexity, and more. Updated regularly.

### AI 总结
**简介**: 一个持续收集并公开主流AI聊天机器人和编程助手（如ChatGPT、Claude、Gemini等）系统提示词（System Prompts）的开源仓库。

**核心功能**:
- **集中收集**：提取并整理了来自OpenAI（GPT-5.4/5.3、Codex）、Anthropic（Claude Opus/Sonnet）、Google（Gemini 3.1 Pro/3 Flash）、Grok、Perplexity等多个厂商及模型的系统提示词。
- **持续更新**：项目承诺定期更新，收录新模型和新版本，并欢迎社区提交拉取请求（PRs）。
- **结构化归档**：以清晰的Markdown表格形式组织内容，按厂商和模型版本分类，并提供历史及变体版本的折叠目录。

**技术亮点**: 该项目本身不涉及复杂的技术栈，其核心价值在于**逆向工程与信息聚合**，通过技术手段提取通常不对外公开的AI系统指令，为研究人员、开发者和爱好者提供了一个宝贵的、集中的参考数据集。

---
## 4. [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock)
- **语言**: Python
- **Stars**: 77,320
- **简介**: Hunt down social media accounts by username across social networks

### AI 总结
**简介**: 一个用于通过用户名在多个社交网络上查找社交媒体账户的 Python 工具。

**核心功能**:
- 支持在超过 300 个社交网站上搜索指定用户名。
- 提供命令行界面，支持同时搜索多个用户名，并可选择将结果保存为多种格式（JSON、CSV 等）。
- 支持使用 Tor 网络进行匿名查询，并可通过代理访问。

**技术亮点**: 基于 Python 开发，支持异步请求以提高搜索速度，并可通过 Docker 容器化部署。

---
