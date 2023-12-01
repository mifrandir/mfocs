---
title: arithmetic_progressions
date: 2023-11-24 10:39
---
# Arithmetic progression

An arithmetic progression is a set $P\subseteq\mathbb{Z}$ of the form
$$
\left\lbrace{x_0 + \ell x_1 : 0\leq \ell\leq L}\right\rbrace
$$
where $x\in\mathbb{Z}$ and $L,d\in\mathbb{N}$.

# Roth

> **Roth's theorem.** There is an absolute constant $C$ such that
> any $A\subseteq\left\lbrace{1,\ldots,N}\right\rbrace$ with
> $|A|\geq CN/\log\log N$ contains a non-trivial three term
> arithmetic progression.

# Generalised arithmetic progression

A generalised arithmetic progression is a set 
$P\subseteq\mathbb{Z}$ of the form
$$
\left\lbrace{x_0 + \ell_1 x_1 + \cdots + \ell_d x_d : 0\leq \ell_i\leq L_i}\right\rbrace
$$
where $x_0,\ldots,x_d\in\mathbb{Z}$ and $L_1,\ldots,L_d\in\mathbb{N}$.
The dimension of $P$ is $d$ and the size is $L_1\cdots L_d$.

> **Freiman's theorem.** If $|A+A|\leq K|A|$ then $A$ is contained in a GAP of dimension $d(K)$ and size $C(K)$.

# Bohr sets

Let $R\subseteq (\mathbb{Z}/q\mathbb{Z})^\times$ be finite and $\varepsilon >
0$.
Then the *Bohr set* $B(R,\varepsilon)$ is
$$
B(R,\varepsilon) = \left\lbrace{x\in\mathbb{Z}/q\mathbb{Z} : \left\Vert \frac{rx}{q}\right\Vert_{\mathbb{R}/\mathbb{Z}} \text{ for }r\in\mathbb{R}}\right\rbrace
$$
