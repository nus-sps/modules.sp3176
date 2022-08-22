---
label: Spectroscopy
layout: default
icon: ":rainbow:"
order: -3
author:
  - name: Ervin Chia
    email: ervin.chia19@sps.nus.edu.sg
    link: https://sps.nus.edu.sg/user/ervin.chia19/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/ultimatemember/76/profile_photo-190x190.jpg?1660521922
  - name: Chua Wei Hong
    email: weihong.chua19@sps.nus.edu.sg
    link: https://sps.nus.edu.sg/user/weihong.chua19/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/ultimatemember/74/profile_photo-190x190.jpg?1660522020
  - name: Hillson Hung
    email: hilson.hung19@sps.nus.edu.sg
    link: https://sps.nus.edu.sg/user/hilson.hung19/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/ultimatemember/79/profile_photo-190x190.jpg?1660522020
  - name: Nemo Chen
    email: mengfu.chen20@sps.nus.edu.sg
    link: https://sps.nus.edu.sg/user/mengfu.chen20/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/ultimatemember/172/profile_photo-190x190.jpg?1660521984
date: 2022-08-15T00:00
description: "Light and Atoms"
---

## 3.3 Spectroscopy

We rounded off the section on optics with a very important property
of light: diffraction patterns through gratings. By employing diffraction
gratings, light of **different wavelengths are distributed differently
across space.** This is instrumental because it allows us to break
down incoming light into its constituents; you may think of it as
reverse superposition across space. The technique and field of splitting
light into different wavelengths and observing its interactions with
other matter is known as spectroscopy. A famous and early example
of spectroscopy is Newton's prism where Sir Isaac Newton was able
to split light from a pinhole into its constituent colours using a
glass prism. The image formed as a result of performing spectroscopy
is known as a spectrum, detailing the presence of the constituents
of the light measured. Over the years, new methods and equipment were
developed to split light more effectively and precisely.

### Emission spectra

Optics and spectroscopy has had a long runway to develop; even in
the 1800s, the spectra of all kinds of light sources were investigated.
An emission spectra is one type of spectrum, by which an object is
allowed to emit light. This light is then collected and split into
its constituents. For many sources such as fire, light bulbs and even
the sun, a continuous spectrum was observed. However, when elements
were heated and allowed to emit or excited through electrical means,
scientists observed that their emission spectra were discrete and
not continuous. No one was able to explain why, even though many empirical
observations and formulae were written. One famous example is the
Rydberg formula by Johannes Rydberg: 
<span id="rydberg"></span>
$$
\begin{align}
\frac{1}{\lambda}=RZ^{2}\left(\frac{1}{n_{1}^{2}}-\frac{1}{n_{2}^{2}}\right)
\end{align}
$$
The Rydberg formula originally describes the relationship between
the discrete emission lines observed and their wavelengths. It was
eventually found to be extendable to certain specific elements such
as sodium and lithium. Discreteness of the emission is captured by
number $n$: these values are only allowed to take integer values,
and emissions are described from a higher integer $n_{2}$ to a lower
$n_{1}$.

As heavier elements were investigated, the emission spectra quickly
become very complicated; some having very fine differences as well
as having many more emissions. Compare the complexity of Hydrogen's
spectra to that of Iron: 

![Emission Spectra of Hydrogen (top) and Iron (bottom)](</Resources/Chapter 3/Hydrogen_spectral_lines.jpg>)


This then became a huge problem that physicists were unable to solve
for a long time: What governed these emissions, and why were they
unique to each element? Even after repeating spectroscopy on materials
under different conditions such as temperature or pressure, the emission
spectra remained the same. As a result, emission spectras of atoms
could be used as a elemental "fingerprint": if one had a catalog
of individual spectrum of elements, then given an unknown spectrum,
one can find what elements are found in the source of the emission!
This is known as *atomic emission spectroscopy* and is highly
useful in probing materials at very low quantities. Therefore, despite
the puzzling nature of the discreteness of emissions from elements,
they were very useful.

**Go to [Activity 4](<In-Class Activities>).**

### Blackbody radiation

When we have an object made up of a dense collection of particles
in motion, the distribution of kinetic energies give rise to a measurable
macroscopic quantity called temperature[^1]. Any object with a non-zero temperature will give out light in the
form of blackbody radiation. This form of light has a continuous distribution
of wavelengths. The key differences between blackbody radiation and
atomic emissions are summarised in the table below. 
[^1]: Apologies for the high number of technical terms in this one statement!
Each term is not hard. The difficulty is understanding their relation
to each other.

| Atomic emission                                            | Blackbody radiation                               |
|------------------------------------------------------------|---------------------------------------------------|
| Discrete lines                                             | Continuous Band                                   |
| Dilute Samples. Little or no interaction between particles | Collective effect of many particles that interact |
| Highly sensitive to chemical composition                   | Only depends on Temperature                       |
| *Intrinsic* property                                       | *Extrinsic* property                              |

Earlier, we discussed the successes of the particulate nature of light
in the late 1800/early 1900s. The problem faced by Max Planck, known
as the ultraviolet catastrophe, is exactly this phenomenon of blackbody
radiation. Consequentially, this broad and continuous distribution
of radiation emitted by hot objects is known as the Planck distribution.
We will not dwell too long with blackbody radiation as we will save
the more in-depth discussions on this topic in a later chapter. In
the meantime, to get a better understanding of blackbody radiation,
**Go to [Activity 5](<In-Class Activities>).**

Are there any light emission that is a combination of both blackbody
and discrete transitions? Study the spectrum of a galaxy (SDSS object
582093484903825431) below.
![Spectrum of a galaxy showing both continuous blackbody and discreet
atomic emission peaks. Image credit: <a href="https://skyserver.sdss.org/dr1/en/get/specById.asp?ID=75094094052851712">SSDS</a>](</Resources/Chapter 3/GalaxySpec.png>)


### Absorption spectra

Another method to probe a sample's constituent elements is to perform
the opposite of an emission spectra: an absorption spectra. As it
turns out, just as specific wavelengths of light is emitted by an
element, shining light with those same wavelengths will result in
absorption; collecting the light that passes through and splitting
it is known as an absorption spectra. 
![Absorption spectra of hydrogen. Credit: Chemblog, *Atomic Theories*](</Resources/Chapter 3/absorption_spectra.png>)

A typical setup for absorption spectroscopy is shown below. The sample
is illuminated by a broadband light source. Certain wavelengths of
light will be absorbed by the sample. The light that paasses through
the sample is split by a diffraction grating or prism and the spectrum
is collected by photodetectors or a camera for analysis. Absorption
spectroscopy is probably the most commonly used spectroscopic technique
used in research and industrial labs. 

Additionally, spectroscopy has proven exceptionally useful in probing
things that are (i) delicate and precious or (ii) hard to access,
which categorically encompass many things such as dinosaur fossils,
artwork, new materials, and of course celestial objects.

![A typical setup for absorption spectroscopy.](</Resources/Chapter 3/AbsorptionSpec.png>)


### Stellar Spectroscopy

In 1802, the spectrum of our very own star was studied, and was found
to have interesting properties and dark fringes. In 1814, Joseph von
Fraunhofer studied the wavelengths at which these dark fringes occurred
and classified them, giving rise to the eponymous Fraunhofer lines.
The Fraunhofer lines give us insight to both the solar and planetary
atmospheres, since light from the sun must have interacted with both
before reaching the surface of Earth. 

In more modern times, one can efficiently collect light from other
stellar sources to analyse their spectra. The figure below shows a
spectrum of a star (SDSS object 75094094052851712). 

![Spectrum of a star showing both continuous blackbody and discreet
atomic absorption peaks. Image credit: <a href="https://skyserver.sdss.org/dr1/en/get/specById.asp?ID=75094094052851712">SDSS</a>](</Resources/Chapter 3/StarSpec.jpg>)

Through spectroscopy, we are able to identify what stars are actually
made of, and with that, we are able to build an understanding of the
cosmos.

In summary, the light being absorbed and emitted by elements encodes
information about the atoms themselves. The principle is straightforward,
and a wide variety of problems can be solved by this technique. However,
at this stage, we are unsure of how the atom is able to accept and
emit very specific wavelengths of light. To understand how it does
so, we must travel back in time once again to follow the models that
tried to explain what the enigmatic atom is.

**Go to [Activity 6](<In-Class Activities>).**