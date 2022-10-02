---
label: Lorentz Transformation
layout: default
icon: ":arrows_clockwise:"
order: -8
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
## 6.8 Lorentz Transformation

In Sections 6.6 and 6.7, we showed the relativity of time and space between different observers in uniform relative motion. According to the classical notions of time and space, the Galilean transformation equations [GR (1)](<Galilean Relativity#sixpointone>) between coordinates in two inertia frames $S$ and $S'$ that we saw in Section 6.2.1 cannot be the actual relations.

Instead, the general mathematical relations between coordinates in two inertia frames $S$ and $S'$ moving with constant relative velocity **v** along the $x$-axis are given by the **Lorentz transformation** equations

<span id="sixpointfourteen"></span> 
$$
\begin{align}
ct'&= \gamma(ct-\beta x)\nonumber \\
x' &=  \gamma(x-\beta ct)\nonumber\\
y' &=  y\nonumber \\
z' &=  z
\end{align}
$$

where ${\gamma=\frac{1}{\sqrt{1-\beta^{2}}}}$, $\beta=\frac{v}{c}$,
$v$ is the relative speed between the two observers, and $c$
is the speed of light. Notice that there is now a transformation for the time coordinate, unlike Galilean transformation. Also, $y'=y$ and $z'=z$ since the relative motion between $S$ and $S'$ is along the $x$-axis. The equations can be inverted to obtain the coordinates $(t,x,y,z)$ in terms of $(t',x',y',z')$, giving the **inverse Lorentz transformation**.

<span id="sixpointfifteen"></span>
$$
\begin{align}
ct &= \gamma(ct'+\beta x')\nonumber \\
x &=  \gamma(x'+\beta ct')\nonumber\\
y &=  y'\nonumber \\
z &=  z'
\end{align}
$$

The Lorentz transformation equations expresses all the properties of space and time that follow from the postulates of special relativity. Using it, one can calculate all of the kinematic relations between measurements made in different inertia frames. Go to [Activity 1](<In-Class Activities#Activity-1>).

### 6.8.1 Minkowski Space-Time Diagram
Up to now, we have been representing space-time events relative to the spatial axes of inertia observers in uniform relative motion, while representing time by drawing the axes at different positions, with the set of axes remaining fixed being the coordinate system of the observer from whose perspective we are observing the event.

In this section, we shall represent space-time events in a more efficient and useful (though perhaps more abstract) manner through the use of **Minkowski space-time diagrams**, proposed by the German mathematician Hermann Minkowski (1864-1909). Go to [Activity 2](<In-Class Activities#Activity-2>).

A space-time diagram easily allows us to visualise a sequence of events. Suppose we track a flashing beacon as it moves along the  $x$-axis. Each flash records a space-time event with the position it is located and the time of the flash, so we get a string of several points on the space-time diagram. If the flashing frequency is increased to infinity, then the space-time points form a continuous curve that tracks the space-time history of the moving object. Such a curve is known as a **worldline**.

---

### 6.8.2 Invariance of Space-time Interval
A set of coordinate transformations - such as the set of rotations in two or three dimensional space - can often be characterised by quantities that remain unchanged, or remain invariant after the transformation. 

Consider two points in a two-dimensional space. Let one of the points be located at $(x,y)$ while the other an infinitesimal distance from it, at $(x+dx,y+dy)$. This infinitesimal distance, $ds$, is therefore given by the Pythagoras Theorem in two dimensions,

<span id="sixpointsixteen"></span>
$$
\begin{align}
(ds)^{2}=(dx)^{2}+(dy)^{2}.
\end{align}
$$

What happens if we perform a rotation of the coordinate axes in this two dimensional space while keeping the two points fixed? Well, the pair of coordinates of each point changes with respect to the transformed axes. However, the quantity $ds$ remains unchanged. That is, the infinitesimal distance between the two points remains unchanged even after the rotation! 

We can see this idea easily applies to the three dimensional space. Consider two points located infinitesimally apart in three dimensional space with coordinates $(x,y,z)$ and $(x+dx,y+dy,z+dz)$. Using Pythagoras Theorem in three dimensions, the infinitesimal distance between them is 

<span id="sixpointseventeen"></span>
$$
\begin{align}
(ds)^{2}=(dx)^{2}+(dy)^{2}+(dz)^{2}.
\end{align} 
$$

Like its two dimensional counterpart, the infinitesimal distance $ds$ between the two points in three dimension remains unchanged even after we arbitrarily rotate the three coordinate axes. Now, here's the catch. Lorentz transformations equations ([1](#sixpointfourteen) and [2](#sixpointfifteen)) describe a four dimensional "rotation" between two inertia frames by transforming the space-time coordinates of an event in one frame $(t,x,y,z)$ to that of another frame $(t',x',y',z')$. 

Motivated from its two dimensional and three dimensional counterparts, we can therefore define the four dimensional infinitesimal "distance" between two events at $(t,x,y,z)$ and $(t+dt,x+dx,y+dy,z+dz)$ as observed in an inertia frame $S$,

<span id="sixpointeighteen"></span>
$$
\begin{align}
(ds)^{2}=-(cdt)^{2}+(dx)^{2}+(dy)^{2}+(dz)^{2},
\end{align}
$$

such that this "distance" remains unchanged even after we apply Lorentz transformation. This quantity is known as the **space-time interval**. Note that it is the simply the extension of Pythagoras Theorem from three dimensions to four dimensions, with the exception of the negative sign in the first term. We shall see its importance in the [Activity 3](<In-Class Activities#Activity-3>) and the subsequent section. It is because of this negative sign that Lorentz transformations of space-time is not exactly the same as rotations of coordinate axes in ordinary space.  

In another inertia frame $S'$ in relative motion with respect to $S$, the space-time interval between the same two events is given by

<span id="sixpointnineteen"></span>
$$
\begin{align}
(ds')^{2}=-(cdt')^{2}+(dx')^{2}+(dy')^{2}+(dz')^{2}
\end{align}
$$

Go to [Activity 3](<In-Class Activities#Activity-3>).

---

### 6.8.3 Invariance of the speed of light from space-time interval

The space-time interval is essentially a mathematical construct. We are interested to know how the invariance of spacetime interval translates to something physical, such as speed.

Consider an object in an inertia frame $S$ moving in the $x$-direction. An observer in this frame will measure that the speed of the object to be $\dfrac{dx}{dt}$. Since the object only moves in the $x$-direction, $dy'=0$ and $dz'=0$. Therefore, in an inertia frame $S$, the space-time interval of the object is given by 

<span id="sixpointtwenty"></span>
$$
\begin{align}
(ds)^{2} & =-(cdt)^{2}+(dx)^{2} \nonumber \\
 & =(dt)^{2}\left(-c^{2}+\left(\frac{dx}{dt}\right)^{2}\right).
\end{align}
$$

Suppose an observer in $S$ a photon travelling in $x$-direction with speed $\dfrac{dx}{dt}=c$. Then

<span id="sixpointtwentyone"></span>
$$
\begin{align}
(ds)^{2}=(dt)^{2}\left(-c^{2}+c^{2}\right)=0. 
\end{align}
$$

Consider an observer in another inertia frame $S'$ that is in uniform relative motion to $S$. By the invariance of space-time interval

<span id="sixpointtwentytwo"></span>
$$
\begin{align}
(ds')^{2}=(ds)^{2}=0 \nonumber\\
(ds')^{2}=-(cdt')^{2}+(dx')^{2} & =0\nonumber\\
\left(\frac{dx'}{dt'}\right)^{2} & =c^{2}\nonumber\\
\frac{dx'}{dt'} & =c
\end{align}
$$

Therefore, the speed of light is invariant between two inertia frames that are in uniform relative motion. This provides the mathematical framework for the second postulate of special relativity.

We shall see an alternative method of mathematically showing the second postulate under [Discussion Questions](<Discussion Questions>).

### 6.8.4 The relativity of simultaneity

Let us go back to the thought experiment with you being on the train that is moving at constant speed and your friend being the ground observer. Imagine now you set up your photon source (i.e. light clock) in the very center of the train. Your "light clock" now emits two photons at the same time, one in a direction towards the front end of the train while the other in a direction towards the back end of the train. Because your "light clock" is equidistant from the two ends, you will observe that the photon reaches the front end at the same instant as the other photon reaches the back end. The two events: (a) photon reaches the front end (and maybe a buzzer goes off) and (b) the other photon reaches the back end (another buzzer sounds) occur *simultaneously*. 

However, to your friend on the ground, these same two events are *not* simultaneous. For as the two photons travel out from the "light clock" (going at speed $c$ according to the second postulate), the train itself is moving forward, so the photon going to the back end need only travel a shorter distance compared to the other photon going forward. As far as your friend is concerned, event (b) happens *before* event (a).

:::quote
Two events that are simultaneous in one inertia frame are not, in general, simultaneous in another inertia frame.
:::

Now that we have seen the relativity of time and length between observers in two inertia frames (Sections [6.6](<Time Dilation>) and [6.7](<Length Contraction>)), this should not be too surprising of a result. Naturally, your train has to be going awfully fast before the discrepancy becomes detectable.

Go to [Activity 4](<In-Class Activities#Activity-4>).

### 6.8.5 Time dilation (Re-visited)
We derived time dilation equation [TD (3)](<Time Dilation#sixpointeight>) using a hypothetical
clock and geometrical methods in Section [6.6](<Time Dilation>). We shall now re-derive
the same results using Lorentz transformation (Eq. [1](#sixpointfourteen) and [2](#sixpointfifteen)).

Consider two inertia frames $S$ and $S'$, with $S'$ moving with constant velocity of **v** along the $x$-axis with respect to $S$. Imagine a light bulb on a table in front of an observer in frame $S'$. The light
bulb is stationary with respect to frame $S'$. Let Event 1 be the event where the bulb is switched on and Event 2 be the later event where it is switched off.  

$$
\text{Time between Events 1 and 2 as measured by an observer in $S'$ }=t_{2}'-t_{1}'=\Delta t'
$$

Since the light bulb is stationary with respect to $S'$, we fixed the
position of it, say at $x' = a$, for both $t'_{1}$ and $t'_{2}$. Then, from the inverse Lorentz transformation equations [2](#sixpointfifteen),

<span id="sixpointtwentythree"></span>
$$
\begin{align}
ct_{1} & =\gamma(ct_{1}'+\beta a) \nonumber\\
ct_{2} & =\gamma(ct_{2}'+\beta a).
\end{align}
$$

Subtracting the first equation from the second, 

<span id="sixpointtwentyfour"></span>
$$
\begin{align}
c(t_{2}-t_{1}) & =\gamma(ct_{2}'-ct_{1}') \nonumber\\
t_{2}-t_{1} & =\gamma\Delta t'.
\end{align}
$$

Letting the time between the events measured by an observer in $S$ be $\Delta t = t_{2}-t_{1}$, we arrived at $\Delta t = \gamma\Delta t'$.

### 6.8.6 Length contraction (Re-visited)
Similarly, we can re-derive
the length contraction equation [LC (5)](<Length Contraction#sixpointthirteen>) in Section 6.7 using Lorentz transformation ([1](#sixpointfourteen) and [2](#sixpointfifteen)). Consider now a rod that is stationary with respect to an observer in frame $S$. Let the left and right ends of the rod be located at coordinates $x_{1}'$ and $x_{2}'$ respectively, according to $S'$. 

$$
\text{ Length of rod measured by an observer in $S'$} =x_{2}'-x_{1}'= \Delta L'
$$

Now let's put ourselves in the shoes of an observer in $S$. Since the rod is stationary with respect to $S'$, the rod will be moving at speed $v$ in the $x$-direction according to an observer in $S$. How should he measure the length of the moving rod? Most logically, he would subtract the positions of the two ends at *one instant of his time*! Say, at the instant $t = a$, an observer in $S$ observes the left and right ends to be at $x_{1}$ and $x_{2}$ respectively. Then, from Lorentz transformation equations [1](#sixpointfourteen),

<span id="sixpointtwentyfive"></span>
$$
\begin{align}
x_{1}' & =\gamma(x_{1}-\beta ca) \nonumber\\
x_{2}' & =\gamma(x_{2}-\beta ca).
\end{align}
$$
Subtracting the first equation from the second, 

<span id="sixpointtwentysix"></span>
$$
\begin{align}
x_{2}'-x_{1}' &= \gamma(x_{2}-x_{1}) \nonumber\\
\Delta L' &= \gamma(x_{2}-x_{1}).
\end{align}
$$

Letting the length of the rod as measured by an observer in $S$ to be $\Delta L = x_{2}-x_{1}$, we finally arrived at $\Delta L' = \gamma\Delta L$.