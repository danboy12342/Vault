---
tags: [fm2/dynamics, fm2/concept]
icon: ⏱️
aliases: [Steady flow, Uniform flow, Unsteady flow, Flow classification]
---
# Steady vs Uniform Flow

Part of [[Elementary Fluid Dynamics]] · "steady" is assumption 1 of the [[Bernoulli Equation]]

> [!summary] The two questions
> - **Steady?** → does anything change **with time** at a fixed point? $\;u_1(t_1) = u_1(t_2)$ → steady. Velocity field $\mathbf v = \mathbf v(\mathbf r)$; unsteady: $\mathbf v = \mathbf v(\mathbf r, t)$.
> - **Uniform?** → does anything change **from place to place**? $\;u_1 = u_2$ → uniform.

The two are independent — a flow can be any combination.

## Characterise these flows (from the notes)
| Situation | Steady? | Uniform? |
| :--- | :--- | :--- |
| Expanding pipe, constant $Q$ ($u_1 > u_2$ by [[Continuity Equation\|continuity]]) | ✅ steady | ❌ non-uniform |
| Constant-diameter pipe, $Q = Q(t)$ changing | ❌ unsteady | ✅ uniform |
| Stone dropped into a still pond, $u(x,t)$ | ❌ unsteady | ❌ non-uniform |
| Wave running up a beach, $u(x,t)$ | ❌ unsteady | ❌ non-uniform |
| Pipe junction, $Q_1 = Q_2 + Q_3$ all constant, $u(x)$ | ✅ steady | ❌ non-uniform |

> [!tip] Exam phrasing
> "Steady" ≠ "uniform". A nozzle with constant flow is steady but **non-uniform** — the fluid accelerates through it, and that change in velocity is exactly what [[Bernoulli Equation|Bernoulli]] describes.
> Uniform flow also matters across streamlines: in uniform flow the Bernoulli constant is the same for every streamline.

Related: [[Streamlines]] · [[Ideal vs Real Fluids]]

> [!quote] Source
> [[ENG2085 Note 6 - Flow Characteristics.pdf#page=12|Note 6 p.12–14]] · [[ENG2085 Note 8 - Bernoulli 2.pdf#page=2|Note 8 p.2]]
