# cache_edits

`cache_edits` 是来源报告的 Anthropic 协议字段：客户端提交要隐藏的 [Tool Call](../concept-tool-call/index.html)/Result 标识，服务端在已有缓存视图中移除其可见内容，同时尽量保留其余前缀缓存复用。

本地 `messages` 不随热路径修改；服务端缓存视图发生变化。该字段的精确公开契约、可编辑块和哈希行为未在本导入中通过官方文档独立验证，因此不能外推为通用 API 保证。

来源：同章 §4，revision 173；证据状态：来源源码/usage 观察报告。
