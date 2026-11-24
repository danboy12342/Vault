---
tags: [fm2/example, fm2/statics]
icon: ✏️
answer: "p1 − p2 ≈ 26.1 kPa"
---
# Ex - Slanted Pipe Manometer

**Uses:** [[Manometry Rules]] · [[U-Tube Manometer]]

## Problem
Water flows up a pipe slanted at 30°. Taps 1 and 2 are 2 m apart horizontally, and a mercury manometer between them reads $h = 12$ cm. $\rho_{Hg} = 13\,546$, $\rho_w = 1000\,\text{kg/m}^3$. Find $p_1 - p_2$.

## Solution
Vertical rise between the taps: $q = 2\tan30^\circ = 1.15$ m. Let $t$ be the unknown length of the connecting leg — it will cancel.
$$p_A = p_1 + \gamma_w(t + h), \quad p_B = p_A, \quad p_B = p_C + \gamma_{Hg}h, \quad p_C = p_2 + \gamma_w(q + t)$$
$$p_1 - p_2 = \gamma_w(q - h) + \gamma_{Hg}h$$
$$= (1000)(9.81)(1.15 - 0.12) + (13\,546)(9.81)(0.12) \approx 26\,100\,\text{Pa}$$

> [!success] Answer
> $p_1 - p_2 \approx 26.1\,\text{kPa}$

> [!tip]
> This is a manometer used in a flowing pipe — the same idea as [[Bernoulli with Manometers]].

> [!quote] Source
> [[ENG2085 Note 3 - Manometry.pdf#page=12|Note 3 p.12]] · [[ENG2085 Slides L3 - Manometry.pdf|Slides L3]]
