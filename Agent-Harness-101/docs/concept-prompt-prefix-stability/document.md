# Prompt 前缀稳定性

Prompt 前缀稳定性指连续请求保持相同早期消息，使依赖前缀匹配的 Prompt Cache 能复用计算。追溯改写旧历史会改变前缀，可能导致缓存失效。

因此过早、频繁 Compaction 不只增加压缩调用，还可能牺牲缓存收益。具体折扣、TTL 和匹配规则属于供应商实现，必须按当时文档验证。

第十章报告 Claude Code 通过 `cache_edits` 让服务端隐藏部分 [Tool Result](../concept-tool-result/index.html)，而客户端保留完整历史，以减少普通历史改写造成的缓存破坏。该协议细节仍需按官方 API 契约独立验证。

来源：《[Context Offloading](../concept-context-offloading/index.html) 机制》“阈值”，revision 145；《Claude Code 的三种上下文压缩与 [Microcompact](../concept-microcompact/index.html) 的秘密》§4，revision 173。
