---
title: matrix_groups
date: 2023-11-01 14:46
---
# Matrix Lie groups
- For all $g\in G$, $X\in\text{Lie}(G)$, $\exp(gX{g}^{-1})=g\exp(X){g}^{-1}$.

1. $G=GL(n,\mathbb{R})$
   - non-compact
   - all matrices: $\text{Lie}G=M_n(\mathbb R)$
   - $\text{Ad}A(X)=AX{A}^{-1}$
   - $\text{ad}X(Y)=[X,Y]=XY-YX$
2. $G=O(n)=\left\lbrace{A\in GL(n,\mathbb{R}) : A^\top = {A}^{-1}}\right\rbrace$
   - disconnected
3. $G=SO(n)=\left\lbrace{A\in O(n) : \det A = 1}\right\rbrace$
   - connected
   - $\left\lbrace{X\in M_n(\mathbb{R}) : X^\top = -X}\right\rbrace$
   - $\tilde{SO(3)}=SU(2)$.
4. $G=SL(n,\mathbb{R})$
   - non-compact
   - $\text{Lie}G = \left\lbrace{A \in M_n(\mathbb{R}) : \text{tr} A = 0}\right\rbrace$
5. $G=SU(2)$
   - Pauli matrices: $\text{Lie}G = \text{span}\left\lbrace{X,Y,Z}\right\rbrace$
