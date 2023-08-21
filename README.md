# Calculation of curvature invariants for Kerr-Newman spacetime

The goal is to calculate the curvature invariants associate to the Kerr-Newman metric.
To do this we use the standard tensor calculus of general relativity. First we verify that Kerr-Newman metric is a solution of Einstein equation in presence of electromagnetic field. Then we calculate the curvature invariants of the Riemann tensor. Finally we plot the Kretschmann scalar as an exemple.  

The metric is written in Boyer-Lindquist coordinate system: $(t,r,\vartheta,\varphi)$.  
The metric signature used is $(+ - - -)$.  

We set:  
- $G = 1$
- $c = 1$
- $\frac{1}{4 \pi \epsilon_0} = 1$
---
The following change of variable could be used to reduce calculation time:  
$
\begin{align}
  \left\{
    \begin{array}{ll}
      y &= \cos(\vartheta) \\
      \mathrm{d} y &= - \sin(\vartheta) \,\mathrm{d} \vartheta
    \end{array}
  \right.
\end{align}
$

then we have $\sin^2(\vartheta)=(1-y^2)$.  
thus:  
$
\mathrm{d} \vartheta^2=\frac{\mathrm{d} y^2}{(1-y^2)}\,.
$
---
The curvature invariants of other black hole spacetimes can be deducted from the
Kerr-Newman ones by taking the apropriate limit of the black hole under consideration:

- Kerr spacetime: Kerr-Newman limit when $Q\rightarrow 0$  
- Reissner-Nordström spacetime: Kerr-Newman limit when $a\rightarrow 0$  
- Schwarzschild spacetime: Kerr-Newman limit when $Q\rightarrow 0$ and $a\rightarrow 0$  

---

The calculation is performed on `Matematica 13.0.0`, on AMD Ryzen 5 5625U and AMD ATI Barcelo. The order of magnitude of calculation time is the second.

## References

- [Second Order Scalar Invariants of the Riemann Tensor: Applications to Black Hole Spacetimes](https://arxiv.org/abs/gr-qc/0302095)
- [Kretschmann Scalar for a Kerr-Newman Black Hole](https://arxiv.org/abs/astro-ph/9912320)
