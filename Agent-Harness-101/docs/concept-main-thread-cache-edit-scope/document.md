# Main Thread Cache Edit 范围

Main Thread Cache Edit 范围把服务端缓存裁剪的发起权限定在主 Agent 线程。来源给出的理由是 Forked [Sub-Agent](../concept-sub-agent/index.html) 具有独立后续缓存视图，并发修改共享前缀可能造成一致性和观测问题。

这是 Claude Code 的保守隔离策略，不等于所有多 Agent 缓存实现都必须如此。

来源：同章 §5.2，revision 173。
