---
label: Length Contraction
layout: default
icon: ":triangular_ruler:"
order: -7
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

## 6.7 Length Contraction: An Informal Derivation

The postulates of relativity have led us to conclude that time is relative - the time between two events is different when measured in different inertia frames. This, in turn, implies that the length of an object is likewise dependent on the frame in which it is measured.

To see this, imagine now you (still on the train) set up the "light-clock" such that the photon source is at one end of the train carriage while the mirror is at the other end, such that a photon can be sent down and back. (Figure [1](#LengthContraction) a)  

<span id="LengthContraction"></span>
![Figure 1. (a): The experiment as seen in $S'$ (by you). The photon travels the length of the train, and the "tick" and "tock" occur at the same place. (b): The photon as seen in $S$ (by your friend). The "tick" and "tock" occur at different locations. $\Delta t_{1}$ is the time taken for the photon to reach the front end while $\Delta t_{2}$ is the return time.](</Resources/Chapter 6/LengthContraction.png>)


Question: How long does the photon takes to complete one round trip? To you, the answer is 

<span id="sixpointnine"></span>
$$
\begin{align}
\Delta t'=\frac{2\Delta L'}{c},
\end{align}
$$

where $\Delta L'$ is the length of the train as measured by you in $S'$. However, to your friend, the situation is a little more complicated since the train is moving (Figure [1](#LengthContraction) b). Let $\Delta t_{1}$ be the time taken for the photon to reach the front end while $\Delta t_{2}$ be the return time. Then geometrically, from Figure [1](#LengthContraction)b, we have

<span id="sixpointten"></span>
$$
\begin{align}
\Delta t_{1}=\frac{\Delta L + v\Delta t_{1}}{c} \nonumber \\
\Delta t_{2}=\frac{\Delta L - v\Delta t_{2}}{c},
\end{align}
$$

where $\Delta L$ is the length of the train as measured by your friend in $S$. Note that once again, we have used the second postulate. Solving for $\Delta t_{1}$ and $\Delta t_{2}$, we have

<span id="sixpointeleven"></span>
$$
\begin{align}
\Delta t_{1}=\frac{\Delta L}{c - v} \nonumber \\
\Delta t_{2}=\frac{\Delta L}{c + v}.
\end{align}
$$

So, your friend will measure the round-trip time as

<span id="sixpointtwelve"></span>
$$
\begin{align}
\Delta t = \Delta t_{1} + \Delta t_{2} = 2\frac{\Delta L}{c}\frac{1}{1-v^{2}/c^{2}}.
\end{align}
$$

Finally, recoginising that $\Delta t$ and $\Delta t'$ are related through time dilation [TD (3)](<Time Dilation#sixpointeight>) and using Equation [LC (1)](<Time Dilation#sixpointnine>), we arrive at

<span id="sixpointthirteen"></span>
$$
\begin{align}
\Delta L' = \frac{1}{\sqrt{1-v^{2}/c^{2}}}\Delta L = \gamma \Delta L. 
\end{align}
$$

For $v<c$, $\gamma>1$ and $\Delta L < \Delta L'$. In other words, your friend measures a shorter train![^1]

[^1]: Dimensions perpendicular to the velocity are not length contracted.