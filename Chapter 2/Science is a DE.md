---
label: Science is a Differential Equation
layout: default
icon: ":chart_with_upwards_trend:"
order: -2
author:
  - name: Dr Lim Zhi Han
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/lim.zhihan/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/2019/06/logo_sps20.png
date: 2022-07-28T14:16
description: "Falling Apples and Orbiting Planets"
---

## 2.2 Science is a differential equation. Religion is a boundary condition.

The title of this section is a quote by [Alan Turing](https://en.wikipedia.org/wiki/Alan_Turing).
Initial conditions discussed earlier is a type of boundary condition.
We have seen how important these conditions are in nfluencing outcomes.
To fully appreciate Turing's quote, we need to know what are differential
equations. 

### 2.2.1 Differential Equations Model Things that Change

Differential equations (DEs) are equations that have terms involving
differentiations. DEs are widely used as mathematical statements to
describe how quantities change. Such statements are often logical. 

#### Beer foam dynamics

For example, beer foam are air bubbles , and bubbles pop. When there
are more bubbles, there will be more popping. When bubbles pop, there
will be less bubbles. The rate of change of the number of bubbles
in a column of beer foam is proportional to the number of bubbles
there are. I hope this sounds logical. If not, get a drink.. We model
this scenario wth 
$$
\frac{dN}{dt}=-kN
$$
where $N$ is the number of bubbles at time $t$, and $k$ is a positive
constant.

#### Particle dynamics

A more relevant example to this chapter is Newton's law of motion.
We know that a force is capable of changing an object's velocity $v$.
More force, more change. Newton says that the resultant force applied
to a particle is proportional to the rate of change in velocity
$$
F=m\frac{dv}{dt}
$$
where $m$ is a constant known as (inertial) mass.

#### Love dynamics

Love is a more complicated affair. Romeo loves Juliet. The more attention
he gets from Juliet, the more feelings he have for her. Juliet is
different (and Romeo don't get it). The more affection Romeo displays,
the more repulsive she finds him. But when Romeo do not give her as
much attention, she starts to develop more feelings for him. We can
model the lovers' feelings as follows:
$$
\begin{align*}
\frac{dR}{dt} & =k_{1}J\\
\frac{dJ}{dt} & =-k_{2}R
\end{align*}
$$


#### Quantum mechanics

The modern view of how molecules, atoms and subatomic particles behave
is that they follow rules of quantum mechanics. The Schrödinger equation
(presented in the 1-dimensional, time independent form) below is a
differential equation that describe how the wavefunction $\psi(x)$
of a particle changes with position $x$ in different physical conditions
$V(x)$. The wavefunction itself relates to the probability of finding
the particle. The bigger the wavefunction at a position, the higher
the chance of finding the particle around that position.

$$
-{\displaystyle \frac{\hbar^{2}}{2m}\frac{d^{2}\psi}{dx^{2}}}+\left(V(x)-E\right)\psi(x)=0
$$

### 2.2.2 Solving DEs Analytically

#### 2.2.2.1 Case 1: Beer foam

Let $N(t)$ be the number of bubbles at time $t$.

Let $N(0)=N_{0}$.

As introduced above, 
$$
\frac{dN}{dt}=-kN
$$
where $k$ is a positive constant. 

Bringing $N$ to the LHS and then integrating both sides with respect
to $t$,

$$
\begin{align*}
\int\frac{1}{N}dN & =\int-kdt\\
\ln N & =-kt+c\\
N & =e^{-kt+c}\\
 & =e^{c}e^{-kt}
\end{align*}
$$

Using $N(0)=N_{0}$ to find $c$,
$$
\begin{align*}
N_{0} & =e^{c}e^{0}=e^{c}\\
\Rightarrow N & =N_{0}e^{-kt}
\end{align*}
$$
Go to [Activity 1](<Chapter 2/In-Class Activities>).

#### 2.2.2.2 Case 2: Constant force on particle

Assume a constant force $F$ acting on a particle with initial velocity
$v(0)=v_{0}$. 

We apply Newton's law of mechanics:
$$
\begin{align*}
F & =m\frac{dv}{dt}\\
\frac{dv}{dt} & =\frac{F}{m}\\
\int dv & =\int\frac{F}{m}dt\\
v & =\frac{F}{m}t+c
\end{align*}
$$
Throw in the initial condition $v(0)=v_{0}$,
$$
\begin{align*}
v_{0} & =0+c\\
\Rightarrow v & =\frac{F}{m}t+v_{0}
\end{align*}
$$

Let us define acceleration of the particle $a$ as 
$$
a=\frac{dv}{dt}
$$
It follows that $a=\dfrac{dv}{dt}=\dfrac{F}{m}$ is a constant in
this case. We can now write
$$
v=v_{0}+at
$$

Let us also define the position of the particle $x(t)$ with 
$$
v=\frac{dx}{dt}
$$

This allows us to solve for $x$:
$$
\begin{align*}
\frac{dx}{dt} & =v_{0}+at\\
\int dx & =\int(v_{0}+at)dt\\
x & =v_{0}t+\frac{1}{2}at^{2}+c
\end{align*}
$$

Let $x(0)=0$. (We can do this because we can set the origin at anywhere!)
$$
\begin{align*}
0 & =0+c\\
\Rightarrow x & =v_{0}t+\frac{1}{2}at^{2}
\end{align*}
$$

Derived above are the so-called kinematic equations which you may
be familiar with.

#### 2.2.2.3 Case 3: Restoring force / Harmonic Oscillator

Think of a spring with one end attached on a wall and the other end
to a particle. The longer you pull the , the greater the force in
the spring that wants to restore it back to the original state. The
scenario is described with a vector equation:

$$
F=-kx
$$
where $F$ is the spring force and $x$ the displacement from the
equilibrium position of the spring. Applying Newton's law, 
$$
F=m\frac{dv}{dt}=m\frac{d^{2}x}{dt^{2}}=-kx
$$
$$
\frac{d^{2}x}{dt^{2}}=-\frac{k}{m}x
$$
An educated guess of the solution of $x$ is
$$
x=ce^{\lambda t}
$$
The reason behind this guess is that differentiating an exponential
function gives back an exponential function. With this guess, we carry
on to differentiate it and fit it back to the DE:
$$
\begin{align*}
\frac{dx}{dt} & =c\lambda e^{\lambda t}\\
\frac{d^{2}x}{dt^{2}} & =c\lambda^{2}e^{\lambda t}\\
c\lambda^{2}e^{\lambda t} & =-\frac{k}{m}ce^{\lambda t}\\
\lambda^{2} & =-\frac{k}{m}\\
\lambda & =\pm\sqrt{-\frac{k}{m}}\\
 & =\pm i\sqrt{\frac{k}{m}}
\end{align*}
$$

Hence the solution is 
$$
x=c_{1}e^{i\sqrt{k/m}t}+c_{2}e^{-i\sqrt{k/m}t}
$$

Assuming the following \textbf{initial conditions}:
$$
\begin{align*}
x(0) & =x_{0}\\
v(0) & =0
\end{align*}
$$

 This is the scenario where you pull the spring by a certain extension
($x_{0})$, and then let go. 
$$
\begin{align*}
v(t) & =ic_{1}\sqrt{\frac{k}{m}}e^{i\sqrt{k/m}t}-ic_{2}\sqrt{\frac{k}{m}}e^{-i\sqrt{k/m}t}\\
v(0)=0 & =ic_{1}-ic_{2}\\
c_{1} & =c_{2}
\end{align*}
$$
$$
\begin{align*}
x(0) & =c_{1}+c_{2}=x_{0}\\
c_{1} & =\frac{x_{0}}{2}\\
x & =\frac{x_{0}}{2}\left(e^{i\sqrt{k/m}t}+e^{-i\sqrt{k/m}t}\right)\\
 & =x_{0}\cos\left(\sqrt{\frac{k}{m}}t\right)
\end{align*}
$$

#### 2.2.2.4 Case 4: Love (is not that complicated)

Recall Romeo and Juliet
$$
\begin{align*}
\frac{dR}{dt} & =k_{1}J\\
\frac{dJ}{dt} & =-k_{2}R
\end{align*}
$$
where $k_{1}$ and $k_{2}$ are (positive) constants. 

Since both $R$ and $J$ are functions of time, the above is a set
of coupled DEs. One cannot solve for $R$ without knowing $J$, and
vice versa. One way to decouple them is to take the time derivative
on one of them, say $R$:
$$
\begin{align*}
\frac{d}{dt}\frac{dR}{dt} & =\frac{d}{dt}k_{1}J\\
\frac{d^{2}R}{dt^{2}} & =k_{1}\frac{dJ}{dt}\\
\frac{d^{2}R}{dt^{2}} & =-k_{1}k_{2}R
\end{align*}
$$

If we look at the above equation carefully we will notice that it
is the DE for a restoring force / harmonic oscillator ($x\rightarrow R,m\rightarrow1,k\rightarrow k_{1}k_{2}$
)!

Assume the initial conditions 
$$
\begin{align*}
R(0) & =R_{0}\\
J(0) & =0,
\end{align*}
$$

(This is equivalent to $x(0)=x_{0},v(0)=0$ in the harmonic oscillator
case.)

The solutions are 
$$
\begin{align*}
R & =R_{0}\cos(\sqrt{k_{1}k_{2}}t)\\
J & =\frac{1}{k_{1}}\frac{dR}{dt}=-\frac{1}{k_{1}}R_{0}\sqrt{k_{1}k_{2}}\sin(\sqrt{k_{1}k_{2}}t)=-\sqrt{\frac{k_{2}}{k_{1}}}R_{0}\sin(\sqrt{k_{1}k_{2}}t)
\end{align*}
$$

Go to [Activity 2](<Chapter 2/In-Class Activities>).

### 2.2.3 Solving DEs Numerically

We will use the simple Euler's method to numerically solve DEs. Simply
approximate $\dfrac{df}{dt}$ with $\dfrac{\Delta f}{\Delta t}$ and
choose an appropriately small $\Delta t$.

#### 2.2.3.1 Case 1: Beer foam

Let
$$
\begin{align*}
\frac{\Delta N}{\Delta t} & =\frac{dN}{dt}=-kN\\
N(0) & =1000=N_{0}\\
k & =0.2\\
\Delta t & =0.01
\end{align*}
$$
 We know $N_{0}$ at first. The numerical schemes finds $N_{1}$ using
$N_{0}$, then finds $N_{2}$ using $N_{1}$ and so on.$N$
$$
\begin{align*}
N_{i+1} & =N_{i}+\Delta N\\
 & =N_{i}+\frac{\Delta N}{\Delta t}\Delta t\\
 & =N_{i}-kN_{i}\Delta t
\end{align*}
$$
We can implement this on in a computer (Python) and plot the solution. 


!!! Try it yourself!
Do the above!
!!!


Any numerical solution will have an error. As the analytical solution
is known, we can track the error with
$$
\text{fractional error}=\frac{\text{numerical solution}-\text{analytical solution}}{\text{analytical solution}}
$$

![Left: Numerical solution of $N(t)$ using Euler's method.</br> Right: Fractional
error against time. We can see that the fractional error accumulates
with time.](</resources/Chapter 2/numDE_beer.png>)


#### 2.2.3.2 Case 2: Love (is in the numbers)

$$
\begin{align*}
\frac{\Delta R}{\Delta t} & \approx\frac{dR}{dt}=k_{1}J\\
\frac{\Delta J}{\Delta t} & \approx\frac{dJ}{dt}=-k_{2}R\\
R(0) & =R_{0}=1\\
J(0) & =J_{0}=0
\end{align*}
$$

Euler method: 
$$
\begin{align*}
R_{i+1} & =R_{i}+\Delta R=R_{i}+k_{1}J_{i}\Delta t\\
J_{i+1} & =J_{i}+\Delta J=J_{i}-k_{2}R_{i}\Delta t
\end{align*}
$$

We can implement this on a computer as was done previously for the
case of beer foam.


!!! Try it yourself!

Do the above for $k_{1}=1$, $k_{2}=0.8$, $\Delta t=0.001$. 

Plot $R(t)$ and $J(t)$ on the same graph.

Plot $J$ vs $R$.
!!!


Introducing a modified Euler method known as the Euler-Cromer method[^1]:
$$
\begin{align*}
R_{i+1} & =R_{i}+\Delta R=R_{i}+k_{1}J_{i}\Delta t\\
J_{i+1} & =J_{i}+\Delta J=J_{i}-k_{2}R_{i+1}\Delta t
\end{align*}
$$

[^1]:  A. Cromer, Stable solutions using the Euler Approximation, American
Journal of Physics, 49, 455 (1981)

Note the difference with the original Euler method?

Go to [Activity 3](<Chapter 2/In-Class Activities>).
