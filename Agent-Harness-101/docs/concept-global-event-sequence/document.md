# 全局事件序列

全局事件序列为同一 Runner 内多个并发 Workflow 的事件分配共享、单调递增的 sequence。

各运行上下文保持隔离，宿主仍可用序列号还原跨运行事件的实际发生顺序。

来源：§4.5，revision 1503；描述 Deer Workflow 开源实现。
