# Persistent Shell Session

Persistent Shell Session 在多个 Bash 调用间保留部分进程状态。revision 310 同时声称工作目录跨命令持久，又称分开 `cd` 与命令可能丢失目录，内部不一致；实际 Runtime 验证前应使用绝对路径或单次命令显式定位。

来源：同章 §9，revision 310；状态：来源内部冲突。
