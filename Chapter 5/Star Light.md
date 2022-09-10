---
label: Star Light, Star Bright
layout: default
icon: ":star-struck:"
order: -2
author:
  - name: Dr Lim Zhi Han
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/lim.zhihan/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/2019/06/logo_sps20.png
  - name: Koh Zhi Yong
    email: zhiyong.koh17@nus.edu.sg
    link: https://sps.nus.edu.sg/user/zhiyong.koh17/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/ultimatemember/25/profile_photo-190x190.jpg?1662811284
  - name: Gerald Kang Joon Kiat
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/joonkiat.kang17/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/ultimatemember/21/profile_photo-190x190.jpg?1662826964
date: 2022-09-10T12:00
description: "Through The Looking Glass"
---

## 5.2 Star Light, Star Bright

### 5.2.1 Luminosity-Distance Relationship

#### Inverse Square Law

You have probably noticed that far-away lights seem dimmer than those
closer to you. This is because the light intensity decreases as the
square of the distance between you and the light. The energy emitted
by a light source per unit time, or power, is determined by the light
source itself. Assuming the light is emitted isotropically [^1],
as the light waves travel away from the source, they are spread out
over larger surface areas. As such, the light energy passing through
a location per unit time per unit area, decreases with $1/d^{2}$.
Since your eye, the light detector, is the same size regardless of
how far you are from the light source, the light-capturing area is
the same. But due to the reduced irradiance further away, the total
energy per unit time caught by your eye is reduced, leading to the
perception of a dimmer light.

[^1]: evenly in all directions

A similar phenomenon is at play when we observe stars in the night
sky. Stars are basically spherical light sources far away from us
that emit light isotropically. 

Go to [Activity 1.](<Activities/#Power of the Sun>)

#### Luminosity and Flux

The intrinsic luminosity $L$ of a star quantifies how much light
comes out of a source. It is measured in energy emitted per unit time.

The radiation flux $F$ quantifies how much light is received by a
detector. It measures the light energy per unit time per unit area.

The two quantities above are related by 
$$
F=\frac{L}{4\pi d^{2}}
$$
where $d$ is the distance from the source to the detector.

Strictly speaking, the flux from a star at any point can be defined
to be dependent on the distance between the star and that point. However,
for the purposes of observational astronomy, we are content to constrain
our definition such that the point of observation is Earth. 

#### Magnitude of Brightness

In observational astronomy, we measure the flux from the star as it
reaches our detectors. The flux is quantified in a logarithmic scale
called magnitude. This scale eases the process of comparison between
different stars. The relative brightness between two stars, as observed
on Earth, is quantified by **apparent magnitude** $m$, defined
as follows

$$
\frac{F_{2}}{F_{1}}=100^{(m_{1}-m_{2})/5}
$$

where $F_{1}$, $F_{2}$, are the radiant flux of star 1 and star
2 respectively, and $m_{1}$, $m_{2}$ are the apparent magnitude
of star 1 and star 2 respectively. Note that by this definition, a
brighter star will have a lower apparent magnitude, and that it is
possible to have a negative magnitude. Also note that this definition
merely establishes a way to compare relative brightness, but a zero
point is not explicitly set by this equation.By convention, a star
called Vega is taken as the zero point of the apparent magnitude scale.
From there, the absolute magnitude of Vega is calculated (0.57) which
indirectly defines the zero point of the absolute magnitude scale. 

The apparent magnitude is a measure of the flux from a star as measured
from Earth. Consequently, its measured value depends on the star's
distance away from us. This additional confounding factor can be troublesome
when we wish to discuss the properties of the star itself, and not
how the star appears to us. Thus, we further define the **absolute
magnitude** $M$ as what the apparent magnitude would be, if the star
were exactly 10 pc away from us. 

<span id="magnitudeDistanceRel"></span>
$$
\begin{align}
100^{(m-M)/5} & =\left(\frac{d}{10\text{ pc}}\right)^{2}\nonumber \\
10^{(m-M)/5} & =\frac{d}{10\text{ pc}}\nonumber \\
\frac{m-M}{5} & =\log_{10}\left(\frac{d}{10\text{ pc}}\right)\nonumber \\
m & =M+5\log_{10}\left(\frac{d}{10\text{ pc}}\right)
\end{align}
$$

where $d$ is the distance between the star and us, measured in parsecs
(pc). 

Table 5.1: Table of magnitude of brightness of notable celestial objects. Fill
in the Absolute Magnitude column and check your values.

| Star       | Apparent (Visual) Magnitude  | Absolute Magnitude  | Distance (pc)  |
|------------|------------------------------|---------------------|----------------|
| Sun        | -26.74                       |                     | 4.85 × 10−6    |
| Sirius     | -1.46                        |                     | 2.64           |
| Canopus α  | -0.74                        |                     | 95.0           |
| Centauri   | -0.27                        |                     | 1.35           |
| Arcturus   | -0.05                        |                     | 11.3           |
| Vega       | 0.03                         |                     | 7.67           |
| Capella    | 0.08                         |                     | 13.2           |
| Procyon    | 0.13                         |                     | 264            |
| Achernar   | 0.34                         |                     | 3.37           |
| Betelgeuse | 0.46                         |                     | 42.6           |
| Hadar      | 0.5                          |                     | 215            |
| Altair     | 0.61                         |                     | 120            |
| Acrux      | 0.76                         |                     | 5.21           |
| Aldebaran  | 0.76                         |                     | 98.1           |
| Antares    | 0.96                         |                     | 169            |


So far, we have discussed the luminous properties of stars in general.
Practically, we must also consider that light can have many different
wavelengths. No star emits monochromatic light, nor do any emit light
of uniform intensity across all wavelengths of the electromagnetic
spectrum. Our detectors, however often operate in narrow bands of
wavelengths. To account for the fact that stars emit light across
a wide range of wavelengths, we define the apparent bolometric magnitude
and absolute bolometric magnitude by applying a bolometric correction
to the measured apparent magnitude and absolute magnitude respectively.

$$
\begin{align*}
m_{bol} & =m_{V}+BC\\
M_{bol} & =M_{V}+BC
\end{align*}
$$
where the subscript $V$ stands for "visual" and $bol$ stands
for "bolometric".

The correction serves to account for light emitted outside of visible
wavelengths. The more a star emits in, for example, ultraviolet or
infrared wavelengths, the more negative the correction is (i.e. the
bolometric magnitude is less than the apparent magnitude, indicating
the star is "brighter" than it appears to us). 