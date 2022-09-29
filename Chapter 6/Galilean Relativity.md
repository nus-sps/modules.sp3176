---
label: Galilean Relativity
layout: default
icon: ":people_holding_hands:"
order: -2
author:
  - name: Dr Lim Zhi Han
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/lim.zhihan/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/2019/06/logo_sps20.png
  - name: Koh Zhi Yong
    email: zhiyong.koh17@nus.edu.sg
    link: https://sps.nus.edu.sg/user/zhiyong.koh17/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/ultimatemember/25/profile_photo-190x190.jpg?1662811284
  - name: Gerald Kang Joon Kiat
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/joonkiat.kang17/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/ultimatemember/21/profile_photo-190x190.jpg?1662826964
date: 2022-09-25T12:00
description: "Space and Time"
---

## 6.2 Galilean Relativity

When we consider the term "relativity", it should not take too long to convince ourselves that most physical measurements are made relative to a chosen reference system. The position vector of a particle, $\textbf{r}=(x,y,z)$, means that its position vector has components $(x,y,z)$ relative to some chosen origin and a chosen set of axes. An event occurring at time $t=\text{10 s}$ means that $t$ is 10 seconds relative to a chosen origin of time, $t=\text{0 s}$. When we measure the kinetic energy of a car, it makes a difference whether the kinetic energy is measured relative to a reference frame fixed to the road or to one fixed on the car. Every one of us carries along our individual set of reference frame, relative to which physical measurements are made.

Many of the ideas on relativity are already present in classical physics. Newton's laws hold in **inertial reference frames**, any one of which moves at constant velocity to any other. 

:::quote
An **inertial reference frame** is defined to be a frame in which a free object is observed to move at a constant velocity (can be at rest) everywhere in the frame.
:::

The above definition implies that that the frame is at rest or moving with constant velocity. In other words, the frame is non-accelerating. 

Imagine, for example, playing a game of billiards in a train going at constant speed down a smooth straight track. The game will proceed exactly the same as it would if the train is at rest; you do not have to "correct" your shots for the fact that the train is moving. If you look out from the windows, from your perspective, it seems as if the environment outside is the one *moving*! Likewise, an observer outside will justifiably claim that your train is the one that is moving from his or her perspective. Furthermore, if you pulled down all the curtains, you would have no way of knowing whether the train is moving or not.

Notice, however, that you know *immediately* if the train speeds up, or slows down, or rounds a corner, or goes over a bump. The tell tale signs are the billiard balls moving in curved trajectories and yourself feeling a lurch. The laws of mechanics, therefore, behave quite differently when the frame is accelerating.

:::quote
The laws of mechanics remain the same for observers in inertial frames that are in uniform motion (can be at rest) with respect to one another.
:::

The above is known as the **Galilean principle of relativity**. In its application to classical physics, the principle of relativity is nothing new and makes intuitive sense, as first stated by Galileo Galilei (1564-1642).

### 6.2.1 Galilean Transformation

Consider two inertial frames, $S$ and $S'$, that are aligned in the same way: $x'$ axis is parallel to $x$ axis, $y'$ axis parallel to $y$ and $z'$ axis parallel to $z$. Suppose that $S'$ moves at a constant velocity of $\textbf{v}$ along the $x$-axis with respect to $S$. It was a fundamental assumption of classical physics that there is a single universal time $t$. Therefore, if observers in $S$ and $S'$ agree to synchronise their clocks (and use the same unit of time), then $t=t'$. Finally, we can choose origins $O$ and $O'$ such that they coincide at $t=t'=0$. This is illustrated in the figure below.

<span id="Galilean_Transformation_Diagram"></span>
![Figure 1. Two inertial frames, $S$ and $S'$ whose spatial coordinate axes are aligned and spatial origins coincide at $t=t'=0$. $S'$ moves in the $+x$ direction relative to $S$ with a speed $v$.](</Resources/Chapter 6/Galilean_Transformation_Diagram.png>)

Consider some event $P$. As measured by observers in $S$, this event occurs at $\textbf{r}=(x,y,z)$ and at time $t$. As measured by observers in $S'$, the same event occurs at $\textbf{r}'=(x',y',z')$ and at time $t'$.

We can establish a mathematical relationship between $(t,x,y,z)$ and $(t',x',y',z')$ just by inspecting Figure [1](#Galilean_Transformation_Diagram).

<span id="sixpointone"></span>
$$
\begin{align}
x' &= x - vt \nonumber  \\
y' &= y \nonumber \\
z' &= z \nonumber \\
t' &= t 
\end{align}
$$

These four equations are known collectively as the **Galilean transformation**. They are the mathematical expression of the classical ideas of space and time. 

The Galilean transformation relates the coordinates measured in two inertial frames arranged with corresponding axes parallel and with relative velocity along the $x$-axis. This is not the most general configuration. For example, if the relative velocity $\textbf{v}$ is in an arbitrary direction, we can rewrite [6.1](#sixpointone) compactly in the form of vectors as 

<span id="sixpointtwo"></span>
$$
\begin{align}
\textbf{r}' &= \textbf{r} - \textbf{v}t \nonumber\\
t'&=t
\end{align}
$$

With [Eq. 2](#sixpointtwo), we can relate the velocities of an object, as measured in the two inertial frames. If $\textbf{u}=\frac{d\textbf{r}}{dt}$ is the velocity of an object measured in $S$ and $\textbf{u}'=\frac{d\textbf{r}'}{dt'}$ is the velocity of the object measured in $S'$, then by differentiating [Eq. 2](#sixpointtwo), we have

<span id="sixpointthree"></span>
$$
\begin{align}
\frac{d\textbf{r}'}{dt'} &= \frac{d\textbf{r}}{dt'} - \textbf{v}\frac{dt}{dt'} \nonumber   \\
\frac{d\textbf{r}'}{dt'} &= \frac{dt}{dt'}\frac{d\textbf{r}}{dt} - \textbf{v}\nonumber \\
\frac{d\textbf{r}'}{dt'} &= \frac{d\textbf{r}}{dt} - \textbf{v}\nonumber \\
\textbf{u}' &= \textbf{u} - \textbf{v}
\end{align}
$$

This is the non-relativistic velocity addition formula. According to the ideas of non-relativistic physics, relative velocities add (and subtract) according to the rules of vector arithmetic.