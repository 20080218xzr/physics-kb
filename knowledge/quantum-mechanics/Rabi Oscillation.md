# Rabi Oscillation

## Physical intuition



-----

## Why

观察表达式可知推迟势函数结果依赖于观察点绝对值，分别对应介质内部的折射光和向外在真空中传播的反射光。

其中对每一薄层的介质，线电流密度：
$$\begin{equation}\bm{J}=-i\omega \bm{P_0}e^{-i\omega t-ikz}dz\end{equation}$$

将介质切成薄层$dz$的叠加电流辐射积分即是最终期望结果。

-----

## Question

- $\mathcal{Q_1}:$ 如何理解 (2) 的指数因子？

最初我理解为k即为介质中波矢$nk_0$，则此因子就是考虑了推迟的影响。然而，正确的理解应该是波矢是未知待求的，此因子是来源于时谐电场在介质中相位变化进而改变强度。

- $\mathcal{Q_2}:$ 如何理解辐射在介质中的传播速度？

最初我理解为辐射传播速度即是光波在介质中仍为光速，然而在此理论中，辐射传播速度仍为$c$，折射率的影响是多个线电流密度薄板互相干涉影响的宏观结果。

-----

## Derivation

先考虑介质外一点$(0,0,z_0)$，$z_0＞0$,由（1）的结论并积分，可得:

$$\begin{equation}\bm{A}=i\omega \frac{\mu_0\bm{P_0}}{2k_0(k+k_0)}e^{-i\omega t+ik_0z_0}\end{equation}$$

再考虑介质内一点$(0,0,z_0)$，$z_0＜0$,注意此处有绝对值影响，故得到两项:

$$\begin{equation}\bm{A}=i\omega \frac{\mu_0\bm{P_0}}{2k_0}(\frac{
e^{-i\omega t-ik_0z_0}}{k-k_0}-\frac{
2k_0e^{-i\omega t-ikz_0}}{k^2-k_0^2})\end{equation}$$

由此计算电场，观察到两项，第一项指数因子和入射光波一致，然而出射光仅一束，因此第一项对应的是要将入射光波抵消以达到“消光”的作用，这便是所谓的*The Ewald-Oseen Extinction Theorm* ( *E-O消光定理* )，由此即可解出原本位置待求的波矢$k=nk_0$，极化强度$P_0=2\varepsilon_0(n-1)E_0$。对于第二项便是透射光电场，可得透射率：
$\begin{equation}t=\frac{2}{n+1}\end{equation}$

将$P_0$结果代入（4）即可得到反射率：
$\begin{equation}r=\frac{n-1}{n+1}\end{equation}$

结果均与菲涅耳公式一致，由此可见，通过电磁辐射推导是独立自洽的理论。



-----

## Connections

- 推迟势与辐射
- 菲涅耳公式
- 介质极化
- 麦克斯韦方程

-----

## Source

- 王振林, *现代电动力学*,
  *6.2*, P312.


-----

## Status

draft