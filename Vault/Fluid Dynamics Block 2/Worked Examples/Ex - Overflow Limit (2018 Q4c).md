---
tags: [fm2/example, fm2/dynamics, fm2/past-exam]
icon: ✏️
exam: 2018 Q4c
marks: 8/80
answer: "Q_max ≈ 0.00363 m³/s"
---
# Ex - Overflow Limit (2018 Q4c)

**Uses:** [[Bernoulli Equation]] · [[Continuity Equation]] · [[Piezometer]] · [[Free Jets]]

## Problem
Water flows steadily (inviscid) along a horizontal pipe of diameter 0.04 m, then out of a 0.03 m nozzle as a free jet. An open vertical tube at A on top of the pipe rises 0.9 m above the pipe. Find the **maximum** flow rate before water spills out of the tube.

## Solution
More flow means higher pressure at (1), so the water column rises. The limit is when the column reaches the top of the tube. The pipe centreline is a further $0.04/2 = 0.02$ m below the pipe top:
$$p_1 = \gamma_w(0.9 + 0.02) \;\text{(gauge)}, \qquad p_2 = 0 \;\text{(free jet)}, \qquad z_1 = z_2$$

**Continuity:** $\dfrac{V_1}{V_2} = \left(\dfrac{0.03}{0.04}\right)^2 = \dfrac{9}{16}$

**Bernoulli 1 → 2:**
$$\rho g(0.92) + \tfrac12\rho V_1^2 = \tfrac12\rho V_2^2 \;\Rightarrow\; \tfrac12V_2^2\left(1 - \tfrac{81}{256}\right) = (0.92)(9.81)$$
$$V_2 = 5.14\,\text{m/s}, \qquad Q = \frac{\pi}{4}(0.03)^2(5.14) = 0.00363\,\text{m}^3/\text{s}$$

> [!success] Answer
> $Q_{max} \approx 3.63 \times 10^{-3}\,\text{m}^3/\text{s}$

> [!quote] Source
> [[ENG2085 Note 8 - Bernoulli 2.pdf#page=12|Note 8 p.12]] (labelled "Q4e" in the notes, "Q4c" on the slides) · [[ENG2085 Slides L8 - Bernoulli 2.pdf|Slides L8]]
