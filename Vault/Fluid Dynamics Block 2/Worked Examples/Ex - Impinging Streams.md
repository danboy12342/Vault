---
tags: [fm2/example, fm2/dynamics]
icon: ✏️
answer: "h ≈ 3.64 m"
---
# Ex - Impinging Streams

**Uses:** [[Stagnation Pressure]] · [[Bernoulli Equation]] · [[Absolute and Gauge Pressure]]

## Problem
Streams of water from two tanks meet head-on at point A, which is a **stagnation point**. Tank 1 is open, with its surface $h$ above A. Tank 2 is closed, with air at 172 kPa (abs) = 71 kPa (gauge) above its surface. A is 6 m above the datum and tank 2's water surface is 2.4 m above it. Viscous effects are negligible. Find $h$.

## Solution
At A: $V_A = 0$ (stagnation), and the pressure there is **not** atmospheric.

**Bernoulli 1 → A** ($p_1 = 0$ gauge, $V_1 = 0$):
$$\rho g z_1 = p_A + \rho g z_A \;\Rightarrow\; p_A = \rho g h \qquad (*)$$

**Bernoulli 2 → A** ($V_2 = 0$):
$$p_2 + \rho g z_2 = p_A + \rho g z_A \;\Rightarrow\; p_2 - p_A = \rho g(z_A - z_2) = \rho g(3.6) \qquad (**)$$

Combine:
$$71\,000 - (1000)(9.81)h = (1000)(9.81)(3.6) \;\Rightarrow\; h = 3.64\,\text{m}$$

> [!success] Answer
> $h \approx 3.64$ m

> [!warning]
> Convert the absolute pressure to gauge before mixing it with $p_{atm} = 0$ at the open tank.

> [!quote] Source
> [[ENG2085 Note 9 - Applications.pdf#page=11|Note 9 p.11]] · [[ENG2085 Slides L9 - Applications.pdf|Slides L9]]
