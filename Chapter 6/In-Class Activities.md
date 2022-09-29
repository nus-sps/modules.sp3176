---
label: In-Class Activities
layout: default
icon: ":teacher:"
order: -10
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
## 6.10 In-Class Activities

### Activity 1

#### Lorentz transformation in the low speed limit

In the low speed limit where $v\ll c$, $\beta\approx0$ and $\gamma\approx1$. What do the time dilation (Eq [TD (3)](<Time Dilation#sixpointeight>)), length contraction (Eq [LC (5)](<Length Contraction#sixpointthirteen>)) and Lorentz transformation equations (Eq [LT (1)](<Lorentz Transformation#sixpointfourteen>)) become? Does this make intuitive sense?

---

### Activity 2

#### Minkowski space-time diagram

Let us visualise how the space-time coordinates of two inertia observers in uniform relative motion are related to each other in a space-time diagram. For simplicity, we consider two inertia frames ($S$ and $S'$) where the relative motion between them occurs only along the $x$-axis. Specifically, suppose $S'$ moves with a constant speed $v$ in the $+x$-direction relative to $S$. 

On the grid below, draw a vertical axis and label it $ct$. Draw a horizontal axis and label it $x$. This set of axes represent the inertia frame $S$. With this construction, a space-time event from the perspective of an observer in $S$ is simply a point located in the plane of the two axes. The coordinate position and coordinate time $(ct,x)$ can be read off the axes directly. Notice that position is represented on the horizontal axis while time is represented on the vertical axis. In relativity, it is conventional to represent time on the vertical axis. Moreover, the space-time diagram gives both axes the same units by scaling the vertical axis by the speed of light, $c$.

<span id="grid"></span>
![](</Resources/Chapter 6/grid2.jpg>)

Next, we represent the space-time diagram, $(ct',x')$, for frame $S'$ on the same grid. To draw the $ct'$ axis, we examine various coordinate points where $x'=0$. First, using Lorentz transformation [LT (1)](<Lorentz Transformation#sixpointfourteen>), show that $x=\gamma\beta$ and $ct=\gamma$ when \{$x'=0,ct'=1$\}.

Repeat the previous step to find the corresponding $x$ and $ct$ coordinates for \{$x'=0,ct'=2$\} and so on. Plot the points on the $(ct,x)$ graph for $\beta=0.6$. Draw a line through these points and label it as $ct'$. 

To draw the $x'$ axis, find the corresponding $x$ and $ct$ coordinates for \{$x'=1,ct'=0$\}, \{$x'=2,ct'=0$\} and so on. Plot the points on the $(ct,x)$ graph for $\beta=0.6$. Draw a line through these points and label it as $x'$.

Suppose an observer in $S$ observes an event occurring at \{$x=3\gamma,ct=4\gamma$\}. With the help of your space-time diagrams, what are the corresponding $ct'$ and $x'$ coordinates for the same event from the perspective of an observer in $S'$ when $\beta=0.6$? 

How will the $ct'$ and $x'$ axes change for higher or lower values of $\beta$ ? 

What happens if $\beta=1$?

---

### Activity 3

#### Invariance of the space-time interval
Use the Lorentz transformation equations (Eq [LT 1](<Lorentz Transformation#sixpointfourteen>)) to show the invariance of the space-time interval between two events at $(t,x,y,z)$ and $(t+dt,x+dx,y+dy,z+dz)$ when transforming from one inertia frame $S$ to another inertia frame $S'$, i.e. $ds=ds'$.

From Lorentz transformation (Eq [LT 1](<Lorentz Transformation#sixpointfourteen>)), we have 

$$
\begin{align}
cdt'=\gamma(cdt-\beta dx) \nonumber \\
dx'=\gamma\left(dx-\beta cdt\right), \nonumber 
\end{align}
$$

where $\gamma=\frac{1}{\sqrt{1-\beta^{2}}}$ and $\beta=\frac{v}{c}$.

---

### Activity 4

#### Relativity of simultaneity
Consider inertia frame $S'$ which moves at a constant speed (comparable to the speed of light) relative to inertia frame $S$. On the same Minkowski space-time diagram, sketch a pair of $(ct',x')$ axes and $(ct,x)$ axes for frames $S'$ and $S$ respectively.  Mark out 2 events on $(ct',x')$ axes that are simultaneous in frame $S'$. 

Show that two events that are simultaneous in one inertia frame is not simultaneous in another inertia frame.
