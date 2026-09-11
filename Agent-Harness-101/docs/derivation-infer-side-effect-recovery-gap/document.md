# 从返回值 Replay 推断副作用缺口

[Journaled Replay](../concept-journaled-replay/index.html) 只承诺复用已完成 Agent 返回值；它没有附带文件或外部系统的事务回滚保证。因此恢复时，未完成 Agent 先前留下的部分副作用可能仍存在，形成[副作用恢复缺口](../concept-side-effect-recovery-gap/index.html)。

权重 2.5：这是作者基于官方边界和本机实现作出的谨慎推断，不是 Anthropic 官方承诺。边文档明确保留该不确定性。

来源：§6.3，revision 1503。
