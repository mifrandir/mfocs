---
title: chain-complexes
date: 2023-10-09 10:54
---

# Definition

A chain complex is a family of $R$-modules
$\left\lbrace{\mathbf{C}}\right\rbrace_{n\in\mathbb{Z}}$
together with $R$-module maps $d_n:\mathbf{C}_n\to\mathbf{C}_{n+1}$
such that each $d\circ d:\mathbf C_n\to\mathbf{C}_{n-2}=0$.

# Notation

- $d_n$ are *differentials*.
- $Z_n = Z_n\left({\mathbf{C}}\right)=\ker\left({d_n}\right)$ is the module of $n$-cycles.
- $B_n=B_n\left({\mathbf{C}}\right)=\text{im}(d_{n+1})$ is the module of $n$-boundaries.
- $H_n=H_n\left({\mathbf{C}}\right)=Z_n/B_n$ is the $n$th homology module.

# Observations

- For all $n$, $0 \subseteq B_n \subseteq Z_n \subseteq C_n$ as $d_{n+1}\circ d_n = 0$ so $B_n\subseteq Z_n$.

