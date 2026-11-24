---
tags: [fm2/dynamics, fm2/statics, fm2/method, fm2/exam-technique]
icon: 🔗
aliases: [Coupled manometer problems, Manometer and Bernoulli]
---
# Bernoulli with Manometers

The bridge between the two halves of the block: [[Manometry Rules]] (statics) + [[Bernoulli Equation]] (dynamics). A favourite Q3 structure.

## Workflow
1. **Continuity** → velocity ratio: $V_1 = \dfrac{A_2}{A_1}V_2$ ([[Continuity Equation]])
2. **Bernoulli** between the two pipe taps (1) and (2) on one streamline:
   $$p_1 - p_2 = \tfrac12\rho(V_2^2 - V_1^2) + \rho g(z_2 - z_1)$$
3. **Manometer loop** from tap 1 to tap 2 using the step rule:
   $$p_1 \pm \gamma_f(\ldots) \pm \gamma_m(\ldots) = p_2$$
4. **Equate** the two expressions for $p_1 - p_2$ → solve for $Q$ or the reading $h$ / $H$.

> [!tip] The short cut
> For a manometer connected between two taps on the same pipe, the elevation terms cancel and:
> - heavy gauge fluid below the pipe ([[U-Tube Manometer]]): $\;p_1 - p_2 = (\gamma_m - \gamma)\,h$ (combined with the $\gamma\Delta z$ term if the pipe is tilted)
> - light fluid on top ([[Inverted Manometer]]): $\;p_2 - p_1 = (\gamma_w - \gamma_m)\,H$
> Always check the sign: higher-pressure side pushes its column further away.

## Examples
- [[Ex - Contraction with Manometer]] — heavy fluid (SG 1.75) under a contraction
- [[Ex - Inverted Manometer on Expansion (2019 Q4c)]] — light oil on top of an expansion
- [[Ex - Tank Nozzle and Manometer (P3.68)]] — mercury manometer reading a negative pressure

> [!quote] Source
> [[ENG2085 Note 7 - Bernoulli 1.pdf#page=10|Note 7 p.10–11]] · [[ENG2085 Note 9 - Applications.pdf#page=13|Note 9 p.13]]
