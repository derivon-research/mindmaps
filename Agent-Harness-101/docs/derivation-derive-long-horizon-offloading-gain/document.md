# 从面积缩减得到 Offloading 长程净收益

## 推导

[累积 Context 面积](../concept-cumulative-context-area/index.html)给出常驻负载的时间累计成本；[Offloading 生命周期](../concept-offloading-lifecycle/index.html)把冷数据改为按需短暂驻留；[可回收 Context 占用](../concept-recoverable-context-occupancy/index.html)限定哪些数据能安全移走。当多数冷数据不再重载时，累计节省超过写盘与少量读回成本，形成 [Offloading 长程净收益](../concept-long-horizon-offloading-gain/index.html)。

## 学习成本

权重 3.5：需要跨越单 Turn 直觉，比较整条时间线上的常驻面积与重载成本。

来源：同章“错觉”“生命周期”“结语”，revision 145。
