# Journaled Replay

Journaled Replay 通过重新执行 [Workflow Script](../concept-workflow-script/index.html)，并在遇到输入相同的已完成 [agent() 调用](../concept-agent-call/index.html)时复用 Journal 结果，实现表面上的断点续接。

它不是 JavaScript VM、调用栈和堆内存快照。该名称是作者为讨论恢复机制采用的术语，不是 Anthropic 对外公开的 API 名称。

来源：§6，revision 1503。
