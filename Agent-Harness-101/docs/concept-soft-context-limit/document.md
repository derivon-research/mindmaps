# Soft Context Limit

Soft Context Limit 是 Harness 暴露给内部预算策略的可用上限，低于模型的物理 Hard Limit。两者之间的差额就是输出、压缩和突发负载的应急空间。

它不是固定百分比：工具返回方差越大、最大输出越长、压缩调用越重，Soft Limit 应越保守。

来源：同章“阈值：三条工程建议”，revision 145。
