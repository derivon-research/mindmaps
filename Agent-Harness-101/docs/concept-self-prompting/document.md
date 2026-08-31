# Self-prompting

Self-prompting 是让 Agent 根据本轮进展和验证结果，为自己生成下一轮要执行的 Prompt。它替代人手工判断“下一步该问什么”，让循环可以自行续接。

边界：Self-prompting 仍受目标、验收和预算约束；它不等于让 Agent 无边界生成任意新目标。

来源：同章 §1、§3 与 §5，revision 1389。
