---
label: Cosmology from Einstein's General Relativity
layout: default
icon: ":stars:"
order: -5
author:
  - name: Dr Lim Zhi Han
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/lim.zhihan/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/2019/06/logo_sps20.png
date: 2022-10-09T12:00
description: "The Expanding Universe"
---
## 7.5 Cosmology from Einstein's General Relativity

Einstein's theory of general relativity (GR). GR is a theory that
relates the energy content of a system and its spacetime geometry.
The theory hinges on the idea that spacetime can be curved, and the
curvature dependent on its mass-energy content. Particles move in
(free-falling) motion by following paths of least action governed
by the geometry of curved spacetime. 

The dynamics is encoded in a set of differential equations known as
the Einstein field equation:
$$
R_{ab}-\frac{1}{2}Rg_{ab}=\frac{8\pi G}{c^{4}}T_{ab}
$$
The LHS of the Einstein field equation consists of geometrical terms
($R_{ab},R$ and $g_{ab}$) that can be found with the metric. The
RHS of the field equation ($T_{ab}$) contain information about the
mass-energy content in the system. In essense, the equation relates
mass-energy with spacetime. As aptly summarised by John Wheeler with
12 words, 
:::quote
"Spacetime tells matter how to move; matter tells spacetime how
to curve."
:::

The theory of general relativity is applicable for isolated systems
such as stars and black holes, as well as for the Universe as a whole.
While a full discussion of the theory is out of the scope of this
course, we will examine the results of the theory in the context expanding
Universe. 

### 7.5.1 Friedmann Equations from General Relativity

The FLRW metric
$$
ds^{2}=-c^{2}dt^{2}+S(t)^{2}\left(\frac{dr^{2}}{1-kr^{2}}+r^{2}d\theta^{2}+r^{2}\sin^{2}\theta d\phi^{2}\right)
$$
describes the spacetime geometry of an expanding homogeneous and isotropic
Universe. Fitting it into the Einstein field equations, one obtain
the following equations[^1]:

[^1]: I have for some years taken GR out of the course in order to maintain
sanity for most (including myself). If you are interest to learn a
tiny bit of GR to see how the following equations are derived, See
[Appendix A](Appendix).

<span id="GR_Friedmann1"></span>
$$
\begin{equation}
\frac{\dot{S}(t)^{2}+kc^{2}}{S(t)^{2}}=\frac{8}{3}\pi G\rho(t)
\end{equation}
$$

and

<span id="GR_Friedmann2"></span>
$$
\begin{equation}
-2\frac{\ddot{S}(t)}{S(t)}-\frac{\dot{S}(t)^{2}+kc^{2}}{S(t)^{2}}=\frac{8\pi G}{c^{2}}p(t)
\end{equation}
$$

Eqs ([1](#GR_Friedmann1)) and ([2](#GR_Friedmann2)) are known
as the first and second Friedmann equations respectively. They are
differential equations of the scale factor $S(t)$ that models the
evolution of the expanding Universe. The equations are first derived
by Alexander Friedmann in 1922, six years after Einstein published
the theory of general relativity. 

We find that the GR-derived Friedmann equations, are similar to Eqs
([1](#GR_Friedmann1)) and ([2](#GR_Friedmann2)) which were derived
using Newtonian gravity. The difference, as we shall see below, is
in the energy content. 

Recall that in the Newtonian derivation of the Friedmann equations,
the Universe contain matter where 
<span id="matterDensity"></span>
$$
\begin{equation}
\rho_{\text{matter}}\propto S^{-3}
\end{equation}
$$
This is rather intuitive as energy dilutes as the universe expands,
and in our 3D world, volume $\propto S^{-3}$.

In the context of general relativity, the energy content of the Universe
may not come only from matter. Other forms of energy such as radiation
and vacuum energy can be considered in the GR-derived Friedmann equations.
In the following section, we will examine how the different energy
content affects the expansion of the Universe.

!!! Try it Yourself!
$p$ stands for "pressure". What is the pressure
for gas particles with 0 Kelvins?

What about pressure for photons? Google for radiation
pressure.
!!!

### 7.5.2 Matter, Radiation, Vacuum and Dark Energy

In the Friedmann equations, there are three time dependent functions
$S(t),$ $\rho(t)$ and $p(t)$. The ultimate goal is to solve the
Friedmann equations to obtain the scale factor $S(t).$ However we
cannot solve for $S(t)$ without knowing the energy density $\rho$
and pressure $p$. To do so, some assumptions and simplifications
needs to be made.

We begin with the first Friedmann equation Eq.([1](#GR_Friedmann1))
$$
\dot{S}^{2}+kc^{2}=\frac{8}{3}\pi G\rho S
$$

Differentiating this with respect to time, we have 

$$
\begin{align*}
2\dot{S}\ddot{S} & =\frac{8\pi G}{3}\left(\dot{\rho}S^{2}+\rho2S\dot{S}\right)
\end{align*}
$$

Putting this into the second Friedmann equation Eq.([2](#GR_Friedmann2)),
we have
$$
\begin{align*}
-2\frac{\ddot{S}(t)}{S(t)}-\frac{\dot{S}(t)^{2}+kc^{2}}{S(t)^{2}} & =\frac{8\pi G}{c^{2}}p(t)\\
-\frac{1}{S}\frac{8\pi G}{3\dot{S}}\left(\dot{\rho}S^{2}+\rho2S\dot{S}\right)-\frac{8}{3}\pi G\rho & =\frac{8\pi G}{c^{2}}p\\
-\frac{\dot{\rho}S}{3\dot{S}}-\frac{2\rho}{3}-\frac{\rho}{3} & =\frac{p}{c^{2}}\\
-\frac{\dot{\rho}S}{3\dot{S}} & =\rho+\frac{p}{c^{2}}\\
\dot{\rho} & =-\frac{3\dot{S}}{S}\left(\rho+\frac{p}{c^{2}}\right)\\
\frac{\dot{\rho}}{\rho} & =-\frac{3\dot{S}}{S}\left(1+\frac{p}{\rho c^{2}}\right)\\
\frac{\dot{\rho}}{\rho} & =-\frac{3\dot{S}}{S}\left(1+w\right)
\end{align*}
$$

where
<span id="EoS"></span>
$$
\begin{equation}
w=\frac{p}{\rho c^{2}}
\end{equation}
$$
$w$ is known as the "equation of state". We now assume for our
cosmological models that density and pressure are proportional, meaning
that while $p$ and $\rho$ are functions of time, their ratio $w$
is a constant. Continuing from the above working,
<span id="energyDensity"></span>
$$
\begin{align}
\frac{1}{\rho}\frac{d\rho}{dt} & =-3(1+w)\frac{1}{S}\frac{dS}{dt}\nonumber \\
\frac{d}{dt}\ln\rho & =-3(1+w)\frac{d}{dt}\ln S\nonumber \\
\ln\rho & =\ln S^{-3(1+w)}+\text{constant }\nonumber \\
\rho & \propto S^{-3(1+w)}
\end{align}
$$

Eq. ([5](#energyDensity)) relates the energy content (characterized
by $w$) to the scale factor. Putting this into Eq. ([1](#GR_Friedmann1)),
we have 
$$
\dot{S}^{2}+kc^{2}\propto\frac{8}{3}\pi GS^{-3(1+w)}S
$$
It is now (almost) possible to solve this differential equation! 

We still need to know the value for $w$. Different types of energy
content have different values of $w.$ Common energy contents that
are discussed in modern cosmology are 

- Matter $w_{\text{m}}=0$
- Radiation $w_{\text{r}} = \displaystyle \frac{1}{3}$
- Vacuum energy (aka cosmological constant) $w_{\Lambda}=-1$
- Dark Energy $w_{de}<-{\displaystyle \frac{1}{3}}$


#### 7.5.2.1 Matter-Dominated Universe

In a matter-dominated Universe, $w=0$. From Eq.([5](#energyDensity)),
$$
\rho\propto S^{-3}
$$
The first Friedmann equation becomes 
$$
\dot{S}^{2}+kc^{2}\propto\frac{8}{3}\pi GS^{-2}
$$


!!! Try it Yourself!
Does this looks familiar? What will the solutions
for $S(t)$ look like for $k=-1,0$ and $1$?}
!!!

#### 7.5.2.2 Radiation-Dominated Universe

**The early Universe is often modeled as a radiation dominated
Universe.** Matter in the early Universe will be highly energetic,
moving so fast at near light speed that they can be approximated to
be radiation-like.

Putting $w_{\text{r}}=\frac{1}{3}$
into Eq.([5](#energyDensity)), we find that the energy density
of radiation relates to the scale factor as:
<span id="radiationDensity"></span>
$$
\begin{equation}
\rho_{\text{r}}\propto S^{-4}
\end{equation}
$$

!!! Try it Yourself!
How do we understand Eq.([6](#radiationDensity))
intuitively?
==- :bulb: Hint
Hint: Compare with Eq.([3](#matterDensity)) and
think about cosmological redshift.

===

!!!


#### 7.5.2.3 Dark Energy-Dominated Universe

"Dark-energy" sounds too evil...

In the 1990s, two competing groups of astronomers were hunting down
supernovae. Their goal was to extend Hubble's plot to very far-away
objects. The research question is "How does the Hubble parameter
change over time?" Based on cosmological models known at the time,
the researchers were pretty sure that the expanding universe is decelerating
(see Fig.([EX 1](Expansion#matter-dom-Uni))). 

In 1998 and 1999, both groups published their results: The expansion
of the Universe is not slowing down. It is in fact accelerating! This
shook the scientific community because no one was expecting that,
yet both (competing) groups got the same results. 

On one hand, if we think about it, the expansion of the Universe is
in itself an astonishing "fact" (backed up by observational evidences
from Hubble and after). But we can always attribute the expansion
to an *initial condition*, that the Universe started off expanding.
We could religiously accept this initial condition, or apply the [anthropic principle](https://en.wikipedia.org/wiki/Anthropic_principle)
and reason that if it is otherwise, the Universe would not have evolved
to this stage for us to discuss about this. 

Acceleration, on the other hand is a different game. The cosmological
models that we know of, the energy contents that we are familiar with,
all point towards a Universe whose rate of expansion decreases over
time. We cannot accept a deccelerating Universe by putting on an initial
condition. It needs us to either tweak in the (cosmological) model,
or accept a new kind of energy content. While it seems neccessary
for to believe in the existence of a new energy content in the Universe
to account for the new observational evidence for an accelerating
Universe, no one has a concrete idea of what this energy is. It has
never been directly or even indirectly observed. All we could do is
to "reason" that it must be there, in dominating amounts! Astronomers
call this mysterious energy "**dark energy**"

To create an accelerating Universe (on paper), one can choose some
value for $w$ and put it into the Friedmann equations to obtain $\ddot{S}(t)>0$.
The choice for $w$ is not unique (we shall see that later), but a
popular choice that astronomers like to use is $w=-1$, corresponding
to what we call the vacuum energy. 

Historically the vacuum energy was first introduced by Einstein for
another purpose. He called it the cosmological constant $\Lambda$.
Nowadays these terms are used interchangably. Let us put $w_{\Lambda}=-1$
into Eq.([5](#energyDensity)), ([4](#EoS)), ([1](#GR_Friedmann1))
and ([2](#GR_Friedmann2)):
$$
\begin{align*}
w_{\Lambda} & =-1\\
\rho_{\Lambda} & \propto S^{-3(1-1)}=1\\
\Rightarrow\rho_{\Lambda} & =\text{constant}\\
\text{Let }\rho_{\Lambda} & =\frac{\Lambda}{8\pi G}
\end{align*}
$$
where $\Lambda$ is a positive constant. The energy density associated
with vacuum energy is a constant. 

!!! Try it Yourself!
Normally constants are simple good stuffs, maybe
even a bit boring. In the context of an expanding Universe however,
a constant (vacuum) energy density is a strange strange thing. Why
so?
!!!

The pressure associated with $\Lambda$ can be found using the equation
of state Eq.([4](#EoS)): 
$$
\begin{align*}
-1 & =\frac{p_{\Lambda}}{\rho_{\Lambda}c^{2}}\\
\Rightarrow p_{\Lambda} & =-\frac{\Lambda}{8\pi G}c^{2}
\end{align*}
$$
The first Friedmann equation Eq.([1](#GR_Friedmann1)) becomes
$$
\frac{\dot{S}(t)^{2}+kc^{2}}{S(t)^{2}}=\frac{8}{3}\pi G\frac{\Lambda}{8\pi G}=\frac{\Lambda}{3}
$$

Solving this equation gives the evolution of a expanding vacuum energy
dominated Universe.

The second Friedmann equation Eq.([2](#GR_Friedmann2)) becomes
$$
\begin{align*}
-2\frac{\ddot{S}}{S}-\frac{\Lambda}{3} & =\frac{8\pi G}{c^{2}}\frac{-\Lambda}{8\pi G}c^{2}\\
-2\frac{\ddot{S}}{S} & =\frac{\Lambda}{3}-\Lambda\\
\ddot{S} & =\frac{\Lambda}{3}S\,>0
\end{align*}
$$
Hence a vacuum energy dominated Universe follows an accelerated expansion.

!!! Try it Yourself!
The vacuum energy falls in the catergory known
as dark energy. We have used $w_{\Lambda}=-1$ to obtain an accelerating
Universe ($\ddot{S}>0$). Show that an accelerating Univese can be
made more generally with 

$$
w<-\frac{1}{3}
$$
!!!



!!! Try it Yourself!
Assume that the Universe was initally dominated
by radiation, and $\rho_{\text{r},0}>\rho_{\text{m},0}>\rho_{\Lambda}$.
Plot energy densities of radiation, matter and vacuum energy against
cosmological scale factor. Use log-log scale.
!!!

The 2011 Physics Nobel Prize which was awarded to astronomers who
discovered that our Universe is accelerating. For more information
on the accelerating Universe and dark energy, read [this writeup.](https://www.nobelprize.org/prizes/physics/2011/advanced-information/)

