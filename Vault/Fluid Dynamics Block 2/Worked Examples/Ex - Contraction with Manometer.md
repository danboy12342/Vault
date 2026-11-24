---
tags: [fm2/example, fm2/dynamics]
icon: ✏️
answer: "h ≈ 0.0994 m"
---
# Ex - Contraction with Manometer

**Uses:** [[Bernoulli with Manometers]] · [[Continuity Equation]] · [[U-Tube Manometer]]

## Problem
Water flows at $V = 0.6$ m/s in a horizontal pipe that contracts from $D_1 = 15$ cm to $D_2 = 10$ cm. Two static taps below the pipe, one on each side of the contraction, are joined by a manometer containing fluid of SG = 1.75 (below the pipe). Viscous effects are negligible. Find the manometer reading $h$.

## Solution
**Bernoulli A → E** (same streamline along the pipe axis, $z_A = z_E$):
$$p_A - p_E = \tfrac12\rho(V_E^2 - V_A^2)$$

**Continuity:** $\dfrac{V_E}{V_A} = \dfrac{A_A}{A_E} = \left(\dfrac{0.15}{0.10}\right)^2 = \dfrac94$
$$p_A - p_E = \tfrac12\rho V_A^2\left[\left(\tfrac94\right)^2 - 1\right] = \tfrac12(1000)(0.6)^2(4.0625) = 731.25\,\text{Pa}$$

**Manometer** — B and C at the same level in the gauge fluid ($p_B = p_C$):
$$p_A + \gamma_w(d + h) = p_E + \gamma_w d + \gamma_m h \;\Rightarrow\; p_A - p_E = (\gamma_m - \gamma_w)\,h$$
$$h = \frac{731.25}{\gamma_w\left(\frac{\gamma_m}{\gamma_w} - 1\right)} = \frac{731.25}{(1000)(9.81)(0.75)} = 0.0994\,\text{m}$$

> [!success] Answer
> $h \approx 0.099\,\text{m}$ (about 10 cm)

> [!quote] Source
> [[ENG2085 Note 7 - Bernoulli 1.pdf#page=10|Note 7 p.10–11]] · [[ENG2085 Slides L7 - Bernoulli 1.pdf|Slides L7]]
