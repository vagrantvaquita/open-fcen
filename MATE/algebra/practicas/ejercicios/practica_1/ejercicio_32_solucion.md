---
titulo: Solución de Álgebra I - Práctica 1
ejercicio: 32
---

# Ejercicio 32

Para hallar las composiciones $f \circ g$ y $g \circ f$, debemos recordar la definición: $(f \circ g)(x) = f(g(x))$, lo cual requiere que el imagen de $g$ esté contenida en el dominio de $f$ {puddu2012conjuntos}.

## Parte i)
$f: \mathbb{R} \to \mathbb{R}, f(x) = 2x^{2}-18$ y $g: \mathbb{R} \to \mathbb{R}, g(x) = x+3$.

*   **Cálculo de $f \circ g$:**
    $$(f \circ g)(x) = f(g(x)) = f(x+3) = 2(x+3)^{2} - 18$$
    Desarrollando el binomio:
    $$2(x^{2} + 6x + 9) - 18 = 2x^{2} + 12x + 18 - 18 = 2x^{2} + 12x$$
    Luego, $f \circ g: \mathbb{R} \to \mathbb{R}, (f \circ g)(x) = 2x^{2} + 12x$.

*   **Cálculo de $g \circ f$:**
    $$(g \circ f)(x) = g(f(x)) = g(2x^{2}-18) = (2x^{2}-18) + 3 = 2x^{2} - 15$$
    Luego, $g \circ f: \mathbb{R} \to \mathbb{R}, (g \circ f)(x) = 2x^{2} - 15$.

## Parte ii)
$f, g: \mathbb{N} \to \mathbb{N}$ con $f(n) = \begin{cases} n-2 & \text{si } n \text{ es divisible por } 4 \\ n+1 & \text{si } n \text{ no es divisible por } 4 \end{cases}$ y $g(n) = 4n$.

*   **Cálculo de $f \circ g$:**
    Como $g(n) = 4n$ siempre es divisible por $4$, aplicamos la primera rama de $f$:
    $$(f \circ g)(n) = f(4n) = 4n - 2$$
    Luego, $f \circ g: \mathbb{N} \to \mathbb{N}, (f \circ g)(n) = 4n - 2$.

*   **Cálculo de $g \circ f$:**
    Analizamos según la divisibilidad de $n$ por $4$:
    $$(g \circ f)(n) = \begin{cases} g(n-2) & \text{si } n \text{ es divisible por } 4 \\ g(n+1) & \text{si } n \text{ no es divisible por } 4 \end{cases}$$
    Sustituyendo $g$:
    $$(g \circ f)(n) = \begin{cases} 4(n-2) = 4n - 8 & \text{si } n \in 4\mathbb{N} \\ 4(n+1) = 4n + 4 & \text{si } n \notin 4\mathbb{N} \end{cases}$$

## Parte iii)
$f: \mathbb{R} \to \mathbb{R} \times \mathbb{R}, f(x) = (x+5, 3x)$ y $g: \mathbb{N} \to \mathbb{R}, g(n) = \sqrt{n}$.

*   **Cálculo de $f \circ g$:**
    La composición está bien definida porque $Im(g) \subseteq \mathbb{R} = Dom(f)$.
    $$(f \circ g)(n) = f(\sqrt{n}) = (\sqrt{n}+5, 3\sqrt{n})$$
    Luego, $f \circ g: \mathbb{N} \to \mathbb{R} \times \mathbb{R}, (f \circ g)(n) = (\sqrt{n}+5, 3\sqrt{n})$.

*   **Cálculo de $g \circ f$:**
    Notemos que $Im(f) \subseteq \mathbb{R} \times \mathbb{R}$, mientras que $Dom(g) = \mathbb{N}$. Para que la composición $g \circ f$ tenga sentido, el dominio de $g$ debería ser un conjunto que contenga pares ordenados de números reales, lo cual no ocurre aquí. Por lo tanto, **$g \circ f$ no está definida**.

---
Bibliografía consultada: {puddu2012conjuntos}, {uba2017fasciculo9}.
