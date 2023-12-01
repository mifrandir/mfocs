---
title: covering
date: 2023-11-09 11:27
---
# Covering
A map $\pi:G\to H$ is a *covering* if
1. it is surjective, and
2. for all $h\in H$, there exists an open $U\ni h$ and disjoint $U_i\subseteq G$ such that
  $$
  {\pi}^{-1}(U) = \bigsqcup_{i\in I} U_i
  $$
  and $\pi_{|U_i}:U_i\to U$ is a diffeomorphism.

> *Theorem*. A Lie group homomorphism $\pi : G\to H$ is a covering if, and only
> if, $d\pi_e : T_e G \to T_e H$ is an isomorphism.

> *Corollary.* Let $\pi:G\to H$ a covering and a Lie group homomorphism. Then
>   - $\ker\pi$ is discrete
>   - $\ker\pi \triangleleft G
>   - if $G$ is connected then $\ker\pi\subseteq Z(G)$

# Universal covering
> *Theorem.* If $G$ is connected then there exists a covering $\pi:\tilde G\to G$
> such that $\tilde G$ is simply connected.

We call $\tilde G$ the *universal covering*.
