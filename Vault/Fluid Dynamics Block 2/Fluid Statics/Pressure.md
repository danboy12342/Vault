---
tags: [fm2/statics, fm2/concept]
icon: 🔵
aliases: [Fluid pressure, Pressure at a point]
---
# Pressure

Part of [[Fluid Statics]] · leads to [[Pascal's Law]], [[Hydrostatic Pressure Distribution]]

## What it is
- In a fluid at rest there is **no shear stress**, so the *only* surface force on a fluid element is pressure.
- Pressure is a **scalar** — the little arrows drawn around a point are *not* a vector, they just show it pushes on every surface.
- Integrating pressure over an area gives a **force** (a vector). The direction comes from the surface, not from pressure:
$$\mathbf F = -\int_A p\,\hat{\mathbf n}\,dA$$
  where $\hat{\mathbf n}$ is the outward normal. The minus sign means pressure always pushes **onto** the surface — it is always **compressive**.
- Magnitude for a uniform pressure: $p = F/A$. Same force, smaller area → higher pressure (thumb vs. syringe needle).

## Units
| Unit | Value |
| :--- | :--- |
| Pascal | $1\,\text{Pa} = 1\,\text{N/m}^2 = 1\,\text{kg/(m s}^2)$ (a small unit) |
| bar | $1\,\text{bar} = 10^5\,\text{Pa}$ |
| atmosphere | $1\,\text{atm} \approx 101\,\text{kPa} = 760\,\text{mm Hg} \approx 10\,300\,\text{mm H}_2\text{O}$ |
| Others | mm H₂O, mm Hg, torr → see [[Pressure Head]] |

Dimensions: $[M L^{-1} T^{-2}]$. Note pressure is also **energy per unit volume** ($\text{J/m}^3 = \text{N/m}^2$), which is why it appears in the [[Bernoulli Equation]].

## Where it's used
Applications of fluid statics: [[Manometry Rules|manometry]] and pressure measurement, buoyancy, forces on dams and gates ([[Hydrostatic Force on a Plane Surface]]), atmospheric pressure ([[Compressible Atmosphere]]), and hydraulic systems ($F_1/A_1 = F_2/A_2$).

## Related
- Reference level matters → [[Absolute and Gauge Pressure]]
- How pressure changes with depth → [[Hydrostatic Pressure Distribution]]

> [!quote] Source
> [[ENG2085 Note 1 - Fluid Statics.pdf#page=3|Note 1 p.3–6]] · [[ENG2085 Slides L1 - Fluid Statics.pdf|Slides L1]]
