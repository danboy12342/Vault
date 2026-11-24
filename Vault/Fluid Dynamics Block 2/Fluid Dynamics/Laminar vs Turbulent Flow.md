---
tags: [fm2/dynamics, fm2/concept]
icon: 🌀
aliases: [Reynolds number, Re, Reynolds experiment]
---
# Laminar vs Turbulent Flow

Part of [[Elementary Fluid Dynamics]] · links back to dimensional analysis in Block 1

**Reynolds' experiment**: ink injected into pipe flow.
- Small flow rate (low velocity) → ink stays a **straight line** → *laminar*
- Medium → wavy → *transitional*
- Large flow rate → ink breaks up, wavy and irregular → *turbulent*

The behaviour depends on the **Reynolds number** (dimensionless):
$$\boxed{Re = \frac{\rho\,U\,D}{\mu}} = \frac{\text{inertial force ("energetic")}}{\text{viscous force ("sluggish")}}$$
$D$ = characteristic length (pipe diameter). Different $\rho, \mu, U, D$ but the **same $Re$** → same flow character.

## Pipe flow ranges (approximate — can't be given precisely)
| Regime | $Re$ |
| :--- | :--- |
| Laminar | $< 2100$ |
| Transitional | $2100 - 4000$ |
| Turbulent | $> 4000$ |

> [!note] Limits depend on the application
> In aerospace, $Re = 500\,000$ can still count as laminar (larger characteristic length, air). Laminar flow is rare in engineering practice, but turbulent flow is hard to analyse — hence the ideal, laminar model in [[Ideal vs Real Fluids]].

Where it matters for Bernoulli: [[Bernoulli Limitations]] (low $Re$ flow past an airfoil follows Bernoulli almost everywhere). Flow-meter $C_d$ also depends weakly on $Re$ → [[Discharge Coefficient]].

> [!quote] Source
> [[ENG2085 Note 6 - Flow Characteristics.pdf#page=10|Note 6 p.10–11]]
