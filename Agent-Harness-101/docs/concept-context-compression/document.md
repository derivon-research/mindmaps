# Context Compression

Context Compression 是窗口压力下改写旧历史以降低占用的总类。它既可先做可恢复 payload 的无损回收，也可在更高压力下对旧轨迹做有损摘要。

早期章节把 Compression 窄化为整段摘要，用来与“payload 产生时 Offloading”对比；第九章补充了机制 B：Compression 触发器也可以追溯回收历史 [Tool Result](../concept-tool-result/index.html)。因而应区分触发阶段与具体操作，不能把所有 Compression 都等同于 summarize。

第二章补充了连续 compaction 的限制：摘要会累积信息损失，极长任务可能需要 [Session Reset](../concept-session-reset/index.html)，并从 [Handoff 文件](../concept-handoff-file/index.html)恢复，而不是无限次继续压缩。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§7.2，revision 2846；《模型之外的全部》§6.1，revision 297；《Harness 101：[Context Offloading](../concept-context-offloading/index.html) 机制》“生命周期”“阈值”，revision 145。
