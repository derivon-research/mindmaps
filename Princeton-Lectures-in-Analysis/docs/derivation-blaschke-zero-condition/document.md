# 让 Jensen 半径逼近单位圆周

先用一个 Blaschke 因子把可能的原点零点移开。对 $0<r<1$ 应用 Jensen 公式，并以 $|f|\le M$ 控制边界平均，得到

$$\sum_{|z_n|<r}\log\frac r{|z_n|}\le C.$$

令 $r\uparrow1$ ，单调收敛给 $\sum_n\log(1/|z_n|)<\infty$ 。由于 $1-t\le\log(1/t)$ 对 $0<t<1$ ，便得到 Blaschke 条件。

**认知成本：2.5/5**。关键是从径向对数亏损转到边界距离并取极限。**来源**：第二卷第 5 章 Problem 1，书页 156–157（PDF 501–502）。
