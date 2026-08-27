# Angular Momentum Ladder Operators

## Physical intuition

角动量升降算符

$$
L_\pm=L_x\pm iL_y
$$

可以把一个角动量本征态

$$
|l,m\rangle
$$

变成具有不同 $m$ 的另一个角动量本征态。

直观上，它们在角动量态空间中实现了

$$
m\rightarrow m\pm1.
$$

它们不是简单地“创造/湮灭粒子”，而是在角动量多重态内部连接不同的量子态。

---

## Why

直接求解 $L^2$ 和 $L_z$ 的本征值问题需要处理球坐标下的偏微分方程。

引入升降算符后，可以利用角动量的对易关系进行纯代数处理。

关键关系是

$$
[L_z,L_\pm]=\pm\hbar L_\pm.
$$

因此，如果

$$
L_z|l,m\rangle=m\hbar|l,m\rangle,
$$

那么 $L_\pm|l,m\rangle$ 仍然是 $L_z$ 的本征态，
但对应的本征值发生变化。

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

进一步结合

$$
[L^2,L_\pm]=0,
$$

可知升降操作不会改变 $l$，只改变 $m$。

---

## Connections

- 角动量代数
- 对易关系
- 旋转对称性
- 角动量简并
- 球谐函数
- 自旋
- 量子谐振子的升降算符

---

## Source

Shankar, *Principles of Quantum Mechanics*,
Chapter 12, Angular Momentum.

具体章节/公式编号待进一步核对。

---

## Status

draft