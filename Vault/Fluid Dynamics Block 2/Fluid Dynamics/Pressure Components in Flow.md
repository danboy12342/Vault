---
tags: [fm2/dynamics, fm2/concept]
icon: 🧩
aliases: [Static pressure, Dynamic pressure, Hydrostatic pressure, Total pressure]
---
# Pressure Components in Flow

Interpreting the terms of the [[Bernoulli Equation]] (pressure form)

$$\underbrace{p}_{\text{static}} + \underbrace{\tfrac12\rho V^2}_{\text{dynamic}} + \underbrace{\rho g z}_{\text{hydrostatic}} = \underbrace{p_T}_{\text{total}} = \text{const}$$

| Term | Name | Physical meaning |
| :--- | :--- | :--- |
| $p$ | **Static** | The actual thermodynamic pressure of the flowing fluid — what you'd feel moving *with* the fluid ("static" relative to it). Measured by a wall tap / [[Piezometer]]. Pressure work per unit volume. |
| $\frac12\rho V^2$ | **Dynamic** | Kinetic energy per unit volume. Most visible as the pressure **rise** at a [[Stagnation Pressure\|stagnation point]]. |
| $\rho g z$ | **Hydrostatic** | Potential energy per unit volume from elevation (relative to a datum). |
| $p_T$ | **Total** | Sum of all three. Constant along a streamline in steady, inviscid, incompressible flow. |

> [!example] Bernoulli reduces to statics
> Two points in a still tank, 1 above 2 by $h$: the dynamic terms are zero, so $p_2 - p_1 = \rho g h = \gamma h$ — exactly the [[Hydrostatic Pressure Distribution|fluid statics result]].

Next: [[Stagnation Pressure]] = static + dynamic.

> [!quote] Source
> [[ENG2085 Note 9 - Applications.pdf#page=3|Note 9 p.3–4]] · [[ENG2085 Note 8 - Bernoulli 2.pdf#page=8|Note 8 p.8]]
