# 大体积工具负载

大体积工具负载是单次工具调用的参数或结果占用大量 token 的现象，例如构建日志、仓库级 grep、完整网页、大文件内容，或 `write_file` 的长 `content` 参数。

这些数据会随消息历史在后续轮次持续占用 [Context Window](../concept-context-window/index.html)，即使绝大部分只被使用一次。它是 [Context Offloading](../concept-context-offloading/index.html) 要解决的直接问题。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§6.2 末尾与 §7 开头，revision 2846；《Harness 101：Context Offloading 机制》“差异”，revision 145。
