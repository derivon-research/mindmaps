# Cache Break 预期修正

Cache Break 预期修正是在主动裁掉缓存片段时，向监控逻辑登记下一轮 `cache_read_input_tokens` 的预期下降，避免把计划内减少误报为异常 Cache Miss。

它不证明缓存一定命中；真正观测仍须核对 usage 与错误信号。

来源：同章 §4.2-4.3，revision 173。
