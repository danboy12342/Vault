---
tags: [fm2/dynamics, fm2/derivation]
icon: 🔋
aliases: [Energy derivation of Bernoulli, Work-energy derivation]
---
# Bernoulli Derivation - Energy

Route 1 to the [[Bernoulli Equation]] (Lecture 7). Route 2: [[Bernoulli Derivation - Streamtube]].

**Idea:** to raise both the potential and kinetic energy of a fluid, **work** must be done on it:
$$W = \Delta E_p + \Delta E_k$$
Pressure is energy per unit volume ($\text{J/m}^3 = \text{N/m}^2$), so pressure forces do that work.

## Setup
A control mass of fluid in a sloping pipe that narrows from section 1 (height $h_1$) to section 2 (height $h_2$). Over a short time $dt$, its back face moves $1 \to 1^*$ ($V_1\,dt$) and its front face moves $2 \to 2^*$ ($V_2\,dt$).
Volume swept: $dV_1 = A_1V_1\,dt$, $dV_2 = A_2V_2\,dt$, equal by [[Continuity Equation|continuity]].

## 1. Work done by pressure
- At 1: $W_1 = p_1A_1V_1\,dt$ — **positive** (force pushes in the direction of motion, the fluid gains energy)
- At 2: $W_2 = -p_2A_2V_2\,dt$ — **negative** (the fluid does work against $p_2$)
$$W = (p_1 - p_2)\,A_1V_1\,dt$$

## 2. Gain in potential energy
The middle part ($1^*$ to $2$) is the same before and after, so only the end slices count:
$$\Delta E_p = mg(h_2 - h_1) = \rho A_1V_1\,dt\;g\,(h_2 - h_1)$$

## 3. Gain in kinetic energy
$$\Delta E_k = \tfrac12 m(V_2^2 - V_1^2) = \tfrac12\rho A_1V_1\,dt\,(V_2^2 - V_1^2)$$

## 4. Energy balance
$W = \Delta E_p + \Delta E_k$, and cancel $A_1V_1\,dt$:
$$p_1 - p_2 = \rho g(h_2 - h_1) + \tfrac12\rho(V_2^2 - V_1^2)$$
$$\Rightarrow\; p_1 + \rho g h_1 + \tfrac12\rho V_1^2 = p_2 + \rho g h_2 + \tfrac12\rho V_2^2$$
$$\boxed{p + \rho g h + \tfrac12\rho V^2 = \text{const}}$$

> [!note] Assumptions used
> Small $dt$ (so $h_1^* \approx h_1$, $V_1^* \approx V_1$), continuity ($A_1V_1 = A_2V_2$, i.e. steady and incompressible), and no energy lost to friction (inviscid).

> [!quote] Source
> [[ENG2085 Note 7 - Bernoulli 1.pdf#page=3|Note 7 p.3–9]] · [[ENG2085 Slides L7 - Bernoulli 1.pdf|Slides L7]]
