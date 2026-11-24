---
tags: [fm2/example, fm2/statics]
icon: ✏️
answer: "FR = 2.54 MN; ycop = 18.44 m from O; xcop = 0.11 m from centroid"
---
# Ex - Triangular Panel in Oil Tank

**Uses:** [[Inclined Surfaces]] · [[Centre of Pressure]] (incl. $x_{cop}$) · [[Centroids and Second Moments of Area]]

## Problem
A tank of oil ($\rho = 800\,\text{kg/m}^3$) has a right-triangular panel on a wall sloping at 30°. The panel is 12 m long along the slope and 6 m wide, with its centroid 5 + 4 = 9 m below the surface. Find the hydrostatic force and the centre of pressure.

## Solution
**Geometry** (triangle, $a = 12$, $b = 6$, $d = 0$):
$$A = \tfrac12(12)(6) = 36\,\text{m}^2, \quad I_{xc} = \frac{ba^3}{36} = 288\,\text{m}^4, \quad I_{xyc} = \frac{ba^2}{72}(b - 2d) = 72\,\text{m}^4$$

**Force:** $h_c = 9$ m
$$F_R = \gamma h_c A = (800)(9.81)(9)(36) = 2.54 \times 10^6\,\text{N}$$

**COP along the slope** — extend the slope up to the surface at O: $y_c = h_c/\sin30^\circ = 18$ m
$$y_{cop} = y_c + \frac{I_{xc}}{A y_c} = 18 + \frac{288}{(36)(18)} = 18.44\,\text{m from O}$$

**COP sideways** — choose $x_c = 0$ at the centroid:
$$x_{cop} = x_c + \frac{I_{xyc}}{A y_c} = 0 + \frac{72}{648} = 0.11\,\text{m}$$

> [!success] Answer
> $F_R = 2.54\,\text{MN}$, acting 18.44 m down the slope from O and 0.11 m sideways from the centroid.

> [!quote] Source
> [[ENG2085 Note 5 - Centre of Pressure.pdf#page=13|Note 5 p.13–14]] · [[ENG2085 Slides L5 - Submerged Bodies.pdf|Slides L5]]
