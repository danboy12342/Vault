---
tags: [fm2/example, fm2/statics, fm2/past-exam]
icon: ✏️
exam: 2017 Q3c
marks: 10/80
answer: "FR = 132.1 kN; T ≈ 39.2 kN"
---
# Ex - Inclined Gate with Cable (2017 Q3c)

**Uses:** [[Inclined Surfaces]] · [[Centre of Pressure]] · [[Gate and Hinge Problems]]

## Problem
A homogeneous rectangular gate, 2.4 m long (up the slope) and 9.6 m wide, weighing 3.6 kN, is inclined at 60° and hinged at its bottom edge. A **horizontal** cable at its top holds it. Water covers 1.8 m of the gate's length. Find the cable force $T$.

## Solution
**1. Force** — wetted area $1.8 \times 9.6 = 17.28\,\text{m}^2$; $y_c = 0.9$ m along the slope from the surface:
$$F_R = \gamma\sin\theta\;y_c A = (9810)(\sin60^\circ)(0.9)(17.28) = 132.1\,\text{kN}$$

**2. COP** — $I_{xc} = \tfrac1{12}(9.6)(1.8)^3 = 4.66\,\text{m}^4$
$$y_{cop} = y_c + \frac{I_{xc}}{A y_c} = 0.9 + \frac{4.66}{(17.28)(0.9)} = 1.2\,\text{m}$$
from the surface, i.e. $1.8 - 1.2 = 0.6$ m from the hinge (along the gate).

**3. Moments about the hinge H**
- $F_R$ (perpendicular to the gate): arm 0.6 m
- $W$ at the gate's centre, 1.2 m along the gate: arm $1.2\cos60^\circ$
- $T$ horizontal at the top, 2.4 m along the gate: arm $2.4\sin60^\circ = 2.08$ m

$$T(2.4\sin60^\circ) = F_R(0.6) + W(1.2\cos60^\circ)$$
$$T = \frac{(132.1)(0.6) + (3.6)(0.6)}{2.078} \approx 39.2\,\text{kN}$$

> [!success] Answer
> $F_R = 132.1\,\text{kN}$, $T \approx 39.2\,\text{kN}$ (39.15 kN in the notes, from rounding the arm to 2.08 m).

> [!quote] Source
> [[ENG2085 Note 4 - Forces on Submerged Surfaces.pdf#page=13|Note 4 p.13–14]] · [[ENG2085 Note 5 - Centre of Pressure.pdf#page=11|Note 5 p.11–12]] · [[ENG2085 Slides L5 - Submerged Bodies.pdf|Slides L5]]
