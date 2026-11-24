---
tags: [fm2/statics, fm2/device]
icon: 🔄
aliases: [Differential manometer, Closed U-tube manometer]
---
# U-Tube Manometer

Device · solved with the [[Manometry Rules]] · improves on the [[Piezometer]]

Uses a **manometer (gauge) fluid** $\gamma_m$ that doesn't mix with the fluid of interest $\gamma_f$. Usually denser ($\gamma_m > \gamma_f$), e.g. mercury SG ≈ 13.6, Meriam blue SG = 1.75 — so it can measure **higher** and **negative** pressures than a piezometer.

## 1. Open U-tube (one end to atmosphere)
Vessel A → down $h_f$ in fluid → across the bend → up $h_m$ in gauge fluid to the open end E:
$$p_A = p_B,\quad p_C = p_B + \gamma_f h_f,\quad p_C = p_D,\quad p_D = p_E + \gamma_m h_m$$
$$\boxed{p_A = p_{atm} + \gamma_m h_m - \gamma_f h_f}$$

## 2. Closed U-tube / differential (between two vessels)
Vessel 1 (fluid $\gamma_1$) at A, vessel 2 (fluid $\gamma_2$) at G:
$$\boxed{p_A = p_G + \gamma_2 h_3 + \gamma_m h_2 - \gamma_1 h_1}$$
→ gives the **pressure difference** $p_A - p_G$ between the vessels.

> [!tip] If the two vessels hold the same fluid $\gamma$ and the taps are at the same height,
> $p_A - p_B = (\gamma_m - \gamma)\,h$ — the form used with a [[Pitot-Static Tube]] or a [[Venturi Meter]].

## Variants
- Small pressure differences → [[Inclined Manometer]]
- Light gauge fluid on top → [[Inverted Manometer]]

## Examples
[[Ex - Two-Pipe Manometer (2018 Q3b)]] · [[Ex - Slanted Pipe Manometer]] · [[Ex - Oil-Mercury Manometer (P2.38)]] · [[Ex - Contraction with Manometer]]

> [!quote] Source
> [[ENG2085 Note 3 - Manometry.pdf#page=7|Note 3 p.7–8]]
