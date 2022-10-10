---
label: Expansion of the Newtonian World
layout: default
icon: ":right_anger_bubble:"
order: -3
author:
  - name: Dr Lim Zhi Han
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/lim.zhihan/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/2019/06/logo_sps20.png
date: 2022-10-09T12:00
description: "The Expanding Universe"
---

## 7.3 Expansion of the Newtonian world

### 7.3.1 Derivation of the Friedmann equations for a matter dominated Universe

A Newtonian world is a matter-dominated Universe, governed by Newton's
laws of mechanics and gravity. In this section, we shall derive the
set of differential equations that describes the expansion of the
Universe.

Consider a spherical shell of mass $m$ and radius $R$ enclosing
a spherically symmetric mass[^1] $M$ located at the center. The shell moves radially **outwards**
with the rate $\dot{R}=\frac{dR}{dt}.$ The space encompassed by the
shell expands as a result. 

[^1]:The physical size of the spherically symmetric inner mass does not
matter as long the radius is less than the radius of the shell.

The kinetic energy (KE) of the shell is 

$$
\begin{equation}
T=\frac{1}{2}m\dot{R}^{2}=\frac{1}{2}mH^{2}R^{2}.
\end{equation}
$$

where $H={\displaystyle \frac{\dot{R}}{R}}$. Note that $H$ is a
function of time.

The potential energy (PE) due to Newtonian gravity is
$$
\begin{equation}
U=-\frac{GMm}{R}=-\frac{4}{3}\pi Gm\rho R^{2}
\end{equation}
$$
 The total energy of the system is 
<span id="total-energy"></span>
$$
\begin{equation}
\frac{1}{2}mH^{2}R^{2}-\frac{4}{3}\pi Gm\rho R^{2}=E
\end{equation}
$$
Qualitatively, one can think that the KE increases the volume enclosed
while the PE tries slow down or revert the expansion. The PE is dependent
on the mass density $\rho$ (of the enclosed mass). 

If $\rho$ is large enough such that PE $>$ KE, then the mass shell's
expansion will **not** continue forever.

If $\rho$ is small such that PE $<$ KE, then the mass shell's expansion
will carry on indefinitely.

As such $E=0$ is the critical point for which the Universe is just
able to expand forever. Hence we define the critical density by

$$
\begin{equation}
\rho_{c}=\frac{3H^{2}}{8\pi G}.
\end{equation}
$$

 If $\rho>\rho_{c}$, the Universe is "closed", if $\rho<\rho_{c}$,
the Universe is "open". 

It is useful to define a quantity that represents the scale of the
Universe at different times. We call this the cosmological scale factor
$S(t)$. All lengths (eg. radii, wavelengths) scales with this factor.
$$
\begin{align}
R(t) & \propto & S(t)\nonumber \\
R(t) & = & r\,S(t)
\end{align}
$$
where $r$ is a constant (in time)[^2]. Differentiating the above equation wrt time,

[^2]: In case you wonder why I chose to use the letter $r$ to represent
a constant, the reason will be given next week.

<span id="scale-factor-derivative1"></span>
<span id="scale-factor-derivative2"></span>
$$
\begin{align}
v(t)=\dot{R}(t) & =r\dot{S}(t)\\
\ddot{R}(t) & =r\ddot{S}(t)
\end{align}
$$
 The parameter $H(t)=v/R$ can hence be written as, 
 <span id="Hubble-law-1"></span>
$$
\begin{equation}
H(t)=\frac{\dot{S}(t)}{S(t)}
\end{equation}
$$
 One may also relate the mass density to the scale factor or
 <span id="mass_density_scale"></span>
$$
\begin{equation}
\rho \propto\frac{1}{R^{3}}\propto S^{-3}
\end{equation}
$$
 Substituting Eqs. ([6](#scale-factor-derivative1)) and ([8](#Hubble-law-1))
into Eq. ([3](#total-energy)),

$$
\begin{align}
\frac{1}{2}m\frac{\dot{S}^{2}}{S^{2}}r^{2}S^{2}-\frac{4}{3}\pi Gm\rho r^{2}S^{2} & =E\nonumber \\
\frac{1}{2}mr^{2}\left(\dot{S}^{2}-\frac{8}{3}\pi G\rho S^{2}\right) & =E
\end{align}
$$

Since $E,m$ and $r$ are constants, we can write 
$$
\begin{equation}
\dot{S}^{2}-\frac{8}{3}\pi G\rho S^{2}=-kc^{2}
\end{equation}
$$
This gives
<span id="Friedmann-1"></span>
$$
\begin{equation}
\frac{\dot{S}^{2}+kc^{2}}{S^{2}} = \frac{8}{3}\pi G\rho
\end{equation}
$$

The dynamics of the expanding shell of mass can be further probed
with the Newton's law of gravitation
$$
\begin{equation}
F=m\ddot{R}=-\frac{GMm}{R^{2}}
\end{equation}
$$
Rewriting in terms of the scale factor and mass density, we have
$$
\begin{equation}
\ddot{S}=-\frac{4}{3}\pi G\rho S.
\end{equation}
$$
Comparing with Eq. ([12](#Friedmann-1)), we have 
<span id="Friedmann-2"></span>
$$
\begin{equation}
\frac{2\ddot{S}}{S}+\frac{\dot{S}^{2}+kc^{2}}{S^{2}}=0
\end{equation}
$$
Eqs. ([12](#Friedmann-1)) and ([15](#Friedmann-2)) are the differential
equations for the scale factor $S(t)$. Solving them to find $S(t)$
allows us to track how the size of the Universe varies with time. 


!!! Try it Yourself!
Ex. $k$ can either be positive, negative or zero.
What decides the value of $k$?

==- :bulb: Hint
Hint: look at total energy and density vs critical
density.
===

!!!

## 7.3.2 Evolution of the Matter-Dominated Universe

The Universe will behave differently depending on how much matter
it contains. Putting Eq.([9](#mass_density_scale)) into the differential
equation Eq. ([12](#Friedmann-1)) and solving it numerically, one
can obtain the following scenarios summarized with the figure below.

<span id="matter-dom-Uni"></span>
![Plot of scale factor over time in a matter-dominated expanding universe.
When the density of the Universe is above a certain critical value
$\rho_{c}$, the expansion halts and starts to contract at some point
in time. Otherwise, the expansion continues forever. In all cases
the second derivative of the graphs are negative, meaning that the
rates of expansion slow down over time.](</Resources/Chapter 7/matterDominatedUnivScalefactor.png>)


!!!light Group Discussion!
Discuss in groups how to solve the differential
equation Eq. ([12](#Friedmann-1)) and reproduce the graphs of Figure
[1](#matter-dom-Uni) above. (We will do this slowly in IS!)
!!!
