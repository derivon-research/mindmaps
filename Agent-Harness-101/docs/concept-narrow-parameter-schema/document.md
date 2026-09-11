# 收窄参数 Schema

收窄参数 Schema 把自由 query 拆成有语义字段，使用 enum、required 和 additionalProperties: false 限制可生成空间。

它减少参数层自由度，但仍需描述字段真实含义和业务边界。

来源：§7.2-7.4，revision 167。
