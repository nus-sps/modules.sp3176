---
label: Atomic Models Throughout History
layout: default
icon: ":atom_symbol:"
order: -4
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

## 3.4 Atomic Models Throughout History

Towards the end of the 1800s, most problems in classical physics were
considered solved; they were either solved ingeniously or were decided
that they had too much computational cost. The problems left, in principle,
were solvable, given enough time to calculate (back then, by hand).
People widely thought that physics was nearing its limit. However,
it was eventually to be found that classical theories failed to account
for various phenomena in atomic physics.

The atomic model was a huge point of debate for scientists back then;
only the most creative of methods would allow them to investigate
something smaller than any microscope could hope to see. First, a
quick summary of what an atom has:

- Protons: particles with a small unit positive electrical charge, known
as an elementary charge $+e$. 
- Neutrons: particles with a very similar mass to a proton, carries
no electrical charge. 
- Electrons: particles with a *negative* electric charge, $-e$.
Also significantly lighter than protons and neutrons. 


#### Plum Pudding model, 1904

The plum pudding model was proposed by J.J. Thompson in 1904, in which
the discovery of electrons, which are very small particles that carry
a singular unit of negative charge, led him to envisage atoms as negatively
charged electron particles held together by a cloud of positive charge.
Protons and neutrons were not discovered yet.

#### Rutherford model, 1911

Ernest Rutherford investigated the Plum pudding model and quickly
realised that it was wrong; the famous Rutherford Scattering experiment
showed that the atom had to be composed of an extremely dense nucleus
surrounded by a sea of electrons. Scientists were largely satisfied
with the Rutherford model based on whatever experiments they could
do with an atom, albeit for a gap in understanding of how the electrons
behave in the atom. 

Consider just one of the electron. Since the nucleus is positively
charged with $+Ze$, and the electron is negatively charged with $-e$,
there is an attractive Coulumb force $\mathbf{F}_{E}$ between them
given by 
$$
\begin{equation}
\mathbf{F}_{E}=-\frac{1}{4\pi\epsilon_{0}}\frac{Ze^{2}}{r^{2}}\hat{\mathbf{r}}
\end{equation}
$$

where $\epsilon_{0}=8.854\times10^{-12}\text{m}^{-3}\text{kg}^{-1}\text{s}^{4}\text{A}^{2}$
is a constant, $r$ is the distance between the nucleus and the electron,
and $\hat{\mathbf{r}}$ is the radial unit vector. With this attractive
force, shouldn't the electron fall into the nucleus? Not neccessarily!
Recall how planets orbit around a star under the influence of an attractive
gravitational force. Motivated by the planetary model, Rutherford
suggested that the electron is to orbit around the nucleus under the
influence of the Coulomb force.

There is however something peculiar about charges (that do not apply
for uncharged masses such as planets): When charges accelerate, they
emit radiation (light) and lose energy. This means that the electron
will loss energy (continuously) during the orbit and will spiral into
the nucleus. A planetary model atom should not even last for a second! 

Enter Niels Bohr. He knew of Planck's and Einstein's new idea of a
quantised light particle (didn't quite like the idea though), and
also Rutherford's new planetary atom (this idea he loved!). He did
not regard the abovementioned shortcoming of Rutherford's model as
a no-go. His intuition led him to believe that the workings of the
subatomic world should not be ruled by classical theories. Through
a series of educated guesses, Bohr then assumed that when electrons
orbited around the nucleus, not any kind of orbits would do; only
specific orbits would be allowed in the atom. After working for a
year on this problem, he had a breakthrough when he came to realise
that Rutherford's planetary model with discrete allowed orbits can
be used to derive the emission/absorption spectrum of hydrogen. With
that he laid down his atomic model with three postulates (fancy word
for assumptions).

![Atomic models. Left: Thompson's Plum pudding model. Center: Rutherford's
model with a dense positively charged nucleus. Right: Bohr's model
with electrons orbiting at specific energy levels. Image credits:
(Left) <a href="https://commons.wikimedia.org/wiki/File:Plum\%5C_pudding\%5C_model.svg">Kurzon, CC BY-SA 4.0</a>;
(Center) <a href="https://commons.wikimedia.org/wiki/File:Rutherford\%5C_atomic\%5C_planetary\%5C_model.svg">Bensteele, CC BY-SA 3.0</a>;
(Right) <a href="https://commons.wikimedia.org/wiki/File:Bohr\%5C_atom\%5C_model.svg">JabberWok CC BY-SA 3.0</a>.](</Resources/Chapter 3/AtomicModels.jpg>)


### 3.4.1 The Bohr atomic model (1913)

The 3 postulate of Bohr's model of an atom are:

1. **Electrons** move in a **circular orbit** around the nucleus,
much like how the earth orbits around the sun. 
2. The **angular momentum** of the electron **is quantized**. 
3. Any change in the electron’s energy is caused by the emission or absorption
of a **quantized packet of light known as a photon.**

Let us look into each of the postulate in detail.

#### Postulate 1

The electron orbits the nucleus in circular motion described by the
following equation, 
$$
\begin{equation}
\mathbf{F}=-\frac{m_{e}v^{2}}{r}\hat{\mathbf{r}}
\end{equation}
$$
where $F$ is the (resultant) centripetal force exerted on the object
in motion, $m_{e}$ is the mass of the electron, $r$ is the radius
of the circular motion, and $v$ the speed of the electron in circular
motion. We also know that the electric force exerted on the electron
to be given by Eq.(1).

In the absence of all other forces, the electric force is the only
force providing for the centripetal force. This gives us 
$$
\begin{equation}
m_{e}v^{2}=\frac{1}{4\pi\epsilon_{0}}\frac{Ze^{2}}{r}
\end{equation}
$$


#### Postulate 2

Much like how momentum is a measure of a body’s tendency to remain
in its linear motion, angular momentum is a measure of a body’s tendency
to remain in its rotary motion. For the electron in circular motion,
the angular momentum $L$ is given by
$$
\begin{equation}
L=m_{e}vr
\end{equation}
$$
At this point, Bohr took a bold step and and believed that angular
momentum is quantized: 
$$
\begin{equation}
L=n\frac{h}{2\pi}=n\hbar
\end{equation}
$$
where **$n$ is a positive integer** (i.e. $n=1,2,3,...$ ),
and $h$ is Planck's constant. $\hbar=h/2\pi$ which is read as h
bar, is a convenient shorthand notation. Putting Eq.(5)
into Eq.(4), we have 
$$
m_{e}v=\frac{n\hbar}{r}
$$
Putting this into Eq.(3), we have 
$$
\begin{align}
\frac{n^{2}\hbar^{2}}{r^{2}} & =m_{e}\frac{1}{4\pi\epsilon_{0}}\frac{Ze^{2}}{r}\nonumber \\
r & =\frac{4\pi\epsilon_{0}n^{2}\hbar^{2}}{m_{e}Ze^{2}}\,,\,n=1,2,3,\dots
\end{align}
$$

Note that now the radius of orbit is quantised, meaning that we can
only find electrons at fixed radii from the proton; no closer or further.
The speed of the electron is also fixed; it is neither too fast nor
too slow!

You may have heard of "energy levels" of an atom. These refer
to the possible discrete energies of an electron can have based on
it's quantised radius of orbit. To work out the energy levels, we
need to digress a little. 

The potential energy of an electron experiencing Coulomb force Eq.(1)
is given by[^1]

[^1]: This "Coulomb potential" can be obtain from the Coulomb force given
in Eq.(1) and the general force-potential relationship $F=-\frac{dV}{dr}$

$$
V=-\frac{1}{4\pi\epsilon_{0}}\frac{Ze^{2}}{r}
$$

We write the potential energy with a negative sign because the electrons
are bound to the nucleus: the electron would require extra energy
to escape from the electric attraction from the positively charged
nucleus. 

Total energy of the system is given by
$$
\begin{align*}
E & =\text{Kinetic energy}+\text{Potential Energy}\\
 & =\frac{1}{2}m_{e}v^{2}-k\frac{Ze^{2}}{r}\\
 & =\frac{1}{2}\frac{1}{4\pi\epsilon_{0}}\frac{Ze^{2}}{r}-\frac{1}{4\pi\epsilon_{0}}\frac{Ze^{2}}{r}\quad\text{(see Eq.(3))}\\
 & =-\frac{1}{8\pi\epsilon_{0}}\frac{Ze^{2}}{r}
\end{align*}
$$
Putting the quantised radius Eq.(5) into the
above, we have 
$$
\begin{equation}
E=-\frac{Z^{2}e^{4}m_{e}}{32\pi^{2}\epsilon_{0}^{2}\hbar^{2}n^{2}}\,,\,n=1,2,3,\dots
\end{equation}
$$


#### Postulate 3

Eq.(6) gives discrete or quantised energies of
an electron. The value of the energy depends on the integer value
of $n$. The higher the $n$, the higher (less negative) the energy.
The electron can transit from one energy level to another. But to
do so, it must gain or lose the exact amount of energy difference
by absorbing or emiting a photon with the specific energy.
$$
\begin{equation}
hf=\left|E_{\text{final}}-E_{\text{initial}}\right|
\end{equation}
$$

For example, when an electron to fall from $n=3\rightarrow1$, it
will emit a photon of energy
$$
E=hf=\frac{Z^{2}e^{4}m_{e}}{32\pi^{2}\epsilon_{0}^{2}\hbar^{2}}\left(\frac{1}{1^{2}}-\frac{1}{3^{2}}\right)=\frac{Z^{2}e^{4}m_{e}}{36\pi^{2}\epsilon_{0}^{2}\hbar^{2}}
$$
 

The curious case of the [Rydberg formula](Spectroscopy/#emission-spectra) was
finally solved: the hydrogen spectra had puzzled scientists for many
years until the day Bohr published his model. Bohr's model accurately
predicted every single transition the Rydberg formula gave while giving
meaning to the seemingly unknown coefficients present in it. The true
success of the Bohr model comes from the results of the quantized
energies and its ability to derive the Rydberg formula, which was
first found empirically from experimental data. To this day, despite
some shortcomings, the Bohr model remains an extremely important concept
in modern physics.

### 3.4.2 The Hydrogen Atom

Through Bohr's model, we found that energy transitions in the hydrogen
atom between its different energy levels absorb or emit light. Furthermore,
they should be extremely sharp and distinct: the energy levels are
significantly far from each other. This means that every atom has
a specific set of wavelengths that it would emit. The whole group
of emissions could be further classified into the specific energy
level that is involved in the transition; every transition between
distinct energy levels can be uniquely identified by the light emitted
or absorbed.

The energies of each level can be computed using equation \ref{eq:quant_energy},
varying $n$ for the different energy levels. Since energy cannot
be created or destroyed, then we know that when a transition occurs
from one state to another, the difference in energy levels must exactly
correspond to the energy of the photon emitted or absorbed. Transitions
that involve the innermost shell, $n=1$, is eponymously known as
the Lyman series and is predominantly ultraviolet. As such, we are
unable to observe it with our eyes (we can most definitely detect
it with sensors). 
![Electron transitions across states in Bohr's Hydrogen model. Credit: <a href="https://commons.wikimedia.org/wiki/File:Hydrogen_transitions.svg">Szdori, OrangeDog, CC BY-2.5</a>.](</Resources/Chapter 3/Hydrogen_transitions.png>)

On the other hand, transitions to the second energy level $n$ = 2,
known as the Balmer series, lie predominantly in the visible light
spectrum. In fact, the Balmer series is exactly the specific wavelengths
of light observed in a Hydrogen lamp. The hydrogen emission spectrum
is observed when hydrogen de-excites to the second energy level. The
signature purple glow seen in a hydrogen lamp is a mixture of these
colors, and can be observed clearly with a proper setup in the darkness.
This is known as the emission spectra of the element. Since it is
the transition that is quantized, we can just as equally try to measure
the effects when hydrogen absorbs the energies needed to excite to
higher energy levels. Since the other colors are not accepted by the
hydrogen atom, we can shine a continuous spectrum of light onto Hydrogen
and collect the light that passes through. The hydrogen would have
absorbed the light that it can accept, and allow the rest through.
The collected light is then analyzed, and we do indeed find the dark
fringes where the emission spectra would have been. This equivalent
method of finding the spectra is known as the absorption spectrum
of the element.

At this point, we are able to mathematically predict the absorption
and emission spectra of hydrogen and hydrogen-like atoms using Bohr's
model. Any other system involving more than one electron is simply
too difficult to calculate by hand (three body problem), and are usually
approximated by other methods in quantum mechanics or computationally
modelled with Schrodinger's model.

### 3.4.3 Wave Model

Despite its successes in recovering the empirical observation of the
Hydrogen emission by a solely theoretical approach, Bohr's model suffered
from several shortcomings. Most notably, it was only able recover
the emission spectrum of Hydrogen and other one-electron systems.
It is unable to reproduce the results of atomic systems with two or
more electrons.

In 1926, Erwin Schrödinger proposed a revolutionary new proposal of
using wave mechanics as a way to approach the atomic model. His model
builds upon Bohr's model in an attempt to further refine and overcome
its shortcomings. It is also alongside this paper where he published
the now eponymous Schrödinger equation which will be discussed in
further detail later. The basis behind Schrödinger's modification
hinges from work contributed by Louis de Broglie. In 1924, de Broglie
proposed that our previous distinction between waves and particles,
one that is well established at the height of classical mechanics,
was to be blurred. He hypothesised that particles, when sufficiently
small or fast, begin to exhibit wave-like properties; and when waves
begin to carry enough momentum, they begin to obtain particle-like
properties. The distinction that is broken is summarised in the following
equation, known as the de Broglie relation:

$$
\begin{equation}
\lambda=\frac{h}{p}
\end{equation}
$$
where $p$ represents momentum, a fundamental property of particles,
and $\lambda$ , the wavelength, a fundamental property of waves.
This was just like how light was originally thought of as waves, but
eventually wave-particle duality became accepted. According to de
Broglie, *everything exhibits wave-particle duality.* This
property was eventually experimentally verified when electrons were
found to behave like waves under specific conditions. This held enormous
consequences; the de Broglie relation could be used to justify the
quantization that Bohr proposed. 

**Go to [Activity 7](<In-Class Activities>).**

Applying the concept of matter waves into the Bohr model allows us
to understand quantisation more intuitively. Waves exhibits interference.
An electron-in-orbit behaving like a wave would loop back to itself
and if a standing wave[^2] [^3]
is not formed, the "electron wave" would destructively interfere
with itself. As a result, only specific setups that form standing
waves were allowed to exist, creating these quantized orbits. These
specific setups would eventually come to be known as *atomic
or electron orbitals.*

[^2]: [Excellent explanation of standing waves from Khan Academy](https://www.khanacademy.org/science/physics/mechanical-waves-and-sound/standing-waves/v/standing-waves-on-strings)

[^3]: [Dr Chammika's awesome demonstration of standing waves :)](https://www.youtube.com/watch?v=AyXvE40hxWc)

![A standing wave that wraps around itself in 1D. Source: Khan Academy](</Resources/Chapter 3/standing_wave.png>)

![The first few atomic orbitals of the hydrogen atom. Credits: Sciencefacts](</Resources/Chapter 3/atomic_orbitals.jpg>)
