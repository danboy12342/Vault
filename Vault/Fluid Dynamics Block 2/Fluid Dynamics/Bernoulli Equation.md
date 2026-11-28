---
tags: [fm2/dynamics, fm2/concept, fm2/given]
icon: ⚡
aliases: [Bernoulli, Bernoulli's equation]
---
# Bernoulli Equation

Central idea of [[Elementary Fluid Dynamics]] (exam Q3) · derived two ways: [[Bernoulli Derivation - Energy]] and [[Bernoulli Derivation - Streamtube]]

$$\boxed{p + \tfrac12\rho V^2 + \rho g z = \text{constant along a streamline}}$$
Between two points 1 and 2 on the same [[Streamlines|streamline]]:
$$p_1 + \tfrac12\rho V_1^2 + \rho g z_1 = p_2 + \tfrac12\rho V_2^2 + \rho g z_2$$

> [!important] Assumptions (all four, every time)
> 1. **Steady** flow ([[Steady vs Uniform Flow]])
> 2. **Incompressible** ($\rho$ constant)
> 3. **Inviscid** — frictionless, ideal fluid ([[Ideal vs Real Fluids]])
> 4. **Along a streamline**
> When they fail → [[Bernoulli Limitations]].

## Three equivalent forms
| Form            | Equation                                    | Units              | Meaning                                                           |
| :-------------- | :------------------------------------------ | :----------------- | :---------------------------------------------------------------- |
| Pressure        | $p + \rho\frac{V^2}{2} + \rho g z = C$      | Pa = energy/volume | [[Pressure Components in Flow\|static + dynamic + hydrostatic]]   |
| Energy per mass | $\frac{p}{\rho} + \frac{V^2}{2} + g z = C$  | J/kg               | pressure work + KE + PE per unit mass                             |
| Head            | $\frac{p}{\gamma} + \frac{V^2}{2g} + z = H$ | m                  | [[Pressure Head\|pressure head]] + velocity head + elevation head |

## The constant
The integration constant is fixed by a **reference point** on the streamline where $p$, $V$, $z$ are known (e.g. the inlet): $C = p_0 + \frac12\rho V_0^2 + \rho g z_0$.
- Different streamlines generally have **different** constants ($C_A \neq C_B$).
- **Exception:** in **uniform** flow (e.g. parallel horizontal streamlines from a uniform upstream), every streamline has the same constant, so you can apply Bernoulli *across* streamlines.

## Fluid statics is a special case
With $V = 0$: $p_1 - p_2 = \rho g(z_2 - z_1) = \gamma h$ — the [[Hydrostatic Pressure Distribution]] again.

## Solving problems
1. Choose points 1 and 2 on one streamline, with as much known as possible (free surfaces: $p = 0$ gauge, $V \approx 0$ for a large tank; free jets: $p = 0$ gauge).
2. Write Bernoulli and cancel terms ($z_1 = z_2$ for horizontal pipes).
3. Use [[Continuity Equation|continuity]] to remove one velocity.
4. If a manometer gives $\Delta p$ → [[Bernoulli with Manometers]].
5. $Q = AV$.

## Applications
[[Stagnation Pressure]] · [[Pitot-Static Tube]] · [[Venturi Meter]] · [[Free Jets]] · [[Bernoulli with Manometers]]

> [!quote] Source
> [[ENG2085 Note 7 - Bernoulli 1.pdf#page=9|Note 7 p.9]] · [[ENG2085 Note 8 - Bernoulli 2.pdf#page=8|Note 8 p.8–10]] · [[ENG2085 Note 9 - Applications.pdf#page=2|Note 9 p.2]] · on the [[Formula Sheet]]
