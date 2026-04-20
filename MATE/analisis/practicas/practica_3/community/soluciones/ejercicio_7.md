Para $f$ (1):

$$
(1) \quad \lim_{(x,y) \to (0,0)} \frac{x^4y^4}{(x^2+y^4)^3}
$$

Cuando nos aproximamos al punto $(0,0)$ por una linea recta de grafico $(x,mx)$ tenemos que:

$$
\lim_{x \to 0} \frac{x^4m^4x^4}{(x^2+mx^4)^3}
$$

Considerando el binomio al cubo:

$$
(a+b)^3=a^3 + 3a^2b+3ab^2+b^3
$$

Entonces:

$$
\lim_{x \to 0} \frac{m^4x^8}{x^6+3x^8m^4+3x^{10}m^8+x^{12}m^{12}}
$$

$$
\lim_{x \to 0} \frac{m^4\cancel{x^8}x^2}{\cancel{x^6}(1+3x^2m^4+3x^{4}m^8+x^{6}m^{12})}
$$

$$
\lim_{x \to 0} \frac{0}{1} = 0
$$

Pero si llego al punto a traves de la curva $(y^2, y)$ entonces:

$$
\lim_{y \to 0} \frac{y^{2^4}y^4}{(y^{2^2}+y^4)^3}
$$

$$
\lim_{y \to 0} \frac{y^{12}}{2^3y^{4^3}}
$$

$$
\lim_{y \to 0} \frac{\cancel{y^{12}}}{8\cancel{y^{12}}} = \frac{1}{8}
$$

$\square$ Queda demostrado que la funcion $f$ (1) no tiene limite.

---

Para $f$ (2), usando $(x, mx)$:

$$
(2) \quad f(x,y)=\frac{x^2}{x^2+y^2-x}
$$

$$
\lim_{x \to 0} f(x,y)=\frac{x^2}{x^2+mx^2-x}
$$

$$
\lim_{x \to 0} f(x,y)=\frac{x^2}{(m^2+1)x^2-x}
$$

$$
\lim_{x \to 0} f(x,y)=\frac{\cancel{x^2}x}{\cancel{x}[(m^2+1)x-1]}
$$

$$
\lim_{x \to 0} f(x,y)=\frac{0}{0-1} = 0
$$

Pero si me muevo al punto $(0,0)$ por la curva $(y^2,y)$:

$$
\lim_{y \to 0} f(x,y)=\frac{y^4}{y^4+\cancel{y^2-y^2}}=\frac{y^4}{y^4} = 1
$$

Que es lo mismo que usar la curva $(x, x^{\frac{1}{2}})$:

$$
\lim_{x \to 0} f(x,y)=\frac{x^2}{x^2+\cancel{x-x}}=\frac{x^2}{x^2} = 1, x \geq 0
$$

$\square$ Queda demostrado que la funcion $f$ (2) no tiene limite.
