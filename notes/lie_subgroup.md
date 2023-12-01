---
title: lie_subgroup
date: 2023-10-24 10:27
---
# Immersed subgroup
An *immersed sugroup* of a [Lie group](lie_group.md) $G$ is a Lie group
$H$ with a smooth $j:H\to G$ whose derivative
$$
dj_p : T_p H \to T_{j(p)} G
$$
is injective for all $p\in M$.

# Embedded subgroup
An *embedded subgroup* of a Lie group $G$ is a Lie group $H$ such that $H$
is a subgroup of $G$ and the inclusion $j:H\to G$ is a Lie group
homomorphism.

> Let $H\leq G$ as groups. Then $H$ is an embedded Lie subgroup if, and only if, $H\subseteq G$ is closed.

> If $\phi : G\to H$ is a Lie group homomorphism, then $\ker\phi\subseteq G$ is a closed and hence embedded Lie subgroup of $G$ with Lie algebra $\text{Lie}(\ker\phi)=\ker(d\phi_e)$.

# Properties
- Immersions need not be injective, only their derivatives.
- The topology on an embedded $H\leq G$ may be very different to the one on
  $G$. E.g. the kernel of a Lie group homomorphism does not have the
  induced topology.
- Any compact Lie group may be embedded in some $GL(n,\mathbb{R})$.
- $\tilde{SL(2,\mathbb{R})}$ may not be embedded in any $GL(n,\mathbb{R})$ (see [covering](covering.md))

# Examples
- The connected component containing the identity is an embedded subgroup.
- Kernel of a Lie group homomorphism is an embedded subgroup.
- Taking $G=T^1=\mathbb{C}/\sim$ and $j:\mathbb{R}\to G$ to be
  $t\mapsto(e^{2\pi i t},e^{2\pi i\alpha t})$ for
  $\alpha\in\mathbb{R}\setminus\mathbb{Q}$ gives an immersion but not an
  embedding.
