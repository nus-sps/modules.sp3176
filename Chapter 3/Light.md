---
label: Light
layout: default
icon: ":bulb:"
order: -2
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

## 3.2 Light

### 3.2.1 From the *Optica* to the electromagnetic spectrum

The study of light can be traced back 2500 years. People attempted
to study and understand how light came to be: it was often the case
that the Sun was the only natural source of light and thus revered
then. The earliest known work on light was *Optica* by Euclid,
studying the nature of light and how it behaved both qualitatively
and quantitatively. Over the years, our understanding of light has
vastly changed, especially so during the Scientific Revolution. Models
of light have come and gone but most remain in one way or another
due to its relevance in nature or practicality. 

The nature of light was a contentious issue before the 1700s. The
two leading theories of light's nature were particle-like (or corpuscular)
and wave-like. In 1690, Christiaan Huygens published a work that would
set in motion the victory of the wave theory, the *Traité de
la Lumière* [^1]. Summarily, his treatise put forth that light was best described
by waves. This was primarily because of the following three phenomenon
unique to *transverse* waves: 

1. Diffraction 
2. Refraction 
3. Polarization 

[^1]: in full; *Treatise on Light: In Which Are Explained the Causes
of That Which Occurs in Reflection \& Refraction.*

Light was found to be capable of exhibiting all three properties and
Huygens mathematically proved the first two so. Although not widely
accepted during its time of publication, contributions by several
others such as Augustin-Jean Fresnel, Denis Poisson and Léon Foucault
expanded on Huygen's work or proved the corpuscular theory otherwise,
leading to the eventual acceptance of light as a wave in the mid-1800s.

In 1862, James Clerk Maxwell brought together several empirical laws
that described electric fields $\mathbf{E}$ and magnetic field $\mathbf{B}$
and compiled them into a set of equations known (today) as the Maxwell's
equations. By further combining the equations, he found that the $\mathbf{E}$
and $\mathbf{B}$ fields in vacuum obey
$$
\begin{align}
\frac{\partial^{2}\mathbf{E}}{\partial x^{2}}+\frac{\partial^{2}\mathbf{E}}{\partial y^{2}}+\frac{\partial^{2}\mathbf{E}}{\partial z^{2}} & =\mu_{0}\epsilon_{0}\frac{\partial^{2}\mathbf{E}}{\partial t^{2}}\\
\frac{\partial^{2}\mathbf{B}}{\partial x^{2}}+\frac{\partial^{2}\mathbf{B}}{\partial y^{2}}+\frac{\partial^{2}\mathbf{B}}{\partial z^{2}} & =\mu_{0}\epsilon_{0}\frac{\partial^{2}\mathbf{B}}{\partial t^{2}}
\end{align}
$$

Equations that look like the above are well studied: they are known
as wave equations because solutions to this class of equations are
of the form of waves. Through theory, he found that electromagnetic
waves travelled at the speed of light, which had been fairly accurately
measured by then. Additionally, treating light as an electromagnetic
phenomenon would also solve the final piece of the puzzle; polarization
of light. However, light was seen as entirely unrelated to electromagnetism
then; thus this finding had stirred the whole scientific community
as either proof of a new revolutionary theory or an amazing coincidence
in nature.

Heinrich Hertz, in 1882, experimentally generated electromagnetic
waves and showed that they travelled through space at the speed of
light. Essentially he created the first radio `antenna' and `generator'.
His work proved Maxwell's equations, which were not widely accepted
then, as well as unified the study of light, electricity and magnetism
into the same concept. Funnily enough, when asked about the practical
importance of radio waves, 
:::quote
*"It's of no use whatsoever[...] this is just an experiment
that proves Maestro Maxwell was right---we just have these mysterious
electromagnetic waves that we cannot see with the naked eye. But they
are there."*
:::

and when asked for potential uses of his antenna contraption, he said 

:::quote
*"Nothing, I guess."* 
:::
We'll leave it at that, I guess.
![The electromagnetic spectrum. Image credit: <a href="https://commons.wikimedia.org/wiki/File:Electromagnetic-Spectrum.svg">Victor Blacus CC BY-3.0</a>](</Resources/Chapter 3/Electromagnetic-Spectrum.png>)

---

### 3.2.2 The wave nature

![Key descriptors of a periodic wave. Credits: *Encyclopedia
Britannica*.](</Resources/Chapter 3/partsofawave.jpg>)


Intuitively, a periodic wave can be described with three properties:
frequency $f$, wavelength $\lambda$ and its speed, $v$. The wavelength
of a wave tells us how far, physically, does a wave extend before
it repeats again. The frequency tells us how rapidly, in time, does
a wave repeat itself. Finally, these two properties are related to
the speed at which the wave travels by 
$$
\begin{align}
v=f\lambda
\end{align}
$$
In the case of light, $v$ is a famously known value: the speed of
light. This quantity is conventionally denoted as $c$, and has the
value $c=299792458\text{ ms}^{-1}$. Since the speed of light does
not change at all (bar some circumstances), light can be entirely
(and is often the case) described with only one of the two variables;
application of equation \ref{eq:wavespeed} would govern the other.
The wave-like nature of light motivates us to mathematically describe
light in the form of a wave. In its most general form, the equation
of a periodic wave looks like:

$$
\begin{align}
y=A\sin(kx+\omega t+\phi)
\end{align}
$$
where $A,k,\phi\text{ and }\omega$ are constants that influence the
way the function behaves. As a result, investigating light and its
properties translates, mathematically, to solving for these 4 variables.
$x$ represents position in the x-axis and $t$ represents time, which
are typically the variables which we cannot control. In nomenclature,
$A$ is known as the amplitude, $\phi$ the phase of the wave, $k$
the angular wavenumber and $\omega$ the angular frequency. $k$ and
$\omega$ are related to wavelenght and frequency via the following
equations;
$$
\begin{align}
k & =2\pi/\lambda\\
\omega & =2\pi f
\end{align}
$$


### 3.2.3 Optics

Optics is the study of behaviour and properties of light and its interactions.
We must therefore venture into the field of optics to understand how
to measure the properties of light.

#### Ray optics

In earlier education, you may have come across a simple treatise in
optics. Light is treated as rays, and lenses serve to bend the path
of light. From this, we are able to predict how light would travel.
The assumption that light can be treated as simple linear rays is
known as the paraxial ray theory, and hinges on the key assumption
in its namesake: 
:::quote
*Light must travel at an angle that is small when measured
from the optical axis of the system.*
:::

In any optical system that we study, we must first define a principal
axis. The principal axis is an imaginary line that is drawn, such
that if light would approach the system nearly parallel to this axis,
it would interact the same regardless of position around the principal
axis. This is known as having some degree of rotational symmetry;
were you to rotate around the optical axis, the system would look
the same to you. If one approaches the lens from above the optical
axis, it must be affected in the same way as it would if it approaches
from below the optical axis; in this case, they both converge to the
same spot F in the diagram.

![A labelled example of a typical optical diagram.](</Resources/Chapter 3/principal_focus.jpg>)


#### Diffraction

As much as we would like to treat light as rays for their simplicity,
ray optics is extremely limited in explaining what light can do. If
we wish to study the properties of light, then we must rely on a theory
or method that hinges on the behaviour of light. The paraxial theory
makes no concession for its wavelength; it is after all one of the
earliest models of light. The ideas behind Huygen's *Treatise*
are discussed from here on. To measure the wavelength of light, we
must accept the behaviour of light as a wave, and as such treat it
accordingly. Diffraction is one such phenomenon that is related to
waves.

To understand diffraction, let us first take a step back to visualize
a water wave. Imagine you throw a stone into a pond of water. What
will you see?

![](</Resources/Chapter 3/circular_and_sinusoid.png>)


We should see something that looks like the picture on the left, but
intuitively we know that the pattern is made up of water waves that
looks like the picture on the right.

The lines in picture on the left is what we call circular wavefronts.
They are formed by (water) waves coming from the point source (your
stone). Each line/wavefront represent a set of points at which the
waves are in-phase (same $\phi$ angle in the sinusoidal wave). If
the light source comes from very far, the circularity of the wavefronts
begin to become insignificant and instead appear parallel. 

![Parallel wavefronts from a light source far away. Each line represents
a top down view of waves; the lines connect waves at their maxima
together.](</Resources/Chapter 3/plane_wave.png>)


Diffraction is a phenomenon which occurs when waves meets an obstacle
in the form of aperture (hole) or edge. The Huygens-Fresnel principle
states that every point on a wavefront can be treated as a source
of a circular wave. When the waves travel parallel, each point on
a wavefront emits its own circular wavefront, and cancel out because
of \textit{superposition} (discussed right after this.), remaining
parallel. However, if the parallel wavefronts are blocked by any opaque
material, some sections of a parallel wavefront can no longer cancel
each other out. As such one can have a diffraction phenomenon as such:

![Diffraction through slits of different sizes.](</Resources/Chapter 3/Diffr-wide-narrow.jpg>)


#### Superposition

The superposition principle tells us that when waves physically overlap,
their amplitudes can be added up. As such, the phases of the waves
are important when superposing them; it can determine the amplitude
of the individual waves at that point.

When two waves are in phase, such that their phase \textit{differences}
are even multiples of $\pi$, then they are said to constructively
interfere and will add up. On the other hand, if they are odd integer
multiples of $\pi$, then they destructively interfere with each other
and results in a minimum. It is from the superposition principle that
the Huygens-Fresnel principle explains and accounts for diffraction.

**Go to [Activity 1](<In-Class Activities>).**

#### Diffraction Pattern

Since every gap can allow for the wave to act as a point source, then
a series of gaps can be treated as a series of point sources at different
fixed positions. This sets up a very interesting situation, as we
are in position to consider what happens between the path differences
between two sources. This is known as the double-slit diffraction
problem, and is easily extendable to many arbitrary slits, or equivalent
sources.

Light from two (or more) slits travel a different distance to the
same point on a screen. Due to the path difference, there will be
phase differences and constructive/destructive interference will occur.
The condition for maximum constructive interference is 
$$
d\sin\theta=m\lambda
$$
where $m$ is an integer. As a result, we see alternating bright and
dark spots on the screen as the angle $\theta$ varies, due to constructive
and destructive interference respectively.

![Diagram of the double slit setup. Adapted from Peatross \& Ware, *Physics
of Light and Optics.*](</Resources/Chapter 3/double_slit.png>)


We arrive at a phenomenon that depends on the wavelength of the light
that we are observing: the maxima at which the interference pattern
occurs depends on the wavelength. Light of different wavelengths will
have maxima at different distances from the central maxima, which
is denoted by $y$ here. It was also found that the more slits there
are, the sharper and clearer these maxima become. Thus, we employ
diffraction gratings which have many grooves or gaps to allow light
through, or reflect them, periodically across very small distances.
Diffraction gratings can arise from (regular) imperfections on a surface;
a metal ruler or even your phone screen can serve as a diffraction
grating.

**Go to [Activity 2](<In-Class Activities>).**

### 3.2.4 Wave-Particle duality of Light

Occurring in the early 1900s was the [ultraviolet catastrophe](https://en.wikipedia.org/wiki/Ultraviolet_catastrophe),
an observation that was irreconcilable with the wave theory of light.
Max Planck proposed a solution to this problem by unwillingly assuming
that energy carried by light had to be quantized. The quantization
of light was so successful in solving the problem that it even accurately
predicted the entire emission spectrum of objects. This problem will
be revisited later.

The success of quantization and particle-like light as a concept did
not stop there. In 1905, Albert Einstein’s Nobel prize winning work
on the photoelectric effect was also evidence of light quantization.
In his experiment, he showed that by shining light of low frequency,
no matter how intense, could not generate electrical current from
a polished metal surface, indicating an insufficiency of energy to
do so. However, once the frequency was raised past a certain value,
an electrical current was observed, regardless of how strong the light
was. This pointed towards some form of quantization with regards to
the frequency (or equivalently, wavelength) of light. These successes
reinvigorated the corpuscular theory of light.

In modern physics, we also treat light as quantized particles, capable
of many things a classical particle could do such as carry momentum.
Today, we understand that in the quantum regime, light exhibits both
particle and wave nature, famously known as the \textit{wave-particle
duality.} The Planck-Einstein concept of light as a particle states
that a single light particle known as the photon, carries a packet
of energy $E$ equivalent to 
$$
\begin{align}
E=hf=h\frac{c}{\lambda}\label{eq:light_momentum}
\end{align}
$$

Where $h$ is the Planck's constant, $6.626\times10^{-34}\text{ Js}^{-1}$
and the last equality holds from substitution using equation \ref{eq:wavespeed}.
This extended further meaning of a wave's properties into its particulate
nature: the frequency of light not only denotes the rate at which
it repeats, but also the energy it carries. 

**Go to [Activity 3](<In-Class Activities>).**