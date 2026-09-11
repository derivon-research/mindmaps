# 生成时主动卸载

生成时主动卸载是在 [Tool Result](../concept-tool-result/index.html) 产生边界由 Harness 检查体积与类型：若返回大且未来无法可靠重放，就先把完整结果保存成快照，再只把路径、大小和恢复说明写入 `messages`。

原文称其为机制 A / Preemptive Offloading。模型从未在 Context 中看到该结果原文，因此它是预防性控制；代价是首次消费前必须额外读取。它适用于大构建日志、命令输出或会变化的网页快照。

来源：同章“生命周期：机制 A”，revision 145。
