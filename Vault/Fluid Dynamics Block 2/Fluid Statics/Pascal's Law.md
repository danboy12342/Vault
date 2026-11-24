---
tags: [fm2/statics, fm2/concept, fm2/derivation]
icon: 🔺
aliases: [Wedge derivation]
---
# Pascal's Law

Part of [[Fluid Statics]] · builds on [[Pressure]]

> [!summary] Result
> With **no shearing stresses**, the pressure at a point is the **same in every direction**:
> $$p_x = p_y = p_z = p_s = p$$

## Derivation (wedge element)
Take a small wedge of fluid with sides $\delta x, \delta y, \delta z$ and sloping face $\delta s$ at angle $\theta$.
- Geometry: $\delta y = \delta s\cos\theta$, $\delta z = \delta s\sin\theta$, volume $\tfrac12\,\delta x\,\delta y\,\delta z$.
- Forces: pressure on each face ($p_y\,\delta x\,\delta z$, $p_z\,\delta x\,\delta y$, $p_s\,\delta x\,\delta s$) plus weight $W = \gamma\,\tfrac12\delta x\delta y\delta z$. The $x$-faces cancel.
- It is a **control mass** (closed system), not a control volume.

**y-direction:** $\sum F_y = m a_y$
$$p_y\,\delta x\,\delta z - p_s\,\delta x\,(\delta s\sin\theta) = \rho\,\tfrac{\delta x\delta y\delta z}{2}\,a_y \;\Rightarrow\; p_y - p_s = \rho\,a_y\,\tfrac{\delta y}{2}$$

**z-direction:** $\sum F_z = m a_z$
$$p_z - p_s = (\rho a_z + \gamma)\,\tfrac{\delta z}{2}$$

**Shrink the wedge to a point** ($\delta y, \delta z \to 0$): the right-hand sides vanish, so $p_y = p_s$ and $p_z = p_s$.

> [!note] Why it works
> Pressure forces scale with **area** ($\delta^2$), while weight and inertia scale with **volume** ($\delta^3$). As the element shrinks, the volume terms disappear first. Shear stresses would break this — see [[Ideal vs Real Fluids]].

## Connects to
- Next step: how pressure varies *between* points → [[Hydrostatic Pressure Distribution]]

> [!quote] Source
> [[ENG2085 Note 1 - Fluid Statics.pdf#page=8|Note 1 p.8–12]]
