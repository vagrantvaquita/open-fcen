Comenzamos observando el comportamiento de la función cuando nos aproximamos al punto $(2,0)$. Notamos que el factor $(x-2)$ tiende a anularse, mientras que el término del seno, independientemente de la complejidad de su argumento, se mantiene siempre acotado entre $-1$ y $1$. Nuestra sospecha inicial es que el producto de un infinitésimo por una función acotada resultará en cero.

Para demostrar esto formalmente mediante la definición $\epsilon-\delta$, realizaremos una traslación de variables que nos permita trabajar en el origen:

*   $h = x - 2$
*   $k = y$

De esta manera, el límite que queremos estudiar es:

$$
\lim_{(h,k) \to (0,0)} h \cdot \sin\left(\frac{h+2}{(h+2)^2+k^2}\right) = 0
$$

Planteamos la definición formal. Queremos ver que para todo $\epsilon > 0$, existe un $\delta > 0$ tal que:

$$
0 < \sqrt{h^2+k^2} < \delta \implies |h \cdot \sin\left(\frac{h+2}{(h+2)^2+k^2}\right) - 0| < \epsilon
$$

Trabajamos con el valor absoluto de la función. Dado que $|\sin(u)| \le 1$ para cualquier argumento real $u$, podemos acotar la expresión de la siguiente manera:

$$
|h| \cdot \left|\sin\left(\frac{h+2}{(h+2)^2+k^2}\right)\right| \le |h| \cdot 1 = |h|
$$

Por otro lado, recordamos la relación fundamental entre las componentes de un vector y su norma, donde $|h| \le \sqrt{h^2+k^2}$. Entonces, si establecemos la condición de entorno $\sqrt{h^2+k^2} < \delta$, llegamos a la siguiente cadena de desigualdades:

$$
|f(x,y) - 0| \le |h| \le \sqrt{h^2+k^2} < \delta
$$

Para asegurar que se cumpla la tesis $|f(x,y) - 0| < \epsilon$, basta con elegir:

$$
\delta = \epsilon
$$

En conclusión, hemos encontrado una relación de dependencia para $\delta$ que satisface la definición de límite en todo entorno del punto $(2,0)$.

$\square$ Queda así demostrada la existencia del límite por definición.
