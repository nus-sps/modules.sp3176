---
label: Pre-Lecture Homework
layout: default
icon: ":spiral_note_pad:"
order: -1
author:
  - name: Dr Lim Zhi Han
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/lim.zhihan/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/2019/06/logo_sps20.png
date: 2022-10-09T12:00
description: "The Expanding Universe"
---

## 7.1 Pre-Lecture Homework

<span id="Hubble's-data"></span>

### 7.1.1 Hubble's data

In the 1920-1930s, Edwin Hubble and Milton Humason collated and measured
the distances and velocities of galaxies. Below is a table comprising
some of their early data. Analyse the data and deduce a relationship
between velocities and distance (if you have not already done so in
previous IS). 

![](</Resources/Chapter 7/Hubble_data.png>)

### 7.1.2 The Cosmological Principle

The cosmological principle states that the Universe is **homogeneous**
and **isotropic**. 

What do the words in bold mean?

Reason that the cosmological principle implies that any observer looking
at the motion of galaxies will find the radial velocities proportional
to the distance between her and the galaxy.

### 7.1.3 Pythagoras theorem in spherical coordinates

Some intense mathy stuffs below. Just read, no need to work out. 

Spherical coordinates are used to specify points on the sphere and
are related to the Cartesian coordinates by 

<span id="Cart2Spherical"></span>
$$
\begin{align}
x & =R\sin\theta\cos\phi\nonumber \\
y & =R\sin\theta\sin\phi\\
z & =R\cos\theta\nonumber 
\end{align}
$$

The corresponding differentials are 

<span id="differentialsSpherical"></span>

$$
\begin{align}
dx & =\sin\theta\cos\phi dR+R\cos\theta\cos\phi d\theta-R\sin\theta\sin\phi d\phi\nonumber \\
dy & =\sin\theta\sin\phi dR+R\cos\theta\sin\phi d\theta+R\sin\theta\cos\phi d\phi\\
dz & =\cos\theta dR-R\sin\theta d\theta\nonumber 
\end{align}
$$

The infinitesimal length between two spatial points is given by 

$$
(dl)^{2}=(dx)^{2}+(dy)^{2}+(dz)^{2}
$$

To write this in spherical coordinates, we'll use Eq. [2](#differentialsSpherical),
and some elbow grease.

$$
\begin{align*}
(dl)^{2} & =(\sin\theta\cos\phi dR+R\cos\theta\cos\phi d\theta-R\sin\theta\sin\phi d\phi)^{2}\\
 & \phantom{=}+(\sin\theta\sin\phi dR+R\cos\theta\sin\phi d\theta+R\sin\theta\cos\phi d\phi)^{2}\\
 & \phantom{=}+(\cos\theta dR-R\sin\theta d\theta)^{2}\\
 & =(dR)^{2}(\sin^{2}\theta\cos^{2}\phi+\sin^{2}\theta\sin^{2}\phi+\cos^{2}\theta)\\
 & \phantom{=}+(d\theta)^{2}(R^{2}\cos^{2}\theta\cos^{2}\phi+R^{2}\cos^{2}\theta\sin^{2}\phi+R^{2}\sin^{2}\theta)\\
 & \phantom{=}+(d\phi)^{2}(R^{2}\sin^{2}\theta\sin^{2}\phi+R^{2}\sin^{2}\theta\cos^{2}\phi)\\
 & \phantom{=}+2dRd\theta(R\sin\theta\cos^{2}\phi\cos\theta+R\sin\theta\sin^{2}\phi\cos\theta-R\sin\theta\cos\theta)\\
 & \phantom{=}+2dRd\phi(-R\sin^{2}\theta\cos\phi\sin\phi+R\sin^{2}\theta\sin\phi\cos\phi)\\
 & \phantom{=}+2d\theta d\phi(-R^{2}\cos\theta\cos\phi\sin\theta\sin\phi+R^{2}\cos\theta\sin\phi\sin\theta\cos\phi)\\
 & =(dR)^{2}+R^{2}(d\theta)^{2}+R^{2}\sin^{2}\theta(d\phi)^{2}
\end{align*}
$$

Yeah finally done! This equation will be used later. 

Oh one note, it is really troublesome to write the parenthesis for
the squares of the differentials. From this point onward, we will
not write them. Hence we have 

<span id="spaceMetric"></span>
$$
\begin{align}
dl^{2} & =dx^{2}+dy^{2}+dz^{2}\nonumber \\
 & =dR^{2}+R^{2}d\theta^{2}+R^{2}\sin^{2}\theta d\phi^{2}
\end{align}
$$