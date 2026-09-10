# To Do List for Computation

用于记录学会 Python 后回头完成的计算机题和数值计算题。按教材出现顺序追加；完成后将复现代码、图像和数值检验写入相应的习题解析文件。

## 待完成

1. [ ] **习题 2.14：简谐振子基态的经典禁区概率**
   - 数值计算基态粒子出现在经典允许区间之外的概率，并保留三位有效数字。
   - 用数值积分计算

     $$
     P_{\mathrm{out}}
     =\frac{2}{\sqrt\pi}\int_1^\infty e^{-\xi^2}\,d\xi,
     \qquad
     \xi=\sqrt{\frac{m\omega}{\hbar}}x.
     $$

   - 用误差函数的补函数 `scipy.special.erfc` 进行独立核对。
   - 可选：绘制基态概率密度，并给经典禁区着色。
   - 建议工具：`numpy`、`scipy.integrate.quad`、`scipy.special.erfc`、`matplotlib`。

2. [ ] 数值计算式子（2.105）

3. [ ] 浏览 [PhET 交互式仿真](https://phet.colorado.edu/)。
