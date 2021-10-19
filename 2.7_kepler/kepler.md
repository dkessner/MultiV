---
layout: page
title: Kepler's Laws from Newton's Laws
permalink: /2.7_kepler/kepler
---


#### Some observations

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

The last equality holds because $\vec{v}\times\vec{v}=0$ for any
vector $\vec{v}$ and $\vec{r}\times\vec{a}=0$ for a central force.

Let $\vec{u}(t) = \begin{pmatrix} \cos\theta(t) \cr \sin\theta(t) \end{pmatrix}$,
so we can write $\vec{r}(t) = r(t)\vec{u}(t)$.  In other words,
$r(t)$ is the distance from the origin, and $\vec{u}(t)$ is the
unit vector in the direction of the position $\vec{r}(t)$.

Let $\vec{u}^{\perp} = \begin{pmatrix} -\sin\theta(t) \cr \cos\theta(t) \end{pmatrix}$
be the unit vector rotated $\frac{\pi}{2}$ from $\vec{u}$.



