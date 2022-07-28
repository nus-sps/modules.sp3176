---
label: In-Class Activities
layout: default
icon: ":teacher:"
order: -4
author:
  - name: Dr Lim Zhi Han
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/lim.zhihan/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/2019/06/logo_sps20.png
date: 2022-07-28T14:16
description: "Falling Apples and Orbiting Planets"
---

## 2.4 In-Class Activities


### 2.4.1 Activity 1: How to win an Ig Nobel Prize

Observe the decay of beer foam and think of science.

### 2.4.2 Activity 2: Love plot

For some chosen values of $R_{0},k_{1}$ and $k_{2}$, plot $R(t)$
and $J(t)$ on the same graph on Desmos.

$$
\begin{align*}
R & =R_{0}\cos(\sqrt{k_{1}k_{2}}t)\\
J & =-\sqrt{\frac{k_{2}}{k_{1}}}R_{0}\sin(\sqrt{k_{1}k_{2}}t)
\end{align*}
$$

Open a new Desmos window and plot $R$ vs $J$. 

Can you form a conserved quantity using $R$ and $J$? (A quantity
that do not change with time $t$.)

### 2.4.3 Activity 3: Numerical solution for love

Solve the case of love numerically with 

1. Euler Method
2. Euler-Cromer Method

Compare the numerical solutions with the analytical solution. 

Also use the conserved quantity to compare the two numerical methods. 

### 2.4.4 Activity 4: VPython code for the Earth-Sun system

Take a close look at the code below. In you group, discuss and make
sense of the code below. 
```
GlowScript 2.2 VPython 

#constants 

R=15e9
Re=150e9
Ms=2e30
Me=6e24
G=6.67e-11

#creating the Sun, set the initial position
sun=sphere(pos=vector(0,0,0), radius=R, color=color.yellow)
sun.m=Ms
#sun.p=vector(0,0,0)*sun.m

#creating Earth, set the initial position and momentum
earth=sphere(pos=vector(Re,0,0), radius=0.4*R, color=color.green)
earth.m=Me
earth.p=vector(0,30e3,0)*earth.m

#Some physics
#here I set the momentum of sun so that the total momentum is zero
sun.p=-(earth.p)

#aesthetics
attach_trail(sun)
attach_trail(earth)

#initial time and time step
t=0
dt=50

#now the serious coding
while t<15000000000:
    rate(10**5)

    #vector from sun to earth
    rse=earth.pos-sun.pos

    #Newton's law of gravitation
    #Fse is the force the Sun exerts on the Earth
    Fse=-G*sun.m*earth.m*norm(rse)/mag(rse)**2

    #Fes is the force the Earth exerts on the Sun. By Newton's third law,
    Fes=-Fse

    #update momentum (with total vector force)

    #Newton's second law
    earth.p=earth.p+(Fse)*dt
    sun.p=sun.p+(Fes)*dt

    #update position
    #relation between momentum and position vectors
    sun.pos=sun.pos+sun.p*dt/sun.m
    earth.pos=earth.pos+earth.p*dt/earth.m

    t=t+dt

```

Run the code in [Trinket](https://trinket.io/glowscript/7bdf9fcfab).

In your program, change parameters one at a time and observe the difference
in results. For example change the initial Earth momentum to 
```
earth.p=vector(0,38e3,0)*earth.m
```
Play around and record any notable ''discoveries''.




Get an account in [Trinket](https://trinket.io). Sign in, create a new trinket
program (select Glowscript) and copy and paste the the Sun-Earth code.
Now the program is yours!

