---
name: example-skill
description: 用于演示的示例技能
invocation: /example
---
# 示例技能

当用户调用 `/example` 时，用友好的问候进行回复，并说明这是一个从 `workspace/skills` 目录加载的演示技能。

你可以在 `workspace/skills/` 下新增一个目录，并在其中放置包含 frontmatter（`name`、`description`、`invocation`）和指令内容的 `SKILL.md` 文件，以创建你自己的技能。
