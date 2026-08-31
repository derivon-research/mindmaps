# Coding Agent 工具集

本章的最小 [Coding Agent](../concept-coding-agent/index.html) 工具集由 `read_file`、`write_file` 与 `bash` 构成：分别读取源码、写入修改和运行命令或测试。

它不是所有 Coding Agent 的完整工具目录，而是说明“工具选择塑造 Agent 形态”所需的最小示例。更成熟系统可加入 edit、glob、grep、版本控制等能力。

第十一章补充：文件 I/O 可下沉为 AFS 共享底座，Shell 与任意工具链则由 [Sandbox](../concept-sandbox/index.html) 按任务需要叠加；两者无需绑定成不可拆分的一套。

第十二章给出 Managed Agent 产品快照：WebSearch/WebFetch、Glob/Grep、Read/Write/Edit 与 Bash 共八类，并强调探索、定位、修改、验证的组合顺序。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§6.1，revision 2846；《写给 Agent 的虚拟文件系统》§5，revision 216；《Claude Code Agent 里的常用工具一览》§1-12，revision 310。
