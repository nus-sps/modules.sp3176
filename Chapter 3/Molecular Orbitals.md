---
label: Molecular Orbitals
layout: default
icon: ":ringed_planet:"
order: -6
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


## 3.6 Molecular Orbitals

Almost done! Up until now in this chapter, you have seen how we came
from plum pudding models to atomic orbitals. At the end of this chapter,
we will bring in one last concept called molecular orbitals.

As you have hopefully learned from previous sections, atomic orbitals
are essentially functions that describe where electrons are the most
likely to be found in an atom. However, what (most) scientists care
about are not atoms, but rather molecules which are made up of a bunch
of atoms. Thus, it is not surprising that the concept of “orbitals”
needs to be extended to the context of a molecule.

But solving the Schrödinger equation to get the atomic orbital of
a single H atom is already a non-trivial task, how are we supposed
to do that to a molecule? Fortunately, scientists came up with an
idea which allows us to obtain a decent guess of what molecular orbitals
look like, but involving minimal effort. Motivated by the principle
of superposition for waves, the molecular orbitals can be thought
of as a superposition of atomic orbitals. This is known as the linear
combination of atomic orbitals (LCAO).

Let's start with something very simple: an $H_{2}$ molecule. This
molecule is obviously formed by two hydrogen atoms, which we name
$H_{a}$ and $H_{b}$. These two atoms each have their 1s orbitals,
which are denoted as $\chi_{a}$ and $\chi_{b}$. When these two atoms
approach each other, the electron clouds surrounding them overlap
and merge together, and thus the electron probability distribution
needs be described by new functions (molecular orbitals). The possible
LCAOs are: 
$$
\begin{equation}
\psi_{+}=N(\chi_{a}+\chi_{b})\hspace{30pt}\psi_{-}=N(\chi_{a}-\chi_{b})
\end{equation}
$$
where $N$ is the normalisation factor. An intuitive way to understand
this is to think of the wave functions as actual waves: if you recall
from physics courses in the past, waves can interfere with each other
either constructively or destructively. In this case, we can understand
$\psi_{+}$ as a result of constructive interference between $\chi_{a}$
and $\chi_{b}$, and $\psi_{-}$ as a result of destructive interference
(see the figure below for visualization).

![Formation of $\psi_{+}$ and $\psi_{-}$ (Image Credit: Seow Ryan)](</Resources/Chapter 3/MOformation.jpg>)

Moreover, just like how each atomic orbital has its corresponding
energy, here the two molecular orbitals we created also have specific
energies. The molecular orbital that arises from constructive interference
($\psi_{+}$) has the energy $E_{1}$, which is lower than the energies
of the two atomic orbitals. On the other hand, $\psi_{-}$, which
comes from destructive interference, has the energy $E_{2}$, which
is higher than the energies of the two atomic orbitals. By filling
both electrons into $\psi_{+}$, the total energy of the molecule
is lowered compared to the two individual atoms. This is where bonding
comes from! This is why we give $\psi_{+}$ is called the bonding
orbital, and $\psi_{-}$ the antibonding orbital. In summary, this
is all shown in the molecular orbital diagram below.

![MO diagram of $H_{2}$ molecule. (Image credit: Shriver & Atkins’
*Inorganic Chemistry*, Fifth Edition.)](</Resources/Chapter 3/H2_MO.png>)

Just like how transitions between different energy levels in a hydrogen
atom, transitions between molecular energy levels also correspond
to absorbing and emitting light. A famous example is $\beta$-carotene,
which is the pigment that gives carrots their orange colour. The most
prominent energy transition of this molecule corresponds to the absorption
of blue light, which is why this molecule is orange in colour!

!!! Try it yourself!

![](</Resources/Chapter 3/carotene.png>)

Shown above is the molecular structure of $\beta$-carotene. Given
that its most prominent energy transition corresponds to an energy
gap of 2.050 * $10^{-19}$ J, verify that this corresponds
to blue light. (hint: use $E=\frac{hc}{\lambda}$!)

!!!

Let's make one final return to the $H_{2}$ molecule. What do you
expect its emission spectrum to look like? Following the logic shown
above, you may expect to see one single emission line that corresponds
to the energy $E_{2}-E_{1}$. However, take a look at Table 1 of [this paper](https://iopscience.iop.org/article/10.3847/1538-4357/aa5b9f):
the actual emission spectrum of $H_{2}$ observed by telescopes is
actually much more complex!

Why? Chapter 4 awaits you!
