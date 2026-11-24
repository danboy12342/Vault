---
tags: [fm2/statics, fm2/concept, fm2/given]
icon: 🧱
aliases: [Resultant force, F = gamma hc A, Force on a submerged plane]
---
# Hydrostatic Force on a Plane Surface

Part of [[Fluid Statics]] · builds on [[Hydrostatic Pressure Distribution]] · location given by [[Centre of Pressure]]

For a submerged plane we want three things:
1. **Magnitude** → this note
2. **Direction** → perpendicular to the surface, pushing onto it ($-\hat{\mathbf n}$, see [[Pressure]])
3. **Line of action** → [[Centre of Pressure]]

## Horizontal surface (tank base)
Pressure is uniform over the base. From above: $p_{atm} + \gamma h$; from below: $p_{atm}$. Atmospheric cancels:
$$F_R = \gamma h A$$

## Vertical (or any) plane surface
Pressure now varies with depth, so integrate over the wetted area:
$$F_R = \int_A p\,dA = \int_A \gamma h\,dA = \gamma\underbrace{\int_A h\,dA}_{\text{first moment of area}}$$
The centroid depth is defined by $h_c A = \int_A h\,dA$, so:
$$\boxed{F_R = \gamma\,h_c\,A = p_c\,A}$$
- $h_c$ = **vertical** depth of the centroid below the free surface
- $A$ = **wetted** area (only the part under the liquid)

> [!summary] What it means
> No integration needed — the force equals the **pressure at the centroid × area**, for any shape, as long as you know the centroid ([[Centroids and Second Moments of Area]]).

> [!note] Atmospheric pressure
> If $p_{atm}$ acts on the free surface *and* the dry side of the plate, it cancels and you use gauge pressure $p = \gamma h$. If the gas above the liquid is pressurised, see [[Pressurised Tanks]].

## Variants
- Sloping plates → [[Inclined Surfaces]] ($F_R = \gamma\sin\theta\,y_c A$, same thing)
- Gas pressure above the liquid → [[Pressurised Tanks]]
- Gates held by hinges / cables → [[Gate and Hinge Problems]]

## Examples
[[Ex - Swimming Pool Walls]] · [[Ex - Inclined Gate with Cable (2017 Q3c)]] · [[Ex - Triangular Panel in Oil Tank]] · [[Ex - Circular Gate Moment (P2.72)]]

> [!quote] Source
> [[ENG2085 Note 4 - Forces on Submerged Surfaces.pdf#page=3|Note 4 p.3–9]] · [[ENG2085 Slides L4 - Flat Surfaces.pdf|Slides L4]] · on the [[Formula Sheet]]
