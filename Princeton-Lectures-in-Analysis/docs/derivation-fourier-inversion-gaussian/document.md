# 由高斯单位逼近证明 Fourier 反演

取 $G_\delta(x)=e^{-\pi\delta x^2}$ ，其变换是高斯好核 $K_\delta$ 。乘法公式给
$\int fK_\delta=\int\widehat fG_\delta$ 。左侧随 $\delta\downarrow0$ 趋于 $f(0)$ ，右侧由快速衰减和 $G_\delta\to1$ 趋于 $\int\widehat f$ 。最后对 $f(\cdot+x)$ 应用零点公式，平移律产生 $e^{2\pi ix\xi}$ 。

**认知成本：3/5**。连接自对偶高斯、单位逼近、换序与平移四个步骤。**来源**：第一卷第 5 章 Theorem 1.9，书页 141（PDF 158）。
