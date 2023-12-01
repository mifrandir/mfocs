---
title: inner_product_on_representations
date: 2023-11-16 16:28
---
# Invariance
An inner product $\langle-,-\rangle$ on a representation $V$ of $G$ is
$G$-invariant if, for all $u,v\in V$, $g\in G$,
$$
\langle gu, gv \rangle = \langle u,v\rangle.
$$

# $G$-invariance
Real representations with $G$-invariant representations are called orthogonal,
complex representations with $G$-invariant inner product are unitary.

> If $V$ is an orthogonal (or unitary) representation, then it is completely
> reducible.

> For any inner product $(-,-)$ on a representation $V$ of a compact, connected Lie group $G$, the inner product
> $$
> \langle u,v\rangle = \int_{g\in G} (gu, gv)
> $$
> is $G$-invariant.

> If $V,W$ are unitary irreducible representations of a compact Lie group $G$ then, for all $v,v'\in V$ and $w,w'\in W$,
> $$
  \int_{g\in G} \langle gv,v'\rangle_V\overline{\langle gw,w'\rangle_W}
  $$
> is zero if $V\not\cong W$ 
