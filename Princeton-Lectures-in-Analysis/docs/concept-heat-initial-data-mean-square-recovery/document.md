# 热流对初值的均方恢复

若  $f$  是  $1$  周期 Riemann 可积函数，  $u(x,t)=f*H_t$  ，则

$$
\int_0^1|u(x,t)-f(x)|^2dx\longrightarrow0
\qquad(t\downarrow0).
$$

频率侧误差系数是
 $a_n(e^{-4\pi^2n^2t}-1)$  。Parseval 把误差范数化成平方和；先截断到有限频率再令  $t\downarrow0$  ，尾部由  $\sum|a_n|^2<\infty$  一致控制。

这是均方结论，不等同于逐点恢复；逐点结论要等第五章证明  $H_t$  是好核。

**来源**：第一卷第 4 章 §4 与练习 11，书页 119、124（PDF 136、141）。
