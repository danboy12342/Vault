---
tags: [fm2/example, fm2/dynamics, fm2/past-exam]
icon: ✏️
exam: 2019 Q4c
marks: 8/80
answer: "H ≈ 6.24 m"
---
# Ex - Inverted Manometer on Expansion (2019 Q4c)

**Uses:** [[Bernoulli with Manometers]] · [[Inverted Manometer]] · [[Continuity Equation]]

## Problem
Water flows at $Q = 0.5\,\text{m}^3/\text{s}$ through a horizontal pipe that **expands** from $A_1 = 0.05\,\text{m}^2$ to $A_2 = 0.07\,\text{m}^2$. An inverted manometer with a light fluid ($\rho_m = 600\,\text{kg/m}^3$) joins the two taps. Viscous effects are negligible. Find the reading $H$.

## Solution
$V_1 = Q/A_1 = 10$ m/s. Continuity: $\dfrac{V_1}{V_2} = \dfrac{A_2}{A_1} = \dfrac75$.

**Bernoulli 1 → 2** ($z_1 = z_2$):
$$p_2 - p_1 = \tfrac12\rho(V_1^2 - V_2^2)$$

**Manometer** ($p_A = p_B$ in the light fluid at the top):
$$p_1 - \rho_w g d - \rho_m g H = p_2 - \rho_w g d - \rho_w g H \;\Rightarrow\; p_2 - p_1 = (\rho_w - \rho_m)gH$$

**Equate:**
$$(1000 - 600)(9.81)H = \tfrac12(1000)(10)^2\left[1 - \left(\tfrac57\right)^2\right] \;\Rightarrow\; H = 6.24\,\text{m}$$

> [!success] Answer
> $H \approx 6.24$ m

> [!tip]
> In an expansion the flow slows down, so pressure **rises** downstream ($p_2 > p_1$). The downstream water column is the taller one.

> [!quote] Source
> [[ENG2085 Note 9 - Applications.pdf#page=13|Note 9 p.13]] (labelled "Q4e" in the notes, "Q4c" on the slides) · [[ENG2085 Slides L9 - Applications.pdf|Slides L9]]
