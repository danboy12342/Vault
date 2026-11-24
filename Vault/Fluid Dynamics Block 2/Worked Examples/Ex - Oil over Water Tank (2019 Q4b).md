---
tags: [fm2/example, fm2/dynamics, fm2/past-exam]
icon: ✏️
exam: 2019 Q4b
marks: 7/80
answer: "V3 = 6.7 m/s; Q ≈ 0.013 m³/s"
---
# Ex - Oil over Water Tank (2019 Q4b)

**Uses:** [[Free Jets]] · [[Bernoulli Equation]] · [[Hydrostatic Pressure Distribution]]

## Problem
A very large open tank holds 2 m of oil (SG = 0.81) on top of water. Water drains through a $d = 50$ mm outlet, 0.7 m below the oil–water interface, as a free jet. Viscous effects are negligible. Find $Q$.

## Solution
Large tank → surface heights barely change, so $V_1 \approx V_2 \approx 0$.

**Bernoulli 1 → 2 in the oil** (surface → interface):
$$p_2 = \rho_{oil}g(z_1 - z_2) = (0.81)(1000)(9.81)(2) = 15.9\,\text{kPa}$$

**Bernoulli 2 → 3 in the water** (interface → jet, $p_3 = 0$):
$$p_2 + \rho_w g z_2 = \tfrac12\rho_w V_3^2 + \rho_w g z_3$$
$$\tfrac12(1000)V_3^2 = 15\,900 + (1000)(9.81)(0.7) \;\Rightarrow\; V_3 = 6.7\,\text{m/s}$$
$$Q = \frac{\pi}{4}(0.05)^2(6.7) = 0.013\,\text{m}^3/\text{s}$$

> [!success] Answer
> $Q \approx 0.013\,\text{m}^3/\text{s}$

> [!note] Reading the handwritten notes
> The height used in the second step must be the **0.7 m** drop from the interface to the outlet. If your copy seems to say 2.7, the answer 6.7 m/s only works with 0.7.

> [!quote] Source
> [[ENG2085 Note 9 - Applications.pdf#page=12|Note 9 p.12]] · [[ENG2085 Slides L9 - Applications.pdf|Slides L9]]
