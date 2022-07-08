__Unit 3 Group Work 2__   
__MultiV 2021-22 / Dr. Kessner__    

\vspace{.25in}

__Be sure to show all work.  No calculator!  Have fun!__

\vspace{.25in}

\renewcommand{\vec}[1]{\mathbf{#1}}

__1.__  Consider the function $f(x,y) = \sqrt{x^2 + y^2}$.

a. Draw the level sets $f(x, y) = 0, 1, 2, 3$ in the $xy$ plane.  What is the surface $z=f(x,y)$?

\vspace{2in}

b.  At each of the following points, find the direction of maximum change of
$f$ and calculate the directional derivative in that direction.  (Do your
answers make sense?)

* $\left<x_0,y_0\right> =
3\left<\cos\frac{\pi}{6},\sin\frac{\pi}{6}\right> =
\left<\frac{3\sqrt{3}}{2},\frac{3}{2}\right>$.

\vspace{2in}

* $\left<x_0,y_0\right> =
2\left<\cos\frac{5\pi}{4},\sin\frac{5\pi}{4}\right> =
\left<-\sqrt{2}, -\sqrt{2}\right>$

\newpage

c. Consider the parametric curve $\left<x(t), y(t)\right> = \left<5\cos t,
5\sin t\right>$.  Find the composite function $f(t) = f(x(t), y(t))$.  Find the
derivative $\frac{df}{dt}$ in two different ways: 1) using standard
differentiation, 2) using the multivariable chain rule.

\vspace{4in}

d. Consider the parametric curve $\left<x(t), y(t)\right> = \left<t\cos t,
t\sin t\right>$.  Find the composite function $f(t) = f(x(t), y(t))$.  Find the
derivative $\frac{df}{dt}$ in two different ways: 1) using standard
differentiation, 2) using the multivariable chain rule.

\newpage

e. For the following points in $\mathbb{R}^3$, verify that the point is on the
surface $z = f(x,y)$, and find the tangent plane to the surface there.
(Do your answers make sense?)

* (3, 0, 3)
* (0, 5, 5)

\vspace{4in}

f. Now consider this same function in polar coordinates:
\begin{align*}
   x &= r \cos \theta \\
   y &= r \sin \theta
\end{align*}
Calculate $\frac{\partial f}{\partial r}$ and $\frac{\partial f}{\partial \theta}$
using the multivariable chain rule (but check your answer by differentiating the
composite function).
(How is this related to parts (b) and (c)?)

\newpage

__2.__ Let 
$$
    F(x, y, z) = \frac{x^2}{16} + \frac{y^2}{25}
$$
and consider the level surface $F(x,y,z) = 1$.  What does the surface look like?

a. For the following points in $\mathbb{R}^3$, verify that the point is on the
surface, and find the tangent plane to the surface there.
(Do your answers make sense?)

* (4, 0, 0)
* (4, 0, 10)
* (0, 5, 0)
* (0, 5, -10)

\vspace{4in}

b. Verify that the curve $\left< x(t), y(t), z(t)\right> = \left<4\cos t, 5\sin
t, t\right>$ lies on the surface.  Calculate $\frac{dF}{dt}$ using the chain
rule. 

\newpage

c. Verify that the curve $\left< x(t), y(t), z(t)\right> = \left<4\cos t, 5\sin
t, e^t \sin t\right>$ lies on the surface.  Calculate $\frac{dF}{dt}$ using the
chain rule. 

\vspace{4in}

d. Verify that the curve $\left< x(t), y(t), z(t)\right> = \left<4, 0, e^t \sin
t\right>$ lies on the surface.  Calculate $\frac{dF}{dt}$ using the chain rule.

\vspace{3in}

Interpret your calculations (b)-(d) as statements about orthogonality.


\newpage

__3.__ Let $R_\theta =
\begin{pmatrix}
    \cos\theta & -\sin\theta \\
    \sin\theta & \cos\theta
\end{pmatrix}$
represent rotation in the plane.

Verify that $R_{\frac{\pi}{2}}^2 = R_{\pi}$ and $R_{\pi}^2 = R_{2\pi} = I$.


---
pagetitle: none
math: <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS_CHTML-full" type="text/javascript"></script>
geometry: margin=1in
header-includes: |
    \usepackage{amsmath}
---


