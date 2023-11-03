---
title: one_parameter_group_of_diffeomorphisms
date: 2023-10-30 11:05
---
# One parameter group of diffeomorphisms
A *one-parameter group of diffeomorphisms* is a smooth map $\phi : \mathbb{R}\times X\to X$ such that
1. $\phi_t = \phi(t,-):X\to X$ is a diffeomorphism, and
2. $\phi_{s+t}=\phi_s\circ\phi_t$.

> There is a group homomorpshism $\mathbb{R}\to\text{Diff}(M)$ given by $t\mapsto \phi_t$.

# Induced vector field
Every such group $\phi$ induces a [vector field](vector_field.md) given by
$$
X(f) = \left.\frac{d}{dt}\right\vert_{t=0}(f\circ\phi_t).
$$

> If $M$ is compact, then there is a 1-1 correspondence between 1-parameter groups and vector fields.
