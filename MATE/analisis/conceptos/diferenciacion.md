# Diferenciacion 

## Funciones de una variable

$f \colon \mathbb{R} \to \mathbb{R}$, decimos que es derivable en $x_0$ si existe:

$$
f(x_0) = \lim{f \to 0} \frac{f(x_0+h) - f(x_0)}{h}
$$

## Funciones de dos variables

Una funcion de dos variables es diferenciable en un punto si cumple dos definiciones:

1. Existen las derivadas parciales en ese punto.
2. El limite del error sobre la taza de cambio es 0.

Definicion: Dada $f: D \subseteq \mathbb{R^2} \to \mathbb{R}$ y $(x_0, y_0) \in D$ decimos que $f$ es *diferenciable* en $(x_0, y_0)$ si existe $a, b \in \mathbb{R}$:

$$
\lim_{(x,y) \to (x_0,y_0)} \frac{f(x,y) - f(x_0, y_0) - a(x-x_0) - b(y, y_0)}{\sqrt{(x-x_0)^2 + (y-y_0)^2}} = 0
$$

o lo que es lo mismo:

$$
\lim_{(x,y) \to (x_0,y_0)} \frac{f(x,y) - [f(x_0, y_0) + \frac{\partial f}{\partial x}(x_0, y_0)(x-x_0) + \frac{\partial f}{\partial y}(x_0, y_0)(y, y_0)]}{\sqrt{(x-x_0)^2 + (y-y_0)^2}} = 0
$$

Observaciones:

* El punto $(x_0, y_0)$ deber ser diferenciable para que exista un plano tangente.
* Deben existir las dos derivadas parciales.
* El limite del plano cuando $f$ tiende al punto $(x_0,y_0)$ debe ser $0$.

### Teorema de la condicion suficiente

Si $f$ es una funcion continua y sus derivadas parciales son funciones continuas entonces `f` es diferenciable.

Definicion: $f$ se dice de clase $\mathbb{C}^1$ si $f$ es continua y sus derivadas parciales existen y son continuas. La clase implica diferenciabilidad.

$$
f \in \mathbb{C}^1 \implies diferenciable
$$

Teorema: Si $f$ es diferenciable en $p_0$ entonces $f$ es continua en $p_0$. El reciproco tambien vale.

Corolario: Si $f$ no es continua en $p_0$ entonces $f$ no es diferenciable en $p_0$.

