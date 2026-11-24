---
tags: [fm2/statics, fm2/concept, fm2/memorise]
icon: 🌤️
aliases: [Standard atmosphere, Isothermal atmosphere, Troposphere]
---
# Compressible Atmosphere

Extension of [[Hydrostatic Pressure Distribution]] when density is **not** constant.

Start from $\dfrac{dp}{dz} = -\rho g$ and use the ideal gas law $\rho = \dfrac{p}{RT}$ ($R = 287\,\text{J/(kg K)}$ for air):
$$\frac{dp}{p} = -\frac{g}{R\,T(z)}\,dz$$
Assume $g$ constant (heights ≪ radius of Earth).

## Case A — Isothermal ($T$ constant)
$$\boxed{\frac{p}{p_0} = \exp\!\left[-\frac{g\,(z - z_0)}{R\,T}\right]}$$

## Case B — Standard troposphere (linear temperature)
$T(z) = T_0 - Bz$, with $T_0 = 288.15\,\text{K}$ and lapse rate $B = 0.0065\,\text{K/m}$:
$$\boxed{\frac{p}{p_0} = \left(1 - \frac{Bz}{T_0}\right)^{g/(RB)}}$$
(For air $g/(RB) \approx 5.26$.)

> [!tip] Which to use?
> Small height changes (a lift, a building): treat air as incompressible, $\Delta p = -\rho g\,\Delta z$ — see [[Ex - Lift Ear Pressure (2018 Q3a)]].
> Kilometres: use one of the boxed results — see [[Ex - Air Pressure at 5000 m]] (isothermal gives 56 kPa, linear-T gives 54 kPa).

> [!warning] Not on the formula sheet
> Neither result is on the [[Formula Sheet]] — be able to derive them from $dp/dz = -\rho g$ and $p = \rho RT$.

> [!quote] Source
> [[ENG2085 Note 2 - Pressure Distribution.pdf#page=10|Note 2 p.10–13]]
