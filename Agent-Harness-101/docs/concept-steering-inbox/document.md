# Steering Inbox

Steering Inbox 保存用户在 Workflow 运行途中发来的纠偏消息，脚本在检查点主动拉取并把新指令并入当前上下文。

来源用计划中的 `drainInbox()` 表达该机制：无消息时继续运行，有消息时及时转向，用户不必持续盯守。

来源：§6，revision 927，https://my.feishu.cn/wiki/ToaRw8BAUiAyFFkR3EAc05atnsg
