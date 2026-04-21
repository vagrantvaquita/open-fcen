Este ejercicio es fundamental para entender cómo las propiedades de funciones de una sola variable se "heredan" al espacio de varias variables.

Primero demostramos la continuidad de $f(x,y) = g(x)$, por definicion:

$$
\forall \epsilon > 0, \exist \delta > 0 : 0 \le |x-a| < \delta \implies |g(x) - g(a)| < \epsilon
$$

Y ahora queremos ver que:

$$
\lim_{(x,y) \to (a,y_0)} f(x,y) = g(x) = f(a,y_0) = g(a)
$$

Queremos ver que:

$$
|\sqrt{(x-a)^2+(y-y_0)^2}|<\delta \implies |f(x,y) - f(a,y_0)| < \epsilon
$$

Por la hipotesis de $g$ ya sabemos que es continua:

$$
|x-a|<\delta
$$

Lo que implica:

$$
|g(x) - g(a)| < \epsilon
$$

Que es igual a:

$$
|f(x,y) - f(a,y_0)| < \epsilon
$$

$\square$ Queda demostrado que con cualquier $y_0$ la funcion $f$ tambien es continua en la recta $x=a$. Las funciones que "extruyen" una curva de una variable a lo largo de otro eje conservan la continuidad de la curva original.
