# Offloading 长程净收益

Offloading 长程净收益来自多数冷 payload 在卸载后不再被读取，使省下的累计 Context 面积超过首次写盘、按需读回和额外工具轮次的成本。

它不承诺单 Turn 更省 token，也不等于无限 Context；当重载频率很高、引用难以发现或外部存储延迟很大时，净收益可能缩小甚至为负。

来源：同章“错觉”“结语”，revision 145。
