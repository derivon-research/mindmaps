# Workflow State

Workflow State 是 loop 执行途中积累的变量与外部持久数据，例如 `quick`、`plan`、`results`、`report` 和 `revision`。

它位于对话上下文之外，因此不依赖某一次模型调用或单次会话，可被暂停后的执行或另一个进程继续读取。

来源：§5，revision 927，https://my.feishu.cn/wiki/ToaRw8BAUiAyFFkR3EAc05atnsg
