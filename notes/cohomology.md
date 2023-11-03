---
title: cohomology
date: 2023-10-27 14:37
---
# Cohomology
Consider the contravariant functor
$$
\text{Hom}(-,R):\text{Ch}(\mathcal A)\to\text{Ch}(\mathcal A)^{\text{op}}.
$$
(see [chain_complexes](chain_complexes.md))

The *cohomology functor* $H^*:\text{Ch}(\mathcal A)^\text{op}\to\text{Graded}_{\mathbb{Z}}(\mathcal A)$ is given by 
$$
\text{Ch}(\mathcal A)
\xrightarrow{\text{Hom}(-,R)}\text{Ch}(\mathcal A)^{\text{op}}
\xrightarrow{H_*}\text{Graded}_{\mathbb{Z}}(\mathcal A)^{\text{op}}.
$$

In particular, if $\mathcal A=\text{Ab}$, we have
$$
\text{Graded}_{\mathbb{Z}}(\text{Ab})^{\text{op}}\cong\text{Graded}_{\mathbb{Z}}(\text{Ab})
$$
so $H^*:\text{Ch}(\text{Ab})\to \text{Graded}_{\mathbb{Z}}(\text{Ab})$
and similarly for simplicial and singular cohomologies.

