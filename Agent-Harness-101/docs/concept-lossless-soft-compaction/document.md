# 无损 Soft Compaction

无损 Soft Compaction 优先回收已有可靠恢复源的旧 payload，例如把稳定文件的已消费内容换回路径引用。它改变 Context 中的表示和可见性，但不丢弃原始信息。

“无损”只对存储信息成立，不保证模型行为完全不变：模型若要再次使用细节，仍须发现引用并读取，因而会增加一次检索步骤。

[Microcompact](../concept-microcompact/index.html) 的热路径与此不同：来源称客户端历史仍完整，但服务端推理视图隐藏旧结果。对模型可见 Context 而言这仍是有损裁剪，不应归入“信息可按引用恢复”的无损路径。

来源：《[Context Offloading](../concept-context-offloading/index.html) 机制》“阈值：多级阈值设计”，revision 145；《Claude Code 的三种上下文压缩与 Microcompact 的秘密》§3-5，revision 173。
