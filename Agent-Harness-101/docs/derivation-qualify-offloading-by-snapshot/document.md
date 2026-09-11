# 生成时快照使大负载获得 Offloading 资格

## 推导

[大体积工具负载](../concept-large-tool-payload/index.html)值得回收；[文件系统持久状态](../concept-filesystem-persistence/index.html)可保存当时的完整输出。即使原工具不可重放，生成时快照也建立了可靠恢复路径，因此形成另一条 [Offloading 候选资格](../concept-offloading-eligibility/index.html)路线。

## 学习成本

权重 2.5：需区分“重跑工具”与“读取当时快照”。这是与稳定来源路线并行的替代推导。

来源：同章“生命周期：机制 A”“差异”，revision 145。
