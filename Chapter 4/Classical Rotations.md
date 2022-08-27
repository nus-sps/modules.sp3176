---
label: Classical Rotations
layout: default
icon: ":arrows_counterclockwise:"
order: -2
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
## 4.2 Classical Rotations and Vibrations
---

### 4.2.1 Rigid Rotor

Consider a particle of mass $m$ rotating around an axis. The inertia
towards linear motion is the particle's mass $m$. For rotational
motion, mass is insufficient to quantify the amount of inertia for
rotational motion. The distance away from the axis of rotation plays
a role too. One way to demonstrate this is to rotate a rod with a
weight attached. The further the weight is away from the axis of rotation,
the harder it is to rotate. The reluctance to rotate is termed as
moment of inertia.

![A particle with mass $m$ rotating about an axis at a distance $r$
away, moving with (instantaneous) linear speed $v$ and angular speed
$\omega$. The particle possess a moment of inertia $I=mr^{2}$ and
an angular momentum of $L=I\omega^{2}.$](</Resources/Chapter 4/rotation.png>)

The particle's motion is characterised by:

- $r$ : distance between the particle and axis
- $I$ : moment of inertia
- $v$ : velocity 
- $\omega$ : angular velocity 
- $p$ : linear momentum
- $L$ : angular momentum
- $T$ : kinetic energy

The above parameters are closely related by the following equations:

<span id="MI"></span>
$$
\begin{equation}
I=mr^{2}
\end{equation}
$$


<span id="velocity"></span>
$$
\begin{equation}
v=r\omega
\end{equation}
$$


<span id="mom"></span>
$$
\begin{equation}
p=mv
\end{equation}
$$

<span id="angMom"></span>
$$
\begin{equation}
L=I\omega
\end{equation}
$$

<span id="KE"></span>
$$
\begin{equation}
T=\frac{1}{2}mv^{2}=\frac{1}{2}mr^{2}\omega^{2}=\frac{1}{2}I\omega^{2}
\end{equation}
$$

!!! Try it yourself!
Spend some time with the above equations and
make sense of the ones that involve angular motion.
!!!

Let us now consider the case of two particles with masses $m_{1}$
and $m_{2}$ joined by a rigid (massless) rod of length $R$. The
2-body system has a center of mass. Let us set the center of mass
to be at the origin, mass $m_{1}$ to be located at distance $r_{1}$
away from the center of mass, and mass $m_{2}$ at $r_{2}$ away.
Since the 2 masses are at opposite sides of the center of mass,
<span id="lengthOfRotor"></span>
$$
\begin{equation}
r_{1}+r_{2}=R
\end{equation}
$$
By principle of moments[^1]

[^1]:CW moments = CCW moments, which you have learned in Sec school!

<span id="PrincipleOfMoments"></span>
$$
\begin{equation}
m_{1}r_{1}=m_{2}r_{2}
\end{equation}
$$


Now set these masses on the $xy$ plane, have the $z$ axis to cut
through the center of mass and allow the masses to rotate around the
$z$ axis. This is the rigid rotor which we will use to model a rotating
diatomic molecule.

![Two particles with masses $m_{1}$ and $m_{2}$ joined by a rigid
massless rod rotates about an axis that cuts through the centre of
mass.](</Resources/Chapter 4/Diatomic Rotation.png>)


!!! Try it yourself!
Ex. Use Eqs.([6](#lengthOfRotor)) and ([7](#PrincipleOfMoments))
to derive 
<span id="r1"></span>
$$
\begin{equation}
r_{1}=\frac{m_{2}}{m_{1}+m_{2}}R
\end{equation}
$$
<span id="r2"></span>
$$
\begin{equation}
r_{2}=\frac{m_{1}}{m_{1}+m_{2}}R
\end{equation}
$$
!!!

</br>

The moment of inertia of the system is given by 
<span id="MIreducedMass"></span>
$$
\begin{align}
I & =m_{1}r_{1}^{2}+m_{2}r_{2}^{2}\nonumber \\
 & =m_{1}\left(\frac{m_{2}}{m_{1}+m_{2}}R\right)^{2}+m_{2}\left(\frac{m_{1}}{m_{1}+m_{2}}R\right)^{2}\nonumber \\
 & =\frac{m_{1}m_{2}R^{2}}{(m_{1}+m_{2})^{2}}(m_{2}+m_{1})\nonumber \\
 & =\frac{m_{1}m_{2}}{m_{1}+m_{2}}R^{2}\nonumber \\
 & =\mu R^{2}
\end{align}
$$

$\mu$ is the called "effective mass". By expressing the moment
of inertia in Eq.([10](#MIreducedMass)) allows us to treat the
2-body system like a single particle. 

Since the rotor is "rigid", the two masses share the same angular
velocity $\omega$. The angular momentum of the system is 
<span id="angMom-1"></span>
$$
\begin{equation}
L=I\omega
\end{equation}
$$

The kinetic energy is 
<span id="rigidRotorKE"></span>
$$
\begin{equation}
T=\frac{1}{2}m_{1}r_{1}^{2}\omega^{2}+\frac{1}{2}m_{2}r_{2}^{2}\omega^{2}=\frac{1}{2}I\omega^{2}=\frac{L^{2}}{2I}
\end{equation}
$$

What is the potential energy of the system?

<span id="regidRotorPE"></span>
$$
\begin{equation}
V=0
\end{equation}
$$
 No potential energy, the rigid rotor here rotates "freely".

### 4.2.2 Harmonic Oscillator

In chapter 2, we learned about the case of one particle attached to
a massless spring. We shall now extend the idea to two particles connected
by a spring.
<span id="2massSpring"></span>
![Two particles with masses $m_{1}$ and $m_{2}$ joined by a massless
spring.](</Resources/Chapter 4/2massSpring.png>)


The equations of motion of the two masses are 

<span id="eq:eom1-1"></span>
$$
\begin{equation}
m_{1}\ddot{x}_{1}=k(x_{2}-x_{1}-x_{0})
\end{equation}
$$
<span id="eq:eom2-1"></span>
$$
\begin{equation}
m_{2}\ddot{x}_{2}=-k(x_{2}-x_{1}-x_{0})
\end{equation}
$$

Similar to how the 2-masses rigid rotor can be re-modeled as a rotation
of a particle with an effective mass, the 2-masses-connected-by-a-spring
system can be re-modeled as a single particle undergoing simple harmonic
motion: 

<span id="HO_accel"></span>
$$
\begin{equation}
\ddot{x}=-\omega^{2}x
\end{equation}
$$
where $\omega$ is the angular frequency
<span id="HO_angFreq"></span>
$$
\begin{equation}
\omega=\sqrt{\frac{k}{\mu}}
\end{equation}
$$
$k$ is the spring constant, and $\mu$ is the effective mass given
by 
<span id="HO_effMass"></span>
$$
\begin{equation}
{\displaystyle \mu=\frac{m_{1}m_{2}}{m_{1}+m_{2}}}
\end{equation}
$$

The kinetic energy of the system is 
<span id="H0_KE"></span>
$$
\begin{equation}
T=\frac{1}{2}\mu\dot{x}^{2}=\frac{p^{2}}{2\mu}
\end{equation}
$$

The potential energy of the system is 
<span id="HO_potential"></span>
$$
\begin{equation}
V=\frac{1}{2}kx^{2}=\frac{1}{2}\mu\omega^{2}x^{2}
\end{equation}
$$
 

For the interested reader, the detailed derivation of the above equations
is given in [Appendix](Appendix). 


