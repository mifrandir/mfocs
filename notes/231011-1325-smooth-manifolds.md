---
title: smooth-manifolds
date: 2023-10-11 13:25
---

# Definitions

- A *topological manifold of dimension $n$* is a topological space $X$
  that is
  1. Hausdorff,
  2. second countable, and
  3. locally homeomorphic to $\mathbb{R}^n$.
- A *chart* on a topologial space $X$ is a open $U\subseteq\mathbb{R}^n$
  and a map $\phi:U\to X$ such that
  1. $\phi\left({U}\right)\subseteq X$, and
  2. $\phi:U\to\phi(U)$ is a homeomorphism.
- Two charts $\phi:U\to X$ and $\psi:V\to X$ are compatbile if, and only if,
  both ${\psi}^{-1}\circ\phi$ and ${\phi}^{-1}\circ\psi$ are smooth.
- An *atlas* on $X$ is a family of charts that are pairwise compatible and
  whose images cover $X$.
- An atlas is *maximal* if its not a proper subset of another atlas.
- A *differentiable manifold* is a topological manifold with a maximal atlas.

# Examples

- $S^1$ is a topological manifold. The usual smooth structure is uniquely
  defined by the atlas $\left\lbrace{\phi,\psi:\left({0,1}\right)}\to
  S^1\right\rbrace$ where
  $$
  \phi(0,1)= S^1\setminus\left\lbrace{(0,1)}\right\rbrace,
  \psi(0,1)=S^1\setminus\left\lbrace{(1,0)}\right\rbrace.
  $$
- $S^n$ is a smooth manifold analogous to the above, replacing $(0,1)$ with
  $D^n$.
- $\mathbb{R}^n$ is a smooth manifold with the obvious structure.
