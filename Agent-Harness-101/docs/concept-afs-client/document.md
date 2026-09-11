# AFSClient

AFSClient 是 Agent 侧统一入口，接受绝对路径并提供读、写、列举、编辑与搜索。来源不提供当前工作目录，以避免隐式 `cd` 状态跨调用漂移。

来源：同章 §4.1，revision 216。
