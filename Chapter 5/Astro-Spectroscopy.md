---
label: Astro-Spectroscopy
layout: default
icon: ":rainbow:"
order: -4
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
## 5.4 Astro-Spectroscopy

Let us now discuss one of the most valuable tools in Science applied
to the study of the Universe. This section introduces how astronomers
determine the chemical compositions and physical properties of celestial
objects. We will also look at how velocities of stars and galaxies
in the radial direction are deduced by examining their spectra.

### 5.4.1 The Blackbody Spectrum

Have you seen a piece of material start to glow as it is heated to
higher temperatures? Consider an iron rod being heated up. At first
you will feel the heat radiating out of the iron. We are feeling the
infra-red light that the iron emits. The iron will begin to glow in
dull red at temperatures above $500^{\circ}\text{C}$. At even higher
temperature, it changes to bright red to orange, then yellow and progressively
white above $1300^{\circ}\text{C}$. From such observations, it seems
that light is somewhat associated with temperatures. Indeed it does!
In fact, light that are emitted from the iron are not limited to just
visible or infrared but covers the entire electromagnetic spectrum.

Consider a hypothetical body that absorbs all incident electromagnetic
radiation and reflects none. We termed this perfect absorber as a
blackbody, since it will appear black when it does not reflect visible
light. While such a body do not reflect light, it is capable of emitting
(blackbody) radiation in all directions. The body emits electromagnetic
energy as a result of the thermal agitation of electrons in its surface.
When the body is in thermal equilibrium, it emits as much energy as
it absorbs, thus making a blackbody both a perfect absorber and emitter. 

The intensity of the electromagnetic energy emitted by a black body
depends on the wavelengths (frequencies) and the body's
thermal equilibrium temperature; the radiation it emits covers the
entire range of the electromagnetic spectrum. The electromagnetic
energy per unit volume per unit wavelength emitted by a black body
at thermal equilibrium temperature $T$ is given by
$$
u(\lambda,T)=\frac{8\pi hc}{\lambda^{5}}\frac{1}{\exp\left(\frac{hc}{k_{B}T}\right)-1}
$$
where $h$ is the Planck's constant, $k_{B}$ is the Boltzmann's constant
and $c$ is the speed of light in vacuum.

![Blackbody spectra at various temperatures. Image credit: <a href="https://commons.wikimedia.org/wiki/File:Black_body.svg">Darth Kule</a>](</Resources/Chapter 5/BBR.PNG>)

The figure above shows the radiation emitted at thermal equilibrium
by a blackbody at various temperatures. It has a well-defined continuous
energy distribution over the entire range of wavelengths of the electromagnetic
spectrum. For any specific wavelength, there is a corresponding energy
density that depends neither on the chemical composition of the body
nor its shape, but only on its surface temperature.

!!! Try it Yourself!
Take a spin on the [!badge icon="/resources/common/PhET-icon.png" text="PhET"](https://phet.colorado.edu/sims/html/blackbody-spectrum/latest/blackbody-spectrum_en.html) Blackbody spectrum simulation. You might have seen this in Chapter 3!
!!!

At a certain temperature $T$, the energy distribution peaks at a
particular wavelength, which can be approximated from the Wien's
Displacement Law
$$
\lambda_{\text{peak}}=\frac{2.898\times10^{-3}\text{mK}}{T}.
$$

Real materials emit electromagnetic energy at only a fraction of a
blackbody. Like any materials, gases when heated and reached thermal
equilibrium also emits electromagnetic radiation. Stars, which are
huge dense masses of gases at their core, are therefore no exception.
In fact, the interior of stars are good approximations of blackbodies
because their hot gases are very opaque, that is, stellar material
is nearly a perfect absorber of radiation. At thermal equilibrium,
the interior of a star emits electromagnetic energy that has a continuous
spectral energy density nearly similar to that of a black body. However,
when the emitted radiation of a star's interior passes
through the star's atmosphere, the relatively cooler
less dense gases absorb parts of the wavelengths that are emitted.
By studying these wavelengths, we can determine the chemical composition
of the stellar atmosphere. Let us take a look at our closest example:
The Sun.

### 5.4.2 Stellar Classification

The first astro-spectroscopy was carried out more than two hundred
years ago by William Hyde Wollaston (1766 - 1828), who noted dark
lines in the spectrum of sunlight after passing through a prism. About
a decade later, Joseph von Fraunhofer (1787 - 1826) repeated the
experiment using a diffraction grating, and recorded about 600 discrete
dark lines. Atomic physics at that time was not yet developed, so
the nature of the lines remained a mystery.

Modern technologies have allowed us to collect the solar spectrum
above Earth's atmosphere (which also causes absorption
of wavelengths). Even so, some of the notable discrete dark lines
still persist in the solar spectrum. This indicates that these lines
are caused by the Sun's atmosphere. The Sun's
interior emits a continuous blackbody spectrum of radiation. As the
light passes through its cooler outer atmosphere, the atoms and molecules
absorb photons at specific wavelengths to undergo electronic transitions.
The absorbed wavelengths coincide with the emission spectrum of some
heated elements, providing strong evidence that these elements are
present in the solar atmosphere of our Sun. 

![Notable Fraunhofer absorption lines in the solar spectrum. Image credit: <a href="https://en.wikipedia.org/wiki/Fraunhofer_lines">Wikimedia Commons</a>](</Resources/Chapter 5/Fraunhofer_lines.png>)

The Fraunhofer absorption lines provide an insight into the chemical
composition of our Sun's atmosphere. Extending to other
stars, the absorption lines in a stellar spectrum serves as a fingerprint
identification of elements present in the stellar atmosphere. 

It was found that all stars have roughly the same chemical composition
(therefore similar discrete dark lines in their stellar spectrum).
However, the relative strength of the absorption lines varies between
stars. Stars are therefore classified based on the relative strength
of their absorption lines and the line strength mostly traces out
the surface temperature of the star. 

To see why, consider two extreme cases where the surface temperature
of a star is too low or too high. A star with a low surface temperature
will have few electrons in the $n=2$ energy level. As a result the
cool star will exhibit weak Balmer lines. On the other hand, a very
hot star will mean that many atoms are fully ionised. With few bound-state
electrons available, the absorption lines will be weak too. In the
intermediary of the two extreme cases, the intensity of the spectral
lines is determined by the ratio of the population of electrons in
each state. 

Therefore, by carefully analysing the intensity of the absorption
lines in a stellar spectra, one can in principle determine the surface
temperature of the star or at least narrow down its temperature range.
The surface temperature of stars are commonly compared against other
stellar properties, such as luminosity.

Most stars are generally classified under the Morgan Keenan (MK) system
using the letters O, B, A, F, G, K, and M, with O type being the hottest
to M type being the coolest. Each spectral type is also further subdivided
using a numeric digit with 0 being the hottest and 9 being the coolest. 


<span id="spectral-class"></span>

Table 5.2: Spectral classification of stars.

| Spectral Type | Characteristics                                                                                                                                                             | Temperature       |
|---------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|
| M             | These red stars are cool enough for simple molecules form. Spectrum involves lines from CN (cyanogen), TiO (titanium oxide), ZrO (zirconium oxide) and some neutral metals. | <3500 K           |
| K             | Spectral lines show mainly that of neutral and ionised metals.                                                                                                              | 3500 – 5000 K     |
| G             | Strong lines from ionized metals such as Ca2+. Hydrogen lines are also present. This is the spectral type of our Sun!                                                       | 5000 – 6000 K     |
| F             | More hydrogen lines than G.                                                                                                                                                 | 6000 – 7500 K     |
| A             | White-blue in colour. Strongest hydrogen lines.                                                                                                                             | 7500 – 10 000 K   |
| B             | Weak hydrogen lines, helium lines appear.                                                                                                                                   | 10 000 – 30 000 K |
| O             | Blue stars. No hydrogen lines, mainly He2+lines.                                                                                                                            | 30 000 – 60 000 K |


![Stellar spectra of various spectral type stars. Image credit: <a href="https://apod.nasa.gov/apod/ap010530.html">KPNO 0.9-m Telescope, AURA, NOAO, NSF</a>](</Resources/Chapter 5/StellarSpectraClassification.jpg>)


### 5.4.3 Doppler effect

**Go to [Activity 2](<In-Class Activities/#Activity-2>): Doppler Rocket**

The Doppler effect is commonly associated with astro-spectroscopy.
Let's start off the discussion with an interesting
phenomenon you have probably encountered. The pitch of an ambulance
siren increases as it moves towards us while it decreases as it moves
away from us. Such a phenomenon was first described by Christian Doppler
and was eventually termed as the Doppler effect. When a source of
sound and a listener is in relative motion relative to each other,
the frequency of the sound heard is not the same as the source frequency. 

To see why, let's first consider an observer and a
source of sound. The source emits a sound wave with frequency, $f$
,and wavelength $\lambda=c/f$, where $c$ is the speed of sound in
air. To make things easier to visualise, consider the observer's
motion in the horizontal direction. 

![Left: An observer and a stationary source of sound. The wavefronts
reaches the observer at intervals of $1/f=\lambda/c$. Right: The
source moves towards the source. The wavefronts reaches the obsever
at highere frequencies, and thus shorter wavelengths.](</Resources/Chapter 5/DopplerSound.png>)

Now suppose the source moves, say at a constant velocity of $v_{s}$
towards the observer. The frequency and wavelength of the sound wave
as perceived by the observer is now different. In one period $T=1/f$,
the source moves by a distance of $v_{s}T=v_{s}/f$. The wavefronts
towards to observer are compressed by this amount. The observer thus
perceives a shorter wavelength, and experiences a higher frequency
of recieving the wavefronts. Let $\lambda'$ and $f'$ be the wavelength
and frequency measured by the observer. It is conventional in astronomy
to take velocities as "recession velocities". This means sources
that move away from us take on positive velocities. Here since the
source moves towards us, $v_{s}<0$. Hence the compressed wavelength
is 
<span id="DopplerSHiftWavelenth"></span>
$$
\begin{align}
\lambda' & =\lambda+\frac{v_{s}}{f}\nonumber \\
 & =\lambda+v_{s}\frac{\lambda}{c}\nonumber \\
\lambda'-\lambda & =\frac{v_{s}}{c}\lambda\nonumber \\
\frac{\Delta\lambda}{\lambda} & =\frac{v_{s}}{c}
\end{align}
$$

where $\Delta\lambda$ is the shift in wavelength. Here the source
is approaching the observer, $v_{s}<0,$ $\Delta\lambda$ is negative,
meaning that the wavelengths received are shorter than the originally
emitted. If the source is receeding away the observer, $v_{s}>0,\Delta\lambda>0,$
the wavelengths received will be longer. The frequency will shift
in a similar way:
<span id="DopplerSHiftFreq"></span>
$$
\begin{equation}
\frac{\Delta f}{f}=-\frac{v_{s}}{c}
\end{equation}
$$

The shifts in wavelengths and frequencies are called the Doppler shifts.

The Doppler effect of sound waves require the speed of sound wave
($c$), velocities of the source with respect to the observer ($v_{s}$)
to be measured with respect to whatever medium they are travelling
within. Electromagnetic waves, such as light, require no medium to
propagate. Nonetheless, there is still a Doppler relation for electromagnetic
waves (e.g. light) just by having knowledge of the relative velocity
between the observer and the source. Here, we quote the result and
shall not derive the relation:

$$
f'=\sqrt{\frac{c-v_{s}}{c+v_{s}}}f
$$
where $c$ here is the speed of light. In the low (source) velocity
limit where $v_{s}\ll c$, the above equation reduces to Eq.([3](#DopplerSHiftFreq)).
In practical astronomy, this is almost always the case and hence the
simpler formulae Eqs.([2](#DopplerSHiftWavelenth)) and ([3](#DopplerSHiftFreq))
are usually used. 

Generally all celestial objects are in relative motion with us, hence
**all astronomical spectral lines are Doppler shifted**.

Astronomers define the redshift of a spectral line by 
<span id="redshiftFormula"></span>
$$
\begin{equation}
z=\frac{\Delta\lambda}{\lambda}
\end{equation}
$$
This term gives a intuitive picture of shifted spectral lines shfted
towards higher wavelengths due to recession velocities. Together with
Eq.([1](#DopplerSHiftWavelenth)) we see that the higher the (recession)
velocity, the greater the redshift.

### 5.4.4 Binary stars and Exoplanets

The use of astro-spectroscopy has led to many interesting astronomical
discoveries. Here, we briefly discuss how spectroscopy is used to
detect binary stars and exoplanets.

A binary star system is a system of two stars that are gravitationally
bound and orbit around each other about a common center of mass. While
some binary star systems are resolvable by using a telescope, more
often than not either the resolving power of the telescope presents
itself as a limiting factor or the relative brightness between the
stars is too large, resulting in a situation where the glare from
the brighter star makes it difficult to observe the fainter star.
In such situations, astro-spectroscopy is a useful tool in helping
to detect binary star systems through the analysis of the Doppler
effect on their stellar spectra. 

The absorption lines in the stellar
spectra of each star are first blueshifted and then redshifted, as
each star moves towards us and then away from us about their common
center of mass, with the period of their common orbit. In some spectroscopic
binaries, the spectral lines of both stars are visible and lines alternate
between single and double. In other systems, only the spectrum of
one star is observed and the lines periodically blueshift and redshift.
By carefully analysing the Doppler shift of the spectral lines, it
is possible to determine the radial velocity of the system and even
the shape of the binary orbit. 

![Absorption lines getting doppler shifted. In this visual, the yellow star emits light, with absorption lines marked in dotted lines. As the large planet orbits around it, the star wobbles forward and backward. When a star is receeding from us, its wavelength increases, making it redder. Similarly, when the star moves towards us, its wavelength increases, making it bluer. The absorption lines of the star as it is moving is presented as filled lines. Image Credit: <a href="http://www.astro.utoronto.ca/~obertas/">Alysa Obertas</a>](</Resources/Chapter 5/RadialVelocity.gif>)

Astro-spectroscopy also offers a useful indirect method of detecting
exoplanets. If the exoplanet is gravitationally bound to a host star,
both of them will orbit about a common center of mass. Again, we search
for the Doppler shift (periodic blueshift and redshift) in the stellar
spectrum of the host star as the star moves towards and away from
us. However, compared to binary star systems, the spectral shift brought
about by an exoplanet can be much less prominent and harder to detect
if the planet is much smaller in size and orbits far from its host
star, causing the radial velocity of the star-exoplanet system to
be relatively much smaller compared to a binary star system. Therefore,
this method is best used for detecting massive exoplanets orbiting
close to their host stars, since this will allow for a much larger
radial velocity of the system and thus a more observable Doppler shift
in the spectral lines of the stellar spectra.

The discovery of the
first exoplanet was made in 1995 by Swiss astronomers Michael Mayor
and Didier Queloz using astro-spectroscopy, who were both subsequently
awarded the 2019 Nobel Prize in Physics. Since then, there have been
a few different methods aside from spectroscopy used in detecting
exoplanets and the number of verified exoplanets has surpassed 5000. 

### 5.4.5 Redshift of Galaxies

In 1912, Vesto Slipher examined the spectrum of our neighbour galaxy,
Andromeda and reported a shift of the spectral lines. He argued that
this (blue)shift of Andromeda's spectrum is most likely due to Andromeda
moving towards us with a radial velocity of 300 $\text{km/s}$. He
went on to analyse 15 other galaxies and found that some are approaching
us and receding from us. Edwin Hubble and Milton Humason extended
Slipher's work in the 1920-30s and found that most galaxies are moving
aways from us. In addition to finding the redshifts and radial velocities,
they used Cepheids in the galaxies they examine to determine the distance
of these galaxies.

![Photographs of some galaxies and their spectra captured by Milton
Humason using the 100 inch Mount Wilson Telescope. As shown the fainter
the galaxy (thus further), the more red-shifted its spectrum is.](</Resources/Chapter 5/Humason_redshift_spec.PNG>)

In 1929, Hubble published a result that changed the view of the Universe.
He found that with the exception of a few nearby galaxies whose spectra
are blueshifted and thus movng towards us, all other galaxies have
redshifted spectra and move away from us. Even more surprisingly,
**the further away the galaxy, the faster the receeding velocity.**
The proportional relationship between distance and recession velocity
of a galaxy, now known as the Hubble's law

<span id="Hubble-law"></span>
$$
\begin{equation}
v=H_{0}d
\end{equation}
$$

What kind of force is pulling the Universe apart? Gravity is an attractive
force, it will not do this. Electric forces cannot be at play as that
will require the galaxies to be highly charged. Nuclear forces do
not work in long range. What could be the cause of this phenomenon? 

Even now we do not truly know the "cause" of the phenomenon. The
best "explanation" is to *assume that the Universe is expanding*,
and model the expansion based on our existing theories. What is the
meaning of an expanding Universe? We will dig into the this in the
second half of the course.