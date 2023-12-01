---
title: representations_of_lie_groups
date: 2023-11-07 13:43
---
# Representation
A *representation* of a Lie group $G$ on $V$ is a Lie group
homomorphism $\phi : G\to\text{Aut}(V)$.

For any Lie group representation $\phi:G\to\text{Aut}(V)$, we have a Lie
algebra representation $d\phi_e : \text{Lie} G \to \text{End}(\text{Lie}(V))$.
That is,
$$
d\phi_e\left[{X,Y}\right] = d\phi_e(X)d\phi_e(Y)-d\phi_e(Y)d\phi_e(X).
$$

# Reducibility

A representation $V$ is
- *reducible* if there is a proper subspace $W\subset V$ such that, for all $g\in G$, $gW=W$;
- *completely reducible* if it is the direct sum of irreducible representations.

> Every representation of a compact Lie group is completely reducible.

# Examples
- For $n\in\mathbb{Z}$ we have a representation $U_n$ of $S^1$ on $\mathbb{C}$
  given by $\phi(e^{i\theta})\cdot z = e^{in\theta}z$. We have the Lie algebra
  homomorphism $d\phi_e (z) = inz$.
- For $n\in\mathbb{N}$ we have a representation $V_n$ of $SU(2)$ on the space
  of homogeneous polynomials in two variables of degree $n$. The action is
 $$
 (A\cdot p)(z_1,z_2) = p(A^{-1} z) = p(\bar a z_1 - b z_2, \bar b z_1 + az_2).
 $$
 Using $\text{Lie} SU(2)=\text{span}\left\lbrace{X,Y,Z}\right\rbrace$, we have the action
 $$
 X 
 $$
 
# Subrepresentation

For a representation $V$ of $G$, define the *subrepresentation* 
$$
V^G = \left\lbrace{v\in V : \forall g\in G. gv = v}\right\rbrace.
$$

> If $G$ is compact, then
> $$
  V^G = \left\lbrace{\int_{g\in V} gv : v\in V}\right\rbrace
  $$
> where integration of vector valued functions is defined in the obvious way
> and $\int_G 1 = \int_G \Omega = 1$.
