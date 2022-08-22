---
label: Quantum Mechanics
layout: default
icon: ":wavy_dash:"
order: -5
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

## 3.5 Quantum Mechanics

### 3.5.1 The Wavefunction and Schrödinger's equation

We shall now dive a little deeper into modern quantum mechanics[^1].
From 1925-1927, three versions of quantum mechanics was independently
 developed by Erwin Schrödinger, Werner Heisenerg and Paul Dirac.
They differed drastically from their initial formulism, but were later
shown to be equivalent. Here we will adopt the Schrödinger "picture",
as out of the three, it is the least chim[^2].

[^1]: Bohr's version is known as the old quantum mechanics

[^2]: Singlish term for intellectually deep or abstract.

Schrödinger postulated that a quantum system can be specified completely
by a wavefunction: 
$$
\Psi
$$
If one knows the wavefunction, then one will know all the mechanical
information such as energy, position and momentum of the system. Schrödinger
sought to find a differential equation that relates how the derivatives
(change) of the wavefunction of a particle is affected by the energy
and boundary conditions it is in.

He starts by assuming that the wavefunction can take on a simple but
general wave-like expression

<span id="generalWave"></span>
$$
\begin{equation}
\Psi(x,t)=\psi_{0}e^{i(kx-\omega t)}
\end{equation}
$$
where $\psi_{0}$ is the amplitude[^3]
of the wave, $k=2\pi/\lambda$ is the wavenumber and $\omega=2\pi f$
is the angular frequency (see Eq.([Light(5)](</Chapter 3/Light#wavenumber>)) and ([Light(6)](</Chapter 3/Light#angfreq>)).
[^3]: The amplitude can be a complex number, as opposed to real.

The derivatives of $\Psi$ are 
$$
\begin{align*}
\frac{\partial\Psi}{\partial t} & =-i\omega\psi_{0}e^{i(kx-\omega t)}=-i\omega\Psi\\
\frac{\partial^{2}\Psi}{\partial t^{2}} & =-i\omega(-i\omega\Psi)=-\omega^{2}\Psi\\
\frac{\partial\Psi}{\partial x} & =ik\psi_{0}e^{i(kx-\omega t)}=ik\Psi\\
\frac{\partial^{2}\Psi}{\partial x^{2}} & =-k^{2}\Psi
\end{align*}
$$

Borrowing de Broglie's idea of matter waves where we have 
$$
\begin{align*}
E & =hf=\hbar\omega\\
p & =\frac{h}{\lambda}=\hbar k
\end{align*}
$$
The above derivatives can be rewritten as 
<span id="diffPsiTime"></span>
<span id="diffPsiTimeAgain"></span>
<span id="diffPsiPos"></span>
<span id="diffPsiPosAgain"></span>
$$
\begin{align}
\frac{\partial\Psi}{\partial t} & =-i\frac{E}{\hbar}\Psi\\
\frac{\partial^{2}\Psi}{\partial t^{2}} & =-\frac{E^{2}}{\hbar^{2}}\Psi\\
\frac{\partial\Psi}{\partial x} & =i\frac{p}{\hbar}\Psi\\
\frac{\partial^{2}\Psi}{\partial x^{2}} & =-\frac{p^{2}}{\hbar^{2}}\Psi
\end{align}
$$

Using a total energy consideration 
$$
\begin{align*}
\text{Total energy} & =\text{Kinetic energy }+\text{Potential energy}\\
E & =\frac{p^{2}}{2m}+V(x)
\end{align*}
$$
Multiply throughout by $\Psi$ and using Eq.([2](#diffPsiTime))
and ([5](diffPsiPosAgain)), we have 
<span id="SchrodingerEq"></span>
$$
\begin{align}
E\Psi & =\frac{p^{2}}{2m}\Psi+V(x)\,\Psi\nonumber \\
i\hbar\frac{\partial\Psi}{\partial t} & =-\frac{\hbar^{2}}{2m}\frac{\partial^{2}\Psi}{\partial x^{2}}+V(x)\,\Psi
\end{align}
$$

The differential equation Eq.([6](#SchrodingerEq)) is known as
the Schrödinger's equation (SE). Different systems will have a different
potential energy landscape $V(x)$ and a different set of boundary
conditions. By finding the solution of the SE, ie $\Psi(x,t)$, one
will essentially be able to determine everything that can be known
about the system.

The SE however is a difficult equation to solve as it has derivatives
in both time $t$ and position $x$. If one is interested to find
the "stationary solutions" such as the standing waves mentioned
in the previous section, then it is beneficial to remove time from
the SE.

To do so, we go back to the assumed general wavefunction in Eq.([1](#generalWave))
and rewrite it as 
$$
\begin{align*}
\Psi(x,t) & =\psi_{0}e^{ikx}e^{-i\omega t}\\
 & =\psi(x)e^{-i\omega t}
\end{align*}
$$
Put this into the SE,
$$ 
\begin{align}
i\hbar\frac{\partial\psi(x)e^{-i\omega t}}{\partial t} & =-\frac{\hbar^{2}}{2m}\frac{\partial^{2}\psi(x)e^{-i\omega t}}{\partial x^{2}}+V(x)\,\psi(x)e^{-i\omega t}\nonumber \\
i\hbar(-i\omega)e^{-i\omega t}\psi(x) & =-\frac{\hbar^{2}}{2m}\frac{\partial^{2}\psi(x)}{\partial x^{2}}e^{-i\omega t}+V(x)\,\psi(x)e^{-i\omega t}\nonumber \\
E\psi(x) & =-\frac{\hbar^{2}}{2m}\frac{\partial^{2}\psi(x)}{\partial x^{2}}+V(x)\,\psi(x)\nonumber \\
\left(-\frac{\hbar^{2}}{2m}\frac{\partial^{2}}{\partial x^{2}}+V(x)\right)\,\psi(x) & =E\,\psi(x)
\end{align}
$$
<span id="timeIndSE"></span>

Eq.([7](timeIndSE)) is known as the time-independent Schrödinger
equation. This equation is the one that will allow us to calculate
the allowed discrete energy states of matter (such as electrons) in
the atom or other systems. 

For now, we understand a wavefunction as something that contains a
particle's mechanical information, and the SE as the equation to solve
to obtain the wavefunction as well as allowed energy states. But...

### 3.5.2 What are wavefunctions actually?

The wavefunction $\Psi(x,t)$ is a complex (as oppose to real) function.
Complex quantities cannot be measured in the real world. Is there
actually a physical meaning associated with this all-important wavefunction? 

No. 

But Max Born offered a "working" statistical interpretation to
the wavefunction: 
$$
\left|\Psi\right|^{2}\equiv\Psi^{*}\Psi\text{ plays the role of a probability density function.}
$$

This interpretation allows one to *use* the wavefunction to
find physically relevant stuffs. For example: 
$$
\int_{a}^{b}\left|\Psi(x,t)\right|^{2}dx=\text{probability of finding the particle between $a$ and $b$ at time $t$}
$$

![The Born interpretation of the wavefunction as a probability desity
function. The probablity of finding the particle in the region $a<x<b$
is equal to the area under the $\left|\Psi\right|^{2}$ graph from
$a$ to $b$. The probability to find the particle around $x=c$ is
the highest while the probability to find the particle around $x=d$
is near zero.](</Resources/Chapter 3/wavefunctionPDF.png>)


With the intepretation of $\left|\Psi\right|^{2}$ as a probability
density function, we have the property that
<span id="normalisation"></span>
$$
\begin{equation}
\int_{-\infty}^{\infty}\left|\Psi(x,t)\right|^{2}dx=1,
\end{equation}
$$
Eq.([8](#normalisation)) is a statement that says that $\left|\Psi\right|^{2}$
is normalised, which simply means that all probabilities add up to
1. 

One can go further into the statistical interpretation by looking
the expected values and varriances of observable physical quantities,
but it is out of the scope of the course and we will leave the interpretation
and use of $\Psi$ as is for now.

We can now try and explore how different systems give rise to different
wavefunctions and allowed energy states..

### 3.5.3 Particle in a box

The particle in a box problem is a thought experiment made by Schrödinger
to illustrate the basics of 'motion' in the quantum world. In this
section, we will solve the time-independent SE for the particle in
box problem[^4].
[^4]: What 'solving' means to physics is that we have to give a (as complete
as possible) description of the physical system in question, which
is usually aided using mathematical equations.

The formal way to state the problem is to ask what happens to the
wavefunction of a single particle along a 1D line when subjected to
the following boundary conditions: 
$$
V(x)=\begin{cases}
0\text{ if }0<x<L,\\
\infty\text{ elsewhere}
\end{cases}
$$

where $V(x)$ is the potential at any point in space. For simplicity,
we shall assume that the particle's wavefunction does not change with
time.

We will first deal with the case of infinite potential as it is easier.
Later we will see what happens when the barriers are finite.

Recall that Schrödinger's equation states that 
$$
\left(-\frac{\hbar^{2}}{2m}\frac{\partial^{2}}{\partial x^{2}}+V(x)\right)\,\psi(x)=E\psi(x)
$$

Inside the box $0<x<L$ where $V=0,$ we have
<span id="inside_box"></span>
$$
\begin{equation}
-\frac{\hbar^{2}}{2m}\frac{\partial^{2}\psi(x)}{\partial x^{2}}=E\psi(x)
\end{equation}
$$
and the wavefunction outside the box must obey 
$$
\begin{equation}
-\frac{\hbar^{2}}{2m}\frac{\partial^{2}\psi(x)}{\partial x^{2}}+\infty\,\psi(x)=E\psi(x)
\end{equation}
$$

We can make an educated assumption that the wavefunction outside the
box must be zero such that Schrodinger's equation still holds[^5]
(because $0=0$). This also gives us the boundary conditions of the
problem:
[^5]: As physicists we sometimes just take infinity times zero to be zero.


<span id="piabBC1"></span>
<span id="piabBC2"></span>
$$
\begin{align}
\psi(0) & =0\\
\psi(L) & =0
\end{align}
$$
But now, what about the wavefunction inside the box?

We can guess the solution must resemble something of form (recall
the restoring force case in Chapter 2 and see the similarity of the
equations)
<span id="ansatz"></span>
$$
\begin{equation}
\psi(x)=ce^{\lambda x}
\end{equation}
$$

Putting the guess solution into the SE, we obtain the general solution
to be 
<span id="PiabGenSol"></span>
$$
\begin{equation}
\psi(x)=c_{1}e^{ikx}+c_{2}e^{-ikx}
\end{equation}
$$
where 
$$
k={\displaystyle \sqrt{\frac{2mE}{\hbar^{2}}}}
$$

Applying the boundary conditions Eq.([11](#piabBC1)) and ([12](#piabBC2)),
we will find that 
$$
c_{1}=-c_{2}
$$
and
$$
kL=n\pi
$$
where $n$ takes positive integer values. Consequently 
$$
\psi(x)=A\sin kx
$$
and <span id="piabEnergyStates"></span>
$$
\begin{equation}
E=\frac{\hbar^{2}n^{2}\pi^{2}}{2mL^{2}}
\end{equation}
$$

$A$ can be determined by normalising the wavefunction with Eq.([8](#normalisation)).
Finally the wavefunction of the particle in a box is
<span id="piabWavefunction"></span>
$$
\begin{equation}
\psi(x)=\sqrt{\frac{2}{L}}\sin\left(\frac{n\pi}{L}x\right)
\end{equation}
$$
and it's allowed energy levels are given by Eq.([15](#piabEnergyStates)).

Also important is to recall that $n$ takes only positive integer
values, thus effectively quantising the energy states and wavefunction.
For this reason, $n$ is known as the quantum number for particle
in a box. 

### 3.5.4 Hydrogen atom and its wavefunction

Welcome back to the Hydrogen atom. The hydrogen atom consists of a
proton and an electron separated by some distance $r$. The potential
of the system is

$$
\begin{equation}
V(r)=-\frac{1}{4\pi\epsilon_{0}}\frac{e^{2}}{r}=-\frac{1}{4\pi\epsilon_{0}}\frac{e^{2}}{\left(x^{2}+y^{2}+z^{2}\right)^{1/2}}
\end{equation}
$$

As the system is 3 dimensional, the time independent SE is 
$$
\left[-\frac{\hbar^{2}}{2\mu}\left(\frac{\partial^{2}}{\partial x^{2}}+\frac{\partial^{2}}{\partial x^{2}}+\frac{\partial^{2}}{\partial x^{2}}\right)-\frac{1}{4\pi\epsilon_{0}}\frac{e^{2}}{\left(x^{2}+y^{2}+z^{2}\right)^{1/2}}\right]\psi=E\,\psi
$$
where 
$$
\mu=\frac{m_{e}m_{p}}{m_{e}+m_{p}}
$$
is so called the reduced mass of the system. We will talk more about
the reduced mass in the next chapter. Meanwhile, in here, since the
mass of the proton $m_{p}$ is much larger than the mass of the electron
$m_{e,}$ we have $\mu\approx m_{e}$. We can concise the notation
and state that the SE of the hydrogen atom is 
<span id="HatomSE"></span>
$$
\begin{equation}
\left[-\frac{\hbar^{2}}{2m_{e}}\nabla^{2}-\frac{1}{4\pi\epsilon_{0}}\frac{e^{2}}{r}\right]\psi=E\,\psi
\end{equation}
$$

The boundary conditions are 
$$
\begin{align*}
\psi(0) & =0\\
\psi(\infty) & =0
\end{align*}
$$
[Translates as: you will not find the electron at the nucleus ($r=0$)
and at somewhere infinitely far away ($r\rightarrow\infty$)].

The procedure to solve the SE is same as that of particle in a box:
Solve the SE with the above bounday conditions. The workings are much
more complicated since the system is three dimensional. The higher
dimensionality also means that more quantum numbers to required to
describe the allowed states of the hydrogen atom. The quantum numbers
are 

1. $n$, the principal quantum number. $n=1,2,3,\dots$
2. $l$, orbital quantum number. $l=0,1,2,\dots,n-1$.
3. $m_{l}$, magnetic quantum number. $m_{l}=-l,\dots,-1,0,1,\dots l$.

The allowed energies of the system is given by 
$$
E=-\frac{e^{4}m_{e}}{32\pi^{2}\epsilon_{0}^{2}\hbar^{2}n^{2}}
$$

The wavefunctions for the hydrogen atom are 
$$
\begin{align*}
\psi_{n=1,l=0,m_{l}=0} & =\frac{1}{\sqrt{\pi}a_{0}^{3/2}}e^{-r/a_{0}}\\
\psi_{n=2,l=0,m_{l}=0} & =\frac{1}{4\sqrt{2\pi}a_{0}^{3/2}}\left(2-\frac{r}{a_{0}}\right)e^{-r/2a_{0}}\\
\psi_{n=2,l=1,m_{l}=0} & =\frac{1}{4\sqrt{2\pi}a_{0}^{3/2}}\frac{r}{a_{0}}e^{-r/2a_{0}}\cos\theta\\
\psi_{n=2,l=1,m_{l}=+1} & =\frac{1}{8\sqrt{\pi}a_{0}^{3/2}}\frac{r}{a_{0}}e^{-r/2a_{0}}\sin\theta e^{i\phi}\\
\psi_{n=2,l=1,m_{l}=-1} & =\frac{1}{8\sqrt{\pi}a_{0}^{3/2}}\frac{r}{a_{0}}e^{-r/2a_{0}}\sin\theta e^{-i\phi}
\end{align*}
$$

Here is 2D visualization of the probabilites of the electron's position
around the nucleus.

![Projections of some wavefunctions of the hydrogen atom. Image credit: <a href="https://chammika-udalagama.github.io/teaching.sp2173-a2m/qm-iii-measurements-i-mommy-where-do-wave-functions-come-from.html\#the-hydrogen-atom-a-real-3d-system">Chammika Udalagama</a>](</Resources/Chapter 3/HatomOrbitals.png>)


The solutions to the hydrogen atom not only opens a pathway to many
new rich areas of physics such a molecular physics which is critical
to the development of physical chemistry. Let us begin to dive into
the how these orbitals play a role in composite systems such as molecules
and their necessary rammifications. 