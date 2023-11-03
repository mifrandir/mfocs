---
title: tangent_vector
date: 2023-10-16 10:41
---
# Definition
A *tangent vector* at $p\in X$ is a map $v:C^\infty(X)\to\mathbb{R}$
such that, for all smooth $a,b\in C^\infty(X)$, $v(ab)=a(p)v(b)+b(p)v(a)$.

The tangent vectors at $p$ form an $n$-dimensional $\mathbb{R}$-vector
space $T_p X$ with basis $\left\lbrace{\frac{\partial}{\partial x_i}}\right\rbrace$ where $\left\lbrace{x_i}\right\rbrace$ are local coordinates near $p$.

# Alternative definition
Let $\alpha$ be a curve in $M$ through $p$ Then the *tangent vector* to
$\alpha$ at $0$ is
$$
\alpha'(0):f\mapsto (f\circ\alpha)'(0)\in\mathbb{R},
$$
sending smooth functions $f:U\to\mathbb{R}$ with $p\in U$ to real numbers
$(f\circ\alpha)'(0)$:
$$
\left\lbrace{\text{functions $M\to\mathbb{R}$, smooth at $p$}}\right\rbrace\to\mathbb{R}
$$

# Properties
- Consider a [Lie group](lie_groups.md) $G$ which arises as the pre-image of a regular value ${F}^{-1}(e)$. Then $T_e G = \ker dF_e$. (Hitchin notes 3.2.1)
