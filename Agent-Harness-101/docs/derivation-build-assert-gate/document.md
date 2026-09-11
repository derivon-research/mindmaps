# 从 LLM-as-a-Judge 得到 `assert()` 闸门

[LLM-as-a-Judge](../concept-llm-as-a-judge/index.html) 给出对自然语言 Rubric 的合格性判断；`assert()` 把该判断收敛为脚本可消费的布尔值，用于回炉、退出、报错或交付。

权重 1.0：对熟悉函数返回值的目标读者，这是直接的接口封装。该边不声称判断必然正确。

来源：§4-5，revision 927。
