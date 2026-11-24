---
tags: [fm2/statics, fm2/method, fm2/memorise]
icon: 🧭
aliases: [Manometry, Manometer method, Golden rules of manometry]
---
# Manometry Rules

The method behind every device: [[Barometer]] · [[Piezometer]] · [[U-Tube Manometer]] · [[Inclined Manometer]] · [[Inverted Manometer]]
Comes straight from [[Hydrostatic Pressure Distribution]].

> [!important] The two rules
> 1. **Same level, same fluid → same pressure.** Two points at the same height are at equal pressure *only if* they are joined by a continuous body of the **same** fluid at rest.
> 2. **Step rule** (fluids are incompressible, so $\Delta p = \gamma h$):
>    - going **down** through fluid $\gamma$ → **add** $\gamma h$ (+↓)
>    - going **up** through fluid $\gamma$ → **subtract** $\gamma h$ (−↑)

## Method
1. Start at a point of known (or unknown) pressure, e.g. $p_A$.
2. Walk through the tube, adding $+\gamma_i h_i$ for each descent and $-\gamma_j h_j$ for each ascent, using **that segment's** fluid.
3. Jump sideways only within the same fluid (rule 1).
4. Finish at the other end and set the expression equal to that pressure ($p_B$, or $p_{atm} = 0$ gauge).

> [!tip] Tricks from the worked examples
> - Lengths along a sloped pipe → vertical heights: use $\tan$ or $\sin$ of the angle (e.g. $2\tan30^\circ = 1.15\,\text{m}$ in [[Ex - Slanted Pipe Manometer]]).
> - Specific gravity: $\gamma = SG \times \gamma_{H_2O}$.
> - Write everything in terms of $\gamma_{H_2O}$ until the last line — fewer arithmetic slips ([[Ex - Two-Pipe Manometer (2018 Q3b)]]).
> - Unknown connecting-leg lengths (often called $d$ or $t$) **cancel** — don't panic when a dimension isn't given.

## Coupled with flow
In [[Bernoulli with Manometers]] the manometer gives $\Delta p$ between two pipe taps, and [[Bernoulli Equation|Bernoulli]] + [[Continuity Equation|continuity]] give the same $\Delta p$ in terms of velocity.

## Examples
[[Ex - Two-Pipe Manometer (2018 Q3b)]] · [[Ex - Slanted Pipe Manometer]] · [[Ex - Oil-Mercury Manometer (P2.38)]]

> [!quote] Source
> [[ENG2085 Note 3 - Manometry.pdf#page=7|Note 3 p.7–10]] · [[ENG2085 Note 6 - Flow Characteristics.pdf#page=3|Note 6 p.3 (summary)]]
