---
label: Cosmic Distance Ladder
layout: default
icon: ":straight_ruler:"
order: -3
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
## 5.3 Cosmic Distance Ladder

The universe is a very large place. We have one star, the Sun, in
our solar system. Our solar system is part of our galaxy, the Milky
Way. Our galaxy is a part of yet even larger groups of galaxies. To
get a sense of the scale, watch 3:49 to 7:30 of the following [video](https://www.youtube.com/watch?v=Iy7NzjCmUf0&t=229s).


Suffice to say, galaxies contain many stars, and the universe contains
many galaxies. All of these entities are extremely far apart from
each other by human standards. As a result, conducting distance measurements
is extremely challenging. Here, we look at methods used to measure
distances in cosmology.

### 5.3.1 The Astronomical Unit (A.U.)

Recall Kepler's third law which we have learn in the
first chapter. It provides us with a simple formula to determine the
relative size of the planetary orbits of different planets. By knowing
the distance from Earth to our Sun as well as the corresponding periods
of the planets by observation, one can in principle deduce the absolute
scale of our solar system. 

As promising as it may sound, the distance from Earth to our Sun was
not known during the time of Kepler. The Astronomical Unit (A.U.)
is defined as the average distance between Earth and our Sun. It was
first determined during the transit of Venus in 1761 with the help
of a method proposed by the English astronomer Edmund Halley (although
he never lived to see the remarkable phenomenon himself). Below we
shall detail the simplified version of the method. 

The general scheme of the method involves the use of parallax and
requires two observers at different locations of Earth to record the
transit independently before comparing their results. 

![(a) Schematic of the transit of Venus as viewed from two different
locations on Earth. (b) Trigonometric parallax applied to determine
the astronomical unit. (c) Venus in transit on 6 June 2012, 12:08pm.
Venus appeared as a small silhouette disc moving across the Sun. This
picture was taken with a digital camera attached to a 104mm Newtonian
telescope at the NUS multi-purpose field.](</Resources/Chapter 5/TransitOfVenus.PNG>)

The figure above shows the schematic of the transit of Venus as observed
from two different locations on Earth. Details of how the astronomical
unit is derived from trasit-of-Venus observations can be found in
the [Appendix](<Appendix>).

### 5.3.2 Stellar Parallax

The distance between us and nearby stars can be found by the stellar
parallax method as sketched in the figure below. The star of interest
is observed twice, with the second observation made six months after
the first. The (different) positions of the star with respect to the
fixed stars in the background were recorded. The reciprocal of the
parallax angle (half the change in angular position) gives the distance
of the star from Earth.

$$
d=\frac{\text{1 A.U. }}{\tan p\;(\text{radians})}\approx\frac{\text{1 A.U. }}{p\;(\text{radians})}=\frac{1}{p'"\;(\text{arc-seconds})}\text{pc }
$$

$1\text{ radian}=206264.8''\text{ (arcseconds)}$

$1\text{ pc}=2.062648\times10^{5}\text{ A.U. }=3.08568\times10^{16}\text{ m}$

![Stellar parallax. A nearby star will appear to be in different positions
at different times of the year. Accurate observational data recording
and simple geometrical calculations allow us to know the distance
of the nearby star.](</Resources/Chapter 5/stellar_parallax.png>)


### 5.3.3 Cepheid Variables

![A Cepheid variable in M100 observed with the Hubble Space telescope.
Image credit: <a href="https://apod.nasa.gov/apod/ap960110.html">NASA,HST, W. Freedman, R. Kennicutt, J. Mould</a>](</Resources/Chapter 5/CepheidInM100.png>)

An independent method of distance measurement is required before we
can assign absolute magnitudes to the stars we see in the sky. One
such method relies on observing a type of star called a Cepheid variable.
Cepheid variables are stars that contract and expand in size periodically,
brightening and dimming periodically in the process. The first discovery
of such an object was *o Ceti* in 1595. The brightness of this
star varied over five orders of magnitudes with irregular periods
of between 100 to 200 days. In 1784, a pulsating star with a regular
period of 5 days and 9 hours was discovered. Other similar pulsating
stars were subsequently found and were called Cepheid variables. Cepheids
pulsate because the competing forces of gravity (inwards) and pressure
(outwards) are far from equilibrium, similar to a wildly swinging
pendulum. 

![Variation of brightness of a typical Cepheid.](</Resources/Chapter 5/Delta_Cephei_lightcurve.jpg>)

Several discoveries related to the properties of Cepheid variables
made it possible to use them as independent measures of distance.
The first discovery was a empirical relation between the pulsation
period and the perceived brightness of the stars. Henrietta Swan Leavitt
(1868 - 1921) found more than 2000 Cepheid variables, most of them
located in the dwarf galaxy called the Small Magellanic Cloud (SMC).
In 1912, she used a sample of 25 Cepheids in the SMC to show that
the apparent magnitude of brightness varies linearly with the logarithm
of the period of pulsation. 

![Plot of apparent (visual) magnitude of brightness (vertical axis)
versus the logarithm of the period of pulsation. from a sample of
25 Cepheids in the SMC. The upper and lower graphs correspond to the
maximum and minimum magnitudes respectively. Image credit: <a href="https://articles.adsabs.harvard.edu//full/1912HarCi.173....1L/0000001.000.html?high=4dea8c437115295">H. S Leavitt</a>](</Resources/Chapter 5/BrightnessPeriodGraph.jpeg>)

Since the SMC has a diameter of about 7000 light years and its distance
from us is much greater at about 200,000 light years, the stars in
the SMC can be considered to be approximately the same distance from
us. Hence, the **linear relation between absolute magnitudes
and the logarithm of their  pulsation periods of Cepheids** also holds.

The second discovery provided a zero point to calibrate Leavitt's
linear relation. This was first carried out in 1913 by Ejnar Hertzsprung
(1873 - 1967), who measured the absolute distances of a few nearby
Cepheid variables via statistical parallax, a modified stellar parallax
technique that used the motion of the sun as a longer baseline together
with measurements of average velocities of stars. Comparing the absolute
distance with the apparent magnitude of a Cepheid variable, it was
thus possible to determine its absolute magnitude. The absolute magnitude
could then be correlated with its pulsation period, giving a reference
point to use in conjunction with Leavitt's linear relation.
A recent relationship found is 
$$
M_{V}=-2.76\log_{10}P\,-1.40
$$

It was thus possible to obtain the absolute magnitud by measuring
the pulsation period of a Cepheid variable. The apparent magnitudes
of the Cepheids are measured observationally as well. With the apparent
and absolute magnitudes known, we can then determine the distance
to that Cepheid variable using Eq.([Star Light(1)](<Star Light/#magnitudeDistanceRel>)).
In this way, Cepheid variables are used as standard candles to measure
extragalactic distances up to 26 Mpc. 

For further distances, extremely bright objects known as supernovae
are used as standard candles to measure distances up to 2200 Mpc.
Further discussion on supernovae will be found in a later chapter.