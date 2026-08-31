# 输入匹配的结果缓存

输入匹配的结果缓存以 Agent 调用的 prompt 与 options 等输入识别已完成结果；Workflow 再次走到相同调用时直接返回缓存，编辑或新增调用才重跑。

本章把实现中的 key 观察性地称为 input hash，但不承诺具体序列化方式或哈希算法。

来源：§6.2，revision 1503；实现观察基于 Claude Code 2.1.215。
