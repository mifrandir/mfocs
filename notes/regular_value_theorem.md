---
title: regular value theorem
date: 2023-10-12 09:58
---
# Regular values
Let $f:M\to N$ be a differentiable map.

A *regular value* of $f$ is a $q\in N$ for which, at all points
$p\in {f}^{-1}(q)$, the differential $d_p f:T_p M \to T_{f(p)}N$ is surjective.

> If $q\in N$ is a regular value, then
> 1. ${f}^{-1}(q)$ is a submanifold of $M$
> 2. If ${f}^{-1}(q)$ is non-empty, then
>   $$\dim(Y) = \dim(X) - \dim\left({{f}^{-1}(q)}\right).$$

> **Sard**. If $F:M\to N$ and $S\subseteq N$ with $N\setminus S$ of measure zero, then, for all $F(p)\in S$, $dF_p$ is surjective.
> 
> I.e. for almost all $q\in N$, ${F}^{-1}\left\lbrace{q}\right\rbrace$ is a submanifold.
