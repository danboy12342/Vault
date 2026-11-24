---
tags: [fm2/statics, fm2/concept, fm2/derivation, fm2/given]
icon: 📉
aliases: [Hydrostatic equation, dp/dz = -gamma, Pressure variation with depth]
---
# Hydrostatic Pressure Distribution

Part of [[Fluid Statics]] · builds on [[Pascal's Law]] · used by [[Manometry Rules]], [[Hydrostatic Force on a Plane Surface]]

## Force balance on a cube element
Pressure is a scalar field $p(x,y,z)$. Balance forces on a cube $\delta x\,\delta y\,\delta z$ at rest (divide by volume, let $\delta \to 0$):

| Direction | Balance | Result |
| :--- | :--- | :--- |
| $x$ | $pA_x - (p+\delta p)A_x = 0$ | $\dfrac{\partial p}{\partial x} = 0$ |
| $y$ | $pA_y - (p+\delta p)A_y = 0$ | $\dfrac{\partial p}{\partial y} = 0$ |
| $z$ | $pA_z - (p+\delta p)A_z - \gamma\,\delta\forall = 0$ | $\dfrac{\partial p}{\partial z} = -\gamma$ |

Formally: $\nabla p + \gamma\,\hat{\mathbf k} = \mathbf 0$. Since $p = p(z)$ only, partial derivatives become total:
$$\boxed{\frac{dp}{dz} = -\rho g = -\gamma}$$

> [!summary] Key insight
> Pressure only changes in the **direction of gravity**. Horizontal lines are **lines of constant pressure** — this is the basis of the [[Manometry Rules]].

## Incompressible fluid ($\rho$ constant, $g$ constant)
$$p_1 - p_0 = -\rho g\,(z_1 - z_0)$$
Measuring depth $h$ **downward** from a free surface at pressure $p_0$:
$$\boxed{p = p_0 + \gamma h}$$
With $p_0 = p_{atm}$ and working in gauge pressure ([[Absolute and Gauge Pressure]]), simply $p = \gamma h$ — this is the first line of the [[Formula Sheet]].

> [!warning] When you *can't* use $p = \gamma h$
> - $\rho$ changes between the two heights (e.g. across the atmosphere, kilometres of height)
> - large temperature changes (gas density depends on $T$)
> → use [[Compressible Atmosphere]] instead.

## Examples
- [[Ex - Lift Ear Pressure (2018 Q3a)]] — air treated as incompressible over 46 m
- [[Ex - Air Pressure at 5000 m]] — where that assumption fails

> [!quote] Source
> [[ENG2085 Note 2 - Pressure Distribution.pdf#page=2|Note 2 p.2–8]] · [[ENG2085 Note 3 - Manometry.pdf#page=2|Note 3 p.2]] · [[ENG2085 Slides L2 - Pressure Distribution.pdf|Slides L2]]
