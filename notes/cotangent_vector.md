---
title: cotangent_vector
date: 2023-10-18 14:46
---
# Definition
The *cotangent space* of $X$ at $p\in X$ is the [dual space](dual_space.md) 
$$
T^*_p X = \left({T_p X}\right)^*=\text{Hom}(T_p X,\mathbb{R}).
$$
Elements of $T^*_p X$ are
called 1-forms. (see [differential form](differential_form.md))

Let $\left\lbrace{x_i}\right\rbrace$ be local coordinates of $X$
near $x$. Then we have a basis $\left\lbrace{\frac{\partial}{\partial x_i}}\right\rbrace$ of $T_p X$ with the corresponding dual basis
$\left\lbrace{dx_i}\right\rbrace$ of $T_p^* X$.

# Properties
- Algebraically, we make the following observation: Define
  $$
  I_p = \left\lbrace{a\in C^\infty(X) : a(p) = 0}\right\rbrace.
  $$
  Then we have a canonical isomorphism 
  $$
  T_p^* X \cong \frac{C^\infty(X)}{\langle 1\rangle_{\mathbb{R}} \oplus I_p^2}
  $$
  Note that $a\in \langle 1\rangle_{\mathbb{R}} \oplus I^2_p$ is precisely the set of functions whose derivative vanishes at $p$.
