---
tags: [fm2/dynamics, fm2/device, fm2/memorise]
icon: ✈️
aliases: [Pitot tube, Pitot static]
---
# Pitot-Static Tube

Flow-measurement device · application of the [[Bernoulli Equation]] and [[Stagnation Pressure]] · used in the lab and on aircraft

- **Pitot (total-pressure) tube** — opening faces upstream → flow stops at the tip $S$ → measures **stagnation pressure** $p_S$.
- **Static hole H** — on the side of the probe or the pipe wall → measures **static pressure** $p_H$.
- The height difference between S and H is usually negligible ($z_S \approx z_H$).

Bernoulli between S and H:
$$p_S = p_H + \tfrac12\rho V_H^2 \quad\Rightarrow\quad \boxed{V = \sqrt{\frac{2\,(p_S - p_H)}{\rho}}}$$

With a [[U-Tube Manometer|differential manometer]] (gauge fluid $\rho_m$, reading $h$):
$$p_S - p_H = (\rho_m - \rho)\,g\,h \;\Rightarrow\; V = \sqrt{\frac{2(\rho_m - \rho)gh}{\rho}}$$

> [!warning] Not on the formula sheet
> Only Bernoulli itself is given — be ready to derive this in two lines ([[Formula Sheet]]).

Compare: a [[Venturi Meter]] measures **flow rate** from two **static** pressures; a Pitot-static tube measures **velocity** from stagnation − static.

> [!quote] Source
> [[ENG2085 Note 9 - Applications.pdf#page=6|Note 9 p.6–7]]
