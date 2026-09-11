# Nudge

Nudge 是 Harness 在满足运行时条件时注入上下文的系统级提醒，又可表现为 `system-reminder`。它针对当前状态动态干预模型注意力，而不是只依赖任务开始时的静态 Prompt。

TODO 示例中，Harness 在最后一批 tool result 后检测到未完成任务时，追加更新计划的提醒，以降低模型忘记维护 TODO 的概率。

边界：Nudge 不是用户消息，也不是模型自行生成的 assistant 消息；它是 Harness 层的上下文补丁。

来源：同章 §5.4「补丁 B：每一步之后 nudge 一下」，revision 2846。
