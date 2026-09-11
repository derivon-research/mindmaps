# Stop Hook、Session Reset 与磁盘状态构成 Ralph Loop

[Hook](../concept-hook/index.html) 拦截尚未完成时的退出；[Session Reset](../concept-session-reset/index.html) 提供干净 Context；[文件系统持久状态](../concept-filesystem-persistence/index.html)让新会话恢复进度。三者合起来，任务可以跨多个上下文持续推进，而不是依赖一个无限增长的会话。

权重 3.5：非显然之处是把“持续执行”建立在反复重启和外置状态上，而不是保持同一上下文。

来源：同章 §6.2，revision 297。
