---
tags: [fm2/dynamics, fm2/derivation]
icon: 🧵
aliases: [Momentum derivation of Bernoulli, Streamtube derivation, Euler along a streamline]
---
# Bernoulli Derivation - Streamtube

Route 2 to the [[Bernoulli Equation]] (Lecture 8) — from **momentum** along a [[Streamlines|streamtube]]. Route 1: [[Bernoulli Derivation - Energy]].

**Assumptions:** steady · incompressible · inviscid.

## Setup
A small streamtube of length $\delta s$ along $\hat{\mathbf s}$. Inlet: $p, V, A$. Outlet: $p + \delta p$, $V + \delta V$, $A + \delta A$. Weight $\delta W$.

**Continuity:** $\rho V A = \rho(V + \delta V)(A + \delta A)$

**Momentum** (outflow − inflow = external force along $\hat{\mathbf s}$):
$$-V(\rho VA) + (V + \delta V)(\rho VA) = \sum F_{ext} \;\Rightarrow\; \sum F_{ext} = \rho V A\,\delta V$$

## External forces along $\hat{\mathbf s}$
**Pressure** — inlet, outlet, plus the side wall. On the sloping side the pressure is about $p + \delta p/2$ (half way), acting on the projected ring area $\delta A$:
$$F_{ps} = pA - (p + \delta p)(A + \delta A) + \left(p + \tfrac{\delta p}{2}\right)\delta A = -A\,\delta p - \tfrac12\,\delta p\,\delta A$$

**Weight** — component along the streamline, with $\delta s\sin\theta = \delta z$:
$$F_{ws} = -\delta W\sin\theta = -\rho g\left(A + \tfrac{\delta A}{2}\right)\delta z$$

## Combine
$$\rho V A\,\delta V = -A\,\delta p - \tfrac12\delta p\,\delta A - \rho g\left(A + \tfrac{\delta A}{2}\right)\delta z$$
Divide by $\rho A$ and drop the second-order small terms ($\delta p\,\delta A$, $\delta A\,\delta z$):
$$V\,\delta V = -\frac{\delta p}{\rho} - g\,\delta z$$
As the tube shrinks, $\delta \to d$. With $V\,dV = d\!\left(\tfrac{V^2}{2}\right)$:
$$\frac{dp}{\rho} + d\!\left(\frac{V^2}{2}\right) + g\,dz = 0$$
Integrate (constant $\rho$):
$$\boxed{p + \rho\frac{V^2}{2} + \rho g z = C} \quad\text{valid along a streamline}$$

## Evaluating the constant
Integrate from a reference point ($z_0$, e.g. the inlet) with known $p(z_0)$, $V(z_0)$:
$$[p - p(z_0)] + \tfrac{\rho}{2}[V^2 - V^2(z_0)] + \rho g(z - z_0) = 0 \;\Rightarrow\; C = p(z_0) + \tfrac12\rho V^2(z_0) + \rho g z_0$$

> [!quote] Source
> [[ENG2085 Note 8 - Bernoulli 2.pdf#page=3|Note 8 p.3–9]] · [[ENG2085 Slides L8 - Bernoulli 2.pdf|Slides L8]]
