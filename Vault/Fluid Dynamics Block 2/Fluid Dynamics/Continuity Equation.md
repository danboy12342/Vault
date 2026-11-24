---
tags: [fm2/dynamics, fm2/concept, fm2/given]
icon: ➿
aliases: [Conservation of mass, Continuity, Q = AV]
---
# Continuity Equation

Part of [[Elementary Fluid Dynamics]] · from Block 1 conservation of mass · used in almost every [[Bernoulli Equation]] problem

General (fixed control volume):
$$\frac{\partial m_{cv}}{\partial t} + \int_{cs}\rho\,\mathbf u\cdot\mathbf n\,dA = 0$$

Apply the block's assumptions one at a time:
- **steady** → time term is zero
- **incompressible** → $\rho$ constant, comes out of the integral
- **inviscid** → uniform velocity across each section, so $\int \mathbf u\cdot\mathbf n\,dA = uA$

$$(\rho u A)_{out} - (\rho u A)_{in} = 0 \;\Rightarrow\; \boxed{A_1 V_1 = A_2 V_2 = Q}$$
(on the [[Formula Sheet]]). Mass flow rate $\dot m = \rho Q = \rho V A$. Branches: $Q_1 = Q_2 + Q_3$.

> [!tip] The ratio trick
> $$\frac{V_1}{V_2} = \frac{A_2}{A_1} = \left(\frac{D_2}{D_1}\right)^2 \text{ for circular pipes}$$
> Substitute this into Bernoulli to leave one unknown velocity. A smaller area means a **faster** flow, and (by Bernoulli) a **lower** pressure.

> [!warning] Squares
> Area goes with **diameter squared**. A 15 cm → 10 cm contraction speeds the flow up by $(15/10)^2 = 2.25$, not 1.5.

Used in: [[Venturi Meter]] · [[Bernoulli with Manometers]] · most dynamics examples in [[Worked Examples Index]]

> [!quote] Source
> [[ENG2085 Note 6 - Flow Characteristics.pdf#page=15|Note 6 p.15]] · [[ENG2085 Note 8 - Bernoulli 2.pdf#page=4|Note 8 p.4]]
