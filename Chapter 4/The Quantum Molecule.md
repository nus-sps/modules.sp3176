---
label: The Quantum Molecule
layout: default
icon: ":cat2:"
order: -3
author:
  - name: Tee Kai Ze
    email: kaize.tee19@sps.nus.edu.sg
    link: https://sps.nus.edu.sg/user/kaize.tee19/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/ultimatemember/95/profile_photo-190x190.jpg?1661557511
  - name: Guan Xin
    email: guan.xin20@sps.nus.edu.sg
    link: https://sps.nus.edu.sg/user/guan.xin20/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/ultimatemember/154/profile_photo-190x190.png?1661557677
  - name: Jensie Low
    email: jensie.low20@sps.nus.edu.sg
    link: https://sps.nus.edu.sg/user/jensie.low20/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/ultimatemember/158/profile_photo-190x190.jpg?1661557649
  - name: Seow Ryan
    email: ryan.seow20@sps.nus.edu.sg
    link: https://sps.nus.edu.sg/user/ryan.seow20/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/ultimatemember/177/profile_photo-190x190.jpg?1661557711
date: 2022-08-27T00:00
description: "Molecules"
---
## 4.3 The Quantum Molecule
---
In the previous chapter, we have established what is a chemical bond
and how electron transitions between energy levels of a molecule are
observable. Building upon the principles of linear combination of
atomic orbitals, one might expect discrete energy levels and transitions
leading to discrete peaks in molecular spectra. Is it really so?

Let us take a look at a molecule you should see and eat everyday:
chlorophyll :) There are 2 types of chlorophyll (Chl), Chl a and Chl
b . Their molecular structure and (solvent-free) absorption spectra
are shown in the figure below.

![Left: Structure of Chlorophyll (Chl) a and b. Right: Absorption of
Chl a and b taken using a solvent free (gas phase) technique. Adapted
from Milne, B. F., Toker, Y., Rubio, A., Nielsen, S. B. Unraveling
the Intrinsic Color of Chlorophyll. *Angew. Chem. Int. Ed.* **2015**, 54, 
2170](</Resources/Chapter 4/Chlorophyll.png>)



!!! Try it yourself!
From the spectrum above, explain why leaves are
green.
!!!

One notable difference between atomic and molecular (UV-Vis) spectra
is that while the former is composed of distinct discrete peaks, the
latter usually exhibit broader peaks or bands. A fine example of a
molecular spectrum is that of Chl a and b shown above. What is the
reason for the broader bands as opposed to narrow peaks? 

One major contributing factor to the broad bands is the existence
of vibrational and rotational energy levels within an (molecular)
electronic state. For a molecule at a certain electronic orbital state,
it can wobble and rotate. The vibrations and rotations changes the
energy of the molecule slightly. As many vibrational and rotational
states are possible for each molecular orbital state, the electronic
state no longer possesses a single well-defined discrete energy but
a range of energies. Depending on the resolution of the spectrometer
used, the band of energy may be resolved such that the finer structures
can be seen (see spectrum of Chl a and b above). Very often a lower
resolution spectrometer is used to probe the molecule , in which case
the finer details will smear out to give smooth and broad peaks (google
image for chlorophyll sprectrum).

The energies associated with transitions across electronic energy
states are orders of magnitude larger than that of the vibrational
states, which are in turn orders of magnitude larger than transitions
across rotational states. 
<span id="energyComparison"></span>
$$
\begin{equation}
\Delta E_{\text{MO}}\approx10^{3}\Delta E_{\text{vib}}\approx10^{6}\Delta E_{\text{rot}}
\end{equation}
$$
A simplistic representation of this is given in the following diagram:

![Energy states of a molecule i much richer than that of an atom.The
allowed vibrational and rotational motion contributes to finely distributed
energy levels within each electronic molecular orbital state.](</Resources/Chapter 4/moleculeEnergyStates.png>)

In order to simplify the quantum description of the molecule, Born
and Oppenheimer assumed that the motion of the electrons and nuclei
in molecules can be considered separately. Since the mass of the nuclei
is of several orders of magnitude heavier than the electrons, the
motion of nuclei is negligible to that of the electrons. The energies
of the electron can then be calculated at fixed internuclei distances.
**The energies of electronic, vibrational and rotational states
can be considered to be independent of each other.** This is known
as the Born-Oppenheimer approximation.

In this course we will examine the vibrational and rotational energy
levels and their corresponding transitions in greater details. 

### 4.3.1 Rotational Energy Levels and Microwave Spectroscopy

Let us consider the rotation of a diatomic molecule. We assume the
bond between the two atoms is rigid, meaning that the internuclear
distance does not change. As shown in section [4.2.1](<Classical Rotations/#421-rigid-rotor>),
the kinetic and potential energies of the system is 
<span id="KErot"></span>
$$
\begin{equation}
T=\frac{L^{2}}{2I}
\end{equation}
$$
and 
<span id="PErot"></span>
$$
\begin{equation}
V=0
\end{equation}
$$
respectively. The Schrödinger equation is 
<span id="SE_rot"></span>
$$
\begin{equation}
-\frac{\hbar^{2}}{2I}\left[\frac{1}{\sin\theta}\frac{\partial}{\partial\theta}\left(\sin\theta\frac{\partial}{\partial\theta}\right)+\frac{1}{\sin^{2}\theta}\frac{\partial^{2}}{\partial\theta^{2}}\right]\psi=E\psi
\end{equation}
$$
It is out of the scope of the course to derive Eq.([4](#SE_rot)).
For the interested reader, see the [Appendix](Appendix) on a note about operators. 

The procedure to solve the above SE is in essence similar to how it
was done in Chapter 3. The allowed energies of the system are 
<span id="RotEnergy"></span>
$$
\begin{equation}
E=\frac{\hbar^{2}J(J+1)}{2I}=BJ(J+1)
\end{equation}
$$
where $J=0,1,2,3,\dots$ is the rotational quantum number and $B=\hbar^{2}/2I$
is called the rotational constant. 

The rotational constant depends on the moment of inertia of the diatomic
system, which in turn depends on the masses of the nuclei as well
as the bond length. Different molecules will have different rotational
constants thus making the set of rotational energies unique to each
molecule. 

The rotational constant above has units of energy. Some (eg. radio
astronomers) like to state the rotational constant in units of frequency
(Hz). In this case, divide the above $B$ by $h$. Other (eg. chemists)
prefer to state the rotational constant in units of wavenumber ($\text{cm}^{-1}$).
In this case divide the above by $hc$ where $c=3.00\times10^{10}\text{cm s}^{-1}$
is the speed of light. 

Define $P(J)$ as the probability of a molecule being in the $J^{\text{th }}$ energy
state, we have 
<span id="probability"></span>
$$
\begin{equation}
P(J)=(2J+1)P(0)\exp\left(-\frac{BJ(J+1)}{kT}\right)
\end{equation}
$$
where $P(0)$ is the probability of finding the particle at ground
state ($J=0$).

The diatomic molecule with a permanent dipole moment can transit from
one rotational energy state to another by absorbing or emitting a
photon.[^1] By examining the probability of transitions, it can be shown that
only transitions across more than one energy level is highly improbable.
Thus transitions across rotational energy levels are restricted to
the following selection rule 

[^1]: Homonuleus diatomic molecules such as $\text{H}_{2}$ and $\text{N}_{2}$
do not have a permanent dipole moment and cannot undergo light-induced
rotational transitions.

<span id="rotSelection"></span>
$$
\begin{equation}
\Delta J=\pm1
\end{equation}
$$
This means that transitions such as $J=3\rightarrow2$ and $J=3\rightarrow4$
are allowed while $J=5\rightarrow3$ is highly unlikely. 

The energy of a photon emitted in a $J+1\rightarrow J$ transition
is given by
<span id="rotSpecEnergy"></span>
$$
\begin{align}
hf=\Delta E & =B(J+1)(J+2)-BJ(J+1)\nonumber \\
hf & =2B(J+1)
\end{align}
$$

The probablility of particle residing in the $J^{\text{th}}$ energy
state given in Eq.([6](probability)) gives the relative intensity
of the spectral line. 

!!! Try it yourself!
Show that the rotational spectrum of a diatomic
molecule is a set of equally spaced spectral lines with separation
$2B$.
!!!

</br>

!!! Try it yourself!
Ex. Suppose you are given the rotational spectrum
of a molecule, how does one find the internuclear distance of the
molecule?
!!!

</br>

!!! Try it yourself!
The figure below is the rotation spectrum of
CO. Explain qualitatively why different spectral lines have different
intensities.

![](</Resources/Chapter 4/CO_spectrum.png>)
!!!




### 4.3.2 Ro-Vibrational Energy Levels and IR Spectroscopy

In the previous section, the bond between atoms are treated as a rigid
rod. In this section, we shall allow the bonds to stretch and compress.
This means that the molecule can vibrate when the atoms are displaced
from their equilibrium position. 

Let us consider the case of a diatomic molecule. We model its vibrational
motion with a harmonic oscillator described in section [4.2.2](classical-rotations/#412-harmonic-oscillator),
i.e. a 1D system with effective mass (see Eq.([Rot.18](<Classical Rotations/#HO_effMass>)))

<span id="reducedMass2"></span>
$$
\begin{equation}
\mu=\frac{m_{1}m_{2}}{m_{1}+m_{2}}
\end{equation}
$$
where $m_{1}$ and $m_{2}$ are the masses of the atoms. The potential
energy is (see Eq.([Rot.18](<Classical Rotations/#HO_potential>)))

<span id="HO_PE2"></span>
$$
\begin{equation}
V=\frac{1}{2}\mu\omega^{2}x^{2}
\end{equation}
$$

The Schrödinger equation is 
<span id="HO_SE"></span>
$$
\begin{equation}
-\frac{\hbar^{2}}{2\mu}\frac{d^{2}\psi}{dx^{2}}+\frac{1}{2}\mu\omega^{2}x^{2}\psi=E\psi
\end{equation}
$$
and the boundary conditions are 

<span id="HO_BC"></span>
$$
\begin{equation}
x\rightarrow\pm\infty,\psi(x)\rightarrow0
\end{equation}
$$

Without going into the details of solving the quantum mechanics for
a harmonic oscillator, we just state here the results. The molecules
display discrete vibrational energy states given by 
<span id="vibEnergy"></span>
$$
\begin{equation}
E=\hbar\omega\left(v+\frac{1}{2}\right)\,,\;v=0,1,2,3,\dots
\end{equation}
$$
where $v$ is the vibrational quantum number which takes on integer
values.

For transitions across vibrational energy levels, a similar rule to
rotational levels holds: 
<span id="vibSelRule"></span>
$$
\begin{equation}
\Delta v=\pm1
\end{equation}
$$
This means that all allowed transitions across vibrational energy
levels will have energy 
<span id="VibrationalTransitionE"></span>
$$
\begin{equation}
\Delta E_{\text{vib}}=E_{v+1}-E_{v}=\frac{h\omega}{2\pi}\left(\left(v+1+\frac{1}{2}\right)-\left(v+\frac{1}{2}\right)\right)=\frac{h\omega}{2\pi}
\end{equation}
$$

Note the the lowest energy state is non-zero. 

!!! Try it yourself!
The fundamental oscillator (angular) frequency
$\omega$ of H^35^Cl is $5.44\times10^{14}$ Hz.

(a) Find $\Delta E_{\text{vib}}$ and the corresponding
wavelength of transition.

(b) In what category of the EM spectrum does this
transition belong? (radio/microwave/IR/visible/UV/X-ray)

(c) Compare the energy of vibrational transitions
of HCl to one of its rotational energy level transitions (say $J=2\rightarrow1$).

(d) Chemist usually report vibrational spectroscopy
results in units of wavenumber (cm^-1^). Convert your answer in
part (a) to wavenumber and compare it to values you can find in the
literature.
!!!

Although it seems from Eq.([15](#VibrationalTransitionE)) that
the vibrational spectrum is a simple single line for a molecule, it
is not so after taking rotational energies into account. In each vibrational
energy *band*, the molecule can be at many different rotational
energy states. For a heterogenous diatomic molecule, a transition
across the vibrational energy will be accompanied by a change in rotational
levels with the following rule: 

<span id="rovibSelRule"></span>
$$
\begin{equation}
\Delta v=\pm1,\;\Delta J=\pm1
\end{equation}
$$

The vibrational spectrum of a molecule thus exhibits 2 bands. The
higher energy band (R-branch) comprises of $\Delta J=+1$ transitions,
while the lower energy band (P-branch) comprises of $\Delta J=-1$.

![Schematic of vibrational and rotational energy levels with P- and
R-branch ro-vibrational transitions.](</Resources/Chapter 4/VibrationalBandTransitions.png>)

![Ro-vibrational spectrum of HCl. Image credit: <a href="https://commons.wikimedia.org/wiki/File:Ro-vibrational_spectrum_of_HCl.svg">Cnrowley CC-SA-4.0-BY</a>](</Resources/Chapter 4/rovibrationalHCl.png>)

The image above is a ro-vibrational absorbance spectrum for HCl, and
we can clearly see that there is a peak near the centre that is missing.
That missing peak belongs to the pure vibrational transition, $\Delta E=\frac{1}{2}\hbar\omega$.
To the left, is the P branch (as in P for poor), where $\Delta J=-1$,
and to the right is the R branch (as in R for rich), where $\Delta J=+1$.
The pure vibrational ($\Delta J=0$) peak do not show up as the transition
is much less favourable than the $\Delta J=\pm1$ transitions.

!!! Try it yourself!

Examine the ro-vibrational spectrum of HCl in
the above figure closely. Try to explain the features you see.
!!!