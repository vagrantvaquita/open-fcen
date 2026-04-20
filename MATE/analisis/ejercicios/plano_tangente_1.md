---
category: plano tangente
---
Decidir si $f$ es diferenciable en $(1,2)$ y usar el plano tangente para dar una aproximación de $f(1.1, 1.9)$.

$$
f(x,y) = 2x^2 + y^2
$$

---

Las derivadas parciales son:

$$
\frac{\partial{f}}{\partial{x}}(x,y) = 4x
$$

$$
\frac{\partial{f}}{\partial{y}}(x,y) = 2y
$$

Evaluamos $f$ y sus derivadas parciales en el punto $(1,2)$:

$$
f(1,2) = 6
$$

$$
\frac{\partial{f}}{\partial{x}}(1,2) = 4
$$

$$
\frac{\partial{f}}{\partial{y}}(1,2) = 4
$$

Recordamos la definicion del plano tangente:

$$
{\mathbb P}(x, y) = f(x_0,y_0) + a(x - x_0) + b(y - y_0)
$$

Entonces queda:

$$
{\mathbb P}(x, y) = 6 + 4(x - x_0) + 4(y - y_0)
$$

Para verificar que es el plano correcto calculamos el limite:

$$
\lim_{(x,y) \to (1,2)} \frac{2x^2 + y^2 - [6 + 4(x - x_0) + 4(y - y_0)]}{\sqrt{(x-x_0)^2 + (y-y_0)^2}} = 0
$$

Para ayudar a calcular el limite vamos a reescribir $x,y$ como potencias de $(x-1)$ y $(y-2)$.

$$
x-1 = x-1+1 = ((x-1) + 1)^2 = (x-1)^2 - 2(x-1) + 1
$$

$$
y-2 = x-2+2 = ((x-2) + 2)^2 = (x-2)^2 - 2\cdot2(x-2) + 4
$$

Con esta igualdad continuamos:

$$
\lim_{(x,y) \to (1,2)} \frac{2(x-1)^2 - \cancel{4(x-1)} + \cancel{2} + (y-2)^2 - \cancel{4(y-2)} + \cancel{4} - \cancel{6} - \cancel{4(x - 1)} - \cancel{4(y - 2)}}{\sqrt{(x-1)^2 + (y-2)^2}} = 0
$$

Luego de cancelar:

$$
\lim_{(x,y) \to (1,2)} \frac{2(x-1)^2 + (y-2)^2}{\sqrt{(x-1)^2 + (y-2)^2}} = 0
$$

Para ver que tiende a cero reescribimos multiplicando por terminos acotados:

$$
\lim_{(x,y) \to (1,2)} 2(x-1)\frac{(x-1)}{\sqrt{(x-1)^2 + (y-2)^2}} + (y-2) \frac{(y-2)}{\sqrt{(x-1)^2 + (y-2)^2}} = 0
$$

Identifico que:

$$
|\frac{(x-1)}{\sqrt{(x-1)^2 + (y-2)^2}}| \le 1
$$

y

$$
|\frac{(y-2)}{\sqrt{(x-1)^2 + (y-2)^2}}| \le 1
$$

Por lo que queda acotado

$$
\lim_{(x,y) \to (1,2)} 2(x-1)\frac{(x-1)}{\sqrt{(x-1)^2 + (y-2)^2}} + (y-2) \frac{(y-2)}{\sqrt{(x-1)^2 + (y-2)^2}} \le \lim_{(x,y) \to (1,2)} 2(x-1) + (y-2) = 0
$$

Y como $(x-1)$ y $(y-2)$ tienden a 0 entonces

$$
\lim_{(x,y) \to (1,2)} 0 + 0 = 0
$$

Por ultimo evaluo el punto $(1.1, 1.9)$ en el plano tangente.

$$
\mathbb{P}(1.1, 1.9) = 6 + 4 \cdot (0.1) + 4 \cdot (-0.1) = 6
