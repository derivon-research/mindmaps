# 两种机制组成 Offloading 生命周期

## 推导

[生成时主动卸载](../concept-generation-time-offloading/index.html)覆盖“结果从未进入 Context”的预防路径；[历史 Tool Result 回收](../concept-historical-tool-result-reclamation/index.html)覆盖“先消费、后回收”的追溯路径。二者按 payload 的可复现性和热度分工，合起来描述 [Offloading 生命周期](../concept-offloading-lifecycle/index.html)。

## 学习成本

权重 2.0：概念直接组合，但必须保持两条时间路径独立。

来源：同章“生命周期”“结语”，revision 145。
