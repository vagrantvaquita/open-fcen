---
titulo: Solución de Álgebra I - Práctica 1
ejercicio: 33
---

# Ejercicio 33

Debemos hallar dos funciones $f, g: \mathbb{N} \to \mathbb{N}$ tales que $f \circ g = id_{\mathbb{N}}$ y $g \circ f \ne id_{\mathbb{N}}$. 

Recordemos que para que $f \circ g = id_{\mathbb{N}}$ se cumpla, es necesario que $g$ sea inyectiva y $f$ sea sobreyectiva. Sin embargo, si $g \circ f \ne id_{\mathbb{N}}$, una de estas no puede ser biyectiva {puddu2012conjuntos}.

## Propuesta de funciones

Definimos las siguientes funciones:

*   **Función $g$:** $g(n) = n + 1$
*   **Función $f$:** $f(n) = \begin{cases} n - 1 & \text{si } n > 1 \\ 1 & \text{si } n = 1 \end{cases}$

Ambas son funciones de $\mathbb{N}$ en $\mathbb{N}$.

## Verificación de $f \circ g = id_{\mathbb{N}}$

Para cualquier $n \in \mathbb{N}$:
$$(f \circ g)(n) = f(g(n)) = f(n + 1)$$
Como $n \ge 1$, entonces $n + 1 \ge 2 > 1$. Por lo tanto, aplicamos la primera rama de $f$:
$$f(n + 1) = (n + 1) - 1 = n$$
Así, $(f \circ g)(n) = n$ para todo $n \in \mathbb{N}$, lo que significa que **$f \circ g = id_{\mathbb{N}}$**.

## Verificación de $g \circ f \ne id_{\mathbb{N}}$

Evaluemos la composición en un valor particular, por ejemplo $n = 1$:
$$(g \circ f)(1) = g(f(1))$$
Según la definición de $f$, $f(1) = 1$. Entonces:
$$g(1) = 1 + 1 = 2$$
Como $(g \circ f)(1) = 2 \ne 1$, concluimos que **$g \circ f \ne id_{\mathbb{N}}$**.

Esto ocurre porque $f$ no es inyectiva (notar que $f(1)=1$ y $f(2)=1$) y $g$ no es sobreyectiva (el 1 no pertenece a su imagen), lo que impide que la composición inversa sea la identidad.

---
Bibliografía consultada: {puddu2012conjuntos}, {uba2017fasciculo9}.
