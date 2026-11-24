---
tags: [fm2/statics, fm2/reference, fm2/given]
icon: 📊
aliases: [Second moment of area, Ixc, Centroid table, Parallel axis theorem, Product of inertia]
---
# Centroids and Second Moments of Area

Reference for [[Hydrostatic Force on a Plane Surface]] and [[Centre of Pressure]] · this table **is on the [[Formula Sheet]]** (Munson Fig. 2.18)

## Definitions
- Centroid: $x_c = \dfrac{\int x\,dA}{A}$, $y_c = \dfrac{\int y\,dA}{A}$ — a property of **geometry only**
- Second moment of area about the centroidal $x$-axis: $I_{xc} = \int (y - y_c)^2\,dA$
- Product of inertia: $I_{xyc}$ (zero if the shape is symmetric about either centroidal axis)

> [!tip] The general pattern
> "Centre of *something*" $= \dfrac{\int x \cdot (\text{something})\,dA}{\int (\text{something})\,dA}$
> - Centroid: weight by area → geometry only
> - Centre of mass: weight by $\rho$ → geometry + density
> - Centre of gravity: weight by $\rho g$ → geometry + density + gravity (same as centre of mass in uniform $g$)
> - **Centre of pressure**: weight by $p$ → geometry + pressure field → [[Centre of Pressure]]

## Parallel axis theorem
$$I_x = I_{xc} + A\,y_c^2$$
Moves the second moment from the centroid to another parallel axis (here, the free surface). This is the key step in the [[Centre of Pressure]] derivation.

## Standard shapes ($x$-axis horizontal through the centroid)
| Shape | Area $A$ | Centroid | $I_{xc}$ | $I_{xyc}$ |
| :--- | :--- | :--- | :--- | :--- |
| Rectangle, width $b$, height $a$ | $ba$ | $a/2$ from edge | $\frac{1}{12}ba^3$ | $0$ |
| Circle, radius $R$ | $\pi R^2$ | centre | $\frac{\pi R^4}{4}$ | $0$ |
| Semicircle, radius $R$ | $\frac{\pi R^2}{2}$ | $\frac{4R}{3\pi}$ from the diameter | $0.1098\,R^4$ | $0$ |
| Triangle, base $b$, height $a$, apex offset $d$ | $\frac{ab}{2}$ | $\frac{a}{3}$ from base; $x = \frac{b+d}{3}$ | $\frac{ba^3}{36}$ | $\frac{ba^2}{72}(b - 2d)$ |
| Quarter circle, radius $R$ | $\frac{\pi R^2}{4}$ | $\frac{4R}{3\pi}$ from each edge | $0.05488\,R^4$ | $-0.01647\,R^4$ |

> [!warning] Circle vs. diameter
> Read whether you're given **radius or diameter** — a 2 m-diameter gate has $R = 1$ m, $A = \pi\,\text{m}^2$. The posted solution to [[Ex - Circular Gate Moment (P2.72)]] slips on exactly this.

> [!quote] Source
> [[ENG2085 Note 4 - Forces on Submerged Surfaces.pdf#page=10|Note 4 p.10]] · [[ENG2085 Note 5 - Centre of Pressure.pdf#page=2|Note 5 p.2–4]]
