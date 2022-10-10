---
label: Expanding Universe in the Spacetime Framework
layout: default
icon: ":telescope:"
order: -4
author:
  - name: Dr Lim Zhi Han
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/lim.zhihan/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/2019/06/logo_sps20.png
date: 2022-10-09T12:00
description: "The Expanding Universe"
---

## 7.4 Expanding Universe in the Spacetime framework 

Go to [Activity 1](<In-Class Activities#Activity-1>).

### 7.4.1 Flat space (no curvature)

Suppose the space is flat or Euclidean, the metric of space is given
by 
<span id="flat3D"></span>
$$
\begin{equation}
dl^{2}=dx^{2}+dy^{2}+dz^{2}
\end{equation}
$$

In a homogeneous, isotropic, size-changing Universe, one will see
the galaxies moving radially away/towards us equally in all directions.
It is thus apt to express the metric in spherical coordinates $(R,\theta,\phi)$:

<span id="flat3Dspherical"></span>
$$
\begin{equation}
dl^{2}=dR^{2}+R^{2}d\theta^{2}+R^{2}\sin^{2}\theta d\phi^{2}
\end{equation}
$$

Looks familiar? 

We are now going to do something that requires your brain to stretch
a bit.. 

First, we allow $R$ to vary with time, i.e. $R=R(t)$. This will
mean that if we were to measure the distance between 2 points ($\Delta R$),
the value will depend on *when* you measure. 

Since the space is homogeneous and isotropic, the change in distance
is the same anywhere and in any directions. This allows us to think
of the change of $\Delta R$ to be due to the scale (size) of the
entire system that changes. We then define a time-dependent scale
factor $S(t)$ and a time-independent "comoving" coordinate $r$
where 
<span id="comovingScaleFactor"></span>
$$
\begin{equation}
R(t)=r\,S(t)
\end{equation}
$$

Note that $r,\theta$ and $\phi$ are **not** functions of time.
This means that if we use $(r,\theta,\phi)$ to label positions of
objects, then these coordinate points will not change in time even
if the space expands or contract. Using Eq.([3](#comovingScaleFactor)),
we allow the time dependency of space to be encoded by the scale factor
$S(t)$. For example, $S(t_{2})>S(t_{1})$ will mean that distance
measured between two objects at $t_{2}$ will be larger than that
in $t_{1}$. 

!!! Try it Yourself!
In the space below, illustrate the above idea
by draw 2 diagrams, one at time $t_{1}$ and the other at $t_{2}$.
Each diagram should contain 2 points P and Q. P has the same $(r,\theta,\phi)$
coordinates in $t_{1}$ and $t_{2}$. Similarly for Q.
!!!

Putting Eq.([3](#comovingScaleFactor)) into Eq.([2](#flat3Dspherical)),
we obtain
<span id="flatFLRW"></span>
$$
\begin{equation}
dl^{2}=S(t)^{2}\left(dr^{2}+r^{2}d\theta^{2}+r^{2}\sin^{2}\theta d\phi^{2}\right)
\end{equation}
$$

Eq.([4](#flatFLRW)) is the space metric for flat space, written
in spherical coordinates.

Space need not be flat.

If one allows space to be curved, yet maintaining universal homogeneity,
one may have (i) flat (zero curvature), (ii) spherical (constant positive
curvature) or (ii) hyperbolic (constant negative curvature) space.

---

### 7.4.2 Spherical space (positive curvature)

A 2-sphere is the 2D surface of a 3D ball. It is defined by the equation
$$
x^{2}+y^{2}+z^{2}=R^{2}
$$
where $R$ is the radius of the ball/sphere. The metric for the 2
sphere is 
$$
ds^{2}=dR^{2}+R^{2}d\theta^{2}+R^{2}\sin^{2}\theta d\phi^{2}=R^{2}d\theta^{2}+R^{2}\sin^{2}\theta d\phi^{2}
$$
Note that $dR=0$ since $R$ is a constant here. 

Now extend your imagination to think of the surface of a 4-dimensional
ball. This surface is a curved 3D space which we call the **3-sphere**.
Being one dimension higher than the 2-sphere, the equation for the
3-sphere is 
<span id="3-sphere"></span>
$$
\begin{equation}
w^{2}+x^{2}+y^{2}+z^{2}=S^{2}
\end{equation}
$$

where $S$ is a constant in space (but not a constant in time). Let
$R^{2}=x^{2}+y^{2}+z^{2}$. In this case $R$ is not a constant. 

To find the space metric, first we work out the differentials
$$
\begin{align*}
w^{2} & =S^{2}-R^{2}\\
2wdw & =0-2RdR\\
w^{2}dw^{2} & =R^{2}dR^{2}\\
dw^{2} & =\frac{R^{2}}{S^{2}-R^{2}}dR^{2}
\end{align*}
$$

The metric of the 3-sphere is 
<span id="metric_3_sphere1"></span>
<span id="metric_3_sphere2"></span>
$$
\begin{align}
dl^{2} & =dw^{2}+dx^{2}+dy^{2}+dz^{2}\nonumber \\
 & =\frac{R^{2}dR^{2}}{S^{2}-R^{2}}+dR^{2}+R^{2}d\theta^{2}+R^{2}\sin^{2}\theta d\phi^{2}\\
 & =S^{2}\left(\frac{dr^{2}}{1-r^{2}}+r^{2}d\theta^{2}+r^{2}\sin^{2}\theta d\phi^{2}\right)
\end{align}
$$

where in the last step we had applied Eq.([3](#comovingScaleFactor))
on Eq.([6](#metric_3_sphere1)) to obtain Eq.([7](#metric_3_sphere2)).

---

### 7.4.3 Hyperbolic space (negative curvature)

The space of an isotropic and homogeneous negatively curved space
takes on a surface of a hyperboloid, whose equation is given by 
$$
w^{2}-x^{2}-y^{2}-z^{2}=S^{2}
$$
The metric of the 3-hyperboloid is 
$$
dl^{2}=-dw^{2}+dx^{2}+dy^{2}+dz^{2}
$$
Using a similar treatment (as we did for the spherical case), the
metric for a hyperbolic space is
<span id="metric_3_hyperbola"></span>
$$
\begin{equation}
dl^{2}=S^{2}\left(\frac{dr^{2}}{1+r^{2}}+r^{2}d\theta^{2}+r^{2}\sin^{2}\theta d\phi^{2}\right)
\end{equation}
$$

!!! Try it Yourself!
Derive Eq.([8](#metric_3_hyperbola)).
!!!

---

### 7.4.4 Friedmann-Lemaitre-Robertson-Walker (FLRW) metric

Putting the above altogether, allowing $S$ to change with time, and
adding the time component, the spacetime metric for an expanding Universe
is 

<span id="FLRWfull"></span>
$$
\begin{equation}
ds^{2}=-c^{2}dt^{2}+S(t)^{2}\left(\frac{dr^{2}}{1-kr^{2}}+r^{2}d\theta^{2}+r^{2}\sin^{2}\theta d\phi^{2}\right)
\end{equation}
$$
where 
$$
k=\begin{cases}
\begin{array}{c}
+1\\
0\\
-1
\end{array} & \begin{array}{c}
,\;\text{positively curved space}\\
,\;\text{flat space}\\
,\;\text{negatively curved space}
\end{array}\end{cases}
$$

Eq. ([9](#FLRWfull}) is known as the Friedmann-Lemaitre-Robertson-Walker
(FLRW) metric. It is the spacetime metric of a homogeneous and isotropic
(expanding) Universe.

### 7.4.5 The Cosmological Redshift

Consider light from a galaxy situated at a $r_{1}$. Let us narrow
down to see just two photons, emitted one after the other at times
$t_{1}$ and $t_{1}+1/f_{1}$, with $f_{1}$ being the frequency of
the photon emitted. Assume the photons travel freely across the intergalactic
distance to us, reaching our detectors at times $t_{0}$ and $t_{0}+1/f_{0}$.
Photons propagating in an isotropic and homogeneous Universe are described
by 
$$
\begin{equation}
ds^{2}=c^{2}dt^{2}-S(t)^{2}\frac{dr^{2}}{1-kr^{2}}=0
\end{equation}
$$
where $S(t)$ is the cosmological scale factor characterizing the
size of the Universe as it expands. For the first and the second photon,
we have respectively
$$
\begin{equation}
c\int_{t_{1}}^{t_{0}}\frac{dt}{S(t)}=\int_{0}^{r_{1}}\frac{dr}{\sqrt{1-kr^{2}}}
\end{equation}
$$
 and
$$
\begin{equation}
c\int_{t_{1}+1/f_{1}}^{t_{0}+1/f_{0}}\frac{dt}{S(t)}=\int_{0}^{r_{1}}\frac{dr}{\sqrt{1-kr^{2}}}.
\end{equation}
$$

Since the RHS of the equations are the same, we can equate the LHS
of both equations, 

$$
\begin{align}
\int_{t_{1}}^{t_{0}}\frac{dt}{S(t)} & = \int_{t_{1}+1/f_{1}}^{t_{0}+1/f_{0}}\frac{dt}{S(t)}\nonumber \\
 & = \int_{t_{1}+1/f_{1}}^{t_{0}}\frac{dt}{S(t)}+\int_{t_{0}}^{t_{0}+1/f_{0}}\frac{dt}{S(t)}\nonumber \\
 & = \int_{t_{1}}^{t_{0}}\frac{dt}{S(t)}-\int_{t_{1}}^{t_{1}+1/f_{1}}\frac{dt}{S(t)}+\int_{t_{0}}^{t_{0}+1/f_{0}}\frac{dt}{S(t)}\nonumber \\
\int_{t_{1}}^{t_{1}+1/f_{1}}\frac{dt}{S(t)} & = \int_{t_{0}}^{t_{0}+1/f_{0}}\frac{dt}{S(t)}
\end{align}
$$

The time interval(s) between the first and second photons emitted
(and received) is very short and it will be reasonable to assume that
the Universe do not expand much in that short time. We can therefore
assume $S$ to be constant within the limits of integration and take
it out of the integration sign(s). This gives
$$
\begin{equation}
\frac{1}{S(t_{1})}\frac{1}{f_{1}}=\frac{1}{S(t_{0})}\frac{1}{f_{0}}
\end{equation}
$$
 Finally we define the cosmological redshift $z$ by 
 <span id="cosmo-redshift-def"></span>  
$$
\begin{equation}
1+z=\frac{\lambda_{0}}{\lambda_{1}}=\frac{f_{1}}{f_{0}}=\frac{S(t_{0})}{S(t_{1})}
\end{equation}
$$