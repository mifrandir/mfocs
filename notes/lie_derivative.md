---
title: lie_derivative
date: 2023-10-20 10:20
---
# Lie derivative
Let $X,Y$ be [vector fields](vector_field.md) on $M$ and let $\phi$ be the [flow](flow_of_a_vector_field.md) of $X$. Then the
*Lie derivative of $Y$ with respect to $X$* is 
$$
L_X Y(p) = \lim_{t\to 0}\frac{(\phi_{-t})_*(Y(\phi_t(p))-Y(p)}{t}.
$$
$$
L_X Y(p) = \left.\frac{d}{dt}\right\vert_{t=0}\left({}\right)
$$

# Properties
- $L_X Y$ defines a vector field on $M$.
- $L_X Y=[X,Y]$.
