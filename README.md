# Xuanqing Xiaohongshu Traffic Hacker Skill

玄清小红书爆款专家是一个 Codex Skill，用于把原始选题、笔记草稿、图文草稿或营销内容重构成更适合小红书发布的版本。

默认输出：

- 5 个高点击标题
- 一篇可直接发布的小红书正文
- 6-10 个小红书标签

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
## 标题

1. ...
2. ...
3. ...
4. ...
5. ...

## 正文

...

## 标签

#... #... #...
```

## Files

- `SKILL.md`: main skill instructions
- `agents/openai.yaml`: UI metadata for Codex skill discovery
- `references/reconstruction-sop.md`: optional deeper SOP for full workflow requests

## Ownership

This skill is branded as 玄清 / Xuanqing.

Copyright (c) 2026 Xuanqing. All rights reserved.
