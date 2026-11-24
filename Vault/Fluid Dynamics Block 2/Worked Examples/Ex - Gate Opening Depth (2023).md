---
tags: [fm2/example, fm2/statics, fm2/past-exam]
icon: ✏️
exam: 2023
answer: "h = 4.77 m (unchanged at 1.5 atm)"
---
# Ex - Gate Opening Depth (2023)

**Uses:** [[Centre of Pressure]] · [[Gate and Hinge Problems]] · [[Absolute and Gauge Pressure]]

## Problem
A rectangular gate, 1 m wide and 2 m high, closes the end of an open water tank ($\gamma_w = 9790\,\text{N/m}^3$). It is hinged along its **top** edge. A force $F = 100$ kN applied at the gate's centroid holds it shut.
(a) Find the water depth $h$ (to the gate's centroid) at which the gate starts to open.
(b) Recompute $h$ if $p_{atm} = 1.5$ atm.

## Solution (a)
$I_{xc} = \tfrac1{12}(1)(2)^3 = \tfrac23\,\text{m}^4$, $A = 2\,\text{m}^2$, $h_c = h$ (unknown).
$$h_{cop} = h + \frac{2/3}{2h} = h + \frac{1}{3h}$$
$$F_R = \gamma h_c A = (9790)(h)(2) = 19\,580\,h$$
The hinge is 1 m above the centroid, at depth $h - 1$. Arm of $F_R$ about the hinge: $h_{cop} - (h - 1) = \frac1{3h} + 1$.
"Just about to open" → moments about the hinge balance:
$$F(1) = F_R\left(\frac{1}{3h} + 1\right) \;\Rightarrow\; 100\,000 = 19\,580h + 6527$$
$$h = 4.77\,\text{m}$$

## Solution (b)
$p_{atm}$ acts on the water surface *and* on the outside of the gate — **it cancels**. No need to recompute.

> [!success] Answer
> (a) $h = 4.77$ m · (b) still 4.77 m

> [!quote] Source
> [[ENG2085 Note 6 - Flow Characteristics.pdf#page=5|Note 6 p.5–7]] · [[ENG2085 Slides L6 - Flow Characteristics.pdf|Slides L6]]
