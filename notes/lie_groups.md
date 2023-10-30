---
title: Lie groups
date: 2023-10-12 09:25
---

# Definition

A *Lie group* $G$ is a smooth manifold equipped with a smooth group structure.
That is, the group operations $\mu : G \times G \to G$ and $\iota : G \to G$
are smooth with respect to the manifold.

A *morphism of Lie groups* is a smooth group homomorphism.

# Properties
- Let $e\in V\subseteq G$ be open and suppose $G$ is connected. Then every
  element of $G$ is a finite product of elements in $W$ and their inverses.

# Examples 

- $M_n(\mathbb{R})$ under addition
- $GL(n,\mathbb{R})$ under multiplication
- $SL(N,\mathbb{R})$ under multiplication
- $O(n)$ under multiplication
  - define $F:M_n(\mathbb{R})\to S_n(\mathbb{R})$ by $A\mapsto A^\top A$
  - note ${F}^{-1}(1)$ is the underlying set of $O(n)$
  - further, let $A,B\in M_n(\mathbb{R})$ and note 
    $$
    F(A+B)-F(A) = (A+B)^\top(A+B)-A^\top A = A^\top B + AB^\top + B^\top B.
    $$
  - thus $dF_A(B) = A^\top B+AB^\top$
  - note, for $A\in O(n)$, $dF_A$ is surjective (TODO: why?)
  - applying the [regular value theorem](./regular_value_theorem.md) yields that $O(n)$ is an $n(n-1)/2$-dimensional manifold
  - the group structure is known and the operations are smooth
- $S^n$ is a Lie group if, and only if, $n\in\left\lbrace{1,3}\right\rbrace$.
