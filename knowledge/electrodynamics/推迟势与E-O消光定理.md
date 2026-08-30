# 推迟势与E-O消光定理

## Physical intuition

无穷大平面上线电流分布$\bm{K}$=$K_0e^{-i\omega t}\bm{e_x}$推迟势有：

$$
\begin{equation}\bm{A}=\begin{cases}\frac{\mu_0K_0}{2k_0}e^{-i\omega t+ik_oz+\frac{\pi}{2}}\bm{e_x}&z>0\\
\frac{\mu_0K_0}{2k_0}e^{-i\omega t-ik_oz+\frac{\pi}{2}}\bm{e_x}&z<0\end{cases}\end{equation}
$$

产生类似于电磁横波的正交电磁场。

从此观点认知光波在界面的反射与折射作用：反射光与折射光是介质极化产生时谐电流从而有电磁横波产生，完全不需要麦克斯韦方程。


---

## Why

观察表达式可知推迟势函数结果依赖于观察点绝对值，分别对应介质内部的折射光和向外在真空中传播的反射光。

其中对每一薄层的介质，线电流密度：
$$\begin{equation}\bm{J}=-i\omega \bm{P_0}e^{-i\omega t-ikz}\end{equation}$$

将介质切成薄层$dz$的叠加电流辐射积分即是最终期望结果。

---

## Question

- $\mathcal{Q_1}:$ 如何理解 (2) 的指数因子？

最初我理解为

---

## Derivation

从

$$
[L_z,L_x]=i\hbar L_y,
\qquad
[L_z,L_y]=-i\hbar L_x
$$

出发，定义

$$
L_\pm=L_x\pm iL_y.
$$

于是

$$
[L_z,L_\pm]
=
\pm\hbar L_\pm.
$$

作用在 $|l,m\rangle$ 上：

$$
L_zL_\pm|l,m\rangle
=
(m\pm1)\hbar L_\pm|l,m\rangle.
$$

因此

$$
L_\pm|l,m\rangle
\propto
|l,m\pm1\rangle.
$$

$$
[L^2,L_\pm]=0,
$$

可知升降操作不会改变 $l$，只改变 $m$。

---

## Connections

- 推迟势与辐射
- 菲涅耳公式
- 介质极化
- 麦克斯韦方程

---

## Source

- 王振林, *现代电动力学*,
*6.2*, P312.

- Zangwill, *Modern Electrodynamics*,
*20.9.1*, P763

---

## Status

draft