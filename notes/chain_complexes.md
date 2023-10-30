---
title: chain_complexes
date: 2023-10-09 10:54
---
# Chain complex
A chain complex $C_\bullet$ is a family of objects
$\left\lbrace{C_n}\right\rbrace_{n\in\mathbb{Z}}$ in an abelian category $\mathcal A$ together with morphisms $\partial_n:C_n\to C_{n+1}$
such that $\partial^2=0$.

- $Z_n = Z_n\left({C}\right)=\ker\left({\partial_n}\right)$ is the module of $n$-cycles.
- $B_n=B_n\left({C}\right)=\text{im}(\partial_{n+1})$ is the module of $n$-boundaries.

# Category of chain complexes
A morphism $f_*:C_\bullet\to D_\bullet$ is a family of morphisms
$f_n:C_n\to D_n$ such that, for all $n$, $\partial\circ f = f\circ\partial$.

We thus have a category $\text{Ch}_\bullet({\mathcal A})$ of chain complexes in
the abelian category $\mathcal A$.

# Observations
- $0 \subseteq B_n \subseteq Z_n \subseteq C_n$ as $\partial_{n+1}\circ \partial_n = 0$ so $B_n\subseteq Z_n$
