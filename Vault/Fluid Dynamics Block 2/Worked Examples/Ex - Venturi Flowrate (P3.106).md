---
tags: [fm2/example, fm2/dynamics]
icon: ✏️
source-problem: Munson 3.106 (Additional Worked Example 11)
answer: "Q ≈ 6.10 × 10⁻³ m³/s"
---
# Ex - Venturi Flowrate (P3.106)

**Uses:** [[Venturi Meter]] · [[Continuity Equation]]

## Problem
Find the flow rate through a horizontal Venturi meter under ideal conditions: $D_1 = 31$ mm, $p_1 = 735$ kPa; throat $D_2 = 19$ mm, $p_2 = 550$ kPa; $\gamma = 9.1\,\text{kN/m}^3$.

## Solution
Head form of Bernoulli, $z_1 = z_2$, with $V_1 = (D_2/D_1)^2V_2$:
$$V_2 = \sqrt{\frac{2g\,(p_1 - p_2)/\gamma}{1 - (D_2/D_1)^4}} = \sqrt{\frac{2(9.81)(185/9.1)}{1 - (19/31)^4}} = 21.5\,\text{m/s}$$
$$Q = \frac{\pi}{4}(0.019)^2(21.5) = 6.10 \times 10^{-3}\,\text{m}^3/\text{s}$$

> [!success] Answer
> $Q \approx 6.10 \times 10^{-3}\,\text{m}^3/\text{s}$ (ideal). A real Venturi would give about $0.97\times$ this — see [[Discharge Coefficient]].

> [!quote] Source
> [[ENG2085 Worked Examples.pdf#page=5|Worked examples p.5 (Q11)]] · [[ENG2085 Worked Examples - Solutions.pdf#page=11|Solutions p.11]]
