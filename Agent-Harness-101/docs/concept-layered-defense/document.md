# 分层防线

分层防线把同一失败教训固化在不同控制面，使复发必须同时穿透多层约束。

来源示例是“禁止注释掉测试”：指令文件明令禁止，pre-commit [Hook](../concept-hook/index.html) 机械拦截，reviewer/evaluator 将其判为 blocker。单点补丁因此升级为系统性约束。

来源：同章 §4.2，revision 297。
