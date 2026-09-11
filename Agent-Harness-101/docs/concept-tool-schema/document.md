# Tool Schema

Tool Schema 是提供给模型的工具接口契约，描述工具名称、用途、参数结构、必填字段和约束。模型依据 schema 决定是否调用、调用哪个工具以及构造什么参数。

示例：天气工具要求 `city` 为中文城市名并禁止额外字段；搜索和抓取工具的 description 还明确区分“发现候选页面”和“读取已知 URL”。

第六章用 location 到 city_code 的破坏性变更说明：Schema 是当前参数真相，历史 [Tool Call](../concept-tool-call/index.html) 不是；Runtime 应在业务逻辑执行前拒绝缺少当前必填字段的调用。

第七章区分结构与语义：strict 和收窄 Schema 能让已选 Tool 的参数更合规，却不能保证模型选择了正确能力；Tool Definition 还需要名字、使用边界与结果契约。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§3.1、§4 与 §6.1，revision 2846；《[Agent Version Drifting](../concept-agent-version-drifting/index.html)》§1、§3-4，revision 270；《工具的真相》§3 与 §7，revision 167。
