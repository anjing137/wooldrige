# chap01 The nature of econometrics and economic data
## 1.2 Steps in Empirical Economic Analysis
1. 实证分析的目的
- 检验理论
- 估计关系

2. 步骤
   - 确立研究问题
   - 建立模型
     - 正式模型：从效用最大化出发
     - 非正式模型：从常识出发
   - 把经济模型转化为计量模型：误差项



# chap10 Basic Regression Analysis with Time Series Data
## 10.1 Explain why the ordering of time series data is important.
- 随机过程
- 时间序列过程
- 随机过程的实现(realization)
## 10.2 Examples of Time Series Regression Models
### 10.2.1 静态模型
- 一般形式
$$
y_t=\beta_0+\beta_1x_t+\varepsilon_t
$$
- 菲利普斯曲线

$$
inf_t = \beta_0 + \beta_1 unem_t + u_t
$$

- 自杀率的多元回归模型

$$
mrdrte_t = \beta_0 + \beta_1 convrte_t + \beta_2 unem_t + \beta_3 yngmle_t + u_t
$$

### 10.2.2 有限分布滞后模型finite distributed lag models
- 模型

$$
gfr_t = \alpha_0 + \delta_0pe_t+\delta_1pe_{t-1}+\delta_2pe_{t-2}+u_t
$$
- gfr是出生率(general fertility rate), pe是个人税收豁免(personal exemption)的实际美元价值。
- 生孩子的决定不会立即由税收豁免的变化导致。

* **冲击乘数**: 也叫冲击倾向(impact propensity), 1单位的变化量对y的即时影响。
* **长期乘数**: 也叫长期趋势(long-run propensity), 1单位变化量对y的长期影响。
