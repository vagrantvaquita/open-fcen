Sea:

$$
f(x,y) = \begin{cases}
\frac{x^2y}{x^2+y^2} & \text{if } (x, y) \neq (0, 0) \\
0 & \text{if } (x, y) = (0, 0)
\end{cases}
$$

Determinar si $f$ es diferenciable en $(0, 0)$.

---

Como en el punto que quiero evaluar la funcion es 0 entonces debo utilizar la definicion del limite del cociente incremental para determinar las derivadas parciales. Recordemos:

$$
f_x(x,y) = \lim_{h \to 0} \frac{f(x + h, y) - f(x, y)}{h}
$$

Entonces aplico a la derivada parcial de $f_x$:

$$
\lim_{h \to 0} \frac{f(0 + h, 0) - f(0,0)}{h}
$$

Como $f$ en el punto $(0,0)$ vale $0$ entonces:

$$
\lim_{h \to 0} \frac{\frac{h^2 \cdot 0}{h^2} - 0}{h} = 0
$$

Y de manera analoga para $f_y$:

$$
\lim_{h \to 0} \frac{f(0, 0 + h) - f(0,0)}{h} = 0
$$

Por lo que

$$
\nabla{f}=(0,0)
$$

Una vez que verifique la existencia de las derivadas parciales debo encontrar el plano tangente.

$$
\mathbb{P}(x,y) = f(0,0) + \nabla{f}(0,0)(x-x_0, y-y_0)
$$

Como tanto $f$ como $\nabla{f}$ evaluados en el punto $(0,0)$ dan $0$ entonces:

$$
\mathbb{P}(x, y) = 0
$$

Lo que significa que el plano vive en $z=0$ o en "el piso". Por ultimo calculamos el limite del plano tangente.

$$
\lim_{(x,y) \to (0,0)} \frac{f(x,y) - 0}{\sqrt{x^2 + y^2}}
$$

Reemplazamos $f$

$$
\lim_{(x,y) \to (0,0)} \frac{\frac{x^2y}{x^2+y^2}}{\sqrt{x^2 + y^2}}
$$

Que es lo mismo que:

$$
\lim_{(x,y) \to (0,0)} \frac{x^2y}{(x^2+y^2)^1} \cdot \frac{1}{\sqrt{x^2 + y^2}}
$$

$$
\lim_{(x,y) \to (0,0)} \frac{x^2y}{(x^2+y^2)^1} \cdot \frac{1}{(x^2 + y^2)^\frac{1}{2}}
$$

$$
\lim_{(x,y) \to (0,0)} \frac{x^2y}{(x^2+y^2)^\frac{3}{2}}
$$

Como ahora el numerados y denominador me quedan de potencia 3, sospecho que el limite no existe. Entonces busco una direccion donde no de 0. Busco en la direccion $y = x$

$$
\lim_{x \to 0^+} \frac{x^3}{(2x^2)^\frac{3}{2}}
$$

Cuidado de simplificar $2 \cdot \frac{3}{2}$ porque solo vale para los $x$ positivos, entonces limito a acercarme a 0 por la derecha (numeros positivos).

$$
\lim_{x \to 0^+} \frac{\cancel{x^3}}{2^\frac{3}{2}\cancel{x^3}} = \frac{1}{2^\frac{3}{2}}
$$

$\square$ Queda demostrado que el limite no existe y no se cumple la condicion 2 de deferencialidad ya que no hay un plano tangente.