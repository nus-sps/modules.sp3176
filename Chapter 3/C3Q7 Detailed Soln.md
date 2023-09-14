---
label: Particle in a Box Detailed Solution
layout: page
icon: ":package:"
author:
  - name: Ryan Phillips
    email: ryan.phillips21@sps.nus.edu.sg
    link: https://sps.nus.edu.sg/user/ryan.phillips21/
    avatar: 
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

Recall that Schrödinger's equation states that 
$$
\left(-\frac{\hbar^{2}}{2m}\frac{\partial^{2}}{\partial x^{2}}+V(x)\right)\,\psi(x)=E\psi(x)
$$

Inside the box $0<x<L$ where $V=0,$ we have

<span id="RSP_Piab_1"></span>
$$
\begin{align}
-\frac{\hbar^{2}}{2m}\frac{\partial^{2}\psi(x)}{\partial x^{2}}=E\psi(x)
\end{align}
$$

and the wavefunction outside the box must obey 

$$
\begin{align}
-\frac{\hbar^{2}}{2m}\frac{\partial^{2}\psi(x)}{\partial x^{2}}+\infty\,\psi(x)=E\psi(x) \nonumber
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
But now, what about the wavefunction inside the box?

### Step 2: Observe the differential equation

We can guess its solution; the second derivative of the wavefunction returns itself multiplied by a constant, which implies that the wavefunction must resemble something of form

<span id="RSP_Piab_4"></span>
$$
\begin{align}
\psi(x)=ce^{\lambda x}
\end{align}
$$
where $\lambda$ is a complex value.

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
-\frac{\hbar}{2m} (\lambda^2 ce^{\lambda x}) &= E(ce^{\lambda x}) \nonumber\\ 
-\frac{\hbar}{2m} \lambda^2 &= E \nonumber\\
\lambda^2 &= -\frac{2mE}{\hbar} \nonumber\\
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

Notice that for Eq.([8](#RSP_Piab_8)), the sine function only returns 0 when $\underline{kL = n\pi}$, where $n$ takes positive integer values. See Figure 1 below.

<span id="Sine_and_Cosine"></span>
![Figure 1: A sine curve. Points where $\sin(x)=0$ are integer multiples of $\pi$. Taken from <a href="https://en.wikipedia.org/wiki/Sine_wave">Wikipedia</a>](</Resources/Chapter 3/Sine_and_Cosine.svg>)

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



### Step 4: Normalize the wavefunction

Consequently, 
$$
\psi(x)=A\sin kx
$$

where $A$ is a complex constant.

Recall that 
$$
\int_{-\infin}^{\infin} |\Psi|^2 \space dx= 1
$$

hence
<span id="RSP_Piab_10"></span>
$$
\begin{align}
\int_{-\infin}^{\infin} \psi(x)\psi^*(x) \space dx &= 1 \nonumber \\
\int_{-\infin}^{\infin} A^2 \sin^2(kx) \space dx &= 1 \nonumber \\
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

Note that the wavefunction in Eq.([11](#RSP_Piab_11)) can take either positive or negative values of $A$ because it has no physical meaning after all. We are mainly interested in the square of the wavefunction which ignores the positive or negative sign.

Also important is to recall that $n$ takes only positive integer
values, thus effectively quantising the energy states and wavefunction.
For this reason, $n$ is known as the quantum number for particle
in a box. 

