# Skill 元数据目录

[Skill](../concept-skill/index.html) 元数据目录是 Harness 启动时扫描各 `SKILL.md` frontmatter 后生成的能力清单。每项只包含名称、描述和正文路径，并被注入 [System Prompt](../concept-system-prompt/index.html)，使模型每轮都能看到可用能力。

目录不是 [Skill 正文](../concept-skill-body/index.html)；它承担低成本常驻发现入口。描述字段需要让模型在推理链中识别何时应加载对应能力。

来源：同章 §8.1-8.2，revision 2846。
