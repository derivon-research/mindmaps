# 让 Item 沿 Pipeline 局部推进

[Item 局部推进](../concept-item-local-progression/index.html)允许单条任务完成一个 stage 后立刻向前；[代码控制流](../concept-code-control-flow/index.html)固定各 stage 的顺序和数据传递。两者结合形成无全局 Barrier 的 [Item Pipeline](../concept-item-pipeline/index.html)。

权重 2.0：这是 item 级并发与顺序 stage 的常规组合，关键是不要误加跨项等待。

来源：§3.3.2，revision 1503。
