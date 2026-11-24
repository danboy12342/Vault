---
tags: [fm2/statics, fm2/concept]
icon: 📏
aliases: [Head, Pressure head]
---
# Pressure Head

Part of [[Fluid Statics]] · reappears as one term in the head form of the [[Bernoulli Equation]]

**Pressure head** = the height of a fluid column that would produce that pressure:
$$h = \frac{p}{\gamma} = \frac{p}{\rho g}$$
It has units of **length** (m, mm, inches…) — which is why pressures are quoted as "mm H₂O" or "mm Hg".

- $1\,\text{atm} = 760\,\text{mm Hg} \approx 10\,300\,\text{mm H}_2\text{O}$
- $\gamma_{Hg} \approx 133\,\text{kN/m}^3$, $\gamma_{H_2O} \approx 9.8\,\text{kN/m}^3$ (ratio ≈ 13.6)

> [!example] Slide example (L3)
> Head of water for $p = 340\,000\,\text{N/m}^2$, $\rho = 10^3\,\text{kg/m}^3$:
> $h = \dfrac{340\,000}{1000 \times 9.81} \approx 34.7\,\text{m}$

In flow problems, the **head form** of Bernoulli is $\frac{p}{\gamma} + \frac{V^2}{2g} + z = H$ — pressure head + velocity head + elevation head.
In the lab, [[Venturi Meter|Venturi]] pressure differences are read directly as a head difference: $p_1 - p_2 = \gamma(h_1 - h_2)$.

> [!quote] Source
> [[ENG2085 Note 3 - Manometry.pdf#page=5|Note 3 p.5]] · [[ENG2085 Slides L3 - Manometry.pdf|Slides L3]]
