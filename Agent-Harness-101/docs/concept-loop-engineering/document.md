# Loop Engineering

Loop Engineering 把原本由人承担的循环接力交给 Agent：Agent 自己发现下一步、规划、执行、验证，并在不达标时续写下一轮；人退回到设定目标、验收与边界的位置。

它不是发明新循环，而是改变循环执行者，并把进度外置到对话之外，使循环能跨轮和跨 Agent 接续。

本章进一步明确：Loop Engineering 是宏观工程姿态，工作重心从“写这一次 Prompt”转向“设计会反复 prompt agent 的 loop”；[Dynamic Workflow](../concept-dynamic-workflow/index.html) 只是把单个 loop 落成模型生成脚本的一种具体形态。

第五章把可改进对象扩展为脚本控制流、Agent Prompt、Schema/验证器与真实运行反馈。一次常漏检查可改成确定分支，模糊文本接口可改成 Schema，并行策略可通过 Eval 回归，而不只继续加长 Prompt。

来源：《从零认识 Loop Engineering》§1-3 与 §8，revision 1389；《Loop Engineering—从 ReAct 到 Orchestration》§2 与 §8，revision 927；《复刻 Dynamic Workflow》§1.3 与 §7.1，revision 1503。
