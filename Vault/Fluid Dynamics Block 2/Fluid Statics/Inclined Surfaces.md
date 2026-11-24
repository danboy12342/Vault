---
tags: [fm2/statics, fm2/concept]
icon: ↘️
aliases: [Inclined plate, Sloping gate]
---
# Inclined Surfaces

Variant of [[Hydrostatic Force on a Plane Surface]] and [[Centre of Pressure]] for a plate at angle $\theta$ to the free surface.

Let $y$ run **along the plate**, starting where the plate's plane meets the free surface. Then $h = y\sin\theta$:
$$F_R = \int_A \gamma\,y\sin\theta\,dA = \gamma\sin\theta\int_A y\,dA$$
$$\boxed{F_R = \gamma\sin\theta\;y_c\,A = \gamma\,h_c\,A}$$
(the same result — $h_c = y_c\sin\theta$ is still the vertical centroid depth).

$$\boxed{y_{cop} = y_c + \frac{I_{xc}}{A\,y_c}}$$

> [!warning] Use $y_c$, not $h_c$, in the COP formula
> Distances in the COP formula are measured **along the slope**. Mixing in vertical depth is the most common error here.

> [!tip] Wetted area only
> If the plate pokes out of the water (e.g. a 2.4 m gate with only 1.8 m submerged), use the **wetted** length for $A$, $y_c$ and $I_{xc}$ — see [[Ex - Inclined Gate with Cable (2017 Q3c)]].
> If the plate starts below the surface, extend its line up to the surface to find the origin of $y$ — see [[Ex - Triangular Panel in Oil Tank]] and [[Ex - Undersea Hatch (P2.58)]].

> [!quote] Source
> [[ENG2085 Note 4 - Forces on Submerged Surfaces.pdf#page=13|Note 4 p.13–14]] · [[ENG2085 Note 5 - Centre of Pressure.pdf#page=12|Note 5 p.12–14]]
