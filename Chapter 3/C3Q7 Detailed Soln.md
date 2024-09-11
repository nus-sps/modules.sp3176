---
label: Particle in a Box Detailed Solution
layout: page
icon: ":package:"
author:
  - name: Ryan Phillips
    email: ryan.phillips21@sps.nus.edu.sg
    link: https://sps.nus.edu.sg/user/ryan.phillips21/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/ultimatemember/232/profile_photo-190x190.jpg?1723621545
date: 2023-09-13T00:00
description: "Light and Atoms"
---

## Context

The particle in a box problem is a thought experiment made by Schrödinger
to illustrate the basics of 'motion' in the quantum world. In this
section, we will solve the time-independent SE for the particle in
box problem[^4].
[^4]: What 'solving' means to physics is that we have to give a (as complete
as possible) description of the physical system in question, which
is usually aided using mathematical equations.

### Step 1: Set boundary conditions

The formal way to state the problem is to ask what happens to the
wavefunction of a single particle along a 1D line when subjected to
the following boundary conditions: 
$$
V(x)=\begin{cases}
0\text{ if }0<x<L,\\
\infty\text{ elsewhere}
\end{cases}
$$

where $V(x)$ is the potential at any point in space. For simplicity, we assumed $V(x)=0$ inside the box and that the particle's wavefunction does not change with time. 

Next, we need the Schrödinger's equation, though it is a difficult equation to solve as it has derivatives in both time $t$ and position $x$. If one is interested to find the "stationary solutions", such as standing waves, then it is beneficial to remove time from the SE.

Recall the Time-independent Schrödinger's equation states that 
$$
\left(-\frac{\hbar^{2}}{2m}\frac{\partial^{2}}{\partial x^{2}}+V(x)\right)\,\psi(x)=E\psi(x)
$$

Inside the box $0<x<L$ where $V(x)=0,$ we have

<span id="RSP_Piab_1"></span>
$$
\begin{align}
-\frac{\hbar^{2}}{2m}\frac{\partial^{2}\psi(x)}{\partial x^{2}}=E\psi(x)
\end{align}
$$

and the wavefunction outside the box must obey $V(x)=\infty,$

$$
\begin{align}
\left(-\frac{\hbar^{2}}{2m}\frac{\partial^{2}\psi(x)}{\partial x^{2}}+\infty \right)\psi(x) =E\psi(x) \nonumber
\end{align}
$$

We can make an educated assumption that the wavefunction outside the
box must be zero such that Schrodinger's equation still holds[^5]
(because $0=0$). This also gives us the boundary conditions of the
problem:
[^5]: As physicists we sometimes just take infinity times zero to be zero.

<span id="RSP_Piab_2"></span>
$$
\begin{align}
\psi(0) & =0  \\
\psi(L) & =0 
\end{align}
$$
But now, what about the wavefunction inside the box for $0 < x< L$?

### Step 2: Observe the differential equation

We can guess its solution; the second derivative of the wavefunction returns itself multiplied by a constant, which implies that the wavefunction must resemble something of form

<span id="RSP_Piab_4"></span>
$$
\begin{align}
\psi(x)=ce^{\lambda x}
\end{align}
$$
where $\lambda$ is a complex value. If you've forgotten why, see [3.5.1 The Wavefunction and Schrödinger's equation](</Chapter 3/Quantum Mechanics#generalWave>).

Taking the first and second derivative,

$$
\begin{align}
\psi'(x) &=\lambda ce^{\lambda x} \nonumber \\ 
\psi''(x)&=\lambda^2 ce^{\lambda x}  \nonumber 
\end{align}
$$

Substituting into the SE, we obtain

<span id="RSP_Piab_5"></span>
$$

\begin{align}
-\frac{\hbar^2}{2m} (\lambda^2 ce^{\lambda x}) &= E(ce^{\lambda x}) \nonumber\\ 
-\frac{\hbar^2}{2m} \lambda^2 &= E \nonumber\\
\lambda^2 &= -\frac{2mE}{\hbar^2} \nonumber\\
\lambda &= \pm\sqrt{-1}\sqrt{\frac{2mE}{\hbar^2}} \nonumber\\
\lambda &= \pm i\sqrt{\frac{2mE}{\hbar^2}}  \\ 
\end{align}

$$

Putting the guess solution into the SE, we obtain the general solution to be 

<span id="RSP_Piab_6"></span>
$$
\begin{align}
\psi(x)=c_{1}e^{ikx}+c_{2}e^{-ikx} 
\end{align}
$$
where $c_1, c_2$ are some constants and $ k = \sqrt{\frac{2mE}{\hbar^2}} $.

### Step 3: Apply the boundary conditions 

Applying the boundary conditions Eq.([2](#RSP_Piab_2)) and ([3](#RSP_Piab_3)), we will find that 

$$
\begin{align}
\psi(0)= c_{1}e^{0}+c_{2}e^{0} &= 0 \nonumber \\
c_{1} + c_{2} &= 0 \nonumber \\
c_{1} &= - c_{2} \nonumber \\
\end{align}
$$

and thus

<span id="RSP_Piab_7"></span>
$$
\begin{align}
\psi(L)= c_{1}e^{ikL}-c_{1}e^{-ikL}  = 0 \nonumber \\
c_{1}(e^{ikL}-e^{-ikL})  = 0  \\
\end{align}
$$

Using Euler's identity and since $\cos(x)=\cos(-x)$ while $-\sin(x)=\sin(-x)$,

$$
\begin{align}
e^{ix} = \cos(x) + i\sin(x) \nonumber \\
e^{-ix} = \cos(x) - i\sin(x) \nonumber \\
e^{ix}-e^{-ix}  = 2i \sin(x)  \nonumber \\
\end{align}
$$

we can use these to simplify Eq.([7](#RSP_Piab_7)) such that

<span id="RSP_Piab_8"></span>
$$
\begin{align}
c_{1}(e^{ikL}-e^{-ikL})  = 0 \nonumber \\
c_{1}[2i \sin(kL)] = 0
\end{align}
$$

We don't have to worry about the complex constants $2ic_{1}$ and can simplify it to some $A$. What's more important is that for Eq.([8](#RSP_Piab_8)), the sine function only returns 0 when $\underline{kL = n\pi}$, where $n$ takes positive integer values. See Figure 1 below.

<span id="Sine_and_Cosine"></span>
![Figure 1: Sine and cosine curves. Points where $\sin(x)=0$ are integer multiples of $\pi$. Taken from <a href="https://en.wikipedia.org/wiki/Sine_wave">Wikipedia</a>](</Resources/Chapter 3/Sine_and_Cosine.svg>)

At this point, we can already obtain the energy states equation. First, we rearrange the finding from Eq.([8](#RSP_Piab_8)):


$$
\begin{align}
kL = n\pi  \nonumber \\
k = \frac{n\pi}{L}  \nonumber \\
\end{align}
$$

and comparing with the value of $k$ from Eq.([6](#RSPPiab_6)),

<span id="RSP_Piab_9"></span>
$$
\begin{align}
k &= \space \sqrt{\frac{2mE}{\hbar^2}} \nonumber \\
k^2 &= \frac{2mE}{\hbar^2} \nonumber \\
\frac{n^2 \pi^2}{L^2} &= \frac{2mE}{\hbar^2} \nonumber \\
E &= \frac{\hbar^{2}n^{2}\pi^{2}}{2mL^{2}}  \\
\end{align}
$$

Unlike Bohr’s atomic model which **postulated** that discrete energy levels exist,
Schrodinger’s derivation **naturally shows** that energy levels must take discrete values! Recall $n$ takes only positive integer
values, and is also known as the quantum number. 

### Step 4: Normalize the wavefunction

Consequently, from Eq.([8](#RSP_Piab_8)) we have
$$
\psi(x)=A\sin kx
$$

where $A$ is a complex constant.

Recall our normalization condition  
$$
\int_{-\infin}^{\infin} |\Psi|^2 \space dx= 1
$$

hence
<span id="RSP_Piab_10"></span>
$$
\begin{align}
\int_{-\infin}^{\infin} \psi(x)\psi^*(x) \space dx &= 1 \nonumber \\
\int_{-\infin}^{\infin} |A|^2 \sin^2(kx) \space dx &= 1 \nonumber \\
\int_{-\infin}^{\infin} \sin^2(kx) \space dx &= \frac{1}{A^2}  \\
\end{align}
$$
Using the trigonometric identity, 
$$
\sin^2(x) = \frac{1-\cos(2x)}{2}
$$
and adjusting the limits to the regions we are interested in, we can integrate Eq.([9](#RSPPiab_9)) as follows:

$$
\begin{align}
\int_{0}^{L} \frac{1-\cos(2kx)}{2} \space dx &= \frac{1}{A^2} \nonumber \\
\int_{0}^{L} 1-\cos(2kx) \space dx &= \frac{2}{A^2} \nonumber \\
\left[ x-\frac{\sin(2kx)}{2} \right]_0^L &= \frac{2}{A^2} \nonumber \\
\left[ L-\frac{\sin(2kL)}{2} -0 \right] &= \frac{2}{A^2}, \text{ where sin(2kL) = sin(2nπ) = 0} \nonumber \\
L &= \frac{2}{A^2} \nonumber \\
A &= \pm\sqrt{\frac{2}{L}} \nonumber \\

\end{align}
$$

Finally the wavefunction of the particle in a box is
<span id="RSP_Piab_11"></span>
$$
\begin{equation}
\psi(x)=\sqrt{\frac{2}{L}}\sin\left(\frac{n\pi}{L}x\right)
\end{equation}
$$
and it's allowed energy levels are given by Eq.([9](#RSP_Piab_9)). 

Note that the wavefunction in Eq.([11](#RSP_Piab_11)) can take either positive or negative values of $A$. Wavefunctions have no physical meaning so it does not matter which we take;  squared values are always positive. 

We are only concerned with the square of the wavefunction as it gives us the Probability Density Function which tells us the probability of finding the particle within $x_0$ and $x_1$.

$$
\begin{align}
P(x_0<x<x_1) &= \int_{x_0}^{x_1} \psi(x)\psi^*(x) \space dx \nonumber \\
&= \int_{x_0}^{x_1} |\psi(x)|^2 \space dx \\

\end{align}
$$


!!! Bonus
For those interested in simulating the energies and wavefunctions for a particle in a box before and after perturbations, visit this [!badge icon="/resources/common/Colab.jpg" target="blank" text="Google Colab"](https://colab.research.google.com/drive/1CejNKVGhs_NYrOwHSicezg-w1jzloZpK?usp=sharing) and explore on your own!  

!!!
