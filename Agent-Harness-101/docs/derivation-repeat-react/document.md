# 重复 ReAct 回合得到多轮 ReAct

## 推导

ReAct 的一次回合已经把 tool result 写回消息历史。若模型观察后继续发出新的 tool call，Harness 复用同一循环，后一行动就能依赖前一结果；持续重复直到[主动停机](../concept-active-halting/index.html)，即得到[多轮 ReAct](../concept-multiround-react/index.html)。

## 学习成本

权重 1.5：控制流只是重复已有回合，但读者要建立“下一步由最新观察决定、轨迹长度未知”的状态视角。

来源：同章 §3.3 与 §4.1-4.3，revision 2846。
