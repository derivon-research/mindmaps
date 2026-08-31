# 文件系统间接引用

文件系统间接引用把原始内容保存在可寻址文件中，而在上下文里只保留路径与恢复说明。需要细节时，Agent 可通过已有 `read_file` 工具重新取回。

它是一种存储位置变化，不包含摘要或语义压缩。无损恢复要求路径指向不可变快照、版本化内容，或任务期间受约束不变的数据源；只记录普通可变路径不足以恢复过去观察。

AFS 把间接引用扩展成统一资源命名空间：路径可指向远程云盘、日历或业务系统，不一定对应本地物理文件。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§7.1 与 §8.1，revision 2846；《[Context Offloading](../concept-context-offloading/index.html) 机制》“差异”，revision 145；《写给 Agent 的虚拟文件系统》§1-3，revision 216。
