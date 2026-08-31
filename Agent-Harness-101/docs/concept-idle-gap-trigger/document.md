# Idle Gap Trigger

Idle Gap Trigger 根据距离上次 API 请求的空闲时间切换 Context 治理后端。来源报告 Claude Code 在超过 60 分钟后走[冷启动本地改写](../concept-cold-start-local-rewrite/index.html)路径。

60 分钟是实现参数，不是由 5 分钟 TTL 数学推出的唯一值；只要服务端缓存确定过期，就可重新评估本地重建策略。

来源：同章 §5.3，revision 173。
