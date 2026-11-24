---
tags: [fm2/dynamics, fm2/concept, fm2/memorise]
icon: 📉
aliases: [Cd, Coefficient of discharge]
---
# Discharge Coefficient

Correction to the ideal [[Venturi Meter]] result · exists because of [[Bernoulli Limitations]]

The ideal equation ignores pressure losses from **friction and turbulence**. Part of the kinetic energy is dissipated as eddies (vortices) downstream. These eddies have high velocity and low pressure, which makes the measured $p_2$ **too low** → the ideal formula **overestimates** the flow rate.

$$\boxed{Q_{actual} = C_d\,Q_{ideal} = C_d\,A_2\sqrt{\frac{2(p_1 - p_2)}{\rho\left[1 - (A_2/A_1)^2\right]}}}, \qquad C_d < 1$$

| Meter | Typical $C_d$ | Why |
| :--- | :--- | :--- |
| Venturi | ≈ 0.97 | smooth taper, low turbulence |
| Orifice plate | ≈ 0.6 | abrupt edge, high turbulence downstream |

$C_d$ also depends slightly on [[Laminar vs Turbulent Flow|Reynolds number]] and the diameter ratio (orifice table in Slides L9: ≈ 0.59–0.64).

> [!quote] Source
> [[ENG2085 Note 9 - Applications.pdf#page=8|Note 9 p.8–9]] · [[ENG2085 Slides L9 - Applications.pdf|Slides L9]]
