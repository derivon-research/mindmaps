# Sandbox

Sandbox 是限制 Agent 代码和命令执行影响范围的隔离环境。来源列出的核心控制包括命令 allow/deny list、默认网络隔离与按会话创建的干净容器。

Sandbox 不是 Tool description 的文字提醒，而是 Harness 在执行层实施的确定性边界。

第十一章补充选型边界：只需要结构化 I/O 的 Agent 可先使用 AFS 一类窄接口；需要语言执行或任意工具链时再叠加相应强度的 Sandbox。AFS 不替代执行隔离。

来源：《模型之外的全部》§5.3，revision 297；《写给 Agent 的虚拟文件系统》§2、§5，revision 216。
