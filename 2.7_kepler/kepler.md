---
layout: page
title: Kepler's Laws from Newton's Laws
permalink: /2.7_kepler/kepler
---


### Central forces

Newton gave a geometric argument to show that a central force
implies the equal area property (equal areas swept out in equal
times).

More precisely, for a central force, 
$\vec{r}\times\vec{v}= \text{const}$, because

$ \begin{aligned}
    \frac{d}{dt} \left(\vec{r} \times \vec{v}\right) &=
        \vec{r}\,\' \times \vec{v} \;+\; \vec{r} \times \vec{v}\,\'  \cr
        &= \vec{v} \times \vec{v}  \;+\; \vec{r} \times \vec{a} \cr
        &= 0
\end{aligned}$

The last equality holds because $\vec{v}\times\vec{v}=0$ for any vector
$\vec{v}$ and $\vec{a}$ is in the direction $-\vec{r}$ for a central force.

### Polar Notation

Let $\vec{u}(t) = \begin{pmatrix} \cos\theta(t) \cr \sin\theta(t) \end{pmatrix}$,
so we can write $\vec{r}(t) = r(t)\vec{u}(t)$.  In other words,
$r(t)$ is the distance from the origin, and $\vec{u}(t)$ is the
unit vector in the direction of the position $\vec{r}(t)$.

Let $\vec{u}^{\perp} = \begin{pmatrix} -\sin\theta(t) \cr \cos\theta(t) \end{pmatrix}$
be the unit vector rotated $\frac{\pi}{2}$ from $\vec{u}$.

Note that $\dfrac{d}{dt}\vec{u} = \dfrac{d\theta}{dt}\vec{u}^{\perp}$ and
$\dfrac{d}{dt}\vec{u}^{\perp} =  -\dfrac{d\theta}{dt}\vec{u}$. (Verify!)

### Equal area property

$\begin{aligned}
\vec{r}\times\vec{v} &=
    \vec{r} \times \left( r\'\vec{u} + r\dfrac{d\theta}{dt}\vec{u}^{\perp} \right) \cr 
    &= r\'(\vec{r}\times\vec{u}) + r\dfrac{d\theta}{dt}(\vec{r}\times\vec{u}^{\perp}) \cr
    &= r^2 \dfrac{d\theta}{dt} \vec{k}
\end{aligned}$

(Verify that $\vec{r}\times\vec{u} = 0$ and 
$\vec{r}\times\vec{u}^{\perp} = r\vec{k}$.)

The area swept out in a small time $dt$ is $dA \approx \frac{1}{2}r^2d\theta$,
so the calculation above shows that $\dfrac{dA}{dt}$ is constant, equal areas
are swept out in equal times.

