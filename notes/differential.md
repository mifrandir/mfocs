---
title: differential
date: 2023-10-16 10:36
---
# Definition
The *differential* of a smooth $F:M\to N$ at $p$ is a linear map 
$dF_p:T_pM\to T_{F(p)}N$ given by $dF_p(X_p)(f)=X_p(f\circ F)$.

In particular, for charts $(U,\phi)$ on $M$ and $(V,\psi)$ on $N$ and
$$
X_p=\sum_{i=1}^{n} a_i\left.\frac{\partial}{\partial x_i}\right\vert_{\phi(p)}
$$
(See [tangent_vector](tangent_vector.md).) Then
$$
dF_p(X_p)(f) = \sum_{i,j} a_i \frac{\partial F_j}{\partial x_i}\frac{\partial (f\circ{\psi}^{-1})}{\partial y_j}.
$$

# Example
- $F:\mathbb{R}^{n+1}\to\mathbb{R}:(x_i)\mapsto\sum_i x_i^2$ has differential
  $dF_p:\mathbb{R}^{n+1}\to\mathbb{R}:x\mapsto 2x^\top p$.
