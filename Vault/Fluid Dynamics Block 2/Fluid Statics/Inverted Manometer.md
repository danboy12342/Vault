---
tags: [fm2/statics, fm2/device]
icon: 🔃
---
# Inverted Manometer

Device · variant of the [[U-Tube Manometer]] · solved with the [[Manometry Rules]]

An upside-down U-tube with a **lighter** gauge fluid trapped at the top ($\rho_m < \rho_w$, e.g. oil at 600 kg/m³, or air). Used to measure the pressure difference between two points in a water pipe.

## Standard result
Tap 1 → up $d$ in water → up $H$ in the light fluid → across the top → down $(d + H)$ in water → tap 2 (taps at the same level):
$$p_1 - \rho_w g d - \rho_m g H + \rho_w g(d + H) = p_2$$
$$\boxed{p_2 - p_1 = (\rho_w - \rho_m)\,g\,H}$$
The connecting length $d$ **cancels**.

> [!tip] Sign sanity check
> The side with **higher** pressure pushes its water column **higher**. In a pipe *expansion* the downstream pressure rises, so the downstream leg reads higher — see [[Ex - Inverted Manometer on Expansion (2019 Q4c)]].

Used in [[Bernoulli with Manometers]].

> [!quote] Source
> [[ENG2085 Note 9 - Applications.pdf#page=13|Note 9 p.13]]
