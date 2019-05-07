:memo: Lists 2019/5/7:

### Table of Contents

1. [By_discussion](#discuss)
2. [By_reading](#reading)
3. [Fragments](#fragments)

## By_discussion <a name="discuss"></a>

* 主要的水传输方式有？

* 水传输主要的方程？

## By_reading <a name="reading"></a>

* 在网独基础上验证文献中改变孔隙率分布的效果

:pencil: 验证不同电流密度下的模拟水分布结果的合理性

:pencil: 发现流动方向上孔隙率变化对水传输影响不大，要想获得更低更均匀的水分布可能需要同时调整流动方向和垂直于流动方向的孔隙率分布和GDL的`各向异性`

* 找到合适的优化指标

ideas | origin | descriptions
------------ | ------------- | -------------
产生的水和加湿所需的水之差 | 《PEM燃料电池：理论与实践》，纸质书 | 具体参考P101图示.P99的计算案例
电流密度分布指标 | ？ | ？

* 找到一种寻找孔隙率最优排布的算法

:pencil: Nelder-Mead Simplex

resources | genre | descriptions
------------ | ------------- | -------------
reference these | original_paper | link [here](https://pdfs.semanticscholar.org/da24/280dfcd767524fb1a1702f50f388ca0d4082.pdf) 
codes | python | github repo link [here](https://github.com/fchollet/nelder-mead/blob/master/nelder_mead.py)
codes | python_package | scipy, introduction [here](https://blog.csdn.net/zhoudi2010/article/details/54584495)

## Fragments <a name="fragments"></a>
