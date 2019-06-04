:memo: Lists 2019/5/7:

### Table of Contents

1. [By_discussion](#discuss)
2. [By_reading](#reading)
3. [Fragments](#fragments)

## By_discussion <a name="discuss"></a>

* 开题和毕业论文需要的具体内容？
1. 和涂老师的实验合作，比如算法、比如模拟

2. 流道结构的优化

3. 水分布的讨论，水分布和物质传输的优化，物质传输和膜导电性能的优化

## By_reading <a name="reading"></a>

* 验证模拟水分布结果的合理性

ideas | origin | descriptions
------------ | ------------- | -------------


* 找到合适的优化目标和优化算法

:pencil: 目标

ideas | origin | descriptions
------------ | ------------- | -------------
阴极催化层中的水淹现象 | [review paper](https://www.sciencedirect.com/science/article/pii/S0360128510000511) | The water flooding is most severe in cathode CL due to the fact that water is produced in this layer and the electro-osmotic drag (EOD) also causes water migrating form anode CL to cathode CL.
孔隙率对GDL排水的影响 |  | 均衡调整孔隙率对扩散排水（体现在D表达式中）和孔隙壁面疏水（亲疏水体现在毛细压力的θ上）的影响
\>>> | \>>>
PEM保持合适的水合程度 | [review paper](https://www.sciencedirect.com/science/article/pii/S0360128510000511) | Thus, the predominant direction of the diffussional and hydraulicwater fluxes can be arranged opposite to that of EOD water flux, balancing the water in the membrane.
产生的水和加湿所需的水之差 | 《PEM燃料电池：理论与实践》(纸质书) | 具体参考P101图示.P99的计算案例
电流密度分布指标 | ？ | ？

:pencil: 算法：Nelder-Mead Simplex

resources | genre | descriptions
------------ | ------------- | -------------
reference these | original_paper | derivation and proof, link [here](https://pdfs.semanticscholar.org/da24/280dfcd767524fb1a1702f50f388ca0d4082.pdf)
codes | python | github repo link [here](https://github.com/fchollet/nelder-mead/blob/master/nelder_mead.py)
codes | python_package | scipy, introduction [here](https://blog.csdn.net/zhoudi2010/article/details/54584495)

## Fragments <a name="fragments"></a>

* 发现流动方向上孔隙率变化对水传输影响不大，要想获得更低更均匀的水分布可能需要同时调整流动方向和垂直于流动方向的孔隙率分布和GDL的`各向异性`