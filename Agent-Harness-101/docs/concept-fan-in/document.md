# Fan-in

Fan-in 是多个 [Sub-Agent](../concept-sub-agent/index.html) 完成后把结果汇聚到同一 [Orchestrator](../concept-orchestrator/index.html)，由它统一合并、处理冲突、更新 Memory 并决定下一步。

Fan-in 让并行产出重新回到一个目标和验收面，避免“散出去之后无人收口”。

来源：同章 §3.2 与 §6，revision 1389。
