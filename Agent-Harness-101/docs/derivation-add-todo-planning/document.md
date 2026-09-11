# 多轮 ReAct 加 TODO 状态得到 Plan-then-Act

## 推导

纯[多轮 ReAct](../concept-multiround-react/index.html) 提供逐步行动，却可能缺少全局覆盖。把可更新 [TODO 状态](../concept-todo-state/index.html)加入同一 Loop，并在 [System Prompt](../concept-system-prompt/index.html) 中要求先写计划、再执行与维护，模型就能在局部行动之外保留一份全局任务视图，形成 [Plan-then-Act](../concept-plan-then-act/index.html)。

TODO 不是替代 Loop 的外部 DAG；它是 Loop 中模型可读写的执行状态。

## 学习成本

权重 2.5：需要理解状态工具如何改变模型行为，但实现只增加一个工具与一段协议提示。

来源：同章 §4.4、§5.1-5.2，revision 2846。
