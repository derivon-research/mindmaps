# Structured Output

Structured Output 是 Agent 通过专用提交工具交付、并由 Runtime 按 JSON Schema 校验的机器可消费结果。

形状不匹配时 Agent 留在 Loop 中修正；多次仍不合格则调用失败，而不是把“看起来像 JSON”的文本交给下游。面向人的最终报告仍可保留自由文本。

来源：§3.2，revision 1503；具体实现观察基于 Claude Code 2.1.215。
