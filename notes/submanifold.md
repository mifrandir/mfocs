---
title: submanifold.md
date: 2023-10-30 10:38
---
# Submanifolds
A [smooth](smooth_function.md) $F:M\to N$ is 
- a *submersion* if $dF_p : T_p M\to T_p N$ is surjective,
- an *immersion* if $dF_p : T_p M\to T_p N$ is injective,
- an embedding if it is an immersion and $F:M\to F(M)$ is a homeomorphism with
  respect to the subspace topology on $F(M)\subseteq N$.

> If $F:M\to N$ is an embedding, then $F:M\subseteq F(M)$ is a diffeomorphism.

> **Whitney**. For each $n$-manifold $M$, there is an embedding $F:M\to\mathbb{R}^{2n}$ such that $F(M)$ is closed.
