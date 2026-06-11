# Xuanqing Xiaohongshu Traffic Hacker Skill

玄清小红书爆款专家是一个 Codex Skill，用于把原始选题、笔记草稿、图文草稿或营销内容重构成更适合小红书发布的版本。

默认输出：

- 1 个最终标题
- 一篇可直接发布的小红书正文
- 6-10 个小红书标签
- 严格 `<COPY_TEXT>` 标签格式，方便数据库录入

## What It Does

This skill rewrites Xiaohongshu/RedNote content from a traffic-hacker perspective. It focuses on:

- click-worthy titles
- reader-relevant angles
- emoji-led paragraph anchors
- publish-ready prose
- Xiaohongshu-style hashtags
- compact output within platform-friendly length

It is designed for content creators, operators, founders, consultants, and personal-brand builders who want to turn rough ideas into sharper Xiaohongshu notes.

## Installation

Clone this repository directly into your Codex skills directory:

```bash
git clone https://github.com/<your-name>/xuanqing-xhs-traffic-hacker.git ~/.codex/skills/xuanqing-xhs-traffic-hacker
```

Or copy the folder manually:

```bash
cp -R xuanqing-xhs-traffic-hacker ~/.codex/skills/
```

## Usage

Invoke the skill explicitly:

```text
Use $xuanqing-xhs-traffic-hacker to rewrite this Xiaohongshu draft: ...
```

You can also ask in Chinese:

```text
用玄清小红书爆款专家重构这篇笔记：...
```

## Output Format

```text
<COPY_TEXT>
<TITLE>
Day 01 每天吃透一个AI知识点｜MCP
</TITLE>

<BODY>
这里是正文内容……
</BODY>

<TAGS>
#MCP #AI知识科普 #人工智能 #AI工具
</TAGS>
</COPY_TEXT>
```

## Files

- `SKILL.md`: main skill instructions
- `agents/openai.yaml`: UI metadata for Codex skill discovery
- `references/reconstruction-sop.md`: optional deeper SOP for full workflow requests

## Ownership

This skill is branded as 玄清 / Xuanqing.

Copyright (c) 2026 Xuanqing. All rights reserved.
