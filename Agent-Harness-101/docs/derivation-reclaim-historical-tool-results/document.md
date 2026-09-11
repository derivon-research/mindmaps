# 追溯改写回收旧 Tool Result

## 推导

[结果侧 Offloading](../concept-result-side-offloading/index.html) 确定要替换的是历史返回值；[追溯式消息改写](../concept-retroactive-message-rewriting/index.html)提供对旧 `messages` 的变换；[稳定可重读数据源](../concept-stable-reread-source/index.html)保证未来仍可恢复当时内容。三者共同建立[历史 Tool Result 回收](../concept-historical-tool-result-reclamation/index.html)。

## 学习成本

权重 3.0：关键观察是结果已经被消费，之后才从热表示切换为冷引用。

来源：同章“生命周期：机制 B”“差异”，revision 145。
