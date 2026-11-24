---
tags: [fm2/statics, fm2/concept, fm2/derivation, fm2/given]
icon: 🎯
aliases: [COP, hcop, Line of action]
---
# Centre of Pressure

Part of [[Fluid Statics]] · gives the line of action of [[Hydrostatic Force on a Plane Surface|the resultant force]] · needed for [[Gate and Hinge Problems]]

The resultant force does **not** act at the centroid. Pressure grows with depth, so the deeper part of the plate pushes harder and the resultant sits **lower**.

## Derivation (free surface open to atmosphere)
The moment of $F_R$ about the surface ($h = 0$) must equal the total moment of the distributed pressure:
$$F_R\,h_{cop} = \int_A h\,(\gamma h)\,dA = \gamma\int_A h^2\,dA = \gamma I_x$$
With $F_R = \gamma h_c A$: $\;h_{cop} = \dfrac{I_x}{h_c A}$.
$I_x$ (about the surface) isn't in tables, so use the [[Centroids and Second Moments of Area|parallel axis theorem]] $I_x = I_{xc} + A h_c^2$:
$$\boxed{h_{cop} = h_c + \frac{I_{xc}}{A\,h_c}}$$

> [!important] Consequences
> - $h_c$, $I_{xc}$, $A$ are all **geometry**, and all positive → $h_{cop} > h_c$: the COP is **always below the centroid**.
> - **Deeper plate** (bigger $h_c$) → $\dfrac{I_{xc}}{A h_c}$ shrinks → COP moves **up towards the centroid**. Very deep surfaces: $h_{cop} \approx h_c$.
> - Only valid for $p = \gamma h$ (static, incompressible, surface open to $p_{atm}$). Otherwise → [[Pressurised Tanks]].

> [!example] Rectangle with its top edge at the surface
> $h_c = a/2$, $A = ab$, $I_{xc} = ba^3/12$ → $h_{cop} = \dfrac{a}{2} + \dfrac{a}{6} = \dfrac{2}{3}a$ — the centroid of the triangular pressure diagram.

## Sideways position (non-symmetric shapes)
If the shape isn't symmetric about a vertical axis, the COP also shifts sideways:
$$x_{cop} = x_c + \frac{I_{xyc}}{A\,y_c}$$
Used in [[Ex - Triangular Panel in Oil Tank]] ($x_{cop}$ is 0.11 m from the centroid).

## Sloping plates
Same formula, but measured **along the slope** $y$ from where the plate's plane meets the surface: $y_{cop} = y_c + \dfrac{I_{xc}}{A y_c}$ → [[Inclined Surfaces]].

> [!bug] Typo in Note 6 summary
> The boxed formula in [[ENG2085 Note 6 - Flow Characteristics.pdf#page=4|Note 6 p.4]] reads $I_{xc}/(A h_c^{2})$ — it should be $I_{xc}/(A h_c)$ as derived in Note 5 and on the [[Formula Sheet]]. Logged in [[Exam Traps]].

## Examples
[[Ex - Inclined Gate with Cable (2017 Q3c)]] · [[Ex - Triangular Panel in Oil Tank]] · [[Ex - Gate Opening Depth (2023)]] · [[Ex - Circular Gate Moment (P2.72)]] · [[Ex - Undersea Hatch (P2.58)]]

> [!quote] Source
> [[ENG2085 Note 5 - Centre of Pressure.pdf#page=4|Note 5 p.4–8]] · [[ENG2085 Slides L5 - Submerged Bodies.pdf|Slides L5]]
