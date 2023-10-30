---
title: flow_of_a_vector_field
date: 2023-10-20 10:29
---
# Integral curve
Let $X$ be a [vector field](vector_field.md) on $M$ and $p\in M$. There exists
a neighbourhood $V\ni p$ such that, for all $q\in V$, there is a unique cuve
$\alpha_q:(-\epsilon,\epsilon)\to M$ such that $\alpha_q(0)=q$ and
$$
\alpha_q'(t)=X(\alpha_q(t)).
$$
This may be thought of as integration of $X$.

# Flow
The flow of $X$ near $p$ is the family of smooth maps
$$
\left\lbrace{\phi_t : V\to M:t\in(-\epsilon,\epsilon)}\right\rbrace
$$
given by $\phi_t(q) = \alpha_q(t)$.

Notice that $\phi_t$ is the identity on $V$.

> A vector fields vectors point in the direction of the flow at every point.

