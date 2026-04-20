# Gradiente

## Notación

Para $f: D \subseteq \mathbb{R^2} \to \mathbb{R}$

$$
\nabla{f} = (\frac{\partial{f}}{\partial{x}}, \frac{\partial{f}}{\partial{y}})
$$

Es el gradiente de $f$.

## En el plano tangente

Permite reescribir el plano tangente de la siguiente manera:

$$
{\mathbb P}(x, y) = f(x_0,y_0) + [(\frac{\partial{f}}{\partial{x}}, \frac{\partial{f}}{\partial{y}}) \cdot (x-x_0, y-y_0)]
$$

$$
{\mathbb P}(x, y) = f(x_0,y_0) + \nabla{f}(x-x_0, y-y_0)]
$$

Si pensamos en un punto $p$ y $p_0$:

$$
\mathbb{P}(p) = f(p_0) + \nabla{f}(p_0) \cdot (p - p_0)
$$

Y podemos verificar el limite con:

$$
\lim_{p \to p0} \frac{f(p) - [f(p_0) + \nabla{f}(p_0) \cdot (p - p_0)]}{\|(p - p0)\|}
$$