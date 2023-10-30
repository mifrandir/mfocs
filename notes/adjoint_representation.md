---
title: adjoint_representation
date: 2023-10-23 14:31
---
# Adjoint representation
The *adjoint [representation](representation_of_a_lie_group.md)* of a [Lie group](lie_group.md) $G$ on its induced [Lie algebra](lie_algebra.md)
is the Lie group homomorphism $\text{Ad}:G\to\text{Aut}(\text{Lie}(G))$ given
by
$$
g\mapsto X\mapsto(L_g)_*(R_{{g}^{-1}})_* X.
$$

# Derivative
Consider the derivative $\text{ad}=d(\text{Ad})_e$. This is a
morphism 
$$
\text{Lie}(G)\to\text{End}(\text{Lie}(G)),
$$
i.e.
$$
\text{Lie}(G)\times\text{Lie}(G)\to\text{Lie}(G).
$$

We have $\text{ad}(X,Y) = [X,Y]$.
> Proof. 
  $\text{ad}(X,Y)$
  $=d(\text{Ad})_e(X)(Y)$
  $=\frac{d}{dt}\text{Ad}(\phi_t)Y$
  $=\frac{d}{dt}(L_{\phi_t})_*(R_{{\phi}^{-1}_t})_* Y$
  $= XY-YX = [X,Y]$
