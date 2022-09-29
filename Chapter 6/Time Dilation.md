---
label: Time Dilation
layout: default
icon: ":mantelpiece_clock:"
order: -6
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

## 6.6 Time Dilation: An Informal Derivation

The second postulate of special relativity forces us to abandon the classical notion of a single universal time. Instead, we shall see that the time of any one event, as measured in two different inertia frames travelling relative to each other, is generally different. 

Let us return to the thought experiment in Section 6.1.3. Suppose you bring the 'light-clock' with you onto a train carriage and the train moves at constant speed, while your friend watches the train (with you and the 'light-clock') moves. Going back to our familiar two frames, we have $S$ (your friend) anchored to the ground and $S'$ (you) travelling at speed $v$ relative to $S$. For simplicity, let us assume the train moves in the $+x$-direction.

<span id="LightClock"></span>

![Figure 1. (a): The experiment as seen in $S'$ (by you). The photon travels straight up and down, and the "tick" and "tock" occur at the same place. (b): As seen in $S$ (by your friend), the "tick" and "tock" are separated by the distance $v\Delta t$. Note that in $S$, your friend will require another person to help time the two events, since "tick" and "tock" occur at two different locations.](</Resources/Chapter 6/LightClock.png>)

Let $\Delta t'$ be the time you record for a "tick-tock" to happen in $S'$.

<span id="sixpointsix"></span>
$$
\begin{align}
\Delta t'=\frac{2L}{c}
\end{align}
$$

Let $\Delta t$ be the time your friend records for a "tick-tock" to happen in $S$. Geometrically, from [Figure 1](#LightClock):

<span id="sixpointseven"></span>
$$
\begin{align}
\Delta t=\frac{\sqrt{(2L)^{2}+(v\Delta t)^{2}}}{c}
\end{align}
$$

Notice that this is where we use the second postulate, that $c$ is the invariant speed of light as observed in $S$ and $S'$. We now make $c$ the subject in both Equations [1](#sixpointsix) and [2](#sixpointseven) before equating them together.

<span id="sixpointeight"></span>
$$
\begin{align}
c=\frac{2L}{\Delta t'} & =\frac{\sqrt{(2L)^{2}+(v\Delta t)^{2}}}{\Delta t}\nonumber \\
\left(\frac{2L}{\Delta t'}\Delta t\right)^{2} & =4L^{2}+v^{2}(\Delta t)^{2}\nonumber \\
(\Delta t)^{2}\left(\frac{4L^{2}}{(\Delta t')^{2}}-v^{2}\right) & =4L^{2}\nonumber \\
(\Delta t)^{2} & =\frac{4L^{2}(\Delta t')^{2}}{4L^{2}-v^{2}(\Delta t')^{2}}\nonumber \\
 & =\frac{(\Delta t')^{2}}{1-v^{2}/c^{2}}\nonumber \\
\Delta t & =\gamma\Delta t'
\end{align}
$$

where $\gamma=1/\sqrt{1-v^{2}/c^{2}}$. 

For $v<c$, $\gamma>1$ and $\Delta t' < \Delta t$. In other words, your friend that measures $\Delta t$ sees a slower clock than you who measures $\Delta t'$!
