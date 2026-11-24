---
tags: [fm2/example, fm2/dynamics]
icon: ✏️
source-problem: Munson 3.68 (Additional Worked Example 10)
answer: "Q ≈ 0.0696 m³/s; h ≈ 0.574 m"
---
# Ex - Tank Nozzle and Manometer (P3.68)

**Uses:** [[Free Jets]] · [[Bernoulli with Manometers]] · [[Continuity Equation]]

## Problem
Water flows steadily from a large open tank (surface 4 m above the pipe) through a 0.08 m pipe, then out of a 0.10 m nozzle as a free jet. A mercury manometer is connected to the 0.08 m pipe; its water leg reaches 2 m above the pipe. Neglect viscosity. Find (a) $Q$ and (b) the manometer reading $h$.

## Solution
**(a)** Bernoulli surface (1) → jet (2): $p_1 = p_2 = 0$, $V_1 = 0$, $z_1 = 4$ m, $z_2 = 0$.
$$V_2 = \sqrt{2gz_1} = \sqrt{2(9.81)(4)} = 8.86\,\text{m/s}$$
$$Q = \frac{\pi}{4}(0.10)^2(8.86) = 0.0696\,\text{m}^3/\text{s}$$

**(b)** Pipe section (3): $V_3 = \left(\dfrac{0.10}{0.08}\right)^2V_2 = 13.84$ m/s. Bernoulli (2) → (3) at the same height:
$$p_3 = \tfrac12\rho(V_2^2 - V_3^2) = \tfrac12(999)(8.86^2 - 13.84^2) = -56\,500\,\text{N/m}^2$$
**Negative** gauge pressure: the flow speeds up in the narrower pipe.
Manometer: $p_3 = -\gamma_{Hg}h + \gamma_w(2 + 0.04)$
$$-56\,500 = -133\,000\,h + 19\,990 \;\Rightarrow\; h = 0.574\,\text{m}$$

> [!success] Answer
> (a) $Q \approx 0.0696\,\text{m}^3/\text{s}$ · (b) $h \approx 0.574$ m

> [!quote] Source
> [[ENG2085 Worked Examples.pdf#page=5|Worked examples p.5 (Q10)]] · [[ENG2085 Worked Examples - Solutions.pdf#page=10|Solutions p.10]]
