---
label: Discussion Questions
layout: default
icon: ":speaking_head_in_silhouette:"
order: -7
author:
  - name: Dr Lim Zhi Han
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/lim.zhihan/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/2019/06/logo_sps20.png
date: 2022-10-09T12:00
description: "The Expanding Universe"
---

## 7.7  Discussion Questions
1. The Friedmann equations derived using Newton's laws are:

<span id="Friedmann1"></span>
$$
\begin{equation}
\frac{\dot{S}^{2}+kc^{2}}{S^{2}}=\frac{8}{3}\pi G\rho
\end{equation}
$$

<span id="Friedmann2"></span>
$$
\begin{equation}
\ddot{S}=-\frac{4}{3}\pi G\rho S
\end{equation}
$$

From the second Friedmann equation Eq.([2](#Friedmann2)) , what
can you say about $\ddot{S}(t)$? 


Does it correspond with our classical idea of gravitation being an
attractive force. 

Does it correspond with current observations of our Universe?

---

2. The reciprocal of the Hubble's constant is often used as an estimate
for the age of the Universe. It can be shown that 
<span id="HubbleAge"></span>
$$
\begin{equation}
t_{0}<\frac{1}{H_{0}}
\end{equation}
$$
where $H_{0}$ is the current value of the Hubble's constant and $t_{0}$
is the current age of the Universe. 

Discuss why Hubble's original value of $H_{0}=550\text{ kms}^{-1}\text{Mpc}^{-1}$
is inappropriate.

---

3. It is possible to obtain Eq.([3](#HubbleAge)) by first showing
that 
<span id="H0t0"></span>
$$
\begin{equation}
H_{0}t_{0}=\int_{0}^{1}\left(1+\frac{\rho_{0}}{\rho_{c,0}}\left(\frac{1}{x}-1\right)\right)^{-1/2}dx
\end{equation}
$$

Show that the intergration on the RHS is less than 1. 

If you are interested in deriving Eq.([4](#H0t0)), please see
[Appendix B](Appendix).

---

4. **Einstein's Static Universe.** Einstein's theory of general
relativity (GR) was formulated in 1916. It was based on the premise
that the metric of spacetime can be dependent on space and time, and
such dependency is related to the energy content in the system. In
1917, Einstein and his contemporaries began to apply GR to cosmology.
Since this more than a decade before Hubble's 1929 observations on
receeding galaxies, Einstein believed that our universe has to be **static** . However, the theory as-is could not result give rise to a
static universe. Perhaps then the theory needs to be modified when
applied to cosmology? Einstein thought. 

GR can be modified in a number of ways . The simplest modification
was to add a constant term. With this added term in the equation,
the Friedmann equations become

<span id="F1-1"></span>
$$
\begin{equation}
\frac{\dot{S}^{2}+kc^{2}}{S^{2}}-\frac{\Lambda}{3}=\frac{8\pi G}{3}\rho
\end{equation}
$$

<span id="F2-1"></span>
$$
\begin{equation}
-2\frac{\ddot{S}}{S}-\frac{\dot{S}^{2}+kc^{2}}{S^{2}}+\Lambda=\frac{8\pi G}{c^{2}}p
\end{equation}
$$
where $\Lambda$ is a constant, also known as the cosmological constant. 

(a) Show that if one set $\dot{S}=0,\ddot{S}=0$ and $p=0$, then
<span id="density_matter_Lambda"></span>
$$
\begin{equation}
\rho=\frac{\Lambda}{4\pi G}
\end{equation}
$$


(b) $S$ is a constant as well. Why?

(c) Since $S$ is a constant, let us set $S=1$. Show that 
<span id="Lambda_matterDom"></span>
$$
\begin{equation}
\Lambda=kc^{2}
\end{equation}
$$


Einstein's static matter-dominated Universe constructed! We have:

$$
S=1,\dot{S}=0,\ddot{S}=0,p=0,\rho=\frac{\Lambda}{4\pi G},\Lambda=kc^{2}
$$
which means that for a static matter-dominated Universe, we need a
positive cosmological constant $\Lambda$ and a positive curvature
$k$.

---

5. **Einstein's Blunder.** Einstein found out from Hubble in
1929 that the Universe is expanding. The addition of the cosmological
constant into the theory is pointless after all! Einstein thought
that this was "the greatest blunder of his life".

Perhaps Einstein was a little harsh on himself. He was just too ahead
of his time! Or perhaps he knew that the static Universe model is
flawed purely from a theoretical point of view too. 

(a) Suppose there is a small perturbation to the scale factor 
$$
S=1+S'
$$
where $S'$ is a function of time and $|S'|\ll1$. Show that 
$$
\rho=\rho_{0}S^{-3}\approx\rho_{0}(1-3S')
$$

(b) Using $\rho=\rho_{0}(1-3S')$ and $S=1+S'$ , show that 
$$
\frac{d^{2}S'}{dt^{2}}=\Lambda S'
$$


(c) Solve ${\displaystyle \frac{d^{2}S'}{dt^{2}}=\Lambda S'}$ with
the initial conditions $S'(0)=S'_{0},\dot{S'}(0)=0$ .

Discuss how
$S'$ evolves. 

Hence Einstein's static universe is an unstable one. A positive perturbation
will cause it to expand while a negative pertubation will cause it
to contract. 

---

6. **Cosmological constant revived.** We saw that the idea of
the cosmological constant to create a static Universe was flawed.
But rather than banishing the cosmological constant, what if it can
be used for another purpose instead? Recent astronomical observations
suggests that the Universe is accelerating ($\ddot{S}>0$). As we
saw in Section 3.7.3, this can be acheived with some form of energy
with equation of state $w<-\frac{1}{3}$ . Can the cosmological constant
be seen as a form of energy?

Let us look at Eq.([5](#F1-1)) and ([6](#F2-1)), but now write
the cosmological constant term on the energy side (RHS) of the equations: 

<span id="F1-1-1"></span>
$$
\begin{equation}
\frac{\dot{S}^{2}+kc^{2}}{S^{2}}=\frac{8\pi G}{3}\rho+\frac{\Lambda}{3}
\end{equation}
$$

<span id="F2-1-1"></span>
$$
\begin{equation}
-2\frac{\ddot{S}}{S}-\frac{\dot{S}^{2}+kc^{2}}{S^{2}}=\frac{8\pi G}{c^{2}}p-\Lambda
\end{equation}
$$
These can be rewitten as 

<span id="F1-1-1-1"></span>
$$
\begin{equation}
\frac{\dot{S}^{2}+kc^{2}}{S^{2}}=\frac{8\pi G}{3}\left(\rho+\rho_{\Lambda}\right)
\end{equation}
$$

<span id="F2-1-1-1"></span>
$$
\begin{equation}
-2\frac{\ddot{S}}{S}-\frac{\dot{S}^{2}+kc^{2}}{S^{2}}=\frac{8\pi G}{c^{2}}\left(p+p_{\Lambda}\right)
\end{equation}
$$
where 
$$
\rho_{\Lambda}=\frac{\Lambda}{8\pi G}
$$
and 
$$
p_{\Lambda}=-\frac{\Lambda c^{2}}{8\pi G}
$$

are intepreted as the energy density and pressure of the cosmological
constant respectively. The equation of state (Eq.([Co 4](Cosmology#EoS)))
is 
$$
w_{\Lambda}=\frac{p_{\Lambda}}{\rho_{\Lambda}c^{2}}=-1
$$
Since $w_{\Lambda}<-\frac{1}{3}$ , it can indeed be used to model
an accelerating Universe! I wonder if Einstein will be happy to know
this....

The "deceleration parameter" $q$ is define by 
$$
q=-\frac{\ddot{S}S}{\dot{S}^{2}}=-\frac{\ddot{S}}{SH^{2}}
$$

a. Show that 
$$
q=\frac{1}{2}\left[\frac{\rho}{\rho_{c}}(1+3w)+\frac{\rho_{\Lambda}}{\rho_{c}}(1+3w_{\Lambda})\right]
$$
where $\rho_{c}=\frac{3H^{2}}{8\pi G}$


b. Using the above expression for the deceleration parameter, discuss
the sign (positive/negative) of it for the cases below. 

(i) Matter dominated Universe ($\rho\gg\rho_{\Lambda}$)

(ii) Cosmological constant dominated Universe ($\rho_{\Lambda}\gg\rho$).

(iii) The dominant energies of the Universe are matter and cosmological
constant (only), with comparable energy densities.

NB. "Comparable" means quantitatively similar in order of magnitude.
Of course one may be larger than the other, and permutations of this
should be considered in your answer.
