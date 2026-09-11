# 主动停机

主动停机是 [ReAct Loop](../concept-react-loop/index.html) 的终止语义：模型在某轮不再发出 tool call，而是直接输出文本终态，Harness 据此退出循环。

这与 Workflow/DAG 的外部终点不同。ReAct 的步数和路径可事先未知，因为是否继续由模型当前判断决定；Harness 可另设 `MAX_ITERATIONS` 作为安全上限，但它不是任务完成判断。

来源：同章 §3.1 与 §4.3「谁决定 loop 什么时候停」，revision 2846。
