---
tags: [fm2/statics, fm2/method, fm2/exam-technique]
icon: 🚪
aliases: [Gate problems, Hinge moments, Moment equilibrium]
---
# Gate and Hinge Problems

The typical Q2 exam structure · combines [[Hydrostatic Force on a Plane Surface]] + [[Centre of Pressure]] + statics (moments)

Typical asks: cable tension, holding force, hinge reaction, the depth at which a gate opens, or the air pressure needed to open a hatch.

## Workflow
1. **Geometry** — width, wetted height/length, angle $\theta$, hinge location. Sketch the wetted area as a flat shape.
2. **Area & centroid** — $A$, $h_c$ (vertical) or $y_c$ (along slope). → [[Centroids and Second Moments of Area]]
3. **Force** — $F_R = \gamma h_c A$ (× $\alpha$ if [[Pressurised Tanks|pressurised]]).
4. **COP** — $h_{cop} = h_c + \dfrac{I_{xc}}{A h_c}$ or $y_{cop} = y_c + \dfrac{I_{xc}}{A y_c}$ ([[Inclined Surfaces]]).
5. **Free body diagram**:
   - $F_R$ perpendicular to the gate, at the COP
   - gate weight $W$ vertically down at its centre of gravity (middle of a uniform gate)
   - cable tension / applied force / air pressure force
   - hinge reactions
6. **Moments about the hinge**: $\sum M_H = 0$ — hinge reactions have no moment, so they drop out. Solve for the unknown.

> [!tip] Moment arms
> - $F_R$ is perpendicular to the gate → its arm is the **distance along the gate** from the hinge to the COP.
> - Weight is vertical → arm $= (\text{distance along gate}) \times \cos\theta$.
> - A horizontal cable → arm $= (\text{distance along gate}) \times \sin\theta$.
> - If the depth $h$ is unknown, $F_R$ and $h_{cop}$ both depend on $h$ — write the moment equation in $h$ and solve ([[Ex - Gate Opening Depth (2023)]]).

## Examples
[[Ex - Inclined Gate with Cable (2017 Q3c)]] · [[Ex - Gate Opening Depth (2023)]] · [[Ex - Circular Gate Moment (P2.72)]] · [[Ex - Undersea Hatch (P2.58)]]

> [!quote] Source
> [[ENG2085 Note 5 - Centre of Pressure.pdf#page=11|Note 5 p.11–12]] · [[ENG2085 Note 6 - Flow Characteristics.pdf#page=5|Note 6 p.5–7]]
