# 在缓存过期后执行冷启动本地改写

## 推导

[Idle Gap Trigger](../concept-idle-gap-trigger/index.html) 判断旧服务端缓存不再值得保护；[追溯式消息改写](../concept-retroactive-message-rewriting/index.html)允许精简本地历史；[Thinking Block 回收](../concept-thinking-block-reclamation/index.html)释放额外推理块。三者共同形成[冷启动本地改写](../concept-cold-start-local-rewrite/index.html)。

## 学习成本

权重 3.0：需把缓存生命周期与客户端持久历史的不可逆变换协调起来。

来源：同章 §5.3-5.4，revision 173。
