# Tool Call 往返

[Tool Call](../concept-tool-call/index.html) 往返由模型输出调用意图、Harness 执行真实能力、[Tool Result](../concept-tool-result/index.html) 回填 Context、模型再生成后续行动或最终答复组成。

一次往返至少涉及调用前和回填后两次模型推理；调用意图本身不包含外部事实。

来源：§5.2-5.4 与 §6.1，revision 167。
