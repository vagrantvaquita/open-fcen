---
titulo: Álgebra I - Práctica 1: Conjuntos, Relaciones y Funciones
categoria: Lógica y Demostraciones
practica: 1
ejercicio: 11
---

# Solución del Ejercicio 11

Para demostrar que una proposición de la forma $\forall x \in A, P(x)$ es falsa, es suficiente con encontrar un **contraejemplo**: un elemento $x_0 \in A$ tal que la propiedad $P(x_0)$ no se cumpla (es decir, que $\sim P(x_0)$ sea verdadera) {puddu2012conjuntos}.

### i) $\forall n \in \mathbb{N}, n \text{ no es un número entero}$
La definición de los conjuntos numéricos establece que los números naturales son un subconjunto de los enteros ($\mathbb{N} \subset \mathbb{Z}$). Por lo tanto, cualquier número natural sirve como contraejemplo.
- **Contraejemplo:** Sea $n = 1$.
- $1 \in \mathbb{N}$, pero $1$ **es** un número entero ($1 \in \mathbb{Z}$).
- La afirmación "$1$ no es un entero" es falsa.

### ii) $\forall x, y \in \mathbb{R}^+, \sqrt{x + y} = \sqrt{x} + \sqrt{y}$
Buscamos dos números reales positivos que no cumplan la igualdad.
- **Contraejemplo:** Sean $x = 1$ e $y = 1$.
- $\sqrt{x + y} = \sqrt{1 + 1} = \sqrt{2} \approx 1,4142...$
- $\sqrt{x} + \sqrt{y} = \sqrt{1} + \sqrt{1} = 1 + 1 = 2$
- Como $\sqrt{2} \neq 2$, la proposición es falsa {uba2017fasciculo9}.

### iii) $\forall x \in \mathbb{R}, x^2 > 4 \Rightarrow x > 2$
Recordemos que una implicación $p \Rightarrow q$ es falsa únicamente cuando el antecedente ($p$) es verdadero y el consecuente ($q$) es falso.
- **Contraejemplo:** Sea $x = -3$.
- Antecedente: $x^2 = (-3)^2 = 9$. Como $9 > 4$, el antecedente es **verdadero**.
- Consecuente: $x = -3$. Como $-3 \ngtr 2$, el consecuente es **falso**.
- Por lo tanto, la implicación es falsa para $x = -3$. (Note que cualquier $x \le -2$ sirve como contraejemplo).
