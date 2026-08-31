# Context 预留预算

Context 预留预算是不能被历史工作记忆占满的窗口空间，用于 [System Prompt](../concept-system-prompt/index.html)、工具定义、当前轮输出、压缩调用本身以及下一次意外膨胀的 [Tool Result](../concept-tool-result/index.html)。

理论 [Context Window](../concept-context-window/index.html) 减去这些预留后，才是可用于历史的工作预算。若等到理论上限附近才压缩，可能连压缩请求本身都无法提交。

来源：同章“阈值：太晚触发的代价”，revision 145。
