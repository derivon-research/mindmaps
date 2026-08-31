# Lagrange 多项式插值

给定互异点 $a_1,\ldots,a_n$ 与任意值 $b_1,\ldots,b_n$ ，多项式

$$
P(z)=\sum_{j=1}^n b_j
\prod_{k\ne j}\frac{z-a_k}{a_j-a_k}
$$

次数至多 $n-1$ ，并满足 $P(a_j)=b_j$ 。各基多项式在自己的节点取 $1$ ，在其余节点取 $0$ 。

**来源**：第二卷第 5 章 Exercise 17(a)，书页 156（PDF 物理页 501）。
