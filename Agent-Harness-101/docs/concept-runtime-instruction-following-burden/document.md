# 运行时 Instruction Following 负担

运行时 Instruction Following 负担，是模型在每次执行中都必须重新读懂自然语言流程、维持顺序、记住约束并避免漏步的认知与可靠性压力。

纯 ReAct + [Skill](../concept-skill/index.html) 把整条流程藏在模型每轮推理里，因此这项负担贯穿全程；一处理解漂移会沿后续链路放大，也让复盘难以定位。它解释了为什么复杂 Skill 往往依赖旗舰模型仍难稳定交付。

来源：§2-3 与 §8，revision 927，https://my.feishu.cn/wiki/ToaRw8BAUiAyFFkR3EAc05atnsg
