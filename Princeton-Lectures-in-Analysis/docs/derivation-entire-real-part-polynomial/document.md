# 从实部的圆周 Fourier 系数消灭高次项

写 $g(z)=\sum_{n\ge0}a_nz^n$ ，令 $u=\operatorname{Re}g$ 。Cauchy 公式与共轭公式相加，对 $n>0$ 得

$$a_nr^n=\frac1\pi\int_0^{2\pi}u(re^{i\theta})e^{-in\theta}\,d\theta.$$

因 $e^{-in\theta}$ 的圆周积分为零，可在被积函数中减去 $Cr^s$ 。利用 $u\le Cr^s$ 及其平均值控制，得到 $|a_n|\le C'r^{s-n}+O(r^{-n})$ 。沿给定半径序列令 $r\to\infty$ ，则所有 $n>s$ 的系数为零。

**认知成本：3/5**。非显然点是将单侧实部上界通过零均值 Fourier 模式转成系数绝对值界。**来源**：第二卷第 5 章 Lemma 5.5，书页 152–153（PDF 497–498）。
