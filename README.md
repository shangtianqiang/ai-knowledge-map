# AI 大模型知识地图

> 一套中文 AI 知识手册：**18 个专题页 + 42 个术语速查**，从"怎么问"到"怎么动手"，给想用好 AI 的人的一份中文地图。

[![在线预览](https://img.shields.io/badge/在线预览-GitHub%20Pages-2B8A3E?style=for-the-badge&logo=githubpages)](https://shangtianqiang.github.io/ai-knowledge-map/)
[![License: MIT](https://img.shields.io/badge/License-MIT-D6409F?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![页面](https://img.shields.io/badge/专题-18-4D6BFE?style=for-the-badge)](https://shangtianqiang.github.io/ai-knowledge-map/)
[![术语](https://img.shields.io/badge/术语-42%2B-FF6B35?style=for-the-badge)](https://shangtianqiang.github.io/ai-knowledge-map/)

## 在线预览

**👉 点击进入：[https://shangtianqiang.github.io/ai-knowledge-map/](https://shangtianqiang.github.io/ai-knowledge-map/)**

无需安装、无需注册，打开即读。也可以把整个仓库下载到本地，双击 `index.html` 离线阅读——所有页面都是**单文件、零依赖、可离线**的。

---

## 这是什么

这是一份**独立学习指南**，用一页一个专题的方式，把当下大模型与 AI Agent 领域最核心的概念讲清楚：

- 它是什么、怎么"想"（大模型、思维链）
- 你怎么"问"（Prompt 工程）
- 它会怎么"错"（幻觉）、知识怎么"补"（RAG）
- 从"会说"到"会做"（Agent、Skill、MCP、Harness）
- 真实的开源实现与产品（DeepSeek Harness、飞书 CLI）
- 主修之后，按角色选修进阶专题：定制、安全、感官、记忆、协作、选型与职业

每个专题约 **5–10 分钟**读完，页面之间通过页脚互链，随时可以回到地图主页或跳到相邻专题。

## 项目特色

- **体系化**：18 个专题不是孤立的名词解释，而是一条有先后顺序的学习路径——先打基础，再学动手，最后看真实产品。
- **单文件、零依赖**：每个页面都是独立的 HTML，内联全部 CSS、JavaScript 与 SVG 图标，不引用任何外部资源，断网也能完整阅读。
- **内容可追溯**：内容整理自官方文档、论文与权威媒体，每个专题页底部都有"来源与延伸阅读"，第三方说法均标注"本站未复测"。
- **响应式 + 可打印**：适配手机、平板与桌面，也支持直接打印成 PDF。
- **克制的视觉**：统一的设计语言、舒适的排版、清晰的层级，没有广告、没有弹窗追踪。

---

## 学习路径 · 主修 11 课

建议按 `01 → 11` 的顺序阅读，顺序是经过设计的：

| 编号 | 专题 | 一句话说明 | 时长 |
|:---:|:---|:---|:---:|
| 01 | [什么是大模型](什么是大模型.html) | 本职只有"预测下一个词"，规模够大后涌现出一切能力 | ≈6 min |
| 02 | [什么是思维链](什么是思维链.html) | 把中间步骤写出来再作答，如今长成了"推理模型"整个品类 | ≈6 min |
| 03 | [什么是 Prompt 工程](什么是Prompt工程.html) | 提示词不是咒语，是你与模型的接口规范 | ≈7 min |
| 04 | [什么是幻觉](什么是幻觉.html) | 流畅、自信、错误——只能管理，不能根除 | ≈6 min |
| 05 | [什么是 RAG](什么是RAG.html) | 让模型开卷考试：先检索资料，再作答，答案有出处 | ≈6 min |
| 06 | [什么是 AI Agent](什么是Agent.html) | 给目标不给步骤，自己规划、调用工具、根据反馈纠错 | ≈6 min |
| 07 | [什么是 Skill](什么是Skill.html) | 给 Agent 的操作手册，让团队手艺变成可分发的资产 | ≈6 min |
| 08 | [什么是 MCP](什么是MCP.html) | AI 应用的"USB-C"，让工具与数据即插即用 | ≈6 min |
| 09 | [什么是 Agent Harness](什么是AgentHarness.html) | 包在模型外面的运行时骨架，模型负责聪明，它负责可靠 | ≈7 min |
| 10 | [什么是 DeepSeek Harness](什么是DeepSeekHarness.html) | "Everything is a Plugin"，当代开源 Agent 框架样本 | ≈7 min |
| 11 | [什么是飞书 CLI](什么是飞书CLI.html) | 给 Agent 装上飞书的手，一行命令读消息、写文档、查日历 | ≈6 min |

## 进阶专题 · 7 个方向

主修之后，按角色与兴趣选修，**不设先后、按需取用**：

| 编号 | 专题 | 方向 | 一句话说明 | 时长 |
|:---:|:---|:---:|:---|:---:|
| 12 | [什么是微调](什么是微调.html) | 定制 | 在预训练模型上继续训练，改的是行为与风格 | ≈6 min |
| 13 | [什么是提示注入](什么是提示注入.html) | 安全 | 把恶意指令藏进 AI 会读的内容里，Agent 时代头号威胁 | ≈6 min |
| 14 | [什么是多模态](什么是多模态.html) | 感官 | 把图像、音频、视频都切成 token 的统一架构 | ≈6 min |
| 15 | [什么是记忆](什么是记忆.html) | 长期 | 窗口是工作台，记忆是抽屉，让 AI 跨会话记住你 | ≈6 min |
| 16 | [什么是多智能体](什么是多智能体.html) | 协作 | 主 Agent 拆解派发、子 Agent 并行执行 | ≈6 min |
| 17 | [AI 工具怎么选](什么是AI工具选择.html) | 实战 | 四大品类、国内外双生态，先场景、后约束、再试跑 | ≈7 min |
| 18 | [什么是 FDE](什么是FDE.html) | 角色 | 前沿部署工程师，把自己部署到客户身边的工程师 | ≈6 min |

## 术语速查

主页内置 **42 个术语**，按主题分为 6 组，适合当工具书随时翻；带下划线的词已有专题页，点击可直接深入：

- **模型本体**（8 词）：Token、上下文窗口、预训练/微调、RLHF、MoE、蒸馏、量化……
- **模型行为**（6 词）：温度、Top-P、幻觉……
- **知识接入**（5 词）：RAG、向量数据库、Embedding……
- **Agent 与工具**（10 词）：Agent、Skill、MCP、Harness、Function Calling、ReAct……
- **推理与评测**（8 词）：思维链、推理模型、测试时算力……
- **产品与运行**（5 词）：系统提示词、上下文工程……

---

## 快速开始

### 方式一：在线阅读（推荐）

直接访问 GitHub Pages：

```
https://shangtianqiang.github.io/ai-knowledge-map/
```

### 方式二：本地离线阅读

把仓库克隆到本地，直接用浏览器打开主页即可，无需任何服务器：

```bash
git clone https://github.com/shangtianqiang/ai-knowledge-map.git
cd ai-knowledge-map
# 双击 index.html，或用命令打开
start index.html
```

### 方式三：启动本地服务器（可选）

如果希望获得与线上一致的体验，可以启动一个静态服务器：

```bash
# Python 3
python -m http.server 8000
# 然后访问 http://localhost:8000
```

---

## 目录结构

```
ai-knowledge-map/
├── index.html                  # 知识地图主页（学习路径 + 术语速查）
├── 什么是大模型.html            # ┐
├── 什么是思维链.html            # │
├── 什么是Prompt工程.html        # │
├── 什么是幻觉.html              # │
├── 什么是RAG.html              # │  主修 11 课
├── 什么是Agent.html            # │  （01–11）
├── 什么是Skill.html            # │
├── 什么是MCP.html              # │
├── 什么是AgentHarness.html     # │
├── 什么是DeepSeekHarness.html  # │
├── 什么是飞书CLI.html           # ┘
├── 什么是微调.html              # ┐
├── 什么是提示注入.html          # │
├── 什么是多模态.html            # │  进阶 7 专题
├── 什么是记忆.html              # │  （12–18）
├── 什么是多智能体.html          # │
├── 什么是AI工具选择.html        # │
├── 什么是FDE.html              # ┘
├── assets/
│   └── wechat-qrcode.jpg       # 公众号二维码
└── README.md
```

## 技术说明

- **纯静态站点**：无需构建工具、无需后端、无需数据库，任何静态托管平台（GitHub Pages / Vercel / Netlify / 对象存储）都能直接部署。
- **内联资源**：CSS、JavaScript、SVG 图标全部内联，单个 HTML 文件即可独立运行，也便于分发与存档。
- **渐进增强**：在禁用 JavaScript 的情况下，核心内容依然完整可读。
- **无障碍**：语义化标签、键盘可达、尊重 `prefers-reduced-motion`。

---

## 内容来源与免责声明

本项目是一份**独立学习指南**：

- 所有内容整理自官方文档、公开论文与权威媒体，并在每个专题页底部列出"来源与延伸阅读"。
- 本项目与所提及的各家公司**没有关联，也不构成任何背书**。
- 第三方说法均标注"本站未复测"；AI 领域发展迅速，部分内容可能随时间变化，请以官方信息为准。
- 如有疏漏或引用不当，欢迎提交 Issue 指正。

## 关注作者

全网同名「**大话数据分析**」，分享数据、分析与 AI 实战：

- **GitHub**：[shangtianqiang](https://github.com/shangtianqiang)
- **知乎**：[@大话数据分析](https://www.zhihu.com/people/xin-cheng-jiu-meng-98)
- **小红书**：[大话数据分析](https://www.xiaohongshu.com/user/profile/609ff36a0000000001007360)
- **今日头条**：[大话数据分析](https://www.toutiao.com/)
- **CSDN**：[大话数据分析](https://blog.csdn.net/weixin_42684533)
- **微信公众号**：「大话数据分析」（点击任意页面页脚的微信图标，可扫码关注）

## License

本项目基于 [MIT License](https://opensource.org/licenses/MIT) 开源，欢迎学习、转载与二次分发，请注明出处。

---

<p align="center">如果这个项目对你有帮助，欢迎点一个 ⭐ Star，这是对我最大的鼓励。</p>
