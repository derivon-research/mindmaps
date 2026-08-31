# Parallel Barrier

Parallel Barrier 并发启动一组任务，并在下游需要全体结果时等待所有分支到达同步点，再返回等长结果集合。

单项失败可保留为 null，但 Barrier 仍让跨项判断明确知道哪些结果缺失。它适用于去重、排名、交叉验证、总编与发布决策。

来源：§3.3.1，revision 1503。
