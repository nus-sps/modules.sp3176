---
label: Appendix B
layout: page
icon: ":pencil:"
order: -5
author:
  - name: Dr Lim Zhi Han
    email: matlzh@nus.edu.sg
    link: https://sps.nus.edu.sg/user/lim.zhihan/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/2019/06/logo_sps20.png
date: 2023-10-25T12:00
description: "The Expanding Universe"
---

To obtain Eq.([7.44](#HubbleAge)), we need to first get the following:

$$
\begin{align}
H = \frac{\dot{S}}{\ddot{S}}, \space H_0 = \frac{\dot{S_0}}{\ddot{S_0}}, \space \rho_c = \frac{3H^2}{8 \pi G}, \space \rho_{c,0} = \frac{3H_0^2}{8 \pi G}, \space \rho S^3 = \rho_0 S^3_0 \nonumber
\end{align}
$$

From the first Friedmann equation,

$$
\begin{align}
\dot{S}^2 - \frac{8}{3} \pi G \rho S^2 & = \dot{S}_0^2 - \frac{8}{3} \ pi G \rho_0 S^2_0 \nonumber \\
\dot{S}^2 & = \dot{S}_0^2 \left( 1 - \frac{8}{3} \pi G \rho_0 \frac{S_0^2}{\dot{S}^2} + \frac{8}{3} \pi G \rho \frac{S^2}{\dot{S}_0^2 } \right) \nonumber \\
& = \dot{S}_0^2 \left ( 1-\frac{H_0^2}{\rho_{c,0}}\rho\frac{S_0^2}{\dot{S}_0^2} + \frac{H_0^2}{\rho_{c,0}}\rho_0\frac{S_0^3}{S^3} \frac{S^2}{\dot{S}_0^2} \right) \nonumber \\
& = \dot{S}_0^2 \left ( 1-\frac{1}{\rho_{c,0}}\rho + \frac{1}{\rho_{c,0}}\rho_0\frac{S_0}{S} \right) \nonumber \\
& = \dot{S}_0^2 \left ( 1+\frac{\rho_0}{\rho_{c,0}} \left( \frac{1}{x} -1 \right) \right) \nonumber \\

\end{align}
$$

where $x=\frac{S}{S_0}$.

$$
\begin{align}

H_0t_0 &= H_0 \int_0^{t_0} {dt} \nonumber \\
&= H_0 \int_0^{S_0} {\frac{dt}{dS} dS} \nonumber \\
&= H_0 \int_0^{1} { (\dot{S})^{-1}  S_0 \space dx} \nonumber \\
&= H_0 \int_0^{1} { \dot{S}_0^{-1} \left ( 1+\frac{\rho_0}{\rho_{c,0}} \left( \frac{1}{x} -1 \right) \right)^{-\frac{1}{2}}  S_0 \space dx} \nonumber \\
&= \int_0^{1} { \left ( 1+\frac{\rho_0}{\rho_{c,0}} \left( \frac{1}{x} -1 \right)\right)^{-\frac{1}{2}} dx} \nonumber \\
\end{align}
$$




