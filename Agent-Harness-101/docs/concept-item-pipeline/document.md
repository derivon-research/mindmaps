# Item Pipeline

Item Pipeline 让每个 item 独立流过多个顺序 stage；条目完成一个 stage 就立即向前，不设置全局 Barrier。

后续 stage 可同时得到上一阶段结果、原始 item 和 index。它适合逐项转换、审查、修复和复验。

来源：§3.3.2，revision 1503。
