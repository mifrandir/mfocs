---
title: smooth_function
date: 2023-10-16 11:07
---
# Smoothness of functions
A continuous $F:M\to N$ is *smooth* if, for all charts $(U,\phi)$
on $M$ and $(V,\psi)$ on $N$, ${\psi}^{-1}\circ F\circ\phi$ is smooth. 
$$
\mathbb{R}^m
\xrightarrow{\phi} M
\xrightarrow{F} N
\xrightarrow{{\psi}^{-1}}
\mathbb{R}^n.
$$
(see [Smooth manifolds](smooth_manifolds.md))

# Algebra structure
Denote by $C^\infty(M)$ the set of all smooth functions $M\to M$. This admits
an $\mathbb{R}$-algebra structure under pointwise addition, pointwise multiplication,
and scalar multiplication.

Further, there is a full subcategory
$$
C^\infty\text{-algebras}\to\textbf{Alg}_\mathbb{R}.
$$

# Properties
On any manfild  there are enough global smooth functions to define local
coordinate systems near any point.
