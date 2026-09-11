# 多级 Compaction

多级 Compaction 用递增阈值分阶段响应窗口压力：先标记候选，再无损回收旧 payload，之后才总结老对话，紧急时执行更强裁剪。

分级的关键不是复制固定的 70/80/90/95 百分比，而是把低损操作排在高损操作之前，并让每一级释放足够空间，避免短期反复触发。

第十章提供 Claude Code 特定实例：[Microcompact](../concept-microcompact/index.html) 常态清理，[Autocompact](../concept-autocompact/index.html) 承担中等压力，[Fullcompact](../concept-fullcompact/index.html) 最后生成摘要；昂贵层还需要失败熔断。来源对 Autocompact 是否调用 LLM 有内部冲突，因此该细节不进入一般定义。

来源：《[Context Offloading](../concept-context-offloading/index.html) 机制》“阈值：多级阈值设计”，revision 145；《Claude Code 的三种上下文压缩与 Microcompact 的秘密》§2、§6，revision 173。
