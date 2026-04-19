---
titulo: Álgebra I - Práctica 1 Conjuntos, Relaciones y Funciones
categoria: Funciones
practica: 1
ejercicio: 31
subejercicio: b
---

# Ejercicio 31b

Dadas las funciones
$$f: \mathbb{R} \to \mathbb{R}, f(x) = \begin{cases} x^2 & \text{si } x < 7 \\ 2x-1 & \text{si } x \ge 7 \end{cases}$$
$$g: \mathbb{N} \to \mathbb{R}, g(n)=\sqrt{n}$$

Hallar, si existen, todos los $n \in \mathbb{N}$ tales que $(f \circ g)(n) = 13$ y todos los $m \in \mathbb{N}$ tales que $(f \circ g)(m) = 15$.

## Resolución

La composición $(f \circ g)(n)$ se define como $f(g(n)) = f(\sqrt{n})$. Dependiendo del valor de $\sqrt{n}$, aplicaremos una u otra rama de $f$.

### 1. Hallar $n \in \mathbb{N}$ tales que $(f \circ g)(n) = 13$

**Caso 1: $\sqrt{n} < 7$**
En este caso, $f(\sqrt{n}) = (\sqrt{n})^2 = n$.
Planteamos la ecuación: $n = 13$.
Verificamos la condición del caso: ¿$\sqrt{13} < 7$? Sí, ya que $13 < 49$.
Por lo tanto, **$n = 13$** es una solución.

**Caso 2: $\sqrt{n} \ge 7$**
En este caso, $f(\sqrt{n}) = 2\sqrt{n} - 1$.
Planteamos la ecuación: $2\sqrt{n} - 1 = 13 \implies 2\sqrt{n} = 14 \implies \sqrt{n} = 7 \implies n = 49$.
Verificamos la condición del caso: ¿$\sqrt{49} \ge 7$? Sí, ya que $7 \ge 7$.
Por lo tanto, **$n = 49$** es una solución.

**Soluciones para 13:** $\{13, 49\}$.

---

### 2. Hallar $m \in \mathbb{N}$ tales que $(f \circ g)(m) = 15$

**Caso 1: $\sqrt{m} < 7$**
En este caso, $f(\sqrt{m}) = (\sqrt{m})^2 = m$.
Planteamos la ecuación: $m = 15$.
Verificamos la condición del caso: ¿$\sqrt{15} < 7$? Sí, ya que $15 < 49$.
Por lo tanto, **$m = 15$** es una solución.

**Caso 2: $\sqrt{m} \ge 7$**
En este caso, $f(\sqrt{m}) = 2\sqrt{m} - 1$.
Planteamos la ecuación: $2\sqrt{m} - 1 = 15 \implies 2\sqrt{m} = 16 \implies \sqrt{m} = 8 \implies m = 64$.
Verificamos la condición del caso: ¿$\sqrt{64} \ge 7$? Sí, ya que $8 \ge 7$.
Por lo tanto, **$m = 64$** es una solución.

**Soluciones para 15:** $\{15, 64\}$.

## Bibliografía
- {puddu2012conjuntos}
- {uba2017fasciculo9}
