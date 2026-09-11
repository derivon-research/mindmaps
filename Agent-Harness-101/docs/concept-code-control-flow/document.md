# 代码控制流

代码控制流用普通程序语义表达阶段先后、异步并行、同步等待、循环上限和[条件分支](../concept-conditional-branch/index.html)。

在 [Dynamic Workflow](../concept-dynamic-workflow/index.html) 中，这部分不依赖模型临场发挥：Quick Search 必定先于 Planning，`Promise.all` 固定并行汇合，`while` 与 `if` 明确回炉和退出条件。

第五章扩展机械控制流范围：去重、精确排序、数学与传统算法、数量检查、重试上限、并发等待和结果传递都应优先留在代码；语义权衡才进入 Agent。

来源：《[Loop Engineering](../concept-loop-engineering/index.html)—从 ReAct 到 Orchestration》§2、§4.2 与 §8，revision 927；《复刻 Dynamic Workflow》§2.1 与 §5.2，revision 1503。
