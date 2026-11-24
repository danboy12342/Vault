---
tags: [fm2/example, fm2/statics, fm2/check-this]
icon: ⚠️
source-problem: White P2.72 (Additional Worked Example 8)
answer: "M_A ≈ 131 kN·m"
---
# Ex - Circular Gate Moment (P2.72)

**Uses:** [[Hydrostatic Force on a Plane Surface]] · [[Centre of Pressure]] · [[Centroids and Second Moments of Area]]

## Problem
A vertical circular gate AB has its top A 3 m below the water surface and its bottom B 2 m below A (so diameter 2 m, $R = 1$ m). Find the moment of the hydrostatic force about A. Ignore atmospheric pressure. $\gamma = 9790\,\text{N/m}^3$.

## Solution
Centroid depth $h_c = 3 + 1 = 4$ m. Area $A = \pi R^2 = \pi\,\text{m}^2$.
$$F = \gamma h_c A = (9790)(4)(\pi) \approx 123\,000\,\text{N}$$
$$h_{cop} - h_c = \frac{I_{xc}}{A h_c} = \frac{\pi(1)^4/4}{(4)(\pi)} = 0.0625\,\text{m}$$
The force acts $1 + 0.0625 = 1.0625$ m below A:
$$M_A = (123\,000)(1.0625) \approx 131\,000\,\text{N·m}$$

> [!success] Answer
> $M_A \approx 131\,\text{kN·m}$

> [!bug] The posted solution looks wrong
> The sheet uses $A = \pi(0.5)^2$ in the force (giving 30.8 kN and $M_A = 32.7$ kN·m) but $R = 1$ m in $I_{xc}$. A 2 m gate has $R = 1$ m, so $A = \pi\,\text{m}^2$. The 0.0625 m offset is right. Logged in [[Exam Traps]].

> [!quote] Source
> [[ENG2085 Worked Examples.pdf#page=4|Worked examples p.4 (Q8)]] · [[ENG2085 Worked Examples - Solutions.pdf#page=9|Solutions p.9]]
