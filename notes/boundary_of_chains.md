---
title: boundary_of_chains
date: 2023-10-18 10:00
---
# Definition
Let $\sigma:\Delta^n\to X$ be a singular $n$-simplex (see [chain.md](chain.md))
and let $0\leq i\leq n$. Then define the singular $(n-1)$-simplex
$\left.\sigma\right\vert_{[0,\ldots,\hat i,\ldots,n]}:\Delta^{n-1}\to X$ by
$$
(x_0,\ldots,x_{n-1})\mapsto \sigma(x_0,\ldots,x_{i-1},0,x_i,\ldots,x_{n-1})
$$
Intuitively, this is the face of $\sigma$ not involving the vertex $i$.

The *boundary of a singular $n$-simplex* $\sigma$ is the $(n-1)$-chain given by
$$
\partial\sigma = \sum_{i=1}^{n} (-1)^i \left.\sigma\right\vert_{[0,\ldots,\hat i,\ldots,n]}.
$$
Intuitively, this is a combination of all the faces of $\sigma$.

We thus have a homomorphism of abelian groups (resp. $R$-modules)
$$
\partial : C_n(X,R) \to C_{n-1}(X,R).
$$

We call a $c\in C_n(X,R)$ *closed* if, and only if, $\partial c = 0$.

# Properties
- $\partial^2 = 0$.
- We have a [chain complex](chain_complexes.md) $C_\bullet$ given by
  $C_n=C_n(X,R)$ and the corresponding boundary maps.
