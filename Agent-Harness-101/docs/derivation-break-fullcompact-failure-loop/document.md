# 熔断连续 Fullcompact 失败

## 推导

[Fullcompact](../concept-fullcompact/index.html) 是可自动重试的昂贵摘要步骤；[Fullcompact 失败](../concept-fullcompact-failure/index.html)说明输出契约未满足。若连续重复同一路径会形成无界调用循环，因此加入重试上限得到 [Compaction Circuit Breaker](../concept-compaction-circuit-breaker/index.html)。

## 学习成本

权重 2.0：直接应用通用熔断思想。

来源：同章 §2，revision 173。
