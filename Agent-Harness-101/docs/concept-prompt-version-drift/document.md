# Prompt Version Drift

Prompt Version Drift 指当前 System Instructions 已改变，历史 Assistant 回答仍持续示范旧输出格式或旧行为，使模型可能继续模仿。

边界提醒应把旧回答标为历史记录，并要求依据当前 Instructions 重新评估。

来源：§1、§2 与 §5，revision 270。
