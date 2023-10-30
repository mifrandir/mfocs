---
title: vector_bundle
date: 2023-10-23 15:36
---
# Vector bundle
A *vector bundle* of rank $k$ on an $n$-dimensional manifold $M$ is
consists of
1. a manifold $E$ of $\dim(E)=n+k$,
2. a smooth projection map $\pi : E\to M$,
3. for each $p\in M$, a real vector space structure on $E_p={\pi}^{-1}\left\lbrace{p}\right\rbrace$
such that, for all $p\in M$, there is neighbourhood $U\ni p$ and a
diffeomorphism 
$$
F : {\pi}^{-1}(U) \to U\times\mathbb{R}^k
$$
such that $\pi=\pi_U \circ F:{\pi}^{-1}(U)\to U$ and $E_p\cong\mathbb{R}^k$ as
vector spaces.
