<!-- <script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script> -->

### Cross-Subject

Section | Description |
------------ | -------------
`点子1` |
全称 | 基于神经网络数值型梯度计算的GDL孔隙率寻优方法
关键词 | --
特点一（差异性） | 基于AI算法的`数值`优化
特点二（可行性） | python库能提供的目前通过神经网络求解ODE的开源案例（[参考链接]()）
特点三（价值性） | 配合AI算法，输入从微分方程组得到的多组解和对应参数，输出最优参数组合
<!-- *---投票区---* |
某某某，年/月/日 | -->
*---补充区---* | 
HZQ，2019/4/11 | 出发点：AI在PEMFC如何落地的尝试
\>>> | \>>>
`点子2` |
全称 | 基于压损比重预测的输出功率优化方案
关键词 | --
特点一（差异性） | 区别于整体考虑，根据需要I-V曲线不同区域的主要压损得到不同工况下的压损比重和需要重点关注的压损类别
特点二（可行性） | 存在不同类别压损的经验公式和相关的实验数据；python库能提供的目前流行的ML回归算法
特点三（价值性） | 得到不同工况下通过降低压损提高输出功率的针对性最佳策略
*---补充区---* | 
HZQ，2019/4/15 | 出发点：AI在PEMFC如何落地的尝试

### Within Subject

Section | Description |
------------ | -------------
`点子1`（[most creative[1]](./GDL_PorosityDistribution.md#Representative_theses)） |
全称 | 阴极GDL孔隙率分布和CL的Pt含量的影响规律
*---补充区---* | 
有价值的规律 | -- 
规律1 | the non-uniform distribution of current density within the MEA accelerates the degradations of membrane, catalyst and carbon, which shortens the life span of PEM fuel cells
规律2 | For PEM fuel cells operated at different power levels/loads, the reaction activity and mass transport rates vary spatially in the CLs, due to the nonuniform distribution of reactant gases and change in void space for gas transport, initiated by the formation of liquid water
规律3 | An "optimal" Nafion ionomer content should minimize the species transport resistance while maintaining good ionic conductivity of the CL
规律4 | it is believed that the region of the CL adjacent to the GDL should be more porous than that near the membrane, as the oxygen concentration decreases within the CL from the GDL-CL interface towards the CL-membrane interface
规律5 | the current density uniformity is hard to achieve by applying the graded design individually considered platinum and GDL porosity, especially with high initial platinum loading and GDL porosity at the cathode inlet
优点（创意） | --
优点1 | the standard variance between the non-uniform spatial current density along the GDL-CL interface and the current density at the cathode inlet is defined as "sv", then divide "sv" by "$$i_{L}$$" to obtain the normalized variation
优点2 | Effectiveness factor (a parameter of agglomerate model) is used to quantitatively describe the effect of species transport on the overall reaction rate, which is defined as the ratio of practical reaction rate (under the effect of species transport) over the intrinsic reaction rate (without the effect of species transport).
结论 | --
结论1 | The effect of platinum gradient on the current density distribution strongly depends on the GDL porosity
结论2 | The interaction of the gradients of platinum and GDL porosity, at middle and high current densities, demonstrates that the optimal platinum gradient is larger with lower initial platinum loading and GDL porosity at the cathode inlet.
\>>> | \>>>
`点子2`（[most valuable[1]](./GDL_PorosityDistribution.md##Representative_theses)） |'
有价值的规律 | -- 
规律1 | --
优点（创意） | --
结论 | --