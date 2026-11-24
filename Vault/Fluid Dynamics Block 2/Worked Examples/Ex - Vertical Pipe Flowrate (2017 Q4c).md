---
tags: [fm2/example, fm2/dynamics, fm2/past-exam]
icon: ✏️
exam: 2017 Q4c
marks: 6/80
answer: "Q ≈ 11.4 m³/s"
---
# Ex - Vertical Pipe Flowrate (2017 Q4c)

**Uses:** [[Bernoulli Equation]] · [[Continuity Equation]]

## Problem
Water (inviscid, incompressible) flows steadily **down** a vertical pipe that narrows from $D_1 = 2$ m at gauge 1 to $D_2 = 1$ m at gauge 2, which is 10 m lower. Both gauges read 50 kPa. Find the flow rate.

## Solution
$p_1 = p_2$, so the pressure terms cancel.

**Continuity:** $\dfrac{V_2}{V_1} = \dfrac{A_1}{A_2} = \left(\dfrac{2}{1}\right)^2 = 4$

**Bernoulli 1 → 2:**
$$\tfrac12 V_1^2 + g z_1 = \tfrac12 V_2^2 + g z_2 \;\Rightarrow\; g(z_1 - z_2) = \tfrac12 V_1^2\left(\frac{V_2^2}{V_1^2} - 1\right) = \tfrac{15}{2}V_1^2$$
$$V_1 = \sqrt{\frac{2(9.81)(10)}{15}} = 3.61\,\text{m/s}$$
$$Q = A_1 V_1 = \frac{\pi}{4}(2)^2(3.61) = 11.36\,\text{m}^3/\text{s}$$

> [!success] Answer
> $Q \approx 11.4\,\text{m}^3/\text{s}$

> [!tip]
> Equal pressures mean all the potential energy lost in the 10 m drop goes into kinetic energy.

> [!quote] Source
> [[ENG2085 Note 7 - Bernoulli 1.pdf#page=12|Note 7 p.12]] (labelled "Q4e" in the notes, "Q4c" on the slides) · [[ENG2085 Slides L7 - Bernoulli 1.pdf|Slides L7]]
