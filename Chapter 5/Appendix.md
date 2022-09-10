---
label: Appendix
layout: default
icon: ":abacus:"
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
date: 2022-09-10T12:00
description: "Through The Looking Glass"
---
## 5.-1 Appendix

## Determination of Astronomical Unit using the Transit of Venus

![(a) Schematic of the transit of Venus as viewed from two different
locations on Earth. (b) Trigonometric parallax applied to determine
the astronomical unit. (c) Venus in transit on 6 June 2012, 12:08pm.
Venus appeared as a small silhouette disc moving across the Sun. This
picture was taken with a digital camera attached to a 104mm Newtonian
telescope at the NUS multi-purpose field.](</Resources/Chapter 5/TransitOfVenus.PNG>)

The figure above shows the schematic of the transit of Venus as observed
from two different locations on Earth. All lengths depicted on the
figure are measured in terms of visual angles and equivalently in
terms of A.U. since they are lengths on the Sun's disk
as observed from Earth. Suppose an observer (P) sees Venus cross the
Sun's disk from A to B while another observer (P')
sees the transit happens from A\textquoteright{} to B'.
The two paths are separated by the distance $D$, whose measurement
is crucial for determining the A.U. 

From the similar triangles in (b), 
$$
\frac{PP'\text{(in km)}}{(1-R_{V})\text{(in A.U.)}}=\frac{D\text{(in A.U.)}}{R_{V}\text{(in A.U.)}}
$$

Here $R_{V}$ is the radius of Venus' orbit around the Sun, which
can be found in terms of the A.U. using Kepler's third law. Rearranging
the terms, we have 
<span id="AU"></span>
$$
\begin{equation}
1\text{A.U.}=\frac{R_{V}PP'}{(1-R_{V})D}\text{km}
\end{equation}
$$

We can determine $D$ through fundamental geometrical reasoning and
accurate measurements of the transit times recorded by the two observers.
The transit time as measured by observer P is proportional to the
chord AB. 

$$
t_{AB}=k\text{AB}=2kR\sin\theta
$$

with $k$ the proportionality constant. We note that the angle subtended
by the chord A'B' is slightly smaller
than that subtended by the chord AB, by say 2$\delta$. We can write
the transit time as measured by observer P'.

$$
\begin{align*}
t'_{A'B'} & =2kRsin(\theta-\delta)\\
 & =2kR(\sin\theta\cos\delta-\sin\delta\cos\theta)\\
 & \approx2kR(\sin\theta-\sin\delta\cos\theta)\\
 & =t_{AB}-2kR\sin\delta\cos\theta
\end{align*}
$$

From the above equations we can obtain $\sin\delta$ which will be
useful later

$$
\begin{align*}
t_{AB}-t'_{A'B'} & =2kR\sin\delta\cos\theta\\
\sin\delta & =\frac{t_{AB}-t'_{A'B'}}{2kR\cos\theta}\\
 & =\frac{t_{AB}-t'_{A'B'}}{t_{AB}}\frac{\sin\theta}{\cos\theta}
\end{align*}
$$

In the third step, we have used the small angle ($\delta\ll1$) approximation
$\cos\delta\approx1$ on the first term.

The distance between the two paths $D$ can be written and approximated
as 

$$
\begin{align*}
D & =h'-h\\
 & =R\cos(\theta-\delta)-R\cos\theta\\
 & =R(\cos\theta\cos\delta+\sin\theta\sin\delta)-R\cos\theta\\
 & =R(\cos\theta+\sin\theta\sin\delta)-Rcos\\
 & =R\sin\theta\sin\delta\\
 & =\frac{R\sin^{2}\theta}{\cos\theta}\frac{t_{AB}-t'_{A'B'}}{t_{AB}}
\end{align*}
$$

Putting this in Eq. ([1](#AU)), 

$$
1 \text{A.U.} = \frac{R_{V}PP'}{(1-R_{V})} \frac{\cos(\theta)}{R \sin^2(\theta)} \frac{t_{AB}}{t_{AB}-t'_{A' B'}} \text{km}
$$

The above is a simplified calculation to bring out the essence of
the method to determine the astronomical unit. With the use of radar
to accurately measure the astronomical unit, this method is now obselete.
Nevertheless the transit of Venus is still a spectacular and rare
event to observe. The previous two transit happened in 2004 and 2012.
The next transit of Venus will happen in 2117!
