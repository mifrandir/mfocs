---
title: exponential_map
date: 2023-10-23 14:52
---
# Exponential map
The *exponential map* $\exp:\text{Lie}(G)\to G$ is given by
$$
X\mapsto \alpha^e(1)
$$
where $\alpha_e$ is the [integral curve](flow_of_a_vector_field.md) of $X$
through $e$.

# Properties
- For a Lie group homomorphism $F:G\to H$, $\exp(dF_e(X_e)) = F(\exp(X_e))$.
- Let $G$ be connected. Then the following are equivalent:
  1. $G$ is abelian, and
  2. $\exp : \text{Lie}(G)\to G$ is a group homomorphism,
  3. $G\cong T^k \times \mathbb{R}^{n-k}$
