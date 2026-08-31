# Agent Result Journal

Agent Result Journal 在 Workflow 执行过程中记录各次 Agent 调用的 started 与已完成 result，使恢复时可以识别哪些计算已经付过成本。

Claude Code 官方只承诺会跟踪已完成 Agent 结果；journal.jsonl、LocalFileJournal 与具体字段是作者在 2.1.215 的实现观察，不应当作长期兼容协议。

来源：§6.1-6.2，revision 1503。
