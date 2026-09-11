# 适度衰减函数的重复积分公式

若 $f$ 在 $\mathbb R^2$ 上连续且适度衰减，则

$$F(x_1)=\int_{\mathbb R}f(x_1,x_2)\,dx_2$$

在 $\mathbb R$ 上连续且适度衰减，并满足

$$\int_{\mathbb R^2}f(x)\,dx=\int_{\mathbb R}\left(\int_{\mathbb R}f(x_1,x_2)\,dx_2\right)dx_1.$$

证明先在有限矩形上使用重复积分公式，再由 $O(N^{-1})$ 的尾部估计放大到全空间。

**来源**：第一卷积分附录 Theorem 3.1，书页 295–297（PDF 312–314）。
