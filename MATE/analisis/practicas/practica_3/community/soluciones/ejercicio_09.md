Comenzamos observando que el grado del numerador es estrictamente mas grande que el del denominador $\frac{grado 3}{grado 2}$. Por lo que sospechamos que el limite tiende a $0$.

Para resolver el ejercicio buscamos que:

$$
\lim_{(x,y) \to (1,0)} |f(x) - a| = 0
$$

Para esto primero transladamos:

$$
\begin{aligned}
x &= h + 1 \\
y &= k
\end{aligned}
$$

Entonces nos queda:

$$
\lim_{(x,y) \to (1,0)} \frac{h^3 cos(k)}{h^2+k^2} = a
$$

Trabajamos por definicion:

$$
\begin{aligned}
\lim_{(x,y) \to (1,0)} |\frac{h^3 cos(k)}{h^2+k^2}| &=|h| \cdot |cos(k)| \cdot |\frac{h^2}{h^2+k^2}| \\
&\le \delta \cdot (1) \cdot (1) \\
0 &\le \delta
\end{aligned}
$$

Por el Teorema del Sándwich, como el lado derecho tiende a $0$, el límite de nuestra función es $0$. Para que la función sea continua, el valor de la función en el punto debe coincidir con el límite $a$. La función es continua en $(1,0)$ si $a=0$.
