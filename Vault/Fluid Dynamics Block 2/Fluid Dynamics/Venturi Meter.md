---
tags: [fm2/dynamics, fm2/device, fm2/memorise]
icon: ⏳
aliases: [Venturi, Flow in variable area pipes, Orifice plate, Flow meter]
---
# Venturi Meter

Flow-measurement device · [[Bernoulli Equation]] + [[Continuity Equation]] · corrected by the [[Discharge Coefficient]]

Static pressure is measured at section 1 (pipe) and section 2 (throat), e.g. with [[Piezometer|piezometers]]. Both lie on the same streamline, so Bernoulli applies.

## Derivation (horizontal, $z_1 = z_2$)
Continuity: $\dfrac{V_1}{V_2} = \dfrac{A_2}{A_1}$

Bernoulli:
$$p_1 - p_2 = \tfrac12\rho(V_2^2 - V_1^2) = \tfrac12\rho V_2^2\left[1 - \left(\frac{A_2}{A_1}\right)^2\right]$$

$$V_2 = \sqrt{\frac{2(p_1 - p_2)}{\rho\left[1 - (A_2/A_1)^2\right]}}, \qquad \boxed{Q_{ideal} = A_2\sqrt{\frac{2(p_1 - p_2)}{\rho\left[1 - (A_2/A_1)^2\right]}}}$$

## In terms of head
In the lab $p_1 - p_2$ is read as a head difference, $p_1 - p_2 = \gamma\,\Delta h$:
$$Q = A_2\sqrt{\frac{2g}{1 - (A_2/A_1)^2}}\;\sqrt{\Delta h} = K\sqrt{\Delta h}$$
Plot $Q$ against $\sqrt{\Delta h}$: the ideal line has slope $K$, and real data falls below it with slope $C_d K$ → [[Discharge Coefficient]].

> [!tip] Orifice plate
> Same equation, but an abrupt plate instead of a smooth throat → far more loss ($C_d \approx 0.6$).

> [!warning] Not on the formula sheet
> Derive from Bernoulli + continuity; see [[Formula Sheet]].

## Examples
[[Ex - Venturi Flowrate (P3.106)]] · [[Ex - Contraction with Manometer]] · [[Ex - Vertical Pipe Flowrate (2017 Q4c)]]

> [!quote] Source
> [[ENG2085 Note 9 - Applications.pdf#page=7|Note 9 p.7–9]] · [[ENG2085 Slides L9 - Applications.pdf|Slides L9]]
