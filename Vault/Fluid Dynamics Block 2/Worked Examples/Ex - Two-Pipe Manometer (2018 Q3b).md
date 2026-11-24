---
tags: [fm2/example, fm2/statics, fm2/past-exam]
icon: ✏️
exam: 2018 Q3b
marks: 6/80
answer: "pA − pB = −3.33 kPa"
---
# Ex - Two-Pipe Manometer (2018 Q3b)

**Uses:** [[Manometry Rules]] · [[U-Tube Manometer]]
Also Additional Worked Example 6 (Munson 2.30).

## Problem
Two water pipes A and B are connected by a manometer whose gauge fluid has SG = 2.6. From the figure: A is 0.5 + 0.6 = 1.1 m above the left gauge-fluid level C; the right gauge-fluid level D is 0.6 m above C; B is 0.8 m below D (1.3 m total drop from A to B). Find $p_A - p_B$.

## Solution
Gauge fluid: $\gamma = SG\,\gamma_{H_2O} = 2.6\,\gamma_{H_2O}$.
Walk A → C → D → B:
$$p_C = p_A + \gamma_{H_2O}(1.1), \qquad p_D = p_C - \gamma(0.6), \qquad p_B = p_D + \gamma_{H_2O}(0.8)$$
$$p_A - p_B = -0.8\,\gamma_{H_2O} + 2.6(0.6)\,\gamma_{H_2O} - 1.1\,\gamma_{H_2O} = -0.34\,\gamma_{H_2O}$$
$$= -0.34 \times 1000 \times 9.81 = -3.33\,\text{kPa}$$

> [!success] Answer
> $p_A - p_B = -3.33\,\text{kPa}$ (B is at the higher pressure). The posted solution gets −3.32 kPa using $\gamma_{H_2O} = 9.80\,\text{kN/m}^3$.

> [!tip] Technique
> Keep everything in multiples of $\gamma_{H_2O}$ until the last line.

> [!quote] Source
> [[ENG2085 Note 3 - Manometry.pdf#page=10|Note 3 p.10–11]] · [[ENG2085 Worked Examples - Solutions.pdf#page=8|Worked solutions p.8 (Q6)]]
