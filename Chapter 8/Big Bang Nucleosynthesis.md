---
label: Big Bang Nucleosynthesis
layout: default
icon: ":bowl_with_spoon:"
order: -3
author:
  - name: Dr Lim Zhi Han
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/lim.zhihan/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/2019/06/logo_sps20.png
date: 2022-10-09T12:00
description: "The Big Bang Theory"
---
## 8.3 Big Bang Nucleosynthesis

One of the success of the Big Bang theory is the model of primordial nucleo-synthesis which correctly predicts the abundance of helium and other light elements in the Universe. In this section we will outline the various nuclear reactions in the first three (and a half) minutes of the Big Bang. We shall begin our discussions at $$ 10^{12} \text{ K} $$ or $$ t \sim 10^{−4} \text{ s} $$, for any earlier and hotter, the physics involved will be out of the scope of this course.
Our Universe just below $$ 10^{12} \text{ K} $$ was a soup of particles comprising of photons ($$ \gamma $$), electrons ($$ e^− $$), positrons ($$ e^+ $$), neutrinos and their anti-particles ($$ \nu_e, \bar \nu_e $$), protons ($$ p^+ $$) and neutrons ($$ n $$). Apart from the massless photons, the speed of the particles follows the Maxwell-Boltzmann distribution[^2],

[^2]: The Maxwell-Boltzmann distribution gives the probability distribution of speeds of a gas at a certain temperature.
[Wikipedia](https://en.wikipedia.org/wiki/Maxwell%E2%80%93Boltzmann_distribution)


<span id="8.11"></span>
$$
\begin{equation}
f(v)=4\pi (\frac{m}{2 \pi kT})^{3/2}v^2\exp(\frac{-mv^2}{2kT}).
\end{equation}
$$

The characteristic thermal energy at a temperature $$ T $$, derived by evaluating the most probable speed in the distribution, is $$ kT $$ . At $$ 10^{12} \text{ K} $$, the characteristic energy

<span id="8.12"></span>
$$
\begin{equation}
kT \approx \text{86 MeV}
\end{equation}
$$

is much larger than the energy difference between the proton and neutron

<span id="8.13"></span>
$$
\begin{equation}
(m_p-m_n)c^2=1.293.
\end{equation}
$$

!!! Try it Yourself!
Plot the Maxwell Boltzmann distribution using $$ \frac{m}{k} = 10^{-4} \text{ and } T=10^{10} $$ with a computer. The plot 
a. is monotonously increasing 
b. is monotonously decreasing
c. has 1 minimum point
d. has 1 maximum point
!!!

!!! Try it Yourself!
Differentiate the Maxwell Boltzmann distribution with respect to $$ v $$ and set it to be zero to obtain the probable speed in the distribution.
!!!

Because of the excessive amount of energy available, protons and neutrons constantly transforms from one to the other via the following equations

<span id="8.14"></span>
$$
\begin{equation}
n+e^+ \rightleftharpoons p^+ + \bar \nu_e
\end{equation}
$$

<span id="8.15"></span>
$$
\begin{equation}
\space n+\nu_e \rightleftharpoons p^+ + e^-
\end{equation}
$$

The ratio of the number density of neutrons and protons is given by the Boltzmann factor

<span id="8.16"></span>
$$
\begin{equation}
\frac{n_n}{n_p}=\exp[-(m_p-m_n)c^2/kT]=0.985.
\end{equation}
$$

This ratio was to drop as the temperature of the Universe falls.

!!! Try it Yourself!
What is the ratio of the number of neutrons to protons at $ 10^{11} \text{ K} $ ?
a. 0.96
b. 0.86
c. 0.76
d. 0.66

!!!

At $ T = 10^{10} \text{ K} $, $ n_n/n_p = 0.223 $. At this temperature, the rates of reactions of $ n \leftrightarrow p^+ $ drops drastically for two reasons. Firstly the energy of neutrinos had fell for them to become much less interacting and unable to initiate reactions in Eqs. ([8.14](#8.14)) and ([8.15](#8.15)). Secondly, as the temperature continues to drop from $ 10^{10} \text{ K} $, energetic photons that are able to fuel the positron–electron pair production 2 $ \gamma \leftrightarrow e^+ + e^− $ are depleting significantly (see Ex. below). This means that more electron and positrons annihilate each other without being replaced. As a result the ratio of 223 neutrons to 1000 protons was almost frozen.  
_Almost_, but not entirely. The $ n_n/n_p $ ratio now falls gradually due to a slow beta decay process

<span id="8.17"></span>
$$
\begin{equation}
n \rightarrow p^+ + e^- + \bar \nu_e
\end{equation}
$$

with a decay half-life of $ \tau_{1/2} = 617s $.

!!! Try it Yourself!
Assuming that the photons and matter particles are in thermodynamic equilibrium, calculate the characteristic energy of the photons at $ 10^{10} \text{ K} $ and compare with the mass of an electron–positron pair.
!!!

!!! Try it Yourself!
Show that beta decay of the neutron results in a drop of $ n_n/n_p $ from 0.223 to 0.164 as the Universe cools from $ 10^{10} \text{ K} $ to $ 10^9 \text{ K} $.
!!!

The proton $ p^+ $ is also known as the hydrogen $ ^1 \text{H} $ nucleus. The next stable nucleus to form is $ ^4_2 \text{He} $, the second lightest element in the Periodic Table. The formation of $ ^4_2 \text{He} $ could not possibly be the product of two protons and two neutrons colliding simultaneously since such events will be too rare. The efficient reactions that produce $ ^4_2 \text{He} $ include

<span id="8.18"></span>
$$
\begin{equation}
\begin{align*}
p^+ + n \space & \rightleftharpoons \space ^2_1 \text{H} + \gamma \\
^2_1 \text{H} + ^2_1 \text{H} \space  &  \rightleftharpoons \space ^3_1 \text{H} + p^+ \\
^3_1 \text{H} + ^2_1 \text{H} \space  & \rightleftharpoons \space ^4_2 \text{He} + n
\end{align*}
\end{equation}
$$

and

<span id="8.19"></span>
$$
\begin{equation}
\begin{align*}
p^+ + n \space & \rightleftharpoons \space ^2_1 \text{H} + \gamma \\
^2_1 \text{H} + ^2_1 \text{H} \space  &  \rightleftharpoons \space ^3_2 \text{He} + n \\
^3_2 \text{He} + ^2_1 \text{H} \space  & \rightleftharpoons \space ^4_2 \text{He} + p^+
\end{align*}
\end{equation}
$$

!!! Try it Yourself!
Compare the binding energy of $ ^2_1 \text{H} $ nucleus and the characteristic energy of photons at $ 10^9 \text{ K} $.
!!!

Notice that in both the reaction schemes above, deuterium $ ^2_1 \text{H} $ needs to be first produced. Above $ 10^9 \text{ K} $, the energetic radiation would have dissociated any $ ^2_1 \text{H} $ nucleus formed, preventing and subsequent reactions. This is know as the deuterium bottleneck. Just below the $ 10^9 \text{ K} $, the deuterium bottleneck is cleared and almost all the neutrons we had started with before $ 10^9 \text{ K} $ were cooked into helium $ ^4_2 \text{He} $. Our sample of $ 164 \space n $ and $ 1000 \space p^+ $ becomes $ 82 \space ^4_2 \text{He} $ and $ 836 \space p^+ $ (or $ ^1 \text{H} $). The mass fraction of $ ^4_2 \text{He} $ in the Universe is thus estimated to be $ 4(82)/[836 + 4(82)] = 0.28 $$. This is consistent with observations which finds the primordial abundance of $ ^4_2 \text{He} $ to be $ 24\% $. This is important as it was shown in separate studies that stella nucleo-synthesis could not have produced so much helium. The fact that Big Bang nucleo-synthesis quantitatively accounts for the helium abundance scores the triumph against the steady state theory, which relied on the stars to produce all the elements.

While the simple account presented above gives a reasonably good estimate to the helium-4 abundance, detailed numerical simulations were made to give a more accurate quantitative abundance of helium-4 and other light elements $ \orange{\text{(see figures 2 and 3 in [?])}} $. The abundance of light elements other than helium-4 is strongly dependent on the baryon[^3] number density. This can be qualitatively understood easily for deuterium. Other than reactions with itself as shown in Eqs. ([8.18](#8.18)) and ([8.19](#8.19)), deuterium also reacts with protons through

[^3]: A class of particles that includes protons and neutrons

<span id="8.20"></span>
$$
\begin{equation}
^2_1 \text{H} + p \rightarrow \space ^3_2 \text{He} + \gamma
\end{equation}
$$

If the baryon number density is high, the reaction is fast, pushing more deuterium to be converted to $ ^3_2 \text{He} $ (which subsequently converts to $ ^3_2 \text{He} $), resulting in a low deuterium abundance. Conversely a low baryon density will result in more deuterium left over. Astronomical observations of the deuterium abundance is hence of great importance as it gives information on the baryon number density. Current observations finds the relative abundance of the light elements to be

<span id="8.21"></span>
$$
\begin{align}
^1_1 \text{H} \quad &:& ^2_1 \text{H} \quad &: &^3_2 \text{He} \quad &: &^4_2 \text{He} \quad &: &^7_3 \text{Li} \nonumber \\
= 0.75  \quad &:& 10^{-5} \quad &: &10^{-5}  \quad &: &0.25  \quad &: \space &10^{-9}
\end{align}