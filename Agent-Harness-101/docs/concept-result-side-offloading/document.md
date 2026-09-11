# 结果侧 Offloading

结果侧 Offloading 把大 [Tool Result](../concept-tool-result/index.html) 的原文换成可恢复引用。不可重放的输出应在生成时先保存快照；已有稳定来源的读取结果可在变旧后直接恢复为来源引用。

结果侧策略不能只按体积决定：它还要检查结果是否已被当前推理消费、恢复来源是否稳定、权限是否仍有效，以及替换是否保留调用绑定。

来源：同章“差异：results 维度”，revision 145。
