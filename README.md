<h1 align="center">heidegger.skill</h1>

<p align="center">海德格尔 · Martin Heidegger</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“语言是存在之家。”<br>— 海德格尔 · <a href="https://www.beyng.com/pages/de/GA09/GA09.313.html">〈关于人道主义的书信〉</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将器具关联、技术显现与有限性整理为思想分析 Skill，让 AI 从人正在做的事和使用的东西出发，检查技术安排如何使世界成为可供调度的资源。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 工具坏掉时，我才注意到它，这能说明什么？

> 平时你关心的是正在进行的工作，工具嵌在用途与配合关系里。失灵使这些关系显出来；这是一条理解日常经验的线索，不是“所有物体都由意识制造”的证据。

### 2. 把员工称为可调度资源，只是换个词吗？

> 要看实际安排，而不只看称呼：人的时间、能力与关系是否只能以可储备、可替换的数量出现？同时检查排班的具体用途与其他解释；采用数字工具本身并不足以证明这种变化已经发生。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 器具关联 | 把对象放回用途、活动和共同生活的关联中。 |
| 技术显现 | 比较事物的实际用途与被储备、计算、调度的方式。 |
| 有限性辨析 | 分开生理预测、第一人称承担与他人照护。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/heidegger-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `heidegger-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/heidegger-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：** “用海德格尔的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：** 明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

《存在与时间》器具关联与有限性选段；〈技术的追问〉选段。开篇引文另核〈关于人道主义的书信〉。

- [原作来源、版本与实际阅读范围](source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://www.beyng.com/pages/de/GA09/GA09.313.html">〈关于人道主义的书信〉</a>，全集第 9 卷，第 313 页。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
