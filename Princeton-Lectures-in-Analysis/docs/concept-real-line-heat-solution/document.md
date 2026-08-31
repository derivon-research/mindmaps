# 实直线热方程的卷积解

对  $f\in\mathcal S(\mathbb R)$  ，

$$
u(x,t)=(f*H_t)(x)
=\int_{\mathbb R}\widehat f(\xi)e^{-4\pi^2t\xi^2}e^{2\pi ix\xi}d\xi
$$

解实直线热方程。Fourier 变换把 PDE 化为
 $\partial_t\widehat u=-4\pi^2\xi^2\widehat u$  ；初值确定  $\widehat u=\widehat f e^{-4\pi^2t\xi^2}$  ，再反演。

解对  $t>0$  无穷光滑，并在  $t\downarrow0$  时一致且均方恢复  $f$  。练习 11还证明它在闭上半平面连续并在  $|x|+t\to\infty$  时消失。

**来源**：第一卷第 5 章 Theorem 2.1、练习 11，书页 146–147、164（PDF 163–164、181）。
