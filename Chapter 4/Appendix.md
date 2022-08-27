---
label: Appendix
layout: default
icon: ":abacus:"
order: -10
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
## 4.-1 Appendix

### Derivation of 2-mass-1-spring simple harmonic oscillator.

![](</Resources/Chapter 4/2massSpring.png>)


The equations of motion of the two masses are 

<span id="eom1"></span>
$$
\begin{equation}
m_{1}\ddot{x}_{1}=k(x_{2}-x_{1}-x_{0})
\end{equation}
$$
<span id="eom2"></span>
$$
\begin{equation}
m_{2}\ddot{x}_{2}=-k(x_{2}-x_{1}-x_{0})
\end{equation}
$$

Let $x_{c}$ be the center of mass. By principle of moments, 

<span id="COM"></span>
$$
\begin{equation}
m_{1}(x_{c}-x_{1})=m_{2}(x_{2}-x_{c})
\end{equation}
$$

Let $x_{d}$ be the distance between the two masses 
<span id="distSep"></span>
$$
\begin{equation}
x_{d}=x_{2}-x_{1}
\end{equation}
$$

This gives
<span id="x1"></span>
$$
\begin{align}
m_{1}x_{c}-m_{1}x_{1} & =m_{2}(x_{d}+x_{1})-m_{2}x_{c}\nonumber \\
x_{1}(m_{1}+m_{2}) & =(m_{1}+m_{2})x_{c}-m_{2}x_{d}\nonumber \\
x_{1} & =x_{c}-\frac{m_{2}}{m_{1}+m_{2}}x_{d}
\end{align}
$$
Similarly, 
<span id="x2"></span>
$$
\begin{equation}
x_{2}=x_{c}+\frac{m_{1}}{m_{1}+m_{2}}x_{d}
\end{equation}
$$

We sought to re-write the equations of motion in terms of $x_{c}\text{ and }x_{d}$.
Putting Eq.([4](#distSep)), ([5](#x1)) and ([6](#x2))
into Eq.([1](#eom1)) and ([2](#eom2)]), we have

$$
\begin{align*}
m_{1}\left(\ddot{x}_{c}-\frac{m_{2}}{m_{1}+m_{2}}\ddot{x}_{d}\right) & =k(x_{d}-x_{0})\\
m_{2}\left(\ddot{x}_{c}+\frac{m_{1}}{m_{1}+m_{2}}\ddot{x}_{d}\right) & =-k(x_{d}-x_{0})\\
(m_{1}+m_{2})\ddot{x}_{c} & =0\\
\ddot{x}_{c} & =0
\end{align*}
$$

That is a bit of work to show that the center of mass do not acceletate
in the vibrational motion! Okay.. but what about the distance of separation?
Putting Eq.([1](#eom1)) and ([2](#eom2)) into Eq.([4](#distSep)),
$$
\begin{align*}
\ddot{x}_{d} & =\ddot{x}_{2}-\ddot{x}_{1}\\
 & =-\frac{k}{m_{2}}(x_{d}-x_{0})-\frac{k}{m_{1}}(x_{d}-x_{0})\\
 & =-\frac{m_{1}+m_{2}}{m_{1}m_{2}}k(x_{d}-x_{0})\\
 & =-\frac{k}{\mu}(x_{d}-x_{0})
\end{align*}
$$
where ${\displaystyle \mu=\frac{m_{1}m_{2}}{m_{1}+m_{2}}}$ is the
effective mass of the system. The above can be made even simpler by
letting $x=x_{d}-x_{0}$ to obtain 
$$
\ddot{x}=-\frac{k}{\mu}x
$$

To obtain the potential energy of the system, we use the force-potential
relationship:

$$
\begin{align*}
F & =-\frac{dV}{dx}\\
\frac{dV}{dx} & =-\mu\ddot{x}=kx\\
V & =\frac{1}{2}kx^{2}
\end{align*}
$$
(We can set the constant of integration to zero without loss of generality.)

### A note on quantum operators

In the previous chapter, we saw that Schrödinger was inspired by the
energy conservation equation 
$$
\frac{p^{2}}{2m}+V(x)=E
$$
and arrived at the Schrödinger equation
$$
\left(-\frac{\hbar^{2}}{2m}\frac{\partial^{2}}{\partial x^{2}}+V(x)\right)\psi(x)=E\psi(x)
$$

In 3 dimensions, 
$$
\frac{\mathbf{p}^{2}}{2m}+V(x)=E
$$
where $\mathbf{p}=(p_{x},p_{y},p_{z})$, leads to 
$$
\left(-\frac{\hbar^{2}}{2m}\nabla^{2}+V(\mathbf{r})\right)\psi(\mathbf{r})=E\psi(\mathbf{r})
$$
where $\mathbf{r}=(x,y,z)$ and 
$$
\nabla^{2}=\left(\frac{\partial^{2}}{\partial x^{2}}+\frac{\partial^{2}}{\partial y^{2}}+\frac{\partial^{2}}{\partial z^{2}}\right)
$$
In spherical coordinates, 
$$
\nabla^{2}=\frac{1}{R^{2}}\frac{\partial}{\partial R}\left(R^{2}\frac{\partial}{\partial R}\right)+\frac{1}{R^{2}\sin\theta}\frac{\partial}{\partial\theta}\left(\sin\theta\frac{\partial}{\partial\theta}\right)+\frac{1}{R^{2}\sin^{2}\theta}\frac{\partial^{2}}{\partial\phi^{2}}
$$
It turns out to obtain the Schrödinger equation from classical concepts,
one can make the following conversions:
$$
\begin{align*}
x & \rightarrow x\\
p & \rightarrow-i\hbar\frac{\partial}{\partial x}\\
p^{2} & \rightarrow-\hbar^{2}\frac{\partial^{2}}{\partial x^{2}}\\
\mathbf{r} & \rightarrow\mathbf{r}\\
\mathbf{p}^{2} & \rightarrow-\hbar^{2}\nabla^{2}
\end{align*}
$$

The right-hand-side of the above conversions are known as the "operators"
in the language of quantum mechanics. For angular momentum $L$ the
operator conversions are
$$
\begin{align*}
L_{x} & \rightarrow-i\hbar\left(y\frac{\partial}{\partial z}-z\frac{\partial}{\partial y}\right)=i\hbar\left(\sin\phi\frac{\partial}{\partial\theta}+\cot\theta\cos\phi\frac{\partial}{\partial\phi}\right)\\
L_{y} & \rightarrow-i\hbar\left(z\frac{\partial}{\partial x}-x\frac{\partial}{\partial z}\right)=i\hbar\left(-\cos\phi\frac{\partial}{\partial\theta}+\cot\theta\sin\phi\frac{\partial}{\partial\phi}\right)\\
L_{z} & \rightarrow-i\hbar\left(x\frac{\partial}{\partial y}-y\frac{\partial}{\partial x}\right)=-i\hbar\frac{\partial}{\partial\phi}\\
\mathbf{L}^{2} & \rightarrow-\hbar^{2}\left[\frac{1}{\sin\theta}\frac{\partial}{\partial\theta}\left(\sin\theta\frac{\partial}{\partial\theta}\right)+\frac{1}{\sin^{2}\theta}\frac{\partial^{2}}{\partial\theta^{2}}\right]
\end{align*}
$$
For the rigid rotor, 
$$
T+V=\frac{\mathbf{L}^{2}}{2I}=E
$$
gives the SE
$$
-\frac{\hbar^{2}}{2I}\left[\frac{1}{\sin\theta}\frac{\partial}{\partial\theta}\left(\sin\theta\frac{\partial}{\partial\theta}\right)+\frac{1}{\sin^{2}\theta}\frac{\partial^{2}}{\partial\theta^{2}}\right]\psi=E\psi
$$
