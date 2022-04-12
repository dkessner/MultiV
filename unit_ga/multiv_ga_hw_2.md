__Geometric Algebra HW 2 (Geometric Product)__   
__MultiV 2021-22 / Dr. Kessner__    

\vspace{.25in}

\renewcommand*{\arraystretch}{1.5}

1. For each of the following vectors, find the inverse.  Draw the unit
circle on the plane, and draw each vector and its inverse.

    a. $u = \begin{pmatrix} 2 \\ 0 \end{pmatrix}$  

    b. $v = \begin{pmatrix} 0 \\ 3 \end{pmatrix}$

    c. $w = \begin{pmatrix} \frac{\sqrt{3}}{2} \\ \frac{1}{2} \end{pmatrix}$

    d. $x = \begin{pmatrix} \sqrt{3} \\ 1 \end{pmatrix}$

\vspace{.5in}

_Answers:_ 
$u^{-1} = \begin{pmatrix} \frac{1}{2} \\ 0 \end{pmatrix}$,
$v^{-1}= \begin{pmatrix} 0 \\ \frac{1}{3} \end{pmatrix}$,
$w^{-1} = w = \begin{pmatrix} \frac{\sqrt{3}}{2} \\ \frac{1}{2} \end{pmatrix}$,
$x^{-1} = \begin{pmatrix} \frac{\sqrt{3}}{4} \\ \frac{1}{4} \end{pmatrix}$


\vspace{.5in}

2. Let $u = e_1 = \begin{pmatrix} 1 \\ 0
    \end{pmatrix}$.  
    Let $v =
    (\cos\dfrac{\pi}{6})e_1+(\sin\dfrac{\pi}{6})e_2 =
    \begin{pmatrix} \frac{\sqrt{3}}{2} \\ \frac{1}{2} \end{pmatrix}$.

    \vspace{.25in}

    Show the following:

    \vspace{.25in}

    a. $uv = 
        (\cos\dfrac{\pi}{6})+(\sin\dfrac{\pi}{6})e_1 e_2 =
        \frac{\sqrt{3}}{2}+\frac{1}{2}e_1 e_2$

        ($uv$ is a rotor representing a rotation by $\frac{\pi}{6}$.)

    b. $vu =
        \frac{\sqrt{3}}{2}-\frac{1}{2}e_1 e_2$

        ($vu$ is a rotor representing a rotation by $-\frac{\pi}{6}$.)

    c. $vuv = v(uv) = (vu)v =
        \begin{pmatrix} \frac{1}{2} \\ \frac{\sqrt{3}}{2} \end{pmatrix}$

        (applying $uv$ on the right (or $vu$ on the left) rotates
        $v$ by $\frac{\pi}{6}$)

    d. $vvu = v(vu) = (uv)v = e_1 =
        \begin{pmatrix} 1 \\ 0 \end{pmatrix}$

        (applying $vu$ on the right (or $uv$ on the left) rotates
        $v$ by $-\frac{\pi}{6}$)

    e. $uvuv = \frac{1}{2} + \frac{\sqrt{3}}{2} e_1 e_2$

       ($uvuv = (uv)^2$ is a rotor representing rotation by $\frac{\pi}{3}$)

    f. $(vu)(uv) = 1$

    g. $vuvuv = e_2 = \begin{pmatrix} 0 \\ 1 \end{pmatrix}$

    h. $uvuvuv = e_1 e_2$

       ($uvuvuv = (uv)^3$ a rotor representing rotation by 
       $\frac{\pi}{2}$ (the unit bivector))


\vspace{2in}

---
pagetitle: none
math: <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS_CHTML-full" type="text/javascript"></script>
geometry: margin=1in
header-includes: |
    \usepackage{amsmath}
---


