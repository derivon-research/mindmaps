# 历史 Tool Result 回收

历史 [Tool Result](../concept-tool-result/index.html) 回收是在窗口压力出现后，扫描已被模型消费的旧 Tool Result，把其中可安全重获的原文追溯改写为短引用。

原文称其为机制 B。它与[生成时主动卸载](../concept-generation-time-offloading/index.html)独立：内容先真实进入 Context，服务当前推理；变旧且可恢复后才被回收。对 `read_file` 结果，只有文件内容稳定或由版本/快照固定时，路径才足以无损恢复当时观察。

来源：同章“生命周期：机制 B”“差异”，revision 145。
