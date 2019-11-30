<!-- <script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script> -->

HZQ: 2019/4/23, "DOCS: add arrangement structure"
HZQ: 2019/11/30, "DOCS: leave the room of full template structure"

### Table of Contents

1. [Cross-Subject](#cross)
2. [Within-Subject](#within)
3. [Fragments](#fragments)

## Cross-Subject <a name="cross"></a>

Section1 |  Section2 | Description |
------------ | ------------- | -------------
`点子1` | |
全称 |  | 基于神经网络数值型梯度计算的GDL孔隙率寻优方法
关键词 |  | 
| | 特点一（差异性） | 基于AI算法的`数值`优化
| | 特点二（可行性） | python库能提供的目前通过神经网络求解ODE的开源案例（[参考链接]()）
| | 特点三（价值性） | 配合AI算法，输入从微分方程组得到的多组解和对应参数，输出最优参数组合
*---投票区---* |
某某某，年/月/日 | -- | Such as...
*---补充区---* | 
HZQ，2019/4/11 |  -- | 出发点：AI在PEMFC如何落地的尝试
\>>> | \>>>
`点子2` | | 
全称 |  | 基于压损比重预测的输出功率优化方案
关键词 | | 
| | 特点一（差异性） | 区别于整体考虑，根据需要I-V曲线不同区域的主要压损得到不同工况下的压损比重和需要重点关注的压损类别
| | 特点二（可行性） | 存在不同类别压损的经验公式和相关的实验数据；python库能提供的目前流行的ML回归算法
| | 特点三（价值性） | 得到不同工况下通过降低压损提高输出功率的针对性最佳策略
*---补充区---* |
HZQ，2019/4/15 | -- | 出发点：AI算法在PEMFC如何落地的尝试

## Within Subject <a name="within"></a>

Section1 |  Section2 | Description |
------------ | ------------- | -------------
`点子1`（来源：[most creative[1]](./GDL_PorosityDistribution.md#Representative_theses)） |
全称 |  | 阴极GDL孔隙率分布和CL的Pt含量的影响
关键词 |  | 
| | 特点一（差异性） | Such as...
| | 特点二（可行性） | Such as...
| | 特点三（价值性） | Such as...
*---投票区---* |
某某某，年/月/日 | -- | Such as...
*---补充区---* |
某某某，年/月/日 | -- | Such as...
有价值的规律 |
规律1 | mechanism | the non-uniform distribution of current density within the MEA accelerates the degradations of membrane, catalyst and carbon, which shortens the life span of PEM fuel cells
规律2 | mechanism | For PEM fuel cells operated at different power levels/loads, the reaction activity and mass transport rates vary spatially in the CLs, due to the nonuniform distribution of reactant gases and change in void space for gas transport, initiated by the formation of liquid water
规律3 | ionomer_CL | An "optimal" Nafion ionomer content should minimize the species transport resistance while maintaining good ionic conductivity of the CL
规律4 | porosity_CL | it is believed that the region of the CL adjacent to the GDL should be more porous than that near the membrane, as the oxygen concentration decreases within the CL from the GDL-CL interface towards the CL-membrane interface
规律5 | mechanism_interaction | the current density uniformity is hard to achieve by applying the graded design individually considered platinum and GDL porosity, especially with high initial platinum loading and GDL porosity at the cathode inlet
优点（创意） |
优点1 | -- | the standard variance between the non-uniform spatial current density along the GDL-CL interface and the current density at the cathode inlet is defined as "sv", then divide "sv" by "i_{L}" to obtain the normalized variation
优点2 | -- | Effectiveness factor (a parameter of agglomerate model) is used to quantitatively describe the effect of species transport on the overall reaction rate, which is defined as the ratio of practical reaction rate (under the effect of species transport) over the intrinsic reaction rate (without the effect of species transport).
结论 | 
结论1 | -- | The effect of platinum gradient on the current density distribution strongly depends on the GDL porosity
结论2 | -- | The interaction of the gradients of platinum and GDL porosity, at middle and high current densities, demonstrates that the optimal platinum gradient is larger with lower initial platinum loading and GDL porosity at the cathode inlet.
\>>> | \>>>
`点子2`（来源：[most valuable[1]](./GDL_PorosityDistribution.md#Representative_theses)） |
全称 |  | 阴极GDL孔隙率分布的影响
关键词 |  | 
| | 特点一（差异性） | Such as...
| | 特点二（可行性） | Such as...
| | 特点三（价值性） | Such as...
*---投票区---* |
某某某，年/月/日 | -- | Such as...
*---补充区---* |
某某某，年/月/日 | -- | Such as...
有价值的规律 |
规律1 | porosity_GDL | it is expected that reducing the porosity of the GDL generally leads to an increase in the electronic conductivity of the GDL; however, it may retard the supply of the reactant gases in the GDL
规律2 | porosity_GDL | the low porosity region near the catalyst results in higher capillary force, and on the other hand, the high porosity region near the channels results in lower capillary force. Therefore, a net capillary force reduced by a porosity gradient in the GDL forces the water to move from the catalyst toward the channels through the GDL
规律3 | structure | the interdigitated channel design can force the gas fuel to flow through the gas diffusion and the catalyst layers effectively for electrochemical reaction
优点（创意） |
优点1 | -- | the average value of the porosity in these cases is fixed at 0.5 while the start and end value are changed so that the effects of porosity gradient could be fairly assessed. 
结论 | 
结论1 | -- | the improvement in the current density with the interdigitated channel design is not significant because this design itself already produces a relatively high current density and hence, a porosity gradient formed in GDL leads to only a very small improvement while the pressure drop caused by this design can be remarkably reduced
结论2 | -- | for parallel channel design and z-serpentine channel design, an appreciable increase in the limiting current density is also observed. Besides, the porosity gradient effectively improves the capillary diffusivity which increases the removal of water from the gas diffusion layers
\>>> | \>>>
`点子3`（来源：[most valuable[2]](./GDL_PorosityDistribution.md#Representative_theses)） |
全称 |  | 阴极GDL孔隙率分布的影响
关键词 |  | 
| | 特点一（差异性） | Such as...
| | 特点二（可行性） | Such as...
| | 特点三（价值性） | Such as...
*---投票区---* |
某某某，年/月/日 | -- | Such as...
*---补充区---* |
某某某，年/月/日 | -- | Such as...
有价值的规律 |
规律1 | -- | apart from a continuous porosity, whose distribution mathematically provides the most flexibility to meet a desired uniformity of local current density variation, it is often convenient in practice to fabricate GDLs with discrete regions of piecewise constant porosity distribution *PS: research results here suggested that it may be sufficient to use a piecewise constant porosity GDL in practice*
规律2 | -- | the reactant gases required for chemical reactions at high cell voltages are less than that consumed at low cell voltages and hence variation in the reactant gases concentration is also smaller along the channel for higher cell voltages
优点（创意） |
优点1 | -- | by mathematically describing constraints and optimized target power density of each selected operation points `respectively`, optimization equations were solved using the `Nelder-Mead Simplex` method combined with a numerical simulation model of PEM fuel cell to satisfy both the objective function and the constraints
结论 | 
结论1 | -- | cell performance and optimum porosity distribution are similar for the continuous or discrete porosity distributions and that a discrete variation of porosity may be used in practice just as effectively
结论2 | -- | for E_{cell}=0.50V the local current density decreases monotonically along the channel since the variation of the porosity is smaller and the effect of the decreasing species concentration dominates the local current density distribution along the entire channel
结论3 | -- | the optimum porosity was found to decrease with increase in temperature, and increase with increase with cell voltage, uniformity criterion, cathode mass flow rate and cathode relative humidity, whereas a non-monotonic relationship was observed with the changes in the operating pressure

## Fragments <a name="fragments"></a>

piece | source_genre | descriptions
------------ | ------------- | -------------
"effective porosity" | paper | link [here](http://jes.ecsdl.org/content/147/7/2468): effective porosity was employed to account for the fact that the pores may be partially filled with liquid water.