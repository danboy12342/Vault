---
tags: [fm2/dynamics, fm2/concept, fm2/memorise]
icon: ⛲
aliases: [Torricelli, Free jet, Tank draining]
---
# Free Jets

Application of the [[Bernoulli Equation]] · flow from a large reservoir through a nozzle, losses neglected

**Free jet** = discharges to the atmosphere → $p = p_{atm}$ (0 gauge) in the jet.

Tank with free surface (1) at height $h$ above the outlet (2):
- (1): $p_1 = p_{atm}$, $V_1 \approx 0$ (large tank)
- (2): $p_2 = p_{atm}$ (free jet)

$$\rho g z_1 = \tfrac12\rho V_2^2 + \rho g z_2 \quad\Rightarrow\quad \boxed{V_2 = \sqrt{2gh}}$$

A distance $H$ further down the falling jet (point 3, still at $p_{atm}$):
$$\boxed{V_3 = \sqrt{2g(h + H)}}$$

> [!tip] Variations seen in exams
> - Two liquids stacked in the tank (oil over water): do Bernoulli in two steps — surface → interface in the top fluid, then interface → outlet in the bottom fluid ([[Ex - Oil over Water Tank (2019 Q4b)]]).
> - A nozzle on the end of a pipe from a tank: the exit is the free jet; use continuity for the velocity inside the pipe ([[Ex - Tank Nozzle and Manometer (P3.68)]]).
> - Siphon / hose: the outlet can be **below** the tank bottom; $h$ is measured from the free surface to the outlet ([[Ex - Pool Drain Hose (P3.59)]]).

> [!warning] Not on the formula sheet
> Derive from Bernoulli each time ([[Formula Sheet]]).

> [!quote] Source
> [[ENG2085 Note 9 - Applications.pdf#page=10|Note 9 p.10]]
