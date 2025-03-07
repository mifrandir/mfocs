---
title: quaternions
date: 2023-10-31 11:52
---
# Quaternions
The quaternions are the $\mathbb{R}$-algebra generated by $\left\lbrace{1,i,j,k}\right\rbrace$, satisfying the equations
$$
ij=k=-ji, i^2=j^2=k^2=-1.
$$

# Isomorphism to $SU(2)$
Consider the matrix algebra
$$
SU(n) = \left\lbrace{ A \in GL(n,\mathbb{C}) : \overline{A}^\top A = I}\right\rbrace
$$
and the Pauli matrices $X,Y,Z\in SU(2)$ given by
$$
X=\begin{pmatrix} 0 & 1 \\ 1 & 0\end{pmatrix},
Y=\begin{pmatrix} 0 & -i \\ i & 0\end{pmatrix},
Z=\begin{pmatrix} 1 & 0 \\ 0 & -1\end{pmatrix}.
$$

Then there is an isomorphism $\mathbb{H}\to SU(2)$ given by
$$
1 \mapsto I, i \mapsto iZ, j\mapsto iY, k\mapsto iX.
$$
