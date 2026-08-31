# Poisson 求和公式

对  $f\in\mathcal S(\mathbb R)$  ，

$$
\sum_{n\in\mathbb Z}f(x+n)
=\sum_{m\in\mathbb Z}\widehat f(m)e^{2\pi imx}.
$$

特别地  $x=0$  时  $\sum f(n)=\sum\widehat f(n)$  。证明计算周期化函数的第  $m$  个 Fourier 系数：把每个单位区间平移回实线后恰得  $\widehat f(m)$  ；连续函数的 Fourier 唯一性随后识别两边。

若  $f$  与  $\widehat f$  都适度衰减，公式仍成立。练习 14–16说明实线 Fejér/Dirichlet 核周期化成圆周对应核；还可重新得到余切与余割平方的部分分式展开。

第二卷第 4 章在全纯条带类  $\mathcal F$  上给出留数证明：核  $(e^{2\pi iz}-1)^{-1}$  的整数极点编码取样和，上下水平线的几何级数编码 Fourier 取样和。

**来源**：第一卷第 5 章 Theorem 3.1、练习 14–16，书页 153–155、164–165（PDF 170–172、181–182）；第二卷第 4 章 Theorem 2.4，书页 118–119（PDF 物理页 463–464）。
