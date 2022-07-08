__Unit 2 Test__   
__MultiV 2021-22 / Dr. Kessner__  

\vspace{.25in}
__No calculator!  Have fun!__
\vspace{.25in}

\renewcommand{\vec}[1]{\mathbf{#1}}


__1.__ Consider the curve defined by the vector function
$$\vec{r}(t) = 
\begin{pmatrix}
10\cos t \\
5\sqrt{2}\sin t \\
5\sqrt{2}\sin t \\
\end{pmatrix}$$

What is the curve?
\vspace{.5in}

a) Find the velocity and speed of this curve.

\vspace{2in}

b) Find $\vec{T}(t)$, $\vec{N}(t)$, and $\vec{B}(t)$.

\vspace{2in}

c) Find the equations of the osculating (TN), normal (NB), and rectifying (TB)
planes at $t=0$.

\newpage

__2.__ Consider the curve defined by:
$$\vec{r}(t) = 
\begin{pmatrix}
\cos 5t^2\\
\sin 5t^2\\
7\\
\end{pmatrix}$$

a) Find the velocity and speed of this curve.

\vspace{2in}

b) Find the arc length of the curve $s(t)$, starting from $t=0$.

\vspace{2in}

c) Reparametrize the curve by arc length.  What is the curve?


\newpage

__3.__ Suppose that a projectile is launched (in 3D, $z$ is up) from a platform
80 ft. above the origin.  The initial position $(x_0, y_0, z_0) = (0, 0, 80)$
and initial velocity $(v_x, v_y, v_z) = (30, 40, 64)$.

a) Assume that the acceleration $\vec{a}(t) = \left<0, 0, -32\right>$, i.e. gravity
acts in the $z$ direction.  Find the velocity vector $\vec{v}(t)$.

\vspace{1.5in}

b) Find the position vector $\vec{r}(t)$.

\vspace{1.5in}

c) What is the maximum height ($z$ value) of the projectile?

\vspace{2in}

d) The projectile hits the ground when $z(t)=0$.  When does this happen?  What
is the $(x,y)$ position when it hits the ground?  What is the distance from
the origin to the point of impact?

\newpage

__4.__ a. Consider the following function defined in polar coordinates:
$$
    r = \frac{6}{1 + 2\cos\theta}
$$
Sketch the graph of the curve.  Also find the equation of the curve in
rectangular coordinates.

\vspace{4in}

b. Consider the following function defined in polar coordinates:
$$
    r = \frac{6}{2 + \cos\theta}
$$
Sketch the graph of the curve.  Also find the equation of the curve in
rectangular coordinates.

\newpage

__Bonus__  Suppose $\vec{r}(t)$ is a curve on the unit sphere.  Prove that the
velocity vector is always orthogonal to the position vector.

\vspace{4in}

__Bonus__  Show that the result above implies that $\vec{T}(t)$, $\vec{N}(t)$
and $\vec{B}(t)$ are pairwise orthogonal unit vectors for any curve
$\vec{r}(t)$, for all $t$.  (In other words, $\vec{T}(t)$, $\vec{N}(t)$, and
$\vec{B}(t)$ form what is known as an _orthonormal basis_ for $\mathbb{R}^3$.)

\newpage

__Bonus__  Assume Newton's second law: $\vec{F} = m\vec{a}$.  Suppose that an
object is moving with its position given by $\vec{r}(t)$ and velocity by
$\vec{v}(t)$.  Also suppose that the only force acting on the object is a
central force (in other words, the force is always directed toward the origin).
Show that $\vec{r}(t) \times \vec{v}(t)$ is constant.  Why does this imply
that the motion is constrained to a plane?

\vspace{4in}

__Bonus__  Suppose you are given a point (focus) and a line (directrix).
Recall the alternate geometric definition of an ellipse: every point on the
ellipse satisfies
$$
    \frac{\text{distance to focus}}{\text{distance to directrix}} = e < 1
$$
Let $d$ be the distance between the focus and directrix.  Derive the polar
equation for the ellipse.

\newpage



---
pagetitle: none
math: <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS_CHTML-full" type="text/javascript"></script>
geometry: margin=1in
header-includes: |
    \usepackage{amsmath}
---


