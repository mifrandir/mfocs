---
title: homology
date: 2023-10-27 13:42
---
# Homology
Fix an abelian category $\mathcal A$. The *$n$th homology of a [chain complex](chain_complexes.md)* $C_\bullet$ is
$$
H_n(C_\bullet) = Z_n(C_\bullet)/B_n(C_\bullet) = \ker(\partial_n)/\text{im}(\partial_{n+1}).
$$

This is well-defined as $0\subseteq B_n\subseteq Z_n\subseteq C_n$.

# The homology functor
Note that for each morphism  $f:C_n\to D_n$ induces a morphism
$f_* : H_n(C_\bullet)\to H_n(D_\bullet)$ on the quotients. 

We may now consider the object 
$H_*(C_\bullet) = \bigoplus_{n\in\mathbb{Z}} H_n(C_\bullet)$.
Thus each morphism of chain complexes $f:C_\bullet\to D_\bullet$ induces a morphism 
$$
f_* = \bigoplus_{n\in\mathbb{Z}} (f_n)_*:H_*(C_\bullet)\to H_*(D_\bullet).
$$

This defines a functor 
$$
H_* : \text{Ch}({\mathcal A})\to\text{Graded}_{\mathbb{Z}}(\mathcal A).
$$
