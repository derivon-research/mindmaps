# Microcompact

Microcompact 是来源对 Claude Code 一种请求前治理机制的命名：主线程每次 API 请求前用规则识别陈旧 [Tool Result](../concept-tool-result/index.html)，优先通过服务端 Context Edit 隐藏；长时间空闲后则直接精简本地历史。

它是 zero-LLM 的高频预处理，不等待窗口总量阈值。它对模型可见信息仍是有损的，删除旧结果可能影响未来行为，不能因用户文本与 Assistant 正文未变就声称行为分布绝对不变。

来源：《Claude Code 的三种上下文压缩与 Microcompact 的秘密》§2-5，revision 173；实现细节为来源报告，未在本导入中独立验证。
