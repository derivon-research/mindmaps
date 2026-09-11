# 把 Worker 重试内化进 `agent()`

`agent()` 提供任务委派边界，[Verification Prompt](../concept-verification-prompt/index.html) 提供局部 Rubric，[LLM-as-a-Judge](../concept-llm-as-a-judge/index.html) 依据该 Rubric 检查每版输出。未通过时调用内部继续搜索、反思和修正，直到准出，形成自验证 `agent()` 调用。

权重 3.0：这是短但非平凡的封装设计。三个尾点分别贡献执行者、标准和判断机制，不能拆成相互替代的单尾边。

来源：§4.1 与 §5，revision 927。
