# Calculation of curvature invariants for Kerr-Newman spacetime

The goal is to calculate the curvature invariants associate to the Kerr-Newman metric. To do this we use the standard tensor calculus of general relativity. First we verify that Kerr-Newman metric is a solution of Einstein equation in presence of electromagnetic field. Then we calculate the curvature invariants associated to the Riemann, Weyl and Ricci tensor. We plot the Kretschmann scalar. And finally we deduce the curvature invariants of the Kerr, Reissner-Nordström and Schwarzschild metric taking the appropriate Kerr-Newman spacetime limits.

The metric is written in Boyer-Lindquist coordinate system: $(t,r,\vartheta,\varphi)$.  
The metric signature used is $(+ - - -)$.  

We set:
- $G = 1$
- $c = 1$
- $4\pi\epsilon_0 = 1$

---

The following change of variable could be used to reduce calculation time:  
$y=\cos(\vartheta)$  
$\mathrm{d}y= -\sin(\vartheta) \mathrm{d} \vartheta$.  

then we have: $\sin^2(\vartheta)=(1-y^2)$.  
thus:  
$\mathrm{d}\vartheta^2=\frac{\mathrm{d} y^2}{(1-y^2)}$.

---
  
In dimension four, the curvature invariants associated with the Riemann, Weyl and Ricci tensor are related by :  
$K_1=I_1+2 R_{\mu\nu}R^{\mu\nu}-\frac{1}{3}R^2$  
$K_3=-I_1+2 R_{\mu\nu}R^{\mu\nu}-\frac{2}{3}R^2$  

---

The Kerr-Newman metric is the most general solution to Einstein's equation describing an asymptotically flat, stationary, axisymmetric spacetime of dimension four in the presence of an electromagnetic field. Consequently, the Kerr, Reissner-Nordtröm and Schwarzschild metrics, as well as the curvature invariants associated with their Riemann, Weyl and Ricci tensors, can be deduced from the Kerr-Newman ones under the appropriate limits:
- Kerr spacetime: $M\neq 0$, $Q=0$.
- Reissner-Nordström spacetime: $M\neq 0$, $a=0$.
- Schwarzschild spacetime: $M\neq 0$, $Q=0$ and $a=0$.

---

The calculation is performed on `Matematica 13`, on AMD Ryzen 5 5625U and AMD ATI Barcelo. The order of magnitude of calculation time is the second.

## References

- [Second Order Scalar Invariants of the Riemann Tensor: Applications to Black Hole Spacetimes](https://arxiv.org/abs/gr-qc/0302095)
- [Kretschmann Scalar for a Kerr-Newman Black Hole](https://arxiv.org/abs/astro-ph/9912320)
