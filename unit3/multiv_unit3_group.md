__Unit 3 Group Work Practice__   
__MultiV 2021-22 / Dr. Kessner__    

\vspace{.25in}

__Please use your own paper.  No calculator!  Have fun!__

\vspace{.25in}

\renewcommand{\vec}[1]{\mathbf{#1}}

__1.__  Consider the function $p(x,y) = x^2 - y^2$.

a. Draw the level sets $p(x, y) = -4, -1, 0, 1, 4$ in the $xy$ plane.

b. Find the equations of the tangent planes to the surface $z=p(x,y)$ at the
following points: $(0,0), (1,0), (0,1), (1,1)$.

\vspace{.5in}

__2.__  Let's think about ants walking on a pringle, i.e. curves on the same
surface $z=p(x,y)=x^2-y^2$.  Consider the following parametrically defined
curves in $\mathbb{R}^2$:  

A) $x(t)=t$, $y(t)=0$  
B) $x(t)=0$, $y(t)=t$  
C) $x(t)=5$, $y(t)=t$  
D) $x(t)=t$, $y(t)=t$ (What happens if $y(t)=-t$?)  
E) $x(t)=5+t$, $y(t)=t$ (What happens if $y(t)=-t$?)  
F) $x(t)=\cos t$, $y(t)=\sin t$  

For each of those curves, do the following analysis:

i) Find the composite function $z(t) = p(x(t), y(t))$, and its derivative $z'(t)$.

ii) Find $z'(t)$ using the multivariable chain rule.

iii) Consider the point on the curve when $t=1$ ($t = \frac{\pi}{2}$ for curve
(F)).  Find $D_{\vec{u}}(p)$ at that point, where $\vec{u}$ is the direction of
the curve, i.e. in the direction of $\vec{r}'(t)$.  What is the relation
between $D_{\vec{u}}(p)$ and $z'(t)$?

iv) Consider the curve in $\mathbb{R}^3$: $\left<x(t), y(t), z(t)\right>$.  Find
the tangent vector of the curve.   Show that as you move along the curve, the
tangent vector is always orthogonal to $\left< \frac{\partial p}{\partial x},
\frac{\partial p}{\partial y}, -1 \right>$.  (In other words, the tangent
vector of the curve lies in the tangent plane to the surface at that point.
Or, the gradient of a function is orthogonal to its level sets).  

_Fun fact_: Notice that the $\mathbb{R}^3$ curves for (D) and (E) are
actually straight lines, and in general, at every point on the pringle there
are two straight lines through the point that coincide with the surface.  For
this reason, the hyperbolic paraboloid is said to be _double ruled_.

\newpage

---
pagetitle: none
math: <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS_CHTML-full" type="text/javascript"></script>
geometry: margin=1in
header-includes: |
    \usepackage{amsmath}
---


