---
tags: [fm2/hub, fm2/exam-technique]
icon: 🪤
aliases: [Common mistakes, Errata]
---
# Exam Traps

Part of [[Block 2 MOC]]. The exam is marked three times — "no room for mistakes" (Lecture 0).

## Common slips
- **Vertical vs. along the slope.** $F_R$ uses vertical $h_c$; the COP on a slope uses $y_c$ along the plate → [[Inclined Surfaces]]
- **Wetted area only.** Use just the submerged part of a gate → [[Ex - Inclined Gate with Cable (2017 Q3c)]]
- **Radius vs. diameter** in $A$ and $I_{xc}$ → [[Centroids and Second Moments of Area]]
- **Diameter ratio squared** for the velocity ratio → [[Continuity Equation]]
- **Inclined manometer**: multiply the reading by $\sin\theta$ → [[Inclined Manometer]]
- **Abs vs. gauge** — convert before mixing with $p_{atm} = 0$ → [[Absolute and Gauge Pressure]]
- **$p_{atm}$ on both sides cancels** — changing it changes nothing → [[Ex - Gate Opening Depth (2023)]]
- **Moment arms about a hinge**: perpendicular force → distance along the gate; weight → $\cos\theta$; horizontal cable → $\sin\theta$ → [[Gate and Hinge Problems]]
- **Bernoulli needs one streamline**, unless the flow is uniform → [[Bernoulli Equation]]
- **Static pressure in a free jet is atmospheric**, but at a stagnation point it is not → [[Free Jets]] · [[Stagnation Pressure]]
- **Pipe centreline vs. top of pipe** when reading a piezometer → [[Ex - Overflow Limit (2018 Q4c)]]
- Watch the **sign** of manometer pressure differences → [[Inverted Manometer]]

## ⚠️ Errors found in the course material
> [!bug] Note 6 summary — COP formula
> [[ENG2085 Note 6 - Flow Characteristics.pdf#page=4|Note 6 p.4]] boxes $h_{cop} = h_c + I_{xc}/(A h_c^{2})$. The correct formula is $I_{xc}/(A h_c)$ (Note 5 and the [[Formula Sheet]]). → [[Centre of Pressure]]

> [!bug] Additional worked example 7 (P2.38)
> The solution finds $p_A$ from B = 200 kPa, but the question gives A = 200 kPa. Correct: $p_B \approx 181$ kPa. → [[Ex - Oil-Mercury Manometer (P2.38)]]

> [!bug] Additional worked example 8 (P2.72)
> The solution uses $A = \pi(0.5)^2$ for a 2 m-diameter gate. Correct: $M_A \approx 131$ kN·m, not 32.7. → [[Ex - Circular Gate Moment (P2.72)]]

> [!note] Label differences
> Some exam questions are labelled "Q4e" in the handwritten notes and "Q4c" on the slides (2017, 2018, 2019). Same questions.

> [!question] Worth checking
> The two worked-solution discrepancies above, before relying on either answer. Office hours: Mon and Fri 1–3 pm, Rankine 518.
