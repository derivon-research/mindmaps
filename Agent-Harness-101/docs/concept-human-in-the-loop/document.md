# Human-in-the-loop

Human-in-the-loop 把人保留在高风险、不可逆或主观判断关键的位置，例如草稿发送前审核、[开放目标](../concept-open-ended-goal/index.html)取舍或不确定排序的最终决策。

它不是要求人轮询每一步，而是把人工注意力集中在机器不应独占判断权的闸门。

第四章补充两种运行中介入：Workflow 在关键岔路通过 `askUserQuestion()` 主动找人；用户通过 [Steering Inbox](../concept-steering-inbox/index.html) 中途纠偏，由脚本在检查点 `drainInbox()`。这些 API 是 DeerFlow 3.0 计划形式，机制本身用于说明可控 loop。

[Company Brain](../concept-company-brain/index.html) 的 [Action Router](../concept-action-router/index.html) 应从建议与请求 Owner 确认开始，随 [Trust Curve](../concept-trust-curve/index.html) 逐步放权；涉及隐私、正式承诺和不可逆动作时仍需人工责任。

来源：《从零认识 [Loop Engineering](../concept-loop-engineering/index.html)》§7，revision 1389；《Loop Engineering—从 ReAct 到 Orchestration》§6，revision 927；《Company Brain》§2.3 与 §3，revision 180。
