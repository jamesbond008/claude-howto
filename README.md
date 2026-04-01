<picture>
  <source media="(prefers-color-scheme: dark)" srcset="resources/logos/claude-howto-logo-dark.svg">
  <img alt="Claude How To" src="resources/logos/claude-howto-logo.svg">
</picture>

<p align="center">
  <a href="https://github.com/trending">
    <img src="https://img.shields.io/badge/GitHub-🔥%20%231%20Trending-purple?style=for-the-badge&logo=github"/>
  </a>
</p>

[![GitHub Stars](https://img.shields.io/github/stars/luongnv89/claude-howto?style=flat&color=gold)](https://github.com/luongnv89/claude-howto/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/luongnv89/claude-howto?style=flat)](https://github.com/luongnv89/claude-howto/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-2.2.0-brightgreen)](CHANGELOG.md)
[![Claude Code](https://img.shields.io/badge/Claude_Code-2.1+-purple)](https://code.claude.com)

# 用一个周末掌握 Claude Code

从输入 `claude` 开始，到编排 agents、hooks、skills 和 MCP servers；这套资料提供可视化教程、可直接复制的模板，以及一条清晰的学习路径。

**英文原版：** [README.en.md](README.en.md) | **中文补充说明：** [README.zh-CN.md](README.zh-CN.md) | **中文交互学习页：** [zh-cn/index.html](zh-cn/index.html)

**[15 分钟快速上手](#15-分钟快速上手)** | **[不知道该从哪开始](#不知道该从哪开始)** | **[浏览功能目录](CATALOG.md)**

## 前端页面完整截图

[查看原图](assets/screenshots/claude-howto-study-full.png)

![Claude How To 中文交互学习页完整截图](assets/screenshots/claude-howto-study-full.png)

---

## 目录

- [问题在哪里](#问题在哪里)
- [Claude How To 如何解决这个问题](#claude-how-to-如何解决这个问题)
- [它是怎么运作的](#它是怎么运作的)
- [不知道该从哪开始](#不知道该从哪开始)
- [15 分钟快速上手](#15-分钟快速上手)
- [你可以用它做什么](#你可以用它做什么)
- [常见问题](#常见问题)
- [参与贡献](#参与贡献)
- [许可证](#许可证)

---

## 问题在哪里

你已经安装了 Claude Code，也试过几个提示词。然后呢？

- **官方文档会告诉你有哪些功能，但不会教你怎么把它们组合起来。** 你知道有 slash commands，却不知道怎么把它们和 hooks、memory、subagents 串成一个真正能节省数小时的工作流。
- **缺少明确的学习路径。** 是先学 MCP 还是先学 hooks？是先学 skills 还是先学 subagents？结果就是每个地方都只扫一眼，最后哪一个都没真正掌握。
- **示例太基础。** 一个 “hello world” 级别的 slash command，并不能帮你搭建一个生产级代码审查流程，更别说把 memory、专门代理和自动安全扫描一起用起来。

你实际上只用到了 Claude Code 很小的一部分能力，而且你甚至不知道自己错过了什么。

---

## Claude How To 如何解决这个问题

这不是另一份功能参考手册，而是一份**结构化、可视化、以示例驱动**的指南，目标是教你如何把 Claude Code 的每个核心能力真正用起来，并且今天就能把这些模板复制进自己的项目。

| | 官方文档 | 本指南 |
|--|---------------|------------|
| **形式** | 功能参考文档 | 带 Mermaid 图的可视化教程 |
| **深度** | 功能说明 | 原理与工作机制也讲清楚 |
| **示例** | 基础片段 | 可以直接落地的生产级模板 |
| **组织方式** | 按功能分散罗列 | 从入门到进阶的渐进式学习路径 |
| **上手方式** | 自行摸索 | 有时间预估的引导式路线图 |
| **自我评估** | 没有 | 有测验帮助你查缺补漏、定制路径 |

### 你会得到什么

- **10 个教程模块**，覆盖 Claude Code 的核心能力，从 slash commands 到自定义 agent 团队
- **可复制的配置模板**，包括 slash commands、`CLAUDE.md` 模板、hook scripts、MCP 配置、subagent 定义和完整 plugin bundle
- **Mermaid 图示**，帮助你理解每个能力在底层是怎么工作的，不只是知道“怎么用”，还知道“为什么这样用”
- **一条引导式学习路径**，帮助你在 11-13 小时内从新手进阶到重度使用者
- **内置自测能力**，可以直接在 Claude Code 里运行 `/self-assessment` 或 `/lesson-quiz hooks` 来找出自己的薄弱点

**[开始学习路线 ->](LEARNING-ROADMAP.md)**

---

## 它是怎么运作的

### 1. 先判断你的起点

先做 [self-assessment 自测](LEARNING-ROADMAP.md#-find-your-level)，或者直接在 Claude Code 中运行 `/self-assessment`。系统会根据你已经掌握的内容，给你一条更适合你的学习路线。

### 2. 按引导路径逐步学习

按顺序完成 10 个模块。每个模块都建立在前一个模块之上。你可以一边学，一边把模板直接复制到自己的项目里。

### 3. 把多个能力组合成工作流

真正的威力来自“组合使用”。你会学到如何把 slash commands + memory + subagents + hooks 接成自动化流水线，用来处理代码审查、部署流程和文档生成。

### 4. 随时测试你的理解程度

每学完一个模块，就运行 `/lesson-quiz [topic]`。测验会准确指出你漏掉了什么，帮助你快速补齐知识空白。

**[15 分钟快速上手](#15-分钟快速上手)**

---

## 已被 5,900+ 开发者使用

- **5,900+ GitHub stars**，来自每天都在用 Claude Code 的开发者
- **690+ forks**，说明很多团队已经开始按自己的流程改造这套指南
- **持续维护中**，会跟随每次 Claude Code 发布同步更新（当前版本：v2.2.0，2026 年 3 月）
- **社区驱动**，很多内容来自真实工作流的实践者贡献

[![Star History Chart](https://api.star-history.com/svg?repos=luongnv89/claude-howto&type=Date)](https://star-history.com/#luongnv89/claude-howto&Date)

---

## 不知道该从哪开始

先做自测，或者直接根据自己的水平选择起点：

| 等级 | 你已经能做到 | 建议从这里开始 | 时间 |
|-------|-----------|------------|------|
| **初学者** | 能启动 Claude Code 并进行对话 | [Slash Commands](01-slash-commands/) | 约 2.5 小时 |
| **中级** | 已经会用 `CLAUDE.md` 和自定义命令 | [Skills](03-skills/) | 约 3.5 小时 |
| **高级** | 已经配置过 MCP servers 和 hooks | [Advanced Features](09-advanced-features/) | 约 5 小时 |

**完整 10 模块学习路径：**

| 顺序 | 模块 | 等级 | 时间 |
|-------|--------|-------|------|
| 1 | [Slash Commands](01-slash-commands/) | Beginner | 30 分钟 |
| 2 | [Memory](02-memory/) | Beginner+ | 45 分钟 |
| 3 | [Checkpoints](08-checkpoints/) | Intermediate | 45 分钟 |
| 4 | [CLI Basics](10-cli/) | Beginner+ | 30 分钟 |
| 5 | [Skills](03-skills/) | Intermediate | 1 小时 |
| 6 | [Hooks](06-hooks/) | Intermediate | 1 小时 |
| 7 | [MCP](05-mcp/) | Intermediate+ | 1 小时 |
| 8 | [Subagents](04-subagents/) | Intermediate+ | 1.5 小时 |
| 9 | [Advanced Features](09-advanced-features/) | Advanced | 2-3 小时 |
| 10 | [Plugins](07-plugins/) | Advanced | 2 小时 |

**[查看完整学习路线图 ->](LEARNING-ROADMAP.md)**

---

## 15 分钟快速上手

```bash
# 1. 克隆这份指南
git clone https://github.com/luongnv89/claude-howto.git
cd claude-howto

# 2. 复制你的第一个 slash command
mkdir -p /path/to/your-project/.claude/commands
cp 01-slash-commands/optimize.md /path/to/your-project/.claude/commands/

# 3. 然后在 Claude Code 中输入：
# /optimize

# 4. 接着配置项目级记忆：
cp 02-memory/project-CLAUDE.md /path/to/your-project/CLAUDE.md

# 5. 安装一个 skill：
cp -r 03-skills/code-review ~/.claude/skills/
```

如果你想完成一套更完整的入门配置，下面是**1 小时核心搭建方案**：

```bash
# Slash commands（15 分钟）
cp 01-slash-commands/*.md .claude/commands/

# 项目记忆（15 分钟）
cp 02-memory/project-CLAUDE.md ./CLAUDE.md

# 安装一个 skill（15 分钟）
cp -r 03-skills/code-review ~/.claude/skills/

# 这个周末的目标：继续加上 hooks、subagents、MCP 和 plugins
# 按学习路线继续配置
```

**[查看完整安装参考](#installation-quick-reference)**

---

## 你可以用它做什么

| 使用场景 | 你会组合使用的能力 |
|----------|------------------------|
| **自动化代码审查** | Slash Commands + Subagents + Memory + MCP |
| **团队上手与规范统一** | Memory + Slash Commands + Plugins |
| **CI/CD 自动化** | CLI Reference + Hooks + Background Tasks |
| **文档生成** | Skills + Subagents + Plugins |
| **安全审计** | Subagents + Skills + Hooks（只读模式） |
| **DevOps 工作流** | Plugins + MCP + Hooks + Background Tasks |
| **复杂重构** | Checkpoints + Planning Mode + Hooks |

---

## 常见问题

**这是免费的吗？**  
是的。MIT 协议，永久免费。你可以在个人项目、公司项目或团队内部使用，只需遵守许可证要求。

**这个项目还在维护吗？**  
在持续维护中。它会跟随 Claude Code 的版本更新同步调整。当前版本是 v2.2.0（2026 年 3 月），兼容 Claude Code 2.1+。

**它和官方文档有什么区别？**  
官方文档更像功能参考；这份指南更像教程，强调图示、生产级模板和循序渐进的学习路线。两者是互补关系：先用这份指南学会怎么上手，再回官方文档查细节。

**完整学完要多久？**  
完整路径大约需要 11-13 小时。不过你在前 15 分钟就能获得实际收益，比如复制一个 slash command 模板并立刻试用。

**可以和 Claude Sonnet / Haiku / Opus 一起使用吗？**  
可以。所有模板都适用于 Claude Sonnet 4.6、Claude Opus 4.6 和 Claude Haiku 4.5。

**我可以参与贡献吗？**  
当然可以。请查看 [CONTRIBUTING.md](CONTRIBUTING.md)。我们欢迎新的示例、bug 修复、文档改进和社区模板。

**可以离线阅读吗？**  
可以。运行 `uv run scripts/build_epub.py` 就能生成包含全部内容和渲染图示的 EPUB 电子书。

---

## 现在就开始真正掌握 Claude Code

你已经装好了 Claude Code。你和高效率之间差的，往往不是模型本身，而是有没有一套正确的使用方法。这份指南提供了结构化路径、可视化解释和可直接复制的模板，帮助你把 Claude Code 真正用起来。

MIT 协议。永久免费。你可以直接 clone、fork，然后改造成自己的版本。

**[开始学习路线 ->](LEARNING-ROADMAP.md)** | **[浏览功能目录](CATALOG.md)** | **[15 分钟快速上手](#15-分钟快速上手)**
