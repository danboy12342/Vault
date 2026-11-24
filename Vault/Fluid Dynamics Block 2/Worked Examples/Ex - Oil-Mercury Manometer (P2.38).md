---
tags: [fm2/example, fm2/statics, fm2/check-this]
icon: ⚠️
source-problem: White P2.38 (Additional Worked Example 7)
answer: "pB ≈ 181 kPa"
---
# Ex - Oil-Mercury Manometer (P2.38)

**Uses:** [[Manometry Rules]] · [[U-Tube Manometer]]

## Problem
Container A holds oil at $p_A = 200$ kPa; container B holds water. Moving from A: down 16 cm of oil (SG 0.8) to the mercury, which sits 8 cm above the bottom of the U. On the right, the mercury reaches 22 cm above the bottom, then 18 cm of water up to B. Find $p_B$.
$\gamma_{oil} = 0.8 \times 9790 = 7832$, $\gamma_{Hg} = 133\,100$, $\gamma_w = 9790\,\text{N/m}^3$.

## Solution
Walk A → B: down through oil (+), up through the net 0.14 m of mercury (−), up through water (−):
$$p_B = p_A + \gamma_{oil}(0.16) - \gamma_{Hg}(0.22 - 0.08) - \gamma_w(0.18)$$
$$= 200\,000 + 1253 - 18\,634 - 1762 \approx 180\,900\,\text{Pa}$$

> [!success] Answer
> $p_B \approx 181\,\text{kPa}$

> [!bug] The posted solution looks wrong
> The solutions sheet "begins at B" with 200 kPa and gets $p_A = 219$ kPa. That answers the reverse question (B known, find A). With $p_A = 200$ kPa as the question states, $p_B \approx 181$ kPa. Worth confirming with Dr Febrianto. Logged in [[Exam Traps]].

> [!quote] Source
> [[ENG2085 Worked Examples.pdf#page=3|Worked examples p.3 (Q7)]] · [[ENG2085 Worked Examples - Solutions.pdf#page=8|Solutions p.8]]
