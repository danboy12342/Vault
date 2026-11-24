---
tags: [fm2/example, fm2/statics]
icon: ✏️
source-problem: Munson 2.58 (Additional Worked Example 9)
answer: "p1 ≈ 107 kPa"
---
# Ex - Undersea Hatch (P2.58)

**Uses:** [[Inclined Surfaces]] · [[Centre of Pressure]] · [[Gate and Hinge Problems]]

## Problem
A structure on the ocean floor has a 2 m-diameter hatch in a wall inclined at 30°, hinged on its top edge, which is 10 m below the surface. Find the minimum air pressure $p_1$ inside that will open the hatch. Seawater $\gamma = 10.1\,\text{kN/m}^3$. Neglect the hatch weight and hinge friction.

## Solution
**Force:** $h_c = 10 + 1\sin30^\circ = 10.5$ m, $A = \pi(1)^2$
$$F_R = (10.1 \times 10^3)(10.5)(\pi) = 3.33 \times 10^5\,\text{N}$$

**COP** — along the slope from the surface: $y_c = \dfrac{10}{\sin30^\circ} + 1 = 21$ m
$$y_R = y_c + \frac{I_{xc}}{y_c A} = 21 + \frac{\pi(1)^4/4}{(21)(\pi)} = 21.012\,\text{m}$$
The hinge is at $y = 20$ m, so $F_R$ acts 1.012 m from the hinge.

**Moments about the hinge:** the air pressure is uniform, so its force $p_1\pi(1)^2$ acts at the hatch centre, 1 m from the hinge:
$$F_R(1.012) = p_1(\pi)(1)^2(1) \;\Rightarrow\; p_1 = \frac{(3.33 \times 10^5)(1.012)}{\pi} \approx 107\,\text{kPa}$$

> [!success] Answer
> $p_1 \approx 107\,\text{kPa}$

> [!quote] Source
> [[ENG2085 Worked Examples.pdf#page=4|Worked examples p.4 (Q9)]] · [[ENG2085 Worked Examples - Solutions.pdf#page=9|Solutions p.9]]
