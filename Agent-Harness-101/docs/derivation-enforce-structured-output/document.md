# 强制 Structured Output

agent() 提供可多轮修正的执行者，[JSON Schema 输出契约](../concept-json-schema-contract/index.html)给出字段和类型要求，[机器可判定信号](../concept-machine-checkable-signal/index.html)让 Runtime 能明确判断是否通过。三者共同形成 [Structured Output](../concept-structured-output/index.html)：不合格时继续修正或失败，合格后才交给 JavaScript。

权重 2.5：这是稳定中间接口的常规构造；三个尾点分别贡献执行、契约与判定。

来源：§3.2，revision 1503；具体工具注入方式基于 Claude Code 2.1.215。
