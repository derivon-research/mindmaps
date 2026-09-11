# 强反型跨导

跨导是偏置点附近漏电流对栅源电压的导数：`gm = dIDS/dVGS`。由平方律可得三个等价形式：

`gm = 2Kinf(W/L)(VGS-VT)`

`gm = sqrt[4Kinf(W/L)IDS]`

`gm = 2IDS/(VGS-VT)`。

“`gm` 与电流成平方根还是正比”取决于固定什么：测量同一尺寸器件时 `W/L` 固定，`gm` 随 `sqrt(IDS)`；设计时若固定 `VOV`，则 `gm` 与 `IDS` 成正比。

来源：第 1 章，书页 12-13，幻灯片 0122-0123。

## 原书图示

![第 1 章 p. 12 的原书电路或分析图](../../assets/book-pages/book-page-0012.jpg)
