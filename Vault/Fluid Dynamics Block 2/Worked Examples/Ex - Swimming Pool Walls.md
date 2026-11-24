---
tags: [fm2/example, fm2/statics]
icon: ✏️
answer: "Long wall 551.8 kN; short wall 214.6 kN"
---
# Ex - Swimming Pool Walls

**Uses:** [[Hydrostatic Force on a Plane Surface]] · [[Centroids and Second Moments of Area]]

## Problem
A swimming pool is 18 m long and 7 m wide, filled with water to $h = 2.5$ m. Find the resultant force on each side wall.

## Solution
Each wall is a vertical rectangle with its top at the free surface, so $h_c = h/2 = 1.25$ m.

**Long side** (18 m × 2.5 m):
$$F_R = \gamma_w h_c A = (1000)(9.81)(1.25)(2.5 \times 18) = 551.8\,\text{kN}$$

**Short side** (7 m × 2.5 m):
$$F_R = (1000)(9.81)(1.25)(2.5 \times 7) = 214.6\,\text{kN}$$

> [!success] Answer
> Long wall **551.8 kN**, short wall **214.6 kN**.

> [!example] Extension (not in the notes)
> Each force acts at $h_{cop} = \tfrac23(2.5) = 1.67$ m below the surface ([[Centre of Pressure]]). The floor carries $\gamma h A = 9810 \times 2.5 \times 126 \approx 3.09$ MN, uniformly.

> [!quote] Source
> [[ENG2085 Note 4 - Forces on Submerged Surfaces.pdf#page=11|Note 4 p.11–12]] · [[ENG2085 Slides L4 - Flat Surfaces.pdf|Slides L4]]
