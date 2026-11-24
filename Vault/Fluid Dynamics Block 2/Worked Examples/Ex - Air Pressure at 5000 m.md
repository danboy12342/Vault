---
tags: [fm2/example, fm2/statics]
icon: ✏️
answer: "56.0 kPa (isothermal); 54.0 kPa (standard troposphere)"
---
# Ex - Air Pressure at 5000 m

**Uses:** [[Compressible Atmosphere]] · [[Hydrostatic Pressure Distribution]]

## Problem
Sea-level pressure is $p_0 = 101\,350$ Pa. Find the standard pressure at $z = 5000$ m:
(a) assuming an isothermal atmosphere at $T = 15^\circ\text{C} = 288.15$ K;
(b) assuming a linear temperature drop $T = 288.15 - 0.0065z$.

## Solution
Air is a **compressible** ideal gas, $\rho = p/(RT)$ with $R = 287$, so $p = p_0 + \gamma h$ doesn't apply. $g$ is constant.

**(a) Isothermal**
$$\ln\frac{p}{p_0} = -\frac{g\,z}{RT} = -\frac{9.81 \times 5000}{287 \times 288.15} = -0.593$$
$$\frac{p}{p_0} = e^{-0.593} = 0.553 \;\Rightarrow\; p \approx 56\,000\,\text{Pa}$$

**(b) Linear temperature** ($T_0 = 288.15$ K, $B = 0.0065$ K/m)
$$\frac{p}{p_0} = \left(1 - \frac{Bz}{T_0}\right)^{g/(RB)} = (0.887)^{5.26} = 0.534 \;\Rightarrow\; p \approx 54\,000\,\text{Pa}$$

> [!success] Answer
> (a) ≈ **56.0 kPa** · (b) ≈ **54.0 kPa**

> [!quote] Source
> [[ENG2085 Note 2 - Pressure Distribution.pdf#page=10|Note 2 p.10–12]]
