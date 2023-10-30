---
title: induced_lie_algebra
date: 2023-10-20 09:45
---
# Induced Lie algebra
The *induced [Lie algebra](lie_algebra.md)* of a [Lie group](lie_group.md) $G$ is given by
$$
\text{Lie}(G) = \left\lbrace{\text{left invariant vector fields}}\right\rbrace
$$
and, for $X,Y\in\text{Lie}(G)$,
$$
\left[{X,Y}\right](f) = X(Y(f))-Y(X(f)).
$$

# Properties
- $\text{Lie}(G)$ is finite-dimensional.
- There is an isomorphism $\text{Lie}(G)\simeq T_e G$ given by $X\mapsto X_e$. The inverse is then given by $X_e \mapsto g\mapsto (dL_g)_eX_e$. (see [tangent_vector](tangent_vector.md), [differential](differential.md), and [vector_field](vector_field.md))
- For $F:G\to H$, the deriviative
  $$
  dF_e : \text{Lie}(G) \to \text{Lie}(H)
  $$
  is a homomorphism of Lie algebras.
- Non-isomorphic Lie groups need not induce non-isomorphic Lie algebras. E.g. take $G=O(n)$ and $H=U(n)$.
