---
tags: [fm2/statics, fm2/concept, fm2/memorise]
icon: 🛢️
aliases: [Pressurisation factor, alpha, Effect of pressurisation]
---
# Pressurised Tanks

Extends [[Hydrostatic Force on a Plane Surface]] and [[Centre of Pressure]] to a closed tank whose gas space is at gauge pressure $p_0^G = p_0 - p_{atm}$.

Pressure on the plate: $p(h) = p_0^G + \gamma h$ — a uniform part plus the usual triangle.

## Force
$$F_R = p_0^G A + \gamma h_c A = \gamma h_c A\left(1 + \frac{p_0^G}{\gamma h_c}\right)$$
$$\boxed{F_R = \gamma\,h_c\,A\,\alpha}, \qquad \alpha = 1 + \frac{p_0^G}{\gamma h_c} \;(>1)$$
$\alpha$ is the **pressurisation factor**.

On a horizontal tank base: $F_R = (p_0^G + \gamma h)A$.

## Centre of pressure
$$h_{cop}F_R = \int_A h\,(p_0^G + \gamma h)\,dA = p_0^G h_c A + \gamma(I_{xc} + A h_c^2) = \gamma A h_c^2\,\alpha + \gamma I_{xc}$$
$$\boxed{h_{cop} = h_c + \frac{I_{xc}}{A\,h_c\,\alpha}}$$
The **only** change from the open-tank result is the $\alpha$ in the denominator. Since $\alpha > 1$, pressurising moves the COP **towards the centroid** (the uniform part of the load acts at the centroid).

> [!tip] Alternative
> Replace the gas pressure by an imaginary extra depth of liquid $p_0^G/\gamma$ above the real surface, then use the open-tank formulas with depths measured from that imaginary surface. Both give the same answer.

> [!warning] Not on the formula sheet
> $\alpha$ isn't on the [[Formula Sheet]] — remember it, or derive it from $\int h\,p\,dA$.

> [!quote] Source
> [[ENG2085 Note 4 - Forces on Submerged Surfaces.pdf#page=5|Note 4 p.5–6]] · [[ENG2085 Note 5 - Centre of Pressure.pdf#page=9|Note 5 p.9–10]]
