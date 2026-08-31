# 在带限区间展开频谱以重构样本

把支撑于  $[-1/2,1/2]$  的  $\widehat f$  看作该区间上的 Fourier 级数；其第  $n$  个系数是  $\int\widehat f(\xi)e^{2\pi in\xi}d\xi=f(n)$  。于是
 $\widehat f=\chi\sum_nf(n)e^{-2\pi in\xi}$  ，逐项逆变换后，  $\widehat\chi$  产生 sinc 核。过采样则用梯形频率窗替代示性函数。

**认知成本：3/5**。把频谱 Fourier 级数系数识别为时域样本，再反演。**来源**：第一卷第 5 章练习 20，书页 167–168（PDF 184–185）。
