# MOST 线性区电流模型

当 `VDS < VGS - VT` 时，沟道从源到漏连续存在，MOST 工作在线性区。长沟道手算式为

`IDS = KP (W/L) [(VGS - VT)VDS - VDS^2/2]`，其中 `KP = mu*Cox`。

在很小的 `VDS` 下，二次项可忽略，得到 `IDS ~= KP(W/L)(VGS-VT)VDS`，器件因此近似为由栅压控制的电阻。随着 `VDS` 增大，漏端沟道变薄，线性近似逐渐失效。

来源：第 1 章，书页 7-9，幻灯片 0113-0115。

## 原书图示

![第 1 章 p. 7 的原书电路或分析图](../../assets/book-pages/book-page-0007.jpg)
