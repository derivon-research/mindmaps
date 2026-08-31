# 参数侧 Offloading

参数侧 Offloading 把历史 [Tool Call](../concept-tool-call/index.html) 中体积很大的数据参数替换成外部引用，同时保留工具名、目标与审计所需的小参数。

典型例子是 `write_file(path, content)`：写入完成后，`content` 已在 `path` 对应的持久对象中，历史副本是冗余；普通 Shell 命令、路径和 URL 很小且有审计价值，不应统一裁掉。

来源：同章“差异：args 维度”，revision 145。
