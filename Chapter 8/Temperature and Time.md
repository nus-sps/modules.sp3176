---
label: Temperature and Time
layout: default
icon: ":thermometer:"
order: -2
author:
  - name: Dr Lim Zhi Han
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/lim.zhihan/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/2019/06/logo_sps20.png
date: 2022-10-09T12:00
description: "The Big Bang Theory"
---
## 8.2 Temperature and Time

In this section, we find a relation between the temperature of the Universe and time. We assume here that the Universe started off with a (infinitely) hot Big Bang and time starts ticking at the moment of the Big Bang. In 1948, Ralph Alpher, Hans Bethe and George Gamow published a paper to discuss a model of a hot and dense expanding Universe where a burst of nuclear reactions occured, thus explaining the origins of chemical elements. As an interesting side note, while Alpher did most of the work, his supervisor Gamow included Bethe as a co-author without Bethe’s knowledge, thinking that it is a good idea for a paper on cosmic beginnings be created by $$ \alpha $$ (Alpher), $$ \beta $$ (Bethe) and $$ \gamma $$ (Gamow). The model proposed in the $$ \alpha - \beta -\gamma $$ paper was subsequently corrected and modified but the key ideas remained. The early Universe was hot and dense, comprising of photons and relativistic particles in constant collision with each other. The mean free path of the particles was short and the Universe was in thermodynamic equilibrium. The radiation (photons and relativistic particles) is described by a blackbody spectrum with a characteristic temperature. The energy per unit volume having wavelengths between $$ \lambda $$ and $$ \lambda +d\lambda $$ is given by

<span id="BB_blackbody1"></span>
$$
\begin{equation}
u_\lambda d\lambda = \frac{8 \pi hc \lambda^{-5}}{\exp(\frac{hc}{\lambda kT})-1}d\lambda
\end{equation}
$$

We had seen in the previous chapter that the energy density of the radiation field scales inversely to the fourth power of the cosmological scale factor.

<span id="matterDensity"></span>
$$
\begin{equation}
\rho_r \propto S^{-4}
\end{equation}
$$

Thus the radiation energy density present (denoted by a subscript 0) is related to an earlier value by

<span id="energyDensity"></span>
$$
\begin{equation}
S_0^4 u_0 d \lambda_0 = S^4u_\lambda d\lambda
\end{equation}
$$

Since the wavelength is proportional to the scale factor due to cosmological redshift,
$$
u_0d\lambda_0 = \frac{S^4}{S^4_0} \frac{8 \pi hc S^{-5}S^5_0 \lambda^{-5}_0}{\exp(\frac{S_0hc}{S\lambda_0kT})-1} SS^{-1}_0d \lambda_0
$$

<span id="8.4"></span>
$$
\begin{align}
\hspace*{-0.3cm}= \frac{8 \pi hc / \lambda^5_0}{\exp(\frac{hc}{\lambda_0k} \frac{S_0}{ST})-1}d\lambda_0
\end{align}
$$

which implies that

<span id="8.5"></span>
$$
\begin{equation}
ST = S_0T_0
\end{equation}
$$

or

<span id="8.6"></span>
$$
\begin{equation}
T \propto S^{-1}
\end{equation}
$$

Hence if one solves the Friedmann equation in the radiation era, one will have the relation between temperature and time.
For the case of a flat, radiation-dominated Universe[^1],

[^1]: You will work this out in Assignment 4 :)

<span id="8.7"></span>
$$
\begin{equation}
S \propto t^{1/2}.
\end{equation}
$$

Therefore

<span id="8.8"></span>
$$
\begin{equation}
T \propto t^{-1/2}.
\end{equation}
$$

The above temperature–time relation holds for closed and open radiation-dominated Universe as well. The interested reader may work this out yourself!

!!! Try it Yourself!
We had spent considerable efforts to obtain a relation between temperature and time in the early Universe. This was done because the processes that happened during the Big Bang can be better understood
a. by following the falling temperature as time evolves.
b. by following the increasing size of the Universe as time evolves.
c. by following the chronological order of events in a linear time scale.
d. by following the decreasing density of the Universe as time evolves.
!!!

!!! Try it Yourself!
“_Events move much more swiftly at first than later._” (Steven Weinberg, The First Three Minutes). Which of the following is a more likely interpretation of Weinberg’s statement?
a. As the temperature is hotter at earlier times, particles move faster and occurence of events are higher.
b. As the rate of change of temperature is higher at ealier times, the particle composition of the Universe (which depends on temperature) changes more quickly at earlier times.
!!!

!!! Try it Yourself!
Given that 

<span id="8.9"></span>
$$
\begin{equation}
\rho_{rad} = \frac{aT^4}{c^2}
\end{equation}
$$

where $$a$$ is the radiation constant and has the value $$ 7.566 \times 10^{-16} \space \text{J m}^{-3}\text{K}^{-4}. $$ Show that

$$
\begin{align}

T(t) \space = \space & \left( \frac{3c^2}{32 \pi Ga} \right) ^{1/4}t^{-1/2} \nonumber \\

 = \space & \space  (1.52 \times 10^{10}\text{Ks}^{1/2})t^{-1/2}
\end{align}
$$
!!!


