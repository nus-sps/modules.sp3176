---
label: Discussion Questions
layout: default
icon: ":speaking_head_in_silhouette:"
order: -6
author:
  - name: Dr Lim Zhi Han
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/lim.zhihan/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/2019/06/logo_sps20.png
date: 2022-10-09T12:00
description: "The Big Bang Theory"
---

## 8.6  Discussion Questions
1. The baryon to photon ratio  
The number of integer-spin particles (such as photons) occupying a quantum state with momentum $$ \bold{p} $$ is given by the Bose-Einstein statistics

<span id="8.25"></span>
$$
\begin{equation}
f(\bold{p}) = \left[ \exp \left( \frac{E(\bold{p})-\mu}{kT} \right) -1 \right]^{-1}.
\end{equation}
$$

Define the number density $ n $ to be

<span id="8.26"></span>
$$
\begin{equation}
n = \frac{g}{(2\pi)^3} \int \frac{4\pi p^2 dp}{\hbar^3} f(p).
\end{equation}
$$

(a) Show that for the case of photons $ (E=pc, \space \mu=0, \space g=2) $,
$$
n_\gamma = \frac{2\zeta (3)}{pi^2} \left( \frac{kT}{\hbar c}\right)^3
$$
where $ \zeta (3) $ = 1.202, $ \zeta $ is the Riemann zeta function defined as 

$$
\zeta(m)=\sum^\infin_{n=1}n^{-m}
$$
==- :bulb: Hint
You may like to use $ 1/(e^x-1) = e^{-x} + e^{-2x} + e^{-3x} + ... $ to evaluate the integral. Or you can use any software (eg. MATHEMATICA) if you wish.
===

(b) Using $ T_0 = 2.735 \text{ K} $, evaluate the present photon number density $ n_{\gamma, 0} $

(c) The ratio of baryon to photon number is of great astrophysical importance. Defined as

<span id="8.27"></span>
$$
\begin{equation}
\eta = \frac{n_B}{n_\gamma},
\end{equation}
$$

this quantity did not change since Big Bang nucleosynthesis. Taking $ \rho_{c,0} = 3H^2_0 /8\pi G = 1.88 \times 10^{−26} h^2 \text{ kg m}^{−3} $, write $ \eta $ in terms of $ \Omega_{B,0} $.  
Note that here, $ h $ is a numerical parameter related to the Hubble constant. (Also, knowing this helps: $ \Omega_{B,0} = \rho_{B,0} / \rho_{c,0} = n_{B,0}m_p/\rho_{c,0} $)

(d) Astronomical observations on deuterium abundance together with numerical simulations of Big Bang nucleosynthesis contrains the value of $ \eta $ to be

<span id="8.27"></span>
$$
\begin{equation}
\eta < 10^{-9}
\end{equation}
$$

Show that this sets a limit for $ \Omega_{B,0} $. Discuss. (You may use h = 0.72 ± 0.08)
