---
tags: [fm2/dynamics, fm2/concept]
icon: 💧
aliases: [Inviscid flow, Ideal fluid, No-slip condition]
---
# Ideal vs Real Fluids

Part of [[Elementary Fluid Dynamics]] · underpins the "inviscid" assumption in the [[Bernoulli Equation]]

|                            | **Ideal fluid**                                   | **Real fluid**                            |
| :------------------------- | :------------------------------------------------ | :---------------------------------------- |
| Viscosity                  | zero — **inviscid**                               | non-zero (often small)                    |
| Shear stress               | none, even though the fluid moves and accelerates | present → friction                        |
| Wall condition             | slips along the wall                              | **no-slip**: $u = 0$ at the wall          |
| Velocity profile in a pipe | flat (uniform)                                    | curved, zero at walls                     |
| Regime                     | typically laminar & incompressible                | laminar or turbulent; compressible or not |

> [!note] Why we use the ideal model
> Elementary fluid dynamics = fluid moving under **applied pressure** with no shear, based on Newton's 2nd law. In this block we focus on fluid that is:
> **ideal (inviscid)** · **incompressible** ($\rho$ constant) · **laminar** · **steady**.

> [!tip] Link to continuity
> "Inviscid" is what lets us use one average velocity across a pipe: a **uniform** profile means $\int \rho\,\mathbf u\cdot\mathbf n\,dA = \rho u A$ → see [[Continuity Equation]].

Where the ideal model breaks down → [[Bernoulli Limitations]] (boundary layers, separation) and [[Discharge Coefficient]] (real flow meters).

Related: [[Laminar vs Turbulent Flow]] · [[Steady vs Uniform Flow]]

> [!quote] Source
> [[ENG2085 Note 6 - Flow Characteristics.pdf#page=8|Note 6 p.8–9]]
