Para $f$ (1):

Para determinar el conjunto de puntos donde esta función es continua, debemos analizar la naturaleza de sus componentes y las restricciones de su dominio.

La función $f(x,y)$ es una función racional compuesta, formada por:

* Numerador: x⋅y, que es un polinomio. Los polinomios son continuos en todo $\mathbb{R^2}$.
* Denominador: $1+e^{x−y}$. Aquí tenemos:
  * Una constante $(1)$.
  * Una función exponencial $(e^u)$.
  * Un polinomio en el exponente $(x−y)$.

Todas estas funciones son continuas en sus respectivos dominios. Por lo tanto, el cociente será continuo en todos los puntos donde el denominador sea distinto de cero.

Debemos encontrar si existen puntos (x,y) tales que:

$$1+e^{x−y}=0$$

Por lo tanto:

$$e^{x−y}=-1$$

Pero $e^u$ es estrictamente positiva entonces el denominador nunca sera cero.

$\square$ Queda demostrado que $f$ es continua para todos los puntos en $\mathbb{R}$
$$
C=\{(x,y) \in \mathbb{R^2}\}
$$

---

Para $f$ (2):

Se trata de una funcion racional (cociente de polinomios).

* Numerador: Es un polinomio de grado 4. Los polinomios son continuos en todo $\mathbb{R}$.
* Denominador: Es un polinomio de grado 2 continuos en todo $\mathbb{R}$.

Por el teorema de continuidad de funciones racionales, la función será continua en todos los puntos de su dominio, es decir, en todos aquellos donde el denominador no se anule.

Identificamos los puntos donde el denominador es cero:

$$
1-x^2-y^2=0
$$

Reordenamos:

$$
x^2+y^2=1
$$

Que es la ecuacion de una circunferencia unitaria centrada en $(0,0)$. $\square$ Queda demostrado que la funcion tiene conjunto de continuidad:

$$
C = \{(x,y) \in \mathbb{R^2}: x^2+y^2 \ne 1\}
$$

---

Para $f$ (3):

Necesitamos que el limite en el entorno tienda a $f(0,0)=1$ si nos aproximamos por los ejes el limite por los ejes es $0$. Observar tambien que el grado del denominador es mayor al del numerador.

Probar el limite por acotación:

Queremos ver si $|f(x,y)| \to 0$

$$
|f(x,y)=|\frac{x^2y^3}{2x^2+y^4}|
$$

Podemos usar la relacion $2x^2 \le 2x^2 + y^4$. Entonces:

$$
y^3 \cdot \frac{x^2}{2x^2+y4} \le y^3 \cdot \frac{x^2}{2x^2} = y^3 \cdot \frac{1}{2}
$$

Como $|y^3| \to 0$ cuando $y \to 0$, por el Teorema del Sándwich (o confrontación), el límite de la función en el origen es 0.
