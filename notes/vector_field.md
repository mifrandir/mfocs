---
title: vector_field
date: 2023-10-16 10:49
---
# Vector field
A *vector field* on $M$ is a smooth map $X:M\to TM$. I.e., for each
$p\in M$, $X_p=X(p)\in T_p M$.

# Pullback
Let $X$ be a vector field on $M$ and $F:M\to M$ a diffeomorphism.
Then define the pullback vector field $F_*X$ on $M$ by
$$
(F_*X)_{F(p)} = F_* X_p = dF_{p}(X_p).
$$
(see [differential](differential.md))

In particular, for $X_p\in T_p M$ and $F\in\text{Diff}(M)$, we obtain
$F_* X_p\in T_{F(p)} M$.

# Left and right invariance
A vector field $X$ is *invariant by a diffeomorphism $F$*
if, and only if, $F_* X = X$.

In particular, consider an element $g\in G$ of a Lie group and the diffeomorphisms $L_g,R_g$ given by
$$
L_g(h) = gh, R_g(h) = hg.
$$
A vector field $X$ is *left invariant* (resp. *right invariant*) if, and
only if, for all $g\in G$, $(L_g)_* X = X$ (resp. $(R_g)_* X=X$).
Explicitly, 
$$
((L_g)_* X)_h(f)
= d(L_g)_{{g}^{-1}h}(X_{{g}^{-1}h})(f)
= X_{g^{-1}h}(f\circ L_g)
= X_h(f)
$$

> If $X$ is left-invariant then, for all $g\in G$ and $f\in C^\infty(M)$,
  $$
  X_g(f) = \left.\frac{d}{dt}\right\vert_{t=0} f(g\exp(tX))
  $$
  (see [exponential_map](exponential_map.md))
  Proof: https://web.math.ku.dk/~schlicht/Liegroups/ad.pdf
