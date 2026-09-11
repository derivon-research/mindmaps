# 用服务端视图执行热路径 Cache Edit

## 推导

[Microcompact](../concept-microcompact/index.html) 提供请求前候选决策；`cache_edits` 提供协议动作；[服务端 Cache 视图](../concept-server-side-cache-view/index.html)允许模型可见历史与本地完整历史分离。三者联合得到[热路径 Cache Edit](../concept-hot-path-cache-edit/index.html)。

## 学习成本

权重 3.5：关键桥梁是区分客户端历史与服务端推理视图。

来源：同章 §4、§5.1，revision 173；实现语义按来源报告。
