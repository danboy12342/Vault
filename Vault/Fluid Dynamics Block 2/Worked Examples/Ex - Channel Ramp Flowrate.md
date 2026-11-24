---
tags: [fm2/example, fm2/dynamics]
icon: ✏️
answer: "V2 = 5.87 m/s; Q ≈ 17.6 m³/s"
---
# Ex - Channel Ramp Flowrate

**Uses:** [[Bernoulli Equation]] · [[Continuity Equation]] · [[Streamlines]] · [[Hydrostatic Pressure Distribution]]

## Problem
Water flows down a ramp in an open channel. At section 1 the channel is 5 m wide and the water 2 m deep; at section 2 it is 3 m wide and 1 m deep. The bed drops 0.6 m between them. Find $Q$.

## Solution
Use the **middle streamline**: point 1 at mid-depth (1 m below the surface, 1.6 m above the downstream bed); point 2 at mid-depth (0.5 m below the surface and 0.5 m above the bed).
Pressure at each point is hydrostatic below the free surface: $p_1 = p_{atm} + \rho g(1)$, $p_2 = p_{atm} + \rho g(0.5)$.

**Continuity:** $\dfrac{V_1}{V_2} = \dfrac{A_2}{A_1} = \dfrac{1 \times 3}{2 \times 5} = 0.3$

**Bernoulli 1 → 2** (divide by $\rho$, $p_{atm}$ cancels):
$$g(1) + \tfrac12(0.3V_2)^2 + g(1.6) = g(0.5) + \tfrac12V_2^2 + g(0.5)$$
$$\tfrac12(1 - 0.09)V_2^2 = 1.6g \;\Rightarrow\; V_2 = \sqrt{\frac{2(1.6)(9.81)}{0.91}} = 5.87\,\text{m/s}$$
$$Q = V_2A_2 = (5.87)(1 \times 3) = 17.6\,\text{m}^3/\text{s}$$

> [!success] Answer
> $Q \approx 17.6\,\text{m}^3/\text{s}$

> [!tip]
> At any point on the stream, $p/\gamma + z$ equals the free-surface height, so the result is the same whichever streamline you pick.

> [!quote] Source
> [[ENG2085 Note 8 - Bernoulli 2.pdf#page=11|Note 8 p.11]] · [[ENG2085 Slides L8 - Bernoulli 2.pdf|Slides L8]]
