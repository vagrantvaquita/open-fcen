---
titulo: Solución de Álgebra I - Práctica 1
ejercicio: 35
---

# Ejercicio 35

Sea $F = \{f: \{1,...,10\} \to \{1,...,10\} / f \text{ es una función biyectiva} \}$, y sea $\mathcal{R}$ la relación en $F$ definida por
$$f\mathcal{R}g \iff \exists n \in \{1,...,10\} / f(n) = 1 \text{ y } g(n) = 1$$

## i) Probar que $\mathcal{R}$ es una relación de equivalencia

Para que $\mathcal{R}$ sea una relación de equivalencia, debe cumplir con tres propiedades: reflexividad, simetría y transitividad {puddu2012conjuntos}.

* **Reflexividad:** Sea $f \in F$. Queremos ver si $f\mathcal{R}f$.
  Como $f$ es una función biyectiva del conjunto $\{1,...,10\}$ en sí mismo, entonces $f$ es sobreyectiva y el $1$ pertenece a la imagen. Esto implica que existe un único $n_{0} \in \{1,...,10\}$ tal que $f(n_{0}) = 1$. Entonces, existe $n_{0}$ tal que $f(n_{0}) = 1$ y $f(n_{0}) = 1$, por lo tanto $f\mathcal{R}f$.

* **Simetría:** Supongamos $f\mathcal{R}g$.
  Por definición, existe un $n$ tal que $f(n) = 1$ y $g(n) = 1$.
  Es inmediato que existe un $n$ tal que $g(n) = 1$ y $f(n) = 1$, luego $g\mathcal{R}f$.

* **Transitividad:** Supongamos $f\mathcal{R}g$ y $g\mathcal{R}h$.
  * Como $f\mathcal{R}g$, existe un $n_{1}$ tal que $f(n_{1}) = 1$ y $g(n_{1}) = 1$.
  * Como $g\mathcal{R}h$, existe un $n_{2}$ tal que $g(n_{2}) = 1$ y $h(n_{2}) = 1$.
    Sin embargo, dado que $g$ es una función (biyectiva), el valor $1$ tiene una única preimagen. Por lo tanto, de $g(n_{1}) = 1$ y $g(n_{2}) = 1$, se deduce que $n_{1} = n_{2}$.
    Llamemos a este valor común $n_{0} = n_{1} = n_{2}$. Entonces $f(n_{0}) = 1$ y $h(n_{0}) = 1$, por lo cual $f\mathcal{R}h$.

**¿Es antisimétrica?**
Una relación es antisimétrica si de $f\mathcal{R}g$ y $g\mathcal{R}f$ se deduce que $f = g$.
Esto no es cierto en este caso. Basta considerar dos funciones distintas que ambas envíen el mismo número al 1. Por ejemplo, $f(1)=1, f(2)=2, f(3)=3, \dots$ (la identidad) y $g(1)=1, g(2)=3, g(3)=2, g(4)=4, \dots$ (intercambia 2 y 3). Ambas envían el 1 al 1, por lo cual $f\mathcal{R}g$ y $g\mathcal{R}f$, pero $f \neq g$.

## ii) Clase de equivalencia de la identidad $Id$

La clase de equivalencia $[Id]_{\mathcal{R}}$ consiste en todas las funciones biyectivas $f \in F$ tales que existe $n$ con $f(n)=1$ e $Id(n)=1$.
Como $Id(n)=n$, la condición $Id(n)=1$ implica que $n=1$.
Entonces $[Id]_{\mathcal{R}} = \{f \in F / f(1) = 1\}$.

Tres elementos distintos de esta clase son:

1. **La propia identidad:** $Id(n) = n$ para todo $n \in \{1,...,10\}$.
2. **Una trasposición:** $f_{2}(1)=1, f_{2}(2)=3, f_{2}(3)=2$ y $f_{2}(n)=n$ para $n \ge 4$.
3. **Un ciclo:** $f_{3}(1)=1, f_{3}(2)=4, f_{3}(4)=5, f_{3}(5)=2$ y $f_{3}(n)=n$ para el resto.

Note que todas cumplen $f(1)=1$.

---

Bibliografía consultada: {puddu2012conjuntos}, {uba2017fasciculo9}.
