# 用分叉缓存一致性限定 Cache Edit 范围

## 推导

[Sub-Agent](../concept-sub-agent/index.html) 会形成独立后续请求分支；`cache_edits` 改变服务端可见缓存；[Prompt 前缀稳定性](../concept-prompt-prefix-stability/index.html)要求各分支对共享前缀有一致预期。为避免并发分支互相改变缓存视图，来源选择只让 Main Thread 发起 Cache Edit。

## 学习成本

权重 3.0：需同时理解 Agent 分叉和缓存视图一致性。

来源：同章 §5.2，revision 173。
