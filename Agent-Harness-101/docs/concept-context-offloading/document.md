# Context Offloading

Context Offloading 由 Harness 把可恢复的大参数或结果移出 `messages` 常驻区，只保留路径、大小和恢复说明；需要细节时，Agent 再通过文件工具按需读回。

第九章把它拆成两个独立时机：机制 A 在 [Tool Result](../concept-tool-result/index.html) 生成时保存不可重放输出，使原文从未进入 Context；机制 B 在窗口压力出现后追溯改写已消费且可稳定重获的历史参数或结果。它不新增 Agent 工具，也不改变 [ReAct Loop](../concept-react-loop/index.html)，但会改变消息历史表示。

示例占位符：`[OFFLOADED] saved to abc123.log ... Use read_file to retrieve.`

第二章补充了工程裁剪形式：超大输出可在 Context 中只留 head/tail 或路径，全文写盘，再由模型按需 grep/read 片段。

边界：路径只有在指向不可变快照、版本化对象或任务期间稳定的数据源时，才保证恢复历史观察；普通可变文件路径并非无条件无损。

来源：《从 ReAct Loop 讲起》§7，revision 2846；《模型之外的全部》§6.1，revision 297；《Harness 101：Context Offloading 机制》“生命周期”“差异”，revision 145。
