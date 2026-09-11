# Weyl 差分估计

令  $S_N=\sum_{n=1}^Ne^{2\pi if(n)}$  。对  $H\le N$  ，Weyl 的估计把  $|S_N|^2$  控制为若干差分相位和：

$$
|S_N|^2\le c\frac NH\sum_{h=0}^H
\left|\sum_{n=1}^{N-h}e^{2\pi i(f(n+h)-f(n))}\right|.
$$

证明把序列平移  $H$  次后相加，并应用 Cauchy–Schwarz。差分会降低多项式相位的次数，这是归纳证明多项式等分布的核心。

**来源**：第一卷第 4 章问题 2(a)，书页 125（PDF 142）。
