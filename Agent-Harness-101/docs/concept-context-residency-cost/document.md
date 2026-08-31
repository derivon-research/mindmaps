# Context 驻留成本

Context 驻留成本不是一段内容进入某一轮时的一次性 token 数，而是它在后续每次模型调用中继续随历史被发送、占用窗口并可能计费的累计代价。

同样大小的 [Tool Result](../concept-tool-result/index.html)，若只服务下一轮就被回收，驻留成本远低于在几十轮历史中永久常驻。这个时间维度解释了为什么 Offloading 可能单轮亏损、长程获利。

来源：《Harness 101：[Context Offloading](../concept-context-offloading/index.html) 机制》“错觉”“生命周期”，revision 145。
