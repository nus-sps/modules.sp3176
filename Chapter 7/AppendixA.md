---
label: Chapter 7 Appendix A
layout: page
icon: ":pencil:"
order: -5
author:
  - name: Dr Lim Zhi Han
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/lim.zhihan/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/2019/06/logo_sps20.png
date: 2023-10-25T12:00
description: "The Expanding Universe"
---


For those who are interested...

Introducing particles with mass into space will result in a gravitational
field. Einstein wanted to describe this gravitational field using
geometry of spacetime. In other words, the presence of the massive
particles (with energy and momentum) should influence the curvature
of the spacetime.

With that Einstein went in search for an equation that links between
energy-momentum and geometry of spacetime. But how do we link these
two totally different things together? The hint comes when we consider
that there is a law that governs the conservation of energy-momentum.
The conservation law for energy momentum is:

<span id="EnergyMomCons"></span>
$$
\begin{equation}
\nabla_{c}T_{ab}=0
\end{equation}
$$ 

where $\nabla_{c}$ is some form of differentiation, and $T_{ab}$
is a quantity that describe energy-momentum content. Can we find a
similar one for geometry, like

<span id="Bianchi"></span>
$$
\begin{equation}
\nabla_{c}G_{ab}=0
\end{equation}
$$ 

where $G_{ab}$ is some geometrical term? 

Indeed after many years of searching, Einstein found a "simple" geometrical term that
satisfy the above equation. Without doing the derivation, we state the Einstein's field equation as follows: 

<span id="EinsteinField"></span>
$$
\begin{equation}
R_{ab}-\frac{1}{2}Rg_{ab}=\frac{8\pi G}{c^{4}}T_{ab}
\end{equation}
$$

The terms on the left hand side, $R_{ab}-\frac{1}{2}Rg_{ab}$ is Einstein's
choice for $G_{ab}$ (Yes it satisfies Eq.(\ref{eq:Bianchi}). Each
of the terms is only dependent on the metric. 

<span id="RicciTensor"></span>
$$
\begin{equation}
\text{Ricci tensor: }\;R_{ab}=\sum_{c}\partial_{c}\Gamma_{ab}^{c}-\sum_{c}\partial_{b}\Gamma_{ac}^{c}+\sum_{c,d}\Gamma_{ab}^{c}\Gamma_{cd}^{d}-\sum_{c,d}\Gamma_{ad}^{c}\Gamma_{cb}^{d}
\end{equation}
$$
<span id="Christoffel"></span>
$$
\begin{equation}
\Gamma_{bc}^{a}=\Gamma_{cb}^{a}=\sum_{d}\frac{1}{2}g^{da}(\partial_{b}g_{cd}+\partial_{c}g_{db}-\partial_{d}g_{bc})
\end{equation}
$$

<span id="RicciScalar"></span>
$$
\begin{equation}
\text{Ricci scalar: }\;R=\sum_{a,b}g^{ab}R_{ab}
\end{equation}
$$

<span id="metricInverseMetric"></span>
$$
\begin{equation}
\sum_{b}g^{ab}g_{bc}=\delta_{\phantom{a}c}^{a}
\end{equation}
$$

The right hand side of Einstein's field equation is one that describe
the matter/energy content in the system. 

<span id="EnergyMomentumTensor"></span>
$$
\begin{equation}
\text{Energy momentum tensor }T_{ab}=\sum_{d}g_{ad}T_{\phantom{c}b}^{d}
\end{equation}
$$

In the case of a homogeneous and isotropic Universe, 

<span id="EnergyMomentum"></span>
$$
\begin{align}
T_{\phantom{0}0}^{0} & =-\rho(t)c^{2}\nonumber \\
T_{\phantom{0}1}^{1} & =T_{\phantom{0}2}^{2}=T_{\phantom{0}3}^{3}=p(t)
\end{align}
$$

where $\rho(t)$ is the energy density and $p(t)$ is the pressure
of the matter/energy content in the system (the Universe in this case).

From the FLRW metric
$$
\begin{equation}
ds^{2}=-c^{2}dt^{2}+S(t)^{2}\left(\frac{dr^{2}}{1-kr^{2}}+r^{2}d\theta^{2}+r^{2}\sin^{2}\theta d\phi^{2}\right), \nonumber
\end{equation}
$$

<span id="metricComponents"></span>
$$
\begin{equation}
g_{00}=-c^{2},\,g_{11}=S(t)^{2}\frac{1}{1-kr^{2}},\,g_{22}=S(t)^{2}r^{2},\,g_{33}=S(t)^{2}r^{2}\sin^{2}\theta
\end{equation}
$$

All other $g_{ab}$ are zero. 

<span id="InvMetricComponents"></span>
$$
\begin{equation}
g^{00}=\frac{-1}{c^{2}},\,g^{11}=\frac{1}{S^{2}}(1-kr^{2}),\,g^{22}=\frac{1}{S^{2}r^{2}},\,g^{33}=\frac{1}{S^{2}r^{2}\sin^{2}\theta}
\end{equation}
$$

All other $g^{ab}$ are zero.

We are not going to torture ourselves with calculating $R_{ab}$ and
$R$ here. For now the result will be stated.

The non-zero components of the Ricci tensor are

$$
\begin{align}

R_{00} & = & -\frac{3\ddot{S}}{S} \nonumber \\
R_{11} & = & \frac{1}{1-kr^{2}}\frac{1}{c^{2}}(S\ddot{S}+2\dot{S}^{2}+2kc^{2})\nonumber \\
R_{22} & = & r^{2}\frac{1}{c^{2}}(S\ddot{S}+2\dot{S}^{2}+2kc^{2})\nonumber \\
R_{33} & = & r^{2}\sin^{2}\theta\frac{1}{c^{2}}(S\ddot{S}+2\dot{S}^{2}+2kc^{2})

\end{align}
$$

The Ricci scalar is 
<span id="FRW-Ricci-scalar"></span>
$$
\begin{equation}
R=\frac{6}{c^{2}}(\frac{\ddot{S}}{S}+\frac{\dot{S}^{2}+kc^{2}}{S^{2}})
\end{equation}
$$

With the above information, we can derive the first and second Friedmann
equations using Einstein's field equation by

(i) setting $a=0,b=0$,

$$
\frac{\dot{S}(t)^{2}+kc^{2}}{S(t)^{2}}=\frac{8}{3}\pi G\rho(t)
$$

(ii) set $a=1,b=1$ (or both to 2 or both to 3)
$$
-2\frac{\ddot{S}(t)}{S(t)}-\frac{\dot{S}(t)^{2}+kc^{2}}{S(t)^{2}}=\frac{8\pi G}{c^{2}}p(t)
$$

