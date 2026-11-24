---
tags: [fm2/statics, fm2/device]
icon: 📐
---
# Inclined Manometer

Device · variant of the [[U-Tube Manometer]] · solved with the [[Manometry Rules]]

One leg is tilted at angle $\theta$ to the horizontal. A small vertical height change $h_2$ shows up as a much longer reading $\ell_2$ along the tube:
$$\frac{h_2}{\ell_2} = \sin\theta \quad\Rightarrow\quad h_2 = \ell_2\sin\theta$$
→ **better for measuring small pressure differences** (easier to read accurately).

For vessels A (fluid $\gamma_1$) and G (fluid $\gamma_2$), gauge fluid $\gamma_f$:
$$\boxed{p_A = p_G + \gamma_2 h_3 + \gamma_f\,\ell_2\sin\theta - \gamma_1 h_1}$$

> [!warning] Common slip
> The step rule uses **vertical** height. Always convert the slanted reading: $\gamma_f\,\ell_2\sin\theta$, not $\gamma_f\,\ell_2$.

> [!quote] Source
> [[ENG2085 Note 3 - Manometry.pdf#page=9|Note 3 p.9]]
