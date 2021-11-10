__Linear Transformations Homework__   
__MultiV 2021-22 / Dr. Kessner__  

\renewcommand{\vec}[1]{\mathbf{#1}}

First, some notation: let $R_{\theta} = 
\begin{pmatrix}
    \cos\theta & -\sin\theta \\
    \sin\theta & \cos\theta
\end{pmatrix}$
represent rotation in the plane.

For example, $R_\frac{\pi}{6}$ means rotation by $\frac{\pi}{6}$:
$$R_{\frac{\pi}{6}} = 
\begin{pmatrix}
    \frac{\sqrt{3}}{2} & -\frac{1}{2} \\[0.3em]
    \frac{1}{2} & \frac{\sqrt{3}}{2}
\end{pmatrix}
$$


__1.__ Apply each of the following matrices to the specified
vectors.  Think about how the vectors are transformed, and make
sure your answers make sense.  Describe the linear transformation
represented by the matrix.

a. $S = 
\begin{pmatrix}
2 & 0 \\
0 & 2 \\
\end{pmatrix}$ 
applied to 
$\vec{i}, \vec{j}, \text{and}
\begin{pmatrix}
    3 \\  
    4 \\  
\end{pmatrix}$

b. $S^2$ applied to 
$\vec{i}, \vec{j}, \text{and}
\begin{pmatrix}
    3 \\  
    4 \\  
\end{pmatrix}$

c. $R_{\frac{\pi}{6}}$ 
applied to 
$\vec{i}, \vec{j}, \text{and}
\begin{pmatrix}
    \frac{\sqrt{3}}{2} \\[0.3em]
    \frac{1}{2} \\  
\end{pmatrix}$

d. $R_{\frac{\pi}{6}}^2$ 
applied to 
$\vec{i}, \vec{j}, \text{and}
\begin{pmatrix}
    \frac{\sqrt{3}}{2} \\[0.3em]
    \frac{1}{2} \\  
\end{pmatrix}$


e. $R_{\frac{\pi}{6}}^3$ 
applied to 
$\vec{i}, \vec{j}, \text{and}
\begin{pmatrix}
    \frac{\sqrt{3}}{2} \\[0.3em]
    \frac{1}{2} \\  
\end{pmatrix}$

f. $A = 
\begin{pmatrix}
0 & 1 \\
1 & 0 \\
\end{pmatrix}$ 
applied to 
$\vec{i}, \vec{j}, \text{and}
\begin{pmatrix}
    3 \\  
    4 \\  
\end{pmatrix}$

g. $A^2$
applied to 
$\vec{i}, \vec{j}, \text{and}
\begin{pmatrix}
    3 \\  
    4 \\  
\end{pmatrix}$

h. $P = 
\begin{pmatrix}
0 & 1 & 0 \\
\end{pmatrix}$ 
applied to 
$\vec{i}, \vec{j}, \vec{k}, \text{and}
\begin{pmatrix}
    3 \\  
    4 \\  
    5 \\  
\end{pmatrix}$

i.  $C = 
\begin{pmatrix}
1 \\ 2 \\ 3 \\
\end{pmatrix}$ 
applied to 
$(0), (1), (2)$.
Yes, these are $1\times 1$ matrices, otherwise known as
real numbers.

j. $PC$ 
applied to 
$(0), (1), (2)$


__2.__  Verify the following:
$$
    R_{\frac{\pi}{6}}^{-1} = R_{-\frac{\pi}{6}}
$$
$$
    R_{\frac{\pi}{4}}^2 = R_{\frac{\pi}{2}}
$$
$$
    R_{\frac{\pi}{2}}^2 = R_{\pi}
$$
$$
    R_{\pi}^2 = I
$$
$$
    R_{\theta}R_{\phi} = R_{\theta + \phi}
$$



---
pagetitle: none
math: <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS_CHTML-full" type="text/javascript"></script>
geometry: margin=1in
header-includes: |
    \usepackage{amsmath}
---


