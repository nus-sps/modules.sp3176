---
label: In-Class Activities
layout: default
icon: ":teacher:"
order: -5
author:
  - name: Dr Lim Zhi Han
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/lim.zhihan/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/2019/06/logo_sps20.png
date: 2022-10-09T12:00
description: "The Big Bang Theory"
---
## 8.5 In-Class Activities - Blackbody Radiation

When light enters a material, it can be reflected, absorbed ot transmitted.  
A blackbody can be imagined to be a perfect material that do not transmit nor reflect light. It absorbs all incoming light.  
This does not mean that the blackbody itself does not emit light. In fact a blackbody will emit light as long as its temperature is not zero.  
Blackbody emission is broadband. The intensity profile (over a range of wavelengths) is given by

<span id="8.22"></span>
$$
\begin{equation}
I_\lambda = A \frac{2hc^2}{\lambda^5}\frac{1}{\exp(\frac{hc}{\lambda kT})-1}
\end{equation}
$$

where $ h=6.63 \times 10^{-34} \text{ m}^2 \text{kgs}^{-1} $, $ c = 3.0 \times 10^8 \text{ ms}^{-1} $, $ k=1.38 \times 10^{-23} \text{ m}^2 \text{kgs}^{-2} \text{K}^{-1} $, $ \lambda $ is the wavelength in meters (**not** nm), $ T $ is the temperature in Kelvins, and $ A $ is a geometrical scaling factor.

### Activity 1: Stefan-Boltzmann Law
The total intensity of the radiation over all wavelength is given by the integral
$$
I = \int^{\infin}_0 I_\lambda d\lambda
$$ 

Show that

$$
I \propto T^4
$$

==- :bulb: Hint
Do a bit of rescaling by letting $ \frac{hc}{kT} = \frac{1}{T'} $, and perform the integration with a software.
===

### Activity 2: Wein's Law
The peak of the blackbody emission profile can be found by finding its derivative and equate to 0, i.e. $ \frac{d I_\lambda}{d \lambda} =0 $. Show that
$$
\lambda_{mode}T = 0.29 \text{ cm K}
$$

==- :bulb: Hint
After differentiating, let $ \lambda T = x $
===
Show that the maximum wavelength corresponds to photon energy of the order of $ kT $.

### Activity 3: Finding the temperature of a blackbody emisison
Download the spectrum of an incandescent light bulb collected by an optical spectrometer in Canvas.
Using $ A $ and $ T $ as your fitting parameter, fit the data with Eq.([8.22](#8.22))
What are the values of $ A $ and $ T $ from your fitting?


Also try fitting the data with

<span id="8.23"></span>
$$
\begin{equation}
\tilde I_\lambda = A\frac{2hc^2}{\lambda^5}\exp \left(-\frac{hc}{\lambda kT}\right)
\end{equation}
$$
Does it fit well?


Eq.([8.23](#8.23)) is known as the **Wein's Tail** of the distribution. The approximated expression works well for wavelengths much lower than the mode wavelength.

### Activity 4: Rayleigh-Jeans
When $ E = \frac{hc}{\lambda} \ll kT $,

<span id="8.24"></span>
$$
\begin{equation}
I_\lambda \approx 2ckT\lambda^{-4}
\end{equation}
$$

This is the approximated expression for the other end of the spectrum known as the Rayleigh-Jean side. Show Eq.([8.24](#8.24))