# 以周期化函数的 Fourier 系数证明 Poisson 求和

周期化函数连续。其第  $m$  个系数为
 $\int_0^1\sum_nf(x+n)e^{-2\pi imx}dx$  ；绝对一致收敛允许换序，每项平移到  $[n,n+1]$  ，而整数相位不变，拼成  $\int_{\mathbb R}f(y)e^{-2\pi imy}dy=\widehat f(m)$  。连续 Fourier 唯一性遂给完整级数恒等式。

**认知成本：3/5**。核心是和积分换序、区间拼接与圆周唯一性。**来源**：第一卷第 5 章 Theorem 3.1，书页 153–155（PDF 170–172）。
