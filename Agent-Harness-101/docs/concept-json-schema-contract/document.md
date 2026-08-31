# JSON Schema 输出契约

JSON Schema 输出契约规定 Agent 中间结果必须具备哪些字段、类型、必填项和嵌套形状。

它强于“请返回 JSON”：JSON.parse() 只能证明语法合法，Schema 还能约束 ok 是否为布尔值、issues 是否存在以及每项字段是否完整。

来源：§3.2，revision 1503。
