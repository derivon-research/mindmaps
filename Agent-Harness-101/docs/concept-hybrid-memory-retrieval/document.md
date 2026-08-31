# 混合记忆检索

混合记忆检索先用 Embedding 找候选，再用 [Graph Expansion](../concept-graph-expansion/index.html) 补关系上下文，最后由 Policy Layer 按角色裁剪原文与 Summary。

它结合未结构化召回和结构化关系，不把两者当作互相替代。

来源：§2.1 与 §3，revision 180。
